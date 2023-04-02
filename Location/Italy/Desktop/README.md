Linux in Italy - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------

A project to collect tested hardware configurations for Linux in Italy.

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

Total: 3779

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME Z490-P                | [bbbfbb2dfc](https://linux-hardware.org/?probe=bbbfbb2dfc) | Apr 01, 2023 |
| Intel         | DB75EN AAG39650-303         | [50d4a766a6](https://linux-hardware.org/?probe=50d4a766a6) | Apr 01, 2023 |
| Acer          | H11H4-AI V:1.0              | [d5337ce0e3](https://linux-hardware.org/?probe=d5337ce0e3) | Apr 01, 2023 |
| Acer          | WG43M                       | [77cb0bf517](https://linux-hardware.org/?probe=77cb0bf517) | Apr 01, 2023 |
| MSI           | X570-A PRO                  | [3093c50d3d](https://linux-hardware.org/?probe=3093c50d3d) | Mar 31, 2023 |
| MSI           | B550-A PRO                  | [f243351def](https://linux-hardware.org/?probe=f243351def) | Mar 31, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [871b458080](https://linux-hardware.org/?probe=871b458080) | Mar 31, 2023 |
| Gigabyte      | Z390 M-CF                   | [6bce2b9bc3](https://linux-hardware.org/?probe=6bce2b9bc3) | Mar 31, 2023 |
| DFI           | LP UT X58                   | [cd706d90d3](https://linux-hardware.org/?probe=cd706d90d3) | Mar 30, 2023 |
| Packard Be... | FIH57                       | [f1336c6cc4](https://linux-hardware.org/?probe=f1336c6cc4) | Mar 30, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [4ccaa78b43](https://linux-hardware.org/?probe=4ccaa78b43) | Mar 30, 2023 |
| ASUSTek       | H110M-R                     | [3c641024ba](https://linux-hardware.org/?probe=3c641024ba) | Mar 30, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | [e772d0e916](https://linux-hardware.org/?probe=e772d0e916) | Mar 29, 2023 |
| AZW           | U59                         | [3776cd7fb3](https://linux-hardware.org/?probe=3776cd7fb3) | Mar 29, 2023 |
| AZW           | U59                         | [f7958b8f39](https://linux-hardware.org/?probe=f7958b8f39) | Mar 29, 2023 |
| HP            | 3646h                       | [b173e99a5a](https://linux-hardware.org/?probe=b173e99a5a) | Mar 29, 2023 |
| ASUSTek       | P8Z77-V LX2                 | [23256b54cf](https://linux-hardware.org/?probe=23256b54cf) | Mar 29, 2023 |
| Acer          | H11H4-AI V:1.0              | [4266c0287d](https://linux-hardware.org/?probe=4266c0287d) | Mar 29, 2023 |
| MSI           | X570-A PRO                  | [0921fd9096](https://linux-hardware.org/?probe=0921fd9096) | Mar 28, 2023 |
| MSI           | B450-A PRO MAX              | [f3ebf80a3d](https://linux-hardware.org/?probe=f3ebf80a3d) | Mar 28, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | [5ac9dd16da](https://linux-hardware.org/?probe=5ac9dd16da) | Mar 28, 2023 |
| HP            | 18E6                        | [a406dc2463](https://linux-hardware.org/?probe=a406dc2463) | Mar 27, 2023 |
| ASUSTek       | X79-DELUXE                  | [da016d15c7](https://linux-hardware.org/?probe=da016d15c7) | Mar 27, 2023 |
| Unknown       | Unknown                     | [6f77d9be36](https://linux-hardware.org/?probe=6f77d9be36) | Mar 26, 2023 |
| Shenzhen M... | HX90G                       | [fb3f1be00d](https://linux-hardware.org/?probe=fb3f1be00d) | Mar 26, 2023 |
| MSI           | B550-A PRO                  | [eddf5a759a](https://linux-hardware.org/?probe=eddf5a759a) | Mar 26, 2023 |
| ASRock        | H61M-DGS                    | [76fc7291a6](https://linux-hardware.org/?probe=76fc7291a6) | Mar 26, 2023 |
| Acer          | Veriton M2631 V:1.0         | [4a4f12631a](https://linux-hardware.org/?probe=4a4f12631a) | Mar 26, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [c7e347798a](https://linux-hardware.org/?probe=c7e347798a) | Mar 26, 2023 |
| ASUSTek       | STRIX Z270I GAMING          | [4253088a92](https://linux-hardware.org/?probe=4253088a92) | Mar 25, 2023 |
| MSI           | Z170A PC MATE               | [ad4b4f6a8f](https://linux-hardware.org/?probe=ad4b4f6a8f) | Mar 25, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | [bf5cc186ea](https://linux-hardware.org/?probe=bf5cc186ea) | Mar 25, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [518cef7fe4](https://linux-hardware.org/?probe=518cef7fe4) | Mar 24, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [dc56fbfedb](https://linux-hardware.org/?probe=dc56fbfedb) | Mar 24, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [67d60d55e4](https://linux-hardware.org/?probe=67d60d55e4) | Mar 24, 2023 |
| ASUSTek       | P8P67 PRO                   | [7ed577df49](https://linux-hardware.org/?probe=7ed577df49) | Mar 23, 2023 |
| MSI           | Z590-A PRO                  | [ad6a144db9](https://linux-hardware.org/?probe=ad6a144db9) | Mar 23, 2023 |
| Lenovo        | SDK0F82993 WIN              | [fbff3ec47c](https://linux-hardware.org/?probe=fbff3ec47c) | Mar 23, 2023 |
| Gigabyte      | H81M-S2PV                   | [ac856abadc](https://linux-hardware.org/?probe=ac856abadc) | Mar 21, 2023 |
| ASRock        | B550M Pro4                  | [de1c89d1b0](https://linux-hardware.org/?probe=de1c89d1b0) | Mar 21, 2023 |
| Dell          | 0D441T A03                  | [926d18b722](https://linux-hardware.org/?probe=926d18b722) | Mar 20, 2023 |
| Acer          | Veriton M4610G              | [fed7efcecb](https://linux-hardware.org/?probe=fed7efcecb) | Mar 20, 2023 |
| Techvision    | TVI7309X B0                 | [67b681a703](https://linux-hardware.org/?probe=67b681a703) | Mar 20, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [42290142fb](https://linux-hardware.org/?probe=42290142fb) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [3500d84a8e](https://linux-hardware.org/?probe=3500d84a8e) | Mar 19, 2023 |
| ASRock        | H61M-DGS                    | [2b86166550](https://linux-hardware.org/?probe=2b86166550) | Mar 19, 2023 |
| Gigabyte      | 970A-DS3P                   | [727e5c46b7](https://linux-hardware.org/?probe=727e5c46b7) | Mar 18, 2023 |
| MSI           | H55M-P31                    | [e95e62df99](https://linux-hardware.org/?probe=e95e62df99) | Mar 18, 2023 |
| HP            | 18E7                        | [9f4d303ffa](https://linux-hardware.org/?probe=9f4d303ffa) | Mar 18, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [b346ffbe8e](https://linux-hardware.org/?probe=b346ffbe8e) | Mar 18, 2023 |
| ASUSTek       | TUF B350M-PLUS GAMING       | [be6db6cc62](https://linux-hardware.org/?probe=be6db6cc62) | Mar 17, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [7298c4b04b](https://linux-hardware.org/?probe=7298c4b04b) | Mar 17, 2023 |
| AMI           | Intel                       | [491d2cca9d](https://linux-hardware.org/?probe=491d2cca9d) | Mar 17, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [794bc239ab](https://linux-hardware.org/?probe=794bc239ab) | Mar 17, 2023 |
| MSI           | B550-A PRO                  | [730eec29f4](https://linux-hardware.org/?probe=730eec29f4) | Mar 16, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [37f8d341e3](https://linux-hardware.org/?probe=37f8d341e3) | Mar 14, 2023 |
| ASUSTek       | H61M-K                      | [783ff991d4](https://linux-hardware.org/?probe=783ff991d4) | Mar 14, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [ce69431d69](https://linux-hardware.org/?probe=ce69431d69) | Mar 14, 2023 |
| ASUSTek       | Rampage V EXTREME           | [e186537a7e](https://linux-hardware.org/?probe=e186537a7e) | Mar 14, 2023 |
| HP            | 18E7                        | [2042edf904](https://linux-hardware.org/?probe=2042edf904) | Mar 12, 2023 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | [a7105953c2](https://linux-hardware.org/?probe=a7105953c2) | Mar 12, 2023 |
| MSI           | P55-CD53                    | [d492118b16](https://linux-hardware.org/?probe=d492118b16) | Mar 12, 2023 |
| ASRock        | B460M Pro4                  | [50e790583a](https://linux-hardware.org/?probe=50e790583a) | Mar 12, 2023 |
| ASRock        | B450 Pro4                   | [4dd7be5be9](https://linux-hardware.org/?probe=4dd7be5be9) | Mar 12, 2023 |
| ASRock        | B450 Pro4                   | [ce0343a044](https://linux-hardware.org/?probe=ce0343a044) | Mar 12, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [17431ae177](https://linux-hardware.org/?probe=17431ae177) | Mar 12, 2023 |
| Dell          | 0P03DX A04                  | [e1c38bafaa](https://linux-hardware.org/?probe=e1c38bafaa) | Mar 11, 2023 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | [b7de8d093d](https://linux-hardware.org/?probe=b7de8d093d) | Mar 11, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [278b9e10a7](https://linux-hardware.org/?probe=278b9e10a7) | Mar 11, 2023 |
| Dell          | 0HY9JP A00                  | [caaa97e4ba](https://linux-hardware.org/?probe=caaa97e4ba) | Mar 11, 2023 |
| MSI           | Z590-A PRO                  | [c0c43b3296](https://linux-hardware.org/?probe=c0c43b3296) | Mar 11, 2023 |
| Acer          | Aspire TC-380               | [563bd52487](https://linux-hardware.org/?probe=563bd52487) | Mar 10, 2023 |
| ASRock        | H410M-HVS                   | [689186d7de](https://linux-hardware.org/?probe=689186d7de) | Mar 10, 2023 |
| MSI           | B550-A PRO                  | [493a2b9df6](https://linux-hardware.org/?probe=493a2b9df6) | Mar 10, 2023 |
| Gigabyte      | Z370N WIFI-CF               | [0fb1309bff](https://linux-hardware.org/?probe=0fb1309bff) | Mar 10, 2023 |
| HP            | 2B35                        | [ddb4d051ab](https://linux-hardware.org/?probe=ddb4d051ab) | Mar 09, 2023 |
| HP            | 2B35                        | [83f9096b77](https://linux-hardware.org/?probe=83f9096b77) | Mar 09, 2023 |
| MSI           | 970A-G46                    | [322eb2bdf0](https://linux-hardware.org/?probe=322eb2bdf0) | Mar 09, 2023 |
| Acer          | Veriton M480                | [8cd45e8525](https://linux-hardware.org/?probe=8cd45e8525) | Mar 09, 2023 |
| ASRock        | H61M-ITX                    | [ab7e81c6ca](https://linux-hardware.org/?probe=ab7e81c6ca) | Mar 09, 2023 |
| HP            | 8433 11                     | [95f33803c0](https://linux-hardware.org/?probe=95f33803c0) | Mar 08, 2023 |
| ASRock        | 970 Performance             | [c018d98ddc](https://linux-hardware.org/?probe=c018d98ddc) | Mar 08, 2023 |
| ASUSTek       | H81T                        | [c17251dbd9](https://linux-hardware.org/?probe=c17251dbd9) | Mar 08, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [3629efc5a5](https://linux-hardware.org/?probe=3629efc5a5) | Mar 08, 2023 |
| Gigabyte      | A320M-S2H-CF                | [00ddbf4ad1](https://linux-hardware.org/?probe=00ddbf4ad1) | Mar 07, 2023 |
| Acer          | Veriton X4610G              | [7f5cb2ac6a](https://linux-hardware.org/?probe=7f5cb2ac6a) | Mar 07, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [ced1079ce2](https://linux-hardware.org/?probe=ced1079ce2) | Mar 07, 2023 |
| Lenovo        | MAHOBAY                     | [e4e709f69a](https://linux-hardware.org/?probe=e4e709f69a) | Mar 07, 2023 |
| Acer          | H11H4-AI V:1.0              | [ff1a57749f](https://linux-hardware.org/?probe=ff1a57749f) | Mar 07, 2023 |
| Acer          | H11H4-AI V:1.0              | [37f7cabb58](https://linux-hardware.org/?probe=37f7cabb58) | Mar 07, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [ad0dbd5503](https://linux-hardware.org/?probe=ad0dbd5503) | Mar 06, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [0f36c1b0f7](https://linux-hardware.org/?probe=0f36c1b0f7) | Mar 06, 2023 |
| ASRock        | G31M-S                      | [69f88597a5](https://linux-hardware.org/?probe=69f88597a5) | Mar 05, 2023 |
| ASUSTek       | PRIME A320I-K               | [88e6308c0a](https://linux-hardware.org/?probe=88e6308c0a) | Mar 05, 2023 |
| AZW           | U59                         | [7711289a77](https://linux-hardware.org/?probe=7711289a77) | Mar 05, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [109fa85017](https://linux-hardware.org/?probe=109fa85017) | Mar 05, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [0d99cfc372](https://linux-hardware.org/?probe=0d99cfc372) | Mar 05, 2023 |
| MSI           | B450M MORTAR MAX            | [f8eea076e5](https://linux-hardware.org/?probe=f8eea076e5) | Mar 05, 2023 |
| HP            | 3397                        | [5250af801f](https://linux-hardware.org/?probe=5250af801f) | Mar 04, 2023 |
| ASUSTek       | P8H67                       | [99008935e9](https://linux-hardware.org/?probe=99008935e9) | Mar 04, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [860f53436b](https://linux-hardware.org/?probe=860f53436b) | Mar 03, 2023 |
| Gigabyte      | X570S AERO G                | [7e85150e30](https://linux-hardware.org/?probe=7e85150e30) | Mar 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [bdfb7a4647](https://linux-hardware.org/?probe=bdfb7a4647) | Mar 03, 2023 |
| AMI           | Intel                       | [b6d932a0ed](https://linux-hardware.org/?probe=b6d932a0ed) | Mar 02, 2023 |
| ASRock        | B365 Pro4                   | [16875fc443](https://linux-hardware.org/?probe=16875fc443) | Mar 02, 2023 |
| ASUSTek       | TUF Gaming H470-PRO         | [14a44a0392](https://linux-hardware.org/?probe=14a44a0392) | Mar 02, 2023 |
| Acer          | FIH57                       | [3f9c79675c](https://linux-hardware.org/?probe=3f9c79675c) | Mar 01, 2023 |
| HP            | 3396                        | [2da0f889cb](https://linux-hardware.org/?probe=2da0f889cb) | Mar 01, 2023 |
| ASUSTek       | SABERTOOTH P67              | [fa7df5da3b](https://linux-hardware.org/?probe=fa7df5da3b) | Mar 01, 2023 |
| ASUSTek       | BT6130                      | [dabd3e0232](https://linux-hardware.org/?probe=dabd3e0232) | Mar 01, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [4e701d495f](https://linux-hardware.org/?probe=4e701d495f) | Mar 01, 2023 |
| ASUSTek       | BT6130                      | [db5b346bd5](https://linux-hardware.org/?probe=db5b346bd5) | Feb 28, 2023 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | [6f1de5f17c](https://linux-hardware.org/?probe=6f1de5f17c) | Feb 28, 2023 |
| ASUSTek       | BT6130                      | [3549cfad14](https://linux-hardware.org/?probe=3549cfad14) | Feb 27, 2023 |
| ASUSTek       | M4N68T-M-V2                 | [051b66987e](https://linux-hardware.org/?probe=051b66987e) | Feb 27, 2023 |
| Cincoze       | DX-1000.01.001              | [64496d4ab7](https://linux-hardware.org/?probe=64496d4ab7) | Feb 27, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [580db05e08](https://linux-hardware.org/?probe=580db05e08) | Feb 27, 2023 |
| Cincoze       | DX-1000.01.001              | [7923f1dc21](https://linux-hardware.org/?probe=7923f1dc21) | Feb 26, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [310a65baea](https://linux-hardware.org/?probe=310a65baea) | Feb 26, 2023 |
| ASRock        | G41C-GS                     | [6a698dda57](https://linux-hardware.org/?probe=6a698dda57) | Feb 26, 2023 |
| ASUSTek       | PRIME X370-PRO              | [aaa112feae](https://linux-hardware.org/?probe=aaa112feae) | Feb 26, 2023 |
| Gigabyte      | B250M-D3H-CF                | [de180bd339](https://linux-hardware.org/?probe=de180bd339) | Feb 25, 2023 |
| ASUSTek       | PRIME H610M-R D4            | [3f2e38e322](https://linux-hardware.org/?probe=3f2e38e322) | Feb 25, 2023 |
| Gigabyte      | Z77MX-D3H                   | [bfd1042a82](https://linux-hardware.org/?probe=bfd1042a82) | Feb 25, 2023 |
| Unknown       | 1.0                         | [69594c956a](https://linux-hardware.org/?probe=69594c956a) | Feb 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d8b9174fba](https://linux-hardware.org/?probe=d8b9174fba) | Feb 25, 2023 |
| Unknown       | 1.0                         | [bab30a1ac1](https://linux-hardware.org/?probe=bab30a1ac1) | Feb 24, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [ccff1403b0](https://linux-hardware.org/?probe=ccff1403b0) | Feb 24, 2023 |
| ASRock        | Q1900-ITX                   | [4ed48d952c](https://linux-hardware.org/?probe=4ed48d952c) | Feb 24, 2023 |
| ASRock        | Q1900-ITX                   | [874cbd6e13](https://linux-hardware.org/?probe=874cbd6e13) | Feb 24, 2023 |
| ASUSTek       | M4A77T/USB3                 | [6bf574175a](https://linux-hardware.org/?probe=6bf574175a) | Feb 24, 2023 |
| ASRock        | H81M-DGS R2.0               | [2645328f34](https://linux-hardware.org/?probe=2645328f34) | Feb 23, 2023 |
| MSI           | X58 Pro                     | [22509b3e42](https://linux-hardware.org/?probe=22509b3e42) | Feb 23, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [d93c7d5661](https://linux-hardware.org/?probe=d93c7d5661) | Feb 23, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [7cdbd101a4](https://linux-hardware.org/?probe=7cdbd101a4) | Feb 23, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [576a0fc8f5](https://linux-hardware.org/?probe=576a0fc8f5) | Feb 23, 2023 |
| ASUSTek       | LEONITE                     | [2739b3325c](https://linux-hardware.org/?probe=2739b3325c) | Feb 23, 2023 |
| ASUSTek       | P5QL-E                      | [52c9ec67bf](https://linux-hardware.org/?probe=52c9ec67bf) | Feb 23, 2023 |
| ASRock        | B660M Pro RS                | [13560ab66d](https://linux-hardware.org/?probe=13560ab66d) | Feb 22, 2023 |
| ASUSTek       | PRIME H610M-R D4            | [2993295e62](https://linux-hardware.org/?probe=2993295e62) | Feb 22, 2023 |
| ASUSTek       | PRIME H610M-R D4            | [c23f2f53ed](https://linux-hardware.org/?probe=c23f2f53ed) | Feb 21, 2023 |
| Acer          | FIH57                       | [294e04e054](https://linux-hardware.org/?probe=294e04e054) | Feb 21, 2023 |
| VXL           | M6V90AI-VL                  | [935d6b4b24](https://linux-hardware.org/?probe=935d6b4b24) | Feb 21, 2023 |
| ASUSTek       | PRIME Z390-P                | [d81ff5358a](https://linux-hardware.org/?probe=d81ff5358a) | Feb 20, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [656629ffba](https://linux-hardware.org/?probe=656629ffba) | Feb 20, 2023 |
| ASUSTek       | H170-PRO                    | [011dc701c1](https://linux-hardware.org/?probe=011dc701c1) | Feb 20, 2023 |
| ASUSTek       | H81M-PLUS                   | [796ba78b54](https://linux-hardware.org/?probe=796ba78b54) | Feb 20, 2023 |
| ASRock        | 960GC-GS FX                 | [39718b8983](https://linux-hardware.org/?probe=39718b8983) | Feb 20, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [accbe9322f](https://linux-hardware.org/?probe=accbe9322f) | Feb 20, 2023 |
| Packard Be... | IMEDIA S3810                | [472db03bf8](https://linux-hardware.org/?probe=472db03bf8) | Feb 20, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [737c043ed7](https://linux-hardware.org/?probe=737c043ed7) | Feb 20, 2023 |
| Gigabyte      | B560M DS3H                  | [72891de86c](https://linux-hardware.org/?probe=72891de86c) | Feb 20, 2023 |
| ASUSTek       | H81M-PLUS                   | [86f16da5e8](https://linux-hardware.org/?probe=86f16da5e8) | Feb 19, 2023 |
| ASUSTek       | BT6130                      | [470ceee356](https://linux-hardware.org/?probe=470ceee356) | Feb 19, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [2af589c6e9](https://linux-hardware.org/?probe=2af589c6e9) | Feb 19, 2023 |
| Pegatron      | 2AB6                        | [537c2d1b64](https://linux-hardware.org/?probe=537c2d1b64) | Feb 18, 2023 |
| Dell          | 0X9M3X A04                  | [9b13a670c5](https://linux-hardware.org/?probe=9b13a670c5) | Feb 18, 2023 |
| ASUSTek       | PRIME A320M-K               | [105ea39c82](https://linux-hardware.org/?probe=105ea39c82) | Feb 18, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [a62c4f0fcd](https://linux-hardware.org/?probe=a62c4f0fcd) | Feb 18, 2023 |
| MSI           | Z170A KRAIT GAMING          | [27dcbbe1d7](https://linux-hardware.org/?probe=27dcbbe1d7) | Feb 18, 2023 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [0428793835](https://linux-hardware.org/?probe=0428793835) | Feb 18, 2023 |
| ASUSTek       | Rampage Formula             | [61fd1aefee](https://linux-hardware.org/?probe=61fd1aefee) | Feb 17, 2023 |
| ASUSTek       | P8Z77-V                     | [f8dca6a264](https://linux-hardware.org/?probe=f8dca6a264) | Feb 17, 2023 |
| HP            | 2820h                       | [552bdc9930](https://linux-hardware.org/?probe=552bdc9930) | Feb 17, 2023 |
| HP            | 1495                        | [6bc4b54027](https://linux-hardware.org/?probe=6bc4b54027) | Feb 16, 2023 |
| MSI           | Z97-G45 GAMING              | [c6a7d3a755](https://linux-hardware.org/?probe=c6a7d3a755) | Feb 16, 2023 |
| ASRock        | Q1900M                      | [2fc7d5968a](https://linux-hardware.org/?probe=2fc7d5968a) | Feb 16, 2023 |
| ASUSTek       | P5K                         | [7767ce777f](https://linux-hardware.org/?probe=7767ce777f) | Feb 16, 2023 |
| Gigabyte      | H270M-D3H-CF                | [7a58ceb644](https://linux-hardware.org/?probe=7a58ceb644) | Feb 15, 2023 |
| ASUSTek       | BT6130                      | [b0693958a6](https://linux-hardware.org/?probe=b0693958a6) | Feb 15, 2023 |
| Acer          | Veriton X2610G              | [22c65bbb88](https://linux-hardware.org/?probe=22c65bbb88) | Feb 15, 2023 |
| Supermicro    | X10DRG-Q                    | [5af331bc84](https://linux-hardware.org/?probe=5af331bc84) | Feb 15, 2023 |
| HP            | 3396                        | [fbff77d7cc](https://linux-hardware.org/?probe=fbff77d7cc) | Feb 14, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | [49f47896e6](https://linux-hardware.org/?probe=49f47896e6) | Feb 14, 2023 |
| HP            | 18E7                        | [b81cc64550](https://linux-hardware.org/?probe=b81cc64550) | Feb 14, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [34ad4bac16](https://linux-hardware.org/?probe=34ad4bac16) | Feb 13, 2023 |
| ASUSTek       | BT6130                      | [db3b191eb2](https://linux-hardware.org/?probe=db3b191eb2) | Feb 13, 2023 |
| ASUSTek       | M5A78L-M LX3                | [c7374801ac](https://linux-hardware.org/?probe=c7374801ac) | Feb 13, 2023 |
| ASUSTek       | H81M-K                      | [6fe888ea28](https://linux-hardware.org/?probe=6fe888ea28) | Feb 13, 2023 |
| ASRock        | Z370M Pro4                  | [6dfaa1ed56](https://linux-hardware.org/?probe=6dfaa1ed56) | Feb 12, 2023 |
| ASUSTek       | F2A55-M LK2                 | [01ab687841](https://linux-hardware.org/?probe=01ab687841) | Feb 12, 2023 |
| Gigabyte      | Z370 HD3P-CF                | [86ca7a4821](https://linux-hardware.org/?probe=86ca7a4821) | Feb 11, 2023 |
| HP            | 3031h                       | [f9a0848388](https://linux-hardware.org/?probe=f9a0848388) | Feb 11, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [2d776f8810](https://linux-hardware.org/?probe=2d776f8810) | Feb 11, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [7b6a31ec69](https://linux-hardware.org/?probe=7b6a31ec69) | Feb 11, 2023 |
| ASUSTek       | P5K                         | [9f8790812d](https://linux-hardware.org/?probe=9f8790812d) | Feb 11, 2023 |
| Lenovo        | 3098 SDK0J40705 WIN         | [6ada8eb627](https://linux-hardware.org/?probe=6ada8eb627) | Feb 10, 2023 |
| ASRock        | Z170 Extreme6+              | [9b9b84473b](https://linux-hardware.org/?probe=9b9b84473b) | Feb 10, 2023 |
| Intel         | JSL MRD                     | [5a876c1bb0](https://linux-hardware.org/?probe=5a876c1bb0) | Feb 10, 2023 |
| ASUSTek       | M4N78                       | [34ddf02a41](https://linux-hardware.org/?probe=34ddf02a41) | Feb 10, 2023 |
| HP            | 843C                        | [02ddbb64e8](https://linux-hardware.org/?probe=02ddbb64e8) | Feb 09, 2023 |
| MSI           | 2A9C                        | [1332640fbd](https://linux-hardware.org/?probe=1332640fbd) | Feb 09, 2023 |
| Gigabyte      | GA-MA78GM-S2H               | [bbaa8165e4](https://linux-hardware.org/?probe=bbaa8165e4) | Feb 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [69c30e6f7b](https://linux-hardware.org/?probe=69c30e6f7b) | Feb 08, 2023 |
| Dell          | 0Y5FXV A00                  | [692b7eab6b](https://linux-hardware.org/?probe=692b7eab6b) | Feb 08, 2023 |
| ASUSTek       | SABERTOOTH P67              | [1fdf18a3ed](https://linux-hardware.org/?probe=1fdf18a3ed) | Feb 08, 2023 |
| ASRock        | H310M-STX                   | [faadf8b29c](https://linux-hardware.org/?probe=faadf8b29c) | Feb 08, 2023 |
| MSI           | Z390-A PRO                  | [de25a58c23](https://linux-hardware.org/?probe=de25a58c23) | Feb 07, 2023 |
| MSI           | B550-A PRO                  | [cc856dafad](https://linux-hardware.org/?probe=cc856dafad) | Feb 07, 2023 |
| ASUSTek       | Rampage IV EXTREME          | [9a94af0f8a](https://linux-hardware.org/?probe=9a94af0f8a) | Feb 07, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [43c3e4d160](https://linux-hardware.org/?probe=43c3e4d160) | Feb 06, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [00006691a6](https://linux-hardware.org/?probe=00006691a6) | Feb 05, 2023 |
| Acer          | WG43M                       | [e463181f54](https://linux-hardware.org/?probe=e463181f54) | Feb 05, 2023 |
| MSI           | MS-7309                     | [46995d58eb](https://linux-hardware.org/?probe=46995d58eb) | Feb 05, 2023 |
| Intel         | DH55TC AAE70932-301         | [350458a94e](https://linux-hardware.org/?probe=350458a94e) | Feb 05, 2023 |
| HP            | 3397                        | [ea72001991](https://linux-hardware.org/?probe=ea72001991) | Feb 05, 2023 |
| ASRock        | 775Dual-VSTA                | [945a366595](https://linux-hardware.org/?probe=945a366595) | Feb 05, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [944149e350](https://linux-hardware.org/?probe=944149e350) | Feb 04, 2023 |
| MSI           | B550-A PRO                  | [55e2abbd96](https://linux-hardware.org/?probe=55e2abbd96) | Feb 04, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | [91a070c2aa](https://linux-hardware.org/?probe=91a070c2aa) | Feb 03, 2023 |
| Intel         | H61                         | [21fd40e0a1](https://linux-hardware.org/?probe=21fd40e0a1) | Feb 03, 2023 |
| MSI           | B550-A PRO                  | [dc4a285d49](https://linux-hardware.org/?probe=dc4a285d49) | Feb 03, 2023 |
| ASUSTek       | P5GDC                       | [6dbac14e8b](https://linux-hardware.org/?probe=6dbac14e8b) | Feb 03, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [fd8c9d9ccf](https://linux-hardware.org/?probe=fd8c9d9ccf) | Feb 03, 2023 |
| HP            | 834F                        | [394eb5f9cc](https://linux-hardware.org/?probe=394eb5f9cc) | Feb 02, 2023 |
| HP            | 834F                        | [9a4a1839d3](https://linux-hardware.org/?probe=9a4a1839d3) | Feb 02, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [1ca0a608f9](https://linux-hardware.org/?probe=1ca0a608f9) | Feb 02, 2023 |
| Acer          | Veriton M2631 V:1.0         | [28e1975b51](https://linux-hardware.org/?probe=28e1975b51) | Feb 02, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [09430385c6](https://linux-hardware.org/?probe=09430385c6) | Feb 02, 2023 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | [b792043acd](https://linux-hardware.org/?probe=b792043acd) | Feb 01, 2023 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | [48bccd4f38](https://linux-hardware.org/?probe=48bccd4f38) | Feb 01, 2023 |
| Pegatron      | 2A94                        | [58961a542f](https://linux-hardware.org/?probe=58961a542f) | Feb 01, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [f4e30fc177](https://linux-hardware.org/?probe=f4e30fc177) | Jan 31, 2023 |
| ASUSTek       | P5QL PRO                    | [77cc2bd640](https://linux-hardware.org/?probe=77cc2bd640) | Jan 31, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [3c8b3f4e7d](https://linux-hardware.org/?probe=3c8b3f4e7d) | Jan 30, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [3bdb934f29](https://linux-hardware.org/?probe=3bdb934f29) | Jan 30, 2023 |
| Intel         | B75                         | [6597bed6da](https://linux-hardware.org/?probe=6597bed6da) | Jan 29, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [e5f6f546d4](https://linux-hardware.org/?probe=e5f6f546d4) | Jan 29, 2023 |
| ASRock        | B460M Pro4                  | [7af163f694](https://linux-hardware.org/?probe=7af163f694) | Jan 29, 2023 |
| MSI           | P55-CD53                    | [7c46f17179](https://linux-hardware.org/?probe=7c46f17179) | Jan 29, 2023 |
| ASRock        | H610M-HVS                   | [2774d547be](https://linux-hardware.org/?probe=2774d547be) | Jan 29, 2023 |
| ASRock        | B460M Pro4                  | [37c0fb77f5](https://linux-hardware.org/?probe=37c0fb77f5) | Jan 29, 2023 |
| ASUSTek       | F2A55-M LK2                 | [8bf2fa8d9b](https://linux-hardware.org/?probe=8bf2fa8d9b) | Jan 28, 2023 |
| Dell          | 0HD5W2 A00                  | [890cad48c3](https://linux-hardware.org/?probe=890cad48c3) | Jan 28, 2023 |
| Gigabyte      | B450M DS3H-CF               | [8f6ea9ffff](https://linux-hardware.org/?probe=8f6ea9ffff) | Jan 28, 2023 |
| ASUSTek       | H110M-K                     | [73b3f84699](https://linux-hardware.org/?probe=73b3f84699) | Jan 28, 2023 |
| ASUSTek       | H61M-K                      | [312e07a824](https://linux-hardware.org/?probe=312e07a824) | Jan 28, 2023 |
| ASRock        | H61M-DGS                    | [825e70e660](https://linux-hardware.org/?probe=825e70e660) | Jan 27, 2023 |
| ASUSTek       | PRIME A320M-K               | [6f449734a9](https://linux-hardware.org/?probe=6f449734a9) | Jan 26, 2023 |
| Gigabyte      | Z370P D3-CF                 | [90f37ac742](https://linux-hardware.org/?probe=90f37ac742) | Jan 26, 2023 |
| Gigabyte      | Z370P D3-CF                 | [e524d7c4d9](https://linux-hardware.org/?probe=e524d7c4d9) | Jan 26, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [01e47b07a8](https://linux-hardware.org/?probe=01e47b07a8) | Jan 26, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [4ae098906f](https://linux-hardware.org/?probe=4ae098906f) | Jan 26, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [8128876a22](https://linux-hardware.org/?probe=8128876a22) | Jan 26, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [c216d513a0](https://linux-hardware.org/?probe=c216d513a0) | Jan 25, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [06b972165b](https://linux-hardware.org/?probe=06b972165b) | Jan 25, 2023 |
| ASRock        | H61M-DGS                    | [5672937ec6](https://linux-hardware.org/?probe=5672937ec6) | Jan 25, 2023 |
| ASUSTek       | PRIME B560M-A               | [78a1bfaac7](https://linux-hardware.org/?probe=78a1bfaac7) | Jan 25, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [596316a81c](https://linux-hardware.org/?probe=596316a81c) | Jan 25, 2023 |
| ASUSTek       | B150M-A/M.2                 | [edb16eafc7](https://linux-hardware.org/?probe=edb16eafc7) | Jan 25, 2023 |
| MSI           | Z390-A PRO                  | [28c31b639b](https://linux-hardware.org/?probe=28c31b639b) | Jan 25, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [3e1520340a](https://linux-hardware.org/?probe=3e1520340a) | Jan 25, 2023 |
| MSI           | Boston                      | [456d7782ad](https://linux-hardware.org/?probe=456d7782ad) | Jan 24, 2023 |
| MSI           | P55-CD53                    | [7c3a675f94](https://linux-hardware.org/?probe=7c3a675f94) | Jan 24, 2023 |
| ASRock        | Z87 Pro3                    | [0ab0dbb821](https://linux-hardware.org/?probe=0ab0dbb821) | Jan 23, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [996a0567b6](https://linux-hardware.org/?probe=996a0567b6) | Jan 23, 2023 |
| Packard Be... | EG43M                       | [92810508a2](https://linux-hardware.org/?probe=92810508a2) | Jan 23, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [d0f4730f71](https://linux-hardware.org/?probe=d0f4730f71) | Jan 23, 2023 |
| T-bao         | MINI PC V1.0                | [6d1c897198](https://linux-hardware.org/?probe=6d1c897198) | Jan 23, 2023 |
| ASRock        | H61M                        | [f5b1db73f7](https://linux-hardware.org/?probe=f5b1db73f7) | Jan 22, 2023 |
| HP            | 8433 11                     | [a5c598c4c5](https://linux-hardware.org/?probe=a5c598c4c5) | Jan 22, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [b919144e1c](https://linux-hardware.org/?probe=b919144e1c) | Jan 22, 2023 |
| ASRock        | G31M-S                      | [dbf8922f3a](https://linux-hardware.org/?probe=dbf8922f3a) | Jan 22, 2023 |
| MSI           | Boston                      | [34413408ce](https://linux-hardware.org/?probe=34413408ce) | Jan 22, 2023 |
| Dell          | 0YXT71 A02                  | [5d3b4c4823](https://linux-hardware.org/?probe=5d3b4c4823) | Jan 22, 2023 |
| ASUSTek       | P5KPL-AM EPU                | [0aa5260ed0](https://linux-hardware.org/?probe=0aa5260ed0) | Jan 22, 2023 |
| ASUSTek       | P5KPL-AM EPU                | [7389389089](https://linux-hardware.org/?probe=7389389089) | Jan 22, 2023 |
| ASRock        | X370 Pro4                   | [6a8cc962ad](https://linux-hardware.org/?probe=6a8cc962ad) | Jan 22, 2023 |
| ASRock        | B365 Pro4                   | [44fa1b3713](https://linux-hardware.org/?probe=44fa1b3713) | Jan 22, 2023 |
| Lenovo        | ThinkCentre M57e 7066W57    | [3ddcdbb616](https://linux-hardware.org/?probe=3ddcdbb616) | Jan 22, 2023 |
| Gigabyte      | Z77MX-D3H                   | [2142d5e771](https://linux-hardware.org/?probe=2142d5e771) | Jan 22, 2023 |
| Gigabyte      | Z77MX-D3H                   | [80d8c352b9](https://linux-hardware.org/?probe=80d8c352b9) | Jan 22, 2023 |
| HP            | 1497                        | [5f7e021023](https://linux-hardware.org/?probe=5f7e021023) | Jan 22, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [0bf19053f1](https://linux-hardware.org/?probe=0bf19053f1) | Jan 21, 2023 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [9229e3b2ae](https://linux-hardware.org/?probe=9229e3b2ae) | Jan 21, 2023 |
| ASUSTek       | P5KPL-AM EPU                | [62dc562b9e](https://linux-hardware.org/?probe=62dc562b9e) | Jan 21, 2023 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | [eb57bb7cd7](https://linux-hardware.org/?probe=eb57bb7cd7) | Jan 21, 2023 |
| ASUSTek       | H170I-PLUS D3               | [b8d373b07e](https://linux-hardware.org/?probe=b8d373b07e) | Jan 21, 2023 |
| ASRock        | H61M-VG3                    | [c9d6e1cbb1](https://linux-hardware.org/?probe=c9d6e1cbb1) | Jan 21, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [3432d7c1f5](https://linux-hardware.org/?probe=3432d7c1f5) | Jan 20, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [2e73bc84e7](https://linux-hardware.org/?probe=2e73bc84e7) | Jan 20, 2023 |
| ASUSTek       | P7P55D-E                    | [6bc203c6fd](https://linux-hardware.org/?probe=6bc203c6fd) | Jan 19, 2023 |
| ASUSTek       | Z77-A                       | [10081492a7](https://linux-hardware.org/?probe=10081492a7) | Jan 19, 2023 |
| ASUSTek       | PRIME H610M-R D4            | [2e54ccac4d](https://linux-hardware.org/?probe=2e54ccac4d) | Jan 19, 2023 |
| ASUSTek       | PRIME H610M-R D4            | [763f4cb45f](https://linux-hardware.org/?probe=763f4cb45f) | Jan 18, 2023 |
| ASUSTek       | PRIME A320M-K               | [dcf9186db1](https://linux-hardware.org/?probe=dcf9186db1) | Jan 18, 2023 |
| ASRock        | G31M-S                      | [d3aa4e7eea](https://linux-hardware.org/?probe=d3aa4e7eea) | Jan 18, 2023 |
| MSI           | Z170A GAMING M7             | [d58a30b560](https://linux-hardware.org/?probe=d58a30b560) | Jan 18, 2023 |
| MSI           | B150M PRO-VDH               | [4e8759fda2](https://linux-hardware.org/?probe=4e8759fda2) | Jan 18, 2023 |
| ASRock        | Z170 Gaming K4              | [44a3d49ef1](https://linux-hardware.org/?probe=44a3d49ef1) | Jan 18, 2023 |
| MSI           | B150M PRO-VDH               | [d1310959ea](https://linux-hardware.org/?probe=d1310959ea) | Jan 17, 2023 |
| Lenovo        | ThinkStation C20 4263BA7    | [52c1a6c197](https://linux-hardware.org/?probe=52c1a6c197) | Jan 17, 2023 |
| Gigabyte      | B450M DS3H-CF               | [b9f958e5c4](https://linux-hardware.org/?probe=b9f958e5c4) | Jan 17, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [d78fd14781](https://linux-hardware.org/?probe=d78fd14781) | Jan 17, 2023 |
| Unknown       | T3 MRD                      | [df73fafeb7](https://linux-hardware.org/?probe=df73fafeb7) | Jan 17, 2023 |
| ASUSTek       | Rampage IV EXTREME          | [4d4b18a5b3](https://linux-hardware.org/?probe=4d4b18a5b3) | Jan 16, 2023 |
| ASUSTek       | PRIME B460M-A               | [25cbbcfc98](https://linux-hardware.org/?probe=25cbbcfc98) | Jan 16, 2023 |
| ASUSTek       | P5Q PRO TURBO               | [1dd0101330](https://linux-hardware.org/?probe=1dd0101330) | Jan 16, 2023 |
| Dell          | 0WMJ54 A01                  | [fece850cae](https://linux-hardware.org/?probe=fece850cae) | Jan 15, 2023 |
| Gigabyte      | Z97X-Gaming G1              | [58c875e5d5](https://linux-hardware.org/?probe=58c875e5d5) | Jan 15, 2023 |
| Gigabyte      | Z370P D3-CF                 | [084cfebfdb](https://linux-hardware.org/?probe=084cfebfdb) | Jan 15, 2023 |
| Gigabyte      | Z370P D3-CF                 | [f8c56a73c0](https://linux-hardware.org/?probe=f8c56a73c0) | Jan 15, 2023 |
| Gigabyte      | X570S AERO G                | [d30e9b41ef](https://linux-hardware.org/?probe=d30e9b41ef) | Jan 15, 2023 |
| Gigabyte      | X570S AERO G                | [a265db8e50](https://linux-hardware.org/?probe=a265db8e50) | Jan 15, 2023 |
| ASUSTek       | TUF Gaming H470-PRO         | [6d67c981b3](https://linux-hardware.org/?probe=6d67c981b3) | Jan 15, 2023 |
| ASRock        | 775Dual-VSTA                | [7b8818c038](https://linux-hardware.org/?probe=7b8818c038) | Jan 15, 2023 |
| ASRock        | 775Dual-VSTA                | [74dfb9a261](https://linux-hardware.org/?probe=74dfb9a261) | Jan 15, 2023 |
| Lenovo        | SDK0F82993 WIN              | [48f294dfb4](https://linux-hardware.org/?probe=48f294dfb4) | Jan 15, 2023 |
| Pegatron      | 2AD5                        | [d41fde4498](https://linux-hardware.org/?probe=d41fde4498) | Jan 15, 2023 |
| Dell          | 0D24M8 A01                  | [d4cc07d2d2](https://linux-hardware.org/?probe=d4cc07d2d2) | Jan 14, 2023 |
| HP            | 8753                        | [5cdf3ef632](https://linux-hardware.org/?probe=5cdf3ef632) | Jan 14, 2023 |
| MSI           | Z370 GAMING PRO CARBON      | [05f1e26e96](https://linux-hardware.org/?probe=05f1e26e96) | Jan 13, 2023 |
| Dell          | 0WG261                      | [c994d9e8ee](https://linux-hardware.org/?probe=c994d9e8ee) | Jan 13, 2023 |
| ASUSTek       | H110M-R                     | [1318c97f67](https://linux-hardware.org/?probe=1318c97f67) | Jan 13, 2023 |
| ASUSTek       | H110M-R                     | [a86e03551c](https://linux-hardware.org/?probe=a86e03551c) | Jan 13, 2023 |
| Dell          | 0WG261                      | [5d1fe40a1f](https://linux-hardware.org/?probe=5d1fe40a1f) | Jan 13, 2023 |
| ASUSTek       | P8Z77-V LX2                 | [64808b5735](https://linux-hardware.org/?probe=64808b5735) | Jan 12, 2023 |
| Pegatron      | 2ACF                        | [611b2fb2a3](https://linux-hardware.org/?probe=611b2fb2a3) | Jan 12, 2023 |
| AOpen         | D1007 0BBA                  | [63a1413fa3](https://linux-hardware.org/?probe=63a1413fa3) | Jan 12, 2023 |
| Gigabyte      | Z790 AERO G                 | [0d6b77da1a](https://linux-hardware.org/?probe=0d6b77da1a) | Jan 11, 2023 |
| ASUSTek       | PRIME B360M-A               | [75584dc48c](https://linux-hardware.org/?probe=75584dc48c) | Jan 11, 2023 |
| Acer          | Veriton X2640G V:1.0        | [0daf81fe54](https://linux-hardware.org/?probe=0daf81fe54) | Jan 11, 2023 |
| HP            | 8767 A                      | [7b2c61c215](https://linux-hardware.org/?probe=7b2c61c215) | Jan 11, 2023 |
| ASUSTek       | BT6130                      | [53c9ec0145](https://linux-hardware.org/?probe=53c9ec0145) | Jan 10, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | [71f6d7912a](https://linux-hardware.org/?probe=71f6d7912a) | Jan 10, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [0d0a198245](https://linux-hardware.org/?probe=0d0a198245) | Jan 10, 2023 |
| ASRockRack    | EPC602D8A                   | [2d1d53f993](https://linux-hardware.org/?probe=2d1d53f993) | Jan 10, 2023 |
| MSI           | B450M MORTAR MAX            | [36530dbc41](https://linux-hardware.org/?probe=36530dbc41) | Jan 10, 2023 |
| MSI           | H310M PRO-D                 | [1ba0a170aa](https://linux-hardware.org/?probe=1ba0a170aa) | Jan 09, 2023 |
| MSI           | MS-7378                     | [965cd11e84](https://linux-hardware.org/?probe=965cd11e84) | Jan 09, 2023 |
| MSI           | Z77A-GD65                   | [f4b0c86cfa](https://linux-hardware.org/?probe=f4b0c86cfa) | Jan 09, 2023 |
| MSI           | MAG B550M MORTAR            | [1549344aef](https://linux-hardware.org/?probe=1549344aef) | Jan 09, 2023 |
| ASRock        | H87 Performance             | [8e1b7a9033](https://linux-hardware.org/?probe=8e1b7a9033) | Jan 09, 2023 |
| MSI           | H310M PRO-D                 | [e5a8783118](https://linux-hardware.org/?probe=e5a8783118) | Jan 09, 2023 |
| ASRock        | 980DE3/U3S3                 | [92d7b143d8](https://linux-hardware.org/?probe=92d7b143d8) | Jan 09, 2023 |
| ASRock        | X370 Gaming K4              | [0ed2f96ba8](https://linux-hardware.org/?probe=0ed2f96ba8) | Jan 09, 2023 |
| ASUSTek       | M5A97 R2.0                  | [ca7597c4fb](https://linux-hardware.org/?probe=ca7597c4fb) | Jan 08, 2023 |
| Gigabyte      | 990XA-UD3                   | [1c85ed2f4b](https://linux-hardware.org/?probe=1c85ed2f4b) | Jan 08, 2023 |
| Gigabyte      | A520M S2H                   | [a303af0bcf](https://linux-hardware.org/?probe=a303af0bcf) | Jan 08, 2023 |
| Gigabyte      | X570S AERO G                | [75def9e004](https://linux-hardware.org/?probe=75def9e004) | Jan 07, 2023 |
| Acer          | Veriton N2620G              | [6345424cff](https://linux-hardware.org/?probe=6345424cff) | Jan 07, 2023 |
| Gigabyte      | X570S AERO G                | [c5a401b596](https://linux-hardware.org/?probe=c5a401b596) | Jan 07, 2023 |
| ASRock        | Q1900-ITX                   | [ac7df499e8](https://linux-hardware.org/?probe=ac7df499e8) | Jan 07, 2023 |
| HP            | 8399                        | [eccd5189f5](https://linux-hardware.org/?probe=eccd5189f5) | Jan 07, 2023 |
| HP            | 89D8 SMVB                   | [dac20769fc](https://linux-hardware.org/?probe=dac20769fc) | Jan 07, 2023 |
| Acer          | Veriton M2631G V:1.0        | [ebbcc0dda8](https://linux-hardware.org/?probe=ebbcc0dda8) | Jan 07, 2023 |
| HP            | ProLiant MicroServer        | [4bdffcda7f](https://linux-hardware.org/?probe=4bdffcda7f) | Jan 07, 2023 |
| Intel         | DH61DL AAG14066-205         | [81431f1578](https://linux-hardware.org/?probe=81431f1578) | Jan 06, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [ce4648337e](https://linux-hardware.org/?probe=ce4648337e) | Jan 05, 2023 |
| Acer          | Veriton M2631G V:1.0        | [ddeffc27a7](https://linux-hardware.org/?probe=ddeffc27a7) | Jan 05, 2023 |
| Gigabyte      | B560M DS3H                  | [667c8405f0](https://linux-hardware.org/?probe=667c8405f0) | Jan 05, 2023 |
| ASRock        | H410M-HVS                   | [922db531b3](https://linux-hardware.org/?probe=922db531b3) | Jan 05, 2023 |
| Intel         | B75                         | [bb046d2540](https://linux-hardware.org/?probe=bb046d2540) | Jan 04, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [7655f77ada](https://linux-hardware.org/?probe=7655f77ada) | Jan 04, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [0e9393e884](https://linux-hardware.org/?probe=0e9393e884) | Jan 03, 2023 |
| ASRock        | N68C-S UCC                  | [31dfc11401](https://linux-hardware.org/?probe=31dfc11401) | Jan 03, 2023 |
| ASRock        | N68C-S UCC                  | [1497921a99](https://linux-hardware.org/?probe=1497921a99) | Jan 03, 2023 |
| Dell          | 0VHWTR A02                  | [0d9d6203e1](https://linux-hardware.org/?probe=0d9d6203e1) | Jan 03, 2023 |
| ASRock        | H77M                        | [b7f415926b](https://linux-hardware.org/?probe=b7f415926b) | Jan 03, 2023 |
| ASRock        | H77M                        | [82c399688f](https://linux-hardware.org/?probe=82c399688f) | Jan 03, 2023 |
| ASRock        | FM2A55M-VG3+                | [741f0d79a1](https://linux-hardware.org/?probe=741f0d79a1) | Jan 03, 2023 |
| Pegatron      | Benicia                     | [008e5d125e](https://linux-hardware.org/?probe=008e5d125e) | Jan 03, 2023 |
| Pegatron      | Benicia                     | [0d47a13713](https://linux-hardware.org/?probe=0d47a13713) | Jan 03, 2023 |
| Pegatron      | Benicia                     | [25466113c1](https://linux-hardware.org/?probe=25466113c1) | Jan 02, 2023 |
| MSI           | H310M PRO-D                 | [27482bbe30](https://linux-hardware.org/?probe=27482bbe30) | Jan 02, 2023 |
| Dell          | 0RF703                      | [66180b5fdf](https://linux-hardware.org/?probe=66180b5fdf) | Jan 02, 2023 |
| MSI           | B250M PRO-VD                | [d94e8b5637](https://linux-hardware.org/?probe=d94e8b5637) | Jan 02, 2023 |
| ASRock        | B450 Steel Legend           | [b953257b12](https://linux-hardware.org/?probe=b953257b12) | Jan 01, 2023 |
| ASUSTek       | P5GD2-VM                    | [13ccd15493](https://linux-hardware.org/?probe=13ccd15493) | Jan 01, 2023 |
| Intel         | DH61DL AAG14066-205         | [8f923bc065](https://linux-hardware.org/?probe=8f923bc065) | Jan 01, 2023 |
| HP            | 82B4                        | [4e2d86906f](https://linux-hardware.org/?probe=4e2d86906f) | Jan 01, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [afdda0ad31](https://linux-hardware.org/?probe=afdda0ad31) | Dec 31, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [3659d7377d](https://linux-hardware.org/?probe=3659d7377d) | Dec 31, 2022 |
| BESSTAR Te... | C-J34 Pro                   | [1b54a52c3c](https://linux-hardware.org/?probe=1b54a52c3c) | Dec 30, 2022 |
| ASUSTek       | H81M-A                      | [10f0b28589](https://linux-hardware.org/?probe=10f0b28589) | Dec 29, 2022 |
| HP            | 0AE8h                       | [b23a6da065](https://linux-hardware.org/?probe=b23a6da065) | Dec 29, 2022 |
| MSI           | Z390-A PRO                  | [3a3375e173](https://linux-hardware.org/?probe=3a3375e173) | Dec 29, 2022 |
| HP            | 8399                        | [8a4ef9ab88](https://linux-hardware.org/?probe=8a4ef9ab88) | Dec 29, 2022 |
| ASUSTek       | H110M-K                     | [4dab06b05f](https://linux-hardware.org/?probe=4dab06b05f) | Dec 29, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [d0969c6a4c](https://linux-hardware.org/?probe=d0969c6a4c) | Dec 28, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [8a4dce4662](https://linux-hardware.org/?probe=8a4dce4662) | Dec 28, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6297565fda](https://linux-hardware.org/?probe=6297565fda) | Dec 28, 2022 |
| Pegatron      | 2AB6                        | [742c9ebcca](https://linux-hardware.org/?probe=742c9ebcca) | Dec 28, 2022 |
| Pegatron      | 2AB6                        | [9e95c7e7c7](https://linux-hardware.org/?probe=9e95c7e7c7) | Dec 28, 2022 |
| ASUSTek       | P8Z77-V PRO                 | [79427500b5](https://linux-hardware.org/?probe=79427500b5) | Dec 28, 2022 |
| ASRock        | 4CoreDual-SATA2             | [05ae1afd3f](https://linux-hardware.org/?probe=05ae1afd3f) | Dec 28, 2022 |
| HP            | 0AE8h                       | [c1bd1ff073](https://linux-hardware.org/?probe=c1bd1ff073) | Dec 27, 2022 |
| Unknown       | Unknown                     | [ccce0caf7e](https://linux-hardware.org/?probe=ccce0caf7e) | Dec 27, 2022 |
| MSI           | Z270 GAMING PRO CARBON      | [f422489705](https://linux-hardware.org/?probe=f422489705) | Dec 27, 2022 |
| Dell          | 0PTTT9 A01                  | [78512365ca](https://linux-hardware.org/?probe=78512365ca) | Dec 26, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [bc68280036](https://linux-hardware.org/?probe=bc68280036) | Dec 26, 2022 |
| ASUSTek       | B85M-E/DASH                 | [b2acfa6e70](https://linux-hardware.org/?probe=b2acfa6e70) | Dec 26, 2022 |
| ASUSTek       | B85M-E/DASH                 | [59e6ec4132](https://linux-hardware.org/?probe=59e6ec4132) | Dec 26, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [5ce1ea886f](https://linux-hardware.org/?probe=5ce1ea886f) | Dec 26, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [f56ea263a2](https://linux-hardware.org/?probe=f56ea263a2) | Dec 26, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [7e46b9fd5b](https://linux-hardware.org/?probe=7e46b9fd5b) | Dec 26, 2022 |
| MSI           | Boston                      | [5ffbd4e9a5](https://linux-hardware.org/?probe=5ffbd4e9a5) | Dec 25, 2022 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [384d09ccdb](https://linux-hardware.org/?probe=384d09ccdb) | Dec 25, 2022 |
| Dell          | 0DN075                      | [9fd08be389](https://linux-hardware.org/?probe=9fd08be389) | Dec 25, 2022 |
| ASRock        | N3700-ITX                   | [dc3f0d5062](https://linux-hardware.org/?probe=dc3f0d5062) | Dec 25, 2022 |
| AMI           | Cherry Trail FFD            | [7070bf387d](https://linux-hardware.org/?probe=7070bf387d) | Dec 24, 2022 |
| HP            | ProLiant MicroServer        | [b95892f2dc](https://linux-hardware.org/?probe=b95892f2dc) | Dec 24, 2022 |
| Foxconn       | 2AA9                        | [07650be639](https://linux-hardware.org/?probe=07650be639) | Dec 24, 2022 |
| ASRock        | B450 Pro4                   | [70ff83271a](https://linux-hardware.org/?probe=70ff83271a) | Dec 24, 2022 |
| ASRock        | X570 Steel Legend           | [7b79249b18](https://linux-hardware.org/?probe=7b79249b18) | Dec 23, 2022 |
| ASUSTek       | M5A78L/USB3                 | [348c431775](https://linux-hardware.org/?probe=348c431775) | Dec 23, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [568df9daf7](https://linux-hardware.org/?probe=568df9daf7) | Dec 23, 2022 |
| Lenovo        | ThinkCentre M71e 3129C3G    | [cb9f99f1cf](https://linux-hardware.org/?probe=cb9f99f1cf) | Dec 23, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [9e19c2db67](https://linux-hardware.org/?probe=9e19c2db67) | Dec 23, 2022 |
| ASRock        | FM2A88M-HD+                 | [18b83ae613](https://linux-hardware.org/?probe=18b83ae613) | Dec 22, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [ec808658f8](https://linux-hardware.org/?probe=ec808658f8) | Dec 22, 2022 |
| Acer          | Aspire M3920                | [803cd5d8f9](https://linux-hardware.org/?probe=803cd5d8f9) | Dec 22, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [fc162d4cb2](https://linux-hardware.org/?probe=fc162d4cb2) | Dec 21, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [1cdb02c6db](https://linux-hardware.org/?probe=1cdb02c6db) | Dec 21, 2022 |
| HP            | 8906 SMVB                   | [c7b2f48d96](https://linux-hardware.org/?probe=c7b2f48d96) | Dec 20, 2022 |
| ASUSTek       | PRIME A320M-K               | [3b38fc673c](https://linux-hardware.org/?probe=3b38fc673c) | Dec 19, 2022 |
| Gigabyte      | 970-GAMING                  | [cf93a75cf0](https://linux-hardware.org/?probe=cf93a75cf0) | Dec 19, 2022 |
| MSI           | X470 GAMING PLUS            | [44cdfa03bf](https://linux-hardware.org/?probe=44cdfa03bf) | Dec 19, 2022 |
| Gigabyte      | B75M-D3H                    | [ad506ad64e](https://linux-hardware.org/?probe=ad506ad64e) | Dec 19, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [87907abff7](https://linux-hardware.org/?probe=87907abff7) | Dec 19, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [831f650b05](https://linux-hardware.org/?probe=831f650b05) | Dec 19, 2022 |
| HP            | 18E7                        | [9f601a9f1a](https://linux-hardware.org/?probe=9f601a9f1a) | Dec 19, 2022 |
| MSI           | B250M PRO-VDH               | [14ea50f3b2](https://linux-hardware.org/?probe=14ea50f3b2) | Dec 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | [2d046f9339](https://linux-hardware.org/?probe=2d046f9339) | Dec 18, 2022 |
| Intel         | H55                         | [a5033f178f](https://linux-hardware.org/?probe=a5033f178f) | Dec 18, 2022 |
| ASUSTek       | P7H55D-M EVO                | [1e294ecd38](https://linux-hardware.org/?probe=1e294ecd38) | Dec 18, 2022 |
| ASUSTek       | F1A55-M LE                  | [c2db38b403](https://linux-hardware.org/?probe=c2db38b403) | Dec 17, 2022 |
| ASUSTek       | P8H77-M LE                  | [d9eba2d52f](https://linux-hardware.org/?probe=d9eba2d52f) | Dec 17, 2022 |
| MSI           | MS-B1711                    | [a5b142e258](https://linux-hardware.org/?probe=a5b142e258) | Dec 17, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [90912f0bba](https://linux-hardware.org/?probe=90912f0bba) | Dec 16, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [25ba267a65](https://linux-hardware.org/?probe=25ba267a65) | Dec 16, 2022 |
| Acer          | Veriton X2631G V:1.0        | [14d39a67c2](https://linux-hardware.org/?probe=14d39a67c2) | Dec 16, 2022 |
| Acer          | Veriton X2631G V:1.0        | [fc99e84afd](https://linux-hardware.org/?probe=fc99e84afd) | Dec 16, 2022 |
| MSI           | AM1I                        | [0ebd00e848](https://linux-hardware.org/?probe=0ebd00e848) | Dec 16, 2022 |
| MSI           | AM1I                        | [97dfa5ebf8](https://linux-hardware.org/?probe=97dfa5ebf8) | Dec 16, 2022 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | [1d1a225cde](https://linux-hardware.org/?probe=1d1a225cde) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [587fac961e](https://linux-hardware.org/?probe=587fac961e) | Dec 15, 2022 |
| Dell          | 0XJ8C4 A00                  | [c7ce3d7180](https://linux-hardware.org/?probe=c7ce3d7180) | Dec 14, 2022 |
| Dell          | 0XJ8C4 A00                  | [b136ecfff3](https://linux-hardware.org/?probe=b136ecfff3) | Dec 14, 2022 |
| HP            | 843C                        | [e647aa1207](https://linux-hardware.org/?probe=e647aa1207) | Dec 14, 2022 |
| HP            | 2AF7                        | [089612dee6](https://linux-hardware.org/?probe=089612dee6) | Dec 14, 2022 |
| ASRock        | B450M-HDV R4.0              | [b4d843d4c2](https://linux-hardware.org/?probe=b4d843d4c2) | Dec 14, 2022 |
| HP            | 2AF7                        | [2c6c08c8b8](https://linux-hardware.org/?probe=2c6c08c8b8) | Dec 14, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [39d58ec9aa](https://linux-hardware.org/?probe=39d58ec9aa) | Dec 13, 2022 |
| Intel         | DB75EN AAG39650-400         | [72b3306c33](https://linux-hardware.org/?probe=72b3306c33) | Dec 13, 2022 |
| Foxconn       | 2ABF                        | [48f3c01650](https://linux-hardware.org/?probe=48f3c01650) | Dec 12, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [3d835ed57d](https://linux-hardware.org/?probe=3d835ed57d) | Dec 12, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [c62c8e69b0](https://linux-hardware.org/?probe=c62c8e69b0) | Dec 12, 2022 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [9a73e431ee](https://linux-hardware.org/?probe=9a73e431ee) | Dec 12, 2022 |
| ASUSTek       | PRIME B450M-K               | [2212bad256](https://linux-hardware.org/?probe=2212bad256) | Dec 12, 2022 |
| ASUSTek       | PRIME B450M-K               | [20cb7a525a](https://linux-hardware.org/?probe=20cb7a525a) | Dec 12, 2022 |
| ASUSTek       | LEUCITE3                    | [b29a792d69](https://linux-hardware.org/?probe=b29a792d69) | Dec 12, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [c5501c208c](https://linux-hardware.org/?probe=c5501c208c) | Dec 11, 2022 |
| MSI           | Boston                      | [4cc25e826f](https://linux-hardware.org/?probe=4cc25e826f) | Dec 11, 2022 |
| Unknown       | T3 MRD                      | [c2cb5ad16b](https://linux-hardware.org/?probe=c2cb5ad16b) | Dec 11, 2022 |
| Gigabyte      | X570S AERO G                | [118d4ebca0](https://linux-hardware.org/?probe=118d4ebca0) | Dec 11, 2022 |
| Intel         | DB75EN AAG39650-400         | [01decbbb6d](https://linux-hardware.org/?probe=01decbbb6d) | Dec 10, 2022 |
| ASUSTek       | PRIME X570-P                | [6b00f35a38](https://linux-hardware.org/?probe=6b00f35a38) | Dec 10, 2022 |
| Lenovo        | SHARKBAY NOK                | [746c717d34](https://linux-hardware.org/?probe=746c717d34) | Dec 10, 2022 |
| Unknown       | Unknown                     | [41ff90c88a](https://linux-hardware.org/?probe=41ff90c88a) | Dec 09, 2022 |
| ASRock        | 970 Extreme3 R2.0           | [d52b5053b2](https://linux-hardware.org/?probe=d52b5053b2) | Dec 09, 2022 |
| Acer          | Veriton N2620G              | [2c4bd5a093](https://linux-hardware.org/?probe=2c4bd5a093) | Dec 08, 2022 |
| Dell          | 0RM5DR A00                  | [cd67b584bb](https://linux-hardware.org/?probe=cd67b584bb) | Dec 07, 2022 |
| ASRock        | H410M-HVS                   | [a8aa92bfed](https://linux-hardware.org/?probe=a8aa92bfed) | Dec 07, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [768329e263](https://linux-hardware.org/?probe=768329e263) | Dec 07, 2022 |
| ASRock        | Z170 Extreme7+              | [15f86800ee](https://linux-hardware.org/?probe=15f86800ee) | Dec 07, 2022 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [9d8dee4e41](https://linux-hardware.org/?probe=9d8dee4e41) | Dec 07, 2022 |
| MAXSUN        | MS-TZZ A320M.2-VH           | [c3fc86b5d4](https://linux-hardware.org/?probe=c3fc86b5d4) | Dec 06, 2022 |
| ASRock        | A320M-DGS                   | [fd3597e4bf](https://linux-hardware.org/?probe=fd3597e4bf) | Dec 06, 2022 |
| HP            | 843C                        | [278cbd2708](https://linux-hardware.org/?probe=278cbd2708) | Dec 06, 2022 |
| Gigabyte      | Z370P D3-CF                 | [13ac8bc162](https://linux-hardware.org/?probe=13ac8bc162) | Dec 06, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [664d064b07](https://linux-hardware.org/?probe=664d064b07) | Dec 06, 2022 |
| HP            | 0A64h                       | [58658d8b61](https://linux-hardware.org/?probe=58658d8b61) | Dec 06, 2022 |
| MSI           | MS-B1711                    | [1fbaa02605](https://linux-hardware.org/?probe=1fbaa02605) | Dec 05, 2022 |
| MSI           | Boston                      | [fd25ac3a2e](https://linux-hardware.org/?probe=fd25ac3a2e) | Dec 05, 2022 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [d0230b5c69](https://linux-hardware.org/?probe=d0230b5c69) | Dec 05, 2022 |
| Acer          | Aspire TC-885 V:1.1         | [73d037e031](https://linux-hardware.org/?probe=73d037e031) | Dec 05, 2022 |
| MSI           | B450M BAZOOKA PLUS          | [dc890ad363](https://linux-hardware.org/?probe=dc890ad363) | Dec 03, 2022 |
| ASUSTek       | PRIME A320M-K               | [84bc78ebb6](https://linux-hardware.org/?probe=84bc78ebb6) | Dec 03, 2022 |
| Acer          | Aspire X3950                | [96044c1932](https://linux-hardware.org/?probe=96044c1932) | Dec 03, 2022 |
| MSI           | B450M BAZOOKA PLUS          | [a087ddb18f](https://linux-hardware.org/?probe=a087ddb18f) | Dec 03, 2022 |
| Pegatron      | 2ACF                        | [f2d1d7fb3d](https://linux-hardware.org/?probe=f2d1d7fb3d) | Dec 03, 2022 |
| MSI           | X99S SLI PLUS               | [03a2e66a94](https://linux-hardware.org/?probe=03a2e66a94) | Dec 03, 2022 |
| ASUSTek       | PRIME A320M-K               | [7d42d3210f](https://linux-hardware.org/?probe=7d42d3210f) | Dec 03, 2022 |
| HP            | 2B52                        | [e2e8bdd4f6](https://linux-hardware.org/?probe=e2e8bdd4f6) | Dec 03, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [dc233f857f](https://linux-hardware.org/?probe=dc233f857f) | Dec 03, 2022 |
| Gigabyte      | B75M-D2V                    | [ee17f7d657](https://linux-hardware.org/?probe=ee17f7d657) | Dec 02, 2022 |
| MSI           | Z170A GAMING M3             | [e4fd5dfa0e](https://linux-hardware.org/?probe=e4fd5dfa0e) | Dec 01, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [f8a7663037](https://linux-hardware.org/?probe=f8a7663037) | Dec 01, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | [f0dba35258](https://linux-hardware.org/?probe=f0dba35258) | Dec 01, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | [baa969bf8b](https://linux-hardware.org/?probe=baa969bf8b) | Nov 30, 2022 |
| MSI           | Boston                      | [0564f7ed2d](https://linux-hardware.org/?probe=0564f7ed2d) | Nov 30, 2022 |
| HP            | 304Ah                       | [15db22accc](https://linux-hardware.org/?probe=15db22accc) | Nov 30, 2022 |
| MSI           | Z170A GAMING M3             | [dfe92c80c1](https://linux-hardware.org/?probe=dfe92c80c1) | Nov 30, 2022 |
| IBM           | MSI-9151 Boards             | [720ff829b9](https://linux-hardware.org/?probe=720ff829b9) | Nov 29, 2022 |
| HP            | 3048h                       | [6f5a8d1a09](https://linux-hardware.org/?probe=6f5a8d1a09) | Nov 29, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [719921de81](https://linux-hardware.org/?probe=719921de81) | Nov 29, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [f998b6a0d9](https://linux-hardware.org/?probe=f998b6a0d9) | Nov 29, 2022 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | [d5702f8b2d](https://linux-hardware.org/?probe=d5702f8b2d) | Nov 29, 2022 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | [640a031786](https://linux-hardware.org/?probe=640a031786) | Nov 29, 2022 |
| HP            | 843B                        | [19bd35484c](https://linux-hardware.org/?probe=19bd35484c) | Nov 28, 2022 |
| ASUSTek       | H110M-K                     | [becbfa5cc7](https://linux-hardware.org/?probe=becbfa5cc7) | Nov 28, 2022 |
| Gigabyte      | M61PME-S2P                  | [4aa3d8ee32](https://linux-hardware.org/?probe=4aa3d8ee32) | Nov 27, 2022 |
| MSI           | H510I PRO WIFI              | [f46e59c772](https://linux-hardware.org/?probe=f46e59c772) | Nov 27, 2022 |
| Gigabyte      | Z370P D3-CF                 | [02c62a5eb8](https://linux-hardware.org/?probe=02c62a5eb8) | Nov 27, 2022 |
| Dell          | 042P49 A01                  | [8f510e55e2](https://linux-hardware.org/?probe=8f510e55e2) | Nov 27, 2022 |
| Gigabyte      | Z370P D3-CF                 | [6206268283](https://linux-hardware.org/?probe=6206268283) | Nov 27, 2022 |
| Gigabyte      | F2A78M-HD2                  | [b5260b5609](https://linux-hardware.org/?probe=b5260b5609) | Nov 26, 2022 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | [eb0921d1f6](https://linux-hardware.org/?probe=eb0921d1f6) | Nov 26, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | [07363955de](https://linux-hardware.org/?probe=07363955de) | Nov 26, 2022 |
| HP            | 3397                        | [c943f7435d](https://linux-hardware.org/?probe=c943f7435d) | Nov 26, 2022 |
| Pegatron      | 2ACF                        | [dc9d24ac01](https://linux-hardware.org/?probe=dc9d24ac01) | Nov 25, 2022 |
| Pegatron      | 2ACF                        | [037b47ab43](https://linux-hardware.org/?probe=037b47ab43) | Nov 25, 2022 |
| HP            | 3397                        | [0605f9214a](https://linux-hardware.org/?probe=0605f9214a) | Nov 25, 2022 |
| ASUSTek       | P8H61-I LX/RM/SI            | [61cfa154b0](https://linux-hardware.org/?probe=61cfa154b0) | Nov 24, 2022 |
| MSI           | H81M-E33                    | [80ec8663ac](https://linux-hardware.org/?probe=80ec8663ac) | Nov 24, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [d6fe192013](https://linux-hardware.org/?probe=d6fe192013) | Nov 24, 2022 |
| ASRock        | 960GC-GS FX                 | [30081f61ca](https://linux-hardware.org/?probe=30081f61ca) | Nov 24, 2022 |
| ASRock        | 960GC-GS FX                 | [9e33d3b8f1](https://linux-hardware.org/?probe=9e33d3b8f1) | Nov 24, 2022 |
| Foxconn       | 2ADA                        | [3be30a3d31](https://linux-hardware.org/?probe=3be30a3d31) | Nov 23, 2022 |
| MSI           | B450M-A PRO MAX             | [e4904d14cc](https://linux-hardware.org/?probe=e4904d14cc) | Nov 23, 2022 |
| Dell          | 09M8Y8 A01                  | [4b44aea106](https://linux-hardware.org/?probe=4b44aea106) | Nov 23, 2022 |
| Dell          | 09M8Y8 A01                  | [1c232e6d70](https://linux-hardware.org/?probe=1c232e6d70) | Nov 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [bd9c6238bc](https://linux-hardware.org/?probe=bd9c6238bc) | Nov 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [393b7f7d3a](https://linux-hardware.org/?probe=393b7f7d3a) | Nov 23, 2022 |
| Lenovo        | Bantry CRB SDK0E50510 WI... | [14c0f082d8](https://linux-hardware.org/?probe=14c0f082d8) | Nov 22, 2022 |
| ASRock        | 960GC-GS FX                 | [d0bd92a5e0](https://linux-hardware.org/?probe=d0bd92a5e0) | Nov 22, 2022 |
| ASRock        | 960GC-GS FX                 | [b4cc2dc00b](https://linux-hardware.org/?probe=b4cc2dc00b) | Nov 22, 2022 |
| HP            | 83E2                        | [b04e1014da](https://linux-hardware.org/?probe=b04e1014da) | Nov 22, 2022 |
| ASUSTek       | M4A78T-E                    | [aef32a0e69](https://linux-hardware.org/?probe=aef32a0e69) | Nov 22, 2022 |
| ASUSTek       | PRIME B460M-A               | [4ed396ae3f](https://linux-hardware.org/?probe=4ed396ae3f) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [f13d80cf0b](https://linux-hardware.org/?probe=f13d80cf0b) | Nov 21, 2022 |
| ASUSTek       | IP4BL-ME-Oli                | [242fd5b355](https://linux-hardware.org/?probe=242fd5b355) | Nov 21, 2022 |
| Gigabyte      | B450 AORUS M                | [7ccd7842c1](https://linux-hardware.org/?probe=7ccd7842c1) | Nov 21, 2022 |
| ASUSTek       | P5E3 Deluxe                 | [c14020107c](https://linux-hardware.org/?probe=c14020107c) | Nov 21, 2022 |
| HP            | 2AF3                        | [babcb0bf93](https://linux-hardware.org/?probe=babcb0bf93) | Nov 21, 2022 |
| Lenovo        | Bantry CRB SDK0E50510 WI... | [07ca09898f](https://linux-hardware.org/?probe=07ca09898f) | Nov 20, 2022 |
| Gigabyte      | H110M-S2H-CF                | [87c95f019e](https://linux-hardware.org/?probe=87c95f019e) | Nov 20, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [835c000337](https://linux-hardware.org/?probe=835c000337) | Nov 20, 2022 |
| Acer          | Nitro N50-620               | [ecd8e9ec1b](https://linux-hardware.org/?probe=ecd8e9ec1b) | Nov 20, 2022 |
| HP            | 8767 A                      | [375e0d4525](https://linux-hardware.org/?probe=375e0d4525) | Nov 19, 2022 |
| Gigabyte      | H110M-S2H-CF                | [f1724d63d5](https://linux-hardware.org/?probe=f1724d63d5) | Nov 19, 2022 |
| ASUSTek       | PRIME A320M-K               | [6d02e2a960](https://linux-hardware.org/?probe=6d02e2a960) | Nov 19, 2022 |
| ASUSTek       | Z170-K                      | [1af696c23c](https://linux-hardware.org/?probe=1af696c23c) | Nov 19, 2022 |
| MSI           | H510M-A PRO                 | [e913feb821](https://linux-hardware.org/?probe=e913feb821) | Nov 18, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [a61b66e4ed](https://linux-hardware.org/?probe=a61b66e4ed) | Nov 18, 2022 |
| Lenovo        | 31900058 STD                | [1408b2dc5f](https://linux-hardware.org/?probe=1408b2dc5f) | Nov 18, 2022 |
| Acer          | E946GZ                      | [f084e099d5](https://linux-hardware.org/?probe=f084e099d5) | Nov 17, 2022 |
| Mediacom      | M-AO241/64                  | [8312099aa4](https://linux-hardware.org/?probe=8312099aa4) | Nov 16, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [e2492ba1c1](https://linux-hardware.org/?probe=e2492ba1c1) | Nov 16, 2022 |
| ASRock        | J3455B-ITX                  | [2a85d4fa3a](https://linux-hardware.org/?probe=2a85d4fa3a) | Nov 15, 2022 |
| ASRock        | 970 Extreme3 R2.0           | [a7e5419c89](https://linux-hardware.org/?probe=a7e5419c89) | Nov 15, 2022 |
| MSI           | H61M-P31/W8                 | [a7d3a01ab2](https://linux-hardware.org/?probe=a7d3a01ab2) | Nov 15, 2022 |
| ASUSTek       | A58M-A/USB3                 | [f6342a3d18](https://linux-hardware.org/?probe=f6342a3d18) | Nov 15, 2022 |
| Intel         | DB75EN AAG39650-400         | [07d6aa9adc](https://linux-hardware.org/?probe=07d6aa9adc) | Nov 14, 2022 |
| Huanan        | X99-F8                      | [503cf4b0ea](https://linux-hardware.org/?probe=503cf4b0ea) | Nov 14, 2022 |
| HP            | 802F                        | [8e7dbc3f9f](https://linux-hardware.org/?probe=8e7dbc3f9f) | Nov 14, 2022 |
| HP            | 802F                        | [89441a53f7](https://linux-hardware.org/?probe=89441a53f7) | Nov 14, 2022 |
| ASUSTek       | PRIME B360-PLUS             | [c3573fb12b](https://linux-hardware.org/?probe=c3573fb12b) | Nov 14, 2022 |
| MSI           | B450M PRO-M2 MAX            | [e1f2995c6f](https://linux-hardware.org/?probe=e1f2995c6f) | Nov 14, 2022 |
| HP            | 3397                        | [035eb81bdf](https://linux-hardware.org/?probe=035eb81bdf) | Nov 13, 2022 |
| MSI           | Z97A GAMING 7               | [275a1c28dd](https://linux-hardware.org/?probe=275a1c28dd) | Nov 13, 2022 |
| Gigabyte      | Z77X-UP7                    | [e0edc946f9](https://linux-hardware.org/?probe=e0edc946f9) | Nov 13, 2022 |
| MSI           | ZH77A-G43                   | [a8f49c1ad8](https://linux-hardware.org/?probe=a8f49c1ad8) | Nov 13, 2022 |
| Mediacom      | M-AO241/64                  | [8c577b3d8f](https://linux-hardware.org/?probe=8c577b3d8f) | Nov 13, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | [7d72f2fa26](https://linux-hardware.org/?probe=7d72f2fa26) | Nov 12, 2022 |
| MSI           | MS-7309                     | [bd4d6c72e3](https://linux-hardware.org/?probe=bd4d6c72e3) | Nov 12, 2022 |
| Gigabyte      | 970A-DS3                    | [7c25342680](https://linux-hardware.org/?probe=7c25342680) | Nov 12, 2022 |
| ASUSTek       | P8P67 EVO                   | [c033c311f3](https://linux-hardware.org/?probe=c033c311f3) | Nov 12, 2022 |
| Unknown       | 775i65G                     | [b872a779af](https://linux-hardware.org/?probe=b872a779af) | Nov 12, 2022 |
| ASUSTek       | P5L1394                     | [d4c699bf10](https://linux-hardware.org/?probe=d4c699bf10) | Nov 11, 2022 |
| Unknown       | 1.0                         | [d07852e419](https://linux-hardware.org/?probe=d07852e419) | Nov 11, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [4fddb7605a](https://linux-hardware.org/?probe=4fddb7605a) | Nov 11, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [779188af6a](https://linux-hardware.org/?probe=779188af6a) | Nov 11, 2022 |
| Intel         | DQ57TM AAE70931-403         | [1759cf3bec](https://linux-hardware.org/?probe=1759cf3bec) | Nov 11, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [b4aa454d9a](https://linux-hardware.org/?probe=b4aa454d9a) | Nov 10, 2022 |
| ASRock        | B365 Pro4                   | [3069280223](https://linux-hardware.org/?probe=3069280223) | Nov 10, 2022 |
| MSI           | H61M-P31/W8                 | [933683bc04](https://linux-hardware.org/?probe=933683bc04) | Nov 10, 2022 |
| Mediacom      | M-AO241/64                  | [d0cac7ee7b](https://linux-hardware.org/?probe=d0cac7ee7b) | Nov 10, 2022 |
| Mediacom      | M-AO241/64                  | [cf0ed7acab](https://linux-hardware.org/?probe=cf0ed7acab) | Nov 10, 2022 |
| ASUSTek       | P5KPL-SE                    | [dafce5f727](https://linux-hardware.org/?probe=dafce5f727) | Nov 09, 2022 |
| MSI           | X299 RAIDER                 | [b7d117fc31](https://linux-hardware.org/?probe=b7d117fc31) | Nov 09, 2022 |
| ASRock        | X370 Gaming K4              | [f0634d863e](https://linux-hardware.org/?probe=f0634d863e) | Nov 08, 2022 |
| ASRock        | Z77 Pro4-M                  | [3a4a75d603](https://linux-hardware.org/?probe=3a4a75d603) | Nov 08, 2022 |
| ASUSTek       | TUF Gaming B550M-E          | [e7fb74c85e](https://linux-hardware.org/?probe=e7fb74c85e) | Nov 08, 2022 |
| ASUSTek       | PRIME X299-DELUXE           | [92cf5ed7b4](https://linux-hardware.org/?probe=92cf5ed7b4) | Nov 07, 2022 |
| Dell          | 0X231R A01                  | [5846e23f06](https://linux-hardware.org/?probe=5846e23f06) | Nov 07, 2022 |
| ASUSTek       | P8H61-M LX R2.0             | [ddca3f4758](https://linux-hardware.org/?probe=ddca3f4758) | Nov 06, 2022 |
| ASRock        | B365 Pro4                   | [6c37cfce25](https://linux-hardware.org/?probe=6c37cfce25) | Nov 06, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [958f0c8551](https://linux-hardware.org/?probe=958f0c8551) | Nov 05, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [98a3c2457d](https://linux-hardware.org/?probe=98a3c2457d) | Nov 05, 2022 |
| Gigabyte      | 990XA-UD3                   | [a06275a0f2](https://linux-hardware.org/?probe=a06275a0f2) | Nov 05, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [1cf71a1b5c](https://linux-hardware.org/?probe=1cf71a1b5c) | Nov 05, 2022 |
| ASRock        | B450M Pro4                  | [97e52df467](https://linux-hardware.org/?probe=97e52df467) | Nov 05, 2022 |
| BESSTAR Te... | UM250 V1.0                  | [67369107e1](https://linux-hardware.org/?probe=67369107e1) | Nov 05, 2022 |
| AMI           | Cherry Trail CR             | [f731a55cc1](https://linux-hardware.org/?probe=f731a55cc1) | Nov 05, 2022 |
| ASRock        | J3455B-ITX                  | [deda12dd1f](https://linux-hardware.org/?probe=deda12dd1f) | Nov 05, 2022 |
| ASRock        | B450M Steel Legend          | [1534af11b9](https://linux-hardware.org/?probe=1534af11b9) | Nov 05, 2022 |
| HP            | 8053                        | [20c566d4e7](https://linux-hardware.org/?probe=20c566d4e7) | Nov 05, 2022 |
| ASUSTek       | P8H67                       | [0d98e4b3b3](https://linux-hardware.org/?probe=0d98e4b3b3) | Nov 05, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6494c493cb](https://linux-hardware.org/?probe=6494c493cb) | Nov 04, 2022 |
| Lenovo        | SHARKBAY SDK0J40700 WIN     | [f027f3a4e2](https://linux-hardware.org/?probe=f027f3a4e2) | Nov 04, 2022 |
| Lenovo        | SHARKBAY SDK0J40700 WIN     | [cb9374e939](https://linux-hardware.org/?probe=cb9374e939) | Nov 04, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [97d8c001ef](https://linux-hardware.org/?probe=97d8c001ef) | Nov 03, 2022 |
| Lenovo        | 3728 SDK0J40700 WIN 3258... | [6700909ef7](https://linux-hardware.org/?probe=6700909ef7) | Nov 03, 2022 |
| HP            | 8054                        | [0f1371d133](https://linux-hardware.org/?probe=0f1371d133) | Nov 03, 2022 |
| Dell          | 0W5363                      | [20c6f0d689](https://linux-hardware.org/?probe=20c6f0d689) | Nov 03, 2022 |
| Dell          | 0W5363                      | [7400a9beb1](https://linux-hardware.org/?probe=7400a9beb1) | Nov 03, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [e4206174ca](https://linux-hardware.org/?probe=e4206174ca) | Nov 03, 2022 |
| ASUSTek       | H81T                        | [7598a634e6](https://linux-hardware.org/?probe=7598a634e6) | Nov 02, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [c9041d22be](https://linux-hardware.org/?probe=c9041d22be) | Nov 02, 2022 |
| ASUSTek       | B85-PLUS                    | [dd24c26ffa](https://linux-hardware.org/?probe=dd24c26ffa) | Nov 02, 2022 |
| Dell          | 0GWHMW A01                  | [732eaeede7](https://linux-hardware.org/?probe=732eaeede7) | Nov 02, 2022 |
| MSI           | B75A-IE35                   | [57b74e4ca2](https://linux-hardware.org/?probe=57b74e4ca2) | Nov 01, 2022 |
| MSI           | Z370 GAMING PLUS            | [527c779cfb](https://linux-hardware.org/?probe=527c779cfb) | Nov 01, 2022 |
| ASUSTek       | BM2AD_D510MT_D310MT         | [8f2b0bc926](https://linux-hardware.org/?probe=8f2b0bc926) | Nov 01, 2022 |
| Intel         | DH61DL AAG14066-205         | [0f62f6f3b1](https://linux-hardware.org/?probe=0f62f6f3b1) | Nov 01, 2022 |
| MSI           | H81M-E33                    | [ee4c33d7b1](https://linux-hardware.org/?probe=ee4c33d7b1) | Nov 01, 2022 |
| ASUSTek       | PRIME A320M-K               | [a14fa00a56](https://linux-hardware.org/?probe=a14fa00a56) | Nov 01, 2022 |
| ASUSTek       | PRIME A320M-K               | [bfa1db2eb1](https://linux-hardware.org/?probe=bfa1db2eb1) | Nov 01, 2022 |
| ASUSTek       | H61M-K                      | [ca5a47c66a](https://linux-hardware.org/?probe=ca5a47c66a) | Nov 01, 2022 |
| ASUSTek       | SABERTOOTH Z87              | [d39c952932](https://linux-hardware.org/?probe=d39c952932) | Nov 01, 2022 |
| MSI           | X570-A PRO                  | [c60d9aa72d](https://linux-hardware.org/?probe=c60d9aa72d) | Oct 31, 2022 |
| ASUSTek       | CG8480                      | [0f7c1dc1cf](https://linux-hardware.org/?probe=0f7c1dc1cf) | Oct 31, 2022 |
| MSI           | H110M PRO-VD PLUS           | [ced3229025](https://linux-hardware.org/?probe=ced3229025) | Oct 31, 2022 |
| HP            | 3397                        | [942cfa2a25](https://linux-hardware.org/?probe=942cfa2a25) | Oct 31, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [e309413fea](https://linux-hardware.org/?probe=e309413fea) | Oct 31, 2022 |
| Gigabyte      | B450 AORUS M                | [13741c554f](https://linux-hardware.org/?probe=13741c554f) | Oct 31, 2022 |
| Gigabyte      | B450 AORUS M                | [e6e466cd8f](https://linux-hardware.org/?probe=e6e466cd8f) | Oct 31, 2022 |
| MSI           | 990FXA-GD80                 | [baaa1111ec](https://linux-hardware.org/?probe=baaa1111ec) | Oct 31, 2022 |
| Gigabyte      | X570S AERO G                | [600587e66a](https://linux-hardware.org/?probe=600587e66a) | Oct 31, 2022 |
| ASUSTek       | PRIME X570-PRO              | [3fbcca75d5](https://linux-hardware.org/?probe=3fbcca75d5) | Oct 30, 2022 |
| ASRock        | FM2A88X-ITX+                | [08cf9e2ccd](https://linux-hardware.org/?probe=08cf9e2ccd) | Oct 30, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | [c128f85cdc](https://linux-hardware.org/?probe=c128f85cdc) | Oct 30, 2022 |
| ASUSTek       | A88XM-PLUS                  | [10aa435a0b](https://linux-hardware.org/?probe=10aa435a0b) | Oct 30, 2022 |
| ASRock        | FM2A88X-ITX+                | [e28a25b18a](https://linux-hardware.org/?probe=e28a25b18a) | Oct 30, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [1f7df5159e](https://linux-hardware.org/?probe=1f7df5159e) | Oct 30, 2022 |
| ASUSTek       | P6TD DELUXE                 | [faa61ea635](https://linux-hardware.org/?probe=faa61ea635) | Oct 30, 2022 |
| MSI           | Z77A-G45 Thunderbolt        | [fa189cf50b](https://linux-hardware.org/?probe=fa189cf50b) | Oct 30, 2022 |
| HP            | 1495                        | [b62f9d83b9](https://linux-hardware.org/?probe=b62f9d83b9) | Oct 30, 2022 |
| MSI           | A320M-A PRO MAX             | [80d6d99bcf](https://linux-hardware.org/?probe=80d6d99bcf) | Oct 30, 2022 |
| HP            | 18E7                        | [d4a4ad62cb](https://linux-hardware.org/?probe=d4a4ad62cb) | Oct 29, 2022 |
| MSI           | B450M PRO-M2 MAX            | [6549416d9d](https://linux-hardware.org/?probe=6549416d9d) | Oct 29, 2022 |
| ASRock        | B450M Pro4                  | [0616272661](https://linux-hardware.org/?probe=0616272661) | Oct 29, 2022 |
| ASUSTek       | PRIME A320M-K               | [25caeb6d9e](https://linux-hardware.org/?probe=25caeb6d9e) | Oct 29, 2022 |
| ASRock        | 890GX Extreme3              | [ff1af2eaf0](https://linux-hardware.org/?probe=ff1af2eaf0) | Oct 29, 2022 |
| ASUSTek       | LEUCITE3                    | [f51161d005](https://linux-hardware.org/?probe=f51161d005) | Oct 29, 2022 |
| ASUSTek       | LEUCITE3                    | [4c4e1b6871](https://linux-hardware.org/?probe=4c4e1b6871) | Oct 29, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [95af9b0439](https://linux-hardware.org/?probe=95af9b0439) | Oct 29, 2022 |
| Gigabyte      | EX58-UD3R                   | [0d76cc7e31](https://linux-hardware.org/?probe=0d76cc7e31) | Oct 29, 2022 |
| ASUSTek       | PRIME A320M-K               | [5876a2f3d6](https://linux-hardware.org/?probe=5876a2f3d6) | Oct 28, 2022 |
| Acer          | MCP7A                       | [c14a31f6ab](https://linux-hardware.org/?probe=c14a31f6ab) | Oct 28, 2022 |
| Unknown       | 775V88+                     | [f1a685b497](https://linux-hardware.org/?probe=f1a685b497) | Oct 28, 2022 |
| Lenovo        | 317E SDK0J40700 WIN 3258... | [8c85b7ec2e](https://linux-hardware.org/?probe=8c85b7ec2e) | Oct 28, 2022 |
| Gigabyte      | H310M S2H x.x               | [acdf2a172f](https://linux-hardware.org/?probe=acdf2a172f) | Oct 28, 2022 |
| MSI           | H81M-P33                    | [16a78334cd](https://linux-hardware.org/?probe=16a78334cd) | Oct 28, 2022 |
| MSI           | Z370 KRAIT GAMING           | [cbf597cec1](https://linux-hardware.org/?probe=cbf597cec1) | Oct 28, 2022 |
| ASUSTek       | P9X79-WS-SYS                | [8b10d380a5](https://linux-hardware.org/?probe=8b10d380a5) | Oct 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [1759cbebe1](https://linux-hardware.org/?probe=1759cbebe1) | Oct 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [ac3b0eaf36](https://linux-hardware.org/?probe=ac3b0eaf36) | Oct 28, 2022 |
| Intel         | DH61DL AAG14066-205         | [9031f7b82b](https://linux-hardware.org/?probe=9031f7b82b) | Oct 27, 2022 |
| Lenovo        | 0B98401 PRO                 | [99f9bbd5ad](https://linux-hardware.org/?probe=99f9bbd5ad) | Oct 27, 2022 |
| MSI           | H110M PRO-VD PLUS           | [d3c4092754](https://linux-hardware.org/?probe=d3c4092754) | Oct 27, 2022 |
| Gigabyte      | Z77X-UP7                    | [c33d6de923](https://linux-hardware.org/?probe=c33d6de923) | Oct 27, 2022 |
| Packard Be... | IMEDIA S3810                | [f492fb9369](https://linux-hardware.org/?probe=f492fb9369) | Oct 27, 2022 |
| MSI           | H81M-E33                    | [f0613bfce8](https://linux-hardware.org/?probe=f0613bfce8) | Oct 27, 2022 |
| MSI           | X58 Pro                     | [6c449246c8](https://linux-hardware.org/?probe=6c449246c8) | Oct 27, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [b682a38061](https://linux-hardware.org/?probe=b682a38061) | Oct 27, 2022 |
| HP            | 1589                        | [4a15b6de0f](https://linux-hardware.org/?probe=4a15b6de0f) | Oct 27, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [d2debd1dab](https://linux-hardware.org/?probe=d2debd1dab) | Oct 26, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [97d2bacb5d](https://linux-hardware.org/?probe=97d2bacb5d) | Oct 26, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [82fcc1ecc7](https://linux-hardware.org/?probe=82fcc1ecc7) | Oct 26, 2022 |
| Intel         | H55                         | [f634aefb9a](https://linux-hardware.org/?probe=f634aefb9a) | Oct 26, 2022 |
| MSI           | ZH77A-G43                   | [ff43c876e9](https://linux-hardware.org/?probe=ff43c876e9) | Oct 26, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [469345600b](https://linux-hardware.org/?probe=469345600b) | Oct 26, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [06f33f301b](https://linux-hardware.org/?probe=06f33f301b) | Oct 26, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [8a718e0ade](https://linux-hardware.org/?probe=8a718e0ade) | Oct 26, 2022 |
| ASRock        | H77 Pro4/MVP                | [94d8bc13bb](https://linux-hardware.org/?probe=94d8bc13bb) | Oct 26, 2022 |
| Lenovo        | 1048 SDK0Q40104 WIN 3915... | [2bed8fe9b1](https://linux-hardware.org/?probe=2bed8fe9b1) | Oct 26, 2022 |
| HP            | 1494                        | [fa63090109](https://linux-hardware.org/?probe=fa63090109) | Oct 26, 2022 |
| HP            | 8509                        | [81bfb5a782](https://linux-hardware.org/?probe=81bfb5a782) | Oct 26, 2022 |
| ASUSTek       | P8H67-M PRO                 | [b50585b578](https://linux-hardware.org/?probe=b50585b578) | Oct 26, 2022 |
| Gigabyte      | B450 AORUS M                | [1603f6064b](https://linux-hardware.org/?probe=1603f6064b) | Oct 26, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [705e51d33e](https://linux-hardware.org/?probe=705e51d33e) | Oct 25, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [50c68d9bb4](https://linux-hardware.org/?probe=50c68d9bb4) | Oct 25, 2022 |
| ASUSTek       | Z87-PRO                     | [a48316f550](https://linux-hardware.org/?probe=a48316f550) | Oct 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [824eb583d8](https://linux-hardware.org/?probe=824eb583d8) | Oct 25, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [6ffc032b64](https://linux-hardware.org/?probe=6ffc032b64) | Oct 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2227bb9824](https://linux-hardware.org/?probe=2227bb9824) | Oct 25, 2022 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | [958c0a2ae7](https://linux-hardware.org/?probe=958c0a2ae7) | Oct 25, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [1f3561258a](https://linux-hardware.org/?probe=1f3561258a) | Oct 25, 2022 |
| Gigabyte      | H97M-D3H                    | [72532e08fe](https://linux-hardware.org/?probe=72532e08fe) | Oct 25, 2022 |
| Dell          | 040DDP A01                  | [cc0b502ddf](https://linux-hardware.org/?probe=cc0b502ddf) | Oct 25, 2022 |
| ASUSTek       | H110M-K                     | [06c00dc8d5](https://linux-hardware.org/?probe=06c00dc8d5) | Oct 25, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [bd3a8063b3](https://linux-hardware.org/?probe=bd3a8063b3) | Oct 25, 2022 |
| ASRock        | AB350 Pro4                  | [82ee095168](https://linux-hardware.org/?probe=82ee095168) | Oct 25, 2022 |
| ASRock        | G41C-GS                     | [a38f9baa55](https://linux-hardware.org/?probe=a38f9baa55) | Oct 25, 2022 |
| MSI           | Z170A GAMING M5             | [b5dcdb6844](https://linux-hardware.org/?probe=b5dcdb6844) | Oct 25, 2022 |
| ASRock        | 4Core1600-GLAN/M            | [33bf20761f](https://linux-hardware.org/?probe=33bf20761f) | Oct 25, 2022 |
| Unknown       | 1.0                         | [cf3a9de207](https://linux-hardware.org/?probe=cf3a9de207) | Oct 25, 2022 |
| ASUSTek       | PRIME Z490-P                | [0eb9c3ebff](https://linux-hardware.org/?probe=0eb9c3ebff) | Oct 25, 2022 |
| Pegatron      | Benicia                     | [3735dca311](https://linux-hardware.org/?probe=3735dca311) | Oct 25, 2022 |
| HP            | 805F                        | [eaa3994f86](https://linux-hardware.org/?probe=eaa3994f86) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO II     | [ab5d5a6170](https://linux-hardware.org/?probe=ab5d5a6170) | Oct 25, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [040714e135](https://linux-hardware.org/?probe=040714e135) | Oct 25, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [6a9d81591f](https://linux-hardware.org/?probe=6a9d81591f) | Oct 25, 2022 |
| Lenovo        | 318E NOK                    | [6b190bfb4f](https://linux-hardware.org/?probe=6b190bfb4f) | Oct 25, 2022 |
| ASUSTek       | PRIME H370-PLUS             | [ef9fdf5dcd](https://linux-hardware.org/?probe=ef9fdf5dcd) | Oct 25, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [0c63b974e1](https://linux-hardware.org/?probe=0c63b974e1) | Oct 25, 2022 |
| ASUSTek       | M3N78-VM                    | [1c68e176b6](https://linux-hardware.org/?probe=1c68e176b6) | Oct 25, 2022 |
| MSI           | H97 PC Mate                 | [1916f5c048](https://linux-hardware.org/?probe=1916f5c048) | Oct 25, 2022 |
| Gigabyte      | F2A78M-HD2                  | [6cffc39cfc](https://linux-hardware.org/?probe=6cffc39cfc) | Oct 25, 2022 |
| Gigabyte      | Z690 UD DDR4                | [c838769296](https://linux-hardware.org/?probe=c838769296) | Oct 25, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [7b59865f68](https://linux-hardware.org/?probe=7b59865f68) | Oct 25, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [7027921568](https://linux-hardware.org/?probe=7027921568) | Oct 25, 2022 |
| MSI           | H61M-P31/W8                 | [7ba2ecf5f0](https://linux-hardware.org/?probe=7ba2ecf5f0) | Oct 25, 2022 |
| Acer          | Veriton M2631 V:1.0         | [1d5e3aa9f0](https://linux-hardware.org/?probe=1d5e3aa9f0) | Oct 25, 2022 |
| MSI           | Z97-G55 SLI                 | [25ddd5274f](https://linux-hardware.org/?probe=25ddd5274f) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [74ca211759](https://linux-hardware.org/?probe=74ca211759) | Oct 25, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [aa4a86445a](https://linux-hardware.org/?probe=aa4a86445a) | Oct 25, 2022 |
| ASRock        | B450 Gaming K4              | [122a54b0c2](https://linux-hardware.org/?probe=122a54b0c2) | Oct 25, 2022 |
| ASUSTek       | PRIME B550M-A               | [a55a6ef774](https://linux-hardware.org/?probe=a55a6ef774) | Oct 25, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [52a4b91a1e](https://linux-hardware.org/?probe=52a4b91a1e) | Oct 25, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [c77d3dfeba](https://linux-hardware.org/?probe=c77d3dfeba) | Oct 25, 2022 |
| Gigabyte      | Z87-HD3                     | [da7fe35832](https://linux-hardware.org/?probe=da7fe35832) | Oct 25, 2022 |
| MSI           | Z170A GAMING M7             | [3326f67ecf](https://linux-hardware.org/?probe=3326f67ecf) | Oct 25, 2022 |
| Intel         | DH61AG AAG23736-507         | [7fa3b3bc6a](https://linux-hardware.org/?probe=7fa3b3bc6a) | Oct 25, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [65c39a9702](https://linux-hardware.org/?probe=65c39a9702) | Oct 24, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | [a0e0f661af](https://linux-hardware.org/?probe=a0e0f661af) | Oct 24, 2022 |
| ASRock        | H370M-ITX/ac                | [fa925dcefb](https://linux-hardware.org/?probe=fa925dcefb) | Oct 24, 2022 |
| MSI           | H510M-A PRO                 | [02e8dbe21d](https://linux-hardware.org/?probe=02e8dbe21d) | Oct 24, 2022 |
| ASUSTek       | PRIME Z390-P                | [261e670072](https://linux-hardware.org/?probe=261e670072) | Oct 24, 2022 |
| ASRock        | Z170 Gaming K4              | [184139e7bc](https://linux-hardware.org/?probe=184139e7bc) | Oct 24, 2022 |
| ASUSTek       | H81M-C                      | [1deed99314](https://linux-hardware.org/?probe=1deed99314) | Oct 24, 2022 |
| ASUSTek       | M4A78T-E                    | [ee86cdac2a](https://linux-hardware.org/?probe=ee86cdac2a) | Oct 24, 2022 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | [df05c11ff4](https://linux-hardware.org/?probe=df05c11ff4) | Oct 24, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [581fb21345](https://linux-hardware.org/?probe=581fb21345) | Oct 24, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [aa82a1f3c9](https://linux-hardware.org/?probe=aa82a1f3c9) | Oct 24, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [c76c6f0a0e](https://linux-hardware.org/?probe=c76c6f0a0e) | Oct 24, 2022 |
| Gigabyte      | B365M D2V                   | [c852b8f3f7](https://linux-hardware.org/?probe=c852b8f3f7) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [f42213926f](https://linux-hardware.org/?probe=f42213926f) | Oct 24, 2022 |
| Dell          | 0M5WNK A00                  | [fad0f2f50e](https://linux-hardware.org/?probe=fad0f2f50e) | Oct 24, 2022 |
| ASUSTek       | Maximus VI EXTREME          | [e5264df501](https://linux-hardware.org/?probe=e5264df501) | Oct 24, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [91bf754e64](https://linux-hardware.org/?probe=91bf754e64) | Oct 24, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [b63ff47508](https://linux-hardware.org/?probe=b63ff47508) | Oct 24, 2022 |
| ASUSTek       | H97-PLUS                    | [aaf3b72437](https://linux-hardware.org/?probe=aaf3b72437) | Oct 24, 2022 |
| ASUSTek       | H170 PRO GAMING             | [905f41afd6](https://linux-hardware.org/?probe=905f41afd6) | Oct 24, 2022 |
| Acer          | Aspire MC605 v1.0           | [9544ff7787](https://linux-hardware.org/?probe=9544ff7787) | Oct 24, 2022 |
| HP            | 3048h                       | [3c3f7eda5e](https://linux-hardware.org/?probe=3c3f7eda5e) | Oct 24, 2022 |
| ASRock        | X370 Gaming K4              | [5658dbff1b](https://linux-hardware.org/?probe=5658dbff1b) | Oct 24, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [1dea808353](https://linux-hardware.org/?probe=1dea808353) | Oct 24, 2022 |
| Gigabyte      | B85M-D3H                    | [f4182ec2e9](https://linux-hardware.org/?probe=f4182ec2e9) | Oct 24, 2022 |
| Gigabyte      | H310M H                     | [3a8627fb53](https://linux-hardware.org/?probe=3a8627fb53) | Oct 24, 2022 |
| MSI           | B350M PRO-VD PLUS           | [93068b4cf8](https://linux-hardware.org/?probe=93068b4cf8) | Oct 24, 2022 |
| ASUSTek       | PRIME B360M-A               | [19ccd70ee8](https://linux-hardware.org/?probe=19ccd70ee8) | Oct 24, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [01c09a61ae](https://linux-hardware.org/?probe=01c09a61ae) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [638c72b105](https://linux-hardware.org/?probe=638c72b105) | Oct 24, 2022 |
| ASUSTek       | PRIME B450M-A               | [fb3feaef06](https://linux-hardware.org/?probe=fb3feaef06) | Oct 24, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [a8ab16a5c5](https://linux-hardware.org/?probe=a8ab16a5c5) | Oct 24, 2022 |
| ASUSTek       | P8Z77-V LE PLUS             | [164b8dd0d8](https://linux-hardware.org/?probe=164b8dd0d8) | Oct 24, 2022 |
| Dell          | 042P49 A02                  | [d9590e8d45](https://linux-hardware.org/?probe=d9590e8d45) | Oct 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [5010a8ef47](https://linux-hardware.org/?probe=5010a8ef47) | Oct 24, 2022 |
| Dell          | 0RW199                      | [dc99b64e62](https://linux-hardware.org/?probe=dc99b64e62) | Oct 24, 2022 |
| MSI           | B450M MORTAR TITANIUM       | [37a0403fc9](https://linux-hardware.org/?probe=37a0403fc9) | Oct 24, 2022 |
| MSI           | Z390-A PRO                  | [40f916420e](https://linux-hardware.org/?probe=40f916420e) | Oct 23, 2022 |
| HP            | 3397                        | [6f58590d3d](https://linux-hardware.org/?probe=6f58590d3d) | Oct 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [22ea226b97](https://linux-hardware.org/?probe=22ea226b97) | Oct 23, 2022 |
| Dell          | 0WR7PY A02                  | [07fb028e18](https://linux-hardware.org/?probe=07fb028e18) | Oct 22, 2022 |
| MSI           | X58 Pro                     | [96db21189e](https://linux-hardware.org/?probe=96db21189e) | Oct 22, 2022 |
| MSI           | PRO Z690-A                  | [9ea661d3b9](https://linux-hardware.org/?probe=9ea661d3b9) | Oct 22, 2022 |
| MSI           | MAG B460M BAZOOKA           | [9cfe9f3c51](https://linux-hardware.org/?probe=9cfe9f3c51) | Oct 22, 2022 |
| ASUSTek       | H110M-A                     | [7bd1ee25b3](https://linux-hardware.org/?probe=7bd1ee25b3) | Oct 21, 2022 |
| HP            | 87D6 SMVB                   | [86740d9460](https://linux-hardware.org/?probe=86740d9460) | Oct 21, 2022 |
| ASUSTek       | P7P55-M                     | [3ff254b938](https://linux-hardware.org/?probe=3ff254b938) | Oct 20, 2022 |
| ASUSTek       | Leonite2                    | [7640c7a49f](https://linux-hardware.org/?probe=7640c7a49f) | Oct 20, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [e455bef105](https://linux-hardware.org/?probe=e455bef105) | Oct 20, 2022 |
| Dell          | 0HY175 A03                  | [86950688ac](https://linux-hardware.org/?probe=86950688ac) | Oct 20, 2022 |
| Dell          | 0HY175 A03                  | [ede27fb1d0](https://linux-hardware.org/?probe=ede27fb1d0) | Oct 19, 2022 |
| HP            | 805D                        | [a70ef30fce](https://linux-hardware.org/?probe=a70ef30fce) | Oct 19, 2022 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [116fff483b](https://linux-hardware.org/?probe=116fff483b) | Oct 19, 2022 |
| Dell          | 0C522T A03                  | [20703ba8b3](https://linux-hardware.org/?probe=20703ba8b3) | Oct 18, 2022 |
| HP            | 3048h                       | [624ad8a33c](https://linux-hardware.org/?probe=624ad8a33c) | Oct 17, 2022 |
| HP            | 3048h                       | [1b3d31f720](https://linux-hardware.org/?probe=1b3d31f720) | Oct 17, 2022 |
| MSI           | MS-B1711                    | [231d1c3373](https://linux-hardware.org/?probe=231d1c3373) | Oct 16, 2022 |
| MSI           | MS-B1711                    | [964bad6988](https://linux-hardware.org/?probe=964bad6988) | Oct 16, 2022 |
| ASUSTek       | PRIME H270-PRO              | [3c2eef945d](https://linux-hardware.org/?probe=3c2eef945d) | Oct 16, 2022 |
| MSI           | MS-7309                     | [9d4f0daf60](https://linux-hardware.org/?probe=9d4f0daf60) | Oct 16, 2022 |
| Packard Be... | IMEDIA S3712                | [d9aa81c4c3](https://linux-hardware.org/?probe=d9aa81c4c3) | Oct 15, 2022 |
| ASUSTek       | H87M-PRO                    | [4f1304fbdd](https://linux-hardware.org/?probe=4f1304fbdd) | Oct 15, 2022 |
| HP            | 198E                        | [47439edd0e](https://linux-hardware.org/?probe=47439edd0e) | Oct 15, 2022 |
| ASUSTek       | P5KPL-CM                    | [d00f5feebf](https://linux-hardware.org/?probe=d00f5feebf) | Oct 15, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [b1eab51bd7](https://linux-hardware.org/?probe=b1eab51bd7) | Oct 15, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [8557c8b501](https://linux-hardware.org/?probe=8557c8b501) | Oct 15, 2022 |
| Gigabyte      | G33M-DS2R                   | [a14ced18eb](https://linux-hardware.org/?probe=a14ced18eb) | Oct 15, 2022 |
| ASUSTek       | P8H77-V                     | [d6af5204e6](https://linux-hardware.org/?probe=d6af5204e6) | Oct 14, 2022 |
| Intel         | STK2MV64CC H89290-502       | [85670dc1fe](https://linux-hardware.org/?probe=85670dc1fe) | Oct 14, 2022 |
| Supermicro    | C7P67                       | [70613229ac](https://linux-hardware.org/?probe=70613229ac) | Oct 12, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d0d2949fd3](https://linux-hardware.org/?probe=d0d2949fd3) | Oct 12, 2022 |
| ASUSTek       | M5A97 R2.0                  | [71970edbae](https://linux-hardware.org/?probe=71970edbae) | Oct 11, 2022 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [0e8d79a9a9](https://linux-hardware.org/?probe=0e8d79a9a9) | Oct 11, 2022 |
| ASUSTek       | Maximus VIII HERO ALPHA     | [c8ee640a4d](https://linux-hardware.org/?probe=c8ee640a4d) | Oct 09, 2022 |
| ASUSTek       | PRIME Z270-A                | [0f4a711f6a](https://linux-hardware.org/?probe=0f4a711f6a) | Oct 08, 2022 |
| ASRock        | H77M                        | [4ce05e4d0a](https://linux-hardware.org/?probe=4ce05e4d0a) | Oct 07, 2022 |
| Packard Be... | IMEDIA S3712                | [a528de7c22](https://linux-hardware.org/?probe=a528de7c22) | Oct 06, 2022 |
| ASUSTek       | PRIME H270-PRO              | [bbf95bf34d](https://linux-hardware.org/?probe=bbf95bf34d) | Oct 06, 2022 |
| ASUSTek       | ET1612I                     | [91fea00cbf](https://linux-hardware.org/?probe=91fea00cbf) | Oct 06, 2022 |
| HP            | 3398                        | [7dd62dded1](https://linux-hardware.org/?probe=7dd62dded1) | Oct 05, 2022 |
| HP            | 1906                        | [a6f705f119](https://linux-hardware.org/?probe=a6f705f119) | Oct 03, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN         | [f6a6361e08](https://linux-hardware.org/?probe=f6a6361e08) | Oct 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [10e3123558](https://linux-hardware.org/?probe=10e3123558) | Oct 03, 2022 |
| ASUSTek       | P8Z68-V LX                  | [42b887e821](https://linux-hardware.org/?probe=42b887e821) | Oct 03, 2022 |
| Pegatron      | 2AC3                        | [0ea51f0746](https://linux-hardware.org/?probe=0ea51f0746) | Oct 03, 2022 |
| AZW           | Gemini X45                  | [721b4545a2](https://linux-hardware.org/?probe=721b4545a2) | Oct 02, 2022 |
| Packard Be... | IMEDIA S3712                | [1fd820d1d0](https://linux-hardware.org/?probe=1fd820d1d0) | Oct 01, 2022 |
| ASRock        | 970 Pro3 R2.0               | [592adc6c9b](https://linux-hardware.org/?probe=592adc6c9b) | Oct 01, 2022 |
| Dell          | 0YXT71 A02                  | [f36bc1d24e](https://linux-hardware.org/?probe=f36bc1d24e) | Sep 29, 2022 |
| ASRock        | J3160DC-ITX                 | [7e1818288f](https://linux-hardware.org/?probe=7e1818288f) | Sep 29, 2022 |
| Gigabyte      | F2A55M-DS2                  | [c17c689217](https://linux-hardware.org/?probe=c17c689217) | Sep 28, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | [960c35d712](https://linux-hardware.org/?probe=960c35d712) | Sep 28, 2022 |
| Dell          | 09M8Y8 A01                  | [f129c4da4a](https://linux-hardware.org/?probe=f129c4da4a) | Sep 28, 2022 |
| Packard Be... | IMEDIA L4875 v1.0           | [bb57b80866](https://linux-hardware.org/?probe=bb57b80866) | Sep 27, 2022 |
| HP            | 8433 11                     | [a1d424bced](https://linux-hardware.org/?probe=a1d424bced) | Sep 27, 2022 |
| ASRock        | AB350 Gaming K4             | [184070d232](https://linux-hardware.org/?probe=184070d232) | Sep 26, 2022 |
| ASRock        | 775Dual-VSTA                | [9509fb65dd](https://linux-hardware.org/?probe=9509fb65dd) | Sep 26, 2022 |
| ASUSTek       | H81M-K                      | [badc988393](https://linux-hardware.org/?probe=badc988393) | Sep 26, 2022 |
| Packard Be... | IMEDIA L4875 v1.0           | [4ed673ff1a](https://linux-hardware.org/?probe=4ed673ff1a) | Sep 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [65d54e7273](https://linux-hardware.org/?probe=65d54e7273) | Sep 25, 2022 |
| ASUSTek       | P8H61-M LX                  | [164f5bfea2](https://linux-hardware.org/?probe=164f5bfea2) | Sep 25, 2022 |
| HP            | 8433 11                     | [dffc61c155](https://linux-hardware.org/?probe=dffc61c155) | Sep 24, 2022 |
| ASRock        | 4CoreDual-SATA2             | [eb0e992df7](https://linux-hardware.org/?probe=eb0e992df7) | Sep 24, 2022 |
| ASUSTek       | P8B75-M LE                  | [8975676700](https://linux-hardware.org/?probe=8975676700) | Sep 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [fd43d92335](https://linux-hardware.org/?probe=fd43d92335) | Sep 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [a4ce7c179e](https://linux-hardware.org/?probe=a4ce7c179e) | Sep 23, 2022 |
| Fujitsu Si... | P5LD2-FM-DH-VP              | [0c6cbcc99d](https://linux-hardware.org/?probe=0c6cbcc99d) | Sep 22, 2022 |
| ASUSTek       | M3N78-VM                    | [edaab96cde](https://linux-hardware.org/?probe=edaab96cde) | Sep 21, 2022 |
| Dell          | 09M8Y8 A01                  | [07dd388834](https://linux-hardware.org/?probe=07dd388834) | Sep 21, 2022 |
| Dell          | 0GM819                      | [951ce34bb2](https://linux-hardware.org/?probe=951ce34bb2) | Sep 21, 2022 |
| Lenovo        | ThinkCentre M57 6072WMD     | [eb8221088f](https://linux-hardware.org/?probe=eb8221088f) | Sep 21, 2022 |
| Dell          | 09M8Y8 A01                  | [2c7466119d](https://linux-hardware.org/?probe=2c7466119d) | Sep 21, 2022 |
| Intel         | H55                         | [6de435d14c](https://linux-hardware.org/?probe=6de435d14c) | Sep 20, 2022 |
| ASUSTek       | G20CB                       | [34f4d43b97](https://linux-hardware.org/?probe=34f4d43b97) | Sep 20, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [9c483616f6](https://linux-hardware.org/?probe=9c483616f6) | Sep 20, 2022 |
| Acer          | Aspire M3970                | [d135989361](https://linux-hardware.org/?probe=d135989361) | Sep 19, 2022 |
| Supermicro    | C7P67                       | [16bff71d62](https://linux-hardware.org/?probe=16bff71d62) | Sep 19, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [75be2db65c](https://linux-hardware.org/?probe=75be2db65c) | Sep 19, 2022 |
| HP            | 2B29                        | [391e407d29](https://linux-hardware.org/?probe=391e407d29) | Sep 18, 2022 |
| ASRock        | 960GC-GS FX                 | [2432fca2f8](https://linux-hardware.org/?probe=2432fca2f8) | Sep 18, 2022 |
| ASRock        | 960GC-GS FX                 | [3e40742ff0](https://linux-hardware.org/?probe=3e40742ff0) | Sep 18, 2022 |
| MSI           | Boston                      | [b884bd8c03](https://linux-hardware.org/?probe=b884bd8c03) | Sep 17, 2022 |
| ASUSTek       | P5K                         | [4cf17a7b6f](https://linux-hardware.org/?probe=4cf17a7b6f) | Sep 17, 2022 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | [3ba3a4becf](https://linux-hardware.org/?probe=3ba3a4becf) | Sep 16, 2022 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | [e6fe8aa148](https://linux-hardware.org/?probe=e6fe8aa148) | Sep 16, 2022 |
| ASUSTek       | ET1612I                     | [0ddd9554cc](https://linux-hardware.org/?probe=0ddd9554cc) | Sep 16, 2022 |
| ASRock        | X370 Gaming K4              | [0858e80da7](https://linux-hardware.org/?probe=0858e80da7) | Sep 15, 2022 |
| ASUSTek       | PRIME H410M-E               | [91f1fdc978](https://linux-hardware.org/?probe=91f1fdc978) | Sep 14, 2022 |
| Dell          | 0WR7PY A02                  | [0a587d6fee](https://linux-hardware.org/?probe=0a587d6fee) | Sep 14, 2022 |
| ASRock        | H61M-DGS                    | [aeac7cfb74](https://linux-hardware.org/?probe=aeac7cfb74) | Sep 14, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [d3f957e34a](https://linux-hardware.org/?probe=d3f957e34a) | Sep 13, 2022 |
| ASUSTek       | G20CB                       | [a52ff97f3b](https://linux-hardware.org/?probe=a52ff97f3b) | Sep 12, 2022 |
| ASUSTek       | G20CB                       | [2d737743f4](https://linux-hardware.org/?probe=2d737743f4) | Sep 12, 2022 |
| ASRock        | B450 Gaming K4              | [2391f4673a](https://linux-hardware.org/?probe=2391f4673a) | Sep 12, 2022 |
| ASRock        | B450 Gaming K4              | [89963f6bf1](https://linux-hardware.org/?probe=89963f6bf1) | Sep 12, 2022 |
| MSI           | X58 Pro                     | [60406c82e8](https://linux-hardware.org/?probe=60406c82e8) | Sep 12, 2022 |
| Acer          | E415SM                      | [bc9ef15cab](https://linux-hardware.org/?probe=bc9ef15cab) | Sep 11, 2022 |
| Acer          | E415SM                      | [4f8a53c667](https://linux-hardware.org/?probe=4f8a53c667) | Sep 11, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [b76fc41706](https://linux-hardware.org/?probe=b76fc41706) | Sep 11, 2022 |
| Fujitsu Si... | P5LD2-FM-DH-VP              | [ad6a16f658](https://linux-hardware.org/?probe=ad6a16f658) | Sep 11, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [4df5d0194d](https://linux-hardware.org/?probe=4df5d0194d) | Sep 11, 2022 |
| Gigabyte      | Z77X-UP7                    | [1634db2e78](https://linux-hardware.org/?probe=1634db2e78) | Sep 11, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [ee06685499](https://linux-hardware.org/?probe=ee06685499) | Sep 11, 2022 |
| Dell          | 09M8Y8 A01                  | [c719d7f544](https://linux-hardware.org/?probe=c719d7f544) | Sep 11, 2022 |
| Dell          | 03NVJ6 A01                  | [3f51b6da48](https://linux-hardware.org/?probe=3f51b6da48) | Sep 10, 2022 |
| ASRock        | J3160DC-ITX                 | [e854b82ab9](https://linux-hardware.org/?probe=e854b82ab9) | Sep 10, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [174c263499](https://linux-hardware.org/?probe=174c263499) | Sep 08, 2022 |
| Gigabyte      | Z97-HD3                     | [aeb2bae778](https://linux-hardware.org/?probe=aeb2bae778) | Sep 08, 2022 |
| Intel         | DH77DF AAG40293-300         | [217971d572](https://linux-hardware.org/?probe=217971d572) | Sep 08, 2022 |
| ASRock        | N3700-ITX                   | [5af515a1f9](https://linux-hardware.org/?probe=5af515a1f9) | Sep 08, 2022 |
| Gigabyte      | Z97-HD3                     | [d5040ffbda](https://linux-hardware.org/?probe=d5040ffbda) | Sep 08, 2022 |
| MSI           | H61M-P31                    | [56a8b0b2a7](https://linux-hardware.org/?probe=56a8b0b2a7) | Sep 08, 2022 |
| Pegatron      | 2A9Eh                       | [2c7b59f70b](https://linux-hardware.org/?probe=2c7b59f70b) | Sep 08, 2022 |
| HP            | 3397                        | [0ebeef29bf](https://linux-hardware.org/?probe=0ebeef29bf) | Sep 07, 2022 |
| Lenovo        | MAHOBAY                     | [2619e261d1](https://linux-hardware.org/?probe=2619e261d1) | Sep 07, 2022 |
| Pegatron      | Narra6                      | [b2a70f42a0](https://linux-hardware.org/?probe=b2a70f42a0) | Sep 07, 2022 |
| ASRock        | Q1900M                      | [05cf506f57](https://linux-hardware.org/?probe=05cf506f57) | Sep 06, 2022 |
| ASUSTek       | STRIKER II EXTREME          | [42e666abe1](https://linux-hardware.org/?probe=42e666abe1) | Sep 06, 2022 |
| ASUSTek       | P8H77-V LE                  | [8a1c5532d6](https://linux-hardware.org/?probe=8a1c5532d6) | Sep 06, 2022 |
| ASUSTek       | P8H77-V LE                  | [cc631912bf](https://linux-hardware.org/?probe=cc631912bf) | Sep 06, 2022 |
| ASUSTek       | P9X79 PRO                   | [7e53f87cc4](https://linux-hardware.org/?probe=7e53f87cc4) | Sep 06, 2022 |
| ASUSTek       | H81M-PLUS                   | [826b486f77](https://linux-hardware.org/?probe=826b486f77) | Sep 05, 2022 |
| HP            | 0B4Ch D                     | [87c4023810](https://linux-hardware.org/?probe=87c4023810) | Sep 05, 2022 |
| ASRock        | Q1900M                      | [6b53538e90](https://linux-hardware.org/?probe=6b53538e90) | Sep 05, 2022 |
| ASUSTek       | PRIME X370-PRO              | [312e33b434](https://linux-hardware.org/?probe=312e33b434) | Sep 05, 2022 |
| Dell          | 0MWYPT A01                  | [57b81c35c1](https://linux-hardware.org/?probe=57b81c35c1) | Sep 05, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [e83fa739c9](https://linux-hardware.org/?probe=e83fa739c9) | Sep 05, 2022 |
| ASUSTek       | STRIKER II EXTREME          | [502995e6f3](https://linux-hardware.org/?probe=502995e6f3) | Sep 05, 2022 |
| MSI           | B550-A PRO                  | [950b2a8eb5](https://linux-hardware.org/?probe=950b2a8eb5) | Sep 05, 2022 |
| ASUSTek       | P9X79 DELUXE                | [2aa7ada396](https://linux-hardware.org/?probe=2aa7ada396) | Sep 05, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [127c2f5f75](https://linux-hardware.org/?probe=127c2f5f75) | Sep 05, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | [26e63d2357](https://linux-hardware.org/?probe=26e63d2357) | Sep 05, 2022 |
| Dell          | 0HY9JP A02                  | [7cbf141461](https://linux-hardware.org/?probe=7cbf141461) | Sep 05, 2022 |
| Lenovo        | 367D 31900003 STD           | [c145bac65a](https://linux-hardware.org/?probe=c145bac65a) | Sep 05, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [7c87d1ad42](https://linux-hardware.org/?probe=7c87d1ad42) | Sep 05, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [43267285d4](https://linux-hardware.org/?probe=43267285d4) | Sep 04, 2022 |
| Gigabyte      | B450M DS3H-CF               | [008133bf59](https://linux-hardware.org/?probe=008133bf59) | Sep 04, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [9cd2bcff37](https://linux-hardware.org/?probe=9cd2bcff37) | Sep 04, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [4a27f8b033](https://linux-hardware.org/?probe=4a27f8b033) | Sep 04, 2022 |
| ASRock        | Q1900M                      | [55a86f60b9](https://linux-hardware.org/?probe=55a86f60b9) | Sep 04, 2022 |
| ASUSTek       | P5P43TD                     | [cca9e79d90](https://linux-hardware.org/?probe=cca9e79d90) | Sep 04, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [2cf13f4045](https://linux-hardware.org/?probe=2cf13f4045) | Sep 04, 2022 |
| Lenovo        | SKYBAY SDK0J40709 WIN 32... | [ed16086671](https://linux-hardware.org/?probe=ed16086671) | Sep 04, 2022 |
| ASUSTek       | UN45                        | [87eca02296](https://linux-hardware.org/?probe=87eca02296) | Sep 04, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [bf4936f3bc](https://linux-hardware.org/?probe=bf4936f3bc) | Sep 04, 2022 |
| ASRock        | H370M-ITX/ac                | [1a577be107](https://linux-hardware.org/?probe=1a577be107) | Sep 04, 2022 |
| ASUSTek       | PRIME A320M-K               | [878661705c](https://linux-hardware.org/?probe=878661705c) | Sep 04, 2022 |
| Dell          | 0T1D10 A01                  | [3064d08dc1](https://linux-hardware.org/?probe=3064d08dc1) | Sep 03, 2022 |
| ASUSTek       | PRIME H470-PLUS             | [e80ac4d271](https://linux-hardware.org/?probe=e80ac4d271) | Sep 03, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [312013ef36](https://linux-hardware.org/?probe=312013ef36) | Sep 03, 2022 |
| Dell          | 0HMF7C A01                  | [292123f83b](https://linux-hardware.org/?probe=292123f83b) | Sep 03, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [6de688d21a](https://linux-hardware.org/?probe=6de688d21a) | Sep 03, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [159c1dcd33](https://linux-hardware.org/?probe=159c1dcd33) | Sep 03, 2022 |
| ASUSTek       | P5KC                        | [602e22310b](https://linux-hardware.org/?probe=602e22310b) | Sep 03, 2022 |
| MSI           | B450-A PRO MAX              | [0c89daf254](https://linux-hardware.org/?probe=0c89daf254) | Sep 03, 2022 |
| MSI           | X570-A PRO                  | [e20b509508](https://linux-hardware.org/?probe=e20b509508) | Sep 03, 2022 |
| ASUSTek       | P7P55D                      | [ad2b0a0a89](https://linux-hardware.org/?probe=ad2b0a0a89) | Sep 03, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [b9f43af7d0](https://linux-hardware.org/?probe=b9f43af7d0) | Sep 03, 2022 |
| ASRock        | H310CM-HDV                  | [df5d5f2e7f](https://linux-hardware.org/?probe=df5d5f2e7f) | Sep 03, 2022 |
| Gigabyte      | Z97X-UD5H-BK                | [97a21d48e0](https://linux-hardware.org/?probe=97a21d48e0) | Sep 03, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [5dcc9cd8c8](https://linux-hardware.org/?probe=5dcc9cd8c8) | Sep 03, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [9cab157472](https://linux-hardware.org/?probe=9cab157472) | Sep 03, 2022 |
| ASUSTek       | Z170-K                      | [d47c5fe35c](https://linux-hardware.org/?probe=d47c5fe35c) | Sep 03, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [9b8eef74b8](https://linux-hardware.org/?probe=9b8eef74b8) | Sep 03, 2022 |
| ASRock        | A320M-HDV                   | [5a9342d8e9](https://linux-hardware.org/?probe=5a9342d8e9) | Sep 03, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [982df83fdf](https://linux-hardware.org/?probe=982df83fdf) | Sep 03, 2022 |
| Dell          | 02YYK5 A00                  | [742579c33d](https://linux-hardware.org/?probe=742579c33d) | Sep 03, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [32d39c8b65](https://linux-hardware.org/?probe=32d39c8b65) | Sep 03, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [709825bde3](https://linux-hardware.org/?probe=709825bde3) | Sep 03, 2022 |
| ASUSTek       | PRIME H270-PRO              | [5c0b32f572](https://linux-hardware.org/?probe=5c0b32f572) | Sep 03, 2022 |
| MSI           | H170 GAMING M3              | [b0d669cf4b](https://linux-hardware.org/?probe=b0d669cf4b) | Sep 03, 2022 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [c13f075f83](https://linux-hardware.org/?probe=c13f075f83) | Sep 03, 2022 |
| ASRock        | 4CoreDual-SATA2             | [c64d84d331](https://linux-hardware.org/?probe=c64d84d331) | Sep 03, 2022 |
| ASRock        | X470 Taichi                 | [0a6ff089f1](https://linux-hardware.org/?probe=0a6ff089f1) | Sep 03, 2022 |
| MSI           | X470 GAMING PRO MAX         | [7f10b8002b](https://linux-hardware.org/?probe=7f10b8002b) | Sep 03, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [65562b09e0](https://linux-hardware.org/?probe=65562b09e0) | Sep 03, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [a591a1fecf](https://linux-hardware.org/?probe=a591a1fecf) | Sep 03, 2022 |
| ASRock        | FM2A88X-ITX+                | [9c22b70a4f](https://linux-hardware.org/?probe=9c22b70a4f) | Sep 03, 2022 |
| MSI           | B550-A PRO                  | [65bfdaa6ea](https://linux-hardware.org/?probe=65bfdaa6ea) | Sep 03, 2022 |
| Gigabyte      | B560M DS3H V2               | [4d9025cf5c](https://linux-hardware.org/?probe=4d9025cf5c) | Sep 03, 2022 |
| BESSTAR Te... | UM350                       | [02423b61e0](https://linux-hardware.org/?probe=02423b61e0) | Sep 03, 2022 |
| ASUSTek       | PRIME A320M-K               | [acfa42b951](https://linux-hardware.org/?probe=acfa42b951) | Sep 03, 2022 |
| Dell          | 0F6X5P A00                  | [71ff7749aa](https://linux-hardware.org/?probe=71ff7749aa) | Sep 03, 2022 |
| OEM           | G41 775 ICH7 8712           | [4c9041cf15](https://linux-hardware.org/?probe=4c9041cf15) | Sep 03, 2022 |
| HP            | 3397                        | [5cd2349a9c](https://linux-hardware.org/?probe=5cd2349a9c) | Sep 02, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [7829cfc920](https://linux-hardware.org/?probe=7829cfc920) | Sep 02, 2022 |
| ASUSTek       | STRIKER II EXTREME          | [5485918ea2](https://linux-hardware.org/?probe=5485918ea2) | Sep 02, 2022 |
| ASUSTek       | P8H77-V LE                  | [f77ecfe3bc](https://linux-hardware.org/?probe=f77ecfe3bc) | Sep 02, 2022 |
| Pegatron      | 2AB6                        | [c4ca3989e0](https://linux-hardware.org/?probe=c4ca3989e0) | Aug 31, 2022 |
| HP            | 18E9                        | [2dff78f303](https://linux-hardware.org/?probe=2dff78f303) | Aug 31, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [98e0a08e65](https://linux-hardware.org/?probe=98e0a08e65) | Aug 30, 2022 |
| ASUSTek       | P5QPL-AM                    | [38e6481a65](https://linux-hardware.org/?probe=38e6481a65) | Aug 30, 2022 |
| OEM           | G41 775 ICH7 8712           | [4225df6517](https://linux-hardware.org/?probe=4225df6517) | Aug 29, 2022 |
| ASUSTek       | Z97-C                       | [9bdae9239f](https://linux-hardware.org/?probe=9bdae9239f) | Aug 29, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [7a2c713719](https://linux-hardware.org/?probe=7a2c713719) | Aug 29, 2022 |
| HP            | 8751                        | [62c8c2f25e](https://linux-hardware.org/?probe=62c8c2f25e) | Aug 29, 2022 |
| ASUSTek       | P5KPL-AM SE                 | [17e8c1560b](https://linux-hardware.org/?probe=17e8c1560b) | Aug 28, 2022 |
| ASRock        | H61M-DGS                    | [023204fa1f](https://linux-hardware.org/?probe=023204fa1f) | Aug 28, 2022 |
| Gigabyte      | H97-HD3                     | [25e4d6c064](https://linux-hardware.org/?probe=25e4d6c064) | Aug 28, 2022 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [f74dc71ad8](https://linux-hardware.org/?probe=f74dc71ad8) | Aug 27, 2022 |
| Gigabyte      | Z490 UD                     | [a872472b1c](https://linux-hardware.org/?probe=a872472b1c) | Aug 26, 2022 |
| Intel         | D2550MUD2 AAG81497-700      | [a181512016](https://linux-hardware.org/?probe=a181512016) | Aug 26, 2022 |
| ASUSTek       | M5A78L LE                   | [e4a6425675](https://linux-hardware.org/?probe=e4a6425675) | Aug 26, 2022 |
| ASUSTek       | PRIME A320M-K               | [a096217ea3](https://linux-hardware.org/?probe=a096217ea3) | Aug 24, 2022 |
| ASUSTek       | M4N68T-M-V2                 | [1528da74f6](https://linux-hardware.org/?probe=1528da74f6) | Aug 22, 2022 |
| ASUSTek       | PRIME Z390-P                | [ca7534d4dc](https://linux-hardware.org/?probe=ca7534d4dc) | Aug 22, 2022 |
| ASUSTek       | H110M-A/M.2                 | [dab0f526b0](https://linux-hardware.org/?probe=dab0f526b0) | Aug 22, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [e064c453da](https://linux-hardware.org/?probe=e064c453da) | Aug 21, 2022 |
| Gigabyte      | P35-DS3L                    | [1ee42449ed](https://linux-hardware.org/?probe=1ee42449ed) | Aug 21, 2022 |
| OEM           | G41 775 ICH7 8712           | [71bfa72a22](https://linux-hardware.org/?probe=71bfa72a22) | Aug 21, 2022 |
| MSI           | G31M3                       | [3bb7906f56](https://linux-hardware.org/?probe=3bb7906f56) | Aug 20, 2022 |
| AZW           | MII-V                       | [59698f6b33](https://linux-hardware.org/?probe=59698f6b33) | Aug 20, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [57f1970999](https://linux-hardware.org/?probe=57f1970999) | Aug 20, 2022 |
| MSI           | Boston                      | [4a10f122a2](https://linux-hardware.org/?probe=4a10f122a2) | Aug 19, 2022 |
| Gigabyte      | Z370 HD3P-CF                | [410c71e7ef](https://linux-hardware.org/?probe=410c71e7ef) | Aug 18, 2022 |
| Acer          | MRS600M                     | [ec4c10d06e](https://linux-hardware.org/?probe=ec4c10d06e) | Aug 17, 2022 |
| ASRock        | 775Dual-VSTA                | [89ac2bb6fe](https://linux-hardware.org/?probe=89ac2bb6fe) | Aug 17, 2022 |
| HP            | 1495                        | [34b69b08b1](https://linux-hardware.org/?probe=34b69b08b1) | Aug 15, 2022 |
| HP            | 1495                        | [6db4307c50](https://linux-hardware.org/?probe=6db4307c50) | Aug 15, 2022 |
| HP            | 1495                        | [c122ce06ab](https://linux-hardware.org/?probe=c122ce06ab) | Aug 15, 2022 |
| ASUSTek       | PRIME B450M-A II            | [4ba26713bc](https://linux-hardware.org/?probe=4ba26713bc) | Aug 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [fd06db829d](https://linux-hardware.org/?probe=fd06db829d) | Aug 14, 2022 |
| Gigabyte      | Z370 HD3P-CF                | [2162cafc91](https://linux-hardware.org/?probe=2162cafc91) | Aug 13, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | [6a0c6ab778](https://linux-hardware.org/?probe=6a0c6ab778) | Aug 13, 2022 |
| AZW           | U59                         | [344d4587f6](https://linux-hardware.org/?probe=344d4587f6) | Aug 12, 2022 |
| Lenovo        | ThinkStation C20 4263BA7    | [e5e5d0d3a3](https://linux-hardware.org/?probe=e5e5d0d3a3) | Aug 11, 2022 |
| Lenovo        | ThinkStation C20 4263BA7    | [93ecf84dcf](https://linux-hardware.org/?probe=93ecf84dcf) | Aug 11, 2022 |
| ASRock        | G41M-VS3                    | [4185ab0f97](https://linux-hardware.org/?probe=4185ab0f97) | Aug 10, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | [7792f4471e](https://linux-hardware.org/?probe=7792f4471e) | Aug 10, 2022 |
| ASRock        | H55M-LE                     | [841c63de14](https://linux-hardware.org/?probe=841c63de14) | Aug 08, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [7ca881aae7](https://linux-hardware.org/?probe=7ca881aae7) | Aug 08, 2022 |
| Acer          | Predator PO3-620            | [ff0507688f](https://linux-hardware.org/?probe=ff0507688f) | Aug 02, 2022 |
| Acer          | FIH57                       | [eec3e58c8c](https://linux-hardware.org/?probe=eec3e58c8c) | Aug 02, 2022 |
| Acer          | FIH57                       | [a6b9d91f36](https://linux-hardware.org/?probe=a6b9d91f36) | Jul 30, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Italy/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Ubuntu 20.04        | 374      | 13.83%  |
| Ubuntu 18.04        | 242      | 8.95%   |
| Ubuntu 22.04        | 114      | 4.22%   |
| OpenMandriva 4.2    | 102      | 3.77%   |
| OpenMandriva 4.3    | 79       | 2.92%   |
| Debian 11           | 60       | 2.22%   |
| Arch Rolling        | 58       | 2.14%   |
| Ubuntu 20.10        | 51       | 1.89%   |
| Ubuntu 19.04        | 47       | 1.74%   |
| OpenMandriva 23.01  | 43       | 1.59%   |
| KDE neon 20.04      | 43       | 1.59%   |
| Fedora 36           | 43       | 1.59%   |
| Ubuntu 19.10        | 42       | 1.55%   |
| Ubuntu 22.10        | 40       | 1.48%   |
| Xubuntu 20.04       | 37       | 1.37%   |
| Linux Mint 20.3     | 36       | 1.33%   |
| Arch                | 36       | 1.33%   |
| Zorin 16            | 34       | 1.26%   |
| Xubuntu 18.04       | 34       | 1.26%   |
| ROSA R10            | 32       | 1.18%   |
| Linux Mint 21.1     | 32       | 1.18%   |
| Ubuntu 21.10        | 31       | 1.15%   |
| Ubuntu 21.04        | 31       | 1.15%   |
| Manjaro             | 31       | 1.15%   |
| Linux Mint 21       | 31       | 1.15%   |
| Debian 10           | 31       | 1.15%   |
| Pop!_OS 22.04       | 27       | 1%      |
| Linux Mint 19.3     | 26       | 0.96%   |
| Kubuntu 20.04       | 26       | 0.96%   |
| Ubuntu 18.10        | 24       | 0.89%   |
| Linux Mint 20.2     | 22       | 0.81%   |
| Linux Mint 20.1     | 22       | 0.81%   |
| Linux Mint 20       | 22       | 0.81%   |
| EndeavourOS Rolling | 21       | 0.78%   |
| ROSA R11            | 20       | 0.74%   |
| ROSA R9             | 19       | 0.7%    |
| Fedora 37           | 19       | 0.7%    |
| Zorin 15            | 18       | 0.67%   |
| Pop!_OS 20.10       | 18       | 0.67%   |
| Fedora 35           | 17       | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 961      | 37.55%  |
| OpenMandriva  | 250      | 9.77%   |
| Linux Mint    | 200      | 7.82%   |
| Fedora        | 121      | 4.73%   |
| Debian        | 117      | 4.57%   |
| Xubuntu       | 108      | 4.22%   |
| ROSA          | 93       | 3.63%   |
| Arch          | 93       | 3.63%   |
| Manjaro       | 75       | 2.93%   |
| Pop!_OS       | 73       | 2.85%   |
| Kubuntu       | 65       | 2.54%   |
| KDE neon      | 60       | 2.34%   |
| Zorin         | 56       | 2.19%   |
| Lubuntu       | 27       | 1.06%   |
| Ubuntu MATE   | 26       | 1.02%   |
| EndeavourOS   | 25       | 0.98%   |
| openSUSE      | 20       | 0.78%   |
| Ubuntu Unity  | 18       | 0.7%    |
| Clear Linux   | 14       | 0.55%   |
| BlackPanther  | 14       | 0.55%   |
| Elementary    | 13       | 0.51%   |
| LMDE          | 11       | 0.43%   |
| Gentoo        | 10       | 0.39%   |
| Endless       | 10       | 0.39%   |
| Peppermint    | 9        | 0.35%   |
| MX            | 9        | 0.35%   |
| ArcoLinux     | 9        | 0.35%   |
| Garuda Linux  | 7        | 0.27%   |
| Ubuntu Studio | 6        | 0.23%   |
| Nobara        | 5        | 0.2%    |
| Kali          | 5        | 0.2%    |
| Slackware     | 4        | 0.16%   |
| LinuxFX       | 4        | 0.16%   |
| CentOS        | 4        | 0.16%   |
| Q4OS          | 3        | 0.12%   |
| Ubuntu Budgie | 2        | 0.08%   |
| Rocky Linux   | 2        | 0.08%   |
| RHEL          | 2        | 0.08%   |
| Puppy         | 2        | 0.08%   |
| Parrot        | 2        | 0.08%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002        | 100      | 3.3%    |
| 5.16.7-desktop-1omv4003         | 77       | 2.54%   |
| 5.15.0-52-generic               | 57       | 1.88%   |
| 5.4.0-42-generic                | 52       | 1.72%   |
| 5.4.0-52-generic                | 43       | 1.42%   |
| 5.15.0-56-generic               | 41       | 1.35%   |
| 6.1.1-desktop-1omv2290          | 36       | 1.19%   |
| 5.15.0-47-generic               | 33       | 1.09%   |
| 5.15.0-58-generic               | 25       | 0.83%   |
| 5.4.0-58-generic                | 24       | 0.79%   |
| 5.4.0-48-generic                | 24       | 0.79%   |
| 5.3.0-46-generic                | 23       | 0.76%   |
| 5.3.0-40-generic                | 23       | 0.76%   |
| 5.4.0-56-generic                | 22       | 0.73%   |
| 5.4.0-29-generic                | 21       | 0.69%   |
| 5.4.0-26-generic                | 21       | 0.69%   |
| 5.15.0-46-generic               | 21       | 0.69%   |
| 5.4.0-54-generic                | 20       | 0.66%   |
| 5.4.0-40-generic                | 19       | 0.63%   |
| 5.4.0-28-generic                | 18       | 0.59%   |
| 5.11.0-38-generic               | 18       | 0.59%   |
| 5.0.0-32-generic                | 18       | 0.59%   |
| 5.8.0-59-generic                | 16       | 0.53%   |
| 5.4.0-37-generic                | 16       | 0.53%   |
| 5.15.0-60-generic               | 16       | 0.53%   |
| 5.8.0-41-generic                | 15       | 0.5%    |
| 5.4.0-65-generic                | 15       | 0.5%    |
| 5.4.0-33-generic                | 15       | 0.5%    |
| 5.3.0-42-generic                | 15       | 0.5%    |
| 5.19.0-35-generic               | 15       | 0.5%    |
| 5.4.0-47-generic                | 14       | 0.46%   |
| 5.4.0-31-generic                | 14       | 0.46%   |
| 5.19.0-23-generic               | 14       | 0.46%   |
| 5.15.0-43-generic               | 14       | 0.46%   |
| 5.10.0-19-amd64                 | 14       | 0.46%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 14       | 0.46%   |
| 4.18.16-desktop-1bP             | 14       | 0.46%   |
| 4.18.0-25-generic               | 14       | 0.46%   |
| 5.8.0-48-generic                | 13       | 0.43%   |
| 5.13.0-39-generic               | 13       | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 510      | 18.23%  |
| 5.15.0  | 258      | 9.22%   |
| 4.15.0  | 209      | 7.47%   |
| 5.8.0   | 162      | 5.79%   |
| 5.3.0   | 140      | 5%      |
| 5.11.0  | 115      | 4.11%   |
| 5.10.14 | 101      | 3.61%   |
| 5.0.0   | 99       | 3.54%   |
| 5.13.0  | 84       | 3%      |
| 5.19.0  | 80       | 2.86%   |
| 5.16.7  | 78       | 2.79%   |
| 5.10.0  | 70       | 2.5%    |
| 4.18.0  | 65       | 2.32%   |
| 6.1.1   | 41       | 1.47%   |
| 4.19.0  | 29       | 1.04%   |
| 6.0.2   | 27       | 0.96%   |
| 4.9.60  | 18       | 0.64%   |
| 4.9.20  | 17       | 0.61%   |
| 5.19.6  | 15       | 0.54%   |
| 4.18.16 | 15       | 0.54%   |
| 6.0.6   | 14       | 0.5%    |
| 5.19.16 | 13       | 0.46%   |
| 6.0.10  | 11       | 0.39%   |
| 6.0.12  | 10       | 0.36%   |
| 5.17.5  | 10       | 0.36%   |
| 4.4.0   | 10       | 0.36%   |
| 6.2.6   | 9        | 0.32%   |
| 6.1.0   | 8        | 0.29%   |
| 5.12.4  | 8        | 0.29%   |
| 6.1.8   | 7        | 0.25%   |
| 6.1.4   | 7        | 0.25%   |
| 6.0.9   | 7        | 0.25%   |
| 6.0.8   | 7        | 0.25%   |
| 6.0.5   | 7        | 0.25%   |
| 6.0.0   | 7        | 0.25%   |
| 5.19.4  | 7        | 0.25%   |
| 5.18.12 | 7        | 0.25%   |
| 5.16.11 | 7        | 0.25%   |
| 6.0.7   | 6        | 0.21%   |
| 5.9.16  | 6        | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 537      | 19.44%  |
| 5.15    | 312      | 11.3%   |
| 4.15    | 210      | 7.6%    |
| 5.10    | 200      | 7.24%   |
| 5.8     | 186      | 6.73%   |
| 5.3     | 145      | 5.25%   |
| 5.19    | 138      | 5%      |
| 5.11    | 134      | 4.85%   |
| 5.16    | 107      | 3.87%   |
| 5.0     | 102      | 3.69%   |
| 6.0     | 99       | 3.58%   |
| 5.13    | 93       | 3.37%   |
| 6.1     | 87       | 3.15%   |
| 4.18    | 84       | 3.04%   |
| 4.9     | 55       | 1.99%   |
| 4.19    | 39       | 1.41%   |
| 5.9     | 32       | 1.16%   |
| 5.17    | 29       | 1.05%   |
| 6.2     | 26       | 0.94%   |
| 5.18    | 26       | 0.94%   |
| 5.6     | 20       | 0.72%   |
| 5.12    | 20       | 0.72%   |
| 5.7     | 18       | 0.65%   |
| 5.14    | 16       | 0.58%   |
| 4.4     | 10       | 0.36%   |
| 4.1     | 10       | 0.36%   |
| 5.5     | 9        | 0.33%   |
| 4.13    | 5        | 0.18%   |
| 5.1     | 2        | 0.07%   |
| 4.20    | 2        | 0.07%   |
| 5.2     | 1        | 0.04%   |
| 4.8     | 1        | 0.04%   |
| 4.7     | 1        | 0.04%   |
| 4.17    | 1        | 0.04%   |
| 4.14    | 1        | 0.04%   |
| 4.12    | 1        | 0.04%   |
| 3.14    | 1        | 0.04%   |
| 3.10    | 1        | 0.04%   |
| 2.6.35  | 1        | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 2368     | 95.79%  |
| i686   | 104      | 4.21%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| GNOME            | 1009     | 39.02%  |
| KDE5             | 497      | 19.22%  |
| Unknown          | 361      | 13.96%  |
| XFCE             | 203      | 7.85%   |
| X-Cinnamon       | 165      | 6.38%   |
| MATE             | 77       | 2.98%   |
| KDE              | 61       | 2.36%   |
| KDE4             | 57       | 2.2%    |
| LXQt             | 35       | 1.35%   |
| Cinnamon         | 22       | 0.85%   |
| LXDE             | 21       | 0.81%   |
| Unity            | 18       | 0.7%    |
| Pantheon         | 12       | 0.46%   |
| GNOME Flashback  | 10       | 0.39%   |
| GNOME Classic    | 7        | 0.27%   |
| Deepin           | 5        | 0.19%   |
| Budgie           | 5        | 0.19%   |
| lightdm-xsession | 4        | 0.15%   |
| i3               | 4        | 0.15%   |
| Trinity          | 3        | 0.12%   |
| openbox          | 2        | 0.08%   |
| Hyprland         | 2        | 0.08%   |
| sway             | 1        | 0.04%   |
| Lubuntu          | 1        | 0.04%   |
| icewm            | 1        | 0.04%   |
| herbstluftwm     | 1        | 0.04%   |
| FVWM             | 1        | 0.04%   |
| bspwm            | 1        | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 2034     | 79.92%  |
| Wayland | 282      | 11.08%  |
| Unknown | 187      | 7.35%   |
| Tty     | 42       | 1.65%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1289     | 49.81%  |
| SDDM    | 467      | 18.04%  |
| GDM3    | 258      | 9.97%   |
| LightDM | 234      | 9.04%   |
| GDM     | 212      | 8.19%   |
| TDM     | 61       | 2.36%   |
| KDM     | 59       | 2.28%   |
| XDM     | 4        | 0.15%   |
| GREETD  | 2        | 0.08%   |
| NODM    | 1        | 0.04%   |
| LXDM    | 1        | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| it_IT       | 1620     | 63.91%  |
| en_US       | 408      | 16.09%  |
| Unknown     | 386      | 15.23%  |
| en_GB       | 46       | 1.81%   |
| C           | 41       | 1.62%   |
| de_DE       | 5        | 0.2%    |
| it_CH       | 4        | 0.16%   |
| fr_FR       | 4        | 0.16%   |
| ru_RU       | 3        | 0.12%   |
| en_IE       | 3        | 0.12%   |
| de_AT       | 3        | 0.12%   |
| de_IT       | 2        | 0.08%   |
| POSIX       | 1        | 0.04%   |
| it_ITutf8   | 1        | 0.04%   |
| it_IT@euro  | 1        | 0.04%   |
| it          | 1        | 0.04%   |
| hu_HU       | 1        | 0.04%   |
| es_MX       | 1        | 0.04%   |
| es_ES       | 1        | 0.04%   |
| en_US.ASCII | 1        | 0.04%   |
| en_AG       | 1        | 0.04%   |
| Default     | 1        | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1607     | 63.54%  |
| EFI  | 922      | 36.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 1918     | 75.69%  |
| Overlay | 289      | 11.4%   |
| Btrfs   | 141      | 5.56%   |
| Unknown | 117      | 4.62%   |
| Xfs     | 29       | 1.14%   |
| Zfs     | 10       | 0.39%   |
| Ext3    | 10       | 0.39%   |
| Ext2    | 7        | 0.28%   |
| Tmpfs   | 6        | 0.24%   |
| F2fs    | 4        | 0.16%   |
| Aufs    | 2        | 0.08%   |
| XXXX    | 1        | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1379     | 54.04%  |
| GPT     | 790      | 30.96%  |
| MBR     | 383      | 15.01%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1979     | 77.79%  |
| Yes       | 565      | 22.21%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1460     | 57.59%  |
| Yes       | 1075     | 42.41%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 784      | 31.75%  |
| ASRock              | 312      | 12.64%  |
| MSI                 | 292      | 11.83%  |
| Gigabyte Technology | 235      | 9.52%   |
| Hewlett-Packard     | 194      | 7.86%   |
| Dell                | 119      | 4.82%   |
| Acer                | 100      | 4.05%   |
| Lenovo              | 80       | 3.24%   |
| Intel               | 56       | 2.27%   |
| Pegatron            | 41       | 1.66%   |
| Fujitsu             | 34       | 1.38%   |
| Unknown             | 34       | 1.38%   |
| Packard Bell        | 26       | 1.05%   |
| Foxconn             | 22       | 0.89%   |
| Fujitsu Siemens     | 12       | 0.49%   |
| Supermicro          | 10       | 0.41%   |
| AMI                 | 10       | 0.41%   |
| Biostar             | 8        | 0.32%   |
| BESSTAR Tech        | 8        | 0.32%   |
| AZW                 | 8        | 0.32%   |
| ABIT                | 6        | 0.24%   |
| TYAN Computer       | 5        | 0.2%    |
| Sapphire            | 5        | 0.2%    |
| IBM                 | 5        | 0.2%    |
| Apple               | 5        | 0.2%    |
| Wistron             | 4        | 0.16%   |
| NEC Computers       | 4        | 0.16%   |
| Gateway             | 3        | 0.12%   |
| ECS                 | 3        | 0.12%   |
| Alienware           | 3        | 0.12%   |
| YANYU               | 2        | 0.08%   |
| Shuttle             | 2        | 0.08%   |
| Proline             | 2        | 0.08%   |
| OEM                 | 2        | 0.08%   |
| LattePanda          | 2        | 0.08%   |
| Huanan              | 2        | 0.08%   |
| eMachines           | 2        | 0.08%   |
| American Megatrends | 2        | 0.08%   |
| AAEON               | 2        | 0.08%   |
| ZOTAC               | 1        | 0.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS All Series                  | 70       | 2.84%   |
| Unknown                          | 35       | 1.42%   |
| ASUS PRIME A320M-K               | 16       | 0.65%   |
| MSI MS-7C37                      | 14       | 0.57%   |
| MSI MS-7C56                      | 13       | 0.53%   |
| MSI MS-7B86                      | 13       | 0.53%   |
| Dell OptiPlex 7010               | 12       | 0.49%   |
| HP Compaq Elite 8300 SFF         | 10       | 0.41%   |
| Gigabyte B450M DS3H              | 9        | 0.36%   |
| ASUS TUF Gaming X570-PLUS        | 9        | 0.36%   |
| ASRock Q1900M                    | 8        | 0.32%   |
| Supermicro H8DM8-2               | 7        | 0.28%   |
| MSI MS-7B79                      | 7        | 0.28%   |
| HP Compaq 8200 Elite SFF PC      | 7        | 0.28%   |
| Dell OptiPlex 3020               | 7        | 0.28%   |
| ASUS TUF Gaming B550-PLUS        | 7        | 0.28%   |
| ASUS ROG STRIX B550-F GAMING     | 7        | 0.28%   |
| ASUS P5KPL-SE                    | 7        | 0.28%   |
| ASRock N68C-S UCC                | 7        | 0.28%   |
| MSI MS-7C52                      | 6        | 0.24%   |
| MSI MS-7C02                      | 6        | 0.24%   |
| MSI MS-7758                      | 6        | 0.24%   |
| HP ProDesk 600 G1 SFF            | 6        | 0.24%   |
| Gigabyte X570 AORUS ELITE        | 6        | 0.24%   |
| Dell OptiPlex 390                | 6        | 0.24%   |
| ASUS P5KPL-AM SE                 | 6        | 0.24%   |
| ASUS P5K                         | 6        | 0.24%   |
| ASRock B450M-HDV R4.0            | 6        | 0.24%   |
| MSI MS-7C91                      | 5        | 0.2%    |
| MSI MS-7B89                      | 5        | 0.2%    |
| MSI MS-7817                      | 5        | 0.2%    |
| HP Compaq 6000 Pro MT PC         | 5        | 0.2%    |
| Gigabyte X470 AORUS ULTRA GAMING | 5        | 0.2%    |
| Dell OptiPlex 990                | 5        | 0.2%    |
| Dell OptiPlex 780                | 5        | 0.2%    |
| Dell OptiPlex 760                | 5        | 0.2%    |
| Dell OptiPlex 3010               | 5        | 0.2%    |
| ASUS ROG STRIX B450-F GAMING     | 5        | 0.2%    |
| ASUS PRIME B450-PLUS             | 5        | 0.2%    |
| ASUS P6T DELUXE V2               | 5        | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS PRIME          | 111      | 4.5%    |
| HP Compaq           | 84       | 3.4%    |
| Dell OptiPlex       | 71       | 2.88%   |
| ASUS All            | 70       | 2.84%   |
| Acer Aspire         | 54       | 2.19%   |
| ASUS TUF            | 52       | 2.11%   |
| ASUS ROG            | 50       | 2.03%   |
| Lenovo ThinkCentre  | 45       | 1.82%   |
| Unknown             | 35       | 1.42%   |
| Acer Veriton        | 33       | 1.34%   |
| Fujitsu ESPRIMO     | 30       | 1.22%   |
| Dell Precision      | 21       | 0.85%   |
| ASUS P8H61-M        | 20       | 0.81%   |
| Packard Bell IMEDIA | 18       | 0.73%   |
| HP Pavilion         | 18       | 0.73%   |
| HP ProDesk          | 17       | 0.69%   |
| Gigabyte X570       | 17       | 0.69%   |
| MSI MS-7C37         | 14       | 0.57%   |
| HP EliteDesk        | 14       | 0.57%   |
| MSI MS-7C56         | 13       | 0.53%   |
| MSI MS-7B86         | 13       | 0.53%   |
| ASUS P5KPL-AM       | 13       | 0.53%   |
| Lenovo IdeaCentre   | 12       | 0.49%   |
| Gigabyte B450       | 12       | 0.49%   |
| ASUS P5K            | 12       | 0.49%   |
| ASUS M5A97          | 12       | 0.49%   |
| Gigabyte B450M      | 11       | 0.45%   |
| ASUS P5Q            | 11       | 0.45%   |
| ASUS M5A78L-M       | 11       | 0.45%   |
| ASUS P8Z77-V        | 10       | 0.41%   |
| ASRock 970          | 10       | 0.41%   |
| Lenovo ThinkStation | 9        | 0.36%   |
| Gigabyte Z390       | 9        | 0.36%   |
| ASUS P8P67          | 9        | 0.36%   |
| ASUS P6T            | 9        | 0.36%   |
| ASRock B450         | 9        | 0.36%   |
| Pegatron Pro        | 8        | 0.32%   |
| Dell Vostro         | 8        | 0.32%   |
| ASUS SABERTOOTH     | 8        | 0.32%   |
| ASUS Rampage        | 8        | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 225      | 9.11%   |
| 2012    | 203      | 8.22%   |
| 2009    | 198      | 8.02%   |
| 2013    | 197      | 7.98%   |
| 2008    | 173      | 7.01%   |
| 2011    | 170      | 6.89%   |
| 2019    | 164      | 6.64%   |
| 2014    | 157      | 6.36%   |
| 2010    | 145      | 5.87%   |
| 2020    | 140      | 5.67%   |
| 2017    | 125      | 5.06%   |
| 2007    | 123      | 4.98%   |
| 2015    | 117      | 4.74%   |
| 2016    | 99       | 4.01%   |
| 2021    | 80       | 3.24%   |
| 2006    | 71       | 2.88%   |
| 2005    | 41       | 1.66%   |
| 2022    | 21       | 0.85%   |
| 2004    | 11       | 0.45%   |
| 2003    | 4        | 0.16%   |
| 2001    | 2        | 0.08%   |
| Unknown | 2        | 0.08%   |
| 2002    | 1        | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 2469     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 2419     | 97.74%  |
| Enabled  | 56       | 2.26%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2469     | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 544      | 21.66%  |
| 16.01-24.0      | 530      | 21.11%  |
| 3.01-4.0        | 505      | 20.11%  |
| 4.01-8.0        | 380      | 15.13%  |
| 32.01-64.0      | 247      | 9.84%   |
| 1.01-2.0        | 133      | 5.3%    |
| 64.01-256.0     | 66       | 2.63%   |
| 24.01-32.0      | 40       | 1.59%   |
| 2.01-3.0        | 39       | 1.55%   |
| 0.51-1.0        | 23       | 0.92%   |
| More than 256.0 | 2        | 0.08%   |
| 0.01-0.5        | 2        | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 1139     | 41.48%  |
| 2.01-3.0   | 629      | 22.91%  |
| 3.01-4.0   | 294      | 10.71%  |
| 4.01-8.0   | 288      | 10.49%  |
| 0.51-1.0   | 266      | 9.69%   |
| 8.01-16.0  | 76       | 2.77%   |
| 0.01-0.5   | 34       | 1.24%   |
| 16.01-24.0 | 13       | 0.47%   |
| 24.01-32.0 | 5        | 0.18%   |
| 32.01-64.0 | 1        | 0.04%   |
| Unknown    | 1        | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 975      | 37.85%  |
| 2       | 782      | 30.36%  |
| 3       | 409      | 15.88%  |
| 4       | 203      | 7.88%   |
| 5       | 99       | 3.84%   |
| 6       | 40       | 1.55%   |
| 0       | 29       | 1.13%   |
| 7       | 16       | 0.62%   |
| 8       | 11       | 0.43%   |
| 10      | 4        | 0.16%   |
| 12      | 3        | 0.12%   |
| 9       | 3        | 0.12%   |
| 13      | 1        | 0.04%   |
| Unknown | 1        | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1523     | 60.87%  |
| No        | 979      | 39.13%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2452     | 99.31%  |
| No        | 17       | 0.69%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1438     | 57.52%  |
| Yes       | 1062     | 42.48%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1855     | 73.7%   |
| Yes       | 662      | 26.3%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Italy   | 2469     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Milan                 | 293      | 10.45%  |
| Rome                  | 282      | 10.06%  |
| Turin                 | 89       | 3.17%   |
| Bologna               | 75       | 2.67%   |
| Naples                | 60       | 2.14%   |
| Florence              | 52       | 1.85%   |
| Genoa                 | 49       | 1.75%   |
| Palermo               | 32       | 1.14%   |
| Padova                | 29       | 1.03%   |
| Rho                   | 27       | 0.96%   |
| Verona                | 25       | 0.89%   |
| Venice                | 20       | 0.71%   |
| Catania               | 20       | 0.71%   |
| Trieste               | 18       | 0.64%   |
| Brescia               | 18       | 0.64%   |
| Reggio Emilia         | 16       | 0.57%   |
| Parma                 | 16       | 0.57%   |
| Milano                | 16       | 0.57%   |
| Capriate San Gervasio | 16       | 0.57%   |
| Bari                  | 16       | 0.57%   |
| Pescara               | 15       | 0.53%   |
| Cagliari              | 15       | 0.53%   |
| Bergamo               | 14       | 0.5%    |
| Sesto San Giovanni    | 13       | 0.46%   |
| Pisa                  | 12       | 0.43%   |
| Monza                 | 12       | 0.43%   |
| Trento                | 11       | 0.39%   |
| Taranto               | 11       | 0.39%   |
| Modena                | 11       | 0.39%   |
| Perugia               | 10       | 0.36%   |
| Lucca                 | 10       | 0.36%   |
| Como                  | 10       | 0.36%   |
| Treviso               | 9        | 0.32%   |
| Casalecchio di Reno   | 9        | 0.32%   |
| Bolzano               | 9        | 0.32%   |
| Vicenza               | 8        | 0.29%   |
| Mestre                | 8        | 0.29%   |
| Udine                 | 7        | 0.25%   |
| Reggio Calabria       | 7        | 0.25%   |
| Capannori             | 7        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 910      | 1523   | 20.44%  |
| WDC                       | 835      | 1393   | 18.76%  |
| Samsung Electronics       | 650      | 1008   | 14.6%   |
| Kingston                  | 323      | 462    | 7.26%   |
| Crucial                   | 284      | 381    | 6.38%   |
| Toshiba                   | 222      | 353    | 4.99%   |
| Maxtor                    | 176      | 239    | 3.95%   |
| Hitachi                   | 157      | 212    | 3.53%   |
| Sandisk                   | 143      | 213    | 3.21%   |
| Unknown                   | 60       | 84     | 1.35%   |
| Phison                    | 59       | 85     | 1.33%   |
| China                     | 38       | 42     | 0.85%   |
| HGST                      | 32       | 53     | 0.72%   |
| SPCC                      | 29       | 34     | 0.65%   |
| Corsair                   | 29       | 45     | 0.65%   |
| Micron/Crucial Technology | 28       | 37     | 0.63%   |
| Intel                     | 28       | 37     | 0.63%   |
| Intenso                   | 25       | 35     | 0.56%   |
| A-DATA Technology         | 22       | 33     | 0.49%   |
| OCZ                       | 21       | 26     | 0.47%   |
| PNY                       | 18       | 24     | 0.4%    |
| Micron Technology         | 18       | 19     | 0.4%    |
| Transcend                 | 17       | 23     | 0.38%   |
| KingDian                  | 16       | 17     | 0.36%   |
| Phison Electronics        | 15       | 19     | 0.34%   |
| Patriot                   | 14       | 18     | 0.31%   |
| SK hynix                  | 13       | 14     | 0.29%   |
| Silicon Motion            | 13       | 18     | 0.29%   |
| Drevo                     | 11       | 12     | 0.25%   |
| Team                      | 9        | 16     | 0.2%    |
| GOODRAM                   | 9        | 15     | 0.2%    |
| Fujitsu                   | 9        | 10     | 0.2%    |
| XPG                       | 8        | 8      | 0.18%   |
| TCSUNBOW                  | 8        | 9      | 0.18%   |
| JMicron Technology        | 8        | 9      | 0.18%   |
| Lexar                     | 7        | 10     | 0.16%   |
| Dogfish                   | 7        | 10     | 0.16%   |
| ASMT                      | 7        | 7      | 0.16%   |
| LITEONIT                  | 6        | 6      | 0.13%   |
| TO Exter                  | 5        | 5      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 102      | 1.98%   |
| Kingston SA400S37240G 240GB SSD                     | 90       | 1.75%   |
| Samsung SSD 860 EVO 500GB                           | 75       | 1.46%   |
| Samsung SSD 850 EVO 250GB                           | 70       | 1.36%   |
| Seagate ST1000DM010-2EP102 1TB                      | 67       | 1.3%    |
| Crucial CT500MX500SSD1 500GB                        | 62       | 1.2%    |
| Toshiba DT01ACA100 1TB                              | 57       | 1.11%   |
| Kingston SA400S37480G 480GB SSD                     | 52       | 1.01%   |
| Seagate ST2000DM008-2FR102 2TB                      | 50       | 0.97%   |
| Seagate ST3500418AS 500GB                           | 46       | 0.89%   |
| Samsung SSD 860 EVO 250GB                           | 42       | 0.82%   |
| Samsung SSD 850 EVO 500GB                           | 42       | 0.82%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 37       | 0.72%   |
| Seagate ST1000DM003-1CH162 1TB                      | 36       | 0.7%    |
| Crucial CT240BX500SSD1 240GB                        | 36       | 0.7%    |
| Seagate ST31000528AS 1TB                            | 35       | 0.68%   |
| Kingston SA400S37120G 120GB SSD                     | 34       | 0.66%   |
| Crucial CT1000MX500SSD1 1TB                         | 33       | 0.64%   |
| Seagate ST1000DM003-1ER162 1TB                      | 32       | 0.62%   |
| Seagate ST2000DM001-1ER164 2TB                      | 31       | 0.6%    |
| Kingston SV300S37A120G 120GB SSD                    | 29       | 0.56%   |
| Toshiba DT01ACA050 500GB                            | 27       | 0.52%   |
| Seagate ST3500413AS 500GB                           | 26       | 0.5%    |
| Samsung NVMe SSD Drive 500GB                        | 26       | 0.5%    |
| Seagate ST1000DM003-1SB10C 1TB                      | 25       | 0.49%   |
| Phison Sabrent 512GB                                | 25       | 0.49%   |
| Crucial CT480BX500SSD1 480GB                        | 24       | 0.47%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 23       | 0.45%   |
| Seagate M3 Portable 2TB                             | 23       | 0.45%   |
| Samsung SSD 840 EVO 250GB                           | 23       | 0.45%   |
| Maxtor STM3250310AS 250GB                           | 22       | 0.43%   |
| Toshiba DT01ACA200 2TB                              | 21       | 0.41%   |
| Seagate ST2000DM006-2DM164 2TB                      | 21       | 0.41%   |
| Seagate ST1000DM003-9YN162 1TB                      | 21       | 0.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 21       | 0.41%   |
| Seagate Expansion+ 2TB                              | 20       | 0.39%   |
| WDC WD30EFRX-68EUZN0 3TB                            | 19       | 0.37%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 19       | 0.37%   |
| Unknown SD/MMC/MS PRO 64GB                          | 19       | 0.37%   |
| SanDisk SSD PLUS 240GB                              | 19       | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 892      | 1479   | 37.37%  |
| WDC                 | 769      | 1265   | 32.22%  |
| Toshiba             | 195      | 313    | 8.17%   |
| Maxtor              | 176      | 239    | 7.37%   |
| Hitachi             | 157      | 212    | 6.58%   |
| Samsung Electronics | 95       | 119    | 3.98%   |
| HGST                | 32       | 53     | 1.34%   |
| Unknown             | 26       | 34     | 1.09%   |
| Fujitsu             | 9        | 10     | 0.38%   |
| ASMT                | 6        | 6      | 0.25%   |
| SABRENT             | 5        | 5      | 0.21%   |
| USB3.0              | 3        | 4      | 0.13%   |
| Apple               | 3        | 3      | 0.13%   |
| WD MediaMax         | 2        | 2      | 0.08%   |
| IBM/Hitachi         | 2        | 2      | 0.08%   |
| HGST HTS            | 2        | 2      | 0.08%   |
| Hewlett-Packard     | 2        | 3      | 0.08%   |
| USB 3.0             | 1        | 2      | 0.04%   |
| USB                 | 1        | 1      | 0.04%   |
| Promise             | 1        | 1      | 0.04%   |
| PI-041              | 1        | 1      | 0.04%   |
| MARVELL             | 1        | 2      | 0.04%   |
| Intenso             | 1        | 3      | 0.04%   |
| HPE                 | 1        | 1      | 0.04%   |
| FC-1307             | 1        | 2      | 0.04%   |
| Config              | 1        | 1      | 0.04%   |
| China               | 1        | 1      | 0.04%   |
| ASMT109x            | 1        | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 425      | 622    | 27.47%  |
| Kingston            | 302      | 431    | 19.52%  |
| Crucial             | 247      | 333    | 15.97%  |
| SanDisk             | 116      | 178    | 7.5%    |
| WDC                 | 63       | 88     | 4.07%   |
| China               | 37       | 41     | 2.39%   |
| Toshiba             | 26       | 32     | 1.68%   |
| SPCC                | 25       | 30     | 1.62%   |
| Corsair             | 23       | 37     | 1.49%   |
| Intenso             | 22       | 29     | 1.42%   |
| OCZ                 | 20       | 25     | 1.29%   |
| PNY                 | 18       | 24     | 1.16%   |
| A-DATA Technology   | 18       | 29     | 1.16%   |
| KingDian            | 16       | 17     | 1.03%   |
| Transcend           | 15       | 21     | 0.97%   |
| Patriot             | 14       | 18     | 0.9%    |
| Intel               | 12       | 18     | 0.78%   |
| GOODRAM             | 9        | 15     | 0.58%   |
| Team                | 8        | 15     | 0.52%   |
| TCSUNBOW            | 8        | 9      | 0.52%   |
| Micron Technology   | 8        | 9      | 0.52%   |
| Drevo               | 7        | 7      | 0.45%   |
| Dogfish             | 7        | 10     | 0.45%   |
| Unknown             | 6        | 7      | 0.39%   |
| LITEONIT            | 6        | 6      | 0.39%   |
| TO Exter            | 5        | 5      | 0.32%   |
| Verbatim            | 4        | 4      | 0.26%   |
| Plextor             | 4        | 8      | 0.26%   |
| LITEON              | 4        | 5      | 0.26%   |
| Lexar               | 4        | 6      | 0.26%   |
| BAITITON            | 4        | 4      | 0.26%   |
| Apacer              | 4        | 4      | 0.26%   |
| SK hynix            | 3        | 3      | 0.19%   |
| Netac               | 3        | 3      | 0.19%   |
| KIOXIA-EXCERIA      | 3        | 3      | 0.19%   |
| KingSpec            | 3        | 4      | 0.19%   |
| JMicron Technology  | 3        | 4      | 0.19%   |
| Gigabyte Technology | 3        | 10     | 0.19%   |
| S3+                 | 2        | 4      | 0.13%   |
| Inateck             | 2        | 2      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1829     | 3767   | 49.62%  |
| SSD     | 1291     | 2162   | 35.02%  |
| NVMe    | 460      | 696    | 12.48%  |
| Unknown | 81       | 110    | 2.2%    |
| MMC     | 25       | 30     | 0.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 2302     | 5819   | 78.17%  |
| NVMe | 457      | 689    | 15.52%  |
| SAS  | 161      | 227    | 5.47%   |
| MMC  | 25       | 30     | 0.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1887     | 3561   | 57.53%  |
| 0.51-1.0   | 840      | 1373   | 25.61%  |
| 1.01-2.0   | 309      | 547    | 9.42%   |
| 2.01-3.0   | 97       | 164    | 2.96%   |
| 3.01-4.0   | 90       | 163    | 2.74%   |
| 4.01-10.0  | 52       | 112    | 1.59%   |
| 10.01-20.0 | 5        | 9      | 0.15%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 624      | 23.38%  |
| 251-500        | 444      | 16.64%  |
| 501-1000       | 353      | 13.23%  |
| 1001-2000      | 295      | 11.05%  |
| 1-20           | 243      | 9.1%    |
| More than 3000 | 195      | 7.31%   |
| 51-100         | 187      | 7.01%   |
| 2001-3000      | 137      | 5.13%   |
| 21-50          | 98       | 3.67%   |
| Unknown        | 93       | 3.48%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1020     | 37.17%  |
| 21-50          | 375      | 13.67%  |
| 101-250        | 283      | 10.31%  |
| 51-100         | 254      | 9.26%   |
| 501-1000       | 224      | 8.16%   |
| 251-500        | 217      | 7.91%   |
| 1001-2000      | 142      | 5.17%   |
| Unknown        | 93       | 3.39%   |
| More than 3000 | 82       | 2.99%   |
| 2001-3000      | 54       | 1.97%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 16       | 18     | 4.65%   |
| Seagate ST3500418AS 500GB             | 9        | 13     | 2.62%   |
| Maxtor STM3250310AS 250GB             | 7        | 7      | 2.03%   |
| WDC WD40EFRX-68N32N0 4TB              | 4        | 5      | 1.16%   |
| Unknown MM0500EANCR 500GB             | 4        | 9      | 1.16%   |
| Seagate ST31500341AS 1TB              | 4        | 4      | 1.16%   |
| Seagate ST31000528AS 1TB              | 4        | 7      | 1.16%   |
| Maxtor STM3320820AS 320GB             | 4        | 4      | 1.16%   |
| WDC WD20EFRX-68EUZN0 2TB              | 3        | 4      | 0.87%   |
| Toshiba DT01ACA100 1TB                | 3        | 3      | 0.87%   |
| Seagate ST3500413AS 500GB             | 3        | 5      | 0.87%   |
| Seagate ST3500320AS 500GB             | 3        | 3      | 0.87%   |
| Seagate ST2000DM001-1ER164 2TB        | 3        | 7      | 0.87%   |
| SanDisk SSD PLUS 480GB                | 3        | 4      | 0.87%   |
| Samsung Electronics HD103UJ 1TB       | 3        | 3      | 0.87%   |
| Maxtor 6Y080L0 82GB                   | 3        | 3      | 0.87%   |
| Hitachi HDS721010CLA332 1TB           | 3        | 3      | 0.87%   |
| WDC WD5000LPCX-24C6HT0 500GB          | 2        | 2      | 0.58%   |
| WDC WD5000AADS-00S9B0 500GB           | 2        | 2      | 0.58%   |
| WDC WD40PURZ-85TTDY0 4TB              | 2        | 2      | 0.58%   |
| WDC WD30EFRX-68EUZN0 3TB              | 2        | 2      | 0.58%   |
| WDC WD10EZEX-60WN4A0 1TB              | 2        | 3      | 0.58%   |
| WDC WD10EADS-00M2B0 1TB               | 2        | 2      | 0.58%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 2        | 2      | 0.58%   |
| Toshiba DT01ACA050 500GB              | 2        | 2      | 0.58%   |
| Seagate ST9500530NS 500GB             | 2        | 3      | 0.58%   |
| Seagate ST9500325AS 500GB             | 2        | 2      | 0.58%   |
| Seagate ST3500620AS 500GB             | 2        | 2      | 0.58%   |
| Seagate ST3320620AS 320GB             | 2        | 3      | 0.58%   |
| Seagate ST3320613AS 320GB             | 2        | 2      | 0.58%   |
| Seagate ST3250820AS 250GB             | 2        | 3      | 0.58%   |
| Seagate ST3250318AS 250GB             | 2        | 2      | 0.58%   |
| Seagate ST3250310AS 250GB             | 2        | 2      | 0.58%   |
| Seagate ST2000DM006-2DM164 2TB        | 2        | 2      | 0.58%   |
| Seagate ST2000DM001-1CH164 2TB        | 2        | 2      | 0.58%   |
| Seagate ST2000DL003-9VT166 2TB        | 2        | 3      | 0.58%   |
| Seagate ST1000DM003-9YN162 1TB        | 2        | 2      | 0.58%   |
| Seagate ST1000DM003-1ER162 1TB        | 2        | 2      | 0.58%   |
| Seagate ST1000DM003-1CH162 1TB        | 2        | 2      | 0.58%   |
| Samsung Electronics SSD 860 EVO 500GB | 2        | 3      | 0.58%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 101      | 139    | 30.79%  |
| WDC                 | 82       | 104    | 25%     |
| Maxtor              | 34       | 38     | 10.37%  |
| Hitachi             | 27       | 30     | 8.23%   |
| Samsung Electronics | 22       | 25     | 6.71%   |
| Toshiba             | 13       | 13     | 3.96%   |
| Kingston            | 11       | 11     | 3.35%   |
| Crucial             | 6        | 6      | 1.83%   |
| Unknown             | 4        | 9      | 1.22%   |
| SanDisk             | 4        | 5      | 1.22%   |
| OCZ                 | 3        | 3      | 0.91%   |
| HGST                | 3        | 4      | 0.91%   |
| Intenso             | 2        | 3      | 0.61%   |
| Corsair             | 2        | 3      | 0.61%   |
| ASMT                | 2        | 2      | 0.61%   |
| WD MediaMax         | 1        | 1      | 0.3%    |
| USB3.0              | 1        | 1      | 0.3%    |
| TCSUNBOW            | 1        | 1      | 0.3%    |
| SK hynix            | 1        | 1      | 0.3%    |
| Micron Technology   | 1        | 1      | 0.3%    |
| LITEONIT            | 1        | 1      | 0.3%    |
| GSemi               | 1        | 1      | 0.3%    |
| Fujitsu             | 1        | 1      | 0.3%    |
| Drevo               | 1        | 1      | 0.3%    |
| CT1000P1            | 1        | 2      | 0.3%    |
| BAITITON            | 1        | 1      | 0.3%    |
| Apacer              | 1        | 1      | 0.3%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 101      | 139    | 35.69%  |
| WDC                 | 81       | 100    | 28.62%  |
| Maxtor              | 34       | 38     | 12.01%  |
| Hitachi             | 27       | 30     | 9.54%   |
| Samsung Electronics | 15       | 16     | 5.3%    |
| Toshiba             | 13       | 13     | 4.59%   |
| Unknown             | 4        | 9      | 1.41%   |
| HGST                | 3        | 4      | 1.06%   |
| ASMT                | 2        | 2      | 0.71%   |
| WD MediaMax         | 1        | 1      | 0.35%   |
| USB3.0              | 1        | 1      | 0.35%   |
| Fujitsu             | 1        | 1      | 0.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 256      | 354    | 84.77%  |
| SSD  | 41       | 48     | 13.58%  |
| NVMe | 5        | 6      | 1.66%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB | 2        | 3      | 33.33%  |
| Seagate STM3250318AS 250GB      | 1        | 1      | 16.67%  |
| Seagate ST9500420AS 500GB       | 1        | 1      | 16.67%  |
| Hitachi HTS725050A7E630 500GB   | 1        | 1      | 16.67%  |
| Hitachi HTS543216L9A300 160GB   | 1        | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 4        | 5      | 66.67%  |
| Hitachi | 2        | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 1527     | 3981   | 54.79%  |
| Works    | 964      | 2369   | 34.59%  |
| Malfunc  | 290      | 408    | 10.41%  |
| Failed   | 6        | 7      | 0.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1623     | 48%     |
| AMD                              | 658      | 19.46%  |
| Samsung Electronics              | 198      | 5.86%   |
| JMicron Technology               | 126      | 3.73%   |
| ASMedia Technology               | 124      | 3.67%   |
| Nvidia                           | 120      | 3.55%   |
| Marvell Technology Group         | 118      | 3.49%   |
| Phison Electronics               | 82       | 2.43%   |
| Micron/Crucial Technology        | 67       | 1.98%   |
| SanDisk                          | 53       | 1.57%   |
| VIA Technologies                 | 48       | 1.42%   |
| Kingston Technology Company      | 29       | 0.86%   |
| Silicon Motion                   | 19       | 0.56%   |
| Adaptec                          | 15       | 0.44%   |
| Micron Technology                | 12       | 0.35%   |
| ADATA Technology                 | 12       | 0.35%   |
| Silicon Image                    | 9        | 0.27%   |
| Toshiba America Info Systems     | 8        | 0.24%   |
| SK hynix                         | 8        | 0.24%   |
| Silicon Integrated Systems [SiS] | 8        | 0.24%   |
| Broadcom / LSI                   | 7        | 0.21%   |
| LSI Logic / Symbios Logic        | 6        | 0.18%   |
| Realtek Semiconductor            | 5        | 0.15%   |
| Promise Technology               | 3        | 0.09%   |
| KIOXIA                           | 3        | 0.09%   |
| Integrated Technology Express    | 3        | 0.09%   |
| Broadcom                         | 3        | 0.09%   |
| ULi Electronics                  | 2        | 0.06%   |
| Seagate Technology               | 2        | 0.06%   |
| MAXIO Technology (Hangzhou)      | 2        | 0.06%   |
| INNOGRIT                         | 2        | 0.06%   |
| HighPoint Technologies           | 2        | 0.06%   |
| Shenzhen Longsys Electronics     | 1        | 0.03%   |
| OCZ Technology Group             | 1        | 0.03%   |
| Lite-On IT Corp. / Plextor       | 1        | 0.03%   |
| Initio                           | 1        | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 358      | 8.09%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 169      | 3.82%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 146      | 3.3%    |
| AMD 400 Series Chipset SATA Controller                                                  | 143      | 3.23%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 125      | 2.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 125      | 2.83%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 124      | 2.8%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 118      | 2.67%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 116      | 2.62%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 112      | 2.53%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 105      | 2.37%   |
| Intel SATA Controller [RAID mode]                                                       | 103      | 2.33%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 93       | 2.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 89       | 2.01%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 73       | 1.65%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 70       | 1.58%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 69       | 1.56%   |
| AMD 500 Series Chipset SATA Controller                                                  | 60       | 1.36%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 58       | 1.31%   |
| Phison E12 NVMe Controller                                                              | 57       | 1.29%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 52       | 1.18%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 52       | 1.18%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 50       | 1.13%   |
| Nvidia MCP61 SATA Controller                                                            | 48       | 1.09%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 47       | 1.06%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 43       | 0.97%   |
| Nvidia MCP61 IDE                                                                        | 41       | 0.93%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 37       | 0.84%   |
| Samsung NVMe SSD Controller 980                                                         | 36       | 0.81%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 36       | 0.81%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 36       | 0.81%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 33       | 0.75%   |
| JMicron JMB368 IDE controller                                                           | 33       | 0.75%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 33       | 0.75%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 33       | 0.75%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 33       | 0.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 32       | 0.72%   |
| AMD FCH SATA Controller D                                                               | 32       | 0.72%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 30       | 0.68%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 29       | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1754     | 52.86%  |
| IDE  | 874      | 26.34%  |
| NVMe | 463      | 13.95%  |
| RAID | 209      | 6.3%    |
| SAS  | 9        | 0.27%   |
| SCSI | 9        | 0.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 1709     | 69.22%  |
| AMD          | 758      | 30.7%   |
| CentaurHauls | 2        | 0.08%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 43       | 1.73%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 39       | 1.57%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 35       | 1.41%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 35       | 1.41%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 29       | 1.17%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 28       | 1.13%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 26       | 1.05%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 24       | 0.97%   |
| Intel Pentium 4 CPU 3.00GHz                 | 22       | 0.89%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 22       | 0.89%   |
| AMD FX-8350 Eight-Core Processor            | 21       | 0.85%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 20       | 0.81%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 20       | 0.81%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 20       | 0.81%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 19       | 0.77%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 18       | 0.73%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 17       | 0.69%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 17       | 0.69%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 17       | 0.69%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 17       | 0.69%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 17       | 0.69%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 17       | 0.69%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 17       | 0.69%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 17       | 0.69%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 16       | 0.65%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 16       | 0.65%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 15       | 0.6%    |
| Intel Core i7-4770 CPU @ 3.40GHz            | 15       | 0.6%    |
| Intel Core i5-9400F CPU @ 2.90GHz           | 15       | 0.6%    |
| Intel Core i5-6600K CPU @ 3.50GHz           | 15       | 0.6%    |
| Intel Core i5 CPU 650 @ 3.20GHz             | 15       | 0.6%    |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 15       | 0.6%    |
| AMD Ryzen 5 5600G with Radeon Graphics      | 15       | 0.6%    |
| AMD Ryzen 5 2600 Six-Core Processor         | 15       | 0.6%    |
| AMD Ryzen 5 1600 Six-Core Processor         | 15       | 0.6%    |
| Intel Core i7 CPU 920 @ 2.67GHz             | 14       | 0.56%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 14       | 0.56%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 14       | 0.56%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 13       | 0.52%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 13       | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 446      | 17.99%  |
| Intel Core i7           | 324      | 13.07%  |
| Intel Core i3           | 176      | 7.1%    |
| AMD Ryzen 5             | 162      | 6.53%   |
| AMD Ryzen 7             | 119      | 4.8%    |
| Intel Core 2 Duo        | 103      | 4.15%   |
| Intel Core 2 Quad       | 102      | 4.11%   |
| Intel Celeron           | 92       | 3.71%   |
| Intel Xeon              | 81       | 3.27%   |
| Intel Pentium Dual-Core | 75       | 3.03%   |
| AMD FX                  | 69       | 2.78%   |
| Intel Pentium           | 67       | 2.7%    |
| Intel Pentium 4         | 60       | 2.42%   |
| AMD Athlon 64 X2        | 47       | 1.9%    |
| AMD Ryzen 9             | 45       | 1.82%   |
| Intel Core 2            | 39       | 1.57%   |
| Other                   | 36       | 1.45%   |
| AMD Ryzen 3             | 35       | 1.41%   |
| Intel Pentium Dual      | 29       | 1.17%   |
| Intel Atom              | 28       | 1.13%   |
| AMD Phenom II X4        | 28       | 1.13%   |
| AMD A8                  | 27       | 1.09%   |
| Intel Core i9           | 25       | 1.01%   |
| Intel Pentium D         | 24       | 0.97%   |
| AMD Phenom II X6        | 20       | 0.81%   |
| AMD Sempron             | 19       | 0.77%   |
| AMD Athlon II X2        | 18       | 0.73%   |
| AMD A10                 | 17       | 0.69%   |
| AMD Phenom              | 16       | 0.65%   |
| AMD Athlon II X4        | 15       | 0.61%   |
| AMD A6                  | 14       | 0.56%   |
| AMD A4                  | 14       | 0.56%   |
| AMD Athlon 64           | 12       | 0.48%   |
| AMD Six-Core Opteron    | 11       | 0.44%   |
| AMD Athlon II X3        | 11       | 0.44%   |
| AMD Athlon              | 10       | 0.4%    |
| AMD Athlon X4           | 7        | 0.28%   |
| AMD Ryzen Threadripper  | 6        | 0.24%   |
| AMD Ryzen 5 PRO         | 4        | 0.16%   |
| AMD Quad-Core Opteron   | 4        | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 1025     | 41.38%  |
| 2       | 711      | 28.7%   |
| 6       | 289      | 11.67%  |
| 8       | 198      | 7.99%   |
| 1       | 126      | 5.09%   |
| 12      | 47       | 1.9%    |
| 3       | 35       | 1.41%   |
| 16      | 21       | 0.85%   |
| 10      | 16       | 0.65%   |
| 24      | 4        | 0.16%   |
| 64      | 1        | 0.04%   |
| 28      | 1        | 0.04%   |
| 14      | 1        | 0.04%   |
| 5       | 1        | 0.04%   |
| Unknown | 1        | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 2432     | 98.5%   |
| 2      | 37       | 1.5%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 1332     | 53.86%  |
| 2       | 1140     | 46.1%   |
| Unknown | 1        | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 2429     | 98.14%  |
| Unknown        | 25       | 1.01%   |
| 32-bit         | 21       | 0.85%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 536      | 20.83%  |
| 0x306c3    | 191      | 7.42%   |
| 0x206a7    | 146      | 5.67%   |
| 0x1067a    | 142      | 5.52%   |
| 0x306a9    | 130      | 5.05%   |
| 0x506e3    | 92       | 3.58%   |
| 0x08701021 | 84       | 3.26%   |
| 0x906e9    | 66       | 2.57%   |
| 0x6fb      | 56       | 2.18%   |
| 0x906ea    | 51       | 1.98%   |
| 0x0800820d | 40       | 1.55%   |
| 0x010000c8 | 37       | 1.44%   |
| 0x6fd      | 34       | 1.32%   |
| 0x06000852 | 34       | 1.32%   |
| 0x106e5    | 29       | 1.13%   |
| 0x10676    | 29       | 1.13%   |
| 0x906ed    | 27       | 1.05%   |
| 0x6f6      | 27       | 1.05%   |
| 0x08701013 | 26       | 1.01%   |
| 0x0a201016 | 25       | 0.97%   |
| 0x06001119 | 25       | 0.97%   |
| 0x08108109 | 24       | 0.93%   |
| 0x20655    | 22       | 0.86%   |
| 0x106a5    | 22       | 0.86%   |
| 0xa0655    | 21       | 0.82%   |
| 0xa0653    | 21       | 0.82%   |
| 0x0a50000c | 20       | 0.78%   |
| 0x10677    | 19       | 0.74%   |
| 0x20652    | 18       | 0.7%    |
| 0x08001138 | 18       | 0.7%    |
| 0xf43      | 17       | 0.66%   |
| 0xa0671    | 16       | 0.62%   |
| 0x30678    | 16       | 0.62%   |
| 0x03000027 | 16       | 0.62%   |
| 0x306f2    | 15       | 0.58%   |
| 0x010000dc | 15       | 0.58%   |
| 0xf49      | 13       | 0.51%   |
| 0x906eb    | 13       | 0.51%   |
| 0x406c4    | 13       | 0.51%   |
| 0x0810100b | 13       | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 245      | 9.88%   |
| Penryn           | 220      | 8.87%   |
| KabyLake         | 209      | 8.43%   |
| SandyBridge      | 190      | 7.66%   |
| IvyBridge        | 163      | 6.57%   |
| Core             | 149      | 6.01%   |
| K10              | 140      | 5.65%   |
| Zen 2            | 130      | 5.24%   |
| Skylake          | 118      | 4.76%   |
| NetBurst         | 91       | 3.67%   |
| Zen 3            | 89       | 3.59%   |
| Piledriver       | 87       | 3.51%   |
| Zen+             | 81       | 3.27%   |
| Zen              | 77       | 3.1%    |
| K8 Hammer        | 73       | 2.94%   |
| Nehalem          | 68       | 2.74%   |
| CometLake        | 62       | 2.5%    |
| Westmere         | 60       | 2.42%   |
| Silvermont       | 49       | 1.98%   |
| K10 Llano        | 20       | 0.81%   |
| Steamroller      | 19       | 0.77%   |
| Goldmont plus    | 18       | 0.73%   |
| Goldmont         | 18       | 0.73%   |
| Excavator        | 15       | 0.6%    |
| Alderlake Hybrid | 15       | 0.6%    |
| Bonnell          | 14       | 0.56%   |
| Icelake          | 12       | 0.48%   |
| Unknown          | 12       | 0.48%   |
| Bulldozer        | 11       | 0.44%   |
| Jaguar           | 8        | 0.32%   |
| Puma             | 6        | 0.24%   |
| Bobcat           | 5        | 0.2%    |
| Tremont          | 3        | 0.12%   |
| Broadwell        | 2        | 0.08%   |
| K6               | 1        | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 1076     | 41.77%  |
| AMD                                          | 762      | 29.58%  |
| Intel                                        | 707      | 27.45%  |
| VIA Technologies                             | 11       | 0.43%   |
| Matrox Electronics Systems                   | 7        | 0.27%   |
| Silicon Integrated Systems [SiS]             | 5        | 0.19%   |
| ASPEED Technology                            | 4        | 0.16%   |
| XGI Technology (eXtreme Graphics Innovation) | 3        | 0.12%   |
| ATI Technologies                             | 1        | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 95       | 3.58%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 90       | 3.39%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 84       | 3.16%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 70       | 2.64%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 67       | 2.52%   |
| Nvidia GT218 [GeForce 210]                                                               | 60       | 2.26%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 56       | 2.11%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 54       | 2.03%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 37       | 1.39%   |
| Intel HD Graphics 530                                                                    | 36       | 1.36%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 34       | 1.28%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 34       | 1.28%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 34       | 1.28%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 31       | 1.17%   |
| Intel HD Graphics 630                                                                    | 31       | 1.17%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 31       | 1.17%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 30       | 1.13%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 29       | 1.09%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 28       | 1.05%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 27       | 1.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 26       | 0.98%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 26       | 0.98%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 26       | 0.98%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 25       | 0.94%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 23       | 0.87%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 23       | 0.87%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 22       | 0.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 21       | 0.79%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 21       | 0.79%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 21       | 0.79%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 19       | 0.72%   |
| Intel Core Processor Integrated Graphics Controller                                      | 19       | 0.72%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 19       | 0.72%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                                      | 18       | 0.68%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 18       | 0.68%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 17       | 0.64%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 17       | 0.64%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 16       | 0.6%    |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 16       | 0.6%    |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 16       | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 1029     | 41.36%  |
| 1 x AMD              | 682      | 27.41%  |
| 1 x Intel            | 638      | 25.64%  |
| 2 x AMD              | 51       | 2.05%   |
| Intel + Nvidia       | 20       | 0.8%    |
| AMD + Nvidia         | 18       | 0.72%   |
| 1 x VIA              | 11       | 0.44%   |
| Intel + AMD          | 8        | 0.32%   |
| 2 x Nvidia           | 5        | 0.2%    |
| 1 x SiS              | 5        | 0.2%    |
| Other                | 3        | 0.12%   |
| 1 x XGI              | 3        | 0.12%   |
| Nvidia + Matrox      | 3        | 0.12%   |
| 1 x Matrox           | 3        | 0.12%   |
| 1 x ASPEED           | 3        | 0.12%   |
| 3 x AMD              | 1        | 0.04%   |
| 2 x Intel            | 1        | 0.04%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.04%   |
| Nvidia + ASPEED      | 1        | 0.04%   |
| Intel + 2 x AMD      | 1        | 0.04%   |
| AMD + Matrox         | 1        | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1883     | 74.49%  |
| Proprietary | 558      | 22.07%  |
| Unknown     | 87       | 3.44%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 964      | 37.55%  |
| 1.01-2.0   | 392      | 15.27%  |
| 0.01-0.5   | 358      | 13.95%  |
| 0.51-1.0   | 354      | 13.79%  |
| 3.01-4.0   | 189      | 7.36%   |
| 7.01-8.0   | 149      | 5.8%    |
| 5.01-6.0   | 93       | 3.62%   |
| 2.01-3.0   | 35       | 1.36%   |
| 8.01-16.0  | 31       | 1.21%   |
| 4.01-5.0   | 1        | 0.04%   |
| 16.01-24.0 | 1        | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 521      | 20.72%  |
| Hewlett-Packard         | 261      | 10.38%  |
| Philips                 | 236      | 9.38%   |
| Goldstar                | 227      | 9.03%   |
| Ancor Communications    | 209      | 8.31%   |
| Acer                    | 188      | 7.48%   |
| Dell                    | 115      | 4.57%   |
| BenQ                    | 113      | 4.49%   |
| AOC                     | 95       | 3.78%   |
| Lenovo                  | 40       | 1.59%   |
| Unknown                 | 38       | 1.51%   |
| HannStar                | 37       | 1.47%   |
| LG Electronics          | 36       | 1.43%   |
| Sony                    | 33       | 1.31%   |
| ASUSTek Computer        | 29       | 1.15%   |
| Fujitsu Siemens         | 16       | 0.64%   |
| Eizo                    | 15       | 0.6%    |
| MSI                     | 14       | 0.56%   |
| Packard Bell            | 11       | 0.44%   |
| Mi                      | 10       | 0.4%    |
| Belinea                 | 10       | 0.4%    |
| Sharp                   | 9        | 0.36%   |
| NEC Computers           | 9        | 0.36%   |
| ViewSonic               | 8        | 0.32%   |
| HPN                     | 8        | 0.32%   |
| CVT                     | 8        | 0.32%   |
| Vestel Elektronik       | 7        | 0.28%   |
| MiTAC                   | 7        | 0.28%   |
| Panasonic               | 6        | 0.24%   |
| OEM                     | 6        | 0.24%   |
| Lenovo Group Limited    | 6        | 0.24%   |
| Iiyama                  | 6        | 0.24%   |
| HannStar Display        | 6        | 0.24%   |
| ___                     | 5        | 0.2%    |
| QBell                   | 5        | 0.2%    |
| Microstep               | 5        | 0.2%    |
| Hyundai ImageQuest      | 5        | 0.2%    |
| Compaq Computer         | 5        | 0.2%    |
| Chi Mei Optoelectronics | 5        | 0.2%    |
| Vestel                  | 4        | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 22       | 0.82%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 19       | 0.71%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch  | 19       | 0.71%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 12       | 0.45%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 12       | 0.45%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                    | 12       | 0.45%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch      | 11       | 0.41%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 11       | 0.41%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 477x268mm 21.5-inch      | 10       | 0.37%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                        | 10       | 0.37%   |
| Acer X223W ACR000D 1680x1050 474x296mm 22.0-inch                       | 10       | 0.37%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch             | 9        | 0.34%   |
| Hewlett-Packard 24fw HPN3545 1920x1080 527x296mm 23.8-inch             | 9        | 0.34%   |
| AOC 27B2G5 AOC2702 1920x1080 598x336mm 27.0-inch                       | 9        | 0.34%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch   | 8        | 0.3%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 8        | 0.3%    |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch                | 8        | 0.3%    |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 8        | 0.3%    |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                 | 8        | 0.3%    |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch  | 8        | 0.3%    |
| Acer K222HQL ACR03E1 1920x1080 477x268mm 21.5-inch                     | 8        | 0.3%    |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 7        | 0.26%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 7        | 0.26%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                   | 7        | 0.26%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch  | 7        | 0.26%   |
| Samsung Electronics C27F390 SAM0D33 1920x1080 598x336mm 27.0-inch      | 7        | 0.26%   |
| Hewlett-Packard 27f HPN354C 1920x1080 598x336mm 27.0-inch              | 7        | 0.26%   |
| Hewlett-Packard 24w HPN3431 1920x1080 527x296mm 23.8-inch              | 7        | 0.26%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 7        | 0.26%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                | 7        | 0.26%   |
| Dell 2009W DEL4042 1680x1050 433x270mm 20.1-inch                       | 7        | 0.26%   |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch       | 7        | 0.26%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch      | 6        | 0.22%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                     | 6        | 0.22%   |
| Philips 190SW PHL086D 1440x900 408x255mm 18.9-inch                     | 6        | 0.22%   |
| Hewlett-Packard L1706 HWP265C 1280x1024 337x270mm 17.0-inch            | 6        | 0.22%   |
| Hewlett-Packard 27f HPN354B 1920x1080 598x336mm 27.0-inch              | 6        | 0.22%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch            | 6        | 0.22%   |
| Goldstar W1934 GSM4B7A 1440x900 410x256mm 19.0-inch                    | 6        | 0.22%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                       | 6        | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1178     | 47.56%  |
| 1280x1024 (SXGA)   | 281      | 11.34%  |
| 1680x1050 (WSXGA+) | 166      | 6.7%    |
| 3840x2160 (4K)     | 151      | 6.1%    |
| 1440x900 (WXGA+)   | 147      | 5.93%   |
| 2560x1440 (QHD)    | 116      | 4.68%   |
| 1366x768 (WXGA)    | 60       | 2.42%   |
| 1360x768           | 53       | 2.14%   |
| Unknown            | 52       | 2.1%    |
| 1600x900 (HD+)     | 40       | 1.61%   |
| 1920x1200 (WUXGA)  | 38       | 1.53%   |
| 2560x1080          | 34       | 1.37%   |
| 1024x768 (XGA)     | 30       | 1.21%   |
| 3840x1080          | 26       | 1.05%   |
| 3440x1440          | 19       | 0.77%   |
| 1600x1200          | 12       | 0.48%   |
| 1920x540           | 10       | 0.4%    |
| 1280x720 (HD)      | 9        | 0.36%   |
| 1280x768           | 5        | 0.2%    |
| 2560x1600          | 4        | 0.16%   |
| 4480x1440          | 3        | 0.12%   |
| 3840x1600          | 3        | 0.12%   |
| 3200x1080          | 3        | 0.12%   |
| 2288x1287          | 3        | 0.12%   |
| 8960x2160          | 2        | 0.08%   |
| 5760x1080          | 2        | 0.08%   |
| 5120x1440          | 2        | 0.08%   |
| 2640x1024          | 2        | 0.08%   |
| 2304x1024          | 2        | 0.08%   |
| 1818x1022          | 2        | 0.08%   |
| 6784x2160          | 1        | 0.04%   |
| 5760x2160          | 1        | 0.04%   |
| 5520x2160          | 1        | 0.04%   |
| 4480x1080          | 1        | 0.04%   |
| 4093x4093          | 1        | 0.04%   |
| 3968x1152          | 1        | 0.04%   |
| 3840x1920          | 1        | 0.04%   |
| 3840x1200          | 1        | 0.04%   |
| 3520x1080          | 1        | 0.04%   |
| 3360x1080          | 1        | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 335      | 13.25%  |
| 24      | 316      | 12.5%   |
| Unknown | 304      | 12.03%  |
| 27      | 298      | 11.79%  |
| 23      | 238      | 9.41%   |
| 19      | 233      | 9.22%   |
| 17      | 134      | 5.3%    |
| 18      | 113      | 4.47%   |
| 22      | 92       | 3.64%   |
| 20      | 87       | 3.44%   |
| 31      | 55       | 2.18%   |
| 34      | 52       | 2.06%   |
| 15      | 42       | 1.66%   |
| 40      | 34       | 1.34%   |
| 84      | 22       | 0.87%   |
| 72      | 21       | 0.83%   |
| 54      | 19       | 0.75%   |
| 32      | 15       | 0.59%   |
| 25      | 14       | 0.55%   |
| 48      | 9        | 0.36%   |
| 52      | 8        | 0.32%   |
| 28      | 8        | 0.32%   |
| 47      | 7        | 0.28%   |
| 42      | 7        | 0.28%   |
| 36      | 6        | 0.24%   |
| 37      | 5        | 0.2%    |
| 39      | 4        | 0.16%   |
| 33      | 4        | 0.16%   |
| 29      | 4        | 0.16%   |
| 26      | 4        | 0.16%   |
| 12      | 4        | 0.16%   |
| 142     | 3        | 0.12%   |
| 75      | 3        | 0.12%   |
| 60      | 3        | 0.12%   |
| 50      | 3        | 0.12%   |
| 46      | 3        | 0.12%   |
| 43      | 3        | 0.12%   |
| 14      | 3        | 0.12%   |
| 65      | 2        | 0.08%   |
| 59      | 2        | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 800      | 32.32%  |
| 401-500        | 714      | 28.85%  |
| Unknown        | 304      | 12.28%  |
| 301-350        | 172      | 6.95%   |
| 351-400        | 147      | 5.94%   |
| 601-700        | 92       | 3.72%   |
| 701-800        | 76       | 3.07%   |
| 1001-1500      | 58       | 2.34%   |
| 1501-2000      | 47       | 1.9%    |
| 801-900        | 45       | 1.82%   |
| 901-1000       | 10       | 0.4%    |
| 201-300        | 6        | 0.24%   |
| More than 2000 | 3        | 0.12%   |
| 101-200        | 1        | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1396     | 58.05%  |
| 16/10   | 343      | 14.26%  |
| 5/4     | 265      | 11.02%  |
| Unknown | 262      | 10.89%  |
| 4/3     | 59       | 2.45%   |
| 21/9    | 52       | 2.16%   |
| 6/5     | 9        | 0.37%   |
| 3/2     | 9        | 0.37%   |
| 32/9    | 6        | 0.25%   |
| 1.00    | 3        | 0.12%   |
| 2.65    | 1        | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 784      | 31.6%   |
| 151-200        | 452      | 18.22%  |
| Unknown        | 304      | 12.25%  |
| 301-350        | 302      | 12.17%  |
| 141-150        | 193      | 7.78%   |
| 351-500        | 127      | 5.12%   |
| 251-300        | 95       | 3.83%   |
| More than 1000 | 93       | 3.75%   |
| 501-1000       | 79       | 3.18%   |
| 101-110        | 40       | 1.61%   |
| 71-80          | 4        | 0.16%   |
| 131-140        | 3        | 0.12%   |
| 91-100         | 2        | 0.08%   |
| 81-90          | 1        | 0.04%   |
| 1-40           | 1        | 0.04%   |
| 111-120        | 1        | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 1509     | 62.54%  |
| 101-120       | 435      | 18.03%  |
| Unknown       | 304      | 12.6%   |
| 1-50          | 89       | 3.69%   |
| 121-160       | 56       | 2.32%   |
| 161-240       | 19       | 0.79%   |
| More than 240 | 1        | 0.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2099     | 83.73%  |
| 2     | 281      | 11.21%  |
| 0     | 100      | 3.99%   |
| 3     | 27       | 1.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 1491     | 42.59%  |
| Intel                            | 891      | 25.45%  |
| Qualcomm Atheros                 | 236      | 6.74%   |
| Broadcom                         | 105      | 3%      |
| Nvidia                           | 97       | 2.77%   |
| TP-Link                          | 86       | 2.46%   |
| Ralink Technology                | 79       | 2.26%   |
| Marvell Technology Group         | 62       | 1.77%   |
| Ralink                           | 40       | 1.14%   |
| Qualcomm Atheros Communications  | 37       | 1.06%   |
| Broadcom Limited                 | 34       | 0.97%   |
| D-Link System                    | 33       | 0.94%   |
| VIA Technologies                 | 27       | 0.77%   |
| D-Link                           | 27       | 0.77%   |
| Huawei Technologies              | 25       | 0.71%   |
| Sitecom Europe                   | 22       | 0.63%   |
| Xiaomi                           | 20       | 0.57%   |
| NetGear                          | 20       | 0.57%   |
| ASUSTek Computer                 | 18       | 0.51%   |
| Samsung Electronics              | 16       | 0.46%   |
| MediaTek                         | 13       | 0.37%   |
| Microsoft                        | 12       | 0.34%   |
| Gemtek                           | 9        | 0.26%   |
| Aquantia                         | 8        | 0.23%   |
| Belkin Components                | 7        | 0.2%    |
| ASIX Electronics                 | 7        | 0.2%    |
| Silicon Integrated Systems [SiS] | 6        | 0.17%   |
| DisplayLink                      | 5        | 0.14%   |
| AVM                              | 5        | 0.14%   |
| 3Com                             | 5        | 0.14%   |
| OPPO Electronics                 | 4        | 0.11%   |
| Linksys                          | 4        | 0.11%   |
| OnePlus Technology (Shenzhen)    | 3        | 0.09%   |
| Motorola                         | 3        | 0.09%   |
| Microchip Technology             | 3        | 0.09%   |
| ZyDAS                            | 2        | 0.06%   |
| ZTE WCDMA Technologies MSM       | 2        | 0.06%   |
| Smart Link                       | 2        | 0.06%   |
| Qualcomm                         | 2        | 0.06%   |
| QinHeng Electronics              | 2        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1197     | 30.66%  |
| Intel Ethernet Connection (2) I219-V                              | 108      | 2.77%   |
| Intel I211 Gigabit Network Connection                             | 104      | 2.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 92       | 2.36%   |
| Intel Wi-Fi 6 AX200                                               | 89       | 2.28%   |
| Intel 82579V Gigabit Network Connection                           | 66       | 1.69%   |
| Realtek RTL8125 2.5GbE Controller                                 | 65       | 1.66%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 49       | 1.26%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 44       | 1.13%   |
| Intel Ethernet Controller I225-V                                  | 43       | 1.1%    |
| Nvidia MCP61 Ethernet                                             | 39       | 1%      |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 39       | 1%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 37       | 0.95%   |
| Intel Ethernet Connection (7) I219-V                              | 37       | 0.95%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 36       | 0.92%   |
| Qualcomm Atheros AR9271 802.11n                                   | 35       | 0.9%    |
| Intel Ethernet Connection I217-LM                                 | 35       | 0.9%    |
| Intel Ethernet Connection I217-V                                  | 33       | 0.85%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 32       | 0.82%   |
| Realtek 802.11ac NIC                                              | 31       | 0.79%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 31       | 0.79%   |
| Intel Wireless 7265                                               | 30       | 0.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 29       | 0.74%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 29       | 0.74%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 24       | 0.61%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 24       | 0.61%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 24       | 0.61%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 24       | 0.61%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 23       | 0.59%   |
| Intel Wireless-AC 9260                                            | 21       | 0.54%   |
| Ralink MT7601U Wireless Adapter                                   | 20       | 0.51%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 20       | 0.51%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 19       | 0.49%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 18       | 0.46%   |
| Nvidia MCP77 Ethernet                                             | 17       | 0.44%   |
| Intel Ethernet Connection (2) I218-V                              | 17       | 0.44%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 17       | 0.44%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 16       | 0.41%   |
| Ralink RT2501/RT2573 Wireless Adapter                             | 15       | 0.38%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 15       | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 308      | 27.07%  |
| Intel                                 | 258      | 22.67%  |
| Qualcomm Atheros                      | 120      | 10.54%  |
| TP-Link                               | 84       | 7.38%   |
| Ralink Technology                     | 79       | 6.94%   |
| Broadcom                              | 42       | 3.69%   |
| Ralink                                | 40       | 3.51%   |
| Qualcomm Atheros Communications       | 37       | 3.25%   |
| D-Link                                | 27       | 2.37%   |
| D-Link System                         | 25       | 2.2%    |
| Sitecom Europe                        | 22       | 1.93%   |
| NetGear                               | 19       | 1.67%   |
| ASUSTek Computer                      | 17       | 1.49%   |
| Microsoft                             | 11       | 0.97%   |
| Gemtek                                | 9        | 0.79%   |
| Belkin Components                     | 7        | 0.62%   |
| MediaTek                              | 6        | 0.53%   |
| Broadcom Limited                      | 6        | 0.53%   |
| AVM                                   | 5        | 0.44%   |
| Linksys                               | 4        | 0.35%   |
| ZyDAS                                 | 2        | 0.18%   |
| Edimax Technology                     | 2        | 0.18%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2        | 0.18%   |
| ZyXEL Communications                  | 1        | 0.09%   |
| Wilocity                              | 1        | 0.09%   |
| Wacom                                 | 1        | 0.09%   |
| Samsung Electronics                   | 1        | 0.09%   |
| Fiberline                             | 1        | 0.09%   |
| AboCom Systems                        | 1        | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                        | 89       | 7.73%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 37       | 3.21%   |
| Qualcomm Atheros AR9271 802.11n                                            | 35       | 3.04%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                         | 32       | 2.78%   |
| Realtek 802.11ac NIC                                                       | 31       | 2.69%   |
| Intel Wireless 7265                                                        | 30       | 2.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 29       | 2.52%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                | 24       | 2.08%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                            | 24       | 2.08%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                     | 24       | 2.08%   |
| Intel Wireless-AC 9260                                                     | 21       | 1.82%   |
| Ralink MT7601U Wireless Adapter                                            | 20       | 1.74%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 20       | 1.74%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                 | 18       | 1.56%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                         | 17       | 1.48%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 16       | 1.39%   |
| Ralink RT2501/RT2573 Wireless Adapter                                      | 15       | 1.3%    |
| Intel Wireless 3165                                                        | 15       | 1.3%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                         | 15       | 1.3%    |
| Ralink RT5370 Wireless Adapter                                             | 14       | 1.22%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                   | 13       | 1.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 13       | 1.13%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                           | 13       | 1.13%   |
| Intel Wireless 7260                                                        | 12       | 1.04%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 12       | 1.04%   |
| Ralink RT2870/RT3070 Wireless Adapter                                      | 11       | 0.95%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 11       | 0.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 11       | 0.95%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 11       | 0.95%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]         | 11       | 0.95%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                        | 10       | 0.87%   |
| TP-Link 802.11ac WLAN Adapter                                              | 10       | 0.87%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 10       | 0.87%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 10       | 0.87%   |
| Intel Tiger Lake PCH CNVi WiFi                                             | 10       | 0.87%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                   | 9        | 0.78%   |
| Realtek RTL8187 Wireless Adapter                                           | 9        | 0.78%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 9        | 0.78%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                  | 9        | 0.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 9        | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 1384     | 51.89%  |
| Intel                             | 743      | 27.86%  |
| Qualcomm Atheros                  | 134      | 5.02%   |
| Nvidia                            | 97       | 3.64%   |
| Broadcom                          | 65       | 2.44%   |
| Marvell Technology Group          | 62       | 2.32%   |
| Broadcom Limited                  | 28       | 1.05%   |
| VIA Technologies                  | 26       | 0.97%   |
| Huawei Technologies               | 23       | 0.86%   |
| Xiaomi                            | 20       | 0.75%   |
| Samsung Electronics               | 15       | 0.56%   |
| D-Link System                     | 8        | 0.3%    |
| Aquantia                          | 8        | 0.3%    |
| MediaTek                          | 7        | 0.26%   |
| ASIX Electronics                  | 7        | 0.26%   |
| Silicon Integrated Systems [SiS]  | 6        | 0.22%   |
| DisplayLink                       | 5        | 0.19%   |
| 3Com                              | 5        | 0.19%   |
| OPPO Electronics                  | 4        | 0.15%   |
| ZTE WCDMA Technologies MSM        | 2        | 0.07%   |
| TP-Link                           | 2        | 0.07%   |
| Qualcomm                          | 2        | 0.07%   |
| OnePlus Technology (Shenzhen)     | 2        | 0.07%   |
| Google                            | 2        | 0.07%   |
| ULi Electronics                   | 1        | 0.04%   |
| SysKonnect                        | 1        | 0.04%   |
| Sundance Technology Inc / IC Plus | 1        | 0.04%   |
| NetGear                           | 1        | 0.04%   |
| Motorola PCS                      | 1        | 0.04%   |
| LG Electronics                    | 1        | 0.04%   |
| JMicron Technology                | 1        | 0.04%   |
| HTC (High Tech Computer)          | 1        | 0.04%   |
| HMD Global                        | 1        | 0.04%   |
| ASUSTek Computer                  | 1        | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1197     | 43.98%  |
| Intel Ethernet Connection (2) I219-V                              | 108      | 3.97%   |
| Intel I211 Gigabit Network Connection                             | 104      | 3.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 92       | 3.38%   |
| Intel 82579V Gigabit Network Connection                           | 66       | 2.42%   |
| Realtek RTL8125 2.5GbE Controller                                 | 65       | 2.39%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 49       | 1.8%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 44       | 1.62%   |
| Intel Ethernet Controller I225-V                                  | 43       | 1.58%   |
| Nvidia MCP61 Ethernet                                             | 39       | 1.43%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 39       | 1.43%   |
| Intel Ethernet Connection (7) I219-V                              | 37       | 1.36%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 36       | 1.32%   |
| Intel Ethernet Connection I217-LM                                 | 35       | 1.29%   |
| Intel Ethernet Connection I217-V                                  | 33       | 1.21%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 31       | 1.14%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 29       | 1.07%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 24       | 0.88%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 23       | 0.84%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 19       | 0.7%    |
| Nvidia MCP77 Ethernet                                             | 17       | 0.62%   |
| Intel Ethernet Connection (2) I218-V                              | 17       | 0.62%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 15       | 0.55%   |
| Intel 82578DM Gigabit Network Connection                          | 15       | 0.55%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 15       | 0.55%   |
| Nvidia MCP73 Ethernet                                             | 14       | 0.51%   |
| Intel 82578DC Gigabit Network Connection                          | 14       | 0.51%   |
| Intel 82574L Gigabit Network Connection                           | 14       | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 13       | 0.48%   |
| Intel NM10/ICH7 Family LAN Controller                             | 13       | 0.48%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 12       | 0.44%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 12       | 0.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 12       | 0.44%   |
| Huawei ANA-NX9                                                    | 12       | 0.44%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 11       | 0.4%    |
| Intel Ethernet Connection (2) I219-LM                             | 11       | 0.4%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 10       | 0.37%   |
| Intel I210 Gigabit Network Connection                             | 10       | 0.37%   |
| Intel 82567V-2 Gigabit Network Connection                         | 10       | 0.37%   |
| Nvidia MCP55 Ethernet                                             | 9        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2451     | 69.26%  |
| WiFi     | 1059     | 29.92%  |
| Modem    | 26       | 0.73%   |
| Unknown  | 3        | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1893     | 74.88%  |
| WiFi     | 634      | 25.08%  |
| Unknown  | 1        | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1699     | 68.4%   |
| 2     | 690      | 27.78%  |
| 3     | 72       | 2.9%    |
| 0     | 14       | 0.56%   |
| 4     | 4        | 0.16%   |
| 6     | 2        | 0.08%   |
| 5     | 2        | 0.08%   |
| 12    | 1        | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2354     | 94.61%  |
| Yes  | 134      | 5.39%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 231      | 34.12%  |
| Cambridge Silicon Radio         | 196      | 28.95%  |
| Realtek Semiconductor           | 66       | 9.75%   |
| Broadcom                        | 48       | 7.09%   |
| ASUSTek Computer                | 44       | 6.5%    |
| Qualcomm Atheros Communications | 20       | 2.95%   |
| Apple                           | 13       | 1.92%   |
| IMC Networks                    | 12       | 1.77%   |
| Integrated System Solution      | 8        | 1.18%   |
| TP-Link                         | 7        | 1.03%   |
| MediaTek                        | 4        | 0.59%   |
| Lite-On Technology              | 4        | 0.59%   |
| Belkin Components               | 4        | 0.59%   |
| Sitecom Europe                  | 3        | 0.44%   |
| Realtek                         | 2        | 0.3%    |
| D-Link System                   | 2        | 0.3%    |
| Conwise Technology              | 2        | 0.3%    |
| Accel Semiconductor             | 2        | 0.3%    |
| SINO WEALTH                     | 1        | 0.15%   |
| Logitech                        | 1        | 0.15%   |
| HTC (High Tech Computer)        | 1        | 0.15%   |
| Hewlett-Packard                 | 1        | 0.15%   |
| Fujitsu Siemens Computers       | 1        | 0.15%   |
| Fujitsu                         | 1        | 0.15%   |
| Foxconn / Hon Hai               | 1        | 0.15%   |
| Dell                            | 1        | 0.15%   |
| 3Com                            | 1        | 0.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 196      | 28.91%  |
| Intel AX200 Bluetooth                                 | 77       | 11.36%  |
| Intel Bluetooth wireless interface                    | 63       | 9.29%   |
| Realtek Bluetooth Radio                               | 44       | 6.49%   |
| Intel AX201 Bluetooth                                 | 26       | 3.83%   |
| Intel Wireless-AC 3168 Bluetooth                      | 20       | 2.95%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 19       | 2.8%    |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 19       | 2.8%    |
| Realtek  Bluetooth 4.2 Adapter                        | 18       | 2.65%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 14       | 2.06%   |
| Broadcom BCM2045 Bluetooth                            | 14       | 2.06%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 13       | 1.92%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 12       | 1.77%   |
| Intel AX210 Bluetooth                                 | 12       | 1.77%   |
| Apple Bluetooth Host Controller                       | 10       | 1.47%   |
| TP-Link UB500 Adapter                                 | 7        | 1.03%   |
| ASUS BCM20702A0                                       | 7        | 1.03%   |
| IMC Networks Bluetooth Device                         | 6        | 0.88%   |
| ASUS Qualcomm Bluetooth 4.1                           | 6        | 0.88%   |
| ASUS Bluetooth Radio                                  | 6        | 0.88%   |
| ASUS Bluetooth Adapter                                | 6        | 0.88%   |
| IMC Networks Bluetooth Radio                          | 5        | 0.74%   |
| Qualcomm Atheros  Bluetooth Device                    | 4        | 0.59%   |
| MediaTek Wireless_Device                              | 4        | 0.59%   |
| Lite-On Bluetooth Device                              | 4        | 0.59%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 4        | 0.59%   |
| Integrated System Solution Bluetooth Device           | 4        | 0.59%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter      | 3        | 0.44%   |
| Broadcom BCM2035 Bluetooth dongle                     | 3        | 0.44%   |
| ASUS Bluetooth Device                                 | 3        | 0.44%   |
| Realtek RTL8821A Bluetooth                            | 2        | 0.29%   |
| Realtek Bluetooth 5.1 Radio                           | 2        | 0.29%   |
| Realtek Bluetooth Radio                               | 2        | 0.29%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 2        | 0.29%   |
| D-Link System DBT-122 Bluetooth                       | 2        | 0.29%   |
| Conwise CW6622                                        | 2        | 0.29%   |
| Broadcom Bluetooth 3.0 Device                         | 2        | 0.29%   |
| Belkin Components F8T012 Bluetooth Adapter            | 2        | 0.29%   |
| Apple Bluetooth HCI                                   | 2        | 0.29%   |
| Accel Bluetooth Device                                | 2        | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 1586     | 39.32%  |
| Nvidia                               | 969      | 24.02%  |
| AMD                                  | 941      | 23.33%  |
| C-Media Electronics                  | 121      | 3%      |
| Creative Labs                        | 52       | 1.29%   |
| Logitech                             | 35       | 0.87%   |
| VIA Technologies                     | 33       | 0.82%   |
| Razer USA                            | 16       | 0.4%    |
| JMTek                                | 15       | 0.37%   |
| Texas Instruments                    | 14       | 0.35%   |
| Creative Technology                  | 13       | 0.32%   |
| M-Audio                              | 12       | 0.3%    |
| Focusrite-Novation                   | 12       | 0.3%    |
| Kingston Technology                  | 10       | 0.25%   |
| ASUSTek Computer                     | 10       | 0.25%   |
| Generalplus Technology               | 9        | 0.22%   |
| Tenx Technology                      | 8        | 0.2%    |
| Silicon Integrated Systems [SiS]     | 8        | 0.2%    |
| GN Netcom                            | 8        | 0.2%    |
| Trust                                | 7        | 0.17%   |
| Micro Star International             | 7        | 0.17%   |
| Ensoniq                              | 7        | 0.17%   |
| Dell                                 | 7        | 0.17%   |
| Samson Technologies                  | 6        | 0.15%   |
| Microsoft                            | 6        | 0.15%   |
| BEHRINGER International              | 6        | 0.15%   |
| Thesycon Systemsoftware & Consulting | 5        | 0.12%   |
| Corsair                              | 5        | 0.12%   |
| Yamaha                               | 4        | 0.1%    |
| SAVITECH                             | 4        | 0.1%    |
| Realtek Semiconductor                | 4        | 0.1%    |
| Plantronics                          | 4        | 0.1%    |
| XMOS                                 | 3        | 0.07%   |
| SteelSeries ApS                      | 3        | 0.07%   |
| Sennheiser Communications            | 3        | 0.07%   |
| KTMicro                              | 3        | 0.07%   |
| Hewlett-Packard                      | 3        | 0.07%   |
| Cambridge Silicon Radio              | 3        | 0.07%   |
| BR36                                 | 3        | 0.07%   |
| Bose                                 | 3        | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 187      | 4.11%   |
| AMD Starship/Matisse HD Audio Controller                                          | 178      | 3.91%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 177      | 3.89%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 167      | 3.67%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 157      | 3.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 133      | 2.92%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 130      | 2.86%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 108      | 2.37%   |
| Intel 200 Series PCH HD Audio                                                     | 102      | 2.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 100      | 2.2%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 98       | 2.15%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 93       | 2.04%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 93       | 2.04%   |
| AMD Family 17h/19h HD Audio Controller                                            | 92       | 2.02%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 87       | 1.91%   |
| Nvidia High Definition Audio Controller                                           | 85       | 1.87%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 84       | 1.85%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 82       | 1.8%    |
| AMD FCH Azalia Controller                                                         | 81       | 1.78%   |
| Intel Cannon Lake PCH cAVS                                                        | 77       | 1.69%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 58       | 1.27%   |
| Nvidia GF108 High Definition Audio Controller                                     | 57       | 1.25%   |
| Nvidia GP106 High Definition Audio Controller                                     | 53       | 1.16%   |
| Nvidia GF119 HDMI Audio Controller                                                | 53       | 1.16%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 52       | 1.14%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 51       | 1.12%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 48       | 1.05%   |
| Nvidia TU116 High Definition Audio Controller                                     | 46       | 1.01%   |
| Nvidia MCP61 High Definition Audio                                                | 46       | 1.01%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 45       | 0.99%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 44       | 0.97%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 44       | 0.97%   |
| AMD Navi 10 HDMI Audio                                                            | 38       | 0.84%   |
| Nvidia GP108 High Definition Audio Controller                                     | 36       | 0.79%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 35       | 0.77%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                 | 35       | 0.77%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 35       | 0.77%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 34       | 0.75%   |
| Nvidia TU106 High Definition Audio Controller                                     | 31       | 0.68%   |
| Nvidia GK107 HDMI Audio Controller                                                | 31       | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 269      | 18.71%  |
| Unknown                      | 242      | 16.83%  |
| Corsair                      | 208      | 14.46%  |
| Crucial                      | 152      | 10.57%  |
| Samsung Electronics          | 130      | 9.04%   |
| SK hynix                     | 102      | 7.09%   |
| G.Skill                      | 78       | 5.42%   |
| Micron Technology            | 69       | 4.8%    |
| Team                         | 26       | 1.81%   |
| Patriot                      | 23       | 1.6%    |
| A-DATA Technology            | 19       | 1.32%   |
| Nanya Technology             | 15       | 1.04%   |
| Ramaxel Technology           | 14       | 0.97%   |
| Unknown (ABCD)               | 13       | 0.9%    |
| Elpida                       | 12       | 0.83%   |
| Unknown                      | 12       | 0.83%   |
| Transcend                    | 7        | 0.49%   |
| Unifosa                      | 6        | 0.42%   |
| Patriot Memory (PDP Systems) | 4        | 0.28%   |
| ASint Technology             | 4        | 0.28%   |
| Unknown (AB)                 | 3        | 0.21%   |
| Hewlett-Packard              | 3        | 0.21%   |
| GeIL                         | 3        | 0.21%   |
| Silicon Power                | 2        | 0.14%   |
| Qimonda                      | 2        | 0.14%   |
| PLEXHD                       | 2        | 0.14%   |
| GOODRAM                      | 2        | 0.14%   |
| CSX                          | 2        | 0.14%   |
| A Force                      | 2        | 0.14%   |
| V-Color                      | 1        | 0.07%   |
| TwinMOS                      | 1        | 0.07%   |
| Toshiba                      | 1        | 0.07%   |
| Thermaltake                  | 1        | 0.07%   |
| PUSKILL                      | 1        | 0.07%   |
| Netac                        | 1        | 0.07%   |
| KomputerBay                  | 1        | 0.07%   |
| Kllisre                      | 1        | 0.07%   |
| Kingmax                      | 1        | 0.07%   |
| INNOVATION PC                | 1        | 0.07%   |
| Goldkey                      | 1        | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s        | 28       | 1.75%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s        | 21       | 1.32%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 19       | 1.19%   |
| Unknown RAM Module 4096MB DIMM DDR2 266MT/s                  | 13       | 0.81%   |
| Unknown RAM Module 2048MB DIMM SDRAM                         | 13       | 0.81%   |
| Unknown (ABCD) RAM 123456789012345678 1GB DIMM DDR3 2400MT/s | 13       | 0.81%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s         | 13       | 0.81%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4                 | 12       | 0.75%   |
| Unknown                                                      | 12       | 0.75%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 10       | 0.63%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                  | 9        | 0.56%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s          | 9        | 0.56%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s          | 9        | 0.56%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s           | 9        | 0.56%   |
| Crucial RAM BL8G36C16U4B.M8FE1 8GB DIMM DDR4 3733MT/s        | 9        | 0.56%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s         | 8        | 0.5%    |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s          | 8        | 0.5%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 7        | 0.44%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s        | 7        | 0.44%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s          | 7        | 0.44%   |
| Unknown RAM Module 512MB DIMM SDRAM                          | 6        | 0.38%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                  | 6        | 0.38%   |
| Unknown RAM Module 1024MB DIMM                               | 6        | 0.38%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s           | 6        | 0.38%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 2400MT/s           | 6        | 0.38%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s          | 6        | 0.38%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s          | 6        | 0.38%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3266MT/s          | 6        | 0.38%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s            | 6        | 0.38%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s          | 6        | 0.38%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s            | 6        | 0.38%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s          | 6        | 0.38%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s          | 6        | 0.38%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s       | 6        | 0.38%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 5        | 0.31%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 5        | 0.31%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                  | 5        | 0.31%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                      | 5        | 0.31%   |
| Unknown RAM Module 1024MB DIMM SDRAM                         | 5        | 0.31%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                   | 5        | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 536      | 41.39%  |
| DDR3    | 435      | 33.59%  |
| DDR2    | 128      | 9.88%   |
| SDRAM   | 85       | 6.56%   |
| Unknown | 64       | 4.94%   |
| DDR     | 22       | 1.7%    |
| LPDDR4  | 14       | 1.08%   |
| DDR5    | 6        | 0.46%   |
| LPDDR3  | 5        | 0.39%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 1192     | 95.28%  |
| SODIMM  | 55       | 4.4%    |
| FB-DIMM | 4        | 0.32%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 493      | 35.24%  |
| 4096  | 334      | 23.87%  |
| 2048  | 263      | 18.8%   |
| 16384 | 161      | 11.51%  |
| 1024  | 89       | 6.36%   |
| 32768 | 33       | 2.36%   |
| 512   | 19       | 1.36%   |
| 256   | 4        | 0.29%   |
| 3072  | 2        | 0.14%   |
| 32    | 1        | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 242      | 17.2%   |
| 1333    | 161      | 11.44%  |
| 3600    | 104      | 7.39%   |
| 3200    | 97       | 6.89%   |
| 2400    | 83       | 5.9%    |
| 800     | 77       | 5.47%   |
| 2667    | 59       | 4.19%   |
| 2133    | 49       | 3.48%   |
| Unknown | 45       | 3.2%    |
| 1867    | 42       | 2.99%   |
| 667     | 42       | 2.99%   |
| 3400    | 31       | 2.2%    |
| 3000    | 31       | 2.2%    |
| 3466    | 27       | 1.92%   |
| 2933    | 23       | 1.63%   |
| 1066    | 19       | 1.35%   |
| 3733    | 18       | 1.28%   |
| 1866    | 18       | 1.28%   |
| 1800    | 17       | 1.21%   |
| 3666    | 15       | 1.07%   |
| 266     | 15       | 1.07%   |
| 3800    | 14       | 1%      |
| 1334    | 13       | 0.92%   |
| 400     | 13       | 0.92%   |
| 2666    | 12       | 0.85%   |
| 3266    | 11       | 0.78%   |
| 2800    | 8        | 0.57%   |
| 533     | 8        | 0.57%   |
| 333     | 7        | 0.5%    |
| 2048    | 6        | 0.43%   |
| 2000    | 6        | 0.43%   |
| 3500    | 5        | 0.36%   |
| 1639    | 5        | 0.36%   |
| 1400    | 5        | 0.36%   |
| 1067    | 5        | 0.36%   |
| 49926   | 4        | 0.28%   |
| 4800    | 4        | 0.28%   |
| 3333    | 4        | 0.28%   |
| 3100    | 4        | 0.28%   |
| 2472    | 4        | 0.28%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 84       | 39.07%  |
| Samsung Electronics   | 33       | 15.35%  |
| Canon                 | 29       | 13.49%  |
| Seiko Epson           | 26       | 12.09%  |
| Brother Industries    | 22       | 10.23%  |
| Lexmark International | 4        | 1.86%   |
| Xerox                 | 3        | 1.4%    |
| Prolific Technology   | 2        | 0.93%   |
| Oki Data              | 2        | 0.93%   |
| Dymo-CoStar           | 2        | 0.93%   |
| Toshiba TEC           | 1        | 0.47%   |
| STMicroelectronics    | 1        | 0.47%   |
| Sato                  | 1        | 0.47%   |
| Ricoh                 | 1        | 0.47%   |
| QinHeng Electronics   | 1        | 0.47%   |
| Pantum                | 1        | 0.47%   |
| Kyocera               | 1        | 0.47%   |
| Apple                 | 1        | 0.47%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung M2020 Series                                                  | 9        | 4.19%   |
| Seiko Epson WF-2510 Series                                            | 7        | 3.26%   |
| HP OfficeJet 6950                                                     | 7        | 3.26%   |
| HP Deskjet 2050 J510                                                  | 6        | 2.79%   |
| Canon LiDE 400                                                        | 5        | 2.33%   |
| Samsung M267x 287x Series                                             | 4        | 1.86%   |
| HP LaserJet 1018                                                      | 4        | 1.86%   |
| HP ENVY 4520 series                                                   | 4        | 1.86%   |
| Canon PIXMA MG3600 Series                                             | 4        | 1.86%   |
| Seiko Epson Printer                                                   | 3        | 1.4%    |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 3        | 1.4%    |
| Samsung ML-216x Series Laser Printer                                  | 3        | 1.4%    |
| Samsung M2070 Series                                                  | 3        | 1.4%    |
| Samsung Composite Device                                              | 3        | 1.4%    |
| HP LaserJet Professional P 1102w                                      | 3        | 1.4%    |
| HP LaserJet P1102                                                     | 3        | 1.4%    |
| HP LaserJet P1005                                                     | 3        | 1.4%    |
| HP Deskjet F4500 series                                               | 3        | 1.4%    |
| HP Deskjet 3050A                                                      | 3        | 1.4%    |
| Brother MFC-L2700DW                                                   | 3        | 1.4%    |
| Brother DCP-1610W                                                     | 3        | 1.4%    |
| Seiko Epson ET-2820 Series                                            | 2        | 0.93%   |
| Samsung ML-1660 Series                                                | 2        | 0.93%   |
| Samsung ML-1640 Series Laser Printer                                  | 2        | 0.93%   |
| Prolific PL2305 Parallel Port                                         | 2        | 0.93%   |
| Oki Data USB Device                                                   | 2        | 0.93%   |
| Lexmark International InkJet Color Printer                            | 2        | 0.93%   |
| HP OfficeJet 5200 series                                              | 2        | 0.93%   |
| HP Officejet 4630 series                                              | 2        | 0.93%   |
| HP Officejet 4500 G510n-z                                             | 2        | 0.93%   |
| HP Officejet 2620 series                                              | 2        | 0.93%   |
| HP LaserJet Pro M12a                                                  | 2        | 0.93%   |
| HP LaserJet 1200                                                      | 2        | 0.93%   |
| HP ENVY 5000 series                                                   | 2        | 0.93%   |
| HP DeskJet F4200 series                                               | 2        | 0.93%   |
| HP Deskjet 3520 series                                                | 2        | 0.93%   |
| HP DeskJet 2130 series                                                | 2        | 0.93%   |
| Canon PIXMA MX920 Series                                              | 2        | 0.93%   |
| Canon PIXMA MG2500 Series                                             | 2        | 0.93%   |
| Canon CanoScan LiDE 300                                               | 2        | 0.93%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 31       | 53.45%  |
| Seiko Epson        | 14       | 24.14%  |
| Hewlett-Packard    | 7        | 12.07%  |
| Mustek Systems     | 4        | 6.9%    |
| Ultima Electronics | 1        | 1.72%   |
| Plustek            | 1        | 1.72%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 110                                                               | 7        | 12.07%  |
| Canon CanoScan LiDE 210                                                               | 6        | 10.34%  |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 3        | 5.17%   |
| Canon CanoScan LiDE 120                                                               | 3        | 5.17%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 2        | 3.45%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 2        | 3.45%   |
| Seiko Epson GT-7700U [Perfection 1240U]                                               | 2        | 3.45%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 2        | 3.45%   |
| HP Scanjet 200                                                                        | 2        | 3.45%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 2        | 3.45%   |
| Canon CanoScan LiDE 60                                                                | 2        | 3.45%   |
| Canon CanoScan LiDE 100                                                               | 2        | 3.45%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1        | 1.72%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 1        | 1.72%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 1        | 1.72%   |
| Seiko Epson GT-F700 [Perfection V350]                                                 | 1        | 1.72%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1        | 1.72%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 1        | 1.72%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 1        | 1.72%   |
| Seiko Epson GT-7600UF [Perfection 1200U/1200U Photo]                                  | 1        | 1.72%   |
| Seiko Epson GT-6600U [Perfection 610]                                                 | 1        | 1.72%   |
| Plustek 600DPI USB Scanner                                                            | 1        | 1.72%   |
| Mustek Systems SNAPSCAN e22                                                           | 1        | 1.72%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO                                            | 1        | 1.72%   |
| HP ScanJet 3800c                                                                      | 1        | 1.72%   |
| HP ScanJet 3400cse                                                                    | 1        | 1.72%   |
| HP ScanJet 2400c                                                                      | 1        | 1.72%   |
| HP PSC 1200                                                                           | 1        | 1.72%   |
| HP HP4470C                                                                            | 1        | 1.72%   |
| Canon CanoScan LiDE 90                                                                | 1        | 1.72%   |
| Canon CanoScan LiDE 700F                                                              | 1        | 1.72%   |
| Canon CanoScan LiDE 600F                                                              | 1        | 1.72%   |
| Canon CanoScan LIDE 25                                                                | 1        | 1.72%   |
| Canon CanoScan LiDE 220                                                               | 1        | 1.72%   |
| Canon CanoScan 4200F                                                                  | 1        | 1.72%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                            | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech                                          | 165      | 33.4%   |
| Microdia                                          | 61       | 12.35%  |
| Microsoft                                         | 53       | 10.73%  |
| Sunplus Innovation Technology                     | 23       | 4.66%   |
| ARC International                                 | 17       | 3.44%   |
| Trust                                             | 14       | 2.83%   |
| Samsung Electronics                               | 12       | 2.43%   |
| Generalplus Technology                            | 11       | 2.23%   |
| Chicony Electronics                               | 11       | 2.23%   |
| Cubeternet                                        | 9        | 1.82%   |
| Z-Star Microelectronics                           | 7        | 1.42%   |
| Realtek Semiconductor                             | 7        | 1.42%   |
| KYE Systems (Mouse Systems)                       | 7        | 1.42%   |
| Apple                                             | 7        | 1.42%   |
| WaveRider Communications                          | 6        | 1.21%   |
| Huawei Technologies                               | 6        | 1.21%   |
| GEMBIRD                                           | 6        | 1.21%   |
| webcam                                            | 5        | 1.01%   |
| Sunplus IT                                        | 5        | 1.01%   |
| IMC Networks                                      | 4        | 0.81%   |
| Aveo Technology                                   | 4        | 0.81%   |
| SunplusIT                                         | 3        | 0.61%   |
| MacroSilicon                                      | 3        | 0.61%   |
| Jieli Technology                                  | 3        | 0.61%   |
| Genesys Logic                                     | 3        | 0.61%   |
| Arkmicro Technologies                             | 3        | 0.61%   |
| Xiongmai                                          | 2        | 0.4%    |
| Unknown                                           | 2        | 0.4%    |
| Silicon Motion                                    | 2        | 0.4%    |
| Novatel Wireless                                  | 2        | 0.4%    |
| LG Electronics                                    | 2        | 0.4%    |
| Hewlett-Packard                                   | 2        | 0.4%    |
| Creative Technology                               | 2        | 0.4%    |
| TerraTec Electronic                               | 1        | 0.2%    |
| Syntek                                            | 1        | 0.2%    |
| Suyin                                             | 1        | 0.2%    |
| Sunplus Technology                                | 1        | 0.2%    |
| STMicroelectronics Imaging Division (VLSI Vision) | 1        | 0.2%    |
| Sonix Technology                                  | 1        | 0.2%    |
| SiGma Micro                                       | 1        | 0.2%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech Webcam C270                     | 49       | 9.88%   |
| Microsoft LifeCam HD-3000                | 24       | 4.84%   |
| Logitech Webcam C170                     | 22       | 4.44%   |
| Logitech HD Pro Webcam C920              | 18       | 3.63%   |
| ARC International Camera                 | 17       | 3.43%   |
| Microdia Webcam Vitade AF                | 16       | 3.23%   |
| Samsung Galaxy A5 (MTP)                  | 12       | 2.42%   |
| Microdia Camera                          | 12       | 2.42%   |
| Microdia USB 2.0 Camera                  | 11       | 2.22%   |
| Logitech Webcam C310                     | 11       | 2.22%   |
| Microdia Sonix USB 2.0 Camera            | 10       | 2.02%   |
| Sunplus Aukey-PC-LM1E Camera             | 8        | 1.61%   |
| Generalplus GENERAL WEBCAM               | 8        | 1.61%   |
| Microdia Integrated Camera               | 7        | 1.41%   |
| WaveRider USB 2.0 Camera                 | 6        | 1.21%   |
| Microsoft LifeCam VX-2000                | 6        | 1.21%   |
| Logitech QuickCam Pro 9000               | 6        | 1.21%   |
| Logitech HD Webcam C525                  | 6        | 1.21%   |
| Huawei UVC Camera                        | 6        | 1.21%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X          | 6        | 1.21%   |
| webcam webcam                            | 5        | 1.01%   |
| Trust WB-6250X Webcam                    | 5        | 1.01%   |
| Sunplus IT AUKEY PC-LM1 USB Camera       | 5        | 1.01%   |
| Sunplus WEMISS CM-A1                     | 5        | 1.01%   |
| Logitech HD Webcam C910                  | 5        | 1.01%   |
| Trust Webcam                             | 4        | 0.81%   |
| Trust 17676 Webcam                       | 4        | 0.81%   |
| Microsoft LifeCam VX-800                 | 4        | 0.81%   |
| Microsoft LifeCam VX-5000                | 4        | 0.81%   |
| Microsoft LifeCam HD-5000                | 4        | 0.81%   |
| Logitech Webcam C200                     | 4        | 0.81%   |
| Logitech QuickCam E 3500                 | 4        | 0.81%   |
| Logitech C922 Pro Stream Webcam          | 4        | 0.81%   |
| KYE Systems (Mouse Systems) PC-W3 Camera | 4        | 0.81%   |
| GEMBIRD USB2.0 PC CAMERA                 | 4        | 0.81%   |
| Sunplus HD 720P webcam                   | 3        | 0.6%    |
| Microsoft LifeCam VX-700                 | 3        | 0.6%    |
| Microsoft LifeCam Cinema                 | 3        | 0.6%    |
| Logitech Webcam C210                     | 3        | 0.6%    |
| Logitech StreamCam                       | 3        | 0.6%    |

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


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Advanced Card Systems     | 18       | 37.5%   |
| BIT4ID                    | 7        | 14.58%  |
| Realtek Semiconductor     | 5        | 10.42%  |
| Gemalto (was Gemplus)     | 4        | 8.33%   |
| SCM Microsystems          | 3        | 6.25%   |
| Clay Logic                | 3        | 6.25%   |
| Alcor Micro               | 3        | 6.25%   |
| OmniKey                   | 2        | 4.17%   |
| Reiner SCT Kartensysteme  | 1        | 2.08%   |
| Microchip Technology      | 1        | 2.08%   |
| Fujitsu Siemens Computers | 1        | 2.08%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Advanced Card Systems ACR38 SmartCard Reader                               | 14       | 28.57%  |
| BIT4ID miniLector EVO                                                      | 6        | 12.24%  |
| Realtek Semiconductor Smart Card Reader Interface                          | 5        | 10.2%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 4        | 8.16%   |
| Advanced Card Systems ACR122U                                              | 4        | 8.16%   |
| Clay Logic Nitrokey Pro                                                    | 3        | 6.12%   |
| Alcor Micro Watchdata W 1981                                               | 2        | 4.08%   |
| SCM Microsystems uTrust 3700 F CL Reader                                   | 1        | 2.04%   |
| SCM Microsystems SCR35xx Smart Card Reader                                 | 1        | 2.04%   |
| SCM Microsystems SCR335 SmartCard Reader                                   | 1        | 2.04%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 2.04%   |
| OmniKey CardMan 3021 / 3121                                                | 1        | 2.04%   |
| OmniKey 3x21 Smart Card Reader                                             | 1        | 2.04%   |
| Microchip Technology SMSC USX101x Reader                                   | 1        | 2.04%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                              | 1        | 2.04%   |
| BIT4ID miniLector AIR NFC v3                                               | 1        | 2.04%   |
| Alcor Micro AU9540 Smartcard Reader                                        | 1        | 2.04%   |
| Advanced Card Systems ACR1281 1S Dual Reader                               | 1        | 2.04%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 2168     | 85.9%   |
| 1     | 313      | 12.4%   |
| 2     | 31       | 1.23%   |
| 3     | 7        | 0.28%   |
| 5     | 3        | 0.12%   |
| 4     | 2        | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 121      | 30.71%  |
| Net/wireless             | 102      | 25.89%  |
| Communication controller | 40       | 10.15%  |
| Chipcard                 | 30       | 7.61%   |
| Unassigned class         | 25       | 6.35%   |
| Sound                    | 13       | 3.3%    |
| Multimedia controller    | 11       | 2.79%   |
| Camera                   | 11       | 2.79%   |
| Card reader              | 9        | 2.28%   |
| Modem                    | 6        | 1.52%   |
| Firewire controller      | 5        | 1.27%   |
| Storage/raid             | 4        | 1.02%   |
| Bluetooth                | 4        | 1.02%   |
| Network                  | 3        | 0.76%   |
| Dvb card                 | 3        | 0.76%   |
| Video                    | 2        | 0.51%   |
| Tv card                  | 2        | 0.51%   |
| Net/ethernet             | 2        | 0.51%   |
| Storage/ide              | 1        | 0.25%   |

