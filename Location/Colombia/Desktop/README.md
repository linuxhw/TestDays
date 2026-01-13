Linux in Colombia - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Colombia.

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

Total: 698

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | H110M PRO-VH PLUS           | [b447d296fe](https://linux-hardware.org/?probe=b447d296fe) | Jan 03, 2026 |
| ASUSTek       | PRIME A320M-K               | [acf3987772](https://linux-hardware.org/?probe=acf3987772) | Jan 02, 2026 |
| Dell          | 0DR845                      | [7c7f5eccce](https://linux-hardware.org/?probe=7c7f5eccce) | Dec 29, 2025 |
| Dell          | 0DR845                      | [c511e33362](https://linux-hardware.org/?probe=c511e33362) | Dec 29, 2025 |
| Pegatron      | 2A73h                       | [0a7d617dd0](https://linux-hardware.org/?probe=0a7d617dd0) | Dec 28, 2025 |
| MSI           | H110M PRO-VH PLUS           | [cc774b7847](https://linux-hardware.org/?probe=cc774b7847) | Dec 27, 2025 |
| MSI           | H110M PRO-VH PLUS           | [ac774dbb04](https://linux-hardware.org/?probe=ac774dbb04) | Dec 26, 2025 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [cdd68e63de](https://linux-hardware.org/?probe=cdd68e63de) | Dec 24, 2025 |
| Gigabyte      | H81M-H                      | [d411be4ea6](https://linux-hardware.org/?probe=d411be4ea6) | Dec 24, 2025 |
| ASRock        | Z77 Extreme4                | [4fe4e5afb6](https://linux-hardware.org/?probe=4fe4e5afb6) | Dec 20, 2025 |
| Gigabyte      | B560M DS3H                  | [300d8c438c](https://linux-hardware.org/?probe=300d8c438c) | Dec 19, 2025 |
| Gigabyte      | H81M-H                      | [b7c896084d](https://linux-hardware.org/?probe=b7c896084d) | Dec 16, 2025 |
| Dell          | 03KWTV A00                  | [105f14d366](https://linux-hardware.org/?probe=105f14d366) | Dec 15, 2025 |
| ASUSTek       | PRIME A320M-K               | [d93dbe02b2](https://linux-hardware.org/?probe=d93dbe02b2) | Dec 15, 2025 |
| ASUSTek       | PRIME A320M-K               | [b74b213001](https://linux-hardware.org/?probe=b74b213001) | Dec 15, 2025 |
| HP            | 339A                        | [010ba89d98](https://linux-hardware.org/?probe=010ba89d98) | Dec 14, 2025 |
| MSI           | H510M-A PRO                 | [bb697ee959](https://linux-hardware.org/?probe=bb697ee959) | Dec 08, 2025 |
| MSI           | H510M-A PRO                 | [ce604a8664](https://linux-hardware.org/?probe=ce604a8664) | Dec 07, 2025 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [c315ba293c](https://linux-hardware.org/?probe=c315ba293c) | Dec 06, 2025 |
| Gigabyte      | H81M-H                      | [caa4b11216](https://linux-hardware.org/?probe=caa4b11216) | Dec 02, 2025 |
| HP            | 0A54h                       | [ec97a70a69](https://linux-hardware.org/?probe=ec97a70a69) | Dec 01, 2025 |
| HP            | 0A54h                       | [fcec4122fd](https://linux-hardware.org/?probe=fcec4122fd) | Dec 01, 2025 |
| Gigabyte      | H81M-H                      | [8223e2878e](https://linux-hardware.org/?probe=8223e2878e) | Nov 28, 2025 |
| ASRock        | G41M-VS3                    | [428c9c16e5](https://linux-hardware.org/?probe=428c9c16e5) | Nov 26, 2025 |
| Gigabyte      | A520M DS3H                  | [a1fbb51783](https://linux-hardware.org/?probe=a1fbb51783) | Nov 26, 2025 |
| Gigabyte      | H81M-H                      | [3212a2cb08](https://linux-hardware.org/?probe=3212a2cb08) | Nov 26, 2025 |
| Biostar       | N68S3+                      | [c4c7d41ba4](https://linux-hardware.org/?probe=c4c7d41ba4) | Nov 24, 2025 |
| HP            | 1495                        | [e22b0bd58c](https://linux-hardware.org/?probe=e22b0bd58c) | Nov 23, 2025 |
| Dell          | 07WP95 A01                  | [fdfff8171c](https://linux-hardware.org/?probe=fdfff8171c) | Nov 16, 2025 |
| ASUSTek       | V220IB                      | [b0d3700a2b](https://linux-hardware.org/?probe=b0d3700a2b) | Nov 13, 2025 |
| Intel         | H61                         | [e2fe6f64a6](https://linux-hardware.org/?probe=e2fe6f64a6) | Nov 13, 2025 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [189da6f5df](https://linux-hardware.org/?probe=189da6f5df) | Nov 12, 2025 |
| Gigabyte      | AX370-Gaming 5              | [cbd0739717](https://linux-hardware.org/?probe=cbd0739717) | Nov 09, 2025 |
| HP            | 339A                        | [760ec69ad1](https://linux-hardware.org/?probe=760ec69ad1) | Nov 08, 2025 |
| AZW           | SER V1.0                    | [7f7f994bbb](https://linux-hardware.org/?probe=7f7f994bbb) | Oct 28, 2025 |
| PCSMART       | PCSGOB270-B Med ZF 3407     | [35ff3fe872](https://linux-hardware.org/?probe=35ff3fe872) | Oct 26, 2025 |
| MSI           | PRO Z690-A WIFI DDR4        | [ddc6c35d34](https://linux-hardware.org/?probe=ddc6c35d34) | Oct 22, 2025 |
| Gigabyte      | A320M-S2H-CF                | [751218fb6b](https://linux-hardware.org/?probe=751218fb6b) | Oct 22, 2025 |
| Biostar       | H61MGC                      | [43f06edd34](https://linux-hardware.org/?probe=43f06edd34) | Oct 21, 2025 |
| eMachines     | EL1352                      | [86584658c9](https://linux-hardware.org/?probe=86584658c9) | Oct 14, 2025 |
| Huanan        | X79 V1.0                    | [c86fb54116](https://linux-hardware.org/?probe=c86fb54116) | Oct 13, 2025 |
| HP            | 1497                        | [c08a1bd7eb](https://linux-hardware.org/?probe=c08a1bd7eb) | Oct 10, 2025 |
| ASUSTek       | PRIME Z390-A                | [2963ea4ce0](https://linux-hardware.org/?probe=2963ea4ce0) | Oct 10, 2025 |
| Pegatron      | 2A73h                       | [f0b1569dfb](https://linux-hardware.org/?probe=f0b1569dfb) | Oct 05, 2025 |
| ASUSTek       | M4A785TD-V EVO              | [4d5e029644](https://linux-hardware.org/?probe=4d5e029644) | Sep 25, 2025 |
| Dell          | 0PC5F7 A00                  | [66ca504a44](https://linux-hardware.org/?probe=66ca504a44) | Sep 13, 2025 |
| ASUSTek       | CROSSBLADE RANGER           | [5fce52b1a1](https://linux-hardware.org/?probe=5fce52b1a1) | Sep 09, 2025 |
| Gigabyte      | B550M DS3H AC               | [f05aa39279](https://linux-hardware.org/?probe=f05aa39279) | Aug 31, 2025 |
| Gigabyte      | B450M DS3H V2               | [99f7c9f3e8](https://linux-hardware.org/?probe=99f7c9f3e8) | Aug 26, 2025 |
| ASUSTek       | PRIME B350M-A               | [92aeb02732](https://linux-hardware.org/?probe=92aeb02732) | Aug 23, 2025 |
| Dell          | 0NW73C A00                  | [36817e573d](https://linux-hardware.org/?probe=36817e573d) | Aug 19, 2025 |
| Gigabyte      | B360M GAMING HD             | [4f1dbd36c1](https://linux-hardware.org/?probe=4f1dbd36c1) | Aug 19, 2025 |
| MSI           | PRO B650M-P                 | [ddde4e388b](https://linux-hardware.org/?probe=ddde4e388b) | Aug 18, 2025 |
| ASRock        | AMD BC-250                  | [046ecbd107](https://linux-hardware.org/?probe=046ecbd107) | Aug 18, 2025 |
| ASRock        | AMD BC-250                  | [3f75a94034](https://linux-hardware.org/?probe=3f75a94034) | Aug 18, 2025 |
| ASRock        | H510M-HDV/M.2 SE            | [f369e92b43](https://linux-hardware.org/?probe=f369e92b43) | Aug 17, 2025 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [aa5f3fdf8b](https://linux-hardware.org/?probe=aa5f3fdf8b) | Jul 24, 2025 |
| Huanan        | X99-F8 V5.0 JX-30MV         | [ff1f29001d](https://linux-hardware.org/?probe=ff1f29001d) | Jul 22, 2025 |
| Huanan        | X99-F8 V5.0 JX-30MV         | [334afcb7e7](https://linux-hardware.org/?probe=334afcb7e7) | Jul 21, 2025 |
| ASRock        | B85M                        | [3048ed0899](https://linux-hardware.org/?probe=3048ed0899) | Jul 17, 2025 |
| Gigabyte      | A520M DS3H                  | [e7c5fefe35](https://linux-hardware.org/?probe=e7c5fefe35) | Jul 13, 2025 |
| Gigabyte      | Z77M-D3H-MVP                | [8d017a2885](https://linux-hardware.org/?probe=8d017a2885) | Jul 12, 2025 |
| Dell          | 073Y7Y A00                  | [cc5df038f4](https://linux-hardware.org/?probe=cc5df038f4) | Jul 11, 2025 |
| ASUSTek       | M4N98TD EVO                 | [f30e7afdab](https://linux-hardware.org/?probe=f30e7afdab) | Jul 10, 2025 |
| Lenovo        | ThinkCentre M91p 4518CC7    | [cb7a4b89ca](https://linux-hardware.org/?probe=cb7a4b89ca) | Jul 08, 2025 |
| ASUSTek       | PRIME B550M-A AC            | [902f769e87](https://linux-hardware.org/?probe=902f769e87) | Jul 08, 2025 |
| Gigabyte      | X150M-PLUS WS-CF            | [ce33bc5660](https://linux-hardware.org/?probe=ce33bc5660) | Jul 07, 2025 |
| Shenzhen M... | DRFXL                       | [29c3690b8a](https://linux-hardware.org/?probe=29c3690b8a) | Jul 06, 2025 |
| HP            | 8433 11                     | [9dcdd4244a](https://linux-hardware.org/?probe=9dcdd4244a) | Jul 01, 2025 |
| MSI           | H81M-E33                    | [797c4773ed](https://linux-hardware.org/?probe=797c4773ed) | Jul 01, 2025 |
| Shenzhen M... | DRFXL                       | [157708d0c7](https://linux-hardware.org/?probe=157708d0c7) | Jun 29, 2025 |
| ASRock        | X870E Nova WiFi             | [e585e9591f](https://linux-hardware.org/?probe=e585e9591f) | Jun 25, 2025 |
| ASUSTek       | PRIME B550-PLUS             | [338a486dcb](https://linux-hardware.org/?probe=338a486dcb) | Jun 25, 2025 |
| ASRock        | X870E Nova WiFi             | [661dccc48c](https://linux-hardware.org/?probe=661dccc48c) | Jun 24, 2025 |
| Gigabyte      | EX58-UD3R                   | [11cd8d00eb](https://linux-hardware.org/?probe=11cd8d00eb) | Jun 22, 2025 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [df6c665d65](https://linux-hardware.org/?probe=df6c665d65) | Jun 16, 2025 |
| Dell          | 0KYJ8C A00                  | [1536ff4100](https://linux-hardware.org/?probe=1536ff4100) | Jun 16, 2025 |
| Dell          | 0Y0MYH A01                  | [3b37d1be73](https://linux-hardware.org/?probe=3b37d1be73) | Jun 15, 2025 |
| MSI           | H81M-E33                    | [5d922ad2df](https://linux-hardware.org/?probe=5d922ad2df) | Jun 15, 2025 |
| Dell          | 06CV2N A01                  | [74044494f5](https://linux-hardware.org/?probe=74044494f5) | Jun 14, 2025 |
| Intel         | DH67BL AAG10189-211         | [9f2490aa6b](https://linux-hardware.org/?probe=9f2490aa6b) | Jun 13, 2025 |
| MSI           | PRO B650M-P                 | [1d6758662a](https://linux-hardware.org/?probe=1d6758662a) | Jun 13, 2025 |
| MSI           | MS-7253                     | [f1f9ff0932](https://linux-hardware.org/?probe=f1f9ff0932) | Jun 11, 2025 |
| MSI           | B360M MORTAR                | [9f69f2a1e8](https://linux-hardware.org/?probe=9f69f2a1e8) | Jun 10, 2025 |
| ASRock        | B365M Pro4                  | [9b9818508b](https://linux-hardware.org/?probe=9b9818508b) | Jun 08, 2025 |
| Dell          | 0T568R A00                  | [0d54fb75e1](https://linux-hardware.org/?probe=0d54fb75e1) | Jun 07, 2025 |
| ASUSTek       | ROG CROSSHAIR X870E HERO    | [1207015f69](https://linux-hardware.org/?probe=1207015f69) | Jun 05, 2025 |
| ASUSTek       | ROG CROSSHAIR X870E HERO    | [bdcbf7cece](https://linux-hardware.org/?probe=bdcbf7cece) | Jun 05, 2025 |
| Gigabyte      | B450M DS3H-CF               | [6e148b36b5](https://linux-hardware.org/?probe=6e148b36b5) | Jun 03, 2025 |
| Unknown       | Unknown                     | [0381498da1](https://linux-hardware.org/?probe=0381498da1) | Jun 01, 2025 |
| MSI           | 0A90                        | [b8a28ebfde](https://linux-hardware.org/?probe=b8a28ebfde) | May 31, 2025 |
| ASUSTek       | ROG CROSSHAIR X870E HERO    | [987e8f065a](https://linux-hardware.org/?probe=987e8f065a) | May 24, 2025 |
| Lenovo        | HASWELLREFRESHDT 3190005... | [87e02f6630](https://linux-hardware.org/?probe=87e02f6630) | May 20, 2025 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [5eba1efc4e](https://linux-hardware.org/?probe=5eba1efc4e) | May 15, 2025 |
| ASRock        | B450 Pro4                   | [820105374a](https://linux-hardware.org/?probe=820105374a) | May 12, 2025 |
| ASRock        | B450 Pro4                   | [3d746459bc](https://linux-hardware.org/?probe=3d746459bc) | May 11, 2025 |
| Gigabyte      | H61M-HD2                    | [4e71fa1c89](https://linux-hardware.org/?probe=4e71fa1c89) | May 06, 2025 |
| Lenovo        | IdeaCentre B320             | [8bf5382842](https://linux-hardware.org/?probe=8bf5382842) | May 04, 2025 |
| Intel         | DH61CR AAG14064-209         | [b34281d7bd](https://linux-hardware.org/?probe=b34281d7bd) | May 04, 2025 |
| Dell          | 02YYK5 A01                  | [dc4fc2a034](https://linux-hardware.org/?probe=dc4fc2a034) | May 02, 2025 |
| Dell          | 08K0X7 A00                  | [869eb3f4e0](https://linux-hardware.org/?probe=869eb3f4e0) | Apr 30, 2025 |
| Dell          | 0P301D A00                  | [db26ee79c3](https://linux-hardware.org/?probe=db26ee79c3) | Apr 29, 2025 |
| MSI           | H81M-E33                    | [f7bd57c602](https://linux-hardware.org/?probe=f7bd57c602) | Apr 29, 2025 |
| Gigabyte      | H55M-USB3                   | [4e62ff3ea2](https://linux-hardware.org/?probe=4e62ff3ea2) | Apr 28, 2025 |
| ASUSTek       | TUF Gaming X570-PLUS        | [1d4bb06810](https://linux-hardware.org/?probe=1d4bb06810) | Apr 19, 2025 |
| ASRock        | G31M-VS2                    | [6973e4e819](https://linux-hardware.org/?probe=6973e4e819) | Apr 18, 2025 |
| SYWZ          | S210HA Series               | [4cf2388547](https://linux-hardware.org/?probe=4cf2388547) | Apr 15, 2025 |
| ASUSTek       | TUF Gaming X570-PLUS        | [1581cc4895](https://linux-hardware.org/?probe=1581cc4895) | Apr 15, 2025 |
| Gigabyte      | B760M DS3H DDR4             | [7a43d31993](https://linux-hardware.org/?probe=7a43d31993) | Apr 15, 2025 |
| ASRock        | H510M-HDV/M.2 SE            | [569be7448b](https://linux-hardware.org/?probe=569be7448b) | Apr 13, 2025 |
| Pegatron      | 2AE2                        | [f628a00d92](https://linux-hardware.org/?probe=f628a00d92) | Apr 09, 2025 |
| Pegatron      | 2AE2                        | [580a936d37](https://linux-hardware.org/?probe=580a936d37) | Apr 09, 2025 |
| Gigabyte      | B760M DS3H DDR4             | [ea6d5d27c6](https://linux-hardware.org/?probe=ea6d5d27c6) | Apr 08, 2025 |
| ECS           | H81H3-M4                    | [3220533812](https://linux-hardware.org/?probe=3220533812) | Apr 07, 2025 |
| Dell          | 00V62H A01                  | [39cb920951](https://linux-hardware.org/?probe=39cb920951) | Apr 05, 2025 |
| ECS           | H81H3-M4                    | [64d5de9c24](https://linux-hardware.org/?probe=64d5de9c24) | Apr 04, 2025 |
| ASRock        | N68-S UCC                   | [6052723444](https://linux-hardware.org/?probe=6052723444) | Apr 03, 2025 |
| ASUSTek       | PRIME X570-PRO              | [737469c6af](https://linux-hardware.org/?probe=737469c6af) | Mar 30, 2025 |
| ASUSTek       | CROSSBLADE RANGER           | [acc389852b](https://linux-hardware.org/?probe=acc389852b) | Mar 26, 2025 |
| ASRock        | A620I Lightning WiFi        | [3731b45096](https://linux-hardware.org/?probe=3731b45096) | Mar 19, 2025 |
| Gigabyte      | GA-78LMT-S2P                | [3777fa2fa5](https://linux-hardware.org/?probe=3777fa2fa5) | Mar 14, 2025 |
| MSI           | Boston                      | [c20d8da526](https://linux-hardware.org/?probe=c20d8da526) | Mar 13, 2025 |
| HP            | 2B5A 011                    | [36d1f81375](https://linux-hardware.org/?probe=36d1f81375) | Mar 12, 2025 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [342406a87e](https://linux-hardware.org/?probe=342406a87e) | Mar 08, 2025 |
| MSI           | A520M-A PRO                 | [f7102c8ec5](https://linux-hardware.org/?probe=f7102c8ec5) | Mar 05, 2025 |
| Gigabyte      | GA-970A-UD3                 | [b48f493b68](https://linux-hardware.org/?probe=b48f493b68) | Feb 07, 2025 |
| Lenovo        | 1064 NOK                    | [30a93294d8](https://linux-hardware.org/?probe=30a93294d8) | Jan 29, 2025 |
| ECS           | H61H2-MV                    | [5a8c6cd8dd](https://linux-hardware.org/?probe=5a8c6cd8dd) | Jan 28, 2025 |
| ASRock        | B450 Steel Legend           | [5a31c98fb5](https://linux-hardware.org/?probe=5a31c98fb5) | Jan 26, 2025 |
| HP            | 3398                        | [9a67b69481](https://linux-hardware.org/?probe=9a67b69481) | Jan 24, 2025 |
| Dell          | 08K0X7 A00                  | [af89f1049a](https://linux-hardware.org/?probe=af89f1049a) | Jan 23, 2025 |
| Shenzhen M... | DRFXL                       | [b6b11fecb4](https://linux-hardware.org/?probe=b6b11fecb4) | Jan 21, 2025 |
| MSI           | B560M PRO-E                 | [c5e5d8ade3](https://linux-hardware.org/?probe=c5e5d8ade3) | Jan 20, 2025 |
| ASUSTek       | B150M-C                     | [6a8e9db888](https://linux-hardware.org/?probe=6a8e9db888) | Jan 09, 2025 |
| HP            | 1497                        | [256c3def88](https://linux-hardware.org/?probe=256c3def88) | Dec 29, 2024 |
| JGINYUE       | X99 TITANIUM D3             | [bb9134a8a6](https://linux-hardware.org/?probe=bb9134a8a6) | Dec 11, 2024 |
| ASUSTek       | PRIME B460M-A               | [275b70a9b3](https://linux-hardware.org/?probe=275b70a9b3) | Dec 09, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [22bfeaf18d](https://linux-hardware.org/?probe=22bfeaf18d) | Dec 08, 2024 |
| ASUSTek       | PRIME B460M-A               | [422c8408b1](https://linux-hardware.org/?probe=422c8408b1) | Dec 07, 2024 |
| HP            | 3398                        | [3be901c90e](https://linux-hardware.org/?probe=3be901c90e) | Dec 06, 2024 |
| Dell          | 0HD5W2 A01                  | [f02fe6c8da](https://linux-hardware.org/?probe=f02fe6c8da) | Dec 03, 2024 |
| Dell          | 0HD5W2 A01                  | [f9aa503983](https://linux-hardware.org/?probe=f9aa503983) | Dec 03, 2024 |
| Gigabyte      | B450M DS3H-CF               | [cb0e4decea](https://linux-hardware.org/?probe=cb0e4decea) | Dec 02, 2024 |
| Gigabyte      | H97M-DS3P                   | [0d1e9eec2d](https://linux-hardware.org/?probe=0d1e9eec2d) | Nov 20, 2024 |
| MSI           | A520M-A PRO                 | [70aebceb5e](https://linux-hardware.org/?probe=70aebceb5e) | Nov 18, 2024 |
| Gigabyte      | B450M DS3H-CF               | [1e4f8fa6f5](https://linux-hardware.org/?probe=1e4f8fa6f5) | Nov 16, 2024 |
| Lenovo        | 0B98401 PRO                 | [2f5cd15407](https://linux-hardware.org/?probe=2f5cd15407) | Nov 14, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [60639f7365](https://linux-hardware.org/?probe=60639f7365) | Nov 14, 2024 |
| MSI           | MPG B550I GAMING EDGE MA... | [62bd667a99](https://linux-hardware.org/?probe=62bd667a99) | Oct 26, 2024 |
| Gigabyte      | A320M-S2H-CF                | [26bd161f46](https://linux-hardware.org/?probe=26bd161f46) | Oct 21, 2024 |
| Quanta        | 2AC7 011                    | [36d655acf6](https://linux-hardware.org/?probe=36d655acf6) | Oct 16, 2024 |
| Intel         | H81                         | [6a28d6befb](https://linux-hardware.org/?probe=6a28d6befb) | Oct 10, 2024 |
| MSI           | B150A GAMING PRO            | [4d5f7679d0](https://linux-hardware.org/?probe=4d5f7679d0) | Oct 06, 2024 |
| Gigabyte      | X670E AORUS MASTER          | [37e187d1c9](https://linux-hardware.org/?probe=37e187d1c9) | Oct 06, 2024 |
| Compumax C... | AMD Ryzen 5000U             | [9f694c0c87](https://linux-hardware.org/?probe=9f694c0c87) | Oct 02, 2024 |
| ECS           | H61H2-MV                    | [29d29072da](https://linux-hardware.org/?probe=29d29072da) | Oct 01, 2024 |
| MSI           | A520M-A PRO                 | [d6ed4a9deb](https://linux-hardware.org/?probe=d6ed4a9deb) | Sep 29, 2024 |
| MSI           | H81M-E33                    | [358f1f3405](https://linux-hardware.org/?probe=358f1f3405) | Sep 28, 2024 |
| ASUSTek       | B150 PRO GAMING D3          | [9342e97a46](https://linux-hardware.org/?probe=9342e97a46) | Sep 28, 2024 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | [2b248e2664](https://linux-hardware.org/?probe=2b248e2664) | Sep 28, 2024 |
| ASUSTek       | M4A79T Deluxe               | [cef2225be4](https://linux-hardware.org/?probe=cef2225be4) | Sep 19, 2024 |
| MSI           | PRO H510M-B                 | [020620e4c2](https://linux-hardware.org/?probe=020620e4c2) | Sep 18, 2024 |
| MSI           | PRO H510M-B                 | [892b66d32f](https://linux-hardware.org/?probe=892b66d32f) | Sep 18, 2024 |
| MSI           | H81M-E33                    | [c91a805424](https://linux-hardware.org/?probe=c91a805424) | Sep 18, 2024 |
| ASUSTek       | P8H61-M LX3                 | [fef809274c](https://linux-hardware.org/?probe=fef809274c) | Sep 12, 2024 |
| Intel         | H61                         | [26ad2a6fdf](https://linux-hardware.org/?probe=26ad2a6fdf) | Sep 10, 2024 |
| Foxconn       | G31MV/G31MV-K FAB           | [cdd64926ef](https://linux-hardware.org/?probe=cdd64926ef) | Sep 06, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [8fe595fe5f](https://linux-hardware.org/?probe=8fe595fe5f) | Sep 05, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [c679b1e522](https://linux-hardware.org/?probe=c679b1e522) | Sep 03, 2024 |
| Gigabyte      | B250M-DS3H-CF               | [21851ce5cc](https://linux-hardware.org/?probe=21851ce5cc) | Sep 02, 2024 |
| ECS           | H81H3-M4                    | [a1a53ea4b7](https://linux-hardware.org/?probe=a1a53ea4b7) | Aug 29, 2024 |
| ECS           | H81H3-M4                    | [07bf45f673](https://linux-hardware.org/?probe=07bf45f673) | Aug 29, 2024 |
| Gigabyte      | X670E AORUS MASTER          | [6bfb0ed86d](https://linux-hardware.org/?probe=6bfb0ed86d) | Aug 24, 2024 |
| MSI           | MS-7253                     | [024d2de5c9](https://linux-hardware.org/?probe=024d2de5c9) | Aug 24, 2024 |
| Intel         | DH61BF AAG81311-101         | [a099b50209](https://linux-hardware.org/?probe=a099b50209) | Aug 23, 2024 |
| Intel         | DH61BF AAG81311-101         | [b235f2f382](https://linux-hardware.org/?probe=b235f2f382) | Aug 23, 2024 |
| HP            | 2129                        | [1eb65765a8](https://linux-hardware.org/?probe=1eb65765a8) | Aug 22, 2024 |
| HP            | 2129                        | [23ae96f746](https://linux-hardware.org/?probe=23ae96f746) | Aug 20, 2024 |
| ASRock        | H61M-VG3                    | [bd7e312add](https://linux-hardware.org/?probe=bd7e312add) | Aug 18, 2024 |
| MSI           | PRO Z690-A WIFI DDR4        | [accba7b6c9](https://linux-hardware.org/?probe=accba7b6c9) | Aug 18, 2024 |
| MSI           | PRO Z690-A WIFI DDR4        | [dbda8656d2](https://linux-hardware.org/?probe=dbda8656d2) | Aug 18, 2024 |
| ASRock        | B450M-HDV R4.0              | [befe3e1358](https://linux-hardware.org/?probe=befe3e1358) | Aug 15, 2024 |
| MSI           | Z77A-G41                    | [85eb1d0f02](https://linux-hardware.org/?probe=85eb1d0f02) | Aug 09, 2024 |
| ECS           | H81H3-M4                    | [64dcbcc2da](https://linux-hardware.org/?probe=64dcbcc2da) | Aug 06, 2024 |
| MSI           | MS-7253                     | [89164c8b71](https://linux-hardware.org/?probe=89164c8b71) | Jul 25, 2024 |
| ASUSTek       | TUF X470-PLUS GAMING        | [027ce3ae0f](https://linux-hardware.org/?probe=027ce3ae0f) | Jul 21, 2024 |
| Dell          | 08NPPY A01                  | [03c5024ab6](https://linux-hardware.org/?probe=03c5024ab6) | Jul 19, 2024 |
| Gigabyte      | X670E AORUS MASTER          | [67f8fcdd69](https://linux-hardware.org/?probe=67f8fcdd69) | Jul 19, 2024 |
| Gigabyte      | X570 AORUS ELITE            | [ea7ab46b40](https://linux-hardware.org/?probe=ea7ab46b40) | Jul 17, 2024 |
| ASRock        | A320M-HDV R4.0              | [ab1d6d4f02](https://linux-hardware.org/?probe=ab1d6d4f02) | Jul 11, 2024 |
| Dell          | 0KYJ8C A00                  | [0cda74adb5](https://linux-hardware.org/?probe=0cda74adb5) | Jun 25, 2024 |
| ASUSTek       | PRIME X670-P                | [157fc29a20](https://linux-hardware.org/?probe=157fc29a20) | Jun 21, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [53d5c7cd29](https://linux-hardware.org/?probe=53d5c7cd29) | Jun 19, 2024 |
| ASUSTek       | PRIME Z690-P D4             | [02e64270cf](https://linux-hardware.org/?probe=02e64270cf) | Jun 09, 2024 |
| MACHINIST     | E5-MR9A PRO V1.2            | [decba51c01](https://linux-hardware.org/?probe=decba51c01) | Jun 08, 2024 |
| Gigabyte      | X670E AORUS PRO X           | [fd6dc7b85b](https://linux-hardware.org/?probe=fd6dc7b85b) | Jun 06, 2024 |
| Gigabyte      | A520M DS3H                  | [e555435a07](https://linux-hardware.org/?probe=e555435a07) | Jun 05, 2024 |
| Intel         | DG41RQ AAE54511-203         | [5cd9b65fe2](https://linux-hardware.org/?probe=5cd9b65fe2) | Jun 05, 2024 |
| Dell          | 0D883F A06                  | [b05d49d4c6](https://linux-hardware.org/?probe=b05d49d4c6) | Jun 03, 2024 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [8e3332a712](https://linux-hardware.org/?probe=8e3332a712) | May 31, 2024 |
| Intel         | D945GCPE AAD97209-201       | [4b5c79152f](https://linux-hardware.org/?probe=4b5c79152f) | May 29, 2024 |
| Dell          | 08NPPY A01                  | [30ae7d8cc1](https://linux-hardware.org/?probe=30ae7d8cc1) | May 27, 2024 |
| ASUSTek       | H61M-K                      | [ed0fb6e87d](https://linux-hardware.org/?probe=ed0fb6e87d) | May 24, 2024 |
| Dell          | 0D883F A06                  | [d979b83929](https://linux-hardware.org/?probe=d979b83929) | May 16, 2024 |
| ASRock        | Z590 Steel Legend WiFi 6... | [9afb28537a](https://linux-hardware.org/?probe=9afb28537a) | May 16, 2024 |
| ASUSTek       | TUF Gaming A620M-PLUS WI... | [0fdd6d8d04](https://linux-hardware.org/?probe=0fdd6d8d04) | May 12, 2024 |
| Biostar       | G41D3B                      | [3f88596c99](https://linux-hardware.org/?probe=3f88596c99) | May 12, 2024 |
| PCSMART       | 7.0                         | [66d6082bf4](https://linux-hardware.org/?probe=66d6082bf4) | May 07, 2024 |
| Gigabyte      | H410M H V3                  | [486c191884](https://linux-hardware.org/?probe=486c191884) | May 07, 2024 |
| PCSMART       | 7.0                         | [18ea3d8d19](https://linux-hardware.org/?probe=18ea3d8d19) | May 05, 2024 |
| ASRock        | Wolfdale1333-D667           | [15e7baeeb3](https://linux-hardware.org/?probe=15e7baeeb3) | May 03, 2024 |
| ASRock        | Wolfdale1333-D667           | [9cfa5ae2c5](https://linux-hardware.org/?probe=9cfa5ae2c5) | May 03, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [c8e2add151](https://linux-hardware.org/?probe=c8e2add151) | May 03, 2024 |
| Intel         | X79G V2.x                   | [00807bfaa6](https://linux-hardware.org/?probe=00807bfaa6) | May 02, 2024 |
| Biostar       | G41D3B                      | [748e0749c5](https://linux-hardware.org/?probe=748e0749c5) | Apr 30, 2024 |
| ASRock        | N68-S                       | [a099ad6775](https://linux-hardware.org/?probe=a099ad6775) | Apr 30, 2024 |
| Gigabyte      | X670E AORUS PRO X           | [ac94661695](https://linux-hardware.org/?probe=ac94661695) | Apr 24, 2024 |
| ASUSTek       | M5A97 EVO R2.0              | [07cede8279](https://linux-hardware.org/?probe=07cede8279) | Apr 17, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [be0f54854d](https://linux-hardware.org/?probe=be0f54854d) | Apr 10, 2024 |
| MSI           | NF725M-P43                  | [9fc3ac2e10](https://linux-hardware.org/?probe=9fc3ac2e10) | Apr 07, 2024 |
| MSI           | A320M PRO-VH PLUS           | [943c2e486a](https://linux-hardware.org/?probe=943c2e486a) | Apr 05, 2024 |
| ASUSTek       | PRIME B550M-A AC            | [61f8f4ee36](https://linux-hardware.org/?probe=61f8f4ee36) | Apr 03, 2024 |
| MSI           | 760GM-P21                   | [9ea00e6ebb](https://linux-hardware.org/?probe=9ea00e6ebb) | Mar 22, 2024 |
| Acer          | Predator G3-710             | [81423396ff](https://linux-hardware.org/?probe=81423396ff) | Mar 16, 2024 |
| Acer          | Predator G3-710             | [4a28c9273f](https://linux-hardware.org/?probe=4a28c9273f) | Mar 16, 2024 |
| ASUSTek       | PRIME B450M-A II            | [903192b99a](https://linux-hardware.org/?probe=903192b99a) | Mar 09, 2024 |
| ASUSTek       | M5A97 EVO R2.0              | [27e68f4135](https://linux-hardware.org/?probe=27e68f4135) | Mar 07, 2024 |
| ASUSTek       | PRIME A520M-A II            | [6e87e2444b](https://linux-hardware.org/?probe=6e87e2444b) | Mar 05, 2024 |
| HP            | 1495                        | [ee01c60448](https://linux-hardware.org/?probe=ee01c60448) | Feb 29, 2024 |
| Intel         | X79G V2.x                   | [077f5b4397](https://linux-hardware.org/?probe=077f5b4397) | Feb 15, 2024 |
| Lenovo        | ThinkStation D30 4223AU4    | [bd10aa2839](https://linux-hardware.org/?probe=bd10aa2839) | Feb 13, 2024 |
| ASUSTek       | PRIME A320M-A               | [f85fa50f25](https://linux-hardware.org/?probe=f85fa50f25) | Feb 08, 2024 |
| Biostar       | A58ML                       | [207acb5012](https://linux-hardware.org/?probe=207acb5012) | Feb 07, 2024 |
| ASRock        | X670E Pro RS                | [b5f16b7125](https://linux-hardware.org/?probe=b5f16b7125) | Feb 03, 2024 |
| ASRock        | X670E Pro RS                | [fd02477c14](https://linux-hardware.org/?probe=fd02477c14) | Feb 02, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6dbdc40268](https://linux-hardware.org/?probe=6dbdc40268) | Jan 22, 2024 |
| Lenovo        | ThinkCentre A62 9486E4S     | [426fe50b95](https://linux-hardware.org/?probe=426fe50b95) | Jan 21, 2024 |
| Lenovo        | ThinkCentre A62 9486E4S     | [9712c9e135](https://linux-hardware.org/?probe=9712c9e135) | Jan 21, 2024 |
| ASUSTek       | PRIME H610M-E D4            | [409e7e4e42](https://linux-hardware.org/?probe=409e7e4e42) | Jan 17, 2024 |
| HP            | 18E5                        | [4fb3a76631](https://linux-hardware.org/?probe=4fb3a76631) | Jan 15, 2024 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [23c4e3e208](https://linux-hardware.org/?probe=23c4e3e208) | Jan 13, 2024 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [b98091e5e6](https://linux-hardware.org/?probe=b98091e5e6) | Jan 13, 2024 |
| Intel         | X79G V2.x                   | [cf61b1759b](https://linux-hardware.org/?probe=cf61b1759b) | Jan 12, 2024 |
| MSI           | GF615M-P33                  | [7d32db9104](https://linux-hardware.org/?probe=7d32db9104) | Jan 12, 2024 |
| ASRock        | X670E Pro RS                | [2f899514f8](https://linux-hardware.org/?probe=2f899514f8) | Jan 12, 2024 |
| MSI           | A320M PRO-VH PLUS           | [3ff7f414fe](https://linux-hardware.org/?probe=3ff7f414fe) | Jan 07, 2024 |
| MSI           | H81M-E33                    | [cced2d2e95](https://linux-hardware.org/?probe=cced2d2e95) | Jan 07, 2024 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [f10936a9f7](https://linux-hardware.org/?probe=f10936a9f7) | Jan 02, 2024 |
| MSI           | PRO Z790-A WIFI             | [40362f198b](https://linux-hardware.org/?probe=40362f198b) | Dec 31, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [863f0b5c06](https://linux-hardware.org/?probe=863f0b5c06) | Dec 29, 2023 |
| Gigabyte      | H61M-S1                     | [6b98d84cb0](https://linux-hardware.org/?probe=6b98d84cb0) | Dec 28, 2023 |
| HP            | 339A                        | [49cb574539](https://linux-hardware.org/?probe=49cb574539) | Dec 27, 2023 |
| MSI           | MPG B550 GAMING CARBON W... | [3c0ecabaa3](https://linux-hardware.org/?probe=3c0ecabaa3) | Dec 27, 2023 |
| MSI           | A320M PRO-VH PLUS           | [53fae0e708](https://linux-hardware.org/?probe=53fae0e708) | Dec 25, 2023 |
| MSI           | A320M PRO-VH PLUS           | [0a5b67d3f4](https://linux-hardware.org/?probe=0a5b67d3f4) | Dec 24, 2023 |
| MSI           | PRO Z790-A WIFI             | [8becdfe1a4](https://linux-hardware.org/?probe=8becdfe1a4) | Dec 23, 2023 |
| MSI           | PRO Z790-A WIFI             | [ff13629db9](https://linux-hardware.org/?probe=ff13629db9) | Dec 23, 2023 |
| ASUSTek       | PRIME B460M-A               | [1c7f9648af](https://linux-hardware.org/?probe=1c7f9648af) | Dec 14, 2023 |
| MSI           | A88XM GAMING                | [1f17749a2e](https://linux-hardware.org/?probe=1f17749a2e) | Dec 12, 2023 |
| Gigabyte      | Z77-DS3H                    | [03c91234ae](https://linux-hardware.org/?probe=03c91234ae) | Dec 11, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c71a153915](https://linux-hardware.org/?probe=c71a153915) | Dec 11, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [31943290a3](https://linux-hardware.org/?probe=31943290a3) | Dec 09, 2023 |
| ASUSTek       | PRIME A320M-K               | [74512675b8](https://linux-hardware.org/?probe=74512675b8) | Dec 09, 2023 |
| ASUSTek       | PRIME A320M-K               | [0c4e850e29](https://linux-hardware.org/?probe=0c4e850e29) | Dec 08, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | [46a43fa59d](https://linux-hardware.org/?probe=46a43fa59d) | Dec 02, 2023 |
| Intel         | DG41RQ AAE54511-205         | [8646f4d21b](https://linux-hardware.org/?probe=8646f4d21b) | Dec 01, 2023 |
| Dell          | 0478VN A00                  | [9673d66df0](https://linux-hardware.org/?probe=9673d66df0) | Nov 28, 2023 |
| Gigabyte      | B660M DS3H DDR4             | [ee5fe89209](https://linux-hardware.org/?probe=ee5fe89209) | Nov 28, 2023 |
| ASUSTek       | PRIME B450M-A II            | [e05084a6aa](https://linux-hardware.org/?probe=e05084a6aa) | Nov 26, 2023 |
| Dell          | 0F373D A00                  | [653b4e617f](https://linux-hardware.org/?probe=653b4e617f) | Nov 25, 2023 |
| Dell          | 0F373D A00                  | [92392e304b](https://linux-hardware.org/?probe=92392e304b) | Nov 24, 2023 |
| HP            | 1495                        | [c03adda1fa](https://linux-hardware.org/?probe=c03adda1fa) | Nov 20, 2023 |
| HP            | 8105                        | [d77d0abf96](https://linux-hardware.org/?probe=d77d0abf96) | Nov 15, 2023 |
| HP            | 198E                        | [f1d1b6839f](https://linux-hardware.org/?probe=f1d1b6839f) | Nov 05, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [4236902f3d](https://linux-hardware.org/?probe=4236902f3d) | Nov 03, 2023 |
| Dell          | 0200DY A02                  | [f07206a75c](https://linux-hardware.org/?probe=f07206a75c) | Nov 02, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [385c30cad6](https://linux-hardware.org/?probe=385c30cad6) | Oct 31, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [e3db582993](https://linux-hardware.org/?probe=e3db582993) | Oct 31, 2023 |
| Dell          | 08NPPY A01                  | [62bc2b3e7a](https://linux-hardware.org/?probe=62bc2b3e7a) | Oct 28, 2023 |
| Lenovo        | 0B98409 STD                 | [b89f42b23f](https://linux-hardware.org/?probe=b89f42b23f) | Oct 24, 2023 |
| MSI           | A320M PRO-VH PLUS           | [92dbf8615b](https://linux-hardware.org/?probe=92dbf8615b) | Oct 24, 2023 |
| Intel         | X79G V2.x                   | [49d37b87cf](https://linux-hardware.org/?probe=49d37b87cf) | Oct 21, 2023 |
| ASUSTek       | PRIME B450M-A II            | [b552badf93](https://linux-hardware.org/?probe=b552badf93) | Oct 17, 2023 |
| Intel         | DG41RQ AAE54511-203         | [64738e1724](https://linux-hardware.org/?probe=64738e1724) | Oct 15, 2023 |
| ASUSTek       | H81M-A                      | [0702e52c02](https://linux-hardware.org/?probe=0702e52c02) | Oct 14, 2023 |
| ASUSTek       | PRIME B450M-A II            | [4ba8548e96](https://linux-hardware.org/?probe=4ba8548e96) | Oct 14, 2023 |
| Lenovo        | ThinkCentre M90 5485AK7     | [02e02dbca5](https://linux-hardware.org/?probe=02e02dbca5) | Oct 11, 2023 |
| MACHINIST     | E5-MR9A PRO V1.2            | [668d09e797](https://linux-hardware.org/?probe=668d09e797) | Oct 07, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [6ff82127e5](https://linux-hardware.org/?probe=6ff82127e5) | Oct 05, 2023 |
| Intel         | DG41RQ AAE54511-202         | [5d2ec27525](https://linux-hardware.org/?probe=5d2ec27525) | Oct 03, 2023 |
| ASUSTek       | NAGAMI2                     | [c0e4ce344f](https://linux-hardware.org/?probe=c0e4ce344f) | Sep 14, 2023 |
| Gigabyte      | H61M-S1                     | [c0bbe7d2b4](https://linux-hardware.org/?probe=c0bbe7d2b4) | Sep 09, 2023 |
| MSI           | A320M PRO-VH PLUS           | [9614656d9b](https://linux-hardware.org/?probe=9614656d9b) | Sep 05, 2023 |
| HP            | 82E0                        | [a86ac881df](https://linux-hardware.org/?probe=a86ac881df) | Sep 05, 2023 |
| MSI           | A320M PRO-VH PLUS           | [3e2b7d52c5](https://linux-hardware.org/?probe=3e2b7d52c5) | Sep 05, 2023 |
| Intel         | DG31PR AAD97573-301         | [359e7817c3](https://linux-hardware.org/?probe=359e7817c3) | Sep 03, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [c972b65ed6](https://linux-hardware.org/?probe=c972b65ed6) | Sep 02, 2023 |
| Intel         | X79G V2.x                   | [658431c5b8](https://linux-hardware.org/?probe=658431c5b8) | Aug 22, 2023 |
| ASUSTek       | Pro B550M-C                 | [0af0e7a958](https://linux-hardware.org/?probe=0af0e7a958) | Aug 17, 2023 |
| MSI           | A320M PRO-VH PLUS           | [65a1f155c0](https://linux-hardware.org/?probe=65a1f155c0) | Aug 17, 2023 |
| Intel         | DH61CR AAG14064-207         | [25d122723f](https://linux-hardware.org/?probe=25d122723f) | Aug 15, 2023 |
| Intel         | DH61CR AAG14064-207         | [ae4eca1596](https://linux-hardware.org/?probe=ae4eca1596) | Aug 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | [7637f0d91d](https://linux-hardware.org/?probe=7637f0d91d) | Aug 06, 2023 |
| MSI           | PRO H610M-G WIFI DDR4       | [d8b172537e](https://linux-hardware.org/?probe=d8b172537e) | Aug 04, 2023 |
| MSI           | A320M PRO-VH PLUS           | [f5cc7a2d00](https://linux-hardware.org/?probe=f5cc7a2d00) | Jul 30, 2023 |
| ASRock        | B85M                        | [d69487eb8d](https://linux-hardware.org/?probe=d69487eb8d) | Jul 26, 2023 |
| Gigabyte      | B450M DS3H-CF               | [d8d58cb5fb](https://linux-hardware.org/?probe=d8d58cb5fb) | Jul 21, 2023 |
| MSI           | A320M PRO-VH PLUS           | [689b191bae](https://linux-hardware.org/?probe=689b191bae) | Jul 21, 2023 |
| Intel X79     | Unknown                     | [360facd1fb](https://linux-hardware.org/?probe=360facd1fb) | Jul 19, 2023 |
| MSI           | 970A-G46                    | [09496b3221](https://linux-hardware.org/?probe=09496b3221) | Jul 12, 2023 |
| MSI           | A320M PRO-VH PLUS           | [e99992afd5](https://linux-hardware.org/?probe=e99992afd5) | Jul 12, 2023 |
| HP            | 2820h                       | [ecbafa25c0](https://linux-hardware.org/?probe=ecbafa25c0) | Jul 10, 2023 |
| HP            | 2820h                       | [9d4f48820d](https://linux-hardware.org/?probe=9d4f48820d) | Jul 10, 2023 |
| HP            | 304Ah                       | [029412ce85](https://linux-hardware.org/?probe=029412ce85) | Jul 05, 2023 |
| MSI           | A320M PRO-VH PLUS           | [a7c8848746](https://linux-hardware.org/?probe=a7c8848746) | Jul 03, 2023 |
| Intel         | SHARKBAY                    | [581282a150](https://linux-hardware.org/?probe=581282a150) | Jun 29, 2023 |
| Gigabyte      | H61M-HD2                    | [404728f350](https://linux-hardware.org/?probe=404728f350) | Jun 29, 2023 |
| Gigabyte      | B560M DS3H V2               | [aa24aa071b](https://linux-hardware.org/?probe=aa24aa071b) | Jun 28, 2023 |
| ASRock        | H55M                        | [cb9e89e20e](https://linux-hardware.org/?probe=cb9e89e20e) | Jun 24, 2023 |
| ASUSTek       | PRIME H410M-E               | [cc8a15081a](https://linux-hardware.org/?probe=cc8a15081a) | Jun 22, 2023 |
| Acer          | Veriton X490G               | [a181339180](https://linux-hardware.org/?probe=a181339180) | Jun 20, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [5ff46d41fd](https://linux-hardware.org/?probe=5ff46d41fd) | Jun 18, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [ddb9fc5a43](https://linux-hardware.org/?probe=ddb9fc5a43) | Jun 14, 2023 |
| Gigabyte      | B560M DS3H V2               | [1b8ad811e0](https://linux-hardware.org/?probe=1b8ad811e0) | Jun 12, 2023 |
| HP            | 82C9                        | [b696990030](https://linux-hardware.org/?probe=b696990030) | Jun 09, 2023 |
| HP            | 18EA                        | [d6e48a99e7](https://linux-hardware.org/?probe=d6e48a99e7) | Jun 08, 2023 |
| Acer          | Predator G3-710             | [7193d24262](https://linux-hardware.org/?probe=7193d24262) | Jun 04, 2023 |
| Acer          | Predator G3-710             | [96834ea12b](https://linux-hardware.org/?probe=96834ea12b) | Jun 04, 2023 |
| Acer          | Predator G3-710             | [c200dbb9cf](https://linux-hardware.org/?probe=c200dbb9cf) | Jun 04, 2023 |
| MSI           | A320M PRO-VH PLUS           | [8ba76b1e88](https://linux-hardware.org/?probe=8ba76b1e88) | Jun 03, 2023 |
| Gigabyte      | H61M-HD2                    | [7c57f43d4a](https://linux-hardware.org/?probe=7c57f43d4a) | May 29, 2023 |
| ASRock        | B450M-HDV R4.0              | [063077bd52](https://linux-hardware.org/?probe=063077bd52) | May 25, 2023 |
| Gigabyte      | B450M DS3H-CF               | [87a75f9dd9](https://linux-hardware.org/?probe=87a75f9dd9) | May 16, 2023 |
| Gigabyte      | GA-990FX-GAMING             | [d7503c22b2](https://linux-hardware.org/?probe=d7503c22b2) | May 16, 2023 |
| Gigabyte      | GA-990FX-GAMING             | [cc42c4e227](https://linux-hardware.org/?probe=cc42c4e227) | May 15, 2023 |
| ASUSTek       | PRIME A320M-K               | [a375533daa](https://linux-hardware.org/?probe=a375533daa) | May 05, 2023 |
| Gigabyte      | Z590 VISION G               | [d37eb8bf49](https://linux-hardware.org/?probe=d37eb8bf49) | May 04, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [2dffd7bed6](https://linux-hardware.org/?probe=2dffd7bed6) | Apr 30, 2023 |
| Pegatron      | 2A73h                       | [f4578519ad](https://linux-hardware.org/?probe=f4578519ad) | Apr 21, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [c4d3eabb55](https://linux-hardware.org/?probe=c4d3eabb55) | Apr 17, 2023 |
| ASUSTek       | PRIME X570-P                | [337102cd4c](https://linux-hardware.org/?probe=337102cd4c) | Apr 15, 2023 |
| Gigabyte      | H61M-HD2                    | [ea4bae8ef7](https://linux-hardware.org/?probe=ea4bae8ef7) | Apr 13, 2023 |
| ASUSTek       | M4N98TD EVO                 | [a2423b5193](https://linux-hardware.org/?probe=a2423b5193) | Apr 07, 2023 |
| ASUSTek       | M4N98TD EVO                 | [8a2a2cf1ce](https://linux-hardware.org/?probe=8a2a2cf1ce) | Apr 07, 2023 |
| Gigabyte      | H310M H x.x                 | [a927671ce2](https://linux-hardware.org/?probe=a927671ce2) | Mar 29, 2023 |
| Lenovo        | ThinkServer TS130           | [2a36fc5043](https://linux-hardware.org/?probe=2a36fc5043) | Mar 28, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [5c811e496f](https://linux-hardware.org/?probe=5c811e496f) | Mar 24, 2023 |
| ASUSTek       | M4N98TD EVO                 | [9cb4b84924](https://linux-hardware.org/?probe=9cb4b84924) | Mar 24, 2023 |
| ASRock        | X670E Pro RS                | [8437e47a82](https://linux-hardware.org/?probe=8437e47a82) | Mar 24, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [592d9de1cb](https://linux-hardware.org/?probe=592d9de1cb) | Mar 23, 2023 |
| HP            | 18E9                        | [2cc6071591](https://linux-hardware.org/?probe=2cc6071591) | Mar 20, 2023 |
| Lenovo        | MAHOBAY NOK                 | [04ba5a6790](https://linux-hardware.org/?probe=04ba5a6790) | Mar 18, 2023 |
| Lenovo        | MAHOBAY NOK                 | [fcbb054633](https://linux-hardware.org/?probe=fcbb054633) | Mar 18, 2023 |
| HP            | 1850                        | [c805a3a08f](https://linux-hardware.org/?probe=c805a3a08f) | Mar 17, 2023 |
| Gigabyte      | B550 AORUS PRO              | [b72b91fd00](https://linux-hardware.org/?probe=b72b91fd00) | Mar 16, 2023 |
| MSI           | H81M-P33                    | [cb3d11f591](https://linux-hardware.org/?probe=cb3d11f591) | Mar 15, 2023 |
| HP            | 1850                        | [c5439b2fea](https://linux-hardware.org/?probe=c5439b2fea) | Mar 15, 2023 |
| ASRock        | G31M-S                      | [7672cc15a2](https://linux-hardware.org/?probe=7672cc15a2) | Mar 13, 2023 |
| Biostar       | H61MHV                      | [9f184e6e93](https://linux-hardware.org/?probe=9f184e6e93) | Mar 11, 2023 |
| Intel         | DH61BF AAG81311-101         | [b960fb0ebf](https://linux-hardware.org/?probe=b960fb0ebf) | Mar 08, 2023 |
| Gigabyte      | H81M-H                      | [6f915814dd](https://linux-hardware.org/?probe=6f915814dd) | Mar 08, 2023 |
| Gigabyte      | H81M-H                      | [5fdd1701df](https://linux-hardware.org/?probe=5fdd1701df) | Mar 08, 2023 |
| Acer          | Aspire X1400                | [195337bbc6](https://linux-hardware.org/?probe=195337bbc6) | Mar 07, 2023 |
| Gigabyte      | B460M AORUS PRO             | [829848b662](https://linux-hardware.org/?probe=829848b662) | Mar 04, 2023 |
| HP            | 806A                        | [66c29ddd8a](https://linux-hardware.org/?probe=66c29ddd8a) | Mar 03, 2023 |
| HP            | 2ADE                        | [b4309c2b06](https://linux-hardware.org/?probe=b4309c2b06) | Feb 23, 2023 |
| ASRock        | X670E Pro RS                | [906d11e2a3](https://linux-hardware.org/?probe=906d11e2a3) | Feb 19, 2023 |
| HP            | 18E9                        | [e3461fcb74](https://linux-hardware.org/?probe=e3461fcb74) | Feb 16, 2023 |
| HP            | 1497                        | [b27560d384](https://linux-hardware.org/?probe=b27560d384) | Feb 14, 2023 |
| Gigabyte      | Z87X-D3H-CF                 | [e4496f3ff8](https://linux-hardware.org/?probe=e4496f3ff8) | Feb 11, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [5fe8eef781](https://linux-hardware.org/?probe=5fe8eef781) | Feb 09, 2023 |
| Unknown       | X79A                        | [eedea973ca](https://linux-hardware.org/?probe=eedea973ca) | Feb 05, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [edbd391f2d](https://linux-hardware.org/?probe=edbd391f2d) | Feb 05, 2023 |
| Gigabyte      | B450M DS3H-CF               | [e2d354b9c5](https://linux-hardware.org/?probe=e2d354b9c5) | Jan 25, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [0c65146f4c](https://linux-hardware.org/?probe=0c65146f4c) | Jan 21, 2023 |
| Intel         | DH61BF AAG81311-101         | [d6ea5bde87](https://linux-hardware.org/?probe=d6ea5bde87) | Jan 21, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [d0a387f425](https://linux-hardware.org/?probe=d0a387f425) | Jan 18, 2023 |
| ASRock        | G965M-S                     | [c1a6d7685b](https://linux-hardware.org/?probe=c1a6d7685b) | Jan 17, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [d569a3f698](https://linux-hardware.org/?probe=d569a3f698) | Jan 15, 2023 |
| Gigabyte      | A320M-S2H-CF                | [d26bcd74b2](https://linux-hardware.org/?probe=d26bcd74b2) | Jan 10, 2023 |
| Gigabyte      | A320M-S2H-CF                | [faf7e2eae9](https://linux-hardware.org/?probe=faf7e2eae9) | Jan 10, 2023 |
| Gigabyte      | A520M DS3H                  | [e7107ee8b4](https://linux-hardware.org/?probe=e7107ee8b4) | Jan 06, 2023 |
| Gigabyte      | A520M DS3H                  | [e351ff5e1d](https://linux-hardware.org/?probe=e351ff5e1d) | Jan 05, 2023 |
| Intel         | DH61BF AAG81311-101         | [db8d3007ee](https://linux-hardware.org/?probe=db8d3007ee) | Jan 03, 2023 |
| MSI           | 880GM-E41                   | [2880803d71](https://linux-hardware.org/?probe=2880803d71) | Dec 23, 2022 |
| Gigabyte      | B450M DS3H-CF               | [fe4ef75450](https://linux-hardware.org/?probe=fe4ef75450) | Dec 21, 2022 |
| Lenovo        | ThinkCentre A62 9486E4S     | [cb7cb7b7d7](https://linux-hardware.org/?probe=cb7cb7b7d7) | Dec 21, 2022 |
| Lenovo        | ThinkCentre A62 9486E4S     | [fcd0306cd3](https://linux-hardware.org/?probe=fcd0306cd3) | Dec 19, 2022 |
| ASUSTek       | M3N78-VM                    | [fa99389a1a](https://linux-hardware.org/?probe=fa99389a1a) | Dec 10, 2022 |
| HP            | 18E9                        | [9086d1a1e5](https://linux-hardware.org/?probe=9086d1a1e5) | Dec 01, 2022 |
| ASUSTek       | P5K WS                      | [f3608476bf](https://linux-hardware.org/?probe=f3608476bf) | Dec 01, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [80b8b349f8](https://linux-hardware.org/?probe=80b8b349f8) | Nov 30, 2022 |
| Dell          | 0TP406                      | [3eceea61d2](https://linux-hardware.org/?probe=3eceea61d2) | Nov 30, 2022 |
| Dell          | 0TP406                      | [d22689331c](https://linux-hardware.org/?probe=d22689331c) | Nov 30, 2022 |
| HP            | 339A                        | [ea5cacd50e](https://linux-hardware.org/?probe=ea5cacd50e) | Nov 29, 2022 |
| Dell          | 0HJ054                      | [0e3d082d5a](https://linux-hardware.org/?probe=0e3d082d5a) | Nov 22, 2022 |
| Lenovo        | ThinkCentre M70e 0830AC4    | [8eb9b40274](https://linux-hardware.org/?probe=8eb9b40274) | Nov 10, 2022 |
| MSI           | GF615M-P33                  | [1a298da454](https://linux-hardware.org/?probe=1a298da454) | Nov 09, 2022 |
| Intel         | D33217GKE G76540-207        | [f90e6e931c](https://linux-hardware.org/?probe=f90e6e931c) | Nov 07, 2022 |
| Intel         | D33217GKE G76540-207        | [a154fd19a0](https://linux-hardware.org/?probe=a154fd19a0) | Nov 07, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [a5d58af861](https://linux-hardware.org/?probe=a5d58af861) | Oct 31, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [b132f4c4e9](https://linux-hardware.org/?probe=b132f4c4e9) | Oct 30, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [7e1df59daa](https://linux-hardware.org/?probe=7e1df59daa) | Oct 30, 2022 |
| Biostar       | H61MH                       | [f505de310c](https://linux-hardware.org/?probe=f505de310c) | Oct 27, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [6edc8b1444](https://linux-hardware.org/?probe=6edc8b1444) | Oct 06, 2022 |
| Gigabyte      | G41MT-S2                    | [c0b1c8ad8f](https://linux-hardware.org/?probe=c0b1c8ad8f) | Sep 27, 2022 |
| HP            | 18E7                        | [710a40851e](https://linux-hardware.org/?probe=710a40851e) | Sep 18, 2022 |
| ASRock        | A520M-HDV                   | [9e4267bcc6](https://linux-hardware.org/?probe=9e4267bcc6) | Sep 15, 2022 |
| ASRock        | A520M-HDV                   | [bd9b94b7f8](https://linux-hardware.org/?probe=bd9b94b7f8) | Sep 15, 2022 |
| HP            | 1494                        | [0faa06cff4](https://linux-hardware.org/?probe=0faa06cff4) | Sep 12, 2022 |
| ECS           | H61H2-M2                    | [9735a8ef90](https://linux-hardware.org/?probe=9735a8ef90) | Sep 01, 2022 |
| Pegatron      | 2AB6                        | [93af020634](https://linux-hardware.org/?probe=93af020634) | Aug 27, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [04474401fc](https://linux-hardware.org/?probe=04474401fc) | Aug 26, 2022 |
| ECS           | H61H2-M2                    | [72ebc08e0c](https://linux-hardware.org/?probe=72ebc08e0c) | Aug 26, 2022 |
| ASUSTek       | TUF B365-PLUS GAMING        | [83e59cf9a5](https://linux-hardware.org/?probe=83e59cf9a5) | Aug 25, 2022 |
| ASUSTek       | PRIME A320M-K               | [928ce75df1](https://linux-hardware.org/?probe=928ce75df1) | Aug 24, 2022 |
| ECS           | H61H2-M2                    | [97ec1c67e8](https://linux-hardware.org/?probe=97ec1c67e8) | Aug 21, 2022 |
| BESSTAR Te... | TH50                        | [03159c112c](https://linux-hardware.org/?probe=03159c112c) | Aug 12, 2022 |
| ASRock        | B550M Pro4                  | [7fa92e1cb6](https://linux-hardware.org/?probe=7fa92e1cb6) | Aug 09, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [08b891334e](https://linux-hardware.org/?probe=08b891334e) | Aug 08, 2022 |
| HP            | ProLiant ML310e Gen8        | [7a12318176](https://linux-hardware.org/?probe=7a12318176) | Aug 02, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [68d8843883](https://linux-hardware.org/?probe=68d8843883) | Jul 17, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [057b18a904](https://linux-hardware.org/?probe=057b18a904) | Jul 16, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [97b45f9af7](https://linux-hardware.org/?probe=97b45f9af7) | Jul 12, 2022 |
| Dell          | 054KM3 A01                  | [149f746382](https://linux-hardware.org/?probe=149f746382) | Jul 02, 2022 |
| ASRock        | A320M-HDV                   | [ec991b1524](https://linux-hardware.org/?probe=ec991b1524) | Jun 27, 2022 |
| MSI           | H81M-E33                    | [d79b11186c](https://linux-hardware.org/?probe=d79b11186c) | Jun 26, 2022 |
| ASRock        | Z77 Extreme4                | [8caff7e62e](https://linux-hardware.org/?probe=8caff7e62e) | Jun 25, 2022 |
| Dell          | 0J2J3Y A00                  | [50f015312c](https://linux-hardware.org/?probe=50f015312c) | Jun 23, 2022 |
| MSI           | H81M-E33                    | [0d2ace0dde](https://linux-hardware.org/?probe=0d2ace0dde) | Jun 16, 2022 |
| MSI           | H81M-E33                    | [52dbd6f482](https://linux-hardware.org/?probe=52dbd6f482) | Jun 16, 2022 |
| Gigabyte      | H61M-HD2                    | [d6e6a17072](https://linux-hardware.org/?probe=d6e6a17072) | Jun 13, 2022 |
| MSI           | G31TM-P21                   | [824dc8a1c9](https://linux-hardware.org/?probe=824dc8a1c9) | Jun 11, 2022 |
| HP            | 8054                        | [7d7b7577db](https://linux-hardware.org/?probe=7d7b7577db) | Jun 01, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2bd8d64c3b](https://linux-hardware.org/?probe=2bd8d64c3b) | May 22, 2022 |
| Gigabyte      | 990FXA-UD3                  | [4bc8f93383](https://linux-hardware.org/?probe=4bc8f93383) | May 17, 2022 |
| Gigabyte      | 990FXA-UD3                  | [89b16a89c5](https://linux-hardware.org/?probe=89b16a89c5) | May 16, 2022 |
| ASUSTek       | H81M-K                      | [753c7be679](https://linux-hardware.org/?probe=753c7be679) | May 05, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [af01f27647](https://linux-hardware.org/?probe=af01f27647) | Apr 30, 2022 |
| Pegatron      | 2A73h                       | [a756a0148d](https://linux-hardware.org/?probe=a756a0148d) | Apr 27, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [7b24feb14a](https://linux-hardware.org/?probe=7b24feb14a) | Apr 21, 2022 |
| ASUSTek       | PRIME Z390-A                | [81d7ace164](https://linux-hardware.org/?probe=81d7ace164) | Apr 18, 2022 |
| Gigabyte      | B550 AORUS ELITE            | [65a5442605](https://linux-hardware.org/?probe=65a5442605) | Apr 04, 2022 |
| HP            | ProLiant ML150 Gen9         | [50114897cc](https://linux-hardware.org/?probe=50114897cc) | Apr 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [066fb2b2b9](https://linux-hardware.org/?probe=066fb2b2b9) | Mar 30, 2022 |
| ASRock        | G41M-VS3                    | [34ccbe7db2](https://linux-hardware.org/?probe=34ccbe7db2) | Mar 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [13cdf54c81](https://linux-hardware.org/?probe=13cdf54c81) | Mar 21, 2022 |
| ASUSTek       | PRIME H410M-E               | [1f267ffe6e](https://linux-hardware.org/?probe=1f267ffe6e) | Mar 11, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [d068227c07](https://linux-hardware.org/?probe=d068227c07) | Mar 06, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [ac671d5e38](https://linux-hardware.org/?probe=ac671d5e38) | Mar 05, 2022 |
| Supermicro    | X7DA8                       | [fcf69abc8f](https://linux-hardware.org/?probe=fcf69abc8f) | Feb 25, 2022 |
| Gigabyte      | H410M H V3                  | [4c58660705](https://linux-hardware.org/?probe=4c58660705) | Feb 22, 2022 |
| ASUSTek       | PRIME H310-PLUS             | [217c73c9a6](https://linux-hardware.org/?probe=217c73c9a6) | Feb 11, 2022 |
| ASRock        | Z77 Extreme4                | [95b7145bd2](https://linux-hardware.org/?probe=95b7145bd2) | Feb 06, 2022 |
| HP            | 1587h                       | [92625959b4](https://linux-hardware.org/?probe=92625959b4) | Feb 02, 2022 |
| ASUSTek       | H61M-K                      | [c7a35398d0](https://linux-hardware.org/?probe=c7a35398d0) | Feb 02, 2022 |
| ASUSTek       | PRIME H410M-E               | [876f78e96c](https://linux-hardware.org/?probe=876f78e96c) | Feb 01, 2022 |
| Intel         | DH61HO AAG62445-102         | [e0cbedce41](https://linux-hardware.org/?probe=e0cbedce41) | Jan 30, 2022 |
| Foxconn       | H61MXL/H61MXL-K             | [9b0853e1e9](https://linux-hardware.org/?probe=9b0853e1e9) | Jan 29, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [f967c472e5](https://linux-hardware.org/?probe=f967c472e5) | Jan 27, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [e92de9ab2e](https://linux-hardware.org/?probe=e92de9ab2e) | Jan 27, 2022 |
| Gigabyte      | H410M H                     | [1ca8a84549](https://linux-hardware.org/?probe=1ca8a84549) | Jan 25, 2022 |
| ASUSTek       | Maximus IX CODE             | [32c7db26bd](https://linux-hardware.org/?probe=32c7db26bd) | Jan 08, 2022 |
| ASRock        | H110M-HDV R3.0              | [90fe76c900](https://linux-hardware.org/?probe=90fe76c900) | Jan 03, 2022 |
| MSI           | H81M-E33                    | [a7e25b05e2](https://linux-hardware.org/?probe=a7e25b05e2) | Dec 27, 2021 |
| ASUSTek       | ROG STRIX B460-I GAMING     | [258369e6dc](https://linux-hardware.org/?probe=258369e6dc) | Dec 24, 2021 |
| MSI           | B150A GAMING PRO            | [475ea42f9a](https://linux-hardware.org/?probe=475ea42f9a) | Dec 11, 2021 |
| HP            | 3047h                       | [b389ca7104](https://linux-hardware.org/?probe=b389ca7104) | Dec 08, 2021 |
| MSI           | 760GM-P23                   | [cbe2fcd79d](https://linux-hardware.org/?probe=cbe2fcd79d) | Nov 26, 2021 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [92d9d82670](https://linux-hardware.org/?probe=92d9d82670) | Nov 25, 2021 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [e3a6c887f6](https://linux-hardware.org/?probe=e3a6c887f6) | Nov 25, 2021 |
| ASRock        | G41M-VS3                    | [35277b1155](https://linux-hardware.org/?probe=35277b1155) | Nov 22, 2021 |
| ASUSTek       | PRIME X570-P                | [abd0cfab6b](https://linux-hardware.org/?probe=abd0cfab6b) | Nov 12, 2021 |
| ASUSTek       | PRIME X570-P                | [27aa14962f](https://linux-hardware.org/?probe=27aa14962f) | Nov 12, 2021 |
| ASUSTek       | PRIME B550M-K               | [de9d0e2b40](https://linux-hardware.org/?probe=de9d0e2b40) | Nov 08, 2021 |
| ASRock        | G41M-VS3                    | [bf54c2ee53](https://linux-hardware.org/?probe=bf54c2ee53) | Nov 04, 2021 |
| ASRock        | G41M-VS3                    | [2ee1cbdc82](https://linux-hardware.org/?probe=2ee1cbdc82) | Nov 03, 2021 |
| Gigabyte      | P67A-UD3-B3                 | [c196661531](https://linux-hardware.org/?probe=c196661531) | Nov 01, 2021 |
| MSI           | 2A9Ch                       | [2f752a1a3e](https://linux-hardware.org/?probe=2f752a1a3e) | Oct 28, 2021 |
| Gigabyte      | H81M-H                      | [eb596b1774](https://linux-hardware.org/?probe=eb596b1774) | Oct 25, 2021 |
| ASUSTek       | PRIME H310-PLUS             | [cdd35d634d](https://linux-hardware.org/?probe=cdd35d634d) | Oct 24, 2021 |
| ASUSTek       | PRIME B550M-K               | [d9c192ea8c](https://linux-hardware.org/?probe=d9c192ea8c) | Oct 23, 2021 |
| ASRock        | G41M-VS3                    | [267bee9221](https://linux-hardware.org/?probe=267bee9221) | Oct 21, 2021 |
| HP            | 0B4Ch D                     | [d0b6443f5b](https://linux-hardware.org/?probe=d0b6443f5b) | Oct 12, 2021 |
| Gigabyte      | B450M DS3H-CF               | [05c0fc8d29](https://linux-hardware.org/?probe=05c0fc8d29) | Oct 10, 2021 |
| ASUSTek       | PRIME B550M-K               | [d034cd0b4a](https://linux-hardware.org/?probe=d034cd0b4a) | Oct 07, 2021 |
| Foxconn       | H61MXE                      | [f684b8da61](https://linux-hardware.org/?probe=f684b8da61) | Oct 06, 2021 |
| ASRock        | G41M-VS3                    | [9c4f3417d4](https://linux-hardware.org/?probe=9c4f3417d4) | Oct 04, 2021 |
| ASRock        | G41M-VS3                    | [3e695d6744](https://linux-hardware.org/?probe=3e695d6744) | Oct 04, 2021 |
| Pegatron      | 2AE2                        | [0309cddc66](https://linux-hardware.org/?probe=0309cddc66) | Oct 02, 2021 |
| ASUSTek       | Z97-A                       | [6476a95a04](https://linux-hardware.org/?probe=6476a95a04) | Sep 27, 2021 |
| Biostar       | G41D3C                      | [16eb676e0c](https://linux-hardware.org/?probe=16eb676e0c) | Sep 25, 2021 |
| ASUSTek       | PRIME B550M-K               | [b30800b2f9](https://linux-hardware.org/?probe=b30800b2f9) | Sep 24, 2021 |
| Gigabyte      | H81M-H                      | [f214b7efbe](https://linux-hardware.org/?probe=f214b7efbe) | Sep 22, 2021 |
| ECS           | G31T-M7                     | [60bf966d06](https://linux-hardware.org/?probe=60bf966d06) | Sep 18, 2021 |
| ASRock        | G41M-VS3                    | [7922da571d](https://linux-hardware.org/?probe=7922da571d) | Sep 16, 2021 |
| ASRock        | G41M-VS3                    | [e7afe651d3](https://linux-hardware.org/?probe=e7afe651d3) | Sep 16, 2021 |
| HP            | 18E9                        | [7a7dd34d6d](https://linux-hardware.org/?probe=7a7dd34d6d) | Sep 13, 2021 |
| MSI           | B350M GAMING PRO            | [052bfbd512](https://linux-hardware.org/?probe=052bfbd512) | Sep 09, 2021 |
| MSI           | B350M GAMING PRO            | [a3b7774236](https://linux-hardware.org/?probe=a3b7774236) | Sep 09, 2021 |
| Intel         | D945GCLF2D AAE59323-101     | [d6808fecbf](https://linux-hardware.org/?probe=d6808fecbf) | Sep 07, 2021 |
| ASUSTek       | PRIME B450M-A II            | [cb9f02b3de](https://linux-hardware.org/?probe=cb9f02b3de) | Sep 07, 2021 |
| ASUSTek       | PRIME B450M-A II            | [f80365b98a](https://linux-hardware.org/?probe=f80365b98a) | Sep 07, 2021 |
| Gigabyte      | G31M-S2C                    | [15d48710db](https://linux-hardware.org/?probe=15d48710db) | Aug 24, 2021 |
| Pegatron      | 2AEE                        | [a3e6da7d21](https://linux-hardware.org/?probe=a3e6da7d21) | Aug 22, 2021 |
| Pegatron      | 2AEE                        | [0b0cf520ba](https://linux-hardware.org/?probe=0b0cf520ba) | Aug 22, 2021 |
| Gigabyte      | G31M-S2C                    | [a8d5b4ff89](https://linux-hardware.org/?probe=a8d5b4ff89) | Aug 22, 2021 |
| HP            | 18E9                        | [9ee974d2df](https://linux-hardware.org/?probe=9ee974d2df) | Aug 21, 2021 |
| HP            | 18E9                        | [838f27241e](https://linux-hardware.org/?probe=838f27241e) | Aug 21, 2021 |
| HP            | 304Ah                       | [4760a65d2f](https://linux-hardware.org/?probe=4760a65d2f) | Aug 20, 2021 |
| HP            | 304Ah                       | [67e7cc53c1](https://linux-hardware.org/?probe=67e7cc53c1) | Aug 18, 2021 |
| Intel         | DB75EN AAG39650-303         | [321af82bbf](https://linux-hardware.org/?probe=321af82bbf) | Aug 09, 2021 |
| Gigabyte      | B550M DS3H                  | [418d6ee68f](https://linux-hardware.org/?probe=418d6ee68f) | Jul 23, 2021 |
| Intel         | DH55HC AAE70933-505         | [e8b5870e50](https://linux-hardware.org/?probe=e8b5870e50) | Jul 19, 2021 |
| MSI           | MS-7309                     | [8b431e8b6f](https://linux-hardware.org/?probe=8b431e8b6f) | Jul 10, 2021 |
| ASRock        | Wolfdale1333-D667           | [7b71d5854c](https://linux-hardware.org/?probe=7b71d5854c) | Jul 01, 2021 |
| ASUSTek       | PRIME Z590-P                | [5530b28aa3](https://linux-hardware.org/?probe=5530b28aa3) | Jun 30, 2021 |
| ASUSTek       | PRIME Z590-P                | [582e4795cf](https://linux-hardware.org/?probe=582e4795cf) | Jun 30, 2021 |
| Intel         | H61                         | [50b0503c3c](https://linux-hardware.org/?probe=50b0503c3c) | Jun 07, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [2a6868991a](https://linux-hardware.org/?probe=2a6868991a) | May 27, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | [33c1ecc56e](https://linux-hardware.org/?probe=33c1ecc56e) | May 19, 2021 |
| Gigabyte      | Z68X-UD7-B3                 | [22eae98fb5](https://linux-hardware.org/?probe=22eae98fb5) | May 13, 2021 |
| ECS           | H81H3-M4                    | [6889e28bfd](https://linux-hardware.org/?probe=6889e28bfd) | May 09, 2021 |
| ECS           | H81H3-M4                    | [0ef93e6291](https://linux-hardware.org/?probe=0ef93e6291) | May 09, 2021 |
| ASRock        | G965M-S                     | [dd116582af](https://linux-hardware.org/?probe=dd116582af) | May 03, 2021 |
| Intel         | H61                         | [cca60711c8](https://linux-hardware.org/?probe=cca60711c8) | May 01, 2021 |
| ASUSTek       | M4A77T/USB3                 | [ae115d5ca8](https://linux-hardware.org/?probe=ae115d5ca8) | Apr 29, 2021 |
| ASUSTek       | M4A77T/USB3                 | [34733fe16f](https://linux-hardware.org/?probe=34733fe16f) | Apr 29, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [037a465656](https://linux-hardware.org/?probe=037a465656) | Apr 28, 2021 |
| MSI           | 970A-G46                    | [f1035827e0](https://linux-hardware.org/?probe=f1035827e0) | Apr 26, 2021 |
| Unknown       | 4CoreDX90-VSTA              | [6410827a2f](https://linux-hardware.org/?probe=6410827a2f) | Apr 25, 2021 |
| Unknown       | 4CoreDX90-VSTA              | [a8c42b2d94](https://linux-hardware.org/?probe=a8c42b2d94) | Apr 25, 2021 |
| MSI           | 970A-G46                    | [9aa4264419](https://linux-hardware.org/?probe=9aa4264419) | Apr 22, 2021 |
| MSI           | K9A2 Platinum               | [fc4fd8ba0e](https://linux-hardware.org/?probe=fc4fd8ba0e) | Apr 19, 2021 |
| Gigabyte      | X399 AORUS PRO-CF           | [7585c05b18](https://linux-hardware.org/?probe=7585c05b18) | Apr 19, 2021 |
| MSI           | K9A2 Platinum               | [ef223aa1d5](https://linux-hardware.org/?probe=ef223aa1d5) | Apr 16, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | [48ab0d2acd](https://linux-hardware.org/?probe=48ab0d2acd) | Apr 14, 2021 |
| ASRock        | N68-VS3 UCC                 | [72861aa353](https://linux-hardware.org/?probe=72861aa353) | Apr 09, 2021 |
| Gigabyte      | X399 AORUS PRO-CF           | [cc61b2b6a7](https://linux-hardware.org/?probe=cc61b2b6a7) | Apr 04, 2021 |
| Gigabyte      | X399 AORUS PRO-CF           | [c079cb8fac](https://linux-hardware.org/?probe=c079cb8fac) | Apr 01, 2021 |
| Gigabyte      | B550M AORUS PRO-P           | [26427e6d23](https://linux-hardware.org/?probe=26427e6d23) | Mar 29, 2021 |
| Dell          | 0G3HR7 A00                  | [f2760185e3](https://linux-hardware.org/?probe=f2760185e3) | Mar 26, 2021 |
| Intel         | DH55HC AAE70933-505         | [2ebfc03ce7](https://linux-hardware.org/?probe=2ebfc03ce7) | Mar 20, 2021 |
| Dell          | 0G3HR7 A00                  | [29c1565b42](https://linux-hardware.org/?probe=29c1565b42) | Mar 10, 2021 |
| Gigabyte      | H61M-S1                     | [98d2580d9e](https://linux-hardware.org/?probe=98d2580d9e) | Mar 06, 2021 |
| Gigabyte      | H61M-S1                     | [91cd908a95](https://linux-hardware.org/?probe=91cd908a95) | Mar 05, 2021 |
| HP            | 2B09                        | [44e3728303](https://linux-hardware.org/?probe=44e3728303) | Mar 05, 2021 |
| ASRock        | Wolfdale1333-D667           | [4cb354b544](https://linux-hardware.org/?probe=4cb354b544) | Mar 02, 2021 |
| Intel         | DP67DE AAG10217-205         | [4b376912e1](https://linux-hardware.org/?probe=4b376912e1) | Feb 23, 2021 |
| Intel         | DP67DE AAG10217-205         | [497e0558af](https://linux-hardware.org/?probe=497e0558af) | Feb 23, 2021 |
| ASRock        | Wolfdale1333-D667           | [ed29a42a57](https://linux-hardware.org/?probe=ed29a42a57) | Feb 23, 2021 |
| MSI           | A320M-A PRO MAX             | [fb6179a8ee](https://linux-hardware.org/?probe=fb6179a8ee) | Feb 16, 2021 |
| Gigabyte      | B450M DS3H-CF               | [5f9a9ff276](https://linux-hardware.org/?probe=5f9a9ff276) | Feb 13, 2021 |
| Gigabyte      | B450M DS3H-CF               | [d8069f1e01](https://linux-hardware.org/?probe=d8069f1e01) | Feb 12, 2021 |
| Dell          | 0HN7XN A01                  | [909121ec95](https://linux-hardware.org/?probe=909121ec95) | Feb 03, 2021 |
| ASRock        | G41M-VS3                    | [b7460ea1e6](https://linux-hardware.org/?probe=b7460ea1e6) | Feb 02, 2021 |
| ECS           | H81H3-M4                    | [b452e9e060](https://linux-hardware.org/?probe=b452e9e060) | Jan 27, 2021 |
| ASUSTek       | PRIME H310M-E               | [cb63800c0d](https://linux-hardware.org/?probe=cb63800c0d) | Jan 24, 2021 |
| ASUSTek       | PRIME H310M-E               | [eb46844f3e](https://linux-hardware.org/?probe=eb46844f3e) | Jan 24, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | [8dcbe2b63e](https://linux-hardware.org/?probe=8dcbe2b63e) | Jan 15, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | [c969271698](https://linux-hardware.org/?probe=c969271698) | Jan 15, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [9bd74368f0](https://linux-hardware.org/?probe=9bd74368f0) | Jan 15, 2021 |
| Intel         | H61                         | [d8489ff473](https://linux-hardware.org/?probe=d8489ff473) | Jan 11, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | [81ab4a6cc7](https://linux-hardware.org/?probe=81ab4a6cc7) | Jan 11, 2021 |
| MSI           | B450M BAZOOKA V2            | [d68301770d](https://linux-hardware.org/?probe=d68301770d) | Jan 05, 2021 |
| Biostar       | H61MHV                      | [60f41299a7](https://linux-hardware.org/?probe=60f41299a7) | Jan 04, 2021 |
| Gigabyte      | 970A-UD3                    | [4de6e16ced](https://linux-hardware.org/?probe=4de6e16ced) | Dec 30, 2020 |
| Dell          | 0G3HR7 A00                  | [1c8f1911c4](https://linux-hardware.org/?probe=1c8f1911c4) | Dec 29, 2020 |
| PCSMART       | Unknown                     | [5c91c760a5](https://linux-hardware.org/?probe=5c91c760a5) | Dec 28, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [69e3d131e9](https://linux-hardware.org/?probe=69e3d131e9) | Dec 16, 2020 |
| ASRock        | G41M-VS3                    | [7633d83de8](https://linux-hardware.org/?probe=7633d83de8) | Dec 08, 2020 |
| ECS           | G31T-M7                     | [da86a0de6d](https://linux-hardware.org/?probe=da86a0de6d) | Dec 06, 2020 |
| ECS           | H81H3-M4                    | [324e08922c](https://linux-hardware.org/?probe=324e08922c) | Nov 23, 2020 |
| ASRock        | B450M Pro4                  | [63124c698a](https://linux-hardware.org/?probe=63124c698a) | Nov 22, 2020 |
| Foxconn       | 2ABF                        | [fa95d7cd22](https://linux-hardware.org/?probe=fa95d7cd22) | Nov 21, 2020 |
| ASRock        | AB350M-HDV                  | [4a503972bc](https://linux-hardware.org/?probe=4a503972bc) | Nov 18, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [a802e86d43](https://linux-hardware.org/?probe=a802e86d43) | Nov 07, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [a39151865e](https://linux-hardware.org/?probe=a39151865e) | Nov 06, 2020 |
| ASRock        | 960GM-VGS3 FX               | [5c51163253](https://linux-hardware.org/?probe=5c51163253) | Nov 05, 2020 |
| ASRock        | A320M-HDV                   | [c4f1aaa3bb](https://linux-hardware.org/?probe=c4f1aaa3bb) | Nov 02, 2020 |
| ASRock        | A320M-HDV                   | [a283f0ab00](https://linux-hardware.org/?probe=a283f0ab00) | Nov 01, 2020 |
| Foxconn       | 2ABF                        | [98e0846229](https://linux-hardware.org/?probe=98e0846229) | Oct 28, 2020 |
| ASRock        | G31M-GS                     | [ed0373efb3](https://linux-hardware.org/?probe=ed0373efb3) | Oct 22, 2020 |
| MSI           | H81M-E33                    | [dc82b20825](https://linux-hardware.org/?probe=dc82b20825) | Oct 20, 2020 |
| MSI           | H81M-E33                    | [21a8676b32](https://linux-hardware.org/?probe=21a8676b32) | Oct 20, 2020 |
| ASRock        | B450M-HDV R4.0              | [d1e0bb32d7](https://linux-hardware.org/?probe=d1e0bb32d7) | Oct 19, 2020 |
| Lenovo        | ThinkCentre A58 7515A18     | [6d228ca955](https://linux-hardware.org/?probe=6d228ca955) | Oct 05, 2020 |
| Gigabyte      | B450M DS3H-CF               | [309b4ecbe6](https://linux-hardware.org/?probe=309b4ecbe6) | Oct 02, 2020 |
| Gigabyte      | G31M-ES2C                   | [41c9698c88](https://linux-hardware.org/?probe=41c9698c88) | Oct 01, 2020 |
| Intel         | 945GCT-M                    | [c0ad55286f](https://linux-hardware.org/?probe=c0ad55286f) | Sep 26, 2020 |
| Dell          | 0MM599                      | [bf8a1f8434](https://linux-hardware.org/?probe=bf8a1f8434) | Sep 22, 2020 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [b178b5269a](https://linux-hardware.org/?probe=b178b5269a) | Sep 18, 2020 |
| ASUSTek       | M4A87TD EVO                 | [4b2b8ed64f](https://linux-hardware.org/?probe=4b2b8ed64f) | Sep 06, 2020 |
| ASRock        | X570 Steel Legend           | [fcc32617ab](https://linux-hardware.org/?probe=fcc32617ab) | Sep 06, 2020 |
| Gigabyte      | AM1M-S2H                    | [8f57e5d722](https://linux-hardware.org/?probe=8f57e5d722) | Sep 05, 2020 |
| PCSMART       | 6.0                         | [e95fadbdfe](https://linux-hardware.org/?probe=e95fadbdfe) | Sep 05, 2020 |
| ASRock        | H110M-HDV R3.0              | [b641263269](https://linux-hardware.org/?probe=b641263269) | Sep 04, 2020 |
| ASUSTek       | M4A87TD/USB3                | [3c21577bc4](https://linux-hardware.org/?probe=3c21577bc4) | Sep 03, 2020 |
| ASUSTek       | PRIME A320M-K               | [131299dd43](https://linux-hardware.org/?probe=131299dd43) | Sep 02, 2020 |
| ASUSTek       | PRIME A320M-K               | [c7c173a4d6](https://linux-hardware.org/?probe=c7c173a4d6) | Aug 28, 2020 |
| ASUSTek       | PRIME H310M-E               | [07445986db](https://linux-hardware.org/?probe=07445986db) | Aug 24, 2020 |
| Dell          | 0D6H9T A01                  | [9c13b5e775](https://linux-hardware.org/?probe=9c13b5e775) | Aug 20, 2020 |
| Dell          | 0D6H9T A01                  | [40b95dab91](https://linux-hardware.org/?probe=40b95dab91) | Aug 20, 2020 |
| ECS           | H81H3-M4                    | [2a6af22359](https://linux-hardware.org/?probe=2a6af22359) | Aug 18, 2020 |
| Foxconn       | 2ABF                        | [24c499fe18](https://linux-hardware.org/?probe=24c499fe18) | Aug 17, 2020 |
| Foxconn       | 2ABF                        | [1fbfbf3d96](https://linux-hardware.org/?probe=1fbfbf3d96) | Aug 17, 2020 |
| ECS           | H81H3-M4                    | [6edc3d456f](https://linux-hardware.org/?probe=6edc3d456f) | Aug 16, 2020 |
| MSI           | A68HM-E33                   | [819dd19a0e](https://linux-hardware.org/?probe=819dd19a0e) | Aug 14, 2020 |
| ASUSTek       | H110-PLUS                   | [28a6907d78](https://linux-hardware.org/?probe=28a6907d78) | Aug 14, 2020 |
| ASUSTek       | PRIME H310M-E               | [a10db0a0f1](https://linux-hardware.org/?probe=a10db0a0f1) | Aug 13, 2020 |
| ASUSTek       | M4A87TD/USB3                | [76ee87fa06](https://linux-hardware.org/?probe=76ee87fa06) | Aug 07, 2020 |
| Gigabyte      | X399 AORUS Gaming 7         | [c27cdabb7b](https://linux-hardware.org/?probe=c27cdabb7b) | Aug 02, 2020 |
| Foxconn       | G41MXE/G41MXE-K             | [67b506f12f](https://linux-hardware.org/?probe=67b506f12f) | Jul 16, 2020 |
| Foxconn       | G41MXE/G41MXE-K             | [65d309fa0f](https://linux-hardware.org/?probe=65d309fa0f) | Jul 16, 2020 |
| Gigabyte      | X570 UD                     | [dffcf158e7](https://linux-hardware.org/?probe=dffcf158e7) | Jul 12, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [f24093f04f](https://linux-hardware.org/?probe=f24093f04f) | Jul 09, 2020 |
| HP            | ProLiant ML310e Gen8 v2     | [b97d60900c](https://linux-hardware.org/?probe=b97d60900c) | Jul 07, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [a57a22212c](https://linux-hardware.org/?probe=a57a22212c) | Jul 06, 2020 |
| ECS           | G31T-M7                     | [95cb3298ec](https://linux-hardware.org/?probe=95cb3298ec) | Jul 05, 2020 |
| ECS           | G31T-M7                     | [56b5cd6eac](https://linux-hardware.org/?probe=56b5cd6eac) | Jul 05, 2020 |
| Pegatron      | 2A73h                       | [58e16275bc](https://linux-hardware.org/?probe=58e16275bc) | Jul 04, 2020 |
| ECS           | H81H3-M4                    | [ed75f47aa0](https://linux-hardware.org/?probe=ed75f47aa0) | Jun 30, 2020 |
| Hardkernel    | ODROID-H2                   | [3cda40d161](https://linux-hardware.org/?probe=3cda40d161) | Jun 28, 2020 |
| ASRock        | N68C-S UCC                  | [19c8257ed1](https://linux-hardware.org/?probe=19c8257ed1) | Jun 26, 2020 |
| ASRock        | N68C-S UCC                  | [a56bd9dd64](https://linux-hardware.org/?probe=a56bd9dd64) | Jun 26, 2020 |
| ECS           | H81H3-M4                    | [9dfcf2f0cb](https://linux-hardware.org/?probe=9dfcf2f0cb) | Jun 23, 2020 |
| Gigabyte      | GA-78LMT-USB3               | [f90ccba28d](https://linux-hardware.org/?probe=f90ccba28d) | Jun 23, 2020 |
| Gigabyte      | GA-78LMT-USB3               | [c8a9bbbaa0](https://linux-hardware.org/?probe=c8a9bbbaa0) | Jun 20, 2020 |
| Biostar       | N68S3+                      | [3d289fd6d2](https://linux-hardware.org/?probe=3d289fd6d2) | Jun 15, 2020 |
| Dell          | 054KM3 A00                  | [3e9f988a30](https://linux-hardware.org/?probe=3e9f988a30) | Jun 11, 2020 |
| ASRock        | G41M-VS3                    | [8143bab4c5](https://linux-hardware.org/?probe=8143bab4c5) | May 30, 2020 |
| MSI           | A55M-P35                    | [1816e90106](https://linux-hardware.org/?probe=1816e90106) | May 22, 2020 |
| ASRock        | G41M-VS3                    | [a0a6bd1e26](https://linux-hardware.org/?probe=a0a6bd1e26) | May 22, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [dc1d621a65](https://linux-hardware.org/?probe=dc1d621a65) | May 15, 2020 |
| MSI           | H110M PRO-VH PLUS           | [c54d7ef6ee](https://linux-hardware.org/?probe=c54d7ef6ee) | May 10, 2020 |
| MSI           | H110M PRO-VH PLUS           | [cbf18515b3](https://linux-hardware.org/?probe=cbf18515b3) | May 10, 2020 |
| ASRock        | G965M-S                     | [9d4cff9871](https://linux-hardware.org/?probe=9d4cff9871) | May 05, 2020 |
| PCChips       | P17G ECS                    | [8220dc9d9a](https://linux-hardware.org/?probe=8220dc9d9a) | May 04, 2020 |
| ECS           | H81H3-M4                    | [c8dd8d2166](https://linux-hardware.org/?probe=c8dd8d2166) | May 02, 2020 |
| Gigabyte      | H170-Gaming 3 DDR3          | [b6540749a2](https://linux-hardware.org/?probe=b6540749a2) | May 01, 2020 |
| MSI           | 970A-G43 PLUS               | [50a3cd26c8](https://linux-hardware.org/?probe=50a3cd26c8) | Apr 25, 2020 |
| Gigabyte      | G31M-S2C                    | [2392a43f27](https://linux-hardware.org/?probe=2392a43f27) | Apr 14, 2020 |
| Gigabyte      | G31M-S2C                    | [50809e26ed](https://linux-hardware.org/?probe=50809e26ed) | Apr 14, 2020 |
| MSI           | MS-7309                     | [598ba6983d](https://linux-hardware.org/?probe=598ba6983d) | Apr 14, 2020 |
| Unknown       | Unknown                     | [6e2105feb5](https://linux-hardware.org/?probe=6e2105feb5) | Apr 03, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [b3c0d80908](https://linux-hardware.org/?probe=b3c0d80908) | Mar 26, 2020 |
| HP            | 3048h                       | [6b07a41174](https://linux-hardware.org/?probe=6b07a41174) | Mar 22, 2020 |
| ASRock        | H61M-VG4                    | [9a17b3a770](https://linux-hardware.org/?probe=9a17b3a770) | Mar 21, 2020 |
| MSI           | K9N6PGM2-V2                 | [68013dac14](https://linux-hardware.org/?probe=68013dac14) | Mar 16, 2020 |
| MSI           | K9N6PGM2-V2                 | [df4df13e54](https://linux-hardware.org/?probe=df4df13e54) | Mar 16, 2020 |
| MSI           | K9N6PGM2-V2                 | [12b38c9ebd](https://linux-hardware.org/?probe=12b38c9ebd) | Mar 16, 2020 |
| Intel         | DH61WW AAG23116-302         | [239a155579](https://linux-hardware.org/?probe=239a155579) | Feb 22, 2020 |
| ASUSTek       | PRIME H310-PLUS             | [c59fbe99a2](https://linux-hardware.org/?probe=c59fbe99a2) | Feb 02, 2020 |
| ASUSTek       | PRIME X570-PRO              | [8f38f0a1e3](https://linux-hardware.org/?probe=8f38f0a1e3) | Jan 20, 2020 |
| Dell          | 0P301D A00                  | [298fac1e53](https://linux-hardware.org/?probe=298fac1e53) | Jan 03, 2020 |
| ASRock        | G41M-VS3                    | [c4c975b9f9](https://linux-hardware.org/?probe=c4c975b9f9) | Dec 29, 2019 |
| Unknown       | GSUO H61V10C                | [96d964a1d9](https://linux-hardware.org/?probe=96d964a1d9) | Dec 23, 2019 |
| Pegatron      | 2AAE                        | [04a6d42a9c](https://linux-hardware.org/?probe=04a6d42a9c) | Dec 16, 2019 |
| Pegatron      | 2AAE                        | [e142be5f58](https://linux-hardware.org/?probe=e142be5f58) | Dec 16, 2019 |
| ASRock        | H55M                        | [a199be0d97](https://linux-hardware.org/?probe=a199be0d97) | Nov 12, 2019 |
| ASRock        | H55M                        | [7202462c60](https://linux-hardware.org/?probe=7202462c60) | Nov 12, 2019 |
| MSI           | MS-7309                     | [2e6203af14](https://linux-hardware.org/?probe=2e6203af14) | Oct 09, 2019 |
| ASUSTek       | H110M-R                     | [d98faab3bc](https://linux-hardware.org/?probe=d98faab3bc) | Oct 09, 2019 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [3181aa4496](https://linux-hardware.org/?probe=3181aa4496) | Sep 02, 2019 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [f063afeba7](https://linux-hardware.org/?probe=f063afeba7) | Aug 28, 2019 |
| HP            | ProLiant ML115 G1           | [8f0d70a883](https://linux-hardware.org/?probe=8f0d70a883) | Jul 29, 2019 |
| Dell          | OptiPlex GX260              | [6c061a7a15](https://linux-hardware.org/?probe=6c061a7a15) | Jul 23, 2019 |
| ASUSTek       | H81M-K                      | [b124f401f6](https://linux-hardware.org/?probe=b124f401f6) | Jul 17, 2019 |
| Intel         | DH55HC AAE70933-501         | [3462cd0ccd](https://linux-hardware.org/?probe=3462cd0ccd) | Jul 07, 2019 |
| MSI           | MS-7191                     | [d753273d7b](https://linux-hardware.org/?probe=d753273d7b) | Jul 03, 2019 |
| Dell          | 0RY206                      | [aed7ab6e58](https://linux-hardware.org/?probe=aed7ab6e58) | Jun 28, 2019 |
| Gigabyte      | H81M-H                      | [bebf195e43](https://linux-hardware.org/?probe=bebf195e43) | Jun 18, 2019 |
| ASRock        | K8Upgrade-VM800             | [83cccbaf1a](https://linux-hardware.org/?probe=83cccbaf1a) | Jun 03, 2019 |
| ASRock        | G965M-S                     | [30b8a56200](https://linux-hardware.org/?probe=30b8a56200) | May 30, 2019 |
| Dell          | 0TT708 A01                  | [b732db0128](https://linux-hardware.org/?probe=b732db0128) | May 24, 2019 |
| Dell          | 0TT708 A01                  | [fbe3c00bb0](https://linux-hardware.org/?probe=fbe3c00bb0) | May 24, 2019 |
| Unknown       | 775i65G                     | [0b6fd94458](https://linux-hardware.org/?probe=0b6fd94458) | May 19, 2019 |
| Unknown       | 775i65G                     | [2b8a659310](https://linux-hardware.org/?probe=2b8a659310) | May 18, 2019 |
| Gigabyte      | GA-78LMT-USB3               | [29cf71291b](https://linux-hardware.org/?probe=29cf71291b) | Apr 21, 2019 |
| Biostar       | A55MLV                      | [38fd682351](https://linux-hardware.org/?probe=38fd682351) | Apr 19, 2019 |
| HP            | 0A60h                       | [c59eb70baf](https://linux-hardware.org/?probe=c59eb70baf) | Apr 11, 2019 |
| HP            | 0A60h                       | [bd74dccea9](https://linux-hardware.org/?probe=bd74dccea9) | Apr 10, 2019 |
| ASUSTek       | H81M-K                      | [c5178f5550](https://linux-hardware.org/?probe=c5178f5550) | Apr 04, 2019 |
| ASUSTek       | H81M-K                      | [ef3d04377e](https://linux-hardware.org/?probe=ef3d04377e) | Apr 01, 2019 |
| ASUSTek       | H81M-K                      | [be751979a7](https://linux-hardware.org/?probe=be751979a7) | Apr 01, 2019 |
| ASUSTek       | H81M-K                      | [b9c1d97ec1](https://linux-hardware.org/?probe=b9c1d97ec1) | Apr 01, 2019 |
| Biostar       | A55MLV                      | [138e3baa2d](https://linux-hardware.org/?probe=138e3baa2d) | Mar 29, 2019 |
| ASUSTek       | H81M-K                      | [d3f5c5ac28](https://linux-hardware.org/?probe=d3f5c5ac28) | Mar 29, 2019 |
| Intel         | DH61CR AAG14064-207         | [2c44dea441](https://linux-hardware.org/?probe=2c44dea441) | Mar 17, 2019 |
| Gigabyte      | GA-78LMT-USB3               | [8d9fa49be1](https://linux-hardware.org/?probe=8d9fa49be1) | Feb 09, 2019 |
| Gigabyte      | GA-78LMT-USB3               | [5dcbf55671](https://linux-hardware.org/?probe=5dcbf55671) | Feb 09, 2019 |
| ASRock        | Wolfdale1333-D667           | [f67c3262d4](https://linux-hardware.org/?probe=f67c3262d4) | Dec 10, 2018 |
| ASRock        | Wolfdale1333-D667           | [06bcad286b](https://linux-hardware.org/?probe=06bcad286b) | Nov 18, 2018 |
| Pegatron      | 2A73h                       | [9ab888ea4f](https://linux-hardware.org/?probe=9ab888ea4f) | Jun 19, 2018 |
| HP            | 2ADE                        | [af28bb9a2f](https://linux-hardware.org/?probe=af28bb9a2f) | Dec 01, 2017 |
| HP            | 2ADE                        | [a2ab5f4392](https://linux-hardware.org/?probe=a2ab5f4392) | Dec 01, 2017 |
| HP            | 0A54h                       | [1f795e5896](https://linux-hardware.org/?probe=1f795e5896) | Jun 29, 2017 |
| HP            | 0A54h                       | [ef67a7d651](https://linux-hardware.org/?probe=ef67a7d651) | Feb 05, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Colombia/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 34       | 6.54%   |
| Ubuntu 18.04       | 31       | 5.96%   |
| Ubuntu 22.04       | 26       | 5%      |
| Arch Rolling       | 16       | 3.08%   |
| OpenMandriva 4.3   | 14       | 2.69%   |
| Zorin 17           | 13       | 2.5%    |
| OpenMandriva 25.90 | 11       | 2.12%   |
| OpenMandriva 23.08 | 11       | 2.12%   |
| Fedora 38          | 11       | 2.12%   |
| Ubuntu 24.04       | 10       | 1.92%   |
| Linux Mint 20.3    | 10       | 1.92%   |
| Fedora 40          | 10       | 1.92%   |
| Debian 12          | 10       | 1.92%   |
| Fedora 42          | 9        | 1.73%   |
| ArcoLinux Rolling  | 9        | 1.73%   |
| Linux Mint 20.2    | 8        | 1.54%   |
| OpenMandriva 4.2   | 7        | 1.35%   |
| KDE neon 20.04     | 7        | 1.35%   |
| Fedora 41          | 7        | 1.35%   |
| Zorin 18           | 6        | 1.15%   |
| Zorin 15           | 6        | 1.15%   |
| OpenMandriva 24.12 | 6        | 1.15%   |
| Manjaro            | 6        | 1.15%   |
| Linux Mint 22.1    | 6        | 1.15%   |
| Linux Mint 21.2    | 6        | 1.15%   |
| Fedora 37          | 6        | 1.15%   |
| Linux Mint 19.3    | 5        | 0.96%   |
| KDE neon 22.04     | 5        | 0.96%   |
| Fedora 39          | 5        | 0.96%   |
| Fedora 35          | 5        | 0.96%   |
| Debian 11          | 5        | 0.96%   |
| Zorin 16           | 4        | 0.77%   |
| Xubuntu 22.04      | 4        | 0.77%   |
| Xubuntu 20.04      | 4        | 0.77%   |
| Pop!_OS 22.04      | 4        | 0.77%   |
| OpenMandriva 23.03 | 4        | 0.77%   |
| Fedora 36          | 4        | 0.77%   |
| Bazzite 42         | 4        | 0.77%   |
| Zorin 12           | 3        | 0.58%   |
| Ubuntu Unity 16.04 | 3        | 0.58%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 107      | 21.93%  |
| OpenMandriva  | 66       | 13.52%  |
| Fedora        | 59       | 12.09%  |
| Linux Mint    | 45       | 9.22%   |
| Zorin         | 32       | 6.56%   |
| Debian        | 20       | 4.1%    |
| Arch          | 19       | 3.89%   |
| KDE neon      | 12       | 2.46%   |
| ROSA          | 11       | 2.25%   |
| Kubuntu       | 11       | 2.25%   |
| Xubuntu       | 10       | 2.05%   |
| Manjaro       | 10       | 2.05%   |
| Nobara        | 9        | 1.84%   |
| ArcoLinux     | 9        | 1.84%   |
| Pop!_OS       | 8        | 1.64%   |
| Bazzite       | 8        | 1.64%   |
| Elementary    | 5        | 1.02%   |
| Ubuntu Unity  | 4        | 0.82%   |
| openSUSE      | 4        | 0.82%   |
| Lubuntu       | 3        | 0.61%   |
| Endless       | 3        | 0.61%   |
| Deepin        | 3        | 0.61%   |
| CachyOS       | 3        | 0.61%   |
| Xero          | 2        | 0.41%   |
| Ubuntu Budgie | 2        | 0.41%   |
| Kali          | 2        | 0.41%   |
| EndeavourOS   | 2        | 0.41%   |
| BlackPanther  | 2        | 0.41%   |
| Vanilla       | 1        | 0.2%    |
| UbuntuDDE     | 1        | 0.2%    |
| SteamOS       | 1        | 0.2%    |
| Rocky Linux   | 1        | 0.2%    |
| Reborn OS     | 1        | 0.2%    |
| Peppermint    | 1        | 0.2%    |
| Parrot        | 1        | 0.2%    |
| NixOS         | 1        | 0.2%    |
| MX            | 1        | 0.2%    |
| Mageia        | 1        | 0.2%    |
| LMDE          | 1        | 0.2%    |
| LinuxFX       | 1        | 0.2%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Desktops | Percent |
|------------------------------------|----------|---------|
| 6.14.2-desktop-3omv2590            | 14       | 2.46%   |
| 5.16.7-desktop-1omv4003            | 13       | 2.28%   |
| 6.4.11-desktop-1omv2390            | 10       | 1.76%   |
| 5.4.0-42-generic                   | 7        | 1.23%   |
| 5.10.14-desktop-1omv4002           | 7        | 1.23%   |
| 6.12.1-desktop-1omv2490            | 6        | 1.05%   |
| 5.19.0-35-generic                  | 5        | 0.88%   |
| 5.15.0-56-generic                  | 5        | 0.88%   |
| 6.8.0-60-generic                   | 4        | 0.7%    |
| 6.2.6-desktop-1omv2390             | 4        | 0.7%    |
| 5.4.0-72-generic                   | 4        | 0.7%    |
| 5.4.0-58-generic                   | 4        | 0.7%    |
| 5.0.0-32-generic                   | 4        | 0.7%    |
| 6.8.11-300.fc40.x86_64             | 3        | 0.53%   |
| 6.8.0-51-generic                   | 3        | 0.53%   |
| 6.8.0-45-generic                   | 3        | 0.53%   |
| 6.8.0-41-generic                   | 3        | 0.53%   |
| 6.8.0-40-generic                   | 3        | 0.53%   |
| 6.6.9-200.fc39.x86_64              | 3        | 0.53%   |
| 6.5.0-35-generic                   | 3        | 0.53%   |
| 6.5.0-14-generic                   | 3        | 0.53%   |
| 6.2.0-35-generic                   | 3        | 0.53%   |
| 6.14.4-104.bazzite.fc42.x86_64     | 3        | 0.53%   |
| 6.14.0-33-generic                  | 3        | 0.53%   |
| 6.14.0-27-generic                  | 3        | 0.53%   |
| 6.12.47-generic-5rosa13-x86_64     | 3        | 0.53%   |
| 6.1.1-desktop-1omv2290             | 3        | 0.53%   |
| 5.4.0-48-generic                   | 3        | 0.53%   |
| 5.4.0-45-generic                   | 3        | 0.53%   |
| 5.4.0-122-generic                  | 3        | 0.53%   |
| 5.19.0-41-generic                  | 3        | 0.53%   |
| 5.15.0-67-generic                  | 3        | 0.53%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 3        | 0.53%   |
| 4.18.0-16-generic                  | 3        | 0.53%   |
| 4.15.0-54-generic                  | 3        | 0.53%   |
| 6.8.7-201.fsync.fc39.x86_64        | 2        | 0.35%   |
| 6.8.0-57-generic                   | 2        | 0.35%   |
| 6.8.0-49-generic                   | 2        | 0.35%   |
| 6.8.0-48-generic                   | 2        | 0.35%   |
| 6.8.0-35-generic                   | 2        | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 65       | 11.97%  |
| 5.15.0  | 38       | 7%      |
| 6.8.0   | 31       | 5.71%   |
| 4.15.0  | 18       | 3.31%   |
| 6.14.2  | 16       | 2.95%   |
| 6.14.0  | 15       | 2.76%   |
| 6.5.0   | 14       | 2.58%   |
| 5.16.7  | 13       | 2.39%   |
| 5.19.0  | 12       | 2.21%   |
| 5.0.0   | 11       | 2.03%   |
| 6.4.11  | 10       | 1.84%   |
| 5.3.0   | 10       | 1.84%   |
| 5.13.0  | 10       | 1.84%   |
| 6.2.0   | 9        | 1.66%   |
| 6.1.0   | 9        | 1.66%   |
| 5.8.0   | 8        | 1.47%   |
| 4.18.0  | 8        | 1.47%   |
| 5.10.14 | 7        | 1.29%   |
| 6.12.1  | 6        | 1.1%    |
| 5.11.0  | 6        | 1.1%    |
| 6.14.4  | 5        | 0.92%   |
| 6.8.7   | 4        | 0.74%   |
| 6.2.6   | 4        | 0.74%   |
| 6.1.1   | 4        | 0.74%   |
| 5.10.0  | 4        | 0.74%   |
| 6.8.11  | 3        | 0.55%   |
| 6.6.9   | 3        | 0.55%   |
| 6.6.2   | 3        | 0.55%   |
| 6.12.9  | 3        | 0.55%   |
| 6.12.47 | 3        | 0.55%   |
| 5.8.5   | 3        | 0.55%   |
| 5.8.18  | 3        | 0.55%   |
| 5.12.4  | 3        | 0.55%   |
| 5.10.74 | 3        | 0.55%   |
| 6.9.12  | 2        | 0.37%   |
| 6.6.7   | 2        | 0.37%   |
| 6.5.7   | 2        | 0.37%   |
| 6.4.13  | 2        | 0.37%   |
| 6.4.10  | 2        | 0.37%   |
| 6.3.8   | 2        | 0.37%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 68       | 12.81%  |
| 5.15    | 44       | 8.29%   |
| 6.8     | 40       | 7.53%   |
| 6.14    | 39       | 7.34%   |
| 6.12    | 24       | 4.52%   |
| 6.1     | 24       | 4.52%   |
| 5.10    | 20       | 3.77%   |
| 6.5     | 18       | 3.39%   |
| 4.15    | 18       | 3.39%   |
| 6.4     | 17       | 3.2%    |
| 5.16    | 17       | 3.2%    |
| 6.2     | 16       | 3.01%   |
| 5.8     | 15       | 2.82%   |
| 6.6     | 12       | 2.26%   |
| 5.19    | 12       | 2.26%   |
| 5.13    | 12       | 2.26%   |
| 5.3     | 11       | 2.07%   |
| 5.0     | 11       | 2.07%   |
| 6.17    | 10       | 1.88%   |
| 4.18    | 10       | 1.88%   |
| 6.3     | 7        | 1.32%   |
| 6.15    | 7        | 1.32%   |
| 6.11    | 7        | 1.32%   |
| 6.10    | 7        | 1.32%   |
| 5.14    | 7        | 1.32%   |
| 5.11    | 7        | 1.32%   |
| 6.9     | 5        | 0.94%   |
| 6.7     | 5        | 0.94%   |
| 6.16    | 5        | 0.94%   |
| 6.0     | 5        | 0.94%   |
| 5.12    | 5        | 0.94%   |
| 6.13    | 4        | 0.75%   |
| 5.17    | 4        | 0.75%   |
| 4.9     | 4        | 0.75%   |
| 5.9     | 2        | 0.38%   |
| 5.6     | 2        | 0.38%   |
| 5.18    | 2        | 0.38%   |
| 4.19    | 2        | 0.38%   |
| 6.18    | 1        | 0.19%   |
| 5.7     | 1        | 0.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 460      | 98.5%   |
| i686   | 7        | 1.5%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 188      | 38.06%  |
| KDE5            | 84       | 17%     |
| KDE6            | 58       | 11.74%  |
| X-Cinnamon      | 33       | 6.68%   |
| Unknown         | 33       | 6.68%   |
| XFCE            | 32       | 6.48%   |
| KDE             | 11       | 2.23%   |
| MATE            | 8        | 1.62%   |
| Pantheon        | 5        | 1.01%   |
| KDE4            | 5        | 1.01%   |
| Unity           | 4        | 0.81%   |
| LXQt            | 4        | 0.81%   |
| i3              | 4        | 0.81%   |
| Deepin          | 4        | 0.81%   |
| Cinnamon        | 4        | 0.81%   |
| LXDE            | 3        | 0.61%   |
| GNOME Classic   | 2        | 0.4%    |
| Budgie          | 2        | 0.4%    |
| ubuntu=GNOME    | 1        | 0.2%    |
| sway            | 1        | 0.2%    |
| qtile           | 1        | 0.2%    |
| Hyprland        | 1        | 0.2%    |
| GNOME Flashback | 1        | 0.2%    |
| Enlightenment   | 1        | 0.2%    |
| Endless:GNOME   | 1        | 0.2%    |
| DDE             | 1        | 0.2%    |
| COSMIC          | 1        | 0.2%    |
| awesome         | 1        | 0.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 308      | 63.24%  |
| Wayland | 154      | 31.62%  |
| Unknown | 17       | 3.49%   |
| Tty     | 8        | 1.64%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 234      | 47.66%  |
| SDDM           | 108      | 22%     |
| GDM3           | 50       | 10.18%  |
| GDM            | 45       | 9.16%   |
| LightDM        | 42       | 8.55%   |
| TDM            | 5        | 1.02%   |
| KDM            | 4        | 0.81%   |
| SLiM           | 1        | 0.2%    |
| LXDM           | 1        | 0.2%    |
| COSMIC-GREETER | 1        | 0.2%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| es_CO   | 244      | 50.41%  |
| en_US   | 134      | 27.69%  |
| es_ES   | 40       | 8.26%   |
| Unknown | 36       | 7.44%   |
| es_MX   | 11       | 2.27%   |
| C       | 7        | 1.45%   |
| pt_BR   | 3        | 0.62%   |
| es_AR   | 3        | 0.62%   |
| en_GB   | 2        | 0.41%   |
| es_VE   | 1        | 0.21%   |
| es_PE   | 1        | 0.21%   |
| es_DO   | 1        | 0.21%   |
| C.UTF8  | 1        | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 285      | 59.62%  |
| EFI  | 193      | 40.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 298      | 61.57%  |
| Btrfs   | 93       | 19.21%  |
| Overlay | 52       | 10.74%  |
| Tmpfs   | 25       | 5.17%   |
| Xfs     | 9        | 1.86%   |
| Unknown | 5        | 1.03%   |
| Zfs     | 1        | 0.21%   |
| Ext2    | 1        | 0.21%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 227      | 47.39%  |
| GPT     | 182      | 38%     |
| MBR     | 70       | 14.61%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 398      | 81.89%  |
| Yes       | 88       | 18.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 297      | 62%     |
| Yes       | 182      | 38%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 99       | 21.2%   |
| Gigabyte Technology                  | 86       | 18.42%  |
| MSI                                  | 56       | 11.99%  |
| ASRock                               | 48       | 10.28%  |
| Hewlett-Packard                      | 43       | 9.21%   |
| Dell                                 | 33       | 7.07%   |
| Intel                                | 26       | 5.57%   |
| Lenovo                               | 18       | 3.85%   |
| Biostar                              | 10       | 2.14%   |
| ECS                                  | 8        | 1.71%   |
| Pegatron                             | 6        | 1.28%   |
| Unknown                              | 6        | 1.28%   |
| Foxconn                              | 5        | 1.07%   |
| PCSMART                              | 4        | 0.86%   |
| Acer                                 | 3        | 0.64%   |
| Huanan                               | 2        | 0.43%   |
| SYWZ                                 | 1        | 0.21%   |
| Supermicro                           | 1        | 0.21%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.21%   |
| Quanta                               | 1        | 0.21%   |
| PCChips                              | 1        | 0.21%   |
| MACHINIST                            | 1        | 0.21%   |
| JGINYUE                              | 1        | 0.21%   |
| Intel X79                            | 1        | 0.21%   |
| Hardkernel                           | 1        | 0.21%   |
| eMachines                            | 1        | 0.21%   |
| Compumax Computer                    | 1        | 0.21%   |
| BESSTAR Tech                         | 1        | 0.21%   |
| AZW                                  | 1        | 0.21%   |
| Apple                                | 1        | 0.21%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Desktops | Percent |
|------------------------------------|----------|---------|
| Gigabyte B450M DS3H                | 9        | 1.93%   |
| Unknown                            | 8        | 1.71%   |
| MSI MS-7817                        | 7        | 1.5%    |
| Gigabyte H81M-H                    | 7        | 1.5%    |
| ASUS PRIME A320M-K                 | 6        | 1.28%   |
| ASUS All Series                    | 5        | 1.07%   |
| MSI MS-7309                        | 4        | 0.86%   |
| Intel H61                          | 4        | 0.86%   |
| Gigabyte H61M-HD2                  | 4        | 0.86%   |
| Gigabyte A520M DS3H                | 4        | 0.86%   |
| ASUS TUF Gaming X570-PLUS          | 4        | 0.86%   |
| ASUS ROG STRIX B550-F GAMING       | 4        | 0.86%   |
| ASUS PRIME B450M-A II              | 4        | 0.86%   |
| ASRock Wolfdale1333-D667           | 4        | 0.86%   |
| ASRock G41M-VS3                    | 4        | 0.86%   |
| MSI MS-7597                        | 3        | 0.64%   |
| HP ProDesk 400 G1 SFF              | 3        | 0.64%   |
| HP Compaq 8200 Elite SFF PC        | 3        | 0.64%   |
| Gigabyte H61M-S1                   | 3        | 0.64%   |
| Gigabyte GA-78LMT-USB3             | 3        | 0.64%   |
| Gigabyte G31M-ES2C                 | 3        | 0.64%   |
| Gigabyte A320M-S2H                 | 3        | 0.64%   |
| ECS G31T-M7                        | 3        | 0.64%   |
| ASUS M5A78L-M/USB3                 | 3        | 0.64%   |
| ASRock G965M-S                     | 3        | 0.64%   |
| MSI MS-7E27                        | 2        | 0.43%   |
| MSI MS-7D22                        | 2        | 0.43%   |
| MSI MS-7C96                        | 2        | 0.43%   |
| MSI MS-7C37                        | 2        | 0.43%   |
| MSI MS-7A15                        | 2        | 0.43%   |
| MSI MS-7641                        | 2        | 0.43%   |
| Intel DH61CR AAG14064-207          | 2        | 0.43%   |
| HP Compaq Pro 6300 SFF             | 2        | 0.43%   |
| HP Compaq Pro 4300 SFF PC          | 2        | 0.43%   |
| HP Compaq dc7700 Small Form Factor | 2        | 0.43%   |
| HP Compaq 6200 Pro MT PC           | 2        | 0.43%   |
| Gigabyte X399 AORUS PRO            | 2        | 0.43%   |
| Gigabyte B550 AORUS PRO AC         | 2        | 0.43%   |
| ECS H81H3-M4                       | 2        | 0.43%   |
| ECS H61H2-MV                       | 2        | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| ASUS PRIME               | 38       | 8.14%   |
| HP Compaq                | 21       | 4.5%    |
| Dell OptiPlex            | 19       | 4.07%   |
| ASUS TUF                 | 15       | 3.21%   |
| Lenovo ThinkCentre       | 12       | 2.57%   |
| ASUS ROG                 | 12       | 2.57%   |
| Gigabyte B450M           | 11       | 2.36%   |
| Unknown                  | 8        | 1.71%   |
| MSI MS-7817              | 7        | 1.5%    |
| HP ProDesk               | 7        | 1.5%    |
| Gigabyte H81M-H          | 7        | 1.5%    |
| Gigabyte B550            | 5        | 1.07%   |
| Dell Vostro              | 5        | 1.07%   |
| ASUS All                 | 5        | 1.07%   |
| MSI MS-7309              | 4        | 0.86%   |
| Intel H61                | 4        | 0.86%   |
| HP ProLiant              | 4        | 0.86%   |
| Gigabyte H61M-HD2        | 4        | 0.86%   |
| Gigabyte A520M           | 4        | 0.86%   |
| ASRock Wolfdale1333-D667 | 4        | 0.86%   |
| ASRock G41M-VS3          | 4        | 0.86%   |
| MSI MS-7597              | 3        | 0.64%   |
| Intel DG41RQ             | 3        | 0.64%   |
| Gigabyte X570            | 3        | 0.64%   |
| Gigabyte X399            | 3        | 0.64%   |
| Gigabyte H61M-S1         | 3        | 0.64%   |
| Gigabyte GA-78LMT-USB3   | 3        | 0.64%   |
| Gigabyte G31M-ES2C       | 3        | 0.64%   |
| Gigabyte B550M           | 3        | 0.64%   |
| Gigabyte A320M-S2H       | 3        | 0.64%   |
| ECS G31T-M7              | 3        | 0.64%   |
| ASUS M5A78L-M            | 3        | 0.64%   |
| ASRock G965M-S           | 3        | 0.64%   |
| MSI MS-7E27              | 2        | 0.43%   |
| MSI MS-7D22              | 2        | 0.43%   |
| MSI MS-7C96              | 2        | 0.43%   |
| MSI MS-7C37              | 2        | 0.43%   |
| MSI MS-7A15              | 2        | 0.43%   |
| MSI MS-7641              | 2        | 0.43%   |
| Lenovo ThinkStation      | 2        | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 48       | 10.28%  |
| 2020 | 43       | 9.21%   |
| 2018 | 43       | 9.21%   |
| 2013 | 40       | 8.57%   |
| 2010 | 40       | 8.57%   |
| 2011 | 34       | 7.28%   |
| 2019 | 26       | 5.57%   |
| 2009 | 26       | 5.57%   |
| 2021 | 25       | 5.35%   |
| 2017 | 23       | 4.93%   |
| 2008 | 19       | 4.07%   |
| 2015 | 17       | 3.64%   |
| 2007 | 16       | 3.43%   |
| 2023 | 14       | 3%      |
| 2016 | 13       | 2.78%   |
| 2022 | 11       | 2.36%   |
| 2014 | 11       | 2.36%   |
| 2006 | 10       | 2.14%   |
| 2024 | 3        | 0.64%   |
| 2025 | 2        | 0.43%   |
| 2005 | 2        | 0.43%   |
| 2003 | 1        | 0.21%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 467      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 456      | 97.02%  |
| Enabled  | 14       | 2.98%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 467      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 98       | 20.59%  |
| 16.01-24.0  | 90       | 18.91%  |
| 4.01-8.0    | 85       | 17.86%  |
| 3.01-4.0    | 76       | 15.97%  |
| 32.01-64.0  | 63       | 13.24%  |
| 1.01-2.0    | 25       | 5.25%   |
| 64.01-256.0 | 20       | 4.2%    |
| 24.01-32.0  | 11       | 2.31%   |
| 2.01-3.0    | 6        | 1.26%   |
| 0.51-1.0    | 2        | 0.42%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 157      | 30.02%  |
| 2.01-3.0   | 123      | 23.52%  |
| 4.01-8.0   | 95       | 18.16%  |
| 3.01-4.0   | 84       | 16.06%  |
| 0.51-1.0   | 31       | 5.93%   |
| 8.01-16.0  | 26       | 4.97%   |
| 16.01-24.0 | 4        | 0.76%   |
| 0.01-0.5   | 3        | 0.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 222      | 45.4%   |
| 2      | 138      | 28.22%  |
| 3      | 72       | 14.72%  |
| 4      | 23       | 4.7%    |
| 5      | 18       | 3.68%   |
| 6      | 8        | 1.64%   |
| 8      | 3        | 0.61%   |
| 7      | 2        | 0.41%   |
| 11     | 1        | 0.2%    |
| 9      | 1        | 0.2%    |
| 0      | 1        | 0.2%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 309      | 65.47%  |
| Yes       | 163      | 34.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 464      | 99.36%  |
| No        | 3        | 0.64%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 269      | 56.75%  |
| Yes       | 205      | 43.25%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 344      | 72.88%  |
| Yes       | 128      | 27.12%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Desktops | Percent |
|----------|----------|---------|
| Colombia | 467      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Bogotá          | 184      | 38.1%   |
| Medellín        | 80       | 16.56%  |
| Santiago de Cali | 40       | 8.28%   |
| Barranquilla     | 21       | 4.35%   |
| Bucaramanga      | 18       | 3.73%   |
| Pereira          | 9        | 1.86%   |
| Ibague           | 9        | 1.86%   |
| Pasto            | 8        | 1.66%   |
| Armenia          | 7        | 1.45%   |
| Valledupar       | 6        | 1.24%   |
| Santa Marta      | 6        | 1.24%   |
| Montería        | 6        | 1.24%   |
| Cúcuta          | 6        | 1.24%   |
| Villavicencio    | 5        | 1.04%   |
| Tunja            | 5        | 1.04%   |
| Neiva            | 5        | 1.04%   |
| Chia             | 5        | 1.04%   |
| Duitama          | 4        | 0.83%   |
| Cartagena        | 4        | 0.83%   |
| Palmira          | 3        | 0.62%   |
| Manizales        | 3        | 0.62%   |
| Buenaventura     | 3        | 0.62%   |
| Tuluá           | 2        | 0.41%   |
| Soledad          | 2        | 0.41%   |
| Piedecuesta      | 2        | 0.41%   |
| Calarcá         | 2        | 0.41%   |
| Bello            | 2        | 0.41%   |
| Zipaquirá       | 1        | 0.21%   |
| Zipacon          | 1        | 0.21%   |
| Yotoco           | 1        | 0.21%   |
| Villagarzon      | 1        | 0.21%   |
| Turbaco          | 1        | 0.21%   |
| Trujillo         | 1        | 0.21%   |
| Tocancipa        | 1        | 0.21%   |
| Soacha           | 1        | 0.21%   |
| Sincelejo        | 1        | 0.21%   |
| Rionegro         | 1        | 0.21%   |
| Puerto Carreño  | 1        | 0.21%   |
| Popayán         | 1        | 0.21%   |
| Policarpa        | 1        | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 140      | 203    | 16.11%  |
| Seagate                     | 119      | 178    | 13.69%  |
| Toshiba                     | 108      | 154    | 12.43%  |
| Hitachi                     | 70       | 88     | 8.06%   |
| Kingston                    | 64       | 120    | 7.36%   |
| Samsung Electronics         | 61       | 100    | 7.02%   |
| A-DATA Technology           | 40       | 48     | 4.6%    |
| Crucial                     | 32       | 40     | 3.68%   |
| SanDisk                     | 22       | 38     | 2.53%   |
| Maxtor                      | 22       | 24     | 2.53%   |
| Patriot                     | 12       | 13     | 1.38%   |
| PNY                         | 11       | 15     | 1.27%   |
| ADATA Technology            | 11       | 12     | 1.27%   |
| Micron/Crucial Technology   | 10       | 15     | 1.15%   |
| HGST                        | 10       | 12     | 1.15%   |
| Realtek Semiconductor       | 9        | 9      | 1.04%   |
| Team                        | 7        | 9      | 0.81%   |
| Silicon Motion              | 7        | 8      | 0.81%   |
| Lexar                       | 7        | 7      | 0.81%   |
| Gigabyte Technology         | 7        | 8      | 0.81%   |
| Unknown                     | 6        | 10     | 0.69%   |
| Phison Electronics          | 5        | 5      | 0.58%   |
| Phison                      | 5        | 9      | 0.58%   |
| Hewlett-Packard             | 5        | 6      | 0.58%   |
| China                       | 5        | 6      | 0.58%   |
| XrayDisk                    | 4        | 4      | 0.46%   |
| XPG                         | 4        | 5      | 0.46%   |
| SPCC                        | 4        | 4      | 0.46%   |
| MAXIO Technology (Hangzhou) | 4        | 5      | 0.46%   |
| KingSpec                    | 4        | 4      | 0.46%   |
| JMicron Technology          | 4        | 4      | 0.46%   |
| SK hynix                    | 3        | 5      | 0.35%   |
| Intel                       | 3        | 3      | 0.35%   |
| Corsair                     | 3        | 6      | 0.35%   |
| Unknown                     | 3        | 4      | 0.35%   |
| Transcend                   | 2        | 3      | 0.23%   |
| Micron Technology           | 2        | 2      | 0.23%   |
| LITEON                      | 2        | 3      | 0.23%   |
| Fujitsu                     | 2        | 2      | 0.23%   |
| Fanxiang                    | 2        | 2      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB                                | 42       | 4.44%   |
| Kingston SA400S37240G 240GB SSD                       | 21       | 2.22%   |
| Toshiba HDWD110 1TB                                   | 14       | 1.48%   |
| Toshiba DT01ACA050 500GB                              | 14       | 1.48%   |
| Toshiba DT01ACA200 2TB                                | 13       | 1.37%   |
| Seagate ST1000DM010-2EP102 1TB                        | 11       | 1.16%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 10       | 1.06%   |
| Kingston SA400S37120G 120GB SSD                       | 10       | 1.06%   |
| Crucial CT240BX500SSD1 240GB                          | 9        | 0.95%   |
| Seagate ST3500413AS 500GB                             | 8        | 0.84%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 8        | 0.84%   |
| Kingston SV300S37A120G 120GB SSD                      | 8        | 0.84%   |
| A-DATA SU630 240GB SSD                                | 8        | 0.84%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 7        | 0.74%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 7        | 0.74%   |
| Micron/Crucial P2 NVMe PCIe SSD 2TB                   | 7        | 0.74%   |
| Hitachi HDS721050CLA362 500GB                         | 7        | 0.74%   |
| A-DATA SU650 120GB SSD                                | 7        | 0.74%   |
| Seagate ST500DM002-1BD142 500GB                       | 6        | 0.63%   |
| Seagate ST1000LM035-1RK172 1TB                        | 6        | 0.63%   |
| Lexar 128GB SSD                                       | 6        | 0.63%   |
| Kingston SA400S37960G 960GB SSD                       | 6        | 0.63%   |
| Kingston SA400S37480G 480GB SSD                       | 6        | 0.63%   |
| Hitachi HDS721616PLA380 160GB                         | 6        | 0.63%   |
| Crucial CT1000BX500SSD1 1TB                           | 6        | 0.63%   |
| Seagate ST500LT012-1DG142 500GB                       | 5        | 0.53%   |
| Seagate ST2000DM008-2FR102 2TB                        | 5        | 0.53%   |
| Seagate ST1000DM003-1SB102 1TB                        | 5        | 0.53%   |
| Seagate ST1000DM003-1ER162 1TB                        | 5        | 0.53%   |
| Hitachi HDS721010CLA332 1TB                           | 5        | 0.53%   |
| Hitachi HDP725050GLA360 500GB                         | 5        | 0.53%   |
| WDC WDS100T2G0A-00JH30 1TB SSD                        | 4        | 0.42%   |
| WDC WD5000AAKX-60U6AA0 500GB                          | 4        | 0.42%   |
| WDC WD10EZEX-08M2NA0 1TB                              | 4        | 0.42%   |
| Toshiba MQ04ABF100 1TB                                | 4        | 0.42%   |
| Toshiba MQ01ABD100 1TB                                | 4        | 0.42%   |
| Seagate ST500LM012 HN-M500MBB 500GB                   | 4        | 0.42%   |
| Seagate ST3500418AS 500GB                             | 4        | 0.42%   |
| Samsung HD322HJ 320GB                                 | 4        | 0.42%   |
| Maxtor STM3320613AS 320GB                             | 4        | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives  | Percent |
|---------------------|----------|---------|---------|
| WDC                 | 120      | 167     | 24.84%  |
| Seagate             | 117      | 175     | 24.22%  |
| Toshiba             | 106      | 151     | 21.95%  |
| Hitachi             | 70       | 88      | 14.49%  |
| Maxtor              | 22       | 24      | 4.55%   |
| Samsung Electronics | 20       | 26      | 4.14%   |
| HGST                | 10       | 12      | 2.07%   |
| Unknown             | 3        | 4       | 0.62%   |
| JMicron Technology  | 3        | 3       | 0.62%   |
| Hewlett-Packard     | 2        | 3       | 0.41%   |
| Fujitsu             | 2        | 2       | 0.41%   |
| Apple               | 2        | 2       | 0.41%   |
| XrayDisk            | 1        | 1       | 0.21%   |
| SAGE                | 1        | Unknown | 0.21%   |
| IBM/Hitachi         | 1        | 1       | 0.21%   |
| HGST HTS            | 1        | 1       | 0.21%   |
| ExcelStor           | 1        | 1       | 0.21%   |
| ASMT                | 1        | 1       | 0.21%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 57       | 103    | 23.65%  |
| A-DATA Technology   | 35       | 43     | 14.52%  |
| Crucial             | 29       | 36     | 12.03%  |
| WDC                 | 19       | 31     | 7.88%   |
| Samsung Electronics | 17       | 21     | 7.05%   |
| Patriot             | 11       | 12     | 4.56%   |
| PNY                 | 9        | 12     | 3.73%   |
| SanDisk             | 7        | 10     | 2.9%    |
| Lexar               | 7        | 7      | 2.9%    |
| Team                | 6        | 8      | 2.49%   |
| Gigabyte Technology | 6        | 7      | 2.49%   |
| China               | 5        | 6      | 2.07%   |
| KingSpec            | 4        | 4      | 1.66%   |
| SPCC                | 3        | 3      | 1.24%   |
| Transcend           | 2        | 3      | 0.83%   |
| Toshiba             | 2        | 3      | 0.83%   |
| SK hynix            | 2        | 4      | 0.83%   |
| LITEON              | 2        | 3      | 0.83%   |
| Hewlett-Packard     | 2        | 2      | 0.83%   |
| Corsair             | 2        | 5      | 0.83%   |
| Unknown             | 2        | 2      | 0.83%   |
| XSTAR               | 1        | 1      | 0.41%   |
| XrayDisk            | 1        | 1      | 0.41%   |
| ValueTech           | 1        | 1      | 0.41%   |
| Unknown             | 1        | 1      | 0.41%   |
| Seagate             | 1        | 1      | 0.41%   |
| Netac               | 1        | 1      | 0.41%   |
| Micron Technology   | 1        | 1      | 0.41%   |
| KingFast            | 1        | 1      | 0.41%   |
| KingDian            | 1        | 1      | 0.41%   |
| EAGET               | 1        | 1      | 0.41%   |
| DTECHCO             | 1        | 3      | 0.41%   |
| 2.5"                | 1        | 1      | 0.41%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 342      | 662    | 50.52%  |
| SSD     | 203      | 339    | 29.99%  |
| NVMe    | 125      | 210    | 18.46%  |
| Unknown | 7        | 10     | 1.03%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 415      | 986    | 74.11%  |
| NVMe | 125      | 210    | 22.32%  |
| SAS  | 20       | 25     | 3.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 308      | 536    | 52.65%  |
| 0.51-1.0   | 203      | 340    | 34.7%   |
| 1.01-2.0   | 47       | 73     | 8.03%   |
| 2.01-3.0   | 9        | 14     | 1.54%   |
| 3.01-4.0   | 8        | 17     | 1.37%   |
| 4.01-10.0  | 7        | 15     | 1.2%    |
| 10.01-20.0 | 2        | 4      | 0.34%   |
| 20.01-50.0 | 1        | 2      | 0.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 103      | 20.12%  |
| 251-500        | 96       | 18.75%  |
| 501-1000       | 88       | 17.19%  |
| 1001-2000      | 60       | 11.72%  |
| 1-20           | 41       | 8.01%   |
| More than 3000 | 34       | 6.64%   |
| 51-100         | 33       | 6.45%   |
| 2001-3000      | 26       | 5.08%   |
| Unknown        | 19       | 3.71%   |
| 21-50          | 12       | 2.34%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 178      | 34.03%  |
| 21-50          | 78       | 14.91%  |
| 101-250        | 68       | 13%     |
| 51-100         | 53       | 10.13%  |
| 501-1000       | 41       | 7.84%   |
| 251-500        | 36       | 6.88%   |
| 1001-2000      | 27       | 5.16%   |
| Unknown        | 19       | 3.63%   |
| More than 3000 | 11       | 2.1%    |
| 2001-3000      | 8        | 1.53%   |
| 0              | 4        | 0.76%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                     | Desktops | Drives | Percent |
|-----------------------------------------------------------|----------|--------|---------|
| Toshiba DT01ACA100 1TB                                    | 4        | 5      | 3.15%   |
| Toshiba DT01ACA050 500GB                                  | 3        | 3      | 2.36%   |
| Seagate ST1000DM003-1ER162 1TB                            | 3        | 3      | 2.36%   |
| Hitachi HDS721050CLA362 500GB                             | 3        | 3      | 2.36%   |
| A-DATA Technology SU630 240GB SSD                         | 3        | 3      | 2.36%   |
| WDC WD3200AAJS-56M0A0 320GB                               | 2        | 2      | 1.57%   |
| WDC WD10EZEX-08WN4A0 1TB                                  | 2        | 3      | 1.57%   |
| Seagate ST500LT012-1DG142 500GB                           | 2        | 2      | 1.57%   |
| Seagate ST500DM002-1BD142 500GB                           | 2        | 2      | 1.57%   |
| Seagate ST3320613AS 320GB                                 | 2        | 4      | 1.57%   |
| Samsung Electronics HD322HJ 320GB                         | 2        | 2      | 1.57%   |
| Realtek Semiconductor RTS5763DL NVMe SSD Controller 512GB | 2        | 2      | 1.57%   |
| Hitachi HDS728080PLAT20 82GB                              | 2        | 2      | 1.57%   |
| Hitachi HDS721616PLA380 160GB                             | 2        | 2      | 1.57%   |
| Hitachi HDP725032GLA360 320GB                             | 2        | 2      | 1.57%   |
| XrayDisk SSD 256GB                                        | 1        | 1      | 0.79%   |
| WDC WDS100T2G0A-00JH30 1TB SSD                            | 1        | 2      | 0.79%   |
| WDC WD800JD-75MSA3 80GB                                   | 1        | 1      | 0.79%   |
| WDC WD800JD-60LSA0 80GB                                   | 1        | 1      | 0.79%   |
| WDC WD800BD-22MRA1 80GB                                   | 1        | 1      | 0.79%   |
| WDC WD6400AAKS-65Z7B0 640GB                               | 1        | 1      | 0.79%   |
| WDC WD5000LPLX-66ZNTT1 500GB                              | 1        | 1      | 0.79%   |
| WDC WD5000AAKX-60U6AA0 500GB                              | 1        | 1      | 0.79%   |
| WDC WD5000AAKS-08V0A0 500GB                               | 1        | 1      | 0.79%   |
| WDC WD3200BEVT-22ZCT0 320GB                               | 1        | 1      | 0.79%   |
| WDC WD3200BEKT-60PVMT0 320GB                              | 1        | 1      | 0.79%   |
| WDC WD3200AVJS-63B6A0 320GB                               | 1        | 1      | 0.79%   |
| WDC WD3200AAJS-65M0A0 320GB                               | 1        | 1      | 0.79%   |
| WDC WD3200AAJS-60Z0A0 320GB                               | 1        | 1      | 0.79%   |
| WDC WD3200AAJS-56B4A0 320GB                               | 1        | 1      | 0.79%   |
| WDC WD3200AAJS-08B4A0 320GB                               | 1        | 1      | 0.79%   |
| WDC WD2500BEVT-60ZCT1 250GB                               | 1        | 1      | 0.79%   |
| WDC WD20PURZ-85GU6Y0 2TB                                  | 1        | 1      | 0.79%   |
| WDC WD20PURZ-85AKKY0 2TB                                  | 1        | 1      | 0.79%   |
| WDC WD20EZRX-00DC0B0 2TB                                  | 1        | 1      | 0.79%   |
| WDC WD2003FYPS-27W9B0 2TB                                 | 1        | 1      | 0.79%   |
| WDC WD1600AAJS-75M0A0 160GB                               | 1        | 1      | 0.79%   |
| WDC WD10EZEX-08M2NA0 1TB                                  | 1        | 1      | 0.79%   |
| WDC WD10EURX-73FH1Y0 1TB                                  | 1        | 1      | 0.79%   |
| WDC WD10EALX-008EA0 1TB                                   | 1        | 3      | 0.79%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                         | Desktops | Drives | Percent |
|--------------------------------|----------|--------|---------|
| WDC                            | 24       | 34     | 21.43%  |
| Seagate                        | 22       | 34     | 19.64%  |
| Hitachi                        | 20       | 23     | 17.86%  |
| Toshiba                        | 15       | 17     | 13.39%  |
| Samsung Electronics            | 8        | 8      | 7.14%   |
| Maxtor                         | 7        | 8      | 6.25%   |
| A-DATA Technology              | 3        | 3      | 2.68%   |
| Realtek Semiconductor          | 2        | 2      | 1.79%   |
| HGST                           | 2        | 2      | 1.79%   |
| XrayDisk                       | 1        | 1      | 0.89%   |
| Team                           | 1        | 1      | 0.89%   |
| Solid State Storage Technology | 1        | 1      | 0.89%   |
| SK hynix                       | 1        | 2      | 0.89%   |
| Patriot                        | 1        | 1      | 0.89%   |
| Kingston                       | 1        | 1      | 0.89%   |
| HUADISK                        | 1        | 1      | 0.89%   |
| Fujitsu                        | 1        | 1      | 0.89%   |
| Crucial                        | 1        | 1      | 0.89%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 23       | 32     | 24.21%  |
| Seagate             | 22       | 34     | 23.16%  |
| Hitachi             | 20       | 23     | 21.05%  |
| Toshiba             | 15       | 17     | 15.79%  |
| Maxtor              | 7        | 8      | 7.37%   |
| Samsung Electronics | 5        | 5      | 5.26%   |
| HGST                | 2        | 2      | 2.11%   |
| Fujitsu             | 1        | 1      | 1.05%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 79       | 122    | 82.29%  |
| SSD  | 11       | 13     | 11.46%  |
| NVMe | 6        | 6      | 6.25%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                   | Desktops | Drives | Percent |
|-------------------------|----------|--------|---------|
| Maxtor STM380211AS 80GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Desktops | Drives | Percent |
|--------|----------|--------|---------|
| Maxtor | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 272      | 714    | 50.09%  |
| Works    | 176      | 365    | 32.41%  |
| Malfunc  | 94       | 141    | 17.31%  |
| Failed   | 1        | 1      | 0.18%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 279      | 44.08%  |
| AMD                            | 160      | 25.28%  |
| Samsung Electronics            | 28       | 4.42%   |
| SanDisk                        | 21       | 3.32%   |
| Nvidia                         | 21       | 3.32%   |
| ADATA Technology               | 15       | 2.37%   |
| Realtek Semiconductor          | 13       | 2.05%   |
| Phison Electronics             | 13       | 2.05%   |
| ASMedia Technology             | 13       | 2.05%   |
| Micron/Crucial Technology      | 11       | 1.74%   |
| Kingston Technology Company    | 11       | 1.74%   |
| Silicon Motion                 | 10       | 1.58%   |
| MAXIO Technology (Hangzhou)    | 7        | 1.11%   |
| JMicron Technology             | 7        | 1.11%   |
| VIA Technologies               | 6        | 0.95%   |
| Solid State Storage Technology | 2        | 0.32%   |
| Seagate Technology             | 2        | 0.32%   |
| Micron Technology              | 2        | 0.32%   |
| Marvell Technology Group       | 2        | 0.32%   |
| INNOGRIT                       | 2        | 0.32%   |
| Biwin Storage Technology       | 2        | 0.32%   |
| Union Memory (Shenzhen)        | 1        | 0.16%   |
| SK hynix                       | 1        | 0.16%   |
| Shenzhen Longsys Electronics   | 1        | 0.16%   |
| Hosin Global Electronics       | 1        | 0.16%   |
| Hewlett-Packard                | 1        | 0.16%   |
| Broadcom / LSI                 | 1        | 0.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 66       | 7.98%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 39       | 4.72%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 38       | 4.59%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 37       | 4.47%   |
| AMD 500 Series Chipset SATA Controller                                                  | 36       | 4.35%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 32       | 3.87%   |
| AMD 400 Series Chipset SATA Controller                                                  | 32       | 3.87%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 22       | 2.66%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 22       | 2.66%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 20       | 2.42%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 18       | 2.18%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 16       | 1.93%   |
| Nvidia MCP61 SATA Controller                                                            | 16       | 1.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 16       | 1.93%   |
| Intel SATA Controller [RAID mode]                                                       | 15       | 1.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 14       | 1.69%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 14       | 1.69%   |
| Nvidia MCP61 IDE                                                                        | 13       | 1.57%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 12       | 1.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 11       | 1.33%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 10       | 1.21%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 10       | 1.21%   |
| AMD 600 Series Chipset SATA Controller                                                  | 10       | 1.21%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 9        | 1.09%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9        | 1.09%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 8        | 0.97%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 8        | 0.97%   |
| Phison E12 NVMe Controller                                                              | 7        | 0.85%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 7        | 0.85%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7        | 0.85%   |
| Kingston Company NV1 NVMe SSD [SM2263XT] (DRAM-less)                                    | 6        | 0.73%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 6        | 0.73%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 6        | 0.73%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                              | 5        | 0.6%    |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 5        | 0.6%    |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                       | 5        | 0.6%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 5        | 0.6%    |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 5        | 0.6%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 5        | 0.6%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 5        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 335      | 52.92%  |
| IDE  | 141      | 22.27%  |
| NVMe | 125      | 19.75%  |
| RAID | 29       | 4.58%   |
| SAS  | 3        | 0.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 280      | 59.96%  |
| AMD    | 187      | 40.04%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-2400 CPU @ 3.10GHz            | 13       | 2.75%   |
| AMD Ryzen 5 3600 6-Core Processor           | 12       | 2.54%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 10       | 2.12%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 10       | 2.12%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 10       | 2.12%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 9        | 1.91%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 8        | 1.69%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 7        | 1.48%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 7        | 1.48%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 7        | 1.48%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 6        | 1.27%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 6        | 1.27%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 6        | 1.27%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 6        | 1.27%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 6        | 1.27%   |
| AMD FX-8320 Eight-Core Processor            | 6        | 1.27%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 5        | 1.06%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 5        | 1.06%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 5        | 1.06%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 5        | 1.06%   |
| AMD Ryzen 7 5700X 8-Core Processor          | 5        | 1.06%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 5        | 1.06%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 4        | 0.85%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 4        | 0.85%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 4        | 0.85%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 4        | 0.85%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 4        | 0.85%   |
| Intel Celeron CPU G1610 @ 2.60GHz           | 4        | 0.85%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 4        | 0.85%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 4        | 0.85%   |
| AMD Athlon 64 X2 Dual Core Processor 5200+  | 4        | 0.85%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 3        | 0.64%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 3        | 0.64%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 3        | 0.64%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 0.64%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 3        | 0.64%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 3        | 0.64%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 3        | 0.64%   |
| Intel Core i5-4590T CPU @ 2.00GHz           | 3        | 0.64%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 3        | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 82       | 17.37%  |
| AMD Ryzen 5             | 65       | 13.77%  |
| Intel Core i7           | 46       | 9.75%   |
| Intel Core i3           | 39       | 8.26%   |
| AMD Ryzen 7             | 24       | 5.08%   |
| Intel Xeon              | 20       | 4.24%   |
| Other                   | 17       | 3.6%    |
| AMD FX                  | 17       | 3.6%    |
| Intel Core 2 Duo        | 16       | 3.39%   |
| Intel Celeron           | 14       | 2.97%   |
| Intel Pentium Dual-Core | 13       | 2.75%   |
| AMD Ryzen 9             | 13       | 2.75%   |
| Intel Pentium           | 11       | 2.33%   |
| AMD Ryzen 3             | 11       | 2.33%   |
| Intel Pentium Dual      | 10       | 2.12%   |
| AMD Athlon II X2        | 8        | 1.69%   |
| AMD Athlon 64 X2        | 6        | 1.27%   |
| Intel Core 2 Quad       | 5        | 1.06%   |
| Intel Core 2            | 5        | 1.06%   |
| AMD Sempron             | 5        | 1.06%   |
| AMD Phenom II X6        | 5        | 1.06%   |
| AMD Phenom II X4        | 5        | 1.06%   |
| AMD Athlon              | 4        | 0.85%   |
| AMD Ryzen Threadripper  | 3        | 0.64%   |
| AMD Phenom              | 3        | 0.64%   |
| AMD A8                  | 3        | 0.64%   |
| AMD A10                 | 3        | 0.64%   |
| Intel Pentium D         | 2        | 0.42%   |
| Intel Pentium 4         | 2        | 0.42%   |
| AMD Ryzen 5 PRO         | 2        | 0.42%   |
| AMD A4                  | 2        | 0.42%   |
| Intel Pentium Gold      | 1        | 0.21%   |
| Intel Core i9           | 1        | 0.21%   |
| Intel Celeron D         | 1        | 0.21%   |
| Intel Atom              | 1        | 0.21%   |
| AMD Ryzen 7 PRO         | 1        | 0.21%   |
| AMD Phenom II X2        | 1        | 0.21%   |
| AMD E                   | 1        | 0.21%   |
| AMD Athlon II X4        | 1        | 0.21%   |
| AMD Athlon II X3        | 1        | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 152      | 32.34%  |
| 2      | 140      | 29.79%  |
| 6      | 87       | 18.51%  |
| 8      | 35       | 7.45%   |
| 12     | 15       | 3.19%   |
| 1      | 14       | 2.98%   |
| 16     | 10       | 2.13%   |
| 3      | 9        | 1.91%   |
| 10     | 5        | 1.06%   |
| 14     | 2        | 0.43%   |
| 20     | 1        | 0.21%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 462      | 98.72%  |
| 2      | 6        | 1.28%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 262      | 55.74%  |
| 1      | 207      | 44.04%  |
| 4      | 1        | 0.21%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 464      | 99.15%  |
| Unknown        | 2        | 0.43%   |
| 64-bit         | 1        | 0.21%   |
| 32-bit         | 1        | 0.21%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 228      | 46.91%  |
| 0x306c3    | 23       | 4.73%   |
| 0x206a7    | 20       | 4.12%   |
| 0x306a9    | 17       | 3.5%    |
| 0x1067a    | 15       | 3.09%   |
| 0x08108109 | 12       | 2.47%   |
| 0x08701021 | 11       | 2.26%   |
| 0x6fd      | 10       | 2.06%   |
| 0x06000852 | 10       | 2.06%   |
| 0x010000c8 | 9        | 1.85%   |
| 0x906e9    | 7        | 1.44%   |
| 0x506e3    | 7        | 1.44%   |
| 0x10676    | 6        | 1.23%   |
| 0x0a50000c | 6        | 1.23%   |
| 0xa0653    | 5        | 1.03%   |
| 0x906ea    | 5        | 1.03%   |
| 0x0800820d | 5        | 1.03%   |
| 0x010000dc | 5        | 1.03%   |
| 0xf65      | 3        | 0.62%   |
| 0xa0671    | 3        | 0.62%   |
| 0xa0655    | 3        | 0.62%   |
| 0x6fb      | 3        | 0.62%   |
| 0x20655    | 3        | 0.62%   |
| 0x20652    | 3        | 0.62%   |
| 0x106e5    | 3        | 0.62%   |
| 0x08001138 | 3        | 0.62%   |
| 0x06001119 | 3        | 0.62%   |
| 0x90672    | 2        | 0.41%   |
| 0x6f6      | 2        | 0.41%   |
| 0x6f2      | 2        | 0.41%   |
| 0x206d7    | 2        | 0.41%   |
| 0x0a601203 | 2        | 0.41%   |
| 0x0a50000d | 2        | 0.41%   |
| 0x0a20120a | 2        | 0.41%   |
| 0x0a201009 | 2        | 0.41%   |
| 0x08701013 | 2        | 0.41%   |
| 0x08001137 | 2        | 0.41%   |
| 0x06000822 | 2        | 0.41%   |
| 0x0600063e | 2        | 0.41%   |
| 0x03000027 | 2        | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 44       | 9.4%    |
| IvyBridge        | 41       | 8.76%   |
| SandyBridge      | 38       | 8.12%   |
| Zen 3            | 36       | 7.69%   |
| Zen 2            | 30       | 6.41%   |
| Penryn           | 30       | 6.41%   |
| Zen+             | 29       | 6.2%    |
| KabyLake         | 27       | 5.77%   |
| K10              | 27       | 5.77%   |
| Core             | 23       | 4.91%   |
| CometLake        | 20       | 4.27%   |
| Unknown          | 20       | 4.27%   |
| Piledriver       | 18       | 3.85%   |
| Skylake          | 13       | 2.78%   |
| Zen              | 12       | 2.56%   |
| Westmere         | 11       | 2.35%   |
| K8 Hammer        | 11       | 2.35%   |
| NetBurst         | 7        | 1.5%    |
| Alderlake Hybrid | 6        | 1.28%   |
| Nehalem          | 5        | 1.07%   |
| Bulldozer        | 4        | 0.85%   |
| Icelake          | 3        | 0.64%   |
| Steamroller      | 2        | 0.43%   |
| Silvermont       | 2        | 0.43%   |
| K10 Llano        | 2        | 0.43%   |
| Broadwell        | 2        | 0.43%   |
| TigerLake        | 1        | 0.21%   |
| Jaguar           | 1        | 0.21%   |
| Goldmont plus    | 1        | 0.21%   |
| Bonnell          | 1        | 0.21%   |
| Bobcat           | 1        | 0.21%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 179      | 35.03%  |
| Nvidia                     | 166      | 32.49%  |
| AMD                        | 159      | 31.12%  |
| Matrox Electronics Systems | 4        | 0.78%   |
| VIA Technologies           | 3        | 0.59%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 23       | 4.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 21       | 4.02%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 18       | 3.45%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 16       | 3.07%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 15       | 2.87%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 15       | 2.87%   |
| Nvidia GT218 [GeForce 210]                                                  | 14       | 2.68%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 13       | 2.49%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 12       | 2.3%    |
| Nvidia GK208B [GeForce GT 710]                                              | 11       | 2.11%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 11       | 2.11%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 10       | 1.92%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 10       | 1.92%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                       | 9        | 1.72%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 8        | 1.53%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 8        | 1.53%   |
| AMD Raphael                                                                 | 8        | 1.53%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 7        | 1.34%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 7        | 1.34%   |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                     | 7        | 1.34%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 7        | 1.34%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 6        | 1.15%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 6        | 1.15%   |
| Nvidia AD107 [GeForce RTX 4060]                                             | 6        | 1.15%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6        | 1.15%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 6        | 1.15%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 6        | 1.15%   |
| Nvidia GF119 [GeForce GT 610]                                               | 5        | 0.96%   |
| Intel Core Processor Integrated Graphics Controller                         | 5        | 0.96%   |
| AMD RS780L [Radeon 3000]                                                    | 5        | 0.96%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 5        | 0.96%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 4        | 0.77%   |
| Nvidia GK208B [GeForce GT 730]                                              | 4        | 0.77%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 4        | 0.77%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 4        | 0.77%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4        | 0.77%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                          | 4        | 0.77%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 3        | 0.57%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 3        | 0.57%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Intel       | 158      | 32.99%  |
| 1 x Nvidia      | 145      | 30.27%  |
| 1 x AMD         | 138      | 28.81%  |
| AMD + Nvidia    | 11       | 2.3%    |
| Intel + Nvidia  | 8        | 1.67%   |
| 2 x AMD         | 6        | 1.25%   |
| Intel + AMD     | 5        | 1.04%   |
| 1 x VIA         | 3        | 0.63%   |
| 1 x Matrox      | 3        | 0.63%   |
| 2 x Intel       | 1        | 0.21%   |
| Nvidia + Matrox | 1        | 0.21%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 390      | 81.59%  |
| Proprietary | 67       | 14.02%  |
| Unknown     | 21       | 4.39%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 263      | 54.12%  |
| 1.01-2.0   | 61       | 12.55%  |
| 0.51-1.0   | 48       | 9.88%   |
| 0.01-0.5   | 46       | 9.47%   |
| 7.01-8.0   | 25       | 5.14%   |
| 3.01-4.0   | 21       | 4.32%   |
| 8.01-16.0  | 9        | 1.85%   |
| 5.01-6.0   | 8        | 1.65%   |
| 2.01-3.0   | 4        | 0.82%   |
| 16.01-24.0 | 1        | 0.21%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 120      | 26.37%  |
| Goldstar             | 86       | 18.9%   |
| Hewlett-Packard      | 59       | 12.97%  |
| Dell                 | 31       | 6.81%   |
| Acer                 | 22       | 4.84%   |
| AOC                  | 15       | 3.3%    |
| Lenovo               | 11       | 2.42%   |
| ASUSTek Computer     | 11       | 2.42%   |
| ViewSonic            | 10       | 2.2%    |
| MSI                  | 8        | 1.76%   |
| Sceptre Tech         | 7        | 1.54%   |
| SAC                  | 7        | 1.54%   |
| LG Electronics       | 7        | 1.54%   |
| RTK                  | 6        | 1.32%   |
| Unknown              | 5        | 1.1%    |
| SANYO                | 4        | 0.88%   |
| BenQ                 | 4        | 0.88%   |
| HKC                  | 3        | 0.66%   |
| Ancor Communications | 3        | 0.66%   |
| SKG                  | 2        | 0.44%   |
| NCS                  | 2        | 0.44%   |
| Envision             | 2        | 0.44%   |
| YSP                  | 1        | 0.22%   |
| Westinghouse         | 1        | 0.22%   |
| VIE                  | 1        | 0.22%   |
| Unknown (XXX)        | 1        | 0.22%   |
| Unknown (CCC)        | 1        | 0.22%   |
| SMC                  | 1        | 0.22%   |
| Positivo             | 1        | 0.22%   |
| Planar               | 1        | 0.22%   |
| PEGA                 | 1        | 0.22%   |
| Panasonic            | 1        | 0.22%   |
| MStar                | 1        | 0.22%   |
| MSD                  | 1        | 0.22%   |
| Mi                   | 1        | 0.22%   |
| LG Display           | 1        | 0.22%   |
| KON                  | 1        | 0.22%   |
| KOA                  | 1        | 0.22%   |
| JRY                  | 1        | 0.22%   |
| ITE                  | 1        | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 8        | 1.69%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 7        | 1.48%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch    | 6        | 1.27%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch      | 6        | 1.27%   |
| Samsung Electronics S20D300 SAM0BDB 1366x768 432x240mm 19.5-inch       | 5        | 1.06%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 477x268mm 21.5-inch      | 5        | 1.06%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 5        | 1.06%   |
| SAC LED MONITOR SAC952D 1920x1080 480x270mm 21.7-inch                  | 5        | 1.06%   |
| Goldstar HD PLUS GSM5AC5 1600x900 440x250mm 19.9-inch                  | 5        | 1.06%   |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                    | 5        | 1.06%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch   | 4        | 0.85%   |
| Hewlett-Packard LV1911 HWP3005 1366x768 410x230mm 18.5-inch            | 4        | 0.85%   |
| Goldstar 20M35 GSM4EED 1600x900 433x236mm 19.4-inch                    | 4        | 0.85%   |
| Goldstar 19EN33 GSM4C18 1366x768 410x230mm 18.5-inch                   | 4        | 0.85%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch      | 3        | 0.64%   |
| Samsung Electronics SyncMaster SAM047D 1360x768 410x230mm 18.5-inch    | 3        | 0.64%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch      | 3        | 0.64%   |
| Samsung Electronics S22F350 SAM0D1B 1920x1080 477x268mm 21.5-inch      | 3        | 0.64%   |
| Samsung Electronics S19C150 SAM0AE6 1366x768 410x230mm 18.5-inch       | 3        | 0.64%   |
| Samsung Electronics Odyssey G40B SAM727D 1920x1080 597x336mm 27.0-inch | 3        | 0.64%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch  | 3        | 0.64%   |
| RTK TV RTK0001 3840x2160                                               | 3        | 0.64%   |
| Lenovo L197 Wide LEN1152 1440x900 410x257mm 19.1-inch                  | 3        | 0.64%   |
| Goldstar W2243 GSM56FE 1920x1080 477x269mm 21.6-inch                   | 3        | 0.64%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                    | 3        | 0.64%   |
| Goldstar ULTRAGEAR GSM7766 2560x1440 697x392mm 31.5-inch               | 3        | 0.64%   |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch          | 2        | 0.42%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                  | 2        | 0.42%   |
| SANYO LCD TV SAN0523 1920x1080 443x249mm 20.0-inch                     | 2        | 0.42%   |
| SANYO LCD MONITOR SAN2213 1600x900 477x268mm 21.5-inch                 | 2        | 0.42%   |
| Samsung Electronics SME1920N SAM06A3 1366x768 410x230mm 18.5-inch      | 2        | 0.42%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch   | 2        | 0.42%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch      | 2        | 0.42%   |
| RTK HX150T RTK1920 1920x1080 344x195mm 15.6-inch                       | 2        | 0.42%   |
| NCS LCD Monitor NCS2275 1920x1080 256x192mm 12.6-inch                  | 2        | 0.42%   |
| MSI G271CQR MSI6CC3 2560x1440 600x330mm 27.0-inch                      | 2        | 0.42%   |
| LG Electronics LCD Monitor E2241 1920x1080                             | 2        | 0.42%   |
| Hewlett-Packard V22 HPN36A8 1920x1080 477x268mm 21.5-inch              | 2        | 0.42%   |
| Hewlett-Packard Compaq W17q HWP26E1 1440x900 408x255mm 18.9-inch       | 2        | 0.42%   |
| Hewlett-Packard Compaq S1922 HWP290B 1366x768 413x234mm 18.7-inch      | 2        | 0.42%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 166      | 37.22%  |
| 1366x768 (WXGA)    | 58       | 13%     |
| 1600x900 (HD+)     | 38       | 8.52%   |
| 3840x2160 (4K)     | 34       | 7.62%   |
| 1440x900 (WXGA+)   | 34       | 7.62%   |
| 1280x1024 (SXGA)   | 27       | 6.05%   |
| 2560x1440 (QHD)    | 18       | 4.04%   |
| 1360x768           | 14       | 3.14%   |
| 1680x1050 (WSXGA+) | 12       | 2.69%   |
| 2560x1080          | 11       | 2.47%   |
| 1024x768 (XGA)     | 6        | 1.35%   |
| 1920x1200 (WUXGA)  | 4        | 0.9%    |
| Unknown            | 4        | 0.9%    |
| 3440x1440          | 3        | 0.67%   |
| 1280x960           | 3        | 0.67%   |
| 1280x720 (HD)      | 3        | 0.67%   |
| 3840x1080          | 2        | 0.45%   |
| 2160x1440          | 2        | 0.45%   |
| 6400x2160          | 1        | 0.22%   |
| 3840x1600          | 1        | 0.22%   |
| 3200x1080          | 1        | 0.22%   |
| 2560x1600          | 1        | 0.22%   |
| 2288x1287          | 1        | 0.22%   |
| 1920x540           | 1        | 0.22%   |
| 1152x864           | 1        | 0.22%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 64       | 14%     |
| 18      | 63       | 13.79%  |
| 19      | 55       | 12.04%  |
| 23      | 42       | 9.19%   |
| 27      | 36       | 7.88%   |
| 31      | 31       | 6.78%   |
| 20      | 26       | 5.69%   |
| 24      | 23       | 5.03%   |
| Unknown | 23       | 5.03%   |
| 17      | 20       | 4.38%   |
| 15      | 11       | 2.41%   |
| 34      | 10       | 2.19%   |
| 22      | 10       | 2.19%   |
| 72      | 5        | 1.09%   |
| 28      | 5        | 1.09%   |
| 84      | 4        | 0.88%   |
| 54      | 4        | 0.88%   |
| 32      | 4        | 0.88%   |
| 16      | 3        | 0.66%   |
| 12      | 3        | 0.66%   |
| 63      | 2        | 0.44%   |
| 48      | 2        | 0.44%   |
| 46      | 2        | 0.44%   |
| 65      | 1        | 0.22%   |
| 60      | 1        | 0.22%   |
| 58      | 1        | 0.22%   |
| 52      | 1        | 0.22%   |
| 40      | 1        | 0.22%   |
| 37      | 1        | 0.22%   |
| 29      | 1        | 0.22%   |
| 13      | 1        | 0.22%   |
| 11      | 1        | 0.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 202      | 45.8%   |
| 501-600     | 90       | 20.41%  |
| 601-700     | 39       | 8.84%   |
| 301-350     | 31       | 7.03%   |
| Unknown     | 23       | 5.22%   |
| 701-800     | 14       | 3.17%   |
| 1001-1500   | 14       | 3.17%   |
| 351-400     | 12       | 2.72%   |
| 1501-2000   | 9        | 2.04%   |
| 201-300     | 5        | 1.13%   |
| 801-900     | 2        | 0.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 296      | 70.81%  |
| 16/10   | 46       | 11%     |
| 5/4     | 26       | 6.22%   |
| Unknown | 20       | 4.78%   |
| 21/9    | 15       | 3.59%   |
| 4/3     | 11       | 2.63%   |
| 32/9    | 2        | 0.48%   |
| 6/5     | 1        | 0.24%   |
| 3/2     | 1        | 0.24%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 110      | 24.39%  |
| 151-200        | 106      | 23.5%   |
| 141-150        | 74       | 16.41%  |
| 351-500        | 46       | 10.2%   |
| 301-350        | 37       | 8.2%    |
| Unknown        | 23       | 5.1%    |
| More than 1000 | 20       | 4.43%   |
| 251-300        | 9        | 2%      |
| 101-110        | 9        | 2%      |
| 501-1000       | 5        | 1.11%   |
| 71-80          | 3        | 0.67%   |
| 131-140        | 3        | 0.67%   |
| 111-120        | 3        | 0.67%   |
| 81-90          | 1        | 0.22%   |
| 51-60          | 1        | 0.22%   |
| 121-130        | 1        | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 286      | 65.75%  |
| 101-120 | 83       | 19.08%  |
| 1-50    | 23       | 5.29%   |
| Unknown | 23       | 5.29%   |
| 161-240 | 10       | 2.3%    |
| 121-160 | 10       | 2.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 380      | 79.33%  |
| 2     | 61       | 12.73%  |
| 0     | 32       | 6.68%   |
| 3     | 6        | 1.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 315      | 48.39%  |
| Intel                             | 131      | 20.12%  |
| Qualcomm Atheros                  | 46       | 7.07%   |
| Ralink Technology                 | 30       | 4.61%   |
| TP-Link                           | 23       | 3.53%   |
| Broadcom                          | 17       | 2.61%   |
| Nvidia                            | 16       | 2.46%   |
| MediaTek                          | 14       | 2.15%   |
| Ralink                            | 8        | 1.23%   |
| Broadcom Limited                  | 6        | 0.92%   |
| Qualcomm Atheros Communications   | 5        | 0.77%   |
| Xiaomi                            | 4        | 0.61%   |
| VIA Technologies                  | 4        | 0.61%   |
| Marvell Technology Group          | 4        | 0.61%   |
| Samsung Electronics               | 3        | 0.46%   |
| Microsoft                         | 3        | 0.46%   |
| Mercucys                          | 3        | 0.46%   |
| Sundance Technology Inc / IC Plus | 2        | 0.31%   |
| Motorola PCS                      | 2        | 0.31%   |
| ICS Advent                        | 2        | 0.31%   |
| D-Link System                     | 2        | 0.31%   |
| ZyDAS                             | 1        | 0.15%   |
| Wistron NeWeb                     | 1        | 0.15%   |
| Texas Instruments                 | 1        | 0.15%   |
| Sierra Wireless                   | 1        | 0.15%   |
| Qualcomm                          | 1        | 0.15%   |
| OPPO Electronics                  | 1        | 0.15%   |
| Mellanox Technologies             | 1        | 0.15%   |
| LG Electronics                    | 1        | 0.15%   |
| Huawei Technologies               | 1        | 0.15%   |
| Encore Electronics                | 1        | 0.15%   |
| Aquantia                          | 1        | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 222      | 30.66%  |
| Realtek RTL8125 2.5GbE Controller                                      | 32       | 4.42%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 31       | 4.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 16       | 2.21%   |
| Intel Wi-Fi 6 AX200                                                    | 15       | 2.07%   |
| Intel I211 Gigabit Network Connection                                  | 15       | 2.07%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 13       | 1.8%    |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 13       | 1.8%    |
| Ralink MT7601U Wireless Adapter                                        | 13       | 1.8%    |
| Nvidia MCP61 Ethernet                                                  | 13       | 1.8%    |
| Intel Ethernet Controller I225-V                                       | 12       | 1.66%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 10       | 1.38%   |
| Intel 82579V Gigabit Network Connection                                | 9        | 1.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 8        | 1.1%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 7        | 0.97%   |
| Realtek 802.11ac NIC                                                   | 7        | 0.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 6        | 0.83%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 6        | 0.83%   |
| Intel Ethernet Connection I217-LM                                      | 6        | 0.83%   |
| TP-Link 802.11n NIC                                                    | 5        | 0.69%   |
| Qualcomm Atheros AR9271 802.11n                                        | 5        | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 5        | 0.69%   |
| Intel Wireless 7260                                                    | 5        | 0.69%   |
| Intel Ethernet Connection (2) I219-V                                   | 5        | 0.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 5        | 0.69%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 5        | 0.69%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 4        | 0.55%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 4        | 0.55%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 4        | 0.55%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 4        | 0.55%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 4        | 0.55%   |
| Intel Ethernet Connection (7) I219-V                                   | 4        | 0.55%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 3        | 0.41%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                  | 3        | 0.41%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 3        | 0.41%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 3        | 0.41%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 3        | 0.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3        | 0.41%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller              | 3        | 0.41%   |
| Ralink RT5370 Wireless Adapter                                         | 3        | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 59       | 26.58%  |
| Intel                           | 50       | 22.52%  |
| Ralink Technology               | 30       | 13.51%  |
| TP-Link                         | 23       | 10.36%  |
| Qualcomm Atheros                | 20       | 9.01%   |
| MediaTek                        | 12       | 5.41%   |
| Ralink                          | 8        | 3.6%    |
| Qualcomm Atheros Communications | 5        | 2.25%   |
| Microsoft                       | 3        | 1.35%   |
| Mercucys                        | 3        | 1.35%   |
| ZyDAS                           | 1        | 0.45%   |
| Wistron NeWeb                   | 1        | 0.45%   |
| Texas Instruments               | 1        | 0.45%   |
| Sierra Wireless                 | 1        | 0.45%   |
| LG Electronics                  | 1        | 0.45%   |
| Encore Electronics              | 1        | 0.45%   |
| D-Link System                   | 1        | 0.45%   |
| Broadcom Limited                | 1        | 0.45%   |
| Broadcom                        | 1        | 0.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 15       | 6.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 13       | 5.8%    |
| Ralink RT2870/RT3070 Wireless Adapter                                | 13       | 5.8%    |
| Ralink MT7601U Wireless Adapter                                      | 13       | 5.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 8        | 3.57%   |
| Realtek 802.11ac NIC                                                 | 7        | 3.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 6        | 2.68%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 6        | 2.68%   |
| TP-Link 802.11n NIC                                                  | 5        | 2.23%   |
| Qualcomm Atheros AR9271 802.11n                                      | 5        | 2.23%   |
| Intel Wireless 7260                                                  | 5        | 2.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 5        | 2.23%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 4        | 1.79%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 4        | 1.79%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 4        | 1.79%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 4        | 1.79%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                | 3        | 1.34%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 3        | 1.34%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 3        | 1.34%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller            | 3        | 1.34%   |
| Ralink RT5370 Wireless Adapter                                       | 3        | 1.34%   |
| Ralink RT2561/RT61 rev B 802.11g                                     | 3        | 1.34%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 3        | 1.34%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                     | 3        | 1.34%   |
| Mercucys 802.11n NIC                                                 | 3        | 1.34%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 3        | 1.34%   |
| Intel Wireless 7265                                                  | 3        | 1.34%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 3        | 1.34%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                              | 2        | 0.89%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 2        | 0.89%   |
| TP-Link 802.11ac WLAN Adapter                                        | 2        | 0.89%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                               | 2        | 0.89%   |
| Realtek RTL8190 802.11n PCI Wireless Network Adapter                 | 2        | 0.89%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter              | 2        | 0.89%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 2        | 0.89%   |
| Realtek RTL8187 Wireless Adapter                                     | 2        | 0.89%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 2        | 0.89%   |
| Microsoft Wireless XBox Controller Dongle                            | 2        | 0.89%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 2        | 0.89%   |
| Intel Centrino Wireless-N 2230                                       | 2        | 0.89%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 294      | 60.12%  |
| Intel                             | 105      | 21.47%  |
| Qualcomm Atheros                  | 26       | 5.32%   |
| Nvidia                            | 16       | 3.27%   |
| Broadcom                          | 16       | 3.27%   |
| Broadcom Limited                  | 5        | 1.02%   |
| Xiaomi                            | 4        | 0.82%   |
| VIA Technologies                  | 4        | 0.82%   |
| Marvell Technology Group          | 4        | 0.82%   |
| Samsung Electronics               | 3        | 0.61%   |
| Sundance Technology Inc / IC Plus | 2        | 0.41%   |
| Motorola PCS                      | 2        | 0.41%   |
| ICS Advent                        | 2        | 0.41%   |
| Qualcomm                          | 1        | 0.2%    |
| OPPO Electronics                  | 1        | 0.2%    |
| Mellanox Technologies             | 1        | 0.2%    |
| Huawei Technologies               | 1        | 0.2%    |
| D-Link System                     | 1        | 0.2%    |
| Aquantia                          | 1        | 0.2%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller     | 222      | 44.58%  |
| Realtek RTL8125 2.5GbE Controller                                          | 32       | 6.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 31       | 6.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 16       | 3.21%   |
| Intel I211 Gigabit Network Connection                                      | 15       | 3.01%   |
| Nvidia MCP61 Ethernet                                                      | 13       | 2.61%   |
| Intel Ethernet Controller I225-V                                           | 12       | 2.41%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 10       | 2.01%   |
| Intel 82579V Gigabit Network Connection                                    | 9        | 1.81%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 7        | 1.41%   |
| Intel Ethernet Connection I217-LM                                          | 6        | 1.2%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 5        | 1%      |
| Intel Ethernet Connection (2) I219-V                                       | 5        | 1%      |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                            | 5        | 1%      |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 4        | 0.8%    |
| Intel Ethernet Connection (7) I219-V                                       | 4        | 0.8%    |
| VIA VT6102/VT6103 [Rhine-II]                                               | 3        | 0.6%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                | 3        | 0.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 3        | 0.6%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 3        | 0.6%    |
| Intel Ethernet Connection I217-V                                           | 3        | 0.6%    |
| Intel Ethernet Connection (2) I219-LM                                      | 3        | 0.6%    |
| Intel 82578DC Gigabit Network Connection                                   | 3        | 0.6%    |
| Intel 82567LM-3 Gigabit Network Connection                                 | 3        | 0.6%    |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 2        | 0.4%    |
| Realtek RTL8126 5GbE Controller                                            | 2        | 0.4%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 2        | 0.4%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                 | 2        | 0.4%    |
| Nvidia MCP77 Ethernet                                                      | 2        | 0.4%    |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                    | 2        | 0.4%    |
| Intel NM10/ICH7 Family LAN Controller                                      | 2        | 0.4%    |
| Intel Ethernet Controller I226-V                                           | 2        | 0.4%    |
| Intel Ethernet Connection (17) I219-LM                                     | 2        | 0.4%    |
| Intel Ethernet Connection (12) I219-V                                      | 2        | 0.4%    |
| Intel Ethernet Connection (10) I219-V                                      | 2        | 0.4%    |
| Intel Alder Lake-S PCH CNVi WiFi                                           | 2        | 0.4%    |
| Intel 82578DM Gigabit Network Connection                                   | 2        | 0.4%    |
| Intel 82566DM-2 Gigabit Network Connection                                 | 2        | 0.4%    |
| Intel 82566DM Gigabit Network Connection                                   | 2        | 0.4%    |
| ICS Advent DM9601 Fast Ethernet Adapter                                    | 2        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 464      | 69.25%  |
| WiFi     | 204      | 30.45%  |
| Unknown  | 2        | 0.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 371      | 76.02%  |
| WiFi     | 117      | 23.98%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 328      | 69.64%  |
| 2     | 134      | 28.45%  |
| 3     | 5        | 1.06%   |
| 0     | 3        | 0.64%   |
| 7     | 1        | 0.21%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 394      | 82.77%  |
| Yes  | 82       | 17.23%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 48       | 36.36%  |
| Cambridge Silicon Radio         | 43       | 32.58%  |
| Realtek Semiconductor           | 10       | 7.58%   |
| IMC Networks                    | 7        | 5.3%    |
| MediaTek                        | 6        | 4.55%   |
| Foxconn / Hon Hai               | 5        | 3.79%   |
| ASUSTek Computer                | 3        | 2.27%   |
| Broadcom                        | 2        | 1.52%   |
| TP-Link                         | 1        | 0.76%   |
| Realtek                         | 1        | 0.76%   |
| Qualcomm Atheros Communications | 1        | 0.76%   |
| Primax Electronics              | 1        | 0.76%   |
| Dell                            | 1        | 0.76%   |
| Apple                           | 1        | 0.76%   |
| Actions                         | 1        | 0.76%   |
| Unknown                         | 1        | 0.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 43       | 32.58%  |
| Intel AX200 Bluetooth                               | 15       | 11.36%  |
| Intel Bluetooth wireless interface                  | 8        | 6.06%   |
| Realtek Bluetooth Radio                             | 7        | 5.3%    |
| MediaTek Wireless_Device                            | 6        | 4.55%   |
| Intel Wireless-AC 3168 Bluetooth                    | 5        | 3.79%   |
| Intel AX210 Bluetooth                               | 5        | 3.79%   |
| Intel Bluetooth Device                              | 4        | 3.03%   |
| IMC Networks Bluetooth Radio                        | 4        | 3.03%   |
| Foxconn / Hon Hai Wireless_Device                   | 4        | 3.03%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3        | 2.27%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3        | 2.27%   |
| Intel AX201 Bluetooth                               | 3        | 2.27%   |
| IMC Networks Wireless_Device                        | 3        | 2.27%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 1.52%   |
| ASUS ASUS USB-BT500                                 | 2        | 1.52%   |
| TP-Link TP-T@- UB500 Adapter                        | 1        | 0.76%   |
| Realtek RTL8723B Bluetooth                          | 1        | 0.76%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1        | 0.76%   |
| Realtek Bluetooth 5.3 Radio                         | 1        | 0.76%   |
| Realtek Bluetooth Radio                             | 1        | 0.76%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1        | 0.76%   |
| Primax Rocketfish RF-FLBTAD Bluetooth Adapter       | 1        | 0.76%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 1        | 0.76%   |
| Dell Wireless 365 Bluetooth                         | 1        | 0.76%   |
| Broadcom HP Portable Bumble Bee                     | 1        | 0.76%   |
| Broadcom Bluetooth 3.0 USB Dongle                   | 1        | 0.76%   |
| ASUS Bluetooth Radio                                | 1        | 0.76%   |
| Apple Bluetooth HCI                                 | 1        | 0.76%   |
| Actions general adapter                             | 1        | 0.76%   |
| Unknown                                             | 1        | 0.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 274      | 36.88%  |
| AMD                                  | 210      | 28.26%  |
| Nvidia                               | 164      | 22.07%  |
| C-Media Electronics                  | 15       | 2.02%   |
| Logitech                             | 8        | 1.08%   |
| Generalplus Technology               | 8        | 1.08%   |
| VIA Technologies                     | 5        | 0.67%   |
| Plantronics                          | 4        | 0.54%   |
| JMTek                                | 4        | 0.54%   |
| Creative Labs                        | 4        | 0.54%   |
| Texas Instruments                    | 3        | 0.4%    |
| M-Audio                              | 3        | 0.4%    |
| Kingston Technology                  | 3        | 0.4%    |
| Hewlett-Packard                      | 3        | 0.4%    |
| Blue Microphones                     | 3        | 0.4%    |
| Thesycon Systemsoftware & Consulting | 2        | 0.27%   |
| SteelSeries ApS                      | 2        | 0.27%   |
| Corsair                              | 2        | 0.27%   |
| Weltrend Semiconductor               | 1        | 0.13%   |
| Walmart                              | 1        | 0.13%   |
| Turtle Beach                         | 1        | 0.13%   |
| Trust                                | 1        | 0.13%   |
| RG-57_pro                            | 1        | 0.13%   |
| Realtek Semiconductor                | 1        | 0.13%   |
| Razer USA                            | 1        | 0.13%   |
| Micro Star International             | 1        | 0.13%   |
| Medeli Electronics                   | 1        | 0.13%   |
| liyuany                              | 1        | 0.13%   |
| KTMicro                              | 1        | 0.13%   |
| Jieli Technology                     | 1        | 0.13%   |
| HiBy                                 | 1        | 0.13%   |
| Harman International                 | 1        | 0.13%   |
| GN Netcom                            | 1        | 0.13%   |
| Giga-Byte Technology                 | 1        | 0.13%   |
| Focusrite-Novation                   | 1        | 0.13%   |
| Earth Computer Technologies          | 1        | 0.13%   |
| Drop                                 | 1        | 0.13%   |
| Creative Technology                  | 1        | 0.13%   |
| Avid Technology                      | 1        | 0.13%   |
| ASUSTek Computer                     | 1        | 0.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 59       | 6.64%   |
| AMD Ryzen HD Audio Controller                                              | 58       | 6.52%   |
| AMD Starship/Matisse HD Audio Controller                                   | 43       | 4.84%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 39       | 4.39%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 39       | 4.39%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 32       | 3.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 25       | 2.81%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 23       | 2.59%   |
| Nvidia High Definition Audio Controller                                    | 22       | 2.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 20       | 2.25%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 19       | 2.14%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 17       | 1.91%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 16       | 1.8%    |
| Nvidia MCP61 High Definition Audio                                         | 15       | 1.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 14       | 1.57%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 14       | 1.57%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 14       | 1.57%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 13       | 1.46%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 13       | 1.46%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 12       | 1.35%   |
| Nvidia GP107GL High Definition Audio Controller                            | 11       | 1.24%   |
| Intel Cannon Lake PCH cAVS                                                 | 10       | 1.12%   |
| AMD Radeon High Definition Audio Controller                                | 10       | 1.12%   |
| AMD FCH Azalia Controller                                                  | 10       | 1.12%   |
| Nvidia GF119 HDMI Audio Controller                                         | 9        | 1.01%   |
| Intel Comet Lake PCH-V cAVS                                                | 9        | 1.01%   |
| Intel 200 Series PCH HD Audio                                              | 9        | 1.01%   |
| AMD Navi 10 HDMI Audio                                                     | 9        | 1.01%   |
| Nvidia TU116 High Definition Audio Controller                              | 8        | 0.9%    |
| Nvidia GP106 High Definition Audio Controller                              | 8        | 0.9%    |
| Intel Alder Lake-S HD Audio Controller                                     | 8        | 0.9%    |
| Generalplus Technology USB Audio Device                                    | 8        | 0.9%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 8        | 0.9%    |
| Intel Smart Sound Technology (SST) Audio Controller                        | 7        | 0.79%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 7        | 0.79%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 7        | 0.79%   |
| Nvidia GP108 High Definition Audio Controller                              | 6        | 0.67%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 6        | 0.67%   |
| Nvidia GA104 High Definition Audio Controller                              | 6        | 0.67%   |
| Nvidia AD107 High Definition Audio Controller                              | 6        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 50       | 16.61%  |
| Corsair                      | 34       | 11.3%   |
| Samsung Electronics          | 32       | 10.63%  |
| A-DATA Technology            | 30       | 9.97%   |
| Kingston                     | 29       | 9.63%   |
| SK hynix                     | 16       | 5.32%   |
| Micron Technology            | 15       | 4.98%   |
| Crucial                      | 13       | 4.32%   |
| G.Skill                      | 11       | 3.65%   |
| Team                         | 9        | 2.99%   |
| Super Talent                 | 7        | 2.33%   |
| Patriot                      | 5        | 1.66%   |
| Nanya Technology             | 5        | 1.66%   |
| Unknown                      | 5        | 1.66%   |
| Ramaxel Technology           | 4        | 1.33%   |
| PNY                          | 4        | 1.33%   |
| Hewlett-Packard              | 4        | 1.33%   |
| GeIL                         | 4        | 1.33%   |
| Avant                        | 3        | 1%      |
| Kreton                       | 2        | 0.66%   |
| Unknown (AD8A)               | 1        | 0.33%   |
| Unknown (0x7F7FB5FFFFFFFFFF) | 1        | 0.33%   |
| Unknown (0x0C26)             | 1        | 0.33%   |
| Unknown (0B85)               | 1        | 0.33%   |
| Unknown (000080B30080)       | 1        | 0.33%   |
| Transcend                    | 1        | 0.33%   |
| tigo                         | 1        | 0.33%   |
| Sesame                       | 1        | 0.33%   |
| Ramos Technology             | 1        | 0.33%   |
| PUSKILL                      | 1        | 0.33%   |
| Patriot Memory (PDP Systems) | 1        | 0.33%   |
| Kllisre                      | 1        | 0.33%   |
| Hikvision                    | 1        | 0.33%   |
| Goldkey                      | 1        | 0.33%   |
| Golden Empire                | 1        | 0.33%   |
| Elpida                       | 1        | 0.33%   |
| CSX                          | 1        | 0.33%   |
| Atermiter                    | 1        | 0.33%   |
| Apacer                       | 1        | 0.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Super Talent RAM SUPERTALENT02 4GB DIMM DDR3 1600MT/s   | 7        | 2.1%    |
| Unknown RAM Module 2GB DIMM SDRAM                       | 6        | 1.8%    |
| Unknown RAM Module 2048MB DIMM SDRAM                    | 5        | 1.5%    |
| A-DATA RAM DDR4 3200 16GB DIMM DDR4 3600MT/s            | 5        | 1.5%    |
| Unknown                                                 | 5        | 1.5%    |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s             | 4        | 1.2%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s               | 3        | 0.9%    |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 3        | 0.9%    |
| Unknown RAM Module 2GB DIMM DDR2 533MT/s                | 3        | 0.9%    |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s      | 3        | 0.9%    |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s      | 3        | 0.9%    |
| Samsung RAM M3 78T2953EZ3-CF7 1GB DIMM DDR2 800MT/s     | 3        | 0.9%    |
| PNY RAM 8GBF1X08QFHH38-135-K 8GB DIMM DDR4 3600MT/s     | 3        | 0.9%    |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3600MT/s      | 3        | 0.9%    |
| GeIL RAM CL11-11-11 D3-1600 4GB DIMM 1866MT/s           | 3        | 0.9%    |
| Corsair RAM CMZ8GX3M1A1600C10 8GB DIMM DDR3 1600MT/s    | 3        | 0.9%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 3        | 0.9%    |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3200MT/s             | 3        | 0.9%    |
| Unknown RAM Module 4GB DIMM SDRAM                       | 2        | 0.6%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 2        | 0.6%    |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                | 2        | 0.6%    |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s      | 2        | 0.6%    |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s              | 2        | 0.6%    |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s          | 2        | 0.6%    |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s               | 2        | 0.6%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 2        | 0.6%    |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s     | 2        | 0.6%    |
| Samsung RAM DDR3 1600 8G 8GB DIMM DDR3 1600MT/s         | 2        | 0.6%    |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s     | 2        | 0.6%    |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 2133MT/s     | 2        | 0.6%    |
| Kingston RAM HP5189-2180-ELC 2GB DIMM DDR2 800MT/s      | 2        | 0.6%    |
| Crucial RAM BLS8G4D240FSB.16FBD2 8GB DIMM DDR4 2400MT/s | 2        | 0.6%    |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM SDRAM 1800MT/s    | 2        | 0.6%    |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s   | 2        | 0.6%    |
| Corsair RAM CMW32GX4M2Z3600C18 16GB DIMM DDR4 3733MT/s  | 2        | 0.6%    |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3733MT/s   | 2        | 0.6%    |
| Corsair RAM CMH32GX5M2E6000C36 16GB DIMM DDR5 6000MT/s  | 2        | 0.6%    |
| A-DATA RAM Module 8GB DIMM DDR4 2666MT/s                | 2        | 0.6%    |
| A-DATA RAM Module 4GB DIMM DDR4 2400MT/s                | 2        | 0.6%    |
| A-DATA RAM Module 4GB DIMM DDR3 1333MT/s                | 2        | 0.6%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 109      | 44.49%  |
| DDR3    | 70       | 28.57%  |
| SDRAM   | 21       | 8.57%   |
| DDR2    | 17       | 6.94%   |
| Unknown | 12       | 4.9%    |
| DDR5    | 9        | 3.67%   |
| DDR     | 5        | 2.04%   |
| LPDDR4  | 1        | 0.41%   |
| DRAM    | 1        | 0.41%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 221      | 93.25%  |
| SODIMM       | 14       | 5.91%   |
| Row Of Chips | 1        | 0.42%   |
| Chip         | 1        | 0.42%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 91       | 32.5%   |
| 4096  | 58       | 20.71%  |
| 2048  | 49       | 17.5%   |
| 16384 | 44       | 15.71%  |
| 32768 | 23       | 8.21%   |
| 1024  | 12       | 4.29%   |
| 49152 | 1        | 0.36%   |
| 24576 | 1        | 0.36%   |
| 512   | 1        | 0.36%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 48       | 17.08%  |
| 1333    | 34       | 12.1%   |
| 3600    | 28       | 9.96%   |
| 3200    | 24       | 8.54%   |
| 2400    | 17       | 6.05%   |
| Unknown | 15       | 5.34%   |
| 2133    | 11       | 3.91%   |
| 3733    | 9        | 3.2%    |
| 800     | 9        | 3.2%    |
| 2667    | 8        | 2.85%   |
| 3000    | 7        | 2.49%   |
| 2666    | 7        | 2.49%   |
| 3800    | 6        | 2.14%   |
| 1866    | 6        | 2.14%   |
| 667     | 6        | 2.14%   |
| 533     | 4        | 1.42%   |
| 6000    | 3        | 1.07%   |
| 5600    | 3        | 1.07%   |
| 3066    | 3        | 1.07%   |
| 1867    | 3        | 1.07%   |
| 1800    | 3        | 1.07%   |
| 4800    | 2        | 0.71%   |
| 3866    | 2        | 0.71%   |
| 3400    | 2        | 0.71%   |
| 1334    | 2        | 0.71%   |
| 400     | 2        | 0.71%   |
| 333     | 2        | 0.71%   |
| 49926   | 1        | 0.36%   |
| 6200    | 1        | 0.36%   |
| 5400    | 1        | 0.36%   |
| 4000    | 1        | 0.36%   |
| 3500    | 1        | 0.36%   |
| 3467    | 1        | 0.36%   |
| 3466    | 1        | 0.36%   |
| 3334    | 1        | 0.36%   |
| 3333    | 1        | 0.36%   |
| 3100    | 1        | 0.36%   |
| 2800    | 1        | 0.36%   |
| 2747    | 1        | 0.36%   |
| 1400    | 1        | 0.36%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 7        | 26.92%  |
| Samsung Electronics | 5        | 19.23%  |
| Seiko Epson         | 3        | 11.54%  |
| Brother Industries  | 3        | 11.54%  |
| Ricoh               | 2        | 7.69%   |
| iDPRT               | 2        | 7.69%   |
| Canon               | 2        | 7.69%   |
| Prolific Technology | 1        | 3.85%   |
| Philips (or NXP)    | 1        | 3.85%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Seiko Epson L120 Series                                | 2        | 7.69%   |
| iDPRT SP410                                            | 2        | 7.69%   |
| HP LaserJet 1020                                       | 2        | 7.69%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F | 1        | 3.85%   |
| Samsung SCX-3400 Series                                | 1        | 3.85%   |
| Samsung ML-2240 Series                                 | 1        | 3.85%   |
| Samsung ML-2010P Mono Laser Printer                    | 1        | 3.85%   |
| Samsung M2020 Series                                   | 1        | 3.85%   |
| Samsung Composite Device                               | 1        | 3.85%   |
| Ricoh Printing Support                                 | 1        | 3.85%   |
| Ricoh Aficio SP 3510DN                                 | 1        | 3.85%   |
| Prolific PL2305 Parallel Port                          | 1        | 3.85%   |
| Philips (or NXP) USB Printer                           | 1        | 3.85%   |
| HP Smart Tank 510 series                               | 1        | 3.85%   |
| HP LaserJet CP 1025                                    | 1        | 3.85%   |
| HP HP Laser 107w                                       | 1        | 3.85%   |
| HP DeskJet 5810 series                                 | 1        | 3.85%   |
| HP Deskjet 2540 series                                 | 1        | 3.85%   |
| Canon G3000 series                                     | 1        | 3.85%   |
| Canon G2060 series                                     | 1        | 3.85%   |
| Brother QL-800 Label Printer                           | 1        | 3.85%   |
| Brother MFC-J1205W                                     | 1        | 3.85%   |
| Brother DCP-T710W                                      | 1        | 3.85%   |

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


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 24       | 23.53%  |
| KYE Systems (Mouse Systems)            | 12       | 11.76%  |
| Microdia                               | 10       | 9.8%    |
| Chicony Electronics                    | 6        | 5.88%   |
| Microsoft                              | 5        | 4.9%    |
| Generalplus Technology                 | 5        | 4.9%    |
| Sunplus Innovation Technology          | 4        | 3.92%   |
| Cubeternet                             | 4        | 3.92%   |
| Samsung Electronics                    | 3        | 2.94%   |
| Huawei Technologies                    | 3        | 2.94%   |
| GEMBIRD                                | 3        | 2.94%   |
| WaveRider Communications               | 2        | 1.96%   |
| Realtek Semiconductor                  | 2        | 1.96%   |
| Bison Electronics                      | 2        | 1.96%   |
| Arkmicro Technologies                  | 2        | 1.96%   |
| Z-Star Microelectronics                | 1        | 0.98%   |
| webcamvendor                           | 1        | 0.98%   |
| webcam                                 | 1        | 0.98%   |
| Web Camera                             | 1        | 0.98%   |
| USB CAMERA                             | 1        | 0.98%   |
| Unknown                                | 1        | 0.98%   |
| Trust                                  | 1        | 0.98%   |
| Sony                                   | 1        | 0.98%   |
| Sonix Technology                       | 1        | 0.98%   |
| Pixart Imaging                         | 1        | 0.98%   |
| OmniVision Technologies                | 1        | 0.98%   |
| Minton Optic Industry                  | 1        | 0.98%   |
| Hewlett-Packard                        | 1        | 0.98%   |
| Cheng Uei Precision Industry (Foxlink) | 1        | 0.98%   |
| Unknown                                | 1        | 0.98%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                                  | 7        | 6.86%   |
| Microdia Integrated Camera                                   | 5        | 4.9%    |
| Logitech HD Webcam C525                                      | 5        | 4.9%    |
| KYE Systems (Mouse Systems) FaceCam 1000X                    | 4        | 3.92%   |
| Generalplus GENERAL WEBCAM                                   | 4        | 3.92%   |
| Sunplus Full HD webcam                                       | 3        | 2.94%   |
| Samsung Galaxy series, misc. (MTP mode)                      | 3        | 2.94%   |
| Logitech Webcam C170                                         | 3        | 2.94%   |
| Huawei HiCamera                                              | 3        | 2.94%   |
| Cubeternet GL-UPC822 UVC WebCam                              | 3        | 2.94%   |
| Chicony HP High Definition 1MP Webcam                        | 3        | 2.94%   |
| Microdia USB 2.0 Camera                                      | 2        | 1.96%   |
| Logitech Webcam C930e                                        | 2        | 1.96%   |
| Logitech Webcam C270                                         | 2        | 1.96%   |
| Logitech BRIO Ultra HD Webcam                                | 2        | 1.96%   |
| KYE Systems (Mouse Systems) FaceCam 320X                     | 2        | 1.96%   |
| GEMBIRD USB2.0 PC CAMERA                                     | 2        | 1.96%   |
| Z-Star Lenovo IdeaCentre Web Camera                          | 1        | 0.98%   |
| webcamvendor NexiGo N60 FHD Webcam                           | 1        | 0.98%   |
| webcam webcam                                                | 1        | 0.98%   |
| Web Camera Web Camera                                        | 1        | 0.98%   |
| WaveRider USB Live camera                                    | 1        | 0.98%   |
| WaveRider USB 2.0 Camera                                     | 1        | 0.98%   |
| USB CAMERA USB CAMERA                                        | 1        | 0.98%   |
| Unknown HD camera                                            | 1        | 0.98%   |
| Trust Full HD Webcam                                         | 1        | 0.98%   |
| Sunplus SPCA2281 Web Camera                                  | 1        | 0.98%   |
| Sony CEVCECM                                                 | 1        | 0.98%   |
| Sonix EMEET SmartCam C950                                    | 1        | 0.98%   |
| Realtek Thronmax Stream Go Pro Webcam                        | 1        | 0.98%   |
| Realtek FULL HD 1080P Webcam                                 | 1        | 0.98%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                         | 1        | 0.98%   |
| OmniVision Monitor Webcam                                    | 1        | 0.98%   |
| Minton Optic Industry S-Cam F5/D-Link DSC-350 Digital Camera | 1        | 0.98%   |
| Microsoft Microsoft LifeCam HD-6000 for Notebooks            | 1        | 0.98%   |
| Microsoft LifeCam Studio                                     | 1        | 0.98%   |
| Microsoft LifeCam HD-5000                                    | 1        | 0.98%   |
| Microsoft LifeCam HD-3000                                    | 1        | 0.98%   |
| Microsoft LifeCam Cinema                                     | 1        | 0.98%   |
| Microdia Webcam Vitade AF                                    | 1        | 0.98%   |

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
| 0     | 404      | 84.34%  |
| 1     | 64       | 13.36%  |
| 2     | 9        | 1.88%   |
| 4     | 1        | 0.21%   |
| 3     | 1        | 0.21%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 35       | 41.18%  |
| Net/wireless             | 26       | 30.59%  |
| Communication controller | 8        | 9.41%   |
| Unassigned class         | 3        | 3.53%   |
| Storage/raid             | 3        | 3.53%   |
| Network                  | 3        | 3.53%   |
| Multimedia controller    | 3        | 3.53%   |
| Sound                    | 2        | 2.35%   |
| Card reader              | 1        | 1.18%   |
| Camera                   | 1        | 1.18%   |

