Elementary 6.1 - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------

A project to collect tested hardware configurations for Elementary 6.1.

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

Total: 202

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | X370 Taichi                 | [d86c708401](https://linux-hardware.org/?probe=d86c708401) | Sep 30, 2022 |
| Gigabyte      | G41MT-S2                    | [c0b1c8ad8f](https://linux-hardware.org/?probe=c0b1c8ad8f) | Sep 27, 2022 |
| Packard Be... | IMEDIA S1300                | [13b1f0e28e](https://linux-hardware.org/?probe=13b1f0e28e) | Sep 24, 2022 |
| Packard Be... | IMEDIA S1300                | [fae2bea6f3](https://linux-hardware.org/?probe=fae2bea6f3) | Sep 19, 2022 |
| Apple         | Mac-F221BEC8                | [b5f851bd15](https://linux-hardware.org/?probe=b5f851bd15) | Sep 12, 2022 |
| IceWhale T... | ZimaBoard 832 ZMB           | [335a8a059b](https://linux-hardware.org/?probe=335a8a059b) | Sep 12, 2022 |
| Gigabyte      | F2A88XM-D3HP                | [3d269171e7](https://linux-hardware.org/?probe=3d269171e7) | Sep 11, 2022 |
| ASUSTek       | P8H77-V LE                  | [ae533c2bdf](https://linux-hardware.org/?probe=ae533c2bdf) | Sep 07, 2022 |
| Acer          | Aspire X1420G               | [e48b081560](https://linux-hardware.org/?probe=e48b081560) | Sep 04, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [3a8803f198](https://linux-hardware.org/?probe=3a8803f198) | Sep 01, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [413bd5a721](https://linux-hardware.org/?probe=413bd5a721) | Aug 29, 2022 |
| ASUSTek       | M2N68-AM SE2                | [0f71a52e11](https://linux-hardware.org/?probe=0f71a52e11) | Aug 28, 2022 |
| Gigabyte      | H61M-S1                     | [6bf1dafdbc](https://linux-hardware.org/?probe=6bf1dafdbc) | Aug 27, 2022 |
| Apple         | Mac-F221BEC8                | [9ffe8ee96e](https://linux-hardware.org/?probe=9ffe8ee96e) | Aug 24, 2022 |
| Apple         | Mac-F221BEC8                | [4709584652](https://linux-hardware.org/?probe=4709584652) | Aug 24, 2022 |
| MSI           | MEG Z490I UNIFY             | [34d2d4f66e](https://linux-hardware.org/?probe=34d2d4f66e) | Aug 24, 2022 |
| Foxconn       | 2ABF                        | [6d7ce1962d](https://linux-hardware.org/?probe=6d7ce1962d) | Aug 24, 2022 |
| ASRock        | N68-VGS3 FX                 | [1d2367ccf7](https://linux-hardware.org/?probe=1d2367ccf7) | Aug 23, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [595bf9c8a7](https://linux-hardware.org/?probe=595bf9c8a7) | Aug 23, 2022 |
| HP            | 805D                        | [6748d722e7](https://linux-hardware.org/?probe=6748d722e7) | Aug 19, 2022 |
| ASUSTek       | P7H55-M LX                  | [b545a0cf4f](https://linux-hardware.org/?probe=b545a0cf4f) | Aug 19, 2022 |
| ASUSTek       | PRIME B450M-A               | [59456f2a25](https://linux-hardware.org/?probe=59456f2a25) | Aug 16, 2022 |
| HP            | 2AF7                        | [ca8820daa4](https://linux-hardware.org/?probe=ca8820daa4) | Aug 16, 2022 |
| ASUSTek       | P5B                         | [1c5cafd185](https://linux-hardware.org/?probe=1c5cafd185) | Aug 15, 2022 |
| Acer          | Aspire X1420G               | [7be7ab2e7e](https://linux-hardware.org/?probe=7be7ab2e7e) | Jul 31, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [e99805635f](https://linux-hardware.org/?probe=e99805635f) | Jul 29, 2022 |
| MSI           | B450M PRO-M2 MAX            | [ab8af10726](https://linux-hardware.org/?probe=ab8af10726) | Jul 28, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [d0a69fba02](https://linux-hardware.org/?probe=d0a69fba02) | Jul 23, 2022 |
| Dell          | 00V62H A01                  | [ae809bb317](https://linux-hardware.org/?probe=ae809bb317) | Jul 19, 2022 |
| ASUSTek       | ROG STRIX B360-H GAMING     | [4cc1f4384c](https://linux-hardware.org/?probe=4cc1f4384c) | Jul 12, 2022 |
| Acer          | Aspire X1420G               | [0b7a9cbc2a](https://linux-hardware.org/?probe=0b7a9cbc2a) | Jul 12, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [3db9c636d0](https://linux-hardware.org/?probe=3db9c636d0) | Jul 09, 2022 |
| MSI           | B450M PRO-VDH MAX           | [b8c450d5fa](https://linux-hardware.org/?probe=b8c450d5fa) | Jul 08, 2022 |
| Intel         | X79Turbo V1.x               | [e4b17550d0](https://linux-hardware.org/?probe=e4b17550d0) | Jul 06, 2022 |
| Intel         | X79Turbo V1.x               | [d07e96a623](https://linux-hardware.org/?probe=d07e96a623) | Jul 06, 2022 |
| Gigabyte      | Z87X-OC-CF                  | [654459e245](https://linux-hardware.org/?probe=654459e245) | Jul 03, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | [80a981f992](https://linux-hardware.org/?probe=80a981f992) | Jul 01, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | [a8073316f6](https://linux-hardware.org/?probe=a8073316f6) | Jun 26, 2022 |
| ASRock        | Z490 Pro4                   | [f84c8a756c](https://linux-hardware.org/?probe=f84c8a756c) | Jun 25, 2022 |
| MSI           | B85I                        | [886f971d22](https://linux-hardware.org/?probe=886f971d22) | Jun 25, 2022 |
| HP            | 339A                        | [822467af7f](https://linux-hardware.org/?probe=822467af7f) | Jun 25, 2022 |
| T-bao         | MINI PC                     | [6b18c66487](https://linux-hardware.org/?probe=6b18c66487) | Jun 18, 2022 |
| Pegatron      | 2ACD                        | [8c8275099b](https://linux-hardware.org/?probe=8c8275099b) | Jun 16, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [5b8ae292bf](https://linux-hardware.org/?probe=5b8ae292bf) | Jun 14, 2022 |
| ASUSTek       | SABERTOOTH X58              | [4cc4a7c1b3](https://linux-hardware.org/?probe=4cc4a7c1b3) | Jun 11, 2022 |
| ASUSTek       | SABERTOOTH X58              | [25a8936801](https://linux-hardware.org/?probe=25a8936801) | Jun 11, 2022 |
| HP            | 2B43                        | [6f36772b0c](https://linux-hardware.org/?probe=6f36772b0c) | Jun 10, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [9756188040](https://linux-hardware.org/?probe=9756188040) | Jun 07, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | [0d57c069a8](https://linux-hardware.org/?probe=0d57c069a8) | Jun 05, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | [16f3fff6ad](https://linux-hardware.org/?probe=16f3fff6ad) | Jun 05, 2022 |
| Dell          | 0T7D40 A01                  | [812b41fe55](https://linux-hardware.org/?probe=812b41fe55) | Jun 04, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | [b3d970d061](https://linux-hardware.org/?probe=b3d970d061) | Jun 04, 2022 |
| MSI           | B85I                        | [5f29683d93](https://linux-hardware.org/?probe=5f29683d93) | Jun 03, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [9f4aa60f60](https://linux-hardware.org/?probe=9f4aa60f60) | Jun 02, 2022 |
| ASUSTek       | P5B                         | [12554af571](https://linux-hardware.org/?probe=12554af571) | May 31, 2022 |
| ASUSTek       | P5B                         | [845c2f114b](https://linux-hardware.org/?probe=845c2f114b) | May 31, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | [a4f2a9b24b](https://linux-hardware.org/?probe=a4f2a9b24b) | May 27, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | [3143793e8f](https://linux-hardware.org/?probe=3143793e8f) | May 27, 2022 |
| ASUSTek       | P8H61                       | [5514e95c95](https://linux-hardware.org/?probe=5514e95c95) | May 24, 2022 |
| ASUSTek       | P8H61                       | [873dd31f8e](https://linux-hardware.org/?probe=873dd31f8e) | May 23, 2022 |
| MSI           | H97M-P35                    | [2b5866b09d](https://linux-hardware.org/?probe=2b5866b09d) | May 23, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [2e27b6fac9](https://linux-hardware.org/?probe=2e27b6fac9) | May 23, 2022 |
| Biostar       | GF8200C M2+                 | [b80588cbea](https://linux-hardware.org/?probe=b80588cbea) | May 21, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | [6f6a104d35](https://linux-hardware.org/?probe=6f6a104d35) | May 21, 2022 |
| MSI           | B85I                        | [c822196290](https://linux-hardware.org/?probe=c822196290) | May 18, 2022 |
| MSI           | MEG X570 UNIFY              | [4d00452dcb](https://linux-hardware.org/?probe=4d00452dcb) | May 15, 2022 |
| ASUSTek       | SABERTOOTH X58              | [c276639676](https://linux-hardware.org/?probe=c276639676) | May 08, 2022 |
| ASUSTek       | H81M-K                      | [753c7be679](https://linux-hardware.org/?probe=753c7be679) | May 05, 2022 |
| ASRock        | X570 Extreme4               | [98e5f20999](https://linux-hardware.org/?probe=98e5f20999) | May 04, 2022 |
| HP            | 0B48h                       | [4c6e5824f2](https://linux-hardware.org/?probe=4c6e5824f2) | Apr 30, 2022 |
| ASUSTek       | P8Z77-V                     | [b3506ef75d](https://linux-hardware.org/?probe=b3506ef75d) | Apr 29, 2022 |
| Dell          | 0J3C2F A00                  | [464c70eb8d](https://linux-hardware.org/?probe=464c70eb8d) | Apr 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [1f10d820f8](https://linux-hardware.org/?probe=1f10d820f8) | Apr 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [dfadead480](https://linux-hardware.org/?probe=dfadead480) | Apr 27, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [dbaaf867f6](https://linux-hardware.org/?probe=dbaaf867f6) | Apr 25, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [1b0a41c232](https://linux-hardware.org/?probe=1b0a41c232) | Apr 25, 2022 |
| AZW           | GTi                         | [e2d4a0da2e](https://linux-hardware.org/?probe=e2d4a0da2e) | Apr 23, 2022 |
| AZW           | GTi                         | [cde74551bf](https://linux-hardware.org/?probe=cde74551bf) | Apr 23, 2022 |
| ECS           | H61H2-MV                    | [939f87564f](https://linux-hardware.org/?probe=939f87564f) | Apr 21, 2022 |
| MSI           | X99A SLI PLUS               | [0b935aadb3](https://linux-hardware.org/?probe=0b935aadb3) | Apr 19, 2022 |
| ASRock        | Z490 Pro4                   | [67071d11a1](https://linux-hardware.org/?probe=67071d11a1) | Apr 18, 2022 |
| Dell          | 0KV62T A01                  | [0c6e50ed20](https://linux-hardware.org/?probe=0c6e50ed20) | Apr 17, 2022 |
| Dell          | 0KV62T A01                  | [7bed7782c4](https://linux-hardware.org/?probe=7bed7782c4) | Apr 17, 2022 |
| MSI           | B450M PRO-VDH MAX           | [e28ee0bd42](https://linux-hardware.org/?probe=e28ee0bd42) | Apr 16, 2022 |
| HP            | 1494                        | [6ad3ca1745](https://linux-hardware.org/?probe=6ad3ca1745) | Apr 16, 2022 |
| Gigabyte      | H61M-D2H-USB3               | [016243a675](https://linux-hardware.org/?probe=016243a675) | Apr 15, 2022 |
| Fujitsu       | D3531-A1 S26361-D3531-A1    | [46dd533a5e](https://linux-hardware.org/?probe=46dd533a5e) | Apr 14, 2022 |
| ASUSTek       | B85M-G                      | [c6dd82e724](https://linux-hardware.org/?probe=c6dd82e724) | Apr 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [dff6de5032](https://linux-hardware.org/?probe=dff6de5032) | Apr 14, 2022 |
| ASUSTek       | B85M-G                      | [e525a26ca8](https://linux-hardware.org/?probe=e525a26ca8) | Apr 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [6a2c5f12fd](https://linux-hardware.org/?probe=6a2c5f12fd) | Apr 13, 2022 |
| Dell          | 0K240Y A01                  | [76d4fbf0a6](https://linux-hardware.org/?probe=76d4fbf0a6) | Apr 13, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | [3440d2dd8c](https://linux-hardware.org/?probe=3440d2dd8c) | Apr 12, 2022 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | [637023ab6d](https://linux-hardware.org/?probe=637023ab6d) | Apr 11, 2022 |
| ASUSTek       | PRIME Z390-A                | [21767e12e4](https://linux-hardware.org/?probe=21767e12e4) | Apr 11, 2022 |
| Pegatron      | IPMH61P1                    | [1adcf74c4f](https://linux-hardware.org/?probe=1adcf74c4f) | Apr 10, 2022 |
| ASUSTek       | H110I-PLUS                  | [e367ac99ce](https://linux-hardware.org/?probe=e367ac99ce) | Apr 10, 2022 |
| ASRock        | C226 WS                     | [7c11c1ec43](https://linux-hardware.org/?probe=7c11c1ec43) | Apr 07, 2022 |
| ASUSTek       | STRIKER II FORMULA          | [5dfea21930](https://linux-hardware.org/?probe=5dfea21930) | Apr 07, 2022 |
| ASUSTek       | STRIKER II FORMULA          | [040990b3fc](https://linux-hardware.org/?probe=040990b3fc) | Apr 07, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [7419ad6a76](https://linux-hardware.org/?probe=7419ad6a76) | Apr 02, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | [b67f1750b8](https://linux-hardware.org/?probe=b67f1750b8) | Mar 31, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | [1cd22c83f1](https://linux-hardware.org/?probe=1cd22c83f1) | Mar 31, 2022 |
| MSI           | H97 GAMING 3                | [97f38615e3](https://linux-hardware.org/?probe=97f38615e3) | Mar 31, 2022 |
| MSI           | MEG X570 ACE                | [55572b8a7e](https://linux-hardware.org/?probe=55572b8a7e) | Mar 31, 2022 |
| ASUSTek       | Rampage IV GENE             | [c067a4d0e7](https://linux-hardware.org/?probe=c067a4d0e7) | Mar 29, 2022 |
| Dell          | 0C522T A00                  | [33ae998152](https://linux-hardware.org/?probe=33ae998152) | Mar 26, 2022 |
| Dell          | 0C522T A00                  | [90242bb090](https://linux-hardware.org/?probe=90242bb090) | Mar 26, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [7577679057](https://linux-hardware.org/?probe=7577679057) | Mar 25, 2022 |
| Gigabyte      | A320M-S2H-CF                | [a237859a86](https://linux-hardware.org/?probe=a237859a86) | Mar 24, 2022 |
| Intel         | X79Turbo V1.x               | [18b126a753](https://linux-hardware.org/?probe=18b126a753) | Mar 24, 2022 |
| AMI           | Cherry Trail CR             | [bbea34ce64](https://linux-hardware.org/?probe=bbea34ce64) | Mar 22, 2022 |
| AMI           | Cherry Trail CR             | [bc5a34ef7e](https://linux-hardware.org/?probe=bc5a34ef7e) | Mar 20, 2022 |
| ASUSTek       | Rampage IV GENE             | [7f5053b061](https://linux-hardware.org/?probe=7f5053b061) | Mar 16, 2022 |
| ASUSTek       | Rampage IV GENE             | [7ff55a3ca6](https://linux-hardware.org/?probe=7ff55a3ca6) | Mar 16, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [eda8848760](https://linux-hardware.org/?probe=eda8848760) | Mar 15, 2022 |
| AOpen         | D1009 A1A4                  | [a7375d4581](https://linux-hardware.org/?probe=a7375d4581) | Mar 13, 2022 |
| MSI           | B85I                        | [d134c8451b](https://linux-hardware.org/?probe=d134c8451b) | Mar 12, 2022 |
| ASRock        | B450M Pro4                  | [12459fc7ea](https://linux-hardware.org/?probe=12459fc7ea) | Mar 11, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [a64818ccea](https://linux-hardware.org/?probe=a64818ccea) | Mar 10, 2022 |
| Biostar       | N68S3B                      | [aa1e6a4c82](https://linux-hardware.org/?probe=aa1e6a4c82) | Mar 10, 2022 |
| ASUSTek       | M11AD                       | [8bb5baaa5a](https://linux-hardware.org/?probe=8bb5baaa5a) | Mar 09, 2022 |
| Biostar       | H61MLV2                     | [d5c330bad8](https://linux-hardware.org/?probe=d5c330bad8) | Mar 08, 2022 |
| HP            | 2ADC                        | [ed0714a64a](https://linux-hardware.org/?probe=ed0714a64a) | Mar 07, 2022 |
| MSI           | B85I                        | [39926596b7](https://linux-hardware.org/?probe=39926596b7) | Mar 07, 2022 |
| Dell          | 0PU052                      | [766b0e4665](https://linux-hardware.org/?probe=766b0e4665) | Mar 06, 2022 |
| Dell          | 0PU052                      | [a8e19bd112](https://linux-hardware.org/?probe=a8e19bd112) | Mar 06, 2022 |
| HP            | 1589                        | [88876808e9](https://linux-hardware.org/?probe=88876808e9) | Mar 05, 2022 |
| HP            | 802E                        | [14c73a40e0](https://linux-hardware.org/?probe=14c73a40e0) | Mar 05, 2022 |
| ASRock        | FM2A58M-DG3+                | [0b7875b1b5](https://linux-hardware.org/?probe=0b7875b1b5) | Mar 05, 2022 |
| HP            | 805D                        | [2a09665009](https://linux-hardware.org/?probe=2a09665009) | Mar 02, 2022 |
| ASUSTek       | M4N72-E                     | [c3fe570b4d](https://linux-hardware.org/?probe=c3fe570b4d) | Feb 28, 2022 |
| ASUSTek       | H81-PLUS                    | [e8956dc4ec](https://linux-hardware.org/?probe=e8956dc4ec) | Feb 27, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [a6d5cc0368](https://linux-hardware.org/?probe=a6d5cc0368) | Feb 26, 2022 |
| Gigabyte      | Z390 UD                     | [7ea66813f3](https://linux-hardware.org/?probe=7ea66813f3) | Feb 23, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [73b31ddab0](https://linux-hardware.org/?probe=73b31ddab0) | Feb 20, 2022 |
| Intel         | DH61BE AAG14062-210         | [00566bb73f](https://linux-hardware.org/?probe=00566bb73f) | Feb 19, 2022 |
| ASUSTek       | M11AD                       | [035887c4ab](https://linux-hardware.org/?probe=035887c4ab) | Feb 18, 2022 |
| ASUSTek       | P5B                         | [fa4c095fd7](https://linux-hardware.org/?probe=fa4c095fd7) | Feb 17, 2022 |
| Intel         | H61                         | [a70c59ad0e](https://linux-hardware.org/?probe=a70c59ad0e) | Feb 17, 2022 |
| ASUSTek       | PRIME Z590-A                | [6beda6e2da](https://linux-hardware.org/?probe=6beda6e2da) | Feb 16, 2022 |
| Biostar       | A68MD PRO                   | [da42cc4da7](https://linux-hardware.org/?probe=da42cc4da7) | Feb 16, 2022 |
| ASUSTek       | PRIME Z590-A                | [825734953d](https://linux-hardware.org/?probe=825734953d) | Feb 13, 2022 |
| MSI           | B85I                        | [898dced271](https://linux-hardware.org/?probe=898dced271) | Feb 13, 2022 |
| Gigabyte      | F2A68HM-H                   | [a2a41e039c](https://linux-hardware.org/?probe=a2a41e039c) | Feb 13, 2022 |
| Gigabyte      | F2A68HM-H                   | [2f3941c9cb](https://linux-hardware.org/?probe=2f3941c9cb) | Feb 12, 2022 |
| ASUSTek       | PRIME A320M-K               | [5f4de1e2b0](https://linux-hardware.org/?probe=5f4de1e2b0) | Feb 12, 2022 |
| ASUSTek       | PRIME B360M-K               | [698e174402](https://linux-hardware.org/?probe=698e174402) | Feb 09, 2022 |
| ASUSTek       | H110M-C                     | [82f3d6edf9](https://linux-hardware.org/?probe=82f3d6edf9) | Feb 09, 2022 |
| MSI           | B450I GAMING PLUS AC        | [a2af859752](https://linux-hardware.org/?probe=a2af859752) | Feb 09, 2022 |
| ECS           | H55H-M                      | [856a42d74b](https://linux-hardware.org/?probe=856a42d74b) | Feb 07, 2022 |
| ASUSTek       | ROG STRIX B360-H GAMING     | [92d9fdcc97](https://linux-hardware.org/?probe=92d9fdcc97) | Feb 07, 2022 |
| Lenovo        | NO DPK                      | [4bb7cedbd8](https://linux-hardware.org/?probe=4bb7cedbd8) | Feb 06, 2022 |
| HP            | 802E                        | [31e2fe159c](https://linux-hardware.org/?probe=31e2fe159c) | Feb 05, 2022 |
| ASUSTek       | H110M-C                     | [6ba127c715](https://linux-hardware.org/?probe=6ba127c715) | Feb 04, 2022 |
| ASUSTek       | P5B                         | [9b661f64dd](https://linux-hardware.org/?probe=9b661f64dd) | Feb 04, 2022 |
| Foxconn       | NETBOX nT-435/535 Ver       | [c7d50db62b](https://linux-hardware.org/?probe=c7d50db62b) | Feb 03, 2022 |
| Foxconn       | NETBOX nT-435/535 Ver       | [2ee2be7ccf](https://linux-hardware.org/?probe=2ee2be7ccf) | Feb 03, 2022 |
| HP            | ProLiant ML110 G7           | [2e1dcafe6c](https://linux-hardware.org/?probe=2e1dcafe6c) | Feb 03, 2022 |
| HP            | 339A                        | [cf9dca84ff](https://linux-hardware.org/?probe=cf9dca84ff) | Feb 02, 2022 |
| Unknown       | Unknown                     | [629972c689](https://linux-hardware.org/?probe=629972c689) | Feb 01, 2022 |
| HP            | 805D                        | [19295e5827](https://linux-hardware.org/?probe=19295e5827) | Feb 01, 2022 |
| ASUSTek       | H110I-PLUS                  | [ebeaf681e3](https://linux-hardware.org/?probe=ebeaf681e3) | Feb 01, 2022 |
| Gigabyte      | B75M-D3H                    | [18717f0712](https://linux-hardware.org/?probe=18717f0712) | Feb 01, 2022 |
| MSI           | Z270 KRAIT GAMING           | [17ccbf9c76](https://linux-hardware.org/?probe=17ccbf9c76) | Jan 28, 2022 |
| Gigabyte      | H61M-DS2                    | [e800b95c58](https://linux-hardware.org/?probe=e800b95c58) | Jan 26, 2022 |
| ASRock        | H61M-HVS                    | [8fdf1980ee](https://linux-hardware.org/?probe=8fdf1980ee) | Jan 25, 2022 |
| ASRock        | H61M-HVS                    | [5d19dff1e4](https://linux-hardware.org/?probe=5d19dff1e4) | Jan 25, 2022 |
| Acer          | ConceptD CM100-51A V:1.1    | [663bbd709d](https://linux-hardware.org/?probe=663bbd709d) | Jan 24, 2022 |
| FIRICH        | J1900                       | [937e24af64](https://linux-hardware.org/?probe=937e24af64) | Jan 22, 2022 |
| ASUSTek       | ROG STRIX B360-H GAMING     | [d1505fe489](https://linux-hardware.org/?probe=d1505fe489) | Jan 21, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [75d67cd8a4](https://linux-hardware.org/?probe=75d67cd8a4) | Jan 20, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [7a14d864d4](https://linux-hardware.org/?probe=7a14d864d4) | Jan 20, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | [ec51f5ca3e](https://linux-hardware.org/?probe=ec51f5ca3e) | Jan 19, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [488d339e77](https://linux-hardware.org/?probe=488d339e77) | Jan 19, 2022 |
| MSI           | B450M-A PRO MAX             | [e7225dad8e](https://linux-hardware.org/?probe=e7225dad8e) | Jan 17, 2022 |
| ASUSTek       | H61M-CS                     | [8855875fbd](https://linux-hardware.org/?probe=8855875fbd) | Jan 14, 2022 |
| Unknown       | T3 MRD                      | [33392a90ce](https://linux-hardware.org/?probe=33392a90ce) | Jan 13, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [00a00c3cac](https://linux-hardware.org/?probe=00a00c3cac) | Jan 13, 2022 |
| ASUSTek       | M5A78L-M LX3                | [39f3687349](https://linux-hardware.org/?probe=39f3687349) | Jan 12, 2022 |
| Foxconn       | 2AB1                        | [07faf9a309](https://linux-hardware.org/?probe=07faf9a309) | Jan 12, 2022 |
| ASUSTek       | H110M-C                     | [be4291793d](https://linux-hardware.org/?probe=be4291793d) | Jan 10, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [7ce29e0c54](https://linux-hardware.org/?probe=7ce29e0c54) | Jan 09, 2022 |
| HP            | 8597                        | [09ed815dd0](https://linux-hardware.org/?probe=09ed815dd0) | Jan 08, 2022 |
| Gigabyte      | GA-970A-D3                  | [b1c9832ce6](https://linux-hardware.org/?probe=b1c9832ce6) | Jan 07, 2022 |
| ASRock        | Z370 Pro4                   | [51cba69624](https://linux-hardware.org/?probe=51cba69624) | Jan 06, 2022 |
| ASRock        | B450M-HDV R4.0              | [20dfc25b62](https://linux-hardware.org/?probe=20dfc25b62) | Jan 05, 2022 |
| Gigabyte      | B85M-DS3H-A                 | [cd6abb9f49](https://linux-hardware.org/?probe=cd6abb9f49) | Jan 03, 2022 |
| MSI           | 2A9C                        | [8d08f7f383](https://linux-hardware.org/?probe=8d08f7f383) | Dec 31, 2021 |
| HP            | 3397                        | [323dc8992b](https://linux-hardware.org/?probe=323dc8992b) | Dec 31, 2021 |
| ASUSTek       | X79-DELUXE                  | [00b9dd3788](https://linux-hardware.org/?probe=00b9dd3788) | Dec 30, 2021 |
| HP            | 1589                        | [d123a8de64](https://linux-hardware.org/?probe=d123a8de64) | Dec 30, 2021 |
| Foxconn       | 2AB1                        | [bcd6fc46cc](https://linux-hardware.org/?probe=bcd6fc46cc) | Dec 30, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [5f67c759fe](https://linux-hardware.org/?probe=5f67c759fe) | Dec 28, 2021 |
| Gigabyte      | Z390 UD                     | [2399fa64ba](https://linux-hardware.org/?probe=2399fa64ba) | Dec 26, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | [783618fe4b](https://linux-hardware.org/?probe=783618fe4b) | Dec 23, 2021 |
| ASUSTek       | H97-PLUS                    | [cba91c2ad2](https://linux-hardware.org/?probe=cba91c2ad2) | Dec 22, 2021 |
| MSI           | B450-A PRO MAX              | [f14eef1ae6](https://linux-hardware.org/?probe=f14eef1ae6) | Dec 20, 2021 |
| Gigabyte      | H310M S2P                   | [a931eb10f0](https://linux-hardware.org/?probe=a931eb10f0) | Dec 19, 2021 |
| Foxconn       | 2AB1                        | [b789981cc4](https://linux-hardware.org/?probe=b789981cc4) | Dec 17, 2021 |
| Gigabyte      | Z590 AORUS ELITE AX         | [c068e358e8](https://linux-hardware.org/?probe=c068e358e8) | Dec 16, 2021 |
| ASUSTek       | M5A78L-M LX3                | [720cc7a45f](https://linux-hardware.org/?probe=720cc7a45f) | Dec 15, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.11.0-43-generic    | 28       | 17.18%  |
| 5.13.0-39-generic    | 17       | 10.43%  |
| 5.13.0-28-generic    | 17       | 10.43%  |
| 5.15.0-46-generic    | 15       | 9.2%    |
| 5.13.0-30-generic    | 10       | 6.13%   |
| 5.13.0-40-generic    | 9        | 5.52%   |
| 5.13.0-27-generic    | 9        | 5.52%   |
| 5.13.0-35-generic    | 7        | 4.29%   |
| 5.13.0-52-generic    | 5        | 3.07%   |
| 5.13.0-51-generic    | 5        | 3.07%   |
| 5.13.0-37-generic    | 5        | 3.07%   |
| 5.11.0-41-generic    | 5        | 3.07%   |
| 5.15.0-41-generic    | 4        | 2.45%   |
| 5.13.0-44-generic    | 4        | 2.45%   |
| 5.11.0-44-generic    | 4        | 2.45%   |
| 5.13.0-48-generic    | 3        | 1.84%   |
| 5.15.0-48-generic    | 2        | 1.23%   |
| 5.13.0-41-generic    | 2        | 1.23%   |
| 5.13.0-25-generic    | 2        | 1.23%   |
| 5.11.0-46-generic    | 2        | 1.23%   |
| 5.17.3-xanmod1       | 1        | 0.61%   |
| 5.15.36-xanmod1      | 1        | 0.61%   |
| 5.14.0-1042-oem      | 1        | 0.61%   |
| 5.13.0-28-lowlatency | 1        | 0.61%   |
| 5.13.0-22-generic    | 1        | 0.61%   |
| 5.11.0-43-lowlatency | 1        | 0.61%   |
| 5.11.0-40-generic    | 1        | 0.61%   |
| 5.11.0-37-generic    | 1        | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13.0  | 85       | 57.05%  |
| 5.11.0  | 40       | 26.85%  |
| 5.15.0  | 21       | 14.09%  |
| 5.17.3  | 1        | 0.67%   |
| 5.15.36 | 1        | 0.67%   |
| 5.14.0  | 1        | 0.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13    | 85       | 57.05%  |
| 5.11    | 40       | 26.85%  |
| 5.15    | 22       | 14.77%  |
| 5.17    | 1        | 0.67%   |
| 5.14    | 1        | 0.67%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 143      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Pantheon | 142      | 99.3%   |
| KDE5     | 1        | 0.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 143      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 123      | 84.83%  |
| LightDM | 22       | 15.17%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 60       | 41.67%  |
| de_DE | 18       | 12.5%   |
| fr_FR | 12       | 8.33%   |
| es_ES | 12       | 8.33%   |
| ru_RU | 7        | 4.86%   |
| en_GB | 7        | 4.86%   |
| pt_BR | 5        | 3.47%   |
| it_IT | 5        | 3.47%   |
| pl_PL | 3        | 2.08%   |
| tr_TR | 2        | 1.39%   |
| ja_JP | 2        | 1.39%   |
| en_CA | 2        | 1.39%   |
| zh_CN | 1        | 0.69%   |
| uk_UA | 1        | 0.69%   |
| sr_RS | 1        | 0.69%   |
| pt_PT | 1        | 0.69%   |
| id_ID | 1        | 0.69%   |
| fr_CA | 1        | 0.69%   |
| en_AU | 1        | 0.69%   |
| de_CH | 1        | 0.69%   |
| C     | 1        | 0.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 79       | 53.74%  |
| BIOS | 68       | 46.26%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 137      | 95.8%   |
| Btrfs   | 3        | 2.1%    |
| Xfs     | 2        | 1.4%    |
| Overlay | 1        | 0.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 127      | 88.19%  |
| GPT     | 14       | 9.72%   |
| MBR     | 3        | 2.08%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 137      | 94.48%  |
| Yes       | 8        | 5.52%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 135      | 93.75%  |
| Yes       | 9        | 6.25%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 40       | 27.97%  |
| Gigabyte Technology | 22       | 15.38%  |
| MSI                 | 18       | 12.59%  |
| Hewlett-Packard     | 13       | 9.09%   |
| ASRock              | 10       | 6.99%   |
| Dell                | 7        | 4.9%    |
| Lenovo              | 4        | 2.8%    |
| Biostar             | 4        | 2.8%    |
| Intel               | 3        | 2.1%    |
| Foxconn             | 3        | 2.1%    |
| Pegatron            | 2        | 1.4%    |
| ECS                 | 2        | 1.4%    |
| Apple               | 2        | 1.4%    |
| Acer                | 2        | 1.4%    |
| Unknown             | 2        | 1.4%    |
| T-bao               | 1        | 0.7%    |
| Packard Bell        | 1        | 0.7%    |
| LORD ELECTRONICS    | 1        | 0.7%    |
| IceWhale Technology | 1        | 0.7%    |
| Fujitsu             | 1        | 0.7%    |
| FIRICH              | 1        | 0.7%    |
| AZW                 | 1        | 0.7%    |
| AOpen               | 1        | 0.7%    |
| AMI                 | 1        | 0.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| ASUS All Series                                   | 4        | 2.8%    |
| MSI MS-7C35                                       | 2        | 1.4%    |
| HP Compaq Pro 6300 MT                             | 2        | 1.4%    |
| Gigabyte Z390 UD                                  | 2        | 1.4%    |
| ASUS TUF Gaming B550M-PLUS                        | 2        | 1.4%    |
| Unknown                                           | 2        | 1.4%    |
| T-bao MINI PC                                     | 1        | 0.7%    |
| Pegatron p7-1174                                  | 1        | 0.7%    |
| Pegatron IPMH61P1                                 | 1        | 0.7%    |
| Packard Bell IMEDIA S1300                         | 1        | 0.7%    |
| MSI PPPPP-CCC#MMMMMMMM                            | 1        | 0.7%    |
| MSI MS-7D52                                       | 1        | 0.7%    |
| MSI MS-7C91                                       | 1        | 0.7%    |
| MSI MS-7C77                                       | 1        | 0.7%    |
| MSI MS-7C52                                       | 1        | 0.7%    |
| MSI MS-7C02                                       | 1        | 0.7%    |
| MSI MS-7B86                                       | 1        | 0.7%    |
| MSI MS-7B84                                       | 1        | 0.7%    |
| MSI MS-7B79                                       | 1        | 0.7%    |
| MSI MS-7A59                                       | 1        | 0.7%    |
| MSI MS-7A40                                       | 1        | 0.7%    |
| MSI MS-7A38                                       | 1        | 0.7%    |
| MSI MS-7918                                       | 1        | 0.7%    |
| MSI MS-7885                                       | 1        | 0.7%    |
| MSI MS-7851                                       | 1        | 0.7%    |
| MSI MS-7817                                       | 1        | 0.7%    |
| LORD ELECTRONICS LORD G4x 775 ICH7 8712 As Design | 1        | 0.7%    |
| Lenovo ThinkCentre M73 10B6001SUS                 | 1        | 0.7%    |
| Lenovo ThinkCentre M72e 3664AD7                   | 1        | 0.7%    |
| Lenovo ThinkCentre M58 6258D3G                    | 1        | 0.7%    |
| Lenovo IdeaCentre 510S-07ICK 90LX006TGE           | 1        | 0.7%    |
| Intel X79                                         | 1        | 0.7%    |
| Intel H61                                         | 1        | 0.7%    |
| Intel DH61BE AAG14062-210                         | 1        | 0.7%    |
| IceWhale ZimaBoard 832 ZMB                        | 1        | 0.7%    |
| HP Z420 Workstation                               | 1        | 0.7%    |
| HP Z240 SFF Workstation                           | 1        | 0.7%    |
| HP Z200 SFF Workstation                           | 1        | 0.7%    |
| HP ProLiant ML110 G7                              | 1        | 0.7%    |
| HP ProDesk 600 G5 SFF                             | 1        | 0.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 7        | 4.9%    |
| Dell OptiPlex          | 6        | 4.2%    |
| ASUS TUF               | 6        | 4.2%    |
| ASUS ROG               | 5        | 3.5%    |
| HP Compaq              | 4        | 2.8%    |
| ASUS All               | 4        | 2.8%    |
| Lenovo ThinkCentre     | 3        | 2.1%    |
| ASUS P8H61-M           | 3        | 2.1%    |
| MSI MS-7C35            | 2        | 1.4%    |
| HP ProDesk             | 2        | 1.4%    |
| Gigabyte Z390          | 2        | 1.4%    |
| Unknown                | 2        | 1.4%    |
| T-bao MINI             | 1        | 0.7%    |
| Pegatron p7-1174       | 1        | 0.7%    |
| Pegatron IPMH61P1      | 1        | 0.7%    |
| Packard Bell IMEDIA    | 1        | 0.7%    |
| MSI PPPPP-CCC#MMMMMMMM | 1        | 0.7%    |
| MSI MS-7D52            | 1        | 0.7%    |
| MSI MS-7C91            | 1        | 0.7%    |
| MSI MS-7C77            | 1        | 0.7%    |
| MSI MS-7C52            | 1        | 0.7%    |
| MSI MS-7C02            | 1        | 0.7%    |
| MSI MS-7B86            | 1        | 0.7%    |
| MSI MS-7B84            | 1        | 0.7%    |
| MSI MS-7B79            | 1        | 0.7%    |
| MSI MS-7A59            | 1        | 0.7%    |
| MSI MS-7A40            | 1        | 0.7%    |
| MSI MS-7A38            | 1        | 0.7%    |
| MSI MS-7918            | 1        | 0.7%    |
| MSI MS-7885            | 1        | 0.7%    |
| MSI MS-7851            | 1        | 0.7%    |
| MSI MS-7817            | 1        | 0.7%    |
| LORD ELECTRONICS LORD  | 1        | 0.7%    |
| Lenovo IdeaCentre      | 1        | 0.7%    |
| Intel X79              | 1        | 0.7%    |
| Intel H61              | 1        | 0.7%    |
| Intel DH61BE           | 1        | 0.7%    |
| IceWhale ZimaBoard     | 1        | 0.7%    |
| HP Z420                | 1        | 0.7%    |
| HP Z240                | 1        | 0.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 19       | 13.29%  |
| 2018 | 16       | 11.19%  |
| 2020 | 13       | 9.09%   |
| 2010 | 13       | 9.09%   |
| 2019 | 12       | 8.39%   |
| 2011 | 12       | 8.39%   |
| 2015 | 10       | 6.99%   |
| 2014 | 10       | 6.99%   |
| 2021 | 9        | 6.29%   |
| 2013 | 9        | 6.29%   |
| 2017 | 6        | 4.2%    |
| 2016 | 5        | 3.5%    |
| 2022 | 3        | 2.1%    |
| 2009 | 2        | 1.4%    |
| 2008 | 2        | 1.4%    |
| 2007 | 1        | 0.7%    |
| 2006 | 1        | 0.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 143      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 136      | 95.1%   |
| Enabled  | 7        | 4.9%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 143      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 33       | 22.92%  |
| 32.01-64.0  | 29       | 20.14%  |
| 8.01-16.0   | 29       | 20.14%  |
| 4.01-8.0    | 23       | 15.97%  |
| 3.01-4.0    | 20       | 13.89%  |
| 64.01-256.0 | 4        | 2.78%   |
| 1.01-2.0    | 3        | 2.08%   |
| 24.01-32.0  | 2        | 1.39%   |
| 2.01-3.0    | 1        | 0.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 60       | 37.04%  |
| 2.01-3.0  | 43       | 26.54%  |
| 4.01-8.0  | 25       | 15.43%  |
| 3.01-4.0  | 23       | 14.2%   |
| 8.01-16.0 | 6        | 3.7%    |
| 0.51-1.0  | 5        | 3.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 50       | 34.25%  |
| 1      | 48       | 32.88%  |
| 3      | 23       | 15.75%  |
| 4      | 14       | 9.59%   |
| 5      | 5        | 3.42%   |
| 6      | 4        | 2.74%   |
| 7      | 2        | 1.37%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 77       | 53.1%   |
| Yes       | 68       | 46.9%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 143      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 73       | 50.34%  |
| Yes       | 72       | 49.66%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 86       | 59.72%  |
| Yes       | 58       | 40.28%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 21       | 14.69%  |
| Germany      | 17       | 11.89%  |
| UK           | 9        | 6.29%   |
| France       | 9        | 6.29%   |
| Spain        | 8        | 5.59%   |
| Brazil       | 7        | 4.9%    |
| Russia       | 6        | 4.2%    |
| Indonesia    | 6        | 4.2%    |
| Canada       | 6        | 4.2%    |
| Switzerland  | 5        | 3.5%    |
| Italy        | 5        | 3.5%    |
| Poland       | 4        | 2.8%    |
| Turkey       | 3        | 2.1%    |
| Japan        | 3        | 2.1%    |
| India        | 3        | 2.1%    |
| Australia    | 3        | 2.1%    |
| Iran         | 2        | 1.4%    |
| Colombia     | 2        | 1.4%    |
| Austria      | 2        | 1.4%    |
| Argentina    | 2        | 1.4%    |
| Thailand     | 1        | 0.7%    |
| Sweden       | 1        | 0.7%    |
| Sri Lanka    | 1        | 0.7%    |
| South Africa | 1        | 0.7%    |
| Serbia       | 1        | 0.7%    |
| Romania      | 1        | 0.7%    |
| Norway       | 1        | 0.7%    |
| New Zealand  | 1        | 0.7%    |
| Netherlands  | 1        | 0.7%    |
| Mexico       | 1        | 0.7%    |
| Malaysia     | 1        | 0.7%    |
| Lithuania    | 1        | 0.7%    |
| Kenya        | 1        | 0.7%    |
| Israel       | 1        | 0.7%    |
| Ireland      | 1        | 0.7%    |
| Hong Kong    | 1        | 0.7%    |
| Egypt        | 1        | 0.7%    |
| Czechia      | 1        | 0.7%    |
| China        | 1        | 0.7%    |
| Belarus      | 1        | 0.7%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Warsaw           | 3        | 1.95%   |
| Moscow           | 3        | 1.95%   |
| Hamburg          | 3        | 1.95%   |
| Caslano          | 3        | 1.95%   |
| Tangerang        | 2        | 1.3%    |
| Paris            | 2        | 1.3%    |
| Istanbul         | 2        | 1.3%    |
| Denver           | 2        | 1.3%    |
| Brisbane         | 2        | 1.3%    |
| Yucca Valley     | 1        | 0.65%   |
| Yokohama         | 1        | 0.65%   |
| Yarang           | 1        | 0.65%   |
| Wroclaw          | 1        | 0.65%   |
| Woolloongabba    | 1        | 0.65%   |
| Woodbridge       | 1        | 0.65%   |
| Wolgast          | 1        | 0.65%   |
| Werneck          | 1        | 0.65%   |
| Walnut Creek     | 1        | 0.65%   |
| Vienna           | 1        | 0.65%   |
| Vanse            | 1        | 0.65%   |
| Tournus          | 1        | 0.65%   |
| Toronto          | 1        | 0.65%   |
| Thrissur         | 1        | 0.65%   |
| Teresina         | 1        | 0.65%   |
| Tel Aviv         | 1        | 0.65%   |
| Tehran           | 1        | 0.65%   |
| Sydney           | 1        | 0.65%   |
| Suresnes         | 1        | 0.65%   |
| Stuttgart        | 1        | 0.65%   |
| Spello           | 1        | 0.65%   |
| Songkhla         | 1        | 0.65%   |
| Sollentuna       | 1        | 0.65%   |
| Sentmenat        | 1        | 0.65%   |
| Sarrebourg       | 1        | 0.65%   |
| Sao Paulo        | 1        | 0.65%   |
| Sant Joan Despí | 1        | 0.65%   |
| San Antonio      | 1        | 0.65%   |
| Saguenay         | 1        | 0.65%   |
| Rotterdam        | 1        | 0.65%   |
| Rio de Janeiro   | 1        | 0.65%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 46       | 71     | 17.23%  |
| Seagate                   | 45       | 62     | 16.85%  |
| Samsung Electronics       | 37       | 62     | 13.86%  |
| Kingston                  | 23       | 31     | 8.61%   |
| Toshiba                   | 18       | 26     | 6.74%   |
| Crucial                   | 11       | 14     | 4.12%   |
| SanDisk                   | 8        | 10     | 3%      |
| Unknown                   | 7        | 15     | 2.62%   |
| Intel                     | 6        | 6      | 2.25%   |
| PNY                       | 5        | 10     | 1.87%   |
| Phison                    | 5        | 5      | 1.87%   |
| Micron/Crucial Technology | 5        | 8      | 1.87%   |
| Hitachi                   | 5        | 6      | 1.87%   |
| A-DATA Technology         | 5        | 5      | 1.87%   |
| Micron Technology         | 3        | 4      | 1.12%   |
| Maxtor                    | 3        | 3      | 1.12%   |
| ASMT                      | 3        | 3      | 1.12%   |
| Team                      | 2        | 3      | 0.75%   |
| Realtek Semiconductor     | 2        | 2      | 0.75%   |
| Plextor                   | 2        | 3      | 0.75%   |
| JMicron Technology        | 2        | 2      | 0.75%   |
| HGST                      | 2        | 2      | 0.75%   |
| Corsair                   | 2        | 2      | 0.75%   |
| China                     | 2        | 2      | 0.75%   |
| XPG                       | 1        | 1      | 0.37%   |
| Transcend                 | 1        | 1      | 0.37%   |
| tigo                      | 1        | 1      | 0.37%   |
| SPCC                      | 1        | 1      | 0.37%   |
| Silicon Motion            | 1        | 1      | 0.37%   |
| OCZ-VERTEX2               | 1        | 1      | 0.37%   |
| OCZ                       | 1        | 2      | 0.37%   |
| Netac                     | 1        | 1      | 0.37%   |
| MidasForce                | 1        | 1      | 0.37%   |
| LITEON                    | 1        | 1      | 0.37%   |
| Leven                     | 1        | 1      | 0.37%   |
| KingFast                  | 1        | 1      | 0.37%   |
| Intenso                   | 1        | 1      | 0.37%   |
| Hewlett-Packard           | 1        | 1      | 0.37%   |
| GOODRAM                   | 1        | 1      | 0.37%   |
| Gigabyte Technology       | 1        | 1      | 0.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Samsung NVMe SSD Drive 500GB      | 7        | 2.31%   |
| Toshiba DT01ACA050 500GB          | 5        | 1.65%   |
| Seagate ST1000DM003-1ER162 1TB    | 4        | 1.32%   |
| Samsung SSD 860 EVO 250GB         | 4        | 1.32%   |
| Micron/Crucial NVMe SSD Drive 1TB | 4        | 1.32%   |
| Kingston SA400S37120G 120GB SSD   | 4        | 1.32%   |
| Crucial CT240BX500SSD1 240GB      | 4        | 1.32%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 3        | 0.99%   |
| WDC WD10EZEX-00BN5A0 1TB          | 3        | 0.99%   |
| Unknown SD/MMC 16GB               | 3        | 0.99%   |
| Unknown M.S./M.S.Pro/HG 16GB      | 3        | 0.99%   |
| Toshiba DT01ACA100 1TB            | 3        | 0.99%   |
| Seagate ST500DM002-1BD142 500GB   | 3        | 0.99%   |
| Seagate ST3500418AS 500GB         | 3        | 0.99%   |
| Seagate ST1000DM010-2EP102 1TB    | 3        | 0.99%   |
| Samsung SSD 860 EVO 1TB           | 3        | 0.99%   |
| Samsung SSD 850 EVO 250GB         | 3        | 0.99%   |
| Phison NVMe SSD Drive 1TB         | 3        | 0.99%   |
| Kingston SV300S37A120G 120GB SSD  | 3        | 0.99%   |
| Kingston SA400S37240G 240GB SSD   | 3        | 0.99%   |
| Kingston NVMe SSD Drive 1TB       | 3        | 0.99%   |
| WDC WD5000AAKX-001CA0 500GB       | 2        | 0.66%   |
| WDC WD5000AAKS-00UU3A0 500GB      | 2        | 0.66%   |
| WDC WD40EFRX-68N32N0 4TB          | 2        | 0.66%   |
| WDC WD10EZEX-08WN4A0 1TB          | 2        | 0.66%   |
| Unknown MMC Card  32GB            | 2        | 0.66%   |
| Toshiba HDWD110 1TB               | 2        | 0.66%   |
| Seagate ST31000528AS 1TB          | 2        | 0.66%   |
| Seagate ST2000DX002-2DV164 2TB    | 2        | 0.66%   |
| Seagate ST2000DM001-9YN164 2TB    | 2        | 0.66%   |
| Seagate ST1000DM003-1CH162 1TB    | 2        | 0.66%   |
| Samsung SSD 870 EVO 1TB           | 2        | 0.66%   |
| Samsung SSD 860 QVO 1TB           | 2        | 0.66%   |
| Samsung SSD 850 PRO 256GB         | 2        | 0.66%   |
| Samsung SSD 840 EVO 250GB         | 2        | 0.66%   |
| Samsung SSD 840 EVO 120GB         | 2        | 0.66%   |
| Samsung NVMe SSD Drive 1TB        | 2        | 0.66%   |
| Samsung HD322HJ 320GB             | 2        | 0.66%   |
| PNY CS900 480GB SSD               | 2        | 0.66%   |
| Kingston SA400S37960G 960GB SSD   | 2        | 0.66%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 42       | 58     | 35%     |
| WDC                 | 39       | 55     | 32.5%   |
| Toshiba             | 17       | 25     | 14.17%  |
| Samsung Electronics | 8        | 9      | 6.67%   |
| Hitachi             | 5        | 6      | 4.17%   |
| Maxtor              | 2        | 2      | 1.67%   |
| HGST                | 2        | 2      | 1.67%   |
| ASMT                | 2        | 2      | 1.67%   |
| Unknown             | 1        | 1      | 0.83%   |
| Hewlett-Packard     | 1        | 1      | 0.83%   |
| Fujitsu             | 1        | 1      | 0.83%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 23       | 36     | 22.55%  |
| Kingston            | 17       | 21     | 16.67%  |
| Crucial             | 10       | 12     | 9.8%    |
| SanDisk             | 8        | 9      | 7.84%   |
| WDC                 | 7        | 12     | 6.86%   |
| PNY                 | 5        | 10     | 4.9%    |
| A-DATA Technology   | 4        | 4      | 3.92%   |
| Intel               | 3        | 3      | 2.94%   |
| Team                | 2        | 3      | 1.96%   |
| Plextor             | 2        | 3      | 1.96%   |
| Micron Technology   | 2        | 2      | 1.96%   |
| Corsair             | 2        | 2      | 1.96%   |
| China               | 2        | 2      | 1.96%   |
| Transcend           | 1        | 1      | 0.98%   |
| Toshiba             | 1        | 1      | 0.98%   |
| tigo                | 1        | 1      | 0.98%   |
| SPCC                | 1        | 1      | 0.98%   |
| Seagate             | 1        | 2      | 0.98%   |
| OCZ-VERTEX2         | 1        | 1      | 0.98%   |
| OCZ                 | 1        | 2      | 0.98%   |
| MidasForce          | 1        | 1      | 0.98%   |
| Maxtor              | 1        | 1      | 0.98%   |
| LITEON              | 1        | 1      | 0.98%   |
| Leven               | 1        | 1      | 0.98%   |
| Intenso             | 1        | 1      | 0.98%   |
| GOODRAM             | 1        | 1      | 0.98%   |
| Gigabyte Technology | 1        | 1      | 0.98%   |
| ASMT                | 1        | 1      | 0.98%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 96       | 162    | 41.03%  |
| SSD     | 88       | 136    | 37.61%  |
| NVMe    | 38       | 56     | 16.24%  |
| Unknown | 9        | 19     | 3.85%   |
| MMC     | 3        | 3      | 1.28%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 132      | 294    | 70.59%  |
| NVMe | 38       | 56     | 20.32%  |
| SAS  | 14       | 23     | 7.49%   |
| MMC  | 3        | 3      | 1.6%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 101      | 173    | 57.06%  |
| 0.51-1.0   | 45       | 81     | 25.42%  |
| 1.01-2.0   | 13       | 17     | 7.34%   |
| 2.01-3.0   | 7        | 15     | 3.95%   |
| 4.01-10.0  | 6        | 7      | 3.39%   |
| 3.01-4.0   | 5        | 5      | 2.82%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 47       | 31.13%  |
| 251-500        | 33       | 21.85%  |
| 501-1000       | 32       | 21.19%  |
| 1001-2000      | 14       | 9.27%   |
| 51-100         | 10       | 6.62%   |
| More than 3000 | 9        | 5.96%   |
| 21-50          | 4        | 2.65%   |
| 2001-3000      | 2        | 1.32%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 64       | 40%     |
| 21-50          | 24       | 15%     |
| 101-250        | 23       | 14.38%  |
| 51-100         | 17       | 10.63%  |
| 251-500        | 13       | 8.13%   |
| 501-1000       | 10       | 6.25%   |
| 1001-2000      | 5        | 3.13%   |
| More than 3000 | 3        | 1.88%   |
| 2001-3000      | 1        | 0.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                        | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| WDC WD5000AAKS-00UU3A0 500GB | 1        | 1      | 33.33%  |
| Seagate ST3500312CS 500GB    | 1        | 1      | 33.33%  |
| SanDisk SSD PLUS 240GB       | 1        | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 33.33%  |
| Seagate | 1        | 1      | 33.33%  |
| SanDisk | 1        | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 50%     |
| Seagate | 1        | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 2        | 2      | 66.67%  |
| SSD  | 1        | 1      | 33.33%  |

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
| Detected | 129      | 336    | 87.16%  |
| Works    | 16       | 37     | 10.81%  |
| Malfunc  | 3        | 3      | 2.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 96       | 48.73%  |
| AMD                         | 39       | 19.8%   |
| Samsung Electronics         | 14       | 7.11%   |
| Nvidia                      | 8        | 4.06%   |
| Kingston Technology Company | 7        | 3.55%   |
| Micron/Crucial Technology   | 6        | 3.05%   |
| Phison Electronics          | 5        | 2.54%   |
| ASMedia Technology          | 5        | 2.54%   |
| Marvell Technology Group    | 4        | 2.03%   |
| Realtek Semiconductor       | 3        | 1.52%   |
| Seagate Technology          | 2        | 1.02%   |
| SanDisk                     | 2        | 1.02%   |
| JMicron Technology          | 2        | 1.02%   |
| Silicon Motion              | 1        | 0.51%   |
| Micron Technology           | 1        | 0.51%   |
| LSI Logic / Symbios Logic   | 1        | 0.51%   |
| ADATA Technology            | 1        | 0.51%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 24       | 9.88%   |
| AMD 400 Series Chipset SATA Controller                                                  | 15       | 6.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 11       | 4.53%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 10       | 4.12%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 9        | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 9        | 3.7%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8        | 3.29%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 7        | 2.88%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7        | 2.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6        | 2.47%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6        | 2.47%   |
| Nvidia MCP61 SATA Controller                                                            | 5        | 2.06%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 5        | 2.06%   |
| Kingston Company A2000 NVMe SSD                                                         | 5        | 2.06%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5        | 2.06%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 1.65%   |
| AMD 500 Series Chipset SATA Controller                                                  | 4        | 1.65%   |
| Nvidia MCP61 IDE                                                                        | 3        | 1.23%   |
| Intel SATA Controller [RAID mode]                                                       | 3        | 1.23%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3        | 1.23%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 1.23%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 1.23%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 0.82%   |
| Realtek Realtek Non-Volatile memory controller                                          | 2        | 0.82%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 0.82%   |
| Phison E12 NVMe Controller                                                              | 2        | 0.82%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 2        | 0.82%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2        | 0.82%   |
| Intel SSD 660P Series                                                                   | 2        | 0.82%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2        | 0.82%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 0.82%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 0.82%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 0.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 0.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 2        | 0.82%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 2        | 0.82%   |
| AMD FCH SATA Controller D                                                               | 2        | 0.82%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 0.41%   |
| Seagate FireCuda 530 SSD                                                                | 1        | 0.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 114      | 58.46%  |
| NVMe | 38       | 19.49%  |
| IDE  | 34       | 17.44%  |
| RAID | 8        | 4.1%    |
| SAS  | 1        | 0.51%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 97       | 67.83%  |
| AMD    | 46       | 32.17%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor          | 5        | 3.5%    |
| Intel Core i7-4770 CPU @ 3.40GHz            | 4        | 2.8%    |
| Intel Core i5-2400 CPU @ 3.10GHz            | 4        | 2.8%    |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 2.1%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 2.1%    |
| Intel 11th Gen Core i7-11700K @ 3.60GHz     | 3        | 2.1%    |
| AMD Ryzen 9 5900X 12-Core Processor         | 3        | 2.1%    |
| AMD Ryzen 5 2600 Six-Core Processor         | 3        | 2.1%    |
| Intel Core i7-9700 CPU @ 3.00GHz            | 2        | 1.4%    |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 1.4%    |
| Intel Core i7-10700K CPU @ 3.80GHz          | 2        | 1.4%    |
| Intel Core i5-8400 CPU @ 2.80GHz            | 2        | 1.4%    |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 1.4%    |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2        | 1.4%    |
| Intel Core i3 CPU 530 @ 2.93GHz             | 2        | 1.4%    |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 2        | 1.4%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 2        | 1.4%    |
| AMD Ryzen 9 3900X 12-Core Processor         | 2        | 1.4%    |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 1.4%    |
| AMD Ryzen 5 2600X Six-Core Processor        | 2        | 1.4%    |
| Intel Xeon CPU X5680 @ 3.33GHz              | 1        | 0.7%    |
| Intel Xeon CPU E5462 @ 2.80GHz              | 1        | 0.7%    |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1        | 0.7%    |
| Intel Xeon CPU E5-2665 0 @ 2.40GHz          | 1        | 0.7%    |
| Intel Xeon CPU E5-1660 0 @ 3.30GHz          | 1        | 0.7%    |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz         | 1        | 0.7%    |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz         | 1        | 0.7%    |
| Intel Xeon CPU E31270 @ 3.40GHz             | 1        | 0.7%    |
| Intel Xeon CPU E31240 @ 3.30GHz             | 1        | 0.7%    |
| Intel Xeon CPU E3-1283L v4 @ 2.90GHz        | 1        | 0.7%    |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz         | 1        | 0.7%    |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1        | 0.7%    |
| Intel Pentium CPU G630 @ 2.70GHz            | 1        | 0.7%    |
| Intel Pentium CPU G620 @ 2.60GHz            | 1        | 0.7%    |
| Intel Pentium CPU G2030 @ 3.00GHz           | 1        | 0.7%    |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1        | 0.7%    |
| Intel Core i7-9700K CPU @ 3.60GHz           | 1        | 0.7%    |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 0.7%    |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1        | 0.7%    |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1        | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 25       | 17.48%  |
| Intel Core i7           | 24       | 16.78%  |
| Intel Core i3           | 14       | 9.79%   |
| Intel Xeon              | 11       | 7.69%   |
| AMD Ryzen 7             | 11       | 7.69%   |
| AMD Ryzen 5             | 11       | 7.69%   |
| Other                   | 5        | 3.5%    |
| Intel Celeron           | 5        | 3.5%    |
| AMD Ryzen 9             | 5        | 3.5%    |
| AMD Athlon II X2        | 4        | 2.8%    |
| Intel Pentium           | 3        | 2.1%    |
| Intel Core 2 Duo        | 3        | 2.1%    |
| Intel Atom              | 3        | 2.1%    |
| AMD Phenom II X4        | 3        | 2.1%    |
| AMD FX                  | 3        | 2.1%    |
| Intel Core 2 Quad       | 2        | 1.4%    |
| AMD Athlon              | 2        | 1.4%    |
| AMD A8                  | 2        | 1.4%    |
| AMD A10                 | 2        | 1.4%    |
| Intel Pentium Dual-Core | 1        | 0.7%    |
| Intel Core i9           | 1        | 0.7%    |
| AMD Ryzen 3             | 1        | 0.7%    |
| AMD Athlon X4           | 1        | 0.7%    |
| AMD Athlon II X4        | 1        | 0.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 61       | 42.07%  |
| 2      | 33       | 22.76%  |
| 8      | 22       | 15.17%  |
| 6      | 19       | 13.1%   |
| 12     | 6        | 4.14%   |
| 1      | 2        | 1.38%   |
| 16     | 1        | 0.69%   |
| 3      | 1        | 0.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 141      | 98.6%   |
| 2      | 2        | 1.4%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 87       | 60.42%  |
| 1      | 57       | 39.58%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 143      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x206a7    | 15       | 10.27%  |
| 0x306c3    | 14       | 9.59%   |
| 0x306a9    | 11       | 7.53%   |
| Unknown    | 10       | 6.85%   |
| 0x08701021 | 8        | 5.48%   |
| 0x506e3    | 5        | 3.42%   |
| 0x0800820d | 5        | 3.42%   |
| 0x906ea    | 4        | 2.74%   |
| 0x08108109 | 4        | 2.74%   |
| 0xa0671    | 3        | 2.05%   |
| 0x906ed    | 3        | 2.05%   |
| 0x906eb    | 3        | 2.05%   |
| 0x906e9    | 3        | 2.05%   |
| 0x206d7    | 3        | 2.05%   |
| 0x1067a    | 3        | 2.05%   |
| 0x06003106 | 3        | 2.05%   |
| 0x010000c8 | 3        | 2.05%   |
| 0xa0655    | 2        | 1.37%   |
| 0xa0653    | 2        | 1.37%   |
| 0x6fb      | 2        | 1.37%   |
| 0x406c4    | 2        | 1.37%   |
| 0x20655    | 2        | 1.37%   |
| 0x20652    | 2        | 1.37%   |
| 0x0a50000c | 2        | 1.37%   |
| 0x0a201016 | 2        | 1.37%   |
| 0x08701013 | 2        | 1.37%   |
| 0x08001138 | 2        | 1.37%   |
| 0x06000852 | 2        | 1.37%   |
| 0x010000c7 | 2        | 1.37%   |
| 0x906ec    | 1        | 0.68%   |
| 0x90672    | 1        | 0.68%   |
| 0x806c1    | 1        | 0.68%   |
| 0x706a8    | 1        | 0.68%   |
| 0x6f7      | 1        | 0.68%   |
| 0x506c9    | 1        | 0.68%   |
| 0x40671    | 1        | 0.68%   |
| 0x306f2    | 1        | 0.68%   |
| 0x306e4    | 1        | 0.68%   |
| 0x30678    | 1        | 0.68%   |
| 0x206c2    | 1        | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| SandyBridge      | 19       | 13.29%  |
| Haswell          | 16       | 11.19%  |
| KabyLake         | 15       | 10.49%  |
| IvyBridge        | 12       | 8.39%   |
| Zen+             | 10       | 6.99%   |
| Zen 2            | 10       | 6.99%   |
| K10              | 8        | 5.59%   |
| Zen 3            | 7        | 4.9%    |
| Westmere         | 5        | 3.5%    |
| Skylake          | 5        | 3.5%    |
| Penryn           | 4        | 2.8%    |
| CometLake        | 4        | 2.8%    |
| Zen              | 3        | 2.1%    |
| Steamroller      | 3        | 2.1%    |
| Silvermont       | 3        | 2.1%    |
| Piledriver       | 3        | 2.1%    |
| Icelake          | 3        | 2.1%    |
| Core             | 3        | 2.1%    |
| Nehalem          | 2        | 1.4%    |
| TigerLake        | 1        | 0.7%    |
| K10 Llano        | 1        | 0.7%    |
| Goldmont plus    | 1        | 0.7%    |
| Goldmont         | 1        | 0.7%    |
| Bulldozer        | 1        | 0.7%    |
| Broadwell        | 1        | 0.7%    |
| Bonnell          | 1        | 0.7%    |
| Alderlake Hybrid | 1        | 0.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 58       | 38.16%  |
| Nvidia | 48       | 31.58%  |
| Intel  | 46       | 30.26%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13       | 8.28%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 8        | 5.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6        | 3.82%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4        | 2.55%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 4        | 2.55%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 3        | 1.91%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 3        | 1.91%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3        | 1.91%   |
| Intel HD Graphics 530                                                                    | 3        | 1.91%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3        | 1.91%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3        | 1.91%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 3        | 1.91%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 3        | 1.91%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2        | 1.27%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2        | 1.27%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 2        | 1.27%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 2        | 1.27%   |
| Intel HD Graphics 630                                                                    | 2        | 1.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 1.27%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 1.27%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                                        | 2        | 1.27%   |
| AMD Park [Mobility Radeon HD 5430]                                                       | 2        | 1.27%   |
| AMD Navi 24 [Radeon RX 6400 / 6500 XT]                                                   | 2        | 1.27%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2        | 1.27%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                                         | 2        | 1.27%   |
| AMD Cezanne                                                                              | 2        | 1.27%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2        | 1.27%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 2        | 1.27%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1        | 0.64%   |
| Nvidia TU106 [GeForce GTX 1650]                                                          | 1        | 0.64%   |
| Nvidia TU104 [GeForce RTX 2080]                                                          | 1        | 0.64%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1        | 0.64%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1        | 0.64%   |
| Nvidia TU104 [GeForce RTX 2060]                                                          | 1        | 0.64%   |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 0.64%   |
| Nvidia GP107GL [Quadro P620]                                                             | 1        | 0.64%   |
| Nvidia GP107GL [Quadro P1000]                                                            | 1        | 0.64%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1        | 0.64%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1        | 0.64%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1        | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 52       | 35.86%  |
| 1 x Nvidia     | 46       | 31.72%  |
| 1 x Intel      | 40       | 27.59%  |
| 2 x AMD        | 3        | 2.07%   |
| Intel + AMD    | 2        | 1.38%   |
| Intel + Nvidia | 1        | 0.69%   |
| AMD + Nvidia   | 1        | 0.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 116      | 80%     |
| Proprietary | 28       | 19.31%  |
| Unknown     | 1        | 0.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 46       | 30.87%  |
| 1.01-2.0   | 25       | 16.78%  |
| 3.01-4.0   | 22       | 14.77%  |
| 0.51-1.0   | 22       | 14.77%  |
| 7.01-8.0   | 10       | 6.71%   |
| 0.01-0.5   | 9        | 6.04%   |
| 5.01-6.0   | 8        | 5.37%   |
| 2.01-3.0   | 4        | 2.68%   |
| 8.01-16.0  | 3        | 2.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 23       | 14.02%  |
| Goldstar             | 17       | 10.37%  |
| Hewlett-Packard      | 16       | 9.76%   |
| Acer                 | 16       | 9.76%   |
| Dell                 | 14       | 8.54%   |
| Philips              | 10       | 6.1%    |
| AOC                  | 8        | 4.88%   |
| Lenovo               | 6        | 3.66%   |
| BenQ                 | 6        | 3.66%   |
| Ancor Communications | 6        | 3.66%   |
| Unknown              | 3        | 1.83%   |
| LG Electronics       | 3        | 1.83%   |
| AUS                  | 3        | 1.83%   |
| Vizio                | 2        | 1.22%   |
| Sony                 | 2        | 1.22%   |
| Sharp                | 2        | 1.22%   |
| NEC Computers        | 2        | 1.22%   |
| Iiyama               | 2        | 1.22%   |
| HPN                  | 2        | 1.22%   |
| Fujitsu Siemens      | 2        | 1.22%   |
| ___                  | 1        | 0.61%   |
| ViewSonic            | 1        | 0.61%   |
| Vestel               | 1        | 0.61%   |
| SPC                  | 1        | 0.61%   |
| Onkyo                | 1        | 0.61%   |
| MSI                  | 1        | 0.61%   |
| Mi                   | 1        | 0.61%   |
| LLP                  | 1        | 0.61%   |
| IOD                  | 1        | 0.61%   |
| Hitachi              | 1        | 0.61%   |
| HannStar             | 1        | 0.61%   |
| Gateway              | 1        | 0.61%   |
| Element              | 1        | 0.61%   |
| Eizo                 | 1        | 0.61%   |
| CHR                  | 1        | 0.61%   |
| CHD                  | 1        | 0.61%   |
| BOE                  | 1        | 0.61%   |
| Apple                | 1        | 0.61%   |
| Unknown              | 1        | 0.61%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 3        | 1.71%   |
| Hewlett-Packard 2010 HWP2889 1600x900 443x250mm 20.0-inch               | 2        | 1.14%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch               | 2        | 1.14%   |
| Goldstar 22EN33 GSM597C 1920x1080 480x270mm 21.7-inch                   | 2        | 1.14%   |
| Dell 1704FPV DEL3016 1280x1024 340x270mm 17.1-inch                      | 2        | 1.14%   |
| BenQ EL2870U BNQ7949 3840x2160 620x340mm 27.8-inch                      | 2        | 1.14%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch   | 2        | 1.14%   |
| ___ TV ___9000 1360x768                                                 | 1        | 0.57%   |
| Vizio VO320E VIZ0035 1280x720 700x390mm 31.5-inch                       | 1        | 0.57%   |
| Vizio M322i-B1 VIZ1005 1920x1080 698x392mm 31.5-inch                    | 1        | 0.57%   |
| ViewSonic LCD Monitor VX2260WM 3840x1080                                | 1        | 0.57%   |
| ViewSonic LCD Monitor VX2260WM                                          | 1        | 0.57%   |
| Vestel LCD Monitor 49FHD_LCD_TV 1920x1080                               | 1        | 0.57%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                      | 1        | 0.57%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                   | 1        | 0.57%   |
| Unknown LCD Monitor Bit 3 LE2262 1680x1050                              | 1        | 0.57%   |
| SPC LCD Monitor SPC1900 1440x900 368x207mm 16.6-inch                    | 1        | 0.57%   |
| Sony TV SNYD703 1360x768                                                | 1        | 0.57%   |
| Sony TV  *00 SNY8004 3840x2160 1220x680mm 55.0-inch                     | 1        | 0.57%   |
| Sharp HDMI SHP108E 1360x768 820x460mm 37.0-inch                         | 1        | 0.57%   |
| Sharp HDMI SHP1048 1920x1080 1330x750mm 60.1-inch                       | 1        | 0.57%   |
| Samsung Electronics T24D391 SAM0B72 1920x1080 521x293mm 23.5-inch       | 1        | 0.57%   |
| Samsung Electronics T22C310 SAM0AE9 1920x1080 477x268mm 21.5-inch       | 1        | 0.57%   |
| Samsung Electronics SyncMaster SAM0421 1920x1200 518x324mm 24.1-inch    | 1        | 0.57%   |
| Samsung Electronics SMBX2035 SAM06FD 1600x900 443x249mm 20.0-inch       | 1        | 0.57%   |
| Samsung Electronics SA300/SA350 SAM078C 1600x900 443x249mm 20.0-inch    | 1        | 0.57%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch    | 1        | 0.57%   |
| Samsung Electronics S27R35x SAM1053 1920x1080 598x336mm 27.0-inch       | 1        | 0.57%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch       | 1        | 0.57%   |
| Samsung Electronics S22C450 SAM09C7 1680x1050 473x291mm 21.9-inch       | 1        | 0.57%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 477x268mm 21.5-inch       | 1        | 0.57%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch        | 1        | 0.57%   |
| Samsung Electronics LCD Monitor SAM0C3F 3840x2160 1872x1053mm 84.6-inch | 1        | 0.57%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch    | 1        | 0.57%   |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch    | 1        | 0.57%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1060x626mm 48.5-inch  | 1        | 0.57%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch    | 1        | 0.57%   |
| Samsung Electronics LCD Monitor SAM0530 1360x768                        | 1        | 0.57%   |
| Samsung Electronics LCD Monitor SAM04FD 1360x768                        | 1        | 0.57%   |
| Samsung Electronics LCD Monitor S22D300                                 | 1        | 0.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 67       | 40.61%  |
| 3840x2160 (4K)     | 15       | 9.09%   |
| 1680x1050 (WSXGA+) | 14       | 8.48%   |
| 2560x1440 (QHD)    | 11       | 6.67%   |
| 1366x768 (WXGA)    | 11       | 6.67%   |
| 1600x900 (HD+)     | 8        | 4.85%   |
| 1280x1024 (SXGA)   | 7        | 4.24%   |
| 1440x900 (WXGA+)   | 6        | 3.64%   |
| 1360x768           | 5        | 3.03%   |
| Unknown            | 5        | 3.03%   |
| 3840x1080          | 4        | 2.42%   |
| 1920x1200 (WUXGA)  | 4        | 2.42%   |
| 3440x1440          | 3        | 1.82%   |
| 5120x1440          | 2        | 1.21%   |
| 7680x2160          | 1        | 0.61%   |
| 3840x1200          | 1        | 0.61%   |
| 2560x1080          | 1        | 0.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 26       | 16.05%  |
| 24      | 18       | 11.11%  |
| 23      | 18       | 11.11%  |
| 21      | 18       | 11.11%  |
| 27      | 14       | 8.64%   |
| 22      | 12       | 7.41%   |
| 31      | 8        | 4.94%   |
| 18      | 8        | 4.94%   |
| 20      | 6        | 3.7%    |
| 19      | 6        | 3.7%    |
| 17      | 5        | 3.09%   |
| 32      | 4        | 2.47%   |
| 34      | 3        | 1.85%   |
| 72      | 2        | 1.23%   |
| 15      | 2        | 1.23%   |
| 84      | 1        | 0.62%   |
| 65      | 1        | 0.62%   |
| 60      | 1        | 0.62%   |
| 55      | 1        | 0.62%   |
| 49      | 1        | 0.62%   |
| 48      | 1        | 0.62%   |
| 43      | 1        | 0.62%   |
| 37      | 1        | 0.62%   |
| 36      | 1        | 0.62%   |
| 28      | 1        | 0.62%   |
| 26      | 1        | 0.62%   |
| 16      | 1        | 0.62%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 46       | 29.3%   |
| 501-600     | 45       | 28.66%  |
| Unknown     | 26       | 16.56%  |
| 601-700     | 12       | 7.64%   |
| 701-800     | 8        | 5.1%    |
| 301-350     | 6        | 3.82%   |
| 1001-1500   | 5        | 3.18%   |
| 351-400     | 4        | 2.55%   |
| 1501-2000   | 3        | 1.91%   |
| 801-900     | 1        | 0.64%   |
| 901-1000    | 1        | 0.64%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 91       | 61.07%  |
| 16/10   | 23       | 15.44%  |
| Unknown | 23       | 15.44%  |
| 5/4     | 5        | 3.36%   |
| 21/9    | 4        | 2.68%   |
| 6/5     | 1        | 0.67%   |
| 32/9    | 1        | 0.67%   |
| 3/2     | 1        | 0.67%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 50       | 31.85%  |
| Unknown        | 26       | 16.56%  |
| 151-200        | 17       | 10.83%  |
| 351-500        | 15       | 9.55%   |
| 301-350        | 14       | 8.92%   |
| 251-300        | 10       | 6.37%   |
| 141-150        | 10       | 6.37%   |
| More than 1000 | 7        | 4.46%   |
| 501-1000       | 4        | 2.55%   |
| 131-140        | 1        | 0.64%   |
| 111-120        | 1        | 0.64%   |
| 101-110        | 1        | 0.64%   |
| 91-100         | 1        | 0.64%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 84       | 54.19%  |
| 101-120 | 29       | 18.71%  |
| Unknown | 26       | 16.77%  |
| 1-50    | 9        | 5.81%   |
| 121-160 | 6        | 3.87%   |
| 161-240 | 1        | 0.65%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 117      | 80.69%  |
| 2     | 24       | 16.55%  |
| 3     | 3        | 2.07%   |
| 0     | 1        | 0.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 87       | 41.23%  |
| Intel                           | 66       | 31.28%  |
| Qualcomm Atheros                | 10       | 4.74%   |
| Ralink Technology               | 7        | 3.32%   |
| Nvidia                          | 7        | 3.32%   |
| Broadcom                        | 7        | 3.32%   |
| Samsung Electronics             | 4        | 1.9%    |
| TP-Link                         | 3        | 1.42%   |
| Ralink                          | 3        | 1.42%   |
| Xiaomi                          | 2        | 0.95%   |
| Linksys                         | 2        | 0.95%   |
| vivo                            | 1        | 0.47%   |
| TRENDnet                        | 1        | 0.47%   |
| Qualcomm Atheros Communications | 1        | 0.47%   |
| Motorola PCS                    | 1        | 0.47%   |
| Microsoft                       | 1        | 0.47%   |
| Marvell Technology Group        | 1        | 0.47%   |
| LG Electronics                  | 1        | 0.47%   |
| Huawei Technologies             | 1        | 0.47%   |
| D-Link System                   | 1        | 0.47%   |
| Broadcom Limited                | 1        | 0.47%   |
| AVM                             | 1        | 0.47%   |
| Aquantia                        | 1        | 0.47%   |
| AboCom Systems                  | 1        | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                 | 64       | 27%     |
| Intel Wi-Fi 6 AX200                                                               | 11       | 4.64%   |
| Realtek RTL8125 2.5GbE Controller                                                 | 10       | 4.22%   |
| Intel I211 Gigabit Network Connection                                             | 8        | 3.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                             | 8        | 3.38%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                             | 6        | 2.53%   |
| Realtek 802.11ac NIC                                                              | 6        | 2.53%   |
| Intel Ethernet Connection (2) I219-V                                              | 6        | 2.53%   |
| Ralink MT7601U Wireless Adapter                                                   | 5        | 2.11%   |
| Nvidia MCP61 Ethernet                                                             | 5        | 2.11%   |
| Intel Ethernet Controller I225-V                                                  | 4        | 1.69%   |
| Intel 82579V Gigabit Network Connection                                           | 4        | 1.69%   |
| Intel Ethernet Connection (7) I219-V                                              | 3        | 1.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                  | 3        | 1.27%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                    | 2        | 0.84%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                       | 2        | 0.84%   |
| Samsung Galaxy series, misc. (tethering mode)                                     | 2        | 0.84%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                               | 2        | 0.84%   |
| Ralink RT5372 Wireless Adapter                                                    | 2        | 0.84%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                            | 2        | 0.84%   |
| Intel Ethernet Connection I217-LM                                                 | 2        | 0.84%   |
| Intel Ethernet Connection (2) I219-LM                                             | 2        | 0.84%   |
| Intel Ethernet Connection (11) I219-V                                             | 2        | 0.84%   |
| Intel Comet Lake PCH CNVi WiFi                                                    | 2        | 0.84%   |
| Intel 82578DM Gigabit Network Connection                                          | 2        | 0.84%   |
| Intel 82574L Gigabit Network Connection                                           | 2        | 0.84%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                | 2        | 0.84%   |
| vivo 1806                                                                         | 1        | 0.42%   |
| TRENDnet TEW-648UBM 802.11n 150Mbps Micro Wireless N Adapter [Realtek RTL8188CUS] | 1        | 0.42%   |
| TP-Link Archer T4U ver.3                                                          | 1        | 0.42%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                        | 1        | 0.42%   |
| TP-Link 802.11ac NIC                                                              | 1        | 0.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                          | 1        | 0.42%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                          | 1        | 0.42%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                          | 1        | 0.42%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                       | 1        | 0.42%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                             | 1        | 0.42%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                           | 1        | 0.42%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                           | 1        | 0.42%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                        | 1        | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 28       | 35.44%  |
| Realtek Semiconductor           | 17       | 21.52%  |
| Ralink Technology               | 7        | 8.86%   |
| Broadcom                        | 7        | 8.86%   |
| TP-Link                         | 3        | 3.8%    |
| Ralink                          | 3        | 3.8%    |
| Qualcomm Atheros                | 3        | 3.8%    |
| Linksys                         | 2        | 2.53%   |
| TRENDnet                        | 1        | 1.27%   |
| Qualcomm Atheros Communications | 1        | 1.27%   |
| Microsoft                       | 1        | 1.27%   |
| Marvell Technology Group        | 1        | 1.27%   |
| LG Electronics                  | 1        | 1.27%   |
| D-Link System                   | 1        | 1.27%   |
| Broadcom Limited                | 1        | 1.27%   |
| AVM                             | 1        | 1.27%   |
| AboCom Systems                  | 1        | 1.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                               | 11       | 13.75%  |
| Realtek 802.11ac NIC                                                              | 6        | 7.5%    |
| Ralink MT7601U Wireless Adapter                                                   | 5        | 6.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                  | 3        | 3.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                               | 2        | 2.5%    |
| Ralink RT5372 Wireless Adapter                                                    | 2        | 2.5%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                            | 2        | 2.5%    |
| Intel Comet Lake PCH CNVi WiFi                                                    | 2        | 2.5%    |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                | 2        | 2.5%    |
| TRENDnet TEW-648UBM 802.11n 150Mbps Micro Wireless N Adapter [Realtek RTL8188CUS] | 1        | 1.25%   |
| TP-Link Archer T4U ver.3                                                          | 1        | 1.25%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                        | 1        | 1.25%   |
| TP-Link 802.11ac NIC                                                              | 1        | 1.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                          | 1        | 1.25%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                          | 1        | 1.25%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                          | 1        | 1.25%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                       | 1        | 1.25%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                             | 1        | 1.25%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                           | 1        | 1.25%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                           | 1        | 1.25%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                        | 1        | 1.25%   |
| Realtek RTL8187 Wireless Adapter                                                  | 1        | 1.25%   |
| Realtek 802.11n WLAN Adapter                                                      | 1        | 1.25%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                         | 1        | 1.25%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                         | 1        | 1.25%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                         | 1        | 1.25%   |
| Qualcomm Atheros AR9271 802.11n                                                   | 1        | 1.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                  | 1        | 1.25%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                    | 1        | 1.25%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]               | 1        | 1.25%   |
| Microsoft Xbox 360 Wireless Adapter                                               | 1        | 1.25%   |
| Marvell Group 88w8335 [Libertas] 802.11b/g Wireless                               | 1        | 1.25%   |
| Linksys WUSB6300 V2                                                               | 1        | 1.25%   |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                                         | 1        | 1.25%   |
| LG AN-WF100 802.11abgn Wireless Adapter [Broadcom BCM4323]                        | 1        | 1.25%   |
| Intel Wireless-AC 9260                                                            | 1        | 1.25%   |
| Intel Wireless 8260                                                               | 1        | 1.25%   |
| Intel Wireless 3165                                                               | 1        | 1.25%   |
| Intel Wireless 3160                                                               | 1        | 1.25%   |
| Intel Wi-Fi 6 AX201                                                               | 1        | 1.25%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 81       | 51.92%  |
| Intel                 | 51       | 32.69%  |
| Qualcomm Atheros      | 7        | 4.49%   |
| Nvidia                | 7        | 4.49%   |
| Samsung Electronics   | 4        | 2.56%   |
| Xiaomi                | 2        | 1.28%   |
| vivo                  | 1        | 0.64%   |
| Motorola PCS          | 1        | 0.64%   |
| Huawei Technologies   | 1        | 0.64%   |
| Aquantia              | 1        | 0.64%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 64       | 40.76%  |
| Realtek RTL8125 2.5GbE Controller                                 | 10       | 6.37%   |
| Intel I211 Gigabit Network Connection                             | 8        | 5.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8        | 5.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6        | 3.82%   |
| Intel Ethernet Connection (2) I219-V                              | 6        | 3.82%   |
| Nvidia MCP61 Ethernet                                             | 5        | 3.18%   |
| Intel Ethernet Controller I225-V                                  | 4        | 2.55%   |
| Intel 82579V Gigabit Network Connection                           | 4        | 2.55%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 1.91%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 1.27%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2        | 1.27%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 1.27%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.27%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 1.27%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 1.27%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 1.27%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.27%   |
| vivo 1806                                                         | 1        | 0.64%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.64%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.64%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.64%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.64%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.64%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1        | 0.64%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.64%   |
| Nvidia MCP77 Ethernet                                             | 1        | 0.64%   |
| Nvidia MCP55 Ethernet                                             | 1        | 0.64%   |
| Motorola PCS Moto G (5) Plus                                      | 1        | 0.64%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.64%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.64%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.64%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 0.64%   |
| Intel Ethernet Connection (12) I219-V                             | 1        | 0.64%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 0.64%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.64%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1        | 0.64%   |
| Huawei YAL-L21                                                    | 1        | 0.64%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 143      | 66.2%   |
| WiFi     | 73       | 33.8%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 104      | 75.91%  |
| WiFi     | 33       | 24.09%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 91       | 63.19%  |
| 2     | 44       | 30.56%  |
| 3     | 8        | 5.56%   |
| 0     | 1        | 0.69%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 106      | 73.1%   |
| Yes  | 39       | 26.9%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 27       | 45%     |
| Cambridge Silicon Radio | 14       | 23.33%  |
| Realtek Semiconductor   | 5        | 8.33%   |
| Broadcom                | 5        | 8.33%   |
| Apple                   | 3        | 5%      |
| ASUSTek Computer        | 2        | 3.33%   |
| Ralink                  | 1        | 1.67%   |
| Qcom                    | 1        | 1.67%   |
| IMC Networks            | 1        | 1.67%   |
| Edimax Technology       | 1        | 1.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 14       | 23.33%  |
| Intel AX200 Bluetooth                               | 10       | 16.67%  |
| Realtek Bluetooth Radio                             | 5        | 8.33%   |
| Intel Bluetooth wireless interface                  | 4        | 6.67%   |
| Intel AX201 Bluetooth                               | 4        | 6.67%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3        | 5%      |
| Intel AX210 Bluetooth                               | 3        | 5%      |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2        | 3.33%   |
| Ralink RT3290 Bluetooth                             | 1        | 1.67%   |
| Qcom Bluetooth USB                                  | 1        | 1.67%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 1.67%   |
| Intel Bluetooth Device                              | 1        | 1.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 1.67%   |
| IMC Networks BCM20702A0                             | 1        | 1.67%   |
| Edimax Bluetooth Adapter                            | 1        | 1.67%   |
| Broadcom HP Portable Bumble Bee                     | 1        | 1.67%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter    | 1        | 1.67%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1        | 1.67%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 1.67%   |
| ASUS BCM20702A0                                     | 1        | 1.67%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1        | 1.67%   |
| Apple Bluetooth USB Host Controller                 | 1        | 1.67%   |
| Apple Bluetooth HCI                                 | 1        | 1.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 89       | 36.63%  |
| AMD                      | 65       | 26.75%  |
| Nvidia                   | 52       | 21.4%   |
| C-Media Electronics      | 11       | 4.53%   |
| Creative Labs            | 8        | 3.29%   |
| Logitech                 | 4        | 1.65%   |
| Focusrite-Novation       | 2        | 0.82%   |
| Corsair                  | 2        | 0.82%   |
| Texas Instruments        | 1        | 0.41%   |
| Razer USA                | 1        | 0.41%   |
| Native Instruments       | 1        | 0.41%   |
| Microsoft                | 1        | 0.41%   |
| Micro Star International | 1        | 0.41%   |
| GN Netcom                | 1        | 0.41%   |
| Generalplus Technology   | 1        | 0.41%   |
| Edifier Technology       | 1        | 0.41%   |
| Creative Technology      | 1        | 0.41%   |
| ASUSTek Computer         | 1        | 0.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 20       | 7.09%   |
| AMD Starship/Matisse HD Audio Controller                                          | 13       | 4.61%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 10       | 3.55%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 8        | 2.84%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 8        | 2.84%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 8        | 2.84%   |
| Intel Cannon Lake PCH cAVS                                                        | 7        | 2.48%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 7        | 2.48%   |
| AMD Family 17h/19h HD Audio Controller                                            | 7        | 2.48%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 7        | 2.48%   |
| Nvidia GF108 High Definition Audio Controller                                     | 6        | 2.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 6        | 2.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 6        | 2.13%   |
| Nvidia MCP61 High Definition Audio                                                | 5        | 1.77%   |
| Nvidia GP106 High Definition Audio Controller                                     | 5        | 1.77%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 5        | 1.77%   |
| Intel 200 Series PCH HD Audio                                                     | 5        | 1.77%   |
| AMD FCH Azalia Controller                                                         | 5        | 1.77%   |
| Nvidia TU116 High Definition Audio Controller                                     | 4        | 1.42%   |
| Nvidia TU104 HD Audio Controller                                                  | 4        | 1.42%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 4        | 1.42%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 4        | 1.42%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 4        | 1.42%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 4        | 1.42%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 4        | 1.42%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 4        | 1.42%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 3        | 1.06%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 3        | 1.06%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 3        | 1.06%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 3        | 1.06%   |
| Intel Comet Lake PCH cAVS                                                         | 3        | 1.06%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 3        | 1.06%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 3        | 1.06%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                     | 3        | 1.06%   |
| Creative Labs EMU20k2 [Sound Blaster X-Fi Titanium Series]                        | 3        | 1.06%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 3        | 1.06%   |
| AMD Kaveri HDMI/DP Audio Controller                                               | 3        | 1.06%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 3        | 1.06%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                         | 2        | 0.71%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2        | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 5        | 18.52%  |
| Kingston            | 5        | 18.52%  |
| Unknown             | 3        | 11.11%  |
| SK hynix            | 3        | 11.11%  |
| Corsair             | 2        | 7.41%   |
| A-DATA Technology   | 2        | 7.41%   |
| Unknown (0x038A)    | 1        | 3.7%    |
| Ramaxel Technology  | 1        | 3.7%    |
| PNY                 | 1        | 3.7%    |
| Patriot             | 1        | 3.7%    |
| Micron Technology   | 1        | 3.7%    |
| G.Skill             | 1        | 3.7%    |
| Crucial             | 1        | 3.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM DDR3 1066MT/s                 | 1        | 3.57%   |
| Unknown RAM Module 8192MB DIMM DDR3 1066MT/s              | 1        | 3.57%   |
| Unknown RAM Module 8192MB DIMM 1066MT/s                   | 1        | 3.57%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                 | 1        | 3.57%   |
| Unknown (0x038A) RAM Module 4GB DIMM DDR3 1066MT/s        | 1        | 3.57%   |
| SK hynix RAM HMT42GR7BMR4C 16384MB DIMM DDR3 1066MT/s     | 1        | 3.57%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s      | 1        | 3.57%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1        | 3.57%   |
| Samsung RAM Module 8192MB DIMM DDR4 2666MT/s              | 1        | 3.57%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 1        | 3.57%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 1        | 3.57%   |
| Samsung RAM M393B2K70DM0 16384MB DIMM DDR3 1066MT/s       | 1        | 3.57%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s       | 1        | 3.57%   |
| Ramaxel RAM RMUA5090KB78HAF2133 8192MB DIMM DDR4 2133MT/s | 1        | 3.57%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8GB DIMM DDR4 3200MT/s       | 1        | 3.57%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s        | 1        | 3.57%   |
| Micron RAM Module 16384MB DIMM DDR3 1600MT/s              | 1        | 3.57%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s         | 1        | 3.57%   |
| Kingston RAM KF3600C18D4/16GX 16GB DIMM DDR4 3600MT/s     | 1        | 3.57%   |
| Kingston RAM 9905783-049.A01G 16384MB DIMM 4800MT/s       | 1        | 3.57%   |
| Kingston RAM 9905625-030.A00G 8GB DIMM 2133MT/s           | 1        | 3.57%   |
| Kingston RAM 9905471-015.A00LF 4GB DIMM DDR3 1333MT/s     | 1        | 3.57%   |
| G.Skill RAM F3-14900CL9-2GBXM 2048MB DIMM DDR3 1600MT/s   | 1        | 3.57%   |
| Crucial RAM CT25664BA1339.C8FE 2048MB DIMM DDR3 1333MT/s  | 1        | 3.57%   |
| Corsair RAM CMX8GX3M1A1600C11 8GB DIMM DDR3 1600MT/s      | 1        | 3.57%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s      | 1        | 3.57%   |
| A-DATA RAM Module 4096MB DIMM DDR4 2400MT/s               | 1        | 3.57%   |
| A-DATA RAM Module 16384MB DIMM DDR4 2667MT/s              | 1        | 3.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 10       | 50%     |
| DDR4    | 8        | 40%     |
| Unknown | 2        | 10%     |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 18       | 90%     |
| SODIMM | 2        | 10%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 9        | 40.91%  |
| 4096  | 6        | 27.27%  |
| 16384 | 5        | 22.73%  |
| 32768 | 1        | 4.55%   |
| 2048  | 1        | 4.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 5        | 21.74%  |
| 1066  | 4        | 17.39%  |
| 3200  | 2        | 8.7%    |
| 1333  | 2        | 8.7%    |
| 4800  | 1        | 4.35%   |
| 3600  | 1        | 4.35%   |
| 2933  | 1        | 4.35%   |
| 2800  | 1        | 4.35%   |
| 2667  | 1        | 4.35%   |
| 2666  | 1        | 4.35%   |
| 2400  | 1        | 4.35%   |
| 2200  | 1        | 4.35%   |
| 2133  | 1        | 4.35%   |
| 1800  | 1        | 4.35%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 2        | 40%     |
| Dymo-CoStar        | 1        | 20%     |
| Canon              | 1        | 20%     |
| Brother Industries | 1        | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| HP OfficeJet 5200 series    | 1        | 20%     |
| HP Ink Tank 110 series      | 1        | 20%     |
| Dymo-CoStar LabelWriter 450 | 1        | 20%     |
| Canon PIXMA MG3600 Series   | 1        | 20%     |
| Brother MFC-J5335DW         | 1        | 20%     |

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 9        | 37.5%   |
| Microdia                      | 3        | 12.5%   |
| Microsoft                     | 2        | 8.33%   |
| Chicony Electronics           | 2        | 8.33%   |
| Apple                         | 2        | 8.33%   |
| Z-Star Microelectronics       | 1        | 4.17%   |
| SunplusIT                     | 1        | 4.17%   |
| Sunplus Innovation Technology | 1        | 4.17%   |
| Razer USA                     | 1        | 4.17%   |
| ANYKA                         | 1        | 4.17%   |
| Alcor Micro                   | 1        | 4.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Logitech HD Webcam C615               | 2        | 8.33%   |
| Chicony HP High Definition 1MP Webcam | 2        | 8.33%   |
| Apple iPhone5/5C/5S/6                 | 2        | 8.33%   |
| Z-Star Vega USB 2.0 Camera            | 1        | 4.17%   |
| SunplusIT USB camera                  | 1        | 4.17%   |
| Sunplus HK 1080P K20Pro               | 1        | 4.17%   |
| Razer USA Razer Kiyo Pro              | 1        | 4.17%   |
| Microsoft LifeCam VX-800              | 1        | 4.17%   |
| Microsoft LifeCam HD-3000             | 1        | 4.17%   |
| Microdia USB 2.0 Camera               | 1        | 4.17%   |
| Microdia Integrated Camera            | 1        | 4.17%   |
| Microdia CameraA                      | 1        | 4.17%   |
| Logitech Webcam C925e                 | 1        | 4.17%   |
| Logitech Webcam C270                  | 1        | 4.17%   |
| Logitech QuickCam Communicate Deluxe  | 1        | 4.17%   |
| Logitech HD Webcam C910               | 1        | 4.17%   |
| Logitech C922 Pro Stream Webcam       | 1        | 4.17%   |
| Logitech BRIO 4K Stream Edition       | 1        | 4.17%   |
| Logitech B525 HD Webcam               | 1        | 4.17%   |
| ANYKA V380 FHD Camera                 | 1        | 4.17%   |
| Alcor Micro USB 2.0 PC Camera         | 1        | 4.17%   |

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


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| LighTuning Fingerprint Sensor | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Chicony Electronics | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Chicony Electronics HP Skylab USB Smartcard Keyboard | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 127      | 86.99%  |
| 1     | 14       | 9.59%   |
| 2     | 4        | 2.74%   |
| 4     | 1        | 0.68%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Desktops | Percent |
|-----------------------|----------|---------|
| Net/wireless          | 11       | 45.83%  |
| Graphics card         | 3        | 12.5%   |
| Bluetooth             | 3        | 12.5%   |
| Unassigned class      | 2        | 8.33%   |
| Sound                 | 2        | 8.33%   |
| Storage/ide           | 1        | 4.17%   |
| Multimedia controller | 1        | 4.17%   |
| Fingerprint reader    | 1        | 4.17%   |

