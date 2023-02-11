Linux in China - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------

A project to collect tested hardware configurations for Linux in China.

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

Total: 481

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | 3148 NOK                    | [72815c2ab8](https://linux-hardware.org/?probe=72815c2ab8) | Jan 30, 2023 |
| OEM           | KX-01 V1.0                  | [75d9dc396c](https://linux-hardware.org/?probe=75d9dc396c) | Jan 28, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [510b879339](https://linux-hardware.org/?probe=510b879339) | Jan 26, 2023 |
| ASUSTek       | A88XM-PLUS                  | [68fcb008b1](https://linux-hardware.org/?probe=68fcb008b1) | Jan 15, 2023 |
| ASUSTek       | PRIME Z790-P                | [a4fb531cc9](https://linux-hardware.org/?probe=a4fb531cc9) | Jan 13, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [eab87def73](https://linux-hardware.org/?probe=eab87def73) | Jan 12, 2023 |
| ASUSTek       | A88XM-PLUS                  | [a595895c7e](https://linux-hardware.org/?probe=a595895c7e) | Jan 11, 2023 |
| ASUSTek       | PRIME H310I-PLUS R2.0       | [56544d809f](https://linux-hardware.org/?probe=56544d809f) | Jan 11, 2023 |
| AZW           | EQ59                        | [3eb85d9ee5](https://linux-hardware.org/?probe=3eb85d9ee5) | Jan 10, 2023 |
| Intel         | JSL MRD                     | [f567ba0a06](https://linux-hardware.org/?probe=f567ba0a06) | Dec 24, 2022 |
| MSI           | H510M BOMBER                | [bb7a4c8457](https://linux-hardware.org/?probe=bb7a4c8457) | Dec 23, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [37de981132](https://linux-hardware.org/?probe=37de981132) | Dec 21, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [b270e219ba](https://linux-hardware.org/?probe=b270e219ba) | Dec 20, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [525bdfe9c0](https://linux-hardware.org/?probe=525bdfe9c0) | Dec 20, 2022 |
| Dell          | 0J1C3P A00                  | [1bd9b328b2](https://linux-hardware.org/?probe=1bd9b328b2) | Dec 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d872d58e4c](https://linux-hardware.org/?probe=d872d58e4c) | Dec 15, 2022 |
| ASUSTek       | Z10PH-D16 Series            | [18911cf243](https://linux-hardware.org/?probe=18911cf243) | Dec 13, 2022 |
| Dell          | 0NK5PH A00                  | [08b0ff8839](https://linux-hardware.org/?probe=08b0ff8839) | Dec 12, 2022 |
| Gigabyte      | X299 UD4 Pro-CF             | [89da872b13](https://linux-hardware.org/?probe=89da872b13) | Dec 12, 2022 |
| Huanan        | X99-T8D V1.0                | [e4bd42a26b](https://linux-hardware.org/?probe=e4bd42a26b) | Dec 09, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [b0bf36f700](https://linux-hardware.org/?probe=b0bf36f700) | Dec 01, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [f5a5a30379](https://linux-hardware.org/?probe=f5a5a30379) | Dec 01, 2022 |
| ONDA          | M3 miniPC VER               | [35f4c45eb5](https://linux-hardware.org/?probe=35f4c45eb5) | Dec 01, 2022 |
| Pegatron      | BYT-X1                      | [edadb85201](https://linux-hardware.org/?probe=edadb85201) | Nov 30, 2022 |
| Pegatron      | BYT-X1                      | [b248df8671](https://linux-hardware.org/?probe=b248df8671) | Nov 30, 2022 |
| ASRock        | B450M Pro4-F                | [8d0514a0df](https://linux-hardware.org/?probe=8d0514a0df) | Nov 28, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [f168cc5b93](https://linux-hardware.org/?probe=f168cc5b93) | Nov 27, 2022 |
| Gigabyte      | X299 UD4 Pro-CF             | [4ef7a46399](https://linux-hardware.org/?probe=4ef7a46399) | Nov 25, 2022 |
| ASUSTek       | TUF X299 MARK 2             | [d742abf044](https://linux-hardware.org/?probe=d742abf044) | Nov 23, 2022 |
| ASUSTek       | TUF X299 MARK 2             | [cac488b207](https://linux-hardware.org/?probe=cac488b207) | Nov 21, 2022 |
| GuoGuang      | IC2M1028N-3                 | [32351ceb62](https://linux-hardware.org/?probe=32351ceb62) | Nov 16, 2022 |
| HP            | 212B                        | [e1c7e7693e](https://linux-hardware.org/?probe=e1c7e7693e) | Nov 16, 2022 |
| ASUSTek       | P8Z68-V LX                  | [a3c41dcc96](https://linux-hardware.org/?probe=a3c41dcc96) | Nov 16, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [340f38c8e2](https://linux-hardware.org/?probe=340f38c8e2) | Nov 15, 2022 |
| Lenovo        | 3716 SDK0K17763 WIN 1801... | [93c2091f01](https://linux-hardware.org/?probe=93c2091f01) | Nov 15, 2022 |
| Dell          | 0ND1Y4 A02                  | [726074bce6](https://linux-hardware.org/?probe=726074bce6) | Nov 09, 2022 |
| Dell          | 0ND1Y4 A02                  | [3ac38eb9be](https://linux-hardware.org/?probe=3ac38eb9be) | Nov 09, 2022 |
| Unknown       | Unknown                     | [ff3d968ae9](https://linux-hardware.org/?probe=ff3d968ae9) | Nov 08, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [0fa75a005b](https://linux-hardware.org/?probe=0fa75a005b) | Nov 08, 2022 |
| ASUSTek       | Maximus VII HERO            | [010836bb97](https://linux-hardware.org/?probe=010836bb97) | Nov 07, 2022 |
| IBM           | M97IP SIT                   | [78703d62ae](https://linux-hardware.org/?probe=78703d62ae) | Nov 07, 2022 |
| ONDA          | M3 miniPC VER               | [d485a7def3](https://linux-hardware.org/?probe=d485a7def3) | Nov 07, 2022 |
| IBM           | M97IP SIT                   | [0301b99674](https://linux-hardware.org/?probe=0301b99674) | Nov 07, 2022 |
| MSI           | 880GMS-E41                  | [2f53fa13ed](https://linux-hardware.org/?probe=2f53fa13ed) | Nov 06, 2022 |
| Unknown       | Unknown                     | [aa1a843244](https://linux-hardware.org/?probe=aa1a843244) | Nov 04, 2022 |
| Unknown       | Unknown                     | [0a55753066](https://linux-hardware.org/?probe=0a55753066) | Nov 04, 2022 |
| Unknown       | Unknown                     | [0e60d35498](https://linux-hardware.org/?probe=0e60d35498) | Nov 04, 2022 |
| Intel         | ChiefRiver                  | [1e1f44f251](https://linux-hardware.org/?probe=1e1f44f251) | Nov 04, 2022 |
| Dell          | 0ND1Y4 A02                  | [9017e31507](https://linux-hardware.org/?probe=9017e31507) | Nov 04, 2022 |
| Intel         | ChiefRiver                  | [64e4630da2](https://linux-hardware.org/?probe=64e4630da2) | Nov 04, 2022 |
| Dell          | 0N0992 A01                  | [6f4decf3b2](https://linux-hardware.org/?probe=6f4decf3b2) | Nov 04, 2022 |
| Unknown       | Unknown                     | [4457bb7b7e](https://linux-hardware.org/?probe=4457bb7b7e) | Nov 03, 2022 |
| Unknown       | Unknown                     | [bc4f9a5a35](https://linux-hardware.org/?probe=bc4f9a5a35) | Nov 02, 2022 |
| Unknown       | Unknown                     | [f87c0b1010](https://linux-hardware.org/?probe=f87c0b1010) | Nov 01, 2022 |
| OEM           | H310MD4                     | [947bf0d86f](https://linux-hardware.org/?probe=947bf0d86f) | Nov 01, 2022 |
| Unknown       | Unknown                     | [0e92fb8c99](https://linux-hardware.org/?probe=0e92fb8c99) | Oct 31, 2022 |
| Unknown       | Unknown                     | [673c23713c](https://linux-hardware.org/?probe=673c23713c) | Oct 30, 2022 |
| Huanan        | H510-D4 V4.0                | [89b298973c](https://linux-hardware.org/?probe=89b298973c) | Oct 30, 2022 |
| Unknown       | Unknown                     | [a517f2e2dd](https://linux-hardware.org/?probe=a517f2e2dd) | Oct 30, 2022 |
| Unknown       | Unknown                     | [03f3800569](https://linux-hardware.org/?probe=03f3800569) | Oct 29, 2022 |
| Unknown       | Unknown                     | [79b9335389](https://linux-hardware.org/?probe=79b9335389) | Oct 26, 2022 |
| Unknown       | Unknown                     | [07a0af33a1](https://linux-hardware.org/?probe=07a0af33a1) | Oct 26, 2022 |
| Unknown       | Unknown                     | [3ba090d9a2](https://linux-hardware.org/?probe=3ba090d9a2) | Oct 26, 2022 |
| Biostar       | H61MLV2                     | [5b6f2b76da](https://linux-hardware.org/?probe=5b6f2b76da) | Oct 25, 2022 |
| Dell          | 0MWYPT A02                  | [cf186994cc](https://linux-hardware.org/?probe=cf186994cc) | Oct 25, 2022 |
| MSI           | Z97S SLI Krait Edition      | [e31e22263a](https://linux-hardware.org/?probe=e31e22263a) | Oct 23, 2022 |
| NORCO         | BPC-7951                    | [7612662684](https://linux-hardware.org/?probe=7612662684) | Oct 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [7afa527ad7](https://linux-hardware.org/?probe=7afa527ad7) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [547c973486](https://linux-hardware.org/?probe=547c973486) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [ca42d57a93](https://linux-hardware.org/?probe=ca42d57a93) | Oct 14, 2022 |
| AMD           | A88                         | [1ee2502537](https://linux-hardware.org/?probe=1ee2502537) | Oct 12, 2022 |
| ASUSTek       | V-P8H67E                    | [b4f0f561d2](https://linux-hardware.org/?probe=b4f0f561d2) | Oct 08, 2022 |
| OEM           | Unknown                     | [306d50f7e3](https://linux-hardware.org/?probe=306d50f7e3) | Oct 03, 2022 |
| OEM           | Unknown                     | [68b7e03b06](https://linux-hardware.org/?probe=68b7e03b06) | Sep 29, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [f750ea8b83](https://linux-hardware.org/?probe=f750ea8b83) | Sep 26, 2022 |
| MSI           | Z97S SLI Krait Edition      | [f35b53ca7c](https://linux-hardware.org/?probe=f35b53ca7c) | Sep 25, 2022 |
| ASRock        | E3V5 Performance Gaming/... | [3653dbd804](https://linux-hardware.org/?probe=3653dbd804) | Sep 20, 2022 |
| AZW           | GK55                        | [9a9019eee6](https://linux-hardware.org/?probe=9a9019eee6) | Sep 19, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [4dce87f7fa](https://linux-hardware.org/?probe=4dce87f7fa) | Sep 16, 2022 |
| Lenovo        | 1036 NO DPK                 | [1b7cb7f0d2](https://linux-hardware.org/?probe=1b7cb7f0d2) | Sep 14, 2022 |
| Lenovo        | 1036 NO DPK                 | [0ac056f016](https://linux-hardware.org/?probe=0ac056f016) | Sep 14, 2022 |
| ONDA          | M3 miniPC VER               | [81ebde1d65](https://linux-hardware.org/?probe=81ebde1d65) | Sep 13, 2022 |
| Colorful T... | H510M-D M.2 V20 V20         | [9b25859acf](https://linux-hardware.org/?probe=9b25859acf) | Sep 11, 2022 |
| MSI           | B450M MORTAR                | [2e0d41f272](https://linux-hardware.org/?probe=2e0d41f272) | Sep 10, 2022 |
| MSI           | B450M MORTAR                | [06ee689632](https://linux-hardware.org/?probe=06ee689632) | Sep 10, 2022 |
| Unknown       | Unknown                     | [a0c1db14a0](https://linux-hardware.org/?probe=a0c1db14a0) | Sep 09, 2022 |
| ONDA          | M3 miniPC VER               | [40f73e6e82](https://linux-hardware.org/?probe=40f73e6e82) | Sep 07, 2022 |
| Dell          | 0NV0M7 A02                  | [23024b776e](https://linux-hardware.org/?probe=23024b776e) | Sep 06, 2022 |
| ASUSTek       | BM6630_BM6330_BP6230        | [d510db88c4](https://linux-hardware.org/?probe=d510db88c4) | Sep 02, 2022 |
| Lenovo        | SHARKBAY NO DPK             | [f872d36cd5](https://linux-hardware.org/?probe=f872d36cd5) | Sep 01, 2022 |
| Unknown       | Unknown                     | [ef43339df1](https://linux-hardware.org/?probe=ef43339df1) | Aug 28, 2022 |
| retsamarre... | Unknown                     | [5bc4dd4776](https://linux-hardware.org/?probe=5bc4dd4776) | Aug 23, 2022 |
| retsamarre... | Unknown                     | [8f8e0f49df](https://linux-hardware.org/?probe=8f8e0f49df) | Aug 23, 2022 |
| MSI           | MAG B660M MORTAR WIFI DD... | [8898d24c48](https://linux-hardware.org/?probe=8898d24c48) | Aug 22, 2022 |
| Biostar       | B550M-SILVER                | [d3a371bce6](https://linux-hardware.org/?probe=d3a371bce6) | Aug 20, 2022 |
| Lenovo        | 3102 SDK0L77767 WIN 3423... | [5d884c320f](https://linux-hardware.org/?probe=5d884c320f) | Aug 16, 2022 |
| MSI           | MAG B550M MORTAR            | [baf348cae9](https://linux-hardware.org/?probe=baf348cae9) | Aug 12, 2022 |
| HP            | 8183                        | [19f5199de8](https://linux-hardware.org/?probe=19f5199de8) | Aug 12, 2022 |
| HP            | 8183                        | [c441ead9f8](https://linux-hardware.org/?probe=c441ead9f8) | Aug 11, 2022 |
| ASRock        | H81M-HDS                    | [1d636956f2](https://linux-hardware.org/?probe=1d636956f2) | Aug 07, 2022 |
| Unknown       | Unknown                     | [7d2ea1146a](https://linux-hardware.org/?probe=7d2ea1146a) | Aug 07, 2022 |
| Unknown       | Unknown                     | [dbafe167dc](https://linux-hardware.org/?probe=dbafe167dc) | Aug 06, 2022 |
| Gigabyte      | B450M GAMING                | [c1d23f2838](https://linux-hardware.org/?probe=c1d23f2838) | Aug 06, 2022 |
| Lenovo        | 102F NO DPK                 | [1a040c2717](https://linux-hardware.org/?probe=1a040c2717) | Aug 04, 2022 |
| Intel         | X99                         | [33e0d23783](https://linux-hardware.org/?probe=33e0d23783) | Aug 04, 2022 |
| Lenovo        | 3133 SDK0J40675 WIN 3305... | [4434d4d78a](https://linux-hardware.org/?probe=4434d4d78a) | Jul 29, 2022 |
| ASUSTek       | F2A55-M LK2 PLUS            | [a0a4abeb19](https://linux-hardware.org/?probe=a0a4abeb19) | Jul 28, 2022 |
| Intel         | D54250WYK H13922-303        | [5ff32931fa](https://linux-hardware.org/?probe=5ff32931fa) | Jul 27, 2022 |
| Gigabyte      | Z690I A ULTRA PLUS D4       | [453b2cce27](https://linux-hardware.org/?probe=453b2cce27) | Jul 22, 2022 |
| X79-1356      | Unknown                     | [2db70d0471](https://linux-hardware.org/?probe=2db70d0471) | Jul 22, 2022 |
| Lenovo        | NOK                         | [a47a727578](https://linux-hardware.org/?probe=a47a727578) | Jul 22, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [6ff44b9490](https://linux-hardware.org/?probe=6ff44b9490) | Jul 15, 2022 |
| MSI           | Z370-OC PRO                 | [2c9d1d78df](https://linux-hardware.org/?probe=2c9d1d78df) | Jul 12, 2022 |
| Colorful T... | H310M-T PRO V21             | [b922e2142b](https://linux-hardware.org/?probe=b922e2142b) | Jul 11, 2022 |
| Unknown       | Unknown                     | [7b1c72c3e7](https://linux-hardware.org/?probe=7b1c72c3e7) | Jul 06, 2022 |
| Gigabyte      | Z87P-D3                     | [2ae62ac227](https://linux-hardware.org/?probe=2ae62ac227) | Jun 30, 2022 |
| MSI           | Z68A-GD80                   | [2e2ca703b0](https://linux-hardware.org/?probe=2e2ca703b0) | Jun 30, 2022 |
| Gigabyte      | EP45-UD3                    | [bb62363ad2](https://linux-hardware.org/?probe=bb62363ad2) | Jun 29, 2022 |
| MSI           | B360M MORTAR                | [607f489961](https://linux-hardware.org/?probe=607f489961) | Jun 25, 2022 |
| Unknown       | Unknown                     | [b3def4c8ad](https://linux-hardware.org/?probe=b3def4c8ad) | Jun 25, 2022 |
| MSI           | MAG B550M MORTAR            | [209001317a](https://linux-hardware.org/?probe=209001317a) | Jun 23, 2022 |
| MAINBRD       | OPS62A-SHA                  | [7c16967701](https://linux-hardware.org/?probe=7c16967701) | Jun 10, 2022 |
| Unknown       | Unknown                     | [2a25ea86fc](https://linux-hardware.org/?probe=2a25ea86fc) | Jun 05, 2022 |
| Unknown       | Unknown                     | [4c36218f66](https://linux-hardware.org/?probe=4c36218f66) | Jun 04, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | [a9c714d138](https://linux-hardware.org/?probe=a9c714d138) | Jun 03, 2022 |
| MAINBRD       | OPS62A-SHA                  | [33201d3794](https://linux-hardware.org/?probe=33201d3794) | Jun 02, 2022 |
| Unknown       | Unknown                     | [bcb55ce8ce](https://linux-hardware.org/?probe=bcb55ce8ce) | Jun 01, 2022 |
| Unknown       | Unknown                     | [24a7b3121f](https://linux-hardware.org/?probe=24a7b3121f) | May 29, 2022 |
| Gigabyte      | X570 GAMING X               | [3ddc17645b](https://linux-hardware.org/?probe=3ddc17645b) | May 29, 2022 |
| Unknown       | Unknown                     | [1da299e36e](https://linux-hardware.org/?probe=1da299e36e) | May 29, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | [91306ce19f](https://linux-hardware.org/?probe=91306ce19f) | May 29, 2022 |
| Intel         | D54250WYK H13922-303        | [59eda31291](https://linux-hardware.org/?probe=59eda31291) | May 24, 2022 |
| MSI           | H97M-P35                    | [2b5866b09d](https://linux-hardware.org/?probe=2b5866b09d) | May 23, 2022 |
| Intel         | HURONRIVER                  | [1ebb900517](https://linux-hardware.org/?probe=1ebb900517) | May 22, 2022 |
| MSI           | B450M-A PRO MAX             | [fce678a9e8](https://linux-hardware.org/?probe=fce678a9e8) | May 21, 2022 |
| Lenovo        | NOK                         | [567c167a97](https://linux-hardware.org/?probe=567c167a97) | May 20, 2022 |
| MAXSUN        | MS-M3A78EL                  | [98d8c5a6ee](https://linux-hardware.org/?probe=98d8c5a6ee) | May 14, 2022 |
| ASUSTek       | TUF Gaming B460-PLUS        | [a83103153b](https://linux-hardware.org/?probe=a83103153b) | May 12, 2022 |
| TSINGHUA T... | B460M-HDV                   | [3c126b8a1d](https://linux-hardware.org/?probe=3c126b8a1d) | May 10, 2022 |
| Lenovo        | NO DPK                      | [24340ea9a8](https://linux-hardware.org/?probe=24340ea9a8) | May 06, 2022 |
| Lenovo        | NO DPK                      | [dc8d8b070e](https://linux-hardware.org/?probe=dc8d8b070e) | May 05, 2022 |
| OEM           | V1.0                        | [167ee50568](https://linux-hardware.org/?probe=167ee50568) | Apr 29, 2022 |
| ASRock        | Z170 Gaming K4              | [96b772b4e6](https://linux-hardware.org/?probe=96b772b4e6) | Apr 24, 2022 |
| ASRock        | Z170 Gaming K4              | [81e06a1dcb](https://linux-hardware.org/?probe=81e06a1dcb) | Apr 18, 2022 |
| Gigabyte      | H61M-D2P-B3                 | [c4561b1073](https://linux-hardware.org/?probe=c4561b1073) | Apr 18, 2022 |
| J&W           | J1900T                      | [7c87f17ed7](https://linux-hardware.org/?probe=7c87f17ed7) | Apr 17, 2022 |
| ASRock        | H110M-DVS R2.0              | [aa88339957](https://linux-hardware.org/?probe=aa88339957) | Apr 16, 2022 |
| Lenovo        | MAHOBAY 31900005 STD        | [d82d73ba0a](https://linux-hardware.org/?probe=d82d73ba0a) | Apr 12, 2022 |
| Gigabyte      | H61M-D2P-B3                 | [a8e2ef2c76](https://linux-hardware.org/?probe=a8e2ef2c76) | Apr 12, 2022 |
| Intel         | SHARKBAY                    | [f676b9a255](https://linux-hardware.org/?probe=f676b9a255) | Apr 11, 2022 |
| Gigabyte      | H61M-D2P-B3                 | [686ef53bc5](https://linux-hardware.org/?probe=686ef53bc5) | Apr 07, 2022 |
| Gigabyte      | H61M-D2P-B3                 | [aad4b24a04](https://linux-hardware.org/?probe=aad4b24a04) | Apr 06, 2022 |
| ASUSTek       | X99-DELUXE II               | [82939dc69f](https://linux-hardware.org/?probe=82939dc69f) | Apr 05, 2022 |
| Unknown       | Unknown                     | [aac8a6f7e4](https://linux-hardware.org/?probe=aac8a6f7e4) | Apr 03, 2022 |
| Lenovo        | 32E9 SDK0T76479 WIN 3423... | [d8dbd14b3e](https://linux-hardware.org/?probe=d8dbd14b3e) | Apr 02, 2022 |
| Lenovo        | QiTianM7150                 | [a6a37565b7](https://linux-hardware.org/?probe=a6a37565b7) | Apr 02, 2022 |
| Inspur        | NF5270M3                    | [053fcd58fc](https://linux-hardware.org/?probe=053fcd58fc) | Mar 26, 2022 |
| ASUSTek       | B360M-D3H                   | [bf6e46cd01](https://linux-hardware.org/?probe=bf6e46cd01) | Mar 26, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [847b9e1fbb](https://linux-hardware.org/?probe=847b9e1fbb) | Mar 23, 2022 |
| MSI           | B450M MORTAR                | [4c4039754c](https://linux-hardware.org/?probe=4c4039754c) | Mar 13, 2022 |
| Lenovo        | 3187 SDK0L77769 WIN 3423... | [545b878c51](https://linux-hardware.org/?probe=545b878c51) | Mar 10, 2022 |
| ASUSTek       | PRIME H510M-K               | [3edcfcdf53](https://linux-hardware.org/?probe=3edcfcdf53) | Mar 08, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [5c95114871](https://linux-hardware.org/?probe=5c95114871) | Mar 02, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [6931b9fe82](https://linux-hardware.org/?probe=6931b9fe82) | Mar 02, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [842379fc35](https://linux-hardware.org/?probe=842379fc35) | Mar 01, 2022 |
| Lenovo        | MAHOBAY                     | [cd7e96054b](https://linux-hardware.org/?probe=cd7e96054b) | Mar 01, 2022 |
| Gigabyte      | EP43T-UD3L                  | [e1ba37c64a](https://linux-hardware.org/?probe=e1ba37c64a) | Feb 27, 2022 |
| Gigabyte      | EP43T-UD3L                  | [5d56069677](https://linux-hardware.org/?probe=5d56069677) | Feb 27, 2022 |
| Lenovo        | NOK                         | [05c2b02bd3](https://linux-hardware.org/?probe=05c2b02bd3) | Feb 26, 2022 |
| MSI           | B350 TOMAHAWK               | [a07d445338](https://linux-hardware.org/?probe=a07d445338) | Feb 21, 2022 |
| Lenovo        | NOK                         | [3936474618](https://linux-hardware.org/?probe=3936474618) | Feb 18, 2022 |
| Lenovo        | NOK                         | [1236b9a36b](https://linux-hardware.org/?probe=1236b9a36b) | Feb 17, 2022 |
| MSI           | A88XM-E45                   | [b58bd64798](https://linux-hardware.org/?probe=b58bd64798) | Feb 17, 2022 |
| ECS           | BSWI-DA                     | [2b3dda83e5](https://linux-hardware.org/?probe=2b3dda83e5) | Feb 04, 2022 |
| Lenovo        | SHARKBAY NO DPK             | [0bef76b548](https://linux-hardware.org/?probe=0bef76b548) | Jan 28, 2022 |
| ASUSTek       | PRIME Z370-A                | [53b2c696ff](https://linux-hardware.org/?probe=53b2c696ff) | Jan 26, 2022 |
| ASUSTek       | PRIME Z370-A                | [7b2482036e](https://linux-hardware.org/?probe=7b2482036e) | Jan 26, 2022 |
| Intel         | G41 V1.0                    | [e1f1c99851](https://linux-hardware.org/?probe=e1f1c99851) | Jan 22, 2022 |
| MSI           | H310M-S03                   | [8c009a1259](https://linux-hardware.org/?probe=8c009a1259) | Jan 17, 2022 |
| ASUSTek       | PRO B460M-C                 | [31b2f44066](https://linux-hardware.org/?probe=31b2f44066) | Jan 17, 2022 |
| Dell          | 0MWYPT A02                  | [08d5ba6a97](https://linux-hardware.org/?probe=08d5ba6a97) | Dec 30, 2021 |
| ASRock        | Z170 Gaming K4              | [590ae02fdb](https://linux-hardware.org/?probe=590ae02fdb) | Dec 29, 2021 |
| TSINGHUA T... | B460M-HDV                   | [8447bd4156](https://linux-hardware.org/?probe=8447bd4156) | Dec 22, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [50d0f206e1](https://linux-hardware.org/?probe=50d0f206e1) | Dec 21, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | [1564f2f5ea](https://linux-hardware.org/?probe=1564f2f5ea) | Dec 18, 2021 |
| Lenovo        | Unknown                     | [64951d70ab](https://linux-hardware.org/?probe=64951d70ab) | Dec 16, 2021 |
| TSINGHUA T... | B460M-HDV                   | [1146dc777c](https://linux-hardware.org/?probe=1146dc777c) | Dec 15, 2021 |
| ASUSTek       | B85M-F                      | [04b3b165f6](https://linux-hardware.org/?probe=04b3b165f6) | Dec 14, 2021 |
| ASRock        | Z170 Gaming K4              | [4f8e294d95](https://linux-hardware.org/?probe=4f8e294d95) | Dec 13, 2021 |
| Lenovo        | 3141 NOK                    | [cc90d7c889](https://linux-hardware.org/?probe=cc90d7c889) | Dec 13, 2021 |
| MSI           | B450I GAMING PLUS AC        | [fe97757850](https://linux-hardware.org/?probe=fe97757850) | Dec 10, 2021 |
| ASUSTek       | PRO B460M-C                 | [ff8706d7ac](https://linux-hardware.org/?probe=ff8706d7ac) | Dec 07, 2021 |
| OEM           | TOP77D Ver1.0               | [5747ccfcd4](https://linux-hardware.org/?probe=5747ccfcd4) | Dec 07, 2021 |
| ASRock        | B360M-ITX/ac                | [2490a94114](https://linux-hardware.org/?probe=2490a94114) | Dec 07, 2021 |
| AOC           | A815HB                      | [b1aec8b16c](https://linux-hardware.org/?probe=b1aec8b16c) | Dec 04, 2021 |
| OEM           | TOP77D Ver1.0               | [6b91b58b81](https://linux-hardware.org/?probe=6b91b58b81) | Nov 30, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [69a76fd0b6](https://linux-hardware.org/?probe=69a76fd0b6) | Nov 29, 2021 |
| ASUSTek       | PRO B460M-C                 | [b316c12d03](https://linux-hardware.org/?probe=b316c12d03) | Nov 27, 2021 |
| Gigabyte      | H61M-DS2                    | [c487bf6a9c](https://linux-hardware.org/?probe=c487bf6a9c) | Nov 24, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [fa956800a1](https://linux-hardware.org/?probe=fa956800a1) | Nov 24, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3d27077285](https://linux-hardware.org/?probe=3d27077285) | Nov 24, 2021 |
| ASUSTek       | B85M-G PLUS                 | [e198df930c](https://linux-hardware.org/?probe=e198df930c) | Nov 23, 2021 |
| ASUSTek       | B85M-G PLUS                 | [023ab776cd](https://linux-hardware.org/?probe=023ab776cd) | Nov 23, 2021 |
| Google        | Panther                     | [5e5d9936ec](https://linux-hardware.org/?probe=5e5d9936ec) | Nov 23, 2021 |
| ASRock        | Z170 Gaming K4              | [6a0bda5a7d](https://linux-hardware.org/?probe=6a0bda5a7d) | Nov 22, 2021 |
| Dell          | 0R790T A00                  | [af9a5a76c3](https://linux-hardware.org/?probe=af9a5a76c3) | Nov 22, 2021 |
| Gigabyte      | B85M-D3V-A                  | [12bcc06e6e](https://linux-hardware.org/?probe=12bcc06e6e) | Nov 21, 2021 |
| ASRock        | TRX40 Creator               | [bdd3471fa2](https://linux-hardware.org/?probe=bdd3471fa2) | Nov 17, 2021 |
| AOC           | A815HB                      | [e56b509a5a](https://linux-hardware.org/?probe=e56b509a5a) | Nov 16, 2021 |
| ASUSTek       | PRIME Z370-A                | [01b7731b34](https://linux-hardware.org/?probe=01b7731b34) | Nov 14, 2021 |
| Shanghai Z... | EA170_ TBD                  | [edc1846e0f](https://linux-hardware.org/?probe=edc1846e0f) | Nov 10, 2021 |
| Shanghai Z... | EA170_ TBD                  | [9f839630ac](https://linux-hardware.org/?probe=9f839630ac) | Nov 10, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [74d845aae1](https://linux-hardware.org/?probe=74d845aae1) | Nov 07, 2021 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [cafc4421b2](https://linux-hardware.org/?probe=cafc4421b2) | Oct 29, 2021 |
| Lenovo        | 3107 SDK0L77769 WIN 3423... | [6a7a621271](https://linux-hardware.org/?probe=6a7a621271) | Oct 22, 2021 |
| Unknown       | Unknown                     | [2fb1797d3d](https://linux-hardware.org/?probe=2fb1797d3d) | Oct 19, 2021 |
| ASRock        | B85M Pro4                   | [bf91ce9da1](https://linux-hardware.org/?probe=bf91ce9da1) | Oct 14, 2021 |
| Dell          | 0C96W1 A02                  | [edb83b3d2f](https://linux-hardware.org/?probe=edb83b3d2f) | Oct 12, 2021 |
| ASUSTek       | ROG Maximus XII HERO        | [3eb7a24e5a](https://linux-hardware.org/?probe=3eb7a24e5a) | Oct 12, 2021 |
| ASUSTek       | ROG Maximus XII HERO        | [38bb1cfdc4](https://linux-hardware.org/?probe=38bb1cfdc4) | Oct 12, 2021 |
| Gigabyte      | B550M AORUS ELITE           | [5e8e9aea62](https://linux-hardware.org/?probe=5e8e9aea62) | Oct 12, 2021 |
| ASUSTek       | A55BM-E                     | [970153a68c](https://linux-hardware.org/?probe=970153a68c) | Oct 03, 2021 |
| Lenovo        | MAHOBAY                     | [f1420c5af0](https://linux-hardware.org/?probe=f1420c5af0) | Sep 29, 2021 |
| ASRock        | TRX40 Creator               | [c7b8fcc312](https://linux-hardware.org/?probe=c7b8fcc312) | Sep 29, 2021 |
| Unknown       | Unknown                     | [4c18e17d7d](https://linux-hardware.org/?probe=4c18e17d7d) | Sep 29, 2021 |
| MSI           | B450M MORTAR MAX            | [8adcff21a2](https://linux-hardware.org/?probe=8adcff21a2) | Sep 27, 2021 |
| Gigabyte      | B450M DS3H-CF               | [10ce8f4e5e](https://linux-hardware.org/?probe=10ce8f4e5e) | Sep 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | [b62637ba85](https://linux-hardware.org/?probe=b62637ba85) | Sep 25, 2021 |
| ASUSTek       | H87-PRO                     | [508bab38ae](https://linux-hardware.org/?probe=508bab38ae) | Sep 20, 2021 |
| ASUSTek       | H87-PRO                     | [8b09747789](https://linux-hardware.org/?probe=8b09747789) | Sep 20, 2021 |
| Sapphire      | Pure Platinum 970A-PLUS     | [d64d86eced](https://linux-hardware.org/?probe=d64d86eced) | Sep 19, 2021 |
| TSINGHUA T... | B460M-HDV                   | [bc175433f9](https://linux-hardware.org/?probe=bc175433f9) | Sep 18, 2021 |
| TSINGHUA T... | B460M-HDV                   | [80017bc79b](https://linux-hardware.org/?probe=80017bc79b) | Sep 18, 2021 |
| ASUSTek       | B360M-BASALT                | [f1783ce369](https://linux-hardware.org/?probe=f1783ce369) | Sep 18, 2021 |
| Lenovo        | NOK                         | [61a15d9531](https://linux-hardware.org/?probe=61a15d9531) | Sep 14, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | [a48ec730b7](https://linux-hardware.org/?probe=a48ec730b7) | Sep 13, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [db46242eec](https://linux-hardware.org/?probe=db46242eec) | Sep 13, 2021 |
| ASUSTek       | Z170-A                      | [2d0a7ed28d](https://linux-hardware.org/?probe=2d0a7ed28d) | Aug 28, 2021 |
| ASUSTek       | Z170-A                      | [fc294326ce](https://linux-hardware.org/?probe=fc294326ce) | Aug 28, 2021 |
| Dell          | 0R790T A00                  | [03b37f86b2](https://linux-hardware.org/?probe=03b37f86b2) | Aug 27, 2021 |
| Lenovo        | SHARKBAY NOK                | [33cc1aba5f](https://linux-hardware.org/?probe=33cc1aba5f) | Aug 25, 2021 |
| Unknown       | Unknown                     | [e0e805180d](https://linux-hardware.org/?probe=e0e805180d) | Aug 22, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [ce37ed52aa](https://linux-hardware.org/?probe=ce37ed52aa) | Aug 19, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [18f0785e64](https://linux-hardware.org/?probe=18f0785e64) | Aug 19, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [753b5b706d](https://linux-hardware.org/?probe=753b5b706d) | Aug 18, 2021 |
| Yanling       | YL-KBRL2 Series Ver:1.01    | [ad2f5f75d8](https://linux-hardware.org/?probe=ad2f5f75d8) | Aug 10, 2021 |
| TSINGHUA T... | B460-N2                     | [59d9384348](https://linux-hardware.org/?probe=59d9384348) | Aug 09, 2021 |
| ASUSTek       | Z97-PRO                     | [a0e65d5ee7](https://linux-hardware.org/?probe=a0e65d5ee7) | Aug 08, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | [07e9ee8610](https://linux-hardware.org/?probe=07e9ee8610) | Aug 02, 2021 |
| Dell          | 0R790T A00                  | [474dfcb3e3](https://linux-hardware.org/?probe=474dfcb3e3) | Jul 26, 2021 |
| Lenovo        | 3188 SDK0L77769 WIN 3423... | [d84332d50b](https://linux-hardware.org/?probe=d84332d50b) | Jul 14, 2021 |
| Lenovo        | 3188 SDK0L77769 WIN 3423... | [f68b508049](https://linux-hardware.org/?probe=f68b508049) | Jul 14, 2021 |
| AMD           | BL2 V2.3                    | [1053adf355](https://linux-hardware.org/?probe=1053adf355) | Jul 12, 2021 |
| MSI           | Z590-A PRO                  | [50d75ad77d](https://linux-hardware.org/?probe=50d75ad77d) | Jul 03, 2021 |
| Dell          | 0GX297                      | [f4debf994a](https://linux-hardware.org/?probe=f4debf994a) | Jun 30, 2021 |
| HP            | 18E7                        | [5f0e216922](https://linux-hardware.org/?probe=5f0e216922) | Jun 28, 2021 |
| TSINGHUA T... | B460-N2 V1.1                | [70d8ede642](https://linux-hardware.org/?probe=70d8ede642) | Jun 23, 2021 |
| Gigabyte      | GA-970A-D3                  | [61460e5cfc](https://linux-hardware.org/?probe=61460e5cfc) | Jun 23, 2021 |
| Gigabyte      | GA-970A-D3                  | [c916e64b0d](https://linux-hardware.org/?probe=c916e64b0d) | Jun 23, 2021 |
| TSINGHUA T... | B460-N2 V1.1                | [8431bcbed8](https://linux-hardware.org/?probe=8431bcbed8) | Jun 22, 2021 |
| ASUSTek       | P5QL PRO                    | [c76462e732](https://linux-hardware.org/?probe=c76462e732) | Jun 20, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | [c0ecdee03e](https://linux-hardware.org/?probe=c0ecdee03e) | Jun 20, 2021 |
| ASUSTek       | P5QL PRO                    | [8b9f25c98b](https://linux-hardware.org/?probe=8b9f25c98b) | Jun 19, 2021 |
| Loongson      | LS3A3000-7A1000-1w-V1.2-... | [014bdabb68](https://linux-hardware.org/?probe=014bdabb68) | Jun 16, 2021 |
| Lenovo        | H310                        | [309031a039](https://linux-hardware.org/?probe=309031a039) | Jun 12, 2021 |
| Advantech     | DMS-BC30 A101-2             | [e9ee5e90e8](https://linux-hardware.org/?probe=e9ee5e90e8) | Jun 08, 2021 |
| Advantech     | DMS-BC30 A101-2             | [2fd059f38d](https://linux-hardware.org/?probe=2fd059f38d) | Jun 08, 2021 |
| Lenovo        | H310                        | [f36653c4fb](https://linux-hardware.org/?probe=f36653c4fb) | Jun 06, 2021 |
| Unknown       | Kunpeng Desktop Board D9... | [2a8b1a08bc](https://linux-hardware.org/?probe=2a8b1a08bc) | Jun 04, 2021 |
| Unknown       | Kunpeng Desktop Board D9... | [ead2c4250e](https://linux-hardware.org/?probe=ead2c4250e) | Jun 04, 2021 |
| Huanghe       | PRO H410M-C                 | [37534d085b](https://linux-hardware.org/?probe=37534d085b) | Jun 04, 2021 |
| Huanghe       | PRO H410M-C                 | [1c92e63940](https://linux-hardware.org/?probe=1c92e63940) | May 31, 2021 |
| Huanan        | X79 VAA1                    | [150afcb2d1](https://linux-hardware.org/?probe=150afcb2d1) | May 30, 2021 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | [a22fbcde28](https://linux-hardware.org/?probe=a22fbcde28) | May 26, 2021 |
| MSI           | B550M PRO-VDH WIFI          | [59f94e4db6](https://linux-hardware.org/?probe=59f94e4db6) | May 25, 2021 |
| Centerm       | C92                         | [fe4761d2b2](https://linux-hardware.org/?probe=fe4761d2b2) | May 25, 2021 |
| Acer          | Aspire TC-606               | [db910234a6](https://linux-hardware.org/?probe=db910234a6) | May 25, 2021 |
| Soyo          | SY-I5GC2-L                  | [02a90f300e](https://linux-hardware.org/?probe=02a90f300e) | May 24, 2021 |
| Soyo          | SY-I5GC2-L                  | [91bdc4a9a0](https://linux-hardware.org/?probe=91bdc4a9a0) | May 24, 2021 |
| MSI           | Z590-A PRO                  | [b74e96d4be](https://linux-hardware.org/?probe=b74e96d4be) | May 22, 2021 |
| Dell          | 0HN7XN A01                  | [fa2352afac](https://linux-hardware.org/?probe=fa2352afac) | May 19, 2021 |
| Gigabyte      | B365M D2V                   | [887f18105e](https://linux-hardware.org/?probe=887f18105e) | May 17, 2021 |
| Gigabyte      | B365M D2V                   | [644431aa47](https://linux-hardware.org/?probe=644431aa47) | May 17, 2021 |
| Gigabyte      | Z170X-UD3-CF                | [41fbd83170](https://linux-hardware.org/?probe=41fbd83170) | May 17, 2021 |
| Lenovo        | 3176 SDK0L77767 WIN 3423... | [d418b8e0e9](https://linux-hardware.org/?probe=d418b8e0e9) | May 17, 2021 |
| Lenovo        | 3176 SDK0L77767 WIN 3423... | [b04d956c6e](https://linux-hardware.org/?probe=b04d956c6e) | May 17, 2021 |
| MSI           | Z590-A PRO                  | [b2cc4333b0](https://linux-hardware.org/?probe=b2cc4333b0) | May 16, 2021 |
| Gigabyte      | B460M AORUS PRO             | [ef3422dd2d](https://linux-hardware.org/?probe=ef3422dd2d) | May 14, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [321f62efb9](https://linux-hardware.org/?probe=321f62efb9) | May 04, 2021 |
| MSI           | B450M MORTAR                | [586195f9e8](https://linux-hardware.org/?probe=586195f9e8) | May 03, 2021 |
| MSI           | B450M MORTAR                | [0f71a5127c](https://linux-hardware.org/?probe=0f71a5127c) | May 01, 2021 |
| Lenovo        | No DPK                      | [15a0f7dbe3](https://linux-hardware.org/?probe=15a0f7dbe3) | Apr 27, 2021 |
| ELSKY         | M219F-6C                    | [85ce077799](https://linux-hardware.org/?probe=85ce077799) | Apr 22, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [c557439d9f](https://linux-hardware.org/?probe=c557439d9f) | Apr 03, 2021 |
| MSI           | B450M MORTAR                | [8406dee7f4](https://linux-hardware.org/?probe=8406dee7f4) | Apr 02, 2021 |
| MSI           | B450M MORTAR                | [6e403bbf50](https://linux-hardware.org/?probe=6e403bbf50) | Apr 02, 2021 |
| SYWZ          | S210H Series                | [2e8183b6eb](https://linux-hardware.org/?probe=2e8183b6eb) | Mar 14, 2021 |
| SYWZ          | S210H Series                | [d0f36756ab](https://linux-hardware.org/?probe=d0f36756ab) | Mar 14, 2021 |
| Dell          | 03CPWF A00                  | [126a2e8974](https://linux-hardware.org/?probe=126a2e8974) | Feb 22, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [0ac46a588c](https://linux-hardware.org/?probe=0ac46a588c) | Feb 21, 2021 |
| Gigabyte      | B85M-D2V-SI                 | [a0779807a2](https://linux-hardware.org/?probe=a0779807a2) | Feb 15, 2021 |
| Dell          | 04VF8V A01                  | [14d2de53c9](https://linux-hardware.org/?probe=14d2de53c9) | Feb 14, 2021 |
| ASRock        | A320M-HDV                   | [d844c4f50e](https://linux-hardware.org/?probe=d844c4f50e) | Feb 05, 2021 |
| ASRock        | A320M-HDV                   | [5c23d11a52](https://linux-hardware.org/?probe=5c23d11a52) | Feb 05, 2021 |
| HUAWEI        | SP1PGUM M1020               | [bd05c84564](https://linux-hardware.org/?probe=bd05c84564) | Feb 04, 2021 |
| Dell          | 06JWJY A00                  | [1f2099e9d3](https://linux-hardware.org/?probe=1f2099e9d3) | Feb 02, 2021 |
| MSI           | B450I GAMING PLUS AC        | [5b274af228](https://linux-hardware.org/?probe=5b274af228) | Feb 02, 2021 |
| ASUSTek       | PRIME Z270-A                | [9c21c30887](https://linux-hardware.org/?probe=9c21c30887) | Jan 30, 2021 |
| MSI           | MAG B460M MORTAR WIFI       | [35d97e2d21](https://linux-hardware.org/?probe=35d97e2d21) | Jan 28, 2021 |
| MSI           | B450I GAMING PLUS AC        | [a1c263681f](https://linux-hardware.org/?probe=a1c263681f) | Jan 26, 2021 |
| ASUSTek       | PRIME H310M-F R2.0          | [3c4d584c27](https://linux-hardware.org/?probe=3c4d584c27) | Jan 26, 2021 |
| ASUSTek       | PRIME H410M-E               | [1b100a591d](https://linux-hardware.org/?probe=1b100a591d) | Jan 19, 2021 |
| Lenovo        | 317E SDK0L77767 WIN 3423... | [6e82572f07](https://linux-hardware.org/?probe=6e82572f07) | Jan 17, 2021 |
| MSI           | B450 TOMAHAWK               | [edbfbb65b8](https://linux-hardware.org/?probe=edbfbb65b8) | Jan 15, 2021 |
| Lenovo        | 3107 NOK                    | [902ea74b31](https://linux-hardware.org/?probe=902ea74b31) | Jan 08, 2021 |
| Google        | Zako                        | [d8df4eefd6](https://linux-hardware.org/?probe=d8df4eefd6) | Jan 01, 2021 |
| Google        | Zako                        | [6bedd150e9](https://linux-hardware.org/?probe=6bedd150e9) | Jan 01, 2021 |
| HP            | 82A4                        | [bf686ef745](https://linux-hardware.org/?probe=bf686ef745) | Jan 01, 2021 |
| Lenovo        | 1.0                         | [897523f5fd](https://linux-hardware.org/?probe=897523f5fd) | Dec 27, 2020 |
| Lenovo        | 1.0                         | [53a763dc24](https://linux-hardware.org/?probe=53a763dc24) | Dec 27, 2020 |
| Gigabyte      | B550I AORUS PRO AX          | [fd025ae38b](https://linux-hardware.org/?probe=fd025ae38b) | Dec 23, 2020 |
| Gigabyte      | B550I AORUS PRO AX          | [a141f2ed51](https://linux-hardware.org/?probe=a141f2ed51) | Dec 22, 2020 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [224c36cf4d](https://linux-hardware.org/?probe=224c36cf4d) | Dec 15, 2020 |
| ASRock        | Z170 Gaming K4              | [a246612b17](https://linux-hardware.org/?probe=a246612b17) | Dec 13, 2020 |
| ASUSTek       | PRIME H270-PLUS             | [0c0911cd7b](https://linux-hardware.org/?probe=0c0911cd7b) | Dec 11, 2020 |
| ASUSTek       | PRIME B450M-A               | [b20c8c639e](https://linux-hardware.org/?probe=b20c8c639e) | Dec 08, 2020 |
| HUAWEI        | Kunpeng Desktop             | [cbd268b858](https://linux-hardware.org/?probe=cbd268b858) | Dec 04, 2020 |
| HUAWEI        | Kunpeng Desktop             | [da163e34c7](https://linux-hardware.org/?probe=da163e34c7) | Dec 04, 2020 |
| ASUSTek       | PRIME A520M-K               | [7eb641e51d](https://linux-hardware.org/?probe=7eb641e51d) | Dec 01, 2020 |
| ASUSTek       | B85M-G                      | [216a0f765e](https://linux-hardware.org/?probe=216a0f765e) | Dec 01, 2020 |
| Gigabyte      | B250-D3A-CF                 | [907d35d953](https://linux-hardware.org/?probe=907d35d953) | Nov 30, 2020 |
| Gigabyte      | B250-HD3-CF                 | [d1c0a8df13](https://linux-hardware.org/?probe=d1c0a8df13) | Nov 23, 2020 |
| Gigabyte      | B250-HD3-CF                 | [7975ba3888](https://linux-hardware.org/?probe=7975ba3888) | Nov 23, 2020 |
| Unknown       | Unknown                     | [d58e8b793e](https://linux-hardware.org/?probe=d58e8b793e) | Nov 22, 2020 |
| Unknown       | Unknown                     | [c0e8909067](https://linux-hardware.org/?probe=c0e8909067) | Nov 22, 2020 |
| Unknown       | Unknown                     | [c0d7c657b1](https://linux-hardware.org/?probe=c0d7c657b1) | Nov 22, 2020 |
| Gigabyte      | 970-GAMING                  | [44f42f7676](https://linux-hardware.org/?probe=44f42f7676) | Nov 21, 2020 |
| Colorful T... | C.H110M-K PRO V21           | [c8211ace73](https://linux-hardware.org/?probe=c8211ace73) | Nov 20, 2020 |
| ASUSTek       | PRIME X570-P                | [0999a52054](https://linux-hardware.org/?probe=0999a52054) | Nov 18, 2020 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [a5d5227154](https://linux-hardware.org/?probe=a5d5227154) | Nov 12, 2020 |
| HP            | 8455                        | [8fbf07649a](https://linux-hardware.org/?probe=8fbf07649a) | Nov 03, 2020 |
| Intel         | SKYBAY                      | [ebc35582c8](https://linux-hardware.org/?probe=ebc35582c8) | Oct 23, 2020 |
| Intel         | SKYBAY                      | [ce89df6806](https://linux-hardware.org/?probe=ce89df6806) | Oct 23, 2020 |
| MSI           | X99A XPOWER GAMING TITAN... | [6faf6514f5](https://linux-hardware.org/?probe=6faf6514f5) | Oct 15, 2020 |
| Gigabyte      | B85M-D2V                    | [3393bfd809](https://linux-hardware.org/?probe=3393bfd809) | Sep 25, 2020 |
| Gigabyte      | B85M-D2V                    | [4ef60f3d1d](https://linux-hardware.org/?probe=4ef60f3d1d) | Sep 25, 2020 |
| ASRock        | FM2A85M-DG3                 | [8516ddc869](https://linux-hardware.org/?probe=8516ddc869) | Sep 24, 2020 |
| AEWIN         | SCB-1711A                   | [2d8dbb0d3a](https://linux-hardware.org/?probe=2d8dbb0d3a) | Sep 09, 2020 |
| RBQ           | RongBotQiu X79.810          | [71e839ea6f](https://linux-hardware.org/?probe=71e839ea6f) | Sep 03, 2020 |
| Lenovo        | 36EF SDK0L77767 WIN 3423... | [a01c93c314](https://linux-hardware.org/?probe=a01c93c314) | Sep 01, 2020 |
| Lenovo        | 36EF SDK0L77767 WIN 3423... | [2800d63edf](https://linux-hardware.org/?probe=2800d63edf) | Aug 30, 2020 |
| Gigabyte      | B450 AORUS M                | [f0d9b71d6d](https://linux-hardware.org/?probe=f0d9b71d6d) | Aug 15, 2020 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [e32815911a](https://linux-hardware.org/?probe=e32815911a) | Aug 11, 2020 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [36a4789e67](https://linux-hardware.org/?probe=36a4789e67) | Aug 10, 2020 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [2e6c21ed23](https://linux-hardware.org/?probe=2e6c21ed23) | Jul 26, 2020 |
| Lenovo        | NOK                         | [99cea2b8c1](https://linux-hardware.org/?probe=99cea2b8c1) | Jul 22, 2020 |
| Lenovo        | Unknown                     | [9e428d8ef9](https://linux-hardware.org/?probe=9e428d8ef9) | Jul 16, 2020 |
| MSI           | 880GM-E41                   | [620e8dbc2c](https://linux-hardware.org/?probe=620e8dbc2c) | Jul 13, 2020 |
| Gigabyte      | AB350M-DS2-CF               | [014b2718ae](https://linux-hardware.org/?probe=014b2718ae) | Jul 13, 2020 |
| Gigabyte      | AB350M-DS2-CF               | [6ea3c86837](https://linux-hardware.org/?probe=6ea3c86837) | Jul 13, 2020 |
| Gigabyte      | Z77M-D3H                    | [ce5f57a42d](https://linux-hardware.org/?probe=ce5f57a42d) | Jul 09, 2020 |
| Intel         | H81C                        | [54732275c2](https://linux-hardware.org/?probe=54732275c2) | Jul 04, 2020 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [176c1bcb0a](https://linux-hardware.org/?probe=176c1bcb0a) | Jun 24, 2020 |
| MSI           | Z370-OC PRO                 | [a37abc19ef](https://linux-hardware.org/?probe=a37abc19ef) | Jun 08, 2020 |
| ASUSTek       | Z97-PRO                     | [c534bc4bc6](https://linux-hardware.org/?probe=c534bc4bc6) | Jun 04, 2020 |
| ASUSTek       | STRIX Z270E GAMING          | [29eb8f828b](https://linux-hardware.org/?probe=29eb8f828b) | May 30, 2020 |
| HP            | 82A1                        | [ddd727fd22](https://linux-hardware.org/?probe=ddd727fd22) | May 25, 2020 |
| HP            | 807D                        | [0523c549d5](https://linux-hardware.org/?probe=0523c549d5) | May 25, 2020 |
| MSI           | MPG X570 GAMING PRO CARB... | [220e504029](https://linux-hardware.org/?probe=220e504029) | May 23, 2020 |
| HP            | 807D                        | [d82ca940de](https://linux-hardware.org/?probe=d82ca940de) | May 22, 2020 |
| Biostar       | H110MLC                     | [70e9170fa4](https://linux-hardware.org/?probe=70e9170fa4) | May 15, 2020 |
| Dell          | 09PR9H A02                  | [a0f6d2eac4](https://linux-hardware.org/?probe=a0f6d2eac4) | May 11, 2020 |
| ASUSTek       | Z97-C                       | [6eb7ec99eb](https://linux-hardware.org/?probe=6eb7ec99eb) | May 08, 2020 |
| Gigabyte      | X58A-UD3R                   | [a244f111f8](https://linux-hardware.org/?probe=a244f111f8) | May 05, 2020 |
| Gigabyte      | X58A-UD3R                   | [69210022d8](https://linux-hardware.org/?probe=69210022d8) | May 05, 2020 |
| Gigabyte      | F2A88XM-DS2-TE              | [2b96fc655b](https://linux-hardware.org/?probe=2b96fc655b) | Apr 28, 2020 |
| Gigabyte      | F2A88XM-DS2-TE              | [c53b21972a](https://linux-hardware.org/?probe=c53b21972a) | Apr 28, 2020 |
| ASUSTek       | B85M-G                      | [1339b47680](https://linux-hardware.org/?probe=1339b47680) | Apr 22, 2020 |
| Dell          | 042P49 A02                  | [bd064eace3](https://linux-hardware.org/?probe=bd064eace3) | Apr 21, 2020 |
| Lenovo        | Tiger Hill                  | [7f92e05b46](https://linux-hardware.org/?probe=7f92e05b46) | Apr 14, 2020 |
| Dell          | 040DDP A01                  | [ab41c29212](https://linux-hardware.org/?probe=ab41c29212) | Mar 31, 2020 |
| ECS           | H61H2-TAIO                  | [e6f8d21b5a](https://linux-hardware.org/?probe=e6f8d21b5a) | Mar 24, 2020 |
| ASUSTek       | Z170-A                      | [4629800e33](https://linux-hardware.org/?probe=4629800e33) | Mar 19, 2020 |
| Gigabyte      | B85-HD3                     | [fb4cdf6f1a](https://linux-hardware.org/?probe=fb4cdf6f1a) | Mar 09, 2020 |
| ECS           | H61H2-TAIO                  | [6ee3574f22](https://linux-hardware.org/?probe=6ee3574f22) | Feb 26, 2020 |
| ECS           | H61H2-TAIO                  | [32a0959f61](https://linux-hardware.org/?probe=32a0959f61) | Feb 25, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [73afca4618](https://linux-hardware.org/?probe=73afca4618) | Feb 17, 2020 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | [81586acd13](https://linux-hardware.org/?probe=81586acd13) | Jan 27, 2020 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | [a9cada02fe](https://linux-hardware.org/?probe=a9cada02fe) | Jan 27, 2020 |
| Colorful T... | C.Q1900M PRO V20            | [17664b4797](https://linux-hardware.org/?probe=17664b4797) | Jan 25, 2020 |
| Colorful T... | C.Q1900M PRO V20            | [8bc2fe0d86](https://linux-hardware.org/?probe=8bc2fe0d86) | Jan 25, 2020 |
| MSI           | B450M MORTAR                | [eb4106d83f](https://linux-hardware.org/?probe=eb4106d83f) | Jan 10, 2020 |
| ASUSTek       | Z97-PRO                     | [e814486254](https://linux-hardware.org/?probe=e814486254) | Jan 07, 2020 |
| MSI           | MPG X570 GAMING PLUS        | [34f134e5b0](https://linux-hardware.org/?probe=34f134e5b0) | Jan 06, 2020 |
| ASUSTek       | H110M-E/M.2                 | [df17ba12c1](https://linux-hardware.org/?probe=df17ba12c1) | Jan 05, 2020 |
| Intel         | MAHOBAY                     | [30a583066a](https://linux-hardware.org/?probe=30a583066a) | Dec 29, 2019 |
| ONDA          | B320-IPC Ver:1.02           | [06286179c2](https://linux-hardware.org/?probe=06286179c2) | Dec 09, 2019 |
| MSI           | X99A XPOWER GAMING TITAN... | [65df5317a4](https://linux-hardware.org/?probe=65df5317a4) | Dec 06, 2019 |
| Dell          | 0XR1GT A00                  | [76dba7bb94](https://linux-hardware.org/?probe=76dba7bb94) | Nov 22, 2019 |
| ASUSTek       | M5A97                       | [ac3e990070](https://linux-hardware.org/?probe=ac3e990070) | Nov 20, 2019 |
| ASUSTek       | M5A97                       | [742601efb5](https://linux-hardware.org/?probe=742601efb5) | Nov 20, 2019 |
| Gigabyte      | Z87P-D3                     | [db5a6d60dd](https://linux-hardware.org/?probe=db5a6d60dd) | Nov 17, 2019 |
| ASUSTek       | B75M-A                      | [bba74ed5a2](https://linux-hardware.org/?probe=bba74ed5a2) | Nov 15, 2019 |
| HP            | 843C                        | [e5e15df58d](https://linux-hardware.org/?probe=e5e15df58d) | Nov 14, 2019 |
| MSI           | X99A XPOWER GAMING TITAN... | [bda577e787](https://linux-hardware.org/?probe=bda577e787) | Nov 12, 2019 |
| Lenovo        | 3107 NOK                    | [8545691fd8](https://linux-hardware.org/?probe=8545691fd8) | Oct 24, 2019 |
| MSI           | Z370 GAMING PRO CARBON A... | [30939907c1](https://linux-hardware.org/?probe=30939907c1) | Oct 13, 2019 |
| MSI           | Z370 GAMING PRO CARBON A... | [6b0db76cfd](https://linux-hardware.org/?probe=6b0db76cfd) | Oct 12, 2019 |
| ASUSTek       | Z8NA-D6                     | [5eab0577d3](https://linux-hardware.org/?probe=5eab0577d3) | Sep 28, 2019 |
| ASUSTek       | B85M-G PLUS/USB             | [174aed26d5](https://linux-hardware.org/?probe=174aed26d5) | Sep 27, 2019 |
| Lenovo        | QiTianM6900                 | [670fee2c10](https://linux-hardware.org/?probe=670fee2c10) | Sep 20, 2019 |
| ASUSTek       | M5A78L-M LX3 PLUS           | [9f0b99fb29](https://linux-hardware.org/?probe=9f0b99fb29) | Sep 03, 2019 |
| Lenovo        | 36EB SDK0L77769 WIN 3423... | [5697eebc76](https://linux-hardware.org/?probe=5697eebc76) | Sep 02, 2019 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [5652e9e755](https://linux-hardware.org/?probe=5652e9e755) | Aug 31, 2019 |
| Gigabyte      | Z270-HD3-CF                 | [1245fd6da5](https://linux-hardware.org/?probe=1245fd6da5) | Aug 30, 2019 |
| HP            | 81C7 MVB 0C                 | [931ea9a398](https://linux-hardware.org/?probe=931ea9a398) | Aug 27, 2019 |
| Dell          | 0GDG8Y A00                  | [a055c74af6](https://linux-hardware.org/?probe=a055c74af6) | Aug 18, 2019 |
| Gigabyte      | M68M-S2P                    | [0decbcaa1f](https://linux-hardware.org/?probe=0decbcaa1f) | Aug 16, 2019 |
| ASUSTek       | M5A78L-M LX3 PLUS           | [ee8b6a4998](https://linux-hardware.org/?probe=ee8b6a4998) | Aug 14, 2019 |
| ASRock        | X470 Gaming-ITX/ac          | [641383210d](https://linux-hardware.org/?probe=641383210d) | Aug 12, 2019 |
| ASUSTek       | M5A78L-M LX3 PLUS           | [e87b327f29](https://linux-hardware.org/?probe=e87b327f29) | Aug 11, 2019 |
| AMI           | PB_1900A                    | [2c3f429517](https://linux-hardware.org/?probe=2c3f429517) | Aug 10, 2019 |
| ASUSTek       | Z97-AR                      | [510b031ce9](https://linux-hardware.org/?probe=510b031ce9) | Aug 09, 2019 |
| Lenovo        | 36E7 SDK0L77769 WIN 3423... | [69d10d1093](https://linux-hardware.org/?probe=69d10d1093) | Aug 02, 2019 |
| Dell          | 0N9Y46 A00                  | [3548830389](https://linux-hardware.org/?probe=3548830389) | Jul 23, 2019 |
| Gigabyte      | B250M-D3V-CF                | [cba535c695](https://linux-hardware.org/?probe=cba535c695) | Jul 18, 2019 |
| HP            | 0B10H                       | [758924e4f2](https://linux-hardware.org/?probe=758924e4f2) | Jul 08, 2019 |
| Lenovo        | MAHOBAY NOK                 | [74dfe126d0](https://linux-hardware.org/?probe=74dfe126d0) | Jul 04, 2019 |
| Dell          | 0DNKMN A00                  | [24870345d1](https://linux-hardware.org/?probe=24870345d1) | Jun 25, 2019 |
| Dell          | 0DNKMN A00                  | [44e012b7fb](https://linux-hardware.org/?probe=44e012b7fb) | Jun 25, 2019 |
| Dell          | 0C96W1 A03                  | [3d80eacdfc](https://linux-hardware.org/?probe=3d80eacdfc) | Jun 18, 2019 |
| ASUSTek       | M5A78L-M LX3 PLUS           | [579eebbcea](https://linux-hardware.org/?probe=579eebbcea) | Jun 07, 2019 |
| ASUSTek       | P8P67 LE                    | [63f1b6d26c](https://linux-hardware.org/?probe=63f1b6d26c) | Jun 06, 2019 |
| ASUSTek       | P8P67 LE                    | [928d66c1a0](https://linux-hardware.org/?probe=928d66c1a0) | Jun 06, 2019 |
| ASUSTek       | P8P67 LE                    | [7ece60be1d](https://linux-hardware.org/?probe=7ece60be1d) | Jun 05, 2019 |
| ASUSTek       | P8P67 LE                    | [83a1805c76](https://linux-hardware.org/?probe=83a1805c76) | Jun 05, 2019 |
| Lenovo        | ZHENGJIUZHE REN7000-28IC... | [1b85d8db4e](https://linux-hardware.org/?probe=1b85d8db4e) | Jun 04, 2019 |
| Gigabyte      | B85M-D2V-SI                 | [6be6da3a8e](https://linux-hardware.org/?probe=6be6da3a8e) | May 31, 2019 |
| Gigabyte      | B85M-D2V-SI                 | [900bc7e93c](https://linux-hardware.org/?probe=900bc7e93c) | May 31, 2019 |
| ASUSTek       | PRIME H310T                 | [851b9539e3](https://linux-hardware.org/?probe=851b9539e3) | May 24, 2019 |
| Dell          | 0XFWHV A00                  | [6dac78db97](https://linux-hardware.org/?probe=6dac78db97) | May 23, 2019 |
| Dell          | 0XFWHV A00                  | [82e6a2d735](https://linux-hardware.org/?probe=82e6a2d735) | May 19, 2019 |
| ASUSTek       | P6X58D PREMIUM              | [e9440445bc](https://linux-hardware.org/?probe=e9440445bc) | May 09, 2019 |
| Gigabyte      | B85N PHOENIX-CF             | [734eb3795e](https://linux-hardware.org/?probe=734eb3795e) | May 08, 2019 |
| ASUSTek       | M2A-VM                      | [3a02e6759d](https://linux-hardware.org/?probe=3a02e6759d) | May 08, 2019 |
| ASUSTek       | H61M-E                      | [6f9f39bbb6](https://linux-hardware.org/?probe=6f9f39bbb6) | May 07, 2019 |
| ASUSTek       | M2A-VM                      | [ac318056f7](https://linux-hardware.org/?probe=ac318056f7) | May 07, 2019 |
| Acer          | Aspire TC-606               | [5de5deb65e](https://linux-hardware.org/?probe=5de5deb65e) | May 06, 2019 |
| Lenovo        | SHARKBAY NOK                | [8df3c6b792](https://linux-hardware.org/?probe=8df3c6b792) | May 06, 2019 |
| Acer          | Aspire TC-606               | [1900e5ff06](https://linux-hardware.org/?probe=1900e5ff06) | May 06, 2019 |
| Gigabyte      | H270N-WIFI-CF               | [61bd5624bb](https://linux-hardware.org/?probe=61bd5624bb) | Apr 30, 2019 |
| Gigabyte      | H270N-WIFI-CF               | [b0a660db1e](https://linux-hardware.org/?probe=b0a660db1e) | Apr 23, 2019 |
| Gigabyte      | H270N-WIFI-CF               | [3fd02cfa82](https://linux-hardware.org/?probe=3fd02cfa82) | Apr 23, 2019 |
| ASUSTek       | B85M-G PLUS/USB             | [8f686df361](https://linux-hardware.org/?probe=8f686df361) | Apr 15, 2019 |
| ASUSTek       | M5A78L-M LX3 PLUS           | [6a9582e524](https://linux-hardware.org/?probe=6a9582e524) | Apr 10, 2019 |
| ASRock        | B360M-HDV                   | [59151791cf](https://linux-hardware.org/?probe=59151791cf) | Apr 09, 2019 |
| Gigabyte      | B150M-Power2-EC-CF          | [68b2380c53](https://linux-hardware.org/?probe=68b2380c53) | Apr 05, 2019 |
| Gigabyte      | Z170X-Gaming 5              | [4efc7fbdc6](https://linux-hardware.org/?probe=4efc7fbdc6) | Apr 01, 2019 |
| Lenovo        | SHARKBAY NOK                | [14cba25e3e](https://linux-hardware.org/?probe=14cba25e3e) | Apr 01, 2019 |
| Lenovo        | 1030 SBB0J05441 WIN 3305... | [92262238c3](https://linux-hardware.org/?probe=92262238c3) | Mar 28, 2019 |
| ASUSTek       | PRIME B350-PLUS             | [175525d48c](https://linux-hardware.org/?probe=175525d48c) | Mar 25, 2019 |
| ASUSTek       | PRIME B350-PLUS             | [dccca67c2e](https://linux-hardware.org/?probe=dccca67c2e) | Mar 25, 2019 |
| ASUSTek       | PRIME B350-PLUS             | [d0787d5045](https://linux-hardware.org/?probe=d0787d5045) | Mar 25, 2019 |
| Lenovo        | 36E7 SDK0L77767 WIN 3423... | [80816fc39e](https://linux-hardware.org/?probe=80816fc39e) | Mar 25, 2019 |
| Gigabyte      | Z87-HD3                     | [050c0abdc8](https://linux-hardware.org/?probe=050c0abdc8) | Mar 18, 2019 |
| ASUSTek       | PRIME Z370-P II             | [0b6eea7daa](https://linux-hardware.org/?probe=0b6eea7daa) | Mar 15, 2019 |
| Yeston Dig... | YESTON A78L Policeman V3... | [3a74ed7842](https://linux-hardware.org/?probe=3a74ed7842) | Mar 12, 2019 |
| Yeston Dig... | YESTON A78L Policeman V3... | [3c900dd5ac](https://linux-hardware.org/?probe=3c900dd5ac) | Mar 12, 2019 |
| Gigabyte      | Z87-HD3                     | [a4ad17d97c](https://linux-hardware.org/?probe=a4ad17d97c) | Mar 02, 2019 |
| ASUSTek       | PRIME Z370-A                | [a9e837c9eb](https://linux-hardware.org/?probe=a9e837c9eb) | Feb 08, 2019 |
| Lenovo        | 36E7 SDK0L77769 WIN 3423... | [1b722df896](https://linux-hardware.org/?probe=1b722df896) | Jan 21, 2019 |
| ASUSTek       | PRIME B450M-A               | [e077ae4d59](https://linux-hardware.org/?probe=e077ae4d59) | Jan 20, 2019 |
| HP            | 2B4F                        | [188b0e90bc](https://linux-hardware.org/?probe=188b0e90bc) | Jan 08, 2019 |
| Dell          | 077RRV A00                  | [c7b9c0beb8](https://linux-hardware.org/?probe=c7b9c0beb8) | Dec 29, 2018 |
| Dell          | 077RRV A00                  | [88d3983de4](https://linux-hardware.org/?probe=88d3983de4) | Dec 29, 2018 |
| ASUSTek       | B85M-G PLUS/USB             | [cbb464c414](https://linux-hardware.org/?probe=cbb464c414) | Dec 04, 2018 |
| Lenovo        | 3102 SDK0L77769 WIN 3423... | [2143ae0253](https://linux-hardware.org/?probe=2143ae0253) | Nov 13, 2018 |
| Huanan        | X79 PLUS V6.11              | [0a36000504](https://linux-hardware.org/?probe=0a36000504) | Nov 05, 2018 |
| Huanan        | X79 V1.4                    | [1204ed863a](https://linux-hardware.org/?probe=1204ed863a) | Oct 29, 2018 |
| Lenovo        | 36C5 SDK0L77767 WIN 3423... | [73b72b86b8](https://linux-hardware.org/?probe=73b72b86b8) | Oct 29, 2018 |
| Gigabyte      | F2A88XM-D3H                 | [94d087771b](https://linux-hardware.org/?probe=94d087771b) | Sep 24, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 51       | 14.61%  |
| Ubuntu 18.04                 | 45       | 12.89%  |
| Arch                         | 19       | 5.44%   |
| Ubuntu 22.04                 | 16       | 4.58%   |
| Debian 11                    | 12       | 3.44%   |
| Ubuntu 19.04                 | 11       | 3.15%   |
| OpenMandriva 4.3             | 9        | 2.58%   |
| UOS 20                       | 8        | 2.29%   |
| Ubuntu 21.04                 | 8        | 2.29%   |
| Debian 10                    | 8        | 2.29%   |
| Arch Rolling                 | 8        | 2.29%   |
| Ubuntu 16.04                 | 7        | 2.01%   |
| Ubuntu 19.10                 | 6        | 1.72%   |
| Manjaro                      | 6        | 1.72%   |
| Ubuntu 21.10                 | 5        | 1.43%   |
| OpenMandriva 4.2             | 5        | 1.43%   |
| Debian 8                     | 5        | 1.43%   |
| Ubuntu Unity 16.04           | 4        | 1.15%   |
| Ubuntu 18.10                 | 4        | 1.15%   |
| KDE neon 20.04               | 4        | 1.15%   |
| Fedora 36                    | 4        | 1.15%   |
| Fedora 32                    | 4        | 1.15%   |
| Debian Unstable              | 4        | 1.15%   |
| CentOS 7                     | 4        | 1.15%   |
| Ubuntu 20.10                 | 3        | 0.86%   |
| OpenMandriva 4.50            | 3        | 0.86%   |
| Linux Mint 20.3              | 3        | 0.86%   |
| Linux Mint 20.2              | 3        | 0.86%   |
| Gentoo 2.7                   | 3        | 0.86%   |
| Debian 9                     | 3        | 0.86%   |
| Atz 11.5                     | 3        | 0.86%   |
| Zorin 16                     | 2        | 0.57%   |
| Ubuntu 22.10                 | 2        | 0.57%   |
| Pop!_OS 21.04                | 2        | 0.57%   |
| openSUSE Tumbleweed-XXXXXXXX | 2        | 0.57%   |
| OpenMandriva 4.90            | 2        | 0.57%   |
| Linux Mint 20.1              | 2        | 0.57%   |
| Gentoo 2.8                   | 2        | 0.57%   |
| Gentoo 2.6                   | 2        | 0.57%   |
| Fedora 33                    | 2        | 0.57%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 153      | 45.13%  |
| Debian       | 36       | 10.62%  |
| Arch         | 27       | 7.96%   |
| OpenMandriva | 19       | 5.6%    |
| Manjaro      | 12       | 3.54%   |
| Linux Mint   | 11       | 3.24%   |
| Fedora       | 11       | 3.24%   |
| Deepin       | 10       | 2.95%   |
| Ubuntu Unity | 6        | 1.77%   |
| Gentoo       | 6        | 1.77%   |
| CentOS       | 6        | 1.77%   |
| KDE neon     | 5        | 1.47%   |
| Atz          | 5        | 1.47%   |
| ROSA         | 4        | 1.18%   |
| Pop!_OS      | 3        | 0.88%   |
| Clear Linux  | 3        | 0.88%   |
| Zorin        | 2        | 0.59%   |
| Xubuntu      | 2        | 0.59%   |
| openSUSE     | 2        | 0.59%   |
| NFS Desktop  | 2        | 0.59%   |
| Elementary   | 2        | 0.59%   |
| Ubuntu Kylin | 1        | 0.29%   |
| RHEL         | 1        | 0.29%   |
| RedFlag      | 1        | 0.29%   |
| RED          | 1        | 0.29%   |
| OpenEuler    | 1        | 0.29%   |
| LFS          | 1        | 0.29%   |
| Kubuntu      | 1        | 0.29%   |
| Endless      | 1        | 0.29%   |
| BlackPanther | 1        | 0.29%   |
| ArcoLinux    | 1        | 0.29%   |
| AOSC OS      | 1        | 0.29%   |
| ALT Linux    | 1        | 0.29%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Desktops | Percent |
|------------------------------------|----------|---------|
| 5.16.7-desktop-1omv4003            | 8        | 2.19%   |
| 5.15.0-52-generic                  | 6        | 1.64%   |
| 5.0.0-23-generic                   | 6        | 1.64%   |
| 5.15.0-56-generic                  | 5        | 1.37%   |
| 5.13.0-22-generic                  | 5        | 1.37%   |
| 5.10.14-desktop-1omv4002           | 5        | 1.37%   |
| 5.4.0-58-generic                   | 4        | 1.09%   |
| 5.13.0-30-generic                  | 4        | 1.09%   |
| 5.11.0-43-generic                  | 4        | 1.09%   |
| 5.0.0-25-generic                   | 4        | 1.09%   |
| 4.19.147-rivoreo-amd64             | 4        | 1.09%   |
| 4.18.0-16-generic                  | 4        | 1.09%   |
| 4.1.42-rivoreo-powerpc64           | 4        | 1.09%   |
| 5.8.0-50-generic                   | 3        | 0.82%   |
| 5.4.0-74-generic                   | 3        | 0.82%   |
| 5.4.0-42-generic                   | 3        | 0.82%   |
| 5.15.0-46-generic                  | 3        | 0.82%   |
| 5.12.4-desktop-1omv4050            | 3        | 0.82%   |
| 5.11.0-41-generic                  | 3        | 0.82%   |
| 5.10.35-gentoo                     | 3        | 0.82%   |
| 5.10.0-18-amd64                    | 3        | 0.82%   |
| 4.19.0-amd64-desktop               | 3        | 0.82%   |
| 4.18.0-10-generic                  | 3        | 0.82%   |
| 4.15.0-58-generic                  | 3        | 0.82%   |
| 4.1.42-rivoreo-powerpc64-largepage | 3        | 0.82%   |
| 5.8.0-63-generic                   | 2        | 0.55%   |
| 5.8.0-43-generic                   | 2        | 0.55%   |
| 5.4.0-73-generic                   | 2        | 0.55%   |
| 5.4.0-54-generic                   | 2        | 0.55%   |
| 5.4.0-49-generic                   | 2        | 0.55%   |
| 5.4.0-40-generic                   | 2        | 0.55%   |
| 5.4.0-33-generic                   | 2        | 0.55%   |
| 5.4.0-29-generic                   | 2        | 0.55%   |
| 5.4.0-125-generic                  | 2        | 0.55%   |
| 5.4.0-124-generic                  | 2        | 0.55%   |
| 5.4.0-121-generic                  | 2        | 0.55%   |
| 5.3.0-28-generic                   | 2        | 0.55%   |
| 5.18.12-desktop-3omv4090           | 2        | 0.55%   |
| 5.16.0-5-riscv64                   | 2        | 0.55%   |
| 5.15.0-25-generic                  | 2        | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.4.0    | 42       | 11.9%   |
| 4.15.0   | 25       | 7.08%   |
| 5.0.0    | 23       | 6.52%   |
| 5.15.0   | 21       | 5.95%   |
| 5.11.0   | 20       | 5.67%   |
| 4.18.0   | 18       | 5.1%    |
| 5.13.0   | 16       | 4.53%   |
| 5.10.0   | 14       | 3.97%   |
| 5.8.0    | 13       | 3.68%   |
| 5.16.7   | 8        | 2.27%   |
| 4.19.0   | 8        | 2.27%   |
| 5.3.0    | 7        | 1.98%   |
| 4.1.42   | 6        | 1.7%    |
| 5.10.14  | 5        | 1.42%   |
| 4.19.147 | 4        | 1.13%   |
| 5.16.0   | 3        | 0.85%   |
| 5.12.4   | 3        | 0.85%   |
| 5.10.35  | 3        | 0.85%   |
| 4.9.0    | 3        | 0.85%   |
| 3.10.0   | 3        | 0.85%   |
| 5.9.8    | 2        | 0.57%   |
| 5.9.10   | 2        | 0.57%   |
| 5.7.7    | 2        | 0.57%   |
| 5.6.14   | 2        | 0.57%   |
| 5.19.0   | 2        | 0.57%   |
| 5.18.16  | 2        | 0.57%   |
| 5.18.12  | 2        | 0.57%   |
| 5.18.0   | 2        | 0.57%   |
| 5.17.0   | 2        | 0.57%   |
| 5.16.13  | 2        | 0.57%   |
| 5.13.13  | 2        | 0.57%   |
| 5.10.4   | 2        | 0.57%   |
| 5.10.36  | 2        | 0.57%   |
| 5.10.19  | 2        | 0.57%   |
| 5.1.4    | 2        | 0.57%   |
| 4.4.0    | 2        | 0.57%   |
| 4.13.0   | 2        | 0.57%   |
| 6.1.0    | 1        | 0.28%   |
| 6.0.0    | 1        | 0.28%   |
| 5.9.9    | 1        | 0.28%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 50       | 14.25%  |
| 5.10    | 35       | 9.97%   |
| 5.15    | 32       | 9.12%   |
| 5.0     | 25       | 7.12%   |
| 4.15    | 25       | 7.12%   |
| 5.11    | 22       | 6.27%   |
| 5.13    | 19       | 5.41%   |
| 4.18    | 18       | 5.13%   |
| 5.8     | 14       | 3.99%   |
| 5.16    | 13       | 3.7%    |
| 4.19    | 13       | 3.7%    |
| 5.18    | 9        | 2.56%   |
| 5.9     | 8        | 2.28%   |
| 5.17    | 8        | 2.28%   |
| 5.3     | 7        | 1.99%   |
| 5.12    | 7        | 1.99%   |
| 4.1     | 6        | 1.71%   |
| 5.6     | 5        | 1.42%   |
| 4.9     | 5        | 1.42%   |
| 5.7     | 4        | 1.14%   |
| 5.19    | 4        | 1.14%   |
| 5.14    | 4        | 1.14%   |
| 3.10    | 3        | 0.85%   |
| 5.1     | 2        | 0.57%   |
| 4.4     | 2        | 0.57%   |
| 4.13    | 2        | 0.57%   |
| 6.1     | 1        | 0.28%   |
| 6.0     | 1        | 0.28%   |
| 5.5     | 1        | 0.28%   |
| 5.2     | 1        | 0.28%   |
| 4.20    | 1        | 0.28%   |
| 4.14    | 1        | 0.28%   |
| 3.4     | 1        | 0.28%   |
| 2.6.16  | 1        | 0.28%   |
| 2.6     | 1        | 0.28%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 315      | 93.75%  |
| ppc64   | 6        | 1.79%   |
| riscv64 | 5        | 1.49%   |
| aarch64 | 3        | 0.89%   |
| i686    | 2        | 0.6%    |
| sh4a    | 1        | 0.3%    |
| ppc64le | 1        | 0.3%    |
| ppc     | 1        | 0.3%    |
| mips64  | 1        | 0.3%    |
| i586    | 1        | 0.3%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| GNOME         | 137      | 40.06%  |
| Unknown       | 91       | 26.61%  |
| KDE5          | 41       | 11.99%  |
| XFCE          | 25       | 7.31%   |
| Deepin        | 9        | 2.63%   |
| KDE           | 8        | 2.34%   |
| X-Cinnamon    | 6        | 1.75%   |
| Unity         | 6        | 1.75%   |
| MATE          | 4        | 1.17%   |
| Pantheon      | 2        | 0.58%   |
| LXDE          | 2        | 0.58%   |
| KDE4          | 2        | 0.58%   |
| i3            | 2        | 0.58%   |
| Cinnamon      | 2        | 0.58%   |
| UKUI          | 1        | 0.29%   |
| sway          | 1        | 0.29%   |
| GNOME Classic | 1        | 0.29%   |
| Budgie        | 1        | 0.29%   |
| awesome       | 1        | 0.29%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 230      | 68.25%  |
| Unknown | 41       | 12.17%  |
| Wayland | 39       | 11.57%  |
| Tty     | 27       | 8.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 184      | 54.44%  |
| GDM     | 39       | 11.54%  |
| GDM3    | 37       | 10.95%  |
| SDDM    | 36       | 10.65%  |
| LightDM | 33       | 9.76%   |
| TDM     | 6        | 1.78%   |
| KDM     | 2        | 0.59%   |
| LXDM    | 1        | 0.3%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| zh_CN       | 145      | 42.52%  |
| en_US       | 105      | 30.79%  |
| Unknown     | 63       | 18.48%  |
| C           | 19       | 5.57%   |
| en_HK       | 2        | 0.59%   |
| en_GB       | 2        | 0.59%   |
| ru_RU       | 1        | 0.29%   |
| ja_JP       | 1        | 0.29%   |
| en_US.utf-8 | 1        | 0.29%   |
| en_SG       | 1        | 0.29%   |
| en_AU       | 1        | 0.29%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 172      | 50.74%  |
| BIOS | 167      | 49.26%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type       | Desktops | Percent |
|------------|----------|---------|
| Ext4       | 273      | 80.29%  |
| Overlay    | 18       | 5.29%   |
| Btrfs      | 16       | 4.71%   |
| Xfs        | 15       | 4.41%   |
| Unknown    | 10       | 2.94%   |
| Zfs        | 4        | 1.18%   |
| Rootfs     | 2        | 0.59%   |
| Reiserfs   | 1        | 0.29%   |
| Fuse.sshfs | 1        | 0.29%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 165      | 48.96%  |
| GPT     | 123      | 36.5%   |
| MBR     | 49       | 14.54%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 274      | 80.83%  |
| Yes       | 65       | 19.17%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 208      | 61.36%  |
| Yes       | 131      | 38.64%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUSTek Computer               | 76       | 22.62%  |
| Lenovo                         | 46       | 13.69%  |
| Gigabyte Technology            | 43       | 12.8%   |
| MSI                            | 34       | 10.12%  |
| Dell                           | 23       | 6.85%   |
| Unknown                        | 18       | 5.36%   |
| ASRock                         | 13       | 3.87%   |
| Hewlett-Packard                | 11       | 3.27%   |
| Intel                          | 10       | 2.98%   |
| TSINGHUA TONGFANG COMPUTER     | 5        | 1.49%   |
| OEM                            | 5        | 1.49%   |
| Huanan                         | 5        | 1.49%   |
| Colorful Technology            | 4        | 1.19%   |
| Biostar                        | 3        | 0.89%   |
| ONDA                           | 2        | 0.6%    |
| HUAWEI                         | 2        | 0.6%    |
| Google                         | 2        | 0.6%    |
| ECS                            | 2        | 0.6%    |
| AZW                            | 2        | 0.6%    |
| AMD                            | 2        | 0.6%    |
| Acer                           | 2        | 0.6%    |
| Yeston Digital Technology      | 1        | 0.3%    |
| Yanling                        | 1        | 0.3%    |
| X79-1356                       | 1        | 0.3%    |
| SYWZ                           | 1        | 0.3%    |
| Soyo                           | 1        | 0.3%    |
| Shanghai Zhaoxin Semiconductor | 1        | 0.3%    |
| Sapphire                       | 1        | 0.3%    |
| retsamarret                    | 1        | 0.3%    |
| RBQ                            | 1        | 0.3%    |
| Pegatron                       | 1        | 0.3%    |
| NORCO                          | 1        | 0.3%    |
| MAXSUN                         | 1        | 0.3%    |
| MAINBRD                        | 1        | 0.3%    |
| LORD ELECTRONICS               | 1        | 0.3%    |
| Loongson                       | 1        | 0.3%    |
| J&W                            | 1        | 0.3%    |
| Inspur                         | 1        | 0.3%    |
| IBM                            | 1        | 0.3%    |
| Huanghe                        | 1        | 0.3%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Unknown                                   | 23       | 6.85%   |
| ASUS All Series                           | 11       | 3.27%   |
| MSI MS-7B89                               | 6        | 1.79%   |
| TSINGHUA TONGFANG COMPUTER E500           | 5        | 1.49%   |
| ASUS TUF Gaming B550M-PLUS                | 5        | 1.49%   |
| MSI MS-7C94                               | 4        | 1.19%   |
| ASUS M5A78L-M LX3 PLUS                    | 3        | 0.89%   |
| MSI MS-7A40                               | 2        | 0.6%    |
| Lenovo YangTianT4900c-00 90ETCTO1WW       | 2        | 0.6%    |
| Lenovo ThinkStation P300 10DACTO1WW       | 2        | 0.6%    |
| Lenovo ThinkCentre M910t-N000 10N9CTO1WW  | 2        | 0.6%    |
| Gigabyte Z87P-D3                          | 2        | 0.6%    |
| Gigabyte F2A88XM-D3H                      | 2        | 0.6%    |
| Gigabyte B85M-D2V-SI                      | 2        | 0.6%    |
| Dell Precision 3660                       | 2        | 0.6%    |
| Dell OptiPlex 9020                        | 2        | 0.6%    |
| Dell OptiPlex 7060                        | 2        | 0.6%    |
| Dell OptiPlex 7010                        | 2        | 0.6%    |
| ASUS Z170-A                               | 2        | 0.6%    |
| ASUS TUF Gaming Z590-PLUS WIFI            | 2        | 0.6%    |
| ASUS TUF B450M-PLUS GAMING                | 2        | 0.6%    |
| ASUS PRIME Z370-A                         | 2        | 0.6%    |
| ASUS PRIME B450M-A                        | 2        | 0.6%    |
| ASRock Z170 Gaming K4                     | 2        | 0.6%    |
| Acer Aspire TC-606                        | 2        | 0.6%    |
| Yeston Digital YESTON A78L Policeman V3.1 | 1        | 0.3%    |
| Yanling YL-KBRL2 Series                   | 1        | 0.3%    |
| SYWZ S210H Series                         | 1        | 0.3%    |
| Soyo SY-I5GC2-L                           | 1        | 0.3%    |
| Shanghai Zhaoxin ZXE CRB                  | 1        | 0.3%    |
| Sapphire Pure Platinum 970A-PLUS          | 1        | 0.3%    |
| RBQ RongBotQiu                            | 1        | 0.3%    |
| Pegatron BYT-X1                           | 1        | 0.3%    |
| ONDA ONDA B320-IPC                        | 1        | 0.3%    |
| ONDA M3 miniPC                            | 1        | 0.3%    |
| OEM ZXE CRB                               | 1        | 0.3%    |
| OEM V1.0                                  | 1        | 0.3%    |
| OEM TOP77D                                | 1        | 0.3%    |
| OEM H310MD4                               | 1        | 0.3%    |
| NORCO BPC-7951                            | 1        | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| Unknown                         | 23       | 6.85%   |
| ASUS TUF                        | 16       | 4.76%   |
| ASUS PRIME                      | 16       | 4.76%   |
| Dell OptiPlex                   | 14       | 4.17%   |
| Lenovo ThinkCentre              | 11       | 3.27%   |
| ASUS All                        | 11       | 3.27%   |
| Lenovo ThinkStation             | 7        | 2.08%   |
| MSI MS-7B89                     | 6        | 1.79%   |
| ASUS ROG                        | 6        | 1.79%   |
| TSINGHUA TONGFANG COMPUTER E500 | 5        | 1.49%   |
| Dell Precision                  | 5        | 1.49%   |
| MSI MS-7C94                     | 4        | 1.19%   |
| Lenovo ZHENGJIUZHE              | 4        | 1.19%   |
| Huanan X79                      | 3        | 0.89%   |
| HP ProDesk                      | 3        | 0.89%   |
| Dell Inspiron                   | 3        | 0.89%   |
| ASUS M5A78L-M                   | 3        | 0.89%   |
| MSI MS-7A40                     | 2        | 0.6%    |
| Lenovo YangTianT4900v-00        | 2        | 0.6%    |
| Lenovo YangTianT4900c-00        | 2        | 0.6%    |
| Gigabyte Z87P-D3                | 2        | 0.6%    |
| Gigabyte X570                   | 2        | 0.6%    |
| Gigabyte F2A88XM-D3H            | 2        | 0.6%    |
| Gigabyte B85M-D2V-SI            | 2        | 0.6%    |
| Gigabyte B450M                  | 2        | 0.6%    |
| Gigabyte B450                   | 2        | 0.6%    |
| ASUS Z170-A                     | 2        | 0.6%    |
| ASUS M5A97                      | 2        | 0.6%    |
| ASRock Z170                     | 2        | 0.6%    |
| Acer Aspire                     | 2        | 0.6%    |
| Yeston Digital YESTON           | 1        | 0.3%    |
| Yanling YL-KBRL2                | 1        | 0.3%    |
| SYWZ S210H                      | 1        | 0.3%    |
| Soyo SY-I5GC2-L                 | 1        | 0.3%    |
| Shanghai Zhaoxin ZXE            | 1        | 0.3%    |
| Sapphire Pure                   | 1        | 0.3%    |
| RBQ RongBotQiu                  | 1        | 0.3%    |
| Pegatron BYT-X1                 | 1        | 0.3%    |
| ONDA ONDA                       | 1        | 0.3%    |
| ONDA M3                         | 1        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 58       | 17.26%  |
| 2020    | 41       | 12.2%   |
| 2019    | 31       | 9.23%   |
| 2017    | 27       | 8.04%   |
| 2015    | 24       | 7.14%   |
| 2013    | 23       | 6.85%   |
| 2021    | 22       | 6.55%   |
| 2012    | 21       | 6.25%   |
| 2014    | 20       | 5.95%   |
| 2016    | 16       | 4.76%   |
| Unknown | 16       | 4.76%   |
| 2011    | 10       | 2.98%   |
| 2022    | 9        | 2.68%   |
| 2009    | 6        | 1.79%   |
| 2010    | 5        | 1.49%   |
| 2008    | 4        | 1.19%   |
| 2007    | 3        | 0.89%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 336      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 328      | 97.62%  |
| Enabled  | 8        | 2.38%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 334      | 99.4%   |
| Yes  | 2        | 0.6%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 88       | 25.96%  |
| 4.01-8.0        | 59       | 17.4%   |
| 8.01-16.0       | 56       | 16.52%  |
| 32.01-64.0      | 52       | 15.34%  |
| 3.01-4.0        | 31       | 9.14%   |
| 64.01-256.0     | 23       | 6.78%   |
| Unknown         | 10       | 2.95%   |
| 24.01-32.0      | 8        | 2.36%   |
| 1.01-2.0        | 5        | 1.47%   |
| 0.51-1.0        | 2        | 0.59%   |
| 0.01-0.5        | 2        | 0.59%   |
| More than 256.0 | 1        | 0.29%   |
| 2.01-3.0        | 1        | 0.29%   |
| 0               | 1        | 0.29%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 115      | 32.03%  |
| 2.01-3.0    | 82       | 22.84%  |
| 4.01-8.0    | 47       | 13.09%  |
| 3.01-4.0    | 42       | 11.7%   |
| 0.51-1.0    | 16       | 4.46%   |
| 8.01-16.0   | 14       | 3.9%    |
| 0.01-0.5    | 14       | 3.9%    |
| Unknown     | 13       | 3.62%   |
| 16.01-24.0  | 10       | 2.79%   |
| 32.01-64.0  | 3        | 0.84%   |
| 24.01-32.0  | 2        | 0.56%   |
| 64.01-256.0 | 1        | 0.28%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 136      | 39.65%  |
| 2      | 111      | 32.36%  |
| 3      | 47       | 13.7%   |
| 4      | 23       | 6.71%   |
| 5      | 12       | 3.5%    |
| 0      | 6        | 1.75%   |
| 6      | 3        | 0.87%   |
| 9      | 2        | 0.58%   |
| 46     | 1        | 0.29%   |
| 11     | 1        | 0.29%   |
| 10     | 1        | 0.29%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 271      | 80.18%  |
| Yes       | 67       | 19.82%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 327      | 97.32%  |
| No        | 9        | 2.68%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 184      | 54.28%  |
| Yes       | 155      | 45.72%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 228      | 66.09%  |
| Yes       | 117      | 33.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| China   | 336      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Beijing          | 70       | 20.29%  |
| Shenzhen         | 28       | 8.12%   |
| Shanghai         | 27       | 7.83%   |
| Guangzhou        | 21       | 6.09%   |
| Wuhan            | 12       | 3.48%   |
| Hangzhou         | 10       | 2.9%    |
| Chengdu          | 10       | 2.9%    |
| Nanhao           | 9        | 2.61%   |
| Nanjing          | 8        | 2.32%   |
| Xi'an            | 7        | 2.03%   |
| Tianjin          | 6        | 1.74%   |
| Chongqing        | 6        | 1.74%   |
| Zhengzhou        | 5        | 1.45%   |
| Xuhui            | 5        | 1.45%   |
| Xiamen           | 4        | 1.16%   |
| Qingdao          | 4        | 1.16%   |
| Jinan            | 4        | 1.16%   |
| Haidian          | 4        | 1.16%   |
| Foshan           | 4        | 1.16%   |
| Suzhou           | 3        | 0.87%   |
| Putuo            | 3        | 0.87%   |
| Hefei            | 3        | 0.87%   |
| Xicheng District | 2        | 0.58%   |
| Wuxi             | 2        | 0.58%   |
| Wulipu           | 2        | 0.58%   |
| Wuhu             | 2        | 0.58%   |
| Nanning          | 2        | 0.58%   |
| Lanzhou          | 2        | 0.58%   |
| Kunming          | 2        | 0.58%   |
| Huangpu          | 2        | 0.58%   |
| Hongkou          | 2        | 0.58%   |
| Hohhot           | 2        | 0.58%   |
| Guiyang          | 2        | 0.58%   |
| Geleshan         | 2        | 0.58%   |
| Chenzhou         | 2        | 0.58%   |
| Changsha         | 2        | 0.58%   |
| Zibo             | 1        | 0.29%   |
| Zhuhai           | 1        | 0.29%   |
| Zhongba          | 1        | 0.29%   |
| Zhejiang         | 1        | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 116      | 214    | 19.33%  |
| WDC                 | 115      | 157    | 19.17%  |
| Samsung Electronics | 67       | 86     | 11.17%  |
| Toshiba             | 35       | 50     | 5.83%   |
| SanDisk             | 24       | 28     | 4%      |
| Kingston            | 21       | 24     | 3.5%    |
| Intel               | 18       | 24     | 3%      |
| Unknown             | 14       | 23     | 2.33%   |
| Silicon Motion      | 13       | 16     | 2.17%   |
| Plextor             | 9        | 11     | 1.5%    |
| HGST                | 9        | 15     | 1.5%    |
| Hitachi             | 8        | 13     | 1.33%   |
| FORESEE             | 7        | 7      | 1.17%   |
| Phison              | 6        | 8      | 1%      |
| GLOWAY              | 6        | 8      | 1%      |
| Crucial             | 6        | 6      | 1%      |
| GALAX               | 5        | 5      | 0.83%   |
| Colorful            | 5        | 6      | 0.83%   |
| Unknown             | 5        | 8      | 0.83%   |
| ZHITAI              | 4        | 4      | 0.67%   |
| Teclast             | 4        | 4      | 0.67%   |
| SK hynix            | 4        | 4      | 0.67%   |
| Netac               | 4        | 5      | 0.67%   |
| Lite-On             | 4        | 6      | 0.67%   |
| Lenovo              | 4        | 5      | 0.67%   |
| Hewlett-Packard     | 4        | 5      | 0.67%   |
| Micron Technology   | 3        | 4      | 0.5%    |
| LITEON              | 3        | 5      | 0.5%    |
| KIOXIA-EXCERIA      | 3        | 3      | 0.5%    |
| Fujitsu             | 3        | 3      | 0.5%    |
| Faspeed             | 3        | 3      | 0.5%    |
| China               | 3        | 3      | 0.5%    |
| A-DATA Technology   | 3        | 3      | 0.5%    |
| tigo                | 2        | 2      | 0.33%   |
| ShineDisk           | 2        | 2      | 0.33%   |
| Q200                | 2        | 5      | 0.33%   |
| Pear                | 2        | 5      | 0.33%   |
| OCZ                 | 2        | 2      | 0.33%   |
| KingShare           | 2        | 2      | 0.33%   |
| KINGBANK            | 2        | 2      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| WDC WD10EZEX-08WN4A0 1TB               | 19       | 2.85%   |
| Seagate ST1000DM010-2EP102 1TB         | 12       | 1.8%    |
| Seagate ST1000DM003-1SB102 1TB         | 12       | 1.8%    |
| Seagate ST500DM002-1BD142 500GB        | 9        | 1.35%   |
| WDC WD10EZEX-08M2NA0 1TB               | 6        | 0.9%    |
| Seagate ST3500418AS 500GB              | 6        | 0.9%    |
| SanDisk NVMe SSD Drive 1TB             | 6        | 0.9%    |
| WDC WDS100T2B0C-00PXH0 1TB             | 5        | 0.75%   |
| Toshiba DT01ACA200 2TB                 | 5        | 0.75%   |
| Seagate ST3000DM008-2DM166 3TB         | 5        | 0.75%   |
| Seagate ST3000DM001-1ER166 3TB         | 5        | 0.75%   |
| Seagate ST2000DM006-2DM164 2TB         | 5        | 0.75%   |
| Seagate ST1000DM003-1ER162 1TB         | 5        | 0.75%   |
| Samsung SSD 860 EVO 500GB              | 5        | 0.75%   |
| Kingston SA400S37480G 480GB SSD        | 5        | 0.75%   |
| Unknown                                | 5        | 0.75%   |
| WDC WD10EZEX-22MFCA0 1TB               | 4        | 0.6%    |
| Toshiba TR200 480GB SSD                | 4        | 0.6%    |
| Seagate ST300MM0008 304GB              | 4        | 0.6%    |
| Seagate ST300MM0006 304GB              | 4        | 0.6%    |
| Samsung NVMe SSD Drive 128GB           | 4        | 0.6%    |
| WDC WD30EZRZ-00GXCB0 3TB               | 3        | 0.45%   |
| Unknown SD64G  64GB                    | 3        | 0.45%   |
| Toshiba Q300. 240GB SSD                | 3        | 0.45%   |
| Toshiba DT01ACA300 3TB                 | 3        | 0.45%   |
| Toshiba DT01ACA100 LENOVO 1TB          | 3        | 0.45%   |
| Toshiba DT01ACA100 1TB                 | 3        | 0.45%   |
| Silicon Motion NVMe SSD Drive 1024GB   | 3        | 0.45%   |
| Seagate ST6000NM0115-1YZ110 6TB        | 3        | 0.45%   |
| Seagate ST31000524AS 1TB               | 3        | 0.45%   |
| Seagate ST2000DM001-1ER164 2TB         | 3        | 0.45%   |
| Seagate ST1000DM003-1CH162 1TB         | 3        | 0.45%   |
| SanDisk NVMe SSD Drive 2TB             | 3        | 0.45%   |
| Samsung SSD 860 EVO 250GB              | 3        | 0.45%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 3        | 0.45%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB | 3        | 0.45%   |
| Samsung NVMe SSD Drive 500GB           | 3        | 0.45%   |
| Netac SSD 120GB                        | 3        | 0.45%   |
| Lite-On NVMe SSD Drive 1024GB          | 3        | 0.45%   |
| GALAX TA1D0240A 240GB                  | 3        | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 115      | 213    | 42.44%  |
| WDC                 | 101      | 133    | 37.27%  |
| Toshiba             | 26       | 36     | 9.59%   |
| HGST                | 9        | 15     | 3.32%   |
| Hitachi             | 8        | 13     | 2.95%   |
| Samsung Electronics | 4        | 4      | 1.48%   |
| Fujitsu             | 3        | 3      | 1.11%   |
| Pear 2TB            | 1        | 1      | 0.37%   |
| IBM H0              | 1        | 1      | 0.37%   |
| Hewlett-Packard     | 1        | 1      | 0.37%   |
| ACASIS              | 1        | 1      | 0.37%   |
| Unknown             | 1        | 2      | 0.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 34       | 40     | 18.68%  |
| Kingston            | 14       | 16     | 7.69%   |
| Intel               | 12       | 18     | 6.59%   |
| Toshiba             | 11       | 12     | 6.04%   |
| SanDisk             | 9        | 10     | 4.95%   |
| Plextor             | 8        | 9      | 4.4%    |
| WDC                 | 6        | 7      | 3.3%    |
| GLOWAY              | 5        | 7      | 2.75%   |
| GALAX               | 5        | 5      | 2.75%   |
| Crucial             | 5        | 5      | 2.75%   |
| Unknown             | 4        | 5      | 2.2%    |
| Teclast             | 4        | 4      | 2.2%    |
| Netac               | 3        | 4      | 1.65%   |
| LITEON              | 3        | 5      | 1.65%   |
| Lenovo              | 3        | 4      | 1.65%   |
| FORESEE             | 3        | 3      | 1.65%   |
| China               | 3        | 3      | 1.65%   |
| A-DATA Technology   | 3        | 3      | 1.65%   |
| Unknown             | 3        | 5      | 1.65%   |
| ZHITAI              | 2        | 2      | 1.1%    |
| tigo                | 2        | 2      | 1.1%    |
| Q200                | 2        | 5      | 1.1%    |
| Pear                | 2        | 5      | 1.1%    |
| OCZ                 | 2        | 2      | 1.1%    |
| Micron Technology   | 2        | 3      | 1.1%    |
| KingShare           | 2        | 2      | 1.1%    |
| KINGBANK            | 2        | 2      | 1.1%    |
| Faspeed             | 2        | 2      | 1.1%    |
| Colorful            | 2        | 2      | 1.1%    |
| Vaseky              | 1        | 1      | 0.55%   |
| UNIC2               | 1        | 1      | 0.55%   |
| StoreJet            | 1        | 1      | 0.55%   |
| Soyo                | 1        | 1      | 0.55%   |
| ShineDisk           | 1        | 1      | 0.55%   |
| NORCO               | 1        | 1      | 0.55%   |
| NGFF                | 1        | 1      | 0.55%   |
| MX                  | 1        | 1      | 0.55%   |
| Maxmemroy           | 1        | 1      | 0.55%   |
| MAXIO               | 1        | 1      | 0.55%   |
| Lexar               | 1        | 1      | 0.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 217      | 423    | 42.38%  |
| SSD     | 150      | 220    | 29.3%   |
| NVMe    | 119      | 163    | 23.24%  |
| Unknown | 20       | 25     | 3.91%   |
| MMC     | 6        | 10     | 1.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 282      | 627    | 65.28%  |
| NVMe | 118      | 162    | 27.31%  |
| SAS  | 26       | 42     | 6.02%   |
| MMC  | 6        | 10     | 1.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 183      | 305    | 46.33%  |
| 0.51-1.0   | 134      | 165    | 33.92%  |
| 1.01-2.0   | 33       | 47     | 8.35%   |
| 2.01-3.0   | 15       | 26     | 3.8%    |
| 3.01-4.0   | 12       | 19     | 3.04%   |
| 4.01-10.0  | 11       | 68     | 2.78%   |
| 10.01-20.0 | 7        | 13     | 1.77%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 83       | 23.85%  |
| 251-500        | 62       | 17.82%  |
| 501-1000       | 55       | 15.8%   |
| 1001-2000      | 36       | 10.34%  |
| More than 3000 | 28       | 8.05%   |
| 51-100         | 27       | 7.76%   |
| 1-20           | 19       | 5.46%   |
| 21-50          | 16       | 4.6%    |
| 2001-3000      | 13       | 3.74%   |
| Unknown        | 9        | 2.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 145      | 40.5%   |
| 101-250        | 54       | 15.08%  |
| 21-50          | 46       | 12.85%  |
| 51-100         | 33       | 9.22%   |
| 251-500        | 28       | 7.82%   |
| 501-1000       | 16       | 4.47%   |
| 1001-2000      | 13       | 3.63%   |
| Unknown        | 9        | 2.51%   |
| More than 3000 | 8        | 2.23%   |
| 2001-3000      | 6        | 1.68%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST31000524AS 1TB              | 2        | 2      | 7.14%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 1        | 1      | 3.57%   |
| WDC WD5003ABYZ-011FA0 500GB           | 1        | 1      | 3.57%   |
| WDC WD5000AAKX-08ERMA0 500GB          | 1        | 1      | 3.57%   |
| WDC WD5000AAKX-00PWEA0 500GB          | 1        | 1      | 3.57%   |
| WDC WD5000AAKX-0 500GB                | 1        | 1      | 3.57%   |
| WDC WD20EARX-00PASB0 2TB              | 1        | 1      | 3.57%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1        | 1      | 3.57%   |
| WDC WD10EZEX-00BN5A0 1TB              | 1        | 1      | 3.57%   |
| Toshiba DT01ACA300 3TB                | 1        | 1      | 3.57%   |
| Toshiba DT01ACA100 1TB                | 1        | 1      | 3.57%   |
| Seagate ST980811AS 80GB               | 1        | 1      | 3.57%   |
| Seagate ST750LM022 HN-M750MBB 752GB   | 1        | 1      | 3.57%   |
| Seagate ST500LT012-1DG142 500GB       | 1        | 1      | 3.57%   |
| Seagate ST500DM009-2DM14C 500GB       | 1        | 1      | 3.57%   |
| Seagate ST500DM002-1BD142 500GB       | 1        | 1      | 3.57%   |
| Seagate ST5000AS0011-1L5178 5TB       | 1        | 1      | 3.57%   |
| Samsung Electronics SSD 970 EVO 500GB | 1        | 1      | 3.57%   |
| Plextor PX-256M6S+ 256GB SSD          | 1        | 1      | 3.57%   |
| Intel SSDSC2KW256G8 256GB             | 1        | 1      | 3.57%   |
| Intel SSDSC2KW240H6 240GB             | 1        | 1      | 3.57%   |
| Intel SSDSC2BW360H6 360GB             | 1        | 1      | 3.57%   |
| GLOWAY VAL120GS3-S7 120GB SSD         | 1        | 3      | 3.57%   |
| GLOWAY FER120GS3-S7 120GB SSD         | 1        | 1      | 3.57%   |
| Fujitsu MJA2250BH G2 250GB            | 1        | 1      | 3.57%   |
| Crucial CT240M500SSD1 240GB           | 1        | 1      | 3.57%   |
| Colorful SL500 320GB SSD              | 1        | 1      | 3.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 8      | 29.63%  |
| Seagate             | 7        | 8      | 25.93%  |
| Intel               | 3        | 3      | 11.11%  |
| Toshiba             | 2        | 2      | 7.41%   |
| GLOWAY              | 2        | 4      | 7.41%   |
| Samsung Electronics | 1        | 1      | 3.7%    |
| Plextor             | 1        | 1      | 3.7%    |
| Fujitsu             | 1        | 1      | 3.7%    |
| Crucial             | 1        | 1      | 3.7%    |
| Colorful            | 1        | 1      | 3.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 7        | 7      | 41.18%  |
| Seagate | 7        | 8      | 41.18%  |
| Toshiba | 2        | 2      | 11.76%  |
| Fujitsu | 1        | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 16       | 18     | 66.67%  |
| SSD  | 7        | 11     | 29.17%  |
| NVMe | 1        | 1      | 4.17%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST31500341AS 1TB          | 1        | 1      | 25%     |
| Samsung Electronics HM160HI 160GB | 1        | 1      | 25%     |
| HGST HUH728080ALN600 8TB          | 1        | 1      | 25%     |
| Hewlett-Packard SSD S700 500GB    | 1        | 2      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1        | 1      | 25%     |
| Samsung Electronics | 1        | 1      | 25%     |
| HGST                | 1        | 1      | 25%     |
| Hewlett-Packard     | 1        | 2      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 197      | 475    | 54.27%  |
| Works    | 141      | 331    | 38.84%  |
| Malfunc  | 21       | 30     | 5.79%   |
| Failed   | 4        | 5      | 1.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 230      | 47.82%  |
| AMD                              | 81       | 16.84%  |
| Samsung Electronics              | 32       | 6.65%   |
| SanDisk                          | 29       | 6.03%   |
| Silicon Motion                   | 19       | 3.95%   |
| ASMedia Technology               | 11       | 2.29%   |
| Marvell Technology Group         | 9        | 1.87%   |
| Phison Electronics               | 7        | 1.46%   |
| Kingston Technology Company      | 7        | 1.46%   |
| SK hynix                         | 4        | 0.83%   |
| Lite-On Technology               | 4        | 0.83%   |
| JMicron Technology               | 4        | 0.83%   |
| IBM                              | 4        | 0.83%   |
| Shenzhen Longsys Electronics     | 3        | 0.62%   |
| Huawei Technologies              | 3        | 0.62%   |
| Broadcom / LSI                   | 3        | 0.62%   |
| Zhaoxin                          | 2        | 0.42%   |
| Yangtze Memory Technologies      | 2        | 0.42%   |
| Union Memory (Shenzhen)          | 2        | 0.42%   |
| Toshiba America Info Systems     | 2        | 0.42%   |
| Solid State Storage Technology   | 2        | 0.42%   |
| Silicon Image                    | 2        | 0.42%   |
| Mylex                            | 2        | 0.42%   |
| MAXIO Technology (Hangzhou)      | 2        | 0.42%   |
| KIOXIA                           | 2        | 0.42%   |
| Beijing Starblaze Technology     | 2        | 0.42%   |
| Silicon Integrated Systems [SiS] | 1        | 0.21%   |
| Seagate Technology               | 1        | 0.21%   |
| Realtek Semiconductor            | 1        | 0.21%   |
| Nvidia                           | 1        | 0.21%   |
| Micron/Crucial Technology        | 1        | 0.21%   |
| Micron Technology                | 1        | 0.21%   |
| LSI Logic / Symbios Logic        | 1        | 0.21%   |
| Loongson Technology              | 1        | 0.21%   |
| HighPoint Technologies           | 1        | 0.21%   |
| Hefei DATANG Storage Technology  | 1        | 0.21%   |
| ADATA Technology                 | 1        | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 47       | 8.25%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 33       | 5.79%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 30       | 5.26%   |
| AMD 400 Series Chipset SATA Controller                                                  | 26       | 4.56%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 18       | 3.16%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 16       | 2.81%   |
| AMD 500 Series Chipset SATA Controller                                                  | 16       | 2.81%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 15       | 2.63%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 15       | 2.63%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 12       | 2.11%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 12       | 2.11%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 11       | 1.93%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 11       | 1.93%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 11       | 1.93%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 10       | 1.75%   |
| SanDisk Non-Volatile memory controller                                                  | 9        | 1.58%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 8        | 1.4%    |
| Intel SATA Controller [RAID mode]                                                       | 8        | 1.4%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8        | 1.4%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 8        | 1.4%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7        | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7        | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 7        | 1.23%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 6        | 1.05%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 6        | 1.05%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 6        | 1.05%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6        | 1.05%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 5        | 0.88%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 5        | 0.88%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 5        | 0.88%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 5        | 0.88%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5        | 0.88%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 0.7%    |
| Phison PS5013 E13 NVMe Controller                                                       | 4        | 0.7%    |
| Lite-On Non-Volatile memory controller                                                  | 4        | 0.7%    |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 4        | 0.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4        | 0.7%    |
| IBM Obsidian chipset SCSI controller                                                    | 4        | 0.7%    |
| AMD FCH IDE Controller                                                                  | 4        | 0.7%    |
| Shenzhen Longsys Non-Volatile memory controller                                         | 3        | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 283      | 58.71%  |
| NVMe | 119      | 24.69%  |
| IDE  | 47       | 9.75%   |
| RAID | 25       | 5.19%   |
| SAS  | 5        | 1.04%   |
| SCSI | 3        | 0.62%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Intel             | 233      | 69.35%  |
| AMD               | 83       | 24.7%   |
| Unknown           | 6        | 1.79%   |
| CHRP IBM,8233-E8B | 4        | 1.19%   |
| sifive,bullet0    | 3        | 0.89%   |
| CHRP IBM,9131-52A | 2        | 0.6%    |
| CentaurHauls      | 2        | 0.6%    |
| sifive,u74-mc     | 1        | 0.3%    |
| PowerNV FP5466G2  | 1        | 0.3%    |
| FSP-1             | 1        | 0.3%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Intel Core i5-4590 CPU @ 3.30GHz                          | 10       | 2.97%   |
| Intel Core i7-8700 CPU @ 3.20GHz                          | 8        | 2.37%   |
| Intel Core i7-7700 CPU @ 3.60GHz                          | 8        | 2.37%   |
| Intel Core i7-4790 CPU @ 3.60GHz                          | 7        | 2.08%   |
| Intel Core i5-8400 CPU @ 2.80GHz                          | 6        | 1.78%   |
|                                                           | 6        | 1.78%   |
| Intel Core i7-10700 CPU @ 2.90GHz                         | 5        | 1.48%   |
| AMD Ryzen 7 3700X 8-Core Processor                        | 5        | 1.48%   |
| AMD Ryzen 5 3600 6-Core Processor                         | 5        | 1.48%   |
| AMD Ryzen 5 2600 Six-Core Processor                       | 5        | 1.48%   |
| Intel Xeon CPU E3-1231 v3 @ 3.40GHz                       | 4        | 1.19%   |
| Intel Core i7-8700K CPU @ 3.70GHz                         | 4        | 1.19%   |
| Intel Core i7-6700 CPU @ 3.40GHz                          | 4        | 1.19%   |
| Intel Core i5-7400 CPU @ 3.00GHz                          | 4        | 1.19%   |
| Intel Core i5-10400 CPU @ 2.90GHz                         | 4        | 1.19%   |
| Intel 12th Gen Core i9-12900K                             | 4        | 1.19%   |
| CHRP IBM,8233-E8B POWER7 (architected), altivec supported | 4        | 1.19%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics                | 4        | 1.19%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics               | 4        | 1.19%   |
| sifive,bullet0 rv64imafdc                                 | 3        | 0.89%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz                       | 3        | 0.89%   |
| Intel Pentium CPU G2030 @ 3.00GHz                         | 3        | 0.89%   |
| Intel Core i9-10900K CPU @ 3.70GHz                        | 3        | 0.89%   |
| Intel Core i7-7700K CPU @ 4.20GHz                         | 3        | 0.89%   |
| Intel Core i7-4790K CPU @ 4.00GHz                         | 3        | 0.89%   |
| Intel Core i5-9400F CPU @ 2.90GHz                         | 3        | 0.89%   |
| Intel Core i5-6500 CPU @ 3.20GHz                          | 3        | 0.89%   |
| Intel Core i5-4460 CPU @ 3.20GHz                          | 3        | 0.89%   |
| Intel Core i3-2100 CPU @ 3.10GHz                          | 3        | 0.89%   |
| Intel Celeron CPU J1900 @ 1.99GHz                         | 3        | 0.89%   |
| AMD Ryzen 7 5700G with Radeon Graphics                    | 3        | 0.89%   |
| AMD Ryzen 5 5600G with Radeon Graphics                    | 3        | 0.89%   |
| AMD Athlon II X2 240 Processor                            | 3        | 0.89%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz                       | 2        | 0.59%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz                       | 2        | 0.59%   |
| Intel Xeon CPU E3-1226 v3 @ 3.30GHz                       | 2        | 0.59%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz               | 2        | 0.59%   |
| Intel Core i7-4770 CPU @ 3.40GHz                          | 2        | 0.59%   |
| Intel Core i7-4600U CPU @ 2.10GHz                         | 2        | 0.59%   |
| Intel Core i7-3770 CPU @ 3.40GHz                          | 2        | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 64       | 19.05%  |
| Intel Core i5           | 56       | 16.67%  |
| Other                   | 36       | 10.71%  |
| Intel Xeon              | 32       | 9.52%   |
| AMD Ryzen 5             | 25       | 7.44%   |
| Intel Core i3           | 21       | 6.25%   |
| Intel Celeron           | 17       | 5.06%   |
| AMD Ryzen 7             | 14       | 4.17%   |
| Intel Pentium           | 9        | 2.68%   |
| AMD FX                  | 7        | 2.08%   |
| AMD Athlon II X2        | 6        | 1.79%   |
| Intel Core i9           | 5        | 1.49%   |
| Intel Core 2 Duo        | 4        | 1.19%   |
| AMD Ryzen 9             | 4        | 1.19%   |
| AMD Ryzen 7 PRO         | 4        | 1.19%   |
| AMD A8                  | 4        | 1.19%   |
| Intel Pentium Dual-Core | 3        | 0.89%   |
| Intel Genuine           | 3        | 0.89%   |
| AMD Athlon X4           | 3        | 0.89%   |
| AMD Athlon              | 3        | 0.89%   |
| Intel Core 2 Quad       | 2        | 0.6%    |
| Intel Atom              | 2        | 0.6%    |
| AMD Ryzen 5 PRO         | 2        | 0.6%    |
| Intel Xeon Bronze       | 1        | 0.3%    |
| Intel Pentium Dual      | 1        | 0.3%    |
| Intel Core 2            | 1        | 0.3%    |
| AMD Ryzen Threadripper  | 1        | 0.3%    |
| AMD Ryzen 3             | 1        | 0.3%    |
| AMD Phenom II X4        | 1        | 0.3%    |
| AMD Athlon II X4        | 1        | 0.3%    |
| AMD Athlon 64 X2        | 1        | 0.3%    |
| AMD A6                  | 1        | 0.3%    |
| AMD A10                 | 1        | 0.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 118      | 35.01%  |
| 2       | 73       | 21.66%  |
| 6       | 60       | 17.8%   |
| 8       | 39       | 11.57%  |
| 12      | 11       | 3.26%   |
| 1       | 9        | 2.67%   |
| 16      | 7        | 2.08%   |
| 10      | 6        | 1.78%   |
| Unknown | 6        | 1.78%   |
| 24      | 3        | 0.89%   |
| 32      | 2        | 0.59%   |
| 40      | 1        | 0.3%    |
| 28      | 1        | 0.3%    |
| 3       | 1        | 0.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 321      | 95.54%  |
| 2       | 8        | 2.38%   |
| Unknown | 6        | 1.79%   |
| 6       | 1        | 0.3%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 205      | 61.01%  |
| 1       | 120      | 35.71%  |
| Unknown | 6        | 1.79%   |
| 4       | 5        | 1.49%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 318      | 94.64%  |
| Unknown        | 17       | 5.06%   |
| 64-bit         | 1        | 0.3%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 95       | 27.78%  |
| 0x306c3    | 34       | 9.94%   |
| 0x906ea    | 18       | 5.26%   |
| 0x906e9    | 16       | 4.68%   |
| 0x306a9    | 14       | 4.09%   |
| 0x206a7    | 12       | 3.51%   |
| 0x506e3    | 11       | 3.22%   |
| 0xa0655    | 9        | 2.63%   |
| 0x1067a    | 7        | 2.05%   |
| 0x90672    | 6        | 1.75%   |
| 0x30678    | 5        | 1.46%   |
| 0x08701013 | 5        | 1.46%   |
| 0x010000c8 | 5        | 1.46%   |
| 0xa0653    | 4        | 1.17%   |
| 0x306f2    | 4        | 1.17%   |
| 0x08701021 | 4        | 1.17%   |
| 0x0810100b | 4        | 1.17%   |
| 0x06003106 | 4        | 1.17%   |
| 0xa0671    | 3        | 0.88%   |
| 0x50654    | 3        | 0.88%   |
| 0x0a50000c | 3        | 0.88%   |
| 0x08600106 | 3        | 0.88%   |
| 0x0800820d | 3        | 0.88%   |
| 0x08001138 | 3        | 0.88%   |
| 0x06001119 | 3        | 0.88%   |
| 0x906ed    | 2        | 0.58%   |
| 0x906eb    | 2        | 0.58%   |
| 0x50657    | 2        | 0.58%   |
| 0x40651    | 2        | 0.58%   |
| 0x306f1    | 2        | 0.58%   |
| 0x306e4    | 2        | 0.58%   |
| 0x30661    | 2        | 0.58%   |
| 0x206d7    | 2        | 0.58%   |
| 0x206c2    | 2        | 0.58%   |
| 0x0a50000d | 2        | 0.58%   |
| 0x0a201009 | 2        | 0.58%   |
| 0x08101016 | 2        | 0.58%   |
| 0x0800820b | 2        | 0.58%   |
| 0x0600063e | 2        | 0.58%   |
| 0x010000c7 | 2        | 0.58%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 54       | 16.07%  |
| KabyLake         | 53       | 15.77%  |
| Unknown          | 28       | 8.33%   |
| Zen 2            | 22       | 6.55%   |
| IvyBridge        | 22       | 6.55%   |
| CometLake        | 22       | 6.55%   |
| Skylake          | 20       | 5.95%   |
| SandyBridge      | 15       | 4.46%   |
| Zen 3            | 12       | 3.57%   |
| Zen              | 12       | 3.57%   |
| Penryn           | 11       | 3.27%   |
| K10              | 9        | 2.68%   |
| Zen+             | 8        | 2.38%   |
| Piledriver       | 8        | 2.38%   |
| Silvermont       | 7        | 2.08%   |
| Alderlake Hybrid | 6        | 1.79%   |
| Steamroller      | 5        | 1.49%   |
| Core             | 3        | 0.89%   |
| Broadwell        | 3        | 0.89%   |
| Westmere         | 2        | 0.6%    |
| Bulldozer        | 2        | 0.6%    |
| Bonnell          | 2        | 0.6%    |
| Tremont          | 1        | 0.3%    |
| TigerLake        | 1        | 0.3%    |
| Puma             | 1        | 0.3%    |
| NetBurst         | 1        | 0.3%    |
| Nehalem          | 1        | 0.3%    |
| K8 Hammer        | 1        | 0.3%    |
| Icelake          | 1        | 0.3%    |
| Goldmont plus    | 1        | 0.3%    |
| Goldmont         | 1        | 0.3%    |
| Excavator        | 1        | 0.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 144      | 39.89%  |
| Nvidia                           | 103      | 28.53%  |
| AMD                              | 99       | 27.42%  |
| Matrox Electronics Systems       | 5        | 1.39%   |
| ASPEED Technology                | 4        | 1.11%   |
| Zhaoxin                          | 2        | 0.55%   |
| Silicon Integrated Systems [SiS] | 1        | 0.28%   |
| Moore Threads Technology         | 1        | 0.28%   |
| Loongson Technology              | 1        | 0.28%   |
| Cirrus Logic                     | 1        | 0.28%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 22       | 5.96%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 19       | 5.15%   |
| Intel HD Graphics 630                                                       | 13       | 3.52%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 12       | 3.25%   |
| Intel HD Graphics 530                                                       | 10       | 2.71%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 10       | 2.71%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 10       | 2.71%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 8        | 2.17%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 8        | 2.17%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 7        | 1.9%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7        | 1.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 6        | 1.63%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 6        | 1.63%   |
| Nvidia GK208B [GeForce GT 730]                                              | 5        | 1.36%   |
| Intel AlderLake-S GT1                                                       | 5        | 1.36%   |
| AMD Renoir                                                                  | 5        | 1.36%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 4        | 1.08%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4        | 1.08%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 4        | 1.08%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 4        | 1.08%   |
| Matrox Electronics Systems Millennium G550                                  | 4        | 1.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 4        | 1.08%   |
| ASPEED Technology ASPEED Graphics Family                                    | 4        | 1.08%   |
| AMD RS780L [Radeon 3000]                                                    | 4        | 1.08%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 4        | 1.08%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 3        | 0.81%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 3        | 0.81%   |
| Nvidia GT200GL [Quadro FX 4800]                                             | 3        | 0.81%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 0.81%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 0.81%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 3        | 0.81%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 0.81%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 0.81%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 3        | 0.81%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 3        | 0.81%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 3        | 0.81%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 3        | 0.81%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 3        | 0.81%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 3        | 0.81%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 3        | 0.81%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| 1 x Intel                    | 120      | 35.4%   |
| 1 x AMD                      | 90       | 26.55%  |
| 1 x Nvidia                   | 88       | 25.96%  |
| Other                        | 6        | 1.77%   |
| 2 x Nvidia                   | 5        | 1.47%   |
| 1 x Matrox                   | 5        | 1.47%   |
| Intel + Nvidia               | 4        | 1.18%   |
| Intel + AMD                  | 4        | 1.18%   |
| AMD + Nvidia                 | 3        | 0.88%   |
| 1 x Zhaoxin                  | 2        | 0.59%   |
| Nvidia + ASPEED              | 2        | 0.59%   |
| 2 x Intel                    | 1        | 0.29%   |
| 2 x AMD                      | 1        | 0.29%   |
| 1 x SiS                      | 1        | 0.29%   |
| 1 x Moore Threads Technology | 1        | 0.29%   |
| 1 x Loongson Technology      | 1        | 0.29%   |
| 1 x Intel + 3 x Nvidia       | 1        | 0.29%   |
| Intel + 2 x Nvidia           | 1        | 0.29%   |
| 1 x Cirrus Logic             | 1        | 0.29%   |
| 1 x ASPEED                   | 1        | 0.29%   |
| AMD + ASPEED                 | 1        | 0.29%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 239      | 70.09%  |
| Proprietary | 58       | 17.01%  |
| Unknown     | 44       | 12.9%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 185      | 54.25%  |
| 1.01-2.0   | 37       | 10.85%  |
| 0.51-1.0   | 28       | 8.21%   |
| 0.01-0.5   | 26       | 7.62%   |
| 3.01-4.0   | 22       | 6.45%   |
| 7.01-8.0   | 16       | 4.69%   |
| 5.01-6.0   | 10       | 2.93%   |
| 2.01-3.0   | 5        | 1.47%   |
| 8.01-16.0  | 5        | 1.47%   |
| 16.01-24.0 | 3        | 0.88%   |
| 4.01-5.0   | 2        | 0.59%   |
| 24.01-32.0 | 2        | 0.59%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 54       | 17.65%  |
| AOC                  | 43       | 14.05%  |
| Lenovo               | 32       | 10.46%  |
| Samsung Electronics  | 20       | 6.54%   |
| Philips              | 19       | 6.21%   |
| Goldstar             | 13       | 4.25%   |
| ViewSonic            | 12       | 3.92%   |
| Hewlett-Packard      | 11       | 3.59%   |
| Acer                 | 9        | 2.94%   |
| BenQ                 | 8        | 2.61%   |
| HKC                  | 5        | 1.63%   |
| Xiaomi               | 3        | 0.98%   |
| Unknown              | 3        | 0.98%   |
| RTK                  | 3        | 0.98%   |
| LG Electronics       | 3        | 0.98%   |
| Lenovo Group Limited | 3        | 0.98%   |
| IPS                  | 3        | 0.98%   |
| Ancor Communications | 3        | 0.98%   |
| TFC                  | 2        | 0.65%   |
| Sony                 | 2        | 0.65%   |
| SKY                  | 2        | 0.65%   |
| Mi                   | 2        | 0.65%   |
| KOIOS                | 2        | 0.65%   |
| HannStar             | 2        | 0.65%   |
| Envision Peripherals | 2        | 0.65%   |
| Eizo                 | 2        | 0.65%   |
| DSC                  | 2        | 0.65%   |
| CHR                  | 2        | 0.65%   |
| CHD                  | 2        | 0.65%   |
| BOE                  | 2        | 0.65%   |
| AGO                  | 2        | 0.65%   |
| Unknown              | 2        | 0.65%   |
| ZTY                  | 1        | 0.33%   |
| ZLS                  | 1        | 0.33%   |
| Xiangye              | 1        | 0.33%   |
| Unknown (AAA)        | 1        | 0.33%   |
| TUP                  | 1        | 0.33%   |
| TCL                  | 1        | 0.33%   |
| SZS                  | 1        | 0.33%   |
| SUG                  | 1        | 0.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| AOC 24B1W1G5 AOC2401 1920x1080 527x296mm 23.8-inch                | 4        | 1.23%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch           | 3        | 0.92%   |
| Lenovo LEN T2254A LEN60CD 1680x1050 474x296mm 22.0-inch           | 3        | 0.92%   |
| Dell P2422H DELA1C5 1920x1080 527x296mm 23.8-inch                 | 3        | 0.92%   |
| Dell P2422H DELA1C3 1920x1080 527x296mm 23.8-inch                 | 3        | 0.92%   |
| AOC Q27P1B AOC2701 2560x1440 597x336mm 27.0-inch                  | 3        | 0.92%   |
| AOC Q2790 AOC2790 2560x1440 597x336mm 27.0-inch                   | 3        | 0.92%   |
| Xiaomi Mi TV XMD004A 1920x1080 708x398mm 32.0-inch                | 2        | 0.62%   |
| ViewSonic VA2478-H-2 VSC8335 1920x1080 527x296mm 23.8-inch        | 2        | 0.62%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch         | 2        | 0.62%   |
| Samsung Electronics S24E360 SAM0C10 1920x1080 520x290mm 23.4-inch | 2        | 0.62%   |
| Samsung Electronics LCD Monitor S19B360                           | 2        | 0.62%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch | 2        | 0.62%   |
| Philips PHL 242M8 PHLC214 1920x1080 527x296mm 23.8-inch           | 2        | 0.62%   |
| Mi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                  | 2        | 0.62%   |
| Lenovo X24q-10 LEN61A4 2560x1440 527x296mm 23.8-inch              | 2        | 0.62%   |
| Lenovo LEN LT2252pwA LEN0A0C 1680x1050 474x296mm 22.0-inch        | 2        | 0.62%   |
| Lenovo LEN LI2364 LEN65C7 1920x1080 509x286mm 23.0-inch           | 2        | 0.62%   |
| Lenovo L197 Wide LEN1152 1440x900 410x257mm 19.1-inch             | 2        | 0.62%   |
| IPS LCD Monitor IPS2700 2560x1440 597x336mm 27.0-inch             | 2        | 0.62%   |
| HKC CH70 HKC27A9 1920x1080 597x336mm 27.0-inch                    | 2        | 0.62%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch         | 2        | 0.62%   |
| DSC Paperlike H D DSC0001 2200x1650 200x150mm 9.8-inch            | 2        | 0.62%   |
| Dell U2518D DEL413C 2560x1440 553x311mm 25.0-inch                 | 2        | 0.62%   |
| Dell U2417H DEL40E7 1920x1080 527x296mm 23.8-inch                 | 2        | 0.62%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                  | 2        | 0.62%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                 | 2        | 0.62%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                 | 2        | 0.62%   |
| Dell P2317H DEL40F3 1920x1080 509x286mm 23.0-inch                 | 2        | 0.62%   |
| Dell E2316H DELF06A 1920x1080 509x286mm 23.0-inch                 | 2        | 0.62%   |
| Dell E2216HV DELF06F 1920x1080 476x268mm 21.5-inch                | 2        | 0.62%   |
| CHD CHHWJT CHD0030 1920x1080 934x532mm 42.3-inch                  | 2        | 0.62%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                | 2        | 0.62%   |
| AOC 2490W1 AOC2490 1920x1080 530x300mm 24.0-inch                  | 2        | 0.62%   |
| AOC 2490W1 AOC2490 1920x1080 527x296mm 23.8-inch                  | 2        | 0.62%   |
| Ancor Communications LCD Monitor VG248 3360x1080                  | 2        | 0.62%   |
| Unknown                                                           | 2        | 0.62%   |
| ZTY LM1710 (VGA) ZTY1910 1280x1024 337x270mm 17.0-inch            | 1        | 0.31%   |
| ZLS E2819TVM ZLS08F2 1920x1080 410x230mm 18.5-inch                | 1        | 0.31%   |
| Xiaomi Mi TV XMD0076 3840x2160 1210x680mm 54.6-inch               | 1        | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 151      | 49.35%  |
| 3840x2160 (4K)     | 39       | 12.75%  |
| 2560x1440 (QHD)    | 32       | 10.46%  |
| 1440x900 (WXGA+)   | 15       | 4.9%    |
| 1280x1024 (SXGA)   | 11       | 3.59%   |
| 1680x1050 (WSXGA+) | 9        | 2.94%   |
| 1600x900 (HD+)     | 9        | 2.94%   |
| Unknown            | 8        | 2.61%   |
| 1920x1200 (WUXGA)  | 7        | 2.29%   |
| 3440x1440          | 5        | 1.63%   |
| 1366x768 (WXGA)    | 5        | 1.63%   |
| 3360x1080          | 2        | 0.65%   |
| 3286x1080          | 2        | 0.65%   |
| 2288x1287          | 2        | 0.65%   |
| 2200x1650          | 2        | 0.65%   |
| 5206x1080          | 1        | 0.33%   |
| 3600x1080          | 1        | 0.33%   |
| 3520x1080          | 1        | 0.33%   |
| 2560x1600          | 1        | 0.33%   |
| 2560x1080          | 1        | 0.33%   |
| 1400x1050          | 1        | 0.33%   |
| 1360x768           | 1        | 0.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 61       | 19.93%  |
| 27      | 40       | 13.07%  |
| 24      | 39       | 12.75%  |
| 21      | 39       | 12.75%  |
| Unknown | 27       | 8.82%   |
| 19      | 13       | 4.25%   |
| 31      | 12       | 3.92%   |
| 18      | 10       | 3.27%   |
| 22      | 9        | 2.94%   |
| 20      | 8        | 2.61%   |
| 17      | 8        | 2.61%   |
| 25      | 7        | 2.29%   |
| 34      | 4        | 1.31%   |
| 40      | 3        | 0.98%   |
| 12      | 3        | 0.98%   |
| 142     | 2        | 0.65%   |
| 65      | 2        | 0.65%   |
| 63      | 2        | 0.65%   |
| 15      | 2        | 0.65%   |
| 11      | 2        | 0.65%   |
| 72      | 1        | 0.33%   |
| 54      | 1        | 0.33%   |
| 46      | 1        | 0.33%   |
| 43      | 1        | 0.33%   |
| 42      | 1        | 0.33%   |
| 37      | 1        | 0.33%   |
| 36      | 1        | 0.33%   |
| 32      | 1        | 0.33%   |
| 29      | 1        | 0.33%   |
| 28      | 1        | 0.33%   |
| 26      | 1        | 0.33%   |
| 14      | 1        | 0.33%   |
| 13      | 1        | 0.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 136      | 45.79%  |
| 401-500        | 74       | 24.92%  |
| Unknown        | 27       | 9.09%   |
| 601-700        | 19       | 6.4%    |
| 301-350        | 11       | 3.7%    |
| 201-300        | 6        | 2.02%   |
| 1001-1500      | 6        | 2.02%   |
| 801-900        | 5        | 1.68%   |
| 701-800        | 5        | 1.68%   |
| 351-400        | 3        | 1.01%   |
| More than 2000 | 2        | 0.67%   |
| 901-1000       | 2        | 0.67%   |
| 1501-2000      | 1        | 0.34%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 204      | 71.08%  |
| 16/10   | 37       | 12.89%  |
| Unknown | 26       | 9.06%   |
| 5/4     | 11       | 3.83%   |
| 21/9    | 5        | 1.74%   |
| 4/3     | 2        | 0.7%    |
| 1.00    | 2        | 0.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 110      | 36.3%   |
| 151-200        | 51       | 16.83%  |
| 301-350        | 43       | 14.19%  |
| Unknown        | 27       | 8.91%   |
| 251-300        | 18       | 5.94%   |
| 351-500        | 17       | 5.61%   |
| 141-150        | 12       | 3.96%   |
| More than 1000 | 8        | 2.64%   |
| 501-1000       | 8        | 2.64%   |
| 71-80          | 3        | 0.99%   |
| 51-60          | 2        | 0.66%   |
| 101-110        | 2        | 0.66%   |
| 81-90          | 1        | 0.33%   |
| 61-70          | 1        | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 175      | 57.95%  |
| 101-120 | 60       | 19.87%  |
| Unknown | 27       | 8.94%   |
| 121-160 | 17       | 5.63%   |
| 161-240 | 15       | 4.97%   |
| 1-50    | 8        | 2.65%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 251      | 73.61%  |
| 0     | 51       | 14.96%  |
| 2     | 36       | 10.56%  |
| 3     | 3        | 0.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 221      | 47.53%  |
| Intel                      | 145      | 31.18%  |
| Qualcomm Atheros           | 20       | 4.3%    |
| Ralink Technology          | 18       | 3.87%   |
| Broadcom                   | 9        | 1.94%   |
| MediaTek                   | 6        | 1.29%   |
| Huawei Technologies        | 5        | 1.08%   |
| Microsoft                  | 4        | 0.86%   |
| IBM                        | 4        | 0.86%   |
| Tenda                      | 3        | 0.65%   |
| Marvell Technology Group   | 3        | 0.65%   |
| Xiaomi                     | 2        | 0.43%   |
| TP-Link                    | 2        | 0.43%   |
| Samsung Electronics        | 2        | 0.43%   |
| NetGear                    | 2        | 0.43%   |
| D-Link                     | 2        | 0.43%   |
| Broadcom Limited           | 2        | 0.43%   |
| ASIX Electronics           | 2        | 0.43%   |
| Aquantia                   | 2        | 0.43%   |
| ZTE WCDMA Technologies MSM | 1        | 0.22%   |
| Sagem                      | 1        | 0.22%   |
| Qualcomm                   | 1        | 0.22%   |
| Oculus VR                  | 1        | 0.22%   |
| Nvidia                     | 1        | 0.22%   |
| Mellanox Technologies      | 1        | 0.22%   |
| Loongson Technology        | 1        | 0.22%   |
| Google                     | 1        | 0.22%   |
| Exar                       | 1        | 0.22%   |
| DisplayLink                | 1        | 0.22%   |
| D-Link System              | 1        | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 166      | 30.91%  |
| Intel Wi-Fi 6 AX200                                               | 19       | 3.54%   |
| Realtek RTL8125 2.5GbE Controller                                 | 18       | 3.35%   |
| Intel Ethernet Connection (2) I219-V                              | 17       | 3.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 16       | 2.98%   |
| Intel I211 Gigabit Network Connection                             | 14       | 2.61%   |
| Realtek 802.11ac NIC                                              | 13       | 2.42%   |
| Ralink MT7601U Wireless Adapter                                   | 12       | 2.23%   |
| Intel Ethernet Connection I217-LM                                 | 9        | 1.68%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 8        | 1.49%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)         | 7        | 1.3%    |
| Intel Ethernet Connection (2) I219-LM                             | 7        | 1.3%    |
| Intel Ethernet Connection (12) I219-V                             | 7        | 1.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 1.3%    |
| Intel Ethernet Controller I225-V                                  | 6        | 1.12%   |
| Intel Ethernet Connection (7) I219-V                              | 6        | 1.12%   |
| Intel Ethernet Connection (2) I218-V                              | 6        | 1.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5        | 0.93%   |
| Intel Wireless-AC 9260                                            | 5        | 0.93%   |
| Intel Wireless 7260                                               | 5        | 0.93%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 5        | 0.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4        | 0.74%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 4        | 0.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4        | 0.74%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 4        | 0.74%   |
| Intel I210 Gigabit Network Connection                             | 4        | 0.74%   |
| Intel Ethernet Connection (7) I219-LM                             | 4        | 0.74%   |
| IBM IBM                                                           | 4        | 0.74%   |
| Tenda U12                                                         | 3        | 0.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 3        | 0.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3        | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3        | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3        | 0.56%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                | 3        | 0.56%   |
| Intel Wireless 7265                                               | 3        | 0.56%   |
| Intel I350 Gigabit Network Connection                             | 3        | 0.56%   |
| Intel Ethernet Connection (2) I218-LM                             | 3        | 0.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 0.56%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3        | 0.56%   |
| Huawei HNS GE/10GE/25GE RDMA Network Controller                   | 3        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 63       | 37.95%  |
| Realtek Semiconductor | 47       | 28.31%  |
| Ralink Technology     | 18       | 10.84%  |
| Qualcomm Atheros      | 11       | 6.63%   |
| MediaTek              | 6        | 3.61%   |
| Broadcom              | 4        | 2.41%   |
| Tenda                 | 3        | 1.81%   |
| Microsoft             | 3        | 1.81%   |
| TP-Link               | 2        | 1.2%    |
| NetGear               | 2        | 1.2%    |
| D-Link                | 2        | 1.2%    |
| Broadcom Limited      | 2        | 1.2%    |
| Xiaomi                | 1        | 0.6%    |
| Sagem                 | 1        | 0.6%    |
| D-Link System         | 1        | 0.6%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                        | 19       | 11.24%  |
| Realtek 802.11ac NIC                                       | 13       | 7.69%   |
| Ralink MT7601U Wireless Adapter                            | 12       | 7.1%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth            | 8        | 4.73%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)  | 7        | 4.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 5        | 2.96%   |
| Intel Wireless-AC 9260                                     | 5        | 2.96%   |
| Intel Wireless 7260                                        | 5        | 2.96%   |
| Intel Alder Lake-S PCH CNVi WiFi                           | 5        | 2.96%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 4        | 2.37%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                    | 4        | 2.37%   |
| Ralink RT2870/RT3070 Wireless Adapter                      | 4        | 2.37%   |
| Tenda U12                                                  | 3        | 1.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 3        | 1.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 3        | 1.78%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter         | 3        | 1.78%   |
| Intel Wireless 7265                                        | 3        | 1.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 3        | 1.78%   |
| Intel Comet Lake PCH CNVi WiFi                             | 3        | 1.78%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                      | 2        | 1.18%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 2        | 1.18%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 2        | 1.18%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                     | 2        | 1.18%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 2        | 1.18%   |
| Realtek 802.11n WLAN Adapter                               | 2        | 1.18%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 2        | 1.18%   |
| Microsoft XBOX ACC                                         | 2        | 1.18%   |
| MediaTek 802.11 n WLAN                                     | 2        | 1.18%   |
| Intel Wireless 8260                                        | 2        | 1.18%   |
| Intel Wireless 3165                                        | 2        | 1.18%   |
| Intel Tiger Lake PCH CNVi WiFi                             | 2        | 1.18%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 2        | 1.18%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter | 2        | 1.18%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter         | 2        | 1.18%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                          | 1        | 0.59%   |
| Sagem XG-760A 802.11bg                                     | 1        | 0.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1        | 0.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 1        | 0.59%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                 | 1        | 0.59%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 1        | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 202      | 57.88%  |
| Intel                    | 107      | 30.66%  |
| Qualcomm Atheros         | 9        | 2.58%   |
| Huawei Technologies      | 5        | 1.43%   |
| Broadcom                 | 5        | 1.43%   |
| IBM                      | 4        | 1.15%   |
| Marvell Technology Group | 3        | 0.86%   |
| Samsung Electronics      | 2        | 0.57%   |
| ASIX Electronics         | 2        | 0.57%   |
| Aquantia                 | 2        | 0.57%   |
| Xiaomi                   | 1        | 0.29%   |
| Qualcomm                 | 1        | 0.29%   |
| Nvidia                   | 1        | 0.29%   |
| Microsoft                | 1        | 0.29%   |
| Mellanox Technologies    | 1        | 0.29%   |
| Loongson Technology      | 1        | 0.29%   |
| Google                   | 1        | 0.29%   |
| DisplayLink              | 1        | 0.29%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 166      | 45.48%  |
| Realtek RTL8125 2.5GbE Controller                                 | 18       | 4.93%   |
| Intel Ethernet Connection (2) I219-V                              | 17       | 4.66%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 16       | 4.38%   |
| Intel I211 Gigabit Network Connection                             | 14       | 3.84%   |
| Intel Ethernet Connection I217-LM                                 | 9        | 2.47%   |
| Intel Ethernet Connection (2) I219-LM                             | 7        | 1.92%   |
| Intel Ethernet Connection (12) I219-V                             | 7        | 1.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 1.92%   |
| Intel Ethernet Controller I225-V                                  | 6        | 1.64%   |
| Intel Ethernet Connection (7) I219-V                              | 6        | 1.64%   |
| Intel Ethernet Connection (2) I218-V                              | 6        | 1.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4        | 1.1%    |
| Intel I210 Gigabit Network Connection                             | 4        | 1.1%    |
| Intel Ethernet Connection (7) I219-LM                             | 4        | 1.1%    |
| IBM IBM                                                           | 4        | 1.1%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3        | 0.82%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3        | 0.82%   |
| Intel I350 Gigabit Network Connection                             | 3        | 0.82%   |
| Intel Ethernet Connection (2) I218-LM                             | 3        | 0.82%   |
| Huawei HNS GE/10GE/25GE RDMA Network Controller                   | 3        | 0.82%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 0.55%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.55%   |
| Intel Ethernet Connection (17) I219-LM                            | 2        | 0.55%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.55%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 0.55%   |
| Intel 82546GB Gigabit Ethernet Controller                         | 2        | 0.55%   |
| Broadcom NetXtreme BCM5721 Gigabit Ethernet PCI Express           | 2        | 0.55%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2        | 0.55%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1        | 0.27%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.27%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.27%   |
| Samsung Android USB Device                                        | 1        | 0.27%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1        | 0.27%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 0.27%   |
| Qualcomm FP3                                                      | 1        | 0.27%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.27%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.27%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 327      | 67.42%  |
| WiFi     | 155      | 31.96%  |
| Modem    | 2        | 0.41%   |
| Unknown  | 1        | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 249      | 74.55%  |
| WiFi     | 85       | 25.45%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 201      | 59.47%  |
| 2     | 102      | 30.18%  |
| 3     | 15       | 4.44%   |
| 0     | 10       | 2.96%   |
| 4     | 4        | 1.18%   |
| 6     | 3        | 0.89%   |
| 8     | 1        | 0.3%    |
| 7     | 1        | 0.3%    |
| 5     | 1        | 0.3%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 304      | 89.68%  |
| Yes  | 35       | 10.32%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 60       | 50.42%  |
| Cambridge Silicon Radio         | 36       | 30.25%  |
| Realtek Semiconductor           | 9        | 7.56%   |
| ASUSTek Computer                | 4        | 3.36%   |
| Qualcomm Atheros Communications | 3        | 2.52%   |
| Broadcom                        | 3        | 2.52%   |
| Realtek                         | 1        | 0.84%   |
| MediaTek                        | 1        | 0.84%   |
| Foxconn / Hon Hai               | 1        | 0.84%   |
| Apple                           | 1        | 0.84%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 36       | 30.25%  |
| Intel Bluetooth wireless interface                    | 22       | 18.49%  |
| Intel AX200 Bluetooth                                 | 19       | 15.97%  |
| Intel Bluetooth Device                                | 9        | 7.56%   |
| Realtek Bluetooth Radio                               | 8        | 6.72%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 4        | 3.36%   |
| Intel Wireless-AC 3168 Bluetooth                      | 3        | 2.52%   |
| Qualcomm Atheros  Bluetooth Device                    | 2        | 1.68%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2        | 1.68%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2        | 1.68%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 2        | 1.68%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1        | 0.84%   |
| Realtek Bluetooth Radio                               | 1        | 0.84%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 1        | 0.84%   |
| MediaTek Wireless_Device                              | 1        | 0.84%   |
| Intel AX210 Bluetooth                                 | 1        | 0.84%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller       | 1        | 0.84%   |
| Broadcom Bluetooth 3.0 USB Dongle                     | 1        | 0.84%   |
| ASUS Qualcomm Bluetooth 4.1                           | 1        | 0.84%   |
| ASUS Bluetooth Radio                                  | 1        | 0.84%   |
| Apple Bluetooth Host Controller                       | 1        | 0.84%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 221      | 46.82%  |
| AMD                              | 121      | 25.64%  |
| Nvidia                           | 95       | 20.13%  |
| Realtek Semiconductor            | 4        | 0.85%   |
| Creative Labs                    | 4        | 0.85%   |
| XMOS                             | 3        | 0.64%   |
| C-Media Electronics              | 3        | 0.64%   |
| Zhaoxin                          | 2        | 0.42%   |
| Texas Instruments                | 2        | 0.42%   |
| Dell                             | 2        | 0.42%   |
| Unknown                          | 1        | 0.21%   |
| TerraTec Electronic              | 1        | 0.21%   |
| Sony                             | 1        | 0.21%   |
| Silicon Integrated Systems [SiS] | 1        | 0.21%   |
| Sennheiser Communications        | 1        | 0.21%   |
| Polycom                          | 1        | 0.21%   |
| NXP Semiconductors               | 1        | 0.21%   |
| Moore Threads Technology         | 1        | 0.21%   |
| Loongson Technology              | 1        | 0.21%   |
| KTMicro                          | 1        | 0.21%   |
| Kingston Technology              | 1        | 0.21%   |
| Giga-Byte Technology             | 1        | 0.21%   |
| Generalplus Technology           | 1        | 0.21%   |
| Atmel                            | 1        | 0.21%   |
| Actions Semiconductor            | 1        | 0.21%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 37       | 6.69%   |
| Intel 200 Series PCH HD Audio                                                     | 33       | 5.97%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 22       | 3.98%   |
| AMD Starship/Matisse HD Audio Controller                                          | 22       | 3.98%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 20       | 3.62%   |
| AMD Family 17h/19h HD Audio Controller                                            | 20       | 3.62%   |
| Intel Cannon Lake PCH cAVS                                                        | 19       | 3.44%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 17       | 3.07%   |
| Intel Comet Lake PCH-V cAVS                                                       | 15       | 2.71%   |
| Nvidia GP106 High Definition Audio Controller                                     | 14       | 2.53%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 14       | 2.53%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 14       | 2.53%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 12       | 2.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 11       | 1.99%   |
| AMD FCH Azalia Controller                                                         | 11       | 1.99%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 11       | 1.99%   |
| Nvidia GP104 High Definition Audio Controller                                     | 10       | 1.81%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 10       | 1.81%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 10       | 1.81%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 10       | 1.81%   |
| Nvidia TU116 High Definition Audio Controller                                     | 9        | 1.63%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 8        | 1.45%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 8        | 1.45%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 8        | 1.45%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 8        | 1.45%   |
| Nvidia GF119 HDMI Audio Controller                                                | 7        | 1.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 6        | 1.08%   |
| Intel Alder Lake-S HD Audio Controller                                            | 6        | 1.08%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 6        | 1.08%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 6        | 1.08%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 5        | 0.9%    |
| Nvidia GM206 High Definition Audio Controller                                     | 5        | 0.9%    |
| Nvidia GA102 High Definition Audio Controller                                     | 5        | 0.9%    |
| Intel Audio device                                                                | 5        | 0.9%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 5        | 0.9%    |
| Realtek Semiconductor USB Audio                                                   | 4        | 0.72%   |
| Nvidia TU102 High Definition Audio Controller                                     | 4        | 0.72%   |
| Nvidia GP102 HDMI Audio Controller                                                | 4        | 0.72%   |
| Nvidia GK106 HDMI Audio Controller                                                | 4        | 0.72%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 4        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                             | Desktops | Percent |
|------------------------------------|----------|---------|
| Kingston                           | 60       | 32.61%  |
| Samsung Electronics                | 25       | 13.59%  |
| Unknown                            | 19       | 10.33%  |
| A-DATA Technology                  | 18       | 9.78%   |
| SK hynix                           | 12       | 6.52%   |
| Micron Technology                  | 6        | 3.26%   |
| Corsair                            | 6        | 3.26%   |
| Unknown                            | 5        | 2.72%   |
| Team                               | 3        | 1.63%   |
| Kingmax                            | 3        | 1.63%   |
| G.Skill                            | 3        | 1.63%   |
| Crucial                            | 3        | 1.63%   |
| Ramsta                             | 2        | 1.09%   |
| Ramaxel Technology                 | 2        | 1.09%   |
| KINGBANK                           | 2        | 1.09%   |
| GLOWAY                             | 2        | 1.09%   |
| Unknown (ABCD)                     | 1        | 0.54%   |
| Transcend                          | 1        | 0.54%   |
| tigo                               | 1        | 0.54%   |
| Thermaltake                        | 1        | 0.54%   |
| Shenzhen Longsys                   | 1        | 0.54%   |
| Sesame                             | 1        | 0.54%   |
| MAXSUN                             | 1        | 0.54%   |
| KLEVV                              | 1        | 0.54%   |
| Kimtigo Semiconductor (HK) Limited | 1        | 0.54%   |
| Juhor                              | 1        | 0.54%   |
| GeIL                               | 1        | 0.54%   |
| Colorful                           | 1        | 0.54%   |
| Apacer                             | 1        | 0.54%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s       | 6        | 2.93%   |
| Unknown                                                      | 5        | 2.44%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s            | 4        | 1.95%   |
| Kingston RAM TF32D4U2S1MEH-8 8GB DIMM DDR4 3200MT/s          | 3        | 1.46%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s         | 3        | 1.46%   |
| Kingston RAM 99P5471-033.A00LF 8192MB DIMM DDR3 1600MT/s     | 3        | 1.46%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                      | 2        | 0.98%   |
| Unknown RAM Module 16GB DIMM DDR4 2133MT/s                   | 2        | 0.98%   |
| SK hynix RAM HMA42GR7MFR4N-TF 16GB DIMM DDR4 2133MT/s        | 2        | 0.98%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s          | 2        | 0.98%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s          | 2        | 0.98%   |
| Samsung RAM M378B1G73EB0-CK0 8GB DIMM DDR3 1600MT/s          | 2        | 0.98%   |
| Kingston RAM KHX1866C10D3/8G 8192MB DIMM DDR3 2133MT/s       | 2        | 0.98%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3                   | 2        | 0.98%   |
| Kingston RAM 99P5474-014.A00LF 4GB DIMM DDR3 1333MT/s        | 2        | 0.98%   |
| Kingston RAM 99P5474-013.A00LF 4GB DIMM DDR3 1600MT/s        | 2        | 0.98%   |
| Kingston RAM 99P5471-016.A00LF 8192MB DIMM DDR3 1600MT/s     | 2        | 0.98%   |
| Kingston RAM 9905701-011.A00G 16GB DIMM DDR4 2400MT/s        | 2        | 0.98%   |
| GLOWAY RAM TYA4U2666D19161C 16384MB DIMM DDR4 2667MT/s       | 2        | 0.98%   |
| Crucial RAM BL16G32C16U4W.16FE 16GB DIMM DDR4 3200MT/s       | 2        | 0.98%   |
| A-DATA RAM Module 8GB DIMM DDR4 2666MT/s                     | 2        | 0.98%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3400MT/s                  | 2        | 0.98%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1        | 0.49%   |
| Unknown RAM Module 8GB DIMM DDR3 1066MT/s                    | 1        | 0.49%   |
| Unknown RAM Module 8192MB DIMM 400MT/s                       | 1        | 0.49%   |
| Unknown RAM Module 8192MB                                    | 1        | 0.49%   |
| Unknown RAM Module 512MB DIMM DDR2 333MT/s                   | 1        | 0.49%   |
| Unknown RAM Module 4GB DIMM SDRAM                            | 1        | 0.49%   |
| Unknown RAM Module 4GB DIMM DDR3 800MT/s                     | 1        | 0.49%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 1        | 0.49%   |
| Unknown RAM Module 4096MB DIMM SDRAM                         | 1        | 0.49%   |
| Unknown RAM Module 2GB DIMM DDR3 667MT/s                     | 1        | 0.49%   |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 1        | 0.49%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s               | 1        | 0.49%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s                 | 1        | 0.49%   |
| Unknown RAM Module 2048MB DIMM DDR2                          | 1        | 0.49%   |
| Unknown RAM Module 16384MB DIMM DDR3 1600MT/s                | 1        | 0.49%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                  | 1        | 0.49%   |
| Unknown RAM CL17-17-17 D4-2400 16384MB DIMM DDR4 2400MT/s    | 1        | 0.49%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 1        | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 79       | 47.02%  |
| DDR3    | 65       | 38.69%  |
| Unknown | 10       | 5.95%   |
| SDRAM   | 7        | 4.17%   |
| DDR2    | 4        | 2.38%   |
| LPDDR4  | 2        | 1.19%   |
| DDR5    | 1        | 0.6%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 155      | 91.72%  |
| SODIMM       | 12       | 7.1%    |
| Row Of Chips | 1        | 0.59%   |
| Unknown      | 1        | 0.59%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 68       | 37.99%  |
| 16384 | 43       | 24.02%  |
| 4096  | 42       | 23.46%  |
| 2048  | 13       | 7.26%   |
| 32768 | 11       | 6.15%   |
| 1024  | 1        | 0.56%   |
| 512   | 1        | 0.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 43       | 22.75%  |
| 1333    | 17       | 8.99%   |
| 3200    | 15       | 7.94%   |
| 2400    | 14       | 7.41%   |
| 3600    | 13       | 6.88%   |
| 2666    | 11       | 5.82%   |
| 2667    | 10       | 5.29%   |
| 2133    | 9        | 4.76%   |
| 800     | 8        | 4.23%   |
| 1866    | 5        | 2.65%   |
| 3466    | 4        | 2.12%   |
| 3400    | 4        | 2.12%   |
| 3000    | 4        | 2.12%   |
| Unknown | 4        | 2.12%   |
| 4800    | 2        | 1.06%   |
| 3733    | 2        | 1.06%   |
| 2933    | 2        | 1.06%   |
| 2800    | 2        | 1.06%   |
| 1867    | 2        | 1.06%   |
| 1800    | 2        | 1.06%   |
| 1066    | 2        | 1.06%   |
| 65535   | 1        | 0.53%   |
| 6400    | 1        | 0.53%   |
| 4199    | 1        | 0.53%   |
| 4133    | 1        | 0.53%   |
| 3800    | 1        | 0.53%   |
| 3500    | 1        | 0.53%   |
| 3266    | 1        | 0.53%   |
| 2200    | 1        | 0.53%   |
| 2187    | 1        | 0.53%   |
| 1067    | 1        | 0.53%   |
| 667     | 1        | 0.53%   |
| 533     | 1        | 0.53%   |
| 400     | 1        | 0.53%   |
| 333     | 1        | 0.53%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                             | Desktops | Percent |
|------------------------------------|----------|---------|
| Hewlett-Packard                    | 1        | 25%     |
| Canon                              | 1        | 25%     |
| Brother Industries                 | 1        | 25%     |
| BeiJing LanXum Computer Technology | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| HP LaserJet 1020                                        | 1        | 25%     |
| Canon PIXMA MP280                                       | 1        | 25%     |
| Brother HL-5440D series                                 | 1        | 25%     |
| BeiJing LanXum Technology Black and White Laser Printer | 1        | 25%     |

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
| Logitech                      | 6        | 25%     |
| Microdia                      | 3        | 12.5%   |
| Z-Star Microelectronics       | 2        | 8.33%   |
| Sunplus Innovation Technology | 2        | 8.33%   |
| Realtek Semiconductor         | 2        | 8.33%   |
| Apple                         | 2        | 8.33%   |
| Alcor Micro                   | 2        | 8.33%   |
| SN0002                        | 1        | 4.17%   |
| Silicon Motion                | 1        | 4.17%   |
| MacroSilicon                  | 1        | 4.17%   |
| IMC Networks                  | 1        | 4.17%   |
| Google                        | 1        | 4.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Realtek USB Camera                      | 2        | 8%      |
| Microdia Camera                         | 2        | 8%      |
| Logitech Webcam C310                    | 2        | 8%      |
| Logitech HD Pro Webcam C920             | 2        | 8%      |
| Apple iPhone 5/5C/5S/6/SE               | 2        | 8%      |
| Z-Star Venus USB2.0 Camera              | 1        | 4%      |
| Z-Star Traveler TV 6500 SF Dia-scanner  | 1        | 4%      |
| Sunplus Full HD webcam                  | 1        | 4%      |
| Sunplus aoni webcam A30                 | 1        | 4%      |
| SN0002 HIK 2K USB CAMERA                | 1        | 4%      |
| Silicon Motion 300k Pixel Camera        | 1        | 4%      |
| Microdia Document Scanner               | 1        | 4%      |
| MacroSilicon USB Video                  | 1        | 4%      |
| Logitech Webcam C270                    | 1        | 4%      |
| Logitech Logitech Webcam C100           | 1        | 4%      |
| Logitech C930c                          | 1        | 4%      |
| IMC Networks XHC Camera                 | 1        | 4%      |
| Google Nexus/Pixel Device (MTP + debug) | 1        | 4%      |
| Alcor Micro USB Video Device            | 1        | 4%      |
| Alcor Micro USB Camera                  | 1        | 4%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Shenzhen Goodix Technology | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Shenzhen Goodix Fingerprint Reader | 1        | 100%    |

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


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 262      | 75.94%  |
| 1     | 66       | 19.13%  |
| 2     | 8        | 2.32%   |
| 3     | 4        | 1.16%   |
| 4     | 2        | 0.58%   |
| 8     | 1        | 0.29%   |
| 7     | 1        | 0.29%   |
| 5     | 1        | 0.29%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 38       | 33.63%  |
| Net/wireless             | 28       | 24.78%  |
| Unassigned class         | 11       | 9.73%   |
| Communication controller | 11       | 9.73%   |
| Sound                    | 7        | 6.19%   |
| Bluetooth                | 5        | 4.42%   |
| Network                  | 4        | 3.54%   |
| Storage/raid             | 3        | 2.65%   |
| Net/ethernet             | 2        | 1.77%   |
| Fingerprint reader       | 1        | 0.88%   |
| Chipcard                 | 1        | 0.88%   |
| Card reader              | 1        | 0.88%   |
| Camera                   | 1        | 0.88%   |

