Ubuntu Budgie 20.04 - Tested Hardware & Statistics
--------------------------------------------------

A project to collect tested hardware configurations for Ubuntu Budgie 20.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_Budgie_20.04/Desktop/README.md) and [notebooks](/Dist/Ubuntu_Budgie_20.04/Notebook/README.md).

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

| Vendor    | Model                       | Form-Factor | Probe                                                      | Date         |
|-----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| TUXEDO    | P95_HP                      | Notebook    | [859d674cfe](https://linux-hardware.org/?probe=859d674cfe) | Dec 02, 2021 |
| Dell      | XPS 13 9365                 | Convertible | [e62e98d46d](https://linux-hardware.org/?probe=e62e98d46d) | Nov 30, 2021 |
| ASUSTek   | ASUS TUF Gaming F15 FX50... | Notebook    | [cd9d182e6e](https://linux-hardware.org/?probe=cd9d182e6e) | Nov 22, 2021 |
| HP        | 0A5Ch                       | Desktop     | [4858eb5c73](https://linux-hardware.org/?probe=4858eb5c73) | Nov 21, 2021 |
| Dell      | Vostro 1700                 | Notebook    | [2aee39d91c](https://linux-hardware.org/?probe=2aee39d91c) | Nov 21, 2021 |
| Gigabyte  | B560M AORUS ELITE           | Desktop     | [b397fce5b8](https://linux-hardware.org/?probe=b397fce5b8) | Nov 20, 2021 |
| Unknown   | Unknown                     | Notebook    | [ed14b60c7a](https://linux-hardware.org/?probe=ed14b60c7a) | Nov 05, 2021 |
| Dell      | Inspiron 5515               | Notebook    | [35d04dc3b9](https://linux-hardware.org/?probe=35d04dc3b9) | Nov 01, 2021 |
| TUXEDO    | Book XP15 / XP17 Gen12      | Notebook    | [4a518a759f](https://linux-hardware.org/?probe=4a518a759f) | Oct 25, 2021 |
| Apple     | Mac-AA95B1DDAB278B95 iMa... | All in one  | [90e49546c2](https://linux-hardware.org/?probe=90e49546c2) | Oct 21, 2021 |
| Acer      | Aspire 4752                 | Notebook    | [c4e21818b1](https://linux-hardware.org/?probe=c4e21818b1) | Oct 20, 2021 |
| HP        | 0A5Ch                       | Desktop     | [8d102a03f6](https://linux-hardware.org/?probe=8d102a03f6) | Oct 19, 2021 |
| HP        | 0A5Ch                       | Desktop     | [139efd1a3d](https://linux-hardware.org/?probe=139efd1a3d) | Oct 19, 2021 |
| TUXEDO    | InfinityBook S 15 Gen6      | Notebook    | [b665ef94e7](https://linux-hardware.org/?probe=b665ef94e7) | Oct 01, 2021 |
| ASUSTek   | X302LJ                      | Notebook    | [281beb5fe7](https://linux-hardware.org/?probe=281beb5fe7) | Sep 23, 2021 |
| HP        | ZBook Studio G3             | Notebook    | [d0b29312b8](https://linux-hardware.org/?probe=d0b29312b8) | Aug 31, 2021 |
| HP        | x360 310 G2 PC              | Notebook    | [429d94dd0f](https://linux-hardware.org/?probe=429d94dd0f) | Aug 31, 2021 |
| Dell      | XPS 15 9560                 | Notebook    | [55f224e5c3](https://linux-hardware.org/?probe=55f224e5c3) | Aug 26, 2021 |
| TUXEDO    | InfinityBook S 15 Gen6      | Notebook    | [aabe23e7a8](https://linux-hardware.org/?probe=aabe23e7a8) | Aug 20, 2021 |
| TUXEDO    | Book XP1511                 | Notebook    | [7526222677](https://linux-hardware.org/?probe=7526222677) | Aug 15, 2021 |
| TUXEDO    | Book XP1511                 | Notebook    | [3312e66e9f](https://linux-hardware.org/?probe=3312e66e9f) | Aug 15, 2021 |
| Lenovo    | ThinkPad E490 20N8S07A00    | Notebook    | [bd4a6e1eaf](https://linux-hardware.org/?probe=bd4a6e1eaf) | Aug 05, 2021 |
| ASUSTek   | P7P55D                      | Desktop     | [c62d162396](https://linux-hardware.org/?probe=c62d162396) | Aug 02, 2021 |
| ASUSTek   | PRIME B450M-A               | Desktop     | [7b213037a5](https://linux-hardware.org/?probe=7b213037a5) | Jul 31, 2021 |
| ASUSTek   | P7P55D                      | Desktop     | [cd96dbf86a](https://linux-hardware.org/?probe=cd96dbf86a) | Jul 30, 2021 |
| ASUSTek   | P7P55D                      | Desktop     | [4d91af39ee](https://linux-hardware.org/?probe=4d91af39ee) | Jul 30, 2021 |
| TUXEDO    | TUXEDO_Book_XA1510          | Notebook    | [bc0cfb6203](https://linux-hardware.org/?probe=bc0cfb6203) | Jul 29, 2021 |
| TUXEDO    | P95_HR                      | Notebook    | [60f8b3ac61](https://linux-hardware.org/?probe=60f8b3ac61) | Jul 26, 2021 |
| Fujitsu   | LIFEBOOK E756               | Notebook    | [6afad8262f](https://linux-hardware.org/?probe=6afad8262f) | Jul 26, 2021 |
| ASUSTek   | P7P55D                      | Desktop     | [b983e48d71](https://linux-hardware.org/?probe=b983e48d71) | Jul 24, 2021 |
| ASUSTek   | P7P55D                      | Desktop     | [2335f32be7](https://linux-hardware.org/?probe=2335f32be7) | Jul 22, 2021 |
| ASUSTek   | PRIME B450M-A               | Desktop     | [abea66177f](https://linux-hardware.org/?probe=abea66177f) | Jul 20, 2021 |
| Fujitsu   | D3227-A1 S26361-D3227-A1    | Desktop     | [157b9695ae](https://linux-hardware.org/?probe=157b9695ae) | Jul 15, 2021 |
| TUXEDO    | InfinityBook Pro 14 Gen6    | Notebook    | [bbda9475cc](https://linux-hardware.org/?probe=bbda9475cc) | Jul 02, 2021 |
| Dell      | 048DY8 A01                  | Desktop     | [04c41fe4c2](https://linux-hardware.org/?probe=04c41fe4c2) | Jun 30, 2021 |
| Fujitsu   | LIFEBOOK E756               | Notebook    | [1c72549a32](https://linux-hardware.org/?probe=1c72549a32) | Jun 29, 2021 |
| HP        | Notebook                    | Notebook    | [43b2a0f397](https://linux-hardware.org/?probe=43b2a0f397) | Jun 16, 2021 |
| Acer      | TravelMate P446-M           | Notebook    | [0c47a21c07](https://linux-hardware.org/?probe=0c47a21c07) | Jun 14, 2021 |
| Toshiba   | Satellite P300              | Notebook    | [f19856109a](https://linux-hardware.org/?probe=f19856109a) | Jun 09, 2021 |
| Toshiba   | Satellite P300              | Notebook    | [a53633e2b1](https://linux-hardware.org/?probe=a53633e2b1) | Jun 09, 2021 |
| Toshiba   | Satellite P300              | Notebook    | [3984b7401d](https://linux-hardware.org/?probe=3984b7401d) | Jun 02, 2021 |
| Acer      | Aspire A515-44              | Notebook    | [0f80210c56](https://linux-hardware.org/?probe=0f80210c56) | Jun 02, 2021 |
| Acer      | Aspire A515-44              | Notebook    | [8f5cb26311](https://linux-hardware.org/?probe=8f5cb26311) | Jun 02, 2021 |
| Dell      | Latitude E6410              | Notebook    | [124fdcdccb](https://linux-hardware.org/?probe=124fdcdccb) | May 25, 2021 |
| Dell      | Latitude E6410              | Notebook    | [5715f12aee](https://linux-hardware.org/?probe=5715f12aee) | May 24, 2021 |
| Toshiba   | Satellite P300              | Notebook    | [34d9279028](https://linux-hardware.org/?probe=34d9279028) | May 24, 2021 |
| TUXEDO    | Unknown                     | Notebook    | [d39c5e1f70](https://linux-hardware.org/?probe=d39c5e1f70) | May 23, 2021 |
| ASUSTek   | K45DR                       | Notebook    | [583824ad87](https://linux-hardware.org/?probe=583824ad87) | May 21, 2021 |
| Acer      | Aspire A515-51G             | Notebook    | [ad8fffaf05](https://linux-hardware.org/?probe=ad8fffaf05) | May 20, 2021 |
| ASUSTek   | N53SM                       | Notebook    | [fb4667be90](https://linux-hardware.org/?probe=fb4667be90) | May 19, 2021 |
| HP        | EliteBook 850 G1            | Notebook    | [5533f32102](https://linux-hardware.org/?probe=5533f32102) | May 18, 2021 |
| Toshiba   | Satellite P300              | Notebook    | [62ac427393](https://linux-hardware.org/?probe=62ac427393) | May 16, 2021 |
| Dell      | XPS 15 9500                 | Notebook    | [fbba77b949](https://linux-hardware.org/?probe=fbba77b949) | Apr 28, 2021 |
| Dell      | XPS 15 9500                 | Notebook    | [aba1faeb69](https://linux-hardware.org/?probe=aba1faeb69) | Apr 28, 2021 |
| ASUSTek   | Maximus VIII IMPACT         | Desktop     | [2c0a43e573](https://linux-hardware.org/?probe=2c0a43e573) | Apr 24, 2021 |
| Gigabyte  | Z77X-D3H                    | Desktop     | [28751098a6](https://linux-hardware.org/?probe=28751098a6) | Apr 23, 2021 |
| HP        | Pavilion g6                 | Notebook    | [e22e43c0b5](https://linux-hardware.org/?probe=e22e43c0b5) | Apr 22, 2021 |
| TUXEDO    | Polaris 17 AMD Gen1         | Notebook    | [0d25287be0](https://linux-hardware.org/?probe=0d25287be0) | Apr 16, 2021 |
| Sony      | SVS13A25PBS                 | Notebook    | [c693fe6603](https://linux-hardware.org/?probe=c693fe6603) | Apr 14, 2021 |
| ASRock    | X370 Gaming-ITX/ac          | Desktop     | [e0fa7ade7a](https://linux-hardware.org/?probe=e0fa7ade7a) | Apr 06, 2021 |
| MSI       | CX62 6QL                    | Notebook    | [fc3756c451](https://linux-hardware.org/?probe=fc3756c451) | Apr 05, 2021 |
| MSI       | CX62 6QL                    | Notebook    | [41b87e1036](https://linux-hardware.org/?probe=41b87e1036) | Apr 05, 2021 |
| TUXEDO    | Aura 15 Gen1                | Notebook    | [7fbbadb983](https://linux-hardware.org/?probe=7fbbadb983) | Mar 27, 2021 |
| HP        | ProBook 640 G2              | Notebook    | [39e97c482d](https://linux-hardware.org/?probe=39e97c482d) | Mar 24, 2021 |
| ASUSTek   | Z77-A                       | Desktop     | [ca21510412](https://linux-hardware.org/?probe=ca21510412) | Mar 23, 2021 |
| Lenovo    | ThinkPad P43s 20RHS00100    | Notebook    | [835766dc3a](https://linux-hardware.org/?probe=835766dc3a) | Mar 21, 2021 |
| Lenovo    | ThinkPad P43s 20RHS00100    | Notebook    | [fb954b806d](https://linux-hardware.org/?probe=fb954b806d) | Mar 21, 2021 |
| TUXEDO    | InfinityBook S 14 Gen6      | Notebook    | [153e336d81](https://linux-hardware.org/?probe=153e336d81) | Mar 21, 2021 |
| TUXEDO    | InfinityBook S 14 Gen6      | Notebook    | [fa3b417784](https://linux-hardware.org/?probe=fa3b417784) | Mar 21, 2021 |
| ASUSTek   | P7P55D-E LX                 | Desktop     | [83f55d5bf7](https://linux-hardware.org/?probe=83f55d5bf7) | Mar 20, 2021 |
| HP        | 3031h                       | Desktop     | [ee5e7baf77](https://linux-hardware.org/?probe=ee5e7baf77) | Mar 16, 2021 |
| ASUSTek   | PRIME B450-PLUS             | Desktop     | [79b5c4e048](https://linux-hardware.org/?probe=79b5c4e048) | Mar 07, 2021 |
| Fujitsu   | LIFEBOOK E756               | Notebook    | [2e450a6687](https://linux-hardware.org/?probe=2e450a6687) | Mar 06, 2021 |
| HP        | ENVY 15                     | Notebook    | [5c1bfc1459](https://linux-hardware.org/?probe=5c1bfc1459) | Mar 05, 2021 |
| HP        | Spectre x360 Convertible... | Convertible | [d1866f15b4](https://linux-hardware.org/?probe=d1866f15b4) | Mar 02, 2021 |
| TUXEDO    | Polaris 15 AMD Gen1         | Notebook    | [12212ad362](https://linux-hardware.org/?probe=12212ad362) | Feb 27, 2021 |
| Dell      | Latitude 5590               | Notebook    | [95fa6d8570](https://linux-hardware.org/?probe=95fa6d8570) | Feb 26, 2021 |
| Dell      | Latitude 7490               | Notebook    | [c72d91886b](https://linux-hardware.org/?probe=c72d91886b) | Feb 25, 2021 |
| Unknown   | Unknown                     | Desktop     | [f97163d774](https://linux-hardware.org/?probe=f97163d774) | Feb 24, 2021 |
| HP        | Spectre x360 Convertible... | Convertible | [10e0380862](https://linux-hardware.org/?probe=10e0380862) | Feb 19, 2021 |
| ASUSTek   | ROG STRIX H470-I GAMING     | Desktop     | [f747681c25](https://linux-hardware.org/?probe=f747681c25) | Feb 19, 2021 |
| ASUSTek   | Maximus VIII IMPACT         | Desktop     | [ffbb4c8bec](https://linux-hardware.org/?probe=ffbb4c8bec) | Feb 17, 2021 |
| MSI       | A320M PRO-VD PLUS           | Desktop     | [24a9ae34ed](https://linux-hardware.org/?probe=24a9ae34ed) | Feb 13, 2021 |
| Gigabyte  | B450M DS3H-CF               | Desktop     | [5f9a9ff276](https://linux-hardware.org/?probe=5f9a9ff276) | Feb 13, 2021 |
| Gigabyte  | B450M DS3H-CF               | Desktop     | [d8069f1e01](https://linux-hardware.org/?probe=d8069f1e01) | Feb 12, 2021 |
| Lenovo    | ThinkPad P1 20MES01400      | Notebook    | [640ff77fea](https://linux-hardware.org/?probe=640ff77fea) | Feb 11, 2021 |
| HP        | Spectre x360 Convertible... | Convertible | [13979999ed](https://linux-hardware.org/?probe=13979999ed) | Feb 07, 2021 |
| HP        | ZBook Studio G3             | Notebook    | [6f207e9b7f](https://linux-hardware.org/?probe=6f207e9b7f) | Feb 04, 2021 |
| Dell      | Latitude 5580               | Notebook    | [b9ac308476](https://linux-hardware.org/?probe=b9ac308476) | Feb 04, 2021 |
| ASUSTek   | X551CA                      | Notebook    | [1857586e3a](https://linux-hardware.org/?probe=1857586e3a) | Feb 03, 2021 |
| ASUSTek   | N53SM                       | Notebook    | [e4689416a8](https://linux-hardware.org/?probe=e4689416a8) | Feb 02, 2021 |
| Apple     | Mac-942B5BF58194151B        | All in one  | [3d2867cd98](https://linux-hardware.org/?probe=3d2867cd98) | Jan 30, 2021 |
| HP        | Laptop 15-da0xxx            | Notebook    | [3d5f8c3cd2](https://linux-hardware.org/?probe=3d5f8c3cd2) | Jan 21, 2021 |
| MSI       | GP73 Leopard 8RE            | Notebook    | [c554fa2a9d](https://linux-hardware.org/?probe=c554fa2a9d) | Jan 17, 2021 |
| ASUSTek   | N53SM                       | Notebook    | [41bf2f638a](https://linux-hardware.org/?probe=41bf2f638a) | Jan 13, 2021 |
| HP        | 1589                        | Desktop     | [fe93b414cb](https://linux-hardware.org/?probe=fe93b414cb) | Jan 09, 2021 |
| MSI       | GE70 2PC\2PE                | Notebook    | [805e6fac6b](https://linux-hardware.org/?probe=805e6fac6b) | Jan 08, 2021 |
| ASUSTek   | TUF Z370-PLUS GAMING        | Desktop     | [276dda536a](https://linux-hardware.org/?probe=276dda536a) | Jan 06, 2021 |
| ASUSTek   | TUF Z370-PLUS GAMING        | Desktop     | [e894de170a](https://linux-hardware.org/?probe=e894de170a) | Jan 06, 2021 |
| Acer      | TravelMate P446-M           | Notebook    | [a0706cf84a](https://linux-hardware.org/?probe=a0706cf84a) | Jan 06, 2021 |
| Acer      | TravelMate P446-M           | Notebook    | [dd100bc162](https://linux-hardware.org/?probe=dd100bc162) | Jan 04, 2021 |
| Acer      | Aspire V3-771               | Notebook    | [450e8c59cc](https://linux-hardware.org/?probe=450e8c59cc) | Jan 02, 2021 |
| Acer      | Aspire V3-771               | Notebook    | [4122ea4b04](https://linux-hardware.org/?probe=4122ea4b04) | Jan 02, 2021 |
| ASUSTek   | TUF Z370-PLUS GAMING        | Desktop     | [8c4fc87665](https://linux-hardware.org/?probe=8c4fc87665) | Jan 02, 2021 |
| ASUSTek   | TUF Z370-PLUS GAMING        | Desktop     | [a80e8c5eb0](https://linux-hardware.org/?probe=a80e8c5eb0) | Jan 02, 2021 |
| Acer      | TravelMate P446-M           | Notebook    | [d040cbadcc](https://linux-hardware.org/?probe=d040cbadcc) | Jan 02, 2021 |
| Gigabyte  | B550I AORUS PRO AX          | Desktop     | [1effa5938b](https://linux-hardware.org/?probe=1effa5938b) | Dec 31, 2020 |
| Intel     | NUC8BEB J72693-307          | Mini pc     | [0d1e39a79a](https://linux-hardware.org/?probe=0d1e39a79a) | Dec 27, 2020 |
| Intel     | NUC8BEB J72693-307          | Mini pc     | [e06953d2f0](https://linux-hardware.org/?probe=e06953d2f0) | Dec 25, 2020 |
| HP        | Spectre x360 Convertible... | Convertible | [6260a9fb0f](https://linux-hardware.org/?probe=6260a9fb0f) | Dec 22, 2020 |
| Intel     | NUC8BEB J72693-307          | Mini pc     | [c671dc11ee](https://linux-hardware.org/?probe=c671dc11ee) | Dec 20, 2020 |
| Gigabyte  | B550M AORUS PRO-P           | Desktop     | [c32461bc20](https://linux-hardware.org/?probe=c32461bc20) | Dec 19, 2020 |
| TUXEDO    | Aura 15 Gen1                | Notebook    | [c85ead3218](https://linux-hardware.org/?probe=c85ead3218) | Dec 19, 2020 |
| Apple     | Mac-F4238CC8 PVT            | All in one  | [05c93972e0](https://linux-hardware.org/?probe=05c93972e0) | Dec 16, 2020 |
| ASUSTek   | F9E                         | Notebook    | [0070b5eda7](https://linux-hardware.org/?probe=0070b5eda7) | Dec 12, 2020 |
| Intel     | NUC8BEB J72693-307          | Mini pc     | [27239584b2](https://linux-hardware.org/?probe=27239584b2) | Dec 12, 2020 |
| HP        | EliteBook 850 G1            | Notebook    | [671d151ab9](https://linux-hardware.org/?probe=671d151ab9) | Dec 12, 2020 |
| ASUSTek   | ZenBook UX425EA_UX425EA     | Notebook    | [a603cda0d7](https://linux-hardware.org/?probe=a603cda0d7) | Dec 12, 2020 |
| HP        | Pavilion Gaming Laptop 1... | Notebook    | [c04e40195e](https://linux-hardware.org/?probe=c04e40195e) | Dec 11, 2020 |
| Fujitsu   | LIFEBOOK E756               | Notebook    | [ccb7d3edd7](https://linux-hardware.org/?probe=ccb7d3edd7) | Dec 10, 2020 |
| ASUSTek   | PRIME A320M-K/BR            | Desktop     | [d65d3733f6](https://linux-hardware.org/?probe=d65d3733f6) | Dec 07, 2020 |
| Intel     | NUC8BEB J72693-307          | Mini pc     | [c620f65d2b](https://linux-hardware.org/?probe=c620f65d2b) | Nov 25, 2020 |
| Acer      | Aspire E1-532               | Notebook    | [c4db9a001e](https://linux-hardware.org/?probe=c4db9a001e) | Nov 25, 2020 |
| Apple     | Mac-F4238CC8 PVT            | All in one  | [732043cc5f](https://linux-hardware.org/?probe=732043cc5f) | Nov 21, 2020 |
| HP        | Laptop 17-ak0xx             | Notebook    | [81d47c5bbd](https://linux-hardware.org/?probe=81d47c5bbd) | Nov 14, 2020 |
| HP        | Laptop 17-ak0xx             | Notebook    | [e51b8a2e3d](https://linux-hardware.org/?probe=e51b8a2e3d) | Nov 14, 2020 |
| HP        | Laptop 17-ak0xx             | Notebook    | [bb3de0e33d](https://linux-hardware.org/?probe=bb3de0e33d) | Nov 08, 2020 |
| Fujitsu   | LIFEBOOK E756               | Notebook    | [3d1548beea](https://linux-hardware.org/?probe=3d1548beea) | Nov 06, 2020 |
| Sony      | SVS13A25PBS                 | Notebook    | [ec54069f90](https://linux-hardware.org/?probe=ec54069f90) | Nov 06, 2020 |
| TUXEDO    | Unknown                     | Notebook    | [ccab34bcd7](https://linux-hardware.org/?probe=ccab34bcd7) | Nov 03, 2020 |
| Apple     | Mac-F2218FC8                | All in one  | [b72a5d9506](https://linux-hardware.org/?probe=b72a5d9506) | Oct 31, 2020 |
| Gigabyte  | Z170X-Gaming 3              | Desktop     | [58b6426d57](https://linux-hardware.org/?probe=58b6426d57) | Oct 30, 2020 |
| Fujitsu   | LIFEBOOK E756               | Notebook    | [7e515b01ea](https://linux-hardware.org/?probe=7e515b01ea) | Oct 30, 2020 |
| Dell      | Latitude E6540              | Notebook    | [45ad219146](https://linux-hardware.org/?probe=45ad219146) | Oct 29, 2020 |
| HP        | Elite x2 1012 G1            | Notebook    | [7a593747a4](https://linux-hardware.org/?probe=7a593747a4) | Oct 26, 2020 |
| HP        | Elite x2 1012 G1            | Notebook    | [82ff46fe7f](https://linux-hardware.org/?probe=82ff46fe7f) | Oct 26, 2020 |
| HP        | Stream 7 Tablet             | Tablet      | [1cb5fb4518](https://linux-hardware.org/?probe=1cb5fb4518) | Oct 25, 2020 |
| ASUSTek   | Maximus VIII IMPACT         | Desktop     | [b5a98b7ffa](https://linux-hardware.org/?probe=b5a98b7ffa) | Oct 24, 2020 |
| Dell      | Latitude 5400               | Notebook    | [9594ef7488](https://linux-hardware.org/?probe=9594ef7488) | Oct 20, 2020 |
| Dell      | Latitude 5400               | Notebook    | [d016f37257](https://linux-hardware.org/?probe=d016f37257) | Oct 20, 2020 |
| HP        | 1998                        | Desktop     | [e8076a87a0](https://linux-hardware.org/?probe=e8076a87a0) | Oct 20, 2020 |
| Apple     | Mac-F4208DC8 PVT            | Desktop     | [25565a3bbf](https://linux-hardware.org/?probe=25565a3bbf) | Oct 19, 2020 |
| Apple     | Mac-F4208DC8 PVT            | Desktop     | [3aa954c07b](https://linux-hardware.org/?probe=3aa954c07b) | Oct 19, 2020 |
| MSI       | MAG X570 TOMAHAWK WIFI      | Desktop     | [7c78d9b4da](https://linux-hardware.org/?probe=7c78d9b4da) | Oct 18, 2020 |
| MSI       | MAG X570 TOMAHAWK WIFI      | Desktop     | [ca85fa1d88](https://linux-hardware.org/?probe=ca85fa1d88) | Oct 18, 2020 |
| AAEON     | UP-APL01 V0.4               | Desktop     | [3d2cb2e4d1](https://linux-hardware.org/?probe=3d2cb2e4d1) | Oct 12, 2020 |
| AAEON     | UP-APL01 V0.4               | Desktop     | [16d3bf5578](https://linux-hardware.org/?probe=16d3bf5578) | Oct 12, 2020 |
| HP        | Laptop 14-dk0xxx            | Notebook    | [2f2b699bf6](https://linux-hardware.org/?probe=2f2b699bf6) | Oct 11, 2020 |
| Lenovo    | ThinkPad P43s 20RH0013US    | Notebook    | [e540cc2901](https://linux-hardware.org/?probe=e540cc2901) | Oct 09, 2020 |
| Lenovo    | 20SL                        | Notebook    | [bda45231ce](https://linux-hardware.org/?probe=bda45231ce) | Oct 07, 2020 |
| Apple     | MacBookPro8,1               | Notebook    | [3f17f3c6e8](https://linux-hardware.org/?probe=3f17f3c6e8) | Oct 06, 2020 |
| TUXEDO    | P7xxTM1                     | Notebook    | [1c64a38e1e](https://linux-hardware.org/?probe=1c64a38e1e) | Oct 05, 2020 |
| MSI       | MAG X570 TOMAHAWK WIFI      | Desktop     | [4a62de4c07](https://linux-hardware.org/?probe=4a62de4c07) | Oct 01, 2020 |
| MSI       | Modern 14 A10RB             | Notebook    | [67d9e1d5e4](https://linux-hardware.org/?probe=67d9e1d5e4) | Sep 30, 2020 |
| ASRock    | B550 Phantom Gaming 4       | Desktop     | [a996c3d55c](https://linux-hardware.org/?probe=a996c3d55c) | Sep 29, 2020 |
| Samsung   | 905S3G/906S3G/915S3G/930... | Notebook    | [2ebce35736](https://linux-hardware.org/?probe=2ebce35736) | Sep 29, 2020 |
| ASUSTek   | UX430UQ                     | Notebook    | [c201929d1a](https://linux-hardware.org/?probe=c201929d1a) | Sep 27, 2020 |
| ASUSTek   | P9X79 DELUXE                | Desktop     | [5b7738af52](https://linux-hardware.org/?probe=5b7738af52) | Sep 23, 2020 |
| Dell      | Latitude 5400               | Notebook    | [763c1287a5](https://linux-hardware.org/?probe=763c1287a5) | Sep 23, 2020 |
| Gigabyte  | B360 AORUS GAMING 3-CF      | Desktop     | [663a5ef41a](https://linux-hardware.org/?probe=663a5ef41a) | Sep 21, 2020 |
| Dell      | 0200DY A03                  | Desktop     | [e91f9c04b9](https://linux-hardware.org/?probe=e91f9c04b9) | Sep 21, 2020 |
| Gigabyte  | Z68M-D2H                    | Desktop     | [d746ae5a52](https://linux-hardware.org/?probe=d746ae5a52) | Sep 19, 2020 |
| HP        | ProBook 4730s               | Notebook    | [4363da5d51](https://linux-hardware.org/?probe=4363da5d51) | Sep 19, 2020 |
| Dell      | Inspiron 7560               | Notebook    | [4a1a3140a7](https://linux-hardware.org/?probe=4a1a3140a7) | Sep 15, 2020 |
| Radxa     | ROCK Pi 4A                  | Soc         | [b335776d4a](https://linux-hardware.org/?probe=b335776d4a) | Sep 14, 2020 |
| MSI       | MAG X570 TOMAHAWK WIFI      | Desktop     | [1037d2b746](https://linux-hardware.org/?probe=1037d2b746) | Sep 09, 2020 |
| MSI       | MAG X570 TOMAHAWK WIFI      | Desktop     | [b3d6fb36eb](https://linux-hardware.org/?probe=b3d6fb36eb) | Sep 08, 2020 |
| Fujitsu   | LIFEBOOK A512               | Notebook    | [0ce417fed7](https://linux-hardware.org/?probe=0ce417fed7) | Sep 08, 2020 |
| Gigabyte  | Z390 DESIGNARE-CF           | Desktop     | [d36f3124d1](https://linux-hardware.org/?probe=d36f3124d1) | Sep 06, 2020 |
| ASUSTek   | ROG STRIX X470-F GAMING     | Desktop     | [e90f4fb0e5](https://linux-hardware.org/?probe=e90f4fb0e5) | Sep 06, 2020 |
| PCSMART   | 6.0                         | Desktop     | [e95fadbdfe](https://linux-hardware.org/?probe=e95fadbdfe) | Sep 05, 2020 |
| MSI       | Z97 GAMING 5                | Desktop     | [3f1b387a92](https://linux-hardware.org/?probe=3f1b387a92) | Sep 04, 2020 |
| HP        | Pavilion g6                 | Notebook    | [522ff3c9c7](https://linux-hardware.org/?probe=522ff3c9c7) | Sep 03, 2020 |
| Dell      | G7 7588                     | Notebook    | [d6cd49b568](https://linux-hardware.org/?probe=d6cd49b568) | Sep 02, 2020 |
| Intel     | NUC8BEB J72693-307          | Mini pc     | [bc9c588fd8](https://linux-hardware.org/?probe=bc9c588fd8) | Aug 30, 2020 |
| Intel     | NUC8BEB J72693-307          | Mini pc     | [5377671241](https://linux-hardware.org/?probe=5377671241) | Aug 27, 2020 |
| Intel     | NUC8BEB J72693-307          | Mini pc     | [2ceaeaf356](https://linux-hardware.org/?probe=2ceaeaf356) | Aug 27, 2020 |
| Dell      | Inspiron 11-3168            | Notebook    | [bf9ae88e59](https://linux-hardware.org/?probe=bf9ae88e59) | Aug 20, 2020 |
| Dell      | Inspiron 11-3168            | Notebook    | [c168661ada](https://linux-hardware.org/?probe=c168661ada) | Aug 20, 2020 |
| Intel     | NUC8BEB J72693-307          | Mini pc     | [957889f93d](https://linux-hardware.org/?probe=957889f93d) | Aug 18, 2020 |
| ASUSTek   | P9X79 DELUXE                | Desktop     | [75f32f4978](https://linux-hardware.org/?probe=75f32f4978) | Aug 16, 2020 |
| MSI       | Prestige 15 A10SC           | Notebook    | [4cea086204](https://linux-hardware.org/?probe=4cea086204) | Aug 16, 2020 |
| Dell      | Inspiron 11-3168            | Notebook    | [d24b0f8f6a](https://linux-hardware.org/?probe=d24b0f8f6a) | Aug 16, 2020 |
| Intel     | NUC8BEB J72693-307          | Mini pc     | [2703fac7a8](https://linux-hardware.org/?probe=2703fac7a8) | Aug 16, 2020 |
| Dell      | Inspiron 11-3168            | Notebook    | [6bdfa3f1ad](https://linux-hardware.org/?probe=6bdfa3f1ad) | Aug 16, 2020 |
| Intel     | NUC8BEB J72693-307          | Mini pc     | [ac036c1715](https://linux-hardware.org/?probe=ac036c1715) | Aug 14, 2020 |
| Gigabyte  | P55A-UD4P                   | Desktop     | [c908fd4599](https://linux-hardware.org/?probe=c908fd4599) | Aug 07, 2020 |
| Standard  | MT40II                      | Notebook    | [974f5398ca](https://linux-hardware.org/?probe=974f5398ca) | Aug 06, 2020 |
| Lenovo    | ThinkPad T430s 23539WU      | Notebook    | [3ff86ae696](https://linux-hardware.org/?probe=3ff86ae696) | Aug 03, 2020 |
| Samsung   | 340XAA/350XAA/550XAA        | Notebook    | [5caeef5a4f](https://linux-hardware.org/?probe=5caeef5a4f) | Aug 03, 2020 |
| Samsung   | 340XAA/350XAA/550XAA        | Notebook    | [89e1df883c](https://linux-hardware.org/?probe=89e1df883c) | Aug 01, 2020 |
| Samsung   | 340XAA/350XAA/550XAA        | Notebook    | [545f6ed65f](https://linux-hardware.org/?probe=545f6ed65f) | Jul 31, 2020 |
| ASUSTek   | P8H77-M PRO                 | Desktop     | [d943208a7c](https://linux-hardware.org/?probe=d943208a7c) | Jul 30, 2020 |
| Apple     | MacBook3,1                  | Notebook    | [7da122d44a](https://linux-hardware.org/?probe=7da122d44a) | Jul 29, 2020 |
| Gigabyte  | Z170-HD3 DDR3-CF            | Desktop     | [f8c44dc8be](https://linux-hardware.org/?probe=f8c44dc8be) | Jul 29, 2020 |
| ASUSTek   | STRIX B250F GAMING          | Desktop     | [cb5d511453](https://linux-hardware.org/?probe=cb5d511453) | Jul 28, 2020 |
| HUAWEI    | MACH-WX9                    | Notebook    | [999f65d55e](https://linux-hardware.org/?probe=999f65d55e) | Jul 28, 2020 |
| ASUSTek   | P8H77-M PRO                 | Desktop     | [87d7bc3077](https://linux-hardware.org/?probe=87d7bc3077) | Jul 28, 2020 |
| Samsung   | 340XAA/350XAA/550XAA        | Notebook    | [6a0fabe139](https://linux-hardware.org/?probe=6a0fabe139) | Jul 28, 2020 |
| Intel     | NUC8BEB J72693-307          | Mini pc     | [ad54591d3a](https://linux-hardware.org/?probe=ad54591d3a) | Jul 27, 2020 |
| Samsung   | 300E5EV/300E4EV/270E5EV/... | Notebook    | [ccd785c473](https://linux-hardware.org/?probe=ccd785c473) | Jul 27, 2020 |
| MSI       | X370 GAMING PRO CARBON      | Desktop     | [f38e8a0201](https://linux-hardware.org/?probe=f38e8a0201) | Jul 26, 2020 |
| HP        | 82F2                        | Desktop     | [172d6aed2a](https://linux-hardware.org/?probe=172d6aed2a) | Jul 26, 2020 |
| Intel     | NUC8BEB J72693-307          | Mini pc     | [0479f5e75d](https://linux-hardware.org/?probe=0479f5e75d) | Jul 26, 2020 |
| Gigabyte  | B360 AORUS GAMING 3 WIFI... | Desktop     | [2e6c21ed23](https://linux-hardware.org/?probe=2e6c21ed23) | Jul 26, 2020 |
| Samsung   | 530U3C/530U4C/532U3C        | Notebook    | [4f80b590f5](https://linux-hardware.org/?probe=4f80b590f5) | Jul 25, 2020 |
| HP        | Pavilion 14                 | Notebook    | [3243fbe29b](https://linux-hardware.org/?probe=3243fbe29b) | Jul 25, 2020 |
| HP        | Pavilion dv6                | Notebook    | [24b46efa49](https://linux-hardware.org/?probe=24b46efa49) | Jul 25, 2020 |
| HP        | EliteBook 2560p             | Notebook    | [dd251c0a0c](https://linux-hardware.org/?probe=dd251c0a0c) | Jul 25, 2020 |
| Dell      | Latitude E6320              | Notebook    | [d9ac43486e](https://linux-hardware.org/?probe=d9ac43486e) | Jul 25, 2020 |
| HP        | 3397                        | Desktop     | [edd52c2428](https://linux-hardware.org/?probe=edd52c2428) | Jul 24, 2020 |
| HP        | 3397                        | Desktop     | [20b3d353d8](https://linux-hardware.org/?probe=20b3d353d8) | Jul 24, 2020 |
| Gigabyte  | H61M-S1                     | Desktop     | [3ce4143dee](https://linux-hardware.org/?probe=3ce4143dee) | Jul 24, 2020 |
| Dell      | G3 3579                     | Notebook    | [b129bccbcf](https://linux-hardware.org/?probe=b129bccbcf) | Jul 24, 2020 |
| Dell      | G7 7588                     | Notebook    | [cb6c4a378b](https://linux-hardware.org/?probe=cb6c4a378b) | Jul 24, 2020 |
| Dell      | Inspiron 5437               | Notebook    | [bae63d5905](https://linux-hardware.org/?probe=bae63d5905) | Jul 24, 2020 |
| Lenovo    | IdeaPad S145-15IWL 81S9     | Notebook    | [a4ff18fb01](https://linux-hardware.org/?probe=a4ff18fb01) | Jul 24, 2020 |
| Acer      | Aspire A315-41              | Notebook    | [689b63d743](https://linux-hardware.org/?probe=689b63d743) | Jul 24, 2020 |
| ASUSTek   | K53E                        | Notebook    | [965c0a5e03](https://linux-hardware.org/?probe=965c0a5e03) | Jul 20, 2020 |
| MSI       | GL62M 7RD                   | Notebook    | [ddfb055569](https://linux-hardware.org/?probe=ddfb055569) | Jul 18, 2020 |
| HP        | Spectre x360 Convertible... | Convertible | [12a4926d36](https://linux-hardware.org/?probe=12a4926d36) | Jul 17, 2020 |
| Gigabyte  | B360 AORUS GAMING 3 WIFI... | Desktop     | [534a204796](https://linux-hardware.org/?probe=534a204796) | Jul 17, 2020 |
| ASUSTek   | M51AC                       | Desktop     | [fcc0f73453](https://linux-hardware.org/?probe=fcc0f73453) | Jul 15, 2020 |
| ASUSTek   | M4A87TD/USB3                | Desktop     | [7d642bd7dc](https://linux-hardware.org/?probe=7d642bd7dc) | Jul 14, 2020 |
| ASUSTek   | M4A87TD/USB3                | Desktop     | [76752b2d00](https://linux-hardware.org/?probe=76752b2d00) | Jul 13, 2020 |
| ASUSTek   | M4A87TD/USB3                | Desktop     | [8639032305](https://linux-hardware.org/?probe=8639032305) | Jul 13, 2020 |
| MSI       | GP72 7RE                    | Notebook    | [66efd09dbc](https://linux-hardware.org/?probe=66efd09dbc) | Jul 12, 2020 |
| Lenovo    | MIIX 310-10ICR 80SG         | Tablet      | [c7cdebaa45](https://linux-hardware.org/?probe=c7cdebaa45) | Jul 09, 2020 |
| ASUSTek   | X510UAR                     | Notebook    | [a8f39d2061](https://linux-hardware.org/?probe=a8f39d2061) | Jul 08, 2020 |
| HP        | EliteBook 840 G6            | Notebook    | [1a175eee47](https://linux-hardware.org/?probe=1a175eee47) | Jul 07, 2020 |
| Dell      | Inspiron 3537               | Notebook    | [803b8c9adc](https://linux-hardware.org/?probe=803b8c9adc) | Jul 06, 2020 |
| Dell      | Inspiron 3537               | Notebook    | [38640e68c7](https://linux-hardware.org/?probe=38640e68c7) | Jul 06, 2020 |
| HP        | Pavilion Laptop 15-cw1xx... | Notebook    | [e2f2937842](https://linux-hardware.org/?probe=e2f2937842) | Jul 05, 2020 |
| Lenovo    | IdeaPad 320-15IKB 80XL      | Notebook    | [e6480fdb93](https://linux-hardware.org/?probe=e6480fdb93) | Jul 04, 2020 |
| Dell      | XPS L401X                   | Notebook    | [291b1c0a01](https://linux-hardware.org/?probe=291b1c0a01) | Jul 03, 2020 |
| HP        | Pavilion Laptop 15-cw1xx... | Notebook    | [c67e3d5b3d](https://linux-hardware.org/?probe=c67e3d5b3d) | Jul 02, 2020 |
| ASUSTek   | M51AC                       | Desktop     | [6af32ff946](https://linux-hardware.org/?probe=6af32ff946) | Jul 01, 2020 |
| ASUSTek   | B85M-E                      | Desktop     | [e46352dec8](https://linux-hardware.org/?probe=e46352dec8) | Jun 28, 2020 |
| Dell      | Latitude E6220              | Notebook    | [2177469041](https://linux-hardware.org/?probe=2177469041) | Jun 25, 2020 |
| Apple     | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [33d1532efd](https://linux-hardware.org/?probe=33d1532efd) | Jun 23, 2020 |
| Apple     | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [110bf098e8](https://linux-hardware.org/?probe=110bf098e8) | Jun 22, 2020 |
| Dell      | 09KPNV A00                  | Desktop     | [9f63cccd5c](https://linux-hardware.org/?probe=9f63cccd5c) | Jun 21, 2020 |
| HP        | Laptop 15-dw0xxx            | Notebook    | [a9c582ba02](https://linux-hardware.org/?probe=a9c582ba02) | Jun 19, 2020 |
| ASUSTek   | P8Z68-V PRO GEN3            | Desktop     | [311c0852f2](https://linux-hardware.org/?probe=311c0852f2) | Jun 18, 2020 |
| Acer      | Aspire R3-131T              | Notebook    | [b51cceda3f](https://linux-hardware.org/?probe=b51cceda3f) | Jun 17, 2020 |
| Acer      | Aspire R3-131T              | Notebook    | [52d48f4c11](https://linux-hardware.org/?probe=52d48f4c11) | Jun 17, 2020 |
| TUXEDO    | InfinityBook Pro 15 v4      | Notebook    | [7d351b71dc](https://linux-hardware.org/?probe=7d351b71dc) | Jun 17, 2020 |
| HP        | ENVY 17                     | Notebook    | [8ee27ae156](https://linux-hardware.org/?probe=8ee27ae156) | Jun 16, 2020 |
| Dell      | Inspiron 7590               | Notebook    | [1e4d9a97b8](https://linux-hardware.org/?probe=1e4d9a97b8) | Jun 15, 2020 |
| Sony      | VPCCW25FL                   | Notebook    | [2e9d3ed45b](https://linux-hardware.org/?probe=2e9d3ed45b) | Jun 14, 2020 |
| HP        | ENVY 17                     | Notebook    | [6717ca8025](https://linux-hardware.org/?probe=6717ca8025) | Jun 14, 2020 |
| Acer      | Aspire V3-572G              | Notebook    | [d780f9b6ef](https://linux-hardware.org/?probe=d780f9b6ef) | Jun 13, 2020 |
| ASUSTek   | X540LA                      | Notebook    | [99651c1c86](https://linux-hardware.org/?probe=99651c1c86) | Jun 12, 2020 |
| HP        | ENVY 17                     | Notebook    | [19571ad1c9](https://linux-hardware.org/?probe=19571ad1c9) | Jun 11, 2020 |
| HP        | ENVY 17                     | Notebook    | [16c895ce30](https://linux-hardware.org/?probe=16c895ce30) | Jun 07, 2020 |
| Lenovo    | ThinkPad X230 23257G6       | Notebook    | [95097be9d3](https://linux-hardware.org/?probe=95097be9d3) | Jun 02, 2020 |
| Acer      | Aspire ZC-105               | All in one  | [42b2dbab31](https://linux-hardware.org/?probe=42b2dbab31) | Jun 01, 2020 |
| Lenovo    | ThinkPad X230 23257G6       | Notebook    | [d4c8c1735b](https://linux-hardware.org/?probe=d4c8c1735b) | May 31, 2020 |
| HUAWEI    | MACH-WX9                    | Notebook    | [f3ca082840](https://linux-hardware.org/?probe=f3ca082840) | May 31, 2020 |
| Lenovo    | IdeaPad 5 15ARE05 81YQ      | Notebook    | [6ad038b762](https://linux-hardware.org/?probe=6ad038b762) | May 30, 2020 |
| ASUSTek   | VivoBook_ASUSLaptop X571... | Notebook    | [3552bfc82b](https://linux-hardware.org/?probe=3552bfc82b) | May 29, 2020 |
| HP        | ENVY 17                     | Notebook    | [0bb6be8c85](https://linux-hardware.org/?probe=0bb6be8c85) | May 27, 2020 |
| HP        | ENVY 17                     | Notebook    | [4f1caa50f6](https://linux-hardware.org/?probe=4f1caa50f6) | May 27, 2020 |
| Lenovo    | ThinkPad X260 20F5S2HF06    | Notebook    | [fb34ca6c06](https://linux-hardware.org/?probe=fb34ca6c06) | May 26, 2020 |
| ASUSTek   | ROG STRIX X570-E GAMING     | Desktop     | [49486e2abf](https://linux-hardware.org/?probe=49486e2abf) | May 24, 2020 |
| Lenovo    | ThinkPad T430 2349P74       | Notebook    | [50dbda3211](https://linux-hardware.org/?probe=50dbda3211) | May 21, 2020 |
| ASUSTek   | P8H77-M PRO                 | Desktop     | [e8b5bf55c7](https://linux-hardware.org/?probe=e8b5bf55c7) | May 20, 2020 |
| ASUSTek   | S400CA                      | Notebook    | [3e3bb3f13e](https://linux-hardware.org/?probe=3e3bb3f13e) | May 19, 2020 |
| ASUSTek   | X510UNR                     | Notebook    | [23cb30a022](https://linux-hardware.org/?probe=23cb30a022) | May 16, 2020 |
| ASUSTek   | X510UNR                     | Notebook    | [d28985973f](https://linux-hardware.org/?probe=d28985973f) | May 16, 2020 |
| Acer      | Aspire F5-573G              | Notebook    | [7eea93aa65](https://linux-hardware.org/?probe=7eea93aa65) | May 16, 2020 |
| Dell      | 0J32FG A06                  | Desktop     | [d5d2970bc5](https://linux-hardware.org/?probe=d5d2970bc5) | May 15, 2020 |
| Gigabyte  | Z68M-D2H                    | Desktop     | [70c167639c](https://linux-hardware.org/?probe=70c167639c) | May 15, 2020 |
| Dell      | Latitude 5400               | Notebook    | [cfdf75da7b](https://linux-hardware.org/?probe=cfdf75da7b) | May 14, 2020 |
| Lenovo    | G550 2958                   | Notebook    | [4e4bcc14f1](https://linux-hardware.org/?probe=4e4bcc14f1) | May 11, 2020 |
| Lenovo    | G550 2958                   | Notebook    | [e4d76f72dc](https://linux-hardware.org/?probe=e4d76f72dc) | May 11, 2020 |
| Lenovo    | G550 2958                   | Notebook    | [ea8d2d9296](https://linux-hardware.org/?probe=ea8d2d9296) | May 11, 2020 |
| Dell      | 0TNXNR A01                  | Desktop     | [c16ecd859c](https://linux-hardware.org/?probe=c16ecd859c) | May 11, 2020 |
| Lenovo    | 3704 SDK0R32862 WIN 3258... | Desktop     | [eb7d6f2ec3](https://linux-hardware.org/?probe=eb7d6f2ec3) | May 10, 2020 |
| Biostar   | G31-M7 TE                   | Desktop     | [e9d31442df](https://linux-hardware.org/?probe=e9d31442df) | May 09, 2020 |
| ASUSTek   | S551LN                      | Notebook    | [51bb777f10](https://linux-hardware.org/?probe=51bb777f10) | May 08, 2020 |
| ASUSTek   | S551LN                      | Notebook    | [b81e2e0679](https://linux-hardware.org/?probe=b81e2e0679) | May 08, 2020 |
| Quanta    | QL3 TBD                     | Notebook    | [680a32b94c](https://linux-hardware.org/?probe=680a32b94c) | May 08, 2020 |
| Gigabyte  | GB-BKi7A-7500               | Notebook    | [a4c4bc09fb](https://linux-hardware.org/?probe=a4c4bc09fb) | May 08, 2020 |
| HP        | EliteBook 840 G5            | Notebook    | [5c81f4ef61](https://linux-hardware.org/?probe=5c81f4ef61) | May 07, 2020 |
| ASUSTek   | G55VW                       | Notebook    | [9cb0c68aa1](https://linux-hardware.org/?probe=9cb0c68aa1) | May 07, 2020 |
| HP        | EliteBook 8560w             | Notebook    | [e2fca9899f](https://linux-hardware.org/?probe=e2fca9899f) | May 07, 2020 |
| Acer      | Aspire F5-573G              | Notebook    | [0b67b7c423](https://linux-hardware.org/?probe=0b67b7c423) | May 06, 2020 |
| Gigabyte  | Z68M-D2H                    | Desktop     | [6fc5f4e0be](https://linux-hardware.org/?probe=6fc5f4e0be) | May 06, 2020 |
| ASRock    | B450 Gaming-ITX/ac          | Desktop     | [2e108e8f82](https://linux-hardware.org/?probe=2e108e8f82) | May 06, 2020 |
| HP        | Spectre x360 Convertible... | Convertible | [181868c1fe](https://linux-hardware.org/?probe=181868c1fe) | May 05, 2020 |
| Gigabyte  | Z68M-D2H                    | Desktop     | [1778c8dba1](https://linux-hardware.org/?probe=1778c8dba1) | May 03, 2020 |
| HP        | Notebook                    | Notebook    | [d666fee133](https://linux-hardware.org/?probe=d666fee133) | May 02, 2020 |
| MSI       | MEG Z390 GODLIKE            | Desktop     | [f5c70a1643](https://linux-hardware.org/?probe=f5c70a1643) | Apr 30, 2020 |
| Lenovo    | ThinkPad W530 2447GW3       | Notebook    | [69f36d1be1](https://linux-hardware.org/?probe=69f36d1be1) | Apr 30, 2020 |
| HP        | Spectre x360 Convertible... | Convertible | [7db8dc0e44](https://linux-hardware.org/?probe=7db8dc0e44) | Apr 28, 2020 |
| ASUSTek   | TUF B450-PLUS GAMING        | Desktop     | [6982ff0a12](https://linux-hardware.org/?probe=6982ff0a12) | Apr 25, 2020 |
| Lenovo    | ThinkPad X230 2306CTO       | Notebook    | [80111dac4b](https://linux-hardware.org/?probe=80111dac4b) | Apr 24, 2020 |
| HUAWEI    | BOHK-WAX9X                  | Notebook    | [cba2c66659](https://linux-hardware.org/?probe=cba2c66659) | Apr 20, 2020 |
| Gigabyte  | Z68M-D2H                    | Desktop     | [3db29a7f67](https://linux-hardware.org/?probe=3db29a7f67) | Apr 12, 2020 |
| Lenovo    | ThinkPad T410 2537H21       | Notebook    | [0140b2344a](https://linux-hardware.org/?probe=0140b2344a) | Apr 08, 2020 |
| HP        | Spectre x360 Convertible... | Convertible | [c17da47049](https://linux-hardware.org/?probe=c17da47049) | Apr 03, 2020 |
| HP        | Spectre x360 Convertible... | Convertible | [18f447ca5d](https://linux-hardware.org/?probe=18f447ca5d) | Apr 03, 2020 |
| Dell      | 0J32FG A06                  | Desktop     | [efb8737ca2](https://linux-hardware.org/?probe=efb8737ca2) | Mar 20, 2020 |
| Lenovo    | ThinkPad P53 20QQS1JE00     | Notebook    | [6692834531](https://linux-hardware.org/?probe=6692834531) | Mar 18, 2020 |
| eMachines | EL1852G                     | Desktop     | [e90ac3f652](https://linux-hardware.org/?probe=e90ac3f652) | Feb 27, 2020 |
| Gigabyte  | Z68M-D2H                    | Desktop     | [6cfda70306](https://linux-hardware.org/?probe=6cfda70306) | Feb 15, 2020 |
| HP        | Compaq 8460p USAO           | Notebook    | [3eab448396](https://linux-hardware.org/?probe=3eab448396) | Dec 21, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.4.0-42-generic           | 24        | 10.81%  |
| 5.4.0-40-generic           | 13        | 5.86%   |
| 5.4.0-52-generic           | 10        | 4.5%    |
| 5.4.0-37-generic           | 10        | 4.5%    |
| 5.4.0-29-generic           | 10        | 4.5%    |
| 5.4.0-48-generic           | 9         | 4.05%   |
| 5.4.0-58-generic           | 8         | 3.6%    |
| 5.4.0-33-generic           | 6         | 2.7%    |
| 5.4.0-65-generic           | 5         | 2.25%   |
| 5.4.0-47-generic           | 5         | 2.25%   |
| 5.4.0-45-generic           | 5         | 2.25%   |
| 5.4.0-31-generic           | 5         | 2.25%   |
| 5.8.0-53-generic           | 4         | 1.8%    |
| 5.4.0-72-generic           | 4         | 1.8%    |
| 5.4.0-66-generic           | 4         | 1.8%    |
| 5.4.0-59-generic           | 4         | 1.8%    |
| 5.4.0-28-generic           | 4         | 1.8%    |
| 5.8.0-59-generic           | 3         | 1.35%   |
| 5.8.0-45-generic           | 3         | 1.35%   |
| 5.8.0-44-generic           | 3         | 1.35%   |
| 5.8.0-43-generic           | 3         | 1.35%   |
| 5.4.0-80-generic           | 3         | 1.35%   |
| 5.4.0-73-generic           | 3         | 1.35%   |
| 5.4.0-54-generic           | 3         | 1.35%   |
| 5.4.0-26-generic           | 3         | 1.35%   |
| 5.11.0-38-generic          | 3         | 1.35%   |
| 5.11.0-27-generic          | 3         | 1.35%   |
| 5.8.0-49-generic           | 2         | 0.9%    |
| 5.8.0-48-generic           | 2         | 0.9%    |
| 5.4.0-62-generic           | 2         | 0.9%    |
| 5.4.0-60-generic           | 2         | 0.9%    |
| 5.4.0-56-generic           | 2         | 0.9%    |
| 5.4.0-51-generic           | 2         | 0.9%    |
| 5.4.0-44-generic           | 2         | 0.9%    |
| 5.4.0-21-generic           | 2         | 0.9%    |
| 5.4.0-18-generic           | 2         | 0.9%    |
| 5.11.0-40-generic          | 2         | 0.9%    |
| 5.11.0-37-generic          | 2         | 0.9%    |
| 5.9.1-050901-generic       | 1         | 0.45%   |
| 5.9.0-050900rc6-lowlatency | 1         | 0.45%   |
| 5.8.6-rockchip64           | 1         | 0.45%   |
| 5.8.11-050811-generic      | 1         | 0.45%   |
| 5.8.0-63-generic           | 1         | 0.45%   |
| 5.8.0-59-lowlatency        | 1         | 0.45%   |
| 5.8.0-50-generic           | 1         | 0.45%   |
| 5.8.0-41-generic           | 1         | 0.45%   |
| 5.7.7-xanmod1              | 1         | 0.45%   |
| 5.6.7-050607-lowlatency    | 1         | 0.45%   |
| 5.6.7-050607-generic       | 1         | 0.45%   |
| 5.6.0-1048-oem             | 1         | 0.45%   |
| 5.6.0-1042-oem             | 1         | 0.45%   |
| 5.6.0-1034-oem             | 1         | 0.45%   |
| 5.5.8-050508-lowlatency    | 1         | 0.45%   |
| 5.5.0-2.1-liquorix-amd64   | 1         | 0.45%   |
| 5.4.0-91-generic           | 1         | 0.45%   |
| 5.4.0-89-generic           | 1         | 0.45%   |
| 5.4.0-77-generic           | 1         | 0.45%   |
| 5.4.0-74-generic           | 1         | 0.45%   |
| 5.4.0-70-generic           | 1         | 0.45%   |
| 5.4.0-67-generic           | 1         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 146       | 74.11%  |
| 5.8.0   | 24        | 12.18%  |
| 5.11.0  | 11        | 5.58%   |
| 5.6.0   | 3         | 1.52%   |
| 5.6.7   | 2         | 1.02%   |
| 5.3.0   | 2         | 1.02%   |
| 5.9.1   | 1         | 0.51%   |
| 5.9.0   | 1         | 0.51%   |
| 5.8.6   | 1         | 0.51%   |
| 5.8.11  | 1         | 0.51%   |
| 5.7.7   | 1         | 0.51%   |
| 5.5.8   | 1         | 0.51%   |
| 5.5.0   | 1         | 0.51%   |
| 5.12.0  | 1         | 0.51%   |
| 5.10.11 | 1         | 0.51%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 146       | 74.11%  |
| 5.8     | 26        | 13.2%   |
| 5.11    | 11        | 5.58%   |
| 5.6     | 5         | 2.54%   |
| 5.9     | 2         | 1.02%   |
| 5.5     | 2         | 1.02%   |
| 5.3     | 2         | 1.02%   |
| 5.7     | 1         | 0.51%   |
| 5.12    | 1         | 0.51%   |
| 5.10    | 1         | 0.51%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 194       | 99.49%  |
| aarch64 | 1         | 0.51%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Budgie | 189       | 96.92%  |
| GNOME  | 5         | 2.56%   |
| XFCE   | 1         | 0.51%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 188       | 96.41%  |
| Wayland | 6         | 3.08%   |
| Tty     | 1         | 0.51%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 101       | 51.27%  |
| TDM     | 52        | 26.4%   |
| GDM     | 22        | 11.17%  |
| LightDM | 21        | 10.66%  |
| GDM3    | 1         | 0.51%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 65        | 33.16%  |
| de_DE   | 22        | 11.22%  |
| pt_BR   | 21        | 10.71%  |
| en_GB   | 13        | 6.63%   |
| fr_FR   | 10        | 5.1%    |
| en_CA   | 9         | 4.59%   |
| it_IT   | 5         | 2.55%   |
| en_AU   | 5         | 2.55%   |
| ru_RU   | 4         | 2.04%   |
| es_ES   | 4         | 2.04%   |
| en_IN   | 4         | 2.04%   |
| zh_TW   | 2         | 1.02%   |
| pt_PT   | 2         | 1.02%   |
| fi_FI   | 2         | 1.02%   |
| es_MX   | 2         | 1.02%   |
| es_CO   | 2         | 1.02%   |
| es_CL   | 2         | 1.02%   |
| es_AR   | 2         | 1.02%   |
| de_CH   | 2         | 1.02%   |
| C       | 2         | 1.02%   |
| zh_CN   | 1         | 0.51%   |
| uk_UA   | 1         | 0.51%   |
| sv_SE   | 1         | 0.51%   |
| pl_PL   | 1         | 0.51%   |
| nb_NO   | 1         | 0.51%   |
| id_ID   | 1         | 0.51%   |
| hu_HU   | 1         | 0.51%   |
| fr_CH   | 1         | 0.51%   |
| es_US   | 1         | 0.51%   |
| es_SV   | 1         | 0.51%   |
| es_GT   | 1         | 0.51%   |
| en_SG   | 1         | 0.51%   |
| en_IL   | 1         | 0.51%   |
| de_AT   | 1         | 0.51%   |
| bg_BG   | 1         | 0.51%   |
| Unknown | 1         | 0.51%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 134       | 65.69%  |
| BIOS | 70        | 34.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 180       | 92.31%  |
| Zfs     | 8         | 4.1%    |
| Btrfs   | 3         | 1.54%   |
| Overlay | 2         | 1.03%   |
| Xfs     | 1         | 0.51%   |
| Jfs     | 1         | 0.51%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 106       | 53.81%  |
| GPT     | 66        | 33.5%   |
| MBR     | 25        | 12.69%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 178       | 89.9%   |
| Yes       | 20        | 10.1%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 133       | 67.51%  |
| Yes       | 64        | 32.49%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 36        | 18.46%  |
| ASUSTek Computer    | 33        | 16.92%  |
| Dell                | 25        | 12.82%  |
| Lenovo              | 19        | 9.74%   |
| TUXEDO              | 15        | 7.69%   |
| MSI                 | 13        | 6.67%   |
| Gigabyte Technology | 13        | 6.67%   |
| Acer                | 12        | 6.15%   |
| Apple               | 8         | 4.1%    |
| Samsung Electronics | 4         | 2.05%   |
| Sony                | 2         | 1.03%   |
| HUAWEI              | 2         | 1.03%   |
| Fujitsu             | 2         | 1.03%   |
| ASRock              | 2         | 1.03%   |
| Toshiba             | 1         | 0.51%   |
| Standard            | 1         | 0.51%   |
| Radxa               | 1         | 0.51%   |
| Quanta              | 1         | 0.51%   |
| PCSMART             | 1         | 0.51%   |
| Intel               | 1         | 0.51%   |
| eMachines           | 1         | 0.51%   |
| Biostar             | 1         | 0.51%   |
| Unknown             | 1         | 0.51%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Unknown                                               | 3         | 1.54%   |
| MSI MS-7C84                                           | 2         | 1.03%   |
| HP ZBook Studio G3                                    | 2         | 1.03%   |
| HP Pavilion g6                                        | 2         | 1.03%   |
| HP Notebook                                           | 2         | 1.03%   |
| Dell Latitude 5400                                    | 2         | 1.03%   |
| Acer TravelMate P446-M                                | 2         | 1.03%   |
| TUXEDO TUXEDO_Book_XA1510                             | 1         | 0.51%   |
| TUXEDO Polaris 17 AMD Gen1                            | 1         | 0.51%   |
| TUXEDO Polaris 15 AMD Gen1                            | 1         | 0.51%   |
| TUXEDO P95_HR                                         | 1         | 0.51%   |
| TUXEDO P95_HP                                         | 1         | 0.51%   |
| TUXEDO P7xxTM1                                        | 1         | 0.51%   |
| TUXEDO InfinityBook S 15 Gen6                         | 1         | 0.51%   |
| TUXEDO InfinityBook S 14 Gen6                         | 1         | 0.51%   |
| TUXEDO InfinityBook Pro 15 v4                         | 1         | 0.51%   |
| TUXEDO InfinityBook Pro 14 Gen6                       | 1         | 0.51%   |
| TUXEDO Book XP1511                                    | 1         | 0.51%   |
| TUXEDO Book XP15 / XP17 Gen12                         | 1         | 0.51%   |
| TUXEDO Aura 15 Gen1                                   | 1         | 0.51%   |
| Toshiba Satellite P300                                | 1         | 0.51%   |
| Standard MT40II                                       | 1         | 0.51%   |
| Sony VPCCW25FL                                        | 1         | 0.51%   |
| Sony SVS13A25PBS                                      | 1         | 0.51%   |
| Samsung 905S3G/906S3G/915S3G/9305SG                   | 1         | 0.51%   |
| Samsung 530U3C/530U4C/532U3C                          | 1         | 0.51%   |
| Samsung 340XAA/350XAA/550XAA                          | 1         | 0.51%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.51%   |
| Radxa ROCK Pi 4A                                      | 1         | 0.51%   |
| Quanta R460-L.BG22P1                                  | 1         | 0.51%   |
| PCSMART 6.0                                           | 1         | 0.51%   |
| MSI Prestige 15 A10SC                                 | 1         | 0.51%   |
| MSI MS-7B38                                           | 1         | 0.51%   |
| MSI MS-7B10                                           | 1         | 0.51%   |
| MSI MS-7A32                                           | 1         | 0.51%   |
| MSI MS-7917                                           | 1         | 0.51%   |
| MSI Modern 14 A10RB                                   | 1         | 0.51%   |
| MSI GP73 Leopard 8RE                                  | 1         | 0.51%   |
| MSI GP72 7RE                                          | 1         | 0.51%   |
| MSI GL62M 7RD                                         | 1         | 0.51%   |
| MSI GE70 2PC\2PE                                      | 1         | 0.51%   |
| MSI CX62 6QL                                          | 1         | 0.51%   |
| Lenovo ThinkPad X260 20F5S2HF06                       | 1         | 0.51%   |
| Lenovo ThinkPad X230 23257G6                          | 1         | 0.51%   |
| Lenovo ThinkPad X230 2306CTO                          | 1         | 0.51%   |
| Lenovo ThinkPad W530 2447GW3                          | 1         | 0.51%   |
| Lenovo ThinkPad T430s 23539WU                         | 1         | 0.51%   |
| Lenovo ThinkPad T430 2349P74                          | 1         | 0.51%   |
| Lenovo ThinkPad T410 2537H21                          | 1         | 0.51%   |
| Lenovo ThinkPad P53 20QQS1JE00                        | 1         | 0.51%   |
| Lenovo ThinkPad P43s 20RHS00100                       | 1         | 0.51%   |
| Lenovo ThinkPad P43s 20RH0013US                       | 1         | 0.51%   |
| Lenovo ThinkPad P1 20MES01400                         | 1         | 0.51%   |
| Lenovo ThinkPad E490 20N8S07A00                       | 1         | 0.51%   |
| Lenovo MIIX 310-10ICR 80SG                            | 1         | 0.51%   |
| Lenovo Legion T530-28ICB 90L300BQMW                   | 1         | 0.51%   |
| Lenovo IdeaPad S145-15IWL 81S9                        | 1         | 0.51%   |
| Lenovo IdeaPad 5 15ARE05 81YQ                         | 1         | 0.51%   |
| Lenovo IdeaPad 320-15IKB 80XL                         | 1         | 0.51%   |
| Lenovo G550 2958                                      | 1         | 0.51%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 12        | 6.15%   |
| Acer Aspire          | 10        | 5.13%   |
| Dell Latitude        | 9         | 4.62%   |
| HP Pavilion          | 6         | 3.08%   |
| Dell Inspiron        | 6         | 3.08%   |
| HP Spectre           | 5         | 2.56%   |
| HP EliteBook         | 5         | 2.56%   |
| TUXEDO InfinityBook  | 4         | 2.05%   |
| HP Compaq            | 4         | 2.05%   |
| Lenovo IdeaPad       | 3         | 1.54%   |
| HP Laptop            | 3         | 1.54%   |
| Dell XPS             | 3         | 1.54%   |
| Dell OptiPlex        | 3         | 1.54%   |
| ASUS PRIME           | 3         | 1.54%   |
| Unknown              | 3         | 1.54%   |
| TUXEDO Polaris       | 2         | 1.03%   |
| TUXEDO P95           | 2         | 1.03%   |
| TUXEDO Book          | 2         | 1.03%   |
| MSI MS-7C84          | 2         | 1.03%   |
| HP ZBook             | 2         | 1.03%   |
| HP ProBook           | 2         | 1.03%   |
| HP Notebook          | 2         | 1.03%   |
| HP ENVY              | 2         | 1.03%   |
| Gigabyte B360        | 2         | 1.03%   |
| Dell Precision       | 2         | 1.03%   |
| ASUS TUF             | 2         | 1.03%   |
| ASUS ROG             | 2         | 1.03%   |
| Acer TravelMate      | 2         | 1.03%   |
| TUXEDO TUXEDO        | 1         | 0.51%   |
| TUXEDO P7xxTM1       | 1         | 0.51%   |
| TUXEDO Aura          | 1         | 0.51%   |
| Toshiba Satellite    | 1         | 0.51%   |
| Standard MT40II      | 1         | 0.51%   |
| Sony VPCCW25FL       | 1         | 0.51%   |
| Sony SVS13A25PBS     | 1         | 0.51%   |
| Samsung 905S3G       | 1         | 0.51%   |
| Samsung 530U3C       | 1         | 0.51%   |
| Samsung 340XAA       | 1         | 0.51%   |
| Samsung 300E5EV      | 1         | 0.51%   |
| Radxa ROCK           | 1         | 0.51%   |
| Quanta R460-L.BG22P1 | 1         | 0.51%   |
| PCSMART 6.0          | 1         | 0.51%   |
| MSI Prestige         | 1         | 0.51%   |
| MSI MS-7B38          | 1         | 0.51%   |
| MSI MS-7B10          | 1         | 0.51%   |
| MSI MS-7A32          | 1         | 0.51%   |
| MSI MS-7917          | 1         | 0.51%   |
| MSI Modern           | 1         | 0.51%   |
| MSI GP73             | 1         | 0.51%   |
| MSI GP72             | 1         | 0.51%   |
| MSI GL62M            | 1         | 0.51%   |
| MSI GE70             | 1         | 0.51%   |
| MSI CX62             | 1         | 0.51%   |
| Lenovo MIIX          | 1         | 0.51%   |
| Lenovo Legion        | 1         | 0.51%   |
| Lenovo G550          | 1         | 0.51%   |
| Lenovo 20SL          | 1         | 0.51%   |
| Intel NUC8i3BEH      | 1         | 0.51%   |
| HUAWEI MACH-WX9      | 1         | 0.51%   |
| HUAWEI BOHK-WAX9X    | 1         | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 42        | 21.54%  |
| 2020    | 35        | 17.95%  |
| 2018    | 29        | 14.87%  |
| 2013    | 18        | 9.23%   |
| 2014    | 9         | 4.62%   |
| 2012    | 9         | 4.62%   |
| 2017    | 8         | 4.1%    |
| 2015    | 8         | 4.1%    |
| 2016    | 7         | 3.59%   |
| 2011    | 7         | 3.59%   |
| 2010    | 7         | 3.59%   |
| 2021    | 6         | 3.08%   |
| 2009    | 4         | 2.05%   |
| 2008    | 4         | 2.05%   |
| 2007    | 1         | 0.51%   |
| Unknown | 1         | 0.51%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 124       | 63.59%  |
| Desktop        | 55        | 28.21%  |
| Convertible    | 6         | 3.08%   |
| All in one     | 5         | 2.56%   |
| Tablet         | 2         | 1.03%   |
| Mini pc        | 2         | 1.03%   |
| System on chip | 1         | 0.51%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 175       | 89.74%  |
| Enabled  | 20        | 10.26%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 195       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 59        | 29.65%  |
| 4.01-8.0    | 43        | 21.61%  |
| 8.01-16.0   | 37        | 18.59%  |
| 3.01-4.0    | 28        | 14.07%  |
| 32.01-64.0  | 20        | 10.05%  |
| 64.01-256.0 | 7         | 3.52%   |
| 2.01-3.0    | 2         | 1.01%   |
| 24.01-32.0  | 1         | 0.5%    |
| 1.01-2.0    | 1         | 0.5%    |
| 0.51-1.0    | 1         | 0.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 66        | 30.84%  |
| 1.01-2.0   | 47        | 21.96%  |
| 4.01-8.0   | 46        | 21.5%   |
| 3.01-4.0   | 38        | 17.76%  |
| 8.01-16.0  | 15        | 7.01%   |
| 32.01-64.0 | 1         | 0.47%   |
| 0.01-0.5   | 1         | 0.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 114       | 57.87%  |
| 2      | 55        | 27.92%  |
| 3      | 13        | 6.6%    |
| 5      | 7         | 3.55%   |
| 4      | 6         | 3.05%   |
| 8      | 1         | 0.51%   |
| 6      | 1         | 0.51%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 126       | 64.29%  |
| Yes       | 70        | 35.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 175       | 89.74%  |
| No        | 20        | 10.26%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 167       | 85.64%  |
| No        | 28        | 14.36%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 138       | 70.41%  |
| No        | 58        | 29.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 30        | 15.38%  |
| Germany            | 26        | 13.33%  |
| Brazil             | 22        | 11.28%  |
| France             | 10        | 5.13%   |
| Italy              | 8         | 4.1%    |
| UK                 | 7         | 3.59%   |
| Canada             | 7         | 3.59%   |
| Russia             | 6         | 3.08%   |
| Spain              | 5         | 2.56%   |
| Australia          | 5         | 2.56%   |
| Switzerland        | 4         | 2.05%   |
| Poland             | 4         | 2.05%   |
| India              | 4         | 2.05%   |
| Austria            | 4         | 2.05%   |
| Ukraine            | 3         | 1.54%   |
| Mexico             | 3         | 1.54%   |
| Japan              | 3         | 1.54%   |
| Iran               | 3         | 1.54%   |
| Finland            | 3         | 1.54%   |
| Turkey             | 2         | 1.03%   |
| Sweden             | 2         | 1.03%   |
| South Africa       | 2         | 1.03%   |
| Portugal           | 2         | 1.03%   |
| Norway             | 2         | 1.03%   |
| Netherlands        | 2         | 1.03%   |
| Indonesia          | 2         | 1.03%   |
| Hungary            | 2         | 1.03%   |
| Colombia           | 2         | 1.03%   |
| Chile              | 2         | 1.03%   |
| Argentina          | 2         | 1.03%   |
| Taiwan             | 1         | 0.51%   |
| Slovenia           | 1         | 0.51%   |
| Singapore          | 1         | 0.51%   |
| Malaysia           | 1         | 0.51%   |
| Kenya              | 1         | 0.51%   |
| Israel             | 1         | 0.51%   |
| Hong Kong          | 1         | 0.51%   |
| Honduras           | 1         | 0.51%   |
| Guatemala          | 1         | 0.51%   |
| El Salvador        | 1         | 0.51%   |
| Ecuador            | 1         | 0.51%   |
| Dominican Republic | 1         | 0.51%   |
| Croatia            | 1         | 0.51%   |
| Bulgaria           | 1         | 0.51%   |
| Bolivia            | 1         | 0.51%   |
| Belgium            | 1         | 0.51%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Paris                   | 4         | 1.99%   |
| Tehran                  | 3         | 1.49%   |
| São Paulo              | 3         | 1.49%   |
| Stuttgart               | 3         | 1.49%   |
| Wilchingen, Osterfingen | 2         | 1%      |
| Vienna                  | 2         | 1%      |
| Sydney                  | 2         | 1%      |
| Moscow                  | 2         | 1%      |
| Montreal                | 2         | 1%      |
| Miami                   | 2         | 1%      |
| Maringá                | 2         | 1%      |
| Los Angeles             | 2         | 1%      |
| Kyiv                    | 2         | 1%      |
| Hamburg                 | 2         | 1%      |
| Frankfurt am Main       | 2         | 1%      |
| Dresden                 | 2         | 1%      |
| Dallas                  | 2         | 1%      |
| Brasília               | 2         | 1%      |
| Belo Horizonte          | 2         | 1%      |
| Zheleznodorozhnyy       | 1         | 0.5%    |
| Zapopan                 | 1         | 0.5%    |
| Zagreb                  | 1         | 0.5%    |
| Zabrze                  | 1         | 0.5%    |
| Yuma                    | 1         | 0.5%    |
| Woking                  | 1         | 0.5%    |
| West Lafayette          | 1         | 0.5%    |
| Waterloo                | 1         | 0.5%    |
| Warsaw                  | 1         | 0.5%    |
| Vicente Lopez           | 1         | 0.5%    |
| Versailles              | 1         | 0.5%    |
| Vantaa                  | 1         | 0.5%    |
| Uman                    | 1         | 0.5%    |
| Tuttlingen              | 1         | 0.5%    |
| Tuscola                 | 1         | 0.5%    |
| Turku                   | 1         | 0.5%    |
| Totana                  | 1         | 0.5%    |
| Topeka                  | 1         | 0.5%    |
| Tokyo                   | 1         | 0.5%    |
| Tijuana                 | 1         | 0.5%    |
| Tiel                    | 1         | 0.5%    |
| Ternopil                | 1         | 0.5%    |
| Teresina                | 1         | 0.5%    |
| Tangerang               | 1         | 0.5%    |
| Talcahuano              | 1         | 0.5%    |
| São Luís              | 1         | 0.5%    |
| São José dos Campos   | 1         | 0.5%    |
| Szentendre              | 1         | 0.5%    |
| Stara Zagora            | 1         | 0.5%    |
| St Petersburg           | 1         | 0.5%    |
| Spilimbergo             | 1         | 0.5%    |
| Smithville              | 1         | 0.5%    |
| Skien                   | 1         | 0.5%    |
| Singapore               | 1         | 0.5%    |
| Sens                    | 1         | 0.5%    |
| Santo Domingo Este      | 1         | 0.5%    |
| Santo André            | 1         | 0.5%    |
| Santarém               | 1         | 0.5%    |
| Santa Tecla             | 1         | 0.5%    |
| Santa Rosa              | 1         | 0.5%    |
| San Pedro Sula          | 1         | 0.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives  | Percent |
|---------------------------|-----------|---------|---------|
| Samsung Electronics       | 56        | 72      | 19.51%  |
| WDC                       | 38        | 55      | 13.24%  |
| Seagate                   | 37        | 50      | 12.89%  |
| Toshiba                   | 26        | 28      | 9.06%   |
| SanDisk                   | 16        | 20      | 5.57%   |
| Kingston                  | 14        | 19      | 4.88%   |
| Unknown                   | 11        | 14      | 3.83%   |
| Crucial                   | 10        | 11      | 3.48%   |
| Intel                     | 9         | 19      | 3.14%   |
| HGST                      | 9         | 13      | 3.14%   |
| Hitachi                   | 8         | 11      | 2.79%   |
| Phison                    | 6         | 9       | 2.09%   |
| A-DATA Technology         | 6         | 7       | 2.09%   |
| SK Hynix                  | 5         | 5       | 1.74%   |
| PNY                       | 4         | 5       | 1.39%   |
| Micron Technology         | 4         | 6       | 1.39%   |
| China                     | 3         | 3       | 1.05%   |
| Micron/Crucial Technology | 2         | 2       | 0.7%    |
| Apple                     | 2         | 3       | 0.7%    |
| XrayDisk                  | 1         | 1       | 0.35%   |
| Vaseky                    | 1         | 1       | 0.35%   |
| USB30                     | 1         | 1       | 0.35%   |
| Transcend                 | 1         | 1       | 0.35%   |
| Silicon Motion            | 1         | 1       | 0.35%   |
| PLEXTOR                   | 1         | 1       | 0.35%   |
| OCZ                       | 1         | 1       | 0.35%   |
| Netac                     | 1         | 1       | 0.35%   |
| MAXTOR                    | 1         | 4       | 0.35%   |
| LITEON                    | 1         | 1       | 0.35%   |
| KingSpec                  | 1         | 1       | 0.35%   |
| KingDian                  | 1         | 1       | 0.35%   |
| KimMiDi                   | 1         | 1       | 0.35%   |
| JMicron                   | 1         | 1       | 0.35%   |
| HS-SSD-C100               | 1         | 1       | 0.35%   |
| Hewlett-Packard           | 1         | Unknown | 0.35%   |
| GALAX TA                  | 1         | 1       | 0.35%   |
| Corsair                   | 1         | 1       | 0.35%   |
| Axiom                     | 1         | 1       | 0.35%   |
| Apacer                    | 1         | 1       | 0.35%   |
| AMD                       | 1         | 8       | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 500GB           | 5         | 1.56%   |
| Toshiba MQ01ABD100 1TB                 | 4         | 1.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 4         | 1.25%   |
| Samsung SSD 860 EVO 500GB              | 4         | 1.25%   |
| Samsung NVMe SSD Drive 512GB           | 4         | 1.25%   |
| Unknown MMC Card  64GB                 | 3         | 0.93%   |
| Unknown MMC Card  32GB                 | 3         | 0.93%   |
| Seagate ST9500325AS 500GB              | 3         | 0.93%   |
| Seagate ST500DM002-1BD142 500GB        | 3         | 0.93%   |
| Seagate ST1000LM035-1RK172 1TB         | 3         | 0.93%   |
| SanDisk SDSSDA240G 240GB               | 3         | 0.93%   |
| SanDisk SDSSDA120G 120GB               | 3         | 0.93%   |
| Samsung SSD 970 EVO 500GB              | 3         | 0.93%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB | 3         | 0.93%   |
| Samsung NVMe SSD Drive 1TB             | 3         | 0.93%   |
| Kingston SA400S37240G 240GB SSD        | 3         | 0.93%   |
| Intel NVMe SSD Drive 512GB             | 3         | 0.93%   |
| WDC WD5000AAKX-001CA0 500GB            | 2         | 0.62%   |
| WDC WD5000AAKS-00UU3A0 500GB           | 2         | 0.62%   |
| Toshiba MQ01ABF050 500GB               | 2         | 0.62%   |
| SK Hynix NVMe SSD Drive 256GB          | 2         | 0.62%   |
| Seagate ST500LT012-1DG142 500GB        | 2         | 0.62%   |
| Seagate ST4000DM000-1F2168 4TB         | 2         | 0.62%   |
| Seagate ST1000LX015-1U7172 1TB         | 2         | 0.62%   |
| Seagate ST1000DM010-2EP102 1TB         | 2         | 0.62%   |
| Seagate ST1000DM003-1CH162 1TB         | 2         | 0.62%   |
| Seagate BUP Slim BK 1TB                | 2         | 0.62%   |
| SanDisk SSD PLUS 120GB                 | 2         | 0.62%   |
| Sandisk NVMe SSD Drive 512GB           | 2         | 0.62%   |
| Samsung SSD 980 PRO 1TB                | 2         | 0.62%   |
| Samsung SSD 970 EVO Plus 500GB         | 2         | 0.62%   |
| Samsung SSD 970 EVO Plus 1TB           | 2         | 0.62%   |
| Samsung SSD 860 QVO 1TB                | 2         | 0.62%   |
| Samsung SSD 860 EVO M.2 250GB          | 2         | 0.62%   |
| Samsung SSD 750 EVO 250GB              | 2         | 0.62%   |
| Phison Sabrent Rocket 4.0 1TB          | 2         | 0.62%   |
| Phison NVMe SSD Drive 240GB            | 2         | 0.62%   |
| Micron/Crucial NVMe SSD Drive 1TB      | 2         | 0.62%   |
| Kingston SV300S37A60G 64GB SSD         | 2         | 0.62%   |
| Kingston SA400S37480G 480GB SSD        | 2         | 0.62%   |
| Intel NVMe SSD Drive 32GB              | 2         | 0.62%   |
| Hitachi HTS545050A7E380 500GB          | 2         | 0.62%   |
| HGST HTS725050A7E630 500GB             | 2         | 0.62%   |
| HGST HTS541010A9E680 1TB               | 2         | 0.62%   |
| Crucial CT250MX500SSD1 250GB           | 2         | 0.62%   |
| XrayDisk 256GB                         | 1         | 0.31%   |
| WDC WDS500G2B0B-00YS70 500GB SSD       | 1         | 0.31%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 1         | 0.31%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD       | 1         | 0.31%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 1         | 0.31%   |
| WDC WDS200T2B0A 2TB SSD                | 1         | 0.31%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD       | 1         | 0.31%   |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 1         | 0.31%   |
| WDC WDS100T2B0A 1TB SSD                | 1         | 0.31%   |
| WDC WD80EFAX-68LHPN0 8TB               | 1         | 0.31%   |
| WDC WD7502AAEX-00Y9A0 752GB            | 1         | 0.31%   |
| WDC WD7501AALS-00J7B1 752GB            | 1         | 0.31%   |
| WDC WD7500BPVT-24HXZT3 752GB           | 1         | 0.31%   |
| WDC WD6401AALS-00L3B2 640GB            | 1         | 0.31%   |
| WDC WD6000HLHX-01JJPV0 600GB           | 1         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 36        | 49     | 33.96%  |
| WDC                 | 29        | 44     | 27.36%  |
| Toshiba             | 20        | 22     | 18.87%  |
| HGST                | 9         | 13     | 8.49%   |
| Hitachi             | 8         | 11     | 7.55%   |
| Unknown             | 1         | 1      | 0.94%   |
| Samsung Electronics | 1         | 1      | 0.94%   |
| MAXTOR              | 1         | 4      | 0.94%   |
| Apple               | 1         | 1      | 0.94%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 27        | 34     | 27.55%  |
| Kingston            | 13        | 18     | 13.27%  |
| SanDisk             | 12        | 15     | 12.24%  |
| WDC                 | 8         | 9      | 8.16%   |
| Crucial             | 8         | 9      | 8.16%   |
| A-DATA Technology   | 5         | 6      | 5.1%    |
| PNY                 | 3         | 4      | 3.06%   |
| China               | 3         | 3      | 3.06%   |
| Micron Technology   | 2         | 4      | 2.04%   |
| Intel               | 2         | 2      | 2.04%   |
| Vaseky              | 1         | 1      | 1.02%   |
| USB30               | 1         | 1      | 1.02%   |
| Transcend           | 1         | 1      | 1.02%   |
| Toshiba             | 1         | 1      | 1.02%   |
| SK Hynix            | 1         | 1      | 1.02%   |
| PLEXTOR             | 1         | 1      | 1.02%   |
| Netac               | 1         | 1      | 1.02%   |
| LITEON              | 1         | 1      | 1.02%   |
| KingSpec            | 1         | 1      | 1.02%   |
| KingDian            | 1         | 1      | 1.02%   |
| JMicron             | 1         | 1      | 1.02%   |
| Axiom               | 1         | 1      | 1.02%   |
| Apple               | 1         | 1      | 1.02%   |
| Apacer              | 1         | 1      | 1.02%   |
| AMD                 | 1         | 8      | 1.02%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 92        | 146    | 35.38%  |
| SSD     | 85        | 126    | 32.69%  |
| NVMe    | 68        | 93     | 26.15%  |
| MMC     | 8         | 10     | 3.08%   |
| Unknown | 7         | 7      | 2.69%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 141       | 268    | 62.11%  |
| NVMe | 68        | 93     | 29.96%  |
| SAS  | 10        | 11     | 4.41%   |
| MMC  | 8         | 10     | 3.52%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 103       | 163    | 57.54%  |
| 0.51-1.0   | 57        | 81     | 31.84%  |
| 1.01-2.0   | 11        | 15     | 6.15%   |
| 3.01-4.0   | 5         | 9      | 2.79%   |
| 4.01-10.0  | 3         | 4      | 1.68%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 57        | 28.08%  |
| 251-500        | 56        | 27.59%  |
| 501-1000       | 34        | 16.75%  |
| 1001-2000      | 15        | 7.39%   |
| 21-50          | 10        | 4.93%   |
| 51-100         | 10        | 4.93%   |
| More than 3000 | 8         | 3.94%   |
| Unknown        | 5         | 2.46%   |
| 2001-3000      | 4         | 1.97%   |
| 1-20           | 4         | 1.97%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 56        | 27.45%  |
| 101-250        | 42        | 20.59%  |
| 21-50          | 39        | 19.12%  |
| 51-100         | 25        | 12.25%  |
| 251-500        | 21        | 10.29%  |
| 1001-2000      | 7         | 3.43%   |
| 501-1000       | 7         | 3.43%   |
| Unknown        | 5         | 2.45%   |
| More than 3000 | 1         | 0.49%   |
| 2001-3000      | 1         | 0.49%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB              | 2         | 2      | 8.33%   |
| Seagate ST9500325AS 500GB           | 2         | 2      | 8.33%   |
| Seagate ST500DM002-1BD142 500GB     | 2         | 2      | 8.33%   |
| WDC WD6000HLHX-01JJPV0 600GB        | 1         | 1      | 4.17%   |
| WDC WD5000AVCS-632DY1 500GB         | 1         | 1      | 4.17%   |
| WDC WD5000AAKX-001CA0 500GB         | 1         | 1      | 4.17%   |
| WDC WD4003FZEX-00Z4SA0 4TB          | 1         | 1      | 4.17%   |
| WDC WD2500AAJS-60M0A0 250GB         | 1         | 1      | 4.17%   |
| WDC WD20EFRX-68EUZN0 2TB            | 1         | 2      | 4.17%   |
| Toshiba MQ01ABF050 500GB            | 1         | 1      | 4.17%   |
| Toshiba MK2561GSYN 250GB            | 1         | 1      | 4.17%   |
| Seagate ST9750420AS 752GB           | 1         | 1      | 4.17%   |
| Seagate ST5000DM000-1FK178 5TB      | 1         | 1      | 4.17%   |
| Seagate ST3320620AS 320GB           | 1         | 1      | 4.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1      | 4.17%   |
| PNY SSD2SC120G3LC709B121-460I 120GB | 1         | 1      | 4.17%   |
| MAXTOR 6B200M0 208GB                | 1         | 2      | 4.17%   |
| Hitachi HTS545025B9SA02 250GB       | 1         | 1      | 4.17%   |
| Hitachi HDS721032CLA362 320GB       | 1         | 1      | 4.17%   |
| HGST HTS725032A7E630 320GB          | 1         | 2      | 4.17%   |
| Crucial CT500P1SSD8 500GB           | 1         | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 8      | 33.33%  |
| WDC     | 6         | 7      | 25%     |
| Toshiba | 4         | 4      | 16.67%  |
| Hitachi | 2         | 2      | 8.33%   |
| PNY     | 1         | 1      | 4.17%   |
| MAXTOR  | 1         | 2      | 4.17%   |
| HGST    | 1         | 2      | 4.17%   |
| Crucial | 1         | 1      | 4.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 8      | 36.36%  |
| WDC     | 6         | 7      | 27.27%  |
| Toshiba | 4         | 4      | 18.18%  |
| Hitachi | 2         | 2      | 9.09%   |
| MAXTOR  | 1         | 2      | 4.55%   |
| HGST    | 1         | 2      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 25     | 90%     |
| NVMe | 1         | 1      | 5%      |
| SSD  | 1         | 1      | 5%      |

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
| Detected | 113       | 220    | 52.31%  |
| Works    | 83        | 135    | 38.43%  |
| Malfunc  | 20        | 27     | 9.26%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 144       | 57.83%  |
| Samsung Electronics           | 33        | 13.25%  |
| AMD                           | 25        | 10.04%  |
| Phison Electronics            | 7         | 2.81%   |
| Sandisk                       | 6         | 2.41%   |
| Toshiba America Info Systems  | 5         | 2.01%   |
| Marvell Technology Group      | 5         | 2.01%   |
| SK Hynix                      | 4         | 1.61%   |
| Micron/Crucial Technology     | 4         | 1.61%   |
| JMicron Technology            | 4         | 1.61%   |
| Micron Technology             | 2         | 0.8%    |
| Silicon Motion                | 1         | 0.4%    |
| Silicon Image                 | 1         | 0.4%    |
| Realtek Semiconductor         | 1         | 0.4%    |
| OCZ Technology Group          | 1         | 0.4%    |
| Nvidia                        | 1         | 0.4%    |
| Kingston Technology Company   | 1         | 0.4%    |
| Integrated Technology Express | 1         | 0.4%    |
| ASMedia Technology            | 1         | 0.4%    |
| ADATA Technology              | 1         | 0.4%    |
| Adaptec                       | 1         | 0.4%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 25        | 8.87%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 21        | 7.45%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 15        | 5.32%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 14        | 4.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 12        | 4.26%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 9         | 3.19%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8         | 2.84%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 7         | 2.48%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6         | 2.13%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 6         | 2.13%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6         | 2.13%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6         | 2.13%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 4         | 1.42%   |
| Phison E12 NVMe Controller                                                              | 4         | 1.42%   |
| Intel SSD 660P Series                                                                   | 4         | 1.42%   |
| Intel SATA Controller [RAID mode]                                                       | 4         | 1.42%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 4         | 1.42%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4         | 1.42%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4         | 1.42%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4         | 1.42%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3         | 1.06%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 3         | 1.06%   |
| Intel Non-Volatile memory controller                                                    | 3         | 1.06%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 3         | 1.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3         | 1.06%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 1.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 3         | 1.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 3         | 1.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3         | 1.06%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3         | 1.06%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 3         | 1.06%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller        | 2         | 0.71%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 2         | 0.71%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 2         | 0.71%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2         | 0.71%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2         | 0.71%   |
| Sandisk PC SN520 NVMe SSD                                                               | 2         | 0.71%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 0.71%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 2         | 0.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2         | 0.71%   |
| Micron Non-Volatile memory controller                                                   | 2         | 0.71%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 2         | 0.71%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 0.71%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 2         | 0.71%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2         | 0.71%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 0.71%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 0.71%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2         | 0.71%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2         | 0.71%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2         | 0.71%   |
| AMD FCH SATA Controller D                                                               | 2         | 0.71%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1         | 0.35%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                             | 1         | 0.35%   |
| SK Hynix BC511                                                                          | 1         | 0.35%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1         | 0.35%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 1         | 0.35%   |
| Samsung NVMe SSD Controller 980                                                         | 1         | 0.35%   |
| Samsung Electronics Non-Volatile memory controller                                      | 1         | 0.35%   |
| Realtek Realtek Non-Volatile memory controller                                          | 1         | 0.35%   |
| Phison E7 NVMe Controller                                                               | 1         | 0.35%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 145       | 58.7%   |
| NVMe | 69        | 27.94%  |
| IDE  | 17        | 6.88%   |
| RAID | 15        | 6.07%   |
| SAS  | 1         | 0.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 164       | 84.1%   |
| AMD    | 30        | 15.38%  |
| ARM    | 1         | 0.51%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 3.06%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 2.04%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 2.04%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 4         | 2.04%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 4         | 2.04%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 2.04%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 2.04%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 1.53%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.53%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 3         | 1.53%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 1.53%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.53%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 1.53%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 3         | 1.53%   |
| AMD Ryzen 5 3600 6-Core Processor             | 3         | 1.53%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 3         | 1.53%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 2         | 1.02%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.02%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 1.02%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 2         | 1.02%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 1.02%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 2         | 1.02%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 1.02%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.02%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 1.02%   |
| Intel Core i5-2415M CPU @ 2.30GHz             | 2         | 1.02%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 1.02%   |
| Intel Core i5 CPU 750 @ 2.67GHz               | 2         | 1.02%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 2         | 1.02%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 2         | 1.02%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 1.02%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.02%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 2         | 1.02%   |
| Intel Xeon CPU W3530 @ 2.80GHz                | 1         | 0.51%   |
| Intel Xeon CPU E5-2680 0 @ 2.70GHz            | 1         | 0.51%   |
| Intel Xeon CPU 5150 @ 2.66GHz                 | 1         | 0.51%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.51%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.51%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 0.51%   |
| Intel Pentium CPU G2030 @ 3.00GHz             | 1         | 0.51%   |
| Intel Pentium 3556U @ 1.70GHz                 | 1         | 0.51%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz              | 1         | 0.51%   |
| Intel Core i9-9900KF CPU @ 3.60GHz            | 1         | 0.51%   |
| Intel Core i7-9700 CPU @ 3.00GHz              | 1         | 0.51%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 0.51%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 1         | 0.51%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 0.51%   |
| Intel Core i7-7Y75 CPU @ 1.30GHz              | 1         | 0.51%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 0.51%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 0.51%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.51%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 0.51%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1         | 0.51%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 1         | 0.51%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.51%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 1         | 0.51%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 1         | 0.51%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 1         | 0.51%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 0.51%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 80        | 40.82%  |
| Intel Core i5           | 42        | 21.43%  |
| Intel Core i3           | 11        | 5.61%   |
| AMD Ryzen 5             | 11        | 5.61%   |
| Intel Core 2 Duo        | 9         | 4.59%   |
| AMD Ryzen 7             | 8         | 4.08%   |
| Other                   | 5         | 2.55%   |
| Intel Pentium           | 4         | 2.04%   |
| Intel Xeon              | 3         | 1.53%   |
| Intel Core i9           | 3         | 1.53%   |
| AMD Ryzen 3             | 3         | 1.53%   |
| Intel Core 2            | 2         | 1.02%   |
| Intel Celeron           | 2         | 1.02%   |
| Intel Atom              | 2         | 1.02%   |
| AMD Ryzen 9             | 2         | 1.02%   |
| AMD A6                  | 2         | 1.02%   |
| Intel Pentium Dual-Core | 1         | 0.51%   |
| Intel Core m5           | 1         | 0.51%   |
| Intel Core 2 Quad       | 1         | 0.51%   |
| AMD Quad-Core           | 1         | 0.51%   |
| AMD Phenom II X6        | 1         | 0.51%   |
| AMD E1                  | 1         | 0.51%   |
| AMD A8                  | 1         | 0.51%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 88        | 45.13%  |
| 2      | 67        | 34.36%  |
| 6      | 23        | 11.79%  |
| 8      | 14        | 7.18%   |
| 16     | 1         | 0.51%   |
| 12     | 1         | 0.51%   |
| 1      | 1         | 0.51%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 193       | 98.97%  |
| 2      | 2         | 1.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 149       | 76.02%  |
| 1      | 47        | 23.98%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 194       | 99.49%  |
| Unknown        | 1         | 0.51%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 11.39%  |
| 0x206a7    | 19        | 9.41%   |
| 0x306a9    | 17        | 8.42%   |
| 0x906ea    | 11        | 5.45%   |
| 0x806ec    | 10        | 4.95%   |
| 0x306c3    | 9         | 4.46%   |
| 0x806ea    | 8         | 3.96%   |
| 0x40651    | 7         | 3.47%   |
| 0x806e9    | 6         | 2.97%   |
| 0x506e3    | 6         | 2.97%   |
| 0x1067a    | 6         | 2.97%   |
| 0x406e3    | 5         | 2.48%   |
| 0xa0652    | 4         | 1.98%   |
| 0x906e9    | 4         | 1.98%   |
| 0x806c1    | 4         | 1.98%   |
| 0x906ec    | 3         | 1.49%   |
| 0x806eb    | 3         | 1.49%   |
| 0x706e5    | 3         | 1.49%   |
| 0x406c3    | 3         | 1.49%   |
| 0x306d4    | 3         | 1.49%   |
| 0x08701021 | 3         | 1.49%   |
| 0x08600103 | 3         | 1.49%   |
| 0x08108109 | 3         | 1.49%   |
| 0x0800820d | 3         | 1.49%   |
| 0x906ed    | 2         | 0.99%   |
| 0x6f6      | 2         | 0.99%   |
| 0x406c4    | 2         | 0.99%   |
| 0x206d7    | 2         | 0.99%   |
| 0x20655    | 2         | 0.99%   |
| 0x20652    | 2         | 0.99%   |
| 0x106e5    | 2         | 0.99%   |
| 0x10676    | 2         | 0.99%   |
| 0x08701013 | 2         | 0.99%   |
| 0x0810100b | 2         | 0.99%   |
| 0x0700010f | 2         | 0.99%   |
| 0xa0660    | 1         | 0.5%    |
| 0x6fb      | 1         | 0.5%    |
| 0x6fa      | 1         | 0.5%    |
| 0x6f2      | 1         | 0.5%    |
| 0x30678    | 1         | 0.5%    |
| 0x106a5    | 1         | 0.5%    |
| 0x08608103 | 1         | 0.5%    |
| 0x08600106 | 1         | 0.5%    |
| 0x08600102 | 1         | 0.5%    |
| 0x08101016 | 1         | 0.5%    |
| 0x07030105 | 1         | 0.5%    |
| 0x0600611a | 1         | 0.5%    |
| 0x06001119 | 1         | 0.5%    |
| 0x010000dc | 1         | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KabyLake    | 54        | 27.69%  |
| SandyBridge | 21        | 10.77%  |
| IvyBridge   | 18        | 9.23%   |
| Haswell     | 17        | 8.72%   |
| Zen 2       | 13        | 6.67%   |
| Skylake     | 11        | 5.64%   |
| Penryn      | 9         | 4.62%   |
| Zen+        | 7         | 3.59%   |
| Silvermont  | 6         | 3.08%   |
| Core        | 5         | 2.56%   |
| CometLake   | 5         | 2.56%   |
| Westmere    | 4         | 2.05%   |
| TigerLake   | 4         | 2.05%   |
| Nehalem     | 4         | 2.05%   |
| Zen         | 3         | 1.54%   |
| IceLake     | 3         | 1.54%   |
| Broadwell   | 3         | 1.54%   |
| Jaguar      | 2         | 1.03%   |
| Unknown     | 2         | 1.03%   |
| Puma        | 1         | 0.51%   |
| Piledriver  | 1         | 0.51%   |
| K10         | 1         | 0.51%   |
| Excavator   | 1         | 0.51%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 128       | 50.59%  |
| Nvidia | 84        | 33.2%   |
| AMD    | 41        | 16.21%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 6.61%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 11        | 4.28%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 4.28%   |
| Intel UHD Graphics 620                                                                   | 8         | 3.11%   |
| Intel HD Graphics 620                                                                    | 7         | 2.72%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 2.72%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 2.72%   |
| Intel HD Graphics 630                                                                    | 5         | 1.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.95%   |
| AMD Renoir                                                                               | 5         | 1.95%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4         | 1.56%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 4         | 1.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 1.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 1.56%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.56%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.56%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.56%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.17%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 3         | 1.17%   |
| Nvidia GP108M [GeForce MX250]                                                            | 3         | 1.17%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 1.17%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 3         | 1.17%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 1.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 1.17%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.17%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.17%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3         | 1.17%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 1.17%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.17%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 1.17%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 3         | 1.17%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 1.17%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.78%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 2         | 0.78%   |
| Nvidia GP108GLM [Quadro P520]                                                            | 2         | 0.78%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.78%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.78%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 2         | 0.78%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 0.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.78%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.78%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.78%   |
| Intel HD Graphics 530                                                                    | 2         | 0.78%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 2         | 0.78%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 2         | 0.78%   |
| AMD Juniper XT [Radeon HD 5770]                                                          | 2         | 0.78%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.39%   |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.39%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1         | 0.39%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.39%   |
| Nvidia TU116 [GeForce GTX 1650]                                                          | 1         | 0.39%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.39%   |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 1         | 0.39%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1         | 0.39%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 1         | 0.39%   |
| Nvidia TU104 [GeForce RTX 2060]                                                          | 1         | 0.39%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.39%   |
| Nvidia GT200GL [Quadro FX 3800]                                                          | 1         | 0.39%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.39%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 77        | 38.89%  |
| Intel + Nvidia | 42        | 21.21%  |
| 1 x Nvidia     | 36        | 18.18%  |
| 1 x AMD        | 27        | 13.64%  |
| Intel + AMD    | 8         | 4.04%   |
| AMD + Nvidia   | 5         | 2.53%   |
| Other          | 1         | 0.51%   |
| 2 x Nvidia     | 1         | 0.51%   |
| 2 x AMD        | 1         | 0.51%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 126       | 63.32%  |
| Proprietary | 68        | 34.17%  |
| Unknown     | 5         | 2.51%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 102       | 51%     |
| 1.01-2.0   | 31        | 15.5%   |
| 3.01-4.0   | 17        | 8.5%    |
| 7.01-8.0   | 12        | 6%      |
| 5.01-6.0   | 12        | 6%      |
| 0.51-1.0   | 12        | 6%      |
| 0.01-0.5   | 12        | 6%      |
| 2.01-3.0   | 1         | 0.5%    |
| 8.01-16.0  | 1         | 0.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 30        | 12.66%  |
| LG Display              | 28        | 11.81%  |
| Chimei Innolux          | 26        | 10.97%  |
| AU Optronics            | 26        | 10.97%  |
| Dell                    | 18        | 7.59%   |
| Goldstar                | 11        | 4.64%   |
| BOE                     | 11        | 4.64%   |
| Hewlett-Packard         | 9         | 3.8%    |
| Apple                   | 6         | 2.53%   |
| AOC                     | 6         | 2.53%   |
| Ancor Communications    | 6         | 2.53%   |
| Unknown                 | 5         | 2.11%   |
| Chi Mei Optoelectronics | 5         | 2.11%   |
| Philips                 | 4         | 1.69%   |
| BenQ                    | 4         | 1.69%   |
| Acer                    | 4         | 1.69%   |
| Sharp                   | 3         | 1.27%   |
| PANDA                   | 3         | 1.27%   |
| LG Electronics          | 3         | 1.27%   |
| InfoVision              | 3         | 1.27%   |
| Eizo                    | 3         | 1.27%   |
| LGD                     | 2         | 0.84%   |
| Idek Iiyama             | 2         | 0.84%   |
| UPD                     | 1         | 0.42%   |
| Sceptre Tech            | 1         | 0.42%   |
| RTK                     | 1         | 0.42%   |
| Pioneer Electronic      | 1         | 0.42%   |
| Orion                   | 1         | 0.42%   |
| NEC Computers           | 1         | 0.42%   |
| MStar                   | 1         | 0.42%   |
| MPI                     | 1         | 0.42%   |
| Medion                  | 1         | 0.42%   |
| Lenovo                  | 1         | 0.42%   |
| KTC                     | 1         | 0.42%   |
| JDI                     | 1         | 0.42%   |
| InnoLux Display         | 1         | 0.42%   |
| HannStar                | 1         | 0.42%   |
| Fujitsu Siemens         | 1         | 0.42%   |
| Daewoo                  | 1         | 0.42%   |
| CSO                     | 1         | 0.42%   |
| ASUSTek Computer        | 1         | 0.42%   |
| AGO                     | 1         | 0.42%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch    | 2         | 0.8%    |
| Samsung Electronics LCD Monitor SAM0BB4 3840x2160 1872x1053mm 84.6-inch | 2         | 0.8%    |
| Samsung Electronics LCD Monitor C34H89x 3440x1440                       | 2         | 0.8%    |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch     | 2         | 0.8%    |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 2         | 0.8%    |
| LGD LCD Monitor 1920x1080                                               | 2         | 0.8%    |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch            | 2         | 0.8%    |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch             | 2         | 0.8%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 2         | 0.8%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch        | 2         | 0.8%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 2         | 0.8%    |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch        | 2         | 0.8%    |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch         | 2         | 0.8%    |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch          | 2         | 0.8%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch          | 2         | 0.8%    |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch           | 2         | 0.8%    |
| UPD LCD801 UPD4843 1920x1080 708x398mm 32.0-inch                        | 1         | 0.4%    |
| Unknown LCD Monitor Sony Nvidia Default Flat Panel 1366x768             | 1         | 0.4%    |
| Unknown LCD Monitor SAMSUNG 3840x2160                                   | 1         | 0.4%    |
| Unknown LCD Monitor SAMSUNG                                             | 1         | 0.4%    |
| Unknown LCD Monitor GTW KX2153                                          | 1         | 0.4%    |
| Unknown LCD Monitor EMA E202HL                                          | 1         | 0.4%    |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                 | 1         | 0.4%    |
| Sharp LCD Monitor SHP146A 1920x1080 294x165mm 13.3-inch                 | 1         | 0.4%    |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch                 | 1         | 0.4%    |
| Sceptre Tech Sceptre B34 SPT0D52 2560x1080 797x334mm 34.0-inch          | 1         | 0.4%    |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch       | 1         | 0.4%    |
| Samsung Electronics U28E570 SAM0D70 3840x2160 608x345mm 27.5-inch       | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM060D 1920x1080 531x299mm 24.0-inch    | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                        | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM041D 1920x1200 459x296mm 21.5-inch    | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM021B 1400x1050 408x300mm 19.9-inch    | 1         | 0.4%    |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch       | 1         | 0.4%    |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch       | 1         | 0.4%    |
| Samsung Electronics S27B550 SAM091B 1920x1080 598x336mm 27.0-inch       | 1         | 0.4%    |
| Samsung Electronics S24C650 SAM09E9 1920x1080 521x293mm 23.5-inch       | 1         | 0.4%    |
| Samsung Electronics S24B300 SAM08CC 1920x1080 521x293mm 23.5-inch       | 1         | 0.4%    |
| Samsung Electronics S24B300 SAM08B4 1920x1080 521x293mm 23.5-inch       | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SEC5A42 1366x768 309x174mm 14.0-inch    | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch    | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch    | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SEC324C 1366x768 353x198mm 15.9-inch    | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch    | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 340x190mm 15.3-inch    | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SDC3150 1920x1080 344x194mm 15.5-inch   | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SAM0C3C 1920x1080 700x390mm 31.5-inch   | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch  | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SAM090B 1920x1080 1020x570mm 46.0-inch  | 1         | 0.4%    |
| Samsung Electronics LCD Monitor SAM06CA 1920x1080 1110x620mm 50.1-inch  | 1         | 0.4%    |
| Samsung Electronics LCD Monitor S24E310 3840x1080                       | 1         | 0.4%    |
| Samsung Electronics LCD Monitor S24E310                                 | 1         | 0.4%    |
| Samsung Electronics LCD Monitor C32F391 1920x1080                       | 1         | 0.4%    |
| Samsung Electronics C32F39M SAM100B 1920x1080 698x393mm 31.5-inch       | 1         | 0.4%    |
| RTK LCD Monitor RTK2136 1280x800 473x296mm 22.0-inch                    | 1         | 0.4%    |
| Pioneer Electronic LCD Monitor PDP-42FXE10 2646x768                     | 1         | 0.4%    |
| Pioneer Electronic LCD Monitor PDP-42FXE10 2390x768                     | 1         | 0.4%    |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                 | 1         | 0.4%    |
| Philips 298X4 PHLC0BD 2560x1080 673x284mm 28.8-inch                     | 1         | 0.4%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                 | 1         | 0.4%    |
| PANDA LCD Monitor NCP004B 1920x1080 344x194mm 15.5-inch                 | 1         | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 90        | 40.54%  |
| 1366x768 (WXGA)    | 46        | 20.72%  |
| 3840x2160 (4K)     | 12        | 5.41%   |
| 2560x1440 (QHD)    | 8         | 3.6%    |
| 2560x1080          | 6         | 2.7%    |
| 1920x1200 (WUXGA)  | 6         | 2.7%    |
| 1600x900 (HD+)     | 6         | 2.7%    |
| 1280x1024 (SXGA)   | 6         | 2.7%    |
| Unknown            | 6         | 2.7%    |
| 1680x1050 (WSXGA+) | 5         | 2.25%   |
| 1280x800 (WXGA)    | 4         | 1.8%    |
| 3840x1080          | 3         | 1.35%   |
| 3440x1440          | 3         | 1.35%   |
| 1440x900 (WXGA+)   | 3         | 1.35%   |
| 1600x1200          | 2         | 0.9%    |
| 1360x768           | 2         | 0.9%    |
| 3840x2400          | 1         | 0.45%   |
| 3520x1080          | 1         | 0.45%   |
| 3000x2000          | 1         | 0.45%   |
| 2880x1800          | 1         | 0.45%   |
| 2646x768           | 1         | 0.45%   |
| 2560x1600          | 1         | 0.45%   |
| 2560x1024          | 1         | 0.45%   |
| 2390x768           | 1         | 0.45%   |
| 2256x1504          | 1         | 0.45%   |
| 2048x1152          | 1         | 0.45%   |
| 1920x540           | 1         | 0.45%   |
| 1920x1280          | 1         | 0.45%   |
| 1400x1050          | 1         | 0.45%   |
| 1280x720 (HD)      | 1         | 0.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 63        | 26.69%  |
| Unknown | 27        | 11.44%  |
| 13      | 24        | 10.17%  |
| 14      | 19        | 8.05%   |
| 27      | 18        | 7.63%   |
| 24      | 14        | 5.93%   |
| 23      | 11        | 4.66%   |
| 17      | 9         | 3.81%   |
| 19      | 6         | 2.54%   |
| 12      | 6         | 2.54%   |
| 21      | 5         | 2.12%   |
| 34      | 4         | 1.69%   |
| 31      | 4         | 1.69%   |
| 20      | 4         | 1.69%   |
| 22      | 3         | 1.27%   |
| 11      | 3         | 1.27%   |
| 84      | 2         | 0.85%   |
| 54      | 2         | 0.85%   |
| 28      | 2         | 0.85%   |
| 18      | 2         | 0.85%   |
| 63      | 1         | 0.42%   |
| 52      | 1         | 0.42%   |
| 48      | 1         | 0.42%   |
| 44      | 1         | 0.42%   |
| 32      | 1         | 0.42%   |
| 29      | 1         | 0.42%   |
| 16      | 1         | 0.42%   |
| 8       | 1         | 0.42%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 92        | 39.48%  |
| 501-600     | 37        | 15.88%  |
| Unknown     | 27        | 11.59%  |
| 201-300     | 22        | 9.44%   |
| 401-500     | 16        | 6.87%   |
| 351-400     | 15        | 6.44%   |
| 601-700     | 10        | 4.29%   |
| 701-800     | 5         | 2.15%   |
| 1001-1500   | 5         | 2.15%   |
| 1501-2000   | 2         | 0.86%   |
| 101-200     | 1         | 0.43%   |
| 901-1000    | 1         | 0.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 139       | 68.47%  |
| Unknown | 25        | 12.32%  |
| 16/10   | 18        | 8.87%   |
| 21/9    | 6         | 2.96%   |
| 5/4     | 5         | 2.46%   |
| 4/3     | 5         | 2.46%   |
| 3/2     | 3         | 1.48%   |
| 6/5     | 1         | 0.49%   |
| 32/9    | 1         | 0.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 62        | 26.5%   |
| 81-90          | 32        | 13.68%  |
| 201-250        | 28        | 11.97%  |
| Unknown        | 27        | 11.54%  |
| 301-350        | 18        | 7.69%   |
| 71-80          | 12        | 5.13%   |
| 351-500        | 10        | 4.27%   |
| 151-200        | 9         | 3.85%   |
| More than 1000 | 7         | 2.99%   |
| 121-130        | 7         | 2.99%   |
| 251-300        | 6         | 2.56%   |
| 61-70          | 5         | 2.14%   |
| 51-60          | 3         | 1.28%   |
| 141-150        | 3         | 1.28%   |
| 131-140        | 2         | 0.85%   |
| 1-40           | 1         | 0.43%   |
| 501-1000       | 1         | 0.43%   |
| 91-100         | 1         | 0.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 63        | 28.13%  |
| 51-100        | 60        | 26.79%  |
| 101-120       | 48        | 21.43%  |
| Unknown       | 27        | 12.05%  |
| 161-240       | 12        | 5.36%   |
| More than 240 | 7         | 3.13%   |
| 1-50          | 7         | 3.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 144       | 72%     |
| 2     | 43        | 21.5%   |
| 3     | 8         | 4%      |
| 0     | 5         | 2.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 114       | 36.42%  |
| Realtek Semiconductor    | 106       | 33.87%  |
| Qualcomm Atheros         | 41        | 13.1%   |
| Broadcom                 | 20        | 6.39%   |
| Ralink                   | 5         | 1.6%    |
| Ralink Technology        | 4         | 1.28%   |
| Marvell Technology Group | 4         | 1.28%   |
| Broadcom Limited         | 4         | 1.28%   |
| Hewlett-Packard          | 2         | 0.64%   |
| Xiaomi                   | 1         | 0.32%   |
| Wacom                    | 1         | 0.32%   |
| Sierra Wireless          | 1         | 0.32%   |
| Nvidia                   | 1         | 0.32%   |
| NetGear                  | 1         | 0.32%   |
| Microsoft                | 1         | 0.32%   |
| MEDIATEK                 | 1         | 0.32%   |
| Luminary Micro           | 1         | 0.32%   |
| Linksys                  | 1         | 0.32%   |
| Lenovo                   | 1         | 0.32%   |
| D-Link System            | 1         | 0.32%   |
| D-Link                   | 1         | 0.32%   |
| ASIX Electronics         | 1         | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 67        | 18.16%  |
| Intel Wi-Fi 6 AX200                                               | 20        | 5.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 15        | 4.07%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 3.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 3.52%   |
| Intel Wireless 8265 / 8275                                        | 12        | 3.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 1.9%    |
| Intel Wireless-AC 9260                                            | 7         | 1.9%    |
| Intel Wireless 8260                                               | 7         | 1.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 6         | 1.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 1.63%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 1.36%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 1.36%   |
| Intel I211 Gigabit Network Connection                             | 5         | 1.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 1.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 1.08%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 1.08%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.08%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 1.08%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 1.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 1.08%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 0.81%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.81%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 0.81%   |
| Intel Wireless 7265                                               | 3         | 0.81%   |
| Intel Wireless 3165                                               | 3         | 0.81%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.81%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.81%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 0.81%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 0.81%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 0.81%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 3         | 0.81%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 0.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.54%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 2         | 0.54%   |
| Realtek 802.11ac NIC                                              | 2         | 0.54%   |
| Ralink MT7601U Wireless Adapter                                   | 2         | 0.54%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.54%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.54%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.54%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 2         | 0.54%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.54%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.54%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.54%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.54%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.54%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.54%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.54%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.54%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 0.54%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 2         | 0.54%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 0.54%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.27%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                          | 1         | 0.27%   |
| Sierra Wireless EM7305                                            | 1         | 0.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.27%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 94        | 53.41%  |
| Qualcomm Atheros      | 29        | 16.48%  |
| Realtek Semiconductor | 18        | 10.23%  |
| Broadcom              | 14        | 7.95%   |
| Ralink                | 5         | 2.84%   |
| Ralink Technology     | 4         | 2.27%   |
| Broadcom Limited      | 4         | 2.27%   |
| Wacom                 | 1         | 0.57%   |
| Sierra Wireless       | 1         | 0.57%   |
| NetGear               | 1         | 0.57%   |
| Microsoft             | 1         | 0.57%   |
| MEDIATEK              | 1         | 0.57%   |
| Linksys               | 1         | 0.57%   |
| D-Link System         | 1         | 0.57%   |
| D-Link                | 1         | 0.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 20        | 11.3%   |
| Intel Wireless 8265 / 8275                                     | 12        | 6.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 7         | 3.95%   |
| Intel Wireless-AC 9260                                         | 7         | 3.95%   |
| Intel Wireless 8260                                            | 7         | 3.95%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 6         | 3.39%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 6         | 3.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 2.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 2.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 2.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 2.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 4         | 2.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 2.26%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 1.69%   |
| Intel Wireless 7265                                            | 3         | 1.69%   |
| Intel Wireless 3165                                            | 3         | 1.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 1.69%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 1.69%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 3         | 1.69%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 1.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 1.13%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 2         | 1.13%   |
| Realtek 802.11ac NIC                                           | 2         | 1.13%   |
| Ralink MT7601U Wireless Adapter                                | 2         | 1.13%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 1.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.13%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 2         | 1.13%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.13%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.13%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 2         | 1.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 1.13%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                       | 1         | 0.56%   |
| Sierra Wireless EM7305                                         | 1         | 0.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.56%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.56%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1         | 0.56%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 0.56%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 1         | 0.56%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1         | 0.56%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.56%   |
| Ralink RT5372 Wireless Adapter                                 | 1         | 0.56%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 0.56%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.56%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.56%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 1         | 0.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 0.56%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]    | 1         | 0.56%   |
| Microsoft XBOX ACC                                             | 1         | 0.56%   |
| MEDIATEK Network controller                                    | 1         | 0.56%   |
| Linksys WUSB54GC v1 802.11g Adapter [Ralink RT73]              | 1         | 0.56%   |
| Intel Wireless 7260                                            | 1         | 0.56%   |
| Intel Wireless 3160                                            | 1         | 0.56%   |
| Intel WiFi Link 5100                                           | 1         | 0.56%   |
| Intel Wi-Fi 6 AX201                                            | 1         | 0.56%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 0.56%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 0.56%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 0.56%   |
| Intel Centrino Wireless-N 2230                                 | 1         | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 98        | 52.69%  |
| Intel                    | 54        | 29.03%  |
| Qualcomm Atheros         | 16        | 8.6%    |
| Broadcom                 | 9         | 4.84%   |
| Marvell Technology Group | 4         | 2.15%   |
| Xiaomi                   | 1         | 0.54%   |
| Nvidia                   | 1         | 0.54%   |
| Lenovo                   | 1         | 0.54%   |
| Hewlett-Packard          | 1         | 0.54%   |
| ASIX Electronics         | 1         | 0.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 67        | 35.26%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 15        | 7.89%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 6.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 6.84%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 2.63%   |
| Intel I211 Gigabit Network Connection                             | 5         | 2.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 2.11%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 2.11%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 2.11%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 2.11%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 1.58%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 1.58%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.58%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.58%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.58%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 1.58%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.05%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.05%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 1.05%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 1.05%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.05%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.05%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.05%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 1.05%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 1.05%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.53%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.53%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.53%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.53%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.53%   |
| Lenovo ThinkPad TBT3 LAN                                          | 1         | 0.53%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.53%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.53%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.53%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.53%   |
| Intel 82566DM Gigabit Network Connection                          | 1         | 0.53%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1         | 0.53%   |
| HP lt4120 Snapdragon X5 LTE                                       | 1         | 0.53%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.53%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 0.53%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 0.53%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.53%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.53%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 0.53%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 175       | 50.87%  |
| WiFi     | 167       | 48.55%  |
| Modem    | 2         | 0.58%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 152       | 56.09%  |
| Ethernet | 119       | 43.91%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 127       | 65.13%  |
| 1     | 59        | 30.26%  |
| 3     | 6         | 3.08%   |
| 0     | 3         | 1.54%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 184       | 92.93%  |
| Yes  | 14        | 7.07%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 72        | 51.43%  |
| Qualcomm Atheros Communications | 11        | 7.86%   |
| Broadcom                        | 11        | 7.86%   |
| Lite-On Technology              | 9         | 6.43%   |
| Cambridge Silicon Radio         | 8         | 5.71%   |
| Realtek Semiconductor           | 6         | 4.29%   |
| Apple                           | 6         | 4.29%   |
| Foxconn / Hon Hai               | 3         | 2.14%   |
| Dell                            | 3         | 2.14%   |
| Ralink                          | 2         | 1.43%   |
| IMC Networks                    | 2         | 1.43%   |
| Hewlett-Packard                 | 2         | 1.43%   |
| ASUSTek Computer                | 2         | 1.43%   |
| Toshiba                         | 1         | 0.71%   |
| Realtek                         | 1         | 0.71%   |
| Belkin Components               | 1         | 0.71%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 25        | 17.86%  |
| Intel AX200 Bluetooth                                                               | 19        | 13.57%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 11        | 7.86%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 8         | 5.71%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 7         | 5%      |
| Intel Bluetooth Device                                                              | 6         | 4.29%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 2.86%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 4         | 2.86%   |
| Realtek Bluetooth Radio                                                             | 3         | 2.14%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 2.14%   |
| Lite-On Bluetooth Device                                                            | 3         | 2.14%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 2.14%   |
| Dell DW375 Bluetooth Module                                                         | 3         | 2.14%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 3         | 2.14%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 1.43%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 1.43%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.43%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.43%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.43%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 2         | 1.43%   |
| Apple Bluetooth Host Controller                                                     | 2         | 1.43%   |
| Apple Bluetooth HCI                                                                 | 2         | 1.43%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.71%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.71%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.71%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.71%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.71%   |
| Lite-On Atheros Bluetooth                                                           | 1         | 0.71%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.71%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.71%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.71%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.71%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.71%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.71%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 0.71%   |
| Broadcom BRCM2070 BT 2.1 + HS USB Module                                            | 1         | 0.71%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                                    | 1         | 0.71%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.71%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 0.71%   |
| Broadcom BCM20702A0                                                                 | 1         | 0.71%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.71%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                               | 1         | 0.71%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 1         | 0.71%   |
| ASUS Bluetooth Adapter                                                              | 1         | 0.71%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 160       | 53.87%  |
| Nvidia                    | 58        | 19.53%  |
| AMD                       | 41        | 13.8%   |
| Realtek Semiconductor     | 6         | 2.02%   |
| C-Media Electronics       | 6         | 2.02%   |
| GN Netcom                 | 4         | 1.35%   |
| Kingston Technology       | 3         | 1.01%   |
| Logitech                  | 2         | 0.67%   |
| JMTek                     | 2         | 0.67%   |
| Focusrite-Novation        | 2         | 0.67%   |
| Blue Microphones          | 2         | 0.67%   |
| SteelSeries ApS           | 1         | 0.34%   |
| Sennheiser Communications | 1         | 0.34%   |
| Razer USA                 | 1         | 0.34%   |
| Plantronics               | 1         | 0.34%   |
| Microsoft                 | 1         | 0.34%   |
| Lenovo                    | 1         | 0.34%   |
| Hewlett-Packard           | 1         | 0.34%   |
| Generalplus Technology    | 1         | 0.34%   |
| Creative Labs             | 1         | 0.34%   |
| Bose                      | 1         | 0.34%   |
| AKAI Professional M.I.    | 1         | 0.34%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 21        | 6.31%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 19        | 5.71%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 18        | 5.41%   |
| Intel Cannon Lake PCH cAVS                                                                        | 14        | 4.2%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 12        | 3.6%    |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 12        | 3.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 2.7%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 8         | 2.4%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 7         | 2.1%    |
| Nvidia GP106 High Definition Audio Controller                                                     | 7         | 2.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 2.1%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 2.1%    |
| Intel 8 Series HD Audio Controller                                                                | 7         | 2.1%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 2.1%    |
| Realtek Semiconductor USB Audio                                                                   | 6         | 1.8%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 1.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 1.8%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 1.5%    |
| Intel CM238 HD Audio Controller                                                                   | 5         | 1.5%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 1.2%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 4         | 1.2%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 1.2%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 1.2%    |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.2%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 1.2%    |
| Intel 200 Series PCH HD Audio                                                                     | 4         | 1.2%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.2%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.2%    |
| AMD Navi 10 HDMI Audio                                                                            | 4         | 1.2%    |
| AMD FCH Azalia Controller                                                                         | 4         | 1.2%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4         | 1.2%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.9%    |
| Nvidia GP108 High Definition Audio Controller                                                     | 3         | 0.9%    |
| Nvidia GP104 High Definition Audio Controller                                                     | 3         | 0.9%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 0.9%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 0.9%    |
| Intel Broadwell-U Audio Controller                                                                | 3         | 0.9%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 3         | 0.9%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 0.9%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3         | 0.9%    |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 0.6%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.6%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.6%    |
| Kingston Technology HyperX Cloud Stinger Wireless                                                 | 2         | 0.6%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 0.6%    |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 2         | 0.6%    |
| C-Media Electronics Blue Snowball                                                                 | 2         | 0.6%    |
| Blue Microphones Yeti Stereo Microphone                                                           | 2         | 0.6%    |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                                        | 2         | 0.6%    |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 0.6%    |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 2         | 0.6%    |
| SteelSeries ApS SteelSeries Arctis 5                                                              | 1         | 0.3%    |
| Sennheiser Communications Sennheiser DECT for Lync                                                | 1         | 0.3%    |
| Razer USA Kraken Tournament Edition                                                               | 1         | 0.3%    |
| Plantronics C320-M                                                                                | 1         | 0.3%    |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.3%    |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.3%    |
| Nvidia GP102 HDMI Audio Controller                                                                | 1         | 0.3%    |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.3%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 36        | 26.87%  |
| SK Hynix            | 31        | 23.13%  |
| Micron Technology   | 13        | 9.7%    |
| Kingston            | 10        | 7.46%   |
| Crucial             | 9         | 6.72%   |
| Unknown             | 6         | 4.48%   |
| Corsair             | 6         | 4.48%   |
| G.Skill             | 4         | 2.99%   |
| A-DATA Technology   | 4         | 2.99%   |
| Smart               | 2         | 1.49%   |
| Ramaxel Technology  | 2         | 1.49%   |
| Unknown (F301)      | 1         | 0.75%   |
| TIMETEC             | 1         | 0.75%   |
| Teikon              | 1         | 0.75%   |
| Team                | 1         | 0.75%   |
| SMART Brazil        | 1         | 0.75%   |
| Sesame              | 1         | 0.75%   |
| Nanya Technology    | 1         | 0.75%   |
| Kingmax             | 1         | 0.75%   |
| Elpida              | 1         | 0.75%   |
| ASint Technology    | 1         | 0.75%   |
| Unknown             | 1         | 0.75%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s            | 4         | 2.78%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s              | 3         | 2.08%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 3         | 2.08%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 2667MT/s           | 3         | 2.08%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 1.39%   |
| SK Hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 1.39%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1333MT/s           | 2         | 1.39%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 2         | 1.39%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 1.39%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s           | 2         | 1.39%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s            | 2         | 1.39%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s            | 2         | 1.39%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 2         | 1.39%   |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM 1334MT/s                | 2         | 1.39%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s              | 2         | 1.39%   |
| Corsair RAM CMW32GX4M2C3200C16 16384MB DIMM DDR4 3200MT/s           | 2         | 1.39%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2400MT/s                      | 1         | 0.69%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                        | 1         | 0.69%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                      | 1         | 0.69%   |
| Unknown RAM Module 4096MB SODIMM DDR3                               | 1         | 0.69%   |
| Unknown RAM Module 4096MB DIMM DDR 1066MT/s                         | 1         | 0.69%   |
| Unknown RAM Module 2048MB SODIMM DDR3                               | 1         | 0.69%   |
| Unknown RAM Module 2048MB DIMM SDRAM                                | 1         | 0.69%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s                         | 1         | 0.69%   |
| Unknown RAM Module 2048MB DIMM DDR 1066MT/s                         | 1         | 0.69%   |
| Unknown (F301) RAM G2RT-4AFT00 16384MB SODIMM DDR4 2667MT/s         | 1         | 0.69%   |
| TIMETEC RAM ED3-1600 8192MB DIMM DDR3 1600MT/s                      | 1         | 0.69%   |
| Teikon RAM TMT451S6BFR8A-PBAJ 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.69%   |
| Team RAM TEAMGROUP-UD4-2400 8192MB DIMM DDR4 3007MT/s               | 1         | 0.69%   |
| Smart RAM SMS4TDC3C0K0446SCG 4096MB SODIMM DDR4 2667MT/s            | 1         | 0.69%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s               | 1         | 0.69%   |
| Smart RAM SF4641G8CK8IEHLSBG 8192MB SODIMM DDR4 2667MT/s            | 1         | 0.69%   |
| SMART Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s        | 1         | 0.69%   |
| SK Hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s                   | 1         | 0.69%   |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1333MT/s                     | 1         | 0.69%   |
| SK Hynix RAM Module 4096MB FB-DIMM DDR2 667MT/s                     | 1         | 0.69%   |
| SK Hynix RAM Module 16384MB SODIMM DDR4 2133MT/s                    | 1         | 0.69%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s                | 1         | 0.69%   |
| SK Hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.69%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.69%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.69%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.69%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s              | 1         | 0.69%   |
| SK Hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1333MT/s              | 1         | 0.69%   |
| SK Hynix RAM HMT125S6AFR8C-G7 2048MB SODIMM DDR3 1067MT/s           | 1         | 0.69%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 0.69%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s        | 1         | 0.69%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s           | 1         | 0.69%   |
| SK Hynix RAM HMA851S6AFR6N-TF 4GB SODIMM DDR4 2133MT/s              | 1         | 0.69%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 1         | 0.69%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s             | 1         | 0.69%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s           | 1         | 0.69%   |
| SK Hynix RAM H9CCNNNCLTMLAR-NUD 8192MB Row Of Chips LPDDR3 1867MT/s | 1         | 0.69%   |
| SK Hynix RAM H5TC4G63AFR-PBA 1GB SODIMM DDR3 1600MT/s               | 1         | 0.69%   |
| Sesame RAM S939A2UGS-ITR.. 8192MB DIMM DDR3 1600MT/s                | 1         | 0.69%   |
| Samsung RAM Module 8192MB Row Of Chips LPDDR4 3733MT/s              | 1         | 0.69%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                         | 1         | 0.69%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2133MT/s                      | 1         | 0.69%   |
| Samsung RAM M471B5673EH1-CF8 2048MB SODIMM DDR3 4199MT/s            | 1         | 0.69%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 60        | 50%     |
| DDR3   | 47        | 39.17%  |
| SDRAM  | 5         | 4.17%   |
| LPDDR3 | 3         | 2.5%    |
| LPDDR4 | 2         | 1.67%   |
| DDR    | 2         | 1.67%   |
| DDR2   | 1         | 0.83%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 85        | 73.28%  |
| DIMM         | 25        | 21.55%  |
| Row Of Chips | 5         | 4.31%   |
| FB-DIMM      | 1         | 0.86%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 45        | 35.43%  |
| 4096  | 45        | 35.43%  |
| 16384 | 22        | 17.32%  |
| 2048  | 10        | 7.87%   |
| 32768 | 3         | 2.36%   |
| 1024  | 2         | 1.57%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 33        | 25.19%  |
| 2667    | 28        | 21.37%  |
| 3200    | 15        | 11.45%  |
| 1333    | 10        | 7.63%   |
| 2400    | 9         | 6.87%   |
| 2133    | 7         | 5.34%   |
| 1334    | 6         | 4.58%   |
| 1067    | 4         | 3.05%   |
| 4199    | 3         | 2.29%   |
| 3600    | 2         | 1.53%   |
| 1867    | 2         | 1.53%   |
| 1066    | 2         | 1.53%   |
| 667     | 2         | 1.53%   |
| Unknown | 2         | 1.53%   |
| 3733    | 1         | 0.76%   |
| 3500    | 1         | 0.76%   |
| 3266    | 1         | 0.76%   |
| 3007    | 1         | 0.76%   |
| 2134    | 1         | 0.76%   |
| 2048    | 1         | 0.76%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 33.33%  |
| Canon               | 2         | 33.33%  |
| Sharp               | 1         | 16.67%  |
| Samsung Electronics | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                       | Computers | Percent |
|-----------------------------|-----------|---------|
| Sharp AL-2030               | 1         | 16.67%  |
| Samsung M2020 Series        | 1         | 16.67%  |
| HP Deskjet 3050 J610 series | 1         | 16.67%  |
| HP DeskJet 2130 series      | 1         | 16.67%  |
| Canon TR7500 series         | 1         | 16.67%  |
| Canon MF240 Series V4       | 1         | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 50%     |
| Canon CanoScan LiDE 110 | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 31        | 22.3%   |
| Acer                                   | 14        | 10.07%  |
| Realtek Semiconductor                  | 13        | 9.35%   |
| Sunplus Innovation Technology          | 11        | 7.91%   |
| Microdia                               | 8         | 5.76%   |
| IMC Networks                           | 8         | 5.76%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 5.76%   |
| Logitech                               | 7         | 5.04%   |
| Quanta                                 | 6         | 4.32%   |
| Apple                                  | 6         | 4.32%   |
| Syntek                                 | 4         | 2.88%   |
| Silicon Motion                         | 4         | 2.88%   |
| Suyin                                  | 3         | 2.16%   |
| Lite-On Technology                     | 3         | 2.16%   |
| LG Electronics                         | 2         | 1.44%   |
| Generalplus Technology                 | 2         | 1.44%   |
| Sonix Technology                       | 1         | 0.72%   |
| Ricoh                                  | 1         | 0.72%   |
| Primax Electronics                     | 1         | 0.72%   |
| OPPO Electronics                       | 1         | 0.72%   |
| Microsoft                              | 1         | 0.72%   |
| Guillemot                              | 1         | 0.72%   |
| Cubeternet                             | 1         | 0.72%   |
| Creative Technology                    | 1         | 0.72%   |
| Alcor Micro                            | 1         | 0.72%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                            | 6         | 4.32%   |
| Chicony HD Webcam                                       | 6         | 4.32%   |
| Microdia Integrated_Webcam_HD                           | 5         | 3.6%    |
| Chicony Integrated Camera                               | 5         | 3.6%    |
| Chicony USB2.0 Camera                                   | 4         | 2.88%   |
| Sunplus Asus Webcam                                     | 3         | 2.16%   |
| Chicony HP HD Camera                                    | 3         | 2.16%   |
| Acer BisonCam,NB Pro                                    | 3         | 2.16%   |
| Acer BisonCam, NB Pro                                   | 3         | 2.16%   |
| Suyin HP Truevision HD                                  | 2         | 1.44%   |
| Sunplus HP HD Webcam [Fixed]                            | 2         | 1.44%   |
| Logitech Webcam C270                                    | 2         | 1.44%   |
| Logitech Webcam B500                                    | 2         | 1.44%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 2         | 1.44%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 2         | 1.44%   |
| IMC Networks Integrated Camera                          | 2         | 1.44%   |
| Chicony HP Wide Vision FHD Camera                       | 2         | 1.44%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 2         | 1.44%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera     | 2         | 1.44%   |
| Apple FaceTime HD Camera (Built-in)                     | 2         | 1.44%   |
| Apple Built-in iSight                                   | 2         | 1.44%   |
| Acer Integrated Camera                                  | 2         | 1.44%   |
| Acer HD Webcam                                          | 2         | 1.44%   |
| Syntek Web Cam - Asus F3SA, F9J, F9S                    | 1         | 0.72%   |
| Syntek USB2.0 Camera                                    | 1         | 0.72%   |
| Syntek Integrated Camera                                | 1         | 0.72%   |
| Syntek EasyCamera                                       | 1         | 0.72%   |
| Suyin HD WebCam                                         | 1         | 0.72%   |
| Sunplus Webcam                                          | 1         | 0.72%   |
| Sunplus MTD Camera                                      | 1         | 0.72%   |
| Sunplus Laptop_Integrated_Webcam_HD                     | 1         | 0.72%   |
| Sunplus Laptop Integrated WebCam HD                     | 1         | 0.72%   |
| Sunplus Integrated_Webcam_HD                            | 1         | 0.72%   |
| Sunplus HD 720P webcam                                  | 1         | 0.72%   |
| Sonix USB2.0 HD UVC WebCam                              | 1         | 0.72%   |
| Silicon Motion WebCam SC-13HDL12131N                    | 1         | 0.72%   |
| Silicon Motion WebCam SC-10HDD13335N                    | 1         | 0.72%   |
| Silicon Motion WebCam SC-10HDD12636N                    | 1         | 0.72%   |
| Silicon Motion Web Camera                               | 1         | 0.72%   |
| Ricoh Sony Vaio Integrated Webcam                       | 1         | 0.72%   |
| Realtek Web Camera                                      | 1         | 0.72%   |
| Realtek USB2.0 VGA UVC WebCam                           | 1         | 0.72%   |
| Realtek USB2.0 HD UVC WebCam                            | 1         | 0.72%   |
| Realtek Integrated Webcam HD                            | 1         | 0.72%   |
| Realtek Integrated Webcam                               | 1         | 0.72%   |
| Realtek HP "Truevision HD" laptop camera                | 1         | 0.72%   |
| Realtek HD WebCam                                       | 1         | 0.72%   |
| Quanta VGA WebCam                                       | 1         | 0.72%   |
| Quanta LG Webcam                                        | 1         | 0.72%   |
| Quanta Laptop_Integrated_Webcam_2HDM                    | 1         | 0.72%   |
| Quanta HP TrueVision HD Camera                          | 1         | 0.72%   |
| Quanta HP True Vision HD Camera                         | 1         | 0.72%   |
| Quanta HD User Facing                                   | 1         | 0.72%   |
| Primax HP HD Webcam [Fixed]                             | 1         | 0.72%   |
| OPPO Reno4 5G                                           | 1         | 0.72%   |
| Microsoft LifeCam HD-3000                               | 1         | 0.72%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 1         | 0.72%   |
| Microdia Laptop Integrated Webcam HD (Composite Device) | 1         | 0.72%   |
| Microdia Dell Laptop Integrated Webcam HD               | 1         | 0.72%   |
| Logitech Webcam C170                                    | 1         | 0.72%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 15        | 41.67%  |
| Validity Sensors           | 14        | 38.89%  |
| Shenzhen Goodix Technology | 3         | 8.33%   |
| LighTuning Technology      | 2         | 5.56%   |
| Elan Microelectronics      | 1         | 2.78%   |
| AuthenTec                  | 1         | 2.78%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 8         | 22.22%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 11.11%  |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 11.11%  |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 8.33%   |
| Synaptics WBDI Device                                                      | 3         | 8.33%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 8.33%   |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 5.56%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 5.56%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 2.78%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.78%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 2.78%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 2.78%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 2.78%   |
| Elan ELAN:Fingerprint                                                      | 1         | 2.78%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 2.78%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 6         | 54.55%  |
| Upek        | 3         | 27.27%  |
| Lenovo      | 1         | 9.09%   |
| Alcor Micro | 1         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 3         | 27.27%  |
| Broadcom BCM5880 Secure Applications Processor             | 3         | 27.27%  |
| Broadcom 5880                                              | 3         | 27.27%  |
| Lenovo Integrated Smart Card Reader                        | 1         | 9.09%   |
| Alcor Micro AU9540 Smartcard Reader                        | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 128       | 64.65%  |
| 1     | 53        | 26.77%  |
| 2     | 15        | 7.58%   |
| 4     | 1         | 0.51%   |
| 3     | 1         | 0.51%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 36        | 43.37%  |
| Graphics card            | 15        | 18.07%  |
| Chipcard                 | 11        | 13.25%  |
| Net/wireless             | 7         | 8.43%   |
| Communication controller | 6         | 7.23%   |
| Storage                  | 2         | 2.41%   |
| Camera                   | 2         | 2.41%   |
| Bluetooth                | 2         | 2.41%   |
| Net/ethernet             | 1         | 1.2%    |
| Card reader              | 1         | 1.2%    |

