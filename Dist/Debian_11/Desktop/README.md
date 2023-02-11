Debian 11 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Debian 11.

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

Total: 2685

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | P9X79                       | [01e8662b39](https://linux-hardware.org/?probe=01e8662b39) | Feb 01, 2023 |
| Gigabyte      | X299 AORUS Gaming 3-CF      | [775a993b3a](https://linux-hardware.org/?probe=775a993b3a) | Feb 01, 2023 |
| Gigabyte      | Z690M DS3H DDR4             | [8f858cb9b9](https://linux-hardware.org/?probe=8f858cb9b9) | Jan 31, 2023 |
| MSI           | 870A-G54                    | [0aaa012de5](https://linux-hardware.org/?probe=0aaa012de5) | Jan 31, 2023 |
| Gigabyte      | P85-D3                      | [7e25d19fae](https://linux-hardware.org/?probe=7e25d19fae) | Jan 31, 2023 |
| ASRock        | G31M-VS2                    | [e12dd528ea](https://linux-hardware.org/?probe=e12dd528ea) | Jan 31, 2023 |
| MSI           | H81M-E34                    | [19b8f90522](https://linux-hardware.org/?probe=19b8f90522) | Jan 31, 2023 |
| ASUSTek       | H61M-A/BR                   | [b6a73bd22e](https://linux-hardware.org/?probe=b6a73bd22e) | Jan 30, 2023 |
| ASUSTek       | H61M-A/BR                   | [0ae96c2bbc](https://linux-hardware.org/?probe=0ae96c2bbc) | Jan 30, 2023 |
| NetGear       | ReadyDATA 5200              | [74a68eba33](https://linux-hardware.org/?probe=74a68eba33) | Jan 30, 2023 |
| ASUSTek       | P8H61-MX                    | [f13f4da766](https://linux-hardware.org/?probe=f13f4da766) | Jan 30, 2023 |
| HP            | 0A64h                       | [da7b36ad47](https://linux-hardware.org/?probe=da7b36ad47) | Jan 30, 2023 |
| Dell          | 02YRK5 A02                  | [d6faeebd74](https://linux-hardware.org/?probe=d6faeebd74) | Jan 29, 2023 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | [55c3e9597c](https://linux-hardware.org/?probe=55c3e9597c) | Jan 29, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | [6b634c85e8](https://linux-hardware.org/?probe=6b634c85e8) | Jan 29, 2023 |
| ASUSTek       | P8H67                       | [c6163491b5](https://linux-hardware.org/?probe=c6163491b5) | Jan 29, 2023 |
| Medion        | TJ4125                      | [5fb5d01ae9](https://linux-hardware.org/?probe=5fb5d01ae9) | Jan 29, 2023 |
| Gigabyte      | 8IPE1000-G/L                | [6f83e8b57d](https://linux-hardware.org/?probe=6f83e8b57d) | Jan 29, 2023 |
| Gigabyte      | M61PME-S2                   | [8227150e0d](https://linux-hardware.org/?probe=8227150e0d) | Jan 29, 2023 |
| Gigabyte      | M61PME-S2                   | [813f01976d](https://linux-hardware.org/?probe=813f01976d) | Jan 29, 2023 |
| ASRock        | B550 Pro4                   | [eaed78d213](https://linux-hardware.org/?probe=eaed78d213) | Jan 28, 2023 |
| Dell          | 0F8098                      | [d6066c739e](https://linux-hardware.org/?probe=d6066c739e) | Jan 28, 2023 |
| ASRock        | B550 Pro4                   | [5fa28ba14d](https://linux-hardware.org/?probe=5fa28ba14d) | Jan 28, 2023 |
| ASUSTek       | B85M-G                      | [4a83dc2dc2](https://linux-hardware.org/?probe=4a83dc2dc2) | Jan 27, 2023 |
| MSI           | B365M PRO-VDH               | [d5bbfc18d5](https://linux-hardware.org/?probe=d5bbfc18d5) | Jan 27, 2023 |
| AZW           | MINI S                      | [ce5e6b1504](https://linux-hardware.org/?probe=ce5e6b1504) | Jan 26, 2023 |
| HP            | 805D                        | [b1996094a9](https://linux-hardware.org/?probe=b1996094a9) | Jan 26, 2023 |
| Inventec      | D CLASS A02                 | [2e70086887](https://linux-hardware.org/?probe=2e70086887) | Jan 25, 2023 |
| ASUSTek       | P8H61-M LX2                 | [dee0143024](https://linux-hardware.org/?probe=dee0143024) | Jan 25, 2023 |
| Gigabyte      | B450M DS3H V2               | [90d383c54e](https://linux-hardware.org/?probe=90d383c54e) | Jan 25, 2023 |
| ASUSTek       | H110M-R                     | [e4b50b33a2](https://linux-hardware.org/?probe=e4b50b33a2) | Jan 25, 2023 |
| MSI           | H110M PRO-VD                | [e0eefbde94](https://linux-hardware.org/?probe=e0eefbde94) | Jan 25, 2023 |
| Gigabyte      | B450M DS3H-CF               | [e2d354b9c5](https://linux-hardware.org/?probe=e2d354b9c5) | Jan 25, 2023 |
| Dell          | 0K3CM7 A00                  | [d3cc219bf7](https://linux-hardware.org/?probe=d3cc219bf7) | Jan 24, 2023 |
| MSI           | H97 PC Mate                 | [d00ec3c042](https://linux-hardware.org/?probe=d00ec3c042) | Jan 24, 2023 |
| ECS           | G31T-M9                     | [59747c81ca](https://linux-hardware.org/?probe=59747c81ca) | Jan 24, 2023 |
| ASRock        | 990FX Killer                | [b6bd3a3bdb](https://linux-hardware.org/?probe=b6bd3a3bdb) | Jan 23, 2023 |
| MSI           | 870A-G54                    | [b1baf04990](https://linux-hardware.org/?probe=b1baf04990) | Jan 23, 2023 |
| Dell          | 09M8Y8 A01                  | [3f3b6c888d](https://linux-hardware.org/?probe=3f3b6c888d) | Jan 23, 2023 |
| Gigabyte      | P85-D3                      | [69164f2a61](https://linux-hardware.org/?probe=69164f2a61) | Jan 23, 2023 |
| ASUSTek       | PRIME X399-A                | [4687e8d062](https://linux-hardware.org/?probe=4687e8d062) | Jan 22, 2023 |
| Intel         | JSL MRD                     | [39dc5a7f96](https://linux-hardware.org/?probe=39dc5a7f96) | Jan 22, 2023 |
| Lenovo        | ThinkCentre M57e 7066W57    | [3ddcdbb616](https://linux-hardware.org/?probe=3ddcdbb616) | Jan 22, 2023 |
| Dell          | 0KRC95 A02                  | [ef532b60e6](https://linux-hardware.org/?probe=ef532b60e6) | Jan 21, 2023 |
| Biostar       | H310MHP                     | [21de314a44](https://linux-hardware.org/?probe=21de314a44) | Jan 21, 2023 |
| ASRock        | H61M-VG3                    | [c9d6e1cbb1](https://linux-hardware.org/?probe=c9d6e1cbb1) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [046504c970](https://linux-hardware.org/?probe=046504c970) | Jan 21, 2023 |
| DFI           | CR101-CST                   | [604ce5b10f](https://linux-hardware.org/?probe=604ce5b10f) | Jan 21, 2023 |
| ASUSTek       | P5QL PRO                    | [9f700f7e19](https://linux-hardware.org/?probe=9f700f7e19) | Jan 21, 2023 |
| Intel         | DH77EB AAG39073-304         | [4af2ea2f7f](https://linux-hardware.org/?probe=4af2ea2f7f) | Jan 20, 2023 |
| Dell          | 0VC8RJ X02                  | [313ea92e9c](https://linux-hardware.org/?probe=313ea92e9c) | Jan 20, 2023 |
| Gigabyte      | H410M H V2                  | [5767b63675](https://linux-hardware.org/?probe=5767b63675) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [28e6aeb27a](https://linux-hardware.org/?probe=28e6aeb27a) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [beec5d3864](https://linux-hardware.org/?probe=beec5d3864) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [6ff84d12be](https://linux-hardware.org/?probe=6ff84d12be) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [002a38370c](https://linux-hardware.org/?probe=002a38370c) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [bbfb85788c](https://linux-hardware.org/?probe=bbfb85788c) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | [9d6c73b1c1](https://linux-hardware.org/?probe=9d6c73b1c1) | Jan 20, 2023 |
| HP            | 3397                        | [39391f23c4](https://linux-hardware.org/?probe=39391f23c4) | Jan 20, 2023 |
| HP            | 3397                        | [7b05c1fdf9](https://linux-hardware.org/?probe=7b05c1fdf9) | Jan 20, 2023 |
| AZW           | SEi                         | [257b104c3a](https://linux-hardware.org/?probe=257b104c3a) | Jan 20, 2023 |
| Gigabyte      | Z690I A ULTRA LITE D4       | [f7cac38f4a](https://linux-hardware.org/?probe=f7cac38f4a) | Jan 20, 2023 |
| AZW           | SEi                         | [481932390b](https://linux-hardware.org/?probe=481932390b) | Jan 20, 2023 |
| ASUSTek       | P5KPL-CM                    | [b9f1f115ba](https://linux-hardware.org/?probe=b9f1f115ba) | Jan 20, 2023 |
| Gigabyte      | Z690I A ULTRA LITE D4       | [abcfca9ea7](https://linux-hardware.org/?probe=abcfca9ea7) | Jan 20, 2023 |
| Lenovo        | 7033EW4                     | [fd4303de2e](https://linux-hardware.org/?probe=fd4303de2e) | Jan 20, 2023 |
| Gigabyte      | H81M-S2V                    | [76be7bde5d](https://linux-hardware.org/?probe=76be7bde5d) | Jan 19, 2023 |
| ASUSTek       | P6T                         | [ac42d5a147](https://linux-hardware.org/?probe=ac42d5a147) | Jan 19, 2023 |
| Gigabyte      | B85M-D3V                    | [285dc35475](https://linux-hardware.org/?probe=285dc35475) | Jan 19, 2023 |
| ASUSTek       | P5AD2-E-Premium             | [285c0f23f1](https://linux-hardware.org/?probe=285c0f23f1) | Jan 19, 2023 |
| ASUSTek       | P8H61-M                     | [1ffe9344ff](https://linux-hardware.org/?probe=1ffe9344ff) | Jan 18, 2023 |
| Medion        | TJ4125                      | [b4f48c3140](https://linux-hardware.org/?probe=b4f48c3140) | Jan 18, 2023 |
| Lenovo        | 7033EW4                     | [df0d8cd728](https://linux-hardware.org/?probe=df0d8cd728) | Jan 18, 2023 |
| ASRock        | A300M-STX                   | [4d726dcf9b](https://linux-hardware.org/?probe=4d726dcf9b) | Jan 17, 2023 |
| Huanan        | B75 V10.1 376               | [2703c87348](https://linux-hardware.org/?probe=2703c87348) | Jan 17, 2023 |
| ASUSTek       | PRIME H510M-K               | [f9f926e910](https://linux-hardware.org/?probe=f9f926e910) | Jan 17, 2023 |
| MSI           | H81M-E34                    | [db4a6791a0](https://linux-hardware.org/?probe=db4a6791a0) | Jan 17, 2023 |
| ASUSTek       | P5G41T-M LE                 | [31b369770d](https://linux-hardware.org/?probe=31b369770d) | Jan 17, 2023 |
| Foxconn       | nT-A3000 series FAB         | [0bdefb0a4f](https://linux-hardware.org/?probe=0bdefb0a4f) | Jan 17, 2023 |
| ASUSTek       | M2N-SLI DELUXE              | [d31aea19b2](https://linux-hardware.org/?probe=d31aea19b2) | Jan 16, 2023 |
| Intel         | DH67BL AAG10189-206         | [23e07704eb](https://linux-hardware.org/?probe=23e07704eb) | Jan 16, 2023 |
| ASRock        | J3455-ITX                   | [6746dfae39](https://linux-hardware.org/?probe=6746dfae39) | Jan 16, 2023 |
| Intel         | JSL MRD                     | [edbaf7bb5d](https://linux-hardware.org/?probe=edbaf7bb5d) | Jan 16, 2023 |
| Lenovo        | 370A SDK0J40697 WIN 3305... | [deb2b560bc](https://linux-hardware.org/?probe=deb2b560bc) | Jan 16, 2023 |
| ASRock        | J3455-ITX                   | [457c7ea5a4](https://linux-hardware.org/?probe=457c7ea5a4) | Jan 16, 2023 |
| Intel         | DH77EB AAG39073-304         | [cb3c4b1eb4](https://linux-hardware.org/?probe=cb3c4b1eb4) | Jan 16, 2023 |
| HP            | 8643 SMVB                   | [4572999070](https://linux-hardware.org/?probe=4572999070) | Jan 16, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [3b4a530695](https://linux-hardware.org/?probe=3b4a530695) | Jan 15, 2023 |
| MSI           | MS-B1711                    | [730b1e7f90](https://linux-hardware.org/?probe=730b1e7f90) | Jan 15, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [202535bce7](https://linux-hardware.org/?probe=202535bce7) | Jan 15, 2023 |
| ASUSTek       | PRIME X570-P                | [ab5933911d](https://linux-hardware.org/?probe=ab5933911d) | Jan 15, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [d1e2f08907](https://linux-hardware.org/?probe=d1e2f08907) | Jan 14, 2023 |
| HP            | ProLiant MicroServer Gen... | [8a79dd9e27](https://linux-hardware.org/?probe=8a79dd9e27) | Jan 13, 2023 |
| ASRock        | H110M-HDV R3.0              | [bed628ce8a](https://linux-hardware.org/?probe=bed628ce8a) | Jan 13, 2023 |
| Lenovo        | ThinkCentre M58p 6234A1U    | [63d74a9021](https://linux-hardware.org/?probe=63d74a9021) | Jan 13, 2023 |
| ASRock        | 970M Pro3                   | [ed62a9383e](https://linux-hardware.org/?probe=ed62a9383e) | Jan 13, 2023 |
| Medion        | TJ4125                      | [700f862aa6](https://linux-hardware.org/?probe=700f862aa6) | Jan 13, 2023 |
| HC            | HCAR357-MI V1.0             | [516f1ed052](https://linux-hardware.org/?probe=516f1ed052) | Jan 13, 2023 |
| Vestel        | 14MB24A                     | [56ee8713e8](https://linux-hardware.org/?probe=56ee8713e8) | Jan 13, 2023 |
| Vestel        | 14MB24A                     | [02c99c8c38](https://linux-hardware.org/?probe=02c99c8c38) | Jan 13, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [d7c612580f](https://linux-hardware.org/?probe=d7c612580f) | Jan 13, 2023 |
| HP            | 21EF                        | [0d5e3a9354](https://linux-hardware.org/?probe=0d5e3a9354) | Jan 12, 2023 |
| HP            | 21EF                        | [cdeab03273](https://linux-hardware.org/?probe=cdeab03273) | Jan 12, 2023 |
| ASUSTek       | P5G41T-M LX V2              | [36a8e226c5](https://linux-hardware.org/?probe=36a8e226c5) | Jan 12, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [4687ae7d43](https://linux-hardware.org/?probe=4687ae7d43) | Jan 12, 2023 |
| Gigabyte      | X570 GAMING X               | [bb85f0bdc7](https://linux-hardware.org/?probe=bb85f0bdc7) | Jan 12, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d93218978e](https://linux-hardware.org/?probe=d93218978e) | Jan 12, 2023 |
| MSI           | B350 PC MATE                | [f235ff785b](https://linux-hardware.org/?probe=f235ff785b) | Jan 12, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [25bd789598](https://linux-hardware.org/?probe=25bd789598) | Jan 12, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [c040acffcf](https://linux-hardware.org/?probe=c040acffcf) | Jan 12, 2023 |
| MSI           | X470 GAMING PLUS            | [ba153350d8](https://linux-hardware.org/?probe=ba153350d8) | Jan 11, 2023 |
| ASRock        | X300-ITX                    | [9e74676ba4](https://linux-hardware.org/?probe=9e74676ba4) | Jan 11, 2023 |
| ASRockRack    | X470D4U                     | [b60a38ae60](https://linux-hardware.org/?probe=b60a38ae60) | Jan 11, 2023 |
| Gigabyte      | X570 GAMING X               | [204a5e8a8e](https://linux-hardware.org/?probe=204a5e8a8e) | Jan 11, 2023 |
| ASRockRack    | X470D4U2/1N1                | [ee2147214c](https://linux-hardware.org/?probe=ee2147214c) | Jan 11, 2023 |
| Dell          | 01XK1W A00                  | [54793acf7e](https://linux-hardware.org/?probe=54793acf7e) | Jan 11, 2023 |
| Gigabyte      | H510M H                     | [81a8002b99](https://linux-hardware.org/?probe=81a8002b99) | Jan 10, 2023 |
| Lenovo        | 1059 SDK0T76538 WIN 3556... | [a2660dcbfb](https://linux-hardware.org/?probe=a2660dcbfb) | Jan 09, 2023 |
| Techvision    | TVI7309X B0                 | [e336a260d6](https://linux-hardware.org/?probe=e336a260d6) | Jan 09, 2023 |
| Techvision    | TVI7309X B0                 | [43cc06ef1d](https://linux-hardware.org/?probe=43cc06ef1d) | Jan 09, 2023 |
| ASRockRack    | X470D4U                     | [0e51eb7caa](https://linux-hardware.org/?probe=0e51eb7caa) | Jan 09, 2023 |
| Dell          | 0HD5W2 A01                  | [a14e62fdf8](https://linux-hardware.org/?probe=a14e62fdf8) | Jan 09, 2023 |
| Acer          | Predator G3-710             | [d47ca88192](https://linux-hardware.org/?probe=d47ca88192) | Jan 09, 2023 |
| HP            | 8053                        | [b377deb121](https://linux-hardware.org/?probe=b377deb121) | Jan 09, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [92205d303f](https://linux-hardware.org/?probe=92205d303f) | Jan 08, 2023 |
| Gigabyte      | X570S I AORUS PRO AX        | [2b8206db29](https://linux-hardware.org/?probe=2b8206db29) | Jan 08, 2023 |
| Gigabyte      | X570S I AORUS PRO AX        | [68fe02a04c](https://linux-hardware.org/?probe=68fe02a04c) | Jan 08, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [0f0b86d738](https://linux-hardware.org/?probe=0f0b86d738) | Jan 07, 2023 |
| ASRock        | Q1900-ITX                   | [ac7df499e8](https://linux-hardware.org/?probe=ac7df499e8) | Jan 07, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [4ceeb719c2](https://linux-hardware.org/?probe=4ceeb719c2) | Jan 06, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [d930da3de0](https://linux-hardware.org/?probe=d930da3de0) | Jan 06, 2023 |
| MSI           | Z97 GAMING 5                | [1edff66d1a](https://linux-hardware.org/?probe=1edff66d1a) | Jan 06, 2023 |
| ASUSTek       | M5A97 R2.0                  | [982de9c98d](https://linux-hardware.org/?probe=982de9c98d) | Jan 06, 2023 |
| Dell          | 01XK1W A00                  | [bb487db79f](https://linux-hardware.org/?probe=bb487db79f) | Jan 05, 2023 |
| ELSKY         | M219FN-6C                   | [95862529f8](https://linux-hardware.org/?probe=95862529f8) | Jan 04, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | [b1771ee07c](https://linux-hardware.org/?probe=b1771ee07c) | Jan 03, 2023 |
| MSI           | MS-7519                     | [3239304aa0](https://linux-hardware.org/?probe=3239304aa0) | Jan 03, 2023 |
| Pegatron      | Maureen                     | [071cde04e9](https://linux-hardware.org/?probe=071cde04e9) | Jan 03, 2023 |
| ASUSTek       | Z170-DELUXE                 | [4a37b87ecf](https://linux-hardware.org/?probe=4a37b87ecf) | Jan 02, 2023 |
| Lenovo        | SHARKBAY NOK                | [7c72451666](https://linux-hardware.org/?probe=7c72451666) | Jan 01, 2023 |
| MSI           | B450M-A PRO MAX             | [8726e38f02](https://linux-hardware.org/?probe=8726e38f02) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [b1dc879a16](https://linux-hardware.org/?probe=b1dc879a16) | Jan 01, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | [de65f4b654](https://linux-hardware.org/?probe=de65f4b654) | Dec 31, 2022 |
| Google        | Teemo                       | [6f6671a40e](https://linux-hardware.org/?probe=6f6671a40e) | Dec 31, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [500ce7ae28](https://linux-hardware.org/?probe=500ce7ae28) | Dec 31, 2022 |
| Google        | Teemo                       | [e3c39f29da](https://linux-hardware.org/?probe=e3c39f29da) | Dec 31, 2022 |
| ASRock        | J3455-ITX                   | [4f45d532ac](https://linux-hardware.org/?probe=4f45d532ac) | Dec 30, 2022 |
| Lenovo        | ThinkStation C20 4263BA7    | [7b55955e2a](https://linux-hardware.org/?probe=7b55955e2a) | Dec 30, 2022 |
| HP            | 339A                        | [8e0b785427](https://linux-hardware.org/?probe=8e0b785427) | Dec 29, 2022 |
| ASUSTek       | PRIME B360M-C               | [c38ca6386e](https://linux-hardware.org/?probe=c38ca6386e) | Dec 29, 2022 |
| Gigabyte      | H61M-DS2                    | [50149bf9e3](https://linux-hardware.org/?probe=50149bf9e3) | Dec 29, 2022 |
| Gigabyte      | H61M-DS2                    | [b0a40a3ac0](https://linux-hardware.org/?probe=b0a40a3ac0) | Dec 29, 2022 |
| Unknown       | Unknown                     | [34b6109940](https://linux-hardware.org/?probe=34b6109940) | Dec 29, 2022 |
| ASRock        | X570 Taichi                 | [c1e5e82fbb](https://linux-hardware.org/?probe=c1e5e82fbb) | Dec 29, 2022 |
| HP            | ProLiant ML30 Gen9          | [174e7e831b](https://linux-hardware.org/?probe=174e7e831b) | Dec 28, 2022 |
| HP            | 158A                        | [c80bfd7c30](https://linux-hardware.org/?probe=c80bfd7c30) | Dec 28, 2022 |
| Lenovo        | 0B98401 WIN                 | [0f71bbaf67](https://linux-hardware.org/?probe=0f71bbaf67) | Dec 28, 2022 |
| ASRock        | J3455-ITX                   | [6e628aeb01](https://linux-hardware.org/?probe=6e628aeb01) | Dec 28, 2022 |
| ASUSTek       | PRIME B360M-K               | [48f161dfc8](https://linux-hardware.org/?probe=48f161dfc8) | Dec 27, 2022 |
| Dell          | 0M017G A00                  | [5c41315695](https://linux-hardware.org/?probe=5c41315695) | Dec 27, 2022 |
| ASRock        | H470M-HVS                   | [210f0c0375](https://linux-hardware.org/?probe=210f0c0375) | Dec 27, 2022 |
| ASRock        | Brazos                      | [f5183b395b](https://linux-hardware.org/?probe=f5183b395b) | Dec 27, 2022 |
| Dell          | 02YRK5 A02                  | [56dc5ff1b9](https://linux-hardware.org/?probe=56dc5ff1b9) | Dec 26, 2022 |
| Gigabyte      | B660M GAMING DDR4           | [2618b85414](https://linux-hardware.org/?probe=2618b85414) | Dec 26, 2022 |
| Lenovo        | ThinkStation D30 42234T7    | [6ad649ad46](https://linux-hardware.org/?probe=6ad649ad46) | Dec 26, 2022 |
| Gigabyte      | B360M H                     | [2f0d1b1c8d](https://linux-hardware.org/?probe=2f0d1b1c8d) | Dec 26, 2022 |
| ASUSTek       | PRIME A320M-K               | [d90a9cdcd3](https://linux-hardware.org/?probe=d90a9cdcd3) | Dec 26, 2022 |
| ASUSTek       | PRIME A320M-K               | [fc0eac877c](https://linux-hardware.org/?probe=fc0eac877c) | Dec 26, 2022 |
| Lenovo        | ThinkStation D30 42234T7    | [6ac63aca4f](https://linux-hardware.org/?probe=6ac63aca4f) | Dec 25, 2022 |
| HP            | ProLiant MicroServer        | [b95892f2dc](https://linux-hardware.org/?probe=b95892f2dc) | Dec 24, 2022 |
| ASUSTek       | WS C422 DC                  | [7be7c81575](https://linux-hardware.org/?probe=7be7c81575) | Dec 24, 2022 |
| ASUSTek       | WS C422 DC                  | [526414fd8f](https://linux-hardware.org/?probe=526414fd8f) | Dec 24, 2022 |
| HP            | 876C SMVB                   | [988b03aae5](https://linux-hardware.org/?probe=988b03aae5) | Dec 23, 2022 |
| ASRock        | X300M-STX                   | [3d90b10b72](https://linux-hardware.org/?probe=3d90b10b72) | Dec 22, 2022 |
| Gigabyte      | B450M DS3H-CF               | [fe4ef75450](https://linux-hardware.org/?probe=fe4ef75450) | Dec 21, 2022 |
| HP            | ProLiant MicroServer Gen... | [57182d09ed](https://linux-hardware.org/?probe=57182d09ed) | Dec 21, 2022 |
| Intel         | DQ77CP AAG67261-300         | [908f619aa7](https://linux-hardware.org/?probe=908f619aa7) | Dec 21, 2022 |
| Gigabyte      | M68MT-S2P                   | [363c106fa2](https://linux-hardware.org/?probe=363c106fa2) | Dec 21, 2022 |
| Gigabyte      | M68MT-S2P                   | [ed29442d39](https://linux-hardware.org/?probe=ed29442d39) | Dec 21, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [c4719bd0ac](https://linux-hardware.org/?probe=c4719bd0ac) | Dec 21, 2022 |
| MSI           | MS-7318                     | [4622016059](https://linux-hardware.org/?probe=4622016059) | Dec 21, 2022 |
| Intel         | DG35EC AAE29266-205         | [3cee3ad865](https://linux-hardware.org/?probe=3cee3ad865) | Dec 20, 2022 |
| Dell          | 0MN1TX A00                  | [f2ae430663](https://linux-hardware.org/?probe=f2ae430663) | Dec 20, 2022 |
| Gigabyte      | P75-D3P                     | [ff2420e759](https://linux-hardware.org/?probe=ff2420e759) | Dec 19, 2022 |
| Dell          | 09KPNV A01                  | [a4c5e58eec](https://linux-hardware.org/?probe=a4c5e58eec) | Dec 19, 2022 |
| ASRock        | N68-GS3 UCC                 | [19dad9b5b2](https://linux-hardware.org/?probe=19dad9b5b2) | Dec 19, 2022 |
| Gigabyte      | G41MT-ES2L                  | [d23b58b5da](https://linux-hardware.org/?probe=d23b58b5da) | Dec 19, 2022 |
| MSI           | A320M-A PRO MAX             | [30aec905c0](https://linux-hardware.org/?probe=30aec905c0) | Dec 19, 2022 |
| GIFA Indus... | TM-J3355-2G2L               | [526697a9d0](https://linux-hardware.org/?probe=526697a9d0) | Dec 19, 2022 |
| Apple         | Mac-F221BEC8                | [493ddb6998](https://linux-hardware.org/?probe=493ddb6998) | Dec 19, 2022 |
| IceWhale T... | ZimaBoard 216 ZMB           | [647bf0e2a7](https://linux-hardware.org/?probe=647bf0e2a7) | Dec 19, 2022 |
| Dell          | 0UY894 A02                  | [904ee2bb12](https://linux-hardware.org/?probe=904ee2bb12) | Dec 18, 2022 |
| Dell          | 06JWJY A00                  | [89ac693c2c](https://linux-hardware.org/?probe=89ac693c2c) | Dec 18, 2022 |
| ASUSTek       | M51BC                       | [78a6f49d22](https://linux-hardware.org/?probe=78a6f49d22) | Dec 18, 2022 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | [0886e650a3](https://linux-hardware.org/?probe=0886e650a3) | Dec 18, 2022 |
| Gigabyte      | X570S AERO G                | [1ec932aa3a](https://linux-hardware.org/?probe=1ec932aa3a) | Dec 17, 2022 |
| ASUSTek       | P8H67-M                     | [cf6fc033d6](https://linux-hardware.org/?probe=cf6fc033d6) | Dec 17, 2022 |
| Dell          | 0V8F20 A01                  | [d9e3649f12](https://linux-hardware.org/?probe=d9e3649f12) | Dec 16, 2022 |
| ASUSTek       | PRIME B560M-A               | [abfa3437b3](https://linux-hardware.org/?probe=abfa3437b3) | Dec 16, 2022 |
| Gigabyte      | B550M DS3H                  | [7b3f9b5af0](https://linux-hardware.org/?probe=7b3f9b5af0) | Dec 16, 2022 |
| Dell          | 0M5DCD A00                  | [f58cc5bcba](https://linux-hardware.org/?probe=f58cc5bcba) | Dec 16, 2022 |
| ASUSTek       | PRIME B560M-A               | [f43049fe6d](https://linux-hardware.org/?probe=f43049fe6d) | Dec 16, 2022 |
| HP            | 876C SMVB                   | [e214378eea](https://linux-hardware.org/?probe=e214378eea) | Dec 16, 2022 |
| ASUSTek       | Z170-DELUXE                 | [3a524796f6](https://linux-hardware.org/?probe=3a524796f6) | Dec 16, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [138cbfa0ba](https://linux-hardware.org/?probe=138cbfa0ba) | Dec 16, 2022 |
| MSI           | AM1I                        | [0ebd00e848](https://linux-hardware.org/?probe=0ebd00e848) | Dec 16, 2022 |
| MSI           | AM1I                        | [97dfa5ebf8](https://linux-hardware.org/?probe=97dfa5ebf8) | Dec 16, 2022 |
| HP            | 876C SMVB                   | [c704265799](https://linux-hardware.org/?probe=c704265799) | Dec 15, 2022 |
| HP            | 876C SMVB                   | [3a6fdcc184](https://linux-hardware.org/?probe=3a6fdcc184) | Dec 15, 2022 |
| ASRock        | H470M-HVS                   | [3c6c7c5eb5](https://linux-hardware.org/?probe=3c6c7c5eb5) | Dec 15, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [4651fa0db3](https://linux-hardware.org/?probe=4651fa0db3) | Dec 14, 2022 |
| ASRockRack    | X470D4U2-2T                 | [47c18717db](https://linux-hardware.org/?probe=47c18717db) | Dec 14, 2022 |
| ASRock        | B550M Steel Legend          | [516d6f7f12](https://linux-hardware.org/?probe=516d6f7f12) | Dec 14, 2022 |
| Dell          | 0N185P A02                  | [32d47ba775](https://linux-hardware.org/?probe=32d47ba775) | Dec 14, 2022 |
| Dell          | 0N185P A02                  | [ee28e5efa8](https://linux-hardware.org/?probe=ee28e5efa8) | Dec 14, 2022 |
| Gigabyte      | GA-MA785GMT-UD2H            | [9e8ad3aefd](https://linux-hardware.org/?probe=9e8ad3aefd) | Dec 14, 2022 |
| Dell          | 0H8367                      | [7fff4bfffc](https://linux-hardware.org/?probe=7fff4bfffc) | Dec 14, 2022 |
| Gigabyte      | GA-MA785GMT-UD2H            | [bdbf3d8792](https://linux-hardware.org/?probe=bdbf3d8792) | Dec 14, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [049fef0294](https://linux-hardware.org/?probe=049fef0294) | Dec 14, 2022 |
| Gigabyte      | Z87M-D3H                    | [88c6ca8956](https://linux-hardware.org/?probe=88c6ca8956) | Dec 14, 2022 |
| MSI           | MS-7318                     | [420ae8857b](https://linux-hardware.org/?probe=420ae8857b) | Dec 13, 2022 |
| ASUSTek       | A88XM-A                     | [64176404e2](https://linux-hardware.org/?probe=64176404e2) | Dec 13, 2022 |
| MSI           | MS-B1591                    | [33cb107fb9](https://linux-hardware.org/?probe=33cb107fb9) | Dec 13, 2022 |
| ASUSTek       | P7H55-M SI                  | [973e367765](https://linux-hardware.org/?probe=973e367765) | Dec 13, 2022 |
| NetGear       | ReadyDATA 5200              | [2db45cfb13](https://linux-hardware.org/?probe=2db45cfb13) | Dec 13, 2022 |
| ASUSTek       | STRIX H270F GAMING          | [3b9b8bb589](https://linux-hardware.org/?probe=3b9b8bb589) | Dec 12, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [d1b0bc1c03](https://linux-hardware.org/?probe=d1b0bc1c03) | Dec 12, 2022 |
| HP            | 1850                        | [af4f26481a](https://linux-hardware.org/?probe=af4f26481a) | Dec 11, 2022 |
| HP            | 1850                        | [28b194e897](https://linux-hardware.org/?probe=28b194e897) | Dec 11, 2022 |
| Gigabyte      | A320M-H-CF                  | [7d4b5e1c20](https://linux-hardware.org/?probe=7d4b5e1c20) | Dec 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [822e79aa3e](https://linux-hardware.org/?probe=822e79aa3e) | Dec 11, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [e3cecbe4be](https://linux-hardware.org/?probe=e3cecbe4be) | Dec 11, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [32e7431c24](https://linux-hardware.org/?probe=32e7431c24) | Dec 11, 2022 |
| Supermicro    | C7SIM-Q                     | [76cf2b62db](https://linux-hardware.org/?probe=76cf2b62db) | Dec 11, 2022 |
| ASRock        | X370 Killer SLI/ac          | [83fc85f9e5](https://linux-hardware.org/?probe=83fc85f9e5) | Dec 10, 2022 |
| Dell          | 0VHWTR A02                  | [b489057ccc](https://linux-hardware.org/?probe=b489057ccc) | Dec 10, 2022 |
| HP            | 876C SMVB                   | [d6211ccceb](https://linux-hardware.org/?probe=d6211ccceb) | Dec 10, 2022 |
| HP            | 339A                        | [ca1d494630](https://linux-hardware.org/?probe=ca1d494630) | Dec 10, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [a80714c4ec](https://linux-hardware.org/?probe=a80714c4ec) | Dec 09, 2022 |
| Gigabyte      | B450 AORUS M                | [bb3d3b636f](https://linux-hardware.org/?probe=bb3d3b636f) | Dec 09, 2022 |
| Gigabyte      | 990FXA-UD3                  | [b2aa17a680](https://linux-hardware.org/?probe=b2aa17a680) | Dec 09, 2022 |
| Gigabyte      | 990FXA-UD3                  | [416ad70d66](https://linux-hardware.org/?probe=416ad70d66) | Dec 08, 2022 |
| Acer          | Veriton N2620G              | [2c4bd5a093](https://linux-hardware.org/?probe=2c4bd5a093) | Dec 08, 2022 |
| Dell          | 0VHWTR A02                  | [5b85a90055](https://linux-hardware.org/?probe=5b85a90055) | Dec 08, 2022 |
| ASRock        | H470M-HVS                   | [2f4b3b1185](https://linux-hardware.org/?probe=2f4b3b1185) | Dec 08, 2022 |
| Unknown       | Unknown                     | [3a5aa82738](https://linux-hardware.org/?probe=3a5aa82738) | Dec 07, 2022 |
| Dell          | 0RM5DR A00                  | [cd67b584bb](https://linux-hardware.org/?probe=cd67b584bb) | Dec 07, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [611fd80398](https://linux-hardware.org/?probe=611fd80398) | Dec 07, 2022 |
| Unknown       | Unknown                     | [4d8d2c3a47](https://linux-hardware.org/?probe=4d8d2c3a47) | Dec 07, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | [7766e8d043](https://linux-hardware.org/?probe=7766e8d043) | Dec 07, 2022 |
| MSI           | B550-A PRO                  | [eb1b8bc98a](https://linux-hardware.org/?probe=eb1b8bc98a) | Dec 06, 2022 |
| Dell          | 0XHGV1 A00                  | [9b9778c525](https://linux-hardware.org/?probe=9b9778c525) | Dec 06, 2022 |
| Dell          | 01XK1W A00                  | [e2ec28bd7c](https://linux-hardware.org/?probe=e2ec28bd7c) | Dec 06, 2022 |
| MSI           | H110M PRO-VD                | [64c80c03cf](https://linux-hardware.org/?probe=64c80c03cf) | Dec 05, 2022 |
| Gigabyte      | Z97-HD3                     | [9b7999b50d](https://linux-hardware.org/?probe=9b7999b50d) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [b7b2f976e8](https://linux-hardware.org/?probe=b7b2f976e8) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [4d38cbb41a](https://linux-hardware.org/?probe=4d38cbb41a) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [7428311d73](https://linux-hardware.org/?probe=7428311d73) | Dec 04, 2022 |
| Dell          | 0K3CM7 A00                  | [9ee4df50e7](https://linux-hardware.org/?probe=9ee4df50e7) | Dec 04, 2022 |
| ASUSTek       | LEUCITE3                    | [4f28bb5933](https://linux-hardware.org/?probe=4f28bb5933) | Dec 04, 2022 |
| HP            | 339A                        | [91ed08d2a9](https://linux-hardware.org/?probe=91ed08d2a9) | Dec 04, 2022 |
| ASUSTek       | PRIME A320M-A               | [91d50f0379](https://linux-hardware.org/?probe=91d50f0379) | Dec 03, 2022 |
| Lenovo        | SHARKBAY NOK                | [c7cf7a1604](https://linux-hardware.org/?probe=c7cf7a1604) | Dec 03, 2022 |
| Lenovo        | SHARKBAY NOK                | [67c278b32e](https://linux-hardware.org/?probe=67c278b32e) | Dec 03, 2022 |
| MSI           | B450M BAZOOKA PLUS          | [dc890ad363](https://linux-hardware.org/?probe=dc890ad363) | Dec 03, 2022 |
| MSI           | B450M BAZOOKA PLUS          | [a087ddb18f](https://linux-hardware.org/?probe=a087ddb18f) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [61e955b5a6](https://linux-hardware.org/?probe=61e955b5a6) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [dc9c0686e7](https://linux-hardware.org/?probe=dc9c0686e7) | Dec 03, 2022 |
| Dell          | 0GY6Y8 A01                  | [f86e02dee0](https://linux-hardware.org/?probe=f86e02dee0) | Dec 03, 2022 |
| ASUSTek       | Z170I PRO GAMING            | [bf8f5e2683](https://linux-hardware.org/?probe=bf8f5e2683) | Dec 03, 2022 |
| Intel         | DP45SG AAE27733-401         | [bc19b3f6a3](https://linux-hardware.org/?probe=bc19b3f6a3) | Dec 02, 2022 |
| Lenovo        | 3753 SDK0T76479 WIN 3423... | [5476b73cb7](https://linux-hardware.org/?probe=5476b73cb7) | Dec 02, 2022 |
| Lenovo        | 3753 SDK0T76479 WIN 3423... | [6d07106192](https://linux-hardware.org/?probe=6d07106192) | Dec 02, 2022 |
| Lenovo        | SHARKBAY NOK                | [e03c6b53ed](https://linux-hardware.org/?probe=e03c6b53ed) | Dec 01, 2022 |
| ASUSTek       | P5B                         | [44f13beada](https://linux-hardware.org/?probe=44f13beada) | Dec 01, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | [f0dba35258](https://linux-hardware.org/?probe=f0dba35258) | Dec 01, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | [baa969bf8b](https://linux-hardware.org/?probe=baa969bf8b) | Nov 30, 2022 |
| Pegatron      | BYT-X1                      | [edadb85201](https://linux-hardware.org/?probe=edadb85201) | Nov 30, 2022 |
| Pegatron      | BYT-X1                      | [b248df8671](https://linux-hardware.org/?probe=b248df8671) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX Z490-A GAMING     | [dc5ec6eb84](https://linux-hardware.org/?probe=dc5ec6eb84) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [6b21f343c3](https://linux-hardware.org/?probe=6b21f343c3) | Nov 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | [952c3681c0](https://linux-hardware.org/?probe=952c3681c0) | Nov 30, 2022 |
| Gigabyte      | B450 AORUS M                | [3e3ccd1471](https://linux-hardware.org/?probe=3e3ccd1471) | Nov 30, 2022 |
| MSI           | B560M-A PRO                 | [81bf84e7e5](https://linux-hardware.org/?probe=81bf84e7e5) | Nov 29, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [9dd6019148](https://linux-hardware.org/?probe=9dd6019148) | Nov 29, 2022 |
| BESSTAR Te... | UM700                       | [a97334be81](https://linux-hardware.org/?probe=a97334be81) | Nov 29, 2022 |
| Gigabyte      | B450M DS3H-CF               | [eae94e440a](https://linux-hardware.org/?probe=eae94e440a) | Nov 29, 2022 |
| ASUSTek       | P5KPL-CM                    | [a20e18af73](https://linux-hardware.org/?probe=a20e18af73) | Nov 29, 2022 |
| ASRock        | H510M-HDV                   | [03a1675c85](https://linux-hardware.org/?probe=03a1675c85) | Nov 29, 2022 |
| Gigabyte      | F2A55M-HD2                  | [8b3da34947](https://linux-hardware.org/?probe=8b3da34947) | Nov 28, 2022 |
| ASRock        | B450M Pro4-F                | [8d0514a0df](https://linux-hardware.org/?probe=8d0514a0df) | Nov 28, 2022 |
| ECS           | H61H2-M13                   | [88988d4d0d](https://linux-hardware.org/?probe=88988d4d0d) | Nov 28, 2022 |
| Dell          | 0K3CM7 A00                  | [076eeadd80](https://linux-hardware.org/?probe=076eeadd80) | Nov 28, 2022 |
| HP            | 212B                        | [53471968c2](https://linux-hardware.org/?probe=53471968c2) | Nov 28, 2022 |
| Dell          | 05XGC8 A00                  | [e0e0efb9be](https://linux-hardware.org/?probe=e0e0efb9be) | Nov 27, 2022 |
| Dell          | 0D24M8 A00                  | [c58c83e367](https://linux-hardware.org/?probe=c58c83e367) | Nov 26, 2022 |
| Dell          | 0D24M8 A00                  | [85b508d6d3](https://linux-hardware.org/?probe=85b508d6d3) | Nov 26, 2022 |
| Dell          | 05XGC8 A00                  | [6ea1a60122](https://linux-hardware.org/?probe=6ea1a60122) | Nov 26, 2022 |
| Gigabyte      | B250-FinTech-CF             | [fcc81ea02b](https://linux-hardware.org/?probe=fcc81ea02b) | Nov 24, 2022 |
| ASUSTek       | P5Q3                        | [655065ee03](https://linux-hardware.org/?probe=655065ee03) | Nov 24, 2022 |
| Lenovo        | 312A NOK                    | [94cdaff2c9](https://linux-hardware.org/?probe=94cdaff2c9) | Nov 24, 2022 |
| Gigabyte      | 990FXA-UD3                  | [38aca80776](https://linux-hardware.org/?probe=38aca80776) | Nov 24, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [c0ce9a3ff3](https://linux-hardware.org/?probe=c0ce9a3ff3) | Nov 23, 2022 |
| MSI           | MAG B550 TORPEDO            | [ca3bcfa403](https://linux-hardware.org/?probe=ca3bcfa403) | Nov 23, 2022 |
| Gigabyte      | G31M-ES2L                   | [e8ab5ad410](https://linux-hardware.org/?probe=e8ab5ad410) | Nov 23, 2022 |
| ASRock        | H410M-HVS R2.0              | [3f381f9fa3](https://linux-hardware.org/?probe=3f381f9fa3) | Nov 23, 2022 |
| ASUSTek       | PRIME Z270-P                | [0e778da8b6](https://linux-hardware.org/?probe=0e778da8b6) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [6d50058ef8](https://linux-hardware.org/?probe=6d50058ef8) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [f6a783a27a](https://linux-hardware.org/?probe=f6a783a27a) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [423fbc1fa0](https://linux-hardware.org/?probe=423fbc1fa0) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [debc5b7ab9](https://linux-hardware.org/?probe=debc5b7ab9) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [dc53077baa](https://linux-hardware.org/?probe=dc53077baa) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [856bb3def2](https://linux-hardware.org/?probe=856bb3def2) | Nov 22, 2022 |
| Foxconn       | H61MXL/H61MXL-K             | [d140a0f503](https://linux-hardware.org/?probe=d140a0f503) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [ee55108218](https://linux-hardware.org/?probe=ee55108218) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [ec03d1b050](https://linux-hardware.org/?probe=ec03d1b050) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [1f2a4089cc](https://linux-hardware.org/?probe=1f2a4089cc) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [4190bbb2d8](https://linux-hardware.org/?probe=4190bbb2d8) | Nov 22, 2022 |
| ECS           | H61H2-M13                   | [570a11d74b](https://linux-hardware.org/?probe=570a11d74b) | Nov 22, 2022 |
| Gigabyte      | G41M-ES2L                   | [404927f4cc](https://linux-hardware.org/?probe=404927f4cc) | Nov 22, 2022 |
| ASUSTek       | M4A78T-E                    | [aef32a0e69](https://linux-hardware.org/?probe=aef32a0e69) | Nov 22, 2022 |
| Dell          | 05DN3X A00                  | [f15eef78fa](https://linux-hardware.org/?probe=f15eef78fa) | Nov 22, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [dba99c363e](https://linux-hardware.org/?probe=dba99c363e) | Nov 20, 2022 |
| Intel         | JSL MRD                     | [469567b71f](https://linux-hardware.org/?probe=469567b71f) | Nov 20, 2022 |
| Dell          | 0WPMFG A00                  | [8b3a3dc37f](https://linux-hardware.org/?probe=8b3a3dc37f) | Nov 20, 2022 |
| Acer          | Nitro N50-620               | [ecd8e9ec1b](https://linux-hardware.org/?probe=ecd8e9ec1b) | Nov 20, 2022 |
| Intel         | JSL MRD                     | [e8171566d3](https://linux-hardware.org/?probe=e8171566d3) | Nov 19, 2022 |
| Gigabyte      | G31M-ES2L                   | [3e3d8f727c](https://linux-hardware.org/?probe=3e3d8f727c) | Nov 19, 2022 |
| Dell          | 02YRK5 A02                  | [da08e08dec](https://linux-hardware.org/?probe=da08e08dec) | Nov 18, 2022 |
| MSI           | H510M-A PRO                 | [e913feb821](https://linux-hardware.org/?probe=e913feb821) | Nov 18, 2022 |
| MSI           | MAG B550M MORTAR            | [57c6327e27](https://linux-hardware.org/?probe=57c6327e27) | Nov 18, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d1d9ddf9f3](https://linux-hardware.org/?probe=d1d9ddf9f3) | Nov 18, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [da04bee118](https://linux-hardware.org/?probe=da04bee118) | Nov 18, 2022 |
| ASUSTek       | PRIME Z690-A                | [06a234be2c](https://linux-hardware.org/?probe=06a234be2c) | Nov 17, 2022 |
| ASUSTek       | P6T DELUXE V2               | [550bd99088](https://linux-hardware.org/?probe=550bd99088) | Nov 17, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [b3e809f3d2](https://linux-hardware.org/?probe=b3e809f3d2) | Nov 17, 2022 |
| Dell          | 09KPNV A01                  | [b21e07c887](https://linux-hardware.org/?probe=b21e07c887) | Nov 16, 2022 |
| GuoGuang      | IC2M1028N-3                 | [32351ceb62](https://linux-hardware.org/?probe=32351ceb62) | Nov 16, 2022 |
| Gigabyte      | H61M-DS2                    | [757a1066ff](https://linux-hardware.org/?probe=757a1066ff) | Nov 16, 2022 |
| ASUSTek       | P8Z68-V LX                  | [a3c41dcc96](https://linux-hardware.org/?probe=a3c41dcc96) | Nov 16, 2022 |
| Gigabyte      | P75-D3                      | [02bdf99508](https://linux-hardware.org/?probe=02bdf99508) | Nov 16, 2022 |
| ASRock        | J3455-ITX                   | [71c99edeb1](https://linux-hardware.org/?probe=71c99edeb1) | Nov 16, 2022 |
| ASRock        | FM2A68M-HD+                 | [e907b4c718](https://linux-hardware.org/?probe=e907b4c718) | Nov 15, 2022 |
| Gigabyte      | A320M-S2H-CF                | [c3cacc3ed6](https://linux-hardware.org/?probe=c3cacc3ed6) | Nov 15, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [ee8a80240d](https://linux-hardware.org/?probe=ee8a80240d) | Nov 15, 2022 |
| ASRock        | B450M-HDV R4.0              | [a46c1d62cf](https://linux-hardware.org/?probe=a46c1d62cf) | Nov 15, 2022 |
| ASRock        | H470M-HVS                   | [e69c2f0da4](https://linux-hardware.org/?probe=e69c2f0da4) | Nov 15, 2022 |
| Intel         | DH77KC AAG39641-400         | [137906fffe](https://linux-hardware.org/?probe=137906fffe) | Nov 15, 2022 |
| ASUSTek       | B85M-G                      | [2029195495](https://linux-hardware.org/?probe=2029195495) | Nov 14, 2022 |
| Lenovo        | ThinkServer TS440           | [9fe9bc94a0](https://linux-hardware.org/?probe=9fe9bc94a0) | Nov 14, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [28df02c741](https://linux-hardware.org/?probe=28df02c741) | Nov 14, 2022 |
| Gigabyte      | P75-D3                      | [37f9da1b7f](https://linux-hardware.org/?probe=37f9da1b7f) | Nov 14, 2022 |
| ASUSTek       | B85M-G                      | [277739769b](https://linux-hardware.org/?probe=277739769b) | Nov 14, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [53a532435e](https://linux-hardware.org/?probe=53a532435e) | Nov 14, 2022 |
| ASUSTek       | PRIME H310M-A R2.0          | [80cce966ce](https://linux-hardware.org/?probe=80cce966ce) | Nov 14, 2022 |
| Gigabyte      | A320M-H-CF                  | [2a6473f450](https://linux-hardware.org/?probe=2a6473f450) | Nov 13, 2022 |
| ASUSTek       | H81M-K                      | [d7ae86ad73](https://linux-hardware.org/?probe=d7ae86ad73) | Nov 13, 2022 |
| Gigabyte      | GA-MA770-UD3                | [d31168230f](https://linux-hardware.org/?probe=d31168230f) | Nov 13, 2022 |
| ASUSTek       | PRIME H310M-A R2.0          | [4788a2a91d](https://linux-hardware.org/?probe=4788a2a91d) | Nov 13, 2022 |
| Gigabyte      | Z590 UD AC                  | [57952c1512](https://linux-hardware.org/?probe=57952c1512) | Nov 13, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [dc2a41e0ee](https://linux-hardware.org/?probe=dc2a41e0ee) | Nov 12, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [e69a98ce67](https://linux-hardware.org/?probe=e69a98ce67) | Nov 11, 2022 |
| ASRock        | H470M-HVS                   | [b81b19a472](https://linux-hardware.org/?probe=b81b19a472) | Nov 11, 2022 |
| Gigabyte      | H61M-D2-B3                  | [46ee069dd8](https://linux-hardware.org/?probe=46ee069dd8) | Nov 11, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [524b1115eb](https://linux-hardware.org/?probe=524b1115eb) | Nov 11, 2022 |
| Apple         | Mac-F4208DC8 PVT            | [45dc316bea](https://linux-hardware.org/?probe=45dc316bea) | Nov 10, 2022 |
| ASUSTek       | M4A78T-E                    | [a885b61478](https://linux-hardware.org/?probe=a885b61478) | Nov 10, 2022 |
| ASUSTek       | M4A78T-E                    | [475ad820cd](https://linux-hardware.org/?probe=475ad820cd) | Nov 10, 2022 |
| Gigabyte      | B75M-D3H                    | [6dd51f8707](https://linux-hardware.org/?probe=6dd51f8707) | Nov 10, 2022 |
| Gigabyte      | X570 UD                     | [29641e8b7c](https://linux-hardware.org/?probe=29641e8b7c) | Nov 09, 2022 |
| ASUSTek       | A88XM-PLUS                  | [e6eee311ea](https://linux-hardware.org/?probe=e6eee311ea) | Nov 08, 2022 |
| ASRock        | FM2A68M-HD+                 | [a90c14df17](https://linux-hardware.org/?probe=a90c14df17) | Nov 08, 2022 |
| ASUSTek       | H110-PLUS                   | [4d260267d7](https://linux-hardware.org/?probe=4d260267d7) | Nov 06, 2022 |
| ASUSTek       | H110-PLUS                   | [789df18cfb](https://linux-hardware.org/?probe=789df18cfb) | Nov 06, 2022 |
| Intel         | DQ67SW AAG12527-310         | [97d0b022d2](https://linux-hardware.org/?probe=97d0b022d2) | Nov 05, 2022 |
| Foxconn       | A88GMV                      | [1391b33f62](https://linux-hardware.org/?probe=1391b33f62) | Nov 05, 2022 |
| ASUSTek       | X99-DELUXE                  | [ab4089c760](https://linux-hardware.org/?probe=ab4089c760) | Nov 04, 2022 |
| ASUSTek       | X99-E WS/USB                | [7a65820be2](https://linux-hardware.org/?probe=7a65820be2) | Nov 04, 2022 |
| Dell          | 0200DY A01                  | [a473b71b4e](https://linux-hardware.org/?probe=a473b71b4e) | Nov 03, 2022 |
| MSI           | H510M PRO-E                 | [23fa7a2cf8](https://linux-hardware.org/?probe=23fa7a2cf8) | Nov 03, 2022 |
| Foxconn       | 2A92                        | [927cf971e9](https://linux-hardware.org/?probe=927cf971e9) | Nov 02, 2022 |
| Gigabyte      | B560M DS3H V2               | [36612b5e01](https://linux-hardware.org/?probe=36612b5e01) | Nov 02, 2022 |
| Shenzhen a... | AC1-DP                      | [754335ffe9](https://linux-hardware.org/?probe=754335ffe9) | Nov 02, 2022 |
| Dell          | 0JGM7F A00                  | [28f4800b2b](https://linux-hardware.org/?probe=28f4800b2b) | Nov 02, 2022 |
| MSI           | H110M PRO-VD                | [1fb0a79791](https://linux-hardware.org/?probe=1fb0a79791) | Nov 02, 2022 |
| Foxconn       | 2A92                        | [0898482b18](https://linux-hardware.org/?probe=0898482b18) | Nov 02, 2022 |
| ASUSTek       | PRO B460M-C                 | [dcf7112b3d](https://linux-hardware.org/?probe=dcf7112b3d) | Nov 01, 2022 |
| ASUSTek       | PRO B460M-C                 | [a333f47ffa](https://linux-hardware.org/?probe=a333f47ffa) | Nov 01, 2022 |
| Phoenix       | POULSBO                     | [177f05205b](https://linux-hardware.org/?probe=177f05205b) | Nov 01, 2022 |
| Gigabyte      | H610M H DDR4                | [b726668f90](https://linux-hardware.org/?probe=b726668f90) | Nov 01, 2022 |
| Gigabyte      | X570S AERO G                | [92fccb6716](https://linux-hardware.org/?probe=92fccb6716) | Nov 01, 2022 |
| MSI           | Z390-A PRO                  | [3eea020596](https://linux-hardware.org/?probe=3eea020596) | Nov 01, 2022 |
| MSI           | MEG Z590 ACE                | [1082f00d60](https://linux-hardware.org/?probe=1082f00d60) | Oct 31, 2022 |
| ASRock        | 960GM-VGS3 FX               | [f31f613901](https://linux-hardware.org/?probe=f31f613901) | Oct 31, 2022 |
| Intel         | DG41AN AAE92991-401         | [cd670cef3d](https://linux-hardware.org/?probe=cd670cef3d) | Oct 31, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [4179fe16d6](https://linux-hardware.org/?probe=4179fe16d6) | Oct 31, 2022 |
| ASUSTek       | PRIME X570-PRO              | [3fbcca75d5](https://linux-hardware.org/?probe=3fbcca75d5) | Oct 30, 2022 |
| HP            | 158B                        | [9c02b7fe58](https://linux-hardware.org/?probe=9c02b7fe58) | Oct 30, 2022 |
| Foxconn       | 2ADA                        | [16815dacc1](https://linux-hardware.org/?probe=16815dacc1) | Oct 29, 2022 |
| Unknown       | 775V88+                     | [f1a685b497](https://linux-hardware.org/?probe=f1a685b497) | Oct 28, 2022 |
| HP            | 3396                        | [d42479acb8](https://linux-hardware.org/?probe=d42479acb8) | Oct 28, 2022 |
| ASUSTek       | PRIME X370-PRO              | [d3cf194e94](https://linux-hardware.org/?probe=d3cf194e94) | Oct 28, 2022 |
| Apple         | Mac-F221BEC8                | [0bf03c49f7](https://linux-hardware.org/?probe=0bf03c49f7) | Oct 27, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [b682a38061](https://linux-hardware.org/?probe=b682a38061) | Oct 27, 2022 |
| MSI           | H110M PRO-VD                | [175f39979c](https://linux-hardware.org/?probe=175f39979c) | Oct 27, 2022 |
| Gigabyte      | 970A-DS3P                   | [1bc5db124b](https://linux-hardware.org/?probe=1bc5db124b) | Oct 27, 2022 |
| Lenovo        | ThinkServer TS440           | [acdfb9b02e](https://linux-hardware.org/?probe=acdfb9b02e) | Oct 26, 2022 |
| ASUSTek       | B85M-G                      | [0d3545c6aa](https://linux-hardware.org/?probe=0d3545c6aa) | Oct 26, 2022 |
| ASUSTek       | B85M-G                      | [0b8dc998a9](https://linux-hardware.org/?probe=0b8dc998a9) | Oct 26, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [c1067e423b](https://linux-hardware.org/?probe=c1067e423b) | Oct 26, 2022 |
| MSI           | Z170A GAMING M5             | [b5dcdb6844](https://linux-hardware.org/?probe=b5dcdb6844) | Oct 25, 2022 |
| MSI           | H81M-P33                    | [b0f36ae0c5](https://linux-hardware.org/?probe=b0f36ae0c5) | Oct 25, 2022 |
| MSI           | H110M PRO-VD                | [f8466185a4](https://linux-hardware.org/?probe=f8466185a4) | Oct 25, 2022 |
| Dell          | 0YJPT1 A00                  | [bb1a7da646](https://linux-hardware.org/?probe=bb1a7da646) | Oct 25, 2022 |
| Dell          | 01XK1W A00                  | [c0fb49f07a](https://linux-hardware.org/?probe=c0fb49f07a) | Oct 25, 2022 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [54710cefe5](https://linux-hardware.org/?probe=54710cefe5) | Oct 24, 2022 |
| ASUSTek       | H81M-C                      | [1deed99314](https://linux-hardware.org/?probe=1deed99314) | Oct 24, 2022 |
| ASUSTek       | M4A78T-E                    | [ee86cdac2a](https://linux-hardware.org/?probe=ee86cdac2a) | Oct 24, 2022 |
| Dell          | 0M5WNK A00                  | [fad0f2f50e](https://linux-hardware.org/?probe=fad0f2f50e) | Oct 24, 2022 |
| Lenovo        | 0x36C017AA SDK0J40700 WI... | [0d21d658ee](https://linux-hardware.org/?probe=0d21d658ee) | Oct 24, 2022 |
| Inventec      | DQ Class A02                | [f64d3223c5](https://linux-hardware.org/?probe=f64d3223c5) | Oct 24, 2022 |
| Inventec      | DQ Class A02                | [c4fddde4b6](https://linux-hardware.org/?probe=c4fddde4b6) | Oct 24, 2022 |
| Dell          | 040DDP A01                  | [083b2c218e](https://linux-hardware.org/?probe=083b2c218e) | Oct 24, 2022 |
| Biostar       | B450MH                      | [048cd18957](https://linux-hardware.org/?probe=048cd18957) | Oct 24, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | [ce3e956a0a](https://linux-hardware.org/?probe=ce3e956a0a) | Oct 24, 2022 |
| ASRock        | Z97 Anniversary             | [9c94714d56](https://linux-hardware.org/?probe=9c94714d56) | Oct 24, 2022 |
| Dell          | 01XK1W A00                  | [86e8f9141a](https://linux-hardware.org/?probe=86e8f9141a) | Oct 24, 2022 |
| Gigabyte      | G41MT-S2P                   | [9d2d49b8e4](https://linux-hardware.org/?probe=9d2d49b8e4) | Oct 23, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [50b6612f7d](https://linux-hardware.org/?probe=50b6612f7d) | Oct 23, 2022 |
| ASRock        | G31M-S                      | [5f1ca232ea](https://linux-hardware.org/?probe=5f1ca232ea) | Oct 23, 2022 |
| Dell          | 0YJPT1 A00                  | [678916671d](https://linux-hardware.org/?probe=678916671d) | Oct 23, 2022 |
| Unknown       | Unknown                     | [dcb8b694a7](https://linux-hardware.org/?probe=dcb8b694a7) | Oct 23, 2022 |
| ASRock        | FM2A68M-HD+                 | [1a49be478c](https://linux-hardware.org/?probe=1a49be478c) | Oct 22, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [168cbb8438](https://linux-hardware.org/?probe=168cbb8438) | Oct 21, 2022 |
| MSI           | H81M-P33                    | [efbd4959b8](https://linux-hardware.org/?probe=efbd4959b8) | Oct 21, 2022 |
| MSI           | H81M-P33                    | [a59f545a7b](https://linux-hardware.org/?probe=a59f545a7b) | Oct 21, 2022 |
| Gigabyte      | H61M-S2PV                   | [f60716afd0](https://linux-hardware.org/?probe=f60716afd0) | Oct 20, 2022 |
| ASRock        | Q1900-ITX                   | [c9d76cd138](https://linux-hardware.org/?probe=c9d76cd138) | Oct 20, 2022 |
| Gigabyte      | GA-6LXSV 00000001           | [ac15415eca](https://linux-hardware.org/?probe=ac15415eca) | Oct 20, 2022 |
| Dell          | 0D4MD1 A02                  | [becbded076](https://linux-hardware.org/?probe=becbded076) | Oct 20, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [e7875c59bc](https://linux-hardware.org/?probe=e7875c59bc) | Oct 20, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | [7799fd6266](https://linux-hardware.org/?probe=7799fd6266) | Oct 20, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [565e5d5e3b](https://linux-hardware.org/?probe=565e5d5e3b) | Oct 20, 2022 |
| Dell          | 0782GW A00                  | [d54932d557](https://linux-hardware.org/?probe=d54932d557) | Oct 19, 2022 |
| ASUSTek       | P9X79                       | [285e78cfbe](https://linux-hardware.org/?probe=285e78cfbe) | Oct 19, 2022 |
| HP            | 876C SMVB                   | [384313312d](https://linux-hardware.org/?probe=384313312d) | Oct 19, 2022 |
| MSI           | H81M-P33                    | [784b068521](https://linux-hardware.org/?probe=784b068521) | Oct 19, 2022 |
| ASUSTek       | B85M-G                      | [42a1bedb35](https://linux-hardware.org/?probe=42a1bedb35) | Oct 19, 2022 |
| HP            | 8061                        | [8692ad745b](https://linux-hardware.org/?probe=8692ad745b) | Oct 19, 2022 |
| ASUSTek       | P5G41T-M LX2/BR             | [46a99f3d0e](https://linux-hardware.org/?probe=46a99f3d0e) | Oct 18, 2022 |
| HP            | 0A58h                       | [4c8d533bb0](https://linux-hardware.org/?probe=4c8d533bb0) | Oct 18, 2022 |
| HP            | 3047h                       | [c1716b926a](https://linux-hardware.org/?probe=c1716b926a) | Oct 18, 2022 |
| Giga-Byte ... | i440BX-W977                 | [018daa60e1](https://linux-hardware.org/?probe=018daa60e1) | Oct 18, 2022 |
| ASUSTek       | B85M-G                      | [86b92cdc50](https://linux-hardware.org/?probe=86b92cdc50) | Oct 18, 2022 |
| Dell          | 0DFRFW A01                  | [dd4ada0631](https://linux-hardware.org/?probe=dd4ada0631) | Oct 18, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [db3ce64578](https://linux-hardware.org/?probe=db3ce64578) | Oct 18, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [621cca0fca](https://linux-hardware.org/?probe=621cca0fca) | Oct 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | [e61760eab3](https://linux-hardware.org/?probe=e61760eab3) | Oct 18, 2022 |
| Dell          | 0WG864                      | [2feb42b3cf](https://linux-hardware.org/?probe=2feb42b3cf) | Oct 17, 2022 |
| HP            | 1589                        | [a6be3ee931](https://linux-hardware.org/?probe=a6be3ee931) | Oct 17, 2022 |
| ASRock        | B450M-HDV                   | [6a523a41da](https://linux-hardware.org/?probe=6a523a41da) | Oct 17, 2022 |
| Dell          | 01XK1W A00                  | [d86b86e8a8](https://linux-hardware.org/?probe=d86b86e8a8) | Oct 17, 2022 |
| HP            | 1589                        | [c36aa260eb](https://linux-hardware.org/?probe=c36aa260eb) | Oct 17, 2022 |
| Acer          | MCP7A                       | [32f914d009](https://linux-hardware.org/?probe=32f914d009) | Oct 17, 2022 |
| ASRock        | B450M Pro4                  | [d55b50c6c7](https://linux-hardware.org/?probe=d55b50c6c7) | Oct 16, 2022 |
| ASRock        | B450M Pro4                  | [4af4c60051](https://linux-hardware.org/?probe=4af4c60051) | Oct 16, 2022 |
| Gigabyte      | C246N-WU2-CF                | [cb7ca4eb5a](https://linux-hardware.org/?probe=cb7ca4eb5a) | Oct 16, 2022 |
| ASUSTek       | PRIME B250M-PLUS            | [c0feb12708](https://linux-hardware.org/?probe=c0feb12708) | Oct 16, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [f26592e956](https://linux-hardware.org/?probe=f26592e956) | Oct 16, 2022 |
| Dell          | 0782GW A00                  | [6a6f7314c0](https://linux-hardware.org/?probe=6a6f7314c0) | Oct 15, 2022 |
| Gigabyte      | H61M-S2PV                   | [f9568da63c](https://linux-hardware.org/?probe=f9568da63c) | Oct 15, 2022 |
| Gigabyte      | H61M-S2PV                   | [b226135430](https://linux-hardware.org/?probe=b226135430) | Oct 15, 2022 |
| Dell          | 0M863N A00                  | [27e1ded122](https://linux-hardware.org/?probe=27e1ded122) | Oct 15, 2022 |
| ASRock        | J5040-ITX                   | [aee52607f0](https://linux-hardware.org/?probe=aee52607f0) | Oct 14, 2022 |
| MSI           | G31TM-P21                   | [ea0fc2d497](https://linux-hardware.org/?probe=ea0fc2d497) | Oct 14, 2022 |
| ASRockRack    | X470D4U2-2T                 | [ebada4e791](https://linux-hardware.org/?probe=ebada4e791) | Oct 14, 2022 |
| Dell          | 0N4YC8 A00                  | [85766540b3](https://linux-hardware.org/?probe=85766540b3) | Oct 14, 2022 |
| Dell          | 0GY6Y8 A01                  | [06e46e98b4](https://linux-hardware.org/?probe=06e46e98b4) | Oct 14, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [9554b1f29a](https://linux-hardware.org/?probe=9554b1f29a) | Oct 14, 2022 |
| ASUSTek       | P5QL-CM                     | [34c01c8045](https://linux-hardware.org/?probe=34c01c8045) | Oct 14, 2022 |
| MSI           | PRO B550-VC                 | [0141458d01](https://linux-hardware.org/?probe=0141458d01) | Oct 14, 2022 |
| Gigabyte      | B450M DS3H-CF               | [ede8c7fa36](https://linux-hardware.org/?probe=ede8c7fa36) | Oct 13, 2022 |
| ASRock        | AM2NF6G-VSTA                | [6a810d253c](https://linux-hardware.org/?probe=6a810d253c) | Oct 13, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [1e2eda446c](https://linux-hardware.org/?probe=1e2eda446c) | Oct 13, 2022 |
| HP            | ProLiant MicroServer        | [067097bef8](https://linux-hardware.org/?probe=067097bef8) | Oct 13, 2022 |
| HP            | 158A                        | [6b1d53174a](https://linux-hardware.org/?probe=6b1d53174a) | Oct 12, 2022 |
| HP            | 3047h                       | [ba7f593887](https://linux-hardware.org/?probe=ba7f593887) | Oct 12, 2022 |
| Gigabyte      | 970A-DS3P                   | [744091dcaa](https://linux-hardware.org/?probe=744091dcaa) | Oct 12, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [55bb52409c](https://linux-hardware.org/?probe=55bb52409c) | Oct 12, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [300975f708](https://linux-hardware.org/?probe=300975f708) | Oct 11, 2022 |
| ASRock        | H570M-ITX/ac                | [eac6add22e](https://linux-hardware.org/?probe=eac6add22e) | Oct 11, 2022 |
| Gigabyte      | GA-880GM-D2H                | [6a9fe776d8](https://linux-hardware.org/?probe=6a9fe776d8) | Oct 10, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [97bbb3b52b](https://linux-hardware.org/?probe=97bbb3b52b) | Oct 09, 2022 |
| Unknown       | Seagate Personal Cloud (... | [40ea197650](https://linux-hardware.org/?probe=40ea197650) | Oct 09, 2022 |
| ASUSTek       | PRIME B450M-A               | [bef5f7f7d7](https://linux-hardware.org/?probe=bef5f7f7d7) | Oct 09, 2022 |
| Dell          | 01XK1W A00                  | [ce045937bc](https://linux-hardware.org/?probe=ce045937bc) | Oct 09, 2022 |
| Dell          | 01XK1W A00                  | [939e426600](https://linux-hardware.org/?probe=939e426600) | Oct 08, 2022 |
| Dell          | 003KPJ A00                  | [e151f6645b](https://linux-hardware.org/?probe=e151f6645b) | Oct 08, 2022 |
| MSI           | H81M-E34                    | [154cb109bf](https://linux-hardware.org/?probe=154cb109bf) | Oct 08, 2022 |
| ASUSTek       | V-P8H67E                    | [b4f0f561d2](https://linux-hardware.org/?probe=b4f0f561d2) | Oct 08, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [1798b09b89](https://linux-hardware.org/?probe=1798b09b89) | Oct 08, 2022 |
| ASRockRack    | X470D4U2-2T                 | [5b543dbd16](https://linux-hardware.org/?probe=5b543dbd16) | Oct 08, 2022 |
| Shuttle       | FS81                        | [ba7c22e135](https://linux-hardware.org/?probe=ba7c22e135) | Oct 07, 2022 |
| Shuttle       | FS81                        | [63ec5c8971](https://linux-hardware.org/?probe=63ec5c8971) | Oct 07, 2022 |
| Fujitsu       | D3417-B1 S26361-D3417-B1    | [aa89234022](https://linux-hardware.org/?probe=aa89234022) | Oct 07, 2022 |
| ASRock        | Z68 Extreme4                | [6b96459f0a](https://linux-hardware.org/?probe=6b96459f0a) | Oct 07, 2022 |
| ASUSTek       | PRIME H270-PRO              | [bbf95bf34d](https://linux-hardware.org/?probe=bbf95bf34d) | Oct 06, 2022 |
| ASUSTek       | P5GDC Pro                   | [25ac480f76](https://linux-hardware.org/?probe=25ac480f76) | Oct 06, 2022 |
| Techvision    | TVI7309X B0                 | [a12d335502](https://linux-hardware.org/?probe=a12d335502) | Oct 06, 2022 |
| Techvision    | TVI7309X B0                 | [fd49fda31a](https://linux-hardware.org/?probe=fd49fda31a) | Oct 06, 2022 |
| ASRock        | B450M Pro4                  | [0432411e08](https://linux-hardware.org/?probe=0432411e08) | Oct 05, 2022 |
| ASRock        | B450M Pro4                  | [c287d961f7](https://linux-hardware.org/?probe=c287d961f7) | Oct 05, 2022 |
| MSI           | X399 GAMING PRO CARBON A... | [1b399dcbb2](https://linux-hardware.org/?probe=1b399dcbb2) | Oct 05, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [bbea875fdc](https://linux-hardware.org/?probe=bbea875fdc) | Oct 05, 2022 |
| Lenovo        | ThinkStation S30 0569BE3    | [026d1ee25e](https://linux-hardware.org/?probe=026d1ee25e) | Oct 05, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [93698d1670](https://linux-hardware.org/?probe=93698d1670) | Oct 05, 2022 |
| ASRock        | 970M Pro3                   | [a9e9513b41](https://linux-hardware.org/?probe=a9e9513b41) | Oct 04, 2022 |
| Dell          | 0D4MD1 A00                  | [9ab1446c27](https://linux-hardware.org/?probe=9ab1446c27) | Oct 04, 2022 |
| Inventec      | D CLASS A02                 | [851214001a](https://linux-hardware.org/?probe=851214001a) | Oct 04, 2022 |
| ASUSTek       | P6T DELUXE V2               | [1c6fd70d5f](https://linux-hardware.org/?probe=1c6fd70d5f) | Oct 04, 2022 |
| HP            | 1906                        | [a6f705f119](https://linux-hardware.org/?probe=a6f705f119) | Oct 03, 2022 |
| Dell          | 0T7D40 A01                  | [1fb6d9ec64](https://linux-hardware.org/?probe=1fb6d9ec64) | Oct 03, 2022 |
| Gigabyte      | D525TUD                     | [47d31ff25c](https://linux-hardware.org/?probe=47d31ff25c) | Oct 03, 2022 |
| Lenovo        | ThinkServer TS440           | [1031dfcd50](https://linux-hardware.org/?probe=1031dfcd50) | Oct 03, 2022 |
| Pegatron      | 2AC3                        | [0ea51f0746](https://linux-hardware.org/?probe=0ea51f0746) | Oct 03, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [e3a783a839](https://linux-hardware.org/?probe=e3a783a839) | Oct 02, 2022 |
| ASUSTek       | PRIME B550M-K               | [31dcf67714](https://linux-hardware.org/?probe=31dcf67714) | Oct 02, 2022 |
| ASUSTek       | PRIME B550M-K               | [97afbe98b8](https://linux-hardware.org/?probe=97afbe98b8) | Oct 02, 2022 |
| ASUSTek       | M5A97 R2.0                  | [78ff851478](https://linux-hardware.org/?probe=78ff851478) | Oct 02, 2022 |
| Dell          | 0KJCC5 A00                  | [7915b298b2](https://linux-hardware.org/?probe=7915b298b2) | Oct 01, 2022 |
| Dell          | 01XK1W A00                  | [29c4292c62](https://linux-hardware.org/?probe=29c4292c62) | Oct 01, 2022 |
| Gigabyte      | H81M-D2V                    | [21a601e10a](https://linux-hardware.org/?probe=21a601e10a) | Sep 30, 2022 |
| HP            | 859C                        | [08161b9516](https://linux-hardware.org/?probe=08161b9516) | Sep 30, 2022 |
| ASRock        | X570 Steel Legend           | [40e65e38cf](https://linux-hardware.org/?probe=40e65e38cf) | Sep 30, 2022 |
| ECS           | G31T-M9                     | [45b25aaf8c](https://linux-hardware.org/?probe=45b25aaf8c) | Sep 29, 2022 |
| Biostar       | H55 HD                      | [bde8e0a133](https://linux-hardware.org/?probe=bde8e0a133) | Sep 28, 2022 |
| BESSTAR Te... | TH50                        | [2045e665b1](https://linux-hardware.org/?probe=2045e665b1) | Sep 28, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [6d92b99f8e](https://linux-hardware.org/?probe=6d92b99f8e) | Sep 28, 2022 |
| HP            | 339A                        | [5c961ef93f](https://linux-hardware.org/?probe=5c961ef93f) | Sep 28, 2022 |
| HP            | 339A                        | [ac9538b489](https://linux-hardware.org/?probe=ac9538b489) | Sep 28, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [82b108b3b8](https://linux-hardware.org/?probe=82b108b3b8) | Sep 28, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0031772f40](https://linux-hardware.org/?probe=0031772f40) | Sep 27, 2022 |
| MSI           | B365M PRO-VDH               | [45e07c7119](https://linux-hardware.org/?probe=45e07c7119) | Sep 27, 2022 |
| Medion        | MS-7728                     | [0b9b2ca570](https://linux-hardware.org/?probe=0b9b2ca570) | Sep 27, 2022 |
| HP            | 339A                        | [25ef7556cc](https://linux-hardware.org/?probe=25ef7556cc) | Sep 27, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [757d465447](https://linux-hardware.org/?probe=757d465447) | Sep 27, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [e3826dca71](https://linux-hardware.org/?probe=e3826dca71) | Sep 27, 2022 |
| Gigabyte      | H81M-S2PV                   | [76a7224818](https://linux-hardware.org/?probe=76a7224818) | Sep 26, 2022 |
| HP            | 339A                        | [07986ca95e](https://linux-hardware.org/?probe=07986ca95e) | Sep 26, 2022 |
| HP            | 0B40h                       | [d72bb749ff](https://linux-hardware.org/?probe=d72bb749ff) | Sep 26, 2022 |
| Lenovo        | Myrtle CRB SDK0J40700 WI... | [508c873693](https://linux-hardware.org/?probe=508c873693) | Sep 26, 2022 |
| Dell          | 01XK1W A00                  | [4e228116be](https://linux-hardware.org/?probe=4e228116be) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6c9c3f13d0](https://linux-hardware.org/?probe=6c9c3f13d0) | Sep 25, 2022 |
| ASRockRack    | X570D4U-2L2T                | [779faa3cfd](https://linux-hardware.org/?probe=779faa3cfd) | Sep 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [65d54e7273](https://linux-hardware.org/?probe=65d54e7273) | Sep 25, 2022 |
| Google        | Teemo                       | [5ddc8b97b8](https://linux-hardware.org/?probe=5ddc8b97b8) | Sep 24, 2022 |
| MSI           | H81M-P33                    | [7e4f539e70](https://linux-hardware.org/?probe=7e4f539e70) | Sep 24, 2022 |
| MSI           | H81M-P33                    | [64cd74457e](https://linux-hardware.org/?probe=64cd74457e) | Sep 24, 2022 |
| Foxconn       | 2ADA                        | [8a734f0799](https://linux-hardware.org/?probe=8a734f0799) | Sep 24, 2022 |
| ASUSTek       | P8B75-M                     | [0299e4f7b1](https://linux-hardware.org/?probe=0299e4f7b1) | Sep 24, 2022 |
| ASUSTek       | P8B75-M                     | [cad0f6f375](https://linux-hardware.org/?probe=cad0f6f375) | Sep 24, 2022 |
| ASUSTek       | P8B75-M                     | [91d179670c](https://linux-hardware.org/?probe=91d179670c) | Sep 23, 2022 |
| ASUSTek       | PRIME X570-P                | [5f1b4b1679](https://linux-hardware.org/?probe=5f1b4b1679) | Sep 23, 2022 |
| ECS           | H61H2-CM                    | [13ad69a13e](https://linux-hardware.org/?probe=13ad69a13e) | Sep 23, 2022 |
| ASUSTek       | P5QPL-VM EPU                | [8a4819f23d](https://linux-hardware.org/?probe=8a4819f23d) | Sep 23, 2022 |
| Gigabyte      | H81M-S2V                    | [6c884d4968](https://linux-hardware.org/?probe=6c884d4968) | Sep 23, 2022 |
| Gigabyte      | H81M-S2V                    | [39a94459dc](https://linux-hardware.org/?probe=39a94459dc) | Sep 23, 2022 |
| ASUSTek       | H110M-R                     | [c9f00bec8e](https://linux-hardware.org/?probe=c9f00bec8e) | Sep 23, 2022 |
| HP            | 876C SMVB                   | [c6fbf7c631](https://linux-hardware.org/?probe=c6fbf7c631) | Sep 23, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [c0cc0dc101](https://linux-hardware.org/?probe=c0cc0dc101) | Sep 21, 2022 |
| Lenovo        | ThinkCentre A70z 0401R6U    | [2a93ca040a](https://linux-hardware.org/?probe=2a93ca040a) | Sep 21, 2022 |
| Thecus        | N2810 0001                  | [f54df3994c](https://linux-hardware.org/?probe=f54df3994c) | Sep 21, 2022 |
| ECS           | G31T-M9                     | [6e67780df1](https://linux-hardware.org/?probe=6e67780df1) | Sep 21, 2022 |
| Gigabyte      | H61M-DS2                    | [a9e18191f7](https://linux-hardware.org/?probe=a9e18191f7) | Sep 21, 2022 |
| ASRock        | H470M-HVS                   | [e267d78b42](https://linux-hardware.org/?probe=e267d78b42) | Sep 21, 2022 |
| ECS           | G31T-M9                     | [46fd18ee44](https://linux-hardware.org/?probe=46fd18ee44) | Sep 21, 2022 |
| ASUSTek       | M3N78-VM                    | [03e6d4f5bc](https://linux-hardware.org/?probe=03e6d4f5bc) | Sep 21, 2022 |
| ASUSTek       | M3N78-VM                    | [658141844b](https://linux-hardware.org/?probe=658141844b) | Sep 21, 2022 |
| Lenovo        | ThinkCentre M57 6072WMD     | [eb8221088f](https://linux-hardware.org/?probe=eb8221088f) | Sep 21, 2022 |
| HP            | 158A                        | [428326af76](https://linux-hardware.org/?probe=428326af76) | Sep 21, 2022 |
| Supermicro    | X9DR3-F                     | [da32f7dbfb](https://linux-hardware.org/?probe=da32f7dbfb) | Sep 21, 2022 |
| ASUSTek       | G20CB                       | [34f4d43b97](https://linux-hardware.org/?probe=34f4d43b97) | Sep 20, 2022 |
| Shuttle       | FS81                        | [4c1fb942aa](https://linux-hardware.org/?probe=4c1fb942aa) | Sep 20, 2022 |
| Gigabyte      | A320M-S2H-CF                | [172fd1874d](https://linux-hardware.org/?probe=172fd1874d) | Sep 20, 2022 |
| Dell          | 0KY237 A01                  | [e1258b712e](https://linux-hardware.org/?probe=e1258b712e) | Sep 20, 2022 |
| Dell          | 0KY237 A01                  | [6f2ce8e794](https://linux-hardware.org/?probe=6f2ce8e794) | Sep 20, 2022 |
| ASUSTek       | B85M-G                      | [f9fa37f0d2](https://linux-hardware.org/?probe=f9fa37f0d2) | Sep 20, 2022 |
| Gigabyte      | GA-M56S-S3                  | [ecd62e14f4](https://linux-hardware.org/?probe=ecd62e14f4) | Sep 20, 2022 |
| Unknown       | 1.0                         | [1ef071c553](https://linux-hardware.org/?probe=1ef071c553) | Sep 20, 2022 |
| MSI           | Z370 PC PRO                 | [7967e43f1d](https://linux-hardware.org/?probe=7967e43f1d) | Sep 20, 2022 |
| Lenovo        | SKYBAY SDK0J40700 WIN 32... | [37fcfc48c5](https://linux-hardware.org/?probe=37fcfc48c5) | Sep 20, 2022 |
| Gigabyte      | EP45T-UD3R                  | [979765d106](https://linux-hardware.org/?probe=979765d106) | Sep 20, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [a0a61b5d8c](https://linux-hardware.org/?probe=a0a61b5d8c) | Sep 20, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [bb8e3ae62a](https://linux-hardware.org/?probe=bb8e3ae62a) | Sep 20, 2022 |
| ASUSTek       | M5A97 R2.0                  | [96e0712ca0](https://linux-hardware.org/?probe=96e0712ca0) | Sep 19, 2022 |
| ASRock        | H470M-HVS                   | [ee235bf98c](https://linux-hardware.org/?probe=ee235bf98c) | Sep 19, 2022 |
| Gigabyte      | B550 VISION D-P             | [9457acbe13](https://linux-hardware.org/?probe=9457acbe13) | Sep 19, 2022 |
| ASUSTek       | P5G41T-M LX                 | [74e31be1be](https://linux-hardware.org/?probe=74e31be1be) | Sep 19, 2022 |
| AZW           | GK55                        | [9a9019eee6](https://linux-hardware.org/?probe=9a9019eee6) | Sep 19, 2022 |
| ASRock        | Z590M-ITX/ax                | [d202b0a504](https://linux-hardware.org/?probe=d202b0a504) | Sep 19, 2022 |
| Supermicro    | X10DRi-T4+                  | [1f507cde8c](https://linux-hardware.org/?probe=1f507cde8c) | Sep 19, 2022 |
| HP            | 1998                        | [14eeedb712](https://linux-hardware.org/?probe=14eeedb712) | Sep 18, 2022 |
| Dell          | 0KY237 A01                  | [8b2d50f5d1](https://linux-hardware.org/?probe=8b2d50f5d1) | Sep 18, 2022 |
| Dell          | 0G785M A00                  | [c1045050d6](https://linux-hardware.org/?probe=c1045050d6) | Sep 17, 2022 |
| Gigabyte      | B365M DS3H                  | [e552983263](https://linux-hardware.org/?probe=e552983263) | Sep 17, 2022 |
| Dell          | 0T2HR0 A02                  | [46dd4dfa8f](https://linux-hardware.org/?probe=46dd4dfa8f) | Sep 17, 2022 |
| AZW           | Gemini T34-M                | [baafe96fc5](https://linux-hardware.org/?probe=baafe96fc5) | Sep 17, 2022 |
| ASUSTek       | P8Z77-V                     | [3ace24ebfc](https://linux-hardware.org/?probe=3ace24ebfc) | Sep 16, 2022 |
| ASUSTek       | LITHIUM                     | [3aab1aa49f](https://linux-hardware.org/?probe=3aab1aa49f) | Sep 16, 2022 |
| ASUSTek       | KCMA-D8                     | [dc8ecec94f](https://linux-hardware.org/?probe=dc8ecec94f) | Sep 16, 2022 |
| Gigabyte      | B150M-D3P-WG-CF             | [e37ff8fec3](https://linux-hardware.org/?probe=e37ff8fec3) | Sep 16, 2022 |
| ASRock        | H470M-HVS                   | [205e3937a8](https://linux-hardware.org/?probe=205e3937a8) | Sep 16, 2022 |
| MSI           | B450-A PRO MAX              | [c63f6d45b4](https://linux-hardware.org/?probe=c63f6d45b4) | Sep 16, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [00ca986a4c](https://linux-hardware.org/?probe=00ca986a4c) | Sep 16, 2022 |
| MSI           | H110M PRO-VD                | [23194305f6](https://linux-hardware.org/?probe=23194305f6) | Sep 15, 2022 |
| ASUSTek       | B85M-G                      | [9f2a08c261](https://linux-hardware.org/?probe=9f2a08c261) | Sep 15, 2022 |
| Gigabyte      | EP45T-UD3R                  | [007e9d4205](https://linux-hardware.org/?probe=007e9d4205) | Sep 15, 2022 |
| HP            | 876C SMVB                   | [adc81b2fd5](https://linux-hardware.org/?probe=adc81b2fd5) | Sep 15, 2022 |
| Gigabyte      | B560M DS3H V2               | [af4b9d7add](https://linux-hardware.org/?probe=af4b9d7add) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [01d92ffc28](https://linux-hardware.org/?probe=01d92ffc28) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [c04d19fe27](https://linux-hardware.org/?probe=c04d19fe27) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [ad0ac85a1c](https://linux-hardware.org/?probe=ad0ac85a1c) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [6cb46b9558](https://linux-hardware.org/?probe=6cb46b9558) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [bec6da09ae](https://linux-hardware.org/?probe=bec6da09ae) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [0366b6294c](https://linux-hardware.org/?probe=0366b6294c) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [a914907c0f](https://linux-hardware.org/?probe=a914907c0f) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [662117584a](https://linux-hardware.org/?probe=662117584a) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [272b6ec971](https://linux-hardware.org/?probe=272b6ec971) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [2528bbb7ac](https://linux-hardware.org/?probe=2528bbb7ac) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [212a063241](https://linux-hardware.org/?probe=212a063241) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [2b6d3fc6f0](https://linux-hardware.org/?probe=2b6d3fc6f0) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [9bc2776801](https://linux-hardware.org/?probe=9bc2776801) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [4048396126](https://linux-hardware.org/?probe=4048396126) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [7036d4bc55](https://linux-hardware.org/?probe=7036d4bc55) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [e4147da882](https://linux-hardware.org/?probe=e4147da882) | Sep 14, 2022 |
| ASRock        | H470M-HVS                   | [f85ab5e109](https://linux-hardware.org/?probe=f85ab5e109) | Sep 14, 2022 |
| Lenovo        | SHARKBAY 0C48431 WIN        | [4598920e84](https://linux-hardware.org/?probe=4598920e84) | Sep 13, 2022 |
| HP            | 876C SMVB                   | [15ec81ce9d](https://linux-hardware.org/?probe=15ec81ce9d) | Sep 13, 2022 |
| Biostar       | NF560-A2G                   | [96c296c2f3](https://linux-hardware.org/?probe=96c296c2f3) | Sep 13, 2022 |
| ASRock        | H470M-HDV                   | [41977548bc](https://linux-hardware.org/?probe=41977548bc) | Sep 13, 2022 |
| Positivo      | POS-EINM10CB POSITIVO       | [7c876e560b](https://linux-hardware.org/?probe=7c876e560b) | Sep 13, 2022 |
| HP            | 8464                        | [fcc16a5a56](https://linux-hardware.org/?probe=fcc16a5a56) | Sep 12, 2022 |
| Gigabyte      | H410M S2H                   | [31ca5d0add](https://linux-hardware.org/?probe=31ca5d0add) | Sep 12, 2022 |
| Gigabyte      | H410M S2H                   | [d76d427a61](https://linux-hardware.org/?probe=d76d427a61) | Sep 12, 2022 |
| Gigabyte      | H410M S2H                   | [c996d652d3](https://linux-hardware.org/?probe=c996d652d3) | Sep 12, 2022 |
| Gigabyte      | H410M S2H                   | [d08cb8e35b](https://linux-hardware.org/?probe=d08cb8e35b) | Sep 12, 2022 |
| Gigabyte      | H410M S2H                   | [0c2d66313e](https://linux-hardware.org/?probe=0c2d66313e) | Sep 12, 2022 |
| Gigabyte      | H410M S2H                   | [5461cdbf3b](https://linux-hardware.org/?probe=5461cdbf3b) | Sep 12, 2022 |
| Gigabyte      | H410M S2H                   | [c055d82971](https://linux-hardware.org/?probe=c055d82971) | Sep 12, 2022 |
| Gigabyte      | H410M S2H                   | [8c0d419ac8](https://linux-hardware.org/?probe=8c0d419ac8) | Sep 12, 2022 |
| ASUSTek       | PRIME B450M-A               | [2af6edb7a0](https://linux-hardware.org/?probe=2af6edb7a0) | Sep 12, 2022 |
| ASUSTek       | G20CB                       | [a52ff97f3b](https://linux-hardware.org/?probe=a52ff97f3b) | Sep 12, 2022 |
| ASUSTek       | G20CB                       | [2d737743f4](https://linux-hardware.org/?probe=2d737743f4) | Sep 12, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [e8da6da2b0](https://linux-hardware.org/?probe=e8da6da2b0) | Sep 12, 2022 |
| Inventec      | C CLASS A01                 | [613f741235](https://linux-hardware.org/?probe=613f741235) | Sep 12, 2022 |
| Dell          | 01XK1W A00                  | [09d0fcce0e](https://linux-hardware.org/?probe=09d0fcce0e) | Sep 12, 2022 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | [e007728e0a](https://linux-hardware.org/?probe=e007728e0a) | Sep 11, 2022 |
| Inventec      | C CLASS A01                 | [21ae14e7a0](https://linux-hardware.org/?probe=21ae14e7a0) | Sep 11, 2022 |
| Inventec      | C CLASS A01                 | [3ddd0d7aa0](https://linux-hardware.org/?probe=3ddd0d7aa0) | Sep 11, 2022 |
| Dell          | 01XK1W A00                  | [41b9796681](https://linux-hardware.org/?probe=41b9796681) | Sep 10, 2022 |
| HP            | 1998                        | [37cd896e72](https://linux-hardware.org/?probe=37cd896e72) | Sep 10, 2022 |
| HP            | 1998                        | [3da9c3ef8e](https://linux-hardware.org/?probe=3da9c3ef8e) | Sep 10, 2022 |
| Lenovo        | ThinkServer TS440           | [cf028f9b8c](https://linux-hardware.org/?probe=cf028f9b8c) | Sep 10, 2022 |
| Lenovo        | ThinkCentre A70 7099A5G     | [102cf248e9](https://linux-hardware.org/?probe=102cf248e9) | Sep 10, 2022 |
| Biostar       | NF560-A2G                   | [68ffa42095](https://linux-hardware.org/?probe=68ffa42095) | Sep 09, 2022 |
| ASRock        | H310CM-HDV                  | [4f0ec780ee](https://linux-hardware.org/?probe=4f0ec780ee) | Sep 09, 2022 |
| Gigabyte      | A320M-S2H-CF                | [e4d2c1c120](https://linux-hardware.org/?probe=e4d2c1c120) | Sep 09, 2022 |
| Gigabyte      | A320M-S2H-CF                | [d28677add3](https://linux-hardware.org/?probe=d28677add3) | Sep 09, 2022 |
| Gigabyte      | M61PME-S2                   | [2557dd83ce](https://linux-hardware.org/?probe=2557dd83ce) | Sep 09, 2022 |
| ASRock        | Q1900M                      | [aadbe54f8d](https://linux-hardware.org/?probe=aadbe54f8d) | Sep 08, 2022 |
| ASUSTek       | P8H61-MX R2.0               | [17675b7bc8](https://linux-hardware.org/?probe=17675b7bc8) | Sep 08, 2022 |
| Gigabyte      | M61PME-S2                   | [1c48e52b18](https://linux-hardware.org/?probe=1c48e52b18) | Sep 08, 2022 |
| Gigabyte      | GA-M56S-S3                  | [b090ccb8fe](https://linux-hardware.org/?probe=b090ccb8fe) | Sep 07, 2022 |
| ASUSTek       | P5G41T-M LE                 | [6949fd04b7](https://linux-hardware.org/?probe=6949fd04b7) | Sep 07, 2022 |
| ASUSTek       | X99-E WS                    | [fcf815d38f](https://linux-hardware.org/?probe=fcf815d38f) | Sep 07, 2022 |
| MSI           | H110M PRO-VD                | [754b9daf74](https://linux-hardware.org/?probe=754b9daf74) | Sep 07, 2022 |
| Gigabyte      | GA-M56S-S3                  | [9012dd4a5d](https://linux-hardware.org/?probe=9012dd4a5d) | Sep 06, 2022 |
| Foxconn       | H61MXL/H61MXL-K             | [92af2339e3](https://linux-hardware.org/?probe=92af2339e3) | Sep 06, 2022 |
| ECS           | G31T-M9                     | [5005d8382e](https://linux-hardware.org/?probe=5005d8382e) | Sep 06, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [f7b09fb3e3](https://linux-hardware.org/?probe=f7b09fb3e3) | Sep 06, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [dacafc4729](https://linux-hardware.org/?probe=dacafc4729) | Sep 06, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | [2c5b0be3af](https://linux-hardware.org/?probe=2c5b0be3af) | Sep 06, 2022 |
| Gigabyte      | G41M-ES2L                   | [4071a8ff9b](https://linux-hardware.org/?probe=4071a8ff9b) | Sep 05, 2022 |
| ASUSTek       | PRIME X370-PRO              | [312e33b434](https://linux-hardware.org/?probe=312e33b434) | Sep 05, 2022 |
| HP            | 805D                        | [fdf50a9e36](https://linux-hardware.org/?probe=fdf50a9e36) | Sep 05, 2022 |
| Dell          | 06FW8P A00                  | [6023e5aa76](https://linux-hardware.org/?probe=6023e5aa76) | Sep 05, 2022 |
| ASUSTek       | Z97-PRO                     | [b9f3857d65](https://linux-hardware.org/?probe=b9f3857d65) | Sep 04, 2022 |
| ASRock        | Q1900M                      | [55a86f60b9](https://linux-hardware.org/?probe=55a86f60b9) | Sep 04, 2022 |
| Gigabyte      | Z87X-UD4H-CF                | [8ffe312747](https://linux-hardware.org/?probe=8ffe312747) | Sep 04, 2022 |
| MSI           | H510M-A PRO                 | [eb29524a90](https://linux-hardware.org/?probe=eb29524a90) | Sep 03, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [3a599be2f2](https://linux-hardware.org/?probe=3a599be2f2) | Sep 03, 2022 |
| ASUSTek       | P8H61 PRO                   | [082520f2d8](https://linux-hardware.org/?probe=082520f2d8) | Sep 03, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [9b8eef74b8](https://linux-hardware.org/?probe=9b8eef74b8) | Sep 03, 2022 |
| ASUSTek       | PRIME H270-PRO              | [5c0b32f572](https://linux-hardware.org/?probe=5c0b32f572) | Sep 03, 2022 |
| ASRockRack    | X470D4U2/1N1                | [0be6c5963d](https://linux-hardware.org/?probe=0be6c5963d) | Sep 02, 2022 |
| ASRock        | J3455-ITX                   | [262c6222d1](https://linux-hardware.org/?probe=262c6222d1) | Sep 02, 2022 |
| Gigabyte      | B550M DS3H                  | [acdd27f635](https://linux-hardware.org/?probe=acdd27f635) | Sep 02, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [3870423379](https://linux-hardware.org/?probe=3870423379) | Sep 02, 2022 |
| Lenovo        | SDK0J40705 WIN 342504154... | [4feb69184d](https://linux-hardware.org/?probe=4feb69184d) | Sep 02, 2022 |
| Lenovo        | SDK0J40705 WIN 342504154... | [bfee1a862f](https://linux-hardware.org/?probe=bfee1a862f) | Sep 02, 2022 |
| Gigabyte      | H77-DS3H                    | [11f9e9fa68](https://linux-hardware.org/?probe=11f9e9fa68) | Sep 02, 2022 |
| Gigabyte      | GA-970A-UD3                 | [e9f6cafc6c](https://linux-hardware.org/?probe=e9f6cafc6c) | Sep 02, 2022 |
| Gigabyte      | Z590 UD AC                  | [6c7b47158f](https://linux-hardware.org/?probe=6c7b47158f) | Sep 02, 2022 |
| Dell          | 02YRK5 A02                  | [bc316a8d3f](https://linux-hardware.org/?probe=bc316a8d3f) | Sep 01, 2022 |
| MSI           | H81M-P33                    | [8d15799ff9](https://linux-hardware.org/?probe=8d15799ff9) | Sep 01, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [b226dd8bc2](https://linux-hardware.org/?probe=b226dd8bc2) | Sep 01, 2022 |
| Gigabyte      | M68MT-S2                    | [29b9669488](https://linux-hardware.org/?probe=29b9669488) | Aug 31, 2022 |
| ASRock        | B450M-HDV R4.0              | [9c9e1d1ff1](https://linux-hardware.org/?probe=9c9e1d1ff1) | Aug 31, 2022 |
| ASRock        | N68-VS3 UCC                 | [688dcf88c9](https://linux-hardware.org/?probe=688dcf88c9) | Aug 30, 2022 |
| ASRock        | N68-VS3 UCC                 | [4ccef99860](https://linux-hardware.org/?probe=4ccef99860) | Aug 30, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [28f3abde34](https://linux-hardware.org/?probe=28f3abde34) | Aug 30, 2022 |
| Fujitsu       | D3348-B1 S26361-D3348-B1    | [9721d1f81d](https://linux-hardware.org/?probe=9721d1f81d) | Aug 30, 2022 |
| Unknown       | Unknown                     | [fd4ab67b77](https://linux-hardware.org/?probe=fd4ab67b77) | Aug 29, 2022 |
| Pegatron      | VIOLET6                     | [f17bcbfc4b](https://linux-hardware.org/?probe=f17bcbfc4b) | Aug 28, 2022 |
| Pegatron      | VIOLET6                     | [4960a57d91](https://linux-hardware.org/?probe=4960a57d91) | Aug 28, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [859b3cb78a](https://linux-hardware.org/?probe=859b3cb78a) | Aug 28, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [e0fedafd62](https://linux-hardware.org/?probe=e0fedafd62) | Aug 27, 2022 |
| ASRock        | Z68 Pro3 Gen3               | [186a63fa9e](https://linux-hardware.org/?probe=186a63fa9e) | Aug 27, 2022 |
| ASUSTek       | P5G41T-M LX V2              | [3c63953ca6](https://linux-hardware.org/?probe=3c63953ca6) | Aug 27, 2022 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [fbfc58655a](https://linux-hardware.org/?probe=fbfc58655a) | Aug 26, 2022 |
| Dell          | 01XK1W A00                  | [7728612d53](https://linux-hardware.org/?probe=7728612d53) | Aug 26, 2022 |
| Dell          | 01XK1W A00                  | [ee6cec5f61](https://linux-hardware.org/?probe=ee6cec5f61) | Aug 26, 2022 |
| Gigabyte      | B250M-DS3H-CF               | [5d4e41a441](https://linux-hardware.org/?probe=5d4e41a441) | Aug 26, 2022 |
| Intel         | X79G V2.x                   | [8418a8e83c](https://linux-hardware.org/?probe=8418a8e83c) | Aug 26, 2022 |
| ASUSTek       | IPN73-BA                    | [89f8b175e2](https://linux-hardware.org/?probe=89f8b175e2) | Aug 26, 2022 |
| Foxconn       | 2ABF                        | [46efca142c](https://linux-hardware.org/?probe=46efca142c) | Aug 26, 2022 |
| HP            | 18E5                        | [9196bf639b](https://linux-hardware.org/?probe=9196bf639b) | Aug 26, 2022 |
| Lenovo        | 7033EW4                     | [54417ae55f](https://linux-hardware.org/?probe=54417ae55f) | Aug 26, 2022 |
| Gigabyte      | X399 AORUS PRO-CF           | [5769de3299](https://linux-hardware.org/?probe=5769de3299) | Aug 25, 2022 |
| Gigabyte      | M61SME-S2                   | [2ee74a388d](https://linux-hardware.org/?probe=2ee74a388d) | Aug 25, 2022 |
| Dell          | 0D4MD1 A02                  | [7a06622253](https://linux-hardware.org/?probe=7a06622253) | Aug 25, 2022 |
| Dell          | 0WG864                      | [a333ec7f99](https://linux-hardware.org/?probe=a333ec7f99) | Aug 25, 2022 |
| ASUSTek       | A7N8X2.0                    | [f063b3e61a](https://linux-hardware.org/?probe=f063b3e61a) | Aug 25, 2022 |
| Gigabyte      | G41MT-S2                    | [42cd205688](https://linux-hardware.org/?probe=42cd205688) | Aug 25, 2022 |
| ASUSTek       | IPN73-BA                    | [da7e1db516](https://linux-hardware.org/?probe=da7e1db516) | Aug 25, 2022 |
| Dell          | 01XK1W A00                  | [604a0a7789](https://linux-hardware.org/?probe=604a0a7789) | Aug 25, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [413cc5a3c3](https://linux-hardware.org/?probe=413cc5a3c3) | Aug 24, 2022 |
| HP            | 339A                        | [961ac650aa](https://linux-hardware.org/?probe=961ac650aa) | Aug 24, 2022 |
| Dell          | 0D4MD1 A02                  | [b634bcdfa9](https://linux-hardware.org/?probe=b634bcdfa9) | Aug 24, 2022 |
| Huanan        | X99-F8D V2.4                | [11cfa7a502](https://linux-hardware.org/?probe=11cfa7a502) | Aug 24, 2022 |
| ASUSTek       | Pro B550M-C                 | [f0691dc9d8](https://linux-hardware.org/?probe=f0691dc9d8) | Aug 23, 2022 |
| Aquarius      | AQH310CM                    | [5e7e2820f4](https://linux-hardware.org/?probe=5e7e2820f4) | Aug 23, 2022 |
| ASUSTek       | A7N8X2.0                    | [56416fa002](https://linux-hardware.org/?probe=56416fa002) | Aug 23, 2022 |
| Dell          | 0MWYPT A02                  | [017af6f58d](https://linux-hardware.org/?probe=017af6f58d) | Aug 23, 2022 |
| Dell          | 0WG864                      | [e199a1a176](https://linux-hardware.org/?probe=e199a1a176) | Aug 23, 2022 |
| MSI           | H110M PRO-VD                | [7652f87b3a](https://linux-hardware.org/?probe=7652f87b3a) | Aug 22, 2022 |
| ASUSTek       | Z10PA-U8 Series             | [3e560a4018](https://linux-hardware.org/?probe=3e560a4018) | Aug 22, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [5cf178d7ac](https://linux-hardware.org/?probe=5cf178d7ac) | Aug 22, 2022 |
| ASUSTek       | Z170-A                      | [35270005d4](https://linux-hardware.org/?probe=35270005d4) | Aug 22, 2022 |
| Biostar       | A68N-5100                   | [2c6df92279](https://linux-hardware.org/?probe=2c6df92279) | Aug 22, 2022 |
| Foxconn       | 2ABF                        | [3eed86b908](https://linux-hardware.org/?probe=3eed86b908) | Aug 21, 2022 |
| ASRock        | Z77 Extreme6                | [660091e5bb](https://linux-hardware.org/?probe=660091e5bb) | Aug 20, 2022 |
| Google        | Teemo                       | [4cc9295e6d](https://linux-hardware.org/?probe=4cc9295e6d) | Aug 20, 2022 |
| MSI           | Z370 PC PRO                 | [9131aa23c4](https://linux-hardware.org/?probe=9131aa23c4) | Aug 20, 2022 |
| Gigabyte      | B460M DS3H V2               | [e5e74eea07](https://linux-hardware.org/?probe=e5e74eea07) | Aug 19, 2022 |
| Intel         | DN2820FYK H24582-201        | [a67c5b1926](https://linux-hardware.org/?probe=a67c5b1926) | Aug 19, 2022 |
| ASRock        | B450M-HDV R4.0              | [2f99e182f6](https://linux-hardware.org/?probe=2f99e182f6) | Aug 19, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [38eed67854](https://linux-hardware.org/?probe=38eed67854) | Aug 18, 2022 |
| Gateway       | DS50                        | [3d4faf13bb](https://linux-hardware.org/?probe=3d4faf13bb) | Aug 18, 2022 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | [58b22885a8](https://linux-hardware.org/?probe=58b22885a8) | Aug 18, 2022 |
| Gigabyte      | B560M DS3H AC               | [84e861fd2c](https://linux-hardware.org/?probe=84e861fd2c) | Aug 18, 2022 |
| ECS           | H61H2-M13                   | [fb83ed3720](https://linux-hardware.org/?probe=fb83ed3720) | Aug 18, 2022 |
| ECS           | G31T-M9                     | [d5b3edd559](https://linux-hardware.org/?probe=d5b3edd559) | Aug 18, 2022 |
| Lenovo        | ThinkStation D30 4223CC9    | [16e54152fd](https://linux-hardware.org/?probe=16e54152fd) | Aug 18, 2022 |
| Lenovo        | ThinkStation D30 4223CC9    | [e0208cab99](https://linux-hardware.org/?probe=e0208cab99) | Aug 18, 2022 |
| MSI           | B85M-E45                    | [cb991c0789](https://linux-hardware.org/?probe=cb991c0789) | Aug 17, 2022 |
| MSI           | X470 GAMING PRO             | [b648d56b04](https://linux-hardware.org/?probe=b648d56b04) | Aug 17, 2022 |
| Gigabyte      | H61M-DS2                    | [d066e1bcdf](https://linux-hardware.org/?probe=d066e1bcdf) | Aug 17, 2022 |
| ECS           | G31T-M9                     | [6192258c32](https://linux-hardware.org/?probe=6192258c32) | Aug 17, 2022 |
| Gigabyte      | D525TUD                     | [125fdc6af1](https://linux-hardware.org/?probe=125fdc6af1) | Aug 17, 2022 |
| Dell          | 0F6X5P A00                  | [47ecca331e](https://linux-hardware.org/?probe=47ecca331e) | Aug 16, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [1999369ff0](https://linux-hardware.org/?probe=1999369ff0) | Aug 16, 2022 |
| Dell          | 02YRK5 A02                  | [959d35921a](https://linux-hardware.org/?probe=959d35921a) | Aug 15, 2022 |
| HP            | 3047h                       | [bba72086af](https://linux-hardware.org/?probe=bba72086af) | Aug 15, 2022 |
| ASUSTek       | WS C422 DC                  | [92d816348a](https://linux-hardware.org/?probe=92d816348a) | Aug 15, 2022 |
| Gigabyte      | GA-970A-UD3                 | [9a1ff39910](https://linux-hardware.org/?probe=9a1ff39910) | Aug 15, 2022 |
| ASRock        | AB350 Gaming K4             | [8a6141848a](https://linux-hardware.org/?probe=8a6141848a) | Aug 13, 2022 |
| Dell          | 0WWJRX A00                  | [c9a3a6e952](https://linux-hardware.org/?probe=c9a3a6e952) | Aug 13, 2022 |
| System76      | Thelio thelio-r1            | [5b24d3e87b](https://linux-hardware.org/?probe=5b24d3e87b) | Aug 12, 2022 |
| Dell          | 0WG864                      | [de74f89735](https://linux-hardware.org/?probe=de74f89735) | Aug 12, 2022 |
| Unknown       | Unknown                     | [ed94063eb8](https://linux-hardware.org/?probe=ed94063eb8) | Aug 12, 2022 |
| ASUSTek       | PRIME Z370-P                | [7afaba2067](https://linux-hardware.org/?probe=7afaba2067) | Aug 12, 2022 |
| MSI           | H110M PRO-VD                | [57be8a8829](https://linux-hardware.org/?probe=57be8a8829) | Aug 12, 2022 |
| MSI           | B450M PRO-VDH MAX           | [059e0786bf](https://linux-hardware.org/?probe=059e0786bf) | Aug 11, 2022 |
| ASRock        | H110M-DGS R3.0              | [934583e785](https://linux-hardware.org/?probe=934583e785) | Aug 11, 2022 |
| Aquarius      | AQH310CM                    | [4084737708](https://linux-hardware.org/?probe=4084737708) | Aug 11, 2022 |
| MSI           | H110M PRO-VD                | [830489f44c](https://linux-hardware.org/?probe=830489f44c) | Aug 11, 2022 |
| Gigabyte      | B360M HD3                   | [d8432224a8](https://linux-hardware.org/?probe=d8432224a8) | Aug 11, 2022 |
| Gigabyte      | B360M HD3                   | [1325d40c4e](https://linux-hardware.org/?probe=1325d40c4e) | Aug 11, 2022 |
| ASRock        | H61M/U3S3                   | [be0d853621](https://linux-hardware.org/?probe=be0d853621) | Aug 11, 2022 |
| Gigabyte      | B450M DS3H V2               | [33dc68fe04](https://linux-hardware.org/?probe=33dc68fe04) | Aug 11, 2022 |
| ASUSTek       | H81T                        | [4049aa824c](https://linux-hardware.org/?probe=4049aa824c) | Aug 11, 2022 |
| ASRock        | G31M-S                      | [335a6f8616](https://linux-hardware.org/?probe=335a6f8616) | Aug 10, 2022 |
| MSI           | H81M-P33                    | [fd910dc3ca](https://linux-hardware.org/?probe=fd910dc3ca) | Aug 10, 2022 |
| MSI           | G41M-P28                    | [c20d54489d](https://linux-hardware.org/?probe=c20d54489d) | Aug 10, 2022 |
| Intel         | DP35DP AAD81073-207         | [3f55eb1ae4](https://linux-hardware.org/?probe=3f55eb1ae4) | Aug 10, 2022 |
| Intel         | DH87RL AAG74240-402         | [a83fd820d4](https://linux-hardware.org/?probe=a83fd820d4) | Aug 10, 2022 |
| MSI           | H81M-P33                    | [243392c01f](https://linux-hardware.org/?probe=243392c01f) | Aug 10, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [ea9b6a4757](https://linux-hardware.org/?probe=ea9b6a4757) | Aug 10, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [4e9256cf7f](https://linux-hardware.org/?probe=4e9256cf7f) | Aug 10, 2022 |
| Intel         | DH87RL AAG74240-402         | [8ea693190b](https://linux-hardware.org/?probe=8ea693190b) | Aug 09, 2022 |
| ASUSTek       | P8H61-M LX3                 | [19346d16de](https://linux-hardware.org/?probe=19346d16de) | Aug 09, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [1713317338](https://linux-hardware.org/?probe=1713317338) | Aug 09, 2022 |
| Gigabyte      | Z270-Gaming K3              | [b73567b27b](https://linux-hardware.org/?probe=b73567b27b) | Aug 09, 2022 |
| ASUSTek       | Z97M-PLUS/BR                | [b66253f362](https://linux-hardware.org/?probe=b66253f362) | Aug 09, 2022 |
| Gigabyte      | B550 GAMING X V2            | [fb01a8303f](https://linux-hardware.org/?probe=fb01a8303f) | Aug 08, 2022 |
| ASUSTek       | M5A88-V EVO                 | [b07157a232](https://linux-hardware.org/?probe=b07157a232) | Aug 08, 2022 |
| Unknown       | Unknown                     | [49c2378f28](https://linux-hardware.org/?probe=49c2378f28) | Aug 08, 2022 |
| Unknown       | Unknown                     | [9943b58e25](https://linux-hardware.org/?probe=9943b58e25) | Aug 08, 2022 |
| Foxconn       | G41MXP/G41MXP-V             | [91fb10e9c6](https://linux-hardware.org/?probe=91fb10e9c6) | Aug 08, 2022 |
| ECS           | G31T-M9                     | [6d24097613](https://linux-hardware.org/?probe=6d24097613) | Aug 08, 2022 |
| ASUSTek       | P8Z77-V                     | [18935d4aff](https://linux-hardware.org/?probe=18935d4aff) | Aug 07, 2022 |
| Gigabyte      | MZGLKAP-00                  | [5a349b05d2](https://linux-hardware.org/?probe=5a349b05d2) | Aug 07, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | [67934f8ed6](https://linux-hardware.org/?probe=67934f8ed6) | Aug 07, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | [d6d5cc239f](https://linux-hardware.org/?probe=d6d5cc239f) | Aug 07, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [468c10942e](https://linux-hardware.org/?probe=468c10942e) | Aug 06, 2022 |
| ECS           | G31T-M9                     | [8cdebd57de](https://linux-hardware.org/?probe=8cdebd57de) | Aug 05, 2022 |
| Gigabyte      | H81M-S2V                    | [696740d407](https://linux-hardware.org/?probe=696740d407) | Aug 05, 2022 |
| Lenovo        | 102F NO DPK                 | [1a040c2717](https://linux-hardware.org/?probe=1a040c2717) | Aug 04, 2022 |
| Intel         | X99                         | [33e0d23783](https://linux-hardware.org/?probe=33e0d23783) | Aug 04, 2022 |
| Foxconn       | 2AB1                        | [a2ebd67b7b](https://linux-hardware.org/?probe=a2ebd67b7b) | Aug 04, 2022 |
| ASUSTek       | P8H61-M LX3                 | [3d945110f8](https://linux-hardware.org/?probe=3d945110f8) | Aug 03, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [d5e820b393](https://linux-hardware.org/?probe=d5e820b393) | Aug 03, 2022 |
| HP            | 8876 11                     | [150fcb8977](https://linux-hardware.org/?probe=150fcb8977) | Aug 03, 2022 |
| HP            | 8876 11                     | [029813dfc5](https://linux-hardware.org/?probe=029813dfc5) | Aug 03, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [ca1d7dd61b](https://linux-hardware.org/?probe=ca1d7dd61b) | Aug 03, 2022 |
| Foxconn       | 2AB1                        | [74cd42b826](https://linux-hardware.org/?probe=74cd42b826) | Aug 03, 2022 |
| Lenovo        | 102F SDK0E50510 WIN 2625... | [80512402c0](https://linux-hardware.org/?probe=80512402c0) | Aug 02, 2022 |
| MSI           | Z97 GAMING 5                | [d2c534d06f](https://linux-hardware.org/?probe=d2c534d06f) | Aug 02, 2022 |
| ASUSTek       | P5G41T-M LE                 | [80c0577159](https://linux-hardware.org/?probe=80c0577159) | Aug 02, 2022 |
| Gigabyte      | H110M-Gaming3-CF            | [99a140d79b](https://linux-hardware.org/?probe=99a140d79b) | Aug 01, 2022 |
| ASRock        | H470M-HVS                   | [5282e92d2c](https://linux-hardware.org/?probe=5282e92d2c) | Aug 01, 2022 |
| ASUSTek       | P9X79                       | [4a518ab792](https://linux-hardware.org/?probe=4a518ab792) | Jul 31, 2022 |
| Gigabyte      | Z590 UD AC                  | [12cf4f1c81](https://linux-hardware.org/?probe=12cf4f1c81) | Jul 31, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [cc1944f4a3](https://linux-hardware.org/?probe=cc1944f4a3) | Jul 31, 2022 |
| Gigabyte      | A320M-H-CF                  | [5facb7723f](https://linux-hardware.org/?probe=5facb7723f) | Jul 30, 2022 |
| MSI           | MS-7418 100                 | [c17e48cc2b](https://linux-hardware.org/?probe=c17e48cc2b) | Jul 30, 2022 |
| MSI           | MS-7418 100                 | [4644e4eaa8](https://linux-hardware.org/?probe=4644e4eaa8) | Jul 30, 2022 |
| ASUSTek       | P8B75-M                     | [ddf26da899](https://linux-hardware.org/?probe=ddf26da899) | Jul 30, 2022 |
| ASUSTek       | P8H61-M LX3                 | [0cdabe4b69](https://linux-hardware.org/?probe=0cdabe4b69) | Jul 30, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | [3b1f863612](https://linux-hardware.org/?probe=3b1f863612) | Jul 30, 2022 |
| Intel         | TR440BXA A16643-311         | [e6245255f4](https://linux-hardware.org/?probe=e6245255f4) | Jul 29, 2022 |
| MSI           | H110M PRO-VD                | [675b1fa2ff](https://linux-hardware.org/?probe=675b1fa2ff) | Jul 29, 2022 |
| ASUSTek       | B85M-E/DASH                 | [2ebbaa4052](https://linux-hardware.org/?probe=2ebbaa4052) | Jul 29, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [902ee3b350](https://linux-hardware.org/?probe=902ee3b350) | Jul 29, 2022 |
| AZW           | MINI S                      | [53ba28d9c3](https://linux-hardware.org/?probe=53ba28d9c3) | Jul 28, 2022 |
| AZW           | MINI S                      | [46216b2db1](https://linux-hardware.org/?probe=46216b2db1) | Jul 28, 2022 |
| MSI           | Z370 GAMING M5              | [b9ec9e3dd4](https://linux-hardware.org/?probe=b9ec9e3dd4) | Jul 28, 2022 |
| MSI           | X470 GAMING PLUS            | [8415a45799](https://linux-hardware.org/?probe=8415a45799) | Jul 28, 2022 |
| MSI           | PRO Z690-A DDR4             | [b5b5f049d0](https://linux-hardware.org/?probe=b5b5f049d0) | Jul 28, 2022 |
| HP            | ProLiant MicroServer        | [8104eee56e](https://linux-hardware.org/?probe=8104eee56e) | Jul 28, 2022 |
| ASUSTek       | P7P55D                      | [0c9828e226](https://linux-hardware.org/?probe=0c9828e226) | Jul 28, 2022 |
| ASUSTek       | H97-PRO                     | [ca77f59b41](https://linux-hardware.org/?probe=ca77f59b41) | Jul 28, 2022 |
| MSI           | H110M PRO-VD                | [33961c087b](https://linux-hardware.org/?probe=33961c087b) | Jul 28, 2022 |
| MSI           | X470 GAMING PLUS            | [88ac64a1bd](https://linux-hardware.org/?probe=88ac64a1bd) | Jul 28, 2022 |
| Gigabyte      | B660M GAMING DDR4           | [661a4a67d4](https://linux-hardware.org/?probe=661a4a67d4) | Jul 27, 2022 |
| ECS           | G31T-M9                     | [5537dcbed3](https://linux-hardware.org/?probe=5537dcbed3) | Jul 27, 2022 |
| Medion        | MS-7728                     | [662e3948f2](https://linux-hardware.org/?probe=662e3948f2) | Jul 27, 2022 |
| HP            | 0AACh                       | [d7df31df8c](https://linux-hardware.org/?probe=d7df31df8c) | Jul 26, 2022 |
| HP            | 0AACh                       | [357aa343ec](https://linux-hardware.org/?probe=357aa343ec) | Jul 26, 2022 |
| ASUSTek       | PRIME H310M-K               | [ba71ad5870](https://linux-hardware.org/?probe=ba71ad5870) | Jul 26, 2022 |
| ASRock        | H510M-HDV/M.2               | [e7672c215b](https://linux-hardware.org/?probe=e7672c215b) | Jul 26, 2022 |
| Gigabyte      | H61M-S1                     | [5e8e9fbd71](https://linux-hardware.org/?probe=5e8e9fbd71) | Jul 26, 2022 |
| ASUSTek       | P8B75-M                     | [46e85f96ca](https://linux-hardware.org/?probe=46e85f96ca) | Jul 26, 2022 |
| ASUSTek       | AT5NM10T-I                  | [9738c4bebc](https://linux-hardware.org/?probe=9738c4bebc) | Jul 26, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | [9d3da43bea](https://linux-hardware.org/?probe=9d3da43bea) | Jul 25, 2022 |
| Dell          | 03NVJ6 A01                  | [3998c390f0](https://linux-hardware.org/?probe=3998c390f0) | Jul 25, 2022 |
| ASRock        | H470M Pro4                  | [5a709f059c](https://linux-hardware.org/?probe=5a709f059c) | Jul 25, 2022 |
| ASRockRack    | B565D4-V1L                  | [1301ad9bd0](https://linux-hardware.org/?probe=1301ad9bd0) | Jul 25, 2022 |
| Gigabyte      | B365M DS3H                  | [571655453a](https://linux-hardware.org/?probe=571655453a) | Jul 24, 2022 |
| AZW           | U59                         | [82e7dfdca5](https://linux-hardware.org/?probe=82e7dfdca5) | Jul 24, 2022 |
| ASUSTek       | TUF Gaming H570-PRO         | [36edefbce1](https://linux-hardware.org/?probe=36edefbce1) | Jul 24, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [de6f28d0f7](https://linux-hardware.org/?probe=de6f28d0f7) | Jul 24, 2022 |
| ASRock        | J5005-ITX                   | [8fdd045c35](https://linux-hardware.org/?probe=8fdd045c35) | Jul 24, 2022 |
| ASUSTek       | PRIME Z390-A                | [9a3ffce1a4](https://linux-hardware.org/?probe=9a3ffce1a4) | Jul 24, 2022 |
| ECS           | G31T-M9                     | [f7489c3b16](https://linux-hardware.org/?probe=f7489c3b16) | Jul 22, 2022 |
| MSI           | H110M PRO-VD                | [ffd65c627e](https://linux-hardware.org/?probe=ffd65c627e) | Jul 22, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | [7cd95094de](https://linux-hardware.org/?probe=7cd95094de) | Jul 21, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | [4655fe2442](https://linux-hardware.org/?probe=4655fe2442) | Jul 21, 2022 |
| MSI           | H110M PRO-VD                | [ffcc0670ba](https://linux-hardware.org/?probe=ffcc0670ba) | Jul 21, 2022 |
| Gigabyte      | M68MT-S2                    | [e505d3e2da](https://linux-hardware.org/?probe=e505d3e2da) | Jul 21, 2022 |
| MSI           | B150M BAZOOKA               | [41053f8c0e](https://linux-hardware.org/?probe=41053f8c0e) | Jul 21, 2022 |
| MSI           | G31TM-P21                   | [34b4e0a6ea](https://linux-hardware.org/?probe=34b4e0a6ea) | Jul 21, 2022 |
| Gigabyte      | M68MT-S2                    | [de41a6c75f](https://linux-hardware.org/?probe=de41a6c75f) | Jul 21, 2022 |
| Intel         | DH67BL AAG10189-209         | [8b924d9018](https://linux-hardware.org/?probe=8b924d9018) | Jul 21, 2022 |
| Dell          | 0HD5W2 A01                  | [e2eca7122c](https://linux-hardware.org/?probe=e2eca7122c) | Jul 21, 2022 |
| Intel         | DH67BL AAG10189-209         | [d9ce312767](https://linux-hardware.org/?probe=d9ce312767) | Jul 20, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [8ad4c64b76](https://linux-hardware.org/?probe=8ad4c64b76) | Jul 20, 2022 |
| MSI           | MS-7236                     | [e824199021](https://linux-hardware.org/?probe=e824199021) | Jul 20, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [b35dabeb45](https://linux-hardware.org/?probe=b35dabeb45) | Jul 20, 2022 |
| Acer          | Aspire TC-120               | [2625b243eb](https://linux-hardware.org/?probe=2625b243eb) | Jul 20, 2022 |
| Acer          | Aspire TC-120               | [25728e964b](https://linux-hardware.org/?probe=25728e964b) | Jul 20, 2022 |
| Thecus        | N2810 0001                  | [dd4d9fb1d5](https://linux-hardware.org/?probe=dd4d9fb1d5) | Jul 20, 2022 |
| Dell          | 07T4MC A11                  | [61d394116d](https://linux-hardware.org/?probe=61d394116d) | Jul 20, 2022 |
| Gigabyte      | B365M DS3H                  | [27bf18a32e](https://linux-hardware.org/?probe=27bf18a32e) | Jul 20, 2022 |
| Intel         | DH67BL AAG10189-209         | [ff8bfdfce1](https://linux-hardware.org/?probe=ff8bfdfce1) | Jul 19, 2022 |
| MSI           | H110M PRO-VD                | [ecf613ee2c](https://linux-hardware.org/?probe=ecf613ee2c) | Jul 19, 2022 |
| ASRock        | H470M-HVS                   | [2ccd5ab488](https://linux-hardware.org/?probe=2ccd5ab488) | Jul 19, 2022 |
| MSI           | H110M PRO-VD                | [069d79d670](https://linux-hardware.org/?probe=069d79d670) | Jul 19, 2022 |
| ASUSTek       | Z170M-PLUS                  | [85df5dd7a2](https://linux-hardware.org/?probe=85df5dd7a2) | Jul 19, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [4f256f41a7](https://linux-hardware.org/?probe=4f256f41a7) | Jul 19, 2022 |
| Gigabyte      | GA-880GM-UD2H               | [a5082efd70](https://linux-hardware.org/?probe=a5082efd70) | Jul 19, 2022 |
| Compaq        | 07A8h                       | [329d1b25c3](https://linux-hardware.org/?probe=329d1b25c3) | Jul 18, 2022 |
| MSI           | H110M PRO-VD                | [b9799fcb96](https://linux-hardware.org/?probe=b9799fcb96) | Jul 18, 2022 |
| ASUSTek       | P5K SE/EPU                  | [b2b12a6837](https://linux-hardware.org/?probe=b2b12a6837) | Jul 18, 2022 |
| ASUSTek       | P8Z77-V                     | [bb9f40d075](https://linux-hardware.org/?probe=bb9f40d075) | Jul 18, 2022 |
| ASRock        | X300M-STX                   | [150da602c4](https://linux-hardware.org/?probe=150da602c4) | Jul 17, 2022 |
| ASRock        | X300M-STX                   | [a46f6b3901](https://linux-hardware.org/?probe=a46f6b3901) | Jul 17, 2022 |
| Gigabyte      | F2A78M-DS2                  | [00a709911c](https://linux-hardware.org/?probe=00a709911c) | Jul 17, 2022 |
| Unknown       | Unknown                     | [e862207f95](https://linux-hardware.org/?probe=e862207f95) | Jul 15, 2022 |
| Gigabyte      | B450M S2H                   | [2fcccdc54a](https://linux-hardware.org/?probe=2fcccdc54a) | Jul 15, 2022 |
| HP            | 0B4Ch D                     | [a27d53815e](https://linux-hardware.org/?probe=a27d53815e) | Jul 15, 2022 |
| ASUSTek       | P8H61/USB3 R2.0             | [e53d3eb407](https://linux-hardware.org/?probe=e53d3eb407) | Jul 15, 2022 |
| Gigabyte      | B250M-DS3H-CF               | [85f6b3a720](https://linux-hardware.org/?probe=85f6b3a720) | Jul 14, 2022 |
| Intel         | DH67BL AAG10189-209         | [15c0aec8fc](https://linux-hardware.org/?probe=15c0aec8fc) | Jul 14, 2022 |
| Gigabyte      | H61M-DS2                    | [d0f1a65579](https://linux-hardware.org/?probe=d0f1a65579) | Jul 14, 2022 |
| Dell          | 09D2HH A00                  | [aadb1249e7](https://linux-hardware.org/?probe=aadb1249e7) | Jul 13, 2022 |
| Gigabyte      | H61M-DS2                    | [d581679f95](https://linux-hardware.org/?probe=d581679f95) | Jul 13, 2022 |
| ASUSTek       | H110M-R                     | [b1ec1ae2ba](https://linux-hardware.org/?probe=b1ec1ae2ba) | Jul 13, 2022 |
| ASRock        | H470M-HVS                   | [8f07cb2956](https://linux-hardware.org/?probe=8f07cb2956) | Jul 13, 2022 |
| Gigabyte      | B450M S2H                   | [0287348f80](https://linux-hardware.org/?probe=0287348f80) | Jul 12, 2022 |
| ASUSTek       | Maximus VIII HERO           | [491e37bdfb](https://linux-hardware.org/?probe=491e37bdfb) | Jul 12, 2022 |
| Dell          | 0N4YC8 A00                  | [7bee96ebd2](https://linux-hardware.org/?probe=7bee96ebd2) | Jul 12, 2022 |
| ECS           | G31T-M9                     | [3465370e70](https://linux-hardware.org/?probe=3465370e70) | Jul 11, 2022 |
| MSI           | H110M PRO-VD                | [4fd6d22bdc](https://linux-hardware.org/?probe=4fd6d22bdc) | Jul 11, 2022 |
| ASRock        | H470M-HVS                   | [d670acc906](https://linux-hardware.org/?probe=d670acc906) | Jul 11, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | [33c06e2d9c](https://linux-hardware.org/?probe=33c06e2d9c) | Jul 11, 2022 |
| MSI           | H110M PRO-VD                | [56a2a5762d](https://linux-hardware.org/?probe=56a2a5762d) | Jul 11, 2022 |
| MSI           | B350 GAMING PLUS            | [778b1989d4](https://linux-hardware.org/?probe=778b1989d4) | Jul 11, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | [abf6dfebe1](https://linux-hardware.org/?probe=abf6dfebe1) | Jul 11, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | [6aeac582a4](https://linux-hardware.org/?probe=6aeac582a4) | Jul 11, 2022 |
| Dell          | 042P49 A00                  | [58ae3712ed](https://linux-hardware.org/?probe=58ae3712ed) | Jul 10, 2022 |
| ASRock        | 990FX Killer                | [397d8bb63f](https://linux-hardware.org/?probe=397d8bb63f) | Jul 10, 2022 |
| ASRock        | Z77 Extreme6                | [fd8bd29c03](https://linux-hardware.org/?probe=fd8bd29c03) | Jul 09, 2022 |
| Lenovo        | 3132 SDK0R32862 WIN 3258... | [8c3180c6f5](https://linux-hardware.org/?probe=8c3180c6f5) | Jul 09, 2022 |
| Dell          | 0N4YC8 A00                  | [f83cbbc674](https://linux-hardware.org/?probe=f83cbbc674) | Jul 08, 2022 |
| ASRock        | H470M-HVS                   | [ec73826821](https://linux-hardware.org/?probe=ec73826821) | Jul 08, 2022 |
| ASRock        | H470M-HVS                   | [d6274d6dbb](https://linux-hardware.org/?probe=d6274d6dbb) | Jul 08, 2022 |
| ASRock        | H470M-HVS                   | [0d57ba971f](https://linux-hardware.org/?probe=0d57ba971f) | Jul 08, 2022 |
| ASRock        | H470M-HVS                   | [1d775a2c62](https://linux-hardware.org/?probe=1d775a2c62) | Jul 08, 2022 |
| ASRock        | H470M-HVS                   | [74b436de8d](https://linux-hardware.org/?probe=74b436de8d) | Jul 08, 2022 |
| ASRock        | H470M-HVS                   | [8a7a7fc746](https://linux-hardware.org/?probe=8a7a7fc746) | Jul 08, 2022 |
| ASRock        | H470M-HVS                   | [cfbc35dc7d](https://linux-hardware.org/?probe=cfbc35dc7d) | Jul 08, 2022 |
| ASRock        | M3A UCC                     | [a7ffeac935](https://linux-hardware.org/?probe=a7ffeac935) | Jul 08, 2022 |
| Intel         | DH61CR AAG14064-204         | [0ebf0eb484](https://linux-hardware.org/?probe=0ebf0eb484) | Jul 08, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [28a59cd061](https://linux-hardware.org/?probe=28a59cd061) | Jul 07, 2022 |
| Intel         | DQ35MP AAD82086-801         | [1f861ad92a](https://linux-hardware.org/?probe=1f861ad92a) | Jul 07, 2022 |
| ASRock        | B450M Pro4                  | [ff75212757](https://linux-hardware.org/?probe=ff75212757) | Jul 07, 2022 |
| Inventec      | D CLASS A02                 | [0fecc82851](https://linux-hardware.org/?probe=0fecc82851) | Jul 06, 2022 |
| congatec      | TS170 B.0                   | [b9469e26f8](https://linux-hardware.org/?probe=b9469e26f8) | Jul 06, 2022 |
| Gigabyte      | X99-UD4-CF                  | [5ac5b5f182](https://linux-hardware.org/?probe=5ac5b5f182) | Jul 06, 2022 |
| ECS           | G31T-M9                     | [f075057e96](https://linux-hardware.org/?probe=f075057e96) | Jul 06, 2022 |
| ASRockRack    | B565D4-V1L                  | [a363492ad6](https://linux-hardware.org/?probe=a363492ad6) | Jul 06, 2022 |
| Gigabyte      | B450M S2H V2                | [5da0f57567](https://linux-hardware.org/?probe=5da0f57567) | Jul 06, 2022 |
| MSI           | Creator TRX40               | [8d512a1405](https://linux-hardware.org/?probe=8d512a1405) | Jul 06, 2022 |
| ASRock        | K10N78D                     | [650465a972](https://linux-hardware.org/?probe=650465a972) | Jul 06, 2022 |
| Gigabyte      | B450M DS3H-CF               | [5636dc957a](https://linux-hardware.org/?probe=5636dc957a) | Jul 05, 2022 |
| HP            | 8433 11                     | [308e487f48](https://linux-hardware.org/?probe=308e487f48) | Jul 05, 2022 |
| MSI           | H61M-P31/W8                 | [ae5c00cbd0](https://linux-hardware.org/?probe=ae5c00cbd0) | Jul 05, 2022 |
| MSI           | H110M PRO-VD                | [cf4ef3e43e](https://linux-hardware.org/?probe=cf4ef3e43e) | Jul 05, 2022 |
| ASUSTek       | H97-PLUS                    | [07a45bcfef](https://linux-hardware.org/?probe=07a45bcfef) | Jul 04, 2022 |
| Intel         | MAHOBAY                     | [39c0379cee](https://linux-hardware.org/?probe=39c0379cee) | Jul 04, 2022 |
| MSI           | H510M-A PRO                 | [12a1f193b8](https://linux-hardware.org/?probe=12a1f193b8) | Jul 04, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [9fd928b97f](https://linux-hardware.org/?probe=9fd928b97f) | Jul 03, 2022 |
| Gigabyte      | 945GCM-S2L                  | [2d627ba67d](https://linux-hardware.org/?probe=2d627ba67d) | Jul 03, 2022 |
| BESSTAR Te... | HM90                        | [064e176be8](https://linux-hardware.org/?probe=064e176be8) | Jul 02, 2022 |
| ASUSTek       | H97-PLUS                    | [85de5cfaff](https://linux-hardware.org/?probe=85de5cfaff) | Jul 02, 2022 |
| MSI           | 880GMA-E35                  | [8bcc34797b](https://linux-hardware.org/?probe=8bcc34797b) | Jul 02, 2022 |
| ASRock        | B450M Pro4                  | [64eae559ae](https://linux-hardware.org/?probe=64eae559ae) | Jul 02, 2022 |
| Gigabyte      | H81M-DS2V                   | [5f35ee7109](https://linux-hardware.org/?probe=5f35ee7109) | Jul 01, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [d7d9387e6d](https://linux-hardware.org/?probe=d7d9387e6d) | Jul 01, 2022 |
| Gigabyte      | B85M-D3H                    | [d0d9e7b5c7](https://linux-hardware.org/?probe=d0d9e7b5c7) | Jul 01, 2022 |
| MSI           | B75MA-E33                   | [482aec0a52](https://linux-hardware.org/?probe=482aec0a52) | Jun 30, 2022 |
| ASUSTek       | P5KPL-E                     | [c969c7cce8](https://linux-hardware.org/?probe=c969c7cce8) | Jun 30, 2022 |
| Dell          | 0D441T A01                  | [b205bc201e](https://linux-hardware.org/?probe=b205bc201e) | Jun 29, 2022 |
| Dell          | 0M858N A01                  | [6cc8dcd51e](https://linux-hardware.org/?probe=6cc8dcd51e) | Jun 29, 2022 |
| Gigabyte      | B150-HD3 DDR3-CF            | [3fe71d66c6](https://linux-hardware.org/?probe=3fe71d66c6) | Jun 28, 2022 |
| ECS           | G41T-M16                    | [5a3363d66f](https://linux-hardware.org/?probe=5a3363d66f) | Jun 28, 2022 |
| Intel         | D945PLRN AAD32731-404       | [d9519690b8](https://linux-hardware.org/?probe=d9519690b8) | Jun 28, 2022 |
| ASUSTek       | B85M-G                      | [642e677d05](https://linux-hardware.org/?probe=642e677d05) | Jun 27, 2022 |
| ASUSTek       | PRIME B450M-A               | [60810eb934](https://linux-hardware.org/?probe=60810eb934) | Jun 27, 2022 |
| ASUSTek       | PRIME B450M-A               | [6ab12fa31e](https://linux-hardware.org/?probe=6ab12fa31e) | Jun 27, 2022 |
| Maxtang       | FP30 V1.0                   | [6d86a132d4](https://linux-hardware.org/?probe=6d86a132d4) | Jun 26, 2022 |
| ASUSTek       | P8Z77-V PRO                 | [838a928e6a](https://linux-hardware.org/?probe=838a928e6a) | Jun 26, 2022 |
| Gigabyte      | M52LT-D3                    | [6c650dabf3](https://linux-hardware.org/?probe=6c650dabf3) | Jun 24, 2022 |
| Gigabyte      | B150-HD3P-CF                | [c62062eac9](https://linux-hardware.org/?probe=c62062eac9) | Jun 24, 2022 |
| Intel         | MAHOBAY                     | [c292904665](https://linux-hardware.org/?probe=c292904665) | Jun 24, 2022 |
| Lenovo        | ThinkServer TS440           | [e68364c28e](https://linux-hardware.org/?probe=e68364c28e) | Jun 24, 2022 |
| Gigabyte      | H470M DS3H                  | [624ad307fc](https://linux-hardware.org/?probe=624ad307fc) | Jun 24, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [cf76d2d9a4](https://linux-hardware.org/?probe=cf76d2d9a4) | Jun 23, 2022 |
| HP            | 830C                        | [7e34e5c70d](https://linux-hardware.org/?probe=7e34e5c70d) | Jun 23, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [c44391986b](https://linux-hardware.org/?probe=c44391986b) | Jun 23, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | [2c1f55aa8f](https://linux-hardware.org/?probe=2c1f55aa8f) | Jun 23, 2022 |
| ECS           | G31T-M9                     | [79e0e345f0](https://linux-hardware.org/?probe=79e0e345f0) | Jun 23, 2022 |
| Dell          | 0J8885                      | [06e5e2fe54](https://linux-hardware.org/?probe=06e5e2fe54) | Jun 23, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [989b450d8b](https://linux-hardware.org/?probe=989b450d8b) | Jun 23, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [39cc29c976](https://linux-hardware.org/?probe=39cc29c976) | Jun 23, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | [d5d735e981](https://linux-hardware.org/?probe=d5d735e981) | Jun 22, 2022 |
| Gigabyte      | B660M GAMING X DDR4         | [d2d5590419](https://linux-hardware.org/?probe=d2d5590419) | Jun 22, 2022 |
| MSI           | H110M PRO-VD                | [a46ae32016](https://linux-hardware.org/?probe=a46ae32016) | Jun 22, 2022 |
| Gigabyte      | H97M-D3H                    | [1529cf29a5](https://linux-hardware.org/?probe=1529cf29a5) | Jun 22, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian_11/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.10.0-7-amd64         | 513      | 24.48%  |
| 5.10.0-8-amd64         | 230      | 10.97%  |
| 5.10.0-9-amd64         | 119      | 5.68%   |
| 5.10.0-19-amd64        | 100      | 4.77%   |
| 5.10.0-2-amd64         | 98       | 4.68%   |
| 5.10.0-13-amd64        | 85       | 4.06%   |
| 5.10.0-18-amd64        | 76       | 3.63%   |
| 5.10.0-11-amd64        | 72       | 3.44%   |
| 5.10.0-20-amd64        | 71       | 3.39%   |
| 5.10.0-10-amd64        | 69       | 3.29%   |
| 5.10.0-16-amd64        | 68       | 3.24%   |
| 5.10.0-14-amd64        | 49       | 2.34%   |
| 5.10.0-17-amd64        | 42       | 2%      |
| 5.10.0-15-amd64        | 36       | 1.72%   |
| 5.10.0-12-amd64        | 29       | 1.38%   |
| 5.15.0-2-amd64         | 22       | 1.05%   |
| 5.18.0-0.bpo.1-amd64   | 16       | 0.76%   |
| 5.16.0-0.bpo.4-amd64   | 15       | 0.72%   |
| 5.13.19-2-pve          | 14       | 0.67%   |
| 5.18.0-0.deb11.4-amd64 | 13       | 0.62%   |
| 5.13.19-6-pve          | 13       | 0.62%   |
| 5.10.0-6-amd64         | 13       | 0.62%   |
| 5.10.0-21-amd64        | 11       | 0.52%   |
| 5.15.53-1-pve          | 10       | 0.48%   |
| 5.15.35-1-pve          | 9        | 0.43%   |
| 5.15.30-2-pve          | 9        | 0.43%   |
| 6.0.0-0.deb11.2-amd64  | 8        | 0.38%   |
| 5.19.0-2-amd64         | 7        | 0.33%   |
| 5.19.0-0.deb11.2-amd64 | 7        | 0.33%   |
| 5.14.0-0.bpo.2-amd64   | 7        | 0.33%   |
| 5.11.22-4-pve          | 7        | 0.33%   |
| 5.15.74-1-pve          | 6        | 0.29%   |
| 5.15.39-4-pve          | 6        | 0.29%   |
| 5.13.19-1-pve          | 6        | 0.29%   |
| 6.0.0-0.deb11.6-amd64  | 5        | 0.24%   |
| 5.15.83-1-pve          | 5        | 0.24%   |
| 5.15.39-1-pve          | 5        | 0.24%   |
| 5.10.0-9-686           | 5        | 0.24%   |
| 5.18.0-2-amd64         | 4        | 0.19%   |
| 5.17.0-1-amd64         | 4        | 0.19%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.0   | 1634     | 82.23%  |
| 5.18.0   | 42       | 2.11%   |
| 5.13.19  | 38       | 1.91%   |
| 5.15.0   | 34       | 1.71%   |
| 5.16.0   | 26       | 1.31%   |
| 5.19.0   | 18       | 0.91%   |
| 6.0.0    | 17       | 0.86%   |
| 5.11.22  | 17       | 0.86%   |
| 5.14.0   | 16       | 0.81%   |
| 5.15.39  | 13       | 0.65%   |
| 5.15.35  | 13       | 0.65%   |
| 5.15.53  | 10       | 0.5%    |
| 5.17.0   | 9        | 0.45%   |
| 5.15.30  | 9        | 0.45%   |
| 5.15.74  | 6        | 0.3%    |
| 5.15.83  | 5        | 0.25%   |
| 6.0.8    | 4        | 0.2%    |
| 5.13.0   | 4        | 0.2%    |
| 6.1.0    | 3        | 0.15%   |
| 5.19.17  | 3        | 0.15%   |
| 5.16.5   | 3        | 0.15%   |
| 5.15.60  | 3        | 0.15%   |
| 4.19.0   | 3        | 0.15%   |
| 5.4.0    | 2        | 0.1%    |
| 5.15.64  | 2        | 0.1%    |
| 5.15.19  | 2        | 0.1%    |
| 5.15.12  | 2        | 0.1%    |
| 5.13.13  | 2        | 0.1%    |
| 5.11.0   | 2        | 0.1%    |
| 5.10.81  | 2        | 0.1%    |
| 5.10.57  | 2        | 0.1%    |
| 5.10.46  | 2        | 0.1%    |
| 5.10.109 | 2        | 0.1%    |
| 6.0.3    | 1        | 0.05%   |
| 5.8.0    | 1        | 0.05%   |
| 5.5.0    | 1        | 0.05%   |
| 5.4.148  | 1        | 0.05%   |
| 5.19.8   | 1        | 0.05%   |
| 5.19.7   | 1        | 0.05%   |
| 5.19.15  | 1        | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 1652     | 83.39%  |
| 5.15    | 97       | 4.9%    |
| 5.13    | 48       | 2.42%   |
| 5.18    | 46       | 2.32%   |
| 5.16    | 31       | 1.56%   |
| 5.19    | 25       | 1.26%   |
| 6.0     | 21       | 1.06%   |
| 5.11    | 20       | 1.01%   |
| 5.14    | 17       | 0.86%   |
| 5.17    | 11       | 0.56%   |
| 6.1     | 3        | 0.15%   |
| 5.4     | 3        | 0.15%   |
| 4.19    | 3        | 0.15%   |
| 5.8     | 1        | 0.05%   |
| 5.5     | 1        | 0.05%   |
| 5.12    | 1        | 0.05%   |
| 5.1     | 1        | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 1896     | 97.58%  |
| i686    | 44       | 2.26%   |
| riscv64 | 2        | 0.1%    |
| armv7l  | 1        | 0.05%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Unknown           | 861      | 43.71%  |
| GNOME             | 348      | 17.66%  |
| KDE5              | 209      | 10.61%  |
| XFCE              | 205      | 10.41%  |
| MATE              | 81       | 4.11%   |
| X-Cinnamon        | 61       | 3.1%    |
| LXDE              | 47       | 2.39%   |
| Cinnamon          | 44       | 2.23%   |
| LXQt              | 24       | 1.22%   |
| i3                | 18       | 0.91%   |
| KDE               | 12       | 0.61%   |
| trinity           | 11       | 0.56%   |
| lightdm-xsession  | 10       | 0.51%   |
| Openbox           | 9        | 0.46%   |
| GNOME Flashback   | 9        | 0.46%   |
| Budgie            | 7        | 0.36%   |
| sway              | 3        | 0.15%   |
| awesome           | 3        | 0.15%   |
| GNOME Classic     | 2        | 0.1%    |
| UKUI              | 1        | 0.05%   |
| GNUstep           | 1        | 0.05%   |
| Enlightenment     | 1        | 0.05%   |
| e16-session       | 1        | 0.05%   |
| DWM               | 1        | 0.05%   |
| /etc/X11/Xsession | 1        | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 852      | 43.4%   |
| Unknown | 630      | 32.09%  |
| Tty     | 292      | 14.88%  |
| Wayland | 188      | 9.58%   |
| Web     | 1        | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1099     | 56.13%  |
| LightDM | 314      | 16.04%  |
| GDM     | 255      | 13.02%  |
| SDDM    | 167      | 8.53%   |
| TDM     | 72       | 3.68%   |
| GDM3    | 35       | 1.79%   |
| SLiM    | 6        | 0.31%   |
| XDM     | 5        | 0.26%   |
| NODM    | 3        | 0.15%   |
| LXDM    | 2        | 0.1%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| ru_RU   | 636      | 32.6%   |
| en_US   | 614      | 31.47%  |
| de_DE   | 91       | 4.66%   |
| fr_FR   | 88       | 4.51%   |
| en_GB   | 81       | 4.15%   |
| es_ES   | 49       | 2.51%   |
| pt_BR   | 46       | 2.36%   |
| it_IT   | 39       | 2%      |
| Unknown | 36       | 1.85%   |
| en_AU   | 25       | 1.28%   |
| en_CA   | 24       | 1.23%   |
| C       | 21       | 1.08%   |
| pl_PL   | 17       | 0.87%   |
| ja_JP   | 11       | 0.56%   |
| hu_HU   | 11       | 0.56%   |
| en_IE   | 11       | 0.56%   |
| es_MX   | 10       | 0.51%   |
| es_AR   | 10       | 0.51%   |
| es_VE   | 9        | 0.46%   |
| zh_CN   | 8        | 0.41%   |
| de_AT   | 8        | 0.41%   |
| pt_PT   | 6        | 0.31%   |
| nl_BE   | 6        | 0.31%   |
| en_IN   | 5        | 0.26%   |
| uk_UA   | 4        | 0.21%   |
| nl_NL   | 4        | 0.21%   |
| fr_BE   | 4        | 0.21%   |
| en_NZ   | 4        | 0.21%   |
| de_CH   | 4        | 0.21%   |
| cs_CZ   | 4        | 0.21%   |
| ca_ES   | 4        | 0.21%   |
| sv_SE   | 3        | 0.15%   |
| ru_UA   | 3        | 0.15%   |
| hr_HR   | 3        | 0.15%   |
| es_CO   | 3        | 0.15%   |
| en_ZA   | 3        | 0.15%   |
| en_HK   | 3        | 0.15%   |
| bg_BG   | 3        | 0.15%   |
| ro_RO   | 2        | 0.1%    |
| fr_CH   | 2        | 0.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1292     | 65.45%  |
| EFI  | 682      | 34.55%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 1181     | 60.5%   |
| Overlay | 628      | 32.17%  |
| Btrfs   | 68       | 3.48%   |
| Zfs     | 37       | 1.9%    |
| Xfs     | 21       | 1.08%   |
| Ext3    | 9        | 0.46%   |
| Unknown | 3        | 0.15%   |
| Tmpfs   | 2        | 0.1%    |
| Ext2    | 2        | 0.1%    |
| Rootfs  | 1        | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 868      | 44.02%  |
| GPT     | 829      | 42.04%  |
| Unknown | 275      | 13.95%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1614     | 82.52%  |
| Yes       | 342      | 17.48%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1049     | 53.58%  |
| Yes       | 909      | 46.42%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 547      | 28.17%  |
| Gigabyte Technology | 344      | 17.71%  |
| MSI                 | 206      | 10.61%  |
| ASRock              | 187      | 9.63%   |
| Dell                | 132      | 6.8%    |
| Hewlett-Packard     | 110      | 5.66%   |
| Lenovo              | 62       | 3.19%   |
| Intel               | 61       | 3.14%   |
| ECS                 | 45       | 2.32%   |
| Foxconn             | 27       | 1.39%   |
| Unknown             | 22       | 1.13%   |
| Fujitsu             | 19       | 0.98%   |
| ASRockRack          | 19       | 0.98%   |
| Supermicro          | 14       | 0.72%   |
| Acer                | 13       | 0.67%   |
| Pegatron            | 11       | 0.57%   |
| Biostar             | 11       | 0.57%   |
| AZW                 | 8        | 0.41%   |
| Inventec            | 6        | 0.31%   |
| Medion              | 5        | 0.26%   |
| Huanan              | 5        | 0.26%   |
| BESSTAR Tech        | 5        | 0.26%   |
| Apple               | 5        | 0.26%   |
| Positivo            | 4        | 0.21%   |
| Google              | 4        | 0.21%   |
| Shuttle             | 3        | 0.15%   |
| Packard Bell        | 3        | 0.15%   |
| Fujitsu Siemens     | 3        | 0.15%   |
| Thecus              | 2        | 0.1%    |
| Techvision          | 2        | 0.1%    |
| Semp Toshiba        | 2        | 0.1%    |
| PC Engines          | 2        | 0.1%    |
| IceWhale Technology | 2        | 0.1%    |
| HPE                 | 2        | 0.1%    |
| Hardkernel          | 2        | 0.1%    |
| Gateway             | 2        | 0.1%    |
| Aquarius            | 2        | 0.1%    |
| AAEON               | 2        | 0.1%    |
| ZOTAC               | 1        | 0.05%   |
| Wistron             | 1        | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS All Series              | 73       | 3.76%   |
| ASUS S20 K29                 | 55       | 2.83%   |
| MSI MS-7996                  | 37       | 1.91%   |
| Unknown                      | 23       | 1.18%   |
| ECS G31T-M9                  | 21       | 1.08%   |
| ASRock H470M-HVS             | 20       | 1.03%   |
| MSI MS-7817                  | 19       | 0.98%   |
| Gigabyte H81M-S2V            | 17       | 0.88%   |
| ASUS PRIME H510M-A           | 17       | 0.88%   |
| Gigabyte H410M S2H           | 16       | 0.82%   |
| ECS H61H2-M13                | 16       | 0.82%   |
| ASUS P8H61-M LX3 R2.0        | 15       | 0.77%   |
| Dell OptiPlex 7010           | 13       | 0.67%   |
| Gigabyte B450M DS3H          | 10       | 0.51%   |
| ASUS PRIME B450M-A           | 9        | 0.46%   |
| ASUS H110M-R                 | 9        | 0.46%   |
| Gigabyte B360M H             | 8        | 0.41%   |
| ASUS PRIME A320M-K           | 8        | 0.41%   |
| ASUS P8H67-M                 | 8        | 0.41%   |
| MSI MS-7C56                  | 7        | 0.36%   |
| Fujitsu ESPRIMO P720         | 7        | 0.36%   |
| ASUS TUF Gaming X570-PLUS    | 7        | 0.36%   |
| ASUS P8H61-M LX3 PLUS R2.0   | 7        | 0.36%   |
| ASUS P5G41T-M LE             | 7        | 0.36%   |
| ASRock H61M-VG4              | 7        | 0.36%   |
| ASRock G31M-VS2              | 7        | 0.36%   |
| ASRock B450M Pro4            | 7        | 0.36%   |
| Intel Pro, Std, Elt Series   | 6        | 0.31%   |
| HP Z620 Workstation          | 6        | 0.31%   |
| HP ProLiant MicroServer Gen8 | 6        | 0.31%   |
| Gigabyte P85-D3              | 6        | 0.31%   |
| Gigabyte GA-78LMT-USB3       | 6        | 0.31%   |
| Gigabyte B85M-D3H            | 6        | 0.31%   |
| Gigabyte A320M-S2H           | 6        | 0.31%   |
| ASUS Pro WS 565-ACE          | 6        | 0.31%   |
| MSI MS-7C95                  | 5        | 0.26%   |
| MSI MS-7C84                  | 5        | 0.26%   |
| MSI MS-7C02                  | 5        | 0.26%   |
| HP Z420 Workstation          | 5        | 0.26%   |
| HP ProLiant MicroServer      | 5        | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 104      | 5.36%   |
| ASUS All               | 73       | 3.76%   |
| Dell OptiPlex          | 72       | 3.71%   |
| ASUS S20               | 55       | 2.83%   |
| MSI MS-7996            | 37       | 1.91%   |
| Lenovo ThinkCentre     | 36       | 1.85%   |
| ASUS ROG               | 35       | 1.8%    |
| ASUS TUF               | 32       | 1.65%   |
| ASUS P8H61-M           | 31       | 1.6%    |
| HP Compaq              | 30       | 1.54%   |
| Dell Precision         | 27       | 1.39%   |
| Gigabyte B450M         | 23       | 1.18%   |
| Unknown                | 23       | 1.18%   |
| ECS G31T-M9            | 21       | 1.08%   |
| ASRock H470M-HVS       | 20       | 1.03%   |
| MSI MS-7817            | 19       | 0.98%   |
| ASUS PRO               | 19       | 0.98%   |
| Gigabyte H410M         | 18       | 0.93%   |
| Gigabyte H81M-S2V      | 17       | 0.88%   |
| ECS H61H2-M13          | 16       | 0.82%   |
| HP ProLiant            | 15       | 0.77%   |
| HP EliteDesk           | 14       | 0.72%   |
| Fujitsu ESPRIMO        | 12       | 0.62%   |
| ASUS P5G41T-M          | 11       | 0.57%   |
| ASRock B450M           | 11       | 0.57%   |
| Lenovo ThinkStation    | 10       | 0.51%   |
| Gigabyte X570          | 10       | 0.51%   |
| ASUS P8H67-M           | 10       | 0.51%   |
| Gigabyte H61M-DS2      | 9        | 0.46%   |
| Gigabyte B360M         | 9        | 0.46%   |
| Dell XPS               | 9        | 0.46%   |
| ASUS H110M-R           | 9        | 0.46%   |
| ASRock B450            | 9        | 0.46%   |
| HP ProDesk             | 8        | 0.41%   |
| Gigabyte GA-78LMT-USB3 | 8        | 0.41%   |
| Gigabyte A320M-S2H     | 8        | 0.41%   |
| Dell Vostro            | 8        | 0.41%   |
| Dell Inspiron          | 8        | 0.41%   |
| ASUS M5A97             | 8        | 0.41%   |
| MSI MS-7C56            | 7        | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2020    | 220      | 11.33%  |
| 2012    | 199      | 10.25%  |
| 2013    | 173      | 8.91%   |
| 2018    | 172      | 8.86%   |
| 2021    | 164      | 8.44%   |
| 2011    | 132      | 6.8%    |
| 2019    | 116      | 5.97%   |
| 2014    | 108      | 5.56%   |
| 2015    | 105      | 5.41%   |
| 2009    | 105      | 5.41%   |
| 2017    | 87       | 4.48%   |
| 2010    | 78       | 4.02%   |
| 2008    | 74       | 3.81%   |
| 2016    | 73       | 3.76%   |
| 2022    | 44       | 2.27%   |
| 2007    | 43       | 2.21%   |
| 2006    | 20       | 1.03%   |
| 2005    | 15       | 0.77%   |
| 2003    | 5        | 0.26%   |
| 2001    | 3        | 0.15%   |
| Unknown | 3        | 0.15%   |
| 2004    | 2        | 0.1%    |
| 2000    | 1        | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1942     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 1917     | 98.46%  |
| Enabled  | 30       | 1.54%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1932     | 99.49%  |
| Yes  | 10       | 0.51%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 4.01-8.0        | 391      | 19.95%  |
| 16.01-24.0      | 363      | 18.52%  |
| 3.01-4.0        | 341      | 17.4%   |
| 8.01-16.0       | 274      | 13.98%  |
| 32.01-64.0      | 235      | 11.99%  |
| 64.01-256.0     | 151      | 7.7%    |
| 1.01-2.0        | 102      | 5.2%    |
| 24.01-32.0      | 40       | 2.04%   |
| 2.01-3.0        | 38       | 1.94%   |
| 0.51-1.0        | 10       | 0.51%   |
| More than 256.0 | 9        | 0.46%   |
| 0.01-0.5        | 6        | 0.31%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 0.51-1.0    | 686      | 33.51%  |
| 1.01-2.0    | 385      | 18.81%  |
| 2.01-3.0    | 287      | 14.02%  |
| 4.01-8.0    | 254      | 12.41%  |
| 3.01-4.0    | 176      | 8.6%    |
| 8.01-16.0   | 96       | 4.69%   |
| 0.01-0.5    | 73       | 3.57%   |
| 16.01-24.0  | 45       | 2.2%    |
| 32.01-64.0  | 23       | 1.12%   |
| 24.01-32.0  | 14       | 0.68%   |
| 64.01-256.0 | 8        | 0.39%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 1032     | 51.96%  |
| 2      | 398      | 20.04%  |
| 3      | 224      | 11.28%  |
| 4      | 150      | 7.55%   |
| 5      | 70       | 3.52%   |
| 6      | 36       | 1.81%   |
| 7      | 22       | 1.11%   |
| 8      | 17       | 0.86%   |
| 0      | 11       | 0.55%   |
| 10     | 7        | 0.35%   |
| 9      | 6        | 0.3%    |
| 13     | 3        | 0.15%   |
| 12     | 3        | 0.15%   |
| 11     | 2        | 0.1%    |
| 28     | 1        | 0.05%   |
| 27     | 1        | 0.05%   |
| 21     | 1        | 0.05%   |
| 18     | 1        | 0.05%   |
| 14     | 1        | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1293     | 66.21%  |
| Yes       | 660      | 33.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1933     | 99.54%  |
| No        | 9        | 0.46%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1424     | 72.95%  |
| Yes       | 528      | 27.05%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1544     | 79.06%  |
| Yes       | 409      | 20.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Russia       | 652      | 33.54%  |
| USA          | 272      | 13.99%  |
| Germany      | 161      | 8.28%   |
| France       | 111      | 5.71%   |
| Spain        | 66       | 3.4%    |
| UK           | 58       | 2.98%   |
| Brazil       | 57       | 2.93%   |
| Italy        | 51       | 2.62%   |
| Canada       | 43       | 2.21%   |
| Australia    | 36       | 1.85%   |
| Poland       | 33       | 1.7%    |
| Netherlands  | 24       | 1.23%   |
| Ukraine      | 20       | 1.03%   |
| Mexico       | 19       | 0.98%   |
| Hungary      | 18       | 0.93%   |
| Belgium      | 18       | 0.93%   |
| Austria      | 18       | 0.93%   |
| Argentina    | 18       | 0.93%   |
| Switzerland  | 17       | 0.87%   |
| Portugal     | 13       | 0.67%   |
| Japan        | 13       | 0.67%   |
| China        | 12       | 0.62%   |
| Bulgaria     | 12       | 0.62%   |
| Venezuela    | 11       | 0.57%   |
| Czechia      | 11       | 0.57%   |
| Sweden       | 10       | 0.51%   |
| Romania      | 10       | 0.51%   |
| Finland      | 10       | 0.51%   |
| Norway       | 8        | 0.41%   |
| India        | 8        | 0.41%   |
| Denmark      | 7        | 0.36%   |
| Croatia      | 7        | 0.36%   |
| Turkey       | 6        | 0.31%   |
| Pakistan     | 6        | 0.31%   |
| Ireland      | 6        | 0.31%   |
| Belarus      | 6        | 0.31%   |
| South Africa | 5        | 0.26%   |
| Hong Kong    | 5        | 0.26%   |
| Colombia     | 5        | 0.26%   |
| Taiwan       | 4        | 0.21%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Voronezh          | 555      | 28%     |
| Moscow            | 25       | 1.26%   |
| St Petersburg     | 15       | 0.76%   |
| Vienna            | 14       | 0.71%   |
| Paris             | 13       | 0.66%   |
| Falkenstein       | 12       | 0.61%   |
| Bangor            | 12       | 0.61%   |
| Seville           | 11       | 0.55%   |
| Sao Paulo         | 11       | 0.55%   |
| Barcelona         | 11       | 0.55%   |
| Dover-Foxcroft    | 10       | 0.5%    |
| Berlin            | 9        | 0.45%   |
| Toronto           | 7        | 0.35%   |
| Sydney            | 7        | 0.35%   |
| Munich            | 7        | 0.35%   |
| Milan             | 7        | 0.35%   |
| London            | 7        | 0.35%   |
| Chicago           | 7        | 0.35%   |
| Brisbane          | 7        | 0.35%   |
| Zurich            | 6        | 0.3%    |
| Warsaw            | 6        | 0.3%    |
| Stockholm         | 6        | 0.3%    |
| Sofia             | 6        | 0.3%    |
| Ocala             | 6        | 0.3%    |
| Melbourne         | 6        | 0.3%    |
| Leipzig           | 6        | 0.3%    |
| Cologne           | 6        | 0.3%    |
| Buenos Aires      | 6        | 0.3%    |
| Windsor           | 5        | 0.25%   |
| San Jose          | 5        | 0.25%   |
| Rio de Janeiro    | 5        | 0.25%   |
| Orlando           | 5        | 0.25%   |
| Nuremberg         | 5        | 0.25%   |
| Lyon              | 5        | 0.25%   |
| Los Angeles       | 5        | 0.25%   |
| Las Vegas         | 5        | 0.25%   |
| Kyiv              | 5        | 0.25%   |
| Frankfurt am Main | 5        | 0.25%   |
| Caracas           | 5        | 0.25%   |
| Budapest          | 5        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 596      | 1016   | 18.53%  |
| WDC                 | 569      | 931    | 17.69%  |
| Samsung Electronics | 454      | 698    | 14.11%  |
| Kingston            | 256      | 322    | 7.96%   |
| Toshiba             | 237      | 426    | 7.37%   |
| Crucial             | 206      | 254    | 6.4%    |
| Hitachi             | 118      | 163    | 3.67%   |
| SanDisk             | 103      | 127    | 3.2%    |
| Intel               | 61       | 80     | 1.9%    |
| China               | 44       | 54     | 1.37%   |
| A-DATA Technology   | 43       | 54     | 1.34%   |
| HGST                | 42       | 70     | 1.31%   |
| SPCC                | 32       | 37     | 0.99%   |
| Unknown             | 26       | 42     | 0.81%   |
| Netac               | 24       | 83     | 0.75%   |
| PNY                 | 21       | 27     | 0.65%   |
| Maxtor              | 19       | 21     | 0.59%   |
| Phison              | 17       | 22     | 0.53%   |
| Corsair             | 17       | 29     | 0.53%   |
| Patriot             | 16       | 18     | 0.5%    |
| Micron Technology   | 16       | 19     | 0.5%    |
| Intenso             | 16       | 20     | 0.5%    |
| Hewlett-Packard     | 16       | 30     | 0.5%    |
| Transcend           | 15       | 16     | 0.47%   |
| OCZ                 | 14       | 18     | 0.44%   |
| SK hynix            | 13       | 24     | 0.4%    |
| Gigabyte Technology | 13       | 15     | 0.4%    |
| Unknown             | 11       | 12     | 0.34%   |
| GOODRAM             | 9        | 21     | 0.28%   |
| XPG                 | 8        | 10     | 0.25%   |
| Apacer              | 8        | 8      | 0.25%   |
| JMicron Technology  | 7        | 7      | 0.22%   |
| Hajaan              | 7        | 9      | 0.22%   |
| KIOXIA              | 6        | 8      | 0.19%   |
| Team                | 5        | 6      | 0.16%   |
| T-FORCE             | 5        | 7      | 0.16%   |
| Phison Electronics  | 5        | 6      | 0.16%   |
| Mushkin             | 5        | 6      | 0.16%   |
| LITEON              | 5        | 6      | 0.16%   |
| KIOXIA-EXCERIA      | 5        | 9      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 77       | 2.06%   |
| Crucial CT480BX500SSD1 480GB     | 65       | 1.74%   |
| Kingston SA400S37240G 240GB SSD  | 64       | 1.72%   |
| Toshiba DT01ACA050 500GB         | 55       | 1.47%   |
| Seagate ST1000DM010-2EP102 1TB   | 44       | 1.18%   |
| Kingston SV300S37A120G 120GB SSD | 37       | 0.99%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 34       | 0.91%   |
| Samsung SSD 860 EVO 250GB        | 34       | 0.91%   |
| Kingston SA400S37480G 480GB SSD  | 33       | 0.88%   |
| Hitachi HDS721050CLA362 500GB    | 31       | 0.83%   |
| Samsung SSD 860 EVO 1TB          | 30       | 0.8%    |
| WDC WD10EZEX-08WN4A0 1TB         | 29       | 0.78%   |
| Toshiba HDWD110 1TB              | 29       | 0.78%   |
| Toshiba DT01ACA100 1TB           | 29       | 0.78%   |
| Seagate ST1000DM003-1ER162 1TB   | 26       | 0.7%    |
| Samsung SSD 970 EVO Plus 500GB   | 26       | 0.7%    |
| Samsung SSD 860 EVO 500GB        | 25       | 0.67%   |
| Seagate ST2000DM008-2FR102 2TB   | 23       | 0.62%   |
| Samsung SSD 970 EVO Plus 1TB     | 22       | 0.59%   |
| Crucial CT500MX500SSD1 500GB     | 22       | 0.59%   |
| Crucial CT1000MX500SSD1 1TB      | 22       | 0.59%   |
| Seagate ST1000DM003-1CH162 1TB   | 21       | 0.56%   |
| Kingston SA400S37120G 120GB SSD  | 21       | 0.56%   |
| Crucial CT240BX500SSD1 240GB     | 21       | 0.56%   |
| Netac SSD 240GB                  | 20       | 0.54%   |
| Samsung SSD 850 EVO 250GB        | 19       | 0.51%   |
| Seagate ST3250318AS 249GB        | 17       | 0.46%   |
| Toshiba DT01ACA200 2TB           | 16       | 0.43%   |
| Seagate ST4000DM004-2CV104 4TB   | 16       | 0.43%   |
| Seagate ST3500418AS 500GB        | 16       | 0.43%   |
| Samsung SSD 850 EVO 500GB        | 16       | 0.43%   |
| Samsung SSD 870 EVO 500GB        | 15       | 0.4%    |
| WDC WD5000AAKX-08U6AA0 500GB     | 14       | 0.38%   |
| Seagate ST2000DM001-1ER164 2TB   | 14       | 0.38%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 13       | 0.35%   |
| Seagate ST250DM000-1BD141 250GB  | 13       | 0.35%   |
| Kingston SUV400S37120G 120GB SSD | 13       | 0.35%   |
| Crucial CT250MX500SSD1 250GB     | 13       | 0.35%   |
| WDC WD10EZEX-00BN5A0 1TB         | 12       | 0.32%   |
| SPCC Solid State Disk 120GB      | 12       | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 583      | 980    | 37.09%  |
| WDC                 | 498      | 817    | 31.68%  |
| Toshiba             | 220      | 401    | 13.99%  |
| Hitachi             | 118      | 163    | 7.51%   |
| Samsung Electronics | 51       | 66     | 3.24%   |
| HGST                | 42       | 70     | 2.67%   |
| Maxtor              | 19       | 21     | 1.21%   |
| Unknown             | 7        | 12     | 0.45%   |
| Hewlett-Packard     | 5        | 14     | 0.32%   |
| SABRENT             | 4        | 4      | 0.25%   |
| Intenso             | 3        | 3      | 0.19%   |
| Fujitsu             | 3        | 4      | 0.19%   |
| HPE                 | 2        | 6      | 0.13%   |
| Synology            | 1        | 1      | 0.06%   |
| StoreJet            | 1        | 1      | 0.06%   |
| RSH-319             | 1        | 1      | 0.06%   |
| QNAP                | 1        | 1      | 0.06%   |
| pqi                 | 1        | 1      | 0.06%   |
| NAS                 | 1        | 5      | 0.06%   |
| MaxDigital          | 1        | 4      | 0.06%   |
| MARSHAL             | 1        | 1      | 0.06%   |
| IBM/Hitachi         | 1        | 1      | 0.06%   |
| Hajaan              | 1        | 1      | 0.06%   |
| ASMT                | 1        | 1      | 0.06%   |
| ASMedia             | 1        | 1      | 0.06%   |
| Apple               | 1        | 1      | 0.06%   |
| AMP                 | 1        | 1      | 0.06%   |
| Advantech           | 1        | 1      | 0.06%   |
| 3ware               | 1        | 4      | 0.06%   |
| 128MB               | 1        | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 261      | 373    | 21.36%  |
| Kingston            | 227      | 284    | 18.58%  |
| Crucial             | 190      | 230    | 15.55%  |
| SanDisk             | 74       | 90     | 6.06%   |
| WDC                 | 61       | 66     | 4.99%   |
| China               | 43       | 53     | 3.52%   |
| A-DATA Technology   | 37       | 45     | 3.03%   |
| Intel               | 32       | 39     | 2.62%   |
| SPCC                | 29       | 32     | 2.37%   |
| Netac               | 24       | 83     | 1.96%   |
| Toshiba             | 16       | 19     | 1.31%   |
| PNY                 | 16       | 21     | 1.31%   |
| Transcend           | 14       | 15     | 1.15%   |
| OCZ                 | 14       | 18     | 1.15%   |
| Patriot             | 13       | 14     | 1.06%   |
| Intenso             | 11       | 13     | 0.9%    |
| Micron Technology   | 10       | 11     | 0.82%   |
| GOODRAM             | 8        | 14     | 0.65%   |
| Gigabyte Technology | 8        | 8      | 0.65%   |
| Apacer              | 8        | 8      | 0.65%   |
| Hewlett-Packard     | 7        | 10     | 0.57%   |
| Hajaan              | 7        | 8      | 0.57%   |
| Unknown             | 7        | 8      | 0.57%   |
| Seagate             | 6        | 7      | 0.49%   |
| Corsair             | 6        | 10     | 0.49%   |
| Mushkin             | 5        | 6      | 0.41%   |
| Xinhaike            | 4        | 6      | 0.33%   |
| Unknown             | 4        | 7      | 0.33%   |
| Team                | 4        | 4      | 0.33%   |
| Plextor             | 4        | 7      | 0.33%   |
| LITEONIT            | 4        | 6      | 0.33%   |
| LITEON              | 4        | 5      | 0.33%   |
| Foxline             | 4        | 4      | 0.33%   |
| T-FORCE             | 3        | 4      | 0.25%   |
| Supermicro          | 3        | 4      | 0.25%   |
| SK hynix            | 3        | 3      | 0.25%   |
| KingDian            | 3        | 3      | 0.25%   |
| JMicron Technology  | 3        | 3      | 0.25%   |
| TEXTORM             | 2        | 3      | 0.16%   |
| Smartbuy            | 2        | 2      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1247     | 2588   | 45.31%  |
| SSD     | 1032     | 1593   | 37.5%   |
| NVMe    | 424      | 634    | 15.41%  |
| Unknown | 37       | 74     | 1.34%   |
| MMC     | 12       | 13     | 0.44%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1767     | 3994   | 76.46%  |
| NVMe | 422      | 628    | 18.26%  |
| SAS  | 110      | 267    | 4.76%   |
| MMC  | 12       | 13     | 0.52%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1411     | 2218   | 56.39%  |
| 0.51-1.0   | 561      | 882    | 22.42%  |
| 1.01-2.0   | 221      | 367    | 8.83%   |
| 3.01-4.0   | 117      | 236    | 4.68%   |
| 4.01-10.0  | 105      | 263    | 4.2%    |
| 2.01-3.0   | 56       | 98     | 2.24%   |
| 10.01-20.0 | 30       | 115    | 1.2%    |
| 20.01-50.0 | 1        | 2      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 632      | 31.89%  |
| 101-250        | 277      | 13.98%  |
| 251-500        | 238      | 12.01%  |
| 501-1000       | 220      | 11.1%   |
| More than 3000 | 191      | 9.64%   |
| 1001-2000      | 134      | 6.76%   |
| 51-100         | 88       | 4.44%   |
| 1-20           | 76       | 3.83%   |
| 2001-3000      | 66       | 3.33%   |
| 21-50          | 60       | 3.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 632      | 31.38%  |
| 1-20           | 492      | 24.43%  |
| 101-250        | 174      | 8.64%   |
| 51-100         | 138      | 6.85%   |
| 21-50          | 137      | 6.8%    |
| 251-500        | 120      | 5.96%   |
| 501-1000       | 107      | 5.31%   |
| More than 3000 | 87       | 4.32%   |
| 1001-2000      | 75       | 3.72%   |
| 2001-3000      | 44       | 2.18%   |
| 0              | 8        | 0.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| WDC WD5000AAKX-60U6AA0 500GB     | 20       | 23     | 4.57%   |
| Seagate ST500DM002-1BD142 500GB  | 19       | 23     | 4.34%   |
| Kingston SV300S37A120G 120GB SSD | 15       | 15     | 3.42%   |
| WDC WD5000AAKX-08U6AA0 500GB     | 8        | 8      | 1.83%   |
| Hitachi HDS721050CLA362 500GB    | 8        | 8      | 1.83%   |
| Seagate ST3250318AS 249GB        | 6        | 6      | 1.37%   |
| Hitachi HDS721050DLE630 500GB    | 6        | 11     | 1.37%   |
| Seagate ST3500418AS 500GB        | 5        | 6      | 1.14%   |
| Seagate ST31500341AS 1TB         | 5        | 7      | 1.14%   |
| Seagate ST250DM000-1BD141 250GB  | 5        | 5      | 1.14%   |
| Seagate ST1000DM003-9YN162 1TB   | 5        | 6      | 1.14%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 4        | 4      | 0.91%   |
| WDC WD20EARS-00MVWB0 2TB         | 4        | 4      | 0.91%   |
| WDC WD10EZEX-08WN4A0 1TB         | 4        | 4      | 0.91%   |
| Toshiba DT01ACA050 500GB         | 4        | 5      | 0.91%   |
| Seagate ST31000528AS 1TB         | 4        | 4      | 0.91%   |
| Seagate ST1000DM003-1CH162 1TB   | 4        | 4      | 0.91%   |
| WDC WD5000AAKX-001CA0 500GB      | 3        | 3      | 0.68%   |
| WDC WD3200AAJS-08L7A0 320GB      | 3        | 3      | 0.68%   |
| WDC WD2500AAJS-00YZCA0 250GB     | 3        | 3      | 0.68%   |
| WDC WD10EARS-00Y5B1 1TB          | 3        | 3      | 0.68%   |
| Seagate ST3500413AS 500GB        | 3        | 4      | 0.68%   |
| Seagate ST3320620AS 320GB        | 3        | 5      | 0.68%   |
| Seagate ST3320613AS 320GB        | 3        | 3      | 0.68%   |
| Seagate ST3120827AS 120GB        | 3        | 4      | 0.68%   |
| Seagate ST2000DM008-2FR102 2TB   | 3        | 4      | 0.68%   |
| Seagate ST2000DM001-1ER164 2TB   | 3        | 3      | 0.68%   |
| Seagate ST2000DM001-1CH164 2TB   | 3        | 4      | 0.68%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 2        | 3      | 0.46%   |
| WDC WD5000AAKS-00UU3A0 500GB     | 2        | 2      | 0.46%   |
| WDC WD40EFRX-68N32N0 4TB         | 2        | 2      | 0.46%   |
| WDC WD3200AAKX-753CA1 320GB      | 2        | 2      | 0.46%   |
| WDC WD3200AAJS-00L7A0 320GB      | 2        | 2      | 0.46%   |
| WDC WD2500AAKX-001CA0 250GB      | 2        | 2      | 0.46%   |
| WDC WD2500AAJS-00B4A0 250GB      | 2        | 2      | 0.46%   |
| WDC WD20EFRX-68EUZN0 2TB         | 2        | 5      | 0.46%   |
| WDC WD20EARX-00PASB0 2TB         | 2        | 2      | 0.46%   |
| WDC WD1600AAJS-00B4A0 160GB      | 2        | 2      | 0.46%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 2        | 2      | 0.46%   |
| WDC WD1002FAEX-00Y9A0 1TB        | 2        | 2      | 0.46%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 135      | 162    | 31.99%  |
| Seagate             | 133      | 173    | 31.52%  |
| Hitachi             | 34       | 47     | 8.06%   |
| Samsung Electronics | 27       | 29     | 6.4%    |
| Kingston            | 24       | 29     | 5.69%   |
| Toshiba             | 15       | 16     | 3.55%   |
| Intel               | 12       | 15     | 2.84%   |
| A-DATA Technology   | 8        | 11     | 1.9%    |
| Maxtor              | 7        | 7      | 1.66%   |
| SanDisk             | 4        | 4      | 0.95%   |
| HGST                | 4        | 4      | 0.95%   |
| Crucial             | 4        | 7      | 0.95%   |
| China               | 3        | 3      | 0.71%   |
| SK hynix            | 2        | 5      | 0.47%   |
| Micron Technology   | 2        | 2      | 0.47%   |
| Hewlett-Packard     | 2        | 3      | 0.47%   |
| Apacer              | 2        | 2      | 0.47%   |
| PNY                 | 1        | 1      | 0.24%   |
| LITEONIT            | 1        | 1      | 0.24%   |
| KingDian            | 1        | 1      | 0.24%   |
| Fujitsu             | 1        | 2      | 0.24%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 133      | 173    | 39.23%  |
| WDC                 | 130      | 156    | 38.35%  |
| Hitachi             | 34       | 47     | 10.03%  |
| Toshiba             | 14       | 15     | 4.13%   |
| Samsung Electronics | 14       | 14     | 4.13%   |
| Maxtor              | 7        | 7      | 2.06%   |
| HGST                | 4        | 4      | 1.18%   |
| Hewlett-Packard     | 2        | 3      | 0.59%   |
| Fujitsu             | 1        | 2      | 0.29%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 315      | 421    | 78.95%  |
| SSD  | 73       | 87     | 18.3%   |
| NVMe | 11       | 16     | 2.76%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD4001FFSX-68JNUN0 4TB        | 1        | 1      | 10%     |
| Seagate ST500DM005 HD502HJ 500GB  | 1        | 1      | 10%     |
| Seagate ST500DM002-1BD142 500GB   | 1        | 2      | 10%     |
| Seagate ST3500830AS 500GB         | 1        | 1      | 10%     |
| Seagate ST3500630A 500GB          | 1        | 1      | 10%     |
| Samsung Electronics SSD 980 1TB   | 1        | 1      | 10%     |
| Samsung Electronics HD253GJ 250GB | 1        | 1      | 10%     |
| HGST HUH728080ALN600 8TB          | 1        | 1      | 10%     |
| HGST HDN724040ALE640 4TB          | 1        | 1      | 10%     |
| Hewlett-Packard SSD S700 500GB    | 1        | 2      | 10%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 5      | 40%     |
| Samsung Electronics | 2        | 2      | 20%     |
| HGST                | 2        | 2      | 20%     |
| WDC                 | 1        | 1      | 10%     |
| Hewlett-Packard     | 1        | 2      | 10%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 1466     | 3250   | 65.83%  |
| Malfunc  | 384      | 524    | 17.24%  |
| Detected | 366      | 1115   | 16.43%  |
| Failed   | 10       | 12     | 0.45%   |
| Limited  | 1        | 1      | 0.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1382     | 52.55%  |
| AMD                              | 498      | 18.94%  |
| Samsung Electronics              | 186      | 7.07%   |
| ASMedia Technology               | 86       | 3.27%   |
| SanDisk                          | 66       | 2.51%   |
| Marvell Technology Group         | 56       | 2.13%   |
| JMicron Technology               | 54       | 2.05%   |
| Phison Electronics               | 48       | 1.83%   |
| Nvidia                           | 46       | 1.75%   |
| Kingston Technology Company      | 34       | 1.29%   |
| VIA Technologies                 | 23       | 0.87%   |
| Micron/Crucial Technology        | 22       | 0.84%   |
| LSI Logic / Symbios Logic        | 22       | 0.84%   |
| Broadcom / LSI                   | 14       | 0.53%   |
| Silicon Motion                   | 11       | 0.42%   |
| ADATA Technology                 | 11       | 0.42%   |
| SK hynix                         | 10       | 0.38%   |
| Adaptec                          | 8        | 0.3%    |
| Toshiba America Info Systems     | 7        | 0.27%   |
| Micron Technology                | 7        | 0.27%   |
| KIOXIA                           | 7        | 0.27%   |
| Silicon Image                    | 5        | 0.19%   |
| Seagate Technology               | 5        | 0.19%   |
| Realtek Semiconductor            | 4        | 0.15%   |
| MAXIO Technology (Hangzhou)      | 4        | 0.15%   |
| Integrated Technology Express    | 2        | 0.08%   |
| INNOGRIT                         | 2        | 0.08%   |
| Hewlett-Packard                  | 2        | 0.08%   |
| 3ware                            | 2        | 0.08%   |
| Silicon Integrated Systems [SiS] | 1        | 0.04%   |
| Lite-On Technology               | 1        | 0.04%   |
| HighPoint Technologies           | 1        | 0.04%   |
| Broadcom                         | 1        | 0.04%   |
| Biwin Storage Technology         | 1        | 0.04%   |
| Unknown                          | 1        | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 284      | 8.62%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 177      | 5.37%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 124      | 3.76%   |
| AMD 400 Series Chipset SATA Controller                                                  | 121      | 3.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 116      | 3.52%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 115      | 3.49%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 111      | 3.37%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 109      | 3.31%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 85       | 2.58%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 73       | 2.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 70       | 2.12%   |
| AMD 500 Series Chipset SATA Controller                                                  | 69       | 2.09%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 65       | 1.97%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 63       | 1.91%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 60       | 1.82%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 53       | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 53       | 1.61%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 46       | 1.4%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 46       | 1.4%    |
| Intel SATA Controller [RAID mode]                                                       | 44       | 1.34%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 38       | 1.15%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 35       | 1.06%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 33       | 1%      |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 31       | 0.94%   |
| AMD FCH SATA Controller D                                                               | 31       | 0.94%   |
| Nvidia MCP61 SATA Controller                                                            | 27       | 0.82%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 25       | 0.76%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 25       | 0.76%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 25       | 0.76%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 23       | 0.7%    |
| Intel 8 Series/C220 Series Chipset Family 4-port SATA Controller 1 [IDE mode]           | 23       | 0.7%    |
| Nvidia MCP61 IDE                                                                        | 22       | 0.67%   |
| Phison E12 NVMe Controller                                                              | 21       | 0.64%   |
| AMD 300 Series Chipset SATA Controller                                                  | 21       | 0.64%   |
| Samsung NVMe SSD Controller 980                                                         | 19       | 0.58%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 19       | 0.58%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 18       | 0.55%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 18       | 0.55%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 17       | 0.52%   |
| JMicron JMB368 IDE controller                                                           | 17       | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1560     | 59.27%  |
| IDE  | 492      | 18.69%  |
| NVMe | 421      | 16%     |
| RAID | 106      | 4.03%   |
| SAS  | 40       | 1.52%   |
| SCSI | 13       | 0.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 1390     | 71.58%  |
| AMD                   | 545      | 28.06%  |
| CentaurHauls          | 4        | 0.21%   |
| sifive,u74-mc         | 1        | 0.05%   |
| Marvell Semiconductor | 1        | 0.05%   |
| Unknown               | 1        | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-9400 CPU @ 2.90GHz            | 60       | 3.08%   |
| Intel Pentium CPU G3420 @ 3.20GHz           | 35       | 1.8%    |
| Intel Pentium CPU G4400 @ 3.30GHz           | 29       | 1.49%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 28       | 1.44%   |
| AMD Ryzen 5 3600 6-Core Processor           | 28       | 1.44%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 27       | 1.39%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 27       | 1.39%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 24       | 1.23%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 23       | 1.18%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 22       | 1.13%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 20       | 1.03%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 20       | 1.03%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 20       | 1.03%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 20       | 1.03%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 19       | 0.98%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 18       | 0.93%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 17       | 0.87%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 17       | 0.87%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 17       | 0.87%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 16       | 0.82%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 15       | 0.77%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 15       | 0.77%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 14       | 0.72%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 13       | 0.67%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 13       | 0.67%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 13       | 0.67%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 13       | 0.67%   |
| AMD FX-8350 Eight-Core Processor            | 13       | 0.67%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 12       | 0.62%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 12       | 0.62%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 12       | 0.62%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 12       | 0.62%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 12       | 0.62%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 12       | 0.62%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 11       | 0.57%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 11       | 0.57%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 11       | 0.57%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 11       | 0.57%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 11       | 0.57%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 11       | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 329      | 16.92%  |
| Intel Core i3           | 206      | 10.6%   |
| Intel Core i7           | 175      | 9%      |
| Intel Pentium           | 154      | 7.92%   |
| AMD Ryzen 5             | 124      | 6.38%   |
| Intel Xeon              | 119      | 6.12%   |
| Intel Celeron           | 91       | 4.68%   |
| AMD Ryzen 7             | 84       | 4.32%   |
| Intel Core 2 Duo        | 83       | 4.27%   |
| Other                   | 61       | 3.14%   |
| AMD Ryzen 9             | 55       | 2.83%   |
| AMD FX                  | 54       | 2.78%   |
| Intel Pentium Dual-Core | 52       | 2.67%   |
| AMD Ryzen 3             | 32       | 1.65%   |
| Intel Core 2 Quad       | 29       | 1.49%   |
| AMD Ryzen Threadripper  | 21       | 1.08%   |
| Intel Core i9           | 19       | 0.98%   |
| AMD Athlon              | 18       | 0.93%   |
| Intel Atom              | 17       | 0.87%   |
| Intel Pentium Gold      | 16       | 0.82%   |
| AMD Athlon 64 X2        | 16       | 0.82%   |
| AMD Athlon II X2        | 15       | 0.77%   |
| AMD A10                 | 15       | 0.77%   |
| Intel Pentium 4         | 13       | 0.67%   |
| AMD Phenom II X4        | 13       | 0.67%   |
| Intel Core 2            | 10       | 0.51%   |
| AMD Phenom II X6        | 10       | 0.51%   |
| AMD GX                  | 9        | 0.46%   |
| Intel Pentium Dual      | 7        | 0.36%   |
| AMD Ryzen 5 PRO         | 7        | 0.36%   |
| Intel Pentium D         | 6        | 0.31%   |
| AMD Sempron             | 6        | 0.31%   |
| AMD A8                  | 6        | 0.31%   |
| AMD E                   | 5        | 0.26%   |
| Intel Pentium Silver    | 4        | 0.21%   |
| Intel Genuine           | 4        | 0.21%   |
| AMD Turion II Neo       | 4        | 0.21%   |
| AMD Athlon X4           | 4        | 0.21%   |
| AMD Athlon II X4        | 4        | 0.21%   |
| AMD Athlon II X3        | 4        | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 659      | 33.9%   |
| 4       | 616      | 31.69%  |
| 6       | 283      | 14.56%  |
| 8       | 176      | 9.05%   |
| 16      | 53       | 2.73%   |
| 1       | 53       | 2.73%   |
| 12      | 43       | 2.21%   |
| 3       | 23       | 1.18%   |
| 10      | 15       | 0.77%   |
| 32      | 9        | 0.46%   |
| 24      | 4        | 0.21%   |
| 44      | 2        | 0.1%    |
| 18      | 2        | 0.1%    |
| Unknown | 2        | 0.1%    |
| 64      | 1        | 0.05%   |
| 28      | 1        | 0.05%   |
| 20      | 1        | 0.05%   |
| 14      | 1        | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 1909     | 98.25%  |
| 2       | 32       | 1.65%   |
| Unknown | 2        | 0.1%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 1008     | 51.85%  |
| 1       | 934      | 48.05%  |
| Unknown | 2        | 0.1%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 1917     | 98.66%  |
| 32-bit         | 22       | 1.13%   |
| Unknown        | 4        | 0.21%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 318      | 16.13%  |
| 0x306c3    | 187      | 9.48%   |
| 0x206a7    | 118      | 5.98%   |
| 0x1067a    | 117      | 5.93%   |
| 0x306a9    | 106      | 5.38%   |
| 0x906ea    | 93       | 4.72%   |
| 0x506e3    | 93       | 4.72%   |
| 0xa0653    | 66       | 3.35%   |
| 0x08701021 | 57       | 2.89%   |
| 0x906e9    | 41       | 2.08%   |
| 0xa0655    | 38       | 1.93%   |
| 0x08108109 | 35       | 1.77%   |
| 0x0a201016 | 32       | 1.62%   |
| 0x0800820d | 29       | 1.47%   |
| 0xa0671    | 28       | 1.42%   |
| 0x010000c8 | 21       | 1.06%   |
| 0x6fd      | 19       | 0.96%   |
| 0x906eb    | 15       | 0.76%   |
| 0x90672    | 15       | 0.76%   |
| 0x206d7    | 15       | 0.76%   |
| 0x08101016 | 15       | 0.76%   |
| 0x906ed    | 14       | 0.71%   |
| 0x6fb      | 14       | 0.71%   |
| 0x306f2    | 14       | 0.71%   |
| 0x0a50000c | 14       | 0.71%   |
| 0x0a201009 | 14       | 0.71%   |
| 0x06003106 | 14       | 0.71%   |
| 0x20655    | 13       | 0.66%   |
| 0x06000852 | 13       | 0.66%   |
| 0x06000822 | 13       | 0.66%   |
| 0x206c2    | 12       | 0.61%   |
| 0x010000b6 | 12       | 0.61%   |
| 0x306e4    | 11       | 0.56%   |
| 0x10676    | 11       | 0.56%   |
| 0x08600106 | 11       | 0.56%   |
| 0x706a8    | 10       | 0.51%   |
| 0x30678    | 10       | 0.51%   |
| 0x106a5    | 10       | 0.51%   |
| 0x906c0    | 9        | 0.46%   |
| 0x08701013 | 9        | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 245      | 12.6%   |
| KabyLake         | 197      | 10.13%  |
| SandyBridge      | 148      | 7.61%   |
| Penryn           | 146      | 7.51%   |
| IvyBridge        | 134      | 6.89%   |
| CometLake        | 117      | 6.02%   |
| Skylake          | 116      | 5.97%   |
| Zen 2            | 106      | 5.45%   |
| Zen 3            | 101      | 5.2%    |
| Zen+             | 88       | 4.53%   |
| K10              | 60       | 3.09%   |
| Core             | 57       | 2.93%   |
| Unknown          | 54       | 2.78%   |
| Piledriver       | 48       | 2.47%   |
| Zen              | 47       | 2.42%   |
| Westmere         | 35       | 1.8%    |
| Silvermont       | 29       | 1.49%   |
| K8 Hammer        | 25       | 1.29%   |
| NetBurst         | 24       | 1.23%   |
| Nehalem          | 23       | 1.18%   |
| Goldmont plus    | 19       | 0.98%   |
| Steamroller      | 17       | 0.87%   |
| Bulldozer        | 16       | 0.82%   |
| Bonnell          | 12       | 0.62%   |
| Broadwell        | 10       | 0.51%   |
| Tremont          | 9        | 0.46%   |
| Jaguar           | 9        | 0.46%   |
| Goldmont         | 9        | 0.46%   |
| Excavator        | 8        | 0.41%   |
| Icelake          | 7        | 0.36%   |
| Bobcat           | 7        | 0.36%   |
| Alderlake Hybrid | 7        | 0.36%   |
| Puma             | 5        | 0.26%   |
| P6               | 3        | 0.15%   |
| K6               | 3        | 0.15%   |
| TigerLake        | 2        | 0.1%    |
| K10 Llano        | 1        | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 880      | 42.78%  |
| Nvidia                           | 664      | 32.28%  |
| AMD                              | 449      | 21.83%  |
| ASPEED Technology                | 42       | 2.04%   |
| Matrox Electronics Systems       | 15       | 0.73%   |
| VIA Technologies                 | 5        | 0.24%   |
| Silicon Integrated Systems [SiS] | 1        | 0.05%   |
| ATI Technologies                 | 1        | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 133      | 6.34%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 96       | 4.57%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 77       | 3.67%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 72       | 3.43%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 63       | 3%      |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 58       | 2.76%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 53       | 2.53%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 50       | 2.38%   |
| ASPEED Technology ASPEED Graphics Family                                    | 42       | 2%      |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 41       | 1.95%   |
| Intel HD Graphics 530                                                       | 40       | 1.91%   |
| Nvidia GF108 [GeForce GT 730]                                               | 38       | 1.81%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 37       | 1.76%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 37       | 1.76%   |
| Nvidia GK208B [GeForce GT 710]                                              | 36       | 1.72%   |
| Intel HD Graphics 510                                                       | 29       | 1.38%   |
| Intel HD Graphics 630                                                       | 28       | 1.33%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 27       | 1.29%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 26       | 1.24%   |
| Nvidia GF108 [GeForce GT 630]                                               | 23       | 1.1%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 21       | 1%      |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 20       | 0.95%   |
| Nvidia GT218 [GeForce 210]                                                  | 19       | 0.91%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 19       | 0.91%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 19       | 0.91%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 17       | 0.81%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 16       | 0.76%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 16       | 0.76%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 14       | 0.67%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 13       | 0.62%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 13       | 0.62%   |
| AMD Renoir                                                                  | 13       | 0.62%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 12       | 0.57%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 12       | 0.57%   |
| Nvidia GF108 [GeForce GT 430]                                               | 12       | 0.57%   |
| Nvidia G86 [GeForce 8500 GT]                                                | 12       | 0.57%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 12       | 0.57%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 12       | 0.57%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 12       | 0.57%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 11       | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| 1 x Intel                         | 794      | 40.51%  |
| 1 x Nvidia                        | 605      | 30.87%  |
| 1 x AMD                           | 404      | 20.61%  |
| Intel + Nvidia                    | 31       | 1.58%   |
| 1 x ASPEED                        | 31       | 1.58%   |
| 2 x AMD                           | 20       | 1.02%   |
| Other                             | 14       | 0.71%   |
| 1 x Matrox                        | 14       | 0.71%   |
| AMD + Nvidia                      | 11       | 0.56%   |
| Intel + AMD                       | 8        | 0.41%   |
| 2 x Nvidia                        | 6        | 0.31%   |
| 1 x VIA                           | 5        | 0.26%   |
| Nvidia + ASPEED                   | 5        | 0.26%   |
| AMD + ASPEED                      | 4        | 0.2%    |
| Intel + 2 x Nvidia                | 3        | 0.15%   |
| 3 x AMD                           | 1        | 0.05%   |
| 2 x Nvidia + 1 x ASPEED           | 1        | 0.05%   |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED | 1        | 0.05%   |
| 1 x SiS                           | 1        | 0.05%   |
| AMD + Matrox                      | 1        | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 963      | 49.21%  |
| Unknown     | 727      | 37.15%  |
| Proprietary | 267      | 13.64%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1317     | 66.95%  |
| 1.01-2.0   | 157      | 7.98%   |
| 0.01-0.5   | 108      | 5.49%   |
| 0.51-1.0   | 104      | 5.29%   |
| 3.01-4.0   | 102      | 5.19%   |
| 7.01-8.0   | 92       | 4.68%   |
| 5.01-6.0   | 43       | 2.19%   |
| 8.01-16.0  | 19       | 0.97%   |
| 2.01-3.0   | 16       | 0.81%   |
| 16.01-24.0 | 6        | 0.31%   |
| 4.01-5.0   | 2        | 0.1%    |
| 24.01-32.0 | 1        | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 207      | 15.62%  |
| Dell                    | 151      | 11.4%   |
| Goldstar                | 142      | 10.72%  |
| Acer                    | 89       | 6.72%   |
| Hewlett-Packard         | 74       | 5.58%   |
| BenQ                    | 74       | 5.58%   |
| AOC                     | 63       | 4.75%   |
| Ancor Communications    | 59       | 4.45%   |
| Philips                 | 58       | 4.38%   |
| Iiyama                  | 35       | 2.64%   |
| Unknown                 | 30       | 2.26%   |
| ASUSTek Computer        | 27       | 2.04%   |
| ViewSonic               | 26       | 1.96%   |
| Eizo                    | 24       | 1.81%   |
| Lenovo                  | 19       | 1.43%   |
| LG Electronics          | 17       | 1.28%   |
| Sony                    | 13       | 0.98%   |
| Vestel Elektronik       | 10       | 0.75%   |
| NEC Computers           | 10       | 0.75%   |
| MSI                     | 8        | 0.6%    |
| Unknown                 | 8        | 0.6%    |
| Vizio                   | 6        | 0.45%   |
| Medion                  | 6        | 0.45%   |
| Fujitsu Siemens         | 5        | 0.38%   |
| Toshiba                 | 4        | 0.3%    |
| Panasonic               | 4        | 0.3%    |
| Microstep               | 4        | 0.3%    |
| Idek Iiyama             | 4        | 0.3%    |
| Chi Mei Optoelectronics | 4        | 0.3%    |
| Belinea                 | 4        | 0.3%    |
| Sceptre Tech            | 3        | 0.23%   |
| ONN                     | 3        | 0.23%   |
| Mi                      | 3        | 0.23%   |
| Lenovo Group Limited    | 3        | 0.23%   |
| Hitachi                 | 3        | 0.23%   |
| Grundig                 | 3        | 0.23%   |
| Gigabyte Technology     | 3        | 0.23%   |
| DENON                   | 3        | 0.23%   |
| VIZ                     | 2        | 0.15%   |
| VIE                     | 2        | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 21       | 1.49%   |
| Vestel Elektronik 50FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 9        | 0.64%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 9        | 0.64%   |
| Unknown                                                               | 8        | 0.57%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch                | 7        | 0.5%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 7        | 0.5%    |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch           | 7        | 0.5%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 6        | 0.43%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 6        | 0.43%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 5        | 0.36%   |
| Dell U2518D DEL413A 2560x1440 550x310mm 24.9-inch                     | 5        | 0.36%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                     | 5        | 0.36%   |
| AOC 1950W AOC1950 1366x768 410x230mm 18.5-inch                        | 5        | 0.36%   |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch      | 5        | 0.36%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 4        | 0.28%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 4        | 0.28%   |
| Philips PHL 221V8 PHLC211 1920x1080 477x268mm 21.5-inch               | 4        | 0.28%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 4        | 0.28%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 4        | 0.28%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 4        | 0.28%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 4        | 0.28%   |
| BenQ GL2480 BNQ78ED 1920x1080 531x298mm 24.0-inch                     | 4        | 0.28%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 4        | 0.28%   |
| Acer K242HL ACR03E3 1920x1080 531x299mm 24.0-inch                     | 4        | 0.28%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch     | 3        | 0.21%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 3        | 0.21%   |
| Samsung Electronics LC32G7xT SAM7058 2560x1440 700x400mm 31.7-inch    | 3        | 0.21%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 3        | 0.21%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 3        | 0.21%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch               | 3        | 0.21%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 3        | 0.21%   |
| Philips 220WS PHL0851 1680x1050 434x270mm 20.1-inch                   | 3        | 0.21%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                 | 3        | 0.21%   |
| Iiyama PL2283H IVM562E 1920x1080 496x292mm 22.7-inch                  | 3        | 0.21%   |
| Grundig WXGA GRU4448 1600x1200                                        | 3        | 0.21%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                  | 3        | 0.21%   |
| Goldstar ULTRAGEAR GSM5B80 2560x1440 597x336mm 27.0-inch              | 3        | 0.21%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                  | 3        | 0.21%   |
| Dell U2715H DELD065 2560x1440 597x336mm 27.0-inch                     | 3        | 0.21%   |
| Dell U2713HM DEL4080 2560x1440 597x336mm 27.0-inch                    | 3        | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 553      | 42.44%  |
| 3840x2160 (4K)     | 127      | 9.75%   |
| 1280x1024 (SXGA)   | 116      | 8.9%    |
| 2560x1440 (QHD)    | 100      | 7.67%   |
| 1680x1050 (WSXGA+) | 63       | 4.83%   |
| Unknown            | 44       | 3.38%   |
| 1366x768 (WXGA)    | 37       | 2.84%   |
| 1920x1200 (WUXGA)  | 32       | 2.46%   |
| 1600x900 (HD+)     | 29       | 2.23%   |
| 1440x900 (WXGA+)   | 29       | 2.23%   |
| 2288x1287          | 23       | 1.77%   |
| 3440x1440          | 19       | 1.46%   |
| 3840x1080          | 17       | 1.3%    |
| 2560x1080          | 17       | 1.3%    |
| 1360x768           | 16       | 1.23%   |
| 1024x768 (XGA)     | 16       | 1.23%   |
| 1600x1200          | 14       | 1.07%   |
| 1920x540           | 6        | 0.46%   |
| 4480x1440          | 5        | 0.38%   |
| 5760x1080          | 3        | 0.23%   |
| 3200x1080          | 3        | 0.23%   |
| 2560x1600          | 3        | 0.23%   |
| 1400x1050          | 3        | 0.23%   |
| 5360x1440          | 2        | 0.15%   |
| 3360x1050          | 2        | 0.15%   |
| 2048x1152          | 2        | 0.15%   |
| 1280x800 (WXGA)    | 2        | 0.15%   |
| 1280x720 (HD)      | 2        | 0.15%   |
| 7680x4320          | 1        | 0.08%   |
| 6400x2160          | 1        | 0.08%   |
| 5760x2160          | 1        | 0.08%   |
| 5120x2160          | 1        | 0.08%   |
| 5120x1440          | 1        | 0.08%   |
| 5120x1080          | 1        | 0.08%   |
| 4480x1600          | 1        | 0.08%   |
| 3840x2560          | 1        | 0.08%   |
| 3840x1600          | 1        | 0.08%   |
| 3360x1080          | 1        | 0.08%   |
| 3280x1080          | 1        | 0.08%   |
| 2960x1050          | 1        | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 192      | 14.87%  |
| 27      | 169      | 13.09%  |
| 23      | 161      | 12.47%  |
| 21      | 119      | 9.22%   |
| Unknown | 111      | 8.6%    |
| 19      | 85       | 6.58%   |
| 17      | 57       | 4.42%   |
| 31      | 54       | 4.18%   |
| 22      | 49       | 3.8%    |
| 18      | 49       | 3.8%    |
| 20      | 36       | 2.79%   |
| 15      | 32       | 2.48%   |
| 34      | 27       | 2.09%   |
| 142     | 21       | 1.63%   |
| 84      | 20       | 1.55%   |
| 32      | 12       | 0.93%   |
| 72      | 11       | 0.85%   |
| 25      | 10       | 0.77%   |
| 54      | 8        | 0.62%   |
| 26      | 8        | 0.62%   |
| 28      | 6        | 0.46%   |
| 52      | 5        | 0.39%   |
| 48      | 5        | 0.39%   |
| 42      | 4        | 0.31%   |
| 40      | 4        | 0.31%   |
| 13      | 4        | 0.31%   |
| 39      | 3        | 0.23%   |
| 35      | 3        | 0.23%   |
| 33      | 3        | 0.23%   |
| 29      | 3        | 0.23%   |
| 65      | 2        | 0.15%   |
| 43      | 2        | 0.15%   |
| 75      | 1        | 0.08%   |
| 74      | 1        | 0.08%   |
| 64      | 1        | 0.08%   |
| 61      | 1        | 0.08%   |
| 55      | 1        | 0.08%   |
| 50      | 1        | 0.08%   |
| 49      | 1        | 0.08%   |
| 47      | 1        | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 477      | 38.25%  |
| 401-500        | 278      | 22.29%  |
| Unknown        | 111      | 8.9%    |
| 301-350        | 87       | 6.98%   |
| 601-700        | 85       | 6.82%   |
| 351-400        | 63       | 5.05%   |
| 701-800        | 41       | 3.29%   |
| 1501-2000      | 33       | 2.65%   |
| 1001-1500      | 26       | 2.09%   |
| More than 2000 | 21       | 1.68%   |
| 801-900        | 12       | 0.96%   |
| 901-1000       | 6        | 0.48%   |
| 201-300        | 5        | 0.4%    |
| 101-200        | 2        | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 746      | 61.91%  |
| 16/10   | 136      | 11.29%  |
| 5/4     | 108      | 8.96%   |
| Unknown | 99       | 8.22%   |
| 4/3     | 40       | 3.32%   |
| 21/9    | 33       | 2.74%   |
| 1.00    | 23       | 1.91%   |
| 3/2     | 8        | 0.66%   |
| 6/5     | 6        | 0.5%    |
| 32/9    | 3        | 0.25%   |
| 2.65    | 1        | 0.08%   |
| 2.00    | 1        | 0.08%   |
| 1.96    | 1        | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 421      | 33.52%  |
| 301-350        | 174      | 13.85%  |
| 151-200        | 156      | 12.42%  |
| Unknown        | 111      | 8.84%   |
| 351-500        | 105      | 8.36%   |
| 141-150        | 89       | 7.09%   |
| More than 1000 | 75       | 5.97%   |
| 251-300        | 63       | 5.02%   |
| 101-110        | 26       | 2.07%   |
| 501-1000       | 19       | 1.51%   |
| 111-120        | 5        | 0.4%    |
| 131-140        | 4        | 0.32%   |
| 71-80          | 3        | 0.24%   |
| 1-40           | 2        | 0.16%   |
| 81-90          | 1        | 0.08%   |
| 41-50          | 1        | 0.08%   |
| 91-100         | 1        | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 741      | 61.54%  |
| 101-120       | 208      | 17.28%  |
| Unknown       | 111      | 9.22%   |
| 1-50          | 57       | 4.73%   |
| 121-160       | 56       | 4.65%   |
| 161-240       | 30       | 2.49%   |
| More than 240 | 1        | 0.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 905      | 45.96%  |
| 0     | 815      | 41.39%  |
| 2     | 224      | 11.38%  |
| 3     | 23       | 1.17%   |
| 4     | 2        | 0.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 1219     | 48.57%  |
| Intel                            | 725      | 28.88%  |
| Qualcomm Atheros                 | 146      | 5.82%   |
| Broadcom                         | 65       | 2.59%   |
| Nvidia                           | 41       | 1.63%   |
| Ralink Technology                | 40       | 1.59%   |
| Broadcom Limited                 | 22       | 0.88%   |
| TP-Link                          | 21       | 0.84%   |
| Ralink                           | 15       | 0.6%    |
| Marvell Technology Group         | 15       | 0.6%    |
| MediaTek                         | 13       | 0.52%   |
| Aquantia                         | 13       | 0.52%   |
| Samsung Electronics              | 11       | 0.44%   |
| Qualcomm Atheros Communications  | 11       | 0.44%   |
| D-Link System                    | 11       | 0.44%   |
| Mellanox Technologies            | 10       | 0.4%    |
| ASIX Electronics                 | 10       | 0.4%    |
| D-Link                           | 9        | 0.36%   |
| NetGear                          | 8        | 0.32%   |
| Microsoft                        | 8        | 0.32%   |
| VIA Technologies                 | 7        | 0.28%   |
| Huawei Technologies              | 6        | 0.24%   |
| ASUSTek Computer                 | 6        | 0.24%   |
| American Megatrends              | 6        | 0.24%   |
| Gemtek                           | 4        | 0.16%   |
| Edimax Technology                | 4        | 0.16%   |
| Dresden Elektronik               | 4        | 0.16%   |
| Belkin Components                | 4        | 0.16%   |
| Xiaomi                           | 3        | 0.12%   |
| Texas Instruments                | 3        | 0.12%   |
| IMC Networks                     | 3        | 0.12%   |
| DisplayLink                      | 3        | 0.12%   |
| 3Com                             | 3        | 0.12%   |
| ZTE WCDMA Technologies MSM       | 2        | 0.08%   |
| Silicon Integrated Systems [SiS] | 2        | 0.08%   |
| Sigma Designs                    | 2        | 0.08%   |
| Qualcomm                         | 2        | 0.08%   |
| QLogic                           | 2        | 0.08%   |
| ICS Advent                       | 2        | 0.08%   |
| AVM                              | 2        | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1007     | 36.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 74       | 2.66%   |
| Intel I211 Gigabit Network Connection                             | 71       | 2.55%   |
| Realtek RTL8125 2.5GbE Controller                                 | 67       | 2.41%   |
| Intel Wi-Fi 6 AX200                                               | 67       | 2.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 66       | 2.37%   |
| Intel I210 Gigabit Network Connection                             | 46       | 1.66%   |
| Intel Ethernet Connection (2) I219-V                              | 46       | 1.66%   |
| Intel Ethernet Controller I225-V                                  | 44       | 1.58%   |
| Intel Ethernet Connection (14) I219-V                             | 33       | 1.19%   |
| Intel Ethernet Connection I217-LM                                 | 31       | 1.12%   |
| Intel 82579V Gigabit Network Connection                           | 31       | 1.12%   |
| Intel 82574L Gigabit Network Connection                           | 29       | 1.04%   |
| Nvidia MCP61 Ethernet                                             | 26       | 0.94%   |
| Intel Ethernet Connection (7) I219-V                              | 25       | 0.9%    |
| Intel Ethernet Connection (2) I219-LM                             | 22       | 0.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 22       | 0.79%   |
| Intel Ethernet Connection I217-V                                  | 21       | 0.76%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 19       | 0.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 19       | 0.68%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 18       | 0.65%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 18       | 0.65%   |
| Intel Wireless 3165                                               | 17       | 0.61%   |
| Intel Ethernet Connection (2) I218-V                              | 16       | 0.58%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 15       | 0.54%   |
| Intel Wireless-AC 9260                                            | 15       | 0.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 14       | 0.5%    |
| Realtek 802.11ac NIC                                              | 13       | 0.47%   |
| Ralink MT7601U Wireless Adapter                                   | 13       | 0.47%   |
| Intel Ethernet Controller X550                                    | 13       | 0.47%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 12       | 0.43%   |
| Ralink RT5370 Wireless Adapter                                    | 12       | 0.43%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 12       | 0.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 12       | 0.43%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 12       | 0.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 11       | 0.4%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 11       | 0.4%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 11       | 0.4%    |
| Intel Wireless 7260                                               | 11       | 0.4%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 11       | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 207      | 36.83%  |
| Realtek Semiconductor           | 114      | 20.28%  |
| Qualcomm Atheros                | 63       | 11.21%  |
| Ralink Technology               | 40       | 7.12%   |
| TP-Link                         | 19       | 3.38%   |
| Broadcom                        | 19       | 3.38%   |
| Ralink                          | 15       | 2.67%   |
| MediaTek                        | 12       | 2.14%   |
| Qualcomm Atheros Communications | 11       | 1.96%   |
| D-Link                          | 9        | 1.6%    |
| NetGear                         | 8        | 1.42%   |
| Microsoft                       | 7        | 1.25%   |
| D-Link System                   | 6        | 1.07%   |
| ASUSTek Computer                | 6        | 1.07%   |
| Edimax Technology               | 4        | 0.71%   |
| Broadcom Limited                | 4        | 0.71%   |
| Belkin Components               | 4        | 0.71%   |
| IMC Networks                    | 3        | 0.53%   |
| Gemtek                          | 3        | 0.53%   |
| AVM                             | 2        | 0.36%   |
| Wilocity                        | 1        | 0.18%   |
| Sitecom Europe                  | 1        | 0.18%   |
| Micro Star International        | 1        | 0.18%   |
| Marvell Technology Group        | 1        | 0.18%   |
| Linksys                         | 1        | 0.18%   |
| BUFFALO                         | 1        | 0.18%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 67       | 11.86%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 22       | 3.89%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 19       | 3.36%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 18       | 3.19%   |
| Intel Wireless 3165                                            | 17       | 3.01%   |
| Intel Wireless-AC 9260                                         | 15       | 2.65%   |
| Realtek 802.11ac NIC                                           | 13       | 2.3%    |
| Ralink MT7601U Wireless Adapter                                | 13       | 2.3%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 12       | 2.12%   |
| Ralink RT5370 Wireless Adapter                                 | 12       | 2.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 12       | 2.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 11       | 1.95%   |
| Intel Wireless 7260                                            | 11       | 1.95%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 10       | 1.77%   |
| Qualcomm Atheros AR9271 802.11n                                | 10       | 1.77%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 10       | 1.77%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 10       | 1.77%   |
| Intel Wireless 7265                                            | 9        | 1.59%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 8        | 1.42%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 6        | 1.06%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 6        | 1.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6        | 1.06%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 6        | 1.06%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 6        | 1.06%   |
| Intel Wireless 8260                                            | 6        | 1.06%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 6        | 1.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 6        | 1.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 5        | 0.88%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 5        | 0.88%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 5        | 0.88%   |
| Ralink RT5372 Wireless Adapter                                 | 5        | 0.88%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 5        | 0.88%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 5        | 0.88%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 5        | 0.88%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 4        | 0.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4        | 0.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4        | 0.71%   |
| NetGear A6210                                                  | 4        | 0.71%   |
| Microsoft Xbox 360 Wireless Adapter                            | 4        | 0.71%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 3        | 0.53%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 1174     | 56.04%  |
| Intel                             | 613      | 29.26%  |
| Qualcomm Atheros                  | 89       | 4.25%   |
| Broadcom                          | 49       | 2.34%   |
| Nvidia                            | 41       | 1.96%   |
| Broadcom Limited                  | 18       | 0.86%   |
| Marvell Technology Group          | 15       | 0.72%   |
| Aquantia                          | 13       | 0.62%   |
| Samsung Electronics               | 11       | 0.53%   |
| ASIX Electronics                  | 10       | 0.48%   |
| Mellanox Technologies             | 9        | 0.43%   |
| VIA Technologies                  | 7        | 0.33%   |
| American Megatrends               | 6        | 0.29%   |
| D-Link System                     | 5        | 0.24%   |
| Huawei Technologies               | 4        | 0.19%   |
| Xiaomi                            | 3        | 0.14%   |
| DisplayLink                       | 3        | 0.14%   |
| 3Com                              | 3        | 0.14%   |
| ZTE WCDMA Technologies MSM        | 2        | 0.1%    |
| TP-Link                           | 2        | 0.1%    |
| Silicon Integrated Systems [SiS]  | 2        | 0.1%    |
| Qualcomm                          | 2        | 0.1%    |
| QLogic                            | 2        | 0.1%    |
| ICS Advent                        | 2        | 0.1%    |
| Tehuti Networks                   | 1        | 0.05%   |
| Sundance Technology Inc / IC Plus | 1        | 0.05%   |
| OPPO Electronics                  | 1        | 0.05%   |
| Motorola PCS                      | 1        | 0.05%   |
| Microsoft                         | 1        | 0.05%   |
| Google                            | 1        | 0.05%   |
| Gemtek                            | 1        | 0.05%   |
| ATEN International                | 1        | 0.05%   |
| ADMtek                            | 1        | 0.05%   |
| Accton Technology                 | 1        | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1007     | 46.09%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 74       | 3.39%   |
| Intel I211 Gigabit Network Connection                             | 71       | 3.25%   |
| Realtek RTL8125 2.5GbE Controller                                 | 67       | 3.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 66       | 3.02%   |
| Intel I210 Gigabit Network Connection                             | 46       | 2.11%   |
| Intel Ethernet Connection (2) I219-V                              | 46       | 2.11%   |
| Intel Ethernet Controller I225-V                                  | 44       | 2.01%   |
| Intel Ethernet Connection (14) I219-V                             | 33       | 1.51%   |
| Intel Ethernet Connection I217-LM                                 | 31       | 1.42%   |
| Intel 82579V Gigabit Network Connection                           | 31       | 1.42%   |
| Intel 82574L Gigabit Network Connection                           | 29       | 1.33%   |
| Nvidia MCP61 Ethernet                                             | 26       | 1.19%   |
| Intel Ethernet Connection (7) I219-V                              | 25       | 1.14%   |
| Intel Ethernet Connection (2) I219-LM                             | 22       | 1.01%   |
| Intel Ethernet Connection I217-V                                  | 21       | 0.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 19       | 0.87%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 18       | 0.82%   |
| Intel Ethernet Connection (2) I218-V                              | 16       | 0.73%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 15       | 0.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 14       | 0.64%   |
| Intel Ethernet Controller X550                                    | 13       | 0.59%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 12       | 0.55%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 12       | 0.55%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 11       | 0.5%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 11       | 0.5%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 11       | 0.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9        | 0.41%   |
| Intel I350 Gigabit Network Connection                             | 9        | 0.41%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 9        | 0.41%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 9        | 0.41%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 9        | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 8        | 0.37%   |
| Intel Ethernet Connection (5) I219-LM                             | 8        | 0.37%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 8        | 0.37%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 7        | 0.32%   |
| Intel Ethernet Connection (7) I219-LM                             | 7        | 0.32%   |
| Intel Ethernet Connection (2) I218-LM                             | 7        | 0.32%   |
| Intel Ethernet Connection (11) I219-V                             | 7        | 0.32%   |
| ASIX AX88179 Gigabit Ethernet                                     | 7        | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1933     | 77.72%  |
| WiFi     | 526      | 21.15%  |
| Modem    | 25       | 1.01%   |
| Unknown  | 3        | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1728     | 88.93%  |
| WiFi     | 215      | 11.07%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1359     | 69.76%  |
| 2     | 443      | 22.74%  |
| 3     | 89       | 4.57%   |
| 4     | 21       | 1.08%   |
| 5     | 12       | 0.62%   |
| 0     | 8        | 0.41%   |
| 6     | 7        | 0.36%   |
| 8     | 4        | 0.21%   |
| 7     | 2        | 0.1%    |
| 13    | 1        | 0.05%   |
| 12    | 1        | 0.05%   |
| 9     | 1        | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1612     | 82.62%  |
| Yes  | 339      | 17.38%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 191      | 45.15%  |
| Cambridge Silicon Radio         | 100      | 23.64%  |
| Realtek Semiconductor           | 30       | 7.09%   |
| Broadcom                        | 24       | 5.67%   |
| ASUSTek Computer                | 23       | 5.44%   |
| Qualcomm Atheros Communications | 14       | 3.31%   |
| IMC Networks                    | 10       | 2.36%   |
| MediaTek                        | 9        | 2.13%   |
| Apple                           | 4        | 0.95%   |
| TP-Link                         | 3        | 0.71%   |
| Lite-On Technology              | 2        | 0.47%   |
| Belkin Components               | 2        | 0.47%   |
| Toshiba                         | 1        | 0.24%   |
| Sitecom Europe                  | 1        | 0.24%   |
| Realtek                         | 1        | 0.24%   |
| Microsoft                       | 1        | 0.24%   |
| Micro Star International        | 1        | 0.24%   |
| Integrated System Solution      | 1        | 0.24%   |
| Hewlett-Packard                 | 1        | 0.24%   |
| Foxconn / Hon Hai               | 1        | 0.24%   |
| Edimax Technology               | 1        | 0.24%   |
| Dynex                           | 1        | 0.24%   |
| Unknown                         | 1        | 0.24%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)       | 100      | 23.58%  |
| Intel AX200 Bluetooth                                     | 62       | 14.62%  |
| Intel Bluetooth wireless interface                        | 48       | 11.32%  |
| Realtek Bluetooth Radio                                   | 24       | 5.66%   |
| Intel Wireless-AC 3168 Bluetooth                          | 22       | 5.19%   |
| Intel Bluetooth Device                                    | 15       | 3.54%   |
| Intel AX210 Bluetooth                                     | 15       | 3.54%   |
| Broadcom BCM20702A0 Bluetooth 4.0                         | 15       | 3.54%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                  | 14       | 3.3%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)            | 12       | 2.83%   |
| MediaTek Wireless_Device                                  | 9        | 2.12%   |
| ASUS Broadcom BCM20702A0 Bluetooth                        | 8        | 1.89%   |
| Realtek  Bluetooth 4.2 Adapter                            | 5        | 1.18%   |
| Qualcomm Atheros  Bluetooth Device                        | 4        | 0.94%   |
| Qualcomm Atheros AR9462 Bluetooth                         | 4        | 0.94%   |
| Intel Centrino Bluetooth Wireless Transceiver             | 4        | 0.94%   |
| IMC Networks Bluetooth Radio                              | 4        | 0.94%   |
| ASUS ASUS USB-BT500                                       | 4        | 0.94%   |
| TP-Link TPuLink UB500 Adapter                             | 3        | 0.71%   |
| Qualcomm Atheros Bluetooth USB Host Controller            | 3        | 0.71%   |
| IMC Networks Bluetooth Device                             | 3        | 0.71%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE     | 3        | 0.71%   |
| ASUS Bluetooth Radio                                      | 3        | 0.71%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                    | 2        | 0.47%   |
| ASUS Bluetooth Adapter                                    | 2        | 0.47%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                      | 2        | 0.47%   |
| Apple Bluetooth USB Host Controller                       | 2        | 0.47%   |
| Toshiba Atheros AR3012 Bluetooth                          | 1        | 0.24%   |
| Sitecom Europe Sitecom bluetooth2.0 class 1 dongle CN-521 | 1        | 0.24%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                   | 1        | 0.24%   |
| Realtek Bluetooth Radio                                   | 1        | 0.24%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                     | 1        | 0.24%   |
| Microsoft Wireless Transceiver for Bluetooth              | 1        | 0.24%   |
| Micro Star International Bluetooth EDR Device             | 1        | 0.24%   |
| Lite-On Bluetooth Device                                  | 1        | 0.24%   |
| Lite-On Atheros AR3012 Bluetooth                          | 1        | 0.24%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter     | 1        | 0.24%   |
| IMC Networks Wireless_Device                              | 1        | 0.24%   |
| IMC Networks Bluetooth                                    | 1        | 0.24%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter         | 1        | 0.24%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 1285     | 45.41%  |
| Nvidia                                       | 618      | 21.84%  |
| AMD                                          | 611      | 21.59%  |
| C-Media Electronics                          | 54       | 1.91%   |
| Creative Labs                                | 25       | 0.88%   |
| Logitech                                     | 23       | 0.81%   |
| ASUSTek Computer                             | 16       | 0.57%   |
| Texas Instruments                            | 14       | 0.49%   |
| Generalplus Technology                       | 11       | 0.39%   |
| Focusrite-Novation                           | 11       | 0.39%   |
| VIA Technologies                             | 10       | 0.35%   |
| Kingston Technology                          | 9        | 0.32%   |
| Creative Technology                          | 9        | 0.32%   |
| JMTek                                        | 7        | 0.25%   |
| GN Netcom                                    | 7        | 0.25%   |
| SteelSeries ApS                              | 6        | 0.21%   |
| Plantronics                                  | 6        | 0.21%   |
| GYROCOM C&C                                  | 6        | 0.21%   |
| Yamaha                                       | 5        | 0.18%   |
| RODE Microphones                             | 5        | 0.18%   |
| Razer USA                                    | 5        | 0.18%   |
| Micro Star International                     | 5        | 0.18%   |
| Dell                                         | 5        | 0.18%   |
| Cambridge Silicon Radio                      | 5        | 0.18%   |
| Unknown                                      | 4        | 0.14%   |
| BEHRINGER International                      | 4        | 0.14%   |
| TerraTec Electronic                          | 3        | 0.11%   |
| Sennheiser Communications                    | 3        | 0.11%   |
| Samson Technologies                          | 3        | 0.11%   |
| KTMicro                                      | 3        | 0.11%   |
| Blue Microphones                             | 3        | 0.11%   |
| Zoran Co. Personal Media Division (Nogatech) | 2        | 0.07%   |
| XMOS                                         | 2        | 0.07%   |
| Tenx Technology                              | 2        | 0.07%   |
| ROCCAT                                       | 2        | 0.07%   |
| Microsoft                                    | 2        | 0.07%   |
| M-Audio                                      | 2        | 0.07%   |
| Huawei Technologies                          | 2        | 0.07%   |
| Giga-Byte Technology                         | 2        | 0.07%   |
| Corsair                                      | 2        | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 191      | 5.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 157      | 4.79%   |
| AMD Starship/Matisse HD Audio Controller                                   | 151      | 4.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 150      | 4.57%   |
| Intel 200 Series PCH HD Audio                                              | 126      | 3.84%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 115      | 3.51%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 114      | 3.48%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 102      | 3.11%   |
| AMD Family 17h/19h HD Audio Controller                                     | 102      | 3.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 78       | 2.38%   |
| Nvidia GF108 High Definition Audio Controller                              | 76       | 2.32%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 65       | 1.98%   |
| Nvidia GP107GL High Definition Audio Controller                            | 63       | 1.92%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 60       | 1.83%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 57       | 1.74%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 51       | 1.55%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 50       | 1.52%   |
| Intel Comet Lake PCH cAVS                                                  | 47       | 1.43%   |
| Intel Cannon Lake PCH cAVS                                                 | 46       | 1.4%    |
| AMD FCH Azalia Controller                                                  | 41       | 1.25%   |
| Intel Audio device                                                         | 40       | 1.22%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 37       | 1.13%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 36       | 1.1%    |
| Nvidia High Definition Audio Controller                                    | 34       | 1.04%   |
| Nvidia GP106 High Definition Audio Controller                              | 33       | 1.01%   |
| Nvidia TU106 High Definition Audio Controller                              | 31       | 0.95%   |
| Nvidia GP104 High Definition Audio Controller                              | 30       | 0.91%   |
| Intel Comet Lake PCH-V cAVS                                                | 30       | 0.91%   |
| Nvidia TU116 High Definition Audio Controller                              | 27       | 0.82%   |
| Nvidia GP108 High Definition Audio Controller                              | 27       | 0.82%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 27       | 0.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 27       | 0.82%   |
| AMD Navi 10 HDMI Audio                                                     | 27       | 0.82%   |
| Nvidia MCP61 High Definition Audio                                         | 26       | 0.79%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 26       | 0.79%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 25       | 0.76%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 23       | 0.7%    |
| Intel Alder Lake-S HD Audio Controller                                     | 21       | 0.64%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 21       | 0.64%   |
| Nvidia GM206 High Definition Audio Controller                              | 20       | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 334      | 17.54%  |
| Unknown                      | 289      | 15.18%  |
| Crucial                      | 262      | 13.76%  |
| Samsung Electronics          | 191      | 10.03%  |
| SK hynix                     | 172      | 9.03%   |
| Corsair                      | 143      | 7.51%   |
| G.Skill                      | 103      | 5.41%   |
| Micron Technology            | 78       | 4.1%    |
| Patriot                      | 59       | 3.1%    |
| A-DATA Technology            | 29       | 1.52%   |
| Unknown                      | 26       | 1.37%   |
| Hikvision                    | 21       | 1.1%    |
| Team                         | 18       | 0.95%   |
| Ramaxel Technology           | 17       | 0.89%   |
| AMD                          | 15       | 0.79%   |
| Elpida                       | 12       | 0.63%   |
| Unknown (ABCD)               | 11       | 0.58%   |
| Nanya Technology             | 11       | 0.58%   |
| GOODRAM                      | 7        | 0.37%   |
| Transcend                    | 6        | 0.32%   |
| Smart                        | 5        | 0.26%   |
| GeIL                         | 5        | 0.26%   |
| Timetec                      | 4        | 0.21%   |
| Qimonda                      | 4        | 0.21%   |
| Hewlett-Packard              | 4        | 0.21%   |
| Apacer                       | 4        | 0.21%   |
| Toshiba                      | 3        | 0.16%   |
| Kingmax                      | 3        | 0.16%   |
| Goldkey                      | 3        | 0.16%   |
| V-Color                      | 2        | 0.11%   |
| Unknown (0x5846)             | 2        | 0.11%   |
| Unifosa                      | 2        | 0.11%   |
| Silicon Power                | 2        | 0.11%   |
| PNY                          | 2        | 0.11%   |
| Patriot Memory (PDP Systems) | 2        | 0.11%   |
| Kllisre                      | 2        | 0.11%   |
| KLEVV                        | 2        | 0.11%   |
| Kimtigo                      | 2        | 0.11%   |
| KETECH                       | 2        | 0.11%   |
| Infineon                     | 2        | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM SDRAM                            | 40       | 1.91%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s        | 35       | 1.67%   |
| Crucial RAM CT8G4DFRA266.M16FG 8GB DIMM DDR4 2666MT/s        | 31       | 1.48%   |
| Crucial RAM CT4G4DFS8213.C8FAR2 4GB DIMM DDR4 2133MT/s       | 27       | 1.29%   |
| Unknown                                                      | 26       | 1.24%   |
| Crucial RAM CT8G4DFRA266.C8FN 8GB DIMM DDR4 2866MT/s         | 24       | 1.15%   |
| Hikvision RAM HKED4161DAA1D0MA1 16GB DIMM DDR4 2667MT/s      | 20       | 0.96%   |
| Unknown RAM Module 1GB DIMM SDRAM                            | 19       | 0.91%   |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 18       | 0.86%   |
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s        | 18       | 0.86%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s        | 17       | 0.81%   |
| Patriot RAM PSD34G160081 4GB DIMM DDR3 1600MT/s              | 16       | 0.76%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 15       | 0.72%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 15       | 0.72%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                         | 14       | 0.67%   |
| Unknown RAM Module 1GB DIMM 800MT/s                          | 14       | 0.67%   |
| Patriot RAM PSD32G13332 2GB DIMM DDR3 1333MT/s               | 14       | 0.67%   |
| Crucial RAM CT8G4DFRA32A.M4FE 8GB DIMM DDR4 3200MT/s         | 12       | 0.57%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 11       | 0.53%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s            | 11       | 0.53%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                         | 10       | 0.48%   |
| Crucial RAM CT8G4DFD8213.C16FAR2 8GB DIMM DDR4 2133MT/s      | 10       | 0.48%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s          | 9        | 0.43%   |
| Kingston RAM 99U5474-013.A00LF 2GB DIMM DDR3 1600MT/s        | 9        | 0.43%   |
| Patriot RAM PSD32G133381 2GB DIMM DDR3 1333MT/s              | 8        | 0.38%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s       | 8        | 0.38%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s          | 8        | 0.38%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s        | 8        | 0.38%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3400MT/s                  | 8        | 0.38%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                    | 7        | 0.33%   |
| Unknown RAM Module 2GB DIMM                                  | 7        | 0.33%   |
| Unknown RAM Module 1GB DIMM                                  | 7        | 0.33%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s          | 7        | 0.33%   |
| Samsung RAM M378A1K43DB2-CTD 8GB DIMM DDR4 4333MT/s          | 7        | 0.33%   |
| Patriot RAM PSD38G13332 8GB DIMM DDR3 1333MT/s               | 7        | 0.33%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s        | 7        | 0.33%   |
| Kingston RAM 99U5474-025.A00LF 2GB DIMM DDR3 1333MT/s        | 7        | 0.33%   |
| Kingston RAM 9905474-012.A00LF 2048MB DIMM DDR3 1333MT/s     | 7        | 0.33%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s           | 7        | 0.33%   |
| Crucial RAM CT25664BA160B.D8FE 2048MB DIMM DDR3 1600MT/s     | 7        | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR4         | 753      | 44.32%  |
| DDR3         | 589      | 34.67%  |
| Unknown      | 125      | 7.36%   |
| SDRAM        | 103      | 6.06%   |
| DDR2         | 82       | 4.83%   |
| DDR          | 21       | 1.24%   |
| LPDDR4       | 14       | 0.82%   |
| DDR5         | 8        | 0.47%   |
| DRAM         | 3        | 0.18%   |
| DDR2 FB-DIMM | 1        | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 1569     | 93.56%  |
| SODIMM       | 97       | 5.78%   |
| FB-DIMM      | 4        | 0.24%   |
| Row Of Chips | 3        | 0.18%   |
| RIMM         | 2        | 0.12%   |
| Chip         | 1        | 0.06%   |
| Unknown      | 1        | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 581      | 31.47%  |
| 4096  | 440      | 23.84%  |
| 2048  | 317      | 17.17%  |
| 16384 | 253      | 13.71%  |
| 32768 | 113      | 6.12%   |
| 1024  | 106      | 5.74%   |
| 512   | 24       | 1.3%    |
| 256   | 6        | 0.33%   |
| 65536 | 4        | 0.22%   |
| 1536  | 1        | 0.05%   |
| 128   | 1        | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 332      | 18.1%   |
| 1333    | 223      | 12.16%  |
| 3200    | 154      | 8.4%    |
| 2667    | 135      | 7.36%   |
| 2400    | 110      | 6%      |
| 2133    | 93       | 5.07%   |
| 800     | 90       | 4.91%   |
| 3600    | 80       | 4.36%   |
| Unknown | 76       | 4.14%   |
| 2666    | 63       | 3.44%   |
| 1866    | 59       | 3.22%   |
| 667     | 46       | 2.51%   |
| 3400    | 30       | 1.64%   |
| 3000    | 27       | 1.47%   |
| 1066    | 27       | 1.47%   |
| 2866    | 26       | 1.42%   |
| 2933    | 25       | 1.36%   |
| 1067    | 21       | 1.15%   |
| 3466    | 20       | 1.09%   |
| 1867    | 20       | 1.09%   |
| 3733    | 18       | 0.98%   |
| 1800    | 17       | 0.93%   |
| 400     | 11       | 0.6%    |
| 3866    | 10       | 0.55%   |
| 3800    | 9        | 0.49%   |
| 1334    | 9        | 0.49%   |
| 533     | 9        | 0.49%   |
| 4800    | 8        | 0.44%   |
| 4333    | 7        | 0.38%   |
| 3066    | 6        | 0.33%   |
| 2800    | 6        | 0.33%   |
| 2048    | 6        | 0.33%   |
| 3500    | 5        | 0.27%   |
| 3100    | 5        | 0.27%   |
| 1648    | 4        | 0.22%   |
| 333     | 4        | 0.22%   |
| 266     | 4        | 0.22%   |
| 3266    | 3        | 0.16%   |
| 2733    | 3        | 0.16%   |
| 2465    | 3        | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 30       | 37.97%  |
| Brother Industries  | 16       | 20.25%  |
| Canon               | 8        | 10.13%  |
| Samsung Electronics | 5        | 6.33%   |
| Xerox               | 3        | 3.8%    |
| Seiko Epson         | 3        | 3.8%    |
| Dymo-CoStar         | 3        | 3.8%    |
| Zebra               | 2        | 2.53%   |
| Prolific Technology | 2        | 2.53%   |
| Pantum              | 2        | 2.53%   |
| STMicroelectronics  | 1        | 1.27%   |
| Kyocera             | 1        | 1.27%   |
| Konica Minolta      | 1        | 1.27%   |
| GODEX INTERNATIONAL | 1        | 1.27%   |
| Apple               | 1        | 1.27%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Xerox B205                                                | 3        | 3.8%    |
| HP LaserJet M101-M106                                     | 3        | 3.8%    |
| HP LaserJet 1200                                          | 3        | 3.8%    |
| HP LaserJet 1020                                          | 3        | 3.8%    |
| Samsung ML-1660 Series                                    | 2        | 2.53%   |
| Prolific PL2305 Parallel Port                             | 2        | 2.53%   |
| HP LaserJet P1005                                         | 2        | 2.53%   |
| HP ENVY 4520 series                                       | 2        | 2.53%   |
| Canon MF4410                                              | 2        | 2.53%   |
| Zebra ZTC ZP 500 (ZPL)                                    | 1        | 1.27%   |
| Zebra ZTC ZD420-203dpi ZPL                                | 1        | 1.27%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 1.27%   |
| Seiko Epson XP-200 Series                                 | 1        | 1.27%   |
| Seiko Epson ET-2710 Series                                | 1        | 1.27%   |
| Seiko Epson ET-2700 Series                                | 1        | 1.27%   |
| Samsung SCX-4650 4x21S Series                             | 1        | 1.27%   |
| Samsung SCX-3200 Series                                   | 1        | 1.27%   |
| Samsung ML-216x Series Laser Printer                      | 1        | 1.27%   |
| Pantum P2500W series                                      | 1        | 1.27%   |
| Pantum M6500-series                                       | 1        | 1.27%   |
| Kyocera ECOSYS M5521cdn                                   | 1        | 1.27%   |
| Konica Minolta bizhub 4402P                               | 1        | 1.27%   |
| HP Officejet J4500 series                                 | 1        | 1.27%   |
| HP Officejet 7110 series                                  | 1        | 1.27%   |
| HP LaserJet Pro M404-M405                                 | 1        | 1.27%   |
| HP LaserJet Pro M148-M149                                 | 1        | 1.27%   |
| HP LaserJet P2055 series                                  | 1        | 1.27%   |
| HP Laserjet P1505                                         | 1        | 1.27%   |
| HP LaserJet P1006                                         | 1        | 1.27%   |
| HP LaserJet M14-M17                                       | 1        | 1.27%   |
| HP LaserJet 400 M401n                                     | 1        | 1.27%   |
| HP LaserJet 1320                                          | 1        | 1.27%   |
| HP LaserJet 1300                                          | 1        | 1.27%   |
| HP LaserJet 1150                                          | 1        | 1.27%   |
| HP LaserJet 1015                                          | 1        | 1.27%   |
| HP ENVY Photo 6200 series                                 | 1        | 1.27%   |
| HP ENVY 5000 series                                       | 1        | 1.27%   |
| HP Deskjet 4640 series                                    | 1        | 1.27%   |
| HP DeskJet 2600 series                                    | 1        | 1.27%   |
| GODEX INTERNATIONAL DT2                                   | 1        | 1.27%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 10       | 55.56%  |
| Seiko Epson     | 3        | 16.67%  |
| Hewlett-Packard | 3        | 16.67%  |
| AGFA-Gevaert NV | 2        | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 220                                       | 3        | 16.67%  |
| Canon CanoScan N670U/N676U/LiDE 20                            | 2        | 11.11%  |
| Canon CanoScan LiDE 110                                       | 2        | 11.11%  |
| AGFA-Gevaert NV SnapScan 1212U (?)                            | 2        | 11.11%  |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]             | 1        | 5.56%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]      | 1        | 5.56%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1        | 5.56%   |
| HP ScanJet Pro 2500 f1                                        | 1        | 5.56%   |
| HP ScanJet 3970c                                              | 1        | 5.56%   |
| HP Scanjet 300                                                | 1        | 5.56%   |
| Canon CanoScan LiDE 210                                       | 1        | 5.56%   |
| Canon CanoScan 8800F                                          | 1        | 5.56%   |
| Canon CanoScan 5600F                                          | 1        | 5.56%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 107      | 41.63%  |
| Microdia                      | 21       | 8.17%   |
| Generalplus Technology        | 12       | 4.67%   |
| Sunplus Innovation Technology | 11       | 4.28%   |
| Microsoft                     | 9        | 3.5%    |
| Samsung Electronics           | 8        | 3.11%   |
| Creative Technology           | 8        | 3.11%   |
| Apple                         | 8        | 3.11%   |
| KYE Systems (Mouse Systems)   | 6        | 2.33%   |
| Jieli Technology              | 5        | 1.95%   |
| ARC International             | 5        | 1.95%   |
| Z-Star Microelectronics       | 4        | 1.56%   |
| Novatek Microelectronics      | 3        | 1.17%   |
| Genesys Logic                 | 3        | 1.17%   |
| Chicony Electronics           | 3        | 1.17%   |
| Xiongmai                      | 2        | 0.78%   |
| Unknown                       | 2        | 0.78%   |
| Nintendo                      | 2        | 0.78%   |
| MacroSilicon                  | 2        | 0.78%   |
| Google                        | 2        | 0.78%   |
| GEMBIRD                       | 2        | 0.78%   |
| AVerMedia Technologies        | 2        | 0.78%   |
| Arkmicro Technologies         | 2        | 0.78%   |
| 2M UVC CAMERA                 | 2        | 0.78%   |
| Xiaomi                        | 1        | 0.39%   |
| WaveRider Communications      | 1        | 0.39%   |
| Valve Software                | 1        | 0.39%   |
| Trust                         | 1        | 0.39%   |
| SunplusIT                     | 1        | 0.39%   |
| Sunplus IT                    | 1        | 0.39%   |
| Silicon Motion                | 1        | 0.39%   |
| SiGma Micro                   | 1        | 0.39%   |
| Ruision                       | 1        | 0.39%   |
| Realtek Semiconductor         | 1        | 0.39%   |
| Razer USA                     | 1        | 0.39%   |
| Mimaki Engineering            | 1        | 0.39%   |
| Lite-On Technology            | 1        | 0.39%   |
| Linux Foundation              | 1        | 0.39%   |
| Lenovo                        | 1        | 0.39%   |
| IMC Networks                  | 1        | 0.39%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Logitech Webcam C270                            | 39       | 15.06%  |
| Logitech C922 Pro Stream Webcam                 | 12       | 4.63%   |
| Logitech HD Pro Webcam C920                     | 10       | 3.86%   |
| Microdia USB 2.0 Camera                         | 9        | 3.47%   |
| Samsung Galaxy A5 (MTP)                         | 8        | 3.09%   |
| Apple iPhone 5/5C/5S/6/SE                       | 8        | 3.09%   |
| Microdia Webcam Vitade AF                       | 7        | 2.7%    |
| Generalplus GENERAL WEBCAM                      | 7        | 2.7%    |
| Microsoft LifeCam HD-3000                       | 6        | 2.32%   |
| Logitech Webcam C170                            | 6        | 2.32%   |
| Logitech HD Webcam C615                         | 5        | 1.93%   |
| Jieli USB PHY 2.0                               | 5        | 1.93%   |
| Logitech C920 PRO HD Webcam                     | 4        | 1.54%   |
| Creative Live! Cam Chat HD [VF0700]             | 4        | 1.54%   |
| Z-Star Venus USB2.0 Camera                      | 3        | 1.16%   |
| Novatek HP High Definition 2MP Webcam           | 3        | 1.16%   |
| Logitech Webcam C310                            | 3        | 1.16%   |
| Logitech Logi Webcam C920e                      | 3        | 1.16%   |
| Logitech HD Webcam C910                         | 3        | 1.16%   |
| Logitech BRIO Ultra HD Webcam                   | 3        | 1.16%   |
| KYE Systems (Mouse Systems) JOYACCESS JA-Webcam | 3        | 1.16%   |
| Generalplus 808 Camera #9 (web-cam mode)        | 3        | 1.16%   |
| ARC International Camera                        | 3        | 1.16%   |
| Xiongmai web camera                             | 2        | 0.77%   |
| Sunplus Full HD webcam                          | 2        | 0.77%   |
| Sunplus FHD Camera Microphone                   | 2        | 0.77%   |
| Nintendo USB Camera                             | 2        | 0.77%   |
| Microdia Sonix USB 2.0 Camera                   | 2        | 0.77%   |
| Logitech Webcam C925e                           | 2        | 0.77%   |
| Logitech StreamCam                              | 2        | 0.77%   |
| Logitech HD Webcam C525                         | 2        | 0.77%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera      | 2        | 0.77%   |
| Genesys Logic USB2.0 Digital Camera             | 2        | 0.77%   |
| Generalplus 2K HD Camera                        | 2        | 0.77%   |
| Creative Live! Cam Optia AF                     | 2        | 0.77%   |
| Arkmicro USB2.0 PC CAMERA                       | 2        | 0.77%   |
| ARC International Camera - 1080p                | 2        | 0.77%   |
| 2M UVC CAMERA NexiGo N660 FHD Webcam            | 2        | 0.77%   |
| Z-Star Integrated Camera                        | 1        | 0.39%   |
| Xiaomi Mi 10 Lite 5G                            | 1        | 0.39%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Validity Sensors | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| SCM Microsystems      | 3        | 21.43%  |
| Gemalto (was Gemplus) | 2        | 14.29%  |
| Alcor Micro           | 2        | 14.29%  |
| Yubico.com            | 1        | 7.14%   |
| Lenovo                | 1        | 7.14%   |
| Feitian Technologies  | 1        | 7.14%   |
| Clay Logic            | 1        | 7.14%   |
| Chicony Electronics   | 1        | 7.14%   |
| Cherry                | 1        | 7.14%   |
| Advanced Card Systems | 1        | 7.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 2        | 14.29%  |
| Yubico.com Yubikey 4/5 CCID                            | 1        | 7.14%   |
| SCM Microsystems uTrust 3512 SAM slot Token            | 1        | 7.14%   |
| Lenovo Smartcard Keyboard                              | 1        | 7.14%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader      | 1        | 7.14%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader       | 1        | 7.14%   |
| Feitian Technologies SCR301                            | 1        | 7.14%   |
| Clay Logic Nitrokey Pro                                | 1        | 7.14%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard   | 1        | 7.14%   |
| Cherry SmartTerminal XX1X                              | 1        | 7.14%   |
| Alcor Micro Watchdata W 1981                           | 1        | 7.14%   |
| Alcor Micro AU9540 Smartcard Reader                    | 1        | 7.14%   |
| Advanced Card Systems ACR39U                           | 1        | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1078     | 55%     |
| 1     | 779      | 39.74%  |
| 2     | 90       | 4.59%   |
| 3     | 9        | 0.46%   |
| 4     | 2        | 0.1%    |
| 7     | 1        | 0.05%   |
| 5     | 1        | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 757      | 80.79%  |
| Net/wireless             | 55       | 5.87%   |
| Communication controller | 28       | 2.99%   |
| Unassigned class         | 26       | 2.77%   |
| Sound                    | 13       | 1.39%   |
| Multimedia controller    | 11       | 1.17%   |
| Bluetooth                | 9        | 0.96%   |
| Camera                   | 8        | 0.85%   |
| Chipcard                 | 6        | 0.64%   |
| Net/ethernet             | 5        | 0.53%   |
| Card reader              | 5        | 0.53%   |
| Storage/raid             | 4        | 0.43%   |
| Tv card                  | 3        | 0.32%   |
| Modem                    | 3        | 0.32%   |
| Storage                  | 1        | 0.11%   |
| Network                  | 1        | 0.11%   |
| Fingerprint reader       | 1        | 0.11%   |
| Dvb card                 | 1        | 0.11%   |

