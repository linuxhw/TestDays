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

Total: 229

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | H110 Pro BTC+               | [a7ccef79ad](https://linux-hardware.org/?probe=a7ccef79ad) | Dec 30, 2022 |
| Gigabyte      | H61M-S2V-B3                 | [b3970a8e5a](https://linux-hardware.org/?probe=b3970a8e5a) | Dec 29, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [bc58be5546](https://linux-hardware.org/?probe=bc58be5546) | Dec 27, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [f9bde62142](https://linux-hardware.org/?probe=f9bde62142) | Dec 27, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [c545cf1f08](https://linux-hardware.org/?probe=c545cf1f08) | Dec 25, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [2fa8510855](https://linux-hardware.org/?probe=2fa8510855) | Dec 19, 2022 |
| Foxconn       | 2ABF                        | [10e579b77e](https://linux-hardware.org/?probe=10e579b77e) | Dec 18, 2022 |
| Dell          | 08WKV3 A00                  | [f58a0ffbc3](https://linux-hardware.org/?probe=f58a0ffbc3) | Dec 13, 2022 |
| ASUSTek       | Z170-P                      | [5180b907e3](https://linux-hardware.org/?probe=5180b907e3) | Dec 10, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [5ca8db90bb](https://linux-hardware.org/?probe=5ca8db90bb) | Dec 10, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [906e4966a6](https://linux-hardware.org/?probe=906e4966a6) | Dec 07, 2022 |
| ASRock        | H55M-LE                     | [9d2066a479](https://linux-hardware.org/?probe=9d2066a479) | Dec 03, 2022 |
| Fujitsu       | D3602-A1 S26361-D3602-A1    | [6f57ed994c](https://linux-hardware.org/?probe=6f57ed994c) | Dec 03, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [62b19626ce](https://linux-hardware.org/?probe=62b19626ce) | Dec 03, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [19d93a0122](https://linux-hardware.org/?probe=19d93a0122) | Dec 03, 2022 |
| Lenovo        | ThinkCentre M70e 0809D1Y    | [0cd85fa9f3](https://linux-hardware.org/?probe=0cd85fa9f3) | Nov 30, 2022 |
| Dell          | 0TP406                      | [3eceea61d2](https://linux-hardware.org/?probe=3eceea61d2) | Nov 30, 2022 |
| Dell          | 0TP406                      | [d22689331c](https://linux-hardware.org/?probe=d22689331c) | Nov 30, 2022 |
| LattePanda    | Alpha                       | [be819160d5](https://linux-hardware.org/?probe=be819160d5) | Nov 26, 2022 |
| LattePanda    | Alpha                       | [b3c831db4d](https://linux-hardware.org/?probe=b3c831db4d) | Nov 26, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [4f230635de](https://linux-hardware.org/?probe=4f230635de) | Nov 19, 2022 |
| Dell          | 0RW199                      | [df40ccbcdb](https://linux-hardware.org/?probe=df40ccbcdb) | Nov 15, 2022 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [4629fb5e08](https://linux-hardware.org/?probe=4629fb5e08) | Nov 13, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [ddca3f4758](https://linux-hardware.org/?probe=ddca3f4758) | Nov 06, 2022 |
| Gigabyte      | H310M S2H                   | [521297d21c](https://linux-hardware.org/?probe=521297d21c) | Nov 03, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [919fad100f](https://linux-hardware.org/?probe=919fad100f) | Oct 31, 2022 |
| ASUSTek       | PRIME X570-PRO              | [6d4b1d0bb3](https://linux-hardware.org/?probe=6d4b1d0bb3) | Oct 25, 2022 |
| HP            | 805D                        | [916b6f09ac](https://linux-hardware.org/?probe=916b6f09ac) | Oct 23, 2022 |
| MSI           | Z370 GAMING PLUS            | [ce623178a2](https://linux-hardware.org/?probe=ce623178a2) | Oct 16, 2022 |
| Dell          | 0D28YY A00                  | [435831fd5b](https://linux-hardware.org/?probe=435831fd5b) | Oct 15, 2022 |
| Kraftway      | KWQ67                       | [8346fc15e3](https://linux-hardware.org/?probe=8346fc15e3) | Oct 13, 2022 |
| Kraftway      | KWQ67                       | [d57d34be64](https://linux-hardware.org/?probe=d57d34be64) | Oct 13, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [88772ad191](https://linux-hardware.org/?probe=88772ad191) | Oct 11, 2022 |
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
| HP            | 2B43                        | [6f36772b0c](https://linux-hardware.org/?probe=6f36772b0c) | Jun 10, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [9756188040](https://linux-hardware.org/?probe=9756188040) | Jun 07, 2022 |
| MSI           | MPG X570S CARBON MAX WIF... | [0d57c069a8](https://linux-hardware.org/?probe=0d57c069a8) | Jun 05, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | [16f3fff6ad](https://linux-hardware.org/?probe=16f3fff6ad) | Jun 05, 2022 |
| Dell          | 0T7D40 A01                  | [812b41fe55](https://linux-hardware.org/?probe=812b41fe55) | Jun 04, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | [b3d970d061](https://linux-hardware.org/?probe=b3d970d061) | Jun 04, 2022 |
| MSI           | B85I                        | [5f29683d93](https://linux-hardware.org/?probe=5f29683d93) | Jun 03, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | [9f4aa60f60](https://linux-hardware.org/?probe=9f4aa60f60) | Jun 02, 2022 |
| ASUSTek       | P5B                         | [12554af571](https://linux-hardware.org/?probe=12554af571) | May 31, 2022 |
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
| 5.11.0-43-generic    | 33       | 17.74%  |
| 5.13.0-39-generic    | 17       | 9.14%   |
| 5.13.0-28-generic    | 16       | 8.6%    |
| 5.15.0-46-generic    | 14       | 7.53%   |
| 5.13.0-27-generic    | 10       | 5.38%   |
| 5.13.0-40-generic    | 9        | 4.84%   |
| 5.13.0-30-generic    | 9        | 4.84%   |
| 5.15.0-56-generic    | 7        | 3.76%   |
| 5.13.0-35-generic    | 7        | 3.76%   |
| 5.13.0-52-generic    | 5        | 2.69%   |
| 5.13.0-51-generic    | 5        | 2.69%   |
| 5.13.0-37-generic    | 5        | 2.69%   |
| 5.11.0-41-generic    | 5        | 2.69%   |
| 5.15.0-53-generic    | 4        | 2.15%   |
| 5.15.0-52-generic    | 4        | 2.15%   |
| 5.15.0-41-generic    | 4        | 2.15%   |
| 5.13.0-44-generic    | 4        | 2.15%   |
| 5.11.0-44-generic    | 4        | 2.15%   |
| 5.15.0-50-generic    | 3        | 1.61%   |
| 5.15.0-48-generic    | 3        | 1.61%   |
| 5.13.0-48-generic    | 3        | 1.61%   |
| 5.13.0-41-generic    | 2        | 1.08%   |
| 5.13.0-25-generic    | 2        | 1.08%   |
| 5.11.0-46-generic    | 2        | 1.08%   |
| 5.11.0-40-generic    | 2        | 1.08%   |
| 5.17.3-xanmod1       | 1        | 0.54%   |
| 5.15.36-xanmod1      | 1        | 0.54%   |
| 5.14.0-1042-oem      | 1        | 0.54%   |
| 5.13.0-28-lowlatency | 1        | 0.54%   |
| 5.13.0-22-generic    | 1        | 0.54%   |
| 5.11.0-43-lowlatency | 1        | 0.54%   |
| 5.11.0-37-generic    | 1        | 0.54%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13.0  | 86       | 50%     |
| 5.11.0  | 46       | 26.74%  |
| 5.15.0  | 37       | 21.51%  |
| 5.17.3  | 1        | 0.58%   |
| 5.15.36 | 1        | 0.58%   |
| 5.14.0  | 1        | 0.58%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13    | 86       | 50%     |
| 5.11    | 46       | 26.74%  |
| 5.15    | 38       | 22.09%  |
| 5.17    | 1        | 0.58%   |
| 5.14    | 1        | 0.58%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 165      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Pantheon | 164      | 99.39%  |
| KDE5     | 1        | 0.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 165      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 142      | 85.03%  |
| LightDM | 25       | 14.97%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 72       | 43.11%  |
| de_DE | 20       | 11.98%  |
| es_ES | 14       | 8.38%   |
| fr_FR | 12       | 7.19%   |
| ru_RU | 11       | 6.59%   |
| en_GB | 7        | 4.19%   |
| pt_BR | 6        | 3.59%   |
| it_IT | 5        | 2.99%   |
| pl_PL | 3        | 1.8%    |
| tr_TR | 2        | 1.2%    |
| pt_PT | 2        | 1.2%    |
| ja_JP | 2        | 1.2%    |
| en_CA | 2        | 1.2%    |
| zh_CN | 1        | 0.6%    |
| uk_UA | 1        | 0.6%    |
| sr_RS | 1        | 0.6%    |
| nl_NL | 1        | 0.6%    |
| id_ID | 1        | 0.6%    |
| fr_CA | 1        | 0.6%    |
| en_AU | 1        | 0.6%    |
| de_CH | 1        | 0.6%    |
| C     | 1        | 0.6%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 91       | 53.85%  |
| BIOS | 78       | 46.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 157      | 95.15%  |
| Btrfs   | 5        | 3.03%   |
| Xfs     | 2        | 1.21%   |
| Overlay | 1        | 0.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 146      | 87.95%  |
| GPT     | 15       | 9.04%   |
| MBR     | 5        | 3.01%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 159      | 95.21%  |
| Yes       | 8        | 4.79%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 155      | 93.37%  |
| Yes       | 11       | 6.63%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 45       | 27.27%  |
| Gigabyte Technology | 25       | 15.15%  |
| MSI                 | 19       | 11.52%  |
| Hewlett-Packard     | 13       | 7.88%   |
| ASRock              | 12       | 7.27%   |
| Dell                | 11       | 6.67%   |
| Lenovo              | 5        | 3.03%   |
| Foxconn             | 4        | 2.42%   |
| Biostar             | 4        | 2.42%   |
| Intel               | 3        | 1.82%   |
| Fujitsu             | 3        | 1.82%   |
| Apple               | 3        | 1.82%   |
| Pegatron            | 2        | 1.21%   |
| ECS                 | 2        | 1.21%   |
| Acer                | 2        | 1.21%   |
| Unknown             | 2        | 1.21%   |
| T-bao               | 1        | 0.61%   |
| Packard Bell        | 1        | 0.61%   |
| LORD ELECTRONICS    | 1        | 0.61%   |
| LattePanda          | 1        | 0.61%   |
| Kraftway            | 1        | 0.61%   |
| IceWhale Technology | 1        | 0.61%   |
| FIRICH              | 1        | 0.61%   |
| AZW                 | 1        | 0.61%   |
| AOpen               | 1        | 0.61%   |
| AMI                 | 1        | 0.61%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| ASUS All Series                                   | 4        | 2.42%   |
| MSI MS-7C35                                       | 2        | 1.21%   |
| HP Compaq Pro 6300 MT                             | 2        | 1.21%   |
| Gigabyte Z390 UD                                  | 2        | 1.21%   |
| Dell OptiPlex 790                                 | 2        | 1.21%   |
| ASUS TUF Gaming B550M-PLUS                        | 2        | 1.21%   |
| Unknown                                           | 2        | 1.21%   |
| T-bao MINI PC                                     | 1        | 0.61%   |
| Pegatron p7-1174                                  | 1        | 0.61%   |
| Pegatron IPMH61P1                                 | 1        | 0.61%   |
| Packard Bell IMEDIA S1300                         | 1        | 0.61%   |
| MSI PPPPP-CCC#MMMMMMMM                            | 1        | 0.61%   |
| MSI MS-7D52                                       | 1        | 0.61%   |
| MSI MS-7C91                                       | 1        | 0.61%   |
| MSI MS-7C77                                       | 1        | 0.61%   |
| MSI MS-7C52                                       | 1        | 0.61%   |
| MSI MS-7C02                                       | 1        | 0.61%   |
| MSI MS-7B86                                       | 1        | 0.61%   |
| MSI MS-7B84                                       | 1        | 0.61%   |
| MSI MS-7B79                                       | 1        | 0.61%   |
| MSI MS-7B61                                       | 1        | 0.61%   |
| MSI MS-7A59                                       | 1        | 0.61%   |
| MSI MS-7A40                                       | 1        | 0.61%   |
| MSI MS-7A38                                       | 1        | 0.61%   |
| MSI MS-7918                                       | 1        | 0.61%   |
| MSI MS-7885                                       | 1        | 0.61%   |
| MSI MS-7851                                       | 1        | 0.61%   |
| MSI MS-7817                                       | 1        | 0.61%   |
| LORD ELECTRONICS LORD G4x 775 ICH7 8712 As Design | 1        | 0.61%   |
| Lenovo ThinkCentre M73 10B6001SUS                 | 1        | 0.61%   |
| Lenovo ThinkCentre M72e 3664AD7                   | 1        | 0.61%   |
| Lenovo ThinkCentre M70e 0809D1Y                   | 1        | 0.61%   |
| Lenovo ThinkCentre M58 6258D3G                    | 1        | 0.61%   |
| Lenovo IdeaCentre 510S-07ICK 90LX006TGE           | 1        | 0.61%   |
| LattePanda Alpha                                  | 1        | 0.61%   |
| Kraftway Credo KCxx                               | 1        | 0.61%   |
| Intel X79                                         | 1        | 0.61%   |
| Intel H61                                         | 1        | 0.61%   |
| Intel DH61BE AAG14062-210                         | 1        | 0.61%   |
| IceWhale ZimaBoard 832 ZMB                        | 1        | 0.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 9        | 5.45%   |
| Dell OptiPlex          | 8        | 4.85%   |
| ASUS TUF               | 7        | 4.24%   |
| ASUS ROG               | 6        | 3.64%   |
| Lenovo ThinkCentre     | 4        | 2.42%   |
| HP Compaq              | 4        | 2.42%   |
| ASUS All               | 4        | 2.42%   |
| Fujitsu ESPRIMO        | 3        | 1.82%   |
| ASUS P8H61-M           | 3        | 1.82%   |
| MSI MS-7C35            | 2        | 1.21%   |
| HP ProDesk             | 2        | 1.21%   |
| Gigabyte Z390          | 2        | 1.21%   |
| Gigabyte H310M         | 2        | 1.21%   |
| Dell Precision         | 2        | 1.21%   |
| Unknown                | 2        | 1.21%   |
| T-bao MINI             | 1        | 0.61%   |
| Pegatron p7-1174       | 1        | 0.61%   |
| Pegatron IPMH61P1      | 1        | 0.61%   |
| Packard Bell IMEDIA    | 1        | 0.61%   |
| MSI PPPPP-CCC#MMMMMMMM | 1        | 0.61%   |
| MSI MS-7D52            | 1        | 0.61%   |
| MSI MS-7C91            | 1        | 0.61%   |
| MSI MS-7C77            | 1        | 0.61%   |
| MSI MS-7C52            | 1        | 0.61%   |
| MSI MS-7C02            | 1        | 0.61%   |
| MSI MS-7B86            | 1        | 0.61%   |
| MSI MS-7B84            | 1        | 0.61%   |
| MSI MS-7B79            | 1        | 0.61%   |
| MSI MS-7B61            | 1        | 0.61%   |
| MSI MS-7A59            | 1        | 0.61%   |
| MSI MS-7A40            | 1        | 0.61%   |
| MSI MS-7A38            | 1        | 0.61%   |
| MSI MS-7918            | 1        | 0.61%   |
| MSI MS-7885            | 1        | 0.61%   |
| MSI MS-7851            | 1        | 0.61%   |
| MSI MS-7817            | 1        | 0.61%   |
| LORD ELECTRONICS LORD  | 1        | 0.61%   |
| Lenovo IdeaCentre      | 1        | 0.61%   |
| LattePanda Alpha       | 1        | 0.61%   |
| Kraftway Credo         | 1        | 0.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 21       | 12.73%  |
| 2018 | 20       | 12.12%  |
| 2010 | 16       | 9.7%    |
| 2019 | 15       | 9.09%   |
| 2020 | 14       | 8.48%   |
| 2011 | 14       | 8.48%   |
| 2015 | 11       | 6.67%   |
| 2014 | 11       | 6.67%   |
| 2021 | 9        | 5.45%   |
| 2017 | 9        | 5.45%   |
| 2013 | 9        | 5.45%   |
| 2016 | 5        | 3.03%   |
| 2022 | 3        | 1.82%   |
| 2008 | 3        | 1.82%   |
| 2009 | 2        | 1.21%   |
| 2007 | 2        | 1.21%   |
| 2006 | 1        | 0.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 165      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 156      | 94.55%  |
| Enabled  | 9        | 5.45%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 165      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 35       | 21.08%  |
| 8.01-16.0   | 35       | 21.08%  |
| 32.01-64.0  | 32       | 19.28%  |
| 4.01-8.0    | 27       | 16.27%  |
| 3.01-4.0    | 25       | 15.06%  |
| 64.01-256.0 | 6        | 3.61%   |
| 1.01-2.0    | 3        | 1.81%   |
| 24.01-32.0  | 2        | 1.2%    |
| 2.01-3.0    | 1        | 0.6%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 67       | 36.41%  |
| 2.01-3.0  | 53       | 28.8%   |
| 4.01-8.0  | 32       | 17.39%  |
| 3.01-4.0  | 22       | 11.96%  |
| 8.01-16.0 | 6        | 3.26%   |
| 0.51-1.0  | 4        | 2.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 56       | 33.33%  |
| 2      | 55       | 32.74%  |
| 3      | 28       | 16.67%  |
| 4      | 17       | 10.12%  |
| 5      | 5        | 2.98%   |
| 6      | 4        | 2.38%   |
| 7      | 2        | 1.19%   |
| 0      | 1        | 0.6%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 91       | 54.49%  |
| Yes       | 76       | 45.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 165      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 86       | 51.19%  |
| Yes       | 82       | 48.81%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 101      | 60.84%  |
| Yes       | 65       | 39.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 27       | 16.36%  |
| Germany      | 19       | 11.52%  |
| Russia       | 11       | 6.67%   |
| UK           | 9        | 5.45%   |
| France       | 9        | 5.45%   |
| Brazil       | 9        | 5.45%   |
| Spain        | 8        | 4.85%   |
| Indonesia    | 6        | 3.64%   |
| Canada       | 6        | 3.64%   |
| Switzerland  | 5        | 3.03%   |
| Italy        | 5        | 3.03%   |
| Poland       | 4        | 2.42%   |
| Turkey       | 3        | 1.82%   |
| Japan        | 3        | 1.82%   |
| India        | 3        | 1.82%   |
| Colombia     | 3        | 1.82%   |
| Australia    | 3        | 1.82%   |
| Argentina    | 3        | 1.82%   |
| Netherlands  | 2        | 1.21%   |
| Iran         | 2        | 1.21%   |
| Austria      | 2        | 1.21%   |
| Thailand     | 1        | 0.61%   |
| Sweden       | 1        | 0.61%   |
| Sri Lanka    | 1        | 0.61%   |
| South Africa | 1        | 0.61%   |
| Slovenia     | 1        | 0.61%   |
| Serbia       | 1        | 0.61%   |
| Romania      | 1        | 0.61%   |
| Portugal     | 1        | 0.61%   |
| Norway       | 1        | 0.61%   |
| New Zealand  | 1        | 0.61%   |
| Mexico       | 1        | 0.61%   |
| Malaysia     | 1        | 0.61%   |
| Lithuania    | 1        | 0.61%   |
| Libya        | 1        | 0.61%   |
| Kenya        | 1        | 0.61%   |
| Israel       | 1        | 0.61%   |
| Ireland      | 1        | 0.61%   |
| Hong Kong    | 1        | 0.61%   |
| Guyana       | 1        | 0.61%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Desktops | Percent |
|---------------|----------|---------|
| Moscow        | 4        | 2.26%   |
| Warsaw        | 3        | 1.69%   |
| Hamburg       | 3        | 1.69%   |
| Caslano       | 3        | 1.69%   |
| Tangerang     | 2        | 1.13%   |
| Sao Paulo     | 2        | 1.13%   |
| Paris         | 2        | 1.13%   |
| Istanbul      | 2        | 1.13%   |
| Denver        | 2        | 1.13%   |
| Brisbane      | 2        | 1.13%   |
| Bandung       | 2        | 1.13%   |
| Yucca Valley  | 1        | 0.56%   |
| Yokohama      | 1        | 0.56%   |
| Yarang        | 1        | 0.56%   |
| Wroclaw       | 1        | 0.56%   |
| Woolloongabba | 1        | 0.56%   |
| Woodbridge    | 1        | 0.56%   |
| Wolgast       | 1        | 0.56%   |
| Werneck       | 1        | 0.56%   |
| Walnut Creek  | 1        | 0.56%   |
| Vienna        | 1        | 0.56%   |
| Vanse         | 1        | 0.56%   |
| Troisdorf     | 1        | 0.56%   |
| Tripoli       | 1        | 0.56%   |
| Tournus       | 1        | 0.56%   |
| Toronto       | 1        | 0.56%   |
| Thrissur      | 1        | 0.56%   |
| Teresina      | 1        | 0.56%   |
| Tel Aviv      | 1        | 0.56%   |
| Tehran        | 1        | 0.56%   |
| Tacoma        | 1        | 0.56%   |
| Sydney        | 1        | 0.56%   |
| Suresnes      | 1        | 0.56%   |
| Surabaya      | 1        | 0.56%   |
| Stuttgart     | 1        | 0.56%   |
| Spello        | 1        | 0.56%   |
| Songkhla      | 1        | 0.56%   |
| Sollentuna    | 1        | 0.56%   |
| Sentmenat     | 1        | 0.56%   |
| Sarrebourg    | 1        | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 53       | 81     | 17.26%  |
| Seagate                     | 49       | 70     | 15.96%  |
| Samsung Electronics         | 43       | 67     | 14.01%  |
| Kingston                    | 25       | 33     | 8.14%   |
| Toshiba                     | 19       | 27     | 6.19%   |
| Crucial                     | 11       | 14     | 3.58%   |
| SanDisk                     | 10       | 12     | 3.26%   |
| Unknown                     | 7        | 15     | 2.28%   |
| PNY                         | 7        | 11     | 2.28%   |
| Micron/Crucial Technology   | 6        | 9      | 1.95%   |
| Intel                       | 6        | 6      | 1.95%   |
| Hitachi                     | 6        | 7      | 1.95%   |
| Phison                      | 5        | 5      | 1.63%   |
| A-DATA Technology           | 5        | 5      | 1.63%   |
| China                       | 4        | 6      | 1.3%    |
| Team                        | 3        | 4      | 0.98%   |
| Micron Technology           | 3        | 4      | 0.98%   |
| Maxtor                      | 3        | 3      | 0.98%   |
| JMicron Technology          | 3        | 3      | 0.98%   |
| ASMT                        | 3        | 3      | 0.98%   |
| Transcend                   | 2        | 2      | 0.65%   |
| SPCC                        | 2        | 2      | 0.65%   |
| Silicon Motion              | 2        | 2      | 0.65%   |
| Realtek Semiconductor       | 2        | 2      | 0.65%   |
| Plextor                     | 2        | 3      | 0.65%   |
| LITEON                      | 2        | 2      | 0.65%   |
| HUSKY                       | 2        | 2      | 0.65%   |
| HGST                        | 2        | 2      | 0.65%   |
| Corsair                     | 2        | 2      | 0.65%   |
| XPG                         | 1        | 1      | 0.33%   |
| tigo                        | 1        | 1      | 0.33%   |
| Phison Electronics          | 1        | 1      | 0.33%   |
| OCZ-VERTEX2                 | 1        | 1      | 0.33%   |
| OCZ                         | 1        | 3      | 0.33%   |
| Netac                       | 1        | 1      | 0.33%   |
| MidasForce                  | 1        | 1      | 0.33%   |
| Lexar                       | 1        | 1      | 0.33%   |
| Leven                       | 1        | 1      | 0.33%   |
| Kingston Technology Company | 1        | 1      | 0.33%   |
| KingFast                    | 1        | 1      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Drive 500GB                        | 7        | 2.01%   |
| Toshiba DT01ACA050 500GB                            | 5        | 1.44%   |
| WDC WD5000AAKX-00ERMA0 500GB                        | 4        | 1.15%   |
| Seagate ST1000DM003-1ER162 1TB                      | 4        | 1.15%   |
| Samsung SSD 860 EVO 250GB                           | 4        | 1.15%   |
| Micron/Crucial NVMe SSD Drive 1TB                   | 4        | 1.15%   |
| Kingston SA400S37240G 240GB SSD                     | 4        | 1.15%   |
| Kingston SA400S37120G 120GB SSD                     | 4        | 1.15%   |
| Crucial CT240BX500SSD1 240GB                        | 4        | 1.15%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 3        | 0.86%   |
| Unknown SD/MMC 2GB                                  | 3        | 0.86%   |
| Unknown M.S./M.S.Pro/HG 16GB                        | 3        | 0.86%   |
| Toshiba DT01ACA100 1TB                              | 3        | 0.86%   |
| Seagate ST500DM002-1BD142 500GB                     | 3        | 0.86%   |
| Seagate ST3500418AS 500GB                           | 3        | 0.86%   |
| Seagate ST1000DM010-2EP102 1TB                      | 3        | 0.86%   |
| Samsung SSD 860 EVO 1TB                             | 3        | 0.86%   |
| Samsung SSD 850 EVO 250GB                           | 3        | 0.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 3        | 0.86%   |
| Phison NVMe SSD Drive 1TB                           | 3        | 0.86%   |
| Kingston SV300S37A120G 120GB SSD                    | 3        | 0.86%   |
| Kingston NVMe SSD Drive 1TB                         | 3        | 0.86%   |
| WDC WD5000AAKX-001CA0 500GB                         | 2        | 0.57%   |
| WDC WD5000AAKS-00UU3A0 500GB                        | 2        | 0.57%   |
| WDC WD40EFRX-68N32N0 4TB                            | 2        | 0.57%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 2        | 0.57%   |
| WDC WD10EADS-00L5B1 1TB                             | 2        | 0.57%   |
| Unknown MMC Card  32GB                              | 2        | 0.57%   |
| Toshiba HDWD110 1TB                                 | 2        | 0.57%   |
| Seagate ST3500630AS 500GB                           | 2        | 0.57%   |
| Seagate ST3160815AS 160GB                           | 2        | 0.57%   |
| Seagate ST31000528AS 1TB                            | 2        | 0.57%   |
| Seagate ST2000DX002-2DV164 2TB                      | 2        | 0.57%   |
| Seagate ST2000DM001-9YN164 2TB                      | 2        | 0.57%   |
| Seagate ST1000DM003-1CH162 1TB                      | 2        | 0.57%   |
| Samsung SSD 870 EVO 1TB                             | 2        | 0.57%   |
| Samsung SSD 860 QVO 1TB                             | 2        | 0.57%   |
| Samsung SSD 860 EVO 500GB                           | 2        | 0.57%   |
| Samsung SSD 850 PRO 256GB                           | 2        | 0.57%   |
| Samsung SSD 840 EVO 250GB                           | 2        | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 46       | 66     | 34.59%  |
| WDC                 | 45       | 63     | 33.83%  |
| Toshiba             | 18       | 26     | 13.53%  |
| Samsung Electronics | 9        | 10     | 6.77%   |
| Hitachi             | 6        | 7      | 4.51%   |
| Maxtor              | 2        | 2      | 1.5%    |
| HGST                | 2        | 2      | 1.5%    |
| ASMT                | 2        | 2      | 1.5%    |
| Unknown             | 1        | 1      | 0.75%   |
| Hewlett-Packard     | 1        | 1      | 0.75%   |
| Fujitsu             | 1        | 1      | 0.75%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 24       | 36     | 20.34%  |
| Kingston            | 19       | 23     | 16.1%   |
| Crucial             | 10       | 12     | 8.47%   |
| SanDisk             | 9        | 10     | 7.63%   |
| WDC                 | 7        | 12     | 5.93%   |
| PNY                 | 7        | 11     | 5.93%   |
| China               | 4        | 6      | 3.39%   |
| A-DATA Technology   | 4        | 4      | 3.39%   |
| Team                | 3        | 4      | 2.54%   |
| Intel               | 3        | 3      | 2.54%   |
| Transcend           | 2        | 2      | 1.69%   |
| SPCC                | 2        | 2      | 1.69%   |
| Plextor             | 2        | 3      | 1.69%   |
| Micron Technology   | 2        | 2      | 1.69%   |
| LITEON              | 2        | 2      | 1.69%   |
| HUSKY               | 2        | 2      | 1.69%   |
| Corsair             | 2        | 2      | 1.69%   |
| Toshiba             | 1        | 1      | 0.85%   |
| tigo                | 1        | 1      | 0.85%   |
| Seagate             | 1        | 2      | 0.85%   |
| OCZ-VERTEX2         | 1        | 1      | 0.85%   |
| OCZ                 | 1        | 3      | 0.85%   |
| MidasForce          | 1        | 1      | 0.85%   |
| Maxtor              | 1        | 1      | 0.85%   |
| Lexar               | 1        | 1      | 0.85%   |
| Leven               | 1        | 1      | 0.85%   |
| JMicron Technology  | 1        | 1      | 0.85%   |
| Intenso             | 1        | 1      | 0.85%   |
| GOODRAM             | 1        | 1      | 0.85%   |
| Gigabyte Technology | 1        | 1      | 0.85%   |
| ASMT                | 1        | 1      | 0.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 108      | 181    | 40.45%  |
| SSD     | 101      | 153    | 37.83%  |
| NVMe    | 45       | 67     | 16.85%  |
| Unknown | 10       | 21     | 3.75%   |
| MMC     | 3        | 3      | 1.12%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 150      | 330    | 70.42%  |
| NVMe | 45       | 67     | 21.13%  |
| SAS  | 15       | 25     | 7.04%   |
| MMC  | 3        | 3      | 1.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 118      | 201    | 58.71%  |
| 0.51-1.0   | 48       | 84     | 23.88%  |
| 1.01-2.0   | 15       | 18     | 7.46%   |
| 2.01-3.0   | 7        | 15     | 3.48%   |
| 4.01-10.0  | 7        | 10     | 3.48%   |
| 3.01-4.0   | 5        | 5      | 2.49%   |
| 10.01-20.0 | 1        | 1      | 0.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 58       | 33.53%  |
| 251-500        | 39       | 22.54%  |
| 501-1000       | 32       | 18.5%   |
| 1001-2000      | 17       | 9.83%   |
| 51-100         | 10       | 5.78%   |
| More than 3000 | 9        | 5.2%    |
| 21-50          | 5        | 2.89%   |
| 2001-3000      | 3        | 1.73%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 72       | 39.34%  |
| 21-50          | 28       | 15.3%   |
| 101-250        | 27       | 14.75%  |
| 51-100         | 22       | 12.02%  |
| 251-500        | 14       | 7.65%   |
| 501-1000       | 10       | 5.46%   |
| 1001-2000      | 6        | 3.28%   |
| More than 3000 | 3        | 1.64%   |
| 2001-3000      | 1        | 0.55%   |

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
| Detected | 149      | 381    | 88.17%  |
| Works    | 17       | 41     | 10.06%  |
| Malfunc  | 3        | 3      | 1.78%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 113      | 49.78%  |
| AMD                         | 42       | 18.5%   |
| Samsung Electronics         | 18       | 7.93%   |
| Nvidia                      | 8        | 3.52%   |
| Micron/Crucial Technology   | 7        | 3.08%   |
| Kingston Technology Company | 7        | 3.08%   |
| Phison Electronics          | 6        | 2.64%   |
| ASMedia Technology          | 5        | 2.2%    |
| SanDisk                     | 4        | 1.76%   |
| Marvell Technology Group    | 4        | 1.76%   |
| Realtek Semiconductor       | 3        | 1.32%   |
| Silicon Motion              | 2        | 0.88%   |
| Seagate Technology          | 2        | 0.88%   |
| LSI Logic / Symbios Logic   | 2        | 0.88%   |
| JMicron Technology          | 2        | 0.88%   |
| Micron Technology           | 1        | 0.44%   |
| ADATA Technology            | 1        | 0.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 26       | 9.29%   |
| AMD 400 Series Chipset SATA Controller                                                  | 15       | 5.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 14       | 5%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 11       | 3.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 10       | 3.57%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 10       | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 10       | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 10       | 3.57%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 8        | 2.86%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 8        | 2.86%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7        | 2.5%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 6        | 2.14%   |
| Nvidia MCP61 SATA Controller                                                            | 5        | 1.79%   |
| Kingston Company A2000 NVMe SSD                                                         | 5        | 1.79%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 1.79%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5        | 1.79%   |
| AMD 500 Series Chipset SATA Controller                                                  | 5        | 1.79%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 1.43%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 1.43%   |
| Phison E12 NVMe Controller                                                              | 3        | 1.07%   |
| Nvidia MCP61 IDE                                                                        | 3        | 1.07%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 1.07%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 1.07%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 1.07%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 0.71%   |
| Samsung NVMe SSD Controller 980                                                         | 2        | 0.71%   |
| Realtek Realtek Non-Volatile memory controller                                          | 2        | 0.71%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 0.71%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 2        | 0.71%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2        | 0.71%   |
| Intel SSD 660P Series                                                                   | 2        | 0.71%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2        | 0.71%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 0.71%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 0.71%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2        | 0.71%   |
| Intel 631xESB/632xESB SATA AHCI Controller                                              | 2        | 0.71%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 2        | 0.71%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                              | 2        | 0.71%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 0.71%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 128      | 56.89%  |
| NVMe | 45       | 20%     |
| IDE  | 41       | 18.22%  |
| RAID | 9        | 4%      |
| SAS  | 1        | 0.44%   |
| SCSI | 1        | 0.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 116      | 70.3%   |
| AMD    | 49       | 29.7%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor          | 5        | 3.03%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 4        | 2.42%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 4        | 2.42%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 4        | 2.42%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 3        | 1.82%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 3        | 1.82%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 1.82%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3        | 1.82%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 1.82%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz     | 3        | 1.82%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 3        | 1.82%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 3        | 1.82%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 2        | 1.21%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 1.21%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 1.21%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 2        | 1.21%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 2        | 1.21%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 2        | 1.21%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2        | 1.21%   |
| Intel Core i3 CPU 530 @ 2.93GHz             | 2        | 1.21%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 2        | 1.21%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 2        | 1.21%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 2        | 1.21%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 2        | 1.21%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2        | 1.21%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 2        | 1.21%   |
| Intel Xeon CPU X5680 @ 3.33GHz              | 1        | 0.61%   |
| Intel Xeon CPU E5462 @ 2.80GHz              | 1        | 0.61%   |
| Intel Xeon CPU E5410 @ 2.33GHz              | 1        | 0.61%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1        | 0.61%   |
| Intel Xeon CPU E5-2665 0 @ 2.40GHz          | 1        | 0.61%   |
| Intel Xeon CPU E5-1660 0 @ 3.30GHz          | 1        | 0.61%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz         | 1        | 0.61%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz         | 1        | 0.61%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz         | 1        | 0.61%   |
| Intel Xeon CPU E31270 @ 3.40GHz             | 1        | 0.61%   |
| Intel Xeon CPU E31240 @ 3.30GHz             | 1        | 0.61%   |
| Intel Xeon CPU E3-1283L v4 @ 2.90GHz        | 1        | 0.61%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz         | 1        | 0.61%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1        | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 29       | 17.58%  |
| Intel Core i7           | 26       | 15.76%  |
| Intel Core i3           | 18       | 10.91%  |
| Intel Xeon              | 13       | 7.88%   |
| AMD Ryzen 5             | 13       | 7.88%   |
| AMD Ryzen 7             | 11       | 6.67%   |
| AMD Ryzen 9             | 6        | 3.64%   |
| Other                   | 5        | 3.03%   |
| Intel Celeron           | 5        | 3.03%   |
| Intel Pentium           | 4        | 2.42%   |
| AMD Athlon II X2        | 4        | 2.42%   |
| Intel Pentium Dual-Core | 3        | 1.82%   |
| Intel Core 2 Quad       | 3        | 1.82%   |
| Intel Core 2 Duo        | 3        | 1.82%   |
| Intel Atom              | 3        | 1.82%   |
| AMD Phenom II X4        | 3        | 1.82%   |
| AMD FX                  | 3        | 1.82%   |
| Intel Core i9           | 2        | 1.21%   |
| AMD Athlon              | 2        | 1.21%   |
| AMD A8                  | 2        | 1.21%   |
| AMD A10                 | 2        | 1.21%   |
| Intel Pentium Gold      | 1        | 0.61%   |
| Intel Core m3           | 1        | 0.61%   |
| AMD Ryzen 3             | 1        | 0.61%   |
| AMD Athlon X4           | 1        | 0.61%   |
| AMD Athlon II X4        | 1        | 0.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 69       | 41.32%  |
| 2      | 41       | 24.55%  |
| 8      | 24       | 14.37%  |
| 6      | 22       | 13.17%  |
| 12     | 6        | 3.59%   |
| 16     | 2        | 1.2%    |
| 1      | 2        | 1.2%    |
| 3      | 1        | 0.6%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 163      | 98.79%  |
| 2      | 2        | 1.21%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 98       | 59.04%  |
| 1      | 68       | 40.96%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 165      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x206a7    | 19       | 11.31%  |
| 0x306c3    | 15       | 8.93%   |
| 0x306a9    | 11       | 6.55%   |
| Unknown    | 10       | 5.95%   |
| 0x08701021 | 8        | 4.76%   |
| 0x906ea    | 6        | 3.57%   |
| 0x906ed    | 5        | 2.98%   |
| 0x906e9    | 5        | 2.98%   |
| 0x506e3    | 5        | 2.98%   |
| 0x1067a    | 5        | 2.98%   |
| 0x0800820d | 5        | 2.98%   |
| 0x906eb    | 4        | 2.38%   |
| 0x0a201016 | 4        | 2.38%   |
| 0x08108109 | 4        | 2.38%   |
| 0xa0671    | 3        | 1.79%   |
| 0x6fb      | 3        | 1.79%   |
| 0x206d7    | 3        | 1.79%   |
| 0x06003106 | 3        | 1.79%   |
| 0x010000c8 | 3        | 1.79%   |
| 0xa0655    | 2        | 1.19%   |
| 0xa0653    | 2        | 1.19%   |
| 0x406c4    | 2        | 1.19%   |
| 0x306e4    | 2        | 1.19%   |
| 0x20655    | 2        | 1.19%   |
| 0x20652    | 2        | 1.19%   |
| 0x106e5    | 2        | 1.19%   |
| 0x10676    | 2        | 1.19%   |
| 0x0a50000c | 2        | 1.19%   |
| 0x08701013 | 2        | 1.19%   |
| 0x08001138 | 2        | 1.19%   |
| 0x06000852 | 2        | 1.19%   |
| 0x010000c7 | 2        | 1.19%   |
| 0x906ec    | 1        | 0.6%    |
| 0x90672    | 1        | 0.6%    |
| 0x806e9    | 1        | 0.6%    |
| 0x806c1    | 1        | 0.6%    |
| 0x706a8    | 1        | 0.6%    |
| 0x6f7      | 1        | 0.6%    |
| 0x506c9    | 1        | 0.6%    |
| 0x40671    | 1        | 0.6%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| SandyBridge      | 23       | 13.94%  |
| KabyLake         | 23       | 13.94%  |
| Haswell          | 17       | 10.3%   |
| IvyBridge        | 13       | 7.88%   |
| Zen+             | 10       | 6.06%   |
| Zen 2            | 10       | 6.06%   |
| Zen 3            | 9        | 5.45%   |
| K10              | 8        | 4.85%   |
| Penryn           | 7        | 4.24%   |
| Westmere         | 5        | 3.03%   |
| Skylake          | 5        | 3.03%   |
| Zen              | 4        | 2.42%   |
| Core             | 4        | 2.42%   |
| CometLake        | 4        | 2.42%   |
| Steamroller      | 3        | 1.82%   |
| Silvermont       | 3        | 1.82%   |
| Piledriver       | 3        | 1.82%   |
| Nehalem          | 3        | 1.82%   |
| Icelake          | 3        | 1.82%   |
| TigerLake        | 1        | 0.61%   |
| K10 Llano        | 1        | 0.61%   |
| Goldmont plus    | 1        | 0.61%   |
| Goldmont         | 1        | 0.61%   |
| Bulldozer        | 1        | 0.61%   |
| Broadwell        | 1        | 0.61%   |
| Bonnell          | 1        | 0.61%   |
| Alderlake Hybrid | 1        | 0.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 64       | 36.57%  |
| Nvidia | 57       | 32.57%  |
| Intel  | 54       | 30.86%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15       | 8.29%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 10       | 5.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7        | 3.87%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 7        | 3.87%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4        | 2.21%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 4        | 2.21%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 3        | 1.66%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 3        | 1.66%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3        | 1.66%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                                           | 3        | 1.66%   |
| Intel HD Graphics 530                                                                    | 3        | 1.66%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3        | 1.66%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 3        | 1.66%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 3        | 1.66%   |
| Nvidia TU106 [GeForce GTX 1650]                                                          | 2        | 1.1%    |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 2        | 1.1%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2        | 1.1%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2        | 1.1%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 2        | 1.1%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 2        | 1.1%    |
| Nvidia GF108 [GeForce GT 730]                                                            | 2        | 1.1%    |
| Nvidia GF108 [GeForce GT 430]                                                            | 2        | 1.1%    |
| Intel HD Graphics 630                                                                    | 2        | 1.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 1.1%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 1.1%    |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                                        | 2        | 1.1%    |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 2        | 1.1%    |
| AMD Park [Mobility Radeon HD 5430]                                                       | 2        | 1.1%    |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                               | 2        | 1.1%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2        | 1.1%    |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                                         | 2        | 1.1%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2        | 1.1%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2        | 1.1%    |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 2        | 1.1%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1        | 0.55%   |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 1        | 0.55%   |
| Nvidia TU104 [GeForce RTX 2080]                                                          | 1        | 0.55%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1        | 0.55%   |
| Nvidia TU104 [GeForce RTX 2060]                                                          | 1        | 0.55%   |
| Nvidia GT218 [GeForce 210]                                                               | 1        | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 57       | 34.13%  |
| 1 x Nvidia     | 52       | 31.14%  |
| 1 x Intel      | 47       | 28.14%  |
| 2 x AMD        | 4        | 2.4%    |
| 2 x Nvidia     | 2        | 1.2%    |
| Intel + Nvidia | 2        | 1.2%    |
| Intel + AMD    | 2        | 1.2%    |
| AMD + Nvidia   | 1        | 0.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 135      | 80.84%  |
| Proprietary | 31       | 18.56%  |
| Unknown     | 1        | 0.6%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 53       | 30.99%  |
| 1.01-2.0   | 26       | 15.2%   |
| 0.51-1.0   | 26       | 15.2%   |
| 3.01-4.0   | 23       | 13.45%  |
| 7.01-8.0   | 14       | 8.19%   |
| 0.01-0.5   | 10       | 5.85%   |
| 5.01-6.0   | 8        | 4.68%   |
| 8.01-16.0  | 6        | 3.51%   |
| 2.01-3.0   | 5        | 2.92%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 29       | 15.59%  |
| Dell                 | 20       | 10.75%  |
| Goldstar             | 19       | 10.22%  |
| Hewlett-Packard      | 18       | 9.68%   |
| Acer                 | 16       | 8.6%    |
| Philips              | 11       | 5.91%   |
| AOC                  | 11       | 5.91%   |
| Lenovo               | 6        | 3.23%   |
| BenQ                 | 6        | 3.23%   |
| Ancor Communications | 6        | 3.23%   |
| LG Electronics       | 4        | 2.15%   |
| Vizio                | 3        | 1.61%   |
| Unknown              | 3        | 1.61%   |
| AUS                  | 3        | 1.61%   |
| Sony                 | 2        | 1.08%   |
| Sharp                | 2        | 1.08%   |
| NEC Computers        | 2        | 1.08%   |
| Iiyama               | 2        | 1.08%   |
| HPN                  | 2        | 1.08%   |
| Fujitsu Siemens      | 2        | 1.08%   |
| ___                  | 1        | 0.54%   |
| ViewSonic            | 1        | 0.54%   |
| Vestel               | 1        | 0.54%   |
| SPC                  | 1        | 0.54%   |
| Onkyo                | 1        | 0.54%   |
| MSI                  | 1        | 0.54%   |
| Mi                   | 1        | 0.54%   |
| LLP                  | 1        | 0.54%   |
| IOD                  | 1        | 0.54%   |
| Hitachi              | 1        | 0.54%   |
| HannStar             | 1        | 0.54%   |
| Gateway              | 1        | 0.54%   |
| Element              | 1        | 0.54%   |
| Eizo                 | 1        | 0.54%   |
| CHR                  | 1        | 0.54%   |
| CHD                  | 1        | 0.54%   |
| BOE                  | 1        | 0.54%   |
| Apple                | 1        | 0.54%   |
| Unknown              | 1        | 0.54%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3        | 1.51%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                       | 2        | 1.01%   |
| Hewlett-Packard 2010 HWP2889 1600x900 443x250mm 20.0-inch             | 2        | 1.01%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2        | 1.01%   |
| Goldstar 22EN33 GSM597C 1920x1080 480x270mm 21.7-inch                 | 2        | 1.01%   |
| Dell 1704FPV DEL3016 1280x1024 338x270mm 17.0-inch                    | 2        | 1.01%   |
| BenQ EL2870U BNQ7949 3840x2160 621x341mm 27.9-inch                    | 2        | 1.01%   |
| AOC 27V2G5 AOC2702 1920x1080 598x336mm 27.0-inch                      | 2        | 1.01%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 2        | 1.01%   |
| ___ LCDTV16 ___9000 1360x768                                          | 1        | 0.5%    |
| Vizio VW37L HDTV40A VIZ0035 1366x768 780x520mm 36.9-inch              | 1        | 0.5%    |
| Vizio E280i-B1 VIZ1002 1360x768 607x345mm 27.5-inch                   | 1        | 0.5%    |
| Vizio E241i-B1 VIZ1005 1920x1080 521x293mm 23.5-inch                  | 1        | 0.5%    |
| ViewSonic LCD Monitor VX2260WM 3840x1080                              | 1        | 0.5%    |
| ViewSonic LCD Monitor VX2260WM                                        | 1        | 0.5%    |
| Vestel LCD Monitor 49FHD_LCD_TV 1920x1080                             | 1        | 0.5%    |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                    | 1        | 0.5%    |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 1        | 0.5%    |
| Unknown LCD Monitor Bit 3 LE2262 1680x1050                            | 1        | 0.5%    |
| SPC LCD Monitor SPC1900 1440x900 368x207mm 16.6-inch                  | 1        | 0.5%    |
| Sony TV SNYD703 1360x768                                              | 1        | 0.5%    |
| Sony TV  *00 SNY8004 3840x2160 1440x810mm 65.0-inch                   | 1        | 0.5%    |
| Sharp HDMI SHP108E 1360x768 820x460mm 37.0-inch                       | 1        | 0.5%    |
| Sharp HDMI SHP1048 1920x1080 1330x750mm 60.1-inch                     | 1        | 0.5%    |
| Samsung Electronics T24D391 SAM0B72 1920x1080 521x293mm 23.5-inch     | 1        | 0.5%    |
| Samsung Electronics T22C310 SAM0AE9 1920x1080 480x270mm 21.7-inch     | 1        | 0.5%    |
| Samsung Electronics SyncMaster SAM0580 1280x1024 376x301mm 19.0-inch  | 1        | 0.5%    |
| Samsung Electronics SyncMaster SAM0423 1920x1080                      | 1        | 0.5%    |
| Samsung Electronics SyncMaster SAM0421 1920x1200 518x324mm 24.1-inch  | 1        | 0.5%    |
| Samsung Electronics SyncMaster SAM0380 1680x1050 459x296mm 21.5-inch  | 1        | 0.5%    |
| Samsung Electronics SyncMaster SAM0259 1280x1024 376x301mm 19.0-inch  | 1        | 0.5%    |
| Samsung Electronics SMBX2035 SAM06FD 1600x900 443x249mm 20.0-inch     | 1        | 0.5%    |
| Samsung Electronics SA300/SA350 SAM078C 1600x900 443x249mm 20.0-inch  | 1        | 0.5%    |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch  | 1        | 0.5%    |
| Samsung Electronics S27R35x SAM1053 1920x1080 598x336mm 27.0-inch     | 1        | 0.5%    |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch     | 1        | 0.5%    |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch     | 1        | 0.5%    |
| Samsung Electronics S22C450 SAM09C7 1680x1050 473x291mm 21.9-inch     | 1        | 0.5%    |
| Samsung Electronics S22B300 SAM08AC 1920x1080 477x268mm 21.5-inch     | 1        | 0.5%    |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch      | 1        | 0.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 75       | 39.89%  |
| 3840x2160 (4K)     | 17       | 9.04%   |
| 1680x1050 (WSXGA+) | 17       | 9.04%   |
| 2560x1440 (QHD)    | 13       | 6.91%   |
| 1366x768 (WXGA)    | 12       | 6.38%   |
| 1280x1024 (SXGA)   | 11       | 5.85%   |
| 1600x900 (HD+)     | 8        | 4.26%   |
| 1440x900 (WXGA+)   | 7        | 3.72%   |
| 3840x1080          | 5        | 2.66%   |
| 1360x768           | 5        | 2.66%   |
| Unknown            | 5        | 2.66%   |
| 1920x1200 (WUXGA)  | 4        | 2.13%   |
| 3440x1440          | 3        | 1.6%    |
| 5120x1440          | 2        | 1.06%   |
| 2560x1080          | 2        | 1.06%   |
| 7680x2160          | 1        | 0.53%   |
| 3840x1200          | 1        | 0.53%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 29       | 15.76%  |
| 24      | 20       | 10.87%  |
| 23      | 20       | 10.87%  |
| 21      | 19       | 10.33%  |
| 27      | 18       | 9.78%   |
| 22      | 13       | 7.07%   |
| 31      | 9        | 4.89%   |
| 19      | 9        | 4.89%   |
| 18      | 8        | 4.35%   |
| 17      | 7        | 3.8%    |
| 20      | 6        | 3.26%   |
| 34      | 4        | 2.17%   |
| 32      | 4        | 2.17%   |
| 72      | 2        | 1.09%   |
| 48      | 2        | 1.09%   |
| 15      | 2        | 1.09%   |
| 84      | 1        | 0.54%   |
| 65      | 1        | 0.54%   |
| 60      | 1        | 0.54%   |
| 55      | 1        | 0.54%   |
| 49      | 1        | 0.54%   |
| 43      | 1        | 0.54%   |
| 38      | 1        | 0.54%   |
| 37      | 1        | 0.54%   |
| 36      | 1        | 0.54%   |
| 28      | 1        | 0.54%   |
| 26      | 1        | 0.54%   |
| 16      | 1        | 0.54%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 53       | 29.61%  |
| 401-500     | 49       | 27.37%  |
| Unknown     | 29       | 16.2%   |
| 601-700     | 13       | 7.26%   |
| 701-800     | 9        | 5.03%   |
| 301-350     | 8        | 4.47%   |
| 351-400     | 6        | 3.35%   |
| 1001-1500   | 6        | 3.35%   |
| 1501-2000   | 3        | 1.68%   |
| 801-900     | 2        | 1.12%   |
| 901-1000    | 1        | 0.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 101      | 59.06%  |
| 16/10   | 27       | 15.79%  |
| Unknown | 25       | 14.62%  |
| 5/4     | 9        | 5.26%   |
| 21/9    | 5        | 2.92%   |
| 32/9    | 2        | 1.17%   |
| 6/5     | 1        | 0.58%   |
| 3/2     | 1        | 0.58%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 54       | 30.17%  |
| Unknown        | 29       | 16.2%   |
| 151-200        | 21       | 11.73%  |
| 301-350        | 18       | 10.06%  |
| 351-500        | 17       | 9.5%    |
| 141-150        | 12       | 6.7%    |
| 251-300        | 11       | 6.15%   |
| More than 1000 | 7        | 3.91%   |
| 501-1000       | 6        | 3.35%   |
| 131-140        | 1        | 0.56%   |
| 111-120        | 1        | 0.56%   |
| 101-110        | 1        | 0.56%   |
| 91-100         | 1        | 0.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 98       | 55.37%  |
| 101-120 | 31       | 17.51%  |
| Unknown | 29       | 16.38%  |
| 1-50    | 10       | 5.65%   |
| 121-160 | 8        | 4.52%   |
| 161-240 | 1        | 0.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 136      | 80.95%  |
| 2     | 27       | 16.07%  |
| 3     | 4        | 2.38%   |
| 0     | 1        | 0.6%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 100      | 40.65%  |
| Intel                             | 76       | 30.89%  |
| Qualcomm Atheros                  | 10       | 4.07%   |
| Broadcom                          | 9        | 3.66%   |
| Ralink Technology                 | 7        | 2.85%   |
| Nvidia                            | 7        | 2.85%   |
| Samsung Electronics               | 6        | 2.44%   |
| Xiaomi                            | 3        | 1.22%   |
| TP-Link                           | 3        | 1.22%   |
| Ralink                            | 3        | 1.22%   |
| Microsoft                         | 2        | 0.81%   |
| Marvell Technology Group          | 2        | 0.81%   |
| Linksys                           | 2        | 0.81%   |
| Broadcom Limited                  | 2        | 0.81%   |
| ZyXEL Communications              | 1        | 0.41%   |
| vivo                              | 1        | 0.41%   |
| TRENDnet                          | 1        | 0.41%   |
| Sundance Technology Inc / IC Plus | 1        | 0.41%   |
| Qualcomm Atheros Communications   | 1        | 0.41%   |
| Motorola PCS                      | 1        | 0.41%   |
| LG Electronics                    | 1        | 0.41%   |
| Huawei Technologies               | 1        | 0.41%   |
| Exar                              | 1        | 0.41%   |
| D-Link System                     | 1        | 0.41%   |
| AVM                               | 1        | 0.41%   |
| Aquantia                          | 1        | 0.41%   |
| AirTies Wireless Networks         | 1        | 0.41%   |
| AboCom Systems                    | 1        | 0.41%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                 | 74       | 26.62%  |
| Intel Wi-Fi 6 AX200                                                               | 12       | 4.32%   |
| Realtek RTL8125 2.5GbE Controller                                                 | 10       | 3.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                             | 10       | 3.6%    |
| Intel I211 Gigabit Network Connection                                             | 9        | 3.24%   |
| Intel Ethernet Connection (2) I219-V                                              | 8        | 2.88%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                             | 6        | 2.16%   |
| Realtek 802.11ac NIC                                                              | 5        | 1.8%    |
| Ralink MT7601U Wireless Adapter                                                   | 5        | 1.8%    |
| Nvidia MCP61 Ethernet                                                             | 5        | 1.8%    |
| Intel Ethernet Controller I225-V                                                  | 5        | 1.8%    |
| Intel Ethernet Connection (7) I219-V                                              | 4        | 1.44%   |
| Intel 82579V Gigabit Network Connection                                           | 4        | 1.44%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                    | 3        | 1.08%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                       | 3        | 1.08%   |
| Samsung Galaxy series, misc. (tethering mode)                                     | 3        | 1.08%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                | 3        | 1.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                               | 3        | 1.08%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                            | 3        | 1.08%   |
| Intel Ethernet Connection I217-LM                                                 | 3        | 1.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                  | 3        | 1.08%   |
| Intel 82574L Gigabit Network Connection                                           | 3        | 1.08%   |
| Ralink RT5372 Wireless Adapter                                                    | 2        | 0.72%   |
| Intel Ethernet Connection (7) I219-LM                                             | 2        | 0.72%   |
| Intel Ethernet Connection (2) I219-LM                                             | 2        | 0.72%   |
| Intel Ethernet Connection (11) I219-V                                             | 2        | 0.72%   |
| Intel Comet Lake PCH CNVi WiFi                                                    | 2        | 0.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                                   | 2        | 0.72%   |
| Intel 82578DM Gigabit Network Connection                                          | 2        | 0.72%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                | 2        | 0.72%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                | 2        | 0.72%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]                      | 1        | 0.36%   |
| vivo 1806                                                                         | 1        | 0.36%   |
| TRENDnet TEW-648UBM 802.11n 150Mbps Micro Wireless N Adapter [Realtek RTL8188CUS] | 1        | 0.36%   |
| TP-Link Archer T4U ver.3                                                          | 1        | 0.36%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                        | 1        | 0.36%   |
| TP-Link 802.11ac NIC                                                              | 1        | 0.36%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY        | 1        | 0.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                          | 1        | 0.36%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                          | 1        | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 31       | 34.44%  |
| Realtek Semiconductor           | 20       | 22.22%  |
| Broadcom                        | 8        | 8.89%   |
| Ralink Technology               | 7        | 7.78%   |
| TP-Link                         | 3        | 3.33%   |
| Ralink                          | 3        | 3.33%   |
| Qualcomm Atheros                | 3        | 3.33%   |
| Microsoft                       | 2        | 2.22%   |
| Linksys                         | 2        | 2.22%   |
| Broadcom Limited                | 2        | 2.22%   |
| ZyXEL Communications            | 1        | 1.11%   |
| TRENDnet                        | 1        | 1.11%   |
| Qualcomm Atheros Communications | 1        | 1.11%   |
| Marvell Technology Group        | 1        | 1.11%   |
| LG Electronics                  | 1        | 1.11%   |
| D-Link System                   | 1        | 1.11%   |
| AVM                             | 1        | 1.11%   |
| AirTies Wireless Networks       | 1        | 1.11%   |
| AboCom Systems                  | 1        | 1.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                               | 12       | 13.19%  |
| Realtek 802.11ac NIC                                                              | 5        | 5.49%   |
| Ralink MT7601U Wireless Adapter                                                   | 5        | 5.49%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                | 3        | 3.3%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                               | 3        | 3.3%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                            | 3        | 3.3%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                  | 3        | 3.3%    |
| Ralink RT5372 Wireless Adapter                                                    | 2        | 2.2%    |
| Intel Comet Lake PCH CNVi WiFi                                                    | 2        | 2.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                                   | 2        | 2.2%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                | 2        | 2.2%    |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                | 2        | 2.2%    |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]                      | 1        | 1.1%    |
| TRENDnet TEW-648UBM 802.11n 150Mbps Micro Wireless N Adapter [Realtek RTL8188CUS] | 1        | 1.1%    |
| TP-Link Archer T4U ver.3                                                          | 1        | 1.1%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                        | 1        | 1.1%    |
| TP-Link 802.11ac NIC                                                              | 1        | 1.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                          | 1        | 1.1%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                          | 1        | 1.1%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                          | 1        | 1.1%    |
| Realtek RTL8191SEvA Wireless LAN Controller                                       | 1        | 1.1%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                             | 1        | 1.1%    |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                           | 1        | 1.1%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                           | 1        | 1.1%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                        | 1        | 1.1%    |
| Realtek RTL8187 Wireless Adapter                                                  | 1        | 1.1%    |
| Realtek 802.11n WLAN Adapter                                                      | 1        | 1.1%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                         | 1        | 1.1%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                         | 1        | 1.1%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                         | 1        | 1.1%    |
| Qualcomm Atheros AR9271 802.11n                                                   | 1        | 1.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                  | 1        | 1.1%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                    | 1        | 1.1%    |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]               | 1        | 1.1%    |
| Microsoft XBOX ACC                                                                | 1        | 1.1%    |
| Microsoft Xbox 360 Wireless Adapter                                               | 1        | 1.1%    |
| Marvell Group 88w8335 [Libertas] 802.11b/g Wireless                               | 1        | 1.1%    |
| Linksys WUSB6300 V2                                                               | 1        | 1.1%    |
| Linksys AE1000 v1 802.11n [Ralink RT3572]                                         | 1        | 1.1%    |
| LG AN-WF100 802.11abgn Wireless Adapter [Broadcom BCM4323]                        | 1        | 1.1%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 92       | 50%     |
| Intel                             | 61       | 33.15%  |
| Qualcomm Atheros                  | 7        | 3.8%    |
| Nvidia                            | 7        | 3.8%    |
| Samsung Electronics               | 6        | 3.26%   |
| Xiaomi                            | 3        | 1.63%   |
| Broadcom                          | 2        | 1.09%   |
| vivo                              | 1        | 0.54%   |
| Sundance Technology Inc / IC Plus | 1        | 0.54%   |
| Motorola PCS                      | 1        | 0.54%   |
| Marvell Technology Group          | 1        | 0.54%   |
| Huawei Technologies               | 1        | 0.54%   |
| Aquantia                          | 1        | 0.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 74       | 39.78%  |
| Realtek RTL8125 2.5GbE Controller                                          | 10       | 5.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 10       | 5.38%   |
| Intel I211 Gigabit Network Connection                                      | 9        | 4.84%   |
| Intel Ethernet Connection (2) I219-V                                       | 8        | 4.3%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 6        | 3.23%   |
| Nvidia MCP61 Ethernet                                                      | 5        | 2.69%   |
| Intel Ethernet Controller I225-V                                           | 5        | 2.69%   |
| Intel Ethernet Connection (7) I219-V                                       | 4        | 2.15%   |
| Intel 82579V Gigabit Network Connection                                    | 4        | 2.15%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 3        | 1.61%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 3        | 1.61%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 3        | 1.61%   |
| Intel Ethernet Connection I217-LM                                          | 3        | 1.61%   |
| Intel 82574L Gigabit Network Connection                                    | 3        | 1.61%   |
| Intel Ethernet Connection (7) I219-LM                                      | 2        | 1.08%   |
| Intel Ethernet Connection (2) I219-LM                                      | 2        | 1.08%   |
| Intel Ethernet Connection (11) I219-V                                      | 2        | 1.08%   |
| Intel 82578DM Gigabit Network Connection                                   | 2        | 1.08%   |
| vivo 1806                                                                  | 1        | 0.54%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.54%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 1        | 0.54%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 1        | 0.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 1        | 0.54%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 1        | 0.54%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 1        | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 1        | 0.54%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 1        | 0.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 1        | 0.54%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                              | 1        | 0.54%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 1        | 0.54%   |
| Nvidia MCP77 Ethernet                                                      | 1        | 0.54%   |
| Nvidia MCP55 Ethernet                                                      | 1        | 0.54%   |
| Motorola PCS moto g(9) play                                                | 1        | 0.54%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                    | 1        | 0.54%   |
| Intel I210 Gigabit Network Connection                                      | 1        | 0.54%   |
| Intel Ethernet Connection I217-V                                           | 1        | 0.54%   |
| Intel Ethernet Connection (2) I218-V                                       | 1        | 0.54%   |
| Intel Ethernet Connection (12) I219-V                                      | 1        | 0.54%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 1        | 0.54%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 165      | 66.27%  |
| WiFi     | 83       | 33.33%  |
| Modem    | 1        | 0.4%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 122      | 76.73%  |
| WiFi     | 37       | 23.27%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 105      | 63.25%  |
| 2     | 51       | 30.72%  |
| 3     | 9        | 5.42%   |
| 0     | 1        | 0.6%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 121      | 72.46%  |
| Yes  | 46       | 27.54%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 30       | 44.78%  |
| Cambridge Silicon Radio | 16       | 23.88%  |
| Realtek Semiconductor   | 6        | 8.96%   |
| Broadcom                | 5        | 7.46%   |
| Apple                   | 4        | 5.97%   |
| ASUSTek Computer        | 2        | 2.99%   |
| Ralink                  | 1        | 1.49%   |
| Qcom                    | 1        | 1.49%   |
| IMC Networks            | 1        | 1.49%   |
| Edimax Technology       | 1        | 1.49%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 16       | 23.88%  |
| Intel AX200 Bluetooth                               | 11       | 16.42%  |
| Realtek Bluetooth Radio                             | 5        | 7.46%   |
| Intel Bluetooth wireless interface                  | 4        | 5.97%   |
| Intel AX210 Bluetooth                               | 4        | 5.97%   |
| Intel AX201 Bluetooth                               | 4        | 5.97%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3        | 4.48%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 2.99%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2        | 2.99%   |
| Apple Bluetooth USB Host Controller                 | 2        | 2.99%   |
| Realtek Bluetooth 5.1 Radio                         | 1        | 1.49%   |
| Ralink RT3290 Bluetooth                             | 1        | 1.49%   |
| Qcom Bluetooth USB                                  | 1        | 1.49%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 1.49%   |
| Intel Bluetooth Device                              | 1        | 1.49%   |
| IMC Networks BCM20702A0                             | 1        | 1.49%   |
| Edimax Bluetooth Adapter                            | 1        | 1.49%   |
| Broadcom HP Portable Bumble Bee                     | 1        | 1.49%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter    | 1        | 1.49%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1        | 1.49%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 1.49%   |
| ASUS BCM20702A0                                     | 1        | 1.49%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1        | 1.49%   |
| Apple Bluetooth HCI                                 | 1        | 1.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 106      | 37.19%  |
| AMD                       | 74       | 25.96%  |
| Nvidia                    | 60       | 21.05%  |
| C-Media Electronics       | 13       | 4.56%   |
| Creative Labs             | 8        | 2.81%   |
| Logitech                  | 4        | 1.4%    |
| Focusrite-Novation        | 2        | 0.7%    |
| Corsair                   | 2        | 0.7%    |
| ASUSTek Computer          | 2        | 0.7%    |
| Texas Instruments         | 1        | 0.35%   |
| Tenx Technology           | 1        | 0.35%   |
| Sony                      | 1        | 0.35%   |
| Razer USA                 | 1        | 0.35%   |
| Philips Speech Processing | 1        | 0.35%   |
| Native Instruments        | 1        | 0.35%   |
| Microsoft                 | 1        | 0.35%   |
| Micro Star International  | 1        | 0.35%   |
| iCreate Technologies      | 1        | 0.35%   |
| GN Netcom                 | 1        | 0.35%   |
| Generalplus Technology    | 1        | 0.35%   |
| Edifier Technology        | 1        | 0.35%   |
| Creative Technology       | 1        | 0.35%   |
| BR25                      | 1        | 0.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                           | Desktops | Percent |
|-------------------------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                      | 24       | 7.36%   |
| AMD Starship/Matisse HD Audio Controller                                                        | 15       | 4.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                             | 11       | 3.37%   |
| Intel Cannon Lake PCH cAVS                                                                      | 10       | 3.07%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                      | 10       | 3.07%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                         | 8        | 2.45%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                             | 8        | 2.45%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                    | 8        | 2.45%   |
| Nvidia GF108 High Definition Audio Controller                                                   | 7        | 2.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                | 7        | 2.15%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                             | 7        | 2.15%   |
| Intel 200 Series PCH HD Audio                                                                   | 7        | 2.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                 | 7        | 2.15%   |
| AMD Family 17h/19h HD Audio Controller                                                          | 7        | 2.15%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                        | 6        | 1.84%   |
| Nvidia TU104 HD Audio Controller                                                                | 5        | 1.53%   |
| Nvidia MCP61 High Definition Audio                                                              | 5        | 1.53%   |
| Nvidia GP106 High Definition Audio Controller                                                   | 5        | 1.53%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                         | 5        | 1.53%   |
| AMD FCH Azalia Controller                                                                       | 5        | 1.53%   |
| Nvidia TU116 High Definition Audio Controller                                                   | 4        | 1.23%   |
| Nvidia GP107GL High Definition Audio Controller                                                 | 4        | 1.23%   |
| Nvidia GA102 High Definition Audio Controller                                                   | 4        | 1.23%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                  | 4        | 1.23%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                               | 4        | 1.23%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                       | 4        | 1.23%   |
| AMD SBx00 Azalia (Intel HDA)                                                                    | 4        | 1.23%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                             | 4        | 1.23%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]               | 4        | 1.23%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                  | 3        | 0.92%   |
| Nvidia TU106 High Definition Audio Controller                                                   | 3        | 0.92%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                           | 3        | 0.92%   |
| Intel Tiger Lake-H HD Audio Controller                                                          | 3        | 0.92%   |
| Intel Comet Lake PCH cAVS                                                                       | 3        | 0.92%   |
| Intel 9 Series Chipset Family HD Audio Controller                                               | 3        | 0.92%   |
| Creative Labs EMU20k2 [Sound Blaster X-Fi Titanium Series]                                      | 3        | 0.92%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus] | 3        | 0.92%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                | 3        | 0.92%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                  | 3        | 0.92%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                         | 3        | 0.92%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 6        | 20%     |
| Samsung Electronics | 5        | 16.67%  |
| Unknown             | 4        | 13.33%  |
| SK hynix            | 3        | 10%     |
| Corsair             | 2        | 6.67%   |
| A-DATA Technology   | 2        | 6.67%   |
| Unknown (0x038A)    | 1        | 3.33%   |
| Ramaxel Technology  | 1        | 3.33%   |
| PNY                 | 1        | 3.33%   |
| Patriot             | 1        | 3.33%   |
| Micron Technology   | 1        | 3.33%   |
| G.Skill             | 1        | 3.33%   |
| Crucial             | 1        | 3.33%   |
| Unknown             | 1        | 3.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM DDR3 1066MT/s                | 1        | 3.23%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                     | 1        | 3.23%   |
| Unknown RAM Module 8192MB DIMM DDR3 1066MT/s             | 1        | 3.23%   |
| Unknown RAM Module 8192MB DIMM 1066MT/s                  | 1        | 3.23%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                | 1        | 3.23%   |
| Unknown (0x038A) RAM Module 4GB DIMM DDR3 1066MT/s       | 1        | 3.23%   |
| SK hynix RAM HMT42GR7BMR4C 16384MB DIMM DDR3 1066MT/s    | 1        | 3.23%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s  | 1        | 3.23%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s   | 1        | 3.23%   |
| Samsung RAM Module 8192MB DIMM DDR4 2666MT/s             | 1        | 3.23%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s    | 1        | 3.23%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s    | 1        | 3.23%   |
| Samsung RAM M393B2K70DM0 16384MB DIMM DDR3 1066MT/s      | 1        | 3.23%   |
| Samsung RAM M378B5273DH0-CK0 4096MB DIMM DDR3 2200MT/s   | 1        | 3.23%   |
| Ramaxel RAM RMUA5090KB78HAF2133 8GB DIMM DDR4 2133MT/s   | 1        | 3.23%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8GB DIMM DDR4 3200MT/s      | 1        | 3.23%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3200MT/s      | 1        | 3.23%   |
| Micron RAM Module 16384MB DIMM DDR3 1600MT/s             | 1        | 3.23%   |
| Kingston RAM KHX2400C15/8G 8192MB DIMM DDR4 3400MT/s     | 1        | 3.23%   |
| Kingston RAM KF3600C18D4/32GX 32GB DIMM DDR4 3600MT/s    | 1        | 3.23%   |
| Kingston RAM KF3600C18D4/16GX 16384MB DIMM DDR4 3600MT/s | 1        | 3.23%   |
| Kingston RAM 9905783-049.A01G 16384MB DIMM 4800MT/s      | 1        | 3.23%   |
| Kingston RAM 9905625-030.A00G 8GB DIMM DDR4 2133MT/s     | 1        | 3.23%   |
| Kingston RAM 9905471-015.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 3.23%   |
| G.Skill RAM F3-14900CL9-2GBXM 2048MB DIMM DDR3 1600MT/s  | 1        | 3.23%   |
| Crucial RAM CT25664BA1339.C8FE 2048MB DIMM DDR3 1333MT/s | 1        | 3.23%   |
| Corsair RAM CMX8GX3M1A1600C11 8GB DIMM DDR3 1600MT/s     | 1        | 3.23%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s     | 1        | 3.23%   |
| A-DATA RAM Module 4096MB DIMM DDR4 2400MT/s              | 1        | 3.23%   |
| A-DATA RAM Module 16384MB DIMM DDR4 2667MT/s             | 1        | 3.23%   |
| Unknown                                                  | 1        | 3.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 10       | 43.48%  |
| DDR4    | 9        | 39.13%  |
| Unknown | 3        | 13.04%  |
| SDRAM   | 1        | 4.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 21       | 91.3%   |
| SODIMM | 2        | 8.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 10       | 40%     |
| 4096  | 7        | 28%     |
| 16384 | 5        | 20%     |
| 32768 | 2        | 8%      |
| 2048  | 1        | 4%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 6        | 23.08%  |
| 1066  | 4        | 15.38%  |
| 3600  | 2        | 7.69%   |
| 3200  | 2        | 7.69%   |
| 1333  | 2        | 7.69%   |
| 4800  | 1        | 3.85%   |
| 3400  | 1        | 3.85%   |
| 2800  | 1        | 3.85%   |
| 2667  | 1        | 3.85%   |
| 2666  | 1        | 3.85%   |
| 2400  | 1        | 3.85%   |
| 2200  | 1        | 3.85%   |
| 2133  | 1        | 3.85%   |
| 1800  | 1        | 3.85%   |
| 800   | 1        | 3.85%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 2        | 33.33%  |
| Canon              | 2        | 33.33%  |
| Dymo-CoStar        | 1        | 16.67%  |
| Brother Industries | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| HP OfficeJet 5200 series    | 1        | 16.67%  |
| HP Ink Tank 110 series      | 1        | 16.67%  |
| Dymo-CoStar LabelWriter 450 | 1        | 16.67%  |
| Canon PIXMA MX390 Series    | 1        | 16.67%  |
| Canon PIXMA MG3600 Series   | 1        | 16.67%  |
| Brother MFC-J5335DW         | 1        | 16.67%  |

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
| Logitech                      | 9        | 32.14%  |
| Microdia                      | 4        | 14.29%  |
| Microsoft                     | 3        | 10.71%  |
| Chicony Electronics           | 2        | 7.14%   |
| Apple                         | 2        | 7.14%   |
| Z-Star Microelectronics       | 1        | 3.57%   |
| SunplusIT                     | 1        | 3.57%   |
| Sunplus Innovation Technology | 1        | 3.57%   |
| Silicon Motion                | 1        | 3.57%   |
| Razer USA                     | 1        | 3.57%   |
| OmniVision Technologies       | 1        | 3.57%   |
| ANYKA                         | 1        | 3.57%   |
| Alcor Micro                   | 1        | 3.57%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Microsoft LifeCam HD-3000             | 2        | 7.14%   |
| Microdia USB 2.0 Camera               | 2        | 7.14%   |
| Logitech HD Webcam C615               | 2        | 7.14%   |
| Chicony HP High Definition 1MP Webcam | 2        | 7.14%   |
| Apple iPhone5/5C/5S/6                 | 2        | 7.14%   |
| Z-Star Vega USB 2.0 Camera            | 1        | 3.57%   |
| SunplusIT MTD camera                  | 1        | 3.57%   |
| Sunplus SPCA2650 AV Camera            | 1        | 3.57%   |
| Silicon Motion Silicon Motion Camera  | 1        | 3.57%   |
| Razer USA Razer Kiyo Pro              | 1        | 3.57%   |
| OmniVision Monitor Webcam             | 1        | 3.57%   |
| Microsoft LifeCam VX-800              | 1        | 3.57%   |
| Microdia Integrated Camera            | 1        | 3.57%   |
| Microdia Camera                       | 1        | 3.57%   |
| Logitech Webcam C925e                 | 1        | 3.57%   |
| Logitech Webcam C270                  | 1        | 3.57%   |
| Logitech QuickCam Communicate Deluxe  | 1        | 3.57%   |
| Logitech Logi 4K Stream Edition       | 1        | 3.57%   |
| Logitech HD Webcam C910               | 1        | 3.57%   |
| Logitech C922 Pro Stream Webcam       | 1        | 3.57%   |
| Logitech B525 HD Webcam               | 1        | 3.57%   |
| ANYKA V380 FHD Camera                 | 1        | 3.57%   |
| Alcor Micro USB 2.0 PC Camera         | 1        | 3.57%   |

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
| 0     | 145      | 86.31%  |
| 1     | 18       | 10.71%  |
| 2     | 4        | 2.38%   |
| 4     | 1        | 0.6%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 13       | 48.15%  |
| Sound                    | 3        | 11.11%  |
| Bluetooth                | 3        | 11.11%  |
| Unassigned class         | 2        | 7.41%   |
| Graphics card            | 2        | 7.41%   |
| Storage/ide              | 1        | 3.7%    |
| Multimedia controller    | 1        | 3.7%    |
| Fingerprint reader       | 1        | 3.7%    |
| Communication controller | 1        | 3.7%    |

