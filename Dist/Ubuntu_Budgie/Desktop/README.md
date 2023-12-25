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

Total: 293

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| Toshiba    | STI 010433                  | [c172f735d2](https://linux-hardware.org/?probe=c172f735d2) | Nov 15, 2023 |
| HP         | 8309                        | [88e1f5e70c](https://linux-hardware.org/?probe=88e1f5e70c) | Nov 13, 2023 |
| Fujitsu    | D3222-A1 S26361-D3222-A1    | [64ce1a549b](https://linux-hardware.org/?probe=64ce1a549b) | Nov 13, 2023 |
| MSI        | A68HM-E33 V2                | [e1edc2410b](https://linux-hardware.org/?probe=e1edc2410b) | Nov 03, 2023 |
| Dell       | 0M5DCD A00                  | [b3a6489f94](https://linux-hardware.org/?probe=b3a6489f94) | Oct 20, 2023 |
| HP         | 8054                        | [66ad5550d1](https://linux-hardware.org/?probe=66ad5550d1) | Oct 10, 2023 |
| ASUSTek    | Z97M-PLUS                   | [01e90212e5](https://linux-hardware.org/?probe=01e90212e5) | Sep 20, 2023 |
| MSI        | A320M-A PRO                 | [6588973c54](https://linux-hardware.org/?probe=6588973c54) | Sep 19, 2023 |
| Lenovo     | SHARKBAY 0B98401 PRO        | [4fe996e64f](https://linux-hardware.org/?probe=4fe996e64f) | Aug 29, 2023 |
| MSI        | H510M-A PRO                 | [1e39da3f6e](https://linux-hardware.org/?probe=1e39da3f6e) | Aug 18, 2023 |
| Gigabyte   | H410M S2H V3                | [e31d121593](https://linux-hardware.org/?probe=e31d121593) | Jul 15, 2023 |
| Gigabyte   | H410M S2H V3                | [9c3135decf](https://linux-hardware.org/?probe=9c3135decf) | Jul 10, 2023 |
| ASUSTek    | H81M-R                      | [12561e59a4](https://linux-hardware.org/?probe=12561e59a4) | Jul 07, 2023 |
| ASUSTek    | H81M-R                      | [48526cd359](https://linux-hardware.org/?probe=48526cd359) | Jul 07, 2023 |
| Fujitsu    | D3233-A1 S26361-D3233-A1    | [4622902df7](https://linux-hardware.org/?probe=4622902df7) | Jun 17, 2023 |
| Gigabyte   | GA-890GPA-UD3H              | [f04b28a0e5](https://linux-hardware.org/?probe=f04b28a0e5) | Jun 10, 2023 |
| ASRock     | B450M Steel Legend          | [5d75bba35e](https://linux-hardware.org/?probe=5d75bba35e) | Jun 06, 2023 |
| Gigabyte   | H310M HD2                   | [b28787ecb7](https://linux-hardware.org/?probe=b28787ecb7) | Jun 04, 2023 |
| Dell       | 024JD7 A00                  | [904e4e2a0d](https://linux-hardware.org/?probe=904e4e2a0d) | May 15, 2023 |
| ASUSTek    | ROG STRIX X670E-E GAMING... | [f87233a295](https://linux-hardware.org/?probe=f87233a295) | Apr 29, 2023 |
| Intel      | H61                         | [b8f0acdf61](https://linux-hardware.org/?probe=b8f0acdf61) | Apr 28, 2023 |
| ASUSTek    | PRIME X570-PRO              | [c546b0771a](https://linux-hardware.org/?probe=c546b0771a) | Apr 24, 2023 |
| ASRock     | A300M-STX                   | [8f9e883980](https://linux-hardware.org/?probe=8f9e883980) | Apr 16, 2023 |
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
| Ubuntu Budgie 20.04 | 68       | 33.17%  |
| Ubuntu Budgie 22.04 | 39       | 19.02%  |
| Ubuntu Budgie 20.10 | 23       | 11.22%  |
| Ubuntu Budgie 21.10 | 19       | 9.27%   |
| Ubuntu Budgie 21.04 | 13       | 6.34%   |
| Ubuntu Budgie 19.10 | 13       | 6.34%   |
| Ubuntu Budgie 18.04 | 12       | 5.85%   |
| Ubuntu Budgie 22.10 | 10       | 4.88%   |
| Ubuntu Budgie 23.04 | 4        | 1.95%   |
| Ubuntu Budgie 23.10 | 2        | 0.98%   |
| Ubuntu Budgie       | 2        | 0.98%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu Budgie | 191      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.4.0-42-generic  | 8        | 3.57%   |
| 5.4.0-47-generic  | 5        | 2.23%   |
| 5.8.0-43-generic  | 4        | 1.79%   |
| 5.4.0-52-generic  | 4        | 1.79%   |
| 5.4.0-48-generic  | 4        | 1.79%   |
| 5.4.0-45-generic  | 4        | 1.79%   |
| 5.4.0-37-generic  | 4        | 1.79%   |
| 5.3.0-40-generic  | 4        | 1.79%   |
| 5.3.0-26-generic  | 4        | 1.79%   |
| 5.15.0-52-generic | 4        | 1.79%   |
| 5.13.0-22-generic | 4        | 1.79%   |
| 5.8.0-44-generic  | 3        | 1.34%   |
| 5.8.0-25-generic  | 3        | 1.34%   |
| 5.4.0-31-generic  | 3        | 1.34%   |
| 5.4.0-29-generic  | 3        | 1.34%   |
| 5.3.0-42-generic  | 3        | 1.34%   |
| 5.19.0-26-generic | 3        | 1.34%   |
| 5.15.0-57-generic | 3        | 1.34%   |
| 5.15.0-46-generic | 3        | 1.34%   |
| 5.15.0-43-generic | 3        | 1.34%   |
| 5.15.0-30-generic | 3        | 1.34%   |
| 5.13.0-39-generic | 3        | 1.34%   |
| 5.11.0-41-generic | 3        | 1.34%   |
| 5.11.0-22-generic | 3        | 1.34%   |
| 5.11.0-18-generic | 3        | 1.34%   |
| 6.5.0-10-generic  | 2        | 0.89%   |
| 6.2.0-20-generic  | 2        | 0.89%   |
| 5.8.0-59-generic  | 2        | 0.89%   |
| 5.8.0-50-generic  | 2        | 0.89%   |
| 5.8.0-48-generic  | 2        | 0.89%   |
| 5.8.0-45-generic  | 2        | 0.89%   |
| 5.8.0-31-generic  | 2        | 0.89%   |
| 5.8.0-29-generic  | 2        | 0.89%   |
| 5.8.0-26-generic  | 2        | 0.89%   |
| 5.4.0-91-generic  | 2        | 0.89%   |
| 5.4.0-72-generic  | 2        | 0.89%   |
| 5.4.0-66-generic  | 2        | 0.89%   |
| 5.4.0-59-generic  | 2        | 0.89%   |
| 5.4.0-40-generic  | 2        | 0.89%   |
| 5.3.0-28-generic  | 2        | 0.89%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 58       | 28.02%  |
| 5.8.0   | 30       | 14.49%  |
| 5.15.0  | 30       | 14.49%  |
| 5.13.0  | 20       | 9.66%   |
| 5.3.0   | 17       | 8.21%   |
| 5.19.0  | 15       | 7.25%   |
| 5.11.0  | 15       | 7.25%   |
| 6.2.0   | 8        | 3.86%   |
| 6.5.0   | 2        | 0.97%   |
| 4.15.0  | 2        | 0.97%   |
| 5.9.1   | 1        | 0.48%   |
| 5.7.7   | 1        | 0.48%   |
| 5.5.8   | 1        | 0.48%   |
| 5.17.2  | 1        | 0.48%   |
| 5.17.1  | 1        | 0.48%   |
| 5.15.92 | 1        | 0.48%   |
| 5.14.2  | 1        | 0.48%   |
| 5.14.1  | 1        | 0.48%   |
| 5.10.0  | 1        | 0.48%   |
| 5.0.0   | 1        | 0.48%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 58       | 28.16%  |
| 5.15    | 31       | 15.05%  |
| 5.8     | 30       | 14.56%  |
| 5.13    | 20       | 9.71%   |
| 5.3     | 17       | 8.25%   |
| 5.19    | 15       | 7.28%   |
| 5.11    | 15       | 7.28%   |
| 6.2     | 8        | 3.88%   |
| 6.5     | 2        | 0.97%   |
| 5.17    | 2        | 0.97%   |
| 4.15    | 2        | 0.97%   |
| 5.9     | 1        | 0.49%   |
| 5.7     | 1        | 0.49%   |
| 5.5     | 1        | 0.49%   |
| 5.14    | 1        | 0.49%   |
| 5.10    | 1        | 0.49%   |
| 5.0     | 1        | 0.49%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 186      | 97.38%  |
| i686   | 5        | 2.62%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| Budgie | 185      | 96.86%  |
| GNOME  | 4        | 2.09%   |
| MATE   | 1        | 0.52%   |
| KDE    | 1        | 0.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 188      | 98.43%  |
| Wayland | 2        | 1.05%   |
| Tty     | 1        | 0.52%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 92       | 47.18%  |
| LightDM | 65       | 33.33%  |
| TDM     | 27       | 13.85%  |
| GDM     | 6        | 3.08%   |
| GDM3    | 4        | 2.05%   |
| SDDM    | 1        | 0.51%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 77       | 40.31%  |
| de_DE   | 25       | 13.09%  |
| pt_BR   | 15       | 7.85%   |
| fr_FR   | 14       | 7.33%   |
| en_CA   | 8        | 4.19%   |
| en_AU   | 7        | 3.66%   |
| es_ES   | 6        | 3.14%   |
| en_GB   | 5        | 2.62%   |
| es_MX   | 3        | 1.57%   |
| es_AR   | 3        | 1.57%   |
| zh_TW   | 2        | 1.05%   |
| uk_UA   | 2        | 1.05%   |
| pt_PT   | 2        | 1.05%   |
| pl_PL   | 2        | 1.05%   |
| nl_NL   | 2        | 1.05%   |
| it_IT   | 2        | 1.05%   |
| es_CO   | 2        | 1.05%   |
| Unknown | 2        | 1.05%   |
| ru_UA   | 1        | 0.52%   |
| ru_RU   | 1        | 0.52%   |
| ro_RO   | 1        | 0.52%   |
| fr_CH   | 1        | 0.52%   |
| fr_CA   | 1        | 0.52%   |
| es_CL   | 1        | 0.52%   |
| en_ZA   | 1        | 0.52%   |
| en_IN   | 1        | 0.52%   |
| en_IL   | 1        | 0.52%   |
| el_GR   | 1        | 0.52%   |
| C       | 1        | 0.52%   |
| bg_BG   | 1        | 0.52%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 125      | 63.45%  |
| EFI  | 72       | 36.55%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 175      | 91.15%  |
| Zfs     | 6        | 3.13%   |
| Tmpfs   | 4        | 2.08%   |
| Overlay | 4        | 2.08%   |
| Btrfs   | 3        | 1.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 113      | 57.95%  |
| GPT     | 69       | 35.38%  |
| MBR     | 13       | 6.67%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 158      | 80.61%  |
| Yes       | 38       | 19.39%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 121      | 61.42%  |
| Yes       | 76       | 38.58%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 52       | 27.23%  |
| Gigabyte Technology | 36       | 18.85%  |
| MSI                 | 20       | 10.47%  |
| Dell                | 18       | 9.42%   |
| Hewlett-Packard     | 17       | 8.9%    |
| ASRock              | 15       | 7.85%   |
| Intel               | 7        | 3.66%   |
| Lenovo              | 5        | 2.62%   |
| Fujitsu             | 5        | 2.62%   |
| Apple               | 3        | 1.57%   |
| Biostar             | 2        | 1.05%   |
| Acer                | 2        | 1.05%   |
| Unknown             | 2        | 1.05%   |
| Semp Toshiba        | 1        | 0.52%   |
| Pegatron            | 1        | 0.52%   |
| PCSMART             | 1        | 0.52%   |
| LattePanda          | 1        | 0.52%   |
| Huanan              | 1        | 0.52%   |
| eMachines           | 1        | 0.52%   |
| BCM                 | 1        | 0.52%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Desktops | Percent |
|-----------------------------------------|----------|---------|
| ASUS All Series                         | 8        | 4.19%   |
| Dell OptiPlex 780                       | 3        | 1.57%   |
| MSI MS-7C84                             | 2        | 1.05%   |
| Intel DP55WB AAE64798-206               | 2        | 1.05%   |
| HP EliteDesk 800 G1 SFF                 | 2        | 1.05%   |
| HP Compaq Elite 8300 SFF                | 2        | 1.05%   |
| Gigabyte Z68M-D2H                       | 2        | 1.05%   |
| Gigabyte AB350-Gaming 3                 | 2        | 1.05%   |
| Dell Precision WorkStation T3500        | 2        | 1.05%   |
| Dell OptiPlex 9010                      | 2        | 1.05%   |
| ASUS PRIME B560M-A                      | 2        | 1.05%   |
| ASUS PRIME B450M-A                      | 2        | 1.05%   |
| ASUS P8H77-M PRO                        | 2        | 1.05%   |
| Apple MacPro1,1                         | 2        | 1.05%   |
| Unknown                                 | 2        | 1.05%   |
| Semp Toshiba STI                        | 1        | 0.52%   |
| Pegatron IPI43-TTM                      | 1        | 0.52%   |
| PCSMART 6.0                             | 1        | 0.52%   |
| MSI MS-7D22                             | 1        | 0.52%   |
| MSI MS-7C95                             | 1        | 0.52%   |
| MSI MS-7C77                             | 1        | 0.52%   |
| MSI MS-7C51                             | 1        | 0.52%   |
| MSI MS-7B86                             | 1        | 0.52%   |
| MSI MS-7B61                             | 1        | 0.52%   |
| MSI MS-7B38                             | 1        | 0.52%   |
| MSI MS-7B10                             | 1        | 0.52%   |
| MSI MS-7A71                             | 1        | 0.52%   |
| MSI MS-7A70                             | 1        | 0.52%   |
| MSI MS-7A32                             | 1        | 0.52%   |
| MSI MS-7971                             | 1        | 0.52%   |
| MSI MS-7917                             | 1        | 0.52%   |
| MSI MS-7885                             | 1        | 0.52%   |
| MSI MS-7850                             | 1        | 0.52%   |
| MSI MS-7817                             | 1        | 0.52%   |
| MSI MS-7721                             | 1        | 0.52%   |
| MSI MS-7680                             | 1        | 0.52%   |
| Lenovo ThinkStation C20 4263BA7         | 1        | 0.52%   |
| Lenovo ThinkCentre M93p 10AB000KUS      | 1        | 0.52%   |
| Lenovo Legion T530-28ICB 90L300BQMW     | 1        | 0.52%   |
| Lenovo IdeaCentre 310S-08ASR 90G9007EGE | 1        | 0.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| Dell OptiPlex         | 10       | 5.24%   |
| ASUS PRIME            | 10       | 5.24%   |
| ASUS ROG              | 8        | 4.19%   |
| ASUS All              | 8        | 4.19%   |
| HP EliteDesk          | 5        | 2.62%   |
| Dell Precision        | 5        | 2.62%   |
| HP Compaq             | 4        | 2.09%   |
| Fujitsu ESPRIMO       | 3        | 1.57%   |
| ASUS TUF              | 3        | 1.57%   |
| ASUS P8H77-M          | 3        | 1.57%   |
| MSI MS-7C84           | 2        | 1.05%   |
| Intel DP55WB          | 2        | 1.05%   |
| HP Pavilion           | 2        | 1.05%   |
| Gigabyte Z68M-D2H     | 2        | 1.05%   |
| Gigabyte X570         | 2        | 1.05%   |
| Gigabyte H410M        | 2        | 1.05%   |
| Gigabyte B360         | 2        | 1.05%   |
| Gigabyte AB350-Gaming | 2        | 1.05%   |
| Dell Inspiron         | 2        | 1.05%   |
| ASUS P8Z68-V          | 2        | 1.05%   |
| ASRock B550           | 2        | 1.05%   |
| Apple MacPro1         | 2        | 1.05%   |
| Unknown               | 2        | 1.05%   |
| Semp Toshiba STI      | 1        | 0.52%   |
| Pegatron IPI43-TTM    | 1        | 0.52%   |
| PCSMART 6.0           | 1        | 0.52%   |
| MSI MS-7D22           | 1        | 0.52%   |
| MSI MS-7C95           | 1        | 0.52%   |
| MSI MS-7C77           | 1        | 0.52%   |
| MSI MS-7C51           | 1        | 0.52%   |
| MSI MS-7B86           | 1        | 0.52%   |
| MSI MS-7B61           | 1        | 0.52%   |
| MSI MS-7B38           | 1        | 0.52%   |
| MSI MS-7B10           | 1        | 0.52%   |
| MSI MS-7A71           | 1        | 0.52%   |
| MSI MS-7A70           | 1        | 0.52%   |
| MSI MS-7A32           | 1        | 0.52%   |
| MSI MS-7971           | 1        | 0.52%   |
| MSI MS-7917           | 1        | 0.52%   |
| MSI MS-7885           | 1        | 0.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 24       | 12.57%  |
| 2013 | 19       | 9.95%   |
| 2014 | 17       | 8.9%    |
| 2020 | 15       | 7.85%   |
| 2019 | 15       | 7.85%   |
| 2011 | 15       | 7.85%   |
| 2017 | 14       | 7.33%   |
| 2012 | 14       | 7.33%   |
| 2010 | 11       | 5.76%   |
| 2015 | 9        | 4.71%   |
| 2009 | 9        | 4.71%   |
| 2021 | 8        | 4.19%   |
| 2016 | 7        | 3.66%   |
| 2007 | 7        | 3.66%   |
| 2008 | 5        | 2.62%   |
| 2023 | 1        | 0.52%   |
| 2022 | 1        | 0.52%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 191      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 185      | 96.35%  |
| Enabled  | 7        | 3.65%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 191      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 71       | 36.41%  |
| 8.01-16.0       | 34       | 17.44%  |
| 4.01-8.0        | 25       | 12.82%  |
| 32.01-64.0      | 22       | 11.28%  |
| 3.01-4.0        | 22       | 11.28%  |
| 64.01-256.0     | 14       | 7.18%   |
| 24.01-32.0      | 3        | 1.54%   |
| 1.01-2.0        | 2        | 1.03%   |
| More than 256.0 | 1        | 0.51%   |
| 2.01-3.0        | 1        | 0.51%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 66       | 31.13%  |
| 1.01-2.0   | 61       | 28.77%  |
| 4.01-8.0   | 41       | 19.34%  |
| 3.01-4.0   | 27       | 12.74%  |
| 8.01-16.0  | 10       | 4.72%   |
| 0.51-1.0   | 4        | 1.89%   |
| 16.01-24.0 | 2        | 0.94%   |
| 32.01-64.0 | 1        | 0.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 56       | 28.14%  |
| 1      | 56       | 28.14%  |
| 3      | 38       | 19.1%   |
| 4      | 22       | 11.06%  |
| 5      | 14       | 7.04%   |
| 8      | 5        | 2.51%   |
| 6      | 5        | 2.51%   |
| 11     | 1        | 0.5%    |
| 9      | 1        | 0.5%    |
| 7      | 1        | 0.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 96       | 50%     |
| No        | 96       | 50%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 188      | 98.43%  |
| No        | 3        | 1.57%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 97       | 50.26%  |
| Yes       | 96       | 49.74%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 116      | 59.79%  |
| Yes       | 78       | 40.21%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 51       | 26.56%  |
| Germany      | 27       | 14.06%  |
| France       | 16       | 8.33%   |
| Brazil       | 16       | 8.33%   |
| Canada       | 8        | 4.17%   |
| Australia    | 7        | 3.65%   |
| Switzerland  | 5        | 2.6%    |
| Spain        | 5        | 2.6%    |
| UK           | 4        | 2.08%   |
| Mexico       | 4        | 2.08%   |
| Argentina    | 4        | 2.08%   |
| Ukraine      | 3        | 1.56%   |
| Romania      | 3        | 1.56%   |
| Portugal     | 3        | 1.56%   |
| Poland       | 3        | 1.56%   |
| Netherlands  | 3        | 1.56%   |
| Croatia      | 3        | 1.56%   |
| Sweden       | 2        | 1.04%   |
| Norway       | 2        | 1.04%   |
| Italy        | 2        | 1.04%   |
| Colombia     | 2        | 1.04%   |
| Thailand     | 1        | 0.52%   |
| Taiwan       | 1        | 0.52%   |
| South Africa | 1        | 0.52%   |
| Slovenia     | 1        | 0.52%   |
| Serbia       | 1        | 0.52%   |
| Saudi Arabia | 1        | 0.52%   |
| Russia       | 1        | 0.52%   |
| Puerto Rico  | 1        | 0.52%   |
| Pakistan     | 1        | 0.52%   |
| Japan        | 1        | 0.52%   |
| Israel       | 1        | 0.52%   |
| India        | 1        | 0.52%   |
| Hungary      | 1        | 0.52%   |
| Greece       | 1        | 0.52%   |
| Chile        | 1        | 0.52%   |
| Bulgaria     | 1        | 0.52%   |
| Bolivia      | 1        | 0.52%   |
| Belgium      | 1        | 0.52%   |
| Austria      | 1        | 0.52%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| New York         | 3        | 1.5%    |
| Brasília        | 3        | 1.5%    |
| Zurich           | 2        | 1%      |
| Zagreb           | 2        | 1%      |
| Uman             | 2        | 1%      |
| Trondheim        | 2        | 1%      |
| Timișoara       | 2        | 1%      |
| Sydney           | 2        | 1%      |
| Seattle          | 2        | 1%      |
| Sao Paulo        | 2        | 1%      |
| San Diego        | 2        | 1%      |
| Paris            | 2        | 1%      |
| Milwaukee        | 2        | 1%      |
| Miami            | 2        | 1%      |
| Maringá         | 2        | 1%      |
| Hamburg          | 2        | 1%      |
| Dallas           | 2        | 1%      |
| Caslano          | 2        | 1%      |
| Bogotá          | 2        | 1%      |
| Berlin           | 2        | 1%      |
| Barcelona        | 2        | 1%      |
| Zabrze           | 1        | 0.5%    |
| Würzburg        | 1        | 0.5%    |
| Willich          | 1        | 0.5%    |
| Westland         | 1        | 0.5%    |
| West Des Moines  | 1        | 0.5%    |
| Walled Lake      | 1        | 0.5%    |
| Void-Vacon       | 1        | 0.5%    |
| UEbach-Palenberg | 1        | 0.5%    |
| Uberlândia      | 1        | 0.5%    |
| Tucson           | 1        | 0.5%    |
| Traunstein       | 1        | 0.5%    |
| Toyokawa         | 1        | 0.5%    |
| Toronto          | 1        | 0.5%    |
| Tocantins        | 1        | 0.5%    |
| Tobyhanna        | 1        | 0.5%    |
| Tlalnepantla     | 1        | 0.5%    |
| Tijuana          | 1        | 0.5%    |
| Thrissur         | 1        | 0.5%    |
| Telford          | 1        | 0.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 76       | 130    | 19.14%  |
| WDC                       | 72       | 120    | 18.14%  |
| Samsung Electronics       | 61       | 112    | 15.37%  |
| Toshiba                   | 22       | 22     | 5.54%   |
| Kingston                  | 21       | 32     | 5.29%   |
| SanDisk                   | 19       | 29     | 4.79%   |
| Hitachi                   | 13       | 18     | 3.27%   |
| Phison                    | 12       | 17     | 3.02%   |
| Crucial                   | 11       | 12     | 2.77%   |
| HGST                      | 7        | 8      | 1.76%   |
| PNY                       | 5        | 5      | 1.26%   |
| Intel                     | 5        | 5      | 1.26%   |
| China                     | 5        | 7      | 1.26%   |
| A-DATA Technology         | 5        | 8      | 1.26%   |
| Unknown                   | 4        | 6      | 1.01%   |
| OCZ                       | 4        | 7      | 1.01%   |
| Transcend                 | 3        | 3      | 0.76%   |
| SPCC                      | 3        | 5      | 0.76%   |
| Patriot                   | 3        | 5      | 0.76%   |
| Micron/Crucial Technology | 3        | 3      | 0.76%   |
| Maxtor                    | 3        | 6      | 0.76%   |
| JMicron Technology        | 3        | 4      | 0.76%   |
| Silicon Motion            | 2        | 3      | 0.5%    |
| Micron Technology         | 2        | 4      | 0.5%    |
| Intenso                   | 2        | 2      | 0.5%    |
| HS-SSD-C100               | 2        | 2      | 0.5%    |
| Apacer                    | 2        | 2      | 0.5%    |
| AMD                       | 2        | 17     | 0.5%    |
| Zheino                    | 1        | 2      | 0.25%   |
| XrayDisk                  | 1        | 1      | 0.25%   |
| WD MediaMax               | 1        | 1      | 0.25%   |
| TDAS                      | 1        | 3      | 0.25%   |
| SK hynix                  | 1        | 1      | 0.25%   |
| SABRENT                   | 1        | 1      | 0.25%   |
| Realtek Semiconductor     | 1        | 1      | 0.25%   |
| Plextor                   | 1        | 1      | 0.25%   |
| Phison Electronics        | 1        | 1      | 0.25%   |
| Netac                     | 1        | 1      | 0.25%   |
| Mushkin                   | 1        | 1      | 0.25%   |
| MicroFrom                 | 1        | 1      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB     | 6        | 1.24%   |
| Samsung SSD 860 QVO 1TB            | 6        | 1.24%   |
| Samsung SSD 860 EVO 500GB          | 6        | 1.24%   |
| Seagate ST500DM002-1BD142 500GB    | 5        | 1.03%   |
| Seagate ST2000DM008-2FR102 2TB     | 5        | 1.03%   |
| Kingston SA400S37480G 480GB SSD    | 5        | 1.03%   |
| WDC WD5000AAKS-00UU3A0 500GB       | 4        | 0.82%   |
| Seagate ST2000DM006-2DM164 2TB     | 4        | 0.82%   |
| Seagate ST2000DM001-1ER164 2TB     | 4        | 0.82%   |
| Seagate ST2000DM001-1CH164 2TB     | 4        | 0.82%   |
| Samsung SSD 850 EVO 500GB          | 4        | 0.82%   |
| Samsung NVMe SSD Drive 512GB       | 4        | 0.82%   |
| Samsung NVMe SSD Drive 500GB       | 4        | 0.82%   |
| Kingston SA400S37240G 240GB SSD    | 4        | 0.82%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 3        | 0.62%   |
| WDC WD5000AAKX-001CA0 500GB        | 3        | 0.62%   |
| WDC WD10EARS-00Y5B1 1TB            | 3        | 0.62%   |
| WDC WD10EADS-00M2B0 1TB            | 3        | 0.62%   |
| Toshiba HDWD110 1TB                | 3        | 0.62%   |
| Seagate ST9500325AS 500GB          | 3        | 0.62%   |
| Seagate ST4000DM000-1F2168 4TB     | 3        | 0.62%   |
| Seagate ST380815AS 80GB            | 3        | 0.62%   |
| Seagate ST3500418AS 500GB          | 3        | 0.62%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3        | 0.62%   |
| Seagate ST1000DM003-1ER162 1TB     | 3        | 0.62%   |
| SanDisk SDSSDA240G 240GB           | 3        | 0.62%   |
| SanDisk SDSSDA120G 120GB           | 3        | 0.62%   |
| Samsung SSD 840 EVO 250GB          | 3        | 0.62%   |
| Phison NVMe SSD Drive 1TB          | 3        | 0.62%   |
| WDC WD7501AALS-00J7B1 752GB        | 2        | 0.41%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 2        | 0.41%   |
| WDC WD40EZRZ-22GXCB0 4TB           | 2        | 0.41%   |
| WDC WD40EZRZ-00GXCB0 4TB           | 2        | 0.41%   |
| WDC WD30EZRX-00D8PB0 3TB           | 2        | 0.41%   |
| WDC WD20EZRZ-00Z5HB0 2TB           | 2        | 0.41%   |
| WDC WD20EZRX-00D8PB0 2TB           | 2        | 0.41%   |
| WDC WD20EFRX-68EUZN0 2TB           | 2        | 0.41%   |
| WDC WD10EZEX-08WN4A0 1TB           | 2        | 0.41%   |
| WDC WD10EZEX-00RKKA0 1TB           | 2        | 0.41%   |
| WDC WD10EZEX-00BN5A0 1TB           | 2        | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 76       | 129    | 38.78%  |
| WDC                 | 63       | 106    | 32.14%  |
| Toshiba             | 22       | 22     | 11.22%  |
| Hitachi             | 13       | 18     | 6.63%   |
| Samsung Electronics | 7        | 8      | 3.57%   |
| HGST                | 7        | 8      | 3.57%   |
| Maxtor              | 3        | 6      | 1.53%   |
| Unknown             | 2        | 2      | 1.02%   |
| WD MediaMax         | 1        | 1      | 0.51%   |
| TDAS                | 1        | 3      | 0.51%   |
| ASMT109x            | 1        | 1      | 0.51%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 41       | 68     | 29.5%   |
| Kingston            | 19       | 27     | 13.67%  |
| SanDisk             | 13       | 21     | 9.35%   |
| WDC                 | 11       | 13     | 7.91%   |
| Crucial             | 9        | 10     | 6.47%   |
| China               | 5        | 7      | 3.6%    |
| PNY                 | 4        | 4      | 2.88%   |
| A-DATA Technology   | 4        | 7      | 2.88%   |
| SPCC                | 3        | 5      | 2.16%   |
| Patriot             | 3        | 5      | 2.16%   |
| OCZ                 | 3        | 3      | 2.16%   |
| Transcend           | 2        | 2      | 1.44%   |
| JMicron Technology  | 2        | 2      | 1.44%   |
| Intel               | 2        | 2      | 1.44%   |
| Apacer              | 2        | 2      | 1.44%   |
| AMD                 | 2        | 17     | 1.44%   |
| Zheino              | 1        | 2      | 0.72%   |
| SK hynix            | 1        | 1      | 0.72%   |
| Plextor             | 1        | 1      | 0.72%   |
| Netac               | 1        | 1      | 0.72%   |
| Mushkin             | 1        | 1      | 0.72%   |
| Micron Technology   | 1        | 1      | 0.72%   |
| MicroFrom           | 1        | 1      | 0.72%   |
| Lexar               | 1        | 1      | 0.72%   |
| KingDian            | 1        | 1      | 0.72%   |
| Intenso             | 1        | 1      | 0.72%   |
| GOODRAM             | 1        | 1      | 0.72%   |
| Gigabyte Technology | 1        | 1      | 0.72%   |
| Axiom               | 1        | 1      | 0.72%   |
| 4Life               | 1        | 1      | 0.72%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 142      | 304    | 44.38%  |
| SSD     | 108      | 210    | 33.75%  |
| NVMe    | 58       | 93     | 18.13%  |
| Unknown | 10       | 12     | 3.13%   |
| MMC     | 2        | 3      | 0.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 180      | 510    | 71.71%  |
| NVMe | 57       | 92     | 22.71%  |
| SAS  | 12       | 17     | 4.78%   |
| MMC  | 2        | 3      | 0.8%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 141      | 291    | 49.82%  |
| 0.51-1.0   | 73       | 115    | 25.8%   |
| 1.01-2.0   | 32       | 56     | 11.31%  |
| 3.01-4.0   | 22       | 30     | 7.77%   |
| 4.01-10.0  | 8        | 12     | 2.83%   |
| 2.01-3.0   | 6        | 7      | 2.12%   |
| 10.01-20.0 | 1        | 3      | 0.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 61       | 30.05%  |
| 251-500        | 40       | 19.7%   |
| 501-1000       | 31       | 15.27%  |
| More than 3000 | 24       | 11.82%  |
| 1001-2000      | 19       | 9.36%   |
| 1-20           | 8        | 3.94%   |
| 2001-3000      | 7        | 3.45%   |
| 51-100         | 7        | 3.45%   |
| 21-50          | 3        | 1.48%   |
| Unknown        | 3        | 1.48%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 62       | 29.81%  |
| 101-250        | 35       | 16.83%  |
| 21-50          | 34       | 16.35%  |
| 51-100         | 22       | 10.58%  |
| 251-500        | 17       | 8.17%   |
| 1001-2000      | 15       | 7.21%   |
| 501-1000       | 10       | 4.81%   |
| More than 3000 | 7        | 3.37%   |
| 2001-3000      | 3        | 1.44%   |
| Unknown        | 3        | 1.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB    | 3        | 3      | 12%     |
| WDC WD5000AAKX-001CA0 500GB        | 2        | 2      | 8%      |
| WDC WD6000HLHX-01JJPV0 600GB       | 1        | 1      | 4%      |
| WDC WD5000LPVX-22V0TT0 500GB       | 1        | 2      | 4%      |
| WDC WD5000AVCS-632DY1 500GB        | 1        | 1      | 4%      |
| WDC WD5000AAKX-329BA0 500GB        | 1        | 1      | 4%      |
| WDC WD4003FZEX-00Z4SA0 4TB         | 1        | 1      | 4%      |
| WDC WD2500AAJS-60M0A0 250GB        | 1        | 1      | 4%      |
| WDC WD20EFRX-68EUZN0 2TB           | 1        | 2      | 4%      |
| WDC WD10EZEX-00RKKA0 1TB           | 1        | 1      | 4%      |
| Seagate ST9500325AS 500GB          | 1        | 1      | 4%      |
| Seagate ST5000DM000-1FK178 5TB     | 1        | 1      | 4%      |
| Seagate ST3500320AS 500GB          | 1        | 1      | 4%      |
| Seagate ST3320620AS 320GB          | 1        | 1      | 4%      |
| Seagate ST3160815AS 160GB          | 1        | 1      | 4%      |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1      | 4%      |
| Seagate ST1000DX001-1NS162 1TB     | 1        | 1      | 4%      |
| Seagate ST1000DM003-1SB102 1TB     | 1        | 1      | 4%      |
| Patriot Pyro m3 240GB SSD          | 1        | 1      | 4%      |
| Maxtor STM3250310AS 250GB          | 1        | 1      | 4%      |
| Maxtor 6B200M0 208GB               | 1        | 2      | 4%      |
| Hitachi HDS721032CLA362 320GB      | 1        | 1      | 4%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 11       | 11     | 44%     |
| WDC     | 10       | 12     | 40%     |
| Maxtor  | 2        | 3      | 8%      |
| Patriot | 1        | 1      | 4%      |
| Hitachi | 1        | 1      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 11       | 11     | 45.83%  |
| WDC     | 10       | 12     | 41.67%  |
| Maxtor  | 2        | 3      | 8.33%   |
| Hitachi | 1        | 1      | 4.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 19       | 27     | 95%     |
| SSD  | 1        | 1      | 5%      |

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
| Detected | 133      | 434    | 62.15%  |
| Works    | 61       | 160    | 28.5%   |
| Malfunc  | 20       | 28     | 9.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 132      | 47.48%  |
| AMD                           | 57       | 20.5%   |
| Samsung Electronics           | 24       | 8.63%   |
| Phison Electronics            | 13       | 4.68%   |
| Marvell Technology Group      | 10       | 3.6%    |
| SanDisk                       | 6        | 2.16%   |
| JMicron Technology            | 6        | 2.16%   |
| ASMedia Technology            | 6        | 2.16%   |
| Micron/Crucial Technology     | 5        | 1.8%    |
| Kingston Technology Company   | 4        | 1.44%   |
| Silicon Motion                | 3        | 1.08%   |
| Nvidia                        | 2        | 0.72%   |
| ADATA Technology              | 2        | 0.72%   |
| Transcend                     | 1        | 0.36%   |
| Silicon Image                 | 1        | 0.36%   |
| Seagate Technology            | 1        | 0.36%   |
| Realtek Semiconductor         | 1        | 0.36%   |
| OCZ Technology Group          | 1        | 0.36%   |
| Micron Technology             | 1        | 0.36%   |
| Integrated Technology Express | 1        | 0.36%   |
| Adaptec                       | 1        | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 36       | 10.47%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 15       | 4.36%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 15       | 4.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 12       | 3.49%   |
| AMD 400 Series Chipset SATA Controller                                                  | 11       | 3.2%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 10       | 2.91%   |
| Intel SATA Controller [RAID mode]                                                       | 9        | 2.62%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 9        | 2.62%   |
| AMD 500 Series Chipset SATA Controller                                                  | 9        | 2.62%   |
| Phison E12 NVMe Controller                                                              | 7        | 2.03%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7        | 2.03%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7        | 2.03%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 6        | 1.74%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 6        | 1.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 6        | 1.74%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6        | 1.74%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 5        | 1.45%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 5        | 1.45%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 1.45%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 4        | 1.16%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 1.16%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 4        | 1.16%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 4        | 1.16%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 1.16%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 1.16%   |
| AMD FCH SATA Controller D                                                               | 4        | 1.16%   |
| AMD 300 Series Chipset SATA Controller                                                  | 4        | 1.16%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 3        | 0.87%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 3        | 0.87%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 3        | 0.87%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 3        | 0.87%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 3        | 0.87%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 0.87%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 0.87%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 0.87%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3        | 0.87%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 3        | 0.87%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3        | 0.87%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3        | 0.87%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3        | 0.87%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 149      | 56.02%  |
| NVMe | 58       | 21.8%   |
| IDE  | 47       | 17.67%  |
| RAID | 11       | 4.14%   |
| SAS  | 1        | 0.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 132      | 69.11%  |
| AMD    | 59       | 30.89%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor          | 6        | 3.13%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 5        | 2.6%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 4        | 2.08%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 4        | 2.08%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 4        | 2.08%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 3        | 1.56%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 3        | 1.56%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 3        | 1.56%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 3        | 1.56%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 1.56%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3        | 1.56%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 3        | 1.56%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3        | 1.56%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 3        | 1.56%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 3        | 1.56%   |
| Intel Xeon CPU 5150 @ 2.66GHz               | 2        | 1.04%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 2        | 1.04%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 1.04%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 2        | 1.04%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 2        | 1.04%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 2        | 1.04%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 2        | 1.04%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2        | 1.04%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 2        | 1.04%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 2        | 1.04%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 2        | 1.04%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2        | 1.04%   |
| Intel Core i3-3225 CPU @ 3.30GHz            | 2        | 1.04%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 1.04%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 2        | 1.04%   |
| Intel Core 2 CPU 6400 @ 2.13GHz             | 2        | 1.04%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 2        | 1.04%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 1.04%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 2        | 1.04%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2        | 1.04%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2        | 1.04%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2        | 1.04%   |
| AMD FX-6300 Six-Core Processor              | 2        | 1.04%   |
| Intel Xeon CPU X5690 @ 3.47GHz              | 1        | 0.52%   |
| Intel Xeon CPU X5492 @ 3.40GHz              | 1        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 39       | 20.31%  |
| Intel Core i5           | 36       | 18.75%  |
| AMD Ryzen 5             | 18       | 9.38%   |
| Intel Xeon              | 12       | 6.25%   |
| AMD Ryzen 7             | 12       | 6.25%   |
| Intel Core i3           | 9        | 4.69%   |
| Intel Core 2 Duo        | 6        | 3.13%   |
| Intel Pentium           | 5        | 2.6%    |
| Intel Core 2            | 5        | 2.6%    |
| AMD Ryzen 9             | 5        | 2.6%    |
| AMD Ryzen 3             | 5        | 2.6%    |
| Other                   | 4        | 2.08%   |
| Intel Core i9           | 4        | 2.08%   |
| Intel Celeron           | 4        | 2.08%   |
| AMD FX                  | 4        | 2.08%   |
| Intel Core 2 Quad       | 3        | 1.56%   |
| AMD A4                  | 3        | 1.56%   |
| Intel Pentium Dual      | 2        | 1.04%   |
| AMD A10                 | 2        | 1.04%   |
| Intel Pentium Dual-Core | 1        | 0.52%   |
| Intel Pentium 4         | 1        | 0.52%   |
| Intel Genuine           | 1        | 0.52%   |
| Intel Core m3           | 1        | 0.52%   |
| Intel Atom              | 1        | 0.52%   |
| AMD Sempron             | 1        | 0.52%   |
| AMD Ryzen Threadripper  | 1        | 0.52%   |
| AMD Phenom II X6        | 1        | 0.52%   |
| AMD Phenom II X4        | 1        | 0.52%   |
| AMD Phenom II X2        | 1        | 0.52%   |
| AMD Athlon X4           | 1        | 0.52%   |
| AMD Athlon II X3        | 1        | 0.52%   |
| AMD Athlon              | 1        | 0.52%   |
| AMD A6                  | 1        | 0.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 81       | 42.41%  |
| 2      | 39       | 20.42%  |
| 6      | 28       | 14.66%  |
| 8      | 26       | 13.61%  |
| 12     | 5        | 2.62%   |
| 1      | 5        | 2.62%   |
| 16     | 3        | 1.57%   |
| 3      | 3        | 1.57%   |
| 24     | 1        | 0.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 185      | 96.86%  |
| 2      | 6        | 3.14%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 115      | 59.9%   |
| 1      | 77       | 40.1%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 190      | 99.48%  |
| 32-bit         | 1        | 0.52%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 79       | 39.11%  |
| 0x306c3    | 14       | 6.93%   |
| 0x306a9    | 13       | 6.44%   |
| 0x206a7    | 10       | 4.95%   |
| 0x506e3    | 7        | 3.47%   |
| 0x1067a    | 7        | 3.47%   |
| 0x08701021 | 5        | 2.48%   |
| 0x906ec    | 4        | 1.98%   |
| 0x106e5    | 4        | 1.98%   |
| 0x0800820d | 4        | 1.98%   |
| 0xa0671    | 3        | 1.49%   |
| 0x6f6      | 3        | 1.49%   |
| 0x6f2      | 3        | 1.49%   |
| 0x906ea    | 2        | 0.99%   |
| 0x906e9    | 2        | 0.99%   |
| 0x6fd      | 2        | 0.99%   |
| 0x406f1    | 2        | 0.99%   |
| 0x206d7    | 2        | 0.99%   |
| 0x08108109 | 2        | 0.99%   |
| 0x08101016 | 2        | 0.99%   |
| 0x08001137 | 2        | 0.99%   |
| 0x06000852 | 2        | 0.99%   |
| 0x010000c8 | 2        | 0.99%   |
| 0xf34      | 1        | 0.5%    |
| 0xa0655    | 1        | 0.5%    |
| 0xa0653    | 1        | 0.5%    |
| 0x906ed    | 1        | 0.5%    |
| 0x706a8    | 1        | 0.5%    |
| 0x6fb      | 1        | 0.5%    |
| 0x406c4    | 1        | 0.5%    |
| 0x306f2    | 1        | 0.5%    |
| 0x30678    | 1        | 0.5%    |
| 0x206c2    | 1        | 0.5%    |
| 0x20655    | 1        | 0.5%    |
| 0x106a5    | 1        | 0.5%    |
| 0x10677    | 1        | 0.5%    |
| 0x0a50000c | 1        | 0.5%    |
| 0x0a201205 | 1        | 0.5%    |
| 0x0a201016 | 1        | 0.5%    |
| 0x08701013 | 1        | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 25       | 13.09%  |
| SandyBridge   | 18       | 9.42%   |
| KabyLake      | 18       | 9.42%   |
| IvyBridge     | 18       | 9.42%   |
| Zen 2         | 16       | 8.38%   |
| Zen+          | 12       | 6.28%   |
| Penryn        | 10       | 5.24%   |
| Core          | 10       | 5.24%   |
| Skylake       | 8        | 4.19%   |
| Zen           | 7        | 3.66%   |
| Nehalem       | 7        | 3.66%   |
| Zen 3         | 6        | 3.14%   |
| Piledriver    | 5        | 2.62%   |
| K10           | 5        | 2.62%   |
| CometLake     | 5        | 2.62%   |
| Westmere      | 4        | 2.09%   |
| Icelake       | 3        | 1.57%   |
| Excavator     | 3        | 1.57%   |
| Steamroller   | 2        | 1.05%   |
| Silvermont    | 2        | 1.05%   |
| Broadwell     | 2        | 1.05%   |
| Puma          | 1        | 0.52%   |
| NetBurst      | 1        | 0.52%   |
| Goldmont plus | 1        | 0.52%   |
| Bulldozer     | 1        | 0.52%   |
| Unknown       | 1        | 0.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 91       | 43.13%  |
| AMD               | 61       | 28.91%  |
| Intel             | 58       | 27.49%  |
| ASPEED Technology | 1        | 0.47%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 14       | 6.57%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 13       | 6.1%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 9        | 4.23%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 9        | 4.23%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 8        | 3.76%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 3.29%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 6        | 2.82%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 5        | 2.35%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 5        | 2.35%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 5        | 2.35%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 4        | 1.88%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4        | 1.88%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 1.88%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 4        | 1.88%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 4        | 1.88%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4        | 1.88%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 4        | 1.88%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 1.41%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 1.41%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 3        | 1.41%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 1.41%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 3        | 1.41%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 0.94%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 2        | 0.94%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 2        | 0.94%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 0.94%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 2        | 0.94%   |
| Nvidia GF108 [GeForce GT 730]                                               | 2        | 0.94%   |
| Intel HD Graphics 530                                                       | 2        | 0.94%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 2        | 0.94%   |
| AMD Juniper XT [Radeon HD 5770]                                             | 2        | 0.94%   |
| AMD Cypress XT [Radeon HD 5870]                                             | 2        | 0.94%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 0.94%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 2        | 0.94%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2        | 0.94%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.47%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.47%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1        | 0.47%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 0.47%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1        | 0.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 82       | 41.62%  |
| 1 x AMD        | 53       | 26.9%   |
| 1 x Intel      | 50       | 25.38%  |
| AMD + Nvidia   | 5        | 2.54%   |
| Intel + Nvidia | 3        | 1.52%   |
| Intel + AMD    | 2        | 1.02%   |
| 2 x Nvidia     | 1        | 0.51%   |
| 1 x ASPEED     | 1        | 0.51%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 121      | 61.11%  |
| Proprietary | 71       | 35.86%  |
| Unknown     | 6        | 3.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 91       | 45.05%  |
| 7.01-8.0   | 24       | 11.88%  |
| 1.01-2.0   | 24       | 11.88%  |
| 3.01-4.0   | 21       | 10.4%   |
| 5.01-6.0   | 16       | 7.92%   |
| 0.51-1.0   | 13       | 6.44%   |
| 0.01-0.5   | 9        | 4.46%   |
| 8.01-16.0  | 2        | 0.99%   |
| 2.01-3.0   | 1        | 0.5%    |
| 16.01-24.0 | 1        | 0.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 42       | 20.1%   |
| Dell                 | 26       | 12.44%  |
| Goldstar             | 16       | 7.66%   |
| AOC                  | 14       | 6.7%    |
| Hewlett-Packard      | 12       | 5.74%   |
| Ancor Communications | 12       | 5.74%   |
| Acer                 | 10       | 4.78%   |
| BenQ                 | 9        | 4.31%   |
| Philips              | 7        | 3.35%   |
| Unknown              | 5        | 2.39%   |
| LG Electronics       | 5        | 2.39%   |
| Idek Iiyama          | 4        | 1.91%   |
| ASUSTek Computer     | 4        | 1.91%   |
| Sony                 | 3        | 1.44%   |
| Medion               | 3        | 1.44%   |
| Iiyama               | 3        | 1.44%   |
| Fujitsu Siemens      | 3        | 1.44%   |
| Vizio                | 2        | 0.96%   |
| ViewSonic            | 2        | 0.96%   |
| Sceptre Tech         | 2        | 0.96%   |
| SANYO                | 2        | 0.96%   |
| MStar                | 2        | 0.96%   |
| Eizo                 | 2        | 0.96%   |
| AGO                  | 2        | 0.96%   |
| VIZ                  | 1        | 0.48%   |
| Unknown (XXX)        | 1        | 0.48%   |
| Sun                  | 1        | 0.48%   |
| Pioneer Electronic   | 1        | 0.48%   |
| Panasonic            | 1        | 0.48%   |
| NEC Computers        | 1        | 0.48%   |
| MPI                  | 1        | 0.48%   |
| Microstep            | 1        | 0.48%   |
| Lenovo               | 1        | 0.48%   |
| Insignia             | 1        | 0.48%   |
| Huion                | 1        | 0.48%   |
| HKC                  | 1        | 0.48%   |
| Daewoo               | 1        | 0.48%   |
| CHD                  | 1        | 0.48%   |
| AUS                  | 1        | 0.48%   |
| Apple                | 1        | 0.48%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S27B550 SAM091B 1920x1080 598x336mm 27.0-inch     | 2        | 0.84%   |
| Samsung Electronics LCD Monitor SAM0BB4 3840x2160 890x500mm 40.2-inch | 2        | 0.84%   |
| Samsung Electronics LCD Monitor C34H89x 3440x1440                     | 2        | 0.84%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                      | 2        | 0.84%   |
| Medion MD20338 MED3943 1600x900 462x272mm 21.1-inch                   | 2        | 0.84%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch              | 2        | 0.84%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2        | 0.84%   |
| Dell D2721H DEL2013 1920x1080 598x336mm 27.0-inch                     | 2        | 0.84%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 2        | 0.84%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 2        | 0.84%   |
| Ancor Communications ASUS PA238 ACI23B1 1920x1080 509x286mm 23.0-inch | 2        | 0.84%   |
| Vizio M190VA VIZ0067 1360x768 410x230mm 18.5-inch                     | 1        | 0.42%   |
| Vizio E320-B1 VIZ0095 1360x768 697x392mm 31.5-inch                    | 1        | 0.42%   |
| Vizio D40u-D1 VIZ1011 3840x2160 878x485mm 39.5-inch                   | 1        | 0.42%   |
| VIZ LCD Monitor M50-C1 3840x2160                                      | 1        | 0.42%   |
| ViewSonic VX2476 Series VSC9939 1920x1080 527x296mm 23.8-inch         | 1        | 0.42%   |
| ViewSonic VA903 SERIES VSC111E 1280x1024 376x301mm 19.0-inch          | 1        | 0.42%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                 | 1        | 0.42%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 1        | 0.42%   |
| Unknown LCD Monitor SAMSUNG 1366x768                                  | 1        | 0.42%   |
| Unknown LCD Monitor SAMSUNG                                           | 1        | 0.42%   |
| Unknown LCD Monitor GTW KX2153                                        | 1        | 0.42%   |
| Unknown LCD Monitor EMA E202HL                                        | 1        | 0.42%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch         | 1        | 0.42%   |
| Sun X7202A SUN0595 1280x1024 376x301mm 19.0-inch                      | 1        | 0.42%   |
| Sony TV SNYEE01 1920x1080                                             | 1        | 0.42%   |
| Sony SDM-HS93 SNY1190 1280x1024 357x286mm 18.0-inch                   | 1        | 0.42%   |
| Sony LCD Monitor TV  *07 5760x2160                                    | 1        | 0.42%   |
| Sony LCD Monitor TV  *07                                              | 1        | 0.42%   |
| Sceptre Tech Sceptre B34 SPT0D52 2560x1080 797x334mm 34.0-inch        | 1        | 0.42%   |
| Sceptre Tech E24 SPT099D 1920x1080 521x293mm 23.5-inch                | 1        | 0.42%   |
| Sceptre Tech E205W-1600 SPT080D 1600x900 477x268mm 21.5-inch          | 1        | 0.42%   |
| SANYO LCD-24XH7** SAN0B92 1920x540 531x299mm 24.0-inch                | 1        | 0.42%   |
| SANYO LCD SAN0A12 1920x540                                            | 1        | 0.42%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch     | 1        | 0.42%   |
| Samsung Electronics T24C550 SAM0AA1 1920x1080 521x293mm 23.5-inch     | 1        | 0.42%   |
| Samsung Electronics SyncMaster SAM0653 1920x1080                      | 1        | 0.42%   |
| Samsung Electronics SyncMaster SAM060C 1920x1080 510x290mm 23.1-inch  | 1        | 0.42%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                      | 1        | 0.42%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch  | 1        | 0.42%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 92       | 43.19%  |
| 3840x2160 (4K)     | 15       | 7.04%   |
| 1280x1024 (SXGA)   | 15       | 7.04%   |
| Unknown            | 13       | 6.1%    |
| 1366x768 (WXGA)    | 11       | 5.16%   |
| 1920x1200 (WUXGA)  | 8        | 3.76%   |
| 1680x1050 (WSXGA+) | 8        | 3.76%   |
| 3440x1440          | 7        | 3.29%   |
| 2560x1080          | 7        | 3.29%   |
| 3840x1080          | 6        | 2.82%   |
| 2560x1440 (QHD)    | 6        | 2.82%   |
| 1600x900 (HD+)     | 4        | 1.88%   |
| 1920x540           | 3        | 1.41%   |
| 3520x1080          | 2        | 0.94%   |
| 2560x1600          | 2        | 0.94%   |
| 5760x2160          | 1        | 0.47%   |
| 4480x1080          | 1        | 0.47%   |
| 3840x1440          | 1        | 0.47%   |
| 3840x1200          | 1        | 0.47%   |
| 3600x1080          | 1        | 0.47%   |
| 3280x1080          | 1        | 0.47%   |
| 3200x1800 (QHD+)   | 1        | 0.47%   |
| 2646x768           | 1        | 0.47%   |
| 2560x1024          | 1        | 0.47%   |
| 2390x768           | 1        | 0.47%   |
| 2048x1152          | 1        | 0.47%   |
| 1600x1200          | 1        | 0.47%   |
| 1400x1050          | 1        | 0.47%   |
| 1280x720 (HD)      | 1        | 0.47%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 44       | 21.36%  |
| 24      | 28       | 13.59%  |
| 27      | 26       | 12.62%  |
| 23      | 23       | 11.17%  |
| 21      | 13       | 6.31%   |
| 34      | 10       | 4.85%   |
| 19      | 8        | 3.88%   |
| 17      | 6        | 2.91%   |
| 31      | 5        | 2.43%   |
| 15      | 5        | 2.43%   |
| 54      | 4        | 1.94%   |
| 22      | 4        | 1.94%   |
| 20      | 4        | 1.94%   |
| 18      | 4        | 1.94%   |
| 84      | 2        | 0.97%   |
| 72      | 2        | 0.97%   |
| 52      | 2        | 0.97%   |
| 33      | 2        | 0.97%   |
| 28      | 2        | 0.97%   |
| 12      | 2        | 0.97%   |
| 63      | 1        | 0.49%   |
| 48      | 1        | 0.49%   |
| 46      | 1        | 0.49%   |
| 40      | 1        | 0.49%   |
| 37      | 1        | 0.49%   |
| 29      | 1        | 0.49%   |
| 25      | 1        | 0.49%   |
| 16      | 1        | 0.49%   |
| 14      | 1        | 0.49%   |
| 13      | 1        | 0.49%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 71       | 34.8%   |
| Unknown     | 44       | 21.57%  |
| 401-500     | 26       | 12.75%  |
| 601-700     | 13       | 6.37%   |
| 701-800     | 12       | 5.88%   |
| 301-350     | 11       | 5.39%   |
| 1001-1500   | 9        | 4.41%   |
| 351-400     | 8        | 3.92%   |
| 201-300     | 4        | 1.96%   |
| 1501-2000   | 4        | 1.96%   |
| 801-900     | 2        | 0.98%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 103      | 53.93%  |
| Unknown | 40       | 20.94%  |
| 16/10   | 15       | 7.85%   |
| 5/4     | 12       | 6.28%   |
| 21/9    | 11       | 5.76%   |
| 4/3     | 6        | 3.14%   |
| 32/9    | 2        | 1.05%   |
| 6/5     | 1        | 0.52%   |
| 1.00    | 1        | 0.52%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 49       | 24.38%  |
| Unknown        | 44       | 21.89%  |
| 301-350        | 26       | 12.94%  |
| 351-500        | 19       | 9.45%   |
| 151-200        | 19       | 9.45%   |
| More than 1000 | 11       | 5.47%   |
| 251-300        | 10       | 4.98%   |
| 141-150        | 9        | 4.48%   |
| 101-110        | 4        | 1.99%   |
| 501-1000       | 4        | 1.99%   |
| 71-80          | 3        | 1.49%   |
| 91-100         | 2        | 1%      |
| 131-140        | 1        | 0.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 108      | 55.67%  |
| Unknown       | 44       | 22.68%  |
| 101-120       | 21       | 10.82%  |
| 1-50          | 9        | 4.64%   |
| 121-160       | 8        | 4.12%   |
| 161-240       | 3        | 1.55%   |
| More than 240 | 1        | 0.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 140      | 71.79%  |
| 2     | 42       | 21.54%  |
| 0     | 9        | 4.62%   |
| 3     | 3        | 1.54%   |
| 4     | 1        | 0.51%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 109      | 39.49%  |
| Intel                           | 99       | 35.87%  |
| Qualcomm Atheros                | 15       | 5.43%   |
| Broadcom                        | 15       | 5.43%   |
| Ralink Technology               | 7        | 2.54%   |
| Microsoft                       | 4        | 1.45%   |
| D-Link System                   | 3        | 1.09%   |
| D-Link                          | 3        | 1.09%   |
| Ralink                          | 2        | 0.72%   |
| Qualcomm Atheros Communications | 2        | 0.72%   |
| Nvidia                          | 2        | 0.72%   |
| NetGear                         | 2        | 0.72%   |
| Linksys                         | 2        | 0.72%   |
| Belkin Components               | 2        | 0.72%   |
| Xiaomi                          | 1        | 0.36%   |
| Wacom                           | 1        | 0.36%   |
| T & A Mobile Phones             | 1        | 0.36%   |
| Mercucys                        | 1        | 0.36%   |
| MediaTek                        | 1        | 0.36%   |
| Exar                            | 1        | 0.36%   |
| Broadcom Limited                | 1        | 0.36%   |
| ASUSTek Computer                | 1        | 0.36%   |
| ASIX Electronics                | 1        | 0.36%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 81       | 25.8%   |
| Intel Wi-Fi 6 AX200                                               | 16       | 5.1%    |
| Intel I211 Gigabit Network Connection                             | 10       | 3.18%   |
| Intel Ethernet Connection I217-LM                                 | 10       | 3.18%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9        | 2.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8        | 2.55%   |
| Intel Ethernet Connection (7) I219-V                              | 7        | 2.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 6        | 1.91%   |
| Intel Wireless-AC 9260                                            | 5        | 1.59%   |
| Intel Ethernet Controller I225-V                                  | 5        | 1.59%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 1.59%   |
| Intel Ethernet Connection (2) I218-V                              | 5        | 1.59%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 1.59%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter      | 5        | 1.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 1.27%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4        | 1.27%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 1.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 0.96%   |
| Realtek 802.11ac NIC                                              | 3        | 0.96%   |
| Intel I210 Gigabit Network Connection                             | 3        | 0.96%   |
| Intel Ethernet Connection (14) I219-V                             | 3        | 0.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3        | 0.96%   |
| Intel 82566DM Gigabit Network Connection                          | 3        | 0.96%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 3        | 0.96%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2        | 0.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2        | 0.64%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 2        | 0.64%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 0.64%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2        | 0.64%   |
| Ralink MT7601U Wireless Adapter                                   | 2        | 0.64%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.64%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2        | 0.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2        | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.64%   |
| Nvidia MCP61 Ethernet                                             | 2        | 0.64%   |
| Microsoft Xbox 360 Wireless Adapter                               | 2        | 0.64%   |
| Linksys WUSB54GC v1 802.11g Adapter [Ralink RT73]                 | 2        | 0.64%   |
| Intel Wireless 7265                                               | 2        | 0.64%   |
| Intel Wireless 3165                                               | 2        | 0.64%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 40       | 38.1%   |
| Realtek Semiconductor           | 20       | 19.05%  |
| Broadcom                        | 8        | 7.62%   |
| Ralink Technology               | 7        | 6.67%   |
| Qualcomm Atheros                | 7        | 6.67%   |
| Microsoft                       | 4        | 3.81%   |
| D-Link                          | 3        | 2.86%   |
| Ralink                          | 2        | 1.9%    |
| Qualcomm Atheros Communications | 2        | 1.9%    |
| NetGear                         | 2        | 1.9%    |
| Linksys                         | 2        | 1.9%    |
| D-Link System                   | 2        | 1.9%    |
| Belkin Components               | 2        | 1.9%    |
| Wacom                           | 1        | 0.95%   |
| Mercucys                        | 1        | 0.95%   |
| MediaTek                        | 1        | 0.95%   |
| ASUSTek Computer                | 1        | 0.95%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 16       | 14.68%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 6        | 5.5%    |
| Intel Wireless-AC 9260                                               | 5        | 4.59%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 5        | 4.59%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 4        | 3.67%   |
| Realtek 802.11ac NIC                                                 | 3        | 2.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 3        | 2.75%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 2        | 1.83%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 2        | 1.83%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 2        | 1.83%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 2        | 1.83%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 2        | 1.83%   |
| Ralink MT7601U Wireless Adapter                                      | 2        | 1.83%   |
| Qualcomm Atheros AR9271 802.11n                                      | 2        | 1.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2        | 1.83%   |
| Microsoft Xbox 360 Wireless Adapter                                  | 2        | 1.83%   |
| Linksys WUSB54GC v1 802.11g Adapter [Ralink RT73]                    | 2        | 1.83%   |
| Intel Wireless 7265                                                  | 2        | 1.83%   |
| Intel Wireless 3165                                                  | 2        | 1.83%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 2        | 1.83%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                             | 1        | 0.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 1        | 0.92%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 1        | 0.92%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                  | 1        | 0.92%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter              | 1        | 0.92%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                           | 1        | 0.92%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                      | 1        | 0.92%   |
| Realtek RTL8191SEvB Wireless LAN Controller                          | 1        | 0.92%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 1        | 0.92%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                              | 1        | 0.92%   |
| Ralink RT5372 Wireless Adapter                                       | 1        | 0.92%   |
| Ralink RT5370 Wireless Adapter                                       | 1        | 0.92%   |
| Ralink RT3072 Wireless Adapter                                       | 1        | 0.92%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 1        | 0.92%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                    | 1        | 0.92%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                            | 1        | 0.92%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                 | 1        | 0.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 1        | 0.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1        | 0.92%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                     | 1        | 0.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 98       | 49.49%  |
| Intel                 | 78       | 39.39%  |
| Qualcomm Atheros      | 8        | 4.04%   |
| Broadcom              | 7        | 3.54%   |
| Nvidia                | 2        | 1.01%   |
| Xiaomi                | 1        | 0.51%   |
| T & A Mobile Phones   | 1        | 0.51%   |
| D-Link System         | 1        | 0.51%   |
| Broadcom Limited      | 1        | 0.51%   |
| ASIX Electronics      | 1        | 0.51%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 81       | 39.71%  |
| Intel I211 Gigabit Network Connection                             | 10       | 4.9%    |
| Intel Ethernet Connection I217-LM                                 | 10       | 4.9%    |
| Realtek RTL8125 2.5GbE Controller                                 | 9        | 4.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8        | 3.92%   |
| Intel Ethernet Connection (7) I219-V                              | 7        | 3.43%   |
| Intel Ethernet Controller I225-V                                  | 5        | 2.45%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 2.45%   |
| Intel Ethernet Connection (2) I218-V                              | 5        | 2.45%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 2.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 1.96%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4        | 1.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 1.47%   |
| Intel I210 Gigabit Network Connection                             | 3        | 1.47%   |
| Intel Ethernet Connection (14) I219-V                             | 3        | 1.47%   |
| Intel 82566DM Gigabit Network Connection                          | 3        | 1.47%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 3        | 1.47%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2        | 0.98%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.98%   |
| Nvidia MCP61 Ethernet                                             | 2        | 0.98%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.98%   |
| Intel 82578DC Gigabit Network Connection                          | 2        | 0.98%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 2        | 0.98%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2        | 0.98%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.49%   |
| T & A Mobile Phones TCL 20E                                       | 1        | 0.49%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.49%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1        | 0.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1        | 0.49%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.49%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.49%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.49%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.49%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 0.49%   |
| Intel Ethernet Connection (10) I219-V                             | 1        | 0.49%   |
| Intel 82574L Gigabit Network Connection                           | 1        | 0.49%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1        | 0.49%   |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 0.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 188      | 65.73%  |
| WiFi     | 97       | 33.92%  |
| Modem    | 1        | 0.35%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 145      | 71.08%  |
| WiFi     | 59       | 28.92%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 121      | 63.35%  |
| 2     | 57       | 29.84%  |
| 3     | 12       | 6.28%   |
| 0     | 1        | 0.52%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 158      | 81.03%  |
| Yes  | 37       | 18.97%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 39       | 49.37%  |
| Cambridge Silicon Radio         | 22       | 27.85%  |
| Broadcom                        | 4        | 5.06%   |
| Qualcomm Atheros Communications | 3        | 3.8%    |
| ASUSTek Computer                | 3        | 3.8%    |
| Realtek Semiconductor           | 2        | 2.53%   |
| Belkin Components               | 2        | 2.53%   |
| MediaTek                        | 1        | 1.27%   |
| Lite-On Technology              | 1        | 1.27%   |
| IMC Networks                    | 1        | 1.27%   |
| Apple                           | 1        | 1.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 22       | 27.85%  |
| Intel AX200 Bluetooth                                 | 16       | 20.25%  |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 5        | 6.33%   |
| Intel Wireless-AC 3168 Bluetooth                      | 5        | 6.33%   |
| Intel Bluetooth wireless interface                    | 5        | 6.33%   |
| Intel AX210 Bluetooth                                 | 4        | 5.06%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 3        | 3.8%    |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 3        | 3.8%    |
| Qualcomm Atheros AR3011 Bluetooth                     | 2        | 2.53%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 2        | 2.53%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1        | 1.27%   |
| Realtek Bluetooth Radio                               | 1        | 1.27%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 1        | 1.27%   |
| MediaTek Wireless_Device                              | 1        | 1.27%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 1        | 1.27%   |
| Intel AX201 Bluetooth                                 | 1        | 1.27%   |
| IMC Networks Bluetooth Radio                          | 1        | 1.27%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 1        | 1.27%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 1        | 1.27%   |
| ASUS Bluetooth Radio                                  | 1        | 1.27%   |
| ASUS Bluetooth Adapter                                | 1        | 1.27%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 1        | 1.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 127      | 37.03%  |
| Nvidia                     | 88       | 25.66%  |
| AMD                        | 81       | 23.62%  |
| Logitech                   | 7        | 2.04%   |
| C-Media Electronics        | 6        | 1.75%   |
| Creative Labs              | 4        | 1.17%   |
| Creative Technology        | 3        | 0.87%   |
| JMTek                      | 2        | 0.58%   |
| GN Netcom                  | 2        | 0.58%   |
| DSEA A/S                   | 2        | 0.58%   |
| ASUSTek Computer           | 2        | 0.58%   |
| Texas Instruments          | 1        | 0.29%   |
| SteelSeries ApS            | 1        | 0.29%   |
| Shure                      | 1        | 0.29%   |
| Samson Technologies        | 1        | 0.29%   |
| Realtek Semiconductor      | 1        | 0.29%   |
| PreSonus Audio Electronics | 1        | 0.29%   |
| OPPO Electronics           | 1        | 0.29%   |
| Native Instruments         | 1        | 0.29%   |
| Nam Tai E&E Products       | 1        | 0.29%   |
| Microsoft                  | 1        | 0.29%   |
| M-Audio                    | 1        | 0.29%   |
| Kingston Technology        | 1        | 0.29%   |
| Giga-Byte Technology       | 1        | 0.29%   |
| Focusrite-Novation         | 1        | 0.29%   |
| ClearOne Communications    | 1        | 0.29%   |
| Bose                       | 1        | 0.29%   |
| Blue Microphones           | 1        | 0.29%   |
| Barco Display Systems      | 1        | 0.29%   |
| Astro Gaming               | 1        | 0.29%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 18       | 4.57%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 17       | 4.31%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 17       | 4.31%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 15       | 3.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 13       | 3.3%    |
| AMD Family 17h/19h HD Audio Controller                                     | 13       | 3.3%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 13       | 3.3%    |
| Intel Cannon Lake PCH cAVS                                                 | 11       | 2.79%   |
| Nvidia GP106 High Definition Audio Controller                              | 10       | 2.54%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 10       | 2.54%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 9        | 2.28%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8        | 2.03%   |
| Nvidia TU106 High Definition Audio Controller                              | 7        | 1.78%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7        | 1.78%   |
| Nvidia GP108 High Definition Audio Controller                              | 6        | 1.52%   |
| Nvidia GP104 High Definition Audio Controller                              | 6        | 1.52%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 6        | 1.52%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 6        | 1.52%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6        | 1.52%   |
| Intel 200 Series PCH HD Audio                                              | 6        | 1.52%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6        | 1.52%   |
| AMD FCH Azalia Controller                                                  | 6        | 1.52%   |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 1.27%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 5        | 1.27%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5        | 1.27%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 5        | 1.27%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5        | 1.27%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5        | 1.27%   |
| AMD Navi 10 HDMI Audio                                                     | 5        | 1.27%   |
| Nvidia TU104 HD Audio Controller                                           | 4        | 1.02%   |
| Nvidia GM206 High Definition Audio Controller                              | 4        | 1.02%   |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 1.02%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 4        | 1.02%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 4        | 1.02%   |
| Nvidia High Definition Audio Controller                                    | 3        | 0.76%   |
| Nvidia GM204 High Definition Audio Controller                              | 3        | 0.76%   |
| Nvidia GK106 HDMI Audio Controller                                         | 3        | 0.76%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 0.76%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 3        | 0.76%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3        | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 20       | 17.7%   |
| Samsung Electronics | 14       | 12.39%  |
| Crucial             | 14       | 12.39%  |
| Unknown             | 10       | 8.85%   |
| SK hynix            | 10       | 8.85%   |
| Corsair             | 9        | 7.96%   |
| G.Skill             | 7        | 6.19%   |
| Micron Technology   | 6        | 5.31%   |
| Team                | 5        | 4.42%   |
| A-DATA Technology   | 5        | 4.42%   |
| Transcend           | 2        | 1.77%   |
| Goodram             | 2        | 1.77%   |
| Unknown (0x873E)    | 1        | 0.88%   |
| Timetec             | 1        | 0.88%   |
| Sesame              | 1        | 0.88%   |
| PNY                 | 1        | 0.88%   |
| Nanya Technology    | 1        | 0.88%   |
| Elpida              | 1        | 0.88%   |
| Avant               | 1        | 0.88%   |
| Apacer              | 1        | 0.88%   |
| Unknown             | 1        | 0.88%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                   | 2        | 1.68%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s  | 2        | 1.68%   |
| Kingston RAM 9905403-199.A00LF 4GB DIMM DDR3 1600MT/s  | 2        | 1.68%   |
| Crucial RAM BLS4G4D240FSB.8FBD 4GB DIMM DDR4 2472MT/s  | 2        | 1.68%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3400MT/s | 2        | 1.68%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s            | 2        | 1.68%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s           | 1        | 0.84%   |
| Unknown RAM Module 512MB DIMM 533MT/s                  | 1        | 0.84%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                   | 1        | 0.84%   |
| Unknown RAM Module 4096MB DIMM DDR 1066MT/s            | 1        | 0.84%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                 | 1        | 0.84%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 1        | 0.84%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s            | 1        | 0.84%   |
| Unknown RAM Module 2048MB DIMM DDR 1066MT/s            | 1        | 0.84%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                 | 1        | 0.84%   |
| Unknown RAM Module 1024MB DIMM DDR2                    | 1        | 0.84%   |
| Unknown RAM DDR3 1600 8G 8192MB DIMM DDR3 1600MT/s     | 1        | 0.84%   |
| Unknown (0x873E) RAM Module 8192MB DIMM DDR3 1333MT/s  | 1        | 0.84%   |
| Transcend RAM TS256MLK64V3U 2GB DIMM DDR3 1066MT/s     | 1        | 0.84%   |
| Transcend RAM Module 2048MB DIMM DDR2 800MT/s          | 1        | 0.84%   |
| Timetec RAM ED3-1600 8192MB DIMM DDR3 1600MT/s         | 1        | 0.84%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3733MT/s     | 1        | 0.84%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s     | 1        | 0.84%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 3000MT/s     | 1        | 0.84%   |
| Team RAM TEAMGROUP-UD4-2400 16GB DIMM DDR4 3007MT/s    | 1        | 0.84%   |
| Team RAM Elite-1333 4GB DIMM DDR3 1333MT/s             | 1        | 0.84%   |
| SK hynix RAM Module 4096MB FB-DIMM DDR2 667MT/s        | 1        | 0.84%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s             | 1        | 0.84%   |
| SK hynix RAM Module 1GB DIMM DDR3 1333MT/s             | 1        | 0.84%   |
| SK hynix RAM Module 1024MB DIMM DDR3 1333MT/s          | 1        | 0.84%   |
| SK hynix RAM HYMP512U64CP8-Y5 1GB DIMM DDR2 1331MT/s   | 1        | 0.84%   |
| SK hynix RAM HYMP112U64CP8-Y5 1GB DIMM DDR2 1639MT/s   | 1        | 0.84%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s   | 1        | 0.84%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s   | 1        | 0.84%   |
| SK hynix RAM HMA81GR7MFR8N-UH 8GB RIMM DDR4 2400MT/s   | 1        | 0.84%   |
| SK hynix RAM HMA41GR7AFR4N-UH 8GB DIMM DDR4 2400MT/s   | 1        | 0.84%   |
| Sesame RAM S939A2UGS-ITR 8GB DIMM DDR3 1600MT/s        | 1        | 0.84%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s              | 1        | 0.84%   |
| Samsung RAM Module 2GB FB-DIMM DDR2 667MT/s            | 1        | 0.84%   |
| Samsung RAM Module 1GB DIMM DDR3 1333MT/s              | 1        | 0.84%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 41       | 43.16%  |
| DDR3    | 39       | 41.05%  |
| DDR2    | 6        | 6.32%   |
| SDRAM   | 5        | 5.26%   |
| Unknown | 3        | 3.16%   |
| DDR     | 1        | 1.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 85       | 90.43%  |
| SODIMM  | 6        | 6.38%   |
| FB-DIMM | 2        | 2.13%   |
| RIMM    | 1        | 1.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 38       | 36.89%  |
| 4096  | 25       | 24.27%  |
| 16384 | 13       | 12.62%  |
| 2048  | 13       | 12.62%  |
| 32768 | 7        | 6.8%    |
| 1024  | 5        | 4.85%   |
| 512   | 2        | 1.94%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 28       | 25.93%  |
| 1333    | 12       | 11.11%  |
| 3200    | 11       | 10.19%  |
| 2400    | 5        | 4.63%   |
| 3400    | 4        | 3.7%    |
| 2667    | 4        | 3.7%    |
| 800     | 4        | 3.7%    |
| 2133    | 3        | 2.78%   |
| 1066    | 3        | 2.78%   |
| 667     | 3        | 2.78%   |
| Unknown | 3        | 2.78%   |
| 3733    | 2        | 1.85%   |
| 3666    | 2        | 1.85%   |
| 3600    | 2        | 1.85%   |
| 3266    | 2        | 1.85%   |
| 3000    | 2        | 1.85%   |
| 2472    | 2        | 1.85%   |
| 1800    | 2        | 1.85%   |
| 3866    | 1        | 0.93%   |
| 3800    | 1        | 0.93%   |
| 3500    | 1        | 0.93%   |
| 3007    | 1        | 0.93%   |
| 2933    | 1        | 0.93%   |
| 2666    | 1        | 0.93%   |
| 2134    | 1        | 0.93%   |
| 2048    | 1        | 0.93%   |
| 1866    | 1        | 0.93%   |
| 1639    | 1        | 0.93%   |
| 1334    | 1        | 0.93%   |
| 1331    | 1        | 0.93%   |
| 533     | 1        | 0.93%   |
| 400     | 1        | 0.93%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 3        | 37.5%   |
| Hewlett-Packard    | 2        | 25%     |
| Sharp              | 1        | 12.5%   |
| Fuji Xerox         | 1        | 12.5%   |
| Brother Industries | 1        | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Sharp AL-2030                 | 1        | 12.5%   |
| HP DeskJet 3700 series        | 1        | 12.5%   |
| HP Deskjet 2540 series        | 1        | 12.5%   |
| Fuji Xerox DocuPrint CM305 df | 1        | 12.5%   |
| Canon TR7500 series           | 1        | 12.5%   |
| Canon MF4010 series           | 1        | 12.5%   |
| Canon MF240 Series UFRII LT   | 1        | 12.5%   |
| Brother HL-2240 series        | 1        | 12.5%   |

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
| Logitech                      | 15       | 36.59%  |
| Microdia                      | 4        | 9.76%   |
| Generalplus Technology        | 4        | 9.76%   |
| Microsoft                     | 3        | 7.32%   |
| Sunplus Innovation Technology | 2        | 4.88%   |
| WaveRider Communications      | 1        | 2.44%   |
| ValueHD                       | 1        | 2.44%   |
| Tobii Technology AB           | 1        | 2.44%   |
| Samsung Electronics           | 1        | 2.44%   |
| Realtek Semiconductor         | 1        | 2.44%   |
| OPPO Electronics              | 1        | 2.44%   |
| Linux Foundation              | 1        | 2.44%   |
| LG Electronics                | 1        | 2.44%   |
| IPEVO                         | 1        | 2.44%   |
| Guillemot                     | 1        | 2.44%   |
| Dell                          | 1        | 2.44%   |
| Cubeternet                    | 1        | 2.44%   |
| ARC International             | 1        | 2.44%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920              | 5        | 12.2%   |
| Microsoft LifeCam HD-3000                | 2        | 4.88%   |
| Microdia Camera                          | 2        | 4.88%   |
| Logitech Webcam C270                     | 2        | 4.88%   |
| Logitech Webcam B500                     | 2        | 4.88%   |
| Generalplus GENERAL WEBCAM               | 2        | 4.88%   |
| Generalplus 808 Camera #9 (web-cam mode) | 2        | 4.88%   |
| WaveRider USB 2.0 Camera                 | 1        | 2.44%   |
| ValueHD Konftel Cam20                    | 1        | 2.44%   |
| Tobii AB EyeChip                         | 1        | 2.44%   |
| Sunplus HD 720P webcam                   | 1        | 2.44%   |
| Sunplus FHD Camera Microphone            | 1        | 2.44%   |
| Samsung Galaxy series, misc. (MTP mode)  | 1        | 2.44%   |
| Realtek Web Camera                       | 1        | 2.44%   |
| OPPO CPH1725                             | 1        | 2.44%   |
| Microsoft LifeCam Cinema                 | 1        | 2.44%   |
| Microdia USB camera                      | 1        | 2.44%   |
| Microdia Integrated Camera               | 1        | 2.44%   |
| Logitech Webcam C170                     | 1        | 2.44%   |
| Logitech QuickCam Pro for Notebooks      | 1        | 2.44%   |
| Logitech Logitech Webcam C925e           | 1        | 2.44%   |
| Logitech Logitech Webcam C160            | 1        | 2.44%   |
| Logitech HD Webcam C910                  | 1        | 2.44%   |
| Logitech B525 HD Webcam                  | 1        | 2.44%   |
| Linux Foundation EEM Gadget              | 1        | 2.44%   |
| LG Optimus (Various Models) MTP Mode     | 1        | 2.44%   |
| IPEVO V4K                                | 1        | 2.44%   |
| Guillemot Hercules HD Sunset             | 1        | 2.44%   |
| Dell Webcam WB7022                       | 1        | 2.44%   |
| Cubeternet GL-UPC822 UVC WebCam          | 1        | 2.44%   |
| ARC International Camera                 | 1        | 2.44%   |

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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Alcor Micro | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| Alcor Micro Watchdata W 1981 | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 168      | 86.15%  |
| 1     | 21       | 10.77%  |
| 2     | 3        | 1.54%   |
| 9     | 1        | 0.51%   |
| 4     | 1        | 0.51%   |
| 3     | 1        | 0.51%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 11       | 30.56%  |
| Net/wireless             | 8        | 22.22%  |
| Unassigned class         | 4        | 11.11%  |
| Sound                    | 4        | 11.11%  |
| Communication controller | 2        | 5.56%   |
| Card reader              | 2        | 5.56%   |
| Bluetooth                | 2        | 5.56%   |
| Net/ethernet             | 1        | 2.78%   |
| Chipcard                 | 1        | 2.78%   |
| Camera                   | 1        | 2.78%   |

