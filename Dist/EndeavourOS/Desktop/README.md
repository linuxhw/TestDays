EndeavourOS - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------

A project to collect tested hardware configurations for EndeavourOS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

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

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek    | M5A99FX PRO R2.0            | [be76fa91bc](https://linux-hardware.org/?probe=be76fa91bc) | Jan 05, 2022 |
| ASUSTek    | P8Z77-V LX                  | [8e11cb731a](https://linux-hardware.org/?probe=8e11cb731a) | Jan 05, 2022 |
| ASUSTek    | ROG CROSSHAIR VIII DARK ... | [b58f7257b9](https://linux-hardware.org/?probe=b58f7257b9) | Jan 05, 2022 |
| ASUSTek    | ROG STRIX X370-F GAMING     | [aa4f09754b](https://linux-hardware.org/?probe=aa4f09754b) | Jan 04, 2022 |
| ASUSTek    | ROG STRIX X370-F GAMING     | [411cf580b4](https://linux-hardware.org/?probe=411cf580b4) | Jan 04, 2022 |
| Gigabyte   | B550 AORUS ELITE V2         | [c804b37a93](https://linux-hardware.org/?probe=c804b37a93) | Jan 04, 2022 |
| ASRock     | B450M Pro4                  | [9b8e2862e0](https://linux-hardware.org/?probe=9b8e2862e0) | Jan 04, 2022 |
| MSI        | Z490-A PRO                  | [ab40f6782f](https://linux-hardware.org/?probe=ab40f6782f) | Jan 04, 2022 |
| ASUSTek    | ROG STRIX Z370-F GAMING     | [d7f6228561](https://linux-hardware.org/?probe=d7f6228561) | Jan 04, 2022 |
| Positivo   | POS-PIH81DI                 | [c2f06752f5](https://linux-hardware.org/?probe=c2f06752f5) | Jan 04, 2022 |
| ASRock     | B450M Pro4                  | [5ce8d98461](https://linux-hardware.org/?probe=5ce8d98461) | Jan 04, 2022 |
| ASRock     | B450 Gaming-ITX/ac          | [4020ca9754](https://linux-hardware.org/?probe=4020ca9754) | Jan 04, 2022 |
| ASUSTek    | Z97-A                       | [1ebd581629](https://linux-hardware.org/?probe=1ebd581629) | Jan 01, 2022 |
| Gigabyte   | Z97X-Gaming 3               | [89d144f949](https://linux-hardware.org/?probe=89d144f949) | Dec 31, 2021 |
| ASRock     | B450 Steel Legend           | [9a67c15230](https://linux-hardware.org/?probe=9a67c15230) | Dec 31, 2021 |
| ASUSTek    | ROG STRIX B450-F GAMING     | [211b09522f](https://linux-hardware.org/?probe=211b09522f) | Dec 31, 2021 |
| MSI        | B450 TOMAHAWK               | [c85d7c78e7](https://linux-hardware.org/?probe=c85d7c78e7) | Dec 28, 2021 |
| LattePanda | Alpha                       | [497e370fc3](https://linux-hardware.org/?probe=497e370fc3) | Dec 26, 2021 |
| Biostar    | G31-M7 TE                   | [abb80ccd85](https://linux-hardware.org/?probe=abb80ccd85) | Dec 25, 2021 |
| LattePanda | Alpha                       | [442f08d351](https://linux-hardware.org/?probe=442f08d351) | Dec 24, 2021 |
| Gigabyte   | M68M-S2P                    | [c06c8838d2](https://linux-hardware.org/?probe=c06c8838d2) | Dec 24, 2021 |
| Acer       | Aspire XC-1660G V:1.1       | [c460e492aa](https://linux-hardware.org/?probe=c460e492aa) | Dec 23, 2021 |
| Gigabyte   | H110N-CF                    | [17067982ca](https://linux-hardware.org/?probe=17067982ca) | Dec 23, 2021 |
| MSI        | Z87-G41 PC Mate             | [aa7388fdd1](https://linux-hardware.org/?probe=aa7388fdd1) | Dec 21, 2021 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [ac70723f1b](https://linux-hardware.org/?probe=ac70723f1b) | Dec 18, 2021 |
| ASUSTek    | ROG CROSSHAIR VIII DARK ... | [83e6ab3542](https://linux-hardware.org/?probe=83e6ab3542) | Dec 18, 2021 |
| Unknown    | Intel X79                   | [767fb84ac9](https://linux-hardware.org/?probe=767fb84ac9) | Dec 17, 2021 |
| Dell       | 0HD5W2 A01                  | [72329a4b56](https://linux-hardware.org/?probe=72329a4b56) | Dec 17, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [8c9d779e45](https://linux-hardware.org/?probe=8c9d779e45) | Dec 14, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [641af2bfa6](https://linux-hardware.org/?probe=641af2bfa6) | Dec 13, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [fd75c6dc41](https://linux-hardware.org/?probe=fd75c6dc41) | Dec 13, 2021 |
| ASUSTek    | ProArt X570-CREATOR WIFI    | [bdfec258d5](https://linux-hardware.org/?probe=bdfec258d5) | Dec 12, 2021 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [9fce8b9430](https://linux-hardware.org/?probe=9fce8b9430) | Dec 12, 2021 |
| Gigabyte   | B550M AORUS PRO             | [d1e767dfde](https://linux-hardware.org/?probe=d1e767dfde) | Dec 11, 2021 |
| ASUSTek    | PRIME B350-PLUS             | [96e7ac029b](https://linux-hardware.org/?probe=96e7ac029b) | Dec 10, 2021 |
| Gigabyte   | X570 AORUS ELITE            | [78c796c1fc](https://linux-hardware.org/?probe=78c796c1fc) | Dec 02, 2021 |
| MSI        | B350 PC MATE                | [7fbe80215d](https://linux-hardware.org/?probe=7fbe80215d) | Nov 24, 2021 |
| Gigabyte   | B560M DS3H                  | [89ea080ce0](https://linux-hardware.org/?probe=89ea080ce0) | Nov 20, 2021 |
| ASUSTek    | Z87-DELUXE                  | [b858dc4d83](https://linux-hardware.org/?probe=b858dc4d83) | Nov 18, 2021 |
| Gigabyte   | B560M DS3H                  | [505925412f](https://linux-hardware.org/?probe=505925412f) | Nov 18, 2021 |
| Gigabyte   | Z77X-D3H                    | [be03431631](https://linux-hardware.org/?probe=be03431631) | Nov 15, 2021 |
| ASUSTek    | K30AD_M31AD_M51AD_M32AD     | [7ebeace900](https://linux-hardware.org/?probe=7ebeace900) | Nov 13, 2021 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [dfe40a023a](https://linux-hardware.org/?probe=dfe40a023a) | Nov 12, 2021 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [1336c9e31c](https://linux-hardware.org/?probe=1336c9e31c) | Nov 12, 2021 |
| Gigabyte   | GA-78LMT-USB3               | [1cfd4ee9f9](https://linux-hardware.org/?probe=1cfd4ee9f9) | Nov 11, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [c9e5138184](https://linux-hardware.org/?probe=c9e5138184) | Nov 07, 2021 |
| ASUSTek    | Maximus VIII HERO           | [22ce2703b9](https://linux-hardware.org/?probe=22ce2703b9) | Nov 07, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [5d0bad7c15](https://linux-hardware.org/?probe=5d0bad7c15) | Nov 06, 2021 |
| ASRock     | H310CM-DVS                  | [79e6ef3655](https://linux-hardware.org/?probe=79e6ef3655) | Oct 29, 2021 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [36b667da98](https://linux-hardware.org/?probe=36b667da98) | Oct 29, 2021 |
| ASRock     | H310CM-DVS                  | [6db3b9d661](https://linux-hardware.org/?probe=6db3b9d661) | Oct 29, 2021 |
| Gigabyte   | B450 GAMING X               | [cb03c494cb](https://linux-hardware.org/?probe=cb03c494cb) | Oct 15, 2021 |
| ASRock     | B550M Pro4                  | [87ab64b604](https://linux-hardware.org/?probe=87ab64b604) | Oct 14, 2021 |
| Gigabyte   | X570 AORUS ULTRA            | [cef9098008](https://linux-hardware.org/?probe=cef9098008) | Oct 14, 2021 |
| Gigabyte   | X570 AORUS ULTRA            | [718bd26737](https://linux-hardware.org/?probe=718bd26737) | Oct 14, 2021 |
| UMAX       | J42 Nano                    | [fd40a94769](https://linux-hardware.org/?probe=fd40a94769) | Oct 09, 2021 |
| Gigabyte   | B85M-HD3                    | [cc7d0245a7](https://linux-hardware.org/?probe=cc7d0245a7) | Oct 09, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [849ca2da3d](https://linux-hardware.org/?probe=849ca2da3d) | Oct 06, 2021 |
| Gigabyte   | B550 VISION D               | [e8a2ba9952](https://linux-hardware.org/?probe=e8a2ba9952) | Oct 03, 2021 |
| MSI        | G41M-P33 Combo              | [ec8e63e96e](https://linux-hardware.org/?probe=ec8e63e96e) | Oct 01, 2021 |
| Gigabyte   | B250M-DS3H-CF               | [62558ba69c](https://linux-hardware.org/?probe=62558ba69c) | Sep 29, 2021 |
| Gigabyte   | H110M-S2-CF                 | [a20f426eed](https://linux-hardware.org/?probe=a20f426eed) | Sep 25, 2021 |
| Gigabyte   | B450M DS3H-CF               | [35cbc8e5b5](https://linux-hardware.org/?probe=35cbc8e5b5) | Sep 19, 2021 |
| Gigabyte   | B450M DS3H-CF               | [860fb3dc8c](https://linux-hardware.org/?probe=860fb3dc8c) | Sep 19, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [8ffa4dd273](https://linux-hardware.org/?probe=8ffa4dd273) | Sep 18, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [60555ce93d](https://linux-hardware.org/?probe=60555ce93d) | Sep 16, 2021 |
| MSI        | B450M PRO-VDH MAX           | [33cee010e8](https://linux-hardware.org/?probe=33cee010e8) | Sep 12, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [c06b4b30a0](https://linux-hardware.org/?probe=c06b4b30a0) | Sep 10, 2021 |
| MSI        | B450-A PRO MAX              | [12cf057e04](https://linux-hardware.org/?probe=12cf057e04) | Sep 02, 2021 |
| Intel      | DH55HC AAE70933-504         | [2880661f42](https://linux-hardware.org/?probe=2880661f42) | Aug 30, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [bcd0cff6bb](https://linux-hardware.org/?probe=bcd0cff6bb) | Aug 29, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [292b3048d8](https://linux-hardware.org/?probe=292b3048d8) | Aug 26, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [6b88068dc4](https://linux-hardware.org/?probe=6b88068dc4) | Aug 26, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [504260a3f8](https://linux-hardware.org/?probe=504260a3f8) | Aug 25, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [1c75e967eb](https://linux-hardware.org/?probe=1c75e967eb) | Aug 24, 2021 |
| HP         | 8906 SMVB                   | [ea16eee1c7](https://linux-hardware.org/?probe=ea16eee1c7) | Aug 24, 2021 |
| MSI        | B450 TOMAHAWK MAX           | [2e16baa112](https://linux-hardware.org/?probe=2e16baa112) | Aug 14, 2021 |
| Gigabyte   | P35-DS3R                    | [421cd7ce36](https://linux-hardware.org/?probe=421cd7ce36) | Aug 09, 2021 |
| MSI        | B450M PRO-VDH MAX           | [fe3d61f4d6](https://linux-hardware.org/?probe=fe3d61f4d6) | Aug 09, 2021 |
| MSI        | B450M PRO-VDH MAX           | [8e9d51a941](https://linux-hardware.org/?probe=8e9d51a941) | Aug 07, 2021 |
| Dell       | 0K240Y A01                  | [5cc92cb5ac](https://linux-hardware.org/?probe=5cc92cb5ac) | Aug 04, 2021 |
| ASUSTek    | ROG STRIX B550-I GAMING     | [816edfa4bb](https://linux-hardware.org/?probe=816edfa4bb) | Jul 25, 2021 |
| Gigabyte   | X399 AORUS PRO-CF           | [404eae69f4](https://linux-hardware.org/?probe=404eae69f4) | Jul 14, 2021 |
| Gigabyte   | GA-78LMT-S2P                | [f36328f6b3](https://linux-hardware.org/?probe=f36328f6b3) | Jul 12, 2021 |
| MSI        | MAG X570 TOMAHAWK WIFI      | [14b3d46ef8](https://linux-hardware.org/?probe=14b3d46ef8) | Jul 03, 2021 |
| ASUSTek    | P7H55D-M EVO                | [62f256e36e](https://linux-hardware.org/?probe=62f256e36e) | Jul 03, 2021 |
| ASUSTek    | ROG STRIX Z370-F GAMING     | [487ca6235b](https://linux-hardware.org/?probe=487ca6235b) | Jul 02, 2021 |
| Gigabyte   | Z97X-Gaming 5               | [625c876e08](https://linux-hardware.org/?probe=625c876e08) | Jun 30, 2021 |
| ASUSTek    | ROG STRIX B550-F GAMING     | [10c5bbf0f8](https://linux-hardware.org/?probe=10c5bbf0f8) | Jun 18, 2021 |
| ASUSTek    | F1A55-M LX                  | [9e7c39435d](https://linux-hardware.org/?probe=9e7c39435d) | Jun 13, 2021 |
| Gigabyte   | X570 I AORUS PRO WIFI       | [ed31182c51](https://linux-hardware.org/?probe=ed31182c51) | Jun 07, 2021 |
| Gigabyte   | B550 AORUS ELITE V2         | [585db3001d](https://linux-hardware.org/?probe=585db3001d) | May 19, 2021 |
| HP         | 2B36                        | [62135f1e45](https://linux-hardware.org/?probe=62135f1e45) | May 19, 2021 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [fec75a202e](https://linux-hardware.org/?probe=fec75a202e) | May 19, 2021 |
| ASRock     | A300M-STX                   | [fc96347868](https://linux-hardware.org/?probe=fc96347868) | May 12, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [dd68978e2b](https://linux-hardware.org/?probe=dd68978e2b) | Apr 28, 2021 |
| Lenovo     | ThinkStation C20 426593U    | [7ee064e334](https://linux-hardware.org/?probe=7ee064e334) | Apr 27, 2021 |
| ASUSTek    | STRIX B250F GAMING          | [8276e1fb2f](https://linux-hardware.org/?probe=8276e1fb2f) | Apr 20, 2021 |
| ASUSTek    | K30AD_M31AD_M51AD_M32AD     | [cf4d5786e5](https://linux-hardware.org/?probe=cf4d5786e5) | Apr 19, 2021 |
| Lenovo     | SHARKBAY NOK                | [0685ce717e](https://linux-hardware.org/?probe=0685ce717e) | Apr 16, 2021 |
| Gigabyte   | B550M AORUS PRO             | [a635a3acb3](https://linux-hardware.org/?probe=a635a3acb3) | Apr 13, 2021 |
| Gigabyte   | B550M AORUS PRO             | [650e9efbab](https://linux-hardware.org/?probe=650e9efbab) | Apr 13, 2021 |
| MSI        | B450 TOMAHAWK MAX           | [e08e82478f](https://linux-hardware.org/?probe=e08e82478f) | Apr 12, 2021 |
| Gigabyte   | B450 AORUS M                | [d53c2a8b0e](https://linux-hardware.org/?probe=d53c2a8b0e) | Apr 11, 2021 |
| Dell       | 0080PM A00                  | [efc9497e6d](https://linux-hardware.org/?probe=efc9497e6d) | Apr 08, 2021 |
| MSI        | MAG B550 TOMAHAWK           | [63e7ed5aa3](https://linux-hardware.org/?probe=63e7ed5aa3) | Apr 07, 2021 |
| Lenovo     | 36EB NOK                    | [2c6f4de8b9](https://linux-hardware.org/?probe=2c6f4de8b9) | Apr 06, 2021 |
| MSI        | X370 GAMING PRO CARBON      | [08f8da317e](https://linux-hardware.org/?probe=08f8da317e) | Apr 03, 2021 |
| Gigabyte   | Z390 GAMING SLI-CF          | [90f906f5f9](https://linux-hardware.org/?probe=90f906f5f9) | Mar 31, 2021 |
| Gigabyte   | Z390 GAMING SLI-CF          | [b2fa0502d0](https://linux-hardware.org/?probe=b2fa0502d0) | Mar 31, 2021 |
| Samsung    | DT_DM500T8A SAMSUNG_SW_R... | [dccf080cd2](https://linux-hardware.org/?probe=dccf080cd2) | Mar 26, 2021 |
| Lenovo     | 3111 SDK0J40697 WIN 3305... | [31baa57d40](https://linux-hardware.org/?probe=31baa57d40) | Mar 17, 2021 |
| MSI        | X370 GAMING PRO CARBON      | [7c5776953c](https://linux-hardware.org/?probe=7c5776953c) | Mar 15, 2021 |
| Gigabyte   | B550M AORUS PRO             | [41de0a7ee7](https://linux-hardware.org/?probe=41de0a7ee7) | Mar 08, 2021 |
| ASUSTek    | TUF GAMING X570-PLUS        | [f9b4d57c67](https://linux-hardware.org/?probe=f9b4d57c67) | Feb 18, 2021 |
| MSI        | Z87-G45 GAMING              | [67ca38a642](https://linux-hardware.org/?probe=67ca38a642) | Feb 12, 2021 |
| MSI        | Z87-G45 GAMING              | [e6937666ae](https://linux-hardware.org/?probe=e6937666ae) | Feb 11, 2021 |
| ASRock     | B550 Phantom Gaming 4       | [e11200bd19](https://linux-hardware.org/?probe=e11200bd19) | Feb 10, 2021 |
| ASUSTek    | H81-PLUS                    | [75fc956099](https://linux-hardware.org/?probe=75fc956099) | Feb 10, 2021 |
| MSI        | MAG X570 TOMAHAWK WIFI      | [cef326fa21](https://linux-hardware.org/?probe=cef326fa21) | Feb 08, 2021 |
| ASRock     | B550M Steel Legend          | [335242ec06](https://linux-hardware.org/?probe=335242ec06) | Jan 20, 2021 |
| ASUSTek    | PRIME X470-PRO              | [396227c9b5](https://linux-hardware.org/?probe=396227c9b5) | Jan 14, 2021 |
| Gigabyte   | X58A-UD3R                   | [3d8c62e8fe](https://linux-hardware.org/?probe=3d8c62e8fe) | Jan 04, 2021 |
| ASUSTek    | Z87-PRO                     | [2ab19967fa](https://linux-hardware.org/?probe=2ab19967fa) | Dec 30, 2020 |
| ASUSTek    | Maximus VIII HERO           | [4d27980548](https://linux-hardware.org/?probe=4d27980548) | Dec 27, 2020 |
| ASUSTek    | Maximus VIII HERO           | [08895b552f](https://linux-hardware.org/?probe=08895b552f) | Dec 27, 2020 |
| HP         | 1905                        | [63771015f5](https://linux-hardware.org/?probe=63771015f5) | Dec 22, 2020 |
| Gigabyte   | H110M-S2-CF                 | [93308d477a](https://linux-hardware.org/?probe=93308d477a) | Dec 18, 2020 |
| Gigabyte   | B550M AORUS PRO             | [8a8d0b8b26](https://linux-hardware.org/?probe=8a8d0b8b26) | Dec 13, 2020 |
| Gigabyte   | X58A-UD3R                   | [a138dbf3ac](https://linux-hardware.org/?probe=a138dbf3ac) | Dec 08, 2020 |
| ASUSTek    | TUF X470-PLUS GAMING        | [00dc0236a1](https://linux-hardware.org/?probe=00dc0236a1) | Dec 07, 2020 |
| Fujitsu    | D2778-B1 S26361-D2778-B1    | [0ffe9c1f28](https://linux-hardware.org/?probe=0ffe9c1f28) | Nov 27, 2020 |
| Lenovo     | 36EB SDK0J40700 WIN 3258... | [34e2c6b1de](https://linux-hardware.org/?probe=34e2c6b1de) | Nov 21, 2020 |
| Dell       | 0KRC95 A02                  | [af91587001](https://linux-hardware.org/?probe=af91587001) | Nov 19, 2020 |
| ASRock     | Z77 Extreme4                | [3de701fc00](https://linux-hardware.org/?probe=3de701fc00) | Nov 12, 2020 |
| ASRock     | Z77 Extreme4                | [64d986c0ec](https://linux-hardware.org/?probe=64d986c0ec) | Nov 12, 2020 |
| Dell       | 0KRC95 A02                  | [6471eccd57](https://linux-hardware.org/?probe=6471eccd57) | Nov 11, 2020 |
| ASUSTek    | ROG STRIX B550-F GAMING     | [7a14486580](https://linux-hardware.org/?probe=7a14486580) | Nov 04, 2020 |
| Gigabyte   | H270-HD3-CF                 | [fa6d538a50](https://linux-hardware.org/?probe=fa6d538a50) | Oct 31, 2020 |
| HP         | 8455                        | [0671b6f4da](https://linux-hardware.org/?probe=0671b6f4da) | Oct 27, 2020 |
| HP         | 8455                        | [e37d606b6b](https://linux-hardware.org/?probe=e37d606b6b) | Oct 26, 2020 |
| Dell       | 0G214D A00                  | [21319d118b](https://linux-hardware.org/?probe=21319d118b) | Oct 25, 2020 |
| MSI        | MS-7366                     | [ada828f120](https://linux-hardware.org/?probe=ada828f120) | Sep 29, 2020 |
| Dell       | 096JG8 A01                  | [a031f4a8a2](https://linux-hardware.org/?probe=a031f4a8a2) | Sep 29, 2020 |
| MSI        | B450 TOMAHAWK MAX           | [ee969068e8](https://linux-hardware.org/?probe=ee969068e8) | Sep 28, 2020 |
| ASUSTek    | ROG STRIX X570-E GAMING     | [a4e794299b](https://linux-hardware.org/?probe=a4e794299b) | Sep 28, 2020 |
| ASUSTek    | P8P67 DELUXE                | [ba15c37977](https://linux-hardware.org/?probe=ba15c37977) | Sep 28, 2020 |
| MSI        | MS-7366                     | [9938e6501b](https://linux-hardware.org/?probe=9938e6501b) | Sep 24, 2020 |
| Gigabyte   | B450 AORUS M                | [34f1896f7e](https://linux-hardware.org/?probe=34f1896f7e) | Sep 23, 2020 |
| Gigabyte   | B550M AORUS PRO             | [17e933a69c](https://linux-hardware.org/?probe=17e933a69c) | Sep 21, 2020 |
| HP         | 1497                        | [7cb2cee563](https://linux-hardware.org/?probe=7cb2cee563) | Sep 19, 2020 |
| Gigabyte   | B550M AORUS PRO             | [50a3035c47](https://linux-hardware.org/?probe=50a3035c47) | Sep 12, 2020 |
| ASUSTek    | ROG STRIX B550-F GAMING     | [3919584d23](https://linux-hardware.org/?probe=3919584d23) | Sep 06, 2020 |
| ASRock     | X470 Gaming-ITX/ac          | [028f3ba060](https://linux-hardware.org/?probe=028f3ba060) | Sep 03, 2020 |
| ASUSTek    | M5A97 R2.0                  | [662f61d283](https://linux-hardware.org/?probe=662f61d283) | Sep 03, 2020 |
| ASUSTek    | ROG CROSSHAIR VIII HERO     | [143c679f1a](https://linux-hardware.org/?probe=143c679f1a) | Sep 03, 2020 |
| ASUSTek    | ROG CROSSHAIR VIII HERO     | [2ab9b15cb6](https://linux-hardware.org/?probe=2ab9b15cb6) | Sep 03, 2020 |
| Gigabyte   | Z170-Gaming K3-CF           | [f70636a60c](https://linux-hardware.org/?probe=f70636a60c) | Sep 02, 2020 |
| ASUSTek    | Z87M-PLUS                   | [844cca1bee](https://linux-hardware.org/?probe=844cca1bee) | Aug 09, 2020 |
| ASUSTek    | PRIME X570-P                | [cb7a700ec4](https://linux-hardware.org/?probe=cb7a700ec4) | Aug 07, 2020 |
| Gigabyte   | B365M DS3H                  | [79c5cea1c1](https://linux-hardware.org/?probe=79c5cea1c1) | Jul 14, 2020 |
| Fujitsu    | D2778-B1 S26361-D2778-B1    | [54774ae912](https://linux-hardware.org/?probe=54774ae912) | Jul 14, 2020 |
| Fujitsu    | D2618-C1 S26361-D2618-C1    | [85295c522b](https://linux-hardware.org/?probe=85295c522b) | Jul 14, 2020 |
| Lenovo     | MAHOBAY NOK                 | [6e3c82fbca](https://linux-hardware.org/?probe=6e3c82fbca) | Jul 13, 2020 |
| Gigabyte   | B365M DS3H                  | [7994cb0fae](https://linux-hardware.org/?probe=7994cb0fae) | Jul 13, 2020 |
| ASUSTek    | Z87M-PLUS                   | [d0c246206e](https://linux-hardware.org/?probe=d0c246206e) | Jul 13, 2020 |
| MSI        | MPG X570 GAMING PLUS        | [5ed412893a](https://linux-hardware.org/?probe=5ed412893a) | Jul 12, 2020 |
| Gigabyte   | B365M DS3H                  | [8baccc57ec](https://linux-hardware.org/?probe=8baccc57ec) | Jul 12, 2020 |
| Gigabyte   | X570 AORUS MASTER           | [b81603bb8b](https://linux-hardware.org/?probe=b81603bb8b) | Jul 12, 2020 |
| MSI        | B450-A PRO MAX              | [22ee76b578](https://linux-hardware.org/?probe=22ee76b578) | Jun 29, 2020 |
| ASUSTek    | TUF GAMING X570-PLUS        | [eb81165361](https://linux-hardware.org/?probe=eb81165361) | May 31, 2020 |
| Biostar    | G31-M7 TE                   | [0ae18cfc51](https://linux-hardware.org/?probe=0ae18cfc51) | May 05, 2020 |
| Gigabyte   | B85M-D3H                    | [adba7e2f11](https://linux-hardware.org/?probe=adba7e2f11) | Apr 24, 2020 |
| ASUSTek    | PRIME A320M-K               | [0b8f4015fa](https://linux-hardware.org/?probe=0b8f4015fa) | Feb 19, 2020 |
| Gigabyte   | B450M S2H                   | [5a1d01743b](https://linux-hardware.org/?probe=5a1d01743b) | Feb 12, 2020 |
| ASUSTek    | PRIME A320M-K               | [32f5e3b842](https://linux-hardware.org/?probe=32f5e3b842) | Nov 21, 2019 |
| ASUSTek    | PRIME A320M-K               | [4d0de4b06b](https://linux-hardware.org/?probe=4d0de4b06b) | Nov 19, 2019 |
| ASUSTek    | PRIME A320M-K               | [791bd283a6](https://linux-hardware.org/?probe=791bd283a6) | Nov 18, 2019 |
| ASUSTek    | PRIME A320M-K               | [eb3f07de2a](https://linux-hardware.org/?probe=eb3f07de2a) | Nov 18, 2019 |
| ASUSTek    | PRIME A320M-K               | [d95c487c0a](https://linux-hardware.org/?probe=d95c487c0a) | Nov 18, 2019 |
| ASUSTek    | PRIME A320M-K               | [c75091b3fd](https://linux-hardware.org/?probe=c75091b3fd) | Nov 18, 2019 |
| ASUSTek    | PRIME A320M-K               | [53dcfb848c](https://linux-hardware.org/?probe=53dcfb848c) | Nov 18, 2019 |
| ASUSTek    | PRIME A320M-K               | [50ea35444e](https://linux-hardware.org/?probe=50ea35444e) | Nov 17, 2019 |
| ASUSTek    | PRIME A320M-K               | [42a25ee1f6](https://linux-hardware.org/?probe=42a25ee1f6) | Nov 08, 2019 |
| ASUSTek    | PRIME A320M-K               | [612f3a46e8](https://linux-hardware.org/?probe=612f3a46e8) | Nov 08, 2019 |
| ASUSTek    | PRIME A320M-K               | [da3b984be5](https://linux-hardware.org/?probe=da3b984be5) | Nov 07, 2019 |
| ASUSTek    | PRIME A320M-K               | [587cf1258f](https://linux-hardware.org/?probe=587cf1258f) | Nov 07, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.15.12-arch1-1      | 7        | 5.04%   |
| 5.7.7-arch1-1        | 6        | 4.32%   |
| 5.15.7-arch1-1       | 4        | 2.88%   |
| 5.11.11-arch1-1      | 4        | 2.88%   |
| 5.15.12-zen1-1-zen   | 3        | 2.16%   |
| 5.15.10-arch1-1      | 3        | 2.16%   |
| 5.14.9-arch2-1       | 3        | 2.16%   |
| 5.14.8-arch1-1       | 3        | 2.16%   |
| 5.10.88-2-lts        | 3        | 2.16%   |
| 5.9.14-arch1-1       | 2        | 1.44%   |
| 5.9.12-arch1-1       | 2        | 1.44%   |
| 5.9.1-arch1-1        | 2        | 1.44%   |
| 5.8.11-arch1-1       | 2        | 1.44%   |
| 5.8.10-arch1-1       | 2        | 1.44%   |
| 5.15.8-arch1-1       | 2        | 1.44%   |
| 5.15.11-arch2-1      | 2        | 1.44%   |
| 5.14.2-arch1-2       | 2        | 1.44%   |
| 5.14.16-arch1-1      | 2        | 1.44%   |
| 5.14.14-arch1-1      | 2        | 1.44%   |
| 5.12.15-arch1-1      | 2        | 1.44%   |
| 5.11.6-arch1-1       | 2        | 1.44%   |
| 5.11.15-arch1-2      | 2        | 1.44%   |
| 5.11.13-arch1-1      | 2        | 1.44%   |
| 5.9.9-arch1-1        | 1        | 0.72%   |
| 5.9.8-zen1-1-zen     | 1        | 0.72%   |
| 5.9.6-zen1-1-zen     | 1        | 0.72%   |
| 5.9.2-arch1-1        | 1        | 0.72%   |
| 5.9.13-arch1-1       | 1        | 0.72%   |
| 5.9.10-arch1-1       | 1        | 0.72%   |
| 5.9.1-6-tkg-bmq      | 1        | 0.72%   |
| 5.9.0-rc3-1-mainline | 1        | 0.72%   |
| 5.8.8-arch1-1        | 1        | 0.72%   |
| 5.8.5-zen1-1-zen     | 1        | 0.72%   |
| 5.8.5-arch1-1        | 1        | 0.72%   |
| 5.8.5-8-tkg-pds      | 1        | 0.72%   |
| 5.8.5-8-tkg-bmq      | 1        | 0.72%   |
| 5.8.12-arch1-1       | 1        | 0.72%   |
| 5.7.8-arch1-1        | 1        | 0.72%   |
| 5.7.6-arch1-1        | 1        | 0.72%   |
| 5.7.12-zen1-1-zen    | 1        | 0.72%   |
| 5.7.12-arch1-1       | 1        | 0.72%   |
| 5.6.6-arch1-1        | 1        | 0.72%   |
| 5.6.15-arch1-1       | 1        | 0.72%   |
| 5.6.10-arch1-1       | 1        | 0.72%   |
| 5.5.4-zen1-1-zen     | 1        | 0.72%   |
| 5.5.2-arch2-2        | 1        | 0.72%   |
| 5.4.90-1-lts         | 1        | 0.72%   |
| 5.15.7-zen1-1-zen    | 1        | 0.72%   |
| 5.15.6-xanmod2-2     | 1        | 0.72%   |
| 5.15.4-arch1-1       | 1        | 0.72%   |
| 5.15.3-xanmod1-1     | 1        | 0.72%   |
| 5.15.2-arch1-1       | 1        | 0.72%   |
| 5.15.12-231-tkg-cfs  | 1        | 0.72%   |
| 5.15.11-zen1-1-zen   | 1        | 0.72%   |
| 5.15.0-arch1-1       | 1        | 0.72%   |
| 5.14.7-arch1-1       | 1        | 0.72%   |
| 5.14.6-arch1-1       | 1        | 0.72%   |
| 5.14.18-lqx1-1-lqx   | 1        | 0.72%   |
| 5.14.15-arch1-1      | 1        | 0.72%   |
| 5.14.12-arch1-1      | 1        | 0.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.12 | 11       | 7.91%   |
| 5.7.7   | 6        | 4.32%   |
| 5.15.7  | 5        | 3.6%    |
| 5.8.5   | 4        | 2.88%   |
| 5.11.11 | 4        | 2.88%   |
| 5.10.88 | 4        | 2.88%   |
| 5.9.1   | 3        | 2.16%   |
| 5.15.11 | 3        | 2.16%   |
| 5.15.10 | 3        | 2.16%   |
| 5.14.9  | 3        | 2.16%   |
| 5.14.8  | 3        | 2.16%   |
| 5.12.15 | 3        | 2.16%   |
| 5.9.14  | 2        | 1.44%   |
| 5.9.12  | 2        | 1.44%   |
| 5.8.11  | 2        | 1.44%   |
| 5.8.10  | 2        | 1.44%   |
| 5.7.12  | 2        | 1.44%   |
| 5.15.8  | 2        | 1.44%   |
| 5.14.2  | 2        | 1.44%   |
| 5.14.16 | 2        | 1.44%   |
| 5.14.14 | 2        | 1.44%   |
| 5.14.11 | 2        | 1.44%   |
| 5.13.13 | 2        | 1.44%   |
| 5.12.5  | 2        | 1.44%   |
| 5.12.4  | 2        | 1.44%   |
| 5.12.14 | 2        | 1.44%   |
| 5.11.6  | 2        | 1.44%   |
| 5.11.15 | 2        | 1.44%   |
| 5.11.13 | 2        | 1.44%   |
| 5.9.9   | 1        | 0.72%   |
| 5.9.8   | 1        | 0.72%   |
| 5.9.6   | 1        | 0.72%   |
| 5.9.2   | 1        | 0.72%   |
| 5.9.13  | 1        | 0.72%   |
| 5.9.10  | 1        | 0.72%   |
| 5.9.0   | 1        | 0.72%   |
| 5.8.8   | 1        | 0.72%   |
| 5.8.12  | 1        | 0.72%   |
| 5.7.8   | 1        | 0.72%   |
| 5.7.6   | 1        | 0.72%   |
| 5.6.6   | 1        | 0.72%   |
| 5.6.15  | 1        | 0.72%   |
| 5.6.10  | 1        | 0.72%   |
| 5.5.4   | 1        | 0.72%   |
| 5.5.2   | 1        | 0.72%   |
| 5.4.90  | 1        | 0.72%   |
| 5.15.6  | 1        | 0.72%   |
| 5.15.4  | 1        | 0.72%   |
| 5.15.3  | 1        | 0.72%   |
| 5.15.2  | 1        | 0.72%   |
| 5.15.0  | 1        | 0.72%   |
| 5.14.7  | 1        | 0.72%   |
| 5.14.6  | 1        | 0.72%   |
| 5.14.18 | 1        | 0.72%   |
| 5.14.15 | 1        | 0.72%   |
| 5.14.12 | 1        | 0.72%   |
| 5.13.9  | 1        | 0.72%   |
| 5.13.8  | 1        | 0.72%   |
| 5.13.7  | 1        | 0.72%   |
| 5.13.12 | 1        | 0.72%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 28       | 20.9%   |
| 5.14    | 18       | 13.43%  |
| 5.9     | 14       | 10.45%  |
| 5.11    | 14       | 10.45%  |
| 5.10    | 14       | 10.45%  |
| 5.12    | 13       | 9.7%    |
| 5.8     | 10       | 7.46%   |
| 5.7     | 9        | 6.72%   |
| 5.13    | 7        | 5.22%   |
| 5.6     | 3        | 2.24%   |
| 5.5     | 2        | 1.49%   |
| 5.4     | 1        | 0.75%   |
| Unknown | 1        | 0.75%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 120      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| KDE5            | 41       | 32.03%  |
| GNOME           | 24       | 18.75%  |
| XFCE            | 23       | 17.97%  |
| KDE             | 11       | 8.59%   |
| X-Cinnamon      | 6        | 4.69%   |
| i3              | 5        | 3.91%   |
| Budgie          | 4        | 3.13%   |
| Cinnamon        | 3        | 2.34%   |
| sway            | 2        | 1.56%   |
| MATE            | 2        | 1.56%   |
| LXQt            | 2        | 1.56%   |
| Unknown         | 2        | 1.56%   |
| herbstluftwm    | 1        | 0.78%   |
| GNOME Flashback | 1        | 0.78%   |
| awesome         | 1        | 0.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 109      | 86.51%  |
| Wayland | 12       | 9.52%   |
| Tty     | 3        | 2.38%   |
| Web     | 1        | 0.79%   |
| Unknown | 1        | 0.79%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 35       | 28.46%  |
| LightDM | 28       | 22.76%  |
| Unknown | 27       | 21.95%  |
| TDM     | 20       | 16.26%  |
| GDM     | 13       | 10.57%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 52       | 43.33%  |
| de_DE   | 14       | 11.67%  |
| en_GB   | 11       | 9.17%   |
| it_IT   | 6        | 5%      |
| pl_PL   | 4        | 3.33%   |
| en_CA   | 4        | 3.33%   |
| fr_FR   | 3        | 2.5%    |
| es_AR   | 3        | 2.5%    |
| ru_RU   | 2        | 1.67%   |
| pt_BR   | 2        | 1.67%   |
| nl_NL   | 2        | 1.67%   |
| es_MX   | 2        | 1.67%   |
| sv_SE   | 1        | 0.83%   |
| sl_SI   | 1        | 0.83%   |
| nl_BE   | 1        | 0.83%   |
| es_GT   | 1        | 0.83%   |
| es_ES   | 1        | 0.83%   |
| es_CR   | 1        | 0.83%   |
| en_ZA   | 1        | 0.83%   |
| en_SG   | 1        | 0.83%   |
| en_IN   | 1        | 0.83%   |
| en_FI   | 1        | 0.83%   |
| en_DK   | 1        | 0.83%   |
| en_AU   | 1        | 0.83%   |
| de_AT   | 1        | 0.83%   |
| cs_CZ   | 1        | 0.83%   |
| Unknown | 1        | 0.83%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 77       | 63.11%  |
| BIOS | 45       | 36.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 85       | 70.83%  |
| Btrfs   | 32       | 26.67%  |
| Xfs     | 1        | 0.83%   |
| Overlay | 1        | 0.83%   |
| F2fs    | 1        | 0.83%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 84       | 69.42%  |
| Unknown | 28       | 23.14%  |
| MBR     | 9        | 7.44%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 94       | 77.69%  |
| Yes       | 27       | 22.31%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 67       | 55.83%  |
| Yes       | 53       | 44.17%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 35       | 29.17%  |
| Gigabyte Technology | 32       | 26.67%  |
| MSI                 | 18       | 15%     |
| ASRock              | 9        | 7.5%    |
| Lenovo              | 6        | 5%      |
| Dell                | 5        | 4.17%   |
| Hewlett-Packard     | 4        | 3.33%   |
| Fujitsu             | 2        | 1.67%   |
| Biostar             | 2        | 1.67%   |
| UMAX                | 1        | 0.83%   |
| Samsung Electronics | 1        | 0.83%   |
| Positivo            | 1        | 0.83%   |
| LattePanda          | 1        | 0.83%   |
| Intel               | 1        | 0.83%   |
| Acer                | 1        | 0.83%   |
| Unknown             | 1        | 0.83%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| ASUS All Series                        | 5        | 4.17%   |
| MSI MS-7C02                            | 4        | 3.33%   |
| ASUS ROG STRIX X570-E GAMING           | 4        | 3.33%   |
| MSI MS-7C84                            | 2        | 1.67%   |
| MSI MS-7B86                            | 2        | 1.67%   |
| Gigabyte H110M-S2                      | 2        | 1.67%   |
| Gigabyte B550M AORUS PRO               | 2        | 1.67%   |
| Gigabyte B550 AORUS ELITE V2           | 2        | 1.67%   |
| Biostar G31-M7 TE                      | 2        | 1.67%   |
| ASUS TUF GAMING X570-PLUS              | 2        | 1.67%   |
| ASUS ROG CROSSHAIR VIII DARK HERO      | 2        | 1.67%   |
| ASUS K30AD_M31AD_M51AD                 | 2        | 1.67%   |
| UMAX J42 Nano                          | 1        | 0.83%   |
| Samsung 500T8A/500S8A/500T9A/500S9A    | 1        | 0.83%   |
| Positivo POS-PIH81DI                   | 1        | 0.83%   |
| MSI MS-7C91                            | 1        | 0.83%   |
| MSI MS-7C75                            | 1        | 0.83%   |
| MSI MS-7C37                            | 1        | 0.83%   |
| MSI MS-7A38                            | 1        | 0.83%   |
| MSI MS-7A34                            | 1        | 0.83%   |
| MSI MS-7A32                            | 1        | 0.83%   |
| MSI MS-7850                            | 1        | 0.83%   |
| MSI MS-7821                            | 1        | 0.83%   |
| MSI MS-7592                            | 1        | 0.83%   |
| MSI MS-7366                            | 1        | 0.83%   |
| Lenovo ThinkStation C20 426593U        | 1        | 0.83%   |
| Lenovo ThinkCentre M93p 10AAS03T00     | 1        | 0.83%   |
| Lenovo ThinkCentre M92p 32383L6        | 1        | 0.83%   |
| Lenovo ThinkCentre M710q 10MR0009US    | 1        | 0.83%   |
| Lenovo IdeaCentre 510-15ICB 90HU002QGE | 1        | 0.83%   |
| Lenovo IdeaCentre 510-15ICB 90HU002JSP | 1        | 0.83%   |
| LattePanda Alpha                       | 1        | 0.83%   |
| Intel DH55HC AAE70933-504              | 1        | 0.83%   |
| HP Z230 Tower Workstation              | 1        | 0.83%   |
| HP Z2 Tower G4 Workstation             | 1        | 0.83%   |
| HP Pavilion Gaming Desktop TG01-2xxx   | 1        | 0.83%   |
| HP 700-502ng                           | 1        | 0.83%   |
| Gigabyte Z97X-Gaming 5                 | 1        | 0.83%   |
| Gigabyte Z97X-Gaming 3                 | 1        | 0.83%   |
| Gigabyte Z77X-D3H                      | 1        | 0.83%   |
| Gigabyte Z390 GAMING SLI               | 1        | 0.83%   |
| Gigabyte Z170-Gaming K3                | 1        | 0.83%   |
| Gigabyte X58A-UD3R                     | 1        | 0.83%   |
| Gigabyte X570 I AORUS PRO WIFI         | 1        | 0.83%   |
| Gigabyte X570 AORUS ULTRA              | 1        | 0.83%   |
| Gigabyte X570 AORUS MASTER             | 1        | 0.83%   |
| Gigabyte X570 AORUS ELITE              | 1        | 0.83%   |
| Gigabyte X399 AORUS PRO                | 1        | 0.83%   |
| Gigabyte P35-DS3R                      | 1        | 0.83%   |
| Gigabyte M68M-S2P                      | 1        | 0.83%   |
| Gigabyte H270-HD3                      | 1        | 0.83%   |
| Gigabyte H110N                         | 1        | 0.83%   |
| Gigabyte GA-78LMT-S2P                  | 1        | 0.83%   |
| Gigabyte B85M-HD3                      | 1        | 0.83%   |
| Gigabyte B85M-D3H                      | 1        | 0.83%   |
| Gigabyte B560M DS3H                    | 1        | 0.83%   |
| Gigabyte B550 VISION D                 | 1        | 0.83%   |
| Gigabyte B450M S2H                     | 1        | 0.83%   |
| Gigabyte B450M DS3H                    | 1        | 0.83%   |
| Gigabyte B450 GAMING X                 | 1        | 0.83%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Desktops | Percent |
|-----------------------|----------|---------|
| ASUS ROG              | 12       | 10%     |
| ASUS All              | 5        | 4.17%   |
| MSI MS-7C02           | 4        | 3.33%   |
| Gigabyte X570         | 4        | 3.33%   |
| ASUS PRIME            | 4        | 3.33%   |
| Lenovo ThinkCentre    | 3        | 2.5%    |
| Gigabyte B550         | 3        | 2.5%    |
| Dell OptiPlex         | 3        | 2.5%    |
| ASUS TUF              | 3        | 2.5%    |
| MSI MS-7C84           | 2        | 1.67%   |
| MSI MS-7B86           | 2        | 1.67%   |
| Lenovo IdeaCentre     | 2        | 1.67%   |
| Gigabyte Z97X-Gaming  | 2        | 1.67%   |
| Gigabyte H110M-S2     | 2        | 1.67%   |
| Gigabyte B550M        | 2        | 1.67%   |
| Gigabyte B450M        | 2        | 1.67%   |
| Gigabyte B450         | 2        | 1.67%   |
| Fujitsu CELSIUS       | 2        | 1.67%   |
| Biostar G31-M7        | 2        | 1.67%   |
| ASUS K30AD            | 2        | 1.67%   |
| ASRock B550M          | 2        | 1.67%   |
| ASRock B450           | 2        | 1.67%   |
| UMAX J42              | 1        | 0.83%   |
| Samsung 500T8A        | 1        | 0.83%   |
| Positivo POS-PIH81DI  | 1        | 0.83%   |
| MSI MS-7C91           | 1        | 0.83%   |
| MSI MS-7C75           | 1        | 0.83%   |
| MSI MS-7C37           | 1        | 0.83%   |
| MSI MS-7A38           | 1        | 0.83%   |
| MSI MS-7A34           | 1        | 0.83%   |
| MSI MS-7A32           | 1        | 0.83%   |
| MSI MS-7850           | 1        | 0.83%   |
| MSI MS-7821           | 1        | 0.83%   |
| MSI MS-7592           | 1        | 0.83%   |
| MSI MS-7366           | 1        | 0.83%   |
| Lenovo ThinkStation   | 1        | 0.83%   |
| LattePanda Alpha      | 1        | 0.83%   |
| Intel DH55HC          | 1        | 0.83%   |
| HP Z230               | 1        | 0.83%   |
| HP Z2                 | 1        | 0.83%   |
| HP Pavilion           | 1        | 0.83%   |
| HP 700-502ng          | 1        | 0.83%   |
| Gigabyte Z77X-D3H     | 1        | 0.83%   |
| Gigabyte Z390         | 1        | 0.83%   |
| Gigabyte Z170-Gaming  | 1        | 0.83%   |
| Gigabyte X58A-UD3R    | 1        | 0.83%   |
| Gigabyte X399         | 1        | 0.83%   |
| Gigabyte P35-DS3R     | 1        | 0.83%   |
| Gigabyte M68M-S2P     | 1        | 0.83%   |
| Gigabyte H270-HD3     | 1        | 0.83%   |
| Gigabyte H110N        | 1        | 0.83%   |
| Gigabyte GA-78LMT-S2P | 1        | 0.83%   |
| Gigabyte B85M-HD3     | 1        | 0.83%   |
| Gigabyte B85M-D3H     | 1        | 0.83%   |
| Gigabyte B560M        | 1        | 0.83%   |
| Gigabyte B365M        | 1        | 0.83%   |
| Gigabyte B250M-DS3H   | 1        | 0.83%   |
| Dell Wyse             | 1        | 0.83%   |
| Dell Precision        | 1        | 0.83%   |
| ASUS STRIX            | 1        | 0.83%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2021 | 32       | 26.67%  |
| 2019 | 20       | 16.67%  |
| 2020 | 14       | 11.67%  |
| 2018 | 10       | 8.33%   |
| 2014 | 10       | 8.33%   |
| 2013 | 8        | 6.67%   |
| 2015 | 6        | 5%      |
| 2017 | 5        | 4.17%   |
| 2010 | 4        | 3.33%   |
| 2012 | 3        | 2.5%    |
| 2011 | 3        | 2.5%    |
| 2016 | 2        | 1.67%   |
| 2009 | 2        | 1.67%   |
| 2007 | 1        | 0.83%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 120      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 119      | 99.17%  |
| Enabled  | 1        | 0.83%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 120      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 42       | 34.71%  |
| 32.01-64.0  | 28       | 23.14%  |
| 8.01-16.0   | 17       | 14.05%  |
| 24.01-32.0  | 10       | 8.26%   |
| 4.01-8.0    | 9        | 7.44%   |
| 3.01-4.0    | 9        | 7.44%   |
| 64.01-256.0 | 6        | 4.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 4.01-8.0   | 33       | 25.38%  |
| 1.01-2.0   | 32       | 24.62%  |
| 2.01-3.0   | 28       | 21.54%  |
| 3.01-4.0   | 16       | 12.31%  |
| 8.01-16.0  | 15       | 11.54%  |
| 0.51-1.0   | 3        | 2.31%   |
| 16.01-24.0 | 2        | 1.54%   |
| 24.01-32.0 | 1        | 0.77%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 36       | 29.75%  |
| 1      | 24       | 19.83%  |
| 4      | 22       | 18.18%  |
| 3      | 21       | 17.36%  |
| 5      | 12       | 9.92%   |
| 7      | 2        | 1.65%   |
| 6      | 2        | 1.65%   |
| 9      | 1        | 0.83%   |
| 0      | 1        | 0.83%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 93       | 76.86%  |
| Yes       | 28       | 23.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 119      | 99.17%  |
| No        | 1        | 0.83%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 61       | 50.41%  |
| Yes       | 60       | 49.59%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 63       | 52.07%  |
| Yes       | 58       | 47.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 26       | 21.67%  |
| Germany      | 22       | 18.33%  |
| Italy        | 8        | 6.67%   |
| France       | 8        | 6.67%   |
| UK           | 6        | 5%      |
| Poland       | 5        | 4.17%   |
| Netherlands  | 5        | 4.17%   |
| Canada       | 5        | 4.17%   |
| Austria      | 4        | 3.33%   |
| Mexico       | 3        | 2.5%    |
| Brazil       | 3        | 2.5%    |
| Argentina    | 3        | 2.5%    |
| Switzerland  | 2        | 1.67%   |
| Spain        | 2        | 1.67%   |
| Slovenia     | 2        | 1.67%   |
| India        | 2        | 1.67%   |
| Belgium      | 2        | 1.67%   |
| Sweden       | 1        | 0.83%   |
| South Korea  | 1        | 0.83%   |
| South Africa | 1        | 0.83%   |
| Singapore    | 1        | 0.83%   |
| Portugal     | 1        | 0.83%   |
| Guatemala    | 1        | 0.83%   |
| Greece       | 1        | 0.83%   |
| Finland      | 1        | 0.83%   |
| Denmark      | 1        | 0.83%   |
| Czechia      | 1        | 0.83%   |
| Costa Rica   | 1        | 0.83%   |
| Australia    | 1        | 0.83%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                           | Desktops | Percent |
|--------------------------------|----------|---------|
| Berlin                         | 4        | 3.25%   |
| Turin                          | 2        | 1.63%   |
| Seattle                        | 2        | 1.63%   |
| Ottawa                         | 2        | 1.63%   |
| Llanelli                       | 2        | 1.63%   |
| Leipzig                        | 2        | 1.63%   |
| Hamburg                        | 2        | 1.63%   |
| Zurich                         | 1        | 0.81%   |
| Zapopan                        | 1        | 0.81%   |
| Wiesbaden                      | 1        | 0.81%   |
| Whiteville                     | 1        | 0.81%   |
| West Haddon                    | 1        | 0.81%   |
| Washington                     | 1        | 0.81%   |
| Warsaw                         | 1        | 0.81%   |
| Volketswil / Volketswil (Dorf) | 1        | 0.81%   |
| Villa Ballester                | 1        | 0.81%   |
| Vienna                         | 1        | 0.81%   |
| Toronto                        | 1        | 0.81%   |
| Thessaloniki                   | 1        | 0.81%   |
| Tempe                          | 1        | 0.81%   |
| Taby                           | 1        | 0.81%   |
| Sullivan                       | 1        | 0.81%   |
| Stuttgart                      | 1        | 0.81%   |
| Spring                         | 1        | 0.81%   |
| Spijkenisse                    | 1        | 0.81%   |
| Skorcz                         | 1        | 0.81%   |
| Singapore                      | 1        | 0.81%   |
| Sheboygan                      | 1        | 0.81%   |
| Senonches                      | 1        | 0.81%   |
| Santa Clarita                  | 1        | 0.81%   |
| Santa Ana                      | 1        | 0.81%   |
| Sant'Agata de' Goti            | 1        | 0.81%   |
| San Nicolás de los Arroyos    | 1        | 0.81%   |
| Salvador                       | 1        | 0.81%   |
| Rtyne v Podkrkonosi            | 1        | 0.81%   |
| Roden                          | 1        | 0.81%   |
| Ribeir??o das Neves            | 1        | 0.81%   |
| Renton                         | 1        | 0.81%   |
| Reggiolo                       | 1        | 0.81%   |
| Rauma                          | 1        | 0.81%   |
| Ramada                         | 1        | 0.81%   |
| Praia Grande                   | 1        | 0.81%   |
| Paris                          | 1        | 0.81%   |
| Pabianice                      | 1        | 0.81%   |
| Oschatz                        | 1        | 0.81%   |
| Oldenburg                      | 1        | 0.81%   |
| New York                       | 1        | 0.81%   |
| New Delhi                      | 1        | 0.81%   |
| New Bedford                    | 1        | 0.81%   |
| Munich                         | 1        | 0.81%   |
| Montreal                       | 1        | 0.81%   |
| Monrovia                       | 1        | 0.81%   |
| Milan                          | 1        | 0.81%   |
| Miami                          | 1        | 0.81%   |
| Maineville                     | 1        | 0.81%   |
| Madrid                         | 1        | 0.81%   |
| Lyon                           | 1        | 0.81%   |
| Ljubljana                      | 1        | 0.81%   |
| Little Rock                    | 1        | 0.81%   |
| Linz                           | 1        | 0.81%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 52       | 91     | 20.16%  |
| Samsung Electronics | 50       | 91     | 19.38%  |
| Seagate             | 43       | 67     | 16.67%  |
| Crucial             | 18       | 30     | 6.98%   |
| Kingston            | 14       | 28     | 5.43%   |
| Toshiba             | 11       | 15     | 4.26%   |
| SanDisk             | 7        | 9      | 2.71%   |
| Phison              | 6        | 7      | 2.33%   |
| Intel               | 5        | 8      | 1.94%   |
| A-DATA Technology   | 5        | 10     | 1.94%   |
| Hitachi             | 4        | 4      | 1.55%   |
| SPCC                | 3        | 3      | 1.16%   |
| Intenso             | 3        | 3      | 1.16%   |
| Corsair             | 3        | 3      | 1.16%   |
| XPG                 | 2        | 2      | 0.78%   |
| OCZ                 | 2        | 2      | 0.78%   |
| Micron Technology   | 2        | 2      | 0.78%   |
| JMicron             | 2        | 2      | 0.78%   |
| HGST                | 2        | 2      | 0.78%   |
| USB3.1              | 1        | 1      | 0.39%   |
| Unknown             | 1        | 1      | 0.39%   |
| UMAX                | 1        | 1      | 0.39%   |
| Transcend           | 1        | 1      | 0.39%   |
| SK Hynix            | 1        | 1      | 0.39%   |
| Realtek             | 1        | 1      | 0.39%   |
| PNY                 | 1        | 1      | 0.39%   |
| Pioneer             | 1        | 3      | 0.39%   |
| PI-041              | 1        | 1      | 0.39%   |
| Patriot             | 1        | 2      | 0.39%   |
| Netac               | 1        | 1      | 0.39%   |
| Mushkin             | 1        | 1      | 0.39%   |
| MAXTOR              | 1        | 1      | 0.39%   |
| Maxone              | 1        | 1      | 0.39%   |
| Leven               | 1        | 1      | 0.39%   |
| LDLC                | 1        | 1      | 0.39%   |
| KIOXIA              | 1        | 1      | 0.39%   |
| imation             | 1        | 1      | 0.39%   |
| HPE                 | 1        | 1      | 0.39%   |
| Hewlett-Packard     | 1        | 1      | 0.39%   |
| Gigabyte Technology | 1        | 2      | 0.39%   |
| DREVO               | 1        | 1      | 0.39%   |
| China               | 1        | 1      | 0.39%   |
| ASMT                | 1        | 2      | 0.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Samsung SSD 860 EVO 1TB          | 7        | 2.19%   |
| Crucial CT500MX500SSD1 500GB     | 6        | 1.88%   |
| WDC WD10EZEX-00BN5A0 1TB         | 5        | 1.56%   |
| Seagate ST2000DM008-2FR102 2TB   | 5        | 1.56%   |
| Samsung SSD 850 EVO 250GB        | 5        | 1.56%   |
| WDC WD10EZEX-08WN4A0 1TB         | 4        | 1.25%   |
| Seagate ST4000DM004-2CV104 4TB   | 4        | 1.25%   |
| Seagate ST1000DM010-2EP102 1TB   | 4        | 1.25%   |
| Samsung SSD 860 EVO 500GB        | 4        | 1.25%   |
| Samsung SSD 850 EVO 500GB        | 4        | 1.25%   |
| Crucial CT1000MX500SSD1 1TB      | 4        | 1.25%   |
| WDC WDS500G3X0C-00SJG0 500GB     | 3        | 0.94%   |
| WDC WDS100T3X0C-00SJG0 1TB       | 3        | 0.94%   |
| WDC WD10EZEX-00RKKA0 1TB         | 3        | 0.94%   |
| Toshiba HDWD110 1TB              | 3        | 0.94%   |
| Seagate ST2000DM006-2DM164 2TB   | 3        | 0.94%   |
| Seagate ST1000DM003-1CH162 1TB   | 3        | 0.94%   |
| Seagate Expansion Desk 8TB       | 3        | 0.94%   |
| Samsung SSD 970 EVO Plus 500GB   | 3        | 0.94%   |
| Samsung SSD 970 EVO 1TB          | 3        | 0.94%   |
| Samsung SSD 960 EVO 500GB        | 3        | 0.94%   |
| Samsung SSD 860 EVO 250GB        | 3        | 0.94%   |
| Samsung SSD 840 EVO 250GB        | 3        | 0.94%   |
| Kingston SA400S37120G 120GB SSD  | 3        | 0.94%   |
| WDC WDS500G2B0C-00PXH0 500GB     | 2        | 0.63%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 2        | 0.63%   |
| WDC WD40EZRZ-00GXCB0 4TB         | 2        | 0.63%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 2        | 0.63%   |
| WDC WD10EZRX-00A8LB0 1TB         | 2        | 0.63%   |
| WDC WD10EZEX-60WN4A1 1TB         | 2        | 0.63%   |
| WDC WD10EZEX-22MFCA0 1TB         | 2        | 0.63%   |
| Toshiba THNSNJ256GCSU 256GB SSD  | 2        | 0.63%   |
| Toshiba A100 120GB SSD           | 2        | 0.63%   |
| SPCC Solid State Disk 240GB      | 2        | 0.63%   |
| Seagate ST95005620AS 500GB       | 2        | 0.63%   |
| Seagate ST500DM002-1BD142 500GB  | 2        | 0.63%   |
| Seagate ST2000DM001-1ER164 2TB   | 2        | 0.63%   |
| Seagate ST1000DM003-1SB102 1TB   | 2        | 0.63%   |
| Seagate ST1000DM003-1ER162 1TB   | 2        | 0.63%   |
| Sandisk NVMe SSD Drive 500GB     | 2        | 0.63%   |
| Samsung SSD SM841 2.5 7mm 128GB  | 2        | 0.63%   |
| Samsung SSD 980 PRO 500GB        | 2        | 0.63%   |
| Samsung SSD 980 500GB            | 2        | 0.63%   |
| Samsung SSD 970 EVO Plus 1TB     | 2        | 0.63%   |
| Samsung SSD 970 EVO 500GB        | 2        | 0.63%   |
| Samsung SSD 840 EVO 500GB        | 2        | 0.63%   |
| Kingston SV300S37A120G 120GB SSD | 2        | 0.63%   |
| Kingston SUV400S37240G 240GB SSD | 2        | 0.63%   |
| Kingston SA400M8240G 240GB SSD   | 2        | 0.63%   |
| Intenso SSD 128GB                | 2        | 0.63%   |
| Corsair Force MP600 1TB          | 2        | 0.63%   |
| XPG SPECTRIX S40G 1TB            | 1        | 0.31%   |
| XPG GAMMIX S11 Pro 1TB           | 1        | 0.31%   |
| WDC WDS500G2X0C-00L350 500GB     | 1        | 0.31%   |
| WDC WDS500G1R0A-68A4W0 500GB SSD | 1        | 0.31%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD | 1        | 0.31%   |
| WDC WDS480G2G0A-00JH30 480GB SSD | 1        | 0.31%   |
| WDC WDS250G3X0C-00SJG0 250GB     | 1        | 0.31%   |
| WDC WDS200T1X0E-00AFY0 2TB       | 1        | 0.31%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 1        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 42       | 66     | 39.25%  |
| WDC                 | 40       | 65     | 37.38%  |
| Toshiba             | 9        | 10     | 8.41%   |
| Hitachi             | 4        | 4      | 3.74%   |
| Samsung Electronics | 3        | 4      | 2.8%    |
| HGST                | 2        | 2      | 1.87%   |
| Unknown             | 1        | 1      | 0.93%   |
| PI-041              | 1        | 1      | 0.93%   |
| MAXTOR              | 1        | 1      | 0.93%   |
| Maxone              | 1        | 1      | 0.93%   |
| JMicron             | 1        | 1      | 0.93%   |
| HPE                 | 1        | 1      | 0.93%   |
| ASMT                | 1        | 2      | 0.93%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 39       | 63     | 36.11%  |
| Crucial             | 16       | 22     | 14.81%  |
| Kingston            | 10       | 23     | 9.26%   |
| WDC                 | 8        | 12     | 7.41%   |
| Toshiba             | 4        | 5      | 3.7%    |
| SanDisk             | 4        | 5      | 3.7%    |
| Intenso             | 3        | 3      | 2.78%   |
| Intel               | 3        | 4      | 2.78%   |
| SPCC                | 2        | 2      | 1.85%   |
| OCZ                 | 2        | 2      | 1.85%   |
| Micron Technology   | 2        | 2      | 1.85%   |
| UMAX                | 1        | 1      | 0.93%   |
| Transcend           | 1        | 1      | 0.93%   |
| Pioneer             | 1        | 3      | 0.93%   |
| PHISON              | 1        | 1      | 0.93%   |
| Patriot             | 1        | 2      | 0.93%   |
| Mushkin             | 1        | 1      | 0.93%   |
| Leven               | 1        | 1      | 0.93%   |
| LDLC                | 1        | 1      | 0.93%   |
| JMicron             | 1        | 1      | 0.93%   |
| imation             | 1        | 1      | 0.93%   |
| Hewlett-Packard     | 1        | 1      | 0.93%   |
| DREVO               | 1        | 1      | 0.93%   |
| Corsair             | 1        | 1      | 0.93%   |
| China               | 1        | 1      | 0.93%   |
| A-DATA Technology   | 1        | 1      | 0.93%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 82       | 159    | 37.61%  |
| SSD     | 80       | 161    | 36.7%   |
| NVMe    | 55       | 87     | 25.23%  |
| Unknown | 1        | 1      | 0.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 107      | 304    | 60.45%  |
| NVMe | 55       | 86     | 31.07%  |
| SAS  | 15       | 18     | 8.47%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 75       | 158    | 40.32%  |
| 0.51-1.0   | 62       | 95     | 33.33%  |
| 1.01-2.0   | 21       | 31     | 11.29%  |
| 3.01-4.0   | 12       | 17     | 6.45%   |
| 2.01-3.0   | 7        | 8      | 3.76%   |
| 4.01-10.0  | 7        | 9      | 3.76%   |
| 10.01-20.0 | 2        | 2      | 1.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1001-2000      | 30       | 24.39%  |
| 501-1000       | 22       | 17.89%  |
| More than 3000 | 17       | 13.82%  |
| 251-500        | 15       | 12.2%   |
| 101-250        | 14       | 11.38%  |
| 2001-3000      | 11       | 8.94%   |
| Unknown        | 9        | 7.32%   |
| 51-100         | 3        | 2.44%   |
| 21-50          | 1        | 0.81%   |
| 1-20           | 1        | 0.81%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 21       | 16.03%  |
| 1001-2000      | 18       | 13.74%  |
| 251-500        | 17       | 12.98%  |
| 101-250        | 16       | 12.21%  |
| 1-20           | 15       | 11.45%  |
| 51-100         | 15       | 11.45%  |
| 21-50          | 9        | 6.87%   |
| Unknown        | 9        | 6.87%   |
| More than 3000 | 8        | 6.11%   |
| 2001-3000      | 3        | 2.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD5000AZRX-00A8LB0 500GB          | 1        | 1      | 8.33%   |
| WDC WD40EFRX-68WT0N0 4TB              | 1        | 2      | 8.33%   |
| Toshiba DT01ACA100 1TB                | 1        | 1      | 8.33%   |
| Seagate ST9320325AS 320GB             | 1        | 5      | 8.33%   |
| Seagate ST6000VX0023-2EF110 6TB       | 1        | 1      | 8.33%   |
| Seagate ST3320620AS 320GB             | 1        | 1      | 8.33%   |
| Samsung Electronics SSD 960 EVO 500GB | 1        | 1      | 8.33%   |
| Samsung Electronics HD103SI 752GB     | 1        | 1      | 8.33%   |
| Kingston SV300S37A120G 120GB SSD      | 1        | 1      | 8.33%   |
| Hitachi HTS545050A7E380 500GB         | 1        | 1      | 8.33%   |
| DREVO X1 SSD 120GB                    | 1        | 1      | 8.33%   |
| ASMT ASM1156-PM 2TB                   | 1        | 2      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 3        | 7      | 25%     |
| WDC                 | 2        | 3      | 16.67%  |
| Samsung Electronics | 2        | 2      | 16.67%  |
| Toshiba             | 1        | 1      | 8.33%   |
| Kingston            | 1        | 1      | 8.33%   |
| Hitachi             | 1        | 1      | 8.33%   |
| DREVO               | 1        | 1      | 8.33%   |
| ASMT                | 1        | 2      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 3        | 7      | 33.33%  |
| WDC                 | 2        | 3      | 22.22%  |
| Toshiba             | 1        | 1      | 11.11%  |
| Samsung Electronics | 1        | 1      | 11.11%  |
| Hitachi             | 1        | 1      | 11.11%  |
| ASMT                | 1        | 2      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 9        | 15     | 81.82%  |
| NVMe | 1        | 1      | 9.09%   |
| SSD  | 1        | 2      | 9.09%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BC142 500GB | 1        | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 91       | 276    | 65%     |
| Detected | 38       | 113    | 27.14%  |
| Malfunc  | 10       | 18     | 7.14%   |
| Failed   | 1        | 1      | 0.71%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 60       | 30.15%  |
| AMD                         | 58       | 29.15%  |
| Samsung Electronics         | 21       | 10.55%  |
| Sandisk                     | 15       | 7.54%   |
| Phison Electronics          | 9        | 4.52%   |
| ASMedia Technology          | 8        | 4.02%   |
| Marvell Technology Group    | 5        | 2.51%   |
| Realtek Semiconductor       | 4        | 2.01%   |
| Kingston Technology Company | 4        | 2.01%   |
| JMicron Technology          | 3        | 1.51%   |
| ADATA Technology            | 3        | 1.51%   |
| Nvidia                      | 2        | 1.01%   |
| SK Hynix                    | 1        | 0.5%    |
| Silicon Motion              | 1        | 0.5%    |
| Seagate Technology          | 1        | 0.5%    |
| Micron/Crucial Technology   | 1        | 0.5%    |
| Micron Technology           | 1        | 0.5%    |
| LSI Logic / Symbios Logic   | 1        | 0.5%    |
| KIOXIA                      | 1        | 0.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 37       | 16.16%  |
| AMD 400 Series Chipset SATA Controller                                         | 19       | 8.3%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 12       | 5.24%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 11       | 4.8%    |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                       | 10       | 4.37%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 8        | 3.49%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 7        | 3.06%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 7        | 3.06%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6        | 2.62%   |
| Intel SATA Controller [RAID mode]                                              | 5        | 2.18%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5        | 2.18%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 4        | 1.75%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 4        | 1.75%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4        | 1.75%   |
| Phison E16 PCIe4 NVMe Controller                                               | 4        | 1.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3        | 1.31%   |
| Realtek Realtek Non-Volatile memory controller                                 | 3        | 1.31%   |
| Phison E12 NVMe Controller                                                     | 3        | 1.31%   |
| Kingston Company A2000 NVMe SSD                                                | 3        | 1.31%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3        | 1.31%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3        | 1.31%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 3        | 1.31%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 3        | 1.31%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3        | 1.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3        | 1.31%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 3        | 1.31%   |
| Samsung NVMe SSD Controller 980                                                | 2        | 0.87%   |
| JMicron JMB363 SATA/IDE Controller                                             | 2        | 0.87%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2        | 0.87%   |
| AMD X370 Series Chipset SATA Controller                                        | 2        | 0.87%   |
| AMD 300 Series Chipset SATA Controller                                         | 2        | 0.87%   |
| SK Hynix BC501 NVMe Solid State Drive                                          | 1        | 0.44%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1        | 0.44%   |
| Seagate FireCuda 520 SSD                                                       | 1        | 0.44%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1        | 0.44%   |
| Realtek RTS5763DL NVMe SSD Controller                                          | 1        | 0.44%   |
| Phison E7 NVMe Controller                                                      | 1        | 0.44%   |
| Phison E18 PCIe4 NVMe Controller                                               | 1        | 0.44%   |
| Nvidia MCP73 SATA Controller (IDE mode)                                        | 1        | 0.44%   |
| Nvidia MCP73 IDE Controller                                                    | 1        | 0.44%   |
| Nvidia MCP61 SATA Controller                                                   | 1        | 0.44%   |
| Nvidia MCP61 IDE                                                               | 1        | 0.44%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1        | 0.44%   |
| Micron Non-Volatile memory controller                                          | 1        | 0.44%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                     | 1        | 0.44%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 1        | 0.44%   |
| Marvell Group 88SE912x IDE Controller                                          | 1        | 0.44%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo          | 1        | 0.44%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                           | 1        | 0.44%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                          | 1        | 0.44%   |
| LSI Logic / Symbios Logic SAS2308 PCI-Express Fusion-MPT SAS-2                 | 1        | 0.44%   |
| KIOXIA Non-Volatile memory controller                                          | 1        | 0.44%   |
| Kingston Company KC2000 NVMe SSD                                               | 1        | 0.44%   |
| JMicron JMB362 SATA Controller                                                 | 1        | 0.44%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 1        | 0.44%   |
| Intel SSD 660P Series                                                          | 1        | 0.44%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1        | 0.44%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1        | 0.44%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 1        | 0.44%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 1        | 0.44%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 107      | 59.44%  |
| NVMe | 55       | 30.56%  |
| IDE  | 12       | 6.67%   |
| RAID | 5        | 2.78%   |
| SAS  | 1        | 0.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 61       | 50.83%  |
| AMD    | 59       | 49.17%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor              | 9        | 7.5%    |
| AMD Ryzen 7 3700X 8-Core Processor             | 7        | 5.83%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 5        | 4.17%   |
| Intel Core i7-4770K CPU @ 3.50GHz              | 4        | 3.33%   |
| AMD Ryzen 9 5900X 12-Core Processor            | 4        | 3.33%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 4        | 3.33%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 3        | 2.5%    |
| Intel Core i5-3570K CPU @ 3.40GHz              | 3        | 2.5%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 3        | 2.5%    |
| AMD Ryzen 5 3600X 6-Core Processor             | 3        | 2.5%    |
| AMD Ryzen 5 3400G with Radeon Vega Graphics    | 3        | 2.5%    |
| Intel Core i7-6700K CPU @ 4.00GHz              | 2        | 1.67%   |
| Intel Core i7-4790K CPU @ 4.00GHz              | 2        | 1.67%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 2        | 1.67%   |
| Intel Core i5-6600 CPU @ 3.30GHz               | 2        | 1.67%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 2        | 1.67%   |
| AMD Ryzen 7 5800X 8-Core Processor             | 2        | 1.67%   |
| AMD Ryzen 7 5700G with Radeon Graphics         | 2        | 1.67%   |
| AMD Ryzen 7 3800X 8-Core Processor             | 2        | 1.67%   |
| Intel Xeon CPU X5675 @ 3.07GHz                 | 1        | 0.83%   |
| Intel Xeon CPU W5580 @ 3.20GHz                 | 1        | 0.83%   |
| Intel Xeon CPU W3520 @ 2.67GHz                 | 1        | 0.83%   |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz            | 1        | 0.83%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz             | 1        | 0.83%   |
| Intel Xeon CPU E3-1240 V2 @ 3.40GHz            | 1        | 0.83%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz         | 1        | 0.83%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz    | 1        | 0.83%   |
| Intel Pentium Dual CPU E2220 @ 2.40GHz         | 1        | 0.83%   |
| Intel Core m3-8100Y CPU @ 1.10GHz              | 1        | 0.83%   |
| Intel Core i7-8700K CPU @ 3.70GHz              | 1        | 0.83%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 1        | 0.83%   |
| Intel Core i7-4770 CPU @ 3.40GHz               | 1        | 0.83%   |
| Intel Core i7-3770K CPU @ 3.50GHz              | 1        | 0.83%   |
| Intel Core i7 CPU 950 @ 3.07GHz                | 1        | 0.83%   |
| Intel Core i7 CPU 860 @ 2.80GHz                | 1        | 0.83%   |
| Intel Core i5-9600K CPU @ 3.70GHz              | 1        | 0.83%   |
| Intel Core i5-9400 CPU @ 2.90GHz               | 1        | 0.83%   |
| Intel Core i5-8500 CPU @ 3.00GHz               | 1        | 0.83%   |
| Intel Core i5-8400 CPU @ 2.80GHz               | 1        | 0.83%   |
| Intel Core i5-7500T CPU @ 2.70GHz              | 1        | 0.83%   |
| Intel Core i5-7500 CPU @ 3.40GHz               | 1        | 0.83%   |
| Intel Core i5-6500TE CPU @ 2.30GHz             | 1        | 0.83%   |
| Intel Core i5-6500 CPU @ 3.20GHz               | 1        | 0.83%   |
| Intel Core i5-4670K CPU @ 3.40GHz              | 1        | 0.83%   |
| Intel Core i5-4570T CPU @ 2.90GHz              | 1        | 0.83%   |
| Intel Core i5-4570 CPU @ 3.20GHz               | 1        | 0.83%   |
| Intel Core i5-4460S CPU @ 2.90GHz              | 1        | 0.83%   |
| Intel Core i5-4460 CPU @ 3.20GHz               | 1        | 0.83%   |
| Intel Core i5-4440 CPU @ 3.10GHz               | 1        | 0.83%   |
| Intel Core i5-3470T CPU @ 2.90GHz              | 1        | 0.83%   |
| Intel Core i5-10600KF CPU @ 4.10GHz            | 1        | 0.83%   |
| Intel Core i5-10400 CPU @ 2.90GHz              | 1        | 0.83%   |
| Intel Core i3-8100 CPU @ 3.60GHz               | 1        | 0.83%   |
| Intel Core i3-6098P CPU @ 3.60GHz              | 1        | 0.83%   |
| Intel Core i3-10105 CPU @ 3.70GHz              | 1        | 0.83%   |
| Intel Core i3 CPU 530 @ 2.93GHz                | 1        | 0.83%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz           | 1        | 0.83%   |
| Intel Celeron J4125 CPU @ 2.00GHz              | 1        | 0.83%   |
| Intel Celeron CPU G1840 @ 2.80GHz              | 1        | 0.83%   |
| AMD Ryzen Threadripper 1920X 12-Core Processor | 1        | 0.83%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 5             | 25       | 20.83%  |
| Intel Core i5           | 24       | 20%     |
| Intel Core i7           | 17       | 14.17%  |
| AMD Ryzen 7             | 15       | 12.5%   |
| AMD Ryzen 9             | 11       | 9.17%   |
| Intel Xeon              | 6        | 5%      |
| Intel Core i3           | 4        | 3.33%   |
| Intel Core 2 Quad       | 3        | 2.5%    |
| AMD FX                  | 3        | 2.5%    |
| Intel Celeron           | 2        | 1.67%   |
| AMD Ryzen 3             | 2        | 1.67%   |
| Intel Pentium Gold      | 1        | 0.83%   |
| Intel Pentium Dual-Core | 1        | 0.83%   |
| Intel Pentium Dual      | 1        | 0.83%   |
| Intel Core m3           | 1        | 0.83%   |
| Intel Core 2 Duo        | 1        | 0.83%   |
| AMD Ryzen Threadripper  | 1        | 0.83%   |
| AMD Phenom II X4        | 1        | 0.83%   |
| AMD Athlon II X4        | 1        | 0.83%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 48       | 39.67%  |
| 6      | 31       | 25.62%  |
| 8      | 16       | 13.22%  |
| 12     | 11       | 9.09%   |
| 2      | 10       | 8.26%   |
| 16     | 2        | 1.65%   |
| 3      | 2        | 1.65%   |
| 10     | 1        | 0.83%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 119      | 98.35%  |
| 2      | 2        | 1.65%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 87       | 72.5%   |
| 1      | 33       | 27.5%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 120      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 34       | 27.64%  |
| 0x08701021 | 16       | 13.01%  |
| 0x306c3    | 9        | 7.32%   |
| 0x0a201009 | 8        | 6.5%    |
| 0x08701013 | 7        | 5.69%   |
| 0x906ea    | 5        | 4.07%   |
| 0x506e3    | 5        | 4.07%   |
| 0x306a9    | 5        | 4.07%   |
| 0x0800820d | 4        | 3.25%   |
| 0x106a5    | 3        | 2.44%   |
| 0x0a201016 | 3        | 2.44%   |
| 0xa0655    | 2        | 1.63%   |
| 0x906e9    | 2        | 1.63%   |
| 0x6fd      | 2        | 1.63%   |
| 0x08108109 | 2        | 1.63%   |
| 0x08001137 | 2        | 1.63%   |
| 0x906ed    | 1        | 0.81%   |
| 0x906eb    | 1        | 0.81%   |
| 0x706a8    | 1        | 0.81%   |
| 0x6fb      | 1        | 0.81%   |
| 0x306f2    | 1        | 0.81%   |
| 0x206c2    | 1        | 0.81%   |
| 0x20652    | 1        | 0.81%   |
| 0x106e5    | 1        | 0.81%   |
| 0x0a50000c | 1        | 0.81%   |
| 0x0a50000b | 1        | 0.81%   |
| 0x08101016 | 1        | 0.81%   |
| 0x08001138 | 1        | 0.81%   |
| 0x06000852 | 1        | 0.81%   |
| 0x010000c8 | 1        | 0.81%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Zen 2         | 26       | 21.67%  |
| Haswell       | 18       | 15%     |
| Zen 3         | 15       | 12.5%   |
| KabyLake      | 13       | 10.83%  |
| Zen+          | 7        | 5.83%   |
| Skylake       | 7        | 5.83%   |
| Zen           | 6        | 5%      |
| IvyBridge     | 6        | 5%      |
| Core          | 5        | 4.17%   |
| Nehalem       | 4        | 3.33%   |
| CometLake     | 3        | 2.5%    |
| Westmere      | 2        | 1.67%   |
| Piledriver    | 2        | 1.67%   |
| SandyBridge   | 1        | 0.83%   |
| Penryn        | 1        | 0.83%   |
| K10 Llano     | 1        | 0.83%   |
| K10           | 1        | 0.83%   |
| Goldmont plus | 1        | 0.83%   |
| Bulldozer     | 1        | 0.83%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 67       | 50.76%  |
| AMD    | 45       | 34.09%  |
| Intel  | 20       | 15.15%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 14       | 10.61%  |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 8        | 6.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8        | 6.06%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 6        | 4.55%   |
| Nvidia GK208B [GeForce GT 710]                                              | 5        | 3.79%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 4        | 3.03%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 4        | 3.03%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4        | 3.03%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 2.27%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 3        | 2.27%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3        | 2.27%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 3        | 2.27%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 3        | 2.27%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 3        | 2.27%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2        | 1.52%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 1.52%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 2        | 1.52%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 1.52%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 2        | 1.52%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 2        | 1.52%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 2        | 1.52%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 2        | 1.52%   |
| Intel HD Graphics 530                                                       | 2        | 1.52%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2        | 1.52%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT / 6800M]                                | 2        | 1.52%   |
| AMD Cezanne                                                                 | 2        | 1.52%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.76%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 0.76%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.76%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 0.76%   |
| Nvidia GT218 [GeForce 210]                                                  | 1        | 0.76%   |
| Nvidia GP107GL [Quadro P400]                                                | 1        | 0.76%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 0.76%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1        | 0.76%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 1        | 0.76%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 1        | 0.76%   |
| Nvidia GK104 [GeForce GTX 670]                                              | 1        | 0.76%   |
| Nvidia GK104 [GeForce GTX 660 OEM]                                          | 1        | 0.76%   |
| Nvidia GF119 [NVS 310]                                                      | 1        | 0.76%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 0.76%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1        | 0.76%   |
| Nvidia GF106 [GeForce GTS 450 OEM]                                          | 1        | 0.76%   |
| Nvidia GF104 [GeForce GTX 460]                                              | 1        | 0.76%   |
| Nvidia GA104 [GeForce RTX 3060 Ti]                                          | 1        | 0.76%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 1        | 0.76%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 1        | 0.76%   |
| Nvidia G92 [GeForce 8800 GT]                                                | 1        | 0.76%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 1        | 0.76%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1        | 0.76%   |
| Intel UHD Graphics 615                                                      | 1        | 0.76%   |
| Intel HD Graphics 630                                                       | 1        | 0.76%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 0.76%   |
| Intel Core Processor Integrated Graphics Controller                         | 1        | 0.76%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 0.76%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 1        | 0.76%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 1        | 0.76%   |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 1        | 0.76%   |
| AMD Tahiti PRO [Radeon HD 7950/8950 OEM / R9 280]                           | 1        | 0.76%   |
| AMD Juniper XT [Radeon HD 5770]                                             | 1        | 0.76%   |
| AMD Hawaii PRO [Radeon R9 290/390]                                          | 1        | 0.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 60       | 49.59%  |
| 1 x AMD        | 40       | 33.06%  |
| 1 x Intel      | 13       | 10.74%  |
| AMD + Nvidia   | 5        | 4.13%   |
| Intel + Nvidia | 2        | 1.65%   |
| Intel + AMD    | 1        | 0.83%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 64       | 53.33%  |
| Proprietary | 56       | 46.67%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 30       | 24.19%  |
| 7.01-8.0   | 27       | 21.77%  |
| 1.01-2.0   | 18       | 14.52%  |
| 3.01-4.0   | 16       | 12.9%   |
| 5.01-6.0   | 11       | 8.87%   |
| 8.01-16.0  | 9        | 7.26%   |
| 0.51-1.0   | 7        | 5.65%   |
| 0.01-0.5   | 4        | 3.23%   |
| 2.01-3.0   | 1        | 0.81%   |
| 16.01-24.0 | 1        | 0.81%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 28       | 18.06%  |
| Goldstar             | 16       | 10.32%  |
| Dell                 | 14       | 9.03%   |
| BenQ                 | 14       | 9.03%   |
| Ancor Communications | 11       | 7.1%    |
| Acer                 | 11       | 7.1%    |
| AOC                  | 9        | 5.81%   |
| Iiyama               | 5        | 3.23%   |
| Vizio                | 4        | 2.58%   |
| ViewSonic            | 4        | 2.58%   |
| Hewlett-Packard      | 4        | 2.58%   |
| ASUSTek Computer     | 4        | 2.58%   |
| LG Electronics       | 3        | 1.94%   |
| Fujitsu Siemens      | 3        | 1.94%   |
| Lenovo Group Limited | 2        | 1.29%   |
| Lenovo               | 2        | 1.29%   |
| Valve                | 1        | 0.65%   |
| Unknown (XXX)        | 1        | 0.65%   |
| Unknown              | 1        | 0.65%   |
| Sony                 | 1        | 0.65%   |
| Sceptre Tech         | 1        | 0.65%   |
| SAC                  | 1        | 0.65%   |
| RS                   | 1        | 0.65%   |
| Planar               | 1        | 0.65%   |
| Pixio                | 1        | 0.65%   |
| Philips              | 1        | 0.65%   |
| NEC Computers        | 1        | 0.65%   |
| MSI                  | 1        | 0.65%   |
| Insignia             | 1        | 0.65%   |
| HVR                  | 1        | 0.65%   |
| HPN                  | 1        | 0.65%   |
| Grundig              | 1        | 0.65%   |
| Gigabyte Technology  | 1        | 0.65%   |
| Gateway              | 1        | 0.65%   |
| Eizo                 | 1        | 0.65%   |
| Belinea              | 1        | 0.65%   |
| Unknown              | 1        | 0.65%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch    | 2        | 1.22%   |
| Samsung Electronics S24D590 SAM0B47 1920x1080 520x290mm 23.4-inch      | 2        | 1.22%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch      | 2        | 1.22%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 2        | 1.22%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2        | 1.22%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                 | 2        | 1.22%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                      | 2        | 1.22%   |
| BenQ G2450H BNQ78AB 1920x1080 531x298mm 24.0-inch                      | 2        | 1.22%   |
| BenQ G2420HD BNQ7840 1920x1080 530x300mm 24.0-inch                     | 2        | 1.22%   |
| ASUSTek Computer VG289 AUS28BA 3840x2160 620x340mm 27.8-inch           | 2        | 1.22%   |
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                        | 2        | 1.22%   |
| Ancor Communications VS248 ACI2498 1920x1080 530x300mm 24.0-inch       | 2        | 1.22%   |
| Vizio V505-G9 VIZ1033 3840x2160 1096x616mm 49.5-inch                   | 1        | 0.61%   |
| Vizio M320NV VIZ0070 1920x1080 700x390mm 31.5-inch                     | 1        | 0.61%   |
| Vizio D32f-F1 VIZ1027 1920x1080 698x392mm 31.5-inch                    | 1        | 0.61%   |
| Vizio 320AR VIZ0089 1360x768 477x268mm 21.5-inch                       | 1        | 0.61%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch          | 1        | 0.61%   |
| ViewSonic VX2457 VSCB931 1920x1080 520x290mm 23.4-inch                 | 1        | 0.61%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch          | 1        | 0.61%   |
| ViewSonic VX2363 Series VSC6B2F 1920x1080 509x286mm 23.0-inch          | 1        | 0.61%   |
| Valve Index HMD VLV91A8                                                | 1        | 0.61%   |
| Unknown LCD Monitor MARANTZ JAPAN, INC. marantz-AVR 3840x2160          | 1        | 0.61%   |
| Unknown (XXX) HDMI XXX0101 2560x1600 220x130mm 10.1-inch               | 1        | 0.61%   |
| Sony TV SNY8002 1920x1080 1600x900mm 72.3-inch                         | 1        | 0.61%   |
| Sceptre Tech Sceptre L24 SPT098C 1920x1080 530x300mm 24.0-inch         | 1        | 0.61%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 1        | 0.61%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 607x345mm 27.5-inch      | 1        | 0.61%   |
| Samsung Electronics SyncMaster SAM058F 1920x1080 477x268mm 21.5-inch   | 1        | 0.61%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch   | 1        | 0.61%   |
| Samsung Electronics SyncMaster SAM02B6 1920x1200 518x324mm 24.1-inch   | 1        | 0.61%   |
| Samsung Electronics SMS22A350H SAM07D2 1920x1080 480x270mm 21.7-inch   | 1        | 0.61%   |
| Samsung Electronics SMEX2220 SAM0686 1920x1080 477x268mm 21.5-inch     | 1        | 0.61%   |
| Samsung Electronics SMBX2350 SAM071D 1920x1080 509x286mm 23.0-inch     | 1        | 0.61%   |
| Samsung Electronics SMB2430L SAM0645 1920x1080 521x293mm 23.5-inch     | 1        | 0.61%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch      | 1        | 0.61%   |
| Samsung Electronics SA300/SA350 SAM0793 1920x1080 531x299mm 24.0-inch  | 1        | 0.61%   |
| Samsung Electronics S24R65x SAM1023 1920x1080 527x296mm 23.8-inch      | 1        | 0.61%   |
| Samsung Electronics S24B300 SAM08B4 1920x1080 521x293mm 23.5-inch      | 1        | 0.61%   |
| Samsung Electronics S24B240 SAM08E9 1920x1080 521x293mm 23.5-inch      | 1        | 0.61%   |
| Samsung Electronics S22C300 SAM0A20 1920x1080 480x270mm 21.7-inch      | 1        | 0.61%   |
| Samsung Electronics S19B420 SAM0975 1366x768 410x230mm 18.5-inch       | 1        | 0.61%   |
| Samsung Electronics LCD Monitor SAM0FA5 3840x2160 1210x680mm 54.6-inch | 1        | 0.61%   |
| Samsung Electronics LCD Monitor SAM0C28 1920x1080 1209x680mm 54.6-inch | 1        | 0.61%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 1209x680mm 54.6-inch | 1        | 0.61%   |
| Samsung Electronics LCD Monitor LU28R55 9840x3840                      | 1        | 0.61%   |
| Samsung Electronics LCD Monitor LU28R55                                | 1        | 0.61%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch     | 1        | 0.61%   |
| Samsung Electronics C49HG9x SAM0E5E 3840x1080 1200x340mm 49.1-inch     | 1        | 0.61%   |
| Samsung Electronics C27FG7x SAM0E42 1920x1080 598x337mm 27.0-inch      | 1        | 0.61%   |
| Samsung Electronics C24FG7x SAM0E43 1920x1080 532x304mm 24.1-inch      | 1        | 0.61%   |
| SAC LED MONITOR SAC952D 1920x1080 470x280mm 21.5-inch                  | 1        | 0.61%   |
| RS LE22A3 BTC22A3 1680x1050 473x296mm 22.0-inch                        | 1        | 0.61%   |
| Planar PLL2410W PLN2410 1920x1080 521x293mm 23.5-inch                  | 1        | 0.61%   |
| Pixio DP ICB270E 2560x1440 768x432mm 34.7-inch                         | 1        | 0.61%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 1        | 0.61%   |
| NEC Computers LCD2090UXi NEC66B0 1600x1200 408x306mm 20.1-inch         | 1        | 0.61%   |
| MSI MAG322CQR MSI3DA7 2560x1440 697x392mm 31.5-inch                    | 1        | 0.61%   |
| LG Electronics LCD Monitor LG HDR QHD 2560x1440                        | 1        | 0.61%   |
| LG Electronics LCD Monitor E2442                                       | 1        | 0.61%   |
| LG Electronics LCD Monitor E1940 1360x768                              | 1        | 0.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 64       | 42.67%  |
| 2560x1440 (QHD)    | 19       | 12.67%  |
| 3840x2160 (4K)     | 17       | 11.33%  |
| 1920x1200 (WUXGA)  | 7        | 4.67%   |
| 1280x1024 (SXGA)   | 7        | 4.67%   |
| Unknown            | 5        | 3.33%   |
| 2560x1080          | 4        | 2.67%   |
| 1680x1050 (WSXGA+) | 4        | 2.67%   |
| 3440x1440          | 3        | 2%      |
| 1600x900 (HD+)     | 3        | 2%      |
| 1440x900 (WXGA+)   | 3        | 2%      |
| 1366x768 (WXGA)    | 3        | 2%      |
| 3840x1080          | 2        | 1.33%   |
| 1360x768           | 2        | 1.33%   |
| 9840x3840          | 1        | 0.67%   |
| 4480x1440          | 1        | 0.67%   |
| 3840x1600          | 1        | 0.67%   |
| 3520x1080          | 1        | 0.67%   |
| 2880x1700          | 1        | 0.67%   |
| 2560x1600          | 1        | 0.67%   |
| 1600x1200          | 1        | 0.67%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 34       | 21.94%  |
| 27      | 29       | 18.71%  |
| 23      | 16       | 10.32%  |
| 21      | 13       | 8.39%   |
| Unknown | 13       | 8.39%   |
| 34      | 9        | 5.81%   |
| 31      | 6        | 3.87%   |
| 19      | 6        | 3.87%   |
| 22      | 5        | 3.23%   |
| 18      | 4        | 2.58%   |
| 54      | 3        | 1.94%   |
| 20      | 3        | 1.94%   |
| 49      | 2        | 1.29%   |
| 32      | 2        | 1.29%   |
| 17      | 2        | 1.29%   |
| 72      | 1        | 0.65%   |
| 69      | 1        | 0.65%   |
| 60      | 1        | 0.65%   |
| 48      | 1        | 0.65%   |
| 42      | 1        | 0.65%   |
| 37      | 1        | 0.65%   |
| 15      | 1        | 0.65%   |
| 10      | 1        | 0.65%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 64       | 44.44%  |
| 401-500     | 25       | 17.36%  |
| Unknown     | 13       | 9.03%   |
| 601-700     | 12       | 8.33%   |
| 701-800     | 11       | 7.64%   |
| 1001-1500   | 7        | 4.86%   |
| 351-400     | 4        | 2.78%   |
| 301-350     | 3        | 2.08%   |
| 1501-2000   | 2        | 1.39%   |
| 801-900     | 1        | 0.69%   |
| 201-300     | 1        | 0.69%   |
| 901-1000    | 1        | 0.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 89       | 64.96%  |
| 16/10   | 18       | 13.14%  |
| Unknown | 12       | 8.76%   |
| 21/9    | 8        | 5.84%   |
| 5/4     | 5        | 3.65%   |
| 4/3     | 2        | 1.46%   |
| 32/9    | 2        | 1.46%   |
| 6/5     | 1        | 0.73%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 50       | 33.11%  |
| 301-350        | 29       | 19.21%  |
| 351-500        | 16       | 10.6%   |
| 251-300        | 15       | 9.93%   |
| Unknown        | 13       | 8.61%   |
| 151-200        | 9        | 5.96%   |
| More than 1000 | 7        | 4.64%   |
| 141-150        | 5        | 3.31%   |
| 501-1000       | 5        | 3.31%   |
| 41-50          | 1        | 0.66%   |
| 111-120        | 1        | 0.66%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 78       | 58.21%  |
| 101-120       | 27       | 20.15%  |
| Unknown       | 13       | 9.7%    |
| 121-160       | 7        | 5.22%   |
| 1-50          | 6        | 4.48%   |
| 161-240       | 2        | 1.49%   |
| More than 240 | 1        | 0.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 86       | 71.07%  |
| 2     | 26       | 21.49%  |
| 3     | 7        | 5.79%   |
| 4     | 2        | 1.65%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 78       | 45.35%  |
| Intel                 | 58       | 33.72%  |
| Qualcomm Atheros      | 8        | 4.65%   |
| Broadcom              | 5        | 2.91%   |
| Ralink Technology     | 3        | 1.74%   |
| Ralink                | 3        | 1.74%   |
| Microsoft             | 3        | 1.74%   |
| Nvidia                | 2        | 1.16%   |
| Xiaomi                | 1        | 0.58%   |
| TP-Link               | 1        | 0.58%   |
| NetGear               | 1        | 0.58%   |
| MediaTek              | 1        | 0.58%   |
| Linksys               | 1        | 0.58%   |
| InterBiometrics       | 1        | 0.58%   |
| Huawei Technologies   | 1        | 0.58%   |
| Exar                  | 1        | 0.58%   |
| Edimax Technology     | 1        | 0.58%   |
| Broadcom Limited      | 1        | 0.58%   |
| ASIX Electronics      | 1        | 0.58%   |
| Aquantia              | 1        | 0.58%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 55       | 26.7%   |
| Intel Wi-Fi 6 AX200                                                 | 19       | 9.22%   |
| Intel I211 Gigabit Network Connection                               | 19       | 9.22%   |
| Realtek RTL8125 2.5GbE Controller                                   | 15       | 7.28%   |
| Intel Ethernet Connection (2) I219-V                                | 5        | 2.43%   |
| Intel Wireless-AC 9260                                              | 4        | 1.94%   |
| Intel Ethernet Controller I225-V                                    | 4        | 1.94%   |
| Intel Ethernet Connection I217-V                                    | 4        | 1.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 3        | 1.46%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 3        | 1.46%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 3        | 1.46%   |
| Microsoft Wireless XBox Controller Dongle                           | 3        | 1.46%   |
| Intel Ethernet Connection I217-LM                                   | 3        | 1.46%   |
| Intel Ethernet Connection (7) I219-V                                | 3        | 1.46%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                  | 3        | 1.46%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter            | 2        | 0.97%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 2        | 0.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 2        | 0.97%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                | 2        | 0.97%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 2        | 0.97%   |
| Intel Wireless 8260                                                 | 2        | 0.97%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 2        | 0.97%   |
| Intel Ethernet Connection (2) I219-LM                               | 2        | 0.97%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                     | 2        | 0.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 2        | 0.97%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 1        | 0.49%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U] | 1        | 0.49%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 1        | 0.49%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 0.49%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                     | 1        | 0.49%   |
| Realtek RTL8188EE Wireless Network Adapter                          | 1        | 0.49%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter            | 1        | 0.49%   |
| Realtek 802.11ac NIC                                                | 1        | 0.49%   |
| Ralink RT5572 Wireless Adapter                                      | 1        | 0.49%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 1        | 0.49%   |
| Ralink RT2870 Wireless Adapter                                      | 1        | 0.49%   |
| Ralink RT2561/RT61 802.11g PCI                                      | 1        | 0.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller           | 1        | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 1        | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 1        | 0.49%   |
| Nvidia MCP73 Ethernet                                               | 1        | 0.49%   |
| Nvidia MCP61 Ethernet                                               | 1        | 0.49%   |
| NetGear A6210                                                       | 1        | 0.49%   |
| MediaTek WiFi                                                       | 1        | 0.49%   |
| Linksys WUSB54GC v3 802.11g Adapter [Ralink RT2070L]                | 1        | 0.49%   |
| InterBiometrics Dygma Shortcut Keyboard                             | 1        | 0.49%   |
| Intel Wireless 7260                                                 | 1        | 0.49%   |
| Intel Tiger Lake PCH CNVi WiFi                                      | 1        | 0.49%   |
| Intel I210 Gigabit Network Connection                               | 1        | 0.49%   |
| Intel Ethernet Connection (7) I219-LM                               | 1        | 0.49%   |
| Intel Ethernet Connection (2) I218-V                                | 1        | 0.49%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 1        | 0.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 1        | 0.49%   |
| Intel 82579V Gigabit Network Connection                             | 1        | 0.49%   |
| Intel 82578DC Gigabit Network Connection                            | 1        | 0.49%   |
| Intel 82567LM-3 Gigabit Network Connection                          | 1        | 0.49%   |
| Intel 82541PI Gigabit Ethernet Controller                           | 1        | 0.49%   |
| Huawei Modem/Networkcard                                            | 1        | 0.49%   |
| Exar XR21V1410 USB-UART IC                                          | 1        | 0.49%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT2870]            | 1        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 33       | 50%     |
| Realtek Semiconductor | 13       | 19.7%   |
| Broadcom              | 4        | 6.06%   |
| Ralink Technology     | 3        | 4.55%   |
| Ralink                | 3        | 4.55%   |
| Microsoft             | 3        | 4.55%   |
| Qualcomm Atheros      | 2        | 3.03%   |
| TP-Link               | 1        | 1.52%   |
| NetGear               | 1        | 1.52%   |
| MediaTek              | 1        | 1.52%   |
| Linksys               | 1        | 1.52%   |
| Edimax Technology     | 1        | 1.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                 | 19       | 28.79%  |
| Intel Wireless-AC 9260                                              | 4        | 6.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 3        | 4.55%   |
| Microsoft Wireless XBox Controller Dongle                           | 3        | 4.55%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                  | 3        | 4.55%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter            | 2        | 3.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 2        | 3.03%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                | 2        | 3.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                    | 2        | 3.03%   |
| Intel Wireless 8260                                                 | 2        | 3.03%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 2        | 3.03%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                     | 2        | 3.03%   |
| TP-Link Archer T1U 802.11a/n/ac Wireless Adapter [MediaTek MT7610U] | 1        | 1.52%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 1        | 1.52%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter            | 1        | 1.52%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                     | 1        | 1.52%   |
| Realtek RTL8188EE Wireless Network Adapter                          | 1        | 1.52%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter            | 1        | 1.52%   |
| Realtek 802.11ac NIC                                                | 1        | 1.52%   |
| Ralink RT5572 Wireless Adapter                                      | 1        | 1.52%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 1        | 1.52%   |
| Ralink RT2870 Wireless Adapter                                      | 1        | 1.52%   |
| Ralink RT2561/RT61 802.11g PCI                                      | 1        | 1.52%   |
| NetGear A6210                                                       | 1        | 1.52%   |
| MediaTek WiFi                                                       | 1        | 1.52%   |
| Linksys WUSB54GC v3 802.11g Adapter [Ralink RT2070L]                | 1        | 1.52%   |
| Intel Wireless 7260                                                 | 1        | 1.52%   |
| Intel Tiger Lake PCH CNVi WiFi                                      | 1        | 1.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 1        | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                     | 1        | 1.52%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT2870]            | 1        | 1.52%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                  | 1        | 1.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 73       | 54.48%  |
| Intel                 | 48       | 35.82%  |
| Qualcomm Atheros      | 6        | 4.48%   |
| Nvidia                | 2        | 1.49%   |
| Xiaomi                | 1        | 0.75%   |
| Broadcom Limited      | 1        | 0.75%   |
| Broadcom              | 1        | 0.75%   |
| ASIX Electronics      | 1        | 0.75%   |
| Aquantia              | 1        | 0.75%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 55       | 40.15%  |
| Intel I211 Gigabit Network Connection                             | 19       | 13.87%  |
| Realtek RTL8125 2.5GbE Controller                                 | 15       | 10.95%  |
| Intel Ethernet Connection (2) I219-V                              | 5        | 3.65%   |
| Intel Ethernet Controller I225-V                                  | 4        | 2.92%   |
| Intel Ethernet Connection I217-V                                  | 4        | 2.92%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 2.19%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 2.19%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 2.19%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 2.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 1.46%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 1.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 1.46%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.73%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.73%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.73%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.73%   |
| Nvidia MCP73 Ethernet                                             | 1        | 0.73%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.73%   |
| Intel I210 Gigabit Network Connection                             | 1        | 0.73%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.73%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 0.73%   |
| Intel 82579V Gigabit Network Connection                           | 1        | 0.73%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.73%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 0.73%   |
| Intel 82541PI Gigabit Ethernet Controller                         | 1        | 0.73%   |
| Broadcom NetLink BCM5787 Gigabit Ethernet PCI Express             | 1        | 0.73%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1        | 0.73%   |
| ASIX AX88772B                                                     | 1        | 0.73%   |
| Aquantia Ethernet controller                                      | 1        | 0.73%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 119      | 65.38%  |
| WiFi     | 60       | 32.97%  |
| Modem    | 3        | 1.65%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 104      | 75.91%  |
| WiFi     | 33       | 24.09%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 68       | 56.2%   |
| 2     | 40       | 33.06%  |
| 3     | 10       | 8.26%   |
| 4     | 2        | 1.65%   |
| 0     | 1        | 0.83%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 96       | 78.69%  |
| Yes  | 26       | 21.31%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 29       | 47.54%  |
| Cambridge Silicon Radio  | 11       | 18.03%  |
| Realtek Semiconductor    | 8        | 13.11%  |
| Broadcom                 | 5        | 8.2%    |
| ASUSTek Computer         | 4        | 6.56%   |
| IMC Networks             | 2        | 3.28%   |
| Toshiba                  | 1        | 1.64%   |
| HTC (High Tech Computer) | 1        | 1.64%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 17       | 27.87%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 11       | 18.03%  |
| Realtek Bluetooth Radio                                              | 8        | 13.11%  |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 5        | 8.2%    |
| Intel Bluetooth wireless interface                                   | 4        | 6.56%   |
| Intel Bluetooth Device                                               | 4        | 6.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 3        | 4.92%   |
| IMC Networks Bluetooth Radio                                         | 2        | 3.28%   |
| Toshiba Atheros AR3012 Bluetooth                                     | 1        | 1.64%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 1        | 1.64%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 1.64%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 1        | 1.64%   |
| ASUS Bluetooth Device                                                | 1        | 1.64%   |
| ASUS Bluetooth Adapter                                               | 1        | 1.64%   |
| ASUS BCM20702A0                                                      | 1        | 1.64%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD                                             | 70       | 28.34%  |
| Nvidia                                          | 65       | 26.32%  |
| Intel                                           | 57       | 23.08%  |
| SteelSeries ApS                                 | 7        | 2.83%   |
| Logitech                                        | 7        | 2.83%   |
| C-Media Electronics                             | 6        | 2.43%   |
| Creative Labs                                   | 4        | 1.62%   |
| Texas Instruments                               | 3        | 1.21%   |
| Thesycon Systemsoftware & Consulting            | 2        | 0.81%   |
| Sennheiser Communications                       | 2        | 0.81%   |
| RODE Microphones                                | 2        | 0.81%   |
| Razer USA                                       | 2        | 0.81%   |
| Kingston Technology                             | 2        | 0.81%   |
| Xilinx                                          | 1        | 0.4%    |
| VIA Technologies                                | 1        | 0.4%    |
| Valve Software                                  | 1        | 0.4%    |
| Sony                                            | 1        | 0.4%    |
| Samson Technologies                             | 1        | 0.4%    |
| No brand                                        | 1        | 0.4%    |
| Native Instruments                              | 1        | 0.4%    |
| Licensed by Sony Computer Entertainment America | 1        | 0.4%    |
| JMTek                                           | 1        | 0.4%    |
| iConnectivity                                   | 1        | 0.4%    |
| Hewlett-Packard                                 | 1        | 0.4%    |
| GYROCOM C&C                                     | 1        | 0.4%    |
| GN Netcom                                       | 1        | 0.4%    |
| Generalplus Technology                          | 1        | 0.4%    |
| Corsair                                         | 1        | 0.4%    |
| Blue Microphones                                | 1        | 0.4%    |
| BEHRINGER International                         | 1        | 0.4%    |
| AKAI Professional M.I.                          | 1        | 0.4%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                    | 34       | 12.01%  |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                  | 14       | 4.95%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller         | 13       | 4.59%   |
| Nvidia GP107GL High Definition Audio Controller                             | 11       | 3.89%   |
| Nvidia GP104 High Definition Audio Controller                               | 11       | 3.89%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                         | 9        | 3.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller            | 8        | 2.83%   |
| Intel 200 Series PCH HD Audio                                               | 7        | 2.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller             | 7        | 2.47%   |
| AMD Navi 10 HDMI Audio                                                      | 7        | 2.47%   |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                   | 6        | 2.12%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                         | 6        | 2.12%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                | 6        | 2.12%   |
| Nvidia GK208 HDMI/DP Audio Controller                                       | 5        | 1.77%   |
| Intel Cannon Lake PCH cAVS                                                  | 5        | 1.77%   |
| Nvidia TU106 High Definition Audio Controller                               | 4        | 1.41%   |
| Nvidia GK104 HDMI Audio Controller                                          | 4        | 1.41%   |
| Nvidia GA104 High Definition Audio Controller                               | 4        | 1.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller         | 4        | 1.41%   |
| SteelSeries ApS Arctis Pro Wireless                                         | 3        | 1.06%   |
| Nvidia TU116 High Definition Audio Controller                               | 3        | 1.06%   |
| Nvidia GP106 High Definition Audio Controller                               | 3        | 1.06%   |
| Nvidia GA102 High Definition Audio Controller                               | 3        | 1.06%   |
| Intel 9 Series Chipset Family HD Audio Controller                           | 3        | 1.06%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                            | 3        | 1.06%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]               | 3        | 1.06%   |
| AMD SBx00 Azalia (Intel HDA)                                                | 3        | 1.06%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                         | 3        | 1.06%   |
| Thesycon Systemsoftware & Consulting DX7 Pro                                | 2        | 0.71%   |
| Texas Instruments PCM2902 Audio Codec                                       | 2        | 0.71%   |
| SteelSeries ApS SteelSeries Arctis 7                                        | 2        | 0.71%   |
| RODE Microphones RODE NT-USB                                                | 2        | 0.71%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller              | 2        | 0.71%   |
| Nvidia TU104 HD Audio Controller                                            | 2        | 0.71%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]               | 2        | 0.71%   |
| Nvidia GF119 HDMI Audio Controller                                          | 2        | 0.71%   |
| Nvidia GF106 High Definition Audio Controller                               | 2        | 0.71%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                     | 2        | 0.71%   |
| Intel Audio device                                                          | 2        | 0.71%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                    | 2        | 0.71%   |
| C-Media Electronics USB Audio Device                                        | 2        | 0.71%   |
| AMD Renoir Radeon High Definition Audio Controller                          | 2        | 0.71%   |
| Xilinx RME Digi9652 (Hammerfall)                                            | 1        | 0.35%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller | 1        | 0.35%   |
| Valve Software Valve VR Radio & HMD Mic                                     | 1        | 0.35%   |
| Texas Instruments SMSL Q5 AMP                                               | 1        | 0.35%   |
| SteelSeries ApS SteelSeries Arctis 5                                        | 1        | 0.35%   |
| SteelSeries ApS Arctis 7 wireless adapter                                   | 1        | 0.35%   |
| Sony DualShock 4 [CUH-ZCT2x]                                                | 1        | 0.35%   |
| Sennheiser Communications Headset [PC 8]                                    | 1        | 0.35%   |
| Sennheiser Communications EPOS H3PRO Dongle                                 | 1        | 0.35%   |
| Samson Technologies Q1U dynamic microphone                                  | 1        | 0.35%   |
| Razer USA Razer Seiren Mini                                                 | 1        | 0.35%   |
| Razer USA Kraken 7.1 V2                                                     | 1        | 0.35%   |
| Nvidia TU102 High Definition Audio Controller                               | 1        | 0.35%   |
| Nvidia MCP73 High Definition Audio                                          | 1        | 0.35%   |
| Nvidia MCP61 High Definition Audio                                          | 1        | 0.35%   |
| Nvidia High Definition Audio Controller                                     | 1        | 0.35%   |
| Nvidia GP102 HDMI Audio Controller                                          | 1        | 0.35%   |
| Nvidia GM204 High Definition Audio Controller                               | 1        | 0.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| G.Skill             | 24       | 22.43%  |
| Corsair             | 24       | 22.43%  |
| Crucial             | 13       | 12.15%  |
| Unknown             | 9        | 8.41%   |
| Samsung Electronics | 8        | 7.48%   |
| Kingston            | 8        | 7.48%   |
| SK Hynix            | 4        | 3.74%   |
| Team                | 3        | 2.8%    |
| Patriot             | 3        | 2.8%    |
| Micron Technology   | 3        | 2.8%    |
| A-DATA Technology   | 3        | 2.8%    |
| Unknown (ABCD)      | 1        | 0.93%   |
| Strontium           | 1        | 0.93%   |
| Ramaxel Technology  | 1        | 0.93%   |
| PNY                 | 1        | 0.93%   |
| Golden Empire       | 1        | 0.93%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s     | 5        | 4.03%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3533MT/s         | 3        | 2.42%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3466MT/s        | 3        | 2.42%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s          | 2        | 1.61%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s          | 2        | 1.61%   |
| G.Skill RAM F4-3600C18-16GTZR 16GB DIMM DDR4 3600MT/s        | 2        | 1.61%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s       | 2        | 1.61%   |
| G.Skill RAM F4-3200C16-8GTZRX 8GB DIMM DDR4 3200MT/s         | 2        | 1.61%   |
| G.Skill RAM F4-3200C16-16GVK 16384MB DIMM DDR4 3600MT/s      | 2        | 1.61%   |
| Crucial RAM CT4G4DFS824A.C8FBD2 4GB DIMM DDR4 2733MT/s       | 2        | 1.61%   |
| Corsair RAM CMZ16GX3M2A1600C10 8192MB DIMM DDR3 1600MT/s     | 2        | 1.61%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3200MT/s                  | 2        | 1.61%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                    | 1        | 0.81%   |
| Unknown RAM Module 4GB DIMM 400MT/s                          | 1        | 0.81%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 1        | 0.81%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 1        | 0.81%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                    | 1        | 0.81%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                     | 1        | 0.81%   |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 1        | 0.81%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                         | 1        | 0.81%   |
| Unknown RAM Module 1GB DIMM 800MT/s                          | 1        | 0.81%   |
| Unknown RAM 04S2666CL19DM 4GB DIMM DDR4 2667MT/s             | 1        | 0.81%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 1        | 0.81%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s        | 1        | 0.81%   |
| Team RAM Elite-800 2048MB DIMM SDRAM 2048MT/s                | 1        | 0.81%   |
| Team RAM Dark-1600 2GB DIMM DDR3 1600MT/s                    | 1        | 0.81%   |
| Strontium RAM SRT8G86U0-H9M 8GB DIMM DDR3 1333MT/s           | 1        | 0.81%   |
| SK Hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 1600MT/s         | 1        | 0.81%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s         | 1        | 0.81%   |
| SK Hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s         | 1        | 0.81%   |
| SK Hynix RAM HMT325U6BFR8C-H9 2GB DIMM DDR2 1066MT/s         | 1        | 0.81%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 1        | 0.81%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s        | 1        | 0.81%   |
| Samsung RAM M393B1K70CH0-YH9 8192MB DIMM DDR3 1333MT/s       | 1        | 0.81%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s          | 1        | 0.81%   |
| Samsung RAM M378B5673EH1-CH9 2048MB DIMM 1333MT/s            | 1        | 0.81%   |
| Samsung RAM M378B1G73AH0-K0 8GB DIMM DDR3 1600MT/s           | 1        | 0.81%   |
| Samsung RAM M378A1K43DB2-CTD 8GB DIMM DDR4 4333MT/s          | 1        | 0.81%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s          | 1        | 0.81%   |
| Ramaxel RAM RMUA5110ME78HAF-2666 8192MB DIMM DDR4 2667MT/s   | 1        | 0.81%   |
| PNY RAM 8GBF1X08QFHH36-135-K 8GB DIMM DDR4 2400MT/s          | 1        | 0.81%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s               | 1        | 0.81%   |
| Patriot RAM PSD34G16002 4GB DIMM DDR3 1600MT/s               | 1        | 0.81%   |
| Patriot RAM PSD32G13332 2GB DIMM DDR3 1333MT/s               | 1        | 0.81%   |
| Micron RAM 8ATF2G64AZ-3G2E1 16GB DIMM DDR4 3200MT/s          | 1        | 0.81%   |
| Micron RAM 18ASF1G72PZ-2G1A2 8GB RIMM DDR4 2133MT/s          | 1        | 0.81%   |
| Micron RAM 16JTF1G64AZ-1G6E1 8192MB DIMM DDR3 1600MT/s       | 1        | 0.81%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s            | 1        | 0.81%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s          | 1        | 0.81%   |
| Kingston RAM KHX1600C9S3L/8G 8192MB SODIMM DDR3 1600MT/s     | 1        | 0.81%   |
| Kingston RAM HP698650-154-KEB 4096MB DIMM DDR3 1600MT/s      | 1        | 0.81%   |
| Kingston RAM 99U5403-467.A00LF 8GB DIMM DDR3 1333MT/s        | 1        | 0.81%   |
| Golden Empire RAM CL4-4-4DDR2800 5 2GB DIMM DDR2 800MT/s     | 1        | 0.81%   |
| G.Skill RAM F4-3600C18-8GTZR 8GB DIMM DDR4 3600MT/s          | 1        | 0.81%   |
| G.Skill RAM F4-3600C16-8GTZNC 8GB DIMM DDR4 3800MT/s         | 1        | 0.81%   |
| G.Skill RAM F4-3600C16-8GTZ 8192MB DIMM DDR4 3333MT/s        | 1        | 0.81%   |
| G.Skill RAM F4-3600C16-32GVK 32GB DIMM DDR4 2800MT/s         | 1        | 0.81%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s          | 1        | 0.81%   |
| G.Skill RAM F4-3200C16-8GVGB 8192MB DIMM DDR4 3200MT/s       | 1        | 0.81%   |
| G.Skill RAM F4-3200C16-8GTZR 8192MB DIMM DDR4 3200MT/s       | 1        | 0.81%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 63       | 65.63%  |
| DDR3    | 21       | 21.88%  |
| Unknown | 4        | 4.17%   |
| SDRAM   | 3        | 3.13%   |
| LPDDR4  | 2        | 2.08%   |
| DDR2    | 2        | 2.08%   |
| DDR     | 1        | 1.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 89       | 95.7%   |
| SODIMM | 3        | 3.23%   |
| RIMM   | 1        | 1.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 48       | 47.06%  |
| 16384 | 21       | 20.59%  |
| 4096  | 19       | 18.63%  |
| 2048  | 9        | 8.82%   |
| 32768 | 4        | 3.92%   |
| 1024  | 1        | 0.98%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 27       | 24.11%  |
| 3600    | 15       | 13.39%  |
| 1333    | 11       | 9.82%   |
| 1600    | 10       | 8.93%   |
| 2400    | 7        | 6.25%   |
| 2133    | 6        | 5.36%   |
| 2667    | 4        | 3.57%   |
| 3533    | 3        | 2.68%   |
| 3466    | 3        | 2.68%   |
| 1867    | 3        | 2.68%   |
| 800     | 3        | 2.68%   |
| 3333    | 2        | 1.79%   |
| 3000    | 2        | 1.79%   |
| 2733    | 2        | 1.79%   |
| 1800    | 2        | 1.79%   |
| 4333    | 1        | 0.89%   |
| 3800    | 1        | 0.89%   |
| 3733    | 1        | 0.89%   |
| 3500    | 1        | 0.89%   |
| 3400    | 1        | 0.89%   |
| 2933    | 1        | 0.89%   |
| 2800    | 1        | 0.89%   |
| 2666    | 1        | 0.89%   |
| 2048    | 1        | 0.89%   |
| 1066    | 1        | 0.89%   |
| 400     | 1        | 0.89%   |
| Unknown | 1        | 0.89%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Brother Industries  | 2        | 66.67%  |
| Prolific Technology | 1        | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Prolific PL2305 Parallel Port | 1        | 33.33%  |
| Brother Printer               | 1        | 33.33%  |
| Brother HL-2130 series        | 1        | 33.33%  |

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


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Logitech                 | 17       | 50%     |
| Microsoft                | 4        | 11.76%  |
| Hewlett-Packard          | 2        | 5.88%   |
| Xiaomi                   | 1        | 2.94%   |
| Valve Software           | 1        | 2.94%   |
| Tobii Technology AB      | 1        | 2.94%   |
| Sunplus IT               | 1        | 2.94%   |
| Realtek Semiconductor    | 1        | 2.94%   |
| Razer USA                | 1        | 2.94%   |
| Microdia                 | 1        | 2.94%   |
| Leap Motion              | 1        | 2.94%   |
| Huawei Technologies      | 1        | 2.94%   |
| HTC (High Tech Computer) | 1        | 2.94%   |
| Unknown                  | 1        | 2.94%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Logitech Webcam C270                 | 5        | 14.71%  |
| Logitech HD Pro Webcam C920          | 5        | 14.71%  |
| Microsoft LifeCam HD-3000            | 2        | 5.88%   |
| Logitech Webcam C310                 | 2        | 5.88%   |
| HP Webcam HD 2300                    | 2        | 5.88%   |
| Xiaomi Mi/Redmi series (PTP + ADB)   | 1        | 2.94%   |
| Valve Software 3D Camera             | 1        | 2.94%   |
| Tobii AB EyeChip                     | 1        | 2.94%   |
| Sunplus IT AUKEY PC-LM1 USB Camera   | 1        | 2.94%   |
| Realtek Webcam                       | 1        | 2.94%   |
| Razer USA Gaming Webcam [Kiyo]       | 1        | 2.94%   |
| Microsoft LifeCam VX-2000            | 1        | 2.94%   |
| Microsoft LifeCam Cinema             | 1        | 2.94%   |
| Microdia USB 2.0 Camera              | 1        | 2.94%   |
| Logitech StreamCam                   | 1        | 2.94%   |
| Logitech HD Webcam C525              | 1        | 2.94%   |
| Logitech HD Webcam B910              | 1        | 2.94%   |
| Logitech C922 Pro Stream Webcam      | 1        | 2.94%   |
| Logitech BRIO                        | 1        | 2.94%   |
| Leap Motion Controller               | 1        | 2.94%   |
| Huawei UVC Camera                    | 1        | 2.94%   |
| HTC (High Tech Computer) VIVE COSMOS | 1        | 2.94%   |
| Unknown                              | 1        | 2.94%   |

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


| Vendor     | Desktops | Percent |
|------------|----------|---------|
| HID Global | 1        | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| HID Global USB Reader V3 | 1        | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 105      | 85.37%  |
| 1     | 17       | 13.82%  |
| 2     | 1        | 0.81%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type             | Desktops | Percent |
|------------------|----------|---------|
| Network          | 4        | 23.53%  |
| Net/ethernet     | 4        | 23.53%  |
| Graphics card    | 3        | 17.65%  |
| Net/wireless     | 2        | 11.76%  |
| Unassigned class | 1        | 5.88%   |
| Dvb card         | 1        | 5.88%   |
| Chipcard         | 1        | 5.88%   |
| Bluetooth        | 1        | 5.88%   |

