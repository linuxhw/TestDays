Linux Lite - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for Linux Lite.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Linux_Lite/Desktop/README.md) and [notebooks](/Dist/Linux_Lite/Notebook/README.md).

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

Total: 341

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | Aspire ES1-521              | Notebook    | [6c3ad2b59f](https://linux-hardware.org/?probe=6c3ad2b59f) | Dec 31, 2025 |
| Acer          | Aspire ES1-521              | Notebook    | [33ed3f8ac4](https://linux-hardware.org/?probe=33ed3f8ac4) | Dec 31, 2025 |
| Acer          | Aspire E5-553               | Notebook    | [7d30225b40](https://linux-hardware.org/?probe=7d30225b40) | Dec 19, 2025 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [4544f05395](https://linux-hardware.org/?probe=4544f05395) | Nov 17, 2025 |
| VIT           | P2400                       | Notebook    | [fd53bea2e1](https://linux-hardware.org/?probe=fd53bea2e1) | Nov 17, 2025 |
| HP            | EliteBook 8460p             | Notebook    | [37b10d88d8](https://linux-hardware.org/?probe=37b10d88d8) | Nov 08, 2025 |
| HP            | Notebook                    | Notebook    | [5dc610343e](https://linux-hardware.org/?probe=5dc610343e) | Nov 05, 2025 |
| HP            | Notebook                    | Notebook    | [cbc5387b7a](https://linux-hardware.org/?probe=cbc5387b7a) | Nov 05, 2025 |
| ASRock        | B550M-ITX/ac                | Desktop     | [c94ad863b1](https://linux-hardware.org/?probe=c94ad863b1) | Oct 16, 2025 |
| MSI           | G41M-P23                    | Desktop     | [ef935d9e4d](https://linux-hardware.org/?probe=ef935d9e4d) | Oct 03, 2025 |
| MSI           | G41M-P23                    | Desktop     | [26f65abd84](https://linux-hardware.org/?probe=26f65abd84) | Sep 23, 2025 |
| Biostar       | A68N-2100                   | Desktop     | [6f9c53ce22](https://linux-hardware.org/?probe=6f9c53ce22) | Sep 13, 2025 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [77b5d4b762](https://linux-hardware.org/?probe=77b5d4b762) | Sep 08, 2025 |
| Dell          | Inspiron 1545               | Notebook    | [46311632f7](https://linux-hardware.org/?probe=46311632f7) | Aug 21, 2025 |
| Dell          | Inspiron 1545               | Notebook    | [42869a1896](https://linux-hardware.org/?probe=42869a1896) | Aug 19, 2025 |
| Dell          | 0DR845                      | Desktop     | [1b99b0c1fa](https://linux-hardware.org/?probe=1b99b0c1fa) | Aug 18, 2025 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [994842d222](https://linux-hardware.org/?probe=994842d222) | Aug 16, 2025 |
| Lenovo        | ThinkPad T440p 20AN00C6G... | Notebook    | [a6720311da](https://linux-hardware.org/?probe=a6720311da) | Aug 12, 2025 |
| Acer          | FMP55                       | Desktop     | [574efa6d4b](https://linux-hardware.org/?probe=574efa6d4b) | Jul 03, 2025 |
| Gigabyte      | H61M-S1                     | Desktop     | [bb3fbb0ebb](https://linux-hardware.org/?probe=bb3fbb0ebb) | Jul 02, 2025 |
| Gigabyte      | H61M-S1                     | Desktop     | [b76d0aef1d](https://linux-hardware.org/?probe=b76d0aef1d) | Jun 29, 2025 |
| ASUSTek       | UX330UAK                    | Notebook    | [8182fc3560](https://linux-hardware.org/?probe=8182fc3560) | Jun 20, 2025 |
| Acer          | Aspire VN7-592G             | Notebook    | [a111583d6f](https://linux-hardware.org/?probe=a111583d6f) | Jun 19, 2025 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [d3af1fc036](https://linux-hardware.org/?probe=d3af1fc036) | Jun 14, 2025 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [a6c52c4ea4](https://linux-hardware.org/?probe=a6c52c4ea4) | Jun 14, 2025 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [fc7894571e](https://linux-hardware.org/?probe=fc7894571e) | Jun 14, 2025 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [1f73771d4d](https://linux-hardware.org/?probe=1f73771d4d) | Jun 02, 2025 |
| Dell          | Latitude E5250              | Notebook    | [d78e89d8bc](https://linux-hardware.org/?probe=d78e89d8bc) | Jun 02, 2025 |
| Dell          | Latitude E5250              | Notebook    | [e1e616c675](https://linux-hardware.org/?probe=e1e616c675) | Jun 02, 2025 |
| Toshiba       | Satellite C655D             | Notebook    | [a32078a93a](https://linux-hardware.org/?probe=a32078a93a) | Jun 02, 2025 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [87ca33e404](https://linux-hardware.org/?probe=87ca33e404) | May 31, 2025 |
| HP            | Laptop 14s-dq0xxx           | Notebook    | [585fc97e17](https://linux-hardware.org/?probe=585fc97e17) | May 28, 2025 |
| Dell          | Latitude 3140               | Notebook    | [f7ff9dc774](https://linux-hardware.org/?probe=f7ff9dc774) | May 19, 2025 |
| Dell          | 0FF3FN A00                  | Desktop     | [617b7a067a](https://linux-hardware.org/?probe=617b7a067a) | May 16, 2025 |
| Unknown       | Unknown                     | Desktop     | [a0e5e98e1f](https://linux-hardware.org/?probe=a0e5e98e1f) | May 14, 2025 |
| HP            | Pavilion g6                 | Notebook    | [219f699b2b](https://linux-hardware.org/?probe=219f699b2b) | May 04, 2025 |
| Dell          | Latitude E7240              | Notebook    | [709fb17f28](https://linux-hardware.org/?probe=709fb17f28) | Apr 29, 2025 |
| Dell          | Latitude E7240              | Notebook    | [8f183dfd6e](https://linux-hardware.org/?probe=8f183dfd6e) | Apr 29, 2025 |
| Dell          | Inspiron N4050              | Notebook    | [50ef56e888](https://linux-hardware.org/?probe=50ef56e888) | Apr 20, 2025 |
| Acer          | Veriton X4110G              | Desktop     | [397841983c](https://linux-hardware.org/?probe=397841983c) | Apr 18, 2025 |
| Sony          | VAIO                        | All in one  | [0da2138b45](https://linux-hardware.org/?probe=0da2138b45) | Apr 11, 2025 |
| Sony          | VAIO                        | All in one  | [b5db2de07d](https://linux-hardware.org/?probe=b5db2de07d) | Apr 11, 2025 |
| HP            | Compaq 15                   | Notebook    | [84ddb2a884](https://linux-hardware.org/?probe=84ddb2a884) | Apr 11, 2025 |
| Sony          | VGNFW468J/B                 | Notebook    | [c0d51ba059](https://linux-hardware.org/?probe=c0d51ba059) | Apr 10, 2025 |
| HP            | Compaq 15                   | Notebook    | [612fc4b67c](https://linux-hardware.org/?probe=612fc4b67c) | Apr 09, 2025 |
| Dell          | Latitude E6220              | Notebook    | [1c3ec272a9](https://linux-hardware.org/?probe=1c3ec272a9) | Apr 01, 2025 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [c769caad0e](https://linux-hardware.org/?probe=c769caad0e) | Mar 12, 2025 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [163a270e2e](https://linux-hardware.org/?probe=163a270e2e) | Feb 21, 2025 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [8f2da6b759](https://linux-hardware.org/?probe=8f2da6b759) | Feb 15, 2025 |
| Acer          | Aspire V5-571PG             | Notebook    | [e30b0b990d](https://linux-hardware.org/?probe=e30b0b990d) | Feb 01, 2025 |
| HP            | Pro Tabley 610 G1           | Notebook    | [93a3240615](https://linux-hardware.org/?probe=93a3240615) | Feb 01, 2025 |
| I-Life Dig... | ZED AIR PRO                 | Notebook    | [452f7db032](https://linux-hardware.org/?probe=452f7db032) | Jan 26, 2025 |
| Acer          | Spin SP111-31               | Convertible | [4d1698df3c](https://linux-hardware.org/?probe=4d1698df3c) | Jan 22, 2025 |
| Gigabyte      | B650 GAMING X AX V2         | Desktop     | [f600e5a8a1](https://linux-hardware.org/?probe=f600e5a8a1) | Jan 19, 2025 |
| Acer          | Aspire A315-53              | Notebook    | [39534d4985](https://linux-hardware.org/?probe=39534d4985) | Jan 07, 2025 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [60d8cda1ee](https://linux-hardware.org/?probe=60d8cda1ee) | Jan 02, 2025 |
| Dell          | 033FF6 A00                  | Desktop     | [d8f0132e52](https://linux-hardware.org/?probe=d8f0132e52) | Jan 01, 2025 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0bc7f79026](https://linux-hardware.org/?probe=0bc7f79026) | Dec 16, 2024 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [1193f44f20](https://linux-hardware.org/?probe=1193f44f20) | Dec 08, 2024 |
| Acer          | TravelMate 8372             | Notebook    | [fb1751719f](https://linux-hardware.org/?probe=fb1751719f) | Nov 30, 2024 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [8b9610f096](https://linux-hardware.org/?probe=8b9610f096) | Nov 23, 2024 |
| ASUSTek       | 1008P                       | Notebook    | [6484520857](https://linux-hardware.org/?probe=6484520857) | Oct 31, 2024 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [3c2cfc5412](https://linux-hardware.org/?probe=3c2cfc5412) | Oct 28, 2024 |
| Google        | Droid                       | Notebook    | [4879fa61ce](https://linux-hardware.org/?probe=4879fa61ce) | Oct 23, 2024 |
| ASRock        | B550M-ITX/ac                | Desktop     | [61f9e31812](https://linux-hardware.org/?probe=61f9e31812) | Sep 30, 2024 |
| CSL-Comput... | C15 5500U                   | Notebook    | [98b09fe8bb](https://linux-hardware.org/?probe=98b09fe8bb) | Sep 30, 2024 |
| ASRock        | B550M-ITX/ac                | Desktop     | [6d7efba0bf](https://linux-hardware.org/?probe=6d7efba0bf) | Sep 29, 2024 |
| CSL-Comput... | C15 5500U                   | Notebook    | [008e0d5421](https://linux-hardware.org/?probe=008e0d5421) | Sep 16, 2024 |
| Dell          | Latitude 5400               | Notebook    | [ee7fe19f16](https://linux-hardware.org/?probe=ee7fe19f16) | Aug 26, 2024 |
| HP            | Notebook                    | Notebook    | [8330d22ee5](https://linux-hardware.org/?probe=8330d22ee5) | Aug 23, 2024 |
| ASRock        | 970A-G                      | Desktop     | [6d383b267d](https://linux-hardware.org/?probe=6d383b267d) | Aug 08, 2024 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [49665d68a3](https://linux-hardware.org/?probe=49665d68a3) | Aug 05, 2024 |
| Acer          | Aspire A315-53              | Notebook    | [c20748d891](https://linux-hardware.org/?probe=c20748d891) | Jul 29, 2024 |
| Acer          | ERC410M                     | Desktop     | [cdc03ce164](https://linux-hardware.org/?probe=cdc03ce164) | Jul 18, 2024 |
| HP            | 2B34                        | Desktop     | [9ee5932126](https://linux-hardware.org/?probe=9ee5932126) | Jul 13, 2024 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [4833f5a1a9](https://linux-hardware.org/?probe=4833f5a1a9) | Jul 12, 2024 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [d707b04e42](https://linux-hardware.org/?probe=d707b04e42) | Jul 12, 2024 |
| Gigabyte      | Z690 AERO G DDR4            | Desktop     | [3ada57e9c6](https://linux-hardware.org/?probe=3ada57e9c6) | Jul 12, 2024 |
| Gigabyte      | MZBAYAP-00                  | Desktop     | [cd1e4598f1](https://linux-hardware.org/?probe=cd1e4598f1) | Jul 05, 2024 |
| Acer          | Aspire E5-573G              | Notebook    | [81a22d43ad](https://linux-hardware.org/?probe=81a22d43ad) | Jun 09, 2024 |
| HP            | 18E7                        | Desktop     | [b1e0cff114](https://linux-hardware.org/?probe=b1e0cff114) | Jun 02, 2024 |
| Acer          | Aspire C22-963              | All in one  | [db7dfe3ac4](https://linux-hardware.org/?probe=db7dfe3ac4) | May 21, 2024 |
| Compal        | JHL90 REFERENCE             | Notebook    | [c477434d4e](https://linux-hardware.org/?probe=c477434d4e) | May 09, 2024 |
| ASUSTek       | M4A88T-I DELUXE             | Desktop     | [98c3cc204a](https://linux-hardware.org/?probe=98c3cc204a) | May 04, 2024 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [99f91f2965](https://linux-hardware.org/?probe=99f91f2965) | May 04, 2024 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [519d12ee29](https://linux-hardware.org/?probe=519d12ee29) | May 04, 2024 |
| ASRock        | Wolfdale1333-D667           | Desktop     | [15e7baeeb3](https://linux-hardware.org/?probe=15e7baeeb3) | May 03, 2024 |
| Dell          | Latitude D630               | Notebook    | [c9ae85eecc](https://linux-hardware.org/?probe=c9ae85eecc) | Apr 30, 2024 |
| Acer          | Aspire 7750G                | Notebook    | [961d70c1de](https://linux-hardware.org/?probe=961d70c1de) | Apr 27, 2024 |
| Dell          | Latitude D630               | Notebook    | [f59eb192f4](https://linux-hardware.org/?probe=f59eb192f4) | Apr 03, 2024 |
| Google        | Celes                       | Notebook    | [996befe940](https://linux-hardware.org/?probe=996befe940) | Mar 13, 2024 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [37172a9059](https://linux-hardware.org/?probe=37172a9059) | Mar 02, 2024 |
| Lenovo        | G40-45 80E1                 | Notebook    | [df12996678](https://linux-hardware.org/?probe=df12996678) | Feb 25, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [eaca048668](https://linux-hardware.org/?probe=eaca048668) | Feb 24, 2024 |
| Acer          | Aspire A315-24P             | Notebook    | [9925fee177](https://linux-hardware.org/?probe=9925fee177) | Feb 23, 2024 |
| Acer          | Aspire A315-24P             | Notebook    | [b76bdbcd5d](https://linux-hardware.org/?probe=b76bdbcd5d) | Feb 18, 2024 |
| Acer          | Aspire A315-24P             | Notebook    | [4abd6b79ce](https://linux-hardware.org/?probe=4abd6b79ce) | Feb 17, 2024 |
| ASUSTek       | Berkeley                    | Desktop     | [0192b193c3](https://linux-hardware.org/?probe=0192b193c3) | Feb 14, 2024 |
| Lenovo        | ThinkPad T430s 2356H83      | Notebook    | [7ee978c5e1](https://linux-hardware.org/?probe=7ee978c5e1) | Feb 08, 2024 |
| Lenovo        | G460 20041                  | Notebook    | [becc9c140b](https://linux-hardware.org/?probe=becc9c140b) | Jan 21, 2024 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [92f943771a](https://linux-hardware.org/?probe=92f943771a) | Jan 19, 2024 |
| ASRock        | J4125B-ITX                  | Desktop     | [663e605574](https://linux-hardware.org/?probe=663e605574) | Jan 17, 2024 |
| ASRock        | J4105M                      | Desktop     | [2e5352f371](https://linux-hardware.org/?probe=2e5352f371) | Jan 16, 2024 |
| Acer          | Aspire 7750G                | Notebook    | [cdbe6b267f](https://linux-hardware.org/?probe=cdbe6b267f) | Dec 19, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [6fc9570e4f](https://linux-hardware.org/?probe=6fc9570e4f) | Dec 19, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [54e52154d1](https://linux-hardware.org/?probe=54e52154d1) | Dec 07, 2023 |
| HP            | 81BB                        | All in one  | [38a445e315](https://linux-hardware.org/?probe=38a445e315) | Dec 04, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [c4949cf710](https://linux-hardware.org/?probe=c4949cf710) | Nov 28, 2023 |
| Medion        | E3223                       | Convertible | [7fd5d80169](https://linux-hardware.org/?probe=7fd5d80169) | Nov 20, 2023 |
| HP            | 81BB                        | All in one  | [a79e0b8d25](https://linux-hardware.org/?probe=a79e0b8d25) | Nov 15, 2023 |
| ASRock        | J3455M                      | Desktop     | [6a3463b7e9](https://linux-hardware.org/?probe=6a3463b7e9) | Nov 15, 2023 |
| Sony          | VGN-SZ750N                  | Notebook    | [aa0a3e3559](https://linux-hardware.org/?probe=aa0a3e3559) | Nov 13, 2023 |
| HP            | 3646h                       | Desktop     | [1cfad160f4](https://linux-hardware.org/?probe=1cfad160f4) | Nov 12, 2023 |
| Intel         | Jasper Lake Client Platf... | Notebook    | [75a2534386](https://linux-hardware.org/?probe=75a2534386) | Nov 07, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [e7d16a3fc2](https://linux-hardware.org/?probe=e7d16a3fc2) | Nov 03, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [639a14d08d](https://linux-hardware.org/?probe=639a14d08d) | Nov 01, 2023 |
| Compaq(Int... | Michelangelo(LT1504)        | Notebook    | [678614e123](https://linux-hardware.org/?probe=678614e123) | Oct 27, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [97e8dc04f5](https://linux-hardware.org/?probe=97e8dc04f5) | Oct 13, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [2e48163fbd](https://linux-hardware.org/?probe=2e48163fbd) | Oct 06, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [651a8f8f97](https://linux-hardware.org/?probe=651a8f8f97) | Oct 05, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [12331db1c1](https://linux-hardware.org/?probe=12331db1c1) | Oct 03, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [6c2de2dfb8](https://linux-hardware.org/?probe=6c2de2dfb8) | Sep 21, 2023 |
| Lenovo        | ThinkPad A475 20KMS08300    | Notebook    | [5f99185bbb](https://linux-hardware.org/?probe=5f99185bbb) | Sep 17, 2023 |
| Toshiba       | Satellite P305              | Notebook    | [d5ac020866](https://linux-hardware.org/?probe=d5ac020866) | Sep 15, 2023 |
| Lenovo        | ThinkPad A475 20KMS08300    | Notebook    | [eaaac22962](https://linux-hardware.org/?probe=eaaac22962) | Sep 15, 2023 |
| Gigabyte      | H510M S2H                   | Desktop     | [75eb2afaca](https://linux-hardware.org/?probe=75eb2afaca) | Sep 09, 2023 |
| Toshiba       | Satellite C850-C1S          | Notebook    | [ce5643add2](https://linux-hardware.org/?probe=ce5643add2) | Sep 09, 2023 |
| ASUSTek       | A8N32-SLI-Deluxe            | Desktop     | [26c288c533](https://linux-hardware.org/?probe=26c288c533) | Aug 30, 2023 |
| Lenovo        | ThinkPad T430s 2356H83      | Notebook    | [d623d73283](https://linux-hardware.org/?probe=d623d73283) | Aug 28, 2023 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | Notebook    | [546610fecb](https://linux-hardware.org/?probe=546610fecb) | Aug 20, 2023 |
| Dell          | Latitude E7240              | Notebook    | [87a0310cf0](https://linux-hardware.org/?probe=87a0310cf0) | Aug 02, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [41ad8c7fc0](https://linux-hardware.org/?probe=41ad8c7fc0) | Jul 26, 2023 |
| ASUSTek       | X502CA                      | Notebook    | [a2f77869ad](https://linux-hardware.org/?probe=a2f77869ad) | Jul 14, 2023 |
| Medion        | Akoya E6418 MD99620         | Notebook    | [7416e91f77](https://linux-hardware.org/?probe=7416e91f77) | Jul 14, 2023 |
| Dell          | 0GN4PW A00                  | Desktop     | [8380b94e4f](https://linux-hardware.org/?probe=8380b94e4f) | Jul 06, 2023 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [8a66b6d6b6](https://linux-hardware.org/?probe=8a66b6d6b6) | Jul 03, 2023 |
| Lenovo        | IdeaPad 310S-14AST 80UL     | Notebook    | [f897f42089](https://linux-hardware.org/?probe=f897f42089) | Jul 03, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [892229f999](https://linux-hardware.org/?probe=892229f999) | Jun 28, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [6d470794e9](https://linux-hardware.org/?probe=6d470794e9) | Jun 28, 2023 |
| Lenovo        | 3740 NOK                    | Desktop     | [dff301aade](https://linux-hardware.org/?probe=dff301aade) | Jun 25, 2023 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [b36de255fe](https://linux-hardware.org/?probe=b36de255fe) | Jun 22, 2023 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [f8f4049a95](https://linux-hardware.org/?probe=f8f4049a95) | Jun 22, 2023 |
| AMI           | Intel                       | Desktop     | [72c570c2fa](https://linux-hardware.org/?probe=72c570c2fa) | Jun 14, 2023 |
| MSI           | H110M PRO-VH                | Desktop     | [d22b8a57cf](https://linux-hardware.org/?probe=d22b8a57cf) | Jun 13, 2023 |
| Dell          | Latitude E6420              | Notebook    | [e86a159ec5](https://linux-hardware.org/?probe=e86a159ec5) | Jun 03, 2023 |
| Dell          | Latitude E6420              | Notebook    | [01cd20c83d](https://linux-hardware.org/?probe=01cd20c83d) | Jun 03, 2023 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [b160fbf41e](https://linux-hardware.org/?probe=b160fbf41e) | May 21, 2023 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [cc90a5ca05](https://linux-hardware.org/?probe=cc90a5ca05) | May 21, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [72adb50172](https://linux-hardware.org/?probe=72adb50172) | May 20, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [50e85498e7](https://linux-hardware.org/?probe=50e85498e7) | May 20, 2023 |
| Lenovo        | ThinkPad X240 20AMS1J100    | Notebook    | [86edc6c6d6](https://linux-hardware.org/?probe=86edc6c6d6) | May 11, 2023 |
| American M... | IPPBT-RO                    | All in one  | [ea620e0681](https://linux-hardware.org/?probe=ea620e0681) | May 04, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [b77341d8f0](https://linux-hardware.org/?probe=b77341d8f0) | May 01, 2023 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | Desktop     | [b971501e28](https://linux-hardware.org/?probe=b971501e28) | May 01, 2023 |
| Apple         | MacBookAir4,1               | Notebook    | [87ab055a31](https://linux-hardware.org/?probe=87ab055a31) | Apr 27, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [c5c1b213f2](https://linux-hardware.org/?probe=c5c1b213f2) | Apr 16, 2023 |
| Lenovo        | Yoga C740 81TC              | Convertible | [087e19943f](https://linux-hardware.org/?probe=087e19943f) | Apr 11, 2023 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [cf325779ee](https://linux-hardware.org/?probe=cf325779ee) | Apr 08, 2023 |
| Lenovo        | IdeaPad 330S-15AST 81F9     | Notebook    | [d79463ea93](https://linux-hardware.org/?probe=d79463ea93) | Apr 04, 2023 |
| Toshiba       | QOSMIO X70-B                | Notebook    | [8d94a6c8e7](https://linux-hardware.org/?probe=8d94a6c8e7) | Mar 28, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [06ad8714ea](https://linux-hardware.org/?probe=06ad8714ea) | Mar 22, 2023 |
| HP            | 0AE4h C                     | Desktop     | [fe2502088a](https://linux-hardware.org/?probe=fe2502088a) | Mar 21, 2023 |
| HP            | 0AE4h C                     | Desktop     | [71bdbbb36f](https://linux-hardware.org/?probe=71bdbbb36f) | Mar 19, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [16b1b61892](https://linux-hardware.org/?probe=16b1b61892) | Mar 17, 2023 |
| Lenovo        | ThinkPad A475 20KMS08300    | Notebook    | [b42df5cbe0](https://linux-hardware.org/?probe=b42df5cbe0) | Mar 11, 2023 |
| Lenovo        | ThinkPad A475 20KMS08300    | Notebook    | [17a3030488](https://linux-hardware.org/?probe=17a3030488) | Mar 11, 2023 |
| Gateway       | Sonic-C                     | Notebook    | [b9f775b14e](https://linux-hardware.org/?probe=b9f775b14e) | Feb 28, 2023 |
| Gateway       | Sonic-C                     | Notebook    | [6def275f9b](https://linux-hardware.org/?probe=6def275f9b) | Feb 26, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [199c8805ee](https://linux-hardware.org/?probe=199c8805ee) | Feb 10, 2023 |
| HP            | 240 G3                      | Notebook    | [a977b66ced](https://linux-hardware.org/?probe=a977b66ced) | Feb 02, 2023 |
| HP            | 240 G3                      | Notebook    | [816a3f4b28](https://linux-hardware.org/?probe=816a3f4b28) | Feb 02, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [cad4d19ab7](https://linux-hardware.org/?probe=cad4d19ab7) | Feb 02, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [4762c2a35b](https://linux-hardware.org/?probe=4762c2a35b) | Jan 31, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [b8891cfc9b](https://linux-hardware.org/?probe=b8891cfc9b) | Jan 27, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [fb0a23c0e6](https://linux-hardware.org/?probe=fb0a23c0e6) | Jan 27, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [24b6a47ebb](https://linux-hardware.org/?probe=24b6a47ebb) | Jan 27, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [b0289f0ef8](https://linux-hardware.org/?probe=b0289f0ef8) | Jan 22, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [adbc469f95](https://linux-hardware.org/?probe=adbc469f95) | Jan 22, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [9249ff32b3](https://linux-hardware.org/?probe=9249ff32b3) | Jan 22, 2023 |
| HP            | Stream Notebook PC 13       | Notebook    | [b31d60976b](https://linux-hardware.org/?probe=b31d60976b) | Jan 14, 2023 |
| ASUSTek       | M4N72-E                     | Desktop     | [1902350147](https://linux-hardware.org/?probe=1902350147) | Dec 28, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [eb42b5e055](https://linux-hardware.org/?probe=eb42b5e055) | Dec 24, 2022 |
| Pegatron      | 2ACB                        | Desktop     | [f77ff3b9b5](https://linux-hardware.org/?probe=f77ff3b9b5) | Dec 19, 2022 |
| Pegatron      | H36FF                       | Notebook    | [f27fc61f18](https://linux-hardware.org/?probe=f27fc61f18) | Dec 18, 2022 |
| Thomson       | PT-NEO14A.2WH32             | Notebook    | [d028ff11a9](https://linux-hardware.org/?probe=d028ff11a9) | Dec 18, 2022 |
| Pegatron      | H36FF                       | Notebook    | [692955be3d](https://linux-hardware.org/?probe=692955be3d) | Dec 18, 2022 |
| Braview       | BRW-BSWI-D2                 | Desktop     | [1568a74103](https://linux-hardware.org/?probe=1568a74103) | Dec 11, 2022 |
| Packard Be... | MCP73VT-PM                  | Desktop     | [e2e6da1ef3](https://linux-hardware.org/?probe=e2e6da1ef3) | Nov 27, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [4916981641](https://linux-hardware.org/?probe=4916981641) | Nov 26, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [9224597686](https://linux-hardware.org/?probe=9224597686) | Oct 28, 2022 |
| UMAX          | VisionBook 12Wi 64G         | Notebook    | [9fe98911c1](https://linux-hardware.org/?probe=9fe98911c1) | Oct 27, 2022 |
| HP            | Compaq Presario CQ50        | Notebook    | [8546f55697](https://linux-hardware.org/?probe=8546f55697) | Oct 24, 2022 |
| HP            | Compaq Presario CQ50        | Notebook    | [3b1b5c18c6](https://linux-hardware.org/?probe=3b1b5c18c6) | Oct 24, 2022 |
| Acer          | Aspire 5600                 | Notebook    | [202a7e570e](https://linux-hardware.org/?probe=202a7e570e) | Oct 20, 2022 |
| MSI           | MS-N014                     | Notebook    | [4c41640fd3](https://linux-hardware.org/?probe=4c41640fd3) | Oct 12, 2022 |
| MSI           | MS-N014                     | Notebook    | [3144cac65a](https://linux-hardware.org/?probe=3144cac65a) | Oct 12, 2022 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [676289f650](https://linux-hardware.org/?probe=676289f650) | Oct 02, 2022 |
| HP            | Compaq 420                  | Notebook    | [d3e367cedc](https://linux-hardware.org/?probe=d3e367cedc) | Oct 01, 2022 |
| HP            | 1632                        | Desktop     | [f510159333](https://linux-hardware.org/?probe=f510159333) | Sep 19, 2022 |
| HP            | Presario V6000 (RG289UA#... | Notebook    | [7f0113694a](https://linux-hardware.org/?probe=7f0113694a) | Sep 15, 2022 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [1a999b09ae](https://linux-hardware.org/?probe=1a999b09ae) | Sep 12, 2022 |
| HP            | 1632                        | Desktop     | [f14389b9dd](https://linux-hardware.org/?probe=f14389b9dd) | Sep 10, 2022 |
| Samsung       | X420/X520                   | Notebook    | [a8ca7bb005](https://linux-hardware.org/?probe=a8ca7bb005) | Sep 04, 2022 |
| Fujitsu       | FMVNQ8P6                    | Notebook    | [5e34698f14](https://linux-hardware.org/?probe=5e34698f14) | Aug 28, 2022 |
| Sony          | VAIO                        | All in one  | [3ed1ad79e4](https://linux-hardware.org/?probe=3ed1ad79e4) | Aug 24, 2022 |
| ASUSTek       | UX303LN                     | Notebook    | [63d5525864](https://linux-hardware.org/?probe=63d5525864) | Aug 16, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [86523f9a5f](https://linux-hardware.org/?probe=86523f9a5f) | Aug 11, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMC    | Notebook    | [47d4f751e1](https://linux-hardware.org/?probe=47d4f751e1) | Aug 09, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [ede7f6cdae](https://linux-hardware.org/?probe=ede7f6cdae) | Jul 23, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [b846c98a96](https://linux-hardware.org/?probe=b846c98a96) | Jul 08, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [fd0a9ef1c8](https://linux-hardware.org/?probe=fd0a9ef1c8) | Jul 08, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [cc2f84d5d3](https://linux-hardware.org/?probe=cc2f84d5d3) | Jul 08, 2022 |
| HP            | Pavilion g4                 | Notebook    | [330078dbac](https://linux-hardware.org/?probe=330078dbac) | Jul 04, 2022 |
| ASUSTek       | X555YI                      | Notebook    | [762b96a2de](https://linux-hardware.org/?probe=762b96a2de) | Jul 02, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [4bea8264d3](https://linux-hardware.org/?probe=4bea8264d3) | Jun 20, 2022 |
| Lenovo        | 103D SDK0J40697 WIN 3305... | Desktop     | [03c6ee002e](https://linux-hardware.org/?probe=03c6ee002e) | Jun 07, 2022 |
| Samsung       | 530XBB                      | Notebook    | [485a99ca42](https://linux-hardware.org/?probe=485a99ca42) | Jun 03, 2022 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [19a5c1de8e](https://linux-hardware.org/?probe=19a5c1de8e) | May 29, 2022 |
| Minix         | Z64 V1.2                    | Notebook    | [97525a1dc3](https://linux-hardware.org/?probe=97525a1dc3) | May 27, 2022 |
| Lenovo        | Remore CRB Win8 STD MM D... | Desktop     | [eb96be3541](https://linux-hardware.org/?probe=eb96be3541) | May 24, 2022 |
| Lenovo        | Remore CRB Win8 STD MM D... | Desktop     | [f1a79871f7](https://linux-hardware.org/?probe=f1a79871f7) | May 24, 2022 |
| HP            | 3047h                       | Desktop     | [cc184c817b](https://linux-hardware.org/?probe=cc184c817b) | May 16, 2022 |
| Dell          | Inspiron 16 5620            | Notebook    | [b42e1cf95b](https://linux-hardware.org/?probe=b42e1cf95b) | May 13, 2022 |
| Minix         | Z64 V1.2                    | Notebook    | [8796deded0](https://linux-hardware.org/?probe=8796deded0) | May 12, 2022 |
| Dell          | MXG061                      | Notebook    | [119f6dd774](https://linux-hardware.org/?probe=119f6dd774) | May 09, 2022 |
| Lenovo        | ThinkCentre M91p 4518E2M    | Desktop     | [2553bf03d1](https://linux-hardware.org/?probe=2553bf03d1) | May 05, 2022 |
| Lenovo        | ThinkCentre M91p 4518E2M    | Desktop     | [03a7fc3c23](https://linux-hardware.org/?probe=03a7fc3c23) | May 05, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [ab553d3a2f](https://linux-hardware.org/?probe=ab553d3a2f) | May 01, 2022 |
| Acer          | Extensa 5220                | Notebook    | [ebbd01171d](https://linux-hardware.org/?probe=ebbd01171d) | May 01, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [f7838121d2](https://linux-hardware.org/?probe=f7838121d2) | Apr 23, 2022 |
| Acer          | Aspire 1410                 | Notebook    | [703c2ec84a](https://linux-hardware.org/?probe=703c2ec84a) | Apr 21, 2022 |
| Lenovo        | ThinkPad T400 6475E13       | Notebook    | [cd49ac8445](https://linux-hardware.org/?probe=cd49ac8445) | Apr 08, 2022 |
| Dell          | 018D1Y A00                  | Desktop     | [0c6fc3cae4](https://linux-hardware.org/?probe=0c6fc3cae4) | Apr 07, 2022 |
| Dell          | MXG061                      | Notebook    | [9c91bd9487](https://linux-hardware.org/?probe=9c91bd9487) | Apr 06, 2022 |
| HP            | 2820h                       | Desktop     | [c4461b3710](https://linux-hardware.org/?probe=c4461b3710) | Apr 04, 2022 |
| Insignia      | NS-P11W7100                 | Notebook    | [daa476af8c](https://linux-hardware.org/?probe=daa476af8c) | Mar 28, 2022 |
| Dell          | MXG071                      | Notebook    | [ac0158dcb9](https://linux-hardware.org/?probe=ac0158dcb9) | Mar 27, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [693b66ce17](https://linux-hardware.org/?probe=693b66ce17) | Mar 27, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [badb9dcc14](https://linux-hardware.org/?probe=badb9dcc14) | Mar 26, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [32115c5548](https://linux-hardware.org/?probe=32115c5548) | Mar 26, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [0f99b7ff76](https://linux-hardware.org/?probe=0f99b7ff76) | Mar 21, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [bc850554b2](https://linux-hardware.org/?probe=bc850554b2) | Mar 16, 2022 |
| Foxconn       | 2A8C                        | Desktop     | [80e5e3a26c](https://linux-hardware.org/?probe=80e5e3a26c) | Mar 15, 2022 |
| HP            | Compaq CQ45                 | Notebook    | [99286efd08](https://linux-hardware.org/?probe=99286efd08) | Mar 10, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [2b748962fa](https://linux-hardware.org/?probe=2b748962fa) | Mar 06, 2022 |
| ASUSTek       | 900                         | Notebook    | [8373f78d4e](https://linux-hardware.org/?probe=8373f78d4e) | Feb 19, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [6134bb8cba](https://linux-hardware.org/?probe=6134bb8cba) | Feb 18, 2022 |
| ABIT          | IP35-E                      | Desktop     | [67d9f7e94e](https://linux-hardware.org/?probe=67d9f7e94e) | Feb 17, 2022 |
| Acer          | Aspire 5600                 | Notebook    | [4b2259f040](https://linux-hardware.org/?probe=4b2259f040) | Feb 10, 2022 |
| Pegatron      | 2ACB                        | Desktop     | [b7987fdaa7](https://linux-hardware.org/?probe=b7987fdaa7) | Feb 10, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [b596d9fdb1](https://linux-hardware.org/?probe=b596d9fdb1) | Feb 09, 2022 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [4fe66f8af6](https://linux-hardware.org/?probe=4fe66f8af6) | Feb 09, 2022 |
| HP            | Compaq nw9440 (EY615ET#A... | Notebook    | [6a5c3254ab](https://linux-hardware.org/?probe=6a5c3254ab) | Jan 30, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [15838ae11b](https://linux-hardware.org/?probe=15838ae11b) | Jan 12, 2022 |
| ASUSTek       | N53Jf                       | Notebook    | [3f0e64b85e](https://linux-hardware.org/?probe=3f0e64b85e) | Jan 03, 2022 |
| ASUSTek       | N53Jf                       | Notebook    | [6d7b0abdfa](https://linux-hardware.org/?probe=6d7b0abdfa) | Jan 03, 2022 |
| EVGA          | X58 SLI FTW3 Tylersburg     | Desktop     | [9e4639427d](https://linux-hardware.org/?probe=9e4639427d) | Jan 03, 2022 |
| EVGA          | X58 SLI FTW3 Tylersburg     | Desktop     | [d351220ea5](https://linux-hardware.org/?probe=d351220ea5) | Jan 02, 2022 |
| EVGA          | X58 SLI FTW3 Tylersburg     | Desktop     | [b2786130fb](https://linux-hardware.org/?probe=b2786130fb) | Jan 02, 2022 |
| ASUSTek       | X541SA                      | Notebook    | [26f2eeeefc](https://linux-hardware.org/?probe=26f2eeeefc) | Dec 31, 2021 |
| HP            | Pavilion dv6500             | Notebook    | [978ee4328d](https://linux-hardware.org/?probe=978ee4328d) | Dec 19, 2021 |
| ASRock        | H61M-VG3                    | Desktop     | [392a957541](https://linux-hardware.org/?probe=392a957541) | Dec 17, 2021 |
| Acer          | Aspire 5600                 | Notebook    | [25b1e50c64](https://linux-hardware.org/?probe=25b1e50c64) | Dec 12, 2021 |
| Gigabyte      | GA-E350N                    | Desktop     | [10d55dd433](https://linux-hardware.org/?probe=10d55dd433) | Dec 02, 2021 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [64eba568a1](https://linux-hardware.org/?probe=64eba568a1) | Nov 25, 2021 |
| HP            | Compaq 2510p                | Notebook    | [8bc24dae3e](https://linux-hardware.org/?probe=8bc24dae3e) | Nov 23, 2021 |
| HP            | Compaq 2510p                | Notebook    | [c76241a894](https://linux-hardware.org/?probe=c76241a894) | Nov 22, 2021 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [b7306537cc](https://linux-hardware.org/?probe=b7306537cc) | Nov 10, 2021 |
| Acer          | Aspire 5600                 | Notebook    | [7e2da6d3e9](https://linux-hardware.org/?probe=7e2da6d3e9) | Oct 26, 2021 |
| Dell          | MXG061                      | Notebook    | [89a5b20193](https://linux-hardware.org/?probe=89a5b20193) | Oct 10, 2021 |
| Biostar       | G41D3C                      | Desktop     | [433bc7cf78](https://linux-hardware.org/?probe=433bc7cf78) | Oct 10, 2021 |
| Biostar       | G41D3C                      | Desktop     | [90dc88db01](https://linux-hardware.org/?probe=90dc88db01) | Oct 02, 2021 |
| Acer          | Swift SF314-56              | Notebook    | [263d6e38b7](https://linux-hardware.org/?probe=263d6e38b7) | Oct 01, 2021 |
| Acer          | Swift SF314-56              | Notebook    | [bb0f894bce](https://linux-hardware.org/?probe=bb0f894bce) | Oct 01, 2021 |
| ASUSTek       | M5A78L LE                   | Desktop     | [ddb041ded0](https://linux-hardware.org/?probe=ddb041ded0) | Sep 15, 2021 |
| ASUSTek       | M5A78L LE                   | Desktop     | [a9335318aa](https://linux-hardware.org/?probe=a9335318aa) | Sep 15, 2021 |
| Dell          | Vostro1710                  | Notebook    | [d50123c66a](https://linux-hardware.org/?probe=d50123c66a) | Sep 01, 2021 |
| Dell          | Inspiron 5452               | Notebook    | [0c9b3ec7a9](https://linux-hardware.org/?probe=0c9b3ec7a9) | Aug 07, 2021 |
| Intel         | DG31PR AAD97573-300         | Desktop     | [0a0a8059c2](https://linux-hardware.org/?probe=0a0a8059c2) | Aug 04, 2021 |
| Intel         | DG31PR AAD97573-300         | Desktop     | [6b7f5cdcc8](https://linux-hardware.org/?probe=6b7f5cdcc8) | Jul 21, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [b2b851f7d2](https://linux-hardware.org/?probe=b2b851f7d2) | Jul 12, 2021 |
| ASUSTek       | X541SA                      | Notebook    | [ed8bb15f60](https://linux-hardware.org/?probe=ed8bb15f60) | Jul 11, 2021 |
| HP            | 0A98h                       | Desktop     | [9844591cd4](https://linux-hardware.org/?probe=9844591cd4) | Jul 02, 2021 |
| ECS           | Livermore                   | Desktop     | [91b29dad17](https://linux-hardware.org/?probe=91b29dad17) | Jun 23, 2021 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [5943266aca](https://linux-hardware.org/?probe=5943266aca) | Jun 18, 2021 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [3b4a122b75](https://linux-hardware.org/?probe=3b4a122b75) | Jun 18, 2021 |
| Fujitsu       | LIFEBOOK U747               | Notebook    | [117e8bf660](https://linux-hardware.org/?probe=117e8bf660) | Jun 17, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [a9255b2217](https://linux-hardware.org/?probe=a9255b2217) | Jun 04, 2021 |
| MSI           | Boston                      | Desktop     | [5cca21c281](https://linux-hardware.org/?probe=5cca21c281) | Apr 26, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop E203... | Notebook    | [58bf661e8d](https://linux-hardware.org/?probe=58bf661e8d) | Apr 15, 2021 |
| ASUSTek       | K50IE                       | Notebook    | [b0bcc6c31c](https://linux-hardware.org/?probe=b0bcc6c31c) | Apr 12, 2021 |
| MSI           | B75A-G43                    | Desktop     | [87a3e8d42c](https://linux-hardware.org/?probe=87a3e8d42c) | Apr 07, 2021 |
| AWOW          | PC BOX                      | Mini pc     | [b9140b8786](https://linux-hardware.org/?probe=b9140b8786) | Mar 29, 2021 |
| ASUSTek       | K54LY                       | Notebook    | [dc7d86f51e](https://linux-hardware.org/?probe=dc7d86f51e) | Mar 21, 2021 |
| Acer          | Aspire V5-552               | Notebook    | [7a32a8a1c3](https://linux-hardware.org/?probe=7a32a8a1c3) | Mar 03, 2021 |
| HP            | Compaq 6735b                | Notebook    | [0f2afbc99a](https://linux-hardware.org/?probe=0f2afbc99a) | Feb 18, 2021 |
| Dell          | Inspiron 7559               | Notebook    | [4d4377253f](https://linux-hardware.org/?probe=4d4377253f) | Feb 15, 2021 |
| HP            | Laptop 17-by2xxx            | Notebook    | [729abf0085](https://linux-hardware.org/?probe=729abf0085) | Jan 30, 2021 |
| Acer          | Predator PH317-52           | Notebook    | [1bd05ad341](https://linux-hardware.org/?probe=1bd05ad341) | Jan 24, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [84cb4ded95](https://linux-hardware.org/?probe=84cb4ded95) | Dec 30, 2020 |
| HP            | 655                         | Notebook    | [a6913cacf3](https://linux-hardware.org/?probe=a6913cacf3) | Dec 28, 2020 |
| HP            | 655                         | Notebook    | [2a4c81218e](https://linux-hardware.org/?probe=2a4c81218e) | Dec 27, 2020 |
| Toshiba       | Satellite T215D             | Notebook    | [084f254e1f](https://linux-hardware.org/?probe=084f254e1f) | Dec 23, 2020 |
| Toshiba       | Satellite T215D             | Notebook    | [bdb8fe4e55](https://linux-hardware.org/?probe=bdb8fe4e55) | Dec 23, 2020 |
| Minix         | NEO Z83-4 V1.1              | Desktop     | [19e83c7c24](https://linux-hardware.org/?probe=19e83c7c24) | Dec 21, 2020 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [77f93a017c](https://linux-hardware.org/?probe=77f93a017c) | Dec 21, 2020 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [a6654cf4f1](https://linux-hardware.org/?probe=a6654cf4f1) | Dec 21, 2020 |
| Minix         | NEO Z83-4 V1.1              | Desktop     | [8f8f606051](https://linux-hardware.org/?probe=8f8f606051) | Dec 16, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [680d4771b2](https://linux-hardware.org/?probe=680d4771b2) | Dec 15, 2020 |
| ASUSTek       | 1001PX                      | Notebook    | [9f911bde1c](https://linux-hardware.org/?probe=9f911bde1c) | Dec 11, 2020 |
| Acer          | Aspire 5750                 | Notebook    | [ba47872fd5](https://linux-hardware.org/?probe=ba47872fd5) | Dec 02, 2020 |
| Acer          | Aspire 5750                 | Notebook    | [c4216f5d80](https://linux-hardware.org/?probe=c4216f5d80) | Dec 02, 2020 |
| HP            | 0ACCh                       | Desktop     | [7f4d2a2df4](https://linux-hardware.org/?probe=7f4d2a2df4) | Nov 23, 2020 |
| HP            | 0ACCh                       | Desktop     | [d28f3f3195](https://linux-hardware.org/?probe=d28f3f3195) | Nov 23, 2020 |
| Lenovo        | ThinkCentre M91p 4524RS6    | Desktop     | [cf9c213443](https://linux-hardware.org/?probe=cf9c213443) | Nov 21, 2020 |
| Lenovo        | ThinkCentre M91p 4524RS6    | Desktop     | [66d1757c3f](https://linux-hardware.org/?probe=66d1757c3f) | Nov 21, 2020 |
| HP            | 3032h                       | Desktop     | [1a10cb8912](https://linux-hardware.org/?probe=1a10cb8912) | Nov 20, 2020 |
| Intel         | H61M-S1                     | Desktop     | [f31ad89e75](https://linux-hardware.org/?probe=f31ad89e75) | Nov 02, 2020 |
| Intel         | H61M-S1                     | Desktop     | [f381b5e487](https://linux-hardware.org/?probe=f381b5e487) | Nov 02, 2020 |
| Lenovo        | ThinkCentre A55 9265BL7     | Desktop     | [1e00064286](https://linux-hardware.org/?probe=1e00064286) | Oct 30, 2020 |
| HP            | 2AA6 PVT                    | Desktop     | [3ee3ed2e83](https://linux-hardware.org/?probe=3ee3ed2e83) | Oct 06, 2020 |
| Dell          | Latitude D530               | Notebook    | [4fe18e86ac](https://linux-hardware.org/?probe=4fe18e86ac) | Sep 27, 2020 |
| MSI           | Z77A-G43                    | Desktop     | [4420c076a7](https://linux-hardware.org/?probe=4420c076a7) | Sep 03, 2020 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [2a6ae45bc4](https://linux-hardware.org/?probe=2a6ae45bc4) | Aug 20, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [a20482ea67](https://linux-hardware.org/?probe=a20482ea67) | Aug 12, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [cb782efc58](https://linux-hardware.org/?probe=cb782efc58) | Aug 07, 2020 |
| Jetway        | I61MG4                      | Desktop     | [f677e427be](https://linux-hardware.org/?probe=f677e427be) | Jul 30, 2020 |
| Jetway        | I61MG4                      | Desktop     | [2e5f79f476](https://linux-hardware.org/?probe=2e5f79f476) | Jul 29, 2020 |
| Lenovo        | MIIX 300-10IBY 80NR         | Tablet      | [cf8c7c6ae6](https://linux-hardware.org/?probe=cf8c7c6ae6) | Jul 29, 2020 |
| Acer          | Aspire ES1-511              | Notebook    | [63a7ae1967](https://linux-hardware.org/?probe=63a7ae1967) | Jul 24, 2020 |
| Google        | Chell                       | Notebook    | [cf727e9a6e](https://linux-hardware.org/?probe=cf727e9a6e) | Jul 23, 2020 |
| ASUSTek       | X751LD                      | Notebook    | [2d9ea757d1](https://linux-hardware.org/?probe=2d9ea757d1) | Jul 14, 2020 |
| ASUSTek       | X751LD                      | Notebook    | [1a4ee704d9](https://linux-hardware.org/?probe=1a4ee704d9) | Jul 14, 2020 |
| Lenovo        | 3000 V200 0764A11           | Notebook    | [8492023ae0](https://linux-hardware.org/?probe=8492023ae0) | Jul 13, 2020 |
| TR            | ST Pro-KN                   | Notebook    | [e78b2937ef](https://linux-hardware.org/?probe=e78b2937ef) | Jul 01, 2020 |
| Acer          | EQ35M                       | Desktop     | [f2dbd9e441](https://linux-hardware.org/?probe=f2dbd9e441) | Jun 23, 2020 |
| Acer          | EQ35M                       | Desktop     | [5ebf9a4f1a](https://linux-hardware.org/?probe=5ebf9a4f1a) | Jun 23, 2020 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | Desktop     | [89182244dc](https://linux-hardware.org/?probe=89182244dc) | Jun 12, 2020 |
| ASUSTek       | N750JK                      | Notebook    | [9102fbcf41](https://linux-hardware.org/?probe=9102fbcf41) | Jun 02, 2020 |
| Samsung       | NC110P/NC108P/NC111P        | Notebook    | [92c219ffb4](https://linux-hardware.org/?probe=92c219ffb4) | May 14, 2020 |
| ASUSTek       | X540YA                      | Notebook    | [2bfdde7714](https://linux-hardware.org/?probe=2bfdde7714) | Apr 03, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Linux Lite 6.6 | 35        | 13.89%  |
| Linux Lite 5.8 | 27        | 10.71%  |
| Linux Lite 6.4 | 25        | 9.92%   |
| Linux Lite 5.4 | 20        | 7.94%   |
| Linux Lite 6.0 | 19        | 7.54%   |
| Linux Lite 5.0 | 18        | 7.14%   |
| Linux Lite 5.2 | 17        | 6.75%   |
| Linux Lite 7.4 | 16        | 6.35%   |
| Linux Lite 6.2 | 16        | 6.35%   |
| Linux Lite 5.6 | 16        | 6.35%   |
| Linux Lite 7.0 | 13        | 5.16%   |
| Linux Lite 7.2 | 10        | 3.97%   |
| Linux Lite 7.6 | 9         | 3.57%   |
| Linux Lite 3.8 | 6         | 2.38%   |
| Linux Lite 4.8 | 2         | 0.79%   |
| Linux Lite 4.6 | 1         | 0.4%    |
| Linux Lite 4.4 | 1         | 0.4%    |
| Linux Lite 4.2 | 1         | 0.4%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Linux Lite | 245       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.0-69-generic | 10        | 3.79%   |
| 5.15.0-82-generic | 7         | 2.65%   |
| 6.8.0-56-generic  | 6         | 2.27%   |
| 5.4.0-70-generic  | 6         | 2.27%   |
| 5.4.0-42-generic  | 6         | 2.27%   |
| 5.15.0-91-generic | 6         | 2.27%   |
| 5.4.0-91-generic  | 5         | 1.89%   |
| 5.15.0-76-generic | 5         | 1.89%   |
| 6.8.0-60-generic  | 4         | 1.52%   |
| 6.8.0-47-generic  | 4         | 1.52%   |
| 5.4.0-96-generic  | 4         | 1.52%   |
| 5.4.0-52-generic  | 4         | 1.52%   |
| 5.4.0-40-generic  | 4         | 1.52%   |
| 5.4.0-109-generic | 4         | 1.52%   |
| 5.4.0-104-generic | 4         | 1.52%   |
| 5.15.0-88-generic | 4         | 1.52%   |
| 5.15.0-71-generic | 4         | 1.52%   |
| 5.15.0-33-generic | 4         | 1.52%   |
| 6.8.0-57-generic  | 3         | 1.14%   |
| 6.8.0-51-generic  | 3         | 1.14%   |
| 6.8.0-38-generic  | 3         | 1.14%   |
| 5.4.0-81-generic  | 3         | 1.14%   |
| 5.4.0-58-generic  | 3         | 1.14%   |
| 5.4.0-48-generic  | 3         | 1.14%   |
| 5.4.0-113-generic | 3         | 1.14%   |
| 5.4.0-107-generic | 3         | 1.14%   |
| 5.15.0-83-generic | 3         | 1.14%   |
| 5.15.0-75-generic | 3         | 1.14%   |
| 5.15.0-58-generic | 3         | 1.14%   |
| 5.15.0-52-generic | 3         | 1.14%   |
| 5.15.0-47-generic | 3         | 1.14%   |
| 5.15.0-46-generic | 3         | 1.14%   |
| 4.4.0-112-generic | 3         | 1.14%   |
| 6.8.0-87-generic  | 2         | 0.76%   |
| 6.8.0-85-generic  | 2         | 0.76%   |
| 6.8.0-78-generic  | 2         | 0.76%   |
| 6.8.0-59-generic  | 2         | 0.76%   |
| 6.8.0-39-generic  | 2         | 0.76%   |
| 5.4.0-90-generic  | 2         | 0.76%   |
| 5.4.0-88-generic  | 2         | 0.76%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 91        | 36.25%  |
| 5.4.0   | 90        | 35.86%  |
| 6.8.0   | 46        | 18.33%  |
| 4.4.0   | 5         | 1.99%   |
| 4.15.0  | 5         | 1.99%   |
| 5.13.0  | 3         | 1.2%    |
| 6.0.0   | 2         | 0.8%    |
| 6.5.0   | 1         | 0.4%    |
| 6.4.0   | 1         | 0.4%    |
| 6.17.0  | 1         | 0.4%    |
| 6.1.0   | 1         | 0.4%    |
| 5.9.0   | 1         | 0.4%    |
| 5.19.0  | 1         | 0.4%    |
| 5.16.9  | 1         | 0.4%    |
| 5.16.0  | 1         | 0.4%    |
| 5.10.0  | 1         | 0.4%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 91        | 36.25%  |
| 5.4     | 90        | 35.86%  |
| 6.8     | 46        | 18.33%  |
| 4.4     | 5         | 1.99%   |
| 4.15    | 5         | 1.99%   |
| 5.13    | 3         | 1.2%    |
| 6.0     | 2         | 0.8%    |
| 5.16    | 2         | 0.8%    |
| 6.5     | 1         | 0.4%    |
| 6.4     | 1         | 0.4%    |
| 6.17    | 1         | 0.4%    |
| 6.1     | 1         | 0.4%    |
| 5.9     | 1         | 0.4%    |
| 5.19    | 1         | 0.4%    |
| 5.10    | 1         | 0.4%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 240       | 97.96%  |
| i686   | 5         | 2.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| XFCE       | 210       | 85.71%  |
| GNOME      | 30        | 12.24%  |
| Unknown    | 2         | 0.82%   |
| X-Cinnamon | 1         | 0.41%   |
| Deepin     | 1         | 0.41%   |
| Budgie     | 1         | 0.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 240       | 97.96%  |
| Wayland | 2         | 0.82%   |
| Tty     | 2         | 0.82%   |
| Unknown | 1         | 0.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 174       | 70.45%  |
| Unknown | 42        | 17%     |
| TDM     | 28        | 11.34%  |
| GDM3    | 2         | 0.81%   |
| GDM     | 1         | 0.4%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 129       | 52.65%  |
| de_DE | 17        | 6.94%   |
| pt_BR | 11        | 4.49%   |
| en_GB | 11        | 4.49%   |
| es_ES | 9         | 3.67%   |
| pl_PL | 8         | 3.27%   |
| fr_FR | 8         | 3.27%   |
| it_IT | 6         | 2.45%   |
| es_MX | 5         | 2.04%   |
| en_CA | 5         | 2.04%   |
| ru_UA | 3         | 1.22%   |
| ru_RU | 3         | 1.22%   |
| pt_PT | 3         | 1.22%   |
| nl_NL | 2         | 0.82%   |
| es_CO | 2         | 0.82%   |
| en_IE | 2         | 0.82%   |
| zh_CN | 1         | 0.41%   |
| tr_TR | 1         | 0.41%   |
| th_TH | 1         | 0.41%   |
| sv_SE | 1         | 0.41%   |
| sr_RS | 1         | 0.41%   |
| sk_SK | 1         | 0.41%   |
| id_ID | 1         | 0.41%   |
| hu_HU | 1         | 0.41%   |
| fr_CA | 1         | 0.41%   |
| es_CL | 1         | 0.41%   |
| es_AR | 1         | 0.41%   |
| en_SG | 1         | 0.41%   |
| en_PH | 1         | 0.41%   |
| en_NZ | 1         | 0.41%   |
| en_IN | 1         | 0.41%   |
| en_AU | 1         | 0.41%   |
| el_GR | 1         | 0.41%   |
| da_DK | 1         | 0.41%   |
| C     | 1         | 0.41%   |
| bg_BG | 1         | 0.41%   |
| ar_SA | 1         | 0.41%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 137       | 55.69%  |
| EFI  | 109       | 44.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 205       | 83.67%  |
| Tmpfs   | 20        | 8.16%   |
| Overlay | 15        | 6.12%   |
| Zfs     | 2         | 0.82%   |
| Btrfs   | 2         | 0.82%   |
| Ext3    | 1         | 0.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 137       | 55.92%  |
| Unknown | 59        | 24.08%  |
| MBR     | 49        | 20%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 208       | 84.55%  |
| Yes       | 38        | 15.45%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 183       | 74.09%  |
| Yes       | 64        | 25.91%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 41        | 16.73%  |
| Lenovo                      | 31        | 12.65%  |
| ASUSTek Computer            | 30        | 12.24%  |
| Acer                        | 24        | 9.8%    |
| Dell                        | 22        | 8.98%   |
| Gigabyte Technology         | 13        | 5.31%   |
| ASRock                      | 9         | 3.67%   |
| Apple                       | 9         | 3.67%   |
| MSI                         | 7         | 2.86%   |
| Toshiba                     | 5         | 2.04%   |
| Sony                        | 4         | 1.63%   |
| Samsung Electronics         | 4         | 1.63%   |
| Fujitsu                     | 4         | 1.63%   |
| Pegatron                    | 3         | 1.22%   |
| Intel                       | 3         | 1.22%   |
| Google                      | 3         | 1.22%   |
| Minix                       | 2         | 0.82%   |
| Medion                      | 2         | 0.82%   |
| Inventec                    | 2         | 0.82%   |
| Fujitsu Siemens             | 2         | 0.82%   |
| Foxconn                     | 2         | 0.82%   |
| Biostar                     | 2         | 0.82%   |
| VIT                         | 1         | 0.41%   |
| UNOWHY                      | 1         | 0.41%   |
| UMAX                        | 1         | 0.41%   |
| TR                          | 1         | 0.41%   |
| Thomson                     | 1         | 0.41%   |
| Packard Bell                | 1         | 0.41%   |
| Jetway                      | 1         | 0.41%   |
| Insignia                    | 1         | 0.41%   |
| I-Life Digital Technologies | 1         | 0.41%   |
| HUAWEI                      | 1         | 0.41%   |
| Gateway                     | 1         | 0.41%   |
| EVGA                        | 1         | 0.41%   |
| CSL-Computer                | 1         | 0.41%   |
| Compaq(Intel)               | 1         | 0.41%   |
| Compal                      | 1         | 0.41%   |
| Braview                     | 1         | 0.41%   |
| AWOW                        | 1         | 0.41%   |
| AMI                         | 1         | 0.41%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| MSI MS-7758                         | 2         | 0.82%   |
| HP Notebook                         | 2         | 0.82%   |
| Dell Latitude E7240                 | 2         | 0.82%   |
| VIT P2400                           | 1         | 0.41%   |
| UNOWHY Y13G010S4EI                  | 1         | 0.41%   |
| UMAX VisionBook 12Wi 64G            | 1         | 0.41%   |
| TR ST Pro-KN                        | 1         | 0.41%   |
| Toshiba Satellite T215D             | 1         | 0.41%   |
| Toshiba Satellite P305              | 1         | 0.41%   |
| Toshiba Satellite C850-C1S          | 1         | 0.41%   |
| Toshiba Satellite C655D             | 1         | 0.41%   |
| Toshiba QOSMIO X70-B                | 1         | 0.41%   |
| Thomson PT-NEO14A.2WH32             | 1         | 0.41%   |
| Sony VPCL116FX                      | 1         | 0.41%   |
| Sony VGNFW468J/B                    | 1         | 0.41%   |
| Sony VGN-SZ750N                     | 1         | 0.41%   |
| Sony VGC-JS54FB_W                   | 1         | 0.41%   |
| Samsung X420/X520                   | 1         | 0.41%   |
| Samsung NC110P/NC108P/NC111P        | 1         | 0.41%   |
| Samsung 905S3G/906S3G/915S3G/9305SG | 1         | 0.41%   |
| Samsung 530XBB                      | 1         | 0.41%   |
| Pegatron H36FF                      | 1         | 0.41%   |
| Pegatron 520-1135la                 | 1         | 0.41%   |
| Pegatron 520-1030a                  | 1         | 0.41%   |
| Packard Bell ISTART D2314           | 1         | 0.41%   |
| MSI MS-N014                         | 1         | 0.41%   |
| MSI MS-7C95                         | 1         | 0.41%   |
| MSI MS-7996                         | 1         | 0.41%   |
| MSI MS-7592                         | 1         | 0.41%   |
| MSI FZ079AA-ABF a6625fr             | 1         | 0.41%   |
| Minix Z83-4                         | 1         | 0.41%   |
| Minix Z64                           | 1         | 0.41%   |
| Medion E3223                        | 1         | 0.41%   |
| Medion Akoya E6418 MD99620          | 1         | 0.41%   |
| Lenovo Z50-75 80EC                  | 1         | 0.41%   |
| Lenovo Yoga C740 81TC               | 1         | 0.41%   |
| Lenovo V530S-07ICR 11BM0028MZ       | 1         | 0.41%   |
| Lenovo ThinkStation P320 30BH000BFR | 1         | 0.41%   |
| Lenovo ThinkPad X240 20AMS1J100     | 1         | 0.41%   |
| Lenovo ThinkPad T440p 20AN00C6GE    | 1         | 0.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Acer Aspire             | 16        | 6.53%   |
| Lenovo IdeaPad          | 10        | 4.08%   |
| HP Compaq               | 10        | 4.08%   |
| Dell Latitude           | 9         | 3.67%   |
| HP Laptop               | 7         | 2.86%   |
| Dell Inspiron           | 7         | 2.86%   |
| Lenovo ThinkPad         | 6         | 2.45%   |
| Toshiba Satellite       | 4         | 1.63%   |
| Lenovo ThinkCentre      | 4         | 1.63%   |
| HP EliteBook            | 4         | 1.63%   |
| ASUS VivoBook           | 4         | 1.63%   |
| HP Pavilion             | 3         | 1.22%   |
| MSI MS-7758             | 2         | 0.82%   |
| Lenovo MIIX             | 2         | 0.82%   |
| Inventec Dell           | 2         | 0.82%   |
| HP Notebook             | 2         | 0.82%   |
| Fujitsu Siemens ESPRIMO | 2         | 0.82%   |
| Fujitsu LIFEBOOK        | 2         | 0.82%   |
| Dell OptiPlex           | 2         | 0.82%   |
| Acer Veriton            | 2         | 0.82%   |
| VIT P2400               | 1         | 0.41%   |
| UNOWHY Y13G010S4EI      | 1         | 0.41%   |
| UMAX VisionBook         | 1         | 0.41%   |
| TR ST                   | 1         | 0.41%   |
| Toshiba QOSMIO          | 1         | 0.41%   |
| Thomson PT-NEO14A.2WH32 | 1         | 0.41%   |
| Sony VPCL116FX          | 1         | 0.41%   |
| Sony VGNFW468J          | 1         | 0.41%   |
| Sony VGN-SZ750N         | 1         | 0.41%   |
| Sony VGC-JS54FB         | 1         | 0.41%   |
| Samsung X420            | 1         | 0.41%   |
| Samsung NC110P          | 1         | 0.41%   |
| Samsung 905S3G          | 1         | 0.41%   |
| Samsung 530XBB          | 1         | 0.41%   |
| Pegatron H36FF          | 1         | 0.41%   |
| Pegatron 520-1135la     | 1         | 0.41%   |
| Pegatron 520-1030a      | 1         | 0.41%   |
| Packard Bell ISTART     | 1         | 0.41%   |
| MSI MS-N014             | 1         | 0.41%   |
| MSI MS-7C95             | 1         | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2011 | 22        | 8.98%   |
| 2010 | 21        | 8.57%   |
| 2008 | 21        | 8.57%   |
| 2018 | 19        | 7.76%   |
| 2012 | 19        | 7.76%   |
| 2020 | 17        | 6.94%   |
| 2014 | 16        | 6.53%   |
| 2007 | 16        | 6.53%   |
| 2015 | 14        | 5.71%   |
| 2017 | 13        | 5.31%   |
| 2016 | 12        | 4.9%    |
| 2013 | 11        | 4.49%   |
| 2009 | 11        | 4.49%   |
| 2019 | 10        | 4.08%   |
| 2022 | 6         | 2.45%   |
| 2021 | 5         | 2.04%   |
| 2023 | 4         | 1.63%   |
| 2024 | 2         | 0.82%   |
| 2006 | 2         | 0.82%   |
| 2005 | 2         | 0.82%   |
| 2025 | 1         | 0.41%   |
| 2004 | 1         | 0.41%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 140       | 57.14%  |
| Desktop     | 84        | 34.29%  |
| All in one  | 10        | 4.08%   |
| Convertible | 4         | 1.63%   |
| Mini pc     | 4         | 1.63%   |
| Tablet      | 3         | 1.22%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 231       | 94.29%  |
| Enabled  | 14        | 5.71%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 242       | 98.78%  |
| Yes  | 3         | 1.22%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 82        | 33.47%  |
| 4.01-8.0    | 56        | 22.86%  |
| 1.01-2.0    | 38        | 15.51%  |
| 8.01-16.0   | 25        | 10.2%   |
| 16.01-24.0  | 23        | 9.39%   |
| 32.01-64.0  | 8         | 3.27%   |
| 2.01-3.0    | 5         | 2.04%   |
| 0.51-1.0    | 4         | 1.63%   |
| 24.01-32.0  | 2         | 0.82%   |
| 64.01-256.0 | 2         | 0.82%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 119       | 47.98%  |
| 2.01-3.0  | 63        | 25.4%   |
| 0.51-1.0  | 31        | 12.5%   |
| 3.01-4.0  | 15        | 6.05%   |
| 4.01-8.0  | 13        | 5.24%   |
| 8.01-16.0 | 4         | 1.61%   |
| 0.01-0.5  | 3         | 1.21%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 175       | 71.14%  |
| 2      | 53        | 21.54%  |
| 3      | 10        | 4.07%   |
| 5      | 3         | 1.22%   |
| 4      | 3         | 1.22%   |
| 0      | 2         | 0.81%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 142       | 57.96%  |
| Yes       | 103       | 42.04%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 213       | 86.94%  |
| No        | 32        | 13.06%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 194       | 79.18%  |
| No        | 51        | 20.82%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 137       | 55.69%  |
| No        | 109       | 44.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 49        | 20%     |
| Germany      | 19        | 7.76%   |
| Brazil       | 17        | 6.94%   |
| UK           | 15        | 6.12%   |
| France       | 11        | 4.49%   |
| Italy        | 10        | 4.08%   |
| Poland       | 9         | 3.67%   |
| Canada       | 9         | 3.67%   |
| Mexico       | 7         | 2.86%   |
| Romania      | 6         | 2.45%   |
| Ukraine      | 5         | 2.04%   |
| Spain        | 5         | 2.04%   |
| Russia       | 5         | 2.04%   |
| Netherlands  | 5         | 2.04%   |
| Colombia     | 5         | 2.04%   |
| Peru         | 4         | 1.63%   |
| Turkey       | 3         | 1.22%   |
| Thailand     | 3         | 1.22%   |
| Serbia       | 3         | 1.22%   |
| Portugal     | 3         | 1.22%   |
| Indonesia    | 3         | 1.22%   |
| Australia    | 3         | 1.22%   |
| Venezuela    | 2         | 0.82%   |
| Switzerland  | 2         | 0.82%   |
| Sweden       | 2         | 0.82%   |
| Slovakia     | 2         | 0.82%   |
| Qatar        | 2         | 0.82%   |
| Philippines  | 2         | 0.82%   |
| Malaysia     | 2         | 0.82%   |
| Ireland      | 2         | 0.82%   |
| India        | 2         | 0.82%   |
| Greece       | 2         | 0.82%   |
| Chile        | 2         | 0.82%   |
| Bulgaria     | 2         | 0.82%   |
| Argentina    | 2         | 0.82%   |
| Uzbekistan   | 1         | 0.41%   |
| South Africa | 1         | 0.41%   |
| Singapore    | 1         | 0.41%   |
| Saudi Arabia | 1         | 0.41%   |
| Pakistan     | 1         | 0.41%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Würzburg         | 3         | 1.2%    |
| Tamm              | 3         | 1.2%    |
| Pabianice         | 3         | 1.2%    |
| Moscow            | 3         | 1.2%    |
| Bangkok           | 3         | 1.2%    |
| Warsaw            | 2         | 0.8%    |
| Valencia          | 2         | 0.8%    |
| Toronto           | 2         | 0.8%    |
| The Hague         | 2         | 0.8%    |
| Sydney            | 2         | 0.8%    |
| Sao Paulo         | 2         | 0.8%    |
| Salerno           | 2         | 0.8%    |
| Randolph          | 2         | 0.8%    |
| Paris             | 2         | 0.8%    |
| Ottawa            | 2         | 0.8%    |
| Odessa            | 2         | 0.8%    |
| Mexico City       | 2         | 0.8%    |
| Madrid            | 2         | 0.8%    |
| Lublin            | 2         | 0.8%    |
| Lisbon            | 2         | 0.8%    |
| Lima              | 2         | 0.8%    |
| Kyiv              | 2         | 0.8%    |
| Frankfurt am Main | 2         | 0.8%    |
| Estacada          | 2         | 0.8%    |
| East Sussex       | 2         | 0.8%    |
| Dublin            | 2         | 0.8%    |
| Doha              | 2         | 0.8%    |
| Delhi             | 2         | 0.8%    |
| Dallas            | 2         | 0.8%    |
| Bogotá           | 2         | 0.8%    |
| Berlin            | 2         | 0.8%    |
| Żywiec           | 1         | 0.4%    |
| Zurich            | 1         | 0.4%    |
| Yangon            | 1         | 0.4%    |
| Winterthur        | 1         | 0.4%    |
| Wiesbaden         | 1         | 0.4%    |
| Wellington        | 1         | 0.4%    |
| Waterbury         | 1         | 0.4%    |
| Washington        | 1         | 0.4%    |
| Wandsworth        | 1         | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 50        | 63     | 16.5%   |
| WDC                 | 43        | 55     | 14.19%  |
| Samsung Electronics | 29        | 32     | 9.57%   |
| Kingston            | 23        | 27     | 7.59%   |
| Toshiba             | 22        | 24     | 7.26%   |
| Unknown             | 20        | 26     | 6.6%    |
| Hitachi             | 15        | 17     | 4.95%   |
| SanDisk             | 10        | 10     | 3.3%    |
| China               | 8         | 10     | 2.64%   |
| Micron Technology   | 7         | 9      | 2.31%   |
| HGST                | 7         | 7      | 2.31%   |
| SK hynix            | 6         | 9      | 1.98%   |
| Crucial             | 5         | 5      | 1.65%   |
| A-DATA Technology   | 5         | 6      | 1.65%   |
| Maxtor              | 4         | 8      | 1.32%   |
| Apple               | 4         | 4      | 1.32%   |
| Phison              | 3         | 3      | 0.99%   |
| GOODRAM             | 3         | 3      | 0.99%   |
| Unknown             | 3         | 3      | 0.99%   |
| Team                | 2         | 2      | 0.66%   |
| PNY                 | 2         | 2      | 0.66%   |
| MSI                 | 2         | 2      | 0.66%   |
| JMicron Technology  | 2         | 2      | 0.66%   |
| Intenso             | 2         | 2      | 0.66%   |
| Intel               | 2         | 2      | 0.66%   |
| Hewlett-Packard     | 2         | 2      | 0.66%   |
| Fujitsu             | 2         | 2      | 0.66%   |
| ASMT                | 2         | 2      | 0.66%   |
| SSSTC               | 1         | 1      | 0.33%   |
| SPCC                | 1         | 1      | 0.33%   |
| OCZ                 | 1         | 1      | 0.33%   |
| MD20000             | 1         | 1      | 0.33%   |
| Mass                | 1         | 1      | 0.33%   |
| LITEONIT            | 1         | 1      | 0.33%   |
| LITEON              | 1         | 1      | 0.33%   |
| Lexar               | 1         | 1      | 0.33%   |
| KIOXIA              | 1         | 1      | 0.33%   |
| HS-SSD-E100         | 1         | 1      | 0.33%   |
| HPE                 | 1         | 1      | 0.33%   |
| Gigabyte Technology | 1         | 1      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                   | 7         | 2.15%   |
| Unknown MMC Card  32GB                            | 6         | 1.84%   |
| Toshiba MQ01ABF050 500GB                          | 5         | 1.53%   |
| WDC WD10JPVX-22JC3T0 1TB                          | 4         | 1.23%   |
| Toshiba MQ01ABD100 1TB                            | 3         | 0.92%   |
| Seagate ST9500325AS 500GB                         | 3         | 0.92%   |
| Seagate ST500DM002-1BD142 500GB                   | 3         | 0.92%   |
| Seagate ST3500418AS 500GB                         | 3         | 0.92%   |
| Samsung SSD 860 EVO 500GB                         | 3         | 0.92%   |
| Kingston SA400S37480G 480GB SSD                   | 3         | 0.92%   |
| Unknown                                           | 3         | 0.92%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                  | 2         | 0.61%   |
| WDC WD5000AAKX-001CA0 500GB                       | 2         | 0.61%   |
| WDC WD10JPVX-75JC3T0 1TB                          | 2         | 0.61%   |
| Unknown NCard  32GB                               | 2         | 0.61%   |
| Unknown HBG4a2  32GB                              | 2         | 0.61%   |
| Unknown DA4064  64GB                              | 2         | 0.61%   |
| Toshiba MQ04ABF100 1TB                            | 2         | 0.61%   |
| Toshiba MQ01ABD050 500GB                          | 2         | 0.61%   |
| Toshiba MK3265GSX 320GB                           | 2         | 0.61%   |
| Toshiba DT01ACA100 1TB                            | 2         | 0.61%   |
| Seagate ST9320325AS 320GB                         | 2         | 0.61%   |
| Seagate ST500LT012-1DG142 500GB                   | 2         | 0.61%   |
| Seagate ST1000LM049-2GH172 1TB                    | 2         | 0.61%   |
| Seagate ST1000LM048-2E7172 1TB                    | 2         | 0.61%   |
| Seagate ST1000LM035-1RK172 1TB                    | 2         | 0.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 2         | 0.61%   |
| SanDisk SDSSDA240G 240GB                          | 2         | 0.61%   |
| SanDisk DF4032  32GB                              | 2         | 0.61%   |
| Samsung SSD PM851 mSATA 256GB                     | 2         | 0.61%   |
| Samsung SSD 850 EVO 250GB                         | 2         | 0.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 2         | 0.61%   |
| Samsung MZVLB256HAHQ-000L7 256GB                  | 2         | 0.61%   |
| Samsung HM500JI 500GB                             | 2         | 0.61%   |
| Samsung HM160HI 160GB                             | 2         | 0.61%   |
| MSI S270 240GB                                    | 2         | 0.61%   |
| Micron MTFDDAK256MAM-1K12 256GB SSD               | 2         | 0.61%   |
| Maxtor Z1 SSD 240GB                               | 2         | 0.61%   |
| Kingston SV300S37A60G 64GB SSD                    | 2         | 0.61%   |
| Kingston SNVS500G 500GB                           | 2         | 0.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 48        | 61     | 34.04%  |
| WDC                 | 35        | 43     | 24.82%  |
| Toshiba             | 21        | 23     | 14.89%  |
| Hitachi             | 15        | 17     | 10.64%  |
| HGST                | 7         | 7      | 4.96%   |
| Samsung Electronics | 5         | 6      | 3.55%   |
| Maxtor              | 2         | 6      | 1.42%   |
| Fujitsu             | 2         | 2      | 1.42%   |
| Apple               | 2         | 2      | 1.42%   |
| Unknown             | 1         | 2      | 0.71%   |
| JMicron Technology  | 1         | 1      | 0.71%   |
| HPE                 | 1         | 1      | 0.71%   |
| ASMT                | 1         | 1      | 0.71%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 19        | 21     | 18.45%  |
| Samsung Electronics | 16        | 16     | 15.53%  |
| China               | 8         | 10     | 7.77%   |
| SanDisk             | 7         | 7      | 6.8%    |
| WDC                 | 6         | 7      | 5.83%   |
| Crucial             | 5         | 5      | 4.85%   |
| A-DATA Technology   | 5         | 6      | 4.85%   |
| Micron Technology   | 4         | 6      | 3.88%   |
| GOODRAM             | 3         | 3      | 2.91%   |
| PNY                 | 2         | 2      | 1.94%   |
| Phison              | 2         | 2      | 1.94%   |
| MSI                 | 2         | 2      | 1.94%   |
| Maxtor              | 2         | 2      | 1.94%   |
| Hewlett-Packard     | 2         | 2      | 1.94%   |
| Apple               | 2         | 2      | 1.94%   |
| Unknown             | 1         | 1      | 0.97%   |
| Toshiba             | 1         | 1      | 0.97%   |
| SPCC                | 1         | 1      | 0.97%   |
| SK hynix            | 1         | 4      | 0.97%   |
| Seagate             | 1         | 1      | 0.97%   |
| OCZ                 | 1         | 1      | 0.97%   |
| LITEONIT            | 1         | 1      | 0.97%   |
| LITEON              | 1         | 1      | 0.97%   |
| Lexar               | 1         | 1      | 0.97%   |
| Intenso             | 1         | 1      | 0.97%   |
| Intel               | 1         | 1      | 0.97%   |
| Gigabyte Technology | 1         | 1      | 0.97%   |
| Fanxiang            | 1         | 2      | 0.97%   |
| Dogfish             | 1         | 1      | 0.97%   |
| CT1000MX            | 1         | 1      | 0.97%   |
| ASUS-PHISON         | 1         | 2      | 0.97%   |
| ASMT                | 1         | 1      | 0.97%   |
| Apacer              | 1         | 1      | 0.97%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 130       | 172    | 45.61%  |
| SSD     | 98        | 116    | 34.39%  |
| NVMe    | 27        | 35     | 9.47%   |
| MMC     | 24        | 30     | 8.42%   |
| Unknown | 6         | 6      | 2.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 203       | 279    | 76.03%  |
| NVMe | 27        | 35     | 10.11%  |
| MMC  | 24        | 30     | 8.99%   |
| SAS  | 13        | 15     | 4.87%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 158       | 207    | 69.3%   |
| 0.51-1.0   | 62        | 72     | 27.19%  |
| 1.01-2.0   | 5         | 6      | 2.19%   |
| 3.01-4.0   | 2         | 2      | 0.88%   |
| 2.01-3.0   | 1         | 1      | 0.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 82        | 32.8%   |
| 251-500        | 55        | 22%     |
| 51-100         | 35        | 14%     |
| 501-1000       | 28        | 11.2%   |
| 1-20           | 17        | 6.8%    |
| 21-50          | 14        | 5.6%    |
| 1001-2000      | 9         | 3.6%    |
| More than 3000 | 7         | 2.8%    |
| 2001-3000      | 2         | 0.8%    |
| Unknown        | 1         | 0.4%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 111       | 43.7%   |
| 21-50     | 66        | 25.98%  |
| 51-100    | 28        | 11.02%  |
| 101-250   | 26        | 10.24%  |
| 251-500   | 9         | 3.54%   |
| 501-1000  | 6         | 2.36%   |
| 1001-2000 | 4         | 1.57%   |
| 2001-3000 | 3         | 1.18%   |
| Unknown   | 1         | 0.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Toshiba MK3265GSX 320GB                        | 2         | 2      | 4.65%   |
| WDC WDS480G2G0A-00JH30 480GB SSD               | 1         | 1      | 2.33%   |
| WDC WD800JD-60LSA0 80GB                        | 1         | 1      | 2.33%   |
| WDC WD800JD-00MSA1 80GB                        | 1         | 1      | 2.33%   |
| WDC WD5000AAKX-001CA0 500GB                    | 1         | 1      | 2.33%   |
| WDC WD5000AAKS-60WWPA0 500GB                   | 1         | 1      | 2.33%   |
| WDC WD1600BEVT-22A23T0 160GB                   | 1         | 1      | 2.33%   |
| WDC WD10JPVX-22JC3T0 1TB                       | 1         | 1      | 2.33%   |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 2.33%   |
| Toshiba MK1059GSM 1TB                          | 1         | 1      | 2.33%   |
| Toshiba DT01ACA100 1TB                         | 1         | 1      | 2.33%   |
| SK hynix HFS256G39TND-N210A 256GB SSD          | 1         | 2      | 2.33%   |
| Seagate ST980811AS 80GB                        | 1         | 1      | 2.33%   |
| Seagate ST9500423AS 500GB                      | 1         | 1      | 2.33%   |
| Seagate ST9500325AS 500GB                      | 1         | 1      | 2.33%   |
| Seagate ST9320325AS 320GB                      | 1         | 1      | 2.33%   |
| Seagate ST9320320AS 320GB                      | 1         | 1      | 2.33%   |
| Seagate ST9160823ASG 160GB                     | 1         | 1      | 2.33%   |
| Seagate ST500LT012-9WS142 500GB                | 1         | 1      | 2.33%   |
| Seagate ST500LT012-1DG142 500GB                | 1         | 1      | 2.33%   |
| Seagate ST3750528AS 752GB                      | 1         | 1      | 2.33%   |
| Seagate ST3120026A 120GB                       | 1         | 1      | 2.33%   |
| Seagate ST1000LM049-2GH172 1TB                 | 1         | 1      | 2.33%   |
| Seagate ST1000LM048-2E7172 1TB                 | 1         | 1      | 2.33%   |
| Seagate ST1000LM035-1RK172 1TB                 | 1         | 1      | 2.33%   |
| SanDisk SSD PLUS 120GB                         | 1         | 1      | 2.33%   |
| Samsung Electronics HM250JI 250GB              | 1         | 1      | 2.33%   |
| Samsung Electronics HM160HI 160GB              | 1         | 1      | 2.33%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1         | 1      | 2.33%   |
| Maxtor 6Y250M0 256GB                           | 1         | 1      | 2.33%   |
| Maxtor 6V300F0 304GB                           | 1         | 3      | 2.33%   |
| Kingston SUV400S37240G 240GB SSD               | 1         | 1      | 2.33%   |
| Hitachi HTS547575A9E384 752GB                  | 1         | 1      | 2.33%   |
| Hitachi HTS545016B9A300 160GB                  | 1         | 1      | 2.33%   |
| Hitachi HTS543232A7A384 320GB                  | 1         | 1      | 2.33%   |
| Hitachi HDS722020ALA330 2TB                    | 1         | 1      | 2.33%   |
| Hitachi HDS721680PLA380 80GB                   | 1         | 1      | 2.33%   |
| Hitachi HDS721616PLA380 160GB                  | 1         | 1      | 2.33%   |
| Hitachi HDP725032GLA360 320GB                  | 1         | 1      | 2.33%   |
| HGST HTS725050A7E630 500GB                     | 1         | 1      | 2.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 13     | 30.95%  |
| WDC                 | 7         | 7      | 16.67%  |
| Hitachi             | 7         | 7      | 16.67%  |
| Toshiba             | 5         | 5      | 11.9%   |
| Samsung Electronics | 2         | 2      | 4.76%   |
| SK hynix            | 1         | 2      | 2.38%   |
| SanDisk             | 1         | 1      | 2.38%   |
| Micron Technology   | 1         | 1      | 2.38%   |
| Maxtor              | 1         | 4      | 2.38%   |
| Kingston            | 1         | 1      | 2.38%   |
| HGST                | 1         | 1      | 2.38%   |
| Apple               | 1         | 1      | 2.38%   |
| Apacer              | 1         | 1      | 2.38%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 13     | 37.14%  |
| Hitachi             | 7         | 7      | 20%     |
| WDC                 | 6         | 6      | 17.14%  |
| Toshiba             | 5         | 5      | 14.29%  |
| Samsung Electronics | 2         | 2      | 5.71%   |
| Maxtor              | 1         | 4      | 2.86%   |
| HGST                | 1         | 1      | 2.86%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 33        | 38     | 82.5%   |
| SSD  | 7         | 8      | 17.5%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Intenso SSD SATAIII 512GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Intenso | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 115       | 150    | 43.89%  |
| Detected | 107       | 162    | 40.84%  |
| Malfunc  | 39        | 46     | 14.89%  |
| Failed   | 1         | 1      | 0.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 168       | 64.37%  |
| AMD                            | 47        | 18.01%  |
| Samsung Electronics            | 8         | 3.07%   |
| Nvidia                         | 7         | 2.68%   |
| SanDisk                        | 4         | 1.53%   |
| Kingston Technology Company    | 4         | 1.53%   |
| SK hynix                       | 3         | 1.15%   |
| Micron Technology              | 3         | 1.15%   |
| Marvell Technology Group       | 3         | 1.15%   |
| JMicron Technology             | 2         | 0.77%   |
| VIA Technologies               | 1         | 0.38%   |
| ULi Electronics                | 1         | 0.38%   |
| Solid State Storage Technology | 1         | 0.38%   |
| Silicon Image                  | 1         | 0.38%   |
| Shenzhen Longsys Electronics   | 1         | 0.38%   |
| Phison Electronics             | 1         | 0.38%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.38%   |
| LSI Logic / Symbios Logic      | 1         | 0.38%   |
| KIOXIA                         | 1         | 0.38%   |
| Hosin Global Electronics       | 1         | 0.38%   |
| Broadcom / LSI                 | 1         | 0.38%   |
| ASMedia Technology             | 1         | 0.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 29        | 8.95%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 12        | 3.7%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 11        | 3.4%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 9         | 2.78%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 9         | 2.78%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 8         | 2.47%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 8         | 2.47%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 7         | 2.16%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 7         | 2.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7         | 2.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 7         | 2.16%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 7         | 2.16%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 6         | 1.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 6         | 1.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 5         | 1.54%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 5         | 1.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 5         | 1.54%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 5         | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5         | 1.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5         | 1.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 4         | 1.23%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 4         | 1.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4         | 1.23%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 4         | 1.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 4         | 1.23%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 4         | 1.23%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 4         | 1.23%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 3         | 0.93%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3         | 0.93%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 0.93%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3         | 0.93%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3         | 0.93%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 0.93%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 3         | 0.93%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 3         | 0.93%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 2         | 0.62%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 0.62%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 2         | 0.62%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                            | 2         | 0.62%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 2         | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 175       | 61.62%  |
| IDE  | 66        | 23.24%  |
| NVMe | 27        | 9.51%   |
| RAID | 15        | 5.28%   |
| SCSI | 1         | 0.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 191       | 77.96%  |
| AMD    | 54        | 22.04%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 5         | 2.04%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 3         | 1.22%   |
| Intel Celeron N4120 CPU @ 1.10GHz             | 3         | 1.22%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 3         | 1.22%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 3         | 1.22%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 3         | 1.22%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 3         | 1.22%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 2         | 0.82%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 0.82%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 0.82%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 0.82%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.82%   |
| Intel Core i5-3570K CPU @ 3.40GHz             | 2         | 0.82%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 2         | 0.82%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.82%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 2         | 0.82%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 2         | 0.82%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 2         | 0.82%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 2         | 0.82%   |
| Intel Core 2 CPU T7600 @ 2.33GHz              | 2         | 0.82%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 2         | 0.82%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 0.82%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 0.82%   |
| Intel Celeron CPU N2807 @ 1.58GHz             | 2         | 0.82%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 2         | 0.82%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 0.82%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 2         | 0.82%   |
| AMD E2-9000e RADEON R2, 4 COMPUTE CORES 2C+2G | 2         | 0.82%   |
| AMD E1-2100 APU with Radeon HD Graphics       | 2         | 0.82%   |
| Intel Xeon CPU X5680 @ 3.33GHz                | 1         | 0.41%   |
| Intel Xeon CPU E5450 @ 3.00GHz                | 1         | 0.41%   |
| Intel Xeon CPU E5410 @ 2.33GHz                | 1         | 0.41%   |
| Intel Xeon CPU 5150 @ 2.66GHz                 | 1         | 0.41%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.41%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.41%   |
| Intel Pentium Dual-Core CPU E6300 @ 2.80GHz   | 1         | 0.41%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz   | 1         | 0.41%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz        | 1         | 0.41%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz        | 1         | 0.41%   |
| Intel Pentium D CPU 3.40GHz                   | 1         | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 43        | 17.55%  |
| Intel Celeron           | 29        | 11.84%  |
| Intel Core i3           | 22        | 8.98%   |
| Intel Core 2 Duo        | 22        | 8.98%   |
| Intel Core i7           | 14        | 5.71%   |
| Intel Atom              | 14        | 5.71%   |
| Other                   | 11        | 4.49%   |
| Intel Pentium           | 8         | 3.27%   |
| AMD Ryzen 5             | 8         | 3.27%   |
| Intel Pentium Dual-Core | 7         | 2.86%   |
| Intel Xeon              | 4         | 1.63%   |
| Intel Core 2            | 4         | 1.63%   |
| AMD Ryzen 3             | 4         | 1.63%   |
| AMD A8                  | 4         | 1.63%   |
| AMD A6                  | 4         | 1.63%   |
| Intel Core 2 Quad       | 3         | 1.22%   |
| AMD FX                  | 3         | 1.22%   |
| AMD E2                  | 3         | 1.22%   |
| AMD E1                  | 3         | 1.22%   |
| AMD A10                 | 3         | 1.22%   |
| Intel Pentium Silver    | 2         | 0.82%   |
| Intel Pentium Dual      | 2         | 0.82%   |
| Intel Pentium D         | 2         | 0.82%   |
| Intel Genuine           | 2         | 0.82%   |
| AMD Turion 64 X2 Mobile | 2         | 0.82%   |
| AMD Phenom II X2        | 2         | 0.82%   |
| AMD E                   | 2         | 0.82%   |
| AMD Athlon II X2        | 2         | 0.82%   |
| Intel Core m7           | 1         | 0.41%   |
| Intel Core 2 Extreme    | 1         | 0.41%   |
| Intel Celeron M         | 1         | 0.41%   |
| Intel Celeron Dual-Core | 1         | 0.41%   |
| AMD Turion Dual-Core    | 1         | 0.41%   |
| AMD Sempron             | 1         | 0.41%   |
| AMD Ryzen 9             | 1         | 0.41%   |
| AMD Quad-Core           | 1         | 0.41%   |
| AMD Phenom II X6        | 1         | 0.41%   |
| AMD Phenom II X4        | 1         | 0.41%   |
| AMD GX                  | 1         | 0.41%   |
| AMD Athlon II Neo       | 1         | 0.41%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 138       | 56.33%  |
| 4      | 81        | 33.06%  |
| 6      | 12        | 4.9%    |
| 1      | 8         | 3.27%   |
| 12     | 2         | 0.82%   |
| 14     | 1         | 0.41%   |
| 10     | 1         | 0.41%   |
| 8      | 1         | 0.41%   |
| 3      | 1         | 0.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 243       | 99.18%  |
| 2      | 2         | 0.82%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 145       | 59.18%  |
| 2      | 100       | 40.82%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 243       | 99.18%  |
| 32-bit         | 2         | 0.82%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 81        | 32.4%   |
| 0x206a7    | 17        | 6.8%    |
| 0x1067a    | 17        | 6.8%    |
| 0x30678    | 10        | 4%      |
| 0x306a9    | 7         | 2.8%    |
| 0x706a1    | 5         | 2%      |
| 0x6fd      | 5         | 2%      |
| 0x406c4    | 5         | 2%      |
| 0x40651    | 5         | 2%      |
| 0x306c3    | 5         | 2%      |
| 0x20655    | 5         | 2%      |
| 0x6fb      | 4         | 1.6%    |
| 0x506c9    | 4         | 1.6%    |
| 0x10676    | 4         | 1.6%    |
| 0x010000c8 | 4         | 1.6%    |
| 0x806ec    | 3         | 1.2%    |
| 0x806c1    | 3         | 1.2%    |
| 0x6f6      | 3         | 1.2%    |
| 0x06006705 | 3         | 1.2%    |
| 0x906e9    | 2         | 0.8%    |
| 0x906c0    | 2         | 0.8%    |
| 0x806ea    | 2         | 0.8%    |
| 0x806e9    | 2         | 0.8%    |
| 0x706a8    | 2         | 0.8%    |
| 0x506e3    | 2         | 0.8%    |
| 0x406e3    | 2         | 0.8%    |
| 0x406c3    | 2         | 0.8%    |
| 0x206c2    | 2         | 0.8%    |
| 0x106ca    | 2         | 0.8%    |
| 0x07030105 | 2         | 0.8%    |
| 0x06000852 | 2         | 0.8%    |
| 0x05000119 | 2         | 0.8%    |
| 0x010000db | 2         | 0.8%    |
| 0xf64      | 1         | 0.4%    |
| 0xf44      | 1         | 0.4%    |
| 0xa0653    | 1         | 0.4%    |
| 0x906eb    | 1         | 0.4%    |
| 0x906ea    | 1         | 0.4%    |
| 0x906a4    | 1         | 0.4%    |
| 0x906a3    | 1         | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Penryn           | 30        | 12.24%  |
| Silvermont       | 24        | 9.8%    |
| SandyBridge      | 21        | 8.57%   |
| Core             | 17        | 6.94%   |
| KabyLake         | 16        | 6.53%   |
| Haswell          | 14        | 5.71%   |
| IvyBridge        | 11        | 4.49%   |
| Goldmont plus    | 11        | 4.49%   |
| Westmere         | 9         | 3.67%   |
| K10              | 9         | 3.67%   |
| Skylake          | 7         | 2.86%   |
| Puma             | 7         | 2.86%   |
| Excavator        | 7         | 2.86%   |
| Goldmont         | 5         | 2.04%   |
| Zen              | 4         | 1.63%   |
| Piledriver       | 4         | 1.63%   |
| Bonnell          | 4         | 1.63%   |
| Unknown          | 4         | 1.63%   |
| Zen+             | 3         | 1.22%   |
| TigerLake        | 3         | 1.22%   |
| K8 Hammer        | 3         | 1.22%   |
| Jaguar           | 3         | 1.22%   |
| Bobcat           | 3         | 1.22%   |
| Alderlake Hybrid | 3         | 1.22%   |
| Zen 3            | 2         | 0.82%   |
| Tremont          | 2         | 0.82%   |
| Steamroller      | 2         | 0.82%   |
| P6               | 2         | 0.82%   |
| NetBurst         | 2         | 0.82%   |
| Nehalem          | 2         | 0.82%   |
| K10 Llano        | 2         | 0.82%   |
| Gracemont        | 2         | 0.82%   |
| CometLake        | 2         | 0.82%   |
| Broadwell        | 2         | 0.82%   |
| Zen 2            | 1         | 0.41%   |
| K8 & K10 hybrid  | 1         | 0.41%   |
| IceLake          | 1         | 0.41%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 145       | 54.92%  |
| AMD    | 65        | 24.62%  |
| Nvidia | 54        | 20.45%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 13        | 4.71%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13        | 4.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11        | 3.99%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 3.26%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 2.9%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 2.54%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 2.54%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 2.54%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 2.17%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 2.17%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6         | 2.17%   |
| Intel Apollo Lake GT1 [HD Graphics 500]                                                  | 5         | 1.81%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 5         | 1.81%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.45%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.09%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 3         | 1.09%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 1.09%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.09%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 1.09%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3         | 1.09%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3         | 1.09%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.72%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.72%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.72%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.72%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 2         | 0.72%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.72%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 2         | 0.72%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 2         | 0.72%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 0.72%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.72%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.72%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 2         | 0.72%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 2         | 0.72%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 2         | 0.72%   |
| AMD RV630/M76 [Mobility Radeon HD 2600 XT/2700]                                          | 2         | 0.72%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 2         | 0.72%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 0.72%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 0.72%   |
| AMD Kabini [Radeon HD 8210]                                                              | 2         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 123       | 50%     |
| 1 x AMD        | 59        | 23.98%  |
| 1 x Nvidia     | 38        | 15.45%  |
| Intel + Nvidia | 16        | 6.5%    |
| 2 x AMD        | 5         | 2.03%   |
| 2 x Intel      | 3         | 1.22%   |
| Other          | 1         | 0.41%   |
| Intel + AMD    | 1         | 0.41%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 215       | 87.4%   |
| Proprietary | 24        | 9.76%   |
| Unknown     | 7         | 2.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 159       | 63.86%  |
| 0.01-0.5   | 44        | 17.67%  |
| 0.51-1.0   | 19        | 7.63%   |
| 1.01-2.0   | 14        | 5.62%   |
| 3.01-4.0   | 7         | 2.81%   |
| 5.01-6.0   | 4         | 1.61%   |
| 7.01-8.0   | 1         | 0.4%    |
| 8.01-16.0  | 1         | 0.4%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 32        | 12.9%   |
| BOE                     | 26        | 10.48%  |
| AU Optronics            | 26        | 10.48%  |
| Chimei Innolux          | 19        | 7.66%   |
| LG Display              | 18        | 7.26%   |
| Hewlett-Packard         | 15        | 6.05%   |
| Goldstar                | 14        | 5.65%   |
| Chi Mei Optoelectronics | 10        | 4.03%   |
| Acer                    | 9         | 3.63%   |
| Apple                   | 7         | 2.82%   |
| Sony                    | 6         | 2.42%   |
| Dell                    | 6         | 2.42%   |
| Ancor Communications    | 6         | 2.42%   |
| Vestel Elektronik       | 4         | 1.61%   |
| Lenovo                  | 4         | 1.61%   |
| CPT                     | 4         | 1.61%   |
| ViewSonic               | 3         | 1.21%   |
| PANDA                   | 3         | 1.21%   |
| NEC Computers           | 3         | 1.21%   |
| LG Philips              | 3         | 1.21%   |
| InfoVision              | 3         | 1.21%   |
| AOC                     | 3         | 1.21%   |
| Unknown                 | 2         | 0.81%   |
| Philips                 | 2         | 0.81%   |
| HannStar                | 2         | 0.81%   |
| Belinea                 | 2         | 0.81%   |
| Unknown                 | 2         | 0.81%   |
| TSL                     | 1         | 0.4%    |
| Toshiba                 | 1         | 0.4%    |
| TCL                     | 1         | 0.4%    |
| Sharp                   | 1         | 0.4%    |
| Seiko/Epson             | 1         | 0.4%    |
| SANYO                   | 1         | 0.4%    |
| OEM                     | 1         | 0.4%    |
| NCS                     | 1         | 0.4%    |
| MSI                     | 1         | 0.4%    |
| InnoLux Display         | 1         | 0.4%    |
| Hitachi                 | 1         | 0.4%    |
| eMachines               | 1         | 0.4%    |
| cPATH                   | 1         | 0.4%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 880x500mm 39.8-inch  | 4         | 1.57%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 3         | 1.18%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 3         | 1.18%   |
| Ancor Communications VE247 ACI2493 1920x1080 530x300mm 24.0-inch      | 3         | 1.18%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 2         | 0.79%   |
| InfoVision LCD Monitor IVO04E3 1366x768 277x156mm 12.5-inch           | 2         | 0.79%   |
| Hewlett-Packard TouchSmart HWP4212 1920x1080 509x286mm 23.0-inch      | 2         | 0.79%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 2         | 0.79%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 0.79%   |
| CPT LCD Monitor CPT1401 1280x800 331x207mm 15.4-inch                  | 2         | 0.79%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                  | 2         | 0.79%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 2         | 0.79%   |
| BOE LCD Monitor BOE05DA 1366x768 277x156mm 12.5-inch                  | 2         | 0.79%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 2         | 0.79%   |
| Apple iMac APPAE19 3840x2160 475x267mm 21.5-inch                      | 2         | 0.79%   |
| Acer X193HQ ACR0069 1366x768 410x230mm 18.5-inch                      | 2         | 0.79%   |
| Unknown                                                               | 2         | 0.79%   |
| ViewSonic VP2365WB VSC7123 1920x1080 509x286mm 23.0-inch              | 1         | 0.39%   |
| ViewSonic VA2026w VSC5020 1680x1050 433x271mm 20.1-inch               | 1         | 0.39%   |
| ViewSonic VA1938 Series VSC0626 1366x768 410x230mm 18.5-inch          | 1         | 0.39%   |
| ViewSonic LCD Monitor VP2365WB 1920x1080                              | 1         | 0.39%   |
| TSL 24MT600BF TSL0758 1920x1080 530x299mm 24.0-inch                   | 1         | 0.39%   |
| Toshiba L705A LCD705A 1280x1024 340x270mm 17.1-inch                   | 1         | 0.39%   |
| TCL LCD TV TCL0030 1920x1080 708x398mm 32.0-inch                      | 1         | 0.39%   |
| Sony TV SNYEA01 1920x1080                                             | 1         | 0.39%   |
| Sony TV SNYDC01 1360x768                                              | 1         | 0.39%   |
| Sony TV SNY4803 1920x1080 1218x685mm 55.0-inch                        | 1         | 0.39%   |
| Sony TV SNY3002 1920x1080 886x498mm 40.0-inch                         | 1         | 0.39%   |
| Sony TV *00 SNY8004 3840x2160 1439x809mm 65.0-inch                    | 1         | 0.39%   |
| Sony Nvidia Defaul t Flat Panel MS_0025 1920x1080 360x200mm 16.2-inch | 1         | 0.39%   |
| Sharp HDMI SHP4192 1920x1080 708x398mm 32.0-inch                      | 1         | 0.39%   |
| Seiko/Epson LCD Monitor                                               | 1         | 0.39%   |
| SANYO LCD SAN1207 1360x768                                            | 1         | 0.39%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1         | 0.39%   |
| Samsung Electronics SyncMaster SAM055A 1920x1200 518x324mm 24.1-inch  | 1         | 0.39%   |
| Samsung Electronics SyncMaster SAM0426 1920x1200                      | 1         | 0.39%   |
| Samsung Electronics SyncMaster SAM0424 1920x1200 520x320mm 24.0-inch  | 1         | 0.39%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 1         | 0.39%   |
| Samsung Electronics SyncMaster SAM0193 1280x1024 376x301mm 19.0-inch  | 1         | 0.39%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch     | 1         | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 80        | 32.26%  |
| 1920x1080 (FHD)    | 77        | 31.05%  |
| 3840x2160 (4K)     | 14        | 5.65%   |
| 1920x1200 (WUXGA)  | 14        | 5.65%   |
| 1280x800 (WXGA)    | 12        | 4.84%   |
| 1600x900 (HD+)     | 10        | 4.03%   |
| 1680x1050 (WSXGA+) | 9         | 3.63%   |
| 1280x1024 (SXGA)   | 8         | 3.23%   |
| 1440x900 (WXGA+)   | 5         | 2.02%   |
| 1360x768           | 4         | 1.61%   |
| 1024x600           | 3         | 1.21%   |
| 2560x1440 (QHD)    | 2         | 0.81%   |
| 2288x1287          | 2         | 0.81%   |
| Unknown            | 2         | 0.81%   |
| 5280x1080          | 1         | 0.4%    |
| 3840x2400          | 1         | 0.4%    |
| 3440x1440          | 1         | 0.4%    |
| 1920x540           | 1         | 0.4%    |
| 1280x720 (HD)      | 1         | 0.4%    |
| 1024x768 (XGA)     | 1         | 0.4%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 55        | 22.09%  |
| 13      | 22        | 8.84%   |
| 14      | 20        | 8.03%   |
| 24      | 19        | 7.63%   |
| 17      | 16        | 6.43%   |
| 23      | 13        | 5.22%   |
| 21      | 12        | 4.82%   |
| Unknown | 11        | 4.42%   |
| 12      | 10        | 4.02%   |
| 11      | 9         | 3.61%   |
| 20      | 8         | 3.21%   |
| 27      | 7         | 2.81%   |
| 19      | 7         | 2.81%   |
| 18      | 7         | 2.81%   |
| 10      | 5         | 2.01%   |
| 84      | 4         | 1.61%   |
| 31      | 4         | 1.61%   |
| 22      | 4         | 1.61%   |
| 16      | 3         | 1.2%    |
| 142     | 2         | 0.8%    |
| 72      | 2         | 0.8%    |
| 46      | 2         | 0.8%    |
| 32      | 2         | 0.8%    |
| 65      | 1         | 0.4%    |
| 60      | 1         | 0.4%    |
| 34      | 1         | 0.4%    |
| 28      | 1         | 0.4%    |
| 26      | 1         | 0.4%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 96        | 38.71%  |
| 501-600        | 37        | 14.92%  |
| 401-500        | 37        | 14.92%  |
| 201-300        | 31        | 12.5%   |
| 351-400        | 15        | 6.05%   |
| Unknown        | 11        | 4.44%   |
| 601-700        | 6         | 2.42%   |
| 1501-2000      | 6         | 2.42%   |
| 1001-1500      | 4         | 1.61%   |
| 701-800        | 3         | 1.21%   |
| More than 2000 | 2         | 0.81%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 178       | 75.42%  |
| 16/10   | 36        | 15.25%  |
| 5/4     | 8         | 3.39%   |
| Unknown | 7         | 2.97%   |
| 4/3     | 2         | 0.85%   |
| 1.00    | 2         | 0.85%   |
| 6/5     | 1         | 0.42%   |
| 3/2     | 1         | 0.42%   |
| 21/9    | 1         | 0.42%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 55        | 22.18%  |
| 201-250        | 38        | 15.32%  |
| 81-90          | 35        | 14.11%  |
| 151-200        | 21        | 8.47%   |
| 141-150        | 11        | 4.44%   |
| Unknown        | 11        | 4.44%   |
| More than 1000 | 9         | 3.63%   |
| 61-70          | 9         | 3.63%   |
| 51-60          | 9         | 3.63%   |
| 71-80          | 8         | 3.23%   |
| 351-500        | 8         | 3.23%   |
| 301-350        | 8         | 3.23%   |
| 121-130        | 7         | 2.82%   |
| 131-140        | 6         | 2.42%   |
| 41-50          | 5         | 2.02%   |
| 251-300        | 5         | 2.02%   |
| 501-1000       | 2         | 0.81%   |
| 111-120        | 1         | 0.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 82        | 34.02%  |
| 101-120       | 78        | 32.37%  |
| 121-160       | 51        | 21.16%  |
| Unknown       | 11        | 4.56%   |
| 161-240       | 10        | 4.15%   |
| 1-50          | 7         | 2.9%    |
| More than 240 | 2         | 0.83%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 218       | 88.62%  |
| 2     | 24        | 9.76%   |
| 0     | 3         | 1.22%   |
| 3     | 1         | 0.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 135       | 36.19%  |
| Intel                                 | 81        | 21.72%  |
| Qualcomm Atheros                      | 56        | 15.01%  |
| Broadcom                              | 27        | 7.24%   |
| Marvell Technology Group              | 8         | 2.14%   |
| Broadcom Limited                      | 8         | 2.14%   |
| Ralink Technology                     | 7         | 1.88%   |
| Ralink                                | 6         | 1.61%   |
| TP-Link                               | 5         | 1.34%   |
| Nvidia                                | 5         | 1.34%   |
| Sierra Wireless                       | 4         | 1.07%   |
| ASUSTek Computer                      | 4         | 1.07%   |
| MediaTek                              | 3         | 0.8%    |
| Xiaomi                                | 2         | 0.54%   |
| Qualcomm Atheros Communications       | 2         | 0.54%   |
| Dell                                  | 2         | 0.54%   |
| ASIX Electronics                      | 2         | 0.54%   |
| ZTE WCDMA Technologies MSM            | 1         | 0.27%   |
| Sundance Technology Inc / IC Plus     | 1         | 0.27%   |
| Sitecom Europe                        | 1         | 0.27%   |
| Samsung Electronics                   | 1         | 0.27%   |
| OPPO Electronics                      | 1         | 0.27%   |
| Microsoft                             | 1         | 0.27%   |
| Linksys                               | 1         | 0.27%   |
| Lenovo                                | 1         | 0.27%   |
| JMicron Technology                    | 1         | 0.27%   |
| Huawei Technologies                   | 1         | 0.27%   |
| Gemtek                                | 1         | 0.27%   |
| Ericsson Business Mobile Networks     | 1         | 0.27%   |
| D-Link                                | 1         | 0.27%   |
| Belkin Components                     | 1         | 0.27%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.27%   |
| 3Com                                  | 1         | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                        | 90        | 20.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                         | 26        | 5.87%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 12        | 2.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 11        | 2.48%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 11        | 2.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 10        | 2.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                         | 10        | 2.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 8         | 1.81%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 6         | 1.35%   |
| Realtek 802.11ac NIC                                                                          | 5         | 1.13%   |
| Ralink MT7601U Wireless Adapter                                                               | 5         | 1.13%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 5         | 1.13%   |
| Intel Wireless 7260                                                                           | 5         | 1.13%   |
| Intel Wireless 3165                                                                           | 5         | 1.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                      | 4         | 0.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 4         | 0.9%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 4         | 0.9%    |
| Intel Gemini Lake PCH CNVi WiFi                                                               | 4         | 0.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 4         | 0.9%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 3         | 0.68%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 3         | 0.68%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                                      | 3         | 0.68%   |
| Intel Wireless 7265                                                                           | 3         | 0.68%   |
| Intel Wireless 3160                                                                           | 3         | 0.68%   |
| Intel Ethernet Connection I218-LM                                                             | 3         | 0.68%   |
| Intel 82566DM-2 Gigabit Network Connection                                                    | 3         | 0.68%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                                | 2         | 0.45%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 2         | 0.45%   |
| Sierra Wireless EM7305 Modem                                                                  | 2         | 0.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 0.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 2         | 0.45%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 0.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 2         | 0.45%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 2         | 0.45%   |
| Realtek RTL8125 2.5GbE Controller                                                             | 2         | 0.45%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2         | 0.45%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2         | 0.45%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 2         | 0.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                                      | 2         | 0.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                 | 2         | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 59        | 27.96%  |
| Qualcomm Atheros                      | 51        | 24.17%  |
| Realtek Semiconductor                 | 44        | 20.85%  |
| Broadcom                              | 12        | 5.69%   |
| Ralink Technology                     | 7         | 3.32%   |
| Ralink                                | 6         | 2.84%   |
| Broadcom Limited                      | 6         | 2.84%   |
| TP-Link                               | 5         | 2.37%   |
| Sierra Wireless                       | 4         | 1.9%    |
| ASUSTek Computer                      | 4         | 1.9%    |
| Qualcomm Atheros Communications       | 2         | 0.95%   |
| MediaTek                              | 2         | 0.95%   |
| Dell                                  | 2         | 0.95%   |
| Sitecom Europe                        | 1         | 0.47%   |
| Microsoft                             | 1         | 0.47%   |
| Linksys                               | 1         | 0.47%   |
| Gemtek                                | 1         | 0.47%   |
| D-Link                                | 1         | 0.47%   |
| Belkin Components                     | 1         | 0.47%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 12        | 5.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 11        | 5.16%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 11        | 5.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 10        | 4.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 8         | 3.76%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 6         | 2.82%   |
| Realtek 802.11ac NIC                                                                          | 5         | 2.35%   |
| Ralink MT7601U Wireless Adapter                                                               | 5         | 2.35%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 5         | 2.35%   |
| Intel Wireless 7260                                                                           | 5         | 2.35%   |
| Intel Wireless 3165                                                                           | 5         | 2.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 4         | 1.88%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 4         | 1.88%   |
| Intel Gemini Lake PCH CNVi WiFi                                                               | 4         | 1.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 4         | 1.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 3         | 1.41%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                                | 3         | 1.41%   |
| Intel Wireless 7265                                                                           | 3         | 1.41%   |
| Intel Wireless 3160                                                                           | 3         | 1.41%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                           | 2         | 0.94%   |
| Sierra Wireless EM7305 Modem                                                                  | 2         | 0.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 0.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 2         | 0.94%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 0.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 2         | 0.94%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 2         | 0.94%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 2         | 0.94%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 2         | 0.94%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                                     | 2         | 0.94%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 2         | 0.94%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 2         | 0.94%   |
| Intel Wireless 8265 / 8275                                                                    | 2         | 0.94%   |
| Intel Wireless 8260                                                                           | 2         | 0.94%   |
| Intel Wi-Fi 6 AX201                                                                           | 2         | 0.94%   |
| Intel Wi-Fi 6 AX200                                                                           | 2         | 0.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2         | 0.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                      | 2         | 0.94%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                              | 2         | 0.94%   |
| Dell Hub of E-Port Replicator                                                                 | 2         | 0.94%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                                     | 2         | 0.94%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 123       | 55.41%  |
| Intel                             | 41        | 18.47%  |
| Broadcom                          | 17        | 7.66%   |
| Qualcomm Atheros                  | 13        | 5.86%   |
| Marvell Technology Group          | 8         | 3.6%    |
| Nvidia                            | 5         | 2.25%   |
| Xiaomi                            | 2         | 0.9%    |
| Broadcom Limited                  | 2         | 0.9%    |
| ASIX Electronics                  | 2         | 0.9%    |
| ZTE WCDMA Technologies MSM        | 1         | 0.45%   |
| Sundance Technology Inc / IC Plus | 1         | 0.45%   |
| Samsung Electronics               | 1         | 0.45%   |
| OPPO Electronics                  | 1         | 0.45%   |
| MediaTek                          | 1         | 0.45%   |
| Lenovo                            | 1         | 0.45%   |
| JMicron Technology                | 1         | 0.45%   |
| Huawei Technologies               | 1         | 0.45%   |
| 3Com                              | 1         | 0.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller     | 90        | 39.47%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 26        | 11.4%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 10        | 4.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 4         | 1.75%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 3         | 1.32%   |
| Intel Ethernet Connection I218-LM                                          | 3         | 1.32%   |
| Intel 82566DM-2 Gigabit Network Connection                                 | 3         | 1.32%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 2         | 0.88%   |
| Realtek RTL8125 2.5GbE Controller                                          | 2         | 0.88%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 2         | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 2         | 0.88%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                      | 2         | 0.88%   |
| Nvidia MCP77 Ethernet                                                      | 2         | 0.88%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                    | 2         | 0.88%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                    | 2         | 0.88%   |
| Intel Ethernet Connection I217-LM                                          | 2         | 0.88%   |
| Intel 82567V-2 Gigabit Network Connection                                  | 2         | 0.88%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 2         | 0.88%   |
| Intel 82567LM Gigabit Network Connection                                   | 2         | 0.88%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                          | 2         | 0.88%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                          | 2         | 0.88%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                     | 2         | 0.88%   |
| ASIX AX88179 Gigabit Ethernet                                              | 2         | 0.88%   |
| ZTE WCDMA MSM ZTE Blade A54                                                | 1         | 0.44%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1         | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                              | 1         | 0.44%   |
| Realtek USB 10/100 LAN                                                     | 1         | 0.44%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                | 1         | 0.44%   |
| Realtek RTL8152 Fast Ethernet Adapter                                      | 1         | 0.44%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 1         | 0.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 1         | 0.44%   |
| Realtek Killer E2600 GbE Controller                                        | 1         | 0.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 1         | 0.44%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                 | 1         | 0.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 1         | 0.44%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                 | 1         | 0.44%   |
| OPPO Ace 3V                                                                | 1         | 0.44%   |
| Nvidia MCP61 Ethernet                                                      | 1         | 0.44%   |
| Nvidia MCP51 Ethernet Controller                                           | 1         | 0.44%   |
| Nvidia CK804 Ethernet Controller                                           | 1         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 213       | 52.21%  |
| WiFi     | 193       | 47.3%   |
| Modem    | 1         | 0.25%   |
| Unknown  | 1         | 0.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 158       | 62.45%  |
| Ethernet | 95        | 37.55%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 142       | 57.96%  |
| 1     | 91        | 37.14%  |
| 0     | 8         | 3.27%   |
| 3     | 3         | 1.22%   |
| 4     | 1         | 0.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 173       | 70.33%  |
| Yes  | 73        | 29.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 39        | 28.47%  |
| Realtek Semiconductor           | 24        | 17.52%  |
| Lite-On Technology              | 11        | 8.03%   |
| Cambridge Silicon Radio         | 10        | 7.3%    |
| Qualcomm Atheros Communications | 9         | 6.57%   |
| IMC Networks                    | 7         | 5.11%   |
| Broadcom                        | 7         | 5.11%   |
| Apple                           | 7         | 5.11%   |
| Hewlett-Packard                 | 6         | 4.38%   |
| Dell                            | 4         | 2.92%   |
| Foxconn / Hon Hai               | 2         | 1.46%   |
| Chicony Electronics             | 2         | 1.46%   |
| ASUSTek Computer                | 2         | 1.46%   |
| Alps Electric                   | 2         | 1.46%   |
| Toshiba                         | 1         | 0.73%   |
| Smart Modular Technologies      | 1         | 0.73%   |
| Realtek                         | 1         | 0.73%   |
| Ralink                          | 1         | 0.73%   |
| MediaTek                        | 1         | 0.73%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 20        | 14.6%   |
| Realtek Bluetooth Radio                             | 15        | 10.95%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10        | 7.3%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 8         | 5.84%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 4.38%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 3.65%   |
| Intel AX201 Bluetooth                               | 4         | 2.92%   |
| IMC Networks Bluetooth Device                       | 4         | 2.92%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 2.19%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 2.19%   |
| Lite-On Bluetooth Device                            | 3         | 2.19%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 2.19%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 2.19%   |
| Realtek RTL8723B Bluetooth                          | 2         | 1.46%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 1.46%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.46%   |
| Intel AX200 Bluetooth                               | 2         | 1.46%   |
| IMC Networks Bluetooth Radio                        | 2         | 1.46%   |
| Dell Wireless 355 Bluetooth                         | 2         | 1.46%   |
| Chicony Bluetooth (RTL8723BE)                       | 2         | 1.46%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 1.46%   |
| ASUS BT-270 Bluetooth Adapter                       | 2         | 1.46%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 1.46%   |
| Apple Bluetooth USB Host Controller                 | 2         | 1.46%   |
| Apple Bluetooth HCI                                 | 2         | 1.46%   |
| Alps Electric BCM2046 Bluetooth Device              | 2         | 1.46%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.73%   |
| Smart Modular Bluetooth Device                      | 1         | 0.73%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.73%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.73%   |
| Realtek Bluetooth Radio                             | 1         | 0.73%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.73%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.73%   |
| MediaTek Wireless_Device                            | 1         | 0.73%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 1         | 0.73%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.73%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.73%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.73%   |
| Intel Bluetooth Device                              | 1         | 0.73%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 0.73%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 178       | 58.94%  |
| AMD                     | 68        | 22.52%  |
| Nvidia                  | 34        | 11.26%  |
| C-Media Electronics     | 5         | 1.66%   |
| JMTek                   | 3         | 0.99%   |
| Logitech                | 2         | 0.66%   |
| Creative Labs           | 2         | 0.66%   |
| ULi Electronics         | 1         | 0.33%   |
| Texas Instruments       | 1         | 0.33%   |
| Realtek Semiconductor   | 1         | 0.33%   |
| Hewlett-Packard         | 1         | 0.33%   |
| GN Netcom               | 1         | 0.33%   |
| Giga-Byte Technology    | 1         | 0.33%   |
| Ensoniq                 | 1         | 0.33%   |
| Blue Microphones        | 1         | 0.33%   |
| BEHRINGER International | 1         | 0.33%   |
| ATI Technologies        | 1         | 0.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 18        | 5.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 17        | 4.8%    |
| AMD FCH Azalia Controller                                                                         | 16        | 4.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 14        | 3.95%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 3.95%   |
| AMD Kabini HDMI/DP Audio                                                                          | 13        | 3.67%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 12        | 3.39%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 12        | 3.39%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 11        | 3.11%   |
| AMD Ryzen HD Audio Controller                                                                     | 11        | 3.11%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 2.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 9         | 2.54%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9         | 2.54%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 1.98%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 1.98%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 1.98%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 7         | 1.98%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 6         | 1.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 1.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 1.41%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 5         | 1.41%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.41%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 1.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.13%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 4         | 1.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 1.13%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.85%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 0.85%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.85%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 0.85%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 3         | 0.85%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.85%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 3         | 0.85%   |
| AMD High Definition Audio Controller                                                              | 3         | 0.85%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3         | 0.85%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 3         | 0.85%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.56%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.56%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 2         | 0.56%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 42        | 19.91%  |
| Unknown             | 39        | 18.48%  |
| SK hynix            | 32        | 15.17%  |
| Kingston            | 28        | 13.27%  |
| Micron Technology   | 18        | 8.53%   |
| Unknown             | 7         | 3.32%   |
| Unknown (ABCD)      | 5         | 2.37%   |
| Elpida              | 5         | 2.37%   |
| Corsair             | 5         | 2.37%   |
| A-DATA Technology   | 4         | 1.9%    |
| Ramaxel Technology  | 3         | 1.42%   |
| Nanya Technology    | 3         | 1.42%   |
| G.Skill             | 2         | 0.95%   |
| Unknown (0x7F61)    | 1         | 0.47%   |
| Unknown (0x0080)    | 1         | 0.47%   |
| Unifosa             | 1         | 0.47%   |
| Transcend           | 1         | 0.47%   |
| Smart               | 1         | 0.47%   |
| Qumo                | 1         | 0.47%   |
| Qimonda             | 1         | 0.47%   |
| Patriot             | 1         | 0.47%   |
| KingSpec            | 1         | 0.47%   |
| GOODRAM             | 1         | 0.47%   |
| GeIL                | 1         | 0.47%   |
| G Skil              | 1         | 0.47%   |
| Crucial             | 1         | 0.47%   |
| Avant               | 1         | 0.47%   |
| 2C0C1121390963FE    | 1         | 0.47%   |
| 2C0C1121390963FD    | 1         | 0.47%   |
| 2C0C1121390963F9    | 1         | 0.47%   |
| 2C0C1121390963F8    | 1         | 0.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 7         | 3.15%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 4         | 1.8%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 4         | 1.8%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 1.8%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 1.35%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.35%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s            | 3         | 1.35%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 2         | 0.9%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 0.9%    |
| Unknown RAM Module 2GB DIMM SDRAM                                | 2         | 0.9%    |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 2         | 0.9%    |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s   | 2         | 0.9%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.9%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.9%    |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s           | 2         | 0.9%    |
| Samsung RAM M3 78T5663QZ3-CF7 2GB DIMM DDR2 800MT/s              | 2         | 0.9%    |
| Kingston RAM ACR256X64D3S1333C9 2GB SODIMM DDR3 1333MT/s         | 2         | 0.9%    |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s            | 2         | 0.9%    |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.45%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 1         | 0.45%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                          | 1         | 0.45%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                       | 1         | 0.45%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 0.45%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                         | 1         | 0.45%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 0.45%   |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                       | 1         | 0.45%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 1         | 0.45%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 1         | 0.45%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 1         | 0.45%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.45%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 0.45%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 0.45%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 1         | 0.45%   |
| Unknown RAM Module 2048MB DIMM DDR2                              | 1         | 0.45%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s                       | 1         | 0.45%   |
| Unknown RAM Module 2048MB DIMM DDR 133MT/s                       | 1         | 0.45%   |
| Unknown RAM Module 2048MB DIMM DDR                               | 1         | 0.45%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                           | 1         | 0.45%   |
| Unknown RAM Module 1GB SODIMM 667MT/s                            | 1         | 0.45%   |
| Unknown RAM Module 1GB DIMM DDR 400MT/s                          | 1         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 69        | 37.1%   |
| DDR4    | 45        | 24.19%  |
| DDR2    | 28        | 15.05%  |
| SDRAM   | 16        | 8.6%    |
| LPDDR4  | 10        | 5.38%   |
| Unknown | 8         | 4.3%    |
| DDR     | 5         | 2.69%   |
| LPDDR5  | 2         | 1.08%   |
| LPDDR3  | 1         | 0.54%   |
| DRAM    | 1         | 0.54%   |
| DDR5    | 1         | 0.54%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 118       | 64.48%  |
| DIMM         | 57        | 31.15%  |
| Row Of Chips | 6         | 3.28%   |
| FB-DIMM      | 2         | 1.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 64        | 31.84%  |
| 4096  | 58        | 28.86%  |
| 8192  | 40        | 19.9%   |
| 1024  | 21        | 10.45%  |
| 16384 | 13        | 6.47%   |
| 32768 | 3         | 1.49%   |
| 6144  | 1         | 0.5%    |
| 512   | 1         | 0.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 50        | 25.51%  |
| 3200    | 20        | 10.2%   |
| 2667    | 20        | 10.2%   |
| 1333    | 15        | 7.65%   |
| 667     | 15        | 7.65%   |
| Unknown | 12        | 6.12%   |
| 2400    | 8         | 4.08%   |
| 800     | 7         | 3.57%   |
| 4199    | 4         | 2.04%   |
| 3266    | 4         | 2.04%   |
| 975     | 4         | 2.04%   |
| 6400    | 3         | 1.53%   |
| 2133    | 3         | 1.53%   |
| 2048    | 3         | 1.53%   |
| 1334    | 3         | 1.53%   |
| 1066    | 3         | 1.53%   |
| 400     | 3         | 1.53%   |
| 3400    | 2         | 1.02%   |
| 1639    | 2         | 1.02%   |
| 49926   | 1         | 0.51%   |
| 19791   | 1         | 0.51%   |
| 4267    | 1         | 0.51%   |
| 3933    | 1         | 0.51%   |
| 3800    | 1         | 0.51%   |
| 3733    | 1         | 0.51%   |
| 3600    | 1         | 0.51%   |
| 3500    | 1         | 0.51%   |
| 2734    | 1         | 0.51%   |
| 1867    | 1         | 0.51%   |
| 1866    | 1         | 0.51%   |
| 1800    | 1         | 0.51%   |
| 1067    | 1         | 0.51%   |
| 1033    | 1         | 0.51%   |
| 133     | 1         | 0.51%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Canon LBP2900      | 1         | 50%     |
| Canon G1020 series | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 2         | 50%     |
| Mustek Systems  | 1         | 25%     |
| Hewlett-Packard | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Mustek Systems ScanExpress 1200 CU | 1         | 25%     |
| HP ScanJet 5200c                   | 1         | 25%     |
| Canon CanoScan LiDE 120            | 1         | 25%     |
| Canon CanoScan LiDE 110            | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 37        | 24.67%  |
| Realtek Semiconductor                  | 10        | 6.67%   |
| Microdia                               | 10        | 6.67%   |
| Apple                                  | 10        | 6.67%   |
| IMC Networks                           | 9         | 6%      |
| Suyin                                  | 8         | 5.33%   |
| Quanta                                 | 7         | 4.67%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 4.67%   |
| Sunplus Innovation Technology          | 6         | 4%      |
| Alcor Micro                            | 6         | 4%      |
| Syntek                                 | 5         | 3.33%   |
| Silicon Motion                         | 5         | 3.33%   |
| Ricoh                                  | 5         | 3.33%   |
| Lite-On Technology                     | 4         | 2.67%   |
| Logitech                               | 3         | 2%      |
| Bison Electronics                      | 3         | 2%      |
| Z-Star Microelectronics                | 2         | 1.33%   |
| Sweex                                  | 1         | 0.67%   |
| Sunplus IT                             | 1         | 0.67%   |
| Samsung Electronics                    | 1         | 0.67%   |
| Pixart Imaging                         | 1         | 0.67%   |
| OmniVision Technologies                | 1         | 0.67%   |
| Microsoft                              | 1         | 0.67%   |
| Luxvisions Innotech Limited            | 1         | 0.67%   |
| Jieli Technology                       | 1         | 0.67%   |
| Hewlett-Packard                        | 1         | 0.67%   |
| Generalplus Technology                 | 1         | 0.67%   |
| Aveo Technology                        | 1         | 0.67%   |
| ALi                                    | 1         | 0.67%   |
| Acer                                   | 1         | 0.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony USB2.0 VGA UVC WebCam                           | 6         | 4%      |
| Chicony Integrated Camera                               | 5         | 3.33%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 4         | 2.67%   |
| Ricoh Sony Vaio Integrated Webcam                       | 3         | 2%      |
| Chicony USB 2.0 Camera                                  | 3         | 2%      |
| Chicony HP Webcam                                       | 3         | 2%      |
| Apple Built-in iSight                                   | 3         | 2%      |
| Alcor Micro USB 2.0 Camera                              | 3         | 2%      |
| Syntek USB Video Device                                 | 2         | 1.33%   |
| Syntek Lenovo EasyCamera                                | 2         | 1.33%   |
| Suyin HP TrueVision HD Integrated Webcam                | 2         | 1.33%   |
| Sunplus Integrated_Webcam_HD                            | 2         | 1.33%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 1.33%   |
| Quanta HP TrueVision HD Camera                          | 2         | 1.33%   |
| Microdia Integrated Webcam                              | 2         | 1.33%   |
| Lite-On Integrated Camera                               | 2         | 1.33%   |
| Lite-On HP Webcam                                       | 2         | 1.33%   |
| IMC Networks EasyCamera                                 | 2         | 1.33%   |
| Chicony VGA Webcam                                      | 2         | 1.33%   |
| Chicony HP High Definition 1MP Webcam                   | 2         | 1.33%   |
| Chicony HD WebCam                                       | 2         | 1.33%   |
| Chicony FJ Camera                                       | 2         | 1.33%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 2         | 1.33%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 2         | 1.33%   |
| Bison Lenovo EasyCamera                                 | 2         | 1.33%   |
| Apple FaceTime HD Camera (Built-in)                     | 2         | 1.33%   |
| Alcor Micro Acer Integrated Webcam                      | 2         | 1.33%   |
| Z-Star Webcam                                           | 1         | 0.67%   |
| Z-Star Venus USB2.0 Camera                              | 1         | 0.67%   |
| Syntek Integrated Camera                                | 1         | 0.67%   |
| Sweex USB keyboard                                      | 1         | 0.67%   |
| Suyin USB 2.0 Camera                                    | 1         | 0.67%   |
| Suyin Integrated_Webcam_HD                              | 1         | 0.67%   |
| Suyin HP Truevision HD                                  | 1         | 0.67%   |
| Suyin HP Integrated Webcam                              | 1         | 0.67%   |
| Suyin HD WebCam                                         | 1         | 0.67%   |
| Suyin Acer/Lenovo Webcam [CN0316]                       | 1         | 0.67%   |
| Sunplus IT PC Camera                                    | 1         | 0.67%   |
| Sunplus MTD camera                                      | 1         | 0.67%   |
| Sunplus Laptop_Integrated_Webcam_HD                     | 1         | 0.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 21.05%  |
| AuthenTec                  | 4         | 21.05%  |
| Upek                       | 2         | 10.53%  |
| Synaptics                  | 2         | 10.53%  |
| Shenzhen Goodix Technology | 2         | 10.53%  |
| LighTuning Technology      | 2         | 10.53%  |
| Samsung Electronics        | 1         | 5.26%   |
| Focal-systems.Corp         | 1         | 5.26%   |
| Elan Microelectronics      | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 10.53%  |
| Shenzhen Goodix  Fingerprint Device                    | 2         | 10.53%  |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 10.53%  |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 5.26%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 5.26%   |
| Validity Sensors Synaptics WBDI                        | 1         | 5.26%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 5.26%   |
| Synaptics WBDI                                         | 1         | 5.26%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 5.26%   |
| Samsung Fingerprint Device                             | 1         | 5.26%   |
| LighTuning Fingerprint Reader                          | 1         | 5.26%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 5.26%   |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 5.26%   |
| Elan ELAN:Fingerprint                                  | 1         | 5.26%   |
| AuthenTec Fingerprint Sensor                           | 1         | 5.26%   |
| AuthenTec AES1600                                      | 1         | 5.26%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 40%     |
| Alcor Micro | 3         | 30%     |
| O2 Micro    | 2         | 20%     |
| Upek        | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 30%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 20%     |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 20%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 10%     |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 10%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 180       | 72.87%  |
| 1     | 56        | 22.67%  |
| 2     | 10        | 4.05%   |
| 3     | 1         | 0.4%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 21        | 26.92%  |
| Fingerprint reader       | 19        | 24.36%  |
| Net/wireless             | 10        | 12.82%  |
| Chipcard                 | 10        | 12.82%  |
| Storage                  | 4         | 5.13%   |
| Bluetooth                | 3         | 3.85%   |
| Sound                    | 2         | 2.56%   |
| Network                  | 2         | 2.56%   |
| Multimedia controller    | 2         | 2.56%   |
| Unassigned class         | 1         | 1.28%   |
| Net/ethernet             | 1         | 1.28%   |
| Dvb card                 | 1         | 1.28%   |
| Communication controller | 1         | 1.28%   |
| Camera                   | 1         | 1.28%   |

