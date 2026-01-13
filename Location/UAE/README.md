Linux in UAE - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Linux in UAE.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/UAE/Desktop/README.md) and [notebooks](/Location/UAE/Notebook/README.md).

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

Total: 526

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad P14s Gen 4 21HG... | Notebook    | [0cec4e8d9d](https://linux-hardware.org/?probe=0cec4e8d9d) | Jan 03, 2026 |
| HP            | ZBook 17 G2                 | Notebook    | [f77f25096b](https://linux-hardware.org/?probe=f77f25096b) | Jan 02, 2026 |
| ASUSTek       | N552VX                      | Notebook    | [6012f92437](https://linux-hardware.org/?probe=6012f92437) | Jan 02, 2026 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [be77a03c1c](https://linux-hardware.org/?probe=be77a03c1c) | Dec 30, 2025 |
| Valve         | Galileo                     | Notebook    | [f15e0b5bab](https://linux-hardware.org/?probe=f15e0b5bab) | Dec 16, 2025 |
| MSI           | B550-A PRO                  | Desktop     | [41ed13cba8](https://linux-hardware.org/?probe=41ed13cba8) | Dec 12, 2025 |
| ASUSTek       | PN50                        | Mini pc     | [34df6e141f](https://linux-hardware.org/?probe=34df6e141f) | Dec 07, 2025 |
| AZW           | SER9                        | Desktop     | [0d40ddcb95](https://linux-hardware.org/?probe=0d40ddcb95) | Dec 07, 2025 |
| AZW           | SER9                        | Desktop     | [ec1d9ca43e](https://linux-hardware.org/?probe=ec1d9ca43e) | Dec 07, 2025 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [6fee2371d3](https://linux-hardware.org/?probe=6fee2371d3) | Nov 26, 2025 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d7ac7f6f50](https://linux-hardware.org/?probe=d7ac7f6f50) | Nov 16, 2025 |
| Lenovo        | ThinkPad X1 Carbon 3448B... | Notebook    | [bbea4bb11c](https://linux-hardware.org/?probe=bbea4bb11c) | Nov 15, 2025 |
| HP            | 8446                        | All in one  | [1a9b934ea9](https://linux-hardware.org/?probe=1a9b934ea9) | Nov 14, 2025 |
| Unknown       | Unknown                     | Desktop     | [cf29202304](https://linux-hardware.org/?probe=cf29202304) | Nov 12, 2025 |
| Unknown       | Unknown                     | Desktop     | [ae6e69bc10](https://linux-hardware.org/?probe=ae6e69bc10) | Nov 10, 2025 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [933e823c56](https://linux-hardware.org/?probe=933e823c56) | Nov 06, 2025 |
| ASRock        | B560M-HDV                   | Desktop     | [28612ad094](https://linux-hardware.org/?probe=28612ad094) | Oct 22, 2025 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [816214c547](https://linux-hardware.org/?probe=816214c547) | Oct 19, 2025 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [4bdeb8cc0c](https://linux-hardware.org/?probe=4bdeb8cc0c) | Oct 19, 2025 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [cfdd072788](https://linux-hardware.org/?probe=cfdd072788) | Oct 19, 2025 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [79bdb88820](https://linux-hardware.org/?probe=79bdb88820) | Oct 10, 2025 |
| Lenovo        | ThinkPad T480s 20L8S6MG0... | Notebook    | [6e593b4697](https://linux-hardware.org/?probe=6e593b4697) | Oct 06, 2025 |
| Lenovo        | ThinkPad T480s 20L8S6MG0... | Notebook    | [6b3b5b029a](https://linux-hardware.org/?probe=6b3b5b029a) | Oct 06, 2025 |
| Shenzhen M... | F7BSC                       | Mini pc     | [88fb27172d](https://linux-hardware.org/?probe=88fb27172d) | Sep 22, 2025 |
| Dell          | Latitude 9450 2-in-1        | Notebook    | [e06c0fc876](https://linux-hardware.org/?probe=e06c0fc876) | Sep 12, 2025 |
| ASUSTek       | Pro WS WRX90E-SAGE SE       | Desktop     | [798282bf6f](https://linux-hardware.org/?probe=798282bf6f) | Sep 09, 2025 |
| Lenovo        | ThinkPad T470 20HD000TUS    | Notebook    | [2d52a5706b](https://linux-hardware.org/?probe=2d52a5706b) | Sep 09, 2025 |
| System76      | Pangolin                    | Notebook    | [721dd30734](https://linux-hardware.org/?probe=721dd30734) | Aug 29, 2025 |
| TUXEDO        | Stellaris 16 Intel Gen7     | Notebook    | [020766f6ad](https://linux-hardware.org/?probe=020766f6ad) | Aug 28, 2025 |
| Dell          | XPS 15 9560                 | Notebook    | [b829688f84](https://linux-hardware.org/?probe=b829688f84) | Aug 22, 2025 |
| MSI           | PRO B550M-P GEN3            | Desktop     | [7b445d8b0d](https://linux-hardware.org/?probe=7b445d8b0d) | Aug 18, 2025 |
| Acer          | Aspire AL14-31P             | Notebook    | [c4886ab2ba](https://linux-hardware.org/?probe=c4886ab2ba) | Aug 12, 2025 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [0c24ef79d5](https://linux-hardware.org/?probe=0c24ef79d5) | Aug 12, 2025 |
| Dell          | Vostro 15 3530              | Notebook    | [733cdc49c7](https://linux-hardware.org/?probe=733cdc49c7) | Aug 11, 2025 |
| Acer          | Aspire AL14-31P             | Notebook    | [5e7b0363ba](https://linux-hardware.org/?probe=5e7b0363ba) | Aug 08, 2025 |
| ASRock        | B660M Pro RS                | Desktop     | [e8c7f9f220](https://linux-hardware.org/?probe=e8c7f9f220) | Jul 21, 2025 |
| Acer          | Aspire X5950                | Desktop     | [42fe54ec73](https://linux-hardware.org/?probe=42fe54ec73) | Jul 19, 2025 |
| Acer          | Aspire X5950                | Desktop     | [4d911db9ad](https://linux-hardware.org/?probe=4d911db9ad) | Jul 19, 2025 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [aede1d24ad](https://linux-hardware.org/?probe=aede1d24ad) | Jul 11, 2025 |
| Lenovo        | Legion Slim 7 16IRH8 82Y... | Notebook    | [74aa4d5413](https://linux-hardware.org/?probe=74aa4d5413) | Jul 06, 2025 |
| Lenovo        | IdeaPad 305-14IBD 80R1      | Notebook    | [c68827931f](https://linux-hardware.org/?probe=c68827931f) | Jul 06, 2025 |
| Alienware     | 17 R4                       | Notebook    | [08797d0070](https://linux-hardware.org/?probe=08797d0070) | Jun 30, 2025 |
| Lenovo        | ThinkPad P53 20QN001BUS     | Notebook    | [b2a7474030](https://linux-hardware.org/?probe=b2a7474030) | Jun 18, 2025 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [2d5e6fa2b1](https://linux-hardware.org/?probe=2d5e6fa2b1) | Jun 13, 2025 |
| Apple         | MacBookPro16,3              | Notebook    | [af0d4461e3](https://linux-hardware.org/?probe=af0d4461e3) | Jun 10, 2025 |
| Lenovo        | N22 80S6                    | Notebook    | [8d216b7ceb](https://linux-hardware.org/?probe=8d216b7ceb) | Jun 09, 2025 |
| Lenovo        | N22 80S6                    | Notebook    | [3dd05cc9e2](https://linux-hardware.org/?probe=3dd05cc9e2) | Jun 09, 2025 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [065417b27d](https://linux-hardware.org/?probe=065417b27d) | Jun 02, 2025 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [a2b775d0c3](https://linux-hardware.org/?probe=a2b775d0c3) | Jun 01, 2025 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [6ee9f26b70](https://linux-hardware.org/?probe=6ee9f26b70) | Jun 01, 2025 |
| Valve         | Galileo                     | Notebook    | [144db2f584](https://linux-hardware.org/?probe=144db2f584) | May 28, 2025 |
| Dell          | 0NRKPK A01                  | Desktop     | [11ec5164d7](https://linux-hardware.org/?probe=11ec5164d7) | May 20, 2025 |
| eOBgmB2N8p... | ROG STRIX B550-F GAMING     | Desktop     | [89c337c7d1](https://linux-hardware.org/?probe=89c337c7d1) | May 16, 2025 |
| eOBgmB2N8p... | ROG STRIX B550-F GAMING     | Desktop     | [6bb0e54fef](https://linux-hardware.org/?probe=6bb0e54fef) | May 16, 2025 |
| HP            | ProBook 450 G6              | Notebook    | [40a19ad35e](https://linux-hardware.org/?probe=40a19ad35e) | May 14, 2025 |
| ASRock        | X670E Steel Legend          | Desktop     | [96ce8fb906](https://linux-hardware.org/?probe=96ce8fb906) | May 12, 2025 |
| ASRock        | X670E Steel Legend          | Desktop     | [acc496e55b](https://linux-hardware.org/?probe=acc496e55b) | May 12, 2025 |
| Apple         | MacBookPro14,3              | Notebook    | [06aeaeb301](https://linux-hardware.org/?probe=06aeaeb301) | May 10, 2025 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [72fc35fb09](https://linux-hardware.org/?probe=72fc35fb09) | Apr 29, 2025 |
| ASUSTek       | ProArt P16 H7606WV_H7606... | Notebook    | [3ef88a9cfa](https://linux-hardware.org/?probe=3ef88a9cfa) | Apr 28, 2025 |
| ASUSTek       | ProArt P16 H7606WV_H7606... | Notebook    | [92d05ea817](https://linux-hardware.org/?probe=92d05ea817) | Apr 27, 2025 |
| ASUSTek       | ProArt P16 H7606WV_H7606... | Notebook    | [a6337d9b19](https://linux-hardware.org/?probe=a6337d9b19) | Apr 27, 2025 |
| ASUSTek       | ROG Maximus Z790 EXTREME    | Desktop     | [4bbd537539](https://linux-hardware.org/?probe=4bbd537539) | Apr 20, 2025 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [5a014f5f4b](https://linux-hardware.org/?probe=5a014f5f4b) | Apr 16, 2025 |
| Dell          | 0PPTY2 A04                  | Server      | [37d4b60135](https://linux-hardware.org/?probe=37d4b60135) | Apr 14, 2025 |
| Apple         | MacBookAir7,2               | Notebook    | [335e9140f6](https://linux-hardware.org/?probe=335e9140f6) | Apr 12, 2025 |
| GMKtec        | NucBox K6                   | Desktop     | [b02362f06b](https://linux-hardware.org/?probe=b02362f06b) | Apr 11, 2025 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [5fd3bd9368](https://linux-hardware.org/?probe=5fd3bd9368) | Apr 09, 2025 |
| Apple         | MacBookPro9,2               | Notebook    | [0d50e1a91a](https://linux-hardware.org/?probe=0d50e1a91a) | Apr 09, 2025 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [36fbf4f170](https://linux-hardware.org/?probe=36fbf4f170) | Apr 06, 2025 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [4c6474d7fa](https://linux-hardware.org/?probe=4c6474d7fa) | Apr 06, 2025 |
| HP            | 8056                        | Desktop     | [651f07870c](https://linux-hardware.org/?probe=651f07870c) | Mar 19, 2025 |
| HP            | 8056                        | Desktop     | [f5b8f1b495](https://linux-hardware.org/?probe=f5b8f1b495) | Mar 19, 2025 |
| ASUSTek       | Z97-PRO                     | Desktop     | [73a61a9147](https://linux-hardware.org/?probe=73a61a9147) | Feb 27, 2025 |
| MSI           | Z590-A PRO                  | Desktop     | [98e0cf9f2a](https://linux-hardware.org/?probe=98e0cf9f2a) | Feb 26, 2025 |
| Dell          | Vostro 5481                 | Notebook    | [3e9f62ea07](https://linux-hardware.org/?probe=3e9f62ea07) | Feb 15, 2025 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [c101c1d1d7](https://linux-hardware.org/?probe=c101c1d1d7) | Feb 10, 2025 |
| ASUSTek       | B365M-PIXIU                 | Desktop     | [bebab512c8](https://linux-hardware.org/?probe=bebab512c8) | Feb 06, 2025 |
| Gigabyte      | X870 AORUS ELITE WIFI7      | Desktop     | [647eb2f98d](https://linux-hardware.org/?probe=647eb2f98d) | Jan 27, 2025 |
| Apple         | MacBookPro12,1              | Notebook    | [e3027d4cd7](https://linux-hardware.org/?probe=e3027d4cd7) | Jan 24, 2025 |
| HP            | Elite x2 1012 G2            | Tablet      | [46c90a5832](https://linux-hardware.org/?probe=46c90a5832) | Jan 22, 2025 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [4e8fdc5a01](https://linux-hardware.org/?probe=4e8fdc5a01) | Jan 08, 2025 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [c808e2833f](https://linux-hardware.org/?probe=c808e2833f) | Jan 07, 2025 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [47b95e50dc](https://linux-hardware.org/?probe=47b95e50dc) | Jan 02, 2025 |
| Intel         | DH61WW AAG23116-302         | Desktop     | [d5dae00d07](https://linux-hardware.org/?probe=d5dae00d07) | Dec 31, 2024 |
| Trigkey       | Green G4 10                 | Desktop     | [abe47751df](https://linux-hardware.org/?probe=abe47751df) | Dec 19, 2024 |
| HP            | 81C5 MVB                    | Desktop     | [598ed0a0e1](https://linux-hardware.org/?probe=598ed0a0e1) | Dec 19, 2024 |
| HP            | Pavilion Laptop 15-eh3xx... | Notebook    | [2b58ebfebe](https://linux-hardware.org/?probe=2b58ebfebe) | Dec 16, 2024 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [64f23b9876](https://linux-hardware.org/?probe=64f23b9876) | Dec 10, 2024 |
| Valve         | Jupiter                     | Notebook    | [b81aceb033](https://linux-hardware.org/?probe=b81aceb033) | Dec 09, 2024 |
| Acer          | TravelMate Spin B118-G2-... | Convertible | [83d6d9d602](https://linux-hardware.org/?probe=83d6d9d602) | Dec 05, 2024 |
| Dell          | XPS 13 9305                 | Notebook    | [1496432b74](https://linux-hardware.org/?probe=1496432b74) | Dec 04, 2024 |
| HP            | Pavilion Laptop 15-eh3xx... | Notebook    | [ed79db6569](https://linux-hardware.org/?probe=ed79db6569) | Nov 27, 2024 |
| Lenovo        | ThinkPad E16 Gen 2 21MA0... | Notebook    | [fa8c5128c6](https://linux-hardware.org/?probe=fa8c5128c6) | Nov 25, 2024 |
| Alienware     | 17 R3                       | Notebook    | [d6363a7652](https://linux-hardware.org/?probe=d6363a7652) | Nov 24, 2024 |
| Valve         | Jupiter                     | Notebook    | [01d5857ef9](https://linux-hardware.org/?probe=01d5857ef9) | Nov 22, 2024 |
| Valve         | Jupiter                     | Notebook    | [228a34d78e](https://linux-hardware.org/?probe=228a34d78e) | Nov 21, 2024 |
| Valve         | Jupiter                     | Notebook    | [fc95853dd8](https://linux-hardware.org/?probe=fc95853dd8) | Nov 19, 2024 |
| Apple         | Mac-F2218FC8                | All in one  | [962eef9779](https://linux-hardware.org/?probe=962eef9779) | Nov 12, 2024 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [364e24bd93](https://linux-hardware.org/?probe=364e24bd93) | Nov 12, 2024 |
| Apple         | Mac-F2218FC8                | All in one  | [c9ef441418](https://linux-hardware.org/?probe=c9ef441418) | Nov 11, 2024 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [32ae84417a](https://linux-hardware.org/?probe=32ae84417a) | Nov 11, 2024 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [a78f5dd558](https://linux-hardware.org/?probe=a78f5dd558) | Nov 11, 2024 |
| HP            | ProBook 450 G6              | Notebook    | [3d3f18fab8](https://linux-hardware.org/?probe=3d3f18fab8) | Nov 06, 2024 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [9093f85751](https://linux-hardware.org/?probe=9093f85751) | Nov 05, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [c36723680e](https://linux-hardware.org/?probe=c36723680e) | Nov 04, 2024 |
| HP            | ProBook 450 G6              | Notebook    | [b6327b1771](https://linux-hardware.org/?probe=b6327b1771) | Oct 27, 2024 |
| Alienware     | x17 R2                      | Notebook    | [ead78bb072](https://linux-hardware.org/?probe=ead78bb072) | Oct 24, 2024 |
| Alienware     | x17 R2                      | Notebook    | [9e6b5acd94](https://linux-hardware.org/?probe=9e6b5acd94) | Oct 22, 2024 |
| Valve         | Jupiter                     | Notebook    | [b40269dd83](https://linux-hardware.org/?probe=b40269dd83) | Oct 22, 2024 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [c31e6ce172](https://linux-hardware.org/?probe=c31e6ce172) | Oct 20, 2024 |
| MSI           | PRO Z790-S WIFI             | Desktop     | [067881f9af](https://linux-hardware.org/?probe=067881f9af) | Oct 16, 2024 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [5de475d8be](https://linux-hardware.org/?probe=5de475d8be) | Oct 08, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [4d89b5ebcb](https://linux-hardware.org/?probe=4d89b5ebcb) | Oct 08, 2024 |
| HP            | Laptop 15-dy5xxx            | Notebook    | [0e2f27c078](https://linux-hardware.org/?probe=0e2f27c078) | Oct 08, 2024 |
| HP            | Laptop 15-dy5xxx            | Notebook    | [8253f323a0](https://linux-hardware.org/?probe=8253f323a0) | Oct 07, 2024 |
| HP            | Laptop 15-dy5xxx            | Notebook    | [6273853b03](https://linux-hardware.org/?probe=6273853b03) | Oct 07, 2024 |
| Valve         | Jupiter                     | Notebook    | [98801dba2b](https://linux-hardware.org/?probe=98801dba2b) | Oct 04, 2024 |
| Valve         | Jupiter                     | Notebook    | [f72decd0b9](https://linux-hardware.org/?probe=f72decd0b9) | Oct 02, 2024 |
| Dell          | Latitude E5470              | Notebook    | [77e0c3eadc](https://linux-hardware.org/?probe=77e0c3eadc) | Sep 29, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [f267e0be7a](https://linux-hardware.org/?probe=f267e0be7a) | Sep 29, 2024 |
| ASUSTek       | Pro WS WRX90E-SAGE SE       | Desktop     | [31f821497b](https://linux-hardware.org/?probe=31f821497b) | Sep 27, 2024 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [61b7158fe5](https://linux-hardware.org/?probe=61b7158fe5) | Sep 23, 2024 |
| ASUSTek       | X541UJ                      | Notebook    | [cc2936a90c](https://linux-hardware.org/?probe=cc2936a90c) | Sep 22, 2024 |
| Dell          | Latitude E5470              | Notebook    | [b03d8fc762](https://linux-hardware.org/?probe=b03d8fc762) | Sep 15, 2024 |
| Dell          | Latitude E6540              | Notebook    | [1181675540](https://linux-hardware.org/?probe=1181675540) | Sep 14, 2024 |
| Neousys Te... | NVS-6108 Rev. A1            | Server      | [7414e2296d](https://linux-hardware.org/?probe=7414e2296d) | Sep 11, 2024 |
| Lenovo        | Legion Go 8APU1 83E1        | Tablet      | [4adc2f2b9b](https://linux-hardware.org/?probe=4adc2f2b9b) | Sep 08, 2024 |
| MSI           | Creator Z16 A11UE           | Notebook    | [146049daab](https://linux-hardware.org/?probe=146049daab) | Sep 01, 2024 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [381d377e54](https://linux-hardware.org/?probe=381d377e54) | Aug 30, 2024 |
| HP            | ENVY 15                     | Notebook    | [bb6e6b46f0](https://linux-hardware.org/?probe=bb6e6b46f0) | Aug 29, 2024 |
| ASUSTek       | ASUS Zenbook S 16 UM5606... | Notebook    | [c62daa5e9a](https://linux-hardware.org/?probe=c62daa5e9a) | Aug 28, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [4627f152d7](https://linux-hardware.org/?probe=4627f152d7) | Aug 22, 2024 |
| Lenovo        | ThinkPad T440p 20AWA02M0... | Notebook    | [37adaec870](https://linux-hardware.org/?probe=37adaec870) | Aug 19, 2024 |
| Apple         | MacBookPro14,3              | Notebook    | [9553d16dbc](https://linux-hardware.org/?probe=9553d16dbc) | Aug 18, 2024 |
| Lenovo        | Legion Slim 7 16IRH8 82Y... | Notebook    | [adbf48a938](https://linux-hardware.org/?probe=adbf48a938) | Aug 14, 2024 |
| Lenovo        | ThinkPad T540p 20BE00AXA... | Notebook    | [c87a2a98f7](https://linux-hardware.org/?probe=c87a2a98f7) | Aug 13, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [ac95e09d3d](https://linux-hardware.org/?probe=ac95e09d3d) | Aug 13, 2024 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [c9c6d489a1](https://linux-hardware.org/?probe=c9c6d489a1) | Aug 07, 2024 |
| Valve         | Jupiter                     | Notebook    | [8908b97b57](https://linux-hardware.org/?probe=8908b97b57) | Aug 05, 2024 |
| Lenovo        | ThinkPad T480 20L6S4KR00    | Notebook    | [124704efaa](https://linux-hardware.org/?probe=124704efaa) | Aug 03, 2024 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [1c41f0d25c](https://linux-hardware.org/?probe=1c41f0d25c) | Jul 28, 2024 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [8c28e82d86](https://linux-hardware.org/?probe=8c28e82d86) | Jul 28, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [100dfc761e](https://linux-hardware.org/?probe=100dfc761e) | Jul 28, 2024 |
| Lenovo        | ThinkPad T490 20N3SCND00    | Notebook    | [d366cdfef1](https://linux-hardware.org/?probe=d366cdfef1) | Jul 26, 2024 |
| Lenovo        | ThinkPad T490 20N3SCND00    | Notebook    | [5d9ee468e3](https://linux-hardware.org/?probe=5d9ee468e3) | Jul 26, 2024 |
| Lenovo        | C320                        | All in one  | [d03627f2dd](https://linux-hardware.org/?probe=d03627f2dd) | Jul 25, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [b43115fc35](https://linux-hardware.org/?probe=b43115fc35) | Jul 25, 2024 |
| Win Elemen... | S500+                       | Desktop     | [3aa986ddc3](https://linux-hardware.org/?probe=3aa986ddc3) | Jul 24, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [d322eab289](https://linux-hardware.org/?probe=d322eab289) | Jul 23, 2024 |
| Pegatron      | 2AB6                        | Desktop     | [0671cbc932](https://linux-hardware.org/?probe=0671cbc932) | Jul 14, 2024 |
| Lenovo        | C320                        | All in one  | [5a7c44d636](https://linux-hardware.org/?probe=5a7c44d636) | Jul 13, 2024 |
| ASUSTek       | Rampage IV BLACK EDITION    | Desktop     | [0456096b3c](https://linux-hardware.org/?probe=0456096b3c) | Jul 13, 2024 |
| Unknown       | OnePlus 6                   | Soc         | [3af4c7e44b](https://linux-hardware.org/?probe=3af4c7e44b) | Jul 13, 2024 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [e7b913d07d](https://linux-hardware.org/?probe=e7b913d07d) | Jul 08, 2024 |
| Dell          | 0T656F A01                  | Desktop     | [ecdd487673](https://linux-hardware.org/?probe=ecdd487673) | Jul 05, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [43eb169014](https://linux-hardware.org/?probe=43eb169014) | Jul 02, 2024 |
| Samsung       | 950QDB                      | Convertible | [9be770e082](https://linux-hardware.org/?probe=9be770e082) | Jun 28, 2024 |
| MSI           | MAG Z790 TOMAHAWK WIFI D... | Desktop     | [ac4cddaec8](https://linux-hardware.org/?probe=ac4cddaec8) | Jun 22, 2024 |
| ASUSTek       | ROG Strix G512LW_2nd2LW     | Notebook    | [c29d8bf39f](https://linux-hardware.org/?probe=c29d8bf39f) | Jun 19, 2024 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [3e62aea70e](https://linux-hardware.org/?probe=3e62aea70e) | Jun 17, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3595b48d6f](https://linux-hardware.org/?probe=3595b48d6f) | Jun 17, 2024 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [4a0a5de54c](https://linux-hardware.org/?probe=4a0a5de54c) | Jun 15, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [9b30ebc629](https://linux-hardware.org/?probe=9b30ebc629) | Jun 15, 2024 |
| Dell          | Latitude E5570              | Notebook    | [aa3048d0b3](https://linux-hardware.org/?probe=aa3048d0b3) | Jun 13, 2024 |
| Dell          | XPS L501X                   | Notebook    | [396ec3b48f](https://linux-hardware.org/?probe=396ec3b48f) | Jun 13, 2024 |
| Dell          | Vostro 3400                 | Notebook    | [2ae5830f06](https://linux-hardware.org/?probe=2ae5830f06) | Jun 05, 2024 |
| MSI           | Z390-A PRO                  | Desktop     | [12de7f6310](https://linux-hardware.org/?probe=12de7f6310) | Jun 04, 2024 |
| SZMZ          | B75-MS V1.0                 | Desktop     | [8465c076a5](https://linux-hardware.org/?probe=8465c076a5) | Jun 02, 2024 |
| Lenovo        | ThinkPad T460 20FMS77B0D    | Notebook    | [48b925a3b1](https://linux-hardware.org/?probe=48b925a3b1) | Jun 02, 2024 |
| Dell          | Latitude E6540              | Notebook    | [64a38f3167](https://linux-hardware.org/?probe=64a38f3167) | Jun 01, 2024 |
| Lenovo        | ThinkPad X13 Gen 1 20T20... | Notebook    | [ceb3eb9275](https://linux-hardware.org/?probe=ceb3eb9275) | May 31, 2024 |
| Dell          | XPS 15 9520                 | Notebook    | [dec3f4b80d](https://linux-hardware.org/?probe=dec3f4b80d) | May 30, 2024 |
| Lenovo        | ThinkPad X240 20AMS39F0E    | Notebook    | [8c697fb84c](https://linux-hardware.org/?probe=8c697fb84c) | May 28, 2024 |
| Microsoft     | Surface Pro 4               | Tablet      | [7b942d00c3](https://linux-hardware.org/?probe=7b942d00c3) | May 26, 2024 |
| Microsoft     | Surface Pro 4               | Tablet      | [4e8bf013a2](https://linux-hardware.org/?probe=4e8bf013a2) | May 26, 2024 |
| Dell          | Latitude E6540              | Notebook    | [b74e867eb2](https://linux-hardware.org/?probe=b74e867eb2) | May 25, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [9d438abd6e](https://linux-hardware.org/?probe=9d438abd6e) | May 24, 2024 |
| HP            | ProBook 430 G4              | Notebook    | [986474f731](https://linux-hardware.org/?probe=986474f731) | May 21, 2024 |
| Acer          | Aspire ES1-531              | Notebook    | [3387f387e2](https://linux-hardware.org/?probe=3387f387e2) | May 19, 2024 |
| Acer          | Aspire ES1-531              | Notebook    | [b7158b3151](https://linux-hardware.org/?probe=b7158b3151) | May 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [5ecbd0cbbc](https://linux-hardware.org/?probe=5ecbd0cbbc) | May 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [fac2c941b9](https://linux-hardware.org/?probe=fac2c941b9) | May 17, 2024 |
| MSI           | Alpha 15 A4DEK              | Notebook    | [df01e00ae4](https://linux-hardware.org/?probe=df01e00ae4) | May 17, 2024 |
| Nvidia        | Tegra                       | Soc         | [31fafc00d1](https://linux-hardware.org/?probe=31fafc00d1) | May 15, 2024 |
| Nvidia        | Tegra                       | Soc         | [13eace5813](https://linux-hardware.org/?probe=13eace5813) | May 15, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [375e987cd3](https://linux-hardware.org/?probe=375e987cd3) | May 14, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [815681c523](https://linux-hardware.org/?probe=815681c523) | May 14, 2024 |
| Dell          | XPS 15 9520                 | Notebook    | [ef8de4b0d9](https://linux-hardware.org/?probe=ef8de4b0d9) | May 09, 2024 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [e475e36ab0](https://linux-hardware.org/?probe=e475e36ab0) | May 06, 2024 |
| HP            | HPPavilionLaptop15-eh0xx... | Notebook    | [2d309668c0](https://linux-hardware.org/?probe=2d309668c0) | May 04, 2024 |
| AZW           | SER V10                     | Mini pc     | [3c76958b8b](https://linux-hardware.org/?probe=3c76958b8b) | Apr 24, 2024 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [c12789125b](https://linux-hardware.org/?probe=c12789125b) | Apr 24, 2024 |
| Dell          | Vostro 3400                 | Notebook    | [ddb98658ed](https://linux-hardware.org/?probe=ddb98658ed) | Apr 15, 2024 |
| Valve         | Jupiter                     | Notebook    | [3f58323ccb](https://linux-hardware.org/?probe=3f58323ccb) | Apr 02, 2024 |
| Lenovo        | ThinkPad T480s 20L8S07A0... | Notebook    | [b136c2a573](https://linux-hardware.org/?probe=b136c2a573) | Mar 26, 2024 |
| Dell          | Inspiron 16 Plus 7620       | Notebook    | [16c311a8b2](https://linux-hardware.org/?probe=16c311a8b2) | Mar 13, 2024 |
| ASRock        | B660M-HDV                   | Desktop     | [427836e454](https://linux-hardware.org/?probe=427836e454) | Mar 02, 2024 |
| ASRock        | B660M-HDV                   | Desktop     | [68b50166f3](https://linux-hardware.org/?probe=68b50166f3) | Mar 02, 2024 |
| HUAWEI        | DRR-WXX                     | Tablet      | [8797322d65](https://linux-hardware.org/?probe=8797322d65) | Mar 02, 2024 |
| Intel         | NUC11TNBi7 M11895-403       | Mini pc     | [6bc129fa19](https://linux-hardware.org/?probe=6bc129fa19) | Feb 27, 2024 |
| Lenovo        | ThinkPad X240 20AMS39F0E    | Notebook    | [28e62d76d4](https://linux-hardware.org/?probe=28e62d76d4) | Feb 25, 2024 |
| Lenovo        | ThinkPad P50 20EN002WAD     | Notebook    | [19f5064a8e](https://linux-hardware.org/?probe=19f5064a8e) | Feb 24, 2024 |
| Lenovo        | ThinkPad P50 20EN002WAD     | Notebook    | [d6e9ae9de6](https://linux-hardware.org/?probe=d6e9ae9de6) | Feb 24, 2024 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [65d3a89e4e](https://linux-hardware.org/?probe=65d3a89e4e) | Feb 23, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [82828b68cb](https://linux-hardware.org/?probe=82828b68cb) | Feb 20, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [813c2cba09](https://linux-hardware.org/?probe=813c2cba09) | Feb 17, 2024 |
| Lenovo        | ThinkPad E14 20RA007TUE     | Notebook    | [84059a6773](https://linux-hardware.org/?probe=84059a6773) | Feb 16, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [95e1c6903c](https://linux-hardware.org/?probe=95e1c6903c) | Feb 16, 2024 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [6637baf0a5](https://linux-hardware.org/?probe=6637baf0a5) | Feb 14, 2024 |
| Valve         | Jupiter                     | Notebook    | [4bfb818f2f](https://linux-hardware.org/?probe=4bfb818f2f) | Feb 12, 2024 |
| Lenovo        | ThinkPad E570 20H50067AD    | Notebook    | [a51f602de8](https://linux-hardware.org/?probe=a51f602de8) | Feb 11, 2024 |
| Lenovo        | ThinkPad E570 20H50067AD    | Notebook    | [2752e93d4b](https://linux-hardware.org/?probe=2752e93d4b) | Feb 08, 2024 |
| ASUSTek       | ZenBook UX482EAR_UX482EA... | Notebook    | [4c292546e2](https://linux-hardware.org/?probe=4c292546e2) | Jan 27, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [3de8476f0b](https://linux-hardware.org/?probe=3de8476f0b) | Jan 21, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [3373e374fb](https://linux-hardware.org/?probe=3373e374fb) | Jan 14, 2024 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [3ea676a743](https://linux-hardware.org/?probe=3ea676a743) | Jan 14, 2024 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [e3c1908003](https://linux-hardware.org/?probe=e3c1908003) | Jan 13, 2024 |
| Dell          | XPS 13 9305                 | Notebook    | [382558433d](https://linux-hardware.org/?probe=382558433d) | Jan 11, 2024 |
| Apple         | MacBookAir5,1               | Notebook    | [26c37b7e05](https://linux-hardware.org/?probe=26c37b7e05) | Jan 02, 2024 |
| Apple         | MacBookAir5,1               | Notebook    | [5c7029f981](https://linux-hardware.org/?probe=5c7029f981) | Dec 23, 2023 |
| Lenovo        | ThinkPad T440p 20AWA02M0... | Notebook    | [c977bbe2c4](https://linux-hardware.org/?probe=c977bbe2c4) | Dec 03, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [91df918363](https://linux-hardware.org/?probe=91df918363) | Nov 28, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [e22c72e9d4](https://linux-hardware.org/?probe=e22c72e9d4) | Nov 26, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [dfa296fd96](https://linux-hardware.org/?probe=dfa296fd96) | Nov 25, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [9218c25c70](https://linux-hardware.org/?probe=9218c25c70) | Nov 21, 2023 |
| ASUSTek       | ROG STRIX Z490-A GAMING     | Desktop     | [340f007a69](https://linux-hardware.org/?probe=340f007a69) | Nov 14, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [9c08dba7b5](https://linux-hardware.org/?probe=9c08dba7b5) | Nov 13, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [e384b513f0](https://linux-hardware.org/?probe=e384b513f0) | Nov 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [e7f5173a86](https://linux-hardware.org/?probe=e7f5173a86) | Nov 12, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [0d5d11180c](https://linux-hardware.org/?probe=0d5d11180c) | Nov 07, 2023 |
| Toshiba       | PORTEGE Z10t-A              | Notebook    | [600445b726](https://linux-hardware.org/?probe=600445b726) | Nov 05, 2023 |
| HP            | HPPavilionLaptop15-eh0xx... | Notebook    | [436064bfba](https://linux-hardware.org/?probe=436064bfba) | Nov 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [92ed6d25c3](https://linux-hardware.org/?probe=92ed6d25c3) | Nov 05, 2023 |
| Toshiba       | Satellite L750              | Notebook    | [f4cbcd5ba1](https://linux-hardware.org/?probe=f4cbcd5ba1) | Nov 05, 2023 |
| Toshiba       | Satellite L750              | Notebook    | [34a347877f](https://linux-hardware.org/?probe=34a347877f) | Nov 05, 2023 |
| HP            | 1589                        | Desktop     | [61922d4b43](https://linux-hardware.org/?probe=61922d4b43) | Nov 05, 2023 |
| Gigabyte      | A5 X1                       | Notebook    | [981be88a61](https://linux-hardware.org/?probe=981be88a61) | Oct 30, 2023 |
| Lenovo        | ThinkPad E490 20N80006UE    | Notebook    | [4bb8e497d3](https://linux-hardware.org/?probe=4bb8e497d3) | Oct 28, 2023 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [2937846c1b](https://linux-hardware.org/?probe=2937846c1b) | Oct 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [8678e7aace](https://linux-hardware.org/?probe=8678e7aace) | Oct 08, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [e6e1c9bac9](https://linux-hardware.org/?probe=e6e1c9bac9) | Sep 30, 2023 |
| I-Life Dig... | ZED AIR PRO                 | Notebook    | [7cb30879f6](https://linux-hardware.org/?probe=7cb30879f6) | Sep 28, 2023 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | Notebook    | [64a85b8eb3](https://linux-hardware.org/?probe=64a85b8eb3) | Sep 28, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [17bbb23241](https://linux-hardware.org/?probe=17bbb23241) | Sep 22, 2023 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [89bf6e640b](https://linux-hardware.org/?probe=89bf6e640b) | Sep 12, 2023 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [7f0de230c8](https://linux-hardware.org/?probe=7f0de230c8) | Sep 12, 2023 |
| Google        | Lick                        | Notebook    | [11aec9d97c](https://linux-hardware.org/?probe=11aec9d97c) | Sep 03, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [53b237137d](https://linux-hardware.org/?probe=53b237137d) | Aug 30, 2023 |
| HP            | 8446                        | All in one  | [9d508328d5](https://linux-hardware.org/?probe=9d508328d5) | Aug 19, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [0585143fdc](https://linux-hardware.org/?probe=0585143fdc) | Aug 19, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [de0ce7c424](https://linux-hardware.org/?probe=de0ce7c424) | Aug 06, 2023 |
| Dell          | Latitude 3420               | Notebook    | [cdecb64c4a](https://linux-hardware.org/?probe=cdecb64c4a) | Aug 04, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [c741db51a0](https://linux-hardware.org/?probe=c741db51a0) | Aug 03, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [18eceddda0](https://linux-hardware.org/?probe=18eceddda0) | Jul 26, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [3466d6ab26](https://linux-hardware.org/?probe=3466d6ab26) | Jul 23, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [94df828438](https://linux-hardware.org/?probe=94df828438) | Jul 22, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3539141ba9](https://linux-hardware.org/?probe=3539141ba9) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | Desktop     | [0c592730d7](https://linux-hardware.org/?probe=0c592730d7) | Jul 16, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [9b3b477b44](https://linux-hardware.org/?probe=9b3b477b44) | Jul 11, 2023 |
| ASRock        | E3C224D4I-14S               | Desktop     | [bd2d074d07](https://linux-hardware.org/?probe=bd2d074d07) | Jul 09, 2023 |
| Dell          | G15 Special Edition 5521    | Notebook    | [42890cd134](https://linux-hardware.org/?probe=42890cd134) | Jul 04, 2023 |
| Dell          | G15 Special Edition 5521    | Notebook    | [8a3a0f9375](https://linux-hardware.org/?probe=8a3a0f9375) | Jul 04, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [884a5ecd03](https://linux-hardware.org/?probe=884a5ecd03) | Jun 28, 2023 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [7f41e23d3a](https://linux-hardware.org/?probe=7f41e23d3a) | Jun 23, 2023 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [79ec1a7b3f](https://linux-hardware.org/?probe=79ec1a7b3f) | Jun 23, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [53ef3811fc](https://linux-hardware.org/?probe=53ef3811fc) | Jun 21, 2023 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [7dd15a9fa4](https://linux-hardware.org/?probe=7dd15a9fa4) | Jun 19, 2023 |
| Intel         | NUC9VXQNB K47179-402        | Mini pc     | [f3c7611dd0](https://linux-hardware.org/?probe=f3c7611dd0) | Jun 17, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [75eeeb7917](https://linux-hardware.org/?probe=75eeeb7917) | Jun 16, 2023 |
| Lenovo        | Yoga Creator 7 15IMH05 8... | Notebook    | [3bcc239452](https://linux-hardware.org/?probe=3bcc239452) | Jun 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [0c81d929ca](https://linux-hardware.org/?probe=0c81d929ca) | Jun 04, 2023 |
| HP            | 0B54h D                     | Desktop     | [f9634b51b9](https://linux-hardware.org/?probe=f9634b51b9) | May 28, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [589112cb44](https://linux-hardware.org/?probe=589112cb44) | May 25, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [2ae74516a9](https://linux-hardware.org/?probe=2ae74516a9) | May 24, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [cbd7b1dcc7](https://linux-hardware.org/?probe=cbd7b1dcc7) | May 24, 2023 |
| Lenovo        | ThinkPad T490 20N2004JAD    | Notebook    | [c765eed46d](https://linux-hardware.org/?probe=c765eed46d) | May 16, 2023 |
| Toshiba       | Satellite L850-B434         | Notebook    | [54e6cd2fc6](https://linux-hardware.org/?probe=54e6cd2fc6) | May 13, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [89747b6213](https://linux-hardware.org/?probe=89747b6213) | May 12, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [0a639ba55d](https://linux-hardware.org/?probe=0a639ba55d) | May 08, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [aabb19e388](https://linux-hardware.org/?probe=aabb19e388) | May 06, 2023 |
| Lenovo        | ThinkPad Yoga 11e 4th Ge... | Convertible | [b9ef1562db](https://linux-hardware.org/?probe=b9ef1562db) | May 05, 2023 |
| Lenovo        | ThinkPad Yoga 11e 4th Ge... | Convertible | [02fa09745c](https://linux-hardware.org/?probe=02fa09745c) | May 05, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [856494ea85](https://linux-hardware.org/?probe=856494ea85) | May 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [c6e5e310b9](https://linux-hardware.org/?probe=c6e5e310b9) | May 02, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [1704454cdb](https://linux-hardware.org/?probe=1704454cdb) | May 02, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [d2f8737b9d](https://linux-hardware.org/?probe=d2f8737b9d) | May 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [78a3abdc19](https://linux-hardware.org/?probe=78a3abdc19) | Apr 25, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [59c225df6e](https://linux-hardware.org/?probe=59c225df6e) | Apr 24, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [6e2da1e766](https://linux-hardware.org/?probe=6e2da1e766) | Apr 21, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [00ed2824f0](https://linux-hardware.org/?probe=00ed2824f0) | Apr 20, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [7a4242a973](https://linux-hardware.org/?probe=7a4242a973) | Apr 19, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [a0cf4fd00d](https://linux-hardware.org/?probe=a0cf4fd00d) | Apr 19, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [7ce26d7fd9](https://linux-hardware.org/?probe=7ce26d7fd9) | Apr 19, 2023 |
| HP            | Pavilion 15                 | Notebook    | [d0c3e2bb4e](https://linux-hardware.org/?probe=d0c3e2bb4e) | Apr 19, 2023 |
| HP            | 15-dc1018ur                 | Notebook    | [7df35a90ad](https://linux-hardware.org/?probe=7df35a90ad) | Apr 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [a7b2caaba8](https://linux-hardware.org/?probe=a7b2caaba8) | Apr 16, 2023 |
| HP            | Pavilion 15                 | Notebook    | [199f3bb771](https://linux-hardware.org/?probe=199f3bb771) | Apr 14, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [59db7a4f11](https://linux-hardware.org/?probe=59db7a4f11) | Apr 10, 2023 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [125884d17a](https://linux-hardware.org/?probe=125884d17a) | Apr 05, 2023 |
| Lenovo        | ThinkPad T460s 20FAS1U20... | Notebook    | [99ea485cee](https://linux-hardware.org/?probe=99ea485cee) | Mar 27, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [83fb0eaf6e](https://linux-hardware.org/?probe=83fb0eaf6e) | Mar 26, 2023 |
| ASUSTek       | Q551LN                      | Notebook    | [3385f39150](https://linux-hardware.org/?probe=3385f39150) | Mar 26, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [1a46276700](https://linux-hardware.org/?probe=1a46276700) | Mar 05, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [2a8830034a](https://linux-hardware.org/?probe=2a8830034a) | Feb 26, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [452bd46c01](https://linux-hardware.org/?probe=452bd46c01) | Feb 22, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [fe78ef8424](https://linux-hardware.org/?probe=fe78ef8424) | Feb 22, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [83bef528a7](https://linux-hardware.org/?probe=83bef528a7) | Feb 19, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [64c385ee36](https://linux-hardware.org/?probe=64c385ee36) | Feb 16, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [54f7f241bf](https://linux-hardware.org/?probe=54f7f241bf) | Feb 15, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [8fc284c3b5](https://linux-hardware.org/?probe=8fc284c3b5) | Feb 15, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [3b09c5ed9e](https://linux-hardware.org/?probe=3b09c5ed9e) | Feb 04, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [be3ef90301](https://linux-hardware.org/?probe=be3ef90301) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [9fb41ee5bc](https://linux-hardware.org/?probe=9fb41ee5bc) | Feb 01, 2023 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | Notebook    | [a64ae29757](https://linux-hardware.org/?probe=a64ae29757) | Jan 31, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [f308688189](https://linux-hardware.org/?probe=f308688189) | Jan 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [83d050bdbe](https://linux-hardware.org/?probe=83d050bdbe) | Jan 25, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [9a930173a0](https://linux-hardware.org/?probe=9a930173a0) | Jan 24, 2023 |
| HP            | 1998                        | Desktop     | [5fcedbdb28](https://linux-hardware.org/?probe=5fcedbdb28) | Jan 22, 2023 |
| Dell          | G5 5587                     | Notebook    | [96ca22c550](https://linux-hardware.org/?probe=96ca22c550) | Jan 21, 2023 |
| Dell          | G5 5587                     | Notebook    | [a070a8ba69](https://linux-hardware.org/?probe=a070a8ba69) | Jan 21, 2023 |
| Acer          | Aspire E5-471P              | Notebook    | [c50e807e64](https://linux-hardware.org/?probe=c50e807e64) | Jan 12, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | Notebook    | [6d3966411f](https://linux-hardware.org/?probe=6d3966411f) | Jan 09, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | Notebook    | [1405e2a7c8](https://linux-hardware.org/?probe=1405e2a7c8) | Jan 09, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | Notebook    | [6206409322](https://linux-hardware.org/?probe=6206409322) | Jan 08, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [eab8778810](https://linux-hardware.org/?probe=eab8778810) | Dec 30, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [89c0ffe36d](https://linux-hardware.org/?probe=89c0ffe36d) | Dec 29, 2022 |
| Lenovo        | Legion Y7000P 81LD          | Notebook    | [d27a1b703b](https://linux-hardware.org/?probe=d27a1b703b) | Dec 26, 2022 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | Desktop     | [f048f7fcdb](https://linux-hardware.org/?probe=f048f7fcdb) | Dec 16, 2022 |
| AZW           | GTR V01                     | Mini pc     | [9f1097843c](https://linux-hardware.org/?probe=9f1097843c) | Dec 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [fae62b5114](https://linux-hardware.org/?probe=fae62b5114) | Dec 11, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [c74d870263](https://linux-hardware.org/?probe=c74d870263) | Dec 04, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [8277ece293](https://linux-hardware.org/?probe=8277ece293) | Nov 30, 2022 |
| Dell          | 0F9N89 A00                  | Server      | [3a917876ba](https://linux-hardware.org/?probe=3a917876ba) | Nov 23, 2022 |
| Gigabyte      | EP45T-UD3R                  | Desktop     | [79119cca36](https://linux-hardware.org/?probe=79119cca36) | Nov 19, 2022 |
| Gigabyte      | EP45T-UD3R                  | Desktop     | [1b30c252bb](https://linux-hardware.org/?probe=1b30c252bb) | Nov 19, 2022 |
| HP            | 0AECh D                     | Desktop     | [9e2ddc5dbd](https://linux-hardware.org/?probe=9e2ddc5dbd) | Nov 18, 2022 |
| HP            | 0AECh D                     | Desktop     | [95b36ddda4](https://linux-hardware.org/?probe=95b36ddda4) | Nov 18, 2022 |
| HP            | 1495                        | Desktop     | [c4535d8ea8](https://linux-hardware.org/?probe=c4535d8ea8) | Nov 15, 2022 |
| Gigabyte      | EP45T-UD3R                  | Desktop     | [faf014b2e6](https://linux-hardware.org/?probe=faf014b2e6) | Nov 12, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [d9af542480](https://linux-hardware.org/?probe=d9af542480) | Nov 08, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [7d3eac2c7d](https://linux-hardware.org/?probe=7d3eac2c7d) | Nov 05, 2022 |
| Gigabyte      | Q270M-D3H                   | Desktop     | [46874cc0a1](https://linux-hardware.org/?probe=46874cc0a1) | Nov 02, 2022 |
| Lenovo        | ThinkPad P1 Gen 5 21DC00... | Notebook    | [910b452558](https://linux-hardware.org/?probe=910b452558) | Oct 30, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [7406489511](https://linux-hardware.org/?probe=7406489511) | Oct 21, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [e8e0acd06e](https://linux-hardware.org/?probe=e8e0acd06e) | Oct 17, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [fdab72c478](https://linux-hardware.org/?probe=fdab72c478) | Oct 07, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [b1590cf8fa](https://linux-hardware.org/?probe=b1590cf8fa) | Oct 03, 2022 |
| Intel         | NUC10i3FNB K61362-306       | Mini pc     | [e8130be6f2](https://linux-hardware.org/?probe=e8130be6f2) | Oct 03, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [df5fcf14f9](https://linux-hardware.org/?probe=df5fcf14f9) | Sep 26, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | Notebook    | [472668e67b](https://linux-hardware.org/?probe=472668e67b) | Sep 12, 2022 |
| MSI           | Z97 PC Mate                 | Desktop     | [512c793b51](https://linux-hardware.org/?probe=512c793b51) | Sep 06, 2022 |
| Lenovo        | ThinkPad T61 76653JG        | Notebook    | [0fae1da16b](https://linux-hardware.org/?probe=0fae1da16b) | Aug 02, 2022 |
| Lenovo        | 81FV                        | Notebook    | [aa9e5c9f73](https://linux-hardware.org/?probe=aa9e5c9f73) | Jul 22, 2022 |
| Lenovo        | ThinkPad T480s 20L7001PA... | Notebook    | [de71ab8780](https://linux-hardware.org/?probe=de71ab8780) | Jul 21, 2022 |
| Intel         | NUC6i7KYB H90766-402        | Mini pc     | [b847a4a45d](https://linux-hardware.org/?probe=b847a4a45d) | Jul 03, 2022 |
| Intel         | NUC6i7KYB H90766-402        | Mini pc     | [0aa196cd0c](https://linux-hardware.org/?probe=0aa196cd0c) | Jul 03, 2022 |
| Dell          | 0MGK50 A02                  | Desktop     | [eca7a31c46](https://linux-hardware.org/?probe=eca7a31c46) | Jun 23, 2022 |
| Dell          | 0MGK50 A02                  | Desktop     | [134bf128f7](https://linux-hardware.org/?probe=134bf128f7) | Jun 23, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [0fbbdf9197](https://linux-hardware.org/?probe=0fbbdf9197) | Jun 07, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [ad2442631e](https://linux-hardware.org/?probe=ad2442631e) | May 28, 2022 |
| HP            | 8446                        | All in one  | [821752cb21](https://linux-hardware.org/?probe=821752cb21) | May 11, 2022 |
| HP            | Pavilion Laptop 13-bb0xx... | Notebook    | [ae7d5dbb0c](https://linux-hardware.org/?probe=ae7d5dbb0c) | May 01, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [6c498d2ce5](https://linux-hardware.org/?probe=6c498d2ce5) | Apr 29, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS4... | Notebook    | [28c774c6de](https://linux-hardware.org/?probe=28c774c6de) | Apr 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [718b671125](https://linux-hardware.org/?probe=718b671125) | Apr 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [5e0763131c](https://linux-hardware.org/?probe=5e0763131c) | Mar 28, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [8dda7f6478](https://linux-hardware.org/?probe=8dda7f6478) | Mar 06, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [4edc1d31b5](https://linux-hardware.org/?probe=4edc1d31b5) | Mar 06, 2022 |
| Google        | Terra                       | Notebook    | [54163369b2](https://linux-hardware.org/?probe=54163369b2) | Feb 23, 2022 |
| Dell          | 0CRH6C A02                  | Desktop     | [f014fcba4f](https://linux-hardware.org/?probe=f014fcba4f) | Feb 14, 2022 |
| Dell          | Latitude E6230              | Notebook    | [a8aeb155b0](https://linux-hardware.org/?probe=a8aeb155b0) | Feb 10, 2022 |
| Biostar       | TZ77XE4                     | Desktop     | [081c3be70e](https://linux-hardware.org/?probe=081c3be70e) | Feb 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [8aafebe07c](https://linux-hardware.org/?probe=8aafebe07c) | Feb 03, 2022 |
| Dell          | Latitude E5440              | Notebook    | [ebbb8ee138](https://linux-hardware.org/?probe=ebbb8ee138) | Jan 22, 2022 |
| Lenovo        | ThinkPad T480s 20L8S3FV0... | Notebook    | [78080db667](https://linux-hardware.org/?probe=78080db667) | Jan 13, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [4670daefab](https://linux-hardware.org/?probe=4670daefab) | Jan 04, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [c36553e3a3](https://linux-hardware.org/?probe=c36553e3a3) | Dec 27, 2021 |
| Google        | Akemi                       | Notebook    | [aaf0a3e10e](https://linux-hardware.org/?probe=aaf0a3e10e) | Dec 20, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [927497310e](https://linux-hardware.org/?probe=927497310e) | Nov 16, 2021 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [7b77d5463d](https://linux-hardware.org/?probe=7b77d5463d) | Nov 13, 2021 |
| win elemen... | MoreFine S500+              | Notebook    | [ace08cf199](https://linux-hardware.org/?probe=ace08cf199) | Nov 11, 2021 |
| win elemen... | MoreFine S500+              | Notebook    | [0e31d4b6fa](https://linux-hardware.org/?probe=0e31d4b6fa) | Nov 11, 2021 |
| MSI           | PS63 Modern 8RD             | Notebook    | [519048dea2](https://linux-hardware.org/?probe=519048dea2) | Nov 01, 2021 |
| MSI           | PS63 Modern 8RD             | Notebook    | [6d3cd2f117](https://linux-hardware.org/?probe=6d3cd2f117) | Nov 01, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FD00... | Convertible | [24d1bd52cc](https://linux-hardware.org/?probe=24d1bd52cc) | Oct 28, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [41ff21e8e8](https://linux-hardware.org/?probe=41ff21e8e8) | Oct 06, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [6654adaf99](https://linux-hardware.org/?probe=6654adaf99) | Oct 04, 2021 |
| HP            | ProBook 6475b               | Notebook    | [9d60bf5397](https://linux-hardware.org/?probe=9d60bf5397) | Oct 02, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FD00... | Convertible | [eccb23bda1](https://linux-hardware.org/?probe=eccb23bda1) | Sep 24, 2021 |
| Apple         | MacBook9,1                  | Notebook    | [888ca9b5de](https://linux-hardware.org/?probe=888ca9b5de) | Sep 04, 2021 |
| Apple         | MacBook9,1                  | Notebook    | [69119d1952](https://linux-hardware.org/?probe=69119d1952) | Sep 04, 2021 |
| ECS           | GeForce6100PM-M2            | Desktop     | [e1f91ca6de](https://linux-hardware.org/?probe=e1f91ca6de) | Sep 02, 2021 |
| HP            | 8446                        | All in one  | [430c02980a](https://linux-hardware.org/?probe=430c02980a) | Aug 13, 2021 |
| Sony          | VGN-NS10J_S                 | Notebook    | [31d1e0e91d](https://linux-hardware.org/?probe=31d1e0e91d) | Aug 12, 2021 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [e25c41c312](https://linux-hardware.org/?probe=e25c41c312) | Jul 03, 2021 |
| LG Electro... | C500-G.AEF5BE1              | Notebook    | [b78f4cd34d](https://linux-hardware.org/?probe=b78f4cd34d) | Jun 14, 2021 |
| Toshiba       | Satellite C850-A966         | Notebook    | [391d22d993](https://linux-hardware.org/?probe=391d22d993) | Jun 02, 2021 |
| Sony          | SVE14A25CAB                 | Notebook    | [78ddb916b5](https://linux-hardware.org/?probe=78ddb916b5) | May 30, 2021 |
| Sony          | SVE14A25CAB                 | Notebook    | [0a2c5cf1cd](https://linux-hardware.org/?probe=0a2c5cf1cd) | May 30, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [5707e7ae37](https://linux-hardware.org/?probe=5707e7ae37) | May 28, 2021 |
| Dell          | OptiPlex 980                | Desktop     | [1fe360b027](https://linux-hardware.org/?probe=1fe360b027) | May 26, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [66cc8bd4a5](https://linux-hardware.org/?probe=66cc8bd4a5) | May 19, 2021 |
| Dell          | G5 5587                     | Notebook    | [2d2cf67a2d](https://linux-hardware.org/?probe=2d2cf67a2d) | May 08, 2021 |
| Dell          | Latitude E6510              | Notebook    | [06d38294ab](https://linux-hardware.org/?probe=06d38294ab) | May 03, 2021 |
| Lenovo        | Legion Y7000P 81LD          | Notebook    | [e3b22a36fb](https://linux-hardware.org/?probe=e3b22a36fb) | Apr 22, 2021 |
| Lenovo        | Legion Y7000P 81LD          | Notebook    | [f5715022b7](https://linux-hardware.org/?probe=f5715022b7) | Apr 22, 2021 |
| HP            | 8446                        | All in one  | [a52aa6f1bd](https://linux-hardware.org/?probe=a52aa6f1bd) | Mar 10, 2021 |
| Acer          | Aspire 5755G                | Notebook    | [6b82d5c050](https://linux-hardware.org/?probe=6b82d5c050) | Mar 07, 2021 |
| Acer          | Aspire 5755G                | Notebook    | [227244211b](https://linux-hardware.org/?probe=227244211b) | Mar 07, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [3c9d39abce](https://linux-hardware.org/?probe=3c9d39abce) | Mar 06, 2021 |
| Lenovo        | ThinkPad X230 2325DV8       | Notebook    | [11d5145d10](https://linux-hardware.org/?probe=11d5145d10) | Feb 12, 2021 |
| HP            | Elite Dragonfly             | Convertible | [87b2f82af5](https://linux-hardware.org/?probe=87b2f82af5) | Feb 01, 2021 |
| HP            | Elite Dragonfly             | Convertible | [6e1ef1920c](https://linux-hardware.org/?probe=6e1ef1920c) | Jan 31, 2021 |
| HP            | Elite Dragonfly             | Convertible | [215ff8ccba](https://linux-hardware.org/?probe=215ff8ccba) | Jan 31, 2021 |
| HP            | Pavilion dv6                | Notebook    | [317b81878c](https://linux-hardware.org/?probe=317b81878c) | Jan 27, 2021 |
| Lenovo        | 3098 NOK                    | Desktop     | [d0ccf5266d](https://linux-hardware.org/?probe=d0ccf5266d) | Jan 27, 2021 |
| ASUSTek       | Strix GL703GM_GL703GM       | Notebook    | [3d8ea2b061](https://linux-hardware.org/?probe=3d8ea2b061) | Jan 27, 2021 |
| HP            | Laptop 15-da1xxx            | Notebook    | [a3c15a6f74](https://linux-hardware.org/?probe=a3c15a6f74) | Jan 18, 2021 |
| HP            | Laptop 15-da1xxx            | Notebook    | [58bf01b1e7](https://linux-hardware.org/?probe=58bf01b1e7) | Jan 18, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [2e84869a9a](https://linux-hardware.org/?probe=2e84869a9a) | Jan 11, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [1c5ef3cfe4](https://linux-hardware.org/?probe=1c5ef3cfe4) | Jan 11, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d071e37713](https://linux-hardware.org/?probe=d071e37713) | Jan 10, 2021 |
| HP            | 8446                        | All in one  | [a07d483bab](https://linux-hardware.org/?probe=a07d483bab) | Jan 07, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | Notebook    | [6a02570e23](https://linux-hardware.org/?probe=6a02570e23) | Jan 03, 2021 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [092666f171](https://linux-hardware.org/?probe=092666f171) | Dec 31, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [93e3d5b038](https://linux-hardware.org/?probe=93e3d5b038) | Dec 25, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [d24a3c768e](https://linux-hardware.org/?probe=d24a3c768e) | Dec 24, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [cb1c064071](https://linux-hardware.org/?probe=cb1c064071) | Dec 16, 2020 |
| Dell          | Latitude E6410              | Notebook    | [a2a46d21e9](https://linux-hardware.org/?probe=a2a46d21e9) | Dec 15, 2020 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [e2816ed19c](https://linux-hardware.org/?probe=e2816ed19c) | Nov 27, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [12a3adede5](https://linux-hardware.org/?probe=12a3adede5) | Nov 06, 2020 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [91e0e6c6bc](https://linux-hardware.org/?probe=91e0e6c6bc) | Nov 04, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [6f0218a447](https://linux-hardware.org/?probe=6f0218a447) | Oct 28, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [7ad824c6f9](https://linux-hardware.org/?probe=7ad824c6f9) | Oct 26, 2020 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [54531ec292](https://linux-hardware.org/?probe=54531ec292) | Oct 21, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f372424ac5](https://linux-hardware.org/?probe=f372424ac5) | Oct 18, 2020 |
| Intel         | D865PERL AAC27648-207       | Desktop     | [387171a87d](https://linux-hardware.org/?probe=387171a87d) | Oct 08, 2020 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [b1cd303933](https://linux-hardware.org/?probe=b1cd303933) | Oct 08, 2020 |
| HP            | 2AA2                        | Desktop     | [ceebc6a90b](https://linux-hardware.org/?probe=ceebc6a90b) | Oct 04, 2020 |
| Intel         | D865PERL AAC27648-207       | Desktop     | [7d3672caff](https://linux-hardware.org/?probe=7d3672caff) | Oct 04, 2020 |
| Intel         | D865PERL AAC27648-207       | Desktop     | [2a18eaa0ab](https://linux-hardware.org/?probe=2a18eaa0ab) | Oct 04, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [f9f212a509](https://linux-hardware.org/?probe=f9f212a509) | Oct 01, 2020 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [ab392f30cb](https://linux-hardware.org/?probe=ab392f30cb) | Sep 30, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [42c8711bea](https://linux-hardware.org/?probe=42c8711bea) | Sep 29, 2020 |
| Acer          | ChiefRiver Platform         | Notebook    | [23e2162b8e](https://linux-hardware.org/?probe=23e2162b8e) | Sep 20, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [22369a8f3c](https://linux-hardware.org/?probe=22369a8f3c) | Sep 20, 2020 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [d026d40366](https://linux-hardware.org/?probe=d026d40366) | Sep 17, 2020 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [18778a34f2](https://linux-hardware.org/?probe=18778a34f2) | Sep 10, 2020 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [ff1f32c975](https://linux-hardware.org/?probe=ff1f32c975) | Sep 10, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [94cbf8e66c](https://linux-hardware.org/?probe=94cbf8e66c) | Sep 10, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a25d4e5346](https://linux-hardware.org/?probe=a25d4e5346) | Sep 09, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c4c1a329af](https://linux-hardware.org/?probe=c4c1a329af) | Sep 06, 2020 |
| Dell          | Inspiron 5537               | Notebook    | [4ddf924081](https://linux-hardware.org/?probe=4ddf924081) | Sep 05, 2020 |
| Dell          | Inspiron 5537               | Notebook    | [23a0e05047](https://linux-hardware.org/?probe=23a0e05047) | Sep 05, 2020 |
| Dell          | Latitude E6540              | Notebook    | [9abf14d168](https://linux-hardware.org/?probe=9abf14d168) | Aug 31, 2020 |
| HP            | 8446                        | All in one  | [08b9600cae](https://linux-hardware.org/?probe=08b9600cae) | Aug 29, 2020 |
| Dell          | Precision 5540              | Notebook    | [76f1cfa736](https://linux-hardware.org/?probe=76f1cfa736) | Aug 23, 2020 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [19af27b191](https://linux-hardware.org/?probe=19af27b191) | Aug 20, 2020 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [f555bad747](https://linux-hardware.org/?probe=f555bad747) | Aug 14, 2020 |
| I-Life Dig... | ZED AIR                     | Notebook    | [b40d7e9c7c](https://linux-hardware.org/?probe=b40d7e9c7c) | Aug 10, 2020 |
| I-Life Dig... | ZED AIR                     | Notebook    | [5662aa186c](https://linux-hardware.org/?probe=5662aa186c) | Aug 10, 2020 |
| HP            | 2AA2                        | Desktop     | [f20932c5c3](https://linux-hardware.org/?probe=f20932c5c3) | Aug 09, 2020 |
| Lenovo        | ThinkPad L480 20LS0012AD    | Notebook    | [81d46e4c4a](https://linux-hardware.org/?probe=81d46e4c4a) | Aug 02, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [670cc8a66c](https://linux-hardware.org/?probe=670cc8a66c) | Jul 26, 2020 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [aea3470496](https://linux-hardware.org/?probe=aea3470496) | Jul 21, 2020 |
| HP            | 2AA2                        | Desktop     | [424f0397a7](https://linux-hardware.org/?probe=424f0397a7) | Jul 16, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X420... | Notebook    | [b3dbd3f2af](https://linux-hardware.org/?probe=b3dbd3f2af) | Jul 14, 2020 |
| Toshiba       | TECRA A50-C                 | Notebook    | [adf7a73571](https://linux-hardware.org/?probe=adf7a73571) | Jul 03, 2020 |
| ASUSTek       | FX503VD                     | Notebook    | [d6c0a21749](https://linux-hardware.org/?probe=d6c0a21749) | Jul 02, 2020 |
| HP            | Pavilion 15                 | Notebook    | [499f0c72ee](https://linux-hardware.org/?probe=499f0c72ee) | Jun 29, 2020 |
| ASUSTek       | P7P55 LX                    | Desktop     | [dc74d7b188](https://linux-hardware.org/?probe=dc74d7b188) | Jun 25, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X420... | Notebook    | [dd5c9e8d9f](https://linux-hardware.org/?probe=dd5c9e8d9f) | Jun 23, 2020 |
| Dell          | Latitude E6410              | Notebook    | [06055ff260](https://linux-hardware.org/?probe=06055ff260) | Jun 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X420... | Notebook    | [b53cc32ed0](https://linux-hardware.org/?probe=b53cc32ed0) | Jun 19, 2020 |
| Lenovo        | G500 20236                  | Notebook    | [fdc9496e84](https://linux-hardware.org/?probe=fdc9496e84) | Jun 19, 2020 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [fdbf1ae7da](https://linux-hardware.org/?probe=fdbf1ae7da) | Jun 19, 2020 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [0d398d9227](https://linux-hardware.org/?probe=0d398d9227) | Jun 14, 2020 |
| HP            | 2AA2                        | Desktop     | [24c07d9d0d](https://linux-hardware.org/?probe=24c07d9d0d) | Jun 11, 2020 |
| HP            | 8446                        | All in one  | [d64a9cef98](https://linux-hardware.org/?probe=d64a9cef98) | Jun 11, 2020 |
| Dell          | Latitude E6410              | Notebook    | [1b73d74e65](https://linux-hardware.org/?probe=1b73d74e65) | Jun 09, 2020 |
| Lenovo        | ThinkPad L480 20LS0012AD    | Notebook    | [e9b38b78d7](https://linux-hardware.org/?probe=e9b38b78d7) | May 30, 2020 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [83ae823929](https://linux-hardware.org/?probe=83ae823929) | May 23, 2020 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [af063f022b](https://linux-hardware.org/?probe=af063f022b) | May 23, 2020 |
| HP            | Presario C300 (RH208UA#A... | Notebook    | [50e95ff237](https://linux-hardware.org/?probe=50e95ff237) | May 14, 2020 |
| HP            | Presario C300 (RH208UA#A... | Notebook    | [6b4a8eab4c](https://linux-hardware.org/?probe=6b4a8eab4c) | May 14, 2020 |
| Toshiba       | TECRA X40-D                 | Notebook    | [3255796d07](https://linux-hardware.org/?probe=3255796d07) | May 10, 2020 |
| YJKC          | vBOOK Plus RVP7             | Notebook    | [49363e9553](https://linux-hardware.org/?probe=49363e9553) | May 07, 2020 |
| HP            | 8446                        | All in one  | [96d169caae](https://linux-hardware.org/?probe=96d169caae) | May 06, 2020 |
| HP            | 8446                        | All in one  | [835b1abcee](https://linux-hardware.org/?probe=835b1abcee) | May 02, 2020 |
| HP            | 8446                        | All in one  | [aa03445e30](https://linux-hardware.org/?probe=aa03445e30) | May 01, 2020 |
| HP            | 8446                        | All in one  | [d9db887931](https://linux-hardware.org/?probe=d9db887931) | May 01, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [887a19760b](https://linux-hardware.org/?probe=887a19760b) | May 01, 2020 |
| Lenovo        | ThinkPad X240 20AMS6GB00    | Notebook    | [3fa804be21](https://linux-hardware.org/?probe=3fa804be21) | May 01, 2020 |
| HP            | 8446                        | All in one  | [eab561395e](https://linux-hardware.org/?probe=eab561395e) | Apr 27, 2020 |
| HP            | 8446                        | All in one  | [ad2491858f](https://linux-hardware.org/?probe=ad2491858f) | Apr 25, 2020 |
| YJKC          | vBOOK Plus RVP7             | Notebook    | [d2328783da](https://linux-hardware.org/?probe=d2328783da) | Apr 24, 2020 |
| Dell          | Vostro 14-5480              | Notebook    | [1bba68101c](https://linux-hardware.org/?probe=1bba68101c) | Apr 20, 2020 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [aac474f532](https://linux-hardware.org/?probe=aac474f532) | Apr 18, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [1ef49ff7a3](https://linux-hardware.org/?probe=1ef49ff7a3) | Apr 17, 2020 |
| HP            | Notebook                    | Notebook    | [4f154f82b0](https://linux-hardware.org/?probe=4f154f82b0) | Apr 01, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [5cd86dffe9](https://linux-hardware.org/?probe=5cd86dffe9) | Mar 16, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [7f0b4db18a](https://linux-hardware.org/?probe=7f0b4db18a) | Mar 12, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [87df29714d](https://linux-hardware.org/?probe=87df29714d) | Mar 11, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [04da794ff5](https://linux-hardware.org/?probe=04da794ff5) | Feb 25, 2020 |
| HP            | EliteBook 2760p             | Notebook    | [40333472c7](https://linux-hardware.org/?probe=40333472c7) | Feb 21, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [b12186f161](https://linux-hardware.org/?probe=b12186f161) | Feb 13, 2020 |
| HP            | Notebook                    | Notebook    | [a25a67e533](https://linux-hardware.org/?probe=a25a67e533) | Feb 02, 2020 |
| Lenovo        | ThinkPad T460 20FMS1A200    | Notebook    | [c2a7159d3a](https://linux-hardware.org/?probe=c2a7159d3a) | Jan 04, 2020 |
| Lenovo        | ThinkPad T460 20FMS1A200    | Notebook    | [028d728043](https://linux-hardware.org/?probe=028d728043) | Jan 04, 2020 |
| Lenovo        | Yoga S730-13IWL 81J0        | Notebook    | [d1ca80edff](https://linux-hardware.org/?probe=d1ca80edff) | Dec 24, 2019 |
| Toshiba       | Satellite A300              | Notebook    | [420c738977](https://linux-hardware.org/?probe=420c738977) | Oct 15, 2019 |
| Toshiba       | Satellite A300              | Notebook    | [036dc7e829](https://linux-hardware.org/?probe=036dc7e829) | Oct 15, 2019 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [ab1c14d729](https://linux-hardware.org/?probe=ab1c14d729) | Oct 12, 2019 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [558c01fdce](https://linux-hardware.org/?probe=558c01fdce) | Oct 07, 2019 |
| Notebook      | P95_96_97Ex,Rx              | Notebook    | [d4ad7906b5](https://linux-hardware.org/?probe=d4ad7906b5) | Sep 11, 2019 |
| Dell          | 0NK70N A03                  | Desktop     | [8aa5224a4a](https://linux-hardware.org/?probe=8aa5224a4a) | Aug 01, 2019 |
| I-Life Dig... | ZED AIR                     | Notebook    | [514c494f7f](https://linux-hardware.org/?probe=514c494f7f) | Jul 23, 2019 |
| I-Life Dig... | ZED AIR                     | Notebook    | [a9fe92aa3c](https://linux-hardware.org/?probe=a9fe92aa3c) | Jul 23, 2019 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [309f371381](https://linux-hardware.org/?probe=309f371381) | May 27, 2019 |
| HP            | EliteBook 8440p             | Notebook    | [1f8a20b199](https://linux-hardware.org/?probe=1f8a20b199) | May 25, 2019 |
| HP            | EliteBook 8440p             | Notebook    | [60d0e8dd5d](https://linux-hardware.org/?probe=60d0e8dd5d) | May 25, 2019 |
| HP            | ProBook 4540s               | Notebook    | [271be85705](https://linux-hardware.org/?probe=271be85705) | May 15, 2019 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [ab25f83cd0](https://linux-hardware.org/?probe=ab25f83cd0) | Mar 27, 2019 |
| ASUSTek       | ROG STRIX X299-XE GAMING    | Desktop     | [c8fdc5e958](https://linux-hardware.org/?probe=c8fdc5e958) | Dec 25, 2018 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [c48aa05e74](https://linux-hardware.org/?probe=c48aa05e74) | Oct 08, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Location/UAE/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 35        | 9.09%   |
| Ubuntu 22.04      | 31        | 8.05%   |
| Arch Rolling      | 19        | 4.94%   |
| Ubuntu 18.04      | 18        | 4.68%   |
| Ubuntu 24.04      | 17        | 4.42%   |
| Pop!_OS 22.04     | 13        | 3.38%   |
| Debian 12         | 12        | 3.12%   |
| Fedora 40         | 9         | 2.34%   |
| ArcoLinux Rolling | 8         | 2.08%   |
| Fedora 42         | 7         | 1.82%   |
| Debian 11         | 6         | 1.56%   |
| Fedora 41         | 5         | 1.3%    |
| Fedora 38         | 5         | 1.3%    |
| Fedora 37         | 5         | 1.3%    |
| Arch              | 5         | 1.3%    |
| Zorin 16          | 4         | 1.04%   |
| Ubuntu 22.10      | 4         | 1.04%   |
| Ubuntu 19.10      | 4         | 1.04%   |
| Linux Mint 21.3   | 4         | 1.04%   |
| Linux Mint 20.3   | 4         | 1.04%   |
| Kubuntu 22.04     | 4         | 1.04%   |
| Fedora 39         | 4         | 1.04%   |
| Fedora 36         | 4         | 1.04%   |
| Zorin 17          | 3         | 0.78%   |
| Zorin 15          | 3         | 0.78%   |
| Ubuntu 25.04      | 3         | 0.78%   |
| Ubuntu 23.04      | 3         | 0.78%   |
| Ubuntu 20.10      | 3         | 0.78%   |
| SteamOS 3.6.20    | 3         | 0.78%   |
| Linux Mint 21.2   | 3         | 0.78%   |
| Kubuntu 24.04     | 3         | 0.78%   |
| KDE neon 22.04    | 3         | 0.78%   |
| Debian 10         | 3         | 0.78%   |
| CachyOS           | 3         | 0.78%   |
| Ubuntu 24.10      | 2         | 0.52%   |
| Ubuntu 21.10      | 2         | 0.52%   |
| Ubuntu 16.04      | 2         | 0.52%   |
| SteamOS 3.5.19    | 2         | 0.52%   |
| SteamOS 3.4.6     | 2         | 0.52%   |
| Pop!_OS 20.10     | 2         | 0.52%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 124       | 33.07%  |
| Fedora       | 44        | 11.73%  |
| Arch         | 24        | 6.4%    |
| Debian       | 22        | 5.87%   |
| Linux Mint   | 18        | 4.8%    |
| Pop!_OS      | 17        | 4.53%   |
| OpenMandriva | 16        | 4.27%   |
| SteamOS      | 12        | 3.2%    |
| Kubuntu      | 12        | 3.2%    |
| Zorin        | 11        | 2.93%   |
| Kali         | 8         | 2.13%   |
| ArcoLinux    | 8         | 2.13%   |
| Manjaro      | 6         | 1.6%    |
| KDE neon     | 6         | 1.6%    |
| Nobara       | 5         | 1.33%   |
| Parrot       | 3         | 0.8%    |
| openSUSE     | 3         | 0.8%    |
| Elementary   | 3         | 0.8%    |
| CachyOS      | 3         | 0.8%    |
| Bazzite      | 3         | 0.8%    |
| Xubuntu      | 2         | 0.53%   |
| NixOS        | 2         | 0.53%   |
| Lubuntu      | 2         | 0.53%   |
| Endless      | 2         | 0.53%   |
| BlackPanther | 2         | 0.53%   |
| Ubuntu Unity | 1         | 0.27%   |
| Ubuntu MATE  | 1         | 0.27%   |
| TUXEDO OS    | 1         | 0.27%   |
| Sparky       | 1         | 0.27%   |
| ROSA         | 1         | 0.27%   |
| Rocky Linux  | 1         | 0.27%   |
| Reborn OS    | 1         | 0.27%   |
| PostmarketOS | 1         | 0.27%   |
| MX           | 1         | 0.27%   |
| Guix         | 1         | 0.27%   |
| GNOME OS     | 1         | 0.27%   |
| Gentoo       | 1         | 0.27%   |
| Garuda Linux | 1         | 0.27%   |
| Feren OS     | 1         | 0.27%   |
| EndeavourOS  | 1         | 0.27%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                                  | Computers | Percent |
|------------------------------------------|-----------|---------|
| 5.4.0-42-generic                         | 7         | 1.73%   |
| 6.9.3-76060903-generic                   | 4         | 0.99%   |
| 6.8.0-40-generic                         | 4         | 0.99%   |
| 6.1.0-21-amd64                           | 4         | 0.99%   |
| 5.4.0-58-generic                         | 4         | 0.99%   |
| 5.4.0-26-generic                         | 4         | 0.99%   |
| 5.13.0-valve36-1-neptune                 | 4         | 0.99%   |
| 6.8.5-301.fc40.x86_64                    | 3         | 0.74%   |
| 6.8.0-60-generic                         | 3         | 0.74%   |
| 6.8.0-51-generic                         | 3         | 0.74%   |
| 6.8.0-31-generic                         | 3         | 0.74%   |
| 6.5.0-valve22-1-neptune-65-g9a338ed8a75e | 3         | 0.74%   |
| 6.2.0-33-generic                         | 3         | 0.74%   |
| 6.14.2-desktop-3omv2590                  | 3         | 0.74%   |
| 6.14.0-29-generic                        | 3         | 0.74%   |
| 6.11.0-21-generic                        | 3         | 0.74%   |
| 6.1.52-valve16-1-neptune-61              | 3         | 0.74%   |
| 5.4.0-37-generic                         | 3         | 0.74%   |
| 5.11.0-40-generic                        | 3         | 0.74%   |
| 4.15.0-50-generic                        | 3         | 0.74%   |
| 6.8.0-38-generic                         | 2         | 0.5%    |
| 6.8.0-36-generic                         | 2         | 0.5%    |
| 6.8.0-35-generic                         | 2         | 0.5%    |
| 6.5.6-300.fc39.x86_64                    | 2         | 0.5%    |
| 6.5.0-kali3-amd64                        | 2         | 0.5%    |
| 6.5.0-45-generic                         | 2         | 0.5%    |
| 6.5.0-35-generic                         | 2         | 0.5%    |
| 6.4.8-desktop-2omv2390                   | 2         | 0.5%    |
| 6.4.7-200.fc38.x86_64                    | 2         | 0.5%    |
| 6.2.0-32-generic                         | 2         | 0.5%    |
| 6.2.0-26-generic                         | 2         | 0.5%    |
| 6.17.1-300.fc43.x86_64                   | 2         | 0.5%    |
| 6.14.2-300.fc42.x86_64                   | 2         | 0.5%    |
| 6.12.11-204.nobara.fc41.x86_64           | 2         | 0.5%    |
| 6.12.1-desktop-1omv2490                  | 2         | 0.5%    |
| 6.11.8-300.fc41.x86_64                   | 2         | 0.5%    |
| 6.11.6-arch1-1                           | 2         | 0.5%    |
| 6.11.0-9-generic                         | 2         | 0.5%    |
| 6.11.0-26-generic                        | 2         | 0.5%    |
| 6.1.1-desktop-1omv2290                   | 2         | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 36        | 9.25%   |
| 6.8.0   | 27        | 6.94%   |
| 5.15.0  | 21        | 5.4%    |
| 6.5.0   | 16        | 4.11%   |
| 5.19.0  | 16        | 4.11%   |
| 6.1.0   | 15        | 3.86%   |
| 4.15.0  | 14        | 3.6%    |
| 6.2.0   | 12        | 3.08%   |
| 6.14.0  | 9         | 2.31%   |
| 6.11.0  | 9         | 2.31%   |
| 5.8.0   | 9         | 2.31%   |
| 5.11.0  | 9         | 2.31%   |
| 5.13.0  | 8         | 2.06%   |
| 5.10.0  | 7         | 1.8%    |
| 5.3.0   | 6         | 1.54%   |
| 6.9.3   | 5         | 1.29%   |
| 6.14.2  | 5         | 1.29%   |
| 6.8.5   | 4         | 1.03%   |
| 6.1.52  | 4         | 1.03%   |
| 6.7.4   | 3         | 0.77%   |
| 6.5.6   | 3         | 0.77%   |
| 6.4.8   | 3         | 0.77%   |
| 6.17.1  | 3         | 0.77%   |
| 6.14.6  | 3         | 0.77%   |
| 6.12.11 | 3         | 0.77%   |
| 6.12.1  | 3         | 0.77%   |
| 6.0.12  | 3         | 0.77%   |
| 5.0.0   | 3         | 0.77%   |
| 6.8.9   | 2         | 0.51%   |
| 6.8.7   | 2         | 0.51%   |
| 6.6.1   | 2         | 0.51%   |
| 6.5.9   | 2         | 0.51%   |
| 6.4.7   | 2         | 0.51%   |
| 6.4.0   | 2         | 0.51%   |
| 6.2.10  | 2         | 0.51%   |
| 6.17.0  | 2         | 0.51%   |
| 6.14.9  | 2         | 0.51%   |
| 6.12.38 | 2         | 0.51%   |
| 6.12.10 | 2         | 0.51%   |
| 6.11.8  | 2         | 0.51%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 38        | 9.84%   |
| 6.8     | 37        | 9.59%   |
| 6.1     | 27        | 6.99%   |
| 5.15    | 26        | 6.74%   |
| 6.5     | 22        | 5.7%    |
| 6.14    | 21        | 5.44%   |
| 6.11    | 20        | 5.18%   |
| 5.19    | 19        | 4.92%   |
| 6.2     | 16        | 4.15%   |
| 4.15    | 14        | 3.63%   |
| 6.9     | 11        | 2.85%   |
| 6.12    | 11        | 2.85%   |
| 5.8     | 11        | 2.85%   |
| 5.10    | 10        | 2.59%   |
| 5.13    | 9         | 2.33%   |
| 5.11    | 9         | 2.33%   |
| 6.4     | 8         | 2.07%   |
| 6.10    | 8         | 2.07%   |
| 6.6     | 7         | 1.81%   |
| 6.17    | 7         | 1.81%   |
| 5.3     | 6         | 1.55%   |
| 6.7     | 5         | 1.3%    |
| 6.0     | 5         | 1.3%    |
| 5.16    | 5         | 1.3%    |
| 6.15    | 3         | 0.78%   |
| 5.9     | 3         | 0.78%   |
| 5.7     | 3         | 0.78%   |
| 5.14    | 3         | 0.78%   |
| 5.0     | 3         | 0.78%   |
| 4.18    | 3         | 0.78%   |
| 6.3     | 2         | 0.52%   |
| 6.16    | 2         | 0.52%   |
| 5.6     | 2         | 0.52%   |
| 5.18    | 2         | 0.52%   |
| 5.17    | 2         | 0.52%   |
| 4.19    | 2         | 0.52%   |
| 6.13    | 1         | 0.26%   |
| 5.5     | 1         | 0.26%   |
| 5.12    | 1         | 0.26%   |
| 4.4     | 1         | 0.26%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 354       | 98.61%  |
| aarch64 | 3         | 0.84%   |
| i686    | 2         | 0.56%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 195       | 52.14%  |
| KDE5          | 50        | 13.37%  |
| KDE6          | 33        | 8.82%   |
| Unknown       | 27        | 7.22%   |
| XFCE          | 17        | 4.55%   |
| X-Cinnamon    | 17        | 4.55%   |
| MATE          | 7         | 1.87%   |
| KDE           | 5         | 1.34%   |
| LXQt          | 4         | 1.07%   |
| Pantheon      | 3         | 0.8%    |
| i3            | 3         | 0.8%    |
| Hyprland      | 3         | 0.8%    |
| Cinnamon      | 2         | 0.53%   |
| wlroots       | 1         | 0.27%   |
| Unity         | 1         | 0.27%   |
| GNOME Classic | 1         | 0.27%   |
| gamescope     | 1         | 0.27%   |
| DWM           | 1         | 0.27%   |
| Budgie        | 1         | 0.27%   |
| bspwm         | 1         | 0.27%   |
| awesome       | 1         | 0.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 208       | 56.22%  |
| Wayland | 140       | 37.84%  |
| Unknown | 13        | 3.51%   |
| Tty     | 9         | 2.43%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 184       | 49.46%  |
| GDM3    | 65        | 17.47%  |
| SDDM    | 52        | 13.98%  |
| GDM     | 41        | 11.02%  |
| LightDM | 28        | 7.53%   |
| TDM     | 2         | 0.54%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 292       | 80%     |
| en_GB   | 19        | 5.21%   |
| Unknown | 18        | 4.93%   |
| C       | 13        | 3.56%   |
| ru_RU   | 5         | 1.37%   |
| en_IN   | 4         | 1.1%    |
| ar_AE   | 3         | 0.82%   |
| en_AU   | 2         | 0.55%   |
| POSIX   | 1         | 0.27%   |
| pl_PL   | 1         | 0.27%   |
| hu_HU   | 1         | 0.27%   |
| es_CO   | 1         | 0.27%   |
| en_PH   | 1         | 0.27%   |
| en_NG   | 1         | 0.27%   |
| en_AG   | 1         | 0.27%   |
| el_GR   | 1         | 0.27%   |
| de_DE   | 1         | 0.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 195       | 52.42%  |
| BIOS | 177       | 47.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 236       | 64.48%  |
| Btrfs   | 74        | 20.22%  |
| Tmpfs   | 27        | 7.38%   |
| Overlay | 18        | 4.92%   |
| Xfs     | 7         | 1.91%   |
| Zfs     | 1         | 0.27%   |
| F2fs    | 1         | 0.27%   |
| Ext2    | 1         | 0.27%   |
| Unknown | 1         | 0.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 179       | 48.64%  |
| GPT     | 173       | 47.01%  |
| MBR     | 16        | 4.35%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 327       | 90.33%  |
| Yes       | 35        | 9.67%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 253       | 69.13%  |
| Yes       | 113       | 30.87%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 87        | 24.23%  |
| Hewlett-Packard                      | 63        | 17.55%  |
| ASUSTek Computer                     | 52        | 14.48%  |
| Dell                                 | 37        | 10.31%  |
| Apple                                | 13        | 3.62%   |
| Valve                                | 12        | 3.34%   |
| MSI                                  | 11        | 3.06%   |
| Acer                                 | 10        | 2.79%   |
| Gigabyte Technology                  | 9         | 2.51%   |
| Toshiba                              | 8         | 2.23%   |
| Intel                                | 7         | 1.95%   |
| ASRock                               | 5         | 1.39%   |
| Notebook                             | 3         | 0.84%   |
| Microsoft                            | 3         | 0.84%   |
| HUAWEI                               | 3         | 0.84%   |
| Google                               | 3         | 0.84%   |
| AZW                                  | 3         | 0.84%   |
| Alienware                            | 3         | 0.84%   |
| win element                          | 2         | 0.56%   |
| Sony                                 | 2         | 0.56%   |
| Razer                                | 2         | 0.56%   |
| I-Life Digital Technologies          | 2         | 0.56%   |
| Unknown                              | 2         | 0.56%   |
| YJKC                                 | 1         | 0.28%   |
| TUXEDO                               | 1         | 0.28%   |
| Trigkey                              | 1         | 0.28%   |
| SZMZ                                 | 1         | 0.28%   |
| System76                             | 1         | 0.28%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.28%   |
| Samsung Electronics                  | 1         | 0.28%   |
| Raspberry Pi Foundation              | 1         | 0.28%   |
| Pegatron                             | 1         | 0.28%   |
| Nvidia                               | 1         | 0.28%   |
| Neousys Technology                   | 1         | 0.28%   |
| LG Electronics                       | 1         | 0.28%   |
| GMKtec                               | 1         | 0.28%   |
| eOBgmB2N8pjrlyC                      | 1         | 0.28%   |
| ECS                                  | 1         | 0.28%   |
| Biostar                              | 1         | 0.28%   |
| A-DATA Technology                    | 1         | 0.28%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Valve Jupiter                                         | 10        | 2.79%   |
| HP All-in-One 22-c0xx                                 | 3         | 0.84%   |
| ASUS VivoBook_ASUSLaptop X1404VA_X1404VA              | 3         | 0.84%   |
| ASUS ROG STRIX X670E-E GAMING WIFI                    | 3         | 0.84%   |
| ASUS All Series                                       | 3         | 0.84%   |
| Valve Galileo                                         | 2         | 0.56%   |
| Razer Blade 15 Advanced Model (Early 2020) - RZ09-033 | 2         | 0.56%   |
| Microsoft Surface Pro 4                               | 2         | 0.56%   |
| Lenovo Yoga 7 15ITL5 82BJ                             | 2         | 0.56%   |
| Lenovo Legion Slim 7 16IRH8 82Y3                      | 2         | 0.56%   |
| Lenovo IdeaPadFlex 5 14ALC05 82HU                     | 2         | 0.56%   |
| Lenovo IdeaPad 3 14ADA05 81W0                         | 2         | 0.56%   |
| HP ProBook 450 G2                                     | 2         | 0.56%   |
| HP Pavilion Notebook                                  | 2         | 0.56%   |
| HP Pavilion Gaming Laptop 15-cx0xxx                   | 2         | 0.56%   |
| HP Pavilion 15                                        | 2         | 0.56%   |
| HP ENVY Laptop 13-aq0xxx                              | 2         | 0.56%   |
| Dell Latitude E6540                                   | 2         | 0.56%   |
| Dell G5 5587                                          | 2         | 0.56%   |
| ASUS Pro WS WRX90E-SAGE SE                            | 2         | 0.56%   |
| Apple MacBookPro9,2                                   | 2         | 0.56%   |
| Apple MacBookAir7,2                                   | 2         | 0.56%   |
| Unknown                                               | 2         | 0.56%   |
| YJKC vBOOK Plus                                       | 1         | 0.28%   |
| Win Element S500+                                     | 1         | 0.28%   |
| win element MoreFine S500+                            | 1         | 0.28%   |
| TUXEDO Stellaris 16 Intel Gen7                        | 1         | 0.28%   |
| Trigkey Green G4                                      | 1         | 0.28%   |
| Toshiba TECRA X40-D                                   | 1         | 0.28%   |
| Toshiba TECRA A50-C                                   | 1         | 0.28%   |
| Toshiba Satellite L850-B434                           | 1         | 0.28%   |
| Toshiba Satellite L750                                | 1         | 0.28%   |
| Toshiba Satellite C850-A966                           | 1         | 0.28%   |
| Toshiba Satellite C660                                | 1         | 0.28%   |
| Toshiba Satellite A300                                | 1         | 0.28%   |
| Toshiba PORTEGE Z10t-A                                | 1         | 0.28%   |
| SZMZ B75-MS                                           | 1         | 0.28%   |
| System76 Pangolin                                     | 1         | 0.28%   |
| Sony VGN-NS10J_S                                      | 1         | 0.28%   |
| Sony SVE14A25CAB                                      | 1         | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 47        | 13.09%  |
| ASUS ROG           | 16        | 4.46%   |
| Lenovo IdeaPad     | 14        | 3.9%    |
| HP Pavilion        | 14        | 3.9%    |
| Valve Jupiter      | 10        | 2.79%   |
| HP Laptop          | 10        | 2.79%   |
| Dell Latitude      | 10        | 2.79%   |
| HP EliteBook       | 7         | 1.95%   |
| Dell XPS           | 7         | 1.95%   |
| Acer Aspire        | 7         | 1.95%   |
| Lenovo Yoga        | 6         | 1.67%   |
| Lenovo Legion      | 6         | 1.67%   |
| HP ProBook         | 6         | 1.67%   |
| ASUS VivoBook      | 6         | 1.67%   |
| ASUS PRIME         | 6         | 1.67%   |
| Toshiba Satellite  | 5         | 1.39%   |
| Lenovo IdeaPadFlex | 4         | 1.11%   |
| HP ENVY            | 4         | 1.11%   |
| Dell Vostro        | 4         | 1.11%   |
| Dell OptiPlex      | 4         | 1.11%   |
| Dell Inspiron      | 4         | 1.11%   |
| ASUS ASUS          | 4         | 1.11%   |
| Microsoft Surface  | 3         | 0.84%   |
| Lenovo ThinkCentre | 3         | 0.84%   |
| HP All-in-One      | 3         | 0.84%   |
| Dell Precision     | 3         | 0.84%   |
| ASUS All           | 3         | 0.84%   |
| Valve Galileo      | 2         | 0.56%   |
| Toshiba TECRA      | 2         | 0.56%   |
| Razer Blade        | 2         | 0.56%   |
| I-Life Digital ZED | 2         | 0.56%   |
| HP ZBook           | 2         | 0.56%   |
| HP EliteDesk       | 2         | 0.56%   |
| HP Elite           | 2         | 0.56%   |
| Dell PowerEdge     | 2         | 0.56%   |
| Dell G5            | 2         | 0.56%   |
| ASUS Zenbook       | 2         | 0.56%   |
| ASUS ProArt        | 2         | 0.56%   |
| ASUS Pro           | 2         | 0.56%   |
| Apple MacBookPro9  | 2         | 0.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 41        | 11.42%  |
| 2020    | 36        | 10.03%  |
| 2023    | 32        | 8.91%   |
| 2022    | 31        | 8.64%   |
| 2019    | 30        | 8.36%   |
| 2018    | 29        | 8.08%   |
| 2016    | 24        | 6.69%   |
| 2013    | 20        | 5.57%   |
| 2017    | 18        | 5.01%   |
| 2012    | 18        | 5.01%   |
| 2014    | 14        | 3.9%    |
| 2015    | 13        | 3.62%   |
| 2010    | 12        | 3.34%   |
| 2024    | 10        | 2.79%   |
| 2011    | 9         | 2.51%   |
| 2008    | 7         | 1.95%   |
| 2009    | 4         | 1.11%   |
| 2007    | 3         | 0.84%   |
| Unknown | 3         | 0.84%   |
| 2025    | 2         | 0.56%   |
| 2006    | 2         | 0.56%   |
| 2005    | 1         | 0.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 234       | 65.18%  |
| Desktop        | 80        | 22.28%  |
| Convertible    | 18        | 5.01%   |
| Mini pc        | 8         | 2.23%   |
| All in one     | 7         | 1.95%   |
| Tablet         | 6         | 1.67%   |
| System on chip | 3         | 0.84%   |
| Server         | 3         | 0.84%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 333       | 91.74%  |
| Enabled  | 30        | 8.26%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 356       | 99.16%  |
| Yes  | 3         | 0.84%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 86        | 23.89%  |
| 16.01-24.0      | 73        | 20.28%  |
| 4.01-8.0        | 70        | 19.44%  |
| 32.01-64.0      | 49        | 13.61%  |
| 3.01-4.0        | 33        | 9.17%   |
| 64.01-256.0     | 25        | 6.94%   |
| 24.01-32.0      | 12        | 3.33%   |
| More than 256.0 | 3         | 0.83%   |
| 2.01-3.0        | 3         | 0.83%   |
| 1.01-2.0        | 3         | 0.83%   |
| 0.51-1.0        | 3         | 0.83%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 102       | 26.42%  |
| 2.01-3.0   | 96        | 24.87%  |
| 3.01-4.0   | 73        | 18.91%  |
| 1.01-2.0   | 72        | 18.65%  |
| 8.01-16.0  | 25        | 6.48%   |
| 0.51-1.0   | 9         | 2.33%   |
| 16.01-24.0 | 5         | 1.3%    |
| 0.01-0.5   | 3         | 0.78%   |
| 24.01-32.0 | 1         | 0.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 237       | 65.11%  |
| 2      | 79        | 21.7%   |
| 3      | 24        | 6.59%   |
| 4      | 9         | 2.47%   |
| 6      | 4         | 1.1%    |
| 5      | 4         | 1.1%    |
| 0      | 3         | 0.82%   |
| 9      | 2         | 0.55%   |
| 11     | 1         | 0.27%   |
| 8      | 1         | 0.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 290       | 80.56%  |
| Yes       | 70        | 19.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 269       | 74.31%  |
| No        | 93        | 25.69%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 308       | 85.32%  |
| No        | 53        | 14.68%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 283       | 78.18%  |
| No        | 79        | 21.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| UAE     | 359       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Dubai            | 185       | 50.41%  |
| Abu Dhabi        | 98        | 26.7%   |
| Sharjah          | 37        | 10.08%  |
| Al Ain City      | 20        | 5.45%   |
| Ajman            | 16        | 4.36%   |
| Al Fujairah City | 5         | 1.36%   |
| Ras al-Khaimah   | 4         | 1.09%   |
| Deira            | 1         | 0.27%   |
| Al Halah         | 1         | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 94        | 136    | 18.58%  |
| WDC                            | 58        | 76     | 11.46%  |
| Seagate                        | 47        | 63     | 9.29%   |
| Toshiba                        | 30        | 35     | 5.93%   |
| SanDisk                        | 28        | 31     | 5.53%   |
| Unknown                        | 25        | 37     | 4.94%   |
| Crucial                        | 21        | 23     | 4.15%   |
| Micron Technology              | 19        | 20     | 3.75%   |
| Intel                          | 19        | 23     | 3.75%   |
| Micron/Crucial Technology      | 15        | 18     | 2.96%   |
| Kingston Technology Company    | 14        | 15     | 2.77%   |
| SK hynix                       | 12        | 17     | 2.37%   |
| Phison Electronics             | 12        | 13     | 2.37%   |
| Kingston                       | 12        | 12     | 2.37%   |
| HGST                           | 12        | 15     | 2.37%   |
| Apple                          | 7         | 8      | 1.38%   |
| Hitachi                        | 5         | 5      | 0.99%   |
| Team                           | 4         | 4      | 0.79%   |
| Lexar                          | 4         | 4      | 0.79%   |
| KIOXIA                         | 4         | 8      | 0.79%   |
| USB3.0                         | 3         | 3      | 0.59%   |
| Silicon Motion                 | 3         | 3      | 0.59%   |
| Shenzhen Longsys Electronics   | 3         | 4      | 0.59%   |
| Realtek Semiconductor          | 3         | 6      | 0.59%   |
| Phison                         | 3         | 3      | 0.59%   |
| External                       | 3         | 3      | 0.59%   |
| Corsair                        | 3         | 6      | 0.59%   |
| ASMT                           | 3         | 13     | 0.59%   |
| Unknown                        | 3         | 3      | 0.59%   |
| Transcend                      | 2         | 2      | 0.4%    |
| Patriot                        | 2         | 3      | 0.4%    |
| LaCie                          | 2         | 2      | 0.4%    |
| JMicron Technology             | 2         | 2      | 0.4%    |
| China                          | 2         | 2      | 0.4%    |
| ADATA Technology               | 2         | 2      | 0.4%    |
| A-DATA Technology              | 2         | 2      | 0.4%    |
| USB                            | 1         | 1      | 0.2%    |
| Super Talent                   | 1         | 1      | 0.2%    |
| SSK Port                       | 1         | 1      | 0.2%    |
| Solid State Storage Technology | 1         | 1      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 9         | 1.66%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 8         | 1.48%   |
| Micron/Crucial P2 NVMe PCIe SSD 2TB                   | 8         | 1.48%   |
| Seagate ST1000LM035-1RK172 1TB                        | 6         | 1.11%   |
| Phison E12 NVMe Controller 1TB                        | 6         | 1.11%   |
| HGST HTS721010A9E630 1TB                              | 6         | 1.11%   |
| Unknown MMC Card  64GB                                | 5         | 0.92%   |
| WDC WD10SPZX-08Z10 1TB                                | 4         | 0.74%   |
| Toshiba DT01ACA100 1TB                                | 4         | 0.74%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD 512GB | 4         | 0.74%   |
| Samsung SSD 990 PRO 2TB                               | 4         | 0.74%   |
| Samsung NVMe SSD Drive 256GB                          | 4         | 0.74%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB  | 4         | 0.74%   |
| Kingston Company SNV3S1000G 1TB                       | 4         | 0.74%   |
| HGST HTS725050A7E630 500GB                            | 4         | 0.74%   |
| WDC WD10JPCX-24UE4T0 1TB                              | 3         | 0.55%   |
| USB3.0 Super Speed 500GB                              | 3         | 0.55%   |
| Unknown SD/MMC/MS PRO 2GB                             | 3         | 0.55%   |
| Unknown MMC Card  512GB                               | 3         | 0.55%   |
| Unknown MMC Card  32GB                                | 3         | 0.55%   |
| Unknown MMC Card  256GB                               | 3         | 0.55%   |
| Unknown MMC Card  16GB                                | 3         | 0.55%   |
| Toshiba MQ01ABD075 752GB                              | 3         | 0.55%   |
| Seagate ST500LT012-1DG142 500GB                       | 3         | 0.55%   |
| Seagate ST500DM002-1BD142 500GB                       | 3         | 0.55%   |
| Seagate ST1000DM010-2EP102 1TB                        | 3         | 0.55%   |
| Samsung SSD 980 PRO 1TB                               | 3         | 0.55%   |
| Samsung SSD 970 EVO Plus 1TB                          | 3         | 0.55%   |
| Samsung SSD 860 EVO 1TB                               | 3         | 0.55%   |
| Samsung SSD 850 PRO 1TB                               | 3         | 0.55%   |
| Phison PS5013 E13 NVMe Controller 500GB               | 3         | 0.55%   |
| Micron MTFDHBA512QFD 512GB                            | 3         | 0.55%   |
| Micron 2400_MTFDKBA512QFM 512GB                       | 3         | 0.55%   |
| Kingston Company SNV2S2000G 2TB                       | 3         | 0.55%   |
| Intel NVMe SSD Drive 512GB                            | 3         | 0.55%   |
| External USB3.0 250GB                                 | 3         | 0.55%   |
| Crucial CT500MX500SSD1 500GB                          | 3         | 0.55%   |
| Crucial CT1000BX500SSD1 1TB                           | 3         | 0.55%   |
| Unknown                                               | 3         | 0.55%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 2         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 46        | 62     | 31.08%  |
| WDC                 | 43        | 61     | 29.05%  |
| Toshiba             | 23        | 28     | 15.54%  |
| HGST                | 12        | 15     | 8.11%   |
| Hitachi             | 5         | 5      | 3.38%   |
| USB3.0              | 3         | 3      | 2.03%   |
| Unknown             | 3         | 6      | 2.03%   |
| External            | 3         | 3      | 2.03%   |
| ASMT                | 3         | 13     | 2.03%   |
| Apple               | 2         | 2      | 1.35%   |
| Samsung Electronics | 1         | 1      | 0.68%   |
| Maxtor              | 1         | 1      | 0.68%   |
| JMicron Technology  | 1         | 1      | 0.68%   |
| HGST HTS            | 1         | 1      | 0.68%   |
| Fujitsu             | 1         | 1      | 0.68%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 30        | 44     | 27.78%  |
| Crucial             | 16        | 18     | 14.81%  |
| WDC                 | 9         | 9      | 8.33%   |
| SanDisk             | 8         | 9      | 7.41%   |
| Kingston            | 6         | 6      | 5.56%   |
| Intel               | 5         | 6      | 4.63%   |
| Team                | 3         | 3      | 2.78%   |
| Apple               | 3         | 3      | 2.78%   |
| Transcend           | 2         | 2      | 1.85%   |
| Toshiba             | 2         | 2      | 1.85%   |
| Patriot             | 2         | 3      | 1.85%   |
| Lexar               | 2         | 2      | 1.85%   |
| LaCie               | 2         | 2      | 1.85%   |
| Corsair             | 2         | 5      | 1.85%   |
| China               | 2         | 2      | 1.85%   |
| Super Talent        | 1         | 1      | 0.93%   |
| SSK Port            | 1         | 1      | 0.93%   |
| SK hynix            | 1         | 1      | 0.93%   |
| PNY                 | 1         | 1      | 0.93%   |
| Micron Technology   | 1         | 1      | 0.93%   |
| MAX                 | 1         | 1      | 0.93%   |
| KingSpec            | 1         | 2      | 0.93%   |
| HXY                 | 1         | 1      | 0.93%   |
| HUGWORLD            | 1         | 1      | 0.93%   |
| Gigabyte Technology | 1         | 1      | 0.93%   |
| CT1000P3            | 1         | 1      | 0.93%   |
| CT1000BX            | 1         | 1      | 0.93%   |
| Carlstein           | 1         | 1      | 0.93%   |
| Unknown             | 1         | 1      | 0.93%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 209       | 280    | 45.83%  |
| HDD     | 130       | 203    | 28.51%  |
| SSD     | 92        | 131    | 20.18%  |
| MMC     | 21        | 29     | 4.61%   |
| Unknown | 4         | 7      | 0.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 208       | 279    | 47.93%  |
| SATA | 181       | 295    | 41.71%  |
| SAS  | 24        | 47     | 5.53%   |
| MMC  | 21        | 29     | 4.84%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 105       | 140    | 44.87%  |
| 0.51-1.0   | 86        | 110    | 36.75%  |
| 1.01-2.0   | 24        | 41     | 10.26%  |
| 3.01-4.0   | 9         | 17     | 3.85%   |
| 10.01-20.0 | 6         | 20     | 2.56%   |
| 4.01-10.0  | 3         | 5      | 1.28%   |
| 2.01-3.0   | 1         | 1      | 0.43%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 98        | 26.06%  |
| 101-250        | 77        | 20.48%  |
| 501-1000       | 56        | 14.89%  |
| 1001-2000      | 39        | 10.37%  |
| 51-100         | 24        | 6.38%   |
| More than 3000 | 23        | 6.12%   |
| 1-20           | 20        | 5.32%   |
| 21-50          | 17        | 4.52%   |
| 2001-3000      | 12        | 3.19%   |
| Unknown        | 10        | 2.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 131       | 34.03%  |
| 21-50          | 83        | 21.56%  |
| 51-100         | 49        | 12.73%  |
| 101-250        | 47        | 12.21%  |
| 251-500        | 24        | 6.23%   |
| 501-1000       | 23        | 5.97%   |
| Unknown        | 10        | 2.6%    |
| 1001-2000      | 7         | 1.82%   |
| More than 3000 | 6         | 1.56%   |
| 2001-3000      | 5         | 1.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                                     | Computers | Drives | Percent |
|-----------------------------------------------------------|-----------|--------|---------|
| WDC WD40PURZ-85TTDY0 4TB                                  | 1         | 2      | 5.26%   |
| WDC WD40EFRX-68WT0N0 4TB                                  | 1         | 2      | 5.26%   |
| WDC WD20EADS-00R6B0 2TB                                   | 1         | 1      | 5.26%   |
| WDC WD10JPVX-60JC3T1 1TB                                  | 1         | 1      | 5.26%   |
| WDC WD10EARS-00MVWB0 1TB                                  | 1         | 1      | 5.26%   |
| WDC WD Blue SA510 2.5 500GB                               | 1         | 1      | 5.26%   |
| Toshiba MQ01ABD050V 500GB                                 | 1         | 1      | 5.26%   |
| Seagate ST500LT012-1DG142 500GB                           | 1         | 1      | 5.26%   |
| Seagate ST500LM000-1EJ162 500GB                           | 1         | 2      | 5.26%   |
| Seagate ST20000NM007D-3DJ103 20TB                         | 1         | 1      | 5.26%   |
| Seagate ST1000LM035-1RK172 1TB                            | 1         | 1      | 5.26%   |
| Seagate ST1000DM003-1ER162 1TB                            | 1         | 1      | 5.26%   |
| SanDisk SD9SN8W512G1002 512GB SSD                         | 1         | 1      | 5.26%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD                       | 1         | 2      | 5.26%   |
| Samsung Electronics MZVLQ256HBJD-00BH1 256GB              | 1         | 1      | 5.26%   |
| Realtek Semiconductor RTS5763DL NVMe SSD Controller 512GB | 1         | 1      | 5.26%   |
| Micron Technology 1100 SATA 512GB SSD                     | 1         | 1      | 5.26%   |
| Intel SSDSCKKF256H6 SATA 256GB                            | 1         | 1      | 5.26%   |
| Intel SSDSC2BB480G7 480GB                                 | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| WDC                   | 6         | 8      | 31.58%  |
| Seagate               | 5         | 6      | 26.32%  |
| SanDisk               | 2         | 3      | 10.53%  |
| Intel                 | 2         | 2      | 10.53%  |
| Toshiba               | 1         | 1      | 5.26%   |
| Samsung Electronics   | 1         | 1      | 5.26%   |
| Realtek Semiconductor | 1         | 1      | 5.26%   |
| Micron Technology     | 1         | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 7      | 45.45%  |
| Seagate | 5         | 6      | 45.45%  |
| Toshiba | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 14     | 56.25%  |
| SSD  | 5         | 7      | 31.25%  |
| NVMe | 2         | 2      | 12.5%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 229       | 406    | 59.95%  |
| Works    | 138       | 221    | 36.13%  |
| Malfunc  | 15        | 23     | 3.93%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 221       | 45.85%  |
| Samsung Electronics              | 71        | 14.73%  |
| AMD                              | 26        | 5.39%   |
| SanDisk                          | 25        | 5.19%   |
| Micron/Crucial Technology        | 19        | 3.94%   |
| Kingston Technology Company      | 19        | 3.94%   |
| Micron Technology                | 18        | 3.73%   |
| Phison Electronics               | 16        | 3.32%   |
| SK hynix                         | 11        | 2.28%   |
| ASMedia Technology               | 8         | 1.66%   |
| Toshiba America Info Systems     | 5         | 1.04%   |
| Silicon Motion                   | 5         | 1.04%   |
| Shenzhen Longsys Electronics     | 4         | 0.83%   |
| KIOXIA                           | 4         | 0.83%   |
| Realtek Semiconductor            | 3         | 0.62%   |
| LSI Logic / Symbios Logic        | 3         | 0.62%   |
| Broadcom / LSI                   | 3         | 0.62%   |
| ADATA Technology                 | 3         | 0.62%   |
| Nvidia                           | 2         | 0.41%   |
| Marvell Technology Group         | 2         | 0.41%   |
| JMicron Technology               | 2         | 0.41%   |
| Apple                            | 2         | 0.41%   |
| VIA Technologies                 | 1         | 0.21%   |
| Solidigm                         | 1         | 0.21%   |
| Solid State Storage Technology   | 1         | 0.21%   |
| Shenzhen Shichuangyi Electronics | 1         | 0.21%   |
| Seagate Technology               | 1         | 0.21%   |
| OCZ Technology Group             | 1         | 0.21%   |
| O2 Micro                         | 1         | 0.21%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.21%   |
| Lite-On Technology               | 1         | 0.21%   |
| Lenovo                           | 1         | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 21        | 4.08%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 20        | 3.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 19        | 3.69%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 18        | 3.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 15        | 2.91%   |
| Intel Volume Management Device NVMe RAID Controller                            | 14        | 2.72%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 14        | 2.72%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 13        | 2.52%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 12        | 2.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 11        | 2.14%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 10        | 1.94%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 10        | 1.94%   |
| Phison E12 NVMe Controller                                                     | 8         | 1.55%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 8         | 1.55%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 8         | 1.55%   |
| AMD 600 Series Chipset SATA Controller                                         | 8         | 1.55%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 7         | 1.36%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 7         | 1.36%   |
| Intel SSD 660P Series                                                          | 7         | 1.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 7         | 1.36%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                   | 6         | 1.17%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 6         | 1.17%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                           | 6         | 1.17%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 6         | 1.17%   |
| Intel Tiger Lake-LP SATA Controller                                            | 6         | 1.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 6         | 1.17%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 5         | 0.97%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 5         | 0.97%   |
| Intel Comet Lake SATA AHCI Controller                                          | 5         | 0.97%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 5         | 0.97%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 5         | 0.97%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 5         | 0.97%   |
| AMD 500 Series Chipset SATA Controller                                         | 5         | 0.97%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 4         | 0.78%   |
| Micron 2550 NVMe SSD (DRAM-less)                                               | 4         | 0.78%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 4         | 0.78%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 4         | 0.78%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 4         | 0.78%   |
| Intel SATA Controller [RAID mode]                                              | 4         | 0.78%   |
| Intel RST Volume Management Device Controller                                  | 4         | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 208       | 44.64%  |
| SATA | 197       | 42.27%  |
| RAID | 47        | 10.09%  |
| IDE  | 10        | 2.15%   |
| SAS  | 3         | 0.64%   |
| SCSI | 1         | 0.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 287       | 79.94%  |
| AMD      | 69        | 19.22%  |
| Qualcomm | 1         | 0.28%   |
| ARM      | 1         | 0.28%   |
| Unknown  | 1         | 0.28%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| AMD Custom APU 0405                     | 10        | 2.79%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 9         | 2.51%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 7         | 1.95%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 7         | 1.95%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 6         | 1.67%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 5         | 1.39%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 5         | 1.39%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 5         | 1.39%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 5         | 1.39%   |
| Intel 13th Gen Core i7-1355U            | 5         | 1.39%   |
| Intel 12th Gen Core i7-12700H           | 5         | 1.39%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 5         | 1.39%   |
| AMD Ryzen 9 5900HX with Radeon Graphics | 5         | 1.39%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 4         | 1.11%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 4         | 1.11%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 4         | 1.11%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 4         | 1.11%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 4         | 1.11%   |
| Intel Xeon CPU E5620 @ 2.40GHz          | 3         | 0.84%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 3         | 0.84%   |
| Intel Core i7-8665U CPU @ 1.90GHz       | 3         | 0.84%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 3         | 0.84%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 3         | 0.84%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 3         | 0.84%   |
| Intel Core i5-9400T CPU @ 1.80GHz       | 3         | 0.84%   |
| Intel Core i5-8300H CPU @ 2.30GHz       | 3         | 0.84%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 3         | 0.84%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 3         | 0.84%   |
| Intel Core i3-10110U CPU @ 2.10GHz      | 3         | 0.84%   |
| AMD Ryzen AI 9 HX 370 w/ Radeon 890M    | 3         | 0.84%   |
| AMD Ryzen 7 7730U with Radeon Graphics  | 3         | 0.84%   |
| AMD Ryzen 7 4700U with Radeon Graphics  | 3         | 0.84%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 3         | 0.84%   |
| Intel Core i9-10885H CPU @ 2.40GHz      | 2         | 0.56%   |
| Intel Core i7-9700 CPU @ 3.00GHz        | 2         | 0.56%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 2         | 0.56%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz      | 2         | 0.56%   |
| Intel Core i7-4790S CPU @ 3.20GHz       | 2         | 0.56%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 2         | 0.56%   |
| Intel Core i7-3770K CPU @ 3.50GHz       | 2         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 98        | 27.3%   |
| Intel Core i5           | 81        | 22.56%  |
| Other                   | 74        | 20.61%  |
| AMD Ryzen 7             | 22        | 6.13%   |
| Intel Core i3           | 13        | 3.62%   |
| AMD Ryzen 9             | 13        | 3.62%   |
| AMD Ryzen 5             | 10        | 2.79%   |
| Intel Xeon              | 8         | 2.23%   |
| Intel Celeron           | 8         | 2.23%   |
| Intel Core 2 Duo        | 6         | 1.67%   |
| Intel Core i9           | 5         | 1.39%   |
| Intel Core              | 3         | 0.84%   |
| AMD Ryzen Threadripper  | 3         | 0.84%   |
| Intel Atom              | 2         | 0.56%   |
| AMD Ryzen 7 PRO         | 2         | 0.56%   |
| Intel Xeon Silver       | 1         | 0.28%   |
| Intel Xeon Gold         | 1         | 0.28%   |
| Intel Pentium Dual-Core | 1         | 0.28%   |
| Intel Pentium 4         | 1         | 0.28%   |
| Intel Pentium           | 1         | 0.28%   |
| Intel Core m5           | 1         | 0.28%   |
| Intel Core 2 Quad       | 1         | 0.28%   |
| Intel Celeron M         | 1         | 0.28%   |
| AMD Sempron             | 1         | 0.28%   |
| AMD Ryzen 3             | 1         | 0.28%   |
| AMD A6                  | 1         | 0.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 123       | 34.26%  |
| 2       | 100       | 27.86%  |
| 8       | 50        | 13.93%  |
| 6       | 36        | 10.03%  |
| 14      | 11        | 3.06%   |
| 10      | 11        | 3.06%   |
| 12      | 10        | 2.79%   |
| 16      | 7         | 1.95%   |
| 24      | 4         | 1.11%   |
| 1       | 4         | 1.11%   |
| 64      | 2         | 0.56%   |
| Unknown | 1         | 0.28%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 353       | 98.33%  |
| 2       | 5         | 1.39%   |
| Unknown | 1         | 0.28%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 304       | 84.68%  |
| 1       | 54        | 15.04%  |
| Unknown | 1         | 0.28%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 355       | 98.89%  |
| 32-bit         | 2         | 0.56%   |
| 64-bit         | 1         | 0.28%   |
| Unknown        | 1         | 0.28%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 217       | 58.97%  |
| 0x306a9    | 12        | 3.26%   |
| 0x406e3    | 10        | 2.72%   |
| 0x806ec    | 9         | 2.45%   |
| 0x906ea    | 8         | 2.17%   |
| 0x806c1    | 8         | 2.17%   |
| 0x40651    | 8         | 2.17%   |
| 0x306c3    | 7         | 1.9%    |
| 0x206a7    | 7         | 1.9%    |
| 0x906e9    | 5         | 1.36%   |
| 0x806ea    | 5         | 1.36%   |
| 0x806e9    | 5         | 1.36%   |
| 0x906a3    | 4         | 1.09%   |
| 0xb06a3    | 3         | 0.82%   |
| 0xa0652    | 3         | 0.82%   |
| 0x906ed    | 3         | 0.82%   |
| 0x506e3    | 3         | 0.82%   |
| 0x206c2    | 3         | 0.82%   |
| 0x20655    | 3         | 0.82%   |
| 0x0a50000c | 3         | 0.82%   |
| 0xb0671    | 2         | 0.54%   |
| 0xa0655    | 2         | 0.54%   |
| 0x806eb    | 2         | 0.54%   |
| 0x6fd      | 2         | 0.54%   |
| 0x306f2    | 2         | 0.54%   |
| 0x306d4    | 2         | 0.54%   |
| 0x106e5    | 2         | 0.54%   |
| 0x1067a    | 2         | 0.54%   |
| 0x08608103 | 2         | 0.54%   |
| 0x08600104 | 2         | 0.54%   |
| 0x08108109 | 2         | 0.54%   |
| 0xf29      | 1         | 0.27%   |
| 0x806d1    | 1         | 0.27%   |
| 0x706a1    | 1         | 0.27%   |
| 0x6fb      | 1         | 0.27%   |
| 0x6e8      | 1         | 0.27%   |
| 0x506c9    | 1         | 0.27%   |
| 0x406c4    | 1         | 0.27%   |
| 0x406c3    | 1         | 0.27%   |
| 0x306e4    | 1         | 0.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 79        | 22.01%  |
| Unknown           | 61        | 16.99%  |
| Haswell           | 31        | 8.64%   |
| Skylake           | 28        | 7.8%    |
| IvyBridge         | 20        | 5.57%   |
| Zen 3             | 19        | 5.29%   |
| TigerLake         | 19        | 5.29%   |
| SandyBridge       | 14        | 3.9%    |
| CometLake         | 13        | 3.62%   |
| Alderlake Hybrid  | 13        | 3.62%   |
| Westmere          | 9         | 2.51%   |
| Broadwell         | 9         | 2.51%   |
| Zen 2             | 7         | 1.95%   |
| Zen+              | 5         | 1.39%   |
| Silvermont        | 5         | 1.39%   |
| Penryn            | 5         | 1.39%   |
| Icelake           | 4         | 1.11%   |
| Goldmont plus     | 3         | 0.84%   |
| Core              | 3         | 0.84%   |
| Nehalem           | 2         | 0.56%   |
| Meteorlake Hybrid | 2         | 0.56%   |
| Zen               | 1         | 0.28%   |
| Piledriver        | 1         | 0.28%   |
| P6                | 1         | 0.28%   |
| NetBurst          | 1         | 0.28%   |
| Lunarlake Hybrid  | 1         | 0.28%   |
| K8 Hammer         | 1         | 0.28%   |
| Gracemont         | 1         | 0.28%   |
| Goldmont          | 1         | 0.28%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 233       | 49.79%  |
| Nvidia                     | 145       | 30.98%  |
| AMD                        | 87        | 18.59%  |
| Matrox Electronics Systems | 2         | 0.43%   |
| ASPEED Technology          | 1         | 0.21%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 17        | 3.59%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 17        | 3.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 15        | 3.16%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 13        | 2.74%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 12        | 2.53%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 12        | 2.53%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 11        | 2.32%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 10        | 2.11%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 2.11%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 10        | 2.11%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 9         | 1.9%    |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 9         | 1.9%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 1.69%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 8         | 1.69%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 7         | 1.48%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 1.48%   |
| Nvidia GM108M [GeForce MX130]                                                            | 6         | 1.27%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 6         | 1.27%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 1.27%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 6         | 1.27%   |
| Nvidia GM108M [GeForce MX110]                                                            | 5         | 1.05%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                                    | 5         | 1.05%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                                  | 5         | 1.05%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.05%   |
| AMD Lucienne                                                                             | 5         | 1.05%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 0.84%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 0.84%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                          | 4         | 0.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 0.84%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 0.84%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 0.84%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 4         | 0.84%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 0.84%   |
| AMD Phoenix1                                                                             | 4         | 0.84%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 0.84%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.63%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 0.63%   |
| Nvidia AD102 [GeForce RTX 4090]                                                          | 3         | 0.63%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                                    | 3         | 0.63%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 132       | 36.57%  |
| Intel + Nvidia     | 80        | 22.16%  |
| 1 x AMD            | 56        | 15.51%  |
| 1 x Nvidia         | 52        | 14.4%   |
| Intel + AMD        | 17        | 4.71%   |
| AMD + Nvidia       | 11        | 3.05%   |
| Other              | 3         | 0.83%   |
| 2 x AMD            | 3         | 0.83%   |
| 2 x Nvidia         | 2         | 0.55%   |
| 1 x Matrox         | 2         | 0.55%   |
| 2 x Intel          | 1         | 0.28%   |
| Intel + 2 x Nvidia | 1         | 0.28%   |
| 1 x ASPEED         | 1         | 0.28%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 272       | 74.52%  |
| Proprietary | 66        | 18.08%  |
| Unknown     | 27        | 7.4%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 249       | 68.22%  |
| 1.01-2.0   | 34        | 9.32%   |
| 0.01-0.5   | 23        | 6.3%    |
| 3.01-4.0   | 20        | 5.48%   |
| 7.01-8.0   | 11        | 3.01%   |
| 8.01-16.0  | 10        | 2.74%   |
| 0.51-1.0   | 6         | 1.64%   |
| 5.01-6.0   | 5         | 1.37%   |
| 16.01-24.0 | 3         | 0.82%   |
| 2.01-3.0   | 2         | 0.55%   |
| 32.01-64.0 | 1         | 0.27%   |
| 4.01-5.0   | 1         | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 49        | 12.76%  |
| Samsung Electronics     | 48        | 12.5%   |
| BOE                     | 47        | 12.24%  |
| Chimei Innolux          | 41        | 10.68%  |
| LG Display              | 34        | 8.85%   |
| Goldstar                | 24        | 6.25%   |
| Apple                   | 14        | 3.65%   |
| Hewlett-Packard         | 13        | 3.39%   |
| BenQ                    | 13        | 3.39%   |
| Valve                   | 11        | 2.86%   |
| Dell                    | 10        | 2.6%    |
| Lenovo                  | 8         | 2.08%   |
| InfoVision              | 6         | 1.56%   |
| Ancor Communications    | 6         | 1.56%   |
| ASUSTek Computer        | 5         | 1.3%    |
| Sharp                   | 4         | 1.04%   |
| Philips                 | 4         | 1.04%   |
| CSO                     | 4         | 1.04%   |
| ViewSonic               | 3         | 0.78%   |
| HKC                     | 3         | 0.78%   |
| Hitachi                 | 3         | 0.78%   |
| Sony                    | 2         | 0.52%   |
| PANDA                   | 2         | 0.52%   |
| Mi                      | 2         | 0.52%   |
| LGD                     | 2         | 0.52%   |
| LG Philips              | 2         | 0.52%   |
| Gigabyte Technology     | 2         | 0.52%   |
| Chi Mei Optoelectronics | 2         | 0.52%   |
| AOC                     | 2         | 0.52%   |
| Acer                    | 2         | 0.52%   |
| WBT                     | 1         | 0.26%   |
| TMX                     | 1         | 0.26%   |
| Seiko/Epson             | 1         | 0.26%   |
| RTK                     | 1         | 0.26%   |
| Panasonic               | 1         | 0.26%   |
| ODH                     | 1         | 0.26%   |
| LG Electronics          | 1         | 0.26%   |
| HUAWEI                  | 1         | 0.26%   |
| Hannspree               | 1         | 0.26%   |
| DENON                   | 1         | 0.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                     | 9         | 2.3%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 5         | 1.28%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                  | 4         | 1.02%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                    | 4         | 1.02%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                       | 4         | 1.02%   |
| ASUSTek Computer PG32UQ AUS32E1 3840x2160 708x399mm 32.0-inch           | 4         | 1.02%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 3         | 0.77%   |
| Hewlett-Packard E233 HPN3460 1920x1080 510x290mm 23.1-inch              | 3         | 0.77%   |
| Hewlett-Packard ALL-in-One HPN401F 1920x1080 476x268mm 21.5-inch        | 3         | 0.77%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch          | 3         | 0.77%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch          | 3         | 0.77%   |
| Valve ANX7530 U VLV3003 800x1280 100x160mm 7.4-inch                     | 2         | 0.51%   |
| Sony AVSYSTEM SNY050A 1280x720 708x398mm 32.0-inch                      | 2         | 0.51%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch   | 2         | 0.51%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch   | 2         | 0.51%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 2         | 0.51%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch       | 2         | 0.51%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                        | 2         | 0.51%   |
| LGD LCD Monitor 1366x768                                                | 2         | 0.51%   |
| LG Display LCD Monitor LGD0575 1920x1080 309x174mm 14.0-inch            | 2         | 0.51%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch             | 2         | 0.51%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 0.51%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch            | 2         | 0.51%   |
| InfoVision LCD Monitor IVO04E3 1366x768 277x156mm 12.5-inch             | 2         | 0.51%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                   | 2         | 0.51%   |
| CSO LCD Monitor CSO1603 2560x1600 344x215mm 16.0-inch                   | 2         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch        | 2         | 0.51%   |
| BOE LCD Monitor BOE08E8 1920x1080 344x194mm 15.5-inch                   | 2         | 0.51%   |
| BOE LCD Monitor BOE07A1 1920x1080 344x193mm 15.5-inch                   | 2         | 0.51%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                   | 2         | 0.51%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                    | 2         | 0.51%   |
| AU Optronics LCD Monitor AUO272B 3840x2160 293x165mm 13.2-inch          | 2         | 0.51%   |
| Apple Color LCD APPA01B 1440x900 286x179mm 13.3-inch                    | 2         | 0.51%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                    | 2         | 0.51%   |
| Ancor Communications VG248 ACI24A4 1920x1080 531x299mm 24.0-inch        | 2         | 0.51%   |
| WBT GOP28UHD144I WBT2800 3840x2160 630x330mm 28.0-inch                  | 1         | 0.26%   |
| ViewSonic VX2718 series VSCE439 1920x1080 609x348mm 27.6-inch           | 1         | 0.26%   |
| ViewSonic VG2439 SERIES VSCD22B 1920x1080 521x293mm 23.5-inch           | 1         | 0.26%   |
| ViewSonic VA1918wm VSCC821 1440x900 410x256mm 19.0-inch                 | 1         | 0.26%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                 | 1         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 163       | 43.7%   |
| 1366x768 (WXGA)   | 62        | 16.62%  |
| 3840x2160 (4K)    | 43        | 11.53%  |
| 2560x1440 (QHD)   | 16        | 4.29%   |
| 800x1280          | 12        | 3.22%   |
| 1920x1200 (WUXGA) | 11        | 2.95%   |
| 1600x900 (HD+)    | 10        | 2.68%   |
| 2560x1600         | 8         | 2.14%   |
| 3440x1440         | 6         | 1.61%   |
| 1280x800 (WXGA)   | 6         | 1.61%   |
| 2880x1800         | 5         | 1.34%   |
| 2560x1080         | 4         | 1.07%   |
| 1440x900 (WXGA+)  | 4         | 1.07%   |
| 3840x1080         | 3         | 0.8%    |
| 2736x1824         | 3         | 0.8%    |
| Unknown           | 3         | 0.8%    |
| 3200x2000         | 2         | 0.54%   |
| 2160x1440         | 2         | 0.54%   |
| 3840x2400         | 1         | 0.27%   |
| 3456x2160         | 1         | 0.27%   |
| 3200x1800 (QHD+)  | 1         | 0.27%   |
| 3072x1920         | 1         | 0.27%   |
| 3000x2000         | 1         | 0.27%   |
| 2880x1920         | 1         | 0.27%   |
| 2304x1440         | 1         | 0.27%   |
| 2240x1400         | 1         | 0.27%   |
| 1920x515          | 1         | 0.27%   |
| 1360x768          | 1         | 0.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 96        | 24.87%  |
| 14      | 49        | 12.69%  |
| 13      | 47        | 12.18%  |
| 27      | 21        | 5.44%   |
| 24      | 19        | 4.92%   |
| 23      | 16        | 4.15%   |
| 21      | 13        | 3.37%   |
| 16      | 13        | 3.37%   |
| 31      | 11        | 2.85%   |
| 12      | 11        | 2.85%   |
| 7       | 11        | 2.85%   |
| Unknown | 11        | 2.85%   |
| 11      | 9         | 2.33%   |
| 84      | 7         | 1.81%   |
| 34      | 6         | 1.55%   |
| 72      | 5         | 1.3%    |
| 32      | 5         | 1.3%    |
| 18      | 5         | 1.3%    |
| 17      | 5         | 1.3%    |
| 20      | 4         | 1.04%   |
| 19      | 3         | 0.78%   |
| 65      | 2         | 0.52%   |
| 54      | 2         | 0.52%   |
| 48      | 2         | 0.52%   |
| 41      | 2         | 0.52%   |
| 52      | 1         | 0.26%   |
| 49      | 1         | 0.26%   |
| 46      | 1         | 0.26%   |
| 44      | 1         | 0.26%   |
| 42      | 1         | 0.26%   |
| 40      | 1         | 0.26%   |
| 35      | 1         | 0.26%   |
| 29      | 1         | 0.26%   |
| 28      | 1         | 0.26%   |
| 8       | 1         | 0.26%   |
| 3       | 1         | 0.26%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 178       | 46.72%  |
| 501-600     | 52        | 13.65%  |
| 201-300     | 45        | 11.81%  |
| 401-500     | 24        | 6.3%    |
| 601-700     | 15        | 3.94%   |
| 1-100       | 12        | 3.15%   |
| 1501-2000   | 11        | 2.89%   |
| Unknown     | 11        | 2.89%   |
| 701-800     | 10        | 2.62%   |
| 1001-1500   | 9         | 2.36%   |
| 351-400     | 7         | 1.84%   |
| 801-900     | 3         | 0.79%   |
| 901-1000    | 3         | 0.79%   |
| 101-200     | 1         | 0.26%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 267       | 76.5%   |
| 16/10   | 40        | 11.46%  |
| Unknown | 10        | 2.87%   |
| 21/9    | 9         | 2.58%   |
| 0.67    | 9         | 2.58%   |
| 3/2     | 5         | 1.43%   |
| 32/9    | 3         | 0.86%   |
| 6/5     | 2         | 0.57%   |
| 0.62    | 2         | 0.57%   |
| 3.73    | 1         | 0.29%   |
| 0.63    | 1         | 0.29%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 95        | 24.68%  |
| 81-90          | 78        | 20.26%  |
| 201-250        | 38        | 9.87%   |
| 351-500        | 23        | 5.97%   |
| 301-350        | 23        | 5.97%   |
| 71-80          | 17        | 4.42%   |
| More than 1000 | 16        | 4.16%   |
| 1-40           | 13        | 3.38%   |
| 111-120        | 13        | 3.38%   |
| 151-200        | 12        | 3.12%   |
| 61-70          | 11        | 2.86%   |
| Unknown        | 11        | 2.86%   |
| 51-60          | 9         | 2.34%   |
| 501-1000       | 9         | 2.34%   |
| 121-130        | 6         | 1.56%   |
| 251-300        | 5         | 1.3%    |
| 141-150        | 5         | 1.3%    |
| 91-100         | 1         | 0.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 129       | 34.4%   |
| 51-100        | 84        | 22.4%   |
| 101-120       | 73        | 19.47%  |
| 161-240       | 51        | 13.6%   |
| More than 240 | 21        | 5.6%    |
| Unknown       | 11        | 2.93%   |
| 1-50          | 6         | 1.6%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 288       | 79.12%  |
| 2     | 51        | 14.01%  |
| 0     | 20        | 5.49%   |
| 3     | 5         | 1.37%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 214       | 40.53%  |
| Realtek Semiconductor           | 165       | 31.25%  |
| Qualcomm Atheros                | 29        | 5.49%   |
| Broadcom                        | 27        | 5.11%   |
| MediaTek                        | 21        | 3.98%   |
| TP-Link                         | 9         | 1.7%    |
| ASIX Electronics                | 9         | 1.7%    |
| Ralink                          | 7         | 1.33%   |
| Marvell Technology Group        | 6         | 1.14%   |
| Shenzhen Goodix Technology      | 5         | 0.95%   |
| Broadcom Limited                | 5         | 0.95%   |
| Xiaomi                          | 4         | 0.76%   |
| Qualcomm                        | 3         | 0.57%   |
| Sigma Designs                   | 2         | 0.38%   |
| Ralink Technology               | 2         | 0.38%   |
| Nvidia                          | 2         | 0.38%   |
| Aquantia                        | 2         | 0.38%   |
| Wilocity                        | 1         | 0.19%   |
| VIA Technologies                | 1         | 0.19%   |
| SILICON Laboratories            | 1         | 0.19%   |
| Sierra Wireless                 | 1         | 0.19%   |
| Samsung Electronics             | 1         | 0.19%   |
| Qualcomm Atheros Communications | 1         | 0.19%   |
| QinHeng Electronics             | 1         | 0.19%   |
| NetGear                         | 1         | 0.19%   |
| Motorola PCS                    | 1         | 0.19%   |
| Microsoft                       | 1         | 0.19%   |
| Microchip Technology            | 1         | 0.19%   |
| Lenovo                          | 1         | 0.19%   |
| Kinesis                         | 1         | 0.19%   |
| Google                          | 1         | 0.19%   |
| D-Link                          | 1         | 0.19%   |
| American Megatrends             | 1         | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 87        | 13.57%  |
| Realtek RTL8125 2.5GbE Controller                                      | 18        | 2.81%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 17        | 2.65%   |
| Intel Wi-Fi 6 AX200                                                    | 17        | 2.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 16        | 2.5%    |
| Intel Wireless 8265 / 8275                                             | 15        | 2.34%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 15        | 2.34%   |
| Intel Wi-Fi 6 AX201                                                    | 15        | 2.34%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 13        | 2.03%   |
| Intel Wireless 8260                                                    | 13        | 2.03%   |
| Intel Wireless 7260                                                    | 12        | 1.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 11        | 1.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 11        | 1.72%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 11        | 1.72%   |
| Intel Ethernet Controller I225-V                                       | 9         | 1.4%    |
| ASIX AX88179 Gigabit Ethernet                                          | 9         | 1.4%    |
| Intel Ethernet Connection I219-LM                                      | 8         | 1.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 1.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 7         | 1.09%   |
| Intel Wireless 7265                                                    | 7         | 1.09%   |
| Intel Ethernet Connection I217-LM                                      | 7         | 1.09%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 7         | 1.09%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 6         | 0.94%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 6         | 0.94%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 6         | 0.94%   |
| Intel I210 Gigabit Network Connection                                  | 6         | 0.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 6         | 0.94%   |
| Shenzhen Goodix Fingerprint Reader                                     | 5         | 0.78%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 5         | 0.78%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 5         | 0.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 5         | 0.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 5         | 0.78%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 5         | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                                  | 5         | 0.78%   |
| Intel Ethernet Connection (2) I219-V                                   | 5         | 0.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 5         | 0.78%   |
| Intel 82579V Gigabit Network Connection                                | 5         | 0.78%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 4         | 0.62%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 4         | 0.62%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 4         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 170       | 51.99%  |
| Realtek Semiconductor           | 60        | 18.35%  |
| Qualcomm Atheros                | 24        | 7.34%   |
| Broadcom                        | 20        | 6.12%   |
| MediaTek                        | 19        | 5.81%   |
| TP-Link                         | 9         | 2.75%   |
| Ralink                          | 7         | 2.14%   |
| Broadcom Limited                | 5         | 1.53%   |
| Marvell Technology Group        | 3         | 0.92%   |
| Ralink Technology               | 2         | 0.61%   |
| Qualcomm                        | 2         | 0.61%   |
| Wilocity                        | 1         | 0.31%   |
| Sierra Wireless                 | 1         | 0.31%   |
| Qualcomm Atheros Communications | 1         | 0.31%   |
| NetGear                         | 1         | 0.31%   |
| Microsoft                       | 1         | 0.31%   |
| D-Link                          | 1         | 0.31%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                           | Computers | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                             | 17        | 5.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                        | 16        | 4.86%   |
| Intel Wireless 8265 / 8275                                                      | 15        | 4.56%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                       | 15        | 4.56%   |
| Intel Wi-Fi 6 AX201                                                             | 15        | 4.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                        | 13        | 3.95%   |
| Intel Wireless 8260                                                             | 13        | 3.95%   |
| Intel Wireless 7260                                                             | 12        | 3.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                        | 11        | 3.34%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                | 8         | 2.43%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                      | 7         | 2.13%   |
| Intel Wireless 7265                                                             | 7         | 2.13%   |
| Intel Comet Lake PCH CNVi WiFi                                                  | 7         | 2.13%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                 | 6         | 1.82%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]            | 6         | 1.82%   |
| Intel Raptor Lake PCH CNVi WiFi                                                 | 6         | 1.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                               | 6         | 1.82%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                        | 5         | 1.52%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                       | 5         | 1.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                      | 5         | 1.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                      | 5         | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                                 | 5         | 1.52%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                      | 4         | 1.22%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                   | 4         | 1.22%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                          | 3         | 0.91%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                         | 3         | 0.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                 | 3         | 0.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                | 3         | 0.91%   |
| MediaTek MT7925 802.11be 160MHz 2x2 PCIe Wireless Network Adapter [Filogic 360] | 3         | 0.91%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                         | 3         | 0.91%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]            | 3         | 0.91%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                               | 3         | 0.91%   |
| Intel Wireless 3165                                                             | 3         | 0.91%   |
| Intel Wireless 3160                                                             | 3         | 0.91%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                         | 3         | 0.91%   |
| Intel Centrino Ultimate-N 6300                                                  | 3         | 0.91%   |
| Intel Centrino Advanced-N 6235                                                  | 3         | 0.91%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                    | 3         | 0.91%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter            | 3         | 0.91%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                     | 3         | 0.91%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 131       | 45.96%  |
| Intel                    | 106       | 37.19%  |
| Broadcom                 | 10        | 3.51%   |
| ASIX Electronics         | 9         | 3.16%   |
| Qualcomm Atheros         | 8         | 2.81%   |
| Xiaomi                   | 4         | 1.4%    |
| Marvell Technology Group | 3         | 1.05%   |
| Nvidia                   | 2         | 0.7%    |
| MediaTek                 | 2         | 0.7%    |
| Aquantia                 | 2         | 0.7%    |
| VIA Technologies         | 1         | 0.35%   |
| Samsung Electronics      | 1         | 0.35%   |
| Qualcomm                 | 1         | 0.35%   |
| QinHeng Electronics      | 1         | 0.35%   |
| Motorola PCS             | 1         | 0.35%   |
| Lenovo                   | 1         | 0.35%   |
| Google                   | 1         | 0.35%   |
| American Megatrends      | 1         | 0.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 87        | 28.9%   |
| Realtek RTL8125 2.5GbE Controller                                      | 18        | 5.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 17        | 5.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 11        | 3.65%   |
| Intel Ethernet Controller I225-V                                       | 9         | 2.99%   |
| ASIX AX88179 Gigabit Ethernet                                          | 9         | 2.99%   |
| Intel Ethernet Connection I219-LM                                      | 8         | 2.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 2.66%   |
| Intel Ethernet Connection I217-LM                                      | 7         | 2.33%   |
| Intel I210 Gigabit Network Connection                                  | 6         | 1.99%   |
| Intel Ethernet Connection (4) I219-LM                                  | 5         | 1.66%   |
| Intel Ethernet Connection (2) I219-V                                   | 5         | 1.66%   |
| Intel 82579V Gigabit Network Connection                                | 5         | 1.66%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 4         | 1.33%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 4         | 1.33%   |
| Intel I211 Gigabit Network Connection                                  | 4         | 1.33%   |
| Intel Ethernet Controller I226-V                                       | 4         | 1.33%   |
| Intel Ethernet Connection I218-LM                                      | 4         | 1.33%   |
| Intel Ethernet Connection (4) I219-V                                   | 4         | 1.33%   |
| Intel Ethernet Connection (2) I219-LM                                  | 4         | 1.33%   |
| Intel Ethernet Connection (7) I219-V                                   | 3         | 1%      |
| Intel Ethernet Connection (6) I219-LM                                  | 3         | 1%      |
| Intel Ethernet Connection (2) I218-V                                   | 3         | 1%      |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 3         | 1%      |
| Intel 82577LM Gigabit Network Connection                               | 3         | 1%      |
| Realtek Killer E2600 GbE Controller                                    | 2         | 0.66%   |
| Intel Ethernet Controller X710 for 10GBASE-T                           | 2         | 0.66%   |
| Intel Ethernet Connection I217-V                                       | 2         | 0.66%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 0.66%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 0.66%   |
| Intel Ethernet Connection (17) I219-V                                  | 2         | 0.66%   |
| Intel Ethernet Connection (14) I219-V                                  | 2         | 0.66%   |
| Intel Ethernet Connection (10) I219-V                                  | 2         | 0.66%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 0.66%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2         | 0.66%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                       | 2         | 0.66%   |
| VIA VT6105/VT6106S [Rhine-III]                                         | 1         | 0.33%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.33%   |
| Realtek USB 10/100/1G/2.5 LAN                                          | 1         | 0.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 307       | 52.57%  |
| Ethernet | 266       | 45.55%  |
| Modem    | 10        | 1.71%   |
| Unknown  | 1         | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 250       | 68.49%  |
| Ethernet | 115       | 31.51%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 193       | 53.46%  |
| 1     | 147       | 40.72%  |
| 3     | 13        | 3.6%    |
| 0     | 5         | 1.39%   |
| 8     | 1         | 0.28%   |
| 6     | 1         | 0.28%   |
| 4     | 1         | 0.28%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 258       | 70.3%   |
| Yes  | 109       | 29.7%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 151       | 52.98%  |
| Realtek Semiconductor           | 31        | 10.88%  |
| IMC Networks                    | 19        | 6.67%   |
| Qualcomm Atheros Communications | 14        | 4.91%   |
| Apple                           | 11        | 3.86%   |
| Foxconn / Hon Hai               | 10        | 3.51%   |
| Cambridge Silicon Radio         | 8         | 2.81%   |
| Broadcom                        | 7         | 2.46%   |
| MediaTek                        | 6         | 2.11%   |
| Ralink                          | 5         | 1.75%   |
| ASUSTek Computer                | 5         | 1.75%   |
| Toshiba                         | 4         | 1.4%    |
| Marvell Semiconductor           | 3         | 1.05%   |
| Lite-On Technology              | 3         | 1.05%   |
| Hewlett-Packard                 | 2         | 0.7%    |
| Dell                            | 2         | 0.7%    |
| Unknown                         | 2         | 0.7%    |
| TP-Link                         | 1         | 0.35%   |
| Realtek                         | 1         | 0.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 44        | 15.38%  |
| Intel AX201 Bluetooth                                 | 27        | 9.44%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 26        | 9.09%   |
| Realtek Bluetooth Radio                               | 21        | 7.34%   |
| Intel Bluetooth Device                                | 18        | 6.29%   |
| Intel AX200 Bluetooth                                 | 17        | 5.94%   |
| Intel AX210 Bluetooth                                 | 14        | 4.9%    |
| IMC Networks Bluetooth Radio                          | 11        | 3.85%   |
| IMC Networks Wireless_Device                          | 8         | 2.8%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 8         | 2.8%    |
| Realtek  Bluetooth 4.2 Adapter                        | 7         | 2.45%   |
| Qualcomm Atheros  Bluetooth Device                    | 6         | 2.1%    |
| MediaTek Wireless_Device                              | 6         | 2.1%    |
| Apple Bluetooth USB Host Controller                   | 6         | 2.1%    |
| Ralink RT3290 Bluetooth                               | 5         | 1.75%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 3         | 1.05%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 3         | 1.05%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 3         | 1.05%   |
| Foxconn / Hon Hai Wireless_Device                     | 3         | 1.05%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter          | 3         | 1.05%   |
| Foxconn / Hon Hai Bluetooth Device                    | 3         | 1.05%   |
| Toshiba Bluetooth USB Host Controller                 | 2         | 0.7%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter               | 2         | 0.7%    |
| Qualcomm Atheros AR3011 Bluetooth                     | 2         | 0.7%    |
| Marvell Bluetooth and Wireless LAN Composite          | 2         | 0.7%    |
| HP Broadcom 2070 Bluetooth Combo                      | 2         | 0.7%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]            | 2         | 0.7%    |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 2         | 0.7%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 2         | 0.7%    |
| Apple Bluetooth Host Controller                       | 2         | 0.7%    |
| Unknown                                               | 2         | 0.7%    |
| TP-Link TP-T@- UB500 Adapter                          | 1         | 0.35%   |
| Toshiba RT Bluetooth Radio                            | 1         | 0.35%   |
| Toshiba Integrated Bluetooth HCI                      | 1         | 0.35%   |
| Realtek RTL8821A Bluetooth                            | 1         | 0.35%   |
| Realtek Bluetooth Radio                               | 1         | 0.35%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 1         | 0.35%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1         | 0.35%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 1         | 0.35%   |
| Marvell Bluetooth and Wireless LAN Composite Device   | 1         | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 281       | 55.98%  |
| Nvidia                                       | 100       | 19.92%  |
| AMD                                          | 78        | 15.54%  |
| ASUSTek Computer                             | 7         | 1.39%   |
| Logitech                                     | 5         | 1%      |
| JMTek                                        | 4         | 0.8%    |
| SteelSeries ApS                              | 3         | 0.6%    |
| Lenovo                                       | 3         | 0.6%    |
| Razer USA                                    | 2         | 0.4%    |
| C-Media Electronics                          | 2         | 0.4%    |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.2%    |
| XMOS                                         | 1         | 0.2%    |
| Telink                                       | 1         | 0.2%    |
| Solid State Logic                            | 1         | 0.2%    |
| Samsung Electronics                          | 1         | 0.2%    |
| Realtek Semiconductor                        | 1         | 0.2%    |
| Plantronics                                  | 1         | 0.2%    |
| Nordic Semiconductor ASA                     | 1         | 0.2%    |
| Micro Star International                     | 1         | 0.2%    |
| M2Tech                                       | 1         | 0.2%    |
| Linux Foundation                             | 1         | 0.2%    |
| Kingston Technology                          | 1         | 0.2%    |
| Hewlett-Packard                              | 1         | 0.2%    |
| Griffin Technology                           | 1         | 0.2%    |
| Dell                                         | 1         | 0.2%    |
| Apple                                        | 1         | 0.2%    |
| Apogee Electronics                           | 1         | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                              | 42        | 7.22%   |
| Intel Sunrise Point-LP HD Audio                                            | 37        | 6.36%   |
| AMD Radeon High Definition Audio Controller                                | 27        | 4.64%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 20        | 3.44%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 19        | 3.26%   |
| Intel Cannon Lake PCH cAVS                                                 | 19        | 3.26%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 18        | 3.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 18        | 3.09%   |
| Intel Haswell-ULT HD Audio Controller                                      | 15        | 2.58%   |
| Intel 8 Series HD Audio Controller                                         | 15        | 2.58%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 13        | 2.23%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 12        | 2.06%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 12        | 2.06%   |
| Nvidia GA106 High Definition Audio Controller                              | 11        | 1.89%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11        | 1.89%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 10        | 1.72%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 9         | 1.55%   |
| Intel Comet Lake PCH-LP cAVS                                               | 9         | 1.55%   |
| Intel Comet Lake PCH cAVS                                                  | 9         | 1.55%   |
| Intel Broadwell-U Audio Controller                                         | 9         | 1.55%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8         | 1.37%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8         | 1.37%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 1.37%   |
| Intel 200 Series PCH HD Audio                                              | 7         | 1.2%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 1.03%   |
| Nvidia TU104 HD Audio Controller                                           | 6         | 1.03%   |
| Nvidia GA104 High Definition Audio Controller                              | 6         | 1.03%   |
| Nvidia AD107 High Definition Audio Controller                              | 6         | 1.03%   |
| ASUSTek Computer USB Audio                                                 | 6         | 1.03%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6         | 1.03%   |
| Nvidia GP106 High Definition Audio Controller                              | 5         | 0.86%   |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 0.86%   |
| Nvidia GA102 High Definition Audio Controller                              | 5         | 0.86%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5         | 0.86%   |
| Intel CM238 HD Audio Controller                                            | 5         | 0.86%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 5         | 0.86%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 5         | 0.86%   |
| Nvidia GP104 High Definition Audio Controller                              | 4         | 0.69%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4         | 0.69%   |
| Nvidia GA107 High Definition Audio Controller                              | 4         | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 64        | 32.16%  |
| SK hynix               | 35        | 17.59%  |
| Micron Technology      | 32        | 16.08%  |
| Crucial                | 18        | 9.05%   |
| Kingston               | 11        | 5.53%   |
| Corsair                | 11        | 5.53%   |
| Unknown                | 5         | 2.51%   |
| Ramaxel Technology     | 4         | 2.01%   |
| G.Skill                | 3         | 1.51%   |
| Unknown                | 3         | 1.51%   |
| Timetec                | 2         | 1.01%   |
| Team                   | 2         | 1.01%   |
| Gold Key               | 2         | 1.01%   |
| Wilk                   | 1         | 0.5%    |
| Unknown (0000000080CE) | 1         | 0.5%    |
| Nanya Technology       | 1         | 0.5%    |
| Lexar                  | 1         | 0.5%    |
| Innodisk               | 1         | 0.5%    |
| A-DATA Technology      | 1         | 0.5%    |
| 4ea5                   | 1         | 0.5%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                    | 5         | 2.27%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s                    | 4         | 1.82%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s                   | 3         | 1.36%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s                    | 3         | 1.36%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s                     | 3         | 1.36%   |
| Unknown                                                                  | 3         | 1.36%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                   | 2         | 0.91%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                   | 2         | 0.91%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                   | 2         | 0.91%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                    | 2         | 0.91%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                    | 2         | 0.91%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s                   | 2         | 0.91%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s                   | 2         | 0.91%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                    | 2         | 0.91%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s                    | 2         | 0.91%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s                    | 2         | 0.91%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s                    | 2         | 0.91%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s                  | 2         | 0.91%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s                | 2         | 0.91%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM DDR5 4800MT/s                  | 2         | 0.91%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                     | 2         | 0.91%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                     | 2         | 0.91%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s               | 2         | 0.91%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s                     | 2         | 0.91%   |
| Crucial RAM CT16G4SFRA32A.M8FF 16GB SODIMM DDR4 3200MT/s                 | 2         | 0.91%   |
| Crucial RAM CT16G4SFRA32A.M16FR 16GB SODIMM DDR4 3200MT/s                | 2         | 0.91%   |
| Wilk RAM W-HK32S32O 32GB SODIMM DDR4 3200MT/s                            | 1         | 0.45%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                                | 1         | 0.45%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2667MT/s                           | 1         | 0.45%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                               | 1         | 0.45%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                      | 1         | 0.45%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                                 | 1         | 0.45%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                               | 1         | 0.45%   |
| Unknown (0000000080CE) RAM M16GDR4SV03D32RA-SC 16GB SODIMM DDR4 3200MT/s | 1         | 0.45%   |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                            | 1         | 0.45%   |
| Timetec RAM S8G-1600 8GB SODIMM DDR3 1600MT/s                            | 1         | 0.45%   |
| Timetec RAM S8G-1600 8GB Chip DDR3 1600MT/s                              | 1         | 0.45%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s                       | 1         | 0.45%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s                       | 1         | 0.45%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s                     | 1         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 98        | 58.68%  |
| DDR3    | 33        | 19.76%  |
| DDR5    | 15        | 8.98%   |
| LPDDR5  | 7         | 4.19%   |
| LPDDR4  | 5         | 2.99%   |
| LPDDR3  | 5         | 2.99%   |
| DDR2    | 3         | 1.8%    |
| Unknown | 1         | 0.6%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 112       | 65.5%   |
| DIMM         | 33        | 19.3%   |
| Row Of Chips | 22        | 12.87%  |
| Chip         | 3         | 1.75%   |
| Unknown      | 1         | 0.58%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 78        | 40.84%  |
| 16384 | 45        | 23.56%  |
| 4096  | 34        | 17.8%   |
| 32768 | 15        | 7.85%   |
| 2048  | 12        | 6.28%   |
| 65536 | 3         | 1.57%   |
| 49152 | 2         | 1.05%   |
| 24576 | 1         | 0.52%   |
| 1024  | 1         | 0.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 52        | 27.66%  |
| 2667  | 33        | 17.55%  |
| 1600  | 20        | 10.64%  |
| 2400  | 11        | 5.85%   |
| 2133  | 11        | 5.85%   |
| 4800  | 8         | 4.26%   |
| 6400  | 5         | 2.66%   |
| 5600  | 5         | 2.66%   |
| 1333  | 5         | 2.66%   |
| 1334  | 4         | 2.13%   |
| 7500  | 3         | 1.6%    |
| 4267  | 3         | 1.6%    |
| 8400  | 2         | 1.06%   |
| 3800  | 2         | 1.06%   |
| 3733  | 2         | 1.06%   |
| 3600  | 2         | 1.06%   |
| 3400  | 2         | 1.06%   |
| 3000  | 2         | 1.06%   |
| 1867  | 2         | 1.06%   |
| 1866  | 2         | 1.06%   |
| 1067  | 2         | 1.06%   |
| 667   | 2         | 1.06%   |
| 7467  | 1         | 0.53%   |
| 6200  | 1         | 0.53%   |
| 4266  | 1         | 0.53%   |
| 3466  | 1         | 0.53%   |
| 2933  | 1         | 0.53%   |
| 2666  | 1         | 0.53%   |
| 1450  | 1         | 0.53%   |
| 800   | 1         | 0.53%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 2         | 40%     |
| Canon              | 2         | 40%     |
| Brother Industries | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                     | Computers | Percent |
|---------------------------|-----------|---------|
| HP Deskjet F2280 series   | 1         | 20%     |
| HP DeskJet 2300 series    | 1         | 20%     |
| Canon TR150 series        | 1         | 20%     |
| Canon PIXMA MG3600 Series | 1         | 20%     |
| Brother MFC-9330CDW       | 1         | 20%     |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 62        | 24.8%   |
| IMC Networks                           | 26        | 10.4%   |
| Bison Electronics                      | 20        | 8%      |
| Microdia                               | 16        | 6.4%    |
| Sunplus Innovation Technology          | 14        | 5.6%    |
| Syntek                                 | 13        | 5.2%    |
| Apple                                  | 13        | 5.2%    |
| Luxvisions Innotech Limited            | 12        | 4.8%    |
| Cheng Uei Precision Industry (Foxlink) | 12        | 4.8%    |
| Realtek Semiconductor                  | 11        | 4.4%    |
| Quanta                                 | 9         | 3.6%    |
| Lite-On Technology                     | 5         | 2%      |
| Samsung Electronics                    | 4         | 1.6%    |
| Sonix Technology                       | 3         | 1.2%    |
| Ricoh                                  | 3         | 1.2%    |
| Microsoft                              | 3         | 1.2%    |
| Logitech                               | 3         | 1.2%    |
| Creative Technology                    | 3         | 1.2%    |
| Alcor Micro                            | 3         | 1.2%    |
| Suyin                                  | 2         | 0.8%    |
| Shinetech                              | 2         | 0.8%    |
| Z-Star Microelectronics                | 1         | 0.4%    |
| Tobii Technology AB                    | 1         | 0.4%    |
| SunplusIT                              | 1         | 0.4%    |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.4%    |
| Ruision                                | 1         | 0.4%    |
| LG Electronics                         | 1         | 0.4%    |
| Lenovo                                 | 1         | 0.4%    |
| KYE Systems (Mouse Systems)            | 1         | 0.4%    |
| kingcome                               | 1         | 0.4%    |
| Google                                 | 1         | 0.4%    |
| Anker PowerConf C200                   | 1         | 0.4%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 26        | 10.36%  |
| Syntek Integrated Camera                                        | 12        | 4.78%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 12        | 4.78%   |
| Microdia Integrated_Webcam_HD                                   | 9         | 3.59%   |
| Sunplus Integrated_Webcam_HD                                    | 7         | 2.79%   |
| IMC Networks Integrated Camera                                  | 7         | 2.79%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                 | 7         | 2.79%   |
| Bison Integrated Camera                                         | 6         | 2.39%   |
| Chicony Integrated Camera (1280x720@30)                         | 5         | 1.99%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 4         | 1.59%   |
| Realtek Integrated_Webcam_HD                                    | 4         | 1.59%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 4         | 1.59%   |
| Realtek HP Truevision HD                                        | 3         | 1.2%    |
| Quanta HP TrueVision HD Camera                                  | 3         | 1.2%    |
| Luxvisions Innotech Limited Integrated Camera                   | 3         | 1.2%    |
| Luxvisions Innotech Limited HP Wide Vision HD Camera            | 3         | 1.2%    |
| Logitech Webcam C270                                            | 3         | 1.2%    |
| Lite-On HP Wide Vision HD Camera                                | 3         | 1.2%    |
| Chicony HP Wide Vision HD Camera                                | 3         | 1.2%    |
| Chicony EasyCamera                                              | 3         | 1.2%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 3         | 1.2%    |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 3         | 1.2%    |
| Bison BisonCam,NB Pro                                           | 3         | 1.2%    |
| Sunplus HP HD Webcam [Fixed]                                    | 2         | 0.8%    |
| Sonix USB2.0 HD UVC WebCam                                      | 2         | 0.8%    |
| Shinetech ASUS FHD webcam                                       | 2         | 0.8%    |
| Ricoh HD Webcam                                                 | 2         | 0.8%    |
| Microdia Laptop_Integrated_Webcam_HD                            | 2         | 0.8%    |
| Microdia Integrated Webcam                                      | 2         | 0.8%    |
| Lite-On HP HD Camera                                            | 2         | 0.8%    |
| Chicony TOSHIBA Web Camera - HD                                 | 2         | 0.8%    |
| Chicony TOSHIBA Web Camera - FHD                                | 2         | 0.8%    |
| Chicony ThinkPad T490 Webcam                                    | 2         | 0.8%    |
| Chicony Lenovo EasyCamera                                       | 2         | 0.8%    |
| Chicony HP Truevision HD                                        | 2         | 0.8%    |
| Chicony HP HD Webcam [Fixed]                                    | 2         | 0.8%    |
| Chicony HP HD Webcam                                            | 2         | 0.8%    |
| Chicony HD WebCam                                               | 2         | 0.8%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam             | 2         | 0.8%    |
| Bison SunplusIT Integrated Camera                               | 2         | 0.8%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 32        | 43.24%  |
| Validity Sensors                   | 24        | 32.43%  |
| Shenzhen Goodix Technology         | 7         | 9.46%   |
| Elan Microelectronics              | 7         | 9.46%   |
| STMicroelectronics                 | 2         | 2.7%    |
| Realtek USB2.0 Finger Print Bridge | 1         | 1.35%   |
| LighTuning Technology              | 1         | 1.35%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 9         | 12.16%  |
| Validity Sensors Synaptics WBDI                                 | 8         | 10.81%  |
| Elan ELAN:ARM-M4                                                | 7         | 9.46%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 5         | 6.76%   |
| Shenzhen Goodix Fingerprint Reader                              | 4         | 5.41%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 3         | 4.05%   |
| Synaptics WBDI                                                  | 3         | 4.05%   |
| Synaptics UWP WBDI Device                                       | 3         | 4.05%   |
| Synaptics UWP WBDI                                              | 3         | 4.05%   |
| Synaptics Prometheus Fingerprint Reader                         | 3         | 4.05%   |
| Shenzhen Goodix  Fingerprint Device                             | 3         | 4.05%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 2         | 2.7%    |
| Validity Sensors VFS495 Fingerprint Reader                      | 2         | 2.7%    |
| Validity Sensors VFS491                                         | 2         | 2.7%    |
| Synaptics Fingerprint reader [HP G6]                            | 2         | 2.7%    |
| STMicroelectronics Fingerprint Reader                           | 2         | 2.7%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor               | 1         | 1.35%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 1         | 1.35%   |
| Validity Sensors VFS Fingerprint sensor                         | 1         | 1.35%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 1         | 1.35%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor     | 1         | 1.35%   |
| Validity Sensors Swipe Fingerprint Sensor                       | 1         | 1.35%   |
| Validity Sensors Fingerprint scanner                            | 1         | 1.35%   |
| Synaptics WBDI Fingerprint Reader USB 086                       | 1         | 1.35%   |
| Synaptics TouchPad                                              | 1         | 1.35%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint       | 1         | 1.35%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                | 1         | 1.35%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 1.35%   |
| LighTuning Fingerprint Sensor                                   | 1         | 1.35%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 7         | 46.67%  |
| Broadcom    | 5         | 33.33%  |
| Upek        | 2         | 13.33%  |
| Aktiv       | 1         | 6.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 46.67%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 13.33%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 13.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 6.67%   |
| Broadcom 5880                                                                | 1         | 6.67%   |
| Broadcom 58200                                                               | 1         | 6.67%   |
| Aktiv Rutoken lite                                                           | 1         | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 203       | 55.16%  |
| 1     | 121       | 32.88%  |
| 2     | 33        | 8.97%   |
| 3     | 11        | 2.99%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 70        | 33.49%  |
| Graphics card            | 49        | 23.44%  |
| Net/wireless             | 24        | 11.48%  |
| Multimedia controller    | 18        | 8.61%   |
| Chipcard                 | 13        | 6.22%   |
| Camera                   | 10        | 4.78%   |
| Communication controller | 6         | 2.87%   |
| Bluetooth                | 5         | 2.39%   |
| Unassigned class         | 4         | 1.91%   |
| Sound                    | 4         | 1.91%   |
| Wireless                 | 2         | 0.96%   |
| Network                  | 1         | 0.48%   |
| Net/ethernet             | 1         | 0.48%   |
| Modem                    | 1         | 0.48%   |
| Card reader              | 1         | 0.48%   |

