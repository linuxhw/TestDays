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

Total: 267

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | SHARKBAY NOK                | [f37b129292](https://linux-hardware.org/?probe=f37b129292) | Nov 05, 2024 |
| HP            | 0B54h D                     | [3e361ce6dd](https://linux-hardware.org/?probe=3e361ce6dd) | Aug 27, 2024 |
| HP            | 0B54h D                     | [a1df6af082](https://linux-hardware.org/?probe=a1df6af082) | Jun 27, 2024 |
| MSI           | A68HM-E33 V2                | [22b44252e3](https://linux-hardware.org/?probe=22b44252e3) | Mar 28, 2024 |
| HP            | 0B54h D                     | [7b38927e17](https://linux-hardware.org/?probe=7b38927e17) | Mar 23, 2024 |
| HP            | 0B54h D                     | [0af537dbcd](https://linux-hardware.org/?probe=0af537dbcd) | Mar 22, 2024 |
| MSI           | A68HM-E33 V2                | [52b29bf885](https://linux-hardware.org/?probe=52b29bf885) | Mar 12, 2024 |
| Gigabyte      | H110N-CF                    | [c6a69fce12](https://linux-hardware.org/?probe=c6a69fce12) | Feb 10, 2024 |
| HP            | 0B54h D                     | [4ec7776a76](https://linux-hardware.org/?probe=4ec7776a76) | Nov 02, 2023 |
| HP            | 339A                        | [a9eaaaeeb0](https://linux-hardware.org/?probe=a9eaaaeeb0) | Sep 12, 2023 |
| HP            | 339A                        | [18bb44efa6](https://linux-hardware.org/?probe=18bb44efa6) | Sep 10, 2023 |
| Unknown       | IPMSB-H61                   | [c104b6462e](https://linux-hardware.org/?probe=c104b6462e) | Aug 26, 2023 |
| Dell          | 0KP561                      | [2b6a6b6139](https://linux-hardware.org/?probe=2b6a6b6139) | Aug 17, 2023 |
| HP            | 0B54h D                     | [c13f21ea22](https://linux-hardware.org/?probe=c13f21ea22) | Jun 29, 2023 |
| Acer          | Veriton X2631G V:1.0        | [99f3070065](https://linux-hardware.org/?probe=99f3070065) | Jun 11, 2023 |
| Gigabyte      | B450M GAMING                | [8ab2ec8df4](https://linux-hardware.org/?probe=8ab2ec8df4) | Jun 09, 2023 |
| HP            | 225E                        | [06c72d2ecd](https://linux-hardware.org/?probe=06c72d2ecd) | May 10, 2023 |
| HP            | 0B54h D                     | [59e9cd0741](https://linux-hardware.org/?probe=59e9cd0741) | Apr 06, 2023 |
| Dell          | 0T7D40 A01                  | [c2174a1837](https://linux-hardware.org/?probe=c2174a1837) | Mar 12, 2023 |
| Acer          | Aspire TC-380               | [563bd52487](https://linux-hardware.org/?probe=563bd52487) | Mar 10, 2023 |
| Dell          | 0J584C                      | [5f16a97f99](https://linux-hardware.org/?probe=5f16a97f99) | Feb 27, 2023 |
| Gigabyte      | Z77MX-D3H                   | [bfd1042a82](https://linux-hardware.org/?probe=bfd1042a82) | Feb 25, 2023 |
| Dell          | 0J584C                      | [f0c7703e3c](https://linux-hardware.org/?probe=f0c7703e3c) | Feb 23, 2023 |
| Dell          | 0J584C                      | [003da08b72](https://linux-hardware.org/?probe=003da08b72) | Feb 22, 2023 |
| ASUSTek       | M4A785TD-V EVO              | [aaa509fed7](https://linux-hardware.org/?probe=aaa509fed7) | Feb 09, 2023 |
| Unknown       | IPMSB-H61                   | [7e13c996bd](https://linux-hardware.org/?probe=7e13c996bd) | Feb 02, 2023 |
| BESSTAR Te... | UM350                       | [ee1ba0e588](https://linux-hardware.org/?probe=ee1ba0e588) | Jan 30, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [e5f6f546d4](https://linux-hardware.org/?probe=e5f6f546d4) | Jan 29, 2023 |
| EVGA          | E689 $                      | [9d4b1aeaa9](https://linux-hardware.org/?probe=9d4b1aeaa9) | Jan 29, 2023 |
| EVGA          | E689 $                      | [be99ae882b](https://linux-hardware.org/?probe=be99ae882b) | Jan 28, 2023 |
| Gigabyte      | GA-990FXA-UD3               | [6e5884ec0c](https://linux-hardware.org/?probe=6e5884ec0c) | Jan 26, 2023 |
| Dell          | 0G261D A00                  | [ac4e94394e](https://linux-hardware.org/?probe=ac4e94394e) | Jan 24, 2023 |
| Unknown       | G41T-M7                     | [026810c423](https://linux-hardware.org/?probe=026810c423) | Jan 22, 2023 |
| Gigabyte      | Z77MX-D3H                   | [2142d5e771](https://linux-hardware.org/?probe=2142d5e771) | Jan 22, 2023 |
| Gigabyte      | Z77MX-D3H                   | [80d8c352b9](https://linux-hardware.org/?probe=80d8c352b9) | Jan 22, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [b8df2d6479](https://linux-hardware.org/?probe=b8df2d6479) | Jan 11, 2023 |
| Intel         | JSL MRD                     | [d1b9dbaae0](https://linux-hardware.org/?probe=d1b9dbaae0) | Jan 11, 2023 |
| HP            | 8643 SMVB                   | [5187413460](https://linux-hardware.org/?probe=5187413460) | Jan 07, 2023 |
| Acer          | Veriton M2631G V:1.0        | [ebbcc0dda8](https://linux-hardware.org/?probe=ebbcc0dda8) | Jan 07, 2023 |
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


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.11.0-43-generic      | 36       | 16.9%   |
| 5.13.0-39-generic      | 16       | 7.51%   |
| 5.13.0-28-generic      | 16       | 7.51%   |
| 5.15.0-46-generic      | 13       | 6.1%    |
| 5.13.0-27-generic      | 10       | 4.69%   |
| 5.13.0-40-generic      | 9        | 4.23%   |
| 5.13.0-30-generic      | 9        | 4.23%   |
| 5.15.0-56-generic      | 8        | 3.76%   |
| 5.13.0-35-generic      | 7        | 3.29%   |
| 5.13.0-37-generic      | 6        | 2.82%   |
| 5.15.0-58-generic      | 5        | 2.35%   |
| 5.13.0-52-generic      | 5        | 2.35%   |
| 5.13.0-51-generic      | 5        | 2.35%   |
| 5.11.0-41-generic      | 5        | 2.35%   |
| 5.15.0-53-generic      | 4        | 1.88%   |
| 5.15.0-52-generic      | 4        | 1.88%   |
| 5.15.0-41-generic      | 4        | 1.88%   |
| 5.13.0-44-generic      | 4        | 1.88%   |
| 5.11.0-44-generic      | 4        | 1.88%   |
| 5.15.0-57-generic      | 3        | 1.41%   |
| 5.15.0-50-generic      | 3        | 1.41%   |
| 5.15.0-48-generic      | 3        | 1.41%   |
| 5.13.0-48-generic      | 3        | 1.41%   |
| 5.15.0-76-generic      | 2        | 0.94%   |
| 5.15.0-73-generic      | 2        | 0.94%   |
| 5.15.0-69-generic      | 2        | 0.94%   |
| 5.13.0-41-generic      | 2        | 0.94%   |
| 5.13.0-25-generic      | 2        | 0.94%   |
| 5.11.0-46-generic      | 2        | 0.94%   |
| 5.11.0-40-generic      | 2        | 0.94%   |
| 6.1.8-x64v2-xanmod1    | 1        | 0.47%   |
| 5.17.3-xanmod1         | 1        | 0.47%   |
| 5.16.15-051615-generic | 1        | 0.47%   |
| 5.15.36-xanmod1        | 1        | 0.47%   |
| 5.15.0-91-generic      | 1        | 0.47%   |
| 5.15.0-84-generic      | 1        | 0.47%   |
| 5.15.0-79-generic      | 1        | 0.47%   |
| 5.15.0-71-generic      | 1        | 0.47%   |
| 5.15.0-60-generic      | 1        | 0.47%   |
| 5.15.0-124-generic     | 1        | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13.0  | 86       | 43.88%  |
| 5.15.0  | 56       | 28.57%  |
| 5.11.0  | 49       | 25%     |
| 6.1.8   | 1        | 0.51%   |
| 5.17.3  | 1        | 0.51%   |
| 5.16.15 | 1        | 0.51%   |
| 5.15.36 | 1        | 0.51%   |
| 5.14.0  | 1        | 0.51%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13    | 86       | 43.88%  |
| 5.15    | 57       | 29.08%  |
| 5.11    | 49       | 25%     |
| 6.1     | 1        | 0.51%   |
| 5.17    | 1        | 0.51%   |
| 5.16    | 1        | 0.51%   |
| 5.14    | 1        | 0.51%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 187      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Pantheon | 187      | 99.47%  |
| GNOME    | 1        | 0.53%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 187      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 158      | 83.16%  |
| LightDM | 32       | 16.84%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 78       | 41.27%  |
| de_DE | 22       | 11.64%  |
| es_ES | 15       | 7.94%   |
| fr_FR | 14       | 7.41%   |
| ru_RU | 12       | 6.35%   |
| pt_BR | 8        | 4.23%   |
| it_IT | 8        | 4.23%   |
| en_GB | 7        | 3.7%    |
| pt_PT | 4        | 2.12%   |
| pl_PL | 3        | 1.59%   |
| en_CA | 3        | 1.59%   |
| tr_TR | 2        | 1.06%   |
| ja_JP | 2        | 1.06%   |
| en_AU | 2        | 1.06%   |
| zh_CN | 1        | 0.53%   |
| uk_UA | 1        | 0.53%   |
| sr_RS | 1        | 0.53%   |
| nl_NL | 1        | 0.53%   |
| nb_NO | 1        | 0.53%   |
| id_ID | 1        | 0.53%   |
| fr_CA | 1        | 0.53%   |
| de_CH | 1        | 0.53%   |
| C     | 1        | 0.53%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 99       | 52.11%  |
| BIOS | 91       | 47.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 178      | 94.68%  |
| Btrfs    | 5        | 2.66%   |
| Xfs      | 2        | 1.06%   |
| Tmpfs    | 1        | 0.53%   |
| Reiserfs | 1        | 0.53%   |
| Overlay  | 1        | 0.53%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 162      | 85.71%  |
| GPT     | 20       | 10.58%  |
| MBR     | 7        | 3.7%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 181      | 95.77%  |
| Yes       | 8        | 4.23%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 175      | 93.09%  |
| Yes       | 13       | 6.91%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 45       | 24.06%  |
| Gigabyte Technology | 30       | 16.04%  |
| MSI                 | 20       | 10.7%   |
| Hewlett-Packard     | 17       | 9.09%   |
| Dell                | 14       | 7.49%   |
| ASRock              | 12       | 6.42%   |
| Lenovo              | 6        | 3.21%   |
| Acer                | 5        | 2.67%   |
| Intel               | 4        | 2.14%   |
| Foxconn             | 4        | 2.14%   |
| Biostar             | 4        | 2.14%   |
| Unknown             | 4        | 2.14%   |
| Fujitsu             | 3        | 1.6%    |
| Apple               | 3        | 1.6%    |
| Pegatron            | 2        | 1.07%   |
| ECS                 | 2        | 1.07%   |
| T-bao               | 1        | 0.53%   |
| Packard Bell        | 1        | 0.53%   |
| LORD ELECTRONICS    | 1        | 0.53%   |
| LattePanda          | 1        | 0.53%   |
| Kraftway            | 1        | 0.53%   |
| IceWhale Technology | 1        | 0.53%   |
| FIRICH              | 1        | 0.53%   |
| EVGA                | 1        | 0.53%   |
| BESSTAR Tech        | 1        | 0.53%   |
| AZW                 | 1        | 0.53%   |
| AOpen               | 1        | 0.53%   |
| AMI                 | 1        | 0.53%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| ASUS All Series                                   | 4        | 2.14%   |
| Unknown                                           | 4        | 2.14%   |
| MSI MS-7C35                                       | 2        | 1.07%   |
| HP Compaq Pro 6300 MT                             | 2        | 1.07%   |
| Gigabyte Z390 UD                                  | 2        | 1.07%   |
| Dell OptiPlex 790                                 | 2        | 1.07%   |
| ASUS TUF Gaming B550M-PLUS                        | 2        | 1.07%   |
| T-bao MINI PC                                     | 1        | 0.53%   |
| Pegatron p7-1174                                  | 1        | 0.53%   |
| Pegatron IPMH61P1                                 | 1        | 0.53%   |
| Packard Bell IMEDIA S1300                         | 1        | 0.53%   |
| MSI PPPPP-CCC#MMMMMMMM                            | 1        | 0.53%   |
| MSI MS-7D52                                       | 1        | 0.53%   |
| MSI MS-7C91                                       | 1        | 0.53%   |
| MSI MS-7C77                                       | 1        | 0.53%   |
| MSI MS-7C52                                       | 1        | 0.53%   |
| MSI MS-7C02                                       | 1        | 0.53%   |
| MSI MS-7B86                                       | 1        | 0.53%   |
| MSI MS-7B84                                       | 1        | 0.53%   |
| MSI MS-7B79                                       | 1        | 0.53%   |
| MSI MS-7B61                                       | 1        | 0.53%   |
| MSI MS-7A59                                       | 1        | 0.53%   |
| MSI MS-7A40                                       | 1        | 0.53%   |
| MSI MS-7A38                                       | 1        | 0.53%   |
| MSI MS-7918                                       | 1        | 0.53%   |
| MSI MS-7885                                       | 1        | 0.53%   |
| MSI MS-7851                                       | 1        | 0.53%   |
| MSI MS-7817                                       | 1        | 0.53%   |
| MSI MS-7721                                       | 1        | 0.53%   |
| LORD ELECTRONICS LORD G4x 775 ICH7 8712 As Design | 1        | 0.53%   |
| Lenovo ThinkCentre M73z 10BBS00200                | 1        | 0.53%   |
| Lenovo ThinkCentre M73 10B6001SUS                 | 1        | 0.53%   |
| Lenovo ThinkCentre M72e 3664AD7                   | 1        | 0.53%   |
| Lenovo ThinkCentre M70e 0809D1Y                   | 1        | 0.53%   |
| Lenovo ThinkCentre M58 6258D3G                    | 1        | 0.53%   |
| Lenovo IdeaCentre 510S-07ICK 90LX006TGE           | 1        | 0.53%   |
| LattePanda Alpha                                  | 1        | 0.53%   |
| Kraftway Credo KCxx                               | 1        | 0.53%   |
| Intel X79                                         | 1        | 0.53%   |
| Intel Jasper Lake Client Platform                 | 1        | 0.53%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 10       | 5.35%   |
| ASUS PRIME             | 8        | 4.28%   |
| ASUS TUF               | 7        | 3.74%   |
| ASUS ROG               | 6        | 3.21%   |
| Lenovo ThinkCentre     | 5        | 2.67%   |
| HP Compaq              | 5        | 2.67%   |
| ASUS All               | 4        | 2.14%   |
| Unknown                | 4        | 2.14%   |
| Fujitsu ESPRIMO        | 3        | 1.6%    |
| ASUS P8H61-M           | 3        | 1.6%    |
| MSI MS-7C35            | 2        | 1.07%   |
| HP ProDesk             | 2        | 1.07%   |
| Gigabyte Z390          | 2        | 1.07%   |
| Gigabyte H310M         | 2        | 1.07%   |
| Gigabyte A320M-S2H     | 2        | 1.07%   |
| Dell Precision         | 2        | 1.07%   |
| Acer Veriton           | 2        | 1.07%   |
| Acer Aspire            | 2        | 1.07%   |
| T-bao MINI             | 1        | 0.53%   |
| Pegatron p7-1174       | 1        | 0.53%   |
| Pegatron IPMH61P1      | 1        | 0.53%   |
| Packard Bell IMEDIA    | 1        | 0.53%   |
| MSI PPPPP-CCC#MMMMMMMM | 1        | 0.53%   |
| MSI MS-7D52            | 1        | 0.53%   |
| MSI MS-7C91            | 1        | 0.53%   |
| MSI MS-7C77            | 1        | 0.53%   |
| MSI MS-7C52            | 1        | 0.53%   |
| MSI MS-7C02            | 1        | 0.53%   |
| MSI MS-7B86            | 1        | 0.53%   |
| MSI MS-7B84            | 1        | 0.53%   |
| MSI MS-7B79            | 1        | 0.53%   |
| MSI MS-7B61            | 1        | 0.53%   |
| MSI MS-7A59            | 1        | 0.53%   |
| MSI MS-7A40            | 1        | 0.53%   |
| MSI MS-7A38            | 1        | 0.53%   |
| MSI MS-7918            | 1        | 0.53%   |
| MSI MS-7885            | 1        | 0.53%   |
| MSI MS-7851            | 1        | 0.53%   |
| MSI MS-7817            | 1        | 0.53%   |
| MSI MS-7721            | 1        | 0.53%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 25       | 13.37%  |
| 2018 | 23       | 12.3%   |
| 2010 | 17       | 9.09%   |
| 2020 | 15       | 8.02%   |
| 2011 | 15       | 8.02%   |
| 2014 | 14       | 7.49%   |
| 2019 | 13       | 6.95%   |
| 2013 | 12       | 6.42%   |
| 2015 | 11       | 5.88%   |
| 2021 | 9        | 4.81%   |
| 2017 | 9        | 4.81%   |
| 2016 | 6        | 3.21%   |
| 2022 | 5        | 2.67%   |
| 2009 | 5        | 2.67%   |
| 2008 | 4        | 2.14%   |
| 2007 | 3        | 1.6%    |
| 2006 | 1        | 0.53%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 187      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 178      | 95.19%  |
| Enabled  | 9        | 4.81%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 187      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 39       | 20.63%  |
| 8.01-16.0   | 39       | 20.63%  |
| 32.01-64.0  | 33       | 17.46%  |
| 4.01-8.0    | 31       | 16.4%   |
| 3.01-4.0    | 29       | 15.34%  |
| 64.01-256.0 | 6        | 3.17%   |
| 24.01-32.0  | 5        | 2.65%   |
| 1.01-2.0    | 5        | 2.65%   |
| 2.01-3.0    | 2        | 1.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 77       | 36.67%  |
| 2.01-3.0  | 60       | 28.57%  |
| 4.01-8.0  | 33       | 15.71%  |
| 3.01-4.0  | 27       | 12.86%  |
| 8.01-16.0 | 7        | 3.33%   |
| 0.51-1.0  | 6        | 2.86%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 68       | 35.42%  |
| 2      | 64       | 33.33%  |
| 3      | 31       | 16.15%  |
| 4      | 17       | 8.85%   |
| 5      | 5        | 2.6%    |
| 6      | 4        | 2.08%   |
| 7      | 2        | 1.04%   |
| 0      | 1        | 0.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 102      | 53.13%  |
| Yes       | 90       | 46.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 186      | 99.47%  |
| No        | 1        | 0.53%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 96       | 50.26%  |
| No        | 95       | 49.74%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 119      | 62.63%  |
| Yes       | 71       | 37.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 29       | 15.51%  |
| Germany      | 20       | 10.7%   |
| Russia       | 13       | 6.95%   |
| France       | 11       | 5.88%   |
| Brazil       | 11       | 5.88%   |
| UK           | 10       | 5.35%   |
| Spain        | 8        | 4.28%   |
| Italy        | 8        | 4.28%   |
| Canada       | 7        | 3.74%   |
| Indonesia    | 6        | 3.21%   |
| Switzerland  | 5        | 2.67%   |
| Poland       | 4        | 2.14%   |
| Australia    | 4        | 2.14%   |
| Argentina    | 4        | 2.14%   |
| Turkey       | 3        | 1.6%    |
| Portugal     | 3        | 1.6%    |
| Japan        | 3        | 1.6%    |
| India        | 3        | 1.6%    |
| Colombia     | 3        | 1.6%    |
| Austria      | 3        | 1.6%    |
| Norway       | 2        | 1.07%   |
| Netherlands  | 2        | 1.07%   |
| Iran         | 2        | 1.07%   |
| Thailand     | 1        | 0.53%   |
| Sweden       | 1        | 0.53%   |
| Sri Lanka    | 1        | 0.53%   |
| South Africa | 1        | 0.53%   |
| Slovenia     | 1        | 0.53%   |
| Serbia       | 1        | 0.53%   |
| Romania      | 1        | 0.53%   |
| Pakistan     | 1        | 0.53%   |
| New Zealand  | 1        | 0.53%   |
| Mexico       | 1        | 0.53%   |
| Malaysia     | 1        | 0.53%   |
| Lithuania    | 1        | 0.53%   |
| Libya        | 1        | 0.53%   |
| Kenya        | 1        | 0.53%   |
| Israel       | 1        | 0.53%   |
| Ireland      | 1        | 0.53%   |
| Hong Kong    | 1        | 0.53%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Desktops | Percent |
|---------------|----------|---------|
| Moscow        | 4        | 1.98%   |
| Warsaw        | 3        | 1.49%   |
| Hamburg       | 3        | 1.49%   |
| Caslano       | 3        | 1.49%   |
| Vienna        | 2        | 0.99%   |
| Tangerang     | 2        | 0.99%   |
| Sao Vicente   | 2        | 0.99%   |
| Sao Paulo     | 2        | 0.99%   |
| Paris         | 2        | 0.99%   |
| Istanbul      | 2        | 0.99%   |
| Denver        | 2        | 0.99%   |
| Brisbane      | 2        | 0.99%   |
| Bandung       | 2        | 0.99%   |
| Yucca Valley  | 1        | 0.5%    |
| Yokohama      | 1        | 0.5%    |
| Yarang        | 1        | 0.5%    |
| Wroclaw       | 1        | 0.5%    |
| Woolloongabba | 1        | 0.5%    |
| Woodbridge    | 1        | 0.5%    |
| Wolgast       | 1        | 0.5%    |
| Windsor       | 1        | 0.5%    |
| Werneck       | 1        | 0.5%    |
| Walnut Creek  | 1        | 0.5%    |
| Vanse         | 1        | 0.5%    |
| Trondheim     | 1        | 0.5%    |
| Troisdorf     | 1        | 0.5%    |
| Tripoli       | 1        | 0.5%    |
| Tournus       | 1        | 0.5%    |
| Toronto       | 1        | 0.5%    |
| Thrissur      | 1        | 0.5%    |
| Teresina      | 1        | 0.5%    |
| Tel Aviv      | 1        | 0.5%    |
| Tehran        | 1        | 0.5%    |
| Tampere       | 1        | 0.5%    |
| Tacoma        | 1        | 0.5%    |
| Sydney        | 1        | 0.5%    |
| Suresnes      | 1        | 0.5%    |
| Surabaya      | 1        | 0.5%    |
| Stuttgart     | 1        | 0.5%    |
| St Petersburg | 1        | 0.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 62       | 93     | 18.13%  |
| Seagate                   | 57       | 84     | 16.67%  |
| Samsung Electronics       | 46       | 73     | 13.45%  |
| Kingston                  | 26       | 34     | 7.6%    |
| Toshiba                   | 19       | 27     | 5.56%   |
| SanDisk                   | 12       | 15     | 3.51%   |
| Crucial                   | 12       | 15     | 3.51%   |
| Hitachi                   | 9        | 11     | 2.63%   |
| Unknown                   | 7        | 19     | 2.05%   |
| PNY                       | 7        | 11     | 2.05%   |
| Micron/Crucial Technology | 6        | 10     | 1.75%   |
| Phison                    | 5        | 5      | 1.46%   |
| Intel                     | 5        | 5      | 1.46%   |
| A-DATA Technology         | 5        | 5      | 1.46%   |
| Micron Technology         | 4        | 5      | 1.17%   |
| China                     | 4        | 6      | 1.17%   |
| Team                      | 3        | 5      | 0.88%   |
| SPCC                      | 3        | 3      | 0.88%   |
| Maxtor                    | 3        | 3      | 0.88%   |
| JMicron Technology        | 3        | 3      | 0.88%   |
| HUSKY                     | 3        | 8      | 0.88%   |
| HGST                      | 3        | 3      | 0.88%   |
| ASMT                      | 3        | 3      | 0.88%   |
| Transcend                 | 2        | 2      | 0.58%   |
| Silicon Motion            | 2        | 2      | 0.58%   |
| Realtek Semiconductor     | 2        | 2      | 0.58%   |
| Plextor                   | 2        | 3      | 0.58%   |
| OCZ                       | 2        | 5      | 0.58%   |
| LITEON                    | 2        | 2      | 0.58%   |
| Corsair                   | 2        | 2      | 0.58%   |
| XPG                       | 1        | 1      | 0.29%   |
| tigo                      | 1        | 1      | 0.29%   |
| SK hynix                  | 1        | 1      | 0.29%   |
| Phison Electronics        | 1        | 1      | 0.29%   |
| Patriot                   | 1        | 1      | 0.29%   |
| OCZ-VERTEX2               | 1        | 1      | 0.29%   |
| Netac                     | 1        | 1      | 0.29%   |
| MidasForce                | 1        | 1      | 0.29%   |
| Lexar                     | 1        | 1      | 0.29%   |
| Leven                     | 1        | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Drive 500GB                        | 7        | 1.79%   |
| Seagate ST500DM002-1BD142 500GB                     | 5        | 1.28%   |
| Seagate ST1000DM003-1ER162 1TB                      | 5        | 1.28%   |
| WDC WD5000AAKX-00ERMA0 500GB                        | 4        | 1.03%   |
| Toshiba DT01ACA050 500GB                            | 4        | 1.03%   |
| Samsung SSD 860 EVO 250GB                           | 4        | 1.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 4        | 1.03%   |
| Micron/Crucial NVMe SSD Drive 1TB                   | 4        | 1.03%   |
| Kingston SA400S37240G 240GB SSD                     | 4        | 1.03%   |
| Kingston SA400S37120G 120GB SSD                     | 4        | 1.03%   |
| Crucial CT240BX500SSD1 240GB                        | 4        | 1.03%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 3        | 0.77%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 3        | 0.77%   |
| Unknown SD/MMC 1073GB                               | 3        | 0.77%   |
| Unknown M.S./M.S.Pro/HG 16GB                        | 3        | 0.77%   |
| Unknown Compact Flash 977MB                         | 3        | 0.77%   |
| Toshiba DT01ACA100 1TB                              | 3        | 0.77%   |
| Seagate ST3500418AS 500GB                           | 3        | 0.77%   |
| Seagate ST1000DM010-2EP102 1TB                      | 3        | 0.77%   |
| Samsung SSD 860 EVO 1TB                             | 3        | 0.77%   |
| Samsung SSD 850 EVO 250GB                           | 3        | 0.77%   |
| Phison NVMe SSD Drive 1TB                           | 3        | 0.77%   |
| Kingston SV300S37A120G 120GB SSD                    | 3        | 0.77%   |
| Kingston NVMe SSD Drive 1TB                         | 3        | 0.77%   |
| HUSKY SSD 128GB                                     | 3        | 0.77%   |
| WDC WD5000AAKX-60U6AA0 500GB                        | 2        | 0.51%   |
| WDC WD5000AAKX-001CA0 500GB                         | 2        | 0.51%   |
| WDC WD5000AAKS-00UU3A0 500GB                        | 2        | 0.51%   |
| WDC WD40EFRX-68N32N0 4TB                            | 2        | 0.51%   |
| WDC WD10EADS-00L5B1 1TB                             | 2        | 0.51%   |
| Unknown MMC Card  32GB                              | 2        | 0.51%   |
| Toshiba HDWD110 1TB                                 | 2        | 0.51%   |
| Seagate ST3500630AS 500GB                           | 2        | 0.51%   |
| Seagate ST3500413AS 500GB                           | 2        | 0.51%   |
| Seagate ST3160815AS 160GB                           | 2        | 0.51%   |
| Seagate ST31000528AS 1TB                            | 2        | 0.51%   |
| Seagate ST2000DX002-2DV164 2TB                      | 2        | 0.51%   |
| Seagate ST2000DM001-9YN164 2TB                      | 2        | 0.51%   |
| Seagate ST1000DM003-1CH162 1TB                      | 2        | 0.51%   |
| SanDisk SDSSDHP256G 256GB                           | 2        | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 54       | 75     | 34.62%  |
| Seagate             | 54       | 80     | 34.62%  |
| Toshiba             | 18       | 26     | 11.54%  |
| Samsung Electronics | 10       | 12     | 6.41%   |
| Hitachi             | 9        | 11     | 5.77%   |
| HGST                | 3        | 3      | 1.92%   |
| Maxtor              | 2        | 2      | 1.28%   |
| ASMT                | 2        | 2      | 1.28%   |
| Unknown             | 1        | 1      | 0.64%   |
| JMicron Technology  | 1        | 1      | 0.64%   |
| Hewlett-Packard     | 1        | 1      | 0.64%   |
| Fujitsu             | 1        | 1      | 0.64%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 24       | 38     | 19.2%   |
| Kingston            | 20       | 24     | 16%     |
| Crucial             | 11       | 13     | 8.8%    |
| SanDisk             | 10       | 12     | 8%      |
| WDC                 | 7        | 12     | 5.6%    |
| PNY                 | 7        | 11     | 5.6%    |
| China               | 4        | 6      | 3.2%    |
| A-DATA Technology   | 4        | 4      | 3.2%    |
| Team                | 3        | 5      | 2.4%    |
| SPCC                | 3        | 3      | 2.4%    |
| Intel               | 3        | 3      | 2.4%    |
| HUSKY               | 3        | 8      | 2.4%    |
| Transcend           | 2        | 2      | 1.6%    |
| Plextor             | 2        | 3      | 1.6%    |
| OCZ                 | 2        | 5      | 1.6%    |
| Micron Technology   | 2        | 2      | 1.6%    |
| LITEON              | 2        | 2      | 1.6%    |
| Corsair             | 2        | 2      | 1.6%    |
| Toshiba             | 1        | 1      | 0.8%    |
| tigo                | 1        | 1      | 0.8%    |
| Seagate             | 1        | 2      | 0.8%    |
| Patriot             | 1        | 1      | 0.8%    |
| OCZ-VERTEX2         | 1        | 1      | 0.8%    |
| MidasForce          | 1        | 1      | 0.8%    |
| Maxtor              | 1        | 1      | 0.8%    |
| Lexar               | 1        | 1      | 0.8%    |
| Leven               | 1        | 1      | 0.8%    |
| Intenso             | 1        | 1      | 0.8%    |
| GOODRAM             | 1        | 1      | 0.8%    |
| Gigabyte Technology | 1        | 1      | 0.8%    |
| ASMT                | 1        | 1      | 0.8%    |
| Unknown             | 1        | 1      | 0.8%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 126      | 215    | 42.28%  |
| SSD     | 109      | 170    | 36.58%  |
| NVMe    | 49       | 72     | 16.44%  |
| Unknown | 11       | 26     | 3.69%   |
| MMC     | 3        | 3      | 1.01%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 171      | 382    | 71.85%  |
| NVMe | 49       | 72     | 20.59%  |
| SAS  | 15       | 29     | 6.3%    |
| MMC  | 3        | 3      | 1.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 132      | 233    | 58.15%  |
| 0.51-1.0   | 55       | 97     | 24.23%  |
| 1.01-2.0   | 19       | 23     | 8.37%   |
| 2.01-3.0   | 9        | 17     | 3.96%   |
| 3.01-4.0   | 7        | 8      | 3.08%   |
| 4.01-10.0  | 5        | 7      | 2.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 67       | 34.18%  |
| 251-500        | 43       | 21.94%  |
| 501-1000       | 37       | 18.88%  |
| 1001-2000      | 19       | 9.69%   |
| 51-100         | 11       | 5.61%   |
| More than 3000 | 10       | 5.1%    |
| 21-50          | 5        | 2.55%   |
| 2001-3000      | 4        | 2.04%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 77       | 36.84%  |
| 21-50          | 37       | 17.7%   |
| 101-250        | 30       | 14.35%  |
| 51-100         | 25       | 11.96%  |
| 251-500        | 17       | 8.13%   |
| 501-1000       | 11       | 5.26%   |
| 1001-2000      | 7        | 3.35%   |
| More than 3000 | 3        | 1.44%   |
| 2001-3000      | 2        | 0.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                        | Desktops | Drives | Percent |
|------------------------------|----------|--------|---------|
| WDC WD5000AAKS-00UU3A0 500GB | 1        | 1      | 25%     |
| Seagate ST3500312CS 500GB    | 1        | 1      | 25%     |
| SanDisk SSD PLUS 240GB       | 1        | 1      | 25%     |
| OCZ VECTOR150 240GB SSD      | 1        | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 1        | 1      | 25%     |
| Seagate | 1        | 1      | 25%     |
| SanDisk | 1        | 1      | 25%     |
| OCZ     | 1        | 1      | 25%     |

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
| SSD  | 2        | 2      | 50%     |
| HDD  | 2        | 2      | 50%     |

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
| Detected | 169      | 436    | 87.56%  |
| Works    | 20       | 46     | 10.36%  |
| Malfunc  | 4        | 4      | 2.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 126      | 49.22%  |
| AMD                         | 50       | 19.53%  |
| Samsung Electronics         | 20       | 7.81%   |
| Nvidia                      | 8        | 3.13%   |
| Micron/Crucial Technology   | 7        | 2.73%   |
| Kingston Technology Company | 7        | 2.73%   |
| Phison Electronics          | 6        | 2.34%   |
| SanDisk                     | 5        | 1.95%   |
| Marvell Technology Group    | 5        | 1.95%   |
| ASMedia Technology          | 5        | 1.95%   |
| JMicron Technology          | 4        | 1.56%   |
| Realtek Semiconductor       | 3        | 1.17%   |
| Silicon Motion              | 2        | 0.78%   |
| Seagate Technology          | 2        | 0.78%   |
| Micron Technology           | 2        | 0.78%   |
| LSI Logic / Symbios Logic   | 2        | 0.78%   |
| SK hynix                    | 1        | 0.39%   |
| ADATA Technology            | 1        | 0.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 31       | 9.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 16       | 5.03%   |
| AMD 400 Series Chipset SATA Controller                                                  | 16       | 5.03%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 13       | 4.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 11       | 3.46%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 10       | 3.14%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 10       | 3.14%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 10       | 3.14%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9        | 2.83%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 9        | 2.83%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 8        | 2.52%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 6        | 1.89%   |
| Intel SATA Controller [RAID mode]                                                       | 6        | 1.89%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 1.89%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 5        | 1.57%   |
| Nvidia MCP61 SATA Controller                                                            | 5        | 1.57%   |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                              | 5        | 1.57%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 5        | 1.57%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 1.57%   |
| AMD 500 Series Chipset SATA Controller                                                  | 5        | 1.57%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 1.26%   |
| Phison E12 NVMe Controller                                                              | 3        | 0.94%   |
| Nvidia MCP61 IDE                                                                        | 3        | 0.94%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 0.94%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 0.94%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 0.94%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 0.94%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 0.63%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 2        | 0.63%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                                       | 2        | 0.63%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 0.63%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 2        | 0.63%   |
| Micron 2200S NVMe SSD [Cassandra]                                                       | 2        | 0.63%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2        | 0.63%   |
| JMicron JMB368 IDE controller                                                           | 2        | 0.63%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 0.63%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2        | 0.63%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 0.63%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 0.63%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 145      | 56.64%  |
| NVMe | 49       | 19.14%  |
| IDE  | 49       | 19.14%  |
| RAID | 11       | 4.3%    |
| SAS  | 1        | 0.39%   |
| SCSI | 1        | 0.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 130      | 69.52%  |
| AMD    | 57       | 30.48%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Intel Core i5-2400 CPU @ 3.10GHz              | 5        | 2.67%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 5        | 2.67%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 4        | 2.14%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 4        | 2.14%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 4        | 2.14%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 4        | 2.14%   |
| Intel Core i7-9700 CPU @ 3.00GHz              | 3        | 1.6%    |
| Intel Core i7-3770 CPU @ 3.40GHz              | 3        | 1.6%    |
| Intel Core i5-7400 CPU @ 3.00GHz              | 3        | 1.6%    |
| Intel Core i5-3470 CPU @ 3.20GHz              | 3        | 1.6%    |
| Intel 11th Gen Core i7-11700K @ 3.60GHz       | 3        | 1.6%    |
| AMD Ryzen 9 5900X 12-Core Processor           | 3        | 1.6%    |
| AMD Ryzen 5 3600 6-Core Processor             | 3        | 1.6%    |
| Intel Core i9-9900K CPU @ 3.60GHz             | 2        | 1.07%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 2        | 1.07%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 2        | 1.07%   |
| Intel Core i7-10700K CPU @ 3.80GHz            | 2        | 1.07%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 2        | 1.07%   |
| Intel Core i3-8100 CPU @ 3.60GHz              | 2        | 1.07%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 2        | 1.07%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 2        | 1.07%   |
| Intel Core i3 CPU 530 @ 2.93GHz               | 2        | 1.07%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz         | 2        | 1.07%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 2        | 1.07%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz          | 2        | 1.07%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 2        | 1.07%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 2        | 1.07%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 2        | 1.07%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 2        | 1.07%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 2        | 1.07%   |
| AMD A8-7600 Radeon R7, 10 Compute Cores 4C+6G | 2        | 1.07%   |
| Intel Xeon CPU X5680 @ 3.33GHz                | 1        | 0.53%   |
| Intel Xeon CPU E5620 @ 2.40GHz                | 1        | 0.53%   |
| Intel Xeon CPU E5462 @ 2.80GHz                | 1        | 0.53%   |
| Intel Xeon CPU E5410 @ 2.33GHz                | 1        | 0.53%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz            | 1        | 0.53%   |
| Intel Xeon CPU E5-2665 0 @ 2.40GHz            | 1        | 0.53%   |
| Intel Xeon CPU E5-1660 0 @ 3.30GHz            | 1        | 0.53%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz           | 1        | 0.53%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz           | 1        | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 32       | 17.11%  |
| Intel Core i7           | 28       | 14.97%  |
| Intel Core i3           | 19       | 10.16%  |
| AMD Ryzen 5             | 18       | 9.63%   |
| Intel Xeon              | 14       | 7.49%   |
| AMD Ryzen 7             | 10       | 5.35%   |
| Intel Celeron           | 7        | 3.74%   |
| AMD Ryzen 9             | 6        | 3.21%   |
| Other                   | 5        | 2.67%   |
| Intel Pentium           | 5        | 2.67%   |
| Intel Core 2 Quad       | 5        | 2.67%   |
| Intel Pentium Dual-Core | 4        | 2.14%   |
| AMD FX                  | 4        | 2.14%   |
| AMD Athlon II X2        | 4        | 2.14%   |
| AMD A8                  | 4        | 2.14%   |
| Intel Core 2 Duo        | 3        | 1.6%    |
| Intel Atom              | 3        | 1.6%    |
| AMD Phenom II X4        | 3        | 1.6%    |
| Intel Core i9           | 2        | 1.07%   |
| AMD Athlon              | 2        | 1.07%   |
| AMD A10                 | 2        | 1.07%   |
| Intel Pentium Gold      | 1        | 0.53%   |
| Intel Pentium Dual      | 1        | 0.53%   |
| Intel Core m3           | 1        | 0.53%   |
| AMD Ryzen 3             | 1        | 0.53%   |
| AMD Phenom II X6        | 1        | 0.53%   |
| AMD Athlon X4           | 1        | 0.53%   |
| AMD Athlon II X4        | 1        | 0.53%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 81       | 42.86%  |
| 2      | 48       | 25.4%   |
| 6      | 25       | 13.23%  |
| 8      | 24       | 12.7%   |
| 12     | 6        | 3.17%   |
| 16     | 2        | 1.06%   |
| 1      | 2        | 1.06%   |
| 3      | 1        | 0.53%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 184      | 98.4%   |
| 2      | 3        | 1.6%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 109      | 57.67%  |
| 1      | 80       | 42.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 187      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x206a7    | 22       | 11.52%  |
| 0x306c3    | 18       | 9.42%   |
| 0x306a9    | 12       | 6.28%   |
| Unknown    | 12       | 6.28%   |
| 0x08701021 | 9        | 4.71%   |
| 0x1067a    | 7        | 3.66%   |
| 0x906ea    | 6        | 3.14%   |
| 0x506e3    | 6        | 3.14%   |
| 0x08108109 | 6        | 3.14%   |
| 0x906ed    | 5        | 2.62%   |
| 0x906e9    | 5        | 2.62%   |
| 0x0800820d | 5        | 2.62%   |
| 0x906eb    | 4        | 2.09%   |
| 0x6fb      | 4        | 2.09%   |
| 0x0a201016 | 4        | 2.09%   |
| 0x06003106 | 4        | 2.09%   |
| 0xa0671    | 3        | 1.57%   |
| 0x206d7    | 3        | 1.57%   |
| 0x06000852 | 3        | 1.57%   |
| 0x010000c8 | 3        | 1.57%   |
| 0xa0655    | 2        | 1.05%   |
| 0xa0653    | 2        | 1.05%   |
| 0x406c4    | 2        | 1.05%   |
| 0x306e4    | 2        | 1.05%   |
| 0x206c2    | 2        | 1.05%   |
| 0x20655    | 2        | 1.05%   |
| 0x20652    | 2        | 1.05%   |
| 0x106e5    | 2        | 1.05%   |
| 0x10676    | 2        | 1.05%   |
| 0x0a50000c | 2        | 1.05%   |
| 0x08701013 | 2        | 1.05%   |
| 0x08001138 | 2        | 1.05%   |
| 0x010000c7 | 2        | 1.05%   |
| 0x906ec    | 1        | 0.52%   |
| 0x906c0    | 1        | 0.52%   |
| 0x90672    | 1        | 0.52%   |
| 0x806e9    | 1        | 0.52%   |
| 0x806c1    | 1        | 0.52%   |
| 0x706a8    | 1        | 0.52%   |
| 0x6fd      | 1        | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| SandyBridge      | 26       | 13.9%   |
| KabyLake         | 23       | 12.3%   |
| Haswell          | 20       | 10.7%   |
| IvyBridge        | 14       | 7.49%   |
| Zen+             | 12       | 6.42%   |
| Zen 2            | 11       | 5.88%   |
| Zen 3            | 9        | 4.81%   |
| Penryn           | 9        | 4.81%   |
| K10              | 9        | 4.81%   |
| Westmere         | 6        | 3.21%   |
| Skylake          | 6        | 3.21%   |
| Core             | 6        | 3.21%   |
| Zen              | 5        | 2.67%   |
| Steamroller      | 5        | 2.67%   |
| Piledriver       | 4        | 2.14%   |
| CometLake        | 4        | 2.14%   |
| Silvermont       | 3        | 1.6%    |
| Nehalem          | 3        | 1.6%    |
| Icelake          | 3        | 1.6%    |
| Tremont          | 1        | 0.53%   |
| TigerLake        | 1        | 0.53%   |
| K10 Llano        | 1        | 0.53%   |
| Goldmont plus    | 1        | 0.53%   |
| Goldmont         | 1        | 0.53%   |
| Bulldozer        | 1        | 0.53%   |
| Broadwell        | 1        | 0.53%   |
| Bonnell          | 1        | 0.53%   |
| Alderlake Hybrid | 1        | 0.53%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 72       | 36.36%  |
| Intel  | 65       | 32.83%  |
| Nvidia | 61       | 30.81%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17       | 8.25%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 10       | 4.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9        | 4.37%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 7        | 3.4%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6        | 2.91%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5        | 2.43%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 5        | 2.43%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 4        | 1.94%   |
| Intel HD Graphics 530                                                                    | 4        | 1.94%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 4        | 1.94%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 3        | 1.46%   |
| Nvidia TU106 [GeForce GTX 1650]                                                          | 3        | 1.46%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 3        | 1.46%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3        | 1.46%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                                           | 3        | 1.46%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 3        | 1.46%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 2        | 0.97%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2        | 0.97%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 2        | 0.97%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2        | 0.97%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 2        | 0.97%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 2        | 0.97%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 2        | 0.97%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2        | 0.97%   |
| Intel HD Graphics 630                                                                    | 2        | 0.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 0.97%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2        | 0.97%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 0.97%   |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                                        | 2        | 0.97%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 2        | 0.97%   |
| AMD RS880 [Radeon HD 4200]                                                               | 2        | 0.97%   |
| AMD Park [Mobility Radeon HD 5430]                                                       | 2        | 0.97%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                               | 2        | 0.97%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 2        | 0.97%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2        | 0.97%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                                         | 2        | 0.97%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2        | 0.97%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2        | 0.97%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 2        | 0.97%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1        | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 64       | 33.51%  |
| 1 x Intel      | 58       | 30.37%  |
| 1 x Nvidia     | 56       | 29.32%  |
| 2 x AMD        | 4        | 2.09%   |
| 2 x Nvidia     | 3        | 1.57%   |
| Intel + Nvidia | 2        | 1.05%   |
| Intel + AMD    | 2        | 1.05%   |
| AMD + Nvidia   | 2        | 1.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 153      | 80.95%  |
| Proprietary | 34       | 17.99%  |
| Unknown     | 2        | 1.06%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 65       | 33.68%  |
| 1.01-2.0   | 29       | 15.03%  |
| 0.51-1.0   | 27       | 13.99%  |
| 3.01-4.0   | 24       | 12.44%  |
| 7.01-8.0   | 15       | 7.77%   |
| 0.01-0.5   | 11       | 5.7%    |
| 5.01-6.0   | 10       | 5.18%   |
| 8.01-16.0  | 7        | 3.63%   |
| 2.01-3.0   | 5        | 2.59%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 37       | 18.32%  |
| Goldstar             | 21       | 10.4%   |
| Dell                 | 21       | 10.4%   |
| Hewlett-Packard      | 19       | 9.41%   |
| Acer                 | 17       | 8.42%   |
| AOC                  | 12       | 5.94%   |
| Philips              | 11       | 5.45%   |
| Lenovo               | 7        | 3.47%   |
| BenQ                 | 7        | 3.47%   |
| Ancor Communications | 6        | 2.97%   |
| LG Electronics       | 4        | 1.98%   |
| Vizio                | 3        | 1.49%   |
| Unknown              | 3        | 1.49%   |
| AUS                  | 3        | 1.49%   |
| Sony                 | 2        | 0.99%   |
| Sharp                | 2        | 0.99%   |
| NEC Computers        | 2        | 0.99%   |
| Iiyama               | 2        | 0.99%   |
| HPN                  | 2        | 0.99%   |
| Fujitsu Siemens      | 2        | 0.99%   |
| ___                  | 1        | 0.5%    |
| ViewSonic            | 1        | 0.5%    |
| Vestel               | 1        | 0.5%    |
| SPC                  | 1        | 0.5%    |
| Onkyo                | 1        | 0.5%    |
| MSI                  | 1        | 0.5%    |
| Mi                   | 1        | 0.5%    |
| LLP                  | 1        | 0.5%    |
| IOD                  | 1        | 0.5%    |
| Hitachi              | 1        | 0.5%    |
| HannStar             | 1        | 0.5%    |
| Element              | 1        | 0.5%    |
| Eizo                 | 1        | 0.5%    |
| CHR                  | 1        | 0.5%    |
| CHI                  | 1        | 0.5%    |
| CHD                  | 1        | 0.5%    |
| BOE                  | 1        | 0.5%    |
| Apple                | 1        | 0.5%    |
| Unknown              | 1        | 0.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 4        | 1.86%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                       | 2        | 0.93%   |
| Goldstar L1753T GSM4434 1280x1024 338x270mm 17.0-inch                 | 2        | 0.93%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2        | 0.93%   |
| Goldstar 22EN33 GSM597C 1920x1080 480x270mm 21.7-inch                 | 2        | 0.93%   |
| Dell 1704FPV DEL3016 1280x1024 338x270mm 17.0-inch                    | 2        | 0.93%   |
| BenQ EL2870U BNQ7949 3840x2160 621x341mm 27.9-inch                    | 2        | 0.93%   |
| AOC Q27G2WG4 AOC2702 2560x1440 597x336mm 27.0-inch                    | 2        | 0.93%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 2        | 0.93%   |
| ___ LCD TV ___9000 1360x768                                           | 1        | 0.47%   |
| Vizio VXW20LHDTV10A VIZ0035 1366x768 440x250mm 19.9-inch              | 1        | 0.47%   |
| Vizio E320i-A0 VIZ1002 1366x768 698x392mm 31.5-inch                   | 1        | 0.47%   |
| Vizio D32x-D1 VIZ1005 1920x1080 698x392mm 31.5-inch                   | 1        | 0.47%   |
| ViewSonic LCD Monitor VX2260WM 3840x1080                              | 1        | 0.47%   |
| ViewSonic LCD Monitor VX2260WM                                        | 1        | 0.47%   |
| Vestel LCD Monitor 49FHD_LCD_TV 1920x1080                             | 1        | 0.47%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                    | 1        | 0.47%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 1        | 0.47%   |
| Unknown LCD Monitor Bit 3 LE2262 1680x1050                            | 1        | 0.47%   |
| SPC SPC1900 SPC1900 1440x900 410x230mm 18.5-inch                      | 1        | 0.47%   |
| Sony TV SNYD703 1360x768                                              | 1        | 0.47%   |
| Sony TV  *00 SNY8004 3840x2160 1220x680mm 55.0-inch                   | 1        | 0.47%   |
| Sharp HDMI SHP108E 1360x768 820x460mm 37.0-inch                       | 1        | 0.47%   |
| Sharp HDMI SHP1048 1920x1080 820x460mm 37.0-inch                      | 1        | 0.47%   |
| Samsung Electronics T24D391 SAM0B72 1920x1080 521x293mm 23.5-inch     | 1        | 0.47%   |
| Samsung Electronics T22C310 SAM0AE9 1920x1080 477x268mm 21.5-inch     | 1        | 0.47%   |
| Samsung Electronics SyncMaster SAM0580 1280x1024 376x301mm 19.0-inch  | 1        | 0.47%   |
| Samsung Electronics SyncMaster SAM0473 2048x1152 510x290mm 23.1-inch  | 1        | 0.47%   |
| Samsung Electronics SyncMaster SAM0471 1360x768 344x194mm 15.5-inch   | 1        | 0.47%   |
| Samsung Electronics SyncMaster SAM0423 1920x1080                      | 1        | 0.47%   |
| Samsung Electronics SyncMaster SAM0421 1920x1200 518x324mm 24.1-inch  | 1        | 0.47%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 474x296mm 22.0-inch  | 1        | 0.47%   |
| Samsung Electronics SyncMaster SAM0380 1680x1050 459x296mm 21.5-inch  | 1        | 0.47%   |
| Samsung Electronics SyncMaster SAM0259 1280x1024 376x301mm 19.0-inch  | 1        | 0.47%   |
| Samsung Electronics SMBX2035 SAM06FD 1600x900 443x249mm 20.0-inch     | 1        | 0.47%   |
| Samsung Electronics SA300/SA350 SAM078C 1600x900 443x249mm 20.0-inch  | 1        | 0.47%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch  | 1        | 0.47%   |
| Samsung Electronics S27R35x SAM1053 1920x1080 598x336mm 27.0-inch     | 1        | 0.47%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch     | 1        | 0.47%   |
| Samsung Electronics S22E450 SAM0C79 1920x1080 477x268mm 21.5-inch     | 1        | 0.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 83       | 40.89%  |
| 1680x1050 (WSXGA+) | 19       | 9.36%   |
| 3840x2160 (4K)     | 18       | 8.87%   |
| 2560x1440 (QHD)    | 14       | 6.9%    |
| 1366x768 (WXGA)    | 13       | 6.4%    |
| 1280x1024 (SXGA)   | 12       | 5.91%   |
| 1600x900 (HD+)     | 8        | 3.94%   |
| 1360x768           | 6        | 2.96%   |
| 3840x1080          | 5        | 2.46%   |
| 1920x1200 (WUXGA)  | 5        | 2.46%   |
| 1440x900 (WXGA+)   | 5        | 2.46%   |
| Unknown            | 5        | 2.46%   |
| 3440x1440          | 3        | 1.48%   |
| 5120x1440          | 2        | 0.99%   |
| 2560x1080          | 2        | 0.99%   |
| 7680x2160          | 1        | 0.49%   |
| 3840x1200          | 1        | 0.49%   |
| 2048x1152          | 1        | 0.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 30       | 15.15%  |
| 24      | 22       | 11.11%  |
| 23      | 22       | 11.11%  |
| 21      | 19       | 9.6%    |
| 27      | 16       | 8.08%   |
| 22      | 15       | 7.58%   |
| 31      | 11       | 5.56%   |
| 18      | 10       | 5.05%   |
| 19      | 8        | 4.04%   |
| 17      | 8        | 4.04%   |
| 20      | 6        | 3.03%   |
| 32      | 5        | 2.53%   |
| 34      | 4        | 2.02%   |
| 36      | 3        | 1.52%   |
| 15      | 3        | 1.52%   |
| 84      | 2        | 1.01%   |
| 72      | 2        | 1.01%   |
| 48      | 2        | 1.01%   |
| 65      | 1        | 0.51%   |
| 60      | 1        | 0.51%   |
| 55      | 1        | 0.51%   |
| 49      | 1        | 0.51%   |
| 43      | 1        | 0.51%   |
| 39      | 1        | 0.51%   |
| 38      | 1        | 0.51%   |
| 37      | 1        | 0.51%   |
| 28      | 1        | 0.51%   |
| 26      | 1        | 0.51%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 59       | 30.41%  |
| 401-500     | 53       | 27.32%  |
| Unknown     | 30       | 15.46%  |
| 601-700     | 12       | 6.19%   |
| 701-800     | 11       | 5.67%   |
| 301-350     | 10       | 5.15%   |
| 1001-1500   | 6        | 3.09%   |
| 351-400     | 5        | 2.58%   |
| 1501-2000   | 4        | 2.06%   |
| 801-900     | 3        | 1.55%   |
| 901-1000    | 1        | 0.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 113      | 60.43%  |
| 16/10   | 29       | 15.51%  |
| Unknown | 26       | 13.9%   |
| 5/4     | 10       | 5.35%   |
| 21/9    | 5        | 2.67%   |
| 32/9    | 2        | 1.07%   |
| 6/5     | 1        | 0.53%   |
| 3/2     | 1        | 0.53%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 60       | 30.77%  |
| Unknown        | 30       | 15.38%  |
| 351-500        | 20       | 10.26%  |
| 151-200        | 20       | 10.26%  |
| 301-350        | 16       | 8.21%   |
| 141-150        | 15       | 7.69%   |
| 251-300        | 13       | 6.67%   |
| 501-1000       | 9        | 4.62%   |
| More than 1000 | 8        | 4.1%    |
| 101-110        | 2        | 1.03%   |
| 131-140        | 1        | 0.51%   |
| 91-100         | 1        | 0.51%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 112      | 57.73%  |
| 101-120 | 32       | 16.49%  |
| Unknown | 30       | 15.46%  |
| 1-50    | 11       | 5.67%   |
| 121-160 | 8        | 4.12%   |
| 161-240 | 1        | 0.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 158      | 82.72%  |
| 2     | 28       | 14.66%  |
| 3     | 3        | 1.57%   |
| 0     | 2        | 1.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 114      | 40.71%  |
| Intel                             | 80       | 28.57%  |
| Qualcomm Atheros                  | 11       | 3.93%   |
| Broadcom                          | 11       | 3.93%   |
| Ralink Technology                 | 9        | 3.21%   |
| Nvidia                            | 7        | 2.5%    |
| TP-Link                           | 6        | 2.14%   |
| Samsung Electronics               | 6        | 2.14%   |
| Ralink                            | 4        | 1.43%   |
| Broadcom Limited                  | 4        | 1.43%   |
| Xiaomi                            | 3        | 1.07%   |
| Marvell Technology Group          | 3        | 1.07%   |
| Qualcomm Atheros Communications   | 2        | 0.71%   |
| Microsoft                         | 2        | 0.71%   |
| Linksys                           | 2        | 0.71%   |
| D-Link System                     | 2        | 0.71%   |
| ZyXEL Communications              | 1        | 0.36%   |
| vivo                              | 1        | 0.36%   |
| TRENDnet                          | 1        | 0.36%   |
| Sundance Technology Inc / IC Plus | 1        | 0.36%   |
| Motorola PCS                      | 1        | 0.36%   |
| LG Electronics                    | 1        | 0.36%   |
| Huawei Technologies               | 1        | 0.36%   |
| Exar                              | 1        | 0.36%   |
| AVM                               | 1        | 0.36%   |
| Aquantia                          | 1        | 0.36%   |
| Allwinner Technology              | 1        | 0.36%   |
| AirTies Wireless Networks         | 1        | 0.36%   |
| Accton Technology                 | 1        | 0.36%   |
| AboCom Systems                    | 1        | 0.36%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 85       | 26.73%  |
| Intel Wi-Fi 6 AX200                                                    | 12       | 3.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 11       | 3.46%   |
| Realtek RTL8125 2.5GbE Controller                                      | 10       | 3.14%   |
| Intel I211 Gigabit Network Connection                                  | 9        | 2.83%   |
| Intel Ethernet Connection (2) I219-V                                   | 8        | 2.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 7        | 2.2%    |
| Realtek 802.11ac NIC                                                   | 6        | 1.89%   |
| Ralink MT7601U Wireless Adapter                                        | 6        | 1.89%   |
| Intel Ethernet Controller I225-V                                       | 6        | 1.89%   |
| Nvidia MCP61 Ethernet                                                  | 5        | 1.57%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 4        | 1.26%   |
| Intel Ethernet Connection (7) I219-V                                   | 4        | 1.26%   |
| Intel 82579V Gigabit Network Connection                                | 4        | 1.26%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3        | 0.94%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 3        | 0.94%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3        | 0.94%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 3        | 0.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 3        | 0.94%   |
| Intel Ethernet Connection I217-LM                                      | 3        | 0.94%   |
| Intel 82574L Gigabit Network Connection                                | 3        | 0.94%   |
| TP-Link 802.11ac WLAN Adapter                                          | 2        | 0.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2        | 0.63%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 2        | 0.63%   |
| Ralink RT5372 Wireless Adapter                                         | 2        | 0.63%   |
| Qualcomm Atheros AR9271 802.11n                                        | 2        | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2        | 0.63%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 2        | 0.63%   |
| Intel Ethernet Connection I217-V                                       | 2        | 0.63%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2        | 0.63%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2        | 0.63%   |
| Intel Ethernet Connection (11) I219-V                                  | 2        | 0.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2        | 0.63%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 2        | 0.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2        | 0.63%   |
| Intel 82578DM Gigabit Network Connection                               | 2        | 0.63%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 2        | 0.63%   |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W]      | 2        | 0.63%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                 | 2        | 0.63%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 2        | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 33       | 30.84%  |
| Realtek Semiconductor           | 25       | 23.36%  |
| Ralink Technology               | 9        | 8.41%   |
| Broadcom                        | 8        | 7.48%   |
| TP-Link                         | 6        | 5.61%   |
| Ralink                          | 4        | 3.74%   |
| Qualcomm Atheros                | 3        | 2.8%    |
| Broadcom Limited                | 3        | 2.8%    |
| Qualcomm Atheros Communications | 2        | 1.87%   |
| Microsoft                       | 2        | 1.87%   |
| Linksys                         | 2        | 1.87%   |
| D-Link System                   | 2        | 1.87%   |
| ZyXEL Communications            | 1        | 0.93%   |
| TRENDnet                        | 1        | 0.93%   |
| Marvell Technology Group        | 1        | 0.93%   |
| LG Electronics                  | 1        | 0.93%   |
| AVM                             | 1        | 0.93%   |
| AirTies Wireless Networks       | 1        | 0.93%   |
| Accton Technology               | 1        | 0.93%   |
| AboCom Systems                  | 1        | 0.93%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                               | 12       | 11.11%  |
| Realtek 802.11ac NIC                                                              | 6        | 5.56%   |
| Ralink MT7601U Wireless Adapter                                                   | 6        | 5.56%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                         | 4        | 3.7%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                                | 3        | 2.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                               | 3        | 2.78%   |
| TP-Link 802.11ac WLAN Adapter                                                     | 2        | 1.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                          | 2        | 1.85%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                           | 2        | 1.85%   |
| Ralink RT5372 Wireless Adapter                                                    | 2        | 1.85%   |
| Qualcomm Atheros AR9271 802.11n                                                   | 2        | 1.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                  | 2        | 1.85%   |
| Intel Comet Lake PCH CNVi WiFi                                                    | 2        | 1.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                                   | 2        | 1.85%   |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W]                 | 2        | 1.85%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                            | 2        | 1.85%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                      | 2        | 1.85%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter                      | 2        | 1.85%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]                      | 1        | 0.93%   |
| TRENDnet TEW-648UBM 802.11n 150Mbps Micro Wireless N Adapter [Realtek RTL8188CUS] | 1        | 0.93%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                       | 1        | 0.93%   |
| TP-Link Archer T4U ver.3                                                          | 1        | 0.93%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                        | 1        | 0.93%   |
| TP-Link 802.11ac NIC                                                              | 1        | 0.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                          | 1        | 0.93%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                          | 1        | 0.93%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                          | 1        | 0.93%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                       | 1        | 0.93%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                             | 1        | 0.93%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                           | 1        | 0.93%   |
| Realtek RTL8188EE Wireless Network Adapter                                        | 1        | 0.93%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                        | 1        | 0.93%   |
| Realtek RTL8187 Wireless Adapter                                                  | 1        | 0.93%   |
| Realtek 802.11n WLAN Adapter                                                      | 1        | 0.93%   |
| Ralink RT2870/RT3070 Wireless Adapter                                             | 1        | 0.93%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                         | 1        | 0.93%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                         | 1        | 0.93%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                         | 1        | 0.93%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                              | 1        | 0.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                  | 1        | 0.93%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 105      | 51.72%  |
| Intel                             | 65       | 32.02%  |
| Qualcomm Atheros                  | 8        | 3.94%   |
| Nvidia                            | 7        | 3.45%   |
| Broadcom                          | 4        | 1.97%   |
| Xiaomi                            | 3        | 1.48%   |
| Samsung Electronics               | 3        | 1.48%   |
| Marvell Technology Group          | 2        | 0.99%   |
| vivo                              | 1        | 0.49%   |
| Sundance Technology Inc / IC Plus | 1        | 0.49%   |
| Motorola PCS                      | 1        | 0.49%   |
| Huawei Technologies               | 1        | 0.49%   |
| Broadcom Limited                  | 1        | 0.49%   |
| Aquantia                          | 1        | 0.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller     | 85       | 41.46%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 11       | 5.37%   |
| Realtek RTL8125 2.5GbE Controller                                          | 10       | 4.88%   |
| Intel I211 Gigabit Network Connection                                      | 9        | 4.39%   |
| Intel Ethernet Connection (2) I219-V                                       | 8        | 3.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 7        | 3.41%   |
| Intel Ethernet Controller I225-V                                           | 6        | 2.93%   |
| Nvidia MCP61 Ethernet                                                      | 5        | 2.44%   |
| Intel Ethernet Connection (7) I219-V                                       | 4        | 1.95%   |
| Intel 82579V Gigabit Network Connection                                    | 4        | 1.95%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 3        | 1.46%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 3        | 1.46%   |
| Intel Ethernet Connection I217-LM                                          | 3        | 1.46%   |
| Intel 82574L Gigabit Network Connection                                    | 3        | 1.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 2        | 0.98%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                    | 2        | 0.98%   |
| Intel Ethernet Connection I217-V                                           | 2        | 0.98%   |
| Intel Ethernet Connection (7) I219-LM                                      | 2        | 0.98%   |
| Intel Ethernet Connection (2) I219-LM                                      | 2        | 0.98%   |
| Intel Ethernet Connection (11) I219-V                                      | 2        | 0.98%   |
| Intel 82578DM Gigabit Network Connection                                   | 2        | 0.98%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 2        | 0.98%   |
| vivo 1820                                                                  | 1        | 0.49%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 1        | 0.49%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 1        | 0.49%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 1        | 0.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 1        | 0.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 1        | 0.49%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 1        | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 1        | 0.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 1        | 0.49%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                              | 1        | 0.49%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 1        | 0.49%   |
| Nvidia MCP77 Ethernet                                                      | 1        | 0.49%   |
| Nvidia MCP55 Ethernet                                                      | 1        | 0.49%   |
| Motorola PCS moto g84 5G                                                   | 1        | 0.49%   |
| Intel I210 Gigabit Network Connection                                      | 1        | 0.49%   |
| Intel Ethernet Connection (2) I218-V                                       | 1        | 0.49%   |
| Intel Ethernet Connection (12) I219-V                                      | 1        | 0.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 186      | 64.58%  |
| WiFi     | 97       | 33.68%  |
| Modem    | 4        | 1.39%   |
| Unknown  | 1        | 0.35%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 134      | 74.03%  |
| WiFi     | 47       | 25.97%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 119      | 62.96%  |
| 2     | 60       | 31.75%  |
| 3     | 9        | 4.76%   |
| 0     | 1        | 0.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 135      | 71.05%  |
| Yes  | 55       | 28.95%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 31       | 42.47%  |
| Cambridge Silicon Radio | 18       | 24.66%  |
| Realtek Semiconductor   | 8        | 10.96%  |
| Broadcom                | 5        | 6.85%   |
| Apple                   | 4        | 5.48%   |
| ASUSTek Computer        | 2        | 2.74%   |
| Ralink                  | 1        | 1.37%   |
| Qcom                    | 1        | 1.37%   |
| IMC Networks            | 1        | 1.37%   |
| Edimax Technology       | 1        | 1.37%   |
| 3Com                    | 1        | 1.37%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 18       | 24.66%  |
| Intel AX200 Bluetooth                               | 11       | 15.07%  |
| Realtek Bluetooth Radio                             | 8        | 10.96%  |
| Intel Bluetooth wireless interface                  | 5        | 6.85%   |
| Intel AX210 Bluetooth                               | 5        | 6.85%   |
| Intel AX201 Bluetooth                               | 4        | 5.48%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2        | 2.74%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 2.74%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2        | 2.74%   |
| Ralink RT3290 Bluetooth                             | 1        | 1.37%   |
| Qcom Bluetooth USB                                  | 1        | 1.37%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 1.37%   |
| Intel AX211 Bluetooth                               | 1        | 1.37%   |
| IMC Networks BCM20702A0                             | 1        | 1.37%   |
| Edimax Bluetooth Adapter                            | 1        | 1.37%   |
| Broadcom HP Portable Bumble Bee                     | 1        | 1.37%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter    | 1        | 1.37%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1        | 1.37%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 1.37%   |
| ASUS BCM20702A0                                     | 1        | 1.37%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1        | 1.37%   |
| Apple Bluetooth USB Host Controller                 | 1        | 1.37%   |
| Apple Bluetooth Host Controller                     | 1        | 1.37%   |
| Apple Bluetooth HCI                                 | 1        | 1.37%   |
| 3Com 3CREB96 Bluetooth Adapter                      | 1        | 1.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 120      | 37.27%  |
| AMD                       | 84       | 26.09%  |
| Nvidia                    | 64       | 19.88%  |
| C-Media Electronics       | 15       | 4.66%   |
| Creative Labs             | 9        | 2.8%    |
| Logitech                  | 4        | 1.24%   |
| JMTek                     | 2        | 0.62%   |
| Jieli Technology          | 2        | 0.62%   |
| Generalplus Technology    | 2        | 0.62%   |
| Focusrite-Novation        | 2        | 0.62%   |
| Corsair                   | 2        | 0.62%   |
| ASUSTek Computer          | 2        | 0.62%   |
| VIA Technologies          | 1        | 0.31%   |
| Texas Instruments         | 1        | 0.31%   |
| Tenx Technology           | 1        | 0.31%   |
| Sony                      | 1        | 0.31%   |
| Realtek Semiconductor     | 1        | 0.31%   |
| Razer USA                 | 1        | 0.31%   |
| Philips Speech Processing | 1        | 0.31%   |
| Native Instruments        | 1        | 0.31%   |
| Microsoft                 | 1        | 0.31%   |
| Micro Star International  | 1        | 0.31%   |
| iCreate Technologies      | 1        | 0.31%   |
| GN Netcom                 | 1        | 0.31%   |
| Edifier Technology        | 1        | 0.31%   |
| Creative Technology       | 1        | 0.31%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 26       | 6.99%   |
| AMD Starship/Matisse HD Audio Controller                                          | 16       | 4.3%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 14       | 3.76%   |
| Intel Cannon Lake PCH cAVS                                                        | 10       | 2.69%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                        | 10       | 2.69%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 10       | 2.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 9        | 2.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 8        | 2.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 8        | 2.15%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 8        | 2.15%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 8        | 2.15%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 8        | 2.15%   |
| Nvidia GF108 High Definition Audio Controller                                     | 7        | 1.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 7        | 1.88%   |
| Intel 200 Series PCH HD Audio                                                     | 7        | 1.88%   |
| AMD FCH Azalia Controller                                                         | 7        | 1.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 6        | 1.61%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 6        | 1.61%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 6        | 1.61%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 6        | 1.61%   |
| Nvidia TU106 High Definition Audio Controller                                     | 5        | 1.34%   |
| Nvidia TU104 HD Audio Controller                                                  | 5        | 1.34%   |
| Nvidia MCP61 High Definition Audio                                                | 5        | 1.34%   |
| Nvidia GP106 High Definition Audio Controller                                     | 5        | 1.34%   |
| AMD Kaveri HDMI/DP Audio Controller                                               | 5        | 1.34%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 5        | 1.34%   |
| Nvidia TU116 High Definition Audio Controller                                     | 4        | 1.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 4        | 1.08%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 4        | 1.08%   |
| Nvidia GA102 High Definition Audio Controller                                     | 4        | 1.08%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 4        | 1.08%   |
| Creative Labs EMU20k2 [Sound Blaster X-Fi Titanium Series]                        | 4        | 1.08%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 4        | 1.08%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 4        | 1.08%   |
| Nvidia GP108 High Definition Audio Controller                                     | 3        | 0.81%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3        | 0.81%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 3        | 0.81%   |
| Nvidia GF119 HDMI Audio Controller                                                | 3        | 0.81%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 3        | 0.81%   |
| Intel Comet Lake PCH cAVS                                                         | 3        | 0.81%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 8        | 22.86%  |
| Samsung Electronics | 6        | 17.14%  |
| Unknown             | 5        | 14.29%  |
| SK hynix            | 3        | 8.57%   |
| Crucial             | 2        | 5.71%   |
| Corsair             | 2        | 5.71%   |
| A-DATA Technology   | 2        | 5.71%   |
| Unknown (0x038A)    | 1        | 2.86%   |
| Ramaxel Technology  | 1        | 2.86%   |
| PNY                 | 1        | 2.86%   |
| Patriot             | 1        | 2.86%   |
| Micron Technology   | 1        | 2.86%   |
| G.Skill             | 1        | 2.86%   |
| Unknown             | 1        | 2.86%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM DDR3 1066MT/s               | 1        | 2.78%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                    | 1        | 2.78%   |
| Unknown RAM Module 8192MB DIMM DDR3 1066MT/s            | 1        | 2.78%   |
| Unknown RAM Module 8192MB DIMM 1066MT/s                 | 1        | 2.78%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s               | 1        | 2.78%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s            | 1        | 2.78%   |
| Unknown (0x038A) RAM Module 4GB DIMM DDR3 1066MT/s      | 1        | 2.78%   |
| SK hynix RAM HMT42GR7BMR4C 16GB DIMM DDR3 1066MT/s      | 1        | 2.78%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s    | 1        | 2.78%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 1        | 2.78%   |
| Samsung RAM Module 8192MB Row Of Chips LPDDR4 3733MT/s  | 1        | 2.78%   |
| Samsung RAM Module 8192MB DIMM DDR4 2666MT/s            | 1        | 2.78%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s   | 1        | 2.78%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 1        | 2.78%   |
| Samsung RAM M393B2K70DM0 16GB DIMM DDR3 1066MT/s        | 1        | 2.78%   |
| Samsung RAM M378B5273DH0-CK0 4096MB DIMM DDR3 2200MT/s  | 1        | 2.78%   |
| Ramaxel RAM RMUA5090KB78HAF2133 8GB DIMM DDR4 2400MT/s  | 1        | 2.78%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8GB DIMM DDR4 3600MT/s     | 1        | 2.78%   |
| Patriot RAM 3200 C16 Series 4GB DIMM DDR4 3600MT/s      | 1        | 2.78%   |
| Micron RAM Module 16384MB DIMM DDR3 1600MT/s            | 1        | 2.78%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s       | 1        | 2.78%   |
| Kingston RAM KHX1600C9D3/8G 8GB DIMM DDR3 1600MT/s      | 1        | 2.78%   |
| Kingston RAM KF3600C18D4/32GX 32GB DIMM DDR4 4000MT/s   | 1        | 2.78%   |
| Kingston RAM KF3600C18D4/16GX 16GB DIMM DDR4 3733MT/s   | 1        | 2.78%   |
| Kingston RAM ACR26D4U9S8MH-8 8GB DIMM DDR4 2667MT/s     | 1        | 2.78%   |
| Kingston RAM 9905783-049.A01G 16384MB DIMM 4800MT/s     | 1        | 2.78%   |
| Kingston RAM 9905625-030.A00G 8GB DIMM DDR4 2133MT/s    | 1        | 2.78%   |
| Kingston RAM 9905471-015.A00LF 4GB DIMM DDR3 1600MT/s   | 1        | 2.78%   |
| G.Skill RAM F3-14900CL9-2GBXM 2048MB DIMM DDR3 1600MT/s | 1        | 2.78%   |
| Crucial RAM CT8G4DFD824A.C16FF 8GB DIMM DDR4 2733MT/s   | 1        | 2.78%   |
| Crucial RAM CT25664BA1339.C8FE 2GB DIMM DDR3 1333MT/s   | 1        | 2.78%   |
| Corsair RAM CMX8GX3M1A1600C11 8GB DIMM DDR3 1600MT/s    | 1        | 2.78%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 3066MT/s    | 1        | 2.78%   |
| A-DATA RAM Module 4096MB DIMM DDR4 2400MT/s             | 1        | 2.78%   |
| A-DATA RAM Module 16384MB DIMM DDR4 2667MT/s            | 1        | 2.78%   |
| Unknown                                                 | 1        | 2.78%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 12       | 44.44%  |
| DDR4    | 10       | 37.04%  |
| Unknown | 3        | 11.11%  |
| SDRAM   | 1        | 3.7%    |
| LPDDR4  | 1        | 3.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 24       | 88.89%  |
| SODIMM       | 2        | 7.41%   |
| Row Of Chips | 1        | 3.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 13       | 44.83%  |
| 4096  | 8        | 27.59%  |
| 16384 | 5        | 17.24%  |
| 32768 | 2        | 6.9%    |
| 2048  | 1        | 3.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 7        | 21.88%  |
| 1066  | 4        | 12.5%   |
| 1333  | 3        | 9.38%   |
| 3733  | 2        | 6.25%   |
| 3600  | 2        | 6.25%   |
| 2667  | 2        | 6.25%   |
| 2400  | 2        | 6.25%   |
| 4800  | 1        | 3.13%   |
| 4000  | 1        | 3.13%   |
| 3400  | 1        | 3.13%   |
| 3066  | 1        | 3.13%   |
| 2733  | 1        | 3.13%   |
| 2666  | 1        | 3.13%   |
| 2200  | 1        | 3.13%   |
| 2133  | 1        | 3.13%   |
| 1800  | 1        | 3.13%   |
| 800   | 1        | 3.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 3        | 37.5%   |
| Canon                 | 2        | 25%     |
| Lexmark International | 1        | 12.5%   |
| Dymo-CoStar           | 1        | 12.5%   |
| Brother Industries    | 1        | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Lexmark International Laser Printer E210 | 1        | 12.5%   |
| HP OfficeJet 5200 series                 | 1        | 12.5%   |
| HP LaserJet 1300                         | 1        | 12.5%   |
| HP Ink Tank 110 series                   | 1        | 12.5%   |
| Dymo-CoStar LabelWriter 450              | 1        | 12.5%   |
| Canon PIXMA MX390 Series                 | 1        | 12.5%   |
| Canon PIXMA MG3600 Series                | 1        | 12.5%   |
| Brother MFC-J5335DW                      | 1        | 12.5%   |

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
| Logitech                      | 9        | 27.27%  |
| Microsoft                     | 3        | 9.09%   |
| Microdia                      | 3        | 9.09%   |
| Z-Star Microelectronics       | 2        | 6.06%   |
| Chicony Electronics           | 2        | 6.06%   |
| Apple                         | 2        | 6.06%   |
| SunplusIT                     | 1        | 3.03%   |
| Sunplus IT                    | 1        | 3.03%   |
| Sunplus Innovation Technology | 1        | 3.03%   |
| Silicon Motion                | 1        | 3.03%   |
| Razer USA                     | 1        | 3.03%   |
| Philips (or NXP)              | 1        | 3.03%   |
| OmniVision Technologies       | 1        | 3.03%   |
| KYE Systems (Mouse Systems)   | 1        | 3.03%   |
| HD USB Camera                 | 1        | 3.03%   |
| Arkmicro Technologies         | 1        | 3.03%   |
| ANYKA                         | 1        | 3.03%   |
| Alcor Micro                   | 1        | 3.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Microsoft LifeCam HD-3000              | 2        | 6.06%   |
| Microdia USB 2.0 Camera                | 2        | 6.06%   |
| Logitech HD Webcam C615                | 2        | 6.06%   |
| Chicony HP High Definition 1MP Webcam  | 2        | 6.06%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR     | 2        | 6.06%   |
| Z-Star Vega USB 2.0 Camera             | 1        | 3.03%   |
| Z-Star Integrated Camera               | 1        | 3.03%   |
| SunplusIT USB camera                   | 1        | 3.03%   |
| Sunplus IT PC Camera                   | 1        | 3.03%   |
| Sunplus DICOTA 4K                      | 1        | 3.03%   |
| Silicon Motion Silicon Motion Camera   | 1        | 3.03%   |
| Razer USA Razer Kiyo Pro               | 1        | 3.03%   |
| Philips (or NXP) SPZ2500               | 1        | 3.03%   |
| OmniVision Monitor Webcam              | 1        | 3.03%   |
| Microsoft LifeCam VX-800               | 1        | 3.03%   |
| Microdia Camera                        | 1        | 3.03%   |
| Logitech Webcam C270                   | 1        | 3.03%   |
| Logitech QuickCam Communicate Deluxe   | 1        | 3.03%   |
| Logitech Logitech Webcam C925e         | 1        | 3.03%   |
| Logitech HD Webcam C910                | 1        | 3.03%   |
| Logitech C922 Pro Stream Webcam        | 1        | 3.03%   |
| Logitech BRIO 4K Stream Edition        | 1        | 3.03%   |
| Logitech B525 HD Webcam                | 1        | 3.03%   |
| KYE Systems (Mouse Systems) iSlim 1300 | 1        | 3.03%   |
| HD USB Camera HD USB Camera            | 1        | 3.03%   |
| Arkmicro USB2.0 PC CAMERA              | 1        | 3.03%   |
| ANYKA V380 FHD Camera                  | 1        | 3.03%   |
| Alcor Micro USB 2.0 PC Camera          | 1        | 3.03%   |

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
| 0     | 161      | 83.85%  |
| 1     | 25       | 13.02%  |
| 2     | 5        | 2.6%    |
| 4     | 1        | 0.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 15       | 44.12%  |
| Graphics card            | 5        | 14.71%  |
| Sound                    | 4        | 11.76%  |
| Bluetooth                | 3        | 8.82%   |
| Unassigned class         | 2        | 5.88%   |
| Storage/ide              | 1        | 2.94%   |
| Network                  | 1        | 2.94%   |
| Multimedia controller    | 1        | 2.94%   |
| Fingerprint reader       | 1        | 2.94%   |
| Communication controller | 1        | 2.94%   |

