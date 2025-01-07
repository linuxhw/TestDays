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

Total: 848

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | Z690M-ITX/ax                | [bbbb62d243](https://linux-hardware.org/?probe=bbbb62d243) | Jan 05, 2025 |
| Gigabyte      | AX370-Gaming K7             | [50b5770d28](https://linux-hardware.org/?probe=50b5770d28) | Jan 02, 2025 |
| ASUSTek       | 970 PRO GAMING/AURA         | [4885d454da](https://linux-hardware.org/?probe=4885d454da) | Dec 23, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [671a76bf13](https://linux-hardware.org/?probe=671a76bf13) | Dec 21, 2024 |
| Pegatron      | 2AB6                        | [6ab7d72400](https://linux-hardware.org/?probe=6ab7d72400) | Dec 08, 2024 |
| Gigabyte      | AX370-Gaming K7             | [5b59960dcf](https://linux-hardware.org/?probe=5b59960dcf) | Dec 02, 2024 |
| HP            | 87D6 SMVB                   | [88199b7676](https://linux-hardware.org/?probe=88199b7676) | Nov 18, 2024 |
| HP            | 87D6 SMVB                   | [9ee644390f](https://linux-hardware.org/?probe=9ee644390f) | Nov 18, 2024 |
| Foxconn       | G31MXP FAB:1.1              | [e6250c0cfc](https://linux-hardware.org/?probe=e6250c0cfc) | Nov 16, 2024 |
| Gigabyte      | AX370-Gaming K7             | [3a24bb6154](https://linux-hardware.org/?probe=3a24bb6154) | Nov 02, 2024 |
| Fujitsu       | D3164-C2 S26361-D3164-C2    | [9fed3b2d74](https://linux-hardware.org/?probe=9fed3b2d74) | Oct 29, 2024 |
| HP            | 18E4                        | [0936cdf872](https://linux-hardware.org/?probe=0936cdf872) | Oct 28, 2024 |
| ASUSTek       | PRIME B550-PLUS             | [0ef7db0f77](https://linux-hardware.org/?probe=0ef7db0f77) | Oct 28, 2024 |
| MSI           | B350M PRO-VDH               | [dd36ced75f](https://linux-hardware.org/?probe=dd36ced75f) | Oct 23, 2024 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [594f81b2d2](https://linux-hardware.org/?probe=594f81b2d2) | Oct 23, 2024 |
| MSI           | B350M PRO-VDH               | [30255b191f](https://linux-hardware.org/?probe=30255b191f) | Oct 21, 2024 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [60b027e69b](https://linux-hardware.org/?probe=60b027e69b) | Oct 19, 2024 |
| Acer          | Veriton X2631G V:1.0        | [c16aec5e6a](https://linux-hardware.org/?probe=c16aec5e6a) | Oct 14, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [958542aabf](https://linux-hardware.org/?probe=958542aabf) | Oct 13, 2024 |
| MSI           | PRO H610M-E DDR4            | [a95a15d17b](https://linux-hardware.org/?probe=a95a15d17b) | Oct 08, 2024 |
| Unknown       | Unknown                     | [599e683113](https://linux-hardware.org/?probe=599e683113) | Oct 06, 2024 |
| Pegatron      | 2AB6                        | [9e31ddb1af](https://linux-hardware.org/?probe=9e31ddb1af) | Oct 04, 2024 |
| ASRock        | H410M-HDV                   | [01a1e8594c](https://linux-hardware.org/?probe=01a1e8594c) | Oct 04, 2024 |
| Pegatron      | 2AB5                        | [5e1831ce63](https://linux-hardware.org/?probe=5e1831ce63) | Oct 03, 2024 |
| ASUSTek       | 970 PRO GAMING/AURA         | [3c3570695d](https://linux-hardware.org/?probe=3c3570695d) | Oct 02, 2024 |
| Gigabyte      | AX370-Gaming K7             | [ddc95ea8b4](https://linux-hardware.org/?probe=ddc95ea8b4) | Oct 01, 2024 |
| ASRock        | H410M-HDV                   | [e8a196d76d](https://linux-hardware.org/?probe=e8a196d76d) | Oct 01, 2024 |
| ASUSTek       | P6TD DELUXE                 | [b0b13c581e](https://linux-hardware.org/?probe=b0b13c581e) | Sep 30, 2024 |
| Pegatron      | 2AB6                        | [621eefa747](https://linux-hardware.org/?probe=621eefa747) | Sep 26, 2024 |
| Gigabyte      | 970A-DS3P                   | [b5cff39380](https://linux-hardware.org/?probe=b5cff39380) | Sep 23, 2024 |
| HP            | 843C                        | [1192869981](https://linux-hardware.org/?probe=1192869981) | Sep 21, 2024 |
| ASUSTek       | Z170-PRO                    | [c2c30664b7](https://linux-hardware.org/?probe=c2c30664b7) | Sep 21, 2024 |
| MSI           | X470 GAMING PRO CARBON      | [b48e7ccff0](https://linux-hardware.org/?probe=b48e7ccff0) | Sep 15, 2024 |
| Fujitsu       | D3401-B2 S26361-D3401-B2    | [ecc2fc4b42](https://linux-hardware.org/?probe=ecc2fc4b42) | Sep 11, 2024 |
| Gigabyte      | 970-GAMING                  | [e06391b86d](https://linux-hardware.org/?probe=e06391b86d) | Sep 10, 2024 |
| HP            | 1825                        | [dad25ef0f2](https://linux-hardware.org/?probe=dad25ef0f2) | Sep 09, 2024 |
| ASUSTek       | 970 PRO GAMING/AURA         | [db3ce60da0](https://linux-hardware.org/?probe=db3ce60da0) | Sep 02, 2024 |
| Gigabyte      | B550M AORUS ELITE           | [8b0e9e2cb3](https://linux-hardware.org/?probe=8b0e9e2cb3) | Sep 02, 2024 |
| Gigabyte      | AX370-Gaming K7             | [f4ecd68705](https://linux-hardware.org/?probe=f4ecd68705) | Sep 01, 2024 |
| MSI           | X470 GAMING PRO CARBON      | [249520907c](https://linux-hardware.org/?probe=249520907c) | Sep 01, 2024 |
| ASUSTek       | Z170-PRO                    | [1df85adc47](https://linux-hardware.org/?probe=1df85adc47) | Aug 27, 2024 |
| Fujitsu       | D3401-B2 S26361-D3401-B2    | [4a901b8c0b](https://linux-hardware.org/?probe=4a901b8c0b) | Aug 27, 2024 |
| MSI           | X370 GAMING PRO CARBON      | [c8e6b2f118](https://linux-hardware.org/?probe=c8e6b2f118) | Aug 26, 2024 |
| Gigabyte      | P55-UD3                     | [cf0af05881](https://linux-hardware.org/?probe=cf0af05881) | Aug 26, 2024 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [7496218099](https://linux-hardware.org/?probe=7496218099) | Aug 21, 2024 |
| MSI           | X470 GAMING PRO CARBON      | [82e70084ce](https://linux-hardware.org/?probe=82e70084ce) | Aug 16, 2024 |
| Gigabyte      | Z490 AORUS ELITE AC         | [c6e46b55fe](https://linux-hardware.org/?probe=c6e46b55fe) | Aug 14, 2024 |
| ASUSTek       | Maximus VII HERO            | [5c94a6c420](https://linux-hardware.org/?probe=5c94a6c420) | Aug 10, 2024 |
| HP            | 3397                        | [27aae09898](https://linux-hardware.org/?probe=27aae09898) | Aug 10, 2024 |
| Biostar       | G31D-M7                     | [b67c1be009](https://linux-hardware.org/?probe=b67c1be009) | Aug 07, 2024 |
| MSI           | MAG X570S TORPEDO MAX       | [bed88d1de4](https://linux-hardware.org/?probe=bed88d1de4) | Aug 04, 2024 |
| ASRock        | Z270 Pro4                   | [5536db56f1](https://linux-hardware.org/?probe=5536db56f1) | Aug 04, 2024 |
| MSI           | X470 GAMING PRO CARBON      | [66634e8715](https://linux-hardware.org/?probe=66634e8715) | Aug 03, 2024 |
| Gigabyte      | AX370-Gaming K7             | [6ca3d35800](https://linux-hardware.org/?probe=6ca3d35800) | Aug 01, 2024 |
| MSI           | X470 GAMING PRO CARBON      | [91ac23bd2e](https://linux-hardware.org/?probe=91ac23bd2e) | Aug 01, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [de1bd8e3cb](https://linux-hardware.org/?probe=de1bd8e3cb) | Jul 30, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [1333a1a8dd](https://linux-hardware.org/?probe=1333a1a8dd) | Jul 30, 2024 |
| MACHINIST     | E5-MR9A V1.0                | [77788e715d](https://linux-hardware.org/?probe=77788e715d) | Jul 29, 2024 |
| ASUSTek       | P5KPL-CM                    | [30546cb187](https://linux-hardware.org/?probe=30546cb187) | Jul 29, 2024 |
| ASUSTek       | PRIME X299-A                | [860a944117](https://linux-hardware.org/?probe=860a944117) | Jul 26, 2024 |
| ASUSTek       | P8H67-M LE                  | [0e270eee51](https://linux-hardware.org/?probe=0e270eee51) | Jul 25, 2024 |
| Unknown       | Unknown                     | [dbab5a12cb](https://linux-hardware.org/?probe=dbab5a12cb) | Jul 23, 2024 |
| ASUSTek       | P6T DELUXE V2               | [c4168d8fdb](https://linux-hardware.org/?probe=c4168d8fdb) | Jul 20, 2024 |
| Fujitsu       | D3401-B2 S26361-D3401-B2    | [86dbf0c37d](https://linux-hardware.org/?probe=86dbf0c37d) | Jul 18, 2024 |
| ASRock        | B550M-ITX/ac                | [3f08512bd1](https://linux-hardware.org/?probe=3f08512bd1) | Jul 17, 2024 |
| ASUSTek       | SABERTOOTH 990FX            | [aff348b763](https://linux-hardware.org/?probe=aff348b763) | Jul 14, 2024 |
| ASUSTek       | B85M-E                      | [a8452650eb](https://linux-hardware.org/?probe=a8452650eb) | Jul 06, 2024 |
| MSI           | A520M-A PRO                 | [57d0db3642](https://linux-hardware.org/?probe=57d0db3642) | Jul 05, 2024 |
| MSI           | PRO Z690-A WIFI             | [82d11210a6](https://linux-hardware.org/?probe=82d11210a6) | Jul 04, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [d982fabc4a](https://linux-hardware.org/?probe=d982fabc4a) | Jul 04, 2024 |
| Gigabyte      | AX370-Gaming K7             | [0b2fed265f](https://linux-hardware.org/?probe=0b2fed265f) | Jul 01, 2024 |
| MSI           | X470 GAMING PRO CARBON      | [03349c5084](https://linux-hardware.org/?probe=03349c5084) | Jul 01, 2024 |
| ASRock        | Z790 Taichi Lite            | [ef95746d6e](https://linux-hardware.org/?probe=ef95746d6e) | Jul 01, 2024 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [67a596e66d](https://linux-hardware.org/?probe=67a596e66d) | Jun 29, 2024 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [6c5690edc3](https://linux-hardware.org/?probe=6c5690edc3) | Jun 29, 2024 |
| ASUSTek       | PRIME B450M-A II            | [10cc6e356c](https://linux-hardware.org/?probe=10cc6e356c) | Jun 28, 2024 |
| MSI           | Z590-A PRO                  | [c7af568c23](https://linux-hardware.org/?probe=c7af568c23) | Jun 28, 2024 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [bba470ebe1](https://linux-hardware.org/?probe=bba470ebe1) | Jun 27, 2024 |
| MSI           | MAG Z790 TOMAHAWK WIFI D... | [ac4cddaec8](https://linux-hardware.org/?probe=ac4cddaec8) | Jun 22, 2024 |
| Dell          | 0T1D10 A01                  | [5293cefaef](https://linux-hardware.org/?probe=5293cefaef) | Jun 18, 2024 |
| ASUSTek       | PRIME H510M-A               | [ec21967f0a](https://linux-hardware.org/?probe=ec21967f0a) | Jun 14, 2024 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [8ed7d5ad10](https://linux-hardware.org/?probe=8ed7d5ad10) | Jun 10, 2024 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [593dc0e739](https://linux-hardware.org/?probe=593dc0e739) | Jun 10, 2024 |
| ASUSTek       | M4N68T-M LE                 | [196e8db012](https://linux-hardware.org/?probe=196e8db012) | Jun 10, 2024 |
| ASRock        | Z690M-ITX/ax                | [140a4d343a](https://linux-hardware.org/?probe=140a4d343a) | Jun 09, 2024 |
| MSI           | MPG Z390 GAMING PLUS        | [9694df133d](https://linux-hardware.org/?probe=9694df133d) | Jun 09, 2024 |
| Gigabyte      | A320M-H-CF                  | [c6cfa28e4c](https://linux-hardware.org/?probe=c6cfa28e4c) | Jun 08, 2024 |
| Gigabyte      | F2A55M-S1                   | [a276ceeae9](https://linux-hardware.org/?probe=a276ceeae9) | Jun 07, 2024 |
| ASUSTek       | PRIME X370-PRO              | [a45e1b649c](https://linux-hardware.org/?probe=a45e1b649c) | Jun 06, 2024 |
| HP            | 2AA7 H                      | [3f761cfc1d](https://linux-hardware.org/?probe=3f761cfc1d) | Jun 04, 2024 |
| ASUSTek       | P5Q                         | [b03f355816](https://linux-hardware.org/?probe=b03f355816) | Jun 02, 2024 |
| Gigabyte      | H81M-DS2                    | [643f4990ff](https://linux-hardware.org/?probe=643f4990ff) | Jun 02, 2024 |
| ASUSTek       | PRIME B450M-A II            | [1b0fc3bc58](https://linux-hardware.org/?probe=1b0fc3bc58) | Jun 02, 2024 |
| Gigabyte      | AX370-Gaming K7             | [358c7b7d8f](https://linux-hardware.org/?probe=358c7b7d8f) | Jun 01, 2024 |
| HP            | 2AA7 H                      | [5696d0e2fb](https://linux-hardware.org/?probe=5696d0e2fb) | May 31, 2024 |
| HP            | 2ADC                        | [66f5e8294a](https://linux-hardware.org/?probe=66f5e8294a) | May 21, 2024 |
| HP            | 8768 A                      | [906ad85020](https://linux-hardware.org/?probe=906ad85020) | May 19, 2024 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [cd3ef6ca70](https://linux-hardware.org/?probe=cd3ef6ca70) | May 17, 2024 |
| Gigabyte      | H110M-S2H-CF                | [f9618afb19](https://linux-hardware.org/?probe=f9618afb19) | May 16, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [ea49781cb7](https://linux-hardware.org/?probe=ea49781cb7) | May 15, 2024 |
| Dell          | 06JWJY A00                  | [5886801845](https://linux-hardware.org/?probe=5886801845) | May 14, 2024 |
| HP            | 8704                        | [dea17248ba](https://linux-hardware.org/?probe=dea17248ba) | May 13, 2024 |
| ASUSTek       | M5A97 LE R2.0               | [98aa0808c4](https://linux-hardware.org/?probe=98aa0808c4) | May 12, 2024 |
| MSI           | PRO Z790-P WIFI             | [787be7c93a](https://linux-hardware.org/?probe=787be7c93a) | May 12, 2024 |
| MSI           | X470 GAMING PRO CARBON      | [1cc56e9dae](https://linux-hardware.org/?probe=1cc56e9dae) | May 11, 2024 |
| ASUSTek       | PRIME B450M-K II            | [1118b63d68](https://linux-hardware.org/?probe=1118b63d68) | May 09, 2024 |
| Gigabyte      | Z270-HD3P-CF                | [b67da2effc](https://linux-hardware.org/?probe=b67da2effc) | May 08, 2024 |
| ASUSTek       | PRIME X370-PRO              | [54f40400ed](https://linux-hardware.org/?probe=54f40400ed) | May 08, 2024 |
| ASRock        | B450 Gaming-ITX/ac          | [9b4c39c111](https://linux-hardware.org/?probe=9b4c39c111) | May 07, 2024 |
| MSI           | MPG X570 GAMING PLUS        | [60ef8abb02](https://linux-hardware.org/?probe=60ef8abb02) | May 07, 2024 |
| ASUSTek       | P5Q                         | [5af3396f04](https://linux-hardware.org/?probe=5af3396f04) | May 05, 2024 |
| HP            | 8054                        | [bc7d8e8b56](https://linux-hardware.org/?probe=bc7d8e8b56) | May 04, 2024 |
| Dell          | 0D881F A05                  | [9dfc8fb5b7](https://linux-hardware.org/?probe=9dfc8fb5b7) | May 03, 2024 |
| Gigabyte      | AX370-Gaming K7             | [e759e41a51](https://linux-hardware.org/?probe=e759e41a51) | May 01, 2024 |
| MSI           | X470 GAMING PRO CARBON      | [6486b4f435](https://linux-hardware.org/?probe=6486b4f435) | May 01, 2024 |
| ASUSTek       | KGPE-D16                    | [f199ccf950](https://linux-hardware.org/?probe=f199ccf950) | Apr 30, 2024 |
| Dell          | 04GJJT A00                  | [b336911f53](https://linux-hardware.org/?probe=b336911f53) | Apr 28, 2024 |
| MSI           | Z790 GAMING PLUS WIFI       | [c1242570d2](https://linux-hardware.org/?probe=c1242570d2) | Apr 25, 2024 |
| Gigabyte      | B75M-D2V                    | [21c055a907](https://linux-hardware.org/?probe=21c055a907) | Apr 25, 2024 |
| Gigabyte      | B365 M AORUS ELITE-CF       | [e89543357b](https://linux-hardware.org/?probe=e89543357b) | Apr 25, 2024 |
| Gigabyte      | B365 M AORUS ELITE-CF       | [91dc4d43de](https://linux-hardware.org/?probe=91dc4d43de) | Apr 25, 2024 |
| ASUSTek       | P5K Premium                 | [9b09b4d8bd](https://linux-hardware.org/?probe=9b09b4d8bd) | Apr 24, 2024 |
| Gigabyte      | 970A-DS3P                   | [1cc02514fd](https://linux-hardware.org/?probe=1cc02514fd) | Apr 23, 2024 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [11d418a07c](https://linux-hardware.org/?probe=11d418a07c) | Apr 22, 2024 |
| Gigabyte      | H310M S2P                   | [80fc55e632](https://linux-hardware.org/?probe=80fc55e632) | Apr 22, 2024 |
| Dell          | 00V62H A01                  | [89c9b39716](https://linux-hardware.org/?probe=89c9b39716) | Apr 22, 2024 |
| Gigabyte      | Z77-D3H                     | [6808539c26](https://linux-hardware.org/?probe=6808539c26) | Apr 21, 2024 |
| Dell          | 0HD5W2 A01                  | [47d879fa41](https://linux-hardware.org/?probe=47d879fa41) | Apr 19, 2024 |
| Gigabyte      | H61MA-D3V                   | [ebc9dd41f4](https://linux-hardware.org/?probe=ebc9dd41f4) | Apr 19, 2024 |
| Dell          | 0HD5W2 A01                  | [6074f97307](https://linux-hardware.org/?probe=6074f97307) | Apr 18, 2024 |
| ASUSTek       | PRIME X299-DELUXE           | [6b14b793c5](https://linux-hardware.org/?probe=6b14b793c5) | Apr 17, 2024 |
| MSI           | X470 GAMING PRO CARBON      | [78cd7a86b3](https://linux-hardware.org/?probe=78cd7a86b3) | Apr 17, 2024 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | [2dc0b12567](https://linux-hardware.org/?probe=2dc0b12567) | Apr 16, 2024 |
| ASUSTek       | P6T SE                      | [31a598cb35](https://linux-hardware.org/?probe=31a598cb35) | Apr 16, 2024 |
| ASUSTek       | PRIME B650-PLUS             | [bca932a740](https://linux-hardware.org/?probe=bca932a740) | Apr 15, 2024 |
| MSI           | B450 GAMING PRO CARBON A... | [d2060f0dcd](https://linux-hardware.org/?probe=d2060f0dcd) | Apr 14, 2024 |
| AMI           | Intel                       | [d8aa9b61b5](https://linux-hardware.org/?probe=d8aa9b61b5) | Apr 14, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [2b471c5586](https://linux-hardware.org/?probe=2b471c5586) | Apr 14, 2024 |
| Intel         | B250                        | [197e339bcf](https://linux-hardware.org/?probe=197e339bcf) | Apr 14, 2024 |
| MSI           | B450 GAMING PRO CARBON A... | [37733a1209](https://linux-hardware.org/?probe=37733a1209) | Apr 09, 2024 |
| Gigabyte      | A320M-DS2-CF                | [14aae5a31c](https://linux-hardware.org/?probe=14aae5a31c) | Apr 08, 2024 |
| Unknown       | Unknown                     | [edbaa46cbe](https://linux-hardware.org/?probe=edbaa46cbe) | Apr 05, 2024 |
| MSI           | MS-B9241                    | [f0b74d9e54](https://linux-hardware.org/?probe=f0b74d9e54) | Apr 05, 2024 |
| Gigabyte      | AX370-Gaming K7             | [bba7520a79](https://linux-hardware.org/?probe=bba7520a79) | Apr 01, 2024 |
| MSI           | X470 GAMING PRO CARBON      | [d82daf5b14](https://linux-hardware.org/?probe=d82daf5b14) | Apr 01, 2024 |
| Lenovo        | IdeaCentre K430             | [b72fcce004](https://linux-hardware.org/?probe=b72fcce004) | Mar 31, 2024 |
| Lenovo        | IdeaCentre K430             | [a2c9b21fb9](https://linux-hardware.org/?probe=a2c9b21fb9) | Mar 31, 2024 |
| MSI           | X370 GAMING PRO CARBON      | [84b0e3e2af](https://linux-hardware.org/?probe=84b0e3e2af) | Mar 31, 2024 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [175015e349](https://linux-hardware.org/?probe=175015e349) | Mar 30, 2024 |
| HP            | 1998                        | [4c2971ed76](https://linux-hardware.org/?probe=4c2971ed76) | Mar 27, 2024 |
| Gigabyte      | A520I AC                    | [baff8cb9b8](https://linux-hardware.org/?probe=baff8cb9b8) | Mar 25, 2024 |
| ASRock        | B450M Pro4                  | [2e8543e629](https://linux-hardware.org/?probe=2e8543e629) | Mar 25, 2024 |
| HP            | 1998                        | [d8865ee940](https://linux-hardware.org/?probe=d8865ee940) | Mar 24, 2024 |
| ASUSTek       | PRIME Z390-A                | [891d67a053](https://linux-hardware.org/?probe=891d67a053) | Mar 19, 2024 |
| Lenovo        | 102F                        | [e4e070f4df](https://linux-hardware.org/?probe=e4e070f4df) | Mar 19, 2024 |
| ASUSTek       | P8H61-M LE/USB3             | [d24e51a631](https://linux-hardware.org/?probe=d24e51a631) | Mar 17, 2024 |
| ASRock        | B550M-ITX/ac                | [cdcb2eddcf](https://linux-hardware.org/?probe=cdcb2eddcf) | Mar 15, 2024 |
| ASUSTek       | TUF Z270 MARK 1             | [bd35285f2c](https://linux-hardware.org/?probe=bd35285f2c) | Mar 14, 2024 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [56218fcc37](https://linux-hardware.org/?probe=56218fcc37) | Mar 13, 2024 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [9fd3e4a19d](https://linux-hardware.org/?probe=9fd3e4a19d) | Mar 13, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [c4fe7430eb](https://linux-hardware.org/?probe=c4fe7430eb) | Mar 13, 2024 |
| ASUSTek       | M5A97 LE R2.0               | [78ab08dee5](https://linux-hardware.org/?probe=78ab08dee5) | Mar 09, 2024 |
| HP            | 8704                        | [a9a02c9d98](https://linux-hardware.org/?probe=a9a02c9d98) | Mar 06, 2024 |
| MSI           | 970 GAMING                  | [7ec06861ba](https://linux-hardware.org/?probe=7ec06861ba) | Mar 05, 2024 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | [65080da98c](https://linux-hardware.org/?probe=65080da98c) | Mar 04, 2024 |
| Gigabyte      | AX370-Gaming K7             | [59d562ccb2](https://linux-hardware.org/?probe=59d562ccb2) | Mar 02, 2024 |
| MSI           | X470 GAMING PRO CARBON      | [b58bb65fff](https://linux-hardware.org/?probe=b58bb65fff) | Mar 01, 2024 |
| ASUSTek       | PRIME Z390-P                | [3022d85c07](https://linux-hardware.org/?probe=3022d85c07) | Feb 28, 2024 |
| Gigabyte      | A320M-S2H-CF                | [8f3bba3e55](https://linux-hardware.org/?probe=8f3bba3e55) | Feb 27, 2024 |
| Acer          | Veriton M4660G V:1.0        | [f4d17adcc4](https://linux-hardware.org/?probe=f4d17adcc4) | Feb 26, 2024 |
| ASUSTek       | P7P55-M                     | [3ea869d864](https://linux-hardware.org/?probe=3ea869d864) | Feb 24, 2024 |
| HP            | 1496                        | [1cc3bd19db](https://linux-hardware.org/?probe=1cc3bd19db) | Feb 23, 2024 |
| Gigabyte      | B760M DS3H                  | [7e6352f1af](https://linux-hardware.org/?probe=7e6352f1af) | Feb 23, 2024 |
| ASUSTek       | P8H61-M LE                  | [6511d32b6d](https://linux-hardware.org/?probe=6511d32b6d) | Feb 22, 2024 |
| Fujitsu       | D3602-A1 S26361-D3602-A1    | [daeb6385eb](https://linux-hardware.org/?probe=daeb6385eb) | Feb 22, 2024 |
| ASUSTek       | M5A97 LE R2.0               | [af9bba507c](https://linux-hardware.org/?probe=af9bba507c) | Feb 22, 2024 |
| ASRock        | B450M Pro4                  | [6ca9a09551](https://linux-hardware.org/?probe=6ca9a09551) | Feb 21, 2024 |
| Gigabyte      | B650M DS3H                  | [91f2211c0c](https://linux-hardware.org/?probe=91f2211c0c) | Feb 14, 2024 |
| ASUSTek       | P5LD2-TVM-SE-SI             | [d0a9f3664e](https://linux-hardware.org/?probe=d0a9f3664e) | Feb 13, 2024 |
| Gigabyte      | A320M-S2H-CF                | [c5a7934836](https://linux-hardware.org/?probe=c5a7934836) | Feb 13, 2024 |
| ASUSTek       | H61M-A/BR                   | [6a09917f6f](https://linux-hardware.org/?probe=6a09917f6f) | Feb 13, 2024 |
| HP            | 843B                        | [aa6fd9964e](https://linux-hardware.org/?probe=aa6fd9964e) | Feb 13, 2024 |
| Gigabyte      | F2A68HM-H                   | [f8f33cacdf](https://linux-hardware.org/?probe=f8f33cacdf) | Feb 13, 2024 |
| Gigabyte      | A320M-S2H-CF                | [25f4ea22cd](https://linux-hardware.org/?probe=25f4ea22cd) | Feb 12, 2024 |
| Gigabyte      | B460 AORUS PRO AC           | [00a2a68eef](https://linux-hardware.org/?probe=00a2a68eef) | Feb 12, 2024 |
| AMD           | 990FXA-UD3                  | [a8866aee9c](https://linux-hardware.org/?probe=a8866aee9c) | Feb 12, 2024 |
| MSI           | Z270 GAMING PLUS            | [d232086b57](https://linux-hardware.org/?probe=d232086b57) | Feb 11, 2024 |
| Intel         | DQ57TM AAE70931-402         | [1c8831a84d](https://linux-hardware.org/?probe=1c8831a84d) | Feb 11, 2024 |
| Unknown       | Unknown                     | [0a197d31ec](https://linux-hardware.org/?probe=0a197d31ec) | Feb 10, 2024 |
| HP            | 1998                        | [de3c15346c](https://linux-hardware.org/?probe=de3c15346c) | Feb 10, 2024 |
| AAEON         | S500 V1.0                   | [e4d8723e6f](https://linux-hardware.org/?probe=e4d8723e6f) | Feb 09, 2024 |
| ASUSTek       | P5LD2-TVM-SE-SI             | [df029c3635](https://linux-hardware.org/?probe=df029c3635) | Feb 07, 2024 |
| MSI           | B550M PRO-VDH WIFI          | [85c4dfa0f4](https://linux-hardware.org/?probe=85c4dfa0f4) | Feb 07, 2024 |
| MSI           | X470 GAMING PRO CARBON      | [429b3c3517](https://linux-hardware.org/?probe=429b3c3517) | Feb 05, 2024 |
| ASUSTek       | PRIME X370-PRO              | [4b6f872d8b](https://linux-hardware.org/?probe=4b6f872d8b) | Feb 05, 2024 |
| HP            | 1998                        | [5e85b19897](https://linux-hardware.org/?probe=5e85b19897) | Feb 05, 2024 |
| HP            | 89D8 SMVB                   | [732db9f3b4](https://linux-hardware.org/?probe=732db9f3b4) | Feb 04, 2024 |
| Shenzhen M... | F6BFC                       | [489a0859f2](https://linux-hardware.org/?probe=489a0859f2) | Feb 03, 2024 |
| Biostar       | G41-M7                      | [eea33a47ac](https://linux-hardware.org/?probe=eea33a47ac) | Feb 03, 2024 |
| ASUSTek       | PRIME X370-PRO              | [58d150eef2](https://linux-hardware.org/?probe=58d150eef2) | Feb 02, 2024 |
| ASUSTek       | P5Q                         | [63522c9a09](https://linux-hardware.org/?probe=63522c9a09) | Feb 02, 2024 |
| Gigabyte      | AX370-Gaming K7             | [c2514048e9](https://linux-hardware.org/?probe=c2514048e9) | Feb 02, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [8e3680cd5d](https://linux-hardware.org/?probe=8e3680cd5d) | Feb 01, 2024 |
| MSI           | X470 GAMING PRO CARBON      | [9d2088ace3](https://linux-hardware.org/?probe=9d2088ace3) | Feb 01, 2024 |
| ASUSTek       | SABERTOOTH 990FX            | [a477ec4fe1](https://linux-hardware.org/?probe=a477ec4fe1) | Jan 31, 2024 |
| MSI           | PRO B660M-A WIFI DDR4       | [aabd02c85c](https://linux-hardware.org/?probe=aabd02c85c) | Jan 30, 2024 |
| Gigabyte      | X570 AORUS ULTRA            | [c823432a5a](https://linux-hardware.org/?probe=c823432a5a) | Jan 30, 2024 |
| Acer          | Veriton X6630G              | [66d62ae7ed](https://linux-hardware.org/?probe=66d62ae7ed) | Jan 29, 2024 |
| Acer          | Veriton X6630G              | [9684aca764](https://linux-hardware.org/?probe=9684aca764) | Jan 29, 2024 |
| ASRock        | B450M Pro4                  | [23faf0c03e](https://linux-hardware.org/?probe=23faf0c03e) | Jan 25, 2024 |
| AZW           | Gemini T45                  | [5a3dba74d6](https://linux-hardware.org/?probe=5a3dba74d6) | Jan 24, 2024 |
| AZW           | Gemini T45                  | [a0e1db7908](https://linux-hardware.org/?probe=a0e1db7908) | Jan 24, 2024 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [7c94952653](https://linux-hardware.org/?probe=7c94952653) | Jan 23, 2024 |
| Gigabyte      | Z97-HD3                     | [e568089bad](https://linux-hardware.org/?probe=e568089bad) | Jan 21, 2024 |
| MSI           | MPG Z390 GAMING PLUS        | [494d0af2e5](https://linux-hardware.org/?probe=494d0af2e5) | Jan 19, 2024 |
| Great Wall    | MBX-Z60AR110 TBD            | [fdfa81d344](https://linux-hardware.org/?probe=fdfa81d344) | Jan 18, 2024 |
| Medion        | H110H4-EM                   | [ea736cf314](https://linux-hardware.org/?probe=ea736cf314) | Jan 17, 2024 |
| ASUSTek       | PRIME H410M-A               | [0d81012aa0](https://linux-hardware.org/?probe=0d81012aa0) | Jan 16, 2024 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [c69281db28](https://linux-hardware.org/?probe=c69281db28) | Jan 15, 2024 |
| MSI           | X470 GAMING PRO CARBON      | [cdfc29ad66](https://linux-hardware.org/?probe=cdfc29ad66) | Jan 15, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [398927cd45](https://linux-hardware.org/?probe=398927cd45) | Jan 13, 2024 |
| Unknown       | Unknown                     | [25341b5586](https://linux-hardware.org/?probe=25341b5586) | Jan 13, 2024 |
| MSI           | H410M PRO                   | [76a24b5fa3](https://linux-hardware.org/?probe=76a24b5fa3) | Jan 12, 2024 |
| ASUSTek       | PRIME A320M-K               | [bddc683db5](https://linux-hardware.org/?probe=bddc683db5) | Jan 12, 2024 |
| MSI           | Z370 GAMING PLUS            | [a188d14c50](https://linux-hardware.org/?probe=a188d14c50) | Jan 11, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f1814dff2e](https://linux-hardware.org/?probe=f1814dff2e) | Jan 11, 2024 |
| HP            | 8767 A                      | [88f6719b01](https://linux-hardware.org/?probe=88f6719b01) | Jan 10, 2024 |
| ASUSTek       | H81T R2.0                   | [23cc8eb053](https://linux-hardware.org/?probe=23cc8eb053) | Jan 10, 2024 |
| Dell          | 0HD5W2 A01                  | [7194fe43ed](https://linux-hardware.org/?probe=7194fe43ed) | Jan 09, 2024 |
| Gigabyte      | H67A-UD3H-B3                | [f43717fa8e](https://linux-hardware.org/?probe=f43717fa8e) | Jan 08, 2024 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [ee9fb5898f](https://linux-hardware.org/?probe=ee9fb5898f) | Jan 07, 2024 |
| HP            | 3397                        | [0ba7322ded](https://linux-hardware.org/?probe=0ba7322ded) | Jan 05, 2024 |
| MSI           | MPG Z390 GAMING PLUS        | [5feecec8b2](https://linux-hardware.org/?probe=5feecec8b2) | Jan 05, 2024 |
| Biostar       | B365MHC                     | [0936a451ce](https://linux-hardware.org/?probe=0936a451ce) | Jan 04, 2024 |
| ASUSTek       | PRIME A320M-K               | [cf07066830](https://linux-hardware.org/?probe=cf07066830) | Jan 03, 2024 |
| Gigabyte      | AX370-Gaming K7             | [435dc251c1](https://linux-hardware.org/?probe=435dc251c1) | Jan 02, 2024 |
| MSI           | 2AE0                        | [00b5d15112](https://linux-hardware.org/?probe=00b5d15112) | Jan 01, 2024 |
| MSI           | X470 GAMING PRO CARBON      | [8a1771af4b](https://linux-hardware.org/?probe=8a1771af4b) | Jan 01, 2024 |
| Toshiba       | STI 013442                  | [c8488906f2](https://linux-hardware.org/?probe=c8488906f2) | Dec 31, 2023 |
| Toshiba       | STI 013442                  | [ed56d2dcb5](https://linux-hardware.org/?probe=ed56d2dcb5) | Dec 31, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [3700165122](https://linux-hardware.org/?probe=3700165122) | Dec 28, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [c68ea76b65](https://linux-hardware.org/?probe=c68ea76b65) | Dec 28, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [48d04b219b](https://linux-hardware.org/?probe=48d04b219b) | Dec 28, 2023 |
| Foxconn       | 2AB7                        | [2d0962bbfa](https://linux-hardware.org/?probe=2d0962bbfa) | Dec 27, 2023 |
| Foxconn       | 2AB7                        | [b1b00dd0b5](https://linux-hardware.org/?probe=b1b00dd0b5) | Dec 27, 2023 |
| Dell          | 0F6X5P A00                  | [8b6cbdd646](https://linux-hardware.org/?probe=8b6cbdd646) | Dec 24, 2023 |
| Dell          | 0F6X5P A00                  | [fb2877e727](https://linux-hardware.org/?probe=fb2877e727) | Dec 21, 2023 |
| MSI           | H97M-P35                    | [759943cd15](https://linux-hardware.org/?probe=759943cd15) | Dec 19, 2023 |
| HP            | 81B3                        | [86d9fc12a5](https://linux-hardware.org/?probe=86d9fc12a5) | Dec 19, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | [d56dcc35b9](https://linux-hardware.org/?probe=d56dcc35b9) | Dec 18, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [6115b25184](https://linux-hardware.org/?probe=6115b25184) | Dec 18, 2023 |
| Gigabyte      | 970-GAMING                  | [f1f6a55f9c](https://linux-hardware.org/?probe=f1f6a55f9c) | Dec 16, 2023 |
| Gigabyte      | 970-GAMING                  | [8b6e7627f9](https://linux-hardware.org/?probe=8b6e7627f9) | Dec 16, 2023 |
| MSI           | Z370 GAMING PLUS            | [57cc6cbccf](https://linux-hardware.org/?probe=57cc6cbccf) | Dec 14, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [22dfb202b4](https://linux-hardware.org/?probe=22dfb202b4) | Dec 12, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [281cfa9ff7](https://linux-hardware.org/?probe=281cfa9ff7) | Dec 11, 2023 |
| Gigabyte      | P55-UD3                     | [4c20f6a826](https://linux-hardware.org/?probe=4c20f6a826) | Dec 10, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [3a6b7f5ae4](https://linux-hardware.org/?probe=3a6b7f5ae4) | Dec 09, 2023 |
| ASUSTek       | PRIME A320M-K               | [e90c011500](https://linux-hardware.org/?probe=e90c011500) | Dec 05, 2023 |
| Gigabyte      | F2A68HM-H                   | [57a63775b2](https://linux-hardware.org/?probe=57a63775b2) | Dec 05, 2023 |
| ASUSTek       | H81M-K                      | [8fd5e3b166](https://linux-hardware.org/?probe=8fd5e3b166) | Dec 04, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [abb3c226ed](https://linux-hardware.org/?probe=abb3c226ed) | Dec 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | [ff37eb859a](https://linux-hardware.org/?probe=ff37eb859a) | Dec 02, 2023 |
| ASUSTek       | M4A88TD-M EVO               | [7f6b5fd810](https://linux-hardware.org/?probe=7f6b5fd810) | Dec 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [88bd7270db](https://linux-hardware.org/?probe=88bd7270db) | Dec 01, 2023 |
| Lenovo        | SHARKBAY NOK                | [be4ecb6dfa](https://linux-hardware.org/?probe=be4ecb6dfa) | Nov 29, 2023 |
| ASUSTek       | P7P55D-E PRO                | [6fe23dd80e](https://linux-hardware.org/?probe=6fe23dd80e) | Nov 28, 2023 |
| ASUSTek       | Z170-A                      | [e38428746a](https://linux-hardware.org/?probe=e38428746a) | Nov 27, 2023 |
| ASUSTek       | M5A97 R2.0                  | [4b4737d484](https://linux-hardware.org/?probe=4b4737d484) | Nov 27, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [c166853e23](https://linux-hardware.org/?probe=c166853e23) | Nov 26, 2023 |
| ASUSTek       | ROG STRIX B460-I GAMING     | [7a0adaf9f3](https://linux-hardware.org/?probe=7a0adaf9f3) | Nov 25, 2023 |
| ASUSTek       | ROG STRIX B460-I GAMING     | [b96e460a4f](https://linux-hardware.org/?probe=b96e460a4f) | Nov 25, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [48112cbfe0](https://linux-hardware.org/?probe=48112cbfe0) | Nov 24, 2023 |
| BESSTAR Te... | TH50                        | [39c4acf035](https://linux-hardware.org/?probe=39c4acf035) | Nov 22, 2023 |
| Lenovo        | ThinkCentre M91p 4518A31    | [9031421465](https://linux-hardware.org/?probe=9031421465) | Nov 22, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [195e3a2ce6](https://linux-hardware.org/?probe=195e3a2ce6) | Nov 22, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | [cd86a8c45b](https://linux-hardware.org/?probe=cd86a8c45b) | Nov 22, 2023 |
| HP            | 2AA7 H                      | [c98041f477](https://linux-hardware.org/?probe=c98041f477) | Nov 21, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [6066ce2199](https://linux-hardware.org/?probe=6066ce2199) | Nov 20, 2023 |
| Dell          | 0YJPT1 A00                  | [7728c1ff4c](https://linux-hardware.org/?probe=7728c1ff4c) | Nov 20, 2023 |
| Dell          | 02M8NY A00                  | [dd2bdfb403](https://linux-hardware.org/?probe=dd2bdfb403) | Nov 20, 2023 |
| ASUSTek       | P8Z77-V LK                  | [883da32584](https://linux-hardware.org/?probe=883da32584) | Nov 18, 2023 |
| Gigabyte      | X570 UD                     | [2902bc3e9f](https://linux-hardware.org/?probe=2902bc3e9f) | Nov 15, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [0874caf8a9](https://linux-hardware.org/?probe=0874caf8a9) | Nov 13, 2023 |
| ASRock        | B760M Steel Legend WiFi     | [8fd2ed0ba7](https://linux-hardware.org/?probe=8fd2ed0ba7) | Nov 13, 2023 |
| Dell          | 0WN7Y6 A01                  | [85e2b37a15](https://linux-hardware.org/?probe=85e2b37a15) | Nov 10, 2023 |
| Dell          | 0D881F A05                  | [9b3ffcb3d5](https://linux-hardware.org/?probe=9b3ffcb3d5) | Nov 07, 2023 |
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


| Version            | Desktops | Percent |
|--------------------|----------|---------|
| 5.15.0-56-generic  | 21       | 3.12%   |
| 5.15.0-52-generic  | 19       | 2.82%   |
| 5.15.0-43-generic  | 19       | 2.82%   |
| 5.15.0-91-generic  | 17       | 2.53%   |
| 5.15.0-107-generic | 15       | 2.23%   |
| 5.15.0-48-generic  | 14       | 2.08%   |
| 6.5.0-28-generic   | 13       | 1.93%   |
| 5.15.0-67-generic  | 13       | 1.93%   |
| 5.15.0-46-generic  | 13       | 1.93%   |
| 5.19.0-35-generic  | 12       | 1.78%   |
| 5.15.0-75-generic  | 12       | 1.78%   |
| 5.15.0-47-generic  | 12       | 1.78%   |
| 5.15.0-27-generic  | 12       | 1.78%   |
| 6.2.0-26-generic   | 11       | 1.63%   |
| 5.15.0-58-generic  | 11       | 1.63%   |
| 5.15.0-40-generic  | 11       | 1.63%   |
| 6.5.0-15-generic   | 10       | 1.49%   |
| 5.15.0-41-generic  | 10       | 1.49%   |
| 5.19.0-38-generic  | 9        | 1.34%   |
| 5.15.0-94-generic  | 9        | 1.34%   |
| 5.15.0-69-generic  | 9        | 1.34%   |
| 5.15.0-53-generic  | 9        | 1.34%   |
| 5.15.0-25-generic  | 9        | 1.34%   |
| 6.2.0-39-generic   | 8        | 1.19%   |
| 6.2.0-37-generic   | 8        | 1.19%   |
| 5.15.0-78-generic  | 8        | 1.19%   |
| 5.15.0-73-generic  | 8        | 1.19%   |
| 5.15.0-60-generic  | 8        | 1.19%   |
| 5.15.0-50-generic  | 8        | 1.19%   |
| 5.19.0-46-generic  | 7        | 1.04%   |
| 5.19.0-41-generic  | 7        | 1.04%   |
| 5.15.0-88-generic  | 7        | 1.04%   |
| 5.15.0-79-generic  | 7        | 1.04%   |
| 6.8.0-45-generic   | 6        | 0.89%   |
| 6.8.0-40-generic   | 6        | 0.89%   |
| 6.5.0-35-generic   | 6        | 0.89%   |
| 6.5.0-26-generic   | 6        | 0.89%   |
| 6.2.0-36-generic   | 6        | 0.89%   |
| 6.2.0-35-generic   | 6        | 0.89%   |
| 5.15.0-86-generic  | 6        | 0.89%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 373      | 62.17%  |
| 6.5.0   | 68       | 11.33%  |
| 5.19.0  | 55       | 9.17%   |
| 6.2.0   | 54       | 9%      |
| 6.8.0   | 14       | 2.33%   |
| 5.17.0  | 4        | 0.67%   |
| 6.1.5   | 2        | 0.33%   |
| 5.18.4  | 2        | 0.33%   |
| 5.13.0  | 2        | 0.33%   |
| 6.9.7   | 1        | 0.17%   |
| 6.8.1   | 1        | 0.17%   |
| 6.7.11  | 1        | 0.17%   |
| 6.5.5   | 1        | 0.17%   |
| 6.5.3   | 1        | 0.17%   |
| 6.5.10  | 1        | 0.17%   |
| 6.4.3   | 1        | 0.17%   |
| 6.4.10  | 1        | 0.17%   |
| 6.4.0   | 1        | 0.17%   |
| 6.3.8   | 1        | 0.17%   |
| 6.3.6   | 1        | 0.17%   |
| 6.1.58  | 1        | 0.17%   |
| 6.1.1   | 1        | 0.17%   |
| 6.0.1   | 1        | 0.17%   |
| 6.0.0   | 1        | 0.17%   |
| 5.4.0   | 1        | 0.17%   |
| 5.19.17 | 1        | 0.17%   |
| 5.19.12 | 1        | 0.17%   |
| 5.18.19 | 1        | 0.17%   |
| 5.18.12 | 1        | 0.17%   |
| 5.18.10 | 1        | 0.17%   |
| 5.18.0  | 1        | 0.17%   |
| 5.17.6  | 1        | 0.17%   |
| 5.17.14 | 1        | 0.17%   |
| 5.16.0  | 1        | 0.17%   |
| 5.15.13 | 1        | 0.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 374      | 62.33%  |
| 6.5     | 71       | 11.83%  |
| 5.19    | 57       | 9.5%    |
| 6.2     | 54       | 9%      |
| 6.8     | 15       | 2.5%    |
| 5.18    | 6        | 1%      |
| 5.17    | 6        | 1%      |
| 6.1     | 4        | 0.67%   |
| 6.4     | 3        | 0.5%    |
| 6.3     | 2        | 0.33%   |
| 6.0     | 2        | 0.33%   |
| 5.13    | 2        | 0.33%   |
| 6.9     | 1        | 0.17%   |
| 6.7     | 1        | 0.17%   |
| 5.4     | 1        | 0.17%   |
| 5.16    | 1        | 0.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 576      | 99.83%  |
| riscv64 | 1        | 0.17%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| KDE5       | 568      | 98.44%  |
| KDE        | 3        | 0.52%   |
| GNOME      | 3        | 0.52%   |
| XFCE       | 1        | 0.17%   |
| X-Cinnamon | 1        | 0.17%   |
| Budgie     | 1        | 0.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 547      | 94.8%   |
| Tty     | 17       | 2.95%   |
| Wayland | 12       | 2.08%   |
| Web     | 1        | 0.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 378      | 64.84%  |
| Unknown | 153      | 26.24%  |
| GDM3    | 34       | 5.83%   |
| LightDM | 17       | 2.92%   |
| GDM     | 1        | 0.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang                 | Desktops | Percent |
|----------------------|----------|---------|
| en_US                | 252      | 43.67%  |
| de_DE                | 56       | 9.71%   |
| fr_FR                | 44       | 7.63%   |
| it_IT                | 25       | 4.33%   |
| en_GB                | 24       | 4.16%   |
| ru_RU                | 22       | 3.81%   |
| pt_BR                | 21       | 3.64%   |
| en_AU                | 16       | 2.77%   |
| es_ES                | 15       | 2.6%    |
| pl_PL                | 10       | 1.73%   |
| en_CA                | 9        | 1.56%   |
| nl_NL                | 7        | 1.21%   |
| es_AR                | 6        | 1.04%   |
| cs_CZ                | 6        | 1.04%   |
| de_AT                | 5        | 0.87%   |
| C                    | 5        | 0.87%   |
| el_GR                | 4        | 0.69%   |
| de_CH                | 4        | 0.69%   |
| nl_BE                | 3        | 0.52%   |
| en_ZA                | 3        | 0.52%   |
| en_PH                | 3        | 0.52%   |
| en_IN                | 3        | 0.52%   |
| zh_CN                | 2        | 0.35%   |
| fi_FI                | 2        | 0.35%   |
| es_VE                | 2        | 0.35%   |
| es_CO                | 2        | 0.35%   |
| en_NZ                | 2        | 0.35%   |
| en_AG                | 2        | 0.35%   |
| الافتراضيّ | 1        | 0.17%   |
| sl_SI                | 1        | 0.17%   |
| sk_SK                | 1        | 0.17%   |
| pt_PT                | 1        | 0.17%   |
| osa_US               | 1        | 0.17%   |
| ja_JP                | 1        | 0.17%   |
| hu_HU                | 1        | 0.17%   |
| fr_CA                | 1        | 0.17%   |
| fr_BE                | 1        | 0.17%   |
| es_PE                | 1        | 0.17%   |
| es_PA                | 1        | 0.17%   |
| es_MX                | 1        | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 351      | 60.31%  |
| EFI  | 231      | 39.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 462      | 78.84%  |
| Tmpfs   | 76       | 12.97%  |
| Btrfs   | 25       | 4.27%   |
| Overlay | 14       | 2.39%   |
| Xfs     | 6        | 1.02%   |
| Zfs     | 1        | 0.17%   |
| Ext3    | 1        | 0.17%   |
| Ext2    | 1        | 0.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 344      | 58.6%   |
| Unknown | 182      | 31.01%  |
| MBR     | 61       | 10.39%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 484      | 82.88%  |
| Yes       | 100      | 17.12%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 366      | 62.99%  |
| Yes       | 215      | 37.01%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 175      | 30.33%  |
| Gigabyte Technology                  | 103      | 17.85%  |
| MSI                                  | 83       | 14.38%  |
| ASRock                               | 46       | 7.97%   |
| Hewlett-Packard                      | 36       | 6.24%   |
| Dell                                 | 32       | 5.55%   |
| Lenovo                               | 22       | 3.81%   |
| Acer                                 | 9        | 1.56%   |
| Fujitsu                              | 8        | 1.39%   |
| Unknown                              | 7        | 1.21%   |
| Supermicro                           | 6        | 1.04%   |
| Biostar                              | 6        | 1.04%   |
| Intel                                | 5        | 0.87%   |
| AZW                                  | 4        | 0.69%   |
| Pegatron                             | 3        | 0.52%   |
| Foxconn                              | 3        | 0.52%   |
| Apple                                | 3        | 0.52%   |
| Alienware                            | 3        | 0.52%   |
| Shuttle                              | 2        | 0.35%   |
| Shenzhen Meigao Electronic Equipment | 2        | 0.35%   |
| Positivo                             | 2        | 0.35%   |
| Medion                               | 2        | 0.35%   |
| BESSTAR Tech                         | 2        | 0.35%   |
| SYWZ                                 | 1        | 0.17%   |
| Semp Toshiba                         | 1        | 0.17%   |
| Seeed Studio                         | 1        | 0.17%   |
| OEM                                  | 1        | 0.17%   |
| MACHINIST                            | 1        | 0.17%   |
| JWIPC                                | 1        | 0.17%   |
| Huanan                               | 1        | 0.17%   |
| Great Wall                           | 1        | 0.17%   |
| ECS                                  | 1        | 0.17%   |
| ASRockRack                           | 1        | 0.17%   |
| AMD                                  | 1        | 0.17%   |
| ABIT                                 | 1        | 0.17%   |
| AAEON                                | 1        | 0.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS All Series              | 21       | 3.64%   |
| Unknown                      | 7        | 1.21%   |
| ASUS ROG STRIX B550-F GAMING | 6        | 1.04%   |
| MSI MS-7B79                  | 5        | 0.87%   |
| ASUS PRIME X370-PRO          | 5        | 0.87%   |
| MSI MS-7B51                  | 4        | 0.69%   |
| HP Compaq Elite 8300 SFF     | 4        | 0.69%   |
| ASUS P5Q                     | 4        | 0.69%   |
| ASRock B450M Pro4            | 4        | 0.69%   |
| MSI MS-7D91                  | 3        | 0.52%   |
| MSI MS-7C95                  | 3        | 0.52%   |
| MSI MS-7B86                  | 3        | 0.52%   |
| MSI MS-7A32                  | 3        | 0.52%   |
| HP EliteDesk 800 G1 SFF      | 3        | 0.52%   |
| Gigabyte B450M DS3H          | 3        | 0.52%   |
| Dell OptiPlex 7040           | 3        | 0.52%   |
| Dell OptiPlex 7010           | 3        | 0.52%   |
| ASUS TUF Gaming B550M-PLUS   | 3        | 0.52%   |
| ASUS ROG STRIX Z390-E GAMING | 3        | 0.52%   |
| ASUS ROG STRIX X570-E GAMING | 3        | 0.52%   |
| ASUS ROG CROSSHAIR VII HERO  | 3        | 0.52%   |
| Supermicro SKAGIT09          | 2        | 0.35%   |
| MSI MS-7E06                  | 2        | 0.35%   |
| MSI MS-7D75                  | 2        | 0.35%   |
| MSI MS-7D54                  | 2        | 0.35%   |
| MSI MS-7D43                  | 2        | 0.35%   |
| MSI MS-7D25                  | 2        | 0.35%   |
| MSI MS-7C56                  | 2        | 0.35%   |
| MSI MS-7C37                  | 2        | 0.35%   |
| MSI MS-7B84                  | 2        | 0.35%   |
| MSI MS-7B61                  | 2        | 0.35%   |
| MSI MS-7A40                  | 2        | 0.35%   |
| MSI MS-7A38                  | 2        | 0.35%   |
| MSI MS-7817                  | 2        | 0.35%   |
| MSI MS-7693                  | 2        | 0.35%   |
| HP ProDesk 600 G1 SFF        | 2        | 0.35%   |
| HP Desktop M01-F1xxx         | 2        | 0.35%   |
| Gigabyte Z77-D3H             | 2        | 0.35%   |
| Gigabyte Z270-HD3P           | 2        | 0.35%   |
| Gigabyte X570 GAMING X       | 2        | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ASUS PRIME         | 35       | 6.07%   |
| ASUS ROG           | 31       | 5.37%   |
| ASUS All           | 21       | 3.64%   |
| ASUS TUF           | 19       | 3.29%   |
| Dell OptiPlex      | 16       | 2.77%   |
| Lenovo ThinkCentre | 15       | 2.6%    |
| Gigabyte X570      | 9        | 1.56%   |
| HP EliteDesk       | 7        | 1.21%   |
| Fujitsu ESPRIMO    | 7        | 1.21%   |
| Dell Precision     | 7        | 1.21%   |
| Unknown            | 7        | 1.21%   |
| HP Compaq          | 6        | 1.04%   |
| MSI MS-7B79        | 5        | 0.87%   |
| Lenovo IdeaCentre  | 5        | 0.87%   |
| HP ProDesk         | 5        | 0.87%   |
| ASRock B450M       | 5        | 0.87%   |
| Acer Aspire        | 5        | 0.87%   |
| MSI MS-7B51        | 4        | 0.69%   |
| HP Pavilion        | 4        | 0.69%   |
| Gigabyte B550M     | 4        | 0.69%   |
| Gigabyte B450      | 4        | 0.69%   |
| Dell XPS           | 4        | 0.69%   |
| ASUS P8Z77-V       | 4        | 0.69%   |
| ASUS P8H61-M       | 4        | 0.69%   |
| ASUS P5Q           | 4        | 0.69%   |
| MSI MS-7D91        | 3        | 0.52%   |
| MSI MS-7C95        | 3        | 0.52%   |
| MSI MS-7B86        | 3        | 0.52%   |
| MSI MS-7A32        | 3        | 0.52%   |
| Gigabyte H410M     | 3        | 0.52%   |
| Gigabyte B550      | 3        | 0.52%   |
| Gigabyte B450M     | 3        | 0.52%   |
| Dell Inspiron      | 3        | 0.52%   |
| ASUS STRIX         | 3        | 0.52%   |
| ASUS SABERTOOTH    | 3        | 0.52%   |
| ASUS P9X79         | 3        | 0.52%   |
| ASUS M5A97         | 3        | 0.52%   |
| ASUS M5A78L-M      | 3        | 0.52%   |
| ASRock A320M-HDV   | 3        | 0.52%   |
| Alienware Aurora   | 3        | 0.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 72       | 12.48%  |
| 2020 | 62       | 10.75%  |
| 2021 | 49       | 8.49%   |
| 2019 | 46       | 7.97%   |
| 2013 | 44       | 7.63%   |
| 2012 | 44       | 7.63%   |
| 2017 | 42       | 7.28%   |
| 2014 | 40       | 6.93%   |
| 2011 | 30       | 5.2%    |
| 2022 | 27       | 4.68%   |
| 2016 | 26       | 4.51%   |
| 2015 | 26       | 4.51%   |
| 2010 | 19       | 3.29%   |
| 2023 | 14       | 2.43%   |
| 2009 | 14       | 2.43%   |
| 2008 | 13       | 2.25%   |
| 2007 | 7        | 1.21%   |
| 2024 | 2        | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 577      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 560      | 97.05%  |
| Enabled  | 17       | 2.95%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 576      | 99.83%  |
| Yes  | 1        | 0.17%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 168      | 28.87%  |
| 32.01-64.0      | 143      | 24.57%  |
| 8.01-16.0       | 89       | 15.29%  |
| 4.01-8.0        | 68       | 11.68%  |
| 64.01-256.0     | 56       | 9.62%   |
| 3.01-4.0        | 33       | 5.67%   |
| 24.01-32.0      | 21       | 3.61%   |
| More than 256.0 | 2        | 0.34%   |
| 2.01-3.0        | 2        | 0.34%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 160      | 25.56%  |
| 2.01-3.0   | 159      | 25.4%   |
| 3.01-4.0   | 119      | 19.01%  |
| 1.01-2.0   | 109      | 17.41%  |
| 8.01-16.0  | 49       | 7.83%   |
| 16.01-24.0 | 14       | 2.24%   |
| 24.01-32.0 | 6        | 0.96%   |
| 0.51-1.0   | 5        | 0.8%    |
| 32.01-64.0 | 4        | 0.64%   |
| 0.01-0.5   | 1        | 0.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 179      | 30.24%  |
| 1      | 146      | 24.66%  |
| 3      | 114      | 19.26%  |
| 4      | 72       | 12.16%  |
| 5      | 35       | 5.91%   |
| 6      | 20       | 3.38%   |
| 7      | 17       | 2.87%   |
| 9      | 4        | 0.68%   |
| 8      | 3        | 0.51%   |
| 11     | 2        | 0.34%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 339      | 58.25%  |
| Yes       | 243      | 41.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 571      | 98.96%  |
| No        | 6        | 1.04%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 302      | 52.07%  |
| No        | 278      | 47.93%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 328      | 56.45%  |
| Yes       | 253      | 43.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 132      | 22.84%  |
| Germany      | 67       | 11.59%  |
| France       | 45       | 7.79%   |
| Italy        | 33       | 5.71%   |
| Brazil       | 31       | 5.36%   |
| UK           | 28       | 4.84%   |
| Russia       | 28       | 4.84%   |
| Spain        | 20       | 3.46%   |
| Netherlands  | 16       | 2.77%   |
| Poland       | 15       | 2.6%    |
| Australia    | 15       | 2.6%    |
| Canada       | 13       | 2.25%   |
| Switzerland  | 9        | 1.56%   |
| Austria      | 9        | 1.56%   |
| Finland      | 7        | 1.21%   |
| Czechia      | 7        | 1.21%   |
| Argentina    | 7        | 1.21%   |
| Bulgaria     | 6        | 1.04%   |
| Belgium      | 6        | 1.04%   |
| Greece       | 5        | 0.87%   |
| Slovenia     | 4        | 0.69%   |
| Portugal     | 4        | 0.69%   |
| India        | 4        | 0.69%   |
| Venezuela    | 3        | 0.52%   |
| Sweden       | 3        | 0.52%   |
| South Africa | 3        | 0.52%   |
| Romania      | 3        | 0.52%   |
| Philippines  | 3        | 0.52%   |
| Norway       | 3        | 0.52%   |
| New Zealand  | 3        | 0.52%   |
| Mexico       | 3        | 0.52%   |
| Turkey       | 2        | 0.35%   |
| Thailand     | 2        | 0.35%   |
| Serbia       | 2        | 0.35%   |
| Peru         | 2        | 0.35%   |
| Iran         | 2        | 0.35%   |
| Hungary      | 2        | 0.35%   |
| Denmark      | 2        | 0.35%   |
| China        | 2        | 0.35%   |
| Belarus      | 2        | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Milan            | 7        | 1.16%   |
| London           | 7        | 1.16%   |
| Berlin           | 7        | 1.16%   |
| Vienna           | 6        | 1%      |
| Moscow           | 6        | 1%      |
| Munich           | 5        | 0.83%   |
| Melbourne        | 5        | 0.83%   |
| Sydney           | 4        | 0.66%   |
| St Petersburg    | 4        | 0.66%   |
| Sao Paulo        | 4        | 0.66%   |
| Rio de Janeiro   | 4        | 0.66%   |
| Montreal         | 4        | 0.66%   |
| Jamestown        | 4        | 0.66%   |
| Dallas           | 4        | 0.66%   |
| Zurich           | 3        | 0.5%    |
| Vladivostok      | 3        | 0.5%    |
| Rome             | 3        | 0.5%    |
| Paris            | 3        | 0.5%    |
| Indianapolis     | 3        | 0.5%    |
| Hamburg          | 3        | 0.5%    |
| Curitiba         | 3        | 0.5%    |
| Caracas          | 3        | 0.5%    |
| Amsterdam        | 3        | 0.5%    |
| Wroclaw          | 2        | 0.33%   |
| Washington       | 2        | 0.33%   |
| Varna            | 2        | 0.33%   |
| Vallejo          | 2        | 0.33%   |
| Ustron           | 2        | 0.33%   |
| Turku            | 2        | 0.33%   |
| Thornton         | 2        | 0.33%   |
| Thessaloniki     | 2        | 0.33%   |
| Strasbourg       | 2        | 0.33%   |
| San Francisco    | 2        | 0.33%   |
| Roche-la-Moliere | 2        | 0.33%   |
| Reggio Emilia    | 2        | 0.33%   |
| Prague           | 2        | 0.33%   |
| Pittsburgh       | 2        | 0.33%   |
| Palermo          | 2        | 0.33%   |
| New York         | 2        | 0.33%   |
| Nashville        | 2        | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 202      | 338    | 16.6%   |
| Samsung Electronics         | 200      | 400    | 16.43%  |
| Seagate                     | 191      | 358    | 15.69%  |
| Kingston                    | 77       | 104    | 6.33%   |
| Toshiba                     | 63       | 85     | 5.18%   |
| Sandisk                     | 63       | 89     | 5.18%   |
| Crucial                     | 57       | 69     | 4.68%   |
| Hitachi                     | 38       | 47     | 3.12%   |
| A-DATA Technology           | 26       | 33     | 2.14%   |
| Intel                       | 18       | 24     | 1.48%   |
| HGST                        | 15       | 19     | 1.23%   |
| China                       | 15       | 16     | 1.23%   |
| PNY                         | 14       | 40     | 1.15%   |
| Unknown                     | 13       | 26     | 1.07%   |
| Phison Electronics          | 13       | 15     | 1.07%   |
| Phison                      | 12       | 12     | 0.99%   |
| Patriot                     | 11       | 14     | 0.9%    |
| Corsair                     | 11       | 14     | 0.9%    |
| SPCC                        | 9        | 11     | 0.74%   |
| Maxtor                      | 8        | 11     | 0.66%   |
| OCZ                         | 7        | 7      | 0.58%   |
| Micron Technology           | 7        | 7      | 0.58%   |
| Transcend                   | 6        | 7      | 0.49%   |
| SK hynix                    | 6        | 8      | 0.49%   |
| Micron/Crucial Technology   | 6        | 10     | 0.49%   |
| Intenso                     | 6        | 8      | 0.49%   |
| Silicon Motion              | 5        | 10     | 0.41%   |
| Lexar                       | 5        | 5      | 0.41%   |
| GOODRAM                     | 5        | 6      | 0.41%   |
| Netac                       | 4        | 6      | 0.33%   |
| Mushkin                     | 4        | 6      | 0.33%   |
| KIOXIA                      | 4        | 4      | 0.33%   |
| Kingston Technology Company | 4        | 9      | 0.33%   |
| Verbatim                    | 3        | 3      | 0.25%   |
| T-FORCE                     | 3        | 3      | 0.25%   |
| SABRENT                     | 3        | 3      | 0.25%   |
| Realtek Semiconductor       | 3        | 3      | 0.25%   |
| JMicron Technology          | 3        | 3      | 0.25%   |
| Gigabyte Technology         | 3        | 3      | 0.25%   |
| Apple                       | 3        | 3      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 23       | 1.58%   |
| Kingston SA400S37240G 240GB SSD                      | 16       | 1.1%    |
| Samsung SSD 860 EVO 1TB                              | 15       | 1.03%   |
| Toshiba DT01ACA100 1TB                               | 14       | 0.96%   |
| Samsung SSD 850 EVO 500GB                            | 14       | 0.96%   |
| Seagate ST2000DM008-2FR102 2TB                       | 13       | 0.89%   |
| Samsung SSD 860 EVO 500GB                            | 13       | 0.89%   |
| Seagate ST4000DM004-2CV104 4TB                       | 12       | 0.83%   |
| Kingston SA400S37480G 480GB SSD                      | 12       | 0.83%   |
| Crucial CT1000MX500SSD1 1TB                          | 9        | 0.62%   |
| WDC WD10EZEX-08WN4A0 1TB                             | 8        | 0.55%   |
| Seagate ST1000DM003-1ER162 1TB                       | 8        | 0.55%   |
| Samsung SSD 870 QVO 1TB                              | 8        | 0.55%   |
| Samsung SSD 850 EVO 250GB                            | 8        | 0.55%   |
| Toshiba HDWD110 1TB                                  | 7        | 0.48%   |
| Seagate ST31000524AS 1TB                             | 7        | 0.48%   |
| Seagate ST2000DM008-2UB102 2TB                       | 7        | 0.48%   |
| Samsung SSD 870 EVO 1TB                              | 7        | 0.48%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 7        | 0.48%   |
| WDC WD40EZRZ-00GXCB0 4TB                             | 6        | 0.41%   |
| WDC WD20EZRX-00D8PB0 2TB                             | 6        | 0.41%   |
| Toshiba DT01ACA200 2TB                               | 6        | 0.41%   |
| Seagate ST500DM002-1BD142 500GB                      | 6        | 0.41%   |
| Seagate ST2000DM001-1ER164 2TB                       | 6        | 0.41%   |
| SanDisk NVMe SSD Drive 500GB                         | 6        | 0.41%   |
| Samsung SSD 980 1TB                                  | 6        | 0.41%   |
| Samsung SSD 870 EVO 500GB                            | 6        | 0.41%   |
| Samsung SSD 860 EVO 250GB                            | 6        | 0.41%   |
| Crucial CT500MX500SSD1 500GB                         | 6        | 0.41%   |
| Crucial CT240BX500SSD1 240GB                         | 6        | 0.41%   |
| WDC WD10EZEX-22MFCA0 1TB                             | 5        | 0.34%   |
| Unknown SD/MMC 1073GB                                | 5        | 0.34%   |
| Unknown M.S./M.S.Pro/HG 16GB                         | 5        | 0.34%   |
| Unknown Compact Flash 977MB                          | 5        | 0.34%   |
| Seagate ST3500418AS 500GB                            | 5        | 0.34%   |
| Seagate ST1000DM003-1SB102 1TB                       | 5        | 0.34%   |
| SanDisk SSD PLUS 480GB                               | 5        | 0.34%   |
| Samsung SSD 980 PRO 2TB                              | 5        | 0.34%   |
| Samsung SSD 980 PRO 1TB                              | 5        | 0.34%   |
| Samsung SSD 970 EVO Plus 1TB                         | 5        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 180      | 337    | 35.36%  |
| WDC                 | 175      | 269    | 34.38%  |
| Toshiba             | 57       | 77     | 11.2%   |
| Hitachi             | 38       | 47     | 7.47%   |
| Samsung Electronics | 26       | 45     | 5.11%   |
| HGST                | 15       | 19     | 2.95%   |
| Maxtor              | 7        | 10     | 1.38%   |
| SABRENT             | 3        | 3      | 0.59%   |
| Unknown             | 2        | 2      | 0.39%   |
| JMicron Technology  | 2        | 2      | 0.39%   |
| Apple               | 2        | 2      | 0.39%   |
| USB3.0              | 1        | 2      | 0.2%    |
| IET                 | 1        | 1      | 0.2%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 124      | 214    | 26.11%  |
| Kingston            | 61       | 77     | 12.84%  |
| Crucial             | 49       | 59     | 10.32%  |
| SanDisk             | 37       | 46     | 7.79%   |
| WDC                 | 31       | 58     | 6.53%   |
| A-DATA Technology   | 22       | 28     | 4.63%   |
| China               | 15       | 16     | 3.16%   |
| PNY                 | 14       | 40     | 2.95%   |
| Patriot             | 11       | 14     | 2.32%   |
| SPCC                | 8        | 9      | 1.68%   |
| Intel               | 8        | 13     | 1.68%   |
| OCZ                 | 7        | 7      | 1.47%   |
| Micron Technology   | 6        | 6      | 1.26%   |
| Transcend           | 5        | 5      | 1.05%   |
| Lexar               | 5        | 5      | 1.05%   |
| GOODRAM             | 5        | 6      | 1.05%   |
| Toshiba             | 4        | 4      | 0.84%   |
| Mushkin             | 4        | 6      | 0.84%   |
| Intenso             | 4        | 4      | 0.84%   |
| Corsair             | 4        | 4      | 0.84%   |
| Verbatim            | 3        | 3      | 0.63%   |
| Netac               | 3        | 5      | 0.63%   |
| SK hynix            | 2        | 2      | 0.42%   |
| Seagate             | 2        | 3      | 0.42%   |
| RZX                 | 2        | 2      | 0.42%   |
| Plextor             | 2        | 2      | 0.42%   |
| LITEONIT            | 2        | 2      | 0.42%   |
| KODAK               | 2        | 2      | 0.42%   |
| KIOXIA-EXCERIA      | 2        | 4      | 0.42%   |
| INNOVATION IT       | 2        | 2      | 0.42%   |
| Hewlett-Packard     | 2        | 2      | 0.42%   |
| Apacer              | 2        | 2      | 0.42%   |
| ValueTech           | 1        | 1      | 0.21%   |
| USB3.0              | 1        | 1      | 0.21%   |
| Teutons             | 1        | 1      | 0.21%   |
| Team                | 1        | 1      | 0.21%   |
| T-FORCE             | 1        | 1      | 0.21%   |
| SSSTC               | 1        | 1      | 0.21%   |
| Smartbuy            | 1        | 1      | 0.21%   |
| SD                  | 1        | 7      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 387      | 816    | 37.94%  |
| SSD     | 376      | 684    | 36.86%  |
| NVMe    | 224      | 367    | 21.96%  |
| Unknown | 30       | 51     | 2.94%   |
| MMC     | 3        | 3      | 0.29%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 525      | 1453   | 64.89%  |
| NVMe | 221      | 361    | 27.32%  |
| SAS  | 60       | 104    | 7.42%   |
| MMC  | 3        | 3      | 0.37%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 362      | 664    | 41.37%  |
| 0.51-1.0   | 247      | 377    | 28.23%  |
| 1.01-2.0   | 123      | 213    | 14.06%  |
| 3.01-4.0   | 73       | 149    | 8.34%   |
| 4.01-10.0  | 33       | 50     | 3.77%   |
| 2.01-3.0   | 29       | 34     | 3.31%   |
| 10.01-20.0 | 8        | 13     | 0.91%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 120      | 20.27%  |
| 1001-2000      | 107      | 18.07%  |
| 501-1000       | 107      | 18.07%  |
| 251-500        | 89       | 15.03%  |
| 101-250        | 79       | 13.34%  |
| 2001-3000      | 62       | 10.47%  |
| 1-20           | 16       | 2.7%    |
| 51-100         | 10       | 1.69%   |
| Unknown        | 2        | 0.34%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 89       | 14.61%  |
| 501-1000       | 87       | 14.29%  |
| 251-500        | 86       | 14.12%  |
| 1001-2000      | 73       | 11.99%  |
| 1-20           | 66       | 10.84%  |
| 51-100         | 63       | 10.34%  |
| 21-50          | 62       | 10.18%  |
| More than 3000 | 54       | 8.87%   |
| 2001-3000      | 27       | 4.43%   |
| Unknown        | 2        | 0.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 3        | 3      | 3.41%   |
| Samsung Electronics SSD 870 EVO 500GB | 3        | 3      | 3.41%   |
| Seagate ST31000524AS 1TB              | 2        | 3      | 2.27%   |
| Samsung Electronics SSD 870 EVO 1TB   | 2        | 2      | 2.27%   |
| Samsung Electronics HD103SI 1TB       | 2        | 2      | 2.27%   |
| Maxtor STM3250310AS 250GB             | 2        | 3      | 2.27%   |
| Hitachi HDS721010CLA630 1TB           | 2        | 2      | 2.27%   |
| WDC WD7502ABYS-02A6B0 752GB           | 1        | 1      | 1.14%   |
| WDC WD5000AZRX-00A3KB0 500GB          | 1        | 1      | 1.14%   |
| WDC WD5000AVVS-63M8B0 500GB           | 1        | 1      | 1.14%   |
| WDC WD5000AAKS-00V1A0 500GB           | 1        | 1      | 1.14%   |
| WDC WD40EURX-63BMCY0 4TB              | 1        | 1      | 1.14%   |
| WDC WD40EFAX-68JH4N1 4TB              | 1        | 4      | 1.14%   |
| WDC WD3200JD-22KLB0 320GB             | 1        | 1      | 1.14%   |
| WDC WD30EZRX-00MMMB0 3TB              | 1        | 1      | 1.14%   |
| WDC WD30EFRX-68EUZN0 3TB              | 1        | 1      | 1.14%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1        | 2      | 1.14%   |
| WDC WD20EADS-14R6B0 2TB               | 1        | 1      | 1.14%   |
| WDC WD10EZRZ-00HTKB0 1TB              | 1        | 1      | 1.14%   |
| WDC WD10EZRX-00L4HB0 1TB              | 1        | 1      | 1.14%   |
| WDC WD10EZEX-22MFCA0 1TB              | 1        | 1      | 1.14%   |
| WDC WD10EZEX-08M2NA0 1TB              | 1        | 1      | 1.14%   |
| WDC WD10EURX-73C57Y0 1TB              | 1        | 1      | 1.14%   |
| WDC WD10EARS-00MVWB0 1TB              | 1        | 1      | 1.14%   |
| WDC WD10EADS-00L5B1 1TB               | 1        | 1      | 1.14%   |
| WDC WD10EACS-65D6B0 1TB               | 1        | 1      | 1.14%   |
| WDC WD1001FALS-40U9B0 1TB             | 1        | 1      | 1.14%   |
| Toshiba MQ01ABF032 320GB              | 1        | 1      | 1.14%   |
| Toshiba MK6475GSX 640GB               | 1        | 1      | 1.14%   |
| Toshiba DT01ACA100 1TB                | 1        | 2      | 1.14%   |
| T-FORCE SSD 512GB                     | 1        | 1      | 1.14%   |
| SSSTC CVB-8D128-HP 128GB SSD          | 1        | 1      | 1.14%   |
| Seagate ST500LT012-9WS142 500GB       | 1        | 1      | 1.14%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1        | 1      | 1.14%   |
| Seagate ST4000VN008-2DR166 4TB        | 1        | 2      | 1.14%   |
| Seagate ST4000NM0053 4TB              | 1        | 1      | 1.14%   |
| Seagate ST3500630AS 500GB             | 1        | 1      | 1.14%   |
| Seagate ST3500418AS 500GB             | 1        | 1      | 1.14%   |
| Seagate ST3500320NS 500GB             | 1        | 1      | 1.14%   |
| Seagate ST3250310AS 250GB             | 1        | 1      | 1.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 20       | 24     | 23.81%  |
| WDC                 | 18       | 24     | 21.43%  |
| Samsung Electronics | 12       | 26     | 14.29%  |
| Hitachi             | 6        | 6      | 7.14%   |
| Crucial             | 4        | 4      | 4.76%   |
| Toshiba             | 3        | 4      | 3.57%   |
| SanDisk             | 3        | 3      | 3.57%   |
| Maxtor              | 3        | 4      | 3.57%   |
| Kingston            | 3        | 3      | 3.57%   |
| T-FORCE             | 1        | 1      | 1.19%   |
| SSSTC               | 1        | 1      | 1.19%   |
| Phison Electronics  | 1        | 1      | 1.19%   |
| OCZ                 | 1        | 1      | 1.19%   |
| Micron Technology   | 1        | 1      | 1.19%   |
| LITEONIT            | 1        | 1      | 1.19%   |
| Intenso             | 1        | 1      | 1.19%   |
| Intel               | 1        | 4      | 1.19%   |
| HGST                | 1        | 1      | 1.19%   |
| Corsair             | 1        | 1      | 1.19%   |
| China               | 1        | 1      | 1.19%   |
| A-DATA Technology   | 1        | 1      | 1.19%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 20       | 24     | 36.36%  |
| WDC                 | 18       | 24     | 32.73%  |
| Hitachi             | 6        | 6      | 10.91%  |
| Samsung Electronics | 4        | 18     | 7.27%   |
| Toshiba             | 3        | 4      | 5.45%   |
| Maxtor              | 3        | 4      | 5.45%   |
| HGST                | 1        | 1      | 1.82%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 52       | 81     | 65%     |
| SSD  | 26       | 30     | 32.5%   |
| NVMe | 2        | 2      | 2.5%    |

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
| Detected | 331      | 955    | 47.97%  |
| Works    | 282      | 851    | 40.87%  |
| Malfunc  | 76       | 113    | 11.01%  |
| Failed   | 1        | 2      | 0.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Intel                                   | 354      | 39.2%   |
| AMD                                     | 219      | 24.25%  |
| Samsung Electronics                     | 86       | 9.52%   |
| SanDisk                                 | 37       | 4.1%    |
| ASMedia Technology                      | 35       | 3.88%   |
| Phison Electronics                      | 34       | 3.77%   |
| Kingston Technology Company             | 23       | 2.55%   |
| JMicron Technology                      | 19       | 2.1%    |
| Marvell Technology Group                | 17       | 1.88%   |
| Micron/Crucial Technology               | 14       | 1.55%   |
| Silicon Motion                          | 8        | 0.89%   |
| Realtek Semiconductor                   | 6        | 0.66%   |
| LSI Logic / Symbios Logic               | 6        | 0.66%   |
| ADATA Technology                        | 6        | 0.66%   |
| KIOXIA                                  | 5        | 0.55%   |
| SK hynix                                | 4        | 0.44%   |
| Seagate Technology                      | 4        | 0.44%   |
| Nvidia                                  | 3        | 0.33%   |
| MAXIO Technology (Hangzhou)             | 3        | 0.33%   |
| VIA Technologies                        | 2        | 0.22%   |
| Toshiba America Info Systems            | 2        | 0.22%   |
| Silicon Image                           | 2        | 0.22%   |
| Lite-On Technology                      | 2        | 0.22%   |
| Broadcom / LSI                          | 2        | 0.22%   |
| Zhaoxin                                 | 1        | 0.11%   |
| Shenzhen Longsys Electronics            | 1        | 0.11%   |
| Promise Technology                      | 1        | 0.11%   |
| OCZ Technology Group                    | 1        | 0.11%   |
| O2 Micro                                | 1        | 0.11%   |
| Netac Technology                        | 1        | 0.11%   |
| Micron Technology                       | 1        | 0.11%   |
| Jiangsu Xinsheng Intelligent Technology | 1        | 0.11%   |
| INNOGRIT                                | 1        | 0.11%   |
| 3ware                                   | 1        | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 114      | 10.47%  |
| AMD 400 Series Chipset SATA Controller                                                  | 48       | 4.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 42       | 3.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 42       | 3.86%   |
| AMD 500 Series Chipset SATA Controller                                                  | 39       | 3.58%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 32       | 2.94%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 30       | 2.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 28       | 2.57%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 26       | 2.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 26       | 2.39%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 25       | 2.3%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 23       | 2.11%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 22       | 2.02%   |
| Intel SATA Controller [RAID mode]                                                       | 21       | 1.93%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 21       | 1.93%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 19       | 1.74%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 18       | 1.65%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 16       | 1.47%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 13       | 1.19%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 12       | 1.1%    |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 12       | 1.1%    |
| AMD 600 Series Chipset SATA Controller                                                  | 12       | 1.1%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 11       | 1.01%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 11       | 1.01%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 10       | 0.92%   |
| Phison E12 NVMe Controller                                                              | 10       | 0.92%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 10       | 0.92%   |
| Intel SSD 660P Series                                                                   | 10       | 0.92%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 10       | 0.92%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 10       | 0.92%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 10       | 0.92%   |
| AMD X370 Series Chipset SATA Controller                                                 | 10       | 0.92%   |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                              | 9        | 0.83%   |
| AMD 300 Series Chipset SATA Controller                                                  | 9        | 0.83%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 8        | 0.73%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 7        | 0.64%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                   | 7        | 0.64%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 7        | 0.64%   |
| Intel Raptor Lake SATA AHCI Controller                                                  | 7        | 0.64%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 515      | 60.23%  |
| NVMe | 220      | 25.73%  |
| IDE  | 78       | 9.12%   |
| RAID | 37       | 4.33%   |
| SAS  | 3        | 0.35%   |
| SCSI | 2        | 0.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor        | Desktops | Percent |
|---------------|----------|---------|
| Intel         | 351      | 60.83%  |
| AMD           | 224      | 38.82%  |
| sifive,u74-mc | 1        | 0.17%   |
| CentaurHauls  | 1        | 0.17%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Core i7-3770 CPU @ 3.40GHz       | 15       | 2.6%    |
| Intel Core i5-4590 CPU @ 3.30GHz       | 10       | 1.73%   |
| AMD Ryzen 7 3700X 8-Core Processor     | 10       | 1.73%   |
| AMD Ryzen 5 5600X 6-Core Processor     | 10       | 1.73%   |
| Intel Core i7-4790 CPU @ 3.60GHz       | 9        | 1.56%   |
| AMD Ryzen 5 5600G with Radeon Graphics | 9        | 1.56%   |
| Intel Core i7-4790K CPU @ 4.00GHz      | 8        | 1.39%   |
| Intel Core i5-9600K CPU @ 3.70GHz      | 8        | 1.39%   |
| AMD Ryzen 9 5900X 12-Core Processor    | 8        | 1.39%   |
| AMD Ryzen 5 3600 6-Core Processor      | 8        | 1.39%   |
| Intel Core i7-6700 CPU @ 3.40GHz       | 7        | 1.21%   |
| Intel Core i5-10400F CPU @ 2.90GHz     | 7        | 1.21%   |
| AMD Ryzen 5 2600X Six-Core Processor   | 7        | 1.21%   |
| Intel Core i7-7700K CPU @ 4.20GHz      | 6        | 1.04%   |
| Intel Core i7 CPU 920 @ 2.67GHz        | 6        | 1.04%   |
| AMD Ryzen 7 5800X 8-Core Processor     | 6        | 1.04%   |
| AMD Ryzen 7 2700X Eight-Core Processor | 6        | 1.04%   |
| AMD FX-8350 Eight-Core Processor       | 6        | 1.04%   |
| Intel Core i7-4770 CPU @ 3.40GHz       | 5        | 0.87%   |
| Intel Core i5-8400 CPU @ 2.80GHz       | 5        | 0.87%   |
| Intel Core i5-6500 CPU @ 3.20GHz       | 5        | 0.87%   |
| Intel Core i5-2300 CPU @ 2.80GHz       | 5        | 0.87%   |
| Intel Core i3-10100F CPU @ 3.60GHz     | 5        | 0.87%   |
| AMD Ryzen 9 3900X 12-Core Processor    | 5        | 0.87%   |
| AMD Ryzen 7 1700 Eight-Core Processor  | 5        | 0.87%   |
| Intel Core i9-9900K CPU @ 3.60GHz      | 4        | 0.69%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 4        | 0.69%   |
| Intel Core i7-3770K CPU @ 3.50GHz      | 4        | 0.69%   |
| Intel Core i7-10700F CPU @ 2.90GHz     | 4        | 0.69%   |
| Intel Core i5-9400 CPU @ 2.90GHz       | 4        | 0.69%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 4        | 0.69%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 4        | 0.69%   |
| Intel Core i3-4130 CPU @ 3.40GHz       | 4        | 0.69%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz   | 4        | 0.69%   |
| Intel 12th Gen Core i7-12700K          | 4        | 0.69%   |
| AMD Ryzen 9 7950X 16-Core Processor    | 4        | 0.69%   |
| AMD Ryzen 9 5950X 16-Core Processor    | 4        | 0.69%   |
| AMD Ryzen 9 3950X 16-Core Processor    | 4        | 0.69%   |
| AMD Ryzen 7 5700G with Radeon Graphics | 4        | 0.69%   |
| AMD Ryzen 5 5600 6-Core Processor      | 4        | 0.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 107      | 18.54%  |
| Intel Core i7           | 103      | 17.85%  |
| AMD Ryzen 5             | 65       | 11.27%  |
| AMD Ryzen 7             | 45       | 7.8%    |
| Other                   | 38       | 6.59%   |
| AMD Ryzen 9             | 34       | 5.89%   |
| Intel Core i3           | 28       | 4.85%   |
| Intel Xeon              | 23       | 3.99%   |
| AMD FX                  | 19       | 3.29%   |
| Intel Pentium           | 13       | 2.25%   |
| Intel Core i9           | 10       | 1.73%   |
| AMD Ryzen 3             | 10       | 1.73%   |
| Intel Core 2 Duo        | 9        | 1.56%   |
| Intel Core 2 Quad       | 8        | 1.39%   |
| Intel Celeron           | 8        | 1.39%   |
| AMD Phenom II X4        | 7        | 1.21%   |
| AMD A6                  | 5        | 0.87%   |
| Intel Pentium Gold      | 4        | 0.69%   |
| AMD Phenom II X6        | 4        | 0.69%   |
| AMD A8                  | 4        | 0.69%   |
| AMD Ryzen Threadripper  | 3        | 0.52%   |
| AMD Ryzen 7 PRO         | 3        | 0.52%   |
| AMD Phenom II X2        | 3        | 0.52%   |
| AMD Opteron             | 3        | 0.52%   |
| AMD Athlon II X2        | 3        | 0.52%   |
| AMD Athlon 64 X2        | 3        | 0.52%   |
| AMD A10                 | 3        | 0.52%   |
| Intel Pentium Dual-Core | 1        | 0.17%   |
| Intel Pentium D         | 1        | 0.17%   |
| Intel Atom              | 1        | 0.17%   |
| AMD Ryzen 5 PRO         | 1        | 0.17%   |
| AMD PRO A10             | 1        | 0.17%   |
| AMD Phenom              | 1        | 0.17%   |
| AMD EPYC                | 1        | 0.17%   |
| AMD E2                  | 1        | 0.17%   |
| AMD E1                  | 1        | 0.17%   |
| AMD C-60                | 1        | 0.17%   |
| AMD Athlon              | 1        | 0.17%   |
| AMD A4                  | 1        | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 224      | 38.82%  |
| 6       | 116      | 20.1%   |
| 2       | 83       | 14.38%  |
| 8       | 80       | 13.86%  |
| 12      | 24       | 4.16%   |
| 16      | 23       | 3.99%   |
| 10      | 7        | 1.21%   |
| 24      | 5        | 0.87%   |
| 1       | 5        | 0.87%   |
| 14      | 4        | 0.69%   |
| 3       | 3        | 0.52%   |
| 36      | 1        | 0.17%   |
| 20      | 1        | 0.17%   |
| Unknown | 1        | 0.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 571      | 98.96%  |
| 2       | 5        | 0.87%   |
| Unknown | 1        | 0.17%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 385      | 66.61%  |
| 1       | 192      | 33.22%  |
| Unknown | 1        | 0.17%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 576      | 99.83%  |
| Unknown        | 1        | 0.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 328      | 55.59%  |
| 0x306c3    | 24       | 4.07%   |
| 0x08701021 | 19       | 3.22%   |
| 0x506e3    | 11       | 1.86%   |
| 0x306a9    | 11       | 1.86%   |
| 0x906e9    | 10       | 1.69%   |
| 0x0800820d | 10       | 1.69%   |
| 0xa0653    | 8        | 1.36%   |
| 0x906ea    | 8        | 1.36%   |
| 0x206a7    | 8        | 1.36%   |
| 0x010000c8 | 8        | 1.36%   |
| 0x906ed    | 7        | 1.19%   |
| 0x0a201016 | 7        | 1.19%   |
| 0xa0655    | 6        | 1.02%   |
| 0x90672    | 6        | 1.02%   |
| 0x0a50000c | 6        | 1.02%   |
| 0x08001138 | 6        | 1.02%   |
| 0x06000852 | 6        | 1.02%   |
| 0x1067a    | 5        | 0.85%   |
| 0x0a601203 | 5        | 0.85%   |
| 0x0a50000d | 5        | 0.85%   |
| 0x0a201205 | 5        | 0.85%   |
| 0x08001137 | 5        | 0.85%   |
| 0x406f1    | 4        | 0.68%   |
| 0x306f2    | 4        | 0.68%   |
| 0x306e4    | 4        | 0.68%   |
| 0xb0671    | 3        | 0.51%   |
| 0xa0671    | 3        | 0.51%   |
| 0x206d7    | 3        | 0.51%   |
| 0x106e5    | 3        | 0.51%   |
| 0x0a20120a | 3        | 0.51%   |
| 0x0a201009 | 3        | 0.51%   |
| 0x08600106 | 3        | 0.51%   |
| 0x0600611a | 3        | 0.51%   |
| 0x106a5    | 2        | 0.34%   |
| 0x0a601206 | 2        | 0.34%   |
| 0x0a201204 | 2        | 0.34%   |
| 0x08701030 | 2        | 0.34%   |
| 0x08001126 | 2        | 0.34%   |
| 0x06001119 | 2        | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 72       | 12.46%  |
| KabyLake         | 61       | 10.55%  |
| Zen 3            | 53       | 9.17%   |
| IvyBridge        | 48       | 8.3%    |
| Zen 2            | 42       | 7.27%   |
| Unknown          | 38       | 6.57%   |
| Zen              | 28       | 4.84%   |
| CometLake        | 28       | 4.84%   |
| Zen+             | 27       | 4.67%   |
| Skylake          | 27       | 4.67%   |
| SandyBridge      | 26       | 4.5%    |
| Piledriver       | 23       | 3.98%   |
| K10              | 19       | 3.29%   |
| Penryn           | 15       | 2.6%    |
| Nehalem          | 14       | 2.42%   |
| Alderlake Hybrid | 10       | 1.73%   |
| Excavator        | 6        | 1.04%   |
| Broadwell        | 6        | 1.04%   |
| Westmere         | 5        | 0.87%   |
| Icelake          | 5        | 0.87%   |
| Core             | 5        | 0.87%   |
| Steamroller      | 3        | 0.52%   |
| K8 Hammer        | 3        | 0.52%   |
| Puma             | 2        | 0.35%   |
| Goldmont         | 2        | 0.35%   |
| Bulldozer        | 2        | 0.35%   |
| Bobcat           | 2        | 0.35%   |
| TigerLake        | 1        | 0.17%   |
| Silvermont       | 1        | 0.17%   |
| NetBurst         | 1        | 0.17%   |
| K10 Llano        | 1        | 0.17%   |
| Goldmont plus    | 1        | 0.17%   |
| Bonnell          | 1        | 0.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 286      | 44.9%   |
| AMD                        | 187      | 29.36%  |
| Intel                      | 158      | 24.8%   |
| Matrox Electronics Systems | 3        | 0.47%   |
| ASPEED Technology          | 2        | 0.31%   |
| Zhaoxin                    | 1        | 0.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 32       | 4.87%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 27       | 4.11%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 25       | 3.81%   |
| Nvidia GK208B [GeForce GT 710]                                              | 14       | 2.13%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 14       | 2.13%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 14       | 2.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 14       | 2.13%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 12       | 1.83%   |
| Intel HD Graphics 530                                                       | 12       | 1.83%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 11       | 1.67%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 11       | 1.67%   |
| AMD Raphael                                                                 | 11       | 1.67%   |
| Intel HD Graphics 630                                                       | 10       | 1.52%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 10       | 1.52%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 10       | 1.52%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 9        | 1.37%   |
| Nvidia GK208B [GeForce GT 730]                                              | 9        | 1.37%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 9        | 1.37%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 8        | 1.22%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 7        | 1.07%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 7        | 1.07%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 7        | 1.07%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 7        | 1.07%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 7        | 1.07%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 6        | 0.91%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 6        | 0.91%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 6        | 0.91%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 6        | 0.91%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 6        | 0.91%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 6        | 0.91%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 6        | 0.91%   |
| Nvidia GT218 [GeForce 210]                                                  | 5        | 0.76%   |
| Nvidia GF108 [GeForce GT 730]                                               | 5        | 0.76%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 5        | 0.76%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 5        | 0.76%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 4        | 0.61%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 4        | 0.61%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 4        | 0.61%   |
| Nvidia GF119 [GeForce GT 610]                                               | 4        | 0.61%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 4        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 268      | 46.05%  |
| 1 x AMD                  | 160      | 27.49%  |
| 1 x Intel                | 112      | 19.24%  |
| 2 x AMD                  | 13       | 2.23%   |
| AMD + Nvidia             | 6        | 1.03%   |
| Intel + Nvidia           | 5        | 0.86%   |
| Intel + AMD              | 5        | 0.86%   |
| 2 x Nvidia               | 3        | 0.52%   |
| 3 x Nvidia               | 2        | 0.34%   |
| AMD + Matrox             | 2        | 0.34%   |
| Other                    | 1        | 0.17%   |
| 1 x Zhaoxin              | 1        | 0.17%   |
| Nvidia + Matrox          | 1        | 0.17%   |
| Nvidia + ASPEED          | 1        | 0.17%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.17%   |
| 1 x ASPEED               | 1        | 0.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 357      | 61.23%  |
| Proprietary | 196      | 33.62%  |
| Unknown     | 30       | 5.15%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 281      | 47.63%  |
| 1.01-2.0   | 62       | 10.51%  |
| 7.01-8.0   | 58       | 9.83%   |
| 3.01-4.0   | 57       | 9.66%   |
| 0.51-1.0   | 42       | 7.12%   |
| 5.01-6.0   | 31       | 5.25%   |
| 0.01-0.5   | 27       | 4.58%   |
| 8.01-16.0  | 24       | 4.07%   |
| 16.01-24.0 | 5        | 0.85%   |
| 2.01-3.0   | 2        | 0.34%   |
| 4.01-5.0   | 1        | 0.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 118      | 17.85%  |
| Dell                 | 79       | 11.95%  |
| Goldstar             | 67       | 10.14%  |
| Hewlett-Packard      | 51       | 7.72%   |
| Acer                 | 40       | 6.05%   |
| Philips              | 33       | 4.99%   |
| BenQ                 | 32       | 4.84%   |
| AOC                  | 30       | 4.54%   |
| Iiyama               | 29       | 4.39%   |
| Ancor Communications | 20       | 3.03%   |
| ASUSTek Computer     | 18       | 2.72%   |
| ViewSonic            | 9        | 1.36%   |
| Sony                 | 9        | 1.36%   |
| Eizo                 | 7        | 1.06%   |
| Lenovo               | 6        | 0.91%   |
| Vizio                | 4        | 0.61%   |
| Sceptre Tech         | 4        | 0.61%   |
| RTK                  | 4        | 0.61%   |
| NEC Computers        | 4        | 0.61%   |
| Idek Iiyama          | 4        | 0.61%   |
| Toshiba              | 3        | 0.45%   |
| Mi                   | 3        | 0.45%   |
| Medion               | 3        | 0.45%   |
| LG Electronics       | 3        | 0.45%   |
| Insignia             | 3        | 0.45%   |
| Hitachi              | 3        | 0.45%   |
| Gigabyte Technology  | 3        | 0.45%   |
| Fujitsu Siemens      | 3        | 0.45%   |
| Xiaomi               | 2        | 0.3%    |
| Vestel Elektronik    | 2        | 0.3%    |
| Unknown              | 2        | 0.3%    |
| Planar               | 2        | 0.3%    |
| Panasonic            | 2        | 0.3%    |
| MiTAC                | 2        | 0.3%    |
| HKC                  | 2        | 0.3%    |
| HannStar             | 2        | 0.3%    |
| Envision Peripherals | 2        | 0.3%    |
| Element              | 2        | 0.3%    |
| DTV                  | 2        | 0.3%    |
| Denver               | 2        | 0.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch               | 5        | 0.71%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 5        | 0.71%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                 | 4        | 0.56%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 3        | 0.42%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 3        | 0.42%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch      | 3        | 0.42%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 3        | 0.42%   |
| Iiyama PLE2207WS IVM5609 1680x1050 474x296mm 22.0-inch                 | 3        | 0.42%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                 | 3        | 0.42%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 3        | 0.42%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 3        | 0.42%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                      | 3        | 0.42%   |
| Dell 2408WFP DELA02B 1920x1200 519x320mm 24.0-inch                     | 3        | 0.42%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                      | 3        | 0.42%   |
| AOC Q27G2WG4 AOC2702 2560x1440 597x336mm 27.0-inch                     | 3        | 0.42%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch             | 2        | 0.28%   |
| Samsung Electronics SyncMaster SAM0589 1920x1080 521x293mm 23.5-inch   | 2        | 0.28%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch   | 2        | 0.28%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch    | 2        | 0.28%   |
| Samsung Electronics SA300/SA350 SAM078F 1920x1080 477x268mm 21.5-inch  | 2        | 0.28%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch      | 2        | 0.28%   |
| Samsung Electronics LCD Monitor SAM0D42 3840x2160 1020x570mm 46.0-inch | 2        | 0.28%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch  | 2        | 0.28%   |
| Samsung Electronics LC27G5xT SAM7079 2560x1440 597x336mm 27.0-inch     | 2        | 0.28%   |
| Planar PX2710MW PLN2710 1920x1080 598x336mm 27.0-inch                  | 2        | 0.28%   |
| Philips PHL 247E6 PHLC0E7 1920x1080 521x293mm 23.5-inch                | 2        | 0.28%   |
| Philips PHL 245E1 PHLC20B 2560x1440 527x296mm 23.8-inch                | 2        | 0.28%   |
| Philips PHL 241V8 PHLC212 1920x1080 527x296mm 23.8-inch                | 2        | 0.28%   |
| Philips LCD Monitor FTV                                                | 2        | 0.28%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                     | 2        | 0.28%   |
| Mi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                       | 2        | 0.28%   |
| Iiyama PLG2888UH IVM710B 3840x2160                                     | 2        | 0.28%   |
| Iiyama PL3288UH IVM1176 3840x2160 698x393mm 31.5-inch                  | 2        | 0.28%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                  | 2        | 0.28%   |
| Hewlett-Packard w2216 HWP280B 1680x1050 465x291mm 21.6-inch            | 2        | 0.28%   |
| Hewlett-Packard w1907 HWP26A3 1440x900 408x255mm 18.9-inch             | 2        | 0.28%   |
| Hewlett-Packard VH240a HPN349A 1920x1080 527x296mm 23.8-inch           | 2        | 0.28%   |
| Hewlett-Packard 27yh HPN351C 1920x1080 598x336mm 27.0-inch             | 2        | 0.28%   |
| Hewlett-Packard 24w HPN3431 1920x1080 527x296mm 23.8-inch              | 2        | 0.28%   |
| Hewlett-Packard 2311x HWP2939 1920x1080 510x287mm 23.0-inch            | 2        | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 314      | 49.84%  |
| 3840x2160 (4K)     | 75       | 11.9%   |
| 2560x1440 (QHD)    | 47       | 7.46%   |
| 1680x1050 (WSXGA+) | 30       | 4.76%   |
| 1920x1200 (WUXGA)  | 29       | 4.6%    |
| 1280x1024 (SXGA)   | 23       | 3.65%   |
| 1366x768 (WXGA)    | 18       | 2.86%   |
| 3440x1440          | 17       | 2.7%    |
| 1600x900 (HD+)     | 15       | 2.38%   |
| 1440x900 (WXGA+)   | 11       | 1.75%   |
| 1360x768           | 9        | 1.43%   |
| 2560x1080          | 8        | 1.27%   |
| Unknown            | 6        | 0.95%   |
| 3840x1080          | 5        | 0.79%   |
| 1920x540           | 4        | 0.63%   |
| 3840x1600          | 3        | 0.48%   |
| 1280x720 (HD)      | 3        | 0.48%   |
| 6160x1440          | 1        | 0.16%   |
| 5760x2160          | 1        | 0.16%   |
| 5760x1080          | 1        | 0.16%   |
| 480x1920           | 1        | 0.16%   |
| 4800x1080          | 1        | 0.16%   |
| 3840x1200          | 1        | 0.16%   |
| 3600x1200          | 1        | 0.16%   |
| 2560x1600          | 1        | 0.16%   |
| 2288x1287          | 1        | 0.16%   |
| 2048x1536          | 1        | 0.16%   |
| 1600x1200          | 1        | 0.16%   |
| 1280x768           | 1        | 0.16%   |
| 1024x768 (XGA)     | 1        | 0.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 117      | 17.62%  |
| 23      | 99       | 14.91%  |
| 27      | 96       | 14.46%  |
| 21      | 65       | 9.79%   |
| 31      | 44       | 6.63%   |
| Unknown | 29       | 4.37%   |
| 19      | 25       | 3.77%   |
| 34      | 23       | 3.46%   |
| 22      | 19       | 2.86%   |
| 18      | 17       | 2.56%   |
| 32      | 15       | 2.26%   |
| 20      | 15       | 2.26%   |
| 72      | 12       | 1.81%   |
| 17      | 10       | 1.51%   |
| 46      | 8        | 1.2%    |
| 84      | 7        | 1.05%   |
| 54      | 6        | 0.9%    |
| 40      | 5        | 0.75%   |
| 25      | 5        | 0.75%   |
| 52      | 4        | 0.6%    |
| 48      | 4        | 0.6%    |
| 28      | 4        | 0.6%    |
| 15      | 4        | 0.6%    |
| 65      | 3        | 0.45%   |
| 37      | 3        | 0.45%   |
| 36      | 3        | 0.45%   |
| 49      | 2        | 0.3%    |
| 43      | 2        | 0.3%    |
| 33      | 2        | 0.3%    |
| 29      | 2        | 0.3%    |
| 142     | 1        | 0.15%   |
| 69      | 1        | 0.15%   |
| 64      | 1        | 0.15%   |
| 61      | 1        | 0.15%   |
| 60      | 1        | 0.15%   |
| 59      | 1        | 0.15%   |
| 55      | 1        | 0.15%   |
| 42      | 1        | 0.15%   |
| 39      | 1        | 0.15%   |
| 38      | 1        | 0.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 271      | 43.08%  |
| 401-500        | 127      | 20.19%  |
| 601-700        | 65       | 10.33%  |
| 701-800        | 42       | 6.68%   |
| 1001-1500      | 32       | 5.09%   |
| Unknown        | 29       | 4.61%   |
| 1501-2000      | 20       | 3.18%   |
| 301-350        | 14       | 2.23%   |
| 801-900        | 12       | 1.91%   |
| 351-400        | 12       | 1.91%   |
| 901-1000       | 3        | 0.48%   |
| More than 2000 | 1        | 0.16%   |
| 201-300        | 1        | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 425      | 73.66%  |
| 16/10   | 71       | 12.31%  |
| 21/9    | 27       | 4.68%   |
| Unknown | 21       | 3.64%   |
| 5/4     | 19       | 3.29%   |
| 32/9    | 4        | 0.69%   |
| 4/3     | 3        | 0.52%   |
| 3/2     | 3        | 0.52%   |
| 6/5     | 1        | 0.17%   |
| 1.96    | 1        | 0.17%   |
| 1.00    | 1        | 0.17%   |
| 0.25    | 1        | 0.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 222      | 34.74%  |
| 301-350        | 96       | 15.02%  |
| 351-500        | 91       | 14.24%  |
| 151-200        | 59       | 9.23%   |
| 251-300        | 44       | 6.89%   |
| More than 1000 | 41       | 6.42%   |
| Unknown        | 29       | 4.54%   |
| 501-1000       | 27       | 4.23%   |
| 141-150        | 24       | 3.76%   |
| 101-110        | 4        | 0.63%   |
| 51-60          | 1        | 0.16%   |
| 131-140        | 1        | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 359      | 61.05%  |
| 101-120       | 104      | 17.69%  |
| 1-50          | 47       | 7.99%   |
| 121-160       | 39       | 6.63%   |
| Unknown       | 29       | 4.93%   |
| 161-240       | 9        | 1.53%   |
| More than 240 | 1        | 0.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 391      | 66.5%   |
| 2     | 152      | 25.85%  |
| 0     | 29       | 4.93%   |
| 3     | 12       | 2.04%   |
| 4     | 4        | 0.68%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 351      | 41.99%  |
| Intel                           | 277      | 33.13%  |
| Qualcomm Atheros                | 43       | 5.14%   |
| Broadcom                        | 23       | 2.75%   |
| Ralink Technology               | 20       | 2.39%   |
| TP-Link                         | 16       | 1.91%   |
| MediaTek                        | 14       | 1.67%   |
| Aquantia                        | 10       | 1.2%    |
| Ralink                          | 9        | 1.08%   |
| Qualcomm Atheros Communications | 6        | 0.72%   |
| Huawei Technologies             | 6        | 0.72%   |
| ASIX Electronics                | 6        | 0.72%   |
| Samsung Electronics             | 5        | 0.6%    |
| NetGear                         | 5        | 0.6%    |
| Nvidia                          | 3        | 0.36%   |
| Edimax Technology               | 3        | 0.36%   |
| D-Link                          | 3        | 0.36%   |
| Belkin Components               | 3        | 0.36%   |
| Xiaomi                          | 2        | 0.24%   |
| Wilocity                        | 2        | 0.24%   |
| VIA Technologies                | 2        | 0.24%   |
| Solarflare Communications       | 2        | 0.24%   |
| Qualcomm                        | 2        | 0.24%   |
| Marvell Technology Group        | 2        | 0.24%   |
| DisplayLink                     | 2        | 0.24%   |
| ASUSTek Computer                | 2        | 0.24%   |
| ZyXEL Communications            | 1        | 0.12%   |
| U-Blox                          | 1        | 0.12%   |
| Seeed Technology                | 1        | 0.12%   |
| QinHeng Electronics             | 1        | 0.12%   |
| OPPO Electronics                | 1        | 0.12%   |
| Motorola PCS                    | 1        | 0.12%   |
| Microsoft                       | 1        | 0.12%   |
| Mercucys                        | 1        | 0.12%   |
| Mellanox Technologies           | 1        | 0.12%   |
| LSI                             | 1        | 0.12%   |
| Linksys                         | 1        | 0.12%   |
| LG Electronics                  | 1        | 0.12%   |
| D-Link System                   | 1        | 0.12%   |
| Bose                            | 1        | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 262      | 26.49%  |
| Realtek RTL8125 2.5GbE Controller                                              | 45       | 4.55%   |
| Intel I211 Gigabit Network Connection                                          | 44       | 4.45%   |
| Intel Ethernet Controller I225-V                                               | 36       | 3.64%   |
| Intel Wi-Fi 6 AX200                                                            | 31       | 3.13%   |
| Intel Ethernet Connection (2) I219-V                                           | 25       | 2.53%   |
| Intel Ethernet Connection I217-LM                                              | 19       | 1.92%   |
| Intel Ethernet Connection (7) I219-V                                           | 19       | 1.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 18       | 1.82%   |
| Intel Ethernet Connection (2) I218-V                                           | 13       | 1.31%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                      | 12       | 1.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 11       | 1.11%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 11       | 1.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 10       | 1.01%   |
| Realtek 802.11ac NIC                                                           | 10       | 1.01%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 10       | 1.01%   |
| Intel Alder Lake-S PCH CNVi WiFi                                               | 9        | 0.91%   |
| Intel 82579V Gigabit Network Connection                                        | 9        | 0.91%   |
| Intel 82574L Gigabit Network Connection                                        | 9        | 0.91%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 8        | 0.81%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                        | 8        | 0.81%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                        | 8        | 0.81%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                   | 8        | 0.81%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 7        | 0.71%   |
| Intel I210 Gigabit Network Connection                                          | 7        | 0.71%   |
| Intel Ethernet Connection (14) I219-V                                          | 7        | 0.71%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 7        | 0.71%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 7        | 0.71%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 6        | 0.61%   |
| Ralink RT5370 Wireless Adapter                                                 | 6        | 0.61%   |
| Ralink MT7601U Wireless Adapter                                                | 6        | 0.61%   |
| Qualcomm Atheros AR9271 802.11n                                                | 6        | 0.61%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                     | 5        | 0.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 5        | 0.51%   |
| Intel Wireless 3165                                                            | 5        | 0.51%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                              | 5        | 0.51%   |
| Intel Ethernet Connection (2) I219-LM                                          | 5        | 0.51%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 5        | 0.51%   |
| Huawei FOA-LX9                                                                 | 5        | 0.51%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 5        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 109      | 34.28%  |
| Realtek Semiconductor           | 81       | 25.47%  |
| Qualcomm Atheros                | 23       | 7.23%   |
| Ralink Technology               | 20       | 6.29%   |
| Broadcom                        | 17       | 5.35%   |
| TP-Link                         | 16       | 5.03%   |
| MediaTek                        | 12       | 3.77%   |
| Ralink                          | 9        | 2.83%   |
| Qualcomm Atheros Communications | 6        | 1.89%   |
| NetGear                         | 5        | 1.57%   |
| Edimax Technology               | 3        | 0.94%   |
| D-Link                          | 3        | 0.94%   |
| Belkin Components               | 3        | 0.94%   |
| Wilocity                        | 2        | 0.63%   |
| ASUSTek Computer                | 2        | 0.63%   |
| ZyXEL Communications            | 1        | 0.31%   |
| Microsoft                       | 1        | 0.31%   |
| Mercucys                        | 1        | 0.31%   |
| Linksys                         | 1        | 0.31%   |
| LG Electronics                  | 1        | 0.31%   |
| D-Link System                   | 1        | 0.31%   |
| Acer Peripherals (now BenQ)     | 1        | 0.31%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                           | 31       | 9.54%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]     | 12       | 3.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 11       | 3.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 11       | 3.38%   |
| Realtek 802.11ac NIC                                          | 10       | 3.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 10       | 3.08%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 9        | 2.77%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 8        | 2.46%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 8        | 2.46%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]       | 8        | 2.46%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter  | 8        | 2.46%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 7        | 2.15%   |
| Ralink RT5370 Wireless Adapter                                | 6        | 1.85%   |
| Ralink MT7601U Wireless Adapter                               | 6        | 1.85%   |
| Qualcomm Atheros AR9271 802.11n                               | 6        | 1.85%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                    | 5        | 1.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 5        | 1.54%   |
| Intel Wireless 3165                                           | 5        | 1.54%   |
| Intel Raptor Lake-S PCH CNVi WiFi                             | 5        | 1.54%   |
| Intel Comet Lake PCH CNVi WiFi                                | 5        | 1.54%   |
| TP-Link 802.11ac WLAN Adapter                                 | 4        | 1.23%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter               | 4        | 1.23%   |
| Realtek 802.11ac WLAN Adapter                                 | 4        | 1.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 4        | 1.23%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter              | 4        | 1.23%   |
| Intel Wireless 7260                                           | 4        | 1.23%   |
| TP-Link 802.11ac NIC                                          | 3        | 0.92%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 3        | 0.92%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                       | 3        | 0.92%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 3        | 0.92%   |
| Ralink RT2870/RT3070 Wireless Adapter                         | 3        | 0.92%   |
| NetGear A6210                                                 | 3        | 0.92%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 3        | 0.92%   |
| Intel Wireless 8265 / 8275                                    | 3        | 0.92%   |
| Intel Wireless 8260                                           | 3        | 0.92%   |
| Intel Wireless 7265                                           | 3        | 0.92%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter            | 2        | 0.62%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 2        | 0.62%   |
| TP-Link Archer T4U ver.3                                      | 2        | 0.62%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                        | 2        | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 322      | 50.79%  |
| Intel                     | 234      | 36.91%  |
| Qualcomm Atheros          | 22       | 3.47%   |
| Aquantia                  | 10       | 1.58%   |
| Broadcom                  | 9        | 1.42%   |
| Huawei Technologies       | 6        | 0.95%   |
| ASIX Electronics          | 6        | 0.95%   |
| Samsung Electronics       | 4        | 0.63%   |
| Nvidia                    | 3        | 0.47%   |
| Xiaomi                    | 2        | 0.32%   |
| VIA Technologies          | 2        | 0.32%   |
| Solarflare Communications | 2        | 0.32%   |
| Qualcomm                  | 2        | 0.32%   |
| MediaTek                  | 2        | 0.32%   |
| Marvell Technology Group  | 2        | 0.32%   |
| DisplayLink               | 2        | 0.32%   |
| OPPO Electronics          | 1        | 0.16%   |
| Motorola PCS              | 1        | 0.16%   |
| Mellanox Technologies     | 1        | 0.16%   |
| American Megatrends       | 1        | 0.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 262      | 39.88%  |
| Realtek RTL8125 2.5GbE Controller                                              | 45       | 6.85%   |
| Intel I211 Gigabit Network Connection                                          | 44       | 6.7%    |
| Intel Ethernet Controller I225-V                                               | 36       | 5.48%   |
| Intel Ethernet Connection (2) I219-V                                           | 25       | 3.81%   |
| Intel Ethernet Connection I217-LM                                              | 19       | 2.89%   |
| Intel Ethernet Connection (7) I219-V                                           | 19       | 2.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 18       | 2.74%   |
| Intel Ethernet Connection (2) I218-V                                           | 13       | 1.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 10       | 1.52%   |
| Intel 82579V Gigabit Network Connection                                        | 9        | 1.37%   |
| Intel 82574L Gigabit Network Connection                                        | 9        | 1.37%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 7        | 1.07%   |
| Intel I210 Gigabit Network Connection                                          | 7        | 1.07%   |
| Intel Ethernet Connection (14) I219-V                                          | 7        | 1.07%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 7        | 1.07%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 6        | 0.91%   |
| Intel Ethernet Connection (2) I219-LM                                          | 5        | 0.76%   |
| Huawei FOA-LX9                                                                 | 5        | 0.76%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 5        | 0.76%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 4        | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 4        | 0.61%   |
| Intel Ethernet Connection I217-V                                               | 4        | 0.61%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 3        | 0.46%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 3        | 0.46%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 3        | 0.46%   |
| Nvidia MCP61 Ethernet                                                          | 3        | 0.46%   |
| Intel Ethernet Connection (7) I219-LM                                          | 3        | 0.46%   |
| Intel Ethernet Connection (12) I219-V                                          | 3        | 0.46%   |
| Intel Ethernet Connection (11) I219-V                                          | 3        | 0.46%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 2        | 0.3%    |
| VIA VT6105/VT6106S [Rhine-III]                                                 | 2        | 0.3%    |
| Solarflare SFC9020 10G Ethernet Controller                                     | 2        | 0.3%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                    | 2        | 0.3%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2        | 0.3%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2        | 0.3%    |
| Qualcomm Airtel 4G                                                             | 2        | 0.3%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 2        | 0.3%    |
| Intel Ethernet Controller I226-V                                               | 2        | 0.3%    |
| Intel Ethernet Connection (2) I218-LM                                          | 2        | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 571      | 65.11%  |
| WiFi     | 300      | 34.21%  |
| Modem    | 6        | 0.68%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 443      | 73.59%  |
| WiFi     | 159      | 26.41%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 342      | 59.27%  |
| 2     | 191      | 33.1%   |
| 3     | 36       | 6.24%   |
| 4     | 3        | 0.52%   |
| 0     | 3        | 0.52%   |
| 6     | 2        | 0.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 395      | 67.99%  |
| Yes  | 186      | 32.01%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 103      | 39.62%  |
| Cambridge Silicon Radio         | 60       | 23.08%  |
| Realtek Semiconductor           | 24       | 9.23%   |
| ASUSTek Computer                | 18       | 6.92%   |
| MediaTek                        | 12       | 4.62%   |
| Broadcom                        | 12       | 4.62%   |
| IMC Networks                    | 8        | 3.08%   |
| TP-Link                         | 6        | 2.31%   |
| Qualcomm Atheros Communications | 4        | 1.54%   |
| Edimax Technology               | 3        | 1.15%   |
| SiW                             | 2        | 0.77%   |
| Apple                           | 2        | 0.77%   |
| Realtek                         | 1        | 0.38%   |
| Ralink                          | 1        | 0.38%   |
| Foxconn / Hon Hai               | 1        | 0.38%   |
| Dynex                           | 1        | 0.38%   |
| D-Link                          | 1        | 0.38%   |
| Conwise Technology              | 1        | 0.38%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 60       | 22.9%   |
| Intel AX200 Bluetooth                                    | 30       | 11.45%  |
| Realtek Bluetooth Radio                                  | 19       | 7.25%   |
| Intel Bluetooth wireless interface                       | 15       | 5.73%   |
| MediaTek Wireless_Device                                 | 12       | 4.58%   |
| Intel AX211 Bluetooth                                    | 11       | 4.2%    |
| Intel AX210 Bluetooth                                    | 11       | 4.2%    |
| Intel Wireless-AC 3168 Bluetooth                         | 10       | 3.82%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 10       | 3.82%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 9        | 3.44%   |
| Intel AX201 Bluetooth                                    | 8        | 3.05%   |
| IMC Networks Bluetooth Radio                             | 7        | 2.67%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 7        | 2.67%   |
| ASUS ASUS USB-BT500                                      | 7        | 2.67%   |
| TP-Link TP-Link Bluetooth USB Adapter                    | 6        | 2.29%   |
| Realtek  Bluetooth 4.2 Adapter                           | 5        | 1.91%   |
| Qualcomm Atheros  Bluetooth Device                       | 3        | 1.15%   |
| SiW SiW                                                  | 2        | 0.76%   |
| ASUS Qualcomm Bluetooth 4.1                              | 2        | 0.76%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE    | 2        | 0.76%   |
| ASUS Bluetooth Device                                    | 2        | 0.76%   |
| ASUS BCM20702A0                                          | 2        | 0.76%   |
| Apple Bluetooth Host Controller                          | 2        | 0.76%   |
| Realtek Bluetooth Radio                                  | 1        | 0.38%   |
| Ralink RT3290 Bluetooth                                  | 1        | 0.38%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 1        | 0.38%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 1        | 0.38%   |
| IMC Networks Wireless_Device                             | 1        | 0.38%   |
| Foxconn / Hon Hai Wireless_Device                        | 1        | 0.38%   |
| Edimax Wi-Fi AC600 Bluetooth4.0 USB Adapter              | 1        | 0.38%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter  | 1        | 0.38%   |
| Edimax Bluetooth Adapter                                 | 1        | 0.38%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 0.38%   |
| D-Link DBT-122 Bluetooth adapter                         | 1        | 0.38%   |
| Conwise CW6622                                           | 1        | 0.38%   |
| Broadcom HP Bluethunder                                  | 1        | 0.38%   |
| Broadcom Bluetooth Controller                            | 1        | 0.38%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 UHE Dongle      | 1        | 0.38%   |
| Broadcom BCM43142 Bluetooth 4.0                          | 1        | 0.38%   |
| Broadcom BCM2045 Bluetooth                               | 1        | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 342      | 31.75%  |
| AMD                                          | 277      | 25.72%  |
| Nvidia                                       | 275      | 25.53%  |
| C-Media Electronics                          | 29       | 2.69%   |
| Logitech                                     | 10       | 0.93%   |
| JMTek                                        | 10       | 0.93%   |
| Micro Star International                     | 9        | 0.84%   |
| GN Netcom                                    | 9        | 0.84%   |
| Generalplus Technology                       | 8        | 0.74%   |
| Creative Labs                                | 8        | 0.74%   |
| Texas Instruments                            | 7        | 0.65%   |
| Kingston Technology                          | 5        | 0.46%   |
| Corsair                                      | 5        | 0.46%   |
| VIA Technologies                             | 4        | 0.37%   |
| Focusrite-Novation                           | 4        | 0.37%   |
| ASUSTek Computer                             | 4        | 0.37%   |
| Tenx Technology                              | 3        | 0.28%   |
| SteelSeries ApS                              | 3        | 0.28%   |
| Samson Technologies                          | 3        | 0.28%   |
| Razer USA                                    | 3        | 0.28%   |
| M-Audio                                      | 3        | 0.28%   |
| Blue Microphones                             | 3        | 0.28%   |
| Nordic Semiconductor ASA                     | 2        | 0.19%   |
| Medeli Electronics                           | 2        | 0.19%   |
| KORG                                         | 2        | 0.19%   |
| Hewlett-Packard                              | 2        | 0.19%   |
| BY EDIFIER                                   | 2        | 0.19%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.09%   |
| ZOOM                                         | 1        | 0.09%   |
| Zhaoxin                                      | 1        | 0.09%   |
| Yamaha                                       | 1        | 0.09%   |
| Veho                                         | 1        | 0.09%   |
| Unknown                                      | 1        | 0.09%   |
| TerraTec Electronic                          | 1        | 0.09%   |
| TEAC                                         | 1        | 0.09%   |
| ShanWan                                      | 1        | 0.09%   |
| Schiit Audio                                 | 1        | 0.09%   |
| Roland                                       | 1        | 0.09%   |
| RODE Microphones                             | 1        | 0.09%   |
| RME                                          | 1        | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 67       | 5.32%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 52       | 4.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 45       | 3.57%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 39       | 3.1%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 39       | 3.1%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 36       | 2.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 35       | 2.78%   |
| Nvidia GP107GL High Definition Audio Controller                            | 34       | 2.7%    |
| Intel 200 Series PCH HD Audio                                              | 31       | 2.46%   |
| Intel Cannon Lake PCH cAVS                                                 | 28       | 2.22%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 28       | 2.22%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 27       | 2.14%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 26       | 2.06%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 26       | 2.06%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 25       | 1.98%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 22       | 1.75%   |
| Nvidia GP104 High Definition Audio Controller                              | 21       | 1.67%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 18       | 1.43%   |
| Nvidia TU116 High Definition Audio Controller                              | 16       | 1.27%   |
| Intel Alder Lake-S HD Audio Controller                                     | 16       | 1.27%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 16       | 1.27%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 15       | 1.19%   |
| Nvidia GP106 High Definition Audio Controller                              | 14       | 1.11%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 14       | 1.11%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 13       | 1.03%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 13       | 1.03%   |
| Nvidia TU104 HD Audio Controller                                           | 12       | 0.95%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 12       | 0.95%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 12       | 0.95%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 11       | 0.87%   |
| Nvidia TU106 High Definition Audio Controller                              | 11       | 0.87%   |
| Nvidia GP108 High Definition Audio Controller                              | 11       | 0.87%   |
| Nvidia GA106 High Definition Audio Controller                              | 11       | 0.87%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 11       | 0.87%   |
| AMD FCH Azalia Controller                                                  | 11       | 0.87%   |
| Nvidia GF119 HDMI Audio Controller                                         | 10       | 0.79%   |
| Nvidia High Definition Audio Controller                                    | 9        | 0.71%   |
| Nvidia GM204 High Definition Audio Controller                              | 9        | 0.71%   |
| Nvidia GF108 High Definition Audio Controller                              | 9        | 0.71%   |
| Nvidia GA104 High Definition Audio Controller                              | 9        | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Kingston                   | 78       | 21.37%  |
| Corsair                    | 64       | 17.53%  |
| G.Skill                    | 45       | 12.33%  |
| Unknown                    | 32       | 8.77%   |
| Samsung Electronics        | 30       | 8.22%   |
| Crucial                    | 28       | 7.67%   |
| Micron Technology          | 18       | 4.93%   |
| SK hynix                   | 17       | 4.66%   |
| Team                       | 7        | 1.92%   |
| Ramaxel Technology         | 5        | 1.37%   |
| Patriot                    | 5        | 1.37%   |
| Unknown                    | 5        | 1.37%   |
| A-DATA Technology          | 4        | 1.1%    |
| PNY                        | 3        | 0.82%   |
| AMD                        | 3        | 0.82%   |
| Transcend                  | 2        | 0.55%   |
| Smart                      | 2        | 0.55%   |
| Silicon Power              | 2        | 0.55%   |
| Nanya Technology           | 2        | 0.55%   |
| Avant                      | 2        | 0.55%   |
| Xi'an UniIC Semiconductors | 1        | 0.27%   |
| V-Color                    | 1        | 0.27%   |
| Unknown (ABCD)             | 1        | 0.27%   |
| Unifosa                    | 1        | 0.27%   |
| Teikon                     | 1        | 0.27%   |
| Qumo                       | 1        | 0.27%   |
| Neo Forza                  | 1        | 0.27%   |
| Lexar                      | 1        | 0.27%   |
| Kingmax                    | 1        | 0.27%   |
| Elpida                     | 1        | 0.27%   |
| Atermiter                  | 1        | 0.27%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 8        | 1.95%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 7        | 1.71%   |
| Unknown                                                | 5        | 1.22%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s | 4        | 0.98%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 3        | 0.73%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s   | 3        | 0.73%   |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s | 3        | 0.73%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s  | 3        | 0.73%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 4000MT/s    | 3        | 0.73%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3600MT/s   | 3        | 0.73%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s    | 3        | 0.73%   |
| G.Skill RAM F3-1600C9-8GXM 8GB DIMM DDR3 1867MT/s      | 3        | 0.73%   |
| Corsair RAM CMK32GX4M2Z3600C18 16GB DIMM DDR4 3800MT/s | 3        | 0.73%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s  | 3        | 0.73%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s              | 2        | 0.49%   |
| Unknown RAM Module 2GB DIMM 400MT/s                    | 2        | 0.49%   |
| Unknown RAM 3600 C20 Series 32GB DIMM DDR4 3666MT/s    | 2        | 0.49%   |
| Unknown RAM 1866 CL10 Series 8192MB DIMM DDR3 933MT/s  | 2        | 0.49%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s    | 2        | 0.49%   |
| Team RAM TEAMGROUP-UD4-2666 4GB DIMM DDR4              | 2        | 0.49%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s   | 2        | 0.49%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s              | 2        | 0.49%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 3200MT/s  | 2        | 0.49%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s    | 2        | 0.49%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s    | 2        | 0.49%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s    | 2        | 0.49%   |
| Ramaxel RAM RMR5040ED58E9W1600 4GB DIMM DDR3 1600MT/s  | 2        | 0.49%   |
| Ramaxel RAM RMR5030EF68F9W1600 4GB DIMM DDR3 1600MT/s  | 2        | 0.49%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8GB DIMM DDR4 3600MT/s    | 2        | 0.49%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s         | 2        | 0.49%   |
| Micron RAM 8ATF1G64AZ-2G6E1 8GB DIMM DDR4 2667MT/s     | 2        | 0.49%   |
| Micron RAM 16JTF1G64AZ-1G6E1 8GB DIMM DDR3 1600MT/s    | 2        | 0.49%   |
| Kingston RAM KHX2666C13/8GX 8GB DIMM DDR4 3200MT/s     | 2        | 0.49%   |
| Kingston RAM KHX2400C11D3/4GX 4GB DIMM DDR3 2400MT/s   | 2        | 0.49%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1800MT/s    | 2        | 0.49%   |
| Kingston RAM KF556C40-32 32GB DIMM DDR5 5808MT/s       | 2        | 0.49%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s  | 2        | 0.49%   |
| Kingston RAM 99U5471-002.A01LF 2GB DIMM DDR3 1334MT/s  | 2        | 0.49%   |
| Kingston RAM 9905471-079.A00LF 8GB DIMM DDR3 1600MT/s  | 2        | 0.49%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3866MT/s | 2        | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 183      | 56.48%  |
| DDR3    | 87       | 26.85%  |
| DDR5    | 18       | 5.56%   |
| Unknown | 18       | 5.56%   |
| SDRAM   | 8        | 2.47%   |
| DDR2    | 6        | 1.85%   |
| LPDDR4  | 2        | 0.62%   |
| DRAM    | 1        | 0.31%   |
| DDR     | 1        | 0.31%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 306      | 95.92%  |
| SODIMM       | 11       | 3.45%   |
| Row Of Chips | 1        | 0.31%   |
| RIMM         | 1        | 0.31%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 138      | 38.66%  |
| 16384 | 88       | 24.65%  |
| 4096  | 63       | 17.65%  |
| 2048  | 35       | 9.8%    |
| 32768 | 31       | 8.68%   |
| 24576 | 1        | 0.28%   |
| 1024  | 1        | 0.28%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 53       | 14.25%  |
| 3200  | 45       | 12.1%   |
| 1333  | 34       | 9.14%   |
| 3600  | 32       | 8.6%    |
| 2400  | 27       | 7.26%   |
| 2667  | 22       | 5.91%   |
| 2133  | 20       | 5.38%   |
| 2666  | 14       | 3.76%   |
| 3800  | 10       | 2.69%   |
| 3000  | 8        | 2.15%   |
| 1867  | 8        | 2.15%   |
| 4800  | 6        | 1.61%   |
| 4000  | 6        | 1.61%   |
| 1066  | 6        | 1.61%   |
| 6000  | 5        | 1.34%   |
| 3666  | 5        | 1.34%   |
| 2933  | 5        | 1.34%   |
| 1866  | 5        | 1.34%   |
| 800   | 5        | 1.34%   |
| 3066  | 4        | 1.08%   |
| 2800  | 4        | 1.08%   |
| 1648  | 4        | 1.08%   |
| 3333  | 3        | 0.81%   |
| 400   | 3        | 0.81%   |
| 5808  | 2        | 0.54%   |
| 5800  | 2        | 0.54%   |
| 3866  | 2        | 0.54%   |
| 3733  | 2        | 0.54%   |
| 3534  | 2        | 0.54%   |
| 3466  | 2        | 0.54%   |
| 3400  | 2        | 0.54%   |
| 3266  | 2        | 0.54%   |
| 3100  | 2        | 0.54%   |
| 1800  | 2        | 0.54%   |
| 1334  | 2        | 0.54%   |
| 52217 | 1        | 0.27%   |
| 5600  | 1        | 0.27%   |
| 5354  | 1        | 0.27%   |
| 5200  | 1        | 0.27%   |
| 4133  | 1        | 0.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 10       | 30.3%   |
| Seiko Epson           | 5        | 15.15%  |
| Brother Industries    | 5        | 15.15%  |
| Samsung Electronics   | 3        | 9.09%   |
| Canon                 | 3        | 9.09%   |
| Zebra                 | 1        | 3.03%   |
| Xerox                 | 1        | 3.03%   |
| Prolific Technology   | 1        | 3.03%   |
| Lexmark International | 1        | 3.03%   |
| Kyocera               | 1        | 3.03%   |
| Dymo-CoStar           | 1        | 3.03%   |
| Datamax-O'Neil        | 1        | 3.03%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Samsung M2070 Series                  | 3        | 9.09%   |
| Seiko Epson L360 Series               | 2        | 6.06%   |
| Brother MFC-J460DW                    | 2        | 6.06%   |
| Zebra Thrmal 2844                     | 1        | 3.03%   |
| Xerox Phaser 3140 and 3155            | 1        | 3.03%   |
| Seiko Epson XP-3100 Series            | 1        | 3.03%   |
| Seiko Epson XP-2150 Series            | 1        | 3.03%   |
| Seiko Epson L3110 Series              | 1        | 3.03%   |
| Prolific PL2305 Parallel Port         | 1        | 3.03%   |
| Lexmark International CX510de         | 1        | 3.03%   |
| Kyocera Mita FS-820                   | 1        | 3.03%   |
| HP OfficeJet Pro 7730 series          | 1        | 3.03%   |
| HP OfficeJet 5500 series              | 1        | 3.03%   |
| HP LaserJet P2015 series              | 1        | 3.03%   |
| HP LaserJet 1022                      | 1        | 3.03%   |
| HP LaserJet 1012                      | 1        | 3.03%   |
| HP ENVY Photo 6200 series             | 1        | 3.03%   |
| HP ENVY 4500 series                   | 1        | 3.03%   |
| HP DeskJet D2300                      | 1        | 3.03%   |
| HP DeskJet 3630 series                | 1        | 3.03%   |
| HP ColorLaserJet M253-M254            | 1        | 3.03%   |
| Dymo-CoStar LabelWriter 450           | 1        | 3.03%   |
| Datamax-O'Neil Datamax E-4304         | 1        | 3.03%   |
| Canon PIXMA MX470 Series              | 1        | 3.03%   |
| Canon PIXMA MG5500 Series             | 1        | 3.03%   |
| Canon LaserShot LBP-1120 Printer      | 1        | 3.03%   |
| Brother PT-P700 P-touch Label Printer | 1        | 3.03%   |
| Brother MFC-L2750DW series            | 1        | 3.03%   |
| Brother DCP-7065DN                    | 1        | 3.03%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| Canon          | 7        | 70%     |
| Seiko Epson    | 2        | 20%     |
| Mustek Systems | 1        | 10%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40      | 2        | 20%     |
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1        | 10%     |
| Seiko Epson GT-6600U [Perfection 610]       | 1        | 10%     |
| Mustek Systems ScanExpress A3 USB 1200 PRO  | 1        | 10%     |
| Canon CanoScan N670U/N676U/LiDE 20          | 1        | 10%     |
| Canon CanoScan N1240U/LiDE 30               | 1        | 10%     |
| Canon CanoScan LiDE 220                     | 1        | 10%     |
| Canon CanoScan LiDE 210                     | 1        | 10%     |
| Canon CanoScan LiDE 110                     | 1        | 10%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 66       | 41.51%  |
| Microdia                      | 13       | 8.18%   |
| Sunplus Innovation Technology | 8        | 5.03%   |
| Microsoft                     | 7        | 4.4%    |
| Samsung Electronics           | 6        | 3.77%   |
| Generalplus Technology        | 6        | 3.77%   |
| Realtek Semiconductor         | 5        | 3.14%   |
| KYE Systems (Mouse Systems)   | 4        | 2.52%   |
| Cubeternet                    | 4        | 2.52%   |
| Creative Technology           | 3        | 1.89%   |
| Chicony Electronics           | 3        | 1.89%   |
| Alcor Micro                   | 3        | 1.89%   |
| Z-Star Microelectronics       | 2        | 1.26%   |
| Unknown                       | 2        | 1.26%   |
| Trust                         | 2        | 1.26%   |
| Razer USA                     | 2        | 1.26%   |
| MacroSilicon                  | 2        | 1.26%   |
| Jieli Technology              | 2        | 1.26%   |
| ARC International             | 2        | 1.26%   |
| YGTek                         | 1        | 0.63%   |
| SunplusIT                     | 1        | 0.63%   |
| Sonix Technology              | 1        | 0.63%   |
| Silicon Motion                | 1        | 0.63%   |
| SHENZHEN EMEET TECHNOLOGY     | 1        | 0.63%   |
| Point Grey Research           | 1        | 0.63%   |
| LG Electronics                | 1        | 0.63%   |
| IMC Networks                  | 1        | 0.63%   |
| Hewlett-Packard               | 1        | 0.63%   |
| Google                        | 1        | 0.63%   |
| GEMBIRD                       | 1        | 0.63%   |
| eMeet                         | 1        | 0.63%   |
| Asuscom Network               | 1        | 0.63%   |
| Apple                         | 1        | 0.63%   |
| Anker PowerConf C200          | 1        | 0.63%   |
| Anker                         | 1        | 0.63%   |
| 2M UVC CAMERA                 | 1        | 0.63%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                | 18       | 11.18%  |
| Logitech Webcam C270                       | 13       | 8.07%   |
| Samsung Galaxy series, misc. (MTP mode)    | 5        | 3.11%   |
| Microdia Webcam Vitade AF                  | 5        | 3.11%   |
| Microsoft LifeCam HD-3000                  | 4        | 2.48%   |
| Logitech Webcam C170                       | 4        | 2.48%   |
| Logitech HD Webcam C910                    | 4        | 2.48%   |
| Logitech HD Webcam C525                    | 4        | 2.48%   |
| Generalplus GENERAL WEBCAM                 | 4        | 2.48%   |
| Sunplus Full HD webcam                     | 3        | 1.86%   |
| Microdia USB 2.0 Camera                    | 3        | 1.86%   |
| Microdia Integrated Camera                 | 3        | 1.86%   |
| Logitech C922 Pro Stream Webcam            | 3        | 1.86%   |
| Logitech BRIO Ultra HD Webcam              | 3        | 1.86%   |
| Alcor Micro USB 2.0 PC Camera              | 3        | 1.86%   |
| Unknown HD camera                          | 2        | 1.24%   |
| Sunplus UC40M Audio                        | 2        | 1.24%   |
| MacroSilicon USB Video                     | 2        | 1.24%   |
| Logitech Webcam C310                       | 2        | 1.24%   |
| Logitech QuickCam Pro 9000                 | 2        | 1.24%   |
| Logitech HD Webcam C615                    | 2        | 1.24%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera | 2        | 1.24%   |
| Jieli USB PHY 2.0                          | 2        | 1.24%   |
| Generalplus 808 Camera #9 (web-cam mode)   | 2        | 1.24%   |
| Cubeternet USB2.0 Camera                   | 2        | 1.24%   |
| Creative Live! Cam Sync HD [VF0770]        | 2        | 1.24%   |
| ARC International Camera                   | 2        | 1.24%   |
| Z-Star Vimicro USB Camera (Altair)         | 1        | 0.62%   |
| Z-Star Venus USB2.0 Camera                 | 1        | 0.62%   |
| YGTek Webcam                               | 1        | 0.62%   |
| Trust Trust Full HD Webcam                 | 1        | 0.62%   |
| Trust 17676 Webcam                         | 1        | 0.62%   |
| SunplusIT USB 2.0 Camera                   | 1        | 0.62%   |
| Sunplus USB Camera                         | 1        | 0.62%   |
| Sunplus SPCA2281 Web Camera                | 1        | 0.62%   |
| Sunplus ezcap U3 capture-04                | 1        | 0.62%   |
| Sonix USB 2.0 Camera                       | 1        | 0.62%   |
| Silicon Motion 300k Pixel Camera           | 1        | 0.62%   |
| SHENZHEN EMEET TECHNOLOGY eMeet Nova       | 1        | 0.62%   |
| Samsung SlimFit Cam                        | 1        | 0.62%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Synaptics                  | 2        | 40%     |
| Shenzhen Goodix Technology | 1        | 20%     |
| LighTuning Technology      | 1        | 20%     |
| Dell                       | 1        | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Synaptics  WBDI Fingerprint Reader - USB 052   | 2        | 40%     |
| Shenzhen Goodix  Fingerprint Device            | 1        | 20%     |
| LighTuning Fingerprint Sensor                  | 1        | 20%     |
| Dell MS819 Wired Mouse With Fingerprint Reader | 1        | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| OmniKey                   | 2        | 22.22%  |
| Gemalto (was Gemplus)     | 2        | 22.22%  |
| SCM Microsystems          | 1        | 11.11%  |
| Bit4id                    | 1        | 11.11%  |
| Alcor Micro               | 1        | 11.11%  |
| Aladdin Knowledge Systems | 1        | 11.11%  |
| Advanced Card Systems     | 1        | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| SCM Microsystems SCR331 SmartCard Reader          | 1        | 11.11%  |
| OmniKey CardMan 3021 / 3121                       | 1        | 11.11%  |
| OmniKey CardMan 1021                              | 1        | 11.11%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1        | 11.11%  |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader  | 1        | 11.11%  |
| Bit4id miniLector EVO                             | 1        | 11.11%  |
| Alcor Micro AU9540 Smartcard Reader               | 1        | 11.11%  |
| Aladdin Knowledge Systems Token JC                | 1        | 11.11%  |
| Advanced Card Systems ACR122U                     | 1        | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 475      | 80.51%  |
| 1     | 95       | 16.1%   |
| 2     | 17       | 2.88%   |
| 3     | 3        | 0.51%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 41       | 33.06%  |
| Net/wireless             | 34       | 27.42%  |
| Unassigned class         | 14       | 11.29%  |
| Multimedia controller    | 5        | 4.03%   |
| Chipcard                 | 5        | 4.03%   |
| Camera                   | 5        | 4.03%   |
| Bluetooth                | 5        | 4.03%   |
| Communication controller | 4        | 3.23%   |
| Sound                    | 3        | 2.42%   |
| Fingerprint reader       | 3        | 2.42%   |
| Storage/raid             | 1        | 0.81%   |
| Storage/ide              | 1        | 0.81%   |
| Net/ethernet             | 1        | 0.81%   |
| Modem                    | 1        | 0.81%   |
| Card reader              | 1        | 0.81%   |

