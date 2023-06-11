Linux in Czechia - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Czechia.

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

Total: 963

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | X99-UD4-CF                  | [a2c63b86b0](https://linux-hardware.org/?probe=a2c63b86b0) | Jun 08, 2023 |
| MSI           | H110M ECO                   | [4215fc5993](https://linux-hardware.org/?probe=4215fc5993) | Jun 05, 2023 |
| Gigabyte      | B360M HD3                   | [fcb1b60578](https://linux-hardware.org/?probe=fcb1b60578) | Jun 04, 2023 |
| MSI           | GF615M-P33                  | [84f237f434](https://linux-hardware.org/?probe=84f237f434) | Jun 04, 2023 |
| Acer          | Veriton M2631 V:1.0         | [e64369d2ec](https://linux-hardware.org/?probe=e64369d2ec) | Jun 03, 2023 |
| Gigabyte      | H67MA-USB3-B3               | [1908e7e6f5](https://linux-hardware.org/?probe=1908e7e6f5) | Jun 03, 2023 |
| HP            | 158A                        | [39d4ab7307](https://linux-hardware.org/?probe=39d4ab7307) | May 31, 2023 |
| ASRock        | B550M Steel Legend          | [ab97cb7f09](https://linux-hardware.org/?probe=ab97cb7f09) | May 30, 2023 |
| Gigabyte      | X399 AORUS PRO-CF           | [b00cd1c84e](https://linux-hardware.org/?probe=b00cd1c84e) | May 30, 2023 |
| Gigabyte      | Z690 UD                     | [feab206ef4](https://linux-hardware.org/?probe=feab206ef4) | May 29, 2023 |
| ASRock        | X670E Taichi Carrara        | [7b001db11a](https://linux-hardware.org/?probe=7b001db11a) | May 29, 2023 |
| HP            | 1495                        | [200cab3da9](https://linux-hardware.org/?probe=200cab3da9) | May 23, 2023 |
| Lenovo        | 36C8 SDK0J40700 WIN 3258... | [7e8b42ab5f](https://linux-hardware.org/?probe=7e8b42ab5f) | May 22, 2023 |
| HP            | 2B5E                        | [a221629f4d](https://linux-hardware.org/?probe=a221629f4d) | May 21, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [5da7add39a](https://linux-hardware.org/?probe=5da7add39a) | May 20, 2023 |
| MSI           | GF615M-P33                  | [09ae9aca26](https://linux-hardware.org/?probe=09ae9aca26) | May 19, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [c3626b71ae](https://linux-hardware.org/?probe=c3626b71ae) | May 18, 2023 |
| Lenovo        | 36C8 SDK0J40700 WIN 3258... | [166ec29ce0](https://linux-hardware.org/?probe=166ec29ce0) | May 18, 2023 |
| MSI           | MAG B760M MORTAR WIFI       | [f7c208d0f0](https://linux-hardware.org/?probe=f7c208d0f0) | May 16, 2023 |
| Gigabyte      | H410M H V2                  | [1effa68567](https://linux-hardware.org/?probe=1effa68567) | May 15, 2023 |
| Lenovo        | NOK                         | [9c6f0bae8f](https://linux-hardware.org/?probe=9c6f0bae8f) | May 14, 2023 |
| MSI           | H81M-P33                    | [b5c0679341](https://linux-hardware.org/?probe=b5c0679341) | May 08, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [b979325eea](https://linux-hardware.org/?probe=b979325eea) | May 07, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | [701907636a](https://linux-hardware.org/?probe=701907636a) | May 06, 2023 |
| ASUSTek       | P8Z68 DELUXE/GEN3           | [288e495c16](https://linux-hardware.org/?probe=288e495c16) | May 06, 2023 |
| Gigabyte      | B660M DS3H DDR4             | [ab48e66c38](https://linux-hardware.org/?probe=ab48e66c38) | May 01, 2023 |
| Gigabyte      | B660M DS3H DDR4             | [0e035d415e](https://linux-hardware.org/?probe=0e035d415e) | May 01, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [e0367e684f](https://linux-hardware.org/?probe=e0367e684f) | Apr 28, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [fed0a1a719](https://linux-hardware.org/?probe=fed0a1a719) | Apr 28, 2023 |
| Lenovo        | NOK                         | [cf3db26781](https://linux-hardware.org/?probe=cf3db26781) | Apr 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [92be2563a8](https://linux-hardware.org/?probe=92be2563a8) | Apr 28, 2023 |
| ASUSTek       | P5G41T-M LX                 | [68d1859c93](https://linux-hardware.org/?probe=68d1859c93) | Apr 23, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [1cc955413f](https://linux-hardware.org/?probe=1cc955413f) | Apr 23, 2023 |
| Pegatron      | 2AB5                        | [5f771d8ee5](https://linux-hardware.org/?probe=5f771d8ee5) | Apr 23, 2023 |
| Gigabyte      | Z97X-Gaming 3               | [085b87dc27](https://linux-hardware.org/?probe=085b87dc27) | Apr 21, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [42ca23ca64](https://linux-hardware.org/?probe=42ca23ca64) | Apr 20, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [e315ba7088](https://linux-hardware.org/?probe=e315ba7088) | Apr 20, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [ec0b554256](https://linux-hardware.org/?probe=ec0b554256) | Apr 19, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [980c6d63d6](https://linux-hardware.org/?probe=980c6d63d6) | Apr 16, 2023 |
| Gigabyte      | AX370-Gaming K7 se3         | [5439790362](https://linux-hardware.org/?probe=5439790362) | Apr 15, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | [9518f3e6d8](https://linux-hardware.org/?probe=9518f3e6d8) | Apr 13, 2023 |
| Gigabyte      | AX370-Gaming K7 se3         | [ef5cbba147](https://linux-hardware.org/?probe=ef5cbba147) | Apr 12, 2023 |
| Lenovo        | Dory CRB                    | [cab4258e1b](https://linux-hardware.org/?probe=cab4258e1b) | Apr 11, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [fff8cbca92](https://linux-hardware.org/?probe=fff8cbca92) | Apr 10, 2023 |
| Lenovo        | ThinkCentre M90p 5536W67    | [f67448dd99](https://linux-hardware.org/?probe=f67448dd99) | Apr 09, 2023 |
| Dell          | 0J3C2F A00                  | [e2c3600e8b](https://linux-hardware.org/?probe=e2c3600e8b) | Apr 07, 2023 |
| MSI           | J1800I                      | [983e4f18d4](https://linux-hardware.org/?probe=983e4f18d4) | Apr 06, 2023 |
| MSI           | B150 PC MATE                | [da2d2d3d5c](https://linux-hardware.org/?probe=da2d2d3d5c) | Apr 05, 2023 |
| ASRock        | Z87 Killer                  | [ec627dea03](https://linux-hardware.org/?probe=ec627dea03) | Apr 05, 2023 |
| Gigabyte      | Z77X-UD3H                   | [5499373552](https://linux-hardware.org/?probe=5499373552) | Apr 03, 2023 |
| MSI           | GF615M-P33                  | [022324033e](https://linux-hardware.org/?probe=022324033e) | Apr 02, 2023 |
| Pegatron      | 2ACF                        | [c015b7fd50](https://linux-hardware.org/?probe=c015b7fd50) | Apr 01, 2023 |
| MSI           | B250M PRO-VDH 2018-05-07    | [6f7e481d06](https://linux-hardware.org/?probe=6f7e481d06) | Mar 27, 2023 |
| ASRock        | Z87 Killer                  | [53ec55f5ae](https://linux-hardware.org/?probe=53ec55f5ae) | Mar 27, 2023 |
| Shenzhen M... | HX90G                       | [b6bd6cab94](https://linux-hardware.org/?probe=b6bd6cab94) | Mar 26, 2023 |
| MSI           | GF615M-P33                  | [51276a5f00](https://linux-hardware.org/?probe=51276a5f00) | Mar 25, 2023 |
| Lenovo        | SHARKBAY NOK                | [df8f872445](https://linux-hardware.org/?probe=df8f872445) | Mar 25, 2023 |
| Gigabyte      | GA-990FX-GAMING             | [7f1e3cf271](https://linux-hardware.org/?probe=7f1e3cf271) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [9b2ff390f6](https://linux-hardware.org/?probe=9b2ff390f6) | Mar 20, 2023 |
| MSI           | B365M PRO-VDH               | [3332cb54e5](https://linux-hardware.org/?probe=3332cb54e5) | Mar 18, 2023 |
| HP            | 09CCh                       | [e122b11e42](https://linux-hardware.org/?probe=e122b11e42) | Mar 12, 2023 |
| HP            | 09CCh                       | [9421be2c59](https://linux-hardware.org/?probe=9421be2c59) | Mar 11, 2023 |
| ASRock        | Z170 Extreme4               | [428377b153](https://linux-hardware.org/?probe=428377b153) | Mar 03, 2023 |
| Foxconn       | 2ABF                        | [9e63190b6f](https://linux-hardware.org/?probe=9e63190b6f) | Mar 01, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [10f864cbb0](https://linux-hardware.org/?probe=10f864cbb0) | Mar 01, 2023 |
| ASUSTek       | AM1I-A                      | [b5fe605f8b](https://linux-hardware.org/?probe=b5fe605f8b) | Feb 27, 2023 |
| Gigabyte      | Z77X-UD5H                   | [2071bc50ce](https://linux-hardware.org/?probe=2071bc50ce) | Feb 27, 2023 |
| Gigabyte      | Z77X-UD5H                   | [472c035387](https://linux-hardware.org/?probe=472c035387) | Feb 27, 2023 |
| Dell          | 0MH651                      | [7921e9f8bc](https://linux-hardware.org/?probe=7921e9f8bc) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [9b2a57b7d2](https://linux-hardware.org/?probe=9b2a57b7d2) | Feb 26, 2023 |
| ASRock        | B550M Phantom Gaming 4      | [8bfeed43ef](https://linux-hardware.org/?probe=8bfeed43ef) | Feb 24, 2023 |
| MSI           | C847MS-E33                  | [698d950f05](https://linux-hardware.org/?probe=698d950f05) | Feb 24, 2023 |
| Dell          | 02YYK5 A00                  | [cff33d0b1e](https://linux-hardware.org/?probe=cff33d0b1e) | Feb 20, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [503fe663b4](https://linux-hardware.org/?probe=503fe663b4) | Feb 20, 2023 |
| ASUSTek       | PRIME H570M-PLUS            | [4fac3ddf27](https://linux-hardware.org/?probe=4fac3ddf27) | Feb 19, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [e2facdc650](https://linux-hardware.org/?probe=e2facdc650) | Feb 19, 2023 |
| ASRock        | B550M-HDV                   | [755006e226](https://linux-hardware.org/?probe=755006e226) | Feb 17, 2023 |
| Dell          | 03NVJ6 A00                  | [d118fe4ba2](https://linux-hardware.org/?probe=d118fe4ba2) | Feb 16, 2023 |
| ASUSTek       | Maximus VII HERO            | [ef3ee2ebf2](https://linux-hardware.org/?probe=ef3ee2ebf2) | Feb 14, 2023 |
| ASUSTek       | Maximus VII HERO            | [cdd9011e76](https://linux-hardware.org/?probe=cdd9011e76) | Feb 13, 2023 |
| Pegatron      | 2AB6                        | [65b3bb622e](https://linux-hardware.org/?probe=65b3bb622e) | Feb 12, 2023 |
| MSI           | 2A9Ch                       | [934ca9b130](https://linux-hardware.org/?probe=934ca9b130) | Feb 12, 2023 |
| MSI           | 2A9Ch                       | [1a76baff0f](https://linux-hardware.org/?probe=1a76baff0f) | Feb 12, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [19547b9a43](https://linux-hardware.org/?probe=19547b9a43) | Feb 12, 2023 |
| Pegatron      | 2AB6                        | [1f727ee133](https://linux-hardware.org/?probe=1f727ee133) | Feb 11, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [2b4f9e9f21](https://linux-hardware.org/?probe=2b4f9e9f21) | Feb 11, 2023 |
| HP            | 0B4Ch D                     | [731d910d0c](https://linux-hardware.org/?probe=731d910d0c) | Feb 08, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [d7157a7862](https://linux-hardware.org/?probe=d7157a7862) | Feb 07, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [4214ad8f29](https://linux-hardware.org/?probe=4214ad8f29) | Feb 04, 2023 |
| Intel         | X79M-S                      | [91ab5e33ed](https://linux-hardware.org/?probe=91ab5e33ed) | Feb 03, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [8ae0d42e1a](https://linux-hardware.org/?probe=8ae0d42e1a) | Feb 03, 2023 |
| ASUSTek       | G10DK                       | [80e1fa4ed8](https://linux-hardware.org/?probe=80e1fa4ed8) | Feb 01, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [6444a93633](https://linux-hardware.org/?probe=6444a93633) | Jan 29, 2023 |
| HP            | 8750                        | [e8b02ffbb5](https://linux-hardware.org/?probe=e8b02ffbb5) | Jan 23, 2023 |
| Intel         | X79M-S                      | [ccad523936](https://linux-hardware.org/?probe=ccad523936) | Jan 22, 2023 |
| ASUSTek       | H81M-C                      | [ec12d33bd7](https://linux-hardware.org/?probe=ec12d33bd7) | Jan 21, 2023 |
| ASRock        | X99 Taichi                  | [793777c14e](https://linux-hardware.org/?probe=793777c14e) | Jan 19, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | [0e8d25f649](https://linux-hardware.org/?probe=0e8d25f649) | Jan 19, 2023 |
| ASUSTek       | PRIME H570M-PLUS            | [4932579d3e](https://linux-hardware.org/?probe=4932579d3e) | Jan 19, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | [a1b3ac9ccc](https://linux-hardware.org/?probe=a1b3ac9ccc) | Jan 19, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [b11a63e25d](https://linux-hardware.org/?probe=b11a63e25d) | Jan 19, 2023 |
| ASRock        | AM1H-ITX                    | [7427c997d7](https://linux-hardware.org/?probe=7427c997d7) | Jan 18, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [3677d8f4e7](https://linux-hardware.org/?probe=3677d8f4e7) | Jan 15, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [291dceb273](https://linux-hardware.org/?probe=291dceb273) | Jan 14, 2023 |
| ASUSTek       | P5KPL-AM                    | [9d4f877d3d](https://linux-hardware.org/?probe=9d4f877d3d) | Jan 14, 2023 |
| MSI           | 970 GAMING                  | [bd4516127b](https://linux-hardware.org/?probe=bd4516127b) | Jan 14, 2023 |
| MSI           | 970 GAMING                  | [3c475bc193](https://linux-hardware.org/?probe=3c475bc193) | Jan 14, 2023 |
| Gigabyte      | B75M-D2V                    | [8f9d1f85ee](https://linux-hardware.org/?probe=8f9d1f85ee) | Jan 14, 2023 |
| MSI           | PRO H610M-B DDR4            | [1d6a667a5b](https://linux-hardware.org/?probe=1d6a667a5b) | Jan 11, 2023 |
| HP            | 304Ah                       | [c79a932800](https://linux-hardware.org/?probe=c79a932800) | Jan 11, 2023 |
| Dell          | 0PTTT9 A01                  | [fa17d61c80](https://linux-hardware.org/?probe=fa17d61c80) | Jan 11, 2023 |
| Gigabyte      | H170-D3H-CF                 | [8064745798](https://linux-hardware.org/?probe=8064745798) | Jan 10, 2023 |
| Gigabyte      | B550M DS3H                  | [3e39bca3ed](https://linux-hardware.org/?probe=3e39bca3ed) | Jan 09, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [2f03fd41c1](https://linux-hardware.org/?probe=2f03fd41c1) | Jan 09, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [92205d303f](https://linux-hardware.org/?probe=92205d303f) | Jan 08, 2023 |
| ASRock        | B450M Pro4-F                | [182a43f2b4](https://linux-hardware.org/?probe=182a43f2b4) | Jan 08, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [b808a6be1a](https://linux-hardware.org/?probe=b808a6be1a) | Jan 08, 2023 |
| Dell          | 0C27VV A00                  | [317f136007](https://linux-hardware.org/?probe=317f136007) | Jan 07, 2023 |
| Gigabyte      | H410M H V3                  | [abdf0ab0b9](https://linux-hardware.org/?probe=abdf0ab0b9) | Jan 03, 2023 |
| Gigabyte      | H410M H V3                  | [5c14d6ea96](https://linux-hardware.org/?probe=5c14d6ea96) | Jan 03, 2023 |
| ASRock        | AM1H-ITX                    | [3b32e784a3](https://linux-hardware.org/?probe=3b32e784a3) | Jan 03, 2023 |
| Intel         | X79M-S                      | [3b38d8023e](https://linux-hardware.org/?probe=3b38d8023e) | Jan 03, 2023 |
| Intel         | X79M-S                      | [5c97a3976d](https://linux-hardware.org/?probe=5c97a3976d) | Jan 01, 2023 |
| Fujitsu Si... | D2420 S26361-D2420          | [9e8c937daa](https://linux-hardware.org/?probe=9e8c937daa) | Dec 31, 2022 |
| Gigabyte      | B75M-D3V                    | [ce23d2f7cd](https://linux-hardware.org/?probe=ce23d2f7cd) | Dec 31, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | [cecef0575d](https://linux-hardware.org/?probe=cecef0575d) | Dec 30, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | [498c8c83e2](https://linux-hardware.org/?probe=498c8c83e2) | Dec 30, 2022 |
| Fujitsu Si... | D2420 S26361-D2420          | [019236854d](https://linux-hardware.org/?probe=019236854d) | Dec 30, 2022 |
| Fujitsu Si... | D2420 S26361-D2420          | [d6f064e643](https://linux-hardware.org/?probe=d6f064e643) | Dec 30, 2022 |
| MSI           | B75MA-P45                   | [f0b4df8849](https://linux-hardware.org/?probe=f0b4df8849) | Dec 29, 2022 |
| MSI           | Z97 PC Mate                 | [1b7e70ab6e](https://linux-hardware.org/?probe=1b7e70ab6e) | Dec 29, 2022 |
| Gigabyte      | M61SME-S2                   | [5d0485ba40](https://linux-hardware.org/?probe=5d0485ba40) | Dec 26, 2022 |
| Gigabyte      | M61SME-S2                   | [d68451099d](https://linux-hardware.org/?probe=d68451099d) | Dec 26, 2022 |
| Dell          | 0T656F A02                  | [35aa2eee2a](https://linux-hardware.org/?probe=35aa2eee2a) | Dec 23, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [c5cc33f2c6](https://linux-hardware.org/?probe=c5cc33f2c6) | Dec 23, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [ffbf35fd33](https://linux-hardware.org/?probe=ffbf35fd33) | Dec 23, 2022 |
| ASRock        | X300M-STX                   | [3d90b10b72](https://linux-hardware.org/?probe=3d90b10b72) | Dec 22, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [64f6471e58](https://linux-hardware.org/?probe=64f6471e58) | Dec 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [b01c41faa0](https://linux-hardware.org/?probe=b01c41faa0) | Dec 21, 2022 |
| HP            | 09CCh                       | [60d8cc87c7](https://linux-hardware.org/?probe=60d8cc87c7) | Dec 20, 2022 |
| Dell          | 0M5DCD A00                  | [2a2f618c62](https://linux-hardware.org/?probe=2a2f618c62) | Dec 19, 2022 |
| ASUSTek       | P8Z77-V LK                  | [c106327357](https://linux-hardware.org/?probe=c106327357) | Dec 18, 2022 |
| Dell          | 0Y2MRG A00                  | [e5525b45b5](https://linux-hardware.org/?probe=e5525b45b5) | Dec 18, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [00cc810cfc](https://linux-hardware.org/?probe=00cc810cfc) | Dec 17, 2022 |
| ASUSTek       | PRIME B450M-K               | [a6dfbac9f9](https://linux-hardware.org/?probe=a6dfbac9f9) | Dec 15, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [57b6a24933](https://linux-hardware.org/?probe=57b6a24933) | Dec 05, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [059ed32da0](https://linux-hardware.org/?probe=059ed32da0) | Dec 03, 2022 |
| ASUSTek       | A88XM-A/USB                 | [012f2dccba](https://linux-hardware.org/?probe=012f2dccba) | Dec 01, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [4e6ae396d9](https://linux-hardware.org/?probe=4e6ae396d9) | Nov 30, 2022 |
| ASUSTek       | P5WD2-Premium               | [aad7343998](https://linux-hardware.org/?probe=aad7343998) | Nov 25, 2022 |
| ASRock        | X570 Pro4                   | [dad186aa07](https://linux-hardware.org/?probe=dad186aa07) | Nov 24, 2022 |
| HP            | 8750                        | [b1ac308187](https://linux-hardware.org/?probe=b1ac308187) | Nov 24, 2022 |
| ASRock        | X670E Taichi Carrara        | [7e844d7172](https://linux-hardware.org/?probe=7e844d7172) | Nov 24, 2022 |
| HP            | 0AACh                       | [9e37ad4151](https://linux-hardware.org/?probe=9e37ad4151) | Nov 23, 2022 |
| Gigabyte      | Z87-HD3                     | [00faab62d7](https://linux-hardware.org/?probe=00faab62d7) | Nov 22, 2022 |
| HP            | 82B4                        | [c56604f389](https://linux-hardware.org/?probe=c56604f389) | Nov 21, 2022 |
| ASUSTek       | A55BM-E                     | [9ed6d8ee1e](https://linux-hardware.org/?probe=9ed6d8ee1e) | Nov 16, 2022 |
| Fujitsu       | D2679-B1 S26361-D2679-Bx... | [b8da32bca0](https://linux-hardware.org/?probe=b8da32bca0) | Nov 14, 2022 |
| Supermicro    | X9DAL                       | [56d4bd9f26](https://linux-hardware.org/?probe=56d4bd9f26) | Nov 13, 2022 |
| ASRock        | B450 Steel Legend           | [48572e207b](https://linux-hardware.org/?probe=48572e207b) | Nov 12, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [558d46bf81](https://linux-hardware.org/?probe=558d46bf81) | Nov 08, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | [9f586bafd4](https://linux-hardware.org/?probe=9f586bafd4) | Nov 07, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | [1d9cb16e2f](https://linux-hardware.org/?probe=1d9cb16e2f) | Nov 07, 2022 |
| ASUSTek       | P5Q DELUXE                  | [82bf0e80f0](https://linux-hardware.org/?probe=82bf0e80f0) | Nov 06, 2022 |
| ASUSTek       | P5Q DELUXE                  | [28af0c9803](https://linux-hardware.org/?probe=28af0c9803) | Nov 06, 2022 |
| ASRock        | AB350M Pro4                 | [96bd39af33](https://linux-hardware.org/?probe=96bd39af33) | Nov 05, 2022 |
| HP            | 3029h                       | [2acf620628](https://linux-hardware.org/?probe=2acf620628) | Nov 04, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [21213fdeec](https://linux-hardware.org/?probe=21213fdeec) | Oct 31, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [919fad100f](https://linux-hardware.org/?probe=919fad100f) | Oct 31, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [f45ab957da](https://linux-hardware.org/?probe=f45ab957da) | Oct 28, 2022 |
| HP            | 3029h                       | [46c9e39101](https://linux-hardware.org/?probe=46c9e39101) | Oct 26, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [5bc9d4bdc8](https://linux-hardware.org/?probe=5bc9d4bdc8) | Oct 26, 2022 |
| Acer          | Veriton NBU                 | [7be04cd3ed](https://linux-hardware.org/?probe=7be04cd3ed) | Oct 25, 2022 |
| Gigabyte      | X58A-UD7                    | [6d3bf37ff3](https://linux-hardware.org/?probe=6d3bf37ff3) | Oct 25, 2022 |
| Dell          | 0J3C2F A00                  | [c97e42e738](https://linux-hardware.org/?probe=c97e42e738) | Oct 20, 2022 |
| ASRock        | H81 Pro BTC R2.0            | [2ead6c088f](https://linux-hardware.org/?probe=2ead6c088f) | Oct 20, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [5335a66143](https://linux-hardware.org/?probe=5335a66143) | Oct 17, 2022 |
| ASRock        | X300M-STX                   | [40c27af11f](https://linux-hardware.org/?probe=40c27af11f) | Oct 17, 2022 |
| ASRock        | X300M-STX                   | [25fdbfba33](https://linux-hardware.org/?probe=25fdbfba33) | Oct 17, 2022 |
| MSI           | 970 GAMING                  | [a6e072bc6b](https://linux-hardware.org/?probe=a6e072bc6b) | Oct 15, 2022 |
| MSI           | 970 GAMING                  | [6bc730181f](https://linux-hardware.org/?probe=6bc730181f) | Oct 15, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [4e66c25e04](https://linux-hardware.org/?probe=4e66c25e04) | Oct 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [da04425205](https://linux-hardware.org/?probe=da04425205) | Oct 14, 2022 |
| ASUSTek       | PRIME A320M-E               | [ff58ea3dc1](https://linux-hardware.org/?probe=ff58ea3dc1) | Oct 12, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [e2d9db1022](https://linux-hardware.org/?probe=e2d9db1022) | Oct 10, 2022 |
| ASUSTek       | PRIME Z590-P                | [cf3661bb7c](https://linux-hardware.org/?probe=cf3661bb7c) | Oct 09, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [704da5b600](https://linux-hardware.org/?probe=704da5b600) | Oct 07, 2022 |
| Dell          | 0D28YY A01                  | [5c85c7623a](https://linux-hardware.org/?probe=5c85c7623a) | Oct 04, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [13f60e066f](https://linux-hardware.org/?probe=13f60e066f) | Oct 03, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [e3eb4cd95f](https://linux-hardware.org/?probe=e3eb4cd95f) | Oct 02, 2022 |
| MSI           | B350 PC MATE                | [a4c73b484e](https://linux-hardware.org/?probe=a4c73b484e) | Oct 02, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [ff11bc4efb](https://linux-hardware.org/?probe=ff11bc4efb) | Oct 02, 2022 |
| Lenovo        | ThinkCentre Edge71 1578D... | [95dded89b8](https://linux-hardware.org/?probe=95dded89b8) | Sep 23, 2022 |
| Gigabyte      | Z77-DS3H                    | [ea8ea96269](https://linux-hardware.org/?probe=ea8ea96269) | Sep 21, 2022 |
| ASUSTek       | AM1M-A                      | [a6e61a9993](https://linux-hardware.org/?probe=a6e61a9993) | Sep 19, 2022 |
| Gigabyte      | X58A-UD7                    | [b7f881a109](https://linux-hardware.org/?probe=b7f881a109) | Sep 19, 2022 |
| Gigabyte      | X58A-UD7                    | [59e7485a11](https://linux-hardware.org/?probe=59e7485a11) | Sep 19, 2022 |
| ASUSTek       | PRIME H310-PLUS             | [b9693eaf7c](https://linux-hardware.org/?probe=b9693eaf7c) | Sep 17, 2022 |
| Gigabyte      | Z77-DS3H                    | [b5a0c6309d](https://linux-hardware.org/?probe=b5a0c6309d) | Sep 17, 2022 |
| Lenovo        | SHARKBAY NOK                | [bfd4a6b00a](https://linux-hardware.org/?probe=bfd4a6b00a) | Sep 13, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [fc3200b967](https://linux-hardware.org/?probe=fc3200b967) | Aug 31, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [a01239fd83](https://linux-hardware.org/?probe=a01239fd83) | Aug 29, 2022 |
| HP            | 8509                        | [0656e40cba](https://linux-hardware.org/?probe=0656e40cba) | Aug 26, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [595bf9c8a7](https://linux-hardware.org/?probe=595bf9c8a7) | Aug 23, 2022 |
| ASRock        | N68C-S UCC                  | [bb19c0586c](https://linux-hardware.org/?probe=bb19c0586c) | Aug 20, 2022 |
| ASUSTek       | P5KPL-SE                    | [2925e63a87](https://linux-hardware.org/?probe=2925e63a87) | Aug 20, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [6865f5ed0b](https://linux-hardware.org/?probe=6865f5ed0b) | Aug 19, 2022 |
| Gigabyte      | B450 GAMING X               | [80760b8e4b](https://linux-hardware.org/?probe=80760b8e4b) | Aug 16, 2022 |
| HP            | 805B                        | [188fdd3a56](https://linux-hardware.org/?probe=188fdd3a56) | Aug 13, 2022 |
| ASRock        | 990FX Killer                | [cba7d360f1](https://linux-hardware.org/?probe=cba7d360f1) | Aug 10, 2022 |
| Gigabyte      | Z87-HD3                     | [ee1bdd9333](https://linux-hardware.org/?probe=ee1bdd9333) | Aug 09, 2022 |
| Gigabyte      | Z87-HD3                     | [a0243ce6f0](https://linux-hardware.org/?probe=a0243ce6f0) | Aug 09, 2022 |
| Gigabyte      | EP35-DS3P                   | [5c29aee903](https://linux-hardware.org/?probe=5c29aee903) | Aug 08, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [61e317887a](https://linux-hardware.org/?probe=61e317887a) | Aug 07, 2022 |
| Dell          | 0VHWTR A02                  | [61b30cfde0](https://linux-hardware.org/?probe=61b30cfde0) | Aug 06, 2022 |
| Gigabyte      | B450 GAMING X               | [b875ef6dbf](https://linux-hardware.org/?probe=b875ef6dbf) | Aug 04, 2022 |
| ASUSTek       | H110M-K                     | [8c6442a868](https://linux-hardware.org/?probe=8c6442a868) | Aug 04, 2022 |
| Gigabyte      | Z87-HD3                     | [01430753da](https://linux-hardware.org/?probe=01430753da) | Aug 02, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [cc8b9aa8f6](https://linux-hardware.org/?probe=cc8b9aa8f6) | Aug 01, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [82d0a7ace6](https://linux-hardware.org/?probe=82d0a7ace6) | Jul 29, 2022 |
| MSI           | G31TM-P35                   | [1bc8def241](https://linux-hardware.org/?probe=1bc8def241) | Jul 28, 2022 |
| HP            | 1494                        | [6805afe809](https://linux-hardware.org/?probe=6805afe809) | Jul 27, 2022 |
| Minix         | NEO Z83-4 V1.1              | [e8c6448552](https://linux-hardware.org/?probe=e8c6448552) | Jul 23, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [2986a26253](https://linux-hardware.org/?probe=2986a26253) | Jul 22, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [7e6502be7c](https://linux-hardware.org/?probe=7e6502be7c) | Jul 20, 2022 |
| Foxconn       | 2ABF                        | [2349372af2](https://linux-hardware.org/?probe=2349372af2) | Jul 16, 2022 |
| ASUSTek       | PRIME Z690-P D4             | [e5fed36e22](https://linux-hardware.org/?probe=e5fed36e22) | Jul 15, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [9c06bd996b](https://linux-hardware.org/?probe=9c06bd996b) | Jul 15, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [9e71693839](https://linux-hardware.org/?probe=9e71693839) | Jul 15, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [e5316b7d72](https://linux-hardware.org/?probe=e5316b7d72) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [3df269fec9](https://linux-hardware.org/?probe=3df269fec9) | Jul 09, 2022 |
| MSI           | X470 GAMING PRO             | [b94f3f8031](https://linux-hardware.org/?probe=b94f3f8031) | Jul 07, 2022 |
| ASUSTek       | P5B                         | [149ab02b84](https://linux-hardware.org/?probe=149ab02b84) | Jul 06, 2022 |
| MSI           | 880GMA-E35                  | [8bcc34797b](https://linux-hardware.org/?probe=8bcc34797b) | Jul 02, 2022 |
| ASUSTek       | A88XM-A/USB                 | [01fb492b9d](https://linux-hardware.org/?probe=01fb492b9d) | Jul 01, 2022 |
| ASUSTek       | A88XM-A/USB                 | [b4b8457bd9](https://linux-hardware.org/?probe=b4b8457bd9) | Jul 01, 2022 |
| Gigabyte      | GA-870A-UD3                 | [7b07f30b17](https://linux-hardware.org/?probe=7b07f30b17) | Jun 29, 2022 |
| Gigabyte      | Z170-Gaming K3              | [70dc9ba605](https://linux-hardware.org/?probe=70dc9ba605) | Jun 28, 2022 |
| Gigabyte      | Z690 UD                     | [2c21dadeed](https://linux-hardware.org/?probe=2c21dadeed) | Jun 25, 2022 |
| ASUSTek       | H81M-R 2016-11-08           | [f9ac4d3e81](https://linux-hardware.org/?probe=f9ac4d3e81) | Jun 25, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [cf76d2d9a4](https://linux-hardware.org/?probe=cf76d2d9a4) | Jun 23, 2022 |
| Gigabyte      | B660M GAMING DDR4           | [80ecbe8684](https://linux-hardware.org/?probe=80ecbe8684) | Jun 21, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | [bbba4fae4b](https://linux-hardware.org/?probe=bbba4fae4b) | Jun 12, 2022 |
| ASUSTek       | M4A78 PRO                   | [805f88e697](https://linux-hardware.org/?probe=805f88e697) | Jun 08, 2022 |
| MSI           | B85M-G43                    | [097b308b60](https://linux-hardware.org/?probe=097b308b60) | Jun 04, 2022 |
| ASUSTek       | P5E-VM DO                   | [935c03cd63](https://linux-hardware.org/?probe=935c03cd63) | Jun 03, 2022 |
| Lenovo        | ThinkCentre M57 00P4496     | [07ba75838a](https://linux-hardware.org/?probe=07ba75838a) | May 31, 2022 |
| ASUSTek       | M4A78 PRO                   | [276f8565dc](https://linux-hardware.org/?probe=276f8565dc) | May 29, 2022 |
| ASUSTek       | TUF X299 MARK 2             | [8409764263](https://linux-hardware.org/?probe=8409764263) | May 27, 2022 |
| Gigabyte      | Z77X-UD3H                   | [0d439f9812](https://linux-hardware.org/?probe=0d439f9812) | May 25, 2022 |
| SIEMENS       | A5E02122237 ES010           | [3d7173e7a3](https://linux-hardware.org/?probe=3d7173e7a3) | May 24, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [5f03a4b52d](https://linux-hardware.org/?probe=5f03a4b52d) | May 21, 2022 |
| MSI           | B85M-G43                    | [ef33bf347c](https://linux-hardware.org/?probe=ef33bf347c) | May 18, 2022 |
| ASRock        | 970M Pro3                   | [d39e962536](https://linux-hardware.org/?probe=d39e962536) | May 18, 2022 |
| ASUSTek       | M5A88-V EVO                 | [ab5a307891](https://linux-hardware.org/?probe=ab5a307891) | May 18, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [77c7c34b9e](https://linux-hardware.org/?probe=77c7c34b9e) | May 18, 2022 |
| ASRock        | 970M Pro3                   | [6f48a71a87](https://linux-hardware.org/?probe=6f48a71a87) | May 17, 2022 |
| HP            | 22F8                        | [70f6561c5c](https://linux-hardware.org/?probe=70f6561c5c) | May 16, 2022 |
| Clientron     | Sunshine Valley             | [e8915a5023](https://linux-hardware.org/?probe=e8915a5023) | May 15, 2022 |
| Clientron     | Sunshine Valley             | [5f148de534](https://linux-hardware.org/?probe=5f148de534) | May 15, 2022 |
| MSI           | AM1I                        | [f22b398676](https://linux-hardware.org/?probe=f22b398676) | May 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [0ec606b729](https://linux-hardware.org/?probe=0ec606b729) | May 14, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [6fdf1cd28c](https://linux-hardware.org/?probe=6fdf1cd28c) | May 14, 2022 |
| Pegatron      | 2AB5                        | [14905c8ec7](https://linux-hardware.org/?probe=14905c8ec7) | May 14, 2022 |
| SIEMENS       | A5E02122237 ES010           | [cc728f6c38](https://linux-hardware.org/?probe=cc728f6c38) | May 09, 2022 |
| Clientron     | Sunshine Valley             | [d2deff798c](https://linux-hardware.org/?probe=d2deff798c) | May 08, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [a3e95474a0](https://linux-hardware.org/?probe=a3e95474a0) | May 08, 2022 |
| ASRock        | 970M Pro3                   | [1983ed1d48](https://linux-hardware.org/?probe=1983ed1d48) | May 07, 2022 |
| ASRock        | 970M Pro3                   | [2853128cd0](https://linux-hardware.org/?probe=2853128cd0) | May 05, 2022 |
| ASRock        | 970M Pro3                   | [5f51fd4cf8](https://linux-hardware.org/?probe=5f51fd4cf8) | May 05, 2022 |
| Clientron     | Sunshine Valley             | [97a95fa1af](https://linux-hardware.org/?probe=97a95fa1af) | May 05, 2022 |
| MSI           | B85M-G43                    | [f5deeb2d19](https://linux-hardware.org/?probe=f5deeb2d19) | May 04, 2022 |
| Dell          | 0P301D A02                  | [ab9edfbc39](https://linux-hardware.org/?probe=ab9edfbc39) | May 03, 2022 |
| ASRock        | 970M Pro3                   | [f20f31b107](https://linux-hardware.org/?probe=f20f31b107) | May 03, 2022 |
| ASRock        | 970M Pro3                   | [73a563257a](https://linux-hardware.org/?probe=73a563257a) | May 03, 2022 |
| MSI           | X570-A PRO                  | [ff568c874c](https://linux-hardware.org/?probe=ff568c874c) | Apr 30, 2022 |
| Gigabyte      | M68MT-S2                    | [f3b89e43d4](https://linux-hardware.org/?probe=f3b89e43d4) | Apr 30, 2022 |
| Gigabyte      | H310N x.x                   | [d0daa33c07](https://linux-hardware.org/?probe=d0daa33c07) | Apr 30, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [f4a6777382](https://linux-hardware.org/?probe=f4a6777382) | Apr 30, 2022 |
| Gigabyte      | H170-HD3 DDR3-CF            | [b23594dfa0](https://linux-hardware.org/?probe=b23594dfa0) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [ffdfb3a578](https://linux-hardware.org/?probe=ffdfb3a578) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [55c0ec3653](https://linux-hardware.org/?probe=55c0ec3653) | Apr 29, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [4185312ca8](https://linux-hardware.org/?probe=4185312ca8) | Apr 27, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [88248eb2e6](https://linux-hardware.org/?probe=88248eb2e6) | Apr 27, 2022 |
| HP            | 22F8                        | [eb4d49a17b](https://linux-hardware.org/?probe=eb4d49a17b) | Apr 27, 2022 |
| HP            | 22F8                        | [67dc13d1ad](https://linux-hardware.org/?probe=67dc13d1ad) | Apr 23, 2022 |
| ASRock        | B450M Pro4-F                | [68d9ef89c7](https://linux-hardware.org/?probe=68d9ef89c7) | Apr 19, 2022 |
| MSI           | B150 PC MATE                | [34c7fe45bc](https://linux-hardware.org/?probe=34c7fe45bc) | Apr 19, 2022 |
| Intel         | X79G V2.x                   | [497807c732](https://linux-hardware.org/?probe=497807c732) | Apr 18, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [874e39c8ef](https://linux-hardware.org/?probe=874e39c8ef) | Apr 18, 2022 |
| ASRockRack    | X470D4U                     | [1b9b990e65](https://linux-hardware.org/?probe=1b9b990e65) | Apr 17, 2022 |
| ASUSTek       | B85M-E                      | [b68f986aaf](https://linux-hardware.org/?probe=b68f986aaf) | Apr 17, 2022 |
| ASUSTek       | B85M-E                      | [93306ff9ee](https://linux-hardware.org/?probe=93306ff9ee) | Apr 17, 2022 |
| Lenovo        | 3132 SDK0K17763 WIN 1801... | [a6e43346ba](https://linux-hardware.org/?probe=a6e43346ba) | Apr 16, 2022 |
| Gigabyte      | G41MT-D3V                   | [b1944bf89e](https://linux-hardware.org/?probe=b1944bf89e) | Apr 15, 2022 |
| Gigabyte      | G41MT-D3V                   | [19b11d696f](https://linux-hardware.org/?probe=19b11d696f) | Apr 15, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [cf9feaf8ec](https://linux-hardware.org/?probe=cf9feaf8ec) | Apr 15, 2022 |
| Gigabyte      | Z590 VISION D               | [4bde7cc5cd](https://linux-hardware.org/?probe=4bde7cc5cd) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [8a5920ae1a](https://linux-hardware.org/?probe=8a5920ae1a) | Apr 13, 2022 |
| Gigabyte      | B85M-D3H-A                  | [46dc99c237](https://linux-hardware.org/?probe=46dc99c237) | Apr 13, 2022 |
| Dell          | 0GWHMW A03                  | [ff312c5929](https://linux-hardware.org/?probe=ff312c5929) | Apr 13, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | [e4ea2782f9](https://linux-hardware.org/?probe=e4ea2782f9) | Apr 10, 2022 |
| MSI           | H110M ECO                   | [c01d51d1f5](https://linux-hardware.org/?probe=c01d51d1f5) | Apr 09, 2022 |
| HP            | 1495                        | [36ea4763de](https://linux-hardware.org/?probe=36ea4763de) | Apr 08, 2022 |
| Dell          | 0VD5HY A04                  | [8672ef6c18](https://linux-hardware.org/?probe=8672ef6c18) | Apr 07, 2022 |
| ASUSTek       | A88XM-A                     | [0f8ce13fb9](https://linux-hardware.org/?probe=0f8ce13fb9) | Apr 06, 2022 |
| ASRock        | B450 Pro4                   | [65e855a6a5](https://linux-hardware.org/?probe=65e855a6a5) | Apr 05, 2022 |
| Gigabyte      | B450M S2H                   | [046d0eb6c8](https://linux-hardware.org/?probe=046d0eb6c8) | Apr 05, 2022 |
| Gigabyte      | H61M-D2-B3                  | [d95c37955a](https://linux-hardware.org/?probe=d95c37955a) | Apr 03, 2022 |
| Intel         | DG45ID AAE27729-310         | [4a15651672](https://linux-hardware.org/?probe=4a15651672) | Apr 01, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | [ce2e9f743d](https://linux-hardware.org/?probe=ce2e9f743d) | Mar 31, 2022 |
| Dell          | OptiPlex 7010               | [f1167c797e](https://linux-hardware.org/?probe=f1167c797e) | Mar 31, 2022 |
| Acer          | Veriton M4610G              | [34ac41051e](https://linux-hardware.org/?probe=34ac41051e) | Mar 30, 2022 |
| ASRock        | B75M-GL R2.0                | [b951c3cc48](https://linux-hardware.org/?probe=b951c3cc48) | Mar 29, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [b02c880a8a](https://linux-hardware.org/?probe=b02c880a8a) | Mar 26, 2022 |
| Le Cube 1     | Unknown                     | [a881cc0397](https://linux-hardware.org/?probe=a881cc0397) | Mar 26, 2022 |
| ASUSTek       | B85M-E                      | [b0769dffdd](https://linux-hardware.org/?probe=b0769dffdd) | Mar 19, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [a5d1f1ec32](https://linux-hardware.org/?probe=a5d1f1ec32) | Mar 18, 2022 |
| MSI           | B85M-G43                    | [3869d4fdc0](https://linux-hardware.org/?probe=3869d4fdc0) | Mar 14, 2022 |
| MSI           | B85M-E45 2015-08-19         | [90f5d4247e](https://linux-hardware.org/?probe=90f5d4247e) | Mar 13, 2022 |
| ASUSTek       | B85M-E                      | [161eda858b](https://linux-hardware.org/?probe=161eda858b) | Mar 10, 2022 |
| Unknown       | Unknown                     | [c9ba6eb4ae](https://linux-hardware.org/?probe=c9ba6eb4ae) | Mar 09, 2022 |
| ASUSTek       | P5E-VM DO                   | [876e876df1](https://linux-hardware.org/?probe=876e876df1) | Mar 09, 2022 |
| ASUSTek       | B85M-E                      | [36bada67c8](https://linux-hardware.org/?probe=36bada67c8) | Mar 08, 2022 |
| ASUSTek       | PRIME B360M-A               | [038e9b79ef](https://linux-hardware.org/?probe=038e9b79ef) | Mar 08, 2022 |
| ASUSTek       | A88XM-A                     | [ce5f22f97a](https://linux-hardware.org/?probe=ce5f22f97a) | Mar 08, 2022 |
| ASUSTek       | M5A78L-M LX3                | [ae9c8e47e2](https://linux-hardware.org/?probe=ae9c8e47e2) | Mar 07, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | [1fb25ad2c3](https://linux-hardware.org/?probe=1fb25ad2c3) | Mar 05, 2022 |
| MSI           | B85M-G43                    | [d5e3087569](https://linux-hardware.org/?probe=d5e3087569) | Mar 04, 2022 |
| HP            | 3031h                       | [52a519941d](https://linux-hardware.org/?probe=52a519941d) | Mar 03, 2022 |
| Gigabyte      | G1.Sniper                   | [59b1ae56dd](https://linux-hardware.org/?probe=59b1ae56dd) | Mar 01, 2022 |
| Dell          | 0M858N A01                  | [02b86c4d66](https://linux-hardware.org/?probe=02b86c4d66) | Mar 01, 2022 |
| HP            | 821D                        | [fdfcbe172a](https://linux-hardware.org/?probe=fdfcbe172a) | Feb 28, 2022 |
| ASUSTek       | P8Q67-M DO/TPM              | [ee784c0a7e](https://linux-hardware.org/?probe=ee784c0a7e) | Feb 28, 2022 |
| ASRock        | Z370M Pro4                  | [8e08f3846b](https://linux-hardware.org/?probe=8e08f3846b) | Feb 27, 2022 |
| ASUSTek       | ROG STRIX B360-G GAMING     | [b2e75d51bb](https://linux-hardware.org/?probe=b2e75d51bb) | Feb 26, 2022 |
| Gigabyte      | G1.Sniper                   | [615669f693](https://linux-hardware.org/?probe=615669f693) | Feb 22, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [d32c812d2b](https://linux-hardware.org/?probe=d32c812d2b) | Feb 22, 2022 |
| Unknown       | Unknown                     | [de7189b0d4](https://linux-hardware.org/?probe=de7189b0d4) | Feb 20, 2022 |
| MSI           | A55M-P33                    | [d891e34be9](https://linux-hardware.org/?probe=d891e34be9) | Feb 20, 2022 |
| MSI           | Boston                      | [0f7a7dd744](https://linux-hardware.org/?probe=0f7a7dd744) | Feb 19, 2022 |
| ASUSTek       | P5E-VM DO                   | [c204579cc4](https://linux-hardware.org/?probe=c204579cc4) | Feb 18, 2022 |
| MSI           | Z370-A PRO                  | [51dfd147ef](https://linux-hardware.org/?probe=51dfd147ef) | Feb 17, 2022 |
| Dell          | 073MMW A02                  | [ab6cd0396d](https://linux-hardware.org/?probe=ab6cd0396d) | Feb 14, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | [fa5ed1f68b](https://linux-hardware.org/?probe=fa5ed1f68b) | Feb 13, 2022 |
| Gigabyte      | EP45-DS3L                   | [bec0b9ac1e](https://linux-hardware.org/?probe=bec0b9ac1e) | Feb 13, 2022 |
| ASUSTek       | M4A77T/USB3                 | [b5dd380b9a](https://linux-hardware.org/?probe=b5dd380b9a) | Feb 10, 2022 |
| HP            | 18E7                        | [11c3f1c67f](https://linux-hardware.org/?probe=11c3f1c67f) | Feb 09, 2022 |
| Gigabyte      | H81M-S2PV                   | [4aece000f1](https://linux-hardware.org/?probe=4aece000f1) | Feb 03, 2022 |
| ASRock        | B75M-GL R2.0                | [4cf4045deb](https://linux-hardware.org/?probe=4cf4045deb) | Feb 01, 2022 |
| Acer          | Aspire XC-830               | [182ad67187](https://linux-hardware.org/?probe=182ad67187) | Feb 01, 2022 |
| ASRock        | B75M-GL R2.0                | [6afebcc975](https://linux-hardware.org/?probe=6afebcc975) | Feb 01, 2022 |
| ASUSTek       | H81M-A                      | [8fba4698c9](https://linux-hardware.org/?probe=8fba4698c9) | Feb 01, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [dcc55138d2](https://linux-hardware.org/?probe=dcc55138d2) | Jan 29, 2022 |
| ASRock        | AB350M Pro4                 | [6b7cf2d570](https://linux-hardware.org/?probe=6b7cf2d570) | Jan 27, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [267ee0e693](https://linux-hardware.org/?probe=267ee0e693) | Jan 26, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [a72f036b05](https://linux-hardware.org/?probe=a72f036b05) | Jan 26, 2022 |
| ASUSTek       | A88XM-PLUS                  | [a920db9f29](https://linux-hardware.org/?probe=a920db9f29) | Jan 23, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [7a14d864d4](https://linux-hardware.org/?probe=7a14d864d4) | Jan 20, 2022 |
| Gigabyte      | X58A-UD7                    | [c0039193bb](https://linux-hardware.org/?probe=c0039193bb) | Jan 09, 2022 |
| HP            | 18E7                        | [2598720ae1](https://linux-hardware.org/?probe=2598720ae1) | Jan 08, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [b4f5f6f8da](https://linux-hardware.org/?probe=b4f5f6f8da) | Jan 08, 2022 |
| Lenovo        | 369A SDK0F82993 WIN         | [e1141045bf](https://linux-hardware.org/?probe=e1141045bf) | Jan 08, 2022 |
| Gigabyte      | Q87M-D2H                    | [5107953369](https://linux-hardware.org/?probe=5107953369) | Jan 08, 2022 |
| MSI           | B350 PC MATE                | [c5c108c138](https://linux-hardware.org/?probe=c5c108c138) | Jan 03, 2022 |
| HP            | 18E7                        | [8fe0391d59](https://linux-hardware.org/?probe=8fe0391d59) | Dec 28, 2021 |
| MSI           | B450 TOMAHAWK               | [dc6fd4bfc7](https://linux-hardware.org/?probe=dc6fd4bfc7) | Dec 25, 2021 |
| HP            | 1905                        | [9e2637fa00](https://linux-hardware.org/?probe=9e2637fa00) | Dec 23, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [180954acf2](https://linux-hardware.org/?probe=180954acf2) | Dec 23, 2021 |
| ASUSTek       | P5G41-M                     | [09352ecc24](https://linux-hardware.org/?probe=09352ecc24) | Dec 21, 2021 |
| Dell          | 0478VN A00                  | [67955910cb](https://linux-hardware.org/?probe=67955910cb) | Dec 18, 2021 |
| ASUSTek       | P5G41-M                     | [c073d4a4e9](https://linux-hardware.org/?probe=c073d4a4e9) | Dec 17, 2021 |
| Gigabyte      | B75M-D3H                    | [86aff395eb](https://linux-hardware.org/?probe=86aff395eb) | Dec 15, 2021 |
| Gigabyte      | B75M-D3H                    | [6b3727344c](https://linux-hardware.org/?probe=6b3727344c) | Dec 15, 2021 |
| Gigabyte      | Z97X-Gaming GT              | [efb6380716](https://linux-hardware.org/?probe=efb6380716) | Dec 11, 2021 |
| Gigabyte      | 990FXA-UD3                  | [b76ef07c59](https://linux-hardware.org/?probe=b76ef07c59) | Dec 10, 2021 |
| Fujitsu       | D3003-A1 S26361-D3003-A1    | [e96b1f7f6b](https://linux-hardware.org/?probe=e96b1f7f6b) | Dec 07, 2021 |
| Dell          | 0PTTT9 A01                  | [fb7c5092e9](https://linux-hardware.org/?probe=fb7c5092e9) | Dec 07, 2021 |
| HP            | 1905                        | [e16a65e786](https://linux-hardware.org/?probe=e16a65e786) | Dec 06, 2021 |
| HP            | 1905                        | [d58c2f29a4](https://linux-hardware.org/?probe=d58c2f29a4) | Dec 06, 2021 |
| Acer          | Nitro N50-600 V:1.1         | [63319937d0](https://linux-hardware.org/?probe=63319937d0) | Dec 04, 2021 |
| EVGA          | 142-SS-E178                 | [8ad978bbf2](https://linux-hardware.org/?probe=8ad978bbf2) | Nov 23, 2021 |
| Lenovo        | 3731 SDK0J40697 WIN 3305... | [c50601fb76](https://linux-hardware.org/?probe=c50601fb76) | Nov 23, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | [021a54d6d2](https://linux-hardware.org/?probe=021a54d6d2) | Nov 18, 2021 |
| ASUSTek       | PRIME X399-A                | [5edbaed472](https://linux-hardware.org/?probe=5edbaed472) | Nov 18, 2021 |
| Intel         | DP55WB AAE64798-204         | [19a21ae965](https://linux-hardware.org/?probe=19a21ae965) | Nov 17, 2021 |
| Biostar       | TH67B                       | [5d655fd2bd](https://linux-hardware.org/?probe=5d655fd2bd) | Nov 17, 2021 |
| MSI           | A88X-G43                    | [c546efdb47](https://linux-hardware.org/?probe=c546efdb47) | Nov 16, 2021 |
| MSI           | A88X-G43                    | [3cb4a9134c](https://linux-hardware.org/?probe=3cb4a9134c) | Nov 16, 2021 |
| ASUSTek       | P5KPL                       | [6e52b269ee](https://linux-hardware.org/?probe=6e52b269ee) | Nov 15, 2021 |
| Seeed Stud... | ODYSSEY-TGL-A               | [b05c5533b0](https://linux-hardware.org/?probe=b05c5533b0) | Nov 14, 2021 |
| HP            | 1998                        | [2e830badd5](https://linux-hardware.org/?probe=2e830badd5) | Nov 14, 2021 |
| MSI           | 970A-G43                    | [da61ca8b52](https://linux-hardware.org/?probe=da61ca8b52) | Nov 13, 2021 |
| MSI           | 970A-G43                    | [d27f131cce](https://linux-hardware.org/?probe=d27f131cce) | Nov 13, 2021 |
| ASRock        | Z97 Anniversary             | [59ca43cb01](https://linux-hardware.org/?probe=59ca43cb01) | Nov 12, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | [0f4ebd720e](https://linux-hardware.org/?probe=0f4ebd720e) | Nov 11, 2021 |
| ASUSTek       | PRIME B360M-C               | [ecf35bff43](https://linux-hardware.org/?probe=ecf35bff43) | Nov 09, 2021 |
| HP            | 1998                        | [c2ab98c42f](https://linux-hardware.org/?probe=c2ab98c42f) | Nov 07, 2021 |
| ASUSTek       | PRIME A320M-K               | [68d7274a99](https://linux-hardware.org/?probe=68d7274a99) | Nov 07, 2021 |
| MSI           | A320M PRO-VH PLUS           | [7295833004](https://linux-hardware.org/?probe=7295833004) | Nov 03, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [164b215164](https://linux-hardware.org/?probe=164b215164) | Oct 29, 2021 |
| MSI           | H310M PRO-VDH PLUS          | [9f21330313](https://linux-hardware.org/?probe=9f21330313) | Oct 18, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [d890edb314](https://linux-hardware.org/?probe=d890edb314) | Oct 16, 2021 |
| ASRock        | B550M Pro4                  | [ae854c2ff2](https://linux-hardware.org/?probe=ae854c2ff2) | Oct 16, 2021 |
| Gigabyte      | H61M-D2-B3                  | [138df954cb](https://linux-hardware.org/?probe=138df954cb) | Oct 15, 2021 |
| Gigabyte      | H61M-D2-B3                  | [dabe5d459a](https://linux-hardware.org/?probe=dabe5d459a) | Oct 15, 2021 |
| MSI           | MS-7309                     | [33faf5dbef](https://linux-hardware.org/?probe=33faf5dbef) | Oct 14, 2021 |
| Dell          | 0GY6Y8 A00                  | [878347dd71](https://linux-hardware.org/?probe=878347dd71) | Oct 13, 2021 |
| MSI           | MS-7309                     | [b0ddfaaa86](https://linux-hardware.org/?probe=b0ddfaaa86) | Oct 12, 2021 |
| ASUSTek       | AM1I-A                      | [b624e54271](https://linux-hardware.org/?probe=b624e54271) | Oct 10, 2021 |
| UMAX          | J42 Nano                    | [fd40a94769](https://linux-hardware.org/?probe=fd40a94769) | Oct 09, 2021 |
| Gigabyte      | Z390 AORUS PRO-CF           | [81c36c3a21](https://linux-hardware.org/?probe=81c36c3a21) | Oct 09, 2021 |
| ASUSTek       | Crosshair IV Formula        | [3cab016500](https://linux-hardware.org/?probe=3cab016500) | Oct 06, 2021 |
| ASUSTek       | P8B75-V                     | [2615e61a63](https://linux-hardware.org/?probe=2615e61a63) | Oct 05, 2021 |
| Acer          | Aspire M1930                | [0f21c5864a](https://linux-hardware.org/?probe=0f21c5864a) | Oct 05, 2021 |
| Lenovo        | ThinkCentre M58p 6234A1G    | [f6518ea548](https://linux-hardware.org/?probe=f6518ea548) | Oct 04, 2021 |
| HP            | 3047h                       | [15f4144ba7](https://linux-hardware.org/?probe=15f4144ba7) | Oct 03, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [38422d16b5](https://linux-hardware.org/?probe=38422d16b5) | Oct 02, 2021 |
| Pegatron      | 2AB5                        | [21453a290c](https://linux-hardware.org/?probe=21453a290c) | Oct 02, 2021 |
| MSI           | X370 GAMING PRO CARBON A... | [26fb963760](https://linux-hardware.org/?probe=26fb963760) | Oct 01, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [7e82dd3e6d](https://linux-hardware.org/?probe=7e82dd3e6d) | Sep 25, 2021 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [f64736711c](https://linux-hardware.org/?probe=f64736711c) | Sep 25, 2021 |
| Foxconn       | Priv                        | [78997c0b10](https://linux-hardware.org/?probe=78997c0b10) | Sep 24, 2021 |
| ASUSTek       | PRIME B360M-A               | [b39008d274](https://linux-hardware.org/?probe=b39008d274) | Sep 22, 2021 |
| ASUSTek       | AM1I-A                      | [0f57a946c9](https://linux-hardware.org/?probe=0f57a946c9) | Sep 22, 2021 |
| MSI           | MPG Z490 GAMING PLUS        | [5422161d82](https://linux-hardware.org/?probe=5422161d82) | Sep 21, 2021 |
| Gigabyte      | GA-990FX-GAMING             | [61c16353ce](https://linux-hardware.org/?probe=61c16353ce) | Sep 14, 2021 |
| ASRock        | B450M Steel Legend          | [d069d8c301](https://linux-hardware.org/?probe=d069d8c301) | Sep 10, 2021 |
| ASRock        | B75M-GL R2.0                | [4078ccd6f6](https://linux-hardware.org/?probe=4078ccd6f6) | Sep 08, 2021 |
| Gigabyte      | H110M-S2PV-CF               | [fb3c4b683c](https://linux-hardware.org/?probe=fb3c4b683c) | Sep 08, 2021 |
| ASRock        | B75M-GL R2.0                | [9e43cd58cd](https://linux-hardware.org/?probe=9e43cd58cd) | Sep 07, 2021 |
| ASUSTek       | P5KPL                       | [5abf2f2b22](https://linux-hardware.org/?probe=5abf2f2b22) | Sep 05, 2021 |
| ASUSTek       | PRIME X370-PRO              | [d0d9c89285](https://linux-hardware.org/?probe=d0d9c89285) | Sep 04, 2021 |
| Gigabyte      | Z77MX-D3H                   | [e9741b1baf](https://linux-hardware.org/?probe=e9741b1baf) | Sep 02, 2021 |
| Gigabyte      | GA-MA78G-DS3H               | [c31af0c00d](https://linux-hardware.org/?probe=c31af0c00d) | Sep 02, 2021 |
| Gigabyte      | B460M DS3H                  | [ef23780b19](https://linux-hardware.org/?probe=ef23780b19) | Aug 31, 2021 |
| ASRock        | B450M Steel Legend          | [d744798f8c](https://linux-hardware.org/?probe=d744798f8c) | Aug 28, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [2a6bfff91f](https://linux-hardware.org/?probe=2a6bfff91f) | Aug 24, 2021 |
| ASRock        | FM2A68M-DG3+                | [157d6655d0](https://linux-hardware.org/?probe=157d6655d0) | Aug 23, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | [413934fef3](https://linux-hardware.org/?probe=413934fef3) | Aug 23, 2021 |
| ASUSTek       | Pro WS X570-ACE             | [a253cd3e21](https://linux-hardware.org/?probe=a253cd3e21) | Aug 21, 2021 |
| Lenovo        | 3176 NOK                    | [ed11430a97](https://linux-hardware.org/?probe=ed11430a97) | Aug 18, 2021 |
| ASRock        | B460M-ITX/ac                | [2eb3e6f3f6](https://linux-hardware.org/?probe=2eb3e6f3f6) | Aug 17, 2021 |
| Dell          | 02YYK5 A00                  | [2918bafc50](https://linux-hardware.org/?probe=2918bafc50) | Aug 16, 2021 |
| ASUSTek       | Z97-A                       | [5e65f099db](https://linux-hardware.org/?probe=5e65f099db) | Aug 12, 2021 |
| Gigabyte      | Z77-D3H                     | [9dafe47483](https://linux-hardware.org/?probe=9dafe47483) | Aug 07, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | [c861e28d21](https://linux-hardware.org/?probe=c861e28d21) | Aug 05, 2021 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | [ffee1e0026](https://linux-hardware.org/?probe=ffee1e0026) | Aug 03, 2021 |
| Dell          | 0J3C2F A00                  | [f557538404](https://linux-hardware.org/?probe=f557538404) | Aug 03, 2021 |
| Dell          | 0J3C2F A00                  | [54a72c496f](https://linux-hardware.org/?probe=54a72c496f) | Aug 03, 2021 |
| Pegatron      | 2AB5                        | [752c8e7000](https://linux-hardware.org/?probe=752c8e7000) | Aug 03, 2021 |
| ASUSTek       | P5QL-E                      | [2894e88095](https://linux-hardware.org/?probe=2894e88095) | Aug 02, 2021 |
| MSI           | MAG B550M MORTAR            | [b5e7cb3f3d](https://linux-hardware.org/?probe=b5e7cb3f3d) | Jul 25, 2021 |
| ASUSTek       | P7H55                       | [44103309b6](https://linux-hardware.org/?probe=44103309b6) | Jul 24, 2021 |
| ASUSTek       | PRIME A320M-K               | [62a0cf7f70](https://linux-hardware.org/?probe=62a0cf7f70) | Jul 21, 2021 |
| Lenovo        | ThinkCentre M58p 3285A1G    | [214c59a169](https://linux-hardware.org/?probe=214c59a169) | Jul 19, 2021 |
| Gigabyte      | GA-890GPA-UD3H              | [3b293f18b7](https://linux-hardware.org/?probe=3b293f18b7) | Jul 18, 2021 |
| ASUSTek       | K30BF_M32BF                 | [c6fa7a1e42](https://linux-hardware.org/?probe=c6fa7a1e42) | Jul 16, 2021 |
| HP            | 3047h                       | [9e162f2640](https://linux-hardware.org/?probe=9e162f2640) | Jul 15, 2021 |
| ASUSTek       | EX-B250-V7                  | [32e09fdf66](https://linux-hardware.org/?probe=32e09fdf66) | Jul 11, 2021 |
| ASUSTek       | PRIME B450M-K II            | [ac44464839](https://linux-hardware.org/?probe=ac44464839) | Jul 10, 2021 |
| ASUSTek       | M3A78-CM                    | [f751fa4ae6](https://linux-hardware.org/?probe=f751fa4ae6) | Jul 04, 2021 |
| HP            | 805B                        | [5d5a6504aa](https://linux-hardware.org/?probe=5d5a6504aa) | Jul 03, 2021 |
| HP            | 805B                        | [83f501a4c5](https://linux-hardware.org/?probe=83f501a4c5) | Jul 03, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [4327921246](https://linux-hardware.org/?probe=4327921246) | Jun 30, 2021 |
| Gigabyte      | Z97X-Gaming GT              | [ca207b7cd3](https://linux-hardware.org/?probe=ca207b7cd3) | Jun 28, 2021 |
| HP            | 2B28                        | [9f9e5ad8f7](https://linux-hardware.org/?probe=9f9e5ad8f7) | Jun 27, 2021 |
| HP            | 2B28                        | [7eb7cb002a](https://linux-hardware.org/?probe=7eb7cb002a) | Jun 27, 2021 |
| Lenovo        | 3176 NOK                    | [9dad112b64](https://linux-hardware.org/?probe=9dad112b64) | Jun 27, 2021 |
| HP            | 3647h                       | [838bf8880c](https://linux-hardware.org/?probe=838bf8880c) | Jun 25, 2021 |
| ASUSTek       | H170-PRO                    | [27b4b0831d](https://linux-hardware.org/?probe=27b4b0831d) | Jun 18, 2021 |
| Gigabyte      | M61PME-S2                   | [528c4990aa](https://linux-hardware.org/?probe=528c4990aa) | Jun 16, 2021 |
| MSI           | B250I PRO                   | [02087ebc8a](https://linux-hardware.org/?probe=02087ebc8a) | Jun 15, 2021 |
| MSI           | B250I PRO                   | [05b0b94ace](https://linux-hardware.org/?probe=05b0b94ace) | Jun 15, 2021 |
| Acer          | Aspire XC-603               | [b8e13ff999](https://linux-hardware.org/?probe=b8e13ff999) | Jun 15, 2021 |
| HP            | 2B28                        | [67c946572f](https://linux-hardware.org/?probe=67c946572f) | Jun 15, 2021 |
| HP            | 2B28                        | [49bcd8e078](https://linux-hardware.org/?probe=49bcd8e078) | Jun 15, 2021 |
| ASUSTek       | M5A99X EVO                  | [6466886164](https://linux-hardware.org/?probe=6466886164) | Jun 06, 2021 |
| ASRock        | H410M-ITX/ac                | [1f2d258849](https://linux-hardware.org/?probe=1f2d258849) | Jun 02, 2021 |
| ASRock        | B450M Pro4                  | [ccd56acb24](https://linux-hardware.org/?probe=ccd56acb24) | May 27, 2021 |
| Gigabyte      | G41MT-S2PT                  | [91eacced05](https://linux-hardware.org/?probe=91eacced05) | May 27, 2021 |
| ASRock        | B450M Pro4                  | [cfb66b647f](https://linux-hardware.org/?probe=cfb66b647f) | May 27, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [8222525f6a](https://linux-hardware.org/?probe=8222525f6a) | May 26, 2021 |
| ASRock        | H110 Pro BTC+               | [947c13ccd9](https://linux-hardware.org/?probe=947c13ccd9) | May 24, 2021 |
| ASRock        | B75M-GL R2.0                | [a51030d9a0](https://linux-hardware.org/?probe=a51030d9a0) | May 22, 2021 |
| HP            | 0B54h D                     | [ee9a2da17c](https://linux-hardware.org/?probe=ee9a2da17c) | May 19, 2021 |
| ASUSTek       | P8H61-M                     | [5d5163972e](https://linux-hardware.org/?probe=5d5163972e) | May 19, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [63da02a979](https://linux-hardware.org/?probe=63da02a979) | May 19, 2021 |
| ASUSTek       | P5N-D                       | [3965d087b0](https://linux-hardware.org/?probe=3965d087b0) | May 17, 2021 |
| MSI           | G41M-P25                    | [57d1c4dafa](https://linux-hardware.org/?probe=57d1c4dafa) | May 16, 2021 |
| ASRock        | H61M-VG4                    | [f99a68e64b](https://linux-hardware.org/?probe=f99a68e64b) | May 14, 2021 |
| HP            | 1850                        | [c904ea417d](https://linux-hardware.org/?probe=c904ea417d) | May 13, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | [8d22fdb15f](https://linux-hardware.org/?probe=8d22fdb15f) | May 12, 2021 |
| ASRock        | H61M-VG4                    | [d2a90378bc](https://linux-hardware.org/?probe=d2a90378bc) | May 12, 2021 |
| Gigabyte      | G31M-ES2L                   | [6a58a91c19](https://linux-hardware.org/?probe=6a58a91c19) | May 11, 2021 |
| Dell          | 00V62H A01                  | [fdac79e308](https://linux-hardware.org/?probe=fdac79e308) | May 10, 2021 |
| Gigabyte      | B460M DS3H V2               | [ee32f4a115](https://linux-hardware.org/?probe=ee32f4a115) | May 07, 2021 |
| Gigabyte      | B460M DS3H V2               | [3ad4ad9793](https://linux-hardware.org/?probe=3ad4ad9793) | May 07, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | [ec56f6327d](https://linux-hardware.org/?probe=ec56f6327d) | May 06, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [223234378e](https://linux-hardware.org/?probe=223234378e) | May 04, 2021 |
| Lenovo        | ThinkCentre M58p 3285A1G    | [0b347a19e2](https://linux-hardware.org/?probe=0b347a19e2) | May 02, 2021 |
| Lenovo        | SDK0J40700 WIN              | [000925bf4b](https://linux-hardware.org/?probe=000925bf4b) | Apr 30, 2021 |
| ASUSTek       | B250 MINING EXPERT          | [4f7a626b9b](https://linux-hardware.org/?probe=4f7a626b9b) | Apr 26, 2021 |
| ASUSTek       | PRIME B450M-A               | [a5d42684da](https://linux-hardware.org/?probe=a5d42684da) | Apr 25, 2021 |
| Gigabyte      | GA-890GPA-UD3H              | [31d974ab0d](https://linux-hardware.org/?probe=31d974ab0d) | Apr 24, 2021 |
| ASUSTek       | Z170-A                      | [0f9a641322](https://linux-hardware.org/?probe=0f9a641322) | Apr 22, 2021 |
| Gigabyte      | GA-73PVM-S2H                | [d8e49fec64](https://linux-hardware.org/?probe=d8e49fec64) | Apr 22, 2021 |
| ASUSTek       | PRIME B450M-A               | [edd61e3d95](https://linux-hardware.org/?probe=edd61e3d95) | Apr 22, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [4198628d9f](https://linux-hardware.org/?probe=4198628d9f) | Apr 22, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [6b7033f43d](https://linux-hardware.org/?probe=6b7033f43d) | Apr 20, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [b5e763d4f7](https://linux-hardware.org/?probe=b5e763d4f7) | Apr 20, 2021 |
| Gigabyte      | EP43-DS3L                   | [105bd71875](https://linux-hardware.org/?probe=105bd71875) | Apr 16, 2021 |
| Gigabyte      | GA-E7AUM-DS2H               | [6c871ab8be](https://linux-hardware.org/?probe=6c871ab8be) | Apr 16, 2021 |
| Lenovo        | Dory CRB                    | [676ace5d71](https://linux-hardware.org/?probe=676ace5d71) | Apr 15, 2021 |
| MSI           | PRESTIGE X570 CREATION      | [26b69278f1](https://linux-hardware.org/?probe=26b69278f1) | Apr 14, 2021 |
| Dell          | 03NVJ6 A00                  | [1dd1d4d667](https://linux-hardware.org/?probe=1dd1d4d667) | Apr 14, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [c294906b60](https://linux-hardware.org/?probe=c294906b60) | Apr 13, 2021 |
| Pegatron      | 2AB5                        | [0a501933e1](https://linux-hardware.org/?probe=0a501933e1) | Apr 13, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | [efb35be24f](https://linux-hardware.org/?probe=efb35be24f) | Apr 13, 2021 |
| Intel         | D525MW AAE93082-401         | [aea7beb5c3](https://linux-hardware.org/?probe=aea7beb5c3) | Apr 12, 2021 |
| Dell          | 0GWHMW A03                  | [a0ff0f4cf3](https://linux-hardware.org/?probe=a0ff0f4cf3) | Apr 08, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [e293d1c2a3](https://linux-hardware.org/?probe=e293d1c2a3) | Apr 07, 2021 |
| Gigabyte      | B450 AORUS M                | [b867fe3dc8](https://linux-hardware.org/?probe=b867fe3dc8) | Apr 06, 2021 |
| MSI           | MS-7418 100                 | [af5ab7c73f](https://linux-hardware.org/?probe=af5ab7c73f) | Apr 06, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [7a299e175f](https://linux-hardware.org/?probe=7a299e175f) | Apr 05, 2021 |
| MSI           | MS-7061                     | [ff8b934f8d](https://linux-hardware.org/?probe=ff8b934f8d) | Mar 31, 2021 |
| HP            | 8299                        | [12120a16f6](https://linux-hardware.org/?probe=12120a16f6) | Mar 30, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | [1b8abaccfb](https://linux-hardware.org/?probe=1b8abaccfb) | Mar 26, 2021 |
| ASUSTek       | Z170-A                      | [53380cdda7](https://linux-hardware.org/?probe=53380cdda7) | Mar 25, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [d40fdda820](https://linux-hardware.org/?probe=d40fdda820) | Mar 25, 2021 |
| ASUSTek       | SABERTOOTH 990FX            | [84c62ff65b](https://linux-hardware.org/?probe=84c62ff65b) | Mar 25, 2021 |
| ASRock        | B75M-GL R2.0                | [2200a1532c](https://linux-hardware.org/?probe=2200a1532c) | Mar 24, 2021 |
| HP            | 21D0                        | [98195974ff](https://linux-hardware.org/?probe=98195974ff) | Mar 24, 2021 |
| Gigabyte      | F2A88XM-D3H                 | [5860ac9ed4](https://linux-hardware.org/?probe=5860ac9ed4) | Mar 21, 2021 |
| Dell          | 0M5DCD A00                  | [39c5751f26](https://linux-hardware.org/?probe=39c5751f26) | Mar 20, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [ffad8b5cba](https://linux-hardware.org/?probe=ffad8b5cba) | Mar 19, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [0cbaa85995](https://linux-hardware.org/?probe=0cbaa85995) | Mar 17, 2021 |
| Biostar       | TB250-BTC PRO               | [e53aecefd9](https://linux-hardware.org/?probe=e53aecefd9) | Mar 17, 2021 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [8e366d0ac5](https://linux-hardware.org/?probe=8e366d0ac5) | Mar 16, 2021 |
| Gigabyte      | G41MT-D3V                   | [38b0010bcd](https://linux-hardware.org/?probe=38b0010bcd) | Mar 14, 2021 |
| ASUSTek       | M4A77T/USB3                 | [878ef5b5a9](https://linux-hardware.org/?probe=878ef5b5a9) | Mar 14, 2021 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [a837738425](https://linux-hardware.org/?probe=a837738425) | Mar 12, 2021 |
| Lenovo        | ThinkCentre M58p 3285A1G    | [82a9fbf842](https://linux-hardware.org/?probe=82a9fbf842) | Mar 10, 2021 |
| Gigabyte      | H61M-S2V-B3                 | [b0a0929002](https://linux-hardware.org/?probe=b0a0929002) | Mar 09, 2021 |
| ASRock        | B75M-GL R2.0                | [5737dda498](https://linux-hardware.org/?probe=5737dda498) | Mar 06, 2021 |
| Gigabyte      | F2A85X-UP4                  | [d75d9b7907](https://linux-hardware.org/?probe=d75d9b7907) | Mar 05, 2021 |
| HP            | 8299                        | [e8e31dfc6e](https://linux-hardware.org/?probe=e8e31dfc6e) | Mar 01, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [d35de9f29e](https://linux-hardware.org/?probe=d35de9f29e) | Feb 28, 2021 |
| Fujitsu       | D3024-A1 S26361-D3024-A1    | [00cab9c594](https://linux-hardware.org/?probe=00cab9c594) | Feb 28, 2021 |
| Pegatron      | 2AB5                        | [3026ac5e90](https://linux-hardware.org/?probe=3026ac5e90) | Feb 27, 2021 |
| Pegatron      | 2AB5                        | [de86804d84](https://linux-hardware.org/?probe=de86804d84) | Feb 27, 2021 |
| ASUSTek       | B150 PRO GAMING/AURA        | [5ebac513c1](https://linux-hardware.org/?probe=5ebac513c1) | Feb 26, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [94d8e7faa5](https://linux-hardware.org/?probe=94d8e7faa5) | Feb 26, 2021 |
| ASUSTek       | P5Q SE PLUS                 | [3c13afb411](https://linux-hardware.org/?probe=3c13afb411) | Feb 25, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | [55cfaaee1b](https://linux-hardware.org/?probe=55cfaaee1b) | Feb 22, 2021 |
| ASUSTek       | M4N78 SE                    | [da1fd4246e](https://linux-hardware.org/?probe=da1fd4246e) | Feb 22, 2021 |
| Gigabyte      | MZAPLBP-00                  | [150d692c9a](https://linux-hardware.org/?probe=150d692c9a) | Feb 16, 2021 |
| Biostar       | TB250-BTC PRO               | [b0d416dfbc](https://linux-hardware.org/?probe=b0d416dfbc) | Feb 16, 2021 |
| ASUSTek       | P5Q SE PLUS                 | [40dd819b23](https://linux-hardware.org/?probe=40dd819b23) | Feb 15, 2021 |
| Gigabyte      | X570 GAMING X               | [4b0521d0ee](https://linux-hardware.org/?probe=4b0521d0ee) | Feb 14, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [23ecc9c16e](https://linux-hardware.org/?probe=23ecc9c16e) | Feb 13, 2021 |
| Gigabyte      | H81M-S2PV                   | [a94647b020](https://linux-hardware.org/?probe=a94647b020) | Feb 12, 2021 |
| MSI           | B350 TOMAHAWK               | [fae8d202da](https://linux-hardware.org/?probe=fae8d202da) | Feb 12, 2021 |
| Gigabyte      | H81M-S2PV                   | [d822d59913](https://linux-hardware.org/?probe=d822d59913) | Feb 12, 2021 |
| ASUSTek       | P5Q SE PLUS                 | [2ef8a250d3](https://linux-hardware.org/?probe=2ef8a250d3) | Feb 07, 2021 |
| ASRock        | H81 Pro BTC R2.0            | [aae7eb09bf](https://linux-hardware.org/?probe=aae7eb09bf) | Feb 06, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [36c87ef485](https://linux-hardware.org/?probe=36c87ef485) | Feb 03, 2021 |
| Intel         | DB75EN AAG39650-400         | [706a8c3c73](https://linux-hardware.org/?probe=706a8c3c73) | Feb 03, 2021 |
| ASRock        | G41C-GS                     | [47cbf95a16](https://linux-hardware.org/?probe=47cbf95a16) | Feb 02, 2021 |
| ASUSTek       | PRIME A320M-R               | [3a99ca2e3a](https://linux-hardware.org/?probe=3a99ca2e3a) | Feb 01, 2021 |
| ASUSTek       | PRIME A320M-R               | [0a61c5b666](https://linux-hardware.org/?probe=0a61c5b666) | Feb 01, 2021 |
| HP            | 8299                        | [16e50ec1cd](https://linux-hardware.org/?probe=16e50ec1cd) | Jan 31, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [a51a715f7b](https://linux-hardware.org/?probe=a51a715f7b) | Jan 30, 2021 |
| Gigabyte      | B360M D3H-CF                | [a01fc6e6fc](https://linux-hardware.org/?probe=a01fc6e6fc) | Jan 28, 2021 |
| Gigabyte      | 970A-DS3P                   | [8405804af1](https://linux-hardware.org/?probe=8405804af1) | Jan 26, 2021 |
| ASUSTek       | P5Q SE PLUS                 | [386196c0dd](https://linux-hardware.org/?probe=386196c0dd) | Jan 26, 2021 |
| Gigabyte      | GA-A75M-UD2H                | [f428258e3c](https://linux-hardware.org/?probe=f428258e3c) | Jan 26, 2021 |
| Intel         | DB75EN AAG39650-400         | [f5b2931f56](https://linux-hardware.org/?probe=f5b2931f56) | Jan 26, 2021 |
| Intel         | DB75EN AAG39650-400         | [daaa93aeda](https://linux-hardware.org/?probe=daaa93aeda) | Jan 26, 2021 |
| Gigabyte      | GA-A75M-UD2H                | [353cfbeabe](https://linux-hardware.org/?probe=353cfbeabe) | Jan 26, 2021 |
| HP            | 0AA8h                       | [3a726e28e4](https://linux-hardware.org/?probe=3a726e28e4) | Jan 23, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [f950b8cb2c](https://linux-hardware.org/?probe=f950b8cb2c) | Jan 23, 2021 |
| ASRock        | B450 Pro4                   | [7177dfdace](https://linux-hardware.org/?probe=7177dfdace) | Jan 23, 2021 |
| ASUSTek       | P8Z77-V LK                  | [39bb07129a](https://linux-hardware.org/?probe=39bb07129a) | Jan 21, 2021 |
| Lenovo        | MAHOBAY NOK                 | [e6246a62eb](https://linux-hardware.org/?probe=e6246a62eb) | Jan 20, 2021 |
| ASRock        | B450M Pro4-F                | [8f063fe8f1](https://linux-hardware.org/?probe=8f063fe8f1) | Jan 19, 2021 |
| ASRock        | B450M Pro4-F                | [5a83f4c70e](https://linux-hardware.org/?probe=5a83f4c70e) | Jan 19, 2021 |
| ASUSTek       | P5W DH Deluxe               | [177818b63b](https://linux-hardware.org/?probe=177818b63b) | Jan 19, 2021 |
| ASUSTek       | M4A77TD                     | [8dff00cfff](https://linux-hardware.org/?probe=8dff00cfff) | Jan 18, 2021 |
| ASRock        | B75M-GL R2.0                | [79848dc213](https://linux-hardware.org/?probe=79848dc213) | Jan 17, 2021 |
| Gigabyte      | B550M AORUS ELITE           | [f26799f89e](https://linux-hardware.org/?probe=f26799f89e) | Jan 17, 2021 |
| MSI           | 970A-G46                    | [139738eab5](https://linux-hardware.org/?probe=139738eab5) | Jan 16, 2021 |
| ASRock        | B75M-GL R2.0                | [16ded24529](https://linux-hardware.org/?probe=16ded24529) | Jan 15, 2021 |
| Gigabyte      | 970A-DS3P                   | [beaa31df09](https://linux-hardware.org/?probe=beaa31df09) | Jan 14, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [e10979867d](https://linux-hardware.org/?probe=e10979867d) | Jan 13, 2021 |
| MSI           | IONA                        | [d28e052ec6](https://linux-hardware.org/?probe=d28e052ec6) | Jan 10, 2021 |
| ASRock        | AB350M Pro4                 | [b75dcb6545](https://linux-hardware.org/?probe=b75dcb6545) | Jan 05, 2021 |
| MSI           | MS-7061                     | [5701f637e7](https://linux-hardware.org/?probe=5701f637e7) | Jan 04, 2021 |
| ASRock        | B75M-GL R2.0                | [0c506c630e](https://linux-hardware.org/?probe=0c506c630e) | Jan 02, 2021 |
| Dell          | 0T10XW A01                  | [7170404b87](https://linux-hardware.org/?probe=7170404b87) | Dec 31, 2020 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [3994a22935](https://linux-hardware.org/?probe=3994a22935) | Dec 27, 2020 |
| Intel         | DQ67OW AAG12528-309         | [5f42b365ae](https://linux-hardware.org/?probe=5f42b365ae) | Dec 26, 2020 |
| ASUSTek       | PRIME X570-P                | [d5fa351273](https://linux-hardware.org/?probe=d5fa351273) | Dec 26, 2020 |
| Gigabyte      | H77M-D3H                    | [fa8a07845c](https://linux-hardware.org/?probe=fa8a07845c) | Dec 25, 2020 |
| Gigabyte      | H77M-D3H                    | [edb4c27530](https://linux-hardware.org/?probe=edb4c27530) | Dec 24, 2020 |
| ASUSTek       | P5G41T-M LX                 | [14e569e26c](https://linux-hardware.org/?probe=14e569e26c) | Dec 20, 2020 |
| HP            | 18E7                        | [a84ff44872](https://linux-hardware.org/?probe=a84ff44872) | Dec 20, 2020 |
| ASRock        | B75M-GL R2.0                | [91c33b15fe](https://linux-hardware.org/?probe=91c33b15fe) | Dec 18, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [94b7599bed](https://linux-hardware.org/?probe=94b7599bed) | Dec 16, 2020 |
| ASUSTek       | M2N-E                       | [8fa83ff1f4](https://linux-hardware.org/?probe=8fa83ff1f4) | Dec 16, 2020 |
| ASUSTek       | M2N-E                       | [6a68ea590f](https://linux-hardware.org/?probe=6a68ea590f) | Dec 15, 2020 |
| ASUSTek       | M2N-E                       | [5b0148344f](https://linux-hardware.org/?probe=5b0148344f) | Dec 15, 2020 |
| MSI           | IONA                        | [e0c6ee5ff1](https://linux-hardware.org/?probe=e0c6ee5ff1) | Dec 15, 2020 |
| Gigabyte      | EG41MF-S2H                  | [81d8b34e8e](https://linux-hardware.org/?probe=81d8b34e8e) | Dec 14, 2020 |
| ASUSTek       | M5A97 LE R2.0               | [8f96733244](https://linux-hardware.org/?probe=8f96733244) | Dec 13, 2020 |
| MSI           | MPG B550I GAMING EDGE WI... | [f86eaf1968](https://linux-hardware.org/?probe=f86eaf1968) | Dec 12, 2020 |
| Gigabyte      | F2A88XM-D3HP                | [a767404d0e](https://linux-hardware.org/?probe=a767404d0e) | Dec 12, 2020 |
| Gigabyte      | F2A88XM-D3HP                | [5edf82c417](https://linux-hardware.org/?probe=5edf82c417) | Dec 12, 2020 |
| ASRock        | B75M-GL R2.0                | [b083b46acb](https://linux-hardware.org/?probe=b083b46acb) | Dec 10, 2020 |
| ASUSTek       | M5A97 LE R2.0               | [a1c00e55f5](https://linux-hardware.org/?probe=a1c00e55f5) | Dec 08, 2020 |
| ASUSTek       | M5A97 LE R2.0               | [8572ec4934](https://linux-hardware.org/?probe=8572ec4934) | Dec 08, 2020 |
| ASUSTek       | P8Z77-V LK                  | [99ba99aa39](https://linux-hardware.org/?probe=99ba99aa39) | Dec 06, 2020 |
| ASUSTek       | B150M PRO GAMING            | [4d4ec823bb](https://linux-hardware.org/?probe=4d4ec823bb) | Dec 06, 2020 |
| HP            | 1905                        | [6690d08a07](https://linux-hardware.org/?probe=6690d08a07) | Dec 04, 2020 |
| MSI           | H81M-P33                    | [9c614066cc](https://linux-hardware.org/?probe=9c614066cc) | Dec 03, 2020 |
| ASUSTek       | B150M PRO GAMING            | [7d1a0b6924](https://linux-hardware.org/?probe=7d1a0b6924) | Dec 02, 2020 |
| ASUSTek       | M5A78L/USB3                 | [80ed74b9e9](https://linux-hardware.org/?probe=80ed74b9e9) | Dec 02, 2020 |
| HP            | 8618                        | [91f724f25b](https://linux-hardware.org/?probe=91f724f25b) | Nov 25, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [7e1033e8f3](https://linux-hardware.org/?probe=7e1033e8f3) | Nov 22, 2020 |
| ASUSTek       | B150M PRO GAMING            | [a49a6f5cd0](https://linux-hardware.org/?probe=a49a6f5cd0) | Nov 20, 2020 |
| ASUSTek       | B150M PRO GAMING            | [6b203577af](https://linux-hardware.org/?probe=6b203577af) | Nov 20, 2020 |
| ASUSTek       | H110M-K                     | [985b5c933d](https://linux-hardware.org/?probe=985b5c933d) | Nov 20, 2020 |
| Gigabyte      | GA-73PVM-S2H                | [a706435b39](https://linux-hardware.org/?probe=a706435b39) | Nov 20, 2020 |
| MSI           | Z97 GAMING 7                | [c1e3c06f22](https://linux-hardware.org/?probe=c1e3c06f22) | Nov 20, 2020 |
| ASRock        | B75M-GL R2.0                | [1c9a604ba6](https://linux-hardware.org/?probe=1c9a604ba6) | Nov 20, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [b536f1bb57](https://linux-hardware.org/?probe=b536f1bb57) | Nov 19, 2020 |
| ASRock        | AB350 Pro4                  | [c8af4ac482](https://linux-hardware.org/?probe=c8af4ac482) | Nov 18, 2020 |
| ASUSTek       | M5A97 R2.0                  | [bbd45f8b19](https://linux-hardware.org/?probe=bbd45f8b19) | Nov 17, 2020 |
| Gigabyte      | 970A-DS3P                   | [5e2da261c7](https://linux-hardware.org/?probe=5e2da261c7) | Nov 14, 2020 |
| ASUSTek       | PRIME B350-PLUS             | [0bd4668348](https://linux-hardware.org/?probe=0bd4668348) | Nov 13, 2020 |
| Gigabyte      | GA-990FXA-D3                | [9f86ed3e72](https://linux-hardware.org/?probe=9f86ed3e72) | Nov 13, 2020 |
| Dell          | 0DR845                      | [fdc86c4e1a](https://linux-hardware.org/?probe=fdc86c4e1a) | Nov 10, 2020 |
| ASUSTek       | M2A-VM HDMI                 | [df7527ce9d](https://linux-hardware.org/?probe=df7527ce9d) | Nov 08, 2020 |
| Dell          | 0HR330                      | [6c239e76c2](https://linux-hardware.org/?probe=6c239e76c2) | Nov 07, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [233cd75348](https://linux-hardware.org/?probe=233cd75348) | Nov 05, 2020 |
| Gigabyte      | H81ND2H                     | [5d76ba9ebd](https://linux-hardware.org/?probe=5d76ba9ebd) | Oct 31, 2020 |
| Gigabyte      | B550 GAMING X               | [c78aeb9bad](https://linux-hardware.org/?probe=c78aeb9bad) | Oct 28, 2020 |
| Gigabyte      | B450M S2H                   | [4ef991873c](https://linux-hardware.org/?probe=4ef991873c) | Oct 26, 2020 |
| MSI           | X370 GAMING PLUS            | [66088ce191](https://linux-hardware.org/?probe=66088ce191) | Oct 20, 2020 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [04aed365e7](https://linux-hardware.org/?probe=04aed365e7) | Oct 18, 2020 |
| Acer          | EM61SM/EM61PM               | [d123fda7a8](https://linux-hardware.org/?probe=d123fda7a8) | Oct 16, 2020 |
| Unknown       | Unknown                     | [0dbef68451](https://linux-hardware.org/?probe=0dbef68451) | Oct 15, 2020 |
| MSI           | X370 GAMING PLUS            | [46840b02f0](https://linux-hardware.org/?probe=46840b02f0) | Oct 14, 2020 |
| HP            | 1905                        | [0e53545ff8](https://linux-hardware.org/?probe=0e53545ff8) | Oct 14, 2020 |
| MSI           | X470 GAMING PRO CARBON      | [fca58ff529](https://linux-hardware.org/?probe=fca58ff529) | Oct 13, 2020 |
| Acer          | Aspire GX-781               | [159afb32c1](https://linux-hardware.org/?probe=159afb32c1) | Oct 10, 2020 |
| Gigabyte      | X570 AORUS ULTRA            | [80079c46e3](https://linux-hardware.org/?probe=80079c46e3) | Oct 10, 2020 |
| Intel         | D946GZIS AAD66165-301       | [bb231aa749](https://linux-hardware.org/?probe=bb231aa749) | Oct 09, 2020 |
| Intel         | D946GZIS AAD66165-301       | [a89dffe004](https://linux-hardware.org/?probe=a89dffe004) | Oct 09, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [95a78ff474](https://linux-hardware.org/?probe=95a78ff474) | Oct 08, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [d01a07b619](https://linux-hardware.org/?probe=d01a07b619) | Oct 08, 2020 |
| ASUSTek       | Maximus VII HERO            | [13fa4df109](https://linux-hardware.org/?probe=13fa4df109) | Oct 08, 2020 |
| Gigabyte      | P55A-UD3                    | [46ebc8c075](https://linux-hardware.org/?probe=46ebc8c075) | Oct 06, 2020 |
| HP            | 1998                        | [8d941cca29](https://linux-hardware.org/?probe=8d941cca29) | Oct 05, 2020 |
| Gigabyte      | B460M DS3H                  | [c607051cd6](https://linux-hardware.org/?probe=c607051cd6) | Oct 04, 2020 |
| Gigabyte      | B460M DS3H                  | [a96b9c0e32](https://linux-hardware.org/?probe=a96b9c0e32) | Oct 04, 2020 |
| ASRock        | N68-S                       | [e867c049a3](https://linux-hardware.org/?probe=e867c049a3) | Sep 30, 2020 |
| ASRock        | N68-S                       | [5e39fce3e2](https://linux-hardware.org/?probe=5e39fce3e2) | Sep 30, 2020 |
| MSI           | 870-C45                     | [0c99fa95e9](https://linux-hardware.org/?probe=0c99fa95e9) | Sep 28, 2020 |
| HP            | 843B                        | [759b4e1098](https://linux-hardware.org/?probe=759b4e1098) | Sep 28, 2020 |
| HP            | 1905                        | [48fd57f60f](https://linux-hardware.org/?probe=48fd57f60f) | Sep 24, 2020 |
| HP            | 1905                        | [0e2d6062d9](https://linux-hardware.org/?probe=0e2d6062d9) | Sep 24, 2020 |
| HP            | 843F                        | [6f9898a049](https://linux-hardware.org/?probe=6f9898a049) | Sep 24, 2020 |
| ASRock        | AB350M Pro4                 | [6cd6f20aef](https://linux-hardware.org/?probe=6cd6f20aef) | Sep 22, 2020 |
| Gigabyte      | F2A88X-D3H                  | [2c385e1a66](https://linux-hardware.org/?probe=2c385e1a66) | Sep 20, 2020 |
| ASUSTek       | TUF B450-PLUS GAMING        | [1699708a5b](https://linux-hardware.org/?probe=1699708a5b) | Sep 20, 2020 |
| ASRock        | 980DE3/U3S3 R2.0            | [8bfe52a7d7](https://linux-hardware.org/?probe=8bfe52a7d7) | Sep 19, 2020 |
| HP            | 843F                        | [91498f153e](https://linux-hardware.org/?probe=91498f153e) | Sep 18, 2020 |
| Gigabyte      | P67A-D3-B3                  | [c5a9bb91be](https://linux-hardware.org/?probe=c5a9bb91be) | Sep 15, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [2399ed18fd](https://linux-hardware.org/?probe=2399ed18fd) | Sep 14, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [73d7e76e09](https://linux-hardware.org/?probe=73d7e76e09) | Sep 11, 2020 |
| Lenovo        | 1036 SDK0Q40104 WIN 3305... | [9ccc9861eb](https://linux-hardware.org/?probe=9ccc9861eb) | Sep 10, 2020 |
| Lenovo        | Bantry CRB 31900058 STD     | [bcc958126a](https://linux-hardware.org/?probe=bcc958126a) | Sep 03, 2020 |
| Gigabyte      | X570 AORUS PRO              | [0295f343f4](https://linux-hardware.org/?probe=0295f343f4) | Sep 03, 2020 |
| ASRock        | B450M Pro4                  | [1975c693cb](https://linux-hardware.org/?probe=1975c693cb) | Sep 02, 2020 |
| Gigabyte      | H170-HD3 DDR3-CF            | [b48f1779ec](https://linux-hardware.org/?probe=b48f1779ec) | Aug 30, 2020 |
| Gigabyte      | P67A-D3-B3                  | [f5f3758bed](https://linux-hardware.org/?probe=f5f3758bed) | Aug 30, 2020 |
| MSI           | B460M PRO-VDH WIFI          | [e53f585923](https://linux-hardware.org/?probe=e53f585923) | Aug 30, 2020 |
| Gigabyte      | 970A-DS3P                   | [557964d138](https://linux-hardware.org/?probe=557964d138) | Aug 29, 2020 |
| Gigabyte      | 970A-DS3P                   | [37dc85cc8b](https://linux-hardware.org/?probe=37dc85cc8b) | Aug 29, 2020 |
| Gigabyte      | F2A88X-D3H                  | [4d58eb3965](https://linux-hardware.org/?probe=4d58eb3965) | Aug 27, 2020 |
| MSI           | A320M PRO-VD/S              | [febc06a11a](https://linux-hardware.org/?probe=febc06a11a) | Aug 25, 2020 |
| ASUSTek       | PRIME Z390-A                | [e7c4cf1576](https://linux-hardware.org/?probe=e7c4cf1576) | Aug 23, 2020 |
| ASUSTek       | PRIME X399-A                | [8d0d4f27be](https://linux-hardware.org/?probe=8d0d4f27be) | Aug 22, 2020 |
| Dell          | 073MMW A01                  | [c9cc3e1a0f](https://linux-hardware.org/?probe=c9cc3e1a0f) | Aug 20, 2020 |
| MSI           | B350 TOMAHAWK               | [51ef1db220](https://linux-hardware.org/?probe=51ef1db220) | Aug 20, 2020 |
| Pegatron      | 2A73h                       | [9754808d3d](https://linux-hardware.org/?probe=9754808d3d) | Aug 20, 2020 |
| MSI           | B350 GAMING PRO CARBON      | [762b0fed7b](https://linux-hardware.org/?probe=762b0fed7b) | Aug 18, 2020 |
| ASUSTek       | P8H67-M PRO                 | [7b143c1637](https://linux-hardware.org/?probe=7b143c1637) | Aug 13, 2020 |
| HP            | 806A                        | [9b5a07dcd9](https://linux-hardware.org/?probe=9b5a07dcd9) | Aug 08, 2020 |
| ASRock        | X570 Extreme4               | [f946f61a7b](https://linux-hardware.org/?probe=f946f61a7b) | Jul 29, 2020 |
| Intel         | DCP847SKE G80890-104        | [33d9cddf98](https://linux-hardware.org/?probe=33d9cddf98) | Jul 28, 2020 |
| HP            | 1495                        | [8a51ce66a3](https://linux-hardware.org/?probe=8a51ce66a3) | Jul 27, 2020 |
| Gigabyte      | Z170-HD3P-CF                | [f37d0fb96a](https://linux-hardware.org/?probe=f37d0fb96a) | Jul 26, 2020 |
| Gigabyte      | Z77-DS3H                    | [e7f8121d46](https://linux-hardware.org/?probe=e7f8121d46) | Jul 22, 2020 |
| Intel         | DG33TL AAD89517-803         | [b50a829b37](https://linux-hardware.org/?probe=b50a829b37) | Jul 19, 2020 |
| ASUSTek       | PRIME B450-PLUS             | [300e34bdff](https://linux-hardware.org/?probe=300e34bdff) | Jul 17, 2020 |
| HP            | 843F                        | [e0bdf38c8a](https://linux-hardware.org/?probe=e0bdf38c8a) | Jul 16, 2020 |
| ASUSTek       | M5A97 LE R2.0               | [2a545cac20](https://linux-hardware.org/?probe=2a545cac20) | Jul 16, 2020 |
| ASUSTek       | M5A97 LE R2.0               | [7e5966439c](https://linux-hardware.org/?probe=7e5966439c) | Jul 16, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [68e6b713ca](https://linux-hardware.org/?probe=68e6b713ca) | Jul 14, 2020 |
| Gigabyte      | GA-M56S-S3                  | [7e2596c52f](https://linux-hardware.org/?probe=7e2596c52f) | Jul 12, 2020 |
| MSI           | MS-7061                     | [ec0257fb90](https://linux-hardware.org/?probe=ec0257fb90) | Jul 11, 2020 |
| MSI           | MS-7061                     | [5c76906c4c](https://linux-hardware.org/?probe=5c76906c4c) | Jul 11, 2020 |
| Packard Be... | PT890-8237A                 | [089d020111](https://linux-hardware.org/?probe=089d020111) | Jul 08, 2020 |
| Intel         | DG33TL AAD89517-803         | [5b3d9f328a](https://linux-hardware.org/?probe=5b3d9f328a) | Jul 03, 2020 |
| ASUSTek       | PRIME H410M-E               | [f033f59c7f](https://linux-hardware.org/?probe=f033f59c7f) | Jul 03, 2020 |
| Intel         | DG33TL AAD89517-803         | [2b1fcc4155](https://linux-hardware.org/?probe=2b1fcc4155) | Jul 03, 2020 |
| ASUSTek       | P5K-E                       | [5923c246c4](https://linux-hardware.org/?probe=5923c246c4) | Jun 30, 2020 |
| ASUSTek       | P5G41T-M LX                 | [dcdaf862fd](https://linux-hardware.org/?probe=dcdaf862fd) | Jun 28, 2020 |
| ASRock        | 970M Pro3                   | [98ee7025f4](https://linux-hardware.org/?probe=98ee7025f4) | Jun 27, 2020 |
| Acer          | EM61SM/EM61PM               | [c7523734df](https://linux-hardware.org/?probe=c7523734df) | Jun 26, 2020 |
| ASRock        | 960GC-GS FX                 | [f31e3e1831](https://linux-hardware.org/?probe=f31e3e1831) | Jun 24, 2020 |
| ASRock        | 960GC-GS FX                 | [b5cf346e5d](https://linux-hardware.org/?probe=b5cf346e5d) | Jun 23, 2020 |
| ASUSTek       | M2R-FVM                     | [e6ee210f6d](https://linux-hardware.org/?probe=e6ee210f6d) | Jun 23, 2020 |
| Gigabyte      | H55M-USB3                   | [6e57629563](https://linux-hardware.org/?probe=6e57629563) | Jun 22, 2020 |
| ASUSTek       | Crosshair IV Formula        | [51b8e4300b](https://linux-hardware.org/?probe=51b8e4300b) | Jun 20, 2020 |
| ASUSTek       | Crosshair IV Formula        | [e1184552d0](https://linux-hardware.org/?probe=e1184552d0) | Jun 20, 2020 |
| ASUSTek       | M2R-FVM                     | [33713a0404](https://linux-hardware.org/?probe=33713a0404) | Jun 18, 2020 |
| ASUSTek       | A55BM-E                     | [ff4c765cf8](https://linux-hardware.org/?probe=ff4c765cf8) | Jun 15, 2020 |
| Pegatron      | 2A73h                       | [fa273cd6e3](https://linux-hardware.org/?probe=fa273cd6e3) | Jun 14, 2020 |
| Pegatron      | 2A73h                       | [bdbf5c3068](https://linux-hardware.org/?probe=bdbf5c3068) | Jun 14, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [b9a88cd7cf](https://linux-hardware.org/?probe=b9a88cd7cf) | Jun 13, 2020 |
| HP            | 1495                        | [c9c1099add](https://linux-hardware.org/?probe=c9c1099add) | Jun 12, 2020 |
| Gigabyte      | GA-MA790XT-UD4P             | [62b8ebc9dc](https://linux-hardware.org/?probe=62b8ebc9dc) | Jun 11, 2020 |
| Gigabyte      | GA-MA78LMT-US2H             | [1d365cfa28](https://linux-hardware.org/?probe=1d365cfa28) | Jun 08, 2020 |
| Gigabyte      | GA-MA790XT-UD4P             | [0d9a285392](https://linux-hardware.org/?probe=0d9a285392) | Jun 05, 2020 |
| ASRock        | 980DE3/U3S3                 | [146b8e892a](https://linux-hardware.org/?probe=146b8e892a) | Jun 05, 2020 |
| ASUSTek       | M2A-VM HDMI                 | [ee9f7329ff](https://linux-hardware.org/?probe=ee9f7329ff) | May 31, 2020 |
| ASUSTek       | M2A-VM HDMI                 | [911a12baa7](https://linux-hardware.org/?probe=911a12baa7) | May 31, 2020 |
| ASRock        | AB350 Pro4                  | [5d11e43736](https://linux-hardware.org/?probe=5d11e43736) | May 30, 2020 |
| Gigabyte      | B450 AORUS M                | [a25818fe46](https://linux-hardware.org/?probe=a25818fe46) | May 30, 2020 |
| Acer          | Aspire XC-830               | [b260486efb](https://linux-hardware.org/?probe=b260486efb) | May 29, 2020 |
| Acer          | Aspire XC-830               | [90501ddf39](https://linux-hardware.org/?probe=90501ddf39) | May 27, 2020 |
| Acer          | Aspire XC-830               | [bb81a1b4c7](https://linux-hardware.org/?probe=bb81a1b4c7) | May 27, 2020 |
| ASUSTek       | P5QL PRO                    | [cd5a927598](https://linux-hardware.org/?probe=cd5a927598) | May 26, 2020 |
| ASRock        | Z97 Anniversary             | [9182b64cda](https://linux-hardware.org/?probe=9182b64cda) | May 25, 2020 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [d8ecbfe382](https://linux-hardware.org/?probe=d8ecbfe382) | May 23, 2020 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [e02d9dc211](https://linux-hardware.org/?probe=e02d9dc211) | May 23, 2020 |
| MSI           | Z270 KRAIT GAMING           | [b51348e9b8](https://linux-hardware.org/?probe=b51348e9b8) | May 22, 2020 |
| ASUSTek       | M2N-CM DVI                  | [e2c38feac9](https://linux-hardware.org/?probe=e2c38feac9) | May 19, 2020 |
| ASUSTek       | PRIME B450M-K               | [8fd77159e9](https://linux-hardware.org/?probe=8fd77159e9) | May 19, 2020 |
| HP            | 304Ah                       | [c27cabd96c](https://linux-hardware.org/?probe=c27cabd96c) | May 19, 2020 |
| HP            | 304Ah                       | [c6d530a3fb](https://linux-hardware.org/?probe=c6d530a3fb) | May 19, 2020 |
| ASRock        | B75M-GL R2.0                | [5d07d6db8e](https://linux-hardware.org/?probe=5d07d6db8e) | May 17, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [96677ee210](https://linux-hardware.org/?probe=96677ee210) | May 16, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [15d0451825](https://linux-hardware.org/?probe=15d0451825) | May 16, 2020 |
| Gigabyte      | M61SME-S2                   | [bd4b1dc757](https://linux-hardware.org/?probe=bd4b1dc757) | May 12, 2020 |
| ASUSTek       | Z97M-PLUS                   | [1523e8f4a8](https://linux-hardware.org/?probe=1523e8f4a8) | May 11, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [6237c4cae4](https://linux-hardware.org/?probe=6237c4cae4) | May 10, 2020 |
| ASRock        | H81M-HDS R2.0               | [c2edd5fbaf](https://linux-hardware.org/?probe=c2edd5fbaf) | May 09, 2020 |
| MSI           | MPG X570 GAMING EDGE WIF... | [ada5fbf86d](https://linux-hardware.org/?probe=ada5fbf86d) | May 03, 2020 |
| MSI           | MS-7507                     | [120f09865e](https://linux-hardware.org/?probe=120f09865e) | Apr 30, 2020 |
| Gigabyte      | N3050ND3H                   | [3f7cfb988e](https://linux-hardware.org/?probe=3f7cfb988e) | Apr 29, 2020 |
| Acer          | EM61SM/EM61PM               | [94e7ff927b](https://linux-hardware.org/?probe=94e7ff927b) | Apr 27, 2020 |
| Acer          | EM61SM/EM61PM               | [8b0fba21d2](https://linux-hardware.org/?probe=8b0fba21d2) | Apr 27, 2020 |
| MSI           | B360M MORTAR                | [d2215c28af](https://linux-hardware.org/?probe=d2215c28af) | Apr 26, 2020 |
| HP            | 339A                        | [a4b2a57cc3](https://linux-hardware.org/?probe=a4b2a57cc3) | Apr 25, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [87b901a1b9](https://linux-hardware.org/?probe=87b901a1b9) | Apr 23, 2020 |
| Gigabyte      | 990FXA-UD3                  | [ffe9b12dd4](https://linux-hardware.org/?probe=ffe9b12dd4) | Apr 23, 2020 |
| MSI           | MS-7267                     | [678e22693c](https://linux-hardware.org/?probe=678e22693c) | Apr 21, 2020 |
| Gigabyte      | AX370-Gaming 5              | [a1ba861a3d](https://linux-hardware.org/?probe=a1ba861a3d) | Apr 20, 2020 |
| Gigabyte      | EG41MF-US2H                 | [695ccb4b40](https://linux-hardware.org/?probe=695ccb4b40) | Apr 18, 2020 |
| Intel         | DP35DP AAD81073-207         | [43157cc32b](https://linux-hardware.org/?probe=43157cc32b) | Apr 18, 2020 |
| ASUSTek       | TUF B450M-PRO GAMING        | [17ba5a84d9](https://linux-hardware.org/?probe=17ba5a84d9) | Apr 12, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [64f6604a82](https://linux-hardware.org/?probe=64f6604a82) | Apr 06, 2020 |
| MSI           | B150 GAMING M3              | [c5221a134d](https://linux-hardware.org/?probe=c5221a134d) | Apr 06, 2020 |
| MSI           | B150 GAMING M3              | [4d2bcc0613](https://linux-hardware.org/?probe=4d2bcc0613) | Apr 06, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [848a63637f](https://linux-hardware.org/?probe=848a63637f) | Apr 01, 2020 |
| ASUSTek       | P5G41-M LX2/GB/LPT          | [736d155f37](https://linux-hardware.org/?probe=736d155f37) | Mar 30, 2020 |
| ASUSTek       | P5G41-M LX2/GB/LPT          | [b8b840e5a5](https://linux-hardware.org/?probe=b8b840e5a5) | Mar 30, 2020 |
| Gigabyte      | GA-MA78LMT-S2               | [4a2233bf6d](https://linux-hardware.org/?probe=4a2233bf6d) | Mar 29, 2020 |
| MSI           | MS-7357                     | [dd315713e7](https://linux-hardware.org/?probe=dd315713e7) | Mar 28, 2020 |
| Gigabyte      | M68MT-S2                    | [ab1ea8323a](https://linux-hardware.org/?probe=ab1ea8323a) | Mar 27, 2020 |
| MSI           | X370 GAMING PRO CARBON A... | [79c8660f50](https://linux-hardware.org/?probe=79c8660f50) | Mar 26, 2020 |
| Gigabyte      | Z77-D3H                     | [6188581fde](https://linux-hardware.org/?probe=6188581fde) | Mar 25, 2020 |
| Intel         | DG43RK AAE78175-402         | [262ba9568a](https://linux-hardware.org/?probe=262ba9568a) | Mar 22, 2020 |
| Gigabyte      | EG41MF-US2H                 | [3454a872c0](https://linux-hardware.org/?probe=3454a872c0) | Mar 22, 2020 |
| Gigabyte      | N3050ND3H                   | [9306c157ae](https://linux-hardware.org/?probe=9306c157ae) | Mar 16, 2020 |
| ASUSTek       | B85M-G                      | [bfb2fb34f1](https://linux-hardware.org/?probe=bfb2fb34f1) | Mar 16, 2020 |
| Gigabyte      | G31M-ES2L                   | [e7634e66cc](https://linux-hardware.org/?probe=e7634e66cc) | Mar 14, 2020 |
| MSI           | H81M-P33                    | [6727ba0937](https://linux-hardware.org/?probe=6727ba0937) | Mar 12, 2020 |
| HP            | 843F                        | [f76a18754d](https://linux-hardware.org/?probe=f76a18754d) | Mar 12, 2020 |
| MSI           | NF520T-C35                  | [e9c434add5](https://linux-hardware.org/?probe=e9c434add5) | Mar 11, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [6f3950f01a](https://linux-hardware.org/?probe=6f3950f01a) | Mar 11, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [5aad033c6b](https://linux-hardware.org/?probe=5aad033c6b) | Mar 11, 2020 |
| Gigabyte      | N3050ND3H                   | [531eedbf04](https://linux-hardware.org/?probe=531eedbf04) | Mar 11, 2020 |
| MSI           | H81M-P33                    | [4fd88fa0cd](https://linux-hardware.org/?probe=4fd88fa0cd) | Mar 11, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [601a1539ce](https://linux-hardware.org/?probe=601a1539ce) | Mar 11, 2020 |
| HP            | 843F                        | [8e3653137c](https://linux-hardware.org/?probe=8e3653137c) | Mar 10, 2020 |
| Dell          | 0NW73C A00                  | [079032cab6](https://linux-hardware.org/?probe=079032cab6) | Feb 29, 2020 |
| Dell          | 0NW73C A00                  | [4f94baa369](https://linux-hardware.org/?probe=4f94baa369) | Feb 28, 2020 |
| Dell          | 0NW73C A00                  | [ee7108cb91](https://linux-hardware.org/?probe=ee7108cb91) | Feb 28, 2020 |
| Dell          | 0NW73C A00                  | [1cfd8f7014](https://linux-hardware.org/?probe=1cfd8f7014) | Feb 28, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [a018f0a4d4](https://linux-hardware.org/?probe=a018f0a4d4) | Feb 27, 2020 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [3ab01ccb21](https://linux-hardware.org/?probe=3ab01ccb21) | Feb 26, 2020 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [8474de61ef](https://linux-hardware.org/?probe=8474de61ef) | Feb 26, 2020 |
| ASUSTek       | CUSL2-M                     | [a20a268bb5](https://linux-hardware.org/?probe=a20a268bb5) | Feb 23, 2020 |
| ASUSTek       | P5G41T-M LX                 | [73e5d55bdb](https://linux-hardware.org/?probe=73e5d55bdb) | Feb 23, 2020 |
| Gigabyte      | GA-770T-D3L                 | [a221d53be6](https://linux-hardware.org/?probe=a221d53be6) | Feb 22, 2020 |
| ASUSTek       | STRIX Z270G GAMING          | [5bd0e60cb9](https://linux-hardware.org/?probe=5bd0e60cb9) | Feb 21, 2020 |
| Gigabyte      | Z77-D3H                     | [86b54afeaf](https://linux-hardware.org/?probe=86b54afeaf) | Feb 20, 2020 |
| HP            | 1495                        | [ce0ebaa644](https://linux-hardware.org/?probe=ce0ebaa644) | Feb 16, 2020 |
| HP            | 1495                        | [e07a108e6f](https://linux-hardware.org/?probe=e07a108e6f) | Feb 16, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [a84be71f79](https://linux-hardware.org/?probe=a84be71f79) | Feb 05, 2020 |
| Gigabyte      | EP35-DS3                    | [5a3ef0f23c](https://linux-hardware.org/?probe=5a3ef0f23c) | Feb 03, 2020 |
| Gigabyte      | GA-73PVM-S2H                | [503c223716](https://linux-hardware.org/?probe=503c223716) | Jan 28, 2020 |
| HP            | 806A                        | [bfc2676644](https://linux-hardware.org/?probe=bfc2676644) | Jan 26, 2020 |
| Gigabyte      | Z390 AORUS PRO-CF           | [436f08bfd7](https://linux-hardware.org/?probe=436f08bfd7) | Jan 24, 2020 |
| Gigabyte      | Z77-D3H                     | [1c841791ef](https://linux-hardware.org/?probe=1c841791ef) | Jan 20, 2020 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [1edaf69823](https://linux-hardware.org/?probe=1edaf69823) | Jan 20, 2020 |
| Gigabyte      | H97-HD3                     | [80245136bd](https://linux-hardware.org/?probe=80245136bd) | Jan 18, 2020 |
| Dell          | 0Y1057                      | [bf78aaecc3](https://linux-hardware.org/?probe=bf78aaecc3) | Jan 17, 2020 |
| Intel         | DQ35JO AAD82085-807         | [6c64315bcf](https://linux-hardware.org/?probe=6c64315bcf) | Jan 15, 2020 |
| Intel         | DQ35JO AAD82085-807         | [c570563513](https://linux-hardware.org/?probe=c570563513) | Jan 15, 2020 |
| Intel         | DQ35JO AAD82085-807         | [5173e103d5](https://linux-hardware.org/?probe=5173e103d5) | Jan 15, 2020 |
| Gigabyte      | EP45-DS4                    | [4bd613ef39](https://linux-hardware.org/?probe=4bd613ef39) | Jan 14, 2020 |
| Gigabyte      | EP45-DS4                    | [081fbf92ef](https://linux-hardware.org/?probe=081fbf92ef) | Jan 14, 2020 |
| Gigabyte      | Z77-D3H                     | [7c5c1cff72](https://linux-hardware.org/?probe=7c5c1cff72) | Jan 14, 2020 |
| Gigabyte      | Z77-D3H                     | [745edd74fb](https://linux-hardware.org/?probe=745edd74fb) | Jan 14, 2020 |
| Gigabyte      | Z77-D3H                     | [4a82019d80](https://linux-hardware.org/?probe=4a82019d80) | Jan 13, 2020 |
| Gigabyte      | Z77-D3H                     | [2a51f23df2](https://linux-hardware.org/?probe=2a51f23df2) | Jan 13, 2020 |
| Gigabyte      | Z77-D3H                     | [2f9a0ca1ce](https://linux-hardware.org/?probe=2f9a0ca1ce) | Jan 12, 2020 |
| Gigabyte      | Z77-D3H                     | [2f98991cfb](https://linux-hardware.org/?probe=2f98991cfb) | Jan 12, 2020 |
| Gigabyte      | Z77-D3H                     | [d93b8a1a22](https://linux-hardware.org/?probe=d93b8a1a22) | Jan 12, 2020 |
| ASUSTek       | P5K Premium                 | [8b39be3e8f](https://linux-hardware.org/?probe=8b39be3e8f) | Jan 10, 2020 |
| Dell          | 0Y1057                      | [6c5515c415](https://linux-hardware.org/?probe=6c5515c415) | Jan 10, 2020 |
| MSI           | MS-7366                     | [7b29163b46](https://linux-hardware.org/?probe=7b29163b46) | Dec 28, 2019 |
| ASUSTek       | P5B-Deluxe                  | [49bc4a3291](https://linux-hardware.org/?probe=49bc4a3291) | Dec 24, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [fff26d5712](https://linux-hardware.org/?probe=fff26d5712) | Dec 21, 2019 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [7cc0e44901](https://linux-hardware.org/?probe=7cc0e44901) | Dec 08, 2019 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [6c2647ab1f](https://linux-hardware.org/?probe=6c2647ab1f) | Dec 07, 2019 |
| MSI           | Z97 PC Mate                 | [72bbff1151](https://linux-hardware.org/?probe=72bbff1151) | Dec 06, 2019 |
| ASUSTek       | P5B-Deluxe                  | [6bd7363656](https://linux-hardware.org/?probe=6bd7363656) | Nov 30, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [199fad181e](https://linux-hardware.org/?probe=199fad181e) | Nov 29, 2019 |
| ASRock        | B75M-GL R2.0                | [af0f782566](https://linux-hardware.org/?probe=af0f782566) | Nov 23, 2019 |
| Gigabyte      | GA-MA770-UD3                | [16108ce66a](https://linux-hardware.org/?probe=16108ce66a) | Nov 19, 2019 |
| ASUSTek       | P5K Premium                 | [5cb1d8f9b9](https://linux-hardware.org/?probe=5cb1d8f9b9) | Nov 15, 2019 |
| ASUSTek       | P5K SE                      | [47ed174456](https://linux-hardware.org/?probe=47ed174456) | Nov 14, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [6a11247e37](https://linux-hardware.org/?probe=6a11247e37) | Nov 11, 2019 |
| Gigabyte      | H110M-S2H-CF                | [c78f6913ae](https://linux-hardware.org/?probe=c78f6913ae) | Nov 11, 2019 |
| ASUSTek       | P5K Premium                 | [ead46dee7b](https://linux-hardware.org/?probe=ead46dee7b) | Nov 11, 2019 |
| MSI           | MS-7360                     | [ef6c3da38a](https://linux-hardware.org/?probe=ef6c3da38a) | Nov 07, 2019 |
| MSI           | MS-7360                     | [3c13191b90](https://linux-hardware.org/?probe=3c13191b90) | Nov 07, 2019 |
| Gigabyte      | GA-M55PLUS-S3G              | [6027467f3b](https://linux-hardware.org/?probe=6027467f3b) | Nov 01, 2019 |
| HP            | 1998                        | [342c447028](https://linux-hardware.org/?probe=342c447028) | Oct 11, 2019 |
| Unknown       | Unknown                     | [c125474c31](https://linux-hardware.org/?probe=c125474c31) | Oct 10, 2019 |
| MSI           | 970 GAMING                  | [1bb3b162b8](https://linux-hardware.org/?probe=1bb3b162b8) | Oct 03, 2019 |
| Acer          | Aspire TC-885 V:1.1         | [42ef2aa13b](https://linux-hardware.org/?probe=42ef2aa13b) | Sep 30, 2019 |
| MSI           | 970 GAMING                  | [f8858e6fb6](https://linux-hardware.org/?probe=f8858e6fb6) | Sep 22, 2019 |
| Gigabyte      | GA-MA69VM-S2                | [1eced47226](https://linux-hardware.org/?probe=1eced47226) | Sep 18, 2019 |
| MSI           | 0A90                        | [70949e4cac](https://linux-hardware.org/?probe=70949e4cac) | Sep 12, 2019 |
| ASRock        | X470 Master SLI             | [49e321f31a](https://linux-hardware.org/?probe=49e321f31a) | Sep 10, 2019 |
| ASRock        | X470 Master SLI             | [9cf2d3e877](https://linux-hardware.org/?probe=9cf2d3e877) | Sep 02, 2019 |
| MSI           | A78M-E45                    | [c5735a3943](https://linux-hardware.org/?probe=c5735a3943) | Aug 31, 2019 |
| MSI           | 0A90                        | [12b46024d1](https://linux-hardware.org/?probe=12b46024d1) | Aug 16, 2019 |
| ELSKY         | Nano9F-2C                   | [a3eb79407f](https://linux-hardware.org/?probe=a3eb79407f) | Aug 08, 2019 |
| MSI           | A78M-E45                    | [5b9ab2b30a](https://linux-hardware.org/?probe=5b9ab2b30a) | Jul 31, 2019 |
| Gigabyte      | 990FXA-UD3                  | [394c81b911](https://linux-hardware.org/?probe=394c81b911) | Jul 28, 2019 |
| Fujitsu       | D3118-A1 S26361-D3118-A1    | [077a9b9d45](https://linux-hardware.org/?probe=077a9b9d45) | Jul 22, 2019 |
| ASRock        | Q1900B-ITX                  | [9f5937d37e](https://linux-hardware.org/?probe=9f5937d37e) | Jul 21, 2019 |
| ASUSTek       | M2N-E SLI                   | [6e181005c4](https://linux-hardware.org/?probe=6e181005c4) | Jul 16, 2019 |
| Fujitsu       | D3118-A1 S26361-D3118-A1    | [7fc111342c](https://linux-hardware.org/?probe=7fc111342c) | Jul 14, 2019 |
| ASUSTek       | P5G41T-M LX                 | [65cf4f7f82](https://linux-hardware.org/?probe=65cf4f7f82) | Jul 05, 2019 |
| ASUSTek       | P5G41T-M LX                 | [d28cd9f74d](https://linux-hardware.org/?probe=d28cd9f74d) | Jul 04, 2019 |
| Gigabyte      | P35-DS3                     | [8168ba11e3](https://linux-hardware.org/?probe=8168ba11e3) | Jul 02, 2019 |
| Gigabyte      | H77-DS3H                    | [87233b6bd2](https://linux-hardware.org/?probe=87233b6bd2) | Jun 28, 2019 |
| Gigabyte      | GA-MA785GMT-UD2H            | [583c276ad3](https://linux-hardware.org/?probe=583c276ad3) | Jun 18, 2019 |
| MSI           | B350 TOMAHAWK               | [84ec84c6f6](https://linux-hardware.org/?probe=84ec84c6f6) | Jun 16, 2019 |
| MSI           | B350 TOMAHAWK               | [ec5e14a2fc](https://linux-hardware.org/?probe=ec5e14a2fc) | Jun 12, 2019 |
| ASUSTek       | H81M-R 2016-11-08           | [8a3d697836](https://linux-hardware.org/?probe=8a3d697836) | Jun 12, 2019 |
| Gigabyte      | GA-MA785GMT-UD2H            | [8373600eb6](https://linux-hardware.org/?probe=8373600eb6) | Jun 09, 2019 |
| Gigabyte      | GA-MA770-UD3                | [e938889e72](https://linux-hardware.org/?probe=e938889e72) | Jun 04, 2019 |
| ASUSTek       | M5A78L-M LX                 | [8984f382ef](https://linux-hardware.org/?probe=8984f382ef) | May 12, 2019 |
| ASUSTek       | P5K SE                      | [fe7f2c780a](https://linux-hardware.org/?probe=fe7f2c780a) | May 11, 2019 |
| MSI           | B350 GAMING PLUS            | [63c8391791](https://linux-hardware.org/?probe=63c8391791) | May 09, 2019 |
| ASUSTek       | P5K Premium                 | [aaecfa3e56](https://linux-hardware.org/?probe=aaecfa3e56) | May 08, 2019 |
| Dell          | 0HHV7N A00                  | [945e8a152d](https://linux-hardware.org/?probe=945e8a152d) | May 06, 2019 |
| Gigabyte      | G33M-S2L                    | [74f9393d09](https://linux-hardware.org/?probe=74f9393d09) | Apr 27, 2019 |
| ASUSTek       | PRIME B250M-A               | [a6769b6b22](https://linux-hardware.org/?probe=a6769b6b22) | Apr 26, 2019 |
| ASRock        | FM2A68M-DG3+                | [6011d46330](https://linux-hardware.org/?probe=6011d46330) | Apr 10, 2019 |
| MSI           | P45 Platinum                | [7999e0452a](https://linux-hardware.org/?probe=7999e0452a) | Apr 07, 2019 |
| MSI           | P45 Platinum                | [4e9d6c8e02](https://linux-hardware.org/?probe=4e9d6c8e02) | Apr 07, 2019 |
| ASUSTek       | J1800I-C                    | [35cfa6018f](https://linux-hardware.org/?probe=35cfa6018f) | Apr 03, 2019 |
| ASUSTek       | Leonite2                    | [acd81f03f2](https://linux-hardware.org/?probe=acd81f03f2) | Mar 28, 2019 |
| ASUSTek       | PRIME X470-PRO              | [aeef8eb693](https://linux-hardware.org/?probe=aeef8eb693) | Mar 26, 2019 |
| MSI           | G41M4                       | [34263c5455](https://linux-hardware.org/?probe=34263c5455) | Mar 22, 2019 |
| MSI           | G41M-P26                    | [fb80aa717a](https://linux-hardware.org/?probe=fb80aa717a) | Mar 21, 2019 |
| HP            | 1497                        | [645891d86b](https://linux-hardware.org/?probe=645891d86b) | Mar 21, 2019 |
| HP            | 1497                        | [50753b9ba5](https://linux-hardware.org/?probe=50753b9ba5) | Mar 21, 2019 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [2f4122790d](https://linux-hardware.org/?probe=2f4122790d) | Mar 20, 2019 |
| HP            | 198E                        | [556ffdb3d3](https://linux-hardware.org/?probe=556ffdb3d3) | Mar 17, 2019 |
| HP            | 198E                        | [c722407ee3](https://linux-hardware.org/?probe=c722407ee3) | Mar 17, 2019 |
| ASUSTek       | K8VSEDX                     | [e75f4538bc](https://linux-hardware.org/?probe=e75f4538bc) | Mar 13, 2019 |
| ASUSTek       | K8VSEDX                     | [af41e6a893](https://linux-hardware.org/?probe=af41e6a893) | Mar 11, 2019 |
| MSI           | B360M MORTAR                | [f86dada1e8](https://linux-hardware.org/?probe=f86dada1e8) | Mar 08, 2019 |
| HP            | Compaq dc7600 Small Form... | [126f2d8b0f](https://linux-hardware.org/?probe=126f2d8b0f) | Mar 07, 2019 |
| HP            | Compaq dc7600 Small Form... | [3ffe7337bd](https://linux-hardware.org/?probe=3ffe7337bd) | Mar 04, 2019 |
| HP            | Compaq dc7600 Small Form... | [06472f3d2c](https://linux-hardware.org/?probe=06472f3d2c) | Mar 03, 2019 |
| Fujitsu Si... | MS-7379VP                   | [e3ef0760f5](https://linux-hardware.org/?probe=e3ef0760f5) | Mar 03, 2019 |
| MSI           | 970A-G43                    | [631892b31b](https://linux-hardware.org/?probe=631892b31b) | Feb 22, 2019 |
| Gigabyte      | G31M-ES2L                   | [3799326d94](https://linux-hardware.org/?probe=3799326d94) | Feb 18, 2019 |
| ASUSTek       | P5K Premium                 | [f6f1f3d526](https://linux-hardware.org/?probe=f6f1f3d526) | Feb 16, 2019 |
| Fujitsu Si... | D2598-A1 S26361-D2598-A1    | [9bc9c716d7](https://linux-hardware.org/?probe=9bc9c716d7) | Feb 15, 2019 |
| ASUSTek       | P5K Premium                 | [13dbdc3bfe](https://linux-hardware.org/?probe=13dbdc3bfe) | Feb 11, 2019 |
| ASUSTek       | P5K Premium                 | [52d7ba736e](https://linux-hardware.org/?probe=52d7ba736e) | Feb 11, 2019 |
| ASRock        | 970 Pro3 R2.0               | [a8632b914f](https://linux-hardware.org/?probe=a8632b914f) | Feb 07, 2019 |
| Fujitsu Si... | MS-7379VP                   | [b854c8f19f](https://linux-hardware.org/?probe=b854c8f19f) | Jan 31, 2019 |
| Gigabyte      | GA-A75M-S2V                 | [190b100445](https://linux-hardware.org/?probe=190b100445) | Jan 27, 2019 |
| Gigabyte      | GA-K8NMF-9                  | [06d9e6367f](https://linux-hardware.org/?probe=06d9e6367f) | Jan 13, 2019 |
| Gigabyte      | GA-MA785GMT-UD2H            | [3f6457cfd5](https://linux-hardware.org/?probe=3f6457cfd5) | Jan 10, 2019 |
| Dell          | 040DDP A01                  | [b930102736](https://linux-hardware.org/?probe=b930102736) | Jan 09, 2019 |
| Dell          | 040DDP A01                  | [40c27cbf90](https://linux-hardware.org/?probe=40c27cbf90) | Jan 09, 2019 |
| Gigabyte      | B450 AORUS ELITE            | [1192b16b2a](https://linux-hardware.org/?probe=1192b16b2a) | Dec 29, 2018 |
| Gigabyte      | B450 AORUS ELITE            | [f1b5bc1e1f](https://linux-hardware.org/?probe=f1b5bc1e1f) | Dec 29, 2018 |
| ASUSTek       | P8P67 PRO                   | [0dad2407e3](https://linux-hardware.org/?probe=0dad2407e3) | Dec 20, 2018 |
| MSI           | H55M-E33                    | [b780e08bb9](https://linux-hardware.org/?probe=b780e08bb9) | Dec 16, 2018 |
| MSI           | MS-B0731 110                | [c3d309bfb3](https://linux-hardware.org/?probe=c3d309bfb3) | Dec 14, 2018 |
| MSI           | MS-B0731 110                | [e827df73dc](https://linux-hardware.org/?probe=e827df73dc) | Dec 14, 2018 |
| ASUSTek       | H170-PRO                    | [0938abc248](https://linux-hardware.org/?probe=0938abc248) | Dec 11, 2018 |
| Gigabyte      | H87N-WIFI                   | [f905cc3870](https://linux-hardware.org/?probe=f905cc3870) | Dec 05, 2018 |
| Gigabyte      | H87N-WIFI                   | [e6d3282cf3](https://linux-hardware.org/?probe=e6d3282cf3) | Dec 05, 2018 |
| Gigabyte      | M68MT-S2                    | [bb2e4203aa](https://linux-hardware.org/?probe=bb2e4203aa) | Nov 29, 2018 |
| Acer          | Aspire XC-330               | [f8f3bade01](https://linux-hardware.org/?probe=f8f3bade01) | Nov 26, 2018 |
| ASUSTek       | M2R32-MVP                   | [c55fd274a8](https://linux-hardware.org/?probe=c55fd274a8) | Nov 25, 2018 |
| ASUSTek       | P5KC                        | [8a3e1d567d](https://linux-hardware.org/?probe=8a3e1d567d) | Nov 24, 2018 |
| Acer          | Aspire XC-330               | [68b982def0](https://linux-hardware.org/?probe=68b982def0) | Nov 24, 2018 |
| MSI           | B450-A PRO                  | [69d51e68b0](https://linux-hardware.org/?probe=69d51e68b0) | Nov 17, 2018 |
| ASUSTek       | Z170-P                      | [89df305ae0](https://linux-hardware.org/?probe=89df305ae0) | Nov 16, 2018 |
| MSI           | B450-A PRO                  | [e19f3cd86b](https://linux-hardware.org/?probe=e19f3cd86b) | Nov 13, 2018 |
| Gigabyte      | Z97X-Gaming 3               | [785b8234d8](https://linux-hardware.org/?probe=785b8234d8) | Nov 11, 2018 |
| Gigabyte      | Z97X-Gaming 3               | [8647c5f6bf](https://linux-hardware.org/?probe=8647c5f6bf) | Nov 11, 2018 |
| MSI           | P45 Platinum                | [a37ef3f804](https://linux-hardware.org/?probe=a37ef3f804) | Nov 10, 2018 |
| ASUSTek       | PRIME H310M-K               | [bb570c89e7](https://linux-hardware.org/?probe=bb570c89e7) | Nov 10, 2018 |
| ASUSTek       | PRIME H310M-K               | [eb0530deb6](https://linux-hardware.org/?probe=eb0530deb6) | Nov 10, 2018 |
| ASUSTek       | PRIME H310M-K               | [afa6ff3556](https://linux-hardware.org/?probe=afa6ff3556) | Nov 10, 2018 |
| Gigabyte      | Z77X-UD3H                   | [72b7400f99](https://linux-hardware.org/?probe=72b7400f99) | Oct 21, 2018 |
| ASUSTek       | 970 PRO GAMING/AURA         | [a31f08667c](https://linux-hardware.org/?probe=a31f08667c) | Oct 21, 2018 |
| ASUSTek       | 970 PRO GAMING/AURA         | [51dce6d904](https://linux-hardware.org/?probe=51dce6d904) | Oct 21, 2018 |
| Supermicro    | X8STi                       | [a265bad98f](https://linux-hardware.org/?probe=a265bad98f) | Oct 19, 2018 |
| Gigabyte      | P67A-UD4-B3                 | [cbbd77219d](https://linux-hardware.org/?probe=cbbd77219d) | Aug 10, 2018 |
| ASUSTek       | K8VSEDX                     | [ef07e2c2ef](https://linux-hardware.org/?probe=ef07e2c2ef) | Aug 10, 2018 |
| Gigabyte      | Z77X-UP5 TH-CF              | [2457e81077](https://linux-hardware.org/?probe=2457e81077) | May 12, 2018 |
| ASUSTek       | K8VSEDX                     | [dff4a09807](https://linux-hardware.org/?probe=dff4a09807) | Feb 02, 2018 |
| MSI           | H81M-P33 V2                 | [ab7edede3c](https://linux-hardware.org/?probe=ab7edede3c) | Jan 17, 2018 |
| ASUSTek       | M2A74-AM                    | [f3d795bddd](https://linux-hardware.org/?probe=f3d795bddd) | Nov 24, 2017 |
| ASUSTek       | J1800I-C                    | [44deca13f0](https://linux-hardware.org/?probe=44deca13f0) | Oct 15, 2017 |
| ASUSTek       | J1800I-C                    | [043af9db42](https://linux-hardware.org/?probe=043af9db42) | Oct 11, 2017 |
| Gigabyte      | M68MT-S2                    | [1843755019](https://linux-hardware.org/?probe=1843755019) | Aug 22, 2017 |
| Gigabyte      | M68MT-S2                    | [5fbed0d6a1](https://linux-hardware.org/?probe=5fbed0d6a1) | Jul 15, 2017 |
| Gigabyte      | GA-A75M-UD2H                | [cf39a21a77](https://linux-hardware.org/?probe=cf39a21a77) | Jul 02, 2017 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [fd5fde7a28](https://linux-hardware.org/?probe=fd5fde7a28) | Jun 15, 2017 |
| ASUSTek       | M5A97 R2.0                  | [602f0c766a](https://linux-hardware.org/?probe=602f0c766a) | Apr 23, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Czechia/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 75       | 11.16%  |
| Ubuntu 18.04                 | 57       | 8.48%   |
| OpenMandriva 4.2             | 38       | 5.65%   |
| Ubuntu 22.04                 | 35       | 5.21%   |
| OpenMandriva 4.3             | 27       | 4.02%   |
| Debian 11                    | 14       | 2.08%   |
| Linux Mint 20.1              | 13       | 1.93%   |
| Arch Rolling                 | 13       | 1.93%   |
| Zorin 16                     | 10       | 1.49%   |
| Ubuntu 19.04                 | 10       | 1.49%   |
| OpenMandriva 23.01           | 10       | 1.49%   |
| Fedora 35                    | 10       | 1.49%   |
| Fedora 32                    | 10       | 1.49%   |
| Ubuntu 20.10                 | 9        | 1.34%   |
| Linux Mint 21.1              | 9        | 1.34%   |
| Linux Mint 20.3              | 9        | 1.34%   |
| Ubuntu 22.10                 | 8        | 1.19%   |
| OpenMandriva 4.50            | 8        | 1.19%   |
| OpenMandriva 23.03           | 8        | 1.19%   |
| Linux Mint 20.2              | 8        | 1.19%   |
| Fedora 36                    | 8        | 1.19%   |
| Fedora 34                    | 8        | 1.19%   |
| ROSA R9                      | 7        | 1.04%   |
| Pop!_OS 20.04                | 7        | 1.04%   |
| Linux Mint 20                | 7        | 1.04%   |
| Fedora 37                    | 7        | 1.04%   |
| Fedora 33                    | 7        | 1.04%   |
| Ubuntu 21.10                 | 6        | 0.89%   |
| Ubuntu 21.04                 | 6        | 0.89%   |
| Ubuntu 19.10                 | 6        | 0.89%   |
| openSUSE Tumbleweed-XXXXXXXX | 6        | 0.89%   |
| Linux Mint 19.3              | 6        | 0.89%   |
| KDE neon 20.04               | 6        | 0.89%   |
| Xubuntu 18.04                | 5        | 0.74%   |
| Ubuntu MATE 20.04            | 5        | 0.74%   |
| Ubuntu 18.10                 | 5        | 0.74%   |
| RHEL 8                       | 5        | 0.74%   |
| Kubuntu 20.04                | 5        | 0.74%   |
| Gentoo 2.6                   | 5        | 0.74%   |
| Debian 10                    | 5        | 0.74%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 215      | 34.02%  |
| OpenMandriva | 84       | 13.29%  |
| Linux Mint   | 62       | 9.81%   |
| Fedora       | 50       | 7.91%   |
| Debian       | 24       | 3.8%    |
| ROSA         | 18       | 2.85%   |
| Arch         | 18       | 2.85%   |
| Pop!_OS      | 17       | 2.69%   |
| Zorin        | 16       | 2.53%   |
| Gentoo       | 14       | 2.22%   |
| Manjaro      | 13       | 2.06%   |
| Xubuntu      | 9        | 1.42%   |
| Kubuntu      | 9        | 1.42%   |
| KDE neon     | 8        | 1.27%   |
| Ubuntu MATE  | 6        | 0.95%   |
| openSUSE     | 6        | 0.95%   |
| Ubuntu Unity | 5        | 0.79%   |
| RHEL         | 5        | 0.79%   |
| Lubuntu      | 5        | 0.79%   |
| Kali         | 5        | 0.79%   |
| Endless      | 5        | 0.79%   |
| CentOS       | 5        | 0.79%   |
| ArcoLinux    | 5        | 0.79%   |
| Elementary   | 4        | 0.63%   |
| Void Linux   | 3        | 0.47%   |
| Parrot       | 2        | 0.32%   |
| Nobara       | 2        | 0.32%   |
| LMDE         | 2        | 0.32%   |
| EndeavourOS  | 2        | 0.32%   |
| Xero         | 1        | 0.16%   |
| Sparky       | 1        | 0.16%   |
| Rocky Linux  | 1        | 0.16%   |
| Rockstor     | 1        | 0.16%   |
| Neptune OS   | 1        | 0.16%   |
| Mageia       | 1        | 0.16%   |
| LinuxFX      | 1        | 0.16%   |
| GNOME OS     | 1        | 0.16%   |
| Garuda Linux | 1        | 0.16%   |
| Drauger OS   | 1        | 0.16%   |
| BlackPanther | 1        | 0.16%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002        | 37       | 4.91%   |
| 5.16.7-desktop-1omv4003         | 27       | 3.59%   |
| 5.4.0-42-generic                | 11       | 1.46%   |
| 6.2.6-desktop-1omv2390          | 10       | 1.33%   |
| 5.4.0-58-generic                | 9        | 1.2%    |
| 6.1.1-desktop-1omv2290          | 8        | 1.06%   |
| 5.11.0-27-generic               | 8        | 1.06%   |
| 5.15.0-56-generic               | 7        | 0.93%   |
| 5.15.0-52-generic               | 7        | 0.93%   |
| 5.13.0-30-generic               | 7        | 0.93%   |
| 5.4.0-26-generic                | 6        | 0.8%    |
| 5.15.0-46-generic               | 6        | 0.8%    |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 6        | 0.8%    |
| 5.4.0-52-generic                | 5        | 0.66%   |
| 5.3.0-28-generic                | 5        | 0.66%   |
| 5.12.4-desktop-1omv4050         | 5        | 0.66%   |
| 5.0.0-37-generic                | 5        | 0.66%   |
| 4.15.0-45-generic               | 5        | 0.66%   |
| 5.8.0-50-generic                | 4        | 0.53%   |
| 5.8.0-41-generic                | 4        | 0.53%   |
| 5.4.0-74-generic                | 4        | 0.53%   |
| 5.4.0-72-generic                | 4        | 0.53%   |
| 5.4.0-48-generic                | 4        | 0.53%   |
| 5.4.0-47-generic                | 4        | 0.53%   |
| 5.4.0-33-generic                | 4        | 0.53%   |
| 5.3.0-40-generic                | 4        | 0.53%   |
| 5.19.0-38-generic               | 4        | 0.53%   |
| 5.19.0-23-generic               | 4        | 0.53%   |
| 5.15.0-58-generic               | 4        | 0.53%   |
| 5.15.0-43-generic               | 4        | 0.53%   |
| 5.15.0-41-generic               | 4        | 0.53%   |
| 5.15.0-25-generic               | 4        | 0.53%   |
| 5.13.0-39-generic               | 4        | 0.53%   |
| 5.11.0-37-generic               | 4        | 0.53%   |
| 5.0.0-32-generic                | 4        | 0.53%   |
| 4.18.0-25-generic               | 4        | 0.53%   |
| 4.18.0-16-generic               | 4        | 0.53%   |
| 4.15.0-43-generic               | 4        | 0.53%   |
| 6.2.0-20-generic                | 3        | 0.4%    |
| 5.8.0-53-generic                | 3        | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 102      | 14.59%  |
| 5.15.0  | 57       | 8.15%   |
| 4.15.0  | 49       | 7.01%   |
| 5.10.14 | 37       | 5.29%   |
| 5.8.0   | 33       | 4.72%   |
| 5.11.0  | 28       | 4.01%   |
| 5.16.7  | 27       | 3.86%   |
| 4.18.0  | 26       | 3.72%   |
| 5.0.0   | 24       | 3.43%   |
| 5.3.0   | 22       | 3.15%   |
| 5.13.0  | 20       | 2.86%   |
| 5.19.0  | 19       | 2.72%   |
| 5.10.0  | 13       | 1.86%   |
| 6.1.1   | 11       | 1.57%   |
| 6.2.6   | 10       | 1.43%   |
| 4.19.0  | 8        | 1.14%   |
| 4.9.20  | 7        | 1%      |
| 5.12.4  | 5        | 0.72%   |
| 6.2.0   | 4        | 0.57%   |
| 6.0.0   | 4        | 0.57%   |
| 6.3.1   | 3        | 0.43%   |
| 6.1.12  | 3        | 0.43%   |
| 6.0.12  | 3        | 0.43%   |
| 5.6.6   | 3        | 0.43%   |
| 5.16.11 | 3        | 0.43%   |
| 6.3.4   | 2        | 0.29%   |
| 6.1.9   | 2        | 0.29%   |
| 6.1.8   | 2        | 0.29%   |
| 6.1.3   | 2        | 0.29%   |
| 6.1.0   | 2        | 0.29%   |
| 5.9.16  | 2        | 0.29%   |
| 5.9.0   | 2        | 0.29%   |
| 5.8.11  | 2        | 0.29%   |
| 5.7.12  | 2        | 0.29%   |
| 5.7.0   | 2        | 0.29%   |
| 5.6.0   | 2        | 0.29%   |
| 5.4.72  | 2        | 0.29%   |
| 5.19.13 | 2        | 0.29%   |
| 5.18.12 | 2        | 0.29%   |
| 5.16.18 | 2        | 0.29%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.4      | 108      | 15.65%  |
| 5.15     | 72       | 10.43%  |
| 5.10     | 64       | 9.28%   |
| 4.15     | 49       | 7.1%    |
| 5.8      | 46       | 6.67%   |
| 5.16     | 37       | 5.36%   |
| 5.11     | 37       | 5.36%   |
| 5.19     | 27       | 3.91%   |
| 4.18     | 27       | 3.91%   |
| 5.0      | 26       | 3.77%   |
| 5.3      | 25       | 3.62%   |
| 6.1      | 24       | 3.48%   |
| 5.13     | 24       | 3.48%   |
| 6.2      | 18       | 2.61%   |
| 6.0      | 12       | 1.74%   |
| 4.9      | 11       | 1.59%   |
| 5.17     | 9        | 1.3%    |
| 5.12     | 8        | 1.16%   |
| 4.19     | 8        | 1.16%   |
| 5.7      | 7        | 1.01%   |
| 5.6      | 7        | 1.01%   |
| 5.18     | 7        | 1.01%   |
| 5.14     | 7        | 1.01%   |
| 6.3      | 6        | 0.87%   |
| 5.9      | 6        | 0.87%   |
| 5.5      | 4        | 0.58%   |
| 4.4      | 2        | 0.29%   |
| 4.17     | 2        | 0.29%   |
| 3.10     | 2        | 0.29%   |
| 5.2      | 1        | 0.14%   |
| 5.10.164 | 1        | 0.14%   |
| 4.20     | 1        | 0.14%   |
| 4.14     | 1        | 0.14%   |
| 4.13     | 1        | 0.14%   |
| 4.10     | 1        | 0.14%   |
| 4.1      | 1        | 0.14%   |
| 2.6      | 1        | 0.14%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 601      | 96.62%  |
| i686   | 21       | 3.38%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| GNOME             | 240      | 37.33%  |
| KDE5              | 136      | 21.15%  |
| Unknown           | 104      | 16.17%  |
| XFCE              | 41       | 6.38%   |
| X-Cinnamon        | 41       | 6.38%   |
| KDE               | 18       | 2.8%    |
| MATE              | 14       | 2.18%   |
| Cinnamon          | 12       | 1.87%   |
| Unity             | 5        | 0.78%   |
| KDE4              | 5        | 0.78%   |
| GNOME Flashback   | 5        | 0.78%   |
| Pantheon          | 4        | 0.62%   |
| LXQt              | 4        | 0.62%   |
| LXDE              | 4        | 0.62%   |
| i3                | 3        | 0.47%   |
| openbox           | 2        | 0.31%   |
| Yaru:ubuntu:GNOME | 1        | 0.16%   |
| qtile             | 1        | 0.16%   |
| Hyprland          | 1        | 0.16%   |
| Core              | 1        | 0.16%   |
| Budgie            | 1        | 0.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 483      | 75.82%  |
| Wayland | 83       | 13.03%  |
| Unknown | 52       | 8.16%   |
| Tty     | 19       | 2.98%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 331      | 51.32%  |
| SDDM    | 129      | 20%     |
| GDM3    | 58       | 8.99%   |
| GDM     | 54       | 8.37%   |
| LightDM | 41       | 6.36%   |
| TDM     | 25       | 3.88%   |
| KDM     | 5        | 0.78%   |
| XDM     | 1        | 0.16%   |
| SLiM    | 1        | 0.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| cs_CZ   | 346      | 54.23%  |
| en_US   | 164      | 25.71%  |
| Unknown | 90       | 14.11%  |
| en_GB   | 15       | 2.35%   |
| C       | 7        | 1.1%    |
| sk_SK   | 4        | 0.63%   |
| ru_RU   | 4        | 0.63%   |
| POSIX   | 2        | 0.31%   |
| pt_PT   | 1        | 0.16%   |
| it_IT   | 1        | 0.16%   |
| fi_FI   | 1        | 0.16%   |
| en_CA   | 1        | 0.16%   |
| en_AU   | 1        | 0.16%   |
| C.UTF8  | 1        | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 396      | 62.56%  |
| EFI  | 237      | 37.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 440      | 68.43%  |
| Overlay  | 83       | 12.91%  |
| Btrfs    | 65       | 10.11%  |
| Unknown  | 24       | 3.73%   |
| Xfs      | 18       | 2.8%    |
| Zfs      | 7        | 1.09%   |
| Tmpfs    | 2        | 0.31%   |
| Ext2     | 2        | 0.31%   |
| Reiserfs | 1        | 0.16%   |
| Ext3     | 1        | 0.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 335      | 52.51%  |
| GPT     | 209      | 32.76%  |
| MBR     | 94       | 14.73%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 506      | 79.56%  |
| Yes       | 130      | 20.44%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 430      | 67.72%  |
| Yes       | 205      | 32.28%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 168      | 27.05%  |
| Gigabyte Technology                  | 135      | 21.74%  |
| MSI                                  | 103      | 16.59%  |
| ASRock                               | 50       | 8.05%   |
| Hewlett-Packard                      | 45       | 7.25%   |
| Dell                                 | 30       | 4.83%   |
| Lenovo                               | 24       | 3.86%   |
| Intel                                | 14       | 2.25%   |
| Acer                                 | 12       | 1.93%   |
| Pegatron                             | 7        | 1.13%   |
| Fujitsu                              | 7        | 1.13%   |
| Fujitsu Siemens                      | 4        | 0.64%   |
| Supermicro                           | 3        | 0.48%   |
| Unknown                              | 3        | 0.48%   |
| Foxconn                              | 2        | 0.32%   |
| Clientron                            | 2        | 0.32%   |
| Biostar                              | 2        | 0.32%   |
| UMAX                                 | 1        | 0.16%   |
| SIEMENS                              | 1        | 0.16%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.16%   |
| Seeed Studio                         | 1        | 0.16%   |
| Packard Bell                         | 1        | 0.16%   |
| Minix                                | 1        | 0.16%   |
| Le Cube 1                            | 1        | 0.16%   |
| EVGA                                 | 1        | 0.16%   |
| ELSKY                                | 1        | 0.16%   |
| ASRockRack                           | 1        | 0.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| ASUS All Series                    | 11       | 1.77%   |
| MSI MS-7C91                        | 9        | 1.45%   |
| MSI MS-7693                        | 7        | 1.13%   |
| MSI MS-7C02                        | 6        | 0.97%   |
| MSI MS-7A34                        | 6        | 0.97%   |
| HP Compaq 8200 Elite SFF PC        | 4        | 0.64%   |
| ASUS P5G41T-M LX                   | 4        | 0.64%   |
| Unknown                            | 4        | 0.64%   |
| MSI MS-7817                        | 3        | 0.48%   |
| MSI MS-7592                        | 3        | 0.48%   |
| Gigabyte B450 AORUS ELITE          | 3        | 0.48%   |
| Gigabyte 970A-DS3P                 | 3        | 0.48%   |
| Dell OptiPlex 790                  | 3        | 0.48%   |
| ASUS TUF B450M-PRO GAMING          | 3        | 0.48%   |
| ASUS ROG STRIX B550-I GAMING       | 3        | 0.48%   |
| ASUS ROG STRIX B550-F GAMING       | 3        | 0.48%   |
| ASRock B450M Pro4-F                | 3        | 0.48%   |
| Pegatron h9-1000cs                 | 2        | 0.32%   |
| Pegatron Elite 7300 Series MT      | 2        | 0.32%   |
| MSI MS-7C84                        | 2        | 0.32%   |
| MSI MS-7C37                        | 2        | 0.32%   |
| MSI MS-7B79                        | 2        | 0.32%   |
| MSI MS-7A32                        | 2        | 0.32%   |
| MSI MS-7850                        | 2        | 0.32%   |
| MSI MS-7597                        | 2        | 0.32%   |
| MSI MS-7512                        | 2        | 0.32%   |
| Lenovo ThinkCentre M58p 3285A1G    | 2        | 0.32%   |
| Intel DQ35JO AAD82085-807          | 2        | 0.32%   |
| HP Z230 Tower Workstation          | 2        | 0.32%   |
| HP EliteDesk 800 G1 SFF            | 2        | 0.32%   |
| HP Compaq dc7600 Small Form Factor | 2        | 0.32%   |
| HP Compaq 8100 Elite SFF PC        | 2        | 0.32%   |
| HP Compaq 6005 Pro MT PC           | 2        | 0.32%   |
| HP 290 G1 SFF Business PC          | 2        | 0.32%   |
| Gigabyte Z97X-Gaming 3             | 2        | 0.32%   |
| Gigabyte Z77-D3H                   | 2        | 0.32%   |
| Gigabyte Z390 AORUS PRO            | 2        | 0.32%   |
| Gigabyte X470 AORUS ULTRA GAMING   | 2        | 0.32%   |
| Gigabyte TRILINE PROFI             | 2        | 0.32%   |
| Gigabyte M61SME-S2                 | 2        | 0.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| ASUS PRIME           | 29       | 4.67%   |
| ASUS ROG             | 24       | 3.86%   |
| HP Compaq            | 20       | 3.22%   |
| Dell OptiPlex        | 20       | 3.22%   |
| ASUS TUF             | 18       | 2.9%    |
| Lenovo ThinkCentre   | 15       | 2.42%   |
| ASUS All             | 11       | 1.77%   |
| MSI MS-7C91          | 9        | 1.45%   |
| Acer Aspire          | 8        | 1.29%   |
| MSI MS-7693          | 7        | 1.13%   |
| Gigabyte B450        | 7        | 1.13%   |
| MSI MS-7C02          | 6        | 0.97%   |
| MSI MS-7A34          | 6        | 0.97%   |
| HP ProDesk           | 6        | 0.97%   |
| HP EliteDesk         | 5        | 0.81%   |
| Dell Precision       | 5        | 0.81%   |
| ASRock B450M         | 5        | 0.81%   |
| Gigabyte X570        | 4        | 0.64%   |
| Fujitsu ESPRIMO      | 4        | 0.64%   |
| ASUS P5G41T-M        | 4        | 0.64%   |
| ASUS M5A97           | 4        | 0.64%   |
| Unknown              | 4        | 0.64%   |
| Pegatron Elite       | 3        | 0.48%   |
| MSI MS-7817          | 3        | 0.48%   |
| MSI MS-7592          | 3        | 0.48%   |
| Gigabyte Z97X-Gaming | 3        | 0.48%   |
| Gigabyte Z390        | 3        | 0.48%   |
| Gigabyte TRILINE     | 3        | 0.48%   |
| Gigabyte 970A-DS3P   | 3        | 0.48%   |
| Dell Vostro          | 3        | 0.48%   |
| ASUS M5A78L-M        | 3        | 0.48%   |
| ASUS A88XM-A         | 3        | 0.48%   |
| ASRock B550M         | 3        | 0.48%   |
| ASRock B450          | 3        | 0.48%   |
| Acer Veriton         | 3        | 0.48%   |
| Pegatron h9-1000cs   | 2        | 0.32%   |
| MSI MS-7C84          | 2        | 0.32%   |
| MSI MS-7C37          | 2        | 0.32%   |
| MSI MS-7B79          | 2        | 0.32%   |
| MSI MS-7A32          | 2        | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 65       | 10.47%  |
| 2020    | 48       | 7.73%   |
| 2017    | 48       | 7.73%   |
| 2011    | 47       | 7.57%   |
| 2014    | 46       | 7.41%   |
| 2012    | 45       | 7.25%   |
| 2019    | 41       | 6.6%    |
| 2013    | 41       | 6.6%    |
| 2009    | 40       | 6.44%   |
| 2008    | 34       | 5.48%   |
| 2007    | 31       | 4.99%   |
| 2015    | 29       | 4.67%   |
| 2010    | 29       | 4.67%   |
| 2021    | 26       | 4.19%   |
| 2016    | 21       | 3.38%   |
| 2006    | 13       | 2.09%   |
| 2022    | 8        | 1.29%   |
| 2005    | 5        | 0.81%   |
| 2004    | 2        | 0.32%   |
| 2000    | 1        | 0.16%   |
| Unknown | 1        | 0.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 621      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 611      | 98.23%  |
| Enabled  | 11       | 1.77%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 621      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 129      | 20.22%  |
| 16.01-24.0  | 128      | 20.06%  |
| 3.01-4.0    | 123      | 19.28%  |
| 32.01-64.0  | 97       | 15.2%   |
| 4.01-8.0    | 75       | 11.76%  |
| 1.01-2.0    | 31       | 4.86%   |
| 64.01-256.0 | 25       | 3.92%   |
| 24.01-32.0  | 16       | 2.51%   |
| 2.01-3.0    | 12       | 1.88%   |
| 0.51-1.0    | 1        | 0.16%   |
| 0.01-0.5    | 1        | 0.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 259      | 37.05%  |
| 2.01-3.0   | 154      | 22.03%  |
| 4.01-8.0   | 99       | 14.16%  |
| 3.01-4.0   | 74       | 10.59%  |
| 0.51-1.0   | 53       | 7.58%   |
| 8.01-16.0  | 40       | 5.72%   |
| 0.01-0.5   | 9        | 1.29%   |
| 16.01-24.0 | 5        | 0.72%   |
| 32.01-64.0 | 3        | 0.43%   |
| 24.01-32.0 | 2        | 0.29%   |
| Unknown    | 1        | 0.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 253      | 38.74%  |
| 2      | 179      | 27.41%  |
| 3      | 106      | 16.23%  |
| 4      | 52       | 7.96%   |
| 5      | 31       | 4.75%   |
| 6      | 10       | 1.53%   |
| 7      | 9        | 1.38%   |
| 0      | 8        | 1.23%   |
| 8      | 4        | 0.61%   |
| 9      | 1        | 0.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 325      | 51.67%  |
| Yes       | 304      | 48.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 616      | 99.19%  |
| No        | 5        | 0.81%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 444      | 70.7%   |
| Yes       | 184      | 29.3%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 471      | 75.12%  |
| Yes       | 156      | 24.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Czechia | 621      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Desktops | Percent |
|---------------------|----------|---------|
| Prague              | 186      | 28.66%  |
| Brno                | 51       | 7.86%   |
| Ostrava             | 22       | 3.39%   |
| Pilsen              | 16       | 2.47%   |
| Hradec Králové    | 14       | 2.16%   |
| Liberec             | 13       | 2%      |
| Pardubice           | 11       | 1.69%   |
| České Budějovice | 11       | 1.69%   |
| Olomouc             | 10       | 1.54%   |
| Zlín               | 9        | 1.39%   |
| Litoměřice        | 6        | 0.92%   |
| Havířov           | 6        | 0.92%   |
| Znojmo              | 5        | 0.77%   |
| Uherské Hradiště | 5        | 0.77%   |
| Sokolov             | 4        | 0.62%   |
| Přerov             | 4        | 0.62%   |
| Ponetovice          | 4        | 0.62%   |
| Most                | 4        | 0.62%   |
| Mladá Boleslav     | 4        | 0.62%   |
| Frýdek-Místek     | 4        | 0.62%   |
| Cheb                | 4        | 0.62%   |
| Český Těšín    | 4        | 0.62%   |
| Zdar                | 3        | 0.46%   |
| Zdanice             | 3        | 0.46%   |
| Vitkov              | 3        | 0.46%   |
| Teplice             | 3        | 0.46%   |
| Rumburk             | 3        | 0.46%   |
| Rakvice             | 3        | 0.46%   |
| Opava               | 3        | 0.46%   |
| Novy Jicin          | 3        | 0.46%   |
| Neratovice          | 3        | 0.46%   |
| Jirikov             | 3        | 0.46%   |
| Děčín            | 3        | 0.46%   |
| Česká Lípa       | 3        | 0.46%   |
| As                  | 3        | 0.46%   |
| Zidlochovice        | 2        | 0.31%   |
| Zelenec             | 2        | 0.31%   |
| Zbysov              | 2        | 0.31%   |
| Vyškov             | 2        | 0.31%   |
| Vsetin              | 2        | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 272      | 517    | 24.35%  |
| Seagate                     | 234      | 381    | 20.95%  |
| Samsung Electronics         | 171      | 264    | 15.31%  |
| Kingston                    | 98       | 137    | 8.77%   |
| A-DATA Technology           | 41       | 52     | 3.67%   |
| Crucial                     | 37       | 42     | 3.31%   |
| Toshiba                     | 35       | 39     | 3.13%   |
| Hitachi                     | 33       | 38     | 2.95%   |
| Patriot                     | 23       | 29     | 2.06%   |
| Intel                       | 20       | 25     | 1.79%   |
| SanDisk                     | 17       | 23     | 1.52%   |
| Unknown                     | 10       | 20     | 0.9%    |
| Apacer                      | 10       | 12     | 0.9%    |
| OCZ                         | 9        | 29     | 0.81%   |
| Maxtor                      | 9        | 13     | 0.81%   |
| Gigabyte Technology         | 9        | 14     | 0.81%   |
| Transcend                   | 8        | 15     | 0.72%   |
| Phison                      | 8        | 12     | 0.72%   |
| HGST                        | 7        | 8      | 0.63%   |
| XPG                         | 6        | 13     | 0.54%   |
| Verbatim                    | 5        | 5      | 0.45%   |
| Silicon Motion              | 5        | 5      | 0.45%   |
| Realtek Semiconductor       | 3        | 6      | 0.27%   |
| Micron/Crucial Technology   | 3        | 3      | 0.27%   |
| Micron Technology           | 3        | 4      | 0.27%   |
| Kingston Technology Company | 3        | 3      | 0.27%   |
| Goodram                     | 3        | 3      | 0.27%   |
| UMAX                        | 2        | 2      | 0.18%   |
| SPCC                        | 2        | 2      | 0.18%   |
| SK hynix                    | 2        | 2      | 0.18%   |
| pqi                         | 2        | 2      | 0.18%   |
| LITEONIT                    | 2        | 2      | 0.18%   |
| Corsair                     | 2        | 2      | 0.18%   |
| China                       | 2        | 2      | 0.18%   |
| Western Digital             | 1        | 1      | 0.09%   |
| WDC WUH                     | 1        | 1      | 0.09%   |
| WDC WDS1                    | 1        | 1      | 0.09%   |
| Team                        | 1        | 1      | 0.09%   |
| TCSUNBOW                    | 1        | 1      | 0.09%   |
| T-CREATE                    | 1        | 1      | 0.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 20       | 1.51%   |
| Samsung SSD 860 EVO 500GB                           | 15       | 1.13%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 14       | 1.06%   |
| Seagate ST2000DM008-2FR102 2TB                      | 13       | 0.98%   |
| Seagate ST1000DM010-2EP102 1TB                      | 13       | 0.98%   |
| Samsung NVMe SSD Drive 500GB                        | 13       | 0.98%   |
| Kingston SA400S37120G 120GB SSD                     | 13       | 0.98%   |
| Seagate ST3500418AS 500GB                           | 12       | 0.91%   |
| WDC WD30EFRX-68EUZN0 3TB                            | 11       | 0.83%   |
| Samsung SSD 850 EVO 250GB                           | 11       | 0.83%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 9        | 0.68%   |
| WDC WD10EZEX-08M2NA0 1TB                            | 9        | 0.68%   |
| Seagate ST500DM002-1BD142 500GB                     | 8        | 0.6%    |
| Seagate ST4000DM004-2CV104 4TB                      | 8        | 0.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 8        | 0.6%    |
| Patriot Burst 120GB SSD                             | 8        | 0.6%    |
| Kingston SA400S37480G 480GB SSD                     | 8        | 0.6%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 7        | 0.53%   |
| Toshiba DT01ACA100 1TB                              | 7        | 0.53%   |
| Seagate ST3250318AS 250GB                           | 7        | 0.53%   |
| Seagate ST2000DM001-1ER164 2TB                      | 7        | 0.53%   |
| Seagate ST1000DM003-1ER162 1TB                      | 7        | 0.53%   |
| Samsung SSD 860 EVO 1TB                             | 7        | 0.53%   |
| Samsung HD322HJ 320GB                               | 7        | 0.53%   |
| Samsung HD103SI 1TB                                 | 7        | 0.53%   |
| Kingston SV300S37A120G 120GB SSD                    | 7        | 0.53%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 6        | 0.45%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB              | 6        | 0.45%   |
| WDC WD5000AAKX-60U6AA0 500GB                        | 5        | 0.38%   |
| WDC WD20EARX-00PASB0 2TB                            | 5        | 0.38%   |
| WDC WD10EZRZ-00HTKB0 1TB                            | 5        | 0.38%   |
| Seagate ST4000VN008-2DR166 4TB                      | 5        | 0.38%   |
| Seagate ST3160815AS 160GB                           | 5        | 0.38%   |
| Seagate ST250DM000-1BD141 250GB                     | 5        | 0.38%   |
| Seagate ST2000DM001-1CH164 2TB                      | 5        | 0.38%   |
| Samsung SSD 980 1TB                                 | 5        | 0.38%   |
| Samsung SSD 970 EVO 500GB                           | 5        | 0.38%   |
| Samsung SSD 850 EVO 500GB                           | 5        | 0.38%   |
| Samsung HD321KJ 320GB                               | 5        | 0.38%   |
| Kingston SV300S37A240G 240GB SSD                    | 5        | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 236      | 445    | 40%     |
| Seagate             | 226      | 365    | 38.31%  |
| Samsung Electronics | 45       | 68     | 7.63%   |
| Hitachi             | 33       | 38     | 5.59%   |
| Toshiba             | 29       | 30     | 4.92%   |
| Maxtor              | 9        | 13     | 1.53%   |
| HGST                | 7        | 8      | 1.19%   |
| Unknown             | 2        | 2      | 0.34%   |
| pqi                 | 2        | 2      | 0.34%   |
| Fujitsu             | 1        | 2      | 0.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 80       | 113    | 21%     |
| Samsung Electronics | 72       | 93     | 18.9%   |
| WDC                 | 47       | 61     | 12.34%  |
| A-DATA Technology   | 38       | 47     | 9.97%   |
| Crucial             | 34       | 39     | 8.92%   |
| Patriot             | 22       | 28     | 5.77%   |
| Intel               | 12       | 15     | 3.15%   |
| Apacer              | 10       | 12     | 2.62%   |
| Transcend           | 8        | 15     | 2.1%    |
| SanDisk             | 8        | 11     | 2.1%    |
| OCZ                 | 7        | 11     | 1.84%   |
| Verbatim            | 5        | 5      | 1.31%   |
| Toshiba             | 3        | 4      | 0.79%   |
| Seagate             | 3        | 3      | 0.79%   |
| Goodram             | 3        | 3      | 0.79%   |
| Gigabyte Technology | 3        | 5      | 0.79%   |
| UMAX                | 2        | 2      | 0.52%   |
| SPCC                | 2        | 2      | 0.52%   |
| SK hynix            | 2        | 2      | 0.52%   |
| Micron Technology   | 2        | 2      | 0.52%   |
| LITEONIT            | 2        | 2      | 0.52%   |
| China               | 2        | 2      | 0.52%   |
| WDC WDS1            | 1        | 1      | 0.26%   |
| Unknown             | 1        | 7      | 0.26%   |
| Team                | 1        | 1      | 0.26%   |
| TCSUNBOW            | 1        | 1      | 0.26%   |
| T-CREATE            | 1        | 1      | 0.26%   |
| SATAFIRM            | 1        | 1      | 0.26%   |
| Phison              | 1        | 1      | 0.26%   |
| LITEON              | 1        | 2      | 0.26%   |
| Kingchuxing         | 1        | 1      | 0.26%   |
| Innodisk            | 1        | 1      | 0.26%   |
| FORESEE             | 1        | 1      | 0.26%   |
| Emtec               | 1        | 1      | 0.26%   |
| ADATA SP            | 1        | 1      | 0.26%   |
| Unknown             | 1        | 1      | 0.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 456      | 973    | 49.09%  |
| SSD     | 314      | 498    | 33.8%   |
| NVMe    | 151      | 266    | 16.25%  |
| Unknown | 5        | 6      | 0.54%   |
| MMC     | 3        | 6      | 0.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 575      | 1450   | 76.26%  |
| NVMe | 151      | 266    | 20.03%  |
| SAS  | 25       | 27     | 3.32%   |
| MMC  | 3        | 6      | 0.4%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 474      | 835    | 55.37%  |
| 0.51-1.0   | 208      | 314    | 24.3%   |
| 1.01-2.0   | 77       | 160    | 9%      |
| 3.01-4.0   | 30       | 45     | 3.5%    |
| 2.01-3.0   | 29       | 47     | 3.39%   |
| 4.01-10.0  | 23       | 44     | 2.69%   |
| 10.01-20.0 | 15       | 26     | 1.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 168      | 25.04%  |
| 251-500        | 118      | 17.59%  |
| 501-1000       | 70       | 10.43%  |
| 1-20           | 65       | 9.69%   |
| 1001-2000      | 64       | 9.54%   |
| More than 3000 | 60       | 8.94%   |
| 51-100         | 42       | 6.26%   |
| Unknown        | 34       | 5.07%   |
| 2001-3000      | 26       | 3.87%   |
| 21-50          | 24       | 3.58%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 258      | 37.5%   |
| 21-50          | 85       | 12.35%  |
| 101-250        | 72       | 10.47%  |
| 51-100         | 58       | 8.43%   |
| 501-1000       | 52       | 7.56%   |
| 251-500        | 46       | 6.69%   |
| 1001-2000      | 34       | 4.94%   |
| Unknown        | 34       | 4.94%   |
| More than 3000 | 31       | 4.51%   |
| 2001-3000      | 18       | 2.62%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| WDC WD60EFRX-68L0BN1 6TB                     | 2        | 3      | 2.44%   |
| Seagate ST2000DM008-2FR102 2TB               | 2        | 3      | 2.44%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD             | 1        | 1      | 1.22%   |
| WDC WDS120G2G0A-00JH30 120GB SSD             | 1        | 1      | 1.22%   |
| WDC WDS100T2B0A-00SM50 1TB SSD               | 1        | 1      | 1.22%   |
| WDC WD800BB-00JHA0 80GB                      | 1        | 1      | 1.22%   |
| WDC WD7500AADS-00M2B0 752GB                  | 1        | 1      | 1.22%   |
| WDC WD6400AAKS-22A7B2 640GB                  | 1        | 1      | 1.22%   |
| WDC WD5000AAKS-00V0A0 500GB                  | 1        | 1      | 1.22%   |
| WDC WD3200AAKS-00L9A0 320GB                  | 1        | 1      | 1.22%   |
| WDC WD30EFRX-68EUZN0 3TB                     | 1        | 1      | 1.22%   |
| WDC WD2502ABYS-02B7A0 256GB                  | 1        | 1      | 1.22%   |
| WDC WD2500BEVS-22UST0 250GB                  | 1        | 1      | 1.22%   |
| WDC WD2500AAKX-75U6AA0 250GB                 | 1        | 1      | 1.22%   |
| WDC WD2500AAKX-60U6AA0 250GB                 | 1        | 1      | 1.22%   |
| WDC WD2500AAKX-603CA0 250GB                  | 1        | 1      | 1.22%   |
| WDC WD2500AAKX-083CA1 250GB                  | 1        | 2      | 1.22%   |
| WDC WD2500AAKS-00VSA0 250GB                  | 1        | 1      | 1.22%   |
| WDC WD2500AAJS-08L7A0 250GB                  | 1        | 2      | 1.22%   |
| WDC WD20EARX-008FB0 2TB                      | 1        | 4      | 1.22%   |
| WDC WD20EARS-00MVWB0 2TB                     | 1        | 1      | 1.22%   |
| WDC WD10JPCX-24UE4T0 1TB                     | 1        | 1      | 1.22%   |
| WDC WD10EZRX-00L4HB0 1TB                     | 1        | 1      | 1.22%   |
| WDC WD10EZEX-75M2NA0 1TB                     | 1        | 1      | 1.22%   |
| WDC WD10EZEX-35M2NA0 1TB                     | 1        | 1      | 1.22%   |
| WDC WD10EZEX-08WN4A0 1TB                     | 1        | 1      | 1.22%   |
| WDC WD10EADS-00M2B0 1TB                      | 1        | 1      | 1.22%   |
| WDC WD1001FALS-40K1B0 1TB                    | 1        | 1      | 1.22%   |
| WDC WD Blue SA510 M.2 2280 1000GB            | 1        | 1      | 1.22%   |
| WDC WD Blue SA510 2.5 500GB                  | 1        | 1      | 1.22%   |
| Toshiba DT01ACA100 1TB                       | 1        | 2      | 1.22%   |
| Seagate ST8000VN0002-1Z8112 8TB              | 1        | 1      | 1.22%   |
| Seagate ST500LT012-9WS142 500GB              | 1        | 2      | 1.22%   |
| Seagate ST500LT0 12-1DG142 500GB             | 1        | 1      | 1.22%   |
| Seagate ST500DM005 HD502HJ 500GB             | 1        | 3      | 1.22%   |
| Seagate ST500DM002-1SB10A 500GB              | 1        | 1      | 1.22%   |
| Seagate ST3500514NS 39M4517 42C0468IBM 500GB | 1        | 1      | 1.22%   |
| Seagate ST3500410SV 500GB                    | 1        | 1      | 1.22%   |
| Seagate ST3320620A 320GB                     | 1        | 1      | 1.22%   |
| Seagate ST3250620NS 250GB                    | 1        | 2      | 1.22%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 27       | 36     | 34.18%  |
| Seagate               | 24       | 33     | 30.38%  |
| Samsung Electronics   | 9        | 10     | 11.39%  |
| Hitachi               | 4        | 4      | 5.06%   |
| Kingston              | 3        | 3      | 3.8%    |
| Micron Technology     | 2        | 2      | 2.53%   |
| HGST                  | 2        | 2      | 2.53%   |
| Crucial               | 2        | 2      | 2.53%   |
| Toshiba               | 1        | 2      | 1.27%   |
| SATAFIRM              | 1        | 1      | 1.27%   |
| Realtek Semiconductor | 1        | 4      | 1.27%   |
| Maxtor                | 1        | 1      | 1.27%   |
| Gigabyte Technology   | 1        | 1      | 1.27%   |
| A-DATA Technology     | 1        | 2      | 1.27%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 24       | 33     | 38.1%   |
| WDC                 | 23       | 31     | 36.51%  |
| Samsung Electronics | 8        | 8      | 12.7%   |
| Hitachi             | 4        | 4      | 6.35%   |
| HGST                | 2        | 2      | 3.17%   |
| Toshiba             | 1        | 2      | 1.59%   |
| Maxtor              | 1        | 1      | 1.59%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 61       | 81     | 78.21%  |
| SSD  | 14       | 15     | 17.95%  |
| NVMe | 3        | 7      | 3.85%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate ST3500418AS 500GB | 2        | 3      | 66.67%  |
| Unknown 00000  16GB       | 1        | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 2        | 3      | 66.67%  |
| Unknown | 1        | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 365      | 999    | 52.44%  |
| Works    | 253      | 643    | 36.35%  |
| Malfunc  | 75       | 103    | 10.78%  |
| Failed   | 3        | 4      | 0.43%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 362      | 41%     |
| AMD                           | 233      | 26.39%  |
| Samsung Electronics           | 70       | 7.93%   |
| JMicron Technology            | 31       | 3.51%   |
| Nvidia                        | 24       | 2.72%   |
| Marvell Technology Group      | 24       | 2.72%   |
| Kingston Technology Company   | 24       | 2.72%   |
| ASMedia Technology            | 24       | 2.72%   |
| SanDisk                       | 16       | 1.81%   |
| Phison Electronics            | 12       | 1.36%   |
| ADATA Technology              | 10       | 1.13%   |
| Silicon Motion                | 8        | 0.91%   |
| VIA Technologies              | 7        | 0.79%   |
| Seagate Technology            | 7        | 0.79%   |
| Micron/Crucial Technology     | 5        | 0.57%   |
| Toshiba America Info Systems  | 4        | 0.45%   |
| Silicon Image                 | 4        | 0.45%   |
| Realtek Semiconductor         | 4        | 0.45%   |
| OCZ Technology Group          | 2        | 0.23%   |
| Integrated Technology Express | 2        | 0.23%   |
| Adaptec                       | 2        | 0.23%   |
| Western Digital               | 1        | 0.11%   |
| Solidigm                      | 1        | 0.11%   |
| Promise Technology            | 1        | 0.11%   |
| Micron Technology             | 1        | 0.11%   |
| LSI Logic / Symbios Logic     | 1        | 0.11%   |
| INNOGRIT                      | 1        | 0.11%   |
| Chelsio Communications        | 1        | 0.11%   |
| 3ware                         | 1        | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 128      | 10.99%  |
| AMD 400 Series Chipset SATA Controller                                                  | 48       | 4.12%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 42       | 3.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 41       | 3.52%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 40       | 3.43%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 35       | 3%      |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 32       | 2.75%   |
| AMD 500 Series Chipset SATA Controller                                                  | 32       | 2.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 30       | 2.58%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 28       | 2.4%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 28       | 2.4%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 25       | 2.15%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 22       | 1.89%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 22       | 1.89%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 20       | 1.72%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 20       | 1.72%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 17       | 1.46%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 17       | 1.46%   |
| AMD 300 Series Chipset SATA Controller                                                  | 17       | 1.46%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 14       | 1.2%    |
| Intel SATA Controller [RAID mode]                                                       | 13       | 1.12%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 12       | 1.03%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 12       | 1.03%   |
| Samsung NVMe SSD Controller 980                                                         | 11       | 0.94%   |
| Nvidia MCP61 SATA Controller                                                            | 11       | 0.94%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 11       | 0.94%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 11       | 0.94%   |
| Nvidia MCP61 IDE                                                                        | 10       | 0.86%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 10       | 0.86%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 10       | 0.86%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 9        | 0.77%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 9        | 0.77%   |
| Kingston Company A2000 NVMe SSD                                                         | 9        | 0.77%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 8        | 0.69%   |
| JMicron JMB368 IDE controller                                                           | 8        | 0.69%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 8        | 0.69%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 8        | 0.69%   |
| Kingston Company Company Non-Volatile memory controller                                 | 7        | 0.6%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 7        | 0.6%    |
| Intel 82Q35 Express PT IDER Controller                                                  | 7        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 480      | 55.17%  |
| IDE  | 198      | 22.76%  |
| NVMe | 155      | 17.82%  |
| RAID | 28       | 3.22%   |
| SAS  | 5        | 0.57%   |
| SCSI | 4        | 0.46%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 368      | 59.26%  |
| AMD    | 253      | 40.74%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 16       | 2.54%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 13       | 2.06%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 12       | 1.9%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 11       | 1.75%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 10       | 1.59%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 9        | 1.43%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 8        | 1.27%   |
| AMD FX-8350 Eight-Core Processor            | 8        | 1.27%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 7        | 1.11%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 7        | 1.11%   |
| AMD FX-6300 Six-Core Processor              | 7        | 1.11%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 6        | 0.95%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 6        | 0.95%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 6        | 0.95%   |
| AMD FX-8300 Eight-Core Processor            | 6        | 0.95%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 5        | 0.79%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 5        | 0.79%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 5        | 0.79%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 5        | 0.79%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 5        | 0.79%   |
| AMD FX-4300 Quad-Core Processor             | 5        | 0.79%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 4        | 0.63%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 4        | 0.63%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 4        | 0.63%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 4        | 0.63%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 4        | 0.63%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 4        | 0.63%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 4        | 0.63%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 4        | 0.63%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 4        | 0.63%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 4        | 0.63%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 4        | 0.63%   |
| Intel Core 2 Duo CPU E6750 @ 2.66GHz        | 4        | 0.63%   |
| Intel Core 2 CPU 6300 @ 1.86GHz             | 4        | 0.63%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 4        | 0.63%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 4        | 0.63%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 4        | 0.63%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 4        | 0.63%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 4        | 0.63%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 3        | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 97       | 15.42%  |
| AMD Ryzen 5             | 71       | 11.29%  |
| Intel Core i7           | 47       | 7.47%   |
| Intel Core 2 Duo        | 40       | 6.36%   |
| Intel Core i3           | 32       | 5.09%   |
| AMD FX                  | 32       | 5.09%   |
| AMD Ryzen 7             | 31       | 4.93%   |
| Intel Pentium           | 27       | 4.29%   |
| Intel Celeron           | 23       | 3.66%   |
| Intel Xeon              | 20       | 3.18%   |
| AMD Ryzen 9             | 20       | 3.18%   |
| Intel Pentium Dual-Core | 16       | 2.54%   |
| Other                   | 15       | 2.38%   |
| AMD Athlon 64 X2        | 12       | 1.91%   |
| Intel Core 2 Quad       | 11       | 1.75%   |
| AMD Ryzen 3             | 10       | 1.59%   |
| AMD Phenom II X4        | 9        | 1.43%   |
| AMD A8                  | 9        | 1.43%   |
| Intel Pentium Dual      | 8        | 1.27%   |
| AMD Athlon              | 8        | 1.27%   |
| Intel Core 2            | 7        | 1.11%   |
| AMD Athlon II X2        | 7        | 1.11%   |
| AMD A10                 | 7        | 1.11%   |
| AMD A4                  | 6        | 0.95%   |
| Intel Pentium 4         | 5        | 0.79%   |
| Intel Core i9           | 5        | 0.79%   |
| Intel Atom              | 5        | 0.79%   |
| AMD Sempron             | 5        | 0.79%   |
| Intel Pentium Gold      | 4        | 0.64%   |
| Intel Pentium D         | 4        | 0.64%   |
| AMD Athlon II X4        | 4        | 0.64%   |
| AMD Ryzen Threadripper  | 3        | 0.48%   |
| AMD Athlon II X3        | 3        | 0.48%   |
| AMD Athlon 64           | 3        | 0.48%   |
| Intel Pentium Silver    | 2        | 0.32%   |
| AMD Ryzen 5 PRO         | 2        | 0.32%   |
| AMD Phenom II X2        | 2        | 0.32%   |
| AMD Phenom              | 2        | 0.32%   |
| AMD Athlon X4           | 2        | 0.32%   |
| AMD Athlon Dual Core    | 2        | 0.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 205      | 32.54%  |
| 2       | 204      | 32.38%  |
| 6       | 103      | 16.35%  |
| 8       | 47       | 7.46%   |
| 1       | 27       | 4.29%   |
| 12      | 23       | 3.65%   |
| 3       | 12       | 1.9%    |
| 16      | 6        | 0.95%   |
| Unknown | 2        | 0.32%   |
| 10      | 1        | 0.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 619      | 99.68%  |
| 2      | 2        | 0.32%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 313      | 50.16%  |
| 2       | 308      | 49.36%  |
| Unknown | 2        | 0.32%   |
| 4       | 1        | 0.16%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 608      | 97.59%  |
| Unknown        | 7        | 1.12%   |
| 32-bit         | 6        | 0.96%   |
| 64-bit         | 2        | 0.32%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 135      | 20.74%  |
| 0x306c3    | 47       | 7.22%   |
| 0x1067a    | 37       | 5.68%   |
| 0x206a7    | 34       | 5.22%   |
| 0x08701021 | 22       | 3.38%   |
| 0x906ea    | 19       | 2.92%   |
| 0x06000852 | 19       | 2.92%   |
| 0x506e3    | 18       | 2.76%   |
| 0x306a9    | 17       | 2.61%   |
| 0x0800820d | 16       | 2.46%   |
| 0x6fb      | 14       | 2.15%   |
| 0x010000c8 | 14       | 2.15%   |
| 0x906e9    | 13       | 2%      |
| 0x08701013 | 13       | 2%      |
| 0x08001138 | 11       | 1.69%   |
| 0x6fd      | 10       | 1.54%   |
| 0x10676    | 8        | 1.23%   |
| 0x0a201016 | 8        | 1.23%   |
| 0xa0653    | 7        | 1.08%   |
| 0x06001119 | 7        | 1.08%   |
| 0x0a201009 | 6        | 0.92%   |
| 0x06003106 | 6        | 0.92%   |
| 0x08101016 | 5        | 0.77%   |
| 0x0810100b | 5        | 0.77%   |
| 0x03000027 | 5        | 0.77%   |
| 0x010000db | 5        | 0.77%   |
| 0xa0655    | 4        | 0.61%   |
| 0x906ed    | 4        | 0.61%   |
| 0x906eb    | 4        | 0.61%   |
| 0x206d7    | 4        | 0.61%   |
| 0x0a601203 | 4        | 0.61%   |
| 0x0a50000c | 4        | 0.61%   |
| 0xa0671    | 3        | 0.46%   |
| 0x90675    | 3        | 0.46%   |
| 0x90672    | 3        | 0.46%   |
| 0x6f6      | 3        | 0.46%   |
| 0x30678    | 3        | 0.46%   |
| 0x20652    | 3        | 0.46%   |
| 0x106e5    | 3        | 0.46%   |
| 0x106a5    | 3        | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 62       | 9.94%   |
| Penryn           | 54       | 8.65%   |
| Zen 2            | 49       | 7.85%   |
| KabyLake         | 49       | 7.85%   |
| SandyBridge      | 46       | 7.37%   |
| Piledriver       | 37       | 5.93%   |
| Zen              | 34       | 5.45%   |
| Core             | 32       | 5.13%   |
| Zen 3            | 29       | 4.65%   |
| K10              | 29       | 4.65%   |
| IvyBridge        | 26       | 4.17%   |
| Zen+             | 23       | 3.69%   |
| Skylake          | 23       | 3.69%   |
| K8 Hammer        | 20       | 3.21%   |
| CometLake        | 13       | 2.08%   |
| NetBurst         | 11       | 1.76%   |
| Silvermont       | 10       | 1.6%    |
| Westmere         | 8        | 1.28%   |
| Steamroller      | 8        | 1.28%   |
| Unknown          | 8        | 1.28%   |
| Nehalem          | 7        | 1.12%   |
| Alderlake Hybrid | 7        | 1.12%   |
| K10 Llano        | 5        | 0.8%    |
| Excavator        | 5        | 0.8%    |
| Bonnell          | 5        | 0.8%    |
| Jaguar           | 4        | 0.64%   |
| Goldmont plus    | 4        | 0.64%   |
| Icelake          | 3        | 0.48%   |
| Goldmont         | 3        | 0.48%   |
| Bulldozer        | 3        | 0.48%   |
| Puma             | 2        | 0.32%   |
| TigerLake        | 1        | 0.16%   |
| P6               | 1        | 0.16%   |
| K6               | 1        | 0.16%   |
| Broadwell        | 1        | 0.16%   |
| Bobcat           | 1        | 0.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 260      | 39.27%  |
| AMD                        | 216      | 32.63%  |
| Intel                      | 184      | 27.79%  |
| Matrox Electronics Systems | 1        | 0.15%   |
| ASPEED Technology          | 1        | 0.15%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 38       | 5.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 34       | 4.92%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 26       | 3.76%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 19       | 2.75%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 18       | 2.6%    |
| Nvidia GK208B [GeForce GT 710]                                              | 14       | 2.03%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 12       | 1.74%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 11       | 1.59%   |
| Nvidia GK208B [GeForce GT 730]                                              | 11       | 1.59%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 11       | 1.59%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 10       | 1.45%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 10       | 1.45%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 9        | 1.3%    |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 9        | 1.3%    |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 9        | 1.3%    |
| Nvidia GM206 [GeForce GTX 960]                                              | 7        | 1.01%   |
| Intel HD Graphics 630                                                       | 7        | 1.01%   |
| Intel HD Graphics 530                                                       | 7        | 1.01%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 7        | 1.01%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 6        | 0.87%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 6        | 0.87%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 6        | 0.87%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 6        | 0.87%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 6        | 0.87%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 6        | 0.87%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 5        | 0.72%   |
| Nvidia GT218 [GeForce 210]                                                  | 5        | 0.72%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 5        | 0.72%   |
| Nvidia GF108 [GeForce GT 630]                                               | 5        | 0.72%   |
| Nvidia G86 [GeForce 8500 GT]                                                | 5        | 0.72%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 5        | 0.72%   |
| AMD RV670 [Radeon HD 3690/3850]                                             | 5        | 0.72%   |
| AMD RS780L [Radeon 3000]                                                    | 5        | 0.72%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 5        | 0.72%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 5        | 0.72%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4        | 0.58%   |
| Nvidia GF119 [GeForce GT 610]                                               | 4        | 0.58%   |
| Nvidia GF116 [GeForce GT 545]                                               | 4        | 0.58%   |
| Nvidia GF108 [GeForce GT 440]                                               | 4        | 0.58%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 4        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 241      | 38.07%  |
| 1 x AMD        | 194      | 30.65%  |
| 1 x Intel      | 162      | 25.59%  |
| 2 x AMD        | 11       | 1.74%   |
| Intel + Nvidia | 8        | 1.26%   |
| AMD + Nvidia   | 6        | 0.95%   |
| Intel + AMD    | 5        | 0.79%   |
| 3 x Nvidia     | 2        | 0.32%   |
| 2 x Nvidia     | 2        | 0.32%   |
| 1 x Matrox     | 1        | 0.16%   |
| 1 x ASPEED     | 1        | 0.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 482      | 75.31%  |
| Proprietary | 132      | 20.63%  |
| Unknown     | 26       | 4.06%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 251      | 38.32%  |
| 0.01-0.5   | 85       | 12.98%  |
| 1.01-2.0   | 82       | 12.52%  |
| 0.51-1.0   | 77       | 11.76%  |
| 3.01-4.0   | 55       | 8.4%    |
| 7.01-8.0   | 52       | 7.94%   |
| 5.01-6.0   | 19       | 2.9%    |
| 2.01-3.0   | 16       | 2.44%   |
| 8.01-16.0  | 15       | 2.29%   |
| 16.01-24.0 | 3        | 0.46%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 104      | 15.29%  |
| Goldstar             | 68       | 10%     |
| Dell                 | 67       | 9.85%   |
| BenQ                 | 64       | 9.41%   |
| Acer                 | 62       | 9.12%   |
| Philips              | 41       | 6.03%   |
| Hewlett-Packard      | 40       | 5.88%   |
| AOC                  | 36       | 5.29%   |
| Ancor Communications | 36       | 5.29%   |
| Iiyama               | 21       | 3.09%   |
| Eizo                 | 14       | 2.06%   |
| Lenovo               | 12       | 1.76%   |
| Sony                 | 11       | 1.62%   |
| ASUSTek Computer     | 11       | 1.62%   |
| Fujitsu Siemens      | 10       | 1.47%   |
| NEC Computers        | 9        | 1.32%   |
| ViewSonic            | 6        | 0.88%   |
| Vestel Elektronik    | 6        | 0.88%   |
| Panasonic            | 6        | 0.88%   |
| LG Electronics       | 6        | 0.88%   |
| Unknown              | 5        | 0.74%   |
| MSI                  | 4        | 0.59%   |
| Lenovo Group Limited | 3        | 0.44%   |
| Belinea              | 3        | 0.44%   |
| Onkyo                | 2        | 0.29%   |
| MStar                | 2        | 0.29%   |
| CON                  | 2        | 0.29%   |
| CHR                  | 2        | 0.29%   |
| Arnos Instruments    | 2        | 0.29%   |
| Wacom                | 1        | 0.15%   |
| Vestel               | 1        | 0.15%   |
| Sharp                | 1        | 0.15%   |
| S2-Tek               | 1        | 0.15%   |
| OEM                  | 1        | 0.15%   |
| MiTAC                | 1        | 0.15%   |
| Microstep            | 1        | 0.15%   |
| LLL                  | 1        | 0.15%   |
| JVC                  | 1        | 0.15%   |
| Jean                 | 1        | 0.15%   |
| Idek Iiyama          | 1        | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 7        | 0.95%   |
| Vestel Elektronik 43UHD_LCD_TV VES3700 3840x2160 950x540mm 43.0-inch  | 6        | 0.82%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 5        | 0.68%   |
| BenQ GW2470 BNQ78D9 1920x1080 527x296mm 23.8-inch                     | 5        | 0.68%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 4        | 0.54%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 4        | 0.54%   |
| Iiyama PL4840 IVM1065 1920x1080 1054x593mm 47.6-inch                  | 4        | 0.54%   |
| BenQ G2220HD BNQ7820 1920x1080 477x268mm 21.5-inch                    | 4        | 0.54%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 4        | 0.54%   |
| AOC 27P2DG5 AOC2702 1920x1080 598x336mm 27.0-inch                     | 4        | 0.54%   |
| AOC 2770M AOC2770 1920x1080 598x336mm 27.0-inch                       | 4        | 0.54%   |
| Samsung Electronics S22C450 SAM09C7 1680x1050 473x291mm 21.9-inch     | 3        | 0.41%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3        | 0.41%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch               | 3        | 0.41%   |
| Panasonic TV MEIC303 1920x1080 698x392mm 31.5-inch                    | 3        | 0.41%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 600x340mm 27.2-inch              | 3        | 0.41%   |
| Goldstar W2243 GSM56FF 1920x1080 477x269mm 21.6-inch                  | 3        | 0.41%   |
| Dell U2410 DELF016 1920x1200 518x324mm 24.1-inch                      | 3        | 0.41%   |
| Dell P190S DEL405A 1280x1024 376x301mm 19.0-inch                      | 3        | 0.41%   |
| BenQ GW2760 BNQ78C6 1920x1080 598x336mm 27.0-inch                     | 3        | 0.41%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 3        | 0.41%   |
| BenQ G2220HD BNQ7821 1920x1080 477x268mm 21.5-inch                    | 3        | 0.41%   |
| Ancor Communications VE228 ACI22FA 1920x1080 531x299mm 24.0-inch      | 3        | 0.41%   |
| Ancor Communications ASUS VH192 ACI19E4 1366x768 410x230mm 18.5-inch  | 3        | 0.41%   |
| Ancor Communications ASUS VB191 ACI19B4 1280x1024 340x270mm 17.1-inch | 3        | 0.41%   |
| Acer P226HQV ACR01C7 1920x1080 477x268mm 21.5-inch                    | 3        | 0.41%   |
| Acer G247HL ACR03FA 1920x1080 531x299mm 24.0-inch                     | 3        | 0.41%   |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                     | 3        | 0.41%   |
| Sony SDM-HS73 SNY2270 1280x1024 338x270mm 17.0-inch                   | 2        | 0.27%   |
| Samsung Electronics SyncMaster SAM05CC 1920x1080 530x300mm 24.0-inch  | 2        | 0.27%   |
| Samsung Electronics SyncMaster SAM05C8 1920x1080 520x290mm 23.4-inch  | 2        | 0.27%   |
| Samsung Electronics SyncMaster SAM0593 1920x1080 477x268mm 21.5-inch  | 2        | 0.27%   |
| Samsung Electronics SyncMaster SAM03D0 1440x900 410x257mm 19.1-inch   | 2        | 0.27%   |
| Samsung Electronics SyncMaster SAM0380 1680x1050 459x296mm 21.5-inch  | 2        | 0.27%   |
| Samsung Electronics SyncMaster SAM030C 1680x1050 474x296mm 22.0-inch  | 2        | 0.27%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch     | 2        | 0.27%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch     | 2        | 0.27%   |
| Samsung Electronics S22C450 SAM09C6 1680x1050 470x290mm 21.7-inch     | 2        | 0.27%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1080                  | 2        | 0.27%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch | 2        | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 301      | 45.33%  |
| 1280x1024 (SXGA)   | 62       | 9.34%   |
| 2560x1440 (QHD)    | 52       | 7.83%   |
| 1680x1050 (WSXGA+) | 52       | 7.83%   |
| 3840x2160 (4K)     | 49       | 7.38%   |
| 1920x1200 (WUXGA)  | 36       | 5.42%   |
| 1440x900 (WXGA+)   | 19       | 2.86%   |
| 1366x768 (WXGA)    | 11       | 1.66%   |
| Unknown            | 11       | 1.66%   |
| 3440x1440          | 8        | 1.2%    |
| 2560x1080          | 8        | 1.2%    |
| 3840x1080          | 7        | 1.05%   |
| 1024x768 (XGA)     | 6        | 0.9%    |
| 1600x1200          | 5        | 0.75%   |
| 1360x768           | 5        | 0.75%   |
| 1280x720 (HD)      | 5        | 0.75%   |
| 2288x1287          | 4        | 0.6%    |
| 1920x540           | 3        | 0.45%   |
| 1600x900 (HD+)     | 3        | 0.45%   |
| 2560x1600          | 2        | 0.3%    |
| 1400x1050          | 2        | 0.3%    |
| 1280x768           | 2        | 0.3%    |
| 9600x2160          | 1        | 0.15%   |
| 7680x2160          | 1        | 0.15%   |
| 640x480            | 1        | 0.15%   |
| 6400x2160          | 1        | 0.15%   |
| 6400x1440          | 1        | 0.15%   |
| 6080x1440          | 1        | 0.15%   |
| 5840x1440          | 1        | 0.15%   |
| 5520x1080          | 1        | 0.15%   |
| 4240x1440          | 1        | 0.15%   |
| 3286x1080          | 1        | 0.15%   |
| 2048x1152          | 1        | 0.15%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 120      | 17.42%  |
| 27      | 90       | 13.06%  |
| 21      | 79       | 11.47%  |
| 23      | 77       | 11.18%  |
| 19      | 63       | 9.14%   |
| Unknown | 57       | 8.27%   |
| 22      | 33       | 4.79%   |
| 31      | 25       | 3.63%   |
| 20      | 20       | 2.9%    |
| 17      | 20       | 2.9%    |
| 34      | 15       | 2.18%   |
| 18      | 15       | 2.18%   |
| 84      | 8        | 1.16%   |
| 25      | 7        | 1.02%   |
| 72      | 5        | 0.73%   |
| 40      | 5        | 0.73%   |
| 32      | 5        | 0.73%   |
| 15      | 5        | 0.73%   |
| 65      | 4        | 0.58%   |
| 47      | 4        | 0.58%   |
| 39      | 4        | 0.58%   |
| 33      | 4        | 0.58%   |
| 54      | 3        | 0.44%   |
| 52      | 3        | 0.44%   |
| 46      | 3        | 0.44%   |
| 26      | 3        | 0.44%   |
| 48      | 2        | 0.29%   |
| 29      | 2        | 0.29%   |
| 28      | 2        | 0.29%   |
| 142     | 1        | 0.15%   |
| 59      | 1        | 0.15%   |
| 55      | 1        | 0.15%   |
| 43      | 1        | 0.15%   |
| 42      | 1        | 0.15%   |
| 13      | 1        | 0.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 265      | 40.21%  |
| 401-500        | 159      | 24.13%  |
| Unknown        | 57       | 8.65%   |
| 351-400        | 50       | 7.59%   |
| 601-700        | 33       | 5.01%   |
| 301-350        | 25       | 3.79%   |
| 701-800        | 23       | 3.49%   |
| 1001-1500      | 21       | 3.19%   |
| 1501-2000      | 13       | 1.97%   |
| 801-900        | 10       | 1.52%   |
| 901-1000       | 2        | 0.3%    |
| More than 2000 | 1        | 0.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 374      | 58.16%  |
| 16/10   | 113      | 17.57%  |
| 5/4     | 67       | 10.42%  |
| Unknown | 50       | 7.78%   |
| 4/3     | 15       | 2.33%   |
| 21/9    | 15       | 2.33%   |
| 3/2     | 5        | 0.78%   |
| 32/9    | 3        | 0.47%   |
| 1.00    | 1        | 0.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 239      | 35.36%  |
| 151-200        | 103      | 15.24%  |
| 301-350        | 92       | 13.61%  |
| Unknown        | 57       | 8.43%   |
| 251-300        | 52       | 7.69%   |
| 351-500        | 51       | 7.54%   |
| 141-150        | 29       | 4.29%   |
| More than 1000 | 26       | 3.85%   |
| 501-1000       | 21       | 3.11%   |
| 101-110        | 5        | 0.74%   |
| 81-90          | 1        | 0.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 411      | 64.32%  |
| 101-120 | 116      | 18.15%  |
| Unknown | 57       | 8.92%   |
| 1-50    | 24       | 3.76%   |
| 121-160 | 20       | 3.13%   |
| 161-240 | 11       | 1.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 496      | 77.5%   |
| 2     | 101      | 15.78%  |
| 0     | 29       | 4.53%   |
| 3     | 14       | 2.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 384      | 47.06%  |
| Intel                             | 216      | 26.47%  |
| Qualcomm Atheros                  | 59       | 7.23%   |
| Nvidia                            | 19       | 2.33%   |
| TP-Link                           | 17       | 2.08%   |
| Marvell Technology Group          | 15       | 1.84%   |
| Broadcom                          | 13       | 1.59%   |
| Qualcomm Atheros Communications   | 12       | 1.47%   |
| Ralink Technology                 | 11       | 1.35%   |
| Broadcom Limited                  | 7        | 0.86%   |
| Ralink                            | 6        | 0.74%   |
| Microsoft                         | 6        | 0.74%   |
| ASUSTek Computer                  | 6        | 0.74%   |
| D-Link                            | 4        | 0.49%   |
| ZyDAS                             | 3        | 0.37%   |
| Xiaomi                            | 3        | 0.37%   |
| VIA Technologies                  | 3        | 0.37%   |
| OnePlus Technology (Shenzhen)     | 3        | 0.37%   |
| MediaTek                          | 3        | 0.37%   |
| Edimax Technology                 | 3        | 0.37%   |
| Samsung Electronics               | 2        | 0.25%   |
| D-Link System                     | 2        | 0.25%   |
| ZyXEL Communications              | 1        | 0.12%   |
| Texas Instruments                 | 1        | 0.12%   |
| Sundance Technology Inc / IC Plus | 1        | 0.12%   |
| SIEMENS                           | 1        | 0.12%   |
| Seeed Technology                  | 1        | 0.12%   |
| MICRORISC                         | 1        | 0.12%   |
| Mercucys                          | 1        | 0.12%   |
| Mellanox Technologies             | 1        | 0.12%   |
| LSI                               | 1        | 0.12%   |
| Intersil                          | 1        | 0.12%   |
| Huawei Technologies               | 1        | 0.12%   |
| Google                            | 1        | 0.12%   |
| Dresden Elektronik                | 1        | 0.12%   |
| Chelsio Communications            | 1        | 0.12%   |
| ASIX Electronics                  | 1        | 0.12%   |
| Arduino SA                        | 1        | 0.12%   |
| Aquantia                          | 1        | 0.12%   |
| American Megatrends               | 1        | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 312      | 34.94%  |
| Intel I211 Gigabit Network Connection                             | 35       | 3.92%   |
| Realtek RTL8125 2.5GbE Controller                                 | 33       | 3.7%    |
| Intel Wi-Fi 6 AX200                                               | 20       | 2.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 20       | 2.24%   |
| Intel Ethernet Connection (2) I219-V                              | 19       | 2.13%   |
| Intel Ethernet Connection I217-LM                                 | 18       | 2.02%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 15       | 1.68%   |
| Intel Ethernet Controller I225-V                                  | 14       | 1.57%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 11       | 1.23%   |
| Qualcomm Atheros AR9271 802.11n                                   | 11       | 1.23%   |
| Intel Ethernet Connection (7) I219-V                              | 11       | 1.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10       | 1.12%   |
| Intel Ethernet Connection (2) I218-V                              | 9        | 1.01%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 9        | 1.01%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 8        | 0.9%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 7        | 0.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 7        | 0.78%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 7        | 0.78%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 7        | 0.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 7        | 0.78%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6        | 0.67%   |
| Nvidia MCP61 Ethernet                                             | 6        | 0.67%   |
| Intel 82579V Gigabit Network Connection                           | 6        | 0.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 5        | 0.56%   |
| Ralink MT7601U Wireless Adapter                                   | 5        | 0.56%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 5        | 0.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5        | 0.56%   |
| Intel 82574L Gigabit Network Connection                           | 5        | 0.56%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 4        | 0.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4        | 0.45%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 4        | 0.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4        | 0.45%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4        | 0.45%   |
| Nvidia MCP73 Ethernet                                             | 4        | 0.45%   |
| Microsoft XBOX ACC                                                | 4        | 0.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4        | 0.45%   |
| ZyDAS ZD1211B 802.11g                                             | 3        | 0.34%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3        | 0.34%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 3        | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 54       | 28.27%  |
| Realtek Semiconductor           | 40       | 20.94%  |
| Qualcomm Atheros                | 17       | 8.9%    |
| TP-Link                         | 16       | 8.38%   |
| Qualcomm Atheros Communications | 12       | 6.28%   |
| Ralink Technology               | 11       | 5.76%   |
| Ralink                          | 6        | 3.14%   |
| Microsoft                       | 6        | 3.14%   |
| Broadcom                        | 5        | 2.62%   |
| ASUSTek Computer                | 5        | 2.62%   |
| D-Link                          | 4        | 2.09%   |
| ZyDAS                           | 3        | 1.57%   |
| MediaTek                        | 3        | 1.57%   |
| Edimax Technology               | 3        | 1.57%   |
| ZyXEL Communications            | 1        | 0.52%   |
| Texas Instruments               | 1        | 0.52%   |
| Mercucys                        | 1        | 0.52%   |
| Marvell Technology Group        | 1        | 0.52%   |
| Intersil                        | 1        | 0.52%   |
| D-Link System                   | 1        | 0.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                           | 20       | 10.47%  |
| Qualcomm Atheros AR9271 802.11n                                               | 11       | 5.76%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 7        | 3.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 7        | 3.66%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 7        | 3.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 5        | 2.62%   |
| Ralink MT7601U Wireless Adapter                                               | 5        | 2.62%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 5        | 2.62%   |
| Microsoft XBOX ACC                                                            | 4        | 2.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 4        | 2.09%   |
| ZyDAS ZD1211B 802.11g                                                         | 3        | 1.57%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                               | 3        | 1.57%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                               | 3        | 1.57%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 3        | 1.57%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 3        | 1.57%   |
| Realtek RTL8187 Wireless Adapter                                              | 3        | 1.57%   |
| Ralink RT5370 Wireless Adapter                                                | 3        | 1.57%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 3        | 1.57%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 3        | 1.57%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 3        | 1.57%   |
| Intel Wireless 8260                                                           | 3        | 1.57%   |
| Intel Wireless 7265                                                           | 3        | 1.57%   |
| Intel Wireless 3165                                                           | 3        | 1.57%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                         | 2        | 1.05%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 2        | 1.05%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                   | 2        | 1.05%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 2        | 1.05%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                    | 2        | 1.05%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 2        | 1.05%   |
| Ralink RT2561/RT61 802.11g PCI                                                | 2        | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 2        | 1.05%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 2        | 1.05%   |
| Microsoft Wireless XBox Controller Dongle                                     | 2        | 1.05%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 2        | 1.05%   |
| Intel Wireless-AC 9260                                                        | 2        | 1.05%   |
| Intel Centrino Wireless-N 2230                                                | 2        | 1.05%   |
| Intel Alder Lake-S PCH CNVi WiFi                                              | 2        | 1.05%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]          | 2        | 1.05%   |
| ZyXEL ZyAIR AG-225H v2 802.11bg                                               | 1        | 0.52%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1        | 0.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 366      | 55.12%  |
| Intel                             | 187      | 28.16%  |
| Qualcomm Atheros                  | 43       | 6.48%   |
| Nvidia                            | 19       | 2.86%   |
| Marvell Technology Group          | 15       | 2.26%   |
| Broadcom                          | 8        | 1.2%    |
| Broadcom Limited                  | 7        | 1.05%   |
| Xiaomi                            | 3        | 0.45%   |
| VIA Technologies                  | 2        | 0.3%    |
| Samsung Electronics               | 2        | 0.3%    |
| TP-Link                           | 1        | 0.15%   |
| Sundance Technology Inc / IC Plus | 1        | 0.15%   |
| Mellanox Technologies             | 1        | 0.15%   |
| Huawei Technologies               | 1        | 0.15%   |
| Google                            | 1        | 0.15%   |
| D-Link System                     | 1        | 0.15%   |
| Chelsio Communications            | 1        | 0.15%   |
| ASUSTek Computer                  | 1        | 0.15%   |
| ASIX Electronics                  | 1        | 0.15%   |
| Aquantia                          | 1        | 0.15%   |
| American Megatrends               | 1        | 0.15%   |
| 3Com                              | 1        | 0.15%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 312      | 45.09%  |
| Intel I211 Gigabit Network Connection                                          | 35       | 5.06%   |
| Realtek RTL8125 2.5GbE Controller                                              | 33       | 4.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 20       | 2.89%   |
| Intel Ethernet Connection (2) I219-V                                           | 19       | 2.75%   |
| Intel Ethernet Connection I217-LM                                              | 18       | 2.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 15       | 2.17%   |
| Intel Ethernet Controller I225-V                                               | 14       | 2.02%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 11       | 1.59%   |
| Intel Ethernet Connection (7) I219-V                                           | 11       | 1.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 10       | 1.45%   |
| Intel Ethernet Connection (2) I218-V                                           | 9        | 1.3%    |
| Intel 82566DM-2 Gigabit Network Connection                                     | 9        | 1.3%    |
| Intel 82567LM-3 Gigabit Network Connection                                     | 8        | 1.16%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 7        | 1.01%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 7        | 1.01%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 6        | 0.87%   |
| Nvidia MCP61 Ethernet                                                          | 6        | 0.87%   |
| Intel 82579V Gigabit Network Connection                                        | 6        | 0.87%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                              | 5        | 0.72%   |
| Intel 82574L Gigabit Network Connection                                        | 5        | 0.72%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 4        | 0.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4        | 0.58%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 4        | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 4        | 0.58%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 4        | 0.58%   |
| Nvidia MCP73 Ethernet                                                          | 4        | 0.58%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3        | 0.43%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 3        | 0.43%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 3        | 0.43%   |
| Intel Ethernet Connection (12) I219-V                                          | 3        | 0.43%   |
| Intel 82578DM Gigabit Network Connection                                       | 3        | 0.43%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 3        | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2        | 0.29%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2        | 0.29%   |
| Nvidia MCP51 Ethernet Controller                                               | 2        | 0.29%   |
| Nvidia CK804 Ethernet Controller                                               | 2        | 0.29%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2        | 0.29%   |
| Marvell Group 88E8075 PCI-E Gigabit Ethernet Controller                        | 2        | 0.29%   |
| Intel NM10/ICH7 Family LAN Controller                                          | 2        | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 616      | 76.14%  |
| WiFi     | 184      | 22.74%  |
| Modem    | 5        | 0.62%   |
| Unknown  | 4        | 0.49%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 534      | 84.49%  |
| WiFi     | 98       | 15.51%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 446      | 71.13%  |
| 2     | 155      | 24.72%  |
| 3     | 14       | 2.23%   |
| 0     | 6        | 0.96%   |
| 5     | 2        | 0.32%   |
| 9     | 1        | 0.16%   |
| 8     | 1        | 0.16%   |
| 6     | 1        | 0.16%   |
| 4     | 1        | 0.16%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 579      | 91.47%  |
| Yes  | 54       | 8.53%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 48       | 29.63%  |
| Cambridge Silicon Radio         | 48       | 29.63%  |
| ASUSTek Computer                | 27       | 16.67%  |
| Realtek Semiconductor           | 12       | 7.41%   |
| Broadcom                        | 8        | 4.94%   |
| IMC Networks                    | 4        | 2.47%   |
| Qualcomm Atheros Communications | 3        | 1.85%   |
| Integrated System Solution      | 3        | 1.85%   |
| MediaTek                        | 2        | 1.23%   |
| Lite-On Technology              | 2        | 1.23%   |
| TP-Link                         | 1        | 0.62%   |
| Mobile Action Technology        | 1        | 0.62%   |
| Micro Star International        | 1        | 0.62%   |
| Creative Technology             | 1        | 0.62%   |
| Belkin Components               | 1        | 0.62%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 48       | 29.63%  |
| Intel AX200 Bluetooth                                    | 17       | 10.49%  |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 11       | 6.79%   |
| Realtek Bluetooth Radio                                  | 10       | 6.17%   |
| Intel Bluetooth wireless interface                       | 10       | 6.17%   |
| ASUS ASUS USB-BT500                                      | 9        | 5.56%   |
| Intel Wireless-AC 3168 Bluetooth                         | 7        | 4.32%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 4        | 2.47%   |
| Intel AX210 Bluetooth                                    | 4        | 2.47%   |
| ASUS Bluetooth Radio                                     | 4        | 2.47%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter    | 3        | 1.85%   |
| Realtek  Bluetooth 4.2 Adapter                           | 2        | 1.23%   |
| MediaTek Wireless_Device                                 | 2        | 1.23%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 2        | 1.23%   |
| Intel AX201 Bluetooth                                    | 2        | 1.23%   |
| IMC Networks Wireless_Device                             | 2        | 1.23%   |
| IMC Networks Bluetooth Radio                             | 2        | 1.23%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 2        | 1.23%   |
| Broadcom BCM2045 Bluetooth                               | 2        | 1.23%   |
| TP-Link UB500 Adapter                                    | 1        | 0.62%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                   | 1        | 0.62%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 1        | 0.62%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 1        | 0.62%   |
| Mobile Action MA-730/MA-730G Bluetooth Adapter           | 1        | 0.62%   |
| Micro Star International MS-6970 BToes Bluetooth adapter | 1        | 0.62%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth               | 1        | 0.62%   |
| Lite-On Bluetooth Device                                 | 1        | 0.62%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 1        | 0.62%   |
| Intel Bluetooth Device                                   | 1        | 0.62%   |
| Creative Bluetooth Audio W2                              | 1        | 0.62%   |
| Broadcom Bluetooth Controller                            | 1        | 0.62%   |
| Broadcom Bluetooth 2.0+eDR dongle                        | 1        | 0.62%   |
| Broadcom BCM2070 Bluetooth 3.0 + HS                      | 1        | 0.62%   |
| Broadcom BCM2035 Bluetooth dongle                        | 1        | 0.62%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter    | 1        | 0.62%   |
| ASUS Qualcomm Bluetooth 4.1                              | 1        | 0.62%   |
| ASUS Bluetooth Adapter                                   | 1        | 0.62%   |
| ASUS 2045 Bluetooth 2.0 Device with trace filter         | 1        | 0.62%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 344      | 34.54%  |
| AMD                       | 299      | 30.02%  |
| Nvidia                    | 236      | 23.69%  |
| C-Media Electronics       | 27       | 2.71%   |
| Creative Labs             | 16       | 1.61%   |
| VIA Technologies          | 9        | 0.9%    |
| Creative Technology       | 9        | 0.9%    |
| Logitech                  | 7        | 0.7%    |
| JMTek                     | 5        | 0.5%    |
| Trust                     | 3        | 0.3%    |
| Razer USA                 | 3        | 0.3%    |
| Lenovo                    | 3        | 0.3%    |
| Kingston Technology       | 3        | 0.3%    |
| GYROCOM C&C               | 3        | 0.3%    |
| Focusrite-Novation        | 3        | 0.3%    |
| Dell                      | 3        | 0.3%    |
| ASUSTek Computer          | 3        | 0.3%    |
| Realtek Semiconductor     | 2        | 0.2%    |
| Plantronics               | 2        | 0.2%    |
| Texas Instruments         | 1        | 0.1%    |
| Tenx Technology           | 1        | 0.1%    |
| SteelSeries ApS           | 1        | 0.1%    |
| Sony                      | 1        | 0.1%    |
| Sennheiser Communications | 1        | 0.1%    |
| Samson Technologies       | 1        | 0.1%    |
| Micro Star International  | 1        | 0.1%    |
| M-Audio                   | 1        | 0.1%    |
| KORG                      | 1        | 0.1%    |
| GN Netcom                 | 1        | 0.1%    |
| fifinemicrophone.com      | 1        | 0.1%    |
| Elgato Systems            | 1        | 0.1%    |
| DigiTech                  | 1        | 0.1%    |
| BEHRINGER International   | 1        | 0.1%    |
| Audio-Technica            | 1        | 0.1%    |
| ASRock                    | 1        | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 65       | 5.49%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 62       | 5.24%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 44       | 3.72%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 40       | 3.38%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 39       | 3.3%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 39       | 3.3%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 38       | 3.21%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 35       | 2.96%   |
| AMD Family 17h/19h HD Audio Controller                                            | 31       | 2.62%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 26       | 2.2%    |
| Nvidia GP107GL High Definition Audio Controller                                   | 25       | 2.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 25       | 2.11%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 25       | 2.11%   |
| AMD FCH Azalia Controller                                                         | 25       | 2.11%   |
| Intel Cannon Lake PCH cAVS                                                        | 23       | 1.94%   |
| Nvidia GP106 High Definition Audio Controller                                     | 22       | 1.86%   |
| Intel 200 Series PCH HD Audio                                                     | 22       | 1.86%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 21       | 1.78%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 20       | 1.69%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 15       | 1.27%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 14       | 1.18%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 12       | 1.01%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 12       | 1.01%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 12       | 1.01%   |
| Nvidia MCP61 High Definition Audio                                                | 11       | 0.93%   |
| Nvidia GP108 High Definition Audio Controller                                     | 11       | 0.93%   |
| Nvidia GP104 High Definition Audio Controller                                     | 11       | 0.93%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 11       | 0.93%   |
| Nvidia GF108 High Definition Audio Controller                                     | 11       | 0.93%   |
| Nvidia TU116 High Definition Audio Controller                                     | 10       | 0.85%   |
| Nvidia TU106 High Definition Audio Controller                                     | 10       | 0.85%   |
| Nvidia GK107 HDMI Audio Controller                                                | 10       | 0.85%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 10       | 0.85%   |
| AMD Navi 10 HDMI Audio                                                            | 10       | 0.85%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 9        | 0.76%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 9        | 0.76%   |
| Nvidia TU104 HD Audio Controller                                                  | 8        | 0.68%   |
| Nvidia GM206 High Definition Audio Controller                                     | 8        | 0.68%   |
| Nvidia GF119 HDMI Audio Controller                                                | 8        | 0.68%   |
| AMD Kabini HDMI/DP Audio                                                          | 8        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 135      | 37.6%   |
| Unknown             | 70       | 19.5%   |
| Samsung Electronics | 28       | 7.8%    |
| Corsair             | 22       | 6.13%   |
| SK hynix            | 21       | 5.85%   |
| Patriot             | 17       | 4.74%   |
| Crucial             | 15       | 4.18%   |
| A-DATA Technology   | 10       | 2.79%   |
| Micron Technology   | 9        | 2.51%   |
| G.Skill             | 8        | 2.23%   |
| Ramaxel Technology  | 6        | 1.67%   |
| Nanya Technology    | 3        | 0.84%   |
| Unknown (ABCD)      | 2        | 0.56%   |
| Transcend           | 2        | 0.56%   |
| GOODRAM             | 2        | 0.56%   |
| Toshiba             | 1        | 0.28%   |
| PDPSystems          | 1        | 0.28%   |
| Patriot Memory      | 1        | 0.28%   |
| Kingmax             | 1        | 0.28%   |
| Kimtigo             | 1        | 0.28%   |
| H                   | 1        | 0.28%   |
| Elpida              | 1        | 0.28%   |
| Apacer              | 1        | 0.28%   |
| AMD                 | 1        | 0.28%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s           | 9        | 2.24%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 7        | 1.75%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s            | 7        | 1.75%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 6        | 1.5%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 5        | 1.25%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s         | 5        | 1.25%   |
| Kingston RAM KHX2400C15/8G 8192MB DIMM DDR4 3400MT/s           | 5        | 1.25%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                        | 4        | 1%      |
| Kingston RAM KHX1600C9D3/8GX 8GB DIMM DDR3 2133MT/s            | 4        | 1%      |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s            | 4        | 1%      |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s            | 4        | 1%      |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s          | 4        | 1%      |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 3        | 0.75%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 3        | 0.75%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 3        | 0.75%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 3        | 0.75%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s          | 3        | 0.75%   |
| Samsung RAM Module 8192MB DIMM DDR4 2666MT/s                   | 3        | 0.75%   |
| Patriot RAM 3600 C18 Series 32GB DIMM DDR4 3600MT/s            | 3        | 0.75%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3266MT/s            | 3        | 0.75%   |
| Kingston RAM KHX3000C15D4/8GX 8GB DIMM DDR4 3400MT/s           | 3        | 0.75%   |
| Kingston RAM KHX2666C16D4/4G 4GB DIMM DDR4 2667MT/s            | 3        | 0.75%   |
| Kingston RAM KHX2400C11D3/4GX 4GB DIMM DDR3 2400MT/s           | 3        | 0.75%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s              | 3        | 0.75%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s          | 3        | 0.75%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s          | 3        | 0.75%   |
| Corsair RAM CMK32GX4M2B3000C15 16GB DIMM DDR4 3000MT/s         | 3        | 0.75%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 3        | 0.75%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 2        | 0.5%    |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                   | 2        | 0.5%    |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                      | 2        | 0.5%    |
| Unknown RAM Module 2GB DIMM 400MT/s                            | 2        | 0.5%    |
| Unknown RAM Module 2048MB DIMM 800MT/s                         | 2        | 0.5%    |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                       | 2        | 0.5%    |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                    | 2        | 0.5%    |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                    | 2        | 0.5%    |
| Unknown RAM 3600 C20 Series 32GB DIMM DDR4 3666MT/s            | 2        | 0.5%    |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 2        | 0.5%    |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s           | 2        | 0.5%    |
| Samsung RAM Module 16GB DIMM DDR4 2666MT/s                     | 2        | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 136      | 42.63%  |
| DDR3    | 106      | 33.23%  |
| Unknown | 29       | 9.09%   |
| DDR2    | 27       | 8.46%   |
| SDRAM   | 9        | 2.82%   |
| DDR5    | 6        | 1.88%   |
| DDR     | 3        | 0.94%   |
| LPDDR4  | 2        | 0.63%   |
| DRAM    | 1        | 0.31%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 303      | 95.89%  |
| SODIMM | 11       | 3.48%   |
| RIMM   | 2        | 0.63%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 112      | 32.09%  |
| 4096  | 83       | 23.78%  |
| 2048  | 58       | 16.62%  |
| 16384 | 47       | 13.47%  |
| 32768 | 28       | 8.02%   |
| 1024  | 18       | 5.16%   |
| 512   | 2        | 0.57%   |
| 256   | 1        | 0.29%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 54       | 14.96%  |
| 1333    | 45       | 12.47%  |
| 3600    | 35       | 9.7%    |
| 800     | 28       | 7.76%   |
| 2133    | 25       | 6.93%   |
| 3200    | 20       | 5.54%   |
| 2400    | 20       | 5.54%   |
| 2667    | 14       | 3.88%   |
| 667     | 11       | 3.05%   |
| 3400    | 9        | 2.49%   |
| 3466    | 7        | 1.94%   |
| 2666    | 7        | 1.94%   |
| Unknown | 7        | 1.94%   |
| 3000    | 6        | 1.66%   |
| 1866    | 6        | 1.66%   |
| 1867    | 5        | 1.39%   |
| 3933    | 4        | 1.11%   |
| 3800    | 4        | 1.11%   |
| 3266    | 4        | 1.11%   |
| 2933    | 4        | 1.11%   |
| 1067    | 4        | 1.11%   |
| 400     | 4        | 1.11%   |
| 4800    | 3        | 0.83%   |
| 3333    | 3        | 0.83%   |
| 1800    | 3        | 0.83%   |
| 1334    | 3        | 0.83%   |
| 1066    | 3        | 0.83%   |
| 4133    | 2        | 0.55%   |
| 3733    | 2        | 0.55%   |
| 3666    | 2        | 0.55%   |
| 3533    | 2        | 0.55%   |
| 3334    | 2        | 0.55%   |
| 2800    | 2        | 0.55%   |
| 6400    | 1        | 0.28%   |
| 5600    | 1        | 0.28%   |
| 5200    | 1        | 0.28%   |
| 3866    | 1        | 0.28%   |
| 3534    | 1        | 0.28%   |
| 3151    | 1        | 0.28%   |
| 2200    | 1        | 0.28%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 8        | 26.67%  |
| Canon               | 7        | 23.33%  |
| Samsung Electronics | 5        | 16.67%  |
| Brother Industries  | 5        | 16.67%  |
| QinHeng Electronics | 3        | 10%     |
| Seiko Epson         | 1        | 3.33%   |
| Pantum              | 1        | 3.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| QinHeng CH340S                          | 3        | 9.68%   |
| HP DeskJet 2600 series                  | 3        | 9.68%   |
| HP LaserJet P2014                       | 2        | 6.45%   |
| Seiko Epson L365 Series                 | 1        | 3.23%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1        | 3.23%   |
| Samsung M267x 287x Series               | 1        | 3.23%   |
| Samsung M2070 Series                    | 1        | 3.23%   |
| Samsung M2020 Series                    | 1        | 3.23%   |
| Samsung C460 Series                     | 1        | 3.23%   |
| Pantum P2000                            | 1        | 3.23%   |
| HP Neverstop Laser 100x                 | 1        | 3.23%   |
| HP LaserJet 1018                        | 1        | 3.23%   |
| HP Deskjet 3050 J610 series             | 1        | 3.23%   |
| Canon TS6300 series                     | 1        | 3.23%   |
| Canon PIXMA MX920 Series                | 1        | 3.23%   |
| Canon PIXMA MX720 Series                | 1        | 3.23%   |
| Canon PIXMA MP280                       | 1        | 3.23%   |
| Canon PIXMA MG3500 Series               | 1        | 3.23%   |
| Canon PIXMA MG2500 Series               | 1        | 3.23%   |
| Canon MG5600 series                     | 1        | 3.23%   |
| Canon iP7200 series                     | 1        | 3.23%   |
| Brother MFC-J3930DW                     | 1        | 3.23%   |
| Brother HL-2030 Laser Printer           | 1        | 3.23%   |
| Brother HL-1430 Laser Printer           | 1        | 3.23%   |
| Brother DCP-J105                        | 1        | 3.23%   |
| Brother DCP-1610W                       | 1        | 3.23%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| Canon          | 5        | 83.33%  |
| Mustek Systems | 1        | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Canon CanoScan LiDE 210             | 2        | 33.33%  |
| Mustek Systems BearPaw 1200 CU Plus | 1        | 16.67%  |
| Canon CanoScan LIDE 25              | 1        | 16.67%  |
| Canon CanoScan LiDE 120             | 1        | 16.67%  |
| Canon CanoScan LiDE 100             | 1        | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 20       | 23.53%  |
| KYE Systems (Mouse Systems)   | 9        | 10.59%  |
| Microdia                      | 8        | 9.41%   |
| Creative Technology           | 7        | 8.24%   |
| Samsung Electronics           | 6        | 7.06%   |
| Microsoft                     | 6        | 7.06%   |
| Z-Star Microelectronics       | 4        | 4.71%   |
| Apple                         | 4        | 4.71%   |
| Hopewin Electronic Material   | 3        | 3.53%   |
| GEMBIRD                       | 3        | 3.53%   |
| Sunplus Innovation Technology | 2        | 2.35%   |
| Hewlett-Packard               | 2        | 2.35%   |
| Generalplus Technology        | 2        | 2.35%   |
| webcam                        | 1        | 1.18%   |
| WaveRider Communications      | 1        | 1.18%   |
| SunplusIT                     | 1        | 1.18%   |
| Smartronix                    | 1        | 1.18%   |
| Nokia Mobile Phones           | 1        | 1.18%   |
| MacroSilicon                  | 1        | 1.18%   |
| Lenovo                        | 1        | 1.18%   |
| HD WEBCAM                     | 1        | 1.18%   |
| Cubeternet                    | 1        | 1.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Samsung Galaxy series, misc. (MTP mode)           | 6        | 6.98%   |
| Logitech Webcam C270                              | 6        | 6.98%   |
| Creative Live! Cam Sync HD [VF0770]               | 5        | 5.81%   |
| Microsoft LifeCam HD-3000                         | 4        | 4.65%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                   | 4        | 4.65%   |
| Logitech Webcam C170                              | 3        | 3.49%   |
| Logitech HD Pro Webcam C920                       | 3        | 3.49%   |
| KYE Systems (Mouse Systems) FaceCam 1000X         | 3        | 3.49%   |
| Hopewin Electronic Material FULL HD 1080P Webcam  | 3        | 3.49%   |
| Z-Star Venus USB2.0 Camera                        | 2        | 2.33%   |
| Microdia Webcam Vitade AF                         | 2        | 2.33%   |
| Microdia USB 2.0 Camera                           | 2        | 2.33%   |
| Logitech Webcam C925e                             | 2        | 2.33%   |
| Logitech HD Webcam C910                           | 2        | 2.33%   |
| KYE Systems (Mouse Systems) Genius FaceCam 320    | 2        | 2.33%   |
| Generalplus 808 Camera #9 (web-cam mode)          | 2        | 2.33%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 2        | 2.33%   |
| Creative Live! Cam Chat HD [VF0700/VF0790]        | 2        | 2.33%   |
| Z-Star Vega USB 2.0 Camera                        | 1        | 1.16%   |
| Z-Star A4 TECH USB2.0 PC Camera J                 | 1        | 1.16%   |
| webcam webcam                                     | 1        | 1.16%   |
| WaveRider USB 2.0 Camera                          | 1        | 1.16%   |
| SunplusIT Umax Webcam W5                          | 1        | 1.16%   |
| Sunplus HD 720P webcam                            | 1        | 1.16%   |
| Sunplus Full HD webcam                            | 1        | 1.16%   |
| Smartronix webcam                                 | 1        | 1.16%   |
| Nokia Mobile Phones Lumia 620/920                 | 1        | 1.16%   |
| Microsoft LifeCam VX-800                          | 1        | 1.16%   |
| Microsoft LifeCam NX-6000                         | 1        | 1.16%   |
| Microdia Sonix USB 2.0 Camera                     | 1        | 1.16%   |
| Microdia HoverCam Solo Spark Audio                | 1        | 1.16%   |
| Microdia CameraA                                  | 1        | 1.16%   |
| Microdia Camera                                   | 1        | 1.16%   |
| MacroSilicon usb video                            | 1        | 1.16%   |
| Logitech Webcam C200                              | 1        | 1.16%   |
| Logitech C922 Pro Stream Webcam                   | 1        | 1.16%   |
| Logitech BRIO 4K Stream Edition                   | 1        | 1.16%   |
| Logitech B525 HD Webcam                           | 1        | 1.16%   |
| Lenovo FHD Webcam                                 | 1        | 1.16%   |
| KYE Systems (Mouse Systems) PC-W3 Camera          | 1        | 1.16%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Dell   | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Dell MS819 Wired Mouse With Fingerprint Reader | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Alcor Micro               | 3        | 42.86%  |
| Realtek Semiconductor     | 1        | 14.29%  |
| OmniKey                   | 1        | 14.29%  |
| Fujitsu Siemens Computers | 1        | 14.29%  |
| Aladdin Knowledge Systems | 1        | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader               | 3        | 42.86%  |
| Realtek Semiconductor Smart Card Reader Interface | 1        | 14.29%  |
| OmniKey 3x21 Smart Card Reader                    | 1        | 14.29%  |
| Fujitsu Siemens Computers SmartCard Reader 2A     | 1        | 14.29%  |
| Aladdin Knowledge Systems Token JC                | 1        | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 551      | 87.46%  |
| 1     | 68       | 10.79%  |
| 2     | 7        | 1.11%   |
| 4     | 2        | 0.32%   |
| 3     | 2        | 0.32%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 39       | 44.83%  |
| Net/wireless             | 13       | 14.94%  |
| Multimedia controller    | 8        | 9.2%    |
| Unassigned class         | 5        | 5.75%   |
| Chipcard                 | 5        | 5.75%   |
| Communication controller | 4        | 4.6%    |
| Sound                    | 3        | 3.45%   |
| Network                  | 3        | 3.45%   |
| Net/ethernet             | 2        | 2.3%    |
| Bluetooth                | 2        | 2.3%    |
| Storage/ide              | 1        | 1.15%   |
| Modem                    | 1        | 1.15%   |
| Camera                   | 1        | 1.15%   |

