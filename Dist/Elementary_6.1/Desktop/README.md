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

Total: 255

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.11.0-43-generic      | 36       | 17.39%  |
| 5.13.0-39-generic      | 17       | 8.21%   |
| 5.13.0-28-generic      | 16       | 7.73%   |
| 5.15.0-46-generic      | 14       | 6.76%   |
| 5.13.0-27-generic      | 10       | 4.83%   |
| 5.13.0-40-generic      | 9        | 4.35%   |
| 5.13.0-30-generic      | 9        | 4.35%   |
| 5.15.0-56-generic      | 8        | 3.86%   |
| 5.13.0-35-generic      | 7        | 3.38%   |
| 5.13.0-37-generic      | 6        | 2.9%    |
| 5.15.0-58-generic      | 5        | 2.42%   |
| 5.13.0-52-generic      | 5        | 2.42%   |
| 5.13.0-51-generic      | 5        | 2.42%   |
| 5.11.0-41-generic      | 5        | 2.42%   |
| 5.15.0-53-generic      | 4        | 1.93%   |
| 5.15.0-52-generic      | 4        | 1.93%   |
| 5.15.0-41-generic      | 4        | 1.93%   |
| 5.13.0-44-generic      | 4        | 1.93%   |
| 5.11.0-44-generic      | 4        | 1.93%   |
| 5.15.0-57-generic      | 3        | 1.45%   |
| 5.15.0-50-generic      | 3        | 1.45%   |
| 5.15.0-48-generic      | 3        | 1.45%   |
| 5.13.0-48-generic      | 3        | 1.45%   |
| 5.15.0-73-generic      | 2        | 0.97%   |
| 5.15.0-69-generic      | 2        | 0.97%   |
| 5.13.0-41-generic      | 2        | 0.97%   |
| 5.13.0-25-generic      | 2        | 0.97%   |
| 5.11.0-46-generic      | 2        | 0.97%   |
| 5.11.0-40-generic      | 2        | 0.97%   |
| 6.1.8-x64v2-xanmod1    | 1        | 0.48%   |
| 5.17.3-xanmod1         | 1        | 0.48%   |
| 5.16.15-051615-generic | 1        | 0.48%   |
| 5.15.36-xanmod1        | 1        | 0.48%   |
| 5.15.0-71-generic      | 1        | 0.48%   |
| 5.15.0-60-generic      | 1        | 0.48%   |
| 5.14.0-1042-oem        | 1        | 0.48%   |
| 5.13.0-28-lowlatency   | 1        | 0.48%   |
| 5.13.0-22-generic      | 1        | 0.48%   |
| 5.11.0-43-lowlatency   | 1        | 0.48%   |
| 5.11.0-37-generic      | 1        | 0.48%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13.0  | 87       | 45.31%  |
| 5.15.0  | 51       | 26.56%  |
| 5.11.0  | 49       | 25.52%  |
| 6.1.8   | 1        | 0.52%   |
| 5.17.3  | 1        | 0.52%   |
| 5.16.15 | 1        | 0.52%   |
| 5.15.36 | 1        | 0.52%   |
| 5.14.0  | 1        | 0.52%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.13    | 87       | 45.31%  |
| 5.15    | 52       | 27.08%  |
| 5.11    | 49       | 25.52%  |
| 6.1     | 1        | 0.52%   |
| 5.17    | 1        | 0.52%   |
| 5.16    | 1        | 0.52%   |
| 5.14    | 1        | 0.52%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 183      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Pantheon | 182      | 99.45%  |
| KDE5     | 1        | 0.55%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 183      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 157      | 84.41%  |
| LightDM | 29       | 15.59%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 76       | 41.08%  |
| de_DE | 22       | 11.89%  |
| fr_FR | 14       | 7.57%   |
| es_ES | 14       | 7.57%   |
| ru_RU | 12       | 6.49%   |
| pt_BR | 8        | 4.32%   |
| it_IT | 8        | 4.32%   |
| en_GB | 7        | 3.78%   |
| pt_PT | 3        | 1.62%   |
| pl_PL | 3        | 1.62%   |
| en_CA | 3        | 1.62%   |
| tr_TR | 2        | 1.08%   |
| ja_JP | 2        | 1.08%   |
| en_AU | 2        | 1.08%   |
| zh_CN | 1        | 0.54%   |
| uk_UA | 1        | 0.54%   |
| sr_RS | 1        | 0.54%   |
| nl_NL | 1        | 0.54%   |
| nb_NO | 1        | 0.54%   |
| id_ID | 1        | 0.54%   |
| fr_CA | 1        | 0.54%   |
| de_CH | 1        | 0.54%   |
| C     | 1        | 0.54%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 99       | 52.94%  |
| BIOS | 88       | 47.06%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 174      | 95.08%  |
| Btrfs    | 5        | 2.73%   |
| Xfs      | 2        | 1.09%   |
| Reiserfs | 1        | 0.55%   |
| Overlay  | 1        | 0.55%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 161      | 87.03%  |
| GPT     | 19       | 10.27%  |
| MBR     | 5        | 2.7%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 177      | 95.68%  |
| Yes       | 8        | 4.32%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 171      | 92.93%  |
| Yes       | 13       | 7.07%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 46       | 25.14%  |
| Gigabyte Technology | 29       | 15.85%  |
| MSI                 | 19       | 10.38%  |
| Hewlett-Packard     | 16       | 8.74%   |
| Dell                | 13       | 7.1%    |
| ASRock              | 12       | 6.56%   |
| Lenovo              | 5        | 2.73%   |
| Acer                | 5        | 2.73%   |
| Intel               | 4        | 2.19%   |
| Foxconn             | 4        | 2.19%   |
| Biostar             | 4        | 2.19%   |
| Unknown             | 4        | 2.19%   |
| Fujitsu             | 3        | 1.64%   |
| Apple               | 3        | 1.64%   |
| Pegatron            | 2        | 1.09%   |
| ECS                 | 2        | 1.09%   |
| T-bao               | 1        | 0.55%   |
| Packard Bell        | 1        | 0.55%   |
| LORD ELECTRONICS    | 1        | 0.55%   |
| LattePanda          | 1        | 0.55%   |
| Kraftway            | 1        | 0.55%   |
| IceWhale Technology | 1        | 0.55%   |
| FIRICH              | 1        | 0.55%   |
| EVGA                | 1        | 0.55%   |
| BESSTAR Tech        | 1        | 0.55%   |
| AZW                 | 1        | 0.55%   |
| AOpen               | 1        | 0.55%   |
| AMI                 | 1        | 0.55%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| ASUS All Series                                   | 4        | 2.19%   |
| Unknown                                           | 4        | 2.19%   |
| MSI MS-7C35                                       | 2        | 1.09%   |
| HP Compaq Pro 6300 MT                             | 2        | 1.09%   |
| Gigabyte Z390 UD                                  | 2        | 1.09%   |
| Dell OptiPlex 790                                 | 2        | 1.09%   |
| ASUS TUF Gaming B550M-PLUS                        | 2        | 1.09%   |
| T-bao MINI PC                                     | 1        | 0.55%   |
| Pegatron p7-1174                                  | 1        | 0.55%   |
| Pegatron IPMH61P1                                 | 1        | 0.55%   |
| Packard Bell IMEDIA S1300                         | 1        | 0.55%   |
| MSI PPPPP-CCC#MMMMMMMM                            | 1        | 0.55%   |
| MSI MS-7D52                                       | 1        | 0.55%   |
| MSI MS-7C91                                       | 1        | 0.55%   |
| MSI MS-7C77                                       | 1        | 0.55%   |
| MSI MS-7C52                                       | 1        | 0.55%   |
| MSI MS-7C02                                       | 1        | 0.55%   |
| MSI MS-7B86                                       | 1        | 0.55%   |
| MSI MS-7B84                                       | 1        | 0.55%   |
| MSI MS-7B79                                       | 1        | 0.55%   |
| MSI MS-7B61                                       | 1        | 0.55%   |
| MSI MS-7A59                                       | 1        | 0.55%   |
| MSI MS-7A40                                       | 1        | 0.55%   |
| MSI MS-7A38                                       | 1        | 0.55%   |
| MSI MS-7918                                       | 1        | 0.55%   |
| MSI MS-7885                                       | 1        | 0.55%   |
| MSI MS-7851                                       | 1        | 0.55%   |
| MSI MS-7817                                       | 1        | 0.55%   |
| LORD ELECTRONICS LORD G4x 775 ICH7 8712 As Design | 1        | 0.55%   |
| Lenovo ThinkCentre M73 10B6001SUS                 | 1        | 0.55%   |
| Lenovo ThinkCentre M72e 3664AD7                   | 1        | 0.55%   |
| Lenovo ThinkCentre M70e 0809D1Y                   | 1        | 0.55%   |
| Lenovo ThinkCentre M58 6258D3G                    | 1        | 0.55%   |
| Lenovo IdeaCentre 510S-07ICK 90LX006TGE           | 1        | 0.55%   |
| LattePanda Alpha                                  | 1        | 0.55%   |
| Kraftway Credo KCxx                               | 1        | 0.55%   |
| Intel X79                                         | 1        | 0.55%   |
| Intel Jasper Lake Client Platform                 | 1        | 0.55%   |
| Intel H61                                         | 1        | 0.55%   |
| Intel DH61BE AAG14062-210                         | 1        | 0.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 9        | 4.92%   |
| ASUS PRIME             | 9        | 4.92%   |
| ASUS TUF               | 7        | 3.83%   |
| ASUS ROG               | 6        | 3.28%   |
| Lenovo ThinkCentre     | 4        | 2.19%   |
| HP Compaq              | 4        | 2.19%   |
| ASUS All               | 4        | 2.19%   |
| Unknown                | 4        | 2.19%   |
| Fujitsu ESPRIMO        | 3        | 1.64%   |
| ASUS P8H61-M           | 3        | 1.64%   |
| MSI MS-7C35            | 2        | 1.09%   |
| HP ProDesk             | 2        | 1.09%   |
| Gigabyte Z390          | 2        | 1.09%   |
| Gigabyte H310M         | 2        | 1.09%   |
| Gigabyte A320M-S2H     | 2        | 1.09%   |
| Dell Precision         | 2        | 1.09%   |
| Acer Veriton           | 2        | 1.09%   |
| Acer Aspire            | 2        | 1.09%   |
| T-bao MINI             | 1        | 0.55%   |
| Pegatron p7-1174       | 1        | 0.55%   |
| Pegatron IPMH61P1      | 1        | 0.55%   |
| Packard Bell IMEDIA    | 1        | 0.55%   |
| MSI PPPPP-CCC#MMMMMMMM | 1        | 0.55%   |
| MSI MS-7D52            | 1        | 0.55%   |
| MSI MS-7C91            | 1        | 0.55%   |
| MSI MS-7C77            | 1        | 0.55%   |
| MSI MS-7C52            | 1        | 0.55%   |
| MSI MS-7C02            | 1        | 0.55%   |
| MSI MS-7B86            | 1        | 0.55%   |
| MSI MS-7B84            | 1        | 0.55%   |
| MSI MS-7B79            | 1        | 0.55%   |
| MSI MS-7B61            | 1        | 0.55%   |
| MSI MS-7A59            | 1        | 0.55%   |
| MSI MS-7A40            | 1        | 0.55%   |
| MSI MS-7A38            | 1        | 0.55%   |
| MSI MS-7918            | 1        | 0.55%   |
| MSI MS-7885            | 1        | 0.55%   |
| MSI MS-7851            | 1        | 0.55%   |
| MSI MS-7817            | 1        | 0.55%   |
| LORD ELECTRONICS LORD  | 1        | 0.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 23       | 12.57%  |
| 2012 | 23       | 12.57%  |
| 2010 | 18       | 9.84%   |
| 2020 | 15       | 8.2%    |
| 2019 | 15       | 8.2%    |
| 2011 | 15       | 8.2%    |
| 2015 | 12       | 6.56%   |
| 2014 | 12       | 6.56%   |
| 2013 | 11       | 6.01%   |
| 2021 | 9        | 4.92%   |
| 2017 | 9        | 4.92%   |
| 2022 | 5        | 2.73%   |
| 2016 | 5        | 2.73%   |
| 2009 | 4        | 2.19%   |
| 2008 | 4        | 2.19%   |
| 2007 | 2        | 1.09%   |
| 2006 | 1        | 0.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 183      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 174      | 95.08%  |
| Enabled  | 9        | 4.92%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 183      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 40       | 21.62%  |
| 8.01-16.0   | 39       | 21.08%  |
| 32.01-64.0  | 33       | 17.84%  |
| 4.01-8.0    | 28       | 15.14%  |
| 3.01-4.0    | 28       | 15.14%  |
| 64.01-256.0 | 6        | 3.24%   |
| 24.01-32.0  | 5        | 2.7%    |
| 1.01-2.0    | 4        | 2.16%   |
| 2.01-3.0    | 2        | 1.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 75       | 36.95%  |
| 2.01-3.0  | 58       | 28.57%  |
| 4.01-8.0  | 33       | 16.26%  |
| 3.01-4.0  | 25       | 12.32%  |
| 8.01-16.0 | 7        | 3.45%   |
| 0.51-1.0  | 5        | 2.46%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 63       | 33.69%  |
| 1      | 63       | 33.69%  |
| 3      | 31       | 16.58%  |
| 4      | 18       | 9.63%   |
| 5      | 5        | 2.67%   |
| 6      | 4        | 2.14%   |
| 7      | 2        | 1.07%   |
| 0      | 1        | 0.53%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 100      | 53.48%  |
| Yes       | 87       | 46.52%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 182      | 99.45%  |
| No        | 1        | 0.55%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 94       | 50.54%  |
| Yes       | 92       | 49.46%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 114      | 61.62%  |
| Yes       | 71       | 38.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 29       | 15.85%  |
| Germany      | 20       | 10.93%  |
| Russia       | 13       | 7.1%    |
| France       | 11       | 6.01%   |
| Brazil       | 11       | 6.01%   |
| UK           | 9        | 4.92%   |
| Spain        | 8        | 4.37%   |
| Italy        | 8        | 4.37%   |
| Canada       | 7        | 3.83%   |
| Indonesia    | 6        | 3.28%   |
| Switzerland  | 5        | 2.73%   |
| Poland       | 4        | 2.19%   |
| Australia    | 4        | 2.19%   |
| Turkey       | 3        | 1.64%   |
| Japan        | 3        | 1.64%   |
| India        | 3        | 1.64%   |
| Colombia     | 3        | 1.64%   |
| Austria      | 3        | 1.64%   |
| Argentina    | 3        | 1.64%   |
| Portugal     | 2        | 1.09%   |
| Norway       | 2        | 1.09%   |
| Netherlands  | 2        | 1.09%   |
| Iran         | 2        | 1.09%   |
| Thailand     | 1        | 0.55%   |
| Sweden       | 1        | 0.55%   |
| Sri Lanka    | 1        | 0.55%   |
| South Africa | 1        | 0.55%   |
| Slovenia     | 1        | 0.55%   |
| Serbia       | 1        | 0.55%   |
| Romania      | 1        | 0.55%   |
| Pakistan     | 1        | 0.55%   |
| New Zealand  | 1        | 0.55%   |
| Mexico       | 1        | 0.55%   |
| Malaysia     | 1        | 0.55%   |
| Lithuania    | 1        | 0.55%   |
| Libya        | 1        | 0.55%   |
| Kenya        | 1        | 0.55%   |
| Israel       | 1        | 0.55%   |
| Ireland      | 1        | 0.55%   |
| Hong Kong    | 1        | 0.55%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Desktops | Percent |
|---------------|----------|---------|
| Moscow        | 4        | 2.03%   |
| Warsaw        | 3        | 1.52%   |
| Hamburg       | 3        | 1.52%   |
| Caslano       | 3        | 1.52%   |
| Vienna        | 2        | 1.02%   |
| Tangerang     | 2        | 1.02%   |
| Sao Vicente   | 2        | 1.02%   |
| Sao Paulo     | 2        | 1.02%   |
| Paris         | 2        | 1.02%   |
| Istanbul      | 2        | 1.02%   |
| Denver        | 2        | 1.02%   |
| Brisbane      | 2        | 1.02%   |
| Bandung       | 2        | 1.02%   |
| Yucca Valley  | 1        | 0.51%   |
| Yokohama      | 1        | 0.51%   |
| Yarang        | 1        | 0.51%   |
| Wroclaw       | 1        | 0.51%   |
| Woolloongabba | 1        | 0.51%   |
| Woodbridge    | 1        | 0.51%   |
| Wolgast       | 1        | 0.51%   |
| Werneck       | 1        | 0.51%   |
| Walnut Creek  | 1        | 0.51%   |
| Vanse         | 1        | 0.51%   |
| Trondheim     | 1        | 0.51%   |
| Troisdorf     | 1        | 0.51%   |
| Tripoli       | 1        | 0.51%   |
| Tournus       | 1        | 0.51%   |
| Toronto       | 1        | 0.51%   |
| Thrissur      | 1        | 0.51%   |
| Teresina      | 1        | 0.51%   |
| Tel Aviv      | 1        | 0.51%   |
| Tehran        | 1        | 0.51%   |
| Tacoma        | 1        | 0.51%   |
| Sydney        | 1        | 0.51%   |
| Suresnes      | 1        | 0.51%   |
| Surabaya      | 1        | 0.51%   |
| Stuttgart     | 1        | 0.51%   |
| St Petersburg | 1        | 0.51%   |
| Spello        | 1        | 0.51%   |
| Songkhla      | 1        | 0.51%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 58       | 89     | 17.16%  |
| Seagate                   | 57       | 82     | 16.86%  |
| Samsung Electronics       | 46       | 73     | 13.61%  |
| Kingston                  | 25       | 33     | 7.4%    |
| Toshiba                   | 19       | 27     | 5.62%   |
| SanDisk                   | 12       | 15     | 3.55%   |
| Crucial                   | 12       | 15     | 3.55%   |
| Hitachi                   | 9        | 10     | 2.66%   |
| Unknown                   | 7        | 15     | 2.07%   |
| PNY                       | 7        | 11     | 2.07%   |
| Micron/Crucial Technology | 6        | 10     | 1.78%   |
| Intel                     | 6        | 6      | 1.78%   |
| Phison                    | 5        | 5      | 1.48%   |
| A-DATA Technology         | 5        | 5      | 1.48%   |
| Micron Technology         | 4        | 5      | 1.18%   |
| China                     | 4        | 6      | 1.18%   |
| Team                      | 3        | 5      | 0.89%   |
| SPCC                      | 3        | 3      | 0.89%   |
| Maxtor                    | 3        | 3      | 0.89%   |
| JMicron Technology        | 3        | 3      | 0.89%   |
| HUSKY                     | 3        | 4      | 0.89%   |
| HGST                      | 3        | 3      | 0.89%   |
| ASMT                      | 3        | 3      | 0.89%   |
| Transcend                 | 2        | 2      | 0.59%   |
| Silicon Motion            | 2        | 2      | 0.59%   |
| Realtek Semiconductor     | 2        | 2      | 0.59%   |
| Plextor                   | 2        | 3      | 0.59%   |
| OCZ                       | 2        | 5      | 0.59%   |
| LITEON                    | 2        | 2      | 0.59%   |
| Corsair                   | 2        | 2      | 0.59%   |
| XPG                       | 1        | 1      | 0.3%    |
| tigo                      | 1        | 1      | 0.3%    |
| SK hynix                  | 1        | 1      | 0.3%    |
| Phison Electronics        | 1        | 1      | 0.3%    |
| Patriot                   | 1        | 1      | 0.3%    |
| OCZ-VERTEX2               | 1        | 1      | 0.3%    |
| Netac                     | 1        | 1      | 0.3%    |
| MidasForce                | 1        | 1      | 0.3%    |
| Lexar                     | 1        | 1      | 0.3%    |
| Leven                     | 1        | 1      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Drive 500GB                        | 7        | 1.82%   |
| Toshiba DT01ACA050 500GB                            | 5        | 1.3%    |
| Seagate ST500DM002-1BD142 500GB                     | 5        | 1.3%    |
| Seagate ST1000DM003-1ER162 1TB                      | 5        | 1.3%    |
| WDC WD5000AAKX-00ERMA0 500GB                        | 4        | 1.04%   |
| Samsung SSD 860 EVO 250GB                           | 4        | 1.04%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 4        | 1.04%   |
| Micron/Crucial NVMe SSD Drive 1TB                   | 4        | 1.04%   |
| Kingston SA400S37240G 240GB SSD                     | 4        | 1.04%   |
| Kingston SA400S37120G 120GB SSD                     | 4        | 1.04%   |
| Crucial CT240BX500SSD1 240GB                        | 4        | 1.04%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 3        | 0.78%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 3        | 0.78%   |
| Unknown SD/MMC 2GB                                  | 3        | 0.78%   |
| Unknown M.S./M.S.Pro/HG 16GB                        | 3        | 0.78%   |
| Toshiba DT01ACA100 1TB                              | 3        | 0.78%   |
| Seagate ST3500418AS 500GB                           | 3        | 0.78%   |
| Seagate ST1000DM010-2EP102 1TB                      | 3        | 0.78%   |
| Samsung SSD 860 EVO 1TB                             | 3        | 0.78%   |
| Samsung SSD 850 EVO 250GB                           | 3        | 0.78%   |
| Phison NVMe SSD Drive 1TB                           | 3        | 0.78%   |
| Kingston SV300S37A120G 120GB SSD                    | 3        | 0.78%   |
| Kingston NVMe SSD Drive 1TB                         | 3        | 0.78%   |
| HUSKY SSD 128GB                                     | 3        | 0.78%   |
| WDC WD5000AAKX-001CA0 500GB                         | 2        | 0.52%   |
| WDC WD5000AAKS-00UU3A0 500GB                        | 2        | 0.52%   |
| WDC WD40EFRX-68N32N0 4TB                            | 2        | 0.52%   |
| WDC WD10EADS-00L5B1 1TB                             | 2        | 0.52%   |
| Unknown MMC Card  32GB                              | 2        | 0.52%   |
| Toshiba HDWD110 1TB                                 | 2        | 0.52%   |
| Seagate ST3500630AS 500GB                           | 2        | 0.52%   |
| Seagate ST3500413AS 500GB                           | 2        | 0.52%   |
| Seagate ST3160815AS 160GB                           | 2        | 0.52%   |
| Seagate ST31000528AS 1TB                            | 2        | 0.52%   |
| Seagate ST2000DX002-2DV164 2TB                      | 2        | 0.52%   |
| Seagate ST2000DM001-9YN164 2TB                      | 2        | 0.52%   |
| Seagate ST1000DM003-1CH162 1TB                      | 2        | 0.52%   |
| SanDisk SDSSDHP256G 256GB                           | 2        | 0.52%   |
| Samsung SSD 870 EVO 1TB                             | 2        | 0.52%   |
| Samsung SSD 860 QVO 1TB                             | 2        | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 54       | 78     | 35.76%  |
| WDC                 | 50       | 71     | 33.11%  |
| Toshiba             | 18       | 26     | 11.92%  |
| Samsung Electronics | 10       | 12     | 6.62%   |
| Hitachi             | 9        | 10     | 5.96%   |
| HGST                | 3        | 3      | 1.99%   |
| Maxtor              | 2        | 2      | 1.32%   |
| ASMT                | 2        | 2      | 1.32%   |
| Unknown             | 1        | 1      | 0.66%   |
| Hewlett-Packard     | 1        | 1      | 0.66%   |
| Fujitsu             | 1        | 1      | 0.66%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 24       | 38     | 19.35%  |
| Kingston            | 19       | 23     | 15.32%  |
| Crucial             | 11       | 13     | 8.87%   |
| SanDisk             | 10       | 12     | 8.06%   |
| WDC                 | 7        | 12     | 5.65%   |
| PNY                 | 7        | 11     | 5.65%   |
| China               | 4        | 6      | 3.23%   |
| A-DATA Technology   | 4        | 4      | 3.23%   |
| Team                | 3        | 5      | 2.42%   |
| SPCC                | 3        | 3      | 2.42%   |
| Intel               | 3        | 3      | 2.42%   |
| HUSKY               | 3        | 4      | 2.42%   |
| Transcend           | 2        | 2      | 1.61%   |
| Plextor             | 2        | 3      | 1.61%   |
| OCZ                 | 2        | 5      | 1.61%   |
| Micron Technology   | 2        | 2      | 1.61%   |
| LITEON              | 2        | 2      | 1.61%   |
| Corsair             | 2        | 2      | 1.61%   |
| Toshiba             | 1        | 1      | 0.81%   |
| tigo                | 1        | 1      | 0.81%   |
| Seagate             | 1        | 2      | 0.81%   |
| Patriot             | 1        | 1      | 0.81%   |
| OCZ-VERTEX2         | 1        | 1      | 0.81%   |
| MidasForce          | 1        | 1      | 0.81%   |
| Maxtor              | 1        | 1      | 0.81%   |
| Lexar               | 1        | 1      | 0.81%   |
| Leven               | 1        | 1      | 0.81%   |
| Intenso             | 1        | 1      | 0.81%   |
| GOODRAM             | 1        | 1      | 0.81%   |
| Gigabyte Technology | 1        | 1      | 0.81%   |
| ASMT                | 1        | 1      | 0.81%   |
| Unknown             | 1        | 1      | 0.81%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 122      | 207    | 41.5%   |
| SSD     | 107      | 165    | 36.39%  |
| NVMe    | 51       | 74     | 17.35%  |
| Unknown | 11       | 22     | 3.74%   |
| MMC     | 3        | 3      | 1.02%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 167      | 370    | 71.06%  |
| NVMe | 50       | 73     | 21.28%  |
| SAS  | 15       | 25     | 6.38%   |
| MMC  | 3        | 3      | 1.28%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 128      | 220    | 57.14%  |
| 0.51-1.0   | 56       | 98     | 25%     |
| 1.01-2.0   | 19       | 22     | 8.48%   |
| 2.01-3.0   | 9        | 17     | 4.02%   |
| 3.01-4.0   | 6        | 6      | 2.68%   |
| 4.01-10.0  | 6        | 9      | 2.68%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 65       | 34.03%  |
| 251-500        | 41       | 21.47%  |
| 501-1000       | 37       | 19.37%  |
| 1001-2000      | 19       | 9.95%   |
| More than 3000 | 10       | 5.24%   |
| 51-100         | 10       | 5.24%   |
| 21-50          | 5        | 2.62%   |
| 2001-3000      | 4        | 2.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 78       | 38.24%  |
| 21-50          | 33       | 16.18%  |
| 101-250        | 28       | 13.73%  |
| 51-100         | 25       | 12.25%  |
| 251-500        | 18       | 8.82%   |
| 501-1000       | 11       | 5.39%   |
| 1001-2000      | 6        | 2.94%   |
| More than 3000 | 3        | 1.47%   |
| 2001-3000      | 2        | 0.98%   |

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
| Detected | 166      | 423    | 87.83%  |
| Works    | 19       | 44     | 10.05%  |
| Malfunc  | 4        | 4      | 2.12%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 123      | 48.62%  |
| AMD                         | 50       | 19.76%  |
| Samsung Electronics         | 20       | 7.91%   |
| Nvidia                      | 8        | 3.16%   |
| Micron/Crucial Technology   | 7        | 2.77%   |
| Kingston Technology Company | 7        | 2.77%   |
| Phison Electronics          | 6        | 2.37%   |
| SanDisk                     | 5        | 1.98%   |
| Marvell Technology Group    | 5        | 1.98%   |
| ASMedia Technology          | 5        | 1.98%   |
| JMicron Technology          | 4        | 1.58%   |
| Realtek Semiconductor       | 3        | 1.19%   |
| Silicon Motion              | 2        | 0.79%   |
| Seagate Technology          | 2        | 0.79%   |
| Micron Technology           | 2        | 0.79%   |
| LSI Logic / Symbios Logic   | 2        | 0.79%   |
| SK hynix                    | 1        | 0.4%    |
| ADATA Technology            | 1        | 0.4%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 31       | 9.84%   |
| AMD 400 Series Chipset SATA Controller                                                  | 17       | 5.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 16       | 5.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12       | 3.81%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 11       | 3.49%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 10       | 3.17%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 10       | 3.17%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 10       | 3.17%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 8        | 2.54%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8        | 2.54%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 8        | 2.54%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 6        | 1.9%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 1.9%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 5        | 1.59%   |
| Nvidia MCP61 SATA Controller                                                            | 5        | 1.59%   |
| Kingston Company A2000 NVMe SSD                                                         | 5        | 1.59%   |
| Intel SATA Controller [RAID mode]                                                       | 5        | 1.59%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5        | 1.59%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 1.59%   |
| AMD 500 Series Chipset SATA Controller                                                  | 5        | 1.59%   |
| Phison E12 NVMe Controller                                                              | 3        | 0.95%   |
| Nvidia MCP61 IDE                                                                        | 3        | 0.95%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 0.95%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3        | 0.95%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3        | 0.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3        | 0.95%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 0.95%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 0.63%   |
| Samsung NVMe SSD Controller 980                                                         | 2        | 0.63%   |
| Realtek NVMe Controller                                                                 | 2        | 0.63%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 0.63%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 2        | 0.63%   |
| Micron 2200S NVMe SSD                                                                   | 2        | 0.63%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2        | 0.63%   |
| JMicron JMB368 IDE controller                                                           | 2        | 0.63%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2        | 0.63%   |
| Intel SSD 660P Series                                                                   | 2        | 0.63%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2        | 0.63%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 2        | 0.63%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 141      | 55.95%  |
| NVMe | 50       | 19.84%  |
| IDE  | 48       | 19.05%  |
| RAID | 11       | 4.37%   |
| SAS  | 1        | 0.4%    |
| SCSI | 1        | 0.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 126      | 68.85%  |
| AMD    | 57       | 31.15%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-2400 CPU @ 3.10GHz            | 5        | 2.73%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 5        | 2.73%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 4        | 2.19%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 4        | 2.19%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 4        | 2.19%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 4        | 2.19%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 3        | 1.64%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 1.64%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3        | 1.64%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 1.64%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz     | 3        | 1.64%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 3        | 1.64%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 1.64%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 2        | 1.09%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2        | 1.09%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2        | 1.09%   |
| Intel Core i7-10700K CPU @ 3.80GHz          | 2        | 1.09%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 2        | 1.09%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 2        | 1.09%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2        | 1.09%   |
| Intel Core i3 CPU 530 @ 2.93GHz             | 2        | 1.09%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz       | 2        | 1.09%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 2        | 1.09%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 2        | 1.09%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 2        | 1.09%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 2        | 1.09%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 2        | 1.09%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2        | 1.09%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 2        | 1.09%   |
| Intel Xeon CPU X5680 @ 3.33GHz              | 1        | 0.55%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1        | 0.55%   |
| Intel Xeon CPU E5462 @ 2.80GHz              | 1        | 0.55%   |
| Intel Xeon CPU E5410 @ 2.33GHz              | 1        | 0.55%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1        | 0.55%   |
| Intel Xeon CPU E5-2665 0 @ 2.40GHz          | 1        | 0.55%   |
| Intel Xeon CPU E5-1660 0 @ 3.30GHz          | 1        | 0.55%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz         | 1        | 0.55%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz         | 1        | 0.55%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz         | 1        | 0.55%   |
| Intel Xeon CPU E31270 @ 3.40GHz             | 1        | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 31       | 16.94%  |
| Intel Core i7           | 28       | 15.3%   |
| Intel Core i3           | 18       | 9.84%   |
| AMD Ryzen 5             | 18       | 9.84%   |
| Intel Xeon              | 14       | 7.65%   |
| AMD Ryzen 7             | 11       | 6.01%   |
| Intel Celeron           | 7        | 3.83%   |
| AMD Ryzen 9             | 6        | 3.28%   |
| Other                   | 5        | 2.73%   |
| Intel Core 2 Quad       | 5        | 2.73%   |
| Intel Pentium Dual-Core | 4        | 2.19%   |
| Intel Pentium           | 4        | 2.19%   |
| AMD FX                  | 4        | 2.19%   |
| AMD Athlon II X2        | 4        | 2.19%   |
| Intel Core 2 Duo        | 3        | 1.64%   |
| Intel Atom              | 3        | 1.64%   |
| AMD Phenom II X4        | 3        | 1.64%   |
| AMD A8                  | 3        | 1.64%   |
| Intel Core i9           | 2        | 1.09%   |
| AMD Athlon              | 2        | 1.09%   |
| AMD A10                 | 2        | 1.09%   |
| Intel Pentium Gold      | 1        | 0.55%   |
| Intel Core m3           | 1        | 0.55%   |
| AMD Ryzen 3             | 1        | 0.55%   |
| AMD Phenom II X6        | 1        | 0.55%   |
| AMD Athlon X4           | 1        | 0.55%   |
| AMD Athlon II X4        | 1        | 0.55%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 80       | 43.24%  |
| 2      | 44       | 23.78%  |
| 8      | 25       | 13.51%  |
| 6      | 25       | 13.51%  |
| 12     | 6        | 3.24%   |
| 16     | 2        | 1.08%   |
| 1      | 2        | 1.08%   |
| 3      | 1        | 0.54%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 180      | 98.36%  |
| 2      | 3        | 1.64%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 108      | 58.38%  |
| 1      | 77       | 41.62%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 183      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x206a7    | 22       | 11.76%  |
| 0x306c3    | 17       | 9.09%   |
| Unknown    | 12       | 6.42%   |
| 0x306a9    | 11       | 5.88%   |
| 0x08701021 | 9        | 4.81%   |
| 0x1067a    | 7        | 3.74%   |
| 0x906ea    | 6        | 3.21%   |
| 0x08108109 | 6        | 3.21%   |
| 0x0800820d | 6        | 3.21%   |
| 0x906ed    | 5        | 2.67%   |
| 0x906e9    | 5        | 2.67%   |
| 0x506e3    | 5        | 2.67%   |
| 0x906eb    | 4        | 2.14%   |
| 0x6fb      | 4        | 2.14%   |
| 0x0a201016 | 4        | 2.14%   |
| 0xa0671    | 3        | 1.6%    |
| 0x206d7    | 3        | 1.6%    |
| 0x06003106 | 3        | 1.6%    |
| 0x06000852 | 3        | 1.6%    |
| 0x010000c8 | 3        | 1.6%    |
| 0xa0655    | 2        | 1.07%   |
| 0xa0653    | 2        | 1.07%   |
| 0x406c4    | 2        | 1.07%   |
| 0x306e4    | 2        | 1.07%   |
| 0x206c2    | 2        | 1.07%   |
| 0x20655    | 2        | 1.07%   |
| 0x20652    | 2        | 1.07%   |
| 0x106e5    | 2        | 1.07%   |
| 0x10676    | 2        | 1.07%   |
| 0x0a50000c | 2        | 1.07%   |
| 0x08701013 | 2        | 1.07%   |
| 0x08001138 | 2        | 1.07%   |
| 0x010000c7 | 2        | 1.07%   |
| 0x906ec    | 1        | 0.53%   |
| 0x906c0    | 1        | 0.53%   |
| 0x90672    | 1        | 0.53%   |
| 0x806e9    | 1        | 0.53%   |
| 0x806c1    | 1        | 0.53%   |
| 0x706a8    | 1        | 0.53%   |
| 0x6f7      | 1        | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| SandyBridge      | 26       | 14.21%  |
| KabyLake         | 23       | 12.57%  |
| Haswell          | 19       | 10.38%  |
| Zen+             | 13       | 7.1%    |
| IvyBridge        | 13       | 7.1%    |
| Zen 2            | 11       | 6.01%   |
| Zen 3            | 9        | 4.92%   |
| Penryn           | 9        | 4.92%   |
| K10              | 9        | 4.92%   |
| Westmere         | 6        | 3.28%   |
| Zen              | 5        | 2.73%   |
| Skylake          | 5        | 2.73%   |
| Core             | 5        | 2.73%   |
| Steamroller      | 4        | 2.19%   |
| Piledriver       | 4        | 2.19%   |
| CometLake        | 4        | 2.19%   |
| Silvermont       | 3        | 1.64%   |
| Nehalem          | 3        | 1.64%   |
| Icelake          | 3        | 1.64%   |
| Tremont          | 1        | 0.55%   |
| TigerLake        | 1        | 0.55%   |
| K10 Llano        | 1        | 0.55%   |
| Goldmont plus    | 1        | 0.55%   |
| Goldmont         | 1        | 0.55%   |
| Bulldozer        | 1        | 0.55%   |
| Broadwell        | 1        | 0.55%   |
| Bonnell          | 1        | 0.55%   |
| Alderlake Hybrid | 1        | 0.55%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 71       | 36.79%  |
| Nvidia | 61       | 31.61%  |
| Intel  | 61       | 31.61%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17       | 8.5%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 11       | 5.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8        | 4%      |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 7        | 3.5%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6        | 3%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5        | 2.5%    |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 4        | 2%      |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 4        | 2%      |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 4        | 2%      |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 3        | 1.5%    |
| Nvidia TU106 [GeForce GTX 1650]                                                          | 3        | 1.5%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 3        | 1.5%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3        | 1.5%    |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                                           | 3        | 1.5%    |
| Intel HD Graphics 530                                                                    | 3        | 1.5%    |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 3        | 1.5%    |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 2        | 1%      |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2        | 1%      |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 2        | 1%      |
| Nvidia GK208B [GeForce GT 710]                                                           | 2        | 1%      |
| Nvidia GF108 [GeForce GT 730]                                                            | 2        | 1%      |
| Nvidia GF108 [GeForce GT 430]                                                            | 2        | 1%      |
| Intel HD Graphics 630                                                                    | 2        | 1%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2        | 1%      |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2        | 1%      |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                                        | 2        | 1%      |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 2        | 1%      |
| AMD RS880 [Radeon HD 4200]                                                               | 2        | 1%      |
| AMD Park [Mobility Radeon HD 5430]                                                       | 2        | 1%      |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                               | 2        | 1%      |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 2        | 1%      |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2        | 1%      |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                                         | 2        | 1%      |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2        | 1%      |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2        | 1%      |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 2        | 1%      |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1        | 0.5%    |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 1        | 0.5%    |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 1        | 0.5%    |
| Nvidia TU104 [GeForce RTX 2080]                                                          | 1        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 64       | 34.59%  |
| 1 x Nvidia     | 55       | 29.73%  |
| 1 x Intel      | 54       | 29.19%  |
| 2 x AMD        | 4        | 2.16%   |
| 2 x Nvidia     | 3        | 1.62%   |
| Intel + Nvidia | 2        | 1.08%   |
| Intel + AMD    | 2        | 1.08%   |
| AMD + Nvidia   | 1        | 0.54%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 149      | 80.54%  |
| Proprietary | 34       | 18.38%  |
| Unknown     | 2        | 1.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 61       | 32.28%  |
| 1.01-2.0   | 30       | 15.87%  |
| 0.51-1.0   | 26       | 13.76%  |
| 3.01-4.0   | 24       | 12.7%   |
| 7.01-8.0   | 15       | 7.94%   |
| 0.01-0.5   | 11       | 5.82%   |
| 5.01-6.0   | 10       | 5.29%   |
| 8.01-16.0  | 7        | 3.7%    |
| 2.01-3.0   | 5        | 2.65%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 33       | 16.58%  |
| Goldstar             | 21       | 10.55%  |
| Dell                 | 21       | 10.55%  |
| Hewlett-Packard      | 20       | 10.05%  |
| Acer                 | 17       | 8.54%   |
| AOC                  | 12       | 6.03%   |
| Philips              | 11       | 5.53%   |
| BenQ                 | 7        | 3.52%   |
| Lenovo               | 6        | 3.02%   |
| Ancor Communications | 6        | 3.02%   |
| LG Electronics       | 4        | 2.01%   |
| Vizio                | 3        | 1.51%   |
| Unknown              | 3        | 1.51%   |
| AUS                  | 3        | 1.51%   |
| Sony                 | 2        | 1.01%   |
| Sharp                | 2        | 1.01%   |
| NEC Computers        | 2        | 1.01%   |
| Iiyama               | 2        | 1.01%   |
| HPN                  | 2        | 1.01%   |
| Fujitsu Siemens      | 2        | 1.01%   |
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
| Gateway              | 1        | 0.5%    |
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
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3        | 1.42%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                       | 2        | 0.94%   |
| Hewlett-Packard 2010 HWP2889 1600x900 443x250mm 20.0-inch             | 2        | 0.94%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 2        | 0.94%   |
| Goldstar L1753T GSM4434 1280x1024 338x270mm 17.0-inch                 | 2        | 0.94%   |
| Goldstar 22EN33 GSM597C 1920x1080 480x270mm 21.7-inch                 | 2        | 0.94%   |
| Dell 1704FPV DEL3016 1280x1024 338x270mm 17.0-inch                    | 2        | 0.94%   |
| BenQ EL2870U BNQ7949 3840x2160 621x341mm 27.9-inch                    | 2        | 0.94%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 2        | 0.94%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 2        | 0.94%   |
| ___ LCDTV16 ___9000 1360x768                                          | 1        | 0.47%   |
| Vizio VA26LHDTV10T VIZ0035 1360x768 576x324mm 26.0-inch               | 1        | 0.47%   |
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
| Sony TV *00 SNY8004 3840x2160 1085x610mm 49.0-inch                    | 1        | 0.47%   |
| Sharp HDMI SHP108E 1360x768 820x460mm 37.0-inch                       | 1        | 0.47%   |
| Sharp HDMI SHP1048 1920x1080 890x500mm 40.2-inch                      | 1        | 0.47%   |
| Samsung Electronics T24D391 SAM0B72 1920x1080 521x293mm 23.5-inch     | 1        | 0.47%   |
| Samsung Electronics T22C310 SAM0AE9 1920x1080 480x270mm 21.7-inch     | 1        | 0.47%   |
| Samsung Electronics SyncMaster SAM0580 1280x1024 376x301mm 19.0-inch  | 1        | 0.47%   |
| Samsung Electronics SyncMaster SAM0473 2048x1152 510x287mm 23.0-inch  | 1        | 0.47%   |
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
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch     | 1        | 0.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 80       | 39.8%   |
| 1680x1050 (WSXGA+) | 19       | 9.45%   |
| 3840x2160 (4K)     | 18       | 8.96%   |
| 2560x1440 (QHD)    | 14       | 6.97%   |
| 1366x768 (WXGA)    | 13       | 6.47%   |
| 1280x1024 (SXGA)   | 12       | 5.97%   |
| 1600x900 (HD+)     | 8        | 3.98%   |
| 1440x900 (WXGA+)   | 7        | 3.48%   |
| 3840x1080          | 5        | 2.49%   |
| 1920x1200 (WUXGA)  | 5        | 2.49%   |
| 1360x768           | 5        | 2.49%   |
| Unknown            | 5        | 2.49%   |
| 3440x1440          | 3        | 1.49%   |
| 5120x1440          | 2        | 1%      |
| 2560x1080          | 2        | 1%      |
| 7680x2160          | 1        | 0.5%    |
| 3840x1200          | 1        | 0.5%    |
| 2048x1152          | 1        | 0.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 30       | 15.23%  |
| 24      | 23       | 11.68%  |
| 23      | 21       | 10.66%  |
| 21      | 19       | 9.64%   |
| 27      | 17       | 8.63%   |
| 22      | 15       | 7.61%   |
| 18      | 10       | 5.08%   |
| 31      | 9        | 4.57%   |
| 19      | 9        | 4.57%   |
| 17      | 8        | 4.06%   |
| 20      | 6        | 3.05%   |
| 32      | 5        | 2.54%   |
| 34      | 4        | 2.03%   |
| 36      | 3        | 1.52%   |
| 84      | 2        | 1.02%   |
| 72      | 2        | 1.02%   |
| 48      | 2        | 1.02%   |
| 15      | 2        | 1.02%   |
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
| 501-600     | 58       | 30.37%  |
| 401-500     | 53       | 27.75%  |
| Unknown     | 30       | 15.71%  |
| 701-800     | 11       | 5.76%   |
| 601-700     | 11       | 5.76%   |
| 301-350     | 9        | 4.71%   |
| 1001-1500   | 6        | 3.14%   |
| 351-400     | 5        | 2.62%   |
| 1501-2000   | 4        | 2.09%   |
| 801-900     | 3        | 1.57%   |
| 901-1000    | 1        | 0.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 109      | 59.24%  |
| 16/10   | 30       | 16.3%   |
| Unknown | 26       | 14.13%  |
| 5/4     | 10       | 5.43%   |
| 21/9    | 5        | 2.72%   |
| 32/9    | 2        | 1.09%   |
| 6/5     | 1        | 0.54%   |
| 3/2     | 1        | 0.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 58       | 30.21%  |
| Unknown        | 30       | 15.63%  |
| 151-200        | 21       | 10.94%  |
| 351-500        | 18       | 9.38%   |
| 301-350        | 17       | 8.85%   |
| 141-150        | 15       | 7.81%   |
| 251-300        | 13       | 6.77%   |
| 501-1000       | 9        | 4.69%   |
| More than 1000 | 8        | 4.17%   |
| 131-140        | 1        | 0.52%   |
| 101-110        | 1        | 0.52%   |
| 91-100         | 1        | 0.52%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 110      | 57.89%  |
| 101-120 | 31       | 16.32%  |
| Unknown | 30       | 15.79%  |
| 1-50    | 10       | 5.26%   |
| 121-160 | 8        | 4.21%   |
| 161-240 | 1        | 0.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 152      | 81.72%  |
| 2     | 28       | 15.05%  |
| 3     | 4        | 2.15%   |
| 0     | 2        | 1.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 113      | 41.54%  |
| Intel                             | 79       | 29.04%  |
| Qualcomm Atheros                  | 11       | 4.04%   |
| Broadcom                          | 11       | 4.04%   |
| Ralink Technology                 | 8        | 2.94%   |
| Nvidia                            | 7        | 2.57%   |
| Samsung Electronics               | 6        | 2.21%   |
| TP-Link                           | 5        | 1.84%   |
| Xiaomi                            | 3        | 1.1%    |
| Ralink                            | 3        | 1.1%    |
| Marvell Technology Group          | 3        | 1.1%    |
| Broadcom Limited                  | 3        | 1.1%    |
| Microsoft                         | 2        | 0.74%   |
| Linksys                           | 2        | 0.74%   |
| D-Link System                     | 2        | 0.74%   |
| ZyXEL Communications              | 1        | 0.37%   |
| vivo                              | 1        | 0.37%   |
| TRENDnet                          | 1        | 0.37%   |
| Sundance Technology Inc / IC Plus | 1        | 0.37%   |
| Qualcomm Atheros Communications   | 1        | 0.37%   |
| Motorola PCS                      | 1        | 0.37%   |
| LG Electronics                    | 1        | 0.37%   |
| Huawei Technologies               | 1        | 0.37%   |
| Exar                              | 1        | 0.37%   |
| AVM                               | 1        | 0.37%   |
| Aquantia                          | 1        | 0.37%   |
| AirTies Wireless Networks         | 1        | 0.37%   |
| Accton Technology                 | 1        | 0.37%   |
| AboCom Systems                    | 1        | 0.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 85       | 27.6%   |
| Intel Wi-Fi 6 AX200                                               | 12       | 3.9%    |
| Realtek RTL8125 2.5GbE Controller                                 | 10       | 3.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10       | 3.25%   |
| Intel I211 Gigabit Network Connection                             | 9        | 2.92%   |
| Intel Ethernet Connection (2) I219-V                              | 8        | 2.6%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7        | 2.27%   |
| Realtek 802.11ac NIC                                              | 6        | 1.95%   |
| Intel Ethernet Controller I225-V                                  | 6        | 1.95%   |
| Ralink MT7601U Wireless Adapter                                   | 5        | 1.62%   |
| Nvidia MCP61 Ethernet                                             | 5        | 1.62%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4        | 1.3%    |
| Intel Ethernet Connection (7) I219-V                              | 4        | 1.3%    |
| Intel 82579V Gigabit Network Connection                           | 4        | 1.3%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3        | 0.97%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3        | 0.97%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3        | 0.97%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 3        | 0.97%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3        | 0.97%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 0.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 0.97%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 0.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.65%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2        | 0.65%   |
| Ralink RT5372 Wireless Adapter                                    | 2        | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.65%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 2        | 0.65%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 0.65%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.65%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2        | 0.65%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2        | 0.65%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 0.65%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 0.65%   |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W] | 2        | 0.65%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                            | 2        | 0.65%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2        | 0.65%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 2        | 0.65%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]      | 1        | 0.32%   |
| vivo 1820                                                         | 1        | 0.32%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 33       | 32.35%  |
| Realtek Semiconductor           | 24       | 23.53%  |
| Ralink Technology               | 8        | 7.84%   |
| Broadcom                        | 8        | 7.84%   |
| TP-Link                         | 5        | 4.9%    |
| Ralink                          | 3        | 2.94%   |
| Qualcomm Atheros                | 3        | 2.94%   |
| Broadcom Limited                | 3        | 2.94%   |
| Microsoft                       | 2        | 1.96%   |
| Linksys                         | 2        | 1.96%   |
| D-Link System                   | 2        | 1.96%   |
| ZyXEL Communications            | 1        | 0.98%   |
| TRENDnet                        | 1        | 0.98%   |
| Qualcomm Atheros Communications | 1        | 0.98%   |
| Marvell Technology Group        | 1        | 0.98%   |
| LG Electronics                  | 1        | 0.98%   |
| AVM                             | 1        | 0.98%   |
| AirTies Wireless Networks       | 1        | 0.98%   |
| Accton Technology               | 1        | 0.98%   |
| AboCom Systems                  | 1        | 0.98%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                               | 12       | 11.65%  |
| Realtek 802.11ac NIC                                                              | 6        | 5.83%   |
| Ralink MT7601U Wireless Adapter                                                   | 5        | 4.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                            | 4        | 3.88%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                | 3        | 2.91%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                               | 3        | 2.91%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                  | 3        | 2.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                          | 2        | 1.94%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                           | 2        | 1.94%   |
| Ralink RT5372 Wireless Adapter                                                    | 2        | 1.94%   |
| Intel Comet Lake PCH CNVi WiFi                                                    | 2        | 1.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                                   | 2        | 1.94%   |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W]                 | 2        | 1.94%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                            | 2        | 1.94%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                | 2        | 1.94%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                                | 2        | 1.94%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]                      | 1        | 0.97%   |
| TRENDnet TEW-648UBM 802.11n 150Mbps Micro Wireless N Adapter [Realtek RTL8188CUS] | 1        | 0.97%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                       | 1        | 0.97%   |
| TP-Link Archer T4U ver.3                                                          | 1        | 0.97%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                        | 1        | 0.97%   |
| TP-Link 802.11ac WLAN Adapter                                                     | 1        | 0.97%   |
| TP-Link 802.11ac NIC                                                              | 1        | 0.97%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                          | 1        | 0.97%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                          | 1        | 0.97%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                          | 1        | 0.97%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                       | 1        | 0.97%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                             | 1        | 0.97%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                           | 1        | 0.97%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                        | 1        | 0.97%   |
| Realtek RTL8187 Wireless Adapter                                                  | 1        | 0.97%   |
| Realtek 802.11n WLAN Adapter                                                      | 1        | 0.97%   |
| Ralink RT2870/RT3070 Wireless Adapter                                             | 1        | 0.97%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                         | 1        | 0.97%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                         | 1        | 0.97%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                         | 1        | 0.97%   |
| Qualcomm Atheros AR9271 802.11n                                                   | 1        | 0.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                  | 1        | 0.97%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                    | 1        | 0.97%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]               | 1        | 0.97%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 104      | 52.26%  |
| Intel                             | 63       | 31.66%  |
| Qualcomm Atheros                  | 8        | 4.02%   |
| Nvidia                            | 7        | 3.52%   |
| Broadcom                          | 4        | 2.01%   |
| Xiaomi                            | 3        | 1.51%   |
| Samsung Electronics               | 3        | 1.51%   |
| Marvell Technology Group          | 2        | 1.01%   |
| vivo                              | 1        | 0.5%    |
| Sundance Technology Inc / IC Plus | 1        | 0.5%    |
| Motorola PCS                      | 1        | 0.5%    |
| Huawei Technologies               | 1        | 0.5%    |
| Aquantia                          | 1        | 0.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 85       | 42.29%  |
| Realtek RTL8125 2.5GbE Controller                                          | 10       | 4.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 10       | 4.98%   |
| Intel I211 Gigabit Network Connection                                      | 9        | 4.48%   |
| Intel Ethernet Connection (2) I219-V                                       | 8        | 3.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 7        | 3.48%   |
| Intel Ethernet Controller I225-V                                           | 6        | 2.99%   |
| Nvidia MCP61 Ethernet                                                      | 5        | 2.49%   |
| Intel Ethernet Connection (7) I219-V                                       | 4        | 1.99%   |
| Intel 82579V Gigabit Network Connection                                    | 4        | 1.99%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 3        | 1.49%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 3        | 1.49%   |
| Intel Ethernet Connection I217-LM                                          | 3        | 1.49%   |
| Intel 82574L Gigabit Network Connection                                    | 3        | 1.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 2        | 1%      |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                    | 2        | 1%      |
| Intel Ethernet Connection (7) I219-LM                                      | 2        | 1%      |
| Intel Ethernet Connection (2) I219-LM                                      | 2        | 1%      |
| Intel Ethernet Connection (11) I219-V                                      | 2        | 1%      |
| Intel 82578DM Gigabit Network Connection                                   | 2        | 1%      |
| Intel 82567LM-3 Gigabit Network Connection                                 | 2        | 1%      |
| vivo 1820                                                                  | 1        | 0.5%    |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 1        | 0.5%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 1        | 0.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 1        | 0.5%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 1        | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 1        | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 1        | 0.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 1        | 0.5%    |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                              | 1        | 0.5%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 1        | 0.5%    |
| Nvidia MCP77 Ethernet                                                      | 1        | 0.5%    |
| Nvidia MCP55 Ethernet                                                      | 1        | 0.5%    |
| Motorola PCS moto g(30)                                                    | 1        | 0.5%    |
| Intel I210 Gigabit Network Connection                                      | 1        | 0.5%    |
| Intel Ethernet Connection I217-V                                           | 1        | 0.5%    |
| Intel Ethernet Connection (2) I218-V                                       | 1        | 0.5%    |
| Intel Ethernet Connection (12) I219-V                                      | 1        | 0.5%    |
| Intel 82566DM-2 Gigabit Network Connection                                 | 1        | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 182      | 65.23%  |
| WiFi     | 93       | 33.33%  |
| Modem    | 4        | 1.43%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 132      | 74.58%  |
| WiFi     | 45       | 25.42%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 116      | 63.04%  |
| 2     | 58       | 31.52%  |
| 3     | 9        | 4.89%   |
| 0     | 1        | 0.54%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 130      | 70.27%  |
| Yes  | 55       | 29.73%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 32       | 43.84%  |
| Cambridge Silicon Radio | 17       | 23.29%  |
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
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 17       | 23.29%  |
| Intel AX200 Bluetooth                               | 11       | 15.07%  |
| Realtek Bluetooth Radio                             | 8        | 10.96%  |
| Intel Bluetooth wireless interface                  | 5        | 6.85%   |
| Intel AX210 Bluetooth                               | 5        | 6.85%   |
| Intel AX201 Bluetooth                               | 4        | 5.48%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3        | 4.11%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 2.74%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2        | 2.74%   |
| Apple Bluetooth USB Host Controller                 | 2        | 2.74%   |
| Ralink RT3290 Bluetooth                             | 1        | 1.37%   |
| Qcom Bluetooth USB                                  | 1        | 1.37%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1        | 1.37%   |
| Intel Bluetooth Device                              | 1        | 1.37%   |
| IMC Networks BCM20702A0                             | 1        | 1.37%   |
| Edimax Bluetooth Adapter                            | 1        | 1.37%   |
| Broadcom HP Portable Bumble Bee                     | 1        | 1.37%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter    | 1        | 1.37%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1        | 1.37%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1        | 1.37%   |
| ASUS BCM20702A0                                     | 1        | 1.37%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1        | 1.37%   |
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
| Intel                     | 116      | 36.83%  |
| AMD                       | 83       | 26.35%  |
| Nvidia                    | 64       | 20.32%  |
| C-Media Electronics       | 15       | 4.76%   |
| Creative Labs             | 8        | 2.54%   |
| Logitech                  | 4        | 1.27%   |
| Jieli Technology          | 2        | 0.63%   |
| Generalplus Technology    | 2        | 0.63%   |
| Focusrite-Novation        | 2        | 0.63%   |
| Corsair                   | 2        | 0.63%   |
| ASUSTek Computer          | 2        | 0.63%   |
| VIA Technologies          | 1        | 0.32%   |
| Texas Instruments         | 1        | 0.32%   |
| Tenx Technology           | 1        | 0.32%   |
| Sony                      | 1        | 0.32%   |
| Realtek Semiconductor     | 1        | 0.32%   |
| Razer USA                 | 1        | 0.32%   |
| Philips Speech Processing | 1        | 0.32%   |
| Native Instruments        | 1        | 0.32%   |
| Microsoft                 | 1        | 0.32%   |
| Micro Star International  | 1        | 0.32%   |
| JMTek                     | 1        | 0.32%   |
| iCreate Technologies      | 1        | 0.32%   |
| GN Netcom                 | 1        | 0.32%   |
| Edifier Technology        | 1        | 0.32%   |
| Creative Technology       | 1        | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 26       | 7.14%   |
| AMD Starship/Matisse HD Audio Controller                                          | 16       | 4.4%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 13       | 3.57%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 11       | 3.02%   |
| Intel Cannon Lake PCH cAVS                                                        | 10       | 2.75%   |
| AMD Family 17h/19h HD Audio Controller                                            | 10       | 2.75%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 9        | 2.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 8        | 2.2%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 8        | 2.2%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 8        | 2.2%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 8        | 2.2%    |
| Nvidia GF108 High Definition Audio Controller                                     | 7        | 1.92%   |
| Intel 200 Series PCH HD Audio                                                     | 7        | 1.92%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 7        | 1.92%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 6        | 1.65%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 6        | 1.65%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 6        | 1.65%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 6        | 1.65%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 6        | 1.65%   |
| AMD FCH Azalia Controller                                                         | 6        | 1.65%   |
| Nvidia TU106 High Definition Audio Controller                                     | 5        | 1.37%   |
| Nvidia TU104 HD Audio Controller                                                  | 5        | 1.37%   |
| Nvidia MCP61 High Definition Audio                                                | 5        | 1.37%   |
| Nvidia GP106 High Definition Audio Controller                                     | 5        | 1.37%   |
| Nvidia TU116 High Definition Audio Controller                                     | 4        | 1.1%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 4        | 1.1%    |
| Nvidia GP107GL High Definition Audio Controller                                   | 4        | 1.1%    |
| Nvidia GA102 High Definition Audio Controller                                     | 4        | 1.1%    |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 4        | 1.1%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 4        | 1.1%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 4        | 1.1%    |
| AMD Kaveri HDMI/DP Audio Controller                                               | 4        | 1.1%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 4        | 1.1%    |
| Nvidia GP108 High Definition Audio Controller                                     | 3        | 0.82%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3        | 0.82%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 3        | 0.82%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 3        | 0.82%   |
| Intel Comet Lake PCH cAVS                                                         | 3        | 0.82%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 3        | 0.82%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 3        | 0.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 8        | 23.53%  |
| Samsung Electronics | 6        | 17.65%  |
| Unknown             | 4        | 11.76%  |
| SK hynix            | 3        | 8.82%   |
| Crucial             | 2        | 5.88%   |
| Corsair             | 2        | 5.88%   |
| A-DATA Technology   | 2        | 5.88%   |
| Unknown (0x038A)    | 1        | 2.94%   |
| Ramaxel Technology  | 1        | 2.94%   |
| PNY                 | 1        | 2.94%   |
| Patriot             | 1        | 2.94%   |
| Micron Technology   | 1        | 2.94%   |
| G.Skill             | 1        | 2.94%   |
| Unknown             | 1        | 2.94%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown RAM Module 8GB DIMM DDR3 1066MT/s                | 1        | 2.86%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                     | 1        | 2.86%   |
| Unknown RAM Module 8192MB DIMM DDR3 1066MT/s             | 1        | 2.86%   |
| Unknown RAM Module 8192MB DIMM 1066MT/s                  | 1        | 2.86%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                | 1        | 2.86%   |
| Unknown (0x038A) RAM Module 4GB DIMM DDR3 1066MT/s       | 1        | 2.86%   |
| SK hynix RAM HMT42GR7BMR4C 16384MB DIMM DDR3 1066MT/s    | 1        | 2.86%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s     | 1        | 2.86%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s   | 1        | 2.86%   |
| Samsung RAM Module 8192MB Row Of Chips LPDDR4 3733MT/s   | 1        | 2.86%   |
| Samsung RAM Module 8192MB DIMM DDR4 2666MT/s             | 1        | 2.86%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s | 1        | 2.86%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s    | 1        | 2.86%   |
| Samsung RAM M393B2K70DM0 16384MB DIMM DDR3 1066MT/s      | 1        | 2.86%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM 2200MT/s           | 1        | 2.86%   |
| Ramaxel RAM RMUA5090KB78HAF2133 8GB DIMM DDR4 2133MT/s   | 1        | 2.86%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8GB DIMM DDR4 3600MT/s      | 1        | 2.86%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3266MT/s       | 1        | 2.86%   |
| Micron RAM Module 16384MB DIMM DDR3 1600MT/s             | 1        | 2.86%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s        | 1        | 2.86%   |
| Kingston RAM KHX1600C9D3/8G 8GB DIMM DDR3 1600MT/s       | 1        | 2.86%   |
| Kingston RAM KF3600C18D4/32GX 32GB DIMM DDR4 3600MT/s    | 1        | 2.86%   |
| Kingston RAM KF3600C18D4/16GX 16GB DIMM DDR4 3600MT/s    | 1        | 2.86%   |
| Kingston RAM ACR26D4U9S8MH-8 8GB DIMM DDR4 2667MT/s      | 1        | 2.86%   |
| Kingston RAM 9905783-049.A01G 16384MB DIMM 4800MT/s      | 1        | 2.86%   |
| Kingston RAM 9905625-030.A00G 8GB DIMM DDR4 2133MT/s     | 1        | 2.86%   |
| Kingston RAM 9905471-015.A00LF 4GB DIMM DDR3 1600MT/s    | 1        | 2.86%   |
| G.Skill RAM F3-14900CL9-2GBXM 2048MB DIMM DDR3 1600MT/s  | 1        | 2.86%   |
| Crucial RAM CT8G4DFD824A.C16FF 8GB DIMM DDR4 2733MT/s    | 1        | 2.86%   |
| Crucial RAM CT25664BA1339.C8FE 2048MB DIMM DDR3 1333MT/s | 1        | 2.86%   |
| Corsair RAM CMX8GX3M1A1600C11 8GB DIMM DDR3 1600MT/s     | 1        | 2.86%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s     | 1        | 2.86%   |
| A-DATA RAM Module 4096MB DIMM DDR4 2400MT/s              | 1        | 2.86%   |
| A-DATA RAM Module 16384MB DIMM DDR4 2667MT/s             | 1        | 2.86%   |
| Unknown                                                  | 1        | 2.86%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 11       | 42.31%  |
| DDR4    | 10       | 38.46%  |
| Unknown | 3        | 11.54%  |
| SDRAM   | 1        | 3.85%   |
| LPDDR4  | 1        | 3.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 23       | 88.46%  |
| SODIMM       | 2        | 7.69%   |
| Row Of Chips | 1        | 3.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 13       | 46.43%  |
| 4096  | 7        | 25%     |
| 16384 | 5        | 17.86%  |
| 32768 | 2        | 7.14%   |
| 2048  | 1        | 3.57%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 7        | 23.33%  |
| 1066  | 4        | 13.33%  |
| 3600  | 3        | 10%     |
| 2667  | 2        | 6.67%   |
| 1333  | 2        | 6.67%   |
| 4800  | 1        | 3.33%   |
| 3733  | 1        | 3.33%   |
| 3400  | 1        | 3.33%   |
| 3266  | 1        | 3.33%   |
| 2800  | 1        | 3.33%   |
| 2733  | 1        | 3.33%   |
| 2666  | 1        | 3.33%   |
| 2400  | 1        | 3.33%   |
| 2200  | 1        | 3.33%   |
| 2133  | 1        | 3.33%   |
| 1800  | 1        | 3.33%   |
| 800   | 1        | 3.33%   |

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
| Microdia                      | 4        | 12.12%  |
| Microsoft                     | 3        | 9.09%   |
| Chicony Electronics           | 2        | 6.06%   |
| Apple                         | 2        | 6.06%   |
| Z-Star Microelectronics       | 1        | 3.03%   |
| SunplusIT                     | 1        | 3.03%   |
| Sunplus Innovation Technology | 1        | 3.03%   |
| Silicon Motion                | 1        | 3.03%   |
| Razer USA                     | 1        | 3.03%   |
| Philips (or NXP)              | 1        | 3.03%   |
| OmniVision Technologies       | 1        | 3.03%   |
| KYE Systems (Mouse Systems)   | 1        | 3.03%   |
| Hopewin Electronic Material   | 1        | 3.03%   |
| HD USB Camera                 | 1        | 3.03%   |
| Arkmicro Technologies         | 1        | 3.03%   |
| ANYKA                         | 1        | 3.03%   |
| Alcor Micro                   | 1        | 3.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Microsoft LifeCam HD-3000                         | 2        | 6.06%   |
| Logitech HD Webcam C615                           | 2        | 6.06%   |
| Chicony HP High Definition 1MP Webcam             | 2        | 6.06%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                   | 2        | 6.06%   |
| Z-Star Vega USB 2.0 Camera                        | 1        | 3.03%   |
| SunplusIT MTD camera                              | 1        | 3.03%   |
| Sunplus FHD Camera Microphone                     | 1        | 3.03%   |
| Silicon Motion Silicon Motion Camera              | 1        | 3.03%   |
| Razer USA Razer Kiyo Pro                          | 1        | 3.03%   |
| Philips (or NXP) SPZ2500                          | 1        | 3.03%   |
| OmniVision Monitor Webcam                         | 1        | 3.03%   |
| Microsoft LifeCam VX-800                          | 1        | 3.03%   |
| Microdia USB 2.0 Camera                           | 1        | 3.03%   |
| Microdia REDRAGON Live Camera Audio               | 1        | 3.03%   |
| Microdia Integrated Camera                        | 1        | 3.03%   |
| Microdia Camera                                   | 1        | 3.03%   |
| Logitech Webcam C925e                             | 1        | 3.03%   |
| Logitech Webcam C270                              | 1        | 3.03%   |
| Logitech QuickCam Communicate Deluxe              | 1        | 3.03%   |
| Logitech HD Webcam C910                           | 1        | 3.03%   |
| Logitech C922 Pro Stream Webcam                   | 1        | 3.03%   |
| Logitech BRIO 4K Stream Edition                   | 1        | 3.03%   |
| Logitech B525 HD Webcam                           | 1        | 3.03%   |
| KYE Systems (Mouse Systems) iSlim 1300            | 1        | 3.03%   |
| Hopewin Electronic Material Integrated RGB Camera | 1        | 3.03%   |
| HD USB Camera HD USB Camera                       | 1        | 3.03%   |
| Arkmicro USB2.0 PC CAMERA                         | 1        | 3.03%   |
| ANYKA V380 FHD Camera                             | 1        | 3.03%   |
| Alcor Micro USB 2.0 PC Camera                     | 1        | 3.03%   |

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
| 0     | 158      | 84.49%  |
| 1     | 24       | 12.83%  |
| 2     | 4        | 2.14%   |
| 4     | 1        | 0.53%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 15       | 48.39%  |
| Sound                    | 4        | 12.9%   |
| Graphics card            | 3        | 9.68%   |
| Bluetooth                | 3        | 9.68%   |
| Unassigned class         | 2        | 6.45%   |
| Storage/ide              | 1        | 3.23%   |
| Multimedia controller    | 1        | 3.23%   |
| Fingerprint reader       | 1        | 3.23%   |
| Communication controller | 1        | 3.23%   |

