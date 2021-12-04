Elementary 6 - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Elementary 6.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Elementary_6/Desktop/README.md) and [notebooks](/Dist/Elementary_6/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 2B07                        | All in one  | [b6cf0a1651](https://linux-hardware.org/?probe=b6cf0a1651) | Dec 03, 2021 |
| Lenovo        | ThinkPad T410s 292494G      | Notebook    | [f43363fde0](https://linux-hardware.org/?probe=f43363fde0) | Dec 03, 2021 |
| Pegatron      | Benicia                     | Desktop     | [51dae15bcd](https://linux-hardware.org/?probe=51dae15bcd) | Dec 03, 2021 |
| Gigabyte      | AX370-Gaming-CF se1         | Desktop     | [313d4d0bd8](https://linux-hardware.org/?probe=313d4d0bd8) | Dec 03, 2021 |
| HP            | EliteBook 820 G2            | Notebook    | [03bb5ecc6a](https://linux-hardware.org/?probe=03bb5ecc6a) | Dec 03, 2021 |
| HP            | 8653 A                      | Desktop     | [85d1730019](https://linux-hardware.org/?probe=85d1730019) | Dec 01, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [68fffd46cf](https://linux-hardware.org/?probe=68fffd46cf) | Dec 01, 2021 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [fbe4820444](https://linux-hardware.org/?probe=fbe4820444) | Dec 01, 2021 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | Desktop     | [500f9c8851](https://linux-hardware.org/?probe=500f9c8851) | Dec 01, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [0131556200](https://linux-hardware.org/?probe=0131556200) | Dec 01, 2021 |
| Samsung       | 550XDA                      | Notebook    | [30c24b17f4](https://linux-hardware.org/?probe=30c24b17f4) | Dec 01, 2021 |
| HP            | EliteBook 2760p             | Notebook    | [d13f27ae75](https://linux-hardware.org/?probe=d13f27ae75) | Nov 30, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [5052f33272](https://linux-hardware.org/?probe=5052f33272) | Nov 30, 2021 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [c7cbb50843](https://linux-hardware.org/?probe=c7cbb50843) | Nov 30, 2021 |
| Google        | Kip                         | Notebook    | [958c198a17](https://linux-hardware.org/?probe=958c198a17) | Nov 29, 2021 |
| Lenovo        | ThinkPad SL400 2743A37      | Notebook    | [26cba9b931](https://linux-hardware.org/?probe=26cba9b931) | Nov 29, 2021 |
| Chuwi         | LarkBox Pro                 | Desktop     | [4af62a6057](https://linux-hardware.org/?probe=4af62a6057) | Nov 29, 2021 |
| Biostar       | TH55XE                      | Desktop     | [9e420cc495](https://linux-hardware.org/?probe=9e420cc495) | Nov 28, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [0a4f8ff5f1](https://linux-hardware.org/?probe=0a4f8ff5f1) | Nov 28, 2021 |
| HP            | Laptop 15s-fq0xxx           | Notebook    | [8b1d090289](https://linux-hardware.org/?probe=8b1d090289) | Nov 28, 2021 |
| MSI           | H81M-P33                    | Desktop     | [8812103632](https://linux-hardware.org/?probe=8812103632) | Nov 28, 2021 |
| HP            | 1497                        | Desktop     | [6f042fb99c](https://linux-hardware.org/?probe=6f042fb99c) | Nov 28, 2021 |
| HP            | Pavilion dm4                | Notebook    | [e2c582f687](https://linux-hardware.org/?probe=e2c582f687) | Nov 28, 2021 |
| HP            | ProBook 4540s               | Notebook    | [b6762448da](https://linux-hardware.org/?probe=b6762448da) | Nov 28, 2021 |
| Acer          | Aspire X3990                | Desktop     | [5559b2d988](https://linux-hardware.org/?probe=5559b2d988) | Nov 27, 2021 |
| Notebook      | L140CU                      | Notebook    | [59021b2a31](https://linux-hardware.org/?probe=59021b2a31) | Nov 27, 2021 |
| Toshiba       | Satellite L840              | Notebook    | [6c29b0fc8d](https://linux-hardware.org/?probe=6c29b0fc8d) | Nov 27, 2021 |
| Acer          | Iconia Tab W500             | Tablet      | [5984a91751](https://linux-hardware.org/?probe=5984a91751) | Nov 27, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [c8a72fc7e2](https://linux-hardware.org/?probe=c8a72fc7e2) | Nov 26, 2021 |
| HP            | 1825                        | Desktop     | [3648c360a9](https://linux-hardware.org/?probe=3648c360a9) | Nov 26, 2021 |
| Lenovo        | ThinkPad SL400 2743A37      | Notebook    | [8c0a3a65ba](https://linux-hardware.org/?probe=8c0a3a65ba) | Nov 26, 2021 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [0004bab911](https://linux-hardware.org/?probe=0004bab911) | Nov 26, 2021 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [2ef4f4f273](https://linux-hardware.org/?probe=2ef4f4f273) | Nov 26, 2021 |
| Dell          | Inspiron 15-3573            | Notebook    | [04dc1956ff](https://linux-hardware.org/?probe=04dc1956ff) | Nov 26, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [ee1387e206](https://linux-hardware.org/?probe=ee1387e206) | Nov 26, 2021 |
| Lenovo        | ThinkPad SL400 2743A37      | Notebook    | [cd408c48d0](https://linux-hardware.org/?probe=cd408c48d0) | Nov 25, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [34e71f1e27](https://linux-hardware.org/?probe=34e71f1e27) | Nov 25, 2021 |
| Lenovo        | ThinkPad X140e 20BLS0040... | Notebook    | [94b3c73b50](https://linux-hardware.org/?probe=94b3c73b50) | Nov 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [0fccfea38c](https://linux-hardware.org/?probe=0fccfea38c) | Nov 25, 2021 |
| Apple         | MacBookPro11,2              | Notebook    | [07931c8e7b](https://linux-hardware.org/?probe=07931c8e7b) | Nov 24, 2021 |
| Dell          | System Inspiron N7110       | Notebook    | [fe6a145b19](https://linux-hardware.org/?probe=fe6a145b19) | Nov 24, 2021 |
| Medion        | E7218                       | Notebook    | [e4a790a38d](https://linux-hardware.org/?probe=e4a790a38d) | Nov 23, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [1bfd5fb612](https://linux-hardware.org/?probe=1bfd5fb612) | Nov 23, 2021 |
| HP            | Laptop 15s-du1xxx           | Notebook    | [d4cf81aaa5](https://linux-hardware.org/?probe=d4cf81aaa5) | Nov 23, 2021 |
| HP            | Laptop 15s-du1xxx           | Notebook    | [0368cfb8e2](https://linux-hardware.org/?probe=0368cfb8e2) | Nov 23, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [4f694a8ba3](https://linux-hardware.org/?probe=4f694a8ba3) | Nov 23, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [945f4c9b1d](https://linux-hardware.org/?probe=945f4c9b1d) | Nov 22, 2021 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [1e15277ce2](https://linux-hardware.org/?probe=1e15277ce2) | Nov 22, 2021 |
| Biostar       | TA790GXE 128M               | Desktop     | [93ff10a9c2](https://linux-hardware.org/?probe=93ff10a9c2) | Nov 21, 2021 |
| MSI           | GF72 7RE                    | Notebook    | [8e48a382b9](https://linux-hardware.org/?probe=8e48a382b9) | Nov 21, 2021 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [12bcc06e6e](https://linux-hardware.org/?probe=12bcc06e6e) | Nov 21, 2021 |
| Alienware     | 17                          | Notebook    | [d3460bdfd1](https://linux-hardware.org/?probe=d3460bdfd1) | Nov 20, 2021 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [e7e27b16de](https://linux-hardware.org/?probe=e7e27b16de) | Nov 20, 2021 |
| Dell          | Vostro 3300                 | Notebook    | [04fc886be3](https://linux-hardware.org/?probe=04fc886be3) | Nov 20, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [9e7d926319](https://linux-hardware.org/?probe=9e7d926319) | Nov 19, 2021 |
| HP            | ProBook 4730s               | Notebook    | [ffaa64e329](https://linux-hardware.org/?probe=ffaa64e329) | Nov 19, 2021 |
| HP            | 0AECh D                     | Desktop     | [c81bcc92ca](https://linux-hardware.org/?probe=c81bcc92ca) | Nov 19, 2021 |
| Schenker      | X170KM-G                    | Notebook    | [79bb8af2a1](https://linux-hardware.org/?probe=79bb8af2a1) | Nov 19, 2021 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [e49d63158f](https://linux-hardware.org/?probe=e49d63158f) | Nov 19, 2021 |
| HP            | ENVY x360 Convertible       | Convertible | [d998144d2e](https://linux-hardware.org/?probe=d998144d2e) | Nov 18, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [38d8d7827f](https://linux-hardware.org/?probe=38d8d7827f) | Nov 18, 2021 |
| Dell          | Inspiron 7506 2n1           | Convertible | [078e3be7c3](https://linux-hardware.org/?probe=078e3be7c3) | Nov 17, 2021 |
| HP            | Compaq 6710b (GB893EA#AB... | Notebook    | [47a6a7a44f](https://linux-hardware.org/?probe=47a6a7a44f) | Nov 17, 2021 |
| Unknown       | Unknown                     | Notebook    | [7027abd4e6](https://linux-hardware.org/?probe=7027abd4e6) | Nov 17, 2021 |
| Acer          | Aspire 5733Z                | Notebook    | [324f0d898e](https://linux-hardware.org/?probe=324f0d898e) | Nov 16, 2021 |
| Acer          | Aspire ES1-571              | Notebook    | [60fef7922d](https://linux-hardware.org/?probe=60fef7922d) | Nov 16, 2021 |
| Dell          | 0F2A20 A00                  | All in one  | [e98616633d](https://linux-hardware.org/?probe=e98616633d) | Nov 16, 2021 |
| Gigabyte      | EP43T-USB3                  | Desktop     | [a24bb09910](https://linux-hardware.org/?probe=a24bb09910) | Nov 15, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [74e99a032e](https://linux-hardware.org/?probe=74e99a032e) | Nov 15, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [58edd5c8e6](https://linux-hardware.org/?probe=58edd5c8e6) | Nov 14, 2021 |
| Gigabyte      | H81M-H                      | Desktop     | [a895ed29e0](https://linux-hardware.org/?probe=a895ed29e0) | Nov 14, 2021 |
| ASRock        | X570 Extreme4               | Desktop     | [e49fdf2db4](https://linux-hardware.org/?probe=e49fdf2db4) | Nov 13, 2021 |
| Lenovo        | ThinkPad T460s 20F90042M... | Notebook    | [76ba8c7144](https://linux-hardware.org/?probe=76ba8c7144) | Nov 13, 2021 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [197f5e1565](https://linux-hardware.org/?probe=197f5e1565) | Nov 12, 2021 |
| Sony          | SVE15115EN                  | Notebook    | [03cbf5ac5a](https://linux-hardware.org/?probe=03cbf5ac5a) | Nov 11, 2021 |
| MSI           | 970A-G43                    | Desktop     | [19714dd1a0](https://linux-hardware.org/?probe=19714dd1a0) | Nov 08, 2021 |
| Gigabyte      | Z270X-Gaming 5              | Desktop     | [5244244701](https://linux-hardware.org/?probe=5244244701) | Nov 08, 2021 |
| Dell          | 05R2TK A01                  | All in one  | [0b728f2263](https://linux-hardware.org/?probe=0b728f2263) | Nov 07, 2021 |
| ASUSTek       | ROG Strix G512LI_G512LI     | Notebook    | [e43a236a2c](https://linux-hardware.org/?probe=e43a236a2c) | Nov 06, 2021 |
| Quanta        | TW9/SW9                     | Notebook    | [86643edf2a](https://linux-hardware.org/?probe=86643edf2a) | Nov 06, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [66109af766](https://linux-hardware.org/?probe=66109af766) | Nov 05, 2021 |
| ASUSTek       | E502SA                      | Notebook    | [28d4f5e427](https://linux-hardware.org/?probe=28d4f5e427) | Nov 04, 2021 |
| HCL Infosy... | HCL ME LAPTOP               | Notebook    | [0db069b4f1](https://linux-hardware.org/?probe=0db069b4f1) | Nov 01, 2021 |
| Fujitsu       | LIFEBOOK U747               | Notebook    | [2b68c16c68](https://linux-hardware.org/?probe=2b68c16c68) | Nov 01, 2021 |
| Dell          | Latitude E6410              | Notebook    | [ba51fc9216](https://linux-hardware.org/?probe=ba51fc9216) | Oct 30, 2021 |
| ASRock        | P67 Extreme4                | Desktop     | [a70eb2d3f8](https://linux-hardware.org/?probe=a70eb2d3f8) | Oct 29, 2021 |
| ASRock        | P67 Extreme4                | Desktop     | [0a07f4c735](https://linux-hardware.org/?probe=0a07f4c735) | Oct 29, 2021 |
| MSI           | 2A9Ch                       | Desktop     | [2f752a1a3e](https://linux-hardware.org/?probe=2f752a1a3e) | Oct 28, 2021 |
| Lenovo        | ThinkPad X230 23259L3       | Notebook    | [801c1d8af3](https://linux-hardware.org/?probe=801c1d8af3) | Oct 27, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [6461bfc243](https://linux-hardware.org/?probe=6461bfc243) | Oct 26, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [a904daf48d](https://linux-hardware.org/?probe=a904daf48d) | Oct 26, 2021 |
| HP            | 84EE 1100                   | All in one  | [225f3ee57b](https://linux-hardware.org/?probe=225f3ee57b) | Oct 26, 2021 |
| HP            | ProBook 6460b               | Notebook    | [18f27d1f5c](https://linux-hardware.org/?probe=18f27d1f5c) | Oct 25, 2021 |
| Lenovo        | ThinkPad T470 20HD004AUS    | Notebook    | [80fb4514c5](https://linux-hardware.org/?probe=80fb4514c5) | Oct 23, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [5c95c74b6c](https://linux-hardware.org/?probe=5c95c74b6c) | Oct 21, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f48a449c7a](https://linux-hardware.org/?probe=f48a449c7a) | Oct 21, 2021 |
| HP            | 158B                        | Desktop     | [24399f4e69](https://linux-hardware.org/?probe=24399f4e69) | Oct 20, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [4ce4f8ba78](https://linux-hardware.org/?probe=4ce4f8ba78) | Oct 20, 2021 |
| Google        | Setzer                      | Notebook    | [e9536ccbfb](https://linux-hardware.org/?probe=e9536ccbfb) | Oct 19, 2021 |
| Google        | Setzer                      | Notebook    | [3ba49636ef](https://linux-hardware.org/?probe=3ba49636ef) | Oct 19, 2021 |
| HP            | 339A                        | Desktop     | [d9c6208191](https://linux-hardware.org/?probe=d9c6208191) | Oct 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [370b129f3f](https://linux-hardware.org/?probe=370b129f3f) | Oct 16, 2021 |
| Lenovo        | ThinkPad E470 20H10052IG    | Notebook    | [1342d4ce00](https://linux-hardware.org/?probe=1342d4ce00) | Oct 15, 2021 |
| HP            | Pavilion dv6500             | Notebook    | [dd3c7ef3e7](https://linux-hardware.org/?probe=dd3c7ef3e7) | Oct 14, 2021 |
| HP            | Pavilion dv6500             | Notebook    | [c1c77cf91a](https://linux-hardware.org/?probe=c1c77cf91a) | Oct 14, 2021 |
| HP            | 2B42                        | All in one  | [42d66aed80](https://linux-hardware.org/?probe=42d66aed80) | Oct 14, 2021 |
| Dell          | 0M9KCM A02                  | Desktop     | [a925b0f3d1](https://linux-hardware.org/?probe=a925b0f3d1) | Oct 12, 2021 |
| Acer          | Aspire ES1-311              | Notebook    | [8f1dd3ce3a](https://linux-hardware.org/?probe=8f1dd3ce3a) | Oct 12, 2021 |
| Acer          | Aspire ES1-311              | Notebook    | [df266accf1](https://linux-hardware.org/?probe=df266accf1) | Oct 12, 2021 |
| Apple         | MacBookAir6,1               | Notebook    | [66f91918dc](https://linux-hardware.org/?probe=66f91918dc) | Oct 12, 2021 |
| Apple         | MacBookAir6,1               | Notebook    | [87403edfc9](https://linux-hardware.org/?probe=87403edfc9) | Oct 11, 2021 |
| HP            | 2B42                        | All in one  | [794d39b312](https://linux-hardware.org/?probe=794d39b312) | Oct 11, 2021 |
| HP            | 2B42                        | All in one  | [936b3a489d](https://linux-hardware.org/?probe=936b3a489d) | Oct 11, 2021 |
| HP            | 2B42                        | All in one  | [c1224ad1ab](https://linux-hardware.org/?probe=c1224ad1ab) | Oct 11, 2021 |
| ASUSTek       | 1215B                       | Notebook    | [7b3bf2ca14](https://linux-hardware.org/?probe=7b3bf2ca14) | Oct 11, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [e5071e6c43](https://linux-hardware.org/?probe=e5071e6c43) | Oct 10, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [f6e75d0258](https://linux-hardware.org/?probe=f6e75d0258) | Oct 09, 2021 |
| HP            | ProBook 4530s               | Notebook    | [0a725a0b81](https://linux-hardware.org/?probe=0a725a0b81) | Oct 07, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [644b3b5b60](https://linux-hardware.org/?probe=644b3b5b60) | Oct 04, 2021 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [05711b548f](https://linux-hardware.org/?probe=05711b548f) | Oct 03, 2021 |
| ASUSTek       | TUF GAMING B560M-PLUS       | Desktop     | [de0f051658](https://linux-hardware.org/?probe=de0f051658) | Oct 02, 2021 |
| Shuttle       | FS61                        | Desktop     | [b25047a516](https://linux-hardware.org/?probe=b25047a516) | Oct 01, 2021 |
| Panasonic     | FZ-G1ASH39E3                | Tablet      | [06f11c0449](https://linux-hardware.org/?probe=06f11c0449) | Sep 30, 2021 |
| Panasonic     | FZ-G1ASH39E3                | Tablet      | [961d53afb6](https://linux-hardware.org/?probe=961d53afb6) | Sep 30, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [32c58fa2f6](https://linux-hardware.org/?probe=32c58fa2f6) | Sep 30, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [c1dc59d33f](https://linux-hardware.org/?probe=c1dc59d33f) | Sep 29, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [1754c64091](https://linux-hardware.org/?probe=1754c64091) | Sep 27, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [c28700cfda](https://linux-hardware.org/?probe=c28700cfda) | Sep 26, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [fbcf277174](https://linux-hardware.org/?probe=fbcf277174) | Sep 26, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [59224ec754](https://linux-hardware.org/?probe=59224ec754) | Sep 26, 2021 |
| ASUSTek       | P7H55-M                     | Desktop     | [3367bc011a](https://linux-hardware.org/?probe=3367bc011a) | Sep 25, 2021 |
| Dell          | 0Y5DDC A00                  | Desktop     | [df95ea94b8](https://linux-hardware.org/?probe=df95ea94b8) | Sep 25, 2021 |
| Dell          | 0Y5DDC A00                  | Desktop     | [10ee1abc07](https://linux-hardware.org/?probe=10ee1abc07) | Sep 25, 2021 |
| Apple         | MacBookPro10,2              | Notebook    | [25c8a26c00](https://linux-hardware.org/?probe=25c8a26c00) | Sep 24, 2021 |
| ASRock        | M3A790GXH/128M              | Desktop     | [818ec10ec8](https://linux-hardware.org/?probe=818ec10ec8) | Sep 24, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [c1b8f22fa6](https://linux-hardware.org/?probe=c1b8f22fa6) | Sep 22, 2021 |
| Intel         | X79 V1.x                    | Desktop     | [19223e911c](https://linux-hardware.org/?probe=19223e911c) | Sep 22, 2021 |
| Dell          | Precision M4800             | Notebook    | [736b482dc3](https://linux-hardware.org/?probe=736b482dc3) | Sep 22, 2021 |
| eMachines     | G525                        | Notebook    | [8e8d037369](https://linux-hardware.org/?probe=8e8d037369) | Sep 21, 2021 |
| ASUSTek       | M4N78-AM                    | Desktop     | [3d8e0efc00](https://linux-hardware.org/?probe=3d8e0efc00) | Sep 21, 2021 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [9d25d0c5c7](https://linux-hardware.org/?probe=9d25d0c5c7) | Sep 21, 2021 |
| Lenovo        | ThinkPad W700 2758MVG       | Notebook    | [66c8ecbaa1](https://linux-hardware.org/?probe=66c8ecbaa1) | Sep 20, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [b01438543e](https://linux-hardware.org/?probe=b01438543e) | Sep 20, 2021 |
| Apple         | MacBookPro10,2              | Notebook    | [0e44f5011a](https://linux-hardware.org/?probe=0e44f5011a) | Sep 20, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3448B... | Notebook    | [2bec640695](https://linux-hardware.org/?probe=2bec640695) | Sep 20, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [d2511347b4](https://linux-hardware.org/?probe=d2511347b4) | Sep 19, 2021 |
| HP            | ENVY 15                     | Notebook    | [ba9a8e1d7a](https://linux-hardware.org/?probe=ba9a8e1d7a) | Sep 19, 2021 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [9d10bffde2](https://linux-hardware.org/?probe=9d10bffde2) | Sep 18, 2021 |
| Lenovo        | ThinkPad X250 20CLS32H00    | Notebook    | [15981e12f3](https://linux-hardware.org/?probe=15981e12f3) | Sep 18, 2021 |
| Lenovo        | ThinkPad X250 20CLS32H00    | Notebook    | [bcdb4d552d](https://linux-hardware.org/?probe=bcdb4d552d) | Sep 18, 2021 |
| HP            | ENVY 15                     | Notebook    | [d2d607895f](https://linux-hardware.org/?probe=d2d607895f) | Sep 18, 2021 |
| ASRock        | A320M-HDV                   | Desktop     | [24bb7c7d18](https://linux-hardware.org/?probe=24bb7c7d18) | Sep 17, 2021 |
| Alienware     | 17                          | Notebook    | [c97b201719](https://linux-hardware.org/?probe=c97b201719) | Sep 17, 2021 |
| Acer          | Aspire V3-572G              | Notebook    | [addf12cb05](https://linux-hardware.org/?probe=addf12cb05) | Sep 16, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [0c206818b9](https://linux-hardware.org/?probe=0c206818b9) | Sep 15, 2021 |
| Acer          | Aspire VX5-591G             | Notebook    | [c7d5407b29](https://linux-hardware.org/?probe=c7d5407b29) | Sep 15, 2021 |
| Dell          | Latitude E7440              | Notebook    | [fc9f25eecb](https://linux-hardware.org/?probe=fc9f25eecb) | Sep 14, 2021 |
| Toshiba       | Satellite P100              | Notebook    | [bc5b605920](https://linux-hardware.org/?probe=bc5b605920) | Sep 13, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [591ba7a77c](https://linux-hardware.org/?probe=591ba7a77c) | Sep 12, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [49b4db94c6](https://linux-hardware.org/?probe=49b4db94c6) | Sep 12, 2021 |
| Lenovo        | 371C No DPK                 | All in one  | [cd0d01d653](https://linux-hardware.org/?probe=cd0d01d653) | Sep 11, 2021 |
| ASUSTek       | UX303LA                     | Notebook    | [1a67d956de](https://linux-hardware.org/?probe=1a67d956de) | Sep 11, 2021 |
| Intel         | H61                         | Desktop     | [0010dbcb5e](https://linux-hardware.org/?probe=0010dbcb5e) | Sep 10, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [f373a049e2](https://linux-hardware.org/?probe=f373a049e2) | Sep 10, 2021 |
| HP            | 8767 A                      | Desktop     | [7f022c67ac](https://linux-hardware.org/?probe=7f022c67ac) | Sep 09, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [6e97abfd44](https://linux-hardware.org/?probe=6e97abfd44) | Sep 09, 2021 |
| Lenovo        | ThinkPad X201 3249CTO       | Notebook    | [7b3432fcf6](https://linux-hardware.org/?probe=7b3432fcf6) | Sep 08, 2021 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [0614925ee7](https://linux-hardware.org/?probe=0614925ee7) | Sep 08, 2021 |
| Gateway       | NV54 Series                 | Notebook    | [fcf57528ed](https://linux-hardware.org/?probe=fcf57528ed) | Sep 08, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [dfb9789af2](https://linux-hardware.org/?probe=dfb9789af2) | Sep 07, 2021 |
| Sony          | Serie VJC14                 | Notebook    | [27828e1dfb](https://linux-hardware.org/?probe=27828e1dfb) | Sep 07, 2021 |
| Sony          | Serie VJC14                 | Notebook    | [4c1200e7cf](https://linux-hardware.org/?probe=4c1200e7cf) | Sep 07, 2021 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [797db05baf](https://linux-hardware.org/?probe=797db05baf) | Sep 06, 2021 |
| Microsoft     | Surface Laptop Go           | Tablet      | [ebd997cb1a](https://linux-hardware.org/?probe=ebd997cb1a) | Sep 05, 2021 |
| Microsoft     | Surface Laptop Go           | Tablet      | [a5d7b5a10e](https://linux-hardware.org/?probe=a5d7b5a10e) | Sep 05, 2021 |
| HP            | Laptop 15-bs1xx             | Notebook    | [91ecd39f66](https://linux-hardware.org/?probe=91ecd39f66) | Sep 05, 2021 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [633441bc2b](https://linux-hardware.org/?probe=633441bc2b) | Sep 05, 2021 |
| Medion        | Akoya THE TOUCH 10          | Notebook    | [d49d62a2f5](https://linux-hardware.org/?probe=d49d62a2f5) | Sep 04, 2021 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [c9476d5d06](https://linux-hardware.org/?probe=c9476d5d06) | Sep 02, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [da332ba09e](https://linux-hardware.org/?probe=da332ba09e) | Sep 01, 2021 |
| HP            | 86ED A01                    | All in one  | [78778f22a2](https://linux-hardware.org/?probe=78778f22a2) | Sep 01, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [adbb6a690a](https://linux-hardware.org/?probe=adbb6a690a) | Sep 01, 2021 |
| Dell          | Latitude 3580               | Notebook    | [2befbbba9e](https://linux-hardware.org/?probe=2befbbba9e) | Aug 31, 2021 |
| HP            | Pavilion g6                 | Notebook    | [7dba3c201c](https://linux-hardware.org/?probe=7dba3c201c) | Aug 31, 2021 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [0c05ab5b21](https://linux-hardware.org/?probe=0c05ab5b21) | Aug 30, 2021 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [48c720456a](https://linux-hardware.org/?probe=48c720456a) | Aug 30, 2021 |
| ASRock        | H81TM-ITX R2.0              | Desktop     | [4f04e7309e](https://linux-hardware.org/?probe=4f04e7309e) | Aug 30, 2021 |
| HP            | ProBook 4320s               | Notebook    | [94f189cea1](https://linux-hardware.org/?probe=94f189cea1) | Aug 29, 2021 |
| eMachines     | G525                        | Notebook    | [d64e29475f](https://linux-hardware.org/?probe=d64e29475f) | Aug 29, 2021 |
| Microsoft     | Surface Pro 4               | Tablet      | [aeec497ed8](https://linux-hardware.org/?probe=aeec497ed8) | Aug 28, 2021 |
| Lenovo        | ThinkPad X201 3249CTO       | Notebook    | [0a9bdb4827](https://linux-hardware.org/?probe=0a9bdb4827) | Aug 27, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [df0d3e8ac4](https://linux-hardware.org/?probe=df0d3e8ac4) | Aug 26, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [d0ff1c6977](https://linux-hardware.org/?probe=d0ff1c6977) | Aug 25, 2021 |
| HP            | 86ED A01                    | All in one  | [402a8e492c](https://linux-hardware.org/?probe=402a8e492c) | Aug 24, 2021 |
| ASUSTek       | P6X58D-E                    | Desktop     | [db1ef28e92](https://linux-hardware.org/?probe=db1ef28e92) | Aug 20, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [fae546f5cb](https://linux-hardware.org/?probe=fae546f5cb) | Aug 20, 2021 |
| Apple         | MacBookPro9,1               | Notebook    | [e9bec90506](https://linux-hardware.org/?probe=e9bec90506) | Aug 19, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [1176a287c7](https://linux-hardware.org/?probe=1176a287c7) | Aug 19, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [9d7628068c](https://linux-hardware.org/?probe=9d7628068c) | Aug 19, 2021 |
| Dell          | System XPS L321X            | Notebook    | [34d7fb6cbb](https://linux-hardware.org/?probe=34d7fb6cbb) | Aug 18, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [f30480d463](https://linux-hardware.org/?probe=f30480d463) | Aug 17, 2021 |
| HP            | Notebook                    | Notebook    | [a3058005e3](https://linux-hardware.org/?probe=a3058005e3) | Aug 16, 2021 |
| HP            | Notebook                    | Notebook    | [7800ef9623](https://linux-hardware.org/?probe=7800ef9623) | Aug 16, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [fa6c69671f](https://linux-hardware.org/?probe=fa6c69671f) | Aug 16, 2021 |
| ASUSTek       | TUF GAMING B450M-PRO II     | Desktop     | [73beb900ea](https://linux-hardware.org/?probe=73beb900ea) | Aug 15, 2021 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [a8d4959fde](https://linux-hardware.org/?probe=a8d4959fde) | Aug 14, 2021 |
| Apple         | MacBookPro9,1               | Notebook    | [a6b2c12401](https://linux-hardware.org/?probe=a6b2c12401) | Aug 14, 2021 |
| Dell          | Precision 5760              | Notebook    | [824e5e7dad](https://linux-hardware.org/?probe=824e5e7dad) | Aug 14, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [e302074e5e](https://linux-hardware.org/?probe=e302074e5e) | Aug 14, 2021 |
| Acer          | Aspire A514-54              | Notebook    | [dcfc87a32f](https://linux-hardware.org/?probe=dcfc87a32f) | Aug 14, 2021 |
| Acer          | Aspire A514-54              | Notebook    | [e354646c04](https://linux-hardware.org/?probe=e354646c04) | Aug 13, 2021 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [69e2e83b95](https://linux-hardware.org/?probe=69e2e83b95) | Aug 10, 2021 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [86d69a15b9](https://linux-hardware.org/?probe=86d69a15b9) | Aug 10, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4e6f050b43](https://linux-hardware.org/?probe=4e6f050b43) | Aug 10, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [76a8d2c20a](https://linux-hardware.org/?probe=76a8d2c20a) | Jul 29, 2021 |
| Google        | Cave                        | Notebook    | [e2617f0c2d](https://linux-hardware.org/?probe=e2617f0c2d) | Jul 25, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [a97fc63d3d](https://linux-hardware.org/?probe=a97fc63d3d) | Jul 23, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [7124417642](https://linux-hardware.org/?probe=7124417642) | Jul 22, 2021 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [0447155931](https://linux-hardware.org/?probe=0447155931) | Jul 02, 2021 |
| Acer          | Swift SF314-55G             | Notebook    | [c371b46cbe](https://linux-hardware.org/?probe=c371b46cbe) | Jun 30, 2021 |
| Acer          | Swift SF315-41              | Notebook    | [8df5e13fc0](https://linux-hardware.org/?probe=8df5e13fc0) | Jun 18, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [c5d0611f79](https://linux-hardware.org/?probe=c5d0611f79) | Jun 13, 2021 |
| Acer          | Swift SF314-55G             | Notebook    | [4e5cf8aa1e](https://linux-hardware.org/?probe=4e5cf8aa1e) | Jun 13, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [63da02a979](https://linux-hardware.org/?probe=63da02a979) | May 19, 2021 |
| Acer          | ConceptD CN315-71P          | Notebook    | [5ecea84320](https://linux-hardware.org/?probe=5ecea84320) | May 15, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [223234378e](https://linux-hardware.org/?probe=223234378e) | May 04, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [e177523d81](https://linux-hardware.org/?probe=e177523d81) | May 03, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [a208e8a358](https://linux-hardware.org/?probe=a208e8a358) | May 01, 2021 |
| Apple         | MacBookPro8,2               | Notebook    | [e87a073ae8](https://linux-hardware.org/?probe=e87a073ae8) | Mar 18, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [1e31858e51](https://linux-hardware.org/?probe=1e31858e51) | Mar 09, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [f7d949f5a7](https://linux-hardware.org/?probe=f7d949f5a7) | Dec 23, 2020 |
| HP            | 8433 11                     | Desktop     | [691ef58a05](https://linux-hardware.org/?probe=691ef58a05) | Dec 09, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.11.0-40-generic      | 51        | 25.89%  |
| 5.11.0-27-generic      | 38        | 19.29%  |
| 5.11.0-38-generic      | 24        | 12.18%  |
| 5.11.0-37-generic      | 24        | 12.18%  |
| 5.11.0-25-generic      | 16        | 8.12%   |
| 5.11.0-34-generic      | 14        | 7.11%   |
| 5.11.0-41-generic      | 8         | 4.06%   |
| 5.8.0-50-generic       | 5         | 2.54%   |
| 5.11.0-36-generic      | 4         | 2.03%   |
| 5.8.0-55-generic       | 3         | 1.52%   |
| 5.8.0-63-generic       | 2         | 1.02%   |
| 5.8.0-53-generic       | 1         | 0.51%   |
| 5.8.0-44-generic       | 1         | 0.51%   |
| 5.4.0-58-generic       | 1         | 0.51%   |
| 5.4.0-56-generic       | 1         | 0.51%   |
| 5.14.7-xanmod1-cacule  | 1         | 0.51%   |
| 5.14.14-051414-generic | 1         | 0.51%   |
| 5.11.0-41-lowlatency   | 1         | 0.51%   |
| 5.11.0-051100-generic  | 1         | 0.51%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 178       | 91.75%  |
| 5.8.0   | 12        | 6.19%   |
| 5.4.0   | 2         | 1.03%   |
| 5.14.7  | 1         | 0.52%   |
| 5.14.14 | 1         | 0.52%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 178       | 91.75%  |
| 5.8     | 12        | 6.19%   |
| 5.4     | 2         | 1.03%   |
| 5.14    | 2         | 1.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 194       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Pantheon   | 174       | 89.69%  |
| Unknown    | 15        | 7.73%   |
| X-Cinnamon | 2         | 1.03%   |
| GNOME      | 2         | 1.03%   |
| MATE       | 1         | 0.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 194       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 157       | 80.93%  |
| LightDM | 28        | 14.43%  |
| TDM     | 7         | 3.61%   |
| GDM     | 2         | 1.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 95        | 48.97%  |
| de_DE | 19        | 9.79%   |
| es_ES | 18        | 9.28%   |
| ru_RU | 8         | 4.12%   |
| fr_FR | 8         | 4.12%   |
| pt_BR | 6         | 3.09%   |
| it_IT | 4         | 2.06%   |
| en_GB | 4         | 2.06%   |
| zh_CN | 3         | 1.55%   |
| pl_PL | 3         | 1.55%   |
| en_CA | 3         | 1.55%   |
| cs_CZ | 3         | 1.55%   |
| tr_TR | 2         | 1.03%   |
| nl_NL | 2         | 1.03%   |
| en_AU | 2         | 1.03%   |
| de_CH | 2         | 1.03%   |
| ca_ES | 2         | 1.03%   |
| vi_VN | 1         | 0.52%   |
| ro_RO | 1         | 0.52%   |
| lt_LT | 1         | 0.52%   |
| id_ID | 1         | 0.52%   |
| hu_HU | 1         | 0.52%   |
| hr_HR | 1         | 0.52%   |
| fr_BE | 1         | 0.52%   |
| fi_FI | 1         | 0.52%   |
| es_MX | 1         | 0.52%   |
| da_DK | 1         | 0.52%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 120       | 61.86%  |
| BIOS | 74        | 38.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 185       | 95.36%  |
| Overlay | 5         | 2.58%   |
| Btrfs   | 4         | 2.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 162       | 83.51%  |
| GPT     | 21        | 10.82%  |
| MBR     | 11        | 5.67%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 184       | 94.85%  |
| Yes       | 10        | 5.15%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 172       | 88.66%  |
| Yes       | 22        | 11.34%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 46        | 23.71%  |
| Lenovo                  | 21        | 10.82%  |
| ASUSTek Computer        | 20        | 10.31%  |
| Dell                    | 18        | 9.28%   |
| Apple                   | 14        | 7.22%   |
| Acer                    | 14        | 7.22%   |
| Gigabyte Technology     | 13        | 6.7%    |
| MSI                     | 7         | 3.61%   |
| ASRock                  | 6         | 3.09%   |
| Toshiba                 | 4         | 2.06%   |
| Intel                   | 3         | 1.55%   |
| TUXEDO                  | 2         | 1.03%   |
| Sony                    | 2         | 1.03%   |
| Medion                  | 2         | 1.03%   |
| HUAWEI                  | 2         | 1.03%   |
| Google                  | 2         | 1.03%   |
| Biostar                 | 2         | 1.03%   |
| Shuttle                 | 1         | 0.52%   |
| Schenker                | 1         | 0.52%   |
| Samsung Electronics     | 1         | 0.52%   |
| Quanta                  | 1         | 0.52%   |
| Pegatron                | 1         | 0.52%   |
| Panasonic               | 1         | 0.52%   |
| Notebook                | 1         | 0.52%   |
| Microsoft               | 1         | 0.52%   |
| HCL Infosystems Limited | 1         | 0.52%   |
| Gateway                 | 1         | 0.52%   |
| Fujitsu                 | 1         | 0.52%   |
| eMachines               | 1         | 0.52%   |
| Chuwi                   | 1         | 0.52%   |
| Alienware               | 1         | 0.52%   |
| Acidanthera             | 1         | 0.52%   |
| Unknown                 | 1         | 0.52%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo Yoga 300-11IBR 80M1                 | 2         | 1.03%   |
| HP Pavilion Notebook                       | 2         | 1.03%   |
| Dell XPS 13 9350                           | 2         | 1.03%   |
| Apple MacBookPro9,1                        | 2         | 1.03%   |
| Apple MacBookPro10,2                       | 2         | 1.03%   |
| Apple MacBookAir7,2                        | 2         | 1.03%   |
| TUXEDO Pulse 15 Gen1                       | 1         | 0.52%   |
| TUXEDO InfinityBook S 14 Gen6              | 1         | 0.52%   |
| Toshiba Satellite P100                     | 1         | 0.52%   |
| Toshiba Satellite L840                     | 1         | 0.52%   |
| Toshiba Satellite L750                     | 1         | 0.52%   |
| Toshiba Satellite L500                     | 1         | 0.52%   |
| Sony SVE15115EN                            | 1         | 0.52%   |
| Sony Serie VJC14                           | 1         | 0.52%   |
| Shuttle DS61                               | 1         | 0.52%   |
| Schenker X170KM-G                          | 1         | 0.52%   |
| Samsung 550XDA                             | 1         | 0.52%   |
| Quanta TW9/SW9                             | 1         | 0.52%   |
| Pegatron KJ379AA-ABA a6400f                | 1         | 0.52%   |
| Panasonic FZ-G1ASH39E3                     | 1         | 0.52%   |
| Notebook L140CU                            | 1         | 0.52%   |
| MSI MS-7C83                                | 1         | 0.52%   |
| MSI MS-7B79                                | 1         | 0.52%   |
| MSI MS-7817                                | 1         | 0.52%   |
| MSI MS-7693                                | 1         | 0.52%   |
| MSI Modern 14 B4MW                         | 1         | 0.52%   |
| MSI GF72 7RE                               | 1         | 0.52%   |
| MSI Elite 7100 Microtower PC               | 1         | 0.52%   |
| Microsoft Surface Pro 4                    | 1         | 0.52%   |
| Medion E7218                               | 1         | 0.52%   |
| Medion Akoya THE TOUCH 10                  | 1         | 0.52%   |
| Lenovo V330-15IKB 81AX                     | 1         | 0.52%   |
| Lenovo ThinkPad X250 20CLS32H00            | 1         | 0.52%   |
| Lenovo ThinkPad X230 23259L3               | 1         | 0.52%   |
| Lenovo ThinkPad X201 3249CTO               | 1         | 0.52%   |
| Lenovo ThinkPad X140e 20BLS00400           | 1         | 0.52%   |
| Lenovo ThinkPad X1 Carbon 3448B86          | 1         | 0.52%   |
| Lenovo ThinkPad W700 2758MVG               | 1         | 0.52%   |
| Lenovo ThinkPad T470 20HD004AUS            | 1         | 0.52%   |
| Lenovo ThinkPad T460s 20F90042MS           | 1         | 0.52%   |
| Lenovo ThinkPad T430 2342A19               | 1         | 0.52%   |
| Lenovo ThinkPad T410s 292494G              | 1         | 0.52%   |
| Lenovo ThinkPad SL400 2743A37              | 1         | 0.52%   |
| Lenovo ThinkPad E470 20H10052IG            | 1         | 0.52%   |
| Lenovo ThinkPad E14 Gen 3 20Y7006XMX       | 1         | 0.52%   |
| Lenovo IdeaPad S145-15AST 81N3             | 1         | 0.52%   |
| Lenovo IdeaPad 5 14ARE05 81YM              | 1         | 0.52%   |
| Lenovo IdeaPad 330-15IKB 81FE              | 1         | 0.52%   |
| Lenovo IdeaCentre AIO 3 24ARE05 F0EW00FLSC | 1         | 0.52%   |
| Lenovo G50-45 80E3                         | 1         | 0.52%   |
| Intel X64                                  | 1         | 0.52%   |
| Intel NUC7i3BNH                            | 1         | 0.52%   |
| Intel H61                                  | 1         | 0.52%   |
| HUAWEI NBLB-WAX9N                          | 1         | 0.52%   |
| HUAWEI BOHK-WAX9X                          | 1         | 0.52%   |
| HP Z820 Workstation                        | 1         | 0.52%   |
| HP Z800 Workstation                        | 1         | 0.52%   |
| HP Stream Laptop 14-cb1xxx                 | 1         | 0.52%   |
| HP ProBook 6460b                           | 1         | 0.52%   |
| HP ProBook 4730s                           | 1         | 0.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 13        | 6.7%    |
| HP Pavilion            | 13        | 6.7%    |
| Acer Aspire            | 10        | 5.15%   |
| HP ProBook             | 6         | 3.09%   |
| HP Laptop              | 6         | 3.09%   |
| HP EliteBook           | 6         | 3.09%   |
| HP ENVY                | 5         | 2.58%   |
| Toshiba Satellite      | 4         | 2.06%   |
| Dell XPS               | 4         | 2.06%   |
| Dell Inspiron          | 4         | 2.06%   |
| Lenovo IdeaPad         | 3         | 1.55%   |
| Dell Latitude          | 3         | 1.55%   |
| ASUS TUF               | 3         | 1.55%   |
| ASUS ROG               | 3         | 1.55%   |
| Lenovo Yoga            | 2         | 1.03%   |
| HP Compaq              | 2         | 1.03%   |
| Dell System            | 2         | 1.03%   |
| Dell Precision         | 2         | 1.03%   |
| Dell OptiPlex          | 2         | 1.03%   |
| Apple MacBookPro9      | 2         | 1.03%   |
| Apple MacBookPro8      | 2         | 1.03%   |
| Apple MacBookPro10     | 2         | 1.03%   |
| Apple MacBookAir7      | 2         | 1.03%   |
| Acer Swift             | 2         | 1.03%   |
| TUXEDO Pulse           | 1         | 0.52%   |
| TUXEDO InfinityBook    | 1         | 0.52%   |
| Sony SVE15115EN        | 1         | 0.52%   |
| Sony Serie             | 1         | 0.52%   |
| Shuttle DS61           | 1         | 0.52%   |
| Schenker X170KM-G      | 1         | 0.52%   |
| Samsung 550XDA         | 1         | 0.52%   |
| Quanta TW9             | 1         | 0.52%   |
| Pegatron KJ379AA-ABA   | 1         | 0.52%   |
| Panasonic FZ-G1ASH39E3 | 1         | 0.52%   |
| Notebook L140CU        | 1         | 0.52%   |
| MSI MS-7C83            | 1         | 0.52%   |
| MSI MS-7B79            | 1         | 0.52%   |
| MSI MS-7817            | 1         | 0.52%   |
| MSI MS-7693            | 1         | 0.52%   |
| MSI Modern             | 1         | 0.52%   |
| MSI GF72               | 1         | 0.52%   |
| MSI Elite              | 1         | 0.52%   |
| Microsoft Surface      | 1         | 0.52%   |
| Medion E7218           | 1         | 0.52%   |
| Medion Akoya           | 1         | 0.52%   |
| Lenovo V330-15IKB      | 1         | 0.52%   |
| Lenovo IdeaCentre      | 1         | 0.52%   |
| Lenovo G50-45          | 1         | 0.52%   |
| Intel X64              | 1         | 0.52%   |
| Intel NUC7i3BNH        | 1         | 0.52%   |
| Intel H61              | 1         | 0.52%   |
| HUAWEI NBLB-WAX9N      | 1         | 0.52%   |
| HUAWEI BOHK-WAX9X      | 1         | 0.52%   |
| HP Z820                | 1         | 0.52%   |
| HP Z800                | 1         | 0.52%   |
| HP Stream              | 1         | 0.52%   |
| HP Notebook            | 1         | 0.52%   |
| HP EliteDesk           | 1         | 0.52%   |
| HP 339A                | 1         | 0.52%   |
| HP 23-q014a            | 1         | 0.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 46        | 23.71%  |
| 2020    | 28        | 14.43%  |
| 2018    | 19        | 9.79%   |
| 2019    | 18        | 9.28%   |
| 2015    | 15        | 7.73%   |
| 2012    | 13        | 6.7%    |
| 2011    | 12        | 6.19%   |
| 2014    | 10        | 5.15%   |
| 2010    | 8         | 4.12%   |
| 2013    | 7         | 3.61%   |
| 2017    | 6         | 3.09%   |
| 2016    | 4         | 2.06%   |
| 2009    | 4         | 2.06%   |
| 2007    | 2         | 1.03%   |
| 2008    | 1         | 0.52%   |
| Unknown | 1         | 0.52%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 119       | 61.34%  |
| Desktop     | 56        | 28.87%  |
| All in one  | 9         | 4.64%   |
| Convertible | 6         | 3.09%   |
| Tablet      | 3         | 1.55%   |
| Mini pc     | 1         | 0.52%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 161       | 82.99%  |
| Enabled  | 33        | 17.01%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 192       | 98.97%  |
| Yes  | 2         | 1.03%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 57        | 29.38%  |
| 16.01-24.0  | 39        | 20.1%   |
| 3.01-4.0    | 38        | 19.59%  |
| 8.01-16.0   | 30        | 15.46%  |
| 32.01-64.0  | 20        | 10.31%  |
| 1.01-2.0    | 7         | 3.61%   |
| 24.01-32.0  | 1         | 0.52%   |
| 2.01-3.0    | 1         | 0.52%   |
| 64.01-256.0 | 1         | 0.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 82        | 41.41%  |
| 2.01-3.0  | 60        | 30.3%   |
| 3.01-4.0  | 30        | 15.15%  |
| 4.01-8.0  | 21        | 10.61%  |
| 0.51-1.0  | 3         | 1.52%   |
| 8.01-16.0 | 2         | 1.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 126       | 64.62%  |
| 2      | 48        | 24.62%  |
| 3      | 10        | 5.13%   |
| 4      | 7         | 3.59%   |
| 5      | 3         | 1.54%   |
| 6      | 1         | 0.51%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 133       | 68.56%  |
| Yes       | 61        | 31.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 157       | 80.93%  |
| No        | 37        | 19.07%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 166       | 85.57%  |
| No        | 28        | 14.43%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 145       | 74.36%  |
| No        | 50        | 25.64%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 26        | 13.4%   |
| Germany            | 17        | 8.76%   |
| India              | 13        | 6.7%    |
| Russia             | 10        | 5.15%   |
| Canada             | 9         | 4.64%   |
| UK                 | 8         | 4.12%   |
| Brazil             | 8         | 4.12%   |
| France             | 7         | 3.61%   |
| Argentina          | 7         | 3.61%   |
| Mexico             | 6         | 3.09%   |
| Indonesia          | 6         | 3.09%   |
| Spain              | 4         | 2.06%   |
| Poland             | 4         | 2.06%   |
| Netherlands        | 4         | 2.06%   |
| Italy              | 4         | 2.06%   |
| Czechia            | 4         | 2.06%   |
| Vietnam            | 3         | 1.55%   |
| Sweden             | 3         | 1.55%   |
| Finland            | 3         | 1.55%   |
| Denmark            | 3         | 1.55%   |
| Austria            | 3         | 1.55%   |
| Australia          | 3         | 1.55%   |
| Turkey             | 2         | 1.03%   |
| Paraguay           | 2         | 1.03%   |
| Kenya              | 2         | 1.03%   |
| Guatemala          | 2         | 1.03%   |
| China              | 2         | 1.03%   |
| Belgium            | 2         | 1.03%   |
| Uruguay            | 1         | 0.52%   |
| Ukraine            | 1         | 0.52%   |
| Thailand           | 1         | 0.52%   |
| Switzerland        | 1         | 0.52%   |
| Sri Lanka          | 1         | 0.52%   |
| South Africa       | 1         | 0.52%   |
| Slovenia           | 1         | 0.52%   |
| Serbia             | 1         | 0.52%   |
| Romania            | 1         | 0.52%   |
| Philippines        | 1         | 0.52%   |
| New Zealand        | 1         | 0.52%   |
| Myanmar            | 1         | 0.52%   |
| Morocco            | 1         | 0.52%   |
| Malaysia           | 1         | 0.52%   |
| Lithuania          | 1         | 0.52%   |
| Latvia             | 1         | 0.52%   |
| Kazakhstan         | 1         | 0.52%   |
| Japan              | 1         | 0.52%   |
| Hungary            | 1         | 0.52%   |
| Guyana             | 1         | 0.52%   |
| Greece             | 1         | 0.52%   |
| Estonia            | 1         | 0.52%   |
| Dominican Republic | 1         | 0.52%   |
| Croatia            | 1         | 0.52%   |
| Colombia           | 1         | 0.52%   |
| Chile              | 1         | 0.52%   |
| Albania            | 1         | 0.52%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Vienna                   | 3         | 1.52%   |
| Moscow                   | 3         | 1.52%   |
| Mexico City              | 3         | 1.52%   |
| Warsaw                   | 2         | 1.02%   |
| Paris                    | 2         | 1.02%   |
| Nairobi                  | 2         | 1.02%   |
| Mumbai                   | 2         | 1.02%   |
| Montreal                 | 2         | 1.02%   |
| Milan                    | 2         | 1.02%   |
| Medan                    | 2         | 1.02%   |
| Guatemala City           | 2         | 1.02%   |
| Buenos Aires             | 2         | 1.02%   |
| Zonguldak                | 1         | 0.51%   |
| Znojmo                   | 1         | 0.51%   |
| Xicheng District         | 1         | 0.51%   |
| Wythenshawe              | 1         | 0.51%   |
| Wriezen                  | 1         | 0.51%   |
| Woodbridge               | 1         | 0.51%   |
| Wigan                    | 1         | 0.51%   |
| Wattala                  | 1         | 0.51%   |
| Vit??ria                 | 1         | 0.51%   |
| Vilnius                  | 1         | 0.51%   |
| Villeurbanne             | 1         | 0.51%   |
| Victoria                 | 1         | 0.51%   |
| Veyre-Monton             | 1         | 0.51%   |
| Vernon                   | 1         | 0.51%   |
| Vantaa                   | 1         | 0.51%   |
| Vancouver                | 1         | 0.51%   |
| Valladolid               | 1         | 0.51%   |
| Ullastrell               | 1         | 0.51%   |
| Turku                    | 1         | 0.51%   |
| Tucson                   | 1         | 0.51%   |
| Tolyatti                 | 1         | 0.51%   |
| Toluca                   | 1         | 0.51%   |
| Toledo                   | 1         | 0.51%   |
| Tirupur                  | 1         | 0.51%   |
| Thousand Oaks            | 1         | 0.51%   |
| Tallinn                  | 1         | 0.51%   |
| Taganrog                 | 1         | 0.51%   |
| Surabaya                 | 1         | 0.51%   |
| Sukabumi                 | 1         | 0.51%   |
| Stockholm                | 1         | 0.51%   |
| Stevenage                | 1         | 0.51%   |
| Staropyshminsk           | 1         | 0.51%   |
| Sparti                   | 1         | 0.51%   |
| Sinop                    | 1         | 0.51%   |
| Simferopol               | 1         | 0.51%   |
| Schwarzenbach am Wald    | 1         | 0.51%   |
| S??o Pedro               | 1         | 0.51%   |
| S??o Paulo               | 1         | 0.51%   |
| Saskatoon                | 1         | 0.51%   |
| Sao Joaquim da Barra     | 1         | 0.51%   |
| Santiago                 | 1         | 0.51%   |
| Santa Monica             | 1         | 0.51%   |
| Sant Carles de la Rapita | 1         | 0.51%   |
| San Francisco            | 1         | 0.51%   |
| San Antonio              | 1         | 0.51%   |
| Samobor                  | 1         | 0.51%   |
| Saltsjoe-Boo             | 1         | 0.51%   |
| Sakai                    | 1         | 0.51%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 47        | 57     | 17.6%   |
| Samsung Electronics       | 42        | 51     | 15.73%  |
| Seagate                   | 29        | 35     | 10.86%  |
| Sandisk                   | 19        | 22     | 7.12%   |
| Toshiba                   | 16        | 16     | 5.99%   |
| Kingston                  | 14        | 18     | 5.24%   |
| Crucial                   | 13        | 14     | 4.87%   |
| Unknown                   | 11        | 11     | 4.12%   |
| Hitachi                   | 7         | 7      | 2.62%   |
| HGST                      | 7         | 7      | 2.62%   |
| Apple                     | 7         | 7      | 2.62%   |
| Intel                     | 5         | 5      | 1.87%   |
| SK Hynix                  | 3         | 3      | 1.12%   |
| Patriot                   | 3         | 3      | 1.12%   |
| OCZ                       | 3         | 3      | 1.12%   |
| Micron Technology         | 3         | 3      | 1.12%   |
| LITEON                    | 3         | 3      | 1.12%   |
| KIOXIA                    | 3         | 3      | 1.12%   |
| Gigabyte Technology       | 3         | 3      | 1.12%   |
| Transcend                 | 2         | 3      | 0.75%   |
| Silicon Motion            | 2         | 2      | 0.75%   |
| Phison                    | 2         | 2      | 0.75%   |
| Micron/Crucial Technology | 2         | 3      | 0.75%   |
| LITEONIT                  | 2         | 2      | 0.75%   |
| China                     | 2         | 2      | 0.75%   |
| A-DATA Technology         | 2         | 2      | 0.75%   |
| USB3.1                    | 1         | 1      | 0.37%   |
| Union Memory              | 1         | 1      | 0.37%   |
| Team                      | 1         | 1      | 0.37%   |
| StoreJet                  | 1         | 1      | 0.37%   |
| OCZ-VERTEX2               | 1         | 1      | 0.37%   |
| Netac                     | 1         | 1      | 0.37%   |
| Mercury                   | 1         | 1      | 0.37%   |
| LS                        | 1         | 1      | 0.37%   |
| Kingmax                   | 1         | 1      | 0.37%   |
| HUAWEI                    | 1         | 1      | 0.37%   |
| Hewlett-Packard           | 1         | 1      | 0.37%   |
| GALAX                     | 1         | 1      | 0.37%   |
| Dogfish                   | 1         | 1      | 0.37%   |
| CLOVER                    | 1         | 1      | 0.37%   |
| Apacer                    | 1         | 1      | 0.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB     | 6         | 2.09%   |
| Kingston SA400S37240G 240GB SSD  | 6         | 2.09%   |
| Samsung NVMe SSD Drive 500GB     | 5         | 1.74%   |
| Unknown MMC Card  128GB          | 4         | 1.39%   |
| Sandisk NVMe SSD Drive 512GB     | 4         | 1.39%   |
| Samsung NVMe SSD Drive 256GB     | 4         | 1.39%   |
| Intel NVMe SSD Drive 512GB       | 4         | 1.39%   |
| Crucial CT240BX500SSD1 240GB     | 4         | 1.39%   |
| WDC WD10JPVX-22JC3T0 1TB         | 3         | 1.05%   |
| Samsung SSD 860 EVO 250GB        | 3         | 1.05%   |
| Samsung NVMe SSD Drive 1TB       | 3         | 1.05%   |
| Kingston SA400S37480G 480GB SSD  | 3         | 1.05%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 2         | 0.7%    |
| WDC WD5000LPVX-22V0TT0 500GB     | 2         | 0.7%    |
| WDC WD10SPZX-21Z10T0 1TB         | 2         | 0.7%    |
| WDC WD10EZEX-60WN4A0 1TB         | 2         | 0.7%    |
| WDC WD10EZEX-08WN4A0 1TB         | 2         | 0.7%    |
| Unknown MMC Card  16GB           | 2         | 0.7%    |
| Toshiba NVMe SSD Drive 256GB     | 2         | 0.7%    |
| Toshiba MK6475GSX 640GB          | 2         | 0.7%    |
| SK Hynix NVMe SSD Drive 512GB    | 2         | 0.7%    |
| Seagate ST500LT012-1DG142 500GB  | 2         | 0.7%    |
| Seagate ST2000LX001-1RG174 2TB   | 2         | 0.7%    |
| Seagate ST1000LM035-1RK172 1TB   | 2         | 0.7%    |
| Sandisk NVMe SSD Drive 500GB     | 2         | 0.7%    |
| Sandisk NVMe SSD Drive 256GB     | 2         | 0.7%    |
| Samsung SSD 850 EVO 250GB        | 2         | 0.7%    |
| Samsung SSD 840 EVO 120GB        | 2         | 0.7%    |
| KIOXIA NVMe SSD Drive 512GB      | 2         | 0.7%    |
| HGST HTS721010A9E630 1TB         | 2         | 0.7%    |
| HGST HTS541010A9E680 1TB         | 2         | 0.7%    |
| Crucial CT525MX300SSD1 528GB     | 2         | 0.7%    |
| Crucial CT250MX500SSD1 250GB     | 2         | 0.7%    |
| Crucial CT240BX200SSD1 240GB     | 2         | 0.7%    |
| Apple SSD SD128E 121GB           | 2         | 0.7%    |
| WDC WDS500G2B0A 500GB SSD        | 1         | 0.35%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1         | 0.35%   |
| WDC WDS200T2B0B-00YS70 2TB SSD   | 1         | 0.35%   |
| WDC WD6401AALS-00J7B0 640GB      | 1         | 0.35%   |
| WDC WD6400BEVT-22A0RT0 640GB     | 1         | 0.35%   |
| WDC WD5000LPLX-08ZNTT0 500GB     | 1         | 0.35%   |
| WDC WD5000BPVT-75HXZT1 500GB     | 1         | 0.35%   |
| WDC WD5000BPVT-00HXZT1 500GB     | 1         | 0.35%   |
| WDC WD5000BPKT-75PK4T0 500GB     | 1         | 0.35%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 1         | 0.35%   |
| WDC WD5000AAKX-603CA0 500GB      | 1         | 0.35%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 1         | 0.35%   |
| WDC WD5000AAKX-003CA0 500GB      | 1         | 0.35%   |
| WDC WD5000AAKX-001CA0 500GB      | 1         | 0.35%   |
| WDC WD50 00LUCT-61C26Y0 500GB    | 1         | 0.35%   |
| WDC WD40EZRZ-00GXCB0 4TB         | 1         | 0.35%   |
| WDC WD40EZAZ-00SF3B0 4TB         | 1         | 0.35%   |
| WDC WD3200AAJS-56B4A0 320GB      | 1         | 0.35%   |
| WDC WD2500BEKT-75A25T0 250GB     | 1         | 0.35%   |
| WDC WD2500AAKS-00B3A0 250GB      | 1         | 0.35%   |
| WDC WD20SPZX-21UA7T0 2TB         | 1         | 0.35%   |
| WDC WD20EZRX-00D8PB0 2TB         | 1         | 0.35%   |
| WDC WD20EARX-00PASB0 2TB         | 1         | 0.35%   |
| WDC WD20EARS-00MVWB0 2TB         | 1         | 0.35%   |
| WDC WD15EARX-00PASB0 1TB         | 1         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 40        | 48     | 40%     |
| Seagate             | 28        | 33     | 28%     |
| Toshiba             | 12        | 12     | 12%     |
| Hitachi             | 7         | 7      | 7%      |
| HGST                | 7         | 7      | 7%      |
| Samsung Electronics | 4         | 4      | 4%      |
| StoreJet            | 1         | 1      | 1%      |
| Apple               | 1         | 1      | 1%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 22     | 19.79%  |
| Crucial             | 13        | 14     | 13.54%  |
| Kingston            | 11        | 14     | 11.46%  |
| SanDisk             | 10        | 11     | 10.42%  |
| Apple               | 6         | 6      | 6.25%   |
| WDC                 | 5         | 5      | 5.21%   |
| Patriot             | 3         | 3      | 3.13%   |
| OCZ                 | 3         | 3      | 3.13%   |
| LITEON              | 3         | 3      | 3.13%   |
| Transcend           | 2         | 3      | 2.08%   |
| LITEONIT            | 2         | 2      | 2.08%   |
| China               | 2         | 2      | 2.08%   |
| A-DATA Technology   | 2         | 2      | 2.08%   |
| Toshiba             | 1         | 1      | 1.04%   |
| Team                | 1         | 1      | 1.04%   |
| SK Hynix            | 1         | 1      | 1.04%   |
| OCZ-VERTEX2         | 1         | 1      | 1.04%   |
| Netac               | 1         | 1      | 1.04%   |
| Micron Technology   | 1         | 1      | 1.04%   |
| Mercury             | 1         | 1      | 1.04%   |
| LS                  | 1         | 1      | 1.04%   |
| Kingmax             | 1         | 1      | 1.04%   |
| Intel               | 1         | 1      | 1.04%   |
| Hewlett-Packard     | 1         | 1      | 1.04%   |
| Gigabyte Technology | 1         | 1      | 1.04%   |
| GALAX               | 1         | 1      | 1.04%   |
| Dogfish             | 1         | 1      | 1.04%   |
| Apacer              | 1         | 1      | 1.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 92        | 113    | 36.95%  |
| SSD     | 85        | 105    | 34.14%  |
| NVMe    | 56        | 68     | 22.49%  |
| MMC     | 10        | 10     | 4.02%   |
| Unknown | 6         | 6      | 2.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 153       | 217    | 68%     |
| NVMe | 56        | 68     | 24.89%  |
| MMC  | 10        | 10     | 4.44%   |
| SAS  | 6         | 7      | 2.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 112       | 145    | 63.28%  |
| 0.51-1.0   | 52        | 58     | 29.38%  |
| 1.01-2.0   | 10        | 11     | 5.65%   |
| 3.01-4.0   | 2         | 2      | 1.13%   |
| 2.01-3.0   | 1         | 2      | 0.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 76        | 38.78%  |
| 251-500        | 54        | 27.55%  |
| 501-1000       | 22        | 11.22%  |
| 21-50          | 11        | 5.61%   |
| 51-100         | 11        | 5.61%   |
| 1001-2000      | 10        | 5.1%    |
| 2001-3000      | 5         | 2.55%   |
| 1-20           | 5         | 2.55%   |
| More than 3000 | 2         | 1.02%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 102       | 52.58%  |
| 21-50     | 41        | 21.13%  |
| 51-100    | 21        | 10.82%  |
| 101-250   | 14        | 7.22%   |
| 251-500   | 6         | 3.09%   |
| 501-1000  | 6         | 3.09%   |
| 1001-2000 | 3         | 1.55%   |
| 2001-3000 | 1         | 0.52%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000BPKT-75PK4T0 500GB        | 1         | 1      | 9.09%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 1         | 1      | 9.09%   |
| WDC WD3200AAJS-56B4A0 320GB         | 1         | 1      | 9.09%   |
| WDC WD10EZEX-00KUWA0 1TB            | 1         | 1      | 9.09%   |
| Toshiba MK3259GSXP 320GB            | 1         | 1      | 9.09%   |
| Seagate ST320LT020-9YG142 320GB     | 1         | 1      | 9.09%   |
| Seagate ST3160813AS 160GB           | 1         | 1      | 9.09%   |
| Seagate ST1000LX015-1U7172-SSHD 1TB | 1         | 1      | 9.09%   |
| SanDisk SD7SB3Q256G1002 256GB SSD   | 1         | 1      | 9.09%   |
| Samsung Electronics HD160JJ 160GB   | 1         | 1      | 9.09%   |
| Hitachi HTS542525K9SA00 250GB       | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 36.36%  |
| Seagate             | 3         | 3      | 27.27%  |
| Toshiba             | 1         | 1      | 9.09%   |
| SanDisk             | 1         | 1      | 9.09%   |
| Samsung Electronics | 1         | 1      | 9.09%   |
| Hitachi             | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 40%     |
| Seagate             | 3         | 3      | 30%     |
| Toshiba             | 1         | 1      | 10%     |
| Samsung Electronics | 1         | 1      | 10%     |
| Hitachi             | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 10     | 88.89%  |
| SSD  | 1         | 1      | 11.11%  |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 164       | 255    | 82%     |
| Works    | 27        | 36     | 13.5%   |
| Malfunc  | 9         | 11     | 4.5%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 142       | 56.8%   |
| AMD                          | 33        | 13.2%   |
| Samsung Electronics          | 27        | 10.8%   |
| Sandisk                      | 15        | 6%      |
| Toshiba America Info Systems | 3         | 1.2%    |
| Phison Electronics           | 3         | 1.2%    |
| Marvell Technology Group     | 3         | 1.2%    |
| KIOXIA                       | 3         | 1.2%    |
| Kingston Technology Company  | 3         | 1.2%    |
| SK Hynix                     | 2         | 0.8%    |
| Silicon Motion               | 2         | 0.8%    |
| Nvidia                       | 2         | 0.8%    |
| Micron/Crucial Technology    | 2         | 0.8%    |
| Micron Technology            | 2         | 0.8%    |
| JMicron Technology           | 2         | 0.8%    |
| ASMedia Technology           | 2         | 0.8%    |
| VIA Technologies             | 1         | 0.4%    |
| Seagate Technology           | 1         | 0.4%    |
| LSI Logic / Symbios Logic    | 1         | 0.4%    |
| Broadcom / LSI               | 1         | 0.4%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 23        | 8.21%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 17        | 6.07%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12        | 4.29%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 11        | 3.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 10        | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 10        | 3.57%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 8         | 2.86%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 8         | 2.86%   |
| Samsung NVMe SSD Controller 980                                                         | 7         | 2.5%    |
| Intel SATA Controller [RAID mode]                                                       | 6         | 2.14%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 6         | 2.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5         | 1.79%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5         | 1.79%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 4         | 1.43%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 4         | 1.43%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4         | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4         | 1.43%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 3         | 1.07%   |
| Samsung Electronics SATA controller                                                     | 3         | 1.07%   |
| KIOXIA Non-Volatile memory controller                                                   | 3         | 1.07%   |
| Intel SSD 660P Series                                                                   | 3         | 1.07%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 3         | 1.07%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3         | 1.07%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3         | 1.07%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3         | 1.07%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3         | 1.07%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3         | 1.07%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 1.07%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 3         | 1.07%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3         | 1.07%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3         | 1.07%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3         | 1.07%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3         | 1.07%   |
| SK Hynix Gold P31 SSD                                                                   | 2         | 0.71%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 2         | 0.71%   |
| Sandisk Non-Volatile memory controller                                                  | 2         | 0.71%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 0.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2         | 0.71%   |
| Phison PS5013 E13 NVMe Controller                                                       | 2         | 0.71%   |
| Micron Non-Volatile memory controller                                                   | 2         | 0.71%   |
| Kingston Company A2000 NVMe SSD                                                         | 2         | 0.71%   |
| JMicron JMB368 IDE controller                                                           | 2         | 0.71%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 2         | 0.71%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 2         | 0.71%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 0.71%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 2         | 0.71%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2         | 0.71%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                    | 2         | 0.71%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3)  | 2         | 0.71%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 0.71%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 0.71%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2         | 0.71%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 2         | 0.71%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2         | 0.71%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2         | 0.71%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2         | 0.71%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 1         | 0.36%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 1         | 0.36%   |
| Toshiba America Info Systems NVMe Controller                                            | 1         | 0.36%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 1         | 0.36%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 143       | 58.61%  |
| NVMe | 56        | 22.95%  |
| RAID | 23        | 9.43%   |
| IDE  | 20        | 8.2%    |
| SAS  | 1         | 0.41%   |
| SCSI | 1         | 0.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 154       | 79.38%  |
| AMD    | 40        | 20.62%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz           | 6         | 3.09%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 4         | 2.06%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 3         | 1.55%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 3         | 1.55%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 3         | 1.55%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 1.55%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 1.55%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 3         | 1.55%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 2         | 1.03%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 2         | 1.03%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 1.03%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 2         | 1.03%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 2         | 1.03%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.03%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 1.03%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 2         | 1.03%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 1.03%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 2         | 1.03%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2         | 1.03%   |
| Intel Core i3 CPU M 350 @ 2.27GHz           | 2         | 1.03%   |
| Intel Core i3 CPU 530 @ 2.93GHz             | 2         | 1.03%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 2         | 1.03%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 2         | 1.03%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 2         | 1.03%   |
| AMD Ryzen 5 4500U with Radeon Graphics      | 2         | 1.03%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2         | 1.03%   |
| Intel Xeon W-11855M CPU @ 3.20GHz           | 1         | 0.52%   |
| Intel Xeon CPU X5660 @ 2.80GHz              | 1         | 0.52%   |
| Intel Xeon CPU E5520 @ 2.27GHz              | 1         | 0.52%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz          | 1         | 0.52%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz          | 1         | 0.52%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1         | 0.52%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 1         | 0.52%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 0.52%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 0.52%   |
| Intel Pentium CPU N3530 @ 2.16GHz           | 1         | 0.52%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 1         | 0.52%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 0.52%   |
| Intel Pentium CPU 6405U @ 2.40GHz           | 1         | 0.52%   |
| Intel Pentium 3556U @ 1.70GHz               | 1         | 0.52%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.52%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 0.52%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1         | 0.52%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.52%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1         | 0.52%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.52%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.52%   |
| Intel Core i7-5557U CPU @ 3.10GHz           | 1         | 0.52%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 0.52%   |
| Intel Core i7-4930K CPU @ 3.40GHz           | 1         | 0.52%   |
| Intel Core i7-4850HQ CPU @ 2.30GHz          | 1         | 0.52%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1         | 0.52%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 0.52%   |
| Intel Core i7-4785T CPU @ 2.20GHz           | 1         | 0.52%   |
| Intel Core i7-4770S CPU @ 3.10GHz           | 1         | 0.52%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 0.52%   |
| Intel Core i7-4510U CPU @ 2.00GHz           | 1         | 0.52%   |
| Intel Core i7-3720QM CPU @ 2.60GHz          | 1         | 0.52%   |
| Intel Core i7-3687U CPU @ 2.10GHz           | 1         | 0.52%   |
| Intel Core i7-3667U CPU @ 2.00GHz           | 1         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 50        | 25.77%  |
| Intel Core i7           | 35        | 18.04%  |
| Intel Core i3           | 17        | 8.76%   |
| Intel Celeron           | 13        | 6.7%    |
| Other                   | 12        | 6.19%   |
| AMD Ryzen 5             | 11        | 5.67%   |
| AMD Ryzen 7             | 10        | 5.15%   |
| Intel Pentium           | 8         | 4.12%   |
| Intel Core 2 Duo        | 6         | 3.09%   |
| Intel Xeon              | 5         | 2.58%   |
| AMD FX                  | 3         | 1.55%   |
| Intel Pentium Silver    | 2         | 1.03%   |
| Intel Pentium Dual-Core | 2         | 1.03%   |
| AMD A8                  | 2         | 1.03%   |
| AMD A4                  | 2         | 1.03%   |
| Intel Pentium Dual      | 1         | 0.52%   |
| Intel Core 2 Quad       | 1         | 0.52%   |
| Intel Core 2            | 1         | 0.52%   |
| Intel Celeron M         | 1         | 0.52%   |
| AMD Ryzen 9             | 1         | 0.52%   |
| AMD Ryzen 7 PRO         | 1         | 0.52%   |
| AMD Ryzen 3             | 1         | 0.52%   |
| AMD Phenom II X4        | 1         | 0.52%   |
| AMD Phenom II           | 1         | 0.52%   |
| AMD Phenom              | 1         | 0.52%   |
| AMD E1                  | 1         | 0.52%   |
| AMD C-60                | 1         | 0.52%   |
| AMD C-50                | 1         | 0.52%   |
| AMD Athlon II X4        | 1         | 0.52%   |
| AMD A6                  | 1         | 0.52%   |
| AMD A10                 | 1         | 0.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 91        | 46.91%  |
| 4      | 63        | 32.47%  |
| 6      | 20        | 10.31%  |
| 8      | 14        | 7.22%   |
| 12     | 3         | 1.55%   |
| 1      | 2         | 1.03%   |
| 3      | 1         | 0.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 191       | 98.45%  |
| 2      | 3         | 1.55%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 132       | 68.04%  |
| 1      | 62        | 31.96%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 194       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 20        | 10.26%  |
| 0x306a9    | 12        | 6.15%   |
| 0x306c3    | 11        | 5.64%   |
| 0x406e3    | 10        | 5.13%   |
| Unknown    | 10        | 5.13%   |
| 0x806c1    | 9         | 4.62%   |
| 0x20655    | 6         | 3.08%   |
| 0x806ea    | 5         | 2.56%   |
| 0x806e9    | 5         | 2.56%   |
| 0x40651    | 5         | 2.56%   |
| 0x306d4    | 5         | 2.56%   |
| 0x1067a    | 5         | 2.56%   |
| 0x906e9    | 4         | 2.05%   |
| 0x30678    | 4         | 2.05%   |
| 0x20652    | 4         | 2.05%   |
| 0x08701021 | 4         | 2.05%   |
| 0xa0671    | 3         | 1.54%   |
| 0x906ea    | 3         | 1.54%   |
| 0x806ec    | 3         | 1.54%   |
| 0x706a8    | 3         | 1.54%   |
| 0x6fb      | 3         | 1.54%   |
| 0x406c4    | 3         | 1.54%   |
| 0x08600104 | 3         | 1.54%   |
| 0x0800820d | 3         | 1.54%   |
| 0xa0653    | 2         | 1.03%   |
| 0x806eb    | 2         | 1.03%   |
| 0x706a1    | 2         | 1.03%   |
| 0x6fd      | 2         | 1.03%   |
| 0x406c3    | 2         | 1.03%   |
| 0x40661    | 2         | 1.03%   |
| 0x206d7    | 2         | 1.03%   |
| 0x106a5    | 2         | 1.03%   |
| 0x08701013 | 2         | 1.03%   |
| 0x08101007 | 2         | 1.03%   |
| 0x07030105 | 2         | 1.03%   |
| 0x06000852 | 2         | 1.03%   |
| 0xa0655    | 1         | 0.51%   |
| 0xa0652    | 1         | 0.51%   |
| 0x906ed    | 1         | 0.51%   |
| 0x906eb    | 1         | 0.51%   |
| 0x706e5    | 1         | 0.51%   |
| 0x6fa      | 1         | 0.51%   |
| 0x306e4    | 1         | 0.51%   |
| 0x206c2    | 1         | 0.51%   |
| 0x106e5    | 1         | 0.51%   |
| 0x0a50000c | 1         | 0.51%   |
| 0x0a201016 | 1         | 0.51%   |
| 0x08608103 | 1         | 0.51%   |
| 0x08600103 | 1         | 0.51%   |
| 0x08108109 | 1         | 0.51%   |
| 0x08101016 | 1         | 0.51%   |
| 0x0810100b | 1         | 0.51%   |
| 0x0800111c | 1         | 0.51%   |
| 0x07000110 | 1         | 0.51%   |
| 0x0700010f | 1         | 0.51%   |
| 0x06006705 | 1         | 0.51%   |
| 0x0600611a | 1         | 0.51%   |
| 0x06001119 | 1         | 0.51%   |
| 0x0600063e | 1         | 0.51%   |
| 0x05000119 | 1         | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 26        | 13.4%   |
| SandyBridge   | 23        | 11.86%  |
| Haswell       | 18        | 9.28%   |
| IvyBridge     | 13        | 6.7%    |
| Zen 2         | 11        | 5.67%   |
| Westmere      | 11        | 5.67%   |
| Skylake       | 11        | 5.67%   |
| TigerLake     | 9         | 4.64%   |
| Silvermont    | 9         | 4.64%   |
| Penryn        | 6         | 3.09%   |
| Core          | 6         | 3.09%   |
| Zen+          | 5         | 2.58%   |
| Zen           | 5         | 2.58%   |
| Goldmont plus | 5         | 2.58%   |
| Broadwell     | 5         | 2.58%   |
| K10           | 4         | 2.06%   |
| Icelake       | 4         | 2.06%   |
| CometLake     | 4         | 2.06%   |
| Piledriver    | 3         | 1.55%   |
| Nehalem       | 3         | 1.55%   |
| Zen 3         | 2         | 1.03%   |
| Puma          | 2         | 1.03%   |
| Jaguar        | 2         | 1.03%   |
| Excavator     | 2         | 1.03%   |
| Bobcat        | 2         | 1.03%   |
| Unknown       | 2         | 1.03%   |
| Bulldozer     | 1         | 0.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 124       | 55.36%  |
| AMD              | 50        | 22.32%  |
| Nvidia           | 49        | 21.88%  |
| Conexant Systems | 1         | 0.45%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 16        | 6.99%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 11        | 4.8%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 4.37%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 3.93%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 8         | 3.49%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 3.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 2.18%   |
| Intel UHD Graphics 620                                                                   | 5         | 2.18%   |
| Intel HD Graphics 620                                                                    | 5         | 2.18%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 2.18%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 2.18%   |
| AMD Renoir                                                                               | 5         | 2.18%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.75%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 1.75%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 1.75%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 1.31%   |
| Intel HD Graphics 630                                                                    | 3         | 1.31%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.31%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 2         | 0.87%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.87%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 2         | 0.87%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2         | 0.87%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                              | 2         | 0.87%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 2         | 0.87%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 0.87%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.87%   |
| Intel Tiger Lake UHD Graphics                                                            | 2         | 0.87%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.87%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.87%   |
| Intel HD Graphics 6000                                                                   | 2         | 0.87%   |
| Intel HD Graphics 5500                                                                   | 2         | 0.87%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.87%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.87%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 0.87%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 0.87%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.87%   |
| AMD RS780D [Radeon HD 3300]                                                              | 2         | 0.87%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 0.87%   |
| AMD Oland PRO [Radeon R7 240/340]                                                        | 2         | 0.87%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 0.87%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                                     | 2         | 0.87%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.44%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.44%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.44%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.44%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 1         | 0.44%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1         | 0.44%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.44%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 1         | 0.44%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.44%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 0.44%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.44%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1         | 0.44%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1         | 0.44%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.44%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 0.44%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 0.44%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.44%   |
| Nvidia GK107M [GeForce GT 750M]                                                          | 1         | 0.44%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| 1 x Intel                      | 97        | 50%     |
| 1 x AMD                        | 41        | 21.13%  |
| 1 x Nvidia                     | 25        | 12.89%  |
| Intel + Nvidia                 | 22        | 11.34%  |
| Intel + AMD                    | 4         | 2.06%   |
| 2 x AMD                        | 2         | 1.03%   |
| AMD + Nvidia                   | 2         | 1.03%   |
| 2 x AMD + 1 x Conexant Systems | 1         | 0.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 169       | 86.67%  |
| Proprietary | 23        | 11.79%  |
| Unknown     | 3         | 1.54%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 113       | 57.95%  |
| 1.01-2.0   | 21        | 10.77%  |
| 0.51-1.0   | 18        | 9.23%   |
| 0.01-0.5   | 15        | 7.69%   |
| 3.01-4.0   | 12        | 6.15%   |
| 7.01-8.0   | 10        | 5.13%   |
| 5.01-6.0   | 2         | 1.03%   |
| 2.01-3.0   | 2         | 1.03%   |
| 8.01-16.0  | 2         | 1.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 24        | 11.65%  |
| AU Optronics            | 24        | 11.65%  |
| Chimei Innolux          | 23        | 11.17%  |
| BOE                     | 20        | 9.71%   |
| LG Display              | 18        | 8.74%   |
| Hewlett-Packard         | 13        | 6.31%   |
| Apple                   | 13        | 6.31%   |
| Goldstar                | 9         | 4.37%   |
| Dell                    | 7         | 3.4%    |
| BenQ                    | 6         | 2.91%   |
| AOC                     | 6         | 2.91%   |
| Lenovo                  | 5         | 2.43%   |
| Acer                    | 5         | 2.43%   |
| Sharp                   | 4         | 1.94%   |
| CPT                     | 3         | 1.46%   |
| Chi Mei Optoelectronics | 3         | 1.46%   |
| Ancor Communications    | 3         | 1.46%   |
| ViewSonic               | 2         | 0.97%   |
| Vizio                   | 1         | 0.49%   |
| Toshiba                 | 1         | 0.49%   |
| TBD                     | 1         | 0.49%   |
| SKY                     | 1         | 0.49%   |
| Seiko/Epson             | 1         | 0.49%   |
| PANDA                   | 1         | 0.49%   |
| NEC Computers           | 1         | 0.49%   |
| MSI                     | 1         | 0.49%   |
| LGD                     | 1         | 0.49%   |
| LG Philips              | 1         | 0.49%   |
| LG Electronics          | 1         | 0.49%   |
| Lenovo Group Limited    | 1         | 0.49%   |
| HOP                     | 1         | 0.49%   |
| HannStar                | 1         | 0.49%   |
| Grundig                 | 1         | 0.49%   |
| Denver                  | 1         | 0.49%   |
| AUS                     | 1         | 0.49%   |
| Unknown                 | 1         | 0.49%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch           | 4         | 1.89%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 0.94%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 340x190mm 15.3-inch         | 2         | 0.94%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 2         | 0.94%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 2         | 0.94%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO413D 1920x1080 309x173mm 13.9-inch           | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO235C 1366x768 260x140mm 11.6-inch            | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 2         | 0.94%   |
| Apple Color LCD APPA014 2560x1600 286x179mm 13.3-inch                    | 2         | 0.94%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                     | 2         | 0.94%   |
| Apple Color LCD APP9CC7 1280x800 290x180mm 13.4-inch                     | 2         | 0.94%   |
| Apple Color LCD APP9CA4 1440x900 331x207mm 15.4-inch                     | 2         | 0.94%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                          | 2         | 0.94%   |
| AOC 22V2WG5 AOC2202 1920x1080 476x268mm 21.5-inch                        | 2         | 0.94%   |
| Vizio E321VL VIZ0083 1366x768 700x400mm 31.7-inch                        | 1         | 0.47%   |
| ViewSonic VA2445 SERIES VSC712E 1920x1080 521x293mm 23.5-inch            | 1         | 0.47%   |
| ViewSonic LCD Monitor VSC732E 1920x1080 520x290mm 23.4-inch              | 1         | 0.47%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                         | 1         | 0.47%   |
| TBD HDMI TBD3148 1600x900 344x193mm 15.5-inch                            | 1         | 0.47%   |
| SKY TV-monitor SKY0001 1920x1080 697x392mm 31.5-inch                     | 1         | 0.47%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 0.47%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 1         | 0.47%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 1         | 0.47%   |
| Sharp LCD Monitor SHP1420 1920x1080 290x170mm 13.2-inch                  | 1         | 0.47%   |
| Seiko/Epson LCD Monitor 1920x1080                                        | 1         | 0.47%   |
| Samsung Electronics U28H75x SAM0E00 3840x2160 607x345mm 27.5-inch        | 1         | 0.47%   |
| Samsung Electronics U28H75x SAM0DFF 3840x2160 608x345mm 27.5-inch        | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM0428 1680x1050 459x296mm 21.5-inch     | 1         | 0.47%   |
| Samsung Electronics S27D850 SAM0BC8 2560x1440 598x336mm 27.0-inch        | 1         | 0.47%   |
| Samsung Electronics S24D332 SAM0F5E 1920x1080 531x299mm 24.0-inch        | 1         | 0.47%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch        | 1         | 0.47%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch        | 1         | 0.47%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch        | 1         | 0.47%   |
| Samsung Electronics S22C200 SAM09B6 1920x1080 477x268mm 21.5-inch        | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC5842 1366x768 309x174mm 14.0-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC364D 1600x900 382x214mm 17.2-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 344x194mm 15.5-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 340x190mm 15.3-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SDC4E42 1366x768 309x174mm 14.0-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch    | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SAM705B 1920x1080 1210x680mm 54.6-inch   | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 890x500mm 40.2-inch    | 1         | 0.47%   |
| Samsung Electronics LCD Monitor S24F350 5760x1080                        | 1         | 0.47%   |
| Samsung Electronics LCD Monitor S24F350                                  | 1         | 0.47%   |
| Samsung Electronics LCD Monitor C24F390 1920x1080                        | 1         | 0.47%   |
| Samsung Electronics C49J89x SAM0F21 3840x1080 1196x336mm 48.9-inch       | 1         | 0.47%   |
| Samsung Electronics C49HG9x SAM0E5D 3840x1080 1200x340mm 49.1-inch       | 1         | 0.47%   |
| Samsung Electronics C27F591 SAM0D36 1920x1080 598x336mm 27.0-inch        | 1         | 0.47%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 1         | 0.47%   |
| NEC Computers EA241WM NEC674F 1920x1200 518x324mm 24.1-inch              | 1         | 0.47%   |
| MSI MAG272CQR MSI3CA6 2560x1440 598x336mm 27.0-inch                      | 1         | 0.47%   |
| LGD LCD Monitor 1920x1080                                                | 1         | 0.47%   |
| LG Philips LCD Monitor LPLCD00 1680x1050 331x207mm 15.4-inch             | 1         | 0.47%   |
| LG Electronics LCD Monitor LG IPS FULLHD                                 | 1         | 0.47%   |
| LG Display LP156WH2-TLE1 LGDCF01 1366x768 344x194mm 15.5-inch            | 1         | 0.47%   |
| LG Display LP140WH2-TLA1 LGD0201 1366x768 310x174mm 14.0-inch            | 1         | 0.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 83        | 41.92%  |
| 1366x768 (WXGA)    | 47        | 23.74%  |
| 1600x900 (HD+)     | 11        | 5.56%   |
| 3840x2160 (4K)     | 9         | 4.55%   |
| 1280x800 (WXGA)    | 8         | 4.04%   |
| 2560x1440 (QHD)    | 6         | 3.03%   |
| 1440x900 (WXGA+)   | 6         | 3.03%   |
| 2560x1600          | 4         | 2.02%   |
| 1680x1050 (WSXGA+) | 4         | 2.02%   |
| Unknown            | 4         | 2.02%   |
| 3840x1080          | 3         | 1.52%   |
| 2560x1080          | 3         | 1.52%   |
| 1920x1200 (WUXGA)  | 3         | 1.52%   |
| 5760x1080          | 1         | 0.51%   |
| 5120x1440          | 1         | 0.51%   |
| 4480x1440          | 1         | 0.51%   |
| 3840x2400          | 1         | 0.51%   |
| 2880x1800          | 1         | 0.51%   |
| 2736x1824          | 1         | 0.51%   |
| 1280x1024 (SXGA)   | 1         | 0.51%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 58        | 28.57%  |
| 13      | 29        | 14.29%  |
| 14      | 16        | 7.88%   |
| 27      | 13        | 6.4%    |
| 21      | 13        | 6.4%    |
| 23      | 12        | 5.91%   |
| Unknown | 11        | 5.42%   |
| 17      | 8         | 3.94%   |
| 24      | 7         | 3.45%   |
| 12      | 7         | 3.45%   |
| 11      | 5         | 2.46%   |
| 20      | 3         | 1.48%   |
| 72      | 2         | 0.99%   |
| 49      | 2         | 0.99%   |
| 40      | 2         | 0.99%   |
| 19      | 2         | 0.99%   |
| 10      | 2         | 0.99%   |
| 74      | 1         | 0.49%   |
| 54      | 1         | 0.49%   |
| 34      | 1         | 0.49%   |
| 33      | 1         | 0.49%   |
| 32      | 1         | 0.49%   |
| 31      | 1         | 0.49%   |
| 29      | 1         | 0.49%   |
| 28      | 1         | 0.49%   |
| 26      | 1         | 0.49%   |
| 25      | 1         | 0.49%   |
| 22      | 1         | 0.49%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 86        | 43%     |
| 201-300     | 30        | 15%     |
| 501-600     | 28        | 14%     |
| 401-500     | 19        | 9.5%    |
| Unknown     | 11        | 5.5%    |
| 351-400     | 9         | 4.5%    |
| 601-700     | 6         | 3%      |
| 701-800     | 3         | 1.5%    |
| 1501-2000   | 3         | 1.5%    |
| 1001-1500   | 3         | 1.5%    |
| 801-900     | 2         | 1%      |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 142       | 75.53%  |
| 16/10   | 26        | 13.83%  |
| Unknown | 11        | 5.85%   |
| 3/2     | 3         | 1.6%    |
| 21/9    | 3         | 1.6%    |
| 32/9    | 2         | 1.06%   |
| 5/4     | 1         | 0.53%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 58        | 28.71%  |
| 81-90          | 32        | 15.84%  |
| 201-250        | 26        | 12.87%  |
| 301-350        | 15        | 7.43%   |
| 71-80          | 13        | 6.44%   |
| Unknown        | 11        | 5.45%   |
| 151-200        | 9         | 4.46%   |
| 61-70          | 7         | 3.47%   |
| 51-60          | 5         | 2.48%   |
| 121-130        | 5         | 2.48%   |
| More than 1000 | 4         | 1.98%   |
| 351-500        | 4         | 1.98%   |
| 251-300        | 4         | 1.98%   |
| 501-1000       | 4         | 1.98%   |
| 41-50          | 2         | 0.99%   |
| 131-140        | 2         | 0.99%   |
| 141-150        | 1         | 0.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 61        | 31.28%  |
| 101-120       | 59        | 30.26%  |
| 51-100        | 45        | 23.08%  |
| 161-240       | 11        | 5.64%   |
| Unknown       | 11        | 5.64%   |
| 1-50          | 5         | 2.56%   |
| More than 240 | 3         | 1.54%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 170       | 87.18%  |
| 2     | 16        | 8.21%   |
| 3     | 5         | 2.56%   |
| 0     | 4         | 2.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 112       | 36.96%  |
| Intel                             | 79        | 26.07%  |
| Qualcomm Atheros                  | 31        | 10.23%  |
| Broadcom                          | 26        | 8.58%   |
| TP-Link                           | 8         | 2.64%   |
| Broadcom Limited                  | 7         | 2.31%   |
| Ralink Technology                 | 6         | 1.98%   |
| Ralink                            | 4         | 1.32%   |
| Xiaomi                            | 3         | 0.99%   |
| Sierra Wireless                   | 3         | 0.99%   |
| MediaTek                          | 3         | 0.99%   |
| Marvell Technology Group          | 2         | 0.66%   |
| Hewlett-Packard                   | 2         | 0.66%   |
| Samsung Electronics               | 1         | 0.33%   |
| Qualcomm                          | 1         | 0.33%   |
| OPPO Electronics                  | 1         | 0.33%   |
| Nvidia                            | 1         | 0.33%   |
| NetGear                           | 1         | 0.33%   |
| NEC Computers                     | 1         | 0.33%   |
| Mercucys                          | 1         | 0.33%   |
| Linksys                           | 1         | 0.33%   |
| Huawei Technologies               | 1         | 0.33%   |
| Google                            | 1         | 0.33%   |
| Ericsson Business Mobile Networks | 1         | 0.33%   |
| Edimax Technology                 | 1         | 0.33%   |
| DisplayLink                       | 1         | 0.33%   |
| D-Link                            | 1         | 0.33%   |
| Attansic Technology               | 1         | 0.33%   |
| ASUSTek Computer                  | 1         | 0.33%   |
| ASIX Electronics                  | 1         | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 73        | 20.51%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 3.65%   |
| Intel Wi-Fi 6 AX200                                               | 10        | 2.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 2.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 8         | 2.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 1.97%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 6         | 1.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 1.69%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 6         | 1.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.4%    |
| Intel Wi-Fi 6 AX201                                               | 5         | 1.4%    |
| Ralink MT7601U Wireless Adapter                                   | 4         | 1.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 1.12%   |
| Intel Wireless 8260                                               | 4         | 1.12%   |
| Intel Wireless 7265                                               | 4         | 1.12%   |
| Intel Wireless 7260                                               | 4         | 1.12%   |
| Intel I211 Gigabit Network Connection                             | 4         | 1.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.12%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1.12%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 1.12%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 4         | 1.12%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.84%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 3         | 0.84%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 3         | 0.84%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 0.84%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.84%   |
| Intel Wireless 8265 / 8275                                        | 3         | 0.84%   |
| Intel Wireless 3160                                               | 3         | 0.84%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.84%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 0.84%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 0.84%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 0.84%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 0.84%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2         | 0.56%   |
| TP-Link 802.11ac NIC                                              | 2         | 0.56%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 0.56%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2         | 0.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.56%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.56%   |
| MediaTek REVVL V+ 5G                                              | 2         | 0.56%   |
| Intel Wireless 3165                                               | 2         | 0.56%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 2         | 0.56%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.56%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.56%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 0.56%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.56%   |
| Intel Centrino Advanced-N 6235                                    | 2         | 0.56%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 0.56%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 2         | 0.56%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 0.56%   |
| TP-Link 802.11ac WLAN Adapter                                     | 1         | 0.28%   |
| Sierra Wireless MC8305 Modem                                      | 1         | 0.28%   |
| Sierra Wireless EM7455                                            | 1         | 0.28%   |
| Sierra Wireless EM7305                                            | 1         | 0.28%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.28%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.28%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 62        | 34.44%  |
| Realtek Semiconductor    | 36        | 20%     |
| Qualcomm Atheros         | 26        | 14.44%  |
| Broadcom                 | 22        | 12.22%  |
| TP-Link                  | 8         | 4.44%   |
| Ralink Technology        | 6         | 3.33%   |
| Broadcom Limited         | 6         | 3.33%   |
| Ralink                   | 4         | 2.22%   |
| Sierra Wireless          | 3         | 1.67%   |
| NetGear                  | 1         | 0.56%   |
| Mercucys                 | 1         | 0.56%   |
| MEDIATEK                 | 1         | 0.56%   |
| Marvell Technology Group | 1         | 0.56%   |
| Edimax Technology        | 1         | 0.56%   |
| D-Link                   | 1         | 0.56%   |
| ASUSTek Computer         | 1         | 0.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 10        | 5.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 8         | 4.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 7         | 3.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 7         | 3.89%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 6         | 3.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 3.33%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 6         | 3.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 2.78%   |
| Intel Wi-Fi 6 AX201                                            | 5         | 2.78%   |
| Ralink MT7601U Wireless Adapter                                | 4         | 2.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 2.22%   |
| Intel Wireless 8260                                            | 4         | 2.22%   |
| Intel Wireless 7265                                            | 4         | 2.22%   |
| Intel Wireless 7260                                            | 4         | 2.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 2.22%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 4         | 2.22%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 3         | 1.67%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 3         | 1.67%   |
| Intel Wireless 8265 / 8275                                     | 3         | 1.67%   |
| Intel Wireless 3160                                            | 3         | 1.67%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 1.67%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 1.67%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.67%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 1.11%   |
| TP-Link 802.11ac NIC                                           | 2         | 1.11%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 1.11%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2         | 1.11%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 1.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.11%   |
| Intel Wireless 3165                                            | 2         | 1.11%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 1.11%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 1.11%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.11%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 1.11%   |
| TP-Link 802.11ac WLAN Adapter                                  | 1         | 0.56%   |
| Sierra Wireless MC8305 Modem                                   | 1         | 0.56%   |
| Sierra Wireless EM7455                                         | 1         | 0.56%   |
| Sierra Wireless EM7305                                         | 1         | 0.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 0.56%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 0.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 0.56%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 0.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.56%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.56%   |
| Realtek RTL8187 Wireless Adapter                               | 1         | 0.56%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 0.56%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 0.56%   |
| Ralink RT5592 PCIe Wireless Network Adapter                    | 1         | 0.56%   |
| Ralink RT2800 802.11n PCI                                      | 1         | 0.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 0.56%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1         | 0.56%   |
| NetGear WNA3100(v1) Wireless-N 300 [Broadcom BCM43231]         | 1         | 0.56%   |
| Mercucys 802.11n NIC                                           | 1         | 0.56%   |
| MEDIATEK Network controller                                    | 1         | 0.56%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 1         | 0.56%   |
| Intel Wireless-AC 9260                                         | 1         | 0.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 0.56%   |
| Intel Ultimate N WiFi Link 5300                                | 1         | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 92        | 54.76%  |
| Intel                    | 38        | 22.62%  |
| Broadcom                 | 13        | 7.74%   |
| Qualcomm Atheros         | 9         | 5.36%   |
| Xiaomi                   | 3         | 1.79%   |
| MediaTek                 | 2         | 1.19%   |
| Samsung Electronics      | 1         | 0.6%    |
| Qualcomm                 | 1         | 0.6%    |
| OPPO Electronics         | 1         | 0.6%    |
| Nvidia                   | 1         | 0.6%    |
| Marvell Technology Group | 1         | 0.6%    |
| Linksys                  | 1         | 0.6%    |
| Google                   | 1         | 0.6%    |
| DisplayLink              | 1         | 0.6%    |
| Broadcom Limited         | 1         | 0.6%    |
| Attansic Technology      | 1         | 0.6%    |
| ASIX Electronics         | 1         | 0.6%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 73        | 42.69%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 7.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 5.85%   |
| Intel I211 Gigabit Network Connection                             | 4         | 2.34%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 2.34%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 2.34%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 1.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 1.75%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.75%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 1.75%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.17%   |
| MediaTek REVVL V+ 5G                                              | 2         | 1.17%   |
| Intel Ethernet Connection I219-V                                  | 2         | 1.17%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.17%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.17%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 1.17%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 2         | 1.17%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 1.17%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.58%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.58%   |
| Qualcomm BOLT!-JUNO                                               | 1         | 0.58%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.58%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.58%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.58%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.58%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.58%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.58%   |
| OPPO RMX2027                                                      | 1         | 0.58%   |
| Nvidia MCP77 Ethernet                                             | 1         | 0.58%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.58%   |
| Linksys Gigabit Ethernet Adapter                                  | 1         | 0.58%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.58%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.58%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.58%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.58%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.58%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.58%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.58%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 0.58%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.58%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.58%   |
| Google Nexus 4/5/7/10 (tether)                                    | 1         | 0.58%   |
| DisplayLink USB3.0 5K Graphic Docking                             | 1         | 0.58%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 0.58%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.58%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.58%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.58%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 0.58%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 1         | 0.58%   |
| ASIX AX88772B                                                     | 1         | 0.58%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 166       | 50.46%  |
| Ethernet | 158       | 48.02%  |
| Modem    | 4         | 1.22%   |
| Unknown  | 1         | 0.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 149       | 51.03%  |
| Ethernet | 143       | 48.97%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 115       | 59.28%  |
| 1     | 77        | 39.69%  |
| 3     | 1         | 0.52%   |
| 0     | 1         | 0.52%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 146       | 75.26%  |
| Yes  | 48        | 24.74%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 51        | 35.42%  |
| Realtek Semiconductor           | 21        | 14.58%  |
| Qualcomm Atheros Communications | 14        | 9.72%   |
| Apple                           | 14        | 9.72%   |
| Broadcom                        | 12        | 8.33%   |
| Cambridge Silicon Radio         | 9         | 6.25%   |
| Lite-On Technology              | 5         | 3.47%   |
| Foxconn / Hon Hai               | 4         | 2.78%   |
| IMC Networks                    | 3         | 2.08%   |
| Ralink                          | 2         | 1.39%   |
| Dell                            | 2         | 1.39%   |
| Toshiba                         | 1         | 0.69%   |
| Realtek                         | 1         | 0.69%   |
| Qcom                            | 1         | 0.69%   |
| Marvell Semiconductor           | 1         | 0.69%   |
| Hewlett-Packard                 | 1         | 0.69%   |
| Belkin Components               | 1         | 0.69%   |
| ASUSTek Computer                | 1         | 0.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 21        | 14.58%  |
| Realtek Bluetooth Radio                             | 11        | 7.64%   |
| Intel Bluetooth Device                              | 11        | 7.64%   |
| Intel AX200 Bluetooth                               | 10        | 6.94%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9         | 6.25%   |
| Realtek  Bluetooth 4.2 Adapter                      | 7         | 4.86%   |
| Apple Bluetooth Host Controller                     | 7         | 4.86%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 6         | 4.17%   |
| Apple Bluetooth USB Host Controller                 | 6         | 4.17%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 2.78%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 2.78%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 2.08%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 2.08%   |
| Realtek 802.11n WLAN Adapter                        | 2         | 1.39%   |
| Ralink RT3290 Bluetooth                             | 2         | 1.39%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 1.39%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.39%   |
| IMC Networks Bluetooth Radio                        | 2         | 1.39%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.39%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 2         | 1.39%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.69%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.69%   |
| Realtek Bluetooth Radio                             | 1         | 0.69%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.69%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.69%   |
| Qcom Broadcom Bluetooth USB                         | 1         | 0.69%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 0.69%   |
| Lite-On Wireless_Device                             | 1         | 0.69%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.69%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 1         | 0.69%   |
| Lite-On Bluetooth Device                            | 1         | 0.69%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.69%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.69%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.69%   |
| Intel AX210 Bluetooth                               | 1         | 0.69%   |
| IMC Networks BCM20702A0                             | 1         | 0.69%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.69%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.69%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.69%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.69%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1         | 0.69%   |
| Broadcom HP Portable Valentine                      | 1         | 0.69%   |
| Broadcom Bluetooth 3.0 Dongle                       | 1         | 0.69%   |
| Broadcom BCM20702A0                                 | 1         | 0.69%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 0.69%   |
| Belkin Components Bluetooth Mini Dongle             | 1         | 0.69%   |
| ASUS Bluetooth Radio                                | 1         | 0.69%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 0.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 151       | 57.85%  |
| AMD                                  | 53        | 20.31%  |
| Nvidia                               | 36        | 13.79%  |
| Generalplus Technology               | 3         | 1.15%   |
| Creative Labs                        | 3         | 1.15%   |
| C-Media Electronics                  | 3         | 1.15%   |
| Logitech                             | 2         | 0.77%   |
| JMTek                                | 2         | 0.77%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.38%   |
| TEAC                                 | 1         | 0.38%   |
| Razer USA                            | 1         | 0.38%   |
| Focusrite-Novation                   | 1         | 0.38%   |
| Creative Technology                  | 1         | 0.38%   |
| Corsair                              | 1         | 0.38%   |
| BY EDIFIER                           | 1         | 0.38%   |
| ASUSTek Computer                     | 1         | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 21        | 6.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 19        | 6.05%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 4.46%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 13        | 4.14%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 12        | 3.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11        | 3.5%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 9         | 2.87%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8         | 2.55%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 8         | 2.55%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 7         | 2.23%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 2.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 1.91%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 1.91%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.59%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 1.59%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 1.59%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 1.59%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 1.59%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 1.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 1.59%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 1.59%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 1.59%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.59%   |
| AMD FCH Azalia Controller                                                                         | 5         | 1.59%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 1.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.27%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4         | 1.27%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.96%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.96%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.96%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 0.96%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 0.96%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.96%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 3         | 0.96%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 0.96%   |
| Intel 200 Series PCH HD Audio                                                                     | 3         | 0.96%   |
| Generalplus Technology USB Audio Device                                                           | 3         | 0.96%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3         | 0.96%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 0.96%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 3         | 0.96%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 2         | 0.64%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 0.64%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.64%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 2         | 0.64%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 0.64%   |
| Intel Crystal Well HD Audio Controller                                                            | 2         | 0.64%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.64%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.64%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                                        | 2         | 0.64%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.64%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                            | 2         | 0.64%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.64%   |
| Thesycon Systemsoftware & Consulting DX3 Pro                                                      | 1         | 0.32%   |
| TEAC TASCAM iXR                                                                                   | 1         | 0.32%   |
| Razer USA Kraken Tournament Edition                                                               | 1         | 0.32%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.32%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.32%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.32%   |
| Nvidia stereo controller                                                                          | 1         | 0.32%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.32%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 17        | 25.37%  |
| SK Hynix            | 11        | 16.42%  |
| Kingston            | 10        | 14.93%  |
| Micron Technology   | 9         | 13.43%  |
| Unknown             | 3         | 4.48%   |
| G.Skill             | 3         | 4.48%   |
| Crucial             | 3         | 4.48%   |
| Ramaxel Technology  | 2         | 2.99%   |
| Corsair             | 2         | 2.99%   |
| A-DATA Technology   | 2         | 2.99%   |
| Toshiba             | 1         | 1.49%   |
| Qimonda             | 1         | 1.49%   |
| Neo Forza           | 1         | 1.49%   |
| Nanya Technology    | 1         | 1.49%   |
| Kllisre             | 1         | 1.49%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s         | 3         | 4.29%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4096MB SODIMM DDR4 2667MT/s     | 2         | 2.86%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s         | 2         | 2.86%   |
| Unknown RAM Module 4096MB Chip DDR4 2133MT/s                  | 1         | 1.43%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                   | 1         | 1.43%   |
| Unknown RAM Module 1024MB SODIMM LPDDR4 2400MT/s              | 1         | 1.43%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s            | 1         | 1.43%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s             | 1         | 1.43%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                  | 1         | 1.43%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 1.43%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 1         | 1.43%   |
| SK Hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s        | 1         | 1.43%   |
| SK Hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s          | 1         | 1.43%   |
| SK Hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s        | 1         | 1.43%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 1         | 1.43%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s        | 1         | 1.43%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s     | 1         | 1.43%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                | 1         | 1.43%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s         | 1         | 1.43%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s      | 1         | 1.43%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM 1067MT/s              | 1         | 1.43%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s      | 1         | 1.43%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s      | 1         | 1.43%   |
| Samsung RAM M471B2873FHS-CF8 1GB SODIMM DDR3 1067MT/s         | 1         | 1.43%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s         | 1         | 1.43%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s        | 1         | 1.43%   |
| Samsung RAM M471A2G43AB2-CWE 16384MB SODIMM DDR4 3200MT/s     | 1         | 1.43%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s         | 1         | 1.43%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR2 800MT/s         | 1         | 1.43%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s           | 1         | 1.43%   |
| Ramaxel RAM RMT3170EF68F9W1600 4096MB SODIMM DDR3 1600MT/s    | 1         | 1.43%   |
| Ramaxel RAM RMSA3310NA86H9F-2666 4GB SODIMM DDR4 2667MT/s     | 1         | 1.43%   |
| Qimonda RAM 64T256020EDL2.5C2 2048MB SODIMM DDR2 2048MT/s     | 1         | 1.43%   |
| Neo Forza RAM NMUD380D81-1600D 8GB DIMM DDR3 1333MT/s         | 1         | 1.43%   |
| Nanya RAM Module 4GB DIMM DDR3 1333MT/s                       | 1         | 1.43%   |
| Micron RAM MT41K256M16LY 2GB SODIMM DDR3 1600MT/s             | 1         | 1.43%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                 | 1         | 1.43%   |
| Micron RAM Module 2048MB SODIMM DDR3 1600MT/s                 | 1         | 1.43%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s         | 1         | 1.43%   |
| Micron RAM 8ATF1G64HZ-2G6H1 8GB SODIMM DDR4 2667MT/s          | 1         | 1.43%   |
| Micron RAM 4ATF51264HZ-2G6E3 4096MB SODIMM DDR4 2667MT/s      | 1         | 1.43%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8192MB SODIMM DDR4 3200MT/s       | 1         | 1.43%   |
| Micron RAM 16JSF25664HZ-1G4F1 2GB SODIMM DDR3 1334MT/s        | 1         | 1.43%   |
| Micron RAM 16ATF2G64HZ-3G2J1 16GB SODIMM DDR4 3200MT/s        | 1         | 1.43%   |
| Kllisre RAM KRE-D3S1600M/8G 8192MB SODIMM DDR3 1600MT/s       | 1         | 1.43%   |
| Kingston RAM KHX2666C15S4/8G 8GB SODIMM DDR4 2667MT/s         | 1         | 1.43%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3                    | 1         | 1.43%   |
| Kingston RAM HP16D3LS1KBG/8G 8192MB SODIMM DDR3 1600MT/s      | 1         | 1.43%   |
| Kingston RAM ACR16D3LS1KFG/8G 8192MB SODIMM DDR3 1600MT/s     | 1         | 1.43%   |
| Kingston RAM 99U5471-052.A 8GB DIMM DDR3 1333MT/s             | 1         | 1.43%   |
| Kingston RAM 99U5458-001.A00LF 2GB DIMM DDR3 1600MT/s         | 1         | 1.43%   |
| Kingston RAM 99U5403-159.A01LF 8192MB DIMM DDR3 1333MT/s      | 1         | 1.43%   |
| Kingston RAM 9965516-069.A00LF 8GB DIMM DDR3 1333MT/s         | 1         | 1.43%   |
| Kingston RAM 9965516-003.A00LF 8GB DIMM DDR3 1333MT/s         | 1         | 1.43%   |
| Kingston RAM 9905700-070.A01G 16GB SODIMM DDR4 2667MT/s       | 1         | 1.43%   |
| Kingston RAM 9905700-026.A00G 8GB SODIMM DDR4 2667MT/s        | 1         | 1.43%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s        | 1         | 1.43%   |
| G.Skill RAM F3-1866C11-8GRSL 8GB SODIMM DDR3 1867MT/s         | 1         | 1.43%   |
| G.Skill RAM F3-14900CL9-4GBSR 4096MB DIMM DDR3 1600MT/s       | 1         | 1.43%   |
| Crucial RAM CT16G4SFRA32A.M16FRS 16384MB SODIMM DDR4 3200MT/s | 1         | 1.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 23        | 45.1%   |
| DDR3   | 23        | 45.1%   |
| SDRAM  | 2         | 3.92%   |
| DDR2   | 2         | 3.92%   |
| LPDDR4 | 1         | 1.96%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 40        | 76.92%  |
| DIMM   | 11        | 21.15%  |
| Chip   | 1         | 1.92%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 21        | 35.59%  |
| 4096  | 19        | 32.2%   |
| 2048  | 10        | 16.95%  |
| 16384 | 7         | 11.86%  |
| 1024  | 2         | 3.39%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 18        | 30.51%  |
| 2667  | 11        | 18.64%  |
| 3200  | 8         | 13.56%  |
| 2400  | 4         | 6.78%   |
| 2133  | 4         | 6.78%   |
| 1333  | 4         | 6.78%   |
| 4199  | 1         | 1.69%   |
| 3600  | 1         | 1.69%   |
| 3007  | 1         | 1.69%   |
| 3000  | 1         | 1.69%   |
| 2048  | 1         | 1.69%   |
| 1867  | 1         | 1.69%   |
| 1334  | 1         | 1.69%   |
| 1067  | 1         | 1.69%   |
| 1066  | 1         | 1.69%   |
| 800   | 1         | 1.69%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 2         | 66.67%  |
| Brother Industries | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| HP LaserJet M101-M106   | 1         | 33.33%  |
| HP Deskjet F4500 series | 1         | 33.33%  |
| Brother MFC-T800W       | 1         | 33.33%  |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 34        | 26.15%  |
| Realtek Semiconductor                  | 10        | 7.69%   |
| Apple                                  | 10        | 7.69%   |
| Acer                                   | 10        | 7.69%   |
| Quanta                                 | 9         | 6.92%   |
| Microdia                               | 9         | 6.92%   |
| Sunplus Innovation Technology          | 7         | 5.38%   |
| Logitech                               | 7         | 5.38%   |
| Suyin                                  | 6         | 4.62%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.85%   |
| Syntek                                 | 4         | 3.08%   |
| Luxvisions Innotech Limited            | 3         | 2.31%   |
| Lenovo                                 | 3         | 2.31%   |
| Microsoft                              | 2         | 1.54%   |
| Lite-On Technology                     | 2         | 1.54%   |
| IMC Networks                           | 2         | 1.54%   |
| Z-Star Microelectronics                | 1         | 0.77%   |
| SHENZHEN Fullhan                       | 1         | 0.77%   |
| Primax Electronics                     | 1         | 0.77%   |
| Importek                               | 1         | 0.77%   |
| icSpring                               | 1         | 0.77%   |
| Generalplus Technology                 | 1         | 0.77%   |
| Creative Technology                    | 1         | 0.77%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 6         | 4.58%   |
| Apple FaceTime HD Camera                             | 4         | 3.05%   |
| Realtek Integrated_Webcam_HD                         | 3         | 2.29%   |
| Realtek HD WebCam                                    | 3         | 2.29%   |
| Quanta HP TrueVision HD Camera                       | 3         | 2.29%   |
| Chicony HP Wide Vision HD Camera                     | 3         | 2.29%   |
| Chicony HP Truevision HD                             | 3         | 2.29%   |
| Chicony HP HD Webcam [Fixed]                         | 3         | 2.29%   |
| Chicony HD Webcam                                    | 3         | 2.29%   |
| Apple FaceTime HD Camera (Built-in)                  | 3         | 2.29%   |
| Acer Lenovo EasyCamera                               | 3         | 2.29%   |
| Syntek Integrated Camera                             | 2         | 1.53%   |
| Suyin Acer/HP Integrated Webcam [CN0314]             | 2         | 1.53%   |
| Suyin 1.3M HD WebCam                                 | 2         | 1.53%   |
| Sunplus Laptop_Integrated_Webcam_HD                  | 2         | 1.53%   |
| Microdia Integrated Webcam HD                        | 2         | 1.53%   |
| Logitech Webcam C270                                 | 2         | 1.53%   |
| Chicony USB2.0 Camera                                | 2         | 1.53%   |
| Chicony HP TrueVision HD Camera                      | 2         | 1.53%   |
| Chicony HP High Definition 1MP Webcam                | 2         | 1.53%   |
| Apple iPhone 5/5C/5S/6/SE                            | 2         | 1.53%   |
| Acer Integrated Camera                               | 2         | 1.53%   |
| Z-Star Sirius USB2.0 Camera                          | 1         | 0.76%   |
| Syntek USB2.0 Camera                                 | 1         | 0.76%   |
| Syntek EasyCamera                                    | 1         | 0.76%   |
| Suyin HP TrueVision HD Integrated Webcam             | 1         | 0.76%   |
| Suyin Asus Integrated Webcam                         | 1         | 0.76%   |
| Sunplus Laptop_Integrated_Webcam_1.3M                | 1         | 0.76%   |
| Sunplus Laptop Integrated WebCam HD                  | 1         | 0.76%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 0.76%   |
| Sunplus FHD Camera Microphone                        | 1         | 0.76%   |
| Sunplus 1.3M HD WebCam                               | 1         | 0.76%   |
| SHENZHEN Fullhan webcam                              | 1         | 0.76%   |
| Realtek Integrated Webcam                            | 1         | 0.76%   |
| Realtek Integrated Camera                            | 1         | 0.76%   |
| Realtek HP Truevision HD                             | 1         | 0.76%   |
| Realtek 2SF022                                       | 1         | 0.76%   |
| Quanta ov9734_techfront_camera                       | 1         | 0.76%   |
| Quanta HP Webcam                                     | 1         | 0.76%   |
| Quanta HP TrueVision HD Webcam                       | 1         | 0.76%   |
| Quanta HP 5M Camera                                  | 1         | 0.76%   |
| Quanta HD User Facing                                | 1         | 0.76%   |
| Quanta HD Camera                                     | 1         | 0.76%   |
| Primax Villem                                        | 1         | 0.76%   |
| Microsoft Xbox NUI Camera                            | 1         | 0.76%   |
| Microsoft LifeCam HD-3000                            | 1         | 0.76%   |
| Microdia Webcam Vitade AF                            | 1         | 0.76%   |
| Microdia USB Live camera                             | 1         | 0.76%   |
| Microdia Laptop_Integrated_Webcam_FHD                | 1         | 0.76%   |
| Microdia Laptop_Integrated_Webcam_2M                 | 1         | 0.76%   |
| Microdia Integrated_Webcam_FHD                       | 1         | 0.76%   |
| Microdia Integrated Webcam                           | 1         | 0.76%   |
| Microdia Integrated Camera                           | 1         | 0.76%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 0.76%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 1         | 0.76%   |
| Luxvisions Innotech Limited HP HD Camera             | 1         | 0.76%   |
| Logitech HD Webcam C615                              | 1         | 0.76%   |
| Logitech HD Pro Webcam C920                          | 1         | 0.76%   |
| Logitech C505 HD Webcam                              | 1         | 0.76%   |
| Logitech BRIO 4K Stream Edition                      | 1         | 0.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 12        | 46.15%  |
| Synaptics                  | 3         | 11.54%  |
| LighTuning Technology      | 3         | 11.54%  |
| Upek                       | 2         | 7.69%   |
| Shenzhen Goodix Technology | 2         | 7.69%   |
| AuthenTec                  | 2         | 7.69%   |
| STMicroelectronics         | 1         | 3.85%   |
| Focal-systems.Corp         | 1         | 3.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 3         | 11.54%  |
| LighTuning EgisTec Touch Fingerprint Sensor            | 3         | 11.54%  |
| Validity Sensors VFS471 Fingerprint Reader             | 2         | 7.69%   |
| Validity Sensors Swipe Fingerprint Sensor              | 2         | 7.69%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 7.69%   |
| Shenzhen Goodix  FingerPrint Device                    | 2         | 7.69%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 3.85%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 3.85%   |
| Validity Sensors VFS491                                | 1         | 3.85%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 3.85%   |
| Validity Sensors Synaptics WBDI                        | 1         | 3.85%   |
| Synaptics  WBDI Fingerprint Reader - USB 052           | 1         | 3.85%   |
| Synaptics  WBDI                                        | 1         | 3.85%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 3.85%   |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 3.85%   |
| AuthenTec Fingerprint Sensor                           | 1         | 3.85%   |
| AuthenTec AES2810                                      | 1         | 3.85%   |
| Unknown                                                | 1         | 3.85%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 50%     |
| Upek        | 1         | 25%     |
| Alcor Micro | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 25%     |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 25%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 137       | 70.26%  |
| 1     | 49        | 25.13%  |
| 2     | 9         | 4.62%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 26        | 37.68%  |
| Net/wireless             | 14        | 20.29%  |
| Graphics card            | 9         | 13.04%  |
| Multimedia controller    | 8         | 11.59%  |
| Chipcard                 | 4         | 5.8%    |
| Sound                    | 2         | 2.9%    |
| Net/ethernet             | 2         | 2.9%    |
| Bluetooth                | 2         | 2.9%    |
| Communication controller | 1         | 1.45%   |
| Camera                   | 1         | 1.45%   |

