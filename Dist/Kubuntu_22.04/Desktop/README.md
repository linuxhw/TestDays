Kubuntu 22.04 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Kubuntu 22.04.

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

Total: 561

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | 08WKV3 A00                  | [e16dbbaf8b](https://linux-hardware.org/?probe=e16dbbaf8b) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [4f690a4297](https://linux-hardware.org/?probe=4f690a4297) | Nov 05, 2023 |
| Unknown       | Unknown                     | [85733c0ec0](https://linux-hardware.org/?probe=85733c0ec0) | Nov 05, 2023 |
| ASUSTek       | M5A97 R2.0                  | [8a4147b40a](https://linux-hardware.org/?probe=8a4147b40a) | Nov 05, 2023 |
| Gigabyte      | H81M-DS2                    | [5ac9818b1f](https://linux-hardware.org/?probe=5ac9818b1f) | Nov 03, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [c9e7b12e63](https://linux-hardware.org/?probe=c9e7b12e63) | Nov 03, 2023 |
| Gigabyte      | P35-DS3L                    | [c2df6f267b](https://linux-hardware.org/?probe=c2df6f267b) | Nov 03, 2023 |
| ASRock        | H61M-VS                     | [677490b7c2](https://linux-hardware.org/?probe=677490b7c2) | Nov 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | [0f4435d620](https://linux-hardware.org/?probe=0f4435d620) | Nov 02, 2023 |
| MSI           | B450-A PRO                  | [f0b1ef4bc8](https://linux-hardware.org/?probe=f0b1ef4bc8) | Nov 01, 2023 |
| ASUSTek       | Z170-A                      | [50a30d4ebd](https://linux-hardware.org/?probe=50a30d4ebd) | Nov 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [7271f0fc8c](https://linux-hardware.org/?probe=7271f0fc8c) | Nov 01, 2023 |
| HP            | 2AF7                        | [0a2c239b75](https://linux-hardware.org/?probe=0a2c239b75) | Nov 01, 2023 |
| ASRock        | H110 Pro BTC+               | [c889a29b7f](https://linux-hardware.org/?probe=c889a29b7f) | Oct 31, 2023 |
| Lenovo        | MAHOBAY NOK                 | [77d9982cf2](https://linux-hardware.org/?probe=77d9982cf2) | Oct 31, 2023 |
| Unknown       | Unknown                     | [986edacf9a](https://linux-hardware.org/?probe=986edacf9a) | Oct 30, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [40769bf0a3](https://linux-hardware.org/?probe=40769bf0a3) | Oct 27, 2023 |
| MSI           | B250M PRO-VDH               | [c3d5a72f41](https://linux-hardware.org/?probe=c3d5a72f41) | Oct 27, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | [3831a70240](https://linux-hardware.org/?probe=3831a70240) | Oct 27, 2023 |
| SYWZ          | S210H Series                | [9239922f80](https://linux-hardware.org/?probe=9239922f80) | Oct 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c74b24edc0](https://linux-hardware.org/?probe=c74b24edc0) | Oct 23, 2023 |
| ASRockRack    | ROMED8-2T                   | [d71e04d478](https://linux-hardware.org/?probe=d71e04d478) | Oct 23, 2023 |
| Gigabyte      | Z77X-UP7                    | [806cdb2bef](https://linux-hardware.org/?probe=806cdb2bef) | Oct 23, 2023 |
| Gigabyte      | GA-890FXA-UD5               | [bd8cdfe190](https://linux-hardware.org/?probe=bd8cdfe190) | Oct 22, 2023 |
| ECS           | CHICAGO2                    | [e33ec52f5a](https://linux-hardware.org/?probe=e33ec52f5a) | Oct 21, 2023 |
| Unknown       | Unknown                     | [f23d0ff7da](https://linux-hardware.org/?probe=f23d0ff7da) | Oct 20, 2023 |
| Unknown       | Unknown                     | [09b04f5fd5](https://linux-hardware.org/?probe=09b04f5fd5) | Oct 20, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [a0cdc0c3e1](https://linux-hardware.org/?probe=a0cdc0c3e1) | Oct 19, 2023 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | [c2215ccabb](https://linux-hardware.org/?probe=c2215ccabb) | Oct 19, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [aad7482915](https://linux-hardware.org/?probe=aad7482915) | Oct 19, 2023 |
| MSI           | B560M PRO                   | [1dba250310](https://linux-hardware.org/?probe=1dba250310) | Oct 14, 2023 |
| Shenzhen M... | F6BFC                       | [007ce9ca02](https://linux-hardware.org/?probe=007ce9ca02) | Oct 14, 2023 |
| ASUSTek       | P8Z77-V LX                  | [09a90189ec](https://linux-hardware.org/?probe=09a90189ec) | Oct 14, 2023 |
| MSI           | B85-G43                     | [8684995c92](https://linux-hardware.org/?probe=8684995c92) | Oct 13, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [f6dac1e5f6](https://linux-hardware.org/?probe=f6dac1e5f6) | Oct 09, 2023 |
| ASRock        | 970 Pro3 R2.0               | [84ff0a9a08](https://linux-hardware.org/?probe=84ff0a9a08) | Oct 07, 2023 |
| ASRock        | 970 Pro3 R2.0               | [1505f63948](https://linux-hardware.org/?probe=1505f63948) | Oct 07, 2023 |
| MSI           | Z370 GAMING PLUS            | [7e01bc1824](https://linux-hardware.org/?probe=7e01bc1824) | Oct 06, 2023 |
| ASUSTek       | Z87-PRO                     | [31248aa2bf](https://linux-hardware.org/?probe=31248aa2bf) | Oct 06, 2023 |
| MSI           | Z370 GAMING PLUS            | [57b1771805](https://linux-hardware.org/?probe=57b1771805) | Oct 04, 2023 |
| ASUSTek       | E2KM1I-DELUXE               | [bb9493309a](https://linux-hardware.org/?probe=bb9493309a) | Oct 04, 2023 |
| Gigabyte      | AX370-Gaming K7             | [f8ee109cbd](https://linux-hardware.org/?probe=f8ee109cbd) | Oct 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [1448f32279](https://linux-hardware.org/?probe=1448f32279) | Oct 01, 2023 |
| ASUSTek       | EB1501P                     | [df48fa7e96](https://linux-hardware.org/?probe=df48fa7e96) | Sep 29, 2023 |
| Unknown       | Unknown                     | [a329c5630e](https://linux-hardware.org/?probe=a329c5630e) | Sep 28, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | [e54490e96a](https://linux-hardware.org/?probe=e54490e96a) | Sep 27, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | [2f574aa287](https://linux-hardware.org/?probe=2f574aa287) | Sep 27, 2023 |
| Acer          | FX58M                       | [e24f36e0bd](https://linux-hardware.org/?probe=e24f36e0bd) | Sep 26, 2023 |
| ASUSTek       | PRIME Z390-P                | [37840dad1c](https://linux-hardware.org/?probe=37840dad1c) | Sep 26, 2023 |
| Unknown       | Unknown                     | [56cd5e0bfd](https://linux-hardware.org/?probe=56cd5e0bfd) | Sep 25, 2023 |
| ASRock        | ALiveXFire-eSATA2           | [7e69c8e2e1](https://linux-hardware.org/?probe=7e69c8e2e1) | Sep 23, 2023 |
| Dell          | 0D881F A05                  | [583c577b02](https://linux-hardware.org/?probe=583c577b02) | Sep 22, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | [16fe0e3ba6](https://linux-hardware.org/?probe=16fe0e3ba6) | Sep 22, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | [aab34fa582](https://linux-hardware.org/?probe=aab34fa582) | Sep 22, 2023 |
| HP            | 18E7                        | [ba0cb8996d](https://linux-hardware.org/?probe=ba0cb8996d) | Sep 21, 2023 |
| Gigabyte      | H310M H                     | [389282109e](https://linux-hardware.org/?probe=389282109e) | Sep 21, 2023 |
| ASUSTek       | Rampage V EDITION 10        | [e753271d63](https://linux-hardware.org/?probe=e753271d63) | Sep 19, 2023 |
| ASRock        | Z68 Pro3                    | [4ffee8598b](https://linux-hardware.org/?probe=4ffee8598b) | Sep 19, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [c8a7f18e5d](https://linux-hardware.org/?probe=c8a7f18e5d) | Sep 19, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [144dcee0ae](https://linux-hardware.org/?probe=144dcee0ae) | Sep 18, 2023 |
| Gigabyte      | H310M H                     | [5a9f4e8791](https://linux-hardware.org/?probe=5a9f4e8791) | Sep 17, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [e6db76aa66](https://linux-hardware.org/?probe=e6db76aa66) | Sep 17, 2023 |
| ASUSTek       | Z97-PRO                     | [37d6d12772](https://linux-hardware.org/?probe=37d6d12772) | Sep 15, 2023 |
| HP            | 0A9Ch                       | [4894ac01b8](https://linux-hardware.org/?probe=4894ac01b8) | Sep 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | [15256fdeb2](https://linux-hardware.org/?probe=15256fdeb2) | Sep 14, 2023 |
| HP            | 1998                        | [c3451afea8](https://linux-hardware.org/?probe=c3451afea8) | Sep 11, 2023 |
| Alienware     | 0H869M A00                  | [64132daa63](https://linux-hardware.org/?probe=64132daa63) | Sep 06, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [d2ae9b900d](https://linux-hardware.org/?probe=d2ae9b900d) | Sep 06, 2023 |
| Gigabyte      | H510M H                     | [1aeb1ffd17](https://linux-hardware.org/?probe=1aeb1ffd17) | Sep 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | [7dabe0d117](https://linux-hardware.org/?probe=7dabe0d117) | Sep 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [d80ee341d8](https://linux-hardware.org/?probe=d80ee341d8) | Sep 01, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [17e971c3fb](https://linux-hardware.org/?probe=17e971c3fb) | Aug 31, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | [d9a8673516](https://linux-hardware.org/?probe=d9a8673516) | Aug 31, 2023 |
| AZW           | MINI S                      | [fb828c24eb](https://linux-hardware.org/?probe=fb828c24eb) | Aug 31, 2023 |
| Gigabyte      | H310M H                     | [ca4ddb2663](https://linux-hardware.org/?probe=ca4ddb2663) | Aug 29, 2023 |
| HP            | 212B                        | [80b2496334](https://linux-hardware.org/?probe=80b2496334) | Aug 29, 2023 |
| ASUSTek       | Pro WS 565-ACE              | [ae73127da5](https://linux-hardware.org/?probe=ae73127da5) | Aug 28, 2023 |
| HP            | 18E7                        | [0b94065a0f](https://linux-hardware.org/?probe=0b94065a0f) | Aug 27, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [cf2cba5c59](https://linux-hardware.org/?probe=cf2cba5c59) | Aug 26, 2023 |
| MSI           | 990FXA GAMING               | [813d9c9c10](https://linux-hardware.org/?probe=813d9c9c10) | Aug 26, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [5004de7897](https://linux-hardware.org/?probe=5004de7897) | Aug 26, 2023 |
| ASUSTek       | M5A97 R2.0                  | [0161911081](https://linux-hardware.org/?probe=0161911081) | Aug 24, 2023 |
| Dell          | 0D881F A05                  | [8c6f4a2e1c](https://linux-hardware.org/?probe=8c6f4a2e1c) | Aug 21, 2023 |
| Fujitsu       | D3602-A1 S26361-D3602-A1    | [8144c6d466](https://linux-hardware.org/?probe=8144c6d466) | Aug 21, 2023 |
| MSI           | B250M MORTAR                | [fc97ccab18](https://linux-hardware.org/?probe=fc97ccab18) | Aug 17, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS WI... | [1962f7a581](https://linux-hardware.org/?probe=1962f7a581) | Aug 17, 2023 |
| Intel         | D53427RKE G87971-402        | [433dcaffa6](https://linux-hardware.org/?probe=433dcaffa6) | Aug 17, 2023 |
| ASRock        | Z77 Extreme4                | [e9f564475b](https://linux-hardware.org/?probe=e9f564475b) | Aug 16, 2023 |
| Dell          | 0D881F A05                  | [83dd0f7fe7](https://linux-hardware.org/?probe=83dd0f7fe7) | Aug 14, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [e2fe66aca4](https://linux-hardware.org/?probe=e2fe66aca4) | Aug 13, 2023 |
| Gigabyte      | Z690 AORUS MASTER           | [760a5d6077](https://linux-hardware.org/?probe=760a5d6077) | Aug 13, 2023 |
| Dell          | 0GNVHC A00                  | [27e3be4942](https://linux-hardware.org/?probe=27e3be4942) | Aug 12, 2023 |
| ASUSTek       | CM1630                      | [dfd52e2852](https://linux-hardware.org/?probe=dfd52e2852) | Aug 12, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [b4b9fa2d17](https://linux-hardware.org/?probe=b4b9fa2d17) | Aug 12, 2023 |
| ASUSTek       | CM1630                      | [d8f56bcdaf](https://linux-hardware.org/?probe=d8f56bcdaf) | Aug 12, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [181db8cf87](https://linux-hardware.org/?probe=181db8cf87) | Aug 11, 2023 |
| Gigabyte      | Z690 AORUS MASTER           | [be6c815f39](https://linux-hardware.org/?probe=be6c815f39) | Aug 10, 2023 |
| ASUSTek       | Q87M-E                      | [0dee84c129](https://linux-hardware.org/?probe=0dee84c129) | Aug 10, 2023 |
| ASRock        | N68C-S UCC                  | [ebe7ed3f69](https://linux-hardware.org/?probe=ebe7ed3f69) | Aug 07, 2023 |
| MSI           | B450M-A PRO MAX             | [ec1bd43523](https://linux-hardware.org/?probe=ec1bd43523) | Aug 05, 2023 |
| HP            | 2AF7                        | [655c896815](https://linux-hardware.org/?probe=655c896815) | Aug 04, 2023 |
| Unknown       | Unknown                     | [3bb1942723](https://linux-hardware.org/?probe=3bb1942723) | Aug 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | [7748df9ae9](https://linux-hardware.org/?probe=7748df9ae9) | Aug 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [48c7912f46](https://linux-hardware.org/?probe=48c7912f46) | Aug 01, 2023 |
| MSI           | PRO Z690-A                  | [19f4cb0c69](https://linux-hardware.org/?probe=19f4cb0c69) | Jul 31, 2023 |
| MSI           | X99S SLI PLUS               | [edf7fd3a91](https://linux-hardware.org/?probe=edf7fd3a91) | Jul 28, 2023 |
| Gigabyte      | EP45T-UD3LR                 | [c2928283bd](https://linux-hardware.org/?probe=c2928283bd) | Jul 28, 2023 |
| MSI           | PRO Z690-A                  | [f1a5d69727](https://linux-hardware.org/?probe=f1a5d69727) | Jul 28, 2023 |
| Supermicro    | C7H61                       | [57c9a4eeff](https://linux-hardware.org/?probe=57c9a4eeff) | Jul 27, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [810ff8bbd6](https://linux-hardware.org/?probe=810ff8bbd6) | Jul 26, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [3548050f99](https://linux-hardware.org/?probe=3548050f99) | Jul 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | [4a1a31cb65](https://linux-hardware.org/?probe=4a1a31cb65) | Jul 25, 2023 |
| Gigabyte      | P67A-UD3-B3                 | [26e7657871](https://linux-hardware.org/?probe=26e7657871) | Jul 23, 2023 |
| MSI           | Z87 MPOWER                  | [dcbda0f556](https://linux-hardware.org/?probe=dcbda0f556) | Jul 23, 2023 |
| Medion        | H110H4-EM2                  | [443b61cb44](https://linux-hardware.org/?probe=443b61cb44) | Jul 22, 2023 |
| ASUSTek       | PRIME B550M-A AC            | [1a39665e1c](https://linux-hardware.org/?probe=1a39665e1c) | Jul 22, 2023 |
| Intel         | DQ57TM AAE70931-402         | [01621f8578](https://linux-hardware.org/?probe=01621f8578) | Jul 21, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | [620c7f4aec](https://linux-hardware.org/?probe=620c7f4aec) | Jul 21, 2023 |
| Dell          | 0D881F A05                  | [26695664a7](https://linux-hardware.org/?probe=26695664a7) | Jul 18, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [164e93a53b](https://linux-hardware.org/?probe=164e93a53b) | Jul 16, 2023 |
| Lenovo        | MAHOBAY                     | [ded2ed05d8](https://linux-hardware.org/?probe=ded2ed05d8) | Jul 15, 2023 |
| Unknown       | Unknown                     | [3caf271d7c](https://linux-hardware.org/?probe=3caf271d7c) | Jul 15, 2023 |
| Unknown       | Unknown                     | [689d391a1d](https://linux-hardware.org/?probe=689d391a1d) | Jul 15, 2023 |
| ASRock        | B85M Pro4                   | [8e53be597f](https://linux-hardware.org/?probe=8e53be597f) | Jul 13, 2023 |
| ASRock        | B85M Pro4                   | [dcb1a242c5](https://linux-hardware.org/?probe=dcb1a242c5) | Jul 13, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [b5374c8055](https://linux-hardware.org/?probe=b5374c8055) | Jul 12, 2023 |
| ASUSTek       | Q87M-E                      | [0d59e226ae](https://linux-hardware.org/?probe=0d59e226ae) | Jul 10, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [17c907528f](https://linux-hardware.org/?probe=17c907528f) | Jul 09, 2023 |
| ASUSTek       | M5A97 R2.0                  | [7c39787112](https://linux-hardware.org/?probe=7c39787112) | Jul 08, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | [b1f7c9aea2](https://linux-hardware.org/?probe=b1f7c9aea2) | Jul 06, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [6b250aabab](https://linux-hardware.org/?probe=6b250aabab) | Jul 05, 2023 |
| Lenovo        | ThinkCentre A70 7844H9G     | [46bfb7c0ff](https://linux-hardware.org/?probe=46bfb7c0ff) | Jul 05, 2023 |
| Gigabyte      | Z87-D3HP-CF                 | [7502eb638e](https://linux-hardware.org/?probe=7502eb638e) | Jul 04, 2023 |
| Dell          | 0D881F A05                  | [947d2ff164](https://linux-hardware.org/?probe=947d2ff164) | Jul 03, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [b5a7ef8997](https://linux-hardware.org/?probe=b5a7ef8997) | Jul 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | [1c976fee39](https://linux-hardware.org/?probe=1c976fee39) | Jul 01, 2023 |
| ASUSTek       | P8Z77-V LE                  | [802b3686d4](https://linux-hardware.org/?probe=802b3686d4) | Jun 28, 2023 |
| MSI           | H81M-P33                    | [1726bb80ec](https://linux-hardware.org/?probe=1726bb80ec) | Jun 27, 2023 |
| Positivo      | POS-PIH81DI                 | [42e304c777](https://linux-hardware.org/?probe=42e304c777) | Jun 26, 2023 |
| Positivo      | POS-PIH81DI                 | [77d2d3d01b](https://linux-hardware.org/?probe=77d2d3d01b) | Jun 26, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [3dffeb35fa](https://linux-hardware.org/?probe=3dffeb35fa) | Jun 20, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | [260297ab72](https://linux-hardware.org/?probe=260297ab72) | Jun 19, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [587c48c954](https://linux-hardware.org/?probe=587c48c954) | Jun 17, 2023 |
| Gigabyte      | C246-WU4-CF                 | [8babb9b5f1](https://linux-hardware.org/?probe=8babb9b5f1) | Jun 13, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [7f974cd282](https://linux-hardware.org/?probe=7f974cd282) | Jun 12, 2023 |
| Lenovo        | 312A SDK0R32862 WIN 3258... | [1e8ab337a5](https://linux-hardware.org/?probe=1e8ab337a5) | Jun 11, 2023 |
| Supermicro    | C7H61                       | [7eef5b7873](https://linux-hardware.org/?probe=7eef5b7873) | Jun 08, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [610c9c318f](https://linux-hardware.org/?probe=610c9c318f) | Jun 08, 2023 |
| MSI           | 2AE0                        | [15b3c478d3](https://linux-hardware.org/?probe=15b3c478d3) | Jun 06, 2023 |
| ASRock        | A320M-HDV R4.0              | [5e9fd3f392](https://linux-hardware.org/?probe=5e9fd3f392) | Jun 05, 2023 |
| Biostar       | B350GT3                     | [b425f8d45a](https://linux-hardware.org/?probe=b425f8d45a) | Jun 05, 2023 |
| Biostar       | A10N-8800E                  | [906dbab25c](https://linux-hardware.org/?probe=906dbab25c) | Jun 01, 2023 |
| Gigabyte      | AX370-Gaming K7             | [7baed02e0e](https://linux-hardware.org/?probe=7baed02e0e) | Jun 01, 2023 |
| ASRock        | H170M Pro4                  | [d936c663d3](https://linux-hardware.org/?probe=d936c663d3) | Jun 01, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [0586d2c0e2](https://linux-hardware.org/?probe=0586d2c0e2) | Jun 01, 2023 |
| ASUSTek       | PRIME A320M-K               | [ebd7782079](https://linux-hardware.org/?probe=ebd7782079) | May 31, 2023 |
| ASUSTek       | P5Q                         | [e936e44332](https://linux-hardware.org/?probe=e936e44332) | May 31, 2023 |
| ASUSTek       | Z97-DELUXE                  | [2723d218b7](https://linux-hardware.org/?probe=2723d218b7) | May 31, 2023 |
| ASUSTek       | P9X79                       | [c677ff5b2d](https://linux-hardware.org/?probe=c677ff5b2d) | May 31, 2023 |
| AZW           | GTR V02                     | [bd1740c7b2](https://linux-hardware.org/?probe=bd1740c7b2) | May 31, 2023 |
| AZW           | GTR V02                     | [cab90f1838](https://linux-hardware.org/?probe=cab90f1838) | May 31, 2023 |
| ASRock        | AB350M Pro4                 | [4f23de2827](https://linux-hardware.org/?probe=4f23de2827) | May 30, 2023 |
| ASUSTek       | P7P55-M                     | [a8fd95ce79](https://linux-hardware.org/?probe=a8fd95ce79) | May 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [1c62418caf](https://linux-hardware.org/?probe=1c62418caf) | May 25, 2023 |
| Acer          | Aspire M3920                | [5e61c22a26](https://linux-hardware.org/?probe=5e61c22a26) | May 24, 2023 |
| ASUSTek       | PRIME B350M-A               | [174a3139c4](https://linux-hardware.org/?probe=174a3139c4) | May 24, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [9568d26302](https://linux-hardware.org/?probe=9568d26302) | May 24, 2023 |
| ASUSTek       | Z170-PRO                    | [27819563b9](https://linux-hardware.org/?probe=27819563b9) | May 23, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | [7f3dae82d3](https://linux-hardware.org/?probe=7f3dae82d3) | May 23, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [434372d228](https://linux-hardware.org/?probe=434372d228) | May 21, 2023 |
| Gigabyte      | A320M-H-CF                  | [1c178d1658](https://linux-hardware.org/?probe=1c178d1658) | May 21, 2023 |
| MSI           | X370 GAMING PLUS            | [610c8c1a42](https://linux-hardware.org/?probe=610c8c1a42) | May 19, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | [1e7af790ed](https://linux-hardware.org/?probe=1e7af790ed) | May 19, 2023 |
| Gigabyte      | B365M DS3H                  | [28b96d7d6a](https://linux-hardware.org/?probe=28b96d7d6a) | May 17, 2023 |
| Gigabyte      | A320M-H-CF                  | [c8250719d9](https://linux-hardware.org/?probe=c8250719d9) | May 16, 2023 |
| ASUSTek       | F1A75-V PRO                 | [9ee8a0ca50](https://linux-hardware.org/?probe=9ee8a0ca50) | May 14, 2023 |
| ASUSTek       | PRIME X570-PRO              | [0701f94970](https://linux-hardware.org/?probe=0701f94970) | May 13, 2023 |
| Dell          | 0WR7PY A02                  | [9448d89bb6](https://linux-hardware.org/?probe=9448d89bb6) | May 12, 2023 |
| Gigabyte      | B75M-D3H                    | [e360693145](https://linux-hardware.org/?probe=e360693145) | May 11, 2023 |
| Acer          | Aspire M3920                | [aed14c1e20](https://linux-hardware.org/?probe=aed14c1e20) | May 07, 2023 |
| ASUSTek       | M5A97 PLUS                  | [a062cb2ab6](https://linux-hardware.org/?probe=a062cb2ab6) | May 07, 2023 |
| ASRock        | FM2A88X Extreme6+           | [00a1158a86](https://linux-hardware.org/?probe=00a1158a86) | May 04, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | [ae1618c708](https://linux-hardware.org/?probe=ae1618c708) | May 03, 2023 |
| ASUSTek       | M5A99X EVO                  | [63015eecb0](https://linux-hardware.org/?probe=63015eecb0) | May 03, 2023 |
| MSI           | B450I GAMING PLUS AC        | [36574d4502](https://linux-hardware.org/?probe=36574d4502) | May 03, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [2da8ff7129](https://linux-hardware.org/?probe=2da8ff7129) | May 03, 2023 |
| Gigabyte      | AX370-Gaming K7             | [ee8e81add2](https://linux-hardware.org/?probe=ee8e81add2) | May 01, 2023 |
| Intel         | H81                         | [c70b10516b](https://linux-hardware.org/?probe=c70b10516b) | Apr 30, 2023 |
| Gigabyte      | B365M DS3H                  | [7feb43607e](https://linux-hardware.org/?probe=7feb43607e) | Apr 27, 2023 |
| MSI           | 970 GAMING                  | [44c5943019](https://linux-hardware.org/?probe=44c5943019) | Apr 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [812906148b](https://linux-hardware.org/?probe=812906148b) | Apr 27, 2023 |
| Alienware     | Aurora R15 AMD              | [f2e22848d1](https://linux-hardware.org/?probe=f2e22848d1) | Apr 25, 2023 |
| MSI           | FM2-A75MA-E35               | [011f691ce1](https://linux-hardware.org/?probe=011f691ce1) | Apr 25, 2023 |
| Gigabyte      | EX58-UD5                    | [3d8d7c49f8](https://linux-hardware.org/?probe=3d8d7c49f8) | Apr 24, 2023 |
| Gigabyte      | EX58-UD5                    | [e9a3b8f1d1](https://linux-hardware.org/?probe=e9a3b8f1d1) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c4a5aad8a1](https://linux-hardware.org/?probe=c4a5aad8a1) | Apr 22, 2023 |
| HP            | 82F2 A01                    | [fbcf679bae](https://linux-hardware.org/?probe=fbcf679bae) | Apr 21, 2023 |
| Supermicro    | C7H61                       | [f5e17f37d4](https://linux-hardware.org/?probe=f5e17f37d4) | Apr 21, 2023 |
| ASUSTek       | Z170-PRO                    | [970c4dfa6f](https://linux-hardware.org/?probe=970c4dfa6f) | Apr 20, 2023 |
| Supermicro    | C7H61                       | [d975325f4b](https://linux-hardware.org/?probe=d975325f4b) | Apr 20, 2023 |
| Dell          | 0D881F A05                  | [7aef52516b](https://linux-hardware.org/?probe=7aef52516b) | Apr 16, 2023 |
| ASRock        | Z170 Extreme4               | [d21971f30f](https://linux-hardware.org/?probe=d21971f30f) | Apr 13, 2023 |
| ASUSTek       | Z97-A                       | [139f5f3aca](https://linux-hardware.org/?probe=139f5f3aca) | Apr 12, 2023 |
| Dell          | 0RW199                      | [8c41f4ff91](https://linux-hardware.org/?probe=8c41f4ff91) | Apr 11, 2023 |
| Dell          | 0F373D A00                  | [e42bdc9769](https://linux-hardware.org/?probe=e42bdc9769) | Apr 09, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | [8187fc54a3](https://linux-hardware.org/?probe=8187fc54a3) | Apr 07, 2023 |
| Gigabyte      | M61SME-S2                   | [25d436d2cb](https://linux-hardware.org/?probe=25d436d2cb) | Apr 06, 2023 |
| HP            | 0A9Ch                       | [178046626f](https://linux-hardware.org/?probe=178046626f) | Apr 05, 2023 |
| Gigabyte      | 970-GAMING                  | [6ec3c125d5](https://linux-hardware.org/?probe=6ec3c125d5) | Apr 05, 2023 |
| ASUSTek       | Z97-K                       | [32f708c916](https://linux-hardware.org/?probe=32f708c916) | Apr 05, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [7eeea6ba29](https://linux-hardware.org/?probe=7eeea6ba29) | Apr 04, 2023 |
| ASUSTek       | Z97-K                       | [6e750dfaa5](https://linux-hardware.org/?probe=6e750dfaa5) | Apr 04, 2023 |
| Alienware     | 0VDT73 A00                  | [ed92305da6](https://linux-hardware.org/?probe=ed92305da6) | Apr 04, 2023 |
| Gigabyte      | B460M AORUS PRO             | [72dc18dacb](https://linux-hardware.org/?probe=72dc18dacb) | Apr 03, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | [f8e61fd850](https://linux-hardware.org/?probe=f8e61fd850) | Apr 03, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [35c3ae13c5](https://linux-hardware.org/?probe=35c3ae13c5) | Apr 02, 2023 |
| Gigabyte      | B460M AORUS PRO             | [12647b9601](https://linux-hardware.org/?probe=12647b9601) | Apr 02, 2023 |
| Gigabyte      | EX58-UD5                    | [0fbed59931](https://linux-hardware.org/?probe=0fbed59931) | Apr 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | [bc77efa103](https://linux-hardware.org/?probe=bc77efa103) | Apr 01, 2023 |
| MSI           | MAG A520M VECTOR WIFI       | [3c08cf9aba](https://linux-hardware.org/?probe=3c08cf9aba) | Apr 01, 2023 |
| ASUSTek       | EB1036                      | [955d389e06](https://linux-hardware.org/?probe=955d389e06) | Mar 30, 2023 |
| Dell          | 0200DY A01                  | [722b28547b](https://linux-hardware.org/?probe=722b28547b) | Mar 28, 2023 |
| MSI           | B85-G43                     | [3dac8c76c2](https://linux-hardware.org/?probe=3dac8c76c2) | Mar 28, 2023 |
| Lenovo        | SHARKBAY SDK0J40709 WIN ... | [22e3e1831c](https://linux-hardware.org/?probe=22e3e1831c) | Mar 28, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [6553d2c85a](https://linux-hardware.org/?probe=6553d2c85a) | Mar 26, 2023 |
| ASUSTek       | PRIME Z590-A                | [9a8b9b917f](https://linux-hardware.org/?probe=9a8b9b917f) | Mar 24, 2023 |
| ASUSTek       | P8Z77-V LE                  | [c50deee021](https://linux-hardware.org/?probe=c50deee021) | Mar 24, 2023 |
| Lenovo        | SHARKBAY NOK                | [84f93bfcf1](https://linux-hardware.org/?probe=84f93bfcf1) | Mar 23, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [d9c0447b0d](https://linux-hardware.org/?probe=d9c0447b0d) | Mar 21, 2023 |
| HP            | 21F5                        | [865a85e5bc](https://linux-hardware.org/?probe=865a85e5bc) | Mar 20, 2023 |
| Intel         | DH67BL AAG10189-208         | [420f476f82](https://linux-hardware.org/?probe=420f476f82) | Mar 19, 2023 |
| Gigabyte      | B450 AORUS M                | [efaf7d4a30](https://linux-hardware.org/?probe=efaf7d4a30) | Mar 18, 2023 |
| Acer          | Aspire XC600 v1.0           | [ef3e267972](https://linux-hardware.org/?probe=ef3e267972) | Mar 18, 2023 |
| HP            | 8266                        | [8bac7f79e8](https://linux-hardware.org/?probe=8bac7f79e8) | Mar 17, 2023 |
| ASUSTek       | H81M-K                      | [9ca1015389](https://linux-hardware.org/?probe=9ca1015389) | Mar 16, 2023 |
| ASUSTek       | PRIME H510M-D               | [d1edfbc4b3](https://linux-hardware.org/?probe=d1edfbc4b3) | Mar 16, 2023 |
| Acer          | Aspire M3920                | [bb2e9ec8a1](https://linux-hardware.org/?probe=bb2e9ec8a1) | Mar 16, 2023 |
| Supermicro    | X9DRD-C/iT+                 | [57c78aa4db](https://linux-hardware.org/?probe=57c78aa4db) | Mar 15, 2023 |
| ASUSTek       | PRIME Z590-P                | [f424a1dc42](https://linux-hardware.org/?probe=f424a1dc42) | Mar 14, 2023 |
| ASUSTek       | H61M-K                      | [783ff991d4](https://linux-hardware.org/?probe=783ff991d4) | Mar 14, 2023 |
| MSI           | B85-G43                     | [7e9ce07cb8](https://linux-hardware.org/?probe=7e9ce07cb8) | Mar 13, 2023 |
| MSI           | B85-G43                     | [9a9a70ade3](https://linux-hardware.org/?probe=9a9a70ade3) | Mar 13, 2023 |
| Gigabyte      | B560M DS3H V2               | [77b7a9348b](https://linux-hardware.org/?probe=77b7a9348b) | Mar 12, 2023 |
| MSI           | MAG B660M BAZOOKA DDR4      | [cb1be19cd3](https://linux-hardware.org/?probe=cb1be19cd3) | Mar 11, 2023 |
| MSI           | B85-G43                     | [47ac638c2e](https://linux-hardware.org/?probe=47ac638c2e) | Mar 11, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [d039d459d7](https://linux-hardware.org/?probe=d039d459d7) | Mar 10, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [fdc9f52c81](https://linux-hardware.org/?probe=fdc9f52c81) | Mar 08, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [7bd6e95116](https://linux-hardware.org/?probe=7bd6e95116) | Mar 08, 2023 |
| Gigabyte      | B365M DS3H                  | [22569ee1f4](https://linux-hardware.org/?probe=22569ee1f4) | Mar 07, 2023 |
| Gigabyte      | EX58-UD5                    | [8805f0bce5](https://linux-hardware.org/?probe=8805f0bce5) | Mar 05, 2023 |
| Gigabyte      | B365M DS3H                  | [7d43df02db](https://linux-hardware.org/?probe=7d43df02db) | Mar 04, 2023 |
| ASUSTek       | P9X79                       | [9a3c215b30](https://linux-hardware.org/?probe=9a3c215b30) | Mar 03, 2023 |
| Gigabyte      | H410M H V3                  | [fdee05953f](https://linux-hardware.org/?probe=fdee05953f) | Mar 03, 2023 |
| ASRock        | B550M Steel Legend          | [8fd450db03](https://linux-hardware.org/?probe=8fd450db03) | Feb 28, 2023 |
| ASUSTek       | PRIME B450M-K               | [575e6a8c55](https://linux-hardware.org/?probe=575e6a8c55) | Feb 26, 2023 |
| ASRock        | H97 Pro4                    | [f703af2e6b](https://linux-hardware.org/?probe=f703af2e6b) | Feb 25, 2023 |
| ASRock        | M3A770DE                    | [b025c7a092](https://linux-hardware.org/?probe=b025c7a092) | Feb 24, 2023 |
| Gigabyte      | B365M DS3H                  | [463265c999](https://linux-hardware.org/?probe=463265c999) | Feb 24, 2023 |
| Gigabyte      | B365M DS3H                  | [4aec81f692](https://linux-hardware.org/?probe=4aec81f692) | Feb 24, 2023 |
| MSI           | B85-G43                     | [62273631b2](https://linux-hardware.org/?probe=62273631b2) | Feb 21, 2023 |
| ASRock        | 960GC-GS FX                 | [39718b8983](https://linux-hardware.org/?probe=39718b8983) | Feb 20, 2023 |
| Gigabyte      | X99-Ultra Gaming-CF         | [031c13ea35](https://linux-hardware.org/?probe=031c13ea35) | Feb 19, 2023 |
| ASUSTek       | H97-PLUS                    | [6824ee9944](https://linux-hardware.org/?probe=6824ee9944) | Feb 19, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [25c9923614](https://linux-hardware.org/?probe=25c9923614) | Feb 18, 2023 |
| ASRock        | B550M Steel Legend          | [b3c5c043ea](https://linux-hardware.org/?probe=b3c5c043ea) | Feb 18, 2023 |
| ASRock        | B550M Steel Legend          | [1c1470c8a2](https://linux-hardware.org/?probe=1c1470c8a2) | Feb 18, 2023 |
| MSI           | MAG B560 TOMAHAWK WIFI      | [6538791548](https://linux-hardware.org/?probe=6538791548) | Feb 17, 2023 |
| MSI           | MAG B560 TOMAHAWK WIFI      | [2da59271fe](https://linux-hardware.org/?probe=2da59271fe) | Feb 17, 2023 |
| Dell          | 0DF42J A00                  | [e192547cd3](https://linux-hardware.org/?probe=e192547cd3) | Feb 17, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [695abe8c65](https://linux-hardware.org/?probe=695abe8c65) | Feb 14, 2023 |
| ASUSTek       | Z10PE-D16 WS                | [d517411fc5](https://linux-hardware.org/?probe=d517411fc5) | Feb 13, 2023 |
| Gigabyte      | B560 HD3                    | [067646f7f8](https://linux-hardware.org/?probe=067646f7f8) | Feb 12, 2023 |
| HP            | 3397                        | [cc5cdaf09b](https://linux-hardware.org/?probe=cc5cdaf09b) | Feb 12, 2023 |
| ASUSTek       | Z10PE-D16 WS                | [b2c120d8d7](https://linux-hardware.org/?probe=b2c120d8d7) | Feb 11, 2023 |
| ASUSTek       | Z10PE-D16 WS                | [a19717f948](https://linux-hardware.org/?probe=a19717f948) | Feb 10, 2023 |
| Gigabyte      | B560 HD3                    | [b4fa86401f](https://linux-hardware.org/?probe=b4fa86401f) | Feb 09, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [ee5a11ee81](https://linux-hardware.org/?probe=ee5a11ee81) | Feb 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [5df3b5ad7e](https://linux-hardware.org/?probe=5df3b5ad7e) | Feb 08, 2023 |
| ASUSTek       | PRIME Z490-P                | [be25e0c930](https://linux-hardware.org/?probe=be25e0c930) | Feb 07, 2023 |
| ASUSTek       | PRIME Z490-P                | [d139473252](https://linux-hardware.org/?probe=d139473252) | Feb 07, 2023 |
| Dell          | 0WR7PY A02                  | [7dcb345b45](https://linux-hardware.org/?probe=7dcb345b45) | Feb 06, 2023 |
| Dell          | 0WR7PY A02                  | [8c3dd4055e](https://linux-hardware.org/?probe=8c3dd4055e) | Feb 06, 2023 |
| ASRock        | X300M-STX                   | [c614e44344](https://linux-hardware.org/?probe=c614e44344) | Feb 05, 2023 |
| ASRock        | X300M-STX                   | [ad59fdb4e4](https://linux-hardware.org/?probe=ad59fdb4e4) | Feb 05, 2023 |
| Lenovo        | NO DPK                      | [0abc762f30](https://linux-hardware.org/?probe=0abc762f30) | Jan 28, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [1a9e67408e](https://linux-hardware.org/?probe=1a9e67408e) | Jan 28, 2023 |
| ASUSTek       | PRIME H510M-E               | [fa464af5fb](https://linux-hardware.org/?probe=fa464af5fb) | Jan 27, 2023 |
| HP            | 3397                        | [764f737fcf](https://linux-hardware.org/?probe=764f737fcf) | Jan 27, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [b7dea81a92](https://linux-hardware.org/?probe=b7dea81a92) | Jan 25, 2023 |
| ASRock        | B450M Pro4                  | [6462d71b74](https://linux-hardware.org/?probe=6462d71b74) | Jan 25, 2023 |
| Gigabyte      | X570S AORUS MASTER          | [a6f80e64b2](https://linux-hardware.org/?probe=a6f80e64b2) | Jan 21, 2023 |
| Gigabyte      | B365M DS3H                  | [29d770594e](https://linux-hardware.org/?probe=29d770594e) | Jan 21, 2023 |
| Dell          | 0WR7PY A02                  | [0072a47bce](https://linux-hardware.org/?probe=0072a47bce) | Jan 20, 2023 |
| ASUSTek       | P8Z68-V LX                  | [49f0bb23ea](https://linux-hardware.org/?probe=49f0bb23ea) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [2b7ce5b726](https://linux-hardware.org/?probe=2b7ce5b726) | Jan 20, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [3dfd98d007](https://linux-hardware.org/?probe=3dfd98d007) | Jan 17, 2023 |
| Dell          | 0D881F A05                  | [0426ee9130](https://linux-hardware.org/?probe=0426ee9130) | Jan 17, 2023 |
| ASUSTek       | H110M-K                     | [dcbf101b59](https://linux-hardware.org/?probe=dcbf101b59) | Jan 17, 2023 |
| ASUSTek       | H110M-K                     | [3964c82d71](https://linux-hardware.org/?probe=3964c82d71) | Jan 17, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [86039b3063](https://linux-hardware.org/?probe=86039b3063) | Jan 15, 2023 |
| ASRock        | A320M-HDV R4.0              | [aa35c556bc](https://linux-hardware.org/?probe=aa35c556bc) | Jan 13, 2023 |
| ASUSTek       | Z97-P                       | [709045636c](https://linux-hardware.org/?probe=709045636c) | Jan 13, 2023 |
| ASUSTek       | G10AJ                       | [e300c19806](https://linux-hardware.org/?probe=e300c19806) | Jan 13, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | [1a619ff898](https://linux-hardware.org/?probe=1a619ff898) | Jan 10, 2023 |
| ASUSTek       | PRIME B450M-A II            | [c7a6fdbf55](https://linux-hardware.org/?probe=c7a6fdbf55) | Jan 06, 2023 |
| MSI           | MEG Z490 UNIFY              | [cb25b352e0](https://linux-hardware.org/?probe=cb25b352e0) | Jan 06, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | [e4f0b0506b](https://linux-hardware.org/?probe=e4f0b0506b) | Jan 06, 2023 |
| ASRock        | A320M-HDV R4.0              | [78ab02a131](https://linux-hardware.org/?probe=78ab02a131) | Jan 05, 2023 |
| Dell          | 0WPMFG A00                  | [02a8ab8bdc](https://linux-hardware.org/?probe=02a8ab8bdc) | Jan 05, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | [efb1372825](https://linux-hardware.org/?probe=efb1372825) | Jan 05, 2023 |
| Dell          | 096JG8 A01                  | [1c58ea8841](https://linux-hardware.org/?probe=1c58ea8841) | Jan 05, 2023 |
| Dell          | 096JG8 A01                  | [90cbbe6b1d](https://linux-hardware.org/?probe=90cbbe6b1d) | Jan 04, 2023 |
| Dell          | 096JG8 A01                  | [2e047c3ad5](https://linux-hardware.org/?probe=2e047c3ad5) | Jan 04, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [54403a8bbf](https://linux-hardware.org/?probe=54403a8bbf) | Jan 02, 2023 |
| ASUSTek       | G10DK                       | [e75694d9a6](https://linux-hardware.org/?probe=e75694d9a6) | Jan 02, 2023 |
| Gigabyte      | Z590 UD AC                  | [9346b2e1bc](https://linux-hardware.org/?probe=9346b2e1bc) | Jan 01, 2023 |
| Dell          | 0PTTT9 A00                  | [7f2851fcf5](https://linux-hardware.org/?probe=7f2851fcf5) | Dec 31, 2022 |
| HP            | 8399                        | [204c8c0a3f](https://linux-hardware.org/?probe=204c8c0a3f) | Dec 29, 2022 |
| Acer          | Aspire X3960                | [f045d61192](https://linux-hardware.org/?probe=f045d61192) | Dec 29, 2022 |
| Acer          | Aspire X3960                | [75e053c90f](https://linux-hardware.org/?probe=75e053c90f) | Dec 29, 2022 |
| Dell          | 0KWVT8 A03                  | [9d2542cf36](https://linux-hardware.org/?probe=9d2542cf36) | Dec 27, 2022 |
| Dell          | 0KWVT8 A03                  | [f2998cdede](https://linux-hardware.org/?probe=f2998cdede) | Dec 27, 2022 |
| Gigabyte      | 970-GAMING                  | [4a2d0b56d6](https://linux-hardware.org/?probe=4a2d0b56d6) | Dec 27, 2022 |
| Gigabyte      | 970-GAMING                  | [9df04c213d](https://linux-hardware.org/?probe=9df04c213d) | Dec 26, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [8d9b11c617](https://linux-hardware.org/?probe=8d9b11c617) | Dec 25, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [d66772a936](https://linux-hardware.org/?probe=d66772a936) | Dec 25, 2022 |
| Gigabyte      | 970-GAMING                  | [ef0c06d132](https://linux-hardware.org/?probe=ef0c06d132) | Dec 25, 2022 |
| Gigabyte      | 970-GAMING                  | [9de3d146ff](https://linux-hardware.org/?probe=9de3d146ff) | Dec 25, 2022 |
| ASUSTek       | X99-DELUXE                  | [3d538213fc](https://linux-hardware.org/?probe=3d538213fc) | Dec 25, 2022 |
| BESSTAR Te... | HM90                        | [3672c73d5a](https://linux-hardware.org/?probe=3672c73d5a) | Dec 24, 2022 |
| ASRock        | X570 Steel Legend           | [7b79249b18](https://linux-hardware.org/?probe=7b79249b18) | Dec 23, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [841b610817](https://linux-hardware.org/?probe=841b610817) | Dec 23, 2022 |
| Gigabyte      | Z97M-DS3H                   | [dca79c9d6d](https://linux-hardware.org/?probe=dca79c9d6d) | Dec 21, 2022 |
| MSI           | X470 GAMING PLUS            | [44cdfa03bf](https://linux-hardware.org/?probe=44cdfa03bf) | Dec 19, 2022 |
| MSI           | B450M PRO-VDH MAX           | [d5d8eaf2b9](https://linux-hardware.org/?probe=d5d8eaf2b9) | Dec 19, 2022 |
| Dell          | 084J0R A00                  | [dabf78159d](https://linux-hardware.org/?probe=dabf78159d) | Dec 15, 2022 |
| Lenovo        | NOK                         | [01d1b7fdb7](https://linux-hardware.org/?probe=01d1b7fdb7) | Dec 15, 2022 |
| MSI           | A320M PRO-VD/S              | [9e9573c0c5](https://linux-hardware.org/?probe=9e9573c0c5) | Dec 14, 2022 |
| Lenovo        | ThinkCentre A70 7844H9G     | [aad5a91184](https://linux-hardware.org/?probe=aad5a91184) | Dec 14, 2022 |
| MSI           | A320M PRO-VD/S              | [c428800285](https://linux-hardware.org/?probe=c428800285) | Dec 14, 2022 |
| ASUSTek       | H170-PRO                    | [0a28fbd557](https://linux-hardware.org/?probe=0a28fbd557) | Dec 12, 2022 |
| Gigabyte      | B550M DS3H                  | [13434876df](https://linux-hardware.org/?probe=13434876df) | Dec 11, 2022 |
| ASRock        | B450M Pro4                  | [36ef5b0deb](https://linux-hardware.org/?probe=36ef5b0deb) | Dec 04, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [23f903a61d](https://linux-hardware.org/?probe=23f903a61d) | Dec 03, 2022 |
| Dell          | 084J0R A00                  | [57b5a73c5d](https://linux-hardware.org/?probe=57b5a73c5d) | Dec 01, 2022 |
| System76      | Thelio thelio-r1            | [76343aa234](https://linux-hardware.org/?probe=76343aa234) | Dec 01, 2022 |
| ASRock        | B75M-DGS                    | [ca277bb16c](https://linux-hardware.org/?probe=ca277bb16c) | Nov 30, 2022 |
| MSI           | Z370 GAMING PLUS            | [bd1c91dba9](https://linux-hardware.org/?probe=bd1c91dba9) | Nov 30, 2022 |
| ASRock        | A320M-HDV R4.0              | [3a64631617](https://linux-hardware.org/?probe=3a64631617) | Nov 30, 2022 |
| ASRock        | A320M-HDV R4.0              | [12492cb99a](https://linux-hardware.org/?probe=12492cb99a) | Nov 29, 2022 |
| Gigabyte      | H97-HD3                     | [7c2db201dc](https://linux-hardware.org/?probe=7c2db201dc) | Nov 24, 2022 |
| MSI           | B350 PC MATE                | [601fd47da1](https://linux-hardware.org/?probe=601fd47da1) | Nov 24, 2022 |
| Gigabyte      | H110M-S2H-CF                | [87c95f019e](https://linux-hardware.org/?probe=87c95f019e) | Nov 20, 2022 |
| Unknown       | Unknown                     | [554da2ef73](https://linux-hardware.org/?probe=554da2ef73) | Nov 18, 2022 |
| ASUSTek       | PRIME H510M-D               | [3491c5eef1](https://linux-hardware.org/?probe=3491c5eef1) | Nov 17, 2022 |
| ASRock        | B560M-ITX/ac                | [c8f725f9cd](https://linux-hardware.org/?probe=c8f725f9cd) | Nov 17, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | [8e4ab9c969](https://linux-hardware.org/?probe=8e4ab9c969) | Nov 16, 2022 |
| Gigabyte      | H97-HD3                     | [b99ae215e4](https://linux-hardware.org/?probe=b99ae215e4) | Nov 14, 2022 |
| Gigabyte      | BOLD E3032                  | [9d013ae9aa](https://linux-hardware.org/?probe=9d013ae9aa) | Nov 14, 2022 |
| Gigabyte      | B660M GAMING DDR4           | [d22c86a486](https://linux-hardware.org/?probe=d22c86a486) | Nov 14, 2022 |
| Gigabyte      | GA-MA790FX-DS5              | [63bba2efec](https://linux-hardware.org/?probe=63bba2efec) | Nov 14, 2022 |
| Supermicro    | X9DAL                       | [56d4bd9f26](https://linux-hardware.org/?probe=56d4bd9f26) | Nov 13, 2022 |
| Foxconn       | 2ADA                        | [4ddae3c3a0](https://linux-hardware.org/?probe=4ddae3c3a0) | Nov 13, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [733739e049](https://linux-hardware.org/?probe=733739e049) | Nov 12, 2022 |
| Dell          | 0HY9JP A00                  | [fed46e3161](https://linux-hardware.org/?probe=fed46e3161) | Nov 12, 2022 |
| ASRock        | B75M                        | [7da4910326](https://linux-hardware.org/?probe=7da4910326) | Nov 12, 2022 |
| ASRock        | X99 Extreme4                | [00da120cde](https://linux-hardware.org/?probe=00da120cde) | Nov 11, 2022 |
| Dell          | 0773VG A00                  | [2ffe6c18f7](https://linux-hardware.org/?probe=2ffe6c18f7) | Nov 10, 2022 |
| Gigabyte      | B660M D3H DDR4              | [64aed4564c](https://linux-hardware.org/?probe=64aed4564c) | Nov 07, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [8ef47e1adb](https://linux-hardware.org/?probe=8ef47e1adb) | Nov 06, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [40a3de202d](https://linux-hardware.org/?probe=40a3de202d) | Nov 03, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [db852ba394](https://linux-hardware.org/?probe=db852ba394) | Nov 03, 2022 |
| ASUSTek       | M5A78L-M LX V2              | [50bd7a7436](https://linux-hardware.org/?probe=50bd7a7436) | Nov 01, 2022 |
| Shuttle       | FH61R                       | [26f86947ef](https://linux-hardware.org/?probe=26f86947ef) | Oct 30, 2022 |
| ASRock        | H61M-VS                     | [9a48b2a679](https://linux-hardware.org/?probe=9a48b2a679) | Oct 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [ac3b0eaf36](https://linux-hardware.org/?probe=ac3b0eaf36) | Oct 28, 2022 |
| HP            | 844C                        | [7e994c50c9](https://linux-hardware.org/?probe=7e994c50c9) | Oct 27, 2022 |
| ASUSTek       | M5A78L-M LE                 | [6954f669c5](https://linux-hardware.org/?probe=6954f669c5) | Oct 27, 2022 |
| ASUSTek       | PRIME X570-P                | [7910e04e13](https://linux-hardware.org/?probe=7910e04e13) | Oct 25, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [bd3a8063b3](https://linux-hardware.org/?probe=bd3a8063b3) | Oct 25, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [285e8cd1a5](https://linux-hardware.org/?probe=285e8cd1a5) | Oct 25, 2022 |
| Gigabyte      | B365M D2V                   | [c852b8f3f7](https://linux-hardware.org/?probe=c852b8f3f7) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [638c72b105](https://linux-hardware.org/?probe=638c72b105) | Oct 24, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | [ca0e86eb6b](https://linux-hardware.org/?probe=ca0e86eb6b) | Oct 22, 2022 |
| MSI           | A320M PRO-M2 V2             | [7524f39579](https://linux-hardware.org/?probe=7524f39579) | Oct 19, 2022 |
| MSI           | H110M PRO-D                 | [d0580b46f2](https://linux-hardware.org/?probe=d0580b46f2) | Oct 18, 2022 |
| Lenovo        | ThinkCentre A70 7844H9G     | [1b0e52eddb](https://linux-hardware.org/?probe=1b0e52eddb) | Oct 18, 2022 |
| JWIPC         | A320I S1                    | [44689a88d8](https://linux-hardware.org/?probe=44689a88d8) | Oct 16, 2022 |
| Gigabyte      | Z68XP-UD3                   | [b36220c65b](https://linux-hardware.org/?probe=b36220c65b) | Oct 13, 2022 |
| ASRock        | A320M-HDV R4.0              | [20eebb7b05](https://linux-hardware.org/?probe=20eebb7b05) | Oct 12, 2022 |
| Gigabyte      | P55-US3L                    | [59843156e8](https://linux-hardware.org/?probe=59843156e8) | Oct 11, 2022 |
| ASRock        | Z170 Extreme4               | [b88e8a8b49](https://linux-hardware.org/?probe=b88e8a8b49) | Oct 11, 2022 |
| Gigabyte      | Z370P D3-CF                 | [71c916389e](https://linux-hardware.org/?probe=71c916389e) | Oct 09, 2022 |
| Acer          | Aspire G7750                | [bd21d9c12b](https://linux-hardware.org/?probe=bd21d9c12b) | Oct 09, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | [691aa10e89](https://linux-hardware.org/?probe=691aa10e89) | Oct 09, 2022 |
| Apple         | Mac-F221BEC8                | [51442982cd](https://linux-hardware.org/?probe=51442982cd) | Oct 07, 2022 |
| ASUSTek       | PRIME B450M-K II            | [1bf20fe68c](https://linux-hardware.org/?probe=1bf20fe68c) | Oct 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [99ed468a82](https://linux-hardware.org/?probe=99ed468a82) | Oct 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [e8b8141f03](https://linux-hardware.org/?probe=e8b8141f03) | Oct 05, 2022 |
| Dell          | 042P49 A02                  | [1ba8422c66](https://linux-hardware.org/?probe=1ba8422c66) | Oct 04, 2022 |
| MSI           | B450I GAMING PLUS AC        | [e857a28ed2](https://linux-hardware.org/?probe=e857a28ed2) | Oct 04, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [bc03e42377](https://linux-hardware.org/?probe=bc03e42377) | Oct 03, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | [61d1e2102b](https://linux-hardware.org/?probe=61d1e2102b) | Oct 03, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | [f05b832b90](https://linux-hardware.org/?probe=f05b832b90) | Oct 01, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | [d638b38369](https://linux-hardware.org/?probe=d638b38369) | Sep 30, 2022 |
| Dell          | 0GY6Y8 A02                  | [dad71b5547](https://linux-hardware.org/?probe=dad71b5547) | Sep 28, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [19fe9ebfb6](https://linux-hardware.org/?probe=19fe9ebfb6) | Sep 27, 2022 |
| ASRock        | 990FX Extreme9              | [c7522b70ba](https://linux-hardware.org/?probe=c7522b70ba) | Sep 27, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [3e14df6c26](https://linux-hardware.org/?probe=3e14df6c26) | Sep 27, 2022 |
| Gigabyte      | X399 AORUS XTREME-CF        | [762ad6e460](https://linux-hardware.org/?probe=762ad6e460) | Sep 26, 2022 |
| MSI           | Z590-A PRO                  | [72bd6750e5](https://linux-hardware.org/?probe=72bd6750e5) | Sep 25, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [60635ca9bc](https://linux-hardware.org/?probe=60635ca9bc) | Sep 24, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [2a7c09d404](https://linux-hardware.org/?probe=2a7c09d404) | Sep 24, 2022 |
| Gigabyte      | X570 GAMING X               | [07f9a5063e](https://linux-hardware.org/?probe=07f9a5063e) | Sep 23, 2022 |
| Biostar       | TA75MH2                     | [e76fb13311](https://linux-hardware.org/?probe=e76fb13311) | Sep 23, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [384ab44e0a](https://linux-hardware.org/?probe=384ab44e0a) | Sep 23, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [24c7d626c8](https://linux-hardware.org/?probe=24c7d626c8) | Sep 23, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [f6e7ad269e](https://linux-hardware.org/?probe=f6e7ad269e) | Sep 22, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [256ff04106](https://linux-hardware.org/?probe=256ff04106) | Sep 20, 2022 |
| MSI           | Z390-A PRO                  | [9b0dd73d61](https://linux-hardware.org/?probe=9b0dd73d61) | Sep 20, 2022 |
| Supermicro    | SKAGIT09                    | [b7dcf8a06c](https://linux-hardware.org/?probe=b7dcf8a06c) | Sep 20, 2022 |
| Acer          | Aspire G7750                | [c54e28dc84](https://linux-hardware.org/?probe=c54e28dc84) | Sep 18, 2022 |
| Gigabyte      | B560M D3H                   | [515d75e6b7](https://linux-hardware.org/?probe=515d75e6b7) | Sep 17, 2022 |
| ASUSTek       | Z97-K                       | [3f362093da](https://linux-hardware.org/?probe=3f362093da) | Sep 16, 2022 |
| Gigabyte      | B450M DS3H-CF               | [ea2264656c](https://linux-hardware.org/?probe=ea2264656c) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [d79d03b7ef](https://linux-hardware.org/?probe=d79d03b7ef) | Sep 11, 2022 |
| ASRock        | H470M-HVS                   | [17e4855f90](https://linux-hardware.org/?probe=17e4855f90) | Sep 09, 2022 |
| Supermicro    | SKAGIT09                    | [d3f42d0c24](https://linux-hardware.org/?probe=d3f42d0c24) | Sep 08, 2022 |
| Gigabyte      | B450M DS3H-CF               | [557860ffbd](https://linux-hardware.org/?probe=557860ffbd) | Sep 07, 2022 |
| MSI           | B350 PC MATE                | [1f4f30c013](https://linux-hardware.org/?probe=1f4f30c013) | Sep 06, 2022 |
| MSI           | B450-A PRO MAX              | [0c89daf254](https://linux-hardware.org/?probe=0c89daf254) | Sep 03, 2022 |
| ASRock        | A320M-HDV                   | [5a9342d8e9](https://linux-hardware.org/?probe=5a9342d8e9) | Sep 03, 2022 |
| Dell          | 02YYK5 A00                  | [742579c33d](https://linux-hardware.org/?probe=742579c33d) | Sep 03, 2022 |
| OEM           | G41 775 ICH7 8712           | [4c9041cf15](https://linux-hardware.org/?probe=4c9041cf15) | Sep 03, 2022 |
| MSI           | 970 GAMING                  | [296c04b276](https://linux-hardware.org/?probe=296c04b276) | Sep 02, 2022 |
| MSI           | MAG B550M BAZOOKA           | [a1b5555512](https://linux-hardware.org/?probe=a1b5555512) | Sep 02, 2022 |
| Gigabyte      | B85M-HD3                    | [dcb5e7a20c](https://linux-hardware.org/?probe=dcb5e7a20c) | Aug 29, 2022 |
| Supermicro    | SKAGIT09                    | [3f4c6a4d48](https://linux-hardware.org/?probe=3f4c6a4d48) | Aug 29, 2022 |
| Pegatron      | 2AB6                        | [93af020634](https://linux-hardware.org/?probe=93af020634) | Aug 27, 2022 |
| ASRock        | B450M/ac R2.0               | [ede2f61f08](https://linux-hardware.org/?probe=ede2f61f08) | Aug 26, 2022 |
| MSI           | B450-A PRO                  | [36f10ad555](https://linux-hardware.org/?probe=36f10ad555) | Aug 24, 2022 |
| ASUSTek       | B85-PLUS                    | [1eba4b558d](https://linux-hardware.org/?probe=1eba4b558d) | Aug 23, 2022 |
| Gigabyte      | BOLD E3032                  | [4b70fe47a2](https://linux-hardware.org/?probe=4b70fe47a2) | Aug 23, 2022 |
| Gigabyte      | H410M S2 V2                 | [cb43b7a4cf](https://linux-hardware.org/?probe=cb43b7a4cf) | Aug 22, 2022 |
| Gigabyte      | H97-Gaming 3                | [c084ff3123](https://linux-hardware.org/?probe=c084ff3123) | Aug 22, 2022 |
| Supermicro    | SKAGIT09                    | [1ae2767db3](https://linux-hardware.org/?probe=1ae2767db3) | Aug 22, 2022 |
| MSI           | B350 PC MATE                | [e058dec94d](https://linux-hardware.org/?probe=e058dec94d) | Aug 19, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [dd98185972](https://linux-hardware.org/?probe=dd98185972) | Aug 16, 2022 |
| ASUSTek       | H170M-PLUS/BR               | [feb4e50ec5](https://linux-hardware.org/?probe=feb4e50ec5) | Aug 16, 2022 |
| Lenovo        | Bantry CRB SDK0J40700 WI... | [792eb4143f](https://linux-hardware.org/?probe=792eb4143f) | Aug 16, 2022 |
| MSI           | B350 PC MATE                | [646d091037](https://linux-hardware.org/?probe=646d091037) | Aug 15, 2022 |
| HP            | 805D                        | [54f4e0fdb0](https://linux-hardware.org/?probe=54f4e0fdb0) | Aug 14, 2022 |
| Dell          | 0C2XKD A01                  | [cfad241ca0](https://linux-hardware.org/?probe=cfad241ca0) | Aug 12, 2022 |
| Positivo      | POS-PARS760GCD POSITIVO     | [dc6e65929f](https://linux-hardware.org/?probe=dc6e65929f) | Aug 12, 2022 |
| HP            | 8459                        | [677ca01f4f](https://linux-hardware.org/?probe=677ca01f4f) | Aug 11, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [d2f7a86fd8](https://linux-hardware.org/?probe=d2f7a86fd8) | Aug 11, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [6eac3041ec](https://linux-hardware.org/?probe=6eac3041ec) | Aug 07, 2022 |
| MSI           | B550-A PRO                  | [fb01882d07](https://linux-hardware.org/?probe=fb01882d07) | Aug 06, 2022 |
| MSI           | Z97 GAMING 7                | [01cf6a0897](https://linux-hardware.org/?probe=01cf6a0897) | Aug 06, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [1340311493](https://linux-hardware.org/?probe=1340311493) | Aug 06, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [6fa2b142e4](https://linux-hardware.org/?probe=6fa2b142e4) | Aug 06, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [e5e72c1264](https://linux-hardware.org/?probe=e5e72c1264) | Aug 05, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [d725206bff](https://linux-hardware.org/?probe=d725206bff) | Aug 04, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [42469385bc](https://linux-hardware.org/?probe=42469385bc) | Aug 04, 2022 |
| ASUSTek       | P8H67                       | [b1b842e547](https://linux-hardware.org/?probe=b1b842e547) | Jul 29, 2022 |
| ASUSTek       | GRYPHON Z87                 | [73b9d340d2](https://linux-hardware.org/?probe=73b9d340d2) | Jul 28, 2022 |
| ASUSTek       | PRIME X370-PRO              | [ee8688ecdb](https://linux-hardware.org/?probe=ee8688ecdb) | Jul 26, 2022 |
| ASRock        | Z270 Gaming K4              | [63612e20b4](https://linux-hardware.org/?probe=63612e20b4) | Jul 26, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [5658129aa4](https://linux-hardware.org/?probe=5658129aa4) | Jul 24, 2022 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [ba1841221c](https://linux-hardware.org/?probe=ba1841221c) | Jul 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [021e469888](https://linux-hardware.org/?probe=021e469888) | Jul 23, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [ea90d78c53](https://linux-hardware.org/?probe=ea90d78c53) | Jul 23, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [6e6e65c711](https://linux-hardware.org/?probe=6e6e65c711) | Jul 23, 2022 |
| Gigabyte      | P35-DS3L                    | [4ae76fafc9](https://linux-hardware.org/?probe=4ae76fafc9) | Jul 22, 2022 |
| Shuttle       | NC01U V1.0                  | [827d6c81ae](https://linux-hardware.org/?probe=827d6c81ae) | Jul 22, 2022 |
| Shuttle       | NC01U V1.0                  | [fecfaf6008](https://linux-hardware.org/?probe=fecfaf6008) | Jul 21, 2022 |
| HP            | 18E9                        | [f15b2671b0](https://linux-hardware.org/?probe=f15b2671b0) | Jul 21, 2022 |
| ASRock        | B550 Extreme4               | [226924706f](https://linux-hardware.org/?probe=226924706f) | Jul 20, 2022 |
| Gigabyte      | P35-DS3L                    | [cabd591648](https://linux-hardware.org/?probe=cabd591648) | Jul 20, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | [0e3950303c](https://linux-hardware.org/?probe=0e3950303c) | Jul 18, 2022 |
| ASRock        | Z170 Extreme4               | [4f4b63a026](https://linux-hardware.org/?probe=4f4b63a026) | Jul 18, 2022 |
| Acer          | Predator PO3-620            | [f3e22c0e6d](https://linux-hardware.org/?probe=f3e22c0e6d) | Jul 18, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [01d595926f](https://linux-hardware.org/?probe=01d595926f) | Jul 15, 2022 |
| MSI           | X99A XPOWER GAMING TITAN... | [e764729eeb](https://linux-hardware.org/?probe=e764729eeb) | Jul 13, 2022 |
| ASRock        | Z170 Extreme4               | [7ecf3ad1b7](https://linux-hardware.org/?probe=7ecf3ad1b7) | Jul 13, 2022 |
| ASRock        | B550 Extreme4               | [6106db3d9a](https://linux-hardware.org/?probe=6106db3d9a) | Jul 12, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | [fafb6deae6](https://linux-hardware.org/?probe=fafb6deae6) | Jul 12, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | [d6531258d0](https://linux-hardware.org/?probe=d6531258d0) | Jul 11, 2022 |
| ASRock        | B550 Taichi                 | [61fe809791](https://linux-hardware.org/?probe=61fe809791) | Jul 10, 2022 |
| Gigabyte      | Z77-D3H                     | [f9e15346d3](https://linux-hardware.org/?probe=f9e15346d3) | Jul 10, 2022 |
| ASUSTek       | P9X79 PRO                   | [d7e1136386](https://linux-hardware.org/?probe=d7e1136386) | Jul 07, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | [7d5d5c1a7e](https://linux-hardware.org/?probe=7d5d5c1a7e) | Jul 02, 2022 |
| HP            | 8459                        | [f43fdff127](https://linux-hardware.org/?probe=f43fdff127) | Jul 01, 2022 |
| ASUSTek       | ET2400A                     | [8801791f80](https://linux-hardware.org/?probe=8801791f80) | Jul 01, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [33c8a42a4d](https://linux-hardware.org/?probe=33c8a42a4d) | Jun 29, 2022 |
| Gigabyte      | X570 AORUS PRO              | [757741fe0d](https://linux-hardware.org/?probe=757741fe0d) | Jun 29, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [efb8cff806](https://linux-hardware.org/?probe=efb8cff806) | Jun 28, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [a6555d107c](https://linux-hardware.org/?probe=a6555d107c) | Jun 27, 2022 |
| ASRock        | A320M Pro4                  | [e1918d8aab](https://linux-hardware.org/?probe=e1918d8aab) | Jun 25, 2022 |
| Huanan        | X99-F8 GAMING V5.0          | [2688876fc9](https://linux-hardware.org/?probe=2688876fc9) | Jun 25, 2022 |
| ASRock        | A320M Pro4                  | [f4f2e68e79](https://linux-hardware.org/?probe=f4f2e68e79) | Jun 24, 2022 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [04e6f0ee4a](https://linux-hardware.org/?probe=04e6f0ee4a) | Jun 24, 2022 |
| ABIT          | IP35 Pro                    | [a5f262c233](https://linux-hardware.org/?probe=a5f262c233) | Jun 23, 2022 |
| ASUSTek       | P8P67 LE                    | [8e1bc37281](https://linux-hardware.org/?probe=8e1bc37281) | Jun 19, 2022 |
| ASRock        | X570M Pro4                  | [bbb784f2df](https://linux-hardware.org/?probe=bbb784f2df) | Jun 18, 2022 |
| Dell          | 0YNVJG A01                  | [b75bebfda2](https://linux-hardware.org/?probe=b75bebfda2) | Jun 18, 2022 |
| ASUSTek       | X99-A/USB                   | [3ad17f6d78](https://linux-hardware.org/?probe=3ad17f6d78) | Jun 16, 2022 |
| ASUSTek       | P5QC                        | [b9a53514e1](https://linux-hardware.org/?probe=b9a53514e1) | Jun 16, 2022 |
| MSI           | Z270 GAMING M5              | [d5f742022e](https://linux-hardware.org/?probe=d5f742022e) | Jun 16, 2022 |
| MSI           | Z270 GAMING M5              | [6c352cf792](https://linux-hardware.org/?probe=6c352cf792) | Jun 16, 2022 |
| Gigabyte      | B450M DS3H-CF               | [2b307211cd](https://linux-hardware.org/?probe=2b307211cd) | Jun 14, 2022 |
| Dell          | 0KC9NP A01                  | [c573376df6](https://linux-hardware.org/?probe=c573376df6) | Jun 11, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [317ae1383a](https://linux-hardware.org/?probe=317ae1383a) | Jun 10, 2022 |
| ASRock        | X570M Pro4                  | [4f6d06171b](https://linux-hardware.org/?probe=4f6d06171b) | Jun 10, 2022 |
| AZW           | Gemini J45                  | [f4d7238f95](https://linux-hardware.org/?probe=f4d7238f95) | Jun 08, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [15f48b1e64](https://linux-hardware.org/?probe=15f48b1e64) | Jun 08, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [9bc79127f3](https://linux-hardware.org/?probe=9bc79127f3) | Jun 06, 2022 |
| Dell          | 0Y2MRG A00                  | [11bba01e79](https://linux-hardware.org/?probe=11bba01e79) | Jun 06, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | [70f49afd95](https://linux-hardware.org/?probe=70f49afd95) | Jun 04, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [95173b9d90](https://linux-hardware.org/?probe=95173b9d90) | Jun 04, 2022 |
| ASUSTek       | M5A78L LE                   | [8eda28a8d4](https://linux-hardware.org/?probe=8eda28a8d4) | May 30, 2022 |
| ASUSTek       | P7H55-M LE                  | [4f55b87c44](https://linux-hardware.org/?probe=4f55b87c44) | May 28, 2022 |
| Gigabyte      | B85M-D2V                    | [2bc6293c6a](https://linux-hardware.org/?probe=2bc6293c6a) | May 19, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [93b08c2d75](https://linux-hardware.org/?probe=93b08c2d75) | May 19, 2022 |
| ASRock        | B560M Pro4                  | [ba3b29db98](https://linux-hardware.org/?probe=ba3b29db98) | May 18, 2022 |
| Gigabyte      | B85M-D2V                    | [da9da96cda](https://linux-hardware.org/?probe=da9da96cda) | May 17, 2022 |
| ASUSTek       | M5A78L LE                   | [697a89162e](https://linux-hardware.org/?probe=697a89162e) | May 16, 2022 |
| Dell          | 0KJCC5 A00                  | [bb68e24835](https://linux-hardware.org/?probe=bb68e24835) | May 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [0ec606b729](https://linux-hardware.org/?probe=0ec606b729) | May 14, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [6fdf1cd28c](https://linux-hardware.org/?probe=6fdf1cd28c) | May 14, 2022 |
| MSI           | B450M PRO-M2                | [0bb720a248](https://linux-hardware.org/?probe=0bb720a248) | May 14, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [fb2a9c9ddf](https://linux-hardware.org/?probe=fb2a9c9ddf) | May 13, 2022 |
| MSI           | B450M MORTAR TITANIUM       | [b03899e10b](https://linux-hardware.org/?probe=b03899e10b) | May 13, 2022 |
| Lenovo        | SHARKBAY NOK                | [7923c29010](https://linux-hardware.org/?probe=7923c29010) | May 11, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | [76cc09b228](https://linux-hardware.org/?probe=76cc09b228) | May 10, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | [6500cb78c3](https://linux-hardware.org/?probe=6500cb78c3) | May 10, 2022 |
| HP            | 1998                        | [7f82a04d73](https://linux-hardware.org/?probe=7f82a04d73) | May 10, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [5f90cb38d2](https://linux-hardware.org/?probe=5f90cb38d2) | May 07, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [0b27354c9c](https://linux-hardware.org/?probe=0b27354c9c) | May 05, 2022 |
| Gigabyte      | Z370P D3-CF                 | [8a561e2442](https://linux-hardware.org/?probe=8a561e2442) | May 05, 2022 |
| Gigabyte      | X570 GAMING X               | [53a75b2d5c](https://linux-hardware.org/?probe=53a75b2d5c) | May 04, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [62f9f79f7c](https://linux-hardware.org/?probe=62f9f79f7c) | May 03, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [afce1937fe](https://linux-hardware.org/?probe=afce1937fe) | May 03, 2022 |
| ASUSTek       | P8B75-M                     | [dadde1bbc0](https://linux-hardware.org/?probe=dadde1bbc0) | May 02, 2022 |
| Supermicro    | X8ST3                       | [a94462f4b5](https://linux-hardware.org/?probe=a94462f4b5) | May 02, 2022 |
| ASUSTek       | PRIME B550M-K               | [92c09fc927](https://linux-hardware.org/?probe=92c09fc927) | Apr 30, 2022 |
| ASRock        | B550 Extreme4               | [7a90a198f5](https://linux-hardware.org/?probe=7a90a198f5) | Apr 30, 2022 |
| ASUSTek       | M5A78L LE                   | [9328531b5a](https://linux-hardware.org/?probe=9328531b5a) | Apr 30, 2022 |
| Lenovo        | 36C5 SDK0J40700 WIN 3258... | [d9ac32b17d](https://linux-hardware.org/?probe=d9ac32b17d) | Apr 30, 2022 |
| Biostar       | A68N-2100K                  | [db9760ae3a](https://linux-hardware.org/?probe=db9760ae3a) | Apr 27, 2022 |
| Biostar       | A68N-2100K                  | [87d629883f](https://linux-hardware.org/?probe=87d629883f) | Apr 27, 2022 |
| HP            | 0AACh                       | [f9e511945d](https://linux-hardware.org/?probe=f9e511945d) | Apr 25, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [4b41ff5fb9](https://linux-hardware.org/?probe=4b41ff5fb9) | Apr 24, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [3d513e3c6c](https://linux-hardware.org/?probe=3d513e3c6c) | Mar 24, 2022 |
| Dell          | 0K240Y A02                  | [b5783c7fa0](https://linux-hardware.org/?probe=b5783c7fa0) | Mar 03, 2022 |
| Gigabyte      | H410M S2H V3                | [e5da146c8e](https://linux-hardware.org/?probe=e5da146c8e) | Feb 27, 2022 |
| Gigabyte      | B550M DS3H                  | [21a8a676d1](https://linux-hardware.org/?probe=21a8a676d1) | Dec 28, 2021 |
| Gigabyte      | B550M DS3H                  | [61561f50ba](https://linux-hardware.org/?probe=61561f50ba) | Dec 28, 2021 |
| Gigabyte      | P35-DS3L                    | [e13fea24e4](https://linux-hardware.org/?probe=e13fea24e4) | Dec 27, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [1c12810a81](https://linux-hardware.org/?probe=1c12810a81) | Dec 06, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [acadafa3aa](https://linux-hardware.org/?probe=acadafa3aa) | Nov 30, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Kubuntu_22.04/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.15.0-56-generic    | 22       | 4.88%   |
| 5.15.0-52-generic    | 19       | 4.21%   |
| 5.15.0-43-generic    | 19       | 4.21%   |
| 5.15.0-48-generic    | 14       | 3.1%    |
| 5.15.0-67-generic    | 13       | 2.88%   |
| 5.15.0-46-generic    | 13       | 2.88%   |
| 5.19.0-35-generic    | 12       | 2.66%   |
| 5.15.0-47-generic    | 12       | 2.66%   |
| 5.15.0-27-generic    | 12       | 2.66%   |
| 5.15.0-58-generic    | 11       | 2.44%   |
| 5.15.0-40-generic    | 11       | 2.44%   |
| 5.15.0-41-generic    | 10       | 2.22%   |
| 6.2.0-26-generic     | 9        | 2%      |
| 5.19.0-38-generic    | 9        | 2%      |
| 5.15.0-75-generic    | 9        | 2%      |
| 5.15.0-69-generic    | 9        | 2%      |
| 5.15.0-53-generic    | 9        | 2%      |
| 5.15.0-25-generic    | 9        | 2%      |
| 5.15.0-78-generic    | 8        | 1.77%   |
| 5.15.0-73-generic    | 8        | 1.77%   |
| 5.15.0-60-generic    | 8        | 1.77%   |
| 5.19.0-46-generic    | 7        | 1.55%   |
| 5.19.0-41-generic    | 7        | 1.55%   |
| 5.15.0-79-generic    | 7        | 1.55%   |
| 5.15.0-50-generic    | 7        | 1.55%   |
| 6.2.0-35-generic     | 6        | 1.33%   |
| 5.15.0-86-generic    | 6        | 1.33%   |
| 5.15.0-72-generic    | 6        | 1.33%   |
| 5.15.0-71-generic    | 6        | 1.33%   |
| 5.15.0-30-generic    | 6        | 1.33%   |
| 6.2.0-32-generic     | 5        | 1.11%   |
| 5.19.0-42-generic    | 5        | 1.11%   |
| 5.15.0-48-lowlatency | 5        | 1.11%   |
| 5.19.0-43-generic    | 4        | 0.89%   |
| 5.15.0-87-generic    | 4        | 0.89%   |
| 5.15.0-84-generic    | 4        | 0.89%   |
| 5.15.0-83-generic    | 4        | 0.89%   |
| 5.15.0-76-generic    | 4        | 0.89%   |
| 5.15.0-56-lowlatency | 4        | 0.89%   |
| 5.15.0-37-generic    | 4        | 0.89%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 298      | 72.15%  |
| 5.19.0  | 53       | 12.83%  |
| 6.2.0   | 31       | 7.51%   |
| 5.17.0  | 4        | 0.97%   |
| 6.1.5   | 2        | 0.48%   |
| 5.18.4  | 2        | 0.48%   |
| 5.13.0  | 2        | 0.48%   |
| 6.5.5   | 1        | 0.24%   |
| 6.5.3   | 1        | 0.24%   |
| 6.5.10  | 1        | 0.24%   |
| 6.5.0   | 1        | 0.24%   |
| 6.4.10  | 1        | 0.24%   |
| 6.4.0   | 1        | 0.24%   |
| 6.3.8   | 1        | 0.24%   |
| 6.3.6   | 1        | 0.24%   |
| 6.1.58  | 1        | 0.24%   |
| 6.1.1   | 1        | 0.24%   |
| 6.0.1   | 1        | 0.24%   |
| 6.0.0   | 1        | 0.24%   |
| 5.4.0   | 1        | 0.24%   |
| 5.19.12 | 1        | 0.24%   |
| 5.18.19 | 1        | 0.24%   |
| 5.18.12 | 1        | 0.24%   |
| 5.18.10 | 1        | 0.24%   |
| 5.17.6  | 1        | 0.24%   |
| 5.17.14 | 1        | 0.24%   |
| 5.16.0  | 1        | 0.24%   |
| 5.15.13 | 1        | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 299      | 72.4%   |
| 5.19    | 54       | 13.08%  |
| 6.2     | 31       | 7.51%   |
| 5.17    | 6        | 1.45%   |
| 5.18    | 5        | 1.21%   |
| 6.5     | 4        | 0.97%   |
| 6.1     | 4        | 0.97%   |
| 6.4     | 2        | 0.48%   |
| 6.3     | 2        | 0.48%   |
| 6.0     | 2        | 0.48%   |
| 5.13    | 2        | 0.48%   |
| 5.4     | 1        | 0.24%   |
| 5.16    | 1        | 0.24%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 401      | 99.75%  |
| riscv64 | 1        | 0.25%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| KDE5   | 397      | 98.76%  |
| KDE    | 2        | 0.5%    |
| GNOME  | 2        | 0.5%    |
| Budgie | 1        | 0.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 383      | 95.27%  |
| Tty     | 10       | 2.49%   |
| Wayland | 8        | 1.99%   |
| Web     | 1        | 0.25%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 277      | 68.23%  |
| Unknown | 92       | 22.66%  |
| GDM3    | 26       | 6.4%    |
| LightDM | 10       | 2.46%   |
| GDM     | 1        | 0.25%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang                 | Desktops | Percent |
|----------------------|----------|---------|
| en_US                | 179      | 44.53%  |
| de_DE                | 37       | 9.2%    |
| fr_FR                | 28       | 6.97%   |
| ru_RU                | 20       | 4.98%   |
| it_IT                | 20       | 4.98%   |
| en_GB                | 19       | 4.73%   |
| pt_BR                | 13       | 3.23%   |
| en_AU                | 12       | 2.99%   |
| pl_PL                | 7        | 1.74%   |
| es_ES                | 7        | 1.74%   |
| nl_NL                | 6        | 1.49%   |
| en_CA                | 5        | 1.24%   |
| es_AR                | 4        | 1%      |
| en_PH                | 3        | 0.75%   |
| de_CH                | 3        | 0.75%   |
| C                    | 3        | 0.75%   |
| fi_FI                | 2        | 0.5%    |
| es_CO                | 2        | 0.5%    |
| en_ZA                | 2        | 0.5%    |
| en_NZ                | 2        | 0.5%    |
| en_IN                | 2        | 0.5%    |
| en_AG                | 2        | 0.5%    |
| el_GR                | 2        | 0.5%    |
| cs_CZ                | 2        | 0.5%    |
| الافتراضيّ | 1        | 0.25%   |
| zh_CN                | 1        | 0.25%   |
| sl_SI                | 1        | 0.25%   |
| pt_PT                | 1        | 0.25%   |
| osa_US               | 1        | 0.25%   |
| nl_BE                | 1        | 0.25%   |
| fr_CA                | 1        | 0.25%   |
| fr_BE                | 1        | 0.25%   |
| es_VE                | 1        | 0.25%   |
| es_PE                | 1        | 0.25%   |
| es_PA                | 1        | 0.25%   |
| en_US.ISO8859-1      | 1        | 0.25%   |
| en_IL                | 1        | 0.25%   |
| en_FI                | 1        | 0.25%   |
| en_DE                | 1        | 0.25%   |
| en_CH                | 1        | 0.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 230      | 56.93%  |
| EFI  | 174      | 43.07%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 344      | 84.52%  |
| Tmpfs   | 27       | 6.63%   |
| Btrfs   | 19       | 4.67%   |
| Overlay | 12       | 2.95%   |
| Xfs     | 4        | 0.98%   |
| Ext3    | 1        | 0.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 247      | 60.54%  |
| Unknown | 121      | 29.66%  |
| MBR     | 40       | 9.8%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 334      | 81.86%  |
| Yes       | 74       | 18.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 251      | 62.28%  |
| Yes       | 152      | 37.72%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 118      | 29.35%  |
| Gigabyte Technology                  | 73       | 18.16%  |
| MSI                                  | 57       | 14.18%  |
| ASRock                               | 38       | 9.45%   |
| Dell                                 | 25       | 6.22%   |
| Hewlett-Packard                      | 19       | 4.73%   |
| Lenovo                               | 17       | 4.23%   |
| Supermicro                           | 6        | 1.49%   |
| Acer                                 | 6        | 1.49%   |
| Fujitsu                              | 5        | 1.24%   |
| Unknown                              | 5        | 1.24%   |
| Intel                                | 4        | 1%      |
| Biostar                              | 4        | 1%      |
| AZW                                  | 3        | 0.75%   |
| Alienware                            | 3        | 0.75%   |
| Shuttle                              | 2        | 0.5%    |
| Positivo                             | 2        | 0.5%    |
| Apple                                | 2        | 0.5%    |
| SYWZ                                 | 1        | 0.25%   |
| Shenzhen Meigao Electronic Equipment | 1        | 0.25%   |
| Seeed Studio                         | 1        | 0.25%   |
| Pegatron                             | 1        | 0.25%   |
| OEM                                  | 1        | 0.25%   |
| Medion                               | 1        | 0.25%   |
| JWIPC                                | 1        | 0.25%   |
| Huanan                               | 1        | 0.25%   |
| Foxconn                              | 1        | 0.25%   |
| ECS                                  | 1        | 0.25%   |
| BESSTAR Tech                         | 1        | 0.25%   |
| ASRockRack                           | 1        | 0.25%   |
| ABIT                                 | 1        | 0.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUS All Series                | 17       | 4.23%   |
| ASUS ROG STRIX B550-F GAMING   | 6        | 1.49%   |
| MSI MS-7B79                    | 5        | 1.24%   |
| Unknown                        | 5        | 1.24%   |
| MSI MS-7B86                    | 3        | 0.75%   |
| Gigabyte B450M DS3H            | 3        | 0.75%   |
| Dell OptiPlex 7010             | 3        | 0.75%   |
| ASUS ROG STRIX X570-E GAMING   | 3        | 0.75%   |
| Supermicro SKAGIT09            | 2        | 0.5%    |
| MSI MS-7C95                    | 2        | 0.5%    |
| MSI MS-7C56                    | 2        | 0.5%    |
| MSI MS-7B84                    | 2        | 0.5%    |
| MSI MS-7B61                    | 2        | 0.5%    |
| MSI MS-7A40                    | 2        | 0.5%    |
| HP ProDesk 600 G1 SFF          | 2        | 0.5%    |
| HP EliteDesk 800 G1 SFF        | 2        | 0.5%    |
| HP Compaq Elite 8300 SFF       | 2        | 0.5%    |
| Gigabyte X570 GAMING X         | 2        | 0.5%    |
| Gigabyte B450 I AORUS PRO WIFI | 2        | 0.5%    |
| Gigabyte 970-GAMING            | 2        | 0.5%    |
| Dell OptiPlex 7040             | 2        | 0.5%    |
| Dell OptiPlex 7020             | 2        | 0.5%    |
| ASUS TUF X470-PLUS GAMING      | 2        | 0.5%    |
| ASUS TUF Gaming Z590-PLUS WIFI | 2        | 0.5%    |
| ASUS TUF Gaming B550M-PLUS     | 2        | 0.5%    |
| ASUS STRIX Z270E GAMING        | 2        | 0.5%    |
| ASUS ROG ZENITH EXTREME        | 2        | 0.5%    |
| ASUS ROG STRIX Z390-E GAMING   | 2        | 0.5%    |
| ASUS ROG STRIX B550-I GAMING   | 2        | 0.5%    |
| ASUS ROG CROSSHAIR VII HERO    | 2        | 0.5%    |
| ASUS PRIME X370-PRO            | 2        | 0.5%    |
| ASUS P9X79                     | 2        | 0.5%    |
| ASUS P8Z77-V LE                | 2        | 0.5%    |
| ASRock H61M-VS                 | 2        | 0.5%    |
| ASRock B450M Pro4              | 2        | 0.5%    |
| ASRock A320M-HDV R4.0          | 2        | 0.5%    |
| SYWZ S210H Series              | 1        | 0.25%   |
| Supermicro X9DAL               | 1        | 0.25%   |
| Supermicro X8ST3               | 1        | 0.25%   |
| Supermicro PIO-1UDP10-01-AI036 | 1        | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 23       | 5.72%   |
| ASUS ROG               | 22       | 5.47%   |
| ASUS All               | 17       | 4.23%   |
| Dell OptiPlex          | 14       | 3.48%   |
| ASUS TUF               | 14       | 3.48%   |
| Lenovo ThinkCentre     | 12       | 2.99%   |
| Gigabyte X570          | 6        | 1.49%   |
| MSI MS-7B79            | 5        | 1.24%   |
| HP ProDesk             | 5        | 1.24%   |
| Fujitsu ESPRIMO        | 5        | 1.24%   |
| Dell Precision         | 5        | 1.24%   |
| Acer Aspire            | 5        | 1.24%   |
| Unknown                | 5        | 1.24%   |
| Lenovo IdeaCentre      | 4        | 1%      |
| Gigabyte B450          | 4        | 1%      |
| Dell XPS               | 4        | 1%      |
| MSI MS-7B86            | 3        | 0.75%   |
| HP EliteDesk           | 3        | 0.75%   |
| HP Compaq              | 3        | 0.75%   |
| Gigabyte H410M         | 3        | 0.75%   |
| Gigabyte B450M         | 3        | 0.75%   |
| ASUS STRIX             | 3        | 0.75%   |
| ASUS P9X79             | 3        | 0.75%   |
| ASUS P8Z77-V           | 3        | 0.75%   |
| ASUS M5A78L-M          | 3        | 0.75%   |
| ASRock B450M           | 3        | 0.75%   |
| ASRock A320M-HDV       | 3        | 0.75%   |
| Alienware Aurora       | 3        | 0.75%   |
| Supermicro SKAGIT09    | 2        | 0.5%    |
| MSI MS-7C95            | 2        | 0.5%    |
| MSI MS-7C56            | 2        | 0.5%    |
| MSI MS-7B84            | 2        | 0.5%    |
| MSI MS-7B61            | 2        | 0.5%    |
| MSI MS-7A40            | 2        | 0.5%    |
| HP Pavilion            | 2        | 0.5%    |
| Gigabyte Z390          | 2        | 0.5%    |
| Gigabyte GA-78LMT-USB3 | 2        | 0.5%    |
| Gigabyte B660M         | 2        | 0.5%    |
| Gigabyte B560M         | 2        | 0.5%    |
| Gigabyte B550M         | 2        | 0.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 55       | 13.68%  |
| 2020 | 43       | 10.7%   |
| 2021 | 39       | 9.7%    |
| 2019 | 36       | 8.96%   |
| 2014 | 32       | 7.96%   |
| 2013 | 31       | 7.71%   |
| 2012 | 29       | 7.21%   |
| 2017 | 27       | 6.72%   |
| 2015 | 22       | 5.47%   |
| 2016 | 20       | 4.98%   |
| 2011 | 18       | 4.48%   |
| 2022 | 14       | 3.48%   |
| 2010 | 12       | 2.99%   |
| 2009 | 8        | 1.99%   |
| 2008 | 8        | 1.99%   |
| 2007 | 5        | 1.24%   |
| 2023 | 3        | 0.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 402      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 391      | 97.26%  |
| Enabled  | 11       | 2.74%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 402      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 120      | 29.63%  |
| 32.01-64.0      | 97       | 23.95%  |
| 8.01-16.0       | 64       | 15.8%   |
| 4.01-8.0        | 44       | 10.86%  |
| 64.01-256.0     | 40       | 9.88%   |
| 3.01-4.0        | 23       | 5.68%   |
| 24.01-32.0      | 15       | 3.7%    |
| More than 256.0 | 2        | 0.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 111      | 26.24%  |
| 2.01-3.0   | 111      | 26.24%  |
| 3.01-4.0   | 73       | 17.26%  |
| 1.01-2.0   | 73       | 17.26%  |
| 8.01-16.0  | 31       | 7.33%   |
| 16.01-24.0 | 11       | 2.6%    |
| 0.51-1.0   | 5        | 1.18%   |
| 24.01-32.0 | 4        | 0.95%   |
| 32.01-64.0 | 3        | 0.71%   |
| 0.01-0.5   | 1        | 0.24%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 126      | 30.88%  |
| 1      | 99       | 24.26%  |
| 3      | 80       | 19.61%  |
| 4      | 46       | 11.27%  |
| 5      | 27       | 6.62%   |
| 6      | 16       | 3.92%   |
| 7      | 9        | 2.21%   |
| 9      | 2        | 0.49%   |
| 8      | 2        | 0.49%   |
| 11     | 1        | 0.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 241      | 59.8%   |
| Yes       | 162      | 40.2%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 398      | 99%     |
| No        | 4        | 1%      |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 210      | 51.98%  |
| No        | 194      | 48.02%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 227      | 56.33%  |
| Yes       | 176      | 43.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 90       | 22.39%  |
| Germany      | 47       | 11.69%  |
| France       | 28       | 6.97%   |
| Italy        | 27       | 6.72%   |
| UK           | 22       | 5.47%   |
| Russia       | 22       | 5.47%   |
| Brazil       | 19       | 4.73%   |
| Netherlands  | 15       | 3.73%   |
| Poland       | 12       | 2.99%   |
| Australia    | 11       | 2.74%   |
| Spain        | 10       | 2.49%   |
| Canada       | 9        | 2.24%   |
| Finland      | 7        | 1.74%   |
| Switzerland  | 6        | 1.49%   |
| Bulgaria     | 5        | 1.24%   |
| Argentina    | 5        | 1.24%   |
| Slovenia     | 4        | 1%      |
| Portugal     | 4        | 1%      |
| Belgium      | 4        | 1%      |
| Philippines  | 3        | 0.75%   |
| New Zealand  | 3        | 0.75%   |
| India        | 3        | 0.75%   |
| Czechia      | 3        | 0.75%   |
| Austria      | 3        | 0.75%   |
| Thailand     | 2        | 0.5%    |
| Sweden       | 2        | 0.5%    |
| South Africa | 2        | 0.5%    |
| Serbia       | 2        | 0.5%    |
| Norway       | 2        | 0.5%    |
| Mexico       | 2        | 0.5%    |
| Iran         | 2        | 0.5%    |
| Greece       | 2        | 0.5%    |
| Vietnam      | 1        | 0.25%   |
| Venezuela    | 1        | 0.25%   |
| Ukraine      | 1        | 0.25%   |
| Turkey       | 1        | 0.25%   |
| Romania      | 1        | 0.25%   |
| Peru         | 1        | 0.25%   |
| Panama       | 1        | 0.25%   |
| Malta        | 1        | 0.25%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Moscow            | 6        | 1.45%   |
| Berlin            | 6        | 1.45%   |
| Munich            | 5        | 1.21%   |
| Rio de Janeiro    | 4        | 0.97%   |
| Montreal          | 4        | 0.97%   |
| Melbourne         | 4        | 0.97%   |
| London            | 4        | 0.97%   |
| Vladivostok       | 3        | 0.73%   |
| Sydney            | 3        | 0.73%   |
| Sao Paulo         | 3        | 0.73%   |
| Milan             | 3        | 0.73%   |
| Dallas            | 3        | 0.73%   |
| Wroclaw           | 2        | 0.48%   |
| Washington        | 2        | 0.48%   |
| Vienna            | 2        | 0.48%   |
| Varna             | 2        | 0.48%   |
| Turku             | 2        | 0.48%   |
| Strasbourg        | 2        | 0.48%   |
| Rome              | 2        | 0.48%   |
| Prague            | 2        | 0.48%   |
| Pittsburgh        | 2        | 0.48%   |
| New York          | 2        | 0.48%   |
| Ljubljana         | 2        | 0.48%   |
| Indianapolis      | 2        | 0.48%   |
| Helsinki          | 2        | 0.48%   |
| Hamburg           | 2        | 0.48%   |
| Grenoble          | 2        | 0.48%   |
| Frankfurt am Main | 2        | 0.48%   |
| Curitiba          | 2        | 0.48%   |
| Columbus          | 2        | 0.48%   |
| Caruaru           | 2        | 0.48%   |
| Canberra          | 2        | 0.48%   |
| Brasília         | 2        | 0.48%   |
| Bougival          | 2        | 0.48%   |
| Belgrade          | 2        | 0.48%   |
| Auckland          | 2        | 0.48%   |
| Amsterdam         | 2        | 0.48%   |
| Zurich            | 1        | 0.24%   |
| Zaandam           | 1        | 0.24%   |
| Yerevan           | 1        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 139      | 216    | 16.71%  |
| Samsung Electronics         | 139      | 255    | 16.71%  |
| Seagate                     | 131      | 240    | 15.75%  |
| Kingston                    | 53       | 68     | 6.37%   |
| Toshiba                     | 46       | 59     | 5.53%   |
| SanDisk                     | 41       | 59     | 4.93%   |
| Crucial                     | 40       | 47     | 4.81%   |
| Hitachi                     | 27       | 35     | 3.25%   |
| A-DATA Technology           | 21       | 24     | 2.52%   |
| Intel                       | 11       | 14     | 1.32%   |
| Unknown                     | 10       | 15     | 1.2%    |
| Phison                      | 10       | 10     | 1.2%    |
| China                       | 10       | 11     | 1.2%    |
| PNY                         | 9        | 19     | 1.08%   |
| Patriot                     | 9        | 12     | 1.08%   |
| HGST                        | 9        | 13     | 1.08%   |
| Phison Electronics          | 7        | 7      | 0.84%   |
| OCZ                         | 6        | 6      | 0.72%   |
| Maxtor                      | 6        | 8      | 0.72%   |
| SPCC                        | 5        | 5      | 0.6%    |
| Micron/Crucial Technology   | 5        | 6      | 0.6%    |
| Transcend                   | 4        | 5      | 0.48%   |
| Lexar                       | 4        | 4      | 0.48%   |
| KIOXIA                      | 4        | 4      | 0.48%   |
| Intenso                     | 4        | 6      | 0.48%   |
| Corsair                     | 4        | 6      | 0.48%   |
| T-FORCE                     | 3        | 3      | 0.36%   |
| SABRENT                     | 3        | 3      | 0.36%   |
| Realtek Semiconductor       | 3        | 3      | 0.36%   |
| Mushkin                     | 3        | 4      | 0.36%   |
| Micron Technology           | 3        | 3      | 0.36%   |
| Kingston Technology Company | 3        | 6      | 0.36%   |
| Apple                       | 3        | 3      | 0.36%   |
| XPG                         | 2        | 2      | 0.24%   |
| Verbatim                    | 2        | 2      | 0.24%   |
| Team                        | 2        | 2      | 0.24%   |
| Smartbuy                    | 2        | 2      | 0.24%   |
| SK hynix                    | 2        | 4      | 0.24%   |
| Silicon Motion              | 2        | 4      | 0.24%   |
| Plextor                     | 2        | 2      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                   | 14       | 1.42%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 11       | 1.11%   |
| Seagate ST4000DM004-2CV104 4TB                    | 10       | 1.01%   |
| Samsung SSD 850 EVO 500GB                         | 10       | 1.01%   |
| Toshiba DT01ACA100 1TB                            | 9        | 0.91%   |
| Samsung SSD 860 EVO 500GB                         | 9        | 0.91%   |
| Samsung SSD 860 EVO 1TB                           | 9        | 0.91%   |
| Seagate ST2000DM008-2FR102 2TB                    | 8        | 0.81%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 7        | 0.71%   |
| Kingston SA400S37480G 480GB SSD                   | 7        | 0.71%   |
| Seagate ST500DM002-1BD142 500GB                   | 6        | 0.61%   |
| Crucial CT240BX500SSD1 240GB                      | 6        | 0.61%   |
| Toshiba HDWD110 1TB                               | 5        | 0.51%   |
| Toshiba DT01ACA200 2TB                            | 5        | 0.51%   |
| SanDisk NVMe SSD Drive 500GB                      | 5        | 0.51%   |
| Samsung SSD 980 PRO 2TB                           | 5        | 0.51%   |
| Samsung SSD 870 QVO 1TB                           | 5        | 0.51%   |
| Samsung SSD 870 EVO 500GB                         | 5        | 0.51%   |
| Samsung SSD 850 EVO 250GB                         | 5        | 0.51%   |
| Samsung HD103SI 1TB                               | 5        | 0.51%   |
| Crucial CT1000MX500SSD1 1TB                       | 5        | 0.51%   |
| WDC WD40EZRZ-00GXCB0 4TB                          | 4        | 0.4%    |
| Seagate ST4000VN008-2DR166 4TB                    | 4        | 0.4%    |
| Seagate ST3500418AS 500GB                         | 4        | 0.4%    |
| Seagate ST31000524AS 1TB                          | 4        | 0.4%    |
| Seagate ST2000DM001-1ER164 2TB                    | 4        | 0.4%    |
| Seagate ST1000DM003-1ER162 1TB                    | 4        | 0.4%    |
| Seagate ST1000DM003-1CH162 1TB                    | 4        | 0.4%    |
| Seagate Expansion 1TB                             | 4        | 0.4%    |
| Samsung SSD 970 EVO Plus 1TB                      | 4        | 0.4%    |
| Samsung SSD 870 EVO 1TB                           | 4        | 0.4%    |
| Samsung SSD 860 EVO 250GB                         | 4        | 0.4%    |
| Samsung SSD 840 EVO 250GB                         | 4        | 0.4%    |
| Samsung NVMe SSD Drive 500GB                      | 4        | 0.4%    |
| Micron/Crucial P2 NVMe PCIe SSD 500GB             | 4        | 0.4%    |
| Kingston SA2000M81000G 1TB                        | 4        | 0.4%    |
| Crucial CT500MX500SSD1 500GB                      | 4        | 0.4%    |
| Crucial CT1000BX500SSD1 1TB                       | 4        | 0.4%    |
| WDC WDS120G2G0A-00JH30 120GB SSD                  | 3        | 0.3%    |
| WDC WD20EZRZ-00Z5HB0 2TB                          | 3        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 124      | 228    | 34.83%  |
| WDC                 | 121      | 175    | 33.99%  |
| Toshiba             | 41       | 52     | 11.52%  |
| Hitachi             | 27       | 35     | 7.58%   |
| Samsung Electronics | 22       | 32     | 6.18%   |
| HGST                | 9        | 13     | 2.53%   |
| Maxtor              | 5        | 7      | 1.4%    |
| Unknown             | 2        | 2      | 0.56%   |
| Apple               | 2        | 2      | 0.56%   |
| USB3.0              | 1        | 1      | 0.28%   |
| JMicron Technology  | 1        | 1      | 0.28%   |
| IET                 | 1        | 1      | 0.28%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 89       | 142    | 26.97%  |
| Kingston            | 43       | 51     | 13.03%  |
| Crucial             | 34       | 39     | 10.3%   |
| SanDisk             | 27       | 33     | 8.18%   |
| WDC                 | 21       | 32     | 6.36%   |
| A-DATA Technology   | 17       | 19     | 5.15%   |
| China               | 10       | 11     | 3.03%   |
| PNY                 | 9        | 19     | 2.73%   |
| Patriot             | 9        | 12     | 2.73%   |
| OCZ                 | 6        | 6      | 1.82%   |
| Intel               | 5        | 8      | 1.52%   |
| SPCC                | 4        | 4      | 1.21%   |
| Lexar               | 4        | 4      | 1.21%   |
| Transcend           | 3        | 3      | 0.91%   |
| Toshiba             | 3        | 3      | 0.91%   |
| SABRENT             | 3        | 3      | 0.91%   |
| Mushkin             | 3        | 4      | 0.91%   |
| Micron Technology   | 3        | 3      | 0.91%   |
| Intenso             | 3        | 3      | 0.91%   |
| Verbatim            | 2        | 2      | 0.61%   |
| Plextor             | 2        | 2      | 0.61%   |
| KODAK               | 2        | 2      | 0.61%   |
| KIOXIA-EXCERIA      | 2        | 4      | 0.61%   |
| Hewlett-Packard     | 2        | 2      | 0.61%   |
| GOODRAM             | 2        | 2      | 0.61%   |
| ValueTech           | 1        | 1      | 0.3%    |
| Teutons             | 1        | 1      | 0.3%    |
| Team                | 1        | 1      | 0.3%    |
| T-FORCE             | 1        | 1      | 0.3%    |
| Smartbuy            | 1        | 1      | 0.3%    |
| Seagate             | 1        | 1      | 0.3%    |
| OCZ-VERTEX3         | 1        | 1      | 0.3%    |
| Maxtor              | 1        | 1      | 0.3%    |
| LITEONIT            | 1        | 1      | 0.3%    |
| KingFast            | 1        | 1      | 0.3%    |
| Integral            | 1        | 1      | 0.3%    |
| INNOVATION IT       | 1        | 1      | 0.3%    |
| INDMEM              | 1        | 1      | 0.3%    |
| Emtec               | 1        | 1      | 0.3%    |
| Drevo               | 1        | 1      | 0.3%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 270      | 549    | 38.41%  |
| SSD     | 266      | 435    | 37.84%  |
| NVMe    | 148      | 232    | 21.05%  |
| Unknown | 16       | 24     | 2.28%   |
| MMC     | 3        | 3      | 0.43%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 369      | 945    | 66.25%  |
| NVMe | 146      | 228    | 26.21%  |
| SAS  | 39       | 67     | 7%      |
| MMC  | 3        | 3      | 0.54%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 259      | 451    | 42.88%  |
| 0.51-1.0   | 170      | 258    | 28.15%  |
| 1.01-2.0   | 77       | 119    | 12.75%  |
| 3.01-4.0   | 48       | 86     | 7.95%   |
| 4.01-10.0  | 27       | 39     | 4.47%   |
| 2.01-3.0   | 19       | 23     | 3.15%   |
| 10.01-20.0 | 4        | 8      | 0.66%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 80       | 19.42%  |
| 501-1000       | 72       | 17.48%  |
| 1001-2000      | 71       | 17.23%  |
| 251-500        | 64       | 15.53%  |
| 101-250        | 55       | 13.35%  |
| 2001-3000      | 51       | 12.38%  |
| 1-20           | 11       | 2.67%   |
| 51-100         | 6        | 1.46%   |
| Unknown        | 2        | 0.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 62       | 14.8%   |
| 251-500        | 60       | 14.32%  |
| 101-250        | 60       | 14.32%  |
| 1001-2000      | 48       | 11.46%  |
| 1-20           | 47       | 11.22%  |
| 51-100         | 47       | 11.22%  |
| More than 3000 | 37       | 8.83%   |
| 21-50          | 36       | 8.59%   |
| 2001-3000      | 20       | 4.77%   |
| Unknown        | 2        | 0.48%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB          | 3        | 3      | 4.55%   |
| Samsung Electronics SSD 870 EVO 500GB    | 3        | 3      | 4.55%   |
| Samsung Electronics HD103SI 1TB          | 2        | 2      | 3.03%   |
| Hitachi HDS721010CLA630 1TB              | 2        | 2      | 3.03%   |
| WDC WD7502ABYS-02A6B0 752GB              | 1        | 1      | 1.52%   |
| WDC WD5000AZRX-00A3KB0 500GB             | 1        | 1      | 1.52%   |
| WDC WD5000AVVS-63M8B0 500GB              | 1        | 1      | 1.52%   |
| WDC WD5000AAKS-00V1A0 500GB              | 1        | 1      | 1.52%   |
| WDC WD30EZRX-00MMMB0 3TB                 | 1        | 1      | 1.52%   |
| WDC WD30EFRX-68EUZN0 3TB                 | 1        | 1      | 1.52%   |
| WDC WD20EFRX-68EUZN0 2TB                 | 1        | 2      | 1.52%   |
| WDC WD20EADS-14R6B0 2TB                  | 1        | 1      | 1.52%   |
| WDC WD10EZRX-00L4HB0 1TB                 | 1        | 1      | 1.52%   |
| WDC WD10EZEX-22MFCA0 1TB                 | 1        | 1      | 1.52%   |
| WDC WD10EZEX-08M2NA0 1TB                 | 1        | 1      | 1.52%   |
| WDC WD10EURX-73C57Y0 1TB                 | 1        | 1      | 1.52%   |
| WDC WD10EARS-00MVWB0 1TB                 | 1        | 1      | 1.52%   |
| WDC WD10EADS-00L5B1 1TB                  | 1        | 1      | 1.52%   |
| WDC WD10EACS-65D6B0 1TB                  | 1        | 1      | 1.52%   |
| Toshiba MQ01ABF032 320GB                 | 1        | 1      | 1.52%   |
| Toshiba MK6475GSX 640GB                  | 1        | 1      | 1.52%   |
| T-FORCE SSD 512GB                        | 1        | 1      | 1.52%   |
| Seagate ST500LT012-9WS142 500GB          | 1        | 1      | 1.52%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 1        | 1      | 1.52%   |
| Seagate ST4000VN008-2DR166 4TB           | 1        | 2      | 1.52%   |
| Seagate ST3500630AS 500GB                | 1        | 1      | 1.52%   |
| Seagate ST3500418AS 500GB                | 1        | 1      | 1.52%   |
| Seagate ST3250310AS 250GB                | 1        | 1      | 1.52%   |
| Seagate ST3160827AS 160GB                | 1        | 1      | 1.52%   |
| Seagate ST3160023A 160GB                 | 1        | 1      | 1.52%   |
| Seagate ST31500341AS 1TB                 | 1        | 1      | 1.52%   |
| Seagate ST31000524AS 1TB                 | 1        | 2      | 1.52%   |
| Seagate ST2000DX001-1NS164 2TB           | 1        | 1      | 1.52%   |
| Seagate ST1000NM0011 1TB                 | 1        | 1      | 1.52%   |
| Seagate ST1000DM003-1SB102 1TB           | 1        | 1      | 1.52%   |
| Seagate ST1000DM003-1CH162 1TB           | 1        | 1      | 1.52%   |
| SanDisk SSD PLUS 1000GB                  | 1        | 1      | 1.52%   |
| SanDisk SDSSDX240GG25 240GB              | 1        | 1      | 1.52%   |
| Samsung Electronics SSD 870 EVO 1TB      | 1        | 1      | 1.52%   |
| Samsung Electronics SSD 840 Series 250GB | 1        | 1      | 1.52%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 15       | 19     | 23.81%  |
| WDC                 | 14       | 16     | 22.22%  |
| Samsung Electronics | 10       | 17     | 15.87%  |
| Hitachi             | 6        | 6      | 9.52%   |
| Crucial             | 3        | 3      | 4.76%   |
| Toshiba             | 2        | 2      | 3.17%   |
| SanDisk             | 2        | 2      | 3.17%   |
| Maxtor              | 2        | 2      | 3.17%   |
| T-FORCE             | 1        | 1      | 1.59%   |
| Phison Electronics  | 1        | 1      | 1.59%   |
| OCZ                 | 1        | 1      | 1.59%   |
| Micron Technology   | 1        | 1      | 1.59%   |
| LITEONIT            | 1        | 1      | 1.59%   |
| Kingston            | 1        | 1      | 1.59%   |
| Intenso             | 1        | 1      | 1.59%   |
| Intel               | 1        | 4      | 1.59%   |
| HGST                | 1        | 1      | 1.59%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 15       | 19     | 34.09%  |
| WDC                 | 14       | 16     | 31.82%  |
| Hitachi             | 6        | 6      | 13.64%  |
| Samsung Electronics | 4        | 11     | 9.09%   |
| Toshiba             | 2        | 2      | 4.55%   |
| Maxtor              | 2        | 2      | 4.55%   |
| HGST                | 1        | 1      | 2.27%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 41       | 57     | 68.33%  |
| SSD  | 18       | 21     | 30%     |
| NVMe | 1        | 1      | 1.67%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Samsung Electronics HD502IJ 500GB | 1        | 1      | 50%     |
| Hitachi HTS547550A9E384 500GB     | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 1        | 1      | 50%     |
| Hitachi             | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 214      | 575    | 44.31%  |
| Detected | 210      | 587    | 43.48%  |
| Malfunc  | 58       | 79     | 12.01%  |
| Failed   | 1        | 2      | 0.21%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 245      | 39.58%  |
| AMD                          | 153      | 24.72%  |
| Samsung Electronics          | 55       | 8.89%   |
| ASMedia Technology           | 29       | 4.68%   |
| SanDisk                      | 24       | 3.88%   |
| Phison Electronics           | 22       | 3.55%   |
| Kingston Technology Company  | 15       | 2.42%   |
| Micron/Crucial Technology    | 12       | 1.94%   |
| JMicron Technology           | 11       | 1.78%   |
| Marvell Technology Group     | 8        | 1.29%   |
| ADATA Technology             | 6        | 0.97%   |
| Realtek Semiconductor        | 5        | 0.81%   |
| LSI Logic / Symbios Logic    | 5        | 0.81%   |
| KIOXIA                       | 5        | 0.81%   |
| Silicon Motion               | 4        | 0.65%   |
| Seagate Technology           | 4        | 0.65%   |
| Toshiba America Info Systems | 2        | 0.32%   |
| SK hynix                     | 2        | 0.32%   |
| Silicon Image                | 2        | 0.32%   |
| Nvidia                       | 2        | 0.32%   |
| MAXIO Technology (Hangzhou)  | 2        | 0.32%   |
| VIA Technologies             | 1        | 0.16%   |
| OCZ Technology Group         | 1        | 0.16%   |
| O2 Micro                     | 1        | 0.16%   |
| Netac Technology             | 1        | 0.16%   |
| INNOGRIT                     | 1        | 0.16%   |
| Broadcom / LSI               | 1        | 0.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 92       | 12.27%  |
| AMD 400 Series Chipset SATA Controller                                                  | 37       | 4.93%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 32       | 4.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 28       | 3.73%   |
| AMD 500 Series Chipset SATA Controller                                                  | 28       | 3.73%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 27       | 3.6%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 21       | 2.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 19       | 2.53%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 18       | 2.4%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 18       | 2.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 16       | 2.13%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 15       | 2%      |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 15       | 2%      |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 15       | 2%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 14       | 1.87%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 14       | 1.87%   |
| Intel SATA Controller [RAID mode]                                                       | 12       | 1.6%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 10       | 1.33%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 10       | 1.33%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 9        | 1.2%    |
| AMD FCH SATA Controller D                                                               | 9        | 1.2%    |
| Phison E12 NVMe Controller                                                              | 8        | 1.07%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 8        | 1.07%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8        | 1.07%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 7        | 0.93%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 7        | 0.93%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 7        | 0.93%   |
| AMD 300 Series Chipset SATA Controller                                                  | 7        | 0.93%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 6        | 0.8%    |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 6        | 0.8%    |
| Intel SSD 660P Series                                                                   | 6        | 0.8%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 6        | 0.8%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6        | 0.8%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6        | 0.8%    |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 5        | 0.67%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 5        | 0.67%   |
| AMD X370 Series Chipset SATA Controller                                                 | 5        | 0.67%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 5        | 0.67%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 4        | 0.53%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                                   | 4        | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 366      | 62.03%  |
| NVMe | 145      | 24.58%  |
| IDE  | 50       | 8.47%   |
| RAID | 24       | 4.07%   |
| SAS  | 3        | 0.51%   |
| SCSI | 2        | 0.34%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor        | Desktops | Percent |
|---------------|----------|---------|
| Intel         | 244      | 60.7%   |
| AMD           | 157      | 39.05%  |
| sifive,u74-mc | 1        | 0.25%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Intel Core i7-3770 CPU @ 3.40GHz           | 9        | 2.24%   |
| AMD Ryzen 5 5600X 6-Core Processor         | 9        | 2.24%   |
| Intel Core i7-4790 CPU @ 3.60GHz           | 8        | 1.99%   |
| Intel Core i7-4790K CPU @ 4.00GHz          | 7        | 1.74%   |
| Intel Core i5-4590 CPU @ 3.30GHz           | 7        | 1.74%   |
| Intel Core i7-6700 CPU @ 3.40GHz           | 6        | 1.49%   |
| Intel Core i5-9600K CPU @ 3.70GHz          | 6        | 1.49%   |
| Intel Core i5-10400F CPU @ 2.90GHz         | 6        | 1.49%   |
| AMD Ryzen 7 3700X 8-Core Processor         | 6        | 1.49%   |
| AMD Ryzen 5 3600 6-Core Processor          | 6        | 1.49%   |
| AMD Ryzen 5 2600X Six-Core Processor       | 6        | 1.49%   |
| AMD Ryzen 9 5900X 12-Core Processor        | 5        | 1.24%   |
| AMD Ryzen 7 2700X Eight-Core Processor     | 5        | 1.24%   |
| AMD Ryzen 5 5600G with Radeon Graphics     | 5        | 1.24%   |
| Intel Core i9-9900K CPU @ 3.60GHz          | 4        | 1%      |
| Intel Core i7-8700 CPU @ 3.20GHz           | 4        | 1%      |
| Intel Core i7-7700K CPU @ 4.20GHz          | 4        | 1%      |
| Intel Core i7-3770K CPU @ 3.50GHz          | 4        | 1%      |
| Intel Core i7 CPU 920 @ 2.67GHz            | 4        | 1%      |
| Intel Core i3-10100F CPU @ 3.60GHz         | 4        | 1%      |
| AMD Ryzen 9 5950X 16-Core Processor        | 4        | 1%      |
| AMD Ryzen 7 5700G with Radeon Graphics     | 4        | 1%      |
| AMD Ryzen 7 1700 Eight-Core Processor      | 4        | 1%      |
| Intel Core i7-5820K CPU @ 3.30GHz          | 3        | 0.75%   |
| Intel Core i7-4770 CPU @ 3.40GHz           | 3        | 0.75%   |
| Intel Core i5-8400 CPU @ 2.80GHz           | 3        | 0.75%   |
| Intel Core i5-7400 CPU @ 3.00GHz           | 3        | 0.75%   |
| Intel Core i5-3570 CPU @ 3.40GHz           | 3        | 0.75%   |
| Intel Core i5-2300 CPU @ 2.80GHz           | 3        | 0.75%   |
| Intel Core i3-4130 CPU @ 3.40GHz           | 3        | 0.75%   |
| Intel 12th Gen Core i9-12900K              | 3        | 0.75%   |
| Intel 12th Gen Core i7-12700K              | 3        | 0.75%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz    | 3        | 0.75%   |
| AMD Ryzen 9 7950X 16-Core Processor        | 3        | 0.75%   |
| AMD Ryzen 9 3900X 12-Core Processor        | 3        | 0.75%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics | 3        | 0.75%   |
| AMD Ryzen 7 5800X 8-Core Processor         | 3        | 0.75%   |
| AMD Ryzen 7 5700X 8-Core Processor         | 3        | 0.75%   |
| AMD Ryzen 7 2700 Eight-Core Processor      | 3        | 0.75%   |
| AMD Ryzen 5 5600 6-Core Processor          | 3        | 0.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 76       | 18.91%  |
| Intel Core i5           | 67       | 16.67%  |
| AMD Ryzen 5             | 47       | 11.69%  |
| AMD Ryzen 7             | 31       | 7.71%   |
| Intel Core i3           | 24       | 5.97%   |
| Other                   | 23       | 5.72%   |
| AMD Ryzen 9             | 22       | 5.47%   |
| Intel Xeon              | 17       | 4.23%   |
| AMD FX                  | 12       | 2.99%   |
| Intel Pentium           | 10       | 2.49%   |
| AMD Ryzen 3             | 9        | 2.24%   |
| Intel Core i9           | 8        | 1.99%   |
| Intel Celeron           | 7        | 1.74%   |
| Intel Core 2 Duo        | 6        | 1.49%   |
| AMD Phenom II X4        | 5        | 1.24%   |
| Intel Core 2 Quad       | 4        | 1%      |
| AMD A6                  | 4        | 1%      |
| AMD Ryzen Threadripper  | 3        | 0.75%   |
| AMD Ryzen 7 PRO         | 3        | 0.75%   |
| AMD Athlon 64 X2        | 3        | 0.75%   |
| AMD A8                  | 3        | 0.75%   |
| Intel Pentium Gold      | 2        | 0.5%    |
| AMD Phenom II X2        | 2        | 0.5%    |
| AMD Opteron             | 2        | 0.5%    |
| AMD A10                 | 2        | 0.5%    |
| Intel Pentium Dual-Core | 1        | 0.25%   |
| Intel Atom              | 1        | 0.25%   |
| AMD PRO A10             | 1        | 0.25%   |
| AMD Phenom II X6        | 1        | 0.25%   |
| AMD Phenom              | 1        | 0.25%   |
| AMD EPYC                | 1        | 0.25%   |
| AMD E2                  | 1        | 0.25%   |
| AMD E1                  | 1        | 0.25%   |
| AMD Athlon II X2        | 1        | 0.25%   |
| AMD A4                  | 1        | 0.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 152      | 37.81%  |
| 6       | 84       | 20.9%   |
| 2       | 64       | 15.92%  |
| 8       | 56       | 13.93%  |
| 16      | 17       | 4.23%   |
| 12      | 12       | 2.99%   |
| 10      | 5        | 1.24%   |
| 1       | 4        | 1%      |
| 24      | 3        | 0.75%   |
| 3       | 2        | 0.5%    |
| 36      | 1        | 0.25%   |
| 14      | 1        | 0.25%   |
| Unknown | 1        | 0.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 398      | 99%     |
| 2       | 3        | 0.75%   |
| Unknown | 1        | 0.25%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 279      | 69.23%  |
| 1       | 123      | 30.52%  |
| Unknown | 1        | 0.25%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 401      | 99.75%  |
| Unknown        | 1        | 0.25%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 196      | 47.92%  |
| 0x306c3    | 21       | 5.13%   |
| 0x08701021 | 14       | 3.42%   |
| 0x506e3    | 10       | 2.44%   |
| 0x306a9    | 9        | 2.2%    |
| 0x0800820d | 9        | 2.2%    |
| 0x906e9    | 8        | 1.96%   |
| 0xa0653    | 7        | 1.71%   |
| 0xa0655    | 6        | 1.47%   |
| 0x906ed    | 6        | 1.47%   |
| 0x906ea    | 6        | 1.47%   |
| 0x90672    | 6        | 1.47%   |
| 0x206a7    | 6        | 1.47%   |
| 0x0a50000c | 6        | 1.47%   |
| 0x010000c8 | 6        | 1.47%   |
| 0x1067a    | 5        | 1.22%   |
| 0x0a201205 | 5        | 1.22%   |
| 0x0a201016 | 5        | 1.22%   |
| 0x406f1    | 4        | 0.98%   |
| 0x0a601203 | 4        | 0.98%   |
| 0xa0671    | 3        | 0.73%   |
| 0x306f2    | 3        | 0.73%   |
| 0x306e4    | 3        | 0.73%   |
| 0x206d7    | 3        | 0.73%   |
| 0x0a50000d | 3        | 0.73%   |
| 0x0a20120a | 3        | 0.73%   |
| 0x08001138 | 3        | 0.73%   |
| 0x08001137 | 3        | 0.73%   |
| 0x0600611a | 3        | 0.73%   |
| 0x06000852 | 3        | 0.73%   |
| 0xb0671    | 2        | 0.49%   |
| 0x106e5    | 2        | 0.49%   |
| 0x106a5    | 2        | 0.49%   |
| 0x0a201204 | 2        | 0.49%   |
| 0x0a201009 | 2        | 0.49%   |
| 0x08600106 | 2        | 0.49%   |
| 0x08001126 | 2        | 0.49%   |
| 0x06001119 | 2        | 0.49%   |
| 0x06000822 | 2        | 0.49%   |
| 0x906ec    | 1        | 0.24%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 56       | 13.9%   |
| KabyLake         | 44       | 10.92%  |
| Zen 3            | 40       | 9.93%   |
| IvyBridge        | 36       | 8.93%   |
| Zen 2            | 30       | 7.44%   |
| Zen+             | 20       | 4.96%   |
| Zen              | 20       | 4.96%   |
| CometLake        | 19       | 4.71%   |
| Unknown          | 19       | 4.71%   |
| Skylake          | 16       | 3.97%   |
| SandyBridge      | 16       | 3.97%   |
| Piledriver       | 16       | 3.97%   |
| K10              | 11       | 2.73%   |
| Penryn           | 10       | 2.48%   |
| Nehalem          | 9        | 2.23%   |
| Excavator        | 6        | 1.49%   |
| Broadwell        | 6        | 1.49%   |
| Alderlake Hybrid | 6        | 1.49%   |
| Icelake          | 5        | 1.24%   |
| Westmere         | 3        | 0.74%   |
| K8 Hammer        | 3        | 0.74%   |
| Core             | 3        | 0.74%   |
| Steamroller      | 1        | 0.25%   |
| Silvermont       | 1        | 0.25%   |
| Puma             | 1        | 0.25%   |
| K10 Llano        | 1        | 0.25%   |
| Goldmont plus    | 1        | 0.25%   |
| Goldmont         | 1        | 0.25%   |
| Bulldozer        | 1        | 0.25%   |
| Bonnell          | 1        | 0.25%   |
| Bobcat           | 1        | 0.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 198      | 44.9%   |
| AMD                        | 135      | 30.61%  |
| Intel                      | 103      | 23.36%  |
| Matrox Electronics Systems | 3        | 0.68%   |
| ASPEED Technology          | 2        | 0.45%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 23       | 5.11%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 18       | 4%      |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 16       | 3.56%   |
| Nvidia GK208B [GeForce GT 710]                                              | 12       | 2.67%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 10       | 2.22%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 9        | 2%      |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 9        | 2%      |
| Intel HD Graphics 530                                                       | 8        | 1.78%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 8        | 1.78%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 8        | 1.78%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 7        | 1.56%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 7        | 1.56%   |
| Intel HD Graphics 630                                                       | 7        | 1.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 7        | 1.56%   |
| Nvidia GK208B [GeForce GT 730]                                              | 6        | 1.33%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 6        | 1.33%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 6        | 1.33%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 6        | 1.33%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 6        | 1.33%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 5        | 1.11%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 5        | 1.11%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 5        | 1.11%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 4        | 0.89%   |
| Nvidia GT218 [GeForce 210]                                                  | 4        | 0.89%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 4        | 0.89%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 4        | 0.89%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 4        | 0.89%   |
| AMD Raphael                                                                 | 4        | 0.89%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4        | 0.89%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 4        | 0.89%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 4        | 0.89%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 4        | 0.89%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 4        | 0.89%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 3        | 0.67%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 3        | 0.67%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 3        | 0.67%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 0.67%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 3        | 0.67%   |
| Nvidia GF108 [GeForce GT 630]                                               | 3        | 0.67%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 3        | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 186      | 46.15%  |
| 1 x AMD                  | 120      | 29.78%  |
| 1 x Intel                | 71       | 17.62%  |
| 2 x AMD                  | 5        | 1.24%   |
| Intel + Nvidia           | 4        | 0.99%   |
| Intel + AMD              | 4        | 0.99%   |
| 2 x Nvidia               | 3        | 0.74%   |
| AMD + Nvidia             | 2        | 0.5%    |
| AMD + Matrox             | 2        | 0.5%    |
| Other                    | 1        | 0.25%   |
| 3 x Nvidia               | 1        | 0.25%   |
| Nvidia + Matrox          | 1        | 0.25%   |
| Nvidia + ASPEED          | 1        | 0.25%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.25%   |
| 1 x ASPEED               | 1        | 0.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 242      | 59.75%  |
| Proprietary | 146      | 36.05%  |
| Unknown     | 17       | 4.2%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 184      | 44.88%  |
| 1.01-2.0   | 49       | 11.95%  |
| 7.01-8.0   | 40       | 9.76%   |
| 3.01-4.0   | 40       | 9.76%   |
| 0.51-1.0   | 32       | 7.8%    |
| 5.01-6.0   | 23       | 5.61%   |
| 0.01-0.5   | 21       | 5.12%   |
| 8.01-16.0  | 15       | 3.66%   |
| 16.01-24.0 | 4        | 0.98%   |
| 4.01-5.0   | 1        | 0.24%   |
| 2.01-3.0   | 1        | 0.24%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 87       | 18.59%  |
| Dell                 | 55       | 11.75%  |
| Goldstar             | 50       | 10.68%  |
| Hewlett-Packard      | 36       | 7.69%   |
| Philips              | 27       | 5.77%   |
| Acer                 | 27       | 5.77%   |
| AOC                  | 23       | 4.91%   |
| BenQ                 | 21       | 4.49%   |
| Iiyama               | 19       | 4.06%   |
| Ancor Communications | 16       | 3.42%   |
| ASUSTek Computer     | 13       | 2.78%   |
| ViewSonic            | 7        | 1.5%    |
| Sony                 | 7        | 1.5%    |
| Eizo                 | 5        | 1.07%   |
| Vizio                | 3        | 0.64%   |
| RTK                  | 3        | 0.64%   |
| NEC Computers        | 3        | 0.64%   |
| LG Electronics       | 3        | 0.64%   |
| Idek Iiyama          | 3        | 0.64%   |
| Xiaomi               | 2        | 0.43%   |
| Vestel Elektronik    | 2        | 0.43%   |
| Unknown              | 2        | 0.43%   |
| Planar               | 2        | 0.43%   |
| Mi                   | 2        | 0.43%   |
| Lenovo               | 2        | 0.43%   |
| Hitachi              | 2        | 0.43%   |
| Gigabyte Technology  | 2        | 0.43%   |
| Fujitsu Siemens      | 2        | 0.43%   |
| DTV                  | 2        | 0.43%   |
| Denver               | 2        | 0.43%   |
| CHD                  | 2        | 0.43%   |
| Unknown              | 2        | 0.43%   |
| Xerox                | 1        | 0.21%   |
| Vita                 | 1        | 0.21%   |
| TXD                  | 1        | 0.21%   |
| Sunplus              | 1        | 0.21%   |
| STD                  | 1        | 0.21%   |
| Sceptre Tech         | 1        | 0.21%   |
| QUS                  | 1        | 0.21%   |
| Pixio                | 1        | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch           | 5        | 1%      |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 5        | 1%      |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 3        | 0.6%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 3        | 0.6%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3        | 0.6%    |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                | 3        | 0.6%    |
| Iiyama PLE2207WS IVM5609 1680x1050 474x296mm 22.0-inch                | 3        | 0.6%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 3        | 0.6%    |
| Dell 2408WFP DELA02B 1920x1200 519x320mm 24.0-inch                    | 3        | 0.6%    |
| AOC Q27P2W AOC2702 2560x1440 597x336mm 27.0-inch                      | 3        | 0.6%    |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch            | 2        | 0.4%    |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch  | 2        | 0.4%    |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 520x320mm 24.0-inch   | 2        | 0.4%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 2        | 0.4%    |
| Samsung Electronics LCD Monitor SAM0D42 3840x2160 890x500mm 40.2-inch | 2        | 0.4%    |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch | 2        | 0.4%    |
| Samsung Electronics LC27G5xT SAM7079 2560x1440 597x336mm 27.0-inch    | 2        | 0.4%    |
| Planar PLL2710W PLN2710 1920x1080 597x336mm 27.0-inch                 | 2        | 0.4%    |
| Philips PHL 247E6 PHLC0E7 1920x1080 521x293mm 23.5-inch               | 2        | 0.4%    |
| Philips PHL 245E1 PHLC20B 1920x1080 527x296mm 23.8-inch               | 2        | 0.4%    |
| Philips FTV PHL01EA 1920x1080 640x360mm 28.9-inch                     | 2        | 0.4%    |
| Mi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                      | 2        | 0.4%    |
| Iiyama PLG2888UH IVM710B 3840x2160                                    | 2        | 0.4%    |
| Hewlett-Packard w2216 HWP280B 1680x1050 465x291mm 21.6-inch           | 2        | 0.4%    |
| Hewlett-Packard 24w HPN3431 1920x1080 527x296mm 23.8-inch             | 2        | 0.4%    |
| Hewlett-Packard 2311 HWP2939 1920x1080 509x286mm 23.0-inch            | 2        | 0.4%    |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                | 2        | 0.4%    |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 2        | 0.4%    |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch             | 2        | 0.4%    |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 2        | 0.4%    |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                | 2        | 0.4%    |
| Goldstar 22EA53 GSM59A5 1920x1080 477x268mm 21.5-inch                 | 2        | 0.4%    |
| Dell S3422DW DELD102 3440x1440 797x334mm 34.0-inch                    | 2        | 0.4%    |
| Dell P2719H DEL4184 1920x1080 598x336mm 27.0-inch                     | 2        | 0.4%    |
| Dell P2415Q DELA0BE 3840x2160 527x296mm 23.8-inch                     | 2        | 0.4%    |
| Dell P2214H DELA098 1920x1080 480x270mm 21.7-inch                     | 2        | 0.4%    |
| Dell 2007WFP DELA019 1680x1050 430x270mm 20.0-inch                    | 2        | 0.4%    |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 2        | 0.4%    |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                    | 2        | 0.4%    |
| AOC U3277WB AOC3277 3840x2160 698x393mm 31.5-inch                     | 2        | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 212      | 47.96%  |
| 3840x2160 (4K)     | 54       | 12.22%  |
| 2560x1440 (QHD)    | 30       | 6.79%   |
| 1680x1050 (WSXGA+) | 25       | 5.66%   |
| 1920x1200 (WUXGA)  | 23       | 5.2%    |
| 1280x1024 (SXGA)   | 18       | 4.07%   |
| 1366x768 (WXGA)    | 14       | 3.17%   |
| 3440x1440          | 12       | 2.71%   |
| 2560x1080          | 8        | 1.81%   |
| 1600x900 (HD+)     | 8        | 1.81%   |
| 1360x768           | 7        | 1.58%   |
| 1440x900 (WXGA+)   | 5        | 1.13%   |
| Unknown            | 5        | 1.13%   |
| 3840x1080          | 4        | 0.9%    |
| 3840x1600          | 2        | 0.45%   |
| 1920x540           | 2        | 0.45%   |
| 1280x720 (HD)      | 2        | 0.45%   |
| 6160x1440          | 1        | 0.23%   |
| 5760x2160          | 1        | 0.23%   |
| 5760x1080          | 1        | 0.23%   |
| 480x1920           | 1        | 0.23%   |
| 4800x1080          | 1        | 0.23%   |
| 3840x1200          | 1        | 0.23%   |
| 3600x1200          | 1        | 0.23%   |
| 2288x1287          | 1        | 0.23%   |
| 1600x1200          | 1        | 0.23%   |
| 1280x768           | 1        | 0.23%   |
| 1024x768 (XGA)     | 1        | 0.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 80       | 17.28%  |
| 23      | 69       | 14.9%   |
| 27      | 66       | 14.25%  |
| 21      | 51       | 11.02%  |
| 31      | 30       | 6.48%   |
| Unknown | 23       | 4.97%   |
| 34      | 18       | 3.89%   |
| 19      | 17       | 3.67%   |
| 22      | 16       | 3.46%   |
| 18      | 10       | 2.16%   |
| 72      | 9        | 1.94%   |
| 32      | 9        | 1.94%   |
| 20      | 8        | 1.73%   |
| 46      | 7        | 1.51%   |
| 84      | 5        | 1.08%   |
| 17      | 5        | 1.08%   |
| 54      | 4        | 0.86%   |
| 40      | 4        | 0.86%   |
| 25      | 4        | 0.86%   |
| 65      | 3        | 0.65%   |
| 48      | 3        | 0.65%   |
| 36      | 3        | 0.65%   |
| 28      | 3        | 0.65%   |
| 37      | 2        | 0.43%   |
| 15      | 2        | 0.43%   |
| 142     | 1        | 0.22%   |
| 69      | 1        | 0.22%   |
| 64      | 1        | 0.22%   |
| 60      | 1        | 0.22%   |
| 55      | 1        | 0.22%   |
| 49      | 1        | 0.22%   |
| 43      | 1        | 0.22%   |
| 42      | 1        | 0.22%   |
| 38      | 1        | 0.22%   |
| 35      | 1        | 0.22%   |
| 33      | 1        | 0.22%   |
| 26      | 1        | 0.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 185      | 41.76%  |
| 401-500        | 93       | 20.99%  |
| 601-700        | 47       | 10.61%  |
| 701-800        | 31       | 7%      |
| Unknown        | 23       | 5.19%   |
| 1001-1500      | 21       | 4.74%   |
| 1501-2000      | 15       | 3.39%   |
| 351-400        | 10       | 2.26%   |
| 801-900        | 8        | 1.81%   |
| 301-350        | 7        | 1.58%   |
| 901-1000       | 2        | 0.45%   |
| More than 2000 | 1        | 0.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 291      | 72.03%  |
| 16/10   | 50       | 12.38%  |
| 21/9    | 21       | 5.2%    |
| Unknown | 17       | 4.21%   |
| 5/4     | 14       | 3.47%   |
| 32/9    | 3        | 0.74%   |
| 3/2     | 3        | 0.74%   |
| 6/5     | 1        | 0.25%   |
| 4/3     | 1        | 0.25%   |
| 1.96    | 1        | 0.25%   |
| 1.00    | 1        | 0.25%   |
| 0.25    | 1        | 0.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 157      | 35.12%  |
| 301-350        | 67       | 14.99%  |
| 351-500        | 61       | 13.65%  |
| 151-200        | 41       | 9.17%   |
| 251-300        | 33       | 7.38%   |
| More than 1000 | 26       | 5.82%   |
| 501-1000       | 23       | 5.15%   |
| Unknown        | 23       | 5.15%   |
| 141-150        | 14       | 3.13%   |
| 101-110        | 2        | 0.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 252      | 60.58%  |
| 101-120 | 74       | 17.79%  |
| 1-50    | 34       | 8.17%   |
| 121-160 | 27       | 6.49%   |
| Unknown | 23       | 5.53%   |
| 161-240 | 6        | 1.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 271      | 66.26%  |
| 2     | 108      | 26.41%  |
| 0     | 18       | 4.4%    |
| 3     | 9        | 2.2%    |
| 4     | 3        | 0.73%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 240      | 40.13%  |
| Intel                           | 199      | 33.28%  |
| Qualcomm Atheros                | 36       | 6.02%   |
| Broadcom                        | 20       | 3.34%   |
| Ralink Technology               | 15       | 2.51%   |
| TP-Link                         | 10       | 1.67%   |
| Aquantia                        | 10       | 1.67%   |
| MediaTek                        | 8        | 1.34%   |
| Ralink                          | 6        | 1%      |
| Huawei Technologies             | 6        | 1%      |
| Samsung Electronics             | 4        | 0.67%   |
| Qualcomm Atheros Communications | 4        | 0.67%   |
| NetGear                         | 3        | 0.5%    |
| Edimax Technology               | 3        | 0.5%    |
| D-Link                          | 3        | 0.5%    |
| Belkin Components               | 3        | 0.5%    |
| ASIX Electronics                | 3        | 0.5%    |
| Xiaomi                          | 2        | 0.33%   |
| Wilocity                        | 2        | 0.33%   |
| VIA Technologies                | 2        | 0.33%   |
| Nvidia                          | 2        | 0.33%   |
| ASUSTek Computer                | 2        | 0.33%   |
| ZyXEL Communications            | 1        | 0.17%   |
| U-Blox                          | 1        | 0.17%   |
| Solarflare Communications       | 1        | 0.17%   |
| Seeed Technology                | 1        | 0.17%   |
| Microsoft                       | 1        | 0.17%   |
| Mercucys                        | 1        | 0.17%   |
| Mellanox Technologies           | 1        | 0.17%   |
| LSI                             | 1        | 0.17%   |
| Linksys                         | 1        | 0.17%   |
| LG Electronics                  | 1        | 0.17%   |
| DisplayLink                     | 1        | 0.17%   |
| D-Link System                   | 1        | 0.17%   |
| Bose                            | 1        | 0.17%   |
| Arduino SA                      | 1        | 0.17%   |
| American Megatrends             | 1        | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 181      | 25.89%  |
| Intel I211 Gigabit Network Connection                             | 30       | 4.29%   |
| Realtek RTL8125 2.5GbE Controller                                 | 27       | 3.86%   |
| Intel Ethernet Controller I225-V                                  | 26       | 3.72%   |
| Intel Wi-Fi 6 AX200                                               | 24       | 3.43%   |
| Intel Ethernet Connection (2) I219-V                              | 16       | 2.29%   |
| Intel Ethernet Connection I217-LM                                 | 14       | 2%      |
| Intel Ethernet Connection (7) I219-V                              | 13       | 1.86%   |
| Intel Ethernet Connection (2) I218-V                              | 12       | 1.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12       | 1.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9        | 1.29%   |
| Intel 82579V Gigabit Network Connection                           | 9        | 1.29%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 8        | 1.14%   |
| Realtek 802.11ac NIC                                              | 8        | 1.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 8        | 1.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7        | 1%      |
| Intel 82574L Gigabit Network Connection                           | 7        | 1%      |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter      | 7        | 1%      |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 7        | 1%      |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 6        | 0.86%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 6        | 0.86%   |
| Intel Ethernet Connection (14) I219-V                             | 6        | 0.86%   |
| Ralink RT5370 Wireless Adapter                                    | 5        | 0.72%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 5        | 0.72%   |
| Intel I210 Gigabit Network Connection                             | 5        | 0.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5        | 0.72%   |
| Huawei ALP-AL00                                                   | 5        | 0.72%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 4        | 0.57%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 4        | 0.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 0.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4        | 0.57%   |
| Qualcomm Atheros AR9271 802.11n                                   | 4        | 0.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4        | 0.57%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 4        | 0.57%   |
| Intel Wireless-AC 9260                                            | 4        | 0.57%   |
| Intel Wireless 7260                                               | 4        | 0.57%   |
| Intel Ethernet Connection I217-V                                  | 4        | 0.57%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4        | 0.57%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 4        | 0.57%   |
| TP-Link 802.11ac NIC                                              | 3        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 73       | 32.44%  |
| Realtek Semiconductor           | 54       | 24%     |
| Qualcomm Atheros                | 19       | 8.44%   |
| Ralink Technology               | 15       | 6.67%   |
| Broadcom                        | 15       | 6.67%   |
| TP-Link                         | 10       | 4.44%   |
| MediaTek                        | 7        | 3.11%   |
| Ralink                          | 6        | 2.67%   |
| Qualcomm Atheros Communications | 4        | 1.78%   |
| NetGear                         | 3        | 1.33%   |
| Edimax Technology               | 3        | 1.33%   |
| D-Link                          | 3        | 1.33%   |
| Belkin Components               | 3        | 1.33%   |
| Wilocity                        | 2        | 0.89%   |
| ASUSTek Computer                | 2        | 0.89%   |
| ZyXEL Communications            | 1        | 0.44%   |
| Microsoft                       | 1        | 0.44%   |
| Mercucys                        | 1        | 0.44%   |
| Linksys                         | 1        | 0.44%   |
| LG Electronics                  | 1        | 0.44%   |
| D-Link System                   | 1        | 0.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 24       | 10.34%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 8        | 3.45%   |
| Realtek 802.11ac NIC                                           | 8        | 3.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 8        | 3.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 7        | 3.02%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 7        | 3.02%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 6        | 2.59%   |
| Ralink RT5370 Wireless Adapter                                 | 5        | 2.16%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 5        | 2.16%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 5        | 2.16%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 4        | 1.72%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 4        | 1.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4        | 1.72%   |
| Qualcomm Atheros AR9271 802.11n                                | 4        | 1.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4        | 1.72%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 4        | 1.72%   |
| Intel Wireless-AC 9260                                         | 4        | 1.72%   |
| Intel Wireless 7260                                            | 4        | 1.72%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 4        | 1.72%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 4        | 1.72%   |
| TP-Link 802.11ac NIC                                           | 3        | 1.29%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 3        | 1.29%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 3        | 1.29%   |
| Ralink MT7601U Wireless Adapter                                | 3        | 1.29%   |
| Intel Wireless 3165                                            | 3        | 1.29%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter             | 2        | 0.86%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 2        | 0.86%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 2        | 0.86%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 2        | 0.86%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 2        | 0.86%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2        | 0.86%   |
| Realtek 802.11ac WLAN Adapter                                  | 2        | 0.86%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 2        | 0.86%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 2        | 0.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2        | 0.86%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2        | 0.86%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 2        | 0.86%   |
| Intel Wireless 8265 / 8275                                     | 2        | 0.86%   |
| Intel Wireless 8260                                            | 2        | 0.86%   |
| Intel Wireless 7265                                            | 2        | 0.86%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 219      | 48.88%  |
| Intel                     | 170      | 37.95%  |
| Qualcomm Atheros          | 18       | 4.02%   |
| Aquantia                  | 10       | 2.23%   |
| Broadcom                  | 7        | 1.56%   |
| Huawei Technologies       | 6        | 1.34%   |
| Samsung Electronics       | 4        | 0.89%   |
| ASIX Electronics          | 3        | 0.67%   |
| Xiaomi                    | 2        | 0.45%   |
| VIA Technologies          | 2        | 0.45%   |
| Nvidia                    | 2        | 0.45%   |
| Solarflare Communications | 1        | 0.22%   |
| Mellanox Technologies     | 1        | 0.22%   |
| MediaTek                  | 1        | 0.22%   |
| DisplayLink               | 1        | 0.22%   |
| American Megatrends       | 1        | 0.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 181      | 39.18%  |
| Intel I211 Gigabit Network Connection                             | 30       | 6.49%   |
| Realtek RTL8125 2.5GbE Controller                                 | 27       | 5.84%   |
| Intel Ethernet Controller I225-V                                  | 26       | 5.63%   |
| Intel Ethernet Connection (2) I219-V                              | 16       | 3.46%   |
| Intel Ethernet Connection I217-LM                                 | 14       | 3.03%   |
| Intel Ethernet Connection (7) I219-V                              | 13       | 2.81%   |
| Intel Ethernet Connection (2) I218-V                              | 12       | 2.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12       | 2.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9        | 1.95%   |
| Intel 82579V Gigabit Network Connection                           | 9        | 1.95%   |
| Intel 82574L Gigabit Network Connection                           | 7        | 1.52%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 7        | 1.52%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 6        | 1.3%    |
| Intel Ethernet Connection (14) I219-V                             | 6        | 1.3%    |
| Intel I210 Gigabit Network Connection                             | 5        | 1.08%   |
| Huawei ALP-AL00                                                   | 5        | 1.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 0.87%   |
| Intel Ethernet Connection I217-V                                  | 4        | 0.87%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3        | 0.65%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3        | 0.65%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 0.65%   |
| Intel Ethernet Connection (7) I219-LM                             | 3        | 0.65%   |
| Intel Ethernet Connection (11) I219-V                             | 3        | 0.65%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.43%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 2        | 0.43%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2        | 0.43%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2        | 0.43%   |
| Nvidia MCP61 Ethernet                                             | 2        | 0.43%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 0.43%   |
| Intel 82583V Gigabit Network Connection                           | 2        | 0.43%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 0.43%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 0.43%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2        | 0.43%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1        | 0.22%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.22%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.22%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.22%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1        | 0.22%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 398      | 65.03%  |
| WiFi     | 210      | 34.31%  |
| Modem    | 4        | 0.65%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 305      | 73.14%  |
| WiFi     | 112      | 26.86%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 237      | 58.96%  |
| 2     | 133      | 33.08%  |
| 3     | 25       | 6.22%   |
| 4     | 3        | 0.75%   |
| 6     | 2        | 0.5%    |
| 0     | 2        | 0.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 287      | 70.86%  |
| Yes  | 118      | 29.14%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 68       | 37.16%  |
| Cambridge Silicon Radio         | 45       | 24.59%  |
| ASUSTek Computer                | 17       | 9.29%   |
| Realtek Semiconductor           | 16       | 8.74%   |
| Broadcom                        | 8        | 4.37%   |
| MediaTek                        | 7        | 3.83%   |
| TP-Link                         | 5        | 2.73%   |
| IMC Networks                    | 5        | 2.73%   |
| Qualcomm Atheros Communications | 3        | 1.64%   |
| Edimax Technology               | 3        | 1.64%   |
| Ralink                          | 1        | 0.55%   |
| Foxconn / Hon Hai               | 1        | 0.55%   |
| Dynex                           | 1        | 0.55%   |
| D-Link                          | 1        | 0.55%   |
| Conwise Technology              | 1        | 0.55%   |
| Apple                           | 1        | 0.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 45       | 24.32%  |
| Intel AX200 Bluetooth                                    | 24       | 12.97%  |
| Realtek Bluetooth Radio                                  | 13       | 7.03%   |
| Intel Bluetooth wireless interface                       | 10       | 5.41%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 8        | 4.32%   |
| MediaTek Wireless_Device                                 | 7        | 3.78%   |
| Intel Wireless-AC 3168 Bluetooth                         | 7        | 3.78%   |
| Intel AX210 Bluetooth                                    | 6        | 3.24%   |
| Intel AX201 Bluetooth                                    | 6        | 3.24%   |
| ASUS ASUS USB-BT500                                      | 6        | 3.24%   |
| TP-Link UB500 Adapter                                    | 5        | 2.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 5        | 2.7%    |
| IMC Networks Bluetooth Radio                             | 5        | 2.7%    |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 5        | 2.7%    |
| Realtek  Bluetooth 4.2 Adapter                           | 3        | 1.62%   |
| Qualcomm Atheros  Bluetooth Device                       | 3        | 1.62%   |
| Intel Bluetooth Device                                   | 3        | 1.62%   |
| ASUS Qualcomm Bluetooth 4.1                              | 2        | 1.08%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE    | 2        | 1.08%   |
| ASUS Bluetooth Device                                    | 2        | 1.08%   |
| ASUS BCM20702A0                                          | 2        | 1.08%   |
| Ralink RT3290 Bluetooth                                  | 1        | 0.54%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 1        | 0.54%   |
| Foxconn / Hon Hai Wireless_Device                        | 1        | 0.54%   |
| Edimax Wi-Fi AC600 Bluetooth4.0 USB Adapter              | 1        | 0.54%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter  | 1        | 0.54%   |
| Edimax Bluetooth Adapter                                 | 1        | 0.54%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 0.54%   |
| D-Link DBT-122 Bluetooth adapter                         | 1        | 0.54%   |
| Conwise CW6622                                           | 1        | 0.54%   |
| Broadcom Bluetooth Controller                            | 1        | 0.54%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 UHE Dongle      | 1        | 0.54%   |
| Broadcom BCM43142 Bluetooth 4.0                          | 1        | 0.54%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 1        | 0.54%   |
| ASUS Bluetooth Radio                                     | 1        | 0.54%   |
| ASUS Bluetooth Adapter                                   | 1        | 0.54%   |
| Apple Bluetooth Host Controller                          | 1        | 0.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 235      | 31.08%  |
| AMD                         | 199      | 26.32%  |
| Nvidia                      | 194      | 25.66%  |
| C-Media Electronics         | 18       | 2.38%   |
| GN Netcom                   | 9        | 1.19%   |
| JMTek                       | 7        | 0.93%   |
| Generalplus Technology      | 6        | 0.79%   |
| Creative Labs               | 6        | 0.79%   |
| Texas Instruments           | 5        | 0.66%   |
| VIA Technologies            | 4        | 0.53%   |
| Micro Star International    | 4        | 0.53%   |
| Logitech                    | 4        | 0.53%   |
| Kingston Technology         | 4        | 0.53%   |
| Tenx Technology             | 3        | 0.4%    |
| Razer USA                   | 3        | 0.4%    |
| Corsair                     | 3        | 0.4%    |
| Blue Microphones            | 3        | 0.4%    |
| ASUSTek Computer            | 3        | 0.4%    |
| SteelSeries ApS             | 2        | 0.26%   |
| Nordic Semiconductor ASA    | 2        | 0.26%   |
| M-Audio                     | 2        | 0.26%   |
| KORG                        | 2        | 0.26%   |
| HECATE G4 TE GAMING HEADSET | 2        | 0.26%   |
| Focusrite-Novation          | 2        | 0.26%   |
| ZOOM                        | 1        | 0.13%   |
| Yamaha                      | 1        | 0.13%   |
| Veho                        | 1        | 0.13%   |
| Unknown                     | 1        | 0.13%   |
| TerraTec Electronic         | 1        | 0.13%   |
| Samson Technologies         | 1        | 0.13%   |
| Roland                      | 1        | 0.13%   |
| RME                         | 1        | 0.13%   |
| QinHeng Electronics         | 1        | 0.13%   |
| PreSonus Audio Electronics  | 1        | 0.13%   |
| Plantronics                 | 1        | 0.13%   |
| Philips (or NXP)            | 1        | 0.13%   |
| Microsoft                   | 1        | 0.13%   |
| Microdia                    | 1        | 0.13%   |
| Medeli Electronics          | 1        | 0.13%   |
| Mark of the Unicorn         | 1        | 0.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 49       | 5.59%   |
| AMD Family 17h/19h HD Audio Controller                                     | 34       | 3.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 33       | 3.77%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 29       | 3.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 25       | 2.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 24       | 2.74%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 23       | 2.63%   |
| Nvidia GP107GL High Definition Audio Controller                            | 22       | 2.51%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 21       | 2.4%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 20       | 2.28%   |
| Intel 200 Series PCH HD Audio                                              | 20       | 2.28%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 19       | 2.17%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 19       | 2.17%   |
| Intel Cannon Lake PCH cAVS                                                 | 18       | 2.05%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 16       | 1.83%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 15       | 1.71%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 15       | 1.71%   |
| Nvidia TU116 High Definition Audio Controller                              | 13       | 1.48%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 13       | 1.48%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 12       | 1.37%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 12       | 1.37%   |
| Nvidia GP108 High Definition Audio Controller                              | 10       | 1.14%   |
| Nvidia GP104 High Definition Audio Controller                              | 10       | 1.14%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 10       | 1.14%   |
| Intel Alder Lake-S HD Audio Controller                                     | 10       | 1.14%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 9        | 1.03%   |
| Nvidia TU104 HD Audio Controller                                           | 9        | 1.03%   |
| Nvidia GP106 High Definition Audio Controller                              | 9        | 1.03%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 9        | 1.03%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 9        | 1.03%   |
| Nvidia TU106 High Definition Audio Controller                              | 8        | 0.91%   |
| Nvidia High Definition Audio Controller                                    | 8        | 0.91%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 8        | 0.91%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8        | 0.91%   |
| AMD FCH Azalia Controller                                                  | 8        | 0.91%   |
| Nvidia GF119 HDMI Audio Controller                                         | 7        | 0.8%    |
| Intel Comet Lake PCH cAVS                                                  | 7        | 0.8%    |
| Nvidia GK107 HDMI Audio Controller                                         | 6        | 0.68%   |
| Nvidia GA106 High Definition Audio Controller                              | 6        | 0.68%   |
| Nvidia GA104 High Definition Audio Controller                              | 6        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 64       | 23.53%  |
| Corsair             | 48       | 17.65%  |
| G.Skill             | 31       | 11.4%   |
| Unknown             | 24       | 8.82%   |
| Samsung Electronics | 20       | 7.35%   |
| Crucial             | 19       | 6.99%   |
| SK hynix            | 13       | 4.78%   |
| Micron Technology   | 13       | 4.78%   |
| Team                | 6        | 2.21%   |
| Patriot             | 5        | 1.84%   |
| Ramaxel Technology  | 4        | 1.47%   |
| PNY                 | 3        | 1.1%    |
| AMD                 | 3        | 1.1%    |
| Unknown             | 3        | 1.1%    |
| Silicon Power       | 2        | 0.74%   |
| Unknown (ABCD)      | 1        | 0.37%   |
| Unifosa             | 1        | 0.37%   |
| Transcend           | 1        | 0.37%   |
| Teikon              | 1        | 0.37%   |
| Smart               | 1        | 0.37%   |
| Qumo                | 1        | 0.37%   |
| Neo Forza           | 1        | 0.37%   |
| Nanya Technology    | 1        | 0.37%   |
| Lexar               | 1        | 0.37%   |
| Kingmax             | 1        | 0.37%   |
| Avant               | 1        | 0.37%   |
| Atermiter           | 1        | 0.37%   |
| ASint Technology    | 1        | 0.37%   |
| A-DATA Technology   | 1        | 0.37%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 6        | 1.99%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 4        | 1.32%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s      | 3        | 0.99%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s   | 3        | 0.99%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s    | 3        | 0.99%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3600MT/s     | 3        | 0.99%   |
| Corsair RAM CMK32GX4M2Z3600C18 16GB DIMM DDR4 3800MT/s   | 3        | 0.99%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s    | 3        | 0.99%   |
| Unknown                                                  | 3        | 0.99%   |
| Unknown RAM Module 2GB DIMM 400MT/s                      | 2        | 0.66%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                     | 2        | 0.66%   |
| Unknown RAM 3600 C20 Series 32GB DIMM DDR4 3666MT/s      | 2        | 0.66%   |
| Unknown RAM 1866 CL10 Series 8192MB DIMM DDR3 933MT/s    | 2        | 0.66%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s       | 2        | 0.66%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s     | 2        | 0.66%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s     | 2        | 0.66%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2667MT/s    | 2        | 0.66%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s      | 2        | 0.66%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s      | 2        | 0.66%   |
| Ramaxel RAM RMR5040ED58E9W1600 4GB DIMM DDR3             | 2        | 0.66%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8GB DIMM DDR4 3600MT/s      | 2        | 0.66%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s           | 2        | 0.66%   |
| Micron RAM 8ATF1G64AZ-2G6E1 8GB DIMM DDR4 2667MT/s       | 2        | 0.66%   |
| Kingston RAM KHX2400C11D3/4GX 4GB DIMM DDR3 2400MT/s     | 2        | 0.66%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s    | 2        | 0.66%   |
| Kingston RAM 99U5471-002.A01LF 2GB DIMM DDR3 1334MT/s    | 2        | 0.66%   |
| Kingston RAM 9905471-079.A00LF 8192MB DIMM DDR3 1600MT/s | 2        | 0.66%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s   | 2        | 0.66%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s      | 2        | 0.66%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s       | 2        | 0.66%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s      | 2        | 0.66%   |
| G.Skill RAM F4-2133C15-8GVR 8GB DIMM DDR4 2133MT/s       | 2        | 0.66%   |
| G.Skill RAM F3-1600C9-8GXM 8192MB DIMM DDR3 1867MT/s     | 2        | 0.66%   |
| Crucial RAM CT8G4DFRA266.C8FE 8GB DIMM DDR4 2933MT/s     | 2        | 0.66%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s    | 2        | 0.66%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s   | 2        | 0.66%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s    | 2        | 0.66%   |
| AMD RAM R9S48G3206U2S 8GB DIMM DDR4 3333MT/s             | 2        | 0.66%   |
| Unknown RAM Module 8GB DIMM DDR3 800MT/s                 | 1        | 0.33%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                | 1        | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 143      | 58.37%  |
| DDR3    | 67       | 27.35%  |
| Unknown | 12       | 4.9%    |
| DDR5    | 10       | 4.08%   |
| DDR2    | 6        | 2.45%   |
| SDRAM   | 5        | 2.04%   |
| LPDDR4  | 1        | 0.41%   |
| DDR     | 1        | 0.41%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 233      | 96.28%  |
| SODIMM | 8        | 3.31%   |
| RIMM   | 1        | 0.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 106      | 39.85%  |
| 16384 | 61       | 22.93%  |
| 4096  | 48       | 18.05%  |
| 2048  | 26       | 9.77%   |
| 32768 | 24       | 9.02%   |
| 1024  | 1        | 0.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 38       | 13.87%  |
| 3600  | 28       | 10.22%  |
| 3200  | 28       | 10.22%  |
| 1333  | 26       | 9.49%   |
| 2400  | 20       | 7.3%    |
| 2667  | 19       | 6.93%   |
| 2133  | 13       | 4.74%   |
| 2666  | 8        | 2.92%   |
| 3800  | 7        | 2.55%   |
| 3000  | 7        | 2.55%   |
| 1867  | 6        | 2.19%   |
| 4800  | 5        | 1.82%   |
| 1066  | 5        | 1.82%   |
| 3666  | 4        | 1.46%   |
| 3066  | 4        | 1.46%   |
| 2933  | 4        | 1.46%   |
| 2800  | 4        | 1.46%   |
| 800   | 4        | 1.46%   |
| 3533  | 3        | 1.09%   |
| 3333  | 3        | 1.09%   |
| 1866  | 3        | 1.09%   |
| 1648  | 3        | 1.09%   |
| 400   | 3        | 1.09%   |
| 6000  | 2        | 0.73%   |
| 3866  | 2        | 0.73%   |
| 3266  | 2        | 0.73%   |
| 1334  | 2        | 0.73%   |
| 52217 | 1        | 0.36%   |
| 5808  | 1        | 0.36%   |
| 5800  | 1        | 0.36%   |
| 5200  | 1        | 0.36%   |
| 4133  | 1        | 0.36%   |
| 4000  | 1        | 0.36%   |
| 3933  | 1        | 0.36%   |
| 3733  | 1        | 0.36%   |
| 3534  | 1        | 0.36%   |
| 3500  | 1        | 0.36%   |
| 3467  | 1        | 0.36%   |
| 3466  | 1        | 0.36%   |
| 3400  | 1        | 0.36%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 8        | 32%     |
| Seiko Epson         | 4        | 16%     |
| Canon               | 3        | 12%     |
| Brother Industries  | 3        | 12%     |
| Samsung Electronics | 2        | 8%      |
| Xerox               | 1        | 4%      |
| Prolific Technology | 1        | 4%      |
| Kyocera             | 1        | 4%      |
| Dymo-CoStar         | 1        | 4%      |
| Datamax-O'Neil      | 1        | 4%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Seiko Epson L360 Series               | 2        | 8%      |
| Samsung M2070 Series                  | 2        | 8%      |
| Brother MFC-J460DW                    | 2        | 8%      |
| Xerox Phaser 3140 and 3155            | 1        | 4%      |
| Seiko Epson XP-3100 Series            | 1        | 4%      |
| Seiko Epson L3110 Series              | 1        | 4%      |
| Prolific PL2305 Parallel Port         | 1        | 4%      |
| Kyocera Mita FS-820                   | 1        | 4%      |
| HP OfficeJet 5500 series              | 1        | 4%      |
| HP LaserJet P2015 series              | 1        | 4%      |
| HP LaserJet 1022                      | 1        | 4%      |
| HP LaserJet 1012                      | 1        | 4%      |
| HP ENVY 4500 series                   | 1        | 4%      |
| HP DeskJet D2300                      | 1        | 4%      |
| HP DeskJet 3630 series                | 1        | 4%      |
| HP ColorLaserJet M253-M254            | 1        | 4%      |
| Dymo-CoStar LabelWriter 450           | 1        | 4%      |
| Datamax-O'Neil Datamax E-4304         | 1        | 4%      |
| Canon PIXMA MX470 Series              | 1        | 4%      |
| Canon PIXMA MG5500 Series             | 1        | 4%      |
| Canon LaserShot LBP-1120 Printer      | 1        | 4%      |
| Brother PT-P700 P-touch Label Printer | 1        | 4%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| Canon          | 5        | 71.43%  |
| Seiko Epson    | 1        | 14.29%  |
| Mustek Systems | 1        | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40      | 2        | 28.57%  |
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1        | 14.29%  |
| Mustek Systems ScanExpress A3 USB 1200 PRO  | 1        | 14.29%  |
| Canon CanoScan N670U/N676U/LiDE 20          | 1        | 14.29%  |
| Canon CanoScan LiDE 220                     | 1        | 14.29%  |
| Canon CanoScan LiDE 210                     | 1        | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 46       | 44.23%  |
| Microdia                      | 8        | 7.69%   |
| Microsoft                     | 5        | 4.81%   |
| Generalplus Technology        | 5        | 4.81%   |
| Sunplus Innovation Technology | 4        | 3.85%   |
| Samsung Electronics           | 4        | 3.85%   |
| Realtek Semiconductor         | 3        | 2.88%   |
| KYE Systems (Mouse Systems)   | 3        | 2.88%   |
| Cubeternet                    | 3        | 2.88%   |
| Unknown                       | 2        | 1.92%   |
| Jieli Technology              | 2        | 1.92%   |
| ARC International             | 2        | 1.92%   |
| Alcor Micro                   | 2        | 1.92%   |
| YGTek                         | 1        | 0.96%   |
| Trust                         | 1        | 0.96%   |
| SunplusIT                     | 1        | 0.96%   |
| Sonix Technology              | 1        | 0.96%   |
| Silicon Motion                | 1        | 0.96%   |
| Razer USA                     | 1        | 0.96%   |
| MacroSilicon                  | 1        | 0.96%   |
| LG Electronics                | 1        | 0.96%   |
| IMC Networks                  | 1        | 0.96%   |
| Hewlett-Packard               | 1        | 0.96%   |
| Google                        | 1        | 0.96%   |
| GEMBIRD                       | 1        | 0.96%   |
| Creative Technology           | 1        | 0.96%   |
| Chicony Electronics           | 1        | 0.96%   |
| Asuscom Network               | 1        | 0.96%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                | 11       | 10.58%  |
| Logitech Webcam C270                       | 8        | 7.69%   |
| Samsung Galaxy series, misc. (MTP mode)    | 4        | 3.85%   |
| Logitech C920 PRO HD Webcam                | 4        | 3.85%   |
| Microdia Integrated Camera                 | 3        | 2.88%   |
| Logitech HD Webcam C910                    | 3        | 2.88%   |
| Logitech HD Webcam C525                    | 3        | 2.88%   |
| Logitech C922 Pro Stream Webcam            | 3        | 2.88%   |
| Unknown HD camera                          | 2        | 1.92%   |
| Microsoft LifeCam HD-3000                  | 2        | 1.92%   |
| Microdia Webcam Vitade AF                  | 2        | 1.92%   |
| Logitech Webcam C170                       | 2        | 1.92%   |
| Logitech QuickCam Pro 9000                 | 2        | 1.92%   |
| Logitech HD Webcam C615                    | 2        | 1.92%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera | 2        | 1.92%   |
| Jieli USB PHY 2.0                          | 2        | 1.92%   |
| Generalplus WEB CAM                        | 2        | 1.92%   |
| Generalplus GENERAL WEBCAM                 | 2        | 1.92%   |
| Cubeternet USB2.0 Camera                   | 2        | 1.92%   |
| ARC International Camera                   | 2        | 1.92%   |
| Alcor Micro USB 2.0 PC Camera              | 2        | 1.92%   |
| YGTek Webcam                               | 1        | 0.96%   |
| Trust 17676 Webcam                         | 1        | 0.96%   |
| SunplusIT USB 2.0 Camera                   | 1        | 0.96%   |
| Sunplus SPCA2281 Web Camera                | 1        | 0.96%   |
| Sunplus HD USB Camaer 4K                   | 1        | 0.96%   |
| Sunplus ezcap U3 capture-04                | 1        | 0.96%   |
| Sunplus Aukey-PC-LM1E Camera               | 1        | 0.96%   |
| Sonix USB 2.0 Camera                       | 1        | 0.96%   |
| Silicon Motion 300k Pixel Camera           | 1        | 0.96%   |
| Realtek USB Camera                         | 1        | 0.96%   |
| Realtek NexiGo N660P FHD Webcam            | 1        | 0.96%   |
| Realtek HK 2M CAM                          | 1        | 0.96%   |
| Razer USA Razer Kiyo Pro                   | 1        | 0.96%   |
| Microsoft MicrosoftÂ LifeCam Studio       | 1        | 0.96%   |
| Microsoft LifeCam Studio                   | 1        | 0.96%   |
| Microsoft LifeCam Cinema                   | 1        | 0.96%   |
| Microdia USB 2.0 Camera                    | 1        | 0.96%   |
| Microdia PC Microscope camera              | 1        | 0.96%   |
| Microdia Camera                            | 1        | 0.96%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Synaptics             | 2        | 66.67%  |
| LighTuning Technology | 1        | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Synaptics  WBDI Fingerprint Reader - USB 052 | 2        | 66.67%  |
| LighTuning Fingerprint Sensor                | 1        | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| OmniKey               | 2        | 33.33%  |
| SCM Microsystems      | 1        | 16.67%  |
| Gemalto (was Gemplus) | 1        | 16.67%  |
| Bit4id                | 1        | 16.67%  |
| Alcor Micro           | 1        | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| SCM Microsystems SCR331 SmartCard Reader          | 1        | 16.67%  |
| OmniKey CardMan 3021 / 3121                       | 1        | 16.67%  |
| OmniKey CardMan 1021                              | 1        | 16.67%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1        | 16.67%  |
| Bit4id miniLector EVO                             | 1        | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader               | 1        | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 330      | 80.1%   |
| 1     | 68       | 16.5%   |
| 2     | 11       | 2.67%   |
| 3     | 3        | 0.73%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 27       | 29.03%  |
| Net/wireless             | 26       | 27.96%  |
| Unassigned class         | 13       | 13.98%  |
| Multimedia controller    | 4        | 4.3%    |
| Communication controller | 4        | 4.3%    |
| Chipcard                 | 4        | 4.3%    |
| Camera                   | 4        | 4.3%    |
| Bluetooth                | 4        | 4.3%    |
| Fingerprint reader       | 3        | 3.23%   |
| Sound                    | 2        | 2.15%   |
| Net/ethernet             | 1        | 1.08%   |
| Modem                    | 1        | 1.08%   |

