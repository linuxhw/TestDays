Ubuntu 22.04 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 22.04.

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

Total: 5099

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | M4A78LT-M-LE                | [9564e74fb6](https://linux-hardware.org/?probe=9564e74fb6) | Jul 01, 2023 |
| ASRock        | H510M-HDV/M.2               | [ec9ab3662c](https://linux-hardware.org/?probe=ec9ab3662c) | Jul 01, 2023 |
| ZR            | A320M-F 1005                | [c32d8de777](https://linux-hardware.org/?probe=c32d8de777) | Jun 30, 2023 |
| Supermicro    | X10DDW-i                    | [c43e65f1ae](https://linux-hardware.org/?probe=c43e65f1ae) | Jun 30, 2023 |
| Intel         | B85 V5.56                   | [a582972a5e](https://linux-hardware.org/?probe=a582972a5e) | Jun 30, 2023 |
| Gigabyte      | B760M DS3H AX DDR4          | [0d3ecc7c44](https://linux-hardware.org/?probe=0d3ecc7c44) | Jun 30, 2023 |
| Pegatron      | 2AB5                        | [f23fa01e43](https://linux-hardware.org/?probe=f23fa01e43) | Jun 30, 2023 |
| AZW           | SEi                         | [37527da518](https://linux-hardware.org/?probe=37527da518) | Jun 30, 2023 |
| Intel         | X99H                        | [8e8c7e8b20](https://linux-hardware.org/?probe=8e8c7e8b20) | Jun 30, 2023 |
| Supermicro    | X9DRW                       | [cb955d7a58](https://linux-hardware.org/?probe=cb955d7a58) | Jun 30, 2023 |
| HP            | 1497                        | [4dd582d288](https://linux-hardware.org/?probe=4dd582d288) | Jun 30, 2023 |
| Dell          | 0KYJ8C A02                  | [f4fff60df3](https://linux-hardware.org/?probe=f4fff60df3) | Jun 30, 2023 |
| ASUSTek       | M51AC                       | [d32d060e9c](https://linux-hardware.org/?probe=d32d060e9c) | Jun 30, 2023 |
| Dell          | 0KYJ8C A02                  | [c860545122](https://linux-hardware.org/?probe=c860545122) | Jun 30, 2023 |
| Medion        | Z370H4-EM                   | [b8327a4d00](https://linux-hardware.org/?probe=b8327a4d00) | Jun 30, 2023 |
| Intel         | B85 V5.56                   | [e8b15eb823](https://linux-hardware.org/?probe=e8b15eb823) | Jun 29, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | [5a6b149eb4](https://linux-hardware.org/?probe=5a6b149eb4) | Jun 29, 2023 |
| Dell          | 0T568R A00                  | [cf98a8a69b](https://linux-hardware.org/?probe=cf98a8a69b) | Jun 29, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d6cb722f64](https://linux-hardware.org/?probe=d6cb722f64) | Jun 29, 2023 |
| ASRock        | Z690 Steel Legend WiFi 6... | [d09ee66df1](https://linux-hardware.org/?probe=d09ee66df1) | Jun 29, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [304ff06fc0](https://linux-hardware.org/?probe=304ff06fc0) | Jun 29, 2023 |
| MSI           | Z87 MPOWER                  | [e34420b76e](https://linux-hardware.org/?probe=e34420b76e) | Jun 29, 2023 |
| ASUSTek       | F2A85-M PRO                 | [a7617c12c5](https://linux-hardware.org/?probe=a7617c12c5) | Jun 28, 2023 |
| ZR            | A320M-F 1005                | [f70bb41b80](https://linux-hardware.org/?probe=f70bb41b80) | Jun 28, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [e29021ab76](https://linux-hardware.org/?probe=e29021ab76) | Jun 28, 2023 |
| ASRock        | X570 Taichi                 | [75cb221d91](https://linux-hardware.org/?probe=75cb221d91) | Jun 28, 2023 |
| ASUSTek       | PRIME B350M-A               | [1f5a11092b](https://linux-hardware.org/?probe=1f5a11092b) | Jun 28, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [607da926f3](https://linux-hardware.org/?probe=607da926f3) | Jun 28, 2023 |
| ASUSTek       | F2A55-M LK                  | [0fcac8a0af](https://linux-hardware.org/?probe=0fcac8a0af) | Jun 28, 2023 |
| MSI           | Z390-A PRO                  | [638d6b4ef3](https://linux-hardware.org/?probe=638d6b4ef3) | Jun 27, 2023 |
| ASRock        | AB350M-HDV                  | [a055db3af3](https://linux-hardware.org/?probe=a055db3af3) | Jun 27, 2023 |
| Dell          | 0KWVT8 A03                  | [8dcd3c3200](https://linux-hardware.org/?probe=8dcd3c3200) | Jun 27, 2023 |
| Gigabyte      | H310M M.2 x.x               | [6f9c836bb4](https://linux-hardware.org/?probe=6f9c836bb4) | Jun 27, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [708131b231](https://linux-hardware.org/?probe=708131b231) | Jun 27, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [ef8f76e9e1](https://linux-hardware.org/?probe=ef8f76e9e1) | Jun 27, 2023 |
| Dell          | 0FXD80 A00                  | [4427c2159c](https://linux-hardware.org/?probe=4427c2159c) | Jun 27, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | [9450fc030e](https://linux-hardware.org/?probe=9450fc030e) | Jun 27, 2023 |
| Dell          | 00010C A00                  | [f965b0f028](https://linux-hardware.org/?probe=f965b0f028) | Jun 27, 2023 |
| HP            | 0A9Ch                       | [08eccac462](https://linux-hardware.org/?probe=08eccac462) | Jun 27, 2023 |
| ASRock        | 960GM-VGS3 FX               | [2cd4ef0e5d](https://linux-hardware.org/?probe=2cd4ef0e5d) | Jun 27, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [962cd7b905](https://linux-hardware.org/?probe=962cd7b905) | Jun 27, 2023 |
| Gigabyte      | AB350M-D3H-CF               | [c73458700f](https://linux-hardware.org/?probe=c73458700f) | Jun 27, 2023 |
| ASUSTek       | ROG ZENITH II EXTREME       | [51f9f56f44](https://linux-hardware.org/?probe=51f9f56f44) | Jun 26, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [91b5e02477](https://linux-hardware.org/?probe=91b5e02477) | Jun 26, 2023 |
| Biostar       | B550T-SILVER                | [bae0c9a5b0](https://linux-hardware.org/?probe=bae0c9a5b0) | Jun 26, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [309cb87000](https://linux-hardware.org/?probe=309cb87000) | Jun 26, 2023 |
| Intel         | DH55TC AAE70932-206         | [9ff872e2a3](https://linux-hardware.org/?probe=9ff872e2a3) | Jun 26, 2023 |
| HP            | 21F5 0A                     | [dd990a6e99](https://linux-hardware.org/?probe=dd990a6e99) | Jun 26, 2023 |
| ASUSTek       | B85M-G                      | [5a9f85740e](https://linux-hardware.org/?probe=5a9f85740e) | Jun 26, 2023 |
| Unknown       | Unknown                     | [7c0c11558d](https://linux-hardware.org/?probe=7c0c11558d) | Jun 26, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [baeab145a2](https://linux-hardware.org/?probe=baeab145a2) | Jun 26, 2023 |
| Lenovo        | 3102 NOK                    | [6277771b08](https://linux-hardware.org/?probe=6277771b08) | Jun 26, 2023 |
| Lenovo        | ThinkCentre M91p 7033A1G    | [a3ca410b6a](https://linux-hardware.org/?probe=a3ca410b6a) | Jun 26, 2023 |
| ASRock        | H61M-VG4                    | [7fbf9c4e53](https://linux-hardware.org/?probe=7fbf9c4e53) | Jun 25, 2023 |
| Intel         | B75                         | [2456289bbd](https://linux-hardware.org/?probe=2456289bbd) | Jun 25, 2023 |
| ASUSTek       | PRIME B650-PLUS             | [9f89885724](https://linux-hardware.org/?probe=9f89885724) | Jun 25, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [9aa214f70a](https://linux-hardware.org/?probe=9aa214f70a) | Jun 25, 2023 |
| Foxconn       | 945 7MC Series              | [dc2911bfae](https://linux-hardware.org/?probe=dc2911bfae) | Jun 25, 2023 |
| Foxconn       | 945 7MC Series              | [273bec93a4](https://linux-hardware.org/?probe=273bec93a4) | Jun 25, 2023 |
| Gigabyte      | Z77MX-D3H                   | [ac084eba06](https://linux-hardware.org/?probe=ac084eba06) | Jun 24, 2023 |
| Intel         | DH55HC AAE70933-503         | [8dab0b7f0d](https://linux-hardware.org/?probe=8dab0b7f0d) | Jun 24, 2023 |
| ASUSTek       | P5K                         | [c33ff02489](https://linux-hardware.org/?probe=c33ff02489) | Jun 24, 2023 |
| ASUSTek       | P5K                         | [c87e87b883](https://linux-hardware.org/?probe=c87e87b883) | Jun 24, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [a19fc9dde8](https://linux-hardware.org/?probe=a19fc9dde8) | Jun 24, 2023 |
| HP            | 0A9Ch                       | [4bd59bd633](https://linux-hardware.org/?probe=4bd59bd633) | Jun 24, 2023 |
| Seeed Stud... | ODYSSEY-X86J41X5 CJ41GV2... | [79a2c321e8](https://linux-hardware.org/?probe=79a2c321e8) | Jun 24, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | [0f64e88f33](https://linux-hardware.org/?probe=0f64e88f33) | Jun 23, 2023 |
| HP            | 304Bh                       | [234bedfab1](https://linux-hardware.org/?probe=234bedfab1) | Jun 23, 2023 |
| ASUSTek       | Q87M-E                      | [f0ab10725e](https://linux-hardware.org/?probe=f0ab10725e) | Jun 23, 2023 |
| Dell          | 0CRH6C A02                  | [7ce8bcbc26](https://linux-hardware.org/?probe=7ce8bcbc26) | Jun 23, 2023 |
| ASRock        | B365M Pro4-F                | [16a5102512](https://linux-hardware.org/?probe=16a5102512) | Jun 23, 2023 |
| HP            | 3047h                       | [e60df0b6d1](https://linux-hardware.org/?probe=e60df0b6d1) | Jun 23, 2023 |
| ASUSTek       | PRIME B550M-A               | [3789bc7deb](https://linux-hardware.org/?probe=3789bc7deb) | Jun 23, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [c202144225](https://linux-hardware.org/?probe=c202144225) | Jun 23, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [83eb8cda4a](https://linux-hardware.org/?probe=83eb8cda4a) | Jun 23, 2023 |
| HP            | 0A9Ch                       | [2f48843246](https://linux-hardware.org/?probe=2f48843246) | Jun 23, 2023 |
| Foxconn       | ALOE X3                     | [ec9afb2155](https://linux-hardware.org/?probe=ec9afb2155) | Jun 23, 2023 |
| MSI           | 760GM-E51                   | [078c1805bd](https://linux-hardware.org/?probe=078c1805bd) | Jun 22, 2023 |
| Supermicro    | X9DRW                       | [3b2f007f67](https://linux-hardware.org/?probe=3b2f007f67) | Jun 22, 2023 |
| Unknown       | Unknown                     | [3e25fc74a7](https://linux-hardware.org/?probe=3e25fc74a7) | Jun 22, 2023 |
| Unknown       | Unknown                     | [c2e0154437](https://linux-hardware.org/?probe=c2e0154437) | Jun 22, 2023 |
| ASRock        | X399 Taichi                 | [d9ca7c4369](https://linux-hardware.org/?probe=d9ca7c4369) | Jun 22, 2023 |
| ASRock        | H61M-VG3                    | [955228e9e5](https://linux-hardware.org/?probe=955228e9e5) | Jun 22, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [d3a63bb6aa](https://linux-hardware.org/?probe=d3a63bb6aa) | Jun 22, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [6c43b99ec8](https://linux-hardware.org/?probe=6c43b99ec8) | Jun 22, 2023 |
| ASRock        | B365 Pro4                   | [46dc8e10a8](https://linux-hardware.org/?probe=46dc8e10a8) | Jun 21, 2023 |
| Dell          | 0NKW6Y A01                  | [def5a35ba4](https://linux-hardware.org/?probe=def5a35ba4) | Jun 21, 2023 |
| Biostar       | H61MGV3                     | [109f8064f6](https://linux-hardware.org/?probe=109f8064f6) | Jun 21, 2023 |
| Dell          | 00V62H A01                  | [2e654ead73](https://linux-hardware.org/?probe=2e654ead73) | Jun 21, 2023 |
| Dell          | 00V62H A01                  | [2ebfd9c347](https://linux-hardware.org/?probe=2ebfd9c347) | Jun 21, 2023 |
| MSI           | B450-A PRO MAX              | [589e702758](https://linux-hardware.org/?probe=589e702758) | Jun 21, 2023 |
| ASUSTek       | PRIME Z270-K                | [c3961b2aa5](https://linux-hardware.org/?probe=c3961b2aa5) | Jun 21, 2023 |
| Lenovo        | 30C0 SDK0J40697 WIN 3305... | [8c4bd347a7](https://linux-hardware.org/?probe=8c4bd347a7) | Jun 21, 2023 |
| Gigabyte      | Z97M-D3H                    | [66e2a42098](https://linux-hardware.org/?probe=66e2a42098) | Jun 21, 2023 |
| Dell          | 09KPNV A01                  | [ff224b2f9d](https://linux-hardware.org/?probe=ff224b2f9d) | Jun 21, 2023 |
| Dell          | 09KPNV A01                  | [acbd33c5c8](https://linux-hardware.org/?probe=acbd33c5c8) | Jun 21, 2023 |
| Shenzhen M... | F7BFC                       | [f76394a58a](https://linux-hardware.org/?probe=f76394a58a) | Jun 21, 2023 |
| HP            | 339A                        | [960fd64baa](https://linux-hardware.org/?probe=960fd64baa) | Jun 21, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [9bcbbbd906](https://linux-hardware.org/?probe=9bcbbbd906) | Jun 21, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | [63f5506bc3](https://linux-hardware.org/?probe=63f5506bc3) | Jun 21, 2023 |
| HP            | 339A                        | [60b0bff872](https://linux-hardware.org/?probe=60b0bff872) | Jun 21, 2023 |
| Dell          | 0GM819                      | [5823b51b38](https://linux-hardware.org/?probe=5823b51b38) | Jun 20, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [6f0b6969bf](https://linux-hardware.org/?probe=6f0b6969bf) | Jun 20, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [92f6324f8a](https://linux-hardware.org/?probe=92f6324f8a) | Jun 20, 2023 |
| ASUSTek       | PRIME X470-PRO              | [f1acdd3081](https://linux-hardware.org/?probe=f1acdd3081) | Jun 20, 2023 |
| MSI           | A68HM-E33 V2                | [8260bcf9b3](https://linux-hardware.org/?probe=8260bcf9b3) | Jun 20, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [bbfb6ff07f](https://linux-hardware.org/?probe=bbfb6ff07f) | Jun 20, 2023 |
| HP            | 18E4                        | [9e2ad40fc3](https://linux-hardware.org/?probe=9e2ad40fc3) | Jun 20, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [19c5a44099](https://linux-hardware.org/?probe=19c5a44099) | Jun 20, 2023 |
| ASRock        | X370 Killer SLI             | [10939cb152](https://linux-hardware.org/?probe=10939cb152) | Jun 20, 2023 |
| ASRock        | H270 Pro4                   | [e3b13a5c7f](https://linux-hardware.org/?probe=e3b13a5c7f) | Jun 20, 2023 |
| AMI           | Intel                       | [94c1b63cc6](https://linux-hardware.org/?probe=94c1b63cc6) | Jun 20, 2023 |
| Acer          | Veriton X490G               | [a181339180](https://linux-hardware.org/?probe=a181339180) | Jun 20, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [d9d8f74eca](https://linux-hardware.org/?probe=d9d8f74eca) | Jun 19, 2023 |
| Lenovo        | ThinkServer TS140           | [9210e713ff](https://linux-hardware.org/?probe=9210e713ff) | Jun 19, 2023 |
| Gigabyte      | B150M-D3H DDR3-CF           | [3e5a0aac78](https://linux-hardware.org/?probe=3e5a0aac78) | Jun 19, 2023 |
| Dell          | 0CRH6C A02                  | [6ae5e917b4](https://linux-hardware.org/?probe=6ae5e917b4) | Jun 19, 2023 |
| Dell          | 0DF42J A00                  | [c1db29329c](https://linux-hardware.org/?probe=c1db29329c) | Jun 19, 2023 |
| Shuttle       | SA76 V10                    | [fbcf156e7e](https://linux-hardware.org/?probe=fbcf156e7e) | Jun 19, 2023 |
| Gigabyte      | Z77MX-D3H                   | [c1aac2f0a4](https://linux-hardware.org/?probe=c1aac2f0a4) | Jun 19, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [257c60290f](https://linux-hardware.org/?probe=257c60290f) | Jun 19, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [8a9a60ca4d](https://linux-hardware.org/?probe=8a9a60ca4d) | Jun 19, 2023 |
| Alienware     | 0CPDXD A00                  | [3e1923b97a](https://linux-hardware.org/?probe=3e1923b97a) | Jun 19, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [eaca61c801](https://linux-hardware.org/?probe=eaca61c801) | Jun 19, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [fcec0ed2a4](https://linux-hardware.org/?probe=fcec0ed2a4) | Jun 19, 2023 |
| ASUSTek       | H110M-A                     | [22fc172f71](https://linux-hardware.org/?probe=22fc172f71) | Jun 18, 2023 |
| Dell          | 0CRH6C A02                  | [3dc796f9d3](https://linux-hardware.org/?probe=3dc796f9d3) | Jun 18, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [68e00c1869](https://linux-hardware.org/?probe=68e00c1869) | Jun 18, 2023 |
| ZR            | A320M-F 1005                | [e3c749da2a](https://linux-hardware.org/?probe=e3c749da2a) | Jun 18, 2023 |
| ASUSTek       | PRIME H510M-K               | [6ce49c3f6f](https://linux-hardware.org/?probe=6ce49c3f6f) | Jun 18, 2023 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | [02de076b1c](https://linux-hardware.org/?probe=02de076b1c) | Jun 18, 2023 |
| Lenovo        | 0x36A017AA SDK0J40709 WI... | [c409de5ebd](https://linux-hardware.org/?probe=c409de5ebd) | Jun 18, 2023 |
| Dell          | 06NWYK A00                  | [5e065b17cf](https://linux-hardware.org/?probe=5e065b17cf) | Jun 18, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [176bffae78](https://linux-hardware.org/?probe=176bffae78) | Jun 18, 2023 |
| ASUSTek       | F2A55-M LK                  | [961b50409f](https://linux-hardware.org/?probe=961b50409f) | Jun 18, 2023 |
| Gigabyte      | A320M-S2H-CF                | [7cefb01373](https://linux-hardware.org/?probe=7cefb01373) | Jun 18, 2023 |
| PCWare        | IPX1800E1                   | [59b9fa6ff9](https://linux-hardware.org/?probe=59b9fa6ff9) | Jun 17, 2023 |
| Gigabyte      | B450M DS3H V2               | [434d06d1ea](https://linux-hardware.org/?probe=434d06d1ea) | Jun 17, 2023 |
| AZW           | GTi                         | [0aaf2297b4](https://linux-hardware.org/?probe=0aaf2297b4) | Jun 17, 2023 |
| MSI           | B660M BOMBER DDR4           | [bebc7de8d4](https://linux-hardware.org/?probe=bebc7de8d4) | Jun 17, 2023 |
| ASUSTek       | A55BM-E                     | [98b3d14b06](https://linux-hardware.org/?probe=98b3d14b06) | Jun 17, 2023 |
| MSI           | B660M BOMBER DDR4           | [0a02c36bd6](https://linux-hardware.org/?probe=0a02c36bd6) | Jun 17, 2023 |
| Medion        | H110H4-EM                   | [d1cae28722](https://linux-hardware.org/?probe=d1cae28722) | Jun 17, 2023 |
| ZR            | A320M-F 1005                | [c190f4fcff](https://linux-hardware.org/?probe=c190f4fcff) | Jun 17, 2023 |
| HP            | 3397                        | [b9fa9f9e43](https://linux-hardware.org/?probe=b9fa9f9e43) | Jun 17, 2023 |
| Dell          | 0PU052                      | [93bd9e7b0b](https://linux-hardware.org/?probe=93bd9e7b0b) | Jun 17, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [a585caa218](https://linux-hardware.org/?probe=a585caa218) | Jun 17, 2023 |
| MSI           | Boston                      | [8bc41737a5](https://linux-hardware.org/?probe=8bc41737a5) | Jun 17, 2023 |
| Dell          | 0PU052                      | [36b0b1204f](https://linux-hardware.org/?probe=36b0b1204f) | Jun 17, 2023 |
| MSI           | B360M PRO-VH                | [e628906fc2](https://linux-hardware.org/?probe=e628906fc2) | Jun 16, 2023 |
| Dell          | 0PU052                      | [d5d7c6ec90](https://linux-hardware.org/?probe=d5d7c6ec90) | Jun 16, 2023 |
| MSI           | X58 Pro-E                   | [abd2765191](https://linux-hardware.org/?probe=abd2765191) | Jun 16, 2023 |
| Gigabyte      | Z490I AORUS ULTRA           | [c5cea5f197](https://linux-hardware.org/?probe=c5cea5f197) | Jun 16, 2023 |
| Gigabyte      | Z97M-DS3H                   | [dc48180bc7](https://linux-hardware.org/?probe=dc48180bc7) | Jun 16, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | [2543c7b4c9](https://linux-hardware.org/?probe=2543c7b4c9) | Jun 16, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | [c47a9a7bb8](https://linux-hardware.org/?probe=c47a9a7bb8) | Jun 16, 2023 |
| Gigabyte      | B760M DS3H DDR4             | [6a93f8d5d8](https://linux-hardware.org/?probe=6a93f8d5d8) | Jun 16, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [5844f8b39b](https://linux-hardware.org/?probe=5844f8b39b) | Jun 16, 2023 |
| OEM           | ALDER LAKE JHS64S           | [0eb1dc0b8e](https://linux-hardware.org/?probe=0eb1dc0b8e) | Jun 16, 2023 |
| Biostar       | A880GZ                      | [0ab2ec8924](https://linux-hardware.org/?probe=0ab2ec8924) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [2a3068b835](https://linux-hardware.org/?probe=2a3068b835) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [96be22e98f](https://linux-hardware.org/?probe=96be22e98f) | Jun 15, 2023 |
| Unknown       | Unknown                     | [f94cf27a96](https://linux-hardware.org/?probe=f94cf27a96) | Jun 15, 2023 |
| Gateway       | SX2110GA                    | [e47130d966](https://linux-hardware.org/?probe=e47130d966) | Jun 15, 2023 |
| ASUSTek       | F2A55-M LK                  | [68965d8ed9](https://linux-hardware.org/?probe=68965d8ed9) | Jun 15, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS        | [05923edc6b](https://linux-hardware.org/?probe=05923edc6b) | Jun 15, 2023 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | [95a5739eda](https://linux-hardware.org/?probe=95a5739eda) | Jun 14, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | [7ee7ee0f67](https://linux-hardware.org/?probe=7ee7ee0f67) | Jun 14, 2023 |
| Unknown       | Unknown                     | [e6ac28ac73](https://linux-hardware.org/?probe=e6ac28ac73) | Jun 14, 2023 |
| Unknown       | Unknown                     | [ca27fe4c19](https://linux-hardware.org/?probe=ca27fe4c19) | Jun 14, 2023 |
| ASUSTek       | M5A99X EVO                  | [5732495ae1](https://linux-hardware.org/?probe=5732495ae1) | Jun 14, 2023 |
| Unknown       | Unknown                     | [613aa12940](https://linux-hardware.org/?probe=613aa12940) | Jun 14, 2023 |
| Shenzhen M... | F7BFC                       | [7ae905703c](https://linux-hardware.org/?probe=7ae905703c) | Jun 14, 2023 |
| ASUSTek       | P8B75-M LE                  | [2bc004d4b4](https://linux-hardware.org/?probe=2bc004d4b4) | Jun 14, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [c536181b6a](https://linux-hardware.org/?probe=c536181b6a) | Jun 14, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [993f00eca6](https://linux-hardware.org/?probe=993f00eca6) | Jun 14, 2023 |
| Dell          | 0WMJ54 A01                  | [3bf8d20351](https://linux-hardware.org/?probe=3bf8d20351) | Jun 14, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [bc10401eda](https://linux-hardware.org/?probe=bc10401eda) | Jun 14, 2023 |
| ASUSTek       | P9X79 PRO                   | [4bab6db53f](https://linux-hardware.org/?probe=4bab6db53f) | Jun 14, 2023 |
| Lenovo        | MAHOBAY NOK                 | [39e2711f1f](https://linux-hardware.org/?probe=39e2711f1f) | Jun 13, 2023 |
| Chuwi         | RZBOX                       | [11bb40ef32](https://linux-hardware.org/?probe=11bb40ef32) | Jun 13, 2023 |
| Foxconn       | 2ABF                        | [61a0229bdd](https://linux-hardware.org/?probe=61a0229bdd) | Jun 13, 2023 |
| Gigabyte      | B450 AORUS M                | [aaef0bda82](https://linux-hardware.org/?probe=aaef0bda82) | Jun 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [0f19266aaf](https://linux-hardware.org/?probe=0f19266aaf) | Jun 13, 2023 |
| HP            | 18E7                        | [1be1b42bb4](https://linux-hardware.org/?probe=1be1b42bb4) | Jun 13, 2023 |
| HP            | 18E7                        | [cbf4019da2](https://linux-hardware.org/?probe=cbf4019da2) | Jun 13, 2023 |
| ASRock        | X570 Phantom Gaming-ITX/... | [7689518326](https://linux-hardware.org/?probe=7689518326) | Jun 13, 2023 |
| ASUSTek       | P9X79 PRO                   | [9e6d8db2d3](https://linux-hardware.org/?probe=9e6d8db2d3) | Jun 13, 2023 |
| ASUSTek       | P7P55D LE                   | [285303d1a0](https://linux-hardware.org/?probe=285303d1a0) | Jun 13, 2023 |
| Seco          | C40 C                       | [37b8e950d0](https://linux-hardware.org/?probe=37b8e950d0) | Jun 12, 2023 |
| ASRockRack    | B565D4-V1L                  | [34df85cbb3](https://linux-hardware.org/?probe=34df85cbb3) | Jun 12, 2023 |
| MSI           | X470 GAMING PRO             | [5f60b4bbac](https://linux-hardware.org/?probe=5f60b4bbac) | Jun 12, 2023 |
| ASRock        | X570 Phantom Gaming-ITX/... | [e68b78c037](https://linux-hardware.org/?probe=e68b78c037) | Jun 12, 2023 |
| MSI           | 760GM-P23                   | [9abb16943e](https://linux-hardware.org/?probe=9abb16943e) | Jun 12, 2023 |
| Gigabyte      | GA-A75M-D2H                 | [b870560cb8](https://linux-hardware.org/?probe=b870560cb8) | Jun 12, 2023 |
| Dell          | 0YF8P5 A00                  | [5ac4a46c16](https://linux-hardware.org/?probe=5ac4a46c16) | Jun 12, 2023 |
| Dell          | 0XCR8D A02                  | [d567ae409c](https://linux-hardware.org/?probe=d567ae409c) | Jun 12, 2023 |
| Dell          | 0M5DCD A00                  | [ae7b392070](https://linux-hardware.org/?probe=ae7b392070) | Jun 12, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [1364983b69](https://linux-hardware.org/?probe=1364983b69) | Jun 12, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [7480d3ed9c](https://linux-hardware.org/?probe=7480d3ed9c) | Jun 11, 2023 |
| Gigabyte      | P55-USB3                    | [33915148d2](https://linux-hardware.org/?probe=33915148d2) | Jun 11, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [8363538b57](https://linux-hardware.org/?probe=8363538b57) | Jun 11, 2023 |
| ASUSTek       | H110M-PLUS                  | [c544318b46](https://linux-hardware.org/?probe=c544318b46) | Jun 11, 2023 |
| Dell          | 0FDY5C A00                  | [21ad2d85dc](https://linux-hardware.org/?probe=21ad2d85dc) | Jun 11, 2023 |
| HP            | 3398                        | [7523eb041f](https://linux-hardware.org/?probe=7523eb041f) | Jun 11, 2023 |
| ASUSTek       | V-P5G43 R1.04G              | [e2400bfebe](https://linux-hardware.org/?probe=e2400bfebe) | Jun 11, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [e2673cf04e](https://linux-hardware.org/?probe=e2673cf04e) | Jun 11, 2023 |
| Unknown       | Unknown                     | [fae1758e76](https://linux-hardware.org/?probe=fae1758e76) | Jun 11, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [baf1f44dc8](https://linux-hardware.org/?probe=baf1f44dc8) | Jun 11, 2023 |
| ASRock        | B650M PG Riptide            | [0f8fc0513f](https://linux-hardware.org/?probe=0f8fc0513f) | Jun 11, 2023 |
| Dell          | 0WMJ54 A01                  | [a6fb35a2d8](https://linux-hardware.org/?probe=a6fb35a2d8) | Jun 11, 2023 |
| Gigabyte      | Z97M-DS3H                   | [d6681f05ec](https://linux-hardware.org/?probe=d6681f05ec) | Jun 11, 2023 |
| Chuwi         | RZBOX                       | [e31b33ae5e](https://linux-hardware.org/?probe=e31b33ae5e) | Jun 11, 2023 |
| ASUSTek       | M5A99FX PRO R2.0            | [2cd4d2c377](https://linux-hardware.org/?probe=2cd4d2c377) | Jun 11, 2023 |
| ASUSTek       | M5A99FX PRO R2.0            | [3544b34815](https://linux-hardware.org/?probe=3544b34815) | Jun 11, 2023 |
| Dell          | 0FDY5C A00                  | [100d556664](https://linux-hardware.org/?probe=100d556664) | Jun 11, 2023 |
| Gigabyte      | GA-990XA-UD3                | [82e1661a51](https://linux-hardware.org/?probe=82e1661a51) | Jun 11, 2023 |
| ASUSTek       | M5A78L/USB3                 | [81e4b3fe5c](https://linux-hardware.org/?probe=81e4b3fe5c) | Jun 10, 2023 |
| ASUSTek       | M5A78L/USB3                 | [b5aee5a0a1](https://linux-hardware.org/?probe=b5aee5a0a1) | Jun 10, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [b6a626c812](https://linux-hardware.org/?probe=b6a626c812) | Jun 10, 2023 |
| ASUSTek       | F2A85-V PRO                 | [43991c533e](https://linux-hardware.org/?probe=43991c533e) | Jun 10, 2023 |
| Intel         | DH55TC AAE70932-302         | [6090a53f8a](https://linux-hardware.org/?probe=6090a53f8a) | Jun 10, 2023 |
| Gigabyte      | B650M GAMING X AX           | [5affc12294](https://linux-hardware.org/?probe=5affc12294) | Jun 10, 2023 |
| ASRock        | B450M Pro4                  | [c23450b0df](https://linux-hardware.org/?probe=c23450b0df) | Jun 10, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [1f8c419c47](https://linux-hardware.org/?probe=1f8c419c47) | Jun 10, 2023 |
| ASUSTek       | PRIME B460M-K               | [873975925d](https://linux-hardware.org/?probe=873975925d) | Jun 10, 2023 |
| Pegatron      | Benicia                     | [c57fee6ea0](https://linux-hardware.org/?probe=c57fee6ea0) | Jun 10, 2023 |
| ASRock        | X570 Phantom Gaming X       | [0c4db9b922](https://linux-hardware.org/?probe=0c4db9b922) | Jun 10, 2023 |
| Gigabyte      | H81M-H                      | [fc025a599d](https://linux-hardware.org/?probe=fc025a599d) | Jun 10, 2023 |
| Gigabyte      | H81M-H                      | [f32fbdf6ea](https://linux-hardware.org/?probe=f32fbdf6ea) | Jun 10, 2023 |
| Dell          | 0PU052                      | [84db4b658c](https://linux-hardware.org/?probe=84db4b658c) | Jun 09, 2023 |
| Dell          | 0PU052                      | [145d296b59](https://linux-hardware.org/?probe=145d296b59) | Jun 09, 2023 |
| Dell          | 0WMJ54 A01                  | [a4d08407bb](https://linux-hardware.org/?probe=a4d08407bb) | Jun 09, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [a1877cb5b3](https://linux-hardware.org/?probe=a1877cb5b3) | Jun 09, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [92fd36b27a](https://linux-hardware.org/?probe=92fd36b27a) | Jun 09, 2023 |
| MSI           | H81I                        | [c7c19346a2](https://linux-hardware.org/?probe=c7c19346a2) | Jun 09, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | [5833483fe2](https://linux-hardware.org/?probe=5833483fe2) | Jun 09, 2023 |
| MSI           | MAG Z490 TOMAHAWK           | [40f18ae1f4](https://linux-hardware.org/?probe=40f18ae1f4) | Jun 09, 2023 |
| ECS           | H81H3-M4                    | [b457e63434](https://linux-hardware.org/?probe=b457e63434) | Jun 09, 2023 |
| Unknown       | GSUO H61V10C                | [0daf816953](https://linux-hardware.org/?probe=0daf816953) | Jun 09, 2023 |
| HP            | 2B35                        | [5921b94b60](https://linux-hardware.org/?probe=5921b94b60) | Jun 09, 2023 |
| Dell          | 0KRC95 A02                  | [585c31e8d3](https://linux-hardware.org/?probe=585c31e8d3) | Jun 08, 2023 |
| Dell          | 0K83V0 A00                  | [fc7fa0850a](https://linux-hardware.org/?probe=fc7fa0850a) | Jun 08, 2023 |
| Gigabyte      | B75M-D3H                    | [8c84a543bf](https://linux-hardware.org/?probe=8c84a543bf) | Jun 08, 2023 |
| Gigabyte      | Z97M-DS3H                   | [5d8df77ade](https://linux-hardware.org/?probe=5d8df77ade) | Jun 08, 2023 |
| Dell          | 0GY6Y8 A02                  | [65f988a0c3](https://linux-hardware.org/?probe=65f988a0c3) | Jun 08, 2023 |
| HJS           | OPSH110D4                   | [bfb0ead991](https://linux-hardware.org/?probe=bfb0ead991) | Jun 08, 2023 |
| AZW           | SEi                         | [399b4a7add](https://linux-hardware.org/?probe=399b4a7add) | Jun 08, 2023 |
| Gigabyte      | H61M-DS2                    | [829912d683](https://linux-hardware.org/?probe=829912d683) | Jun 08, 2023 |
| Dell          | 0GDG8Y A00                  | [4789561d79](https://linux-hardware.org/?probe=4789561d79) | Jun 08, 2023 |
| Dell          | 088DT1 A01                  | [173e9a0e0c](https://linux-hardware.org/?probe=173e9a0e0c) | Jun 08, 2023 |
| Gigabyte      | H61M-DS2                    | [f995c68d61](https://linux-hardware.org/?probe=f995c68d61) | Jun 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [f4e1a7a712](https://linux-hardware.org/?probe=f4e1a7a712) | Jun 08, 2023 |
| Gigabyte      | GA-A75M-D2H                 | [f78a07f792](https://linux-hardware.org/?probe=f78a07f792) | Jun 08, 2023 |
| ASUSTek       | PRIME X570-P                | [a91f24af7a](https://linux-hardware.org/?probe=a91f24af7a) | Jun 08, 2023 |
| ASUSTek       | PRIME X570-P                | [96e1e7ea7e](https://linux-hardware.org/?probe=96e1e7ea7e) | Jun 08, 2023 |
| ASRock        | B85M-HDS                    | [e563fa3fe2](https://linux-hardware.org/?probe=e563fa3fe2) | Jun 07, 2023 |
| ASUSTek       | PRIME B360-PLUS             | [8b82994313](https://linux-hardware.org/?probe=8b82994313) | Jun 07, 2023 |
| ECS           | GF8100VM-M5                 | [6aa065057f](https://linux-hardware.org/?probe=6aa065057f) | Jun 07, 2023 |
| Lenovo        | 3704 SDK0J40700 WIN 3258... | [b18ffc5311](https://linux-hardware.org/?probe=b18ffc5311) | Jun 07, 2023 |
| Foxconn       | H55M-S                      | [83b86844c0](https://linux-hardware.org/?probe=83b86844c0) | Jun 06, 2023 |
| Lenovo        | Kabini CRB 31900058 STD     | [8f3282c700](https://linux-hardware.org/?probe=8f3282c700) | Jun 06, 2023 |
| MSI           | B85-G43 GAMING              | [326a620bbd](https://linux-hardware.org/?probe=326a620bbd) | Jun 06, 2023 |
| ASRock        | H310M-HG4                   | [47b2817d31](https://linux-hardware.org/?probe=47b2817d31) | Jun 06, 2023 |
| MSI           | B85-G43 GAMING              | [9cfd61dae7](https://linux-hardware.org/?probe=9cfd61dae7) | Jun 06, 2023 |
| ASRock        | G41C-GS R2.0                | [6e4835c7bc](https://linux-hardware.org/?probe=6e4835c7bc) | Jun 06, 2023 |
| HP            | 2820h                       | [eb7322ad95](https://linux-hardware.org/?probe=eb7322ad95) | Jun 06, 2023 |
| Chuwi         | RZBOX                       | [f395c0f429](https://linux-hardware.org/?probe=f395c0f429) | Jun 06, 2023 |
| HP            | 3397                        | [f85e642ee3](https://linux-hardware.org/?probe=f85e642ee3) | Jun 06, 2023 |
| Gigabyte      | H310M M.2 x.x               | [602e1c8875](https://linux-hardware.org/?probe=602e1c8875) | Jun 06, 2023 |
| Intel         | DP55WB AAE64798-204         | [fe09edbecc](https://linux-hardware.org/?probe=fe09edbecc) | Jun 06, 2023 |
| Gigabyte      | Z590 VISION G               | [ee1abb360e](https://linux-hardware.org/?probe=ee1abb360e) | Jun 06, 2023 |
| ASUSTek       | PRIME B550M-A AC            | [de614b2bc7](https://linux-hardware.org/?probe=de614b2bc7) | Jun 05, 2023 |
| HP            | 3397                        | [ea59ba572e](https://linux-hardware.org/?probe=ea59ba572e) | Jun 05, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [cc575f0073](https://linux-hardware.org/?probe=cc575f0073) | Jun 05, 2023 |
| ASRock        | G41M-GS3                    | [f8789775fe](https://linux-hardware.org/?probe=f8789775fe) | Jun 05, 2023 |
| Dell          | 0DF42J A00                  | [c68dff0dd7](https://linux-hardware.org/?probe=c68dff0dd7) | Jun 05, 2023 |
| HP            | 83E2                        | [522273fe60](https://linux-hardware.org/?probe=522273fe60) | Jun 05, 2023 |
| ASUSTek       | PRIME B550M-A AC            | [0cf4dfc5e4](https://linux-hardware.org/?probe=0cf4dfc5e4) | Jun 05, 2023 |
| HP            | 3397                        | [e9dd850e23](https://linux-hardware.org/?probe=e9dd850e23) | Jun 05, 2023 |
| Pegatron      | 2AC2                        | [6182103d25](https://linux-hardware.org/?probe=6182103d25) | Jun 05, 2023 |
| MSI           | Boston                      | [9f5efc29ad](https://linux-hardware.org/?probe=9f5efc29ad) | Jun 04, 2023 |
| Lenovo        | ThinkCentre Edge 91Z 707... | [a6804d8ca1](https://linux-hardware.org/?probe=a6804d8ca1) | Jun 04, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [d9dba3ffdf](https://linux-hardware.org/?probe=d9dba3ffdf) | Jun 04, 2023 |
| Intel         | DH55HC AAE70933-503         | [b3d5e112eb](https://linux-hardware.org/?probe=b3d5e112eb) | Jun 04, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [ba0e7c7d59](https://linux-hardware.org/?probe=ba0e7c7d59) | Jun 04, 2023 |
| ASRock        | A75M-HVS                    | [69bc52dc4f](https://linux-hardware.org/?probe=69bc52dc4f) | Jun 04, 2023 |
| Acer          | Predator G3-710             | [7193d24262](https://linux-hardware.org/?probe=7193d24262) | Jun 04, 2023 |
| Acer          | Predator G3-710             | [96834ea12b](https://linux-hardware.org/?probe=96834ea12b) | Jun 04, 2023 |
| HP            | 83E2                        | [3684f8562d](https://linux-hardware.org/?probe=3684f8562d) | Jun 04, 2023 |
| Acer          | Predator G3-710             | [c200dbb9cf](https://linux-hardware.org/?probe=c200dbb9cf) | Jun 04, 2023 |
| Dell          | 0Y5DDC A00                  | [5713168678](https://linux-hardware.org/?probe=5713168678) | Jun 04, 2023 |
| Unknown       | Unknown                     | [8c2d7ce6e2](https://linux-hardware.org/?probe=8c2d7ce6e2) | Jun 04, 2023 |
| Dell          | 0N4NF7 A00                  | [e1348eb2c2](https://linux-hardware.org/?probe=e1348eb2c2) | Jun 03, 2023 |
| Dell          | 0N4NF7 A00                  | [6ff177257b](https://linux-hardware.org/?probe=6ff177257b) | Jun 03, 2023 |
| ASRock        | FM2A88X Extreme6+           | [2745284306](https://linux-hardware.org/?probe=2745284306) | Jun 03, 2023 |
| SZMZ          | X99M-G2                     | [e9b164885c](https://linux-hardware.org/?probe=e9b164885c) | Jun 03, 2023 |
| Dell          | 0D6H9T A01                  | [1ebbe353ba](https://linux-hardware.org/?probe=1ebbe353ba) | Jun 03, 2023 |
| Dell          | 0D6H9T A01                  | [0bb2080b31](https://linux-hardware.org/?probe=0bb2080b31) | Jun 03, 2023 |
| Gigabyte      | X79-UD3                     | [e459d2654f](https://linux-hardware.org/?probe=e459d2654f) | Jun 03, 2023 |
| ASUSTek       | PRIME B650M-A AX            | [983a81f19e](https://linux-hardware.org/?probe=983a81f19e) | Jun 03, 2023 |
| Dell          | 08NPPY A00                  | [de331bfb5c](https://linux-hardware.org/?probe=de331bfb5c) | Jun 02, 2023 |
| Biostar       | TA970XE                     | [11936a0f0f](https://linux-hardware.org/?probe=11936a0f0f) | Jun 02, 2023 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | [c8fca2b92d](https://linux-hardware.org/?probe=c8fca2b92d) | Jun 02, 2023 |
| ASRock        | B365 Pro4                   | [35fff15a30](https://linux-hardware.org/?probe=35fff15a30) | Jun 02, 2023 |
| ASRock        | B365 Pro4                   | [54fcb811b8](https://linux-hardware.org/?probe=54fcb811b8) | Jun 02, 2023 |
| Dell          | 06X1TJ A00                  | [16d662673f](https://linux-hardware.org/?probe=16d662673f) | Jun 02, 2023 |
| ASUSTek       | Maximus Formula             | [6a70fa0a86](https://linux-hardware.org/?probe=6a70fa0a86) | Jun 02, 2023 |
| Gigabyte      | Z97M-DS3H                   | [1a4437e831](https://linux-hardware.org/?probe=1a4437e831) | Jun 02, 2023 |
| Gigabyte      | H61M-S2PV                   | [6c86bd69e0](https://linux-hardware.org/?probe=6c86bd69e0) | Jun 01, 2023 |
| ASRock        | Z77M                        | [eae1adee21](https://linux-hardware.org/?probe=eae1adee21) | Jun 01, 2023 |
| HP            | 18E5                        | [9d89c3065b](https://linux-hardware.org/?probe=9d89c3065b) | Jun 01, 2023 |
| HP            | 1906                        | [ac98480bd2](https://linux-hardware.org/?probe=ac98480bd2) | Jun 01, 2023 |
| HP            | 18E7                        | [a3f557389e](https://linux-hardware.org/?probe=a3f557389e) | Jun 01, 2023 |
| Dell          | 03NVJ6 A00                  | [1f295f3ec2](https://linux-hardware.org/?probe=1f295f3ec2) | Jun 01, 2023 |
| Pegatron      | 2ACB                        | [cfd38fc71a](https://linux-hardware.org/?probe=cfd38fc71a) | May 31, 2023 |
| Gigabyte      | F2A78M-HD2                  | [c76d767402](https://linux-hardware.org/?probe=c76d767402) | May 31, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [6c3655186f](https://linux-hardware.org/?probe=6c3655186f) | May 31, 2023 |
| ASUSTek       | G10DK                       | [75cde40262](https://linux-hardware.org/?probe=75cde40262) | May 31, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [2c6c547437](https://linux-hardware.org/?probe=2c6c547437) | May 31, 2023 |
| MSI           | B450M MORTAR MAX            | [1d0c56937c](https://linux-hardware.org/?probe=1d0c56937c) | May 31, 2023 |
| System76      | Thelio Mira                 | [d5fe3a3749](https://linux-hardware.org/?probe=d5fe3a3749) | May 30, 2023 |
| Intel         | STK2M3W64CC H89289-504      | [a7e599b1f5](https://linux-hardware.org/?probe=a7e599b1f5) | May 30, 2023 |
| ASRock        | H110M-DS/Hyper              | [a29a16d74c](https://linux-hardware.org/?probe=a29a16d74c) | May 30, 2023 |
| Intel         | STK2M3W64CC H89289-504      | [c471536b99](https://linux-hardware.org/?probe=c471536b99) | May 30, 2023 |
| ASRock        | H110M-DS/Hyper              | [05e7ed23f3](https://linux-hardware.org/?probe=05e7ed23f3) | May 30, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | [5271bd0b88](https://linux-hardware.org/?probe=5271bd0b88) | May 30, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [de30e713bf](https://linux-hardware.org/?probe=de30e713bf) | May 30, 2023 |
| Pegatron      | 2AC2                        | [a8873fdeab](https://linux-hardware.org/?probe=a8873fdeab) | May 30, 2023 |
| ASUSTek       | PRIME Z370-P                | [afb02cee29](https://linux-hardware.org/?probe=afb02cee29) | May 29, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [d98102f69a](https://linux-hardware.org/?probe=d98102f69a) | May 29, 2023 |
| Gigabyte      | H410M H                     | [7a52f09646](https://linux-hardware.org/?probe=7a52f09646) | May 29, 2023 |
| Fujitsu       | D3402-A1 S26361-D3402-A1    | [0ae3ea958a](https://linux-hardware.org/?probe=0ae3ea958a) | May 29, 2023 |
| HP            | 1497                        | [5f1886622a](https://linux-hardware.org/?probe=5f1886622a) | May 29, 2023 |
| HP            | 2B43                        | [fb2841cfa4](https://linux-hardware.org/?probe=fb2841cfa4) | May 29, 2023 |
| ASUSTek       | M4A87TD/USB3                | [bf0674c0f0](https://linux-hardware.org/?probe=bf0674c0f0) | May 28, 2023 |
| ASRock        | 970 Pro3 R2.0               | [4ae997cf6b](https://linux-hardware.org/?probe=4ae997cf6b) | May 28, 2023 |
| Lenovo        | 3730 SDK0T76463 WIN 3422... | [7467436de2](https://linux-hardware.org/?probe=7467436de2) | May 28, 2023 |
| HP            | 1495                        | [15b94cba50](https://linux-hardware.org/?probe=15b94cba50) | May 28, 2023 |
| ECS           | H81H3-M4                    | [21261aa270](https://linux-hardware.org/?probe=21261aa270) | May 28, 2023 |
| Dell          | 048DY8 A01                  | [9bfe61714e](https://linux-hardware.org/?probe=9bfe61714e) | May 28, 2023 |
| HP            | 0B54h D                     | [f9634b51b9](https://linux-hardware.org/?probe=f9634b51b9) | May 28, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [dbb348e8bf](https://linux-hardware.org/?probe=dbb348e8bf) | May 28, 2023 |
| Pegatron      | 2ACB                        | [cc1c8b2941](https://linux-hardware.org/?probe=cc1c8b2941) | May 28, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [5a39bd1d78](https://linux-hardware.org/?probe=5a39bd1d78) | May 28, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [a36d2b541a](https://linux-hardware.org/?probe=a36d2b541a) | May 28, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [bb842bc2d8](https://linux-hardware.org/?probe=bb842bc2d8) | May 28, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | [183ee8e37a](https://linux-hardware.org/?probe=183ee8e37a) | May 27, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [ccf71ca66c](https://linux-hardware.org/?probe=ccf71ca66c) | May 27, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [1a3a921775](https://linux-hardware.org/?probe=1a3a921775) | May 27, 2023 |
| MSI           | A55M-E33                    | [c25cb7cbb6](https://linux-hardware.org/?probe=c25cb7cbb6) | May 27, 2023 |
| Gigabyte      | Z97M-DS3H                   | [8311d009bd](https://linux-hardware.org/?probe=8311d009bd) | May 27, 2023 |
| Gigabyte      | Z77MX-D3H                   | [9cb2973f2f](https://linux-hardware.org/?probe=9cb2973f2f) | May 27, 2023 |
| Lenovo        | 31900058 STD                | [d09ae4f1a2](https://linux-hardware.org/?probe=d09ae4f1a2) | May 27, 2023 |
| Gigabyte      | Z77MX-D3H                   | [2cea143017](https://linux-hardware.org/?probe=2cea143017) | May 26, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [b82f4b77f4](https://linux-hardware.org/?probe=b82f4b77f4) | May 26, 2023 |
| ASUSTek       | X99-DELUXE                  | [ebc73bb225](https://linux-hardware.org/?probe=ebc73bb225) | May 26, 2023 |
| Dell          | 0NDYHG A01                  | [07be92d6f3](https://linux-hardware.org/?probe=07be92d6f3) | May 26, 2023 |
| ASUSTek       | Z77-A                       | [0c22362cc0](https://linux-hardware.org/?probe=0c22362cc0) | May 26, 2023 |
| Dell          | 0XCR8D A03                  | [25867f7c36](https://linux-hardware.org/?probe=25867f7c36) | May 26, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [a49bd1dd26](https://linux-hardware.org/?probe=a49bd1dd26) | May 25, 2023 |
| Acer          | Aspire TC-895 V:1.0         | [936b06e11f](https://linux-hardware.org/?probe=936b06e11f) | May 25, 2023 |
| Gigabyte      | P43-ES3G                    | [b9af05a16f](https://linux-hardware.org/?probe=b9af05a16f) | May 25, 2023 |
| ASUSTek       | M4A78LT-M                   | [7080c87654](https://linux-hardware.org/?probe=7080c87654) | May 25, 2023 |
| PCWare        | IPMH110G                    | [33b6fce5ff](https://linux-hardware.org/?probe=33b6fce5ff) | May 25, 2023 |
| ASUSTek       | P5QPL-VM EPU                | [63ba811050](https://linux-hardware.org/?probe=63ba811050) | May 25, 2023 |
| ASUSTek       | P5QPL-VM EPU                | [380b9a5005](https://linux-hardware.org/?probe=380b9a5005) | May 25, 2023 |
| ASUSTek       | F2A85-V                     | [c166f91030](https://linux-hardware.org/?probe=c166f91030) | May 25, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [6e9287cc5c](https://linux-hardware.org/?probe=6e9287cc5c) | May 25, 2023 |
| Dell          | 0654JC A01                  | [d3a2957b45](https://linux-hardware.org/?probe=d3a2957b45) | May 24, 2023 |
| AZW           | SEi                         | [bc0c7a512f](https://linux-hardware.org/?probe=bc0c7a512f) | May 24, 2023 |
| ASRock        | A320M-HDV R4.0              | [bce76b90ef](https://linux-hardware.org/?probe=bce76b90ef) | May 24, 2023 |
| EPSON DIRE... | MR7200E-L                   | [a436b49a11](https://linux-hardware.org/?probe=a436b49a11) | May 24, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [44861be08c](https://linux-hardware.org/?probe=44861be08c) | May 24, 2023 |
| Gigabyte      | H81M-S2V                    | [f0e96b17d7](https://linux-hardware.org/?probe=f0e96b17d7) | May 24, 2023 |
| Gigabyte      | H81M-S2V                    | [02d5fa9cc3](https://linux-hardware.org/?probe=02d5fa9cc3) | May 24, 2023 |
| AZW           | SEi                         | [825fbaebcd](https://linux-hardware.org/?probe=825fbaebcd) | May 23, 2023 |
| Gigabyte      | 970A-DS3P                   | [af5b849c20](https://linux-hardware.org/?probe=af5b849c20) | May 23, 2023 |
| ASUSTek       | B85M-E/BR                   | [ed20b84824](https://linux-hardware.org/?probe=ed20b84824) | May 23, 2023 |
| Gigabyte      | H77N-WIFI                   | [9e96bcdbef](https://linux-hardware.org/?probe=9e96bcdbef) | May 23, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [4e817c1abf](https://linux-hardware.org/?probe=4e817c1abf) | May 23, 2023 |
| Medion        | H110H4-EM                   | [218e19be02](https://linux-hardware.org/?probe=218e19be02) | May 23, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [362ad8bcaf](https://linux-hardware.org/?probe=362ad8bcaf) | May 23, 2023 |
| Dell          | 0JC6JH A00                  | [91d6d0d2da](https://linux-hardware.org/?probe=91d6d0d2da) | May 23, 2023 |
| Pegatron      | 2ACB                        | [e9c0ee4659](https://linux-hardware.org/?probe=e9c0ee4659) | May 23, 2023 |
| Gigabyte      | B75M-D3H                    | [00a6f60d75](https://linux-hardware.org/?probe=00a6f60d75) | May 23, 2023 |
| ASRock        | X399 Professional Gaming    | [72cd126fc6](https://linux-hardware.org/?probe=72cd126fc6) | May 23, 2023 |
| HP            | 0AECh D                     | [06f56df636](https://linux-hardware.org/?probe=06f56df636) | May 23, 2023 |
| eMachines     | EL1360                      | [0821a0d29b](https://linux-hardware.org/?probe=0821a0d29b) | May 22, 2023 |
| Biostar       | A880GZ                      | [097e118b3a](https://linux-hardware.org/?probe=097e118b3a) | May 22, 2023 |
| HP            | 1791                        | [7fa95d1b7b](https://linux-hardware.org/?probe=7fa95d1b7b) | May 22, 2023 |
| Gigabyte      | F2A55M-S1                   | [59ede76205](https://linux-hardware.org/?probe=59ede76205) | May 22, 2023 |
| Gigabyte      | F2A55M-S1                   | [a5c1b4eecd](https://linux-hardware.org/?probe=a5c1b4eecd) | May 22, 2023 |
| ASRock        | B450 Steel Legend           | [012c721256](https://linux-hardware.org/?probe=012c721256) | May 22, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [406014a766](https://linux-hardware.org/?probe=406014a766) | May 22, 2023 |
| ASUSTek       | F2A85-V PRO                 | [dc846ba2e5](https://linux-hardware.org/?probe=dc846ba2e5) | May 22, 2023 |
| Medion        | B360H4-EM V1.0              | [ae4f01f58e](https://linux-hardware.org/?probe=ae4f01f58e) | May 22, 2023 |
| MSI           | Z87-G43                     | [2fa7c1d81d](https://linux-hardware.org/?probe=2fa7c1d81d) | May 21, 2023 |
| Gigabyte      | B550M DS3H                  | [7db2aa27dc](https://linux-hardware.org/?probe=7db2aa27dc) | May 21, 2023 |
| Dell          | 033FF6 A00                  | [086dd9367e](https://linux-hardware.org/?probe=086dd9367e) | May 21, 2023 |
| Gigabyte      | B450M S2H                   | [5309c41b94](https://linux-hardware.org/?probe=5309c41b94) | May 21, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a6f95de398](https://linux-hardware.org/?probe=a6f95de398) | May 21, 2023 |
| ASUSTek       | P8B75-M                     | [313fb9c88a](https://linux-hardware.org/?probe=313fb9c88a) | May 21, 2023 |
| Gigabyte      | Z390 UD                     | [867806192a](https://linux-hardware.org/?probe=867806192a) | May 21, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [62b86acadc](https://linux-hardware.org/?probe=62b86acadc) | May 21, 2023 |
| Dell          | 0VNP2H A00                  | [298317e388](https://linux-hardware.org/?probe=298317e388) | May 21, 2023 |
| ASUSTek       | P8Z68-V LX                  | [27c48503ad](https://linux-hardware.org/?probe=27c48503ad) | May 21, 2023 |
| Unknown       | GSUO H61V10C                | [8e1037e4c1](https://linux-hardware.org/?probe=8e1037e4c1) | May 20, 2023 |
| Gigabyte      | F2A88X-D3H                  | [a547a22c01](https://linux-hardware.org/?probe=a547a22c01) | May 20, 2023 |
| Medion        | BTDD-LT                     | [3b5eac782c](https://linux-hardware.org/?probe=3b5eac782c) | May 20, 2023 |
| MSI           | H97M-G43                    | [2e31a2b7e0](https://linux-hardware.org/?probe=2e31a2b7e0) | May 20, 2023 |
| Dell          | 0JP3NX A01                  | [a4a766a9e1](https://linux-hardware.org/?probe=a4a766a9e1) | May 20, 2023 |
| Daten Tecn... | DA320MXV DC                 | [0b7e1e51b9](https://linux-hardware.org/?probe=0b7e1e51b9) | May 20, 2023 |
| ASUSTek       | PRIME B560-PLUS             | [6f6b65d0ed](https://linux-hardware.org/?probe=6f6b65d0ed) | May 19, 2023 |
| Pegatron      | Benicia                     | [24fc512198](https://linux-hardware.org/?probe=24fc512198) | May 19, 2023 |
| Gigabyte      | B360M DS3H                  | [b6336515aa](https://linux-hardware.org/?probe=b6336515aa) | May 19, 2023 |
| Acer          | TDPS05                      | [ed5384ee4d](https://linux-hardware.org/?probe=ed5384ee4d) | May 19, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [665ac2defe](https://linux-hardware.org/?probe=665ac2defe) | May 19, 2023 |
| ASRock        | H110M-DS/Hyper              | [b208edbf01](https://linux-hardware.org/?probe=b208edbf01) | May 19, 2023 |
| Gigabyte      | Z97M-DS3H                   | [db9774a799](https://linux-hardware.org/?probe=db9774a799) | May 19, 2023 |
| ASRock        | H110M-DS/Hyper              | [c90642a42c](https://linux-hardware.org/?probe=c90642a42c) | May 19, 2023 |
| ASUSTek       | PRIME H410M-R               | [09cc939f04](https://linux-hardware.org/?probe=09cc939f04) | May 19, 2023 |
| Gigabyte      | H310M S2                    | [61f60c8a7d](https://linux-hardware.org/?probe=61f60c8a7d) | May 19, 2023 |
| Gigabyte      | B460M DS3H V2               | [0d337f6d69](https://linux-hardware.org/?probe=0d337f6d69) | May 19, 2023 |
| Dell          | 0MGK50 A02                  | [7b98244b73](https://linux-hardware.org/?probe=7b98244b73) | May 19, 2023 |
| Pegatron      | Benicia                     | [6bb420fe9a](https://linux-hardware.org/?probe=6bb420fe9a) | May 19, 2023 |
| ASRock        | B365M Pro4                  | [0df5d6f44e](https://linux-hardware.org/?probe=0df5d6f44e) | May 19, 2023 |
| Dell          | 0VNP2H A01                  | [6e51bd033e](https://linux-hardware.org/?probe=6e51bd033e) | May 19, 2023 |
| ASUSTek       | PRIME B550M-A AC            | [916931d01a](https://linux-hardware.org/?probe=916931d01a) | May 19, 2023 |
| MSI           | Z97-G55 SLI                 | [a17ed55b13](https://linux-hardware.org/?probe=a17ed55b13) | May 19, 2023 |
| Dell          | 0D881F A06                  | [2d5184956b](https://linux-hardware.org/?probe=2d5184956b) | May 18, 2023 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | [75ca7ed17e](https://linux-hardware.org/?probe=75ca7ed17e) | May 18, 2023 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | [839536ab43](https://linux-hardware.org/?probe=839536ab43) | May 18, 2023 |
| MSI           | Z97-G55 SLI                 | [0883ceb18c](https://linux-hardware.org/?probe=0883ceb18c) | May 18, 2023 |
| ASUSTek       | CROSSBLADE RANGER           | [afd85b3621](https://linux-hardware.org/?probe=afd85b3621) | May 18, 2023 |
| Dell          | 0VRWRC A00                  | [c7f7f8758b](https://linux-hardware.org/?probe=c7f7f8758b) | May 18, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [c09d32ebc2](https://linux-hardware.org/?probe=c09d32ebc2) | May 18, 2023 |
| Gigabyte      | GB-BRR7H-4700               | [215d88c8b6](https://linux-hardware.org/?probe=215d88c8b6) | May 18, 2023 |
| Gigabyte      | GB-BRR7H-4700               | [d452669f4a](https://linux-hardware.org/?probe=d452669f4a) | May 18, 2023 |
| ASUSTek       | PRIME B560M-A               | [e33e3678c6](https://linux-hardware.org/?probe=e33e3678c6) | May 18, 2023 |
| Gigabyte      | H310M S2                    | [b8a04e73b8](https://linux-hardware.org/?probe=b8a04e73b8) | May 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [be46da6480](https://linux-hardware.org/?probe=be46da6480) | May 18, 2023 |
| Dell          | 0VNP2H A00                  | [85da02478a](https://linux-hardware.org/?probe=85da02478a) | May 17, 2023 |
| Dell          | 0RY007                      | [c2b8174064](https://linux-hardware.org/?probe=c2b8174064) | May 17, 2023 |
| Gigabyte      | GA-A75M-D2H                 | [ad477b9698](https://linux-hardware.org/?probe=ad477b9698) | May 17, 2023 |
| ASUSTek       | H81M-A/BR                   | [0982e8a637](https://linux-hardware.org/?probe=0982e8a637) | May 17, 2023 |
| Gigabyte      | Z370P D3-CF                 | [874dcebbaa](https://linux-hardware.org/?probe=874dcebbaa) | May 17, 2023 |
| eMachines     | EMCP73VT-PM                 | [d17610915a](https://linux-hardware.org/?probe=d17610915a) | May 17, 2023 |
| Gigabyte      | Z370P D3-CF                 | [af16278f1e](https://linux-hardware.org/?probe=af16278f1e) | May 17, 2023 |
| ASUSTek       | P7H55D-M PRO                | [2c423cf3e9](https://linux-hardware.org/?probe=2c423cf3e9) | May 17, 2023 |
| Intel         | D54250WYK H13922-302        | [0829603c60](https://linux-hardware.org/?probe=0829603c60) | May 17, 2023 |
| ASRock        | Z97 Professional            | [7d0ecd3359](https://linux-hardware.org/?probe=7d0ecd3359) | May 17, 2023 |
| EPSON DIRE... | MR7200E-L                   | [fed1ba2b90](https://linux-hardware.org/?probe=fed1ba2b90) | May 17, 2023 |
| ASUSTek       | P5E WS Pro                  | [97a221407d](https://linux-hardware.org/?probe=97a221407d) | May 17, 2023 |
| Acer          | TDPS05                      | [2cfc303d36](https://linux-hardware.org/?probe=2cfc303d36) | May 17, 2023 |
| EPSON DIRE... | MR7200E-L                   | [b0710623f7](https://linux-hardware.org/?probe=b0710623f7) | May 17, 2023 |
| eMachines     | EMCP73VT-PM                 | [777f8ccab0](https://linux-hardware.org/?probe=777f8ccab0) | May 17, 2023 |
| ZOTAC         | Unknown                     | [5ae0ed6f5a](https://linux-hardware.org/?probe=5ae0ed6f5a) | May 16, 2023 |
| ASUSTek       | PRIME B650M-A AX            | [c7c487333a](https://linux-hardware.org/?probe=c7c487333a) | May 16, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [afbef25815](https://linux-hardware.org/?probe=afbef25815) | May 16, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [546f6e95e9](https://linux-hardware.org/?probe=546f6e95e9) | May 16, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [54fc8d0489](https://linux-hardware.org/?probe=54fc8d0489) | May 16, 2023 |
| SHANGZHAOY... | X99-D8-MAX V1.0             | [b77555d36f](https://linux-hardware.org/?probe=b77555d36f) | May 16, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [3f5bade9b8](https://linux-hardware.org/?probe=3f5bade9b8) | May 16, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | [bdaec355df](https://linux-hardware.org/?probe=bdaec355df) | May 16, 2023 |
| ASUSTek       | X99-DELUXE                  | [d2fbc01926](https://linux-hardware.org/?probe=d2fbc01926) | May 15, 2023 |
| Supermicro    | H12DSU-iN                   | [05b2b86f35](https://linux-hardware.org/?probe=05b2b86f35) | May 15, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | [6a8a2f481e](https://linux-hardware.org/?probe=6a8a2f481e) | May 15, 2023 |
| ASUSTek       | H97-PLUS                    | [e67567bd2a](https://linux-hardware.org/?probe=e67567bd2a) | May 15, 2023 |
| Fujitsu       | JIB75Y3                     | [31146fe86e](https://linux-hardware.org/?probe=31146fe86e) | May 15, 2023 |
| MSI           | Z87-G45 GAMING              | [06e1ef84b3](https://linux-hardware.org/?probe=06e1ef84b3) | May 15, 2023 |
| ASUSTek       | F2A85-V PRO                 | [b21029ef65](https://linux-hardware.org/?probe=b21029ef65) | May 15, 2023 |
| Medion        | B360H4-EM V1.0              | [1efefa9214](https://linux-hardware.org/?probe=1efefa9214) | May 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [6e8f0dd2b9](https://linux-hardware.org/?probe=6e8f0dd2b9) | May 15, 2023 |
| Dell          | 0N4YC8 A00                  | [61eeca9cec](https://linux-hardware.org/?probe=61eeca9cec) | May 15, 2023 |
| Dell          | 0J3C2F A00                  | [17b9d54da0](https://linux-hardware.org/?probe=17b9d54da0) | May 15, 2023 |
| SHANGZHAOY... | X99-D8-MAX V1.0             | [6e21010553](https://linux-hardware.org/?probe=6e21010553) | May 15, 2023 |
| HP            | 0B4Ch D                     | [64b813a7dc](https://linux-hardware.org/?probe=64b813a7dc) | May 14, 2023 |
| Lenovo        | 310B SDK0J40705 WIN 3425... | [94d901f023](https://linux-hardware.org/?probe=94d901f023) | May 14, 2023 |
| Pegatron      | IPXSB-H61                   | [c585628bc8](https://linux-hardware.org/?probe=c585628bc8) | May 14, 2023 |
| Pegatron      | 2AC2                        | [510047e597](https://linux-hardware.org/?probe=510047e597) | May 14, 2023 |
| Lenovo        | Dory CRB                    | [8e0efa6d0a](https://linux-hardware.org/?probe=8e0efa6d0a) | May 14, 2023 |
| eMachines     | EL1360                      | [74745ea02b](https://linux-hardware.org/?probe=74745ea02b) | May 14, 2023 |
| Biostar       | N61PB-M2S                   | [4ac75a003b](https://linux-hardware.org/?probe=4ac75a003b) | May 14, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | [dc1d9d7e15](https://linux-hardware.org/?probe=dc1d9d7e15) | May 14, 2023 |
| Gigabyte      | Z97M-DS3H                   | [091a42a1c0](https://linux-hardware.org/?probe=091a42a1c0) | May 14, 2023 |
| Intel         | DH77DF AAG40293-301         | [f35c753afd](https://linux-hardware.org/?probe=f35c753afd) | May 14, 2023 |
| Pegatron      | 2AB5                        | [2381fb0c55](https://linux-hardware.org/?probe=2381fb0c55) | May 14, 2023 |
| Intel         | DH77DF AAG40293-301         | [65ad7c5ad5](https://linux-hardware.org/?probe=65ad7c5ad5) | May 13, 2023 |
| Fujitsu       | D3011-A1 S26361-D3011-A1    | [ede664c4ca](https://linux-hardware.org/?probe=ede664c4ca) | May 13, 2023 |
| Fujitsu       | D3011-A1 S26361-D3011-A1    | [4849aadd59](https://linux-hardware.org/?probe=4849aadd59) | May 13, 2023 |
| MSI           | A68HM-E33 V2                | [a60326fa0a](https://linux-hardware.org/?probe=a60326fa0a) | May 13, 2023 |
| Gateway       | DX4840                      | [b96adf8863](https://linux-hardware.org/?probe=b96adf8863) | May 13, 2023 |
| Intel         | B75                         | [da0a89cf17](https://linux-hardware.org/?probe=da0a89cf17) | May 13, 2023 |
| Toshiba       | STI 007567                  | [579ec5bb2b](https://linux-hardware.org/?probe=579ec5bb2b) | May 13, 2023 |
| Dell          | 0NC2VH A01                  | [48c5ff757c](https://linux-hardware.org/?probe=48c5ff757c) | May 13, 2023 |
| ASUSTek       | M5A78L-M LX                 | [f720713dda](https://linux-hardware.org/?probe=f720713dda) | May 13, 2023 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [62aab97f35](https://linux-hardware.org/?probe=62aab97f35) | May 12, 2023 |
| ASUSTek       | X99-DELUXE                  | [2acd6e02ea](https://linux-hardware.org/?probe=2acd6e02ea) | May 12, 2023 |
| ASRock        | H510M-ITX/ac                | [9a8da03c1e](https://linux-hardware.org/?probe=9a8da03c1e) | May 12, 2023 |
| Medion        | BTDD-LT                     | [86a5697c9c](https://linux-hardware.org/?probe=86a5697c9c) | May 12, 2023 |
| Gigabyte      | Z97M-DS3H                   | [29b8cfc7e6](https://linux-hardware.org/?probe=29b8cfc7e6) | May 12, 2023 |
| Gigabyte      | MW51-HP0-00                 | [ed263fdd1b](https://linux-hardware.org/?probe=ed263fdd1b) | May 12, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | [01b1668378](https://linux-hardware.org/?probe=01b1668378) | May 12, 2023 |
| Biostar       | A68N-5600E                  | [55db0c720e](https://linux-hardware.org/?probe=55db0c720e) | May 12, 2023 |
| Intel         | DH87RL AAG74240-403         | [888f0a2923](https://linux-hardware.org/?probe=888f0a2923) | May 12, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [7b966568cc](https://linux-hardware.org/?probe=7b966568cc) | May 12, 2023 |
| Gigabyte      | Z590 GAMING X               | [c9ad858393](https://linux-hardware.org/?probe=c9ad858393) | May 12, 2023 |
| Acer          | Nitro N50-600 V:1.1         | [40d2790e0a](https://linux-hardware.org/?probe=40d2790e0a) | May 12, 2023 |
| ASUSTek       | P8P67 LE                    | [cae9bea146](https://linux-hardware.org/?probe=cae9bea146) | May 12, 2023 |
| MSI           | H61M-P20/W8                 | [b727300be6](https://linux-hardware.org/?probe=b727300be6) | May 11, 2023 |
| Biostar       | B450MH                      | [e5dac06f4e](https://linux-hardware.org/?probe=e5dac06f4e) | May 11, 2023 |
| ZOTAC         | Unknown                     | [9495c6ca84](https://linux-hardware.org/?probe=9495c6ca84) | May 11, 2023 |
| Biostar       | B450MH                      | [12659ad2e2](https://linux-hardware.org/?probe=12659ad2e2) | May 11, 2023 |
| Gigabyte      | Z270N-Gaming 5              | [c056fdd9a8](https://linux-hardware.org/?probe=c056fdd9a8) | May 11, 2023 |
| Dell          | 0X8DXD A00                  | [1e8359a02c](https://linux-hardware.org/?probe=1e8359a02c) | May 11, 2023 |
| Dell          | 0T10XW A02                  | [a488bed661](https://linux-hardware.org/?probe=a488bed661) | May 11, 2023 |
| Lenovo        | 310B SDK0J40705 WIN 3425... | [53d9e318f6](https://linux-hardware.org/?probe=53d9e318f6) | May 11, 2023 |
| Biostar       | H110MHV3                    | [e1ce381308](https://linux-hardware.org/?probe=e1ce381308) | May 11, 2023 |
| Biostar       | H110MHV3                    | [5b0f8f8419](https://linux-hardware.org/?probe=5b0f8f8419) | May 11, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [3df5f7ec7e](https://linux-hardware.org/?probe=3df5f7ec7e) | May 11, 2023 |
| Dell          | 0Y958C A00                  | [fb1b987ad5](https://linux-hardware.org/?probe=fb1b987ad5) | May 10, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [1b20151b4c](https://linux-hardware.org/?probe=1b20151b4c) | May 10, 2023 |
| Dell          | 076VHM A02                  | [7f1984ec16](https://linux-hardware.org/?probe=7f1984ec16) | May 10, 2023 |
| Dell          | 0GDG8Y A00                  | [e9e13fa531](https://linux-hardware.org/?probe=e9e13fa531) | May 10, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [554b258b3c](https://linux-hardware.org/?probe=554b258b3c) | May 10, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [3ea46668c4](https://linux-hardware.org/?probe=3ea46668c4) | May 10, 2023 |
| Dell          | 0GM819                      | [ccd99ab6c3](https://linux-hardware.org/?probe=ccd99ab6c3) | May 10, 2023 |
| ASUSTek       | P8Z68-M PRO                 | [37b88384a5](https://linux-hardware.org/?probe=37b88384a5) | May 10, 2023 |
| AZW           | MINI S 10                   | [c64432906e](https://linux-hardware.org/?probe=c64432906e) | May 10, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | [02c4a35621](https://linux-hardware.org/?probe=02c4a35621) | May 10, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [a9df4bc7fb](https://linux-hardware.org/?probe=a9df4bc7fb) | May 10, 2023 |
| MSI           | MAG B560 TOMAHAWK WIFI      | [6fd3dea188](https://linux-hardware.org/?probe=6fd3dea188) | May 10, 2023 |
| MSI           | MAG B560 TOMAHAWK WIFI      | [e55b8813e3](https://linux-hardware.org/?probe=e55b8813e3) | May 10, 2023 |
| MSI           | B350M PRO-VDH               | [9caca8f4cc](https://linux-hardware.org/?probe=9caca8f4cc) | May 10, 2023 |
| ASUSTek       | H170-PRO                    | [8f41b17a9b](https://linux-hardware.org/?probe=8f41b17a9b) | May 10, 2023 |
| ASUSTek       | X99-DELUXE II               | [966821ec0d](https://linux-hardware.org/?probe=966821ec0d) | May 10, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [6ddb2fa975](https://linux-hardware.org/?probe=6ddb2fa975) | May 10, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [16bdfe6490](https://linux-hardware.org/?probe=16bdfe6490) | May 10, 2023 |
| Gigabyte      | B450M AORUS ELITE           | [fbe7b6d2bf](https://linux-hardware.org/?probe=fbe7b6d2bf) | May 10, 2023 |
| Dell          | 0D883F A06                  | [18afa7a07b](https://linux-hardware.org/?probe=18afa7a07b) | May 10, 2023 |
| Intel         | DQ57TM AAE70931-402         | [df02c1cce7](https://linux-hardware.org/?probe=df02c1cce7) | May 09, 2023 |
| HP            | 18E5                        | [09eb27d0c5](https://linux-hardware.org/?probe=09eb27d0c5) | May 09, 2023 |
| Dell          | 0KC9NP A01                  | [575bffc7a9](https://linux-hardware.org/?probe=575bffc7a9) | May 09, 2023 |
| HP            | 3398                        | [360aa1ac89](https://linux-hardware.org/?probe=360aa1ac89) | May 09, 2023 |
| Lenovo        | Dory CRB                    | [e7ffe2585f](https://linux-hardware.org/?probe=e7ffe2585f) | May 09, 2023 |
| Gigabyte      | Z97X-Gaming 5               | [588003adc9](https://linux-hardware.org/?probe=588003adc9) | May 09, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [58a9b45939](https://linux-hardware.org/?probe=58a9b45939) | May 09, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | [bcccbb24de](https://linux-hardware.org/?probe=bcccbb24de) | May 09, 2023 |
| Dell          | 0KYJ8C A02                  | [ce4726c253](https://linux-hardware.org/?probe=ce4726c253) | May 09, 2023 |
| Lenovo        | ThinkCentre M71z 1782W14    | [f5a1b23281](https://linux-hardware.org/?probe=f5a1b23281) | May 09, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [228e778389](https://linux-hardware.org/?probe=228e778389) | May 09, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [c8ab230418](https://linux-hardware.org/?probe=c8ab230418) | May 08, 2023 |
| Gigabyte      | F2A78M-HD2                  | [0a758d5a5d](https://linux-hardware.org/?probe=0a758d5a5d) | May 08, 2023 |
| Gigabyte      | H310M H x.x                 | [e44f7dfac5](https://linux-hardware.org/?probe=e44f7dfac5) | May 08, 2023 |
| ASRock        | J4125M                      | [a702df382b](https://linux-hardware.org/?probe=a702df382b) | May 08, 2023 |
| Dell          | 096JG8 A01                  | [08df3c35ee](https://linux-hardware.org/?probe=08df3c35ee) | May 08, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | [dc43e4a7e3](https://linux-hardware.org/?probe=dc43e4a7e3) | May 08, 2023 |
| HP            | 1998                        | [2ed500d3e9](https://linux-hardware.org/?probe=2ed500d3e9) | May 08, 2023 |
| HP            | 1998                        | [558c305af2](https://linux-hardware.org/?probe=558c305af2) | May 08, 2023 |
| Gigabyte      | G41MT-S2                    | [0458d9f44b](https://linux-hardware.org/?probe=0458d9f44b) | May 08, 2023 |
| NEC Comput... | IH81M                       | [407098c17f](https://linux-hardware.org/?probe=407098c17f) | May 07, 2023 |
| ASUSTek       | M5A88-V EVO                 | [c174fcc2d8](https://linux-hardware.org/?probe=c174fcc2d8) | May 07, 2023 |
| Dell          | 09KPNV A00                  | [6089dfdeab](https://linux-hardware.org/?probe=6089dfdeab) | May 07, 2023 |
| ASUSTek       | STRIX B250I GAMING          | [536e6e7cc9](https://linux-hardware.org/?probe=536e6e7cc9) | May 07, 2023 |
| Lenovo        | 30C0 SDK0J40697 WIN 3305... | [94ab5e431c](https://linux-hardware.org/?probe=94ab5e431c) | May 07, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | [25c4b5fe60](https://linux-hardware.org/?probe=25c4b5fe60) | May 07, 2023 |
| MSI           | 2A9C                        | [4acb37f728](https://linux-hardware.org/?probe=4acb37f728) | May 07, 2023 |
| Datto         | SSD                         | [c086218bd4](https://linux-hardware.org/?probe=c086218bd4) | May 07, 2023 |
| ASUSTek       | Z77-A                       | [92b5951471](https://linux-hardware.org/?probe=92b5951471) | May 07, 2023 |
| ASRock        | J4125M                      | [57865d6cea](https://linux-hardware.org/?probe=57865d6cea) | May 07, 2023 |
| Intel         | H61                         | [cd89c5b708](https://linux-hardware.org/?probe=cd89c5b708) | May 06, 2023 |
| Gateway       | DX4870                      | [dcd0bbb01a](https://linux-hardware.org/?probe=dcd0bbb01a) | May 06, 2023 |
| ASRock        | N3150-NUC                   | [5775b2c94f](https://linux-hardware.org/?probe=5775b2c94f) | May 06, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [00794346db](https://linux-hardware.org/?probe=00794346db) | May 06, 2023 |
| Gigabyte      | A320M-H-CF                  | [ee58ce6d9c](https://linux-hardware.org/?probe=ee58ce6d9c) | May 06, 2023 |
| Acer          | EG43M                       | [50ee9c3423](https://linux-hardware.org/?probe=50ee9c3423) | May 06, 2023 |
| ASUSTek       | SABERTOOTH X79              | [f9d2b57c91](https://linux-hardware.org/?probe=f9d2b57c91) | May 06, 2023 |
| ASRock        | 945GCM-S                    | [940d88bfce](https://linux-hardware.org/?probe=940d88bfce) | May 06, 2023 |
| ASUSTek       | A88XM-PLUS                  | [870a49d90c](https://linux-hardware.org/?probe=870a49d90c) | May 05, 2023 |
| Gigabyte      | GA-MA785GMT-UD2H            | [50fba20da2](https://linux-hardware.org/?probe=50fba20da2) | May 05, 2023 |
| Biostar       | G41D3C                      | [15680367e1](https://linux-hardware.org/?probe=15680367e1) | May 05, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [14c71828ca](https://linux-hardware.org/?probe=14c71828ca) | May 05, 2023 |
| Gigabyte      | Z97M-DS3H                   | [8774a893d6](https://linux-hardware.org/?probe=8774a893d6) | May 05, 2023 |
| ASRock        | B560M Pro4                  | [5491fd5858](https://linux-hardware.org/?probe=5491fd5858) | May 05, 2023 |
| ASRock        | A320M-HDV R4.0              | [d27392828f](https://linux-hardware.org/?probe=d27392828f) | May 05, 2023 |
| ASUSTek       | P5KPL-AM/PS                 | [a5c1634444](https://linux-hardware.org/?probe=a5c1634444) | May 05, 2023 |
| MSI           | Z170A GAMING M5             | [3f515702d2](https://linux-hardware.org/?probe=3f515702d2) | May 05, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [867e98f955](https://linux-hardware.org/?probe=867e98f955) | May 05, 2023 |
| HP            | 21EF                        | [6dd5a8409e](https://linux-hardware.org/?probe=6dd5a8409e) | May 05, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | [36de4a9de4](https://linux-hardware.org/?probe=36de4a9de4) | May 05, 2023 |
| ASUSTek       | PRIME A320M-K               | [a375533daa](https://linux-hardware.org/?probe=a375533daa) | May 05, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [f0bc6ca2dd](https://linux-hardware.org/?probe=f0bc6ca2dd) | May 05, 2023 |
| Dell          | 02YYK5 A01                  | [6ea350c49d](https://linux-hardware.org/?probe=6ea350c49d) | May 05, 2023 |
| Dell          | 02YYK5 A01                  | [f688c82ff2](https://linux-hardware.org/?probe=f688c82ff2) | May 05, 2023 |
| Dell          | 0J3C2F A00                  | [a8d4348329](https://linux-hardware.org/?probe=a8d4348329) | May 04, 2023 |
| Gigabyte      | B550 GAMING X V2            | [11a0e59867](https://linux-hardware.org/?probe=11a0e59867) | May 04, 2023 |
| YANYU         | EPIC-N56_I522E Ver          | [b2ff986f07](https://linux-hardware.org/?probe=b2ff986f07) | May 04, 2023 |
| Gigabyte      | B550M DS3H                  | [e8c596445b](https://linux-hardware.org/?probe=e8c596445b) | May 04, 2023 |
| Gigabyte      | B550M DS3H                  | [372a18076a](https://linux-hardware.org/?probe=372a18076a) | May 04, 2023 |
| ASUSTek       | PRIME H370M-PLUS            | [c7011d8c2a](https://linux-hardware.org/?probe=c7011d8c2a) | May 04, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | [a2f3590a6a](https://linux-hardware.org/?probe=a2f3590a6a) | May 04, 2023 |
| Gigabyte      | G31M-ES2L                   | [cbcc5a5b9f](https://linux-hardware.org/?probe=cbcc5a5b9f) | May 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [424f0dca9d](https://linux-hardware.org/?probe=424f0dca9d) | May 04, 2023 |
| HP            | 8055                        | [b17e451ea7](https://linux-hardware.org/?probe=b17e451ea7) | May 03, 2023 |
| ASUSTek       | H81M-K                      | [e146c82a49](https://linux-hardware.org/?probe=e146c82a49) | May 03, 2023 |
| ASUSTek       | CROSSBLADE RANGER           | [99860cb84a](https://linux-hardware.org/?probe=99860cb84a) | May 03, 2023 |
| Lenovo        | 3730 SDK0T76463 WIN 3422... | [61873cde49](https://linux-hardware.org/?probe=61873cde49) | May 03, 2023 |
| Gigabyte      | H310M H x.x                 | [7996838ce9](https://linux-hardware.org/?probe=7996838ce9) | May 03, 2023 |
| ASUSTek       | PRIME Z590-P                | [bbd9496296](https://linux-hardware.org/?probe=bbd9496296) | May 03, 2023 |
| ASUSTek       | P5NT WS                     | [70d5fd7a1d](https://linux-hardware.org/?probe=70d5fd7a1d) | May 03, 2023 |
| ASRock        | H81M-HDS R2.0               | [d0120d30ca](https://linux-hardware.org/?probe=d0120d30ca) | May 03, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [169cbbf5a9](https://linux-hardware.org/?probe=169cbbf5a9) | May 03, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [3a7e1532da](https://linux-hardware.org/?probe=3a7e1532da) | May 03, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [1e26913701](https://linux-hardware.org/?probe=1e26913701) | May 03, 2023 |
| ASUSTek       | CROSSBLADE RANGER           | [c64363305b](https://linux-hardware.org/?probe=c64363305b) | May 03, 2023 |
| Intel         | PH10LU E13069-531           | [432b5e380d](https://linux-hardware.org/?probe=432b5e380d) | May 03, 2023 |
| Intel         | PH10LU E13069-531           | [f34e545b00](https://linux-hardware.org/?probe=f34e545b00) | May 03, 2023 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [6873c6d2aa](https://linux-hardware.org/?probe=6873c6d2aa) | May 03, 2023 |
| ASUSTek       | H110M-A                     | [a99c9cd007](https://linux-hardware.org/?probe=a99c9cd007) | May 02, 2023 |
| HP            | 86FC MVB                    | [de40052f4c](https://linux-hardware.org/?probe=de40052f4c) | May 02, 2023 |
| Dell          | 0NW6H5 A00                  | [11e8fb1ecd](https://linux-hardware.org/?probe=11e8fb1ecd) | May 02, 2023 |
| Dell          | 0NW6H5 A00                  | [2675aa56c4](https://linux-hardware.org/?probe=2675aa56c4) | May 02, 2023 |
| Unknown       | 1.0                         | [e3580544f1](https://linux-hardware.org/?probe=e3580544f1) | May 02, 2023 |
| HP            | 82B4                        | [5c0b7b180d](https://linux-hardware.org/?probe=5c0b7b180d) | May 02, 2023 |
| Dell          | 03NVJ6 A01                  | [b585380bc4](https://linux-hardware.org/?probe=b585380bc4) | May 02, 2023 |
| HP            | 2AFB                        | [a2d8494867](https://linux-hardware.org/?probe=a2d8494867) | May 01, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | [bf317c9241](https://linux-hardware.org/?probe=bf317c9241) | May 01, 2023 |
| Dell          | 0D6H9T A00                  | [0e46a82cca](https://linux-hardware.org/?probe=0e46a82cca) | May 01, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [f3b0efc277](https://linux-hardware.org/?probe=f3b0efc277) | May 01, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [56c837b00f](https://linux-hardware.org/?probe=56c837b00f) | May 01, 2023 |
| Intel         | D54250WYK H13922-302        | [973f9c6467](https://linux-hardware.org/?probe=973f9c6467) | May 01, 2023 |
| Lenovo        | Dory CRB                    | [29636a9923](https://linux-hardware.org/?probe=29636a9923) | May 01, 2023 |
| Intel         | D54250WYK H13922-302        | [92f7217eb7](https://linux-hardware.org/?probe=92f7217eb7) | May 01, 2023 |
| Acer          | Aspire M3970                | [87a55abfa7](https://linux-hardware.org/?probe=87a55abfa7) | May 01, 2023 |
| MSI           | X99A GAMING 7               | [dfb285267c](https://linux-hardware.org/?probe=dfb285267c) | May 01, 2023 |
| Acer          | EQ35M                       | [52de48d7c8](https://linux-hardware.org/?probe=52de48d7c8) | May 01, 2023 |
| ASRock        | 970 Pro3 R2.0               | [26681d2879](https://linux-hardware.org/?probe=26681d2879) | May 01, 2023 |
| ASUSTek       | PRIME H610M-E D4            | [56db7fc27f](https://linux-hardware.org/?probe=56db7fc27f) | May 01, 2023 |
| ASRock        | 970 Pro3 R2.0               | [577b5e8f51](https://linux-hardware.org/?probe=577b5e8f51) | May 01, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [27fdafaf01](https://linux-hardware.org/?probe=27fdafaf01) | May 01, 2023 |
| Gigabyte      | Z77MX-D3H                   | [fa4e32fe2c](https://linux-hardware.org/?probe=fa4e32fe2c) | May 01, 2023 |
| Dell          | 09KPNV A01                  | [45dad4b8e9](https://linux-hardware.org/?probe=45dad4b8e9) | May 01, 2023 |
| ASRock        | B660M-HDV                   | [a137e6ab62](https://linux-hardware.org/?probe=a137e6ab62) | May 01, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [4f0b170b70](https://linux-hardware.org/?probe=4f0b170b70) | May 01, 2023 |
| ASUSTek       | PRIME B550M-A AC            | [f10c443a56](https://linux-hardware.org/?probe=f10c443a56) | May 01, 2023 |
| Dell          | 07PR60 A00                  | [e6f49bbe8a](https://linux-hardware.org/?probe=e6f49bbe8a) | Apr 30, 2023 |
| ASUSTek       | H81-PLUS                    | [3b45144d62](https://linux-hardware.org/?probe=3b45144d62) | Apr 30, 2023 |
| Gigabyte      | EP45-UD3P                   | [8d99ef5cc7](https://linux-hardware.org/?probe=8d99ef5cc7) | Apr 30, 2023 |
| ASUSTek       | H81I-PLUS                   | [01578538eb](https://linux-hardware.org/?probe=01578538eb) | Apr 30, 2023 |
| MSI           | PRO Z690-A WIFI             | [bfa4eb5eda](https://linux-hardware.org/?probe=bfa4eb5eda) | Apr 30, 2023 |
| ASRock        | B550M Steel Legend          | [68d85dd28f](https://linux-hardware.org/?probe=68d85dd28f) | Apr 30, 2023 |
| ASRock        | B550M Steel Legend          | [5166f820a6](https://linux-hardware.org/?probe=5166f820a6) | Apr 30, 2023 |
| ASRock        | 960GM-GS3 FX                | [392492c032](https://linux-hardware.org/?probe=392492c032) | Apr 30, 2023 |
| Medion        | H81H3-EM2                   | [c85a3da4ab](https://linux-hardware.org/?probe=c85a3da4ab) | Apr 30, 2023 |
| Gigabyte      | TRX40 AORUS XTREME          | [a88277b7f9](https://linux-hardware.org/?probe=a88277b7f9) | Apr 30, 2023 |
| ASRock        | H110M-DGS R3.0              | [88e7444fa5](https://linux-hardware.org/?probe=88e7444fa5) | Apr 30, 2023 |
| ASRock        | H110M-DGS R3.0              | [763e7fa1b6](https://linux-hardware.org/?probe=763e7fa1b6) | Apr 30, 2023 |
| ASRock        | B450M Steel Legend          | [fed083feba](https://linux-hardware.org/?probe=fed083feba) | Apr 30, 2023 |
| Dell          | 00V62H A00                  | [86cb104ceb](https://linux-hardware.org/?probe=86cb104ceb) | Apr 29, 2023 |
| ASUSTek       | PRIME X470-PRO              | [244cfe88a4](https://linux-hardware.org/?probe=244cfe88a4) | Apr 29, 2023 |
| ASRock        | N68C-S UCC                  | [13628f3559](https://linux-hardware.org/?probe=13628f3559) | Apr 29, 2023 |
| ASUSTek       | H110M-D                     | [81cff8a578](https://linux-hardware.org/?probe=81cff8a578) | Apr 29, 2023 |
| Gigabyte      | Z790 UD                     | [536a24a0e3](https://linux-hardware.org/?probe=536a24a0e3) | Apr 29, 2023 |
| ASRock        | N68C-S UCC                  | [f7f4643b8f](https://linux-hardware.org/?probe=f7f4643b8f) | Apr 29, 2023 |
| Gigabyte      | H310M H x.x                 | [6b44ad5061](https://linux-hardware.org/?probe=6b44ad5061) | Apr 29, 2023 |
| Gigabyte      | H310M H x.x                 | [ce73a703b6](https://linux-hardware.org/?probe=ce73a703b6) | Apr 29, 2023 |
| YANYU         | EPIC-N56_I522E Ver          | [4798ab5c06](https://linux-hardware.org/?probe=4798ab5c06) | Apr 29, 2023 |
| ASUSTek       | PRIME B450M-K               | [3592ce514a](https://linux-hardware.org/?probe=3592ce514a) | Apr 29, 2023 |
| Gigabyte      | G41MT-S2                    | [ba5c65f4e3](https://linux-hardware.org/?probe=ba5c65f4e3) | Apr 29, 2023 |
| Lenovo        | XXXX 3000 H210              | [96644846f5](https://linux-hardware.org/?probe=96644846f5) | Apr 29, 2023 |
| Dell          | 0T0MHW A02                  | [4f08178f96](https://linux-hardware.org/?probe=4f08178f96) | Apr 29, 2023 |
| ECS           | H81H3-M4                    | [67da6cebd3](https://linux-hardware.org/?probe=67da6cebd3) | Apr 29, 2023 |
| Gigabyte      | GA-78LMT-S2                 | [16b28befee](https://linux-hardware.org/?probe=16b28befee) | Apr 28, 2023 |
| Dell          | 0773VG A02                  | [bd3dba564e](https://linux-hardware.org/?probe=bd3dba564e) | Apr 28, 2023 |
| Dell          | 0773VG A02                  | [cab1aa59e0](https://linux-hardware.org/?probe=cab1aa59e0) | Apr 28, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [e0367e684f](https://linux-hardware.org/?probe=e0367e684f) | Apr 28, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [fed0a1a719](https://linux-hardware.org/?probe=fed0a1a719) | Apr 28, 2023 |
| ASUSTek       | Z87-PLUS                    | [7477be45f8](https://linux-hardware.org/?probe=7477be45f8) | Apr 28, 2023 |
| ASUSTek       | PRIME X370-PRO              | [ddb48a2def](https://linux-hardware.org/?probe=ddb48a2def) | Apr 28, 2023 |
| Lenovo        | 1048 SDK0Q40104 WIN 3915... | [43942fab0f](https://linux-hardware.org/?probe=43942fab0f) | Apr 28, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [a6eba14ab4](https://linux-hardware.org/?probe=a6eba14ab4) | Apr 28, 2023 |
| Dell          | 0WMJ54 A01                  | [01c8d89ab9](https://linux-hardware.org/?probe=01c8d89ab9) | Apr 28, 2023 |
| Lenovo        | Dory CRB                    | [f8aee85cd4](https://linux-hardware.org/?probe=f8aee85cd4) | Apr 28, 2023 |
| MSI           | H310M PRO-M2 PLUS           | [815dd8e866](https://linux-hardware.org/?probe=815dd8e866) | Apr 28, 2023 |
| ASUSTek       | P8H67-M PRO                 | [589810ee4b](https://linux-hardware.org/?probe=589810ee4b) | Apr 28, 2023 |
| Gigabyte      | Z490 AORUS ULTRA            | [96371860f5](https://linux-hardware.org/?probe=96371860f5) | Apr 28, 2023 |
| HP            | 21D0                        | [a26451e82c](https://linux-hardware.org/?probe=a26451e82c) | Apr 28, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [d138bfdf52](https://linux-hardware.org/?probe=d138bfdf52) | Apr 28, 2023 |
| ASRock        | A75M-HVS                    | [528362dfca](https://linux-hardware.org/?probe=528362dfca) | Apr 28, 2023 |
| Lenovo        | Dory CRB                    | [f4d7a6ed92](https://linux-hardware.org/?probe=f4d7a6ed92) | Apr 28, 2023 |
| Unknown       | RS780-SB700                 | [94f2408a63](https://linux-hardware.org/?probe=94f2408a63) | Apr 28, 2023 |
| Unknown       | RS780-SB700                 | [76c36882d9](https://linux-hardware.org/?probe=76c36882d9) | Apr 28, 2023 |
| Dell          | 0WMJ54 A01                  | [3d73e4cd7e](https://linux-hardware.org/?probe=3d73e4cd7e) | Apr 27, 2023 |
| Intel         | DH87RL AAG74240-403         | [54b1c509f2](https://linux-hardware.org/?probe=54b1c509f2) | Apr 27, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [49033dd76c](https://linux-hardware.org/?probe=49033dd76c) | Apr 27, 2023 |
| MSI           | X99A GAMING 9 ACK           | [3d79f67248](https://linux-hardware.org/?probe=3d79f67248) | Apr 27, 2023 |
| Dell          | 0HHV7N A00                  | [33517b7bfe](https://linux-hardware.org/?probe=33517b7bfe) | Apr 27, 2023 |
| ASUSTek       | CROSSBLADE RANGER           | [641d7d0398](https://linux-hardware.org/?probe=641d7d0398) | Apr 27, 2023 |
| Lenovo        | ThinkCentre M71e 3129B8G    | [2b6c3d498a](https://linux-hardware.org/?probe=2b6c3d498a) | Apr 27, 2023 |
| Gigabyte      | Z97P-D3                     | [40b51d3cae](https://linux-hardware.org/?probe=40b51d3cae) | Apr 27, 2023 |
| HP            | 18E7                        | [c6a760cb50](https://linux-hardware.org/?probe=c6a760cb50) | Apr 27, 2023 |
| ASUSTek       | H110M-A                     | [1fa553ab02](https://linux-hardware.org/?probe=1fa553ab02) | Apr 27, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [3e8fe7fed4](https://linux-hardware.org/?probe=3e8fe7fed4) | Apr 27, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [9211d42ee3](https://linux-hardware.org/?probe=9211d42ee3) | Apr 27, 2023 |
| HP            | 3047h                       | [3e6dada8a9](https://linux-hardware.org/?probe=3e6dada8a9) | Apr 26, 2023 |
| ECS           | G41T-R3                     | [fcbdd2737a](https://linux-hardware.org/?probe=fcbdd2737a) | Apr 26, 2023 |
| ASRock        | H61M-VG4                    | [a8e7de2e0b](https://linux-hardware.org/?probe=a8e7de2e0b) | Apr 26, 2023 |
| MSI           | MAG B550M MORTAR            | [f91ac46cfd](https://linux-hardware.org/?probe=f91ac46cfd) | Apr 26, 2023 |
| HP            | 1825                        | [5a26051aec](https://linux-hardware.org/?probe=5a26051aec) | Apr 26, 2023 |
| Gigabyte      | Z370M D3H-CF                | [ada8ff75dd](https://linux-hardware.org/?probe=ada8ff75dd) | Apr 26, 2023 |
| MSI           | B450-A PRO MAX              | [2d7c2dd8f9](https://linux-hardware.org/?probe=2d7c2dd8f9) | Apr 26, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [45c453eb4e](https://linux-hardware.org/?probe=45c453eb4e) | Apr 26, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [b79a40ebdc](https://linux-hardware.org/?probe=b79a40ebdc) | Apr 26, 2023 |
| ASUSTek       | X99-A                       | [6788eea8d2](https://linux-hardware.org/?probe=6788eea8d2) | Apr 26, 2023 |
| MSI           | PRO Z690-A WIFI             | [23c9be7614](https://linux-hardware.org/?probe=23c9be7614) | Apr 26, 2023 |
| Pegatron      | IPXSB-H61                   | [2b0ee4d542](https://linux-hardware.org/?probe=2b0ee4d542) | Apr 26, 2023 |
| ASUSTek       | PRIME B450M-A               | [d8c1be05af](https://linux-hardware.org/?probe=d8c1be05af) | Apr 25, 2023 |
| ASUSTek       | PRIME X570-P                | [290f3ebad7](https://linux-hardware.org/?probe=290f3ebad7) | Apr 25, 2023 |
| Acer          | Aspire X3995                | [877c9deb7a](https://linux-hardware.org/?probe=877c9deb7a) | Apr 25, 2023 |
| Biostar       | A68N-5600E                  | [ccaeaae27b](https://linux-hardware.org/?probe=ccaeaae27b) | Apr 25, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [4668a2409b](https://linux-hardware.org/?probe=4668a2409b) | Apr 25, 2023 |
| Acer          | Predator G3-605             | [37cd92a7f0](https://linux-hardware.org/?probe=37cd92a7f0) | Apr 25, 2023 |
| Acer          | Predator G3-605             | [0b966e7b88](https://linux-hardware.org/?probe=0b966e7b88) | Apr 25, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [7b091628e5](https://linux-hardware.org/?probe=7b091628e5) | Apr 25, 2023 |
| Gigabyte      | Z270X-UD3-CF                | [06fbe4d0b6](https://linux-hardware.org/?probe=06fbe4d0b6) | Apr 25, 2023 |
| ASUSTek       | PRIME Z790-P                | [c7fdbbb95b](https://linux-hardware.org/?probe=c7fdbbb95b) | Apr 25, 2023 |
| ASUSTek       | PRIME Z790-P                | [363bb28966](https://linux-hardware.org/?probe=363bb28966) | Apr 25, 2023 |
| OEM           | HN B85 Ver:1.4              | [1da5934b27](https://linux-hardware.org/?probe=1da5934b27) | Apr 25, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [1a58c88206](https://linux-hardware.org/?probe=1a58c88206) | Apr 25, 2023 |
| ASUSTek       | M4A78LT-M                   | [11f1e291a7](https://linux-hardware.org/?probe=11f1e291a7) | Apr 25, 2023 |
| ASUSTek       | M3A                         | [c16000b1e4](https://linux-hardware.org/?probe=c16000b1e4) | Apr 25, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [342918aa38](https://linux-hardware.org/?probe=342918aa38) | Apr 24, 2023 |
| Lenovo        | 313A NOK                    | [34a521ebad](https://linux-hardware.org/?probe=34a521ebad) | Apr 24, 2023 |
| MSI           | H110M ECO                   | [bfa2b17374](https://linux-hardware.org/?probe=bfa2b17374) | Apr 24, 2023 |
| Dell          | 0VTJVC A00                  | [da7d66917d](https://linux-hardware.org/?probe=da7d66917d) | Apr 24, 2023 |
| ASUSTek       | STRIX B250I GAMING          | [beabf00341](https://linux-hardware.org/?probe=beabf00341) | Apr 24, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [e18fd8d449](https://linux-hardware.org/?probe=e18fd8d449) | Apr 24, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | [ed8414c493](https://linux-hardware.org/?probe=ed8414c493) | Apr 24, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [267c5b8075](https://linux-hardware.org/?probe=267c5b8075) | Apr 24, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | [695220be38](https://linux-hardware.org/?probe=695220be38) | Apr 24, 2023 |
| Lenovo        | 32E9 SDK0T76463 WIN 3422... | [9f49daf25a](https://linux-hardware.org/?probe=9f49daf25a) | Apr 24, 2023 |
| Lenovo        | 32E9 SDK0T76463 WIN 3422... | [cc7a31d3d6](https://linux-hardware.org/?probe=cc7a31d3d6) | Apr 24, 2023 |
| ASUSTek       | PRIME X370-PRO              | [eb716c53fa](https://linux-hardware.org/?probe=eb716c53fa) | Apr 24, 2023 |
| Gigabyte      | G41MT-S2                    | [de1981f9e6](https://linux-hardware.org/?probe=de1981f9e6) | Apr 24, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [39fd6ad31f](https://linux-hardware.org/?probe=39fd6ad31f) | Apr 24, 2023 |
| ASUSTek       | P5G41T-M LX                 | [68d1859c93](https://linux-hardware.org/?probe=68d1859c93) | Apr 23, 2023 |
| Gigabyte      | Z97P-D3                     | [5da4c37f75](https://linux-hardware.org/?probe=5da4c37f75) | Apr 23, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [e653a5dd45](https://linux-hardware.org/?probe=e653a5dd45) | Apr 23, 2023 |
| Lenovo        | 36C5 SDK0K17763 WIN 1801... | [95e77b87f5](https://linux-hardware.org/?probe=95e77b87f5) | Apr 23, 2023 |
| ASUSTek       | STRIX B250I GAMING          | [0e96ee4471](https://linux-hardware.org/?probe=0e96ee4471) | Apr 23, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [793e094165](https://linux-hardware.org/?probe=793e094165) | Apr 23, 2023 |
| Gigabyte      | TRX40 AORUS XTREME          | [eac9934073](https://linux-hardware.org/?probe=eac9934073) | Apr 23, 2023 |
| ASUSTek       | Maximus VII FORMULA         | [0d45b24479](https://linux-hardware.org/?probe=0d45b24479) | Apr 23, 2023 |
| Gigabyte      | Z97M-DS3H                   | [652e029529](https://linux-hardware.org/?probe=652e029529) | Apr 23, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [b342cd8fe0](https://linux-hardware.org/?probe=b342cd8fe0) | Apr 23, 2023 |
| Intel         | DH61BE AAG14062-206         | [c1817da6ab](https://linux-hardware.org/?probe=c1817da6ab) | Apr 23, 2023 |
| Gigabyte      | 970A-DS3P                   | [4a55a10fd0](https://linux-hardware.org/?probe=4a55a10fd0) | Apr 23, 2023 |
| ASUSTek       | PRIME Z390-A                | [3fc4048a96](https://linux-hardware.org/?probe=3fc4048a96) | Apr 23, 2023 |
| ASUSTek       | Z87-PRO                     | [08ebdd71ab](https://linux-hardware.org/?probe=08ebdd71ab) | Apr 23, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | [1c85c89b5d](https://linux-hardware.org/?probe=1c85c89b5d) | Apr 22, 2023 |
| System76      | Thelio thelio-r1            | [d48efc62c4](https://linux-hardware.org/?probe=d48efc62c4) | Apr 22, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | [1404fc66cf](https://linux-hardware.org/?probe=1404fc66cf) | Apr 22, 2023 |
| Gigabyte      | Z390 UD                     | [c9e17ad011](https://linux-hardware.org/?probe=c9e17ad011) | Apr 22, 2023 |
| Intel         | H81                         | [fbc2766f35](https://linux-hardware.org/?probe=fbc2766f35) | Apr 22, 2023 |
| Gigabyte      | Z790 UD                     | [8536a23081](https://linux-hardware.org/?probe=8536a23081) | Apr 22, 2023 |
| Gigabyte      | 990FXA-UD3                  | [bab80153bf](https://linux-hardware.org/?probe=bab80153bf) | Apr 22, 2023 |
| MSI           | Z77A-G41                    | [9cd2294229](https://linux-hardware.org/?probe=9cd2294229) | Apr 22, 2023 |
| ASUSTek       | PRIME X570-P                | [f23eeda727](https://linux-hardware.org/?probe=f23eeda727) | Apr 22, 2023 |
| MSI           | B550-A PRO                  | [06bc639254](https://linux-hardware.org/?probe=06bc639254) | Apr 22, 2023 |
| Gigabyte      | TRX40 AORUS XTREME          | [d4d3e7f8d6](https://linux-hardware.org/?probe=d4d3e7f8d6) | Apr 21, 2023 |
| MSI           | IONA                        | [3820fb6576](https://linux-hardware.org/?probe=3820fb6576) | Apr 21, 2023 |
| Shuttle       | FG45 V10                    | [b5a9d7b1e4](https://linux-hardware.org/?probe=b5a9d7b1e4) | Apr 21, 2023 |
| ASRock        | H81M-HDS R2.0               | [eaf8476afd](https://linux-hardware.org/?probe=eaf8476afd) | Apr 21, 2023 |
| Unknown       | Unknown                     | [be207ea29f](https://linux-hardware.org/?probe=be207ea29f) | Apr 21, 2023 |
| HP            | 1825                        | [e586a2657b](https://linux-hardware.org/?probe=e586a2657b) | Apr 21, 2023 |
| HP            | 1494                        | [625373a1de](https://linux-hardware.org/?probe=625373a1de) | Apr 21, 2023 |
| ASUSTek       | PRIME B360M-A               | [61d7104ec4](https://linux-hardware.org/?probe=61d7104ec4) | Apr 21, 2023 |
| Dell          | 0RY206                      | [8290af518f](https://linux-hardware.org/?probe=8290af518f) | Apr 21, 2023 |
| ASUSTek       | PRIME TRX40-PRO S           | [b2ac72f8d9](https://linux-hardware.org/?probe=b2ac72f8d9) | Apr 20, 2023 |
| HP            | ProLiant MicroServer        | [ea76b8632f](https://linux-hardware.org/?probe=ea76b8632f) | Apr 20, 2023 |
| ASUSTek       | PRIME TRX40-PRO S           | [4748a2ce89](https://linux-hardware.org/?probe=4748a2ce89) | Apr 20, 2023 |
| ASRock        | G31M-S                      | [7c2bfcaeca](https://linux-hardware.org/?probe=7c2bfcaeca) | Apr 20, 2023 |
| Acer          | Aspire M3970                | [d43372f3fd](https://linux-hardware.org/?probe=d43372f3fd) | Apr 20, 2023 |
| Gigabyte      | Z97M-DS3H                   | [904089ce14](https://linux-hardware.org/?probe=904089ce14) | Apr 20, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [42ca23ca64](https://linux-hardware.org/?probe=42ca23ca64) | Apr 20, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [e315ba7088](https://linux-hardware.org/?probe=e315ba7088) | Apr 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [f5da23bee0](https://linux-hardware.org/?probe=f5da23bee0) | Apr 20, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [e367a9a4ab](https://linux-hardware.org/?probe=e367a9a4ab) | Apr 20, 2023 |
| Fujitsu       | D3498-A1 S26361-D3498-A1    | [f20338e169](https://linux-hardware.org/?probe=f20338e169) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | [2c6da4e91f](https://linux-hardware.org/?probe=2c6da4e91f) | Apr 20, 2023 |
| ASUSTek       | H87M-PLUS                   | [472922fafd](https://linux-hardware.org/?probe=472922fafd) | Apr 20, 2023 |
| Intel         | DP67BA AAG10219-303         | [a1b9ea4fd9](https://linux-hardware.org/?probe=a1b9ea4fd9) | Apr 20, 2023 |
| Intel         | DX58SO2 AAG10925-207        | [4e31c5af6b](https://linux-hardware.org/?probe=4e31c5af6b) | Apr 20, 2023 |
| Intel         | DP67BA AAG10219-303         | [27a629fd15](https://linux-hardware.org/?probe=27a629fd15) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | [f3a680d9bc](https://linux-hardware.org/?probe=f3a680d9bc) | Apr 20, 2023 |
| Fujitsu       | D3348-A1 S26361-D3348-A1    | [96d5a26185](https://linux-hardware.org/?probe=96d5a26185) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | [b6306c2e97](https://linux-hardware.org/?probe=b6306c2e97) | Apr 20, 2023 |
| Fujitsu       | D3517-A1 S26361-D3517-A1    | [fbedbcb213](https://linux-hardware.org/?probe=fbedbcb213) | Apr 20, 2023 |
| ASUSTek       | X99-S                       | [6e77ac0ec9](https://linux-hardware.org/?probe=6e77ac0ec9) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | [c1b2a75484](https://linux-hardware.org/?probe=c1b2a75484) | Apr 20, 2023 |
| Fujitsu       | D3617-A1 S26361-D3617-A1    | [756eccb961](https://linux-hardware.org/?probe=756eccb961) | Apr 20, 2023 |
| Gigabyte      | H97-HD3                     | [ef04208d0f](https://linux-hardware.org/?probe=ef04208d0f) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | [c419c9200f](https://linux-hardware.org/?probe=c419c9200f) | Apr 20, 2023 |
| ASUSTek       | X99-S                       | [1be8dc273c](https://linux-hardware.org/?probe=1be8dc273c) | Apr 20, 2023 |
| ASUSTek       | PRIME Z490M-PLUS            | [244222ae5c](https://linux-hardware.org/?probe=244222ae5c) | Apr 20, 2023 |
| ASUSTek       | PRIME H270M-PLUS            | [f77fe53c69](https://linux-hardware.org/?probe=f77fe53c69) | Apr 20, 2023 |
| Dell          | 08NPPY A00                  | [7d49aa5207](https://linux-hardware.org/?probe=7d49aa5207) | Apr 20, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | [d53ce13aa3](https://linux-hardware.org/?probe=d53ce13aa3) | Apr 20, 2023 |
| ASRock        | B550M Pro4                  | [ec13e17577](https://linux-hardware.org/?probe=ec13e17577) | Apr 20, 2023 |
| ASUSTek       | PRIME Z390-P                | [9fde2b21fc](https://linux-hardware.org/?probe=9fde2b21fc) | Apr 20, 2023 |
| ASUSTek       | G35CG                       | [ddc7ba8ccb](https://linux-hardware.org/?probe=ddc7ba8ccb) | Apr 20, 2023 |
| Fujitsu       | D3348-A2 S26361-D3348-A2    | [3dbd4f731c](https://linux-hardware.org/?probe=3dbd4f731c) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [d46e9b11d5](https://linux-hardware.org/?probe=d46e9b11d5) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [afbf28c15a](https://linux-hardware.org/?probe=afbf28c15a) | Apr 20, 2023 |
| ASUSTek       | PRIME Z370-A II             | [f185782be2](https://linux-hardware.org/?probe=f185782be2) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [731671f1b8](https://linux-hardware.org/?probe=731671f1b8) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [463c62da83](https://linux-hardware.org/?probe=463c62da83) | Apr 20, 2023 |
| Fujitsu       | D3517-A1 S26361-D3517-A1    | [0356125777](https://linux-hardware.org/?probe=0356125777) | Apr 20, 2023 |
| ASUSTek       | PRIME Z490M-PLUS            | [0a45e9e9af](https://linux-hardware.org/?probe=0a45e9e9af) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [ccf2e2bbc3](https://linux-hardware.org/?probe=ccf2e2bbc3) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | [3171099090](https://linux-hardware.org/?probe=3171099090) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [032f3a72c6](https://linux-hardware.org/?probe=032f3a72c6) | Apr 20, 2023 |
| Intel         | DH87MC AAG74242-401         | [df7041b726](https://linux-hardware.org/?probe=df7041b726) | Apr 20, 2023 |
| ASUSTek       | P9X79 WS                    | [04e9cd2455](https://linux-hardware.org/?probe=04e9cd2455) | Apr 20, 2023 |
| Intel         | DP55WB AAE64798-207         | [0dd9e12f5a](https://linux-hardware.org/?probe=0dd9e12f5a) | Apr 20, 2023 |
| HP            | 870B                        | [ad6a3cc4d0](https://linux-hardware.org/?probe=ad6a3cc4d0) | Apr 20, 2023 |
| ASRock        | B760M Steel Legend WiFi     | [9e668ff813](https://linux-hardware.org/?probe=9e668ff813) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | [5dc0cb1f28](https://linux-hardware.org/?probe=5dc0cb1f28) | Apr 20, 2023 |
| Medion        | GA-Z170X-Gaming 7           | [706cfb4c50](https://linux-hardware.org/?probe=706cfb4c50) | Apr 20, 2023 |
| Gigabyte      | H97-HD3                     | [b3b27e0fcf](https://linux-hardware.org/?probe=b3b27e0fcf) | Apr 20, 2023 |
| ASUSTek       | PRIME Z370-A II             | [bdbd8d06e2](https://linux-hardware.org/?probe=bdbd8d06e2) | Apr 20, 2023 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | [ff10999142](https://linux-hardware.org/?probe=ff10999142) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | [11da8c5d96](https://linux-hardware.org/?probe=11da8c5d96) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [128d16cf7f](https://linux-hardware.org/?probe=128d16cf7f) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | [c2de2809a0](https://linux-hardware.org/?probe=c2de2809a0) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | [c3a3c03c3f](https://linux-hardware.org/?probe=c3a3c03c3f) | Apr 20, 2023 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | [1ae9258a0d](https://linux-hardware.org/?probe=1ae9258a0d) | Apr 20, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | [ab89260502](https://linux-hardware.org/?probe=ab89260502) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [3f99aeec69](https://linux-hardware.org/?probe=3f99aeec69) | Apr 20, 2023 |
| HP            | 870B                        | [50f654b2a0](https://linux-hardware.org/?probe=50f654b2a0) | Apr 20, 2023 |
| Fujitsu       | D3348-A1 S26361-D3348-A1    | [9949a0748f](https://linux-hardware.org/?probe=9949a0748f) | Apr 20, 2023 |
| ASUSTek       | PRIME Z370-A II             | [e3cfbf7435](https://linux-hardware.org/?probe=e3cfbf7435) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [9817f90648](https://linux-hardware.org/?probe=9817f90648) | Apr 20, 2023 |
| ASUSTek       | G35CG                       | [cf4854d704](https://linux-hardware.org/?probe=cf4854d704) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | [296676f929](https://linux-hardware.org/?probe=296676f929) | Apr 20, 2023 |
| ASUSTek       | PRIME Z370-A II             | [2eeebec1ec](https://linux-hardware.org/?probe=2eeebec1ec) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | [68ac671aab](https://linux-hardware.org/?probe=68ac671aab) | Apr 20, 2023 |
| ASUSTek       | PRIME X370-PRO              | [a069d32b86](https://linux-hardware.org/?probe=a069d32b86) | Apr 20, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [1b1a3da7b2](https://linux-hardware.org/?probe=1b1a3da7b2) | Apr 20, 2023 |
| ASUSTek       | X99-S                       | [2a1fcefe29](https://linux-hardware.org/?probe=2a1fcefe29) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | [5c54edc96d](https://linux-hardware.org/?probe=5c54edc96d) | Apr 20, 2023 |
| ASRock        | B760M Steel Legend WiFi     | [563e45a22a](https://linux-hardware.org/?probe=563e45a22a) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | [0000720fb6](https://linux-hardware.org/?probe=0000720fb6) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [fdda3d6276](https://linux-hardware.org/?probe=fdda3d6276) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [ee95d83f31](https://linux-hardware.org/?probe=ee95d83f31) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | [1e49dc0f67](https://linux-hardware.org/?probe=1e49dc0f67) | Apr 20, 2023 |
| Apple         | Mac-F221BEC8                | [798a408c25](https://linux-hardware.org/?probe=798a408c25) | Apr 20, 2023 |
| ASRock        | A320M-HDV                   | [114bd5a129](https://linux-hardware.org/?probe=114bd5a129) | Apr 19, 2023 |
| Acer          | Veriton X2632G V:1.0        | [0fa4554c3c](https://linux-hardware.org/?probe=0fa4554c3c) | Apr 19, 2023 |
| ASUSTek       | P5G41T-M LX                 | [b830d8001e](https://linux-hardware.org/?probe=b830d8001e) | Apr 19, 2023 |
| Gigabyte      | Z97-HD3                     | [8b560b455e](https://linux-hardware.org/?probe=8b560b455e) | Apr 19, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [882d6f625d](https://linux-hardware.org/?probe=882d6f625d) | Apr 19, 2023 |
| Dell          | 040DDP A01                  | [bb212aa105](https://linux-hardware.org/?probe=bb212aa105) | Apr 19, 2023 |
| MSI           | PRO Z690-A WIFI             | [26c96a2c4b](https://linux-hardware.org/?probe=26c96a2c4b) | Apr 19, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [2822b1a8c3](https://linux-hardware.org/?probe=2822b1a8c3) | Apr 19, 2023 |
| ASUSTek       | Z87-PRO                     | [7981ad8440](https://linux-hardware.org/?probe=7981ad8440) | Apr 19, 2023 |
| ASUSTek       | PRIME A320M-K               | [8f16bcad94](https://linux-hardware.org/?probe=8f16bcad94) | Apr 19, 2023 |
| ASUSTek       | PRIME A320M-K               | [848607e7f1](https://linux-hardware.org/?probe=848607e7f1) | Apr 19, 2023 |
| Dell          | 040DDP A01                  | [2b839be032](https://linux-hardware.org/?probe=2b839be032) | Apr 19, 2023 |
| ASUSTek       | PRIME B250M-PLUS/BR         | [c0a82bb35a](https://linux-hardware.org/?probe=c0a82bb35a) | Apr 19, 2023 |
| Intel         | DH61AG AAG23736-504         | [9a853b9c86](https://linux-hardware.org/?probe=9a853b9c86) | Apr 19, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [a775ede9a0](https://linux-hardware.org/?probe=a775ede9a0) | Apr 18, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [da85d2406d](https://linux-hardware.org/?probe=da85d2406d) | Apr 18, 2023 |
| ASUSTek       | PRIME B250M-PLUS/BR         | [8bb9dc2419](https://linux-hardware.org/?probe=8bb9dc2419) | Apr 18, 2023 |
| HP            | 1825                        | [5c637a9ef6](https://linux-hardware.org/?probe=5c637a9ef6) | Apr 18, 2023 |
| Lenovo        | 3714 SDK0J40709 WIN 3259... | [ae7ea68877](https://linux-hardware.org/?probe=ae7ea68877) | Apr 18, 2023 |
| Medion        | BTDD-LT                     | [b26cb60a3f](https://linux-hardware.org/?probe=b26cb60a3f) | Apr 18, 2023 |
| ASRock        | B450M Pro4                  | [eb66896af3](https://linux-hardware.org/?probe=eb66896af3) | Apr 18, 2023 |
| MSI           | PRO B660-A DDR4             | [b274726abd](https://linux-hardware.org/?probe=b274726abd) | Apr 17, 2023 |
| MSI           | Z97 GAMING 5                | [152e32b151](https://linux-hardware.org/?probe=152e32b151) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [79225bdfaf](https://linux-hardware.org/?probe=79225bdfaf) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [4d802fb610](https://linux-hardware.org/?probe=4d802fb610) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [2b749e898e](https://linux-hardware.org/?probe=2b749e898e) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [702377976d](https://linux-hardware.org/?probe=702377976d) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [32f7392dce](https://linux-hardware.org/?probe=32f7392dce) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [b7f40b0d8e](https://linux-hardware.org/?probe=b7f40b0d8e) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [9602690aa2](https://linux-hardware.org/?probe=9602690aa2) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [bbf0a5108a](https://linux-hardware.org/?probe=bbf0a5108a) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [000ec3362e](https://linux-hardware.org/?probe=000ec3362e) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [7d67899067](https://linux-hardware.org/?probe=7d67899067) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [256a2110b0](https://linux-hardware.org/?probe=256a2110b0) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [9f69cc7127](https://linux-hardware.org/?probe=9f69cc7127) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [997c25143e](https://linux-hardware.org/?probe=997c25143e) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [71822fdac9](https://linux-hardware.org/?probe=71822fdac9) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [b3f9111b79](https://linux-hardware.org/?probe=b3f9111b79) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | [df314b2a9c](https://linux-hardware.org/?probe=df314b2a9c) | Apr 17, 2023 |
| Dell          | 0K83V0 A00                  | [9e0514e439](https://linux-hardware.org/?probe=9e0514e439) | Apr 17, 2023 |
| Dell          | 0J4NFV A01                  | [a6b3ac3ff2](https://linux-hardware.org/?probe=a6b3ac3ff2) | Apr 17, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [5109f5c8d9](https://linux-hardware.org/?probe=5109f5c8d9) | Apr 17, 2023 |
| Fujitsu       | FujitsuTP7000 -1            | [3154b04b37](https://linux-hardware.org/?probe=3154b04b37) | Apr 17, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [dbd2cfbd81](https://linux-hardware.org/?probe=dbd2cfbd81) | Apr 17, 2023 |
| Gigabyte      | GA-IMB410TN                 | [44293ba6b9](https://linux-hardware.org/?probe=44293ba6b9) | Apr 17, 2023 |
| ASUSTek       | EX-B560M-V5                 | [243b7b3722](https://linux-hardware.org/?probe=243b7b3722) | Apr 17, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E EXTR... | [45722c96bb](https://linux-hardware.org/?probe=45722c96bb) | Apr 17, 2023 |
| Dell          | 0F896N A03                  | [4ec01d373e](https://linux-hardware.org/?probe=4ec01d373e) | Apr 17, 2023 |
| ASRock        | B450M Pro4                  | [ddbe51a022](https://linux-hardware.org/?probe=ddbe51a022) | Apr 17, 2023 |
| HP            | 8055                        | [f9b8b05db5](https://linux-hardware.org/?probe=f9b8b05db5) | Apr 17, 2023 |
| HP            | 8055                        | [462446d664](https://linux-hardware.org/?probe=462446d664) | Apr 17, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [7230f64c9b](https://linux-hardware.org/?probe=7230f64c9b) | Apr 16, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [a7f312ea0a](https://linux-hardware.org/?probe=a7f312ea0a) | Apr 16, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [f1afe43806](https://linux-hardware.org/?probe=f1afe43806) | Apr 16, 2023 |
| MSI           | B560M PRO-VDH WIFI          | [fd0b3fe549](https://linux-hardware.org/?probe=fd0b3fe549) | Apr 16, 2023 |
| Dell          | 0TP412                      | [7491d6d66d](https://linux-hardware.org/?probe=7491d6d66d) | Apr 16, 2023 |
| Foxconn       | A7DA 3 series               | [a8f557c1c3](https://linux-hardware.org/?probe=a8f557c1c3) | Apr 16, 2023 |
| Lenovo        | 317E SDK0J40700 WIN 3258... | [e8b30a69f9](https://linux-hardware.org/?probe=e8b30a69f9) | Apr 16, 2023 |
| Foxconn       | A7DA 3 series               | [4f7648a3d0](https://linux-hardware.org/?probe=4f7648a3d0) | Apr 16, 2023 |
| Dell          | 0TP412                      | [c5f0ba736e](https://linux-hardware.org/?probe=c5f0ba736e) | Apr 16, 2023 |
| HP            | 18E4                        | [bc45bcdf89](https://linux-hardware.org/?probe=bc45bcdf89) | Apr 16, 2023 |
| Dell          | 0MR5MV A00                  | [ed13b58a51](https://linux-hardware.org/?probe=ed13b58a51) | Apr 16, 2023 |
| HP            | 1850                        | [9ba17e1d9c](https://linux-hardware.org/?probe=9ba17e1d9c) | Apr 16, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [6d206f88cb](https://linux-hardware.org/?probe=6d206f88cb) | Apr 16, 2023 |
| ASRock        | H87 Pro4                    | [e85b3e34b0](https://linux-hardware.org/?probe=e85b3e34b0) | Apr 16, 2023 |
| Lenovo        | ThinkCentre M71z 1782W14    | [c4434a61df](https://linux-hardware.org/?probe=c4434a61df) | Apr 15, 2023 |
| HP            | 83E2                        | [af01123687](https://linux-hardware.org/?probe=af01123687) | Apr 15, 2023 |
| HP            | 83E2                        | [f5052291a4](https://linux-hardware.org/?probe=f5052291a4) | Apr 15, 2023 |
| ASUSTek       | ROG Rampage VI EXTREME      | [fb75806ceb](https://linux-hardware.org/?probe=fb75806ceb) | Apr 15, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [6d930e2f8a](https://linux-hardware.org/?probe=6d930e2f8a) | Apr 15, 2023 |
| ASRock        | A320M-HDV R4.0              | [2c7e1238eb](https://linux-hardware.org/?probe=2c7e1238eb) | Apr 15, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [9deba6cdac](https://linux-hardware.org/?probe=9deba6cdac) | Apr 15, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [7c8e58956e](https://linux-hardware.org/?probe=7c8e58956e) | Apr 15, 2023 |
| HP            | 1850                        | [d30cea781b](https://linux-hardware.org/?probe=d30cea781b) | Apr 15, 2023 |
| Dell          | 0D24M8 A01                  | [5244c86993](https://linux-hardware.org/?probe=5244c86993) | Apr 15, 2023 |
| Gigabyte      | AX370-Gaming K7 se3         | [5439790362](https://linux-hardware.org/?probe=5439790362) | Apr 15, 2023 |
| ASUSTek       | ET1612I                     | [f67ace875b](https://linux-hardware.org/?probe=f67ace875b) | Apr 14, 2023 |
| HP            | 2B4B                        | [9103ce1fce](https://linux-hardware.org/?probe=9103ce1fce) | Apr 14, 2023 |
| Acer          | Aspire M3970                | [0792e082e7](https://linux-hardware.org/?probe=0792e082e7) | Apr 14, 2023 |
| Gigabyte      | H97M-D3H                    | [e48eeac368](https://linux-hardware.org/?probe=e48eeac368) | Apr 14, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [87acc1eb9d](https://linux-hardware.org/?probe=87acc1eb9d) | Apr 14, 2023 |
| Gigabyte      | B560M DS3H V2               | [fe75c98b15](https://linux-hardware.org/?probe=fe75c98b15) | Apr 14, 2023 |
| Lenovo        | 3098 SDK0J40705 WIN         | [9ab9baf194](https://linux-hardware.org/?probe=9ab9baf194) | Apr 14, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [a1c457ea48](https://linux-hardware.org/?probe=a1c457ea48) | Apr 14, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [6cf54a6bf4](https://linux-hardware.org/?probe=6cf54a6bf4) | Apr 14, 2023 |
| MSI           | H310M PRO-M2 PLUS           | [30d6d32fc1](https://linux-hardware.org/?probe=30d6d32fc1) | Apr 13, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c3eb775c80](https://linux-hardware.org/?probe=c3eb775c80) | Apr 13, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [654728e9fe](https://linux-hardware.org/?probe=654728e9fe) | Apr 13, 2023 |
| Dell          | 00V62H A00                  | [0632bfe4d0](https://linux-hardware.org/?probe=0632bfe4d0) | Apr 13, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [c47d5d79fd](https://linux-hardware.org/?probe=c47d5d79fd) | Apr 13, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [89a7f8f7e7](https://linux-hardware.org/?probe=89a7f8f7e7) | Apr 13, 2023 |
| Gigabyte      | B460M DS3H V2               | [4e09a1cd3e](https://linux-hardware.org/?probe=4e09a1cd3e) | Apr 13, 2023 |
| MSI           | A520M-A PRO                 | [b5f4a1670f](https://linux-hardware.org/?probe=b5f4a1670f) | Apr 13, 2023 |
| ECS           | G41T-R3                     | [2c589a38f7](https://linux-hardware.org/?probe=2c589a38f7) | Apr 13, 2023 |
| MSI           | X370 GAMING PLUS            | [f63c87bf19](https://linux-hardware.org/?probe=f63c87bf19) | Apr 13, 2023 |
| Lenovo        | NO DPK                      | [4d84f3549a](https://linux-hardware.org/?probe=4d84f3549a) | Apr 13, 2023 |
| Intel         | DH67BL AAG10189-209         | [b8e206486d](https://linux-hardware.org/?probe=b8e206486d) | Apr 13, 2023 |
| HP            | 0B4Ch D                     | [a0247e45a6](https://linux-hardware.org/?probe=a0247e45a6) | Apr 13, 2023 |
| HP            | 0B4Ch D                     | [f205e700dc](https://linux-hardware.org/?probe=f205e700dc) | Apr 13, 2023 |
| HP            | 1495                        | [569a6f28f4](https://linux-hardware.org/?probe=569a6f28f4) | Apr 12, 2023 |
| ECS           | H61H2-MV                    | [5a3fbafb75](https://linux-hardware.org/?probe=5a3fbafb75) | Apr 12, 2023 |
| Dell          | 0XHGV1 A00                  | [6cbdeb350e](https://linux-hardware.org/?probe=6cbdeb350e) | Apr 12, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [4d3cf8103e](https://linux-hardware.org/?probe=4d3cf8103e) | Apr 12, 2023 |
| Intel         | D33217GKE G76540-203        | [c07a4d67ca](https://linux-hardware.org/?probe=c07a4d67ca) | Apr 12, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [378f217cd4](https://linux-hardware.org/?probe=378f217cd4) | Apr 12, 2023 |
| Gigabyte      | X79-UP4                     | [8f9b60caf3](https://linux-hardware.org/?probe=8f9b60caf3) | Apr 12, 2023 |
| ASRock        | H410D4-P1                   | [3f7d6e5bfb](https://linux-hardware.org/?probe=3f7d6e5bfb) | Apr 12, 2023 |
| Dell          | 042P49 A02                  | [b6d105b2b9](https://linux-hardware.org/?probe=b6d105b2b9) | Apr 12, 2023 |
| MiTAC         | PD10EHI                     | [13f79a1843](https://linux-hardware.org/?probe=13f79a1843) | Apr 12, 2023 |
| Win elemen... | M600                        | [4268d36ca4](https://linux-hardware.org/?probe=4268d36ca4) | Apr 12, 2023 |
| Gigabyte      | AX370-Gaming K7 se3         | [ef5cbba147](https://linux-hardware.org/?probe=ef5cbba147) | Apr 12, 2023 |
| Dell          | 0K83V0 A00                  | [3bc76fa8ab](https://linux-hardware.org/?probe=3bc76fa8ab) | Apr 12, 2023 |
| Gigabyte      | 990FXA-UD3                  | [30fdc58d69](https://linux-hardware.org/?probe=30fdc58d69) | Apr 12, 2023 |
| ASRock        | H61M-HVS                    | [1649a1f9b5](https://linux-hardware.org/?probe=1649a1f9b5) | Apr 12, 2023 |
| ASRock        | H61M-HVS                    | [497756c5ab](https://linux-hardware.org/?probe=497756c5ab) | Apr 12, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [46eba03bed](https://linux-hardware.org/?probe=46eba03bed) | Apr 12, 2023 |
| ASUSTek       | PRIME A320M-K               | [dc55b7997e](https://linux-hardware.org/?probe=dc55b7997e) | Apr 12, 2023 |
| ASUSTek       | PRIME A320M-K               | [b35d9a7487](https://linux-hardware.org/?probe=b35d9a7487) | Apr 12, 2023 |
| ASUSTek       | H110M-A                     | [2f7cf166f0](https://linux-hardware.org/?probe=2f7cf166f0) | Apr 11, 2023 |
| Acer          | H57M01                      | [c62231ca98](https://linux-hardware.org/?probe=c62231ca98) | Apr 11, 2023 |
| Gigabyte      | Z97M-DS3H                   | [b85f3476ed](https://linux-hardware.org/?probe=b85f3476ed) | Apr 11, 2023 |
| MSI           | A320M-A PRO MAX             | [d5e033eb2e](https://linux-hardware.org/?probe=d5e033eb2e) | Apr 11, 2023 |
| Gigabyte      | Z68P-DS3                    | [6026c92eaa](https://linux-hardware.org/?probe=6026c92eaa) | Apr 11, 2023 |
| ASUSTek       | H97I-PLUS                   | [8fdee327be](https://linux-hardware.org/?probe=8fdee327be) | Apr 11, 2023 |
| ASRock        | B85M-HDS R2.0               | [24bdbac13a](https://linux-hardware.org/?probe=24bdbac13a) | Apr 11, 2023 |
| ASUSTek       | PRIME Z690-A                | [b434d4a0b5](https://linux-hardware.org/?probe=b434d4a0b5) | Apr 11, 2023 |
| Dell          | 0GXM1W A01                  | [eafb6edf1e](https://linux-hardware.org/?probe=eafb6edf1e) | Apr 10, 2023 |
| Dell          | 0GXM1W A01                  | [cbd05b393a](https://linux-hardware.org/?probe=cbd05b393a) | Apr 10, 2023 |
| Dell          | 0F6X5P A00                  | [ab53417291](https://linux-hardware.org/?probe=ab53417291) | Apr 10, 2023 |
| ASRock        | 960GC-GS FX                 | [e3eee10ad1](https://linux-hardware.org/?probe=e3eee10ad1) | Apr 10, 2023 |
| Gigabyte      | B450M H                     | [7806838777](https://linux-hardware.org/?probe=7806838777) | Apr 09, 2023 |
| MSI           | MS-B0A21                    | [93db7f66f1](https://linux-hardware.org/?probe=93db7f66f1) | Apr 08, 2023 |
| Dell          | 0WR7PY A00                  | [2719755017](https://linux-hardware.org/?probe=2719755017) | Apr 08, 2023 |
| Gigabyte      | Z690 UD DDR4                | [6f2fcf320a](https://linux-hardware.org/?probe=6f2fcf320a) | Apr 08, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [097df073bd](https://linux-hardware.org/?probe=097df073bd) | Apr 08, 2023 |
| ASRock        | X99 Taichi                  | [7ae23e9c38](https://linux-hardware.org/?probe=7ae23e9c38) | Apr 07, 2023 |
| HP            | ProLiant MicroServer Gen... | [0258b5925f](https://linux-hardware.org/?probe=0258b5925f) | Apr 07, 2023 |
| Gigabyte      | F2A68HM-H                   | [98bc626360](https://linux-hardware.org/?probe=98bc626360) | Apr 07, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [a6e4c91ee0](https://linux-hardware.org/?probe=a6e4c91ee0) | Apr 07, 2023 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | [64b9978ed0](https://linux-hardware.org/?probe=64b9978ed0) | Apr 06, 2023 |
| HP            | 8055                        | [8ef78a4649](https://linux-hardware.org/?probe=8ef78a4649) | Apr 06, 2023 |
| HP            | 8055                        | [8afe68fd20](https://linux-hardware.org/?probe=8afe68fd20) | Apr 06, 2023 |
| eMachines     | EMCP73VT-PM                 | [936f8c6692](https://linux-hardware.org/?probe=936f8c6692) | Apr 06, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_22.04/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.15.0-56-generic | 289      | 7.41%   |
| 5.15.0-52-generic | 250      | 6.41%   |
| 5.15.0-58-generic | 242      | 6.21%   |
| 5.19.0-35-generic | 212      | 5.44%   |
| 5.15.0-48-generic | 202      | 5.18%   |
| 5.15.0-47-generic | 196      | 5.03%   |
| 5.15.0-43-generic | 190      | 4.87%   |
| 5.19.0-32-generic | 164      | 4.21%   |
| 5.19.0-41-generic | 163      | 4.18%   |
| 5.15.0-53-generic | 150      | 3.85%   |
| 5.19.0-38-generic | 145      | 3.72%   |
| 5.15.0-46-generic | 137      | 3.51%   |
| 5.15.0-25-generic | 110      | 2.82%   |
| 5.15.0-27-generic | 102      | 2.62%   |
| 5.19.0-43-generic | 99       | 2.54%   |
| 5.15.0-60-generic | 94       | 2.41%   |
| 5.15.0-41-generic | 93       | 2.39%   |
| 5.15.0-40-generic | 91       | 2.33%   |
| 5.15.0-57-generic | 82       | 2.1%    |
| 5.15.0-50-generic | 80       | 2.05%   |
| 5.19.0-40-generic | 68       | 1.74%   |
| 5.19.0-45-generic | 67       | 1.72%   |
| 5.15.0-67-generic | 63       | 1.62%   |
| 5.15.0-33-generic | 60       | 1.54%   |
| 5.15.0-30-generic | 53       | 1.36%   |
| 5.19.0-42-generic | 46       | 1.18%   |
| 5.15.0-39-generic | 46       | 1.18%   |
| 5.15.0-35-generic | 44       | 1.13%   |
| 5.15.0-69-generic | 42       | 1.08%   |
| 5.15.0-37-generic | 41       | 1.05%   |
| 5.15.0-71-generic | 26       | 0.67%   |
| 5.15.0-73-generic | 17       | 0.44%   |
| 5.15.0-72-generic | 13       | 0.33%   |
| 5.15.0-75-generic | 12       | 0.31%   |
| 5.15.0-23-generic | 12       | 0.31%   |
| 5.19.0-46-generic | 11       | 0.28%   |
| 5.15.0-70-generic | 11       | 0.28%   |
| 5.15.0-18-generic | 9        | 0.23%   |
| 5.15.0-32-generic | 7        | 0.18%   |
| 5.13.0-19-generic | 7        | 0.18%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 2526     | 71.46%  |
| 5.19.0  | 903      | 25.54%  |
| 5.17.0  | 19       | 0.54%   |
| 5.13.0  | 15       | 0.42%   |
| 5.18.0  | 5        | 0.14%   |
| 6.1.0   | 4        | 0.11%   |
| 6.0.0   | 4        | 0.11%   |
| 6.0.1   | 3        | 0.08%   |
| 5.18.10 | 3        | 0.08%   |
| 5.10.60 | 3        | 0.08%   |
| 6.2.11  | 2        | 0.06%   |
| 6.1.11  | 2        | 0.06%   |
| 6.0.9   | 2        | 0.06%   |
| 5.8.0   | 2        | 0.06%   |
| 5.19.5  | 2        | 0.06%   |
| 5.19.17 | 2        | 0.06%   |
| 5.17.9  | 2        | 0.06%   |
| 5.17.15 | 2        | 0.06%   |
| 5.15.13 | 2        | 0.06%   |
| 5.14.0  | 2        | 0.06%   |
| 6.3.7   | 1        | 0.03%   |
| 6.3.2   | 1        | 0.03%   |
| 6.2.9   | 1        | 0.03%   |
| 6.2.6   | 1        | 0.03%   |
| 6.2.3   | 1        | 0.03%   |
| 6.2.1   | 1        | 0.03%   |
| 6.2.0   | 1        | 0.03%   |
| 6.1.8   | 1        | 0.03%   |
| 6.1.6   | 1        | 0.03%   |
| 6.1.4   | 1        | 0.03%   |
| 6.1.32  | 1        | 0.03%   |
| 6.1.10  | 1        | 0.03%   |
| 6.0.8   | 1        | 0.03%   |
| 6.0.3   | 1        | 0.03%   |
| 5.4.0   | 1        | 0.03%   |
| 5.19.3  | 1        | 0.03%   |
| 5.18.8  | 1        | 0.03%   |
| 5.18.3  | 1        | 0.03%   |
| 5.18.19 | 1        | 0.03%   |
| 5.18.13 | 1        | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 2528     | 71.55%  |
| 5.19    | 908      | 25.7%   |
| 5.17    | 28       | 0.79%   |
| 5.13    | 15       | 0.42%   |
| 5.18    | 13       | 0.37%   |
| 6.1     | 11       | 0.31%   |
| 6.0     | 11       | 0.31%   |
| 6.2     | 7        | 0.2%    |
| 5.10    | 3        | 0.08%   |
| 6.3     | 2        | 0.06%   |
| 5.8     | 2        | 0.06%   |
| 5.14    | 2        | 0.06%   |
| 5.4     | 1        | 0.03%   |
| 5.16    | 1        | 0.03%   |
| 5.11    | 1        | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 3435     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 3130     | 91.07%  |
| Unknown         | 177      | 5.15%   |
| GNUstep         | 66       | 1.92%   |
| X-Cinnamon      | 36       | 1.05%   |
| GNOME Flashback | 11       | 0.32%   |
| GNOME Classic   | 8        | 0.23%   |
| i3              | 4        | 0.12%   |
| ubuntu=GNOME    | 1        | 0.03%   |
| ubuntu          | 1        | 0.03%   |
| INPT            | 1        | 0.03%   |
| i3-with-shmlog  | 1        | 0.03%   |
| awesome         | 1        | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 1866     | 53.3%   |
| X11     | 1356     | 38.73%  |
| Tty     | 201      | 5.74%   |
| Unknown | 77       | 2.2%    |
| Web     | 1        | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM3    | 3002     | 87.17%  |
| Unknown | 300      | 8.71%   |
| LightDM | 111      | 3.22%   |
| GDM     | 14       | 0.41%   |
| SDDM    | 12       | 0.35%   |
| SLiM    | 4        | 0.12%   |
| LXDM    | 1        | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 1515     | 43.98%  |
| de_DE   | 340      | 9.87%   |
| fr_FR   | 219      | 6.36%   |
| en_GB   | 169      | 4.91%   |
| pt_BR   | 135      | 3.92%   |
| it_IT   | 114      | 3.31%   |
| en_CA   | 100      | 2.9%    |
| ru_RU   | 88       | 2.55%   |
| es_ES   | 74       | 2.15%   |
| en_AU   | 64       | 1.86%   |
| en_IN   | 52       | 1.51%   |
| pl_PL   | 45       | 1.31%   |
| C       | 41       | 1.19%   |
| nl_NL   | 37       | 1.07%   |
| cs_CZ   | 31       | 0.9%    |
| Unknown | 31       | 0.9%    |
| ja_JP   | 30       | 0.87%   |
| de_AT   | 28       | 0.81%   |
| es_MX   | 22       | 0.64%   |
| es_AR   | 22       | 0.64%   |
| sv_SE   | 21       | 0.61%   |
| zh_CN   | 18       | 0.52%   |
| fi_FI   | 17       | 0.49%   |
| en_ZA   | 17       | 0.49%   |
| hu_HU   | 14       | 0.41%   |
| fr_BE   | 13       | 0.38%   |
| pt_PT   | 12       | 0.35%   |
| el_GR   | 11       | 0.32%   |
| nl_BE   | 10       | 0.29%   |
| en_PH   | 10       | 0.29%   |
| en_NZ   | 10       | 0.29%   |
| de_CH   | 10       | 0.29%   |
| tr_TR   | 9        | 0.26%   |
| ko_KR   | 8        | 0.23%   |
| fr_CA   | 8        | 0.23%   |
| es_CO   | 8        | 0.23%   |
| sk_SK   | 7        | 0.2%    |
| zh_TW   | 5        | 0.15%   |
| nb_NO   | 5        | 0.15%   |
| es_EC   | 5        | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 2405     | 69.35%  |
| EFI  | 1063     | 30.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Ext4          | 2938     | 84.06%  |
| Tmpfs         | 300      | 8.58%   |
| Overlay       | 103      | 2.95%   |
| Zfs           | 77       | 2.2%    |
| Btrfs         | 40       | 1.14%   |
| Xfs           | 22       | 0.63%   |
| Ext2          | 7        | 0.2%    |
| Unknown       | 4        | 0.11%   |
| XXXX          | 1        | 0.03%   |
| Jfs           | 1        | 0.03%   |
| Fuse.snapfuse | 1        | 0.03%   |
| Ext3          | 1        | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 2294     | 64.51%  |
| Unknown | 895      | 25.17%  |
| MBR     | 367      | 10.32%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2858     | 82.13%  |
| Yes       | 622      | 17.87%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1986     | 57.3%   |
| Yes       | 1480     | 42.7%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 881      | 25.65%  |
| Gigabyte Technology | 512      | 14.91%  |
| MSI                 | 413      | 12.02%  |
| Dell                | 367      | 10.68%  |
| ASRock              | 264      | 7.69%   |
| Hewlett-Packard     | 253      | 7.37%   |
| Lenovo              | 137      | 3.99%   |
| Intel               | 96       | 2.79%   |
| Acer                | 70       | 2.04%   |
| Fujitsu             | 58       | 1.69%   |
| Unknown             | 43       | 1.25%   |
| Pegatron            | 32       | 0.93%   |
| Medion              | 30       | 0.87%   |
| Foxconn             | 28       | 0.82%   |
| Biostar             | 26       | 0.76%   |
| Shuttle             | 17       | 0.49%   |
| ECS                 | 17       | 0.49%   |
| Apple               | 17       | 0.49%   |
| Supermicro          | 14       | 0.41%   |
| Alienware           | 13       | 0.38%   |
| Huanan              | 10       | 0.29%   |
| AZW                 | 10       | 0.29%   |
| Gateway             | 9        | 0.26%   |
| Packard Bell        | 8        | 0.23%   |
| BESSTAR Tech        | 7        | 0.2%    |
| Positivo            | 6        | 0.17%   |
| ASRockRack          | 6        | 0.17%   |
| OEM                 | 5        | 0.15%   |
| eMachines           | 5        | 0.15%   |
| AMI                 | 4        | 0.12%   |
| Wistron             | 3        | 0.09%   |
| PCWare              | 3        | 0.09%   |
| Google              | 3        | 0.09%   |
| ZOTAC               | 2        | 0.06%   |
| YANYU               | 2        | 0.06%   |
| System76            | 2        | 0.06%   |
| Protectli           | 2        | 0.06%   |
| NCR                 | 2        | 0.06%   |
| MiTAC               | 2        | 0.06%   |
| Maxtang             | 2        | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS All Series              | 89       | 2.59%   |
| Unknown                      | 49       | 1.43%   |
| Dell OptiPlex 7010           | 29       | 0.84%   |
| Dell OptiPlex 9020           | 23       | 0.67%   |
| ASUS PRIME A320M-K           | 23       | 0.67%   |
| ASUS TUF Gaming X570-PLUS    | 22       | 0.64%   |
| MSI MS-7C37                  | 18       | 0.52%   |
| MSI MS-7721                  | 18       | 0.52%   |
| ASUS PRIME Z590-P            | 18       | 0.52%   |
| Dell OptiPlex 3020           | 17       | 0.49%   |
| MSI MS-7C91                  | 15       | 0.44%   |
| ASUS ROG STRIX B550-F GAMING | 15       | 0.44%   |
| Dell OptiPlex 790            | 14       | 0.41%   |
| ASUS PRIME X570-PRO          | 14       | 0.41%   |
| ASUS PRIME B550M-A           | 14       | 0.41%   |
| HP Compaq 8200 Elite SFF PC  | 12       | 0.35%   |
| MSI MS-7C52                  | 11       | 0.32%   |
| Dell OptiPlex 990            | 11       | 0.32%   |
| Dell OptiPlex 7050           | 11       | 0.32%   |
| Dell OptiPlex 3050           | 11       | 0.32%   |
| ASRock B450M Pro4            | 11       | 0.32%   |
| MSI MS-7C02                  | 10       | 0.29%   |
| MSI MS-7B79                  | 10       | 0.29%   |
| Intel H61                    | 10       | 0.29%   |
| HP ProDesk 600 G1 SFF        | 10       | 0.29%   |
| Gigabyte B450M DS3H          | 10       | 0.29%   |
| Dell OptiPlex 780            | 10       | 0.29%   |
| ASUS M5A78L-M/USB3           | 10       | 0.29%   |
| Dell OptiPlex 7040           | 9        | 0.26%   |
| ASUS ROG STRIX B450-F GAMING | 9        | 0.26%   |
| ASRock A320M-HDV R4.0        | 9        | 0.26%   |
| MSI MS-7C56                  | 8        | 0.23%   |
| MSI MS-7B86                  | 8        | 0.23%   |
| MSI MS-7817                  | 8        | 0.23%   |
| MSI MS-7693                  | 8        | 0.23%   |
| HP EliteDesk 800 G1 SFF      | 8        | 0.23%   |
| HP Compaq Pro 6300 SFF       | 8        | 0.23%   |
| Gigabyte B75M-D3H            | 8        | 0.23%   |
| Gigabyte A320M-S2H           | 8        | 0.23%   |
| Gigabyte 970A-DS3P           | 8        | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell OptiPlex       | 226      | 6.58%   |
| ASUS PRIME          | 197      | 5.74%   |
| ASUS ROG            | 112      | 3.26%   |
| ASUS TUF            | 89       | 2.59%   |
| ASUS All            | 89       | 2.59%   |
| HP Compaq           | 83       | 2.42%   |
| Lenovo ThinkCentre  | 70       | 2.04%   |
| Dell Precision      | 58       | 1.69%   |
| Unknown             | 49       | 1.43%   |
| Acer Aspire         | 44       | 1.28%   |
| HP EliteDesk        | 41       | 1.19%   |
| Dell Inspiron       | 35       | 1.02%   |
| Fujitsu ESPRIMO     | 33       | 0.96%   |
| HP ProDesk          | 30       | 0.87%   |
| Lenovo ThinkStation | 22       | 0.64%   |
| Gigabyte B450M      | 22       | 0.64%   |
| ASUS M5A78L-M       | 21       | 0.61%   |
| Gigabyte X570       | 20       | 0.58%   |
| Lenovo IdeaCentre   | 19       | 0.55%   |
| Fujitsu CELSIUS     | 19       | 0.55%   |
| MSI MS-7C37         | 18       | 0.52%   |
| MSI MS-7721         | 18       | 0.52%   |
| Gigabyte Z390       | 18       | 0.52%   |
| Dell XPS            | 18       | 0.52%   |
| ASUS M5A97          | 18       | 0.52%   |
| ASRock B450M        | 17       | 0.49%   |
| Gigabyte B550M      | 16       | 0.47%   |
| MSI MS-7C91         | 15       | 0.44%   |
| Gigabyte B550       | 15       | 0.44%   |
| Gigabyte B450       | 15       | 0.44%   |
| ASUS P8H61-M        | 15       | 0.44%   |
| Dell Vostro         | 14       | 0.41%   |
| ASUS Pro            | 14       | 0.41%   |
| ASUS CROSSHAIR      | 14       | 0.41%   |
| ASRock X570         | 12       | 0.35%   |
| Acer Veriton        | 12       | 0.35%   |
| MSI MS-7C52         | 11       | 0.32%   |
| MSI MS-7C02         | 10       | 0.29%   |
| MSI MS-7B79         | 10       | 0.29%   |
| Intel H61           | 10       | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 318      | 9.26%   |
| 2013    | 304      | 8.85%   |
| 2012    | 296      | 8.62%   |
| 2021    | 273      | 7.95%   |
| 2020    | 265      | 7.71%   |
| 2019    | 262      | 7.63%   |
| 2011    | 253      | 7.37%   |
| 2014    | 239      | 6.96%   |
| 2017    | 216      | 6.29%   |
| 2015    | 196      | 5.71%   |
| 2010    | 168      | 4.89%   |
| 2022    | 162      | 4.72%   |
| 2009    | 144      | 4.19%   |
| 2016    | 130      | 3.78%   |
| 2008    | 100      | 2.91%   |
| 2007    | 64       | 1.86%   |
| 2006    | 18       | 0.52%   |
| 2023    | 16       | 0.47%   |
| 2005    | 6        | 0.17%   |
| Unknown | 5        | 0.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 3435     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 3316     | 96.34%  |
| Enabled  | 126      | 3.66%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 3429     | 99.83%  |
| Yes  | 6        | 0.17%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 901      | 26%     |
| 32.01-64.0      | 599      | 17.29%  |
| 8.01-16.0       | 597      | 17.23%  |
| 4.01-8.0        | 568      | 16.39%  |
| 3.01-4.0        | 388      | 11.2%   |
| 64.01-256.0     | 243      | 7.01%   |
| 24.01-32.0      | 93       | 2.68%   |
| 1.01-2.0        | 43       | 1.24%   |
| 2.01-3.0        | 19       | 0.55%   |
| More than 256.0 | 12       | 0.35%   |
| 0.51-1.0        | 2        | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 1157     | 31.58%  |
| 2.01-3.0    | 1092     | 29.8%   |
| 4.01-8.0    | 554      | 15.12%  |
| 3.01-4.0    | 529      | 14.44%  |
| 8.01-16.0   | 189      | 5.16%   |
| 0.51-1.0    | 73       | 1.99%   |
| 16.01-24.0  | 30       | 0.82%   |
| 0.01-0.5    | 15       | 0.41%   |
| 24.01-32.0  | 13       | 0.35%   |
| 32.01-64.0  | 11       | 0.3%    |
| 64.01-256.0 | 1        | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 1393     | 39.61%  |
| 2      | 1036     | 29.46%  |
| 3      | 528      | 15.01%  |
| 4      | 252      | 7.17%   |
| 5      | 125      | 3.55%   |
| 6      | 61       | 1.73%   |
| 0      | 41       | 1.17%   |
| 7      | 31       | 0.88%   |
| 8      | 15       | 0.43%   |
| 9      | 13       | 0.37%   |
| 11     | 6        | 0.17%   |
| 10     | 5        | 0.14%   |
| 12     | 3        | 0.09%   |
| 25     | 2        | 0.06%   |
| 13     | 2        | 0.06%   |
| 38     | 1        | 0.03%   |
| 20     | 1        | 0.03%   |
| 17     | 1        | 0.03%   |
| 14     | 1        | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1916     | 55.39%  |
| Yes       | 1543     | 44.61%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3405     | 99.1%   |
| No        | 31       | 0.9%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1903     | 55.02%  |
| Yes       | 1556     | 44.98%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2352     | 67.96%  |
| Yes       | 1109     | 32.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 749      | 21.78%  |
| Germany      | 403      | 11.72%  |
| France       | 234      | 6.8%    |
| Brazil       | 186      | 5.41%   |
| UK           | 164      | 4.77%   |
| Russia       | 134      | 3.9%    |
| Italy        | 133      | 3.87%   |
| Canada       | 132      | 3.84%   |
| Switzerland  | 126      | 3.66%   |
| Spain        | 83       | 2.41%   |
| Australia    | 71       | 2.06%   |
| Netherlands  | 66       | 1.92%   |
| Poland       | 60       | 1.74%   |
| India        | 57       | 1.66%   |
| Austria      | 46       | 1.34%   |
| Sweden       | 41       | 1.19%   |
| Belgium      | 40       | 1.16%   |
| Finland      | 38       | 1.1%    |
| Mexico       | 37       | 1.08%   |
| Japan        | 37       | 1.08%   |
| Czechia      | 36       | 1.05%   |
| Argentina    | 36       | 1.05%   |
| Greece       | 30       | 0.87%   |
| Turkey       | 23       | 0.67%   |
| Hungary      | 23       | 0.67%   |
| South Africa | 21       | 0.61%   |
| Romania      | 20       | 0.58%   |
| China        | 20       | 0.58%   |
| Bulgaria     | 19       | 0.55%   |
| Slovakia     | 18       | 0.52%   |
| Portugal     | 17       | 0.49%   |
| South Korea  | 14       | 0.41%   |
| Norway       | 14       | 0.41%   |
| Denmark      | 14       | 0.41%   |
| Serbia       | 12       | 0.35%   |
| Colombia     | 12       | 0.35%   |
| New Zealand  | 11       | 0.32%   |
| Taiwan       | 10       | 0.29%   |
| Indonesia    | 10       | 0.29%   |
| Hong Kong    | 10       | 0.29%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Zurich            | 79       | 2.21%   |
| Berlin            | 34       | 0.95%   |
| Vienna            | 30       | 0.84%   |
| Paris             | 26       | 0.73%   |
| Sydney            | 25       | 0.7%    |
| Moscow            | 25       | 0.7%    |
| Cheboksary        | 24       | 0.67%   |
| Milan             | 22       | 0.62%   |
| Helsinki          | 20       | 0.56%   |
| Sao Paulo         | 19       | 0.53%   |
| Madrid            | 19       | 0.53%   |
| Lucerne           | 18       | 0.5%    |
| Rio de Janeiro    | 17       | 0.48%   |
| New York          | 17       | 0.48%   |
| Athens            | 17       | 0.48%   |
| St Petersburg     | 16       | 0.45%   |
| Seattle           | 16       | 0.45%   |
| Prague            | 16       | 0.45%   |
| Hamburg           | 16       | 0.45%   |
| Toronto           | 14       | 0.39%   |
| Munich            | 14       | 0.39%   |
| Istanbul          | 14       | 0.39%   |
| San José         | 13       | 0.36%   |
| Warsaw            | 12       | 0.34%   |
| Rome              | 12       | 0.34%   |
| Manchester        | 12       | 0.34%   |
| London            | 12       | 0.34%   |
| Dallas            | 12       | 0.34%   |
| Budapest          | 12       | 0.34%   |
| Sofia             | 11       | 0.31%   |
| Frankfurt am Main | 11       | 0.31%   |
| Brisbane          | 11       | 0.31%   |
| Amsterdam         | 11       | 0.31%   |
| Melbourne         | 10       | 0.28%   |
| Los Angeles       | 10       | 0.28%   |
| Stockholm         | 9        | 0.25%   |
| Perth             | 9        | 0.25%   |
| Bucharest         | 9        | 0.25%   |
| Vancouver         | 8        | 0.22%   |
| Turin             | 8        | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 1120     | 1775   | 18.46%  |
| WDC                         | 1098     | 1805   | 18.1%   |
| Samsung Electronics         | 920      | 1414   | 15.16%  |
| Kingston                    | 381      | 460    | 6.28%   |
| Toshiba                     | 300      | 393    | 4.94%   |
| Sandisk                     | 293      | 412    | 4.83%   |
| Crucial                     | 270      | 403    | 4.45%   |
| Hitachi                     | 197      | 244    | 3.25%   |
| A-DATA Technology           | 94       | 113    | 1.55%   |
| Intel                       | 88       | 103    | 1.45%   |
| China                       | 75       | 85     | 1.24%   |
| Unknown                     | 73       | 116    | 1.2%    |
| HGST                        | 67       | 101    | 1.1%    |
| SK hynix                    | 58       | 73     | 0.96%   |
| Phison Electronics          | 51       | 70     | 0.84%   |
| Intenso                     | 51       | 60     | 0.84%   |
| Silicon Motion              | 48       | 58     | 0.79%   |
| PNY                         | 43       | 49     | 0.71%   |
| Kingston Technology Company | 41       | 46     | 0.68%   |
| Micron/Crucial Technology   | 40       | 56     | 0.66%   |
| SPCC                        | 37       | 60     | 0.61%   |
| Phison                      | 32       | 45     | 0.53%   |
| Micron Technology           | 31       | 43     | 0.51%   |
| OCZ                         | 28       | 44     | 0.46%   |
| Patriot                     | 25       | 30     | 0.41%   |
| Maxtor                      | 24       | 33     | 0.4%    |
| Gigabyte Technology         | 23       | 30     | 0.38%   |
| Transcend                   | 22       | 22     | 0.36%   |
| Lexar                       | 22       | 22     | 0.36%   |
| Corsair                     | 22       | 25     | 0.36%   |
| Unknown                     | 20       | 23     | 0.33%   |
| Team                        | 19       | 29     | 0.31%   |
| Hewlett-Packard             | 16       | 47     | 0.26%   |
| ASMT                        | 15       | 27     | 0.25%   |
| Realtek Semiconductor       | 14       | 16     | 0.23%   |
| KIOXIA                      | 14       | 27     | 0.23%   |
| JMicron Technology          | 14       | 15     | 0.23%   |
| Apacer                      | 14       | 14     | 0.23%   |
| ADATA Technology            | 14       | 19     | 0.23%   |
| KingSpec                    | 12       | 12     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB                        | 89       | 1.26%   |
| Seagate ST500DM002-1BD142 500GB                       | 88       | 1.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB   | 84       | 1.19%   |
| Kingston SA400S37240G 240GB SSD                       | 82       | 1.16%   |
| Seagate ST2000DM008-2FR102 2TB                        | 78       | 1.11%   |
| Samsung SSD 850 EVO 250GB                             | 60       | 0.85%   |
| Samsung SSD 850 EVO 500GB                             | 59       | 0.84%   |
| Samsung SSD 860 EVO 500GB                             | 54       | 0.77%   |
| Samsung SSD 980 PRO 1TB                               | 53       | 0.75%   |
| Kingston SA400S37480G 480GB SSD                       | 52       | 0.74%   |
| Seagate ST4000DM004-2CV104 4TB                        | 46       | 0.65%   |
| Seagate ST1000DM003-1CH162 1TB                        | 46       | 0.65%   |
| Toshiba DT01ACA100 1TB                                | 45       | 0.64%   |
| Crucial CT500MX500SSD1 500GB                          | 42       | 0.6%    |
| Toshiba DT01ACA050 500GB                              | 41       | 0.58%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 40       | 0.57%   |
| Seagate ST1000DM003-1ER162 1TB                        | 37       | 0.52%   |
| Kingston SA400S37120G 120GB SSD                       | 37       | 0.52%   |
| Crucial CT240BX500SSD1 240GB                          | 35       | 0.5%    |
| SanDisk NVMe SSD Drive 1TB                            | 32       | 0.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB    | 32       | 0.45%   |
| Crucial CT1000MX500SSD1 1TB                           | 32       | 0.45%   |
| Toshiba HDWD110 1TB                                   | 31       | 0.44%   |
| Samsung SSD 980 1TB                                   | 31       | 0.44%   |
| Samsung NVMe SSD Drive 1TB                            | 31       | 0.44%   |
| Unknown SD/MMC/MS PRO 250GB                           | 29       | 0.41%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 28       | 0.4%    |
| Seagate ST2000DM001-1CH164 2TB                        | 27       | 0.38%   |
| Toshiba DT01ACA200 2TB                                | 26       | 0.37%   |
| Seagate ST2000DM006-2DM164 2TB                        | 26       | 0.37%   |
| Seagate ST1000DM003-1SB102 1TB                        | 26       | 0.37%   |
| Samsung SSD 860 EVO 1TB                               | 26       | 0.37%   |
| Seagate ST3500418AS 500GB                             | 24       | 0.34%   |
| Samsung SSD 870 EVO 500GB                             | 24       | 0.34%   |
| Kingston SV300S37A120G 120GB SSD                      | 24       | 0.34%   |
| Toshiba VT180 240GB SSD                               | 23       | 0.33%   |
| Seagate ST2000DM001-1ER164 2TB                        | 23       | 0.33%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                   | 23       | 0.33%   |
| Crucial CT480BX500SSD1 480GB                          | 23       | 0.33%   |
| Crucial CT1000BX500SSD1 1TB                           | 22       | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1094     | 1724   | 38.51%  |
| WDC                 | 968      | 1590   | 34.07%  |
| Toshiba             | 256      | 330    | 9.01%   |
| Hitachi             | 196      | 243    | 6.9%    |
| Samsung Electronics | 148      | 209    | 5.21%   |
| HGST                | 67       | 97     | 2.36%   |
| Unknown             | 32       | 41     | 1.13%   |
| Maxtor              | 22       | 29     | 0.77%   |
| Intenso             | 15       | 16     | 0.53%   |
| Fujitsu             | 7        | 8      | 0.25%   |
| Apple               | 7        | 7      | 0.25%   |
| WD MediaMax         | 4        | 4      | 0.14%   |
| ASMT                | 4        | 5      | 0.14%   |
| Hewlett-Packard     | 3        | 11     | 0.11%   |
| ASMedia             | 3        | 3      | 0.11%   |
| USB3.0              | 2        | 3      | 0.07%   |
| Inateck             | 2        | 2      | 0.07%   |
| HPE                 | 2        | 3      | 0.07%   |
| SABRENT             | 1        | 2      | 0.04%   |
| RSH-339             | 1        | 1      | 0.04%   |
| QUANTUM             | 1        | 1      | 0.04%   |
| MARVELL             | 1        | 1      | 0.04%   |
| LaCie               | 1        | 1      | 0.04%   |
| HGST HTS            | 1        | 1      | 0.04%   |
| External            | 1        | 1      | 0.04%   |
| ExcelStor           | 1        | 1      | 0.04%   |
| DAS                 | 1        | 3      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 473      | 631    | 22.47%  |
| Kingston            | 319      | 384    | 15.15%  |
| Crucial             | 245      | 365    | 11.64%  |
| SanDisk             | 160      | 225    | 7.6%    |
| WDC                 | 121      | 149    | 5.75%   |
| A-DATA Technology   | 80       | 98     | 3.8%    |
| China               | 74       | 83     | 3.52%   |
| Intel               | 52       | 58     | 2.47%   |
| Toshiba             | 51       | 56     | 2.42%   |
| PNY                 | 39       | 45     | 1.85%   |
| SPCC                | 36       | 58     | 1.71%   |
| Intenso             | 28       | 35     | 1.33%   |
| OCZ                 | 26       | 30     | 1.24%   |
| Patriot             | 24       | 29     | 1.14%   |
| Transcend           | 21       | 21     | 1%      |
| Micron Technology   | 19       | 31     | 0.9%    |
| Team                | 18       | 28     | 0.86%   |
| SK hynix            | 18       | 24     | 0.86%   |
| Lexar               | 16       | 16     | 0.76%   |
| Gigabyte Technology | 16       | 23     | 0.76%   |
| Corsair             | 13       | 15     | 0.62%   |
| KingSpec            | 12       | 12     | 0.57%   |
| Apacer              | 12       | 12     | 0.57%   |
| Unknown             | 12       | 13     | 0.57%   |
| Hewlett-Packard     | 11       | 11     | 0.52%   |
| ASMT                | 11       | 22     | 0.52%   |
| GOODRAM             | 9        | 15     | 0.43%   |
| LITEON              | 8        | 9      | 0.38%   |
| LITEONIT            | 7        | 7      | 0.33%   |
| Emtec               | 7        | 7      | 0.33%   |
| Seagate             | 6        | 8      | 0.29%   |
| Netac               | 6        | 7      | 0.29%   |
| Dogfish             | 6        | 10     | 0.29%   |
| Mushkin             | 5        | 5      | 0.24%   |
| FORESEE             | 5        | 5      | 0.24%   |
| Fanxiang            | 5        | 7      | 0.24%   |
| Plextor             | 4        | 4      | 0.19%   |
| MidasForce          | 4        | 4      | 0.19%   |
| Leven               | 4        | 7      | 0.19%   |
| LDLC                | 4        | 4      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 2223     | 4337   | 42.96%  |
| SSD     | 1789     | 2708   | 34.58%  |
| NVMe    | 1018     | 1543   | 19.68%  |
| Unknown | 122      | 213    | 2.36%   |
| MMC     | 22       | 31     | 0.43%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 3003     | 6813   | 69.74%  |
| NVMe | 1003     | 1516   | 23.29%  |
| SAS  | 278      | 472    | 6.46%   |
| MMC  | 22       | 31     | 0.51%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 2101     | 3354   | 47.89%  |
| 0.51-1.0   | 1261     | 1928   | 28.74%  |
| 1.01-2.0   | 515      | 799    | 11.74%  |
| 3.01-4.0   | 220      | 349    | 5.01%   |
| 4.01-10.0  | 134      | 329    | 3.05%   |
| 2.01-3.0   | 115      | 167    | 2.62%   |
| 10.01-20.0 | 41       | 119    | 0.93%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 859      | 24.2%   |
| 251-500        | 664      | 18.7%   |
| 501-1000       | 641      | 18.06%  |
| 1001-2000      | 404      | 11.38%  |
| More than 3000 | 349      | 9.83%   |
| 2001-3000      | 185      | 5.21%   |
| 51-100         | 171      | 4.82%   |
| 1-20           | 142      | 4%      |
| Unknown        | 68       | 1.92%   |
| 21-50          | 67       | 1.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1142     | 31.45%  |
| 21-50          | 649      | 17.87%  |
| 51-100         | 437      | 12.04%  |
| 101-250        | 430      | 11.84%  |
| 251-500        | 294      | 8.1%    |
| 501-1000       | 246      | 6.77%   |
| More than 3000 | 152      | 4.19%   |
| 1001-2000      | 149      | 4.1%    |
| Unknown        | 68       | 1.87%   |
| 2001-3000      | 63       | 1.74%   |
| 0              | 1        | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD40EFRX-68WT0N0 4TB              | 7        | 8      | 2.24%   |
| Seagate ST500DM002-1BD142 500GB       | 7        | 7      | 2.24%   |
| WDC WD10EARS-00Y5B1 1TB               | 4        | 5      | 1.28%   |
| SanDisk SSD PLUS 480GB                | 4        | 4      | 1.28%   |
| WDC WD5000AAKX-08ERMA0 500GB          | 3        | 3      | 0.96%   |
| Seagate ST3500418AS 500GB             | 3        | 4      | 0.96%   |
| Seagate ST3250310AS 250GB             | 3        | 3      | 0.96%   |
| Seagate ST2000DM001-1CH164 2TB        | 3        | 3      | 0.96%   |
| Samsung Electronics SSD 870 EVO 1TB   | 3        | 3      | 0.96%   |
| Kingston SV300S37A120G 120GB SSD      | 3        | 3      | 0.96%   |
| Kingston SA400S37240G 240GB SSD       | 3        | 3      | 0.96%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 2        | 2      | 0.64%   |
| WDC WD4003FZEX-00Z4SA0 4TB            | 2        | 4      | 0.64%   |
| WDC WD30EZRX-00MMMB0 3TB              | 2        | 6      | 0.64%   |
| WDC WD10EZEX-60ZF5A0 1TB              | 2        | 2      | 0.64%   |
| WDC WD10EZEX-22MFCA0 1TB              | 2        | 2      | 0.64%   |
| WDC WD10EADS-00M2B0 1TB               | 2        | 2      | 0.64%   |
| Toshiba DT01ACA100 1TB                | 2        | 2      | 0.64%   |
| Toshiba DT01ACA050 500GB              | 2        | 2      | 0.64%   |
| Seagate ST3750528AS 752GB             | 2        | 2      | 0.64%   |
| Seagate ST3320620AS 320GB             | 2        | 2      | 0.64%   |
| Seagate ST31000528AS 1TB              | 2        | 2      | 0.64%   |
| Seagate ST2000DM008-2FR102 2TB        | 2        | 2      | 0.64%   |
| Seagate ST1000DX001-1CM162 1TB        | 2        | 2      | 0.64%   |
| Seagate ST1000DM010-2EP102 1TB        | 2        | 2      | 0.64%   |
| Seagate ST1000DM003-9YN162 1TB        | 2        | 2      | 0.64%   |
| Seagate ST1000DM003-1CH162 1TB        | 2        | 2      | 0.64%   |
| SanDisk SSD PLUS 1000GB               | 2        | 2      | 0.64%   |
| Samsung Electronics SSD 980 PRO 1TB   | 2        | 3      | 0.64%   |
| Samsung Electronics SSD 970 EVO 1TB   | 2        | 2      | 0.64%   |
| Samsung Electronics SSD 870 EVO 500GB | 2        | 2      | 0.64%   |
| Samsung Electronics HD322GJ 320GB     | 2        | 2      | 0.64%   |
| Samsung Electronics HD103UJ 1TB       | 2        | 2      | 0.64%   |
| LITEONIT LCT-128M3S 128GB SSD         | 2        | 2      | 0.64%   |
| Intel SSDSC2CW120A3 120GB             | 2        | 2      | 0.64%   |
| Hitachi HUA722010CLA330 1TB           | 2        | 2      | 0.64%   |
| Hitachi HDS721010CLA332 1TB           | 2        | 2      | 0.64%   |
| Crucial CT480M500SSD1 480GB           | 2        | 2      | 0.64%   |
| A-DATA Technology SX8100NP 512GB      | 2        | 2      | 0.64%   |
| A-DATA Technology SU650 240GB SSD     | 2        | 2      | 0.64%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 91       | 110    | 29.84%  |
| Seagate             | 76       | 89     | 24.92%  |
| Samsung Electronics | 36       | 40     | 11.8%   |
| Hitachi             | 19       | 19     | 6.23%   |
| Toshiba             | 12       | 12     | 3.93%   |
| Kingston            | 10       | 10     | 3.28%   |
| Intel               | 7        | 7      | 2.3%    |
| Crucial             | 7        | 9      | 2.3%    |
| SanDisk             | 6        | 7      | 1.97%   |
| Maxtor              | 5        | 6      | 1.64%   |
| A-DATA Technology   | 5        | 5      | 1.64%   |
| China               | 4        | 4      | 1.31%   |
| LITEONIT            | 3        | 3      | 0.98%   |
| HGST                | 3        | 4      | 0.98%   |
| SK hynix            | 2        | 2      | 0.66%   |
| Micron Technology   | 2        | 8      | 0.66%   |
| LDLC                | 2        | 2      | 0.66%   |
| Intenso             | 2        | 2      | 0.66%   |
| YS                  | 1        | 1      | 0.33%   |
| XPG                 | 1        | 1      | 0.33%   |
| WD MediaMax         | 1        | 1      | 0.33%   |
| Silicon Motion      | 1        | 1      | 0.33%   |
| PNY                 | 1        | 1      | 0.33%   |
| Patriot             | 1        | 1      | 0.33%   |
| OCZ                 | 1        | 1      | 0.33%   |
| Netac               | 1        | 1      | 0.33%   |
| Mushkin             | 1        | 1      | 0.33%   |
| KingSpec            | 1        | 1      | 0.33%   |
| Gigabyte Technology | 1        | 1      | 0.33%   |
| ASMedia             | 1        | 1      | 0.33%   |
| Unknown             | 1        | 1      | 0.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 88       | 107    | 39.82%  |
| Seagate             | 76       | 89     | 34.39%  |
| Hitachi             | 19       | 19     | 8.6%    |
| Samsung Electronics | 17       | 18     | 7.69%   |
| Toshiba             | 11       | 11     | 4.98%   |
| Maxtor              | 5        | 6      | 2.26%   |
| HGST                | 3        | 4      | 1.36%   |
| WD MediaMax         | 1        | 1      | 0.45%   |
| ASMedia             | 1        | 1      | 0.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 205      | 256    | 70.93%  |
| SSD  | 69       | 79     | 23.88%  |
| NVMe | 15       | 17     | 5.19%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Samsung Electronics SSD 980 500GB     | 2        | 2      | 28.57%  |
| WDC WD800BB-00FJA0 80GB               | 1        | 1      | 14.29%  |
| WDC WD3200AAJS-22VWA0 320GB           | 1        | 1      | 14.29%  |
| Samsung Electronics SSD 960 EVO 250GB | 1        | 1      | 14.29%  |
| Intel SSDPEKKW256G7 256GB             | 1        | 1      | 14.29%  |
| Hewlett-Packard EF0450FARMV 450GB     | 1        | 4      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 3      | 42.86%  |
| WDC                 | 2        | 2      | 28.57%  |
| Intel               | 1        | 1      | 14.29%  |
| Hewlett-Packard     | 1        | 4      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 2344     | 6059   | 62.74%  |
| Works    | 1118     | 2411   | 29.93%  |
| Malfunc  | 267      | 352    | 7.15%   |
| Failed   | 7        | 10     | 0.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 2279     | 45.73%  |
| AMD                            | 1055     | 21.17%  |
| Samsung Electronics            | 391      | 7.85%   |
| SanDisk                        | 194      | 3.89%   |
| ASMedia Technology             | 194      | 3.89%   |
| Kingston Technology Company    | 105      | 2.11%   |
| Marvell Technology Group       | 104      | 2.09%   |
| Phison Electronics             | 97       | 1.95%   |
| JMicron Technology             | 93       | 1.87%   |
| Nvidia                         | 78       | 1.57%   |
| Micron/Crucial Technology      | 68       | 1.36%   |
| Silicon Motion                 | 55       | 1.1%    |
| SK hynix                       | 42       | 0.84%   |
| ADATA Technology               | 30       | 0.6%    |
| LSI Logic / Symbios Logic      | 21       | 0.42%   |
| Realtek Semiconductor          | 20       | 0.4%    |
| KIOXIA                         | 19       | 0.38%   |
| Silicon Image                  | 16       | 0.32%   |
| Broadcom / LSI                 | 16       | 0.32%   |
| VIA Technologies               | 15       | 0.3%    |
| MAXIO Technology (Hangzhou)    | 14       | 0.28%   |
| Micron Technology              | 13       | 0.26%   |
| Seagate Technology             | 12       | 0.24%   |
| Adaptec                        | 10       | 0.2%    |
| Shenzhen Longsys Electronics   | 6        | 0.12%   |
| Toshiba America Info Systems   | 4        | 0.08%   |
| Solidigm                       | 3        | 0.06%   |
| Lite-On Technology             | 3        | 0.06%   |
| INNOGRIT                       | 3        | 0.06%   |
| Hewlett-Packard                | 3        | 0.06%   |
| Union Memory (Shenzhen)        | 2        | 0.04%   |
| OCZ Technology Group           | 2        | 0.04%   |
| Integrated Technology Express  | 2        | 0.04%   |
| Apple                          | 2        | 0.04%   |
| 3ware                          | 2        | 0.04%   |
| Western Digital                | 1        | 0.02%   |
| Transcend                      | 1        | 0.02%   |
| TenaFe                         | 1        | 0.02%   |
| Tekram Technology              | 1        | 0.02%   |
| Solid State Storage Technology | 1        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 579      | 9.58%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 288      | 4.77%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 197      | 3.26%   |
| Intel SATA Controller [RAID mode]                                                       | 191      | 3.16%   |
| AMD 400 Series Chipset SATA Controller                                                  | 188      | 3.11%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 186      | 3.08%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 179      | 2.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 171      | 2.83%   |
| AMD 500 Series Chipset SATA Controller                                                  | 165      | 2.73%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 157      | 2.6%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 146      | 2.42%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 138      | 2.28%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 118      | 1.95%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 115      | 1.9%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 107      | 1.77%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 103      | 1.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 95       | 1.57%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 93       | 1.54%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 82       | 1.36%   |
| AMD FCH SATA Controller D                                                               | 75       | 1.24%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 71       | 1.17%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 70       | 1.16%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 66       | 1.09%   |
| Samsung NVMe SSD Controller 980                                                         | 61       | 1.01%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 57       | 0.94%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 50       | 0.83%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 46       | 0.76%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 44       | 0.73%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 43       | 0.71%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 43       | 0.71%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 43       | 0.71%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 43       | 0.71%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 41       | 0.68%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 39       | 0.65%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 37       | 0.61%   |
| AMD 300 Series Chipset SATA Controller                                                  | 37       | 0.61%   |
| Nvidia MCP61 SATA Controller                                                            | 36       | 0.6%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 35       | 0.58%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 35       | 0.58%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 34       | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 2818     | 57.94%  |
| NVMe | 1006     | 20.68%  |
| IDE  | 653      | 13.43%  |
| RAID | 333      | 6.85%   |
| SAS  | 39       | 0.8%    |
| SCSI | 15       | 0.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 2319     | 67.51%  |
| AMD    | 1116     | 32.49%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 61       | 1.77%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 52       | 1.51%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 44       | 1.28%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 42       | 1.22%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 40       | 1.16%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 40       | 1.16%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 39       | 1.13%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 37       | 1.07%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 36       | 1.04%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 35       | 1.02%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 34       | 0.99%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 34       | 0.99%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 33       | 0.96%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 33       | 0.96%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 32       | 0.93%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 32       | 0.93%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 30       | 0.87%   |
| AMD FX-8350 Eight-Core Processor            | 30       | 0.87%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 28       | 0.81%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 28       | 0.81%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 25       | 0.73%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 25       | 0.73%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 24       | 0.7%    |
| Intel Core i5-6500 CPU @ 3.20GHz            | 24       | 0.7%    |
| Intel Core i7-9700K CPU @ 3.60GHz           | 23       | 0.67%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 23       | 0.67%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 23       | 0.67%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 22       | 0.64%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 20       | 0.58%   |
| Intel 12th Gen Core i9-12900K               | 20       | 0.58%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 19       | 0.55%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 19       | 0.55%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 19       | 0.55%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 19       | 0.55%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 19       | 0.55%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 18       | 0.52%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 18       | 0.52%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 18       | 0.52%   |
| AMD FX-6300 Six-Core Processor              | 18       | 0.52%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 17       | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 672      | 19.53%  |
| Intel Core i7           | 504      | 14.65%  |
| Intel Core i3           | 285      | 8.28%   |
| AMD Ryzen 5             | 273      | 7.94%   |
| Intel Xeon              | 213      | 6.19%   |
| Other                   | 201      | 5.84%   |
| AMD Ryzen 7             | 183      | 5.32%   |
| AMD Ryzen 9             | 122      | 3.55%   |
| AMD FX                  | 117      | 3.4%    |
| Intel Celeron           | 96       | 2.79%   |
| Intel Core 2 Duo        | 81       | 2.35%   |
| Intel Core 2 Quad       | 77       | 2.24%   |
| Intel Pentium           | 75       | 2.18%   |
| AMD Ryzen 3             | 55       | 1.6%    |
| AMD A10                 | 43       | 1.25%   |
| Intel Pentium Dual-Core | 35       | 1.02%   |
| Intel Core i9           | 33       | 0.96%   |
| AMD Phenom II X4        | 32       | 0.93%   |
| AMD A8                  | 31       | 0.9%    |
| AMD Ryzen Threadripper  | 29       | 0.84%   |
| AMD Athlon II X2        | 29       | 0.84%   |
| AMD A6                  | 23       | 0.67%   |
| AMD A4                  | 18       | 0.52%   |
| AMD Phenom II X6        | 17       | 0.49%   |
| AMD Athlon 64 X2        | 17       | 0.49%   |
| AMD Athlon II X4        | 16       | 0.47%   |
| Intel Core 2            | 15       | 0.44%   |
| Intel Atom              | 13       | 0.38%   |
| AMD Athlon              | 13       | 0.38%   |
| AMD Athlon II X3        | 10       | 0.29%   |
| Intel Pentium Dual      | 9        | 0.26%   |
| AMD Ryzen 5 PRO         | 9        | 0.26%   |
| AMD Phenom II X2        | 9        | 0.26%   |
| AMD Sempron             | 8        | 0.23%   |
| AMD Athlon X4           | 7        | 0.2%    |
| AMD Ryzen 3 PRO         | 6        | 0.17%   |
| Intel Pentium Gold      | 5        | 0.15%   |
| Intel Pentium 4         | 5        | 0.15%   |
| AMD Phenom              | 5        | 0.15%   |
| AMD E1                  | 5        | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 1402     | 40.74%  |
| 2      | 742      | 21.56%  |
| 6      | 518      | 15.05%  |
| 8      | 374      | 10.87%  |
| 12     | 131      | 3.81%   |
| 16     | 96       | 2.79%   |
| 1      | 54       | 1.57%   |
| 3      | 49       | 1.42%   |
| 10     | 28       | 0.81%   |
| 24     | 17       | 0.49%   |
| 32     | 9        | 0.26%   |
| 14     | 7        | 0.2%    |
| 28     | 4        | 0.12%   |
| 20     | 4        | 0.12%   |
| 64     | 2        | 0.06%   |
| 18     | 2        | 0.06%   |
| 128    | 1        | 0.03%   |
| 40     | 1        | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 3373     | 98.2%   |
| 2      | 62       | 1.8%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 2019     | 58.73%  |
| 1      | 1417     | 41.22%  |
| 6      | 1        | 0.03%   |
| 4      | 1        | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 3433     | 99.91%  |
| Unknown        | 3        | 0.09%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 2104     | 59.82%  |
| 0x306c3    | 146      | 4.15%   |
| 0x306a9    | 98       | 2.79%   |
| 0x506e3    | 85       | 2.42%   |
| 0x206a7    | 73       | 2.08%   |
| 0x08701021 | 59       | 1.68%   |
| 0x906ea    | 57       | 1.62%   |
| 0x906e9    | 53       | 1.51%   |
| 0x90672    | 38       | 1.08%   |
| 0x0a201016 | 37       | 1.05%   |
| 0xa0653    | 34       | 0.97%   |
| 0xa0671    | 33       | 0.94%   |
| 0x06000852 | 33       | 0.94%   |
| 0x0800820d | 31       | 0.88%   |
| 0x306f2    | 30       | 0.85%   |
| 0x0a20120a | 30       | 0.85%   |
| 0x1067a    | 28       | 0.8%    |
| 0x010000c8 | 27       | 0.77%   |
| 0x906ed    | 25       | 0.71%   |
| 0xa0655    | 24       | 0.68%   |
| 0x08108109 | 22       | 0.63%   |
| 0x08701013 | 19       | 0.54%   |
| 0x0a601203 | 16       | 0.45%   |
| 0x06003106 | 16       | 0.45%   |
| 0xb0671    | 14       | 0.4%    |
| 0x906ec    | 14       | 0.4%    |
| 0x0a50000c | 13       | 0.37%   |
| 0x06001119 | 13       | 0.37%   |
| 0x0a201205 | 12       | 0.34%   |
| 0x906eb    | 11       | 0.31%   |
| 0x0a50000d | 11       | 0.31%   |
| 0x406f1    | 10       | 0.28%   |
| 0x20655    | 10       | 0.28%   |
| 0x106a5    | 10       | 0.28%   |
| 0x0a201009 | 10       | 0.28%   |
| 0x0810100b | 10       | 0.28%   |
| 0x08001138 | 10       | 0.28%   |
| 0x90675    | 9        | 0.26%   |
| 0x106e5    | 9        | 0.26%   |
| 0x0a201204 | 9        | 0.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 458      | 13.32%  |
| KabyLake         | 317      | 9.22%   |
| IvyBridge        | 276      | 8.03%   |
| Zen 3            | 237      | 6.89%   |
| SandyBridge      | 234      | 6.8%    |
| Skylake          | 210      | 6.11%   |
| Zen 2            | 207      | 6.02%   |
| Penryn           | 165      | 4.8%    |
| Piledriver       | 150      | 4.36%   |
| K10              | 130      | 3.78%   |
| Unknown          | 130      | 3.78%   |
| Zen+             | 126      | 3.66%   |
| CometLake        | 109      | 3.17%   |
| Westmere         | 101      | 2.94%   |
| Zen              | 93       | 2.7%    |
| Core             | 78       | 2.27%   |
| Nehalem          | 60       | 1.74%   |
| Alderlake Hybrid | 60       | 1.74%   |
| Steamroller      | 38       | 1.1%    |
| Icelake          | 35       | 1.02%   |
| Silvermont       | 33       | 0.96%   |
| K8 Hammer        | 27       | 0.79%   |
| Broadwell        | 26       | 0.76%   |
| Bulldozer        | 25       | 0.73%   |
| Excavator        | 23       | 0.67%   |
| Goldmont plus    | 21       | 0.61%   |
| Goldmont         | 13       | 0.38%   |
| K10 Llano        | 11       | 0.32%   |
| NetBurst         | 9        | 0.26%   |
| Tremont          | 7        | 0.2%    |
| Bobcat           | 7        | 0.2%    |
| TigerLake        | 6        | 0.17%   |
| Puma             | 6        | 0.17%   |
| Jaguar           | 6        | 0.17%   |
| Bonnell          | 5        | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 1523     | 41.21%  |
| Intel                                        | 1187     | 32.12%  |
| AMD                                          | 950      | 25.7%   |
| Matrox Electronics Systems                   | 16       | 0.43%   |
| ASPEED Technology                            | 16       | 0.43%   |
| ATI Technologies                             | 2        | 0.05%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.03%   |
| VIA Technologies                             | 1        | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 214      | 5.67%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 119      | 3.15%   |
| Intel HD Graphics 530                                                       | 110      | 2.91%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 108      | 2.86%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 107      | 2.83%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 92       | 2.44%   |
| Nvidia GK208B [GeForce GT 710]                                              | 77       | 2.04%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 58       | 1.54%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 57       | 1.51%   |
| Nvidia GT218 [GeForce 210]                                                  | 54       | 1.43%   |
| Intel HD Graphics 630                                                       | 54       | 1.43%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 51       | 1.35%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 51       | 1.35%   |
| Nvidia GK208B [GeForce GT 730]                                              | 47       | 1.25%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 47       | 1.25%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 45       | 1.19%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 44       | 1.17%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 42       | 1.11%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 40       | 1.06%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 38       | 1.01%   |
| Intel AlderLake-S GT1                                                       | 37       | 0.98%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 33       | 0.87%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 32       | 0.85%   |
| Nvidia GF119 [GeForce GT 610]                                               | 30       | 0.79%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 29       | 0.77%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 29       | 0.77%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 28       | 0.74%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 28       | 0.74%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 28       | 0.74%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 27       | 0.72%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 26       | 0.69%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 26       | 0.69%   |
| Intel Core Processor Integrated Graphics Controller                         | 26       | 0.69%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 25       | 0.66%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 24       | 0.64%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 24       | 0.64%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                              | 22       | 0.58%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 22       | 0.58%   |
| AMD RS780L [Radeon 3000]                                                    | 22       | 0.58%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 21       | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 1384     | 39.99%  |
| 1 x Intel                | 1005     | 29.04%  |
| 1 x AMD                  | 854      | 24.67%  |
| Intel + Nvidia           | 61       | 1.76%   |
| AMD + Nvidia             | 39       | 1.13%   |
| 2 x AMD                  | 35       | 1.01%   |
| 2 x Nvidia               | 22       | 0.64%   |
| Intel + AMD              | 19       | 0.55%   |
| 1 x Matrox               | 12       | 0.35%   |
| 1 x ASPEED               | 10       | 0.29%   |
| Nvidia + ASPEED          | 5        | 0.14%   |
| Nvidia + Matrox          | 3        | 0.09%   |
| Other                    | 2        | 0.06%   |
| Intel + AMD + 1 x Nvidia | 2        | 0.06%   |
| 3 x AMD                  | 1        | 0.03%   |
| 1 x XGI                  | 1        | 0.03%   |
| 1 x VIA                  | 1        | 0.03%   |
| 1 x Intel + 3 x Nvidia   | 1        | 0.03%   |
| Intel + 2 x Nvidia       | 1        | 0.03%   |
| AMD + 2 x Nvidia         | 1        | 0.03%   |
| AMD + Matrox             | 1        | 0.03%   |
| AMD + ASPEED             | 1        | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 2375     | 68.13%  |
| Proprietary | 939      | 26.94%  |
| Unknown     | 172      | 4.93%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 2511     | 71.97%  |
| 1.01-2.0   | 220      | 6.31%   |
| 0.51-1.0   | 166      | 4.76%   |
| 7.01-8.0   | 162      | 4.64%   |
| 3.01-4.0   | 144      | 4.13%   |
| 0.01-0.5   | 102      | 2.92%   |
| 8.01-16.0  | 83       | 2.38%   |
| 5.01-6.0   | 51       | 1.46%   |
| 16.01-24.0 | 23       | 0.66%   |
| 2.01-3.0   | 22       | 0.63%   |
| 4.01-5.0   | 5        | 0.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 585      | 16.98%  |
| Dell                 | 399      | 11.58%  |
| Goldstar             | 309      | 8.97%   |
| Acer                 | 242      | 7.02%   |
| Hewlett-Packard      | 235      | 6.82%   |
| BenQ                 | 170      | 4.93%   |
| AOC                  | 168      | 4.88%   |
| Philips              | 160      | 4.64%   |
| Ancor Communications | 140      | 4.06%   |
| Iiyama               | 78       | 2.26%   |
| Lenovo               | 73       | 2.12%   |
| ViewSonic            | 66       | 1.92%   |
| ASUSTek Computer     | 65       | 1.89%   |
| Sony                 | 42       | 1.22%   |
| Vizio                | 33       | 0.96%   |
| Fujitsu Siemens      | 30       | 0.87%   |
| LG Electronics       | 29       | 0.84%   |
| Panasonic            | 26       | 0.75%   |
| Unknown              | 25       | 0.73%   |
| Eizo                 | 25       | 0.73%   |
| Sceptre Tech         | 24       | 0.7%    |
| NEC Computers        | 24       | 0.7%    |
| MSI                  | 21       | 0.61%   |
| Unknown              | 19       | 0.55%   |
| Medion               | 18       | 0.52%   |
| HannStar             | 18       | 0.52%   |
| Toshiba              | 14       | 0.41%   |
| Sharp                | 11       | 0.32%   |
| HKC                  | 11       | 0.32%   |
| Vestel Elektronik    | 10       | 0.29%   |
| Gigabyte Technology  | 10       | 0.29%   |
| Apple                | 10       | 0.29%   |
| RTK                  | 9        | 0.26%   |
| Mi                   | 9        | 0.26%   |
| Hitachi              | 9        | 0.26%   |
| Gericom              | 9        | 0.26%   |
| Unknown (XXX)        | 8        | 0.23%   |
| Plain Tree Systems   | 8        | 0.23%   |
| MStar                | 8        | 0.23%   |
| Onkyo                | 7        | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| BenQ GL2460 BNQ78CE 1920x1080 530x300mm 24.0-inch                       | 21       | 0.57%   |
| Unknown                                                                 | 19       | 0.52%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 15       | 0.41%   |
| Samsung Electronics LCD Monitor LF24T450F 1920x1080                     | 15       | 0.41%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 15       | 0.41%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 14       | 0.38%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                 | 13       | 0.36%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                      | 13       | 0.36%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                       | 12       | 0.33%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch    | 10       | 0.27%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 10       | 0.27%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch   | 10       | 0.27%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 9        | 0.25%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                 | 9        | 0.25%   |
| Philips 247EL PHLC084 1920x1080 521x293mm 23.5-inch                     | 9        | 0.25%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1872x1053mm 84.6-inch | 8        | 0.22%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                 | 8        | 0.22%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                   | 8        | 0.22%   |
| Gericom Q26 QMX2426 1920x1080 550x344mm 25.5-inch                       | 8        | 0.22%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch       | 7        | 0.19%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch                 | 7        | 0.19%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                        | 7        | 0.19%   |
| AOC 2790 AOC2790 1920x1080 598x336mm 27.0-inch                          | 7        | 0.19%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch               | 6        | 0.16%   |
| Sony TV SNY3102 1920x1080 708x398mm 32.0-inch                           | 6        | 0.16%   |
| Sceptre Tech E24 SPT099D 1920x1080 521x293mm 23.5-inch                  | 6        | 0.16%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch       | 6        | 0.16%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch       | 6        | 0.16%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1200                    | 6        | 0.16%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch   | 6        | 0.16%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch                | 6        | 0.16%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                 | 6        | 0.16%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                      | 6        | 0.16%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                      | 6        | 0.16%   |
| MStar Demo MST0030 1360x765 708x398mm 32.0-inch                         | 6        | 0.16%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                | 6        | 0.16%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch              | 6        | 0.16%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                       | 6        | 0.16%   |
| BenQ GL2760 BNQ78D5 1920x1080 598x336mm 27.0-inch                       | 6        | 0.16%   |
| Ancor Communications VS278 ACI27A1 1920x1080 598x336mm 27.0-inch        | 6        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1574     | 46.58%  |
| 3840x2160 (4K)     | 371      | 10.98%  |
| 2560x1440 (QHD)    | 242      | 7.16%   |
| 1280x1024 (SXGA)   | 195      | 5.77%   |
| 1680x1050 (WSXGA+) | 166      | 4.91%   |
| 1366x768 (WXGA)    | 122      | 3.61%   |
| 1920x1200 (WUXGA)  | 106      | 3.14%   |
| 1440x900 (WXGA+)   | 105      | 3.11%   |
| 1600x900 (HD+)     | 104      | 3.08%   |
| 3440x1440          | 52       | 1.54%   |
| 2560x1080          | 46       | 1.36%   |
| 1360x768           | 46       | 1.36%   |
| Unknown            | 46       | 1.36%   |
| 1920x540           | 32       | 0.95%   |
| 3840x1080          | 28       | 0.83%   |
| 1024x768 (XGA)     | 24       | 0.71%   |
| 1280x720 (HD)      | 20       | 0.59%   |
| 1600x1200          | 17       | 0.5%    |
| 2560x1600          | 12       | 0.36%   |
| 2288x1287          | 11       | 0.33%   |
| 3840x1600          | 8        | 0.24%   |
| 2048x1152          | 5        | 0.15%   |
| 1280x960           | 5        | 0.15%   |
| 3840x1200          | 4        | 0.12%   |
| 1400x1050          | 4        | 0.12%   |
| 4480x1440          | 3        | 0.09%   |
| 5760x1080          | 2        | 0.06%   |
| 5120x1440          | 2        | 0.06%   |
| 3600x1080          | 2        | 0.06%   |
| 3360x1080          | 2        | 0.06%   |
| 1280x768           | 2        | 0.06%   |
| 720x480            | 1        | 0.03%   |
| 6400x2160          | 1        | 0.03%   |
| 5760x2160          | 1        | 0.03%   |
| 5520x1080          | 1        | 0.03%   |
| 4480x1080          | 1        | 0.03%   |
| 4093x4093          | 1        | 0.03%   |
| 4080x2058          | 1        | 0.03%   |
| 3840x2560          | 1        | 0.03%   |
| 3840x1440          | 1        | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 480      | 13.95%  |
| 24      | 478      | 13.89%  |
| 23      | 421      | 12.23%  |
| 21      | 372      | 10.81%  |
| Unknown | 248      | 7.21%   |
| 19      | 217      | 6.3%    |
| 31      | 182      | 5.29%   |
| 20      | 115      | 3.34%   |
| 22      | 112      | 3.25%   |
| 18      | 112      | 3.25%   |
| 17      | 101      | 2.93%   |
| 34      | 77       | 2.24%   |
| 84      | 63       | 1.83%   |
| 32      | 51       | 1.48%   |
| 15      | 47       | 1.37%   |
| 72      | 40       | 1.16%   |
| 40      | 35       | 1.02%   |
| 25      | 34       | 0.99%   |
| 54      | 25       | 0.73%   |
| 28      | 18       | 0.52%   |
| 37      | 14       | 0.41%   |
| 65      | 13       | 0.38%   |
| 29      | 13       | 0.38%   |
| 46      | 12       | 0.35%   |
| 42      | 12       | 0.35%   |
| 36      | 12       | 0.35%   |
| 26      | 12       | 0.35%   |
| 52      | 11       | 0.32%   |
| 43      | 10       | 0.29%   |
| 48      | 9        | 0.26%   |
| 49      | 8        | 0.23%   |
| 142     | 6        | 0.17%   |
| 64      | 6        | 0.17%   |
| 47      | 6        | 0.17%   |
| 14      | 6        | 0.17%   |
| 60      | 5        | 0.15%   |
| 57      | 5        | 0.15%   |
| 35      | 5        | 0.15%   |
| 33      | 5        | 0.15%   |
| 16      | 5        | 0.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 1293     | 38.67%  |
| 401-500        | 807      | 24.13%  |
| 601-700        | 266      | 7.95%   |
| Unknown        | 248      | 7.42%   |
| 701-800        | 146      | 4.37%   |
| 301-350        | 140      | 4.19%   |
| 351-400        | 123      | 3.68%   |
| 1501-2000      | 110      | 3.29%   |
| 1001-1500      | 109      | 3.26%   |
| 801-900        | 60       | 1.79%   |
| 901-1000       | 23       | 0.69%   |
| 201-300        | 12       | 0.36%   |
| More than 2000 | 7        | 0.21%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 2193     | 68.3%   |
| 16/10   | 411      | 12.8%   |
| Unknown | 203      | 6.32%   |
| 5/4     | 196      | 6.1%    |
| 21/9    | 102      | 3.18%   |
| 4/3     | 51       | 1.59%   |
| 32/9    | 17       | 0.53%   |
| 3/2     | 16       | 0.5%    |
| 1.00    | 8        | 0.25%   |
| 6/5     | 6        | 0.19%   |
| 2.12    | 2        | 0.06%   |
| 1.96    | 2        | 0.06%   |
| 0.56    | 2        | 0.06%   |
| 2.00    | 1        | 0.03%   |
| 0.89    | 1        | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1087     | 32.12%  |
| 301-350        | 489      | 14.45%  |
| 151-200        | 448      | 13.24%  |
| 351-500        | 338      | 9.99%   |
| Unknown        | 248      | 7.33%   |
| 251-300        | 199      | 5.88%   |
| More than 1000 | 198      | 5.85%   |
| 141-150        | 183      | 5.41%   |
| 501-1000       | 121      | 3.58%   |
| 101-110        | 40       | 1.18%   |
| 131-140        | 9        | 0.27%   |
| 111-120        | 9        | 0.27%   |
| 71-80          | 7        | 0.21%   |
| 81-90          | 3        | 0.09%   |
| 121-130        | 2        | 0.06%   |
| 91-100         | 2        | 0.06%   |
| 41-50          | 1        | 0.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 2025     | 62.42%  |
| 101-120       | 560      | 17.26%  |
| Unknown       | 248      | 7.64%   |
| 1-50          | 177      | 5.46%   |
| 121-160       | 158      | 4.87%   |
| 161-240       | 75       | 2.31%   |
| More than 240 | 1        | 0.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2583     | 74.05%  |
| 2     | 551      | 15.8%   |
| 0     | 281      | 8.06%   |
| 3     | 63       | 1.81%   |
| 4     | 8        | 0.23%   |
| 6     | 1        | 0.03%   |
| 5     | 1        | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 2043     | 42.13%  |
| Intel                           | 1593     | 32.85%  |
| Qualcomm Atheros                | 249      | 5.14%   |
| Broadcom                        | 140      | 2.89%   |
| Ralink Technology               | 102      | 2.1%    |
| TP-Link                         | 101      | 2.08%   |
| Nvidia                          | 65       | 1.34%   |
| Ralink                          | 56       | 1.15%   |
| MediaTek                        | 51       | 1.05%   |
| NetGear                         | 32       | 0.66%   |
| Broadcom Limited                | 32       | 0.66%   |
| Aquantia                        | 30       | 0.62%   |
| Marvell Technology Group        | 29       | 0.6%    |
| Microsoft                       | 23       | 0.47%   |
| Samsung Electronics             | 22       | 0.45%   |
| Qualcomm Atheros Communications | 22       | 0.45%   |
| ASIX Electronics                | 22       | 0.45%   |
| D-Link System                   | 21       | 0.43%   |
| D-Link                          | 17       | 0.35%   |
| Xiaomi                          | 15       | 0.31%   |
| ASUSTek Computer                | 15       | 0.31%   |
| Edimax Technology               | 13       | 0.27%   |
| Linksys                         | 11       | 0.23%   |
| IMC Networks                    | 10       | 0.21%   |
| DisplayLink                     | 9        | 0.19%   |
| Sitecom Europe                  | 6        | 0.12%   |
| Qualcomm                        | 6        | 0.12%   |
| Belkin Components               | 6        | 0.12%   |
| AVM                             | 5        | 0.1%    |
| ZyDAS                           | 4        | 0.08%   |
| Wilocity                        | 4        | 0.08%   |
| VIA Technologies                | 4        | 0.08%   |
| OPPO Electronics                | 4        | 0.08%   |
| JMicron Technology              | 4        | 0.08%   |
| Huawei Technologies             | 4        | 0.08%   |
| Texas Instruments               | 3        | 0.06%   |
| Mellanox Technologies           | 3        | 0.06%   |
| ICS Advent                      | 3        | 0.06%   |
| Dresden Elektronik              | 3        | 0.06%   |
| Arduino SA                      | 3        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1588     | 28.67%  |
| Realtek RTL8125 2.5GbE Controller                                 | 227      | 4.1%    |
| Intel I211 Gigabit Network Connection                             | 175      | 3.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 165      | 2.98%   |
| Intel Wi-Fi 6 AX200                                               | 158      | 2.85%   |
| Intel Ethernet Connection I217-LM                                 | 123      | 2.22%   |
| Intel Ethernet Connection (2) I219-V                              | 121      | 2.18%   |
| Intel Ethernet Controller I225-V                                  | 117      | 2.11%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 72       | 1.3%    |
| Intel 82579V Gigabit Network Connection                           | 68       | 1.23%   |
| Intel Ethernet Connection (7) I219-V                              | 64       | 1.16%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 57       | 1.03%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 56       | 1.01%   |
| Realtek 802.11ac NIC                                              | 56       | 1.01%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 52       | 0.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 51       | 0.92%   |
| Intel Ethernet Connection (2) I219-LM                             | 50       | 0.9%    |
| Intel Ethernet Connection I217-V                                  | 48       | 0.87%   |
| Intel Ethernet Connection (2) I218-V                              | 45       | 0.81%   |
| Ralink MT7601U Wireless Adapter                                   | 40       | 0.72%   |
| Intel 82574L Gigabit Network Connection                           | 39       | 0.7%    |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 38       | 0.69%   |
| Intel Wireless-AC 9260                                            | 34       | 0.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 34       | 0.61%   |
| Nvidia MCP61 Ethernet                                             | 32       | 0.58%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 32       | 0.58%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 30       | 0.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 27       | 0.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 27       | 0.49%   |
| Intel Wireless 7265                                               | 26       | 0.47%   |
| Intel Wireless 7260                                               | 25       | 0.45%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 25       | 0.45%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 23       | 0.42%   |
| Intel I210 Gigabit Network Connection                             | 23       | 0.42%   |
| Intel Ethernet Connection (7) I219-LM                             | 23       | 0.42%   |
| Intel Ethernet Connection (5) I219-LM                             | 23       | 0.42%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 23       | 0.42%   |
| Intel Wireless 3165                                               | 22       | 0.4%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 21       | 0.38%   |
| Ralink RT5370 Wireless Adapter                                    | 20       | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 570      | 34.07%  |
| Realtek Semiconductor                 | 389      | 23.25%  |
| Qualcomm Atheros                      | 144      | 8.61%   |
| Ralink Technology                     | 102      | 6.1%    |
| TP-Link                               | 99       | 5.92%   |
| Ralink                                | 56       | 3.35%   |
| Broadcom                              | 55       | 3.29%   |
| MediaTek                              | 46       | 2.75%   |
| NetGear                               | 32       | 1.91%   |
| Microsoft                             | 23       | 1.37%   |
| Qualcomm Atheros Communications       | 22       | 1.32%   |
| D-Link                                | 17       | 1.02%   |
| D-Link System                         | 16       | 0.96%   |
| Broadcom Limited                      | 15       | 0.9%    |
| ASUSTek Computer                      | 15       | 0.9%    |
| Edimax Technology                     | 13       | 0.78%   |
| IMC Networks                          | 10       | 0.6%    |
| Linksys                               | 9        | 0.54%   |
| Sitecom Europe                        | 6        | 0.36%   |
| Belkin Components                     | 6        | 0.36%   |
| AVM                                   | 5        | 0.3%    |
| ZyDAS                                 | 4        | 0.24%   |
| Wilocity                              | 4        | 0.24%   |
| Micro Star International              | 2        | 0.12%   |
| Mercucys                              | 2        | 0.12%   |
| Encore Electronics                    | 2        | 0.12%   |
| BUFFALO                               | 2        | 0.12%   |
| Sagem                                 | 1        | 0.06%   |
| Philips (or NXP)                      | 1        | 0.06%   |
| LSI                                   | 1        | 0.06%   |
| Guillemot                             | 1        | 0.06%   |
| Gemtek                                | 1        | 0.06%   |
| Dell                                  | 1        | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                        | 158      | 9.32%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 72       | 4.25%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 56       | 3.3%    |
| Realtek 802.11ac NIC                                       | 56       | 3.3%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 52       | 3.07%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 51       | 3.01%   |
| Ralink MT7601U Wireless Adapter                            | 40       | 2.36%   |
| Intel Alder Lake-S PCH CNVi WiFi                           | 38       | 2.24%   |
| Intel Wireless-AC 9260                                     | 34       | 2%      |
| Intel Cannon Lake PCH CNVi WiFi                            | 34       | 2%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 27       | 1.59%   |
| Intel Wireless 7265                                        | 26       | 1.53%   |
| Intel Wireless 7260                                        | 25       | 1.47%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter         | 25       | 1.47%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 23       | 1.36%   |
| Intel Wireless 3165                                        | 22       | 1.3%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter           | 21       | 1.24%   |
| Ralink RT5370 Wireless Adapter                             | 20       | 1.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 20       | 1.18%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                    | 20       | 1.18%   |
| Intel Comet Lake PCH CNVi WiFi                             | 20       | 1.18%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 19       | 1.12%   |
| Qualcomm Atheros AR9271 802.11n                            | 19       | 1.12%   |
| Intel Tiger Lake PCH CNVi WiFi                             | 18       | 1.06%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 17       | 1%      |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                 | 17       | 1%      |
| Realtek RTL8192CE PCIe Wireless Network Adapter            | 17       | 1%      |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter      | 17       | 1%      |
| Intel Wireless 8260                                        | 17       | 1%      |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                | 16       | 0.94%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]               | 15       | 0.88%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                        | 14       | 0.83%   |
| Ralink RT2870/RT3070 Wireless Adapter                      | 14       | 0.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 14       | 0.83%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 14       | 0.83%   |
| TP-Link 802.11ac WLAN Adapter                              | 13       | 0.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 13       | 0.77%   |
| Microsoft Xbox Wireless Adapter for Windows                | 13       | 0.77%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                     | 12       | 0.71%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                  | 12       | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1904     | 51.85%  |
| Intel                                  | 1299     | 35.38%  |
| Qualcomm Atheros                       | 119      | 3.24%   |
| Broadcom                               | 86       | 2.34%   |
| Nvidia                                 | 65       | 1.77%   |
| Aquantia                               | 30       | 0.82%   |
| Marvell Technology Group               | 29       | 0.79%   |
| ASIX Electronics                       | 22       | 0.6%    |
| Broadcom Limited                       | 17       | 0.46%   |
| Samsung Electronics                    | 16       | 0.44%   |
| Xiaomi                                 | 15       | 0.41%   |
| DisplayLink                            | 9        | 0.25%   |
| Qualcomm                               | 6        | 0.16%   |
| D-Link System                          | 5        | 0.14%   |
| VIA Technologies                       | 4        | 0.11%   |
| OPPO Electronics                       | 4        | 0.11%   |
| MediaTek                               | 4        | 0.11%   |
| JMicron Technology                     | 4        | 0.11%   |
| ICS Advent                             | 3        | 0.08%   |
| Huawei Technologies                    | 3        | 0.08%   |
| TP-Link                                | 2        | 0.05%   |
| Tehuti Networks                        | 2        | 0.05%   |
| Sundance Technology Inc / IC Plus      | 2        | 0.05%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.05%   |
| Mellanox Technologies                  | 2        | 0.05%   |
| Linksys                                | 2        | 0.05%   |
| Google                                 | 2        | 0.05%   |
| Chelsio Communications                 | 2        | 0.05%   |
| Apple                                  | 2        | 0.05%   |
| American Megatrends                    | 2        | 0.05%   |
| Vimtron Electronics                    | 1        | 0.03%   |
| Spreadtrum Communications              | 1        | 0.03%   |
| Prolific Technology                    | 1        | 0.03%   |
| Motorola PCS                           | 1        | 0.03%   |
| MosChip Semiconductor                  | 1        | 0.03%   |
| LG Electronics                         | 1        | 0.03%   |
| Compal Electronics                     | 1        | 0.03%   |
| 3Com                                   | 1        | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1588     | 41.81%  |
| Realtek RTL8125 2.5GbE Controller                                 | 227      | 5.98%   |
| Intel I211 Gigabit Network Connection                             | 175      | 4.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 165      | 4.34%   |
| Intel Ethernet Connection I217-LM                                 | 123      | 3.24%   |
| Intel Ethernet Connection (2) I219-V                              | 121      | 3.19%   |
| Intel Ethernet Controller I225-V                                  | 117      | 3.08%   |
| Intel 82579V Gigabit Network Connection                           | 68       | 1.79%   |
| Intel Ethernet Connection (7) I219-V                              | 64       | 1.69%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 57       | 1.5%    |
| Intel Ethernet Connection (2) I219-LM                             | 50       | 1.32%   |
| Intel Ethernet Connection I217-V                                  | 48       | 1.26%   |
| Intel Ethernet Connection (2) I218-V                              | 45       | 1.18%   |
| Intel 82574L Gigabit Network Connection                           | 39       | 1.03%   |
| Nvidia MCP61 Ethernet                                             | 32       | 0.84%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 32       | 0.84%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 30       | 0.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 27       | 0.71%   |
| Intel I210 Gigabit Network Connection                             | 23       | 0.61%   |
| Intel Ethernet Connection (7) I219-LM                             | 23       | 0.61%   |
| Intel Ethernet Connection (5) I219-LM                             | 23       | 0.61%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 23       | 0.61%   |
| Intel 82578DC Gigabit Network Connection                          | 20       | 0.53%   |
| Intel Ethernet Connection (14) I219-V                             | 19       | 0.5%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 18       | 0.47%   |
| ASIX AX88179 Gigabit Ethernet                                     | 17       | 0.45%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 16       | 0.42%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 16       | 0.42%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 16       | 0.42%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 16       | 0.42%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 15       | 0.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 14       | 0.37%   |
| Intel Ethernet Controller X550                                    | 14       | 0.37%   |
| Intel Ethernet Connection (11) I219-V                             | 14       | 0.37%   |
| Intel 82578DM Gigabit Network Connection                          | 14       | 0.37%   |
| Intel Ethernet Connection (2) I218-LM                             | 13       | 0.34%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 13       | 0.34%   |
| Intel Ethernet Connection (17) I219-V                             | 12       | 0.32%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 11       | 0.29%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 11       | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3405     | 67.96%  |
| WiFi     | 1561     | 31.16%  |
| Modem    | 39       | 0.78%   |
| Unknown  | 5        | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2720     | 75.83%  |
| WiFi     | 865      | 24.11%  |
| Modem    | 2        | 0.06%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2165     | 62.75%  |
| 2     | 1072     | 31.07%  |
| 3     | 154      | 4.46%   |
| 4     | 26       | 0.75%   |
| 0     | 21       | 0.61%   |
| 5     | 8        | 0.23%   |
| 7     | 2        | 0.06%   |
| 8     | 1        | 0.03%   |
| 6     | 1        | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2324     | 67.25%  |
| Yes  | 1132     | 32.75%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 522      | 45.67%  |
| Cambridge Silicon Radio         | 227      | 19.86%  |
| Realtek Semiconductor           | 81       | 7.09%   |
| ASUSTek Computer                | 75       | 6.56%   |
| Qualcomm Atheros Communications | 49       | 4.29%   |
| Broadcom                        | 40       | 3.5%    |
| IMC Networks                    | 27       | 2.36%   |
| MediaTek                        | 23       | 2.01%   |
| Apple                           | 19       | 1.66%   |
| TP-Link                         | 16       | 1.4%    |
| Lite-On Technology              | 16       | 1.4%    |
| Foxconn / Hon Hai               | 6        | 0.52%   |
| Belkin Components               | 6        | 0.52%   |
| Logitech                        | 4        | 0.35%   |
| Edimax Technology               | 4        | 0.35%   |
| Dell                            | 4        | 0.35%   |
| Realtek                         | 3        | 0.26%   |
| Micro Star International        | 3        | 0.26%   |
| Integrated System Solution      | 2        | 0.17%   |
| Hewlett-Packard                 | 2        | 0.17%   |
| D-Link System                   | 2        | 0.17%   |
| Conwise Technology              | 2        | 0.17%   |
| Unknown                         | 2        | 0.17%   |
| TRENDnet                        | 1        | 0.09%   |
| Toshiba                         | 1        | 0.09%   |
| Ralink                          | 1        | 0.09%   |
| Mobile Action Technology        | 1        | 0.09%   |
| ISSC                            | 1        | 0.09%   |
| HTC (High Tech Computer)        | 1        | 0.09%   |
| Dynex                           | 1        | 0.09%   |
| Actions                         | 1        | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 227      | 19.83%  |
| Intel AX200 Bluetooth                                 | 134      | 11.7%   |
| Intel Bluetooth wireless interface                    | 102      | 8.91%   |
| Intel AX210 Bluetooth                                 | 71       | 6.2%    |
| Intel AX201 Bluetooth                                 | 64       | 5.59%   |
| Realtek Bluetooth Radio                               | 59       | 5.15%   |
| Intel Wireless-AC 3168 Bluetooth                      | 50       | 4.37%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 40       | 3.49%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 33       | 2.88%   |
| ASUS ASUS USB-BT500                                   | 25       | 2.18%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 24       | 2.1%    |
| MediaTek Wireless_Device                              | 23       | 2.01%   |
| Intel Bluetooth Device                                | 21       | 1.83%   |
| Qualcomm Atheros  Bluetooth Device                    | 19       | 1.66%   |
| TP-Link UB500 Adapter                                 | 16       | 1.4%    |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 16       | 1.4%    |
| IMC Networks Bluetooth Radio                          | 14       | 1.22%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 13       | 1.14%   |
| Realtek  Bluetooth 4.2 Adapter                        | 12       | 1.05%   |
| ASUS Bluetooth Radio                                  | 11       | 0.96%   |
| Lite-On Bluetooth Device                              | 9        | 0.79%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 9        | 0.79%   |
| IMC Networks Wireless_Device                          | 8        | 0.7%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 8        | 0.7%    |
| Apple Bluetooth USB Host Controller                   | 8        | 0.7%    |
| Realtek RTL8821A Bluetooth                            | 7        | 0.61%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 7        | 0.61%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 6        | 0.52%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 5        | 0.44%   |
| ASUS Qualcomm Bluetooth 4.1                           | 5        | 0.44%   |
| ASUS Bluetooth Device                                 | 5        | 0.44%   |
| ASUS BCM20702A0                                       | 5        | 0.44%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 4        | 0.35%   |
| Logitech BT Mini-Receiver (HCI mode)                  | 4        | 0.35%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 4        | 0.35%   |
| Foxconn / Hon Hai Wireless_Device                     | 4        | 0.35%   |
| Realtek Bluetooth Radio                               | 3        | 0.26%   |
| Micro Star International Bluetooth Device             | 3        | 0.26%   |
| IMC Networks Bluetooth Device                         | 3        | 0.26%   |
| Edimax Bluetooth Adapter                              | 3        | 0.26%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 2217     | 38.81%  |
| Nvidia                                       | 1444     | 25.28%  |
| AMD                                          | 1374     | 24.05%  |
| C-Media Electronics                          | 115      | 2.01%   |
| Logitech                                     | 59       | 1.03%   |
| Creative Labs                                | 55       | 0.96%   |
| ASUSTek Computer                             | 38       | 0.67%   |
| GN Netcom                                    | 31       | 0.54%   |
| Micro Star International                     | 25       | 0.44%   |
| Texas Instruments                            | 24       | 0.42%   |
| Kingston Technology                          | 20       | 0.35%   |
| JMTek                                        | 18       | 0.32%   |
| Razer USA                                    | 17       | 0.3%    |
| Creative Technology                          | 15       | 0.26%   |
| SteelSeries ApS                              | 14       | 0.25%   |
| Generalplus Technology                       | 14       | 0.25%   |
| Corsair                                      | 14       | 0.25%   |
| Focusrite-Novation                           | 11       | 0.19%   |
| Plantronics                                  | 9        | 0.16%   |
| Tenx Technology                              | 8        | 0.14%   |
| VIA Technologies                             | 7        | 0.12%   |
| Giga-Byte Technology                         | 7        | 0.12%   |
| Blue Microphones                             | 7        | 0.12%   |
| Zoran Co. Personal Media Division (Nogatech) | 6        | 0.11%   |
| Sennheiser Communications                    | 6        | 0.11%   |
| M-Audio                                      | 6        | 0.11%   |
| Realtek Semiconductor                        | 5        | 0.09%   |
| KTMicro                                      | 5        | 0.09%   |
| Jieli Technology                             | 5        | 0.09%   |
| Hewlett-Packard                              | 5        | 0.09%   |
| Dell                                         | 5        | 0.09%   |
| Astro Gaming                                 | 5        | 0.09%   |
| Apple                                        | 5        | 0.09%   |
| Sony                                         | 4        | 0.07%   |
| Samson Technologies                          | 4        | 0.07%   |
| Scarlett                                     | 3        | 0.05%   |
| RODE Microphones                             | 3        | 0.05%   |
| Microsoft                                    | 3        | 0.05%   |
| Cambridge Silicon Radio                      | 3        | 0.05%   |
| Bose                                         | 3        | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 361      | 5.48%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 327      | 4.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 249      | 3.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 240      | 3.64%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 216      | 3.28%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 202      | 3.07%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 198      | 3.01%   |
| AMD Family 17h/19h HD Audio Controller                                     | 178      | 2.7%    |
| Intel 200 Series PCH HD Audio                                              | 174      | 2.64%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 132      | 2%      |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 128      | 1.94%   |
| Intel Cannon Lake PCH cAVS                                                 | 126      | 1.91%   |
| AMD FCH Azalia Controller                                                  | 119      | 1.81%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 115      | 1.75%   |
| Nvidia GP107GL High Definition Audio Controller                            | 100      | 1.52%   |
| Intel Alder Lake-S HD Audio Controller                                     | 91       | 1.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 91       | 1.38%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 89       | 1.35%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 87       | 1.32%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 82       | 1.24%   |
| Nvidia GA104 High Definition Audio Controller                              | 81       | 1.23%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 81       | 1.23%   |
| Nvidia High Definition Audio Controller                                    | 80       | 1.21%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 80       | 1.21%   |
| Nvidia GA102 High Definition Audio Controller                              | 72       | 1.09%   |
| Nvidia GP106 High Definition Audio Controller                              | 71       | 1.08%   |
| Nvidia GP104 High Definition Audio Controller                              | 71       | 1.08%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 71       | 1.08%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 67       | 1.02%   |
| Nvidia TU116 High Definition Audio Controller                              | 66       | 1%      |
| Intel Tiger Lake-H HD Audio Controller                                     | 66       | 1%      |
| Intel C610/X99 series chipset HD Audio Controller                          | 63       | 0.96%   |
| Nvidia GK107 HDMI Audio Controller                                         | 58       | 0.88%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 56       | 0.85%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 53       | 0.8%    |
| Nvidia GF119 HDMI Audio Controller                                         | 53       | 0.8%    |
| Nvidia TU106 High Definition Audio Controller                              | 52       | 0.79%   |
| Nvidia GA106 High Definition Audio Controller                              | 52       | 0.79%   |
| Nvidia GP108 High Definition Audio Controller                              | 50       | 0.76%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 48       | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 341      | 18.92%  |
| Corsair                      | 267      | 14.82%  |
| Samsung Electronics          | 189      | 10.49%  |
| SK hynix                     | 176      | 9.77%   |
| G.Skill                      | 146      | 8.1%    |
| Unknown                      | 143      | 7.94%   |
| Crucial                      | 141      | 7.82%   |
| Micron Technology            | 90       | 4.99%   |
| A-DATA Technology            | 47       | 2.61%   |
| Team                         | 35       | 1.94%   |
| Unknown                      | 31       | 1.72%   |
| Patriot                      | 21       | 1.17%   |
| Ramaxel Technology           | 16       | 0.89%   |
| Nanya Technology             | 15       | 0.83%   |
| Unknown (ABCD)               | 12       | 0.67%   |
| Transcend                    | 8        | 0.44%   |
| AMD                          | 8        | 0.44%   |
| Smart                        | 7        | 0.39%   |
| PNY                          | 7        | 0.39%   |
| Elpida                       | 7        | 0.39%   |
| Apacer                       | 7        | 0.39%   |
| GOODRAM                      | 6        | 0.33%   |
| Silicon Power                | 5        | 0.28%   |
| Timetec                      | 4        | 0.22%   |
| KETECH                       | 4        | 0.22%   |
| Hewlett-Packard              | 4        | 0.22%   |
| GeIL                         | 4        | 0.22%   |
| Avant                        | 4        | 0.22%   |
| ASint Technology             | 4        | 0.22%   |
| Asgard                       | 4        | 0.22%   |
| Patriot Memory (PDP Systems) | 3        | 0.17%   |
| KLEVV                        | 3        | 0.17%   |
| Kingmax                      | 3        | 0.17%   |
| Atermiter                    | 3        | 0.17%   |
| Super Talent                 | 2        | 0.11%   |
| Qumo                         | 2        | 0.11%   |
| Netac                        | 2        | 0.11%   |
| Neo Forza                    | 2        | 0.11%   |
| ZION                         | 1        | 0.06%   |
| V-Color                      | 1        | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown                                                        | 31       | 1.59%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s       | 19       | 0.98%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s          | 19       | 0.98%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 13       | 0.67%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s            | 13       | 0.67%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                    | 13       | 0.67%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 12       | 0.62%   |
| Kingston RAM 9905734-415.A00G 16GB DIMM DDR4 3200MT/s          | 12       | 0.62%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s           | 12       | 0.62%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s            | 12       | 0.62%   |
| SK hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s        | 11       | 0.57%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s         | 11       | 0.57%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 10       | 0.51%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s             | 10       | 0.51%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 10       | 0.51%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s           | 10       | 0.51%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 9        | 0.46%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 9        | 0.46%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s           | 9        | 0.46%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s          | 9        | 0.46%   |
| Kingston RAM 9905734-016.A00G 16GB DIMM DDR4 3200MT/s          | 9        | 0.46%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s            | 8        | 0.41%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 8        | 0.41%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s            | 8        | 0.41%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s         | 8        | 0.41%   |
| Corsair RAM CM4X16GC3000C16K4D 16GB DIMM DDR4 3000MT/s         | 8        | 0.41%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s           | 7        | 0.36%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s            | 7        | 0.36%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s         | 7        | 0.36%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 6        | 0.31%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                           | 6        | 0.31%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3733MT/s             | 6        | 0.31%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s           | 6        | 0.31%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 6        | 0.31%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 6        | 0.31%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s            | 6        | 0.31%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3266MT/s             | 6        | 0.31%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s            | 6        | 0.31%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s              | 6        | 0.31%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s            | 6        | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 862      | 53.88%  |
| DDR3    | 504      | 31.5%   |
| Unknown | 60       | 3.75%   |
| DDR5    | 52       | 3.25%   |
| SDRAM   | 47       | 2.94%   |
| DDR2    | 37       | 2.31%   |
| LPDDR4  | 21       | 1.31%   |
| DDR     | 11       | 0.69%   |
| LPDDR3  | 4        | 0.25%   |
| DRAM    | 2        | 0.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 1442     | 91.91%  |
| SODIMM       | 109      | 6.95%   |
| RIMM         | 9        | 0.57%   |
| Row Of Chips | 7        | 0.45%   |
| FB-DIMM      | 1        | 0.06%   |
| Unknown      | 1        | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size   | Desktops | Percent |
|--------|----------|---------|
| 8192   | 629      | 37.15%  |
| 16384  | 366      | 21.62%  |
| 4096   | 362      | 21.38%  |
| 2048   | 163      | 9.63%   |
| 32768  | 138      | 8.15%   |
| 1024   | 30       | 1.77%   |
| 65536  | 3        | 0.18%   |
| 131072 | 1        | 0.06%   |
| 512    | 1        | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 308      | 17.49%  |
| 3200    | 229      | 13%     |
| 1333    | 166      | 9.43%   |
| 2400    | 139      | 7.89%   |
| 3600    | 129      | 7.33%   |
| 2667    | 113      | 6.42%   |
| 2133    | 75       | 4.26%   |
| 3000    | 47       | 2.67%   |
| 1867    | 44       | 2.5%    |
| 800     | 38       | 2.16%   |
| 2666    | 34       | 1.93%   |
| 4800    | 25       | 1.42%   |
| 2933    | 25       | 1.42%   |
| 3800    | 24       | 1.36%   |
| 3400    | 24       | 1.36%   |
| 667     | 24       | 1.36%   |
| 1800    | 22       | 1.25%   |
| 3733    | 19       | 1.08%   |
| 3533    | 19       | 1.08%   |
| 1066    | 17       | 0.97%   |
| 1866    | 16       | 0.91%   |
| 3266    | 12       | 0.68%   |
| Unknown | 12       | 0.68%   |
| 3534    | 11       | 0.62%   |
| 1067    | 11       | 0.62%   |
| 3466    | 10       | 0.57%   |
| 2800    | 9        | 0.51%   |
| 5600    | 8        | 0.45%   |
| 5200    | 8        | 0.45%   |
| 3866    | 8        | 0.45%   |
| 3666    | 8        | 0.45%   |
| 3500    | 8        | 0.45%   |
| 2000    | 7        | 0.4%    |
| 400     | 7        | 0.4%    |
| 3933    | 6        | 0.34%   |
| 5808    | 5        | 0.28%   |
| 3334    | 5        | 0.28%   |
| 2733    | 5        | 0.28%   |
| 2465    | 5        | 0.28%   |
| 2448    | 5        | 0.28%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 55       | 31.79%  |
| Brother Industries    | 39       | 22.54%  |
| Canon                 | 21       | 12.14%  |
| Samsung Electronics   | 20       | 11.56%  |
| Seiko Epson           | 18       | 10.4%   |
| Prolific Technology   | 3        | 1.73%   |
| Lexmark International | 3        | 1.73%   |
| Dymo-CoStar           | 3        | 1.73%   |
| STMicroelectronics    | 2        | 1.16%   |
| QinHeng Electronics   | 2        | 1.16%   |
| Zebra                 | 1        | 0.58%   |
| Pantum                | 1        | 0.58%   |
| Oki Data              | 1        | 0.58%   |
| Kyocera               | 1        | 0.58%   |
| Fuji Xerox            | 1        | 0.58%   |
| BESTEASY              | 1        | 0.58%   |
| Apple                 | 1        | 0.58%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Seiko Epson L220 Series                                   | 3        | 1.69%   |
| Seiko Epson ET-2720 Series                                | 3        | 1.69%   |
| Samsung Composite Device                                  | 3        | 1.69%   |
| Prolific PL2305 Parallel Port                             | 3        | 1.69%   |
| HP OfficeJet 3830 series                                  | 3        | 1.69%   |
| HP DeskJet 2130 series                                    | 3        | 1.69%   |
| Brother Printer                                           | 3        | 1.69%   |
| Brother HL-1440 Laser Printer                             | 3        | 1.69%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2        | 1.13%   |
| Seiko Epson XP-2100 Series                                | 2        | 1.13%   |
| Seiko Epson ET-2810 Series                                | 2        | 1.13%   |
| Samsung ML-216x Series Laser Printer                      | 2        | 1.13%   |
| Samsung M2070 Series                                      | 2        | 1.13%   |
| Samsung C460 Series                                       | 2        | 1.13%   |
| QinHeng CH340S                                            | 2        | 1.13%   |
| HP OfficeJet Pro 8020 series                              | 2        | 1.13%   |
| HP OfficeJet 5600 (USBHUB)                                | 2        | 1.13%   |
| HP Officejet 4500 G510n-z                                 | 2        | 1.13%   |
| HP LaserJet P1005                                         | 2        | 1.13%   |
| HP LaserJet M14-M17                                       | 2        | 1.13%   |
| HP LaserJet 4250                                          | 2        | 1.13%   |
| HP LaserJet 3015                                          | 2        | 1.13%   |
| HP DeskJet 4100 series                                    | 2        | 1.13%   |
| HP DeskJet 3700 series                                    | 2        | 1.13%   |
| HP DeskJet 2620 All-in-One Printer                        | 2        | 1.13%   |
| HP DeskJet 2300 series                                    | 2        | 1.13%   |
| HP DeskJet 1110 series                                    | 2        | 1.13%   |
| Dymo-CoStar LabelWriter 400                               | 2        | 1.13%   |
| Canon TS3100 series                                       | 2        | 1.13%   |
| Canon LBP2900                                             | 2        | 1.13%   |
| Brother HL-L2375DW series                                 | 2        | 1.13%   |
| Brother HL-L2350DW series                                 | 2        | 1.13%   |
| Brother HL-2270DW Laser Printer                           | 2        | 1.13%   |
| Brother DCP-J105                                          | 2        | 1.13%   |
| Brother DCP-7055 scanner/printer                          | 2        | 1.13%   |
| Brother DCP-1610W                                         | 2        | 1.13%   |
| Zebra ZP 450 Printer                                      | 1        | 0.56%   |
| Seiko Epson WF-3520 Series                                | 1        | 0.56%   |
| Seiko Epson WF-2840 Series                                | 1        | 0.56%   |
| Seiko Epson WF-2510 Series                                | 1        | 0.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 19       | 59.38%  |
| Seiko Epson                 | 6        | 18.75%  |
| Hewlett-Packard             | 6        | 18.75%  |
| Acer Peripherals (now BenQ) | 1        | 3.13%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 120                             | 5        | 15.63%  |
| Canon CanoScan LiDE 100                             | 3        | 9.38%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO] | 2        | 6.25%   |
| Canon CanoScan LiDE 220                             | 2        | 6.25%   |
| Canon CanoScan LiDE 110                             | 2        | 6.25%   |
| Seiko Epson GT-X770 [Perfection V500]               | 1        | 3.13%   |
| Seiko Epson GT-F700 [Perfection V350]               | 1        | 3.13%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]  | 1        | 3.13%   |
| Seiko Epson GT-7700U [Perfection 1240U]             | 1        | 3.13%   |
| HP Scanjet N6010                                    | 1        | 3.13%   |
| HP ScanJet G4010                                    | 1        | 3.13%   |
| HP Scanjet G2710                                    | 1        | 3.13%   |
| HP ScanJet 4850C/4890C                              | 1        | 3.13%   |
| HP ScanJet 3970c                                    | 1        | 3.13%   |
| HP ScanJet 3400cse                                  | 1        | 3.13%   |
| Canon CanoScan N670U/N676U/LiDE 20                  | 1        | 3.13%   |
| Canon CanoScan N1240U/LiDE 30                       | 1        | 3.13%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40              | 1        | 3.13%   |
| Canon CanoScan LIDE 25                              | 1        | 3.13%   |
| Canon CanoScan LiDE 200                             | 1        | 3.13%   |
| Canon CanoScan 9000F Mark II                        | 1        | 3.13%   |
| Canon CanoScan 4200F                                | 1        | 3.13%   |
| Acer Peripherals (now BenQ) Benq 5000               | 1        | 3.13%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 235      | 36.15%  |
| Microdia                      | 58       | 8.92%   |
| Microsoft                     | 45       | 6.92%   |
| Sunplus Innovation Technology | 29       | 4.46%   |
| Apple                         | 24       | 3.69%   |
| Samsung Electronics           | 21       | 3.23%   |
| Realtek Semiconductor         | 18       | 2.77%   |
| Generalplus Technology        | 17       | 2.62%   |
| ARC International             | 17       | 2.62%   |
| Z-Star Microelectronics       | 16       | 2.46%   |
| Chicony Electronics           | 14       | 2.15%   |
| Trust                         | 8        | 1.23%   |
| Creative Technology           | 8        | 1.23%   |
| 2M UVC CAMERA                 | 8        | 1.23%   |
| Razer USA                     | 6        | 0.92%   |
| MacroSilicon                  | 6        | 0.92%   |
| GEMBIRD                       | 6        | 0.92%   |
| Cubeternet                    | 6        | 0.92%   |
| KYE Systems (Mouse Systems)   | 5        | 0.77%   |
| Sonix Technology              | 4        | 0.62%   |
| Jieli Technology              | 4        | 0.62%   |
| Hewlett-Packard               | 4        | 0.62%   |
| AVerMedia Technologies        | 4        | 0.62%   |
| YGTek                         | 3        | 0.46%   |
| WaveRider Communications      | 3        | 0.46%   |
| Philips (or NXP)              | 3        | 0.46%   |
| Linux Foundation              | 3        | 0.46%   |
| IMC Networks                  | 3        | 0.46%   |
| Aveo Technology               | 3        | 0.46%   |
| Asuscom Network               | 3        | 0.46%   |
| Alcor Micro                   | 3        | 0.46%   |
| Sunplus IT                    | 2        | 0.31%   |
| Quanta                        | 2        | 0.31%   |
| Pixart Imaging                | 2        | 0.31%   |
| OPPO Electronics              | 2        | 0.31%   |
| OmniVision Technologies       | 2        | 0.31%   |
| Magic Control Technology      | 2        | 0.31%   |
| Huawei Technologies           | 2        | 0.31%   |
| GenesysLogic Technology       | 2        | 0.31%   |
| Genesys Logic                 | 2        | 0.31%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 58       | 8.9%    |
| Logitech HD Pro Webcam C920                       | 35       | 5.37%   |
| Logitech C922 Pro Stream Webcam                   | 24       | 3.68%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                   | 22       | 3.37%   |
| Samsung Galaxy A5 (MTP)                           | 20       | 3.07%   |
| Microdia Webcam Vitade AF                         | 19       | 2.91%   |
| ARC International Camera                          | 17       | 2.61%   |
| Logitech HD Webcam C615                           | 13       | 1.99%   |
| Logitech C920 PRO HD Webcam                       | 13       | 1.99%   |
| Microsoft LifeCam HD-3000                         | 12       | 1.84%   |
| Sunplus Full HD webcam                            | 9        | 1.38%   |
| Logitech Webcam C170                              | 9        | 1.38%   |
| Generalplus GENERAL WEBCAM                        | 9        | 1.38%   |
| Sunplus FHD Camera Microphone                     | 8        | 1.23%   |
| Microsoft LifeCam Cinema                          | 8        | 1.23%   |
| Microdia REDRAGON Live Camera Audio               | 8        | 1.23%   |
| Microdia Camera                                   | 8        | 1.23%   |
| Logitech Webcam C310                              | 8        | 1.23%   |
| Logitech HD Webcam C525                           | 8        | 1.23%   |
| 2M UVC CAMERA NexiGo N660 FHD Webcam              | 8        | 1.23%   |
| Logitech BRIO Ultra HD Webcam                     | 7        | 1.07%   |
| Microdia Sonix USB 2.0 Camera                     | 6        | 0.92%   |
| Microdia Integrated Camera                        | 6        | 0.92%   |
| Chicony HP High Definition 1MP Webcam             | 6        | 0.92%   |
| Z-Star Venus USB2.0 Camera                        | 5        | 0.77%   |
| Realtek USB Camera                                | 5        | 0.77%   |
| Realtek FULL HD 1080P Webcam                      | 5        | 0.77%   |
| MacroSilicon USB Video                            | 5        | 0.77%   |
| Logitech Webcam C925e                             | 5        | 0.77%   |
| Razer USA Gaming Webcam [Kiyo]                    | 4        | 0.61%   |
| Microsoft LifeCam VX-500 [1357]                   | 4        | 0.61%   |
| Microsoft LifeCam Studio                          | 4        | 0.61%   |
| Microdia USB 2.0 Camera                           | 4        | 0.61%   |
| Logitech StreamCam                                | 4        | 0.61%   |
| Logitech QuickCam Pro 9000                        | 4        | 0.61%   |
| Logitech QuickCam Communicate MP/S5500            | 4        | 0.61%   |
| Jieli USB PHY 2.0                                 | 4        | 0.61%   |
| Generalplus WEB CAM                               | 4        | 0.61%   |
| Generalplus 808 Camera #9 (web-cam mode)          | 4        | 0.61%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 4        | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Dell                  | 2        | 40%     |
| Microsoft             | 1        | 20%     |
| Elan Microelectronics | 1        | 20%     |
| DigitalPersona        | 1        | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Dell MS819 Wired Mouse With Fingerprint Reader | 2        | 40%     |
| Microsoft Fingerprint Reader                   | 1        | 20%     |
| Elan fingerprint sensor [FeinTech FPS00200]    | 1        | 20%     |
| DigitalPersona Fingerprint Reader              | 1        | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Advanced Card Systems     | 7        | 22.58%  |
| Realtek Semiconductor     | 4        | 12.9%   |
| Gemalto (was Gemplus)     | 4        | 12.9%   |
| SCM Microsystems          | 3        | 9.68%   |
| Chicony Electronics       | 3        | 9.68%   |
| Alcor Micro               | 3        | 9.68%   |
| Reiner SCT Kartensysteme  | 1        | 3.23%   |
| Lenovo                    | 1        | 3.23%   |
| Giesecke & Devrient       | 1        | 3.23%   |
| Fujitsu Siemens Computers | 1        | 3.23%   |
| Cherry                    | 1        | 3.23%   |
| BIT4ID                    | 1        | 3.23%   |
| Aladdin Knowledge Systems | 1        | 3.23%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface                          | 4        | 12.9%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 4        | 12.9%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                     | 3        | 9.68%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                       | 3        | 9.68%   |
| Advanced Card Systems ACR38 SmartCard Reader                               | 3        | 9.68%   |
| Alcor Micro AU9540 Smartcard Reader                                        | 2        | 6.45%   |
| Advanced Card Systems ACR122U                                              | 2        | 6.45%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 3.23%   |
| Lenovo Smartcard Keyboard                                                  | 1        | 3.23%   |
| Giesecke & Devrient StarSign CUT S                                         | 1        | 3.23%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                              | 1        | 3.23%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                | 1        | 3.23%   |
| BIT4ID miniLector EVO                                                      | 1        | 3.23%   |
| Alcor Micro Watchdata W 1981                                               | 1        | 3.23%   |
| Aladdin Knowledge Systems Token JC                                         | 1        | 3.23%   |
| Advanced Card Systems ACR39U                                               | 1        | 3.23%   |
| Advanced Card Systems ACR1281 1S Dual Reader                               | 1        | 3.23%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 2878     | 82.58%  |
| 1     | 508      | 14.58%  |
| 2     | 57       | 1.64%   |
| 3     | 22       | 0.63%   |
| 5     | 8        | 0.23%   |
| 4     | 8        | 0.23%   |
| 8     | 2        | 0.06%   |
| 7     | 1        | 0.03%   |
| 6     | 1        | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 265      | 36.3%   |
| Net/wireless             | 167      | 22.88%  |
| Unassigned class         | 73       | 10%     |
| Communication controller | 51       | 6.99%   |
| Sound                    | 46       | 6.3%    |
| Chipcard                 | 20       | 2.74%   |
| Camera                   | 17       | 2.33%   |
| Multimedia controller    | 16       | 2.19%   |
| Bluetooth                | 15       | 2.05%   |
| Storage/raid             | 13       | 1.78%   |
| Net/ethernet             | 13       | 1.78%   |
| Network                  | 8        | 1.1%    |
| Card reader              | 6        | 0.82%   |
| Dvb card                 | 4        | 0.55%   |
| Storage/nvme             | 3        | 0.41%   |
| Storage/ata              | 3        | 0.41%   |
| Modem                    | 3        | 0.41%   |
| Fingerprint reader       | 3        | 0.41%   |
| Tv card                  | 2        | 0.27%   |
| Wireless                 | 1        | 0.14%   |
| Firewire controller      | 1        | 0.14%   |

