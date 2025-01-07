OpenMandriva 23.08 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------------

A project to collect tested hardware configurations for OpenMandriva 23.08.

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

Total: 1133

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | A55M-E33                    | [491adf615a](https://linux-hardware.org/?probe=491adf615a) | Jan 04, 2025 |
| HP            | 2AF3                        | [27a5a9b662](https://linux-hardware.org/?probe=27a5a9b662) | Jan 01, 2025 |
| MSI           | Z97 GAMING 5                | [40b22f7ebe](https://linux-hardware.org/?probe=40b22f7ebe) | Dec 30, 2024 |
| Lenovo        | ThinkCentre M90p 5536P79    | [e13ed7c057](https://linux-hardware.org/?probe=e13ed7c057) | Dec 30, 2024 |
| HP            | 805D                        | [1c1e40f526](https://linux-hardware.org/?probe=1c1e40f526) | Dec 28, 2024 |
| ASRock        | A620M-HDV/M.2               | [7bd64010ea](https://linux-hardware.org/?probe=7bd64010ea) | Dec 28, 2024 |
| ASUSTek       | D700SA                      | [cdea79b4a9](https://linux-hardware.org/?probe=cdea79b4a9) | Dec 25, 2024 |
| MSI           | A78M-E35 V2                 | [37ed0bfc1f](https://linux-hardware.org/?probe=37ed0bfc1f) | Dec 24, 2024 |
| Gigabyte      | F2A85XM-D3H                 | [5d6d1c59a4](https://linux-hardware.org/?probe=5d6d1c59a4) | Dec 21, 2024 |
| ASUSTek       | P8H61-M LX2 R2.0            | [f50786aff4](https://linux-hardware.org/?probe=f50786aff4) | Dec 19, 2024 |
| Gigabyte      | X570S AORUS PRO AX          | [f0168d3f71](https://linux-hardware.org/?probe=f0168d3f71) | Dec 19, 2024 |
| HP            | 2B2C                        | [0b3869847d](https://linux-hardware.org/?probe=0b3869847d) | Dec 17, 2024 |
| Gigabyte      | F2A68HM-HD2                 | [69b82b01c8](https://linux-hardware.org/?probe=69b82b01c8) | Dec 16, 2024 |
| Dell          | 0TDG4V A00                  | [e8c33005d3](https://linux-hardware.org/?probe=e8c33005d3) | Dec 14, 2024 |
| ASRock        | X299 Taichi XE              | [23e15f73e6](https://linux-hardware.org/?probe=23e15f73e6) | Dec 14, 2024 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [263df008c5](https://linux-hardware.org/?probe=263df008c5) | Dec 13, 2024 |
| MSI           | B250I GAMING PRO AC         | [b6c3e35ea6](https://linux-hardware.org/?probe=b6c3e35ea6) | Dec 12, 2024 |
| ASUSTek       | M2N-SLI                     | [137df4dff6](https://linux-hardware.org/?probe=137df4dff6) | Dec 12, 2024 |
| Gigabyte      | B660 GAMING X DDR4          | [1b40e982de](https://linux-hardware.org/?probe=1b40e982de) | Dec 11, 2024 |
| Gigabyte      | B450M DS3H V2               | [a60bd4a552](https://linux-hardware.org/?probe=a60bd4a552) | Dec 11, 2024 |
| Dell          | 082WXT A01                  | [2af24c92cd](https://linux-hardware.org/?probe=2af24c92cd) | Dec 08, 2024 |
| Unknown       | Unknown                     | [ed080e6dcc](https://linux-hardware.org/?probe=ed080e6dcc) | Dec 06, 2024 |
| Dell          | 0YP806 A02                  | [e738237e89](https://linux-hardware.org/?probe=e738237e89) | Dec 04, 2024 |
| Unknown       | Unknown                     | [c832be89c4](https://linux-hardware.org/?probe=c832be89c4) | Dec 03, 2024 |
| HP            | 1497                        | [a0ee162b98](https://linux-hardware.org/?probe=a0ee162b98) | Nov 23, 2024 |
| Gigabyte      | Z590 AORUS ELITE AX         | [cc54459990](https://linux-hardware.org/?probe=cc54459990) | Nov 18, 2024 |
| Dell          | 0NV0M7 A01                  | [9dfc73bd5d](https://linux-hardware.org/?probe=9dfc73bd5d) | Nov 12, 2024 |
| ASRock        | H55M                        | [dd4d6e3552](https://linux-hardware.org/?probe=dd4d6e3552) | Nov 12, 2024 |
| Intel         | DH55PJ AAE93812-302         | [f00ff7ef01](https://linux-hardware.org/?probe=f00ff7ef01) | Nov 09, 2024 |
| Gigabyte      | Z170-HD3P-CF                | [93d34614a7](https://linux-hardware.org/?probe=93d34614a7) | Nov 06, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [cfe914638e](https://linux-hardware.org/?probe=cfe914638e) | Nov 06, 2024 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | [b9654bc74b](https://linux-hardware.org/?probe=b9654bc74b) | Nov 05, 2024 |
| Lenovo        | MAHOBAY NOK                 | [039371fc2a](https://linux-hardware.org/?probe=039371fc2a) | Oct 28, 2024 |
| ASUSTek       | P5G41T-M LX2/BR             | [f714c9c792](https://linux-hardware.org/?probe=f714c9c792) | Oct 28, 2024 |
| Gigabyte      | H510M H                     | [f9526923ef](https://linux-hardware.org/?probe=f9526923ef) | Oct 24, 2024 |
| ASUSTek       | PRIME B550M-K               | [1af65cb620](https://linux-hardware.org/?probe=1af65cb620) | Oct 19, 2024 |
| Lenovo        | 0x36C017AA NOK              | [435957e3d2](https://linux-hardware.org/?probe=435957e3d2) | Oct 10, 2024 |
| MSI           | H81M-E33                    | [cd077d54a9](https://linux-hardware.org/?probe=cd077d54a9) | Oct 04, 2024 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | [ff0ca8bb9f](https://linux-hardware.org/?probe=ff0ca8bb9f) | Oct 03, 2024 |
| ASUSTek       | H61M-K                      | [634a831e43](https://linux-hardware.org/?probe=634a831e43) | Sep 30, 2024 |
| Gigabyte      | B760M GAMING X AX DDR4      | [bf4c0a4115](https://linux-hardware.org/?probe=bf4c0a4115) | Sep 28, 2024 |
| Dell          | 0HY9JP A02                  | [34ec1e561d](https://linux-hardware.org/?probe=34ec1e561d) | Sep 27, 2024 |
| Pegatron      | 2A99                        | [df53c2fdc1](https://linux-hardware.org/?probe=df53c2fdc1) | Sep 17, 2024 |
| HP            | 3397                        | [7f9f3926c3](https://linux-hardware.org/?probe=7f9f3926c3) | Sep 14, 2024 |
| Acer          | Aspire XC100A               | [1ad96742a9](https://linux-hardware.org/?probe=1ad96742a9) | Sep 08, 2024 |
| ECS           | Alhena5                     | [f5243d4e22](https://linux-hardware.org/?probe=f5243d4e22) | Sep 07, 2024 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [a841980936](https://linux-hardware.org/?probe=a841980936) | Sep 04, 2024 |
| ASUSTek       | A88X-PLUS                   | [2c57038ccf](https://linux-hardware.org/?probe=2c57038ccf) | Sep 03, 2024 |
| ASUSTek       | PRIME B550-PLUS             | [42c8ab64a2](https://linux-hardware.org/?probe=42c8ab64a2) | Sep 02, 2024 |
| ASUSTek       | P5QPL-AM                    | [9cebc8ab4a](https://linux-hardware.org/?probe=9cebc8ab4a) | Sep 01, 2024 |
| MSI           | H310M PRO-M2 PLUS           | [cc73e58de2](https://linux-hardware.org/?probe=cc73e58de2) | Sep 01, 2024 |
| ASUSTek       | PRIME H310M-E R2.0          | [fcc932f938](https://linux-hardware.org/?probe=fcc932f938) | Aug 31, 2024 |
| Lenovo        | ThinkCentre M57e 9482CP1    | [e4fb5c4a3d](https://linux-hardware.org/?probe=e4fb5c4a3d) | Aug 29, 2024 |
| ASUSTek       | K30AM-J                     | [912c2ae503](https://linux-hardware.org/?probe=912c2ae503) | Aug 29, 2024 |
| Positivo      | POS-PIG41BA POSITIVO        | [6605b92414](https://linux-hardware.org/?probe=6605b92414) | Aug 29, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6b34ecf844](https://linux-hardware.org/?probe=6b34ecf844) | Aug 26, 2024 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [95ec5259c5](https://linux-hardware.org/?probe=95ec5259c5) | Aug 25, 2024 |
| Dell          | 0F1HC1 A02                  | [480813bb87](https://linux-hardware.org/?probe=480813bb87) | Aug 19, 2024 |
| HP            | 1495                        | [732805c466](https://linux-hardware.org/?probe=732805c466) | Aug 17, 2024 |
| ASRock        | H77 Pro4-M                  | [920c2d7d1d](https://linux-hardware.org/?probe=920c2d7d1d) | Aug 15, 2024 |
| ASUSTek       | P5GC-MX/GBL                 | [ce7187e567](https://linux-hardware.org/?probe=ce7187e567) | Aug 15, 2024 |
| HP            | 3648h                       | [8c2f4df269](https://linux-hardware.org/?probe=8c2f4df269) | Aug 14, 2024 |
| Apple         | Mac-F42C88C8 Proto1         | [c5a7b37c75](https://linux-hardware.org/?probe=c5a7b37c75) | Aug 11, 2024 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [8df996f30f](https://linux-hardware.org/?probe=8df996f30f) | Aug 10, 2024 |
| Dell          | 00V62H A01                  | [c7c8508e19](https://linux-hardware.org/?probe=c7c8508e19) | Aug 09, 2024 |
| Intel         | DCP847SKE G79416-106        | [9533769267](https://linux-hardware.org/?probe=9533769267) | Aug 09, 2024 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [c6367fd908](https://linux-hardware.org/?probe=c6367fd908) | Aug 05, 2024 |
| Positivo      | POS-EC945AL                 | [4291daa596](https://linux-hardware.org/?probe=4291daa596) | Aug 02, 2024 |
| HP            | 8299                        | [9295b0b5b3](https://linux-hardware.org/?probe=9295b0b5b3) | Aug 02, 2024 |
| HP            | 1825                        | [5b9b648342](https://linux-hardware.org/?probe=5b9b648342) | Aug 02, 2024 |
| Alienware     | 0J560M A03                  | [59b665b374](https://linux-hardware.org/?probe=59b665b374) | Aug 02, 2024 |
| Fujitsu       | D3003-A1 S26361-D3003-A1    | [8a7ddf4baf](https://linux-hardware.org/?probe=8a7ddf4baf) | Aug 01, 2024 |
| Dell          | 042P49 A02                  | [7bcbf232f8](https://linux-hardware.org/?probe=7bcbf232f8) | Aug 01, 2024 |
| ASUSTek       | GA15DH                      | [20c5bb0dcd](https://linux-hardware.org/?probe=20c5bb0dcd) | Aug 01, 2024 |
| Gigabyte      | B450M DS3H-CF               | [97eeb04e17](https://linux-hardware.org/?probe=97eeb04e17) | Jul 31, 2024 |
| Biostar       | A68MHE                      | [a5f30c5c54](https://linux-hardware.org/?probe=a5f30c5c54) | Jul 31, 2024 |
| Gigabyte      | GA-A75M-UD2H                | [3476d0940e](https://linux-hardware.org/?probe=3476d0940e) | Jul 30, 2024 |
| PCWare        | IPMH61R1                    | [c865528f1c](https://linux-hardware.org/?probe=c865528f1c) | Jul 29, 2024 |
| Itautec       | ST 4254 ST-4254 Padrao 0... | [48ef85a1e7](https://linux-hardware.org/?probe=48ef85a1e7) | Jul 29, 2024 |
| Lenovo        | SHARKBAY NOK                | [30bb835251](https://linux-hardware.org/?probe=30bb835251) | Jul 28, 2024 |
| Dell          | 0NW6H5 A00                  | [acb85bcfe6](https://linux-hardware.org/?probe=acb85bcfe6) | Jul 28, 2024 |
| HP            | 339A                        | [ea89e47f4e](https://linux-hardware.org/?probe=ea89e47f4e) | Jul 27, 2024 |
| ASRock        | FM2A55M-VG3+                | [fb251e81e1](https://linux-hardware.org/?probe=fb251e81e1) | Jul 22, 2024 |
| Gigabyte      | A320M-S2H-CF                | [310f665bb6](https://linux-hardware.org/?probe=310f665bb6) | Jul 22, 2024 |
| ASUSTek       | PRIME B550M-K               | [43941683fc](https://linux-hardware.org/?probe=43941683fc) | Jul 21, 2024 |
| ASUSTek       | Z170 PRO GAMING             | [9340309f3d](https://linux-hardware.org/?probe=9340309f3d) | Jul 21, 2024 |
| Intel         | H61                         | [659abbba46](https://linux-hardware.org/?probe=659abbba46) | Jul 21, 2024 |
| HP            | 18E4                        | [bcfb2d82b4](https://linux-hardware.org/?probe=bcfb2d82b4) | Jul 20, 2024 |
| HC            | HCAR357-MI V1.0             | [5c18bea34f](https://linux-hardware.org/?probe=5c18bea34f) | Jul 20, 2024 |
| HP            | 339A                        | [2156013e3f](https://linux-hardware.org/?probe=2156013e3f) | Jul 19, 2024 |
| HP            | 0A68h                       | [6a608ec580](https://linux-hardware.org/?probe=6a608ec580) | Jul 17, 2024 |
| Biostar       | A320MH                      | [89ca8f23b5](https://linux-hardware.org/?probe=89ca8f23b5) | Jul 17, 2024 |
| Acer          | FI946GZG                    | [f43f547c9f](https://linux-hardware.org/?probe=f43f547c9f) | Jul 16, 2024 |
| ASUSTek       | VM40B                       | [f279df4081](https://linux-hardware.org/?probe=f279df4081) | Jul 15, 2024 |
| Dell          | 0MF252                      | [2451c65503](https://linux-hardware.org/?probe=2451c65503) | Jul 13, 2024 |
| PCBOX         | Kant                        | [15c4a5cbe5](https://linux-hardware.org/?probe=15c4a5cbe5) | Jul 12, 2024 |
| ASRock        | G31M-S                      | [91753f29af](https://linux-hardware.org/?probe=91753f29af) | Jul 11, 2024 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | [973f1cb205](https://linux-hardware.org/?probe=973f1cb205) | Jul 10, 2024 |
| Gigabyte      | Z490 VISION G               | [bf2543da0b](https://linux-hardware.org/?probe=bf2543da0b) | Jul 10, 2024 |
| Shuttle       | FZ270                       | [434e447cc2](https://linux-hardware.org/?probe=434e447cc2) | Jul 09, 2024 |
| Gigabyte      | P41T-D3                     | [cc80c6a7cb](https://linux-hardware.org/?probe=cc80c6a7cb) | Jul 09, 2024 |
| MSI           | KA790GX                     | [8c3c570301](https://linux-hardware.org/?probe=8c3c570301) | Jul 07, 2024 |
| HP            | 1493                        | [04b4232ad9](https://linux-hardware.org/?probe=04b4232ad9) | Jul 07, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [972c0527aa](https://linux-hardware.org/?probe=972c0527aa) | Jul 07, 2024 |
| ASRock        | FM2A68M-DG3+                | [c5062c2b4e](https://linux-hardware.org/?probe=c5062c2b4e) | Jul 07, 2024 |
| ECS           | H61H2-M2                    | [123fb7680a](https://linux-hardware.org/?probe=123fb7680a) | Jul 07, 2024 |
| Gigabyte      | H410M H                     | [4a179a1ec9](https://linux-hardware.org/?probe=4a179a1ec9) | Jul 07, 2024 |
| MSI           | 2AE0                        | [a8d3498fb0](https://linux-hardware.org/?probe=a8d3498fb0) | Jul 06, 2024 |
| ASUSTek       | A68HM-PLUS                  | [6ec43479a8](https://linux-hardware.org/?probe=6ec43479a8) | Jul 06, 2024 |
| ASRock        | H71M-DGS                    | [53971fc966](https://linux-hardware.org/?probe=53971fc966) | Jul 06, 2024 |
| Gigabyte      | G31M-ES2L                   | [bb1db7e4cf](https://linux-hardware.org/?probe=bb1db7e4cf) | Jul 06, 2024 |
| Gigabyte      | Z77M-D3H                    | [b541df6068](https://linux-hardware.org/?probe=b541df6068) | Jul 06, 2024 |
| MSI           | B550-A PRO                  | [2ee11e7de8](https://linux-hardware.org/?probe=2ee11e7de8) | Jul 06, 2024 |
| HP            | 1497                        | [be525ac03c](https://linux-hardware.org/?probe=be525ac03c) | Jul 05, 2024 |
| Dell          | 0GXM1W A00                  | [e44c5d6c4f](https://linux-hardware.org/?probe=e44c5d6c4f) | Jul 05, 2024 |
| ASUSTek       | P7P55D-E                    | [f8e0a5453b](https://linux-hardware.org/?probe=f8e0a5453b) | Jul 05, 2024 |
| Dell          | 042P49 A02                  | [e025d87bfa](https://linux-hardware.org/?probe=e025d87bfa) | Jul 05, 2024 |
| MSI           | H270 GAMING M3              | [117d7740f8](https://linux-hardware.org/?probe=117d7740f8) | Jul 05, 2024 |
| ASUSTek       | TUF Gaming B650-PLUS        | [61d934db3e](https://linux-hardware.org/?probe=61d934db3e) | Jul 05, 2024 |
| Fujitsu       | D3413-A1 S26361-D3413-A1    | [e1fab4870a](https://linux-hardware.org/?probe=e1fab4870a) | Jul 05, 2024 |
| ASUSTek       | PRIME A320M-K               | [32be2b30f2](https://linux-hardware.org/?probe=32be2b30f2) | Jul 05, 2024 |
| Fujitsu       | D3431-A1 S26361-D3431-A1    | [f45604d7f6](https://linux-hardware.org/?probe=f45604d7f6) | Jul 05, 2024 |
| Acer          | Aspire TC-875 V:1.0         | [56bb0a8004](https://linux-hardware.org/?probe=56bb0a8004) | Jul 05, 2024 |
| ASRock        | B365M IB-R                  | [b9fe5565b5](https://linux-hardware.org/?probe=b9fe5565b5) | Jul 05, 2024 |
| MSI           | PRO B760M-P                 | [bcbbe706a6](https://linux-hardware.org/?probe=bcbbe706a6) | Jul 04, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [5b82d8232e](https://linux-hardware.org/?probe=5b82d8232e) | Jul 04, 2024 |
| ASUSTek       | P5G41T-M LX2/BR             | [6df32aa15e](https://linux-hardware.org/?probe=6df32aa15e) | Jul 04, 2024 |
| Dell          | 05XGC8 A01                  | [44645f9599](https://linux-hardware.org/?probe=44645f9599) | Jul 04, 2024 |
| Acer          | Aspire XC-895 V:1.0         | [6d10ca7208](https://linux-hardware.org/?probe=6d10ca7208) | Jul 04, 2024 |
| ASUSTek       | P7H55-M LE                  | [84a42d41f7](https://linux-hardware.org/?probe=84a42d41f7) | Jul 04, 2024 |
| ASUSTek       | PRIME B450M-A               | [c5052cf8b8](https://linux-hardware.org/?probe=c5052cf8b8) | Jul 04, 2024 |
| MSI           | Z87-G41 PC Mate             | [d6e0c0e321](https://linux-hardware.org/?probe=d6e0c0e321) | Jul 04, 2024 |
| HP            | 8954                        | [e4a7684a2a](https://linux-hardware.org/?probe=e4a7684a2a) | Jul 03, 2024 |
| Dell          | 0D28YY A03                  | [e4581c717c](https://linux-hardware.org/?probe=e4581c717c) | Jul 03, 2024 |
| GEEKOM        | A8                          | [30b6883c52](https://linux-hardware.org/?probe=30b6883c52) | Jul 02, 2024 |
| Acer          | Veriton N4640G              | [316499457a](https://linux-hardware.org/?probe=316499457a) | Jul 01, 2024 |
| HP            | 0A08h                       | [3c13100cd4](https://linux-hardware.org/?probe=3c13100cd4) | Jul 01, 2024 |
| ASRock        | 970M Pro3                   | [3f4c9aeb8b](https://linux-hardware.org/?probe=3f4c9aeb8b) | Jul 01, 2024 |
| ASUSTek       | X99-A/USB                   | [f75ecb76e4](https://linux-hardware.org/?probe=f75ecb76e4) | Jun 30, 2024 |
| Unknown       | FLASH i7-11800H PLUS        | [bc4a7261d4](https://linux-hardware.org/?probe=bc4a7261d4) | Jun 30, 2024 |
| MSI           | MS-7392                     | [fbfd1ecd6e](https://linux-hardware.org/?probe=fbfd1ecd6e) | Jun 29, 2024 |
| MSI           | A88XM-E35                   | [d77265cc89](https://linux-hardware.org/?probe=d77265cc89) | Jun 29, 2024 |
| Gigabyte      | P85-D3                      | [d3f906eda8](https://linux-hardware.org/?probe=d3f906eda8) | Jun 29, 2024 |
| ASUSTek       | M5A78L-M LX3                | [7bfeaeecf5](https://linux-hardware.org/?probe=7bfeaeecf5) | Jun 28, 2024 |
| HP            | 0A98h                       | [b67771e6ef](https://linux-hardware.org/?probe=b67771e6ef) | Jun 28, 2024 |
| ASUSTek       | M5A99FX PRO R2.0            | [9964f3c440](https://linux-hardware.org/?probe=9964f3c440) | Jun 28, 2024 |
| Acer          | Aspire GX-781               | [137ae977af](https://linux-hardware.org/?probe=137ae977af) | Jun 27, 2024 |
| Gigabyte      | A320M-S2H-CF                | [a2804074c3](https://linux-hardware.org/?probe=a2804074c3) | Jun 26, 2024 |
| ASUSTek       | P5GC-MX                     | [23b3a67905](https://linux-hardware.org/?probe=23b3a67905) | Jun 25, 2024 |
| MSI           | Z490-A PRO                  | [c7fba61395](https://linux-hardware.org/?probe=c7fba61395) | Jun 25, 2024 |
| HP            | 304Bh                       | [385a52ece1](https://linux-hardware.org/?probe=385a52ece1) | Jun 23, 2024 |
| ASRock        | N68-S3 FX                   | [c67bf51171](https://linux-hardware.org/?probe=c67bf51171) | Jun 22, 2024 |
| MSI           | 785GTM-E45                  | [50af260321](https://linux-hardware.org/?probe=50af260321) | Jun 22, 2024 |
| MSI           | G41M-P33 Combo              | [dd6b3518ed](https://linux-hardware.org/?probe=dd6b3518ed) | Jun 22, 2024 |
| Pegatron      | NARRA5                      | [3f2465cb2f](https://linux-hardware.org/?probe=3f2465cb2f) | Jun 22, 2024 |
| ASRock        | J3355B-ITX                  | [fe967c69f9](https://linux-hardware.org/?probe=fe967c69f9) | Jun 21, 2024 |
| ASUSTek       | PRIME X670-P                | [157fc29a20](https://linux-hardware.org/?probe=157fc29a20) | Jun 21, 2024 |
| Gigabyte      | Z77X-D3H                    | [82c23cabe2](https://linux-hardware.org/?probe=82c23cabe2) | Jun 20, 2024 |
| Intel         | H61                         | [da1a1d129a](https://linux-hardware.org/?probe=da1a1d129a) | Jun 19, 2024 |
| HP            | 0A98h                       | [0c6652df6e](https://linux-hardware.org/?probe=0c6652df6e) | Jun 19, 2024 |
| Gigabyte      | GA-890GPA-UD3H              | [33df6bfe30](https://linux-hardware.org/?probe=33df6bfe30) | Jun 19, 2024 |
| Gigabyte      | M68MT-S2                    | [540399cfff](https://linux-hardware.org/?probe=540399cfff) | Jun 18, 2024 |
| Gigabyte      | AM1M-S2H                    | [1f1d42d470](https://linux-hardware.org/?probe=1f1d42d470) | Jun 17, 2024 |
| Intel         | B85                         | [83f3947827](https://linux-hardware.org/?probe=83f3947827) | Jun 17, 2024 |
| HP            | 18E4                        | [aa89247575](https://linux-hardware.org/?probe=aa89247575) | Jun 16, 2024 |
| MSI           | 880GM-E41                   | [1688f3e6ec](https://linux-hardware.org/?probe=1688f3e6ec) | Jun 15, 2024 |
| Unknown       | Unknown                     | [fd4fa297ee](https://linux-hardware.org/?probe=fd4fa297ee) | Jun 15, 2024 |
| Intel         | H61 V1.6B                   | [930c36f35d](https://linux-hardware.org/?probe=930c36f35d) | Jun 15, 2024 |
| ASUSTek       | M5A97 LE R2.0               | [3cb9c14764](https://linux-hardware.org/?probe=3cb9c14764) | Jun 15, 2024 |
| MSI           | Z97 GAMING 5                | [bd481829f1](https://linux-hardware.org/?probe=bd481829f1) | Jun 15, 2024 |
| Intel         | H61                         | [593dc22666](https://linux-hardware.org/?probe=593dc22666) | Jun 12, 2024 |
| TPV-INVENT... | 2AC6 A01                    | [f153cb875f](https://linux-hardware.org/?probe=f153cb875f) | Jun 12, 2024 |
| Gigabyte      | F2A68HM-H                   | [61ed5fb52e](https://linux-hardware.org/?probe=61ed5fb52e) | Jun 11, 2024 |
| Fujitsu       | D3162-B1 S26361-D3162-B1    | [c779d45043](https://linux-hardware.org/?probe=c779d45043) | Jun 11, 2024 |
| ASUSTek       | ROG Maximus Z690 HERO       | [e410fbc83c](https://linux-hardware.org/?probe=e410fbc83c) | Jun 10, 2024 |
| HP            | 3398                        | [59527c7be0](https://linux-hardware.org/?probe=59527c7be0) | Jun 10, 2024 |
| Intel         | Unknown                     | [c4f6ab3dd2](https://linux-hardware.org/?probe=c4f6ab3dd2) | Jun 09, 2024 |
| HP            | 2B36                        | [3f48e6e1f0](https://linux-hardware.org/?probe=3f48e6e1f0) | Jun 09, 2024 |
| Gigabyte      | B450 GAMING X               | [12d93a151d](https://linux-hardware.org/?probe=12d93a151d) | Jun 09, 2024 |
| Gigabyte      | H410M H V2                  | [20465abb0a](https://linux-hardware.org/?probe=20465abb0a) | Jun 07, 2024 |
| MSI           | A320M PRO-VH                | [569d81676c](https://linux-hardware.org/?probe=569d81676c) | Jun 07, 2024 |
| Huanan        | X99-F8 V2.0                 | [eba6036446](https://linux-hardware.org/?probe=eba6036446) | Jun 07, 2024 |
| Unknown       | T3 MRD                      | [ce12a5263c](https://linux-hardware.org/?probe=ce12a5263c) | Jun 06, 2024 |
| Intel         | H61                         | [59f9cc58f5](https://linux-hardware.org/?probe=59f9cc58f5) | Jun 05, 2024 |
| Pegatron      | Benicia                     | [6827b37cff](https://linux-hardware.org/?probe=6827b37cff) | Jun 05, 2024 |
| Intel         | DG41RQ AAE54511-203         | [5cd9b65fe2](https://linux-hardware.org/?probe=5cd9b65fe2) | Jun 05, 2024 |
| Biostar       | IH61MF-Q5                   | [85f2d92c2f](https://linux-hardware.org/?probe=85f2d92c2f) | Jun 05, 2024 |
| ASUSTek       | PRIME B250M-A               | [a659934c95](https://linux-hardware.org/?probe=a659934c95) | Jun 05, 2024 |
| HP            | 304Ah                       | [d7b5fb1612](https://linux-hardware.org/?probe=d7b5fb1612) | Jun 04, 2024 |
| Acer          | Veriton L4620G v1.0         | [24db2893da](https://linux-hardware.org/?probe=24db2893da) | Jun 04, 2024 |
| Gigabyte      | B450M DS3H V2               | [af058de203](https://linux-hardware.org/?probe=af058de203) | Jun 03, 2024 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [a83bb7fac6](https://linux-hardware.org/?probe=a83bb7fac6) | Jun 03, 2024 |
| Gigabyte      | G41M-Combo                  | [075953fb1c](https://linux-hardware.org/?probe=075953fb1c) | Jun 03, 2024 |
| MSI           | B450M PRO-VDH MAX           | [b29da130f8](https://linux-hardware.org/?probe=b29da130f8) | Jun 01, 2024 |
| ASUSTek       | B75M-PLUS                   | [b5b1e4990e](https://linux-hardware.org/?probe=b5b1e4990e) | Jun 01, 2024 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | [41250af6e1](https://linux-hardware.org/?probe=41250af6e1) | Jun 01, 2024 |
| Gigabyte      | F2A55M-HD2                  | [da55eec4ab](https://linux-hardware.org/?probe=da55eec4ab) | May 31, 2024 |
| ASRock        | B450 Steel Legend           | [6210e40c07](https://linux-hardware.org/?probe=6210e40c07) | May 30, 2024 |
| ASUSTek       | P9X79 WS                    | [272fdc5776](https://linux-hardware.org/?probe=272fdc5776) | May 29, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [af3d9d57b2](https://linux-hardware.org/?probe=af3d9d57b2) | May 29, 2024 |
| Intel         | D945GCPE AAD97209-201       | [4b5c79152f](https://linux-hardware.org/?probe=4b5c79152f) | May 29, 2024 |
| MACHINIST     | E5-K9 V2.1                  | [5d058e6d3e](https://linux-hardware.org/?probe=5d058e6d3e) | May 29, 2024 |
| Dell          | 0K83V0 A00                  | [6def61be90](https://linux-hardware.org/?probe=6def61be90) | May 27, 2024 |
| Biostar       | B550GTQ                     | [285d09979c](https://linux-hardware.org/?probe=285d09979c) | May 27, 2024 |
| Gigabyte      | B760 DS3H DDR4              | [6f84904cc3](https://linux-hardware.org/?probe=6f84904cc3) | May 27, 2024 |
| Gigabyte      | B760 GAMING X DDR4          | [740702872c](https://linux-hardware.org/?probe=740702872c) | May 27, 2024 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [3cbc575f22](https://linux-hardware.org/?probe=3cbc575f22) | May 24, 2024 |
| PCWare        | IPMH110G-DDR3               | [583ce9e1b1](https://linux-hardware.org/?probe=583ce9e1b1) | May 24, 2024 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | [7fd5b705f5](https://linux-hardware.org/?probe=7fd5b705f5) | May 21, 2024 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [c95d40f047](https://linux-hardware.org/?probe=c95d40f047) | May 21, 2024 |
| Dell          | 0G3HR7 A00                  | [8e85e2f4cb](https://linux-hardware.org/?probe=8e85e2f4cb) | May 20, 2024 |
| HP            | 0AECh D                     | [7173a4bf88](https://linux-hardware.org/?probe=7173a4bf88) | May 18, 2024 |
| Gigabyte      | H61M-S1                     | [0891be8a65](https://linux-hardware.org/?probe=0891be8a65) | May 15, 2024 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [f92d0dae39](https://linux-hardware.org/?probe=f92d0dae39) | May 14, 2024 |
| ECS           | BSWI-D2                     | [d8a75a2978](https://linux-hardware.org/?probe=d8a75a2978) | May 14, 2024 |
| MSI           | H61M-P20                    | [5b41f32988](https://linux-hardware.org/?probe=5b41f32988) | May 14, 2024 |
| Lenovo        | 31900058 STD                | [9eaada84d1](https://linux-hardware.org/?probe=9eaada84d1) | May 13, 2024 |
| ASRock        | FM2A68M-DG3+                | [c523181e20](https://linux-hardware.org/?probe=c523181e20) | May 13, 2024 |
| Dell          | 0WR7PY A02                  | [928f4cb666](https://linux-hardware.org/?probe=928f4cb666) | May 12, 2024 |
| Dell          | 06D7TR A02                  | [b9cd12037a](https://linux-hardware.org/?probe=b9cd12037a) | May 11, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [e0cb5549df](https://linux-hardware.org/?probe=e0cb5549df) | May 10, 2024 |
| CYBERGENO     | GENOCYBER                   | [8766fe0791](https://linux-hardware.org/?probe=8766fe0791) | May 10, 2024 |
| ASUSTek       | PRIME B560M-A AC            | [c166fb3c82](https://linux-hardware.org/?probe=c166fb3c82) | May 10, 2024 |
| HP            | 3396                        | [5e68a536f2](https://linux-hardware.org/?probe=5e68a536f2) | May 09, 2024 |
| Dell          | 0VNP2H A00                  | [28953f7c6a](https://linux-hardware.org/?probe=28953f7c6a) | May 09, 2024 |
| Gigabyte      | B450 AORUS ELITE            | [0cd34decca](https://linux-hardware.org/?probe=0cd34decca) | May 08, 2024 |
| ASRock        | B450M-HDV                   | [098e62d52a](https://linux-hardware.org/?probe=098e62d52a) | May 08, 2024 |
| Gigabyte      | H310M S2H x.x               | [97598b9cc3](https://linux-hardware.org/?probe=97598b9cc3) | May 07, 2024 |
| Intel         | DQ45CB AAE30148-207         | [263e934dc2](https://linux-hardware.org/?probe=263e934dc2) | May 07, 2024 |
| Fujitsu       | D3164-A1 S26361-D3164-A1    | [ae1edad2ab](https://linux-hardware.org/?probe=ae1edad2ab) | May 06, 2024 |
| HP            | 8053                        | [06b48e5ec6](https://linux-hardware.org/?probe=06b48e5ec6) | May 06, 2024 |
| Gigabyte      | H61M-S2PV                   | [780a67ef79](https://linux-hardware.org/?probe=780a67ef79) | May 05, 2024 |
| Lenovo        | 0B98401 WIN                 | [8d1ee988ad](https://linux-hardware.org/?probe=8d1ee988ad) | May 05, 2024 |
| Dell          | 0R6PCT A01                  | [61f596b724](https://linux-hardware.org/?probe=61f596b724) | May 04, 2024 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [64b195310b](https://linux-hardware.org/?probe=64b195310b) | May 04, 2024 |
| HP            | 339A                        | [a5f44d3bdb](https://linux-hardware.org/?probe=a5f44d3bdb) | May 04, 2024 |
| Gigabyte      | B550M DS3H AC               | [15375b5d97](https://linux-hardware.org/?probe=15375b5d97) | May 04, 2024 |
| ASUSTek       | K8V-MX                      | [64054e7bf3](https://linux-hardware.org/?probe=64054e7bf3) | May 03, 2024 |
| ASUSTek       | PRIME B460-PLUS             | [dd201d321b](https://linux-hardware.org/?probe=dd201d321b) | May 03, 2024 |
| Dell          | 0WR7PY A04                  | [b48e977e84](https://linux-hardware.org/?probe=b48e977e84) | May 03, 2024 |
| Intel         | B75                         | [4c39b0616d](https://linux-hardware.org/?probe=4c39b0616d) | May 02, 2024 |
| ASUSTek       | PRIME B660-PLUS D4          | [d7c901b5d7](https://linux-hardware.org/?probe=d7c901b5d7) | May 02, 2024 |
| Packard Be... | IMEDIA S2185                | [47d64869d6](https://linux-hardware.org/?probe=47d64869d6) | Apr 30, 2024 |
| MSI           | PRO H610M-G DDR4            | [b8ab800603](https://linux-hardware.org/?probe=b8ab800603) | Apr 30, 2024 |
| Biostar       | H310MHP                     | [1faa8b5213](https://linux-hardware.org/?probe=1faa8b5213) | Apr 30, 2024 |
| Biostar       | H310MHP                     | [d5bc5a946f](https://linux-hardware.org/?probe=d5bc5a946f) | Apr 30, 2024 |
| Lenovo        | 30C9 SEK0N11843 IOT 3806... | [517daa7c85](https://linux-hardware.org/?probe=517daa7c85) | Apr 30, 2024 |
| ASUSTek       | PRIME H410M-K               | [9c6f64ecd9](https://linux-hardware.org/?probe=9c6f64ecd9) | Apr 29, 2024 |
| ASUSTek       | H81M-P PLUS                 | [e3c17dccb5](https://linux-hardware.org/?probe=e3c17dccb5) | Apr 29, 2024 |
| Gigabyte      | GA-MA785GMT-UD2H            | [b1f251b92c](https://linux-hardware.org/?probe=b1f251b92c) | Apr 29, 2024 |
| EVGA          | NF66 2                      | [ef1a49773b](https://linux-hardware.org/?probe=ef1a49773b) | Apr 29, 2024 |
| ASUSTek       | Maximus VII HERO            | [51efe9cdc9](https://linux-hardware.org/?probe=51efe9cdc9) | Apr 28, 2024 |
| MSI           | A68HM GRENADE               | [c1a1b60624](https://linux-hardware.org/?probe=c1a1b60624) | Apr 28, 2024 |
| Intel         | D945GCL AAD67193-205        | [2520d8fe1d](https://linux-hardware.org/?probe=2520d8fe1d) | Apr 28, 2024 |
| ASUSTek       | P8H61-M LE                  | [15d91ebe7c](https://linux-hardware.org/?probe=15d91ebe7c) | Apr 28, 2024 |
| ASRock        | A320M-DVS R3.0              | [3af9ef3df5](https://linux-hardware.org/?probe=3af9ef3df5) | Apr 27, 2024 |
| MSI           | G31M3-L V2                  | [0a033139d1](https://linux-hardware.org/?probe=0a033139d1) | Apr 27, 2024 |
| HP            | 3029h                       | [70cd5cbc22](https://linux-hardware.org/?probe=70cd5cbc22) | Apr 26, 2024 |
| MSI           | B250I GAMING PRO AC         | [edf573962d](https://linux-hardware.org/?probe=edf573962d) | Apr 25, 2024 |
| MAXSUN        | MS-Terminator B550M         | [4960448326](https://linux-hardware.org/?probe=4960448326) | Apr 25, 2024 |
| HP            | 2AF7                        | [dcff3bbb91](https://linux-hardware.org/?probe=dcff3bbb91) | Apr 25, 2024 |
| Gigabyte      | F2A55M-DS2                  | [8252280757](https://linux-hardware.org/?probe=8252280757) | Apr 25, 2024 |
| Gigabyte      | EX58-UD3R                   | [826b210e79](https://linux-hardware.org/?probe=826b210e79) | Apr 24, 2024 |
| Dell          | 08NPPY A00                  | [8e54a2234f](https://linux-hardware.org/?probe=8e54a2234f) | Apr 24, 2024 |
| Acer          | Veriton X2632G V:1.0        | [88daeba4af](https://linux-hardware.org/?probe=88daeba4af) | Apr 23, 2024 |
| Gigabyte      | Z390 UD                     | [36a382f0da](https://linux-hardware.org/?probe=36a382f0da) | Apr 23, 2024 |
| ASUSTek       | A68HM-PLUS                  | [c495b7e3d7](https://linux-hardware.org/?probe=c495b7e3d7) | Apr 23, 2024 |
| ASRock        | G31M-S                      | [591e58940a](https://linux-hardware.org/?probe=591e58940a) | Apr 22, 2024 |
| Dell          | 0VHXCD A01                  | [4b7a01c41a](https://linux-hardware.org/?probe=4b7a01c41a) | Apr 22, 2024 |
| MSI           | MPG X570 GAMING EDGE WIF... | [a2b7475561](https://linux-hardware.org/?probe=a2b7475561) | Apr 21, 2024 |
| Positivo      | POS-PIG41BA POSITIVO        | [d5e1581050](https://linux-hardware.org/?probe=d5e1581050) | Apr 21, 2024 |
| Acer          | WG43M                       | [93fcdbd13d](https://linux-hardware.org/?probe=93fcdbd13d) | Apr 20, 2024 |
| HP            | 339A                        | [8cb48fe045](https://linux-hardware.org/?probe=8cb48fe045) | Apr 19, 2024 |
| MSI           | MS-7235                     | [d0b1ac0e44](https://linux-hardware.org/?probe=d0b1ac0e44) | Apr 19, 2024 |
| MSI           | B85I                        | [8751cf893f](https://linux-hardware.org/?probe=8751cf893f) | Apr 19, 2024 |
| Dell          | 0Y958C A00                  | [88a0060933](https://linux-hardware.org/?probe=88a0060933) | Apr 18, 2024 |
| ASUSTek       | P9X79                       | [3f587bf3dd](https://linux-hardware.org/?probe=3f587bf3dd) | Apr 18, 2024 |
| ASUSTek       | P8Z77-V LX                  | [686220b484](https://linux-hardware.org/?probe=686220b484) | Apr 17, 2024 |
| Pegatron      | Narra6                      | [fb336cac9b](https://linux-hardware.org/?probe=fb336cac9b) | Apr 17, 2024 |
| Intel         | H61                         | [e0bacf6b01](https://linux-hardware.org/?probe=e0bacf6b01) | Apr 17, 2024 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [41c197d579](https://linux-hardware.org/?probe=41c197d579) | Apr 16, 2024 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [4fb5756438](https://linux-hardware.org/?probe=4fb5756438) | Apr 14, 2024 |
| Lenovo        | Win8 Pro DPK TPG            | [c6fd918c6e](https://linux-hardware.org/?probe=c6fd918c6e) | Apr 14, 2024 |
| ASUSTek       | PRIME H610M-K D4            | [ca76c3d3ec](https://linux-hardware.org/?probe=ca76c3d3ec) | Apr 13, 2024 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | [2998b9027d](https://linux-hardware.org/?probe=2998b9027d) | Apr 13, 2024 |
| Dell          | OptiPlex 7050               | [e6f968f709](https://linux-hardware.org/?probe=e6f968f709) | Apr 11, 2024 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | [5757303d9a](https://linux-hardware.org/?probe=5757303d9a) | Apr 11, 2024 |
| Dell          | 0NKW6Y A02                  | [fcd30b6392](https://linux-hardware.org/?probe=fcd30b6392) | Apr 11, 2024 |
| HP            | 1998                        | [4e592f29d7](https://linux-hardware.org/?probe=4e592f29d7) | Apr 11, 2024 |
| Foxconn       | 2A8C                        | [9d16faea24](https://linux-hardware.org/?probe=9d16faea24) | Apr 10, 2024 |
| ASUSTek       | H61M-C                      | [a0e36b103b](https://linux-hardware.org/?probe=a0e36b103b) | Apr 10, 2024 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [1163ac6ace](https://linux-hardware.org/?probe=1163ac6ace) | Apr 09, 2024 |
| MSI           | G41M-P26                    | [c337a993c8](https://linux-hardware.org/?probe=c337a993c8) | Apr 07, 2024 |
| ASUSTek       | M4A88T-M/USB3               | [69cf49e1b1](https://linux-hardware.org/?probe=69cf49e1b1) | Apr 07, 2024 |
| Intel         | B75                         | [7ac22ca55d](https://linux-hardware.org/?probe=7ac22ca55d) | Apr 07, 2024 |
| Dell          | 0KP561                      | [dd6f49d82f](https://linux-hardware.org/?probe=dd6f49d82f) | Apr 06, 2024 |
| Gigabyte      | H410M S2H V2                | [2713f1fbb2](https://linux-hardware.org/?probe=2713f1fbb2) | Apr 06, 2024 |
| Unknown       | Unknown                     | [0f08ac20fe](https://linux-hardware.org/?probe=0f08ac20fe) | Apr 06, 2024 |
| HP            | 1497                        | [bc9fcab61a](https://linux-hardware.org/?probe=bc9fcab61a) | Apr 06, 2024 |
| HP            | 1790                        | [0038bf2917](https://linux-hardware.org/?probe=0038bf2917) | Apr 06, 2024 |
| Biostar       | TB250-BTC PRO               | [3fceee8ca7](https://linux-hardware.org/?probe=3fceee8ca7) | Apr 06, 2024 |
| Dell          | 02YYK5 A01                  | [e407d84cc9](https://linux-hardware.org/?probe=e407d84cc9) | Apr 06, 2024 |
| ASRock        | H87 Pro4                    | [46c9acd849](https://linux-hardware.org/?probe=46c9acd849) | Apr 05, 2024 |
| Gigabyte      | GA-78LMT-S2 R2 sex          | [2d8c4c947f](https://linux-hardware.org/?probe=2d8c4c947f) | Apr 05, 2024 |
| Lenovo        | ThinkCentre M90p 5536P79    | [1750bd22db](https://linux-hardware.org/?probe=1750bd22db) | Apr 05, 2024 |
| Shenzhen M... | F7BFC                       | [4b0127a449](https://linux-hardware.org/?probe=4b0127a449) | Apr 04, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [e3541ebcf4](https://linux-hardware.org/?probe=e3541ebcf4) | Apr 03, 2024 |
| Dell          | 051FJ8 A00                  | [8f67355bed](https://linux-hardware.org/?probe=8f67355bed) | Apr 03, 2024 |
| HP            | 3396                        | [641a1891ba](https://linux-hardware.org/?probe=641a1891ba) | Apr 02, 2024 |
| Dell          | 0XFWHV A00                  | [ea24de6920](https://linux-hardware.org/?probe=ea24de6920) | Apr 02, 2024 |
| Gigabyte      | GA-770T-D3L                 | [402894f9cd](https://linux-hardware.org/?probe=402894f9cd) | Apr 01, 2024 |
| Intel         | H81                         | [b7c3224542](https://linux-hardware.org/?probe=b7c3224542) | Apr 01, 2024 |
| HP            | 2171                        | [3cd1f729a4](https://linux-hardware.org/?probe=3cd1f729a4) | Apr 01, 2024 |
| QIYIDA        | X79-M6 V1.0                 | [ab18c6c58f](https://linux-hardware.org/?probe=ab18c6c58f) | Mar 31, 2024 |
| Pegatron      | Benicia                     | [22f74ed745](https://linux-hardware.org/?probe=22f74ed745) | Mar 31, 2024 |
| Gigabyte      | B550M DS3H                  | [2ec08fd0c4](https://linux-hardware.org/?probe=2ec08fd0c4) | Mar 31, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [30575319dc](https://linux-hardware.org/?probe=30575319dc) | Mar 31, 2024 |
| ASUSTek       | P8Z77-V PREMIUM             | [3c3064e23a](https://linux-hardware.org/?probe=3c3064e23a) | Mar 31, 2024 |
| Dell          | 0H634K A00                  | [cd85e4d384](https://linux-hardware.org/?probe=cd85e4d384) | Mar 30, 2024 |
| Positivo      | POS-AG31AP                  | [606557f097](https://linux-hardware.org/?probe=606557f097) | Mar 30, 2024 |
| ASUSTek       | SABERTOOTH X99              | [9eadaaa051](https://linux-hardware.org/?probe=9eadaaa051) | Mar 29, 2024 |
| Gigabyte      | B560M DS3H V2               | [f99b737a3e](https://linux-hardware.org/?probe=f99b737a3e) | Mar 29, 2024 |
| GEEKOM        | A5                          | [c7e07714cc](https://linux-hardware.org/?probe=c7e07714cc) | Mar 28, 2024 |
| HP            | 2AE3                        | [f068c22e6c](https://linux-hardware.org/?probe=f068c22e6c) | Mar 28, 2024 |
| Dell          | 0YXT71 A03                  | [d854505a5b](https://linux-hardware.org/?probe=d854505a5b) | Mar 27, 2024 |
| HP            | 2AA6 PVT                    | [899a3e57bb](https://linux-hardware.org/?probe=899a3e57bb) | Mar 27, 2024 |
| ASRock        | H310CM-HDV                  | [b4c034c103](https://linux-hardware.org/?probe=b4c034c103) | Mar 26, 2024 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [3f052410d3](https://linux-hardware.org/?probe=3f052410d3) | Mar 26, 2024 |
| Dell          | 088DT1 A01                  | [de5dac0125](https://linux-hardware.org/?probe=de5dac0125) | Mar 26, 2024 |
| ASRock        | H110M-HG4                   | [0ef9ca77ad](https://linux-hardware.org/?probe=0ef9ca77ad) | Mar 26, 2024 |
| Dell          | 07WP95 A01                  | [1c4843f354](https://linux-hardware.org/?probe=1c4843f354) | Mar 26, 2024 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [786693fab4](https://linux-hardware.org/?probe=786693fab4) | Mar 25, 2024 |
| ASUSTek       | TUF B360M-PLUS GAMING       | [000bb993d1](https://linux-hardware.org/?probe=000bb993d1) | Mar 25, 2024 |
| MSI           | H110M PRO-VD                | [c250bda654](https://linux-hardware.org/?probe=c250bda654) | Mar 25, 2024 |
| Pegatron      | 2AB5                        | [713be0f3f0](https://linux-hardware.org/?probe=713be0f3f0) | Mar 25, 2024 |
| Dell          | 084J0R A00                  | [691f19e56c](https://linux-hardware.org/?probe=691f19e56c) | Mar 24, 2024 |
| ASUSTek       | TUF Z390M-PRO GAMING        | [45e2102834](https://linux-hardware.org/?probe=45e2102834) | Mar 23, 2024 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | [5a656756e0](https://linux-hardware.org/?probe=5a656756e0) | Mar 22, 2024 |
| ASRock        | A320M-HDV                   | [69bd8b3475](https://linux-hardware.org/?probe=69bd8b3475) | Mar 22, 2024 |
| AMI           | Intel                       | [4bb3934f7d](https://linux-hardware.org/?probe=4bb3934f7d) | Mar 21, 2024 |
| Intel         | X99                         | [c85af1f29d](https://linux-hardware.org/?probe=c85af1f29d) | Mar 21, 2024 |
| Casper        | NIRVANA DESKTOP             | [6428f854e6](https://linux-hardware.org/?probe=6428f854e6) | Mar 21, 2024 |
| HP            | 8768 A                      | [6c296786d2](https://linux-hardware.org/?probe=6c296786d2) | Mar 19, 2024 |
| Foxconn       | 2ABF                        | [cec4a4b661](https://linux-hardware.org/?probe=cec4a4b661) | Mar 19, 2024 |
| Lenovo        | 30C0 SDK0J40705 WIN 3425... | [fac66be915](https://linux-hardware.org/?probe=fac66be915) | Mar 19, 2024 |
| ASUSTek       | PRIME B450-PLUS             | [345e2df2db](https://linux-hardware.org/?probe=345e2df2db) | Mar 19, 2024 |
| HP            | 0B4Ch D                     | [e85fec8591](https://linux-hardware.org/?probe=e85fec8591) | Mar 18, 2024 |
| MSI           | X99A RAIDER                 | [8d5dfb7293](https://linux-hardware.org/?probe=8d5dfb7293) | Mar 18, 2024 |
| ASRock        | X470 Taichi                 | [195c54fe84](https://linux-hardware.org/?probe=195c54fe84) | Mar 17, 2024 |
| ASUSTek       | PRIME Z790-P                | [82c42946af](https://linux-hardware.org/?probe=82c42946af) | Mar 17, 2024 |
| MSI           | B560M PRO-E                 | [2e1e84fe15](https://linux-hardware.org/?probe=2e1e84fe15) | Mar 16, 2024 |
| HP            | 097Ch                       | [23bc1b2344](https://linux-hardware.org/?probe=23bc1b2344) | Mar 15, 2024 |
| AZW           | MINI S 10                   | [843a0455d6](https://linux-hardware.org/?probe=843a0455d6) | Mar 15, 2024 |
| MSI           | Z270 PC MATE                | [87ef1a815e](https://linux-hardware.org/?probe=87ef1a815e) | Mar 15, 2024 |
| Gigabyte      | Z68MA-D2H-B3                | [708c2c7987](https://linux-hardware.org/?probe=708c2c7987) | Mar 15, 2024 |
| MSI           | B85M-G43                    | [c1b1061c0d](https://linux-hardware.org/?probe=c1b1061c0d) | Mar 14, 2024 |
| MSI           | MPG X570 GAMING EDGE WIF... | [4c8d39a7ab](https://linux-hardware.org/?probe=4c8d39a7ab) | Mar 14, 2024 |
| Gigabyte      | 945GCMX-S2                  | [fa1bce30a0](https://linux-hardware.org/?probe=fa1bce30a0) | Mar 13, 2024 |
| ASUSTek       | P5G41T-M LX                 | [d89d81deb7](https://linux-hardware.org/?probe=d89d81deb7) | Mar 12, 2024 |
| OEM           | X79-Turbo                   | [b19889facd](https://linux-hardware.org/?probe=b19889facd) | Mar 12, 2024 |
| Intel         | B75                         | [f78757e7b2](https://linux-hardware.org/?probe=f78757e7b2) | Mar 11, 2024 |
| Dell          | 0KV62T A00                  | [fba62e6832](https://linux-hardware.org/?probe=fba62e6832) | Mar 11, 2024 |
| Gigabyte      | X299 AORUS Gaming-CF        | [a32383cf3e](https://linux-hardware.org/?probe=a32383cf3e) | Mar 09, 2024 |
| ASUSTek       | PRIME H510M-E               | [2171fc67cb](https://linux-hardware.org/?probe=2171fc67cb) | Mar 07, 2024 |
| MSI           | B550-A PRO                  | [1df3b86749](https://linux-hardware.org/?probe=1df3b86749) | Mar 06, 2024 |
| MSI           | MAG X570S TORPEDO MAX       | [3a31238bd4](https://linux-hardware.org/?probe=3a31238bd4) | Mar 05, 2024 |
| Intel         | DH77EB AAG39073-304         | [b0109a5dac](https://linux-hardware.org/?probe=b0109a5dac) | Mar 05, 2024 |
| Acer          | Veriton N4630G              | [53fb2ce231](https://linux-hardware.org/?probe=53fb2ce231) | Mar 05, 2024 |
| Dell          | 0GM819                      | [82f828df2c](https://linux-hardware.org/?probe=82f828df2c) | Mar 04, 2024 |
| Dell          | 0GM819                      | [1cae3bcd28](https://linux-hardware.org/?probe=1cae3bcd28) | Mar 04, 2024 |
| HP            | 2B1B                        | [a8d024554f](https://linux-hardware.org/?probe=a8d024554f) | Mar 04, 2024 |
| Gigabyte      | B550 AORUS PRO AC           | [5e2bacbc0c](https://linux-hardware.org/?probe=5e2bacbc0c) | Mar 02, 2024 |
| ASRock        | G41C-GS R2.0                | [c57846f189](https://linux-hardware.org/?probe=c57846f189) | Mar 01, 2024 |
| ASUSTek       | VANGUARD B85                | [70712f8f34](https://linux-hardware.org/?probe=70712f8f34) | Feb 28, 2024 |
| HP            | 304Ah                       | [f01c7352de](https://linux-hardware.org/?probe=f01c7352de) | Feb 27, 2024 |
| HP            | 1497                        | [58e91b7bbc](https://linux-hardware.org/?probe=58e91b7bbc) | Feb 26, 2024 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | [fc8733df5b](https://linux-hardware.org/?probe=fc8733df5b) | Feb 26, 2024 |
| Intel         | D54250WYK H13922-303        | [125932cb50](https://linux-hardware.org/?probe=125932cb50) | Feb 26, 2024 |
| Gigabyte      | A320M-S2H-CF                | [4e50b74dd4](https://linux-hardware.org/?probe=4e50b74dd4) | Feb 22, 2024 |
| ASUSTek       | M4N68T-M-LE-V2              | [177b3e8210](https://linux-hardware.org/?probe=177b3e8210) | Feb 21, 2024 |
| ASUSTek       | PRIME B760M-A               | [df41ae1364](https://linux-hardware.org/?probe=df41ae1364) | Feb 20, 2024 |
| ASRock        | QC6000M                     | [c262bb8499](https://linux-hardware.org/?probe=c262bb8499) | Feb 20, 2024 |
| HP            | 8459                        | [50c9809b3f](https://linux-hardware.org/?probe=50c9809b3f) | Feb 18, 2024 |
| Gigabyte      | G41MT-S2PT                  | [dca61882f5](https://linux-hardware.org/?probe=dca61882f5) | Feb 18, 2024 |
| Dell          | 042P49 A02                  | [cae0de6242](https://linux-hardware.org/?probe=cae0de6242) | Feb 16, 2024 |
| Dell          | 0D441T A01                  | [13ad4a683c](https://linux-hardware.org/?probe=13ad4a683c) | Feb 15, 2024 |
| Positivo      | POS-MIG31AG                 | [73530ca4c9](https://linux-hardware.org/?probe=73530ca4c9) | Feb 15, 2024 |
| AMD           | A88DA                       | [89ca695711](https://linux-hardware.org/?probe=89ca695711) | Feb 14, 2024 |
| ASUSTek       | H81M-D                      | [9df4273ea0](https://linux-hardware.org/?probe=9df4273ea0) | Feb 14, 2024 |
| Acer          | Aspire TC-1660 V:1.1        | [1c0656fae9](https://linux-hardware.org/?probe=1c0656fae9) | Feb 14, 2024 |
| ECS           | G31T-M7                     | [7a7105d6d8](https://linux-hardware.org/?probe=7a7105d6d8) | Feb 14, 2024 |
| Unknown       | Unknown                     | [599636c242](https://linux-hardware.org/?probe=599636c242) | Feb 12, 2024 |
| Pegatron      | 2AC3                        | [a9575c488b](https://linux-hardware.org/?probe=a9575c488b) | Feb 11, 2024 |
| ASUSTek       | P8P67 PRO                   | [5b06c8344c](https://linux-hardware.org/?probe=5b06c8344c) | Feb 11, 2024 |
| ASUSTek       | P5B                         | [3b213fb567](https://linux-hardware.org/?probe=3b213fb567) | Feb 10, 2024 |
| ASUSTek       | CROSSHAIR VI HERO           | [9f43349b7d](https://linux-hardware.org/?probe=9f43349b7d) | Feb 10, 2024 |
| HP            | 3647h                       | [f504108ab7](https://linux-hardware.org/?probe=f504108ab7) | Feb 10, 2024 |
| MSI           | H81M-E33                    | [df8bed98ed](https://linux-hardware.org/?probe=df8bed98ed) | Feb 10, 2024 |
| Gigabyte      | B550 AORUS ELITE            | [7fbd70f2fa](https://linux-hardware.org/?probe=7fbd70f2fa) | Feb 10, 2024 |
| Positivo      | POS-PIG41BAG                | [ad94b1b798](https://linux-hardware.org/?probe=ad94b1b798) | Feb 10, 2024 |
| HP            | 3646h                       | [711bc33a9e](https://linux-hardware.org/?probe=711bc33a9e) | Feb 10, 2024 |
| ASRock        | N68-GS                      | [06f147ad72](https://linux-hardware.org/?probe=06f147ad72) | Feb 09, 2024 |
| Gigabyte      | B75M-D3V                    | [142b258a2b](https://linux-hardware.org/?probe=142b258a2b) | Feb 08, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [1e2d466f1b](https://linux-hardware.org/?probe=1e2d466f1b) | Feb 08, 2024 |
| ASUSTek       | PRIME Z370-A                | [a63089827b](https://linux-hardware.org/?probe=a63089827b) | Feb 08, 2024 |
| ASUSTek       | A68HM-PLUS                  | [214df7602f](https://linux-hardware.org/?probe=214df7602f) | Feb 07, 2024 |
| ASRock        | P5B-DE                      | [34550c52b4](https://linux-hardware.org/?probe=34550c52b4) | Feb 05, 2024 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [c2ec630f3d](https://linux-hardware.org/?probe=c2ec630f3d) | Feb 04, 2024 |
| HP            | 339A                        | [e8e666af64](https://linux-hardware.org/?probe=e8e666af64) | Feb 02, 2024 |
| HP            | 18E7                        | [84caef4dde](https://linux-hardware.org/?probe=84caef4dde) | Feb 02, 2024 |
| Dell          | 0WMJ54 A00                  | [d6c3c89e3d](https://linux-hardware.org/?probe=d6c3c89e3d) | Feb 02, 2024 |
| Dell          | 0215PR A05                  | [05183a71ef](https://linux-hardware.org/?probe=05183a71ef) | Feb 01, 2024 |
| ASUSTek       | PRIME B650-PLUS             | [c83dcb11ca](https://linux-hardware.org/?probe=c83dcb11ca) | Jan 31, 2024 |
| ASUSTek       | M5A97 R2.0                  | [bf9814808f](https://linux-hardware.org/?probe=bf9814808f) | Jan 31, 2024 |
| HP            | 8B3C A                      | [12ec418267](https://linux-hardware.org/?probe=12ec418267) | Jan 31, 2024 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [2a526e4632](https://linux-hardware.org/?probe=2a526e4632) | Jan 30, 2024 |
| Gigabyte      | X570 GAMING X               | [3418c8d84c](https://linux-hardware.org/?probe=3418c8d84c) | Jan 30, 2024 |
| Dell          | 0GDG8Y A00                  | [9cbabba588](https://linux-hardware.org/?probe=9cbabba588) | Jan 29, 2024 |
| AZW           | MINI S 10                   | [d707319ed7](https://linux-hardware.org/?probe=d707319ed7) | Jan 29, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c9d5d0fa7b](https://linux-hardware.org/?probe=c9d5d0fa7b) | Jan 29, 2024 |
| Dell          | 0J3C2F A00                  | [95ae5646c8](https://linux-hardware.org/?probe=95ae5646c8) | Jan 29, 2024 |
| HP            | 3396                        | [b59e0b4023](https://linux-hardware.org/?probe=b59e0b4023) | Jan 29, 2024 |
| Gigabyte      | EP45T-UD3R                  | [d3aaef580d](https://linux-hardware.org/?probe=d3aaef580d) | Jan 28, 2024 |
| ASRock        | B760M-HDV/M.2 D4            | [56ef6ba880](https://linux-hardware.org/?probe=56ef6ba880) | Jan 28, 2024 |
| ASRock        | B450 Gaming K4              | [9cee6b0a5b](https://linux-hardware.org/?probe=9cee6b0a5b) | Jan 27, 2024 |
| ASRock        | H470 Phantom Gaming 4       | [dc402c3f43](https://linux-hardware.org/?probe=dc402c3f43) | Jan 27, 2024 |
| Gigabyte      | 945GCM-S2L                  | [4490f8e838](https://linux-hardware.org/?probe=4490f8e838) | Jan 27, 2024 |
| HP            | 82F2 A01                    | [437bec28fa](https://linux-hardware.org/?probe=437bec28fa) | Jan 26, 2024 |
| Gigabyte      | B550M DS3H                  | [347b980bdf](https://linux-hardware.org/?probe=347b980bdf) | Jan 25, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [ff7fd4d2cd](https://linux-hardware.org/?probe=ff7fd4d2cd) | Jan 24, 2024 |
| ASUSTek       | PRIME A320M-K               | [5c2e73a06a](https://linux-hardware.org/?probe=5c2e73a06a) | Jan 23, 2024 |
| Gigabyte      | H61M-S1                     | [91f61c4366](https://linux-hardware.org/?probe=91f61c4366) | Jan 23, 2024 |
| Intel         | Unknown                     | [8427ffd0dc](https://linux-hardware.org/?probe=8427ffd0dc) | Jan 23, 2024 |
| MSI           | MAG X570S TORPEDO MAX       | [97f9705158](https://linux-hardware.org/?probe=97f9705158) | Jan 22, 2024 |
| HP            | 18E5                        | [69ba380344](https://linux-hardware.org/?probe=69ba380344) | Jan 21, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [ec963a72d8](https://linux-hardware.org/?probe=ec963a72d8) | Jan 21, 2024 |
| Casper        | NIRVANA NOTEBOOK            | [af055c48ff](https://linux-hardware.org/?probe=af055c48ff) | Jan 21, 2024 |
| Intel         | DZ77GA-70K AAG39009-500     | [cba7125977](https://linux-hardware.org/?probe=cba7125977) | Jan 20, 2024 |
| Dell          | 042P49 A02                  | [366d017089](https://linux-hardware.org/?probe=366d017089) | Jan 20, 2024 |
| ASUSTek       | PRIME A320M-K               | [58be81f7c1](https://linux-hardware.org/?probe=58be81f7c1) | Jan 20, 2024 |
| Gigabyte      | A320M-S2H-CF                | [39cd221e89](https://linux-hardware.org/?probe=39cd221e89) | Jan 20, 2024 |
| HP            | 8055                        | [5e6a445b12](https://linux-hardware.org/?probe=5e6a445b12) | Jan 19, 2024 |
| ASUSTek       | K30AD_M31AD_M51AD           | [8d2bc7b076](https://linux-hardware.org/?probe=8d2bc7b076) | Jan 18, 2024 |
| Biostar       | A770E                       | [a149b3aeb6](https://linux-hardware.org/?probe=a149b3aeb6) | Jan 17, 2024 |
| ASUSTek       | Z97-DELUXE                  | [f414f21db4](https://linux-hardware.org/?probe=f414f21db4) | Jan 16, 2024 |
| ASUSTek       | H81M-K                      | [c1f78ee398](https://linux-hardware.org/?probe=c1f78ee398) | Jan 16, 2024 |
| MSI           | A320M-A PRO                 | [4f2655db6f](https://linux-hardware.org/?probe=4f2655db6f) | Jan 14, 2024 |
| Positivo      | POS-EINM10CB POSITIVO       | [ed11587f82](https://linux-hardware.org/?probe=ed11587f82) | Jan 14, 2024 |
| Gigabyte      | EX58-UD3R                   | [b62ae21449](https://linux-hardware.org/?probe=b62ae21449) | Jan 13, 2024 |
| Gigabyte      | H510M H V2                  | [1340d91b43](https://linux-hardware.org/?probe=1340d91b43) | Jan 13, 2024 |
| Dell          | 0W2F8G A01                  | [959d868bbf](https://linux-hardware.org/?probe=959d868bbf) | Jan 13, 2024 |
| Gigabyte      | H97M-Gaming 3               | [6230f1ef11](https://linux-hardware.org/?probe=6230f1ef11) | Jan 12, 2024 |
| MSI           | B450M-A PRO MAX             | [50ca06fa28](https://linux-hardware.org/?probe=50ca06fa28) | Jan 11, 2024 |
| ASUSTek       | PRIME Z270-P                | [bf8ac62321](https://linux-hardware.org/?probe=bf8ac62321) | Jan 11, 2024 |
| Intel         | H81                         | [1a1c6de235](https://linux-hardware.org/?probe=1a1c6de235) | Jan 10, 2024 |
| ASRock        | Q1900B-ITX                  | [610dfd5b71](https://linux-hardware.org/?probe=610dfd5b71) | Jan 10, 2024 |
| MSI           | 970A-G43                    | [00e0cf9c8d](https://linux-hardware.org/?probe=00e0cf9c8d) | Jan 09, 2024 |
| OEM           | B75 Ver:1.41                | [5466b2e4af](https://linux-hardware.org/?probe=5466b2e4af) | Jan 08, 2024 |
| Lenovo        | ThinkCentre M72e 0896A2G    | [b77ad754ae](https://linux-hardware.org/?probe=b77ad754ae) | Jan 08, 2024 |
| Gigabyte      | B450M K-CF                  | [6ffbab86cc](https://linux-hardware.org/?probe=6ffbab86cc) | Jan 07, 2024 |
| Dell          | 00V62H A01                  | [6fcf0891d9](https://linux-hardware.org/?probe=6fcf0891d9) | Jan 07, 2024 |
| Gigabyte      | MZBSWAP-00                  | [eb3700b576](https://linux-hardware.org/?probe=eb3700b576) | Jan 06, 2024 |
| Shenzhen M... | F7BFC                       | [59d6a69f30](https://linux-hardware.org/?probe=59d6a69f30) | Jan 05, 2024 |
| Shenzhen M... | F7BFC                       | [d8ed7241cb](https://linux-hardware.org/?probe=d8ed7241cb) | Jan 05, 2024 |
| Intel         | JSL MRD                     | [8b1f990d75](https://linux-hardware.org/?probe=8b1f990d75) | Jan 05, 2024 |
| Acer          | Veriton M2630G V:1.0        | [40d6bf6d97](https://linux-hardware.org/?probe=40d6bf6d97) | Jan 05, 2024 |
| ASUSTek       | M5A78L-M LX3 PLUS           | [d53af9a54d](https://linux-hardware.org/?probe=d53af9a54d) | Jan 03, 2024 |
| ASUSTek       | Maximus V GENE              | [e62026b868](https://linux-hardware.org/?probe=e62026b868) | Jan 02, 2024 |
| ASUSTek       | M2N68-AM SE2                | [553bcade60](https://linux-hardware.org/?probe=553bcade60) | Jan 01, 2024 |
| Gigabyte      | G41M-Combo                  | [0a6df1d55f](https://linux-hardware.org/?probe=0a6df1d55f) | Dec 28, 2023 |
| Intel         | H61                         | [baec7a3074](https://linux-hardware.org/?probe=baec7a3074) | Dec 28, 2023 |
| MSI           | MS-B9311                    | [424154cf65](https://linux-hardware.org/?probe=424154cf65) | Dec 28, 2023 |
| Acer          | Predator Orion PO5-620      | [2d7731ff10](https://linux-hardware.org/?probe=2d7731ff10) | Dec 26, 2023 |
| HP            | 82F1                        | [86959f8199](https://linux-hardware.org/?probe=86959f8199) | Dec 24, 2023 |
| ASUSTek       | P5GC-MX/1333                | [a95c11e27b](https://linux-hardware.org/?probe=a95c11e27b) | Dec 23, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [a84743b247](https://linux-hardware.org/?probe=a84743b247) | Dec 23, 2023 |
| Foxconn       | 2ABF                        | [3441aa81e6](https://linux-hardware.org/?probe=3441aa81e6) | Dec 23, 2023 |
| Lenovo        | SHARKBAY SDK0J40705 WIN ... | [739d4b0840](https://linux-hardware.org/?probe=739d4b0840) | Dec 23, 2023 |
| Dell          | 0X7841                      | [3757ec7f5f](https://linux-hardware.org/?probe=3757ec7f5f) | Dec 22, 2023 |
| ASUSTek       | P7H55-M LE                  | [d15476594e](https://linux-hardware.org/?probe=d15476594e) | Dec 22, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [be8f1bf021](https://linux-hardware.org/?probe=be8f1bf021) | Dec 22, 2023 |
| HP            | 2B28                        | [a3c79770af](https://linux-hardware.org/?probe=a3c79770af) | Dec 21, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [2675cca8c2](https://linux-hardware.org/?probe=2675cca8c2) | Dec 21, 2023 |
| ECS           | H81H3-MV                    | [95bd5100ac](https://linux-hardware.org/?probe=95bd5100ac) | Dec 20, 2023 |
| Gigabyte      | 970-GAMING                  | [403d617fdd](https://linux-hardware.org/?probe=403d617fdd) | Dec 19, 2023 |
| Gigabyte      | Z77X-UP5 TH-CF              | [ee9b8f604a](https://linux-hardware.org/?probe=ee9b8f604a) | Dec 19, 2023 |
| Dell          | 0T10XW A00                  | [ffff088d9c](https://linux-hardware.org/?probe=ffff088d9c) | Dec 18, 2023 |
| Foxconn       | 2ABF                        | [907abd30c7](https://linux-hardware.org/?probe=907abd30c7) | Dec 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [5c8981cf69](https://linux-hardware.org/?probe=5c8981cf69) | Dec 17, 2023 |
| ASRock        | 970M Pro3                   | [1e7fb2b8d8](https://linux-hardware.org/?probe=1e7fb2b8d8) | Dec 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [41fd53bbff](https://linux-hardware.org/?probe=41fd53bbff) | Dec 16, 2023 |
| HP            | 3647h                       | [4feaf76045](https://linux-hardware.org/?probe=4feaf76045) | Dec 16, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [72b7f2d771](https://linux-hardware.org/?probe=72b7f2d771) | Dec 16, 2023 |
| Gigabyte      | P55A-UD3                    | [485f360521](https://linux-hardware.org/?probe=485f360521) | Dec 15, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [a2e31b8b20](https://linux-hardware.org/?probe=a2e31b8b20) | Dec 15, 2023 |
| ASUSTek       | H81M-CS/BR                  | [39094226f9](https://linux-hardware.org/?probe=39094226f9) | Dec 15, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [8939c99ccb](https://linux-hardware.org/?probe=8939c99ccb) | Dec 15, 2023 |
| ASUSTek       | PRIME B460M-A               | [1c7f9648af](https://linux-hardware.org/?probe=1c7f9648af) | Dec 14, 2023 |
| HP            | 1495                        | [bd97989dd8](https://linux-hardware.org/?probe=bd97989dd8) | Dec 14, 2023 |
| ASUSTek       | PRIME H270-PRO              | [b701b34038](https://linux-hardware.org/?probe=b701b34038) | Dec 14, 2023 |
| ASRock        | G41M-VS3                    | [313b058c8c](https://linux-hardware.org/?probe=313b058c8c) | Dec 14, 2023 |
| ASRock        | AB350M-HDV                  | [945274527c](https://linux-hardware.org/?probe=945274527c) | Dec 13, 2023 |
| HP            | 18E5                        | [8195da7520](https://linux-hardware.org/?probe=8195da7520) | Dec 13, 2023 |
| Positivo      | POS-PIH81DL                 | [55cf834e17](https://linux-hardware.org/?probe=55cf834e17) | Dec 13, 2023 |
| HP            | 8169                        | [e0549dcc03](https://linux-hardware.org/?probe=e0549dcc03) | Dec 12, 2023 |
| MSI           | A88XM GAMING                | [1f17749a2e](https://linux-hardware.org/?probe=1f17749a2e) | Dec 12, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | [0e87f04695](https://linux-hardware.org/?probe=0e87f04695) | Dec 12, 2023 |
| Dell          | 0TNDVR A00                  | [4a4ab03bc7](https://linux-hardware.org/?probe=4a4ab03bc7) | Dec 11, 2023 |
| Dell          | 0GXM1W A00                  | [1b4243a8d7](https://linux-hardware.org/?probe=1b4243a8d7) | Dec 11, 2023 |
| Gigabyte      | Z77-DS3H                    | [03c91234ae](https://linux-hardware.org/?probe=03c91234ae) | Dec 11, 2023 |
| Gigabyte      | H310M DS2 x.x               | [6150f23143](https://linux-hardware.org/?probe=6150f23143) | Dec 10, 2023 |
| Gigabyte      | P67A-UD3P-B3                | [e96b9306cb](https://linux-hardware.org/?probe=e96b9306cb) | Dec 10, 2023 |
| HP            | 2B29                        | [6fb328f58e](https://linux-hardware.org/?probe=6fb328f58e) | Dec 10, 2023 |
| HP            | 3047h                       | [b4e9ee347f](https://linux-hardware.org/?probe=b4e9ee347f) | Dec 10, 2023 |
| ASUSTek       | PRIME Z270M-PLUS            | [5c1ffcfbe3](https://linux-hardware.org/?probe=5c1ffcfbe3) | Dec 09, 2023 |
| MSI           | B450-A PRO MAX              | [c576c4fbae](https://linux-hardware.org/?probe=c576c4fbae) | Dec 09, 2023 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | [a4eb4e410e](https://linux-hardware.org/?probe=a4eb4e410e) | Dec 08, 2023 |
| Biostar       | A520MH                      | [de9fc0f8f2](https://linux-hardware.org/?probe=de9fc0f8f2) | Dec 07, 2023 |
| Dell          | 0HN7XN A01                  | [986d7f4d8f](https://linux-hardware.org/?probe=986d7f4d8f) | Dec 07, 2023 |
| HP            | 21B4 A01                    | [a8f5a67f32](https://linux-hardware.org/?probe=a8f5a67f32) | Dec 07, 2023 |
| Foxconn       | 2A8C                        | [2a4412d268](https://linux-hardware.org/?probe=2a4412d268) | Dec 06, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [1f2c85d176](https://linux-hardware.org/?probe=1f2c85d176) | Dec 06, 2023 |
| ASUSTek       | H110M-A/M.2                 | [f15eca360f](https://linux-hardware.org/?probe=f15eca360f) | Dec 06, 2023 |
| ASUSTek       | PRIME A520M-A II            | [a2e7a10bdf](https://linux-hardware.org/?probe=a2e7a10bdf) | Dec 05, 2023 |
| Gigabyte      | A320M-H-CF                  | [4d14243cb9](https://linux-hardware.org/?probe=4d14243cb9) | Dec 05, 2023 |
| Gigabyte      | Z68XP-UD4                   | [3cdd72e242](https://linux-hardware.org/?probe=3cdd72e242) | Dec 05, 2023 |
| Foxconn       | 2ABF                        | [9478c73013](https://linux-hardware.org/?probe=9478c73013) | Dec 05, 2023 |
| Dell          | 02N3WF A03                  | [2974cc160f](https://linux-hardware.org/?probe=2974cc160f) | Dec 05, 2023 |
| Acer          | Veriton S6620G v1.0         | [34095bbfed](https://linux-hardware.org/?probe=34095bbfed) | Dec 04, 2023 |
| HP            | 1998                        | [50a48ad374](https://linux-hardware.org/?probe=50a48ad374) | Dec 04, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [f013a81cbb](https://linux-hardware.org/?probe=f013a81cbb) | Dec 03, 2023 |
| ASRock        | B450 Gaming K4              | [b877f8ccda](https://linux-hardware.org/?probe=b877f8ccda) | Dec 03, 2023 |
| HP            | 3397                        | [b6c4db2738](https://linux-hardware.org/?probe=b6c4db2738) | Dec 03, 2023 |
| HP            | 8169                        | [6bdddabb7f](https://linux-hardware.org/?probe=6bdddabb7f) | Dec 03, 2023 |
| ASUSTek       | P7P55 LX                    | [0d59473ae1](https://linux-hardware.org/?probe=0d59473ae1) | Dec 02, 2023 |
| Intel         | X99                         | [e96bed5f38](https://linux-hardware.org/?probe=e96bed5f38) | Dec 02, 2023 |
| MSI           | B85M-E43 DASH               | [b9caa2d56f](https://linux-hardware.org/?probe=b9caa2d56f) | Dec 02, 2023 |
| ASUSTek       | H81M-K                      | [8f5c7fb36e](https://linux-hardware.org/?probe=8f5c7fb36e) | Dec 02, 2023 |
| Gigabyte      | B450M DS3H-CF               | [5f195d4731](https://linux-hardware.org/?probe=5f195d4731) | Dec 02, 2023 |
| Dell          | 0T10XW A02                  | [ddb5b7cd64](https://linux-hardware.org/?probe=ddb5b7cd64) | Dec 01, 2023 |
| HP            | 8459                        | [b7a22ecb3f](https://linux-hardware.org/?probe=b7a22ecb3f) | Dec 01, 2023 |
| Intel         | DG41RQ AAE54511-205         | [8646f4d21b](https://linux-hardware.org/?probe=8646f4d21b) | Dec 01, 2023 |
| ASUSTek       | PRIME A320M-K               | [ed158c0464](https://linux-hardware.org/?probe=ed158c0464) | Dec 01, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [436f0406e4](https://linux-hardware.org/?probe=436f0406e4) | Dec 01, 2023 |
| Gigabyte      | B250-D3A-CF                 | [5d3de45ec6](https://linux-hardware.org/?probe=5d3de45ec6) | Dec 01, 2023 |
| Intel         | X99H                        | [147f088343](https://linux-hardware.org/?probe=147f088343) | Dec 01, 2023 |
| ASRock        | Z790 Taichi                 | [915505c787](https://linux-hardware.org/?probe=915505c787) | Nov 30, 2023 |
| Gigabyte      | H61M-S1                     | [cc54ea37ef](https://linux-hardware.org/?probe=cc54ea37ef) | Nov 30, 2023 |
| ASUSTek       | PRIME Z790M-PLUS D4         | [3630fd2945](https://linux-hardware.org/?probe=3630fd2945) | Nov 30, 2023 |
| AZW           | U59                         | [eccee157da](https://linux-hardware.org/?probe=eccee157da) | Nov 30, 2023 |
| Gigabyte      | H81M-S2H                    | [b23f24b006](https://linux-hardware.org/?probe=b23f24b006) | Nov 30, 2023 |
| HP            | 1495                        | [9dcb53a8c2](https://linux-hardware.org/?probe=9dcb53a8c2) | Nov 30, 2023 |
| Gigabyte      | B75M-D3H                    | [6a3776da6b](https://linux-hardware.org/?probe=6a3776da6b) | Nov 29, 2023 |
| ASUSTek       | PRIME A320M-K               | [1537766927](https://linux-hardware.org/?probe=1537766927) | Nov 29, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [1b2c06817f](https://linux-hardware.org/?probe=1b2c06817f) | Nov 29, 2023 |
| Unknown       | Intel BayTrail Series R1... | [6ab4075642](https://linux-hardware.org/?probe=6ab4075642) | Nov 29, 2023 |
| HP            | 8053                        | [6d6877e008](https://linux-hardware.org/?probe=6d6877e008) | Nov 29, 2023 |
| Lenovo        | SHARKBAY SDK0E50515 STD     | [d87ba8d291](https://linux-hardware.org/?probe=d87ba8d291) | Nov 29, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [fc4e66ac12](https://linux-hardware.org/?probe=fc4e66ac12) | Nov 29, 2023 |
| MSI           | A320M-A PRO                 | [96af3871d2](https://linux-hardware.org/?probe=96af3871d2) | Nov 29, 2023 |
| Fujitsu       | D2924-A1 S26361-D2924-A1    | [a06c08c462](https://linux-hardware.org/?probe=a06c08c462) | Nov 28, 2023 |
| ASUSTek       | PRIME A320M-K               | [7c53518c08](https://linux-hardware.org/?probe=7c53518c08) | Nov 28, 2023 |
| Gigabyte      | H310M DS2                   | [14a8656c8b](https://linux-hardware.org/?probe=14a8656c8b) | Nov 28, 2023 |
| HP            | 1497                        | [6cd2fea9bd](https://linux-hardware.org/?probe=6cd2fea9bd) | Nov 28, 2023 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | [9e6c582721](https://linux-hardware.org/?probe=9e6c582721) | Nov 28, 2023 |
| Gigabyte      | G31-S3G                     | [895a8554b4](https://linux-hardware.org/?probe=895a8554b4) | Nov 28, 2023 |
| HP            | 18E5                        | [a9c04bd2c7](https://linux-hardware.org/?probe=a9c04bd2c7) | Nov 28, 2023 |
| Biostar       | H310MHP                     | [58282ae6c7](https://linux-hardware.org/?probe=58282ae6c7) | Nov 28, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [7c4bb8dad1](https://linux-hardware.org/?probe=7c4bb8dad1) | Nov 28, 2023 |
| Gigabyte      | P67A-D3-B3                  | [fc4a8c9532](https://linux-hardware.org/?probe=fc4a8c9532) | Nov 27, 2023 |
| Lenovo        | ThinkCentre M58p 6137A1G    | [fafec0e338](https://linux-hardware.org/?probe=fafec0e338) | Nov 27, 2023 |
| ASRock        | H510M-HVS R2.0              | [e8867e4bb9](https://linux-hardware.org/?probe=e8867e4bb9) | Nov 27, 2023 |
| Gigabyte      | G41MT-S2P                   | [0ff86eddc6](https://linux-hardware.org/?probe=0ff86eddc6) | Nov 27, 2023 |
| ASUSTek       | M5A97 R2.0                  | [8885a17766](https://linux-hardware.org/?probe=8885a17766) | Nov 27, 2023 |
| Intel         | H61                         | [97a16fcd1b](https://linux-hardware.org/?probe=97a16fcd1b) | Nov 27, 2023 |
| Dell          | 0CU409                      | [328adb4fd0](https://linux-hardware.org/?probe=328adb4fd0) | Nov 27, 2023 |
| Intel         | X99H                        | [2cbd1213a8](https://linux-hardware.org/?probe=2cbd1213a8) | Nov 27, 2023 |
| HP            | 83EE                        | [4a9e67adc6](https://linux-hardware.org/?probe=4a9e67adc6) | Nov 27, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [dda972d27c](https://linux-hardware.org/?probe=dda972d27c) | Nov 26, 2023 |
| Dell          | 07KY25 A01                  | [98134987bb](https://linux-hardware.org/?probe=98134987bb) | Nov 26, 2023 |
| Shenzhen M... | F7BAA                       | [8c0edc3315](https://linux-hardware.org/?probe=8c0edc3315) | Nov 26, 2023 |
| Dell          | 0WR7PY A01                  | [cceb19120f](https://linux-hardware.org/?probe=cceb19120f) | Nov 26, 2023 |
| MSI           | MS-B1711                    | [963341bb09](https://linux-hardware.org/?probe=963341bb09) | Nov 26, 2023 |
| ASRock        | 4X4-4000 Series             | [d9c6907311](https://linux-hardware.org/?probe=d9c6907311) | Nov 26, 2023 |
| ASRock        | 970A-G                      | [aabcb223d0](https://linux-hardware.org/?probe=aabcb223d0) | Nov 26, 2023 |
| ASUSTek       | Rampage V EXTREME           | [2d09c86fa7](https://linux-hardware.org/?probe=2d09c86fa7) | Nov 26, 2023 |
| ASUSTek       | P8Z77-M                     | [2009f6493b](https://linux-hardware.org/?probe=2009f6493b) | Nov 26, 2023 |
| Foxconn       | 2ADA                        | [0f5aa8a55b](https://linux-hardware.org/?probe=0f5aa8a55b) | Nov 26, 2023 |
| Gigabyte      | B75M-D3H                    | [454b211624](https://linux-hardware.org/?probe=454b211624) | Nov 25, 2023 |
| Minix         | H61M-USB3 V1.2              | [2024379183](https://linux-hardware.org/?probe=2024379183) | Nov 25, 2023 |
| Dell          | 0K83V0 A00                  | [0ffd410841](https://linux-hardware.org/?probe=0ffd410841) | Nov 25, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [4e8b656513](https://linux-hardware.org/?probe=4e8b656513) | Nov 24, 2023 |
| MSI           | Z87-G41 PC Mate             | [a56a424940](https://linux-hardware.org/?probe=a56a424940) | Nov 24, 2023 |
| ASUSTek       | P8H77-M LE                  | [39919b75ba](https://linux-hardware.org/?probe=39919b75ba) | Nov 24, 2023 |
| MSI           | A68HM-E33 V2                | [e257380edc](https://linux-hardware.org/?probe=e257380edc) | Nov 23, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [4b2a2cc667](https://linux-hardware.org/?probe=4b2a2cc667) | Nov 23, 2023 |
| ASRock        | A320M-HDV R4.0              | [a67ae23c5a](https://linux-hardware.org/?probe=a67ae23c5a) | Nov 23, 2023 |
| Gigabyte      | 970A-DS3P FX                | [eff4442629](https://linux-hardware.org/?probe=eff4442629) | Nov 22, 2023 |
| Gigabyte      | H510M H                     | [078c28606a](https://linux-hardware.org/?probe=078c28606a) | Nov 21, 2023 |
| Gigabyte      | B75M-D3H                    | [5be7c208c3](https://linux-hardware.org/?probe=5be7c208c3) | Nov 20, 2023 |
| ECS           | H61H2-M2                    | [29293282c2](https://linux-hardware.org/?probe=29293282c2) | Nov 20, 2023 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | [6ed1f31ed3](https://linux-hardware.org/?probe=6ed1f31ed3) | Nov 20, 2023 |
| HP            | 89B5 A                      | [4c228a49ce](https://linux-hardware.org/?probe=4c228a49ce) | Nov 20, 2023 |
| ASRock        | B660M-STX                   | [883a70813a](https://linux-hardware.org/?probe=883a70813a) | Nov 19, 2023 |
| ASUSTek       | PRIME H510M-K               | [4243816d27](https://linux-hardware.org/?probe=4243816d27) | Nov 19, 2023 |
| ASUSTek       | M2NPV-VM                    | [be4bd9aeaf](https://linux-hardware.org/?probe=be4bd9aeaf) | Nov 18, 2023 |
| HP            | 8055                        | [1125d976fc](https://linux-hardware.org/?probe=1125d976fc) | Nov 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ff84b6e035](https://linux-hardware.org/?probe=ff84b6e035) | Nov 17, 2023 |
| ASUSTek       | P5SD2-VM                    | [8fa21e29e3](https://linux-hardware.org/?probe=8fa21e29e3) | Nov 17, 2023 |
| ASUSTek       | P5G41T-M LX                 | [63ba7cf0b1](https://linux-hardware.org/?probe=63ba7cf0b1) | Nov 16, 2023 |
| Inventec      | D CLASS A02                 | [e8f9a52206](https://linux-hardware.org/?probe=e8f9a52206) | Nov 16, 2023 |
| Gigabyte      | 970A-DS3P FX                | [5b960b8464](https://linux-hardware.org/?probe=5b960b8464) | Nov 16, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [160e8325ba](https://linux-hardware.org/?probe=160e8325ba) | Nov 15, 2023 |
| Unknown       | T3 MRD                      | [f4a73d26e0](https://linux-hardware.org/?probe=f4a73d26e0) | Nov 15, 2023 |
| ASUSTek       | P5GC-MX/CKD/SI              | [08053c4143](https://linux-hardware.org/?probe=08053c4143) | Nov 15, 2023 |
| MSI           | Z97-G43                     | [ea16582cb2](https://linux-hardware.org/?probe=ea16582cb2) | Nov 14, 2023 |
| MSI           | A88X-G45 GAMING             | [5ab91132ea](https://linux-hardware.org/?probe=5ab91132ea) | Nov 14, 2023 |
| HP            | 09F0h                       | [1c1ab6c56f](https://linux-hardware.org/?probe=1c1ab6c56f) | Nov 12, 2023 |
| Dell          | 018D1Y A00                  | [4a14d46e6b](https://linux-hardware.org/?probe=4a14d46e6b) | Nov 12, 2023 |
| MSI           | B350 TOMAHAWK ARCTIC        | [cccbd25b73](https://linux-hardware.org/?probe=cccbd25b73) | Nov 12, 2023 |
| Dell          | 0KWVT8 A03                  | [fcc17bd8a1](https://linux-hardware.org/?probe=fcc17bd8a1) | Nov 12, 2023 |
| HP            | 1850                        | [117ab7ea0d](https://linux-hardware.org/?probe=117ab7ea0d) | Nov 11, 2023 |
| Gigabyte      | Z77-D3H                     | [9c852b1f0b](https://linux-hardware.org/?probe=9c852b1f0b) | Nov 11, 2023 |
| Minix         | NEO Z83-4 V1.5              | [3623dfcb88](https://linux-hardware.org/?probe=3623dfcb88) | Nov 10, 2023 |
| Intel         | DG35EC AAE29266-210         | [fe0e055f82](https://linux-hardware.org/?probe=fe0e055f82) | Nov 10, 2023 |
| HP            | 339A                        | [7be77c764f](https://linux-hardware.org/?probe=7be77c764f) | Nov 09, 2023 |
| MSI           | A320M-A PRO                 | [9f16fd11b7](https://linux-hardware.org/?probe=9f16fd11b7) | Nov 09, 2023 |
| Gigabyte      | H110M-S2H-CF                | [10f68961cf](https://linux-hardware.org/?probe=10f68961cf) | Nov 08, 2023 |
| Gigabyte      | G41MT-S2                    | [c301ae970c](https://linux-hardware.org/?probe=c301ae970c) | Nov 08, 2023 |
| Dell          | 082WXT A01                  | [41e56ed8e4](https://linux-hardware.org/?probe=41e56ed8e4) | Nov 08, 2023 |
| HP            | 339A                        | [cdcbe8d47d](https://linux-hardware.org/?probe=cdcbe8d47d) | Nov 07, 2023 |
| Foxconn       | 2AAF                        | [fc483856a6](https://linux-hardware.org/?probe=fc483856a6) | Nov 07, 2023 |
| ASUSTek       | H81M-K                      | [3de6cf8221](https://linux-hardware.org/?probe=3de6cf8221) | Nov 07, 2023 |
| Gigabyte      | F2A68HM-HD2                 | [c376116add](https://linux-hardware.org/?probe=c376116add) | Nov 06, 2023 |
| Gigabyte      | A320M-H-CF                  | [105d51f329](https://linux-hardware.org/?probe=105d51f329) | Nov 05, 2023 |
| HP            | 802F                        | [8fe557cc85](https://linux-hardware.org/?probe=8fe557cc85) | Nov 05, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [2710dfedf4](https://linux-hardware.org/?probe=2710dfedf4) | Nov 05, 2023 |
| ASRock        | 970 Pro3 R2.0               | [f070e73453](https://linux-hardware.org/?probe=f070e73453) | Nov 05, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [459eb3cd2a](https://linux-hardware.org/?probe=459eb3cd2a) | Nov 04, 2023 |
| Acer          | Aspire M1920                | [f6ffcb0c41](https://linux-hardware.org/?probe=f6ffcb0c41) | Nov 04, 2023 |
| Gigabyte      | GA-870A-USB3L               | [d2412dfd7c](https://linux-hardware.org/?probe=d2412dfd7c) | Nov 04, 2023 |
| ASUSTek       | H110M-D                     | [03303fa6ed](https://linux-hardware.org/?probe=03303fa6ed) | Nov 04, 2023 |
| MSI           | H110M PRO-D                 | [da5c3ffb7e](https://linux-hardware.org/?probe=da5c3ffb7e) | Nov 02, 2023 |
| ASRock        | H81M-HG4 R4.0               | [0f5f162498](https://linux-hardware.org/?probe=0f5f162498) | Nov 02, 2023 |
| Gigabyte      | B75M-HD3                    | [e27c813285](https://linux-hardware.org/?probe=e27c813285) | Oct 31, 2023 |
| Intel         | B75                         | [a46db29108](https://linux-hardware.org/?probe=a46db29108) | Oct 29, 2023 |
| ASUSTek       | PRIME B250-PRO              | [ac060a5eb6](https://linux-hardware.org/?probe=ac060a5eb6) | Oct 29, 2023 |
| Dell          | 03NVJ6 A01                  | [09d76f025a](https://linux-hardware.org/?probe=09d76f025a) | Oct 29, 2023 |
| Gigabyte      | H61MA-D3V                   | [0c4d99e9dc](https://linux-hardware.org/?probe=0c4d99e9dc) | Oct 29, 2023 |
| Gigabyte      | 970A-DS3P                   | [31d6b19c8d](https://linux-hardware.org/?probe=31d6b19c8d) | Oct 29, 2023 |
| Koloe         | X58                         | [91fbabe04c](https://linux-hardware.org/?probe=91fbabe04c) | Oct 29, 2023 |
| ASRock        | B450 Steel Legend           | [21beb00969](https://linux-hardware.org/?probe=21beb00969) | Oct 28, 2023 |
| Unknown       | Phitronics G31VS-M          | [10bcfab3cb](https://linux-hardware.org/?probe=10bcfab3cb) | Oct 28, 2023 |
| Gigabyte      | Z370M D3H-CF                | [80b6c027b0](https://linux-hardware.org/?probe=80b6c027b0) | Oct 27, 2023 |
| ASUSTek       | A68HM-PLUS                  | [9d662bd187](https://linux-hardware.org/?probe=9d662bd187) | Oct 27, 2023 |
| ASUSTek       | M5A78L-M LX3                | [d3dacafdc2](https://linux-hardware.org/?probe=d3dacafdc2) | Oct 26, 2023 |
| Dell          | 03NJH0 A01                  | [dbb152a219](https://linux-hardware.org/?probe=dbb152a219) | Oct 26, 2023 |
| MSI           | H110M PRO-VD                | [b62701c032](https://linux-hardware.org/?probe=b62701c032) | Oct 25, 2023 |
| Lenovo        | ThinkCentre M90 5485W2L     | [0fcc4fe794](https://linux-hardware.org/?probe=0fcc4fe794) | Oct 24, 2023 |
| EPSON DIRE... | AT992E                      | [b61468f9c5](https://linux-hardware.org/?probe=b61468f9c5) | Oct 24, 2023 |
| Lenovo        | 30C7 SDK0J40709 WIN 3259... | [71fd7dde1d](https://linux-hardware.org/?probe=71fd7dde1d) | Oct 23, 2023 |
| MSI           | PRO Z690-P DDR4             | [35e54833e8](https://linux-hardware.org/?probe=35e54833e8) | Oct 23, 2023 |
| HP            | 3397                        | [3f8e8810c1](https://linux-hardware.org/?probe=3f8e8810c1) | Oct 23, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [3e46064143](https://linux-hardware.org/?probe=3e46064143) | Oct 22, 2023 |
| ASUSTek       | H170 PRO GAMING             | [859edb18bd](https://linux-hardware.org/?probe=859edb18bd) | Oct 21, 2023 |
| ASUSTek       | PRIME B250M-A               | [ff0d8bbab4](https://linux-hardware.org/?probe=ff0d8bbab4) | Oct 21, 2023 |
| ASUSTek       | P5KPL-AM                    | [b5bf9b7639](https://linux-hardware.org/?probe=b5bf9b7639) | Oct 21, 2023 |
| MSI           | G41TM-P31                   | [3ed69770a6](https://linux-hardware.org/?probe=3ed69770a6) | Oct 20, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [3fd9b0b53f](https://linux-hardware.org/?probe=3fd9b0b53f) | Oct 20, 2023 |
| Intel         | DH55HC AAE70933-505         | [f1bc373847](https://linux-hardware.org/?probe=f1bc373847) | Oct 19, 2023 |
| Gigabyte      | Z370 HD3P-CF                | [0994d6d9a2](https://linux-hardware.org/?probe=0994d6d9a2) | Oct 18, 2023 |
| ASUSTek       | PRIME H510M-A               | [04e9833b48](https://linux-hardware.org/?probe=04e9833b48) | Oct 18, 2023 |
| Acer          | Veriton X2660G              | [d122988e18](https://linux-hardware.org/?probe=d122988e18) | Oct 17, 2023 |
| ASRock        | X470 Master SLI/ac          | [9258f94300](https://linux-hardware.org/?probe=9258f94300) | Oct 17, 2023 |
| Shenzhen M... | F7BSC                       | [8522bfdadd](https://linux-hardware.org/?probe=8522bfdadd) | Oct 16, 2023 |
| MSI           | Z97A GAMING 7               | [8af7152ba5](https://linux-hardware.org/?probe=8af7152ba5) | Oct 16, 2023 |
| ASRock        | N68-S3 FX                   | [b1a36d42aa](https://linux-hardware.org/?probe=b1a36d42aa) | Oct 16, 2023 |
| Gigabyte      | GA-E350N-USB3               | [62f5ab12ea](https://linux-hardware.org/?probe=62f5ab12ea) | Oct 15, 2023 |
| Gigabyte      | GA-78LMT-S2 R2              | [038f59eb24](https://linux-hardware.org/?probe=038f59eb24) | Oct 15, 2023 |
| Intel         | DG41RQ AAE54511-203         | [64738e1724](https://linux-hardware.org/?probe=64738e1724) | Oct 15, 2023 |
| PCWare        | IPMH61R1                    | [145dc39d14](https://linux-hardware.org/?probe=145dc39d14) | Oct 14, 2023 |
| ASUSTek       | P8Q77-M                     | [ed4ca29c66](https://linux-hardware.org/?probe=ed4ca29c66) | Oct 14, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [babe25d4ce](https://linux-hardware.org/?probe=babe25d4ce) | Oct 14, 2023 |
| HP            | 1495                        | [e524318d58](https://linux-hardware.org/?probe=e524318d58) | Oct 13, 2023 |
| ASUSTek       | P5Q3 DELUXE                 | [29bb46e198](https://linux-hardware.org/?probe=29bb46e198) | Oct 12, 2023 |
| ASRock        | A320M-HDV R4.0              | [d1d30ae371](https://linux-hardware.org/?probe=d1d30ae371) | Oct 10, 2023 |
| Lenovo        | ThinkCentre M90p 5536W67    | [3e075f72d8](https://linux-hardware.org/?probe=3e075f72d8) | Oct 09, 2023 |
| ASUSTek       | PRIME B450M-K II            | [a3401cc125](https://linux-hardware.org/?probe=a3401cc125) | Oct 09, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [0bf2deeb16](https://linux-hardware.org/?probe=0bf2deeb16) | Oct 07, 2023 |
| Dell          | 0M5DCD A00                  | [30d2522c95](https://linux-hardware.org/?probe=30d2522c95) | Oct 07, 2023 |
| Intel         | H61                         | [a37805d0d3](https://linux-hardware.org/?probe=a37805d0d3) | Oct 07, 2023 |
| ASRock        | N68C-GS FX                  | [cfafd2008d](https://linux-hardware.org/?probe=cfafd2008d) | Oct 07, 2023 |
| MSI           | 09AC                        | [f70ac0139f](https://linux-hardware.org/?probe=f70ac0139f) | Oct 07, 2023 |
| AZW           | Green G4 10                 | [d8fb758dec](https://linux-hardware.org/?probe=d8fb758dec) | Oct 07, 2023 |
| MACHINIST     | E5-MR9A PRO V1.2            | [668d09e797](https://linux-hardware.org/?probe=668d09e797) | Oct 07, 2023 |
| Lenovo        | ThinkCentre xxx 7090A17     | [669bc2a016](https://linux-hardware.org/?probe=669bc2a016) | Oct 06, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [bc448fbb82](https://linux-hardware.org/?probe=bc448fbb82) | Oct 05, 2023 |
| MSI           | B450-A PRO MAX              | [6e8b2e49f0](https://linux-hardware.org/?probe=6e8b2e49f0) | Oct 05, 2023 |
| HP            | 3397                        | [e77e1b6391](https://linux-hardware.org/?probe=e77e1b6391) | Oct 04, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [a72a2ee89e](https://linux-hardware.org/?probe=a72a2ee89e) | Oct 04, 2023 |
| HP            | 1825                        | [d326bc59ff](https://linux-hardware.org/?probe=d326bc59ff) | Oct 04, 2023 |
| ECS           | H61H2-MV                    | [51ec04551f](https://linux-hardware.org/?probe=51ec04551f) | Oct 04, 2023 |
| Lenovo        | NOK                         | [dd6bffed79](https://linux-hardware.org/?probe=dd6bffed79) | Oct 04, 2023 |
| HP            | 3646h                       | [f39e9c8741](https://linux-hardware.org/?probe=f39e9c8741) | Oct 04, 2023 |
| Intel         | JSL MRD                     | [5a4bfcaba3](https://linux-hardware.org/?probe=5a4bfcaba3) | Oct 03, 2023 |
| Intel         | DG41RQ AAE54511-202         | [5d2ec27525](https://linux-hardware.org/?probe=5d2ec27525) | Oct 03, 2023 |
| Dell          | 0Y3R3K A03                  | [0675277f70](https://linux-hardware.org/?probe=0675277f70) | Oct 03, 2023 |
| Dell          | 0GXM1W A00                  | [fe83d524fb](https://linux-hardware.org/?probe=fe83d524fb) | Oct 02, 2023 |
| AZW           | MINI S 10                   | [13e3a733fd](https://linux-hardware.org/?probe=13e3a733fd) | Oct 01, 2023 |
| Gigabyte      | Z77X-UD5H                   | [def4633785](https://linux-hardware.org/?probe=def4633785) | Oct 01, 2023 |
| ASUSTek       | B85M-G                      | [0166816d1b](https://linux-hardware.org/?probe=0166816d1b) | Oct 01, 2023 |
| ASUSTek       | H110M-R                     | [b8aadf6823](https://linux-hardware.org/?probe=b8aadf6823) | Sep 30, 2023 |
| ASUSTek       | P5B-E Plus                  | [78c413cac5](https://linux-hardware.org/?probe=78c413cac5) | Sep 30, 2023 |
| AZW           | MINI S 10                   | [e065b9c701](https://linux-hardware.org/?probe=e065b9c701) | Sep 30, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [d0fea1d86b](https://linux-hardware.org/?probe=d0fea1d86b) | Sep 29, 2023 |
| Intel         | H110D4-P1                   | [ccedaaab02](https://linux-hardware.org/?probe=ccedaaab02) | Sep 29, 2023 |
| Lenovo        | H410                        | [f49a6ce32f](https://linux-hardware.org/?probe=f49a6ce32f) | Sep 28, 2023 |
| ASUSTek       | M2N-E SLI                   | [2a5937c5e5](https://linux-hardware.org/?probe=2a5937c5e5) | Sep 28, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [a1ef1eb6e6](https://linux-hardware.org/?probe=a1ef1eb6e6) | Sep 28, 2023 |
| ASUSTek       | D700MD                      | [91740e63b9](https://linux-hardware.org/?probe=91740e63b9) | Sep 27, 2023 |
| Pegatron      | EVANS                       | [b9347254b0](https://linux-hardware.org/?probe=b9347254b0) | Sep 25, 2023 |
| ASRock        | X370 Pro4                   | [1939307392](https://linux-hardware.org/?probe=1939307392) | Sep 25, 2023 |
| Biostar       | B550MH                      | [4ef9bbad17](https://linux-hardware.org/?probe=4ef9bbad17) | Sep 24, 2023 |
| Gigabyte      | X299 AORUS Gaming-CF        | [4c6071b20c](https://linux-hardware.org/?probe=4c6071b20c) | Sep 24, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [c0e3bef058](https://linux-hardware.org/?probe=c0e3bef058) | Sep 24, 2023 |
| ASUSTek       | Z97-C                       | [e4c1f075b9](https://linux-hardware.org/?probe=e4c1f075b9) | Sep 23, 2023 |
| ASUSTek       | A88XM-A                     | [c2cb8052f9](https://linux-hardware.org/?probe=c2cb8052f9) | Sep 23, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [46a99bb50a](https://linux-hardware.org/?probe=46a99bb50a) | Sep 23, 2023 |
| Gigabyte      | Z68X-UD3H-B3                | [92e5dde8b3](https://linux-hardware.org/?probe=92e5dde8b3) | Sep 23, 2023 |
| Shuttle       | XS36V                       | [dbcb5658e4](https://linux-hardware.org/?probe=dbcb5658e4) | Sep 23, 2023 |
| ASUSTek       | P7P55-M                     | [f5b912e122](https://linux-hardware.org/?probe=f5b912e122) | Sep 22, 2023 |
| Positivo      | POS-AG31AP                  | [2e2072e3ca](https://linux-hardware.org/?probe=2e2072e3ca) | Sep 21, 2023 |
| Megaware      | MW-HDC-M 02/24/2012 - ME... | [d3c9063140](https://linux-hardware.org/?probe=d3c9063140) | Sep 21, 2023 |
| Dell          | 0KRC95 A00                  | [61ae2b85c5](https://linux-hardware.org/?probe=61ae2b85c5) | Sep 21, 2023 |
| Gigabyte      | B560M DS3H V2               | [182384fdaa](https://linux-hardware.org/?probe=182384fdaa) | Sep 20, 2023 |
| MSI           | Indio                       | [330a2c9640](https://linux-hardware.org/?probe=330a2c9640) | Sep 20, 2023 |
| Biostar       | B550GTQ                     | [5478c7bc91](https://linux-hardware.org/?probe=5478c7bc91) | Sep 19, 2023 |
| Pegatron      | 2AB5                        | [6f4fafb23f](https://linux-hardware.org/?probe=6f4fafb23f) | Sep 19, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [f40bb3790e](https://linux-hardware.org/?probe=f40bb3790e) | Sep 18, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [0a5f29963e](https://linux-hardware.org/?probe=0a5f29963e) | Sep 18, 2023 |
| Gigabyte      | B85M-D3H                    | [7b51f6f455](https://linux-hardware.org/?probe=7b51f6f455) | Sep 18, 2023 |
| ASUSTek       | A88XM-PLUS                  | [ab79a26993](https://linux-hardware.org/?probe=ab79a26993) | Sep 18, 2023 |
| ASUSTek       | PRIME A320M-K               | [9c94944d56](https://linux-hardware.org/?probe=9c94944d56) | Sep 18, 2023 |
| ASUSTek       | P5GC-MX/1333                | [232bd09926](https://linux-hardware.org/?probe=232bd09926) | Sep 17, 2023 |
| MSI           | B450M MORTAR MAX            | [beaa4e5554](https://linux-hardware.org/?probe=beaa4e5554) | Sep 17, 2023 |
| Dell          | 0KWVT8 A03                  | [cd0090bea7](https://linux-hardware.org/?probe=cd0090bea7) | Sep 16, 2023 |
| Intel         | DX79SI AAG28808-602         | [2ccc7fc308](https://linux-hardware.org/?probe=2ccc7fc308) | Sep 16, 2023 |
| ASRock        | 960GC-GS FX                 | [513b6982f2](https://linux-hardware.org/?probe=513b6982f2) | Sep 16, 2023 |
| ASUSTek       | PRIME A320M-K               | [bef465f035](https://linux-hardware.org/?probe=bef465f035) | Sep 16, 2023 |
| Intel         | DH61CR AAG14064-204         | [e28e555058](https://linux-hardware.org/?probe=e28e555058) | Sep 16, 2023 |
| Lenovo        | ThinkCentre M58 7360BB6     | [cb32849dcc](https://linux-hardware.org/?probe=cb32849dcc) | Sep 16, 2023 |
| HP            | 339A                        | [5808e19d94](https://linux-hardware.org/?probe=5808e19d94) | Sep 15, 2023 |
| Gigabyte      | P35-DS3                     | [7cf209e4c1](https://linux-hardware.org/?probe=7cf209e4c1) | Sep 15, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [dd369f3c60](https://linux-hardware.org/?probe=dd369f3c60) | Sep 15, 2023 |
| Dell          | 073MMW A03                  | [b0fc15849b](https://linux-hardware.org/?probe=b0fc15849b) | Sep 15, 2023 |
| Gigabyte      | B450 AORUS M                | [9b3fc9218b](https://linux-hardware.org/?probe=9b3fc9218b) | Sep 14, 2023 |
| Intel         | H81                         | [34f1a336e3](https://linux-hardware.org/?probe=34f1a336e3) | Sep 14, 2023 |
| Gigabyte      | Z97X-SOC-CF                 | [9c86fc8235](https://linux-hardware.org/?probe=9c86fc8235) | Sep 14, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [33b3749fc5](https://linux-hardware.org/?probe=33b3749fc5) | Sep 14, 2023 |
| ASUSTek       | NAGAMI2                     | [c0e4ce344f](https://linux-hardware.org/?probe=c0e4ce344f) | Sep 14, 2023 |
| MSI           | B85M-E45                    | [d454b67226](https://linux-hardware.org/?probe=d454b67226) | Sep 13, 2023 |
| Packard Be... | MCP73                       | [b47efcac04](https://linux-hardware.org/?probe=b47efcac04) | Sep 13, 2023 |
| HP            | 339A                        | [1b8a467d98](https://linux-hardware.org/?probe=1b8a467d98) | Sep 13, 2023 |
| ASUSTek       | PRIME B550M-K               | [3b15d88a26](https://linux-hardware.org/?probe=3b15d88a26) | Sep 13, 2023 |
| MSI           | A88XM GAMING                | [0b0a88f781](https://linux-hardware.org/?probe=0b0a88f781) | Sep 13, 2023 |
| Pegatron      | 2ACF                        | [2b7e16f244](https://linux-hardware.org/?probe=2b7e16f244) | Sep 12, 2023 |
| MSI           | Z170A GAMING M9 ACK         | [49cc8ea6d2](https://linux-hardware.org/?probe=49cc8ea6d2) | Sep 12, 2023 |
| MSI           | B450M PRO-VDH               | [c06182cc86](https://linux-hardware.org/?probe=c06182cc86) | Sep 12, 2023 |
| Intel         | H61                         | [fec08a2214](https://linux-hardware.org/?probe=fec08a2214) | Sep 12, 2023 |
| Dell          | 0G254H A00                  | [b41d69b7e2](https://linux-hardware.org/?probe=b41d69b7e2) | Sep 12, 2023 |
| HP            | 82A1                        | [8a68160c22](https://linux-hardware.org/?probe=8a68160c22) | Sep 12, 2023 |
| Dell          | 0G3HR7 A00                  | [ae2dfec1af](https://linux-hardware.org/?probe=ae2dfec1af) | Sep 11, 2023 |
| Unknown       | Unknown                     | [7c32a84014](https://linux-hardware.org/?probe=7c32a84014) | Sep 11, 2023 |
| Intel         | JSL MRD                     | [b360f71c3d](https://linux-hardware.org/?probe=b360f71c3d) | Sep 11, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [9c4e42b171](https://linux-hardware.org/?probe=9c4e42b171) | Sep 11, 2023 |
| HP            | 304Ah                       | [fe71b825fd](https://linux-hardware.org/?probe=fe71b825fd) | Sep 11, 2023 |
| Intel         | H81 V2.3                    | [0673e1f5ed](https://linux-hardware.org/?probe=0673e1f5ed) | Sep 11, 2023 |
| Dell          | 088DT1 A00                  | [08eff7732c](https://linux-hardware.org/?probe=08eff7732c) | Sep 11, 2023 |
| Philco        | DTC-A55                     | [30cdd25bb0](https://linux-hardware.org/?probe=30cdd25bb0) | Sep 11, 2023 |
| ASUSTek       | PRIME H410M-R               | [962fd46c5c](https://linux-hardware.org/?probe=962fd46c5c) | Sep 11, 2023 |
| MSI           | PRO Z690-A                  | [2c892b26d1](https://linux-hardware.org/?probe=2c892b26d1) | Sep 11, 2023 |
| Gigabyte      | H110M-S2PT-CF               | [83ff674ae7](https://linux-hardware.org/?probe=83ff674ae7) | Sep 10, 2023 |
| Daten Tecn... | DA75PRO                     | [343cbab6e9](https://linux-hardware.org/?probe=343cbab6e9) | Sep 10, 2023 |
| ASRock        | A300M-STX                   | [923e3060e8](https://linux-hardware.org/?probe=923e3060e8) | Sep 10, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [91b6565880](https://linux-hardware.org/?probe=91b6565880) | Sep 09, 2023 |
| HP            | 8266                        | [fed6cc89fe](https://linux-hardware.org/?probe=fed6cc89fe) | Sep 09, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [8723b09478](https://linux-hardware.org/?probe=8723b09478) | Sep 09, 2023 |
| ASUSTek       | P10S-C Series               | [67829cd702](https://linux-hardware.org/?probe=67829cd702) | Sep 09, 2023 |
| Lenovo        | Annapurna CRB NOK           | [dc4bc20437](https://linux-hardware.org/?probe=dc4bc20437) | Sep 09, 2023 |
| Dell          | 0YJPT1 A00                  | [b16e6f8c25](https://linux-hardware.org/?probe=b16e6f8c25) | Sep 08, 2023 |
| MSI           | H61MA-E35                   | [e64c5d24b0](https://linux-hardware.org/?probe=e64c5d24b0) | Sep 08, 2023 |
| Dell          | 0J37VM A01                  | [cfd16871a7](https://linux-hardware.org/?probe=cfd16871a7) | Sep 08, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [c06ee9858a](https://linux-hardware.org/?probe=c06ee9858a) | Sep 08, 2023 |
| Intel         | H81                         | [52fa5b7a15](https://linux-hardware.org/?probe=52fa5b7a15) | Sep 08, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [7a0e6bd16c](https://linux-hardware.org/?probe=7a0e6bd16c) | Sep 07, 2023 |
| Medion        | H110H4-CM2                  | [184f133a7d](https://linux-hardware.org/?probe=184f133a7d) | Sep 07, 2023 |
| ASRock        | H310CM-HDV                  | [7aa11cd98f](https://linux-hardware.org/?probe=7aa11cd98f) | Sep 07, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [7bdd695dc3](https://linux-hardware.org/?probe=7bdd695dc3) | Sep 07, 2023 |
| Gigabyte      | H610M S2 V2 DDR4            | [7323821425](https://linux-hardware.org/?probe=7323821425) | Sep 07, 2023 |
| Gigabyte      | Z87X-UD3H-CF                | [43f205483a](https://linux-hardware.org/?probe=43f205483a) | Sep 07, 2023 |
| ASUSTek       | ROG STRIX B560-E GAMING ... | [498958a11d](https://linux-hardware.org/?probe=498958a11d) | Sep 07, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [96d3b5db5c](https://linux-hardware.org/?probe=96d3b5db5c) | Sep 07, 2023 |
| ASUSTek       | PRIME Z390M-PLUS            | [f98e7f20ca](https://linux-hardware.org/?probe=f98e7f20ca) | Sep 06, 2023 |
| MSI           | PRO B650-P WIFI             | [507d1bd39c](https://linux-hardware.org/?probe=507d1bd39c) | Sep 06, 2023 |
| Gigabyte      | B75M-D3H                    | [2285c5c493](https://linux-hardware.org/?probe=2285c5c493) | Sep 06, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | [a738df6114](https://linux-hardware.org/?probe=a738df6114) | Sep 06, 2023 |
| Intel         | DQ67SW AAG12527-310         | [774ca51623](https://linux-hardware.org/?probe=774ca51623) | Sep 06, 2023 |
| Gigabyte      | A320M-S2H-CF                | [03e260aff4](https://linux-hardware.org/?probe=03e260aff4) | Sep 06, 2023 |
| ASRock        | H77 Pro4/MVP                | [9e650e7107](https://linux-hardware.org/?probe=9e650e7107) | Sep 06, 2023 |
| Lenovo        | IdeaCentre K330B            | [a53977eb83](https://linux-hardware.org/?probe=a53977eb83) | Sep 06, 2023 |
| Dell          | 0PC5F7 A00                  | [9ffb575d81](https://linux-hardware.org/?probe=9ffb575d81) | Sep 06, 2023 |
| Shenzhen M... | F7BFD                       | [3f1c2a5cfa](https://linux-hardware.org/?probe=3f1c2a5cfa) | Sep 06, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [c43f7a6e53](https://linux-hardware.org/?probe=c43f7a6e53) | Sep 06, 2023 |
| Lenovo        | SDK0E50510 WIN              | [4e04252ac1](https://linux-hardware.org/?probe=4e04252ac1) | Sep 06, 2023 |
| Dell          | 0CU409                      | [f5ae8200cf](https://linux-hardware.org/?probe=f5ae8200cf) | Sep 06, 2023 |
| ASUSTek       | PRIME B450M-A II            | [07f51e668b](https://linux-hardware.org/?probe=07f51e668b) | Sep 06, 2023 |
| ASRock        | B550M Pro4                  | [afba6fc1eb](https://linux-hardware.org/?probe=afba6fc1eb) | Sep 06, 2023 |
| HP            | 0B54h D                     | [978ff127e9](https://linux-hardware.org/?probe=978ff127e9) | Sep 05, 2023 |
| MSI           | H270 GAMING M3              | [1c93682de6](https://linux-hardware.org/?probe=1c93682de6) | Sep 05, 2023 |
| ASRock        | 970 Pro3 R2.0               | [01ede034b7](https://linux-hardware.org/?probe=01ede034b7) | Sep 05, 2023 |
| Intel         | H61                         | [d749d1595f](https://linux-hardware.org/?probe=d749d1595f) | Sep 05, 2023 |
| Dell          | 0T1D10 A01                  | [97ac9f9de8](https://linux-hardware.org/?probe=97ac9f9de8) | Sep 05, 2023 |
| ASRock        | H470M-STX                   | [97e43e20d7](https://linux-hardware.org/?probe=97e43e20d7) | Sep 05, 2023 |
| HP            | 0B4Ch D                     | [25b4eff820](https://linux-hardware.org/?probe=25b4eff820) | Sep 05, 2023 |
| ASRock        | E35LM1                      | [663d9ac1e1](https://linux-hardware.org/?probe=663d9ac1e1) | Sep 04, 2023 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | [59b9a21678](https://linux-hardware.org/?probe=59b9a21678) | Sep 04, 2023 |
| ASRock        | X570M Pro4                  | [46627e6392](https://linux-hardware.org/?probe=46627e6392) | Sep 04, 2023 |
| ASUSTek       | P5P43TD/USB3                | [619032e1d0](https://linux-hardware.org/?probe=619032e1d0) | Sep 04, 2023 |
| Dell          | 0J8G6F A03                  | [490dd7a710](https://linux-hardware.org/?probe=490dd7a710) | Sep 04, 2023 |
| ASRock        | B460M-HDV                   | [2380eeae30](https://linux-hardware.org/?probe=2380eeae30) | Sep 04, 2023 |
| ASRock        | N68-S3 FX                   | [2b503dd2b6](https://linux-hardware.org/?probe=2b503dd2b6) | Sep 04, 2023 |
| Gigabyte      | H310M S2H x.x               | [7c39e7227e](https://linux-hardware.org/?probe=7c39e7227e) | Sep 04, 2023 |
| Lenovo        | ThinkCentre A58 77057FG     | [b96c23b77b](https://linux-hardware.org/?probe=b96c23b77b) | Sep 04, 2023 |
| Intel         | DG41RQ AAE54511-203         | [46aeab1365](https://linux-hardware.org/?probe=46aeab1365) | Sep 04, 2023 |
| OEM           | Intel H81                   | [649a092684](https://linux-hardware.org/?probe=649a092684) | Sep 04, 2023 |
| ASRock        | 960GM-VGS3 FX               | [c3059a2ebc](https://linux-hardware.org/?probe=c3059a2ebc) | Sep 04, 2023 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [2ba34b459a](https://linux-hardware.org/?probe=2ba34b459a) | Sep 04, 2023 |
| ASRock        | H510M-HDV R2.0              | [27684bd06d](https://linux-hardware.org/?probe=27684bd06d) | Sep 04, 2023 |
| ASUSTek       | PRIME B250M-A               | [02160fded0](https://linux-hardware.org/?probe=02160fded0) | Sep 04, 2023 |
| Gigabyte      | H87-D3H-CF                  | [9918661e50](https://linux-hardware.org/?probe=9918661e50) | Sep 04, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [08a80ee482](https://linux-hardware.org/?probe=08a80ee482) | Sep 04, 2023 |
| Lenovo        | SHARKBAY NOK                | [1cc4b106a4](https://linux-hardware.org/?probe=1cc4b106a4) | Sep 04, 2023 |
| Gigabyte      | H510M H                     | [f235f2e7ef](https://linux-hardware.org/?probe=f235f2e7ef) | Sep 04, 2023 |
| Gigabyte      | H510M S2H                   | [82f3e710d9](https://linux-hardware.org/?probe=82f3e710d9) | Sep 04, 2023 |
| Gigabyte      | A320M-H-CF                  | [8d171f78bf](https://linux-hardware.org/?probe=8d171f78bf) | Sep 04, 2023 |
| MSI           | B360M MORTAR ILYA MUROME... | [0899e4058a](https://linux-hardware.org/?probe=0899e4058a) | Sep 04, 2023 |
| ASUSTek       | Maximus VIII RANGER         | [0faa734044](https://linux-hardware.org/?probe=0faa734044) | Sep 04, 2023 |
| Dell          | 0D441T A03                  | [3ba5173eb2](https://linux-hardware.org/?probe=3ba5173eb2) | Sep 03, 2023 |
| ASUSTek       | P5E-VM SE                   | [6ce264a945](https://linux-hardware.org/?probe=6ce264a945) | Sep 03, 2023 |
| Gigabyte      | X79-UD3                     | [58ff81abf2](https://linux-hardware.org/?probe=58ff81abf2) | Sep 03, 2023 |
| Intel         | H61                         | [209644dbc2](https://linux-hardware.org/?probe=209644dbc2) | Sep 03, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | [70172e3461](https://linux-hardware.org/?probe=70172e3461) | Sep 03, 2023 |
| Gigabyte      | G41M-Combo                  | [26c9b8cc2c](https://linux-hardware.org/?probe=26c9b8cc2c) | Sep 03, 2023 |
| ASUSTek       | M2N-MX SE Plus              | [5656c8fd0b](https://linux-hardware.org/?probe=5656c8fd0b) | Sep 03, 2023 |
| ASUSTek       | STRIKER II EXTREME          | [eafb53342a](https://linux-hardware.org/?probe=eafb53342a) | Sep 03, 2023 |
| BESSTAR Te... | Cherry Trail CR             | [3ad034200f](https://linux-hardware.org/?probe=3ad034200f) | Sep 03, 2023 |
| ASUSTek       | PRIME B365M-A               | [b44e37eec5](https://linux-hardware.org/?probe=b44e37eec5) | Sep 03, 2023 |
| Gigabyte      | B450M DS3H V2               | [e0b3a3a55b](https://linux-hardware.org/?probe=e0b3a3a55b) | Sep 03, 2023 |
| ASRock        | A320D4-P1                   | [244c92966f](https://linux-hardware.org/?probe=244c92966f) | Sep 03, 2023 |
| NEC Comput... | MS-7451MA                   | [963dde730a](https://linux-hardware.org/?probe=963dde730a) | Sep 03, 2023 |
| HP            | 828A                        | [13126d5ce1](https://linux-hardware.org/?probe=13126d5ce1) | Sep 03, 2023 |
| ASUSTek       | M5A78L-M LX V2              | [92b5ca6639](https://linux-hardware.org/?probe=92b5ca6639) | Sep 03, 2023 |
| ASUSTek       | PRIME X470-PRO              | [976846f5c4](https://linux-hardware.org/?probe=976846f5c4) | Sep 03, 2023 |
| Pegatron      | IPMSB-GS                    | [35b8f645a7](https://linux-hardware.org/?probe=35b8f645a7) | Sep 03, 2023 |
| BESSTAR Te... | UM350                       | [9e80502e5d](https://linux-hardware.org/?probe=9e80502e5d) | Sep 03, 2023 |
| MSI           | Z390-A PRO                  | [16b96480a2](https://linux-hardware.org/?probe=16b96480a2) | Sep 03, 2023 |
| ASRock        | B450 Gaming K4              | [96dbf56986](https://linux-hardware.org/?probe=96dbf56986) | Sep 03, 2023 |
| Intel         | H81                         | [98f445e831](https://linux-hardware.org/?probe=98f445e831) | Sep 03, 2023 |
| ASUSTek       | M2N                         | [1df62dde56](https://linux-hardware.org/?probe=1df62dde56) | Sep 03, 2023 |
| Gigabyte      | F2A88X-UP4                  | [37bfab5442](https://linux-hardware.org/?probe=37bfab5442) | Sep 02, 2023 |
| Intel         | DQ77KB AAG40294-401         | [656df7cddd](https://linux-hardware.org/?probe=656df7cddd) | Sep 02, 2023 |
| HP            | 3646h                       | [cd226fee15](https://linux-hardware.org/?probe=cd226fee15) | Sep 02, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [4fa68712c5](https://linux-hardware.org/?probe=4fa68712c5) | Sep 02, 2023 |
| MSI           | B450M MORTAR MAX            | [b161a13302](https://linux-hardware.org/?probe=b161a13302) | Sep 02, 2023 |
| HP            | 1497                        | [43c8de838b](https://linux-hardware.org/?probe=43c8de838b) | Sep 02, 2023 |
| ASRock        | N68-S3 UCC                  | [53cd38e0c5](https://linux-hardware.org/?probe=53cd38e0c5) | Sep 02, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | [d25c5d75c1](https://linux-hardware.org/?probe=d25c5d75c1) | Sep 02, 2023 |
| ASRock        | FM2A55M-VG3+                | [df01a7432c](https://linux-hardware.org/?probe=df01a7432c) | Sep 02, 2023 |
| Dell          | 04YP6J A02                  | [02c6b100f0](https://linux-hardware.org/?probe=02c6b100f0) | Sep 02, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [5590e2e8d6](https://linux-hardware.org/?probe=5590e2e8d6) | Sep 02, 2023 |
| MSI           | H81M-P33                    | [266b226035](https://linux-hardware.org/?probe=266b226035) | Sep 02, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [c03e79d6e1](https://linux-hardware.org/?probe=c03e79d6e1) | Sep 02, 2023 |
| ASRock        | A620M-HDV/M.2+              | [674da4ba95](https://linux-hardware.org/?probe=674da4ba95) | Sep 02, 2023 |
| Acer          | Aspire TC-875 V:1.0         | [a25ba0bd0c](https://linux-hardware.org/?probe=a25ba0bd0c) | Sep 02, 2023 |
| ASRock        | H570 Steel Legend           | [192d8ebfa3](https://linux-hardware.org/?probe=192d8ebfa3) | Sep 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [2a9211117f](https://linux-hardware.org/?probe=2a9211117f) | Sep 02, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [c972b65ed6](https://linux-hardware.org/?probe=c972b65ed6) | Sep 02, 2023 |
| Medion        | B460H6-EM                   | [ec8f0bbb13](https://linux-hardware.org/?probe=ec8f0bbb13) | Sep 02, 2023 |
| Foxconn       | 2ABF                        | [f3655da9eb](https://linux-hardware.org/?probe=f3655da9eb) | Sep 01, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | [ba40b3b859](https://linux-hardware.org/?probe=ba40b3b859) | Sep 01, 2023 |
| Intel         | DP67DE AAG10217-300         | [4d0db0b964](https://linux-hardware.org/?probe=4d0db0b964) | Sep 01, 2023 |
| MSI           | PRO Z690-P DDR4             | [6cd52cad83](https://linux-hardware.org/?probe=6cd52cad83) | Sep 01, 2023 |
| Acer          | Veriton M4610G              | [a5e1bdfce5](https://linux-hardware.org/?probe=a5e1bdfce5) | Sep 01, 2023 |
| Dell          | 00V62H A01                  | [5b976d122b](https://linux-hardware.org/?probe=5b976d122b) | Sep 01, 2023 |
| HP            | 3032h                       | [7dfc9fa7a0](https://linux-hardware.org/?probe=7dfc9fa7a0) | Sep 01, 2023 |
| HP            | 1632                        | [a36b07aeda](https://linux-hardware.org/?probe=a36b07aeda) | Sep 01, 2023 |
| Gigabyte      | GA-MA770T-UD3               | [d5d9154715](https://linux-hardware.org/?probe=d5d9154715) | Sep 01, 2023 |
| Gigabyte      | B75M-D3H                    | [9e7e8b4fbd](https://linux-hardware.org/?probe=9e7e8b4fbd) | Sep 01, 2023 |
| AZW           | U59                         | [4cca42eeb3](https://linux-hardware.org/?probe=4cca42eeb3) | Sep 01, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [73147203ca](https://linux-hardware.org/?probe=73147203ca) | Sep 01, 2023 |
| ASUSTek       | PRIME B450M-K               | [8cc90dd6b0](https://linux-hardware.org/?probe=8cc90dd6b0) | Sep 01, 2023 |
| ASUSTek       | H81M2                       | [55dd352412](https://linux-hardware.org/?probe=55dd352412) | Sep 01, 2023 |
| Gigabyte      | M5NM1AI-GB                  | [2b2efe00dd](https://linux-hardware.org/?probe=2b2efe00dd) | Sep 01, 2023 |
| ASUSTek       | P9X79                       | [905ee212e5](https://linux-hardware.org/?probe=905ee212e5) | Sep 01, 2023 |
| Gigabyte      | B85M-D3H                    | [4660dc9f99](https://linux-hardware.org/?probe=4660dc9f99) | Sep 01, 2023 |
| AOpen         | i65HMx-D R1.04AL            | [aef1de4c53](https://linux-hardware.org/?probe=aef1de4c53) | Sep 01, 2023 |
| Medion        | B250H4-EM                   | [c2e1f2eb0b](https://linux-hardware.org/?probe=c2e1f2eb0b) | Sep 01, 2023 |
| Intel         | SHARKBAY                    | [cc7fea9c3a](https://linux-hardware.org/?probe=cc7fea9c3a) | Sep 01, 2023 |
| ASUSTek       | H110M-A/M.2                 | [6010a74736](https://linux-hardware.org/?probe=6010a74736) | Sep 01, 2023 |
| ASUSTek       | N3050T                      | [fa4b0cbf08](https://linux-hardware.org/?probe=fa4b0cbf08) | Sep 01, 2023 |
| Foxconn       | G31MXP FAB:1.1              | [4fc2089efc](https://linux-hardware.org/?probe=4fc2089efc) | Sep 01, 2023 |
| ASRock        | A320M-HD                    | [7fd4c8ad9c](https://linux-hardware.org/?probe=7fd4c8ad9c) | Sep 01, 2023 |
| MSI           | MS-7390                     | [7115ad031a](https://linux-hardware.org/?probe=7115ad031a) | Sep 01, 2023 |
| Fujitsu       | D3410-B2 S26361-D3410-B2    | [924293e07f](https://linux-hardware.org/?probe=924293e07f) | Sep 01, 2023 |
| MSI           | X99A WORKSTATION            | [46d1af7083](https://linux-hardware.org/?probe=46d1af7083) | Sep 01, 2023 |
| HP            | 1632                        | [13de11f1ff](https://linux-hardware.org/?probe=13de11f1ff) | Sep 01, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [d728ff01da](https://linux-hardware.org/?probe=d728ff01da) | Sep 01, 2023 |
| ASUSTek       | WS X299 SAGE                | [a01568da7d](https://linux-hardware.org/?probe=a01568da7d) | Aug 31, 2023 |
| HP            | 3397                        | [b9dabe8514](https://linux-hardware.org/?probe=b9dabe8514) | Aug 31, 2023 |
| Positivo      | ONE500                      | [1e84a5bf44](https://linux-hardware.org/?probe=1e84a5bf44) | Aug 31, 2023 |
| PCWare        | IPX1800E1                   | [bfe03f751b](https://linux-hardware.org/?probe=bfe03f751b) | Aug 31, 2023 |
| Shenzhen M... | F6BFC                       | [c5fc2337ec](https://linux-hardware.org/?probe=c5fc2337ec) | Aug 31, 2023 |
| Foxconn       | G41S/G41S-K                 | [8ad8098315](https://linux-hardware.org/?probe=8ad8098315) | Aug 31, 2023 |
| Intel         | H61                         | [d0bd2f4cfa](https://linux-hardware.org/?probe=d0bd2f4cfa) | Aug 31, 2023 |
| Intel         | B75                         | [d8367a0977](https://linux-hardware.org/?probe=d8367a0977) | Aug 31, 2023 |
| MSI           | H61M-P20/W8                 | [c35045d386](https://linux-hardware.org/?probe=c35045d386) | Aug 31, 2023 |
| HP            | 339A                        | [1ac5cd4af8](https://linux-hardware.org/?probe=1ac5cd4af8) | Aug 31, 2023 |
| HP            | 8768 A                      | [99787646c5](https://linux-hardware.org/?probe=99787646c5) | Aug 31, 2023 |
| HP            | 2215                        | [3b3b45d0ce](https://linux-hardware.org/?probe=3b3b45d0ce) | Aug 31, 2023 |
| Intel         | HM570                       | [d7c97890f9](https://linux-hardware.org/?probe=d7c97890f9) | Aug 31, 2023 |
| Red Hat       | RHEL RHEL-9.2.0 PC          | [ee06e81f13](https://linux-hardware.org/?probe=ee06e81f13) | Aug 31, 2023 |
| Intel         | H55                         | [955198ab64](https://linux-hardware.org/?probe=955198ab64) | Aug 31, 2023 |
| Dell          | 0GDG8Y A00                  | [b9c66b93e7](https://linux-hardware.org/?probe=b9c66b93e7) | Aug 31, 2023 |
| Gigabyte      | GA-73PVM-S2H                | [4abb2ab82b](https://linux-hardware.org/?probe=4abb2ab82b) | Aug 31, 2023 |
| Acer          | Veriton N4660G              | [25339d5009](https://linux-hardware.org/?probe=25339d5009) | Aug 31, 2023 |
| MSI           | X99A RAIDER                 | [5b79d93d0a](https://linux-hardware.org/?probe=5b79d93d0a) | Aug 31, 2023 |
| ASUSTek       | PRIME B550M-A               | [19cb61cbf6](https://linux-hardware.org/?probe=19cb61cbf6) | Aug 31, 2023 |
| ASUSTek       | PRIME B550M-A               | [06860111ba](https://linux-hardware.org/?probe=06860111ba) | Aug 31, 2023 |
| MSI           | A88X-G41 PC Mate            | [13724b9cc2](https://linux-hardware.org/?probe=13724b9cc2) | Aug 31, 2023 |
| MSI           | A320M PRO-E                 | [92c4032614](https://linux-hardware.org/?probe=92c4032614) | Aug 31, 2023 |
| Lenovo        | SDK0J40700 WIN              | [12785fd41a](https://linux-hardware.org/?probe=12785fd41a) | Aug 31, 2023 |
| HP            | 1587h                       | [fe659d3db6](https://linux-hardware.org/?probe=fe659d3db6) | Aug 31, 2023 |
| HP            | 806A                        | [638dfe4edc](https://linux-hardware.org/?probe=638dfe4edc) | Aug 31, 2023 |
| MSI           | A520M-A PRO                 | [d672293a11](https://linux-hardware.org/?probe=d672293a11) | Aug 31, 2023 |
| ASUSTek       | PRIME X570-P                | [f0f4af9185](https://linux-hardware.org/?probe=f0f4af9185) | Aug 31, 2023 |
| MSI           | Z370-A PRO                  | [56e3937602](https://linux-hardware.org/?probe=56e3937602) | Aug 31, 2023 |
| ViewSonic     | VPC14-WP                    | [a5476c92e7](https://linux-hardware.org/?probe=a5476c92e7) | Aug 31, 2023 |
| Fujitsu       | D2679-B1 S26361-D2679-Bx... | [81ae698cf8](https://linux-hardware.org/?probe=81ae698cf8) | Aug 31, 2023 |
| HP            | 8768 A                      | [3b19eaee36](https://linux-hardware.org/?probe=3b19eaee36) | Aug 31, 2023 |
| Gigabyte      | H110M-H-CF                  | [faf094d2ca](https://linux-hardware.org/?probe=faf094d2ca) | Aug 31, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | [dc63902a68](https://linux-hardware.org/?probe=dc63902a68) | Aug 31, 2023 |
| MSI           | 880G-E45                    | [f10edf60fd](https://linux-hardware.org/?probe=f10edf60fd) | Aug 31, 2023 |
| MSI           | 2A78h                       | [78b5a663f2](https://linux-hardware.org/?probe=78b5a663f2) | Aug 31, 2023 |
| Dell          | 0KRC95 A02                  | [9173d00240](https://linux-hardware.org/?probe=9173d00240) | Aug 31, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [1a3fdd076f](https://linux-hardware.org/?probe=1a3fdd076f) | Aug 31, 2023 |
| MSI           | Boston                      | [f43cd6df24](https://linux-hardware.org/?probe=f43cd6df24) | Aug 31, 2023 |
| ECS           | A780GM-A                    | [12787b1e38](https://linux-hardware.org/?probe=12787b1e38) | Aug 31, 2023 |
| Megaware      | MW-NM70HD-MI 06/11/2012 ... | [7b8812491c](https://linux-hardware.org/?probe=7b8812491c) | Aug 31, 2023 |
| ASUSTek       | P5G41T-M LX                 | [bdae370995](https://linux-hardware.org/?probe=bdae370995) | Aug 30, 2023 |
| ASUSTek       | P8Q77-M                     | [d9760de265](https://linux-hardware.org/?probe=d9760de265) | Aug 30, 2023 |
| ASUSTek       | P8Z68-V LX                  | [7de2ff1052](https://linux-hardware.org/?probe=7de2ff1052) | Aug 30, 2023 |
| MSI           | 970 GAMING                  | [f468606e38](https://linux-hardware.org/?probe=f468606e38) | Aug 30, 2023 |
| Dell          | OptiPlex 7050               | [a35a9d7d8a](https://linux-hardware.org/?probe=a35a9d7d8a) | Aug 30, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [79783b33ff](https://linux-hardware.org/?probe=79783b33ff) | Aug 30, 2023 |
| ASUSTek       | A8N-E                       | [84578c86e7](https://linux-hardware.org/?probe=84578c86e7) | Aug 30, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [42f87cb09b](https://linux-hardware.org/?probe=42f87cb09b) | Aug 30, 2023 |
| MSI           | H61MA-E35                   | [5eee145629](https://linux-hardware.org/?probe=5eee145629) | Aug 30, 2023 |
| Dell          | 0Y5DDC A00                  | [21ec7587ed](https://linux-hardware.org/?probe=21ec7587ed) | Aug 30, 2023 |
| ASRock        | H470M-STX                   | [8ba058add5](https://linux-hardware.org/?probe=8ba058add5) | Aug 30, 2023 |
| Gigabyte      | B450M H                     | [cd7bf0b2db](https://linux-hardware.org/?probe=cd7bf0b2db) | Aug 30, 2023 |
| Acer          | Aspire XC-330               | [2e1b103708](https://linux-hardware.org/?probe=2e1b103708) | Aug 30, 2023 |
| Intel         | DH55TC AAE70932-205         | [5e3be336db](https://linux-hardware.org/?probe=5e3be336db) | Aug 30, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [a65c8bb631](https://linux-hardware.org/?probe=a65c8bb631) | Aug 30, 2023 |
| Medion        | B460H6-EM                   | [fac263bf1a](https://linux-hardware.org/?probe=fac263bf1a) | Aug 30, 2023 |
| ASUSTek       | P6T                         | [69879aca23](https://linux-hardware.org/?probe=69879aca23) | Aug 30, 2023 |
| HP            | 0B4Ch D                     | [362ee070d7](https://linux-hardware.org/?probe=362ee070d7) | Aug 30, 2023 |
| ASRock        | M3A UCC                     | [b46f15b2d2](https://linux-hardware.org/?probe=b46f15b2d2) | Aug 30, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [a2f37c4111](https://linux-hardware.org/?probe=a2f37c4111) | Aug 30, 2023 |
| ASUSTek       | A88XM-E/USB                 | [376615315b](https://linux-hardware.org/?probe=376615315b) | Aug 30, 2023 |
| ASUSTek       | P5Q SE PLUS                 | [311596a316](https://linux-hardware.org/?probe=311596a316) | Aug 30, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [f040a85f2f](https://linux-hardware.org/?probe=f040a85f2f) | Aug 30, 2023 |
| ASUSTek       | P8H67-V                     | [24b196c99a](https://linux-hardware.org/?probe=24b196c99a) | Aug 30, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [9ed00c6987](https://linux-hardware.org/?probe=9ed00c6987) | Aug 30, 2023 |
| Foxconn       | H55MXV Series               | [af9d0ad662](https://linux-hardware.org/?probe=af9d0ad662) | Aug 30, 2023 |
| HP            | 876C SMVB                   | [25176eb482](https://linux-hardware.org/?probe=25176eb482) | Aug 30, 2023 |
| Gigabyte      | F2A88XM-HD3                 | [43cb5c7282](https://linux-hardware.org/?probe=43cb5c7282) | Aug 30, 2023 |
| HP            | 876C SMVB                   | [246cb7a1ca](https://linux-hardware.org/?probe=246cb7a1ca) | Aug 30, 2023 |
| ASRock        | H170M-ITX/ac                | [7921e28c6b](https://linux-hardware.org/?probe=7921e28c6b) | Aug 30, 2023 |
| OEM           | Intel H81                   | [7d179cb8e9](https://linux-hardware.org/?probe=7d179cb8e9) | Aug 30, 2023 |
| Dell          | 0DR845                      | [2b4ff07956](https://linux-hardware.org/?probe=2b4ff07956) | Aug 30, 2023 |
| ASRock        | 970 Pro3 R2.0               | [f59364572a](https://linux-hardware.org/?probe=f59364572a) | Aug 30, 2023 |
| Itautec       | ST 4254 ST-4254 Padrao 0... | [fbbbe0087a](https://linux-hardware.org/?probe=fbbbe0087a) | Aug 30, 2023 |
| Apple         | Mac-F221BEC8                | [13b77d8273](https://linux-hardware.org/?probe=13b77d8273) | Aug 30, 2023 |
| Acer          | Aspire TC-895 V:1.0         | [20bd10b5f4](https://linux-hardware.org/?probe=20bd10b5f4) | Aug 30, 2023 |
| Foxconn       | D180S/D190S/D290S Series... | [5f6030cb69](https://linux-hardware.org/?probe=5f6030cb69) | Aug 30, 2023 |
| Foxconn       | Lucknow                     | [eece5a84ae](https://linux-hardware.org/?probe=eece5a84ae) | Aug 30, 2023 |
| MSI           | A320M PRO-VD PLUS           | [1782829fec](https://linux-hardware.org/?probe=1782829fec) | Aug 29, 2023 |
| MSI           | H61M-E22/W8                 | [2439d2ed95](https://linux-hardware.org/?probe=2439d2ed95) | Aug 29, 2023 |
| HP            | 1589                        | [047e0158e8](https://linux-hardware.org/?probe=047e0158e8) | Aug 29, 2023 |
| ASUSTek       | PRIME Z270-P                | [c4bec90c4e](https://linux-hardware.org/?probe=c4bec90c4e) | Aug 29, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [567a59e1bc](https://linux-hardware.org/?probe=567a59e1bc) | Aug 29, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva_23.08/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Desktops | Percent |
|------------------------------|----------|---------|
| 6.4.11-desktop-1omv2390      | 863      | 78.53%  |
| 6.4.8-desktop-2omv2390       | 219      | 19.93%  |
| 6.5.0-desktop-1omv2390       | 8        | 0.73%   |
| 6.10.1-desktop-1omv2490      | 3        | 0.27%   |
| 6.9.3-desktop-1omv2490       | 1        | 0.09%   |
| 6.6.2-desktop-1omv2390       | 1        | 0.09%   |
| 6.6.0-desktop-1omv2390       | 1        | 0.09%   |
| 6.5.1-desktop-1omv2390       | 1        | 0.09%   |
| 6.5.0-desktop-0.rc7.1omv2390 | 1        | 0.09%   |
| 6.3.5-desktop-3omv2390       | 1        | 0.09%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.4.11  | 863      | 78.53%  |
| 6.4.8   | 219      | 19.93%  |
| 6.5.0   | 9        | 0.82%   |
| 6.10.1  | 3        | 0.27%   |
| 6.9.3   | 1        | 0.09%   |
| 6.6.2   | 1        | 0.09%   |
| 6.6.0   | 1        | 0.09%   |
| 6.5.1   | 1        | 0.09%   |
| 6.3.5   | 1        | 0.09%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.4     | 1080     | 98.45%  |
| 6.5     | 10       | 0.91%   |
| 6.10    | 3        | 0.27%   |
| 6.6     | 2        | 0.18%   |
| 6.9     | 1        | 0.09%   |
| 6.3     | 1        | 0.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 1097     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| KDE5    | 950      | 86.44%  |
| GNOME   | 84       | 7.64%   |
| LXQt    | 59       | 5.37%   |
| Budgie  | 3        | 0.27%   |
| Unknown | 3        | 0.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 1059     | 96.36%  |
| X11     | 38       | 3.46%   |
| Unknown | 2        | 0.18%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SDDM | 1014     | 92.35%  |
| GDM  | 84       | 7.65%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 516      | 46.91%  |
| de_DE | 75       | 6.82%   |
| pt_BR | 71       | 6.45%   |
| ru_RU | 70       | 6.36%   |
| fr_FR | 56       | 5.09%   |
| en_GB | 45       | 4.09%   |
| pl_PL | 39       | 3.55%   |
| it_IT | 34       | 3.09%   |
| es_ES | 34       | 3.09%   |
| es_AR | 13       | 1.18%   |
| es_MX | 12       | 1.09%   |
| fr_BE | 11       | 1%      |
| en_CA | 11       | 1%      |
| cs_CZ | 11       | 1%      |
| hu_HU | 10       | 0.91%   |
| pt_PT | 8        | 0.73%   |
| es_VE | 8        | 0.73%   |
| en_AU | 8        | 0.73%   |
| tr_TR | 6        | 0.55%   |
| es_CO | 6        | 0.55%   |
| nl_BE | 5        | 0.45%   |
| en_IN | 5        | 0.45%   |
| de_AT | 5        | 0.45%   |
| nl_NL | 4        | 0.36%   |
| ro_RO | 3        | 0.27%   |
| en_SG | 3        | 0.27%   |
| UTF-8 | 2        | 0.18%   |
| it_CH | 2        | 0.18%   |
| fr_CA | 2        | 0.18%   |
| es_CL | 2        | 0.18%   |
| en_ZA | 2        | 0.18%   |
| en_IE | 2        | 0.18%   |
| en_HK | 2        | 0.18%   |
| de_CH | 2        | 0.18%   |
| ar_DZ | 2        | 0.18%   |
| uk_UA | 1        | 0.09%   |
| ja_JP | 1        | 0.09%   |
| fr_CH | 1        | 0.09%   |
| es_UY | 1        | 0.09%   |
| es_PY | 1        | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 583      | 53.05%  |
| BIOS | 516      | 46.95%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Overlay  | 533      | 48.28%  |
| Ext4     | 506      | 45.83%  |
| Btrfs    | 36       | 3.26%   |
| Xfs      | 11       | 1%      |
| Reiserfs | 5        | 0.45%   |
| F2fs     | 5        | 0.45%   |
| Jfs      | 3        | 0.27%   |
| Ext3     | 3        | 0.27%   |
| Udf      | 1        | 0.09%   |
| Ext2     | 1        | 0.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 842      | 76.48%  |
| MBR  | 259      | 23.52%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 574      | 51.85%  |
| No        | 533      | 48.15%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 563      | 51.14%  |
| Yes       | 538      | 48.86%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 228      | 20.78%  |
| Gigabyte Technology                  | 170      | 15.5%   |
| Hewlett-Packard                      | 117      | 10.67%  |
| MSI                                  | 115      | 10.48%  |
| Dell                                 | 85       | 7.75%   |
| ASRock                               | 78       | 7.11%   |
| Intel                                | 62       | 5.65%   |
| Lenovo                               | 50       | 4.56%   |
| Fujitsu                              | 27       | 2.46%   |
| Acer                                 | 23       | 2.1%    |
| Foxconn                              | 15       | 1.37%   |
| Pegatron                             | 13       | 1.19%   |
| Biostar                              | 13       | 1.19%   |
| Unknown                              | 12       | 1.09%   |
| Positivo                             | 9        | 0.82%   |
| ECS                                  | 8        | 0.73%   |
| Shenzhen Meigao Electronic Equipment | 7        | 0.64%   |
| AZW                                  | 7        | 0.64%   |
| Medion                               | 5        | 0.46%   |
| OEM                                  | 4        | 0.36%   |
| Shuttle                              | 3        | 0.27%   |
| PCWare                               | 3        | 0.27%   |
| Red Hat                              | 2        | 0.18%   |
| Packard Bell                         | 2        | 0.18%   |
| Minix                                | 2        | 0.18%   |
| Megaware                             | 2        | 0.18%   |
| MACHINIST                            | 2        | 0.18%   |
| Itautec                              | 2        | 0.18%   |
| Huanan                               | 2        | 0.18%   |
| GEEKOM                               | 2        | 0.18%   |
| Casper                               | 2        | 0.18%   |
| BESSTAR Tech                         | 2        | 0.18%   |
| Apple                                | 2        | 0.18%   |
| AMD                                  | 2        | 0.18%   |
| ViewSonic                            | 1        | 0.09%   |
| TPV-INVENTA                          | 1        | 0.09%   |
| QIYIDA                               | 1        | 0.09%   |
| Philco                               | 1        | 0.09%   |
| PCBOX                                | 1        | 0.09%   |
| NEC Computers                        | 1        | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS All Series                            | 16       | 1.46%   |
| Unknown                                    | 14       | 1.28%   |
| Intel H61                                  | 12       | 1.09%   |
| Dell OptiPlex 7010                         | 9        | 0.82%   |
| HP Compaq Pro 6300 SFF                     | 8        | 0.73%   |
| Intel H81                                  | 7        | 0.64%   |
| MSI MS-7C51                                | 5        | 0.46%   |
| MSI MS-7817                                | 5        | 0.46%   |
| Intel X99                                  | 5        | 0.46%   |
| Gigabyte B75M-D3H                          | 5        | 0.46%   |
| Gigabyte A320M-S2H                         | 5        | 0.46%   |
| Dell OptiPlex 9020                         | 5        | 0.46%   |
| Dell OptiPlex 3010                         | 5        | 0.46%   |
| ASUS TUF Gaming B550-PLUS                  | 5        | 0.46%   |
| Positivo POS-PIG41BA                       | 4        | 0.36%   |
| MSI MS-7C91                                | 4        | 0.36%   |
| MSI MS-7721                                | 4        | 0.36%   |
| Intel B75                                  | 4        | 0.36%   |
| HP Z400 Workstation                        | 4        | 0.36%   |
| HP Compaq 6200 Pro SFF PC                  | 4        | 0.36%   |
| Gigabyte X299 AORUS Gaming                 | 4        | 0.36%   |
| Dell OptiPlex 9010                         | 4        | 0.36%   |
| Dell OptiPlex 790                          | 4        | 0.36%   |
| ASUS TUF Gaming X570-PLUS                  | 4        | 0.36%   |
| ASUS PRIME A320M-K                         | 4        | 0.36%   |
| Shenzhen Meigao Electronic Equipment UM690 | 3        | 0.27%   |
| MSI MS-7C56                                | 3        | 0.27%   |
| MSI MS-7C52                                | 3        | 0.27%   |
| MSI MS-7C37                                | 3        | 0.27%   |
| MSI MS-7B89                                | 3        | 0.27%   |
| MSI MS-7B86                                | 3        | 0.27%   |
| MSI MS-7996                                | 3        | 0.27%   |
| Intel Jasper Lake Client Platform          | 3        | 0.27%   |
| HP EliteDesk 800 G1 USDT                   | 3        | 0.27%   |
| HP EliteDesk 800 G1 SFF                    | 3        | 0.27%   |
| HP Desktop M01-F1xxx                       | 3        | 0.27%   |
| HP Compaq Elite 8300 SFF                   | 3        | 0.27%   |
| HP Compaq Elite 8300 CMT                   | 3        | 0.27%   |
| HP Compaq 8200 Elite SFF PC                | 3        | 0.27%   |
| HP Compaq 8000 Elite SFF PC                | 3        | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Dell OptiPlex        | 58       | 5.29%   |
| ASUS PRIME           | 52       | 4.74%   |
| HP Compaq            | 45       | 4.1%    |
| Lenovo ThinkCentre   | 35       | 3.19%   |
| Fujitsu ESPRIMO      | 20       | 1.82%   |
| ASUS TUF             | 20       | 1.82%   |
| ASUS ROG             | 18       | 1.64%   |
| HP EliteDesk         | 17       | 1.55%   |
| ASUS All             | 16       | 1.46%   |
| Unknown              | 14       | 1.28%   |
| Intel H61            | 13       | 1.19%   |
| Acer Aspire          | 12       | 1.09%   |
| HP ProDesk           | 10       | 0.91%   |
| Acer Veriton         | 10       | 0.91%   |
| Dell Inspiron        | 9        | 0.82%   |
| ASUS M5A78L-M        | 9        | 0.82%   |
| Intel H81            | 8        | 0.73%   |
| HP Slim              | 8        | 0.73%   |
| Gigabyte B550        | 7        | 0.64%   |
| Gigabyte B450M       | 7        | 0.64%   |
| Gigabyte B450        | 7        | 0.64%   |
| Lenovo IdeaCentre    | 6        | 0.55%   |
| Gigabyte A320M-S2H   | 6        | 0.55%   |
| Dell Vostro          | 6        | 0.55%   |
| MSI MS-7C51          | 5        | 0.46%   |
| MSI MS-7817          | 5        | 0.46%   |
| Intel X99            | 5        | 0.46%   |
| Gigabyte X570        | 5        | 0.46%   |
| Gigabyte H510M       | 5        | 0.46%   |
| Gigabyte B75M-D3H    | 5        | 0.46%   |
| ASUS P5GC-MX         | 5        | 0.46%   |
| ASUS P5G41T-M        | 5        | 0.46%   |
| ASRock B450          | 5        | 0.46%   |
| Positivo POS-PIG41BA | 4        | 0.36%   |
| MSI MS-7C91          | 4        | 0.36%   |
| MSI MS-7721          | 4        | 0.36%   |
| Intel DG41RQ         | 4        | 0.36%   |
| Intel B75            | 4        | 0.36%   |
| HP Z400              | 4        | 0.36%   |
| HP Pavilion          | 4        | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 122      | 11.12%  |
| 2013 | 96       | 8.75%   |
| 2020 | 80       | 7.29%   |
| 2014 | 80       | 7.29%   |
| 2010 | 73       | 6.65%   |
| 2018 | 70       | 6.38%   |
| 2017 | 70       | 6.38%   |
| 2011 | 68       | 6.2%    |
| 2021 | 65       | 5.93%   |
| 2019 | 60       | 5.47%   |
| 2009 | 55       | 5.01%   |
| 2022 | 51       | 4.65%   |
| 2016 | 51       | 4.65%   |
| 2023 | 36       | 3.28%   |
| 2015 | 35       | 3.19%   |
| 2008 | 34       | 3.1%    |
| 2007 | 28       | 2.55%   |
| 2006 | 13       | 1.19%   |
| 2024 | 5        | 0.46%   |
| 2005 | 3        | 0.27%   |
| 2004 | 2        | 0.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 1097     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 1097     | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1097     | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 251      | 22.84%  |
| 4.01-8.0    | 220      | 20.02%  |
| 8.01-16.0   | 216      | 19.65%  |
| 3.01-4.0    | 165      | 15.01%  |
| 32.01-64.0  | 133      | 12.1%   |
| 24.01-32.0  | 32       | 2.91%   |
| 64.01-256.0 | 31       | 2.82%   |
| 2.01-3.0    | 24       | 2.18%   |
| 1.01-2.0    | 23       | 2.09%   |
| 0.51-1.0    | 4        | 0.36%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 726      | 65.29%  |
| 2.01-3.0  | 230      | 20.68%  |
| 0.51-1.0  | 87       | 7.82%   |
| 3.01-4.0  | 40       | 3.6%    |
| 4.01-8.0  | 16       | 1.44%   |
| 0.01-0.5  | 12       | 1.08%   |
| 8.01-16.0 | 1        | 0.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 507      | 45.76%  |
| 2      | 286      | 25.81%  |
| 3      | 147      | 13.27%  |
| 4      | 85       | 7.67%   |
| 5      | 42       | 3.79%   |
| 6      | 18       | 1.62%   |
| 0      | 10       | 0.9%    |
| 7      | 5        | 0.45%   |
| 8      | 4        | 0.36%   |
| 10     | 2        | 0.18%   |
| 11     | 1        | 0.09%   |
| 9      | 1        | 0.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 557      | 50.77%  |
| No        | 540      | 49.23%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1084     | 98.81%  |
| No        | 13       | 1.19%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 684      | 62.3%   |
| Yes       | 414      | 37.7%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 810      | 73.64%  |
| Yes       | 290      | 26.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 140      | 12.76%  |
| Brazil       | 108      | 9.85%   |
| Germany      | 102      | 9.3%    |
| Russia       | 77       | 7.02%   |
| France       | 75       | 6.84%   |
| Poland       | 59       | 5.38%   |
| Italy        | 51       | 4.65%   |
| UK           | 41       | 3.74%   |
| Spain        | 40       | 3.65%   |
| Canada       | 23       | 2.1%    |
| Australia    | 20       | 1.82%   |
| Belgium      | 19       | 1.73%   |
| Netherlands  | 18       | 1.64%   |
| Mexico       | 18       | 1.64%   |
| Argentina    | 17       | 1.55%   |
| Hungary      | 14       | 1.28%   |
| Greece       | 13       | 1.19%   |
| Czechia      | 13       | 1.19%   |
| India        | 12       | 1.09%   |
| Japan        | 11       | 1%      |
| Colombia     | 11       | 1%      |
| Venezuela    | 10       | 0.91%   |
| Turkey       | 10       | 0.91%   |
| Bulgaria     | 10       | 0.91%   |
| Austria      | 10       | 0.91%   |
| Portugal     | 9        | 0.82%   |
| China        | 9        | 0.82%   |
| Slovakia     | 8        | 0.73%   |
| Ukraine      | 7        | 0.64%   |
| Thailand     | 7        | 0.64%   |
| Romania      | 7        | 0.64%   |
| Malaysia     | 7        | 0.64%   |
| Israel       | 6        | 0.55%   |
| Iran         | 6        | 0.55%   |
| Finland      | 6        | 0.55%   |
| Sweden       | 5        | 0.46%   |
| Serbia       | 5        | 0.46%   |
| Indonesia    | 5        | 0.46%   |
| South Africa | 4        | 0.36%   |
| Kazakhstan   | 4        | 0.36%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Berlin         | 13       | 1.18%   |
| Warsaw         | 11       | 1%      |
| Moscow         | 11       | 1%      |
| St Petersburg  | 9        | 0.82%   |
| Krakow         | 9        | 0.82%   |
| Sydney         | 8        | 0.73%   |
| Novosibirsk    | 7        | 0.64%   |
| Milan          | 7        | 0.64%   |
| Vienna         | 6        | 0.54%   |
| Rome           | 6        | 0.54%   |
| Tehran         | 5        | 0.45%   |
| Sao Paulo      | 5        | 0.45%   |
| Sao Goncalo    | 5        | 0.45%   |
| San Cristóbal | 5        | 0.45%   |
| Munich         | 5        | 0.45%   |
| Melbourne      | 5        | 0.45%   |
| Liège         | 5        | 0.45%   |
| Istanbul       | 5        | 0.45%   |
| Bogotá        | 5        | 0.45%   |
| Athens         | 5        | 0.45%   |
| Wroclaw        | 4        | 0.36%   |
| Prague         | 4        | 0.36%   |
| Porto Alegre   | 4        | 0.36%   |
| Paris          | 4        | 0.36%   |
| Lodz           | 4        | 0.36%   |
| Hamburg        | 4        | 0.36%   |
| Cologne        | 4        | 0.36%   |
| Bristol        | 4        | 0.36%   |
| Zaragoza       | 3        | 0.27%   |
| Yekaterinburg  | 3        | 0.27%   |
| Turin          | 3        | 0.27%   |
| Sofia          | 3        | 0.27%   |
| Seville        | 3        | 0.27%   |
| Santo André   | 3        | 0.27%   |
| Rouen          | 3        | 0.27%   |
| Rio de Janeiro | 3        | 0.27%   |
| Portland       | 3        | 0.27%   |
| Pollença      | 3        | 0.27%   |
| Philadelphia   | 3        | 0.27%   |
| Perth          | 3        | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 322      | 406    | 16.72%  |
| Seagate                     | 306      | 374    | 15.89%  |
| Samsung Electronics         | 242      | 318    | 12.56%  |
| Kingston                    | 125      | 144    | 6.49%   |
| Toshiba                     | 120      | 136    | 6.23%   |
| Crucial                     | 92       | 113    | 4.78%   |
| SanDisk                     | 63       | 68     | 3.27%   |
| Hitachi                     | 57       | 60     | 2.96%   |
| China                       | 44       | 49     | 2.28%   |
| A-DATA Technology           | 38       | 41     | 1.97%   |
| Unknown                     | 30       | 53     | 1.56%   |
| SPCC                        | 25       | 26     | 1.3%    |
| Maxtor                      | 22       | 26     | 1.14%   |
| Intel                       | 22       | 22     | 1.14%   |
| Patriot                     | 18       | 19     | 0.93%   |
| GOODRAM                     | 17       | 21     | 0.88%   |
| PNY                         | 16       | 17     | 0.83%   |
| Lexar                       | 16       | 19     | 0.83%   |
| Intenso                     | 15       | 18     | 0.78%   |
| Team                        | 13       | 13     | 0.67%   |
| JMicron Technology          | 13       | 13     | 0.67%   |
| HGST                        | 13       | 14     | 0.67%   |
| Apacer                      | 13       | 14     | 0.67%   |
| Kingston Technology Company | 12       | 15     | 0.62%   |
| Phison                      | 11       | 13     | 0.57%   |
| Micron Technology           | 11       | 11     | 0.57%   |
| Unknown                     | 11       | 12     | 0.57%   |
| Silicon Motion              | 10       | 11     | 0.52%   |
| Netac                       | 10       | 10     | 0.52%   |
| Fanxiang                    | 10       | 10     | 0.52%   |
| OCZ                         | 9        | 9      | 0.47%   |
| Transcend                   | 8        | 8      | 0.42%   |
| Hewlett-Packard             | 8        | 8      | 0.42%   |
| Corsair                     | 8        | 9      | 0.42%   |
| T-FORCE                     | 6        | 7      | 0.31%   |
| KIOXIA-EXCERIA              | 6        | 6      | 0.31%   |
| KingSpec                    | 6        | 7      | 0.31%   |
| KingFast                    | 6        | 7      | 0.31%   |
| XPG                         | 5        | 5      | 0.26%   |
| Plextor                     | 5        | 5      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 31       | 1.42%   |
| Seagate ST1000DM010-2EP102 1TB   | 27       | 1.24%   |
| Kingston SA400S37240G 240GB SSD  | 27       | 1.24%   |
| Kingston SA400S37480G 480GB SSD  | 23       | 1.06%   |
| Toshiba DT01ACA100 1TB           | 20       | 0.92%   |
| Crucial CT500MX500SSD1 500GB     | 17       | 0.78%   |
| WDC WD10EZEX-08WN4A0 1TB         | 16       | 0.73%   |
| Seagate ST2000DM008-2FR102 2TB   | 16       | 0.73%   |
| Samsung SSD 850 EVO 250GB        | 15       | 0.69%   |
| Kingston SA400S37120G 120GB SSD  | 15       | 0.69%   |
| Seagate ST1000DM003-1CH162 1TB   | 14       | 0.64%   |
| Crucial CT240BX500SSD1 240GB     | 14       | 0.64%   |
| Toshiba HDWD110 1TB              | 13       | 0.6%    |
| Toshiba DT01ACA050 500GB         | 13       | 0.6%    |
| Seagate ST3500418AS 500GB        | 13       | 0.6%    |
| SanDisk NVMe SSD Drive 1TB       | 13       | 0.6%    |
| Samsung SSD 850 EVO 500GB        | 13       | 0.6%    |
| Samsung SSD 870 QVO 1TB          | 11       | 0.5%    |
| Samsung SSD 860 EVO 500GB        | 11       | 0.5%    |
| Kingston SV300S37A120G 120GB SSD | 11       | 0.5%    |
| Unknown                          | 11       | 0.5%    |
| Seagate ST3500312CS 500GB        | 10       | 0.46%   |
| Seagate ST2000DM001-1CH164 2TB   | 10       | 0.46%   |
| Seagate ST1000DM003-1ER162 1TB   | 10       | 0.46%   |
| Unknown SD/MMC/MS PRO 128GB      | 9        | 0.41%   |
| Samsung SSD 970 EVO Plus 2TB     | 9        | 0.41%   |
| Samsung HD322HJ 320GB            | 9        | 0.41%   |
| JMicron Generic 500GB            | 9        | 0.41%   |
| Crucial CT1000MX500SSD1 1TB      | 9        | 0.41%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 8        | 0.37%   |
| WDC WD10EZEX-00BN5A0 1TB         | 8        | 0.37%   |
| Unknown SD/MMC 1073GB            | 8        | 0.37%   |
| Unknown M.S./M.S.Pro/HG 16GB     | 8        | 0.37%   |
| Unknown Compact Flash 977MB      | 8        | 0.37%   |
| Seagate ST1000DM003-1SB102 1TB   | 8        | 0.37%   |
| SanDisk SSD PLUS 1000GB          | 8        | 0.37%   |
| SanDisk NVMe SSD Drive 500GB     | 8        | 0.37%   |
| Samsung SSD 980 500GB            | 8        | 0.37%   |
| Toshiba MQ01ABF050 500GB         | 7        | 0.32%   |
| Seagate ST2000DM001-1ER164 2TB   | 7        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 304      | 371    | 33.97%  |
| WDC                 | 278      | 343    | 31.06%  |
| Toshiba             | 112      | 126    | 12.51%  |
| Samsung Electronics | 70       | 75     | 7.82%   |
| Hitachi             | 57       | 60     | 6.37%   |
| Maxtor              | 21       | 25     | 2.35%   |
| HGST                | 13       | 14     | 1.45%   |
| Unknown             | 10       | 11     | 1.12%   |
| JMicron Technology  | 10       | 10     | 1.12%   |
| Fujitsu             | 4        | 5      | 0.45%   |
| Apple               | 4        | 4      | 0.45%   |
| Min Yi U            | 2        | 2      | 0.22%   |
| ExcelStor           | 2        | 2      | 0.22%   |
| WD MediaMax         | 1        | 1      | 0.11%   |
| SABRENT             | 1        | 1      | 0.11%   |
| Intenso             | 1        | 1      | 0.11%   |
| IB-AC703            | 1        | 1      | 0.11%   |
| DAS                 | 1        | 4      | 0.11%   |
| ASMT                | 1        | 1      | 0.11%   |
| ASMedia             | 1        | 1      | 0.11%   |
| Unknown             | 1        | 2      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 126      | 154    | 16.89%  |
| Kingston            | 100      | 115    | 13.4%   |
| Crucial             | 71       | 78     | 9.52%   |
| China               | 44       | 49     | 5.9%    |
| WDC                 | 38       | 42     | 5.09%   |
| SanDisk             | 38       | 41     | 5.09%   |
| A-DATA Technology   | 27       | 28     | 3.62%   |
| SPCC                | 21       | 21     | 2.82%   |
| Patriot             | 17       | 18     | 2.28%   |
| GOODRAM             | 17       | 21     | 2.28%   |
| PNY                 | 15       | 16     | 2.01%   |
| Intenso             | 14       | 17     | 1.88%   |
| Intel               | 13       | 13     | 1.74%   |
| Apacer              | 10       | 10     | 1.34%   |
| OCZ                 | 9        | 9      | 1.21%   |
| Micron Technology   | 9        | 9      | 1.21%   |
| Lexar               | 9        | 10     | 1.21%   |
| Team                | 8        | 8      | 1.07%   |
| Unknown             | 8        | 8      | 1.07%   |
| Transcend           | 7        | 7      | 0.94%   |
| Toshiba             | 6        | 7      | 0.8%    |
| Netac               | 6        | 6      | 0.8%    |
| KingSpec            | 6        | 7      | 0.8%    |
| KingFast            | 6        | 7      | 0.8%    |
| Hewlett-Packard     | 6        | 6      | 0.8%    |
| Fanxiang            | 6        | 6      | 0.8%    |
| KIOXIA-EXCERIA      | 5        | 5      | 0.67%   |
| USB3.0              | 4        | 4      | 0.54%   |
| T-FORCE             | 4        | 5      | 0.54%   |
| Plextor             | 4        | 4      | 0.54%   |
| Verbatim            | 3        | 3      | 0.4%    |
| LITEON              | 3        | 3      | 0.4%    |
| INNOVATION IT       | 3        | 3      | 0.4%    |
| HS-SSD-C100         | 3        | 3      | 0.4%    |
| Emtec               | 3        | 3      | 0.4%    |
| XrayDisk            | 2        | 2      | 0.27%   |
| X12                 | 2        | 2      | 0.27%   |
| WALRAM              | 2        | 2      | 0.27%   |
| Vaseky              | 2        | 3      | 0.27%   |
| Teclast             | 2        | 2      | 0.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 700      | 1060   | 44.19%  |
| SSD     | 593      | 825    | 37.44%  |
| NVMe    | 264      | 359    | 16.67%  |
| Unknown | 19       | 37     | 1.2%    |
| MMC     | 8        | 9      | 0.51%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 995      | 1813   | 73.65%  |
| NVMe | 263      | 353    | 19.47%  |
| SAS  | 85       | 115    | 6.29%   |
| MMC  | 8        | 9      | 0.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 769      | 1129   | 56.59%  |
| 0.51-1.0   | 400      | 510    | 29.43%  |
| 1.01-2.0   | 116      | 147    | 8.54%   |
| 3.01-4.0   | 32       | 40     | 2.35%   |
| 2.01-3.0   | 27       | 34     | 1.99%   |
| 4.01-10.0  | 11       | 18     | 0.81%   |
| 10.01-20.0 | 4        | 7      | 0.29%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 354      | 31.95%  |
| 101-250        | 202      | 18.23%  |
| 251-500        | 170      | 15.34%  |
| 501-1000       | 109      | 9.84%   |
| Unknown        | 77       | 6.95%   |
| 51-100         | 71       | 6.41%   |
| 21-50          | 44       | 3.97%   |
| 1001-2000      | 44       | 3.97%   |
| More than 3000 | 20       | 1.81%   |
| 2001-3000      | 17       | 1.53%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 848      | 76.74%  |
| Unknown        | 77       | 6.97%   |
| 21-50          | 65       | 5.88%   |
| 101-250        | 30       | 2.71%   |
| 251-500        | 24       | 2.17%   |
| 51-100         | 22       | 1.99%   |
| 501-1000       | 15       | 1.36%   |
| 1001-2000      | 13       | 1.18%   |
| More than 3000 | 6        | 0.54%   |
| 2001-3000      | 5        | 0.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 10       | 10     | 2.51%   |
| Seagate ST3500418AS 500GB         | 9        | 9      | 2.26%   |
| Seagate ST1000DM010-2EP102 1TB    | 6        | 7      | 1.5%    |
| Toshiba DT01ACA050 500GB          | 5        | 5      | 1.25%   |
| Seagate ST3500312CS 500GB         | 5        | 5      | 1.25%   |
| Samsung Electronics HD322HJ 320GB | 5        | 6      | 1.25%   |
| Hitachi HTS543225L9A300 250GB     | 5        | 5      | 1.25%   |
| WDC WD10EARS-00Y5B1 1TB           | 4        | 4      | 1%      |
| Toshiba DT01ACA100 1TB            | 4        | 4      | 1%      |
| Seagate ST3160318AS 160GB         | 4        | 4      | 1%      |
| Seagate ST1000DM003-1CH162 1TB    | 4        | 4      | 1%      |
| Maxtor STM380815AS 80GB           | 4        | 5      | 1%      |
| Kingston SV300S37A120G 120GB SSD  | 4        | 4      | 1%      |
| WDC WD5000AVCS-632DY1 500GB       | 3        | 3      | 0.75%   |
| WDC WD5000AAKX-75U6AA0 500GB      | 3        | 3      | 0.75%   |
| WDC WD10EZEX-60M2NA0 1TB          | 3        | 3      | 0.75%   |
| Toshiba MQ01ABD075 752GB          | 3        | 3      | 0.75%   |
| Seagate ST500LT012-9WS142 500GB   | 3        | 3      | 0.75%   |
| Seagate ST3500413AS 500GB         | 3        | 3      | 0.75%   |
| Seagate ST2000DM001-1CH164 2TB    | 3        | 3      | 0.75%   |
| SanDisk SSD PLUS 480GB            | 3        | 3      | 0.75%   |
| Samsung Electronics HD502HJ 500GB | 3        | 3      | 0.75%   |
| Samsung Electronics HD320KJ 320GB | 3        | 4      | 0.75%   |
| Samsung Electronics HD103UJ 1TB   | 3        | 3      | 0.75%   |
| Samsung Electronics HD103SJ 1TB   | 3        | 3      | 0.75%   |
| WDC WD5000AAKX-08U6AA0 500GB      | 2        | 2      | 0.5%    |
| WDC WD5000AAKX-00ERMA0 500GB      | 2        | 2      | 0.5%    |
| WDC WD5000AAKS-60Z1A0 500GB       | 2        | 2      | 0.5%    |
| WDC WD3200AAJS-56M0A0 320GB       | 2        | 2      | 0.5%    |
| WDC WD3200AAJS-56B4A0 320GB       | 2        | 2      | 0.5%    |
| WDC WD3200AAJS-00L7A0 320GB       | 2        | 2      | 0.5%    |
| WDC WD2500AAKX-001CA0 250GB       | 2        | 2      | 0.5%    |
| WDC WD20EFRX-68EUZN0 2TB          | 2        | 3      | 0.5%    |
| WDC WD10EZEX-08WN4A0 1TB          | 2        | 2      | 0.5%    |
| WDC WD10EZEX-00BN5A0 1TB          | 2        | 2      | 0.5%    |
| Toshiba MQ01ABD100 1TB            | 2        | 2      | 0.5%    |
| Toshiba MK3259GSXP 320GB          | 2        | 2      | 0.5%    |
| Toshiba HDWD120 2TB               | 2        | 2      | 0.5%    |
| Seagate STM3250318AS 250GB        | 2        | 2      | 0.5%    |
| Seagate ST980811AS 80GB           | 2        | 2      | 0.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 106      | 113    | 27.39%  |
| WDC                 | 102      | 113    | 26.36%  |
| Samsung Electronics | 41       | 44     | 10.59%  |
| Hitachi             | 35       | 35     | 9.04%   |
| Toshiba             | 32       | 33     | 8.27%   |
| Maxtor              | 15       | 17     | 3.88%   |
| Kingston            | 10       | 10     | 2.58%   |
| SanDisk             | 7        | 7      | 1.81%   |
| China               | 4        | 4      | 1.03%   |
| A-DATA Technology   | 4        | 4      | 1.03%   |
| SPCC                | 3        | 3      | 0.78%   |
| XPG                 | 2        | 2      | 0.52%   |
| Netac               | 2        | 2      | 0.52%   |
| Micron Technology   | 2        | 2      | 0.52%   |
| HGST                | 2        | 2      | 0.52%   |
| Crucial             | 2        | 2      | 0.52%   |
| Reeinno             | 1        | 1      | 0.26%   |
| PNY                 | 1        | 1      | 0.26%   |
| Plextor             | 1        | 1      | 0.26%   |
| OCZ                 | 1        | 1      | 0.26%   |
| KingDian            | 1        | 1      | 0.26%   |
| KINGCOMP            | 1        | 1      | 0.26%   |
| JMicron Technology  | 1        | 1      | 0.26%   |
| Intenso             | 1        | 1      | 0.26%   |
| Intel               | 1        | 1      | 0.26%   |
| INNOVATION IT       | 1        | 1      | 0.26%   |
| Hewlett-Packard     | 1        | 1      | 0.26%   |
| Fujitsu             | 1        | 1      | 0.26%   |
| ExcelStor           | 1        | 1      | 0.26%   |
| EX276687RUS         | 1        | 1      | 0.26%   |
| Corsair             | 1        | 1      | 0.26%   |
| C300-CTF            | 1        | 1      | 0.26%   |
| C-S12               | 1        | 1      | 0.26%   |
| ASMT                | 1        | 1      | 0.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 106      | 113    | 32.52%  |
| WDC                 | 97       | 108    | 29.75%  |
| Samsung Electronics | 35       | 37     | 10.74%  |
| Hitachi             | 35       | 35     | 10.74%  |
| Toshiba             | 32       | 33     | 9.82%   |
| Maxtor              | 15       | 17     | 4.6%    |
| HGST                | 2        | 2      | 0.61%   |
| JMicron Technology  | 1        | 1      | 0.31%   |
| Fujitsu             | 1        | 1      | 0.31%   |
| ExcelStor           | 1        | 1      | 0.31%   |
| ASMT                | 1        | 1      | 0.31%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 287      | 349    | 82.95%  |
| SSD  | 51       | 54     | 14.74%  |
| NVMe | 8        | 8      | 2.31%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD3200BPVT-22JJ5T0 320GB    | 1        | 1      | 9.09%   |
| WDC WD10EZEX-22MFCA0 1TB        | 1        | 1      | 9.09%   |
| WDC WD10EZEX-00BN5A0 1TB        | 1        | 1      | 9.09%   |
| Toshiba MQ01ABF032 320GB        | 1        | 1      | 9.09%   |
| Seagate ST500DM002-1BD142 500GB | 1        | 1      | 9.09%   |
| Seagate ST3320613AS 320GB       | 1        | 1      | 9.09%   |
| Seagate ST3320418AS 320GB       | 1        | 1      | 9.09%   |
| Seagate ST3250318AS 250GB       | 1        | 1      | 9.09%   |
| Seagate ST31000528AS 1TB        | 1        | 1      | 9.09%   |
| Samsung Electronics HD203WI 2TB | 1        | 1      | 9.09%   |
| Hitachi HDS721050CLA360 500GB   | 1        | 1      | 9.09%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 5      | 45.45%  |
| WDC                 | 3        | 3      | 27.27%  |
| Toshiba             | 1        | 1      | 9.09%   |
| Samsung Electronics | 1        | 1      | 9.09%   |
| Hitachi             | 1        | 1      | 9.09%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 906      | 1723   | 66.33%  |
| Malfunc  | 336      | 411    | 24.6%   |
| Detected | 113      | 145    | 8.27%   |
| Failed   | 11       | 11     | 0.81%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 743      | 50.17%  |
| AMD                              | 313      | 21.13%  |
| Samsung Electronics              | 75       | 5.06%   |
| SanDisk                          | 46       | 3.11%   |
| Kingston Technology Company      | 40       | 2.7%    |
| ASMedia Technology               | 36       | 2.43%   |
| Phison Electronics               | 31       | 2.09%   |
| Nvidia                           | 27       | 1.82%   |
| JMicron Technology               | 26       | 1.76%   |
| Micron/Crucial Technology        | 23       | 1.55%   |
| Marvell Technology Group         | 21       | 1.42%   |
| Silicon Motion                   | 20       | 1.35%   |
| MAXIO Technology (Hangzhou)      | 17       | 1.15%   |
| Realtek Semiconductor            | 9        | 0.61%   |
| ADATA Technology                 | 9        | 0.61%   |
| VIA Technologies                 | 6        | 0.41%   |
| Micron Technology                | 6        | 0.41%   |
| Shenzhen Longsys Electronics     | 5        | 0.34%   |
| KIOXIA                           | 4        | 0.27%   |
| Broadcom / LSI                   | 4        | 0.27%   |
| Toshiba America Info Systems     | 3        | 0.2%    |
| LSI Logic / Symbios Logic        | 3        | 0.2%    |
| SK hynix                         | 2        | 0.14%   |
| Netac Technology                 | 2        | 0.14%   |
| INNOGRIT                         | 2        | 0.14%   |
| Union Memory (Shenzhen)          | 1        | 0.07%   |
| Sony                             | 1        | 0.07%   |
| Solid State Storage Technology   | 1        | 0.07%   |
| Silicon Integrated Systems [SiS] | 1        | 0.07%   |
| Seagate Technology               | 1        | 0.07%   |
| Lite-On Technology               | 1        | 0.07%   |
| Integrated Technology Express    | 1        | 0.07%   |
| Biwin Storage Technology         | 1        | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 155      | 8.48%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 99       | 5.42%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 76       | 4.16%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 70       | 3.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 64       | 3.5%    |
| AMD 400 Series Chipset SATA Controller                                                  | 59       | 3.23%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 56       | 3.06%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 53       | 2.9%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 46       | 2.52%   |
| AMD 500 Series Chipset SATA Controller                                                  | 44       | 2.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 42       | 2.3%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 39       | 2.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 34       | 1.86%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 34       | 1.86%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 33       | 1.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 30       | 1.64%   |
| Intel SATA Controller [RAID mode]                                                       | 29       | 1.59%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 29       | 1.59%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 29       | 1.59%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 24       | 1.31%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 23       | 1.26%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 22       | 1.2%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 18       | 0.98%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 17       | 0.93%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 16       | 0.88%   |
| Nvidia MCP61 SATA Controller                                                            | 16       | 0.88%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 16       | 0.88%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 15       | 0.82%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 14       | 0.77%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 14       | 0.77%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 13       | 0.71%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 13       | 0.71%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 12       | 0.66%   |
| Phison E12 NVMe Controller                                                              | 12       | 0.66%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                                    | 12       | 0.66%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 12       | 0.66%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 11       | 0.6%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 11       | 0.6%    |
| Nvidia MCP61 IDE                                                                        | 11       | 0.6%    |
| AMD FCH IDE Controller                                                                  | 11       | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 866      | 59.32%  |
| IDE  | 271      | 18.56%  |
| NVMe | 264      | 18.08%  |
| RAID | 50       | 3.42%   |
| SAS  | 5        | 0.34%   |
| SCSI | 4        | 0.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 755      | 68.82%  |
| AMD    | 342      | 31.18%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz            | 26       | 2.37%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 18       | 1.64%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 17       | 1.55%   |
| AMD Ryzen 5 3600 6-Core Processor           | 17       | 1.55%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 15       | 1.37%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 14       | 1.28%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 14       | 1.28%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 12       | 1.09%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 11       | 1%      |
| Intel Core i3-2100 CPU @ 3.10GHz            | 11       | 1%      |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 11       | 1%      |
| Intel Core i5-7400 CPU @ 3.00GHz            | 10       | 0.91%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 10       | 0.91%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 10       | 0.91%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 10       | 0.91%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 9        | 0.82%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 9        | 0.82%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 9        | 0.82%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 9        | 0.82%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 9        | 0.82%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 9        | 0.82%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 9        | 0.82%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 9        | 0.82%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 9        | 0.82%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 9        | 0.82%   |
| AMD FX-8350 Eight-Core Processor            | 9        | 0.82%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 8        | 0.73%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 8        | 0.73%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 8        | 0.73%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 8        | 0.73%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 8        | 0.73%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 8        | 0.73%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 7        | 0.64%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 7        | 0.64%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 7        | 0.64%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 7        | 0.64%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 6        | 0.55%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 6        | 0.55%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 6        | 0.55%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz       | 6        | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 240      | 21.86%  |
| Intel Core i7           | 109      | 9.93%   |
| Intel Core i3           | 107      | 9.74%   |
| AMD Ryzen 5             | 86       | 7.83%   |
| Other                   | 56       | 5.1%    |
| AMD Ryzen 7             | 46       | 4.19%   |
| Intel Core 2 Duo        | 39       | 3.55%   |
| Intel Celeron           | 39       | 3.55%   |
| Intel Xeon              | 36       | 3.28%   |
| Intel Pentium Dual-Core | 32       | 2.91%   |
| Intel Pentium           | 32       | 2.91%   |
| Intel Core 2 Quad       | 29       | 2.64%   |
| AMD FX                  | 29       | 2.64%   |
| AMD Ryzen 9             | 23       | 2.09%   |
| AMD Ryzen 3             | 23       | 2.09%   |
| AMD Athlon II X2        | 16       | 1.46%   |
| AMD A8                  | 16       | 1.46%   |
| AMD A6                  | 13       | 1.18%   |
| AMD Phenom II X4        | 11       | 1%      |
| AMD A4                  | 10       | 0.91%   |
| AMD A10                 | 10       | 0.91%   |
| AMD Athlon 64 X2        | 8        | 0.73%   |
| Intel Core 2            | 7        | 0.64%   |
| Intel Atom              | 7        | 0.64%   |
| AMD Athlon              | 7        | 0.64%   |
| Intel Pentium Dual      | 6        | 0.55%   |
| Intel Pentium Gold      | 4        | 0.36%   |
| Intel Pentium D         | 4        | 0.36%   |
| Intel Core i9           | 4        | 0.36%   |
| AMD Ryzen 5 PRO         | 4        | 0.36%   |
| AMD E                   | 4        | 0.36%   |
| Intel Genuine           | 3        | 0.27%   |
| AMD PRO A10             | 3        | 0.27%   |
| AMD GX                  | 3        | 0.27%   |
| AMD E1                  | 3        | 0.27%   |
| AMD Athlon X4           | 3        | 0.27%   |
| AMD Athlon Dual Core    | 3        | 0.27%   |
| Intel Pentium 4         | 2        | 0.18%   |
| AMD Sempron             | 2        | 0.18%   |
| AMD Phenom II X3        | 2        | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 447      | 40.71%  |
| 2      | 343      | 31.24%  |
| 6      | 148      | 13.48%  |
| 8      | 74       | 6.74%   |
| 1      | 28       | 2.55%   |
| 12     | 22       | 2%      |
| 10     | 12       | 1.09%   |
| 3      | 9        | 0.82%   |
| 16     | 8        | 0.73%   |
| 14     | 4        | 0.36%   |
| 36     | 1        | 0.09%   |
| 24     | 1        | 0.09%   |
| 5      | 1        | 0.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 1089     | 99.27%  |
| 2      | 6        | 0.55%   |
| 16     | 1        | 0.09%   |
| 14     | 1        | 0.09%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 566      | 51.55%  |
| 1      | 531      | 48.36%  |
| 12     | 1        | 0.09%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 1097     | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 775      | 70.65%  |
| 0x0a50000d | 24       | 2.19%   |
| 0x0a20120a | 22       | 2.01%   |
| 0x010000c8 | 18       | 1.64%   |
| 0x08701030 | 17       | 1.55%   |
| 0x08108109 | 17       | 1.55%   |
| 0x06001119 | 17       | 1.55%   |
| 0x08701021 | 16       | 1.46%   |
| 0x06000822 | 14       | 1.28%   |
| 0x0800820d | 13       | 1.19%   |
| 0x06003106 | 12       | 1.09%   |
| 0x08101016 | 7        | 0.64%   |
| 0x0600611a | 7        | 0.64%   |
| 0x06000817 | 7        | 0.64%   |
| 0x0a601206 | 6        | 0.55%   |
| 0x0a404102 | 6        | 0.55%   |
| 0x0700010b | 6        | 0.55%   |
| 0x06003104 | 6        | 0.55%   |
| 0x0600081c | 6        | 0.55%   |
| 0x0a50000c | 5        | 0.46%   |
| 0x0a201025 | 5        | 0.46%   |
| 0x08600106 | 5        | 0.46%   |
| 0x08001138 | 5        | 0.46%   |
| 0x010000b6 | 5        | 0.46%   |
| 0x05000101 | 4        | 0.36%   |
| 0x01000086 | 4        | 0.36%   |
| 0x0a601203 | 3        | 0.27%   |
| 0x0a20102b | 3        | 0.27%   |
| 0x08701013 | 3        | 0.27%   |
| 0x08008206 | 3        | 0.27%   |
| 0x07030105 | 3        | 0.27%   |
| 0x06006705 | 3        | 0.27%   |
| 0x05000028 | 3        | 0.27%   |
| 0x03000027 | 3        | 0.27%   |
| 0x010000c6 | 3        | 0.27%   |
| 0x0a50000f | 2        | 0.18%   |
| 0x0a20120e | 2        | 0.18%   |
| 0x08600109 | 2        | 0.18%   |
| 0x08108102 | 2        | 0.18%   |
| 0x08101013 | 2        | 0.18%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 133      | 12.11%  |
| IvyBridge        | 110      | 10.02%  |
| Penryn           | 87       | 7.92%   |
| SandyBridge      | 81       | 7.38%   |
| KabyLake         | 74       | 6.74%   |
| Zen 3            | 67       | 6.1%    |
| Skylake          | 49       | 4.46%   |
| Piledriver       | 46       | 4.19%   |
| Zen 2            | 45       | 4.1%    |
| CometLake        | 43       | 3.92%   |
| Zen+             | 40       | 3.64%   |
| Alderlake Hybrid | 37       | 3.37%   |
| K10              | 36       | 3.28%   |
| Core             | 36       | 3.28%   |
| Westmere         | 23       | 2.09%   |
| Nehalem          | 22       | 2%      |
| Unknown          | 20       | 1.82%   |
| Zen              | 19       | 1.73%   |
| Steamroller      | 19       | 1.73%   |
| K8 Hammer        | 16       | 1.46%   |
| Silvermont       | 15       | 1.37%   |
| Icelake          | 14       | 1.28%   |
| Excavator        | 11       | 1%      |
| Bobcat           | 9        | 0.82%   |
| Gracemont        | 8        | 0.73%   |
| NetBurst         | 6        | 0.55%   |
| Jaguar           | 6        | 0.55%   |
| Tremont          | 5        | 0.46%   |
| K10 Llano        | 5        | 0.46%   |
| Broadwell        | 5        | 0.46%   |
| Puma             | 4        | 0.36%   |
| Bonnell          | 3        | 0.27%   |
| Goldmont plus    | 2        | 0.18%   |
| Goldmont         | 1        | 0.09%   |
| Bulldozer        | 1        | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 428      | 37.74%  |
| Nvidia            | 351      | 30.95%  |
| AMD               | 350      | 30.86%  |
| Red Hat           | 2        | 0.18%   |
| ATI Technologies  | 2        | 0.18%   |
| ASPEED Technology | 1        | 0.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 68       | 5.89%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 49       | 4.24%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 47       | 4.07%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 32       | 2.77%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 32       | 2.77%   |
| Intel HD Graphics 530                                                                    | 29       | 2.51%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 28       | 2.42%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 19       | 1.65%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 19       | 1.65%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 18       | 1.56%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 18       | 1.56%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 17       | 1.47%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 16       | 1.39%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 16       | 1.39%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 15       | 1.3%    |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 15       | 1.3%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 14       | 1.21%   |
| Intel Core Processor Integrated Graphics Controller                                      | 13       | 1.13%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 13       | 1.13%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 13       | 1.13%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 12       | 1.04%   |
| Intel HD Graphics 630                                                                    | 12       | 1.04%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                                | 12       | 1.04%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 12       | 1.04%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 12       | 1.04%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 12       | 1.04%   |
| Nvidia GT218 [GeForce 210]                                                               | 11       | 0.95%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 11       | 0.95%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 11       | 0.95%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 10       | 0.87%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 10       | 0.87%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 10       | 0.87%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 9        | 0.78%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 9        | 0.78%   |
| AMD RS780L [Radeon 3000]                                                                 | 9        | 0.78%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 8        | 0.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8        | 0.69%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 8        | 0.69%   |
| AMD Raphael                                                                              | 8        | 0.69%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 7        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| 1 x Intel              | 379      | 34.42%  |
| 1 x AMD                | 325      | 29.52%  |
| 1 x Nvidia             | 320      | 29.06%  |
| Intel + Nvidia         | 22       | 2%      |
| 2 x Intel              | 21       | 1.91%   |
| 2 x AMD                | 16       | 1.45%   |
| AMD + Nvidia           | 6        | 0.54%   |
| Intel + AMD            | 5        | 0.45%   |
| 2 x Nvidia             | 3        | 0.27%   |
| 1 x Red Hat            | 2        | 0.18%   |
| 2 x Intel + 1 x Nvidia | 1        | 0.09%   |
| Nvidia + ASPEED        | 1        | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1055     | 96.08%  |
| Unknown     | 35       | 3.19%   |
| Proprietary | 8        | 0.73%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 429      | 38.96%  |
| 1.01-2.0   | 176      | 15.99%  |
| 0.51-1.0   | 146      | 13.26%  |
| 0.01-0.5   | 119      | 10.81%  |
| 3.01-4.0   | 85       | 7.72%   |
| 7.01-8.0   | 76       | 6.9%    |
| 8.01-16.0  | 34       | 3.09%   |
| 5.01-6.0   | 22       | 2%      |
| 2.01-3.0   | 10       | 0.91%   |
| 16.01-24.0 | 3        | 0.27%   |
| 4.01-5.0   | 1        | 0.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 180      | 16.76%  |
| Goldstar                | 125      | 11.64%  |
| Dell                    | 91       | 8.47%   |
| Acer                    | 82       | 7.64%   |
| Hewlett-Packard         | 79       | 7.36%   |
| AOC                     | 64       | 5.96%   |
| Philips                 | 56       | 5.21%   |
| BenQ                    | 43       | 4%      |
| Ancor Communications    | 39       | 3.63%   |
| ViewSonic               | 29       | 2.7%    |
| Iiyama                  | 21       | 1.96%   |
| Sony                    | 19       | 1.77%   |
| ASUSTek Computer        | 16       | 1.49%   |
| NEC Computers           | 14       | 1.3%    |
| Lenovo                  | 14       | 1.3%    |
| MSI                     | 13       | 1.21%   |
| Eizo                    | 12       | 1.12%   |
| Fujitsu Siemens         | 11       | 1.02%   |
| Unknown (XXX)           | 7        | 0.65%   |
| RTK                     | 7        | 0.65%   |
| Panasonic               | 7        | 0.65%   |
| Unknown                 | 6        | 0.56%   |
| Hitachi                 | 6        | 0.56%   |
| Toshiba                 | 5        | 0.47%   |
| Sharp                   | 5        | 0.47%   |
| Medion                  | 5        | 0.47%   |
| HKC                     | 5        | 0.47%   |
| ___                     | 4        | 0.37%   |
| Sceptre Tech            | 4        | 0.37%   |
| Belinea                 | 4        | 0.37%   |
| TCL                     | 3        | 0.28%   |
| Packard Bell            | 3        | 0.28%   |
| MStar                   | 3        | 0.28%   |
| HannStar                | 3        | 0.28%   |
| Haier                   | 3        | 0.28%   |
| Gigabyte Technology     | 3        | 0.28%   |
| eMachines               | 3        | 0.28%   |
| CVT                     | 3        | 0.28%   |
| Chi Mei Optoelectronics | 3        | 0.28%   |
| Vizio                   | 2        | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 5        | 0.46%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 5        | 0.46%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 5        | 0.46%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                    | 5        | 0.46%   |
| Dell P2311H DEL4066 1920x1080 510x290mm 23.1-inch                     | 5        | 0.46%   |
| Ancor Communications BE24A ACI24AB 1920x1200 518x324mm 24.1-inch      | 5        | 0.46%   |
| Ancor Communications ASUS VC239 ACI23C4 1920x1080 509x286mm 23.0-inch | 5        | 0.46%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch     | 4        | 0.37%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 4        | 0.37%   |
| NEC Computers EA244WMi NEC68D6 1920x1200 519x324mm 24.1-inch          | 4        | 0.37%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                    | 4        | 0.37%   |
| AOC Q27G2WG4 AOC2702 2560x1440 597x336mm 27.0-inch                    | 4        | 0.37%   |
| Acer K222HQL ACR03E1 1920x1080 477x268mm 21.5-inch                    | 4        | 0.37%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch            | 3        | 0.28%   |
| TCL L23D2200F TCL2304 1920x1080 510x287mm 23.0-inch                   | 3        | 0.28%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 3        | 0.28%   |
| Philips PHL 221V8 PHLC211 1920x1080 477x268mm 21.5-inch               | 3        | 0.28%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                    | 3        | 0.28%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                      | 3        | 0.28%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch            | 3        | 0.28%   |
| Goldstar W2261 GSM56CF 1920x1080 477x268mm 21.5-inch                  | 3        | 0.28%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch               | 3        | 0.28%   |
| Goldstar IPS237 GSM5901 1920x1080 510x290mm 23.1-inch                 | 3        | 0.28%   |
| Goldstar FULL HD GSM5BFB 1920x1080 480x270mm 21.7-inch                | 3        | 0.28%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                | 3        | 0.28%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 3        | 0.28%   |
| Dell S2340L DELD058 1920x1080 509x286mm 23.0-inch                     | 3        | 0.28%   |
| BenQ ZOWIE XL LCD BNQ7F31 1920x1080 531x298mm 24.0-inch               | 3        | 0.28%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 3        | 0.28%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                    | 3        | 0.28%   |
| AOC 24G2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 3        | 0.28%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 3        | 0.28%   |
| AOC 2217 AOC2217 1680x1050 470x300mm 22.0-inch                        | 3        | 0.28%   |
| AOC 1950W AOC1950 1366x768 410x230mm 18.5-inch                        | 3        | 0.28%   |
| Acer V226HQL ACR032D 1920x1080 477x268mm 21.5-inch                    | 3        | 0.28%   |
| ___ LCD TV ___9000 1360x768                                           | 2        | 0.18%   |
| ViewSonic VX2452 Series VSCDE2E 1920x1080 521x293mm 23.5-inch         | 2        | 0.18%   |
| ViewSonic VA2265 SERIES VSCB330 1920x1080 476x268mm 21.5-inch         | 2        | 0.18%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 2        | 0.18%   |
| Unknown (XXX) HDMI XXX0088 1920x540                                   | 2        | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 519      | 48.96%  |
| 3840x2160 (4K)     | 86       | 8.11%   |
| 1280x1024 (SXGA)   | 74       | 6.98%   |
| 2560x1440 (QHD)    | 66       | 6.23%   |
| 1680x1050 (WSXGA+) | 55       | 5.19%   |
| 1366x768 (WXGA)    | 53       | 5%      |
| 1440x900 (WXGA+)   | 44       | 4.15%   |
| 1920x1200 (WUXGA)  | 38       | 3.58%   |
| 1600x900 (HD+)     | 37       | 3.49%   |
| 1360x768           | 20       | 1.89%   |
| 3440x1440          | 13       | 1.23%   |
| 1920x540           | 11       | 1.04%   |
| 1600x1200          | 10       | 0.94%   |
| 1024x768 (XGA)     | 10       | 0.94%   |
| 2560x1080          | 9        | 0.85%   |
| 1280x720 (HD)      | 4        | 0.38%   |
| 3840x1600          | 2        | 0.19%   |
| 2288x1287          | 2        | 0.19%   |
| 2048x1152          | 2        | 0.19%   |
| 1280x960           | 2        | 0.19%   |
| 2256x1504          | 1        | 0.09%   |
| 1360x765           | 1        | 0.09%   |
| Unknown            | 1        | 0.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 153      | 14.31%  |
| 23      | 151      | 14.13%  |
| 21      | 129      | 12.07%  |
| 27      | 119      | 11.13%  |
| 19      | 72       | 6.74%   |
| 31      | 66       | 6.17%   |
| 18      | 55       | 5.14%   |
| 17      | 50       | 4.68%   |
| 22      | 44       | 4.12%   |
| 20      | 40       | 3.74%   |
| Unknown | 22       | 2.06%   |
| 15      | 21       | 1.96%   |
| 72      | 20       | 1.87%   |
| 84      | 19       | 1.78%   |
| 34      | 19       | 1.78%   |
| 54      | 9        | 0.84%   |
| 32      | 9        | 0.84%   |
| 40      | 7        | 0.65%   |
| 28      | 6        | 0.56%   |
| 25      | 6        | 0.56%   |
| 52      | 5        | 0.47%   |
| 37      | 5        | 0.47%   |
| 26      | 4        | 0.37%   |
| 16      | 4        | 0.37%   |
| 48      | 3        | 0.28%   |
| 46      | 3        | 0.28%   |
| 142     | 2        | 0.19%   |
| 85      | 2        | 0.19%   |
| 74      | 2        | 0.19%   |
| 55      | 2        | 0.19%   |
| 43      | 2        | 0.19%   |
| 42      | 2        | 0.19%   |
| 38      | 2        | 0.19%   |
| 12      | 2        | 0.19%   |
| 75      | 1        | 0.09%   |
| 65      | 1        | 0.09%   |
| 61      | 1        | 0.09%   |
| 59      | 1        | 0.09%   |
| 58      | 1        | 0.09%   |
| 49      | 1        | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 419      | 39.49%  |
| 401-500        | 306      | 28.84%  |
| 601-700        | 79       | 7.45%   |
| 301-350        | 68       | 6.41%   |
| 1501-2000      | 44       | 4.15%   |
| 351-400        | 42       | 3.96%   |
| 701-800        | 30       | 2.83%   |
| 1001-1500      | 27       | 2.54%   |
| Unknown        | 22       | 2.07%   |
| 801-900        | 16       | 1.51%   |
| 901-1000       | 4        | 0.38%   |
| More than 2000 | 2        | 0.19%   |
| 201-300        | 2        | 0.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 743      | 71.58%  |
| 16/10   | 155      | 14.93%  |
| 5/4     | 78       | 7.51%   |
| 21/9    | 25       | 2.41%   |
| 4/3     | 22       | 2.12%   |
| Unknown | 6        | 0.58%   |
| 32/9    | 3        | 0.29%   |
| 3/2     | 3        | 0.29%   |
| 1.00    | 2        | 0.19%   |
| 1.96    | 1        | 0.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 373      | 35.06%  |
| 151-200        | 154      | 14.47%  |
| 301-350        | 123      | 11.56%  |
| 351-500        | 97       | 9.12%   |
| 141-150        | 90       | 8.46%   |
| 251-300        | 77       | 7.24%   |
| More than 1000 | 69       | 6.48%   |
| 501-1000       | 25       | 2.35%   |
| Unknown        | 22       | 2.07%   |
| 101-110        | 19       | 1.79%   |
| 131-140        | 5        | 0.47%   |
| 111-120        | 3        | 0.28%   |
| 71-80          | 2        | 0.19%   |
| 121-130        | 2        | 0.19%   |
| 91-100         | 2        | 0.19%   |
| 81-90          | 1        | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 743      | 71.58%  |
| 101-120 | 174      | 16.76%  |
| 1-50    | 55       | 5.3%    |
| 121-160 | 30       | 2.89%   |
| Unknown | 22       | 2.12%   |
| 161-240 | 14       | 1.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 975      | 88.64%  |
| 2     | 72       | 6.55%   |
| 0     | 48       | 4.36%   |
| 3     | 5        | 0.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 723      | 49.86%  |
| Intel                             | 393      | 27.1%   |
| Qualcomm Atheros                  | 83       | 5.72%   |
| Broadcom                          | 37       | 2.55%   |
| TP-Link                           | 33       | 2.28%   |
| Ralink Technology                 | 32       | 2.21%   |
| Nvidia                            | 24       | 1.66%   |
| Qualcomm Atheros Communications   | 14       | 0.97%   |
| Ralink                            | 13       | 0.9%    |
| D-Link                            | 13       | 0.9%    |
| MediaTek                          | 12       | 0.83%   |
| Marvell Technology Group          | 8        | 0.55%   |
| NetGear                           | 6        | 0.41%   |
| Broadcom Limited                  | 6        | 0.41%   |
| Huawei Technologies               | 5        | 0.34%   |
| Samsung Electronics               | 4        | 0.28%   |
| ASUSTek Computer                  | 4        | 0.28%   |
| VIA Technologies                  | 3        | 0.21%   |
| Qualcomm                          | 3        | 0.21%   |
| ASIX Electronics                  | 3        | 0.21%   |
| Xiaomi                            | 2        | 0.14%   |
| Microsoft                         | 2        | 0.14%   |
| Mercucys                          | 2        | 0.14%   |
| BUFFALO                           | 2        | 0.14%   |
| AVM                               | 2        | 0.14%   |
| Aquantia                          | 2        | 0.14%   |
| ZyXEL Communications              | 1        | 0.07%   |
| ZTE WCDMA Technologies MSM        | 1        | 0.07%   |
| U-Blox                            | 1        | 0.07%   |
| Tenda                             | 1        | 0.07%   |
| Sundance Technology Inc / IC Plus | 1        | 0.07%   |
| Smart Link                        | 1        | 0.07%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.07%   |
| OPPO Electronics                  | 1        | 0.07%   |
| Motorola PCS                      | 1        | 0.07%   |
| Mellanox Technologies             | 1        | 0.07%   |
| Manta                             | 1        | 0.07%   |
| JMicron Technology                | 1        | 0.07%   |
| Gemtek                            | 1        | 0.07%   |
| Edimax Technology                 | 1        | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 566      | 35.29%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 66       | 4.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 53       | 3.3%    |
| Realtek RTL8125 2.5GbE Controller                                      | 49       | 3.05%   |
| Intel Ethernet Connection I217-LM                                      | 36       | 2.24%   |
| Intel Ethernet Controller I225-V                                       | 25       | 1.56%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 24       | 1.5%    |
| Intel Ethernet Connection (2) I219-V                                   | 24       | 1.5%    |
| Intel Wi-Fi 6 AX200                                                    | 23       | 1.43%   |
| Intel 82579V Gigabit Network Connection                                | 21       | 1.31%   |
| Ralink MT7601U Wireless Adapter                                        | 20       | 1.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 19       | 1.18%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 19       | 1.18%   |
| Intel I211 Gigabit Network Connection                                  | 18       | 1.12%   |
| Realtek 802.11ac NIC                                                   | 17       | 1.06%   |
| Intel Ethernet Connection (2) I219-LM                                  | 16       | 1%      |
| Nvidia MCP61 Ethernet                                                  | 14       | 0.87%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 14       | 0.87%   |
| Intel Ethernet Connection I217-V                                       | 13       | 0.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 12       | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 11       | 0.69%   |
| Intel 82578DM Gigabit Network Connection                               | 11       | 0.69%   |
| Qualcomm Atheros AR9271 802.11n                                        | 10       | 0.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 10       | 0.62%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 9        | 0.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 9        | 0.56%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 8        | 0.5%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 8        | 0.5%    |
| Intel Ethernet Connection (7) I219-V                                   | 8        | 0.5%    |
| Intel Ethernet Connection (2) I218-V                                   | 8        | 0.5%    |
| Intel 82574L Gigabit Network Connection                                | 8        | 0.5%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 7        | 0.44%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter               | 7        | 0.44%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 7        | 0.44%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 7        | 0.44%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 7        | 0.44%   |
| Intel Wireless 7260                                                    | 7        | 0.44%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 6        | 0.37%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                        | 6        | 0.37%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 6        | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 126      | 29.51%  |
| Intel                           | 114      | 26.7%   |
| Qualcomm Atheros                | 35       | 8.2%    |
| TP-Link                         | 33       | 7.73%   |
| Ralink Technology               | 32       | 7.49%   |
| Qualcomm Atheros Communications | 14       | 3.28%   |
| Ralink                          | 13       | 3.04%   |
| D-Link                          | 13       | 3.04%   |
| Broadcom                        | 12       | 2.81%   |
| MediaTek                        | 11       | 2.58%   |
| NetGear                         | 6        | 1.41%   |
| ASUSTek Computer                | 4        | 0.94%   |
| Microsoft                       | 2        | 0.47%   |
| Mercucys                        | 2        | 0.47%   |
| BUFFALO                         | 2        | 0.47%   |
| AVM                             | 2        | 0.47%   |
| ZyXEL Communications            | 1        | 0.23%   |
| Tenda                           | 1        | 0.23%   |
| Gemtek                          | 1        | 0.23%   |
| Edimax Technology               | 1        | 0.23%   |
| CyberTAN Technology             | 1        | 0.23%   |
| Belkin Components               | 1        | 0.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 24       | 5.59%   |
| Intel Wi-Fi 6 AX200                                            | 23       | 5.36%   |
| Ralink MT7601U Wireless Adapter                                | 20       | 4.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 19       | 4.43%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 19       | 4.43%   |
| Realtek 802.11ac NIC                                           | 17       | 3.96%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 12       | 2.8%    |
| Qualcomm Atheros AR9271 802.11n                                | 10       | 2.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 10       | 2.33%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 8        | 1.86%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 8        | 1.86%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 7        | 1.63%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 7        | 1.63%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 7        | 1.63%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 7        | 1.63%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 7        | 1.63%   |
| Intel Wireless 7260                                            | 7        | 1.63%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 6        | 1.4%    |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 6        | 1.4%    |
| Intel Wireless 7265                                            | 6        | 1.4%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 5        | 1.17%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 5        | 1.17%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 5        | 1.17%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 5        | 1.17%   |
| Intel Wireless 3165                                            | 5        | 1.17%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 4        | 0.93%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 4        | 0.93%   |
| Ralink RT5370 Wireless Adapter                                 | 4        | 0.93%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 4        | 0.93%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 4        | 0.93%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 4        | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4        | 0.93%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 4        | 0.93%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 3        | 0.7%    |
| TP-Link 802.11ac NIC                                           | 3        | 0.7%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 3        | 0.7%    |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 3        | 0.7%    |
| Realtek RTL8188EE Wireless Network Adapter                     | 3        | 0.7%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 3        | 0.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3        | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 675      | 59.37%  |
| Intel                             | 316      | 27.79%  |
| Qualcomm Atheros                  | 52       | 4.57%   |
| Broadcom                          | 25       | 2.2%    |
| Nvidia                            | 24       | 2.11%   |
| Marvell Technology Group          | 8        | 0.7%    |
| Broadcom Limited                  | 6        | 0.53%   |
| Huawei Technologies               | 5        | 0.44%   |
| VIA Technologies                  | 3        | 0.26%   |
| Samsung Electronics               | 3        | 0.26%   |
| Qualcomm                          | 3        | 0.26%   |
| ASIX Electronics                  | 3        | 0.26%   |
| Xiaomi                            | 2        | 0.18%   |
| Aquantia                          | 2        | 0.18%   |
| Sundance Technology Inc / IC Plus | 1        | 0.09%   |
| Silicon Integrated Systems [SiS]  | 1        | 0.09%   |
| OPPO Electronics                  | 1        | 0.09%   |
| Motorola PCS                      | 1        | 0.09%   |
| Mellanox Technologies             | 1        | 0.09%   |
| MediaTek                          | 1        | 0.09%   |
| JMicron Technology                | 1        | 0.09%   |
| DisplayLink                       | 1        | 0.09%   |
| Apple                             | 1        | 0.09%   |
| 3Com                              | 1        | 0.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 566      | 48.42%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 66       | 5.65%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 53       | 4.53%   |
| Realtek RTL8125 2.5GbE Controller                                      | 49       | 4.19%   |
| Intel Ethernet Connection I217-LM                                      | 36       | 3.08%   |
| Intel Ethernet Controller I225-V                                       | 25       | 2.14%   |
| Intel Ethernet Connection (2) I219-V                                   | 24       | 2.05%   |
| Intel 82579V Gigabit Network Connection                                | 21       | 1.8%    |
| Intel I211 Gigabit Network Connection                                  | 18       | 1.54%   |
| Intel Ethernet Connection (2) I219-LM                                  | 16       | 1.37%   |
| Nvidia MCP61 Ethernet                                                  | 14       | 1.2%    |
| Intel 82567LM-3 Gigabit Network Connection                             | 14       | 1.2%    |
| Intel Ethernet Connection I217-V                                       | 13       | 1.11%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 11       | 0.94%   |
| Intel 82578DM Gigabit Network Connection                               | 11       | 0.94%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 9        | 0.77%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 9        | 0.77%   |
| Intel Ethernet Connection (7) I219-V                                   | 8        | 0.68%   |
| Intel Ethernet Connection (2) I218-V                                   | 8        | 0.68%   |
| Intel 82574L Gigabit Network Connection                                | 8        | 0.68%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 6        | 0.51%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 6        | 0.51%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                             | 5        | 0.43%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 5        | 0.43%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 5        | 0.43%   |
| Intel Ethernet Controller I226-V                                       | 5        | 0.43%   |
| Intel Ethernet Connection (17) I219-V                                  | 5        | 0.43%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 4        | 0.34%   |
| Intel I210 Gigabit Network Connection                                  | 4        | 0.34%   |
| Intel Ethernet Connection (14) I219-V                                  | 4        | 0.34%   |
| Intel Ethernet Connection (11) I219-V                                  | 4        | 0.34%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 4        | 0.34%   |
| Huawei E353/E3131                                                      | 4        | 0.34%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 4        | 0.34%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3        | 0.26%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 3        | 0.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3        | 0.26%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 3        | 0.26%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 3        | 0.26%   |
| Nvidia MCP51 Ethernet Controller                                       | 3        | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1084     | 72.07%  |
| WiFi     | 414      | 27.53%  |
| Modem    | 5        | 0.33%   |
| Unknown  | 1        | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 864      | 80.22%  |
| WiFi     | 213      | 19.78%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 789      | 71.92%  |
| 2     | 273      | 24.89%  |
| 3     | 20       | 1.82%   |
| 0     | 10       | 0.91%   |
| 4     | 5        | 0.46%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 727      | 66.15%  |
| Yes  | 372      | 33.85%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 108      | 36.99%  |
| Cambridge Silicon Radio         | 79       | 27.05%  |
| Realtek Semiconductor           | 40       | 13.7%   |
| Broadcom                        | 14       | 4.79%   |
| MediaTek                        | 10       | 3.42%   |
| Qualcomm Atheros Communications | 8        | 2.74%   |
| ASUSTek Computer                | 8        | 2.74%   |
| IMC Networks                    | 7        | 2.4%    |
| TP-Link                         | 5        | 1.71%   |
| Lite-On Technology              | 4        | 1.37%   |
| Integrated System Solution      | 2        | 0.68%   |
| Edimax Technology               | 2        | 0.68%   |
| Apple                           | 2        | 0.68%   |
| Foxconn / Hon Hai               | 1        | 0.34%   |
| Dynex                           | 1        | 0.34%   |
| Unknown                         | 1        | 0.34%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 79       | 27.05%  |
| Realtek Bluetooth Radio                                  | 29       | 9.93%   |
| Intel AX200 Bluetooth                                    | 22       | 7.53%   |
| Intel Bluetooth wireless interface                       | 21       | 7.19%   |
| Intel Wireless-AC 3168 Bluetooth                         | 19       | 6.51%   |
| Intel AX210 Bluetooth                                    | 19       | 6.51%   |
| MediaTek Wireless_Device                                 | 10       | 3.42%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 10       | 3.42%   |
| Intel AX201 Bluetooth                                    | 10       | 3.42%   |
| Realtek  Bluetooth 4.2 Adapter                           | 8        | 2.74%   |
| IMC Networks Bluetooth Radio                             | 6        | 2.05%   |
| TP-Link TP-Link Bluetooth USB Adapter                    | 5        | 1.71%   |
| Qualcomm Atheros  Bluetooth Device                       | 4        | 1.37%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 4        | 1.37%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 4        | 1.37%   |
| Broadcom HP Portable Bumble Bee                          | 3        | 1.03%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 2        | 0.68%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth               | 2        | 0.68%   |
| Lite-On Bluetooth Device                                 | 2        | 0.68%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 2        | 0.68%   |
| Edimax Bluetooth Adapter                                 | 2        | 0.68%   |
| Broadcom BCM2045 Bluetooth                               | 2        | 0.68%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 2        | 0.68%   |
| ASUS BCM20702A0                                          | 2        | 0.68%   |
| ASUS ASUS USB-BT500                                      | 2        | 0.68%   |
| Realtek RTL8821A Bluetooth                               | 1        | 0.34%   |
| Realtek RTL8723B Bluetooth                               | 1        | 0.34%   |
| Realtek Bluetooth 5.3 Radio                              | 1        | 0.34%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                   | 1        | 0.34%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 1        | 0.34%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter         | 1        | 0.34%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter    | 1        | 0.34%   |
| Integrated System Solution Bluetooth Device              | 1        | 0.34%   |
| IMC Networks Wireless_Device                             | 1        | 0.34%   |
| Foxconn / Hon Hai Wireless_Device                        | 1        | 0.34%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 0.34%   |
| Broadcom HP Bluethunder                                  | 1        | 0.34%   |
| Broadcom Bluetooth V3.0 USB Device                       | 1        | 0.34%   |
| Broadcom Bluetooth 3.0 Device                            | 1        | 0.34%   |
| Broadcom BCM2210 Bluetooth                               | 1        | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 734      | 44.67%  |
| AMD                                          | 422      | 25.68%  |
| Nvidia                                       | 320      | 19.48%  |
| C-Media Electronics                          | 35       | 2.13%   |
| Creative Labs                                | 16       | 0.97%   |
| Texas Instruments                            | 10       | 0.61%   |
| ASUSTek Computer                             | 9        | 0.55%   |
| Creative Technology                          | 6        | 0.37%   |
| Razer USA                                    | 5        | 0.3%    |
| Tenx Technology                              | 4        | 0.24%   |
| Generalplus Technology                       | 4        | 0.24%   |
| Zoran Co. Personal Media Division (Nogatech) | 3        | 0.18%   |
| M-Audio                                      | 3        | 0.18%   |
| Logitech                                     | 3        | 0.18%   |
| Kingston Technology                          | 3        | 0.18%   |
| GN Netcom                                    | 3        | 0.18%   |
| Focusrite-Novation                           | 3        | 0.18%   |
| Bose                                         | 3        | 0.18%   |
| VIA Technologies                             | 2        | 0.12%   |
| SAVITECH                                     | 2        | 0.12%   |
| Realtek Semiconductor                        | 2        | 0.12%   |
| Micro Star International                     | 2        | 0.12%   |
| Lenovo                                       | 2        | 0.12%   |
| KTMicro                                      | 2        | 0.12%   |
| JMTek                                        | 2        | 0.12%   |
| Jieli Technology                             | 2        | 0.12%   |
| GYROCOM C&C                                  | 2        | 0.12%   |
| FiiO Electronics Technology                  | 2        | 0.12%   |
| Fifine Microphones                           | 2        | 0.12%   |
| ATI Technologies                             | 2        | 0.12%   |
| Xilinx                                       | 1        | 0.06%   |
| Valve Software                               | 1        | 0.06%   |
| Thesycon Systemsoftware & Consulting         | 1        | 0.06%   |
| SteelSeries ApS                              | 1        | 0.06%   |
| Sony                                         | 1        | 0.06%   |
| somic                                        | 1        | 0.06%   |
| Silicon Integrated Systems [SiS]             | 1        | 0.06%   |
| Samson Technologies                          | 1        | 0.06%   |
| PreSonus Audio Electronics                   | 1        | 0.06%   |
| Plantronics                                  | 1        | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 108      | 5.49%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 97       | 4.93%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 84       | 4.27%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                        | 83       | 4.22%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 79       | 4.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 74       | 3.76%   |
| AMD Starship/Matisse HD Audio Controller                                          | 69       | 3.51%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 63       | 3.2%    |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 54       | 2.75%   |
| AMD FCH Azalia Controller                                                         | 53       | 2.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 52       | 2.64%   |
| Intel 200 Series PCH HD Audio                                                     | 50       | 2.54%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 43       | 2.19%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 40       | 2.03%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 32       | 1.63%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 31       | 1.58%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 27       | 1.37%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 26       | 1.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 26       | 1.32%   |
| Nvidia GF108 High Definition Audio Controller                                     | 25       | 1.27%   |
| Intel Alder Lake-S HD Audio Controller                                            | 24       | 1.22%   |
| Nvidia High Definition Audio Controller                                           | 22       | 1.12%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 22       | 1.12%   |
| Intel Comet Lake PCH-V cAVS                                                       | 20       | 1.02%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 20       | 1.02%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 20       | 1.02%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 19       | 0.97%   |
| Intel Cannon Lake PCH cAVS                                                        | 19       | 0.97%   |
| Nvidia GF119 HDMI Audio Controller                                                | 18       | 0.92%   |
| Nvidia TU116 High Definition Audio Controller                                     | 17       | 0.86%   |
| Nvidia GP108 High Definition Audio Controller                                     | 17       | 0.86%   |
| AMD Rembrandt Radeon High Definition Audio Controller                             | 16       | 0.81%   |
| AMD Navi 10 HDMI Audio                                                            | 16       | 0.81%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 16       | 0.81%   |
| Intel Smart Sound Technology (SST) Audio Controller                               | 15       | 0.76%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 15       | 0.76%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 15       | 0.76%   |
| AMD Trinity HDMI Audio Controller                                                 | 15       | 0.76%   |
| Nvidia MCP61 High Definition Audio                                                | 14       | 0.71%   |
| AMD Kaveri HDMI/DP Audio Controller                                               | 14       | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 226      | 17.04%  |
| Unknown                      | 195      | 14.71%  |
| Samsung Electronics          | 152      | 11.46%  |
| SK hynix                     | 125      | 9.43%   |
| Corsair                      | 104      | 7.84%   |
| Crucial                      | 89       | 6.71%   |
| Micron Technology            | 73       | 5.51%   |
| G.Skill                      | 63       | 4.75%   |
| Unknown                      | 30       | 2.26%   |
| A-DATA Technology            | 22       | 1.66%   |
| Team                         | 20       | 1.51%   |
| Ramaxel Technology           | 17       | 1.28%   |
| Patriot                      | 17       | 1.28%   |
| Nanya Technology             | 15       | 1.13%   |
| GOODRAM                      | 14       | 1.06%   |
| Elpida                       | 14       | 1.06%   |
| Smart                        | 8        | 0.6%    |
| AMD                          | 8        | 0.6%    |
| Transcend                    | 7        | 0.53%   |
| Atermiter                    | 7        | 0.53%   |
| Apacer                       | 7        | 0.53%   |
| PNY                          | 6        | 0.45%   |
| Unknown (0x0E9D)             | 4        | 0.3%    |
| Patriot Memory (PDP Systems) | 4        | 0.3%    |
| Juhor                        | 4        | 0.3%    |
| Kllisre                      | 3        | 0.23%   |
| Kingmax                      | 3        | 0.23%   |
| Avant                        | 3        | 0.23%   |
| ASint Technology             | 3        | 0.23%   |
| Wodposit                     | 2        | 0.15%   |
| Wilk Elektronik              | 2        | 0.15%   |
| Unknown (0x7FFF)             | 2        | 0.15%   |
| Timetec                      | 2        | 0.15%   |
| Thermaltake                  | 2        | 0.15%   |
| Teikon                       | 2        | 0.15%   |
| Silicon Power                | 2        | 0.15%   |
| Red Hat                      | 2        | 0.15%   |
| Qimonda                      | 2        | 0.15%   |
| Patriot Memory               | 2        | 0.15%   |
| Novatech                     | 2        | 0.15%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Unknown                                                  | 30       | 2.05%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM 1600MT/s           | 15       | 1.02%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 13       | 0.89%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                | 12       | 0.82%   |
| Unknown RAM Module 2GB DIMM SDRAM                        | 12       | 0.82%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 11       | 0.75%   |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 10       | 0.68%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s      | 10       | 0.68%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                 | 9        | 0.61%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s     | 9        | 0.61%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s      | 9        | 0.61%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                 | 8        | 0.55%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                 | 8        | 0.55%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s      | 8        | 0.55%   |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s   | 8        | 0.55%   |
| Unknown RAM Module 2GB DIMM DDR2                         | 7        | 0.48%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s       | 7        | 0.48%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s      | 7        | 0.48%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 7        | 0.48%   |
| Crucial RAM CT102464BA160B.C16 8192MB DIMM DDR3 1600MT/s | 7        | 0.48%   |
| Unknown RAM Module 4GB DIMM SDRAM                        | 6        | 0.41%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                | 6        | 0.41%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 6        | 0.41%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                     | 6        | 0.41%   |
| Unknown RAM Module 2GB DIMM 400MT/s                      | 6        | 0.41%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                     | 6        | 0.41%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s     | 6        | 0.41%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s     | 6        | 0.41%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s      | 6        | 0.41%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1800MT/s      | 6        | 0.41%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s      | 6        | 0.41%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1333MT/s    | 6        | 0.41%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 4000MT/s      | 6        | 0.41%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s   | 6        | 0.41%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3466MT/s    | 6        | 0.41%   |
| Unknown RAM Module 4GB DIMM 800MT/s                      | 5        | 0.34%   |
| Unknown RAM Module 4GB DIMM 400MT/s                      | 5        | 0.34%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s    | 5        | 0.34%   |
| Samsung RAM M378B5773DH0-CH9 2048MB DIMM DDR3 1333MT/s   | 5        | 0.34%   |
| Elpida RAM EBJ21UE8BDF0-DJ-F 2GB DIMM DDR3 1333MT/s      | 5        | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 435      | 38.94%  |
| DDR4    | 413      | 36.97%  |
| SDRAM   | 75       | 6.71%   |
| Unknown | 75       | 6.71%   |
| DDR2    | 70       | 6.27%   |
| DDR5    | 26       | 2.33%   |
| DDR     | 15       | 1.34%   |
| DRAM    | 4        | 0.36%   |
| RAM     | 2        | 0.18%   |
| LPDDR5  | 1        | 0.09%   |
| LPDDR4  | 1        | 0.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 989      | 91.07%  |
| SODIMM       | 91       | 8.38%   |
| FB-DIMM      | 4        | 0.37%   |
| Row Of Chips | 1        | 0.09%   |
| RIMM         | 1        | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 445      | 36.03%  |
| 4096  | 338      | 27.37%  |
| 2048  | 219      | 17.73%  |
| 16384 | 127      | 10.28%  |
| 1024  | 53       | 4.29%   |
| 32768 | 42       | 3.4%    |
| 512   | 6        | 0.49%   |
| 24576 | 1        | 0.08%   |
| 15616 | 1        | 0.08%   |
| 12333 | 1        | 0.08%   |
| 3072  | 1        | 0.08%   |
| 256   | 1        | 0.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 269      | 21.25%  |
| 1333    | 165      | 13.03%  |
| 3200    | 97       | 7.66%   |
| 2667    | 73       | 5.77%   |
| 2400    | 67       | 5.29%   |
| 3600    | 63       | 4.98%   |
| 2133    | 51       | 4.03%   |
| Unknown | 44       | 3.48%   |
| 800     | 43       | 3.4%    |
| 667     | 41       | 3.24%   |
| 1867    | 24       | 1.9%    |
| 1800    | 24       | 1.9%    |
| 2666    | 22       | 1.74%   |
| 400     | 18       | 1.42%   |
| 3733    | 16       | 1.26%   |
| 1866    | 16       | 1.26%   |
| 1066    | 15       | 1.18%   |
| 3800    | 14       | 1.11%   |
| 3466    | 14       | 1.11%   |
| 4800    | 12       | 0.95%   |
| 2933    | 12       | 0.95%   |
| 3400    | 11       | 0.87%   |
| 1067    | 11       | 0.87%   |
| 4000    | 10       | 0.79%   |
| 533     | 10       | 0.79%   |
| 3000    | 8        | 0.63%   |
| 3534    | 6        | 0.47%   |
| 2800    | 6        | 0.47%   |
| 2000    | 6        | 0.47%   |
| 1648    | 6        | 0.47%   |
| 1334    | 6        | 0.47%   |
| 333     | 6        | 0.47%   |
| 6000    | 5        | 0.39%   |
| 5600    | 5        | 0.39%   |
| 3066    | 5        | 0.39%   |
| 49926   | 4        | 0.32%   |
| 2465    | 4        | 0.32%   |
| 1639    | 4        | 0.32%   |
| 1632    | 4        | 0.32%   |
| 5200    | 3        | 0.24%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 25       | 40.98%  |
| Brother Industries    | 9        | 14.75%  |
| Samsung Electronics   | 8        | 13.11%  |
| Canon                 | 7        | 11.48%  |
| Seiko Epson           | 6        | 9.84%   |
| Prolific Technology   | 3        | 4.92%   |
| Oki Data              | 1        | 1.64%   |
| Lexmark International | 1        | 1.64%   |
| Apple                 | 1        | 1.64%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Prolific PL2305 Parallel Port                | 3        | 4.92%   |
| Samsung ML-1660 Series                       | 2        | 3.28%   |
| HP ENVY 5000 series                          | 2        | 3.28%   |
| HP DeskJet 4100 series                       | 2        | 3.28%   |
| HP DeskJet 2700 series                       | 2        | 3.28%   |
| HP DeskJet 2620 All-in-One Printer           | 2        | 3.28%   |
| Seiko Epson XP-2100 Series                   | 1        | 1.64%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1        | 1.64%   |
| Seiko Epson L3210 Series                     | 1        | 1.64%   |
| Seiko Epson L3150 Series                     | 1        | 1.64%   |
| Seiko Epson L300 Series                      | 1        | 1.64%   |
| Seiko Epson ET-4850 Series                   | 1        | 1.64%   |
| Samsung SCX-6x55X Series                     | 1        | 1.64%   |
| Samsung ML-216x Series Laser Printer         | 1        | 1.64%   |
| Samsung ML-1865                              | 1        | 1.64%   |
| Samsung ML-1640 Series Laser Printer         | 1        | 1.64%   |
| Samsung M2020 Series                         | 1        | 1.64%   |
| Samsung Composite Device                     | 1        | 1.64%   |
| Oki Data MC363 Multifunction Printer         | 1        | 1.64%   |
| Lexmark International MS510dn                | 1        | 1.64%   |
| HP Printing Support                          | 1        | 1.64%   |
| HP PhotoSmart 7150                           | 1        | 1.64%   |
| HP OfficeJet Pro 7740 series                 | 1        | 1.64%   |
| HP OfficeJet Pro 6960                        | 1        | 1.64%   |
| HP OfficeJet 8010 series                     | 1        | 1.64%   |
| HP OfficeJet 3830 series                     | 1        | 1.64%   |
| HP LaserJet 1200                             | 1        | 1.64%   |
| HP LaserJet 1020                             | 1        | 1.64%   |
| HP LaserJet 1015                             | 1        | 1.64%   |
| HP ENVY 4520 series                          | 1        | 1.64%   |
| HP DeskJet 6940 series                       | 1        | 1.64%   |
| HP DeskJet 4530 series                       | 1        | 1.64%   |
| HP DeskJet 3630 series                       | 1        | 1.64%   |
| HP Deskjet 3050A                             | 1        | 1.64%   |
| HP DeskJet 2300 series                       | 1        | 1.64%   |
| HP Deskjet 1510                              | 1        | 1.64%   |
| HP Color LaserJet CP1215                     | 1        | 1.64%   |
| Canon PIXMA MG3600 Series                    | 1        | 1.64%   |
| Canon MF4410                                 | 1        | 1.64%   |
| Canon MF4010 series                          | 1        | 1.64%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 8        | 72.73%  |
| Hewlett-Packard | 2        | 18.18%  |
| Seiko Epson     | 1        | 9.09%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Canon CanoScan LIDE 25                            | 2        | 18.18%  |
| Canon CanoScan LiDE 110                           | 2        | 18.18%  |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100] | 1        | 9.09%   |
| HP Scanjet G2710                                  | 1        | 9.09%   |
| HP ScanJet 2400c                                  | 1        | 9.09%   |
| Canon CanoScan N670U/N676U/LiDE 20                | 1        | 9.09%   |
| Canon CanoScan N650U/N656U                        | 1        | 9.09%   |
| Canon CanoScan LiDE 220                           | 1        | 9.09%   |
| Canon CanoScan 1220U                              | 1        | 9.09%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 41       | 35.65%  |
| Microsoft                     | 9        | 7.83%   |
| Microdia                      | 7        | 6.09%   |
| Z-Star Microelectronics       | 4        | 3.48%   |
| Chicony Electronics           | 4        | 3.48%   |
| Unknown                       | 3        | 2.61%   |
| Sunplus Innovation Technology | 3        | 2.61%   |
| KYE Systems (Mouse Systems)   | 3        | 2.61%   |
| Hewlett-Packard               | 3        | 2.61%   |
| SunplusIT                     | 2        | 1.74%   |
| Realtek Semiconductor         | 2        | 1.74%   |
| MacroSilicon                  | 2        | 1.74%   |
| Genesys Logic                 | 2        | 1.74%   |
| Generalplus Technology        | 2        | 1.74%   |
| GEMBIRD                       | 2        | 1.74%   |
| Creative Technology           | 2        | 1.74%   |
| Bison Electronics             | 2        | 1.74%   |
| ASUSTek Computer              | 2        | 1.74%   |
| Arkmicro Technologies         | 2        | 1.74%   |
| ARC International             | 2        | 1.74%   |
| WaveRider Communications      | 1        | 0.87%   |
| Valve Software                | 1        | 0.87%   |
| Sunplus IT                    | 1        | 0.87%   |
| Samsung Electronics           | 1        | 0.87%   |
| Polycom                       | 1        | 0.87%   |
| Pixart Imaging                | 1        | 0.87%   |
| Netchip Technology            | 1        | 0.87%   |
| Jieli Technology              | 1        | 0.87%   |
| Jeilin Technology             | 1        | 0.87%   |
| IOGEAR                        | 1        | 0.87%   |
| ezcap                         | 1        | 0.87%   |
| eMPIA Technology              | 1        | 0.87%   |
| Dynex                         | 1        | 0.87%   |
| Apple                         | 1        | 0.87%   |
| A4Tech                        | 1        | 0.87%   |
| 2M UVC CAMERA                 | 1        | 0.87%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech Webcam C270                     | 13       | 11.3%   |
| Logitech C922 Pro Stream Webcam          | 4        | 3.48%   |
| Unknown HD camera                        | 3        | 2.61%   |
| Microsoft LifeCam HD-3000                | 3        | 2.61%   |
| Logitech HD Webcam C615                  | 3        | 2.61%   |
| Logitech HD Pro Webcam C920              | 3        | 2.61%   |
| Z-Star Venus USB2.0 Camera               | 2        | 1.74%   |
| Sunplus Full HD webcam                   | 2        | 1.74%   |
| Microsoft LifeCam VX-500 [1357]          | 2        | 1.74%   |
| Microdia Integrated Camera               | 2        | 1.74%   |
| Logitech Webcam C930e                    | 2        | 1.74%   |
| Logitech Webcam C310                     | 2        | 1.74%   |
| Logitech Webcam C170                     | 2        | 1.74%   |
| Logitech HD Webcam C525                  | 2        | 1.74%   |
| KYE Systems (Mouse Systems) USB20 Camera | 2        | 1.74%   |
| HP HP Webcam HD 2300                     | 2        | 1.74%   |
| Generalplus GENERAL WEBCAM               | 2        | 1.74%   |
| GEMBIRD USB2.0 PC CAMERA                 | 2        | 1.74%   |
| Chicony HP High Definition 1MP Webcam    | 2        | 1.74%   |
| ASUS CU4K30 UVC UHD Video                | 2        | 1.74%   |
| ARC International Camera                 | 2        | 1.74%   |
| Z-Star Vimicro USB Camera (Altair)       | 1        | 0.87%   |
| Z-Star Integrated Camera                 | 1        | 0.87%   |
| WaveRider USB Live camera                | 1        | 0.87%   |
| Valve Software 3D Camera                 | 1        | 0.87%   |
| SunplusIT USB 2.0 Camera                 | 1        | 0.87%   |
| SunplusIT Depstech webcam                | 1        | 0.87%   |
| Sunplus IT PC Camera                     | 1        | 0.87%   |
| Sunplus USB 2.0 Camera                   | 1        | 0.87%   |
| Samsung Galaxy series, misc. (MTP mode)  | 1        | 0.87%   |
| Realtek NexiGo N660P FHD Webcam          | 1        | 0.87%   |
| Realtek FULL HD 1080P Webcam             | 1        | 0.87%   |
| Polycom Poly Studio P5 webcam            | 1        | 0.87%   |
| Pixart Imaging Digital_Camera            | 1        | 0.87%   |
| Netchip Nuroum V11                       | 1        | 0.87%   |
| Microsoft LifeCam VX-700                 | 1        | 0.87%   |
| Microsoft LifeCam VX-5000                | 1        | 0.87%   |
| Microsoft LifeCam VX-2000                | 1        | 0.87%   |
| Microsoft LifeCam Studio                 | 1        | 0.87%   |
| Microdia Webcam Vitade AF                | 1        | 0.87%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Upek   | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| OmniKey               | 1        | 16.67%  |
| Gemalto (was Gemplus) | 1        | 16.67%  |
| Chicony Electronics   | 1        | 16.67%  |
| CHERRY                | 1        | 16.67%  |
| Alcor Micro           | 1        | 16.67%  |
| Advanced Card Systems | 1        | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| OmniKey CardMan 3121 (HID Technologies)              | 1        | 16.67%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader    | 1        | 16.67%  |
| Chicony Electronics HP Skylab USB Smartcard Keyboard | 1        | 16.67%  |
| CHERRY SmartCard Reader Keyboard KC 1000 SC          | 1        | 16.67%  |
| Alcor Micro Watchdata W 1981                         | 1        | 16.67%  |
| Advanced Card Systems ACR38 SmartCard Reader         | 1        | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1006     | 91.54%  |
| 1     | 84       | 7.64%   |
| 2     | 8        | 0.73%   |
| 3     | 1        | 0.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 52       | 54.17%  |
| Unassigned class         | 12       | 12.5%   |
| Net/wireless             | 12       | 12.5%   |
| Communication controller | 7        | 7.29%   |
| Multimedia controller    | 5        | 5.21%   |
| Chipcard                 | 4        | 4.17%   |
| Storage/raid             | 2        | 2.08%   |
| Fingerprint reader       | 1        | 1.04%   |
| Card reader              | 1        | 1.04%   |

