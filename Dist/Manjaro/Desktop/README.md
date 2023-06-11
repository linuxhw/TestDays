Manjaro - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for Manjaro.

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

Total: 3934

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | X370 GAMING M7 ACK          | [450b8ab5a7](https://linux-hardware.org/?probe=450b8ab5a7) | Jun 10, 2023 |
| Dell          | 0KC9NP A01                  | [ab5b79d6fd](https://linux-hardware.org/?probe=ab5b79d6fd) | Jun 10, 2023 |
| Unknown       | Unknown                     | [4c9c3d929b](https://linux-hardware.org/?probe=4c9c3d929b) | Jun 10, 2023 |
| Gigabyte      | B550 GAMING X V2            | [03ef8fea42](https://linux-hardware.org/?probe=03ef8fea42) | Jun 10, 2023 |
| HP            | 82C9                        | [b696990030](https://linux-hardware.org/?probe=b696990030) | Jun 09, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [f4f543eaa6](https://linux-hardware.org/?probe=f4f543eaa6) | Jun 09, 2023 |
| HP            | 3397                        | [c754fea198](https://linux-hardware.org/?probe=c754fea198) | Jun 08, 2023 |
| ASRock        | Z270 Gaming K6              | [31a7447d8b](https://linux-hardware.org/?probe=31a7447d8b) | Jun 08, 2023 |
| ASRock        | Z270 Gaming K6              | [267154b0d2](https://linux-hardware.org/?probe=267154b0d2) | Jun 08, 2023 |
| Gigabyte      | A520M H                     | [302bb0628a](https://linux-hardware.org/?probe=302bb0628a) | Jun 08, 2023 |
| HP            | 3397                        | [d86a6fc258](https://linux-hardware.org/?probe=d86a6fc258) | Jun 07, 2023 |
| HP            | 2B36                        | [45ee697eed](https://linux-hardware.org/?probe=45ee697eed) | Jun 07, 2023 |
| HP            | 2B36                        | [0f36ecaa7e](https://linux-hardware.org/?probe=0f36ecaa7e) | Jun 07, 2023 |
| DIEBOLD       | B85H3-M5                    | [7e56b1fd68](https://linux-hardware.org/?probe=7e56b1fd68) | Jun 07, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [ae164f9998](https://linux-hardware.org/?probe=ae164f9998) | Jun 06, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [6ae325ff9d](https://linux-hardware.org/?probe=6ae325ff9d) | Jun 06, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [77e1fa9533](https://linux-hardware.org/?probe=77e1fa9533) | Jun 06, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | [c33bc572fd](https://linux-hardware.org/?probe=c33bc572fd) | Jun 06, 2023 |
| ASUSTek       | PRIME H370M-PLUS            | [bbbe24d6b6](https://linux-hardware.org/?probe=bbbe24d6b6) | Jun 06, 2023 |
| HP            | 8918                        | [6f94c9caa9](https://linux-hardware.org/?probe=6f94c9caa9) | Jun 06, 2023 |
| Dell          | 055H3G A01                  | [3fc296df33](https://linux-hardware.org/?probe=3fc296df33) | Jun 05, 2023 |
| MSI           | GF615M-P33                  | [84f237f434](https://linux-hardware.org/?probe=84f237f434) | Jun 04, 2023 |
| HP            | 8643 SMVB                   | [88fbd57dac](https://linux-hardware.org/?probe=88fbd57dac) | Jun 04, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [06752ca793](https://linux-hardware.org/?probe=06752ca793) | Jun 04, 2023 |
| Biostar       | B450MX-S                    | [ccc6b5c4b5](https://linux-hardware.org/?probe=ccc6b5c4b5) | Jun 03, 2023 |
| Biostar       | B450MX-S                    | [6a01df1d69](https://linux-hardware.org/?probe=6a01df1d69) | Jun 03, 2023 |
| HP            | 3397                        | [530b98edd5](https://linux-hardware.org/?probe=530b98edd5) | Jun 03, 2023 |
| HP            | 8918                        | [b03f8a6eb3](https://linux-hardware.org/?probe=b03f8a6eb3) | Jun 02, 2023 |
| Pegatron      | H81-M1                      | [cdb426bfb4](https://linux-hardware.org/?probe=cdb426bfb4) | Jun 02, 2023 |
| Pegatron      | H81-M1                      | [35eb509619](https://linux-hardware.org/?probe=35eb509619) | Jun 02, 2023 |
| ASRock        | B450 Gaming K4              | [24ccc7665f](https://linux-hardware.org/?probe=24ccc7665f) | Jun 01, 2023 |
| ASRock        | B450 Gaming K4              | [af6c8f3355](https://linux-hardware.org/?probe=af6c8f3355) | Jun 01, 2023 |
| MSI           | P55-GD55                    | [1400fdf705](https://linux-hardware.org/?probe=1400fdf705) | May 31, 2023 |
| MSI           | PRO X670-P WIFI             | [10f4ef3e86](https://linux-hardware.org/?probe=10f4ef3e86) | May 31, 2023 |
| MSI           | PRO Z790-A WIFI             | [676d83919f](https://linux-hardware.org/?probe=676d83919f) | May 30, 2023 |
| HP            | 0B54h D                     | [c7813156eb](https://linux-hardware.org/?probe=c7813156eb) | May 30, 2023 |
| HP            | 2B36                        | [8e4fc0d41f](https://linux-hardware.org/?probe=8e4fc0d41f) | May 29, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [e29eb3dfcc](https://linux-hardware.org/?probe=e29eb3dfcc) | May 29, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [40ba623a3e](https://linux-hardware.org/?probe=40ba623a3e) | May 28, 2023 |
| MSI           | A520M-A PRO                 | [c78b5e28f1](https://linux-hardware.org/?probe=c78b5e28f1) | May 28, 2023 |
| ASUSTek       | ROG STRIX X399-E GAMING     | [4f1ff269d2](https://linux-hardware.org/?probe=4f1ff269d2) | May 28, 2023 |
| ASUSTek       | PRIME H510M-A               | [4945ea3fba](https://linux-hardware.org/?probe=4945ea3fba) | May 26, 2023 |
| Intel         | DN2820FYK H24582-204        | [1987af2458](https://linux-hardware.org/?probe=1987af2458) | May 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [5c4649a83e](https://linux-hardware.org/?probe=5c4649a83e) | May 24, 2023 |
| Unknown       | Unknown                     | [957b9f9de8](https://linux-hardware.org/?probe=957b9f9de8) | May 23, 2023 |
| HP            | 8876 11                     | [889144e990](https://linux-hardware.org/?probe=889144e990) | May 23, 2023 |
| AMI           | Intel                       | [9ddb291be3](https://linux-hardware.org/?probe=9ddb291be3) | May 22, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [781e226978](https://linux-hardware.org/?probe=781e226978) | May 22, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [68caefd4e9](https://linux-hardware.org/?probe=68caefd4e9) | May 22, 2023 |
| Lenovo        | 3753 NOK                    | [f2971c14a7](https://linux-hardware.org/?probe=f2971c14a7) | May 21, 2023 |
| AMI           | Intel                       | [13f87e64f1](https://linux-hardware.org/?probe=13f87e64f1) | May 21, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | [2a95b22ac3](https://linux-hardware.org/?probe=2a95b22ac3) | May 21, 2023 |
| Unknown       | HX90                        | [d640a32296](https://linux-hardware.org/?probe=d640a32296) | May 21, 2023 |
| Lenovo        | 3714 NOK                    | [0da1ff78c6](https://linux-hardware.org/?probe=0da1ff78c6) | May 20, 2023 |
| MSI           | X370 GAMING M7 ACK          | [c59f2a4b1e](https://linux-hardware.org/?probe=c59f2a4b1e) | May 19, 2023 |
| MSI           | GF615M-P33                  | [09ae9aca26](https://linux-hardware.org/?probe=09ae9aca26) | May 19, 2023 |
| ASRock        | 890FX Deluxe4               | [c00eb20149](https://linux-hardware.org/?probe=c00eb20149) | May 18, 2023 |
| Gigabyte      | A520M H                     | [a776d86dad](https://linux-hardware.org/?probe=a776d86dad) | May 17, 2023 |
| Gigabyte      | X99-Gaming 5                | [81eee33114](https://linux-hardware.org/?probe=81eee33114) | May 17, 2023 |
| Dell          | 0W0CHX A00                  | [a74974308d](https://linux-hardware.org/?probe=a74974308d) | May 16, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [9dd2c4cbee](https://linux-hardware.org/?probe=9dd2c4cbee) | May 16, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [dfc49eb820](https://linux-hardware.org/?probe=dfc49eb820) | May 16, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [a4cbf66286](https://linux-hardware.org/?probe=a4cbf66286) | May 16, 2023 |
| MSI           | B450 TOMAHAWK               | [a1d85d1caf](https://linux-hardware.org/?probe=a1d85d1caf) | May 16, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [aeb8c0e04f](https://linux-hardware.org/?probe=aeb8c0e04f) | May 16, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | [9ed74f5d63](https://linux-hardware.org/?probe=9ed74f5d63) | May 15, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | [b4ffbbf7d3](https://linux-hardware.org/?probe=b4ffbbf7d3) | May 15, 2023 |
| MSI           | 760GM-P23                   | [970443eea3](https://linux-hardware.org/?probe=970443eea3) | May 14, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [beb403e4e0](https://linux-hardware.org/?probe=beb403e4e0) | May 14, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [65374a707a](https://linux-hardware.org/?probe=65374a707a) | May 14, 2023 |
| Intel         | X79F1 V2.0                  | [a2446b63b3](https://linux-hardware.org/?probe=a2446b63b3) | May 14, 2023 |
| Intel         | H61 V1.1                    | [f5cbf650c3](https://linux-hardware.org/?probe=f5cbf650c3) | May 14, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [58c658819c](https://linux-hardware.org/?probe=58c658819c) | May 13, 2023 |
| MSI           | MAG B550M BAZOOKA           | [ef9c6905f1](https://linux-hardware.org/?probe=ef9c6905f1) | May 13, 2023 |
| ASRock        | H370M-ITX/ac                | [7f4f38aeb1](https://linux-hardware.org/?probe=7f4f38aeb1) | May 13, 2023 |
| HP            | 3047h                       | [bb0087d307](https://linux-hardware.org/?probe=bb0087d307) | May 12, 2023 |
| ASUSTek       | F1A75-M PRO/CSM             | [f9a67e4a1f](https://linux-hardware.org/?probe=f9a67e4a1f) | May 11, 2023 |
| Gigabyte      | B550 GAMING X V2            | [4d4946eec9](https://linux-hardware.org/?probe=4d4946eec9) | May 11, 2023 |
| ASUSTek       | F1A75-M PRO/CSM             | [18a4110763](https://linux-hardware.org/?probe=18a4110763) | May 11, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [ec8e4b5f19](https://linux-hardware.org/?probe=ec8e4b5f19) | May 11, 2023 |
| Lenovo        | ThinkCentre M71z 1761E4U    | [a865f3d92e](https://linux-hardware.org/?probe=a865f3d92e) | May 11, 2023 |
| Gigabyte      | 970A-DS3P                   | [1e4f2a0daf](https://linux-hardware.org/?probe=1e4f2a0daf) | May 10, 2023 |
| Gigabyte      | Z97X-SLI-CF                 | [5921d78ceb](https://linux-hardware.org/?probe=5921d78ceb) | May 10, 2023 |
| Gigabyte      | Z590 UD AC                  | [532e5b78de](https://linux-hardware.org/?probe=532e5b78de) | May 09, 2023 |
| MSI           | B85-G43                     | [878fbbb243](https://linux-hardware.org/?probe=878fbbb243) | May 09, 2023 |
| Gigabyte      | AX370-Gaming 5              | [462a9b182b](https://linux-hardware.org/?probe=462a9b182b) | May 09, 2023 |
| ASRock        | N68-S3 UCC                  | [8a1fbe8e3c](https://linux-hardware.org/?probe=8a1fbe8e3c) | May 09, 2023 |
| Gateway       | RS780                       | [e04207a390](https://linux-hardware.org/?probe=e04207a390) | May 07, 2023 |
| Gigabyte      | B450 AORUS M                | [87e972803c](https://linux-hardware.org/?probe=87e972803c) | May 07, 2023 |
| Intel         | H61                         | [c359f42a22](https://linux-hardware.org/?probe=c359f42a22) | May 07, 2023 |
| ASRock        | X670E Steel Legend          | [0c0ad48cc6](https://linux-hardware.org/?probe=0c0ad48cc6) | May 07, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | [812ae9a763](https://linux-hardware.org/?probe=812ae9a763) | May 06, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [4d21a72bfb](https://linux-hardware.org/?probe=4d21a72bfb) | May 05, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [ffab85a31a](https://linux-hardware.org/?probe=ffab85a31a) | May 05, 2023 |
| Gigabyte      | X99-Gaming 5                | [e1d1bdef81](https://linux-hardware.org/?probe=e1d1bdef81) | May 04, 2023 |
| ASUSTek       | ProArt B550-CREATOR         | [5989cc1ac0](https://linux-hardware.org/?probe=5989cc1ac0) | May 03, 2023 |
| ASUSTek       | ProArt B550-CREATOR         | [9258699383](https://linux-hardware.org/?probe=9258699383) | May 03, 2023 |
| ASRock        | A320M-HDV R4.0              | [1909560f36](https://linux-hardware.org/?probe=1909560f36) | May 02, 2023 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [553a101cf8](https://linux-hardware.org/?probe=553a101cf8) | May 02, 2023 |
| ASRock        | A320M-HDV R4.0              | [17097573de](https://linux-hardware.org/?probe=17097573de) | May 02, 2023 |
| Dell          | 073MMW A02                  | [09a404ced5](https://linux-hardware.org/?probe=09a404ced5) | May 02, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [7ffccfda78](https://linux-hardware.org/?probe=7ffccfda78) | May 01, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [cf6a478eb1](https://linux-hardware.org/?probe=cf6a478eb1) | May 01, 2023 |
| ASRock        | B650 LiveMixer              | [aecb4b61b4](https://linux-hardware.org/?probe=aecb4b61b4) | May 01, 2023 |
| Shuttle       | DL20N                       | [3f97bcaa08](https://linux-hardware.org/?probe=3f97bcaa08) | Apr 30, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | [2e2b57b3ae](https://linux-hardware.org/?probe=2e2b57b3ae) | Apr 30, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | [e47ae2080c](https://linux-hardware.org/?probe=e47ae2080c) | Apr 29, 2023 |
| MSI           | B450M MORTAR MAX            | [3586d79ce4](https://linux-hardware.org/?probe=3586d79ce4) | Apr 29, 2023 |
| HP            | 845A                        | [d0aa2a4a7a](https://linux-hardware.org/?probe=d0aa2a4a7a) | Apr 29, 2023 |
| HP            | 845A                        | [f8bc4601ef](https://linux-hardware.org/?probe=f8bc4601ef) | Apr 29, 2023 |
| Pegatron      | Benicia                     | [930452646c](https://linux-hardware.org/?probe=930452646c) | Apr 28, 2023 |
| ASUSTek       | ROG STRIX Z370-I GAMING     | [e8886a7521](https://linux-hardware.org/?probe=e8886a7521) | Apr 28, 2023 |
| Apple         | Mac-F221BEC8                | [3342a295e8](https://linux-hardware.org/?probe=3342a295e8) | Apr 28, 2023 |
| Dell          | 0200DY A02                  | [2499c633a5](https://linux-hardware.org/?probe=2499c633a5) | Apr 27, 2023 |
| Gigabyte      | H61MA-D3V                   | [3a1d89d5a0](https://linux-hardware.org/?probe=3a1d89d5a0) | Apr 27, 2023 |
| ASUSTek       | ROG STRIX B760-I GAMING ... | [6dec479f55](https://linux-hardware.org/?probe=6dec479f55) | Apr 25, 2023 |
| ASUSTek       | Z170I PRO GAMING            | [a2875a31b2](https://linux-hardware.org/?probe=a2875a31b2) | Apr 25, 2023 |
| Biostar       | B450MX-S                    | [5ac7debff3](https://linux-hardware.org/?probe=5ac7debff3) | Apr 25, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [25ac3a297e](https://linux-hardware.org/?probe=25ac3a297e) | Apr 24, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [0e85243397](https://linux-hardware.org/?probe=0e85243397) | Apr 23, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [e5c6fc2738](https://linux-hardware.org/?probe=e5c6fc2738) | Apr 23, 2023 |
| HUAWEI        | PUM-WDX9-PCB-B1 M1060       | [2c8835f2e2](https://linux-hardware.org/?probe=2c8835f2e2) | Apr 22, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [519c11a569](https://linux-hardware.org/?probe=519c11a569) | Apr 21, 2023 |
| MSI           | B450-A PRO MAX              | [51ef82c2fd](https://linux-hardware.org/?probe=51ef82c2fd) | Apr 21, 2023 |
| Dell          | 0WN7Y6 A01                  | [cc1233b9b9](https://linux-hardware.org/?probe=cc1233b9b9) | Apr 21, 2023 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | [15cc4335c7](https://linux-hardware.org/?probe=15cc4335c7) | Apr 21, 2023 |
| Gigabyte      | A320M-H-CF                  | [b0b94f2462](https://linux-hardware.org/?probe=b0b94f2462) | Apr 21, 2023 |
| Gigabyte      | A320M-H-CF                  | [d429a2c865](https://linux-hardware.org/?probe=d429a2c865) | Apr 21, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [5a9a6c553f](https://linux-hardware.org/?probe=5a9a6c553f) | Apr 20, 2023 |
| ASRock        | FM2A68M-DG3+                | [f8519c5a20](https://linux-hardware.org/?probe=f8519c5a20) | Apr 20, 2023 |
| Gigabyte      | B550 GAMING X               | [a815ec2fa2](https://linux-hardware.org/?probe=a815ec2fa2) | Apr 19, 2023 |
| ASRock        | FM2A68M-DG3+                | [701110cf4e](https://linux-hardware.org/?probe=701110cf4e) | Apr 19, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [023e96a6fd](https://linux-hardware.org/?probe=023e96a6fd) | Apr 18, 2023 |
| Dell          | 0200DY A02                  | [6041b126fa](https://linux-hardware.org/?probe=6041b126fa) | Apr 18, 2023 |
| ASRock        | 970 Pro3 R2.0               | [e816e4de38](https://linux-hardware.org/?probe=e816e4de38) | Apr 18, 2023 |
| ASRock        | Z790 Taichi                 | [0d25cf28bc](https://linux-hardware.org/?probe=0d25cf28bc) | Apr 17, 2023 |
| MSI           | MS-B0A41                    | [5950f6e73c](https://linux-hardware.org/?probe=5950f6e73c) | Apr 17, 2023 |
| ASUSTek       | X99-PRO/USB                 | [058029e9f7](https://linux-hardware.org/?probe=058029e9f7) | Apr 17, 2023 |
| Dell          | 0P01GV A03                  | [ed2675881e](https://linux-hardware.org/?probe=ed2675881e) | Apr 17, 2023 |
| ASUSTek       | Z170I PRO GAMING            | [286c8ef93c](https://linux-hardware.org/?probe=286c8ef93c) | Apr 16, 2023 |
| HP            | 158A                        | [56694ce9a3](https://linux-hardware.org/?probe=56694ce9a3) | Apr 16, 2023 |
| ASUSTek       | PRIME Z490-A                | [3924bb4eb5](https://linux-hardware.org/?probe=3924bb4eb5) | Apr 16, 2023 |
| ASUSTek       | PRIME A320M-K               | [2eb96e4d6e](https://linux-hardware.org/?probe=2eb96e4d6e) | Apr 16, 2023 |
| ASUSTek       | PRIME A320M-K               | [7d34909c86](https://linux-hardware.org/?probe=7d34909c86) | Apr 16, 2023 |
| HP            | 802E                        | [d6a1c8ad74](https://linux-hardware.org/?probe=d6a1c8ad74) | Apr 15, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [3a6ad12afa](https://linux-hardware.org/?probe=3a6ad12afa) | Apr 15, 2023 |
| ASUSTek       | GR6                         | [9cccf46449](https://linux-hardware.org/?probe=9cccf46449) | Apr 15, 2023 |
| MSI           | Z97 GAMING 5                | [988cd72346](https://linux-hardware.org/?probe=988cd72346) | Apr 15, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [8aa8fd23c6](https://linux-hardware.org/?probe=8aa8fd23c6) | Apr 15, 2023 |
| MSI           | X399 GAMING PRO CARBON A... | [c99626b458](https://linux-hardware.org/?probe=c99626b458) | Apr 14, 2023 |
| MSI           | B85-G43                     | [0363360efa](https://linux-hardware.org/?probe=0363360efa) | Apr 14, 2023 |
| Gigabyte      | F2A68HM-S1                  | [b5ce8ee6ec](https://linux-hardware.org/?probe=b5ce8ee6ec) | Apr 13, 2023 |
| ASUSTek       | PRIME A320M-K               | [bbc081e43e](https://linux-hardware.org/?probe=bbc081e43e) | Apr 13, 2023 |
| ASUSTek       | PRIME A320M-K               | [a59a28162e](https://linux-hardware.org/?probe=a59a28162e) | Apr 13, 2023 |
| Intel         | H61 V1.1                    | [1b97e4ffc5](https://linux-hardware.org/?probe=1b97e4ffc5) | Apr 12, 2023 |
| Intel         | H61 V1.1                    | [402a94b1c0](https://linux-hardware.org/?probe=402a94b1c0) | Apr 12, 2023 |
| Gigabyte      | X570S UD                    | [2d599510b8](https://linux-hardware.org/?probe=2d599510b8) | Apr 12, 2023 |
| Daten Tecn... | DH110MXV                    | [6a1c34f539](https://linux-hardware.org/?probe=6a1c34f539) | Apr 12, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1429799ca6](https://linux-hardware.org/?probe=1429799ca6) | Apr 11, 2023 |
| HP            | 1495                        | [762886dcb0](https://linux-hardware.org/?probe=762886dcb0) | Apr 11, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [8b8b7e1e4e](https://linux-hardware.org/?probe=8b8b7e1e4e) | Apr 11, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [192ca29359](https://linux-hardware.org/?probe=192ca29359) | Apr 11, 2023 |
| Dell          | 0K240Y A01                  | [1daf1b0ff6](https://linux-hardware.org/?probe=1daf1b0ff6) | Apr 10, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [1dad85ccf1](https://linux-hardware.org/?probe=1dad85ccf1) | Apr 10, 2023 |
| Intel         | H61 V1.1                    | [1c3cfd94a3](https://linux-hardware.org/?probe=1c3cfd94a3) | Apr 09, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [6aae769b7a](https://linux-hardware.org/?probe=6aae769b7a) | Apr 09, 2023 |
| Intel         | H61 V1.1                    | [e553db41a3](https://linux-hardware.org/?probe=e553db41a3) | Apr 08, 2023 |
| Huanan        | X99-F8                      | [4b020d6c5a](https://linux-hardware.org/?probe=4b020d6c5a) | Apr 08, 2023 |
| Gigabyte      | B450M DS3H-CF               | [15c7f69a52](https://linux-hardware.org/?probe=15c7f69a52) | Apr 07, 2023 |
| ASUSTek       | Z170M-PLUS                  | [be741560b8](https://linux-hardware.org/?probe=be741560b8) | Apr 06, 2023 |
| HP            | 21D0                        | [be69723341](https://linux-hardware.org/?probe=be69723341) | Apr 06, 2023 |
| ASUSTek       | PRIME Z490M-PLUS            | [1190aa9be8](https://linux-hardware.org/?probe=1190aa9be8) | Apr 06, 2023 |
| HP            | 84FD                        | [7e80c3baf0](https://linux-hardware.org/?probe=7e80c3baf0) | Apr 05, 2023 |
| Gigabyte      | H61MA-D3V                   | [ba4ee67415](https://linux-hardware.org/?probe=ba4ee67415) | Apr 05, 2023 |
| ASUSTek       | X99-A II                    | [882dc981fb](https://linux-hardware.org/?probe=882dc981fb) | Apr 04, 2023 |
| Foxconn       | 2ADA                        | [0d1d784767](https://linux-hardware.org/?probe=0d1d784767) | Apr 04, 2023 |
| Dell          | 042P49 A02                  | [74a232499a](https://linux-hardware.org/?probe=74a232499a) | Apr 04, 2023 |
| MSI           | H81M-E34                    | [5e24c6a44a](https://linux-hardware.org/?probe=5e24c6a44a) | Apr 03, 2023 |
| MSI           | B450-A PRO                  | [c487bcedab](https://linux-hardware.org/?probe=c487bcedab) | Apr 03, 2023 |
| ASRock        | B550M Pro4                  | [161e53a104](https://linux-hardware.org/?probe=161e53a104) | Apr 03, 2023 |
| MSI           | GF615M-P33                  | [022324033e](https://linux-hardware.org/?probe=022324033e) | Apr 02, 2023 |
| ASRock        | B550M Pro4                  | [9ccae5a498](https://linux-hardware.org/?probe=9ccae5a498) | Apr 02, 2023 |
| ASUSTek       | M5A97 R2.0                  | [fe4d7e3bd0](https://linux-hardware.org/?probe=fe4d7e3bd0) | Apr 02, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [bb490db4a9](https://linux-hardware.org/?probe=bb490db4a9) | Apr 02, 2023 |
| ASRock        | B550 Taichi                 | [cff286981b](https://linux-hardware.org/?probe=cff286981b) | Apr 01, 2023 |
| ASRock        | B550 Taichi                 | [01517a396d](https://linux-hardware.org/?probe=01517a396d) | Apr 01, 2023 |
| HP            | 1495                        | [96ea87fbce](https://linux-hardware.org/?probe=96ea87fbce) | Apr 01, 2023 |
| MSI           | X570-A PRO                  | [3093c50d3d](https://linux-hardware.org/?probe=3093c50d3d) | Mar 31, 2023 |
| Intel         | H61 V1.1                    | [e670f092d7](https://linux-hardware.org/?probe=e670f092d7) | Mar 31, 2023 |
| ASRock        | H61M-HVS                    | [0672578da7](https://linux-hardware.org/?probe=0672578da7) | Mar 30, 2023 |
| Intel         | X99 V1.0                    | [13c66b0e69](https://linux-hardware.org/?probe=13c66b0e69) | Mar 30, 2023 |
| MSI           | H81M-E34                    | [ac06c6037f](https://linux-hardware.org/?probe=ac06c6037f) | Mar 30, 2023 |
| MSI           | X570-A PRO                  | [0921fd9096](https://linux-hardware.org/?probe=0921fd9096) | Mar 28, 2023 |
| ASRock        | B550 Taichi                 | [94d97c5e0c](https://linux-hardware.org/?probe=94d97c5e0c) | Mar 28, 2023 |
| Intel         | H61 V1.1                    | [497266ad29](https://linux-hardware.org/?probe=497266ad29) | Mar 28, 2023 |
| ASRock        | FM2A55M-HD+ R2.0            | [a45bc637c9](https://linux-hardware.org/?probe=a45bc637c9) | Mar 27, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [aaae412a63](https://linux-hardware.org/?probe=aaae412a63) | Mar 26, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [9e318501f5](https://linux-hardware.org/?probe=9e318501f5) | Mar 25, 2023 |
| Lenovo        | 30D2 NOK                    | [dc62baadff](https://linux-hardware.org/?probe=dc62baadff) | Mar 25, 2023 |
| MSI           | GF615M-P33                  | [51276a5f00](https://linux-hardware.org/?probe=51276a5f00) | Mar 25, 2023 |
| Intel         | H61 V1.1                    | [e678dd580c](https://linux-hardware.org/?probe=e678dd580c) | Mar 25, 2023 |
| Dell          | 08NPPY A00                  | [38079fceb0](https://linux-hardware.org/?probe=38079fceb0) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [4731c6e59f](https://linux-hardware.org/?probe=4731c6e59f) | Mar 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [127173d60b](https://linux-hardware.org/?probe=127173d60b) | Mar 23, 2023 |
| Intel         | H61 V1.1                    | [f1292785cd](https://linux-hardware.org/?probe=f1292785cd) | Mar 23, 2023 |
| Dell          | 0X9M3X A01                  | [38f83864e4](https://linux-hardware.org/?probe=38f83864e4) | Mar 22, 2023 |
| OEM           | H110 Ver:2.21               | [4b80817d4b](https://linux-hardware.org/?probe=4b80817d4b) | Mar 22, 2023 |
| OEM           | H110 Ver:2.21               | [9c01b0ee80](https://linux-hardware.org/?probe=9c01b0ee80) | Mar 22, 2023 |
| Lenovo        | Dory CRB                    | [821914dc88](https://linux-hardware.org/?probe=821914dc88) | Mar 22, 2023 |
| ASUSTek       | Z170M-PLUS                  | [a1e76aa5c1](https://linux-hardware.org/?probe=a1e76aa5c1) | Mar 21, 2023 |
| MSI           | PRO B660M-A WIFI            | [2184cf01f3](https://linux-hardware.org/?probe=2184cf01f3) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [cd12accab0](https://linux-hardware.org/?probe=cd12accab0) | Mar 21, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [5eee23b1db](https://linux-hardware.org/?probe=5eee23b1db) | Mar 20, 2023 |
| ASUSTek       | PRIME Z370-P II             | [3b81f87409](https://linux-hardware.org/?probe=3b81f87409) | Mar 20, 2023 |
| ASRock        | X570 Taichi                 | [a6fa212cf2](https://linux-hardware.org/?probe=a6fa212cf2) | Mar 19, 2023 |
| ASRock        | B360M Pro4                  | [e5be65dd5e](https://linux-hardware.org/?probe=e5be65dd5e) | Mar 19, 2023 |
| HP            | 8056                        | [fa7f589aea](https://linux-hardware.org/?probe=fa7f589aea) | Mar 19, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [add9634ad5](https://linux-hardware.org/?probe=add9634ad5) | Mar 19, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [e2cfab15ef](https://linux-hardware.org/?probe=e2cfab15ef) | Mar 19, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [75dd9244fb](https://linux-hardware.org/?probe=75dd9244fb) | Mar 18, 2023 |
| Gigabyte      | GA-970A-DS3                 | [8a94a38026](https://linux-hardware.org/?probe=8a94a38026) | Mar 18, 2023 |
| Gigabyte      | GA-970A-DS3                 | [31851c4e15](https://linux-hardware.org/?probe=31851c4e15) | Mar 18, 2023 |
| HP            | 1495                        | [d83e879ba0](https://linux-hardware.org/?probe=d83e879ba0) | Mar 18, 2023 |
| HP            | 1495                        | [b7b5d46ce0](https://linux-hardware.org/?probe=b7b5d46ce0) | Mar 18, 2023 |
| Dell          | 0GY6Y8 A01                  | [3b10072541](https://linux-hardware.org/?probe=3b10072541) | Mar 18, 2023 |
| HP            | 2B36                        | [85c11ec746](https://linux-hardware.org/?probe=85c11ec746) | Mar 17, 2023 |
| ASUSTek       | PRIME B450M-A               | [fbf7dd9d94](https://linux-hardware.org/?probe=fbf7dd9d94) | Mar 17, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [e41f82bcfd](https://linux-hardware.org/?probe=e41f82bcfd) | Mar 16, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [d6def0b0aa](https://linux-hardware.org/?probe=d6def0b0aa) | Mar 16, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [abe67692b9](https://linux-hardware.org/?probe=abe67692b9) | Mar 16, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [1a4e62a4a5](https://linux-hardware.org/?probe=1a4e62a4a5) | Mar 16, 2023 |
| Dell          | 0WR7PY A01                  | [b34a55307e](https://linux-hardware.org/?probe=b34a55307e) | Mar 16, 2023 |
| Intel         | H61 V1.1                    | [175eb36378](https://linux-hardware.org/?probe=175eb36378) | Mar 16, 2023 |
| Dell          | 0WR7PY A01                  | [73a4a38e57](https://linux-hardware.org/?probe=73a4a38e57) | Mar 15, 2023 |
| Intel         | H61 V1.1                    | [eaa24cb538](https://linux-hardware.org/?probe=eaa24cb538) | Mar 15, 2023 |
| MSI           | X570-A PRO                  | [c4be4f7d67](https://linux-hardware.org/?probe=c4be4f7d67) | Mar 14, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [39ded01df5](https://linux-hardware.org/?probe=39ded01df5) | Mar 14, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [529e83761c](https://linux-hardware.org/?probe=529e83761c) | Mar 14, 2023 |
| ASRock        | Z270 Gaming K6              | [3afad06d79](https://linux-hardware.org/?probe=3afad06d79) | Mar 14, 2023 |
| Gigabyte      | P55M-UD2                    | [74cdc2f679](https://linux-hardware.org/?probe=74cdc2f679) | Mar 14, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [e1fc53bd25](https://linux-hardware.org/?probe=e1fc53bd25) | Mar 13, 2023 |
| ASUSTek       | B85M-G                      | [22ae0716b2](https://linux-hardware.org/?probe=22ae0716b2) | Mar 13, 2023 |
| Biostar       | A960D+V3                    | [e18f6a3a84](https://linux-hardware.org/?probe=e18f6a3a84) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [abb73d2e5f](https://linux-hardware.org/?probe=abb73d2e5f) | Mar 13, 2023 |
| ASUSTek       | P5Q PRO TURBO               | [44fc80c7d5](https://linux-hardware.org/?probe=44fc80c7d5) | Mar 13, 2023 |
| Huanan        | X99-F8                      | [2bd21ce3b3](https://linux-hardware.org/?probe=2bd21ce3b3) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [8f1fe0703b](https://linux-hardware.org/?probe=8f1fe0703b) | Mar 12, 2023 |
| ASUSTek       | PRIME B450M-K               | [d5a4dbf55c](https://linux-hardware.org/?probe=d5a4dbf55c) | Mar 12, 2023 |
| EVGA          | X570 FTW WIFI.0             | [ebb7252eb5](https://linux-hardware.org/?probe=ebb7252eb5) | Mar 12, 2023 |
| EVGA          | X570 FTW WIFI.0             | [74001bfcc3](https://linux-hardware.org/?probe=74001bfcc3) | Mar 12, 2023 |
| ASUSTek       | X99-PRO/USB                 | [f4d8b766a9](https://linux-hardware.org/?probe=f4d8b766a9) | Mar 12, 2023 |
| HP            | 212B                        | [0d3860ffc6](https://linux-hardware.org/?probe=0d3860ffc6) | Mar 11, 2023 |
| MSI           | X99A SLI PLUS               | [77566542fd](https://linux-hardware.org/?probe=77566542fd) | Mar 11, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [e7682656f1](https://linux-hardware.org/?probe=e7682656f1) | Mar 11, 2023 |
| Gigabyte      | Z370 HD3-CF                 | [b53c65e6c9](https://linux-hardware.org/?probe=b53c65e6c9) | Mar 10, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [29a2c22865](https://linux-hardware.org/?probe=29a2c22865) | Mar 09, 2023 |
| Gigabyte      | B550M DS3H                  | [dba3d6498b](https://linux-hardware.org/?probe=dba3d6498b) | Mar 09, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [add9ea7c34](https://linux-hardware.org/?probe=add9ea7c34) | Mar 09, 2023 |
| MSI           | B75MA-P45                   | [f066452d7d](https://linux-hardware.org/?probe=f066452d7d) | Mar 08, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [4cc3cc4c17](https://linux-hardware.org/?probe=4cc3cc4c17) | Mar 08, 2023 |
| Dell          | 0TTDMJ A00                  | [3d321d8069](https://linux-hardware.org/?probe=3d321d8069) | Mar 07, 2023 |
| ASRock        | H97 Pro4                    | [9ef8ff0b68](https://linux-hardware.org/?probe=9ef8ff0b68) | Mar 06, 2023 |
| ASUSTek       | PRIME A520M-E               | [be51d02a20](https://linux-hardware.org/?probe=be51d02a20) | Mar 06, 2023 |
| ASRock        | AB350 Gaming K4             | [896ea5798f](https://linux-hardware.org/?probe=896ea5798f) | Mar 06, 2023 |
| HP            | 8597                        | [17c1e6efd7](https://linux-hardware.org/?probe=17c1e6efd7) | Mar 05, 2023 |
| MSI           | B450-A PRO MAX              | [ec707b621c](https://linux-hardware.org/?probe=ec707b621c) | Mar 05, 2023 |
| MSI           | B450-A PRO MAX              | [36699f94c9](https://linux-hardware.org/?probe=36699f94c9) | Mar 05, 2023 |
| ASUSTek       | PRIME Z390-A                | [859a660d90](https://linux-hardware.org/?probe=859a660d90) | Mar 05, 2023 |
| ASUSTek       | PRIME X470-PRO              | [cb13decef3](https://linux-hardware.org/?probe=cb13decef3) | Mar 05, 2023 |
| ASUSTek       | PRIME Z390-P                | [ab48c17484](https://linux-hardware.org/?probe=ab48c17484) | Mar 04, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [ce8df757cc](https://linux-hardware.org/?probe=ce8df757cc) | Mar 04, 2023 |
| Biostar       | B450MX-S                    | [7dfed91b1f](https://linux-hardware.org/?probe=7dfed91b1f) | Mar 03, 2023 |
| HP            | 212B                        | [45dec8a39c](https://linux-hardware.org/?probe=45dec8a39c) | Mar 03, 2023 |
| Gigabyte      | B550M DS3H                  | [150a75757b](https://linux-hardware.org/?probe=150a75757b) | Mar 02, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [8bc604606b](https://linux-hardware.org/?probe=8bc604606b) | Mar 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [d209549d77](https://linux-hardware.org/?probe=d209549d77) | Mar 02, 2023 |
| ASUSTek       | PRO A320M-R WI-FI           | [2b64b38f7a](https://linux-hardware.org/?probe=2b64b38f7a) | Mar 01, 2023 |
| Dell          | 08NPPY A00                  | [66b1256bd3](https://linux-hardware.org/?probe=66b1256bd3) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [4630f9a67c](https://linux-hardware.org/?probe=4630f9a67c) | Feb 27, 2023 |
| Gigabyte      | B450M S2H                   | [4f55a08266](https://linux-hardware.org/?probe=4f55a08266) | Feb 27, 2023 |
| Kllisre       | X79 V2.72S                  | [eb7e4b521c](https://linux-hardware.org/?probe=eb7e4b521c) | Feb 26, 2023 |
| ASRock        | B450M Steel Legend          | [f80e5503fc](https://linux-hardware.org/?probe=f80e5503fc) | Feb 25, 2023 |
| MSI           | B450M PRO-M2                | [e63cbac447](https://linux-hardware.org/?probe=e63cbac447) | Feb 25, 2023 |
| MSI           | B450M PRO-M2                | [4af0524a44](https://linux-hardware.org/?probe=4af0524a44) | Feb 25, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | [e27e1cd0e8](https://linux-hardware.org/?probe=e27e1cd0e8) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [fea6031cfe](https://linux-hardware.org/?probe=fea6031cfe) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [4cf00365ff](https://linux-hardware.org/?probe=4cf00365ff) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [79aa51c612](https://linux-hardware.org/?probe=79aa51c612) | Feb 23, 2023 |
| ASRock        | H370M-ITX/ac                | [300d88af87](https://linux-hardware.org/?probe=300d88af87) | Feb 23, 2023 |
| Positivo      | POS-EIH61CE POSITIVO        | [f3bb3aa940](https://linux-hardware.org/?probe=f3bb3aa940) | Feb 23, 2023 |
| Positivo      | POS-EIH61CE POSITIVO        | [7d1b0e3db5](https://linux-hardware.org/?probe=7d1b0e3db5) | Feb 23, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [af2a414265](https://linux-hardware.org/?probe=af2a414265) | Feb 23, 2023 |
| Dell          | 0200DY A02                  | [a39eba7e6a](https://linux-hardware.org/?probe=a39eba7e6a) | Feb 22, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [64b7226700](https://linux-hardware.org/?probe=64b7226700) | Feb 21, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [c61a513a81](https://linux-hardware.org/?probe=c61a513a81) | Feb 20, 2023 |
| ASUSTek       | H81M-K                      | [cb6168e276](https://linux-hardware.org/?probe=cb6168e276) | Feb 20, 2023 |
| ASUSTek       | X99-M WS                    | [69eb540783](https://linux-hardware.org/?probe=69eb540783) | Feb 20, 2023 |
| ASRock        | X570 Taichi Razer Editio... | [3f44c52c3e](https://linux-hardware.org/?probe=3f44c52c3e) | Feb 20, 2023 |
| ASUSTek       | PRIME X370-PRO              | [35d0544ea5](https://linux-hardware.org/?probe=35d0544ea5) | Feb 19, 2023 |
| ASUSTek       | BT6130                      | [470ceee356](https://linux-hardware.org/?probe=470ceee356) | Feb 19, 2023 |
| ASUSTek       | PRIME X370-PRO              | [703cc27199](https://linux-hardware.org/?probe=703cc27199) | Feb 19, 2023 |
| MSI           | B85M-P33 V2                 | [b78aee1c5a](https://linux-hardware.org/?probe=b78aee1c5a) | Feb 19, 2023 |
| ASUSTek       | X99-PRO/USB                 | [45631ae666](https://linux-hardware.org/?probe=45631ae666) | Feb 18, 2023 |
| Dell          | 0X9M3X A04                  | [9b13a670c5](https://linux-hardware.org/?probe=9b13a670c5) | Feb 18, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [ab3e07326a](https://linux-hardware.org/?probe=ab3e07326a) | Feb 18, 2023 |
| ASRock        | B450 Pro4                   | [d6b212b427](https://linux-hardware.org/?probe=d6b212b427) | Feb 18, 2023 |
| ASUSTek       | PRIME Z270-K                | [5ecce23878](https://linux-hardware.org/?probe=5ecce23878) | Feb 18, 2023 |
| MSI           | B450-A PRO MAX              | [13485dcee3](https://linux-hardware.org/?probe=13485dcee3) | Feb 18, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [06d9c4427a](https://linux-hardware.org/?probe=06d9c4427a) | Feb 18, 2023 |
| Intel         | H61                         | [c1a0ccd450](https://linux-hardware.org/?probe=c1a0ccd450) | Feb 17, 2023 |
| MSI           | 970A-G43                    | [e02e6e5509](https://linux-hardware.org/?probe=e02e6e5509) | Feb 17, 2023 |
| HP            | 8053                        | [adbabb5537](https://linux-hardware.org/?probe=adbabb5537) | Feb 17, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [7e8c7de460](https://linux-hardware.org/?probe=7e8c7de460) | Feb 17, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [dc2acd10eb](https://linux-hardware.org/?probe=dc2acd10eb) | Feb 17, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [e01cd81ae1](https://linux-hardware.org/?probe=e01cd81ae1) | Feb 16, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [d98e6087da](https://linux-hardware.org/?probe=d98e6087da) | Feb 16, 2023 |
| ASRock        | Z77 Extreme3                | [baa2750a13](https://linux-hardware.org/?probe=baa2750a13) | Feb 16, 2023 |
| Dell          | 0W2F8G A00                  | [aa7bf98168](https://linux-hardware.org/?probe=aa7bf98168) | Feb 16, 2023 |
| ASUSTek       | P5QPL-AM                    | [a3b4daa09d](https://linux-hardware.org/?probe=a3b4daa09d) | Feb 16, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [e8dc5253a3](https://linux-hardware.org/?probe=e8dc5253a3) | Feb 15, 2023 |
| MSI           | Z390-A PRO                  | [713f522b92](https://linux-hardware.org/?probe=713f522b92) | Feb 14, 2023 |
| Acer          | H410H6-M17 P21-A1           | [beaef7f0ab](https://linux-hardware.org/?probe=beaef7f0ab) | Feb 14, 2023 |
| ASUSTek       | PRIME B560-PLUS             | [348fef3dbb](https://linux-hardware.org/?probe=348fef3dbb) | Feb 13, 2023 |
| Shuttle       | FX79R                       | [b1631ebb53](https://linux-hardware.org/?probe=b1631ebb53) | Feb 13, 2023 |
| ASUSTek       | PRIME H510M-A               | [8583704242](https://linux-hardware.org/?probe=8583704242) | Feb 13, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [88b290f249](https://linux-hardware.org/?probe=88b290f249) | Feb 13, 2023 |
| ASRock        | B460 Phantom Gaming 4       | [785e6e2876](https://linux-hardware.org/?probe=785e6e2876) | Feb 12, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [35781b31c5](https://linux-hardware.org/?probe=35781b31c5) | Feb 12, 2023 |
| HP            | 3397                        | [b22590d882](https://linux-hardware.org/?probe=b22590d882) | Feb 11, 2023 |
| ASRock        | B460M-HDV                   | [cb5573dd52](https://linux-hardware.org/?probe=cb5573dd52) | Feb 11, 2023 |
| Dell          | 0T568R A00                  | [fedf0db748](https://linux-hardware.org/?probe=fedf0db748) | Feb 10, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [e6bcd546ae](https://linux-hardware.org/?probe=e6bcd546ae) | Feb 10, 2023 |
| ASRock        | B450M Steel Legend          | [2a39868a05](https://linux-hardware.org/?probe=2a39868a05) | Feb 10, 2023 |
| ASRock        | Z77 Extreme3                | [0efa8164b3](https://linux-hardware.org/?probe=0efa8164b3) | Feb 10, 2023 |
| Gigabyte      | Z690 AORUS PRO              | [7a116a53c6](https://linux-hardware.org/?probe=7a116a53c6) | Feb 09, 2023 |
| Gigabyte      | Z87N-WIFI                   | [530627f086](https://linux-hardware.org/?probe=530627f086) | Feb 09, 2023 |
| ASUSTek       | B85M-G                      | [7f27fb0a83](https://linux-hardware.org/?probe=7f27fb0a83) | Feb 09, 2023 |
| MSI           | X570-A PRO                  | [9decf03532](https://linux-hardware.org/?probe=9decf03532) | Feb 09, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [157c2ef73f](https://linux-hardware.org/?probe=157c2ef73f) | Feb 09, 2023 |
| ASUSTek       | X99-PRO/USB                 | [29e3ebe102](https://linux-hardware.org/?probe=29e3ebe102) | Feb 09, 2023 |
| ASRock        | B460M-HDV                   | [dd0daa720e](https://linux-hardware.org/?probe=dd0daa720e) | Feb 08, 2023 |
| ASRock        | B460M-HDV                   | [4684c0511e](https://linux-hardware.org/?probe=4684c0511e) | Feb 08, 2023 |
| ASUSTek       | X99-PRO/USB                 | [d1f6f6da3a](https://linux-hardware.org/?probe=d1f6f6da3a) | Feb 08, 2023 |
| ASRock        | B450 Gaming K4              | [dd8fbe3d62](https://linux-hardware.org/?probe=dd8fbe3d62) | Feb 08, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [9d81046c8b](https://linux-hardware.org/?probe=9d81046c8b) | Feb 07, 2023 |
| Dell          | 0W2F8G A00                  | [b0694cfc5c](https://linux-hardware.org/?probe=b0694cfc5c) | Feb 06, 2023 |
| HP            | 3397                        | [a8f8381e48](https://linux-hardware.org/?probe=a8f8381e48) | Feb 05, 2023 |
| HP            | 3397                        | [c41ab8c19e](https://linux-hardware.org/?probe=c41ab8c19e) | Feb 05, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [add74ba4b4](https://linux-hardware.org/?probe=add74ba4b4) | Feb 05, 2023 |
| Shenzhen M... | F7BFC                       | [4d3066b96e](https://linux-hardware.org/?probe=4d3066b96e) | Feb 05, 2023 |
| Acer          | Aspire TC-885 V:1.1         | [898b87361c](https://linux-hardware.org/?probe=898b87361c) | Feb 05, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [66a494b2ec](https://linux-hardware.org/?probe=66a494b2ec) | Feb 04, 2023 |
| MSI           | MEG Z390 ACE                | [0528b7476a](https://linux-hardware.org/?probe=0528b7476a) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [3f0bf3e580](https://linux-hardware.org/?probe=3f0bf3e580) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [1998f6f225](https://linux-hardware.org/?probe=1998f6f225) | Feb 04, 2023 |
| Intel         | H61                         | [4189171d59](https://linux-hardware.org/?probe=4189171d59) | Feb 03, 2023 |
| ASUSTek       | P5G41T-M LX                 | [62882a0c3e](https://linux-hardware.org/?probe=62882a0c3e) | Feb 03, 2023 |
| ASUSTek       | PRIME B450M-A               | [19b6a074e8](https://linux-hardware.org/?probe=19b6a074e8) | Feb 03, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | [9b2f47d039](https://linux-hardware.org/?probe=9b2f47d039) | Feb 02, 2023 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4    | [115de2faed](https://linux-hardware.org/?probe=115de2faed) | Feb 01, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [4e438c4768](https://linux-hardware.org/?probe=4e438c4768) | Jan 31, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [66459fc07c](https://linux-hardware.org/?probe=66459fc07c) | Jan 31, 2023 |
| Gigabyte      | 945GCM-S2C                  | [41ad246a0b](https://linux-hardware.org/?probe=41ad246a0b) | Jan 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [f2a2476d45](https://linux-hardware.org/?probe=f2a2476d45) | Jan 31, 2023 |
| Gigabyte      | Z390 DESIGNARE-CF           | [02c8ae01d1](https://linux-hardware.org/?probe=02c8ae01d1) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [070a09add8](https://linux-hardware.org/?probe=070a09add8) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [8cca3cb036](https://linux-hardware.org/?probe=8cca3cb036) | Jan 30, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [02580dd501](https://linux-hardware.org/?probe=02580dd501) | Jan 30, 2023 |
| ASUSTek       | P5Q PRO TURBO               | [72e0a3fde5](https://linux-hardware.org/?probe=72e0a3fde5) | Jan 28, 2023 |
| ASUSTek       | P5Q PRO TURBO               | [a1cb8edb5a](https://linux-hardware.org/?probe=a1cb8edb5a) | Jan 28, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [8b5c80cad4](https://linux-hardware.org/?probe=8b5c80cad4) | Jan 28, 2023 |
| ASRock        | Z97 Killer                  | [2658d00cd2](https://linux-hardware.org/?probe=2658d00cd2) | Jan 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [31bda5eb31](https://linux-hardware.org/?probe=31bda5eb31) | Jan 28, 2023 |
| ASRock        | Z97 Killer                  | [d4c609c373](https://linux-hardware.org/?probe=d4c609c373) | Jan 27, 2023 |
| ASUSTek       | PRIME B450M-A               | [4a33dd0b76](https://linux-hardware.org/?probe=4a33dd0b76) | Jan 27, 2023 |
| ASRock        | X570 Taichi                 | [bdfb4aecf9](https://linux-hardware.org/?probe=bdfb4aecf9) | Jan 27, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | [65e298b3ee](https://linux-hardware.org/?probe=65e298b3ee) | Jan 27, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [5269e78083](https://linux-hardware.org/?probe=5269e78083) | Jan 26, 2023 |
| Lenovo        | NO DPK                      | [b1e29a464f](https://linux-hardware.org/?probe=b1e29a464f) | Jan 26, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | [5c55d923ff](https://linux-hardware.org/?probe=5c55d923ff) | Jan 26, 2023 |
| Intel         | DG965SS AAD41678-306        | [fde41db330](https://linux-hardware.org/?probe=fde41db330) | Jan 26, 2023 |
| ASUSTek       | PRIME B560M-A               | [78a1bfaac7](https://linux-hardware.org/?probe=78a1bfaac7) | Jan 25, 2023 |
| Gigabyte      | B550 AORUS ELITE AX         | [026efbc485](https://linux-hardware.org/?probe=026efbc485) | Jan 25, 2023 |
| Gigabyte      | B550 AORUS ELITE AX         | [184de230c5](https://linux-hardware.org/?probe=184de230c5) | Jan 25, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [996a0567b6](https://linux-hardware.org/?probe=996a0567b6) | Jan 23, 2023 |
| ASUSTek       | PRIME X570-PRO              | [b67d126993](https://linux-hardware.org/?probe=b67d126993) | Jan 23, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [7f1bb5c3c3](https://linux-hardware.org/?probe=7f1bb5c3c3) | Jan 23, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [f74d2ca84b](https://linux-hardware.org/?probe=f74d2ca84b) | Jan 23, 2023 |
| ASUSTek       | A68HM-PLUS                  | [3afbe94c21](https://linux-hardware.org/?probe=3afbe94c21) | Jan 23, 2023 |
| Gigabyte      | GA-970A-UD3                 | [a8d203f94b](https://linux-hardware.org/?probe=a8d203f94b) | Jan 23, 2023 |
| ASUSTek       | PRIME B450M-K               | [8a68388e16](https://linux-hardware.org/?probe=8a68388e16) | Jan 22, 2023 |
| Dell          | 0D28YY A00                  | [394be1956b](https://linux-hardware.org/?probe=394be1956b) | Jan 22, 2023 |
| ASUSTek       | Z97-K                       | [1261e08a8a](https://linux-hardware.org/?probe=1261e08a8a) | Jan 22, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [d1e0b2e009](https://linux-hardware.org/?probe=d1e0b2e009) | Jan 22, 2023 |
| Gigabyte      | Z97X-Gaming 7               | [a51b58dfbb](https://linux-hardware.org/?probe=a51b58dfbb) | Jan 22, 2023 |
| Shenzhen M... | F6BFC                       | [21f62b0eac](https://linux-hardware.org/?probe=21f62b0eac) | Jan 21, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [be39389c7f](https://linux-hardware.org/?probe=be39389c7f) | Jan 21, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [0d8275b0de](https://linux-hardware.org/?probe=0d8275b0de) | Jan 21, 2023 |
| Gigabyte      | Z87N-WIFI                   | [d77592ccf0](https://linux-hardware.org/?probe=d77592ccf0) | Jan 20, 2023 |
| ASUSTek       | M5A97 R2.0                  | [19eabab270](https://linux-hardware.org/?probe=19eabab270) | Jan 19, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [d0a387f425](https://linux-hardware.org/?probe=d0a387f425) | Jan 18, 2023 |
| Gigabyte      | H77-D3H                     | [15da5de3ae](https://linux-hardware.org/?probe=15da5de3ae) | Jan 18, 2023 |
| MSI           | H81I                        | [f51db4589d](https://linux-hardware.org/?probe=f51db4589d) | Jan 18, 2023 |
| Gigabyte      | 990FXA-UD3                  | [39591416ac](https://linux-hardware.org/?probe=39591416ac) | Jan 18, 2023 |
| Gigabyte      | Z87N-WIFI                   | [b796ac9a1d](https://linux-hardware.org/?probe=b796ac9a1d) | Jan 17, 2023 |
| Gigabyte      | F2A68HM-H                   | [d8d6e517e0](https://linux-hardware.org/?probe=d8d6e517e0) | Jan 17, 2023 |
| HP            | 805A                        | [0f9521809b](https://linux-hardware.org/?probe=0f9521809b) | Jan 17, 2023 |
| HP            | 805A                        | [4061c209e2](https://linux-hardware.org/?probe=4061c209e2) | Jan 17, 2023 |
| ASUSTek       | PRIME B560M-A AC            | [8cd20f181b](https://linux-hardware.org/?probe=8cd20f181b) | Jan 16, 2023 |
| Biostar       | A320MH                      | [1736406da7](https://linux-hardware.org/?probe=1736406da7) | Jan 16, 2023 |
| Intel         | X99                         | [9c0ea1f762](https://linux-hardware.org/?probe=9c0ea1f762) | Jan 16, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [02178066f5](https://linux-hardware.org/?probe=02178066f5) | Jan 16, 2023 |
| ASUSTek       | GD30CI                      | [7d1227f25f](https://linux-hardware.org/?probe=7d1227f25f) | Jan 15, 2023 |
| ASUSTek       | GD30CI                      | [2ed7e76dbe](https://linux-hardware.org/?probe=2ed7e76dbe) | Jan 15, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [ebe7fa8c2a](https://linux-hardware.org/?probe=ebe7fa8c2a) | Jan 14, 2023 |
| Dell          | 00V62H A01                  | [47aa34eddd](https://linux-hardware.org/?probe=47aa34eddd) | Jan 14, 2023 |
| Gigabyte      | B450M S2H                   | [e92f01ff78](https://linux-hardware.org/?probe=e92f01ff78) | Jan 14, 2023 |
| ASRock        | B450 Gaming K4              | [5bcda073b3](https://linux-hardware.org/?probe=5bcda073b3) | Jan 13, 2023 |
| Shuttle       | FS61                        | [9034ce313b](https://linux-hardware.org/?probe=9034ce313b) | Jan 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [4cb06b24fd](https://linux-hardware.org/?probe=4cb06b24fd) | Jan 11, 2023 |
| Gigabyte      | A320M-S2H-CF                | [d26bcd74b2](https://linux-hardware.org/?probe=d26bcd74b2) | Jan 10, 2023 |
| Gigabyte      | A320M-S2H-CF                | [faf7e2eae9](https://linux-hardware.org/?probe=faf7e2eae9) | Jan 10, 2023 |
| ASRock        | Z87M Extreme4               | [4aa4793173](https://linux-hardware.org/?probe=4aa4793173) | Jan 10, 2023 |
| ASUSTek       | PRIME Z270-A                | [b4c192526f](https://linux-hardware.org/?probe=b4c192526f) | Jan 08, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [874ab2d9a6](https://linux-hardware.org/?probe=874ab2d9a6) | Jan 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f09e26eaa3](https://linux-hardware.org/?probe=f09e26eaa3) | Jan 07, 2023 |
| Intel         | DG35EC AAE29266-205         | [29654c0c64](https://linux-hardware.org/?probe=29654c0c64) | Jan 06, 2023 |
| Gigabyte      | B450M S2H                   | [bf90b7d77d](https://linux-hardware.org/?probe=bf90b7d77d) | Jan 06, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [f188e7e419](https://linux-hardware.org/?probe=f188e7e419) | Jan 04, 2023 |
| Lenovo        | 31900058 STD or WIN         | [21cdab1361](https://linux-hardware.org/?probe=21cdab1361) | Jan 03, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [32e666defa](https://linux-hardware.org/?probe=32e666defa) | Jan 03, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [c2c723d7b2](https://linux-hardware.org/?probe=c2c723d7b2) | Jan 03, 2023 |
| ASUSTek       | PRIME B550M-K               | [395606c638](https://linux-hardware.org/?probe=395606c638) | Jan 03, 2023 |
| ASUSTek       | B85M-E/BR                   | [88f7654113](https://linux-hardware.org/?probe=88f7654113) | Jan 02, 2023 |
| Lenovo        | Dory CRB                    | [c87645ef7b](https://linux-hardware.org/?probe=c87645ef7b) | Jan 02, 2023 |
| MSI           | A520M-A PRO                 | [28a0c6dda9](https://linux-hardware.org/?probe=28a0c6dda9) | Jan 02, 2023 |
| ASRock        | B450M Pro4                  | [7b9bc5bc99](https://linux-hardware.org/?probe=7b9bc5bc99) | Jan 02, 2023 |
| Dell          | 0PU052                      | [82740aac1d](https://linux-hardware.org/?probe=82740aac1d) | Jan 02, 2023 |
| Dell          | 0PU052                      | [e40981850d](https://linux-hardware.org/?probe=e40981850d) | Jan 02, 2023 |
| Dell          | 04YP6J A02                  | [ee7f6ddcc1](https://linux-hardware.org/?probe=ee7f6ddcc1) | Jan 01, 2023 |
| ASUSTek       | M5A97 R2.0                  | [e877a9f9e3](https://linux-hardware.org/?probe=e877a9f9e3) | Jan 01, 2023 |
| AZW           | GTR V02                     | [5c08e4403a](https://linux-hardware.org/?probe=5c08e4403a) | Jan 01, 2023 |
| ASRock        | B550M Pro4                  | [ddab7428a1](https://linux-hardware.org/?probe=ddab7428a1) | Jan 01, 2023 |
| ASRock        | B550M Pro4                  | [7389925566](https://linux-hardware.org/?probe=7389925566) | Jan 01, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [7e22db9b23](https://linux-hardware.org/?probe=7e22db9b23) | Dec 31, 2022 |
| ASRock        | B550 Steel Legend           | [8705e10ac6](https://linux-hardware.org/?probe=8705e10ac6) | Dec 31, 2022 |
| ASUSTek       | PRIME X670-P WIFI           | [cecef0575d](https://linux-hardware.org/?probe=cecef0575d) | Dec 30, 2022 |
| Gigabyte      | Z87-HD3                     | [97f08bd689](https://linux-hardware.org/?probe=97f08bd689) | Dec 30, 2022 |
| Gigabyte      | H510M H                     | [24574296e5](https://linux-hardware.org/?probe=24574296e5) | Dec 29, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [7a7f335c4a](https://linux-hardware.org/?probe=7a7f335c4a) | Dec 29, 2022 |
| MSI           | X370 GAMING M7 ACK          | [60fe0d0b31](https://linux-hardware.org/?probe=60fe0d0b31) | Dec 29, 2022 |
| MSI           | PRO B660M-A DDR4            | [dbc37ff826](https://linux-hardware.org/?probe=dbc37ff826) | Dec 29, 2022 |
| Dell          | 0TTDMJ A00                  | [198e723dc2](https://linux-hardware.org/?probe=198e723dc2) | Dec 28, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [6d56c4c392](https://linux-hardware.org/?probe=6d56c4c392) | Dec 27, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | [d6a12148ec](https://linux-hardware.org/?probe=d6a12148ec) | Dec 27, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [bd232cd937](https://linux-hardware.org/?probe=bd232cd937) | Dec 27, 2022 |
| Gigabyte      | Z370 HD3-CF                 | [ac6571db76](https://linux-hardware.org/?probe=ac6571db76) | Dec 27, 2022 |
| ASRock        | Z690 Taichi                 | [4a4e2975d2](https://linux-hardware.org/?probe=4a4e2975d2) | Dec 27, 2022 |
| ASUSTek       | M5A78L-M LX3                | [a6c0667059](https://linux-hardware.org/?probe=a6c0667059) | Dec 27, 2022 |
| ASUSTek       | M5A78L-M LX3                | [ad94a727ab](https://linux-hardware.org/?probe=ad94a727ab) | Dec 27, 2022 |
| ASRock        | AB350M-HDV                  | [666ea6d820](https://linux-hardware.org/?probe=666ea6d820) | Dec 26, 2022 |
| ASUSTek       | M5A97 R2.0                  | [be1ace7f20](https://linux-hardware.org/?probe=be1ace7f20) | Dec 26, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | [82de75771e](https://linux-hardware.org/?probe=82de75771e) | Dec 25, 2022 |
| ASRock        | X670E Pro RS                | [b7a0a3d703](https://linux-hardware.org/?probe=b7a0a3d703) | Dec 24, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [e3e2773bde](https://linux-hardware.org/?probe=e3e2773bde) | Dec 24, 2022 |
| Gigabyte      | H510M H                     | [d592546f0a](https://linux-hardware.org/?probe=d592546f0a) | Dec 23, 2022 |
| Gigabyte      | H510M H                     | [52f1e32fc8](https://linux-hardware.org/?probe=52f1e32fc8) | Dec 23, 2022 |
| Dell          | 0GY6Y8 A02                  | [1044231936](https://linux-hardware.org/?probe=1044231936) | Dec 22, 2022 |
| HP            | 8053                        | [38b3012a7c](https://linux-hardware.org/?probe=38b3012a7c) | Dec 22, 2022 |
| ASRock        | X670E Taichi                | [e1b13226a4](https://linux-hardware.org/?probe=e1b13226a4) | Dec 21, 2022 |
| ASRock        | AB350 Pro4                  | [c7005e1e89](https://linux-hardware.org/?probe=c7005e1e89) | Dec 21, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [dbefd12c1c](https://linux-hardware.org/?probe=dbefd12c1c) | Dec 19, 2022 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | [9fb0357e3e](https://linux-hardware.org/?probe=9fb0357e3e) | Dec 19, 2022 |
| ASRock        | Z390 Pro4                   | [478165e478](https://linux-hardware.org/?probe=478165e478) | Dec 18, 2022 |
| Gigabyte      | B550M DS3H                  | [d868b73cfb](https://linux-hardware.org/?probe=d868b73cfb) | Dec 18, 2022 |
| Gigabyte      | B460M AORUS PRO             | [6deb38fb48](https://linux-hardware.org/?probe=6deb38fb48) | Dec 17, 2022 |
| MSI           | X370 GAMING M7 ACK          | [71dabd9e44](https://linux-hardware.org/?probe=71dabd9e44) | Dec 17, 2022 |
| MSI           | A68HM-E33                   | [0df6f80110](https://linux-hardware.org/?probe=0df6f80110) | Dec 17, 2022 |
| MSI           | X370 GAMING M7 ACK          | [3b245437e5](https://linux-hardware.org/?probe=3b245437e5) | Dec 17, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [d2dce9cbfd](https://linux-hardware.org/?probe=d2dce9cbfd) | Dec 16, 2022 |
| Gigabyte      | H510M H                     | [ccb746cd73](https://linux-hardware.org/?probe=ccb746cd73) | Dec 15, 2022 |
| ZOTAC         | ION                         | [f02f6b8382](https://linux-hardware.org/?probe=f02f6b8382) | Dec 15, 2022 |
| Dell          | 0D6H9T A02                  | [6266999282](https://linux-hardware.org/?probe=6266999282) | Dec 15, 2022 |
| Gigabyte      | B450M H                     | [c888c743e3](https://linux-hardware.org/?probe=c888c743e3) | Dec 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7d15ecff86](https://linux-hardware.org/?probe=7d15ecff86) | Dec 15, 2022 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [72175490ae](https://linux-hardware.org/?probe=72175490ae) | Dec 15, 2022 |
| MSI           | B250 GAMING M3              | [cf050915a5](https://linux-hardware.org/?probe=cf050915a5) | Dec 14, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [39d58ec9aa](https://linux-hardware.org/?probe=39d58ec9aa) | Dec 13, 2022 |
| ASUSTek       | X99-A II                    | [a6e0258bbe](https://linux-hardware.org/?probe=a6e0258bbe) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [8fd3c60681](https://linux-hardware.org/?probe=8fd3c60681) | Dec 13, 2022 |
| Intel         | Eaglelake Fab D             | [ed5c44a200](https://linux-hardware.org/?probe=ed5c44a200) | Dec 13, 2022 |
| MSI           | B450I GAMING PLUS MAX WI... | [0973466d88](https://linux-hardware.org/?probe=0973466d88) | Dec 13, 2022 |
| MSI           | B450I GAMING PLUS MAX WI... | [9d2ef8adf1](https://linux-hardware.org/?probe=9d2ef8adf1) | Dec 13, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [c5501c208c](https://linux-hardware.org/?probe=c5501c208c) | Dec 11, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [6964e348d6](https://linux-hardware.org/?probe=6964e348d6) | Dec 11, 2022 |
| ASUSTek       | X99-A II                    | [09f8da551c](https://linux-hardware.org/?probe=09f8da551c) | Dec 11, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [23be4288bb](https://linux-hardware.org/?probe=23be4288bb) | Dec 11, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [121359234c](https://linux-hardware.org/?probe=121359234c) | Dec 11, 2022 |
| ASUSTek       | PRIME X570-P                | [6b00f35a38](https://linux-hardware.org/?probe=6b00f35a38) | Dec 10, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [deab1a46db](https://linux-hardware.org/?probe=deab1a46db) | Dec 10, 2022 |
| ASUSTek       | PRIME B550M-A               | [e843a9c61d](https://linux-hardware.org/?probe=e843a9c61d) | Dec 10, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [27fdfb657e](https://linux-hardware.org/?probe=27fdfb657e) | Dec 09, 2022 |
| Gigabyte      | B550M S2H                   | [5e56097f25](https://linux-hardware.org/?probe=5e56097f25) | Dec 08, 2022 |
| MSI           | PRO B650-P WIFI             | [b74866314e](https://linux-hardware.org/?probe=b74866314e) | Dec 08, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [d6666dccec](https://linux-hardware.org/?probe=d6666dccec) | Dec 08, 2022 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | [c6895362e6](https://linux-hardware.org/?probe=c6895362e6) | Dec 07, 2022 |
| Lenovo        | ThinkStation S20 4157DT6    | [7c45cf5115](https://linux-hardware.org/?probe=7c45cf5115) | Dec 07, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [037c8e9cbc](https://linux-hardware.org/?probe=037c8e9cbc) | Dec 06, 2022 |
| Gigabyte      | F2A58M-HD2                  | [61c23e2501](https://linux-hardware.org/?probe=61c23e2501) | Dec 06, 2022 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | [689479ce87](https://linux-hardware.org/?probe=689479ce87) | Dec 06, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [f11d4ebe40](https://linux-hardware.org/?probe=f11d4ebe40) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [ddd1487d81](https://linux-hardware.org/?probe=ddd1487d81) | Dec 05, 2022 |
| HP            | 8053                        | [5fad592ef3](https://linux-hardware.org/?probe=5fad592ef3) | Dec 05, 2022 |
| Gigabyte      | B550M S2H                   | [dd012c9f92](https://linux-hardware.org/?probe=dd012c9f92) | Dec 04, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [9eb248d38e](https://linux-hardware.org/?probe=9eb248d38e) | Dec 04, 2022 |
| ASUSTek       | M5A97 R2.0                  | [b3b5eb90e5](https://linux-hardware.org/?probe=b3b5eb90e5) | Dec 03, 2022 |
| ASRock        | Z87 Extreme4                | [422dde5ae5](https://linux-hardware.org/?probe=422dde5ae5) | Dec 03, 2022 |
| MSI           | B450I GAMING PLUS AC        | [366f9ae2aa](https://linux-hardware.org/?probe=366f9ae2aa) | Dec 03, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [ec36ceb3fd](https://linux-hardware.org/?probe=ec36ceb3fd) | Dec 02, 2022 |
| MSI           | A68HM-E33                   | [4e2313d8b7](https://linux-hardware.org/?probe=4e2313d8b7) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [8cf4925f08](https://linux-hardware.org/?probe=8cf4925f08) | Dec 01, 2022 |
| ASRock        | X300M-STX                   | [97ceee65f3](https://linux-hardware.org/?probe=97ceee65f3) | Dec 01, 2022 |
| ASRock        | X300M-STX                   | [5b7f983a24](https://linux-hardware.org/?probe=5b7f983a24) | Dec 01, 2022 |
| ASRock        | X300M-STX                   | [42ddb2463e](https://linux-hardware.org/?probe=42ddb2463e) | Dec 01, 2022 |
| Gigabyte      | Z370 HD3-CF                 | [ece7618688](https://linux-hardware.org/?probe=ece7618688) | Nov 30, 2022 |
| ASRock        | B550M Pro4                  | [f48969af69](https://linux-hardware.org/?probe=f48969af69) | Nov 29, 2022 |
| Dell          | 09WH54 A00                  | [2700be5b4a](https://linux-hardware.org/?probe=2700be5b4a) | Nov 28, 2022 |
| Gigabyte      | M61PME-S2P                  | [4aa3d8ee32](https://linux-hardware.org/?probe=4aa3d8ee32) | Nov 27, 2022 |
| HP            | 3397                        | [e264b68f30](https://linux-hardware.org/?probe=e264b68f30) | Nov 27, 2022 |
| Gigabyte      | 970A-DS3P FX                | [4ded1fb943](https://linux-hardware.org/?probe=4ded1fb943) | Nov 26, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [bb0d4b34af](https://linux-hardware.org/?probe=bb0d4b34af) | Nov 26, 2022 |
| Gigabyte      | A320M-H-CF                  | [5f1188d448](https://linux-hardware.org/?probe=5f1188d448) | Nov 26, 2022 |
| ASRock        | B550M Pro4                  | [0828e5929e](https://linux-hardware.org/?probe=0828e5929e) | Nov 26, 2022 |
| Gigabyte      | A320M-H-CF                  | [771019bcc6](https://linux-hardware.org/?probe=771019bcc6) | Nov 26, 2022 |
| Gigabyte      | B550M S2H                   | [8ea3c120c6](https://linux-hardware.org/?probe=8ea3c120c6) | Nov 23, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [6cd720c62c](https://linux-hardware.org/?probe=6cd720c62c) | Nov 23, 2022 |
| MSI           | PRO Z690-A DDR4             | [fc53a66047](https://linux-hardware.org/?probe=fc53a66047) | Nov 22, 2022 |
| ASUSTek       | Maximus VI GENE             | [62b0cb4c94](https://linux-hardware.org/?probe=62b0cb4c94) | Nov 22, 2022 |
| ASUSTek       | Maximus VI GENE             | [26e7d04331](https://linux-hardware.org/?probe=26e7d04331) | Nov 22, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [a22e271ac2](https://linux-hardware.org/?probe=a22e271ac2) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [64cff39a82](https://linux-hardware.org/?probe=64cff39a82) | Nov 21, 2022 |
| ASRock        | B550M Pro4                  | [7d1d0390ba](https://linux-hardware.org/?probe=7d1d0390ba) | Nov 20, 2022 |
| MSI           | 970A-G43                    | [6c04d813ff](https://linux-hardware.org/?probe=6c04d813ff) | Nov 20, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [d40491a06a](https://linux-hardware.org/?probe=d40491a06a) | Nov 19, 2022 |
| Intel         | DH55PJ AAE93812-303         | [bebe890c96](https://linux-hardware.org/?probe=bebe890c96) | Nov 19, 2022 |
| ASUSTek       | PRIME A320M-K               | [6d02e2a960](https://linux-hardware.org/?probe=6d02e2a960) | Nov 19, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | [598f8e7c34](https://linux-hardware.org/?probe=598f8e7c34) | Nov 19, 2022 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | [c8fc039301](https://linux-hardware.org/?probe=c8fc039301) | Nov 19, 2022 |
| Lenovo        | 3717 SDK0J40700 WIN 3258... | [1ffee02fee](https://linux-hardware.org/?probe=1ffee02fee) | Nov 19, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [312da35b57](https://linux-hardware.org/?probe=312da35b57) | Nov 17, 2022 |
| ASUSTek       | Maximus VIII GENE           | [8b542ffc42](https://linux-hardware.org/?probe=8b542ffc42) | Nov 17, 2022 |
| MSI           | X79A-GD45                   | [7f7b7354b8](https://linux-hardware.org/?probe=7f7b7354b8) | Nov 17, 2022 |
| MSI           | X79A-GD45                   | [42d08e1136](https://linux-hardware.org/?probe=42d08e1136) | Nov 17, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [f5fd3e9e4b](https://linux-hardware.org/?probe=f5fd3e9e4b) | Nov 16, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [07d80f1783](https://linux-hardware.org/?probe=07d80f1783) | Nov 16, 2022 |
| Gigabyte      | GA-A75M-UD2H                | [4da8ff348a](https://linux-hardware.org/?probe=4da8ff348a) | Nov 15, 2022 |
| ASRock        | A320M-HDV R4.0              | [7764c0fea2](https://linux-hardware.org/?probe=7764c0fea2) | Nov 15, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c8c74ea1ec](https://linux-hardware.org/?probe=c8c74ea1ec) | Nov 15, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [567b81705d](https://linux-hardware.org/?probe=567b81705d) | Nov 15, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [389d8cf0e0](https://linux-hardware.org/?probe=389d8cf0e0) | Nov 15, 2022 |
| ASUSTek       | PRIME B350M-A               | [aabc2148da](https://linux-hardware.org/?probe=aabc2148da) | Nov 15, 2022 |
| MSI           | Z97A GAMING 7               | [275a1c28dd](https://linux-hardware.org/?probe=275a1c28dd) | Nov 13, 2022 |
| ASUSTek       | PRIME X470-PRO              | [370fb87faa](https://linux-hardware.org/?probe=370fb87faa) | Nov 13, 2022 |
| MSI           | B85M-P33 V2                 | [d633461307](https://linux-hardware.org/?probe=d633461307) | Nov 13, 2022 |
| ASRock        | X300M-STX                   | [6b2e935e07](https://linux-hardware.org/?probe=6b2e935e07) | Nov 12, 2022 |
| ASRock        | X300M-STX                   | [b071af765d](https://linux-hardware.org/?probe=b071af765d) | Nov 12, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [87b7416681](https://linux-hardware.org/?probe=87b7416681) | Nov 12, 2022 |
| ASUSTek       | PRIME A320M-K               | [f4ed581802](https://linux-hardware.org/?probe=f4ed581802) | Nov 11, 2022 |
| ASUSTek       | PRIME A320M-K               | [e06ab9c0b9](https://linux-hardware.org/?probe=e06ab9c0b9) | Nov 11, 2022 |
| Gigabyte      | H410M S2H V3                | [2172ca7325](https://linux-hardware.org/?probe=2172ca7325) | Nov 11, 2022 |
| MSI           | X79A-GD45                   | [cb82895374](https://linux-hardware.org/?probe=cb82895374) | Nov 11, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [8dcd548e89](https://linux-hardware.org/?probe=8dcd548e89) | Nov 10, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [e95608162f](https://linux-hardware.org/?probe=e95608162f) | Nov 10, 2022 |
| ASUSTek       | H110M-A                     | [4868cf87f5](https://linux-hardware.org/?probe=4868cf87f5) | Nov 09, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [9571026291](https://linux-hardware.org/?probe=9571026291) | Nov 08, 2022 |
| ASRock        | X300M-STX                   | [1fee3f08a9](https://linux-hardware.org/?probe=1fee3f08a9) | Nov 07, 2022 |
| MSI           | B550-A PRO                  | [6c4ff211d1](https://linux-hardware.org/?probe=6c4ff211d1) | Nov 07, 2022 |
| HP            | 844C                        | [5b8b05d13d](https://linux-hardware.org/?probe=5b8b05d13d) | Nov 07, 2022 |
| ASRock        | AB350M                      | [fae0de4ece](https://linux-hardware.org/?probe=fae0de4ece) | Nov 07, 2022 |
| Pegatron      | 2AB6                        | [c55efc41db](https://linux-hardware.org/?probe=c55efc41db) | Nov 06, 2022 |
| HP            | 828A                        | [42d15a94b0](https://linux-hardware.org/?probe=42d15a94b0) | Nov 06, 2022 |
| ASRock        | H310CM-HDV                  | [cb1cecc5e1](https://linux-hardware.org/?probe=cb1cecc5e1) | Nov 05, 2022 |
| ASUSTek       | P8H61-M LE/CSM              | [fb29e83d2d](https://linux-hardware.org/?probe=fb29e83d2d) | Nov 05, 2022 |
| ASUSTek       | P8H67                       | [0d98e4b3b3](https://linux-hardware.org/?probe=0d98e4b3b3) | Nov 05, 2022 |
| Lenovo        | 3728 SDK0J40700 WIN 3258... | [6700909ef7](https://linux-hardware.org/?probe=6700909ef7) | Nov 03, 2022 |
| ASUSTek       | M5A97 R2.0                  | [fecd8f06dd](https://linux-hardware.org/?probe=fecd8f06dd) | Nov 02, 2022 |
| HP            | 8054                        | [0f866b3605](https://linux-hardware.org/?probe=0f866b3605) | Nov 02, 2022 |
| ASUSTek       | P5K-E                       | [6b48759d1d](https://linux-hardware.org/?probe=6b48759d1d) | Nov 02, 2022 |
| MSI           | Z370 GAMING PLUS            | [527c779cfb](https://linux-hardware.org/?probe=527c779cfb) | Nov 01, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [8ce0b9271b](https://linux-hardware.org/?probe=8ce0b9271b) | Nov 01, 2022 |
| MSI           | MAG B660M MORTAR WIFI DD... | [115e9027d0](https://linux-hardware.org/?probe=115e9027d0) | Nov 01, 2022 |
| Acer          | H410H6-M17 P21-A1           | [9333be5120](https://linux-hardware.org/?probe=9333be5120) | Nov 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6e577f6de5](https://linux-hardware.org/?probe=6e577f6de5) | Nov 01, 2022 |
| HP            | 3397                        | [942cfa2a25](https://linux-hardware.org/?probe=942cfa2a25) | Oct 31, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [f497e98b58](https://linux-hardware.org/?probe=f497e98b58) | Oct 31, 2022 |
| Gigabyte      | Z77M-D3H                    | [83cd207e4e](https://linux-hardware.org/?probe=83cd207e4e) | Oct 30, 2022 |
| ASRock        | X570 Pro4                   | [d2407c253b](https://linux-hardware.org/?probe=d2407c253b) | Oct 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [7d6c392e74](https://linux-hardware.org/?probe=7d6c392e74) | Oct 29, 2022 |
| Gigabyte      | Z370 HD3-CF                 | [06cb3f01ba](https://linux-hardware.org/?probe=06cb3f01ba) | Oct 29, 2022 |
| ASUSTek       | PRIME A320M-K               | [25caeb6d9e](https://linux-hardware.org/?probe=25caeb6d9e) | Oct 29, 2022 |
| ASUSTek       | PRIME B365M-C               | [ccf9650f9a](https://linux-hardware.org/?probe=ccf9650f9a) | Oct 29, 2022 |
| Acer          | Aspire TC-885 V:1.1         | [81ccab7297](https://linux-hardware.org/?probe=81ccab7297) | Oct 29, 2022 |
| ASUSTek       | PRIME A320M-K               | [5876a2f3d6](https://linux-hardware.org/?probe=5876a2f3d6) | Oct 28, 2022 |
| ASUSTek       | P9X79-WS-SYS                | [8b10d380a5](https://linux-hardware.org/?probe=8b10d380a5) | Oct 28, 2022 |
| ASRock        | B550M Pro4                  | [b21b6b2908](https://linux-hardware.org/?probe=b21b6b2908) | Oct 27, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2227bb9824](https://linux-hardware.org/?probe=2227bb9824) | Oct 25, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [1f3561258a](https://linux-hardware.org/?probe=1f3561258a) | Oct 25, 2022 |
| Unknown       | 1.0                         | [cf3a9de207](https://linux-hardware.org/?probe=cf3a9de207) | Oct 25, 2022 |
| MSI           | H97 PC Mate                 | [1916f5c048](https://linux-hardware.org/?probe=1916f5c048) | Oct 25, 2022 |
| Acer          | Aspire MC605 v1.0           | [9544ff7787](https://linux-hardware.org/?probe=9544ff7787) | Oct 24, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [4b88876126](https://linux-hardware.org/?probe=4b88876126) | Oct 24, 2022 |
| HP            | 828A                        | [2123f2610c](https://linux-hardware.org/?probe=2123f2610c) | Oct 24, 2022 |
| MSI           | Z68MA-G45                   | [3f398756eb](https://linux-hardware.org/?probe=3f398756eb) | Oct 23, 2022 |
| MSI           | Z68MA-G45                   | [d96627943d](https://linux-hardware.org/?probe=d96627943d) | Oct 23, 2022 |
| Lenovo        | ThinkCentre A57 9851CDF     | [8910fecc7d](https://linux-hardware.org/?probe=8910fecc7d) | Oct 23, 2022 |
| Gigabyte      | Z690 AORUS PRO              | [7cb3500943](https://linux-hardware.org/?probe=7cb3500943) | Oct 22, 2022 |
| Gigabyte      | B365M DS3H                  | [d5f16dde87](https://linux-hardware.org/?probe=d5f16dde87) | Oct 22, 2022 |
| ASUSTek       | P8Z68-V GEN3                | [e1dedae10a](https://linux-hardware.org/?probe=e1dedae10a) | Oct 22, 2022 |
| ASRock        | H310CM-HDV                  | [afe54b52c9](https://linux-hardware.org/?probe=afe54b52c9) | Oct 21, 2022 |
| ASUSTek       | ROG STRIX B360-G GAMING     | [eaad7f0757](https://linux-hardware.org/?probe=eaad7f0757) | Oct 20, 2022 |
| Gigabyte      | H61M-S2V-B3                 | [9e7b79bfbb](https://linux-hardware.org/?probe=9e7b79bfbb) | Oct 20, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [7f069e1021](https://linux-hardware.org/?probe=7f069e1021) | Oct 20, 2022 |
| ASUSTek       | H110M-K                     | [a43f7f6601](https://linux-hardware.org/?probe=a43f7f6601) | Oct 19, 2022 |
| ASUSTek       | H170 PRO GAMING             | [cb86d1ba99](https://linux-hardware.org/?probe=cb86d1ba99) | Oct 18, 2022 |
| ASRock        | X670E PG Lightning          | [c3ce6dce01](https://linux-hardware.org/?probe=c3ce6dce01) | Oct 18, 2022 |
| Foxconn       | 2ABF                        | [ac2c9383c0](https://linux-hardware.org/?probe=ac2c9383c0) | Oct 18, 2022 |
| ASRock        | H310CM-HDV                  | [2426012acb](https://linux-hardware.org/?probe=2426012acb) | Oct 18, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [98024d1066](https://linux-hardware.org/?probe=98024d1066) | Oct 17, 2022 |
| MACHINIST     | X79 V2.82H                  | [5d99fbefc1](https://linux-hardware.org/?probe=5d99fbefc1) | Oct 17, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [7de3eff9df](https://linux-hardware.org/?probe=7de3eff9df) | Oct 16, 2022 |
| Gigabyte      | X399 AORUS PRO-CF           | [93e82a30ac](https://linux-hardware.org/?probe=93e82a30ac) | Oct 16, 2022 |
| Gigabyte      | X399 AORUS PRO-CF           | [eb9b7e329b](https://linux-hardware.org/?probe=eb9b7e329b) | Oct 16, 2022 |
| ASUSTek       | P8H77-V                     | [d6af5204e6](https://linux-hardware.org/?probe=d6af5204e6) | Oct 14, 2022 |
| Gigabyte      | H510M H                     | [28a0b7d55f](https://linux-hardware.org/?probe=28a0b7d55f) | Oct 14, 2022 |
| HP            | 802E                        | [6231a344aa](https://linux-hardware.org/?probe=6231a344aa) | Oct 14, 2022 |
| Dell          | 0HN7XN A01                  | [a71fb08b36](https://linux-hardware.org/?probe=a71fb08b36) | Oct 14, 2022 |
| Dell          | 0HN7XN A01                  | [abf7c780d2](https://linux-hardware.org/?probe=abf7c780d2) | Oct 13, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [f55bb836c3](https://linux-hardware.org/?probe=f55bb836c3) | Oct 13, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [8e2b577a03](https://linux-hardware.org/?probe=8e2b577a03) | Oct 13, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [dd9695948c](https://linux-hardware.org/?probe=dd9695948c) | Oct 11, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d006fa9a19](https://linux-hardware.org/?probe=d006fa9a19) | Oct 11, 2022 |
| Gigabyte      | B450M H                     | [36fc5f2c90](https://linux-hardware.org/?probe=36fc5f2c90) | Oct 10, 2022 |
| Gigabyte      | B450M H                     | [c3dc2e33df](https://linux-hardware.org/?probe=c3dc2e33df) | Oct 10, 2022 |
| HP            | 8460                        | [08601807cc](https://linux-hardware.org/?probe=08601807cc) | Oct 10, 2022 |
| HP            | 8460                        | [5be586f271](https://linux-hardware.org/?probe=5be586f271) | Oct 10, 2022 |
| ASUSTek       | P6X58-E-WS                  | [786a8ba316](https://linux-hardware.org/?probe=786a8ba316) | Oct 09, 2022 |
| Dell          | 0TTDMJ A00                  | [656b9369be](https://linux-hardware.org/?probe=656b9369be) | Oct 09, 2022 |
| ASRock        | B550M Steel Legend          | [740a5f78d8](https://linux-hardware.org/?probe=740a5f78d8) | Oct 09, 2022 |
| Gigabyte      | B450 GAMING X               | [a297c351ed](https://linux-hardware.org/?probe=a297c351ed) | Oct 09, 2022 |
| Dell          | 0NW73C A00                  | [2b0a3f91ea](https://linux-hardware.org/?probe=2b0a3f91ea) | Oct 08, 2022 |
| Dell          | 0M9KCM A01                  | [6fa93f6da5](https://linux-hardware.org/?probe=6fa93f6da5) | Oct 07, 2022 |
| Gigabyte      | P55M-UD2                    | [e9627c4c34](https://linux-hardware.org/?probe=e9627c4c34) | Oct 07, 2022 |
| Dell          | 0D24M8 A00                  | [8130af2fab](https://linux-hardware.org/?probe=8130af2fab) | Oct 06, 2022 |
| HP            | 87D6 SMVB                   | [03cf885086](https://linux-hardware.org/?probe=03cf885086) | Oct 05, 2022 |
| Gigabyte      | H510M H                     | [a4c0e2324f](https://linux-hardware.org/?probe=a4c0e2324f) | Oct 04, 2022 |
| HP            | 21D0                        | [6815e2bba2](https://linux-hardware.org/?probe=6815e2bba2) | Oct 04, 2022 |
| Dell          | 0HN7XN A00                  | [77776da6f7](https://linux-hardware.org/?probe=77776da6f7) | Oct 03, 2022 |
| Dell          | 0HN7XN A00                  | [84d4748b3e](https://linux-hardware.org/?probe=84d4748b3e) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [668ad3e30a](https://linux-hardware.org/?probe=668ad3e30a) | Oct 02, 2022 |
| ASRock        | B450 Pro4                   | [402a7995c4](https://linux-hardware.org/?probe=402a7995c4) | Oct 02, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [15a068e26b](https://linux-hardware.org/?probe=15a068e26b) | Oct 01, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3a9d882d91](https://linux-hardware.org/?probe=3a9d882d91) | Oct 01, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [dda857d7e6](https://linux-hardware.org/?probe=dda857d7e6) | Oct 01, 2022 |
| Gigabyte      | Z170X-Gaming GT             | [991ea6c93f](https://linux-hardware.org/?probe=991ea6c93f) | Oct 01, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [32a742b50d](https://linux-hardware.org/?probe=32a742b50d) | Oct 01, 2022 |
| Dell          | 07PR60 A01                  | [812cb18129](https://linux-hardware.org/?probe=812cb18129) | Sep 30, 2022 |
| Dell          | 0HN7XN A00                  | [c9126cd382](https://linux-hardware.org/?probe=c9126cd382) | Sep 30, 2022 |
| ASRock        | X399M Taichi                | [b7943d1645](https://linux-hardware.org/?probe=b7943d1645) | Sep 29, 2022 |
| Gigabyte      | Z690 GAMING X DDR4          | [b372f8126f](https://linux-hardware.org/?probe=b372f8126f) | Sep 29, 2022 |
| ASRock        | J3160DC-ITX                 | [7e1818288f](https://linux-hardware.org/?probe=7e1818288f) | Sep 29, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [c83049a0f6](https://linux-hardware.org/?probe=c83049a0f6) | Sep 29, 2022 |
| ASRock        | Z97 Pro3                    | [7b34a50df8](https://linux-hardware.org/?probe=7b34a50df8) | Sep 28, 2022 |
| ASRock        | B450 Pro4                   | [6a9066019c](https://linux-hardware.org/?probe=6a9066019c) | Sep 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [76aac25208](https://linux-hardware.org/?probe=76aac25208) | Sep 28, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [27ce89f701](https://linux-hardware.org/?probe=27ce89f701) | Sep 28, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [30507c8461](https://linux-hardware.org/?probe=30507c8461) | Sep 27, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [e5b4fe8914](https://linux-hardware.org/?probe=e5b4fe8914) | Sep 25, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [c65cbf84dc](https://linux-hardware.org/?probe=c65cbf84dc) | Sep 25, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [e47b2b85dc](https://linux-hardware.org/?probe=e47b2b85dc) | Sep 24, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [719b20fd4e](https://linux-hardware.org/?probe=719b20fd4e) | Sep 24, 2022 |
| Huanan        | X99-TF                      | [1361d73bcd](https://linux-hardware.org/?probe=1361d73bcd) | Sep 22, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [1faf714086](https://linux-hardware.org/?probe=1faf714086) | Sep 21, 2022 |
| Minix         | NEO G41V-4 Max              | [a1640603ca](https://linux-hardware.org/?probe=a1640603ca) | Sep 20, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [6c7d6ef178](https://linux-hardware.org/?probe=6c7d6ef178) | Sep 20, 2022 |
| Dell          | 040DDP A01                  | [635c6895e1](https://linux-hardware.org/?probe=635c6895e1) | Sep 20, 2022 |
| Intel         | X99 V1.0                    | [02bfe94d24](https://linux-hardware.org/?probe=02bfe94d24) | Sep 19, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [25d7dc8f0d](https://linux-hardware.org/?probe=25d7dc8f0d) | Sep 19, 2022 |
| Gigabyte      | A320M-H-CF                  | [a3e30957c7](https://linux-hardware.org/?probe=a3e30957c7) | Sep 19, 2022 |
| HP            | 212B                        | [c823e0060e](https://linux-hardware.org/?probe=c823e0060e) | Sep 19, 2022 |
| MSI           | B250M PRO-VDH               | [b0836f0c26](https://linux-hardware.org/?probe=b0836f0c26) | Sep 19, 2022 |
| ASRock        | X399 Phantom Gaming 6       | [a28b408f4a](https://linux-hardware.org/?probe=a28b408f4a) | Sep 19, 2022 |
| MSI           | B250M PRO-VDH               | [3b6b90fee6](https://linux-hardware.org/?probe=3b6b90fee6) | Sep 18, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [d11c4e27df](https://linux-hardware.org/?probe=d11c4e27df) | Sep 18, 2022 |
| Intel         | X99 V1.0                    | [735c794db9](https://linux-hardware.org/?probe=735c794db9) | Sep 17, 2022 |
| Foxconn       | 2ADA                        | [b136916fb3](https://linux-hardware.org/?probe=b136916fb3) | Sep 16, 2022 |
| BESSTAR Te... | UM700                       | [f6ccaeed5e](https://linux-hardware.org/?probe=f6ccaeed5e) | Sep 16, 2022 |
| ASRock        | B450M Pro4                  | [19a46a2f8e](https://linux-hardware.org/?probe=19a46a2f8e) | Sep 16, 2022 |
| ASUSTek       | PRIME H410M-E               | [91f1fdc978](https://linux-hardware.org/?probe=91f1fdc978) | Sep 14, 2022 |
| Exo           | H310CH5-M2                  | [9154b5149b](https://linux-hardware.org/?probe=9154b5149b) | Sep 14, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [4a436fb179](https://linux-hardware.org/?probe=4a436fb179) | Sep 14, 2022 |
| ASUSTek       | X99-DELUXE II               | [8c9013ec12](https://linux-hardware.org/?probe=8c9013ec12) | Sep 13, 2022 |
| Dell          | 04YP6J A00                  | [ef4ae2baac](https://linux-hardware.org/?probe=ef4ae2baac) | Sep 13, 2022 |
| Gigabyte      | H77M-D3H                    | [3767b84078](https://linux-hardware.org/?probe=3767b84078) | Sep 12, 2022 |
| Foxconn       | 2ADA                        | [1b43b0d291](https://linux-hardware.org/?probe=1b43b0d291) | Sep 11, 2022 |
| MSI           | B350M BAZOOKA               | [ff7d2e74a5](https://linux-hardware.org/?probe=ff7d2e74a5) | Sep 11, 2022 |
| ASRock        | J3160DC-ITX                 | [e854b82ab9](https://linux-hardware.org/?probe=e854b82ab9) | Sep 10, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6248f4732d](https://linux-hardware.org/?probe=6248f4732d) | Sep 10, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [70f5e3d77c](https://linux-hardware.org/?probe=70f5e3d77c) | Sep 08, 2022 |
| HP            | 3397                        | [0ebeef29bf](https://linux-hardware.org/?probe=0ebeef29bf) | Sep 07, 2022 |
| Intel         | Unknown                     | [2758407d23](https://linux-hardware.org/?probe=2758407d23) | Sep 07, 2022 |
| ASUSTek       | PRIME B360-PLUS             | [d35810173c](https://linux-hardware.org/?probe=d35810173c) | Sep 07, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [038f57c2d8](https://linux-hardware.org/?probe=038f57c2d8) | Sep 06, 2022 |
| MSI           | Z87-G41 PC Mate             | [775e007fc8](https://linux-hardware.org/?probe=775e007fc8) | Sep 05, 2022 |
| Intel         | B75                         | [eca0b46101](https://linux-hardware.org/?probe=eca0b46101) | Sep 05, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [43267285d4](https://linux-hardware.org/?probe=43267285d4) | Sep 04, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [518aa50eb0](https://linux-hardware.org/?probe=518aa50eb0) | Sep 04, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [4a27f8b033](https://linux-hardware.org/?probe=4a27f8b033) | Sep 04, 2022 |
| HP            | 8054                        | [878115f808](https://linux-hardware.org/?probe=878115f808) | Sep 04, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [65562b09e0](https://linux-hardware.org/?probe=65562b09e0) | Sep 03, 2022 |
| BESSTAR Te... | UM700                       | [f1198508de](https://linux-hardware.org/?probe=f1198508de) | Sep 03, 2022 |
| Dell          | 07PR60 A01                  | [d37a4374eb](https://linux-hardware.org/?probe=d37a4374eb) | Sep 02, 2022 |
| ASUSTek       | P6X58D-E                    | [cf774b3e03](https://linux-hardware.org/?probe=cf774b3e03) | Sep 02, 2022 |
| HP            | 8054                        | [1586ce33d1](https://linux-hardware.org/?probe=1586ce33d1) | Sep 02, 2022 |
| ASRock        | N68-S                       | [df5d34428a](https://linux-hardware.org/?probe=df5d34428a) | Sep 01, 2022 |
| ASUSTek       | M5A78L-M LX3                | [5ba264dfb2](https://linux-hardware.org/?probe=5ba264dfb2) | Sep 01, 2022 |
| ASUSTek       | M5A78L-M LX3                | [169c9af937](https://linux-hardware.org/?probe=169c9af937) | Sep 01, 2022 |
| Lenovo        | SHARKBAY NO DPK             | [f872d36cd5](https://linux-hardware.org/?probe=f872d36cd5) | Sep 01, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [37695eb7e5](https://linux-hardware.org/?probe=37695eb7e5) | Aug 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d816d2ade0](https://linux-hardware.org/?probe=d816d2ade0) | Aug 30, 2022 |
| ASRock        | N68-S                       | [6aabf89438](https://linux-hardware.org/?probe=6aabf89438) | Aug 30, 2022 |
| ASUSTek       | PRIME Z590-P                | [e05dcd4a08](https://linux-hardware.org/?probe=e05dcd4a08) | Aug 29, 2022 |
| ASRock        | FM2A58M-VG3+ R2.0           | [422af9d6b5](https://linux-hardware.org/?probe=422af9d6b5) | Aug 29, 2022 |
| ASRock        | N68-S                       | [4fff0a6104](https://linux-hardware.org/?probe=4fff0a6104) | Aug 29, 2022 |
| ASUSTek       | ProArt B550-CREATOR         | [ec9f8ea30e](https://linux-hardware.org/?probe=ec9f8ea30e) | Aug 28, 2022 |
| ASRock        | B550M Pro4                  | [8c6b85a46c](https://linux-hardware.org/?probe=8c6b85a46c) | Aug 27, 2022 |
| ASRock        | B450M Pro4                  | [f4fe5fd168](https://linux-hardware.org/?probe=f4fe5fd168) | Aug 27, 2022 |
| Gigabyte      | B550 GAMING X V2            | [94e2f7cedc](https://linux-hardware.org/?probe=94e2f7cedc) | Aug 27, 2022 |
| Dell          | 0KWVT8 A02                  | [3f9c00b0da](https://linux-hardware.org/?probe=3f9c00b0da) | Aug 27, 2022 |
| ASRock        | X99 WS                      | [d16d59fab2](https://linux-hardware.org/?probe=d16d59fab2) | Aug 26, 2022 |
| ASUSTek       | Z170-P                      | [0bd08aee88](https://linux-hardware.org/?probe=0bd08aee88) | Aug 24, 2022 |
| Gigabyte      | B550M S2H                   | [8b5fe2494e](https://linux-hardware.org/?probe=8b5fe2494e) | Aug 23, 2022 |
| ASUSTek       | PRIME B450M-A               | [bfdd1ab294](https://linux-hardware.org/?probe=bfdd1ab294) | Aug 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0dbe2c5dfd](https://linux-hardware.org/?probe=0dbe2c5dfd) | Aug 22, 2022 |
| MACHINIST     | H81M-PRO S1 V2.0            | [12be75fa90](https://linux-hardware.org/?probe=12be75fa90) | Aug 21, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [3b799e56c6](https://linux-hardware.org/?probe=3b799e56c6) | Aug 21, 2022 |
| MSI           | P55-GD55                    | [89f2c92fa1](https://linux-hardware.org/?probe=89f2c92fa1) | Aug 21, 2022 |
| ASUSTek       | PRIME B365M-C               | [8ae386a7a0](https://linux-hardware.org/?probe=8ae386a7a0) | Aug 20, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [1d1f39fd1b](https://linux-hardware.org/?probe=1d1f39fd1b) | Aug 19, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [d59342b7a4](https://linux-hardware.org/?probe=d59342b7a4) | Aug 19, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [e61c3cee8a](https://linux-hardware.org/?probe=e61c3cee8a) | Aug 18, 2022 |
| ASRock        | B550M Pro4                  | [41b271c4e7](https://linux-hardware.org/?probe=41b271c4e7) | Aug 17, 2022 |
| Gigabyte      | H61M-S2P                    | [49aedf1cf8](https://linux-hardware.org/?probe=49aedf1cf8) | Aug 17, 2022 |
| Gigabyte      | B550M S2H                   | [e04617befa](https://linux-hardware.org/?probe=e04617befa) | Aug 17, 2022 |
| MSI           | Z87-G41 PC Mate             | [08e79a0a1c](https://linux-hardware.org/?probe=08e79a0a1c) | Aug 16, 2022 |
| MSI           | X470 GAMING PRO             | [52b08fd4ba](https://linux-hardware.org/?probe=52b08fd4ba) | Aug 16, 2022 |
| ASRock        | Z77 Extreme4                | [07e825ed5b](https://linux-hardware.org/?probe=07e825ed5b) | Aug 16, 2022 |
| VS Company    | H61H2                       | [a0b88242a4](https://linux-hardware.org/?probe=a0b88242a4) | Aug 16, 2022 |
| Gigabyte      | B450 AORUS M                | [bdf5ba285f](https://linux-hardware.org/?probe=bdf5ba285f) | Aug 15, 2022 |
| Gigabyte      | B550M S2H                   | [db7b7b3126](https://linux-hardware.org/?probe=db7b7b3126) | Aug 15, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | [2fb0eea98c](https://linux-hardware.org/?probe=2fb0eea98c) | Aug 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [76e185a2e5](https://linux-hardware.org/?probe=76e185a2e5) | Aug 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [59b6bdadd3](https://linux-hardware.org/?probe=59b6bdadd3) | Aug 14, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [45ddbf814d](https://linux-hardware.org/?probe=45ddbf814d) | Aug 14, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e63db5769a](https://linux-hardware.org/?probe=e63db5769a) | Aug 14, 2022 |
| ASRock        | 990FX Extreme3              | [646169ae62](https://linux-hardware.org/?probe=646169ae62) | Aug 14, 2022 |
| HP            | 82A2                        | [bc3d667d42](https://linux-hardware.org/?probe=bc3d667d42) | Aug 13, 2022 |
| MSI           | B350M PRO-VD PLUS           | [ba65d9b67e](https://linux-hardware.org/?probe=ba65d9b67e) | Aug 13, 2022 |
| MSI           | 970A SLI Krait Edition      | [a94fe940b1](https://linux-hardware.org/?probe=a94fe940b1) | Aug 13, 2022 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [41560e8e13](https://linux-hardware.org/?probe=41560e8e13) | Aug 12, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [f82761570b](https://linux-hardware.org/?probe=f82761570b) | Aug 12, 2022 |
| AZW           | U59                         | [344d4587f6](https://linux-hardware.org/?probe=344d4587f6) | Aug 12, 2022 |
| ASRock        | 990FX Extreme3              | [e3006f6ca1](https://linux-hardware.org/?probe=e3006f6ca1) | Aug 11, 2022 |
| ASUSTek       | Z87-PRO                     | [f8a688c41e](https://linux-hardware.org/?probe=f8a688c41e) | Aug 11, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [3219cc3946](https://linux-hardware.org/?probe=3219cc3946) | Aug 10, 2022 |
| HP            | 8053                        | [db80dc0ee1](https://linux-hardware.org/?probe=db80dc0ee1) | Aug 10, 2022 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | [48b0dfdee0](https://linux-hardware.org/?probe=48b0dfdee0) | Aug 10, 2022 |
| Unknown       | Unknown                     | [e4c7906333](https://linux-hardware.org/?probe=e4c7906333) | Aug 09, 2022 |
| Lenovo        | Bantry CRB NOK              | [fbeb21c99a](https://linux-hardware.org/?probe=fbeb21c99a) | Aug 09, 2022 |
| ASUSTek       | G10DK                       | [2401d4af44](https://linux-hardware.org/?probe=2401d4af44) | Aug 08, 2022 |
| MSI           | MAG B550M MORTAR            | [7cf010b820](https://linux-hardware.org/?probe=7cf010b820) | Aug 08, 2022 |
| ASRock        | B450 Pro4                   | [b87492e7c7](https://linux-hardware.org/?probe=b87492e7c7) | Aug 08, 2022 |
| Gigabyte      | B150M-D3H-CF                | [5235533a87](https://linux-hardware.org/?probe=5235533a87) | Aug 07, 2022 |
| MSI           | B550-A PRO                  | [a3aa8d0879](https://linux-hardware.org/?probe=a3aa8d0879) | Aug 05, 2022 |
| Dell          | 0XR1GT A00                  | [2e069ba5c2](https://linux-hardware.org/?probe=2e069ba5c2) | Aug 04, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [e963ce265b](https://linux-hardware.org/?probe=e963ce265b) | Aug 04, 2022 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [22b43d3149](https://linux-hardware.org/?probe=22b43d3149) | Aug 04, 2022 |
| ECS           | H61H2-MV                    | [6b2a77a281](https://linux-hardware.org/?probe=6b2a77a281) | Aug 02, 2022 |
| MSI           | B450 GAMING PRO CARBON M... | [5951f66289](https://linux-hardware.org/?probe=5951f66289) | Aug 02, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [30e0a23365](https://linux-hardware.org/?probe=30e0a23365) | Aug 01, 2022 |
| ASUSTek       | F2A55-M LK2                 | [97a5e9c390](https://linux-hardware.org/?probe=97a5e9c390) | Aug 01, 2022 |
| Dell          | 0D24M8 A00                  | [6367e245e6](https://linux-hardware.org/?probe=6367e245e6) | Jul 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [9ea9e6f737](https://linux-hardware.org/?probe=9ea9e6f737) | Jul 30, 2022 |
| MSI           | X470 GAMING PRO MAX         | [5651db0a63](https://linux-hardware.org/?probe=5651db0a63) | Jul 30, 2022 |
| ASRock        | H81M-VG4                    | [1fd9e0ca3a](https://linux-hardware.org/?probe=1fd9e0ca3a) | Jul 30, 2022 |
| ASRock        | H81M-VG4                    | [309df31c47](https://linux-hardware.org/?probe=309df31c47) | Jul 30, 2022 |
| ASUSTek       | PRIME Z590-P                | [fa38197b4d](https://linux-hardware.org/?probe=fa38197b4d) | Jul 29, 2022 |
| Lenovo        | 3133 SDK0J40675 WIN 3305... | [4434d4d78a](https://linux-hardware.org/?probe=4434d4d78a) | Jul 29, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [f666b16fde](https://linux-hardware.org/?probe=f666b16fde) | Jul 28, 2022 |
| Gigabyte      | H97-Gaming 3                | [90656d8ef4](https://linux-hardware.org/?probe=90656d8ef4) | Jul 27, 2022 |
| Lenovo        | 3717 SDK0J40697 WIN 3305... | [701f519b4c](https://linux-hardware.org/?probe=701f519b4c) | Jul 27, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [b41540a078](https://linux-hardware.org/?probe=b41540a078) | Jul 26, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [331a99ef9a](https://linux-hardware.org/?probe=331a99ef9a) | Jul 26, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [1f3433b9e1](https://linux-hardware.org/?probe=1f3433b9e1) | Jul 26, 2022 |
| Gigabyte      | 990XA-UD3                   | [803bd277e7](https://linux-hardware.org/?probe=803bd277e7) | Jul 26, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [0c310749f1](https://linux-hardware.org/?probe=0c310749f1) | Jul 26, 2022 |
| Gigabyte      | H61M-D2P-B3                 | [8f0769b485](https://linux-hardware.org/?probe=8f0769b485) | Jul 25, 2022 |
| Gigabyte      | Z68P-DS3                    | [b03f1fee53](https://linux-hardware.org/?probe=b03f1fee53) | Jul 24, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [e512b2f9f2](https://linux-hardware.org/?probe=e512b2f9f2) | Jul 23, 2022 |
| Dell          | 0GM819                      | [8c617c1c3f](https://linux-hardware.org/?probe=8c617c1c3f) | Jul 23, 2022 |
| BESSTAR Te... | HM90                        | [cb4da5b649](https://linux-hardware.org/?probe=cb4da5b649) | Jul 23, 2022 |
| MSI           | B450M PRO-VDH MAX           | [9002ca2e54](https://linux-hardware.org/?probe=9002ca2e54) | Jul 23, 2022 |
| ASUSTek       | Maximus Formula             | [2e71fca3d5](https://linux-hardware.org/?probe=2e71fca3d5) | Jul 22, 2022 |
| BESSTAR Te... | HM90                        | [380230bbf6](https://linux-hardware.org/?probe=380230bbf6) | Jul 22, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [51c2b5bc3b](https://linux-hardware.org/?probe=51c2b5bc3b) | Jul 22, 2022 |
| MACHINIST     | X79 V2.82H                  | [da4a098248](https://linux-hardware.org/?probe=da4a098248) | Jul 22, 2022 |
| MACHINIST     | X79 V2.82H                  | [0e06f3fdf5](https://linux-hardware.org/?probe=0e06f3fdf5) | Jul 22, 2022 |
| ASUSTek       | P9X79                       | [5ff04691ce](https://linux-hardware.org/?probe=5ff04691ce) | Jul 21, 2022 |
| ASUSTek       | P9X79                       | [1bcee43b6e](https://linux-hardware.org/?probe=1bcee43b6e) | Jul 21, 2022 |
| ASRock        | Z77 Extreme4                | [492529f973](https://linux-hardware.org/?probe=492529f973) | Jul 21, 2022 |
| PCWare        | IPMH81G1                    | [cb66716a63](https://linux-hardware.org/?probe=cb66716a63) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [1a28383fee](https://linux-hardware.org/?probe=1a28383fee) | Jul 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [63489ff6e5](https://linux-hardware.org/?probe=63489ff6e5) | Jul 19, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [fd46c32d92](https://linux-hardware.org/?probe=fd46c32d92) | Jul 19, 2022 |
| ASUSTek       | Maximus Formula             | [3c600cafa6](https://linux-hardware.org/?probe=3c600cafa6) | Jul 17, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [b28f8248b4](https://linux-hardware.org/?probe=b28f8248b4) | Jul 17, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [84d62872f5](https://linux-hardware.org/?probe=84d62872f5) | Jul 17, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [3b1f082065](https://linux-hardware.org/?probe=3b1f082065) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [3605f29c73](https://linux-hardware.org/?probe=3605f29c73) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [533392d790](https://linux-hardware.org/?probe=533392d790) | Jul 16, 2022 |
| Gigabyte      | A520M S2H                   | [dfc64d417f](https://linux-hardware.org/?probe=dfc64d417f) | Jul 15, 2022 |
| ASUSTek       | M5A97 R2.0                  | [06992e615b](https://linux-hardware.org/?probe=06992e615b) | Jul 15, 2022 |
| BESSTAR Te... | TL50                        | [c77ff65710](https://linux-hardware.org/?probe=c77ff65710) | Jul 15, 2022 |
| ASRock        | B550M Pro4                  | [dcdc04db9f](https://linux-hardware.org/?probe=dcdc04db9f) | Jul 14, 2022 |
| Gigabyte      | Z97-D3H-CF                  | [55f956b817](https://linux-hardware.org/?probe=55f956b817) | Jul 14, 2022 |
| MSI           | A320M-A PRO MAX             | [31127e76f8](https://linux-hardware.org/?probe=31127e76f8) | Jul 14, 2022 |
| MSI           | X470 GAMING PRO             | [716dd72eeb](https://linux-hardware.org/?probe=716dd72eeb) | Jul 13, 2022 |
| ASUSTek       | Maximus Formula             | [cd81bcaf19](https://linux-hardware.org/?probe=cd81bcaf19) | Jul 13, 2022 |
| MSI           | A320M-A PRO MAX             | [ed83060c1a](https://linux-hardware.org/?probe=ed83060c1a) | Jul 13, 2022 |
| ASUSTek       | M5A97 R2.0                  | [8bdaa5b844](https://linux-hardware.org/?probe=8bdaa5b844) | Jul 13, 2022 |
| BESSTAR Te... | UM350                       | [7437e30da5](https://linux-hardware.org/?probe=7437e30da5) | Jul 11, 2022 |
| MSI           | Z77A-G45                    | [ff2bae4518](https://linux-hardware.org/?probe=ff2bae4518) | Jul 11, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [5c8deeb62c](https://linux-hardware.org/?probe=5c8deeb62c) | Jul 10, 2022 |
| MSI           | H110M PRO-VH PLUS           | [02cbc3a4ae](https://linux-hardware.org/?probe=02cbc3a4ae) | Jul 10, 2022 |
| MSI           | Z77A-G45                    | [2d4a011972](https://linux-hardware.org/?probe=2d4a011972) | Jul 10, 2022 |
| Gigabyte      | B365M DS3H                  | [8c2d8a89d0](https://linux-hardware.org/?probe=8c2d8a89d0) | Jul 10, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [5dc09a66d8](https://linux-hardware.org/?probe=5dc09a66d8) | Jul 08, 2022 |
| ASUSTek       | M5A97 R2.0                  | [b46404cc89](https://linux-hardware.org/?probe=b46404cc89) | Jul 07, 2022 |
| Dell          | 0NK5PH A00                  | [6e17948aa5](https://linux-hardware.org/?probe=6e17948aa5) | Jul 07, 2022 |
| Dell          | 0NK5PH A00                  | [56b772ade4](https://linux-hardware.org/?probe=56b772ade4) | Jul 07, 2022 |
| ASRock        | B450M Pro4 R2.0             | [d9dc513be7](https://linux-hardware.org/?probe=d9dc513be7) | Jul 06, 2022 |
| Fujitsu       | D2981-A1 S26361-D2981-A1    | [5e40d26a2b](https://linux-hardware.org/?probe=5e40d26a2b) | Jul 06, 2022 |
| Inventec      | D CLASS A02                 | [ac1652fd54](https://linux-hardware.org/?probe=ac1652fd54) | Jul 06, 2022 |
| ASUSTek       | PRIME B550M-A               | [a5e8e3a046](https://linux-hardware.org/?probe=a5e8e3a046) | Jul 05, 2022 |
| ASRock        | B550M Pro4                  | [39803eaf94](https://linux-hardware.org/?probe=39803eaf94) | Jul 04, 2022 |
| ASRock        | B550M Pro4                  | [747051c1fc](https://linux-hardware.org/?probe=747051c1fc) | Jul 04, 2022 |
| MSI           | B250M PRO-VDH               | [fb76db49bd](https://linux-hardware.org/?probe=fb76db49bd) | Jul 04, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [327086a8b8](https://linux-hardware.org/?probe=327086a8b8) | Jul 04, 2022 |
| ASRock        | IMB-1213                    | [6e1ba0ba69](https://linux-hardware.org/?probe=6e1ba0ba69) | Jul 04, 2022 |
| HP            | 0A9Ch                       | [3dafdd1a3f](https://linux-hardware.org/?probe=3dafdd1a3f) | Jul 03, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [6918411ee2](https://linux-hardware.org/?probe=6918411ee2) | Jul 03, 2022 |
| ASUSTek       | PRIME A320M-K               | [a381b573f6](https://linux-hardware.org/?probe=a381b573f6) | Jul 03, 2022 |
| ASUSTek       | PRIME X570-P                | [1a729c627d](https://linux-hardware.org/?probe=1a729c627d) | Jul 03, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [c633887935](https://linux-hardware.org/?probe=c633887935) | Jul 02, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [5763cb4576](https://linux-hardware.org/?probe=5763cb4576) | Jul 01, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [21dd020507](https://linux-hardware.org/?probe=21dd020507) | Jul 01, 2022 |
| MSI           | PRESTIGE X570 CREATION      | [7f17faf180](https://linux-hardware.org/?probe=7f17faf180) | Jun 30, 2022 |
| HP            | 0B54h D                     | [bef89f554e](https://linux-hardware.org/?probe=bef89f554e) | Jun 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | [6a2f1d22f1](https://linux-hardware.org/?probe=6a2f1d22f1) | Jun 29, 2022 |
| Gigabyte      | B450M DS3H-CF               | [0a976062da](https://linux-hardware.org/?probe=0a976062da) | Jun 29, 2022 |
| ASRock        | H61M-ITX                    | [e8d5e4ff14](https://linux-hardware.org/?probe=e8d5e4ff14) | Jun 29, 2022 |
| ASUSTek       | PRIME Z390-P                | [97613877b7](https://linux-hardware.org/?probe=97613877b7) | Jun 29, 2022 |
| Gigabyte      | B550 AORUS MASTER           | [be4dd3360f](https://linux-hardware.org/?probe=be4dd3360f) | Jun 28, 2022 |
| Gigabyte      | A520M DS3H                  | [b56fe3beb3](https://linux-hardware.org/?probe=b56fe3beb3) | Jun 28, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | [0441b2cf28](https://linux-hardware.org/?probe=0441b2cf28) | Jun 27, 2022 |
| HP            | 212B                        | [687ca162d2](https://linux-hardware.org/?probe=687ca162d2) | Jun 27, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | [ca055793c5](https://linux-hardware.org/?probe=ca055793c5) | Jun 27, 2022 |
| ASUSTek       | PRIME B450M-K               | [441cba3212](https://linux-hardware.org/?probe=441cba3212) | Jun 27, 2022 |
| Gigabyte      | H370M DS3H-CF               | [862d58f1a4](https://linux-hardware.org/?probe=862d58f1a4) | Jun 27, 2022 |
| MSI           | A320M PRO-M2 V2             | [a801c7c2ba](https://linux-hardware.org/?probe=a801c7c2ba) | Jun 27, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [da1c9472bd](https://linux-hardware.org/?probe=da1c9472bd) | Jun 27, 2022 |
| ASRock        | A320M-HDV R4.0              | [0e8993f232](https://linux-hardware.org/?probe=0e8993f232) | Jun 27, 2022 |
| ASRock        | B550M Pro4                  | [92d424a6b5](https://linux-hardware.org/?probe=92d424a6b5) | Jun 26, 2022 |
| Minix         | NEO Z83-4 V1.1              | [4fd5881226](https://linux-hardware.org/?probe=4fd5881226) | Jun 26, 2022 |
| Minix         | NEO Z83-4 V1.1              | [01e2541b47](https://linux-hardware.org/?probe=01e2541b47) | Jun 26, 2022 |
| Dell          | 088DT1 A01                  | [6b2aa6c257](https://linux-hardware.org/?probe=6b2aa6c257) | Jun 26, 2022 |
| Dell          | 088DT1 A01                  | [dae78cdc9e](https://linux-hardware.org/?probe=dae78cdc9e) | Jun 26, 2022 |
| ASRock        | Z77 Extreme4                | [b397f63621](https://linux-hardware.org/?probe=b397f63621) | Jun 26, 2022 |
| ASRock        | H61M-ITX                    | [6c9ee0dadd](https://linux-hardware.org/?probe=6c9ee0dadd) | Jun 26, 2022 |
| ASRock        | B450M Pro4 R2.0             | [f1e0998426](https://linux-hardware.org/?probe=f1e0998426) | Jun 25, 2022 |
| ASRock        | B450M Pro4 R2.0             | [abdb925c2a](https://linux-hardware.org/?probe=abdb925c2a) | Jun 24, 2022 |
| Gigabyte      | MQLP5AP-00                  | [fad6b4b320](https://linux-hardware.org/?probe=fad6b4b320) | Jun 24, 2022 |
| Gigabyte      | B450M S2H V2                | [e0e21604de](https://linux-hardware.org/?probe=e0e21604de) | Jun 24, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [4a8c282d59](https://linux-hardware.org/?probe=4a8c282d59) | Jun 24, 2022 |
| ASRock        | H510M-ITX/ac                | [f1e5f3d686](https://linux-hardware.org/?probe=f1e5f3d686) | Jun 23, 2022 |
| ECS           | H61H2-MV                    | [6035d3cf75](https://linux-hardware.org/?probe=6035d3cf75) | Jun 22, 2022 |
| Gigabyte      | 970A-DS3P                   | [43c1598008](https://linux-hardware.org/?probe=43c1598008) | Jun 22, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [0e6a585307](https://linux-hardware.org/?probe=0e6a585307) | Jun 21, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [7063b6a7ef](https://linux-hardware.org/?probe=7063b6a7ef) | Jun 21, 2022 |
| ASRock        | B550M Pro4                  | [ab46a92e42](https://linux-hardware.org/?probe=ab46a92e42) | Jun 20, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [1bd776020e](https://linux-hardware.org/?probe=1bd776020e) | Jun 20, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [75d908e7db](https://linux-hardware.org/?probe=75d908e7db) | Jun 19, 2022 |
| ASUSTek       | M5A97 R2.0                  | [df832fa379](https://linux-hardware.org/?probe=df832fa379) | Jun 18, 2022 |
| Gigabyte      | B450 AORUS M                | [8b1fb7056f](https://linux-hardware.org/?probe=8b1fb7056f) | Jun 17, 2022 |
| Gigabyte      | B450 AORUS M                | [277df992e4](https://linux-hardware.org/?probe=277df992e4) | Jun 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [530c081484](https://linux-hardware.org/?probe=530c081484) | Jun 17, 2022 |
| ASRock        | AB350M-HDV                  | [65478d1857](https://linux-hardware.org/?probe=65478d1857) | Jun 17, 2022 |
| Gigabyte      | X399 AORUS Gaming 7         | [b9de371265](https://linux-hardware.org/?probe=b9de371265) | Jun 17, 2022 |
| Gigabyte      | X399 AORUS Gaming 7         | [d987e4522e](https://linux-hardware.org/?probe=d987e4522e) | Jun 17, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [4a8163d07f](https://linux-hardware.org/?probe=4a8163d07f) | Jun 17, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [cee122d15f](https://linux-hardware.org/?probe=cee122d15f) | Jun 16, 2022 |
| AZW           | U59                         | [5a661910dc](https://linux-hardware.org/?probe=5a661910dc) | Jun 16, 2022 |
| Unknown       | Unknown                     | [87eb57392c](https://linux-hardware.org/?probe=87eb57392c) | Jun 16, 2022 |
| MSI           | B360M PRO-VD                | [fa86b2da10](https://linux-hardware.org/?probe=fa86b2da10) | Jun 15, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | [a46a8033f8](https://linux-hardware.org/?probe=a46a8033f8) | Jun 15, 2022 |
| ASRock        | B550M Pro4                  | [4dc0746a65](https://linux-hardware.org/?probe=4dc0746a65) | Jun 15, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [7587cca95a](https://linux-hardware.org/?probe=7587cca95a) | Jun 14, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [0b792ecaef](https://linux-hardware.org/?probe=0b792ecaef) | Jun 14, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [d0050d4fcd](https://linux-hardware.org/?probe=d0050d4fcd) | Jun 14, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [9dae5c70a5](https://linux-hardware.org/?probe=9dae5c70a5) | Jun 14, 2022 |
| Dell          | 0D28YY A00                  | [18487dbcb1](https://linux-hardware.org/?probe=18487dbcb1) | Jun 14, 2022 |
| ASRock        | B550M Pro4                  | [5c9ca9542b](https://linux-hardware.org/?probe=5c9ca9542b) | Jun 13, 2022 |
| HP            | 212B                        | [2680c53ca7](https://linux-hardware.org/?probe=2680c53ca7) | Jun 13, 2022 |
| ASRock        | B550M Pro4                  | [275c522503](https://linux-hardware.org/?probe=275c522503) | Jun 13, 2022 |
| Unknown       | 1.0                         | [8c8f612260](https://linux-hardware.org/?probe=8c8f612260) | Jun 13, 2022 |
| Huanan        | X99-TF V2.0                 | [cf8091c979](https://linux-hardware.org/?probe=cf8091c979) | Jun 13, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [feca5f6bb5](https://linux-hardware.org/?probe=feca5f6bb5) | Jun 12, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [1d0ca4cb7a](https://linux-hardware.org/?probe=1d0ca4cb7a) | Jun 12, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [ded6b87e98](https://linux-hardware.org/?probe=ded6b87e98) | Jun 12, 2022 |
| HP            | 0A9Ch                       | [bd8345d324](https://linux-hardware.org/?probe=bd8345d324) | Jun 12, 2022 |
| Gigabyte      | H510M H                     | [7b1a78a681](https://linux-hardware.org/?probe=7b1a78a681) | Jun 11, 2022 |
| Gigabyte      | Z68P-DS3                    | [03554389d5](https://linux-hardware.org/?probe=03554389d5) | Jun 11, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [568b23271e](https://linux-hardware.org/?probe=568b23271e) | Jun 11, 2022 |
| Gigabyte      | B550M DS3H                  | [32415f8bd1](https://linux-hardware.org/?probe=32415f8bd1) | Jun 10, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [0dd5653fc1](https://linux-hardware.org/?probe=0dd5653fc1) | Jun 10, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | [294890a076](https://linux-hardware.org/?probe=294890a076) | Jun 10, 2022 |
| ASUSTek       | ROG STRIX B360-I GAMING     | [1b4307a298](https://linux-hardware.org/?probe=1b4307a298) | Jun 09, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [c18fee9219](https://linux-hardware.org/?probe=c18fee9219) | Jun 08, 2022 |
| MSI           | H81M-E33                    | [49191a1c98](https://linux-hardware.org/?probe=49191a1c98) | Jun 08, 2022 |
| MSI           | B350 GAMING PRO CARBON      | [2f1acce421](https://linux-hardware.org/?probe=2f1acce421) | Jun 08, 2022 |
| HP            | 1998                        | [fd5184fe12](https://linux-hardware.org/?probe=fd5184fe12) | Jun 08, 2022 |
| ASRock        | B550M Pro4                  | [10fbde5027](https://linux-hardware.org/?probe=10fbde5027) | Jun 07, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [25213ed098](https://linux-hardware.org/?probe=25213ed098) | Jun 07, 2022 |
| Gigabyte      | Z690 AORUS PRO DDR4         | [1196dd3b41](https://linux-hardware.org/?probe=1196dd3b41) | Jun 06, 2022 |
| MSI           | B350M PRO-VDH               | [ae45bf67a3](https://linux-hardware.org/?probe=ae45bf67a3) | Jun 06, 2022 |
| Gigabyte      | Z690 AORUS PRO DDR4         | [15efe8a0a2](https://linux-hardware.org/?probe=15efe8a0a2) | Jun 06, 2022 |
| MSI           | H81M-E33                    | [6a2d6cbe74](https://linux-hardware.org/?probe=6a2d6cbe74) | Jun 04, 2022 |
| BESSTAR Te... | UM700                       | [ea24f8341e](https://linux-hardware.org/?probe=ea24f8341e) | Jun 02, 2022 |
| BESSTAR Te... | UM700                       | [d3799b37d7](https://linux-hardware.org/?probe=d3799b37d7) | Jun 02, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [829ee446bd](https://linux-hardware.org/?probe=829ee446bd) | Jun 02, 2022 |
| MSI           | B350 TOMAHAWK               | [b9cdc775ea](https://linux-hardware.org/?probe=b9cdc775ea) | Jun 02, 2022 |
| ASRock        | B550M Pro4                  | [9ac2f5ba04](https://linux-hardware.org/?probe=9ac2f5ba04) | Jun 01, 2022 |
| MSI           | H81I                        | [6b4e34a35e](https://linux-hardware.org/?probe=6b4e34a35e) | Jun 01, 2022 |
| MSI           | B250M PRO-VDH               | [eede963720](https://linux-hardware.org/?probe=eede963720) | May 31, 2022 |
| MSI           | B250M PRO-VDH               | [e2dd690b16](https://linux-hardware.org/?probe=e2dd690b16) | May 31, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [a6506e0582](https://linux-hardware.org/?probe=a6506e0582) | May 30, 2022 |
| ASRock        | B550M Pro4                  | [a5eee874a5](https://linux-hardware.org/?probe=a5eee874a5) | May 30, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0050247c85](https://linux-hardware.org/?probe=0050247c85) | May 29, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [1416d5a87d](https://linux-hardware.org/?probe=1416d5a87d) | May 29, 2022 |
| Google        | Guado                       | [d026c0565d](https://linux-hardware.org/?probe=d026c0565d) | May 29, 2022 |
| ASRock        | B550M Pro4                  | [4e2d37a90d](https://linux-hardware.org/?probe=4e2d37a90d) | May 29, 2022 |
| ASRock        | B550M Pro4                  | [b861a73ade](https://linux-hardware.org/?probe=b861a73ade) | May 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | [c3d1916e14](https://linux-hardware.org/?probe=c3d1916e14) | May 28, 2022 |
| Gigabyte      | MCMLUCB-00                  | [90c886e471](https://linux-hardware.org/?probe=90c886e471) | May 27, 2022 |
| Dell          | 0KP561                      | [2435960bba](https://linux-hardware.org/?probe=2435960bba) | May 27, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [63690e08a1](https://linux-hardware.org/?probe=63690e08a1) | May 27, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [d1891c2d3b](https://linux-hardware.org/?probe=d1891c2d3b) | May 27, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [bf3f9d0ed3](https://linux-hardware.org/?probe=bf3f9d0ed3) | May 26, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [c9c34c5c6f](https://linux-hardware.org/?probe=c9c34c5c6f) | May 26, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [c8f47b62d2](https://linux-hardware.org/?probe=c8f47b62d2) | May 26, 2022 |
| ASRock        | B550M Pro4                  | [d5df82a4ce](https://linux-hardware.org/?probe=d5df82a4ce) | May 25, 2022 |
| ASRock        | H670M-ITX/ax                | [c11c9ac073](https://linux-hardware.org/?probe=c11c9ac073) | May 25, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [0390e0a7c2](https://linux-hardware.org/?probe=0390e0a7c2) | May 25, 2022 |
| MSI           | X470 GAMING PRO             | [8409fe7eab](https://linux-hardware.org/?probe=8409fe7eab) | May 24, 2022 |
| ASRock        | B550M Pro4                  | [35ba2b5a7a](https://linux-hardware.org/?probe=35ba2b5a7a) | May 24, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [7375e6d7ec](https://linux-hardware.org/?probe=7375e6d7ec) | May 24, 2022 |
| Unknown       | Unknown                     | [62b61f57ef](https://linux-hardware.org/?probe=62b61f57ef) | May 24, 2022 |
| Gigabyte      | Z77M-D3H                    | [b7369242f9](https://linux-hardware.org/?probe=b7369242f9) | May 23, 2022 |
| Google        | Guado                       | [3245615e95](https://linux-hardware.org/?probe=3245615e95) | May 23, 2022 |
| MSI           | H310M PRO-VDH PLUS          | [de3cd5c495](https://linux-hardware.org/?probe=de3cd5c495) | May 23, 2022 |
| ASRock        | Z77 Extreme4                | [198a8b039a](https://linux-hardware.org/?probe=198a8b039a) | May 22, 2022 |
| ASRock        | Z77 Extreme4                | [3c45f702eb](https://linux-hardware.org/?probe=3c45f702eb) | May 22, 2022 |
| MSI           | H97M-G43                    | [3869b1146e](https://linux-hardware.org/?probe=3869b1146e) | May 22, 2022 |
| ASRock        | B550M Pro4                  | [85974104c5](https://linux-hardware.org/?probe=85974104c5) | May 21, 2022 |
| MSI           | Z390-A PRO                  | [8baf319c52](https://linux-hardware.org/?probe=8baf319c52) | May 21, 2022 |
| Gigabyte      | H61M-S2PV                   | [4dce3bdb3a](https://linux-hardware.org/?probe=4dce3bdb3a) | May 21, 2022 |
| Chatreey      | AC1-DP                      | [aefe90ce82](https://linux-hardware.org/?probe=aefe90ce82) | May 20, 2022 |
| HP            | 212B                        | [a52da35d02](https://linux-hardware.org/?probe=a52da35d02) | May 20, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [1efa62dcdb](https://linux-hardware.org/?probe=1efa62dcdb) | May 19, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [bcb2dd930d](https://linux-hardware.org/?probe=bcb2dd930d) | May 19, 2022 |
| HP            | 8053                        | [67ea3799ad](https://linux-hardware.org/?probe=67ea3799ad) | May 18, 2022 |
| MSI           | X99S GAMING 7               | [ff6fe109c0](https://linux-hardware.org/?probe=ff6fe109c0) | May 17, 2022 |
| ASUSTek       | PRIME X570-P                | [0e0b2d38d8](https://linux-hardware.org/?probe=0e0b2d38d8) | May 17, 2022 |
| ASUSTek       | PRIME X570-P                | [a80d230e6e](https://linux-hardware.org/?probe=a80d230e6e) | May 17, 2022 |
| ASRock        | B550M Pro4                  | [acd5c94fc8](https://linux-hardware.org/?probe=acd5c94fc8) | May 16, 2022 |
| HP            | 3031h                       | [9a6723ea52](https://linux-hardware.org/?probe=9a6723ea52) | May 16, 2022 |
| HP            | 3031h                       | [414614ec5d](https://linux-hardware.org/?probe=414614ec5d) | May 16, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [798d2cee16](https://linux-hardware.org/?probe=798d2cee16) | May 16, 2022 |
| Gigabyte      | MCMLUCB-00                  | [1ad57be6ad](https://linux-hardware.org/?probe=1ad57be6ad) | May 16, 2022 |
| ASUSTek       | PRIME Z390-P                | [a0c15e2a2f](https://linux-hardware.org/?probe=a0c15e2a2f) | May 16, 2022 |
| Gigabyte      | B550M AORUS ELITE           | [6d1b1bca17](https://linux-hardware.org/?probe=6d1b1bca17) | May 16, 2022 |
| HP            | 8053                        | [35d3caac96](https://linux-hardware.org/?probe=35d3caac96) | May 16, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Manjaro/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Manjaro           | 1145     | 41.44%  |
| Manjaro 20.1      | 135      | 4.89%   |
| Manjaro 20.2.1    | 108      | 3.91%   |
| Manjaro 22.0.0    | 102      | 3.69%   |
| Manjaro 20.2      | 89       | 3.22%   |
| Manjaro 20.0.3    | 81       | 2.93%   |
| Manjaro 18.1.5    | 56       | 2.03%   |
| Manjaro 21.2.6    | 53       | 1.92%   |
| Manjaro 21.2.5    | 53       | 1.92%   |
| Manjaro 21.1.0    | 53       | 1.92%   |
| Manjaro 18.0.4    | 46       | 1.66%   |
| Manjaro 21.2.0    | 45       | 1.63%   |
| Manjaro 20.0      | 45       | 1.63%   |
| Manjaro 21.1.6    | 38       | 1.38%   |
| Manjaro 21.0.7    | 36       | 1.3%    |
| Manjaro 21.0.5    | 35       | 1.27%   |
| Manjaro 21.0      | 35       | 1.27%   |
| Manjaro 19.0.2    | 31       | 1.12%   |
| Manjaro 20.1.2    | 29       | 1.05%   |
| Manjaro 20.0.1    | 29       | 1.05%   |
| Manjaro 21.2.3    | 27       | 0.98%   |
| Manjaro 22.1.0    | 25       | 0.9%    |
| Manjaro 20.1.1    | 24       | 0.87%   |
| Manjaro 21.2.1    | 23       | 0.83%   |
| Manjaro 21.3.7    | 20       | 0.72%   |
| Manjaro 21.3.6    | 18       | 0.65%   |
| Manjaro 22.0.4    | 16       | 0.58%   |
| Manjaro 21.0.4    | 16       | 0.58%   |
| Manjaro 21.0.1    | 14       | 0.51%   |
| Manjaro 21.0.2    | 13       | 0.47%   |
| Manjaro 22.1.1    | 12       | 0.43%   |
| Manjaro 21.2rc    | 12       | 0.43%   |
| Manjaro 21.2.4    | 12       | 0.43%   |
| Manjaro 21.1.2    | 12       | 0.43%   |
| Manjaro 21.0.3    | 12       | 0.43%   |
| Manjaro 18.0.0-rc | 12       | 0.43%   |
| Manjaro 22.0      | 11       | 0.4%    |
| Manjaro 21.3.1    | 11       | 0.4%    |
| Manjaro 21.1.5    | 11       | 0.4%    |
| Manjaro 21.3.0    | 10       | 0.36%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Manjaro | 2538     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.9.16-1-MANJARO  | 115      | 3.73%   |
| 5.8.6-1-MANJARO   | 68       | 2.21%   |
| 5.13.19-2-MANJARO | 66       | 2.14%   |
| 5.15.28-1-MANJARO | 49       | 1.59%   |
| 5.9.11-3-MANJARO  | 48       | 1.56%   |
| 5.8.11-1-MANJARO  | 46       | 1.49%   |
| 5.10.42-1-MANJARO | 40       | 1.3%    |
| 6.1.1-1-MANJARO   | 38       | 1.23%   |
| 5.8.18-1-MANJARO  | 38       | 1.23%   |
| 6.1.12-1-MANJARO  | 32       | 1.04%   |
| 5.15.32-1-MANJARO | 32       | 1.04%   |
| 5.6.16-1-MANJARO  | 31       | 1.01%   |
| 5.15.60-1-MANJARO | 30       | 0.97%   |
| 5.10.36-2-MANJARO | 30       | 0.97%   |
| 5.7.9-1-MANJARO   | 29       | 0.94%   |
| 5.15.12-1-MANJARO | 29       | 0.94%   |
| 5.8.3-2-MANJARO   | 25       | 0.81%   |
| 5.8.16-2-MANJARO  | 25       | 0.81%   |
| 5.6.19-2-MANJARO  | 24       | 0.78%   |
| 5.6.15-1-MANJARO  | 24       | 0.78%   |
| 5.17.1-3-MANJARO  | 24       | 0.78%   |
| 5.7.0-3-MANJARO   | 23       | 0.75%   |
| 5.10.2-2-MANJARO  | 23       | 0.75%   |
| 5.6.7-1-MANJARO   | 22       | 0.71%   |
| 5.6.12-1-MANJARO  | 22       | 0.71%   |
| 5.16.14-1-MANJARO | 22       | 0.71%   |
| 5.15.2-2-MANJARO  | 22       | 0.71%   |
| 5.10.23-1-MANJARO | 22       | 0.71%   |
| 5.9.1-1-MANJARO   | 21       | 0.68%   |
| 5.11.6-1-MANJARO  | 21       | 0.68%   |
| 5.4.15-2-MANJARO  | 20       | 0.65%   |
| 5.7.17-2-MANJARO  | 19       | 0.62%   |
| 5.4.6-2-MANJARO   | 19       | 0.62%   |
| 5.10.7-3-MANJARO  | 19       | 0.62%   |
| 5.10.15-1-MANJARO | 19       | 0.62%   |
| 5.14.10-1-MANJARO | 17       | 0.55%   |
| 5.11.2-1-MANJARO  | 17       | 0.55%   |
| 5.10.53-1-MANJARO | 17       | 0.55%   |
| 5.9.3-1-MANJARO   | 16       | 0.52%   |
| 5.6.11-1-MANJARO  | 16       | 0.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.9.16  | 115      | 3.73%   |
| 5.8.6   | 68       | 2.21%   |
| 5.13.19 | 66       | 2.14%   |
| 5.9.11  | 51       | 1.66%   |
| 5.15.28 | 49       | 1.59%   |
| 5.8.11  | 47       | 1.53%   |
| 5.10.42 | 40       | 1.3%    |
| 6.1.1   | 38       | 1.23%   |
| 5.8.18  | 38       | 1.23%   |
| 6.1.12  | 32       | 1.04%   |
| 5.15.32 | 32       | 1.04%   |
| 5.6.16  | 31       | 1.01%   |
| 5.15.60 | 30       | 0.97%   |
| 5.10.36 | 30       | 0.97%   |
| 5.7.9   | 29       | 0.94%   |
| 5.7.0   | 29       | 0.94%   |
| 5.17.1  | 29       | 0.94%   |
| 5.15.12 | 29       | 0.94%   |
| 5.9.1   | 28       | 0.91%   |
| 5.6.19  | 27       | 0.88%   |
| 5.8.3   | 26       | 0.84%   |
| 5.8.16  | 25       | 0.81%   |
| 5.6.15  | 24       | 0.78%   |
| 5.6.12  | 23       | 0.75%   |
| 5.15.2  | 23       | 0.75%   |
| 5.10.2  | 23       | 0.75%   |
| 5.6.7   | 22       | 0.71%   |
| 5.16.14 | 22       | 0.71%   |
| 5.10.23 | 22       | 0.71%   |
| 5.11.6  | 21       | 0.68%   |
| 5.7.17  | 20       | 0.65%   |
| 5.4.15  | 20       | 0.65%   |
| 5.10.7  | 20       | 0.65%   |
| 5.4.6   | 19       | 0.62%   |
| 5.10.15 | 19       | 0.62%   |
| 5.15.7  | 17       | 0.55%   |
| 5.14.10 | 17       | 0.55%   |
| 5.14.0  | 17       | 0.55%   |
| 5.11.2  | 17       | 0.55%   |
| 5.10.53 | 17       | 0.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 442      | 15.36%  |
| 5.10    | 360      | 12.51%  |
| 5.4     | 253      | 8.79%   |
| 5.9     | 230      | 7.99%   |
| 5.8     | 228      | 7.92%   |
| 6.1     | 185      | 6.43%   |
| 5.6     | 172      | 5.98%   |
| 5.13    | 126      | 4.38%   |
| 5.7     | 109      | 3.79%   |
| 5.11    | 91       | 3.16%   |
| 4.19    | 66       | 2.29%   |
| 5.17    | 64       | 2.22%   |
| 5.16    | 64       | 2.22%   |
| 6.0     | 61       | 2.12%   |
| 5.14    | 61       | 2.12%   |
| 5.18    | 55       | 1.91%   |
| 5.19    | 53       | 1.84%   |
| 5.12    | 49       | 1.7%    |
| 5.5     | 39       | 1.36%   |
| 4.14    | 33       | 1.15%   |
| 6.2     | 30       | 1.04%   |
| 5.3     | 23       | 0.8%    |
| 6.3     | 21       | 0.73%   |
| 5.2     | 17       | 0.59%   |
| 5.1     | 13       | 0.45%   |
| 5.0     | 11       | 0.38%   |
| 4.20    | 5        | 0.17%   |
| 4.18    | 5        | 0.17%   |
| 4.17    | 3        | 0.1%    |
| 4.16    | 3        | 0.1%    |
| 4.9     | 2        | 0.07%   |
| 4.7     | 2        | 0.07%   |
| 4.4     | 2        | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 2538     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| KDE5                     | 995      | 37.45%  |
| XFCE                     | 571      | 21.49%  |
| GNOME                    | 502      | 18.89%  |
| KDE                      | 247      | 9.3%    |
| Unknown                  | 104      | 3.91%   |
| X-Cinnamon               | 83       | 3.12%   |
| i3                       | 45       | 1.69%   |
| MATE                     | 22       | 0.83%   |
| Cinnamon                 | 22       | 0.83%   |
| Deepin                   | 21       | 0.79%   |
| Budgie                   | 14       | 0.53%   |
| LXQt                     | 8        | 0.3%    |
| awesome                  | 5        | 0.19%   |
| sway                     | 4        | 0.15%   |
| bspwm                    | 3        | 0.11%   |
| ICEWM                    | 2        | 0.08%   |
| GNOME Classic            | 2        | 0.08%   |
| Yaru:ubuntu:GNOME        | 1        | 0.04%   |
| qtile                    | 1        | 0.04%   |
| openbox                  | 1        | 0.04%   |
| LXDE                     | 1        | 0.04%   |
| Enlightenment            | 1        | 0.04%   |
| DWM                      | 1        | 0.04%   |
| /usr/bin/openbox-session | 1        | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 2315     | 89.56%  |
| Wayland | 203      | 7.85%   |
| Unknown | 41       | 1.59%   |
| Tty     | 26       | 1.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1140     | 43.51%  |
| SDDM    | 653      | 24.92%  |
| LightDM | 440      | 16.79%  |
| GDM     | 286      | 10.92%  |
| TDM     | 89       | 3.4%    |
| LXDM    | 5        | 0.19%   |
| GREETD  | 3        | 0.11%   |
| SLiM    | 2        | 0.08%   |
| XDM     | 1        | 0.04%   |
| LYNDE   | 1        | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 1016     | 39.38%  |
| de_DE   | 224      | 8.68%   |
| ru_RU   | 196      | 7.6%    |
| en_GB   | 161      | 6.24%   |
| Unknown | 155      | 6.01%   |
| pt_BR   | 113      | 4.38%   |
| en_CA   | 71       | 2.75%   |
| fr_FR   | 70       | 2.71%   |
| es_ES   | 63       | 2.44%   |
| it_IT   | 56       | 2.17%   |
| pl_PL   | 48       | 1.86%   |
| en_AU   | 39       | 1.51%   |
| nl_NL   | 21       | 0.81%   |
| de_AT   | 21       | 0.81%   |
| en_IN   | 20       | 0.78%   |
| ru_UA   | 18       | 0.7%    |
| es_AR   | 16       | 0.62%   |
| sv_SE   | 15       | 0.58%   |
| es_MX   | 15       | 0.58%   |
| zh_CN   | 14       | 0.54%   |
| fi_FI   | 13       | 0.5%    |
| fr_CA   | 11       | 0.43%   |
| en_IE   | 11       | 0.43%   |
| hu_HU   | 10       | 0.39%   |
| en_ZA   | 9        | 0.35%   |
| en_PH   | 9        | 0.35%   |
| da_DK   | 9        | 0.35%   |
| cs_CZ   | 9        | 0.35%   |
| en_NZ   | 8        | 0.31%   |
| pt_PT   | 7        | 0.27%   |
| es_CL   | 7        | 0.27%   |
| uk_UA   | 6        | 0.23%   |
| es_UY   | 6        | 0.23%   |
| en_IL   | 6        | 0.23%   |
| en_DK   | 6        | 0.23%   |
| de_CH   | 6        | 0.23%   |
| ja_JP   | 5        | 0.19%   |
| fr_BE   | 5        | 0.19%   |
| tr_TR   | 4        | 0.16%   |
| nb_NO   | 4        | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1618     | 62.37%  |
| EFI  | 976      | 37.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 2147     | 83.06%  |
| Btrfs   | 273      | 10.56%  |
| Xfs     | 41       | 1.59%   |
| Unknown | 40       | 1.55%   |
| Overlay | 37       | 1.43%   |
| Tmpfs   | 24       | 0.93%   |
| F2fs    | 12       | 0.46%   |
| Zfs     | 4        | 0.15%   |
| Ext2    | 3        | 0.12%   |
| Ext3    | 2        | 0.08%   |
| XXXX    | 1        | 0.04%   |
| XXXfs   | 1        | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1238     | 47.52%  |
| GPT     | 1097     | 42.11%  |
| MBR     | 270      | 10.36%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2145     | 82.69%  |
| Yes       | 449      | 17.31%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1631     | 62.92%  |
| Yes       | 961      | 37.08%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 747      | 29.43%  |
| Gigabyte Technology                  | 519      | 20.45%  |
| MSI                                  | 405      | 15.96%  |
| ASRock                               | 279      | 10.99%  |
| Dell                                 | 134      | 5.28%   |
| Hewlett-Packard                      | 123      | 4.85%   |
| Intel                                | 62       | 2.44%   |
| Lenovo                               | 53       | 2.09%   |
| Acer                                 | 27       | 1.06%   |
| Unknown                              | 22       | 0.87%   |
| Biostar                              | 20       | 0.79%   |
| Pegatron                             | 16       | 0.63%   |
| Huanan                               | 13       | 0.51%   |
| Foxconn                              | 11       | 0.43%   |
| Apple                                | 9        | 0.35%   |
| Medion                               | 8        | 0.32%   |
| Fujitsu                              | 7        | 0.28%   |
| ECS                                  | 7        | 0.28%   |
| Shuttle                              | 5        | 0.2%    |
| Positivo                             | 5        | 0.2%    |
| BESSTAR Tech                         | 5        | 0.2%    |
| AZW                                  | 4        | 0.16%   |
| Alienware                            | 4        | 0.16%   |
| PCWare                               | 3        | 0.12%   |
| ZOTAC                                | 2        | 0.08%   |
| Shenzhen Meigao Electronic Equipment | 2        | 0.08%   |
| OEM                                  | 2        | 0.08%   |
| Minix                                | 2        | 0.08%   |
| MACHINIST                            | 2        | 0.08%   |
| Inventec                             | 2        | 0.08%   |
| Google                               | 2        | 0.08%   |
| Gateway                              | 2        | 0.08%   |
| Fujitsu Siemens                      | 2        | 0.08%   |
| XFX                                  | 1        | 0.04%   |
| VS Company                           | 1        | 0.04%   |
| TPV-INVENTA                          | 1        | 0.04%   |
| SYWZ                                 | 1        | 0.04%   |
| System76                             | 1        | 0.04%   |
| Supermicro                           | 1        | 0.04%   |
| SiYW                                 | 1        | 0.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 71       | 2.8%    |
| MSI MS-7C37                      | 28       | 1.1%    |
| MSI MS-7C02                      | 26       | 1.02%   |
| Gigabyte B450M DS3H              | 26       | 1.02%   |
| Unknown                          | 24       | 0.95%   |
| ASUS TUF Gaming X570-PLUS        | 22       | 0.87%   |
| ASUS PRIME A320M-K               | 19       | 0.75%   |
| MSI MS-7C91                      | 17       | 0.67%   |
| MSI MS-7B86                      | 17       | 0.67%   |
| ASRock B450M Pro4                | 16       | 0.63%   |
| MSI MS-7B79                      | 15       | 0.59%   |
| ASUS ROG STRIX B450-F GAMING     | 14       | 0.55%   |
| Gigabyte X570 AORUS ELITE        | 13       | 0.51%   |
| MSI MS-7A38                      | 12       | 0.47%   |
| Dell OptiPlex 9020               | 12       | 0.47%   |
| ASUS TUF Gaming B550M-PLUS       | 12       | 0.47%   |
| ASUS ROG STRIX B550-F GAMING     | 12       | 0.47%   |
| ASUS PRIME B450M-A               | 12       | 0.47%   |
| Gigabyte B450 AORUS M            | 11       | 0.43%   |
| Gigabyte 970A-DS3P               | 11       | 0.43%   |
| Dell OptiPlex 7010               | 11       | 0.43%   |
| ASUS PRIME B350-PLUS             | 11       | 0.43%   |
| MSI MS-7B89                      | 10       | 0.39%   |
| Gigabyte X570 AORUS MASTER       | 10       | 0.39%   |
| Gigabyte X470 AORUS ULTRA GAMING | 10       | 0.39%   |
| ASUS ROG STRIX X570-E GAMING     | 10       | 0.39%   |
| MSI MS-7817                      | 9        | 0.35%   |
| MSI MS-7693                      | 9        | 0.35%   |
| Gigabyte B450 AORUS ELITE        | 9        | 0.35%   |
| ASUS ROG CROSSHAIR VIII HERO     | 9        | 0.35%   |
| ASUS PRIME X470-PRO              | 9        | 0.35%   |
| ASUS PRIME B450-PLUS             | 9        | 0.35%   |
| MSI MS-7C94                      | 8        | 0.32%   |
| MSI MS-7A34                      | 8        | 0.32%   |
| ASUS PRIME X370-PRO              | 8        | 0.32%   |
| ASUS PRIME B350M-A               | 8        | 0.32%   |
| ASRock B450M Steel Legend        | 8        | 0.32%   |
| ASRock B450 Pro4                 | 8        | 0.32%   |
| ASUS ROG STRIX X570-F GAMING     | 7        | 0.28%   |
| ASUS M5A78L-M PLUS/USB3          | 7        | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS PRIME          | 159      | 6.26%   |
| ASUS ROG            | 145      | 5.71%   |
| Dell OptiPlex       | 83       | 3.27%   |
| ASUS TUF            | 81       | 3.19%   |
| ASUS All            | 71       | 2.8%    |
| Gigabyte X570       | 47       | 1.85%   |
| Gigabyte B450M      | 43       | 1.69%   |
| HP Compaq           | 36       | 1.42%   |
| Gigabyte B450       | 34       | 1.34%   |
| MSI MS-7C37         | 28       | 1.1%    |
| MSI MS-7C02         | 26       | 1.02%   |
| ASRock B450M        | 26       | 1.02%   |
| Lenovo ThinkCentre  | 24       | 0.95%   |
| Unknown             | 24       | 0.95%   |
| Dell Precision      | 22       | 0.87%   |
| Gigabyte B550       | 20       | 0.79%   |
| ASRock X570         | 20       | 0.79%   |
| HP EliteDesk        | 19       | 0.75%   |
| ASRock B450         | 18       | 0.71%   |
| MSI MS-7C91         | 17       | 0.67%   |
| MSI MS-7B86         | 17       | 0.67%   |
| Acer Aspire         | 17       | 0.67%   |
| ASUS M5A78L-M       | 16       | 0.63%   |
| MSI MS-7B79         | 15       | 0.59%   |
| ASUS P8Z77-V        | 15       | 0.59%   |
| Gigabyte Z390       | 14       | 0.55%   |
| ASUS M5A97          | 14       | 0.55%   |
| MSI MS-7A38         | 12       | 0.47%   |
| Gigabyte X470       | 12       | 0.47%   |
| Gigabyte 970A-DS3P  | 12       | 0.47%   |
| ASUS Maximus        | 12       | 0.47%   |
| Gigabyte B550M      | 11       | 0.43%   |
| ASUS P8H61-M        | 11       | 0.43%   |
| MSI MS-7B89         | 10       | 0.39%   |
| HP Pavilion         | 10       | 0.39%   |
| MSI MS-7817         | 9        | 0.35%   |
| MSI MS-7693         | 9        | 0.35%   |
| Lenovo ThinkStation | 9        | 0.35%   |
| ASRock X470         | 9        | 0.35%   |
| ASRock B550M        | 9        | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 414      | 16.31%  |
| 2019    | 318      | 12.53%  |
| 2020    | 277      | 10.91%  |
| 2017    | 215      | 8.47%   |
| 2012    | 203      | 8%      |
| 2013    | 179      | 7.05%   |
| 2014    | 149      | 5.87%   |
| 2011    | 143      | 5.63%   |
| 2015    | 112      | 4.41%   |
| 2016    | 111      | 4.37%   |
| 2021    | 94       | 3.7%    |
| 2010    | 88       | 3.47%   |
| 2009    | 77       | 3.03%   |
| 2022    | 47       | 1.85%   |
| 2008    | 46       | 1.81%   |
| 2007    | 44       | 1.73%   |
| 2006    | 12       | 0.47%   |
| 2023    | 4        | 0.16%   |
| 2005    | 4        | 0.16%   |
| Unknown | 1        | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 2538     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 2536     | 99.88%  |
| Enabled  | 3        | 0.12%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2536     | 99.92%  |
| Yes  | 2        | 0.08%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 924      | 35.72%  |
| 32.01-64.0  | 537      | 20.76%  |
| 8.01-16.0   | 463      | 17.9%   |
| 4.01-8.0    | 247      | 9.55%   |
| 3.01-4.0    | 168      | 6.49%   |
| 64.01-256.0 | 128      | 4.95%   |
| 24.01-32.0  | 84       | 3.25%   |
| 1.01-2.0    | 30       | 1.16%   |
| 2.01-3.0    | 6        | 0.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 725      | 25.19%  |
| 2.01-3.0    | 651      | 22.62%  |
| 1.01-2.0    | 635      | 22.06%  |
| 3.01-4.0    | 473      | 16.44%  |
| 8.01-16.0   | 244      | 8.48%   |
| 0.51-1.0    | 71       | 2.47%   |
| 16.01-24.0  | 44       | 1.53%   |
| 24.01-32.0  | 14       | 0.49%   |
| 0.01-0.5    | 11       | 0.38%   |
| 32.01-64.0  | 9        | 0.31%   |
| 64.01-256.0 | 1        | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 804      | 30.13%  |
| 1      | 629      | 23.58%  |
| 3      | 540      | 20.24%  |
| 4      | 344      | 12.89%  |
| 5      | 197      | 7.38%   |
| 6      | 73       | 2.74%   |
| 7      | 36       | 1.35%   |
| 8      | 15       | 0.56%   |
| 0      | 11       | 0.41%   |
| 9      | 9        | 0.34%   |
| 11     | 4        | 0.15%   |
| 10     | 3        | 0.11%   |
| 12     | 2        | 0.07%   |
| 20     | 1        | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1706     | 66.28%  |
| Yes       | 868      | 33.72%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2511     | 98.94%  |
| No        | 27       | 1.06%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1375     | 53.42%  |
| Yes       | 1199     | 46.58%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1530     | 59.28%  |
| Yes       | 1051     | 40.72%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 485      | 18.97%  |
| Germany      | 310      | 12.13%  |
| Russia       | 232      | 9.08%   |
| Brazil       | 157      | 6.14%   |
| Canada       | 104      | 4.07%   |
| France       | 94       | 3.68%   |
| Spain        | 85       | 3.33%   |
| UK           | 83       | 3.25%   |
| Italy        | 78       | 3.05%   |
| Poland       | 75       | 2.93%   |
| Ukraine      | 54       | 2.11%   |
| Netherlands  | 51       | 2%      |
| Sweden       | 43       | 1.68%   |
| Australia    | 41       | 1.6%    |
| Austria      | 38       | 1.49%   |
| Finland      | 31       | 1.21%   |
| Belgium      | 26       | 1.02%   |
| Mexico       | 25       | 0.98%   |
| Romania      | 24       | 0.94%   |
| India        | 24       | 0.94%   |
| Argentina    | 24       | 0.94%   |
| Greece       | 20       | 0.78%   |
| Norway       | 19       | 0.74%   |
| Bulgaria     | 19       | 0.74%   |
| Switzerland  | 18       | 0.7%    |
| Hungary      | 18       | 0.7%    |
| Denmark      | 18       | 0.7%    |
| Portugal     | 17       | 0.67%   |
| South Africa | 14       | 0.55%   |
| China        | 14       | 0.55%   |
| Israel       | 13       | 0.51%   |
| Czechia      | 13       | 0.51%   |
| Belarus      | 13       | 0.51%   |
| Turkey       | 11       | 0.43%   |
| Lithuania    | 11       | 0.43%   |
| Saudi Arabia | 10       | 0.39%   |
| New Zealand  | 10       | 0.39%   |
| Ireland      | 10       | 0.39%   |
| Philippines  | 9        | 0.35%   |
| Chile        | 9        | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Moscow            | 53       | 1.97%   |
| St Petersburg     | 24       | 0.89%   |
| Warsaw            | 19       | 0.71%   |
| Berlin            | 19       | 0.71%   |
| Vienna            | 18       | 0.67%   |
| Kyiv              | 17       | 0.63%   |
| Madrid            | 16       | 0.59%   |
| Sao Paulo         | 15       | 0.56%   |
| Toronto           | 14       | 0.52%   |
| Athens            | 14       | 0.52%   |
| Rome              | 13       | 0.48%   |
| Amsterdam         | 13       | 0.48%   |
| Stockholm         | 12       | 0.45%   |
| Rio de Janeiro    | 12       | 0.45%   |
| Frankfurt am Main | 12       | 0.45%   |
| Sydney            | 11       | 0.41%   |
| Helsinki          | 11       | 0.41%   |
| Hamburg           | 11       | 0.41%   |
| Portland          | 10       | 0.37%   |
| Paris             | 10       | 0.37%   |
| Milan             | 10       | 0.37%   |
| Melbourne         | 10       | 0.37%   |
| Krakow            | 10       | 0.37%   |
| Bucharest         | 10       | 0.37%   |
| Barcelona         | 10       | 0.37%   |
| Sofia             | 9        | 0.33%   |
| Dallas            | 9        | 0.33%   |
| Copenhagen        | 9        | 0.33%   |
| Yekaterinburg     | 8        | 0.3%    |
| Stuttgart         | 8        | 0.3%    |
| New York          | 8        | 0.3%    |
| Montreal          | 8        | 0.3%    |
| Minsk             | 8        | 0.3%    |
| Miami             | 8        | 0.3%    |
| Indianapolis      | 8        | 0.3%    |
| Austin            | 8        | 0.3%    |
| Vilnius           | 7        | 0.26%   |
| Oslo              | 7        | 0.26%   |
| Omsk              | 7        | 0.26%   |
| Munich            | 7        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 982      | 1665   | 17.67%  |
| Seagate                     | 970      | 1567   | 17.45%  |
| Samsung Electronics         | 927      | 1632   | 16.68%  |
| Kingston                    | 348      | 494    | 6.26%   |
| Toshiba                     | 301      | 396    | 5.41%   |
| Crucial                     | 288      | 440    | 5.18%   |
| SanDisk                     | 286      | 387    | 5.14%   |
| Hitachi                     | 134      | 195    | 2.41%   |
| Intel                       | 113      | 152    | 2.03%   |
| A-DATA Technology           | 86       | 122    | 1.55%   |
| Phison                      | 84       | 112    | 1.51%   |
| HGST                        | 63       | 98     | 1.13%   |
| China                       | 57       | 81     | 1.03%   |
| Silicon Motion              | 48       | 68     | 0.86%   |
| PNY                         | 43       | 64     | 0.77%   |
| Micron/Crucial Technology   | 41       | 50     | 0.74%   |
| OCZ                         | 39       | 53     | 0.7%    |
| Unknown                     | 37       | 66     | 0.67%   |
| SPCC                        | 37       | 44     | 0.67%   |
| Patriot                     | 35       | 44     | 0.63%   |
| Intenso                     | 35       | 51     | 0.63%   |
| XPG                         | 32       | 36     | 0.58%   |
| Phison Electronics          | 31       | 36     | 0.56%   |
| SK hynix                    | 30       | 34     | 0.54%   |
| Corsair                     | 27       | 38     | 0.49%   |
| Micron Technology           | 25       | 32     | 0.45%   |
| Transcend                   | 23       | 23     | 0.41%   |
| Realtek Semiconductor       | 22       | 27     | 0.4%    |
| Plextor                     | 21       | 25     | 0.38%   |
| Team                        | 20       | 26     | 0.36%   |
| JMicron Technology          | 20       | 26     | 0.36%   |
| GOODRAM                     | 19       | 24     | 0.34%   |
| Lexar                       | 18       | 20     | 0.32%   |
| Apacer                      | 15       | 17     | 0.27%   |
| Kingston Technology Company | 14       | 15     | 0.25%   |
| Maxtor                      | 13       | 15     | 0.23%   |
| Gigabyte Technology         | 13       | 22     | 0.23%   |
| Hewlett-Packard             | 11       | 15     | 0.2%    |
| ASMT                        | 11       | 18     | 0.2%    |
| KingDian                    | 10       | 10     | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 88       | 1.33%   |
| Samsung SSD 860 EVO 500GB                           | 85       | 1.28%   |
| Seagate ST1000DM010-2EP102 1TB                      | 79       | 1.19%   |
| Seagate ST2000DM008-2FR102 2TB                      | 74       | 1.12%   |
| Samsung SSD 850 EVO 500GB                           | 63       | 0.95%   |
| Samsung NVMe SSD Drive 500GB                        | 63       | 0.95%   |
| Samsung SSD 850 EVO 250GB                           | 62       | 0.94%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 56       | 0.85%   |
| Toshiba DT01ACA100 1TB                              | 56       | 0.85%   |
| Kingston SA400S37120G 120GB SSD                     | 53       | 0.8%    |
| Crucial CT500MX500SSD1 500GB                        | 52       | 0.79%   |
| Samsung SSD 860 EVO 1TB                             | 50       | 0.76%   |
| Samsung NVMe SSD Drive 1TB                          | 49       | 0.74%   |
| Seagate ST500DM002-1BD142 500GB                     | 44       | 0.66%   |
| Seagate ST2000DM006-2DM164 2TB                      | 41       | 0.62%   |
| Seagate ST1000DM003-1ER162 1TB                      | 41       | 0.62%   |
| Crucial CT1000MX500SSD1 1TB                         | 41       | 0.62%   |
| Samsung SSD 860 EVO 250GB                           | 40       | 0.6%    |
| Kingston SA400S37480G 480GB SSD                     | 40       | 0.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 39       | 0.59%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 38       | 0.57%   |
| Toshiba HDWD110 1TB                                 | 37       | 0.56%   |
| Seagate ST1000DM003-1CH162 1TB                      | 35       | 0.53%   |
| Crucial CT240BX500SSD1 240GB                        | 35       | 0.53%   |
| Seagate ST2000DM001-1ER164 2TB                      | 32       | 0.48%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 32       | 0.48%   |
| Seagate ST3500418AS 500GB                           | 31       | 0.47%   |
| SanDisk NVMe SSD Drive 500GB                        | 31       | 0.47%   |
| Kingston SV300S37A120G 120GB SSD                    | 31       | 0.47%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 29       | 0.44%   |
| Toshiba DT01ACA200 2TB                              | 28       | 0.42%   |
| Seagate Expansion 1TB                               | 28       | 0.42%   |
| Seagate ST4000DM004-2CV104 4TB                      | 27       | 0.41%   |
| Seagate ST2000DM001-1CH164 2TB                      | 26       | 0.39%   |
| Toshiba DT01ACA050 500GB                            | 25       | 0.38%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 24       | 0.36%   |
| Seagate ST31000524AS 1TB                            | 24       | 0.36%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 24       | 0.36%   |
| Samsung SSD 970 EVO Plus 500GB                      | 24       | 0.36%   |
| Samsung SSD 840 EVO 250GB                           | 24       | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 949      | 1523   | 37.85%  |
| WDC                 | 873      | 1431   | 34.82%  |
| Toshiba             | 269      | 348    | 10.73%  |
| Samsung Electronics | 139      | 216    | 5.54%   |
| Hitachi             | 134      | 195    | 5.35%   |
| HGST                | 62       | 97     | 2.47%   |
| Unknown             | 17       | 26     | 0.68%   |
| Maxtor              | 13       | 15     | 0.52%   |
| Fujitsu             | 8        | 9      | 0.32%   |
| Intenso             | 6        | 10     | 0.24%   |
| USB3.0              | 5        | 5      | 0.2%    |
| Apple               | 5        | 8      | 0.2%    |
| External            | 4        | 5      | 0.16%   |
| ASMT                | 4        | 7      | 0.16%   |
| HGST HTS            | 3        | 3      | 0.12%   |
| Hewlett-Packard     | 3        | 3      | 0.12%   |
| ASMedia             | 3        | 3      | 0.12%   |
| USB                 | 2        | 2      | 0.08%   |
| Maxone              | 2        | 2      | 0.08%   |
| JMicron Technology  | 2        | 5      | 0.08%   |
| SABRENT             | 1        | 1      | 0.04%   |
| MaxDigital          | 1        | 1      | 0.04%   |
| Lenovo              | 1        | 1      | 0.04%   |
| IBM/Hitachi         | 1        | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 551      | 842    | 26.19%  |
| Kingston            | 303      | 422    | 14.4%   |
| Crucial             | 261      | 404    | 12.4%   |
| SanDisk             | 171      | 224    | 8.13%   |
| WDC                 | 133      | 188    | 6.32%   |
| A-DATA Technology   | 72       | 103    | 3.42%   |
| China               | 56       | 80     | 2.66%   |
| Intel               | 54       | 72     | 2.57%   |
| OCZ                 | 39       | 53     | 1.85%   |
| PNY                 | 38       | 59     | 1.81%   |
| Patriot             | 33       | 42     | 1.57%   |
| SPCC                | 31       | 38     | 1.47%   |
| Toshiba             | 23       | 34     | 1.09%   |
| Intenso             | 21       | 31     | 1%      |
| Plextor             | 19       | 23     | 0.9%    |
| Corsair             | 19       | 28     | 0.9%    |
| Transcend           | 18       | 18     | 0.86%   |
| Lexar               | 18       | 20     | 0.86%   |
| GOODRAM             | 18       | 23     | 0.86%   |
| Micron Technology   | 17       | 20     | 0.81%   |
| Team                | 16       | 22     | 0.76%   |
| Apacer              | 15       | 17     | 0.71%   |
| SK hynix            | 11       | 12     | 0.52%   |
| Gigabyte Technology | 11       | 15     | 0.52%   |
| Seagate             | 10       | 13     | 0.48%   |
| KingDian            | 10       | 10     | 0.48%   |
| Leven               | 9        | 9      | 0.43%   |
| KingSpec            | 8        | 10     | 0.38%   |
| JMicron Technology  | 8        | 9      | 0.38%   |
| SABRENT             | 7        | 7      | 0.33%   |
| ASMT                | 7        | 11     | 0.33%   |
| LITEONIT            | 5        | 8      | 0.24%   |
| Apple               | 5        | 5      | 0.24%   |
| Verbatim            | 4        | 5      | 0.19%   |
| Mushkin             | 4        | 4      | 0.19%   |
| LITEON              | 4        | 4      | 0.19%   |
| Hoodisk             | 4        | 4      | 0.19%   |
| TO Exter            | 3        | 3      | 0.14%   |
| NGFF                | 3        | 3      | 0.14%   |
| Netac               | 3        | 4      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1826     | 3917   | 40.66%  |
| SSD     | 1637     | 2986   | 36.45%  |
| NVMe    | 935      | 1491   | 20.82%  |
| Unknown | 88       | 129    | 1.96%   |
| MMC     | 5        | 5      | 0.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 2335     | 6663   | 66.64%  |
| NVMe | 934      | 1490   | 26.66%  |
| SAS  | 230      | 370    | 6.56%   |
| MMC  | 5        | 5      | 0.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1736     | 3367   | 44.22%  |
| 0.51-1.0   | 1217     | 2014   | 31%     |
| 1.01-2.0   | 532      | 794    | 13.55%  |
| 3.01-4.0   | 179      | 283    | 4.56%   |
| 2.01-3.0   | 128      | 197    | 3.26%   |
| 4.01-10.0  | 112      | 211    | 2.85%   |
| 10.01-20.0 | 22       | 37     | 0.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 251-500        | 465      | 17.15%  |
| 101-250        | 462      | 17.04%  |
| 501-1000       | 452      | 16.67%  |
| 1001-2000      | 449      | 16.56%  |
| More than 3000 | 384      | 14.16%  |
| 2001-3000      | 235      | 8.67%   |
| 51-100         | 95       | 3.5%    |
| Unknown        | 95       | 3.5%    |
| 1-20           | 41       | 1.51%   |
| 21-50          | 33       | 1.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 438      | 15.52%  |
| 1-20           | 400      | 14.17%  |
| 501-1000       | 364      | 12.9%   |
| 21-50          | 340      | 12.05%  |
| 251-500        | 338      | 11.98%  |
| 51-100         | 309      | 10.95%  |
| 1001-2000      | 275      | 9.74%   |
| More than 3000 | 155      | 5.49%   |
| 2001-3000      | 107      | 3.79%   |
| Unknown        | 95       | 3.37%   |
| 0              | 1        | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 7        | 9      | 2.15%   |
| WDC WD5000AAKX-001CA0 500GB           | 5        | 7      | 1.53%   |
| WDC WD10EARS-00Y5B1 1TB               | 5        | 5      | 1.53%   |
| Samsung Electronics HD103SJ 1TB       | 5        | 5      | 1.53%   |
| Hitachi HDS721010CLA332 1TB           | 5        | 5      | 1.53%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 4        | 4      | 1.23%   |
| Seagate ST3500413AS 500GB             | 4        | 5      | 1.23%   |
| Seagate ST1000DX001-1CM162 1TB        | 4        | 6      | 1.23%   |
| Samsung Electronics SSD 960 EVO 250GB | 4        | 5      | 1.23%   |
| Samsung Electronics HD103UJ 1TB       | 4        | 6      | 1.23%   |
| WDC WD15EARS-00MVWB0 1TB              | 3        | 3      | 0.92%   |
| WDC WD10EZEX-00RKKA0 1TB              | 3        | 3      | 0.92%   |
| WDC WD10EZEX-00BN5A0 1TB              | 3        | 3      | 0.92%   |
| WDC WD10EARX-00N0YB0 1TB              | 3        | 4      | 0.92%   |
| Toshiba MQ01ABD050 500GB              | 3        | 3      | 0.92%   |
| Seagate ST4000DM000-1F2168 4TB        | 3        | 10     | 0.92%   |
| Seagate ST31000524AS 1TB              | 3        | 5      | 0.92%   |
| Seagate ST2000DM001-1CH164 2TB        | 3        | 3      | 0.92%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 3        | 3      | 0.92%   |
| Samsung Electronics SSD 870 EVO 1TB   | 3        | 3      | 0.92%   |
| Kingston SV300S37A120G 120GB SSD      | 3        | 3      | 0.92%   |
| Kingston SA400S37240G 240GB SSD       | 3        | 3      | 0.92%   |
| Crucial CT525MX300SSD1 528GB          | 3        | 3      | 0.92%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 2        | 2      | 0.61%   |
| WDC WD5000AAKX-003CA0 500GB           | 2        | 2      | 0.61%   |
| WDC WD5000AACS-00G8B1 500GB           | 2        | 2      | 0.61%   |
| WDC WD40EFRX-68WT0N0 4TB              | 2        | 3      | 0.61%   |
| WDC WD30EZRZ-00Z5HB0 3TB              | 2        | 2      | 0.61%   |
| WDC WD30EFRX-68EUZN0 3TB              | 2        | 2      | 0.61%   |
| WDC WD20EARX-00PASB0 2TB              | 2        | 2      | 0.61%   |
| WDC WD20EARS-00MVWB0 2TB              | 2        | 2      | 0.61%   |
| Seagate ST3250318AS 250GB             | 2        | 2      | 0.61%   |
| Seagate ST3250310AS 250GB             | 2        | 2      | 0.61%   |
| Seagate ST31000528AS 1TB              | 2        | 4      | 0.61%   |
| Seagate ST31000340NS 1TB              | 2        | 3      | 0.61%   |
| Seagate ST2000DX001-1CM164 2TB        | 2        | 2      | 0.61%   |
| Seagate ST2000DM008-2FR102 2TB        | 2        | 2      | 0.61%   |
| Seagate ST2000DM006-2DM164 2TB        | 2        | 2      | 0.61%   |
| Seagate ST2000DM001-1ER164 2TB        | 2        | 7      | 0.61%   |
| Seagate ST1000DX001-1NS162 1TB        | 2        | 3      | 0.61%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 98       | 114    | 31.21%  |
| Seagate             | 89       | 128    | 28.34%  |
| Samsung Electronics | 29       | 35     | 9.24%   |
| Hitachi             | 19       | 21     | 6.05%   |
| Kingston            | 12       | 12     | 3.82%   |
| Toshiba             | 11       | 14     | 3.5%    |
| SanDisk             | 9        | 12     | 2.87%   |
| Intel               | 9        | 10     | 2.87%   |
| HGST                | 7        | 7      | 2.23%   |
| Crucial             | 7        | 7      | 2.23%   |
| A-DATA Technology   | 5        | 5      | 1.59%   |
| OCZ                 | 2        | 2      | 0.64%   |
| Apacer              | 2        | 2      | 0.64%   |
| Transcend           | 1        | 1      | 0.32%   |
| SPCC                | 1        | 1      | 0.32%   |
| SK hynix            | 1        | 2      | 0.32%   |
| Phison              | 1        | 2      | 0.32%   |
| Patriot             | 1        | 1      | 0.32%   |
| Micron Technology   | 1        | 1      | 0.32%   |
| Maxtor              | 1        | 1      | 0.32%   |
| MaxDigital          | 1        | 1      | 0.32%   |
| KingSpec            | 1        | 2      | 0.32%   |
| Intenso             | 1        | 4      | 0.32%   |
| Hewlett-Packard     | 1        | 1      | 0.32%   |
| Fujitsu             | 1        | 1      | 0.32%   |
| Drevo               | 1        | 1      | 0.32%   |
| Corsair             | 1        | 5      | 0.32%   |
| ASMT                | 1        | 5      | 0.32%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 97       | 113    | 39.75%  |
| Seagate             | 88       | 125    | 36.07%  |
| Samsung Electronics | 19       | 24     | 7.79%   |
| Hitachi             | 19       | 21     | 7.79%   |
| Toshiba             | 11       | 14     | 4.51%   |
| HGST                | 7        | 7      | 2.87%   |
| Maxtor              | 1        | 1      | 0.41%   |
| MaxDigital          | 1        | 1      | 0.41%   |
| Fujitsu             | 1        | 1      | 0.41%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 225      | 307    | 76.79%  |
| SSD  | 58       | 79     | 19.8%   |
| NVMe | 10       | 12     | 3.41%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WDS256G1X0C-00ENX0 256GB      | 1        | 1      | 8.33%   |
| WDC WD3200BPVT-24ZEST0 320GB      | 1        | 1      | 8.33%   |
| WDC WD1600AAJS-65WAA0 160GB       | 1        | 1      | 8.33%   |
| Toshiba MQ01ABF050 500GB          | 1        | 1      | 8.33%   |
| Toshiba MK1059GSM 1TB             | 1        | 1      | 8.33%   |
| Seagate ST9640320AS 640GB         | 1        | 1      | 8.33%   |
| Seagate ST3500418AS 500GB         | 1        | 1      | 8.33%   |
| Seagate ST3250318AS 250GB         | 1        | 1      | 8.33%   |
| Seagate ST31000524AS 1TB          | 1        | 2      | 8.33%   |
| Samsung Electronics HD321HJ 320GB | 1        | 1      | 8.33%   |
| Kingston SV300S37A120G 120GB SSD  | 1        | 1      | 8.33%   |
| Hitachi HDS721010CLA332 1TB       | 1        | 1      | 8.33%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 4        | 5      | 33.33%  |
| WDC                 | 3        | 3      | 25%     |
| Toshiba             | 2        | 2      | 16.67%  |
| Samsung Electronics | 1        | 1      | 8.33%   |
| Kingston            | 1        | 1      | 8.33%   |
| Hitachi             | 1        | 1      | 8.33%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 1680     | 5354   | 57.18%  |
| Works    | 968      | 2763   | 32.95%  |
| Malfunc  | 278      | 398    | 9.46%   |
| Failed   | 12       | 13     | 0.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1341     | 34.22%  |
| AMD                              | 1185     | 30.24%  |
| Samsung Electronics              | 394      | 10.05%  |
| ASMedia Technology               | 162      | 4.13%   |
| SanDisk                          | 152      | 3.88%   |
| Phison Electronics               | 127      | 3.24%   |
| Marvell Technology Group         | 72       | 1.84%   |
| Micron/Crucial Technology        | 70       | 1.79%   |
| Kingston Technology Company      | 64       | 1.63%   |
| Silicon Motion                   | 63       | 1.61%   |
| JMicron Technology               | 60       | 1.53%   |
| ADATA Technology                 | 43       | 1.1%    |
| Nvidia                           | 37       | 0.94%   |
| Realtek Semiconductor            | 33       | 0.84%   |
| SK hynix                         | 19       | 0.48%   |
| Seagate Technology               | 10       | 0.26%   |
| Toshiba America Info Systems     | 9        | 0.23%   |
| LSI Logic / Symbios Logic        | 9        | 0.23%   |
| KIOXIA                           | 9        | 0.23%   |
| VIA Technologies                 | 8        | 0.2%    |
| Micron Technology                | 8        | 0.2%    |
| Lite-On Technology               | 6        | 0.15%   |
| Broadcom / LSI                   | 6        | 0.15%   |
| Silicon Image                    | 5        | 0.13%   |
| Adaptec                          | 4        | 0.1%    |
| Shenzhen Longsys Electronics     | 3        | 0.08%   |
| MAXIO Technology (Hangzhou)      | 3        | 0.08%   |
| Integrated Technology Express    | 3        | 0.08%   |
| Yangtze Memory Technologies      | 1        | 0.03%   |
| Union Memory (Shenzhen)          | 1        | 0.03%   |
| Transcend                        | 1        | 0.03%   |
| Silicon Integrated Systems [SiS] | 1        | 0.03%   |
| Promise Technology               | 1        | 0.03%   |
| PMC-Sierra                       | 1        | 0.03%   |
| OCZ Technology Group             | 1        | 0.03%   |
| Lenovo                           | 1        | 0.03%   |
| INNOGRIT                         | 1        | 0.03%   |
| HighPoint Technologies           | 1        | 0.03%   |
| Dell                             | 1        | 0.03%   |
| Biwin Storage Technology         | 1        | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 794      | 16.21%  |
| AMD 400 Series Chipset SATA Controller                                                  | 342      | 6.98%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 235      | 4.8%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 159      | 3.25%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 158      | 3.23%   |
| AMD 500 Series Chipset SATA Controller                                                  | 154      | 3.14%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 131      | 2.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 111      | 2.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 111      | 2.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 109      | 2.23%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 102      | 2.08%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 101      | 2.06%   |
| AMD 300 Series Chipset SATA Controller                                                  | 86       | 1.76%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 85       | 1.74%   |
| Intel SATA Controller [RAID mode]                                                       | 84       | 1.72%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 69       | 1.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 65       | 1.33%   |
| Phison E12 NVMe Controller                                                              | 63       | 1.29%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 62       | 1.27%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 54       | 1.1%    |
| AMD FCH SATA Controller D                                                               | 54       | 1.1%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 53       | 1.08%   |
| AMD X370 Series Chipset SATA Controller                                                 | 43       | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 42       | 0.86%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 42       | 0.86%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 42       | 0.86%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 41       | 0.84%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 41       | 0.84%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 40       | 0.82%   |
| Samsung NVMe SSD Controller 980                                                         | 39       | 0.8%    |
| Kingston Company A2000 NVMe SSD                                                         | 37       | 0.76%   |
| Intel SSD 660P Series                                                                   | 36       | 0.74%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 36       | 0.74%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 35       | 0.71%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 33       | 0.67%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 33       | 0.67%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 32       | 0.65%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 30       | 0.61%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 29       | 0.59%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 27       | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 2249     | 60.18%  |
| NVMe | 939      | 25.13%  |
| IDE  | 383      | 10.25%  |
| RAID | 143      | 3.83%   |
| SAS  | 20       | 0.54%   |
| SCSI | 3        | 0.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 1316     | 51.83%  |
| AMD    | 1223     | 48.17%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 132      | 5.17%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 79       | 3.1%    |
| AMD Ryzen 5 2600 Six-Core Processor         | 63       | 2.47%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 62       | 2.43%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 45       | 1.76%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 35       | 1.37%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 33       | 1.29%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 29       | 1.14%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 27       | 1.06%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 27       | 1.06%   |
| AMD FX-8350 Eight-Core Processor            | 26       | 1.02%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 25       | 0.98%   |
| AMD FX-6300 Six-Core Processor              | 25       | 0.98%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 24       | 0.94%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 24       | 0.94%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 23       | 0.9%    |
| Intel Core i7-7700K CPU @ 4.20GHz           | 23       | 0.9%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 23       | 0.9%    |
| Intel Core i5-9400F CPU @ 2.90GHz           | 23       | 0.9%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 23       | 0.9%    |
| Intel Core i7-8700 CPU @ 3.20GHz            | 22       | 0.86%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 22       | 0.86%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 20       | 0.78%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 20       | 0.78%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 20       | 0.78%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 20       | 0.78%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 20       | 0.78%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 19       | 0.74%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 19       | 0.74%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 19       | 0.74%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 18       | 0.71%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 18       | 0.71%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 18       | 0.71%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 18       | 0.71%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 17       | 0.67%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 17       | 0.67%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 16       | 0.63%   |
| AMD Ryzen 7 1700X Eight-Core Processor      | 16       | 0.63%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 16       | 0.63%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 15       | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 429      | 16.85%  |
| AMD Ryzen 5             | 422      | 16.58%  |
| Intel Core i7           | 352      | 13.83%  |
| AMD Ryzen 7             | 287      | 11.27%  |
| Intel Core i3           | 134      | 5.26%   |
| Intel Xeon              | 124      | 4.87%   |
| AMD Ryzen 9             | 124      | 4.87%   |
| AMD FX                  | 110      | 4.32%   |
| Other                   | 56       | 2.2%    |
| AMD Ryzen 3             | 47       | 1.85%   |
| Intel Core 2 Duo        | 43       | 1.69%   |
| Intel Celeron           | 35       | 1.37%   |
| Intel Pentium           | 32       | 1.26%   |
| AMD Ryzen Threadripper  | 29       | 1.14%   |
| AMD Phenom II X4        | 29       | 1.14%   |
| Intel Core 2 Quad       | 26       | 1.02%   |
| Intel Core i9           | 23       | 0.9%    |
| Intel Pentium Dual-Core | 22       | 0.86%   |
| AMD Athlon II X2        | 21       | 0.82%   |
| AMD A10                 | 19       | 0.75%   |
| AMD A8                  | 18       | 0.71%   |
| AMD A4                  | 16       | 0.63%   |
| AMD Athlon              | 14       | 0.55%   |
| AMD Phenom II X6        | 12       | 0.47%   |
| Intel Core 2            | 11       | 0.43%   |
| AMD Athlon 64 X2        | 11       | 0.43%   |
| AMD Athlon X4           | 9        | 0.35%   |
| AMD Athlon II X4        | 9        | 0.35%   |
| Intel Atom              | 8        | 0.31%   |
| AMD Ryzen 5 PRO         | 8        | 0.31%   |
| AMD Phenom              | 7        | 0.27%   |
| Intel Pentium Gold      | 6        | 0.24%   |
| Intel Pentium Dual      | 6        | 0.24%   |
| AMD Ryzen 7 PRO         | 6        | 0.24%   |
| Intel Genuine           | 5        | 0.2%    |
| AMD Athlon II X3        | 5        | 0.2%    |
| Intel Pentium D         | 4        | 0.16%   |
| AMD Sempron             | 4        | 0.16%   |
| AMD Phenom II X2        | 3        | 0.12%   |
| AMD E1                  | 3        | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 881      | 34.59%  |
| 6       | 603      | 23.67%  |
| 2       | 390      | 15.31%  |
| 8       | 381      | 14.96%  |
| 12      | 113      | 4.44%   |
| 16      | 71       | 2.79%   |
| 3       | 46       | 1.81%   |
| 1       | 28       | 1.1%    |
| 10      | 18       | 0.71%   |
| 24      | 7        | 0.27%   |
| 32      | 3        | 0.12%   |
| 20      | 2        | 0.08%   |
| 14      | 2        | 0.08%   |
| Unknown | 2        | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 2516     | 99.13%  |
| 2      | 22       | 0.87%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 1722     | 67.66%  |
| 1       | 821      | 32.26%  |
| Unknown | 2        | 0.08%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 2510     | 98.7%   |
| Unknown        | 33       | 1.3%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1315     | 50.02%  |
| 0x08701021 | 136      | 5.17%   |
| 0x306c3    | 103      | 3.92%   |
| 0x0800820d | 102      | 3.88%   |
| 0x08701013 | 76       | 2.89%   |
| 0x306a9    | 67       | 2.55%   |
| 0x206a7    | 63       | 2.4%    |
| 0x906ea    | 57       | 2.17%   |
| 0x506e3    | 51       | 1.94%   |
| 0x06000852 | 47       | 1.79%   |
| 0x1067a    | 35       | 1.33%   |
| 0x08001138 | 32       | 1.22%   |
| 0x906e9    | 28       | 1.07%   |
| 0x010000c8 | 24       | 0.91%   |
| 0x306f2    | 23       | 0.87%   |
| 0x0a201016 | 23       | 0.87%   |
| 0x0a201009 | 22       | 0.84%   |
| 0x206d7    | 20       | 0.76%   |
| 0x08108109 | 20       | 0.76%   |
| 0x08001137 | 19       | 0.72%   |
| 0x08101016 | 16       | 0.61%   |
| 0x06003106 | 14       | 0.53%   |
| 0xa0655    | 13       | 0.49%   |
| 0x906ed    | 13       | 0.49%   |
| 0x06001119 | 13       | 0.49%   |
| 0x90672    | 12       | 0.46%   |
| 0x106e5    | 12       | 0.46%   |
| 0x0a601203 | 11       | 0.42%   |
| 0x0a50000c | 11       | 0.42%   |
| 0x0a20120a | 11       | 0.42%   |
| 0x08600106 | 11       | 0.42%   |
| 0x08001129 | 9        | 0.34%   |
| 0xa0671    | 8        | 0.3%    |
| 0xa0653    | 8        | 0.3%    |
| 0x906ec    | 8        | 0.3%    |
| 0x906eb    | 8        | 0.3%    |
| 0x6fd      | 8        | 0.3%    |
| 0x206c2    | 8        | 0.3%    |
| 0x406f1    | 7        | 0.27%   |
| 0x10676    | 7        | 0.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 2            | 361      | 14.17%  |
| Haswell          | 267      | 10.48%  |
| KabyLake         | 254      | 9.97%   |
| Zen+             | 238      | 9.34%   |
| Zen              | 165      | 6.48%   |
| SandyBridge      | 162      | 6.36%   |
| IvyBridge        | 157      | 6.16%   |
| Zen 3            | 156      | 6.12%   |
| Piledriver       | 122      | 4.79%   |
| Skylake          | 116      | 4.55%   |
| Penryn           | 89       | 3.49%   |
| K10              | 87       | 3.41%   |
| Unknown          | 57       | 2.24%   |
| CometLake        | 56       | 2.2%    |
| Core             | 39       | 1.53%   |
| Nehalem          | 33       | 1.3%    |
| Westmere         | 32       | 1.26%   |
| Steamroller      | 26       | 1.02%   |
| Broadwell        | 19       | 0.75%   |
| Bulldozer        | 18       | 0.71%   |
| K8 Hammer        | 14       | 0.55%   |
| Alderlake Hybrid | 14       | 0.55%   |
| Excavator        | 8        | 0.31%   |
| Silvermont       | 7        | 0.27%   |
| Icelake          | 7        | 0.27%   |
| Goldmont plus    | 7        | 0.27%   |
| Bonnell          | 7        | 0.27%   |
| NetBurst         | 6        | 0.24%   |
| Goldmont         | 6        | 0.24%   |
| K10 Llano        | 5        | 0.2%    |
| Jaguar           | 4        | 0.16%   |
| Bobcat           | 4        | 0.16%   |
| TigerLake        | 2        | 0.08%   |
| Puma             | 2        | 0.08%   |
| Tremont          | 1        | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 1283     | 46.82%  |
| AMD                        | 975      | 35.58%  |
| Intel                      | 480      | 17.52%  |
| Matrox Electronics Systems | 1        | 0.04%   |
| ATI Technologies           | 1        | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 237      | 8.4%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 94       | 3.33%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 88       | 3.12%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 86       | 3.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 86       | 3.05%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 63       | 2.23%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 56       | 1.98%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 55       | 1.95%   |
| Nvidia GK208B [GeForce GT 710]                                              | 52       | 1.84%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 50       | 1.77%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 44       | 1.56%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 41       | 1.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 41       | 1.45%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 41       | 1.45%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 38       | 1.35%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 35       | 1.24%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 34       | 1.2%    |
| Intel HD Graphics 530                                                       | 34       | 1.2%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 33       | 1.17%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 31       | 1.1%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 30       | 1.06%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 30       | 1.06%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 29       | 1.03%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 29       | 1.03%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 26       | 0.92%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 25       | 0.89%   |
| Intel HD Graphics 630                                                       | 24       | 0.85%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 24       | 0.85%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 23       | 0.81%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 23       | 0.81%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 23       | 0.81%   |
| Nvidia GK208B [GeForce GT 730]                                              | 22       | 0.78%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 22       | 0.78%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 21       | 0.74%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 20       | 0.71%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 20       | 0.71%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 20       | 0.71%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 20       | 0.71%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 19       | 0.67%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 19       | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Nvidia         | 1169     | 45.31%  |
| 1 x AMD            | 886      | 34.34%  |
| 1 x Intel          | 353      | 13.68%  |
| Intel + Nvidia     | 48       | 1.86%   |
| AMD + Nvidia       | 41       | 1.59%   |
| 2 x AMD            | 40       | 1.55%   |
| 2 x Nvidia         | 26       | 1.01%   |
| Intel + AMD        | 14       | 0.54%   |
| 1 x Matrox         | 1        | 0.04%   |
| Intel + 2 x Nvidia | 1        | 0.04%   |
| Intel + 2 x AMD    | 1        | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1513     | 58.85%  |
| Proprietary | 1045     | 40.65%  |
| Unknown     | 13       | 0.51%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1047     | 39.96%  |
| 7.01-8.0   | 400      | 15.27%  |
| 1.01-2.0   | 314      | 11.98%  |
| 3.01-4.0   | 272      | 10.38%  |
| 5.01-6.0   | 177      | 6.76%   |
| 0.51-1.0   | 157      | 5.99%   |
| 8.01-16.0  | 105      | 4.01%   |
| 0.01-0.5   | 85       | 3.24%   |
| 2.01-3.0   | 47       | 1.79%   |
| 16.01-24.0 | 14       | 0.53%   |
| 4.01-5.0   | 2        | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 477      | 15.74%  |
| Goldstar             | 321      | 10.59%  |
| Dell                 | 284      | 9.37%   |
| Acer                 | 242      | 7.98%   |
| AOC                  | 188      | 6.2%    |
| Ancor Communications | 179      | 5.91%   |
| BenQ                 | 176      | 5.81%   |
| Hewlett-Packard      | 147      | 4.85%   |
| Philips              | 125      | 4.12%   |
| LG Electronics       | 99       | 3.27%   |
| ViewSonic            | 67       | 2.21%   |
| ASUSTek Computer     | 64       | 2.11%   |
| Lenovo               | 49       | 1.62%   |
| Iiyama               | 43       | 1.42%   |
| Unknown              | 42       | 1.39%   |
| Unknown              | 30       | 0.99%   |
| Sony                 | 27       | 0.89%   |
| Vizio                | 21       | 0.69%   |
| MSI                  | 20       | 0.66%   |
| Eizo                 | 18       | 0.59%   |
| AUS                  | 17       | 0.56%   |
| NEC Computers        | 15       | 0.49%   |
| Idek Iiyama          | 15       | 0.49%   |
| Gigabyte Technology  | 15       | 0.49%   |
| Fujitsu Siemens      | 15       | 0.49%   |
| Sceptre Tech         | 12       | 0.4%    |
| Medion               | 12       | 0.4%    |
| Sharp                | 10       | 0.33%   |
| Vestel Elektronik    | 8        | 0.26%   |
| Microstep            | 8        | 0.26%   |
| Lenovo Group Limited | 8        | 0.26%   |
| HannStar             | 8        | 0.26%   |
| Toshiba              | 7        | 0.23%   |
| Pixio                | 7        | 0.23%   |
| Panasonic            | 7        | 0.23%   |
| KTC                  | 6        | 0.2%    |
| HPN                  | 6        | 0.2%    |
| Apple                | 6        | 0.2%    |
| VIZ                  | 5        | 0.16%   |
| Vestel               | 5        | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown                                                               | 30       | 0.91%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 20       | 0.61%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 19       | 0.58%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 18       | 0.55%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 13       | 0.39%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 12       | 0.36%   |
| AOC 27P2DG5 AOC2702 1920x1080 598x336mm 27.0-inch                     | 11       | 0.33%   |
| Samsung Electronics U28E590 SAM0C4D 1680x1050 610x350mm 27.7-inch     | 9        | 0.27%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 9        | 0.27%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 9        | 0.27%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                    | 9        | 0.27%   |
| Vestel Elektronik 43UHD_LCD_TV VES3700 3840x2160 950x540mm 43.0-inch  | 8        | 0.24%   |
| Goldstar LG HDR WFHD GSM7715 2560x1080 800x340mm 34.2-inch            | 8        | 0.24%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 8        | 0.24%   |
| AOC Q27P1B AOC2701 2560x1440 597x336mm 27.0-inch                      | 8        | 0.24%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                      | 8        | 0.24%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 7        | 0.21%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 7        | 0.21%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 7        | 0.21%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                     | 7        | 0.21%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 7        | 0.21%   |
| Ancor Communications VG248 ACI24A4 1920x1080 530x300mm 24.0-inch      | 7        | 0.21%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 7        | 0.21%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                       | 6        | 0.18%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 6        | 0.18%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                | 6        | 0.18%   |
| Goldstar E2350 GSM5791 1920x1080 510x290mm 23.1-inch                  | 6        | 0.18%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                | 6        | 0.18%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 6        | 0.18%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 6        | 0.18%   |
| ASUSTek Computer VA326 AUS32FA 1920x1080 698x393mm 31.5-inch          | 6        | 0.18%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 6        | 0.18%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                        | 6        | 0.18%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 6        | 0.18%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 6        | 0.18%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 6        | 0.18%   |
| Ancor Communications ASUS MG279 ACI27A7 2560x1440 597x336mm 27.0-inch | 6        | 0.18%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch  | 5        | 0.15%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 5        | 0.15%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 5        | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1289     | 43.53%  |
| 2560x1440 (QHD)    | 289      | 9.76%   |
| 3840x2160 (4K)     | 275      | 9.29%   |
| Unknown            | 170      | 5.74%   |
| 1680x1050 (WSXGA+) | 118      | 3.99%   |
| 1280x1024 (SXGA)   | 117      | 3.95%   |
| 3440x1440          | 78       | 2.63%   |
| 1366x768 (WXGA)    | 78       | 2.63%   |
| 1920x1200 (WUXGA)  | 77       | 2.6%    |
| 1440x900 (WXGA+)   | 72       | 2.43%   |
| 3840x1080          | 66       | 2.23%   |
| 2560x1080          | 66       | 2.23%   |
| 1600x900 (HD+)     | 58       | 1.96%   |
| 1360x768           | 27       | 0.91%   |
| 4480x1440          | 12       | 0.41%   |
| 5120x1440          | 11       | 0.37%   |
| 1920x540           | 11       | 0.37%   |
| 5760x1080          | 10       | 0.34%   |
| 1280x720 (HD)      | 9        | 0.3%    |
| 1024x768 (XGA)     | 9        | 0.3%    |
| 5760x2160          | 7        | 0.24%   |
| 3600x1080          | 7        | 0.24%   |
| 2560x1600          | 7        | 0.24%   |
| 3840x1600          | 6        | 0.2%    |
| 3360x1080          | 5        | 0.17%   |
| 3200x1080          | 5        | 0.17%   |
| 1600x1200          | 5        | 0.17%   |
| 7680x2160          | 4        | 0.14%   |
| 6400x2160          | 4        | 0.14%   |
| 3840x1200          | 4        | 0.14%   |
| 3520x1080          | 4        | 0.14%   |
| 3360x1050          | 3        | 0.1%    |
| 3286x1080          | 3        | 0.1%    |
| 7680x1080          | 2        | 0.07%   |
| 5504x1440          | 2        | 0.07%   |
| 5120x1080          | 2        | 0.07%   |
| 4480x1080          | 2        | 0.07%   |
| 4240x1440          | 2        | 0.07%   |
| 2960x900           | 2        | 0.07%   |
| 2944x1080          | 2        | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 517      | 17.72%  |
| 24      | 414      | 14.19%  |
| 27      | 409      | 14.02%  |
| 23      | 334      | 11.45%  |
| 21      | 299      | 10.25%  |
| 19      | 125      | 4.29%   |
| 31      | 118      | 4.05%   |
| 34      | 111      | 3.81%   |
| 22      | 80       | 2.74%   |
| 18      | 72       | 2.47%   |
| 20      | 64       | 2.19%   |
| 17      | 53       | 1.82%   |
| 84      | 34       | 1.17%   |
| 40      | 23       | 0.79%   |
| 72      | 21       | 0.72%   |
| 32      | 21       | 0.72%   |
| 25      | 20       | 0.69%   |
| 54      | 19       | 0.65%   |
| 15      | 15       | 0.51%   |
| 28      | 13       | 0.45%   |
| 65      | 12       | 0.41%   |
| 48      | 11       | 0.38%   |
| 49      | 10       | 0.34%   |
| 33      | 9        | 0.31%   |
| 43      | 8        | 0.27%   |
| 37      | 8        | 0.27%   |
| 46      | 7        | 0.24%   |
| 42      | 7        | 0.24%   |
| 29      | 7        | 0.24%   |
| 26      | 7        | 0.24%   |
| 12      | 7        | 0.24%   |
| 36      | 6        | 0.21%   |
| 35      | 6        | 0.21%   |
| 14      | 6        | 0.21%   |
| 47      | 5        | 0.17%   |
| 39      | 5        | 0.17%   |
| 60      | 4        | 0.14%   |
| 52      | 4        | 0.14%   |
| 16      | 4        | 0.14%   |
| 64      | 3        | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 1033     | 37.01%  |
| 401-500     | 556      | 19.92%  |
| Unknown     | 517      | 18.52%  |
| 601-700     | 178      | 6.38%   |
| 701-800     | 147      | 5.27%   |
| 351-400     | 81       | 2.9%    |
| 1001-1500   | 76       | 2.72%   |
| 301-350     | 65       | 2.33%   |
| 1501-2000   | 60       | 2.15%   |
| 801-900     | 47       | 1.68%   |
| 201-300     | 16       | 0.57%   |
| 901-1000    | 15       | 0.54%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1598     | 60.42%  |
| Unknown | 485      | 18.34%  |
| 16/10   | 259      | 9.79%   |
| 21/9    | 122      | 4.61%   |
| 5/4     | 111      | 4.2%    |
| 4/3     | 29       | 1.1%    |
| 3/2     | 18       | 0.68%   |
| 32/9    | 12       | 0.45%   |
| 6/5     | 5        | 0.19%   |
| 1.96    | 2        | 0.08%   |
| 3.20    | 1        | 0.04%   |
| 1.03    | 1        | 0.04%   |
| 0.80    | 1        | 0.04%   |
| 0.56    | 1        | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 902      | 31.63%  |
| Unknown        | 517      | 18.13%  |
| 301-350        | 411      | 14.41%  |
| 351-500        | 279      | 9.78%   |
| 151-200        | 256      | 8.98%   |
| 251-300        | 145      | 5.08%   |
| More than 1000 | 114      | 4%      |
| 141-150        | 101      | 3.54%   |
| 501-1000       | 84       | 2.95%   |
| 101-110        | 18       | 0.63%   |
| 131-140        | 8        | 0.28%   |
| 71-80          | 7        | 0.25%   |
| 81-90          | 3        | 0.11%   |
| 51-60          | 2        | 0.07%   |
| 111-120        | 2        | 0.07%   |
| 91-100         | 2        | 0.07%   |
| 121-130        | 1        | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 1431     | 52.82%  |
| 101-120 | 518      | 19.12%  |
| Unknown | 517      | 19.08%  |
| 121-160 | 98       | 3.62%   |
| 1-50    | 93       | 3.43%   |
| 161-240 | 52       | 1.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1875     | 72.12%  |
| 2     | 601      | 23.12%  |
| 3     | 83       | 3.19%   |
| 0     | 35       | 1.35%   |
| 4     | 6        | 0.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1561     | 42.88%  |
| Intel                                  | 1144     | 31.43%  |
| Qualcomm Atheros                       | 191      | 5.25%   |
| Broadcom                               | 102      | 2.8%    |
| Ralink Technology                      | 92       | 2.53%   |
| TP-Link                                | 91       | 2.5%    |
| Microsoft                              | 45       | 1.24%   |
| MediaTek                               | 35       | 0.96%   |
| Nvidia                                 | 31       | 0.85%   |
| Aquantia                               | 31       | 0.85%   |
| Ralink                                 | 26       | 0.71%   |
| Qualcomm Atheros Communications        | 25       | 0.69%   |
| Samsung Electronics                    | 21       | 0.58%   |
| Xiaomi                                 | 18       | 0.49%   |
| ASUSTek Computer                       | 17       | 0.47%   |
| NetGear                                | 16       | 0.44%   |
| D-Link                                 | 16       | 0.44%   |
| Marvell Technology Group               | 15       | 0.41%   |
| Huawei Technologies                    | 13       | 0.36%   |
| Broadcom Limited                       | 12       | 0.33%   |
| Linksys                                | 11       | 0.3%    |
| D-Link System                          | 9        | 0.25%   |
| Microchip Technology                   | 8        | 0.22%   |
| Edimax Technology                      | 7        | 0.19%   |
| Mellanox Technologies                  | 6        | 0.16%   |
| Motorola PCS                           | 5        | 0.14%   |
| ASIX Electronics                       | 5        | 0.14%   |
| ZyXEL Communications                   | 4        | 0.11%   |
| InterBiometrics                        | 4        | 0.11%   |
| T & A Mobile Phones                    | 3        | 0.08%   |
| Sony Ericsson Mobile Communications AB | 3        | 0.08%   |
| SEGGER                                 | 3        | 0.08%   |
| Qualcomm                               | 3        | 0.08%   |
| OPPO Electronics                       | 3        | 0.08%   |
| OnePlus Technology (Shenzhen)          | 3        | 0.08%   |
| JMicron Technology                     | 3        | 0.08%   |
| IMC Networks                           | 3        | 0.08%   |
| Google                                 | 3        | 0.08%   |
| Belkin Components                      | 3        | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3]  | 3        | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1270     | 30.32%  |
| Intel I211 Gigabit Network Connection                             | 284      | 6.78%   |
| Intel Wi-Fi 6 AX200                                               | 190      | 4.54%   |
| Realtek RTL8125 2.5GbE Controller                                 | 147      | 3.51%   |
| Intel Ethernet Connection (2) I219-V                              | 124      | 2.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 81       | 1.93%   |
| Intel Ethernet Controller I225-V                                  | 80       | 1.91%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 64       | 1.53%   |
| Intel Ethernet Connection (7) I219-V                              | 57       | 1.36%   |
| Intel Wireless-AC 9260                                            | 49       | 1.17%   |
| Intel 82579V Gigabit Network Connection                           | 47       | 1.12%   |
| Intel Ethernet Connection (2) I218-V                              | 43       | 1.03%   |
| Intel Ethernet Connection I217-LM                                 | 39       | 0.93%   |
| Intel Ethernet Connection I217-V                                  | 38       | 0.91%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 33       | 0.79%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 32       | 0.76%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 32       | 0.76%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 31       | 0.74%   |
| Ralink MT7601U Wireless Adapter                                   | 30       | 0.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 29       | 0.69%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 27       | 0.64%   |
| Realtek 802.11ac NIC                                              | 26       | 0.62%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 25       | 0.6%    |
| Qualcomm Atheros AR9271 802.11n                                   | 25       | 0.6%    |
| Microsoft Xbox 360 Wireless Adapter                               | 25       | 0.6%    |
| Intel 82574L Gigabit Network Connection                           | 23       | 0.55%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 22       | 0.53%   |
| Intel Wireless 8265 / 8275                                        | 22       | 0.53%   |
| Intel Wireless 7265                                               | 22       | 0.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 20       | 0.48%   |
| Nvidia MCP61 Ethernet                                             | 20       | 0.48%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 19       | 0.45%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 18       | 0.43%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18       | 0.43%   |
| Ralink RT5370 Wireless Adapter                                    | 17       | 0.41%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 17       | 0.41%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 17       | 0.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 16       | 0.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 16       | 0.38%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 16       | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 470      | 36.15%  |
| Realtek Semiconductor                 | 264      | 20.31%  |
| Qualcomm Atheros                      | 96       | 7.38%   |
| Ralink Technology                     | 92       | 7.08%   |
| TP-Link                               | 81       | 6.23%   |
| Broadcom                              | 65       | 5%      |
| Microsoft                             | 45       | 3.46%   |
| MediaTek                              | 29       | 2.23%   |
| Ralink                                | 26       | 2%      |
| Qualcomm Atheros Communications       | 25       | 1.92%   |
| ASUSTek Computer                      | 17       | 1.31%   |
| NetGear                               | 16       | 1.23%   |
| D-Link                                | 16       | 1.23%   |
| Linksys                               | 11       | 0.85%   |
| Edimax Technology                     | 7        | 0.54%   |
| D-Link System                         | 6        | 0.46%   |
| Broadcom Limited                      | 5        | 0.38%   |
| ZyXEL Communications                  | 4        | 0.31%   |
| IMC Networks                          | 3        | 0.23%   |
| Belkin Components                     | 3        | 0.23%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3        | 0.23%   |
| ZyDAS                                 | 2        | 0.15%   |
| Realtek                               | 2        | 0.15%   |
| Mercucys                              | 2        | 0.15%   |
| AVM                                   | 2        | 0.15%   |
| Xiaomi                                | 1        | 0.08%   |
| Wacom                                 | 1        | 0.08%   |
| Senao                                 | 1        | 0.08%   |
| Samsung Electronics                   | 1        | 0.08%   |
| Philips (or NXP)                      | 1        | 0.08%   |
| Marvell Technology Group              | 1        | 0.08%   |
| Fujitsu Siemens Computers             | 1        | 0.08%   |
| Encore Electronics                    | 1        | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 190      | 14.48%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 64       | 4.88%   |
| Intel Wireless-AC 9260                                         | 49       | 3.73%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 32       | 2.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 32       | 2.44%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 31       | 2.36%   |
| Ralink MT7601U Wireless Adapter                                | 30       | 2.29%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 29       | 2.21%   |
| Realtek 802.11ac NIC                                           | 26       | 1.98%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 25       | 1.91%   |
| Qualcomm Atheros AR9271 802.11n                                | 25       | 1.91%   |
| Microsoft Xbox 360 Wireless Adapter                            | 25       | 1.91%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 22       | 1.68%   |
| Intel Wireless 8265 / 8275                                     | 22       | 1.68%   |
| Intel Wireless 7265                                            | 22       | 1.68%   |
| Ralink RT5370 Wireless Adapter                                 | 17       | 1.3%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 17       | 1.3%    |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 17       | 1.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 16       | 1.22%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 16       | 1.22%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 16       | 1.22%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 16       | 1.22%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 15       | 1.14%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 13       | 0.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 13       | 0.99%   |
| Microsoft XBOX ACC                                             | 13       | 0.99%   |
| Intel Wireless 3165                                            | 12       | 0.91%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 11       | 0.84%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 11       | 0.84%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 11       | 0.84%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 11       | 0.84%   |
| Intel Wireless 7260                                            | 11       | 0.84%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 10       | 0.76%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 10       | 0.76%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 10       | 0.76%   |
| TP-Link 802.11ac NIC                                           | 9        | 0.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 9        | 0.69%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 9        | 0.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 9        | 0.69%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 9        | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 1468     | 53.79%  |
| Intel                                  | 925      | 33.9%   |
| Qualcomm Atheros                       | 110      | 4.03%   |
| Broadcom                               | 40       | 1.47%   |
| Nvidia                                 | 31       | 1.14%   |
| Aquantia                               | 31       | 1.14%   |
| Xiaomi                                 | 17       | 0.62%   |
| Marvell Technology Group               | 14       | 0.51%   |
| Samsung Electronics                    | 11       | 0.4%    |
| Huawei Technologies                    | 11       | 0.4%    |
| TP-Link                                | 10       | 0.37%   |
| Broadcom Limited                       | 7        | 0.26%   |
| Mellanox Technologies                  | 6        | 0.22%   |
| ASIX Electronics                       | 5        | 0.18%   |
| MediaTek                               | 4        | 0.15%   |
| Sony Ericsson Mobile Communications AB | 3        | 0.11%   |
| OPPO Electronics                       | 3        | 0.11%   |
| JMicron Technology                     | 3        | 0.11%   |
| Google                                 | 3        | 0.11%   |
| D-Link System                          | 3        | 0.11%   |
| T & A Mobile Phones                    | 2        | 0.07%   |
| Sundance Technology Inc / IC Plus      | 2        | 0.07%   |
| Qualcomm                               | 2        | 0.07%   |
| OnePlus Technology (Shenzhen)          | 2        | 0.07%   |
| National Semiconductor                 | 2        | 0.07%   |
| Motorola PCS                           | 2        | 0.07%   |
| HMD Global                             | 2        | 0.07%   |
| ZTE WCDMA Technologies MSM             | 1        | 0.04%   |
| VIA Technologies                       | 1        | 0.04%   |
| Silicon Integrated Systems [SiS]       | 1        | 0.04%   |
| NetXen Incorporated                    | 1        | 0.04%   |
| LG Electronics                         | 1        | 0.04%   |
| ICS Advent                             | 1        | 0.04%   |
| Foxconn / Hon Hai                      | 1        | 0.04%   |
| DisplayLink                            | 1        | 0.04%   |
| Apple                                  | 1        | 0.04%   |
| Accton Technology                      | 1        | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1270     | 44.96%  |
| Intel I211 Gigabit Network Connection                             | 284      | 10.05%  |
| Realtek RTL8125 2.5GbE Controller                                 | 147      | 5.2%    |
| Intel Ethernet Connection (2) I219-V                              | 124      | 4.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 81       | 2.87%   |
| Intel Ethernet Controller I225-V                                  | 80       | 2.83%   |
| Intel Ethernet Connection (7) I219-V                              | 57       | 2.02%   |
| Intel 82579V Gigabit Network Connection                           | 47       | 1.66%   |
| Intel Ethernet Connection (2) I218-V                              | 43       | 1.52%   |
| Intel Ethernet Connection I217-LM                                 | 39       | 1.38%   |
| Intel Ethernet Connection I217-V                                  | 38       | 1.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 33       | 1.17%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 27       | 0.96%   |
| Intel 82574L Gigabit Network Connection                           | 23       | 0.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 20       | 0.71%   |
| Nvidia MCP61 Ethernet                                             | 20       | 0.71%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 19       | 0.67%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 18       | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 18       | 0.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 16       | 0.57%   |
| Intel Ethernet Connection (2) I219-LM                             | 16       | 0.57%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 14       | 0.5%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 14       | 0.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 13       | 0.46%   |
| Intel I210 Gigabit Network Connection                             | 13       | 0.46%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 11       | 0.39%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 11       | 0.39%   |
| Intel Ethernet Connection (7) I219-LM                             | 10       | 0.35%   |
| Intel Ethernet Connection (11) I219-V                             | 10       | 0.35%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 10       | 0.35%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 9        | 0.32%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 9        | 0.32%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 9        | 0.32%   |
| Intel Ethernet Connection (14) I219-V                             | 9        | 0.32%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 8        | 0.28%   |
| Intel Ethernet Connection (2) I218-LM                             | 8        | 0.28%   |
| Intel Ethernet Connection (12) I219-V                             | 7        | 0.25%   |
| Huawei ANE-LX1                                                    | 7        | 0.25%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 7        | 0.25%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 6        | 0.21%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2512     | 66.79%  |
| WiFi     | 1199     | 31.88%  |
| Modem    | 42       | 1.12%   |
| Unknown  | 8        | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2025     | 76.59%  |
| WiFi     | 619      | 23.41%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1606     | 62.66%  |
| 2     | 804      | 31.37%  |
| 3     | 115      | 4.49%   |
| 0     | 21       | 0.82%   |
| 5     | 8        | 0.31%   |
| 4     | 7        | 0.27%   |
| 8     | 1        | 0.04%   |
| 7     | 1        | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2122     | 82.06%  |
| Yes  | 464      | 17.94%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 442      | 40.48%  |
| Cambridge Silicon Radio         | 304      | 27.84%  |
| ASUSTek Computer                | 101      | 9.25%   |
| Realtek Semiconductor           | 72       | 6.59%   |
| Broadcom                        | 53       | 4.85%   |
| Qualcomm Atheros Communications | 16       | 1.47%   |
| IMC Networks                    | 15       | 1.37%   |
| Apple                           | 14       | 1.28%   |
| TP-Link                         | 12       | 1.1%    |
| MediaTek                        | 10       | 0.92%   |
| Foxconn / Hon Hai               | 8        | 0.73%   |
| Edimax Technology               | 8        | 0.73%   |
| Dynex                           | 6        | 0.55%   |
| HTC (High Tech Computer)        | 5        | 0.46%   |
| Realtek                         | 4        | 0.37%   |
| Lite-On Technology              | 4        | 0.37%   |
| Conwise Technology              | 4        | 0.37%   |
| SINO WEALTH                     | 3        | 0.27%   |
| Integrated System Solution      | 3        | 0.27%   |
| Belkin Components               | 3        | 0.27%   |
| Ralink                          | 2        | 0.18%   |
| Sitecom Europe                  | 1        | 0.09%   |
| Micro Star International        | 1        | 0.09%   |
| D-Link                          | 1        | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 304      | 27.74%  |
| Intel AX200 Bluetooth                                                | 175      | 15.97%  |
| Intel Bluetooth wireless interface                                   | 74       | 6.75%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 63       | 5.75%   |
| Realtek Bluetooth Radio                                              | 58       | 5.29%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 49       | 4.47%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 39       | 3.56%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 35       | 3.19%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 34       | 3.1%    |
| Intel AX201 Bluetooth                                                | 25       | 2.28%   |
| ASUS Bluetooth Radio                                                 | 17       | 1.55%   |
| Intel AX210 Bluetooth                                                | 15       | 1.37%   |
| ASUS ASUS USB-BT500                                                  | 15       | 1.37%   |
| ASUS Bluetooth Adapter                                               | 13       | 1.19%   |
| TP-Link UB500 Adapter                                                | 12       | 1.09%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 10       | 0.91%   |
| MediaTek Wireless_Device                                             | 10       | 0.91%   |
| IMC Networks Bluetooth Radio                                         | 10       | 0.91%   |
| ASUS BCM20702A0                                                      | 10       | 0.91%   |
| Qualcomm Atheros  Bluetooth Device                                   | 7        | 0.64%   |
| Apple Bluetooth Host Controller                                      | 7        | 0.64%   |
| Intel Bluetooth Device                                               | 6        | 0.55%   |
| Edimax Bluetooth Adapter                                             | 6        | 0.55%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 6        | 0.55%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 6        | 0.55%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 5        | 0.46%   |
| Realtek Bluetooth Radio                                              | 4        | 0.36%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 4        | 0.36%   |
| Foxconn / Hon Hai Wireless_Device                                    | 4        | 0.36%   |
| Conwise CW6622                                                       | 4        | 0.36%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 4        | 0.36%   |
| SINO WEALTH RK Bluetooth Keyboar                                     | 3        | 0.27%   |
| Realtek Bluetooth 5.1 Radio                                          | 3        | 0.27%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 3        | 0.27%   |
| Broadcom Bluetooth 2.0+eDR dongle                                    | 3        | 0.27%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 3        | 0.27%   |
| Apple Bluetooth HCI MacBookPro (HID mode)                            | 3        | 0.27%   |
| Ralink RT3290 Bluetooth                                              | 2        | 0.18%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 2        | 0.18%   |
| Lite-On Bluetooth Device                                             | 2        | 0.18%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 1449     | 29.28%  |
| Intel                    | 1272     | 25.71%  |
| Nvidia                   | 1228     | 24.82%  |
| C-Media Electronics      | 183      | 3.7%    |
| Creative Labs            | 71       | 1.43%   |
| Logitech                 | 69       | 1.39%   |
| Kingston Technology      | 47       | 0.95%   |
| JMTek                    | 38       | 0.77%   |
| Texas Instruments        | 35       | 0.71%   |
| Corsair                  | 33       | 0.67%   |
| SteelSeries ApS          | 31       | 0.63%   |
| Creative Technology      | 30       | 0.61%   |
| Focusrite-Novation       | 29       | 0.59%   |
| ASUSTek Computer         | 27       | 0.55%   |
| Razer USA                | 26       | 0.53%   |
| Blue Microphones         | 26       | 0.53%   |
| Generalplus Technology   | 24       | 0.49%   |
| BEHRINGER International  | 20       | 0.4%    |
| Sony                     | 14       | 0.28%   |
| Plantronics              | 14       | 0.28%   |
| GYROCOM C&C              | 12       | 0.24%   |
| Realtek Semiconductor    | 11       | 0.22%   |
| VIA Technologies         | 9        | 0.18%   |
| M-Audio                  | 9        | 0.18%   |
| Turtle Beach             | 8        | 0.16%   |
| Samson Technologies      | 8        | 0.16%   |
| XMOS                     | 7        | 0.14%   |
| SAVITECH                 | 7        | 0.14%   |
| RODE Microphones         | 7        | 0.14%   |
| Micro Star International | 7        | 0.14%   |
| GN Netcom                | 7        | 0.14%   |
| Giga-Byte Technology     | 7        | 0.14%   |
| Dell                     | 7        | 0.14%   |
| Audio-Technica           | 7        | 0.14%   |
| Yamaha                   | 6        | 0.12%   |
| DSEA A/S                 | 6        | 0.12%   |
| Astro Gaming             | 6        | 0.12%   |
| Valve Software           | 5        | 0.1%    |
| Microsoft                | 5        | 0.1%    |
| Elgato Systems           | 5        | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 436      | 7.52%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 302      | 5.21%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 239      | 4.12%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 169      | 2.91%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 166      | 2.86%   |
| AMD Family 17h/19h HD Audio Controller                                     | 163      | 2.81%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 157      | 2.71%   |
| Intel 200 Series PCH HD Audio                                              | 138      | 2.38%   |
| Nvidia GP104 High Definition Audio Controller                              | 128      | 2.21%   |
| Nvidia GP106 High Definition Audio Controller                              | 124      | 2.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 114      | 1.97%   |
| AMD Navi 10 HDMI Audio                                                     | 112      | 1.93%   |
| Nvidia GP107GL High Definition Audio Controller                            | 111      | 1.91%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 110      | 1.9%    |
| Intel Cannon Lake PCH cAVS                                                 | 101      | 1.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 94       | 1.62%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 82       | 1.41%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 77       | 1.33%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 71       | 1.22%   |
| Nvidia TU116 High Definition Audio Controller                              | 70       | 1.21%   |
| AMD FCH Azalia Controller                                                  | 69       | 1.19%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 69       | 1.19%   |
| Nvidia GM204 High Definition Audio Controller                              | 64       | 1.1%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 62       | 1.07%   |
| Nvidia TU104 HD Audio Controller                                           | 60       | 1.03%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 60       | 1.03%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 60       | 1.03%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 59       | 1.02%   |
| Nvidia TU106 High Definition Audio Controller                              | 55       | 0.95%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 52       | 0.9%    |
| Nvidia GA104 High Definition Audio Controller                              | 46       | 0.79%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 46       | 0.79%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 45       | 0.78%   |
| Nvidia GP108 High Definition Audio Controller                              | 44       | 0.76%   |
| Nvidia GM206 High Definition Audio Controller                              | 43       | 0.74%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 42       | 0.72%   |
| Nvidia GK104 HDMI Audio Controller                                         | 41       | 0.71%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 37       | 0.64%   |
| Nvidia GP102 HDMI Audio Controller                                         | 35       | 0.6%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 34       | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Corsair                      | 306      | 18.69%  |
| Kingston                     | 294      | 17.96%  |
| G.Skill                      | 228      | 13.93%  |
| Unknown                      | 196      | 11.97%  |
| Crucial                      | 149      | 9.1%    |
| Samsung Electronics          | 96       | 5.86%   |
| SK hynix                     | 61       | 3.73%   |
| Micron Technology            | 54       | 3.3%    |
| Team                         | 41       | 2.5%    |
| A-DATA Technology            | 41       | 2.5%    |
| Patriot                      | 31       | 1.89%   |
| Goodram                      | 12       | 0.73%   |
| Nanya Technology             | 11       | 0.67%   |
| Elpida                       | 10       | 0.61%   |
| Unknown                      | 9        | 0.55%   |
| Ramaxel Technology           | 8        | 0.49%   |
| Unknown (ABCD)               | 7        | 0.43%   |
| Kllisre                      | 5        | 0.31%   |
| GeIL                         | 5        | 0.31%   |
| Transcend                    | 4        | 0.24%   |
| Smart                        | 4        | 0.24%   |
| Silicon Power                | 4        | 0.24%   |
| PNY                          | 4        | 0.24%   |
| AMD                          | 4        | 0.24%   |
| Patriot Memory (PDP Systems) | 3        | 0.18%   |
| Kingmax                      | 3        | 0.18%   |
| CSX                          | 3        | 0.18%   |
| Apacer                       | 3        | 0.18%   |
| Unknown (08C8)               | 2        | 0.12%   |
| Qumo                         | 2        | 0.12%   |
| Patriot Memory               | 2        | 0.12%   |
| Neo Forza                    | 2        | 0.12%   |
| Wilk Elektronik              | 1        | 0.06%   |
| Unknown (AB)                 | 1        | 0.06%   |
| Unknown (0xAD44594E45540000) | 1        | 0.06%   |
| Unknown (0x8551)             | 1        | 0.06%   |
| Unknown (0x0416)             | 1        | 0.06%   |
| TwinMOS                      | 1        | 0.06%   |
| Thermaltake                  | 1        | 0.06%   |
| TEXTORM                      | 1        | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 44       | 2.43%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s          | 32       | 1.77%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s            | 21       | 1.16%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 20       | 1.11%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s            | 17       | 0.94%   |
| G.Skill RAM F4-3200C16-16GVK 16384MB DIMM DDR4 3600MT/s        | 17       | 0.94%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s         | 16       | 0.88%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s           | 14       | 0.77%   |
| Kingston RAM KHX2400C15/8G 8192MB DIMM DDR4 3400MT/s           | 14       | 0.77%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s         | 14       | 0.77%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 13       | 0.72%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s            | 11       | 0.61%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 10       | 0.55%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3266MT/s            | 10       | 0.55%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s            | 10       | 0.55%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s          | 10       | 0.55%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s                    | 10       | 0.55%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s         | 9        | 0.5%    |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s            | 9        | 0.5%    |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s            | 9        | 0.5%    |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s            | 9        | 0.5%    |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s          | 9        | 0.5%    |
| Unknown                                                        | 9        | 0.5%    |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 8        | 0.44%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s             | 8        | 0.44%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s          | 8        | 0.44%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                        | 7        | 0.39%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 7        | 0.39%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s            | 7        | 0.39%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s          | 7        | 0.39%   |
| G.Skill RAM F4-3200C16-8GVGB 8GB DIMM DDR4 3200MT/s            | 7        | 0.39%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s            | 7        | 0.39%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 6        | 0.33%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s          | 6        | 0.33%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 6        | 0.33%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 6        | 0.33%   |
| Kingston RAM KHX2666C15D4/4G 4GB DIMM DDR4 3200MT/s            | 6        | 0.33%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s             | 6        | 0.33%   |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 3733MT/s             | 6        | 0.33%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3200MT/s         | 6        | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 855      | 58.16%  |
| DDR3    | 415      | 28.23%  |
| Unknown | 79       | 5.37%   |
| DDR2    | 42       | 2.86%   |
| SDRAM   | 38       | 2.59%   |
| DDR5    | 20       | 1.36%   |
| DDR     | 12       | 0.82%   |
| LPDDR4  | 7        | 0.48%   |
| LPDDR3  | 1        | 0.07%   |
| DRAM    | 1        | 0.07%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 1409     | 96.91%  |
| SODIMM  | 39       | 2.68%   |
| RIMM    | 3        | 0.21%   |
| FB-DIMM | 3        | 0.21%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 705      | 44.31%  |
| 4096  | 323      | 20.3%   |
| 16384 | 299      | 18.79%  |
| 2048  | 144      | 9.05%   |
| 32768 | 75       | 4.71%   |
| 1024  | 40       | 2.51%   |
| 512   | 4        | 0.25%   |
| 3072  | 1        | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 231      | 14.09%  |
| 3200    | 206      | 12.57%  |
| 3600    | 179      | 10.92%  |
| 1333    | 144      | 8.79%   |
| 2400    | 93       | 5.67%   |
| 2133    | 73       | 4.45%   |
| 2667    | 72       | 4.39%   |
| 3400    | 53       | 3.23%   |
| 1867    | 52       | 3.17%   |
| 3000    | 49       | 2.99%   |
| 800     | 45       | 2.75%   |
| 3533    | 33       | 2.01%   |
| 3800    | 32       | 1.95%   |
| 1866    | 32       | 1.95%   |
| 3866    | 28       | 1.71%   |
| 667     | 28       | 1.71%   |
| 3733    | 25       | 1.53%   |
| 3466    | 25       | 1.53%   |
| 2933    | 19       | 1.16%   |
| Unknown | 17       | 1.04%   |
| 2666    | 16       | 0.98%   |
| 3266    | 15       | 0.92%   |
| 1800    | 15       | 0.92%   |
| 2800    | 14       | 0.85%   |
| 1066    | 14       | 0.85%   |
| 3666    | 10       | 0.61%   |
| 4800    | 7        | 0.43%   |
| 1334    | 7        | 0.43%   |
| 3334    | 6        | 0.37%   |
| 2448    | 6        | 0.37%   |
| 5200    | 5        | 0.31%   |
| 3534    | 5        | 0.31%   |
| 1067    | 5        | 0.31%   |
| 333     | 5        | 0.31%   |
| 6000    | 4        | 0.24%   |
| 3500    | 4        | 0.24%   |
| 3100    | 4        | 0.24%   |
| 2048    | 4        | 0.24%   |
| 1648    | 4        | 0.24%   |
| 533     | 4        | 0.24%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 46       | 40.35%  |
| Brother Industries    | 21       | 18.42%  |
| Canon                 | 15       | 13.16%  |
| Seiko Epson           | 7        | 6.14%   |
| Samsung Electronics   | 6        | 5.26%   |
| Pantum                | 3        | 2.63%   |
| Apple                 | 3        | 2.63%   |
| Xerox                 | 2        | 1.75%   |
| Ricoh                 | 2        | 1.75%   |
| Prolific Technology   | 2        | 1.75%   |
| Zebra                 | 1        | 0.88%   |
| STMicroelectronics    | 1        | 0.88%   |
| QinHeng Electronics   | 1        | 0.88%   |
| Oki Data              | 1        | 0.88%   |
| Lexmark International | 1        | 0.88%   |
| Graphtec America      | 1        | 0.88%   |
| Dymo-CoStar           | 1        | 0.88%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| HP OfficeJet 5200 series                                  | 4        | 3.48%   |
| HP LaserJet 1300                                          | 3        | 2.61%   |
| Apple Gamesir-T1s 2.0b                                    | 3        | 2.61%   |
| Xerox Phaser 3020                                         | 2        | 1.74%   |
| Seiko Epson L120 Series                                   | 2        | 1.74%   |
| Samsung ML-1640 Series Laser Printer                      | 2        | 1.74%   |
| Prolific PL2305 Parallel Port                             | 2        | 1.74%   |
| HP Officejet 2620 series                                  | 2        | 1.74%   |
| HP DeskJet 4530 series                                    | 2        | 1.74%   |
| HP DeskJet 3630 series                                    | 2        | 1.74%   |
| HP DeskJet 2600 series                                    | 2        | 1.74%   |
| HP DeskJet 2130 series                                    | 2        | 1.74%   |
| HP Color LaserJet Pro M453-4                              | 2        | 1.74%   |
| Canon PIXMA MX340                                         | 2        | 1.74%   |
| Canon PIXMA MG2500 Series                                 | 2        | 1.74%   |
| Canon MG5700 series                                       | 2        | 1.74%   |
| Canon G3010 series                                        | 2        | 1.74%   |
| Brother HL-5370DW series                                  | 2        | 1.74%   |
| Brother DCP-7040                                          | 2        | 1.74%   |
| Zebra ZTC ZC100                                           | 1        | 0.87%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 0.87%   |
| Seiko Epson XP-4100 Series                                | 1        | 0.87%   |
| Seiko Epson Stylus NX230/SX235W Series                    | 1        | 0.87%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1        | 0.87%   |
| Seiko Epson L805 Series                                   | 1        | 0.87%   |
| Seiko Epson ET-4760 Series                                | 1        | 0.87%   |
| Seiko Epson ET-3850 Series                                | 1        | 0.87%   |
| Samsung ML-1660 Series                                    | 1        | 0.87%   |
| Samsung M2020 Series                                      | 1        | 0.87%   |
| Samsung CLX-3300 Series                                   | 1        | 0.87%   |
| Samsung CLP-310 Color Laser Printer                       | 1        | 0.87%   |
| Ricoh SP 112SU                                            | 1        | 0.87%   |
| Ricoh Printing Support                                    | 1        | 0.87%   |
| QinHeng CH340S                                            | 1        | 0.87%   |
| Pantum P2500W series                                      | 1        | 0.87%   |
| Pantum P2200 series                                       | 1        | 0.87%   |
| Pantum M6500 series                                       | 1        | 0.87%   |
| Oki Data USB Device                                       | 1        | 0.87%   |
| Lexmark International Lexmark MS312dn                     | 1        | 0.87%   |
| HP Smart Install                                          | 1        | 0.87%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 12       | 52.17%  |
| Seiko Epson        | 5        | 21.74%  |
| Hewlett-Packard    | 2        | 8.7%    |
| Visioneer          | 1        | 4.35%   |
| Ultima Electronics | 1        | 4.35%   |
| Mustek Systems     | 1        | 4.35%   |
| AGFA-Gevaert NV    | 1        | 4.35%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 110                                                               | 4        | 17.39%  |
| Canon CanoScan LiDE 220                                                               | 3        | 13.04%  |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 2        | 8.7%    |
| Canon CanoScan LIDE 25                                                                | 2        | 8.7%    |
| Visioneer OneTouch 5300 USB                                                           | 1        | 4.35%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1        | 4.35%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 1        | 4.35%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1        | 4.35%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]                                     | 1        | 4.35%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO                                            | 1        | 4.35%   |
| HP ScanJet 3500c                                                                      | 1        | 4.35%   |
| HP ScanJet 3400cse                                                                    | 1        | 4.35%   |
| Canon CanoScan LiDE 90                                                                | 1        | 4.35%   |
| Canon CanoScan LiDE 210                                                               | 1        | 4.35%   |
| Canon CanoScan LiDE 120                                                               | 1        | 4.35%   |
| AGFA-Gevaert NV SnapScan e26                                                          | 1        | 4.35%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 254      | 41.57%  |
| Microdia                      | 48       | 7.86%   |
| Microsoft                     | 47       | 7.69%   |
| Samsung Electronics           | 23       | 3.76%   |
| Z-Star Microelectronics       | 20       | 3.27%   |
| Sunplus Innovation Technology | 15       | 2.45%   |
| Creative Technology           | 12       | 1.96%   |
| Apple                         | 11       | 1.8%    |
| GEMBIRD                       | 9        | 1.47%   |
| MacroSilicon                  | 8        | 1.31%   |
| Generalplus Technology        | 8        | 1.31%   |
| Realtek Semiconductor         | 7        | 1.15%   |
| Cubeternet                    | 7        | 1.15%   |
| LG Electronics                | 6        | 0.98%   |
| Google                        | 6        | 0.98%   |
| Chicony Electronics           | 6        | 0.98%   |
| ARC International             | 6        | 0.98%   |
| Valve Software                | 5        | 0.82%   |
| KYE Systems (Mouse Systems)   | 5        | 0.82%   |
| Huawei Technologies           | 5        | 0.82%   |
| Genesys Logic                 | 5        | 0.82%   |
| Aveo Technology               | 5        | 0.82%   |
| webcam                        | 4        | 0.65%   |
| Pixart Imaging                | 4        | 0.65%   |
| Jieli Technology              | 4        | 0.65%   |
| Alcor Micro                   | 4        | 0.65%   |
| Xiongmai                      | 3        | 0.49%   |
| WCM_USB                       | 3        | 0.49%   |
| Sunplus IT                    | 3        | 0.49%   |
| Sonix Technology              | 3        | 0.49%   |
| SHENZHEN EMEET TECHNOLOGY     | 3        | 0.49%   |
| Razer USA                     | 3        | 0.49%   |
| Philips (or NXP)              | 3        | 0.49%   |
| Linux Foundation              | 3        | 0.49%   |
| Elgato Systems                | 3        | 0.49%   |
| AVerMedia Technologies        | 3        | 0.49%   |
| Arkmicro Technologies         | 3        | 0.49%   |
| Xiaomi                        | 2        | 0.33%   |
| WaveRider Communications      | 2        | 0.33%   |
| Silicon Motion                | 2        | 0.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                  | 60       | 9.76%   |
| Logitech HD Pro Webcam C920                           | 54       | 8.78%   |
| Samsung Galaxy series, misc. (MTP mode)               | 23       | 3.74%   |
| Microsoft LifeCam HD-3000                             | 21       | 3.41%   |
| Logitech C922 Pro Stream Webcam                       | 20       | 3.25%   |
| Microdia Webcam Vitade AF                             | 17       | 2.76%   |
| Z-Star Venus USB2.0 Camera                            | 11       | 1.79%   |
| Logitech Webcam C310                                  | 11       | 1.79%   |
| Logitech HD Webcam C615                               | 11       | 1.79%   |
| Logitech BRIO Ultra HD Webcam                         | 9        | 1.46%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                       | 9        | 1.46%   |
| Microdia USB 2.0 Camera                               | 8        | 1.3%    |
| MacroSilicon usb video                                | 8        | 1.3%    |
| Logitech Webcam C930e                                 | 8        | 1.3%    |
| Logitech Webcam C170                                  | 8        | 1.3%    |
| Logitech HD Webcam C525                               | 8        | 1.3%    |
| Microdia CameraA                                      | 7        | 1.14%   |
| Sunplus FHD Camera Microphone                         | 6        | 0.98%   |
| Microsoft LifeCam VX-2000                             | 6        | 0.98%   |
| Logitech StreamCam                                    | 6        | 0.98%   |
| Logitech HD Webcam C510                               | 6        | 0.98%   |
| Logitech B525 HD Webcam                               | 6        | 0.98%   |
| GEMBIRD USB2.0 PC CAMERA                              | 6        | 0.98%   |
| Valve Software 3D Camera                              | 5        | 0.81%   |
| Sunplus Full HD webcam                                | 5        | 0.81%   |
| Logitech Webcam Pro 9000                              | 5        | 0.81%   |
| Logitech HD Webcam C910                               | 5        | 0.81%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 5        | 0.81%   |
| Huawei UVC Camera                                     | 5        | 0.81%   |
| ARC International Camera                              | 5        | 0.81%   |
| webcam webcam                                         | 4        | 0.65%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                  | 4        | 0.65%   |
| Microsoft LifeCam Cinema                              | 4        | 0.65%   |
| Logitech BRIO 4K Stream Edition                       | 4        | 0.65%   |
| Jieli USB PHY 2.0                                     | 4        | 0.65%   |
| Google Nexus/Pixel Device (MTP + debug)               | 4        | 0.65%   |
| Generalplus GENERAL WEBCAM                            | 4        | 0.65%   |
| Generalplus 808 Camera #9 (web-cam mode)              | 4        | 0.65%   |
| Creative Live! Cam Chat HD [VF0700/VF0790]            | 4        | 0.65%   |
| Z-Star Integrated Camera                              | 3        | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Elan Microelectronics | 3        | 42.86%  |
| STMicroelectronics    | 1        | 14.29%  |
| LighTuning Technology | 1        | 14.29%  |
| Futronic Technology   | 1        | 14.29%  |
| AuthenTec             | 1        | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200] | 3        | 42.86%  |
| STMicroelectronics Fingerprint Reader       | 1        | 14.29%  |
| LighTuning Fingerprint Sensor               | 1        | 14.29%  |
| Futronic FS81 Fingerprint Scanner Module    | 1        | 14.29%  |
| AuthenTec AES1600                           | 1        | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Gemalto (was Gemplus)             | 5        | 20.83%  |
| Alcor Micro                       | 5        | 20.83%  |
| VASCO Data Security International | 4        | 16.67%  |
| Realtek Semiconductor             | 4        | 16.67%  |
| OmniKey                           | 2        | 8.33%   |
| Yubico.com                        | 1        | 4.17%   |
| SCM Microsystems                  | 1        | 4.17%   |
| Cherry                            | 1        | 4.17%   |
| BIT4ID                            | 1        | 4.17%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader               | 5        | 20.83%  |
| Realtek Semiconductor Smart Card Reader Interface               | 4        | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                             | 4        | 16.67%  |
| VASCO Data Security International Digipass 905 SmartCard Reader | 2        | 8.33%   |
| OmniKey 3x21 Smart Card Reader                                  | 2        | 8.33%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                 | 1        | 4.17%   |
| VASCO Data Security International DIGIPASS 920                  | 1        | 4.17%   |
| VASCO Data Security International DIGIPASS 870                  | 1        | 4.17%   |
| SCM Microsystems SCR331 SmartCard Reader                        | 1        | 4.17%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                     | 1        | 4.17%   |
| BIT4ID miniLector EVO                                           | 1        | 4.17%   |
| Alcor Micro Watchdata W 1981                                    | 1        | 4.17%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 2221     | 85.72%  |
| 1     | 334      | 12.89%  |
| 2     | 33       | 1.27%   |
| 3     | 3        | 0.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 156      | 39.69%  |
| Graphics card            | 54       | 13.74%  |
| Unassigned class         | 53       | 13.49%  |
| Camera                   | 20       | 5.09%   |
| Multimedia controller    | 15       | 3.82%   |
| Chipcard                 | 15       | 3.82%   |
| Net/ethernet             | 13       | 3.31%   |
| Sound                    | 12       | 3.05%   |
| Communication controller | 12       | 3.05%   |
| Bluetooth                | 10       | 2.54%   |
| Dvb card                 | 9        | 2.29%   |
| Storage/raid             | 6        | 1.53%   |
| Fingerprint reader       | 6        | 1.53%   |
| Network                  | 5        | 1.27%   |
| Storage/ide              | 2        | 0.51%   |
| Video                    | 1        | 0.25%   |
| Tv card                  | 1        | 0.25%   |
| Storage/ata              | 1        | 0.25%   |
| Storage                  | 1        | 0.25%   |
| Modem                    | 1        | 0.25%   |

