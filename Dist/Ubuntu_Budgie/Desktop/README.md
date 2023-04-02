Ubuntu Budgie - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu Budgie.

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

Total: 270

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek    | PRIME B450M-GAMING/BR       | [2536217d87](https://linux-hardware.org/?probe=2536217d87) | Mar 23, 2023 |
| HP         | 83E1                        | [86061f121d](https://linux-hardware.org/?probe=86061f121d) | Mar 08, 2023 |
| ASUSTek    | Z87-PRO                     | [7997191f44](https://linux-hardware.org/?probe=7997191f44) | Feb 28, 2023 |
| ASUSTek    | Z87-PRO                     | [9a6bc5f3af](https://linux-hardware.org/?probe=9a6bc5f3af) | Feb 28, 2023 |
| MSI        | Z170-A PRO                  | [a5a54422a0](https://linux-hardware.org/?probe=a5a54422a0) | Feb 23, 2023 |
| MSI        | X99S SLI PLUS               | [8c6fb84b12](https://linux-hardware.org/?probe=8c6fb84b12) | Feb 09, 2023 |
| ASRock     | Z390 Phantom Gaming 4-IB    | [3a9937a61b](https://linux-hardware.org/?probe=3a9937a61b) | Feb 09, 2023 |
| ASUSTek    | ROG STRIX X570-I GAMING     | [866e97ab12](https://linux-hardware.org/?probe=866e97ab12) | Feb 03, 2023 |
| ASRock     | FM2A88X Extreme4+           | [9f812fe2a7](https://linux-hardware.org/?probe=9f812fe2a7) | Feb 02, 2023 |
| Fujitsu    | D3183-A1 S26361-D3183-A1    | [bfb86ee660](https://linux-hardware.org/?probe=bfb86ee660) | Jan 29, 2023 |
| Lenovo     | 36F7 SDK0J40700 WIN 3258... | [831fd897ec](https://linux-hardware.org/?probe=831fd897ec) | Jan 25, 2023 |
| Lenovo     | ThinkStation C20 4263BA7    | [38ff99d952](https://linux-hardware.org/?probe=38ff99d952) | Jan 10, 2023 |
| ASUSTek    | PRIME B560M-A               | [f560abfd7f](https://linux-hardware.org/?probe=f560abfd7f) | Jan 03, 2023 |
| ASUSTek    | M52AD_M12AD_A_F_K31AD       | [de65990b87](https://linux-hardware.org/?probe=de65990b87) | Jan 01, 2023 |
| Gigabyte   | Z170X-Gaming 3              | [1773b79334](https://linux-hardware.org/?probe=1773b79334) | Dec 17, 2022 |
| ASUSTek    | ROG STRIX X570-I GAMING     | [e95599a479](https://linux-hardware.org/?probe=e95599a479) | Dec 09, 2022 |
| ASUSTek    | PRIME B450M-A               | [c40fd27f39](https://linux-hardware.org/?probe=c40fd27f39) | Dec 05, 2022 |
| Fujitsu    | D3222-A1 S26361-D3222-A1    | [3272263f3b](https://linux-hardware.org/?probe=3272263f3b) | Dec 04, 2022 |
| Fujitsu    | D3348-B2 S26361-D3348-B2    | [4568e83912](https://linux-hardware.org/?probe=4568e83912) | Dec 03, 2022 |
| Fujitsu    | D3348-B2 S26361-D3348-B2    | [2047a872cb](https://linux-hardware.org/?probe=2047a872cb) | Dec 03, 2022 |
| Acer       | Aspire XC-830               | [42efe1dfdf](https://linux-hardware.org/?probe=42efe1dfdf) | Dec 02, 2022 |
| Fujitsu    | D3348-B2 S26361-D3348-B2    | [eabfad66da](https://linux-hardware.org/?probe=eabfad66da) | Nov 22, 2022 |
| Gigabyte   | H97M-D3H                    | [4e0102dff6](https://linux-hardware.org/?probe=4e0102dff6) | Nov 20, 2022 |
| Dell       | 0RW199                      | [2a2fa5baf8](https://linux-hardware.org/?probe=2a2fa5baf8) | Nov 20, 2022 |
| MSI        | B550M PRO-VDH WIFI          | [afb716fb12](https://linux-hardware.org/?probe=afb716fb12) | Nov 18, 2022 |
| Dell       | 0C27VV A01                  | [ed46beadef](https://linux-hardware.org/?probe=ed46beadef) | Oct 30, 2022 |
| MSI        | B450-A PRO MAX              | [0e8db93a43](https://linux-hardware.org/?probe=0e8db93a43) | Oct 30, 2022 |
| Dell       | 0C27VV A01                  | [23c855f88b](https://linux-hardware.org/?probe=23c855f88b) | Oct 17, 2022 |
| Dell       | 0C27VV A01                  | [ebe65ec5fa](https://linux-hardware.org/?probe=ebe65ec5fa) | Oct 17, 2022 |
| MSI        | H67MA-E35                   | [d4f5628033](https://linux-hardware.org/?probe=d4f5628033) | Oct 11, 2022 |
| Gigabyte   | M68MT-S2                    | [55db3c3775](https://linux-hardware.org/?probe=55db3c3775) | Sep 27, 2022 |
| Gigabyte   | X570 I AORUS PRO WIFI       | [293e528545](https://linux-hardware.org/?probe=293e528545) | Sep 21, 2022 |
| Gigabyte   | B75M-D3P                    | [da53115e6b](https://linux-hardware.org/?probe=da53115e6b) | Sep 15, 2022 |
| Gigabyte   | M68MT-S2                    | [1a5358a3c1](https://linux-hardware.org/?probe=1a5358a3c1) | Sep 14, 2022 |
| Gigabyte   | X570S AORUS PRO AX          | [f42f75038e](https://linux-hardware.org/?probe=f42f75038e) | Sep 03, 2022 |
| Intel      | DP55WB AAE64798-206         | [548332086b](https://linux-hardware.org/?probe=548332086b) | Sep 02, 2022 |
| ASUSTek    | A88X-PRO                    | [922554664a](https://linux-hardware.org/?probe=922554664a) | Aug 25, 2022 |
| HP         | 3397                        | [335f59c96f](https://linux-hardware.org/?probe=335f59c96f) | Aug 22, 2022 |
| Intel      | X79M-S                      | [49a7d62fe8](https://linux-hardware.org/?probe=49a7d62fe8) | Aug 18, 2022 |
| ASUSTek    | Berkeley                    | [e9998910ee](https://linux-hardware.org/?probe=e9998910ee) | Aug 17, 2022 |
| HP         | 828A                        | [f42b1efd1e](https://linux-hardware.org/?probe=f42b1efd1e) | Aug 17, 2022 |
| Biostar    | A960D+V3                    | [83f7f840b7](https://linux-hardware.org/?probe=83f7f840b7) | Aug 15, 2022 |
| ASRock     | A300M-STX                   | [a6aba67197](https://linux-hardware.org/?probe=a6aba67197) | Aug 02, 2022 |
| ASRock     | A300M-STX                   | [fae724727b](https://linux-hardware.org/?probe=fae724727b) | Aug 02, 2022 |
| Intel      | STK1A32SC H95551-301        | [ea91c7805d](https://linux-hardware.org/?probe=ea91c7805d) | Jul 22, 2022 |
| Gigabyte   | GA-890GPA-UD3H              | [f6faa2d944](https://linux-hardware.org/?probe=f6faa2d944) | Jun 25, 2022 |
| HP         | 212B                        | [a163af0cb5](https://linux-hardware.org/?probe=a163af0cb5) | Jun 21, 2022 |
| Gigabyte   | B75M-D3H                    | [da04a03393](https://linux-hardware.org/?probe=da04a03393) | Jun 04, 2022 |
| Gigabyte   | GA-890GPA-UD3H              | [3195007eb2](https://linux-hardware.org/?probe=3195007eb2) | May 30, 2022 |
| Gigabyte   | F2A78M-HD2                  | [fc9dd3db05](https://linux-hardware.org/?probe=fc9dd3db05) | May 26, 2022 |
| ASUSTek    | PRIME B560M-A               | [7b393b3933](https://linux-hardware.org/?probe=7b393b3933) | May 24, 2022 |
| MSI        | X370 GAMING PRO CARBON      | [9acb45109f](https://linux-hardware.org/?probe=9acb45109f) | May 21, 2022 |
| Gigabyte   | B75M-D3H                    | [b9437261b7](https://linux-hardware.org/?probe=b9437261b7) | May 10, 2022 |
| Gigabyte   | B450 I AORUS PRO WIFI-CF    | [4ab84df25d](https://linux-hardware.org/?probe=4ab84df25d) | May 10, 2022 |
| HP         | 1825                        | [fe93966c1c](https://linux-hardware.org/?probe=fe93966c1c) | May 09, 2022 |
| ASUSTek    | P8Z77-V LX                  | [9f241088c2](https://linux-hardware.org/?probe=9f241088c2) | May 06, 2022 |
| ASUSTek    | P8Z77-V LX                  | [37fa300c26](https://linux-hardware.org/?probe=37fa300c26) | Apr 18, 2022 |
| Gigabyte   | B550 AORUS ELITE AX V2      | [e2cbc23977](https://linux-hardware.org/?probe=e2cbc23977) | Apr 12, 2022 |
| MSI        | H81M-E33                    | [33547f6d85](https://linux-hardware.org/?probe=33547f6d85) | Apr 11, 2022 |
| Gigabyte   | X570 UD                     | [860fedd7f0](https://linux-hardware.org/?probe=860fedd7f0) | Apr 01, 2022 |
| Gigabyte   | 970A-DS3P                   | [eaae14de4f](https://linux-hardware.org/?probe=eaae14de4f) | Mar 05, 2022 |
| Gigabyte   | B560 DS3H AC-Y1             | [5be284f90d](https://linux-hardware.org/?probe=5be284f90d) | Feb 26, 2022 |
| ASUSTek    | ROG STRIX B550-E GAMING     | [7fa418eb00](https://linux-hardware.org/?probe=7fa418eb00) | Feb 25, 2022 |
| ASRock     | 970 Pro3 R2.0               | [9b8714532b](https://linux-hardware.org/?probe=9b8714532b) | Feb 20, 2022 |
| Dell       | 0RW199                      | [5cf70558c8](https://linux-hardware.org/?probe=5cf70558c8) | Feb 14, 2022 |
| ASUSTek    | M4A87TD/USB3                | [88768afd55](https://linux-hardware.org/?probe=88768afd55) | Feb 10, 2022 |
| ASRock     | B550 Phantom Gaming-ITX/... | [6f4c9d5553](https://linux-hardware.org/?probe=6f4c9d5553) | Jan 27, 2022 |
| Gigabyte   | 970A-DS3P                   | [b96e414ae9](https://linux-hardware.org/?probe=b96e414ae9) | Jan 21, 2022 |
| Gigabyte   | 970A-DS3P                   | [96047ce382](https://linux-hardware.org/?probe=96047ce382) | Jan 19, 2022 |
| ASUSTek    | P5KPL-AM SE                 | [e4d4e112f7](https://linux-hardware.org/?probe=e4d4e112f7) | Jan 13, 2022 |
| ASRock     | 4X4-4000 Series             | [172d5b0abc](https://linux-hardware.org/?probe=172d5b0abc) | Jan 12, 2022 |
| ASUSTek    | H81M-C                      | [f0e03ffaed](https://linux-hardware.org/?probe=f0e03ffaed) | Dec 22, 2021 |
| Lenovo     | 36F7 SDK0J40700 WIN 3258... | [ddf55561ad](https://linux-hardware.org/?probe=ddf55561ad) | Dec 21, 2021 |
| Dell       | 0XPDFK A01                  | [8e1c093fb8](https://linux-hardware.org/?probe=8e1c093fb8) | Dec 20, 2021 |
| Dell       | 0XPDFK A01                  | [7eabc884a6](https://linux-hardware.org/?probe=7eabc884a6) | Dec 19, 2021 |
| Lenovo     | 36F7 SDK0J40700 WIN 3258... | [d416ec7878](https://linux-hardware.org/?probe=d416ec7878) | Dec 17, 2021 |
| Dell       | 0XPDFK A01                  | [2aaaff47a4](https://linux-hardware.org/?probe=2aaaff47a4) | Dec 17, 2021 |
| ASUSTek    | PRIME B360M-A               | [d34989fcaa](https://linux-hardware.org/?probe=d34989fcaa) | Dec 16, 2021 |
| ASUSTek    | PRIME B360M-A               | [7587f8f78a](https://linux-hardware.org/?probe=7587f8f78a) | Dec 16, 2021 |
| ASRock     | H61M-HVS                    | [bd9653afdd](https://linux-hardware.org/?probe=bd9653afdd) | Dec 15, 2021 |
| ASRock     | Z370M Pro4                  | [ade1f1db1a](https://linux-hardware.org/?probe=ade1f1db1a) | Dec 07, 2021 |
| Intel      | DP55WB AAE64798-206         | [6e77546d03](https://linux-hardware.org/?probe=6e77546d03) | Dec 06, 2021 |
| ASRock     | 970M Pro3                   | [126c160ef3](https://linux-hardware.org/?probe=126c160ef3) | Dec 04, 2021 |
| Dell       | 0Y2MRG A00                  | [945995abf6](https://linux-hardware.org/?probe=945995abf6) | Dec 02, 2021 |
| Dell       | 0Y2MRG A00                  | [35a82530fb](https://linux-hardware.org/?probe=35a82530fb) | Dec 02, 2021 |
| Pegatron   | IPI43-TTM                   | [3cea520e1f](https://linux-hardware.org/?probe=3cea520e1f) | Nov 29, 2021 |
| Pegatron   | IPI43-TTM                   | [3fbd626bf6](https://linux-hardware.org/?probe=3fbd626bf6) | Nov 27, 2021 |
| Pegatron   | IPI43-TTM                   | [ba184983ea](https://linux-hardware.org/?probe=ba184983ea) | Nov 27, 2021 |
| HP         | 0A5Ch                       | [4858eb5c73](https://linux-hardware.org/?probe=4858eb5c73) | Nov 21, 2021 |
| Gigabyte   | B560M AORUS ELITE           | [b397fce5b8](https://linux-hardware.org/?probe=b397fce5b8) | Nov 20, 2021 |
| ASUSTek    | Pro WS 565-ACE              | [61f2f6aeab](https://linux-hardware.org/?probe=61f2f6aeab) | Nov 19, 2021 |
| Lenovo     | SDK0J40700 WIN              | [f18f314bc7](https://linux-hardware.org/?probe=f18f314bc7) | Nov 01, 2021 |
| Gigabyte   | H410M H V3                  | [6a3a81abd6](https://linux-hardware.org/?probe=6a3a81abd6) | Oct 22, 2021 |
| Gigabyte   | H410M H V3                  | [2f0f49590b](https://linux-hardware.org/?probe=2f0f49590b) | Oct 22, 2021 |
| MSI        | X370 GAMING PRO CARBON      | [cc51204b2c](https://linux-hardware.org/?probe=cc51204b2c) | Oct 20, 2021 |
| HP         | 0A5Ch                       | [8d102a03f6](https://linux-hardware.org/?probe=8d102a03f6) | Oct 19, 2021 |
| HP         | 0A5Ch                       | [139efd1a3d](https://linux-hardware.org/?probe=139efd1a3d) | Oct 19, 2021 |
| Gigabyte   | AB350-Gaming 3-CF           | [4cb5912db3](https://linux-hardware.org/?probe=4cb5912db3) | Oct 15, 2021 |
| ASRock     | Z370M Pro4                  | [17c9df42cd](https://linux-hardware.org/?probe=17c9df42cd) | Sep 07, 2021 |
| ASRock     | Z370M Pro4                  | [01d203a7af](https://linux-hardware.org/?probe=01d203a7af) | Sep 07, 2021 |
| ASRock     | H61M-VG3                    | [7257c7b0bb](https://linux-hardware.org/?probe=7257c7b0bb) | Aug 20, 2021 |
| MSI        | X370 GAMING PRO CARBON      | [15b41a9b17](https://linux-hardware.org/?probe=15b41a9b17) | Aug 16, 2021 |
| MSI        | X370 GAMING PRO CARBON      | [dcbe85bfb3](https://linux-hardware.org/?probe=dcbe85bfb3) | Aug 16, 2021 |
| ASUSTek    | P7P55D                      | [c62d162396](https://linux-hardware.org/?probe=c62d162396) | Aug 02, 2021 |
| ASUSTek    | PRIME B450M-A               | [7b213037a5](https://linux-hardware.org/?probe=7b213037a5) | Jul 31, 2021 |
| ASUSTek    | P7P55D                      | [cd96dbf86a](https://linux-hardware.org/?probe=cd96dbf86a) | Jul 30, 2021 |
| ASUSTek    | ROG STRIX B550-I GAMING     | [6f7de51af1](https://linux-hardware.org/?probe=6f7de51af1) | Jul 25, 2021 |
| ASUSTek    | P7P55D                      | [b983e48d71](https://linux-hardware.org/?probe=b983e48d71) | Jul 24, 2021 |
| Gigabyte   | H110M-S2H-CF                | [18951b50fd](https://linux-hardware.org/?probe=18951b50fd) | Jul 23, 2021 |
| ASUSTek    | P7P55D                      | [2335f32be7](https://linux-hardware.org/?probe=2335f32be7) | Jul 22, 2021 |
| ASUSTek    | PRIME B450M-A               | [abea66177f](https://linux-hardware.org/?probe=abea66177f) | Jul 20, 2021 |
| Fujitsu    | D3227-A1 S26361-D3227-A1    | [157b9695ae](https://linux-hardware.org/?probe=157b9695ae) | Jul 15, 2021 |
| Gigabyte   | H110M-S2H-CF                | [e0f1466068](https://linux-hardware.org/?probe=e0f1466068) | Jul 09, 2021 |
| HP         | 1588h                       | [28a2da9b7f](https://linux-hardware.org/?probe=28a2da9b7f) | Jul 05, 2021 |
| Dell       | 048DY8 A01                  | [04c41fe4c2](https://linux-hardware.org/?probe=04c41fe4c2) | Jun 30, 2021 |
| Intel      | DB75EN AAG39650-303         | [d90efe186a](https://linux-hardware.org/?probe=d90efe186a) | Jun 25, 2021 |
| ASUSTek    | M4A87TD/USB3                | [ebcfe7dad0](https://linux-hardware.org/?probe=ebcfe7dad0) | Jun 16, 2021 |
| HP         | 1998                        | [7b400d8da6](https://linux-hardware.org/?probe=7b400d8da6) | Jun 11, 2021 |
| HP         | 1998                        | [304ce6f1c4](https://linux-hardware.org/?probe=304ce6f1c4) | Jun 02, 2021 |
| Pegatron   | IPI43-TTM                   | [6a63f48182](https://linux-hardware.org/?probe=6a63f48182) | May 29, 2021 |
| Gigabyte   | Z68M-D2H                    | [75877fb3b1](https://linux-hardware.org/?probe=75877fb3b1) | May 19, 2021 |
| Gigabyte   | Z68M-D2H                    | [91cee123e9](https://linux-hardware.org/?probe=91cee123e9) | May 19, 2021 |
| Gigabyte   | Z68M-D2H                    | [ec195ffe95](https://linux-hardware.org/?probe=ec195ffe95) | May 12, 2021 |
| ASUSTek    | ROG STRIX Z390-H GAMING     | [8260769b47](https://linux-hardware.org/?probe=8260769b47) | May 01, 2021 |
| ASUSTek    | P6T SE                      | [a2fb8f6b18](https://linux-hardware.org/?probe=a2fb8f6b18) | May 01, 2021 |
| ASUSTek    | P8H77-M LE                  | [289b0a89c0](https://linux-hardware.org/?probe=289b0a89c0) | Apr 25, 2021 |
| ASUSTek    | Maximus VIII IMPACT         | [2c0a43e573](https://linux-hardware.org/?probe=2c0a43e573) | Apr 24, 2021 |
| Gigabyte   | Z77X-D3H                    | [28751098a6](https://linux-hardware.org/?probe=28751098a6) | Apr 23, 2021 |
| Gigabyte   | Z68M-D2H                    | [c2c4591ef9](https://linux-hardware.org/?probe=c2c4591ef9) | Apr 16, 2021 |
| ASRock     | X370 Gaming-ITX/ac          | [e0fa7ade7a](https://linux-hardware.org/?probe=e0fa7ade7a) | Apr 06, 2021 |
| Huanan     | X79 249PC V2.2              | [787866050a](https://linux-hardware.org/?probe=787866050a) | Apr 03, 2021 |
| Pegatron   | IPI43-TTM                   | [87168e11ee](https://linux-hardware.org/?probe=87168e11ee) | Mar 26, 2021 |
| Pegatron   | IPI43-TTM                   | [72adf1881e](https://linux-hardware.org/?probe=72adf1881e) | Mar 26, 2021 |
| ASUSTek    | Z77-A                       | [ca21510412](https://linux-hardware.org/?probe=ca21510412) | Mar 23, 2021 |
| ASUSTek    | PRIME A320M-K               | [4c755699d3](https://linux-hardware.org/?probe=4c755699d3) | Mar 21, 2021 |
| ASUSTek    | P7P55D-E LX                 | [83f55d5bf7](https://linux-hardware.org/?probe=83f55d5bf7) | Mar 20, 2021 |
| HP         | 3031h                       | [ee5e7baf77](https://linux-hardware.org/?probe=ee5e7baf77) | Mar 16, 2021 |
| ASUSTek    | Z97-A                       | [0cc10a7f8b](https://linux-hardware.org/?probe=0cc10a7f8b) | Mar 14, 2021 |
| ASUSTek    | ROG STRIX Z390-H GAMING     | [26c69c1a34](https://linux-hardware.org/?probe=26c69c1a34) | Mar 07, 2021 |
| ASUSTek    | PRIME B450-PLUS             | [79b5c4e048](https://linux-hardware.org/?probe=79b5c4e048) | Mar 07, 2021 |
| Dell       | 0KJCC5 A00                  | [5587c00381](https://linux-hardware.org/?probe=5587c00381) | Mar 02, 2021 |
| Unknown    | Unknown                     | [c6d24d073b](https://linux-hardware.org/?probe=c6d24d073b) | Feb 25, 2021 |
| Unknown    | Unknown                     | [f97163d774](https://linux-hardware.org/?probe=f97163d774) | Feb 24, 2021 |
| BCM        | RX965Q                      | [889ee09398](https://linux-hardware.org/?probe=889ee09398) | Feb 21, 2021 |
| ASUSTek    | ROG STRIX H470-I GAMING     | [f747681c25](https://linux-hardware.org/?probe=f747681c25) | Feb 19, 2021 |
| ASUSTek    | H61M-A                      | [2b8de1db1f](https://linux-hardware.org/?probe=2b8de1db1f) | Feb 19, 2021 |
| Dell       | 0KRC95 A02                  | [745c1185fd](https://linux-hardware.org/?probe=745c1185fd) | Feb 18, 2021 |
| ASUSTek    | H61M-K                      | [d470929ba8](https://linux-hardware.org/?probe=d470929ba8) | Feb 14, 2021 |
| MSI        | A320M PRO-VD PLUS           | [24a9ae34ed](https://linux-hardware.org/?probe=24a9ae34ed) | Feb 13, 2021 |
| Gigabyte   | B450M DS3H-CF               | [5f9a9ff276](https://linux-hardware.org/?probe=5f9a9ff276) | Feb 13, 2021 |
| Gigabyte   | B450M DS3H-CF               | [d8069f1e01](https://linux-hardware.org/?probe=d8069f1e01) | Feb 12, 2021 |
| MSI        | B250M BAZOOKA               | [f48bc9fc78](https://linux-hardware.org/?probe=f48bc9fc78) | Feb 07, 2021 |
| MSI        | B250M BAZOOKA               | [1f3b4b8203](https://linux-hardware.org/?probe=1f3b4b8203) | Feb 07, 2021 |
| MSI        | B250M BAZOOKA               | [005301f0e8](https://linux-hardware.org/?probe=005301f0e8) | Feb 07, 2021 |
| MSI        | B250M BAZOOKA               | [48a778609f](https://linux-hardware.org/?probe=48a778609f) | Feb 06, 2021 |
| Apple      | Mac-F4208DC8 PVT            | [bb89e367c8](https://linux-hardware.org/?probe=bb89e367c8) | Jan 17, 2021 |
| Gigabyte   | H110M-A-CF                  | [3a07ab383e](https://linux-hardware.org/?probe=3a07ab383e) | Jan 15, 2021 |
| Gigabyte   | H110M-A-CF                  | [bb66f59b76](https://linux-hardware.org/?probe=bb66f59b76) | Jan 12, 2021 |
| HP         | 1589                        | [fe93b414cb](https://linux-hardware.org/?probe=fe93b414cb) | Jan 09, 2021 |
| ASUSTek    | TUF Z370-PLUS GAMING        | [276dda536a](https://linux-hardware.org/?probe=276dda536a) | Jan 06, 2021 |
| Gigabyte   | H110M-A-CF                  | [bff63b3c48](https://linux-hardware.org/?probe=bff63b3c48) | Jan 05, 2021 |
| ASUSTek    | TUF Z370-PLUS GAMING        | [a80e8c5eb0](https://linux-hardware.org/?probe=a80e8c5eb0) | Jan 02, 2021 |
| Gigabyte   | B550I AORUS PRO AX          | [1effa5938b](https://linux-hardware.org/?probe=1effa5938b) | Dec 31, 2020 |
| Dell       | 0PK096                      | [e1a520e089](https://linux-hardware.org/?probe=e1a520e089) | Dec 24, 2020 |
| Gigabyte   | B550M AORUS PRO-P           | [c32461bc20](https://linux-hardware.org/?probe=c32461bc20) | Dec 19, 2020 |
| ASUSTek    | PRIME A320M-K/BR            | [d65d3733f6](https://linux-hardware.org/?probe=d65d3733f6) | Dec 07, 2020 |
| Gigabyte   | TRX40 DESIGNARE             | [25ff6d84d0](https://linux-hardware.org/?probe=25ff6d84d0) | Dec 07, 2020 |
| ASRock     | P67 Extreme4                | [ca2f3a785a](https://linux-hardware.org/?probe=ca2f3a785a) | Dec 06, 2020 |
| MSI        | MAG B550 TOMAHAWK           | [77dc96c206](https://linux-hardware.org/?probe=77dc96c206) | Nov 27, 2020 |
| LattePanda | Alpha                       | [706f930815](https://linux-hardware.org/?probe=706f930815) | Nov 26, 2020 |
| LattePanda | Alpha                       | [a5c3e54e65](https://linux-hardware.org/?probe=a5c3e54e65) | Nov 24, 2020 |
| Gigabyte   | 970A-D3P                    | [304945ac43](https://linux-hardware.org/?probe=304945ac43) | Nov 23, 2020 |
| ASUSTek    | Z97-A-USB31                 | [8bbc1a2d1c](https://linux-hardware.org/?probe=8bbc1a2d1c) | Nov 22, 2020 |
| ASUSTek    | P8Z68-V                     | [643bb20dc1](https://linux-hardware.org/?probe=643bb20dc1) | Nov 20, 2020 |
| Gigabyte   | TRX40 DESIGNARE             | [eb2134b274](https://linux-hardware.org/?probe=eb2134b274) | Oct 31, 2020 |
| MSI        | MEG Z490I UNIFY             | [e59b548946](https://linux-hardware.org/?probe=e59b548946) | Oct 31, 2020 |
| MSI        | MEG Z490I UNIFY             | [39348ac053](https://linux-hardware.org/?probe=39348ac053) | Oct 31, 2020 |
| Gigabyte   | Z170X-Gaming 3              | [58b6426d57](https://linux-hardware.org/?probe=58b6426d57) | Oct 30, 2020 |
| ASUSTek    | TUF Gaming X570-PLUS        | [aead0dde26](https://linux-hardware.org/?probe=aead0dde26) | Oct 27, 2020 |
| ASUSTek    | Maximus VIII IMPACT         | [b5a98b7ffa](https://linux-hardware.org/?probe=b5a98b7ffa) | Oct 24, 2020 |
| MSI        | Z370 GAMING PLUS            | [a5246866a5](https://linux-hardware.org/?probe=a5246866a5) | Oct 21, 2020 |
| MSI        | Z370 GAMING PLUS            | [19879c3493](https://linux-hardware.org/?probe=19879c3493) | Oct 21, 2020 |
| HP         | 1998                        | [e8076a87a0](https://linux-hardware.org/?probe=e8076a87a0) | Oct 20, 2020 |
| HP         | 1998                        | [69ed04c55d](https://linux-hardware.org/?probe=69ed04c55d) | Oct 20, 2020 |
| Apple      | Mac-F4208DC8 PVT            | [25565a3bbf](https://linux-hardware.org/?probe=25565a3bbf) | Oct 19, 2020 |
| Apple      | Mac-F4208DC8 PVT            | [3aa954c07b](https://linux-hardware.org/?probe=3aa954c07b) | Oct 19, 2020 |
| MSI        | MAG X570 TOMAHAWK WIFI      | [7c78d9b4da](https://linux-hardware.org/?probe=7c78d9b4da) | Oct 18, 2020 |
| MSI        | MAG X570 TOMAHAWK WIFI      | [ca85fa1d88](https://linux-hardware.org/?probe=ca85fa1d88) | Oct 18, 2020 |
| ASRock     | Q1900B-ITX                  | [527411a589](https://linux-hardware.org/?probe=527411a589) | Oct 15, 2020 |
| Unknown    | Unknown                     | [f82db8cb1c](https://linux-hardware.org/?probe=f82db8cb1c) | Oct 13, 2020 |
| AAEON      | UP-APL01 V0.4               | [3d2cb2e4d1](https://linux-hardware.org/?probe=3d2cb2e4d1) | Oct 12, 2020 |
| AAEON      | UP-APL01 V0.4               | [16d3bf5578](https://linux-hardware.org/?probe=16d3bf5578) | Oct 12, 2020 |
| ASUSTek    | TUF Z390-PLUS GAMING        | [9d2f2dbd87](https://linux-hardware.org/?probe=9d2f2dbd87) | Oct 12, 2020 |
| Dell       | 0M9KCM A00                  | [f884d19586](https://linux-hardware.org/?probe=f884d19586) | Oct 02, 2020 |
| MSI        | MAG X570 TOMAHAWK WIFI      | [4a62de4c07](https://linux-hardware.org/?probe=4a62de4c07) | Oct 01, 2020 |
| ASRock     | B550 Phantom Gaming 4       | [a996c3d55c](https://linux-hardware.org/?probe=a996c3d55c) | Sep 29, 2020 |
| ASUSTek    | P9X79 DELUXE                | [5b7738af52](https://linux-hardware.org/?probe=5b7738af52) | Sep 23, 2020 |
| Dell       | 0RY007                      | [b1ca551538](https://linux-hardware.org/?probe=b1ca551538) | Sep 22, 2020 |
| Gigabyte   | B360 AORUS GAMING 3-CF      | [663a5ef41a](https://linux-hardware.org/?probe=663a5ef41a) | Sep 21, 2020 |
| Dell       | 0200DY A03                  | [e91f9c04b9](https://linux-hardware.org/?probe=e91f9c04b9) | Sep 21, 2020 |
| Gigabyte   | Z68M-D2H                    | [d746ae5a52](https://linux-hardware.org/?probe=d746ae5a52) | Sep 19, 2020 |
| MSI        | MAG X570 TOMAHAWK WIFI      | [1037d2b746](https://linux-hardware.org/?probe=1037d2b746) | Sep 09, 2020 |
| MSI        | MAG X570 TOMAHAWK WIFI      | [b3d6fb36eb](https://linux-hardware.org/?probe=b3d6fb36eb) | Sep 08, 2020 |
| Gigabyte   | Z390 DESIGNARE-CF           | [d36f3124d1](https://linux-hardware.org/?probe=d36f3124d1) | Sep 06, 2020 |
| ASUSTek    | ROG STRIX X470-F GAMING     | [e90f4fb0e5](https://linux-hardware.org/?probe=e90f4fb0e5) | Sep 06, 2020 |
| PCSMART    | 6.0                         | [e95fadbdfe](https://linux-hardware.org/?probe=e95fadbdfe) | Sep 05, 2020 |
| MSI        | Z97 GAMING 5                | [3f1b387a92](https://linux-hardware.org/?probe=3f1b387a92) | Sep 04, 2020 |
| Gigabyte   | G31M-ES2L                   | [ed4a78cd06](https://linux-hardware.org/?probe=ed4a78cd06) | Aug 24, 2020 |
| MSI        | Z87-G41 PC Mate             | [1b2d8402af](https://linux-hardware.org/?probe=1b2d8402af) | Aug 17, 2020 |
| ASUSTek    | P9X79 DELUXE                | [75f32f4978](https://linux-hardware.org/?probe=75f32f4978) | Aug 16, 2020 |
| Gigabyte   | P55A-UD4P                   | [c908fd4599](https://linux-hardware.org/?probe=c908fd4599) | Aug 07, 2020 |
| ASUSTek    | P8H77-M PRO                 | [d943208a7c](https://linux-hardware.org/?probe=d943208a7c) | Jul 30, 2020 |
| Gigabyte   | Z170-HD3 DDR3-CF            | [f8c44dc8be](https://linux-hardware.org/?probe=f8c44dc8be) | Jul 29, 2020 |
| ASUSTek    | STRIX B250F GAMING          | [cb5d511453](https://linux-hardware.org/?probe=cb5d511453) | Jul 28, 2020 |
| ASUSTek    | P8H77-M PRO                 | [87d7bc3077](https://linux-hardware.org/?probe=87d7bc3077) | Jul 28, 2020 |
| MSI        | X370 GAMING PRO CARBON      | [f38e8a0201](https://linux-hardware.org/?probe=f38e8a0201) | Jul 26, 2020 |
| HP         | 82F2                        | [172d6aed2a](https://linux-hardware.org/?probe=172d6aed2a) | Jul 26, 2020 |
| Gigabyte   | B360 AORUS GAMING 3 WIFI... | [2e6c21ed23](https://linux-hardware.org/?probe=2e6c21ed23) | Jul 26, 2020 |
| HP         | 3397                        | [edd52c2428](https://linux-hardware.org/?probe=edd52c2428) | Jul 24, 2020 |
| HP         | 3397                        | [20b3d353d8](https://linux-hardware.org/?probe=20b3d353d8) | Jul 24, 2020 |
| Gigabyte   | H61M-S1                     | [3ce4143dee](https://linux-hardware.org/?probe=3ce4143dee) | Jul 24, 2020 |
| Gigabyte   | B360 AORUS GAMING 3 WIFI... | [534a204796](https://linux-hardware.org/?probe=534a204796) | Jul 17, 2020 |
| ASUSTek    | M51AC                       | [fcc0f73453](https://linux-hardware.org/?probe=fcc0f73453) | Jul 15, 2020 |
| ASUSTek    | M4A87TD/USB3                | [7d642bd7dc](https://linux-hardware.org/?probe=7d642bd7dc) | Jul 14, 2020 |
| ASUSTek    | M4A87TD/USB3                | [76752b2d00](https://linux-hardware.org/?probe=76752b2d00) | Jul 13, 2020 |
| ASUSTek    | M4A87TD/USB3                | [8639032305](https://linux-hardware.org/?probe=8639032305) | Jul 13, 2020 |
| Dell       | 0P301D A02                  | [709ca37e1e](https://linux-hardware.org/?probe=709ca37e1e) | Jul 12, 2020 |
| ASUSTek    | M51AC                       | [6af32ff946](https://linux-hardware.org/?probe=6af32ff946) | Jul 01, 2020 |
| ASUSTek    | B85M-E                      | [e46352dec8](https://linux-hardware.org/?probe=e46352dec8) | Jun 28, 2020 |
| Dell       | 09KPNV A00                  | [9f63cccd5c](https://linux-hardware.org/?probe=9f63cccd5c) | Jun 21, 2020 |
| ASUSTek    | P8Z68-V PRO GEN3            | [311c0852f2](https://linux-hardware.org/?probe=311c0852f2) | Jun 18, 2020 |
| Gigabyte   | Z68M-D2H                    | [fbbc2c4d98](https://linux-hardware.org/?probe=fbbc2c4d98) | May 30, 2020 |
| Gigabyte   | Z68M-D2H                    | [ca71847ca1](https://linux-hardware.org/?probe=ca71847ca1) | May 30, 2020 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [49486e2abf](https://linux-hardware.org/?probe=49486e2abf) | May 24, 2020 |
| ASUSTek    | P8H77-M PRO                 | [cdaf886b58](https://linux-hardware.org/?probe=cdaf886b58) | May 20, 2020 |
| ASUSTek    | P8H77-M PRO                 | [e8b5bf55c7](https://linux-hardware.org/?probe=e8b5bf55c7) | May 20, 2020 |
| Dell       | 0J32FG A06                  | [d5d2970bc5](https://linux-hardware.org/?probe=d5d2970bc5) | May 15, 2020 |
| Gigabyte   | Z68M-D2H                    | [70c167639c](https://linux-hardware.org/?probe=70c167639c) | May 15, 2020 |
| Dell       | 0TNXNR A01                  | [c16ecd859c](https://linux-hardware.org/?probe=c16ecd859c) | May 11, 2020 |
| Lenovo     | 3704 SDK0R32862 WIN 3258... | [eb7d6f2ec3](https://linux-hardware.org/?probe=eb7d6f2ec3) | May 10, 2020 |
| Biostar    | G31-M7 TE                   | [e9d31442df](https://linux-hardware.org/?probe=e9d31442df) | May 09, 2020 |
| ASRock     | B450 Gaming-ITX/ac          | [2e108e8f82](https://linux-hardware.org/?probe=2e108e8f82) | May 06, 2020 |
| MSI        | Z87-G41 PC Mate             | [c17fa3f327](https://linux-hardware.org/?probe=c17fa3f327) | May 02, 2020 |
| MSI        | MEG Z390 GODLIKE            | [f5c70a1643](https://linux-hardware.org/?probe=f5c70a1643) | Apr 30, 2020 |
| ASUSTek    | TUF B450-PLUS GAMING        | [6982ff0a12](https://linux-hardware.org/?probe=6982ff0a12) | Apr 25, 2020 |
| HP         | 0A80h                       | [f51e29fc6f](https://linux-hardware.org/?probe=f51e29fc6f) | Apr 13, 2020 |
| Gigabyte   | Z68M-D2H                    | [3db29a7f67](https://linux-hardware.org/?probe=3db29a7f67) | Apr 12, 2020 |
| ASRock     | N68C-S UCC                  | [c6df4257a4](https://linux-hardware.org/?probe=c6df4257a4) | Apr 11, 2020 |
| HP         | 8433 11                     | [e20dd4e4a3](https://linux-hardware.org/?probe=e20dd4e4a3) | Apr 02, 2020 |
| HP         | 8433 11                     | [eafaace7ee](https://linux-hardware.org/?probe=eafaace7ee) | Apr 02, 2020 |
| HP         | 8433 11                     | [0e29f294ba](https://linux-hardware.org/?probe=0e29f294ba) | Apr 02, 2020 |
| ASUSTek    | ROG CROSSHAIR VII HERO      | [5b8ef620f7](https://linux-hardware.org/?probe=5b8ef620f7) | Mar 27, 2020 |
| Gigabyte   | AB350-Gaming 3-CF           | [384177f515](https://linux-hardware.org/?probe=384177f515) | Mar 23, 2020 |
| Apple      | Mac-F221BEC8                | [477afd03f4](https://linux-hardware.org/?probe=477afd03f4) | Mar 21, 2020 |
| Dell       | 0J32FG A06                  | [efb8737ca2](https://linux-hardware.org/?probe=efb8737ca2) | Mar 20, 2020 |
| MSI        | Z270-A PRO                  | [5e41eb4c66](https://linux-hardware.org/?probe=5e41eb4c66) | Mar 14, 2020 |
| Dell       | 0C2KJT A00                  | [210b1c0abf](https://linux-hardware.org/?probe=210b1c0abf) | Mar 13, 2020 |
| ASUSTek    | Maximus VIII IMPACT         | [9ca13583bb](https://linux-hardware.org/?probe=9ca13583bb) | Mar 09, 2020 |
| eMachines  | EL1852G                     | [e90ac3f652](https://linux-hardware.org/?probe=e90ac3f652) | Feb 27, 2020 |
| Intel      | DQ965CO AAD34641-506        | [3c3c53b8e5](https://linux-hardware.org/?probe=3c3c53b8e5) | Feb 26, 2020 |
| ASUSTek    | Z97-A                       | [45382a84f3](https://linux-hardware.org/?probe=45382a84f3) | Feb 21, 2020 |
| HP         | 2215                        | [f9ecf106d2](https://linux-hardware.org/?probe=f9ecf106d2) | Feb 19, 2020 |
| Acer       | Veriton L4610G              | [e38723516e](https://linux-hardware.org/?probe=e38723516e) | Feb 17, 2020 |
| Acer       | Veriton L4610G              | [aef314a65c](https://linux-hardware.org/?probe=aef314a65c) | Feb 17, 2020 |
| Gigabyte   | Z68M-D2H                    | [6cfda70306](https://linux-hardware.org/?probe=6cfda70306) | Feb 15, 2020 |
| Intel      | ChiefRiver                  | [1ca590a614](https://linux-hardware.org/?probe=1ca590a614) | Jan 22, 2020 |
| Dell       | 0C27VV A01                  | [b896b0fef0](https://linux-hardware.org/?probe=b896b0fef0) | Jan 18, 2020 |
| Gigabyte   | MSH87TN-00                  | [624e731bcd](https://linux-hardware.org/?probe=624e731bcd) | Jan 16, 2020 |
| Gigabyte   | P55A-UD4P                   | [df0bc17152](https://linux-hardware.org/?probe=df0bc17152) | Jan 13, 2020 |
| Dell       | 0G9322                      | [62b841a44f](https://linux-hardware.org/?probe=62b841a44f) | Jun 08, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Ubuntu Budgie 20.04 | 67       | 36.22%  |
| Ubuntu Budgie 22.04 | 27       | 14.59%  |
| Ubuntu Budgie 20.10 | 23       | 12.43%  |
| Ubuntu Budgie 21.10 | 19       | 10.27%  |
| Ubuntu Budgie 21.04 | 13       | 7.03%   |
| Ubuntu Budgie 19.10 | 13       | 7.03%   |
| Ubuntu Budgie 18.04 | 12       | 6.49%   |
| Ubuntu Budgie 22.10 | 9        | 4.86%   |
| Ubuntu Budgie       | 2        | 1.08%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu Budgie | 173      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.4.0-42-generic  | 8        | 3.94%   |
| 5.4.0-47-generic  | 5        | 2.46%   |
| 5.8.0-43-generic  | 4        | 1.97%   |
| 5.4.0-52-generic  | 4        | 1.97%   |
| 5.4.0-48-generic  | 4        | 1.97%   |
| 5.4.0-45-generic  | 4        | 1.97%   |
| 5.4.0-37-generic  | 4        | 1.97%   |
| 5.3.0-40-generic  | 4        | 1.97%   |
| 5.3.0-26-generic  | 4        | 1.97%   |
| 5.15.0-52-generic | 4        | 1.97%   |
| 5.13.0-22-generic | 4        | 1.97%   |
| 5.8.0-44-generic  | 3        | 1.48%   |
| 5.8.0-25-generic  | 3        | 1.48%   |
| 5.4.0-31-generic  | 3        | 1.48%   |
| 5.4.0-29-generic  | 3        | 1.48%   |
| 5.3.0-42-generic  | 3        | 1.48%   |
| 5.19.0-26-generic | 3        | 1.48%   |
| 5.15.0-46-generic | 3        | 1.48%   |
| 5.15.0-43-generic | 3        | 1.48%   |
| 5.15.0-30-generic | 3        | 1.48%   |
| 5.13.0-39-generic | 3        | 1.48%   |
| 5.11.0-41-generic | 3        | 1.48%   |
| 5.11.0-22-generic | 3        | 1.48%   |
| 5.11.0-18-generic | 3        | 1.48%   |
| 5.8.0-59-generic  | 2        | 0.99%   |
| 5.8.0-50-generic  | 2        | 0.99%   |
| 5.8.0-48-generic  | 2        | 0.99%   |
| 5.8.0-45-generic  | 2        | 0.99%   |
| 5.8.0-31-generic  | 2        | 0.99%   |
| 5.8.0-29-generic  | 2        | 0.99%   |
| 5.8.0-26-generic  | 2        | 0.99%   |
| 5.4.0-91-generic  | 2        | 0.99%   |
| 5.4.0-72-generic  | 2        | 0.99%   |
| 5.4.0-66-generic  | 2        | 0.99%   |
| 5.4.0-59-generic  | 2        | 0.99%   |
| 5.4.0-40-generic  | 2        | 0.99%   |
| 5.3.0-28-generic  | 2        | 0.99%   |
| 5.19.0-31-generic | 2        | 0.99%   |
| 5.19.0-23-generic | 2        | 0.99%   |
| 5.15.0-57-generic | 2        | 0.99%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 57       | 30.65%  |
| 5.8.0   | 30       | 16.13%  |
| 5.15.0  | 26       | 13.98%  |
| 5.13.0  | 20       | 10.75%  |
| 5.3.0   | 17       | 9.14%   |
| 5.11.0  | 15       | 8.06%   |
| 5.19.0  | 9        | 4.84%   |
| 4.15.0  | 2        | 1.08%   |
| 5.9.1   | 1        | 0.54%   |
| 5.7.7   | 1        | 0.54%   |
| 5.5.8   | 1        | 0.54%   |
| 5.17.2  | 1        | 0.54%   |
| 5.17.1  | 1        | 0.54%   |
| 5.15.92 | 1        | 0.54%   |
| 5.14.2  | 1        | 0.54%   |
| 5.14.1  | 1        | 0.54%   |
| 5.10.0  | 1        | 0.54%   |
| 5.0.0   | 1        | 0.54%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 57       | 30.81%  |
| 5.8     | 30       | 16.22%  |
| 5.15    | 27       | 14.59%  |
| 5.13    | 20       | 10.81%  |
| 5.3     | 17       | 9.19%   |
| 5.11    | 15       | 8.11%   |
| 5.19    | 9        | 4.86%   |
| 5.17    | 2        | 1.08%   |
| 4.15    | 2        | 1.08%   |
| 5.9     | 1        | 0.54%   |
| 5.7     | 1        | 0.54%   |
| 5.5     | 1        | 0.54%   |
| 5.14    | 1        | 0.54%   |
| 5.10    | 1        | 0.54%   |
| 5.0     | 1        | 0.54%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 168      | 97.11%  |
| i686   | 5        | 2.89%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Budgie | 167      | 96.53%  |
| GNOME  | 4        | 2.31%   |
| MATE   | 1        | 0.58%   |
| KDE    | 1        | 0.58%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 170      | 98.27%  |
| Wayland | 2        | 1.16%   |
| Tty     | 1        | 0.58%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 90       | 50.85%  |
| LightDM | 49       | 27.68%  |
| TDM     | 27       | 15.25%  |
| GDM     | 6        | 3.39%   |
| GDM3    | 4        | 2.26%   |
| SDDM    | 1        | 0.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 68       | 39.31%  |
| de_DE   | 24       | 13.87%  |
| fr_FR   | 14       | 8.09%   |
| pt_BR   | 11       | 6.36%   |
| en_CA   | 8        | 4.62%   |
| en_AU   | 6        | 3.47%   |
| es_ES   | 5        | 2.89%   |
| en_GB   | 5        | 2.89%   |
| es_MX   | 3        | 1.73%   |
| zh_TW   | 2        | 1.16%   |
| uk_UA   | 2        | 1.16%   |
| pt_PT   | 2        | 1.16%   |
| pl_PL   | 2        | 1.16%   |
| nl_NL   | 2        | 1.16%   |
| it_IT   | 2        | 1.16%   |
| es_CO   | 2        | 1.16%   |
| es_AR   | 2        | 1.16%   |
| Unknown | 2        | 1.16%   |
| ru_UA   | 1        | 0.58%   |
| ru_RU   | 1        | 0.58%   |
| ro_RO   | 1        | 0.58%   |
| fr_CH   | 1        | 0.58%   |
| fr_CA   | 1        | 0.58%   |
| es_CL   | 1        | 0.58%   |
| en_IN   | 1        | 0.58%   |
| en_IL   | 1        | 0.58%   |
| el_GR   | 1        | 0.58%   |
| C       | 1        | 0.58%   |
| bg_BG   | 1        | 0.58%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 115      | 64.25%  |
| EFI  | 64       | 35.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 161      | 92.53%  |
| Zfs     | 6        | 3.45%   |
| Overlay | 4        | 2.3%    |
| Btrfs   | 3        | 1.72%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 111      | 63.07%  |
| GPT     | 53       | 30.11%  |
| MBR     | 12       | 6.82%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 142      | 79.78%  |
| Yes       | 36       | 20.22%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 113      | 63.13%  |
| Yes       | 66       | 36.87%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 48       | 27.75%  |
| Gigabyte Technology | 34       | 19.65%  |
| MSI                 | 17       | 9.83%   |
| Dell                | 16       | 9.25%   |
| Hewlett-Packard     | 15       | 8.67%   |
| ASRock              | 14       | 8.09%   |
| Intel               | 6        | 3.47%   |
| Lenovo              | 4        | 2.31%   |
| Fujitsu             | 4        | 2.31%   |
| Apple               | 3        | 1.73%   |
| Biostar             | 2        | 1.16%   |
| Acer                | 2        | 1.16%   |
| Unknown             | 2        | 1.16%   |
| Pegatron            | 1        | 0.58%   |
| PCSMART             | 1        | 0.58%   |
| LattePanda          | 1        | 0.58%   |
| Huanan              | 1        | 0.58%   |
| eMachines           | 1        | 0.58%   |
| BCM                 | 1        | 0.58%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| ASUS All Series                         | 6        | 3.47%   |
| Dell OptiPlex 780                       | 3        | 1.73%   |
| MSI MS-7C84                             | 2        | 1.16%   |
| Intel DP55WB AAE64798-206               | 2        | 1.16%   |
| HP EliteDesk 800 G1 SFF                 | 2        | 1.16%   |
| HP Compaq Elite 8300 SFF                | 2        | 1.16%   |
| Gigabyte Z68M-D2H                       | 2        | 1.16%   |
| Gigabyte AB350-Gaming 3                 | 2        | 1.16%   |
| Dell Precision WorkStation T3500        | 2        | 1.16%   |
| Dell OptiPlex 9010                      | 2        | 1.16%   |
| ASUS PRIME B560M-A                      | 2        | 1.16%   |
| ASUS PRIME B450M-A                      | 2        | 1.16%   |
| ASUS P8H77-M PRO                        | 2        | 1.16%   |
| Apple MacPro1,1                         | 2        | 1.16%   |
| Unknown                                 | 2        | 1.16%   |
| Pegatron IPI43-TTM                      | 1        | 0.58%   |
| PCSMART 6.0                             | 1        | 0.58%   |
| MSI MS-7C95                             | 1        | 0.58%   |
| MSI MS-7C77                             | 1        | 0.58%   |
| MSI MS-7B86                             | 1        | 0.58%   |
| MSI MS-7B61                             | 1        | 0.58%   |
| MSI MS-7B38                             | 1        | 0.58%   |
| MSI MS-7B10                             | 1        | 0.58%   |
| MSI MS-7A71                             | 1        | 0.58%   |
| MSI MS-7A70                             | 1        | 0.58%   |
| MSI MS-7A32                             | 1        | 0.58%   |
| MSI MS-7971                             | 1        | 0.58%   |
| MSI MS-7917                             | 1        | 0.58%   |
| MSI MS-7885                             | 1        | 0.58%   |
| MSI MS-7850                             | 1        | 0.58%   |
| MSI MS-7817                             | 1        | 0.58%   |
| MSI MS-7680                             | 1        | 0.58%   |
| Lenovo ThinkStation C20 4263BA7         | 1        | 0.58%   |
| Lenovo Legion T530-28ICB 90L300BQMW     | 1        | 0.58%   |
| Lenovo IdeaCentre 310S-08ASR 90G9007EGE | 1        | 0.58%   |
| Lenovo H30-05 90BJ0086GE                | 1        | 0.58%   |
| LattePanda Alpha                        | 1        | 0.58%   |
| Intel STK1A32SC                         | 1        | 0.58%   |
| Intel DB75EN AAG39650-303               | 1        | 0.58%   |
| Intel CLIENTPRO 385                     | 1        | 0.58%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS PRIME            | 9        | 5.2%    |
| Dell OptiPlex         | 8        | 4.62%   |
| ASUS ROG              | 7        | 4.05%   |
| ASUS All              | 6        | 3.47%   |
| Dell Precision        | 5        | 2.89%   |
| HP EliteDesk          | 4        | 2.31%   |
| HP Compaq             | 4        | 2.31%   |
| ASUS TUF              | 3        | 1.73%   |
| ASUS P8H77-M          | 3        | 1.73%   |
| MSI MS-7C84           | 2        | 1.16%   |
| Intel DP55WB          | 2        | 1.16%   |
| HP Pavilion           | 2        | 1.16%   |
| Gigabyte Z68M-D2H     | 2        | 1.16%   |
| Gigabyte X570         | 2        | 1.16%   |
| Gigabyte B360         | 2        | 1.16%   |
| Gigabyte AB350-Gaming | 2        | 1.16%   |
| Fujitsu ESPRIMO       | 2        | 1.16%   |
| Dell Inspiron         | 2        | 1.16%   |
| ASUS P8Z68-V          | 2        | 1.16%   |
| ASRock B550           | 2        | 1.16%   |
| Apple MacPro1         | 2        | 1.16%   |
| Unknown               | 2        | 1.16%   |
| Pegatron IPI43-TTM    | 1        | 0.58%   |
| PCSMART 6.0           | 1        | 0.58%   |
| MSI MS-7C95           | 1        | 0.58%   |
| MSI MS-7C77           | 1        | 0.58%   |
| MSI MS-7B86           | 1        | 0.58%   |
| MSI MS-7B61           | 1        | 0.58%   |
| MSI MS-7B38           | 1        | 0.58%   |
| MSI MS-7B10           | 1        | 0.58%   |
| MSI MS-7A71           | 1        | 0.58%   |
| MSI MS-7A70           | 1        | 0.58%   |
| MSI MS-7A32           | 1        | 0.58%   |
| MSI MS-7971           | 1        | 0.58%   |
| MSI MS-7917           | 1        | 0.58%   |
| MSI MS-7885           | 1        | 0.58%   |
| MSI MS-7850           | 1        | 0.58%   |
| MSI MS-7817           | 1        | 0.58%   |
| MSI MS-7680           | 1        | 0.58%   |
| Lenovo ThinkStation   | 1        | 0.58%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 22       | 12.72%  |
| 2013 | 18       | 10.4%   |
| 2020 | 16       | 9.25%   |
| 2012 | 14       | 8.09%   |
| 2017 | 13       | 7.51%   |
| 2011 | 13       | 7.51%   |
| 2014 | 12       | 6.94%   |
| 2019 | 11       | 6.36%   |
| 2010 | 11       | 6.36%   |
| 2015 | 9        | 5.2%    |
| 2009 | 9        | 5.2%    |
| 2016 | 7        | 4.05%   |
| 2007 | 7        | 4.05%   |
| 2021 | 6        | 3.47%   |
| 2008 | 5        | 2.89%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 173      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 169      | 97.13%  |
| Enabled  | 5        | 2.87%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 173      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 65       | 36.93%  |
| 8.01-16.0       | 30       | 17.05%  |
| 4.01-8.0        | 21       | 11.93%  |
| 32.01-64.0      | 21       | 11.93%  |
| 3.01-4.0        | 21       | 11.93%  |
| 64.01-256.0     | 12       | 6.82%   |
| 24.01-32.0      | 2        | 1.14%   |
| 1.01-2.0        | 2        | 1.14%   |
| More than 256.0 | 1        | 0.57%   |
| 2.01-3.0        | 1        | 0.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 59       | 30.57%  |
| 1.01-2.0   | 57       | 29.53%  |
| 4.01-8.0   | 36       | 18.65%  |
| 3.01-4.0   | 25       | 12.95%  |
| 8.01-16.0  | 9        | 4.66%   |
| 0.51-1.0   | 4        | 2.07%   |
| 16.01-24.0 | 2        | 1.04%   |
| 32.01-64.0 | 1        | 0.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 51       | 28.18%  |
| 1      | 51       | 28.18%  |
| 3      | 33       | 18.23%  |
| 4      | 19       | 10.5%   |
| 5      | 14       | 7.73%   |
| 8      | 5        | 2.76%   |
| 6      | 5        | 2.76%   |
| 11     | 1        | 0.55%   |
| 9      | 1        | 0.55%   |
| 7      | 1        | 0.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 91       | 52.3%   |
| No        | 83       | 47.7%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 170      | 98.27%  |
| No        | 3        | 1.73%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 88       | 50.29%  |
| No        | 87       | 49.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 102      | 57.95%  |
| Yes       | 74       | 42.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 47       | 27.01%  |
| Germany      | 25       | 14.37%  |
| France       | 16       | 9.2%    |
| Brazil       | 11       | 6.32%   |
| Canada       | 8        | 4.6%    |
| Australia    | 6        | 3.45%   |
| Switzerland  | 5        | 2.87%   |
| UK           | 4        | 2.3%    |
| Spain        | 4        | 2.3%    |
| Mexico       | 4        | 2.3%    |
| Ukraine      | 3        | 1.72%   |
| Portugal     | 3        | 1.72%   |
| Poland       | 3        | 1.72%   |
| Netherlands  | 3        | 1.72%   |
| Croatia      | 3        | 1.72%   |
| Argentina    | 3        | 1.72%   |
| Sweden       | 2        | 1.15%   |
| Romania      | 2        | 1.15%   |
| Norway       | 2        | 1.15%   |
| Italy        | 2        | 1.15%   |
| Colombia     | 2        | 1.15%   |
| Thailand     | 1        | 0.57%   |
| Taiwan       | 1        | 0.57%   |
| Slovenia     | 1        | 0.57%   |
| Saudi Arabia | 1        | 0.57%   |
| Russia       | 1        | 0.57%   |
| Puerto Rico  | 1        | 0.57%   |
| Japan        | 1        | 0.57%   |
| Israel       | 1        | 0.57%   |
| India        | 1        | 0.57%   |
| Hungary      | 1        | 0.57%   |
| Greece       | 1        | 0.57%   |
| Chile        | 1        | 0.57%   |
| Bulgaria     | 1        | 0.57%   |
| Bolivia      | 1        | 0.57%   |
| Belgium      | 1        | 0.57%   |
| Austria      | 1        | 0.57%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| New York         | 3        | 1.67%   |
| Zurich           | 2        | 1.11%   |
| Zagreb           | 2        | 1.11%   |
| Uman             | 2        | 1.11%   |
| Trondheim        | 2        | 1.11%   |
| Timișoara       | 2        | 1.11%   |
| Sydney           | 2        | 1.11%   |
| Seattle          | 2        | 1.11%   |
| Sao Paulo        | 2        | 1.11%   |
| Paris            | 2        | 1.11%   |
| Milwaukee        | 2        | 1.11%   |
| Miami            | 2        | 1.11%   |
| Maringá         | 2        | 1.11%   |
| Lisbon           | 2        | 1.11%   |
| Hamburg          | 2        | 1.11%   |
| Dallas           | 2        | 1.11%   |
| Caslano          | 2        | 1.11%   |
| Bogotá          | 2        | 1.11%   |
| Barcelona        | 2        | 1.11%   |
| Zabrze           | 1        | 0.56%   |
| Würzburg        | 1        | 0.56%   |
| Willich          | 1        | 0.56%   |
| Westland         | 1        | 0.56%   |
| West Des Moines  | 1        | 0.56%   |
| Walled Lake      | 1        | 0.56%   |
| Void-Vacon       | 1        | 0.56%   |
| UEbach-Palenberg | 1        | 0.56%   |
| Tucson           | 1        | 0.56%   |
| Traunstein       | 1        | 0.56%   |
| Toyokawa         | 1        | 0.56%   |
| Toronto          | 1        | 0.56%   |
| Tocantins        | 1        | 0.56%   |
| Tobyhanna        | 1        | 0.56%   |
| Tlalnepantla     | 1        | 0.56%   |
| Tijuana          | 1        | 0.56%   |
| Thrissur         | 1        | 0.56%   |
| Telford          | 1        | 0.56%   |
| Tann             | 1        | 0.56%   |
| Świnoujście    | 1        | 0.56%   |
| Stockholm        | 1        | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 70       | 121    | 19.66%  |
| WDC                       | 62       | 109    | 17.42%  |
| Samsung Electronics       | 54       | 104    | 15.17%  |
| Toshiba                   | 20       | 20     | 5.62%   |
| Kingston                  | 20       | 30     | 5.62%   |
| SanDisk                   | 18       | 28     | 5.06%   |
| Hitachi                   | 13       | 17     | 3.65%   |
| Phison                    | 12       | 17     | 3.37%   |
| Crucial                   | 8        | 9      | 2.25%   |
| HGST                      | 6        | 7      | 1.69%   |
| Intel                     | 5        | 5      | 1.4%    |
| Unknown                   | 4        | 6      | 1.12%   |
| PNY                       | 4        | 4      | 1.12%   |
| OCZ                       | 4        | 7      | 1.12%   |
| China                     | 4        | 6      | 1.12%   |
| SPCC                      | 3        | 5      | 0.84%   |
| Patriot                   | 3        | 5      | 0.84%   |
| Maxtor                    | 3        | 6      | 0.84%   |
| JMicron Technology        | 3        | 4      | 0.84%   |
| A-DATA Technology         | 3        | 6      | 0.84%   |
| Transcend                 | 2        | 2      | 0.56%   |
| Silicon Motion            | 2        | 3      | 0.56%   |
| Micron/Crucial Technology | 2        | 2      | 0.56%   |
| Micron Technology         | 2        | 4      | 0.56%   |
| HS-SSD-C100               | 2        | 2      | 0.56%   |
| Apacer                    | 2        | 2      | 0.56%   |
| AMD                       | 2        | 17     | 0.56%   |
| Zheino                    | 1        | 2      | 0.28%   |
| XrayDisk                  | 1        | 1      | 0.28%   |
| WD MediaMax               | 1        | 1      | 0.28%   |
| TDAS                      | 1        | 3      | 0.28%   |
| SK hynix                  | 1        | 1      | 0.28%   |
| SABRENT                   | 1        | 1      | 0.28%   |
| Realtek Semiconductor     | 1        | 1      | 0.28%   |
| Plextor                   | 1        | 1      | 0.28%   |
| Phison Electronics        | 1        | 1      | 0.28%   |
| Netac                     | 1        | 1      | 0.28%   |
| Mushkin                   | 1        | 1      | 0.28%   |
| MDT                       | 1        | 1      | 0.28%   |
| Lexar                     | 1        | 1      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB     | 6        | 1.36%   |
| Samsung SSD 860 QVO 1TB            | 6        | 1.36%   |
| Samsung SSD 860 EVO 500GB          | 6        | 1.36%   |
| Seagate ST500DM002-1BD142 500GB    | 5        | 1.13%   |
| Kingston SA400S37480G 480GB SSD    | 5        | 1.13%   |
| WDC WD5000AAKS-00UU3A0 500GB       | 4        | 0.9%    |
| Seagate ST2000DM008-2FR102 2TB     | 4        | 0.9%    |
| Seagate ST2000DM001-1ER164 2TB     | 4        | 0.9%    |
| Seagate ST2000DM001-1CH164 2TB     | 4        | 0.9%    |
| Samsung SSD 850 EVO 500GB          | 4        | 0.9%    |
| Samsung NVMe SSD Drive 512GB       | 4        | 0.9%    |
| Samsung NVMe SSD Drive 500GB       | 4        | 0.9%    |
| Kingston SA400S37240G 240GB SSD    | 4        | 0.9%    |
| WDC WD5000AAKX-001CA0 500GB        | 3        | 0.68%   |
| WDC WD10EARS-00Y5B1 1TB            | 3        | 0.68%   |
| WDC WD10EADS-00M2B0 1TB            | 3        | 0.68%   |
| Toshiba HDWD110 1TB                | 3        | 0.68%   |
| Seagate ST9500325AS 500GB          | 3        | 0.68%   |
| Seagate ST4000DM000-1F2168 4TB     | 3        | 0.68%   |
| Seagate ST380815AS 80GB            | 3        | 0.68%   |
| Seagate ST2000DM006-2DM164 2TB     | 3        | 0.68%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3        | 0.68%   |
| Seagate ST1000DM003-1ER162 1TB     | 3        | 0.68%   |
| SanDisk SDSSDA240G 240GB           | 3        | 0.68%   |
| SanDisk SDSSDA120G 120GB           | 3        | 0.68%   |
| Phison NVMe SSD Drive 1TB          | 3        | 0.68%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 2        | 0.45%   |
| WDC WD7501AALS-00J7B1 752GB        | 2        | 0.45%   |
| WDC WD40EZRZ-22GXCB0 4TB           | 2        | 0.45%   |
| WDC WD40EZRZ-00GXCB0 4TB           | 2        | 0.45%   |
| WDC WD30EZRX-00D8PB0 3TB           | 2        | 0.45%   |
| WDC WD20EZRZ-00Z5HB0 2TB           | 2        | 0.45%   |
| WDC WD20EFRX-68EUZN0 2TB           | 2        | 0.45%   |
| WDC WD10EZEX-08WN4A0 1TB           | 2        | 0.45%   |
| WDC WD10EZEX-00RKKA0 1TB           | 2        | 0.45%   |
| Unknown SD/MMC/MS PRO 64GB         | 2        | 0.45%   |
| Toshiba MD04ACA400 4TB             | 2        | 0.45%   |
| Toshiba DT01ACA200 2TB             | 2        | 0.45%   |
| Toshiba DT01ACA100 1TB             | 2        | 0.45%   |
| SPCC Solid State Disk 256GB        | 2        | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 70       | 120    | 39.11%  |
| WDC                 | 56       | 98     | 31.28%  |
| Toshiba             | 20       | 20     | 11.17%  |
| Hitachi             | 13       | 17     | 7.26%   |
| Samsung Electronics | 6        | 7      | 3.35%   |
| HGST                | 6        | 7      | 3.35%   |
| Maxtor              | 3        | 6      | 1.68%   |
| Unknown             | 2        | 2      | 1.12%   |
| WD MediaMax         | 1        | 1      | 0.56%   |
| SABRENT             | 1        | 1      | 0.56%   |
| ASMT109x            | 1        | 1      | 0.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 37       | 64     | 30.33%  |
| Kingston            | 18       | 26     | 14.75%  |
| SanDisk             | 13       | 21     | 10.66%  |
| WDC                 | 8        | 10     | 6.56%   |
| Crucial             | 7        | 8      | 5.74%   |
| China               | 4        | 6      | 3.28%   |
| SPCC                | 3        | 5      | 2.46%   |
| PNY                 | 3        | 3      | 2.46%   |
| Patriot             | 3        | 5      | 2.46%   |
| OCZ                 | 3        | 3      | 2.46%   |
| A-DATA Technology   | 3        | 6      | 2.46%   |
| JMicron Technology  | 2        | 2      | 1.64%   |
| Intel               | 2        | 2      | 1.64%   |
| Apacer              | 2        | 2      | 1.64%   |
| AMD                 | 2        | 17     | 1.64%   |
| Zheino              | 1        | 2      | 0.82%   |
| Transcend           | 1        | 1      | 0.82%   |
| SK hynix            | 1        | 1      | 0.82%   |
| Plextor             | 1        | 1      | 0.82%   |
| Netac               | 1        | 1      | 0.82%   |
| Mushkin             | 1        | 1      | 0.82%   |
| Micron Technology   | 1        | 1      | 0.82%   |
| Lexar               | 1        | 1      | 0.82%   |
| KingDian            | 1        | 1      | 0.82%   |
| GOODRAM             | 1        | 1      | 0.82%   |
| Gigabyte Technology | 1        | 1      | 0.82%   |
| Axiom               | 1        | 1      | 0.82%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 130      | 280    | 45.14%  |
| SSD     | 95       | 193    | 32.99%  |
| NVMe    | 51       | 84     | 17.71%  |
| Unknown | 10       | 14     | 3.47%   |
| MMC     | 2        | 3      | 0.69%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 162      | 470    | 71.37%  |
| NVMe | 51       | 84     | 22.47%  |
| SAS  | 12       | 17     | 5.29%   |
| MMC  | 2        | 3      | 0.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 127      | 268    | 49.8%   |
| 0.51-1.0   | 68       | 110    | 26.67%  |
| 1.01-2.0   | 27       | 50     | 10.59%  |
| 3.01-4.0   | 19       | 26     | 7.45%   |
| 4.01-10.0  | 8        | 12     | 3.14%   |
| 2.01-3.0   | 6        | 7      | 2.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 54       | 29.35%  |
| 251-500        | 38       | 20.65%  |
| 501-1000       | 29       | 15.76%  |
| More than 3000 | 21       | 11.41%  |
| 1001-2000      | 16       | 8.7%    |
| 1-20           | 7        | 3.8%    |
| 51-100         | 7        | 3.8%    |
| 2001-3000      | 6        | 3.26%   |
| 21-50          | 3        | 1.63%   |
| Unknown        | 3        | 1.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 55       | 29.26%  |
| 101-250        | 33       | 17.55%  |
| 21-50          | 30       | 15.96%  |
| 51-100         | 19       | 10.11%  |
| 251-500        | 17       | 9.04%   |
| 1001-2000      | 12       | 6.38%   |
| 501-1000       | 9        | 4.79%   |
| More than 3000 | 7        | 3.72%   |
| 2001-3000      | 3        | 1.6%    |
| Unknown        | 3        | 1.6%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB    | 3        | 3      | 12.5%   |
| WDC WD5000AAKX-001CA0 500GB        | 2        | 2      | 8.33%   |
| WDC WD6000HLHX-01JJPV0 600GB       | 1        | 1      | 4.17%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 1        | 1      | 4.17%   |
| WDC WD5000AVCS-632DY1 500GB        | 1        | 1      | 4.17%   |
| WDC WD4003FZEX-00Z4SA0 4TB         | 1        | 1      | 4.17%   |
| WDC WD2500AAJS-60M0A0 250GB        | 1        | 1      | 4.17%   |
| WDC WD20EFRX-68EUZN0 2TB           | 1        | 2      | 4.17%   |
| WDC WD10EZEX-00RKKA0 1TB           | 1        | 1      | 4.17%   |
| Seagate ST9500325AS 500GB          | 1        | 1      | 4.17%   |
| Seagate ST5000DM000-1FK178 5TB     | 1        | 1      | 4.17%   |
| Seagate ST3500320AS 500GB          | 1        | 1      | 4.17%   |
| Seagate ST3320620AS 320GB          | 1        | 1      | 4.17%   |
| Seagate ST3160815AS 160GB          | 1        | 1      | 4.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1      | 4.17%   |
| Seagate ST1000DX001-1NS162 1TB     | 1        | 1      | 4.17%   |
| Seagate ST1000DM003-1SB102 1TB     | 1        | 1      | 4.17%   |
| Patriot Pyro m3 240GB SSD          | 1        | 1      | 4.17%   |
| Maxtor STM3250310AS 250GB          | 1        | 1      | 4.17%   |
| Maxtor 6B200M0 208GB               | 1        | 2      | 4.17%   |
| Hitachi HDS721032CLA362 320GB      | 1        | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 11       | 11     | 45.83%  |
| WDC     | 9        | 10     | 37.5%   |
| Maxtor  | 2        | 3      | 8.33%   |
| Patriot | 1        | 1      | 4.17%   |
| Hitachi | 1        | 1      | 4.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 11       | 11     | 47.83%  |
| WDC     | 9        | 10     | 39.13%  |
| Maxtor  | 2        | 3      | 8.7%    |
| Hitachi | 1        | 1      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 18       | 25     | 94.74%  |
| SSD  | 1        | 1      | 5.26%   |

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
| Detected | 123      | 406    | 63.08%  |
| Works    | 53       | 142    | 27.18%  |
| Malfunc  | 19       | 26     | 9.74%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 120      | 47.43%  |
| AMD                           | 51       | 20.16%  |
| Samsung Electronics           | 21       | 8.3%    |
| Phison Electronics            | 13       | 5.14%   |
| Marvell Technology Group      | 10       | 3.95%   |
| JMicron Technology            | 6        | 2.37%   |
| ASMedia Technology            | 6        | 2.37%   |
| SanDisk                       | 5        | 1.98%   |
| Kingston Technology Company   | 4        | 1.58%   |
| Silicon Motion                | 3        | 1.19%   |
| Micron/Crucial Technology     | 3        | 1.19%   |
| Nvidia                        | 2        | 0.79%   |
| Transcend                     | 1        | 0.4%    |
| Silicon Image                 | 1        | 0.4%    |
| Seagate Technology            | 1        | 0.4%    |
| Realtek Semiconductor         | 1        | 0.4%    |
| OCZ Technology Group          | 1        | 0.4%    |
| Micron Technology             | 1        | 0.4%    |
| Integrated Technology Express | 1        | 0.4%    |
| ADATA Technology              | 1        | 0.4%    |
| Adaptec                       | 1        | 0.4%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 32       | 10.09%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 14       | 4.42%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12       | 3.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 10       | 3.15%   |
| AMD 400 Series Chipset SATA Controller                                                  | 10       | 3.15%   |
| Intel SATA Controller [RAID mode]                                                       | 9        | 2.84%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9        | 2.84%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 9        | 2.84%   |
| AMD 500 Series Chipset SATA Controller                                                  | 9        | 2.84%   |
| Phison E12 NVMe Controller                                                              | 7        | 2.21%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7        | 2.21%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6        | 1.89%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 6        | 1.89%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6        | 1.89%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 5        | 1.58%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 1.58%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 5        | 1.58%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4        | 1.26%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 4        | 1.26%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 1.26%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 4        | 1.26%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 4        | 1.26%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4        | 1.26%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3        | 0.95%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 3        | 0.95%   |
| Kingston Company A2000 NVMe SSD                                                         | 3        | 0.95%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 3        | 0.95%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 0.95%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 0.95%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 0.95%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3        | 0.95%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 3        | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 0.95%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3        | 0.95%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3        | 0.95%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 0.95%   |
| AMD FCH SATA Controller D                                                               | 3        | 0.95%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 0.95%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 2        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 132      | 54.32%  |
| NVMe | 52       | 21.4%   |
| IDE  | 46       | 18.93%  |
| RAID | 12       | 4.94%   |
| SAS  | 1        | 0.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 120      | 69.36%  |
| AMD    | 53       | 30.64%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor          | 6        | 3.45%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 5        | 2.87%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 4        | 2.3%    |
| Intel Core i7-2600 CPU @ 3.40GHz            | 4        | 2.3%    |
| Intel Core i9-9900K CPU @ 3.60GHz           | 3        | 1.72%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 3        | 1.72%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 1.72%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 3        | 1.72%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 1.72%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 1.72%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 3        | 1.72%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 1.72%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 3        | 1.72%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 3        | 1.72%   |
| Intel Xeon CPU 5150 @ 2.66GHz               | 2        | 1.15%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 2        | 1.15%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 1.15%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 2        | 1.15%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 2        | 1.15%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 2        | 1.15%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 1.15%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 2        | 1.15%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 2        | 1.15%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2        | 1.15%   |
| Intel Core i3-3225 CPU @ 3.30GHz            | 2        | 1.15%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 1.15%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 2        | 1.15%   |
| Intel Core 2 CPU 6400 @ 2.13GHz             | 2        | 1.15%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 1.15%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 2        | 1.15%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2        | 1.15%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2        | 1.15%   |
| AMD FX-6300 Six-Core Processor              | 2        | 1.15%   |
| Intel Xeon CPU X5690 @ 3.47GHz              | 1        | 0.57%   |
| Intel Xeon CPU X5492 @ 3.40GHz              | 1        | 0.57%   |
| Intel Xeon CPU W3670 @ 3.20GHz              | 1        | 0.57%   |
| Intel Xeon CPU W3530 @ 2.80GHz              | 1        | 0.57%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1        | 0.57%   |
| Intel Xeon CPU E5-2697A v4 @ 2.60GHz        | 1        | 0.57%   |
| Intel Xeon CPU E5-2680 0 @ 2.70GHz          | 1        | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 37       | 21.26%  |
| Intel Core i5           | 29       | 16.67%  |
| AMD Ryzen 5             | 17       | 9.77%   |
| Intel Xeon              | 12       | 6.9%    |
| AMD Ryzen 7             | 11       | 6.32%   |
| Intel Core i3           | 8        | 4.6%    |
| Intel Core 2 Duo        | 6        | 3.45%   |
| Intel Core 2            | 5        | 2.87%   |
| Other                   | 4        | 2.3%    |
| Intel Pentium           | 4        | 2.3%    |
| Intel Core i9           | 4        | 2.3%    |
| AMD Ryzen 3             | 4        | 2.3%    |
| AMD FX                  | 4        | 2.3%    |
| Intel Core 2 Quad       | 3        | 1.72%   |
| Intel Celeron           | 3        | 1.72%   |
| AMD Ryzen 9             | 3        | 1.72%   |
| Intel Pentium Dual      | 2        | 1.15%   |
| AMD A4                  | 2        | 1.15%   |
| AMD A10                 | 2        | 1.15%   |
| Intel Pentium Dual-Core | 1        | 0.57%   |
| Intel Pentium 4         | 1        | 0.57%   |
| Intel Genuine           | 1        | 0.57%   |
| Intel Core m3           | 1        | 0.57%   |
| Intel Atom              | 1        | 0.57%   |
| AMD Sempron             | 1        | 0.57%   |
| AMD Ryzen Threadripper  | 1        | 0.57%   |
| AMD Phenom II X6        | 1        | 0.57%   |
| AMD Phenom II X4        | 1        | 0.57%   |
| AMD Phenom II X2        | 1        | 0.57%   |
| AMD Athlon X4           | 1        | 0.57%   |
| AMD Athlon II X3        | 1        | 0.57%   |
| AMD Athlon              | 1        | 0.57%   |
| AMD A6                  | 1        | 0.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 74       | 42.77%  |
| 2      | 36       | 20.81%  |
| 8      | 25       | 14.45%  |
| 6      | 24       | 13.87%  |
| 1      | 4        | 2.31%   |
| 16     | 3        | 1.73%   |
| 12     | 3        | 1.73%   |
| 3      | 3        | 1.73%   |
| 24     | 1        | 0.58%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 167      | 96.53%  |
| 2      | 6        | 3.47%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 104      | 59.77%  |
| 1      | 70       | 40.23%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 172      | 99.42%  |
| 32-bit         | 1        | 0.58%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 67       | 36.41%  |
| 0x306c3    | 13       | 7.07%   |
| 0x306a9    | 13       | 7.07%   |
| 0x206a7    | 10       | 5.43%   |
| 0x1067a    | 7        | 3.8%    |
| 0x506e3    | 6        | 3.26%   |
| 0x08701021 | 5        | 2.72%   |
| 0x906ec    | 4        | 2.17%   |
| 0x106e5    | 4        | 2.17%   |
| 0x0800820d | 4        | 2.17%   |
| 0xa0671    | 3        | 1.63%   |
| 0x6f6      | 3        | 1.63%   |
| 0x6f2      | 3        | 1.63%   |
| 0x906ea    | 2        | 1.09%   |
| 0x906e9    | 2        | 1.09%   |
| 0x6fd      | 2        | 1.09%   |
| 0x406f1    | 2        | 1.09%   |
| 0x206d7    | 2        | 1.09%   |
| 0x08108109 | 2        | 1.09%   |
| 0x08101016 | 2        | 1.09%   |
| 0x06000852 | 2        | 1.09%   |
| 0x010000c8 | 2        | 1.09%   |
| 0xf34      | 1        | 0.54%   |
| 0xa0655    | 1        | 0.54%   |
| 0x906ed    | 1        | 0.54%   |
| 0x706a8    | 1        | 0.54%   |
| 0x6fb      | 1        | 0.54%   |
| 0x406c4    | 1        | 0.54%   |
| 0x306f2    | 1        | 0.54%   |
| 0x30678    | 1        | 0.54%   |
| 0x206c2    | 1        | 0.54%   |
| 0x20655    | 1        | 0.54%   |
| 0x106a5    | 1        | 0.54%   |
| 0x10677    | 1        | 0.54%   |
| 0x0a50000c | 1        | 0.54%   |
| 0x08701013 | 1        | 0.54%   |
| 0x08600103 | 1        | 0.54%   |
| 0x08108102 | 1        | 0.54%   |
| 0x0810100b | 1        | 0.54%   |
| 0x08001137 | 1        | 0.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 21       | 12.14%  |
| IvyBridge     | 18       | 10.4%   |
| KabyLake      | 17       | 9.83%   |
| Zen 2         | 16       | 9.25%   |
| SandyBridge   | 15       | 8.67%   |
| Zen+          | 11       | 6.36%   |
| Penryn        | 10       | 5.78%   |
| Core          | 10       | 5.78%   |
| Skylake       | 7        | 4.05%   |
| Nehalem       | 7        | 4.05%   |
| Zen           | 6        | 3.47%   |
| K10           | 5        | 2.89%   |
| Zen 3         | 4        | 2.31%   |
| Westmere      | 4        | 2.31%   |
| Piledriver    | 4        | 2.31%   |
| Icelake       | 3        | 1.73%   |
| Excavator     | 3        | 1.73%   |
| Steamroller   | 2        | 1.16%   |
| Silvermont    | 2        | 1.16%   |
| CometLake     | 2        | 1.16%   |
| Broadwell     | 2        | 1.16%   |
| Puma          | 1        | 0.58%   |
| NetBurst      | 1        | 0.58%   |
| Goldmont plus | 1        | 0.58%   |
| Bulldozer     | 1        | 0.58%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 83       | 43.23%  |
| AMD               | 58       | 30.21%  |
| Intel             | 50       | 26.04%  |
| ASPEED Technology | 1        | 0.52%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 13       | 6.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 11       | 5.67%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 9        | 4.64%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 3.61%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 7        | 3.61%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 6        | 3.09%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 6        | 3.09%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 5        | 2.58%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 5        | 2.58%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 4        | 2.06%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4        | 2.06%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 4        | 2.06%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4        | 2.06%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4        | 2.06%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 4        | 2.06%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 1.55%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 1.55%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 3        | 1.55%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 1.55%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 1.03%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 2        | 1.03%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 1.03%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 1.03%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 2        | 1.03%   |
| Nvidia GF108 [GeForce GT 730]                                               | 2        | 1.03%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 1.03%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 2        | 1.03%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 2        | 1.03%   |
| AMD Juniper XT [Radeon HD 5770]                                             | 2        | 1.03%   |
| AMD Cypress XT [Radeon HD 5870]                                             | 2        | 1.03%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 1.03%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 2        | 1.03%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2        | 1.03%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.52%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.52%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 0.52%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 0.52%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 0.52%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1        | 0.52%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 1        | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 74       | 41.34%  |
| 1 x AMD        | 50       | 27.93%  |
| 1 x Intel      | 43       | 24.02%  |
| AMD + Nvidia   | 5        | 2.79%   |
| Intel + Nvidia | 3        | 1.68%   |
| Intel + AMD    | 2        | 1.12%   |
| 2 x Nvidia     | 1        | 0.56%   |
| 1 x ASPEED     | 1        | 0.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 108      | 60%     |
| Proprietary | 66       | 36.67%  |
| Unknown     | 6        | 3.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 81       | 44.02%  |
| 1.01-2.0   | 24       | 13.04%  |
| 7.01-8.0   | 21       | 11.41%  |
| 3.01-4.0   | 19       | 10.33%  |
| 5.01-6.0   | 16       | 8.7%    |
| 0.51-1.0   | 12       | 6.52%   |
| 0.01-0.5   | 9        | 4.89%   |
| 2.01-3.0   | 1        | 0.54%   |
| 8.01-16.0  | 1        | 0.54%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 39       | 20.21%  |
| Dell                 | 25       | 12.95%  |
| Hewlett-Packard      | 12       | 6.22%   |
| Goldstar             | 11       | 5.7%    |
| AOC                  | 11       | 5.7%    |
| Ancor Communications | 11       | 5.7%    |
| Acer                 | 10       | 5.18%   |
| BenQ                 | 9        | 4.66%   |
| Philips              | 6        | 3.11%   |
| Unknown              | 5        | 2.59%   |
| LG Electronics       | 5        | 2.59%   |
| Idek Iiyama          | 4        | 2.07%   |
| ASUSTek Computer     | 4        | 2.07%   |
| Sony                 | 3        | 1.55%   |
| Medion               | 3        | 1.55%   |
| Iiyama               | 3        | 1.55%   |
| ViewSonic            | 2        | 1.04%   |
| Sceptre Tech         | 2        | 1.04%   |
| SANYO                | 2        | 1.04%   |
| MStar                | 2        | 1.04%   |
| Fujitsu Siemens      | 2        | 1.04%   |
| Eizo                 | 2        | 1.04%   |
| AGO                  | 2        | 1.04%   |
| Vizio                | 1        | 0.52%   |
| VIZ                  | 1        | 0.52%   |
| Unknown (XXX)        | 1        | 0.52%   |
| Sun                  | 1        | 0.52%   |
| Pioneer Electronic   | 1        | 0.52%   |
| Panasonic            | 1        | 0.52%   |
| NEC Computers        | 1        | 0.52%   |
| MPI                  | 1        | 0.52%   |
| Microstep            | 1        | 0.52%   |
| Lenovo               | 1        | 0.52%   |
| Insignia             | 1        | 0.52%   |
| Huion                | 1        | 0.52%   |
| HKC                  | 1        | 0.52%   |
| Daewoo               | 1        | 0.52%   |
| CHD                  | 1        | 0.52%   |
| AUS                  | 1        | 0.52%   |
| Apple                | 1        | 0.52%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S27B550 SAM091B 1920x1080 598x336mm 27.0-inch     | 2        | 0.91%   |
| Samsung Electronics LCD Monitor SAM0BB4 3840x2160 890x500mm 40.2-inch | 2        | 0.91%   |
| Samsung Electronics LCD Monitor C34H89x 3440x1440                     | 2        | 0.91%   |
| MStar Demo MST0030 1366x768 708x398mm 32.0-inch                       | 2        | 0.91%   |
| Medion MD20338 MED3943 1600x900 462x272mm 21.1-inch                   | 2        | 0.91%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2        | 0.91%   |
| Dell D2721H DEL2013 1920x1080 598x336mm 27.0-inch                     | 2        | 0.91%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 2        | 0.91%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 2        | 0.91%   |
| Ancor Communications ASUS PA238 ACI23B1 1920x1080 509x286mm 23.0-inch | 2        | 0.91%   |
| Vizio E320VT VIZ0067 1920x1080 698x392mm 31.5-inch                    | 1        | 0.46%   |
| Vizio D40u-D1 VIZ1011 3840x2160 878x485mm 39.5-inch                   | 1        | 0.46%   |
| VIZ LCD Monitor M50-C1 3840x2160                                      | 1        | 0.46%   |
| ViewSonic VX2476 Series VSC9939 1920x1080 527x296mm 23.8-inch         | 1        | 0.46%   |
| ViewSonic VA903 SERIES VSC111E 1280x1024 376x301mm 19.0-inch          | 1        | 0.46%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                 | 1        | 0.46%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 1        | 0.46%   |
| Unknown LCD Monitor SAMSUNG 1366x768                                  | 1        | 0.46%   |
| Unknown LCD Monitor SAMSUNG                                           | 1        | 0.46%   |
| Unknown LCD Monitor GTW KX2153                                        | 1        | 0.46%   |
| Unknown LCD Monitor EMA E202HL                                        | 1        | 0.46%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch         | 1        | 0.46%   |
| Sun X7202A SUN0595 1280x1024 376x301mm 19.0-inch                      | 1        | 0.46%   |
| Sony TV SNYEE01 1920x1080                                             | 1        | 0.46%   |
| Sony SDM-HS93 SNY1190 1280x1024 357x286mm 18.0-inch                   | 1        | 0.46%   |
| Sony LCD Monitor TV  *07 5760x2160                                    | 1        | 0.46%   |
| Sony LCD Monitor TV  *07                                              | 1        | 0.46%   |
| Sceptre Tech Sceptre B34 SPT0D52 2560x1080 797x334mm 34.0-inch        | 1        | 0.46%   |
| Sceptre Tech E24 SPT099D 1920x1080 409x230mm 18.5-inch                | 1        | 0.46%   |
| Sceptre Tech E20 SPT080D 1600x900 434x236mm 19.4-inch                 | 1        | 0.46%   |
| SANYO LCD-24XH7** SAN0B92 1920x540 531x299mm 24.0-inch                | 1        | 0.46%   |
| SANYO LCD SAN0A12 1920x540                                            | 1        | 0.46%   |
| Samsung Electronics T24C550 SAM0AA1 1920x1080 521x293mm 23.5-inch     | 1        | 0.46%   |
| Samsung Electronics SyncMaster SAM0653 1920x1080                      | 1        | 0.46%   |
| Samsung Electronics SyncMaster SAM060C 1920x1080 510x290mm 23.1-inch  | 1        | 0.46%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                      | 1        | 0.46%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch  | 1        | 0.46%   |
| Samsung Electronics SyncMaster SAM03EE 1680x1050                      | 1        | 0.46%   |
| Samsung Electronics SyncMaster SAM0346 1680x1050 459x296mm 21.5-inch  | 1        | 0.46%   |
| Samsung Electronics SyncMaster SAM02B6 1920x1200 518x324mm 24.1-inch  | 1        | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 83       | 42.13%  |
| 1280x1024 (SXGA)   | 15       | 7.61%   |
| 3840x2160 (4K)     | 13       | 6.6%    |
| Unknown            | 13       | 6.6%    |
| 1366x768 (WXGA)    | 10       | 5.08%   |
| 1920x1200 (WUXGA)  | 8        | 4.06%   |
| 1680x1050 (WSXGA+) | 7        | 3.55%   |
| 3840x1080          | 6        | 3.05%   |
| 3440x1440          | 6        | 3.05%   |
| 2560x1440 (QHD)    | 6        | 3.05%   |
| 2560x1080          | 6        | 3.05%   |
| 1920x540           | 3        | 1.52%   |
| 1600x900 (HD+)     | 3        | 1.52%   |
| 3520x1080          | 2        | 1.02%   |
| 2560x1600          | 2        | 1.02%   |
| 5760x2160          | 1        | 0.51%   |
| 4480x1080          | 1        | 0.51%   |
| 3840x1440          | 1        | 0.51%   |
| 3840x1200          | 1        | 0.51%   |
| 3600x1080          | 1        | 0.51%   |
| 3280x1080          | 1        | 0.51%   |
| 3200x1800 (QHD+)   | 1        | 0.51%   |
| 2646x768           | 1        | 0.51%   |
| 2560x1024          | 1        | 0.51%   |
| 2390x768           | 1        | 0.51%   |
| 2048x1152          | 1        | 0.51%   |
| 1600x1200          | 1        | 0.51%   |
| 1400x1050          | 1        | 0.51%   |
| 1280x720 (HD)      | 1        | 0.51%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 44       | 23.28%  |
| 24      | 25       | 13.23%  |
| 27      | 24       | 12.7%   |
| 23      | 21       | 11.11%  |
| 21      | 10       | 5.29%   |
| 34      | 8        | 4.23%   |
| 19      | 8        | 4.23%   |
| 17      | 6        | 3.17%   |
| 15      | 5        | 2.65%   |
| 18      | 4        | 2.12%   |
| 54      | 3        | 1.59%   |
| 31      | 3        | 1.59%   |
| 22      | 3        | 1.59%   |
| 20      | 3        | 1.59%   |
| 84      | 2        | 1.06%   |
| 52      | 2        | 1.06%   |
| 33      | 2        | 1.06%   |
| 28      | 2        | 1.06%   |
| 12      | 2        | 1.06%   |
| 72      | 1        | 0.53%   |
| 63      | 1        | 0.53%   |
| 48      | 1        | 0.53%   |
| 47      | 1        | 0.53%   |
| 46      | 1        | 0.53%   |
| 40      | 1        | 0.53%   |
| 37      | 1        | 0.53%   |
| 29      | 1        | 0.53%   |
| 25      | 1        | 0.53%   |
| 16      | 1        | 0.53%   |
| 14      | 1        | 0.53%   |
| 13      | 1        | 0.53%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 65       | 34.57%  |
| Unknown     | 44       | 23.4%   |
| 401-500     | 21       | 11.17%  |
| 601-700     | 11       | 5.85%   |
| 301-350     | 11       | 5.85%   |
| 701-800     | 10       | 5.32%   |
| 1001-1500   | 9        | 4.79%   |
| 351-400     | 8        | 4.26%   |
| 201-300     | 4        | 2.13%   |
| 1501-2000   | 3        | 1.6%    |
| 801-900     | 2        | 1.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 90       | 51.43%  |
| Unknown | 40       | 22.86%  |
| 16/10   | 14       | 8%      |
| 5/4     | 12       | 6.86%   |
| 21/9    | 9        | 5.14%   |
| 4/3     | 6        | 3.43%   |
| 32/9    | 2        | 1.14%   |
| 6/5     | 1        | 0.57%   |
| 1.00    | 1        | 0.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 44       | 23.78%  |
| 201-250        | 43       | 23.24%  |
| 301-350        | 24       | 12.97%  |
| 151-200        | 16       | 8.65%   |
| 351-500        | 15       | 8.11%   |
| 251-300        | 10       | 5.41%   |
| More than 1000 | 9        | 4.86%   |
| 141-150        | 9        | 4.86%   |
| 501-1000       | 5        | 2.7%    |
| 101-110        | 4        | 2.16%   |
| 71-80          | 3        | 1.62%   |
| 91-100         | 2        | 1.08%   |
| 131-140        | 1        | 0.54%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 97       | 54.49%  |
| Unknown       | 44       | 24.72%  |
| 101-120       | 18       | 10.11%  |
| 1-50          | 8        | 4.49%   |
| 121-160       | 7        | 3.93%   |
| 161-240       | 3        | 1.69%   |
| More than 240 | 1        | 0.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 125      | 70.62%  |
| 2     | 39       | 22.03%  |
| 0     | 9        | 5.08%   |
| 3     | 3        | 1.69%   |
| 4     | 1        | 0.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 99       | 39.29%  |
| Intel                           | 89       | 35.32%  |
| Broadcom                        | 15       | 5.95%   |
| Qualcomm Atheros                | 14       | 5.56%   |
| Ralink Technology               | 7        | 2.78%   |
| Microsoft                       | 4        | 1.59%   |
| D-Link System                   | 3        | 1.19%   |
| Ralink                          | 2        | 0.79%   |
| Qualcomm Atheros Communications | 2        | 0.79%   |
| Nvidia                          | 2        | 0.79%   |
| NetGear                         | 2        | 0.79%   |
| Linksys                         | 2        | 0.79%   |
| D-Link                          | 2        | 0.79%   |
| Belkin Components               | 2        | 0.79%   |
| Xiaomi                          | 1        | 0.4%    |
| Wacom                           | 1        | 0.4%    |
| Mercucys                        | 1        | 0.4%    |
| MediaTek                        | 1        | 0.4%    |
| Exar                            | 1        | 0.4%    |
| Broadcom Limited                | 1        | 0.4%    |
| ASIX Electronics                | 1        | 0.4%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 72       | 25.17%  |
| Intel Wi-Fi 6 AX200                                               | 15       | 5.24%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9        | 3.15%   |
| Intel I211 Gigabit Network Connection                             | 9        | 3.15%   |
| Intel Ethernet Connection I217-LM                                 | 8        | 2.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8        | 2.8%    |
| Intel Ethernet Connection (7) I219-V                              | 7        | 2.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 6        | 2.1%    |
| Intel Wireless-AC 9260                                            | 5        | 1.75%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 1.75%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 1.75%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 5        | 1.75%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 1.4%    |
| Intel Ethernet Controller I225-V                                  | 4        | 1.4%    |
| Intel Ethernet Connection (2) I218-V                              | 4        | 1.4%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 1.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 1.05%   |
| Realtek 802.11ac NIC                                              | 3        | 1.05%   |
| Intel I210 Gigabit Network Connection                             | 3        | 1.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3        | 1.05%   |
| Intel 82566DM Gigabit Network Connection                          | 3        | 1.05%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 3        | 1.05%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2        | 0.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2        | 0.7%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 2        | 0.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 0.7%    |
| Realtek RTL8188EE Wireless Network Adapter                        | 2        | 0.7%    |
| Ralink MT7601U Wireless Adapter                                   | 2        | 0.7%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.7%    |
| Qualcomm Atheros AR9271 802.11n                                   | 2        | 0.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2        | 0.7%    |
| Nvidia MCP61 Ethernet                                             | 2        | 0.7%    |
| Microsoft Xbox 360 Wireless Adapter                               | 2        | 0.7%    |
| Linksys WUSB54GC v1 802.11g Adapter [Ralink RT73]                 | 2        | 0.7%    |
| Intel Wireless 7265                                               | 2        | 0.7%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2        | 0.7%    |
| Intel Ethernet Connection I217-V                                  | 2        | 0.7%    |
| Intel Ethernet Connection (14) I219-V                             | 2        | 0.7%    |
| Intel 82578DC Gigabit Network Connection                          | 2        | 0.7%    |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 2        | 0.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 36       | 37.11%  |
| Realtek Semiconductor           | 18       | 18.56%  |
| Broadcom                        | 8        | 8.25%   |
| Ralink Technology               | 7        | 7.22%   |
| Qualcomm Atheros                | 7        | 7.22%   |
| Microsoft                       | 4        | 4.12%   |
| Ralink                          | 2        | 2.06%   |
| Qualcomm Atheros Communications | 2        | 2.06%   |
| NetGear                         | 2        | 2.06%   |
| Linksys                         | 2        | 2.06%   |
| D-Link System                   | 2        | 2.06%   |
| D-Link                          | 2        | 2.06%   |
| Belkin Components               | 2        | 2.06%   |
| Wacom                           | 1        | 1.03%   |
| Mercucys                        | 1        | 1.03%   |
| MediaTek                        | 1        | 1.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                                   | 15       | 15%     |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 6        | 6%      |
| Intel Wireless-AC 9260                                                                | 5        | 5%      |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                    | 5        | 5%      |
| Realtek 802.11ac NIC                                                                  | 3        | 3%      |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 3        | 3%      |
| Realtek RTL88x2bu [AC1200 Techkey]                                                    | 2        | 2%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 2        | 2%      |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                            | 2        | 2%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 2        | 2%      |
| Realtek RTL8188EE Wireless Network Adapter                                            | 2        | 2%      |
| Ralink MT7601U Wireless Adapter                                                       | 2        | 2%      |
| Qualcomm Atheros AR9271 802.11n                                                       | 2        | 2%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 2        | 2%      |
| Microsoft Xbox 360 Wireless Adapter                                                   | 2        | 2%      |
| Linksys WUSB54GC v1 802.11g Adapter [Ralink RT73]                                     | 2        | 2%      |
| Intel Wireless 7265                                                                   | 2        | 2%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 2        | 2%      |
| Wacom ACK-40401 [Wireless Accessory Kit]                                              | 1        | 1%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1        | 1%      |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                              | 1        | 1%      |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                   | 1        | 1%      |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                            | 1        | 1%      |
| Realtek RTL8192CE PCIe Wireless Network Adapter                                       | 1        | 1%      |
| Realtek RTL8191SEvB Wireless LAN Controller                                           | 1        | 1%      |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1        | 1%      |
| Ralink RT5372 Wireless Adapter                                                        | 1        | 1%      |
| Ralink RT5370 Wireless Adapter                                                        | 1        | 1%      |
| Ralink RT3072 Wireless Adapter                                                        | 1        | 1%      |
| Ralink RT2870/RT3070 Wireless Adapter                                                 | 1        | 1%      |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                     | 1        | 1%      |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                             | 1        | 1%      |
| Ralink RT3060 Wireless 802.11n 1T/1R                                                  | 1        | 1%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 1        | 1%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 1        | 1%      |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1        | 1%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1        | 1%      |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1        | 1%      |
| NetGear WNA3100M(v1) Wireless-N 300 [Realtek RTL8192CU]                               | 1        | 1%      |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                                       | 1        | 1%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 89       | 49.72%  |
| Intel                 | 70       | 39.11%  |
| Qualcomm Atheros      | 7        | 3.91%   |
| Broadcom              | 7        | 3.91%   |
| Nvidia                | 2        | 1.12%   |
| Xiaomi                | 1        | 0.56%   |
| D-Link System         | 1        | 0.56%   |
| Broadcom Limited      | 1        | 0.56%   |
| ASIX Electronics      | 1        | 0.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 72       | 38.92%  |
| Realtek RTL8125 2.5GbE Controller                                 | 9        | 4.86%   |
| Intel I211 Gigabit Network Connection                             | 9        | 4.86%   |
| Intel Ethernet Connection I217-LM                                 | 8        | 4.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8        | 4.32%   |
| Intel Ethernet Connection (7) I219-V                              | 7        | 3.78%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 2.7%    |
| Intel 82579V Gigabit Network Connection                           | 5        | 2.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 2.16%   |
| Intel Ethernet Controller I225-V                                  | 4        | 2.16%   |
| Intel Ethernet Connection (2) I218-V                              | 4        | 2.16%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 2.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 1.62%   |
| Intel I210 Gigabit Network Connection                             | 3        | 1.62%   |
| Intel 82566DM Gigabit Network Connection                          | 3        | 1.62%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 3        | 1.62%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 1.08%   |
| Nvidia MCP61 Ethernet                                             | 2        | 1.08%   |
| Intel Ethernet Connection I217-V                                  | 2        | 1.08%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 1.08%   |
| Intel 82578DC Gigabit Network Connection                          | 2        | 1.08%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 2        | 1.08%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2        | 1.08%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.54%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.54%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1        | 0.54%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.54%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.54%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.54%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.54%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.54%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 0.54%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 0.54%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 0.54%   |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 0.54%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1        | 0.54%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 1        | 0.54%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1        | 0.54%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 170      | 65.38%  |
| WiFi     | 89       | 34.23%  |
| Modem    | 1        | 0.38%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 130      | 70.65%  |
| WiFi     | 54       | 29.35%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 107      | 61.85%  |
| 2     | 53       | 30.64%  |
| 3     | 12       | 6.94%   |
| 0     | 1        | 0.58%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 147      | 83.05%  |
| Yes  | 30       | 16.95%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 35       | 46.67%  |
| Cambridge Silicon Radio         | 22       | 29.33%  |
| Broadcom                        | 4        | 5.33%   |
| Qualcomm Atheros Communications | 3        | 4%      |
| ASUSTek Computer                | 3        | 4%      |
| Realtek Semiconductor           | 2        | 2.67%   |
| Belkin Components               | 2        | 2.67%   |
| MediaTek                        | 1        | 1.33%   |
| Lite-On Technology              | 1        | 1.33%   |
| IMC Networks                    | 1        | 1.33%   |
| Apple                           | 1        | 1.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 22       | 29.33%  |
| Intel AX200 Bluetooth                                 | 15       | 20%     |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 5        | 6.67%   |
| Intel Wireless-AC 3168 Bluetooth                      | 5        | 6.67%   |
| Intel Bluetooth wireless interface                    | 4        | 5.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 3        | 4%      |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 3        | 4%      |
| Qualcomm Atheros AR3011 Bluetooth                     | 2        | 2.67%   |
| Intel AX210 Bluetooth                                 | 2        | 2.67%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 2        | 2.67%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1        | 1.33%   |
| Realtek Bluetooth Radio                               | 1        | 1.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 1        | 1.33%   |
| MediaTek Wireless_Device                              | 1        | 1.33%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 1        | 1.33%   |
| Intel AX201 Bluetooth                                 | 1        | 1.33%   |
| IMC Networks Bluetooth Radio                          | 1        | 1.33%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 1        | 1.33%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1        | 1.33%   |
| ASUS Bluetooth Radio                                  | 1        | 1.33%   |
| ASUS Bluetooth Adapter                                | 1        | 1.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 1        | 1.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 115      | 37.22%  |
| Nvidia                     | 80       | 25.89%  |
| AMD                        | 74       | 23.95%  |
| C-Media Electronics        | 6        | 1.94%   |
| Logitech                   | 5        | 1.62%   |
| Creative Labs              | 4        | 1.29%   |
| Creative Technology        | 3        | 0.97%   |
| JMTek                      | 2        | 0.65%   |
| Texas Instruments          | 1        | 0.32%   |
| SteelSeries ApS            | 1        | 0.32%   |
| Sennheiser Communications  | 1        | 0.32%   |
| Samson Technologies        | 1        | 0.32%   |
| Realtek Semiconductor      | 1        | 0.32%   |
| PreSonus Audio Electronics | 1        | 0.32%   |
| OPPO Electronics           | 1        | 0.32%   |
| Native Instruments         | 1        | 0.32%   |
| Nam Tai E&E Products       | 1        | 0.32%   |
| Microsoft                  | 1        | 0.32%   |
| M-Audio                    | 1        | 0.32%   |
| Kingston Technology        | 1        | 0.32%   |
| GN Netcom                  | 1        | 0.32%   |
| Giga-Byte Technology       | 1        | 0.32%   |
| Focusrite-Novation         | 1        | 0.32%   |
| Bose                       | 1        | 0.32%   |
| Blue Microphones           | 1        | 0.32%   |
| Barco Display Systems      | 1        | 0.32%   |
| ASUSTek Computer           | 1        | 0.32%   |
| Astro Gaming               | 1        | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 16       | 4.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 15       | 4.21%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 14       | 3.93%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 14       | 3.93%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 13       | 3.65%   |
| AMD Family 17h/19h HD Audio Controller                                     | 12       | 3.37%   |
| Nvidia GP106 High Definition Audio Controller                              | 10       | 2.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 10       | 2.81%   |
| Intel Cannon Lake PCH cAVS                                                 | 10       | 2.81%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 9        | 2.53%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 8        | 2.25%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7        | 1.97%   |
| Nvidia TU106 High Definition Audio Controller                              | 6        | 1.69%   |
| Nvidia GP108 High Definition Audio Controller                              | 6        | 1.69%   |
| Nvidia GP107GL High Definition Audio Controller                            | 6        | 1.69%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 6        | 1.69%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6        | 1.69%   |
| Intel 200 Series PCH HD Audio                                              | 6        | 1.69%   |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 1.4%    |
| Nvidia GP104 High Definition Audio Controller                              | 5        | 1.4%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5        | 1.4%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 5        | 1.4%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 5        | 1.4%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5        | 1.4%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5        | 1.4%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5        | 1.4%    |
| AMD Navi 10 HDMI Audio                                                     | 5        | 1.4%    |
| AMD FCH Azalia Controller                                                  | 5        | 1.4%    |
| Nvidia TU104 HD Audio Controller                                           | 4        | 1.12%   |
| Nvidia GM206 High Definition Audio Controller                              | 4        | 1.12%   |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 1.12%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 4        | 1.12%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 4        | 1.12%   |
| Nvidia High Definition Audio Controller                                    | 3        | 0.84%   |
| Nvidia GM204 High Definition Audio Controller                              | 3        | 0.84%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3        | 0.84%   |
| Nvidia GK106 HDMI Audio Controller                                         | 3        | 0.84%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 0.84%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3        | 0.84%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3        | 0.84%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 18       | 17.48%  |
| Samsung Electronics | 13       | 12.62%  |
| Crucial             | 12       | 11.65%  |
| Unknown             | 10       | 9.71%   |
| SK hynix            | 10       | 9.71%   |
| Corsair             | 8        | 7.77%   |
| G.Skill             | 6        | 5.83%   |
| Micron Technology   | 5        | 4.85%   |
| Team                | 4        | 3.88%   |
| A-DATA Technology   | 4        | 3.88%   |
| Transcend           | 2        | 1.94%   |
| GOODRAM             | 2        | 1.94%   |
| Unknown (0x873E)    | 1        | 0.97%   |
| Timetec             | 1        | 0.97%   |
| Sesame              | 1        | 0.97%   |
| PNY                 | 1        | 0.97%   |
| Nanya Technology    | 1        | 0.97%   |
| Elpida              | 1        | 0.97%   |
| Avant               | 1        | 0.97%   |
| Apacer              | 1        | 0.97%   |
| Unknown             | 1        | 0.97%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                    | 2        | 1.85%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s   | 2        | 1.85%   |
| Kingston RAM 9905403-199.A00LF 4GB DIMM DDR3 1600MT/s   | 2        | 1.85%   |
| Crucial RAM BLS4G4D240FSB.8FBD 4GB DIMM DDR4 2472MT/s   | 2        | 1.85%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s  | 2        | 1.85%   |
| A-DATA RAM DDR4 3000 16GB DIMM DDR4 3600MT/s            | 2        | 1.85%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s            | 1        | 0.93%   |
| Unknown RAM Module 512MB DIMM 533MT/s                   | 1        | 0.93%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                    | 1        | 0.93%   |
| Unknown RAM Module 4096MB DIMM DDR 1066MT/s             | 1        | 0.93%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                  | 1        | 0.93%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 1        | 0.93%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s             | 1        | 0.93%   |
| Unknown RAM Module 2048MB DIMM DDR 1066MT/s             | 1        | 0.93%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                  | 1        | 0.93%   |
| Unknown RAM Module 1024MB DIMM DDR2                     | 1        | 0.93%   |
| Unknown RAM DDR3 1600 8G 8192MB DIMM DDR3 1600MT/s      | 1        | 0.93%   |
| Unknown (0x873E) RAM Module 8192MB DIMM DDR3 1333MT/s   | 1        | 0.93%   |
| Transcend RAM TS256MLK64V3U 2GB DIMM DDR3 1066MT/s      | 1        | 0.93%   |
| Transcend RAM Module 2048MB DIMM DDR2 800MT/s           | 1        | 0.93%   |
| Timetec RAM ED3-1600 8192MB DIMM DDR3 1600MT/s          | 1        | 0.93%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3733MT/s     | 1        | 0.93%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 3000MT/s      | 1        | 0.93%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 3007MT/s      | 1        | 0.93%   |
| Team RAM Elite-1333 4GB DIMM 1333MT/s                   | 1        | 0.93%   |
| SK hynix RAM Module 4096MB FB-DIMM DDR2 667MT/s         | 1        | 0.93%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s              | 1        | 0.93%   |
| SK hynix RAM Module 1GB DIMM DDR3 1333MT/s              | 1        | 0.93%   |
| SK hynix RAM Module 1024MB DIMM DDR3 1333MT/s           | 1        | 0.93%   |
| SK hynix RAM HYMP512U64CP8-Y5 1GB DIMM DDR2 1331MT/s    | 1        | 0.93%   |
| SK hynix RAM HYMP112U64CP8-Y5 1024MB DIMM DDR2 1639MT/s | 1        | 0.93%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s    | 1        | 0.93%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s    | 1        | 0.93%   |
| SK hynix RAM HMA81GR7MFR8N-UH 8GB RIMM DDR4 2400MT/s    | 1        | 0.93%   |
| SK hynix RAM HMA41GR7AFR4N-UH 8GB DIMM DDR4 2400MT/s    | 1        | 0.93%   |
| Sesame RAM S939A2UGS-ITR 8GB DIMM DDR3 1600MT/s         | 1        | 0.93%   |
| Samsung RAM Module 2GB FB-DIMM DDR2 667MT/s             | 1        | 0.93%   |
| Samsung RAM Module 1GB DIMM DDR3 1333MT/s               | 1        | 0.93%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s   | 1        | 0.93%   |
| Samsung RAM M393A4K40CB1-CRC 32GB DIMM DDR4 2400MT/s    | 1        | 0.93%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 36       | 41.86%  |
| DDR4    | 35       | 40.7%   |
| DDR2    | 6        | 6.98%   |
| SDRAM   | 5        | 5.81%   |
| Unknown | 3        | 3.49%   |
| DDR     | 1        | 1.16%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 78       | 91.76%  |
| SODIMM  | 4        | 4.71%   |
| FB-DIMM | 2        | 2.35%   |
| RIMM    | 1        | 1.18%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 32       | 34.04%  |
| 4096  | 24       | 25.53%  |
| 16384 | 13       | 13.83%  |
| 2048  | 13       | 13.83%  |
| 32768 | 5        | 5.32%   |
| 1024  | 5        | 5.32%   |
| 512   | 2        | 2.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 26       | 26.53%  |
| 3200    | 12       | 12.24%  |
| 1333    | 11       | 11.22%  |
| 2400    | 5        | 5.1%    |
| 800     | 4        | 4.08%   |
| 2667    | 3        | 3.06%   |
| 1066    | 3        | 3.06%   |
| 667     | 3        | 3.06%   |
| Unknown | 3        | 3.06%   |
| 3600    | 2        | 2.04%   |
| 3400    | 2        | 2.04%   |
| 3266    | 2        | 2.04%   |
| 3000    | 2        | 2.04%   |
| 2472    | 2        | 2.04%   |
| 2133    | 2        | 2.04%   |
| 1800    | 2        | 2.04%   |
| 3866    | 1        | 1.02%   |
| 3733    | 1        | 1.02%   |
| 3666    | 1        | 1.02%   |
| 3500    | 1        | 1.02%   |
| 3007    | 1        | 1.02%   |
| 2666    | 1        | 1.02%   |
| 2134    | 1        | 1.02%   |
| 2048    | 1        | 1.02%   |
| 1866    | 1        | 1.02%   |
| 1639    | 1        | 1.02%   |
| 1334    | 1        | 1.02%   |
| 1331    | 1        | 1.02%   |
| 533     | 1        | 1.02%   |
| 400     | 1        | 1.02%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 3        | 50%     |
| Sharp           | 1        | 16.67%  |
| Hewlett-Packard | 1        | 16.67%  |
| Fuji Xerox      | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Sharp AL-2030                 | 1        | 16.67%  |
| HP Deskjet 2540 series        | 1        | 16.67%  |
| Fuji Xerox DocuPrint CM305 df | 1        | 16.67%  |
| Canon TR7500 series           | 1        | 16.67%  |
| Canon MF4010 series           | 1        | 16.67%  |
| Canon MF240 Series UFRII LT   | 1        | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 120 | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 14       | 38.89%  |
| Microdia                      | 4        | 11.11%  |
| Microsoft                     | 3        | 8.33%   |
| Generalplus Technology        | 3        | 8.33%   |
| Tobii Technology AB           | 1        | 2.78%   |
| Sunplus Innovation Technology | 1        | 2.78%   |
| Samsung Electronics           | 1        | 2.78%   |
| Realtek Semiconductor         | 1        | 2.78%   |
| OPPO Electronics              | 1        | 2.78%   |
| Linux Foundation              | 1        | 2.78%   |
| LG Electronics                | 1        | 2.78%   |
| IPEVO                         | 1        | 2.78%   |
| Guillemot                     | 1        | 2.78%   |
| Dell                          | 1        | 2.78%   |
| Cubeternet                    | 1        | 2.78%   |
| ARC International             | 1        | 2.78%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920              | 4        | 11.11%  |
| Microsoft LifeCam HD-3000                | 2        | 5.56%   |
| Microdia Camera                          | 2        | 5.56%   |
| Logitech Webcam C270                     | 2        | 5.56%   |
| Logitech Webcam B500                     | 2        | 5.56%   |
| Generalplus GENERAL WEBCAM               | 2        | 5.56%   |
| Tobii AB EyeChip                         | 1        | 2.78%   |
| Sunplus HD 720P webcam                   | 1        | 2.78%   |
| Samsung Galaxy A5 (MTP)                  | 1        | 2.78%   |
| Realtek Web Camera                       | 1        | 2.78%   |
| OPPO 8T TMO                              | 1        | 2.78%   |
| Microsoft LifeCam Cinema                 | 1        | 2.78%   |
| Microdia USB camera                      | 1        | 2.78%   |
| Microdia Integrated Camera               | 1        | 2.78%   |
| Logitech Webcam C925e                    | 1        | 2.78%   |
| Logitech Webcam C170                     | 1        | 2.78%   |
| Logitech QuickCam Pro for Notebooks      | 1        | 2.78%   |
| Logitech Logitech Webcam C160            | 1        | 2.78%   |
| Logitech HD Webcam C910                  | 1        | 2.78%   |
| Logitech B525 HD Webcam                  | 1        | 2.78%   |
| Linux Foundation EEM Gadget              | 1        | 2.78%   |
| LG Optimus (Various Models) MTP Mode     | 1        | 2.78%   |
| IPEVO V4K                                | 1        | 2.78%   |
| Guillemot Hercules HD Sunset             | 1        | 2.78%   |
| Generalplus 808 Camera #9 (web-cam mode) | 1        | 2.78%   |
| Dell Webcam WB7022                       | 1        | 2.78%   |
| Cubeternet GL-UPC822 UVC WebCam          | 1        | 2.78%   |
| ARC International Camera                 | 1        | 2.78%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

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
| 0     | 156      | 88.64%  |
| 1     | 14       | 7.95%   |
| 2     | 3        | 1.7%    |
| 9     | 1        | 0.57%   |
| 4     | 1        | 0.57%   |
| 3     | 1        | 0.57%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 8        | 27.59%  |
| Net/wireless             | 6        | 20.69%  |
| Unassigned class         | 4        | 13.79%  |
| Sound                    | 4        | 13.79%  |
| Communication controller | 2        | 6.9%    |
| Bluetooth                | 2        | 6.9%    |
| Net/ethernet             | 1        | 3.45%   |
| Card reader              | 1        | 3.45%   |
| Camera                   | 1        | 3.45%   |

