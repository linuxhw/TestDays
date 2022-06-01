Linux in France - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in France.

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

Total: 3523

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | 3148 SDK0K13476 WIN 3306... | [5723328e24](https://linux-hardware.org/?probe=5723328e24) | May 31, 2022 |
| ASRock        | N68C-GS4 FX                 | [d7db5b0968](https://linux-hardware.org/?probe=d7db5b0968) | May 30, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | [b0e96de917](https://linux-hardware.org/?probe=b0e96de917) | May 30, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | [b4f73129a2](https://linux-hardware.org/?probe=b4f73129a2) | May 30, 2022 |
| Gigabyte      | X570 UD                     | [627604d5dc](https://linux-hardware.org/?probe=627604d5dc) | May 29, 2022 |
| ASRock        | B85M-HDS                    | [54a1e6b445](https://linux-hardware.org/?probe=54a1e6b445) | May 29, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | [c1dd2cf1be](https://linux-hardware.org/?probe=c1dd2cf1be) | May 29, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | [0df520da7e](https://linux-hardware.org/?probe=0df520da7e) | May 29, 2022 |
| Shuttle       | FS81                        | [756f86d9fc](https://linux-hardware.org/?probe=756f86d9fc) | May 28, 2022 |
| Acer          | Veriton X2631G V:1.0        | [3c144d36f0](https://linux-hardware.org/?probe=3c144d36f0) | May 28, 2022 |
| ASUSTek       | H110M-K                     | [9ff7306bbd](https://linux-hardware.org/?probe=9ff7306bbd) | May 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | [ed9c55ffc6](https://linux-hardware.org/?probe=ed9c55ffc6) | May 28, 2022 |
| Acer          | Veriton X2631G V:1.0        | [26e26a3995](https://linux-hardware.org/?probe=26e26a3995) | May 28, 2022 |
| MSI           | B450 TOMAHAWK               | [2651c1881a](https://linux-hardware.org/?probe=2651c1881a) | May 27, 2022 |
| ASRock        | N68C-GS4 FX                 | [e78421dc9f](https://linux-hardware.org/?probe=e78421dc9f) | May 27, 2022 |
| Dell          | 0YJPT1 A00                  | [b122151e55](https://linux-hardware.org/?probe=b122151e55) | May 27, 2022 |
| ASUSTek       | P8H61                       | [0145453c1a](https://linux-hardware.org/?probe=0145453c1a) | May 27, 2022 |
| Fujitsu Si... | D2840-A1 S26361-D2840-A1    | [a9d7621b8d](https://linux-hardware.org/?probe=a9d7621b8d) | May 26, 2022 |
| MSI           | X370 GAMING PLUS            | [2f96ea6c22](https://linux-hardware.org/?probe=2f96ea6c22) | May 26, 2022 |
| ASUSTek       | PRIME X570-P                | [3774c9e6e6](https://linux-hardware.org/?probe=3774c9e6e6) | May 26, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [740aeb1dff](https://linux-hardware.org/?probe=740aeb1dff) | May 26, 2022 |
| ASUSTek       | PRIME X470-PRO              | [496399846f](https://linux-hardware.org/?probe=496399846f) | May 26, 2022 |
| MSI           | A320M-A PRO MAX             | [f1ccdbbba4](https://linux-hardware.org/?probe=f1ccdbbba4) | May 26, 2022 |
| Gigabyte      | F2A78M-HD2                  | [fc9dd3db05](https://linux-hardware.org/?probe=fc9dd3db05) | May 26, 2022 |
| ASUSTek       | PRIME X570-P                | [f52de609a0](https://linux-hardware.org/?probe=f52de609a0) | May 26, 2022 |
| Gigabyte      | B450M H                     | [9c3f88c494](https://linux-hardware.org/?probe=9c3f88c494) | May 25, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [44386f8bae](https://linux-hardware.org/?probe=44386f8bae) | May 25, 2022 |
| ASUSTek       | P8Z77-M                     | [6e2da39201](https://linux-hardware.org/?probe=6e2da39201) | May 25, 2022 |
| Pegatron      | 2A94                        | [0b4773f876](https://linux-hardware.org/?probe=0b4773f876) | May 25, 2022 |
| Lenovo        | MAHOBAY NOK                 | [aa8d9cb3b9](https://linux-hardware.org/?probe=aa8d9cb3b9) | May 25, 2022 |
| Packard Be... | IMEDIA S3840                | [d102437a6f](https://linux-hardware.org/?probe=d102437a6f) | May 25, 2022 |
| ASUSTek       | M4N68T-M-V2                 | [e317246d50](https://linux-hardware.org/?probe=e317246d50) | May 24, 2022 |
| Shuttle       | FH170                       | [2645369ebc](https://linux-hardware.org/?probe=2645369ebc) | May 24, 2022 |
| HP            | 83EE                        | [dba7684d63](https://linux-hardware.org/?probe=dba7684d63) | May 24, 2022 |
| ASRock        | H470M-ITX/ac                | [181f7decc6](https://linux-hardware.org/?probe=181f7decc6) | May 24, 2022 |
| ASRockRack    | E3C232D2I                   | [0442460b97](https://linux-hardware.org/?probe=0442460b97) | May 24, 2022 |
| Gigabyte      | 970A-DS3P                   | [23d890ffc6](https://linux-hardware.org/?probe=23d890ffc6) | May 23, 2022 |
| Shuttle       | FS110                       | [d1147263be](https://linux-hardware.org/?probe=d1147263be) | May 23, 2022 |
| ASUSTek       | H61M-C                      | [4b17ea4a7f](https://linux-hardware.org/?probe=4b17ea4a7f) | May 23, 2022 |
| Dell          | 0F6X5P A00                  | [506150769b](https://linux-hardware.org/?probe=506150769b) | May 23, 2022 |
| ASUSTek       | ROG Maximus XII FORMULA     | [685e1fb0e9](https://linux-hardware.org/?probe=685e1fb0e9) | May 22, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [3e34ce179d](https://linux-hardware.org/?probe=3e34ce179d) | May 22, 2022 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | [0c144ce08f](https://linux-hardware.org/?probe=0c144ce08f) | May 22, 2022 |
| ASUSTek       | ROG Maximus XII FORMULA     | [d702284a55](https://linux-hardware.org/?probe=d702284a55) | May 22, 2022 |
| Intel         | D33217GKE G76540-203        | [306d3e6caf](https://linux-hardware.org/?probe=306d3e6caf) | May 22, 2022 |
| Shuttle       | FS110                       | [4845946b59](https://linux-hardware.org/?probe=4845946b59) | May 22, 2022 |
| MSI           | H97M-G43                    | [3869b1146e](https://linux-hardware.org/?probe=3869b1146e) | May 22, 2022 |
| ASUSTek       | P7P55D-E PRO                | [dfa1010543](https://linux-hardware.org/?probe=dfa1010543) | May 21, 2022 |
| Gigabyte      | Z77P-D3                     | [fc0a2b2595](https://linux-hardware.org/?probe=fc0a2b2595) | May 21, 2022 |
| MSI           | B450-A PRO MAX              | [0fe6809527](https://linux-hardware.org/?probe=0fe6809527) | May 20, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [a21b574411](https://linux-hardware.org/?probe=a21b574411) | May 20, 2022 |
| ASUSTek       | Maximus III Formula         | [866cd3e9f6](https://linux-hardware.org/?probe=866cd3e9f6) | May 20, 2022 |
| ASUSTek       | Z87-DELUXE                  | [bcd22d5d0e](https://linux-hardware.org/?probe=bcd22d5d0e) | May 20, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [73fdd642c6](https://linux-hardware.org/?probe=73fdd642c6) | May 19, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [6a9166ca20](https://linux-hardware.org/?probe=6a9166ca20) | May 19, 2022 |
| MSI           | H110M PRO-VD                | [5c61e35792](https://linux-hardware.org/?probe=5c61e35792) | May 19, 2022 |
| MSI           | MAG B560M MORTAR WIFI       | [4e7e663f39](https://linux-hardware.org/?probe=4e7e663f39) | May 19, 2022 |
| ASUSTek       | Z97-C                       | [11968efbc5](https://linux-hardware.org/?probe=11968efbc5) | May 19, 2022 |
| ASRock        | B560M Pro4                  | [ba3b29db98](https://linux-hardware.org/?probe=ba3b29db98) | May 18, 2022 |
| ASUSTek       | PRIME B450M-K               | [54f3323bd2](https://linux-hardware.org/?probe=54f3323bd2) | May 18, 2022 |
| MSI           | B350M MORTAR                | [fd66fd9a5a](https://linux-hardware.org/?probe=fd66fd9a5a) | May 18, 2022 |
| ASUSTek       | P8Z68-V PRO GEN3            | [8a6fc346c5](https://linux-hardware.org/?probe=8a6fc346c5) | May 18, 2022 |
| ASUSTek       | PRIME B450M-K               | [1dba88e243](https://linux-hardware.org/?probe=1dba88e243) | May 18, 2022 |
| Apple         | Mac-F221BEC8                | [92c20deb50](https://linux-hardware.org/?probe=92c20deb50) | May 17, 2022 |
| Gigabyte      | B75N                        | [b3e561590b](https://linux-hardware.org/?probe=b3e561590b) | May 17, 2022 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [818ee286b7](https://linux-hardware.org/?probe=818ee286b7) | May 17, 2022 |
| Pegatron      | 2A94                        | [c54b357993](https://linux-hardware.org/?probe=c54b357993) | May 16, 2022 |
| Dell          | 0GTK4K A02                  | [fba6de28d9](https://linux-hardware.org/?probe=fba6de28d9) | May 16, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [efe02f8593](https://linux-hardware.org/?probe=efe02f8593) | May 16, 2022 |
| ASUSTek       | H110T                       | [e1d711b496](https://linux-hardware.org/?probe=e1d711b496) | May 16, 2022 |
| Lenovo        | 3168 NOK                    | [273ebcdba6](https://linux-hardware.org/?probe=273ebcdba6) | May 15, 2022 |
| MSI           | MEG X570 UNIFY              | [4d00452dcb](https://linux-hardware.org/?probe=4d00452dcb) | May 15, 2022 |
| Gigabyte      | PH67A-D3-B3                 | [e819cbe6f7](https://linux-hardware.org/?probe=e819cbe6f7) | May 15, 2022 |
| ASUSTek       | H170M-PLUS                  | [c1f5cb662f](https://linux-hardware.org/?probe=c1f5cb662f) | May 15, 2022 |
| Gigabyte      | PH67A-D3-B3                 | [a292b16ff7](https://linux-hardware.org/?probe=a292b16ff7) | May 14, 2022 |
| Dell          | 0JGM7F A00                  | [49bb61d936](https://linux-hardware.org/?probe=49bb61d936) | May 14, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [3112931a28](https://linux-hardware.org/?probe=3112931a28) | May 14, 2022 |
| Dell          | 0JGM7F A00                  | [1f5b1d9c0a](https://linux-hardware.org/?probe=1f5b1d9c0a) | May 14, 2022 |
| MSI           | 970 GAMING                  | [bb9d221b00](https://linux-hardware.org/?probe=bb9d221b00) | May 14, 2022 |
| Gigabyte      | P55-UD3R                    | [638e77ebd8](https://linux-hardware.org/?probe=638e77ebd8) | May 13, 2022 |
| Acer          | Veriton M670G               | [a583d3a342](https://linux-hardware.org/?probe=a583d3a342) | May 13, 2022 |
| ASUSTek       | F1A75-M LE                  | [823a7381c9](https://linux-hardware.org/?probe=823a7381c9) | May 13, 2022 |
| MSI           | B450M MORTAR TITANIUM       | [b03899e10b](https://linux-hardware.org/?probe=b03899e10b) | May 13, 2022 |
| ASUSTek       | F1A75-M LE                  | [d7733a6d5e](https://linux-hardware.org/?probe=d7733a6d5e) | May 13, 2022 |
| Shuttle       | FH170                       | [9a5b55b35c](https://linux-hardware.org/?probe=9a5b55b35c) | May 13, 2022 |
| MSI           | Z97 GAMING 5                | [e395176aad](https://linux-hardware.org/?probe=e395176aad) | May 13, 2022 |
| ASUSTek       | PRIME A320M-K               | [a0a6e09b95](https://linux-hardware.org/?probe=a0a6e09b95) | May 13, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [bf4afe4481](https://linux-hardware.org/?probe=bf4afe4481) | May 12, 2022 |
| Lenovo        | SHARKBAY NOK                | [7923c29010](https://linux-hardware.org/?probe=7923c29010) | May 11, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [b1d977cd69](https://linux-hardware.org/?probe=b1d977cd69) | May 11, 2022 |
| Dell          | 0DR845                      | [ab501b0efe](https://linux-hardware.org/?probe=ab501b0efe) | May 10, 2022 |
| MSI           | B360 GAMING PLUS            | [4591877807](https://linux-hardware.org/?probe=4591877807) | May 10, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [c8eccf75df](https://linux-hardware.org/?probe=c8eccf75df) | May 09, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [ca1de5c6ae](https://linux-hardware.org/?probe=ca1de5c6ae) | May 09, 2022 |
| Gigabyte      | X570 UD                     | [20c66a91ff](https://linux-hardware.org/?probe=20c66a91ff) | May 09, 2022 |
| MSI           | 760GM-P34                   | [85bea22dfe](https://linux-hardware.org/?probe=85bea22dfe) | May 09, 2022 |
| ASUSTek       | Z87-A                       | [ecff4161ad](https://linux-hardware.org/?probe=ecff4161ad) | May 08, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [8f09cb9a0e](https://linux-hardware.org/?probe=8f09cb9a0e) | May 08, 2022 |
| Pegatron      | Eureka3                     | [e383533179](https://linux-hardware.org/?probe=e383533179) | May 08, 2022 |
| Packard Be... | 1.XX                        | [d06b70fd87](https://linux-hardware.org/?probe=d06b70fd87) | May 08, 2022 |
| Packard Be... | 1.XX                        | [9f3bfe5333](https://linux-hardware.org/?probe=9f3bfe5333) | May 08, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | [dc9b228486](https://linux-hardware.org/?probe=dc9b228486) | May 08, 2022 |
| ASUSTek       | SABERTOOTH X58              | [c276639676](https://linux-hardware.org/?probe=c276639676) | May 08, 2022 |
| ASUSTek       | P8H77-V LE                  | [acf562b58b](https://linux-hardware.org/?probe=acf562b58b) | May 08, 2022 |
| ASUSTek       | P8H77-V LE                  | [1a3e2da376](https://linux-hardware.org/?probe=1a3e2da376) | May 08, 2022 |
| ASUSTek       | SABERTOOTH X58              | [3aa3223913](https://linux-hardware.org/?probe=3aa3223913) | May 07, 2022 |
| Acer          | F690GVM                     | [4883e77b23](https://linux-hardware.org/?probe=4883e77b23) | May 07, 2022 |
| HP            | 1495                        | [4b63b733be](https://linux-hardware.org/?probe=4b63b733be) | May 06, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [216b5bc826](https://linux-hardware.org/?probe=216b5bc826) | May 06, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [54046196e9](https://linux-hardware.org/?probe=54046196e9) | May 06, 2022 |
| Dell          | 0GK35Y A00                  | [0be64397bb](https://linux-hardware.org/?probe=0be64397bb) | May 06, 2022 |
| ASUSTek       | EB1501P                     | [f1d427d32b](https://linux-hardware.org/?probe=f1d427d32b) | May 06, 2022 |
| HP            | 1495                        | [c845f7b657](https://linux-hardware.org/?probe=c845f7b657) | May 05, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [d0a7dbb1e0](https://linux-hardware.org/?probe=d0a7dbb1e0) | May 04, 2022 |
| ASUSTek       | PRIME B360-PLUS             | [4ce66ff579](https://linux-hardware.org/?probe=4ce66ff579) | May 04, 2022 |
| MSI           | H97M-G43                    | [498fd4cdca](https://linux-hardware.org/?probe=498fd4cdca) | May 03, 2022 |
| MSI           | H97 GAMING 3                | [c3694433d0](https://linux-hardware.org/?probe=c3694433d0) | May 03, 2022 |
| Lenovo        | ThinkCentre M57e 6176A13    | [c920b52ec3](https://linux-hardware.org/?probe=c920b52ec3) | May 02, 2022 |
| MSI           | B450I GAMING PLUS AC        | [c0ef0738b5](https://linux-hardware.org/?probe=c0ef0738b5) | May 02, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [04c7c1f7f4](https://linux-hardware.org/?probe=04c7c1f7f4) | May 02, 2022 |
| ASUSTek       | PRIME B450M-A               | [fac138a25c](https://linux-hardware.org/?probe=fac138a25c) | May 02, 2022 |
| ASUSTek       | F1A75-M LE                  | [93232d0716](https://linux-hardware.org/?probe=93232d0716) | May 01, 2022 |
| Gigabyte      | H61M-DS2 x.x                | [463e99eb8c](https://linux-hardware.org/?probe=463e99eb8c) | Apr 30, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [22008db28a](https://linux-hardware.org/?probe=22008db28a) | Apr 30, 2022 |
| ASRock        | B550 Extreme4               | [7a90a198f5](https://linux-hardware.org/?probe=7a90a198f5) | Apr 30, 2022 |
| ASUSTek       | P8H61-M                     | [942f86f88a](https://linux-hardware.org/?probe=942f86f88a) | Apr 30, 2022 |
| ASRock        | B550 Extreme4               | [75362e2061](https://linux-hardware.org/?probe=75362e2061) | Apr 30, 2022 |
| Gigabyte      | 990FXA-UD3                  | [9b128bc47e](https://linux-hardware.org/?probe=9b128bc47e) | Apr 30, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [970d30df6d](https://linux-hardware.org/?probe=970d30df6d) | Apr 29, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [686f4acac4](https://linux-hardware.org/?probe=686f4acac4) | Apr 29, 2022 |
| ASUSTek       | B150 PRO GAMING D3          | [e258d71e2e](https://linux-hardware.org/?probe=e258d71e2e) | Apr 29, 2022 |
| Foxconn       | 2A8C                        | [eb747a3063](https://linux-hardware.org/?probe=eb747a3063) | Apr 29, 2022 |
| Dell          | 08NPPY A00                  | [6c4d2173a5](https://linux-hardware.org/?probe=6c4d2173a5) | Apr 27, 2022 |
| ASRock        | B550 Extreme4               | [a7061bdb08](https://linux-hardware.org/?probe=a7061bdb08) | Apr 27, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [f06ce3d416](https://linux-hardware.org/?probe=f06ce3d416) | Apr 27, 2022 |
| Gigabyte      | B560M DS3H V2               | [4854a84496](https://linux-hardware.org/?probe=4854a84496) | Apr 27, 2022 |
| ASRock        | B550 Extreme4               | [fcd8a2962e](https://linux-hardware.org/?probe=fcd8a2962e) | Apr 26, 2022 |
| ASUSTek       | P6T DELUXE V2               | [0e266b4987](https://linux-hardware.org/?probe=0e266b4987) | Apr 25, 2022 |
| MSI           | MEG X570 ACE                | [6807da5804](https://linux-hardware.org/?probe=6807da5804) | Apr 25, 2022 |
| ASUSTek       | G20AJ                       | [ed023008e4](https://linux-hardware.org/?probe=ed023008e4) | Apr 25, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [71c83c7998](https://linux-hardware.org/?probe=71c83c7998) | Apr 25, 2022 |
| MSI           | MEG X570 ACE                | [e558893ff0](https://linux-hardware.org/?probe=e558893ff0) | Apr 25, 2022 |
| MSI           | MEG B550 UNIFY              | [3cf3319591](https://linux-hardware.org/?probe=3cf3319591) | Apr 25, 2022 |
| Gigabyte      | G41M-Combo                  | [5bfd7adb54](https://linux-hardware.org/?probe=5bfd7adb54) | Apr 24, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [3f1d42f10f](https://linux-hardware.org/?probe=3f1d42f10f) | Apr 24, 2022 |
| ASUSTek       | B85M-E                      | [31572b098d](https://linux-hardware.org/?probe=31572b098d) | Apr 24, 2022 |
| HP            | 2820h                       | [3918640e67](https://linux-hardware.org/?probe=3918640e67) | Apr 23, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [31ff0c4c22](https://linux-hardware.org/?probe=31ff0c4c22) | Apr 23, 2022 |
| Pegatron      | IPPPV-D3G                   | [2eea78768b](https://linux-hardware.org/?probe=2eea78768b) | Apr 23, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | [929f99800a](https://linux-hardware.org/?probe=929f99800a) | Apr 23, 2022 |
| MSI           | P67A-GD65                   | [ff96b12477](https://linux-hardware.org/?probe=ff96b12477) | Apr 23, 2022 |
| AMI           | Cherry Trail Tablet         | [a2179e3116](https://linux-hardware.org/?probe=a2179e3116) | Apr 22, 2022 |
| MSI           | Z77A-G43                    | [e0729e8375](https://linux-hardware.org/?probe=e0729e8375) | Apr 22, 2022 |
| ASUSTek       | P5QC                        | [63f53fd6cb](https://linux-hardware.org/?probe=63f53fd6cb) | Apr 22, 2022 |
| Pegatron      | EVANS                       | [118f512619](https://linux-hardware.org/?probe=118f512619) | Apr 21, 2022 |
| Acer          | Nitro N50-600 V:1.1         | [15332404e6](https://linux-hardware.org/?probe=15332404e6) | Apr 21, 2022 |
| Acer          | Nitro N50-600 V:1.1         | [b272388aa6](https://linux-hardware.org/?probe=b272388aa6) | Apr 21, 2022 |
| Dell          | 040DDP A01                  | [0830bf0a35](https://linux-hardware.org/?probe=0830bf0a35) | Apr 20, 2022 |
| MSI           | H110M PRO-VD PLUS           | [37d0f0bb74](https://linux-hardware.org/?probe=37d0f0bb74) | Apr 20, 2022 |
| ASUSTek       | Leonite2                    | [e8813012dd](https://linux-hardware.org/?probe=e8813012dd) | Apr 19, 2022 |
| Gigabyte      | H170-HD3-CF                 | [cebf5b3135](https://linux-hardware.org/?probe=cebf5b3135) | Apr 17, 2022 |
| HP            | 18E5                        | [211d35a24b](https://linux-hardware.org/?probe=211d35a24b) | Apr 17, 2022 |
| Intel         | DH61BE AAG14062-206         | [4816f51374](https://linux-hardware.org/?probe=4816f51374) | Apr 17, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [7afe8794c5](https://linux-hardware.org/?probe=7afe8794c5) | Apr 16, 2022 |
| ASUSTek       | G20AJ                       | [f83ee2cc17](https://linux-hardware.org/?probe=f83ee2cc17) | Apr 16, 2022 |
| ASUSTek       | G20AJ                       | [eef3c69fcd](https://linux-hardware.org/?probe=eef3c69fcd) | Apr 16, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [eae3d7f803](https://linux-hardware.org/?probe=eae3d7f803) | Apr 15, 2022 |
| Dell          | 0M5DCD A00                  | [8da74b67c8](https://linux-hardware.org/?probe=8da74b67c8) | Apr 15, 2022 |
| ASUSTek       | Z97-K/USB                   | [16aaadda77](https://linux-hardware.org/?probe=16aaadda77) | Apr 14, 2022 |
| BESSTAR Te... | HM80                        | [80b368187a](https://linux-hardware.org/?probe=80b368187a) | Apr 14, 2022 |
| MSI           | Z390-A PRO                  | [a642b9ec3a](https://linux-hardware.org/?probe=a642b9ec3a) | Apr 14, 2022 |
| ASUSTek       | P8P67 LE                    | [84abfd3112](https://linux-hardware.org/?probe=84abfd3112) | Apr 14, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [191880e24b](https://linux-hardware.org/?probe=191880e24b) | Apr 14, 2022 |
| MSI           | B150M PRO-VD D3             | [84bd94d672](https://linux-hardware.org/?probe=84bd94d672) | Apr 13, 2022 |
| Gigabyte      | Z97X-Gaming 3               | [5d45d7b3f7](https://linux-hardware.org/?probe=5d45d7b3f7) | Apr 13, 2022 |
| Gigabyte      | Z97X-UD3H-CF                | [a676bf83eb](https://linux-hardware.org/?probe=a676bf83eb) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [392f621ca6](https://linux-hardware.org/?probe=392f621ca6) | Apr 13, 2022 |
| ASRock        | B550 Extreme4               | [f74831788b](https://linux-hardware.org/?probe=f74831788b) | Apr 13, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [fe40f7c199](https://linux-hardware.org/?probe=fe40f7c199) | Apr 13, 2022 |
| HP            | 3648h                       | [fef6cf4c12](https://linux-hardware.org/?probe=fef6cf4c12) | Apr 13, 2022 |
| MSI           | X470 GAMING PRO             | [1ba8ee75be](https://linux-hardware.org/?probe=1ba8ee75be) | Apr 13, 2022 |
| ASUSTek       | H97-PLUS                    | [234fd15d56](https://linux-hardware.org/?probe=234fd15d56) | Apr 13, 2022 |
| Pegatron      | 2AD5                        | [3a1253ff97](https://linux-hardware.org/?probe=3a1253ff97) | Apr 13, 2022 |
| ASUSTek       | H81M-A                      | [9d42acb7dc](https://linux-hardware.org/?probe=9d42acb7dc) | Apr 13, 2022 |
| Gigabyte      | H87M-D3H                    | [f638f9b557](https://linux-hardware.org/?probe=f638f9b557) | Apr 13, 2022 |
| Dell          | 0YXT71 A01                  | [682a5bc6cc](https://linux-hardware.org/?probe=682a5bc6cc) | Apr 13, 2022 |
| Gigabyte      | B560M DS3H V2               | [175d1ee5ad](https://linux-hardware.org/?probe=175d1ee5ad) | Apr 12, 2022 |
| Gigabyte      | X570 AORUS PRO              | [7819bdfd17](https://linux-hardware.org/?probe=7819bdfd17) | Apr 12, 2022 |
| MSI           | H510M-A PRO                 | [fdb4e581a9](https://linux-hardware.org/?probe=fdb4e581a9) | Apr 11, 2022 |
| ASUSTek       | PRIME Z270-A                | [c31ef29891](https://linux-hardware.org/?probe=c31ef29891) | Apr 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [2a33f087e6](https://linux-hardware.org/?probe=2a33f087e6) | Apr 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [05b9ec80c6](https://linux-hardware.org/?probe=05b9ec80c6) | Apr 11, 2022 |
| Jetway        | 1.0                         | [dbfff94911](https://linux-hardware.org/?probe=dbfff94911) | Apr 10, 2022 |
| Dell          | 0200DY A00                  | [38488f5c3a](https://linux-hardware.org/?probe=38488f5c3a) | Apr 10, 2022 |
| HP            | 3048h                       | [c55f6bc20c](https://linux-hardware.org/?probe=c55f6bc20c) | Apr 10, 2022 |
| HP            | 1998                        | [28dcd611cc](https://linux-hardware.org/?probe=28dcd611cc) | Apr 10, 2022 |
| ASUSTek       | H110I-PLUS                  | [e367ac99ce](https://linux-hardware.org/?probe=e367ac99ce) | Apr 10, 2022 |
| ASRock        | Z87 Pro4                    | [03ee27c2ea](https://linux-hardware.org/?probe=03ee27c2ea) | Apr 09, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [48c13b2a02](https://linux-hardware.org/?probe=48c13b2a02) | Apr 09, 2022 |
| ASUSTek       | P7P55-M                     | [dd609f533b](https://linux-hardware.org/?probe=dd609f533b) | Apr 09, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | [2db23c062e](https://linux-hardware.org/?probe=2db23c062e) | Apr 08, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [7305c4d766](https://linux-hardware.org/?probe=7305c4d766) | Apr 08, 2022 |
| ASUSTek       | ROG STRIX Z490-I GAMING     | [3cfcaa0d11](https://linux-hardware.org/?probe=3cfcaa0d11) | Apr 08, 2022 |
| HP            | 82F2 A01                    | [6eb23290be](https://linux-hardware.org/?probe=6eb23290be) | Apr 08, 2022 |
| MSI           | Z77A-GD65                   | [030e3f6ea9](https://linux-hardware.org/?probe=030e3f6ea9) | Apr 07, 2022 |
| ASUSTek       | STRIKER II FORMULA          | [5dfea21930](https://linux-hardware.org/?probe=5dfea21930) | Apr 07, 2022 |
| ASUSTek       | STRIKER II FORMULA          | [040990b3fc](https://linux-hardware.org/?probe=040990b3fc) | Apr 07, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [e50ab269b2](https://linux-hardware.org/?probe=e50ab269b2) | Apr 06, 2022 |
| MSI           | Z370-A PRO                  | [c4f0f0573c](https://linux-hardware.org/?probe=c4f0f0573c) | Apr 06, 2022 |
| Dell          | 0Y2MRG A00                  | [d764d51af9](https://linux-hardware.org/?probe=d764d51af9) | Apr 06, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [05e3166f60](https://linux-hardware.org/?probe=05e3166f60) | Apr 06, 2022 |
| Dell          | 0M5DCD A00                  | [209a69c333](https://linux-hardware.org/?probe=209a69c333) | Apr 06, 2022 |
| ASUSTek       | A8N-VM CSM                  | [eac824e348](https://linux-hardware.org/?probe=eac824e348) | Apr 06, 2022 |
| Gigabyte      | X570 AORUS PRO              | [fe22c5530c](https://linux-hardware.org/?probe=fe22c5530c) | Apr 05, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | [f98a0cf73b](https://linux-hardware.org/?probe=f98a0cf73b) | Apr 05, 2022 |
| Dell          | 0T656F A02                  | [260c2183c2](https://linux-hardware.org/?probe=260c2183c2) | Apr 04, 2022 |
| Dell          | 0DR845                      | [26a919fc82](https://linux-hardware.org/?probe=26a919fc82) | Apr 04, 2022 |
| Packard Be... | IMEDIA S2110A               | [b8bf871708](https://linux-hardware.org/?probe=b8bf871708) | Apr 04, 2022 |
| Gigabyte      | Z590 UD AC                  | [ddd9e641ee](https://linux-hardware.org/?probe=ddd9e641ee) | Apr 04, 2022 |
| MSI           | P45 Neo-F                   | [8f1c621674](https://linux-hardware.org/?probe=8f1c621674) | Apr 04, 2022 |
| ASUSTek       | PRIME B250M-K               | [cc6c7d17d9](https://linux-hardware.org/?probe=cc6c7d17d9) | Apr 03, 2022 |
| Packard Be... | Cuba MS-7301                | [1a89e021cd](https://linux-hardware.org/?probe=1a89e021cd) | Apr 03, 2022 |
| Acer          | Aspire X1700                | [dd39a6a660](https://linux-hardware.org/?probe=dd39a6a660) | Apr 03, 2022 |
| Acer          | Predator G3-605             | [7e8eef4976](https://linux-hardware.org/?probe=7e8eef4976) | Apr 03, 2022 |
| HP            | 18E5                        | [3474ce6335](https://linux-hardware.org/?probe=3474ce6335) | Apr 02, 2022 |
| ASRock        | B85M-HDS R2.0               | [9a446ac5fd](https://linux-hardware.org/?probe=9a446ac5fd) | Apr 02, 2022 |
| ASRock        | B560M Pro4                  | [5a4174b74d](https://linux-hardware.org/?probe=5a4174b74d) | Apr 02, 2022 |
| Pegatron      | 2A73h                       | [1aff91c424](https://linux-hardware.org/?probe=1aff91c424) | Apr 02, 2022 |
| Gigabyte      | X570 UD                     | [860fedd7f0](https://linux-hardware.org/?probe=860fedd7f0) | Apr 01, 2022 |
| Dell          | 06JWJY A01                  | [afe97da13d](https://linux-hardware.org/?probe=afe97da13d) | Apr 01, 2022 |
| ASUSTek       | B85M-E                      | [b81a77ca49](https://linux-hardware.org/?probe=b81a77ca49) | Apr 01, 2022 |
| MSI           | B85-G43 GAMING              | [70574c396b](https://linux-hardware.org/?probe=70574c396b) | Mar 31, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [ec4c49e5b2](https://linux-hardware.org/?probe=ec4c49e5b2) | Mar 31, 2022 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [ff4a7768d2](https://linux-hardware.org/?probe=ff4a7768d2) | Mar 31, 2022 |
| ASUSTek       | PRIME Z270-A                | [e8bc504167](https://linux-hardware.org/?probe=e8bc504167) | Mar 30, 2022 |
| ASUSTek       | PRIME X470-PRO              | [3cd8bdb60c](https://linux-hardware.org/?probe=3cd8bdb60c) | Mar 30, 2022 |
| Dell          | 0KV3RP A00                  | [7b36bbe047](https://linux-hardware.org/?probe=7b36bbe047) | Mar 30, 2022 |
| ASUSTek       | NCL-DS                      | [e078564242](https://linux-hardware.org/?probe=e078564242) | Mar 30, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [2491111c9d](https://linux-hardware.org/?probe=2491111c9d) | Mar 30, 2022 |
| Intel         | D33217GKE G76540-203        | [d178add858](https://linux-hardware.org/?probe=d178add858) | Mar 29, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [2955e87822](https://linux-hardware.org/?probe=2955e87822) | Mar 29, 2022 |
| Lenovo        | 0C48431 PRO                 | [5376a37772](https://linux-hardware.org/?probe=5376a37772) | Mar 28, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [3d9b292e29](https://linux-hardware.org/?probe=3d9b292e29) | Mar 28, 2022 |
| Gigabyte      | A520M S2H                   | [eb0a725911](https://linux-hardware.org/?probe=eb0a725911) | Mar 28, 2022 |
| Gigabyte      | F2A78M-HD2                  | [1991a3f990](https://linux-hardware.org/?probe=1991a3f990) | Mar 28, 2022 |
| ASUSTek       | P5Q-PRO                     | [c5d26f3dc7](https://linux-hardware.org/?probe=c5d26f3dc7) | Mar 27, 2022 |
| ASUSTek       | P5Q-PRO                     | [53da8c0cdf](https://linux-hardware.org/?probe=53da8c0cdf) | Mar 27, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [3ed10cce06](https://linux-hardware.org/?probe=3ed10cce06) | Mar 27, 2022 |
| Dell          | 0D24M8 A01                  | [60b0ea7dd1](https://linux-hardware.org/?probe=60b0ea7dd1) | Mar 26, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [90299bc344](https://linux-hardware.org/?probe=90299bc344) | Mar 26, 2022 |
| Alienware     | 0R3FWM A00                  | [46a5c111c3](https://linux-hardware.org/?probe=46a5c111c3) | Mar 25, 2022 |
| Dell          | 0JP3NX A01                  | [60eeaf871f](https://linux-hardware.org/?probe=60eeaf871f) | Mar 25, 2022 |
| ASRock        | N68C-S UCC                  | [da1fd40737](https://linux-hardware.org/?probe=da1fd40737) | Mar 24, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [93014492bd](https://linux-hardware.org/?probe=93014492bd) | Mar 24, 2022 |
| Intel         | DH61BE AAG14062-206         | [08a352b1d2](https://linux-hardware.org/?probe=08a352b1d2) | Mar 24, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [9da89c589d](https://linux-hardware.org/?probe=9da89c589d) | Mar 24, 2022 |
| ASRock        | H110M-HDV R3.0              | [5409f0281e](https://linux-hardware.org/?probe=5409f0281e) | Mar 24, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [f7248b112d](https://linux-hardware.org/?probe=f7248b112d) | Mar 24, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [0e85a5ee68](https://linux-hardware.org/?probe=0e85a5ee68) | Mar 24, 2022 |
| Dell          | 0Y7WYT A00                  | [2376c46c04](https://linux-hardware.org/?probe=2376c46c04) | Mar 23, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [7a02e1b55c](https://linux-hardware.org/?probe=7a02e1b55c) | Mar 22, 2022 |
| ASRock        | X370 Killer SLI             | [8f2239d221](https://linux-hardware.org/?probe=8f2239d221) | Mar 22, 2022 |
| ASUSTek       | A88XM-A                     | [052225ab9a](https://linux-hardware.org/?probe=052225ab9a) | Mar 22, 2022 |
| MSI           | B450M BAZOOKA MAX WIFI      | [747e4d92cf](https://linux-hardware.org/?probe=747e4d92cf) | Mar 21, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [279bb03666](https://linux-hardware.org/?probe=279bb03666) | Mar 21, 2022 |
| ASUSTek       | PRIME Z370-P                | [a5937e694a](https://linux-hardware.org/?probe=a5937e694a) | Mar 20, 2022 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | [8ab51e0212](https://linux-hardware.org/?probe=8ab51e0212) | Mar 20, 2022 |
| MSI           | B560M PRO-VDH               | [b171a344f7](https://linux-hardware.org/?probe=b171a344f7) | Mar 20, 2022 |
| ASRock        | A55M-HVS                    | [b10a9e37bb](https://linux-hardware.org/?probe=b10a9e37bb) | Mar 19, 2022 |
| ASUSTek       | H110I-PLUS                  | [6a83a88b15](https://linux-hardware.org/?probe=6a83a88b15) | Mar 19, 2022 |
| ASUSTek       | P7P55D LE                   | [df99604e73](https://linux-hardware.org/?probe=df99604e73) | Mar 19, 2022 |
| Unknown       | X79-P3                      | [df0d4ee1a9](https://linux-hardware.org/?probe=df0d4ee1a9) | Mar 19, 2022 |
| Unknown       | X79-P3                      | [ab104fe8c0](https://linux-hardware.org/?probe=ab104fe8c0) | Mar 19, 2022 |
| Dell          | 08HPGT A01                  | [30ecdb0b0e](https://linux-hardware.org/?probe=30ecdb0b0e) | Mar 19, 2022 |
| Dell          | 040DDP A01                  | [4cf633a014](https://linux-hardware.org/?probe=4cf633a014) | Mar 18, 2022 |
| HP            | 81B3                        | [1924290221](https://linux-hardware.org/?probe=1924290221) | Mar 17, 2022 |
| Dell          | 06JWJY A01                  | [55cad08f99](https://linux-hardware.org/?probe=55cad08f99) | Mar 17, 2022 |
| MSI           | H110M GAMING                | [d15ac7e6d5](https://linux-hardware.org/?probe=d15ac7e6d5) | Mar 16, 2022 |
| Dell          | 06JWJY A01                  | [562922f633](https://linux-hardware.org/?probe=562922f633) | Mar 15, 2022 |
| MSI           | G31TM-P35                   | [47bfa2ee49](https://linux-hardware.org/?probe=47bfa2ee49) | Mar 14, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [34c10545c2](https://linux-hardware.org/?probe=34c10545c2) | Mar 14, 2022 |
| Dell          | OptiPlex 980                | [14cf2b23f7](https://linux-hardware.org/?probe=14cf2b23f7) | Mar 14, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [b0d2c76aa3](https://linux-hardware.org/?probe=b0d2c76aa3) | Mar 13, 2022 |
| HP            | 2AFB                        | [38a1e87f23](https://linux-hardware.org/?probe=38a1e87f23) | Mar 13, 2022 |
| ASUSTek       | H170M-PLUS                  | [ed2262d433](https://linux-hardware.org/?probe=ed2262d433) | Mar 13, 2022 |
| ASRock        | Q1900M                      | [44eb8c4b87](https://linux-hardware.org/?probe=44eb8c4b87) | Mar 13, 2022 |
| Lenovo        | ThinkCentre M58e 7491B1G    | [4464b6adb3](https://linux-hardware.org/?probe=4464b6adb3) | Mar 13, 2022 |
| Gigabyte      | GA-MA770-UD3                | [7092d99cc8](https://linux-hardware.org/?probe=7092d99cc8) | Mar 13, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [668a2b2bdb](https://linux-hardware.org/?probe=668a2b2bdb) | Mar 13, 2022 |
| ASRock        | B85M-ITX                    | [252e96684a](https://linux-hardware.org/?probe=252e96684a) | Mar 13, 2022 |
| ASUSTek       | SABERTOOTH P67              | [2ee9a56044](https://linux-hardware.org/?probe=2ee9a56044) | Mar 12, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [29a5d5b8f2](https://linux-hardware.org/?probe=29a5d5b8f2) | Mar 12, 2022 |
| Foxconn       | 2AAF                        | [5160788fcc](https://linux-hardware.org/?probe=5160788fcc) | Mar 11, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [32676b1a27](https://linux-hardware.org/?probe=32676b1a27) | Mar 11, 2022 |
| HP            | 1495                        | [65180550c1](https://linux-hardware.org/?probe=65180550c1) | Mar 11, 2022 |
| ASUSTek       | PRIME Z370-P                | [7a11ca484c](https://linux-hardware.org/?probe=7a11ca484c) | Mar 10, 2022 |
| ASRock        | N68C-S UCC                  | [28e6a0766d](https://linux-hardware.org/?probe=28e6a0766d) | Mar 09, 2022 |
| ASRock        | N68C-S UCC                  | [8e6ae6265b](https://linux-hardware.org/?probe=8e6ae6265b) | Mar 09, 2022 |
| ASUSTek       | SABERTOOTH P67              | [8e6dca57f5](https://linux-hardware.org/?probe=8e6dca57f5) | Mar 08, 2022 |
| EVGA          | X58 SLI FTW3 Tylersburg     | [4946a1c5b0](https://linux-hardware.org/?probe=4946a1c5b0) | Mar 07, 2022 |
| EVGA          | X58 SLI FTW3 Tylersburg     | [f68258a39f](https://linux-hardware.org/?probe=f68258a39f) | Mar 07, 2022 |
| ASUSTek       | P5QPL-AM                    | [5c6c47dafa](https://linux-hardware.org/?probe=5c6c47dafa) | Mar 07, 2022 |
| Foxconn       | 2A8C                        | [9bcfd85a21](https://linux-hardware.org/?probe=9bcfd85a21) | Mar 07, 2022 |
| MSI           | B450M MORTAR                | [f0f74fc82a](https://linux-hardware.org/?probe=f0f74fc82a) | Mar 07, 2022 |
| HP            | 1589                        | [88876808e9](https://linux-hardware.org/?probe=88876808e9) | Mar 05, 2022 |
| Dell          | 0G5GJ6 A03                  | [66f88a032f](https://linux-hardware.org/?probe=66f88a032f) | Mar 05, 2022 |
| MSI           | B450M MORTAR                | [1fb41e944f](https://linux-hardware.org/?probe=1fb41e944f) | Mar 05, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | [7e772f422e](https://linux-hardware.org/?probe=7e772f422e) | Mar 05, 2022 |
| Lenovo        | MAHOBAY                     | [b05aa15bb2](https://linux-hardware.org/?probe=b05aa15bb2) | Mar 04, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | [ebcfbc4212](https://linux-hardware.org/?probe=ebcfbc4212) | Mar 04, 2022 |
| HP            | 805D                        | [2a09665009](https://linux-hardware.org/?probe=2a09665009) | Mar 02, 2022 |
| ASUSTek       | PRIME B450M-A               | [eb61ea7985](https://linux-hardware.org/?probe=eb61ea7985) | Mar 02, 2022 |
| HP            | 212B                        | [c183489268](https://linux-hardware.org/?probe=c183489268) | Mar 01, 2022 |
| MSI           | H81M-E34                    | [563e906e47](https://linux-hardware.org/?probe=563e906e47) | Mar 01, 2022 |
| ASRock        | B450M Pro4                  | [469f1aa208](https://linux-hardware.org/?probe=469f1aa208) | Feb 27, 2022 |
| Lenovo        | NO DPK                      | [a720d5bcaf](https://linux-hardware.org/?probe=a720d5bcaf) | Feb 27, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [4f0307c6be](https://linux-hardware.org/?probe=4f0307c6be) | Feb 26, 2022 |
| Foxconn       | 2ADA                        | [fe3763eb05](https://linux-hardware.org/?probe=fe3763eb05) | Feb 26, 2022 |
| Gigabyte      | G41M-ES2H                   | [b3d54bc211](https://linux-hardware.org/?probe=b3d54bc211) | Feb 26, 2022 |
| ASRock        | Z87 Extreme9/ac             | [09664674b6](https://linux-hardware.org/?probe=09664674b6) | Feb 25, 2022 |
| Acer          | Aspire X3990                | [65a154d7fd](https://linux-hardware.org/?probe=65a154d7fd) | Feb 25, 2022 |
| HP            | 3397                        | [96bb93ffa4](https://linux-hardware.org/?probe=96bb93ffa4) | Feb 25, 2022 |
| Gigabyte      | B450M DS3H-CF               | [2ffdc9f169](https://linux-hardware.org/?probe=2ffdc9f169) | Feb 25, 2022 |
| Pegatron      | Narra6                      | [ad9a06f14d](https://linux-hardware.org/?probe=ad9a06f14d) | Feb 25, 2022 |
| MSI           | KA780G                      | [f6bc0eda57](https://linux-hardware.org/?probe=f6bc0eda57) | Feb 25, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [f2a6491fc3](https://linux-hardware.org/?probe=f2a6491fc3) | Feb 24, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [bca185ed94](https://linux-hardware.org/?probe=bca185ed94) | Feb 24, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [69ac34390b](https://linux-hardware.org/?probe=69ac34390b) | Feb 24, 2022 |
| Gigabyte      | H97N-WIFI                   | [06aa2ee2d6](https://linux-hardware.org/?probe=06aa2ee2d6) | Feb 24, 2022 |
| Dell          | 0GDG8Y A00                  | [2d0234e231](https://linux-hardware.org/?probe=2d0234e231) | Feb 24, 2022 |
| MSI           | A320M GAMING PRO            | [9cc531a056](https://linux-hardware.org/?probe=9cc531a056) | Feb 24, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [487957580f](https://linux-hardware.org/?probe=487957580f) | Feb 24, 2022 |
| Unknown       | TB-4000                     | [70155eb876](https://linux-hardware.org/?probe=70155eb876) | Feb 24, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | [544dbac379](https://linux-hardware.org/?probe=544dbac379) | Feb 23, 2022 |
| MSI           | G41M-P25                    | [c8ebea2807](https://linux-hardware.org/?probe=c8ebea2807) | Feb 23, 2022 |
| ASUSTek       | PRIME X570-P                | [9bef02ada7](https://linux-hardware.org/?probe=9bef02ada7) | Feb 22, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [c31bdc38a5](https://linux-hardware.org/?probe=c31bdc38a5) | Feb 22, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [4fb61ea315](https://linux-hardware.org/?probe=4fb61ea315) | Feb 22, 2022 |
| Gigabyte      | Z77-D3H                     | [a0d52488b2](https://linux-hardware.org/?probe=a0d52488b2) | Feb 22, 2022 |
| ASUSTek       | PRIME X570-P                | [177c3db384](https://linux-hardware.org/?probe=177c3db384) | Feb 21, 2022 |
| Gigabyte      | GA-990XA-UD3                | [d24cd3d1e1](https://linux-hardware.org/?probe=d24cd3d1e1) | Feb 21, 2022 |
| MSI           | B450M PRO-VDH MAX           | [f4ded8b967](https://linux-hardware.org/?probe=f4ded8b967) | Feb 20, 2022 |
| Gigabyte      | B360N WIFI-CF               | [6fd8316a53](https://linux-hardware.org/?probe=6fd8316a53) | Feb 20, 2022 |
| ASRock        | X570 Steel Legend           | [c8f8294a07](https://linux-hardware.org/?probe=c8f8294a07) | Feb 20, 2022 |
| Gigabyte      | B460 HD3                    | [ceeb703cf4](https://linux-hardware.org/?probe=ceeb703cf4) | Feb 20, 2022 |
| ASUSTek       | PRIME X370-PRO              | [cd61ef5a5d](https://linux-hardware.org/?probe=cd61ef5a5d) | Feb 20, 2022 |
| ASRock        | M3A UCC                     | [eaa75fb3f4](https://linux-hardware.org/?probe=eaa75fb3f4) | Feb 20, 2022 |
| ASRock        | M3A UCC                     | [ce306a4c86](https://linux-hardware.org/?probe=ce306a4c86) | Feb 20, 2022 |
| MSI           | H61M-P31/W8                 | [d91667374d](https://linux-hardware.org/?probe=d91667374d) | Feb 20, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [c5fc2ff073](https://linux-hardware.org/?probe=c5fc2ff073) | Feb 20, 2022 |
| Intel         | CRESCENTBAY                 | [281c863152](https://linux-hardware.org/?probe=281c863152) | Feb 20, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [090e6be6c1](https://linux-hardware.org/?probe=090e6be6c1) | Feb 19, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [e4f6077e95](https://linux-hardware.org/?probe=e4f6077e95) | Feb 19, 2022 |
| ASUSTek       | Z97-A                       | [f5a62e4392](https://linux-hardware.org/?probe=f5a62e4392) | Feb 19, 2022 |
| Huanan        | X99-F8 V2.0                 | [23c722f6cf](https://linux-hardware.org/?probe=23c722f6cf) | Feb 18, 2022 |
| Lenovo        | ThinkCentre xxx 7090A17     | [f46ff370b9](https://linux-hardware.org/?probe=f46ff370b9) | Feb 17, 2022 |
| Gigabyte      | H81M-HD3                    | [fe34b72551](https://linux-hardware.org/?probe=fe34b72551) | Feb 17, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [740ff0ffcc](https://linux-hardware.org/?probe=740ff0ffcc) | Feb 17, 2022 |
| Huanan        | X99-F8 V2.0                 | [f4fec6a5be](https://linux-hardware.org/?probe=f4fec6a5be) | Feb 17, 2022 |
| Pegatron      | Narra6                      | [712b5069b6](https://linux-hardware.org/?probe=712b5069b6) | Feb 17, 2022 |
| ASUSTek       | PRIME Z590-A                | [6beda6e2da](https://linux-hardware.org/?probe=6beda6e2da) | Feb 16, 2022 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [a74d65bfe6](https://linux-hardware.org/?probe=a74d65bfe6) | Feb 16, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | [9773bc9c72](https://linux-hardware.org/?probe=9773bc9c72) | Feb 16, 2022 |
| ASUSTek       | NCL-DS                      | [6b6f1e1dbd](https://linux-hardware.org/?probe=6b6f1e1dbd) | Feb 16, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [3bdbe20aed](https://linux-hardware.org/?probe=3bdbe20aed) | Feb 16, 2022 |
| MSI           | B450-A PRO MAX              | [538072f18d](https://linux-hardware.org/?probe=538072f18d) | Feb 16, 2022 |
| Gigabyte      | Z690 GAMING X DDR4          | [e91478dbc2](https://linux-hardware.org/?probe=e91478dbc2) | Feb 16, 2022 |
| AZW           | U59                         | [f3eee45bda](https://linux-hardware.org/?probe=f3eee45bda) | Feb 16, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [4bc183685a](https://linux-hardware.org/?probe=4bc183685a) | Feb 16, 2022 |
| Lenovo        | ThinkCentre M58p 7630A38    | [5317cf122d](https://linux-hardware.org/?probe=5317cf122d) | Feb 15, 2022 |
| ASUSTek       | P7H55-M PRO                 | [a3ebde02ae](https://linux-hardware.org/?probe=a3ebde02ae) | Feb 15, 2022 |
| ASRock        | 970M Pro3                   | [9f10f0a7a0](https://linux-hardware.org/?probe=9f10f0a7a0) | Feb 15, 2022 |
| MSI           | MS-7204                     | [5f95f68df7](https://linux-hardware.org/?probe=5f95f68df7) | Feb 15, 2022 |
| MSI           | 970A-G46                    | [36ec26d9e5](https://linux-hardware.org/?probe=36ec26d9e5) | Feb 15, 2022 |
| Dell          | 0JP3NX A01                  | [b7696b0129](https://linux-hardware.org/?probe=b7696b0129) | Feb 14, 2022 |
| Dell          | 0JP3NX A01                  | [504bb820fe](https://linux-hardware.org/?probe=504bb820fe) | Feb 14, 2022 |
| Dell          | 0KWVT8 A03                  | [8112bfd058](https://linux-hardware.org/?probe=8112bfd058) | Feb 14, 2022 |
| ASUSTek       | Z170-A                      | [046f5cdbd7](https://linux-hardware.org/?probe=046f5cdbd7) | Feb 14, 2022 |
| Biostar       | H81MHV3 5.0                 | [c70891d986](https://linux-hardware.org/?probe=c70891d986) | Feb 14, 2022 |
| ASRock        | A320M-HDV R4.0              | [27e20ff1d8](https://linux-hardware.org/?probe=27e20ff1d8) | Feb 14, 2022 |
| Gigabyte      | Z87X-D3H-CF                 | [ba5c642fd0](https://linux-hardware.org/?probe=ba5c642fd0) | Feb 14, 2022 |
| HP            | 1791                        | [2e6f278aca](https://linux-hardware.org/?probe=2e6f278aca) | Feb 14, 2022 |
| ASUSTek       | PRIME Z590-A                | [825734953d](https://linux-hardware.org/?probe=825734953d) | Feb 13, 2022 |
| MSI           | Z97 GAMING 5                | [fa15ba7f8a](https://linux-hardware.org/?probe=fa15ba7f8a) | Feb 13, 2022 |
| MSI           | H61M-E33                    | [86bdb696b0](https://linux-hardware.org/?probe=86bdb696b0) | Feb 13, 2022 |
| HP            | 805D                        | [db88b9cb70](https://linux-hardware.org/?probe=db88b9cb70) | Feb 13, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [d2a90294b3](https://linux-hardware.org/?probe=d2a90294b3) | Feb 13, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [ee8d1e4b48](https://linux-hardware.org/?probe=ee8d1e4b48) | Feb 13, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [7a511b44b6](https://linux-hardware.org/?probe=7a511b44b6) | Feb 12, 2022 |
| MSI           | G31TM-P21                   | [d9dbe1d02f](https://linux-hardware.org/?probe=d9dbe1d02f) | Feb 11, 2022 |
| Gigabyte      | G41M-Combo                  | [a72979e0f8](https://linux-hardware.org/?probe=a72979e0f8) | Feb 11, 2022 |
| Foxconn       | 2A8C                        | [9dc9075c9b](https://linux-hardware.org/?probe=9dc9075c9b) | Feb 11, 2022 |
| ASRock        | H110M-HDV R3.0              | [b18b1304b6](https://linux-hardware.org/?probe=b18b1304b6) | Feb 11, 2022 |
| Gigabyte      | B250M-DS3H-CF               | [41452f28a6](https://linux-hardware.org/?probe=41452f28a6) | Feb 11, 2022 |
| ASUSTek       | P5QC                        | [82f706b315](https://linux-hardware.org/?probe=82f706b315) | Feb 11, 2022 |
| Dell          | 06NWYK A00                  | [a4654ee182](https://linux-hardware.org/?probe=a4654ee182) | Feb 11, 2022 |
| Dell          | 0D24M8 A01                  | [a45da375c0](https://linux-hardware.org/?probe=a45da375c0) | Feb 11, 2022 |
| Unknown       | Unknown                     | [f8ea6734a8](https://linux-hardware.org/?probe=f8ea6734a8) | Feb 11, 2022 |
| Acer          | EG43M                       | [9d294230e4](https://linux-hardware.org/?probe=9d294230e4) | Feb 10, 2022 |
| MSI           | Z370 GAMING PLUS            | [f0de0b509f](https://linux-hardware.org/?probe=f0de0b509f) | Feb 10, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [aaff820712](https://linux-hardware.org/?probe=aaff820712) | Feb 09, 2022 |
| ECS           | Livermore8                  | [e400ebae28](https://linux-hardware.org/?probe=e400ebae28) | Feb 09, 2022 |
| Fujitsu Si... | G31T-M2 V3.02               | [acfc17126b](https://linux-hardware.org/?probe=acfc17126b) | Feb 09, 2022 |
| ASUSTek       | Z170-A                      | [aa66dba98f](https://linux-hardware.org/?probe=aa66dba98f) | Feb 09, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [a752207fe2](https://linux-hardware.org/?probe=a752207fe2) | Feb 09, 2022 |
| MSI           | B450M PRO-VDH MAX           | [c3ad47497a](https://linux-hardware.org/?probe=c3ad47497a) | Feb 09, 2022 |
| HP            | 158B                        | [1884efdb3d](https://linux-hardware.org/?probe=1884efdb3d) | Feb 09, 2022 |
| HP            | 3397                        | [b5bf60705d](https://linux-hardware.org/?probe=b5bf60705d) | Feb 09, 2022 |
| HP            | 8053                        | [d197acb85f](https://linux-hardware.org/?probe=d197acb85f) | Feb 08, 2022 |
| Dell          | 0HX555                      | [f8c149fc7c](https://linux-hardware.org/?probe=f8c149fc7c) | Feb 08, 2022 |
| ASUSTek       | P5W DH Deluxe               | [7c3fa0c43b](https://linux-hardware.org/?probe=7c3fa0c43b) | Feb 08, 2022 |
| Gigabyte      | B365 M AORUS ELITE-CF       | [3c0edffcbd](https://linux-hardware.org/?probe=3c0edffcbd) | Feb 08, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [10fa8a5f53](https://linux-hardware.org/?probe=10fa8a5f53) | Feb 08, 2022 |
| MSI           | B550-A PRO                  | [a7c60ed07d](https://linux-hardware.org/?probe=a7c60ed07d) | Feb 08, 2022 |
| MSI           | Z370 GAMING PLUS            | [08e26250a7](https://linux-hardware.org/?probe=08e26250a7) | Feb 08, 2022 |
| Gigabyte      | H81M-D2V                    | [fb079a5d70](https://linux-hardware.org/?probe=fb079a5d70) | Feb 08, 2022 |
| Gigabyte      | H81M-D2V                    | [99626fa6fd](https://linux-hardware.org/?probe=99626fa6fd) | Feb 08, 2022 |
| ASUSTek       | T-P5G31A                    | [87ad84da68](https://linux-hardware.org/?probe=87ad84da68) | Feb 07, 2022 |
| Dell          | 0K240Y A01                  | [e76acf08bd](https://linux-hardware.org/?probe=e76acf08bd) | Feb 07, 2022 |
| ASRock        | P67 Extreme4 Gen3           | [3a7e065d08](https://linux-hardware.org/?probe=3a7e065d08) | Feb 07, 2022 |
| HP            | 3397                        | [1f567723ba](https://linux-hardware.org/?probe=1f567723ba) | Feb 07, 2022 |
| HP            | 802F                        | [d581c9200c](https://linux-hardware.org/?probe=d581c9200c) | Feb 07, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [0b667cb9f8](https://linux-hardware.org/?probe=0b667cb9f8) | Feb 07, 2022 |
| Lenovo        | 3102 SDK0K13476 WIN 3306... | [10be720f0d](https://linux-hardware.org/?probe=10be720f0d) | Feb 07, 2022 |
| ASUSTek       | Z170-P D3                   | [4146cd6bcb](https://linux-hardware.org/?probe=4146cd6bcb) | Feb 07, 2022 |
| ASRock        | P67 Performance             | [4bed91b4a7](https://linux-hardware.org/?probe=4bed91b4a7) | Feb 07, 2022 |
| ASUSTek       | PRIME B250M-K               | [72f22c503d](https://linux-hardware.org/?probe=72f22c503d) | Feb 07, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [3326f61a1d](https://linux-hardware.org/?probe=3326f61a1d) | Feb 06, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [972365b3d4](https://linux-hardware.org/?probe=972365b3d4) | Feb 06, 2022 |
| HP            | 8053                        | [0327caabc3](https://linux-hardware.org/?probe=0327caabc3) | Feb 06, 2022 |
| MSI           | Z170A XPOWER GAMING TITA... | [f7d707147c](https://linux-hardware.org/?probe=f7d707147c) | Feb 06, 2022 |
| MSI           | B450-A PRO MAX              | [830c0232b6](https://linux-hardware.org/?probe=830c0232b6) | Feb 06, 2022 |
| ASUSTek       | P8Z68-V LX                  | [5f2710fb3a](https://linux-hardware.org/?probe=5f2710fb3a) | Feb 05, 2022 |
| BESSTAR Te... | HM50                        | [4a771cafbd](https://linux-hardware.org/?probe=4a771cafbd) | Feb 05, 2022 |
| Dell          | 0Y2K8N A01                  | [e3922aecf0](https://linux-hardware.org/?probe=e3922aecf0) | Feb 04, 2022 |
| Intel         | DH67VR AAG27177-201         | [554a5bc8bb](https://linux-hardware.org/?probe=554a5bc8bb) | Feb 04, 2022 |
| MSI           | MAG B550M MORTAR            | [06714fad25](https://linux-hardware.org/?probe=06714fad25) | Feb 03, 2022 |
| HP            | 1495                        | [b5cb1ae686](https://linux-hardware.org/?probe=b5cb1ae686) | Feb 03, 2022 |
| MSI           | B450M MORTAR                | [a2fbd7d84e](https://linux-hardware.org/?probe=a2fbd7d84e) | Feb 03, 2022 |
| MSI           | MS-7309                     | [75c2bc30ee](https://linux-hardware.org/?probe=75c2bc30ee) | Feb 03, 2022 |
| Gigabyte      | GB-BRR7H-4800               | [dca1097e4a](https://linux-hardware.org/?probe=dca1097e4a) | Feb 02, 2022 |
| ASUSTek       | Z97-C                       | [160b2468d6](https://linux-hardware.org/?probe=160b2468d6) | Feb 02, 2022 |
| Unknown       | GB01                        | [3b894ab0d8](https://linux-hardware.org/?probe=3b894ab0d8) | Feb 02, 2022 |
| ASRock        | G41M-VS3                    | [825356bf6c](https://linux-hardware.org/?probe=825356bf6c) | Feb 02, 2022 |
| ASUSTek       | Z97-C                       | [b7abddb5e1](https://linux-hardware.org/?probe=b7abddb5e1) | Feb 02, 2022 |
| Dell          | 0Y7WYT A00                  | [f7cf8b586e](https://linux-hardware.org/?probe=f7cf8b586e) | Feb 01, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [d424a8e145](https://linux-hardware.org/?probe=d424a8e145) | Feb 01, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [89dbe92caf](https://linux-hardware.org/?probe=89dbe92caf) | Feb 01, 2022 |
| Dell          | 08K0X7 A00                  | [8a390406ca](https://linux-hardware.org/?probe=8a390406ca) | Feb 01, 2022 |
| HP            | 805D                        | [19295e5827](https://linux-hardware.org/?probe=19295e5827) | Feb 01, 2022 |
| ASUSTek       | H110I-PLUS                  | [ebeaf681e3](https://linux-hardware.org/?probe=ebeaf681e3) | Feb 01, 2022 |
| Intel         | DH67GD AAG10206-208         | [512d94c497](https://linux-hardware.org/?probe=512d94c497) | Jan 31, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [00314992e5](https://linux-hardware.org/?probe=00314992e5) | Jan 31, 2022 |
| HP            | 3031h                       | [6d72e2608a](https://linux-hardware.org/?probe=6d72e2608a) | Jan 31, 2022 |
| HP            | 3031h                       | [dcda450860](https://linux-hardware.org/?probe=dcda450860) | Jan 31, 2022 |
| HP            | 18E7                        | [2e3af3e4c6](https://linux-hardware.org/?probe=2e3af3e4c6) | Jan 31, 2022 |
| Packard Be... | IMEDIA S2291                | [02485b0d91](https://linux-hardware.org/?probe=02485b0d91) | Jan 30, 2022 |
| ASRock        | N68C-S                      | [a53e0201fe](https://linux-hardware.org/?probe=a53e0201fe) | Jan 30, 2022 |
| MSI           | Z97 GAMING 5                | [26005d669e](https://linux-hardware.org/?probe=26005d669e) | Jan 29, 2022 |
| ASUSTek       | T-P5G31A                    | [fb83efdcef](https://linux-hardware.org/?probe=fb83efdcef) | Jan 29, 2022 |
| BESSTAR Te... | HM50                        | [d144b3e6f3](https://linux-hardware.org/?probe=d144b3e6f3) | Jan 29, 2022 |
| ASRock        | FM2A88X+ Killer             | [efc653778b](https://linux-hardware.org/?probe=efc653778b) | Jan 29, 2022 |
| ASUSTek       | Berkeley                    | [a4a0a9e165](https://linux-hardware.org/?probe=a4a0a9e165) | Jan 27, 2022 |
| ASUSTek       | M2R-FVM                     | [17fd122470](https://linux-hardware.org/?probe=17fd122470) | Jan 27, 2022 |
| MSI           | H110M GAMING                | [71c6952d90](https://linux-hardware.org/?probe=71c6952d90) | Jan 27, 2022 |
| Gigabyte      | H81M-DS2                    | [c0328d5402](https://linux-hardware.org/?probe=c0328d5402) | Jan 27, 2022 |
| ASUSTek       | P7P55D-E PRO                | [7daa77d5ba](https://linux-hardware.org/?probe=7daa77d5ba) | Jan 27, 2022 |
| Jetway        | 1.0                         | [49169b21a3](https://linux-hardware.org/?probe=49169b21a3) | Jan 27, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [f867a4e327](https://linux-hardware.org/?probe=f867a4e327) | Jan 26, 2022 |
| Gigabyte      | H61M-DS2                    | [e800b95c58](https://linux-hardware.org/?probe=e800b95c58) | Jan 26, 2022 |
| Medion        | H110H4-CM2                  | [8574d37f58](https://linux-hardware.org/?probe=8574d37f58) | Jan 25, 2022 |
| ASUSTek       | PRIME H310I-PLUS R2.0       | [ab4d7bb5c0](https://linux-hardware.org/?probe=ab4d7bb5c0) | Jan 24, 2022 |
| Dell          | 051FJ8 A00                  | [4248fcfd47](https://linux-hardware.org/?probe=4248fcfd47) | Jan 24, 2022 |
| ASUSTek       | A88XM-E/USB                 | [5133eb5fcd](https://linux-hardware.org/?probe=5133eb5fcd) | Jan 24, 2022 |
| Gigabyte      | A320M-S2H-CF                | [fcde789242](https://linux-hardware.org/?probe=fcde789242) | Jan 24, 2022 |
| Gigabyte      | F2A88XM-HD3P                | [0cd1cb73e3](https://linux-hardware.org/?probe=0cd1cb73e3) | Jan 24, 2022 |
| HP            | 2ADC                        | [39d0f275b9](https://linux-hardware.org/?probe=39d0f275b9) | Jan 23, 2022 |
| ASRock        | B550 Extreme4               | [a6e7a03b85](https://linux-hardware.org/?probe=a6e7a03b85) | Jan 23, 2022 |
| Intel         | DG965MQ AAD37419-302        | [0c7117815f](https://linux-hardware.org/?probe=0c7117815f) | Jan 23, 2022 |
| Online Lab... | SR 42                       | [e3037eb087](https://linux-hardware.org/?probe=e3037eb087) | Jan 22, 2022 |
| Gigabyte      | H310M S2H x.x               | [9e14e04f7f](https://linux-hardware.org/?probe=9e14e04f7f) | Jan 22, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [012cafbe22](https://linux-hardware.org/?probe=012cafbe22) | Jan 22, 2022 |
| ECS           | CDC-I                       | [b37fc67319](https://linux-hardware.org/?probe=b37fc67319) | Jan 22, 2022 |
| ASUSTek       | PRIME B360M-A               | [3825d7e113](https://linux-hardware.org/?probe=3825d7e113) | Jan 22, 2022 |
| ASUSTek       | EB1501P                     | [bd43e4b748](https://linux-hardware.org/?probe=bd43e4b748) | Jan 22, 2022 |
| ASUSTek       | EB1501P                     | [fec419577b](https://linux-hardware.org/?probe=fec419577b) | Jan 22, 2022 |
| Gigabyte      | GB-BRR7H-4800               | [992e0c224c](https://linux-hardware.org/?probe=992e0c224c) | Jan 22, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [52e78b26c2](https://linux-hardware.org/?probe=52e78b26c2) | Jan 21, 2022 |
| ASUSTek       | P8H67-M EVO                 | [515ba182ff](https://linux-hardware.org/?probe=515ba182ff) | Jan 21, 2022 |
| ASUSTek       | M2N-E SLI                   | [bac342fc0f](https://linux-hardware.org/?probe=bac342fc0f) | Jan 21, 2022 |
| ASRock        | N68C-GS FX                  | [7023fd83fc](https://linux-hardware.org/?probe=7023fd83fc) | Jan 21, 2022 |
| Gigabyte      | A320M-S2H-CF                | [dd92029684](https://linux-hardware.org/?probe=dd92029684) | Jan 21, 2022 |
| HP            | 18E7                        | [e2c42c2813](https://linux-hardware.org/?probe=e2c42c2813) | Jan 21, 2022 |
| ASUSTek       | Maximus VI HERO             | [2bdeafa547](https://linux-hardware.org/?probe=2bdeafa547) | Jan 21, 2022 |
| Acer          | WMCP78M                     | [96428e77d6](https://linux-hardware.org/?probe=96428e77d6) | Jan 20, 2022 |
| Lenovo        | ThinkCentre A70 7099A5G     | [db3da2bd92](https://linux-hardware.org/?probe=db3da2bd92) | Jan 20, 2022 |
| HARDKERNEL    | ODROID-H2                   | [8571d32884](https://linux-hardware.org/?probe=8571d32884) | Jan 20, 2022 |
| ASUSTek       | Z97-C                       | [d777f4e71b](https://linux-hardware.org/?probe=d777f4e71b) | Jan 20, 2022 |
| Dell          | 09WH54 A00                  | [7a4a69082a](https://linux-hardware.org/?probe=7a4a69082a) | Jan 19, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [bddb19b4e9](https://linux-hardware.org/?probe=bddb19b4e9) | Jan 19, 2022 |
| MSI           | A68HM-E33 V2                | [c17caa5493](https://linux-hardware.org/?probe=c17caa5493) | Jan 19, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [0fdf95e1d5](https://linux-hardware.org/?probe=0fdf95e1d5) | Jan 18, 2022 |
| Alienware     | 2                           | [e149bdddfa](https://linux-hardware.org/?probe=e149bdddfa) | Jan 18, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [5cccda3e40](https://linux-hardware.org/?probe=5cccda3e40) | Jan 18, 2022 |
| ASRock        | B450M Pro4                  | [556d0fb884](https://linux-hardware.org/?probe=556d0fb884) | Jan 18, 2022 |
| ASRock        | B450M Pro4                  | [5232d69014](https://linux-hardware.org/?probe=5232d69014) | Jan 18, 2022 |
| ASUSTek       | PRIME X470-PRO              | [24fedcca0a](https://linux-hardware.org/?probe=24fedcca0a) | Jan 18, 2022 |
| Gigabyte      | A320MA-M.2-CF               | [3dacdab227](https://linux-hardware.org/?probe=3dacdab227) | Jan 17, 2022 |
| Foxconn       | 2ABF                        | [54a4320a98](https://linux-hardware.org/?probe=54a4320a98) | Jan 16, 2022 |
| ASUSTek       | PRIME B250-PLUS             | [6a024b63f0](https://linux-hardware.org/?probe=6a024b63f0) | Jan 16, 2022 |
| Dell          | 040DDP A01                  | [4eca922a4c](https://linux-hardware.org/?probe=4eca922a4c) | Jan 15, 2022 |
| MSI           | B85I                        | [dc1862e477](https://linux-hardware.org/?probe=dc1862e477) | Jan 15, 2022 |
| ASUSTek       | P5QL PRO                    | [18abe058ad](https://linux-hardware.org/?probe=18abe058ad) | Jan 15, 2022 |
| HP            | 1998                        | [7849d3e43a](https://linux-hardware.org/?probe=7849d3e43a) | Jan 15, 2022 |
| Gigabyte      | B450M DS3H-CF               | [671180553c](https://linux-hardware.org/?probe=671180553c) | Jan 14, 2022 |
| ASUSTek       | PRIME A320M-K               | [d93c0f1e9c](https://linux-hardware.org/?probe=d93c0f1e9c) | Jan 14, 2022 |
| Lenovo        | ThinkCentre A70 7099A5G     | [78902354bb](https://linux-hardware.org/?probe=78902354bb) | Jan 14, 2022 |
| ASUSTek       | Maximus IV GENE-Z           | [e1d5a4a319](https://linux-hardware.org/?probe=e1d5a4a319) | Jan 14, 2022 |
| ASUSTek       | G20AJ                       | [2289107616](https://linux-hardware.org/?probe=2289107616) | Jan 14, 2022 |
| MSI           | MS-7255                     | [bf4604061a](https://linux-hardware.org/?probe=bf4604061a) | Jan 14, 2022 |
| ASUSTek       | Z97-AR                      | [3ed202b80d](https://linux-hardware.org/?probe=3ed202b80d) | Jan 13, 2022 |
| Dell          | 0KWVT8 A00                  | [c4a3e67da7](https://linux-hardware.org/?probe=c4a3e67da7) | Jan 13, 2022 |
| Dell          | 0TT708 A01                  | [805a0e93cb](https://linux-hardware.org/?probe=805a0e93cb) | Jan 13, 2022 |
| MSI           | GF615M-P33                  | [b214018b58](https://linux-hardware.org/?probe=b214018b58) | Jan 12, 2022 |
| Lenovo        | ThinkCentre M58e 7491B1G    | [568741947f](https://linux-hardware.org/?probe=568741947f) | Jan 12, 2022 |
| MSI           | B350M PRO-VDH               | [29b6159e9c](https://linux-hardware.org/?probe=29b6159e9c) | Jan 12, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [1bc317c3e4](https://linux-hardware.org/?probe=1bc317c3e4) | Jan 12, 2022 |
| ASRock        | Z77 Pro3                    | [fd49163d5c](https://linux-hardware.org/?probe=fd49163d5c) | Jan 12, 2022 |
| Gigabyte      | A320M-S2H-CF                | [4c24369bb7](https://linux-hardware.org/?probe=4c24369bb7) | Jan 11, 2022 |
| ASUSTek       | M4A88T-M/USB3               | [14d1da1771](https://linux-hardware.org/?probe=14d1da1771) | Jan 11, 2022 |
| Intel         | DQ77KB AAG81483-500         | [86eec4d66c](https://linux-hardware.org/?probe=86eec4d66c) | Jan 11, 2022 |
| Intel         | DQ77KB AAG81483-500         | [ee451ffe45](https://linux-hardware.org/?probe=ee451ffe45) | Jan 11, 2022 |
| Dell          | 048DY8 A01                  | [a7e349dead](https://linux-hardware.org/?probe=a7e349dead) | Jan 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c973caf482](https://linux-hardware.org/?probe=c973caf482) | Jan 10, 2022 |
| ASUSTek       | H81-GAMER                   | [e123597c40](https://linux-hardware.org/?probe=e123597c40) | Jan 09, 2022 |
| HP            | 18E7                        | [0a1687e6fa](https://linux-hardware.org/?probe=0a1687e6fa) | Jan 09, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [7f94c66f93](https://linux-hardware.org/?probe=7f94c66f93) | Jan 09, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [02fe041d02](https://linux-hardware.org/?probe=02fe041d02) | Jan 09, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [1cbc81e5c2](https://linux-hardware.org/?probe=1cbc81e5c2) | Jan 09, 2022 |
| Lenovo        | ThinkCentre M58e 7491B1G    | [a77218c72c](https://linux-hardware.org/?probe=a77218c72c) | Jan 09, 2022 |
| MSI           | B450M BAZOOKA MAX WIFI      | [6cb48fa647](https://linux-hardware.org/?probe=6cb48fa647) | Jan 08, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [c290fc6fc3](https://linux-hardware.org/?probe=c290fc6fc3) | Jan 08, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [8875c8251a](https://linux-hardware.org/?probe=8875c8251a) | Jan 08, 2022 |
| MSI           | Z170A GAMING M3             | [19ec6b28dd](https://linux-hardware.org/?probe=19ec6b28dd) | Jan 07, 2022 |
| ASUSTek       | ROG STRIX Z490-I GAMING     | [c3a0a425f9](https://linux-hardware.org/?probe=c3a0a425f9) | Jan 07, 2022 |
| ASUSTek       | ROG STRIX Z490-I GAMING     | [ea4bdf8279](https://linux-hardware.org/?probe=ea4bdf8279) | Jan 06, 2022 |
| HP            | 18E7                        | [b9844ec9ca](https://linux-hardware.org/?probe=b9844ec9ca) | Jan 06, 2022 |
| Gigabyte      | M57SLI-S4                   | [ec63d82626](https://linux-hardware.org/?probe=ec63d82626) | Jan 05, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [7a0e13a7c1](https://linux-hardware.org/?probe=7a0e13a7c1) | Jan 05, 2022 |
| MSI           | B550M-A PRO                 | [40770f71e7](https://linux-hardware.org/?probe=40770f71e7) | Jan 05, 2022 |
| HP            | 1791                        | [74122badef](https://linux-hardware.org/?probe=74122badef) | Jan 04, 2022 |
| Intel         | DG965MQ AAD37419-302        | [1792f6a645](https://linux-hardware.org/?probe=1792f6a645) | Jan 04, 2022 |
| Dell          | 0MWYPT A01                  | [59421d72cc](https://linux-hardware.org/?probe=59421d72cc) | Jan 03, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [608b8edfd4](https://linux-hardware.org/?probe=608b8edfd4) | Jan 03, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [157c5615eb](https://linux-hardware.org/?probe=157c5615eb) | Jan 03, 2022 |
| ASUSTek       | P5Q-PRO                     | [960b50cf61](https://linux-hardware.org/?probe=960b50cf61) | Jan 03, 2022 |
| ASUSTek       | Z97-C                       | [acdca2de8b](https://linux-hardware.org/?probe=acdca2de8b) | Jan 03, 2022 |
| ASUSTek       | PRIME A320M-K               | [9d1d46c08a](https://linux-hardware.org/?probe=9d1d46c08a) | Jan 02, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [8de00c21aa](https://linux-hardware.org/?probe=8de00c21aa) | Jan 01, 2022 |
| ASRock        | 870iCafe R2.0               | [f67cc91b2e](https://linux-hardware.org/?probe=f67cc91b2e) | Dec 31, 2021 |
| ASUSTek       | P5K-E                       | [f1c3532217](https://linux-hardware.org/?probe=f1c3532217) | Dec 31, 2021 |
| Pegatron      | E66                         | [6646bf482c](https://linux-hardware.org/?probe=6646bf482c) | Dec 31, 2021 |
| ASUSTek       | STRIX X99 GAMING            | [f7f99c478d](https://linux-hardware.org/?probe=f7f99c478d) | Dec 31, 2021 |
| ASUSTek       | PRIME B450M-A               | [58cb628601](https://linux-hardware.org/?probe=58cb628601) | Dec 31, 2021 |
| HP            | 1589                        | [d123a8de64](https://linux-hardware.org/?probe=d123a8de64) | Dec 30, 2021 |
| ASUSTek       | PRIME Z690-P WIFI           | [428d5b007d](https://linux-hardware.org/?probe=428d5b007d) | Dec 30, 2021 |
| Pegatron      | 2A73                        | [7bd7b908f5](https://linux-hardware.org/?probe=7bd7b908f5) | Dec 29, 2021 |
| MSI           | P45 Neo-F                   | [438c7c7ab9](https://linux-hardware.org/?probe=438c7c7ab9) | Dec 27, 2021 |
| Packard Be... | MCP73VT-PM                  | [c4f47dca10](https://linux-hardware.org/?probe=c4f47dca10) | Dec 27, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [f9a93f6a5e](https://linux-hardware.org/?probe=f9a93f6a5e) | Dec 27, 2021 |
| ASUSTek       | M3N78-EMH HDMI              | [9c23b50b11](https://linux-hardware.org/?probe=9c23b50b11) | Dec 26, 2021 |
| Gigabyte      | H67MA-UD2H-B3               | [e32af6a3de](https://linux-hardware.org/?probe=e32af6a3de) | Dec 26, 2021 |
| MSI           | Z170A GAMING M3             | [44aaf06363](https://linux-hardware.org/?probe=44aaf06363) | Dec 26, 2021 |
| ASRock        | Z690M-ITX/ax                | [0a35834719](https://linux-hardware.org/?probe=0a35834719) | Dec 26, 2021 |
| Lenovo        | SHARKBAY NOK                | [2a7c56982c](https://linux-hardware.org/?probe=2a7c56982c) | Dec 26, 2021 |
| ASRock        | Z690M-ITX/ax                | [fcc19136e0](https://linux-hardware.org/?probe=fcc19136e0) | Dec 26, 2021 |
| JGINYUE       | X99-D8 Server V1.0          | [d1548e5cd1](https://linux-hardware.org/?probe=d1548e5cd1) | Dec 25, 2021 |
| MSI           | MS-7255                     | [8bb001fa61](https://linux-hardware.org/?probe=8bb001fa61) | Dec 25, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [6c2dae2ca3](https://linux-hardware.org/?probe=6c2dae2ca3) | Dec 25, 2021 |
| Gigabyte      | B150M-HD3-CF                | [1f8dbcbdc7](https://linux-hardware.org/?probe=1f8dbcbdc7) | Dec 24, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [1e9acda341](https://linux-hardware.org/?probe=1e9acda341) | Dec 24, 2021 |
| Gigabyte      | B150M-HD3-CF                | [8b9eeb5990](https://linux-hardware.org/?probe=8b9eeb5990) | Dec 24, 2021 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [26b64d67a9](https://linux-hardware.org/?probe=26b64d67a9) | Dec 24, 2021 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [04bcdd10e9](https://linux-hardware.org/?probe=04bcdd10e9) | Dec 24, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [adf33163a2](https://linux-hardware.org/?probe=adf33163a2) | Dec 24, 2021 |
| ASUSTek       | A8N5X                       | [4786d6b56c](https://linux-hardware.org/?probe=4786d6b56c) | Dec 24, 2021 |
| Packard Be... | IXTREME M5850               | [27a73b1bee](https://linux-hardware.org/?probe=27a73b1bee) | Dec 23, 2021 |
| MSI           | Z590-A PRO                  | [4b20c43b53](https://linux-hardware.org/?probe=4b20c43b53) | Dec 22, 2021 |
| Intel         | DH67BL AAG10189-213         | [5fa9087a0f](https://linux-hardware.org/?probe=5fa9087a0f) | Dec 22, 2021 |
| HP            | 2B47                        | [64a4b36df8](https://linux-hardware.org/?probe=64a4b36df8) | Dec 22, 2021 |
| MSI           | P67A-GD65                   | [125fa6f8fe](https://linux-hardware.org/?probe=125fa6f8fe) | Dec 22, 2021 |
| ASUSTek       | H81M-C                      | [f0e03ffaed](https://linux-hardware.org/?probe=f0e03ffaed) | Dec 22, 2021 |
| ASUSTek       | F1A75-V EVO                 | [fa17fae5a5](https://linux-hardware.org/?probe=fa17fae5a5) | Dec 22, 2021 |
| ASUSTek       | PRIME Z590-A                | [7d5af78d9b](https://linux-hardware.org/?probe=7d5af78d9b) | Dec 21, 2021 |
| ASUSTek       | Z97-A                       | [1d27772094](https://linux-hardware.org/?probe=1d27772094) | Dec 21, 2021 |
| Gigabyte      | B150M-D3H-CF                | [22f2f5c84b](https://linux-hardware.org/?probe=22f2f5c84b) | Dec 21, 2021 |
| ASUSTek       | ROG ZENITH EXTREME          | [e3d82aebbe](https://linux-hardware.org/?probe=e3d82aebbe) | Dec 20, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | [9813973b1b](https://linux-hardware.org/?probe=9813973b1b) | Dec 20, 2021 |
| Dell          | 0NDYHG A01                  | [093e7e5784](https://linux-hardware.org/?probe=093e7e5784) | Dec 20, 2021 |
| ASUSTek       | PRIME Z390-P                | [499419ee06](https://linux-hardware.org/?probe=499419ee06) | Dec 20, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | [32340d057e](https://linux-hardware.org/?probe=32340d057e) | Dec 20, 2021 |
| Gigabyte      | H110M-S2H-CF                | [c64c369808](https://linux-hardware.org/?probe=c64c369808) | Dec 19, 2021 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [f86ed2049c](https://linux-hardware.org/?probe=f86ed2049c) | Dec 19, 2021 |
| MSI           | MPG Z490 GAMING PLUS        | [2089bb7833](https://linux-hardware.org/?probe=2089bb7833) | Dec 19, 2021 |
| MSI           | 2A9C                        | [0e6220a2e6](https://linux-hardware.org/?probe=0e6220a2e6) | Dec 18, 2021 |
| Gigabyte      | H370 HD3-CF                 | [2497b24eda](https://linux-hardware.org/?probe=2497b24eda) | Dec 18, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [ac70723f1b](https://linux-hardware.org/?probe=ac70723f1b) | Dec 18, 2021 |
| Lenovo        | ThinkCentre M57e 9489W1U    | [ba5156ef68](https://linux-hardware.org/?probe=ba5156ef68) | Dec 17, 2021 |
| ASUSTek       | P8H61-M LE                  | [b8be0cdaef](https://linux-hardware.org/?probe=b8be0cdaef) | Dec 17, 2021 |
| HP            | 0A00h                       | [56585a2839](https://linux-hardware.org/?probe=56585a2839) | Dec 17, 2021 |
| MSI           | MPG Z490 GAMING PLUS        | [e498196491](https://linux-hardware.org/?probe=e498196491) | Dec 16, 2021 |
| MSI           | 2AE0                        | [f40b9dbbbe](https://linux-hardware.org/?probe=f40b9dbbbe) | Dec 16, 2021 |
| Dell          | 0Y2MRG A00                  | [dfb598a85c](https://linux-hardware.org/?probe=dfb598a85c) | Dec 16, 2021 |
| HP            | 18E7                        | [c600f1f2bb](https://linux-hardware.org/?probe=c600f1f2bb) | Dec 15, 2021 |
| ASUSTek       | H81-GAMER                   | [74658e6a83](https://linux-hardware.org/?probe=74658e6a83) | Dec 15, 2021 |
| ASUSTek       | Q170M2                      | [83811b886e](https://linux-hardware.org/?probe=83811b886e) | Dec 15, 2021 |
| Unknown       | CN700-8237                  | [c55be123a1](https://linux-hardware.org/?probe=c55be123a1) | Dec 15, 2021 |
| Acer          | Aspire XC-704               | [598246c9fd](https://linux-hardware.org/?probe=598246c9fd) | Dec 15, 2021 |
| ASUSTek       | P8B75-M LX                  | [4575aea29e](https://linux-hardware.org/?probe=4575aea29e) | Dec 14, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [705efd4d1a](https://linux-hardware.org/?probe=705efd4d1a) | Dec 14, 2021 |
| ASUSTek       | STRIX Z270E GAMING          | [a3dd0b366d](https://linux-hardware.org/?probe=a3dd0b366d) | Dec 13, 2021 |
| ASUSTek       | PRIME H410M-A               | [fb0903d979](https://linux-hardware.org/?probe=fb0903d979) | Dec 13, 2021 |
| Dell          | 0T656F A02                  | [c6fcad51e9](https://linux-hardware.org/?probe=c6fcad51e9) | Dec 13, 2021 |
| ASRock        | B560M Pro4                  | [f03914de42](https://linux-hardware.org/?probe=f03914de42) | Dec 13, 2021 |
| ASUSTek       | PRIME B360M-K               | [abb6a94373](https://linux-hardware.org/?probe=abb6a94373) | Dec 12, 2021 |
| ASRock        | H310M-STX                   | [96a7160cee](https://linux-hardware.org/?probe=96a7160cee) | Dec 11, 2021 |
| ASRock        | H310M-STX                   | [f40860a3ed](https://linux-hardware.org/?probe=f40860a3ed) | Dec 11, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [9c363da2d7](https://linux-hardware.org/?probe=9c363da2d7) | Dec 11, 2021 |
| ASUSTek       | M5A78L-M LX3                | [92d870bb08](https://linux-hardware.org/?probe=92d870bb08) | Dec 11, 2021 |
| Gigabyte      | AB350-Gaming-CF             | [4b61220ac3](https://linux-hardware.org/?probe=4b61220ac3) | Dec 11, 2021 |
| ASUSTek       | H81M-PLUS                   | [7ffe169cf9](https://linux-hardware.org/?probe=7ffe169cf9) | Dec 10, 2021 |
| HP            | 3048h                       | [b583a7dd31](https://linux-hardware.org/?probe=b583a7dd31) | Dec 09, 2021 |
| MSI           | Z87-G45 GAMING              | [1a012f2f1f](https://linux-hardware.org/?probe=1a012f2f1f) | Dec 09, 2021 |
| ASRock        | B560M Pro4                  | [ca363e419b](https://linux-hardware.org/?probe=ca363e419b) | Dec 09, 2021 |
| MSI           | 970 GAMING                  | [1a5b0a8d39](https://linux-hardware.org/?probe=1a5b0a8d39) | Dec 09, 2021 |
| MSI           | 970 GAMING                  | [f4d8f580dc](https://linux-hardware.org/?probe=f4d8f580dc) | Dec 09, 2021 |
| Gigabyte      | 945GCM-S2L                  | [a253c74be5](https://linux-hardware.org/?probe=a253c74be5) | Dec 08, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [d16919abc9](https://linux-hardware.org/?probe=d16919abc9) | Dec 08, 2021 |
| Acer          | M945G                       | [5c72066083](https://linux-hardware.org/?probe=5c72066083) | Dec 08, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | [0bd9e5cc80](https://linux-hardware.org/?probe=0bd9e5cc80) | Dec 08, 2021 |
| Dell          | 0HGFJM A00                  | [db1f27a7c7](https://linux-hardware.org/?probe=db1f27a7c7) | Dec 08, 2021 |
| Dell          | 0HGFJM A00                  | [1a392b6f38](https://linux-hardware.org/?probe=1a392b6f38) | Dec 08, 2021 |
| ECS           | Nettle2                     | [bb67b27e67](https://linux-hardware.org/?probe=bb67b27e67) | Dec 07, 2021 |
| ASRock        | Z370M Pro4                  | [ade1f1db1a](https://linux-hardware.org/?probe=ade1f1db1a) | Dec 07, 2021 |
| ASUSTek       | P5Q-PRO                     | [b31cb16e0b](https://linux-hardware.org/?probe=b31cb16e0b) | Dec 07, 2021 |
| Apple         | Mac-F221BEC8                | [94181f0230](https://linux-hardware.org/?probe=94181f0230) | Dec 07, 2021 |
| ASUSTek       | P5Q-PRO                     | [873bcda612](https://linux-hardware.org/?probe=873bcda612) | Dec 06, 2021 |
| Foxconn       | 2AAF                        | [db9d51686c](https://linux-hardware.org/?probe=db9d51686c) | Dec 06, 2021 |
| Gigabyte      | Z390 AORUS PRO-CF           | [a323c197dc](https://linux-hardware.org/?probe=a323c197dc) | Dec 05, 2021 |
| HP            | 1587h                       | [aaa0c74349](https://linux-hardware.org/?probe=aaa0c74349) | Dec 04, 2021 |
| ASUSTek       | M2N68-AM Plus               | [e9b454a745](https://linux-hardware.org/?probe=e9b454a745) | Dec 04, 2021 |
| Packard Be... | PT890-8237A                 | [47f9bd515f](https://linux-hardware.org/?probe=47f9bd515f) | Dec 04, 2021 |
| Packard Be... | PT890-8237A                 | [300819afb3](https://linux-hardware.org/?probe=300819afb3) | Dec 04, 2021 |
| Dell          | 0G254H A00                  | [11897b38da](https://linux-hardware.org/?probe=11897b38da) | Dec 03, 2021 |
| Gigabyte      | Z590 VISION G               | [51e33fc095](https://linux-hardware.org/?probe=51e33fc095) | Dec 03, 2021 |
| Dell          | 09WH54 A00                  | [27eb39e7f9](https://linux-hardware.org/?probe=27eb39e7f9) | Dec 03, 2021 |
| Acer          | F672CR R01-A4               | [ee1bc7199e](https://linux-hardware.org/?probe=ee1bc7199e) | Dec 03, 2021 |
| MSI           | B450M-A PRO MAX             | [17a6983b50](https://linux-hardware.org/?probe=17a6983b50) | Dec 03, 2021 |
| ASUSTek       | M2N68-AM Plus               | [b096d0494e](https://linux-hardware.org/?probe=b096d0494e) | Dec 02, 2021 |
| Huanan        | X99-F8 V2.0                 | [039bbca776](https://linux-hardware.org/?probe=039bbca776) | Dec 02, 2021 |
| ASUSTek       | A55BM-E                     | [9596c8e51d](https://linux-hardware.org/?probe=9596c8e51d) | Dec 02, 2021 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | [859bf9eacb](https://linux-hardware.org/?probe=859bf9eacb) | Dec 02, 2021 |
| ASUSTek       | H81M-A                      | [50acb69e6e](https://linux-hardware.org/?probe=50acb69e6e) | Dec 02, 2021 |
| ASUSTek       | P8Z77-V LX                  | [c9ed75dd92](https://linux-hardware.org/?probe=c9ed75dd92) | Dec 02, 2021 |
| MSI           | B550M-A PRO                 | [052c17dd21](https://linux-hardware.org/?probe=052c17dd21) | Dec 01, 2021 |
| Gigabyte      | B75-D3V                     | [c6885625b9](https://linux-hardware.org/?probe=c6885625b9) | Dec 01, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [0a3e70b938](https://linux-hardware.org/?probe=0a3e70b938) | Dec 01, 2021 |
| Dell          | 0RY007                      | [814e4720d3](https://linux-hardware.org/?probe=814e4720d3) | Nov 30, 2021 |
| ASUSTek       | M2N                         | [8f674fd086](https://linux-hardware.org/?probe=8f674fd086) | Nov 30, 2021 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | [cab4a8d09e](https://linux-hardware.org/?probe=cab4a8d09e) | Nov 30, 2021 |
| ASUSTek       | H81M-PLUS                   | [6d6caad964](https://linux-hardware.org/?probe=6d6caad964) | Nov 29, 2021 |
| ASUSTek       | Z10PE-D16 WS                | [3188aa78c9](https://linux-hardware.org/?probe=3188aa78c9) | Nov 29, 2021 |
| ASUSTek       | P8P67 PRO                   | [c3b84208ce](https://linux-hardware.org/?probe=c3b84208ce) | Nov 29, 2021 |
| ASRock        | FM2A78M-DG3+                | [72dfdf487b](https://linux-hardware.org/?probe=72dfdf487b) | Nov 29, 2021 |
| Pegatron      | 2A99                        | [dcbf9d1032](https://linux-hardware.org/?probe=dcbf9d1032) | Nov 28, 2021 |
| Intel         | X79G V2.x                   | [a04ccc0b10](https://linux-hardware.org/?probe=a04ccc0b10) | Nov 28, 2021 |
| MSI           | P45 Neo-F                   | [8e6e31f42c](https://linux-hardware.org/?probe=8e6e31f42c) | Nov 28, 2021 |
| Pegatron      | 2A99                        | [bae15d38f8](https://linux-hardware.org/?probe=bae15d38f8) | Nov 28, 2021 |
| ASUSTek       | P8Z77-V LX                  | [d47afa3352](https://linux-hardware.org/?probe=d47afa3352) | Nov 27, 2021 |
| ASUSTek       | M3A32-MVP DELUXE            | [2b259d6d47](https://linux-hardware.org/?probe=2b259d6d47) | Nov 27, 2021 |
| ASUSTek       | P8H67-M PRO                 | [5c3b79adb4](https://linux-hardware.org/?probe=5c3b79adb4) | Nov 27, 2021 |
| ASUSTek       | P8H67-M PRO                 | [691afaf7d0](https://linux-hardware.org/?probe=691afaf7d0) | Nov 27, 2021 |
| MSI           | MPG Z490 GAMING PLUS        | [46a63cf369](https://linux-hardware.org/?probe=46a63cf369) | Nov 27, 2021 |
| MSI           | MPG Z490 GAMING PLUS        | [d8109a1195](https://linux-hardware.org/?probe=d8109a1195) | Nov 27, 2021 |
| Dell          | 0M5DCD A00                  | [53441b22f8](https://linux-hardware.org/?probe=53441b22f8) | Nov 27, 2021 |
| ASUSTek       | P8Z77-V                     | [9ceba48554](https://linux-hardware.org/?probe=9ceba48554) | Nov 26, 2021 |
| ASUSTek       | P8Z77-V                     | [a8c5a39f21](https://linux-hardware.org/?probe=a8c5a39f21) | Nov 26, 2021 |
| Gigabyte      | GA-990FXA-UD3               | [20e8f6655f](https://linux-hardware.org/?probe=20e8f6655f) | Nov 26, 2021 |
| MSI           | H81M-P33                    | [3d2583b1f1](https://linux-hardware.org/?probe=3d2583b1f1) | Nov 26, 2021 |
| HP            | 3646h                       | [096733a0fa](https://linux-hardware.org/?probe=096733a0fa) | Nov 25, 2021 |
| ASUSTek       | PRIME Z390-P                | [457371fa9a](https://linux-hardware.org/?probe=457371fa9a) | Nov 25, 2021 |
| HP            | 3646h                       | [36b1e0c879](https://linux-hardware.org/?probe=36b1e0c879) | Nov 25, 2021 |
| ASUSTek       | PRIME B360-PLUS             | [515b608f63](https://linux-hardware.org/?probe=515b608f63) | Nov 25, 2021 |
| Dell          | 0G254H A00                  | [2e6c744703](https://linux-hardware.org/?probe=2e6c744703) | Nov 24, 2021 |
| Fujitsu       | D2990-A1 S26361-D2990-A1    | [2ebf5505af](https://linux-hardware.org/?probe=2ebf5505af) | Nov 24, 2021 |
| Gigabyte      | H87N-WIFI                   | [90c2875d6d](https://linux-hardware.org/?probe=90c2875d6d) | Nov 24, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | [148f8b6de1](https://linux-hardware.org/?probe=148f8b6de1) | Nov 24, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | [021d70dbf2](https://linux-hardware.org/?probe=021d70dbf2) | Nov 24, 2021 |
| ASUSTek       | P8P67 DELUXE                | [f3453925e5](https://linux-hardware.org/?probe=f3453925e5) | Nov 23, 2021 |
| ASUSTek       | Z97-A                       | [856ecc2b70](https://linux-hardware.org/?probe=856ecc2b70) | Nov 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | [f5cadf9b2e](https://linux-hardware.org/?probe=f5cadf9b2e) | Nov 23, 2021 |
| ASUSTek       | PRIME B365M-K               | [523372b197](https://linux-hardware.org/?probe=523372b197) | Nov 23, 2021 |
| MSI           | MS-7030                     | [dc2b0207b3](https://linux-hardware.org/?probe=dc2b0207b3) | Nov 23, 2021 |
| Gigabyte      | H61N-USB3                   | [83e388363c](https://linux-hardware.org/?probe=83e388363c) | Nov 23, 2021 |
| ASRock        | FM2A88X+ Killer             | [2b2b399b41](https://linux-hardware.org/?probe=2b2b399b41) | Nov 23, 2021 |
| Dell          | 0PC5F7 A03                  | [5ee25c6894](https://linux-hardware.org/?probe=5ee25c6894) | Nov 23, 2021 |
| Dell          | 0PC5F7 A03                  | [7995f7e3a8](https://linux-hardware.org/?probe=7995f7e3a8) | Nov 23, 2021 |
| Dell          | 0TP412                      | [f759f2084b](https://linux-hardware.org/?probe=f759f2084b) | Nov 22, 2021 |
| ASRock        | FM2A78M-HD+ R2.0            | [a518c0d17a](https://linux-hardware.org/?probe=a518c0d17a) | Nov 21, 2021 |
| ASUSTek       | ROG STRIX B460-F GAMING     | [c10736a15e](https://linux-hardware.org/?probe=c10736a15e) | Nov 21, 2021 |
| Dell          | 0TP412                      | [a162484e1f](https://linux-hardware.org/?probe=a162484e1f) | Nov 21, 2021 |
| Unknown       | Intel X79                   | [b272698078](https://linux-hardware.org/?probe=b272698078) | Nov 21, 2021 |
| Gigabyte      | B450M GAMING                | [2355c29da1](https://linux-hardware.org/?probe=2355c29da1) | Nov 21, 2021 |
| ASUSTek       | PRIME B360-PLUS             | [8c90375658](https://linux-hardware.org/?probe=8c90375658) | Nov 20, 2021 |
| Dell          | 014GRG A02                  | [c23455dd49](https://linux-hardware.org/?probe=c23455dd49) | Nov 20, 2021 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | [a13103a9ad](https://linux-hardware.org/?probe=a13103a9ad) | Nov 20, 2021 |
| MSI           | B360 GAMING PLUS            | [abb51a9107](https://linux-hardware.org/?probe=abb51a9107) | Nov 20, 2021 |
| ASUSTek       | PRIME B360-PLUS             | [a385b829b0](https://linux-hardware.org/?probe=a385b829b0) | Nov 20, 2021 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [bd795eb1c2](https://linux-hardware.org/?probe=bd795eb1c2) | Nov 19, 2021 |
| Dell          | 0R230R A00                  | [ed396bc8af](https://linux-hardware.org/?probe=ed396bc8af) | Nov 19, 2021 |
| Gigabyte      | B85M-D3H                    | [7119b7f25b](https://linux-hardware.org/?probe=7119b7f25b) | Nov 19, 2021 |
| ASUSTek       | Z97M-PLUS                   | [b63110a5f3](https://linux-hardware.org/?probe=b63110a5f3) | Nov 19, 2021 |
| ECS           | H81H3-M3                    | [019a8bc90a](https://linux-hardware.org/?probe=019a8bc90a) | Nov 19, 2021 |
| OEM           | Unknown                     | [fe641f4c72](https://linux-hardware.org/?probe=fe641f4c72) | Nov 19, 2021 |
| OEM           | Unknown                     | [793c116a8d](https://linux-hardware.org/?probe=793c116a8d) | Nov 19, 2021 |
| HP            | 82F2                        | [864b1b1731](https://linux-hardware.org/?probe=864b1b1731) | Nov 18, 2021 |
| ASUSTek       | Z87-A                       | [906510b2cd](https://linux-hardware.org/?probe=906510b2cd) | Nov 18, 2021 |
| ASUSTek       | ROG STRIX B460-F GAMING     | [483c332cbf](https://linux-hardware.org/?probe=483c332cbf) | Nov 18, 2021 |
| HP            | 3397                        | [7a9bd82ef2](https://linux-hardware.org/?probe=7a9bd82ef2) | Nov 18, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2dc50bf90a](https://linux-hardware.org/?probe=2dc50bf90a) | Nov 18, 2021 |
| HP            | 8599                        | [4103117abb](https://linux-hardware.org/?probe=4103117abb) | Nov 18, 2021 |
| Intel         | DQ45CB AAE30148-207         | [37c8f0eb6b](https://linux-hardware.org/?probe=37c8f0eb6b) | Nov 18, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [589cb14b9f](https://linux-hardware.org/?probe=589cb14b9f) | Nov 18, 2021 |
| Unknown       | Unknown                     | [f6332ae0c5](https://linux-hardware.org/?probe=f6332ae0c5) | Nov 17, 2021 |
| MSI           | Z97-G45 GAMING              | [fc7a1caa36](https://linux-hardware.org/?probe=fc7a1caa36) | Nov 17, 2021 |
| ASRock        | X470 Master SLI             | [c48f95d233](https://linux-hardware.org/?probe=c48f95d233) | Nov 17, 2021 |
| ASUSTek       | Z87-A                       | [6f2c01d947](https://linux-hardware.org/?probe=6f2c01d947) | Nov 16, 2021 |
| ASUSTek       | H97-PLUS                    | [ed3c10b44f](https://linux-hardware.org/?probe=ed3c10b44f) | Nov 16, 2021 |
| ASUSTek       | X99-E                       | [c8deed9ea3](https://linux-hardware.org/?probe=c8deed9ea3) | Nov 16, 2021 |
| MSI           | MPG B550 GAMING PLUS        | [e4375ff53a](https://linux-hardware.org/?probe=e4375ff53a) | Nov 16, 2021 |
| MSI           | MPG B550 GAMING PLUS        | [b8aa4af077](https://linux-hardware.org/?probe=b8aa4af077) | Nov 16, 2021 |
| ASUSTek       | P5Q                         | [f544ee5b12](https://linux-hardware.org/?probe=f544ee5b12) | Nov 16, 2021 |
| Gigabyte      | H87N-WIFI                   | [cc51562a6c](https://linux-hardware.org/?probe=cc51562a6c) | Nov 16, 2021 |
| HP            | 3397                        | [be170ea3c0](https://linux-hardware.org/?probe=be170ea3c0) | Nov 15, 2021 |
| HP            | 3397                        | [33500b1506](https://linux-hardware.org/?probe=33500b1506) | Nov 15, 2021 |
| ASRock        | K8Upgrade-VM800             | [082a3abfd7](https://linux-hardware.org/?probe=082a3abfd7) | Nov 15, 2021 |
| ASUSTek       | P5KPL/1600                  | [16fc189abd](https://linux-hardware.org/?probe=16fc189abd) | Nov 15, 2021 |
| Gigabyte      | Z77X-D3H                    | [be03431631](https://linux-hardware.org/?probe=be03431631) | Nov 15, 2021 |
| Lenovo        | ThinkCentre A70z 1165AEG    | [0e36428c44](https://linux-hardware.org/?probe=0e36428c44) | Nov 14, 2021 |
| Gigabyte      | H87M-D3H                    | [2d14af5192](https://linux-hardware.org/?probe=2d14af5192) | Nov 14, 2021 |
| MSI           | B350 PC MATE                | [e8420e53fd](https://linux-hardware.org/?probe=e8420e53fd) | Nov 14, 2021 |
| HPE           | ProLiant MicroServer Gen... | [1c302d3d99](https://linux-hardware.org/?probe=1c302d3d99) | Nov 14, 2021 |
| ASUSTek       | A88XM-A                     | [b30ab99344](https://linux-hardware.org/?probe=b30ab99344) | Nov 14, 2021 |
| HP            | 0B4Ch D                     | [c5bd8d37eb](https://linux-hardware.org/?probe=c5bd8d37eb) | Nov 13, 2021 |
| Gigabyte      | F2A88XM-D3H                 | [43cad93f6f](https://linux-hardware.org/?probe=43cad93f6f) | Nov 13, 2021 |
| MSI           | E3M WORKSTATION V5          | [8defc9a3ab](https://linux-hardware.org/?probe=8defc9a3ab) | Nov 13, 2021 |
| MSI           | E3M WORKSTATION V5          | [d46343ea4b](https://linux-hardware.org/?probe=d46343ea4b) | Nov 13, 2021 |
| Acer          | RS780DV                     | [415847f244](https://linux-hardware.org/?probe=415847f244) | Nov 13, 2021 |
| Gigabyte      | H97M-HD3                    | [c8d9d803dc](https://linux-hardware.org/?probe=c8d9d803dc) | Nov 13, 2021 |
| Intel         | DN2800MT AAG81515-900       | [9c80fda1da](https://linux-hardware.org/?probe=9c80fda1da) | Nov 13, 2021 |
| Acer          | RS780DV                     | [610927f2e1](https://linux-hardware.org/?probe=610927f2e1) | Nov 12, 2021 |
| ASUSTek       | P8Z77-V LE                  | [4662796030](https://linux-hardware.org/?probe=4662796030) | Nov 12, 2021 |
| ASRock        | Z97E-ITX/ac                 | [b6d11ec1ba](https://linux-hardware.org/?probe=b6d11ec1ba) | Nov 11, 2021 |
| ASRock        | X470 Master SLI             | [7058d85808](https://linux-hardware.org/?probe=7058d85808) | Nov 11, 2021 |
| Acer          | Aspire X3995                | [351c694ae4](https://linux-hardware.org/?probe=351c694ae4) | Nov 11, 2021 |
| Dell          | 0M5DCD A00                  | [afe9c5ca6f](https://linux-hardware.org/?probe=afe9c5ca6f) | Nov 10, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [36e64b8256](https://linux-hardware.org/?probe=36e64b8256) | Nov 10, 2021 |
| Huanan        | X99-F8 V2.0                 | [7463b38c9c](https://linux-hardware.org/?probe=7463b38c9c) | Nov 10, 2021 |
| ASUSTek       | ROG STRIX B460-F GAMING     | [81726142d7](https://linux-hardware.org/?probe=81726142d7) | Nov 10, 2021 |
| ASUSTek       | PRIME Z490-P                | [c25ef7b482](https://linux-hardware.org/?probe=c25ef7b482) | Nov 08, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | [0ef80f43bb](https://linux-hardware.org/?probe=0ef80f43bb) | Nov 08, 2021 |
| ASRock        | G31M-S                      | [2ff442af20](https://linux-hardware.org/?probe=2ff442af20) | Nov 08, 2021 |
| MSI           | X370 GAMING PLUS            | [f04a2bdf6e](https://linux-hardware.org/?probe=f04a2bdf6e) | Nov 07, 2021 |
| Dell          | 0M5DCD A00                  | [637bbc0c25](https://linux-hardware.org/?probe=637bbc0c25) | Nov 07, 2021 |
| ASUSTek       | H87-PLUS                    | [a699d4683c](https://linux-hardware.org/?probe=a699d4683c) | Nov 07, 2021 |
| ASRock        | B450M Pro4                  | [1fb0114a05](https://linux-hardware.org/?probe=1fb0114a05) | Nov 07, 2021 |
| Pegatron      | EVANS                       | [00cdced4d4](https://linux-hardware.org/?probe=00cdced4d4) | Nov 06, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [d7e365ed4b](https://linux-hardware.org/?probe=d7e365ed4b) | Nov 06, 2021 |
| Gigabyte      | B450M DS3H-CF               | [4b112de56d](https://linux-hardware.org/?probe=4b112de56d) | Nov 06, 2021 |
| Lenovo        | SHARKBAY No DPK             | [92be8f6c8b](https://linux-hardware.org/?probe=92be8f6c8b) | Nov 06, 2021 |
| MSI           | MEG X570 UNIFY              | [37685b5198](https://linux-hardware.org/?probe=37685b5198) | Nov 06, 2021 |
| ASUSTek       | P8Z77-V LX                  | [2297044b3a](https://linux-hardware.org/?probe=2297044b3a) | Nov 06, 2021 |
| Intel         | BTC-T37                     | [7c29416d55](https://linux-hardware.org/?probe=7c29416d55) | Nov 04, 2021 |
| HP            | ProLiant ML110 G7           | [2c91f2a607](https://linux-hardware.org/?probe=2c91f2a607) | Nov 04, 2021 |
| ASUSTek       | Z97-K                       | [3164be18f3](https://linux-hardware.org/?probe=3164be18f3) | Nov 04, 2021 |
| MSI           | B150 PC MATE                | [3fdd2f72ac](https://linux-hardware.org/?probe=3fdd2f72ac) | Nov 04, 2021 |
| Gigabyte      | B150M-D3H-CF                | [f5ef935897](https://linux-hardware.org/?probe=f5ef935897) | Nov 04, 2021 |
| HP            | 8860 A                      | [567271f7e7](https://linux-hardware.org/?probe=567271f7e7) | Nov 03, 2021 |
| HP            | 8860 A                      | [2176b7b19a](https://linux-hardware.org/?probe=2176b7b19a) | Nov 03, 2021 |
| Dell          | 0NK5PH A01                  | [817c2b6d6b](https://linux-hardware.org/?probe=817c2b6d6b) | Nov 03, 2021 |
| Gigabyte      | H61M-S1                     | [772accc103](https://linux-hardware.org/?probe=772accc103) | Nov 03, 2021 |
| Gigabyte      | H61M-S1                     | [a601cc3ed9](https://linux-hardware.org/?probe=a601cc3ed9) | Nov 03, 2021 |
| ASUSTek       | Z87M-PLUS                   | [c26ea680eb](https://linux-hardware.org/?probe=c26ea680eb) | Nov 03, 2021 |
| Gigabyte      | F2A88XM-D3H                 | [b20a9e2eb0](https://linux-hardware.org/?probe=b20a9e2eb0) | Nov 03, 2021 |
| MSI           | A88XM-E35                   | [c8d4d0f9c5](https://linux-hardware.org/?probe=c8d4d0f9c5) | Nov 03, 2021 |
| MSI           | A88XM-E35                   | [7079674844](https://linux-hardware.org/?probe=7079674844) | Nov 03, 2021 |
| ASUSTek       | EB1501P                     | [b4407d37ce](https://linux-hardware.org/?probe=b4407d37ce) | Nov 03, 2021 |
| Biostar       | A68MD PRO                   | [19a6612e0a](https://linux-hardware.org/?probe=19a6612e0a) | Nov 03, 2021 |
| Foxconn       | 2AA9h                       | [92ec7d0070](https://linux-hardware.org/?probe=92ec7d0070) | Nov 03, 2021 |
| HP            | 8860 A                      | [7c3c80b113](https://linux-hardware.org/?probe=7c3c80b113) | Nov 02, 2021 |
| Biostar       | A68MD PRO                   | [417cbcba6a](https://linux-hardware.org/?probe=417cbcba6a) | Nov 02, 2021 |
| Dell          | 0KP561                      | [e0c7723977](https://linux-hardware.org/?probe=e0c7723977) | Nov 02, 2021 |
| Dell          | 09WH54 A01                  | [71b3674e8c](https://linux-hardware.org/?probe=71b3674e8c) | Nov 02, 2021 |
| Dell          | 0KP561                      | [904f09d033](https://linux-hardware.org/?probe=904f09d033) | Nov 02, 2021 |
| Gigabyte      | M61PM-S2                    | [ed3a73a8a0](https://linux-hardware.org/?probe=ed3a73a8a0) | Nov 02, 2021 |
| Medion        | MS-7728                     | [564ffdab3d](https://linux-hardware.org/?probe=564ffdab3d) | Nov 02, 2021 |
| ASUSTek       | P7P55D                      | [1a1f3c42e0](https://linux-hardware.org/?probe=1a1f3c42e0) | Nov 01, 2021 |
| Pegatron      | 2AF0                        | [cffe6f5469](https://linux-hardware.org/?probe=cffe6f5469) | Nov 01, 2021 |
| Dell          | 0PC5F7 A03                  | [7599b9831d](https://linux-hardware.org/?probe=7599b9831d) | Nov 01, 2021 |
| HP            | 21D0                        | [040c7efa45](https://linux-hardware.org/?probe=040c7efa45) | Nov 01, 2021 |
| Intel         | BTC-T37                     | [a8f544c7d1](https://linux-hardware.org/?probe=a8f544c7d1) | Nov 01, 2021 |
| Unknown       | Unknown                     | [7983497985](https://linux-hardware.org/?probe=7983497985) | Oct 31, 2021 |
| Unknown       | Unknown                     | [75cc8a67e9](https://linux-hardware.org/?probe=75cc8a67e9) | Oct 31, 2021 |
| MSI           | Z170-A PRO                  | [77006702f8](https://linux-hardware.org/?probe=77006702f8) | Oct 31, 2021 |
| ASUSTek       | M5A78L/USB3                 | [6ca4f46d1b](https://linux-hardware.org/?probe=6ca4f46d1b) | Oct 31, 2021 |
| MSI           | Z97-G45 GAMING              | [e9cd437617](https://linux-hardware.org/?probe=e9cd437617) | Oct 31, 2021 |
| Dell          | 0PC5F7 A03                  | [e04a41fc30](https://linux-hardware.org/?probe=e04a41fc30) | Oct 31, 2021 |
| ASUSTek       | M2N-E SLI                   | [f9bff20c4d](https://linux-hardware.org/?probe=f9bff20c4d) | Oct 31, 2021 |
| ASUSTek       | M2N-E SLI                   | [03db91ce41](https://linux-hardware.org/?probe=03db91ce41) | Oct 31, 2021 |
| HP            | 1587h                       | [2aeea457fd](https://linux-hardware.org/?probe=2aeea457fd) | Oct 31, 2021 |
| Gigabyte      | B450M DS3H-CF               | [70a2909c2d](https://linux-hardware.org/?probe=70a2909c2d) | Oct 31, 2021 |
| Gigabyte      | B450M DS3H-CF               | [01a8d30d48](https://linux-hardware.org/?probe=01a8d30d48) | Oct 31, 2021 |
| Dell          | 0YXT71 A02                  | [e1b966b80d](https://linux-hardware.org/?probe=e1b966b80d) | Oct 30, 2021 |
| Dell          | 0PC5F7 A03                  | [d4c089bc2f](https://linux-hardware.org/?probe=d4c089bc2f) | Oct 30, 2021 |
| Dell          | 08WKV3 A00                  | [827cb9a77a](https://linux-hardware.org/?probe=827cb9a77a) | Oct 30, 2021 |
| Gigabyte      | H110M-S2H-CF                | [fbaa649304](https://linux-hardware.org/?probe=fbaa649304) | Oct 30, 2021 |
| Dell          | 0YXT71 A02                  | [d220ec0b0b](https://linux-hardware.org/?probe=d220ec0b0b) | Oct 29, 2021 |
| ASUSTek       | M2N-MX SE                   | [91fe7919be](https://linux-hardware.org/?probe=91fe7919be) | Oct 29, 2021 |
| HP            | ProLiant ML350 G6           | [9753f223e2](https://linux-hardware.org/?probe=9753f223e2) | Oct 29, 2021 |
| HP            | ProLiant ML350 G6           | [b38eec0fcb](https://linux-hardware.org/?probe=b38eec0fcb) | Oct 29, 2021 |
| HP            | ProLiant ML350 G6           | [afa2c8eed0](https://linux-hardware.org/?probe=afa2c8eed0) | Oct 29, 2021 |
| Dell          | 0C3YXR A00                  | [3fbbe71d21](https://linux-hardware.org/?probe=3fbbe71d21) | Oct 28, 2021 |
| ASRock        | B550M Steel Legend          | [df8ab9effb](https://linux-hardware.org/?probe=df8ab9effb) | Oct 28, 2021 |
| HP            | 0AECh D                     | [15a01d5e13](https://linux-hardware.org/?probe=15a01d5e13) | Oct 28, 2021 |
| Pegatron      | EVANS                       | [30143b0cb7](https://linux-hardware.org/?probe=30143b0cb7) | Oct 28, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [03af7df5b2](https://linux-hardware.org/?probe=03af7df5b2) | Oct 28, 2021 |
| ASRock        | AB350 Gaming-ITX/ac         | [c7798ba8d3](https://linux-hardware.org/?probe=c7798ba8d3) | Oct 28, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | [c198141a8e](https://linux-hardware.org/?probe=c198141a8e) | Oct 28, 2021 |
| ASRock        | G31M-GS                     | [17892fbf03](https://linux-hardware.org/?probe=17892fbf03) | Oct 27, 2021 |
| ASRock        | G31M-GS                     | [25e9cd546b](https://linux-hardware.org/?probe=25e9cd546b) | Oct 27, 2021 |
| Foxconn       | 2ABF                        | [380d5ab9f0](https://linux-hardware.org/?probe=380d5ab9f0) | Oct 27, 2021 |
| ASUSTek       | Z87-A                       | [36e2c969b8](https://linux-hardware.org/?probe=36e2c969b8) | Oct 26, 2021 |
| MSI           | B85-G41 PC Mate             | [90659e6a34](https://linux-hardware.org/?probe=90659e6a34) | Oct 26, 2021 |
| Dell          | 0M5DCD A00                  | [f7ee091ae1](https://linux-hardware.org/?probe=f7ee091ae1) | Oct 26, 2021 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [05766074d7](https://linux-hardware.org/?probe=05766074d7) | Oct 26, 2021 |
| MSI           | MS-7309                     | [72f1e0a452](https://linux-hardware.org/?probe=72f1e0a452) | Oct 25, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [3134454d4f](https://linux-hardware.org/?probe=3134454d4f) | Oct 24, 2021 |
| MSI           | MPG Z490 GAMING PLUS        | [487d0f0e12](https://linux-hardware.org/?probe=487d0f0e12) | Oct 24, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [eb97afcaa6](https://linux-hardware.org/?probe=eb97afcaa6) | Oct 24, 2021 |
| HP            | 3047h                       | [06668ade73](https://linux-hardware.org/?probe=06668ade73) | Oct 23, 2021 |
| Pegatron      | 2AB5                        | [2590ec6a56](https://linux-hardware.org/?probe=2590ec6a56) | Oct 23, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [879759ba36](https://linux-hardware.org/?probe=879759ba36) | Oct 23, 2021 |
| Gigabyte      | F2A88X-D3H                  | [0fca47e3eb](https://linux-hardware.org/?probe=0fca47e3eb) | Oct 22, 2021 |
| MSI           | Z97 GAMING 5                | [0273030434](https://linux-hardware.org/?probe=0273030434) | Oct 22, 2021 |
| Dell          | 0KP561                      | [08bbb7d29e](https://linux-hardware.org/?probe=08bbb7d29e) | Oct 22, 2021 |
| Gigabyte      | H510M H                     | [4b2e1ddc09](https://linux-hardware.org/?probe=4b2e1ddc09) | Oct 22, 2021 |
| MSI           | B450M PRO-VDH MAX           | [11f7ec8b16](https://linux-hardware.org/?probe=11f7ec8b16) | Oct 21, 2021 |
| ICP / iEi     | SA58 V1.01                  | [bca4498e5d](https://linux-hardware.org/?probe=bca4498e5d) | Oct 21, 2021 |
| Dell          | 0GDG8Y A00                  | [a4bf9808a8](https://linux-hardware.org/?probe=a4bf9808a8) | Oct 21, 2021 |
| ASRock        | E350M1                      | [84353af140](https://linux-hardware.org/?probe=84353af140) | Oct 21, 2021 |
| Gigabyte      | F2A88X-D3H                  | [df8210558e](https://linux-hardware.org/?probe=df8210558e) | Oct 21, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [a79f5ef1cf](https://linux-hardware.org/?probe=a79f5ef1cf) | Oct 20, 2021 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [a29fc046a6](https://linux-hardware.org/?probe=a29fc046a6) | Oct 20, 2021 |
| ASRock        | TRX40 Creator               | [8789f3f1e1](https://linux-hardware.org/?probe=8789f3f1e1) | Oct 20, 2021 |
| MSI           | H97M-G43                    | [48617be8f2](https://linux-hardware.org/?probe=48617be8f2) | Oct 20, 2021 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [de600dc6cc](https://linux-hardware.org/?probe=de600dc6cc) | Oct 20, 2021 |
| ASUSTek       | P8Z77-V PRO                 | [1276c2e404](https://linux-hardware.org/?probe=1276c2e404) | Oct 20, 2021 |
| ASRock        | H81M-HDS R2.0               | [33159aa42b](https://linux-hardware.org/?probe=33159aa42b) | Oct 19, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | [1db051798c](https://linux-hardware.org/?probe=1db051798c) | Oct 19, 2021 |
| ASUSTek       | P8Z77-V                     | [e59d042da2](https://linux-hardware.org/?probe=e59d042da2) | Oct 19, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [28e2302e29](https://linux-hardware.org/?probe=28e2302e29) | Oct 19, 2021 |
| MSI           | 760GM-P23                   | [9e2d96b5b6](https://linux-hardware.org/?probe=9e2d96b5b6) | Oct 19, 2021 |
| MSI           | H55M-E33                    | [4b6fa6fd54](https://linux-hardware.org/?probe=4b6fa6fd54) | Oct 19, 2021 |
| ASRock        | Z87 Extreme4                | [2ec87a3f6f](https://linux-hardware.org/?probe=2ec87a3f6f) | Oct 18, 2021 |
| Gigabyte      | M61PME-S2                   | [7076f55128](https://linux-hardware.org/?probe=7076f55128) | Oct 18, 2021 |
| Packard Be... | IXTREME M5850               | [68136b417b](https://linux-hardware.org/?probe=68136b417b) | Oct 18, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [90fe8a952c](https://linux-hardware.org/?probe=90fe8a952c) | Oct 18, 2021 |
| Shuttle       | FS87                        | [f0bcf2111a](https://linux-hardware.org/?probe=f0bcf2111a) | Oct 18, 2021 |
| Gigabyte      | B550M DS3H                  | [6178b450ad](https://linux-hardware.org/?probe=6178b450ad) | Oct 17, 2021 |
| ASRock        | B560M-HDV                   | [200bfff8ba](https://linux-hardware.org/?probe=200bfff8ba) | Oct 17, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | [a1796c4f09](https://linux-hardware.org/?probe=a1796c4f09) | Oct 17, 2021 |
| Gigabyte      | F2A78M-HD2                  | [4f34393ca6](https://linux-hardware.org/?probe=4f34393ca6) | Oct 17, 2021 |
| Gigabyte      | X570 GAMING X               | [dd8260abf9](https://linux-hardware.org/?probe=dd8260abf9) | Oct 16, 2021 |
| ASUSTek       | PRIME B450M-A               | [80c959f7ca](https://linux-hardware.org/?probe=80c959f7ca) | Oct 15, 2021 |
| Pegatron      | Eureka3                     | [6499d1cf77](https://linux-hardware.org/?probe=6499d1cf77) | Oct 15, 2021 |
| Pegatron      | Eureka3                     | [a456734f94](https://linux-hardware.org/?probe=a456734f94) | Oct 15, 2021 |
| MSI           | H97 GUARD-PRO               | [b0879e4a90](https://linux-hardware.org/?probe=b0879e4a90) | Oct 15, 2021 |
| Gigabyte      | GA-870A-UD3                 | [b967c1cfc5](https://linux-hardware.org/?probe=b967c1cfc5) | Oct 15, 2021 |
| ASUSTek       | F2A85-M PRO                 | [f90d8850f9](https://linux-hardware.org/?probe=f90d8850f9) | Oct 15, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [a528c3b507](https://linux-hardware.org/?probe=a528c3b507) | Oct 15, 2021 |
| Gigabyte      | H61M-S2PV                   | [d54d095b0d](https://linux-hardware.org/?probe=d54d095b0d) | Oct 15, 2021 |
| Dell          | 0N4YC8 A00                  | [1a94195ddb](https://linux-hardware.org/?probe=1a94195ddb) | Oct 15, 2021 |
| Unknown       | X79-P3                      | [a6e06b8cba](https://linux-hardware.org/?probe=a6e06b8cba) | Oct 15, 2021 |
| HP            | 3047h                       | [3555f36d18](https://linux-hardware.org/?probe=3555f36d18) | Oct 14, 2021 |
| HP            | 3047h                       | [1c853f239e](https://linux-hardware.org/?probe=1c853f239e) | Oct 14, 2021 |
| Gigabyte      | X570 AORUS PRO              | [31e1bbbea1](https://linux-hardware.org/?probe=31e1bbbea1) | Oct 14, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [77dff3a32a](https://linux-hardware.org/?probe=77dff3a32a) | Oct 14, 2021 |
| ASUSTek       | PRIME B450M-A               | [0b5ca0df4e](https://linux-hardware.org/?probe=0b5ca0df4e) | Oct 14, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [a99608bc0c](https://linux-hardware.org/?probe=a99608bc0c) | Oct 13, 2021 |
| MSI           | 970 GAMING                  | [a9928ec3dc](https://linux-hardware.org/?probe=a9928ec3dc) | Oct 13, 2021 |
| ASRock        | AB350M-HDV                  | [1d2c20267a](https://linux-hardware.org/?probe=1d2c20267a) | Oct 13, 2021 |
| Gigabyte      | B450 AORUS ELITE V2         | [b3c4471f54](https://linux-hardware.org/?probe=b3c4471f54) | Oct 13, 2021 |
| MSI           | B350 TOMAHAWK               | [41379ff58a](https://linux-hardware.org/?probe=41379ff58a) | Oct 13, 2021 |
| MSI           | NF520T-C35                  | [277af949b6](https://linux-hardware.org/?probe=277af949b6) | Oct 12, 2021 |
| MSI           | NF520T-C35                  | [ed9520268a](https://linux-hardware.org/?probe=ed9520268a) | Oct 12, 2021 |
| Dell          | 0PC5F7 A03                  | [10b4482e0f](https://linux-hardware.org/?probe=10b4482e0f) | Oct 12, 2021 |
| Gigabyte      | B450 AORUS ELITE V2         | [35417a9b1f](https://linux-hardware.org/?probe=35417a9b1f) | Oct 12, 2021 |
| MSI           | MPG Z490 GAMING PLUS        | [59f755658e](https://linux-hardware.org/?probe=59f755658e) | Oct 12, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [d36ac446bd](https://linux-hardware.org/?probe=d36ac446bd) | Oct 12, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [a972779ddc](https://linux-hardware.org/?probe=a972779ddc) | Oct 12, 2021 |
| ASUSTek       | PRIME B450M-A               | [138c57899f](https://linux-hardware.org/?probe=138c57899f) | Oct 11, 2021 |
| Dell          | 0215PR A02                  | [d9e5820db2](https://linux-hardware.org/?probe=d9e5820db2) | Oct 11, 2021 |
| MSI           | MPG Z490 GAMING PLUS        | [46f9cbae92](https://linux-hardware.org/?probe=46f9cbae92) | Oct 11, 2021 |
| ASUSTek       | Z87-A                       | [b905f9c827](https://linux-hardware.org/?probe=b905f9c827) | Oct 10, 2021 |
| ASUSTek       | F2A85-M PRO                 | [b52a51beee](https://linux-hardware.org/?probe=b52a51beee) | Oct 09, 2021 |
| Intel         | DQ77KB AAG81483-500         | [e686032cff](https://linux-hardware.org/?probe=e686032cff) | Oct 09, 2021 |
| Intel         | DQ77KB AAG81483-500         | [0705a7ff76](https://linux-hardware.org/?probe=0705a7ff76) | Oct 09, 2021 |
| Gigabyte      | M61PME-S2P                  | [6e233bce65](https://linux-hardware.org/?probe=6e233bce65) | Oct 09, 2021 |
| Medion        | H81H3-EM2 H81EM2W08.309     | [7f0cdb7424](https://linux-hardware.org/?probe=7f0cdb7424) | Oct 09, 2021 |
| ASUSTek       | PRIME B450M-A               | [f62701cf54](https://linux-hardware.org/?probe=f62701cf54) | Oct 09, 2021 |
| ASUSTek       | PRIME H410M-K               | [a4da124d05](https://linux-hardware.org/?probe=a4da124d05) | Oct 08, 2021 |
| Gigabyte      | B450 AORUS ELITE V2         | [8068b5b456](https://linux-hardware.org/?probe=8068b5b456) | Oct 08, 2021 |
| Gigabyte      | B450M DS3H-CF               | [cb7bf65b6c](https://linux-hardware.org/?probe=cb7bf65b6c) | Oct 08, 2021 |
| Foxconn       | 2AAF                        | [65e2eaccd6](https://linux-hardware.org/?probe=65e2eaccd6) | Oct 08, 2021 |
| ASUSTek       | P7P55D                      | [85e49e67ca](https://linux-hardware.org/?probe=85e49e67ca) | Oct 08, 2021 |
| Packard Be... | IMEDIA S3710                | [0e30e16dd6](https://linux-hardware.org/?probe=0e30e16dd6) | Oct 07, 2021 |
| MSI           | Z97-G45 GAMING              | [0d11725312](https://linux-hardware.org/?probe=0d11725312) | Oct 07, 2021 |
| Acer          | M945G                       | [d7bc24b484](https://linux-hardware.org/?probe=d7bc24b484) | Oct 07, 2021 |
| ASUSTek       | P5K                         | [e65f644073](https://linux-hardware.org/?probe=e65f644073) | Oct 07, 2021 |
| ASUSTek       | P5W DH Deluxe               | [3a064bdf05](https://linux-hardware.org/?probe=3a064bdf05) | Oct 07, 2021 |
| MSI           | B360M PRO-VH                | [e472116ccb](https://linux-hardware.org/?probe=e472116ccb) | Oct 07, 2021 |
| ASUSTek       | P8Z77-V LX                  | [d2defec478](https://linux-hardware.org/?probe=d2defec478) | Oct 07, 2021 |
| ASUSTek       | P8Z77-V LX                  | [6a5240a6cf](https://linux-hardware.org/?probe=6a5240a6cf) | Oct 07, 2021 |
| ASUSTek       | P8H77-V LE                  | [673f49386c](https://linux-hardware.org/?probe=673f49386c) | Oct 06, 2021 |
| Lenovo        | ThinkCentre M81 5049RE9     | [1360830bab](https://linux-hardware.org/?probe=1360830bab) | Oct 06, 2021 |
| MSI           | MS-9A45 0A                  | [04afb3d9fe](https://linux-hardware.org/?probe=04afb3d9fe) | Oct 06, 2021 |
| HP            | ProLiant MicroServer Gen... | [ebdea9d0f5](https://linux-hardware.org/?probe=ebdea9d0f5) | Oct 06, 2021 |
| Dell          | 0PC5F7 A03                  | [ff4e1fdb3a](https://linux-hardware.org/?probe=ff4e1fdb3a) | Oct 06, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [46552d08f3](https://linux-hardware.org/?probe=46552d08f3) | Oct 06, 2021 |
| ASUSTek       | P7H55-M SI                  | [704043deab](https://linux-hardware.org/?probe=704043deab) | Oct 06, 2021 |
| Dell          | 0T2HR0 A00                  | [dc55f173fe](https://linux-hardware.org/?probe=dc55f173fe) | Oct 05, 2021 |
| MSI           | A320M-A PRO MAX             | [6639f1cf4f](https://linux-hardware.org/?probe=6639f1cf4f) | Oct 05, 2021 |
| Lenovo        | ThinkCentre A55 92658HG     | [edc1f2768d](https://linux-hardware.org/?probe=edc1f2768d) | Oct 05, 2021 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | [ff6c577d9b](https://linux-hardware.org/?probe=ff6c577d9b) | Oct 05, 2021 |
| HP            | 21D0                        | [ba6cce80cb](https://linux-hardware.org/?probe=ba6cce80cb) | Oct 05, 2021 |
| MSI           | MS-9A45 0A                  | [658cbe1d32](https://linux-hardware.org/?probe=658cbe1d32) | Oct 05, 2021 |
| Lenovo        | 312A SDK0L22692 WIN 3306... | [5d1781625e](https://linux-hardware.org/?probe=5d1781625e) | Oct 05, 2021 |
| ASUSTek       | Rampage IV EXTREME          | [04ad8f47dc](https://linux-hardware.org/?probe=04ad8f47dc) | Oct 05, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [46a61c0976](https://linux-hardware.org/?probe=46a61c0976) | Oct 05, 2021 |
| ASUSTek       | P5G41T-M LX                 | [41aef7dc51](https://linux-hardware.org/?probe=41aef7dc51) | Oct 05, 2021 |
| Dell          | 0CRH6C A02                  | [9289bbcd3e](https://linux-hardware.org/?probe=9289bbcd3e) | Oct 04, 2021 |
| MSI           | H55M-ED55                   | [032097d2f5](https://linux-hardware.org/?probe=032097d2f5) | Oct 03, 2021 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [de0f051658](https://linux-hardware.org/?probe=de0f051658) | Oct 02, 2021 |
| ASUSTek       | P5QPL-AM                    | [feb4da8218](https://linux-hardware.org/?probe=feb4da8218) | Oct 02, 2021 |
| Lenovo        | ThinkCentre A70z 1165AEG    | [a10065fd78](https://linux-hardware.org/?probe=a10065fd78) | Oct 02, 2021 |
| MSI           | B85-G43                     | [1dde7a0e87](https://linux-hardware.org/?probe=1dde7a0e87) | Oct 02, 2021 |
| MSI           | Z370 PC PRO                 | [b3f32a59be](https://linux-hardware.org/?probe=b3f32a59be) | Oct 02, 2021 |
| Gigabyte      | B450 AORUS ELITE V2         | [3108ebc19b](https://linux-hardware.org/?probe=3108ebc19b) | Oct 02, 2021 |
| Dell          | 06JWJY A01                  | [13718f9c0b](https://linux-hardware.org/?probe=13718f9c0b) | Oct 01, 2021 |
| Lenovo        | 103D SDK0Q40112 WIN 3305... | [e78610af87](https://linux-hardware.org/?probe=e78610af87) | Oct 01, 2021 |
| Lenovo        | 103D SDK0Q40112 WIN 3305... | [21a915ab04](https://linux-hardware.org/?probe=21a915ab04) | Oct 01, 2021 |
| Acer          | RS780DV                     | [5b85dd12e6](https://linux-hardware.org/?probe=5b85dd12e6) | Oct 01, 2021 |
| Gigabyte      | M68SM-S2L                   | [9bea72de00](https://linux-hardware.org/?probe=9bea72de00) | Sep 30, 2021 |
| Gigabyte      | M68SM-S2L                   | [66d1af2e80](https://linux-hardware.org/?probe=66d1af2e80) | Sep 30, 2021 |
| ASUSTek       | M4A785TD-M EVO              | [0228a60cde](https://linux-hardware.org/?probe=0228a60cde) | Sep 29, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [9b7ef00b29](https://linux-hardware.org/?probe=9b7ef00b29) | Sep 29, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [e48cd88acc](https://linux-hardware.org/?probe=e48cd88acc) | Sep 29, 2021 |
| Gigabyte      | H67A-USB3-B3                | [9440c234ae](https://linux-hardware.org/?probe=9440c234ae) | Sep 28, 2021 |
| ASUSTek       | M4A785TD-V EVO              | [c21eff0d32](https://linux-hardware.org/?probe=c21eff0d32) | Sep 28, 2021 |
| Dell          | 0F373D A00                  | [24954bd6cf](https://linux-hardware.org/?probe=24954bd6cf) | Sep 28, 2021 |
| Dell          | 0GXM1W A00                  | [57b3b27a47](https://linux-hardware.org/?probe=57b3b27a47) | Sep 28, 2021 |
| HP            | 1497                        | [1d45c925f0](https://linux-hardware.org/?probe=1d45c925f0) | Sep 27, 2021 |
| eMachines     | EL1352                      | [2d5f9a7733](https://linux-hardware.org/?probe=2d5f9a7733) | Sep 27, 2021 |
| HP            | 212B                        | [b49e0ae670](https://linux-hardware.org/?probe=b49e0ae670) | Sep 27, 2021 |
| ASUSTek       | P8P67 DELUXE                | [33216e0982](https://linux-hardware.org/?probe=33216e0982) | Sep 26, 2021 |
| ASUSTek       | P5Q-E                       | [39df7a70f9](https://linux-hardware.org/?probe=39df7a70f9) | Sep 26, 2021 |
| Gigabyte      | B250M-DS3H-CF               | [6949d5b908](https://linux-hardware.org/?probe=6949d5b908) | Sep 26, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [b95cc329ed](https://linux-hardware.org/?probe=b95cc329ed) | Sep 26, 2021 |
| Dell          | 0RW199                      | [fb15e813cd](https://linux-hardware.org/?probe=fb15e813cd) | Sep 25, 2021 |
| ASUSTek       | M4A78LT-M-LE                | [cc524fa15a](https://linux-hardware.org/?probe=cc524fa15a) | Sep 25, 2021 |
| ASUSTek       | M4A78LT-M-LE                | [4c89eda70c](https://linux-hardware.org/?probe=4c89eda70c) | Sep 25, 2021 |
| HP            | 8860 A                      | [f3e67793a1](https://linux-hardware.org/?probe=f3e67793a1) | Sep 25, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [f8428d002d](https://linux-hardware.org/?probe=f8428d002d) | Sep 24, 2021 |
| Gigabyte      | H67A-USB3-B3                | [0aab60dbc8](https://linux-hardware.org/?probe=0aab60dbc8) | Sep 24, 2021 |
| Dell          | 0C27VV A01                  | [189c6b9bd1](https://linux-hardware.org/?probe=189c6b9bd1) | Sep 23, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [03b0290469](https://linux-hardware.org/?probe=03b0290469) | Sep 23, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [b4cf3f9692](https://linux-hardware.org/?probe=b4cf3f9692) | Sep 23, 2021 |
| Gigabyte      | H97-HD3                     | [bb4f678d57](https://linux-hardware.org/?probe=bb4f678d57) | Sep 23, 2021 |
| ASUSTek       | PRIME B460-PLUS             | [d76a8245a5](https://linux-hardware.org/?probe=d76a8245a5) | Sep 22, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [72bba35083](https://linux-hardware.org/?probe=72bba35083) | Sep 22, 2021 |
| AZW           | L55                         | [1b49e20e8a](https://linux-hardware.org/?probe=1b49e20e8a) | Sep 22, 2021 |
| Gigabyte      | H67A-USB3-B3                | [772b49f342](https://linux-hardware.org/?probe=772b49f342) | Sep 21, 2021 |
| Gigabyte      | H110M-S2H-CF                | [05eab7ef4b](https://linux-hardware.org/?probe=05eab7ef4b) | Sep 21, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | [577bc6cd1a](https://linux-hardware.org/?probe=577bc6cd1a) | Sep 21, 2021 |
| ASUSTek       | Z170-A                      | [323169caf9](https://linux-hardware.org/?probe=323169caf9) | Sep 21, 2021 |
| eMachines     | EL1850                      | [a70c7ba20f](https://linux-hardware.org/?probe=a70c7ba20f) | Sep 21, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [1e7a40ebdb](https://linux-hardware.org/?probe=1e7a40ebdb) | Sep 20, 2021 |
| MSI           | H410M-A PRO                 | [6395502a0b](https://linux-hardware.org/?probe=6395502a0b) | Sep 20, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | [7891bfd540](https://linux-hardware.org/?probe=7891bfd540) | Sep 20, 2021 |
| ASUSTek       | PRIME A520M-K               | [68c27a546a](https://linux-hardware.org/?probe=68c27a546a) | Sep 20, 2021 |
| HP            | 225E                        | [eadad0eb90](https://linux-hardware.org/?probe=eadad0eb90) | Sep 19, 2021 |
| ASUSTek       | B85M-G                      | [9f31d3090b](https://linux-hardware.org/?probe=9f31d3090b) | Sep 19, 2021 |
| Gigabyte      | A520M S2H                   | [1db5fc32c3](https://linux-hardware.org/?probe=1db5fc32c3) | Sep 18, 2021 |
| ASUSTek       | P8P67                       | [8c1582c3ed](https://linux-hardware.org/?probe=8c1582c3ed) | Sep 18, 2021 |
| HP            | 3397                        | [2055aedbe2](https://linux-hardware.org/?probe=2055aedbe2) | Sep 17, 2021 |
| Acer          | RS740DVF                    | [4c36d6b364](https://linux-hardware.org/?probe=4c36d6b364) | Sep 17, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [0e308c5ece](https://linux-hardware.org/?probe=0e308c5ece) | Sep 17, 2021 |
| ASUSTek       | M4A79XTD EVO                | [babdb2f68a](https://linux-hardware.org/?probe=babdb2f68a) | Sep 17, 2021 |
| Foxconn       | 2AAF                        | [be2ce05253](https://linux-hardware.org/?probe=be2ce05253) | Sep 17, 2021 |
| Gigabyte      | G41M-Combo                  | [0941fe8cc4](https://linux-hardware.org/?probe=0941fe8cc4) | Sep 16, 2021 |
| ASUSTek       | P8Z77-V LK                  | [203e58b1d1](https://linux-hardware.org/?probe=203e58b1d1) | Sep 16, 2021 |
| MSI           | B85-G43 GAMING              | [da6e58ed2a](https://linux-hardware.org/?probe=da6e58ed2a) | Sep 16, 2021 |
| Foxconn       | 2AAF                        | [ca0b3e0add](https://linux-hardware.org/?probe=ca0b3e0add) | Sep 15, 2021 |
| Dell          | 0Y7WYT A00                  | [e4278d3243](https://linux-hardware.org/?probe=e4278d3243) | Sep 15, 2021 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | [e880de0931](https://linux-hardware.org/?probe=e880de0931) | Sep 15, 2021 |
| ASUSTek       | P6T WS PRO                  | [6054cd43f4](https://linux-hardware.org/?probe=6054cd43f4) | Sep 14, 2021 |
| ASUSTek       | PRIME B460-PLUS             | [67361acb38](https://linux-hardware.org/?probe=67361acb38) | Sep 14, 2021 |
| ASUSTek       | PRIME B460-PLUS             | [f7cc010076](https://linux-hardware.org/?probe=f7cc010076) | Sep 14, 2021 |
| MSI           | MAG B550M BAZOOKA           | [6ddab6806e](https://linux-hardware.org/?probe=6ddab6806e) | Sep 14, 2021 |
| MSI           | MAG B550M BAZOOKA           | [72352cd62b](https://linux-hardware.org/?probe=72352cd62b) | Sep 14, 2021 |
| ASUSTek       | P5Q                         | [cb4997020a](https://linux-hardware.org/?probe=cb4997020a) | Sep 14, 2021 |
| ASUSTek       | Leonite2                    | [be99559571](https://linux-hardware.org/?probe=be99559571) | Sep 12, 2021 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [cf7cbe9ec0](https://linux-hardware.org/?probe=cf7cbe9ec0) | Sep 12, 2021 |
| Foxconn       | 2ABF                        | [b86d7ca102](https://linux-hardware.org/?probe=b86d7ca102) | Sep 12, 2021 |
| Gigabyte      | B450 AORUS ELITE V2         | [10cc07f1c3](https://linux-hardware.org/?probe=10cc07f1c3) | Sep 12, 2021 |
| HP            | 8704                        | [b26e444f12](https://linux-hardware.org/?probe=b26e444f12) | Sep 12, 2021 |
| Gigabyte      | B150M-D3H-CF                | [d13739db96](https://linux-hardware.org/?probe=d13739db96) | Sep 11, 2021 |
| Dell          | 0GDG8Y A00                  | [70e6485466](https://linux-hardware.org/?probe=70e6485466) | Sep 11, 2021 |
| ASRock        | B450 Gaming K4              | [356430d4ae](https://linux-hardware.org/?probe=356430d4ae) | Sep 11, 2021 |
| HP            | 83EE                        | [2a014fbea5](https://linux-hardware.org/?probe=2a014fbea5) | Sep 11, 2021 |
| MSI           | X99A TOMAHAWK               | [8a1c74b101](https://linux-hardware.org/?probe=8a1c74b101) | Sep 10, 2021 |
| Dell          | 0M5DCD A00                  | [f4c9642d6f](https://linux-hardware.org/?probe=f4c9642d6f) | Sep 10, 2021 |
| Gigabyte      | Z87MX-D3H-CF                | [f979017fa9](https://linux-hardware.org/?probe=f979017fa9) | Sep 09, 2021 |
| ASUSTek       | M3N18L T-M3N8200            | [bd8410bceb](https://linux-hardware.org/?probe=bd8410bceb) | Sep 09, 2021 |
| Dell          | 0JP3NX A00                  | [4fc7d3730e](https://linux-hardware.org/?probe=4fc7d3730e) | Sep 09, 2021 |
| Dell          | 0TP412                      | [25b9af915a](https://linux-hardware.org/?probe=25b9af915a) | Sep 09, 2021 |
| Gigabyte      | X79-UD3                     | [2bcb651e8f](https://linux-hardware.org/?probe=2bcb651e8f) | Sep 09, 2021 |
| HP            | 339A                        | [7430a62153](https://linux-hardware.org/?probe=7430a62153) | Sep 09, 2021 |
| ASUSTek       | H81-PLUS                    | [4a0b05a3cd](https://linux-hardware.org/?probe=4a0b05a3cd) | Sep 09, 2021 |
| Gigabyte      | GA-880GM-USB3               | [969bf56907](https://linux-hardware.org/?probe=969bf56907) | Sep 09, 2021 |
| MSI           | B360 GAMING PLUS            | [41d1a4f015](https://linux-hardware.org/?probe=41d1a4f015) | Sep 09, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [8909b2d9b7](https://linux-hardware.org/?probe=8909b2d9b7) | Sep 08, 2021 |
| Dell          | 03NVJ6 A01                  | [64435431ed](https://linux-hardware.org/?probe=64435431ed) | Sep 08, 2021 |
| Dell          | 0NNNCT A01                  | [db2503f46f](https://linux-hardware.org/?probe=db2503f46f) | Sep 07, 2021 |
| Dell          | 0M5DCD A00                  | [89f806e02f](https://linux-hardware.org/?probe=89f806e02f) | Sep 07, 2021 |
| Lenovo        | ThinkCentre M58e 7491B1G    | [85afc4a99b](https://linux-hardware.org/?probe=85afc4a99b) | Sep 07, 2021 |
| ASRock        | Z370M Pro4                  | [17c9df42cd](https://linux-hardware.org/?probe=17c9df42cd) | Sep 07, 2021 |
| ASRock        | Z370M Pro4                  | [01d203a7af](https://linux-hardware.org/?probe=01d203a7af) | Sep 07, 2021 |
| ASUSTek       | P7P55-M                     | [5c6513527b](https://linux-hardware.org/?probe=5c6513527b) | Sep 07, 2021 |
| Dell          | 0M5DCD A00                  | [ddee404146](https://linux-hardware.org/?probe=ddee404146) | Sep 07, 2021 |
| ASUSTek       | P8Z77-V LE PLUS             | [867b1f5318](https://linux-hardware.org/?probe=867b1f5318) | Sep 07, 2021 |
| ASUSTek       | P5KPL-AM EPU                | [4025c96223](https://linux-hardware.org/?probe=4025c96223) | Sep 06, 2021 |
| ASUSTek       | P5KPL-AM EPU                | [7eda37e31d](https://linux-hardware.org/?probe=7eda37e31d) | Sep 06, 2021 |
| Gigabyte      | GA-970A-D3                  | [42e5ea780a](https://linux-hardware.org/?probe=42e5ea780a) | Sep 06, 2021 |
| Dell          | 0C7195                      | [5e8cb420ea](https://linux-hardware.org/?probe=5e8cb420ea) | Sep 06, 2021 |
| MSI           | B450M PRO-M2 MAX            | [c40909a574](https://linux-hardware.org/?probe=c40909a574) | Sep 06, 2021 |
| Huanan        | X99-F8                      | [c1441fa5dc](https://linux-hardware.org/?probe=c1441fa5dc) | Sep 06, 2021 |
| Gigabyte      | H61M-D2H-USB3               | [57e1ed1142](https://linux-hardware.org/?probe=57e1ed1142) | Sep 05, 2021 |
| ASUSTek       | P8Z77-M                     | [475b67a609](https://linux-hardware.org/?probe=475b67a609) | Sep 05, 2021 |
| HP            | ProLiant MicroServer        | [69ca9e90ae](https://linux-hardware.org/?probe=69ca9e90ae) | Sep 05, 2021 |
| ASUSTek       | M4A88TD-M EVO               | [64875f65a3](https://linux-hardware.org/?probe=64875f65a3) | Sep 05, 2021 |
| HP            | 3029h                       | [9c52ec1eb2](https://linux-hardware.org/?probe=9c52ec1eb2) | Sep 04, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | [b52a9fd947](https://linux-hardware.org/?probe=b52a9fd947) | Sep 03, 2021 |
| ASUSTek       | P5Q                         | [036dfd91e1](https://linux-hardware.org/?probe=036dfd91e1) | Sep 03, 2021 |
| Fujitsu       | D2990-A1 S26361-D2990-A1    | [ee76fbd8e5](https://linux-hardware.org/?probe=ee76fbd8e5) | Sep 03, 2021 |
| Gigabyte      | 945P-S3                     | [823bc68829](https://linux-hardware.org/?probe=823bc68829) | Sep 02, 2021 |
| MSI           | TRX40 PRO WIFI              | [d337b01cb3](https://linux-hardware.org/?probe=d337b01cb3) | Sep 02, 2021 |
| ASUSTek       | P9X79                       | [d432591188](https://linux-hardware.org/?probe=d432591188) | Sep 01, 2021 |
| Dell          | 0RY007                      | [52d47340f2](https://linux-hardware.org/?probe=52d47340f2) | Sep 01, 2021 |
| ASUSTek       | Leonite2                    | [c331557969](https://linux-hardware.org/?probe=c331557969) | Sep 01, 2021 |
| Dell          | 0N4YC8 A00                  | [7e7b3b3b91](https://linux-hardware.org/?probe=7e7b3b3b91) | Aug 31, 2021 |
| Dell          | 0J37VM A01                  | [2505115dc2](https://linux-hardware.org/?probe=2505115dc2) | Aug 31, 2021 |
| Dell          | 0RW199                      | [caec671180](https://linux-hardware.org/?probe=caec671180) | Aug 31, 2021 |
| Biostar       | A320MH                      | [ad30d85752](https://linux-hardware.org/?probe=ad30d85752) | Aug 31, 2021 |
| ASUSTek       | P5Q-E                       | [997ce785b2](https://linux-hardware.org/?probe=997ce785b2) | Aug 31, 2021 |
| ASUSTek       | P7H55-M SI                  | [462a181df0](https://linux-hardware.org/?probe=462a181df0) | Aug 30, 2021 |
| Intel         | D54250WYK H13922-303        | [33f0fb6241](https://linux-hardware.org/?probe=33f0fb6241) | Aug 30, 2021 |
| MSI           | MAG B460M MORTAR            | [6fa1f56407](https://linux-hardware.org/?probe=6fa1f56407) | Aug 30, 2021 |
| ASRock        | B550 Extreme4               | [07024d83ca](https://linux-hardware.org/?probe=07024d83ca) | Aug 30, 2021 |
| ASUSTek       | P7H55-M SI                  | [2f9f7d43ad](https://linux-hardware.org/?probe=2f9f7d43ad) | Aug 30, 2021 |
| Foxconn       | 2ABF                        | [967db93155](https://linux-hardware.org/?probe=967db93155) | Aug 30, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [bbe1424130](https://linux-hardware.org/?probe=bbe1424130) | Aug 30, 2021 |
| Gigabyte      | A520M S2H                   | [1c95ab3662](https://linux-hardware.org/?probe=1c95ab3662) | Aug 29, 2021 |
| ASUSTek       | P8Z77-M PRO                 | [c0d2217f9a](https://linux-hardware.org/?probe=c0d2217f9a) | Aug 29, 2021 |
| ASUSTek       | P8Z77-M PRO                 | [85e89b83a0](https://linux-hardware.org/?probe=85e89b83a0) | Aug 29, 2021 |
| Gigabyte      | EP43-DS3                    | [0eaf518e06](https://linux-hardware.org/?probe=0eaf518e06) | Aug 29, 2021 |
| Gigabyte      | X570 AORUS PRO              | [445afafc69](https://linux-hardware.org/?probe=445afafc69) | Aug 29, 2021 |
| Gigabyte      | Z77-DS3H                    | [e06775bbd6](https://linux-hardware.org/?probe=e06775bbd6) | Aug 29, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | [05ad6628c6](https://linux-hardware.org/?probe=05ad6628c6) | Aug 29, 2021 |
| MSI           | MEG X570 UNIFY              | [cf5f33a843](https://linux-hardware.org/?probe=cf5f33a843) | Aug 28, 2021 |
| ASRock        | H470 Steel Legend           | [d11755c374](https://linux-hardware.org/?probe=d11755c374) | Aug 28, 2021 |
| Unknown       | Unknown                     | [22dcd2395a](https://linux-hardware.org/?probe=22dcd2395a) | Aug 28, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [614ac09d36](https://linux-hardware.org/?probe=614ac09d36) | Aug 28, 2021 |
| Jetway        | 1.0                         | [9c4b8ad466](https://linux-hardware.org/?probe=9c4b8ad466) | Aug 28, 2021 |
| MSI           | 2A9C                        | [57601d98f3](https://linux-hardware.org/?probe=57601d98f3) | Aug 28, 2021 |
| Gigabyte      | H61M-S2PV                   | [d2997c25fd](https://linux-hardware.org/?probe=d2997c25fd) | Aug 28, 2021 |
| MSI           | X570-A PRO                  | [830bfb129f](https://linux-hardware.org/?probe=830bfb129f) | Aug 27, 2021 |
| Packard Be... | MCP73VT-PM                  | [c9ed90c1a7](https://linux-hardware.org/?probe=c9ed90c1a7) | Aug 27, 2021 |
| HP            | 1497                        | [172fbe6a53](https://linux-hardware.org/?probe=172fbe6a53) | Aug 27, 2021 |
| ASUSTek       | P5QPL-VM EPU                | [a951328dee](https://linux-hardware.org/?probe=a951328dee) | Aug 27, 2021 |
| ASUSTek       | P6X58D-E                    | [b15958b9c4](https://linux-hardware.org/?probe=b15958b9c4) | Aug 27, 2021 |
| ASUSTek       | ROG STRIX TRX40-E GAMING    | [afd5f8b9b1](https://linux-hardware.org/?probe=afd5f8b9b1) | Aug 27, 2021 |
| ASUSTek       | P6X58D-E                    | [126fd385c1](https://linux-hardware.org/?probe=126fd385c1) | Aug 27, 2021 |
| MSI           | 2A9C                        | [61ba0e79da](https://linux-hardware.org/?probe=61ba0e79da) | Aug 26, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [aa1a98a9d6](https://linux-hardware.org/?probe=aa1a98a9d6) | Aug 25, 2021 |
| ASUSTek       | P7P55D DELUXE               | [179854811e](https://linux-hardware.org/?probe=179854811e) | Aug 24, 2021 |
| ASUSTek       | P7P55D DELUXE               | [ae12ab4c17](https://linux-hardware.org/?probe=ae12ab4c17) | Aug 24, 2021 |
| ASUSTek       | PRIME A320M-K               | [847e7f4c1a](https://linux-hardware.org/?probe=847e7f4c1a) | Aug 23, 2021 |
| MSI           | 2A9C                        | [14712a07fb](https://linux-hardware.org/?probe=14712a07fb) | Aug 23, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [e3c59baa2e](https://linux-hardware.org/?probe=e3c59baa2e) | Aug 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | [f128b4ee5a](https://linux-hardware.org/?probe=f128b4ee5a) | Aug 23, 2021 |
| Acer          | RS780DV                     | [57b9f12c78](https://linux-hardware.org/?probe=57b9f12c78) | Aug 23, 2021 |
| Dell          | 0T656F A02                  | [7115ffee65](https://linux-hardware.org/?probe=7115ffee65) | Aug 22, 2021 |
| MSI           | 2A9C                        | [198ebeb6c8](https://linux-hardware.org/?probe=198ebeb6c8) | Aug 22, 2021 |
| HP            | ProLiant ML350 G6           | [d89bfcf1f9](https://linux-hardware.org/?probe=d89bfcf1f9) | Aug 22, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [edc2f605d1](https://linux-hardware.org/?probe=edc2f605d1) | Aug 21, 2021 |
| ASUSTek       | Z87-EXPERT                  | [df9d84a892](https://linux-hardware.org/?probe=df9d84a892) | Aug 21, 2021 |
| MSI           | MS-B1711                    | [e7f26dd76d](https://linux-hardware.org/?probe=e7f26dd76d) | Aug 21, 2021 |
| ASUSTek       | P5VD2-VM SE                 | [be5f9f33d4](https://linux-hardware.org/?probe=be5f9f33d4) | Aug 21, 2021 |
| ASUSTek       | PRIME Z590-A                | [56700e09b7](https://linux-hardware.org/?probe=56700e09b7) | Aug 20, 2021 |
| ASUSTek       | AT5IONT-I                   | [19d0290990](https://linux-hardware.org/?probe=19d0290990) | Aug 20, 2021 |
| ASUSTek       | AT5IONT-I                   | [cddc530d88](https://linux-hardware.org/?probe=cddc530d88) | Aug 20, 2021 |
| Dell          | 0Y2K8N A01                  | [6b0fd02c91](https://linux-hardware.org/?probe=6b0fd02c91) | Aug 20, 2021 |
| MSI           | MEG X570 UNIFY              | [c4800a930a](https://linux-hardware.org/?probe=c4800a930a) | Aug 20, 2021 |
| HP            | 339A                        | [57d5bbd1e4](https://linux-hardware.org/?probe=57d5bbd1e4) | Aug 19, 2021 |
| Dell          | 0T2HR0 A00                  | [5190965eeb](https://linux-hardware.org/?probe=5190965eeb) | Aug 19, 2021 |
| ASUSTek       | P8H77-V LE                  | [dffd5d1df7](https://linux-hardware.org/?probe=dffd5d1df7) | Aug 19, 2021 |
| ASUSTek       | D520MT_D520SF_D320MT        | [5fb844180b](https://linux-hardware.org/?probe=5fb844180b) | Aug 19, 2021 |
| Gigabyte      | P55-USB3                    | [5e6a1d1926](https://linux-hardware.org/?probe=5e6a1d1926) | Aug 19, 2021 |
| Gigabyte      | F2A75M-D3H                  | [2c092a6adf](https://linux-hardware.org/?probe=2c092a6adf) | Aug 19, 2021 |
| MSI           | IONA                        | [750db2f0df](https://linux-hardware.org/?probe=750db2f0df) | Aug 18, 2021 |
| ASUSTek       | TUF Gaming X570-PRO         | [2dbf8d3544](https://linux-hardware.org/?probe=2dbf8d3544) | Aug 18, 2021 |
| ASUSTek       | A_F_K31DA_K31DAG_K20DA      | [02cd855bbb](https://linux-hardware.org/?probe=02cd855bbb) | Aug 17, 2021 |
| ASRock        | Z390 Phantom Gaming 4S      | [1524eec7a5](https://linux-hardware.org/?probe=1524eec7a5) | Aug 17, 2021 |
| Fujitsu Si... | D2840-A1 S26361-D2840-A1    | [7911fbd6a6](https://linux-hardware.org/?probe=7911fbd6a6) | Aug 17, 2021 |
| ASUSTek       | M51AC                       | [a4ea667732](https://linux-hardware.org/?probe=a4ea667732) | Aug 16, 2021 |
| Gigabyte      | Z97-D3H-CF                  | [64bc2deef1](https://linux-hardware.org/?probe=64bc2deef1) | Aug 16, 2021 |
| Gigabyte      | Z97-D3H-CF                  | [8e11283bd3](https://linux-hardware.org/?probe=8e11283bd3) | Aug 16, 2021 |
| ASUSTek       | Basswood                    | [f42051fa02](https://linux-hardware.org/?probe=f42051fa02) | Aug 15, 2021 |
| HP            | 3048h                       | [6c142e320c](https://linux-hardware.org/?probe=6c142e320c) | Aug 15, 2021 |
| Acer          | RS780DV                     | [994fc23020](https://linux-hardware.org/?probe=994fc23020) | Aug 15, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [9ab4399f8c](https://linux-hardware.org/?probe=9ab4399f8c) | Aug 15, 2021 |
| ASUSTek       | P8H67                       | [7c1b975d25](https://linux-hardware.org/?probe=7c1b975d25) | Aug 15, 2021 |
| Gigabyte      | F2A88XM-HD3                 | [b178612e9f](https://linux-hardware.org/?probe=b178612e9f) | Aug 14, 2021 |
| Gigabyte      | F2A88XM-HD3                 | [28b07ead33](https://linux-hardware.org/?probe=28b07ead33) | Aug 14, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [2e16baa112](https://linux-hardware.org/?probe=2e16baa112) | Aug 14, 2021 |
| ASUSTek       | Maximus VI HERO             | [ee8e577b6b](https://linux-hardware.org/?probe=ee8e577b6b) | Aug 14, 2021 |
| ASUSTek       | PRIME A320M-K               | [47857ab024](https://linux-hardware.org/?probe=47857ab024) | Aug 14, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [a19e04efad](https://linux-hardware.org/?probe=a19e04efad) | Aug 13, 2021 |
| Acer          | RS780DV                     | [465919d85b](https://linux-hardware.org/?probe=465919d85b) | Aug 13, 2021 |
| Gigabyte      | 970A-UD3P                   | [1993cb18b6](https://linux-hardware.org/?probe=1993cb18b6) | Aug 13, 2021 |
| HP            | 8169                        | [44501c3c18](https://linux-hardware.org/?probe=44501c3c18) | Aug 13, 2021 |
| Gigabyte      | Z68MA-D2H-B3                | [bf398306f4](https://linux-hardware.org/?probe=bf398306f4) | Aug 12, 2021 |
| Acer          | Veriton X2631G V:1.0        | [d0db0c37b0](https://linux-hardware.org/?probe=d0db0c37b0) | Aug 12, 2021 |
| Dell          | 0YJPT1 A00                  | [38822c9ed8](https://linux-hardware.org/?probe=38822c9ed8) | Aug 12, 2021 |
| MSI           | A88X-G41 PC Mate            | [709aac26c8](https://linux-hardware.org/?probe=709aac26c8) | Aug 12, 2021 |
| ASUSTek       | Z87-PLUS                    | [0b4420c0ff](https://linux-hardware.org/?probe=0b4420c0ff) | Aug 11, 2021 |
| Dell          | 0YJPT1 A00                  | [df38ee9c55](https://linux-hardware.org/?probe=df38ee9c55) | Aug 11, 2021 |
| Gigabyte      | B550M DS3H                  | [6776a424d5](https://linux-hardware.org/?probe=6776a424d5) | Aug 11, 2021 |
| Dell          | 0XGF09 A00                  | [b57ba5741a](https://linux-hardware.org/?probe=b57ba5741a) | Aug 10, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | [b8f7efb815](https://linux-hardware.org/?probe=b8f7efb815) | Aug 08, 2021 |
| ASUSTek       | G30AB                       | [007bbb69a3](https://linux-hardware.org/?probe=007bbb69a3) | Aug 07, 2021 |
| ASUSTek       | PRIME A320M-K               | [742ad08c3b](https://linux-hardware.org/?probe=742ad08c3b) | Aug 07, 2021 |
| ASUSTek       | P8P67-M PRO                 | [704ffb4b81](https://linux-hardware.org/?probe=704ffb4b81) | Aug 07, 2021 |
| ASUSTek       | G30AB                       | [22783d1f62](https://linux-hardware.org/?probe=22783d1f62) | Aug 07, 2021 |
| ASRock        | H470M-HDV/M.2               | [8be0194bc4](https://linux-hardware.org/?probe=8be0194bc4) | Aug 07, 2021 |
| ASUSTek       | P5K WS                      | [87db1e85e8](https://linux-hardware.org/?probe=87db1e85e8) | Aug 07, 2021 |
| Gigabyte      | GA-880GM-UD2H               | [b6e23e4857](https://linux-hardware.org/?probe=b6e23e4857) | Aug 07, 2021 |
| Gigabyte      | H110M-S2H-CF                | [1f0997ab64](https://linux-hardware.org/?probe=1f0997ab64) | Aug 07, 2021 |
| Acer          | Veriton X2631G V:1.0        | [7306d11e16](https://linux-hardware.org/?probe=7306d11e16) | Aug 06, 2021 |
| Shuttle       | FS81                        | [43e13eac00](https://linux-hardware.org/?probe=43e13eac00) | Aug 05, 2021 |
| Gigabyte      | G41M-Combo                  | [fcab34ee40](https://linux-hardware.org/?probe=fcab34ee40) | Aug 05, 2021 |
| Gigabyte      | X58A-UD3R                   | [a8d0a3efc9](https://linux-hardware.org/?probe=a8d0a3efc9) | Aug 05, 2021 |
| ASUSTek       | M5A78L-M LX3                | [8dedf936cf](https://linux-hardware.org/?probe=8dedf936cf) | Aug 05, 2021 |
| Gigabyte      | B150M-D2V-CF                | [ec022c7698](https://linux-hardware.org/?probe=ec022c7698) | Aug 04, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | [8ac108e44f](https://linux-hardware.org/?probe=8ac108e44f) | Aug 04, 2021 |
| Gigabyte      | H61M-S1                     | [1b395c03b8](https://linux-hardware.org/?probe=1b395c03b8) | Aug 04, 2021 |
| ASUSTek       | P5K PRO                     | [8de53a9490](https://linux-hardware.org/?probe=8de53a9490) | Aug 04, 2021 |
| ASUSTek       | P5K PRO                     | [ec6ce0a80c](https://linux-hardware.org/?probe=ec6ce0a80c) | Aug 04, 2021 |
| Gigabyte      | H61M-S1                     | [035d920e95](https://linux-hardware.org/?probe=035d920e95) | Aug 03, 2021 |
| ASUSTek       | B150M-A/M.2                 | [1a69f31e56](https://linux-hardware.org/?probe=1a69f31e56) | Aug 03, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [c2e803dd7e](https://linux-hardware.org/?probe=c2e803dd7e) | Aug 02, 2021 |
| ASUSTek       | P7P55D                      | [c62d162396](https://linux-hardware.org/?probe=c62d162396) | Aug 02, 2021 |
| HP            | 3047h                       | [18889349d1](https://linux-hardware.org/?probe=18889349d1) | Aug 02, 2021 |
| ASRock        | B550M-HDV                   | [74709057b7](https://linux-hardware.org/?probe=74709057b7) | Aug 02, 2021 |
| ASUSTek       | M5A78L-M LX3                | [89f51fb222](https://linux-hardware.org/?probe=89f51fb222) | Aug 01, 2021 |
| ASUSTek       | M5A78L-M LX3                | [1a815befe7](https://linux-hardware.org/?probe=1a815befe7) | Aug 01, 2021 |
| ASUSTek       | P6T DELUXE V2               | [51a1b8132e](https://linux-hardware.org/?probe=51a1b8132e) | Aug 01, 2021 |
| HP            | 1494                        | [23fed64f63](https://linux-hardware.org/?probe=23fed64f63) | Aug 01, 2021 |
| ASRock        | N68C-S UCC                  | [2c67644e4c](https://linux-hardware.org/?probe=2c67644e4c) | Aug 01, 2021 |
| ASRock        | 760GM-HDV                   | [279fa91266](https://linux-hardware.org/?probe=279fa91266) | Aug 01, 2021 |
| Intel         | DQ45CB AAE30148-207         | [d78c495dd8](https://linux-hardware.org/?probe=d78c495dd8) | Jul 31, 2021 |
| HP            | 1494                        | [1e2880ae34](https://linux-hardware.org/?probe=1e2880ae34) | Jul 31, 2021 |
| ASUSTek       | PRIME B450M-A               | [1f46414a9c](https://linux-hardware.org/?probe=1f46414a9c) | Jul 31, 2021 |
| ASRock        | N68C-S UCC                  | [3b4a485e30](https://linux-hardware.org/?probe=3b4a485e30) | Jul 31, 2021 |
| Dell          | 08HPGT A01                  | [0b25532f6b](https://linux-hardware.org/?probe=0b25532f6b) | Jul 30, 2021 |
| ASUSTek       | P7P55D                      | [cd96dbf86a](https://linux-hardware.org/?probe=cd96dbf86a) | Jul 30, 2021 |
| ASUSTek       | P5G41T-M LX3                | [7c3d5f062e](https://linux-hardware.org/?probe=7c3d5f062e) | Jul 30, 2021 |
| Gigabyte      | M720-US3                    | [869cada120](https://linux-hardware.org/?probe=869cada120) | Jul 30, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [bc9a454567](https://linux-hardware.org/?probe=bc9a454567) | Jul 28, 2021 |
| Shuttle       | FX79R                       | [6ceba6fc67](https://linux-hardware.org/?probe=6ceba6fc67) | Jul 28, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [e1a5d3e001](https://linux-hardware.org/?probe=e1a5d3e001) | Jul 27, 2021 |
| ASUSTek       | G11CD                       | [d9180fa6f0](https://linux-hardware.org/?probe=d9180fa6f0) | Jul 27, 2021 |
| ASUSTek       | M4A785D-M PRO               | [467d107518](https://linux-hardware.org/?probe=467d107518) | Jul 27, 2021 |
| ASUSTek       | Z87-A                       | [b417b06648](https://linux-hardware.org/?probe=b417b06648) | Jul 27, 2021 |
| Dell          | 0WMJ54 A01                  | [b24fc8e5f2](https://linux-hardware.org/?probe=b24fc8e5f2) | Jul 27, 2021 |
| ASUSTek       | Z87-A                       | [214326666c](https://linux-hardware.org/?probe=214326666c) | Jul 26, 2021 |
| ASUSTek       | Z87-A                       | [b2eca29d6c](https://linux-hardware.org/?probe=b2eca29d6c) | Jul 26, 2021 |
| ASUSTek       | Z97-K                       | [588c5ca9f6](https://linux-hardware.org/?probe=588c5ca9f6) | Jul 26, 2021 |
| ASUSTek       | Z97-K                       | [d7369d7eb4](https://linux-hardware.org/?probe=d7369d7eb4) | Jul 26, 2021 |
| ASUSTek       | Z97-P                       | [ef88333344](https://linux-hardware.org/?probe=ef88333344) | Jul 26, 2021 |
| Gigabyte      | H110M-S2H-CF                | [11c5d6c6d0](https://linux-hardware.org/?probe=11c5d6c6d0) | Jul 25, 2021 |
| Supermicro    | A1SA2-2750FA                | [de408d6408](https://linux-hardware.org/?probe=de408d6408) | Jul 25, 2021 |
| ASUSTek       | PRIME B450M-A               | [558e1369e9](https://linux-hardware.org/?probe=558e1369e9) | Jul 25, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [acc53aae10](https://linux-hardware.org/?probe=acc53aae10) | Jul 25, 2021 |
| Intel         | DN2800MT AAG23738-600       | [37b38d65e6](https://linux-hardware.org/?probe=37b38d65e6) | Jul 25, 2021 |
| MSI           | B450M MORTAR MAX            | [abe81b8f00](https://linux-hardware.org/?probe=abe81b8f00) | Jul 25, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [d8bbd9a390](https://linux-hardware.org/?probe=d8bbd9a390) | Jul 25, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [fcc85782f6](https://linux-hardware.org/?probe=fcc85782f6) | Jul 25, 2021 |
| Protectli     | FW6                         | [0efef10e76](https://linux-hardware.org/?probe=0efef10e76) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [dd3347639f](https://linux-hardware.org/?probe=dd3347639f) | Jul 25, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [f7c4474b4d](https://linux-hardware.org/?probe=f7c4474b4d) | Jul 25, 2021 |
| Intel         | DG965SS AAD41678-307        | [d3f38dbf63](https://linux-hardware.org/?probe=d3f38dbf63) | Jul 24, 2021 |
| ASUSTek       | P7P55D                      | [b983e48d71](https://linux-hardware.org/?probe=b983e48d71) | Jul 24, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [61aa66455b](https://linux-hardware.org/?probe=61aa66455b) | Jul 23, 2021 |
| AZW           | Gemini T34-M                | [ae05dd2fac](https://linux-hardware.org/?probe=ae05dd2fac) | Jul 23, 2021 |
| ASUSTek       | B85M-E                      | [fe84eda758](https://linux-hardware.org/?probe=fe84eda758) | Jul 23, 2021 |
| Gigabyte      | H110M-S2H-CF                | [18951b50fd](https://linux-hardware.org/?probe=18951b50fd) | Jul 23, 2021 |
| ASUSTek       | P7P55D                      | [2335f32be7](https://linux-hardware.org/?probe=2335f32be7) | Jul 22, 2021 |
| Dell          | 00V62H A01                  | [1e19b61594](https://linux-hardware.org/?probe=1e19b61594) | Jul 22, 2021 |
| Gigabyte      | H87M-D3H                    | [176a2484a2](https://linux-hardware.org/?probe=176a2484a2) | Jul 22, 2021 |
| Supermicro    | X8STi                       | [bb4e8a2c68](https://linux-hardware.org/?probe=bb4e8a2c68) | Jul 21, 2021 |
| Dell          | 0FM586                      | [0282db3729](https://linux-hardware.org/?probe=0282db3729) | Jul 21, 2021 |
| HP            | 876C SMVB                   | [4048e5035d](https://linux-hardware.org/?probe=4048e5035d) | Jul 21, 2021 |
| HP            | 83E1                        | [977631dbb5](https://linux-hardware.org/?probe=977631dbb5) | Jul 20, 2021 |
| ASRock        | B550 Extreme4               | [9a73f63205](https://linux-hardware.org/?probe=9a73f63205) | Jul 20, 2021 |
| AMI           | Cherry Trail CR             | [a27b2da2b9](https://linux-hardware.org/?probe=a27b2da2b9) | Jul 20, 2021 |
| MSI           | B450M PRO-VDH MAX           | [ba992e4651](https://linux-hardware.org/?probe=ba992e4651) | Jul 20, 2021 |
| Unknown       | Unknown                     | [8cfcc66d8c](https://linux-hardware.org/?probe=8cfcc66d8c) | Jul 20, 2021 |
| ASRock        | B85M-HDS                    | [9104b94412](https://linux-hardware.org/?probe=9104b94412) | Jul 19, 2021 |
| ASRock        | B85M-HDS                    | [cafe2c46f1](https://linux-hardware.org/?probe=cafe2c46f1) | Jul 19, 2021 |
| Dell          | 0TP412                      | [8788d078a0](https://linux-hardware.org/?probe=8788d078a0) | Jul 19, 2021 |
| MSI           | X370 GAMING PRO CARBON      | [2f617f0199](https://linux-hardware.org/?probe=2f617f0199) | Jul 19, 2021 |
| ASUSTek       | P8Z68-V                     | [1a60e02aa9](https://linux-hardware.org/?probe=1a60e02aa9) | Jul 19, 2021 |
| Gigabyte      | B450M DS3H-CF               | [8e540a6dfa](https://linux-hardware.org/?probe=8e540a6dfa) | Jul 19, 2021 |
| MSI           | H81M-P33                    | [8db8179a0e](https://linux-hardware.org/?probe=8db8179a0e) | Jul 19, 2021 |
| Gigabyte      | B450 AORUS ELITE V2         | [55114a067a](https://linux-hardware.org/?probe=55114a067a) | Jul 18, 2021 |
| ASUSTek       | H81M-K                      | [07e568874b](https://linux-hardware.org/?probe=07e568874b) | Jul 18, 2021 |
| MSI           | Z97-G55 SLI                 | [066f6ad76f](https://linux-hardware.org/?probe=066f6ad76f) | Jul 18, 2021 |
| Packard Be... | FMCP7AM                     | [78890894da](https://linux-hardware.org/?probe=78890894da) | Jul 18, 2021 |
| MSI           | Z97 GAMING 3                | [fb4d52b3b2](https://linux-hardware.org/?probe=fb4d52b3b2) | Jul 18, 2021 |
| Pegatron      | 2AB6                        | [b790271fac](https://linux-hardware.org/?probe=b790271fac) | Jul 18, 2021 |
| ASUSTek       | Puffer                      | [70d79984df](https://linux-hardware.org/?probe=70d79984df) | Jul 18, 2021 |
| ASUSTek       | Maximus VIII RANGER         | [3cc44e771e](https://linux-hardware.org/?probe=3cc44e771e) | Jul 17, 2021 |
| ASUSTek       | Z77-A                       | [cda477a3d2](https://linux-hardware.org/?probe=cda477a3d2) | Jul 17, 2021 |
| Dell          | 0VNP2H A00                  | [167ec81986](https://linux-hardware.org/?probe=167ec81986) | Jul 17, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [4a94a55c2d](https://linux-hardware.org/?probe=4a94a55c2d) | Jul 16, 2021 |
| Gigabyte      | GA-970A-DS3                 | [809d9eba8e](https://linux-hardware.org/?probe=809d9eba8e) | Jul 16, 2021 |
| eMachines     | WMCP61M                     | [93d91a0c0f](https://linux-hardware.org/?probe=93d91a0c0f) | Jul 16, 2021 |
| ASUSTek       | M4A785TD-V EVO              | [b833818421](https://linux-hardware.org/?probe=b833818421) | Jul 15, 2021 |
| Packard Be... | Cuba MS-7301                | [c3ac2909b9](https://linux-hardware.org/?probe=c3ac2909b9) | Jul 15, 2021 |
| ASUSTek       | P5Q TURBO                   | [571e42bf60](https://linux-hardware.org/?probe=571e42bf60) | Jul 15, 2021 |
| Packard Be... | FMCP7AM                     | [c880ee37db](https://linux-hardware.org/?probe=c880ee37db) | Jul 15, 2021 |
| Pegatron      | 2A94                        | [01258441ad](https://linux-hardware.org/?probe=01258441ad) | Jul 15, 2021 |
| Gigabyte      | PH67-DS3-B3                 | [1a9eb0a199](https://linux-hardware.org/?probe=1a9eb0a199) | Jul 15, 2021 |
| ASUSTek       | M3A-H/HDMI                  | [6c97b09b3f](https://linux-hardware.org/?probe=6c97b09b3f) | Jul 14, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [1f4a85bedb](https://linux-hardware.org/?probe=1f4a85bedb) | Jul 14, 2021 |
| ASUSTek       | V-P8H67E                    | [e0ff38374e](https://linux-hardware.org/?probe=e0ff38374e) | Jul 13, 2021 |
| ASUSTek       | PRIME A320M-K               | [cf2ad5ad23](https://linux-hardware.org/?probe=cf2ad5ad23) | Jul 13, 2021 |
| MSI           | Z87-GD65 GAMING             | [39de069b11](https://linux-hardware.org/?probe=39de069b11) | Jul 13, 2021 |
| Packard Be... | FMCP7AM                     | [ccb422130e](https://linux-hardware.org/?probe=ccb422130e) | Jul 13, 2021 |
| ASRock        | B450M-HDV R4.0              | [8f7899c59a](https://linux-hardware.org/?probe=8f7899c59a) | Jul 12, 2021 |
| MSI           | H310M PRO-M2 PLUS           | [e2b0276cb9](https://linux-hardware.org/?probe=e2b0276cb9) | Jul 11, 2021 |
| Pegatron      | Eureka3                     | [fa59bdf986](https://linux-hardware.org/?probe=fa59bdf986) | Jul 10, 2021 |
| Huanan        | X99-F8 V2.0                 | [776f848ccd](https://linux-hardware.org/?probe=776f848ccd) | Jul 09, 2021 |
| Gigabyte      | H110M-S2H-CF                | [e0f1466068](https://linux-hardware.org/?probe=e0f1466068) | Jul 09, 2021 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [36ef771a7b](https://linux-hardware.org/?probe=36ef771a7b) | Jul 09, 2021 |
| Shuttle       | FH61V                       | [57e978bf7e](https://linux-hardware.org/?probe=57e978bf7e) | Jul 09, 2021 |
| Packard Be... | 1.0                         | [23fcbae626](https://linux-hardware.org/?probe=23fcbae626) | Jul 07, 2021 |
| ASRock        | Z170 Pro4/D3                | [073c40fe0a](https://linux-hardware.org/?probe=073c40fe0a) | Jul 07, 2021 |
| MSI           | J1900I                      | [31b65c37c9](https://linux-hardware.org/?probe=31b65c37c9) | Jul 07, 2021 |
| ASUSTek       | M5A97 R2.0                  | [4bbd7fe568](https://linux-hardware.org/?probe=4bbd7fe568) | Jul 06, 2021 |
| Gigabyte      | H110M-S2V-CF                | [e0356ccd8b](https://linux-hardware.org/?probe=e0356ccd8b) | Jul 06, 2021 |
| ASUSTek       | P8H61-M LE                  | [456048c8ee](https://linux-hardware.org/?probe=456048c8ee) | Jul 06, 2021 |
| ASRock        | G41M-VS3                    | [8378aedbc0](https://linux-hardware.org/?probe=8378aedbc0) | Jul 06, 2021 |
| Unknown       | Unknown                     | [43c34f1818](https://linux-hardware.org/?probe=43c34f1818) | Jul 06, 2021 |
| MSI           | MAG Z490 TOMAHAWK           | [55996ad01c](https://linux-hardware.org/?probe=55996ad01c) | Jul 05, 2021 |
| HP            | 158A                        | [73f7cd0409](https://linux-hardware.org/?probe=73f7cd0409) | Jul 05, 2021 |
| ASUSTek       | PRIME A320M-K               | [a44525ea2d](https://linux-hardware.org/?probe=a44525ea2d) | Jul 05, 2021 |
| Gigabyte      | B450M DS3H-CF               | [21de58e8c0](https://linux-hardware.org/?probe=21de58e8c0) | Jul 05, 2021 |
| Dell          | 0T10XW A00                  | [38235d3567](https://linux-hardware.org/?probe=38235d3567) | Jul 05, 2021 |
| Alienware     | 0N4R4N A00                  | [9219336156](https://linux-hardware.org/?probe=9219336156) | Jul 04, 2021 |
| ASRock        | B450M Pro4                  | [0a99c9a4b8](https://linux-hardware.org/?probe=0a99c9a4b8) | Jul 04, 2021 |
| ASUSTek       | M4A89GTD-PRO                | [86220cd206](https://linux-hardware.org/?probe=86220cd206) | Jul 03, 2021 |
| Dell          | 0XGF09 A00                  | [cdb7bd832e](https://linux-hardware.org/?probe=cdb7bd832e) | Jul 03, 2021 |
| Gigabyte      | F2A78M-HD2                  | [7974efd1a4](https://linux-hardware.org/?probe=7974efd1a4) | Jul 03, 2021 |
| MSI           | B450I GAMING PLUS AC        | [f3c078e87b](https://linux-hardware.org/?probe=f3c078e87b) | Jul 03, 2021 |
| HP            | 2215                        | [fdcb579a89](https://linux-hardware.org/?probe=fdcb579a89) | Jul 02, 2021 |
| Acer          | Aspire TC-780               | [db439f45a3](https://linux-hardware.org/?probe=db439f45a3) | Jul 02, 2021 |
| Dell          | 09KPNV A01                  | [a3f3f1e1c0](https://linux-hardware.org/?probe=a3f3f1e1c0) | Jul 02, 2021 |
| HP            | 0B4Ch D                     | [4970123f28](https://linux-hardware.org/?probe=4970123f28) | Jul 01, 2021 |
| Dell          | 0GDG8Y A00                  | [b74d40229a](https://linux-hardware.org/?probe=b74d40229a) | Jul 01, 2021 |
| Dell          | 0KWVT8 A00                  | [485d9a5869](https://linux-hardware.org/?probe=485d9a5869) | Jul 01, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [cbda299075](https://linux-hardware.org/?probe=cbda299075) | Jul 01, 2021 |
| HP            | 2B2C                        | [a032901252](https://linux-hardware.org/?probe=a032901252) | Jul 01, 2021 |
| HP            | 3397                        | [85b6ea31ba](https://linux-hardware.org/?probe=85b6ea31ba) | Jun 30, 2021 |
| ASUSTek       | H97-PRO                     | [bd9090c48a](https://linux-hardware.org/?probe=bd9090c48a) | Jun 30, 2021 |
| ASUSTek       | P8P67 PRO                   | [795164c4e3](https://linux-hardware.org/?probe=795164c4e3) | Jun 29, 2021 |
| ASUSTek       | Z170-P D3                   | [a0a2c651ab](https://linux-hardware.org/?probe=a0a2c651ab) | Jun 29, 2021 |
| ASUSTek       | PRIME Z390-P                | [e99b341cf4](https://linux-hardware.org/?probe=e99b341cf4) | Jun 29, 2021 |
| MSI           | Z97-G55 SLI                 | [4ae1c51612](https://linux-hardware.org/?probe=4ae1c51612) | Jun 28, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [c382d2c54e](https://linux-hardware.org/?probe=c382d2c54e) | Jun 27, 2021 |
| ASUSTek       | Basswood                    | [daf1b9da91](https://linux-hardware.org/?probe=daf1b9da91) | Jun 27, 2021 |
| HP            | 1850                        | [1c89bb4a9d](https://linux-hardware.org/?probe=1c89bb4a9d) | Jun 27, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [adca4503e7](https://linux-hardware.org/?probe=adca4503e7) | Jun 27, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [1e4e8c8638](https://linux-hardware.org/?probe=1e4e8c8638) | Jun 27, 2021 |
| Gigabyte      | F2A88XM-DS2                 | [88f3b44a11](https://linux-hardware.org/?probe=88f3b44a11) | Jun 27, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [ada772c932](https://linux-hardware.org/?probe=ada772c932) | Jun 27, 2021 |
| HP            | 8436                        | [617d5e50fd](https://linux-hardware.org/?probe=617d5e50fd) | Jun 27, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [783cc8aa8e](https://linux-hardware.org/?probe=783cc8aa8e) | Jun 26, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [048336bb59](https://linux-hardware.org/?probe=048336bb59) | Jun 26, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [598db879ae](https://linux-hardware.org/?probe=598db879ae) | Jun 25, 2021 |
| ASRock        | X300M-STX                   | [e4de52b465](https://linux-hardware.org/?probe=e4de52b465) | Jun 25, 2021 |
| MSI           | B450M MORTAR TITANIUM       | [dcb1437824](https://linux-hardware.org/?probe=dcb1437824) | Jun 24, 2021 |
| ASRock        | P67 Extreme4 Gen3           | [3389bd71ff](https://linux-hardware.org/?probe=3389bd71ff) | Jun 24, 2021 |
| Intel         | DH67BL AAG10189-213         | [76f6756df6](https://linux-hardware.org/?probe=76f6756df6) | Jun 23, 2021 |
| Dell          | 0F6X5P A00                  | [a08f695bff](https://linux-hardware.org/?probe=a08f695bff) | Jun 23, 2021 |
| OEM           | B250B                       | [76ea6ec5b6](https://linux-hardware.org/?probe=76ea6ec5b6) | Jun 22, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [a347deb07c](https://linux-hardware.org/?probe=a347deb07c) | Jun 22, 2021 |
| HP            | 8459                        | [410e67ab9f](https://linux-hardware.org/?probe=410e67ab9f) | Jun 22, 2021 |
| OEM           | B250B                       | [cadd03edf3](https://linux-hardware.org/?probe=cadd03edf3) | Jun 21, 2021 |
| Unknown       | x.x                         | [a3eb153848](https://linux-hardware.org/?probe=a3eb153848) | Jun 21, 2021 |
| ASUSTek       | P8P67 PRO                   | [825bd96378](https://linux-hardware.org/?probe=825bd96378) | Jun 21, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | [08fc06c75e](https://linux-hardware.org/?probe=08fc06c75e) | Jun 20, 2021 |
| HP            | 81B3                        | [18282dbba2](https://linux-hardware.org/?probe=18282dbba2) | Jun 20, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [31458f96c8](https://linux-hardware.org/?probe=31458f96c8) | Jun 19, 2021 |
| MSI           | B85-G43                     | [4749868a2f](https://linux-hardware.org/?probe=4749868a2f) | Jun 19, 2021 |
| MSI           | B450M MORTAR MAX            | [33ffb80782](https://linux-hardware.org/?probe=33ffb80782) | Jun 19, 2021 |
| MSI           | Z77A-G43 GAMING             | [e5da744b7b](https://linux-hardware.org/?probe=e5da744b7b) | Jun 19, 2021 |
| ASUSTek       | H81M-PLUS                   | [76eecb7492](https://linux-hardware.org/?probe=76eecb7492) | Jun 18, 2021 |
| Gigabyte      | Z77-DS3H                    | [7047d636dd](https://linux-hardware.org/?probe=7047d636dd) | Jun 18, 2021 |
| Gigabyte      | B560M DS3H                  | [a9673cbf80](https://linux-hardware.org/?probe=a9673cbf80) | Jun 18, 2021 |
| Dell          | 0YXT71 A03                  | [a9b0958bdf](https://linux-hardware.org/?probe=a9b0958bdf) | Jun 17, 2021 |
| eMachines     | EL1352                      | [79e34b0adc](https://linux-hardware.org/?probe=79e34b0adc) | Jun 16, 2021 |
| eMachines     | EL1352                      | [f175ae71f2](https://linux-hardware.org/?probe=f175ae71f2) | Jun 16, 2021 |
| Gigabyte      | B450 AORUS ELITE V2         | [becb0bd4e6](https://linux-hardware.org/?probe=becb0bd4e6) | Jun 16, 2021 |
| Dell          | 0F6X5P A00                  | [4f957170f1](https://linux-hardware.org/?probe=4f957170f1) | Jun 16, 2021 |
| Dell          | 0F6X5P A00                  | [9b0c004cd8](https://linux-hardware.org/?probe=9b0c004cd8) | Jun 16, 2021 |
| Dell          | 0WR7PY A02                  | [fb27aaebe4](https://linux-hardware.org/?probe=fb27aaebe4) | Jun 15, 2021 |
| Foxconn       | 2ADA                        | [7227747abd](https://linux-hardware.org/?probe=7227747abd) | Jun 15, 2021 |
| MSI           | IONA                        | [a78e4a4750](https://linux-hardware.org/?probe=a78e4a4750) | Jun 15, 2021 |
| HP            | 3048h                       | [df1677f5da](https://linux-hardware.org/?probe=df1677f5da) | Jun 14, 2021 |
| ASUSTek       | F2A55-M LK                  | [40ba16d0f3](https://linux-hardware.org/?probe=40ba16d0f3) | Jun 13, 2021 |
| Gigabyte      | M68MT-S2                    | [b7b83eed19](https://linux-hardware.org/?probe=b7b83eed19) | Jun 12, 2021 |
| Unknown       | X79-P3                      | [8c01718379](https://linux-hardware.org/?probe=8c01718379) | Jun 12, 2021 |
| ASUSTek       | STRIX Z270E GAMING          | [704bf0bba3](https://linux-hardware.org/?probe=704bf0bba3) | Jun 12, 2021 |
| Gigabyte      | Z97MX-Gaming 5              | [2dcbc551cd](https://linux-hardware.org/?probe=2dcbc551cd) | Jun 12, 2021 |
| Gigabyte      | Z97MX-Gaming 5              | [fe086dcd5a](https://linux-hardware.org/?probe=fe086dcd5a) | Jun 12, 2021 |
| Gigabyte      | Z87M-D3H                    | [32905a1e6b](https://linux-hardware.org/?probe=32905a1e6b) | Jun 11, 2021 |
| MSI           | X370 GAMING PRO CARBON      | [4342f2eefd](https://linux-hardware.org/?probe=4342f2eefd) | Jun 11, 2021 |
| Gigabyte      | B150M-D3H-CF                | [93f4681a87](https://linux-hardware.org/?probe=93f4681a87) | Jun 10, 2021 |
| Dell          | 05WNJ2 A03                  | [e477ab6481](https://linux-hardware.org/?probe=e477ab6481) | Jun 10, 2021 |
| HP            | 843B                        | [95015678e1](https://linux-hardware.org/?probe=95015678e1) | Jun 09, 2021 |
| Acer          | Aspire XC600 v1.0           | [5ab9e6db96](https://linux-hardware.org/?probe=5ab9e6db96) | Jun 09, 2021 |
| Gigabyte      | MKLP7AP-00                  | [e0ae1815ed](https://linux-hardware.org/?probe=e0ae1815ed) | Jun 09, 2021 |
| Acer          | Aspire TC-605               | [128ff95aec](https://linux-hardware.org/?probe=128ff95aec) | Jun 09, 2021 |
| MSI           | B85-G43                     | [f520908586](https://linux-hardware.org/?probe=f520908586) | Jun 09, 2021 |
| Dell          | 0MWYPT A01                  | [fb7b10919d](https://linux-hardware.org/?probe=fb7b10919d) | Jun 09, 2021 |
| Gigabyte      | GA-880GM-D2H                | [cea39bff8b](https://linux-hardware.org/?probe=cea39bff8b) | Jun 09, 2021 |
| MSI           | X570-A PRO                  | [deea5f0b30](https://linux-hardware.org/?probe=deea5f0b30) | Jun 09, 2021 |
| ASRock        | B250M Pro4                  | [a3fd36f3a1](https://linux-hardware.org/?probe=a3fd36f3a1) | Jun 08, 2021 |
| HP            | 3397                        | [883f6f07e7](https://linux-hardware.org/?probe=883f6f07e7) | Jun 08, 2021 |
| ASUSTek       | P8Z77-V DELUXE              | [de2648c81a](https://linux-hardware.org/?probe=de2648c81a) | Jun 08, 2021 |
| ASUSTek       | P5G41T-M LX                 | [796b91b965](https://linux-hardware.org/?probe=796b91b965) | Jun 07, 2021 |
| MSI           | G41M-P26                    | [d5ae433d94](https://linux-hardware.org/?probe=d5ae433d94) | Jun 07, 2021 |
| MSI           | G41M-P26                    | [813f207c6c](https://linux-hardware.org/?probe=813f207c6c) | Jun 07, 2021 |
| Dell          | 0R790T A00                  | [2a1a642f42](https://linux-hardware.org/?probe=2a1a642f42) | Jun 06, 2021 |
| ASRock        | 880GM-LE FX                 | [a8cfccf8c9](https://linux-hardware.org/?probe=a8cfccf8c9) | Jun 06, 2021 |
| ASUSTek       | A8V Deluxe                  | [b38568681e](https://linux-hardware.org/?probe=b38568681e) | Jun 05, 2021 |
| NEC Comput... | SiS650                      | [a787298bdb](https://linux-hardware.org/?probe=a787298bdb) | Jun 05, 2021 |
| Intel         | DQ45CB AAE30148-207         | [eb1a429c65](https://linux-hardware.org/?probe=eb1a429c65) | Jun 05, 2021 |
| Intel         | DQ45CB AAE30148-207         | [344336e673](https://linux-hardware.org/?probe=344336e673) | Jun 05, 2021 |
| eMachines     | EL1352                      | [c543977660](https://linux-hardware.org/?probe=c543977660) | Jun 05, 2021 |
| Foxconn       | 2ABF                        | [11b7eb9f82](https://linux-hardware.org/?probe=11b7eb9f82) | Jun 05, 2021 |
| Pegatron      | 2AE3                        | [4be451ab41](https://linux-hardware.org/?probe=4be451ab41) | Jun 05, 2021 |
| ASUSTek       | P7P55D                      | [a45bf395ca](https://linux-hardware.org/?probe=a45bf395ca) | Jun 04, 2021 |
| ASUSTek       | 2A73h                       | [22c772be67](https://linux-hardware.org/?probe=22c772be67) | Jun 04, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [a580ef9f5c](https://linux-hardware.org/?probe=a580ef9f5c) | Jun 04, 2021 |
| ASRock        | B450M Pro4-F                | [90a9ee81f6](https://linux-hardware.org/?probe=90a9ee81f6) | Jun 04, 2021 |
| HP            | 0AE8h                       | [c2210f9f53](https://linux-hardware.org/?probe=c2210f9f53) | Jun 04, 2021 |
| Dell          | Precision T3610             | [14cd659d3d](https://linux-hardware.org/?probe=14cd659d3d) | Jun 04, 2021 |
| ASUSTek       | PRIME Z390-P                | [c0e0de26cb](https://linux-hardware.org/?probe=c0e0de26cb) | Jun 04, 2021 |
| ASUSTek       | H97-PRO                     | [dddc29e546](https://linux-hardware.org/?probe=dddc29e546) | Jun 03, 2021 |
| ASUSTek       | H97-PRO                     | [f6cbadb237](https://linux-hardware.org/?probe=f6cbadb237) | Jun 03, 2021 |
| Gigabyte      | PH67-DS3-B3                 | [5d98d7b3a5](https://linux-hardware.org/?probe=5d98d7b3a5) | Jun 03, 2021 |
| ASUSTek       | X99-E                       | [63b320d482](https://linux-hardware.org/?probe=63b320d482) | Jun 03, 2021 |
| Packard Be... | IMEDIA S2110A               | [34a921fd71](https://linux-hardware.org/?probe=34a921fd71) | Jun 03, 2021 |
| ASRock        | 760GM-HDV                   | [7da2b7b1bb](https://linux-hardware.org/?probe=7da2b7b1bb) | Jun 03, 2021 |
| MSI           | B85-G41 PC Mate             | [ce4078a2fb](https://linux-hardware.org/?probe=ce4078a2fb) | Jun 02, 2021 |
| HP            | 1495                        | [6bcbd544ee](https://linux-hardware.org/?probe=6bcbd544ee) | Jun 02, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [40545ef53f](https://linux-hardware.org/?probe=40545ef53f) | Jun 02, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [f4ce6e2f6a](https://linux-hardware.org/?probe=f4ce6e2f6a) | Jun 02, 2021 |
| ASUSTek       | H81M-PLUS                   | [59f96992d1](https://linux-hardware.org/?probe=59f96992d1) | Jun 01, 2021 |
| ASUSTek       | PRIME Z270-A                | [b477237e52](https://linux-hardware.org/?probe=b477237e52) | Jun 01, 2021 |
| ASUSTek       | PRIME Z390-P                | [75cd860063](https://linux-hardware.org/?probe=75cd860063) | Jun 01, 2021 |
| Gigabyte      | 990XA-UD3                   | [77fcb9cf4a](https://linux-hardware.org/?probe=77fcb9cf4a) | Jun 01, 2021 |
| Gigabyte      | B450 AORUS ELITE V2         | [ee70388997](https://linux-hardware.org/?probe=ee70388997) | May 31, 2021 |
| ASUSTek       | H97M-E                      | [0d40daa834](https://linux-hardware.org/?probe=0d40daa834) | May 31, 2021 |
| Medion        | MS-7616                     | [c3730db7dd](https://linux-hardware.org/?probe=c3730db7dd) | May 31, 2021 |
| Lenovo        | 3102 NOK                    | [3d1a8cffc3](https://linux-hardware.org/?probe=3d1a8cffc3) | May 31, 2021 |
| Dell          | 00V62H A01                  | [0fc3abdb1c](https://linux-hardware.org/?probe=0fc3abdb1c) | May 31, 2021 |
| ASUSTek       | P5B-Deluxe                  | [926229be87](https://linux-hardware.org/?probe=926229be87) | May 31, 2021 |
| MSI           | H170 GAMING M3              | [8b15965a17](https://linux-hardware.org/?probe=8b15965a17) | May 30, 2021 |
| ASRock        | A520M-ITX/ac                | [cef790f685](https://linux-hardware.org/?probe=cef790f685) | May 29, 2021 |
| MSI           | Z170M MORTAR                | [8502ea76c6](https://linux-hardware.org/?probe=8502ea76c6) | May 29, 2021 |
| Gigabyte      | B75M-D3H                    | [f55f5434e6](https://linux-hardware.org/?probe=f55f5434e6) | May 29, 2021 |
| Gigabyte      | B75M-D3H                    | [3f196ad923](https://linux-hardware.org/?probe=3f196ad923) | May 29, 2021 |
| MSI           | Z170M MORTAR                | [ec7a65fcba](https://linux-hardware.org/?probe=ec7a65fcba) | May 29, 2021 |
| MSI           | B350 PC MATE                | [d640900b8a](https://linux-hardware.org/?probe=d640900b8a) | May 29, 2021 |
| MSI           | B350 PC MATE                | [f7942b9c3e](https://linux-hardware.org/?probe=f7942b9c3e) | May 29, 2021 |
| MSI           | B450I GAMING PLUS AC        | [d03d2796a0](https://linux-hardware.org/?probe=d03d2796a0) | May 29, 2021 |
| MSI           | B450I GAMING PLUS AC        | [200072e2a7](https://linux-hardware.org/?probe=200072e2a7) | May 29, 2021 |
| Gigabyte      | G41M-Combo                  | [bd17f8fbd9](https://linux-hardware.org/?probe=bd17f8fbd9) | May 29, 2021 |
| ASUSTek       | GL12CX                      | [d95dd524bc](https://linux-hardware.org/?probe=d95dd524bc) | May 28, 2021 |
| ASUSTek       | PRIME Z390-P                | [243cdc0172](https://linux-hardware.org/?probe=243cdc0172) | May 28, 2021 |
| Shuttle       | FS81                        | [5a326e0155](https://linux-hardware.org/?probe=5a326e0155) | May 27, 2021 |
| ASUSTek       | P7P55D                      | [73fab078b8](https://linux-hardware.org/?probe=73fab078b8) | May 27, 2021 |
| ASUSTek       | P7P55D                      | [345ff7d041](https://linux-hardware.org/?probe=345ff7d041) | May 27, 2021 |
| Gigabyte      | M4HM87P-00                  | [08b08dc8d9](https://linux-hardware.org/?probe=08b08dc8d9) | May 27, 2021 |
| ASUSTek       | PRIME Z390-P                | [9f58a0f0bf](https://linux-hardware.org/?probe=9f58a0f0bf) | May 26, 2021 |
| ASUSTek       | H81I-PLUS                   | [8ca4919b3c](https://linux-hardware.org/?probe=8ca4919b3c) | May 26, 2021 |
| Gigabyte      | GA-MA785GM-US2H             | [775e4d5b91](https://linux-hardware.org/?probe=775e4d5b91) | May 26, 2021 |
| ASUSTek       | H170M-E D3                  | [3814a57318](https://linux-hardware.org/?probe=3814a57318) | May 26, 2021 |
| HP            | 3397                        | [de611cdb9f](https://linux-hardware.org/?probe=de611cdb9f) | May 26, 2021 |
| ASUSTek       | STRIX H270I GAMING          | [5989c34ed4](https://linux-hardware.org/?probe=5989c34ed4) | May 25, 2021 |
| Packard Be... | MCP73PV                     | [212fd0c495](https://linux-hardware.org/?probe=212fd0c495) | May 25, 2021 |
| ASRock        | H110M-ITX/ac                | [f03f0287f4](https://linux-hardware.org/?probe=f03f0287f4) | May 24, 2021 |
| MSI           | H310M PRO-M2 PLUS           | [123b35c040](https://linux-hardware.org/?probe=123b35c040) | May 24, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [18a85dba7a](https://linux-hardware.org/?probe=18a85dba7a) | May 24, 2021 |
| ASUSTek       | PRIME X570-PRO              | [ff5199d25c](https://linux-hardware.org/?probe=ff5199d25c) | May 24, 2021 |
| ASUSTek       | M4N68T V2                   | [21992da49b](https://linux-hardware.org/?probe=21992da49b) | May 23, 2021 |
| AZW           | AP35                        | [7c30c0c3ca](https://linux-hardware.org/?probe=7c30c0c3ca) | May 22, 2021 |
| Foxconn       | 2ADA                        | [26ad7625f4](https://linux-hardware.org/?probe=26ad7625f4) | May 22, 2021 |
| Gigabyte      | G41MT-S2                    | [0b430ac76e](https://linux-hardware.org/?probe=0b430ac76e) | May 22, 2021 |
| Alienware     | 0PGRP5 A01                  | [54c021054a](https://linux-hardware.org/?probe=54c021054a) | May 21, 2021 |
| ASUSTek       | P8H61-I LX/RM/SI            | [67cc04ed57](https://linux-hardware.org/?probe=67cc04ed57) | May 21, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | [3579e0c2c1](https://linux-hardware.org/?probe=3579e0c2c1) | May 21, 2021 |
| Gigabyte      | F2A88XM-DS2                 | [91962c3998](https://linux-hardware.org/?probe=91962c3998) | May 20, 2021 |
| Unknown       | Unknown                     | [1713150242](https://linux-hardware.org/?probe=1713150242) | May 20, 2021 |
| Gigabyte      | F2A88XM-DS2                 | [83945bef1b](https://linux-hardware.org/?probe=83945bef1b) | May 19, 2021 |
| Gigabyte      | B450M DS3H-CF               | [5bd94422d2](https://linux-hardware.org/?probe=5bd94422d2) | May 19, 2021 |
| ASUSTek       | Z87-C                       | [90f950c23b](https://linux-hardware.org/?probe=90f950c23b) | May 19, 2021 |
| ASUSTek       | V-P8H67E                    | [e8f0220bba](https://linux-hardware.org/?probe=e8f0220bba) | May 19, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [fec75a202e](https://linux-hardware.org/?probe=fec75a202e) | May 19, 2021 |
| Gigabyte      | Z87X-UD5H-CF                | [a2454fcd1f](https://linux-hardware.org/?probe=a2454fcd1f) | May 19, 2021 |
| Gigabyte      | G41MT-S2                    | [11bc06ce52](https://linux-hardware.org/?probe=11bc06ce52) | May 19, 2021 |
| MSI           | MEG X299 CREATION           | [c9ec042c96](https://linux-hardware.org/?probe=c9ec042c96) | May 19, 2021 |
| ASUSTek       | H81-PLUS                    | [fcc92ae0ad](https://linux-hardware.org/?probe=fcc92ae0ad) | May 19, 2021 |
| Foxconn       | 2ADA                        | [c1932872e1](https://linux-hardware.org/?probe=c1932872e1) | May 18, 2021 |
| Acer          | C-AXC-605                   | [7f9d35f468](https://linux-hardware.org/?probe=7f9d35f468) | May 18, 2021 |
| HP            | 3047h                       | [6ef9869544](https://linux-hardware.org/?probe=6ef9869544) | May 18, 2021 |
| ASRock        | B550 Extreme4               | [38fe00e843](https://linux-hardware.org/?probe=38fe00e843) | May 18, 2021 |
| ASRock        | B550 Extreme4               | [6c7317e728](https://linux-hardware.org/?probe=6c7317e728) | May 18, 2021 |
| MSI           | Z97 GAMING 3                | [cb9d4b0462](https://linux-hardware.org/?probe=cb9d4b0462) | May 18, 2021 |
| Gigabyte      | 970A-DS3P                   | [ff7e2b9ffd](https://linux-hardware.org/?probe=ff7e2b9ffd) | May 17, 2021 |
| Dell          | 0VHRW1 A03                  | [1ac850d5b7](https://linux-hardware.org/?probe=1ac850d5b7) | May 17, 2021 |
| Gigabyte      | G33M-S2                     | [d0dd5188ee](https://linux-hardware.org/?probe=d0dd5188ee) | May 16, 2021 |
| Lenovo        | Dory CRB                    | [03488bcb96](https://linux-hardware.org/?probe=03488bcb96) | May 16, 2021 |
| Acer          | RS780DV                     | [891ec8399c](https://linux-hardware.org/?probe=891ec8399c) | May 15, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [dec38c20c6](https://linux-hardware.org/?probe=dec38c20c6) | May 15, 2021 |
| ASUSTek       | PRIME Z390-P                | [00a90e02e9](https://linux-hardware.org/?probe=00a90e02e9) | May 15, 2021 |
| ASUSTek       | F2A55-M LE                  | [c21ee50e9e](https://linux-hardware.org/?probe=c21ee50e9e) | May 15, 2021 |
| Gigabyte      | PH67-DS3-B3                 | [0179ef402f](https://linux-hardware.org/?probe=0179ef402f) | May 15, 2021 |
| Gigabyte      | 970A-DS3P                   | [93ce6f702d](https://linux-hardware.org/?probe=93ce6f702d) | May 15, 2021 |
| ASUSTek       | PRIME B250M-K               | [09b5a12bde](https://linux-hardware.org/?probe=09b5a12bde) | May 15, 2021 |
| Lenovo        | XXXX 2222222                | [97391ddd40](https://linux-hardware.org/?probe=97391ddd40) | May 14, 2021 |
| HP            | 2B2C                        | [7358e30bef](https://linux-hardware.org/?probe=7358e30bef) | May 14, 2021 |
| ASUSTek       | H170I-PRO                   | [ee52a7df5c](https://linux-hardware.org/?probe=ee52a7df5c) | May 14, 2021 |
| ASUSTek       | H170I-PRO                   | [743878c784](https://linux-hardware.org/?probe=743878c784) | May 14, 2021 |
| ASUSTek       | PRIME H310T R2.0            | [a9ce752f06](https://linux-hardware.org/?probe=a9ce752f06) | May 14, 2021 |
| ASUSTek       | NCL-DS                      | [c6ef12178f](https://linux-hardware.org/?probe=c6ef12178f) | May 14, 2021 |
| MSI           | GF615M-P33 V2               | [6f22f99f9f](https://linux-hardware.org/?probe=6f22f99f9f) | May 14, 2021 |
| MSI           | H61M-E33                    | [23d2285e8a](https://linux-hardware.org/?probe=23d2285e8a) | May 13, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [bbefe7273f](https://linux-hardware.org/?probe=bbefe7273f) | May 13, 2021 |
| Gigabyte      | PH67-DS3-B3                 | [a5ac6bf1e0](https://linux-hardware.org/?probe=a5ac6bf1e0) | May 13, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [b925797f6d](https://linux-hardware.org/?probe=b925797f6d) | May 12, 2021 |
| Gigabyte      | PH67-DS3-B3                 | [acebfd2f44](https://linux-hardware.org/?probe=acebfd2f44) | May 12, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [bb658b6811](https://linux-hardware.org/?probe=bb658b6811) | May 10, 2021 |
| MSI           | H61MA-E35                   | [54ca4978d0](https://linux-hardware.org/?probe=54ca4978d0) | May 10, 2021 |
| Acer          | RS780DV                     | [ccaa0d800f](https://linux-hardware.org/?probe=ccaa0d800f) | May 10, 2021 |
| Dell          | 0D6H9T A03                  | [48ec3c90d2](https://linux-hardware.org/?probe=48ec3c90d2) | May 09, 2021 |
| MSI           | A68HM-P33 V2                | [4dc951c5ed](https://linux-hardware.org/?probe=4dc951c5ed) | May 09, 2021 |
| ASUSTek       | P8H67-M                     | [f769807d6d](https://linux-hardware.org/?probe=f769807d6d) | May 08, 2021 |
| ASRock        | B450M Steel Legend          | [7f812a2df5](https://linux-hardware.org/?probe=7f812a2df5) | May 08, 2021 |
| HP            | 09F8h                       | [88de1576e5](https://linux-hardware.org/?probe=88de1576e5) | May 08, 2021 |
| MSI           | A320M BAZOOKA               | [567b2fa307](https://linux-hardware.org/?probe=567b2fa307) | May 08, 2021 |
| ASUSTek       | M5A99X EVO                  | [b9c914324d](https://linux-hardware.org/?probe=b9c914324d) | May 07, 2021 |
| ASRock        | X570 Taichi                 | [a0c245e667](https://linux-hardware.org/?probe=a0c245e667) | May 07, 2021 |
| Lenovo        | ThinkCentre A70z 1165AEG    | [96e6c99f83](https://linux-hardware.org/?probe=96e6c99f83) | May 07, 2021 |
| Gigabyte      | H55M-D2H                    | [3f02dd61e1](https://linux-hardware.org/?probe=3f02dd61e1) | May 07, 2021 |
| HP            | 09F8h                       | [9d6ad317f4](https://linux-hardware.org/?probe=9d6ad317f4) | May 07, 2021 |
| Dell          | 0N4YC8 A00                  | [68cf0770aa](https://linux-hardware.org/?probe=68cf0770aa) | May 06, 2021 |
| ASRock        | N68C-S UCC                  | [6655939154](https://linux-hardware.org/?probe=6655939154) | May 06, 2021 |
| MSI           | H110M PRO-VD                | [86167086f7](https://linux-hardware.org/?probe=86167086f7) | May 06, 2021 |
| ASRock        | Z87 Extreme9/ac             | [7275134ee3](https://linux-hardware.org/?probe=7275134ee3) | May 05, 2021 |
| Dell          | 0NC2VH A01                  | [23c98ab77c](https://linux-hardware.org/?probe=23c98ab77c) | May 04, 2021 |
| Intel         | DN2800MT AAG81515-900       | [ac8e827d44](https://linux-hardware.org/?probe=ac8e827d44) | May 04, 2021 |
| MSI           | B350I PRO AC                | [db10576980](https://linux-hardware.org/?probe=db10576980) | May 04, 2021 |
| ASUSTek       | M4A79XTD EVO                | [4bf4556f96](https://linux-hardware.org/?probe=4bf4556f96) | May 03, 2021 |
| ASUSTek       | M4A785TD-M EVO              | [6509f2af70](https://linux-hardware.org/?probe=6509f2af70) | May 03, 2021 |
| ASUSTek       | PRIME Z590-A                | [efdac3411b](https://linux-hardware.org/?probe=efdac3411b) | May 03, 2021 |
| HP            | 198E                        | [396de7f15d](https://linux-hardware.org/?probe=396de7f15d) | May 03, 2021 |
| ASRock        | 960GC-GS FX                 | [8d4dbb05c3](https://linux-hardware.org/?probe=8d4dbb05c3) | May 03, 2021 |
| MSI           | Z77A-G43 GAMING             | [cdfa14b0cd](https://linux-hardware.org/?probe=cdfa14b0cd) | May 03, 2021 |
| ASUSTek       | PRIME H410I-PLUS            | [fd65650f77](https://linux-hardware.org/?probe=fd65650f77) | May 02, 2021 |
| MSI           | H67MA-E35                   | [1b86c3e879](https://linux-hardware.org/?probe=1b86c3e879) | May 02, 2021 |
| ASUSTek       | Maximus VIII RANGER         | [41d3825923](https://linux-hardware.org/?probe=41d3825923) | May 02, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [62c1d1c377](https://linux-hardware.org/?probe=62c1d1c377) | May 02, 2021 |
| ASUSTek       | Maximus VIII RANGER         | [67d4f3b674](https://linux-hardware.org/?probe=67d4f3b674) | May 02, 2021 |
| MSI           | B75A-G43                    | [e024b40c46](https://linux-hardware.org/?probe=e024b40c46) | May 01, 2021 |
| Dell          | 040DDP A01                  | [09afa10520](https://linux-hardware.org/?probe=09afa10520) | May 01, 2021 |
| MSI           | B450-A PRO MAX              | [973aaf91ee](https://linux-hardware.org/?probe=973aaf91ee) | May 01, 2021 |
| MSI           | P35 Platinum                | [ae45ab5c00](https://linux-hardware.org/?probe=ae45ab5c00) | May 01, 2021 |
| MSI           | P35 Platinum                | [d4353cc43f](https://linux-hardware.org/?probe=d4353cc43f) | May 01, 2021 |
| HP            | 158A                        | [2fac0fa486](https://linux-hardware.org/?probe=2fac0fa486) | May 01, 2021 |
| Gigabyte      | GA-A75M-UD2H                | [978057058a](https://linux-hardware.org/?probe=978057058a) | May 01, 2021 |
| ASUSTek       | P6T SE                      | [a2fb8f6b18](https://linux-hardware.org/?probe=a2fb8f6b18) | May 01, 2021 |
| Dell          | 0D28YY A03                  | [0408dbd954](https://linux-hardware.org/?probe=0408dbd954) | Apr 30, 2021 |
| HP            | 18E5                        | [8c8ed10c09](https://linux-hardware.org/?probe=8c8ed10c09) | Apr 30, 2021 |
| Pegatron      | 2AB6                        | [56ed9fd483](https://linux-hardware.org/?probe=56ed9fd483) | Apr 30, 2021 |
| ASUSTek       | X79-DELUXE                  | [54c1a7c393](https://linux-hardware.org/?probe=54c1a7c393) | Apr 30, 2021 |
| Unknown       | X79-P3                      | [9ceaa2839b](https://linux-hardware.org/?probe=9ceaa2839b) | Apr 30, 2021 |
| ASUSTek       | PRIME X570-PRO              | [88b8ca6dbe](https://linux-hardware.org/?probe=88b8ca6dbe) | Apr 30, 2021 |
| ASUSTek       | PRIME X570-PRO              | [be1a846088](https://linux-hardware.org/?probe=be1a846088) | Apr 30, 2021 |
| ASUSTek       | P5GC-MX/1333                | [9088160499](https://linux-hardware.org/?probe=9088160499) | Apr 30, 2021 |
| ASUSTek       | P5GC-MX/1333                | [7feaa72545](https://linux-hardware.org/?probe=7feaa72545) | Apr 30, 2021 |
| Gigabyte      | Z87-D3HP-CF                 | [a93721363c](https://linux-hardware.org/?probe=a93721363c) | Apr 29, 2021 |
| Gigabyte      | Z87-D3HP-CF                 | [780cd0596c](https://linux-hardware.org/?probe=780cd0596c) | Apr 28, 2021 |
| HP            | 2B36                        | [6458f2da90](https://linux-hardware.org/?probe=6458f2da90) | Apr 28, 2021 |
| Gigabyte      | GA-A75-UD4H                 | [7a9cf3fd0c](https://linux-hardware.org/?probe=7a9cf3fd0c) | Apr 28, 2021 |
| Gigabyte      | H170-HD3-CF                 | [2ffdc89c2a](https://linux-hardware.org/?probe=2ffdc89c2a) | Apr 28, 2021 |
| Gigabyte      | Z390 GAMING SLI-CF          | [50f8ddb45c](https://linux-hardware.org/?probe=50f8ddb45c) | Apr 28, 2021 |
| ASRock        | H81 Pro BTC R2.0            | [7fd75986b4](https://linux-hardware.org/?probe=7fd75986b4) | Apr 28, 2021 |
| MSI           | B450M-A PRO MAX             | [40f6803170](https://linux-hardware.org/?probe=40f6803170) | Apr 28, 2021 |
| Lenovo        | ThinkCentre A70z 1165AEG    | [728347c38c](https://linux-hardware.org/?probe=728347c38c) | Apr 27, 2021 |
| Packard Be... | IMEDIA S1350                | [781d544a3e](https://linux-hardware.org/?probe=781d544a3e) | Apr 27, 2021 |
| MSI           | B350M GAMING PRO            | [1a70d53d57](https://linux-hardware.org/?probe=1a70d53d57) | Apr 27, 2021 |
| Dell          | 0GN6JF A01                  | [80e68a5c66](https://linux-hardware.org/?probe=80e68a5c66) | Apr 27, 2021 |
| Foxconn       | 2ADA                        | [5c97427daa](https://linux-hardware.org/?probe=5c97427daa) | Apr 26, 2021 |
| Foxconn       | 2ADA                        | [048d6f18a3](https://linux-hardware.org/?probe=048d6f18a3) | Apr 26, 2021 |
| HP            | 18E7                        | [1300ea6a53](https://linux-hardware.org/?probe=1300ea6a53) | Apr 26, 2021 |
| Lenovo        | 36EE SDK0J40700 WIN 3258... | [16aa72ef55](https://linux-hardware.org/?probe=16aa72ef55) | Apr 26, 2021 |
| Gigabyte      | H61M-USB3V                  | [a3a8c3f6d6](https://linux-hardware.org/?probe=a3a8c3f6d6) | Apr 26, 2021 |
| Dell          | 0M5DCD A00                  | [6c6ddd36c9](https://linux-hardware.org/?probe=6c6ddd36c9) | Apr 26, 2021 |
| MSI           | Boston                      | [5cca21c281](https://linux-hardware.org/?probe=5cca21c281) | Apr 26, 2021 |
| Acer          | FC51GM                      | [ace5e495f5](https://linux-hardware.org/?probe=ace5e495f5) | Apr 26, 2021 |
| ASUSTek       | P8Z77-M                     | [8495ecf36e](https://linux-hardware.org/?probe=8495ecf36e) | Apr 26, 2021 |
| ASUSTek       | H81M-PLUS                   | [c35521c972](https://linux-hardware.org/?probe=c35521c972) | Apr 26, 2021 |
| ASUSTek       | P5Q DELUXE                  | [145106a409](https://linux-hardware.org/?probe=145106a409) | Apr 25, 2021 |
| ASUSTek       | P8H77-M LE                  | [289b0a89c0](https://linux-hardware.org/?probe=289b0a89c0) | Apr 25, 2021 |
| Lenovo        | 30BE SDK0K17763 WIN 1801... | [0f8266989e](https://linux-hardware.org/?probe=0f8266989e) | Apr 24, 2021 |
| AMI           | Cherry Trail CR             | [df3ffa30c9](https://linux-hardware.org/?probe=df3ffa30c9) | Apr 24, 2021 |
| ASUSTek       | P6X58D-E                    | [5a1a9434a2](https://linux-hardware.org/?probe=5a1a9434a2) | Apr 24, 2021 |
| ASUSTek       | VC66                        | [6158b04856](https://linux-hardware.org/?probe=6158b04856) | Apr 24, 2021 |
| Unknown       | Unknown                     | [160f692db0](https://linux-hardware.org/?probe=160f692db0) | Apr 23, 2021 |
| Gigabyte      | G31M-ES2L                   | [84b9adcb37](https://linux-hardware.org/?probe=84b9adcb37) | Apr 23, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | [efce67d492](https://linux-hardware.org/?probe=efce67d492) | Apr 22, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [e707b18e13](https://linux-hardware.org/?probe=e707b18e13) | Apr 22, 2021 |
| ASUSTek       | ROG Maximus X HERO          | [95caa8f42f](https://linux-hardware.org/?probe=95caa8f42f) | Apr 21, 2021 |
| ASUSTek       | H81T                        | [162aebd4db](https://linux-hardware.org/?probe=162aebd4db) | Apr 20, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [f456137399](https://linux-hardware.org/?probe=f456137399) | Apr 20, 2021 |
| Gigabyte      | B85M-D3H                    | [1bcff94731](https://linux-hardware.org/?probe=1bcff94731) | Apr 20, 2021 |
| ASUSTek       | ROG Maximus X HERO          | [3a850efa15](https://linux-hardware.org/?probe=3a850efa15) | Apr 20, 2021 |
| ASUSTek       | P5Q DELUXE                  | [8ab143ec6b](https://linux-hardware.org/?probe=8ab143ec6b) | Apr 20, 2021 |
| MSI           | X370 GAMING PRO CARBON      | [a7510be467](https://linux-hardware.org/?probe=a7510be467) | Apr 20, 2021 |
| MSI           | X370 GAMING PRO CARBON      | [b34f45f6f4](https://linux-hardware.org/?probe=b34f45f6f4) | Apr 20, 2021 |
| MSI           | X370 GAMING PRO CARBON      | [f87f88a5c4](https://linux-hardware.org/?probe=f87f88a5c4) | Apr 20, 2021 |
| MSI           | 770-G45                     | [85ebceeb24](https://linux-hardware.org/?probe=85ebceeb24) | Apr 20, 2021 |
| Acer          | Aspire M5910                | [6db90c645b](https://linux-hardware.org/?probe=6db90c645b) | Apr 19, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [cf4d5786e5](https://linux-hardware.org/?probe=cf4d5786e5) | Apr 19, 2021 |
| HP            | 158A                        | [8e149f0d98](https://linux-hardware.org/?probe=8e149f0d98) | Apr 18, 2021 |
| Acer          | Aspire XC600 v1.0           | [19db7f16f4](https://linux-hardware.org/?probe=19db7f16f4) | Apr 18, 2021 |
| Lenovo        | ThinkCentre A70z 1165AEG    | [2fb025fbba](https://linux-hardware.org/?probe=2fb025fbba) | Apr 18, 2021 |
| Dell          | 0KRC95 A03                  | [61da77da82](https://linux-hardware.org/?probe=61da77da82) | Apr 18, 2021 |
| ASRock        | B550 Extreme4               | [c49e659e03](https://linux-hardware.org/?probe=c49e659e03) | Apr 17, 2021 |
| ASRock        | B550 Extreme4               | [a221421eba](https://linux-hardware.org/?probe=a221421eba) | Apr 17, 2021 |
| MSI           | 760GM-P34                   | [3973833aaa](https://linux-hardware.org/?probe=3973833aaa) | Apr 17, 2021 |
| ASUSTek       | G11CD                       | [2c36061530](https://linux-hardware.org/?probe=2c36061530) | Apr 17, 2021 |
| MSI           | X470 GAMING PRO             | [a47e1c40ec](https://linux-hardware.org/?probe=a47e1c40ec) | Apr 17, 2021 |
| ASUSTek       | M2N68-VM                    | [611ca83c61](https://linux-hardware.org/?probe=611ca83c61) | Apr 17, 2021 |
| ASUSTek       | M2N68-VM                    | [cc3fcf1a7e](https://linux-hardware.org/?probe=cc3fcf1a7e) | Apr 17, 2021 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | [289a9d70d9](https://linux-hardware.org/?probe=289a9d70d9) | Apr 17, 2021 |
| Acer          | F690GVM                     | [0cc39aaf3a](https://linux-hardware.org/?probe=0cc39aaf3a) | Apr 17, 2021 |
| Gigabyte      | H170-HD3-CF                 | [f103eefd66](https://linux-hardware.org/?probe=f103eefd66) | Apr 17, 2021 |
| Gigabyte      | Z390 GAMING SLI-CF          | [e802fc9ff5](https://linux-hardware.org/?probe=e802fc9ff5) | Apr 17, 2021 |
| Acer          | F690GVM                     | [4929b0e708](https://linux-hardware.org/?probe=4929b0e708) | Apr 16, 2021 |
| ASRock        | G41M-VS3                    | [22a1791862](https://linux-hardware.org/?probe=22a1791862) | Apr 16, 2021 |
| Gigabyte      | AX370-Gaming K3             | [edf7620418](https://linux-hardware.org/?probe=edf7620418) | Apr 16, 2021 |
| ASUSTek       | Z170-P                      | [9b7d4d668c](https://linux-hardware.org/?probe=9b7d4d668c) | Apr 16, 2021 |
| ASUSTek       | B85M-G                      | [d25ec1d53c](https://linux-hardware.org/?probe=d25ec1d53c) | Apr 14, 2021 |
| ASUSTek       | P8H67-M PRO                 | [afadb6e29d](https://linux-hardware.org/?probe=afadb6e29d) | Apr 14, 2021 |
| ASUSTek       | P8H67-M PRO                 | [1f2927f37e](https://linux-hardware.org/?probe=1f2927f37e) | Apr 14, 2021 |
| ASUSTek       | P5Q-PRO                     | [dfa626566e](https://linux-hardware.org/?probe=dfa626566e) | Apr 14, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [8e6097fc59](https://linux-hardware.org/?probe=8e6097fc59) | Apr 14, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [5dfd466b51](https://linux-hardware.org/?probe=5dfd466b51) | Apr 13, 2021 |
| ASRock        | X79 Extreme4-M              | [80d1c14a8c](https://linux-hardware.org/?probe=80d1c14a8c) | Apr 13, 2021 |
| ASUSTek       | H170I-PRO                   | [62d1af2caf](https://linux-hardware.org/?probe=62d1af2caf) | Apr 13, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [f219a8eaaa](https://linux-hardware.org/?probe=f219a8eaaa) | Apr 12, 2021 |
| ASUSTek       | P5Q-PRO                     | [5a020eec30](https://linux-hardware.org/?probe=5a020eec30) | Apr 12, 2021 |
| ASUSTek       | P8Z68-V PRO GEN3            | [824778b869](https://linux-hardware.org/?probe=824778b869) | Apr 12, 2021 |
| ASUSTek       | STRIX H270F GAMING          | [db9b0573be](https://linux-hardware.org/?probe=db9b0573be) | Apr 12, 2021 |
| Packard Be... | FMP55                       | [f6854b9e96](https://linux-hardware.org/?probe=f6854b9e96) | Apr 11, 2021 |
| Lenovo        | 0B98401 PRO                 | [a96caef923](https://linux-hardware.org/?probe=a96caef923) | Apr 11, 2021 |
| ASUSTek       | M4A79XTD EVO                | [d76708221f](https://linux-hardware.org/?probe=d76708221f) | Apr 11, 2021 |
| ASUSTek       | P8P67                       | [71000e5ea9](https://linux-hardware.org/?probe=71000e5ea9) | Apr 11, 2021 |
| ASUSTek       | P8H77-M                     | [b58618df73](https://linux-hardware.org/?probe=b58618df73) | Apr 11, 2021 |
| ASRock        | B550M-HDV                   | [72d0111934](https://linux-hardware.org/?probe=72d0111934) | Apr 11, 2021 |
| Gigabyte      | B150M-D3H-CF                | [b904f5b89c](https://linux-hardware.org/?probe=b904f5b89c) | Apr 11, 2021 |
| Gigabyte      | Z68P-DS3                    | [1a27d885fc](https://linux-hardware.org/?probe=1a27d885fc) | Apr 10, 2021 |
| Acer          | RS880M05                    | [0b8b3991a7](https://linux-hardware.org/?probe=0b8b3991a7) | Apr 10, 2021 |
| MSI           | B250M BAZOOKA               | [12b526716f](https://linux-hardware.org/?probe=12b526716f) | Apr 10, 2021 |
| MSI           | B250M BAZOOKA               | [a2302afc9e](https://linux-hardware.org/?probe=a2302afc9e) | Apr 10, 2021 |
| MSI           | B360 GAMING PLUS            | [a9178f9852](https://linux-hardware.org/?probe=a9178f9852) | Apr 10, 2021 |
| ASRock        | C2550D4I                    | [c881809c02](https://linux-hardware.org/?probe=c881809c02) | Apr 09, 2021 |
| ASRockRack    | E3C232D2I                   | [5f8788ee08](https://linux-hardware.org/?probe=5f8788ee08) | Apr 09, 2021 |
| ASUSTek       | PRIME H270M-PLUS            | [07427b8218](https://linux-hardware.org/?probe=07427b8218) | Apr 09, 2021 |
| ASUSTek       | P5VD2-VM SE                 | [922a324d57](https://linux-hardware.org/?probe=922a324d57) | Apr 09, 2021 |
| ASRock        | X370 Gaming X               | [ec2915656d](https://linux-hardware.org/?probe=ec2915656d) | Apr 09, 2021 |
| Gigabyte      | H97-HD3                     | [6e7b795b09](https://linux-hardware.org/?probe=6e7b795b09) | Apr 09, 2021 |
| Gigabyte      | B450M DS3H-CF               | [a551f985b0](https://linux-hardware.org/?probe=a551f985b0) | Apr 09, 2021 |
| ASUSTek       | Maximus VII HERO            | [f1bdcd63e8](https://linux-hardware.org/?probe=f1bdcd63e8) | Apr 09, 2021 |
| Lenovo        | 0C48431 PRO                 | [168c88c35b](https://linux-hardware.org/?probe=168c88c35b) | Apr 08, 2021 |
| DFI           | LP BI P45-T2S Elite         | [01f0babd70](https://linux-hardware.org/?probe=01f0babd70) | Apr 08, 2021 |
| HP            | EG157AA-ABF m1260.fr        | [cf4f87aefd](https://linux-hardware.org/?probe=cf4f87aefd) | Apr 08, 2021 |
| ASUSTek       | P7P55D-E                    | [d4dbcd3245](https://linux-hardware.org/?probe=d4dbcd3245) | Apr 07, 2021 |
| MSI           | B85M-G43                    | [8e88c039f1](https://linux-hardware.org/?probe=8e88c039f1) | Apr 07, 2021 |
| Gigabyte      | B550 GAMING X V2            | [fb80233da7](https://linux-hardware.org/?probe=fb80233da7) | Apr 07, 2021 |
| Packard Be... | FMP55                       | [7f9d9db2ee](https://linux-hardware.org/?probe=7f9d9db2ee) | Apr 07, 2021 |
| MSI           | AMETHYST-M                  | [e47db7138d](https://linux-hardware.org/?probe=e47db7138d) | Apr 07, 2021 |
| MSI           | AMETHYST-M                  | [d54c5d4ba2](https://linux-hardware.org/?probe=d54c5d4ba2) | Apr 07, 2021 |
| HP            | 8436                        | [8295cec05d](https://linux-hardware.org/?probe=8295cec05d) | Apr 07, 2021 |
| Medion        | H81H3-EM2                   | [706b7cc962](https://linux-hardware.org/?probe=706b7cc962) | Apr 06, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [0bf3eb12ef](https://linux-hardware.org/?probe=0bf3eb12ef) | Apr 06, 2021 |
| Medion        | H81H3-EM2                   | [5b83bdb517](https://linux-hardware.org/?probe=5b83bdb517) | Apr 06, 2021 |
| Gigabyte      | 990FXA-UD3                  | [4b6b54b926](https://linux-hardware.org/?probe=4b6b54b926) | Apr 06, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [39524d8c7a](https://linux-hardware.org/?probe=39524d8c7a) | Apr 05, 2021 |
| Gigabyte      | B450M DS3H-CF               | [657c0505c5](https://linux-hardware.org/?probe=657c0505c5) | Apr 05, 2021 |
| MSI           | B250 PC MATE                | [1a150fa4c7](https://linux-hardware.org/?probe=1a150fa4c7) | Apr 05, 2021 |
| MSI           | B350 PC MATE                | [ca96bbf9e2](https://linux-hardware.org/?probe=ca96bbf9e2) | Apr 05, 2021 |
| ASUSTek       | F1A75-I DELUXE              | [277aed7ed9](https://linux-hardware.org/?probe=277aed7ed9) | Apr 05, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [5c152c9fde](https://linux-hardware.org/?probe=5c152c9fde) | Apr 05, 2021 |
| ASUSTek       | M4N68T-M-LE-V2              | [b5253eecf6](https://linux-hardware.org/?probe=b5253eecf6) | Apr 05, 2021 |
| ASUSTek       | Z170-P                      | [74ad9c69c1](https://linux-hardware.org/?probe=74ad9c69c1) | Apr 04, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [e9d704007f](https://linux-hardware.org/?probe=e9d704007f) | Apr 04, 2021 |
| ASUSTek       | P5LD2EB2-DHS                | [4089d0f836](https://linux-hardware.org/?probe=4089d0f836) | Apr 04, 2021 |
| Unknown       | Unknown                     | [d38419f785](https://linux-hardware.org/?probe=d38419f785) | Apr 04, 2021 |
| Acer          | Aspire X1430                | [b8683aa93c](https://linux-hardware.org/?probe=b8683aa93c) | Apr 04, 2021 |
| Gigabyte      | 990FXA-UD3                  | [1adca5c963](https://linux-hardware.org/?probe=1adca5c963) | Apr 03, 2021 |
| ASUSTek       | B150I PRO GAMING/AURA       | [b33866b71b](https://linux-hardware.org/?probe=b33866b71b) | Apr 03, 2021 |
| Pegatron      | EVANS                       | [662adb3d96](https://linux-hardware.org/?probe=662adb3d96) | Apr 03, 2021 |
| Biostar       | H81MHV3                     | [3064c65330](https://linux-hardware.org/?probe=3064c65330) | Apr 03, 2021 |
| Foxconn       | 2ABF                        | [9414f40cf2](https://linux-hardware.org/?probe=9414f40cf2) | Apr 03, 2021 |
| ASUSTek       | PRIME B450M-A               | [3bf53bc518](https://linux-hardware.org/?probe=3bf53bc518) | Apr 03, 2021 |
| Gigabyte      | 990FXA-UD3                  | [327a4888d5](https://linux-hardware.org/?probe=327a4888d5) | Apr 03, 2021 |
| Acer          | RS780DV                     | [42ed33d902](https://linux-hardware.org/?probe=42ed33d902) | Apr 03, 2021 |
| Dell          | 0M5DCD A00                  | [0eaf54f4f5](https://linux-hardware.org/?probe=0eaf54f4f5) | Apr 03, 2021 |
| Dell          | 0M5DCD A00                  | [51543dbb4d](https://linux-hardware.org/?probe=51543dbb4d) | Apr 03, 2021 |
| Gigabyte      | F2A88XM-D3H                 | [e0a4eeb793](https://linux-hardware.org/?probe=e0a4eeb793) | Apr 02, 2021 |
| Unknown       | Intel X79                   | [ce5e0bdd78](https://linux-hardware.org/?probe=ce5e0bdd78) | Apr 02, 2021 |
| ASUSTek       | PRIME Z390-A                | [06a465012b](https://linux-hardware.org/?probe=06a465012b) | Apr 02, 2021 |
| ASUSTek       | P8Z77-V LX                  | [da7dc5e5b9](https://linux-hardware.org/?probe=da7dc5e5b9) | Apr 02, 2021 |
| Gigabyte      | AB350M-D3H-CF               | [7f7f35810e](https://linux-hardware.org/?probe=7f7f35810e) | Apr 01, 2021 |
| Dell          | 0N4YC8 A00                  | [abbb037f1e](https://linux-hardware.org/?probe=abbb037f1e) | Apr 01, 2021 |
| Intel         | Q3XXG4-P V1.0               | [cfa6090469](https://linux-hardware.org/?probe=cfa6090469) | Apr 01, 2021 |
| ASUSTek       | B85-PLUS                    | [f6ac5358d0](https://linux-hardware.org/?probe=f6ac5358d0) | Mar 30, 2021 |
| Foxconn       | 2ABF                        | [f8ca1b001a](https://linux-hardware.org/?probe=f8ca1b001a) | Mar 30, 2021 |
| Dell          | 042P49 A01                  | [d6c9390744](https://linux-hardware.org/?probe=d6c9390744) | Mar 30, 2021 |
| ASRock        | FM2A68M-DG3+                | [25661235c9](https://linux-hardware.org/?probe=25661235c9) | Mar 30, 2021 |
| ASUSTek       | Z97I-PLUS                   | [161ae9e17a](https://linux-hardware.org/?probe=161ae9e17a) | Mar 29, 2021 |
| Intel         | H81                         | [daf9bd8edd](https://linux-hardware.org/?probe=daf9bd8edd) | Mar 29, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [56de90095b](https://linux-hardware.org/?probe=56de90095b) | Mar 29, 2021 |
| HP            | 81B3                        | [b24942946b](https://linux-hardware.org/?probe=b24942946b) | Mar 28, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [feff198a8c](https://linux-hardware.org/?probe=feff198a8c) | Mar 28, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [3370936d2f](https://linux-hardware.org/?probe=3370936d2f) | Mar 28, 2021 |
| HP            | 18E5                        | [15dc965007](https://linux-hardware.org/?probe=15dc965007) | Mar 28, 2021 |
| ASUSTek       | M4A79T Deluxe               | [96b81659fd](https://linux-hardware.org/?probe=96b81659fd) | Mar 28, 2021 |
| ASUSTek       | M4N68T-M-LE-V2              | [92223923ad](https://linux-hardware.org/?probe=92223923ad) | Mar 28, 2021 |
| ASUSTek       | B85M-G                      | [91155409dd](https://linux-hardware.org/?probe=91155409dd) | Mar 27, 2021 |
| eMachines     | EL1850                      | [7c2d95778c](https://linux-hardware.org/?probe=7c2d95778c) | Mar 27, 2021 |
| Gigabyte      | G31M-ES2L                   | [ef10beafcc](https://linux-hardware.org/?probe=ef10beafcc) | Mar 27, 2021 |
| Gigabyte      | H310MD2P-CF                 | [9faf0b355d](https://linux-hardware.org/?probe=9faf0b355d) | Mar 26, 2021 |
| ASRock        | H310M-STX                   | [419277b830](https://linux-hardware.org/?probe=419277b830) | Mar 26, 2021 |
| ASUSTek       | P8Z68 DELUXE                | [8ce30ac5a9](https://linux-hardware.org/?probe=8ce30ac5a9) | Mar 26, 2021 |
| Gigabyte      | Z77-D3H                     | [6ab1c423db](https://linux-hardware.org/?probe=6ab1c423db) | Mar 25, 2021 |
| ASRock        | A320M-HDV R3.0              | [a2ad3de5d8](https://linux-hardware.org/?probe=a2ad3de5d8) | Mar 25, 2021 |
| Gigabyte      | M61PME-S2P                  | [246f71ebbb](https://linux-hardware.org/?probe=246f71ebbb) | Mar 25, 2021 |
| Gigabyte      | M61PME-S2P                  | [e03dc458e6](https://linux-hardware.org/?probe=e03dc458e6) | Mar 25, 2021 |
| HP            | 3647h                       | [8f736cdc0f](https://linux-hardware.org/?probe=8f736cdc0f) | Mar 25, 2021 |
| HP            | 3647h                       | [32da606fb2](https://linux-hardware.org/?probe=32da606fb2) | Mar 25, 2021 |
| ASUSTek       | M4A785TD-M EVO              | [07db300210](https://linux-hardware.org/?probe=07db300210) | Mar 25, 2021 |
| Lenovo        | 36EE SDK0J40700 WIN 3258... | [cc06351c8c](https://linux-hardware.org/?probe=cc06351c8c) | Mar 24, 2021 |
| Acer          | ERC410M                     | [de264500c8](https://linux-hardware.org/?probe=de264500c8) | Mar 24, 2021 |
| ASUSTek       | PRIME A320M-K               | [2b381b3421](https://linux-hardware.org/?probe=2b381b3421) | Mar 24, 2021 |
| MSI           | B450M-A PRO MAX             | [c349eb2cce](https://linux-hardware.org/?probe=c349eb2cce) | Mar 23, 2021 |
| Gigabyte      | X570 UD                     | [b728548810](https://linux-hardware.org/?probe=b728548810) | Mar 23, 2021 |
| HP            | 0A9Ch                       | [d06786a41f](https://linux-hardware.org/?probe=d06786a41f) | Mar 23, 2021 |
| MSI           | Z370-A PRO                  | [5bfda75d00](https://linux-hardware.org/?probe=5bfda75d00) | Mar 23, 2021 |
| Gigabyte      | Z97X-Gaming 3               | [56e94aaad4](https://linux-hardware.org/?probe=56e94aaad4) | Mar 23, 2021 |
| ASUSTek       | M4A79T Deluxe               | [584de972f5](https://linux-hardware.org/?probe=584de972f5) | Mar 22, 2021 |
| Dell          | 05XGC8 A01                  | [1f7a0c0323](https://linux-hardware.org/?probe=1f7a0c0323) | Mar 22, 2021 |
| Dell          | 0CT103 A02                  | [05386eb1aa](https://linux-hardware.org/?probe=05386eb1aa) | Mar 22, 2021 |
| Lenovo        | SHARKBAY NOK                | [e9b0291347](https://linux-hardware.org/?probe=e9b0291347) | Mar 21, 2021 |
| HP            | 8459                        | [b7ac3b44df](https://linux-hardware.org/?probe=b7ac3b44df) | Mar 21, 2021 |
| ASUSTek       | P5KPL-AM SE                 | [90f988bead](https://linux-hardware.org/?probe=90f988bead) | Mar 21, 2021 |
| Unknown       | Unknown                     | [733b8d0260](https://linux-hardware.org/?probe=733b8d0260) | Mar 21, 2021 |
| MSI           | B250M BAZOOKA               | [eb39723fc7](https://linux-hardware.org/?probe=eb39723fc7) | Mar 21, 2021 |
| MSI           | H310M PRO-D                 | [b723b19a29](https://linux-hardware.org/?probe=b723b19a29) | Mar 21, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [36cb237d6b](https://linux-hardware.org/?probe=36cb237d6b) | Mar 21, 2021 |
| Acer          | FMCP7AM                     | [547c1bf7d7](https://linux-hardware.org/?probe=547c1bf7d7) | Mar 20, 2021 |
| ASUSTek       | G20AJ                       | [5f7b0e03c9](https://linux-hardware.org/?probe=5f7b0e03c9) | Mar 20, 2021 |
| ASUSTek       | H81M-K                      | [be20eafb4f](https://linux-hardware.org/?probe=be20eafb4f) | Mar 20, 2021 |
| Acer          | FMCP7AM                     | [52c74b2b51](https://linux-hardware.org/?probe=52c74b2b51) | Mar 20, 2021 |
| ASUSTek       | P8P67                       | [76bec8b2dc](https://linux-hardware.org/?probe=76bec8b2dc) | Mar 20, 2021 |
| HP            | 1497                        | [d35a7eef80](https://linux-hardware.org/?probe=d35a7eef80) | Mar 19, 2021 |
| MSI           | MS-7996                     | [5e207ad4fb](https://linux-hardware.org/?probe=5e207ad4fb) | Mar 19, 2021 |
| Gigabyte      | H87-HD3                     | [290838c751](https://linux-hardware.org/?probe=290838c751) | Mar 19, 2021 |
| Gigabyte      | Z390 AORUS PRO-CF           | [b16be4f4fc](https://linux-hardware.org/?probe=b16be4f4fc) | Mar 19, 2021 |
| Intel         | DB85FL AAG89861-203         | [5dbbeea263](https://linux-hardware.org/?probe=5dbbeea263) | Mar 19, 2021 |
| ASUSTek       | H81M-K                      | [0dd442a763](https://linux-hardware.org/?probe=0dd442a763) | Mar 19, 2021 |
| Pegatron      | EVANS                       | [18ef9299ba](https://linux-hardware.org/?probe=18ef9299ba) | Mar 18, 2021 |
| Pegatron      | EVANS                       | [b30a6e5dc9](https://linux-hardware.org/?probe=b30a6e5dc9) | Mar 18, 2021 |
| MSI           | B85M-P33                    | [740062dd8a](https://linux-hardware.org/?probe=740062dd8a) | Mar 18, 2021 |
| MSI           | B85M-P33                    | [e6c45eff18](https://linux-hardware.org/?probe=e6c45eff18) | Mar 18, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [ff60a699b7](https://linux-hardware.org/?probe=ff60a699b7) | Mar 18, 2021 |
| Pegatron      | 2AD5                        | [ef50e4ba3b](https://linux-hardware.org/?probe=ef50e4ba3b) | Mar 17, 2021 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [feb788ccac](https://linux-hardware.org/?probe=feb788ccac) | Mar 17, 2021 |
| Dell          | 0C27VV A01                  | [709d149da0](https://linux-hardware.org/?probe=709d149da0) | Mar 17, 2021 |
| Gigabyte      | GA-990XA-UD3                | [baa382cc01](https://linux-hardware.org/?probe=baa382cc01) | Mar 17, 2021 |
| ASUSTek       | M5A99X EVO                  | [55aa9109dd](https://linux-hardware.org/?probe=55aa9109dd) | Mar 17, 2021 |
| MSI           | MS-7267                     | [9ef4729cf8](https://linux-hardware.org/?probe=9ef4729cf8) | Mar 17, 2021 |
| Gigabyte      | B450M DS3H-CF               | [3b6feef3b9](https://linux-hardware.org/?probe=3b6feef3b9) | Mar 16, 2021 |
| ASUSTek       | M32CD4-K                    | [4e742c32dd](https://linux-hardware.org/?probe=4e742c32dd) | Mar 16, 2021 |
| MSI           | MS-7267                     | [f9ddf39632](https://linux-hardware.org/?probe=f9ddf39632) | Mar 16, 2021 |
| MSI           | 970 GAMING                  | [9b2db98a8d](https://linux-hardware.org/?probe=9b2db98a8d) | Mar 16, 2021 |
| HP            | 2B17                        | [753cbbeb9e](https://linux-hardware.org/?probe=753cbbeb9e) | Mar 16, 2021 |
| HP            | 0B4Ch D                     | [0ea968b326](https://linux-hardware.org/?probe=0ea968b326) | Mar 16, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [e0d52f745d](https://linux-hardware.org/?probe=e0d52f745d) | Mar 16, 2021 |
| Gigabyte      | Z77-D3H                     | [e1ce24306b](https://linux-hardware.org/?probe=e1ce24306b) | Mar 15, 2021 |
| Lenovo        | 7033EW4                     | [56afa5dc8a](https://linux-hardware.org/?probe=56afa5dc8a) | Mar 15, 2021 |
| Medion        | H61H2-LM3 V1.0              | [baec6f54e0](https://linux-hardware.org/?probe=baec6f54e0) | Mar 14, 2021 |
| MSI           | A320M-A PRO                 | [d900771dcf](https://linux-hardware.org/?probe=d900771dcf) | Mar 14, 2021 |
| ASUSTek       | Z97-A                       | [0cc10a7f8b](https://linux-hardware.org/?probe=0cc10a7f8b) | Mar 14, 2021 |
| MSI           | B85M-G43                    | [7df1054145](https://linux-hardware.org/?probe=7df1054145) | Mar 14, 2021 |
| Lenovo        | ThinkCentre M57e 6176A13    | [ea3b0d4216](https://linux-hardware.org/?probe=ea3b0d4216) | Mar 13, 2021 |
| ASUSTek       | H81-GAMER                   | [dfff897d6f](https://linux-hardware.org/?probe=dfff897d6f) | Mar 13, 2021 |
| Dell          | 0T656F A02                  | [708eb1bf51](https://linux-hardware.org/?probe=708eb1bf51) | Mar 13, 2021 |
| ASRock        | N68C-S UCC                  | [64bc9346ba](https://linux-hardware.org/?probe=64bc9346ba) | Mar 13, 2021 |
| HP            | 18E7                        | [76536f1bd8](https://linux-hardware.org/?probe=76536f1bd8) | Mar 13, 2021 |
| ASRock        | N68C-S UCC                  | [b71c4bb3c1](https://linux-hardware.org/?probe=b71c4bb3c1) | Mar 13, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [6b9d8f4c2c](https://linux-hardware.org/?probe=6b9d8f4c2c) | Mar 12, 2021 |
| MSI           | N3150I ECO                  | [ec0dd2e662](https://linux-hardware.org/?probe=ec0dd2e662) | Mar 12, 2021 |
| Dell          | 0T656F A02                  | [cc36a18a02](https://linux-hardware.org/?probe=cc36a18a02) | Mar 12, 2021 |
| Acer          | Aspire TC-780               | [5ac5e5625a](https://linux-hardware.org/?probe=5ac5e5625a) | Mar 12, 2021 |
| Intel         | DG965MQ AAD37419-302        | [2c5b191c86](https://linux-hardware.org/?probe=2c5b191c86) | Mar 11, 2021 |
| ASUSTek       | PRIME H310M-D R2.0          | [5f4e258cd5](https://linux-hardware.org/?probe=5f4e258cd5) | Mar 11, 2021 |
| Dell          | 00F82W A00                  | [25490e8c8c](https://linux-hardware.org/?probe=25490e8c8c) | Mar 11, 2021 |
| ASUSTek       | F2A85-M PRO                 | [97801fdc79](https://linux-hardware.org/?probe=97801fdc79) | Mar 11, 2021 |
| ASRock        | B550 Extreme4               | [79444a2f75](https://linux-hardware.org/?probe=79444a2f75) | Mar 11, 2021 |
| ASUSTek       | ROG STRIX H470-I GAMING     | [f8503ecc3b](https://linux-hardware.org/?probe=f8503ecc3b) | Mar 10, 2021 |
| ASUSTek       | PRIME A320M-K               | [2cb2416ff0](https://linux-hardware.org/?probe=2cb2416ff0) | Mar 10, 2021 |
| ASUSTek       | WS X299 SAGE                | [946940365a](https://linux-hardware.org/?probe=946940365a) | Mar 10, 2021 |
| ASUSTek       | H170M-PLUS                  | [b758883250](https://linux-hardware.org/?probe=b758883250) | Mar 10, 2021 |
| MSI           | 970 GAMING                  | [d3f85484f5](https://linux-hardware.org/?probe=d3f85484f5) | Mar 10, 2021 |
| ASRock        | B550 Extreme4               | [93620deb05](https://linux-hardware.org/?probe=93620deb05) | Mar 10, 2021 |
| ASUSTek       | PRIME X570-PRO              | [1b9a963c0f](https://linux-hardware.org/?probe=1b9a963c0f) | Mar 09, 2021 |
| MSI           | MAG B550 TOMAHAWK           | [d4787d1161](https://linux-hardware.org/?probe=d4787d1161) | Mar 09, 2021 |
| HP            | 829D                        | [df5bbf7aac](https://linux-hardware.org/?probe=df5bbf7aac) | Mar 09, 2021 |
| Gigabyte      | H61M-D2-B3                  | [15e03f68a5](https://linux-hardware.org/?probe=15e03f68a5) | Mar 09, 2021 |
| ASUSTek       | P8Z77-V                     | [f5c0ec7927](https://linux-hardware.org/?probe=f5c0ec7927) | Mar 09, 2021 |
| Gigabyte      | H61M-D2-B3                  | [dfefa43e04](https://linux-hardware.org/?probe=dfefa43e04) | Mar 09, 2021 |
| Dell          | 0HN7XN A01                  | [3b5f8120f4](https://linux-hardware.org/?probe=3b5f8120f4) | Mar 09, 2021 |
| HP            | 3048h                       | [224f7775f2](https://linux-hardware.org/?probe=224f7775f2) | Mar 09, 2021 |
| ASUSTek       | VM65N-K                     | [bdd6d645ed](https://linux-hardware.org/?probe=bdd6d645ed) | Mar 08, 2021 |
| MSI           | B85M-P33                    | [e7d2bb8e63](https://linux-hardware.org/?probe=e7d2bb8e63) | Mar 08, 2021 |
| ASUSTek       | PRIME Z390-P                | [accdafb993](https://linux-hardware.org/?probe=accdafb993) | Mar 08, 2021 |
| Intel         | DG965MQ AAD37419-302        | [e444e349b6](https://linux-hardware.org/?probe=e444e349b6) | Mar 08, 2021 |
| Acer          | Aspire XC600 v1.0           | [c1d72b6a7f](https://linux-hardware.org/?probe=c1d72b6a7f) | Mar 07, 2021 |
| HP            | 21D0                        | [db2894295c](https://linux-hardware.org/?probe=db2894295c) | Mar 06, 2021 |
| MSI           | MS-9A45 0A                  | [150912bfbf](https://linux-hardware.org/?probe=150912bfbf) | Mar 06, 2021 |
| Gigabyte      | Z77-DS3H                    | [cb029f9aab](https://linux-hardware.org/?probe=cb029f9aab) | Mar 06, 2021 |
| HP            | 339A                        | [548165b4ab](https://linux-hardware.org/?probe=548165b4ab) | Mar 06, 2021 |
| Gigabyte      | X570 AORUS PRO              | [5c86fc01aa](https://linux-hardware.org/?probe=5c86fc01aa) | Mar 06, 2021 |
| ASUSTek       | B150I PRO GAMING/AURA       | [df0e387c4e](https://linux-hardware.org/?probe=df0e387c4e) | Mar 06, 2021 |
| ASUSTek       | H97M-E                      | [9fc11777e5](https://linux-hardware.org/?probe=9fc11777e5) | Mar 06, 2021 |
| MSI           | B450M PRO-VDH MAX           | [79e6e8bbfc](https://linux-hardware.org/?probe=79e6e8bbfc) | Mar 06, 2021 |
| MSI           | B450M PRO-VDH MAX           | [7e8aa7dc5a](https://linux-hardware.org/?probe=7e8aa7dc5a) | Mar 06, 2021 |
| Dell          | 0D6H9T A01                  | [e773c4a2ec](https://linux-hardware.org/?probe=e773c4a2ec) | Mar 05, 2021 |
| MSI           | Z170-A PRO                  | [ba76d096ed](https://linux-hardware.org/?probe=ba76d096ed) | Mar 04, 2021 |
| Intel         | DG31PR AAD97573-301         | [09e15a8c00](https://linux-hardware.org/?probe=09e15a8c00) | Mar 04, 2021 |
| HP            | 8298                        | [c647523900](https://linux-hardware.org/?probe=c647523900) | Mar 04, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [c0daa56232](https://linux-hardware.org/?probe=c0daa56232) | Mar 04, 2021 |
| HP            | 2B2C                        | [20c11c9bbc](https://linux-hardware.org/?probe=20c11c9bbc) | Mar 04, 2021 |
| ASUSTek       | PRIME B450M-A               | [1870d9ac0b](https://linux-hardware.org/?probe=1870d9ac0b) | Mar 04, 2021 |
| Pegatron      | Benicia                     | [bcb6a9c668](https://linux-hardware.org/?probe=bcb6a9c668) | Mar 03, 2021 |
| ASUSTek       | PRIME B450M-A               | [d33f35d012](https://linux-hardware.org/?probe=d33f35d012) | Mar 03, 2021 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [35aa198b7a](https://linux-hardware.org/?probe=35aa198b7a) | Mar 03, 2021 |
| MSI           | X470 GAMING PRO CARBON      | [27aaf0c4ba](https://linux-hardware.org/?probe=27aaf0c4ba) | Mar 03, 2021 |
| ASUSTek       | B85-PLUS                    | [4cc8774bf3](https://linux-hardware.org/?probe=4cc8774bf3) | Mar 02, 2021 |
| Dell          | 0Y2K8N A00                  | [eca9b9b213](https://linux-hardware.org/?probe=eca9b9b213) | Mar 02, 2021 |
| Unknown       | Unknown                     | [76c81058cd](https://linux-hardware.org/?probe=76c81058cd) | Mar 02, 2021 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [f2eed042d9](https://linux-hardware.org/?probe=f2eed042d9) | Mar 02, 2021 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [7c1ac98fc7](https://linux-hardware.org/?probe=7c1ac98fc7) | Mar 02, 2021 |
| ASRock        | G41M-VS3                    | [587becd063](https://linux-hardware.org/?probe=587becd063) | Mar 02, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [84a1cebdd5](https://linux-hardware.org/?probe=84a1cebdd5) | Mar 01, 2021 |
| ASUSTek       | P8Z68-V LX                  | [2281ed2750](https://linux-hardware.org/?probe=2281ed2750) | Mar 01, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [f3ed2d4804](https://linux-hardware.org/?probe=f3ed2d4804) | Mar 01, 2021 |
| Dell          | 0215PR A02                  | [f96f352657](https://linux-hardware.org/?probe=f96f352657) | Mar 01, 2021 |
| Pegatron      | E60                         | [c8e4e068f4](https://linux-hardware.org/?probe=c8e4e068f4) | Mar 01, 2021 |
| ASUSTek       | WS X299 SAGE                | [ca676f22c8](https://linux-hardware.org/?probe=ca676f22c8) | Mar 01, 2021 |
| ASUSTek       | G11CD                       | [00f5bdbdfb](https://linux-hardware.org/?probe=00f5bdbdfb) | Mar 01, 2021 |
| ASUSTek       | WS X299 SAGE                | [3430cf6bf1](https://linux-hardware.org/?probe=3430cf6bf1) | Mar 01, 2021 |
| ASUSTek       | PRIME Z390-P                | [6cc823cf63](https://linux-hardware.org/?probe=6cc823cf63) | Feb 28, 2021 |
| MSI           | H61M-P22                    | [2b1f47c25e](https://linux-hardware.org/?probe=2b1f47c25e) | Feb 28, 2021 |
| Lenovo        | 7033EW4                     | [ac9f74f328](https://linux-hardware.org/?probe=ac9f74f328) | Feb 28, 2021 |
| ASUSTek       | X99-PRO                     | [ac965855ba](https://linux-hardware.org/?probe=ac965855ba) | Feb 28, 2021 |
| Gigabyte      | Z68P-DS3                    | [3d57c5be17](https://linux-hardware.org/?probe=3d57c5be17) | Feb 27, 2021 |
| MSI           | MPG Z490 GAMING PLUS        | [36543664dc](https://linux-hardware.org/?probe=36543664dc) | Feb 27, 2021 |
| Lenovo        | ThinkCentre M90 5485WFL     | [47fadb4fa4](https://linux-hardware.org/?probe=47fadb4fa4) | Feb 27, 2021 |
| ASRock        | A320M-HDV R4.0              | [9057e2fabf](https://linux-hardware.org/?probe=9057e2fabf) | Feb 27, 2021 |
| Gigabyte      | G41MT-D3V                   | [ed1976fefc](https://linux-hardware.org/?probe=ed1976fefc) | Feb 27, 2021 |
| Lenovo        | ThinkCentre M58p 6234WAV    | [05a9547b85](https://linux-hardware.org/?probe=05a9547b85) | Feb 26, 2021 |
| MSI           | MPG Z490 GAMING PLUS        | [6becd1cb83](https://linux-hardware.org/?probe=6becd1cb83) | Feb 26, 2021 |
| ASRock        | A320M-HDV R3.0              | [f8fa93e318](https://linux-hardware.org/?probe=f8fa93e318) | Feb 26, 2021 |
| LIVEFAN       | Unknown                     | [a95f919120](https://linux-hardware.org/?probe=a95f919120) | Feb 25, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [1772e8a594](https://linux-hardware.org/?probe=1772e8a594) | Feb 25, 2021 |
| MSI           | X470 GAMING PLUS MAX        | [09ccd98cfb](https://linux-hardware.org/?probe=09ccd98cfb) | Feb 25, 2021 |
| MSI           | Z87-G41 PC Mate             | [4a6cc7a165](https://linux-hardware.org/?probe=4a6cc7a165) | Feb 25, 2021 |
| Intel         | DN2800MT AAG23738-801       | [ed8bf69f6b](https://linux-hardware.org/?probe=ed8bf69f6b) | Feb 25, 2021 |
| Gigabyte      | H81M-S2PV                   | [dc2800f15c](https://linux-hardware.org/?probe=dc2800f15c) | Feb 24, 2021 |
| ASUSTek       | P9X79 PRO                   | [52da1c28e5](https://linux-hardware.org/?probe=52da1c28e5) | Feb 24, 2021 |
| Dell          | 0NK5PH A00                  | [3f81389dd6](https://linux-hardware.org/?probe=3f81389dd6) | Feb 24, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [b8499efd63](https://linux-hardware.org/?probe=b8499efd63) | Feb 24, 2021 |
| ASRock        | ION3D-HT                    | [0d58be2193](https://linux-hardware.org/?probe=0d58be2193) | Feb 24, 2021 |
| ASUSTek       | ROG STRIX H470-I GAMING     | [c096245d55](https://linux-hardware.org/?probe=c096245d55) | Feb 23, 2021 |
| MSI           | Z490-A PRO                  | [9aec3aa69a](https://linux-hardware.org/?probe=9aec3aa69a) | Feb 23, 2021 |
| ASUSTek       | P5Q-PRO                     | [b59eb35b59](https://linux-hardware.org/?probe=b59eb35b59) | Feb 23, 2021 |
| HP            | 0A9Ch                       | [564d09fb7e](https://linux-hardware.org/?probe=564d09fb7e) | Feb 22, 2021 |
| Shuttle       | B10IE01                     | [33f0017dbd](https://linux-hardware.org/?probe=33f0017dbd) | Feb 22, 2021 |
| Shuttle       | B10IE01                     | [33babdfb03](https://linux-hardware.org/?probe=33babdfb03) | Feb 22, 2021 |
| Foxconn       | 2ACA                        | [4f062f3285](https://linux-hardware.org/?probe=4f062f3285) | Feb 22, 2021 |
| ASUSTek       | PRIME Z390-P                | [fce5467293](https://linux-hardware.org/?probe=fce5467293) | Feb 21, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [ee63c3542d](https://linux-hardware.org/?probe=ee63c3542d) | Feb 21, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [ba6d173e12](https://linux-hardware.org/?probe=ba6d173e12) | Feb 21, 2021 |
| ASUSTek       | P8H67-M                     | [45bd552a86](https://linux-hardware.org/?probe=45bd552a86) | Feb 21, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [1382e76c47](https://linux-hardware.org/?probe=1382e76c47) | Feb 21, 2021 |
| ASUSTek       | H170M-PLUS                  | [38aba8dfe7](https://linux-hardware.org/?probe=38aba8dfe7) | Feb 20, 2021 |
| MSI           | P35 Platinum                | [f482c78051](https://linux-hardware.org/?probe=f482c78051) | Feb 20, 2021 |
| MSI           | P35 Platinum                | [ce07ef3087](https://linux-hardware.org/?probe=ce07ef3087) | Feb 20, 2021 |
| Medion        | H67H2-EM                    | [80d0c1b135](https://linux-hardware.org/?probe=80d0c1b135) | Feb 20, 2021 |
| ASUSTek       | P5QL PRO                    | [6f9495b8b9](https://linux-hardware.org/?probe=6f9495b8b9) | Feb 19, 2021 |
| ASUSTek       | ROG STRIX H470-I GAMING     | [f747681c25](https://linux-hardware.org/?probe=f747681c25) | Feb 19, 2021 |
| ASRock        | M3A UCC                     | [714da9501f](https://linux-hardware.org/?probe=714da9501f) | Feb 19, 2021 |
| Gigabyte      | B450M DS3H-CF               | [7ee61faff8](https://linux-hardware.org/?probe=7ee61faff8) | Feb 19, 2021 |
| HP            | 3048h                       | [a4e16b612f](https://linux-hardware.org/?probe=a4e16b612f) | Feb 18, 2021 |
| ASUSTek       | P8H61-M LE                  | [9ccf7e2078](https://linux-hardware.org/?probe=9ccf7e2078) | Feb 18, 2021 |
| MSI           | X470 GAMING PLUS            | [51e50d143a](https://linux-hardware.org/?probe=51e50d143a) | Feb 18, 2021 |
| eMachines     | WMCP61M                     | [087382e171](https://linux-hardware.org/?probe=087382e171) | Feb 18, 2021 |
| MSI           | B150M PRO-VDH               | [71e634cfe2](https://linux-hardware.org/?probe=71e634cfe2) | Feb 18, 2021 |
| eMachines     | WMCP61M                     | [a1a77aa715](https://linux-hardware.org/?probe=a1a77aa715) | Feb 18, 2021 |
| ASRock        | N68C-S UCC                  | [c2ab8a3196](https://linux-hardware.org/?probe=c2ab8a3196) | Feb 18, 2021 |
| Lenovo        | SHARKBAY NOK                | [2792d5d293](https://linux-hardware.org/?probe=2792d5d293) | Feb 18, 2021 |
| ASRockRack    | EPYCD8-2T                   | [4c4ad9ebe5](https://linux-hardware.org/?probe=4c4ad9ebe5) | Feb 18, 2021 |
| Unknown       | XH61X000.100                | [029de8905d](https://linux-hardware.org/?probe=029de8905d) | Feb 17, 2021 |
| MSI           | H81M-P33                    | [bfa8d32e2c](https://linux-hardware.org/?probe=bfa8d32e2c) | Feb 17, 2021 |
| Pegatron      | Eureka3                     | [e72dd7a211](https://linux-hardware.org/?probe=e72dd7a211) | Feb 17, 2021 |
| ASUSTek       | NCL-DS                      | [8b8ae89ab9](https://linux-hardware.org/?probe=8b8ae89ab9) | Feb 17, 2021 |
| MSI           | Z490-A PRO                  | [a621945145](https://linux-hardware.org/?probe=a621945145) | Feb 17, 2021 |
| ASUSTek       | M5A88-V EVO                 | [af794c7302](https://linux-hardware.org/?probe=af794c7302) | Feb 17, 2021 |
| MSI           | X570-A PRO                  | [a11127fa47](https://linux-hardware.org/?probe=a11127fa47) | Feb 16, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | [5ad5e7c0b8](https://linux-hardware.org/?probe=5ad5e7c0b8) | Feb 16, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [65b32aa4a5](https://linux-hardware.org/?probe=65b32aa4a5) | Feb 16, 2021 |
| Supermicro    | X10SDE-DF                   | [ed9d9f347d](https://linux-hardware.org/?probe=ed9d9f347d) | Feb 16, 2021 |
| ASRock        | G41M-VS3                    | [ffc4840176](https://linux-hardware.org/?probe=ffc4840176) | Feb 15, 2021 |
| ASUSTek       | EB1501G                     | [0d0d8b9925](https://linux-hardware.org/?probe=0d0d8b9925) | Feb 15, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [02647a095d](https://linux-hardware.org/?probe=02647a095d) | Feb 15, 2021 |
| ASUSTek       | M4A785TD-M EVO              | [73cd08b5d2](https://linux-hardware.org/?probe=73cd08b5d2) | Feb 15, 2021 |
| Gigabyte      | MKLP7AP-00                  | [7cfbb0a2c7](https://linux-hardware.org/?probe=7cfbb0a2c7) | Feb 15, 2021 |
| ASUSTek       | H170M-PLUS                  | [51137990d6](https://linux-hardware.org/?probe=51137990d6) | Feb 15, 2021 |
| MSI           | G31TM-P35                   | [f78793e217](https://linux-hardware.org/?probe=f78793e217) | Feb 15, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [284fb17dcc](https://linux-hardware.org/?probe=284fb17dcc) | Feb 15, 2021 |
| MSI           | X370 GAMING PLUS            | [26f4437015](https://linux-hardware.org/?probe=26f4437015) | Feb 14, 2021 |
| HP            | 18E4                        | [6c8bac2b52](https://linux-hardware.org/?probe=6c8bac2b52) | Feb 14, 2021 |
| MSI           | B360 GAMING PLUS            | [28fd708d1e](https://linux-hardware.org/?probe=28fd708d1e) | Feb 14, 2021 |
| MSI           | H61M-P22                    | [969861d9dd](https://linux-hardware.org/?probe=969861d9dd) | Feb 14, 2021 |
| Acer          | WG43M                       | [09d469f1fc](https://linux-hardware.org/?probe=09d469f1fc) | Feb 14, 2021 |
| ASUSTek       | P5Q                         | [8e1c4c322c](https://linux-hardware.org/?probe=8e1c4c322c) | Feb 14, 2021 |
| ASUSTek       | PRIME Z390-P                | [cdd0998f7c](https://linux-hardware.org/?probe=cdd0998f7c) | Feb 14, 2021 |
| ASUSTek       | A_F_K20CE                   | [771c050533](https://linux-hardware.org/?probe=771c050533) | Feb 14, 2021 |
| ASUSTek       | M5A99X EVO                  | [26169a65ed](https://linux-hardware.org/?probe=26169a65ed) | Feb 13, 2021 |
| ASRock        | Z97E-ITX/ac                 | [f4551a22fd](https://linux-hardware.org/?probe=f4551a22fd) | Feb 13, 2021 |
| Lenovo        | ThinkCentre M57 6075G4G     | [634bd29e96](https://linux-hardware.org/?probe=634bd29e96) | Feb 13, 2021 |
| Foxconn       | 2ADA                        | [e331704c31](https://linux-hardware.org/?probe=e331704c31) | Feb 13, 2021 |
| MSI           | A320M PRO-VD/S              | [cfb6d7e271](https://linux-hardware.org/?probe=cfb6d7e271) | Feb 13, 2021 |
| Gigabyte      | H270-HD3-CF                 | [839d302e65](https://linux-hardware.org/?probe=839d302e65) | Feb 13, 2021 |
| HP            | 0A9Ch                       | [1b4df379f5](https://linux-hardware.org/?probe=1b4df379f5) | Feb 13, 2021 |
| HP            | 8767 A                      | [06b6693f47](https://linux-hardware.org/?probe=06b6693f47) | Feb 13, 2021 |
| ASUSTek       | G10AC                       | [45b762a0d1](https://linux-hardware.org/?probe=45b762a0d1) | Feb 13, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [99b31bd894](https://linux-hardware.org/?probe=99b31bd894) | Feb 13, 2021 |
| MSI           | A320M PRO-VD PLUS           | [24a9ae34ed](https://linux-hardware.org/?probe=24a9ae34ed) | Feb 13, 2021 |
| MSI           | P67A-GD65                   | [bf080c8ec0](https://linux-hardware.org/?probe=bf080c8ec0) | Feb 13, 2021 |
| MSI           | 2A9C                        | [7ea18b68f6](https://linux-hardware.org/?probe=7ea18b68f6) | Feb 13, 2021 |
| HP            | 18E7                        | [a96bf65645](https://linux-hardware.org/?probe=a96bf65645) | Feb 13, 2021 |
| Fujitsu       | D2990-A1 S26361-D2990-A1    | [51060f5181](https://linux-hardware.org/?probe=51060f5181) | Feb 13, 2021 |
| HP            | 2B17                        | [d3bef43185](https://linux-hardware.org/?probe=d3bef43185) | Feb 13, 2021 |
| Gigabyte      | Z97P-D3                     | [89c2eed11c](https://linux-hardware.org/?probe=89c2eed11c) | Feb 13, 2021 |
| ASRock        | H55M Pro                    | [5aa415f427](https://linux-hardware.org/?probe=5aa415f427) | Feb 13, 2021 |
| ASUSTek       | PRIME Z390-P                | [f4ee71d37f](https://linux-hardware.org/?probe=f4ee71d37f) | Feb 12, 2021 |
| MSI           | Z370 GAMING PRO CARBON A... | [96ee622b51](https://linux-hardware.org/?probe=96ee622b51) | Feb 12, 2021 |
| ASRock        | G41M-VS3                    | [dde8e71738](https://linux-hardware.org/?probe=dde8e71738) | Feb 12, 2021 |
| Foxconn       | 2ABF                        | [8ec8f1ce75](https://linux-hardware.org/?probe=8ec8f1ce75) | Feb 11, 2021 |
| ASUSTek       | M4N78                       | [0684df7966](https://linux-hardware.org/?probe=0684df7966) | Feb 10, 2021 |
| ASUSTek       | M5A99X EVO                  | [e5b3c2f659](https://linux-hardware.org/?probe=e5b3c2f659) | Feb 10, 2021 |
| Fujitsu       | D3162-C1 S26361-D3162-C1    | [c0ccb5e573](https://linux-hardware.org/?probe=c0ccb5e573) | Feb 10, 2021 |
| MSI           | B85M GAMING                 | [bd107eb4ae](https://linux-hardware.org/?probe=bd107eb4ae) | Feb 10, 2021 |
| ASRock        | P43DE                       | [270e1435b9](https://linux-hardware.org/?probe=270e1435b9) | Feb 10, 2021 |
| MSI           | A68HM-E33 V2                | [b74bbac7ff](https://linux-hardware.org/?probe=b74bbac7ff) | Feb 10, 2021 |
| HP            | 1791                        | [9fdc347ed0](https://linux-hardware.org/?probe=9fdc347ed0) | Feb 10, 2021 |
| MSI           | A320M-A PRO                 | [2c29fdbbea](https://linux-hardware.org/?probe=2c29fdbbea) | Feb 09, 2021 |
| HP            | 3397                        | [fdeb1e2688](https://linux-hardware.org/?probe=fdeb1e2688) | Feb 09, 2021 |
| Gigabyte      | MZBAYAB-00                  | [fa48450d71](https://linux-hardware.org/?probe=fa48450d71) | Feb 09, 2021 |
| ASUSTek       | P8P67 PRO                   | [bbff698cb8](https://linux-hardware.org/?probe=bbff698cb8) | Feb 09, 2021 |
| ASUSTek       | M5A99X EVO                  | [da403b7294](https://linux-hardware.org/?probe=da403b7294) | Feb 08, 2021 |
| HP            | 3397                        | [566a75a85a](https://linux-hardware.org/?probe=566a75a85a) | Feb 08, 2021 |
| Gigabyte      | B85M-HD3                    | [d4efd5185b](https://linux-hardware.org/?probe=d4efd5185b) | Feb 08, 2021 |
| MSI           | H81M-E34                    | [b6308af2c4](https://linux-hardware.org/?probe=b6308af2c4) | Feb 07, 2021 |
| ASUSTek       | P8Z77-V                     | [d165244f3b](https://linux-hardware.org/?probe=d165244f3b) | Feb 07, 2021 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | [7d178db676](https://linux-hardware.org/?probe=7d178db676) | Feb 07, 2021 |
| Dell          | 0GWHMW A00                  | [dc30f3885a](https://linux-hardware.org/?probe=dc30f3885a) | Feb 07, 2021 |
| ASRock        | FM2A88X+ Killer             | [0abbad91f6](https://linux-hardware.org/?probe=0abbad91f6) | Feb 07, 2021 |
| HP            | 18E5                        | [f78d266260](https://linux-hardware.org/?probe=f78d266260) | Feb 06, 2021 |
| ASRock        | A320M-HDV R3.0              | [698b1c6ea7](https://linux-hardware.org/?probe=698b1c6ea7) | Feb 05, 2021 |
| HP            | 2B47                        | [8ac1dd6ec7](https://linux-hardware.org/?probe=8ac1dd6ec7) | Feb 05, 2021 |
| HP            | 18E5                        | [1e1e2ef32b](https://linux-hardware.org/?probe=1e1e2ef32b) | Feb 05, 2021 |
| MSI           | B360 GAMING PLUS            | [b027c83f03](https://linux-hardware.org/?probe=b027c83f03) | Feb 05, 2021 |
| MSI           | Z87-G55                     | [c1fc6c783a](https://linux-hardware.org/?probe=c1fc6c783a) | Feb 05, 2021 |
| ASUSTek       | P8H61-M LE                  | [5b0f2901d7](https://linux-hardware.org/?probe=5b0f2901d7) | Feb 04, 2021 |
| Gigabyte      | X570 AORUS PRO              | [7308a74269](https://linux-hardware.org/?probe=7308a74269) | Feb 04, 2021 |
| Gigabyte      | X570 AORUS PRO              | [88fda16ddd](https://linux-hardware.org/?probe=88fda16ddd) | Feb 04, 2021 |
| ASUSTek       | H97M-E                      | [e5f083fe5b](https://linux-hardware.org/?probe=e5f083fe5b) | Feb 04, 2021 |
| MSI           | B550M-A PRO                 | [b80ad03112](https://linux-hardware.org/?probe=b80ad03112) | Feb 04, 2021 |
| ASUSTek       | H97M-E                      | [afacc90df0](https://linux-hardware.org/?probe=afacc90df0) | Feb 03, 2021 |
| MSI           | A320M-A PRO MAX             | [1db8d5c272](https://linux-hardware.org/?probe=1db8d5c272) | Feb 03, 2021 |
| MSI           | 09AC                        | [aeccfacb66](https://linux-hardware.org/?probe=aeccfacb66) | Feb 03, 2021 |
| Foxconn       | 2ABF                        | [0d7d8c22d1](https://linux-hardware.org/?probe=0d7d8c22d1) | Feb 03, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [e2723fb2bc](https://linux-hardware.org/?probe=e2723fb2bc) | Feb 03, 2021 |
| MSI           | B360 GAMING PLUS            | [82ff70f30b](https://linux-hardware.org/?probe=82ff70f30b) | Feb 02, 2021 |
| HP            | 81B4                        | [724be02ff9](https://linux-hardware.org/?probe=724be02ff9) | Feb 02, 2021 |
| MSI           | B450-A PRO MAX              | [09e9a6932e](https://linux-hardware.org/?probe=09e9a6932e) | Feb 01, 2021 |
| Biostar       | H61MGV3                     | [d3391d7b84](https://linux-hardware.org/?probe=d3391d7b84) | Feb 01, 2021 |
| Acer          | EG43M                       | [d6e0e0433a](https://linux-hardware.org/?probe=d6e0e0433a) | Jan 31, 2021 |
| Acer          | EG43M                       | [f6a7e2df44](https://linux-hardware.org/?probe=f6a7e2df44) | Jan 31, 2021 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [770bab0deb](https://linux-hardware.org/?probe=770bab0deb) | Jan 31, 2021 |
| MSI           | H310M PRO-M2 PLUS           | [bbab610ec1](https://linux-hardware.org/?probe=bbab610ec1) | Jan 31, 2021 |
| Packard Be... | IMEDIA S3840                | [c0a7dff96d](https://linux-hardware.org/?probe=c0a7dff96d) | Jan 31, 2021 |
| Dell          | 0GXM1W A01                  | [720c314129](https://linux-hardware.org/?probe=720c314129) | Jan 30, 2021 |
| Dell          | 0GXM1W A02                  | [fdca13ca28](https://linux-hardware.org/?probe=fdca13ca28) | Jan 30, 2021 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [7463bd6a6f](https://linux-hardware.org/?probe=7463bd6a6f) | Jan 30, 2021 |
| HP            | 3048h                       | [59c1560e00](https://linux-hardware.org/?probe=59c1560e00) | Jan 30, 2021 |
| Acer          | G31                         | [fb84e1d152](https://linux-hardware.org/?probe=fb84e1d152) | Jan 30, 2021 |
| Gigabyte      | G41M-Combo                  | [9e34adfe39](https://linux-hardware.org/?probe=9e34adfe39) | Jan 30, 2021 |
| MSI           | Z77A-G43                    | [9989c5e243](https://linux-hardware.org/?probe=9989c5e243) | Jan 29, 2021 |
| MSI           | H81I                        | [b6f9ee5a69](https://linux-hardware.org/?probe=b6f9ee5a69) | Jan 29, 2021 |
| ASRock        | G41M-GS3                    | [ff64931372](https://linux-hardware.org/?probe=ff64931372) | Jan 29, 2021 |
| Gigabyte      | F2A68HM-D3H                 | [654bd5e92a](https://linux-hardware.org/?probe=654bd5e92a) | Jan 29, 2021 |
| MSI           | B85M-P32                    | [fa2a80e3ac](https://linux-hardware.org/?probe=fa2a80e3ac) | Jan 28, 2021 |
| HP            | 3397                        | [c453dbbdca](https://linux-hardware.org/?probe=c453dbbdca) | Jan 28, 2021 |
| ASUSTek       | M4A785TD-M EVO              | [ae84fab12c](https://linux-hardware.org/?probe=ae84fab12c) | Jan 27, 2021 |
| HP            | 18E5                        | [2a72f13e4c](https://linux-hardware.org/?probe=2a72f13e4c) | Jan 27, 2021 |
| Gigabyte      | P35-DS3R                    | [4a38c1273c](https://linux-hardware.org/?probe=4a38c1273c) | Jan 26, 2021 |
| MSI           | 970 GAMING                  | [956123e813](https://linux-hardware.org/?probe=956123e813) | Jan 26, 2021 |
| ASRock        | AM1B-ITX                    | [946862c0ec](https://linux-hardware.org/?probe=946862c0ec) | Jan 26, 2021 |
| ASUSTek       | P8Z77-V LK                  | [285d66a0b4](https://linux-hardware.org/?probe=285d66a0b4) | Jan 26, 2021 |
| ASRock        | X470 Master SLI             | [36eaf717e9](https://linux-hardware.org/?probe=36eaf717e9) | Jan 26, 2021 |
| MSI           | Z77A-G43                    | [de631d6f63](https://linux-hardware.org/?probe=de631d6f63) | Jan 26, 2021 |
| ASUSTek       | P8Z77-V LK                  | [59b1524664](https://linux-hardware.org/?probe=59b1524664) | Jan 26, 2021 |
| ASRock        | AB350M Pro4                 | [2da6d3600f](https://linux-hardware.org/?probe=2da6d3600f) | Jan 26, 2021 |
| ASUSTek       | Leonite2                    | [c42ebccd34](https://linux-hardware.org/?probe=c42ebccd34) | Jan 26, 2021 |
| MSI           | B250M PRO-VDH               | [1cb17df2b9](https://linux-hardware.org/?probe=1cb17df2b9) | Jan 25, 2021 |
| Dell          | 0N4YC8 A00                  | [438fa28cf8](https://linux-hardware.org/?probe=438fa28cf8) | Jan 25, 2021 |
| ASRock        | X470 Master SLI             | [b1be9375c0](https://linux-hardware.org/?probe=b1be9375c0) | Jan 24, 2021 |
| MSI           | A320M PRO-VD PLUS           | [a120019247](https://linux-hardware.org/?probe=a120019247) | Jan 24, 2021 |
| ASUSTek       | B85M-E                      | [264e9402a9](https://linux-hardware.org/?probe=264e9402a9) | Jan 24, 2021 |
| Gigabyte      | GA-MA770-DS3                | [c9af16a580](https://linux-hardware.org/?probe=c9af16a580) | Jan 24, 2021 |
| ASUSTek       | Z87-A                       | [92b6c1388f](https://linux-hardware.org/?probe=92b6c1388f) | Jan 24, 2021 |
| ASUSTek       | K30BF_M32BF_A_F_K31BF       | [f8fdb6f4b3](https://linux-hardware.org/?probe=f8fdb6f4b3) | Jan 24, 2021 |
| ASUSTek       | B85M-E                      | [b53745e607](https://linux-hardware.org/?probe=b53745e607) | Jan 23, 2021 |
| Gigabyte      | 970A-DS3P                   | [1c542b4230](https://linux-hardware.org/?probe=1c542b4230) | Jan 23, 2021 |
| Gigabyte      | 970A-DS3P                   | [afc08fba5e](https://linux-hardware.org/?probe=afc08fba5e) | Jan 23, 2021 |
| MSI           | B85-G43                     | [4955170f6b](https://linux-hardware.org/?probe=4955170f6b) | Jan 23, 2021 |
| HP            | 0A9Ch                       | [f5196be361](https://linux-hardware.org/?probe=f5196be361) | Jan 23, 2021 |
| Lenovo        | ThinkCentre M57 6075G4G     | [caf2e445a4](https://linux-hardware.org/?probe=caf2e445a4) | Jan 22, 2021 |
| MSI           | 2A9C                        | [93a0c5aab7](https://linux-hardware.org/?probe=93a0c5aab7) | Jan 22, 2021 |
| Dell          | 048DY8 A00                  | [3936ca09db](https://linux-hardware.org/?probe=3936ca09db) | Jan 22, 2021 |
| MSI           | 970A-G43 PLUS               | [a2dea9d333](https://linux-hardware.org/?probe=a2dea9d333) | Jan 22, 2021 |
| ASUSTek       | VC66                        | [7bf78ca6ac](https://linux-hardware.org/?probe=7bf78ca6ac) | Jan 22, 2021 |
| ASUSTek       | Z97-PRO GAMER               | [79ea9e0ea5](https://linux-hardware.org/?probe=79ea9e0ea5) | Jan 21, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | [4a71b6426d](https://linux-hardware.org/?probe=4a71b6426d) | Jan 21, 2021 |
| Medion        | MS-7728                     | [9775cd1138](https://linux-hardware.org/?probe=9775cd1138) | Jan 21, 2021 |
| Dell          | 0M5DCD A00                  | [b587c1f043](https://linux-hardware.org/?probe=b587c1f043) | Jan 21, 2021 |
| ASUSTek       | VC66                        | [4027d37d47](https://linux-hardware.org/?probe=4027d37d47) | Jan 20, 2021 |
| Dell          | 0TP412                      | [8af2d76163](https://linux-hardware.org/?probe=8af2d76163) | Jan 20, 2021 |
| Dell          | 0TP412                      | [7b20443f95](https://linux-hardware.org/?probe=7b20443f95) | Jan 20, 2021 |
| MSI           | Z87-GD65 GAMING             | [d11a961070](https://linux-hardware.org/?probe=d11a961070) | Jan 20, 2021 |
| Intel         | DG31GL AAE33912-200         | [14491b53d7](https://linux-hardware.org/?probe=14491b53d7) | Jan 20, 2021 |
| Dell          | 0K216C                      | [524206eff9](https://linux-hardware.org/?probe=524206eff9) | Jan 20, 2021 |
| MSI           | B150 GAMING M3              | [5d5f4f790e](https://linux-hardware.org/?probe=5d5f4f790e) | Jan 19, 2021 |
| Dell          | 0RW199                      | [b1fb29a33e](https://linux-hardware.org/?probe=b1fb29a33e) | Jan 19, 2021 |
| ASUSTek       | P8B75-M LX                  | [b12380d932](https://linux-hardware.org/?probe=b12380d932) | Jan 19, 2021 |
| Unknown       | Unknown                     | [4e23983c80](https://linux-hardware.org/?probe=4e23983c80) | Jan 19, 2021 |
| ASUSTek       | P8Z77-V DELUXE              | [79397b3de7](https://linux-hardware.org/?probe=79397b3de7) | Jan 19, 2021 |
| ASUSTek       | Z87-C                       | [2320c57e92](https://linux-hardware.org/?probe=2320c57e92) | Jan 19, 2021 |
| ECS           | Nettle2                     | [a6bdef0e24](https://linux-hardware.org/?probe=a6bdef0e24) | Jan 19, 2021 |
| ECS           | Nettle2                     | [73dd2e0deb](https://linux-hardware.org/?probe=73dd2e0deb) | Jan 19, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [c765adbbfc](https://linux-hardware.org/?probe=c765adbbfc) | Jan 18, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [879d1df75b](https://linux-hardware.org/?probe=879d1df75b) | Jan 18, 2021 |
| HP            | ProLiant MicroServer        | [708c73fa1d](https://linux-hardware.org/?probe=708c73fa1d) | Jan 17, 2021 |
| Acer          | G31                         | [981b782758](https://linux-hardware.org/?probe=981b782758) | Jan 17, 2021 |
| HP            | 18E5                        | [5af2f3397e](https://linux-hardware.org/?probe=5af2f3397e) | Jan 17, 2021 |
| Gigabyte      | M61PME-S2P                  | [119ad3e83d](https://linux-hardware.org/?probe=119ad3e83d) | Jan 17, 2021 |
| ASUSTek       | P5QD TURBO                  | [3819b82e2f](https://linux-hardware.org/?probe=3819b82e2f) | Jan 17, 2021 |
| ASRock        | A320M-HDV R3.0              | [ff70c56774](https://linux-hardware.org/?probe=ff70c56774) | Jan 16, 2021 |
| ASUSTek       | P8B75-M LX PLUS             | [c53595bd26](https://linux-hardware.org/?probe=c53595bd26) | Jan 16, 2021 |
| HP            | 0984h                       | [5bb1bf036f](https://linux-hardware.org/?probe=5bb1bf036f) | Jan 16, 2021 |
| Gigabyte      | M61PME-S2P                  | [fd53599f24](https://linux-hardware.org/?probe=fd53599f24) | Jan 16, 2021 |
| MSI           | B350 TOMAHAWK               | [f62df1e7ef](https://linux-hardware.org/?probe=f62df1e7ef) | Jan 15, 2021 |
| Dell          | 0KC9NP A00                  | [19f4f5baff](https://linux-hardware.org/?probe=19f4f5baff) | Jan 15, 2021 |
| ASRock        | TRX40 Taichi                | [a770b03db4](https://linux-hardware.org/?probe=a770b03db4) | Jan 15, 2021 |
| MSI           | MEG X299 CREATION           | [589f688e41](https://linux-hardware.org/?probe=589f688e41) | Jan 15, 2021 |
| Dell          | 0KC9NP A00                  | [7a92eb4a8b](https://linux-hardware.org/?probe=7a92eb4a8b) | Jan 15, 2021 |
| Gigabyte      | G41M-Combo                  | [07f6f9f8fe](https://linux-hardware.org/?probe=07f6f9f8fe) | Jan 14, 2021 |
| ASUSTek       | PRIME X470-PRO              | [396227c9b5](https://linux-hardware.org/?probe=396227c9b5) | Jan 14, 2021 |
| MSI           | MPG B550I GAMING EDGE WI... | [c43ddfd32a](https://linux-hardware.org/?probe=c43ddfd32a) | Jan 13, 2021 |
| ASUSTek       | P8Z77-V LX                  | [f631333cfc](https://linux-hardware.org/?probe=f631333cfc) | Jan 13, 2021 |
| MSI           | Z370-A PRO                  | [08f7698393](https://linux-hardware.org/?probe=08f7698393) | Jan 13, 2021 |
| Foxconn       | 2ADA                        | [f51f89648e](https://linux-hardware.org/?probe=f51f89648e) | Jan 13, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | [4f66c556fa](https://linux-hardware.org/?probe=4f66c556fa) | Jan 13, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | [04b6596686](https://linux-hardware.org/?probe=04b6596686) | Jan 13, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [404b2c3391](https://linux-hardware.org/?probe=404b2c3391) | Jan 12, 2021 |
| MSI           | GF615M-P33 V2               | [62cb79908f](https://linux-hardware.org/?probe=62cb79908f) | Jan 12, 2021 |
| Alienware     | 06G6JW A00                  | [992089d02a](https://linux-hardware.org/?probe=992089d02a) | Jan 12, 2021 |
| Lenovo        | Annapurna CRB NOK           | [312134ec25](https://linux-hardware.org/?probe=312134ec25) | Jan 12, 2021 |
| MSI           | X299 TOMAHAWK AC            | [fcca7cb78a](https://linux-hardware.org/?probe=fcca7cb78a) | Jan 12, 2021 |
| ASUSTek       | M4N68T V2                   | [1823efd2b1](https://linux-hardware.org/?probe=1823efd2b1) | Jan 12, 2021 |
| Lenovo        | Annapurna CRB NOK           | [bc287e5f8c](https://linux-hardware.org/?probe=bc287e5f8c) | Jan 11, 2021 |
| ASUSTek       | Maximus VIII HERO ALPHA     | [4f903969f9](https://linux-hardware.org/?probe=4f903969f9) | Jan 11, 2021 |
| ASUSTek       | PRIME B450M-A               | [98a4f93ad6](https://linux-hardware.org/?probe=98a4f93ad6) | Jan 11, 2021 |
| ECS           | Nettle2                     | [53d1c62d82](https://linux-hardware.org/?probe=53d1c62d82) | Jan 10, 2021 |
| HP            | 0A9Ch                       | [b2525701f2](https://linux-hardware.org/?probe=b2525701f2) | Jan 10, 2021 |
| HP            | 0A9Ch                       | [aadfc20149](https://linux-hardware.org/?probe=aadfc20149) | Jan 10, 2021 |
| Dell          | 0M5DCD A00                  | [50d8726c6d](https://linux-hardware.org/?probe=50d8726c6d) | Jan 09, 2021 |
| Gigabyte      | Z97-D3H-CF                  | [8b429c0f9a](https://linux-hardware.org/?probe=8b429c0f9a) | Jan 09, 2021 |
| ASUSTek       | M2N32-SLI DELUXE            | [84531dd458](https://linux-hardware.org/?probe=84531dd458) | Jan 09, 2021 |
| Medion        | MS-7621                     | [70cf4c2f6b](https://linux-hardware.org/?probe=70cf4c2f6b) | Jan 09, 2021 |
| ASUSTek       | Z87-A                       | [b01e929f22](https://linux-hardware.org/?probe=b01e929f22) | Jan 08, 2021 |
| ASUSTek       | H87I-PLUS                   | [be0f998823](https://linux-hardware.org/?probe=be0f998823) | Jan 08, 2021 |
| MSI           | 970A-G43                    | [cd6d9a5ae8](https://linux-hardware.org/?probe=cd6d9a5ae8) | Jan 08, 2021 |
| ASUSTek       | G11CD                       | [145a13d355](https://linux-hardware.org/?probe=145a13d355) | Jan 07, 2021 |
| ASUSTek       | G11CD                       | [dc70a6fae2](https://linux-hardware.org/?probe=dc70a6fae2) | Jan 07, 2021 |
| MSI           | G41M-P26                    | [2b503c1c1d](https://linux-hardware.org/?probe=2b503c1c1d) | Jan 07, 2021 |
| ASUSTek       | P5LD2-VM SE                 | [71eec0354c](https://linux-hardware.org/?probe=71eec0354c) | Jan 07, 2021 |
| ASUSTek       | PRIME B460M-A               | [b1d4490951](https://linux-hardware.org/?probe=b1d4490951) | Jan 07, 2021 |
| ASUSTek       | Z170-P                      | [b554d17cb0](https://linux-hardware.org/?probe=b554d17cb0) | Jan 07, 2021 |
| ASUSTek       | P7H55-M                     | [cdcd41e8ef](https://linux-hardware.org/?probe=cdcd41e8ef) | Jan 06, 2021 |
| Dell          | 0XCR8D A03                  | [35167a79e9](https://linux-hardware.org/?probe=35167a79e9) | Jan 05, 2021 |
| Gigabyte      | Z270X-Gaming K5             | [03674e2272](https://linux-hardware.org/?probe=03674e2272) | Jan 05, 2021 |
| MSI           | B150 GAMING M3              | [000a2f3003](https://linux-hardware.org/?probe=000a2f3003) | Jan 05, 2021 |
| ASUSTek       | M5A97 R2.0                  | [831f1db9fd](https://linux-hardware.org/?probe=831f1db9fd) | Jan 05, 2021 |
| ASUSTek       | M5A97 R2.0                  | [3b17cae83b](https://linux-hardware.org/?probe=3b17cae83b) | Jan 05, 2021 |
| Dell          | 0XCR8D A03                  | [46e1cf3c69](https://linux-hardware.org/?probe=46e1cf3c69) | Jan 05, 2021 |
| Dell          | 0P301D A00                  | [8d9f83f819](https://linux-hardware.org/?probe=8d9f83f819) | Jan 05, 2021 |
| Gigabyte      | H61M-S2PV                   | [e921311031](https://linux-hardware.org/?probe=e921311031) | Jan 05, 2021 |
| MSI           | B150M MORTAR                | [467cca1579](https://linux-hardware.org/?probe=467cca1579) | Jan 04, 2021 |
| ASUSTek       | TUF Gaming B460-PLUS        | [58de9ef8f5](https://linux-hardware.org/?probe=58de9ef8f5) | Jan 04, 2021 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [e15d96307d](https://linux-hardware.org/?probe=e15d96307d) | Jan 04, 2021 |
| ASRock        | X299 Extreme4               | [6781dcc071](https://linux-hardware.org/?probe=6781dcc071) | Jan 04, 2021 |
| ASUSTek       | Yale                        | [1e963acac1](https://linux-hardware.org/?probe=1e963acac1) | Jan 03, 2021 |
| ASUSTek       | Yale                        | [8545be8a2f](https://linux-hardware.org/?probe=8545be8a2f) | Jan 03, 2021 |
| Supermicro    | X10SBA-LA                   | [b463b2c6c6](https://linux-hardware.org/?probe=b463b2c6c6) | Jan 03, 2021 |
| ASUSTek       | P8B75-M LX PLUS             | [32f6fedd00](https://linux-hardware.org/?probe=32f6fedd00) | Jan 03, 2021 |
| ASUSTek       | PRIME X470-PRO              | [393d398d58](https://linux-hardware.org/?probe=393d398d58) | Jan 03, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | [1b172621ff](https://linux-hardware.org/?probe=1b172621ff) | Jan 03, 2021 |
| ASUSTek       | Z87-WS                      | [fb15222989](https://linux-hardware.org/?probe=fb15222989) | Jan 03, 2021 |
| Shuttle       | FX79R                       | [7399beda06](https://linux-hardware.org/?probe=7399beda06) | Jan 03, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [d4b2a29860](https://linux-hardware.org/?probe=d4b2a29860) | Jan 03, 2021 |
| ASUSTek       | TUF X470-PLUS GAMING        | [7b4723037b](https://linux-hardware.org/?probe=7b4723037b) | Jan 03, 2021 |
| MSI           | Z370-A PRO                  | [ad133ca098](https://linux-hardware.org/?probe=ad133ca098) | Jan 02, 2021 |
| ASUSTek       | DIRETTO                     | [ab742e4cf2](https://linux-hardware.org/?probe=ab742e4cf2) | Jan 02, 2021 |
| Lenovo        | SHARKBAY SDK0J40700 WIN     | [3e269ade23](https://linux-hardware.org/?probe=3e269ade23) | Jan 02, 2021 |
| ASUSTek       | P5N73-AM                    | [946a105451](https://linux-hardware.org/?probe=946a105451) | Jan 02, 2021 |
| Acer          | Aspire X3400                | [da9e0d0bb4](https://linux-hardware.org/?probe=da9e0d0bb4) | Jan 02, 2021 |
| MSI           | H310M PRO-M2                | [d3ae82193a](https://linux-hardware.org/?probe=d3ae82193a) | Jan 02, 2021 |
| ASRock        | X470 Master SLI             | [f2c8ec14c7](https://linux-hardware.org/?probe=f2c8ec14c7) | Jan 02, 2021 |
| Gigabyte      | GA-MA790XT-UD4P             | [c1e497d477](https://linux-hardware.org/?probe=c1e497d477) | Jan 01, 2021 |
| ASRock        | ConRoe1333-D667             | [08418bc872](https://linux-hardware.org/?probe=08418bc872) | Jan 01, 2021 |
| ASUSTek       | P5K-VM                      | [f30318eb9d](https://linux-hardware.org/?probe=f30318eb9d) | Dec 31, 2020 |
| ASUSTek       | P8Z68-V PRO GEN3            | [52174c15fa](https://linux-hardware.org/?probe=52174c15fa) | Dec 31, 2020 |
| MSI           | MPG X570 GAMING PLUS        | [ca40fca827](https://linux-hardware.org/?probe=ca40fca827) | Dec 31, 2020 |
| Gigabyte      | B550 AORUS ELITE            | [128d487aed](https://linux-hardware.org/?probe=128d487aed) | Dec 31, 2020 |
| ASUSTek       | PRIME Z390-P                | [2c0474607a](https://linux-hardware.org/?probe=2c0474607a) | Dec 30, 2020 |
| Gigabyte      | H67M-D2-B3                  | [7bfcdf7a25](https://linux-hardware.org/?probe=7bfcdf7a25) | Dec 30, 2020 |
| Gigabyte      | H77M-D3H                    | [3484414f66](https://linux-hardware.org/?probe=3484414f66) | Dec 30, 2020 |
| ASUSTek       | P7P55D-E                    | [2655172fc1](https://linux-hardware.org/?probe=2655172fc1) | Dec 29, 2020 |
| ASUSTek       | P5N73-AM                    | [47d2381c33](https://linux-hardware.org/?probe=47d2381c33) | Dec 29, 2020 |
| MSI           | B85-G43                     | [b4ff0916e6](https://linux-hardware.org/?probe=b4ff0916e6) | Dec 29, 2020 |
| HP            | 18E7                        | [45466acec1](https://linux-hardware.org/?probe=45466acec1) | Dec 29, 2020 |
| ASUSTek       | P8Z68-V PRO GEN3            | [6c082cea20](https://linux-hardware.org/?probe=6c082cea20) | Dec 29, 2020 |
| ASUSTek       | PRIME A320M-K               | [92477de1b5](https://linux-hardware.org/?probe=92477de1b5) | Dec 28, 2020 |
| ASRock        | AB350 Pro4                  | [2fdfa7f06e](https://linux-hardware.org/?probe=2fdfa7f06e) | Dec 28, 2020 |
| MSI           | IONA                        | [491d3cfb92](https://linux-hardware.org/?probe=491d3cfb92) | Dec 28, 2020 |
| ASRock        | ConRoe945G-DVI              | [c80d106ccc](https://linux-hardware.org/?probe=c80d106ccc) | Dec 28, 2020 |
| ASRock        | B450M Pro4                  | [68b993ebcf](https://linux-hardware.org/?probe=68b993ebcf) | Dec 28, 2020 |
| ASUSTek       | P5Q-PRO                     | [237ca98302](https://linux-hardware.org/?probe=237ca98302) | Dec 28, 2020 |
| ASUSTek       | P5Q-PRO                     | [e9352b65c9](https://linux-hardware.org/?probe=e9352b65c9) | Dec 27, 2020 |
| ASUSTek       | X99-E                       | [2747a0f22f](https://linux-hardware.org/?probe=2747a0f22f) | Dec 27, 2020 |
| Gigabyte      | 970A-DS3P                   | [30e511203c](https://linux-hardware.org/?probe=30e511203c) | Dec 26, 2020 |
| ASRock        | B365M-HDV                   | [2e88b8f00b](https://linux-hardware.org/?probe=2e88b8f00b) | Dec 25, 2020 |
| MSI           | 2AE0                        | [57d0f5bc7e](https://linux-hardware.org/?probe=57d0f5bc7e) | Dec 25, 2020 |
| ASUSTek       | M4A87TD/USB3                | [e0d1e76f11](https://linux-hardware.org/?probe=e0d1e76f11) | Dec 25, 2020 |
| Acer          | RS780DV                     | [78c1d5a37b](https://linux-hardware.org/?probe=78c1d5a37b) | Dec 25, 2020 |
| ASUSTek       | P7P55D-E                    | [b762dffefb](https://linux-hardware.org/?probe=b762dffefb) | Dec 25, 2020 |
| Acer          | RS780DV                     | [f5547eeb84](https://linux-hardware.org/?probe=f5547eeb84) | Dec 24, 2020 |
| MSI           | B85-G43 GAMING              | [d9523e89f8](https://linux-hardware.org/?probe=d9523e89f8) | Dec 23, 2020 |
| MSI           | Z87 MPOWER MAX              | [5db0b2dedf](https://linux-hardware.org/?probe=5db0b2dedf) | Dec 23, 2020 |
| ASUSTek       | Hematite-XL                 | [36cfdc4d8d](https://linux-hardware.org/?probe=36cfdc4d8d) | Dec 23, 2020 |
| ASUSTek       | ROG ZENITH EXTREME          | [5fd86e8c94](https://linux-hardware.org/?probe=5fd86e8c94) | Dec 22, 2020 |
| HP            | 8055                        | [fff0e236bb](https://linux-hardware.org/?probe=fff0e236bb) | Dec 21, 2020 |
| ASUSTek       | Z97-DELUXE/USB              | [002ae66585](https://linux-hardware.org/?probe=002ae66585) | Dec 21, 2020 |
| ASUSTek       | Z97-DELUXE/USB              | [9058a3fea9](https://linux-hardware.org/?probe=9058a3fea9) | Dec 21, 2020 |
| Gigabyte      | F2A78M-HD2                  | [e30f78c281](https://linux-hardware.org/?probe=e30f78c281) | Dec 20, 2020 |
| MSI           | 2A9C                        | [63d54bffba](https://linux-hardware.org/?probe=63d54bffba) | Dec 20, 2020 |
| MSI           | 2A9C                        | [e1816a5176](https://linux-hardware.org/?probe=e1816a5176) | Dec 20, 2020 |
| ICP / iEi     | B202 V1.0                   | [820146d4e8](https://linux-hardware.org/?probe=820146d4e8) | Dec 19, 2020 |
| ASUSTek       | PRIME B460-PLUS             | [44a1e79c16](https://linux-hardware.org/?probe=44a1e79c16) | Dec 19, 2020 |
| ASUSTek       | Maximus VIII HERO           | [5e78716779](https://linux-hardware.org/?probe=5e78716779) | Dec 19, 2020 |
| ASUSTek       | Maximus VIII HERO           | [26e22bb193](https://linux-hardware.org/?probe=26e22bb193) | Dec 19, 2020 |
| ASUSTek       | PRIME Z370-P                | [35365be0e8](https://linux-hardware.org/?probe=35365be0e8) | Dec 19, 2020 |
| ASUSTek       | H81M-PLUS                   | [ccb3c7aa09](https://linux-hardware.org/?probe=ccb3c7aa09) | Dec 19, 2020 |
| ASRock        | A320M-HDV R3.0              | [38f82ecb34](https://linux-hardware.org/?probe=38f82ecb34) | Dec 19, 2020 |
| Dell          | 0T656F A02                  | [67a2963aa5](https://linux-hardware.org/?probe=67a2963aa5) | Dec 19, 2020 |
| ASRock        | A320M-HDV R3.0              | [a09c3ee698](https://linux-hardware.org/?probe=a09c3ee698) | Dec 18, 2020 |
| ASUSTek       | P7P55D LE                   | [1ab565d87b](https://linux-hardware.org/?probe=1ab565d87b) | Dec 18, 2020 |
| Acer          | Veriton M430G               | [b125029d45](https://linux-hardware.org/?probe=b125029d45) | Dec 18, 2020 |
| Dell          | 0FM586                      | [288f7e8f18](https://linux-hardware.org/?probe=288f7e8f18) | Dec 17, 2020 |
| Dell          | 0FM586                      | [776ae2e62c](https://linux-hardware.org/?probe=776ae2e62c) | Dec 17, 2020 |
| MSI           | X470 GAMING PRO CARBON      | [a2eed5653d](https://linux-hardware.org/?probe=a2eed5653d) | Dec 17, 2020 |
| Acer          | Aspire X1430                | [6c7210f22c](https://linux-hardware.org/?probe=6c7210f22c) | Dec 17, 2020 |
| Lenovo        | SHARKBAY SDK0J40700 WIN     | [8d5568e7d2](https://linux-hardware.org/?probe=8d5568e7d2) | Dec 17, 2020 |
| Unknown       | MYIR YA157C v2 www.myir-... | [ff25232143](https://linux-hardware.org/?probe=ff25232143) | Dec 16, 2020 |
| Unknown       | MYIR YA157C v2 www.myir-... | [05c9576d64](https://linux-hardware.org/?probe=05c9576d64) | Dec 16, 2020 |
| ASUSTek       | P8P67-M PRO                 | [0cb935df85](https://linux-hardware.org/?probe=0cb935df85) | Dec 16, 2020 |
| ASRock        | G41M-GS3                    | [817f2de699](https://linux-hardware.org/?probe=817f2de699) | Dec 15, 2020 |
| Gigabyte      | GA-73PVM-S2H                | [dae0780e65](https://linux-hardware.org/?probe=dae0780e65) | Dec 15, 2020 |
| Dell          | 0TP412                      | [4ff2139b87](https://linux-hardware.org/?probe=4ff2139b87) | Dec 14, 2020 |
| ASUSTek       | PRIME X570-P                | [381bdcb158](https://linux-hardware.org/?probe=381bdcb158) | Dec 14, 2020 |
| Lenovo        | NOK                         | [a25c051ec2](https://linux-hardware.org/?probe=a25c051ec2) | Dec 14, 2020 |
| ASRock        | G41M-GS3                    | [fa58ed983b](https://linux-hardware.org/?probe=fa58ed983b) | Dec 14, 2020 |
| ASUSTek       | P5Q DELUXE                  | [8f04033a84](https://linux-hardware.org/?probe=8f04033a84) | Dec 12, 2020 |
| ASUSTek       | P5Q DELUXE                  | [27f5bfbeaa](https://linux-hardware.org/?probe=27f5bfbeaa) | Dec 12, 2020 |
| Gigabyte      | 970A-DS3P                   | [5c2ae1fa13](https://linux-hardware.org/?probe=5c2ae1fa13) | Dec 12, 2020 |
| Dell          | 0GDG8Y A00                  | [a829a2256d](https://linux-hardware.org/?probe=a829a2256d) | Dec 12, 2020 |
| HP            | 8056                        | [79fd2c8837](https://linux-hardware.org/?probe=79fd2c8837) | Dec 12, 2020 |
| Acer          | Aspire TC-780               | [5da324cd52](https://linux-hardware.org/?probe=5da324cd52) | Dec 12, 2020 |
| Gigabyte      | B450M DS3H-CF               | [72fb2b557f](https://linux-hardware.org/?probe=72fb2b557f) | Dec 11, 2020 |
| Acer          | Aspire TC-780               | [8126dfd770](https://linux-hardware.org/?probe=8126dfd770) | Dec 11, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [e067c79090](https://linux-hardware.org/?probe=e067c79090) | Dec 11, 2020 |
| Dell          | 0T10XW A01                  | [06f2ce6684](https://linux-hardware.org/?probe=06f2ce6684) | Dec 10, 2020 |
| ASUSTek       | P8P67-M PRO                 | [4ded133d99](https://linux-hardware.org/?probe=4ded133d99) | Dec 10, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [210226a341](https://linux-hardware.org/?probe=210226a341) | Dec 09, 2020 |
| Dell          | 0RW199                      | [ade3fa6dae](https://linux-hardware.org/?probe=ade3fa6dae) | Dec 09, 2020 |
| ASUSTek       | P8H61-M LX R2.0             | [cd8dd46823](https://linux-hardware.org/?probe=cd8dd46823) | Dec 08, 2020 |
| ASUSTek       | P8H61-M LX R2.0             | [4f0145ca57](https://linux-hardware.org/?probe=4f0145ca57) | Dec 08, 2020 |
| ASUSTek       | PRIME A320M-K               | [f2d47c30b4](https://linux-hardware.org/?probe=f2d47c30b4) | Dec 08, 2020 |
| MSI           | X570-A PRO                  | [de6ddf0b90](https://linux-hardware.org/?probe=de6ddf0b90) | Dec 08, 2020 |
| ASUSTek       | TUF X470-PLUS GAMING        | [00dc0236a1](https://linux-hardware.org/?probe=00dc0236a1) | Dec 07, 2020 |
| Gigabyte      | H110M-S2H-CF                | [54986a0bb4](https://linux-hardware.org/?probe=54986a0bb4) | Dec 07, 2020 |
| ASUSTek       | G20CB                       | [c7ac7d0761](https://linux-hardware.org/?probe=c7ac7d0761) | Dec 07, 2020 |
| ASUSTek       | Z170M-PLUS                  | [768553fba0](https://linux-hardware.org/?probe=768553fba0) | Dec 07, 2020 |
| MSI           | GF615M-P33 V2               | [7ba0606c23](https://linux-hardware.org/?probe=7ba0606c23) | Dec 06, 2020 |
| Dell          | 04YP6J A02                  | [6c15ba650c](https://linux-hardware.org/?probe=6c15ba650c) | Dec 06, 2020 |
| Huanan        | X79 V6.11                   | [c53c474f35](https://linux-hardware.org/?probe=c53c474f35) | Dec 06, 2020 |
| Huanan        | X79 V6.11                   | [2c9d9bc82d](https://linux-hardware.org/?probe=2c9d9bc82d) | Dec 06, 2020 |
| ASUSTek       | P5KPL-CM                    | [3a51799fd7](https://linux-hardware.org/?probe=3a51799fd7) | Dec 06, 2020 |
| Gigabyte      | X570 AORUS PRO              | [7d793f9f11](https://linux-hardware.org/?probe=7d793f9f11) | Dec 05, 2020 |
| MSI           | X299 RAIDER                 | [339ac5d6bd](https://linux-hardware.org/?probe=339ac5d6bd) | Dec 04, 2020 |
| ASRock        | G41M-VS3                    | [db0ce92bc9](https://linux-hardware.org/?probe=db0ce92bc9) | Dec 04, 2020 |
| MSI           | Z77A-GD65                   | [da3b838497](https://linux-hardware.org/?probe=da3b838497) | Dec 04, 2020 |
| Medion        | MS-7748                     | [21baf67750](https://linux-hardware.org/?probe=21baf67750) | Dec 03, 2020 |
| ASUSTek       | EMERY                       | [1b9cd9a176](https://linux-hardware.org/?probe=1b9cd9a176) | Dec 03, 2020 |
| ASUSTek       | PRIME B250-PRO              | [04507586ba](https://linux-hardware.org/?probe=04507586ba) | Dec 02, 2020 |
| MSI           | Z87-GD65 GAMING             | [2a74484bc4](https://linux-hardware.org/?probe=2a74484bc4) | Dec 02, 2020 |
| MSI           | X370 GAMING PLUS            | [51b746b135](https://linux-hardware.org/?probe=51b746b135) | Dec 01, 2020 |
| MSI           | X370 GAMING PLUS            | [6895936b8a](https://linux-hardware.org/?probe=6895936b8a) | Dec 01, 2020 |
| Pegatron      | Benicia                     | [3c85925a65](https://linux-hardware.org/?probe=3c85925a65) | Nov 30, 2020 |
| MSI           | H67MA-E35                   | [74c694fc3d](https://linux-hardware.org/?probe=74c694fc3d) | Nov 30, 2020 |
| MSI           | MS-7387                     | [c0b3272c7c](https://linux-hardware.org/?probe=c0b3272c7c) | Nov 29, 2020 |
| HP            | 1905                        | [ffe5e00d8d](https://linux-hardware.org/?probe=ffe5e00d8d) | Nov 29, 2020 |
| ASRock        | X99 Extreme3                | [feac9fa302](https://linux-hardware.org/?probe=feac9fa302) | Nov 29, 2020 |
| ASUSTek       | SABERTOOTH X58              | [3f8230ea85](https://linux-hardware.org/?probe=3f8230ea85) | Nov 29, 2020 |
| eMachines     | EL1352                      | [b7646b7bf3](https://linux-hardware.org/?probe=b7646b7bf3) | Nov 29, 2020 |
| ASUSTek       | E45M1-I DELUXE              | [6e93d9d1b3](https://linux-hardware.org/?probe=6e93d9d1b3) | Nov 29, 2020 |
| MSI           | B350M PRO-VDH               | [28b680c91d](https://linux-hardware.org/?probe=28b680c91d) | Nov 29, 2020 |
| ASUSTek       | P8H77-V LE                  | [6b2618079e](https://linux-hardware.org/?probe=6b2618079e) | Nov 28, 2020 |
| Gigabyte      | B450M DS3H-CF               | [341ccb93dd](https://linux-hardware.org/?probe=341ccb93dd) | Nov 28, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [78d68d35d8](https://linux-hardware.org/?probe=78d68d35d8) | Nov 26, 2020 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | [a00037e95a](https://linux-hardware.org/?probe=a00037e95a) | Nov 25, 2020 |
| eMachines     | WMCP61M                     | [a62a5a1516](https://linux-hardware.org/?probe=a62a5a1516) | Nov 25, 2020 |
| HP            | 1998                        | [15adb8196e](https://linux-hardware.org/?probe=15adb8196e) | Nov 24, 2020 |
| MSI           | GF615M-P33 V2               | [a930c4cd46](https://linux-hardware.org/?probe=a930c4cd46) | Nov 24, 2020 |
| MSI           | 2A9C                        | [6f612dd213](https://linux-hardware.org/?probe=6f612dd213) | Nov 23, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [58a2cd4ba7](https://linux-hardware.org/?probe=58a2cd4ba7) | Nov 23, 2020 |
| Dell          | 0WMJ54 A01                  | [06e21fbf57](https://linux-hardware.org/?probe=06e21fbf57) | Nov 23, 2020 |
| Dell          | 0MM599                      | [23519a176b](https://linux-hardware.org/?probe=23519a176b) | Nov 22, 2020 |
| NEC Comput... | MS-7168                     | [540d992720](https://linux-hardware.org/?probe=540d992720) | Nov 22, 2020 |
| Gigabyte      | MZBSWAP-K4                  | [88fb429442](https://linux-hardware.org/?probe=88fb429442) | Nov 22, 2020 |
| Lenovo        | SHARKBAY SDK0J40700 WIN     | [0669393dce](https://linux-hardware.org/?probe=0669393dce) | Nov 22, 2020 |
| MSI           | FM2-A85XA-G65               | [417f1ef75c](https://linux-hardware.org/?probe=417f1ef75c) | Nov 22, 2020 |
| Lenovo        | SHARKBAY SDK0J40700 WIN     | [cca920fc98](https://linux-hardware.org/?probe=cca920fc98) | Nov 22, 2020 |
| MSI           | B350I PRO AC                | [a6b5a62743](https://linux-hardware.org/?probe=a6b5a62743) | Nov 22, 2020 |
| ASUSTek       | Z97-A-USB31                 | [8bbc1a2d1c](https://linux-hardware.org/?probe=8bbc1a2d1c) | Nov 22, 2020 |
| ASUSTek       | M5A78L                      | [e91e823d16](https://linux-hardware.org/?probe=e91e823d16) | Nov 22, 2020 |
| Dell          | 0M863N A00                  | [4676fa7a39](https://linux-hardware.org/?probe=4676fa7a39) | Nov 22, 2020 |
| Dell          | 0M863N A00                  | [6fdaecb973](https://linux-hardware.org/?probe=6fdaecb973) | Nov 22, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [8865abb1b9](https://linux-hardware.org/?probe=8865abb1b9) | Nov 22, 2020 |
| ASRock        | AB350M Pro4-F               | [1c9e345bc2](https://linux-hardware.org/?probe=1c9e345bc2) | Nov 21, 2020 |
| ECS           | GeForce6100PM-M2            | [ff1cc0b0b7](https://linux-hardware.org/?probe=ff1cc0b0b7) | Nov 21, 2020 |
| Medion        | MS-7728                     | [de2d34055b](https://linux-hardware.org/?probe=de2d34055b) | Nov 21, 2020 |
| ASRock        | X470 Master SLI             | [e0de72e9a0](https://linux-hardware.org/?probe=e0de72e9a0) | Nov 21, 2020 |
| HP            | 1905                        | [a9a5a13cdb](https://linux-hardware.org/?probe=a9a5a13cdb) | Nov 21, 2020 |
| MSI           | B350 PC MATE                | [9935ba7ce5](https://linux-hardware.org/?probe=9935ba7ce5) | Nov 21, 2020 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | [49224bd7f8](https://linux-hardware.org/?probe=49224bd7f8) | Nov 21, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [bb354951ac](https://linux-hardware.org/?probe=bb354951ac) | Nov 20, 2020 |
| Fujitsu       | D3162-C1 S26361-D3162-C1    | [0df60470f2](https://linux-hardware.org/?probe=0df60470f2) | Nov 20, 2020 |
| Foxconn       | 2ADA                        | [4735a99b91](https://linux-hardware.org/?probe=4735a99b91) | Nov 20, 2020 |
| Foxconn       | 2ADA                        | [52b337443a](https://linux-hardware.org/?probe=52b337443a) | Nov 20, 2020 |
| Foxconn       | VL280U Proto1               | [9713f73f82](https://linux-hardware.org/?probe=9713f73f82) | Nov 20, 2020 |
| Foxconn       | VL280U Proto1               | [7e7bfd0b6b](https://linux-hardware.org/?probe=7e7bfd0b6b) | Nov 20, 2020 |
| Gigabyte      | H110M-S2H-CF                | [8bd52edc17](https://linux-hardware.org/?probe=8bd52edc17) | Nov 20, 2020 |
| Gigabyte      | Z97P-D3                     | [f494295959](https://linux-hardware.org/?probe=f494295959) | Nov 19, 2020 |
| Dell          | 048DY8 A01                  | [206fc66c5c](https://linux-hardware.org/?probe=206fc66c5c) | Nov 19, 2020 |
| ASRock        | B450 Gaming K4              | [fda16d7876](https://linux-hardware.org/?probe=fda16d7876) | Nov 19, 2020 |
| Acer          | Veriton L4630G V:1.0        | [5c0c180c3e](https://linux-hardware.org/?probe=5c0c180c3e) | Nov 18, 2020 |
| Gigabyte      | G33M-S2                     | [9a6775f827](https://linux-hardware.org/?probe=9a6775f827) | Nov 18, 2020 |
| Gigabyte      | B450M DS3H-CF               | [1e55cf875e](https://linux-hardware.org/?probe=1e55cf875e) | Nov 18, 2020 |
| ASRock        | B450 Gaming K4              | [fffa4cf39b](https://linux-hardware.org/?probe=fffa4cf39b) | Nov 18, 2020 |
| HP            | 805D                        | [285309d0e6](https://linux-hardware.org/?probe=285309d0e6) | Nov 16, 2020 |
| Gigabyte      | B450M DS3H-CF               | [cef5c1f659](https://linux-hardware.org/?probe=cef5c1f659) | Nov 16, 2020 |
| ASUSTek       | B85-PLUS                    | [2c7971cfaa](https://linux-hardware.org/?probe=2c7971cfaa) | Nov 16, 2020 |
| ASUSTek       | M4A88TD-M EVO               | [f1412d02b3](https://linux-hardware.org/?probe=f1412d02b3) | Nov 16, 2020 |
| ASUSTek       | M4A88TD-M EVO               | [5ae5cfc312](https://linux-hardware.org/?probe=5ae5cfc312) | Nov 16, 2020 |
| Dell          | 0F6X5P A00                  | [c5ed241b08](https://linux-hardware.org/?probe=c5ed241b08) | Nov 16, 2020 |
| ASUSTek       | Leonite2                    | [2b1962317c](https://linux-hardware.org/?probe=2b1962317c) | Nov 16, 2020 |
| Acer          | Aspire X3990                | [b1260bb70f](https://linux-hardware.org/?probe=b1260bb70f) | Nov 16, 2020 |
| ASUSTek       | Leonite2                    | [625266db10](https://linux-hardware.org/?probe=625266db10) | Nov 16, 2020 |
| Medion        | Cattle24 1M                 | [d43c71c240](https://linux-hardware.org/?probe=d43c71c240) | Nov 16, 2020 |
| Acer          | Aspire TC-780               | [0b4d7fef93](https://linux-hardware.org/?probe=0b4d7fef93) | Nov 15, 2020 |
| ICP / iEi     | B202 V1.0                   | [41c7e0250e](https://linux-hardware.org/?probe=41c7e0250e) | Nov 15, 2020 |
| ASUSTek       | NCCH-DL                     | [ed6ebd1f7d](https://linux-hardware.org/?probe=ed6ebd1f7d) | Nov 15, 2020 |
| Gigabyte      | B450 AORUS M                | [af8d47e3e4](https://linux-hardware.org/?probe=af8d47e3e4) | Nov 15, 2020 |
| HP            | 18E5                        | [9da8cd466f](https://linux-hardware.org/?probe=9da8cd466f) | Nov 15, 2020 |
| ASUSTek       | PRIME B360-PLUS             | [dadbc2f1d7](https://linux-hardware.org/?probe=dadbc2f1d7) | Nov 15, 2020 |
| Dell          | 0MH415                      | [e34d3ddcd3](https://linux-hardware.org/?probe=e34d3ddcd3) | Nov 14, 2020 |
| Gigabyte      | 990FXA-UD3                  | [3ff589a01e](https://linux-hardware.org/?probe=3ff589a01e) | Nov 13, 2020 |
| ASRock        | A320M Pro4                  | [b2a79c11d8](https://linux-hardware.org/?probe=b2a79c11d8) | Nov 13, 2020 |
| Gateway       | DT55                        | [b661d61fa1](https://linux-hardware.org/?probe=b661d61fa1) | Nov 13, 2020 |
| MSI           | Z77A-G45                    | [f3741b744f](https://linux-hardware.org/?probe=f3741b744f) | Nov 13, 2020 |
| MSI           | P45-C51                     | [7b15cb83c2](https://linux-hardware.org/?probe=7b15cb83c2) | Nov 13, 2020 |
| Gigabyte      | Z170XP-SLI-CF               | [c440448133](https://linux-hardware.org/?probe=c440448133) | Nov 12, 2020 |
| ASUSTek       | P8Z77-V                     | [d8ea72913e](https://linux-hardware.org/?probe=d8ea72913e) | Nov 12, 2020 |
| MSI           | IONA                        | [641321013b](https://linux-hardware.org/?probe=641321013b) | Nov 12, 2020 |
| MSI           | Z77A-GD65                   | [ec5dc55eee](https://linux-hardware.org/?probe=ec5dc55eee) | Nov 12, 2020 |
| MSI           | IONA                        | [de8a1e2219](https://linux-hardware.org/?probe=de8a1e2219) | Nov 12, 2020 |
| ASUSTek       | A8N-SLI DELUXE              | [c16c928715](https://linux-hardware.org/?probe=c16c928715) | Nov 12, 2020 |
| Gigabyte      | P35-DS3R                    | [15abd6a7a8](https://linux-hardware.org/?probe=15abd6a7a8) | Nov 12, 2020 |
| ASRock        | G41M-VS3                    | [8c58b0ab33](https://linux-hardware.org/?probe=8c58b0ab33) | Nov 11, 2020 |
| ASUSTek       | PRIME A320M-K               | [6f875042da](https://linux-hardware.org/?probe=6f875042da) | Nov 11, 2020 |
| ASUSTek       | Maximus VIII HERO           | [93c156a472](https://linux-hardware.org/?probe=93c156a472) | Nov 11, 2020 |
| ASRock        | B550M-ITX/ac                | [f38bf2204e](https://linux-hardware.org/?probe=f38bf2204e) | Nov 11, 2020 |
| ASRock        | Z370M-ITX/ac                | [41f557e471](https://linux-hardware.org/?probe=41f557e471) | Nov 11, 2020 |
| Gigabyte      | 970A-DS3P                   | [927e9227f3](https://linux-hardware.org/?probe=927e9227f3) | Nov 11, 2020 |
| MSI           | B450 GAMING PLUS            | [aee4bc71f3](https://linux-hardware.org/?probe=aee4bc71f3) | Nov 10, 2020 |
| HP            | 18E5                        | [cb560d2290](https://linux-hardware.org/?probe=cb560d2290) | Nov 10, 2020 |
| MSI           | X470 GAMING PLUS MAX        | [899d0241cd](https://linux-hardware.org/?probe=899d0241cd) | Nov 09, 2020 |
| HP            | 8459                        | [930627db04](https://linux-hardware.org/?probe=930627db04) | Nov 08, 2020 |
| Gigabyte      | 970A-DS3P                   | [e60de252d1](https://linux-hardware.org/?probe=e60de252d1) | Nov 07, 2020 |
| Gigabyte      | B85M-D3H                    | [cdd1a3be02](https://linux-hardware.org/?probe=cdd1a3be02) | Nov 07, 2020 |
| Dell          | 0KP561                      | [04c5cfb3aa](https://linux-hardware.org/?probe=04c5cfb3aa) | Nov 07, 2020 |
| Dell          | 0TP412                      | [ca6e39eeb9](https://linux-hardware.org/?probe=ca6e39eeb9) | Nov 07, 2020 |
| Gigabyte      | P55A-UD3R                   | [85263f2c12](https://linux-hardware.org/?probe=85263f2c12) | Nov 07, 2020 |
| ASUSTek       | P5Q-PRO                     | [435c7df04c](https://linux-hardware.org/?probe=435c7df04c) | Nov 07, 2020 |
| ASUSTek       | A8N-SLI Premium             | [f2bab5cd08](https://linux-hardware.org/?probe=f2bab5cd08) | Nov 07, 2020 |
| ASUSTek       | Z170-K                      | [80cac509cd](https://linux-hardware.org/?probe=80cac509cd) | Nov 06, 2020 |
| Lenovo        | ThinkCentre M90 5485WFL     | [e57019aa03](https://linux-hardware.org/?probe=e57019aa03) | Nov 06, 2020 |
| Acer          | Aspire X1430                | [f85cca62c6](https://linux-hardware.org/?probe=f85cca62c6) | Nov 05, 2020 |
| ASUSTek       | M4N98TD EVO                 | [6c7624949a](https://linux-hardware.org/?probe=6c7624949a) | Nov 05, 2020 |
| Dell          | 0TDG4V A00                  | [7bcf7e8ada](https://linux-hardware.org/?probe=7bcf7e8ada) | Nov 05, 2020 |
| ASRock        | FM2A88X+ Killer             | [51a4e59bff](https://linux-hardware.org/?probe=51a4e59bff) | Nov 05, 2020 |
| Gigabyte      | H110M-S2H-CF                | [3c00fc3ec5](https://linux-hardware.org/?probe=3c00fc3ec5) | Nov 05, 2020 |
| HP            | 845A                        | [07a03c62c8](https://linux-hardware.org/?probe=07a03c62c8) | Nov 05, 2020 |
| HP            | 845A                        | [30bac157d5](https://linux-hardware.org/?probe=30bac157d5) | Nov 05, 2020 |
| Gigabyte      | P55A-UD3                    | [3d4bf2864e](https://linux-hardware.org/?probe=3d4bf2864e) | Nov 04, 2020 |
| MSI           | B250M PRO-VDH               | [262aa524ea](https://linux-hardware.org/?probe=262aa524ea) | Nov 04, 2020 |
| HP            | 8436                        | [94e092d727](https://linux-hardware.org/?probe=94e092d727) | Nov 04, 2020 |
| Gigabyte      | GA-K8N-SLi                  | [944775d347](https://linux-hardware.org/?probe=944775d347) | Nov 03, 2020 |
| ASUSTek       | PRIME B450M-A               | [71733fbf6f](https://linux-hardware.org/?probe=71733fbf6f) | Nov 03, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [476ecabe25](https://linux-hardware.org/?probe=476ecabe25) | Nov 03, 2020 |
| Gigabyte      | Z77X-UP5 TH-CF              | [f58d2eb476](https://linux-hardware.org/?probe=f58d2eb476) | Nov 03, 2020 |
| HP            | PX591AA-ABF w5046.fr        | [577c409ce7](https://linux-hardware.org/?probe=577c409ce7) | Nov 02, 2020 |
| Medion        | H81H3-EM2                   | [fb68163ab1](https://linux-hardware.org/?probe=fb68163ab1) | Nov 02, 2020 |
| ASRock        | G41M-VS3                    | [4792113587](https://linux-hardware.org/?probe=4792113587) | Nov 02, 2020 |
| MSI           | B75A-G41                    | [cc006c2cf2](https://linux-hardware.org/?probe=cc006c2cf2) | Nov 02, 2020 |
| Gigabyte      | F2A78M-DS2                  | [ffa7fd26a5](https://linux-hardware.org/?probe=ffa7fd26a5) | Nov 01, 2020 |
| Gigabyte      | GA-880GM-UD2H               | [2fe3e165eb](https://linux-hardware.org/?probe=2fe3e165eb) | Oct 31, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [07081ea2ef](https://linux-hardware.org/?probe=07081ea2ef) | Oct 31, 2020 |
| MSI           | Z87 MPOWER MAX              | [c4f4df2ec5](https://linux-hardware.org/?probe=c4f4df2ec5) | Oct 31, 2020 |
| Pegatron      | Narra6                      | [85fb4a9535](https://linux-hardware.org/?probe=85fb4a9535) | Oct 30, 2020 |
| MSI           | MPG B550I GAMING EDGE WI... | [a225772655](https://linux-hardware.org/?probe=a225772655) | Oct 30, 2020 |
| Gigabyte      | X570 GAMING X               | [cdd915b358](https://linux-hardware.org/?probe=cdd915b358) | Oct 30, 2020 |
| MSI           | B250I GAMING PRO AC         | [bbfbcdc505](https://linux-hardware.org/?probe=bbfbcdc505) | Oct 30, 2020 |
| MSI           | 2A9C                        | [468654bc97](https://linux-hardware.org/?probe=468654bc97) | Oct 30, 2020 |
| ASUSTek       | P5B-PLUS Series             | [e6506fe0a4](https://linux-hardware.org/?probe=e6506fe0a4) | Oct 30, 2020 |
| ASRock        | B450M Steel Legend          | [d67299180d](https://linux-hardware.org/?probe=d67299180d) | Oct 30, 2020 |
| ASUSTek       | P5B-PLUS Series             | [45d470edbf](https://linux-hardware.org/?probe=45d470edbf) | Oct 30, 2020 |
| MSI           | Z270 SLI                    | [f8adb0fcd7](https://linux-hardware.org/?probe=f8adb0fcd7) | Oct 29, 2020 |
| ASRock        | A320M-HDV R3.0              | [6599258a10](https://linux-hardware.org/?probe=6599258a10) | Oct 29, 2020 |
| MSI           | Z87 MPOWER MAX              | [beeb97510d](https://linux-hardware.org/?probe=beeb97510d) | Oct 29, 2020 |
| ASUSTek       | H81M-PLUS                   | [81d7477f57](https://linux-hardware.org/?probe=81d7477f57) | Oct 29, 2020 |
| ASUSTek       | Maximus V GENE              | [253b5aba98](https://linux-hardware.org/?probe=253b5aba98) | Oct 29, 2020 |
| MSI           | Z270 PC MATE                | [8a4a642906](https://linux-hardware.org/?probe=8a4a642906) | Oct 28, 2020 |
| eMachines     | WMCP61M                     | [86ee279d47](https://linux-hardware.org/?probe=86ee279d47) | Oct 27, 2020 |
| HP            | 8455                        | [0671b6f4da](https://linux-hardware.org/?probe=0671b6f4da) | Oct 27, 2020 |
| ASUSTek       | P7P55D-E                    | [56203fe528](https://linux-hardware.org/?probe=56203fe528) | Oct 27, 2020 |
| Lenovo        | 7Y45CTO1WW                  | [97cb93281b](https://linux-hardware.org/?probe=97cb93281b) | Oct 27, 2020 |
| HP            | 8455                        | [e37d606b6b](https://linux-hardware.org/?probe=e37d606b6b) | Oct 26, 2020 |
| MSI           | H97 PC Mate                 | [7d2833c2f9](https://linux-hardware.org/?probe=7d2833c2f9) | Oct 25, 2020 |
| Intel         | DP67BG AAG10491-307         | [eb0f8ebda9](https://linux-hardware.org/?probe=eb0f8ebda9) | Oct 25, 2020 |
| Intel         | DP67BG AAG10491-307         | [eac3ee0282](https://linux-hardware.org/?probe=eac3ee0282) | Oct 24, 2020 |
| Pegatron      | 2A94                        | [bbca9f3f38](https://linux-hardware.org/?probe=bbca9f3f38) | Oct 24, 2020 |
| Pegatron      | 2A94                        | [37af6edb96](https://linux-hardware.org/?probe=37af6edb96) | Oct 24, 2020 |
| ASUSTek       | SABERTOOTH X58              | [ebfe736036](https://linux-hardware.org/?probe=ebfe736036) | Oct 23, 2020 |
| ASUSTek       | PRIME A320M-K               | [3c2d2515cd](https://linux-hardware.org/?probe=3c2d2515cd) | Oct 23, 2020 |
| ASRock        | G41C-GS                     | [0dc964b3c0](https://linux-hardware.org/?probe=0dc964b3c0) | Oct 23, 2020 |
| ASRock        | G41C-GS                     | [43ffb45024](https://linux-hardware.org/?probe=43ffb45024) | Oct 23, 2020 |
| MSI           | A320M PRO-VD/S V2           | [30ea0e0ae1](https://linux-hardware.org/?probe=30ea0e0ae1) | Oct 23, 2020 |
| Dell          | 0Y2K8N A00                  | [09848e9b64](https://linux-hardware.org/?probe=09848e9b64) | Oct 21, 2020 |
| Dell          | 0Y2K8N A00                  | [1453c9a529](https://linux-hardware.org/?probe=1453c9a529) | Oct 21, 2020 |
| ASUSTek       | H87M-PRO                    | [f624a97989](https://linux-hardware.org/?probe=f624a97989) | Oct 21, 2020 |
| HP            | 8436                        | [4445219a59](https://linux-hardware.org/?probe=4445219a59) | Oct 20, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [c4af7339cb](https://linux-hardware.org/?probe=c4af7339cb) | Oct 20, 2020 |
| Dell          | 0GN6JF A01                  | [9933622af0](https://linux-hardware.org/?probe=9933622af0) | Oct 20, 2020 |
| Dell          | 0GN6JF A01                  | [b5b4c17e52](https://linux-hardware.org/?probe=b5b4c17e52) | Oct 20, 2020 |
| Medion        | H81H3-EM2                   | [036cb30b41](https://linux-hardware.org/?probe=036cb30b41) | Oct 19, 2020 |
| HP            | 0A5Ch                       | [ea9111fddf](https://linux-hardware.org/?probe=ea9111fddf) | Oct 19, 2020 |
| HP            | 0A5Ch                       | [2d9232cb5e](https://linux-hardware.org/?probe=2d9232cb5e) | Oct 18, 2020 |
| Intel         | DH67CF AAG10215-207         | [bdad9ec53e](https://linux-hardware.org/?probe=bdad9ec53e) | Oct 18, 2020 |
| Gigabyte      | Z87-D3HP-CF                 | [ba30541ce8](https://linux-hardware.org/?probe=ba30541ce8) | Oct 17, 2020 |
| Gigabyte      | 970A-DS3P                   | [497d123503](https://linux-hardware.org/?probe=497d123503) | Oct 17, 2020 |
| Gigabyte      | 970A-DS3P                   | [3ee2376d82](https://linux-hardware.org/?probe=3ee2376d82) | Oct 17, 2020 |
| ASRock        | G41M-VS3                    | [ec67326e58](https://linux-hardware.org/?probe=ec67326e58) | Oct 17, 2020 |
| HP            | 805F                        | [253d13c796](https://linux-hardware.org/?probe=253d13c796) | Oct 16, 2020 |
| Gigabyte      | H81M-HD3                    | [8717143fd2](https://linux-hardware.org/?probe=8717143fd2) | Oct 15, 2020 |
| Intel         | DN2800MT AAG81515-900       | [bce81e5e09](https://linux-hardware.org/?probe=bce81e5e09) | Oct 14, 2020 |
| Intel         | DN2800MT AAG81515-900       | [e02177cc6b](https://linux-hardware.org/?probe=e02177cc6b) | Oct 14, 2020 |
| ASRock        | A320M-HDV R4.0              | [753273ae7d](https://linux-hardware.org/?probe=753273ae7d) | Oct 14, 2020 |
| MSI           | MPG X570 GAMING EDGE WIF... | [11affeff47](https://linux-hardware.org/?probe=11affeff47) | Oct 14, 2020 |
| Gigabyte      | B450 AORUS M                | [2bbb556fce](https://linux-hardware.org/?probe=2bbb556fce) | Oct 14, 2020 |
| Acer          | F690GVM                     | [ddd4875afc](https://linux-hardware.org/?probe=ddd4875afc) | Oct 14, 2020 |
| Acer          | Aspire X3400                | [4f32e6a1ff](https://linux-hardware.org/?probe=4f32e6a1ff) | Oct 13, 2020 |
| ASRock        | B85 Anniversary             | [556e5734b2](https://linux-hardware.org/?probe=556e5734b2) | Oct 13, 2020 |
| Intel         | D34010WYB H14771-304        | [45610fc866](https://linux-hardware.org/?probe=45610fc866) | Oct 13, 2020 |
| ASUSTek       | M4A785TD-V EVO              | [a81dcdea30](https://linux-hardware.org/?probe=a81dcdea30) | Oct 13, 2020 |
| MSI           | MPG X570 GAMING PLUS        | [32d5a3fc79](https://linux-hardware.org/?probe=32d5a3fc79) | Oct 13, 2020 |
| Dell          | 06NWYK A00                  | [2ccb5912f9](https://linux-hardware.org/?probe=2ccb5912f9) | Oct 12, 2020 |
| ASUSTek       | P5QL-E                      | [ddbfba67ab](https://linux-hardware.org/?probe=ddbfba67ab) | Oct 12, 2020 |
| ASUSTek       | X99-A/USB                   | [312aff2ed7](https://linux-hardware.org/?probe=312aff2ed7) | Oct 12, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [eed7ced527](https://linux-hardware.org/?probe=eed7ced527) | Oct 11, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [9c37b1dfff](https://linux-hardware.org/?probe=9c37b1dfff) | Oct 11, 2020 |
| MSI           | H97M-E35                    | [583794cac0](https://linux-hardware.org/?probe=583794cac0) | Oct 10, 2020 |
| MSI           | B250M PRO-VDH               | [9394b5714e](https://linux-hardware.org/?probe=9394b5714e) | Oct 10, 2020 |
| Medion        | MS-7681                     | [9eadfdb4d0](https://linux-hardware.org/?probe=9eadfdb4d0) | Oct 09, 2020 |
| Acer          | Aspire X3400                | [d3e4761754](https://linux-hardware.org/?probe=d3e4761754) | Oct 09, 2020 |
| Foxconn       | 2ABF                        | [2c77c76b2b](https://linux-hardware.org/?probe=2c77c76b2b) | Oct 09, 2020 |
| Pegatron      | Narra6                      | [ae8fcaeb4c](https://linux-hardware.org/?probe=ae8fcaeb4c) | Oct 09, 2020 |
| Dell          | 040DDP A01                  | [19dcddc1fe](https://linux-hardware.org/?probe=19dcddc1fe) | Oct 09, 2020 |
| ASRock        | FM2A88M-HD+                 | [a77811a56d](https://linux-hardware.org/?probe=a77811a56d) | Oct 09, 2020 |
| ASUSTek       | P1801                       | [dc14d61e5f](https://linux-hardware.org/?probe=dc14d61e5f) | Oct 09, 2020 |
| Intel         | DH67VR AAG27177-201         | [5b097d2b44](https://linux-hardware.org/?probe=5b097d2b44) | Oct 09, 2020 |
| ASUSTek       | Z87-A                       | [7e99ba9f73](https://linux-hardware.org/?probe=7e99ba9f73) | Oct 08, 2020 |
| MSI           | 970 GAMING                  | [ba80d79115](https://linux-hardware.org/?probe=ba80d79115) | Oct 07, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [1220e3f380](https://linux-hardware.org/?probe=1220e3f380) | Oct 07, 2020 |
| ASUSTek       | Z87-A                       | [2d408481fe](https://linux-hardware.org/?probe=2d408481fe) | Oct 07, 2020 |
| MSI           | Z77A-G43                    | [cf1c8121f9](https://linux-hardware.org/?probe=cf1c8121f9) | Oct 07, 2020 |
| MSI           | Z87-GD65 GAMING             | [d986be730d](https://linux-hardware.org/?probe=d986be730d) | Oct 06, 2020 |
| ASUSTek       | P8Z68-V PRO GEN3            | [e957d20716](https://linux-hardware.org/?probe=e957d20716) | Oct 06, 2020 |
| ASUSTek       | P8Z68-V PRO GEN3            | [44e2e9b579](https://linux-hardware.org/?probe=44e2e9b579) | Oct 06, 2020 |
| Gigabyte      | X570 GAMING X               | [1d28040300](https://linux-hardware.org/?probe=1d28040300) | Oct 05, 2020 |
| MSI           | Z77A-G41                    | [188aee1ef2](https://linux-hardware.org/?probe=188aee1ef2) | Oct 05, 2020 |
| ASRock        | A320M-HDV R3.0              | [c4ccc34194](https://linux-hardware.org/?probe=c4ccc34194) | Oct 05, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [38f25ef4a4](https://linux-hardware.org/?probe=38f25ef4a4) | Oct 04, 2020 |
| ASUSTek       | P5Q-PRO                     | [6c08d1ce47](https://linux-hardware.org/?probe=6c08d1ce47) | Oct 04, 2020 |
| HP            | 339A                        | [92af508797](https://linux-hardware.org/?probe=92af508797) | Oct 04, 2020 |
| ASUSTek       | ET2221I-B85                 | [bed3d173a3](https://linux-hardware.org/?probe=bed3d173a3) | Oct 03, 2020 |
| Gigabyte      | G31M-S2L                    | [d3956958c8](https://linux-hardware.org/?probe=d3956958c8) | Oct 03, 2020 |
| Acer          | Aspire XC-830               | [f4a16946cf](https://linux-hardware.org/?probe=f4a16946cf) | Oct 03, 2020 |
| ASUSTek       | P8H67                       | [da384f423d](https://linux-hardware.org/?probe=da384f423d) | Oct 02, 2020 |
| MSI           | Z87-GD65 GAMING             | [689c105058](https://linux-hardware.org/?probe=689c105058) | Oct 02, 2020 |
| MSI           | X399 SLI PLUS               | [1eda24a79d](https://linux-hardware.org/?probe=1eda24a79d) | Oct 02, 2020 |
| ASUSTek       | PRIME B350-PLUS             | [7677555e7a](https://linux-hardware.org/?probe=7677555e7a) | Oct 01, 2020 |
| ASUSTek       | TUF B450-PLUS GAMING        | [c5e4327934](https://linux-hardware.org/?probe=c5e4327934) | Oct 01, 2020 |
| AZW           | AP35                        | [f061d53d82](https://linux-hardware.org/?probe=f061d53d82) | Oct 01, 2020 |
| ASUSTek       | ET2221I-B85                 | [9cb36ac60f](https://linux-hardware.org/?probe=9cb36ac60f) | Oct 01, 2020 |
| ASRock        | FM2A88M-HD+                 | [94f8834aad](https://linux-hardware.org/?probe=94f8834aad) | Oct 01, 2020 |
| MSI           | B450M PRO-M2 V2             | [818f9519dc](https://linux-hardware.org/?probe=818f9519dc) | Oct 01, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [3e4e76ba74](https://linux-hardware.org/?probe=3e4e76ba74) | Sep 30, 2020 |
| ASUSTek       | P5K                         | [c3b03a40db](https://linux-hardware.org/?probe=c3b03a40db) | Sep 30, 2020 |
| Gigabyte      | H97N-WIFI                   | [1c88f1efcd](https://linux-hardware.org/?probe=1c88f1efcd) | Sep 29, 2020 |
| MSI           | C847IS-P33                  | [316f66e76c](https://linux-hardware.org/?probe=316f66e76c) | Sep 29, 2020 |
| MSI           | Z270 GAMING PRO CARBON      | [f8258cf616](https://linux-hardware.org/?probe=f8258cf616) | Sep 28, 2020 |
| MSI           | Z270 GAMING PRO CARBON      | [5c87fbeabf](https://linux-hardware.org/?probe=5c87fbeabf) | Sep 28, 2020 |
| ASRock        | X570 Pro4                   | [559f9c9d14](https://linux-hardware.org/?probe=559f9c9d14) | Sep 28, 2020 |
| Acer          | Aspire TC-780               | [fe6ee985a5](https://linux-hardware.org/?probe=fe6ee985a5) | Sep 28, 2020 |
| ASUSTek       | Maximus VIII FORMULA        | [1fb5365014](https://linux-hardware.org/?probe=1fb5365014) | Sep 28, 2020 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | [c0dddfdadc](https://linux-hardware.org/?probe=c0dddfdadc) | Sep 27, 2020 |
| ASUSTek       | STRIX X99 GAMING            | [3d370043c6](https://linux-hardware.org/?probe=3d370043c6) | Sep 26, 2020 |
| HP            | 843F                        | [a1563ed731](https://linux-hardware.org/?probe=a1563ed731) | Sep 25, 2020 |
| HP            | 81C3                        | [354ceb04d4](https://linux-hardware.org/?probe=354ceb04d4) | Sep 25, 2020 |
| ASUSTek       | STRIX X99 GAMING            | [cac9e0576f](https://linux-hardware.org/?probe=cac9e0576f) | Sep 24, 2020 |
| ASRock        | G41M-GS3                    | [52aeb5fa3b](https://linux-hardware.org/?probe=52aeb5fa3b) | Sep 24, 2020 |
| Pegatron      | 2AF0                        | [c38ae69c79](https://linux-hardware.org/?probe=c38ae69c79) | Sep 24, 2020 |
| Dell          | 02K9CR A01                  | [c2e31c7ce8](https://linux-hardware.org/?probe=c2e31c7ce8) | Sep 24, 2020 |
| Dell          | 0F6X5P A00                  | [a1cbd8f918](https://linux-hardware.org/?probe=a1cbd8f918) | Sep 23, 2020 |
| ASUSTek       | M4A785TD-M EVO              | [276d93eddf](https://linux-hardware.org/?probe=276d93eddf) | Sep 23, 2020 |
| ASUSTek       | M4A785TD-M EVO              | [019fcca808](https://linux-hardware.org/?probe=019fcca808) | Sep 22, 2020 |
| Dell          | 0F6X5P A00                  | [0b548f3a3f](https://linux-hardware.org/?probe=0b548f3a3f) | Sep 22, 2020 |
| ASRock        | A320M-HDV R3.0              | [5e9a974b53](https://linux-hardware.org/?probe=5e9a974b53) | Sep 21, 2020 |
| ASRock        | A320M-HDV R3.0              | [7c00255c2f](https://linux-hardware.org/?probe=7c00255c2f) | Sep 21, 2020 |
| ASUSTek       | STRIX Z270E GAMING          | [dc11756a9e](https://linux-hardware.org/?probe=dc11756a9e) | Sep 21, 2020 |
| ASUSTek       | PRIME X470-PRO              | [6cdbdb17ef](https://linux-hardware.org/?probe=6cdbdb17ef) | Sep 21, 2020 |
| MSI           | MPG Z390 GAMING EDGE AC     | [de8040f8f2](https://linux-hardware.org/?probe=de8040f8f2) | Sep 20, 2020 |
| ASUSTek       | M2N68-AM Plus               | [7f8e568705](https://linux-hardware.org/?probe=7f8e568705) | Sep 20, 2020 |
| ASUSTek       | P8H61-MX USB3               | [2def8c0128](https://linux-hardware.org/?probe=2def8c0128) | Sep 19, 2020 |
| ASUSTek       | PRIME A320M-K               | [824fc83ef8](https://linux-hardware.org/?probe=824fc83ef8) | Sep 18, 2020 |
| Gigabyte      | Z390 M GAMING-CF            | [e08a1d60e8](https://linux-hardware.org/?probe=e08a1d60e8) | Sep 18, 2020 |
| ASRock        | A320M-HDV R3.0              | [70911dd742](https://linux-hardware.org/?probe=70911dd742) | Sep 18, 2020 |
| Dell          | 06NWYK A00                  | [02ffd06512](https://linux-hardware.org/?probe=02ffd06512) | Sep 16, 2020 |
| HP            | 0A64h                       | [f329c9fbec](https://linux-hardware.org/?probe=f329c9fbec) | Sep 16, 2020 |
| ASUSTek       | H81M-C                      | [b062c35766](https://linux-hardware.org/?probe=b062c35766) | Sep 16, 2020 |
| OEM           | Kabylake JHS62N             | [e8de401182](https://linux-hardware.org/?probe=e8de401182) | Sep 16, 2020 |
| Foxconn       | 2AAF                        | [b435a34320](https://linux-hardware.org/?probe=b435a34320) | Sep 15, 2020 |
| Dell          | 0XJ8C4 A00                  | [4c6f76d2e4](https://linux-hardware.org/?probe=4c6f76d2e4) | Sep 15, 2020 |
| ASUSTek       | STRIX X99 GAMING            | [d22f9784a7](https://linux-hardware.org/?probe=d22f9784a7) | Sep 14, 2020 |
| ASUSTek       | H87-PLUS                    | [dfba4f1752](https://linux-hardware.org/?probe=dfba4f1752) | Sep 14, 2020 |
| ASUSTek       | G11CD                       | [962d52b690](https://linux-hardware.org/?probe=962d52b690) | Sep 14, 2020 |
| ASUSTek       | G11CD                       | [a663586db5](https://linux-hardware.org/?probe=a663586db5) | Sep 14, 2020 |
| ASRock        | A300M-STX                   | [e44fe51292](https://linux-hardware.org/?probe=e44fe51292) | Sep 13, 2020 |
| ASRock        | A300M-STX                   | [7365686a0b](https://linux-hardware.org/?probe=7365686a0b) | Sep 13, 2020 |
| ASRock        | A320M-HDV R3.0              | [c9cdefc34c](https://linux-hardware.org/?probe=c9cdefc34c) | Sep 13, 2020 |
| Gigabyte      | H77-DS3H                    | [65dd1fb23a](https://linux-hardware.org/?probe=65dd1fb23a) | Sep 13, 2020 |
| ASRock        | A320M-HDV R3.0              | [d33962bb92](https://linux-hardware.org/?probe=d33962bb92) | Sep 13, 2020 |
| ASUSTek       | P5LD2-Deluxe                | [0c5611fcc9](https://linux-hardware.org/?probe=0c5611fcc9) | Sep 12, 2020 |
| ASUSTek       | P5LD2                       | [924fc4be69](https://linux-hardware.org/?probe=924fc4be69) | Sep 12, 2020 |
| ASUSTek       | P7P55D-E LX                 | [c58648ff5c](https://linux-hardware.org/?probe=c58648ff5c) | Sep 12, 2020 |
| ASRock        | B450M Pro4-F                | [5ff85a124a](https://linux-hardware.org/?probe=5ff85a124a) | Sep 12, 2020 |
| HP            | 158A                        | [721bc97aa8](https://linux-hardware.org/?probe=721bc97aa8) | Sep 11, 2020 |
| ASRock        | X470 Master SLI             | [9968dc910c](https://linux-hardware.org/?probe=9968dc910c) | Sep 10, 2020 |
| ASRock        | X470 Master SLI             | [2ae445db73](https://linux-hardware.org/?probe=2ae445db73) | Sep 10, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [d8d560feb2](https://linux-hardware.org/?probe=d8d560feb2) | Sep 09, 2020 |
| ASRock        | G41M-VS3                    | [618e865492](https://linux-hardware.org/?probe=618e865492) | Sep 09, 2020 |
| ASUSTek       | PRIME X470-PRO              | [a4973bc555](https://linux-hardware.org/?probe=a4973bc555) | Sep 09, 2020 |
| MSI           | MS-7358 Fab D               | [1927a0da3f](https://linux-hardware.org/?probe=1927a0da3f) | Sep 09, 2020 |
| HP            | 82F2                        | [b0a2f3a18c](https://linux-hardware.org/?probe=b0a2f3a18c) | Sep 09, 2020 |
| Gigabyte      | Z390 M GAMING-CF            | [8f6a0c6345](https://linux-hardware.org/?probe=8f6a0c6345) | Sep 08, 2020 |
| ASUSTek       | H87-PLUS                    | [ad2897518b](https://linux-hardware.org/?probe=ad2897518b) | Sep 08, 2020 |
| ASUSTek       | P5K                         | [ce6dc8bcd9](https://linux-hardware.org/?probe=ce6dc8bcd9) | Sep 08, 2020 |
| MSI           | Boston                      | [f29a79fd9d](https://linux-hardware.org/?probe=f29a79fd9d) | Sep 08, 2020 |
| MSI           | B450M MORTAR MAX            | [72e57dd8ad](https://linux-hardware.org/?probe=72e57dd8ad) | Sep 07, 2020 |
| ASUSTek       | EB1501P                     | [6f97b62a32](https://linux-hardware.org/?probe=6f97b62a32) | Sep 07, 2020 |
| ASUSTek       | P5LD2EB2-DHS                | [3c62df51c9](https://linux-hardware.org/?probe=3c62df51c9) | Sep 07, 2020 |
| MSI           | X370 GAMING PRO CARBON      | [2cb82dda4a](https://linux-hardware.org/?probe=2cb82dda4a) | Sep 06, 2020 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [968094fc1f](https://linux-hardware.org/?probe=968094fc1f) | Sep 06, 2020 |
| ASRock        | A320M-HDV R3.0              | [447cfb5f92](https://linux-hardware.org/?probe=447cfb5f92) | Sep 06, 2020 |
| AZW           | AP35                        | [57c2508765](https://linux-hardware.org/?probe=57c2508765) | Sep 06, 2020 |
| MSI           | MPG X570 GAMING PRO CARB... | [b4cb07b4d6](https://linux-hardware.org/?probe=b4cb07b4d6) | Sep 05, 2020 |
| ASUSTek       | Z170-A                      | [543b18512b](https://linux-hardware.org/?probe=543b18512b) | Sep 05, 2020 |
| MSI           | Z87M GAMING                 | [bbbf80a444](https://linux-hardware.org/?probe=bbbf80a444) | Sep 05, 2020 |
| Gigabyte      | H81M-DS2V                   | [1e5936fd20](https://linux-hardware.org/?probe=1e5936fd20) | Sep 05, 2020 |
| ASUSTek       | H87-PLUS                    | [1602fc1f70](https://linux-hardware.org/?probe=1602fc1f70) | Sep 04, 2020 |
| ASUSTek       | P8Z77-V LK                  | [2a5b8ffdcc](https://linux-hardware.org/?probe=2a5b8ffdcc) | Sep 04, 2020 |
| ASUSTek       | H87-PLUS                    | [e28e4f4e11](https://linux-hardware.org/?probe=e28e4f4e11) | Sep 04, 2020 |
| MSI           | Z77A-G45                    | [278850fdd4](https://linux-hardware.org/?probe=278850fdd4) | Sep 04, 2020 |
| ASUSTek       | TUF B450-PLUS GAMING        | [5c361a6bab](https://linux-hardware.org/?probe=5c361a6bab) | Sep 03, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [fcf2bff910](https://linux-hardware.org/?probe=fcf2bff910) | Sep 03, 2020 |
| ASUSTek       | PRIME X470-PRO              | [4e517ea925](https://linux-hardware.org/?probe=4e517ea925) | Sep 03, 2020 |
| Gigabyte      | B450M DS3H-CF               | [ecd644b602](https://linux-hardware.org/?probe=ecd644b602) | Sep 03, 2020 |
| ASUSTek       | PRIME X570-PRO              | [518f7c6e38](https://linux-hardware.org/?probe=518f7c6e38) | Sep 03, 2020 |
| eMachines     | EL1350                      | [3574107a8b](https://linux-hardware.org/?probe=3574107a8b) | Sep 03, 2020 |
| ASRock        | X470 Master SLI             | [03bcf3b1fd](https://linux-hardware.org/?probe=03bcf3b1fd) | Sep 02, 2020 |
| Gigabyte      | AB350M-D3H-CF               | [23dadc00da](https://linux-hardware.org/?probe=23dadc00da) | Sep 02, 2020 |
| Gigabyte      | Z170-Gaming K3-CF           | [f70636a60c](https://linux-hardware.org/?probe=f70636a60c) | Sep 02, 2020 |
| Packard Be... | MCP73VT-PM                  | [70c5fec502](https://linux-hardware.org/?probe=70c5fec502) | Sep 02, 2020 |
| ASRock        | M3A UCC                     | [43182d8754](https://linux-hardware.org/?probe=43182d8754) | Sep 01, 2020 |
| ASRock        | M3A UCC                     | [50908c43f9](https://linux-hardware.org/?probe=50908c43f9) | Sep 01, 2020 |
| MSI           | 09AC                        | [7821db3244](https://linux-hardware.org/?probe=7821db3244) | Aug 31, 2020 |
| MSI           | 09AC                        | [d8cf9f6b2a](https://linux-hardware.org/?probe=d8cf9f6b2a) | Aug 31, 2020 |
| Supermicro    | X10SDE-DF                   | [7b5daea34a](https://linux-hardware.org/?probe=7b5daea34a) | Aug 31, 2020 |
| Gigabyte      | P35-DS3P                    | [bdbeeeb9ae](https://linux-hardware.org/?probe=bdbeeeb9ae) | Aug 31, 2020 |
| Gigabyte      | P55-UD3R                    | [1764692beb](https://linux-hardware.org/?probe=1764692beb) | Aug 30, 2020 |
| ASUSTek       | M2A-VM HDMI                 | [0655d3194c](https://linux-hardware.org/?probe=0655d3194c) | Aug 30, 2020 |
| MSI           | X399 SLI PLUS               | [7ad15ff9ac](https://linux-hardware.org/?probe=7ad15ff9ac) | Aug 30, 2020 |
| MSI           | X399 SLI PLUS               | [0141de1e81](https://linux-hardware.org/?probe=0141de1e81) | Aug 30, 2020 |
| MSI           | MS-6734                     | [6a988dac6b](https://linux-hardware.org/?probe=6a988dac6b) | Aug 30, 2020 |
| MSI           | MS-6734                     | [424e1dd60f](https://linux-hardware.org/?probe=424e1dd60f) | Aug 30, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [9cd23540a3](https://linux-hardware.org/?probe=9cd23540a3) | Aug 30, 2020 |
| ASUSTek       | P5N32-SLI-Deluxe            | [a63b6d0082](https://linux-hardware.org/?probe=a63b6d0082) | Aug 30, 2020 |
| ASRock        | FM2A55M-DGS R2.0            | [daa3dc52bc](https://linux-hardware.org/?probe=daa3dc52bc) | Aug 30, 2020 |
| eMachines     | E945GCU                     | [03b4fe8b2b](https://linux-hardware.org/?probe=03b4fe8b2b) | Aug 29, 2020 |
| HP            | 085Ch                       | [52ea9cfc53](https://linux-hardware.org/?probe=52ea9cfc53) | Aug 29, 2020 |
| NEC Comput... | K8M800-8237                 | [a21a5ca94c](https://linux-hardware.org/?probe=a21a5ca94c) | Aug 29, 2020 |
| ASUSTek       | P5N32-SLI-Deluxe            | [e44cdadbf5](https://linux-hardware.org/?probe=e44cdadbf5) | Aug 29, 2020 |
| MSI           | MS-7253                     | [92d7b3789d](https://linux-hardware.org/?probe=92d7b3789d) | Aug 29, 2020 |
| Lenovo        | 7033EW4                     | [c072a212c4](https://linux-hardware.org/?probe=c072a212c4) | Aug 28, 2020 |
| Lenovo        | 7033EW4                     | [fea8f87952](https://linux-hardware.org/?probe=fea8f87952) | Aug 28, 2020 |
| ASUSTek       | H81M-PLUS                   | [63476b75a7](https://linux-hardware.org/?probe=63476b75a7) | Aug 28, 2020 |
| Dell          | 0TP412                      | [6e9ad5bc68](https://linux-hardware.org/?probe=6e9ad5bc68) | Aug 27, 2020 |
| Dell          | 0GXM1W A00                  | [0cbd7a74b1](https://linux-hardware.org/?probe=0cbd7a74b1) | Aug 27, 2020 |
| MSI           | MPG X570 GAMING PLUS        | [e803cc1161](https://linux-hardware.org/?probe=e803cc1161) | Aug 26, 2020 |
| ASRock        | 960GC-GS FX                 | [8f55f4b8db](https://linux-hardware.org/?probe=8f55f4b8db) | Aug 26, 2020 |
| ASUSTek       | X99-E                       | [c3e2a36b7e](https://linux-hardware.org/?probe=c3e2a36b7e) | Aug 25, 2020 |
| Fujitsu       | D3164-A1 S26361-D3164-A1    | [5b809ddcc4](https://linux-hardware.org/?probe=5b809ddcc4) | Aug 25, 2020 |
| MSI           | Z97 PC Mate                 | [3a5ed56860](https://linux-hardware.org/?probe=3a5ed56860) | Aug 25, 2020 |
| Dell          | 0TP412                      | [52a77ff93b](https://linux-hardware.org/?probe=52a77ff93b) | Aug 22, 2020 |
| ASUSTek       | PRIME Z390-P                | [4889be0d7d](https://linux-hardware.org/?probe=4889be0d7d) | Aug 22, 2020 |
| Gigabyte      | B150M-D3H-CF                | [0caa9b7dee](https://linux-hardware.org/?probe=0caa9b7dee) | Aug 21, 2020 |
| Foxconn       | G31M/G31M-S FAB:1.2         | [df1e984f0f](https://linux-hardware.org/?probe=df1e984f0f) | Aug 21, 2020 |
| MSI           | B450 GAMING PLUS            | [ecb0e5f754](https://linux-hardware.org/?probe=ecb0e5f754) | Aug 20, 2020 |
| ASRock        | A320M-HDV R3.0              | [c43450f7fc](https://linux-hardware.org/?probe=c43450f7fc) | Aug 20, 2020 |
| ASRock        | B550M-HDV                   | [4b960750cd](https://linux-hardware.org/?probe=4b960750cd) | Aug 20, 2020 |
| ASRock        | X570 Taichi                 | [b486cc8b6a](https://linux-hardware.org/?probe=b486cc8b6a) | Aug 19, 2020 |
| MSI           | MPG X570 GAMING PLUS        | [d26057f87c](https://linux-hardware.org/?probe=d26057f87c) | Aug 19, 2020 |
| Gigabyte      | 970-GAMING                  | [79a539bc40](https://linux-hardware.org/?probe=79a539bc40) | Aug 18, 2020 |
| MSI           | MS-7030                     | [078a4e11bd](https://linux-hardware.org/?probe=078a4e11bd) | Aug 17, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [84ecbaf643](https://linux-hardware.org/?probe=84ecbaf643) | Aug 17, 2020 |
| Dell          | 0T10XW A01                  | [5187bc61f2](https://linux-hardware.org/?probe=5187bc61f2) | Aug 17, 2020 |
| Acer          | Aspire X3400                | [063550dc21](https://linux-hardware.org/?probe=063550dc21) | Aug 16, 2020 |
| MSI           | E350DM-E33                  | [67f718b80b](https://linux-hardware.org/?probe=67f718b80b) | Aug 16, 2020 |
| MSI           | E350DM-E33                  | [df8f51adcb](https://linux-hardware.org/?probe=df8f51adcb) | Aug 16, 2020 |
| MSI           | 2A9C                        | [57304d839a](https://linux-hardware.org/?probe=57304d839a) | Aug 15, 2020 |
| ASUSTek       | STRIX X99 GAMING            | [2340ff1559](https://linux-hardware.org/?probe=2340ff1559) | Aug 15, 2020 |
| Unknown       | Unknown                     | [028f9bfeb1](https://linux-hardware.org/?probe=028f9bfeb1) | Aug 14, 2020 |
| Pegatron      | Benicia                     | [84f49f849f](https://linux-hardware.org/?probe=84f49f849f) | Aug 14, 2020 |
| MSI           | MS-7358 Fab D               | [7f70838329](https://linux-hardware.org/?probe=7f70838329) | Aug 14, 2020 |
| Gigabyte      | Z390 UD                     | [93334a69b9](https://linux-hardware.org/?probe=93334a69b9) | Aug 13, 2020 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [155a16e518](https://linux-hardware.org/?probe=155a16e518) | Aug 13, 2020 |
| ASUSTek       | M4A785TD-V EVO              | [b7833315dc](https://linux-hardware.org/?probe=b7833315dc) | Aug 12, 2020 |
| ASRock        | B450M Pro4                  | [27573f027c](https://linux-hardware.org/?probe=27573f027c) | Aug 12, 2020 |
| Gigabyte      | P55A-UD3                    | [7e704ff8b0](https://linux-hardware.org/?probe=7e704ff8b0) | Aug 12, 2020 |
| ASUSTek       | STRIX X99 GAMING            | [b41b2a06a8](https://linux-hardware.org/?probe=b41b2a06a8) | Aug 12, 2020 |
| ASUSTek       | P5L1394                     | [b456897a28](https://linux-hardware.org/?probe=b456897a28) | Aug 11, 2020 |
| ASUSTek       | H87-PLUS                    | [86e2176cdc](https://linux-hardware.org/?probe=86e2176cdc) | Aug 11, 2020 |
| Intel         | D945GPM AAD21423-104        | [bce3fdf194](https://linux-hardware.org/?probe=bce3fdf194) | Aug 11, 2020 |
| Lenovo        | Dory CRB                    | [665867f7e0](https://linux-hardware.org/?probe=665867f7e0) | Aug 11, 2020 |
| ASRock        | A320M-HDV R4.0              | [a00f58a226](https://linux-hardware.org/?probe=a00f58a226) | Aug 11, 2020 |
| ASRock        | P5B-DE                      | [cbf7725f45](https://linux-hardware.org/?probe=cbf7725f45) | Aug 10, 2020 |
| MSI           | MPG X570 GAMING PLUS        | [750d3cf532](https://linux-hardware.org/?probe=750d3cf532) | Aug 09, 2020 |
| MSI           | MAG B550 TOMAHAWK           | [269aea18a3](https://linux-hardware.org/?probe=269aea18a3) | Aug 09, 2020 |
| Gigabyte      | 990XA-UD3                   | [d331c2376e](https://linux-hardware.org/?probe=d331c2376e) | Aug 09, 2020 |
| Gigabyte      | Z170X-UD3-CF                | [8e36441dd9](https://linux-hardware.org/?probe=8e36441dd9) | Aug 08, 2020 |
| ASUSTek       | H81M-PLUS                   | [e8afd895ba](https://linux-hardware.org/?probe=e8afd895ba) | Aug 08, 2020 |
| ASUSTek       | PRIME X570-PRO              | [e5f24075e5](https://linux-hardware.org/?probe=e5f24075e5) | Aug 07, 2020 |
| ASRock        | B250 Pro4                   | [47d59124d7](https://linux-hardware.org/?probe=47d59124d7) | Aug 06, 2020 |
| ASUSTek       | PRIME X370-PRO              | [428884bb0f](https://linux-hardware.org/?probe=428884bb0f) | Aug 05, 2020 |
| ASUSTek       | P6X58D-E                    | [5c731d7021](https://linux-hardware.org/?probe=5c731d7021) | Aug 04, 2020 |
| Gigabyte      | Z77-D3H                     | [05331a0b70](https://linux-hardware.org/?probe=05331a0b70) | Aug 04, 2020 |
| Foxconn       | 2AAF                        | [a25e0e6b85](https://linux-hardware.org/?probe=a25e0e6b85) | Aug 03, 2020 |
| ASRock        | A320M-HDV R3.0              | [b2700d8f83](https://linux-hardware.org/?probe=b2700d8f83) | Aug 03, 2020 |
| ASUSTek       | PRIME Z390-P                | [66421b347c](https://linux-hardware.org/?probe=66421b347c) | Aug 03, 2020 |
| ASUSTek       | P7P55D-E                    | [0696b02afe](https://linux-hardware.org/?probe=0696b02afe) | Aug 03, 2020 |
| Lenovo        | ThinkCentre M91p 7033A1G    | [39140e5995](https://linux-hardware.org/?probe=39140e5995) | Aug 02, 2020 |
| Gigabyte      | P55A-UD6                    | [037ea98d32](https://linux-hardware.org/?probe=037ea98d32) | Aug 02, 2020 |
| ASUSTek       | P4C800-E                    | [b5d4f4918e](https://linux-hardware.org/?probe=b5d4f4918e) | Aug 02, 2020 |
| Gigabyte      | P55A-UD6                    | [b9af67fb9c](https://linux-hardware.org/?probe=b9af67fb9c) | Aug 02, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [ff5143e508](https://linux-hardware.org/?probe=ff5143e508) | Aug 02, 2020 |
| HP            | 2B17                        | [15d7c9cae9](https://linux-hardware.org/?probe=15d7c9cae9) | Aug 02, 2020 |
| HP            | 3648h                       | [214629da03](https://linux-hardware.org/?probe=214629da03) | Aug 01, 2020 |
| MSI           | B250M PRO-VDH               | [8edb27c14d](https://linux-hardware.org/?probe=8edb27c14d) | Aug 01, 2020 |
| MSI           | B450M PRO-VDH MAX           | [03cc0d2162](https://linux-hardware.org/?probe=03cc0d2162) | Jul 31, 2020 |
| ASUSTek       | PRIME B550M-A               | [622146a38f](https://linux-hardware.org/?probe=622146a38f) | Jul 30, 2020 |
| Unknown       | Unknown                     | [a41923bfa1](https://linux-hardware.org/?probe=a41923bfa1) | Jul 30, 2020 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [094e4854f8](https://linux-hardware.org/?probe=094e4854f8) | Jul 28, 2020 |
| ASUSTek       | PRIME X370-PRO              | [28b5b22bd3](https://linux-hardware.org/?probe=28b5b22bd3) | Jul 27, 2020 |
| ASUSTek       | PRIME A320M-K               | [23ca2ea865](https://linux-hardware.org/?probe=23ca2ea865) | Jul 26, 2020 |
| ASUSTek       | PRIME A320M-K               | [5a8b71cd17](https://linux-hardware.org/?probe=5a8b71cd17) | Jul 26, 2020 |
| ASUSTek       | P5L1394                     | [1bba8815b0](https://linux-hardware.org/?probe=1bba8815b0) | Jul 26, 2020 |
| ASRock        | G41C-GS R2.0                | [7743adb004](https://linux-hardware.org/?probe=7743adb004) | Jul 24, 2020 |
| MSI           | B450I GAMING PLUS AC        | [8d0197924b](https://linux-hardware.org/?probe=8d0197924b) | Jul 23, 2020 |
| Dell          | 0C7195                      | [41b14ef5af](https://linux-hardware.org/?probe=41b14ef5af) | Jul 19, 2020 |
| ASRock        | A320M-HDV R3.0              | [44c0bfe456](https://linux-hardware.org/?probe=44c0bfe456) | Jul 19, 2020 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [3434e8ac4d](https://linux-hardware.org/?probe=3434e8ac4d) | Jul 19, 2020 |
| Gigabyte      | M68MT-D3P                   | [49fde2499f](https://linux-hardware.org/?probe=49fde2499f) | Jul 18, 2020 |
| Gigabyte      | M68MT-D3P                   | [5ea27e2813](https://linux-hardware.org/?probe=5ea27e2813) | Jul 18, 2020 |
| Gigabyte      | M85M-US2H                   | [80ed31b99d](https://linux-hardware.org/?probe=80ed31b99d) | Jul 17, 2020 |
| MSI           | 2A9C                        | [bd4169b6ec](https://linux-hardware.org/?probe=bd4169b6ec) | Jul 17, 2020 |
| MSI           | MPG X570 GAMING PLUS        | [49edf6c88a](https://linux-hardware.org/?probe=49edf6c88a) | Jul 17, 2020 |
| SiYW          | S200 Series                 | [ad04ac201a](https://linux-hardware.org/?probe=ad04ac201a) | Jul 16, 2020 |
| ASUSTek       | P6T DELUXE V2               | [51c75756c0](https://linux-hardware.org/?probe=51c75756c0) | Jul 15, 2020 |
| Gigabyte      | A320MA-M.2-CF               | [28930e29cd](https://linux-hardware.org/?probe=28930e29cd) | Jul 13, 2020 |
| ASRock        | G41M-VS3                    | [5efac1c0f4](https://linux-hardware.org/?probe=5efac1c0f4) | Jul 12, 2020 |
| ASUSTek       | Rampage III GENE            | [0f64324b26](https://linux-hardware.org/?probe=0f64324b26) | Jul 12, 2020 |
| Pegatron      | 2A73h                       | [da5a273c8e](https://linux-hardware.org/?probe=da5a273c8e) | Jul 11, 2020 |
| Pegatron      | 2A73h                       | [e170c0def5](https://linux-hardware.org/?probe=e170c0def5) | Jul 11, 2020 |
| Gigabyte      | B450M DS3H-CF               | [e6a4eb5bef](https://linux-hardware.org/?probe=e6a4eb5bef) | Jul 11, 2020 |
| HP            | ProLiant ML310e Gen8 v2     | [47fc5beaf4](https://linux-hardware.org/?probe=47fc5beaf4) | Jul 10, 2020 |
| ASUSTek       | Z97-P                       | [7b8567fe01](https://linux-hardware.org/?probe=7b8567fe01) | Jul 09, 2020 |
| Gigabyte      | GA-MA78LMT-S2               | [2917dd7cc8](https://linux-hardware.org/?probe=2917dd7cc8) | Jul 08, 2020 |
| Dell          | 0F6X5P A00                  | [39f78be0f7](https://linux-hardware.org/?probe=39f78be0f7) | Jul 08, 2020 |
| ASUSTek       | PRIME Z390-P                | [e70d8ca32d](https://linux-hardware.org/?probe=e70d8ca32d) | Jul 08, 2020 |
| ASUSTek       | P8H61-I                     | [2c0d7e8c7a](https://linux-hardware.org/?probe=2c0d7e8c7a) | Jul 07, 2020 |
| Gigabyte      | H61M-S2PV                   | [3b240b1ef9](https://linux-hardware.org/?probe=3b240b1ef9) | Jul 06, 2020 |
| AMI           | Cherry Trail CR             | [8e383dbfe6](https://linux-hardware.org/?probe=8e383dbfe6) | Jul 06, 2020 |
| ASUSTek       | P6T DELUXE V2               | [a82dabe8d8](https://linux-hardware.org/?probe=a82dabe8d8) | Jul 05, 2020 |
| Packard Be... | MCP73VT-PM                  | [662254b22c](https://linux-hardware.org/?probe=662254b22c) | Jul 05, 2020 |
| AMI           | Cherry Trail CR             | [849543b5cc](https://linux-hardware.org/?probe=849543b5cc) | Jul 04, 2020 |
| ASUSTek       | A8N-SLI Premium             | [28e261b751](https://linux-hardware.org/?probe=28e261b751) | Jul 04, 2020 |
| Gigabyte      | G31M-S2L                    | [324058062b](https://linux-hardware.org/?probe=324058062b) | Jul 03, 2020 |
| Gigabyte      | H87M-HD3                    | [7ce48e526b](https://linux-hardware.org/?probe=7ce48e526b) | Jul 02, 2020 |
| ASUSTek       | TUF X299 MARK 1             | [5a6a88b473](https://linux-hardware.org/?probe=5a6a88b473) | Jul 02, 2020 |
| Intel         | D510MO AAE76523-403         | [e8214f2da1](https://linux-hardware.org/?probe=e8214f2da1) | Jul 01, 2020 |
| ASRock        | B85M DASH/OL R2.0           | [8edc5e23ae](https://linux-hardware.org/?probe=8edc5e23ae) | Jul 01, 2020 |
| ASUSTek       | P8B75-V                     | [45d662a3eb](https://linux-hardware.org/?probe=45d662a3eb) | Jul 01, 2020 |
| ASUSTek       | PRIME B450M-A               | [086cfa3f2a](https://linux-hardware.org/?probe=086cfa3f2a) | Jul 01, 2020 |
| ASUSTek       | PRIME B450M-A               | [990010134c](https://linux-hardware.org/?probe=990010134c) | Jul 01, 2020 |
| ASUSTek       | EB1501P                     | [451ede4dd5](https://linux-hardware.org/?probe=451ede4dd5) | Jul 01, 2020 |
| ASUSTek       | P5LD2EB2-DHS                | [66d4b86237](https://linux-hardware.org/?probe=66d4b86237) | Jul 01, 2020 |
| MSI           | H97 PC Mate                 | [f913833d11](https://linux-hardware.org/?probe=f913833d11) | Jun 30, 2020 |
| ASUSTek       | PRIME Z370-P II             | [4b339632a7](https://linux-hardware.org/?probe=4b339632a7) | Jun 30, 2020 |
| MSI           | Z97 PC Mate                 | [ec882b1fc4](https://linux-hardware.org/?probe=ec882b1fc4) | Jun 30, 2020 |
| MSI           | 2A9C                        | [f4dc9fb10d](https://linux-hardware.org/?probe=f4dc9fb10d) | Jun 29, 2020 |
| MSI           | GF615M-P33 V2               | [3d5ceb6580](https://linux-hardware.org/?probe=3d5ceb6580) | Jun 29, 2020 |
| ASUSTek       | M5A99X EVO R2.0             | [c402db8d9b](https://linux-hardware.org/?probe=c402db8d9b) | Jun 28, 2020 |
| Gigabyte      | B450M DS3H-CF               | [3b0de375b5](https://linux-hardware.org/?probe=3b0de375b5) | Jun 27, 2020 |
| MSI           | MS-7030                     | [1a75b913ae](https://linux-hardware.org/?probe=1a75b913ae) | Jun 27, 2020 |
| Gigabyte      | Z97X-Gaming 3               | [fbe21e5182](https://linux-hardware.org/?probe=fbe21e5182) | Jun 27, 2020 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [3c44e0545a](https://linux-hardware.org/?probe=3c44e0545a) | Jun 25, 2020 |
| Intel         | DQ77KB AAG81483-500         | [34b7fb0e96](https://linux-hardware.org/?probe=34b7fb0e96) | Jun 25, 2020 |
| AZW           | AP35                        | [6166c5d0ee](https://linux-hardware.org/?probe=6166c5d0ee) | Jun 25, 2020 |
| Pegatron      | 2AB5                        | [d03b6e2dc1](https://linux-hardware.org/?probe=d03b6e2dc1) | Jun 24, 2020 |
| Gigabyte      | GA-990FXA-UD5               | [07c936d031](https://linux-hardware.org/?probe=07c936d031) | Jun 24, 2020 |
| Gigabyte      | GA-990FXA-UD5               | [d7756174f4](https://linux-hardware.org/?probe=d7756174f4) | Jun 24, 2020 |
| Gigabyte      | B450M DS3H-CF               | [adf9bfc9f8](https://linux-hardware.org/?probe=adf9bfc9f8) | Jun 23, 2020 |
| Gigabyte      | B450M DS3H-CF               | [ca4b93aba6](https://linux-hardware.org/?probe=ca4b93aba6) | Jun 23, 2020 |
| TYAN Compu... | Tempest-i5000PX-S5380       | [514e174756](https://linux-hardware.org/?probe=514e174756) | Jun 22, 2020 |
| ASUSTek       | P8H61-I                     | [b500cc4d28](https://linux-hardware.org/?probe=b500cc4d28) | Jun 21, 2020 |
| ASRock        | X570 Phantom Gaming 4       | [a6f13fd4fa](https://linux-hardware.org/?probe=a6f13fd4fa) | Jun 21, 2020 |
| Unknown       | Intel X79                   | [48c72e4369](https://linux-hardware.org/?probe=48c72e4369) | Jun 20, 2020 |
| Unknown       | Intel X79                   | [7eebc49848](https://linux-hardware.org/?probe=7eebc49848) | Jun 19, 2020 |
| ASRock        | G41C-GS                     | [84e596ec9e](https://linux-hardware.org/?probe=84e596ec9e) | Jun 19, 2020 |
| HP            | 18E5                        | [b7129c0dda](https://linux-hardware.org/?probe=b7129c0dda) | Jun 18, 2020 |
| ASRock        | A320M-HDV R3.0              | [e33cafa4a6](https://linux-hardware.org/?probe=e33cafa4a6) | Jun 17, 2020 |
| ASUSTek       | NCL-DS                      | [36432de3d9](https://linux-hardware.org/?probe=36432de3d9) | Jun 17, 2020 |
| ASUSTek       | P5K                         | [50a778f706](https://linux-hardware.org/?probe=50a778f706) | Jun 16, 2020 |
| Lenovo        | 3642 SDK0J40700 WIN 3258... | [61ccc2fb2b](https://linux-hardware.org/?probe=61ccc2fb2b) | Jun 15, 2020 |
| Apple         | Mac-F221BEC8                | [9f8851ddfb](https://linux-hardware.org/?probe=9f8851ddfb) | Jun 15, 2020 |
| Apple         | Mac-F221BEC8                | [790f7ecc0b](https://linux-hardware.org/?probe=790f7ecc0b) | Jun 15, 2020 |
| MSI           | B450 TOMAHAWK               | [232ff1d6fd](https://linux-hardware.org/?probe=232ff1d6fd) | Jun 15, 2020 |
| ASUSTek       | STRIX Z270I GAMING          | [663d09fe93](https://linux-hardware.org/?probe=663d09fe93) | Jun 14, 2020 |
| Packard Be... | MCP73VT-PM                  | [8cba2e7fa8](https://linux-hardware.org/?probe=8cba2e7fa8) | Jun 14, 2020 |
| Packard Be... | MCP73VT-PM                  | [26f700fbc5](https://linux-hardware.org/?probe=26f700fbc5) | Jun 14, 2020 |
| Gigabyte      | GA-870A-UD3                 | [8cc73d5fd3](https://linux-hardware.org/?probe=8cc73d5fd3) | Jun 14, 2020 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [f6d8242584](https://linux-hardware.org/?probe=f6d8242584) | Jun 14, 2020 |
| MSI           | Z370M GAMING PRO AC         | [2719525780](https://linux-hardware.org/?probe=2719525780) | Jun 14, 2020 |
| ASUSTek       | PRIME H270M-PLUS            | [26608d5024](https://linux-hardware.org/?probe=26608d5024) | Jun 13, 2020 |
| MSI           | B350M GAMING PRO            | [e4e55c9086](https://linux-hardware.org/?probe=e4e55c9086) | Jun 13, 2020 |
| ASRock        | D1800B-ITX                  | [2dd5ff6c79](https://linux-hardware.org/?probe=2dd5ff6c79) | Jun 13, 2020 |
| HP            | 1495                        | [980bf84367](https://linux-hardware.org/?probe=980bf84367) | Jun 12, 2020 |
| HP            | 1791                        | [a23ff13fe0](https://linux-hardware.org/?probe=a23ff13fe0) | Jun 11, 2020 |
| MSI           | MS-7387                     | [672076e304](https://linux-hardware.org/?probe=672076e304) | Jun 11, 2020 |
| MSI           | Z170A GAMING PRO CARBON     | [defc1e9484](https://linux-hardware.org/?probe=defc1e9484) | Jun 11, 2020 |
| ASUSTek       | A88XM-A                     | [eae021e818](https://linux-hardware.org/?probe=eae021e818) | Jun 11, 2020 |
| ASUSTek       | H61M-K                      | [53edcf7fb7](https://linux-hardware.org/?probe=53edcf7fb7) | Jun 11, 2020 |
| MSI           | Z77IA-E53                   | [0fddd36f6b](https://linux-hardware.org/?probe=0fddd36f6b) | Jun 11, 2020 |
| ASUSTek       | A88XM-A                     | [fdacafcb1a](https://linux-hardware.org/?probe=fdacafcb1a) | Jun 10, 2020 |
| Unknown       | Unknown                     | [c9e6a82c59](https://linux-hardware.org/?probe=c9e6a82c59) | Jun 10, 2020 |
| Dell          | 08NPPY A00                  | [1320e8e157](https://linux-hardware.org/?probe=1320e8e157) | Jun 10, 2020 |
| MSI           | B85-G43                     | [20ac0217ed](https://linux-hardware.org/?probe=20ac0217ed) | Jun 09, 2020 |
| ASUSTek       | ET1612I                     | [7232340ccc](https://linux-hardware.org/?probe=7232340ccc) | Jun 08, 2020 |
| ASUSTek       | PRIME A320M-K               | [8bfc4f18cc](https://linux-hardware.org/?probe=8bfc4f18cc) | Jun 08, 2020 |
| ASUSTek       | Z97-PRO                     | [f59d1dadad](https://linux-hardware.org/?probe=f59d1dadad) | Jun 07, 2020 |
| ASRock        | B365M-HDV                   | [968130895a](https://linux-hardware.org/?probe=968130895a) | Jun 07, 2020 |
| ASRock        | B450M Pro4                  | [dd2266a382](https://linux-hardware.org/?probe=dd2266a382) | Jun 07, 2020 |
| Dell          | 042P49 A01                  | [067332e367](https://linux-hardware.org/?probe=067332e367) | Jun 06, 2020 |
| ASUSTek       | Z97-A                       | [db06574e83](https://linux-hardware.org/?probe=db06574e83) | Jun 06, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [edbd2a746d](https://linux-hardware.org/?probe=edbd2a746d) | Jun 06, 2020 |
| Dell          | 0XJ8C4 A00                  | [bc19c77210](https://linux-hardware.org/?probe=bc19c77210) | Jun 06, 2020 |
| Lenovo        | ThinkCentre M55 8795B3G     | [d484254d94](https://linux-hardware.org/?probe=d484254d94) | Jun 06, 2020 |
| Lenovo        | ThinkCentre M55 8795B3G     | [d44e496516](https://linux-hardware.org/?probe=d44e496516) | Jun 06, 2020 |
| Gigabyte      | EP41-UD3L                   | [555821d51b](https://linux-hardware.org/?probe=555821d51b) | Jun 05, 2020 |
| ASRock        | H110M-DGS R3.0              | [57bfa28e3f](https://linux-hardware.org/?probe=57bfa28e3f) | Jun 05, 2020 |
| MSI           | B85-G43                     | [c65bb45e33](https://linux-hardware.org/?probe=c65bb45e33) | Jun 04, 2020 |
| ASUSTek       | P5QL PRO                    | [09dd1054df](https://linux-hardware.org/?probe=09dd1054df) | Jun 04, 2020 |
| ASRock        | FM2A78M-HD+                 | [0b6d98ead5](https://linux-hardware.org/?probe=0b6d98ead5) | Jun 02, 2020 |
| ASUSTek       | PRIME X470-PRO              | [152a30ae22](https://linux-hardware.org/?probe=152a30ae22) | Jun 01, 2020 |
| ASUSTek       | P5QL-EM                     | [161dbff3f0](https://linux-hardware.org/?probe=161dbff3f0) | Jun 01, 2020 |
| Dell          | 01TKCC A01                  | [f9292cad21](https://linux-hardware.org/?probe=f9292cad21) | May 31, 2020 |
| Dell          | 01TKCC A01                  | [51888eddbf](https://linux-hardware.org/?probe=51888eddbf) | May 31, 2020 |
| ASUSTek       | ET1612I                     | [ee417d15f0](https://linux-hardware.org/?probe=ee417d15f0) | May 31, 2020 |
| ASUSTek       | P5QL-EM                     | [6cfd100041](https://linux-hardware.org/?probe=6cfd100041) | May 30, 2020 |
| Shuttle       | FDX30                       | [340cd4222f](https://linux-hardware.org/?probe=340cd4222f) | May 30, 2020 |
| MSI           | B85-G43                     | [9937c3172a](https://linux-hardware.org/?probe=9937c3172a) | May 30, 2020 |
| ASUSTek       | P5LD2EB2-DHS                | [3de22ae680](https://linux-hardware.org/?probe=3de22ae680) | May 30, 2020 |
| MSI           | Z87-G45 GAMING              | [7058275682](https://linux-hardware.org/?probe=7058275682) | May 30, 2020 |
| MSI           | B450 TOMAHAWK               | [a1efaa98b1](https://linux-hardware.org/?probe=a1efaa98b1) | May 29, 2020 |
| MSI           | B450 TOMAHAWK               | [34dd0b6941](https://linux-hardware.org/?probe=34dd0b6941) | May 29, 2020 |
| MSI           | 970A GAMING PRO CARBON      | [7dcb902e34](https://linux-hardware.org/?probe=7dcb902e34) | May 29, 2020 |
| ASUSTek       | M5A97 R2.0                  | [d6fdecb2a8](https://linux-hardware.org/?probe=d6fdecb2a8) | May 29, 2020 |
| ASUSTek       | M5A97 R2.0                  | [fccd6d2acb](https://linux-hardware.org/?probe=fccd6d2acb) | May 29, 2020 |
| Gigabyte      | GA-970A-DS3                 | [f379a24222](https://linux-hardware.org/?probe=f379a24222) | May 28, 2020 |
| Gigabyte      | GA-970A-DS3                 | [4f8da3f7bf](https://linux-hardware.org/?probe=4f8da3f7bf) | May 28, 2020 |
| Gigabyte      | GA-970A-DS3                 | [31a1f63718](https://linux-hardware.org/?probe=31a1f63718) | May 28, 2020 |
| Gigabyte      | Z87X-D3H-CF                 | [5ec55d2057](https://linux-hardware.org/?probe=5ec55d2057) | May 27, 2020 |
| ASUSTek       | P5K                         | [397770e575](https://linux-hardware.org/?probe=397770e575) | May 27, 2020 |
| ASRock        | X470 Master SLI             | [8a433bca00](https://linux-hardware.org/?probe=8a433bca00) | May 27, 2020 |
| Gigabyte      | B450M DS3H-CF               | [85c3730751](https://linux-hardware.org/?probe=85c3730751) | May 26, 2020 |
| Gigabyte      | B450M DS3H-CF               | [51b2aa93a4](https://linux-hardware.org/?probe=51b2aa93a4) | May 26, 2020 |
| ASRock        | AM1B-ITX                    | [d0b6f8f474](https://linux-hardware.org/?probe=d0b6f8f474) | May 25, 2020 |
| MSI           | Z370 SLI PLUS               | [2dd5aa87a5](https://linux-hardware.org/?probe=2dd5aa87a5) | May 25, 2020 |
| Acer          | RS780HVF                    | [ed41875c06](https://linux-hardware.org/?probe=ed41875c06) | May 24, 2020 |
| Pegatron      | 2ACF                        | [f25037ea8b](https://linux-hardware.org/?probe=f25037ea8b) | May 24, 2020 |
| Dell          | 0PTTT9 A01                  | [94bed1b34e](https://linux-hardware.org/?probe=94bed1b34e) | May 24, 2020 |
| ECS           | Livermore                   | [d0b9ebdefb](https://linux-hardware.org/?probe=d0b9ebdefb) | May 24, 2020 |
| ECS           | Livermore                   | [237d126789](https://linux-hardware.org/?probe=237d126789) | May 24, 2020 |
| Biostar       | A68N-5545                   | [857e3fd731](https://linux-hardware.org/?probe=857e3fd731) | May 24, 2020 |
| MSI           | Z97 GAMING 3                | [88c03f1a36](https://linux-hardware.org/?probe=88c03f1a36) | May 23, 2020 |
| Gigabyte      | H81M-S2PT                   | [94e4163982](https://linux-hardware.org/?probe=94e4163982) | May 23, 2020 |
| MSI           | Z370 GAMING PRO CARBON      | [a81867a805](https://linux-hardware.org/?probe=a81867a805) | May 23, 2020 |
| MSI           | Z370 GAMING PRO CARBON      | [fdd83ff91c](https://linux-hardware.org/?probe=fdd83ff91c) | May 23, 2020 |
| ASUSTek       | PRIME A320M-K               | [40e6ddb96d](https://linux-hardware.org/?probe=40e6ddb96d) | May 23, 2020 |
| Acer          | MCP73VE NVIDIA MCP73        | [e07f3de8e6](https://linux-hardware.org/?probe=e07f3de8e6) | May 22, 2020 |
| MSI           | MS-7387                     | [b85703d1e4](https://linux-hardware.org/?probe=b85703d1e4) | May 21, 2020 |
| Acer          | MCP73VE NVIDIA MCP73        | [ff3d580484](https://linux-hardware.org/?probe=ff3d580484) | May 21, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [a40836723e](https://linux-hardware.org/?probe=a40836723e) | May 21, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [6c7cce8852](https://linux-hardware.org/?probe=6c7cce8852) | May 21, 2020 |
| HP            | 3397                        | [6927084356](https://linux-hardware.org/?probe=6927084356) | May 21, 2020 |
| Gigabyte      | H81M-S2PT                   | [4ba71a5989](https://linux-hardware.org/?probe=4ba71a5989) | May 21, 2020 |
| ASRock        | X399 Phantom Gaming 6       | [a23c2dd033](https://linux-hardware.org/?probe=a23c2dd033) | May 21, 2020 |
| Intel         | D34010WYK H14771-302        | [ad175abda8](https://linux-hardware.org/?probe=ad175abda8) | May 20, 2020 |
| Gigabyte      | G31M-ES2L                   | [33a4941e41](https://linux-hardware.org/?probe=33a4941e41) | May 20, 2020 |
| Gigabyte      | F2A88XM-D3H                 | [64db7e90fe](https://linux-hardware.org/?probe=64db7e90fe) | May 20, 2020 |
| TECO Elect... | TR3760 REV1.3               | [528a1449b7](https://linux-hardware.org/?probe=528a1449b7) | May 20, 2020 |
| MSI           | Z97 PC Mate                 | [1b8c7fe26f](https://linux-hardware.org/?probe=1b8c7fe26f) | May 20, 2020 |
| ASUSTek       | X750LN                      | [4015469fe5](https://linux-hardware.org/?probe=4015469fe5) | May 20, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [e739c254eb](https://linux-hardware.org/?probe=e739c254eb) | May 20, 2020 |
| Gigabyte      | H81M-S2PT                   | [4973d24ce9](https://linux-hardware.org/?probe=4973d24ce9) | May 20, 2020 |
| MSI           | P45-C51                     | [45ba588bf4](https://linux-hardware.org/?probe=45ba588bf4) | May 20, 2020 |
| Gigabyte      | F2A88XM-D3H                 | [2b1062016d](https://linux-hardware.org/?probe=2b1062016d) | May 20, 2020 |
| TECO Elect... | TR3760 REV1.3               | [d9534f6d65](https://linux-hardware.org/?probe=d9534f6d65) | May 19, 2020 |
| TECO Elect... | TR3760 REV1.3               | [f56e849d3b](https://linux-hardware.org/?probe=f56e849d3b) | May 19, 2020 |
| Gigabyte      | B450M S2H                   | [720b1b2422](https://linux-hardware.org/?probe=720b1b2422) | May 19, 2020 |
| MSI           | MS-7387                     | [f50637ba15](https://linux-hardware.org/?probe=f50637ba15) | May 19, 2020 |
| MSI           | MS-7387                     | [3696c34bef](https://linux-hardware.org/?probe=3696c34bef) | May 19, 2020 |
| Gigabyte      | F2A88XM-D3H                 | [70944d71b9](https://linux-hardware.org/?probe=70944d71b9) | May 18, 2020 |
| HP            | 3397                        | [017a298610](https://linux-hardware.org/?probe=017a298610) | May 18, 2020 |
| ASRock        | N68-GS4 FX                  | [93091cc8d8](https://linux-hardware.org/?probe=93091cc8d8) | May 17, 2020 |
| ASUSTek       | P8Z77-V LX                  | [29cd7c0cbb](https://linux-hardware.org/?probe=29cd7c0cbb) | May 17, 2020 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | [8a0cfc27c5](https://linux-hardware.org/?probe=8a0cfc27c5) | May 17, 2020 |
| MSI           | Z97 GAMING 3                | [660a47edfe](https://linux-hardware.org/?probe=660a47edfe) | May 17, 2020 |
| ASUSTek       | A8N-SLI Premium             | [9be3021125](https://linux-hardware.org/?probe=9be3021125) | May 17, 2020 |
| Dell          | 0T568R A00                  | [067d6bd987](https://linux-hardware.org/?probe=067d6bd987) | May 16, 2020 |
| Dell          | 0XGF09 A00                  | [07bda685fd](https://linux-hardware.org/?probe=07bda685fd) | May 16, 2020 |
| Fujitsu Si... | D2841-A1 S26361-D2841-A1    | [ee6d2fec1c](https://linux-hardware.org/?probe=ee6d2fec1c) | May 14, 2020 |
| ASUSTek       | P7P55D LE                   | [9b29259369](https://linux-hardware.org/?probe=9b29259369) | May 14, 2020 |
| Dell          | 0TP412                      | [e2d39cb880](https://linux-hardware.org/?probe=e2d39cb880) | May 14, 2020 |
| Gigabyte      | MQLP5AP-00                  | [19203b9371](https://linux-hardware.org/?probe=19203b9371) | May 13, 2020 |
| ASUSTek       | AM1I-A                      | [47cac37018](https://linux-hardware.org/?probe=47cac37018) | May 13, 2020 |
| ABIT          | AX78                        | [4b7c29fa00](https://linux-hardware.org/?probe=4b7c29fa00) | May 13, 2020 |
| Gigabyte      | MQLP5AP-00                  | [e3752ca829](https://linux-hardware.org/?probe=e3752ca829) | May 12, 2020 |
| Gigabyte      | A320M-S2H-CF                | [7d37b8ad19](https://linux-hardware.org/?probe=7d37b8ad19) | May 12, 2020 |
| Gigabyte      | B450M DS3H-CF               | [810d96f227](https://linux-hardware.org/?probe=810d96f227) | May 12, 2020 |
| Dell          | 0TP412                      | [bc488e0a7d](https://linux-hardware.org/?probe=bc488e0a7d) | May 11, 2020 |
| ASUSTek       | Z97-C                       | [c45116c4ac](https://linux-hardware.org/?probe=c45116c4ac) | May 11, 2020 |
| ASUSTek       | X750LN                      | [5ee259695b](https://linux-hardware.org/?probe=5ee259695b) | May 11, 2020 |
| Dell          | 0X8DXD A00                  | [79c618a36d](https://linux-hardware.org/?probe=79c618a36d) | May 11, 2020 |
| Dell          | 0TNXNR A01                  | [c16ecd859c](https://linux-hardware.org/?probe=c16ecd859c) | May 11, 2020 |
| HP            | 1495                        | [25f501b39c](https://linux-hardware.org/?probe=25f501b39c) | May 11, 2020 |
| AZW           | AP35                        | [5b4d6e509e](https://linux-hardware.org/?probe=5b4d6e509e) | May 10, 2020 |
| AZW           | AP35                        | [6ecbc4dec2](https://linux-hardware.org/?probe=6ecbc4dec2) | May 10, 2020 |
| Lenovo        | Dory CRB                    | [3ad96d29ba](https://linux-hardware.org/?probe=3ad96d29ba) | May 10, 2020 |
| Foxconn       | G31M/G31M-S FAB:1.2         | [6236b5e331](https://linux-hardware.org/?probe=6236b5e331) | May 10, 2020 |
| Gigabyte      | GA-MA770-UD3                | [e0d31bbb0d](https://linux-hardware.org/?probe=e0d31bbb0d) | May 10, 2020 |
| ASRock        | D1800B-ITX                  | [6fea6011bd](https://linux-hardware.org/?probe=6fea6011bd) | May 10, 2020 |
| ASUSTek       | P8B75-M LE                  | [a742b7eabd](https://linux-hardware.org/?probe=a742b7eabd) | May 10, 2020 |
| ASUSTek       | P8B75-M LE                  | [d90ea01c74](https://linux-hardware.org/?probe=d90ea01c74) | May 10, 2020 |
| ASUSTek       | GL12CP                      | [c84f56f5a7](https://linux-hardware.org/?probe=c84f56f5a7) | May 09, 2020 |
| ASUSTek       | GL12CP                      | [e198bf4945](https://linux-hardware.org/?probe=e198bf4945) | May 09, 2020 |
| ASRock        | X79 Extreme9                | [fa59824e22](https://linux-hardware.org/?probe=fa59824e22) | May 09, 2020 |
| ASUSTek       | M4A785TD-V EVO              | [3bf8690861](https://linux-hardware.org/?probe=3bf8690861) | May 09, 2020 |
| ASUSTek       | M2VTVM-VM890                | [40bed765ac](https://linux-hardware.org/?probe=40bed765ac) | May 09, 2020 |
| ASRock        | N68-GS4 FX                  | [8a18014920](https://linux-hardware.org/?probe=8a18014920) | May 09, 2020 |
| MSI           | MEG X570 UNIFY              | [73d5531734](https://linux-hardware.org/?probe=73d5531734) | May 09, 2020 |
| ASUSTek       | P9X79 WS                    | [78e4f8dc9f](https://linux-hardware.org/?probe=78e4f8dc9f) | May 09, 2020 |
| HP            | 8436                        | [81d4b0810d](https://linux-hardware.org/?probe=81d4b0810d) | May 09, 2020 |
| HP            | 845A                        | [16dd8fcfe7](https://linux-hardware.org/?probe=16dd8fcfe7) | May 08, 2020 |
| ASUSTek       | V-P8H67E                    | [d36c77e26e](https://linux-hardware.org/?probe=d36c77e26e) | May 08, 2020 |
| ASRock        | N68-GS4 FX                  | [f70ba23054](https://linux-hardware.org/?probe=f70ba23054) | May 08, 2020 |
| MSI           | FM2-A85XA-G65               | [bbf9a17590](https://linux-hardware.org/?probe=bbf9a17590) | May 08, 2020 |
| Gigabyte      | Z97X-Gaming 3               | [862a3a5a5d](https://linux-hardware.org/?probe=862a3a5a5d) | May 08, 2020 |
| Gigabyte      | G41M-Combo                  | [35366d24ca](https://linux-hardware.org/?probe=35366d24ca) | May 08, 2020 |
| Gigabyte      | G41M-Combo                  | [9291596ec6](https://linux-hardware.org/?probe=9291596ec6) | May 08, 2020 |
| ASUSTek       | PRIME B360M-A               | [a60475afb0](https://linux-hardware.org/?probe=a60475afb0) | May 07, 2020 |
| MSI           | Z97 PC Mate                 | [fc1db5d564](https://linux-hardware.org/?probe=fc1db5d564) | May 07, 2020 |
| MSI           | Z270 PC MATE                | [04090b8ee3](https://linux-hardware.org/?probe=04090b8ee3) | May 07, 2020 |
| ASUSTek       | ROG ZENITH II EXTREME       | [f5152b2ec1](https://linux-hardware.org/?probe=f5152b2ec1) | May 07, 2020 |
| MSI           | Z97 PC Mate                 | [1a82d2cfc3](https://linux-hardware.org/?probe=1a82d2cfc3) | May 07, 2020 |
| Gigabyte      | GA-990FXA-UD3               | [98ccbe892e](https://linux-hardware.org/?probe=98ccbe892e) | May 06, 2020 |
| ASUSTek       | ROG Maximus X CODE          | [300d51236d](https://linux-hardware.org/?probe=300d51236d) | May 06, 2020 |
| Gigabyte      | MZBAYAP-00                  | [bb0103ee9b](https://linux-hardware.org/?probe=bb0103ee9b) | May 06, 2020 |
| ASUSTek       | VC66                        | [a580ba2bf2](https://linux-hardware.org/?probe=a580ba2bf2) | May 06, 2020 |
| MSI           | H97 PC Mate                 | [25f66d5708](https://linux-hardware.org/?probe=25f66d5708) | May 06, 2020 |
| MSI           | Z270 PC MATE                | [b0543d9256](https://linux-hardware.org/?probe=b0543d9256) | May 06, 2020 |
| HP            | 3648h                       | [6e25e29b0b](https://linux-hardware.org/?probe=6e25e29b0b) | May 06, 2020 |
| HP            | 3648h                       | [874e199ea8](https://linux-hardware.org/?probe=874e199ea8) | May 06, 2020 |
| MSI           | Z270 PC MATE                | [861bf2eacd](https://linux-hardware.org/?probe=861bf2eacd) | May 06, 2020 |
| Acer          | Veriton L4630G V:1.0        | [e6db9125c8](https://linux-hardware.org/?probe=e6db9125c8) | May 06, 2020 |
| ASRock        | G41C-GS R2.0                | [dbb0455ab1](https://linux-hardware.org/?probe=dbb0455ab1) | May 05, 2020 |
| ASRock        | G41C-GS R2.0                | [fb4f50ed1f](https://linux-hardware.org/?probe=fb4f50ed1f) | May 05, 2020 |
| MSI           | 970A-G43 PLUS               | [e7cea6516d](https://linux-hardware.org/?probe=e7cea6516d) | May 05, 2020 |
| Foxconn       | 2AAF                        | [62a67147a3](https://linux-hardware.org/?probe=62a67147a3) | May 05, 2020 |
| Gigabyte      | EP45-DS3                    | [f900840637](https://linux-hardware.org/?probe=f900840637) | May 05, 2020 |
| HP            | 1495                        | [a38478daa1](https://linux-hardware.org/?probe=a38478daa1) | May 05, 2020 |
| HP            | 1495                        | [6fed1750c3](https://linux-hardware.org/?probe=6fed1750c3) | May 05, 2020 |
| Dell          | 0Y958C A00                  | [3ffe16de27](https://linux-hardware.org/?probe=3ffe16de27) | May 04, 2020 |
| Dell          | 0TP412                      | [9ce0e97157](https://linux-hardware.org/?probe=9ce0e97157) | May 04, 2020 |
| HP            | 1791                        | [7c51f74b31](https://linux-hardware.org/?probe=7c51f74b31) | May 04, 2020 |
| ASRock        | 970M Pro3                   | [bda5bd4d52](https://linux-hardware.org/?probe=bda5bd4d52) | May 04, 2020 |
| Gigabyte      | Z390 DESIGNARE-CF           | [1a79fa9925](https://linux-hardware.org/?probe=1a79fa9925) | May 03, 2020 |
| ABIT          | AX78                        | [db25b23bb3](https://linux-hardware.org/?probe=db25b23bb3) | May 03, 2020 |
| ASUSTek       | H81M-K                      | [290249c7eb](https://linux-hardware.org/?probe=290249c7eb) | May 02, 2020 |
| Packard Be... | Cuba MS-7301                | [15315258a0](https://linux-hardware.org/?probe=15315258a0) | May 02, 2020 |
| Intel         | B75                         | [28ce2bd86e](https://linux-hardware.org/?probe=28ce2bd86e) | May 02, 2020 |
| ASUSTek       | P7P55D-E                    | [86a2be9709](https://linux-hardware.org/?probe=86a2be9709) | May 02, 2020 |
| ASUSTek       | P7P55D-E                    | [5e1b319b91](https://linux-hardware.org/?probe=5e1b319b91) | May 02, 2020 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [dbe5cb3010](https://linux-hardware.org/?probe=dbe5cb3010) | May 02, 2020 |
| Gigabyte      | F2A88XM-D3H                 | [791064f7e8](https://linux-hardware.org/?probe=791064f7e8) | May 02, 2020 |
| Dell          | 0FJ030                      | [c26cacacee](https://linux-hardware.org/?probe=c26cacacee) | May 02, 2020 |
| ASUSTek       | P9X79                       | [9b1ed70bd8](https://linux-hardware.org/?probe=9b1ed70bd8) | May 02, 2020 |
| Packard Be... | Cuba MS-7301                | [8cf2d9d376](https://linux-hardware.org/?probe=8cf2d9d376) | May 02, 2020 |
| MSI           | MPG X570 GAMING PLUS        | [41837e50e6](https://linux-hardware.org/?probe=41837e50e6) | May 01, 2020 |
| ASUSTek       | PRIME B360M-A               | [8266071d4d](https://linux-hardware.org/?probe=8266071d4d) | May 01, 2020 |
| ASUSTek       | PRIME B360M-A               | [125f63ea26](https://linux-hardware.org/?probe=125f63ea26) | May 01, 2020 |
| ASRock        | D1800B-ITX                  | [c370b45af1](https://linux-hardware.org/?probe=c370b45af1) | May 01, 2020 |
| ASRock        | D1800B-ITX                  | [c6e7ca8fe8](https://linux-hardware.org/?probe=c6e7ca8fe8) | May 01, 2020 |
| ASRock        | B450 Pro4                   | [df6555b4f4](https://linux-hardware.org/?probe=df6555b4f4) | Apr 30, 2020 |
| ASUSTek       | Z170I PRO GAMING            | [1c7198fd73](https://linux-hardware.org/?probe=1c7198fd73) | Apr 30, 2020 |
| HP            | 2B2C                        | [62f24051d1](https://linux-hardware.org/?probe=62f24051d1) | Apr 30, 2020 |
| Foxconn       | 2ABF                        | [dc860d6491](https://linux-hardware.org/?probe=dc860d6491) | Apr 30, 2020 |
| ASUSTek       | M4A88T-M/USB3               | [207ce88ae1](https://linux-hardware.org/?probe=207ce88ae1) | Apr 30, 2020 |
| ASUSTek       | M4A88T-M/USB3               | [7706139edf](https://linux-hardware.org/?probe=7706139edf) | Apr 30, 2020 |
| Gigabyte      | Z77X-UD5H                   | [910d637db9](https://linux-hardware.org/?probe=910d637db9) | Apr 30, 2020 |
| Dell          | 0MM599                      | [cebb5ef400](https://linux-hardware.org/?probe=cebb5ef400) | Apr 29, 2020 |
| Dell          | 0MM599                      | [b2386ebff9](https://linux-hardware.org/?probe=b2386ebff9) | Apr 29, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | [d547582725](https://linux-hardware.org/?probe=d547582725) | Apr 29, 2020 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [e523f8067b](https://linux-hardware.org/?probe=e523f8067b) | Apr 29, 2020 |
| HP            | 8436                        | [fa20b51d89](https://linux-hardware.org/?probe=fa20b51d89) | Apr 29, 2020 |
| ASUSTek       | P8Z77-V                     | [67ed484a45](https://linux-hardware.org/?probe=67ed484a45) | Apr 28, 2020 |
| Intel         | B75                         | [c62fbe4919](https://linux-hardware.org/?probe=c62fbe4919) | Apr 28, 2020 |
| Gigabyte      | GA-880GM-UD2H               | [b98a1c50e8](https://linux-hardware.org/?probe=b98a1c50e8) | Apr 28, 2020 |
| ASUSTek       | A8N-SLI Premium             | [7431fbecad](https://linux-hardware.org/?probe=7431fbecad) | Apr 28, 2020 |
| Packard Be... | IMEDIA S3720                | [672aaf94c0](https://linux-hardware.org/?probe=672aaf94c0) | Apr 27, 2020 |
| ASUSTek       | PRIME X370-PRO              | [385d6ddbc2](https://linux-hardware.org/?probe=385d6ddbc2) | Apr 27, 2020 |
| Dell          | 0T568R A00                  | [b54248e085](https://linux-hardware.org/?probe=b54248e085) | Apr 27, 2020 |
| ASUSTek       | PRIME X370-PRO              | [f588b3f26d](https://linux-hardware.org/?probe=f588b3f26d) | Apr 27, 2020 |
| Gigabyte      | B450M DS3H-CF               | [498b198b32](https://linux-hardware.org/?probe=498b198b32) | Apr 27, 2020 |
| HP            | 8436                        | [3bde97eb14](https://linux-hardware.org/?probe=3bde97eb14) | Apr 27, 2020 |
| Gigabyte      | GA-880GM-UD2H               | [1c46568976](https://linux-hardware.org/?probe=1c46568976) | Apr 26, 2020 |
| MSI           | X570-A PRO                  | [f67846d40f](https://linux-hardware.org/?probe=f67846d40f) | Apr 26, 2020 |
| American M... | K7S41GX                     | [beb69bfa6b](https://linux-hardware.org/?probe=beb69bfa6b) | Apr 26, 2020 |
| Supermicro    | X10SDE-DF                   | [54cbea6bb1](https://linux-hardware.org/?probe=54cbea6bb1) | Apr 26, 2020 |
| Supermicro    | X10SDE-DF                   | [3c55fe3c77](https://linux-hardware.org/?probe=3c55fe3c77) | Apr 26, 2020 |
| ASUSTek       | P5KPL-AM                    | [76eb877783](https://linux-hardware.org/?probe=76eb877783) | Apr 26, 2020 |
| ASUSTek       | ROG Maximus X HERO          | [e012a7adff](https://linux-hardware.org/?probe=e012a7adff) | Apr 25, 2020 |
| ASUSTek       | Q87M-E                      | [4b53217002](https://linux-hardware.org/?probe=4b53217002) | Apr 25, 2020 |
| ASUSTek       | P6T SE                      | [cb688ef5cb](https://linux-hardware.org/?probe=cb688ef5cb) | Apr 25, 2020 |
| ASRock        | A320M-HDV R3.0              | [a03b2f3c45](https://linux-hardware.org/?probe=a03b2f3c45) | Apr 25, 2020 |
| ASUSTek       | P7P55D                      | [83065dac12](https://linux-hardware.org/?probe=83065dac12) | Apr 25, 2020 |
| Lenovo        | XXXX 2222222                | [215a273803](https://linux-hardware.org/?probe=215a273803) | Apr 25, 2020 |
| MSI           | GF615M-P33                  | [52332385fb](https://linux-hardware.org/?probe=52332385fb) | Apr 24, 2020 |
| MSI           | GF615M-P33                  | [2e21b2870e](https://linux-hardware.org/?probe=2e21b2870e) | Apr 24, 2020 |
| ASUSTek       | Maximus VIII HERO           | [6f7a2ef749](https://linux-hardware.org/?probe=6f7a2ef749) | Apr 24, 2020 |
| MSI           | H97 PC Mate                 | [2565308a86](https://linux-hardware.org/?probe=2565308a86) | Apr 24, 2020 |
| MSI           | X470 GAMING PRO MAX         | [364918c615](https://linux-hardware.org/?probe=364918c615) | Apr 24, 2020 |
| Lenovo        | XXXX 2222222                | [96c9f0757c](https://linux-hardware.org/?probe=96c9f0757c) | Apr 23, 2020 |
| ASUSTek       | VM65N-K                     | [657363222d](https://linux-hardware.org/?probe=657363222d) | Apr 23, 2020 |
| ASUSTek       | VM65N-K                     | [0002f7d48f](https://linux-hardware.org/?probe=0002f7d48f) | Apr 23, 2020 |
| ASUSTek       | P5N-D                       | [1fe14e4cdb](https://linux-hardware.org/?probe=1fe14e4cdb) | Apr 23, 2020 |
| MSI           | H81I                        | [1a376610c9](https://linux-hardware.org/?probe=1a376610c9) | Apr 23, 2020 |
| ASUSTek       | CG8270                      | [8bdb44e9da](https://linux-hardware.org/?probe=8bdb44e9da) | Apr 22, 2020 |
| Foxconn       | 2A8C                        | [64941f8ea2](https://linux-hardware.org/?probe=64941f8ea2) | Apr 21, 2020 |
| Gigabyte      | B450M DS3H-CF               | [e2f04ac86c](https://linux-hardware.org/?probe=e2f04ac86c) | Apr 21, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [40acf1c225](https://linux-hardware.org/?probe=40acf1c225) | Apr 21, 2020 |
| Dell          | 0DN075                      | [895ee492cf](https://linux-hardware.org/?probe=895ee492cf) | Apr 21, 2020 |
| Lenovo        | XXXX 2222222                | [8d23c0f9e7](https://linux-hardware.org/?probe=8d23c0f9e7) | Apr 20, 2020 |
| Lenovo        | 3704 SDK0R32862 WIN 3258... | [b95577df66](https://linux-hardware.org/?probe=b95577df66) | Apr 19, 2020 |
| Gigabyte      | EP45-DS3                    | [f9c0199510](https://linux-hardware.org/?probe=f9c0199510) | Apr 19, 2020 |
| Lenovo        | 3704 SDK0R32862 WIN 3258... | [f7dc311ac9](https://linux-hardware.org/?probe=f7dc311ac9) | Apr 19, 2020 |
| Gigabyte      | G31M-ES2L                   | [1527e5bbe4](https://linux-hardware.org/?probe=1527e5bbe4) | Apr 19, 2020 |
| ASRock        | A320M Pro4                  | [bbe29521e7](https://linux-hardware.org/?probe=bbe29521e7) | Apr 19, 2020 |
| MSI           | B75A-G43                    | [1a207ee248](https://linux-hardware.org/?probe=1a207ee248) | Apr 18, 2020 |
| HP            | 1998                        | [f9ac7999a1](https://linux-hardware.org/?probe=f9ac7999a1) | Apr 17, 2020 |
| HP            | 1998                        | [3b299d3624](https://linux-hardware.org/?probe=3b299d3624) | Apr 17, 2020 |
| HP            | 212B                        | [71cfef0293](https://linux-hardware.org/?probe=71cfef0293) | Apr 17, 2020 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [6c4a805b47](https://linux-hardware.org/?probe=6c4a805b47) | Apr 15, 2020 |
| HP            | 3029h                       | [456e067f81](https://linux-hardware.org/?probe=456e067f81) | Apr 15, 2020 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [6b0f7ae519](https://linux-hardware.org/?probe=6b0f7ae519) | Apr 15, 2020 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [9ac5aaa22b](https://linux-hardware.org/?probe=9ac5aaa22b) | Apr 14, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | [037ec6a37b](https://linux-hardware.org/?probe=037ec6a37b) | Apr 14, 2020 |
| Acer          | MCP73VE NVIDIA MCP73        | [c263eac3e9](https://linux-hardware.org/?probe=c263eac3e9) | Apr 13, 2020 |
| Acer          | MCP73VE NVIDIA MCP73        | [75fff2a0a6](https://linux-hardware.org/?probe=75fff2a0a6) | Apr 13, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [2128ec98b5](https://linux-hardware.org/?probe=2128ec98b5) | Apr 13, 2020 |
| MSI           | MPG X570 GAMING PLUS        | [f9068b89bb](https://linux-hardware.org/?probe=f9068b89bb) | Apr 13, 2020 |
| Gigabyte      | G31M-ES2L                   | [5c021ee1a9](https://linux-hardware.org/?probe=5c021ee1a9) | Apr 12, 2020 |
| Gigabyte      | G31M-ES2L                   | [219ea2fa2d](https://linux-hardware.org/?probe=219ea2fa2d) | Apr 12, 2020 |
| MSI           | MPG Z390 GAMING PLUS        | [df2259b602](https://linux-hardware.org/?probe=df2259b602) | Apr 11, 2020 |
| Gigabyte      | GA-880GM-UD2H               | [a7d4e8b1e4](https://linux-hardware.org/?probe=a7d4e8b1e4) | Apr 10, 2020 |
| Supermicro    | X10SDE-DF                   | [ae18373146](https://linux-hardware.org/?probe=ae18373146) | Apr 10, 2020 |
| Dell          | 03NVJ6 A01                  | [c33a241c84](https://linux-hardware.org/?probe=c33a241c84) | Apr 10, 2020 |
| Dell          | 03NVJ6 A01                  | [23b3f8f5c0](https://linux-hardware.org/?probe=23b3f8f5c0) | Apr 09, 2020 |
| Dell          | 03NVJ6 A01                  | [b9d0a1b8fb](https://linux-hardware.org/?probe=b9d0a1b8fb) | Apr 09, 2020 |
| Kontron       | 986LCD-M/mITX 67130900      | [da9c733fbc](https://linux-hardware.org/?probe=da9c733fbc) | Apr 08, 2020 |
| Dell          | 0TP412                      | [59494c6c64](https://linux-hardware.org/?probe=59494c6c64) | Apr 07, 2020 |
| MSI           | Z77A-GD65                   | [216bf075a1](https://linux-hardware.org/?probe=216bf075a1) | Apr 07, 2020 |
| Dell          | 0GM819                      | [07dcdb2c01](https://linux-hardware.org/?probe=07dcdb2c01) | Apr 07, 2020 |
| Dell          | 0WMJ54 A01                  | [915652c132](https://linux-hardware.org/?probe=915652c132) | Apr 07, 2020 |
| Dell          | 0GM819                      | [d102e71fbb](https://linux-hardware.org/?probe=d102e71fbb) | Apr 07, 2020 |
| ASUSTek       | P8Z77-V LX2                 | [8d2322b3b3](https://linux-hardware.org/?probe=8d2322b3b3) | Apr 06, 2020 |
| ASUSTek       | TUF Z390-PRO GAMING         | [de0d4452e5](https://linux-hardware.org/?probe=de0d4452e5) | Apr 06, 2020 |
| ASUSTek       | P5G41T-M LX                 | [535709081b](https://linux-hardware.org/?probe=535709081b) | Apr 05, 2020 |
| ASUSTek       | P5G41T-M LX                 | [6ecc71ff86](https://linux-hardware.org/?probe=6ecc71ff86) | Apr 05, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [72802278e7](https://linux-hardware.org/?probe=72802278e7) | Apr 04, 2020 |
| HP            | 3048h                       | [8488bc3d2d](https://linux-hardware.org/?probe=8488bc3d2d) | Apr 04, 2020 |
| ASUSTek       | SABERTOOTH X58              | [8858339401](https://linux-hardware.org/?probe=8858339401) | Apr 03, 2020 |
| ASUSTek       | SABERTOOTH X58              | [be33197016](https://linux-hardware.org/?probe=be33197016) | Apr 03, 2020 |
| MSI           | H97 PC Mate                 | [58e215593a](https://linux-hardware.org/?probe=58e215593a) | Apr 03, 2020 |
| ASRock        | G31M-GS                     | [0f6ebd3e93](https://linux-hardware.org/?probe=0f6ebd3e93) | Apr 02, 2020 |
| MSI           | H310M PRO-D                 | [d11c4af980](https://linux-hardware.org/?probe=d11c4af980) | Apr 02, 2020 |
| MSI           | H55-GD65                    | [faeb386cfa](https://linux-hardware.org/?probe=faeb386cfa) | Apr 01, 2020 |
| ASUSTek       | P8Z77-V LX2                 | [a99e2d239d](https://linux-hardware.org/?probe=a99e2d239d) | Apr 01, 2020 |
| Gigabyte      | B450M DS3H-CF               | [dfa092565b](https://linux-hardware.org/?probe=dfa092565b) | Apr 01, 2020 |
| Dell          | 0M5DCD A00                  | [8479e75278](https://linux-hardware.org/?probe=8479e75278) | Apr 01, 2020 |
| ASUSTek       | P6X58D-E                    | [3defa9e6eb](https://linux-hardware.org/?probe=3defa9e6eb) | Mar 31, 2020 |
| ABIT          | AV8                         | [b996d0c641](https://linux-hardware.org/?probe=b996d0c641) | Mar 31, 2020 |
| Dell          | 0M5DCD A00                  | [fc0e42a494](https://linux-hardware.org/?probe=fc0e42a494) | Mar 31, 2020 |
| Intel         | DG31PR AAD97573-305         | [16b46d0972](https://linux-hardware.org/?probe=16b46d0972) | Mar 31, 2020 |
| Intel         | DG31PR AAD97573-305         | [756572e439](https://linux-hardware.org/?probe=756572e439) | Mar 31, 2020 |
| Dell          | 0TP412                      | [bf588fc977](https://linux-hardware.org/?probe=bf588fc977) | Mar 30, 2020 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [d27ea3ee61](https://linux-hardware.org/?probe=d27ea3ee61) | Mar 30, 2020 |
| Dell          | 0TP412                      | [c2f16e0243](https://linux-hardware.org/?probe=c2f16e0243) | Mar 30, 2020 |
| ASUSTek       | M2N-E                       | [374938e33e](https://linux-hardware.org/?probe=374938e33e) | Mar 29, 2020 |
| ASUSTek       | TUF B450-PLUS GAMING        | [05d2bfb696](https://linux-hardware.org/?probe=05d2bfb696) | Mar 29, 2020 |
| ASUSTek       | PRIME A320M-K               | [cabb3f4266](https://linux-hardware.org/?probe=cabb3f4266) | Mar 29, 2020 |
| ASUSTek       | M2N-E                       | [7a234988b2](https://linux-hardware.org/?probe=7a234988b2) | Mar 28, 2020 |
| MSI           | 2A78h                       | [b0057491d5](https://linux-hardware.org/?probe=b0057491d5) | Mar 28, 2020 |
| MSI           | 2A78h                       | [aa82acd394](https://linux-hardware.org/?probe=aa82acd394) | Mar 28, 2020 |
| ASUSTek       | M2N8-VMX                    | [7c5ab211d6](https://linux-hardware.org/?probe=7c5ab211d6) | Mar 28, 2020 |
| Foxconn       | 2ABF                        | [7731b4d728](https://linux-hardware.org/?probe=7731b4d728) | Mar 27, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [5b8ef620f7](https://linux-hardware.org/?probe=5b8ef620f7) | Mar 27, 2020 |
| MSI           | MPG X570 GAMING PLUS        | [fc9638e824](https://linux-hardware.org/?probe=fc9638e824) | Mar 27, 2020 |
| MSI           | B450M PRO-M2                | [00eb5b862a](https://linux-hardware.org/?probe=00eb5b862a) | Mar 27, 2020 |
| Dell          | 0TP412                      | [a610823fcb](https://linux-hardware.org/?probe=a610823fcb) | Mar 26, 2020 |
| Lenovo        | ThinkCentre M91p 4518AQ2    | [c940519403](https://linux-hardware.org/?probe=c940519403) | Mar 26, 2020 |
| MSI           | B350 PC MATE                | [3137fce60f](https://linux-hardware.org/?probe=3137fce60f) | Mar 24, 2020 |
| MSI           | E350IS-E45                  | [58d28507ad](https://linux-hardware.org/?probe=58d28507ad) | Mar 24, 2020 |
| Dell          | 0TP412                      | [391205b10b](https://linux-hardware.org/?probe=391205b10b) | Mar 23, 2020 |
| Acer          | FMCP7A-ION-LE               | [e90644613d](https://linux-hardware.org/?probe=e90644613d) | Mar 23, 2020 |
| ASUSTek       | M5A99X EVO R2.0             | [1cdf4b6935](https://linux-hardware.org/?probe=1cdf4b6935) | Mar 22, 2020 |
| ASUSTek       | Z170-A                      | [0ba9800425](https://linux-hardware.org/?probe=0ba9800425) | Mar 22, 2020 |
| ASUSTek       | Z170-A                      | [71fb10171c](https://linux-hardware.org/?probe=71fb10171c) | Mar 22, 2020 |
| Gigabyte      | B450M DS3H-CF               | [e24fe4e6fe](https://linux-hardware.org/?probe=e24fe4e6fe) | Mar 22, 2020 |
| ECS           | Nettle3                     | [03dcc45a52](https://linux-hardware.org/?probe=03dcc45a52) | Mar 21, 2020 |
| Unknown       | GeForce 8000 series         | [5cd956fefd](https://linux-hardware.org/?probe=5cd956fefd) | Mar 21, 2020 |
| ECS           | Nettle3                     | [409146b5df](https://linux-hardware.org/?probe=409146b5df) | Mar 20, 2020 |
| Packard Be... | IMEDIA S3840                | [8bb4a3c5f7](https://linux-hardware.org/?probe=8bb4a3c5f7) | Mar 19, 2020 |
| ASRock        | G41M-VS3                    | [bf039635e9](https://linux-hardware.org/?probe=bf039635e9) | Mar 19, 2020 |
| ASUSTek       | NCL-DS                      | [7483894658](https://linux-hardware.org/?probe=7483894658) | Mar 18, 2020 |
| MSI           | X370 GAMING PLUS            | [745dce9c6b](https://linux-hardware.org/?probe=745dce9c6b) | Mar 16, 2020 |
| ASUSTek       | P6T DELUXE V2               | [ffaec98a07](https://linux-hardware.org/?probe=ffaec98a07) | Mar 15, 2020 |
| ASUSTek       | F2A85-M PRO                 | [e3053ba223](https://linux-hardware.org/?probe=e3053ba223) | Mar 15, 2020 |
| Gigabyte      | B450M DS3H-CF               | [bf6ec30aab](https://linux-hardware.org/?probe=bf6ec30aab) | Mar 13, 2020 |
| Gigabyte      | B450M DS3H-CF               | [0811bdefcb](https://linux-hardware.org/?probe=0811bdefcb) | Mar 12, 2020 |
| Gigabyte      | AB350-Gaming-CF             | [c550370efa](https://linux-hardware.org/?probe=c550370efa) | Mar 11, 2020 |
| ASRock        | B85M Pro3                   | [765094a989](https://linux-hardware.org/?probe=765094a989) | Mar 10, 2020 |
| MSI           | B450M PRO-M2                | [147867af3f](https://linux-hardware.org/?probe=147867af3f) | Mar 10, 2020 |
| ASUSTek       | P5G41T-M LX                 | [085af73afc](https://linux-hardware.org/?probe=085af73afc) | Mar 10, 2020 |
| MSI           | X370 GAMING PLUS            | [78c1606697](https://linux-hardware.org/?probe=78c1606697) | Mar 09, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/France/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 603      | 23.23%  |
| Ubuntu 18.04                 | 218      | 8.4%    |
| OpenMandriva 4.2             | 169      | 6.51%   |
| Xubuntu 20.04                | 64       | 2.47%   |
| Linux Mint 20.1              | 57       | 2.2%    |
| Debian 11                    | 55       | 2.12%   |
| Debian 10                    | 55       | 2.12%   |
| OpenMandriva 4.3             | 54       | 2.08%   |
| Arch Rolling                 | 44       | 1.69%   |
| Ubuntu 20.10                 | 43       | 1.66%   |
| Ubuntu 21.04                 | 40       | 1.54%   |
| Ubuntu 21.10                 | 39       | 1.5%    |
| Linux Mint 20.2              | 39       | 1.5%    |
| Linux Mint 20.3              | 36       | 1.39%   |
| Linux Mint 19.3              | 35       | 1.35%   |
| Fedora 33                    | 35       | 1.35%   |
| Kubuntu 20.04                | 33       | 1.27%   |
| Arch                         | 31       | 1.19%   |
| Linux Mint 20                | 30       | 1.16%   |
| Ubuntu 19.04                 | 29       | 1.12%   |
| Ubuntu 19.10                 | 27       | 1.04%   |
| KDE neon 20.04               | 27       | 1.04%   |
| Fedora 35                    | 26       | 1%      |
| Ubuntu 16.04                 | 24       | 0.92%   |
| Fedora 32                    | 24       | 0.92%   |
| Fedora 34                    | 23       | 0.89%   |
| Xubuntu 18.04                | 22       | 0.85%   |
| Ubuntu 22.04                 | 22       | 0.85%   |
| ROSA R11                     | 22       | 0.85%   |
| ROSA R10                     | 22       | 0.85%   |
| Manjaro                      | 22       | 0.85%   |
| ROSA R9                      | 21       | 0.81%   |
| Pop!_OS 21.04                | 20       | 0.77%   |
| ROSA R11.1                   | 19       | 0.73%   |
| Ubuntu 18.10                 | 18       | 0.69%   |
| Lubuntu 20.04                | 18       | 0.69%   |
| Zorin 15                     | 15       | 0.58%   |
| Ubuntu MATE 20.04            | 15       | 0.58%   |
| ROSA R8.1                    | 14       | 0.54%   |
| Pop!_OS 20.04                | 13       | 0.5%    |
| OpenMandriva 4.50            | 13       | 0.5%    |
| Fedora 31                    | 13       | 0.5%    |
| Zorin 16                     | 12       | 0.46%   |
| Pop!_OS 20.10                | 11       | 0.42%   |
| Mageia 8                     | 11       | 0.42%   |
| LMDE 4                       | 11       | 0.42%   |
| Linux Mint 19.2              | 11       | 0.42%   |
| BlackPanther 18.1            | 11       | 0.42%   |
| ArcoLinux Rolling            | 11       | 0.42%   |
| Gentoo 2.7                   | 10       | 0.39%   |
| Ubuntu Studio 20.04          | 9        | 0.35%   |
| openSUSE Tumbleweed-XXXXXXXX | 9        | 0.35%   |
| Debian Testing               | 9        | 0.35%   |
| Pop!_OS 21.10                | 8        | 0.31%   |
| Kubuntu 20.10                | 8        | 0.31%   |
| Elementary 6.1               | 8        | 0.31%   |
| Debian Unstable              | 7        | 0.27%   |
| Xubuntu 19.10                | 6        | 0.23%   |
| ROSA R8                      | 6        | 0.23%   |
| Linux Mint 19.1              | 6        | 0.23%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| Ubuntu         | 1025     | 41.75%  |
| OpenMandriva   | 240      | 9.78%   |
| Linux Mint     | 199      | 8.11%   |
| Debian         | 126      | 5.13%   |
| Xubuntu        | 106      | 4.32%   |
| Fedora         | 101      | 4.11%   |
| ROSA           | 91       | 3.71%   |
| Arch           | 74       | 3.01%   |
| Manjaro        | 66       | 2.69%   |
| Kubuntu        | 55       | 2.24%   |
| Pop!_OS        | 51       | 2.08%   |
| Ubuntu MATE    | 32       | 1.3%    |
| Zorin          | 29       | 1.18%   |
| KDE neon       | 29       | 1.18%   |
| Lubuntu        | 25       | 1.02%   |
| openSUSE       | 18       | 0.73%   |
| Gentoo         | 18       | 0.73%   |
| Ubuntu Budgie  | 13       | 0.53%   |
| Mageia         | 13       | 0.53%   |
| LMDE           | 13       | 0.53%   |
| BlackPanther   | 13       | 0.53%   |
| Elementary     | 12       | 0.49%   |
| ArcoLinux      | 11       | 0.45%   |
| Clear Linux    | 10       | 0.41%   |
| CentOS         | 10       | 0.41%   |
| Ubuntu Studio  | 9        | 0.37%   |
| EndeavourOS    | 8        | 0.33%   |
| Endless        | 7        | 0.29%   |
| Artix          | 7        | 0.29%   |
| Devuan         | 6        | 0.24%   |
| MX             | 4        | 0.16%   |
| Kali           | 4        | 0.16%   |
| Trisquel       | 3        | 0.12%   |
| Solus          | 3        | 0.12%   |
| LinuxFX        | 3        | 0.12%   |
| UbuntuDDE      | 2        | 0.08%   |
| Slackware      | 2        | 0.08%   |
| Parrot         | 2        | 0.08%   |
| Garuda Linux   | 2        | 0.08%   |
| antergos       | 2        | 0.08%   |
| Void Linux     | 1        | 0.04%   |
| Sparky         | 1        | 0.04%   |
| Scientific     | 1        | 0.04%   |
| Rocky Linux    | 1        | 0.04%   |
| Q4OS           | 1        | 0.04%   |
| Pardus         | 1        | 0.04%   |
| Linux Lite     | 1        | 0.04%   |
| Kaisen         | 1        | 0.04%   |
| Generic        | 1        | 0.04%   |
| Bluestar Linux | 1        | 0.04%   |
| antiX          | 1        | 0.04%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002        | 162      | 5.63%   |
| 5.4.0-58-generic                | 50       | 1.74%   |
| 5.16.7-desktop-1omv4003         | 50       | 1.74%   |
| 5.4.0-42-generic                | 44       | 1.53%   |
| 5.4.0-65-generic                | 31       | 1.08%   |
| 5.4.0-48-generic                | 31       | 1.08%   |
| 5.4.0-52-generic                | 30       | 1.04%   |
| 5.4.0-29-generic                | 30       | 1.04%   |
| 5.11.0-37-generic               | 30       | 1.04%   |
| 5.11.0-27-generic               | 27       | 0.94%   |
| 5.8.0-50-generic                | 26       | 0.9%    |
| 5.8.0-43-generic                | 26       | 0.9%    |
| 5.13.0-39-generic               | 26       | 0.9%    |
| 5.13.0-28-generic               | 26       | 0.9%    |
| 5.4.0-54-generic                | 25       | 0.87%   |
| 5.4.0-26-generic                | 25       | 0.87%   |
| 5.11.0-38-generic               | 23       | 0.8%    |
| 5.4.0-81-generic                | 21       | 0.73%   |
| 5.8.0-48-generic                | 20       | 0.69%   |
| 5.4.0-74-generic                | 20       | 0.69%   |
| 5.11.0-40-generic               | 20       | 0.69%   |
| 5.8.0-44-generic                | 19       | 0.66%   |
| 5.4.0-73-generic                | 19       | 0.66%   |
| 5.4.0-70-generic                | 19       | 0.66%   |
| 5.4.0-37-generic                | 19       | 0.66%   |
| 5.11.0-41-generic               | 19       | 0.66%   |
| 5.4.0-91-generic                | 18       | 0.63%   |
| 5.4.0-72-generic                | 18       | 0.63%   |
| 5.4.0-66-generic                | 18       | 0.63%   |
| 5.8.0-59-generic                | 17       | 0.59%   |
| 5.4.0-53-generic                | 17       | 0.59%   |
| 5.13.0-27-generic               | 17       | 0.59%   |
| 5.11.0-43-generic               | 17       | 0.59%   |
| 5.4.0-31-generic                | 16       | 0.56%   |
| 5.3.0-42-generic                | 16       | 0.56%   |
| 5.8.0-53-generic                | 15       | 0.52%   |
| 5.4.0-80-generic                | 15       | 0.52%   |
| 5.13.0-40-generic               | 15       | 0.52%   |
| 5.8.0-63-generic                | 14       | 0.49%   |
| 5.11.0-34-generic               | 14       | 0.49%   |
| 5.10.0-8-amd64                  | 14       | 0.49%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 14       | 0.49%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 14       | 0.49%   |
| 5.8.0-41-generic                | 13       | 0.45%   |
| 5.4.0-77-generic                | 13       | 0.45%   |
| 5.4.0-99-generic                | 12       | 0.42%   |
| 5.4.0-90-generic                | 12       | 0.42%   |
| 5.4.0-109-generic               | 12       | 0.42%   |
| 5.12.4-desktop-1omv4050         | 12       | 0.42%   |
| 5.11.0-25-generic               | 12       | 0.42%   |
| 4.18.0-25-generic               | 12       | 0.42%   |
| 5.4.0-89-generic                | 11       | 0.38%   |
| 5.4.0-47-generic                | 11       | 0.38%   |
| 5.4.0-33-generic                | 11       | 0.38%   |
| 5.4.0-100-generic               | 11       | 0.38%   |
| 5.3.0-46-generic                | 11       | 0.38%   |
| 5.3.0-40-generic                | 11       | 0.38%   |
| 5.13.0-22-generic               | 11       | 0.38%   |
| 5.11.0-22-generic               | 11       | 0.38%   |
| 5.4.0-88-generic                | 10       | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 652      | 24.26%  |
| 5.11.0  | 232      | 8.63%   |
| 5.8.0   | 214      | 7.96%   |
| 4.15.0  | 195      | 7.26%   |
| 5.10.14 | 164      | 6.1%    |
| 5.13.0  | 152      | 5.66%   |
| 5.3.0   | 104      | 3.87%   |
| 5.10.0  | 62       | 2.31%   |
| 5.0.0   | 60       | 2.23%   |
| 4.18.0  | 58       | 2.16%   |
| 4.19.0  | 57       | 2.12%   |
| 5.16.7  | 52       | 1.94%   |
| 5.15.0  | 32       | 1.19%   |
| 4.9.20  | 19       | 0.71%   |
| 4.9.60  | 16       | 0.6%    |
| 5.12.4  | 13       | 0.48%   |
| 5.4.32  | 11       | 0.41%   |
| 5.11.12 | 11       | 0.41%   |
| 4.4.0   | 11       | 0.41%   |
| 4.18.16 | 11       | 0.41%   |
| 5.9.16  | 8        | 0.3%    |
| 5.9.0   | 8        | 0.3%    |
| 5.8.16  | 7        | 0.26%   |
| 5.6.19  | 7        | 0.26%   |
| 5.14.14 | 7        | 0.26%   |
| 5.13.19 | 7        | 0.26%   |
| 5.13.13 | 7        | 0.26%   |
| 5.13.12 | 7        | 0.26%   |
| 5.7.0   | 6        | 0.22%   |
| 5.17.5  | 6        | 0.22%   |
| 4.9.9   | 6        | 0.22%   |
| 4.9.0   | 6        | 0.22%   |
| 4.1.38  | 6        | 0.22%   |
| 5.9.8   | 5        | 0.19%   |
| 5.9.1   | 5        | 0.19%   |
| 5.8.15  | 5        | 0.19%   |
| 5.8.11  | 5        | 0.19%   |
| 5.7.15  | 5        | 0.19%   |
| 5.3.18  | 5        | 0.19%   |
| 5.16.16 | 5        | 0.19%   |
| 5.16.11 | 5        | 0.19%   |
| 5.15.28 | 5        | 0.19%   |
| 5.15.11 | 5        | 0.19%   |
| 5.14.0  | 5        | 0.19%   |
| 4.9.155 | 5        | 0.19%   |
| 4.1.34  | 5        | 0.19%   |
| 3.10.0  | 5        | 0.19%   |
| 5.9.11  | 4        | 0.15%   |
| 5.8.5   | 4        | 0.15%   |
| 5.8.18  | 4        | 0.15%   |
| 5.6.0   | 4        | 0.15%   |
| 5.5.7   | 4        | 0.15%   |
| 5.4.83  | 4        | 0.15%   |
| 5.17.4  | 4        | 0.15%   |
| 5.17.1  | 4        | 0.15%   |
| 5.16.18 | 4        | 0.15%   |
| 5.16.0  | 4        | 0.15%   |
| 5.15.2  | 4        | 0.15%   |
| 5.15.15 | 4        | 0.15%   |
| 5.15.12 | 4        | 0.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 693      | 26.09%  |
| 5.11    | 269      | 10.13%  |
| 5.10    | 269      | 10.13%  |
| 5.8     | 256      | 9.64%   |
| 4.15    | 196      | 7.38%   |
| 5.13    | 186      | 7%      |
| 5.3     | 118      | 4.44%   |
| 5.16    | 91       | 3.43%   |
| 5.15    | 70       | 2.64%   |
| 4.18    | 70       | 2.64%   |
| 5.0     | 67       | 2.52%   |
| 4.19    | 64       | 2.41%   |
| 4.9     | 62       | 2.33%   |
| 5.9     | 42       | 1.58%   |
| 5.6     | 29       | 1.09%   |
| 5.14    | 28       | 1.05%   |
| 5.7     | 27       | 1.02%   |
| 5.12    | 27       | 1.02%   |
| 5.17    | 25       | 0.94%   |
| 5.5     | 15       | 0.56%   |
| 4.1     | 13       | 0.49%   |
| 4.4     | 12       | 0.45%   |
| 4.20    | 5        | 0.19%   |
| 3.10    | 5        | 0.19%   |
| 4.12    | 4        | 0.15%   |
| 5.2     | 3        | 0.11%   |
| 4.14    | 3        | 0.11%   |
| 5.1     | 2        | 0.08%   |
| 4.8     | 2        | 0.08%   |
| 4.13    | 2        | 0.08%   |
| 2.6     | 1        | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 2293     | 96.1%   |
| i686   | 91       | 3.81%   |
| armv7l | 2        | 0.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 1040     | 41.82%  |
| KDE5            | 410      | 16.49%  |
| Unknown         | 315      | 12.67%  |
| XFCE            | 218      | 8.77%   |
| X-Cinnamon      | 151      | 6.07%   |
| MATE            | 88       | 3.54%   |
| KDE4            | 58       | 2.33%   |
| KDE             | 48       | 1.93%   |
| Unity           | 39       | 1.57%   |
| LXQt            | 25       | 1.01%   |
| Cinnamon        | 22       | 0.88%   |
| Budgie          | 14       | 0.56%   |
| Pantheon        | 12       | 0.48%   |
| LXDE            | 11       | 0.44%   |
| i3              | 8        | 0.32%   |
| GNOME Flashback | 6        | 0.24%   |
| GNOME Classic   | 5        | 0.2%    |
| Deepin          | 3        | 0.12%   |
| bspwm           | 3        | 0.12%   |
| awesome         | 2        | 0.08%   |
| trinity         | 1        | 0.04%   |
| qtile           | 1        | 0.04%   |
| Openbox         | 1        | 0.04%   |
| LeftWM          | 1        | 0.04%   |
| ICEWM           | 1        | 0.04%   |
| GNUstep         | 1        | 0.04%   |
| fluxbox         | 1        | 0.04%   |
| Enlightenment   | 1        | 0.04%   |
| DWM             | 1        | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 2051     | 84.02%  |
| Wayland | 170      | 6.96%   |
| Unknown | 146      | 5.98%   |
| Tty     | 74       | 3.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1134     | 45.74%  |
| SDDM    | 424      | 17.1%   |
| GDM     | 406      | 16.38%  |
| LightDM | 174      | 7.02%   |
| TDM     | 144      | 5.81%   |
| GDM3    | 131      | 5.28%   |
| KDM     | 58       | 2.34%   |
| SLiM    | 3        | 0.12%   |
| Ly      | 3        | 0.12%   |
| XDM     | 1        | 0.04%   |
| NODM    | 1        | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| fr_FR       | 1709     | 70.16%  |
| Unknown     | 310      | 12.73%  |
| en_US       | 304      | 12.48%  |
| en_GB       | 31       | 1.27%   |
| C           | 29       | 1.19%   |
| de_DE       | 10       | 0.41%   |
| ru_RU       | 6        | 0.25%   |
| pt_PT       | 4        | 0.16%   |
| nl_NL       | 4        | 0.16%   |
| es_ES       | 4        | 0.16%   |
| fr_CA       | 3        | 0.12%   |
| C.UTF8      | 3        | 0.12%   |
| sv_SE       | 2        | 0.08%   |
| it_IT       | 2        | 0.08%   |
| fr_FR.UTF8  | 2        | 0.08%   |
| fr_BE       | 2        | 0.08%   |
| en_DK       | 2        | 0.08%   |
| sr_RS@latin | 1        | 0.04%   |
| sr_RS       | 1        | 0.04%   |
| ru_UA       | 1        | 0.04%   |
| POSIX       | 1        | 0.04%   |
| fr_LU       | 1        | 0.04%   |
| fr_CH       | 1        | 0.04%   |
| en_US.utf-8 | 1        | 0.04%   |
| en_IE       | 1        | 0.04%   |
| en_EN       | 1        | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1505     | 62.01%  |
| EFI  | 922      | 37.99%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 1934     | 79.26%  |
| Overlay  | 238      | 9.75%   |
| Btrfs    | 102      | 4.18%   |
| Unknown  | 97       | 3.98%   |
| Xfs      | 37       | 1.52%   |
| Zfs      | 17       | 0.7%    |
| Ext2     | 5        | 0.2%    |
| Ext3     | 4        | 0.16%   |
| F2fs     | 2        | 0.08%   |
| Tmpfs    | 1        | 0.04%   |
| Rootfs   | 1        | 0.04%   |
| Reiserfs | 1        | 0.04%   |
| Aufs     | 1        | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1227     | 50.33%  |
| GPT     | 744      | 30.52%  |
| MBR     | 467      | 19.16%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1809     | 74.32%  |
| Yes       | 625      | 25.68%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1528     | 62.47%  |
| Yes       | 918      | 37.53%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| ASUSTek Computer            | 703      | 29.49%  |
| MSI                         | 401      | 16.82%  |
| Gigabyte Technology         | 329      | 13.8%   |
| Dell                        | 197      | 8.26%   |
| ASRock                      | 160      | 6.71%   |
| Hewlett-Packard             | 156      | 6.54%   |
| Lenovo                      | 62       | 2.6%    |
| Acer                        | 56       | 2.35%   |
| Intel                       | 41       | 1.72%   |
| Pegatron                    | 35       | 1.47%   |
| Foxconn                     | 34       | 1.43%   |
| Packard Bell                | 26       | 1.09%   |
| Unknown                     | 24       | 1.01%   |
| Fujitsu                     | 16       | 0.67%   |
| Medion                      | 14       | 0.59%   |
| eMachines                   | 13       | 0.55%   |
| ECS                         | 13       | 0.55%   |
| Supermicro                  | 12       | 0.5%    |
| Shuttle                     | 11       | 0.46%   |
| Apple                       | 7        | 0.29%   |
| Biostar                     | 6        | 0.25%   |
| AZW                         | 6        | 0.25%   |
| AMI                         | 6        | 0.25%   |
| Alienware                   | 6        | 0.25%   |
| NEC Computers               | 4        | 0.17%   |
| Huanan                      | 4        | 0.17%   |
| Fujitsu Siemens             | 4        | 0.17%   |
| ASRockRack                  | 4        | 0.17%   |
| OEM                         | 3        | 0.13%   |
| ABIT                        | 3        | 0.13%   |
| ZOTAC                       | 2        | 0.08%   |
| ICP / iEi                   | 2        | 0.08%   |
| Gateway                     | 2        | 0.08%   |
| BESSTAR Tech                | 2        | 0.08%   |
| Wistron                     | 1        | 0.04%   |
| WinFast                     | 1        | 0.04%   |
| TYAN Computer               | 1        | 0.04%   |
| TECO Electric and Machinery | 1        | 0.04%   |
| SiYW                        | 1        | 0.04%   |
| Sapphire                    | 1        | 0.04%   |
| Protectli                   | 1        | 0.04%   |
| PCP                         | 1        | 0.04%   |
| Online Labs                 | 1        | 0.04%   |
| LIVEFAN                     | 1        | 0.04%   |
| Kontron                     | 1        | 0.04%   |
| JGINYUE                     | 1        | 0.04%   |
| Jetway                      | 1        | 0.04%   |
| HPE                         | 1        | 0.04%   |
| HARDKERNEL                  | 1        | 0.04%   |
| EVGA                        | 1        | 0.04%   |
| DFI                         | 1        | 0.04%   |
| Compaq                      | 1        | 0.04%   |
| American Megatrends         | 1        | 0.04%   |
| AMD                         | 1        | 0.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 96       | 4.03%   |
| Unknown                          | 26       | 1.09%   |
| Gigabyte B450M DS3H              | 20       | 0.84%   |
| Dell OptiPlex 390                | 16       | 0.67%   |
| Dell OptiPlex 9020               | 13       | 0.55%   |
| ASUS PRIME A320M-K               | 13       | 0.55%   |
| MSI MS-7C91                      | 11       | 0.46%   |
| MSI MS-7816                      | 11       | 0.46%   |
| Dell OptiPlex 7010               | 11       | 0.46%   |
| MSI MS-7C02                      | 10       | 0.42%   |
| MSI MS-7C37                      | 9        | 0.38%   |
| MSI MS-7B79                      | 9        | 0.38%   |
| MSI MS-7A38                      | 9        | 0.38%   |
| MSI MS-7850                      | 9        | 0.38%   |
| MSI MS-7817                      | 9        | 0.38%   |
| MSI MS-7758                      | 9        | 0.38%   |
| MSI MS-7693                      | 9        | 0.38%   |
| HP Compaq Elite 8300 SFF         | 9        | 0.38%   |
| Gigabyte 970A-DS3P               | 9        | 0.38%   |
| Dell OptiPlex 3020               | 9        | 0.38%   |
| ASUS PRIME X470-PRO              | 9        | 0.38%   |
| ASUS PRIME B450M-A               | 9        | 0.38%   |
| ASRock B450M Pro4                | 9        | 0.38%   |
| MSI MS-7B86                      | 8        | 0.34%   |
| ASUS TUF Gaming X570-PLUS        | 8        | 0.34%   |
| ASUS TUF B450-PLUS GAMING        | 8        | 0.34%   |
| MSI MS-7A34                      | 7        | 0.29%   |
| MSI MS-7821                      | 7        | 0.29%   |
| MSI MS-7597                      | 7        | 0.29%   |
| HP Compaq 8200 Elite SFF PC      | 7        | 0.29%   |
| Gigabyte G41M-Combo              | 7        | 0.29%   |
| ASUS ROG STRIX X570-E GAMING     | 7        | 0.29%   |
| ASUS P7P55D                      | 7        | 0.29%   |
| MSI MS-7B89                      | 6        | 0.25%   |
| MSI MS-7A32                      | 6        | 0.25%   |
| Gigabyte 990FXA-UD3              | 6        | 0.25%   |
| eMachines EL1352                 | 6        | 0.25%   |
| ASUS Z170-A                      | 6        | 0.25%   |
| ASUS PRIME Z390-P                | 6        | 0.25%   |
| ASUS P8Z77-V                     | 6        | 0.25%   |
| ASUS P5Q-PRO                     | 6        | 0.25%   |
| Supermicro X8STi                 | 5        | 0.21%   |
| MSI MS-7C94                      | 5        | 0.21%   |
| MSI MS-7C56                      | 5        | 0.21%   |
| MSI MS-7C35                      | 5        | 0.21%   |
| MSI MS-7A40                      | 5        | 0.21%   |
| MSI MS-7721                      | 5        | 0.21%   |
| MSI MS-7680                      | 5        | 0.21%   |
| MSI G5320fr                      | 5        | 0.21%   |
| HP ProDesk 600 G1 SFF            | 5        | 0.21%   |
| Gigabyte G31M-ES2L               | 5        | 0.21%   |
| Gigabyte F2A78M-HD2              | 5        | 0.21%   |
| Dell Precision WorkStation T3400 | 5        | 0.21%   |
| Dell Precision Tower 3620        | 5        | 0.21%   |
| Dell Precision T1700             | 5        | 0.21%   |
| Dell Precision 3630 Tower        | 5        | 0.21%   |
| Dell OptiPlex 780                | 5        | 0.21%   |
| Dell OptiPlex 3050               | 5        | 0.21%   |
| ASUS PRIME B360-PLUS             | 5        | 0.21%   |
| ASUS P8Z77-V LX                  | 5        | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell OptiPlex       | 109      | 4.57%   |
| ASUS PRIME          | 97       | 4.07%   |
| ASUS All            | 96       | 4.03%   |
| HP Compaq           | 56       | 2.35%   |
| Dell Precision      | 54       | 2.27%   |
| ASUS ROG            | 52       | 2.18%   |
| Lenovo ThinkCentre  | 49       | 2.06%   |
| ASUS TUF            | 40       | 1.68%   |
| Acer Aspire         | 34       | 1.43%   |
| Unknown             | 26       | 1.09%   |
| Gigabyte B450M      | 23       | 0.96%   |
| HP ProDesk          | 20       | 0.84%   |
| Packard Bell IMEDIA | 19       | 0.8%    |
| ASUS P8Z77-V        | 18       | 0.76%   |
| HP EliteDesk        | 17       | 0.71%   |
| Gigabyte X570       | 16       | 0.67%   |
| Acer Veriton        | 15       | 0.63%   |
| Fujitsu ESPRIMO     | 14       | 0.59%   |
| ASRock B450M        | 13       | 0.55%   |
| Gigabyte B450       | 12       | 0.5%    |
| ASUS P8H61-M        | 12       | 0.5%    |
| ASUS P7P55D         | 12       | 0.5%    |
| MSI MS-7C91         | 11       | 0.46%   |
| MSI MS-7816         | 11       | 0.46%   |
| Dell Inspiron       | 11       | 0.46%   |
| ASUS P8P67          | 11       | 0.46%   |
| ASUS Maximus        | 11       | 0.46%   |
| MSI MS-7C02         | 10       | 0.42%   |
| HP ProLiant         | 10       | 0.42%   |
| Gigabyte Z390       | 10       | 0.42%   |
| Dell XPS            | 10       | 0.42%   |
| MSI MS-7C37         | 9        | 0.38%   |
| MSI MS-7B79         | 9        | 0.38%   |
| MSI MS-7A38         | 9        | 0.38%   |
| MSI MS-7850         | 9        | 0.38%   |
| MSI MS-7817         | 9        | 0.38%   |
| MSI MS-7758         | 9        | 0.38%   |
| MSI MS-7693         | 9        | 0.38%   |
| Gigabyte 970A-DS3P  | 9        | 0.38%   |
| ASUS M5A78L-M       | 9        | 0.38%   |
| MSI MS-7B86         | 8        | 0.34%   |
| HP Pavilion         | 8        | 0.34%   |
| ASUS SABERTOOTH     | 8        | 0.34%   |
| ASUS P6T            | 8        | 0.34%   |
| ASUS P5Q            | 8        | 0.34%   |
| ASUS P5K            | 8        | 0.34%   |
| ASUS M5A97          | 8        | 0.34%   |
| MSI MS-7A34         | 7        | 0.29%   |
| MSI MS-7821         | 7        | 0.29%   |
| MSI MS-7597         | 7        | 0.29%   |
| Gigabyte G41M-Combo | 7        | 0.29%   |
| ASUS STRIX          | 7        | 0.29%   |
| ASUS P7P55D-E       | 7        | 0.29%   |
| MSI MS-7B89         | 6        | 0.25%   |
| MSI MS-7A32         | 6        | 0.25%   |
| Gigabyte 990FXA-UD3 | 6        | 0.25%   |
| Foxconn Pro         | 6        | 0.25%   |
| eMachines EL1352    | 6        | 0.25%   |
| ASUS Z170-A         | 6        | 0.25%   |
| ASUS P8B75-M        | 6        | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 250      | 10.49%  |
| 2013    | 228      | 9.56%   |
| 2012    | 215      | 9.02%   |
| 2011    | 182      | 7.63%   |
| 2010    | 176      | 7.38%   |
| 2014    | 173      | 7.26%   |
| 2019    | 156      | 6.54%   |
| 2009    | 154      | 6.46%   |
| 2017    | 137      | 5.75%   |
| 2020    | 133      | 5.58%   |
| 2008    | 132      | 5.54%   |
| 2015    | 115      | 4.82%   |
| 2016    | 101      | 4.24%   |
| 2007    | 88       | 3.69%   |
| 2021    | 50       | 2.1%    |
| 2006    | 46       | 1.93%   |
| 2005    | 29       | 1.22%   |
| 2004    | 9        | 0.38%   |
| 2003    | 5        | 0.21%   |
| Unknown | 3        | 0.13%   |
| 2002    | 1        | 0.04%   |
| 2001    | 1        | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 2384     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 2325     | 97.36%  |
| Enabled  | 63       | 2.64%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2383     | 99.96%  |
| Yes  | 1        | 0.04%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 598      | 24.63%  |
| 8.01-16.0       | 498      | 20.51%  |
| 3.01-4.0        | 460      | 18.95%  |
| 4.01-8.0        | 338      | 13.92%  |
| 32.01-64.0      | 248      | 10.21%  |
| 1.01-2.0        | 99       | 4.08%   |
| 64.01-256.0     | 65       | 2.68%   |
| 24.01-32.0      | 56       | 2.31%   |
| 2.01-3.0        | 41       | 1.69%   |
| 0.51-1.0        | 18       | 0.74%   |
| 0.01-0.5        | 3        | 0.12%   |
| Unknown         | 3        | 0.12%   |
| More than 256.0 | 1        | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 993      | 37.81%  |
| 2.01-3.0    | 576      | 21.93%  |
| 4.01-8.0    | 357      | 13.59%  |
| 3.01-4.0    | 305      | 11.61%  |
| 0.51-1.0    | 218      | 8.3%    |
| 8.01-16.0   | 96       | 3.66%   |
| 0.01-0.5    | 45       | 1.71%   |
| 16.01-24.0  | 20       | 0.76%   |
| 32.01-64.0  | 8        | 0.3%    |
| Unknown     | 4        | 0.15%   |
| 24.01-32.0  | 3        | 0.11%   |
| 64.01-256.0 | 1        | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 914      | 36.83%  |
| 2       | 703      | 28.32%  |
| 3       | 419      | 16.88%  |
| 4       | 227      | 9.15%   |
| 5       | 111      | 4.47%   |
| 6       | 48       | 1.93%   |
| 0       | 23       | 0.93%   |
| 7       | 22       | 0.89%   |
| 8       | 6        | 0.24%   |
| 9       | 4        | 0.16%   |
| Unknown | 3        | 0.12%   |
| 22      | 1        | 0.04%   |
| 11      | 1        | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1404     | 58.04%  |
| No        | 1015     | 41.96%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2367     | 99.29%  |
| No        | 17       | 0.71%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1498     | 61.77%  |
| Yes       | 927      | 38.23%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1833     | 76.06%  |
| Yes       | 577      | 23.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| France  | 2384     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Desktops | Percent |
|------------------------|----------|---------|
| Paris                  | 324      | 12.71%  |
| Lyon                   | 49       | 1.92%   |
| Marseille              | 42       | 1.65%   |
| Strasbourg             | 38       | 1.49%   |
| Toulouse               | 30       | 1.18%   |
| Nantes                 | 28       | 1.1%    |
| Nice                   | 26       | 1.02%   |
| Montpellier            | 22       | 0.86%   |
| Clichy-sous-Bois       | 21       | 0.82%   |
| Tours                  | 19       | 0.75%   |
| Roubaix                | 19       | 0.75%   |
| Grenoble               | 16       | 0.63%   |
| Rennes                 | 14       | 0.55%   |
| Bordeaux               | 14       | 0.55%   |
| Toulon                 | 13       | 0.51%   |
| La Rochelle            | 13       | 0.51%   |
| Amiens                 | 12       | 0.47%   |
| Lille                  | 11       | 0.43%   |
| Dijon                  | 10       | 0.39%   |
| Poitiers               | 9        | 0.35%   |
| Pau                    | 9        | 0.35%   |
| Nîmes                 | 9        | 0.35%   |
| Argenteuil             | 9        | 0.35%   |
| Violes                 | 8        | 0.31%   |
| Perpignan              | 8        | 0.31%   |
| Metz                   | 8        | 0.31%   |
| Limoges                | 8        | 0.31%   |
| Colomiers              | 8        | 0.31%   |
| Clermont-Ferrand       | 8        | 0.31%   |
| Besançon              | 8        | 0.31%   |
| Aubervilliers          | 8        | 0.31%   |
| Aix-en-Provence        | 8        | 0.31%   |
| Versailles             | 7        | 0.27%   |
| Vannes                 | 7        | 0.27%   |
| Saint-Maur-des-Fossés | 7        | 0.27%   |
| Rueil-Malmaison        | 7        | 0.27%   |
| Rosny-sous-Bois        | 7        | 0.27%   |
| Niort                  | 7        | 0.27%   |
| Chartres               | 7        | 0.27%   |
| Caen                   | 7        | 0.27%   |
| Angers                 | 7        | 0.27%   |
| Villeurbanne           | 6        | 0.24%   |
| Varades                | 6        | 0.24%   |
| Tournefeuille          | 6        | 0.24%   |
| Thionville             | 6        | 0.24%   |
| Suresnes               | 6        | 0.24%   |
| Rouen                  | 6        | 0.24%   |
| Pontault-Combault      | 6        | 0.24%   |
| Orléans               | 6        | 0.24%   |
| Nancy                  | 6        | 0.24%   |
| Marange-Silvange       | 6        | 0.24%   |
| Brest                  | 6        | 0.24%   |
| Boulogne-Billancourt   | 6        | 0.24%   |
| Vélizy-Villacoublay   | 5        | 0.2%    |
| Valence                | 5        | 0.2%    |
| Saint-Nazaire          | 5        | 0.2%    |
| Nanterre               | 5        | 0.2%    |
| Mieuxcé               | 5        | 0.2%    |
| Meaux                  | 5        | 0.2%    |
| Houilles               | 5        | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 962      | 1563   | 22.04%  |
| WDC                       | 821      | 1375   | 18.81%  |
| Samsung Electronics       | 674      | 1141   | 15.44%  |
| Crucial                   | 339      | 503    | 7.77%   |
| Kingston                  | 229      | 282    | 5.25%   |
| Toshiba                   | 210      | 286    | 4.81%   |
| Sandisk                   | 155      | 198    | 3.55%   |
| Hitachi                   | 155      | 203    | 3.55%   |
| MAXTOR                    | 81       | 105    | 1.86%   |
| PNY                       | 74       | 92     | 1.7%    |
| Intel                     | 64       | 80     | 1.47%   |
| HGST                      | 47       | 78     | 1.08%   |
| Unknown                   | 46       | 70     | 1.05%   |
| Phison                    | 43       | 57     | 0.99%   |
| Corsair                   | 38       | 42     | 0.87%   |
| LDLC                      | 35       | 58     | 0.8%    |
| OCZ                       | 34       | 46     | 0.78%   |
| China                     | 30       | 41     | 0.69%   |
| Transcend                 | 26       | 31     | 0.6%    |
| SK Hynix                  | 21       | 27     | 0.48%   |
| Micron/Crucial Technology | 21       | 29     | 0.48%   |
| SPCC                      | 18       | 24     | 0.41%   |
| A-DATA Technology         | 16       | 18     | 0.37%   |
| Micron Technology         | 13       | 18     | 0.3%    |
| Gigabyte Technology       | 10       | 13     | 0.23%   |
| Intenso                   | 9        | 10     | 0.21%   |
| Hewlett-Packard           | 9        | 16     | 0.21%   |
| Silicon Motion            | 8        | 14     | 0.18%   |
| Fujitsu                   | 8        | 17     | 0.18%   |
| Patriot                   | 7        | 12     | 0.16%   |
| ASMT                      | 7        | 7      | 0.16%   |
| LITEONIT                  | 6        | 6      | 0.14%   |
| EMTEC                     | 6        | 8      | 0.14%   |
| Magnetic Data             | 5        | 6      | 0.11%   |
| LaCie                     | 5        | 6      | 0.11%   |
| KingSpec                  | 5        | 6      | 0.11%   |
| JMicron                   | 5        | 8      | 0.11%   |
| Verbatim                  | 4        | 4      | 0.09%   |
| TO Exter                  | 4        | 4      | 0.09%   |
| TEXTORM                   | 4        | 4      | 0.09%   |
| SABRENT                   | 4        | 4      | 0.09%   |
| LITEON                    | 4        | 4      | 0.09%   |
| GOODRAM                   | 4        | 6      | 0.09%   |
| GALAX                     | 4        | 4      | 0.09%   |
| ASMT109x                  | 4        | 5      | 0.09%   |
| Unknown                   | 4        | 5      | 0.09%   |
| XPG                       | 3        | 5      | 0.07%   |
| TCSUNBOW                  | 3        | 5      | 0.07%   |
| PLEXTOR                   | 3        | 3      | 0.07%   |
| KingDian                  | 3        | 4      | 0.07%   |
| Dogfish                   | 3        | 3      | 0.07%   |
| BAITITON                  | 3        | 3      | 0.07%   |
| Apple                     | 3        | 3      | 0.07%   |
| Apacer                    | 3        | 3      | 0.07%   |
| Realtek Semiconductor     | 2        | 2      | 0.05%   |
| Realtek                   | 2        | 2      | 0.05%   |
| MaxDigital                | 2        | 3      | 0.05%   |
| Lexar                     | 2        | 2      | 0.05%   |
| Leven                     | 2        | 2      | 0.05%   |
| KIOXIA                    | 2        | 3      | 0.05%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Samsung SSD 860 EVO 500GB        | 63       | 1.24%   |
| Seagate ST1000DM010-2EP102 1TB   | 62       | 1.22%   |
| Seagate ST2000DM008-2FR102 2TB   | 60       | 1.19%   |
| Seagate ST500DM002-1BD142 500GB  | 59       | 1.17%   |
| Samsung SSD 850 EVO 250GB        | 54       | 1.07%   |
| Crucial CT240BX500SSD1 240GB     | 52       | 1.03%   |
| Seagate ST2000DM001-1ER164 2TB   | 46       | 0.91%   |
| Seagate ST1000DM003-1ER162 1TB   | 45       | 0.89%   |
| Toshiba DT01ACA100 1TB           | 42       | 0.83%   |
| Seagate ST1000DM003-1CH162 1TB   | 42       | 0.83%   |
| Samsung SSD 850 EVO 500GB        | 41       | 0.81%   |
| Seagate ST2000DM001-1CH164 2TB   | 39       | 0.77%   |
| Crucial CT500MX500SSD1 500GB     | 39       | 0.77%   |
| Samsung SSD 860 EVO 250GB        | 38       | 0.75%   |
| Samsung NVMe SSD Drive 500GB     | 35       | 0.69%   |
| Kingston SA400S37240G 240GB SSD  | 34       | 0.67%   |
| Samsung SSD 860 EVO 1TB          | 33       | 0.65%   |
| Seagate ST2000DM006-2DM164 2TB   | 32       | 0.63%   |
| Kingston SA400S37120G 120GB SSD  | 32       | 0.63%   |
| Crucial CT1000MX500SSD1 1TB      | 32       | 0.63%   |
| Kingston SV300S37A120G 120GB SSD | 31       | 0.61%   |
| Seagate ST3500418AS 500GB        | 28       | 0.55%   |
| Samsung HD103SJ 1TB              | 28       | 0.55%   |
| WDC WD10EZEX-08WN4A0 1TB         | 27       | 0.53%   |
| PNY CS900 240GB SSD              | 24       | 0.47%   |
| WDC WD20EZRX-00D8PB0 2TB         | 23       | 0.45%   |
| Unknown SD/MMC/MS PRO 999GB      | 23       | 0.45%   |
| Seagate ST31000524AS 1TB         | 23       | 0.45%   |
| Kingston SA400S37480G 480GB SSD  | 23       | 0.45%   |
| Crucial CT480BX500SSD1 480GB     | 23       | 0.45%   |
| Seagate ST4000DM004-2CV104 4TB   | 22       | 0.43%   |
| PNY CS900 120GB SSD              | 22       | 0.43%   |
| Toshiba DT01ACA050 500GB         | 21       | 0.41%   |
| Samsung SSD 860 QVO 1TB          | 21       | 0.41%   |
| Seagate ST31000528AS 1TB         | 20       | 0.4%    |
| Samsung SSD 840 EVO 250GB        | 20       | 0.4%    |
| WDC WD10EZEX-00BN5A0 1TB         | 19       | 0.38%   |
| Samsung SSD 850 PRO 256GB        | 19       | 0.38%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 18       | 0.36%   |
| Toshiba HDWD120 2TB              | 18       | 0.36%   |
| Samsung SSD 970 EVO Plus 500GB   | 18       | 0.36%   |
| Samsung HD103UJ 1TB              | 18       | 0.36%   |
| Seagate ST3500413AS 500GB        | 17       | 0.34%   |
| Seagate ST2000DL003-9VT166 2TB   | 17       | 0.34%   |
| Toshiba HDWD110 1TB              | 16       | 0.32%   |
| Seagate ST1000DM003-1SB102 1TB   | 16       | 0.32%   |
| Samsung SSD 870 QVO 1TB          | 16       | 0.32%   |
| Samsung NVMe SSD Drive 250GB     | 16       | 0.32%   |
| WDC WD10EZEX-08M2NA0 1TB         | 15       | 0.3%    |
| SanDisk SDSSDA240G 240GB         | 15       | 0.3%    |
| Toshiba DT01ACA200 2TB           | 14       | 0.28%   |
| Seagate ST4000VN008-2DR166 4TB   | 14       | 0.28%   |
| Seagate ST3160815AS 160GB        | 14       | 0.28%   |
| Seagate ST1000DM003-9YN162 1TB   | 14       | 0.28%   |
| Seagate ST1000DM003-1SB10C 1TB   | 14       | 0.28%   |
| Seagate Expansion 4TB            | 14       | 0.28%   |
| Samsung NVMe SSD Drive 1TB       | 14       | 0.28%   |
| Hitachi HDS721010CLA332 1TB      | 14       | 0.28%   |
| Crucial M4-CT128M4SSD2 128GB     | 14       | 0.28%   |
| Seagate ST3320820AS 320GB        | 13       | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 954      | 1531   | 39.42%  |
| WDC                 | 764      | 1274   | 31.57%  |
| Toshiba             | 196      | 259    | 8.1%    |
| Samsung Electronics | 155      | 229    | 6.4%    |
| Hitachi             | 155      | 203    | 6.4%    |
| MAXTOR              | 81       | 105    | 3.35%   |
| HGST                | 47       | 78     | 1.94%   |
| Unknown             | 25       | 31     | 1.03%   |
| Fujitsu             | 8        | 17     | 0.33%   |
| Hewlett-Packard     | 7        | 13     | 0.29%   |
| ASMT                | 6        | 6      | 0.25%   |
| SABRENT             | 4        | 4      | 0.17%   |
| Magnetic Data       | 4        | 4      | 0.17%   |
| ASMT109x            | 3        | 4      | 0.12%   |
| LaCie               | 2        | 2      | 0.08%   |
| Asmedia             | 2        | 4      | 0.08%   |
| USB                 | 1        | 1      | 0.04%   |
| PHD 3.0             | 1        | 1      | 0.04%   |
| MDT                 | 1        | 1      | 0.04%   |
| MARVELL             | 1        | 1      | 0.04%   |
| Intenso             | 1        | 1      | 0.04%   |
| H/W                 | 1        | 1      | 0.04%   |
| Apple               | 1        | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 427      | 642    | 27.58%  |
| Crucial             | 302      | 448    | 19.51%  |
| Kingston            | 207      | 252    | 13.37%  |
| SanDisk             | 136      | 171    | 8.79%   |
| PNY                 | 69       | 83     | 4.46%   |
| WDC                 | 52       | 64     | 3.36%   |
| Intel               | 49       | 62     | 3.17%   |
| OCZ                 | 33       | 42     | 2.13%   |
| China               | 29       | 40     | 1.87%   |
| Transcend           | 25       | 30     | 1.61%   |
| Corsair             | 25       | 27     | 1.61%   |
| LDLC                | 21       | 27     | 1.36%   |
| SPCC                | 16       | 22     | 1.03%   |
| Toshiba             | 13       | 19     | 0.84%   |
| SK Hynix            | 13       | 18     | 0.84%   |
| A-DATA Technology   | 13       | 15     | 0.84%   |
| Micron Technology   | 8        | 11     | 0.52%   |
| Patriot             | 7        | 12     | 0.45%   |
| Intenso             | 7        | 8      | 0.45%   |
| LITEONIT            | 6        | 6      | 0.39%   |
| KingSpec            | 5        | 6      | 0.32%   |
| JMicron             | 5        | 8      | 0.32%   |
| EMTEC               | 5        | 6      | 0.32%   |
| Verbatim            | 4        | 4      | 0.26%   |
| TO Exter            | 4        | 4      | 0.26%   |
| GOODRAM             | 4        | 6      | 0.26%   |
| GALAX               | 4        | 4      | 0.26%   |
| TEXTORM             | 3        | 3      | 0.19%   |
| PLEXTOR             | 3        | 3      | 0.19%   |
| LITEON              | 3        | 3      | 0.19%   |
| KingDian            | 3        | 4      | 0.19%   |
| Gigabyte Technology | 3        | 5      | 0.19%   |
| Dogfish             | 3        | 3      | 0.19%   |
| BAITITON            | 3        | 3      | 0.19%   |
| Apacer              | 3        | 3      | 0.19%   |
| Unknown             | 2        | 5      | 0.13%   |
| TCSUNBOW            | 2        | 4      | 0.13%   |
| Seagate             | 2        | 2      | 0.13%   |
| Integral            | 2        | 2      | 0.13%   |
| Apple               | 2        | 2      | 0.13%   |
| Unknown             | 2        | 2      | 0.13%   |
| Vaseky              | 1        | 1      | 0.06%   |
| USB3.0              | 1        | 1      | 0.06%   |
| TYPEC 1T            | 1        | 1      | 0.06%   |
| Team                | 1        | 1      | 0.06%   |
| StoreJet            | 1        | 1      | 0.06%   |
| SPCC Sol            | 1        | 1      | 0.06%   |
| QUMOX               | 1        | 1      | 0.06%   |
| PNY CS90            | 1        | 1      | 0.06%   |
| Pioneer             | 1        | 2      | 0.06%   |
| ORTIAL              | 1        | 1      | 0.06%   |
| OCZ-VERTEX          | 1        | 1      | 0.06%   |
| Netac               | 1        | 1      | 0.06%   |
| Lexar               | 1        | 1      | 0.06%   |
| Leven               | 1        | 1      | 0.06%   |
| INNOVATION IT       | 1        | 1      | 0.06%   |
| Innodisk            | 1        | 1      | 0.06%   |
| Hoodisk             | 1        | 1      | 0.06%   |
| Gost                | 1        | 1      | 0.06%   |
| DREVO               | 1        | 1      | 0.06%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1831     | 3771   | 51.09%  |
| SSD     | 1268     | 2106   | 35.38%  |
| NVMe    | 399      | 621    | 11.13%  |
| Unknown | 72       | 126    | 2.01%   |
| MMC     | 14       | 19     | 0.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 2247     | 5750   | 80.08%  |
| NVMe | 399      | 619    | 14.22%  |
| SAS  | 146      | 255    | 5.2%    |
| MMC  | 14       | 19     | 0.5%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1731     | 3275   | 51.43%  |
| 0.51-1.0   | 940      | 1504   | 27.93%  |
| 1.01-2.0   | 408      | 658    | 12.12%  |
| 3.01-4.0   | 140      | 224    | 4.16%   |
| 2.01-3.0   | 95       | 137    | 2.82%   |
| 4.01-10.0  | 46       | 70     | 1.37%   |
| 10.01-20.0 | 6        | 9      | 0.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 562      | 22.14%  |
| 251-500        | 446      | 17.57%  |
| 501-1000       | 377      | 14.85%  |
| 1001-2000      | 303      | 11.94%  |
| More than 3000 | 224      | 8.83%   |
| 1-20           | 189      | 7.45%   |
| 2001-3000      | 142      | 5.59%   |
| 51-100         | 118      | 4.65%   |
| Unknown        | 105      | 4.14%   |
| 21-50          | 72       | 2.84%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 848      | 32.52%  |
| 21-50          | 324      | 12.42%  |
| 101-250        | 292      | 11.2%   |
| 51-100         | 265      | 10.16%  |
| 251-500        | 237      | 9.09%   |
| 501-1000       | 228      | 8.74%   |
| 1001-2000      | 181      | 6.94%   |
| Unknown        | 105      | 4.03%   |
| More than 3000 | 77       | 2.95%   |
| 2001-3000      | 51       | 1.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 6        | 7      | 1.57%   |
| Seagate ST31000524AS 1TB          | 5        | 5      | 1.31%   |
| WDC WD5000AAKX-001CA0 500GB       | 4        | 4      | 1.05%   |
| WDC WD10EADS-00M2B0 1TB           | 4        | 6      | 1.05%   |
| Toshiba DT01ACA100 1TB            | 4        | 5      | 1.05%   |
| Samsung Electronics HD321KJ 320GB | 4        | 4      | 1.05%   |
| Samsung Electronics HD103SJ 1TB   | 4        | 5      | 1.05%   |
| Kingston SV300S37A120G 120GB SSD  | 4        | 6      | 1.05%   |
| WDC WD6400AAKS-22A7B2 640GB       | 3        | 5      | 0.79%   |
| WDC WD3200AAKS-00L9A0 320GB       | 3        | 3      | 0.79%   |
| WDC WD3200AAJS-08L7A0 320GB       | 3        | 3      | 0.79%   |
| WDC WD20PURZ-85GU6Y0 2TB          | 3        | 3      | 0.79%   |
| WDC WD20EARS-00MVWB0 2TB          | 3        | 3      | 0.79%   |
| WDC WD10EADS-22M2B0 1TB           | 3        | 3      | 0.79%   |
| Seagate ST9250315AS 250GB         | 3        | 5      | 0.79%   |
| Seagate ST3500418AS 500GB         | 3        | 3      | 0.79%   |
| Seagate ST3500320AS 500GB         | 3        | 3      | 0.79%   |
| Seagate ST3320820AS 320GB         | 3        | 3      | 0.79%   |
| Seagate ST3320418AS 320GB         | 3        | 3      | 0.79%   |
| Seagate ST3160815AS 160GB         | 3        | 3      | 0.79%   |
| Seagate ST31000528AS 1TB          | 3        | 3      | 0.79%   |
| Seagate ST3000DM001-1CH166 3TB    | 3        | 3      | 0.79%   |
| Seagate ST1000DX001-1NS162 1TB    | 3        | 3      | 0.79%   |
| Seagate ST1000DM003-1CH162 1TB    | 3        | 3      | 0.79%   |
| Samsung Electronics HD502HJ 500GB | 3        | 3      | 0.79%   |
| MAXTOR STM3500320AS 500GB         | 3        | 4      | 0.79%   |
| MAXTOR STM3250310AS 250GB         | 3        | 5      | 0.79%   |
| Kingston SA400S37120G 120GB SSD   | 3        | 3      | 0.79%   |
| Hitachi HDS721050CLA362 500GB     | 3        | 7      | 0.79%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 2        | 2      | 0.52%   |
| WDC WD5000AAKS-65YGA0 500GB       | 2        | 2      | 0.52%   |
| WDC WD5000AADS-00S9B0 500GB       | 2        | 2      | 0.52%   |
| WDC WD3200AAJS-22B4A0 320GB       | 2        | 2      | 0.52%   |
| WDC WD30EZRX-00DC0B0 3TB          | 2        | 2      | 0.52%   |
| WDC WD30EFRX-68AX9N0 3TB          | 2        | 5      | 0.52%   |
| WDC WD2500AAKX-753CA1 250GB       | 2        | 2      | 0.52%   |
| WDC WD1600AAJS-60B4A0 160GB       | 2        | 3      | 0.52%   |
| WDC WD10EZEX-60WN4A0 1TB          | 2        | 2      | 0.52%   |
| WDC WD10EZEX-21M2NA0 1TB          | 2        | 2      | 0.52%   |
| WDC WD10EARS-00Y5B1 1TB           | 2        | 3      | 0.52%   |
| WDC WD10EALX-009BA0 1TB           | 2        | 2      | 0.52%   |
| WDC WD10EADS-65L5B1 1TB           | 2        | 2      | 0.52%   |
| WDC WD10EADS-00L5B1 1TB           | 2        | 2      | 0.52%   |
| WDC WD1003FZEX-00MK2A0 1TB        | 2        | 3      | 0.52%   |
| WDC WD1002FAEX-00Y9A0 1TB         | 2        | 3      | 0.52%   |
| Toshiba DT01ACA050 500GB          | 2        | 2      | 0.52%   |
| Seagate STM3500418AS 500GB        | 2        | 3      | 0.52%   |
| Seagate ST380815AS 80GB           | 2        | 2      | 0.52%   |
| Seagate ST3500413AS 500GB         | 2        | 3      | 0.52%   |
| Seagate ST340810A 40GB            | 2        | 2      | 0.52%   |
| Seagate ST3360320AS 360GB         | 2        | 2      | 0.52%   |
| Seagate ST3250310AS 250GB         | 2        | 2      | 0.52%   |
| Seagate ST250DM000-1BD141 250GB   | 2        | 2      | 0.52%   |
| Seagate ST2000DM001-9YN164 2TB    | 2        | 2      | 0.52%   |
| Seagate ST2000DM001-1CH164 2TB    | 2        | 3      | 0.52%   |
| Seagate ST1000DM010-2EP102 1TB    | 2        | 2      | 0.52%   |
| Seagate ST1000DM003-9YN162 1TB    | 2        | 2      | 0.52%   |
| Seagate ST1000DM003-1ER162 1TB    | 2        | 2      | 0.52%   |
| Samsung Electronics HD103UJ 1TB   | 2        | 3      | 0.52%   |
| MAXTOR 6B200M0 208GB              | 2        | 3      | 0.52%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 114      | 143    | 30.56%  |
| Seagate             | 103      | 119    | 27.61%  |
| Samsung Electronics | 31       | 33     | 8.31%   |
| MAXTOR              | 21       | 25     | 5.63%   |
| Hitachi             | 21       | 28     | 5.63%   |
| Crucial             | 14       | 16     | 3.75%   |
| Kingston            | 13       | 16     | 3.49%   |
| Intel               | 11       | 12     | 2.95%   |
| Toshiba             | 10       | 11     | 2.68%   |
| HGST                | 6        | 9      | 1.61%   |
| SK Hynix            | 5        | 9      | 1.34%   |
| SanDisk             | 3        | 4      | 0.8%    |
| OCZ                 | 3        | 3      | 0.8%    |
| LDLC                | 3        | 3      | 0.8%    |
| A-DATA Technology   | 3        | 3      | 0.8%    |
| SPCC                | 2        | 2      | 0.54%   |
| Fujitsu             | 2        | 2      | 0.54%   |
| OCZ-VERTEX          | 1        | 1      | 0.27%   |
| Micron Technology   | 1        | 1      | 0.27%   |
| LITEONIT            | 1        | 1      | 0.27%   |
| KingSpec            | 1        | 1      | 0.27%   |
| INNOVATION IT       | 1        | 1      | 0.27%   |
| Hewlett-Packard     | 1        | 1      | 0.27%   |
| Corsair             | 1        | 1      | 0.27%   |
| ASMT                | 1        | 1      | 0.27%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 113      | 142    | 37.17%  |
| Seagate             | 103      | 119    | 33.88%  |
| Samsung Electronics | 26       | 28     | 8.55%   |
| MAXTOR              | 21       | 25     | 6.91%   |
| Hitachi             | 21       | 28     | 6.91%   |
| Toshiba             | 10       | 11     | 3.29%   |
| HGST                | 6        | 9      | 1.97%   |
| Fujitsu             | 2        | 2      | 0.66%   |
| Hewlett-Packard     | 1        | 1      | 0.33%   |
| ASMT                | 1        | 1      | 0.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 272      | 366    | 80.24%  |
| SSD  | 64       | 77     | 18.88%  |
| NVMe | 3        | 3      | 0.88%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| WDC WD4000FYYZ-01UL1B2 4TB                       | 1        | 1      | 11.11%  |
| WDC WD20EARS-00J99B0 2TB                         | 1        | 1      | 11.11%  |
| WDC WD10EALX-759BA1 1TB                          | 1        | 1      | 11.11%  |
| Seagate ST3500418AS 500GB                        | 1        | 1      | 11.11%  |
| Seagate ST3250318AS 250GB                        | 1        | 1      | 11.11%  |
| Samsung Electronics MZ7LN512HAJQ-00000 512GB SSD | 1        | 2      | 11.11%  |
| Samsung Electronics HD753LJ 752GB                | 1        | 1      | 11.11%  |
| Samsung Electronics HD501LJ 500GB                | 1        | 1      | 11.11%  |
| Kingston SMS200S360G 64GB SSD                    | 1        | 1      | 11.11%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 3        | 3      | 33.33%  |
| Samsung Electronics | 3        | 4      | 33.33%  |
| Seagate             | 2        | 2      | 22.22%  |
| Kingston            | 1        | 1      | 11.11%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 1282     | 3669   | 47.25%  |
| Works    | 1092     | 2518   | 40.25%  |
| Malfunc  | 330      | 446    | 12.16%  |
| Failed   | 9        | 10     | 0.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1563     | 48.65%  |
| AMD                              | 661      | 20.57%  |
| Samsung Electronics              | 186      | 5.79%   |
| Marvell Technology Group         | 124      | 3.86%   |
| Nvidia                           | 120      | 3.73%   |
| JMicron Technology               | 102      | 3.17%   |
| ASMedia Technology               | 93       | 2.89%   |
| Phison Electronics               | 66       | 2.05%   |
| Micron/Crucial Technology        | 63       | 1.96%   |
| Sandisk                          | 52       | 1.62%   |
| VIA Technologies                 | 44       | 1.37%   |
| Kingston Technology Company      | 27       | 0.84%   |
| Silicon Image                    | 17       | 0.53%   |
| Silicon Motion                   | 11       | 0.34%   |
| LSI Logic / Symbios Logic        | 11       | 0.34%   |
| Micron Technology                | 10       | 0.31%   |
| SK Hynix                         | 8        | 0.25%   |
| Broadcom / LSI                   | 8        | 0.25%   |
| Adaptec                          | 7        | 0.22%   |
| Toshiba America Info Systems     | 6        | 0.19%   |
| Silicon Integrated Systems [SiS] | 6        | 0.19%   |
| Integrated Technology Express    | 5        | 0.16%   |
| ADATA Technology                 | 5        | 0.16%   |
| Realtek Semiconductor            | 3        | 0.09%   |
| Hewlett-Packard                  | 3        | 0.09%   |
| Promise Technology               | 2        | 0.06%   |
| Lite-On Technology               | 2        | 0.06%   |
| Unknown                          | 1        | 0.03%   |
| ULi Electronics                  | 1        | 0.03%   |
| Tekram Technology                | 1        | 0.03%   |
| Shenzhen Longsys Electronics     | 1        | 0.03%   |
| Seagate Technology               | 1        | 0.03%   |
| OCZ Technology Group             | 1        | 0.03%   |
| KIOXIA                           | 1        | 0.03%   |
| 3ware                            | 1        | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 382      | 9.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 212      | 5.1%    |
| AMD 400 Series Chipset SATA Controller                                                  | 156      | 3.76%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 128      | 3.08%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 124      | 2.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 124      | 2.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 121      | 2.91%   |
| Intel SATA Controller [RAID mode]                                                       | 114      | 2.74%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 103      | 2.48%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 98       | 2.36%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 96       | 2.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 95       | 2.29%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 93       | 2.24%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 88       | 2.12%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 69       | 1.66%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 69       | 1.66%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 69       | 1.66%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 64       | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 64       | 1.54%   |
| Nvidia MCP61 SATA Controller                                                            | 61       | 1.47%   |
| AMD 500 Series Chipset SATA Controller                                                  | 58       | 1.4%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 55       | 1.32%   |
| Nvidia MCP61 IDE                                                                        | 53       | 1.28%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 44       | 1.06%   |
| AMD FCH SATA Controller D                                                               | 43       | 1.04%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 41       | 0.99%   |
| Phison E12 NVMe Controller                                                              | 39       | 0.94%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 38       | 0.91%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 35       | 0.84%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 33       | 0.79%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 31       | 0.75%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 30       | 0.72%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 30       | 0.72%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 30       | 0.72%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 28       | 0.67%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 27       | 0.65%   |
| AMD 300 Series Chipset SATA Controller                                                  | 27       | 0.65%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 25       | 0.6%    |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 25       | 0.6%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 25       | 0.6%    |
| JMicron JMB362 SATA Controller                                                          | 22       | 0.53%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 22       | 0.53%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 22       | 0.53%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 21       | 0.51%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 20       | 0.48%   |
| Kingston Company A2000 NVMe SSD                                                         | 18       | 0.43%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 18       | 0.43%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 17       | 0.41%   |
| Samsung NVMe SSD Controller 980                                                         | 17       | 0.41%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 17       | 0.41%   |
| JMicron JMB368 IDE controller                                                           | 17       | 0.41%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 17       | 0.41%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 17       | 0.41%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 17       | 0.41%   |
| AMD FCH IDE Controller                                                                  | 17       | 0.41%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 16       | 0.39%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 16       | 0.39%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 16       | 0.39%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 15       | 0.36%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 15       | 0.36%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1756     | 56.08%  |
| IDE  | 744      | 23.76%  |
| NVMe | 406      | 12.97%  |
| RAID | 198      | 6.32%   |
| SAS  | 14       | 0.45%   |
| SCSI | 13       | 0.42%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 1609     | 67.49%  |
| AMD                   | 771      | 32.34%  |
| CentaurHauls          | 2        | 0.08%   |
| Marvell Semiconductor | 1        | 0.04%   |
| ARM                   | 1        | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 39       | 1.63%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 38       | 1.59%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 36       | 1.51%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 27       | 1.13%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 25       | 1.05%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 25       | 1.05%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 25       | 1.05%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 24       | 1%      |
| Intel Core i5-2400 CPU @ 3.10GHz            | 23       | 0.96%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 22       | 0.92%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 22       | 0.92%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 21       | 0.88%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 21       | 0.88%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 20       | 0.84%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 18       | 0.75%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 18       | 0.75%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 18       | 0.75%   |
| AMD Athlon II X2 220 Processor              | 18       | 0.75%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 17       | 0.71%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 17       | 0.71%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 17       | 0.71%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 17       | 0.71%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 17       | 0.71%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 17       | 0.71%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 16       | 0.67%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 16       | 0.67%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 16       | 0.67%   |
| AMD Phenom II X4 955 Processor              | 16       | 0.67%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 15       | 0.63%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 15       | 0.63%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 15       | 0.63%   |
| AMD FX-6300 Six-Core Processor              | 15       | 0.63%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 14       | 0.59%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 14       | 0.59%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 14       | 0.59%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 14       | 0.59%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 13       | 0.54%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 13       | 0.54%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 13       | 0.54%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 13       | 0.54%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 13       | 0.54%   |
| AMD FX-8350 Eight-Core Processor            | 13       | 0.54%   |
| AMD Athlon II X2 250 Processor              | 13       | 0.54%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 12       | 0.5%    |
| Intel Pentium CPU G3220 @ 3.00GHz           | 12       | 0.5%    |
| Intel Core i7-8700 CPU @ 3.20GHz            | 12       | 0.5%    |
| Intel Core i7-7700 CPU @ 3.60GHz            | 12       | 0.5%    |
| Intel Core i7 CPU 860 @ 2.80GHz             | 12       | 0.5%    |
| Intel Core i5-9600K CPU @ 3.70GHz           | 12       | 0.5%    |
| Intel Core i5-4440 CPU @ 3.10GHz            | 12       | 0.5%    |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz       | 12       | 0.5%    |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 12       | 0.5%    |
| AMD Ryzen 5 3600X 6-Core Processor          | 12       | 0.5%    |
| Intel Pentium 4 CPU 3.00GHz                 | 11       | 0.46%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 11       | 0.46%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 11       | 0.46%   |
| Intel Core i5 CPU 760 @ 2.80GHz             | 11       | 0.46%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 11       | 0.46%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 11       | 0.46%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 11       | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 463      | 19.39%  |
| Intel Core i7           | 344      | 14.41%  |
| Intel Core i3           | 166      | 6.95%   |
| AMD Ryzen 5             | 163      | 6.83%   |
| AMD Ryzen 7             | 114      | 4.77%   |
| Intel Xeon              | 111      | 4.65%   |
| Intel Core 2 Duo        | 93       | 3.89%   |
| Intel Pentium           | 79       | 3.31%   |
| Intel Core 2 Quad       | 74       | 3.1%    |
| AMD FX                  | 66       | 2.76%   |
| AMD Athlon II X2        | 54       | 2.26%   |
| Intel Pentium Dual-Core | 51       | 2.14%   |
| AMD Ryzen 3             | 47       | 1.97%   |
| AMD Athlon 64 X2        | 44       | 1.84%   |
| Intel Celeron           | 43       | 1.8%    |
| AMD Ryzen 9             | 40       | 1.68%   |
| AMD Phenom II X4        | 36       | 1.51%   |
| Intel Pentium Dual      | 31       | 1.3%    |
| Intel Atom              | 31       | 1.3%    |
| Intel Pentium 4         | 27       | 1.13%   |
| Intel Core 2            | 26       | 1.09%   |
| Other                   | 23       | 0.96%   |
| Intel Core i9           | 22       | 0.92%   |
| AMD A4                  | 22       | 0.92%   |
| AMD A8                  | 21       | 0.88%   |
| AMD Athlon 64           | 16       | 0.67%   |
| Intel Pentium D         | 14       | 0.59%   |
| AMD Sempron             | 12       | 0.5%    |
| AMD Ryzen Threadripper  | 12       | 0.5%    |
| AMD Athlon II X4        | 12       | 0.5%    |
| Intel Pentium Gold      | 11       | 0.46%   |
| AMD Phenom II X6        | 11       | 0.46%   |
| AMD Athlon              | 10       | 0.42%   |
| AMD A10                 | 10       | 0.42%   |
| AMD Athlon Dual Core    | 9        | 0.38%   |
| AMD A6                  | 9        | 0.38%   |
| AMD E                   | 8        | 0.34%   |
| AMD Athlon X4           | 7        | 0.29%   |
| AMD Ryzen 5 PRO         | 6        | 0.25%   |
| AMD E1                  | 6        | 0.25%   |
| AMD Phenom              | 5        | 0.21%   |
| Intel Genuine           | 4        | 0.17%   |
| AMD Phenom II X2        | 4        | 0.17%   |
| AMD E2                  | 4        | 0.17%   |
| AMD Athlon II X3        | 4        | 0.17%   |
| AMD Turion II Neo       | 3        | 0.13%   |
| AMD Ryzen 7 PRO         | 2        | 0.08%   |
| AMD Ryzen 3 PRO         | 2        | 0.08%   |
| AMD Phenom II X3        | 2        | 0.08%   |
| AMD Dual Core Opteron   | 2        | 0.08%   |
| AMD Athlon XP           | 2        | 0.08%   |
| AMD Athlon X2           | 2        | 0.08%   |
| AMD Athlon II           | 2        | 0.08%   |
| Intel Xeon Bronze       | 1        | 0.04%   |
| Intel Pentium Silver    | 1        | 0.04%   |
| CentaurHauls VIA Nano   | 1        | 0.04%   |
| CentaurHauls VIA C7     | 1        | 0.04%   |
| AMD EPYC                | 1        | 0.04%   |
| AMD A12                 | 1        | 0.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 1007     | 42.03%  |
| 2       | 696      | 29.05%  |
| 6       | 281      | 11.73%  |
| 8       | 176      | 7.35%   |
| 1       | 92       | 3.84%   |
| 12      | 55       | 2.3%    |
| 3       | 32       | 1.34%   |
| Unknown | 21       | 0.88%   |
| 10      | 12       | 0.5%    |
| 16      | 11       | 0.46%   |
| 32      | 5        | 0.21%   |
| 64      | 3        | 0.13%   |
| 24      | 2        | 0.08%   |
| 20      | 2        | 0.08%   |
| 40      | 1        | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 2359     | 98.91%  |
| 2      | 26       | 1.09%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 1225     | 51.19%  |
| 2       | 1147     | 47.93%  |
| Unknown | 21       | 0.88%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 2338     | 97.82%  |
| Unknown        | 29       | 1.21%   |
| 32-bit         | 23       | 0.96%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 429      | 17.44%  |
| 0x306c3    | 275      | 11.18%  |
| 0x206a7    | 155      | 6.3%    |
| 0x1067a    | 140      | 5.69%   |
| 0x306a9    | 139      | 5.65%   |
| 0x506e3    | 101      | 4.11%   |
| 0x010000c8 | 71       | 2.89%   |
| 0x08701021 | 67       | 2.72%   |
| 0x906ea    | 62       | 2.52%   |
| 0x906e9    | 60       | 2.44%   |
| 0x0800820d | 59       | 2.4%    |
| 0x08701013 | 44       | 1.79%   |
| 0x06000852 | 41       | 1.67%   |
| 0x6fd      | 40       | 1.63%   |
| 0x106e5    | 37       | 1.5%    |
| 0x06001119 | 36       | 1.46%   |
| 0x10676    | 30       | 1.22%   |
| 0x08108109 | 26       | 1.06%   |
| 0x6fb      | 24       | 0.98%   |
| 0x906ed    | 22       | 0.89%   |
| 0x08001138 | 22       | 0.89%   |
| 0xa0653    | 18       | 0.73%   |
| 0x106a5    | 18       | 0.73%   |
| 0xa0655    | 17       | 0.69%   |
| 0x08001137 | 17       | 0.69%   |
| 0x306f2    | 16       | 0.65%   |
| 0x0a201016 | 16       | 0.65%   |
| 0x206d7    | 15       | 0.61%   |
| 0x10677    | 15       | 0.61%   |
| 0x010000db | 14       | 0.57%   |
| 0x906ec    | 13       | 0.53%   |
| 0xa0671    | 12       | 0.49%   |
| 0x6f6      | 12       | 0.49%   |
| 0x206c2    | 12       | 0.49%   |
| 0x0a201009 | 12       | 0.49%   |
| 0x010000c7 | 12       | 0.49%   |
| 0x906eb    | 11       | 0.45%   |
| 0x6f2      | 11       | 0.45%   |
| 0x20655    | 11       | 0.45%   |
| 0x08600106 | 11       | 0.45%   |
| 0x106ca    | 10       | 0.41%   |
| 0x0810100b | 10       | 0.41%   |
| 0x406f1    | 9        | 0.37%   |
| 0x20652    | 9        | 0.37%   |
| 0x03000027 | 9        | 0.37%   |
| 0x010000dc | 9        | 0.37%   |
| 0xf43      | 8        | 0.33%   |
| 0x306e4    | 8        | 0.33%   |
| 0x08101016 | 8        | 0.33%   |
| 0x0800820b | 8        | 0.33%   |
| 0x0600063e | 8        | 0.33%   |
| 0x05000119 | 8        | 0.33%   |
| 0x50654    | 7        | 0.28%   |
| 0x406c4    | 7        | 0.28%   |
| 0x30678    | 7        | 0.28%   |
| 0x06003106 | 7        | 0.28%   |
| 0xf41      | 6        | 0.24%   |
| 0x0a50000c | 6        | 0.24%   |
| 0x07030105 | 6        | 0.24%   |
| 0x010000b6 | 6        | 0.24%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 332      | 13.92%  |
| KabyLake         | 206      | 8.64%   |
| Penryn           | 199      | 8.34%   |
| SandyBridge      | 191      | 8.01%   |
| IvyBridge        | 160      | 6.71%   |
| Zen 2            | 157      | 6.58%   |
| K10              | 136      | 5.7%    |
| Skylake          | 134      | 5.62%   |
| Zen+             | 109      | 4.57%   |
| Core             | 99       | 4.15%   |
| Piledriver       | 95       | 3.98%   |
| K8 Hammer        | 80       | 3.35%   |
| Zen              | 77       | 3.23%   |
| Nehalem          | 68       | 2.85%   |
| Zen 3            | 47       | 1.97%   |
| CometLake        | 45       | 1.89%   |
| NetBurst         | 44       | 1.84%   |
| Westmere         | 35       | 1.47%   |
| Silvermont       | 23       | 0.96%   |
| Bonnell          | 21       | 0.88%   |
| Broadwell        | 19       | 0.8%    |
| Unknown          | 16       | 0.67%   |
| Bobcat           | 13       | 0.55%   |
| Excavator        | 11       | 0.46%   |
| Bulldozer        | 11       | 0.46%   |
| Steamroller      | 10       | 0.42%   |
| K10 Llano        | 10       | 0.42%   |
| Icelake          | 9        | 0.38%   |
| Puma             | 6        | 0.25%   |
| Goldmont plus    | 6        | 0.25%   |
| Goldmont         | 5        | 0.21%   |
| K6               | 4        | 0.17%   |
| Jaguar           | 4        | 0.17%   |
| Alderlake Hybrid | 2        | 0.08%   |
| Tremont          | 1        | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 1159     | 45.54%  |
| AMD                              | 706      | 27.74%  |
| Intel                            | 642      | 25.23%  |
| Matrox Electronics Systems       | 14       | 0.55%   |
| ASPEED Technology                | 12       | 0.47%   |
| VIA Technologies                 | 6        | 0.24%   |
| Silicon Integrated Systems [SiS] | 3        | 0.12%   |
| ATI Technologies                 | 2        | 0.08%   |
| S3 Graphics                      | 1        | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 135      | 5.14%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 77       | 2.93%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 75       | 2.86%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 68       | 2.59%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 62       | 2.36%   |
| Intel HD Graphics 530                                                                    | 53       | 2.02%   |
| Nvidia GT218 [GeForce 210]                                                               | 51       | 1.94%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 50       | 1.9%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 48       | 1.83%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 41       | 1.56%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 39       | 1.49%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 38       | 1.45%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 37       | 1.41%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 32       | 1.22%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 30       | 1.14%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 28       | 1.07%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 28       | 1.07%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 26       | 0.99%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 26       | 0.99%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 25       | 0.95%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 25       | 0.95%   |
| Intel HD Graphics 630                                                                    | 24       | 0.91%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 23       | 0.88%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 21       | 0.8%    |
| AMD RS780L [Radeon 3000]                                                                 | 21       | 0.8%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 19       | 0.72%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 18       | 0.69%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 18       | 0.69%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 18       | 0.69%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 18       | 0.69%   |
| AMD Renoir                                                                               | 18       | 0.69%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 17       | 0.65%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 17       | 0.65%   |
| AMD RV620 LE [Radeon HD 3450]                                                            | 17       | 0.65%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 16       | 0.61%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 16       | 0.61%   |
| AMD Juniper XT [Radeon HD 5770]                                                          | 16       | 0.61%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 15       | 0.57%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 15       | 0.57%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 14       | 0.53%   |
| AMD RV730 PRO [Radeon HD 4650]                                                           | 14       | 0.53%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 13       | 0.5%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 13       | 0.5%    |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                                      | 13       | 0.5%    |
| Nvidia GP107GL [Quadro P400]                                                             | 12       | 0.46%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 12       | 0.46%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 12       | 0.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 12       | 0.46%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 12       | 0.46%   |
| AMD RS880 [Radeon HD 4250]                                                               | 12       | 0.46%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 11       | 0.42%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 11       | 0.42%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 11       | 0.42%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 11       | 0.42%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 11       | 0.42%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 10       | 0.38%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 10       | 0.38%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 10       | 0.38%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 10       | 0.38%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                                        | 10       | 0.38%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 1089     | 44.96%  |
| 1 x AMD              | 628      | 25.93%  |
| 1 x Intel            | 527      | 21.76%  |
| Intel + Nvidia       | 41       | 1.69%   |
| 2 x AMD              | 38       | 1.57%   |
| AMD + Nvidia         | 22       | 0.91%   |
| Intel + AMD          | 20       | 0.83%   |
| 2 x Nvidia           | 15       | 0.62%   |
| 1 x Matrox           | 12       | 0.5%    |
| 1 x ASPEED           | 10       | 0.41%   |
| 1 x VIA              | 6        | 0.25%   |
| Other                | 4        | 0.17%   |
| 1 x SiS              | 3        | 0.12%   |
| 3 x Nvidia           | 1        | 0.04%   |
| 3 x AMD              | 1        | 0.04%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.04%   |
| 1 x S3 Graphics      | 1        | 0.04%   |
| Nvidia + Matrox      | 1        | 0.04%   |
| Nvidia + ASPEED      | 1        | 0.04%   |
| AMD + ASPEED         | 1        | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1697     | 69.63%  |
| Proprietary | 626      | 25.69%  |
| Unknown     | 114      | 4.68%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 810      | 32.87%  |
| 0.01-0.5   | 391      | 15.87%  |
| 1.01-2.0   | 390      | 15.83%  |
| 0.51-1.0   | 344      | 13.96%  |
| 3.01-4.0   | 204      | 8.28%   |
| 7.01-8.0   | 156      | 6.33%   |
| 5.01-6.0   | 83       | 3.37%   |
| 8.01-16.0  | 44       | 1.79%   |
| 2.01-3.0   | 35       | 1.42%   |
| 16.01-24.0 | 4        | 0.16%   |
| 4.01-5.0   | 3        | 0.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 410      | 15.78%  |
| Iiyama                  | 248      | 9.54%   |
| Dell                    | 223      | 8.58%   |
| Hewlett-Packard         | 203      | 7.81%   |
| Goldstar                | 184      | 7.08%   |
| Acer                    | 183      | 7.04%   |
| Ancor Communications    | 167      | 6.43%   |
| Philips                 | 136      | 5.23%   |
| AOC                     | 111      | 4.27%   |
| BenQ                    | 93       | 3.58%   |
| ViewSonic               | 58       | 2.23%   |
| ASUSTek Computer        | 35       | 1.35%   |
| Unknown                 | 34       | 1.31%   |
| HannStar                | 28       | 1.08%   |
| Idek Iiyama             | 26       | 1%      |
| Packard Bell            | 25       | 0.96%   |
| LG Electronics          | 25       | 0.96%   |
| Lenovo                  | 24       | 0.92%   |
| Sony                    | 21       | 0.81%   |
| NEC Computers           | 17       | 0.65%   |
| Eizo                    | 17       | 0.65%   |
| Vestel Elektronik       | 16       | 0.62%   |
| Hitachi                 | 16       | 0.62%   |
| Fujitsu Siemens         | 16       | 0.62%   |
| Medion                  | 15       | 0.58%   |
| Hyundai ImageQuest      | 12       | 0.46%   |
| Denver                  | 11       | 0.42%   |
| SNC                     | 9        | 0.35%   |
| MSI                     | 8        | 0.31%   |
| Belinea                 | 8        | 0.31%   |
| Panasonic               | 7        | 0.27%   |
| NECCI                   | 7        | 0.27%   |
| HKC                     | 7        | 0.27%   |
| RTK                     | 6        | 0.23%   |
| RS                      | 6        | 0.23%   |
| Toshiba                 | 5        | 0.19%   |
| Plain Tree Systems      | 5        | 0.19%   |
| NUL                     | 5        | 0.19%   |
| HPN                     | 5        | 0.19%   |
| Gigabyte Technology     | 5        | 0.19%   |
| Unknown                 | 5        | 0.19%   |
| Vestel                  | 4        | 0.15%   |
| SENSY                   | 4        | 0.15%   |
| RIS                     | 4        | 0.15%   |
| Onkyo                   | 4        | 0.15%   |
| OEM                     | 4        | 0.15%   |
| Lite-On                 | 4        | 0.15%   |
| LG Display              | 4        | 0.15%   |
| Lenovo Group Limited    | 4        | 0.15%   |
| GDH                     | 4        | 0.15%   |
| Chi Mei Optoelectronics | 4        | 0.15%   |
| Apple                   | 4        | 0.15%   |
| ___                     | 3        | 0.12%   |
| SHARP                   | 3        | 0.12%   |
| NTS                     | 3        | 0.12%   |
| Microstep               | 3        | 0.12%   |
| Lacie                   | 3        | 0.12%   |
| Jean                    | 3        | 0.12%   |
| InnoLux Display         | 3        | 0.12%   |
| IBM                     | 3        | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                 | 24       | 0.86%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 18       | 0.65%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                         | 16       | 0.58%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 13       | 0.47%   |
| Iiyama PLE2283H IVM562E 1920x1080 477x268mm 21.5-inch                 | 11       | 0.4%    |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 9        | 0.32%   |
| Iiyama PLX2783H IVM6611 1920x1080 598x336mm 27.0-inch                 | 9        | 0.32%   |
| AOC F22 AOC2200 1920x1080 476x268mm 21.5-inch                         | 9        | 0.32%   |
| Ancor Communications VE247 ACI2493 1920x1080 530x300mm 24.0-inch      | 9        | 0.32%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 520x290mm 23.4-inch | 9        | 0.32%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                | 8        | 0.29%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 8        | 0.29%   |
| Iiyama PLB2403WS IVM5601 1920x1200 519x324mm 24.1-inch                | 8        | 0.29%   |
| Iiyama PL2530H IVM6132 1920x1080 544x303mm 24.5-inch                  | 8        | 0.29%   |
| Hewlett-Packard v220 HWP26FE 1680x1050 473x296mm 22.0-inch            | 8        | 0.29%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                     | 8        | 0.29%   |
| Ancor Communications VX238 ACI23C1 1920x1080 510x290mm 23.1-inch      | 8        | 0.29%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 7        | 0.25%   |
| Iiyama PL2492H IVM612F 1920x1080 527x296mm 23.8-inch                  | 7        | 0.25%   |
| Iiyama PL2474H IVM6146 1920x1080 521x293mm 23.5-inch                  | 7        | 0.25%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                 | 7        | 0.25%   |
| Hewlett-Packard S2231 HWP2905 1920x1080 477x268mm 21.5-inch           | 7        | 0.25%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 7        | 0.25%   |
| Dell P2214H DELA098 1920x1080 477x268mm 21.5-inch                     | 7        | 0.25%   |
| BenQ GW2765 BNQ78D6 2560x1440 597x336mm 27.0-inch                     | 7        | 0.25%   |
| AOC 24G1WG4 AOC2401 1920x1080 521x293mm 23.5-inch                     | 7        | 0.25%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch | 7        | 0.25%   |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                     | 7        | 0.25%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch               | 6        | 0.22%   |
| Iiyama PLE2403WS IVM5604 1920x1200 519x324mm 24.1-inch                | 6        | 0.22%   |
| Iiyama PL2776HD IVM6605 1920x1080 598x336mm 27.0-inch                 | 6        | 0.22%   |
| Goldstar W2234 GSM56B8 1680x1050 474x296mm 22.0-inch                  | 6        | 0.22%   |
| Goldstar IPS235 GSM587D 1920x1080 510x290mm 23.1-inch                 | 6        | 0.22%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 6        | 0.22%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 6        | 0.22%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 6        | 0.22%   |
| Acer AL1916W ACRAD52 1440x900 408x255mm 18.9-inch                     | 6        | 0.22%   |
| SNC PHOTO 190V SNC1850 1366x768 409x230mm 18.5-inch                   | 5        | 0.18%   |
| Samsung Electronics SyncMaster SAM034D 1280x1024 376x301mm 19.0-inch  | 5        | 0.18%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 490x320mm 23.0-inch  | 5        | 0.18%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 5        | 0.18%   |
| Samsung Electronics SyncMaster SAM011F 1280x1024 376x301mm 19.0-inch  | 5        | 0.18%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch     | 5        | 0.18%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch               | 5        | 0.18%   |
| Philips LCD Monitor FTV 1920x1080                                     | 5        | 0.18%   |
| NUL LCD Monitor NUL0001 1280x1024 338x270mm 17.0-inch                 | 5        | 0.18%   |
| Iiyama X2483/2481 IVM6128 1920x1080 527x296mm 23.8-inch               | 5        | 0.18%   |
| Iiyama PLE2483H-DP IVM611E 1920x1080 531x299mm 24.0-inch              | 5        | 0.18%   |
| Iiyama PL2773H IVM660A 1920x1080 598x336mm 27.0-inch                  | 5        | 0.18%   |
| Iiyama PL2530H IVM6133 1920x1080 544x303mm 24.5-inch                  | 5        | 0.18%   |
| Iiyama PL2390 IVM562D 1920x1080 510x290mm 23.1-inch                   | 5        | 0.18%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch            | 5        | 0.18%   |
| Hewlett-Packard vs17 HWP2647 1280x1024 337x270mm 17.0-inch            | 5        | 0.18%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch          | 5        | 0.18%   |
| Hewlett-Packard Compaq Q2022 HWP291A 1600x900 443x249mm 20.0-inch     | 5        | 0.18%   |
| Hewlett-Packard 2309 HWP2821 1920x1080 510x287mm 23.0-inch            | 5        | 0.18%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                  | 5        | 0.18%   |
| Dell P170S DEL4058 1280x1024 338x270mm 17.0-inch                      | 5        | 0.18%   |
| AOC Q3279WG5B AOC3279 2560x1440 730x430mm 33.4-inch                   | 5        | 0.18%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 5        | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1181     | 46.51%  |
| 1680x1050 (WSXGA+) | 232      | 9.14%   |
| 1280x1024 (SXGA)   | 230      | 9.06%   |
| 2560x1440 (QHD)    | 161      | 6.34%   |
| 3840x2160 (4K)     | 129      | 5.08%   |
| 1440x900 (WXGA+)   | 103      | 4.06%   |
| 1920x1200 (WUXGA)  | 92       | 3.62%   |
| Unknown            | 85       | 3.35%   |
| 1600x900 (HD+)     | 60       | 2.36%   |
| 1366x768 (WXGA)    | 43       | 1.69%   |
| 3840x1080          | 33       | 1.3%    |
| 1360x768           | 30       | 1.18%   |
| 1600x1200          | 20       | 0.79%   |
| 3440x1440          | 19       | 0.75%   |
| 2560x1080          | 19       | 0.75%   |
| 1024x768 (XGA)     | 16       | 0.63%   |
| 4480x1440          | 7        | 0.28%   |
| 3200x1080          | 7        | 0.28%   |
| 3600x1080          | 5        | 0.2%    |
| 3840x1600          | 4        | 0.16%   |
| 1920x540           | 4        | 0.16%   |
| 1280x960           | 4        | 0.16%   |
| 5760x2160          | 3        | 0.12%   |
| 5760x1200          | 3        | 0.12%   |
| 5760x1080          | 3        | 0.12%   |
| 2560x1024          | 3        | 0.12%   |
| 7680x2160          | 2        | 0.08%   |
| 3200x1200          | 2        | 0.08%   |
| 2960x1050          | 2        | 0.08%   |
| 2560x1600          | 2        | 0.08%   |
| 2288x1287          | 2        | 0.08%   |
| 2048x1152          | 2        | 0.08%   |
| 1280x768           | 2        | 0.08%   |
| 1280x720 (HD)      | 2        | 0.08%   |
| 6720x2160          | 1        | 0.04%   |
| 6400x2160          | 1        | 0.04%   |
| 6400x1080          | 1        | 0.04%   |
| 5040x1080          | 1        | 0.04%   |
| 4880x1080          | 1        | 0.04%   |
| 4480x1600          | 1        | 0.04%   |
| 4240x1440          | 1        | 0.04%   |
| 4160x1440          | 1        | 0.04%   |
| 4096x2160          | 1        | 0.04%   |
| 3840x1440          | 1        | 0.04%   |
| 3840x1200          | 1        | 0.04%   |
| 3520x1200          | 1        | 0.04%   |
| 3360x1200          | 1        | 0.04%   |
| 3360x1050          | 1        | 0.04%   |
| 3280x1080          | 1        | 0.04%   |
| 3280x1050          | 1        | 0.04%   |
| 3120x1050          | 1        | 0.04%   |
| 3046x1050          | 1        | 0.04%   |
| 2944x1080          | 1        | 0.04%   |
| 2880x1200          | 1        | 0.04%   |
| 2704x1050          | 1        | 0.04%   |
| 2464x900           | 1        | 0.04%   |
| 2304x768           | 1        | 0.04%   |
| 2200x1650          | 1        | 0.04%   |
| 1920x2100          | 1        | 0.04%   |
| 1280x800 (WXGA)    | 1        | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 378      | 14.73%  |
| 24      | 345      | 13.44%  |
| 27      | 339      | 13.21%  |
| 21      | 301      | 11.73%  |
| Unknown | 285      | 11.1%   |
| 19      | 206      | 8.02%   |
| 22      | 160      | 6.23%   |
| 17      | 119      | 4.64%   |
| 20      | 96       | 3.74%   |
| 18      | 69       | 2.69%   |
| 31      | 46       | 1.79%   |
| 34      | 30       | 1.17%   |
| 84      | 28       | 1.09%   |
| 15      | 23       | 0.9%    |
| 32      | 19       | 0.74%   |
| 25      | 18       | 0.7%    |
| 72      | 17       | 0.66%   |
| 54      | 13       | 0.51%   |
| 33      | 12       | 0.47%   |
| 40      | 9        | 0.35%   |
| 65      | 6        | 0.23%   |
| 46      | 5        | 0.19%   |
| 12      | 5        | 0.19%   |
| 29      | 4        | 0.16%   |
| 26      | 4        | 0.16%   |
| 16      | 4        | 0.16%   |
| 49      | 3        | 0.12%   |
| 37      | 3        | 0.12%   |
| 14      | 3        | 0.12%   |
| 52      | 2        | 0.08%   |
| 48      | 2        | 0.08%   |
| 43      | 2        | 0.08%   |
| 42      | 2        | 0.08%   |
| 35      | 2        | 0.08%   |
| 28      | 2        | 0.08%   |
| 142     | 1        | 0.04%   |
| 60      | 1        | 0.04%   |
| 55      | 1        | 0.04%   |
| 47      | 1        | 0.04%   |
| 30      | 1        | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 954      | 38.69%  |
| 401-500        | 699      | 28.35%  |
| Unknown        | 285      | 11.56%  |
| 301-350        | 137      | 5.56%   |
| 351-400        | 135      | 5.47%   |
| 601-700        | 89       | 3.61%   |
| 701-800        | 61       | 2.47%   |
| 1501-2000      | 45       | 1.82%   |
| 1001-1500      | 34       | 1.38%   |
| 801-900        | 14       | 0.57%   |
| 201-300        | 8        | 0.32%   |
| 901-1000       | 4        | 0.16%   |
| More than 2000 | 1        | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1394     | 58.35%  |
| 16/10   | 394      | 16.49%  |
| Unknown | 261      | 10.93%  |
| 5/4     | 218      | 9.13%   |
| 4/3     | 43       | 1.8%    |
| 21/9    | 38       | 1.59%   |
| 3/2     | 23       | 0.96%   |
| 6/5     | 11       | 0.46%   |
| 32/9    | 4        | 0.17%   |
| 11/10   | 2        | 0.08%   |
| 1.00    | 1        | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 953      | 38.01%  |
| 151-200        | 404      | 16.11%  |
| 301-350        | 345      | 13.76%  |
| Unknown        | 285      | 11.37%  |
| 141-150        | 148      | 5.9%    |
| 251-300        | 128      | 5.11%   |
| 351-500        | 107      | 4.27%   |
| More than 1000 | 70       | 2.79%   |
| 501-1000       | 27       | 1.08%   |
| 101-110        | 21       | 0.84%   |
| 131-140        | 6        | 0.24%   |
| 71-80          | 5        | 0.2%    |
| 121-130        | 4        | 0.16%   |
| 81-90          | 2        | 0.08%   |
| 111-120        | 2        | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 1543     | 64.72%  |
| 101-120 | 415      | 17.41%  |
| Unknown | 285      | 11.95%  |
| 121-160 | 68       | 2.85%   |
| 1-50    | 52       | 2.18%   |
| 161-240 | 21       | 0.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1824     | 75.19%  |
| 2     | 423      | 17.44%  |
| 0     | 137      | 5.65%   |
| 3     | 40       | 1.65%   |
| 4     | 2        | 0.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 1439     | 43.53%  |
| Intel                             | 860      | 26.01%  |
| Qualcomm Atheros                  | 255      | 7.71%   |
| Broadcom                          | 106      | 3.21%   |
| Nvidia                            | 90       | 2.72%   |
| Marvell Technology Group          | 61       | 1.85%   |
| TP-Link                           | 52       | 1.57%   |
| Ralink                            | 49       | 1.48%   |
| Ralink Technology                 | 44       | 1.33%   |
| NetGear                           | 43       | 1.3%    |
| D-Link System                     | 30       | 0.91%   |
| Broadcom Limited                  | 29       | 0.88%   |
| VIA Technologies                  | 20       | 0.6%    |
| Samsung Electronics               | 18       | 0.54%   |
| D-Link                            | 15       | 0.45%   |
| Microsoft                         | 14       | 0.42%   |
| Belkin Components                 | 13       | 0.39%   |
| Aquantia                          | 11       | 0.33%   |
| MediaTek                          | 10       | 0.3%    |
| Qualcomm Atheros Communications   | 9        | 0.27%   |
| Guillemot                         | 9        | 0.27%   |
| Huawei Technologies               | 8        | 0.24%   |
| ASIX Electronics                  | 8        | 0.24%   |
| Edimax Technology                 | 7        | 0.21%   |
| ASUSTek Computer                  | 7        | 0.21%   |
| Xiaomi                            | 5        | 0.15%   |
| IMC Networks                      | 5        | 0.15%   |
| TRENDnet                          | 4        | 0.12%   |
| Silicon Integrated Systems [SiS]  | 4        | 0.12%   |
| STMicroelectronics                | 3        | 0.09%   |
| Sagem                             | 3        | 0.09%   |
| Linksys                           | 3        | 0.09%   |
| JMicron Technology                | 3        | 0.09%   |
| Google                            | 3        | 0.09%   |
| Gemtek                            | 3        | 0.09%   |
| Arduino SA                        | 3        | 0.09%   |
| 3Com                              | 3        | 0.09%   |
| Toshiba                           | 2        | 0.06%   |
| Qualcomm                          | 2        | 0.06%   |
| QLogic                            | 2        | 0.06%   |
| Pulse-Eight                       | 2        | 0.06%   |
| OnePlus Technology (Shenzhen)     | 2        | 0.06%   |
| Motorola PCS                      | 2        | 0.06%   |
| Microchip Technology              | 2        | 0.06%   |
| Metrologic Instruments            | 2        | 0.06%   |
| LSI                               | 2        | 0.06%   |
| Intersil                          | 2        | 0.06%   |
| ICS Advent                        | 2        | 0.06%   |
| HTC (High Tech Computer)          | 2        | 0.06%   |
| Fujitsu Siemens Computers         | 2        | 0.06%   |
| Accton Technology                 | 2        | 0.06%   |
| ZyDAS                             | 1        | 0.03%   |
| Wilocity                          | 1        | 0.03%   |
| Unknown                           | 1        | 0.03%   |
| Texas Instruments                 | 1        | 0.03%   |
| Tenda                             | 1        | 0.03%   |
| Tehuti Networks                   | 1        | 0.03%   |
| Sundance Technology Inc / IC Plus | 1        | 0.03%   |
| Sigma Designs                     | 1        | 0.03%   |
| RetroFreak PCB                    | 1        | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1168     | 31.87%  |
| Intel I211 Gigabit Network Connection                             | 102      | 2.78%   |
| Intel Ethernet Connection (2) I219-V                              | 98       | 2.67%   |
| Realtek RTL8125 2.5GbE Controller                                 | 80       | 2.18%   |
| Intel Wi-Fi 6 AX200                                               | 80       | 2.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 73       | 1.99%   |
| Intel 82579V Gigabit Network Connection                           | 59       | 1.61%   |
| Intel Ethernet Connection I217-LM                                 | 54       | 1.47%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 46       | 1.26%   |
| Nvidia MCP61 Ethernet                                             | 45       | 1.23%   |
| Intel Ethernet Connection (7) I219-V                              | 45       | 1.23%   |
| Intel Ethernet Connection (2) I218-V                              | 40       | 1.09%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 37       | 1.01%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 36       | 0.98%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 33       | 0.9%    |
| Intel 82574L Gigabit Network Connection                           | 33       | 0.9%    |
| Intel Ethernet Connection I217-V                                  | 31       | 0.85%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 30       | 0.82%   |
| Intel Ethernet Connection (2) I219-LM                             | 29       | 0.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 27       | 0.74%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 27       | 0.74%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 24       | 0.65%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 24       | 0.65%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 23       | 0.63%   |
| Intel Wireless-AC 9260                                            | 23       | 0.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 22       | 0.6%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 22       | 0.6%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 21       | 0.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 20       | 0.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 20       | 0.55%   |
| Ralink MT7601U Wireless Adapter                                   | 18       | 0.49%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 18       | 0.49%   |
| Intel Ethernet Controller I225-V                                  | 18       | 0.49%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 17       | 0.46%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 16       | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 16       | 0.44%   |
| Intel I210 Gigabit Network Connection                             | 16       | 0.44%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 16       | 0.44%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 15       | 0.41%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 15       | 0.41%   |
| Realtek 802.11ac NIC                                              | 15       | 0.41%   |
| Intel Wireless 3165                                               | 15       | 0.41%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 14       | 0.38%   |
| Intel Wireless 8260                                               | 13       | 0.35%   |
| Intel Wireless 7260                                               | 13       | 0.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 13       | 0.35%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 13       | 0.35%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 12       | 0.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 12       | 0.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 12       | 0.33%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 12       | 0.33%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 11       | 0.3%    |
| Nvidia MCP77 Ethernet                                             | 11       | 0.3%    |
| Nvidia CK804 Ethernet Controller                                  | 11       | 0.3%    |
| Intel Ethernet Connection (7) I219-LM                             | 11       | 0.3%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 10       | 0.27%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 10       | 0.27%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 10       | 0.27%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 10       | 0.27%   |
| NetGear A6210                                                     | 10       | 0.27%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 243      | 24.97%  |
| Intel                                 | 241      | 24.77%  |
| Qualcomm Atheros                      | 132      | 13.57%  |
| TP-Link                               | 52       | 5.34%   |
| Ralink                                | 49       | 5.04%   |
| Ralink Technology                     | 44       | 4.52%   |
| NetGear                               | 42       | 4.32%   |
| Broadcom                              | 39       | 4.01%   |
| D-Link                                | 15       | 1.54%   |
| Microsoft                             | 14       | 1.44%   |
| D-Link System                         | 14       | 1.44%   |
| Belkin Components                     | 13       | 1.34%   |
| Qualcomm Atheros Communications       | 9        | 0.92%   |
| Guillemot                             | 9        | 0.92%   |
| Broadcom Limited                      | 8        | 0.82%   |
| Edimax Technology                     | 7        | 0.72%   |
| ASUSTek Computer                      | 7        | 0.72%   |
| IMC Networks                          | 5        | 0.51%   |
| TRENDnet                              | 4        | 0.41%   |
| MediaTek                              | 4        | 0.41%   |
| Sagem                                 | 3        | 0.31%   |
| Gemtek                                | 3        | 0.31%   |
| Toshiba                               | 2        | 0.21%   |
| Marvell Technology Group              | 2        | 0.21%   |
| Linksys                               | 2        | 0.21%   |
| Fujitsu Siemens Computers             | 2        | 0.21%   |
| Accton Technology                     | 2        | 0.21%   |
| ZyDAS                                 | 1        | 0.1%    |
| Wilocity                              | 1        | 0.1%    |
| Tenda                                 | 1        | 0.1%    |
| Micro Star International              | 1        | 0.1%    |
| BUFFALO                               | 1        | 0.1%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                               | 80       | 8.15%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 27       | 2.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 27       | 2.75%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 24       | 2.45%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 23       | 2.34%   |
| Intel Wireless-AC 9260                                            | 23       | 2.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 22       | 2.24%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 22       | 2.24%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 21       | 2.14%   |
| Ralink MT7601U Wireless Adapter                                   | 18       | 1.83%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 18       | 1.83%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 17       | 1.73%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 16       | 1.63%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 15       | 1.53%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 15       | 1.53%   |
| Realtek 802.11ac NIC                                              | 15       | 1.53%   |
| Intel Wireless 3165                                               | 15       | 1.53%   |
| Intel Wireless 8260                                               | 13       | 1.33%   |
| Intel Wireless 7260                                               | 13       | 1.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 13       | 1.33%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 12       | 1.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 12       | 1.22%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 10       | 1.02%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 10       | 1.02%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter        | 10       | 1.02%   |
| NetGear A6210                                                     | 10       | 1.02%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 9        | 0.92%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 9        | 0.92%   |
| Realtek RTL8187 Wireless Adapter                                  | 9        | 0.92%   |
| Ralink RT5370 Wireless Adapter                                    | 9        | 0.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 9        | 0.92%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 9        | 0.92%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 8        | 0.82%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 8        | 0.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8        | 0.82%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]               | 8        | 0.82%   |
| Intel Wireless 8265 / 8275                                        | 8        | 0.82%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 7        | 0.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7        | 0.71%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 7        | 0.71%   |
| Qualcomm Atheros AR9271 802.11n                                   | 7        | 0.71%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                  | 7        | 0.71%   |
| NetGear WNA3100M(v1) Wireless-N 300 [Realtek RTL8192CU]           | 7        | 0.71%   |
| Intel Wireless 7265                                               | 7        | 0.71%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 7        | 0.71%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 7        | 0.71%   |
| TP-Link 802.11ac WLAN Adapter                                     | 6        | 0.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 6        | 0.61%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller         | 6        | 0.61%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 6        | 0.61%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 6        | 0.61%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 6        | 0.61%   |
| Microsoft XBOX ACC                                                | 6        | 0.61%   |
| Microsoft Xbox 360 Wireless Adapter                               | 6        | 0.61%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                            | 5        | 0.51%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 5        | 0.51%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 5        | 0.51%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 5        | 0.51%   |
| Guillemot Hercules HWNUm-300 Wireless N mini [Realtek RTL8191SU]  | 5        | 0.51%   |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W] | 5        | 0.51%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 1344     | 52.5%   |
| Intel                             | 720      | 28.13%  |
| Qualcomm Atheros                  | 136      | 5.31%   |
| Nvidia                            | 90       | 3.52%   |
| Broadcom                          | 67       | 2.62%   |
| Marvell Technology Group          | 59       | 2.3%    |
| Broadcom Limited                  | 21       | 0.82%   |
| VIA Technologies                  | 18       | 0.7%    |
| Samsung Electronics               | 18       | 0.7%    |
| D-Link System                     | 16       | 0.63%   |
| Aquantia                          | 11       | 0.43%   |
| Huawei Technologies               | 8        | 0.31%   |
| ASIX Electronics                  | 8        | 0.31%   |
| Xiaomi                            | 5        | 0.2%    |
| MediaTek                          | 5        | 0.2%    |
| Silicon Integrated Systems [SiS]  | 3        | 0.12%   |
| JMicron Technology                | 3        | 0.12%   |
| 3Com                              | 3        | 0.12%   |
| Qualcomm                          | 2        | 0.08%   |
| QLogic                            | 2        | 0.08%   |
| OnePlus Technology (Shenzhen)     | 2        | 0.08%   |
| Motorola PCS                      | 2        | 0.08%   |
| ICS Advent                        | 2        | 0.08%   |
| HTC (High Tech Computer)          | 2        | 0.08%   |
| Tehuti Networks                   | 1        | 0.04%   |
| Sundance Technology Inc / IC Plus | 1        | 0.04%   |
| NetGear                           | 1        | 0.04%   |
| Netchip Technology                | 1        | 0.04%   |
| National Semiconductor            | 1        | 0.04%   |
| Mellanox Technologies             | 1        | 0.04%   |
| Linksys                           | 1        | 0.04%   |
| Intellon                          | 1        | 0.04%   |
| IBM                               | 1        | 0.04%   |
| Google                            | 1        | 0.04%   |
| Foxconn / Hon Hai                 | 1        | 0.04%   |
| DisplayLink                       | 1        | 0.04%   |
| AMD                               | 1        | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 1168     | 44.11%  |
| Intel I211 Gigabit Network Connection                                         | 102      | 3.85%   |
| Intel Ethernet Connection (2) I219-V                                          | 98       | 3.7%    |
| Realtek RTL8125 2.5GbE Controller                                             | 80       | 3.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 73       | 2.76%   |
| Intel 82579V Gigabit Network Connection                                       | 59       | 2.23%   |
| Intel Ethernet Connection I217-LM                                             | 54       | 2.04%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 46       | 1.74%   |
| Nvidia MCP61 Ethernet                                                         | 45       | 1.7%    |
| Intel Ethernet Connection (7) I219-V                                          | 45       | 1.7%    |
| Intel Ethernet Connection (2) I218-V                                          | 40       | 1.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                     | 37       | 1.4%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 36       | 1.36%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                       | 33       | 1.25%   |
| Intel 82574L Gigabit Network Connection                                       | 33       | 1.25%   |
| Intel Ethernet Connection I217-V                                              | 31       | 1.17%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 30       | 1.13%   |
| Intel Ethernet Connection (2) I219-LM                                         | 29       | 1.1%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 24       | 0.91%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                      | 20       | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 20       | 0.76%   |
| Intel Ethernet Controller I225-V                                              | 18       | 0.68%   |
| VIA VT6102/VT6103 [Rhine-II]                                                  | 16       | 0.6%    |
| Samsung Galaxy series, misc. (tethering mode)                                 | 16       | 0.6%    |
| Intel I210 Gigabit Network Connection                                         | 16       | 0.6%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 14       | 0.53%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                               | 13       | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 12       | 0.45%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                             | 12       | 0.45%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                      | 11       | 0.42%   |
| Nvidia MCP77 Ethernet                                                         | 11       | 0.42%   |
| Nvidia CK804 Ethernet Controller                                              | 11       | 0.42%   |
| Intel Ethernet Connection (7) I219-LM                                         | 11       | 0.42%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                    | 10       | 0.38%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                       | 10       | 0.38%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                              | 10       | 0.38%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                       | 10       | 0.38%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 9        | 0.34%   |
| Intel 82566DM-2 Gigabit Network Connection                                    | 9        | 0.34%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                     | 8        | 0.3%    |
| Nvidia MCP73 Ethernet                                                         | 8        | 0.3%    |
| Intel NM10/ICH7 Family LAN Controller                                         | 8        | 0.3%    |
| Intel Ethernet Connection (5) I219-LM                                         | 8        | 0.3%    |
| ASIX AX88179 Gigabit Ethernet                                                 | 8        | 0.3%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]             | 8        | 0.3%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                               | 7        | 0.26%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                       | 6        | 0.23%   |
| Intel Ethernet Connection (11) I219-V                                         | 6        | 0.23%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 6        | 0.23%   |
| Intel 82567V-2 Gigabit Network Connection                                     | 6        | 0.23%   |
| Intel 82562V-2 10/100 Network Connection                                      | 6        | 0.23%   |
| Huawei MAR-LX1A                                                               | 6        | 0.23%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                             | 6        | 0.23%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                | 5        | 0.19%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                     | 5        | 0.19%   |
| Nvidia MCP55 Ethernet                                                         | 5        | 0.19%   |
| Intel I350 Gigabit Network Connection                                         | 5        | 0.19%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 5        | 0.19%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                               | 5        | 0.19%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                               | 5        | 0.19%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2367     | 71.1%   |
| WiFi     | 927      | 27.85%  |
| Modem    | 28       | 0.84%   |
| Unknown  | 7        | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1979     | 79.45%  |
| WiFi     | 512      | 20.55%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1606     | 66.83%  |
| 2     | 689      | 28.67%  |
| 3     | 73       | 3.04%   |
| 0     | 19       | 0.79%   |
| 4     | 9        | 0.37%   |
| 5     | 4        | 0.17%   |
| 6     | 2        | 0.08%   |
| 8     | 1        | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1710     | 69.57%  |
| Yes  | 748      | 30.43%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 208      | 34.9%   |
| Cambridge Silicon Radio         | 186      | 31.21%  |
| ASUSTek Computer                | 54       | 9.06%   |
| Broadcom                        | 30       | 5.03%   |
| Realtek Semiconductor           | 29       | 4.87%   |
| IMC Networks                    | 24       | 4.03%   |
| Qualcomm Atheros Communications | 19       | 3.19%   |
| Belkin Components               | 11       | 1.85%   |
| Apple                           | 9        | 1.51%   |
| Integrated System Solution      | 4        | 0.67%   |
| TP-Link                         | 3        | 0.5%    |
| HTC (High Tech Computer)        | 3        | 0.5%    |
| Foxconn / Hon Hai               | 3        | 0.5%    |
| Realtek                         | 2        | 0.34%   |
| Lite-On Technology              | 2        | 0.34%   |
| TRENDnet                        | 1        | 0.17%   |
| Micro Star International        | 1        | 0.17%   |
| Logitech                        | 1        | 0.17%   |
| Kensington                      | 1        | 0.17%   |
| Dell                            | 1        | 0.17%   |
| D-Link System                   | 1        | 0.17%   |
| Creative Technology             | 1        | 0.17%   |
| Conwise Technology              | 1        | 0.17%   |
| Com One                         | 1        | 0.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 186      | 31.21%  |
| Intel AX200 Bluetooth                                                | 72       | 12.08%  |
| Intel Bluetooth wireless interface                                   | 50       | 8.39%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 25       | 4.19%   |
| Realtek Bluetooth Radio                                              | 23       | 3.86%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 21       | 3.52%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 18       | 3.02%   |
| IMC Networks Bluetooth Radio                                         | 16       | 2.68%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 16       | 2.68%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 15       | 2.52%   |
| Intel AX201 Bluetooth                                                | 13       | 2.18%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 10       | 1.68%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 10       | 1.68%   |
| ASUS Bluetooth Adapter                                               | 8        | 1.34%   |
| ASUS BCM20702A0                                                      | 8        | 1.34%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 7        | 1.17%   |
| ASUS Bluetooth Radio                                                 | 7        | 1.17%   |
| Intel AX210 Bluetooth                                                | 6        | 1.01%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 5        | 0.84%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 4        | 0.67%   |
| TP-Link UB500 Adapter                                                | 3        | 0.5%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 3        | 0.5%    |
| Intel Centrino Bluetooth Wireless Transceiver                        | 3        | 0.5%    |
| IMC Networks Bluetooth Device                                        | 3        | 0.5%    |
| IMC Networks BCM20702A0                                              | 3        | 0.5%    |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 3        | 0.5%    |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                     | 3        | 0.5%    |
| ASUS ASUS USB-BT500                                                  | 3        | 0.5%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 3        | 0.5%    |
| Apple Bluetooth USB Host Controller                                  | 3        | 0.5%    |
| Realtek Bluetooth Radio                                              | 2        | 0.34%   |
| Qualcomm Atheros  Bluetooth Device                                   | 2        | 0.34%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                     | 2        | 0.34%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 2        | 0.34%   |
| Integrated System Solution Bluetooth Device                          | 2        | 0.34%   |
| IMC Networks Bluetooth Module                                        | 2        | 0.34%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 2        | 0.34%   |
| Broadcom HP Bluetooth Module                                         | 2        | 0.34%   |
| Broadcom BCM2045 Bluetooth                                           | 2        | 0.34%   |
| Belkin Components Bluetooth Mini Dongle                              | 2        | 0.34%   |
| ASUS Bluetooth Device                                                | 2        | 0.34%   |
| Apple Bluetooth HCI                                                  | 2        | 0.34%   |
| TRENDnet TBW-108UB USB Adapter                                       | 1        | 0.17%   |
| Realtek 802.11ac WLAN Adapter                                        | 1        | 0.17%   |
| Micro Star International Bluetooth Device                            | 1        | 0.17%   |
| Logitech Bluetooth wireless hub                                      | 1        | 0.17%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                         | 1        | 0.17%   |
| Lite-On Bluetooth Device                                             | 1        | 0.17%   |
| Kensington Bluetooth EDR Dongle                                      | 1        | 0.17%   |
| Intel Bluetooth Device                                               | 1        | 0.17%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                      | 1        | 0.17%   |
| Dell Wireless 365 Bluetooth                                          | 1        | 0.17%   |
| D-Link System DBT-122 Bluetooth                                      | 1        | 0.17%   |
| Creative Bluetooth Audio W2                                          | 1        | 0.17%   |
| Conwise CW6622                                                       | 1        | 0.17%   |
| Com One Bluetooth Device                                             | 1        | 0.17%   |
| Broadcom Bluetooth dongle                                            | 1        | 0.17%   |
| Broadcom Bluetooth 3.0+HS USB Adapter                                | 1        | 0.17%   |
| Broadcom Bluetooth 3.0 Device                                        | 1        | 0.17%   |
| Broadcom BCM43142 Bluetooth 4.0                                      | 1        | 0.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1489     | 36.58%  |
| Nvidia                           | 1067     | 26.22%  |
| AMD                              | 939      | 23.07%  |
| C-Media Electronics              | 103      | 2.53%   |
| Creative Labs                    | 63       | 1.55%   |
| Logitech                         | 57       | 1.4%    |
| VIA Technologies                 | 26       | 0.64%   |
| Texas Instruments                | 23       | 0.57%   |
| Corsair                          | 19       | 0.47%   |
| Kingston Technology              | 18       | 0.44%   |
| GN Netcom                        | 18       | 0.44%   |
| Sennheiser Communications        | 17       | 0.42%   |
| JMTek                            | 17       | 0.42%   |
| Plantronics                      | 15       | 0.37%   |
| Focusrite-Novation               | 15       | 0.37%   |
| Razer USA                        | 13       | 0.32%   |
| SteelSeries ApS                  | 12       | 0.29%   |
| Generalplus Technology           | 11       | 0.27%   |
| XMOS                             | 7        | 0.17%   |
| Creative Technology              | 7        | 0.17%   |
| Silicon Integrated Systems [SiS] | 6        | 0.15%   |
| ASUSTek Computer                 | 6        | 0.15%   |
| Turtle Beach                     | 5        | 0.12%   |
| Tenx Technology                  | 5        | 0.12%   |
| Sony                             | 5        | 0.12%   |
| M-Audio                          | 5        | 0.12%   |
| Ensoniq                          | 5        | 0.12%   |
| Yamaha                           | 4        | 0.1%    |
| Unknown                          | 4        | 0.1%    |
| RODE Microphones                 | 4        | 0.1%    |
| BEHRINGER International          | 4        | 0.1%    |
| Medeli Electronics               | 3        | 0.07%   |
| GYROCOM C&C                      | 3        | 0.07%   |
| Guillemot                        | 3        | 0.07%   |
| Dell                             | 3        | 0.07%   |
| AKAI Professional M.I.           | 3        | 0.07%   |
| Roland                           | 2        | 0.05%   |
| ROCCAT                           | 2        | 0.05%   |
| PreSonus Audio Electronics       | 2        | 0.05%   |
| Hewlett-Packard                  | 2        | 0.05%   |
| Giga-Byte Technology             | 2        | 0.05%   |
| Cambridge Silicon Radio          | 2        | 0.05%   |
| Bose                             | 2        | 0.05%   |
| Blue Microphones                 | 2        | 0.05%   |
| Audio-Technica                   | 2        | 0.05%   |
| ATI Technologies                 | 2        | 0.05%   |
| Astro Gaming                     | 2        | 0.05%   |
| Alesis                           | 2        | 0.05%   |
| ZOOM                             | 1        | 0.02%   |
| Xilinx                           | 1        | 0.02%   |
| www.hirestech.com 2013 Rev 1.3   | 1        | 0.02%   |
| Valve Software                   | 1        | 0.02%   |
| USB MICROPHONE                   | 1        | 0.02%   |
| ULi Electronics                  | 1        | 0.02%   |
| TerraTec Electronic              | 1        | 0.02%   |
| SGM                              | 1        | 0.02%   |
| SAVITECH                         | 1        | 0.02%   |
| Samson Technologies              | 1        | 0.02%   |
| Realtek Semiconductor            | 1        | 0.02%   |
| Qualcomm                         | 1        | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 228      | 4.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 194      | 4.2%    |
| AMD Starship/Matisse HD Audio Controller                                          | 175      | 3.79%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 173      | 3.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 151      | 3.27%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 139      | 3.01%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 133      | 2.88%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 130      | 2.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 119      | 2.58%   |
| Intel 200 Series PCH HD Audio                                                     | 106      | 2.3%    |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 102      | 2.21%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 98       | 2.12%   |
| Nvidia High Definition Audio Controller                                           | 78       | 1.69%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 77       | 1.67%   |
| AMD Family 17h/19h HD Audio Controller                                            | 77       | 1.67%   |
| Intel Cannon Lake PCH cAVS                                                        | 76       | 1.65%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 76       | 1.65%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 75       | 1.62%   |
| AMD FCH Azalia Controller                                                         | 75       | 1.62%   |
| Nvidia GP106 High Definition Audio Controller                                     | 62       | 1.34%   |
| Nvidia MCP61 High Definition Audio                                                | 59       | 1.28%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 57       | 1.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 53       | 1.15%   |
| Nvidia GP104 High Definition Audio Controller                                     | 51       | 1.1%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 51       | 1.1%    |
| Nvidia GK104 HDMI Audio Controller                                                | 47       | 1.02%   |
| Nvidia GM204 High Definition Audio Controller                                     | 45       | 0.97%   |
| Nvidia GF119 HDMI Audio Controller                                                | 45       | 0.97%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 44       | 0.95%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 41       | 0.89%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 41       | 0.89%   |
| Nvidia GM206 High Definition Audio Controller                                     | 39       | 0.84%   |
| Nvidia GK107 HDMI Audio Controller                                                | 39       | 0.84%   |
| Nvidia GF108 High Definition Audio Controller                                     | 39       | 0.84%   |
| AMD Navi 10 HDMI Audio                                                            | 38       | 0.82%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 38       | 0.82%   |
| Nvidia TU106 High Definition Audio Controller                                     | 37       | 0.8%    |
| Nvidia GP108 High Definition Audio Controller                                     | 37       | 0.8%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 34       | 0.74%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 31       | 0.67%   |
| Nvidia TU116 High Definition Audio Controller                                     | 30       | 0.65%   |
| Nvidia TU104 HD Audio Controller                                                  | 30       | 0.65%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 30       | 0.65%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 27       | 0.58%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 27       | 0.58%   |
| Nvidia GK106 HDMI Audio Controller                                                | 26       | 0.56%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 26       | 0.56%   |
| Intel Comet Lake PCH cAVS                                                         | 21       | 0.45%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                     | 21       | 0.45%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                    | 20       | 0.43%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                     | 19       | 0.41%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 19       | 0.41%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 19       | 0.41%   |
| Nvidia GA102 High Definition Audio Controller                                     | 18       | 0.39%   |
| AMD Trinity HDMI Audio Controller                                                 | 17       | 0.37%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                             | 17       | 0.37%   |
| Nvidia GT216 HDMI Audio Controller                                                | 16       | 0.35%   |
| Nvidia GA104 High Definition Audio Controller                                     | 16       | 0.35%   |
| Kingston Technology HyperX 7.1 Audio                                              | 16       | 0.35%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 16       | 0.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 289      | 17.75%  |
| Kingston            | 257      | 15.79%  |
| Corsair             | 248      | 15.23%  |
| G.Skill             | 172      | 10.57%  |
| Crucial             | 147      | 9.03%   |
| Samsung Electronics | 145      | 8.91%   |
| SK Hynix            | 139      | 8.54%   |
| Micron Technology   | 81       | 4.98%   |
| Nanya Technology    | 28       | 1.72%   |
| Elpida              | 15       | 0.92%   |
| Transcend           | 10       | 0.61%   |
| Team                | 10       | 0.61%   |
| Ramaxel Technology  | 10       | 0.61%   |
| Patriot             | 9        | 0.55%   |
| PNY                 | 8        | 0.49%   |
| A-DATA Technology   | 7        | 0.43%   |
| Unifosa             | 6        | 0.37%   |
| Unknown (ABCD)      | 5        | 0.31%   |
| Qimonda             | 5        | 0.31%   |
| Unknown             | 5        | 0.31%   |
| OCZ                 | 3        | 0.18%   |
| Toshiba             | 2        | 0.12%   |
| TIMETEC             | 2        | 0.12%   |
| Swissbit            | 2        | 0.12%   |
| Hewlett-Packard     | 2        | 0.12%   |
| Unknown (0x0C97)    | 1        | 0.06%   |
| Unknown (07FB)      | 1        | 0.06%   |
| Textorm             | 1        | 0.06%   |
| TakeMS              | 1        | 0.06%   |
| Silicon Power       | 1        | 0.06%   |
| Sesame              | 1        | 0.06%   |
| Ramos Technology    | 1        | 0.06%   |
| Patriot Memory      | 1        | 0.06%   |
| M                   | 1        | 0.06%   |
| Kreton              | 1        | 0.06%   |
| Klevv               | 1        | 0.06%   |
| Innodisk            | 1        | 0.06%   |
| Infineon            | 1        | 0.06%   |
| HPE                 | 1        | 0.06%   |
| H                   | 1        | 0.06%   |
| GeIL                | 1        | 0.06%   |
| Avant               | 1        | 0.06%   |
| Atermiter           | 1        | 0.06%   |
| ASint Technology    | 1        | 0.06%   |
| Apacer              | 1        | 0.06%   |
| A Force             | 1        | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 17       | 0.95%   |
| Kingston RAM KHX1600C9D3/4GX 4096MB DIMM DDR3 2400MT/s         | 16       | 0.9%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 12       | 0.67%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 12       | 0.67%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s          | 11       | 0.62%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                        | 10       | 0.56%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 10       | 0.56%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 8        | 0.45%   |
| Unknown RAM Module 4096MB DIMM DDR 1333MT/s                    | 8        | 0.45%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 8        | 0.45%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                         | 8        | 0.45%   |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 8        | 0.45%   |
| SK Hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2465MT/s           | 8        | 0.45%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s            | 8        | 0.45%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s            | 8        | 0.45%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s            | 8        | 0.45%   |
| G.Skill RAM F3-12800CL9-4GBXL 4GB DIMM DDR3 1867MT/s           | 8        | 0.45%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 7        | 0.39%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                    | 7        | 0.39%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                    | 7        | 0.39%   |
| SK Hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 7        | 0.39%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s        | 7        | 0.39%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s        | 7        | 0.39%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s            | 7        | 0.39%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s            | 7        | 0.39%   |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1600MT/s            | 7        | 0.39%   |
| Corsair RAM CMK16GX4M2Z3200C16 8192MB DIMM DDR4 3200MT/s       | 7        | 0.39%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s          | 7        | 0.39%   |
| Unknown RAM Module 1024MB DIMM DDR2                            | 6        | 0.34%   |
| Unknown RAM Module 1024MB DIMM                                 | 6        | 0.34%   |
| SK Hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s           | 6        | 0.34%   |
| Samsung RAM M378B5673EH1-CH9 2048MB DIMM DDR3 1333MT/s         | 6        | 0.34%   |
| Samsung RAM M3 78T5663EH3-CF7 2GB DIMM DDR2 800MT/s            | 6        | 0.34%   |
| Crucial RAM CT51264BD160B.C16F 4096MB DIMM DDR3 1600MT/s       | 6        | 0.34%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s         | 6        | 0.34%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3200MT/s          | 6        | 0.34%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 5        | 0.28%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 5        | 0.28%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                        | 5        | 0.28%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 5        | 0.28%   |
| Unknown RAM Module 2048MB DIMM SDRAM                           | 5        | 0.28%   |
| Unknown RAM Module 2048MB DIMM DDR3 1066MT/s                   | 5        | 0.28%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                     | 5        | 0.28%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                    | 5        | 0.28%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 5        | 0.28%   |
| SK Hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s            | 5        | 0.28%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s            | 5        | 0.28%   |
| Samsung RAM M378B5273CH0-CH9 4096MB DIMM 1867MT/s              | 5        | 0.28%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s            | 5        | 0.28%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s            | 5        | 0.28%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s             | 5        | 0.28%   |
| Micron RAM 8JTF51264AZ-1G6E1 4096MB DIMM DDR3 1600MT/s         | 5        | 0.28%   |
| Micron RAM 8JTF25664AZ-1G6M1 2GB DIMM DDR3 1600MT/s            | 5        | 0.28%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3533MT/s        | 5        | 0.28%   |
| Kingston RAM KHX2400C15D4/4G 4096MB DIMM DDR4 3151MT/s         | 5        | 0.28%   |
| Kingston RAM KHX2400C15/8G 8192MB DIMM DDR4 2933MT/s           | 5        | 0.28%   |
| Kingston RAM KHX1866C10D3/4G 4096MB DIMM DDR3 1867MT/s         | 5        | 0.28%   |
| Kingston RAM KHX1600C10D3/8G 4096MB DIMM DDR3 1600MT/s         | 5        | 0.28%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s            | 5        | 0.28%   |
| Kingston RAM 99U5584-005.A00LF 4096MB DIMM DDR3 1600MT/s       | 5        | 0.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 552      | 38.44%  |
| DDR4    | 532      | 37.05%  |
| DDR2    | 124      | 8.64%   |
| Unknown | 103      | 7.17%   |
| SDRAM   | 78       | 5.43%   |
| DDR     | 39       | 2.72%   |
| LPDDR4  | 7        | 0.49%   |
| DRAM    | 1        | 0.07%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 1339     | 94.96%  |
| SODIMM  | 63       | 4.47%   |
| FB-DIMM | 5        | 0.35%   |
| RIMM    | 3        | 0.21%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 502      | 31.83%  |
| 4096  | 462      | 29.3%   |
| 2048  | 290      | 18.39%  |
| 16384 | 152      | 9.64%   |
| 1024  | 127      | 8.05%   |
| 512   | 26       | 1.65%   |
| 32768 | 16       | 1.01%   |
| 256   | 2        | 0.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 313      | 20%     |
| 1333    | 201      | 12.84%  |
| 3200    | 133      | 8.5%    |
| 2400    | 101      | 6.45%   |
| 800     | 90       | 5.75%   |
| 2133    | 85       | 5.43%   |
| 2667    | 71       | 4.54%   |
| 667     | 64       | 4.09%   |
| 3600    | 59       | 3.77%   |
| 1066    | 43       | 2.75%   |
| Unknown | 40       | 2.56%   |
| 1867    | 36       | 2.3%    |
| 3466    | 30       | 1.92%   |
| 2666    | 24       | 1.53%   |
| 2933    | 23       | 1.47%   |
| 3000    | 22       | 1.41%   |
| 1866    | 22       | 1.41%   |
| 1800    | 18       | 1.15%   |
| 400     | 17       | 1.09%   |
| 2048    | 11       | 0.7%    |
| 1067    | 11       | 0.7%    |
| 533     | 11       | 0.7%    |
| 2800    | 10       | 0.64%   |
| 333     | 9        | 0.58%   |
| 3400    | 8        | 0.51%   |
| 2465    | 8        | 0.51%   |
| 1334    | 8        | 0.51%   |
| 3800    | 7        | 0.45%   |
| 3733    | 7        | 0.45%   |
| 3266    | 7        | 0.45%   |
| 1639    | 7        | 0.45%   |
| 3533    | 6        | 0.38%   |
| 3100    | 6        | 0.38%   |
| 3151    | 5        | 0.32%   |
| 1400    | 5        | 0.32%   |
| 2733    | 4        | 0.26%   |
| 49926   | 3        | 0.19%   |
| 3666    | 3        | 0.19%   |
| 3007    | 3        | 0.19%   |
| 2473    | 3        | 0.19%   |
| 2134    | 3        | 0.19%   |
| 266     | 3        | 0.19%   |
| 52217   | 2        | 0.13%   |
| 3334    | 2        | 0.13%   |
| 3333    | 2        | 0.13%   |
| 3066    | 2        | 0.13%   |
| 2200    | 2        | 0.13%   |
| 2000    | 2        | 0.13%   |
| 4800    | 1        | 0.06%   |
| 4333    | 1        | 0.06%   |
| 4266    | 1        | 0.06%   |
| 3500    | 1        | 0.06%   |
| 3001    | 1        | 0.06%   |
| 2747    | 1        | 0.06%   |
| 2448    | 1        | 0.06%   |
| 2197    | 1        | 0.06%   |
| 1872    | 1        | 0.06%   |
| 880     | 1        | 0.06%   |
| 666     | 1        | 0.06%   |
| 200     | 1        | 0.06%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 75       | 49.67%  |
| Canon               | 21       | 13.91%  |
| Samsung Electronics | 19       | 12.58%  |
| Brother Industries  | 18       | 11.92%  |
| Seiko Epson         | 11       | 7.28%   |
| Prolific Technology | 2        | 1.32%   |
| Xerox               | 1        | 0.66%   |
| STMicroelectronics  | 1        | 0.66%   |
| Ricoh               | 1        | 0.66%   |
| QinHeng Electronics | 1        | 0.66%   |
| Kyocera             | 1        | 0.66%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| HP ENVY 4520 series                                        | 7        | 4.61%   |
| HP DeskJet 3630 series                                     | 6        | 3.95%   |
| Samsung M2070 Series                                       | 5        | 3.29%   |
| HP ENVY Photo 6200 series                                  | 5        | 3.29%   |
| HP DeskJet 2700 series                                     | 5        | 3.29%   |
| Seiko Epson XP-243 245 247 Series                          | 3        | 1.97%   |
| HP ENVY 5000 series                                        | 3        | 1.97%   |
| HP DeskJet Plus 4100 series                                | 3        | 1.97%   |
| HP DeskJet 3700 series                                     | 3        | 1.97%   |
| HP Deskjet 3050A                                           | 3        | 1.97%   |
| Canon PIXMA MG3600 Series                                  | 3        | 1.97%   |
| Brother HL-2030 Laser Printer                              | 3        | 1.97%   |
| Seiko Epson XP-2100 Series                                 | 2        | 1.32%   |
| Samsung M2020 Series                                       | 2        | 1.32%   |
| Samsung CLX-3180 Series                                    | 2        | 1.32%   |
| Samsung CLX-3170 Series                                    | 2        | 1.32%   |
| Prolific PL2305 Parallel Port                              | 2        | 1.32%   |
| HP OfficeJet 3830 series                                   | 2        | 1.32%   |
| HP DeskJet F4200 series                                    | 2        | 1.32%   |
| HP DeskJet 5550                                            | 2        | 1.32%   |
| HP DeskJet 2620 All-in-One Printer                         | 2        | 1.32%   |
| HP Deskjet 1510                                            | 2        | 1.32%   |
| Canon iP7200 series                                        | 2        | 1.32%   |
| Brother Printer                                            | 2        | 1.32%   |
| Brother HL-L2350DW series                                  | 2        | 1.32%   |
| Xerox ColorQube 8580DN                                     | 1        | 0.66%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44  | 1        | 0.66%   |
| Seiko Epson XP-255 257 Series                              | 1        | 0.66%   |
| Seiko Epson WF-2510 Series                                 | 1        | 0.66%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]               | 1        | 0.66%   |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 1        | 0.66%   |
| Seiko Epson ET-2720 Series                                 | 1        | 0.66%   |
| Seiko Epson AcuLaser CX17NF                                | 1        | 0.66%   |
| Samsung SCX-3400 Series                                    | 1        | 0.66%   |
| Samsung SCX-3200 Series                                    | 1        | 0.66%   |
| Samsung ML-216x Series Laser Printer                       | 1        | 0.66%   |
| Samsung ML-1660 Series                                     | 1        | 0.66%   |
| Samsung ML-1630 Series                                     | 1        | 0.66%   |
| Samsung M288x Series                                       | 1        | 0.66%   |
| Samsung CLP-300 Series                                     | 1        | 0.66%   |
| Samsung C48x Series Color Laser Multifunction Printer      | 1        | 0.66%   |
| Ricoh SP 211                                               | 1        | 0.66%   |
| QinHeng CH340S                                             | 1        | 0.66%   |
| Kyocera FS-1370DN                                          | 1        | 0.66%   |
| HP Printing Support                                        | 1        | 0.66%   |
| HP Officejet Pro 8100                                      | 1        | 0.66%   |
| HP OfficeJet Pro 6960                                      | 1        | 0.66%   |
| HP OfficeJet Pro 69                                        | 1        | 0.66%   |
| HP OfficeJet 5200 series                                   | 1        | 0.66%   |
| HP Officejet 4500 G510n-z                                  | 1        | 0.66%   |
| HP LaserJet Pro M12w                                       | 1        | 0.66%   |
| HP LaserJet P2055 series                                   | 1        | 0.66%   |
| HP LaserJet P2014                                          | 1        | 0.66%   |
| HP LaserJet M203-M206                                      | 1        | 0.66%   |
| HP LaserJet 200 colorMFP M276nw                            | 1        | 0.66%   |
| HP LaserJet 1200                                           | 1        | 0.66%   |
| HP LaserJet 1022                                           | 1        | 0.66%   |
| HP ENVY Pro 6400 series                                    | 1        | 0.66%   |
| HP ENVY Photo 7800 series                                  | 1        | 0.66%   |
| HP ENVY Photo 7100 series                                  | 1        | 0.66%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 34       | 65.38%  |
| Seiko Epson     | 9        | 17.31%  |
| Hewlett-Packard | 7        | 13.46%  |
| AGFA-Gevaert NV | 2        | 3.85%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20                          | 6        | 11.54%  |
| Canon CanoScan N1240U/LiDE 30                               | 6        | 11.54%  |
| Canon CanoScan LiDE 110                                     | 5        | 9.62%   |
| Seiko Epson GT-X770 [Perfection V500]                       | 4        | 7.69%   |
| Canon CanoScan LIDE 25                                      | 4        | 7.69%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                      | 3        | 5.77%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]     | 2        | 3.85%   |
| Canon CanoScan LiDE 220                                     | 2        | 3.85%   |
| Canon CanoScan LiDE 210                                     | 2        | 3.85%   |
| Seiko Epson GT-F600 [Perfection 4180]                       | 1        | 1.92%   |
| Seiko Epson GT-9800F [Perfection 3200]                      | 1        | 1.92%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO] | 1        | 1.92%   |
| HP ScanJet G4010                                            | 1        | 1.92%   |
| HP ScanJet 5200c                                            | 1        | 1.92%   |
| HP ScanJet 4570c                                            | 1        | 1.92%   |
| HP ScanJet 3570c                                            | 1        | 1.92%   |
| HP ScanJet 3500c                                            | 1        | 1.92%   |
| HP ScanJet 2300c                                            | 1        | 1.92%   |
| HP PSC 1200                                                 | 1        | 1.92%   |
| Canon CanoScan LiDE 60                                      | 1        | 1.92%   |
| Canon CanoScan LiDE 200                                     | 1        | 1.92%   |
| Canon CanoScan LiDE 120                                     | 1        | 1.92%   |
| Canon CanoScan 9000F Mark II                                | 1        | 1.92%   |
| Canon CanoScan 4400F                                        | 1        | 1.92%   |
| Canon CanoScan 4200F                                        | 1        | 1.92%   |
| AGFA-Gevaert NV SnapScan e20                                | 1        | 1.92%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                          | 1        | 1.92%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 200      | 45.87%  |
| Microsoft                     | 31       | 7.11%   |
| Microdia                      | 26       | 5.96%   |
| Samsung Electronics           | 22       | 5.05%   |
| Sunplus Innovation Technology | 14       | 3.21%   |
| Guillemot                     | 12       | 2.75%   |
| Chicony Electronics           | 10       | 2.29%   |
| Generalplus Technology        | 9        | 2.06%   |
| Realtek Semiconductor         | 8        | 1.83%   |
| Sonix Technology              | 7        | 1.61%   |
| Hewlett-Packard               | 7        | 1.61%   |
| GEMBIRD                       | 7        | 1.61%   |
| Apple                         | 7        | 1.61%   |
| KYE Systems (Mouse Systems)   | 6        | 1.38%   |
| Creative Technology           | 6        | 1.38%   |
| ARC International             | 6        | 1.38%   |
| Cubeternet                    | 5        | 1.15%   |
| 2M UVC CAMERA                 | 5        | 1.15%   |
| WaveRider Communications      | 3        | 0.69%   |
| Sunplus IT                    | 3        | 0.69%   |
| Arkmicro Technologies         | 3        | 0.69%   |
| Z-Star Microelectronics       | 2        | 0.46%   |
| Razer USA                     | 2        | 0.46%   |
| Philips (or NXP)              | 2        | 0.46%   |
| MacroSilicon                  | 2        | 0.46%   |
| Jieli Technology              | 2        | 0.46%   |
| Huawei Technologies           | 2        | 0.46%   |
| Genesys Logic                 | 2        | 0.46%   |
| AVerMedia Technologies        | 2        | 0.46%   |
| Alcor Micro                   | 2        | 0.46%   |
| YGTek                         | 1        | 0.23%   |
| Yealink Network Technology    | 1        | 0.23%   |
| Xiongmai                      | 1        | 0.23%   |
| Xiaomi                        | 1        | 0.23%   |
| WCM_USB                       | 1        | 0.23%   |
| Valve Software                | 1        | 0.23%   |
| Trust                         | 1        | 0.23%   |
| Teslong Camera                | 1        | 0.23%   |
| Syntek                        | 1        | 0.23%   |
| Suyin                         | 1        | 0.23%   |
| SunplusIT                     | 1        | 0.23%   |
| Silicon Motion                | 1        | 0.23%   |
| SHENZHEN AONI ELECTRONIC      | 1        | 0.23%   |
| Sanyo Electric                | 1        | 0.23%   |
| PrehKeyTec                    | 1        | 0.23%   |
| Nokia Mobile Phones           | 1        | 0.23%   |
| Linux Foundation              | 1        | 0.23%   |
| Canon                         | 1        | 0.23%   |
| Brother Industries            | 1        | 0.23%   |
| Aveo Technology               | 1        | 0.23%   |
| 4K USB CAMERA                 | 1        | 0.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 40       | 9.17%   |
| Samsung Galaxy A5 (MTP)                           | 22       | 5.05%   |
| Logitech HD Pro Webcam C920                       | 22       | 5.05%   |
| Logitech HD Webcam C525                           | 20       | 4.59%   |
| Microsoft LifeCam HD-3000                         | 10       | 2.29%   |
| Logitech Webcam C310                              | 10       | 2.29%   |
| Logitech Webcam C170                              | 10       | 2.29%   |
| Logitech C922 Pro Stream Webcam                   | 10       | 2.29%   |
| Microdia Webcam Vitade AF                         | 7        | 1.61%   |
| Guillemot Hercules HD Twist                       | 7        | 1.61%   |
| Apple iPhone 5/5C/5S/6/SE                         | 7        | 1.61%   |
| Microdia Camera                                   | 6        | 1.38%   |
| Logitech HD Webcam C910                           | 6        | 1.38%   |
| Logitech HD Webcam C615                           | 6        | 1.38%   |
| ARC International Camera                          | 6        | 1.38%   |
| Sonix USB Camera                                  | 5        | 1.15%   |
| Realtek Full HD webcam                            | 5        | 1.15%   |
| Logitech Webcam C300                              | 5        | 1.15%   |
| Logitech BRIO Ultra HD Webcam                     | 5        | 1.15%   |
| HP Webcam HD 4310                                 | 5        | 1.15%   |
| Generalplus 808 Camera                            | 5        | 1.15%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 5        | 1.15%   |
| 2M UVC CAMERA Web Camera                          | 5        | 1.15%   |
| Sunplus Canyon CNS-CWC5 Webcam                    | 4        | 0.92%   |
| Microsoft LifeCam VX-5000                         | 4        | 0.92%   |
| Microsoft LifeCam Cinema                          | 4        | 0.92%   |
| Microdia USB 2.0 Camera                           | 4        | 0.92%   |
| Microdia Sonix USB 2.0 Camera                     | 4        | 0.92%   |
| Logitech Webcam Pro 9000                          | 4        | 0.92%   |
| Logitech Webcam C930e                             | 4        | 0.92%   |
| Logitech Webcam C200                              | 4        | 0.92%   |
| Logitech StreamCam                                | 4        | 0.92%   |
| Logitech QuickCam Pro 9000                        | 4        | 0.92%   |
| Logitech QuickCam Pro 4000                        | 4        | 0.92%   |
| Logitech B525 HD Webcam                           | 4        | 0.92%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera        | 4        | 0.92%   |
| Generalplus CAMERA - UVC                          | 4        | 0.92%   |
| Cubeternet USB2.0 Camera                          | 4        | 0.92%   |
| WaveRider USB 2.0 Camera                          | 3        | 0.69%   |
| Sunplus IT AUKEY PC-LM1 USB Camera                | 3        | 0.69%   |
| Sunplus Canyon CNS CWC5 Webcam                    | 3        | 0.69%   |
| Microsoft LifeCam HD-5000                         | 3        | 0.69%   |
| Microdia Integrated Camera                        | 3        | 0.69%   |
| Logitech Webcam C210                              | 3        | 0.69%   |
| Logitech QuickCam Pro 5000                        | 3        | 0.69%   |
| Logitech Logitech Webcam C100                     | 3        | 0.69%   |
| Logitech C920 PRO HD Webcam                       | 3        | 0.69%   |
| Logitech BRIO 4K Stream Edition                   | 3        | 0.69%   |
| Arkmicro USB2.0 PC CAMERA                         | 3        | 0.69%   |
| Sunplus Aukey-PC-LM1E Camera                      | 2        | 0.46%   |
| Razer USA Gaming Webcam [Kiyo]                    | 2        | 0.46%   |
| Microsoft Xbox NUI Camera                         | 2        | 0.46%   |
| Microsoft MicrosoftÃ‚ LifeCam VX-5500          | 2        | 0.46%   |
| Microsoft LifeCam VX-2000                         | 2        | 0.46%   |
| Logitech Webcam C250                              | 2        | 0.46%   |
| Jieli USB PHY 2.0                                 | 2        | 0.46%   |
| Huawei UVC Camera                                 | 2        | 0.46%   |
| HP Webcam HD 2300                                 | 2        | 0.46%   |
| Guillemot Hercules HD Sunset                      | 2        | 0.46%   |
| Guillemot Hercules Dualpix Exchange               | 2        | 0.46%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Validity Sensors           | 1        | 20%     |
| Synaptics                  | 1        | 20%     |
| Shenzhen Goodix Technology | 1        | 20%     |
| Elan Microelectronics      | 1        | 20%     |
| AuthenTec                  | 1        | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1        | 20%     |
| Synaptics  WBDI Fingerprint Reader - USB 052                | 1        | 20%     |
| Shenzhen Goodix  Fingerprint Device                         | 1        | 20%     |
| Elan fingerprint sensor [FeinTech FPS00200]                 | 1        | 20%     |
| AuthenTec AES2501 Fingerprint Sensor                        | 1        | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Hewlett-Packard           | 4        | 22.22%  |
| Gemalto (was Gemplus)     | 4        | 22.22%  |
| SCM Microsystems          | 2        | 11.11%  |
| ST-Ericsson               | 1        | 5.56%   |
| Realtek Semiconductor     | 1        | 5.56%   |
| Feitian Technologies      | 1        | 5.56%   |
| Chicony Electronics       | 1        | 5.56%   |
| Cherry                    | 1        | 5.56%   |
| Alcor Micro               | 1        | 5.56%   |
| Aladdin Knowledge Systems | 1        | 5.56%   |
| Advanced Card Systems     | 1        | 5.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Hewlett-Packard SC Keyboard - Apollo (Liteon)        | 4        | 22.22%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader    | 3        | 16.67%  |
| ST-Ericsson Chipcard Reader                          | 1        | 5.56%   |
| SCM Microsystems SCR335 SmartCard Reader             | 1        | 5.56%   |
| SCM Microsystems CLOUD 2700 F Smart Card Reader      | 1        | 5.56%   |
| Realtek Semiconductor Smart Card Reader Interface    | 1        | 5.56%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader     | 1        | 5.56%   |
| Feitian Technologies FT SCR310                       | 1        | 5.56%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard | 1        | 5.56%   |
| Cherry Cherry GmbH CHERRY SECURE BOARD 1.0           | 1        | 5.56%   |
| Alcor Micro Watchdata W 1981                         | 1        | 5.56%   |
| Aladdin Knowledge Systems Token JC                   | 1        | 5.56%   |
| Advanced Card Systems ACR122U                        | 1        | 5.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 2096     | 86.18%  |
| 1     | 279      | 11.47%  |
| 2     | 44       | 1.81%   |
| 4     | 7        | 0.29%   |
| 3     | 4        | 0.16%   |
| 5     | 2        | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 147      | 37.6%   |
| Net/wireless             | 80       | 20.46%  |
| Communication controller | 38       | 9.72%   |
| Unassigned class         | 32       | 8.18%   |
| Multimedia controller    | 16       | 4.09%   |
| Sound                    | 15       | 3.84%   |
| Net/ethernet             | 9        | 2.3%    |
| Chipcard                 | 9        | 2.3%    |
| Bluetooth                | 8        | 2.05%   |
| Camera                   | 6        | 1.53%   |
| Storage/raid             | 5        | 1.28%   |
| Network                  | 5        | 1.28%   |
| Card reader              | 5        | 1.28%   |
| Modem                    | 4        | 1.02%   |
| Firewire controller      | 4        | 1.02%   |
| Fingerprint reader       | 4        | 1.02%   |
| Storage/ide              | 3        | 0.77%   |
| Tv card                  | 1        | 0.26%   |

