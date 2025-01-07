Lubuntu - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Lubuntu.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Lubuntu/Desktop/README.md) and [notebooks](/Dist/Lubuntu/Notebook/README.md).

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

Total: 2511

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | MS-77311                    | Desktop     | [f7f9b1ae97](https://linux-hardware.org/?probe=f7f9b1ae97) | Jan 04, 2025 |
| ABIT          | AT8 32X                     | Desktop     | [e613a45614](https://linux-hardware.org/?probe=e613a45614) | Jan 03, 2025 |
| Dell          | 0N4YC8 A00                  | Desktop     | [f722edf7a9](https://linux-hardware.org/?probe=f722edf7a9) | Jan 01, 2025 |
| HP            | Pavilion g7                 | Notebook    | [5692787b6f](https://linux-hardware.org/?probe=5692787b6f) | Dec 31, 2024 |
| Acer          | Aspire A114-32              | Notebook    | [d4aff4e66c](https://linux-hardware.org/?probe=d4aff4e66c) | Dec 30, 2024 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [37872e53dc](https://linux-hardware.org/?probe=37872e53dc) | Dec 30, 2024 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [0dc9a2432a](https://linux-hardware.org/?probe=0dc9a2432a) | Dec 30, 2024 |
| ASUSTek       | A78M-A                      | Desktop     | [1c59a39f39](https://linux-hardware.org/?probe=1c59a39f39) | Dec 30, 2024 |
| HP            | Notebook                    | Notebook    | [fb6c3eebe1](https://linux-hardware.org/?probe=fb6c3eebe1) | Dec 29, 2024 |
| Unchartevi... | 6540                        | Notebook    | [1d27092258](https://linux-hardware.org/?probe=1d27092258) | Dec 29, 2024 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [5099a4c834](https://linux-hardware.org/?probe=5099a4c834) | Dec 28, 2024 |
| Lenovo        | SHARKBAY 0B98417 WIN        | Desktop     | [8c5e303e5b](https://linux-hardware.org/?probe=8c5e303e5b) | Dec 27, 2024 |
| Unknown       | Unknown                     | Notebook    | [dae997fee3](https://linux-hardware.org/?probe=dae997fee3) | Dec 26, 2024 |
| Dell          | 0200DY A01                  | Desktop     | [fa349ac11f](https://linux-hardware.org/?probe=fa349ac11f) | Dec 23, 2024 |
| Dell          | Inspiron 1545               | Notebook    | [9cc6330a09](https://linux-hardware.org/?probe=9cc6330a09) | Dec 21, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [19e00fa4e5](https://linux-hardware.org/?probe=19e00fa4e5) | Dec 21, 2024 |
| ASUSTek       | A78M-A                      | Desktop     | [efa5a4e952](https://linux-hardware.org/?probe=efa5a4e952) | Dec 21, 2024 |
| Dell          | System XPS 15Z              | Notebook    | [9e7fc2d36e](https://linux-hardware.org/?probe=9e7fc2d36e) | Dec 20, 2024 |
| ASUSTek       | X550CL                      | Notebook    | [ca719e1a32](https://linux-hardware.org/?probe=ca719e1a32) | Dec 20, 2024 |
| Lenovo        | SHARKBAY 0B98417 WIN        | Desktop     | [78c7a48933](https://linux-hardware.org/?probe=78c7a48933) | Dec 20, 2024 |
| Medion        | S6421 MD60703               | Notebook    | [609c73a176](https://linux-hardware.org/?probe=609c73a176) | Dec 19, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | Notebook    | [bc07631f18](https://linux-hardware.org/?probe=bc07631f18) | Dec 18, 2024 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [0f9a0492e2](https://linux-hardware.org/?probe=0f9a0492e2) | Dec 18, 2024 |
| Gigabyte      | B550M S2H                   | Desktop     | [e32011dedf](https://linux-hardware.org/?probe=e32011dedf) | Dec 18, 2024 |
| Lenovo        | IdeaPad S405 9802           | Notebook    | [10b9693723](https://linux-hardware.org/?probe=10b9693723) | Dec 17, 2024 |
| Lenovo        | IdeaPad S405 9802           | Notebook    | [3a61babe21](https://linux-hardware.org/?probe=3a61babe21) | Dec 17, 2024 |
| Foxconn       | G31MX Series                | Desktop     | [bdb6d7f31e](https://linux-hardware.org/?probe=bdb6d7f31e) | Dec 15, 2024 |
| Packard Be... | DOT S                       | Notebook    | [60865a1411](https://linux-hardware.org/?probe=60865a1411) | Dec 14, 2024 |
| HP            | EliteBook 835 13 inch G1... | Notebook    | [501650199f](https://linux-hardware.org/?probe=501650199f) | Dec 12, 2024 |
| HP            | 2000                        | Notebook    | [3c20e6e18c](https://linux-hardware.org/?probe=3c20e6e18c) | Dec 11, 2024 |
| Unknown       | ROUTER                      | Desktop     | [c6bf9058fa](https://linux-hardware.org/?probe=c6bf9058fa) | Dec 10, 2024 |
| Fujitsu Si... | ESPRIMO Mobile V6555        | Notebook    | [291861d530](https://linux-hardware.org/?probe=291861d530) | Dec 08, 2024 |
| Dell          | Inspiron 15-3567            | Notebook    | [cbf6bf1b48](https://linux-hardware.org/?probe=cbf6bf1b48) | Dec 06, 2024 |
| ASUSTek       | M5A88-M                     | Desktop     | [520539e9f6](https://linux-hardware.org/?probe=520539e9f6) | Dec 01, 2024 |
| HP            | Laptop 15-db0xxx            | Notebook    | [469069638e](https://linux-hardware.org/?probe=469069638e) | Dec 01, 2024 |
| Google        | Candy                       | Notebook    | [035e637f3d](https://linux-hardware.org/?probe=035e637f3d) | Dec 01, 2024 |
| Lenovo        | 3722 No DPK                 | All in one  | [ed6a0b64aa](https://linux-hardware.org/?probe=ed6a0b64aa) | Nov 26, 2024 |
| Foxconn       | G31MV/G31MV-K FAB           | Desktop     | [95b6ff9464](https://linux-hardware.org/?probe=95b6ff9464) | Nov 25, 2024 |
| Acer          | AO722                       | Notebook    | [15b4d05c90](https://linux-hardware.org/?probe=15b4d05c90) | Nov 25, 2024 |
| Acer          | AO722                       | Notebook    | [f5300839f0](https://linux-hardware.org/?probe=f5300839f0) | Nov 25, 2024 |
| Apple         | MacBook5,1                  | Notebook    | [c9bc1374b3](https://linux-hardware.org/?probe=c9bc1374b3) | Nov 25, 2024 |
| Google        | Candy                       | Notebook    | [cac90e3ac0](https://linux-hardware.org/?probe=cac90e3ac0) | Nov 25, 2024 |
| Dell          | 096JG8 A01                  | Desktop     | [a61d2e5e14](https://linux-hardware.org/?probe=a61d2e5e14) | Nov 25, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [1299c66f0d](https://linux-hardware.org/?probe=1299c66f0d) | Nov 24, 2024 |
| Google        | Candy                       | Notebook    | [0cb5a31970](https://linux-hardware.org/?probe=0cb5a31970) | Nov 23, 2024 |
| Sony          | M730                        | Notebook    | [55d7e62f9d](https://linux-hardware.org/?probe=55d7e62f9d) | Nov 23, 2024 |
| HP            | 097Ch                       | Desktop     | [a95a57c236](https://linux-hardware.org/?probe=a95a57c236) | Nov 22, 2024 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [6c171fbbd4](https://linux-hardware.org/?probe=6c171fbbd4) | Nov 22, 2024 |
| HP            | Notebook                    | Notebook    | [bb9e0faf8f](https://linux-hardware.org/?probe=bb9e0faf8f) | Nov 22, 2024 |
| MSI           | H410M BOMBER                | Desktop     | [0fdf3b3e0b](https://linux-hardware.org/?probe=0fdf3b3e0b) | Nov 21, 2024 |
| MSI           | H410M BOMBER                | Desktop     | [97ed06f147](https://linux-hardware.org/?probe=97ed06f147) | Nov 21, 2024 |
| ASUSTek       | PRIME H510M-E R2.0          | Desktop     | [98d4a70c46](https://linux-hardware.org/?probe=98d4a70c46) | Nov 20, 2024 |
| Medion        | E122X                       | Notebook    | [e7c29c8ff7](https://linux-hardware.org/?probe=e7c29c8ff7) | Nov 19, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [ba64567726](https://linux-hardware.org/?probe=ba64567726) | Nov 18, 2024 |
| Dell          | Inspiron 15-3567            | Notebook    | [815225e627](https://linux-hardware.org/?probe=815225e627) | Nov 18, 2024 |
| ECS           | RS480-M                     | Desktop     | [5c9a33d3ef](https://linux-hardware.org/?probe=5c9a33d3ef) | Nov 18, 2024 |
| Medion        | E3215 MD60929               | Convertible | [4445d09a20](https://linux-hardware.org/?probe=4445d09a20) | Nov 17, 2024 |
| HP            | 1905                        | Desktop     | [603e331581](https://linux-hardware.org/?probe=603e331581) | Nov 17, 2024 |
| Apple         | MacBook5,1                  | Notebook    | [fc4768f63d](https://linux-hardware.org/?probe=fc4768f63d) | Nov 17, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [61b4034745](https://linux-hardware.org/?probe=61b4034745) | Nov 17, 2024 |
| HP            | 1589                        | Desktop     | [b620b573ed](https://linux-hardware.org/?probe=b620b573ed) | Nov 16, 2024 |
| AOpen         | i67QMx-HA R1.03 55DE6100... | Desktop     | [09be9e2bee](https://linux-hardware.org/?probe=09be9e2bee) | Nov 16, 2024 |
| AOpen         | i67QMx-HA R1.03 55DE6100... | Desktop     | [727094dd28](https://linux-hardware.org/?probe=727094dd28) | Nov 16, 2024 |
| Dell          | XPS MXC062                  | Notebook    | [bb0597c639](https://linux-hardware.org/?probe=bb0597c639) | Nov 15, 2024 |
| Dell          | XPS MXC062                  | Notebook    | [fbc63bd772](https://linux-hardware.org/?probe=fbc63bd772) | Nov 15, 2024 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [342d578a5c](https://linux-hardware.org/?probe=342d578a5c) | Nov 13, 2024 |
| Apple         | Mac-F2218FC8                | All in one  | [c9ef441418](https://linux-hardware.org/?probe=c9ef441418) | Nov 11, 2024 |
| Acer          | Aspire ES1-531              | Notebook    | [a7c11e81f1](https://linux-hardware.org/?probe=a7c11e81f1) | Nov 09, 2024 |
| HP            | ProBook 430 G2              | Notebook    | [ea645a6ae1](https://linux-hardware.org/?probe=ea645a6ae1) | Nov 08, 2024 |
| Fujitsu Si... | AMILO A7645                 | Notebook    | [82b3b117c2](https://linux-hardware.org/?probe=82b3b117c2) | Nov 08, 2024 |
| Supermicro    | X8DTT-H                     | Server      | [05f8ebdf95](https://linux-hardware.org/?probe=05f8ebdf95) | Nov 06, 2024 |
| ADI           | MinnowBoard Turbot          | Desktop     | [bc4cd39271](https://linux-hardware.org/?probe=bc4cd39271) | Nov 05, 2024 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [67b92639b5](https://linux-hardware.org/?probe=67b92639b5) | Nov 05, 2024 |
| ASUSTek       | B85M-G                      | Desktop     | [ccd12bcd3a](https://linux-hardware.org/?probe=ccd12bcd3a) | Nov 03, 2024 |
| Sony          | VPCF132FX                   | Notebook    | [b584189661](https://linux-hardware.org/?probe=b584189661) | Nov 03, 2024 |
| Dell          | Latitude E7240              | Notebook    | [82e1ee846b](https://linux-hardware.org/?probe=82e1ee846b) | Nov 02, 2024 |
| Dell          | 0WJ772                      | Desktop     | [d6dc667160](https://linux-hardware.org/?probe=d6dc667160) | Nov 01, 2024 |
| Intel         | H61                         | Desktop     | [0e1936ef18](https://linux-hardware.org/?probe=0e1936ef18) | Oct 31, 2024 |
| Lenovo        | G770 20089                  | Notebook    | [3547cb6c29](https://linux-hardware.org/?probe=3547cb6c29) | Oct 30, 2024 |
| LG Electro... | X110-L.B7BLP1               | Notebook    | [a71f31873d](https://linux-hardware.org/?probe=a71f31873d) | Oct 29, 2024 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [6403f7199d](https://linux-hardware.org/?probe=6403f7199d) | Oct 29, 2024 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [d47c826466](https://linux-hardware.org/?probe=d47c826466) | Oct 28, 2024 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [125ef7ec35](https://linux-hardware.org/?probe=125ef7ec35) | Oct 27, 2024 |
| HP            | 245 G8 Notebook PC          | Notebook    | [8a3413b200](https://linux-hardware.org/?probe=8a3413b200) | Oct 26, 2024 |
| Lenovo        | IdeaPad 1 15IJL7 82LX       | Notebook    | [6028ccb88f](https://linux-hardware.org/?probe=6028ccb88f) | Oct 25, 2024 |
| Lenovo        | ThinkPad E15 20RD005VRT     | Notebook    | [0faadd1106](https://linux-hardware.org/?probe=0faadd1106) | Oct 24, 2024 |
| Toshiba       | Satellite C660              | Notebook    | [11806f6477](https://linux-hardware.org/?probe=11806f6477) | Oct 24, 2024 |
| Dell          | Latitude E5450              | Notebook    | [0465141d52](https://linux-hardware.org/?probe=0465141d52) | Oct 23, 2024 |
| Toshiba       | Satellite P55W-C            | Notebook    | [84c58de68f](https://linux-hardware.org/?probe=84c58de68f) | Oct 23, 2024 |
| Toshiba       | Satellite P55W-C            | Notebook    | [2fbe7927f9](https://linux-hardware.org/?probe=2fbe7927f9) | Oct 23, 2024 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [6e69e5e4a4](https://linux-hardware.org/?probe=6e69e5e4a4) | Oct 23, 2024 |
| HP            | EliteBook 2540p             | Notebook    | [53c668190f](https://linux-hardware.org/?probe=53c668190f) | Oct 23, 2024 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [7205fb0b92](https://linux-hardware.org/?probe=7205fb0b92) | Oct 23, 2024 |
| Dell          | Inspiron 1501               | Notebook    | [5ac3420a2b](https://linux-hardware.org/?probe=5ac3420a2b) | Oct 22, 2024 |
| HP            | Pavilion Laptop 15-cs315... | Notebook    | [c61e1c6184](https://linux-hardware.org/?probe=c61e1c6184) | Oct 22, 2024 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [df61da6a87](https://linux-hardware.org/?probe=df61da6a87) | Oct 22, 2024 |
| HP            | EliteBook 830 G6            | Notebook    | [f7d13716ee](https://linux-hardware.org/?probe=f7d13716ee) | Oct 22, 2024 |
| Medion        | S6421 MD60703               | Notebook    | [c92c3514b3](https://linux-hardware.org/?probe=c92c3514b3) | Oct 22, 2024 |
| Pegatron      | EVANS                       | Desktop     | [17c53eb7a7](https://linux-hardware.org/?probe=17c53eb7a7) | Oct 21, 2024 |
| Dell          | Latitude E5450              | Notebook    | [2ec7e21290](https://linux-hardware.org/?probe=2ec7e21290) | Oct 19, 2024 |
| Chuwi         | GemiBook Pro                | Notebook    | [be2a9177cc](https://linux-hardware.org/?probe=be2a9177cc) | Oct 19, 2024 |
| AZW           | LZX TBD                     | Desktop     | [f6d5bd13f2](https://linux-hardware.org/?probe=f6d5bd13f2) | Oct 17, 2024 |
| Haier         | ZEB19 V1.1                  | Desktop     | [beb67a0dab](https://linux-hardware.org/?probe=beb67a0dab) | Oct 17, 2024 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [dd98dbec76](https://linux-hardware.org/?probe=dd98dbec76) | Oct 17, 2024 |
| HP            | InsydeH2O EFI BIOS          | Notebook    | [3d33564930](https://linux-hardware.org/?probe=3d33564930) | Oct 16, 2024 |
| HP            | Compaq CQ58                 | Notebook    | [129913dcc6](https://linux-hardware.org/?probe=129913dcc6) | Oct 14, 2024 |
| ASUSTek       | A78M-A                      | Desktop     | [1eb695071c](https://linux-hardware.org/?probe=1eb695071c) | Oct 14, 2024 |
| ASUSTek       | A78M-A                      | Desktop     | [5629586c09](https://linux-hardware.org/?probe=5629586c09) | Oct 13, 2024 |
| Positivo      | C14CU51                     | Notebook    | [a50a121b61](https://linux-hardware.org/?probe=a50a121b61) | Oct 12, 2024 |
| HP            | 255 G5                      | Notebook    | [062ce32d62](https://linux-hardware.org/?probe=062ce32d62) | Oct 11, 2024 |
| HONOR         | NMH-WCX9                    | Notebook    | [03f4ff2833](https://linux-hardware.org/?probe=03f4ff2833) | Oct 09, 2024 |
| HONOR         | NMH-WCX9                    | Notebook    | [e167d1430c](https://linux-hardware.org/?probe=e167d1430c) | Oct 09, 2024 |
| Samsung       | 370E4K                      | Notebook    | [f87816505c](https://linux-hardware.org/?probe=f87816505c) | Oct 07, 2024 |
| Acer          | Aspire 5735                 | Notebook    | [4c1559410d](https://linux-hardware.org/?probe=4c1559410d) | Oct 06, 2024 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [fb9c9f4215](https://linux-hardware.org/?probe=fb9c9f4215) | Oct 06, 2024 |
| Acer          | Aspire 5735                 | Notebook    | [50e1561f7d](https://linux-hardware.org/?probe=50e1561f7d) | Oct 06, 2024 |
| Dell          | Vostro 1500                 | Notebook    | [6680201494](https://linux-hardware.org/?probe=6680201494) | Oct 06, 2024 |
| ASUSTek       | M4A78 PRO                   | Desktop     | [3fefc80707](https://linux-hardware.org/?probe=3fefc80707) | Oct 05, 2024 |
| Google        | Rabbid                      | Notebook    | [022398a237](https://linux-hardware.org/?probe=022398a237) | Oct 05, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [e15bff83db](https://linux-hardware.org/?probe=e15bff83db) | Oct 05, 2024 |
| HP            | EliteBook 2540p             | Notebook    | [582f0a4f04](https://linux-hardware.org/?probe=582f0a4f04) | Oct 04, 2024 |
| MSI           | MS-B0621 100                | All in one  | [3d6c67056e](https://linux-hardware.org/?probe=3d6c67056e) | Oct 04, 2024 |
| AZW           | MINI S                      | Desktop     | [2476470ecb](https://linux-hardware.org/?probe=2476470ecb) | Oct 04, 2024 |
| AMI           | Intel                       | Convertible | [375367c891](https://linux-hardware.org/?probe=375367c891) | Oct 03, 2024 |
| AZW           | MINI S                      | Desktop     | [b08901d4d7](https://linux-hardware.org/?probe=b08901d4d7) | Oct 03, 2024 |
| Dell          | Inspiron 1100               | Notebook    | [1012ad2903](https://linux-hardware.org/?probe=1012ad2903) | Oct 02, 2024 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [1faf24f4b7](https://linux-hardware.org/?probe=1faf24f4b7) | Oct 01, 2024 |
| Toshiba       | Satellite C660              | Notebook    | [1ce63743fd](https://linux-hardware.org/?probe=1ce63743fd) | Oct 01, 2024 |
| Apple         | MacBook4,1                  | Notebook    | [1b71a4b0c9](https://linux-hardware.org/?probe=1b71a4b0c9) | Oct 01, 2024 |
| Acer          | Spin SP513-53N              | Convertible | [e0a0689e0e](https://linux-hardware.org/?probe=e0a0689e0e) | Sep 28, 2024 |
| Lenovo        | ThinkPad T480s 20L8S3SW0... | Notebook    | [d3f2558562](https://linux-hardware.org/?probe=d3f2558562) | Sep 28, 2024 |
| ASUSTek       | X553MA                      | Notebook    | [a96b018191](https://linux-hardware.org/?probe=a96b018191) | Sep 25, 2024 |
| Lenovo        | MAHOBAY                     | Desktop     | [133a8522bd](https://linux-hardware.org/?probe=133a8522bd) | Sep 25, 2024 |
| MicroByte     | ezbook                      | Notebook    | [5b878e7b72](https://linux-hardware.org/?probe=5b878e7b72) | Sep 24, 2024 |
| Gateway       | IPISB-VR                    | Desktop     | [bc45b7939c](https://linux-hardware.org/?probe=bc45b7939c) | Sep 23, 2024 |
| AZW           | LZX TBD                     | Desktop     | [242bb69a07](https://linux-hardware.org/?probe=242bb69a07) | Sep 22, 2024 |
| HP            | Pavilion 15                 | Notebook    | [617c9c6fd3](https://linux-hardware.org/?probe=617c9c6fd3) | Sep 22, 2024 |
| HP            | Pavilion 15                 | Notebook    | [47d81a32ab](https://linux-hardware.org/?probe=47d81a32ab) | Sep 22, 2024 |
| ZOTAC         | ZBOX-RI323NANO              | Mini pc     | [28bf51645a](https://linux-hardware.org/?probe=28bf51645a) | Sep 21, 2024 |
| Positivo      | DC8BT11TV                   | All in one  | [02e77e625f](https://linux-hardware.org/?probe=02e77e625f) | Sep 19, 2024 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [273c5852ff](https://linux-hardware.org/?probe=273c5852ff) | Sep 18, 2024 |
| HP            | InsydeH2O EFI BIOS          | Notebook    | [7102de50a6](https://linux-hardware.org/?probe=7102de50a6) | Sep 17, 2024 |
| Dell          | Latitude E6410              | Notebook    | [92cd0e0eee](https://linux-hardware.org/?probe=92cd0e0eee) | Sep 17, 2024 |
| Dell          | Latitude E6410              | Notebook    | [d9385745e8](https://linux-hardware.org/?probe=d9385745e8) | Sep 17, 2024 |
| Dell          | Inspiron 1564               | Notebook    | [e2028cccf6](https://linux-hardware.org/?probe=e2028cccf6) | Sep 14, 2024 |
| AZW           | LZX TBD                     | Desktop     | [555138dd5b](https://linux-hardware.org/?probe=555138dd5b) | Sep 13, 2024 |
| Haier         | ZEB19 V1.1                  | Desktop     | [fc948e0f5d](https://linux-hardware.org/?probe=fc948e0f5d) | Sep 13, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [606582cd82](https://linux-hardware.org/?probe=606582cd82) | Sep 10, 2024 |
| Acer          | Aspire ES1-571              | Notebook    | [a5aeb5f264](https://linux-hardware.org/?probe=a5aeb5f264) | Sep 10, 2024 |
| Complet       | MY8305                      | Notebook    | [fdab3231de](https://linux-hardware.org/?probe=fdab3231de) | Sep 07, 2024 |
| Samsung       | RV415                       | Notebook    | [e3d0816997](https://linux-hardware.org/?probe=e3d0816997) | Sep 07, 2024 |
| Fujitsu Si... | D2151-A2 S26361-D2151-A2    | Desktop     | [d15a8e878e](https://linux-hardware.org/?probe=d15a8e878e) | Sep 06, 2024 |
| Chuwi         | HeroBook Air                | Notebook    | [09a139dbbe](https://linux-hardware.org/?probe=09a139dbbe) | Sep 04, 2024 |
| Chuwi         | HeroBook Air                | Notebook    | [163bdd4e80](https://linux-hardware.org/?probe=163bdd4e80) | Sep 04, 2024 |
| HP            | 895D                        | Desktop     | [2ffb71ca8d](https://linux-hardware.org/?probe=2ffb71ca8d) | Sep 03, 2024 |
| HP            | 18E9                        | Desktop     | [3cfa598b85](https://linux-hardware.org/?probe=3cfa598b85) | Sep 03, 2024 |
| HP            | EliteBook 8440p             | Notebook    | [70ad6eb824](https://linux-hardware.org/?probe=70ad6eb824) | Sep 03, 2024 |
| Acer          | AOD255                      | Notebook    | [3dace1f171](https://linux-hardware.org/?probe=3dace1f171) | Sep 03, 2024 |
| Acer          | AOD255                      | Notebook    | [7d7265c514](https://linux-hardware.org/?probe=7d7265c514) | Sep 03, 2024 |
| HP            | Compaq 6735s                | Notebook    | [ef4b082281](https://linux-hardware.org/?probe=ef4b082281) | Sep 02, 2024 |
| Haier         | ZEB19 V1.1                  | Desktop     | [dd01bca542](https://linux-hardware.org/?probe=dd01bca542) | Sep 01, 2024 |
| HP            | Compaq 6530b (GW688AV)      | Notebook    | [acf0e79f7a](https://linux-hardware.org/?probe=acf0e79f7a) | Aug 31, 2024 |
| ASUSTek       | P8B75-M LX PLUS             | Desktop     | [b0e323ae58](https://linux-hardware.org/?probe=b0e323ae58) | Aug 31, 2024 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [ac81eefe24](https://linux-hardware.org/?probe=ac81eefe24) | Aug 31, 2024 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [b1b7d3ccd5](https://linux-hardware.org/?probe=b1b7d3ccd5) | Aug 30, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c37c1fe47f](https://linux-hardware.org/?probe=c37c1fe47f) | Aug 29, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [609fb0b8b9](https://linux-hardware.org/?probe=609fb0b8b9) | Aug 28, 2024 |
| Acer          | Aspire Z5610                | All in one  | [9d826bce47](https://linux-hardware.org/?probe=9d826bce47) | Aug 28, 2024 |
| Dell          | Latitude 5285               | Notebook    | [ece411e4e4](https://linux-hardware.org/?probe=ece411e4e4) | Aug 27, 2024 |
| Haier         | ZEB19 V1.1                  | Desktop     | [f600ce1cc4](https://linux-hardware.org/?probe=f600ce1cc4) | Aug 27, 2024 |
| Lenovo        | ThinkPad L480 20LTS15Q00    | Notebook    | [c7bd2c3d2e](https://linux-hardware.org/?probe=c7bd2c3d2e) | Aug 26, 2024 |
| Apple         | Mac-7BA5B2D9E42DDD94        | Desktop     | [773d5ea3fe](https://linux-hardware.org/?probe=773d5ea3fe) | Aug 26, 2024 |
| Dell          | 0HY9JP A00                  | Desktop     | [dae885b643](https://linux-hardware.org/?probe=dae885b643) | Aug 25, 2024 |
| AZW           | MINI S                      | Desktop     | [eaafeaecad](https://linux-hardware.org/?probe=eaafeaecad) | Aug 24, 2024 |
| Fujitsu Si... | AMILO Pi 1505               | Notebook    | [b62ccb34eb](https://linux-hardware.org/?probe=b62ccb34eb) | Aug 23, 2024 |
| HP            | Pavilion dv6                | Notebook    | [8745b6a8a6](https://linux-hardware.org/?probe=8745b6a8a6) | Aug 22, 2024 |
| Acer          | Aspire E5-571G              | Notebook    | [5d217cd410](https://linux-hardware.org/?probe=5d217cd410) | Aug 22, 2024 |
| eMachines     | E725                        | Notebook    | [22fba92ec4](https://linux-hardware.org/?probe=22fba92ec4) | Aug 20, 2024 |
| Lenovo        | ThinkPad T61 7658CTO        | Notebook    | [c395b3e28c](https://linux-hardware.org/?probe=c395b3e28c) | Aug 19, 2024 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | Notebook    | [d4e9ec66bb](https://linux-hardware.org/?probe=d4e9ec66bb) | Aug 17, 2024 |
| Dell          | 0FDY5C A00                  | Desktop     | [85ce806b0f](https://linux-hardware.org/?probe=85ce806b0f) | Aug 17, 2024 |
| Dell          | XPS MXC062                  | Notebook    | [46f9c80883](https://linux-hardware.org/?probe=46f9c80883) | Aug 16, 2024 |
| Lenovo        | IdeaPad S205 Brazos         | Notebook    | [e40f1ca18f](https://linux-hardware.org/?probe=e40f1ca18f) | Aug 15, 2024 |
| Google        | Zako                        | Desktop     | [cbd6dd35bc](https://linux-hardware.org/?probe=cbd6dd35bc) | Aug 14, 2024 |
| Google        | Zako                        | Desktop     | [c5d4e9a38b](https://linux-hardware.org/?probe=c5d4e9a38b) | Aug 14, 2024 |
| HP            | EliteBook 8440p             | Notebook    | [46e4c79baf](https://linux-hardware.org/?probe=46e4c79baf) | Aug 13, 2024 |
| HP            | EliteBook 8440p             | Notebook    | [4a401d3cf7](https://linux-hardware.org/?probe=4a401d3cf7) | Aug 13, 2024 |
| HP            | Compaq Presario CQ60        | Notebook    | [d0e97b8772](https://linux-hardware.org/?probe=d0e97b8772) | Aug 13, 2024 |
| Gigabyte      | GA-MA69GM-S2H               | Desktop     | [27116cd0ce](https://linux-hardware.org/?probe=27116cd0ce) | Aug 12, 2024 |
| HP            | Notebook                    | Notebook    | [0d521e10c8](https://linux-hardware.org/?probe=0d521e10c8) | Aug 11, 2024 |
| ASUSTek       | X540SA                      | Notebook    | [683c8f3f4b](https://linux-hardware.org/?probe=683c8f3f4b) | Aug 11, 2024 |
| SK hynix      | HT14CCIC42E                 | Notebook    | [eb41114fc3](https://linux-hardware.org/?probe=eb41114fc3) | Aug 10, 2024 |
| Gigabyte      | P55-USB3                    | Desktop     | [d13ef904ba](https://linux-hardware.org/?probe=d13ef904ba) | Aug 08, 2024 |
| Acer          | Aspire 5715Z                | Notebook    | [32b3360c63](https://linux-hardware.org/?probe=32b3360c63) | Aug 07, 2024 |
| Acer          | Aspire 5715Z                | Notebook    | [387c8e5fe4](https://linux-hardware.org/?probe=387c8e5fe4) | Aug 07, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [ef1df870ea](https://linux-hardware.org/?probe=ef1df870ea) | Aug 07, 2024 |
| Dell          | 0V8DVD A00                  | All in one  | [6ac88acf00](https://linux-hardware.org/?probe=6ac88acf00) | Aug 06, 2024 |
| Fujitsu       | D2778-C1 S26361-D2778-C1    | Desktop     | [13bf9126f5](https://linux-hardware.org/?probe=13bf9126f5) | Aug 04, 2024 |
| Dell          | 0H0P0M A00                  | Desktop     | [18107160ad](https://linux-hardware.org/?probe=18107160ad) | Aug 04, 2024 |
| HP            | Notebook                    | Notebook    | [1a796d1daf](https://linux-hardware.org/?probe=1a796d1daf) | Aug 04, 2024 |
| Dell          | Inspiron N5110              | Notebook    | [c390f98098](https://linux-hardware.org/?probe=c390f98098) | Aug 03, 2024 |
| Acer          | Aspire A515-51              | Notebook    | [edc0e332b2](https://linux-hardware.org/?probe=edc0e332b2) | Aug 01, 2024 |
| Acer          | Aspire A515-51              | Notebook    | [bd658968cf](https://linux-hardware.org/?probe=bd658968cf) | Aug 01, 2024 |
| HP            | Laptop 15-da0xxx            | Notebook    | [ed33f895c9](https://linux-hardware.org/?probe=ed33f895c9) | Jul 28, 2024 |
| Acer          | Eagle2B                     | Desktop     | [8172d0782d](https://linux-hardware.org/?probe=8172d0782d) | Jul 28, 2024 |
| Intel         | STCK1A32WFC H67490-303      | Notebook    | [b12d74f728](https://linux-hardware.org/?probe=b12d74f728) | Jul 27, 2024 |
| HP            | Pavilion x2 Detachable      | Notebook    | [f5fb19db6b](https://linux-hardware.org/?probe=f5fb19db6b) | Jul 27, 2024 |
| Acer          | Swift SF113-31              | Notebook    | [6c63a7574e](https://linux-hardware.org/?probe=6c63a7574e) | Jul 26, 2024 |
| HP            | Pavilion x2 Detachable      | Notebook    | [8f6ba78b79](https://linux-hardware.org/?probe=8f6ba78b79) | Jul 25, 2024 |
| HP            | 2AF7                        | Desktop     | [d00c713358](https://linux-hardware.org/?probe=d00c713358) | Jul 23, 2024 |
| Acer          | Aspire A515-57G             | Notebook    | [e7fba30a89](https://linux-hardware.org/?probe=e7fba30a89) | Jul 23, 2024 |
| Dell          | 0MN1TX A01                  | Desktop     | [99e899cbb0](https://linux-hardware.org/?probe=99e899cbb0) | Jul 22, 2024 |
| Dell          | Inspiron 3135               | Notebook    | [36c80b438d](https://linux-hardware.org/?probe=36c80b438d) | Jul 22, 2024 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | Convertible | [7599f8d0d5](https://linux-hardware.org/?probe=7599f8d0d5) | Jul 20, 2024 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | Convertible | [722e7132bd](https://linux-hardware.org/?probe=722e7132bd) | Jul 20, 2024 |
| HP            | 240 G4                      | Notebook    | [74ad43cd86](https://linux-hardware.org/?probe=74ad43cd86) | Jul 19, 2024 |
| PROBOOK       | U SERIES                    | Notebook    | [e9b030a9df](https://linux-hardware.org/?probe=e9b030a9df) | Jul 17, 2024 |
| Dell          | 0PC5F7 A01                  | Desktop     | [57944fa9c9](https://linux-hardware.org/?probe=57944fa9c9) | Jul 16, 2024 |
| PROBOOK       | U SERIES                    | Notebook    | [bdc92be04b](https://linux-hardware.org/?probe=bdc92be04b) | Jul 15, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [e0376fa4fe](https://linux-hardware.org/?probe=e0376fa4fe) | Jul 13, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [64b642a303](https://linux-hardware.org/?probe=64b642a303) | Jul 12, 2024 |
| Microsoft     | Surface Laptop Go           | Tablet      | [414019b989](https://linux-hardware.org/?probe=414019b989) | Jul 11, 2024 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [aab047cc91](https://linux-hardware.org/?probe=aab047cc91) | Jul 10, 2024 |
| ASUSTek       | K52JB                       | Notebook    | [d50ec4eed9](https://linux-hardware.org/?probe=d50ec4eed9) | Jul 09, 2024 |
| Lenovo        | ThinkPad L13 Gen 1 20R4S... | Notebook    | [4cc52bfb25](https://linux-hardware.org/?probe=4cc52bfb25) | Jul 07, 2024 |
| Gigabyte      | H61M-S2P                    | Desktop     | [045d7ad610](https://linux-hardware.org/?probe=045d7ad610) | Jul 06, 2024 |
| Notebook      | PB50_70EF,ED,EC             | Notebook    | [9d7e31a9f6](https://linux-hardware.org/?probe=9d7e31a9f6) | Jul 06, 2024 |
| Dell          | XPS M1330                   | Notebook    | [a01b178b3a](https://linux-hardware.org/?probe=a01b178b3a) | Jul 06, 2024 |
| Acer          | Aspire V5-471P              | Notebook    | [f8a09477f0](https://linux-hardware.org/?probe=f8a09477f0) | Jul 05, 2024 |
| Packard Be... | EasyNote TE69BM             | Notebook    | [e4f954f464](https://linux-hardware.org/?probe=e4f954f464) | Jul 05, 2024 |
| ASUSTek       | K50AD                       | Notebook    | [0fd561ca3c](https://linux-hardware.org/?probe=0fd561ca3c) | Jul 05, 2024 |
| Unknown       | N10(M1N1)                   | Notebook    | [fc2ca6d762](https://linux-hardware.org/?probe=fc2ca6d762) | Jul 04, 2024 |
| Morshow       | v1.0                        | Mini pc     | [1134367fdd](https://linux-hardware.org/?probe=1134367fdd) | Jul 03, 2024 |
| HP            | 14                          | Notebook    | [f28a807a2e](https://linux-hardware.org/?probe=f28a807a2e) | Jul 01, 2024 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [3f56bdc232](https://linux-hardware.org/?probe=3f56bdc232) | Jul 01, 2024 |
| Fujitsu       | D3402-A1 S26361-D3402-A1    | Desktop     | [b76253dea1](https://linux-hardware.org/?probe=b76253dea1) | Jul 01, 2024 |
| Dell          | Latitude E6410              | Notebook    | [6f8ffa83ce](https://linux-hardware.org/?probe=6f8ffa83ce) | Jul 01, 2024 |
| HP            | Pavilion 10 TS              | Notebook    | [c2bd71447d](https://linux-hardware.org/?probe=c2bd71447d) | Jun 30, 2024 |
| Dell          | Inspiron 15-3567            | Notebook    | [3eed7f4afe](https://linux-hardware.org/?probe=3eed7f4afe) | Jun 30, 2024 |
| ASUSTek       | K52JB                       | Notebook    | [cda7f38058](https://linux-hardware.org/?probe=cda7f38058) | Jun 29, 2024 |
| HP            | Laptop 15-bw0xx             | Notebook    | [3a1445300b](https://linux-hardware.org/?probe=3a1445300b) | Jun 28, 2024 |
| Dell          | Latitude 3190               | Notebook    | [41e83ac5c5](https://linux-hardware.org/?probe=41e83ac5c5) | Jun 27, 2024 |
| HP            | Pavilion dv6                | Notebook    | [e6342ad374](https://linux-hardware.org/?probe=e6342ad374) | Jun 27, 2024 |
| RWC           | DA-T118-SR                  | Notebook    | [05f141e671](https://linux-hardware.org/?probe=05f141e671) | Jun 26, 2024 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [16c26f1386](https://linux-hardware.org/?probe=16c26f1386) | Jun 26, 2024 |
| Teclast       | tPAD                        | Notebook    | [7fcbabfefd](https://linux-hardware.org/?probe=7fcbabfefd) | Jun 25, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [1da0ed40d4](https://linux-hardware.org/?probe=1da0ed40d4) | Jun 24, 2024 |
| Dell          | 088DT1 A01                  | Desktop     | [35d8e69b80](https://linux-hardware.org/?probe=35d8e69b80) | Jun 20, 2024 |
| Insyde        | Braswell                    | Notebook    | [fb1a3d94f3](https://linux-hardware.org/?probe=fb1a3d94f3) | Jun 19, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [2639f09193](https://linux-hardware.org/?probe=2639f09193) | Jun 19, 2024 |
| Dell          | 07WP95 A01                  | Desktop     | [220e02a4f2](https://linux-hardware.org/?probe=220e02a4f2) | Jun 19, 2024 |
| Dell          | 0H0P0M A00                  | Desktop     | [9472163fb6](https://linux-hardware.org/?probe=9472163fb6) | Jun 18, 2024 |
| Dell          | 0H0P0M A00                  | Desktop     | [3819010bcc](https://linux-hardware.org/?probe=3819010bcc) | Jun 18, 2024 |
| Dell          | 0H0P0M A00                  | Desktop     | [ecc4765c8f](https://linux-hardware.org/?probe=ecc4765c8f) | Jun 18, 2024 |
| NU591         | 1.0                         | Desktop     | [c1efde8d4f](https://linux-hardware.org/?probe=c1efde8d4f) | Jun 15, 2024 |
| Samsung       | QX311/QX411/QX412/QX511     | Notebook    | [e37830ceb9](https://linux-hardware.org/?probe=e37830ceb9) | Jun 10, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [f495fbd229](https://linux-hardware.org/?probe=f495fbd229) | Jun 04, 2024 |
| HP            | ZBook 15 G2                 | Notebook    | [a788fb84c1](https://linux-hardware.org/?probe=a788fb84c1) | Jun 02, 2024 |
| HP            | ZBook 15 G2                 | Notebook    | [60515e0fa6](https://linux-hardware.org/?probe=60515e0fa6) | Jun 02, 2024 |
| HP            | Laptop 15-bs0xx             | Notebook    | [3e4d7f9fbc](https://linux-hardware.org/?probe=3e4d7f9fbc) | Jun 01, 2024 |
| ASRock        | Wolfdale1333-D667           | Desktop     | [aded923eb2](https://linux-hardware.org/?probe=aded923eb2) | May 31, 2024 |
| ASUSTek       | X550WAK                     | Notebook    | [1a64c5c27f](https://linux-hardware.org/?probe=1a64c5c27f) | May 31, 2024 |
| HP            | Laptop 15-bw0xx             | Notebook    | [3bae231b99](https://linux-hardware.org/?probe=3bae231b99) | May 31, 2024 |
| HP            | Laptop 15-bw0xx             | Notebook    | [0c0fc0bbe4](https://linux-hardware.org/?probe=0c0fc0bbe4) | May 31, 2024 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [01934266f4](https://linux-hardware.org/?probe=01934266f4) | May 31, 2024 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [3414247f17](https://linux-hardware.org/?probe=3414247f17) | May 31, 2024 |
| Lenovo        | ThinkPad X200 2024B67       | Notebook    | [6d2d7fbbb5](https://linux-hardware.org/?probe=6d2d7fbbb5) | May 28, 2024 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [5201ae534c](https://linux-hardware.org/?probe=5201ae534c) | May 28, 2024 |
| Intel         | NUC11ATBC4 M53051-400       | Mini pc     | [424447b0e3](https://linux-hardware.org/?probe=424447b0e3) | May 27, 2024 |
| Dell          | 042P49 A01                  | Desktop     | [153d7e94c8](https://linux-hardware.org/?probe=153d7e94c8) | May 27, 2024 |
| Dell          | 042P49 A01                  | Desktop     | [3351870e5d](https://linux-hardware.org/?probe=3351870e5d) | May 27, 2024 |
| ODM           | Unknown                     | Notebook    | [d6a98e94b6](https://linux-hardware.org/?probe=d6a98e94b6) | May 27, 2024 |
| ASUSTek       | GL552VX                     | Notebook    | [9f2697991a](https://linux-hardware.org/?probe=9f2697991a) | May 26, 2024 |
| Itautec       | NT 2030                     | Desktop     | [956753c602](https://linux-hardware.org/?probe=956753c602) | May 25, 2024 |
| Pegatron      | 2AEE                        | Desktop     | [c1b8b9150f](https://linux-hardware.org/?probe=c1b8b9150f) | May 25, 2024 |
| Unknown       | Unknown                     | Tablet      | [5ac8baaef6](https://linux-hardware.org/?probe=5ac8baaef6) | May 24, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [133e970ae7](https://linux-hardware.org/?probe=133e970ae7) | May 23, 2024 |
| Lenovo        | ThinkPad T560 20FJS0XX00    | Notebook    | [11d6470b8b](https://linux-hardware.org/?probe=11d6470b8b) | May 23, 2024 |
| Packard Be... | PT890-8237A                 | Desktop     | [150aa2b8e8](https://linux-hardware.org/?probe=150aa2b8e8) | May 22, 2024 |
| Apple         | MacBookAir1,1               | Notebook    | [8c29382ba8](https://linux-hardware.org/?probe=8c29382ba8) | May 21, 2024 |
| MSI           | MS-B0A81                    | Desktop     | [3b16ea46f0](https://linux-hardware.org/?probe=3b16ea46f0) | May 20, 2024 |
| Lenovo        | Bantry CRB NOK              | Desktop     | [a501c1214c](https://linux-hardware.org/?probe=a501c1214c) | May 19, 2024 |
| ODM           | Unknown                     | Notebook    | [9fcefdfbe9](https://linux-hardware.org/?probe=9fcefdfbe9) | May 19, 2024 |
| Lenovo        | Bantry CRB NOK              | Desktop     | [5c2dca5ac4](https://linux-hardware.org/?probe=5c2dca5ac4) | May 19, 2024 |
| Dell          | 0DF42J A00                  | Desktop     | [dc9f14663c](https://linux-hardware.org/?probe=dc9f14663c) | May 18, 2024 |
| HP            | 17E2                        | Mini pc     | [fef2c192b3](https://linux-hardware.org/?probe=fef2c192b3) | May 16, 2024 |
| HP            | 17E2                        | Mini pc     | [0d8c39e4da](https://linux-hardware.org/?probe=0d8c39e4da) | May 16, 2024 |
| Lenovo        | ThinkPad L490 20Q5002GGE    | Notebook    | [c92390a81b](https://linux-hardware.org/?probe=c92390a81b) | May 15, 2024 |
| Dell          | Inspiron 13-5378            | Notebook    | [fcb1c00cb1](https://linux-hardware.org/?probe=fcb1c00cb1) | May 15, 2024 |
| Sony          | VPCW216AG                   | Notebook    | [0e3674f67f](https://linux-hardware.org/?probe=0e3674f67f) | May 14, 2024 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [abf8f16050](https://linux-hardware.org/?probe=abf8f16050) | May 13, 2024 |
| Dell          | Vostro 3400                 | Notebook    | [345ddaf7ed](https://linux-hardware.org/?probe=345ddaf7ed) | May 13, 2024 |
| Lenovo        | G575 20081                  | Notebook    | [581885ea87](https://linux-hardware.org/?probe=581885ea87) | May 11, 2024 |
| Intel         | H61                         | Desktop     | [274a448032](https://linux-hardware.org/?probe=274a448032) | May 09, 2024 |
| Acer          | One S1003                   | Tablet      | [4b36e20081](https://linux-hardware.org/?probe=4b36e20081) | May 09, 2024 |
| Shenzhen B... | XN116B                      | Notebook    | [47dbcecbd7](https://linux-hardware.org/?probe=47dbcecbd7) | May 04, 2024 |
| Dell          | Vostro 3400                 | Notebook    | [93da978d38](https://linux-hardware.org/?probe=93da978d38) | May 04, 2024 |
| HP            | EliteBook 840 G4            | Notebook    | [f9fed717ee](https://linux-hardware.org/?probe=f9fed717ee) | May 03, 2024 |
| ASRock        | Wolfdale1333-D667           | Desktop     | [9cfa5ae2c5](https://linux-hardware.org/?probe=9cfa5ae2c5) | May 03, 2024 |
| ASUSTek       | X540YA                      | Notebook    | [e163aa8e32](https://linux-hardware.org/?probe=e163aa8e32) | May 03, 2024 |
| HP            | Pavilion dm1                | Notebook    | [ba07809953](https://linux-hardware.org/?probe=ba07809953) | May 02, 2024 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [f163dcd97e](https://linux-hardware.org/?probe=f163dcd97e) | May 02, 2024 |
| Notebook      | W54_W94_W955TU,-T,-C        | Notebook    | [c327d5c1a6](https://linux-hardware.org/?probe=c327d5c1a6) | May 01, 2024 |
| Apple         | MacBookPro5,5               | Notebook    | [2ddfed1c8a](https://linux-hardware.org/?probe=2ddfed1c8a) | May 01, 2024 |
| HP            | 18E9                        | Desktop     | [5b1f8d9d02](https://linux-hardware.org/?probe=5b1f8d9d02) | Apr 29, 2024 |
| Lenovo        | G50-45 80E3                 | Notebook    | [a12bc9b719](https://linux-hardware.org/?probe=a12bc9b719) | Apr 28, 2024 |
| ASUSTek       | K45A                        | Notebook    | [7bed7e12ab](https://linux-hardware.org/?probe=7bed7e12ab) | Apr 27, 2024 |
| ASUSTek       | K53BY                       | Notebook    | [6f6c4b9d68](https://linux-hardware.org/?probe=6f6c4b9d68) | Apr 26, 2024 |
| HP            | Compaq 8710w (GT649PA#AB... | Notebook    | [00f1c96012](https://linux-hardware.org/?probe=00f1c96012) | Apr 26, 2024 |
| Dell          | Inspiron 15-3567            | Notebook    | [e93fe83f01](https://linux-hardware.org/?probe=e93fe83f01) | Apr 24, 2024 |
| Acer          | Aspire E5-573G              | Notebook    | [216cd2fc72](https://linux-hardware.org/?probe=216cd2fc72) | Apr 24, 2024 |
| ASUSTek       | X555QG                      | Notebook    | [c905efd379](https://linux-hardware.org/?probe=c905efd379) | Apr 23, 2024 |
| ASUSTek       | X555QG                      | Notebook    | [26b8da2305](https://linux-hardware.org/?probe=26b8da2305) | Apr 23, 2024 |
| ASUSTek       | K42F                        | Notebook    | [f29299723c](https://linux-hardware.org/?probe=f29299723c) | Apr 23, 2024 |
| Lenovo        | B575e 36852BG               | Notebook    | [c2c9ec964e](https://linux-hardware.org/?probe=c2c9ec964e) | Apr 23, 2024 |
| ASUSTek       | K42F                        | Notebook    | [63b454fa02](https://linux-hardware.org/?probe=63b454fa02) | Apr 23, 2024 |
| Lenovo        | B575e 36852BG               | Notebook    | [d168fb33c4](https://linux-hardware.org/?probe=d168fb33c4) | Apr 23, 2024 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [8049fc6b37](https://linux-hardware.org/?probe=8049fc6b37) | Apr 23, 2024 |
| Toshiba       | Satellite C850D-11C         | Notebook    | [beccadec71](https://linux-hardware.org/?probe=beccadec71) | Apr 22, 2024 |
| HP            | 8265                        | Desktop     | [17dd357578](https://linux-hardware.org/?probe=17dd357578) | Apr 21, 2024 |
| Fujitsu       | FMVA40B1RJ                  | Notebook    | [b0d3f0b365](https://linux-hardware.org/?probe=b0d3f0b365) | Apr 20, 2024 |
| Dell          | Inspiron 15-3567            | Notebook    | [bf1e4f8d6a](https://linux-hardware.org/?probe=bf1e4f8d6a) | Apr 20, 2024 |
| HP            | 8184 X4                     | Desktop     | [e110e13968](https://linux-hardware.org/?probe=e110e13968) | Apr 19, 2024 |
| HP            | 3031h                       | Desktop     | [1d9c5e06d3](https://linux-hardware.org/?probe=1d9c5e06d3) | Apr 18, 2024 |
| HP            | EliteBook 6930p             | Notebook    | [263d72f3c6](https://linux-hardware.org/?probe=263d72f3c6) | Apr 17, 2024 |
| Unknown       | Unknown                     | Notebook    | [10d92e98c0](https://linux-hardware.org/?probe=10d92e98c0) | Apr 16, 2024 |
| Dell          | 0D28YY A00                  | Desktop     | [c1bd4e2de3](https://linux-hardware.org/?probe=c1bd4e2de3) | Apr 14, 2024 |
| ASRock        | H61M-VG3                    | Desktop     | [caf43c2754](https://linux-hardware.org/?probe=caf43c2754) | Apr 14, 2024 |
| HP            | 250 G4 Notebook PC          | Notebook    | [2fcb542c43](https://linux-hardware.org/?probe=2fcb542c43) | Apr 14, 2024 |
| Prestigio     | Smartbook PSB116A           | Desktop     | [cc592e784e](https://linux-hardware.org/?probe=cc592e784e) | Apr 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [94f12b2951](https://linux-hardware.org/?probe=94f12b2951) | Apr 11, 2024 |
| Unknown       | M-140BI3                    | Notebook    | [491b1013ab](https://linux-hardware.org/?probe=491b1013ab) | Apr 11, 2024 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [8f232e4e6c](https://linux-hardware.org/?probe=8f232e4e6c) | Apr 11, 2024 |
| Biostar       | TA75M+                      | Desktop     | [24de8dbd0b](https://linux-hardware.org/?probe=24de8dbd0b) | Apr 10, 2024 |
| HP            | Pavilion g7                 | Notebook    | [6d84e70e34](https://linux-hardware.org/?probe=6d84e70e34) | Apr 10, 2024 |
| Lenovo        | ThinkPad X201 3680A44       | Notebook    | [db6aadf372](https://linux-hardware.org/?probe=db6aadf372) | Apr 10, 2024 |
| Acer          | Aspire ES1-512              | Notebook    | [47ad6cd23e](https://linux-hardware.org/?probe=47ad6cd23e) | Apr 05, 2024 |
| Acer          | Aspire ES1-512              | Notebook    | [9b5914816a](https://linux-hardware.org/?probe=9b5914816a) | Apr 05, 2024 |
| Dell          | Latitude E6410              | Notebook    | [7c4144e1df](https://linux-hardware.org/?probe=7c4144e1df) | Apr 05, 2024 |
| ASRock        | H61M-VG3                    | Desktop     | [82fa2b1397](https://linux-hardware.org/?probe=82fa2b1397) | Apr 04, 2024 |
| Acer          | Extensa 5630                | Notebook    | [224d74c060](https://linux-hardware.org/?probe=224d74c060) | Apr 04, 2024 |
| Acer          | Aspire E1-572G              | Notebook    | [7a19eed833](https://linux-hardware.org/?probe=7a19eed833) | Apr 03, 2024 |
| Acer          | Aspire XC-780               | Desktop     | [28ef93502a](https://linux-hardware.org/?probe=28ef93502a) | Apr 03, 2024 |
| Acer          | Aspire 3000                 | Notebook    | [1d2fad06c8](https://linux-hardware.org/?probe=1d2fad06c8) | Apr 02, 2024 |
| ASUSTek       | VivoBook_ASUS Laptop E20... | Notebook    | [83edc14408](https://linux-hardware.org/?probe=83edc14408) | Mar 30, 2024 |
| AZW           | MINI S                      | Desktop     | [b915778838](https://linux-hardware.org/?probe=b915778838) | Mar 30, 2024 |
| HP            | 250 G4 Notebook PC          | Notebook    | [82ae07c449](https://linux-hardware.org/?probe=82ae07c449) | Mar 29, 2024 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [6c9bf73f0c](https://linux-hardware.org/?probe=6c9bf73f0c) | Mar 28, 2024 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | Notebook    | [8d88a75722](https://linux-hardware.org/?probe=8d88a75722) | Mar 27, 2024 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [a47bfb1a29](https://linux-hardware.org/?probe=a47bfb1a29) | Mar 27, 2024 |
| HP            | Laptop 15-db0xxx            | Notebook    | [04ef2627e2](https://linux-hardware.org/?probe=04ef2627e2) | Mar 27, 2024 |
| Supermicro    | X8DTT-IBX                   | Server      | [0ece65fa78](https://linux-hardware.org/?probe=0ece65fa78) | Mar 27, 2024 |
| Supermicro    | X8DTT-IBX                   | Server      | [b909136c03](https://linux-hardware.org/?probe=b909136c03) | Mar 27, 2024 |
| Supermicro    | X8DTT-IBX                   | Server      | [d93ff94b95](https://linux-hardware.org/?probe=d93ff94b95) | Mar 27, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b4e434bb17](https://linux-hardware.org/?probe=b4e434bb17) | Mar 27, 2024 |
| Supermicro    | X8DTT-IBX                   | Server      | [47de08fbc7](https://linux-hardware.org/?probe=47de08fbc7) | Mar 26, 2024 |
| Supermicro    | X8DTT-IBX                   | Server      | [4e7f4f9166](https://linux-hardware.org/?probe=4e7f4f9166) | Mar 26, 2024 |
| Supermicro    | X8DTT-IBX                   | Server      | [4533e58601](https://linux-hardware.org/?probe=4533e58601) | Mar 26, 2024 |
| Acer          | Extensa 2540                | Notebook    | [3e49d36612](https://linux-hardware.org/?probe=3e49d36612) | Mar 26, 2024 |
| Supermicro    | X8DTT-IBX                   | Server      | [d380208ff7](https://linux-hardware.org/?probe=d380208ff7) | Mar 26, 2024 |
| HP            | 15 Notebook PC              | Notebook    | [46b79e7d26](https://linux-hardware.org/?probe=46b79e7d26) | Mar 26, 2024 |
| Chuwi         | LarkBox X                   | Mini pc     | [b3bbd8f0a3](https://linux-hardware.org/?probe=b3bbd8f0a3) | Mar 23, 2024 |
| HP            | Laptop 14-em0xxx            | Notebook    | [3f937a527b](https://linux-hardware.org/?probe=3f937a527b) | Mar 23, 2024 |
| Lenovo        | ThinkPad T460 20FMS08H00    | Notebook    | [8dfcfff063](https://linux-hardware.org/?probe=8dfcfff063) | Mar 23, 2024 |
| Samsung       | N100                        | Notebook    | [d7a66b3835](https://linux-hardware.org/?probe=d7a66b3835) | Mar 22, 2024 |
| Sony          | VGN-TZ21MN_N                | Notebook    | [1e1a62727b](https://linux-hardware.org/?probe=1e1a62727b) | Mar 19, 2024 |
| ASUSTek       | P5KC                        | Desktop     | [4b54f8d3f2](https://linux-hardware.org/?probe=4b54f8d3f2) | Mar 18, 2024 |
| Unknown       | Unknown                     | Notebook    | [27317f4bcf](https://linux-hardware.org/?probe=27317f4bcf) | Mar 18, 2024 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [5603a5896d](https://linux-hardware.org/?probe=5603a5896d) | Mar 17, 2024 |
| ODM           | Unknown                     | Notebook    | [5a87f7eaeb](https://linux-hardware.org/?probe=5a87f7eaeb) | Mar 17, 2024 |
| Sony          | VPCW216AG                   | Notebook    | [c607fc8a6b](https://linux-hardware.org/?probe=c607fc8a6b) | Mar 16, 2024 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [0dd66d219d](https://linux-hardware.org/?probe=0dd66d219d) | Mar 16, 2024 |
| HP            | Split 13 x2 PC              | Notebook    | [447e4a6951](https://linux-hardware.org/?probe=447e4a6951) | Mar 14, 2024 |
| Lenovo        | ThinkPad L520 5015AH2       | Notebook    | [c63473fd10](https://linux-hardware.org/?probe=c63473fd10) | Mar 12, 2024 |
| HP            | Notebook                    | Notebook    | [51a929c53a](https://linux-hardware.org/?probe=51a929c53a) | Mar 08, 2024 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [61e1fc891a](https://linux-hardware.org/?probe=61e1fc891a) | Mar 07, 2024 |
| Sony          | SVF1521NSTB                 | Notebook    | [b9f4d235c9](https://linux-hardware.org/?probe=b9f4d235c9) | Mar 06, 2024 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [00c46d511e](https://linux-hardware.org/?probe=00c46d511e) | Mar 06, 2024 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [b4a202211e](https://linux-hardware.org/?probe=b4a202211e) | Mar 06, 2024 |
| HP            | Notebook                    | Notebook    | [025b54a984](https://linux-hardware.org/?probe=025b54a984) | Mar 06, 2024 |
| HP            | Notebook                    | Notebook    | [5f90d8f25b](https://linux-hardware.org/?probe=5f90d8f25b) | Mar 06, 2024 |
| Microsoft     | Surface Pro 2               | Tablet      | [326d4bbffb](https://linux-hardware.org/?probe=326d4bbffb) | Mar 05, 2024 |
| Fujitsu       | FMVC05005                   | Notebook    | [af1cd1c78b](https://linux-hardware.org/?probe=af1cd1c78b) | Mar 04, 2024 |
| Sony          | VPCEB3C4R                   | Notebook    | [f63a65b29f](https://linux-hardware.org/?probe=f63a65b29f) | Mar 04, 2024 |
| MSI           | MS-168A                     | Notebook    | [1625072479](https://linux-hardware.org/?probe=1625072479) | Mar 02, 2024 |
| MSI           | MS-168A                     | Notebook    | [cae162bcad](https://linux-hardware.org/?probe=cae162bcad) | Mar 02, 2024 |
| HP            | 250 G1                      | Notebook    | [805489bf43](https://linux-hardware.org/?probe=805489bf43) | Feb 26, 2024 |
| Acer          | Aspire X1700                | Desktop     | [20842b7abc](https://linux-hardware.org/?probe=20842b7abc) | Feb 26, 2024 |
| Google        | Lindar                      | Notebook    | [0f6ee4fa1f](https://linux-hardware.org/?probe=0f6ee4fa1f) | Feb 25, 2024 |
| ASRock        | HM55-HT                     | Desktop     | [f6669716da](https://linux-hardware.org/?probe=f6669716da) | Feb 24, 2024 |
| Dell          | Latitude D620               | Notebook    | [2ca5ca0cad](https://linux-hardware.org/?probe=2ca5ca0cad) | Feb 24, 2024 |
| EPoX Compu... | MCP61 Series                | Desktop     | [8028d0a8d1](https://linux-hardware.org/?probe=8028d0a8d1) | Feb 24, 2024 |
| Dell          | Latitude D620               | Notebook    | [78a800debc](https://linux-hardware.org/?probe=78a800debc) | Feb 22, 2024 |
| Dell          | 042P49 A01                  | Desktop     | [3e64e4a44e](https://linux-hardware.org/?probe=3e64e4a44e) | Feb 22, 2024 |
| FOUNDER Co... | M672+968                    | Notebook    | [0dd60ea26f](https://linux-hardware.org/?probe=0dd60ea26f) | Feb 22, 2024 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [7c9a199867](https://linux-hardware.org/?probe=7c9a199867) | Feb 21, 2024 |
| Sony          | VPCEB3C4R                   | Notebook    | [93a9016bf3](https://linux-hardware.org/?probe=93a9016bf3) | Feb 20, 2024 |
| Dell          | Inspiron 531s               | Desktop     | [0d9877a337](https://linux-hardware.org/?probe=0d9877a337) | Feb 19, 2024 |
| HP            | Presario M2000 (EE629LA#... | Notebook    | [302398d57c](https://linux-hardware.org/?probe=302398d57c) | Feb 18, 2024 |
| HP            | Presario M2000 (EE629LA#... | Notebook    | [c44f12d85d](https://linux-hardware.org/?probe=c44f12d85d) | Feb 18, 2024 |
| HP            | 83DD                        | Mini pc     | [71dc39d477](https://linux-hardware.org/?probe=71dc39d477) | Feb 17, 2024 |
| HP            | 83DD                        | Mini pc     | [8a763f4ef6](https://linux-hardware.org/?probe=8a763f4ef6) | Feb 17, 2024 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | Desktop     | [edc56f85b9](https://linux-hardware.org/?probe=edc56f85b9) | Feb 17, 2024 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [d18785d54f](https://linux-hardware.org/?probe=d18785d54f) | Feb 16, 2024 |
| Samsung       | 530XBB                      | Notebook    | [f98c88531f](https://linux-hardware.org/?probe=f98c88531f) | Feb 15, 2024 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [d21dee5d98](https://linux-hardware.org/?probe=d21dee5d98) | Feb 13, 2024 |
| Digibras      | NH4CU53                     | Notebook    | [1e3d9f1795](https://linux-hardware.org/?probe=1e3d9f1795) | Feb 10, 2024 |
| Dell          | Latitude 3340               | Notebook    | [f1233f10b5](https://linux-hardware.org/?probe=f1233f10b5) | Feb 10, 2024 |
| Google        | Lindar                      | Notebook    | [e3a071ae43](https://linux-hardware.org/?probe=e3a071ae43) | Feb 10, 2024 |
| Dell          | Latitude E5430 vPro         | Notebook    | [9e120d90b8](https://linux-hardware.org/?probe=9e120d90b8) | Feb 09, 2024 |
| ASRock        | H110M Combo-G               | Desktop     | [319e01fd31](https://linux-hardware.org/?probe=319e01fd31) | Feb 09, 2024 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | Notebook    | [52d94c62ce](https://linux-hardware.org/?probe=52d94c62ce) | Feb 08, 2024 |
| MSI           | MS-7309                     | Desktop     | [dd1dea1c0e](https://linux-hardware.org/?probe=dd1dea1c0e) | Feb 07, 2024 |
| Fujitsu       | LIFEBOOK U7313              | Notebook    | [f1f1ab12ba](https://linux-hardware.org/?probe=f1f1ab12ba) | Feb 07, 2024 |
| Foxconn       | G41MXP/G41MXP-V             | Desktop     | [f63c9d5f5a](https://linux-hardware.org/?probe=f63c9d5f5a) | Feb 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [5fa467241b](https://linux-hardware.org/?probe=5fa467241b) | Feb 05, 2024 |
| Itautec       | Infoway w7430               | Notebook    | [4928095170](https://linux-hardware.org/?probe=4928095170) | Feb 05, 2024 |
| Acer          | Aspire 5951G                | Notebook    | [e583f21b3a](https://linux-hardware.org/?probe=e583f21b3a) | Feb 05, 2024 |
| Packard Be... | EasyNote ENTG71BM           | Notebook    | [eb979afe2e](https://linux-hardware.org/?probe=eb979afe2e) | Feb 04, 2024 |
| HP            | Pavilion dv6                | Notebook    | [52c0814c31](https://linux-hardware.org/?probe=52c0814c31) | Feb 03, 2024 |
| HP            | Pavilion dv6                | Notebook    | [d477732dfa](https://linux-hardware.org/?probe=d477732dfa) | Feb 03, 2024 |
| ODM           | Unknown                     | Notebook    | [0ad5efc9ef](https://linux-hardware.org/?probe=0ad5efc9ef) | Feb 03, 2024 |
| Gigabyte      | H61M-S1                     | Desktop     | [e7f247621c](https://linux-hardware.org/?probe=e7f247621c) | Feb 02, 2024 |
| Lenovo        | G405 20239                  | Notebook    | [7afc820794](https://linux-hardware.org/?probe=7afc820794) | Feb 01, 2024 |
| Acer          | Swift SF314-43              | Notebook    | [793c3d3b4c](https://linux-hardware.org/?probe=793c3d3b4c) | Jan 31, 2024 |
| Lenovo        | G575 20081                  | Notebook    | [162e1f81cf](https://linux-hardware.org/?probe=162e1f81cf) | Jan 31, 2024 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [a72292c97b](https://linux-hardware.org/?probe=a72292c97b) | Jan 31, 2024 |
| Dell          | Inspiron N5010              | Notebook    | [dcd752673f](https://linux-hardware.org/?probe=dcd752673f) | Jan 29, 2024 |
| Acer          | Aspire ES1-520              | Notebook    | [633516e35a](https://linux-hardware.org/?probe=633516e35a) | Jan 25, 2024 |
| Lenovo        | ThinkPad T60p 20078JU       | Notebook    | [6c83cf1141](https://linux-hardware.org/?probe=6c83cf1141) | Jan 25, 2024 |
| Acer          | Aspire E1-572G              | Notebook    | [d94fb0b47b](https://linux-hardware.org/?probe=d94fb0b47b) | Jan 24, 2024 |
| ODM           | Unknown                     | Notebook    | [2d8310fe96](https://linux-hardware.org/?probe=2d8310fe96) | Jan 24, 2024 |
| Dell          | 0DF42J A00                  | Desktop     | [f181c086e3](https://linux-hardware.org/?probe=f181c086e3) | Jan 23, 2024 |
| Dell          | 0DF42J A00                  | Desktop     | [5a172ff7ec](https://linux-hardware.org/?probe=5a172ff7ec) | Jan 22, 2024 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [c0eb7c0861](https://linux-hardware.org/?probe=c0eb7c0861) | Jan 21, 2024 |
| ASUSTek       | M2N32-SLI DELUXE            | Desktop     | [9b6eb3d320](https://linux-hardware.org/?probe=9b6eb3d320) | Jan 19, 2024 |
| Dell          | 018D1Y A00                  | Desktop     | [5d46b8d1b3](https://linux-hardware.org/?probe=5d46b8d1b3) | Jan 19, 2024 |
| Dell          | 018D1Y A00                  | Desktop     | [cf089739df](https://linux-hardware.org/?probe=cf089739df) | Jan 19, 2024 |
| ZOTAC         | NM10                        | Desktop     | [e185a9b292](https://linux-hardware.org/?probe=e185a9b292) | Jan 18, 2024 |
| Intel         | H61                         | Desktop     | [1d639194e4](https://linux-hardware.org/?probe=1d639194e4) | Jan 17, 2024 |
| HP            | 3397                        | Desktop     | [a46224b9bc](https://linux-hardware.org/?probe=a46224b9bc) | Jan 17, 2024 |
| BESSTAR Te... | GB1B                        | Mini pc     | [817daf41f7](https://linux-hardware.org/?probe=817daf41f7) | Jan 16, 2024 |
| BESSTAR Te... | GB1B                        | Mini pc     | [87ad2c7889](https://linux-hardware.org/?probe=87ad2c7889) | Jan 16, 2024 |
| Lenovo        | ThinkPad SL 2746F2G         | Notebook    | [47b2e38ff4](https://linux-hardware.org/?probe=47b2e38ff4) | Jan 16, 2024 |
| Foxconn       | G41MXP/G41MXP-V             | Desktop     | [907bccb062](https://linux-hardware.org/?probe=907bccb062) | Jan 16, 2024 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [45399ef111](https://linux-hardware.org/?probe=45399ef111) | Jan 15, 2024 |
| Dell          | Inspiron N5010              | Notebook    | [d6239c4393](https://linux-hardware.org/?probe=d6239c4393) | Jan 15, 2024 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [dce09bb097](https://linux-hardware.org/?probe=dce09bb097) | Jan 14, 2024 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [c0f0afd78c](https://linux-hardware.org/?probe=c0f0afd78c) | Jan 14, 2024 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | Notebook    | [82175efff8](https://linux-hardware.org/?probe=82175efff8) | Jan 14, 2024 |
| Foxconn       | 2AA9h                       | Desktop     | [40459d91a4](https://linux-hardware.org/?probe=40459d91a4) | Jan 11, 2024 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [681ea2eb1a](https://linux-hardware.org/?probe=681ea2eb1a) | Jan 10, 2024 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [2894cc00dc](https://linux-hardware.org/?probe=2894cc00dc) | Jan 10, 2024 |
| iRU           | 15TLI                       | Notebook    | [4d83aee906](https://linux-hardware.org/?probe=4d83aee906) | Jan 10, 2024 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [5654e285db](https://linux-hardware.org/?probe=5654e285db) | Jan 10, 2024 |
| iRU           | 15TLI                       | Notebook    | [d318923a72](https://linux-hardware.org/?probe=d318923a72) | Jan 09, 2024 |
| Supermicro    | X12DPi-N6                   | Server      | [fe3ca134e4](https://linux-hardware.org/?probe=fe3ca134e4) | Jan 09, 2024 |
| Supermicro    | X12DPi-N6                   | Server      | [ba90dbeba2](https://linux-hardware.org/?probe=ba90dbeba2) | Jan 09, 2024 |
| ASUSTek       | K53U                        | Notebook    | [df631caaa2](https://linux-hardware.org/?probe=df631caaa2) | Jan 09, 2024 |
| Lenovo        | ThinkPad T430 23477C7       | Notebook    | [db1c43a6a6](https://linux-hardware.org/?probe=db1c43a6a6) | Jan 09, 2024 |
| HP            | 240 G6 Notebook PC          | Notebook    | [52fa49b647](https://linux-hardware.org/?probe=52fa49b647) | Jan 08, 2024 |
| HP            | Notebook                    | Notebook    | [79932769a2](https://linux-hardware.org/?probe=79932769a2) | Jan 08, 2024 |
| Lenovo        | IdeaPad S145-14API 81UV     | Notebook    | [3a14a938f8](https://linux-hardware.org/?probe=3a14a938f8) | Jan 08, 2024 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [186230d9c6](https://linux-hardware.org/?probe=186230d9c6) | Jan 08, 2024 |
| Microsoft     | Surface Pro                 | Tablet      | [9aa6d7d7c0](https://linux-hardware.org/?probe=9aa6d7d7c0) | Jan 07, 2024 |
| Digibras      | NH4CU03                     | Notebook    | [be0eab4038](https://linux-hardware.org/?probe=be0eab4038) | Jan 05, 2024 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [f8471bbcf4](https://linux-hardware.org/?probe=f8471bbcf4) | Jan 04, 2024 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [3290e9841e](https://linux-hardware.org/?probe=3290e9841e) | Jan 04, 2024 |
| Dell          | 0CRH6C A00                  | Desktop     | [6c4bafe7b1](https://linux-hardware.org/?probe=6c4bafe7b1) | Jan 04, 2024 |
| Lenovo        | 3102 SDK0J40700 WIN 3258... | Desktop     | [afda94711c](https://linux-hardware.org/?probe=afda94711c) | Jan 04, 2024 |
| Google        | Electro                     | Notebook    | [74ed1caffe](https://linux-hardware.org/?probe=74ed1caffe) | Jan 04, 2024 |
| Packard Be... | EasyNote LM85               | Notebook    | [e756bb57ba](https://linux-hardware.org/?probe=e756bb57ba) | Jan 03, 2024 |
| Acer          | Aspire ES1-520              | Notebook    | [922ef3d7e1](https://linux-hardware.org/?probe=922ef3d7e1) | Jan 03, 2024 |
| Koloe         | X58                         | Desktop     | [2a3e4788ed](https://linux-hardware.org/?probe=2a3e4788ed) | Jan 03, 2024 |
| Microsoft     | Surface Pro 3               | Tablet      | [481cbbf231](https://linux-hardware.org/?probe=481cbbf231) | Jan 03, 2024 |
| HP            | Notebook                    | Notebook    | [3db48f7d59](https://linux-hardware.org/?probe=3db48f7d59) | Jan 02, 2024 |
| Apple         | MacBookAir4,2               | Notebook    | [7ebd4a00e7](https://linux-hardware.org/?probe=7ebd4a00e7) | Dec 31, 2023 |
| Apple         | MacBook6,1                  | Notebook    | [ba4ad2bc18](https://linux-hardware.org/?probe=ba4ad2bc18) | Dec 31, 2023 |
| HP            | ProBook 470 G3              | Notebook    | [22bd0ee412](https://linux-hardware.org/?probe=22bd0ee412) | Dec 30, 2023 |
| Dell          | 0PU052                      | Desktop     | [7da56e0b33](https://linux-hardware.org/?probe=7da56e0b33) | Dec 29, 2023 |
| Lenovo        | ThinkPad W540 20BG001KFR    | Notebook    | [af69ec2d33](https://linux-hardware.org/?probe=af69ec2d33) | Dec 29, 2023 |
| Lenovo        | ThinkPad W540 20BG001KFR    | Notebook    | [143c6b4161](https://linux-hardware.org/?probe=143c6b4161) | Dec 29, 2023 |
| Chuwi         | GemiBook Plus               | Notebook    | [acb06bb39a](https://linux-hardware.org/?probe=acb06bb39a) | Dec 29, 2023 |
| EPoX Compu... | MCP61 Series                | Desktop     | [730493cca3](https://linux-hardware.org/?probe=730493cca3) | Dec 29, 2023 |
| Qilive        | QW20141BSP                  | Notebook    | [3f2d1e03c3](https://linux-hardware.org/?probe=3f2d1e03c3) | Dec 28, 2023 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [8f6b669800](https://linux-hardware.org/?probe=8f6b669800) | Dec 27, 2023 |
| Google        | Swanky                      | Notebook    | [12fd273db1](https://linux-hardware.org/?probe=12fd273db1) | Dec 27, 2023 |
| Acer          | Extensa 215-55              | Notebook    | [54ca5c9e74](https://linux-hardware.org/?probe=54ca5c9e74) | Dec 25, 2023 |
| Google        | Madoo                       | Notebook    | [14e757fdb4](https://linux-hardware.org/?probe=14e757fdb4) | Dec 24, 2023 |
| Acer          | Aspire 1810TZ               | Notebook    | [0b4e0e5e2b](https://linux-hardware.org/?probe=0b4e0e5e2b) | Dec 24, 2023 |
| Acer          | Aspire 1810TZ               | Notebook    | [3ba98d8db9](https://linux-hardware.org/?probe=3ba98d8db9) | Dec 24, 2023 |
| Dell          | 0XPDFK A01                  | Desktop     | [538aa9126b](https://linux-hardware.org/?probe=538aa9126b) | Dec 23, 2023 |
| ATARI         | VCS 800 Black Walnut        | Notebook    | [34456982d3](https://linux-hardware.org/?probe=34456982d3) | Dec 23, 2023 |
| Google        | Treeya                      | Notebook    | [b6541ef594](https://linux-hardware.org/?probe=b6541ef594) | Dec 19, 2023 |
| AAEON         | MF-001 V1.0                 | Desktop     | [9e7c59246d](https://linux-hardware.org/?probe=9e7c59246d) | Dec 19, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [6528f813b7](https://linux-hardware.org/?probe=6528f813b7) | Dec 17, 2023 |
| Google        | Candy                       | Notebook    | [be56752bfd](https://linux-hardware.org/?probe=be56752bfd) | Dec 17, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [65d7452931](https://linux-hardware.org/?probe=65d7452931) | Dec 17, 2023 |
| PELADN        | HA-3                        | Desktop     | [cd40102512](https://linux-hardware.org/?probe=cd40102512) | Dec 17, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [acdb6ef8aa](https://linux-hardware.org/?probe=acdb6ef8aa) | Dec 17, 2023 |
| XFX           | MI-9300-7AS9                | Desktop     | [a3015ca40c](https://linux-hardware.org/?probe=a3015ca40c) | Dec 14, 2023 |
| HP            | ZBook 17                    | Notebook    | [d1269ca08c](https://linux-hardware.org/?probe=d1269ca08c) | Dec 13, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [295f9127b0](https://linux-hardware.org/?probe=295f9127b0) | Dec 12, 2023 |
| Lenovo        | 3111 SDK0J40700 WIN 3258... | Mini pc     | [52be4d3e15](https://linux-hardware.org/?probe=52be4d3e15) | Dec 12, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | Desktop     | [e126cdbf4b](https://linux-hardware.org/?probe=e126cdbf4b) | Dec 10, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [2ceba60d03](https://linux-hardware.org/?probe=2ceba60d03) | Dec 09, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [912e908ba0](https://linux-hardware.org/?probe=912e908ba0) | Dec 09, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [213b775f8b](https://linux-hardware.org/?probe=213b775f8b) | Dec 08, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [d4c43fe4f4](https://linux-hardware.org/?probe=d4c43fe4f4) | Dec 08, 2023 |
| Dell          | 0XPDFK A01                  | Desktop     | [5ebbbca196](https://linux-hardware.org/?probe=5ebbbca196) | Dec 04, 2023 |
| Dell          | 0PU052                      | Desktop     | [4a653cc26a](https://linux-hardware.org/?probe=4a653cc26a) | Dec 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [d25f6b4dd3](https://linux-hardware.org/?probe=d25f6b4dd3) | Dec 02, 2023 |
| HP            | EliteBook 655 15.6 inch ... | Notebook    | [5a628a7b0f](https://linux-hardware.org/?probe=5a628a7b0f) | Nov 30, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [3b82362902](https://linux-hardware.org/?probe=3b82362902) | Nov 29, 2023 |
| SGIN          | M15                         | Notebook    | [c7fb994367](https://linux-hardware.org/?probe=c7fb994367) | Nov 28, 2023 |
| Dell          | Latitude E6520              | Notebook    | [a03b74a3d3](https://linux-hardware.org/?probe=a03b74a3d3) | Nov 28, 2023 |
| ASUSTek       | X550ZE                      | Notebook    | [dedc54db8f](https://linux-hardware.org/?probe=dedc54db8f) | Nov 27, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [370ddc00c4](https://linux-hardware.org/?probe=370ddc00c4) | Nov 24, 2023 |
| Chuwi         | X312B                       | Notebook    | [7f13217449](https://linux-hardware.org/?probe=7f13217449) | Nov 23, 2023 |
| eMachines     | EL1358                      | Desktop     | [f22b0b98c3](https://linux-hardware.org/?probe=f22b0b98c3) | Nov 23, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [1e58f5a4f9](https://linux-hardware.org/?probe=1e58f5a4f9) | Nov 21, 2023 |
| MSI           | Raider GE76 12UE            | Notebook    | [bad07cc00d](https://linux-hardware.org/?probe=bad07cc00d) | Nov 20, 2023 |
| Packard Be... | ENLE11BZ                    | Notebook    | [905ad855b3](https://linux-hardware.org/?probe=905ad855b3) | Nov 19, 2023 |
| ASUSTek       | X201E                       | Notebook    | [3532136698](https://linux-hardware.org/?probe=3532136698) | Nov 18, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [d297e1365c](https://linux-hardware.org/?probe=d297e1365c) | Nov 16, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [dde4f98b29](https://linux-hardware.org/?probe=dde4f98b29) | Nov 16, 2023 |
| HUAWEI        | MRGFG-XX                    | Notebook    | [b7dda3ece0](https://linux-hardware.org/?probe=b7dda3ece0) | Nov 14, 2023 |
| Acer          | Extensa 5620                | Notebook    | [3c206e8578](https://linux-hardware.org/?probe=3c206e8578) | Nov 13, 2023 |
| MSI           | MS-7309                     | Desktop     | [c6ca259cae](https://linux-hardware.org/?probe=c6ca259cae) | Nov 13, 2023 |
| Intel         | STK2MV64CC H89290-502       | Desktop     | [041670b7d8](https://linux-hardware.org/?probe=041670b7d8) | Nov 13, 2023 |
| ASUSTek       | T100TAS                     | Notebook    | [ff4068e60a](https://linux-hardware.org/?probe=ff4068e60a) | Nov 12, 2023 |
| HP            | 255 G1                      | Notebook    | [988c1c2454](https://linux-hardware.org/?probe=988c1c2454) | Nov 12, 2023 |
| HP            | 255 G1                      | Notebook    | [9aa30be183](https://linux-hardware.org/?probe=9aa30be183) | Nov 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [fa680be8d9](https://linux-hardware.org/?probe=fa680be8d9) | Nov 10, 2023 |
| ASUSTek       | X550ZE                      | Notebook    | [31d4fc8694](https://linux-hardware.org/?probe=31d4fc8694) | Nov 09, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [94bc809d57](https://linux-hardware.org/?probe=94bc809d57) | Nov 05, 2023 |
| Hampoo        | I2W6_AP135 Reserved         | Notebook    | [cf0c02a17a](https://linux-hardware.org/?probe=cf0c02a17a) | Nov 03, 2023 |
| Hampoo        | I2W6_AP135 Reserved         | Notebook    | [fdb464fed7](https://linux-hardware.org/?probe=fdb464fed7) | Nov 02, 2023 |
| PCChips       | P49G                        | Desktop     | [6b1de00356](https://linux-hardware.org/?probe=6b1de00356) | Nov 02, 2023 |
| ZOTAC         | NM10                        | Desktop     | [5a951d80a6](https://linux-hardware.org/?probe=5a951d80a6) | Oct 31, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [d63ccd5259](https://linux-hardware.org/?probe=d63ccd5259) | Oct 30, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [4f0b8be2f6](https://linux-hardware.org/?probe=4f0b8be2f6) | Oct 30, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [115cf0d371](https://linux-hardware.org/?probe=115cf0d371) | Oct 30, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [6fbbd2a061](https://linux-hardware.org/?probe=6fbbd2a061) | Oct 30, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [48785f697c](https://linux-hardware.org/?probe=48785f697c) | Oct 29, 2023 |
| ASUSTek       | P7P55-M                     | Desktop     | [3fa8a23f12](https://linux-hardware.org/?probe=3fa8a23f12) | Oct 29, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [c86a40c419](https://linux-hardware.org/?probe=c86a40c419) | Oct 28, 2023 |
| Intel         | H61                         | Desktop     | [fccff5fcb2](https://linux-hardware.org/?probe=fccff5fcb2) | Oct 27, 2023 |
| Acer          | Veriton N4660G              | Desktop     | [712511f568](https://linux-hardware.org/?probe=712511f568) | Oct 27, 2023 |
| Acer          | Aspire 9300                 | Notebook    | [3094b549c5](https://linux-hardware.org/?probe=3094b549c5) | Oct 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [358936d398](https://linux-hardware.org/?probe=358936d398) | Oct 25, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [5a23f97862](https://linux-hardware.org/?probe=5a23f97862) | Oct 23, 2023 |
| Dixonsxp      | Unknown                     | Notebook    | [da9f723fd0](https://linux-hardware.org/?probe=da9f723fd0) | Oct 23, 2023 |
| Dell          | XPS 9315                    | Notebook    | [8c9d16e737](https://linux-hardware.org/?probe=8c9d16e737) | Oct 22, 2023 |
| ZOTAC         | NM10                        | Desktop     | [2e0ab67bec](https://linux-hardware.org/?probe=2e0ab67bec) | Oct 21, 2023 |
| HP            | Compaq Presario CQ40        | Notebook    | [5ddf61741f](https://linux-hardware.org/?probe=5ddf61741f) | Oct 20, 2023 |
| HP            | 8265                        | Desktop     | [f1bdedb075](https://linux-hardware.org/?probe=f1bdedb075) | Oct 20, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [8ff07b1c79](https://linux-hardware.org/?probe=8ff07b1c79) | Oct 19, 2023 |
| Positivo      | AT300b                      | Notebook    | [a39989b55b](https://linux-hardware.org/?probe=a39989b55b) | Oct 18, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [c60b3dbfa2](https://linux-hardware.org/?probe=c60b3dbfa2) | Oct 17, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20D900... | Notebook    | [9d142e587e](https://linux-hardware.org/?probe=9d142e587e) | Oct 17, 2023 |
| Acer          | Aspire A314-23P             | Notebook    | [99490448ae](https://linux-hardware.org/?probe=99490448ae) | Oct 16, 2023 |
| Acer          | Aspire A314-23P             | Notebook    | [431b672bf5](https://linux-hardware.org/?probe=431b672bf5) | Oct 16, 2023 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [1f161ae269](https://linux-hardware.org/?probe=1f161ae269) | Oct 16, 2023 |
| Google        | Careena                     | Notebook    | [8359c8c3e8](https://linux-hardware.org/?probe=8359c8c3e8) | Oct 15, 2023 |
| Google        | Careena                     | Notebook    | [4292c49150](https://linux-hardware.org/?probe=4292c49150) | Oct 15, 2023 |
| HP            | Notebook                    | Notebook    | [fb39ee7d9d](https://linux-hardware.org/?probe=fb39ee7d9d) | Oct 13, 2023 |
| Thomson       | NEO14-4W64                  | Notebook    | [f68e52a8a1](https://linux-hardware.org/?probe=f68e52a8a1) | Oct 12, 2023 |
| BLANK         | Intel powered classmate ... | Notebook    | [78cc4b7937](https://linux-hardware.org/?probe=78cc4b7937) | Oct 11, 2023 |
| BLANK         | Intel powered classmate ... | Notebook    | [bc4093e3c7](https://linux-hardware.org/?probe=bc4093e3c7) | Oct 11, 2023 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [ee4617fa73](https://linux-hardware.org/?probe=ee4617fa73) | Oct 10, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [2bb1495e06](https://linux-hardware.org/?probe=2bb1495e06) | Oct 08, 2023 |
| Google        | Sasuke                      | Notebook    | [ea2d350776](https://linux-hardware.org/?probe=ea2d350776) | Oct 08, 2023 |
| ASRock        | Q1900B-ITX                  | Desktop     | [f8ad7736e2](https://linux-hardware.org/?probe=f8ad7736e2) | Oct 07, 2023 |
| Insyde        | Braswell                    | Notebook    | [c4261097f5](https://linux-hardware.org/?probe=c4261097f5) | Oct 07, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [bf8761b854](https://linux-hardware.org/?probe=bf8761b854) | Oct 06, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [ae4ee327c0](https://linux-hardware.org/?probe=ae4ee327c0) | Oct 06, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [f88a18cfef](https://linux-hardware.org/?probe=f88a18cfef) | Oct 06, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [92e214fb3e](https://linux-hardware.org/?probe=92e214fb3e) | Oct 04, 2023 |
| Getac         | X500G3                      | Notebook    | [919772eed0](https://linux-hardware.org/?probe=919772eed0) | Oct 02, 2023 |
| Panasonic     | CF-F9KWPZFFE                | Notebook    | [33cf16d622](https://linux-hardware.org/?probe=33cf16d622) | Oct 01, 2023 |
| Dell          | 0JP3NX A01                  | Desktop     | [d14bc5c139](https://linux-hardware.org/?probe=d14bc5c139) | Sep 27, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [f4326ad956](https://linux-hardware.org/?probe=f4326ad956) | Sep 26, 2023 |
| ASUSTek       | E1600WKA                    | All in one  | [43c8a9b758](https://linux-hardware.org/?probe=43c8a9b758) | Sep 26, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [3ff273b73c](https://linux-hardware.org/?probe=3ff273b73c) | Sep 26, 2023 |
| Intel         | H61                         | Desktop     | [ee0266b53c](https://linux-hardware.org/?probe=ee0266b53c) | Sep 25, 2023 |
| ASUSTek       | X451MA                      | Notebook    | [ed779c5de4](https://linux-hardware.org/?probe=ed779c5de4) | Sep 20, 2023 |
| IceWhale T... | ZimaBoard 216 ZMB           | Desktop     | [7b1aae3e2b](https://linux-hardware.org/?probe=7b1aae3e2b) | Sep 20, 2023 |
| Mini PC       | Cherry Trail CR             | Notebook    | [f16d8d4254](https://linux-hardware.org/?probe=f16d8d4254) | Sep 19, 2023 |
| Apple         | Mac-7BA5B2D9E42DDD94 iMa... | Desktop     | [47d423039b](https://linux-hardware.org/?probe=47d423039b) | Sep 19, 2023 |
| Dell          | Precision 3570              | Notebook    | [fd3441ff1d](https://linux-hardware.org/?probe=fd3441ff1d) | Sep 18, 2023 |
| Google        | Blooglet                    | Notebook    | [79ce749655](https://linux-hardware.org/?probe=79ce749655) | Sep 17, 2023 |
| Intel         | D945GCZ AAD32112-503        | Desktop     | [806f698174](https://linux-hardware.org/?probe=806f698174) | Sep 14, 2023 |
| HP            | 15                          | Notebook    | [03e1207549](https://linux-hardware.org/?probe=03e1207549) | Sep 12, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [04666fa9b7](https://linux-hardware.org/?probe=04666fa9b7) | Sep 11, 2023 |
| HP            | 2000                        | Notebook    | [48790bd831](https://linux-hardware.org/?probe=48790bd831) | Sep 09, 2023 |
| HP            | 2000                        | Notebook    | [ce9ba2b7c4](https://linux-hardware.org/?probe=ce9ba2b7c4) | Sep 09, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [6aea4eb6c4](https://linux-hardware.org/?probe=6aea4eb6c4) | Sep 09, 2023 |
| eMachines     | eM350                       | Notebook    | [fae8f9e3f1](https://linux-hardware.org/?probe=fae8f9e3f1) | Sep 06, 2023 |
| Dell          | Latitude 3190               | Notebook    | [60f82737fa](https://linux-hardware.org/?probe=60f82737fa) | Sep 06, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [89f4028960](https://linux-hardware.org/?probe=89f4028960) | Sep 05, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [23f0f9321c](https://linux-hardware.org/?probe=23f0f9321c) | Sep 05, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [7d6ff14b38](https://linux-hardware.org/?probe=7d6ff14b38) | Sep 05, 2023 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [69fec63660](https://linux-hardware.org/?probe=69fec63660) | Sep 04, 2023 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [ea00f871b9](https://linux-hardware.org/?probe=ea00f871b9) | Sep 04, 2023 |
| HP            | 255 G2                      | Notebook    | [27b48aa011](https://linux-hardware.org/?probe=27b48aa011) | Sep 02, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [8ba55e98ec](https://linux-hardware.org/?probe=8ba55e98ec) | Sep 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [d169572a6b](https://linux-hardware.org/?probe=d169572a6b) | Aug 31, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [ddcb97361b](https://linux-hardware.org/?probe=ddcb97361b) | Aug 30, 2023 |
| ASUSTek       | X75VD                       | Notebook    | [cab1480dc6](https://linux-hardware.org/?probe=cab1480dc6) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [2bd35d44f1](https://linux-hardware.org/?probe=2bd35d44f1) | Aug 29, 2023 |
| Packard Be... | EasyNote TJ65               | Notebook    | [f37ab96772](https://linux-hardware.org/?probe=f37ab96772) | Aug 28, 2023 |
| HP            | EliteBook 830 G8 Noteboo... | Notebook    | [7abf0d31d8](https://linux-hardware.org/?probe=7abf0d31d8) | Aug 28, 2023 |
| Toshiba       | Satellite P770              | Notebook    | [8618c83c93](https://linux-hardware.org/?probe=8618c83c93) | Aug 26, 2023 |
| Google        | Robo                        | Notebook    | [dfa74d0961](https://linux-hardware.org/?probe=dfa74d0961) | Aug 26, 2023 |
| Acer          | Predator G3610              | Desktop     | [04153b05c7](https://linux-hardware.org/?probe=04153b05c7) | Aug 22, 2023 |
| Compal        | PBL20                       | Notebook    | [ae09076b4e](https://linux-hardware.org/?probe=ae09076b4e) | Aug 22, 2023 |
| HP            | Notebook                    | Notebook    | [11d2993965](https://linux-hardware.org/?probe=11d2993965) | Aug 20, 2023 |
| Google        | Madoo                       | Notebook    | [8eea1017dc](https://linux-hardware.org/?probe=8eea1017dc) | Aug 20, 2023 |
| HP            | Notebook                    | Notebook    | [f6e4865586](https://linux-hardware.org/?probe=f6e4865586) | Aug 19, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [3dfc4104a4](https://linux-hardware.org/?probe=3dfc4104a4) | Aug 18, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [62ecbe2f01](https://linux-hardware.org/?probe=62ecbe2f01) | Aug 18, 2023 |
| Inventec      | DQ Class A02                | Desktop     | [92a3afc475](https://linux-hardware.org/?probe=92a3afc475) | Aug 17, 2023 |
| Lenovo        | ThinkPad T430 2349TFK       | Notebook    | [390899a281](https://linux-hardware.org/?probe=390899a281) | Aug 17, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [dd8d164747](https://linux-hardware.org/?probe=dd8d164747) | Aug 17, 2023 |
| Acer          | Aspire 5050                 | Notebook    | [63329f0ff6](https://linux-hardware.org/?probe=63329f0ff6) | Aug 16, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [374096baa6](https://linux-hardware.org/?probe=374096baa6) | Aug 15, 2023 |
| ASUSTek       | BM6875_BM6675_BP6375        | Desktop     | [0a2cdad4c1](https://linux-hardware.org/?probe=0a2cdad4c1) | Aug 15, 2023 |
| Apple         | Mac-F223BEC8                | Desktop     | [74a3be9a4a](https://linux-hardware.org/?probe=74a3be9a4a) | Aug 14, 2023 |
| HP            | Pavilion g7                 | Notebook    | [43351d6476](https://linux-hardware.org/?probe=43351d6476) | Aug 12, 2023 |
| Positivo      | C4128B-1                    | Convertible | [ef67e885dc](https://linux-hardware.org/?probe=ef67e885dc) | Aug 11, 2023 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | Notebook    | [abaa0512b0](https://linux-hardware.org/?probe=abaa0512b0) | Aug 11, 2023 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [0028486d9d](https://linux-hardware.org/?probe=0028486d9d) | Aug 10, 2023 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [459b9f31b9](https://linux-hardware.org/?probe=459b9f31b9) | Aug 09, 2023 |
| Shuttle       | XS35V3                      | Desktop     | [ced8776e4d](https://linux-hardware.org/?probe=ced8776e4d) | Aug 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [81411c1db8](https://linux-hardware.org/?probe=81411c1db8) | Aug 08, 2023 |
| Toshiba       | Satellite L875D             | Notebook    | [de1a418102](https://linux-hardware.org/?probe=de1a418102) | Aug 08, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [3e037493db](https://linux-hardware.org/?probe=3e037493db) | Aug 06, 2023 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [ffbbe60721](https://linux-hardware.org/?probe=ffbbe60721) | Aug 05, 2023 |
| Dell          | Inspiron 5720               | Notebook    | [20532065b5](https://linux-hardware.org/?probe=20532065b5) | Aug 04, 2023 |
| Dell          | Inspiron 5720               | Notebook    | [8f6ada13fa](https://linux-hardware.org/?probe=8f6ada13fa) | Aug 04, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ca00849760](https://linux-hardware.org/?probe=ca00849760) | Aug 02, 2023 |
| HP            | Pavilion 15                 | Notebook    | [257fe62454](https://linux-hardware.org/?probe=257fe62454) | Aug 02, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [00d2ac7698](https://linux-hardware.org/?probe=00d2ac7698) | Aug 01, 2023 |
| Shuttle       | XS35V3                      | Desktop     | [52c5dda710](https://linux-hardware.org/?probe=52c5dda710) | Jul 31, 2023 |
| AAEON         | MF-001 V1.0                 | Desktop     | [1a2d3f1778](https://linux-hardware.org/?probe=1a2d3f1778) | Jul 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [80a34d344b](https://linux-hardware.org/?probe=80a34d344b) | Jul 28, 2023 |
| Unknown       | SCHNEIDER                   | Desktop     | [6ab609f07e](https://linux-hardware.org/?probe=6ab609f07e) | Jul 27, 2023 |
| Dell          | Inspiron 1520               | Notebook    | [a119f99239](https://linux-hardware.org/?probe=a119f99239) | Jul 27, 2023 |
| Unknown       | T3 MRD                      | Desktop     | [5539799efa](https://linux-hardware.org/?probe=5539799efa) | Jul 26, 2023 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [5ca26c7da9](https://linux-hardware.org/?probe=5ca26c7da9) | Jul 26, 2023 |
| Lenovo        | ThinkPad T61 7659WCN        | Notebook    | [f447bc27b2](https://linux-hardware.org/?probe=f447bc27b2) | Jul 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4fe4e8b639](https://linux-hardware.org/?probe=4fe4e8b639) | Jul 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [742d3b24c8](https://linux-hardware.org/?probe=742d3b24c8) | Jul 24, 2023 |
| Unknown       | Toshiba AC100 / Dynabook... | Notebook    | [c7dd142af9](https://linux-hardware.org/?probe=c7dd142af9) | Jul 24, 2023 |
| Dell          | Inspiron 5576               | Notebook    | [54c338bb01](https://linux-hardware.org/?probe=54c338bb01) | Jul 22, 2023 |
| Dell          | Inspiron 5576               | Notebook    | [6654328e2c](https://linux-hardware.org/?probe=6654328e2c) | Jul 22, 2023 |
| HP            | 2187 A01                    | Desktop     | [efd197811b](https://linux-hardware.org/?probe=efd197811b) | Jul 22, 2023 |
| HP            | 3646h                       | Desktop     | [01f2207fe0](https://linux-hardware.org/?probe=01f2207fe0) | Jul 22, 2023 |
| Acer          | Aspire SW3-013              | Notebook    | [b503fa1044](https://linux-hardware.org/?probe=b503fa1044) | Jul 21, 2023 |
| Dell          | Latitude 5290               | Notebook    | [66860827b9](https://linux-hardware.org/?probe=66860827b9) | Jul 21, 2023 |
| ASUSTek       | ROG Strix G733QR_G733QR     | Notebook    | [cd8a01d7ab](https://linux-hardware.org/?probe=cd8a01d7ab) | Jul 19, 2023 |
| Fujitsu       | FMVNC4BC4                   | Notebook    | [14249b136a](https://linux-hardware.org/?probe=14249b136a) | Jul 19, 2023 |
| Acer          | Aspire E1-771               | Notebook    | [9d53aeea5a](https://linux-hardware.org/?probe=9d53aeea5a) | Jul 19, 2023 |
| HP            | 255 G2                      | Notebook    | [eaf9befa3a](https://linux-hardware.org/?probe=eaf9befa3a) | Jul 19, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [07809870aa](https://linux-hardware.org/?probe=07809870aa) | Jul 19, 2023 |
| LG Electro... | 15Z90N-U.ARS5U1             | Notebook    | [54b03a096b](https://linux-hardware.org/?probe=54b03a096b) | Jul 19, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [2d896167d8](https://linux-hardware.org/?probe=2d896167d8) | Jul 16, 2023 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [493d7a5ab7](https://linux-hardware.org/?probe=493d7a5ab7) | Jul 12, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [d0035bb703](https://linux-hardware.org/?probe=d0035bb703) | Jul 10, 2023 |
| Gateway       | ZX4250                      | All in one  | [8fb942eccd](https://linux-hardware.org/?probe=8fb942eccd) | Jul 10, 2023 |
| Gateway       | ZX4250                      | All in one  | [ff650dc0df](https://linux-hardware.org/?probe=ff650dc0df) | Jul 10, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [2f1b70e168](https://linux-hardware.org/?probe=2f1b70e168) | Jul 08, 2023 |
| Acer          | Aspire E5-523G              | Notebook    | [6535e7c6d1](https://linux-hardware.org/?probe=6535e7c6d1) | Jul 08, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [282c9db256](https://linux-hardware.org/?probe=282c9db256) | Jul 08, 2023 |
| Dell          | Inspiron 13-5378            | Notebook    | [8337bfbb61](https://linux-hardware.org/?probe=8337bfbb61) | Jul 08, 2023 |
| Acer          | Swift SFE16-42              | Notebook    | [c8b8a7d737](https://linux-hardware.org/?probe=c8b8a7d737) | Jul 07, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [632958a27e](https://linux-hardware.org/?probe=632958a27e) | Jul 07, 2023 |
| HP            | ProBook 4525s               | Notebook    | [e70917548c](https://linux-hardware.org/?probe=e70917548c) | Jul 07, 2023 |
| Unknown       | Unknown                     | Other       | [f49e789b52](https://linux-hardware.org/?probe=f49e789b52) | Jul 04, 2023 |
| Lenovo        | ThinkPad T430 2349G7G       | Notebook    | [b0eefed750](https://linux-hardware.org/?probe=b0eefed750) | Jul 03, 2023 |
| Google        | Pyro                        | Notebook    | [9632e7a77b](https://linux-hardware.org/?probe=9632e7a77b) | Jul 02, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [b6b1cf5b68](https://linux-hardware.org/?probe=b6b1cf5b68) | Jul 02, 2023 |
| Dell          | 0T656F A02                  | Desktop     | [e9b879f3ff](https://linux-hardware.org/?probe=e9b879f3ff) | Jul 02, 2023 |
| eMachines     | eME443                      | Notebook    | [0d6808da66](https://linux-hardware.org/?probe=0d6808da66) | Jun 30, 2023 |
| UMAX          | VisionBook 14Wr Plus        | Notebook    | [5f838f5922](https://linux-hardware.org/?probe=5f838f5922) | Jun 28, 2023 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [d4b8002633](https://linux-hardware.org/?probe=d4b8002633) | Jun 28, 2023 |
| Sony          | VPCEB37FD                   | Notebook    | [afe6ac4f32](https://linux-hardware.org/?probe=afe6ac4f32) | Jun 27, 2023 |
| Intel         | NUC11ATBC4 M53051-400       | Mini pc     | [7c6c7cff66](https://linux-hardware.org/?probe=7c6c7cff66) | Jun 26, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [fa54c60ae0](https://linux-hardware.org/?probe=fa54c60ae0) | Jun 26, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [f0268ac6a8](https://linux-hardware.org/?probe=f0268ac6a8) | Jun 26, 2023 |
| Microsoft     | Surface 3                   | Tablet      | [e094f469bc](https://linux-hardware.org/?probe=e094f469bc) | Jun 25, 2023 |
| Sony          | VPCEB37FD                   | Notebook    | [e8d24fe375](https://linux-hardware.org/?probe=e8d24fe375) | Jun 25, 2023 |
| HP            | InsydeH2O EFI BIOS          | Notebook    | [f8d0ce645a](https://linux-hardware.org/?probe=f8d0ce645a) | Jun 23, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [234a73d6b0](https://linux-hardware.org/?probe=234a73d6b0) | Jun 23, 2023 |
| Toshiba       | Satellite P200              | Notebook    | [19350653f7](https://linux-hardware.org/?probe=19350653f7) | Jun 23, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [6e4fe4f0c8](https://linux-hardware.org/?probe=6e4fe4f0c8) | Jun 22, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [004f9be7a7](https://linux-hardware.org/?probe=004f9be7a7) | Jun 21, 2023 |
| Pencents      | U50 Standard                | Mini pc     | [96db8365b1](https://linux-hardware.org/?probe=96db8365b1) | Jun 20, 2023 |
| TrekStor      | SurfTab wintron 7.0 ST70... | Notebook    | [b61b22c866](https://linux-hardware.org/?probe=b61b22c866) | Jun 20, 2023 |
| ASUSTek       | 1011CX                      | Notebook    | [0fa6b0b3dc](https://linux-hardware.org/?probe=0fa6b0b3dc) | Jun 19, 2023 |
| ASRock        | J4125-ITX                   | Desktop     | [b4c617c995](https://linux-hardware.org/?probe=b4c617c995) | Jun 19, 2023 |
| HP            | ProBook 650 G3              | Notebook    | [009fdf15c4](https://linux-hardware.org/?probe=009fdf15c4) | Jun 19, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [e4c0eeb007](https://linux-hardware.org/?probe=e4c0eeb007) | Jun 17, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [f52a0ddf99](https://linux-hardware.org/?probe=f52a0ddf99) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [7b9388df1b](https://linux-hardware.org/?probe=7b9388df1b) | Jun 16, 2023 |
| Fujitsu       | D3049-B1 S26361-D3049-B1... | Server      | [af1a5cda08](https://linux-hardware.org/?probe=af1a5cda08) | Jun 16, 2023 |
| Dell          | Precision 3570              | Notebook    | [6f6debf1a4](https://linux-hardware.org/?probe=6f6debf1a4) | Jun 15, 2023 |
| Pegatron      | 2A73h                       | Desktop     | [a96d9ae076](https://linux-hardware.org/?probe=a96d9ae076) | Jun 15, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [dae8f5a0b4](https://linux-hardware.org/?probe=dae8f5a0b4) | Jun 15, 2023 |
| HP            | 21B4 A01                    | Desktop     | [16b576ebea](https://linux-hardware.org/?probe=16b576ebea) | Jun 15, 2023 |
| Lenovo        | IdeaPad Y580                | Notebook    | [699cb9ac1e](https://linux-hardware.org/?probe=699cb9ac1e) | Jun 13, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [b843a66531](https://linux-hardware.org/?probe=b843a66531) | Jun 11, 2023 |
| Lenovo        | ThinkPad X201 3249CTO       | Notebook    | [849dbace60](https://linux-hardware.org/?probe=849dbace60) | Jun 09, 2023 |
| HP            | 3646h                       | Desktop     | [046f5d1a5b](https://linux-hardware.org/?probe=046f5d1a5b) | Jun 09, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [c85cff4000](https://linux-hardware.org/?probe=c85cff4000) | Jun 08, 2023 |
| Sony          | VPCEH2E1R                   | Notebook    | [97e5366810](https://linux-hardware.org/?probe=97e5366810) | Jun 08, 2023 |
| HP            | 3646h                       | Desktop     | [02353b5e9f](https://linux-hardware.org/?probe=02353b5e9f) | Jun 06, 2023 |
| HP            | 240 G3                      | Notebook    | [475e3e63ef](https://linux-hardware.org/?probe=475e3e63ef) | Jun 05, 2023 |
| Shanghai Z... | ZEB20 TBD                   | Mini pc     | [b6411e69f3](https://linux-hardware.org/?probe=b6411e69f3) | Jun 04, 2023 |
| HP            | 3397                        | Desktop     | [046df77f81](https://linux-hardware.org/?probe=046df77f81) | Jun 02, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [3138d92b76](https://linux-hardware.org/?probe=3138d92b76) | Jun 01, 2023 |
| Samsung       | N150/N210/N220              | Notebook    | [449400ebe9](https://linux-hardware.org/?probe=449400ebe9) | May 31, 2023 |
| Shanghai Z... | ZEB20 TBD                   | Mini pc     | [1375d36b0f](https://linux-hardware.org/?probe=1375d36b0f) | May 28, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [88c6b12404](https://linux-hardware.org/?probe=88c6b12404) | May 27, 2023 |
| Shanghai Z... | ZEB20 TBD                   | Mini pc     | [84953a504d](https://linux-hardware.org/?probe=84953a504d) | May 26, 2023 |
| Dell          | Latitude E6430              | Notebook    | [37dab72e8c](https://linux-hardware.org/?probe=37dab72e8c) | May 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [cbab0f6dd8](https://linux-hardware.org/?probe=cbab0f6dd8) | May 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [a1a76abc51](https://linux-hardware.org/?probe=a1a76abc51) | May 24, 2023 |
| ASUSTek       | X450CC                      | Notebook    | [ca431e5e80](https://linux-hardware.org/?probe=ca431e5e80) | May 24, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [20c80a45a8](https://linux-hardware.org/?probe=20c80a45a8) | May 22, 2023 |
| Foxconn       | G41MXE-V                    | Desktop     | [ffc74ae329](https://linux-hardware.org/?probe=ffc74ae329) | May 21, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [bd6409ee58](https://linux-hardware.org/?probe=bd6409ee58) | May 19, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [2d944abb09](https://linux-hardware.org/?probe=2d944abb09) | May 19, 2023 |
| ASUSTek       | A88XM-A                     | Desktop     | [eea6382d39](https://linux-hardware.org/?probe=eea6382d39) | May 19, 2023 |
| HP            | ProBook 650 G3              | Notebook    | [ce80a21736](https://linux-hardware.org/?probe=ce80a21736) | May 19, 2023 |
| ZOTAC         | NM10                        | Desktop     | [0be7755cf9](https://linux-hardware.org/?probe=0be7755cf9) | May 19, 2023 |
| PCWare        | IPX1800E2                   | Desktop     | [f19d94af88](https://linux-hardware.org/?probe=f19d94af88) | May 18, 2023 |
| PCWare        | IPX1800E2                   | Desktop     | [a75df73ade](https://linux-hardware.org/?probe=a75df73ade) | May 18, 2023 |
| Lenovo        | ThinkPad T400 276522G       | Notebook    | [dc8b38dd37](https://linux-hardware.org/?probe=dc8b38dd37) | May 17, 2023 |
| Google        | Snappy                      | Notebook    | [0c095bb37a](https://linux-hardware.org/?probe=0c095bb37a) | May 17, 2023 |
| Hampoo        | Cherry Trail CR V200        | Notebook    | [1167f27914](https://linux-hardware.org/?probe=1167f27914) | May 15, 2023 |
| Medion        | Akoya P6660 MD99790         | Notebook    | [20ecc9b5dc](https://linux-hardware.org/?probe=20ecc9b5dc) | May 15, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [0145d107e8](https://linux-hardware.org/?probe=0145d107e8) | May 15, 2023 |
| Intel         | W7650                       | Notebook    | [a672f7199c](https://linux-hardware.org/?probe=a672f7199c) | May 14, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [5f3a14748e](https://linux-hardware.org/?probe=5f3a14748e) | May 13, 2023 |
| Toshiba       | Satellite Radius P55W-B     | Notebook    | [e2ed5e2135](https://linux-hardware.org/?probe=e2ed5e2135) | May 11, 2023 |
| Acer          | EQ45M                       | Desktop     | [57fa86c8dc](https://linux-hardware.org/?probe=57fa86c8dc) | May 11, 2023 |
| libre-comp... | roc-rk3328-cc               | Soc         | [9709c9cf35](https://linux-hardware.org/?probe=9709c9cf35) | May 09, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [0b08b7a631](https://linux-hardware.org/?probe=0b08b7a631) | May 09, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [a08e2235cd](https://linux-hardware.org/?probe=a08e2235cd) | May 09, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [5438ddaf64](https://linux-hardware.org/?probe=5438ddaf64) | May 08, 2023 |
| HP            | Notebook                    | Notebook    | [70ee3adf89](https://linux-hardware.org/?probe=70ee3adf89) | May 08, 2023 |
| Samsung       | 530XBB                      | Notebook    | [4d039b72a7](https://linux-hardware.org/?probe=4d039b72a7) | May 08, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [8b7b41fde9](https://linux-hardware.org/?probe=8b7b41fde9) | May 07, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [f830561f82](https://linux-hardware.org/?probe=f830561f82) | May 07, 2023 |
| Unknown       | Unknown                     | Notebook    | [cacf6a8831](https://linux-hardware.org/?probe=cacf6a8831) | May 07, 2023 |
| HP            | x2 210                      | Notebook    | [f60c4cb29b](https://linux-hardware.org/?probe=f60c4cb29b) | May 07, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [3daf4fbc68](https://linux-hardware.org/?probe=3daf4fbc68) | May 07, 2023 |
| Dell          | Latitude E6520              | Notebook    | [e6309dff56](https://linux-hardware.org/?probe=e6309dff56) | May 05, 2023 |
| Google        | Glimmer                     | Notebook    | [c9ccc1f6c9](https://linux-hardware.org/?probe=c9ccc1f6c9) | May 02, 2023 |
| Google        | Glimmer                     | Notebook    | [f4558038dd](https://linux-hardware.org/?probe=f4558038dd) | May 02, 2023 |
| Unknown       | Phitronics N68C-M           | Desktop     | [77747ce79b](https://linux-hardware.org/?probe=77747ce79b) | May 02, 2023 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [4eb2bc6e88](https://linux-hardware.org/?probe=4eb2bc6e88) | May 01, 2023 |
| NEC Comput... | ECS-945G                    | Desktop     | [5f6daf506f](https://linux-hardware.org/?probe=5f6daf506f) | May 01, 2023 |
| Sony          | SVF1521C6EW                 | Notebook    | [57e1c14061](https://linux-hardware.org/?probe=57e1c14061) | Apr 30, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [e1d1572c51](https://linux-hardware.org/?probe=e1d1572c51) | Apr 30, 2023 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [6976f884e6](https://linux-hardware.org/?probe=6976f884e6) | Apr 29, 2023 |
| HP            | Laptop 15-bs2xx             | Notebook    | [ad768363bc](https://linux-hardware.org/?probe=ad768363bc) | Apr 28, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [e80ea5c4ae](https://linux-hardware.org/?probe=e80ea5c4ae) | Apr 28, 2023 |
| Google        | Chell                       | Notebook    | [1d1b263f21](https://linux-hardware.org/?probe=1d1b263f21) | Apr 27, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [e9237f0d53](https://linux-hardware.org/?probe=e9237f0d53) | Apr 27, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [ce4700304c](https://linux-hardware.org/?probe=ce4700304c) | Apr 26, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [4db8688749](https://linux-hardware.org/?probe=4db8688749) | Apr 25, 2023 |
| AXIOO         | MYBOOK-14 .B001             | Notebook    | [38d6a9b3d2](https://linux-hardware.org/?probe=38d6a9b3d2) | Apr 25, 2023 |
| ASUSTek       | F1A55-M LK R2.0             | Desktop     | [234e0d0738](https://linux-hardware.org/?probe=234e0d0738) | Apr 23, 2023 |
| Dell          | Latitude 5290               | Notebook    | [54f92464ba](https://linux-hardware.org/?probe=54f92464ba) | Apr 23, 2023 |
| HP            | G42                         | Notebook    | [dd87e935d0](https://linux-hardware.org/?probe=dd87e935d0) | Apr 20, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [f79af9bad0](https://linux-hardware.org/?probe=f79af9bad0) | Apr 20, 2023 |
| Acer          | Aspire 5735                 | Notebook    | [2d8d4a8124](https://linux-hardware.org/?probe=2d8d4a8124) | Apr 20, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [00ed2824f0](https://linux-hardware.org/?probe=00ed2824f0) | Apr 20, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [7a4242a973](https://linux-hardware.org/?probe=7a4242a973) | Apr 19, 2023 |
| HP            | Pavilion 15                 | Notebook    | [d0c3e2bb4e](https://linux-hardware.org/?probe=d0c3e2bb4e) | Apr 19, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [70a0b986fa](https://linux-hardware.org/?probe=70a0b986fa) | Apr 18, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | Notebook    | [db4749ffef](https://linux-hardware.org/?probe=db4749ffef) | Apr 18, 2023 |
| HP            | InsydeH2O EFI BIOS          | Notebook    | [c64154e569](https://linux-hardware.org/?probe=c64154e569) | Apr 17, 2023 |
| GPU Compan... | GWTN116-3                   | Notebook    | [e233174fb3](https://linux-hardware.org/?probe=e233174fb3) | Apr 17, 2023 |
| Lenovo        | ThinkPad X240 20AMS0RR00    | Notebook    | [db0d2a4c4e](https://linux-hardware.org/?probe=db0d2a4c4e) | Apr 14, 2023 |
| HP            | Pavilion 15                 | Notebook    | [199f3bb771](https://linux-hardware.org/?probe=199f3bb771) | Apr 14, 2023 |
| HP            | Pavilion dv6                | Notebook    | [d938ba339d](https://linux-hardware.org/?probe=d938ba339d) | Apr 14, 2023 |
| Intel         | W7650                       | Notebook    | [3e4c54a5f0](https://linux-hardware.org/?probe=3e4c54a5f0) | Apr 11, 2023 |
| Lenovo        | ThinkPad T530 2394BF7       | Notebook    | [5161d2f521](https://linux-hardware.org/?probe=5161d2f521) | Apr 11, 2023 |
| MSI           | H310M PRO-VD                | Desktop     | [498c52e62e](https://linux-hardware.org/?probe=498c52e62e) | Apr 10, 2023 |
| Toshiba       | Satellite P70-A             | Notebook    | [6ffb7a79ef](https://linux-hardware.org/?probe=6ffb7a79ef) | Apr 06, 2023 |
| Acer          | Aspire E1-570               | Notebook    | [ad70ba8e9d](https://linux-hardware.org/?probe=ad70ba8e9d) | Apr 05, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [33d6b0fbc8](https://linux-hardware.org/?probe=33d6b0fbc8) | Apr 05, 2023 |
| HP            | Pavilion 15                 | Notebook    | [f982fd86f7](https://linux-hardware.org/?probe=f982fd86f7) | Apr 05, 2023 |
| AXIOO         | MYBOOK-14 .B001             | Notebook    | [edba1216c0](https://linux-hardware.org/?probe=edba1216c0) | Apr 04, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [5f29b020ab](https://linux-hardware.org/?probe=5f29b020ab) | Apr 04, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b16afcac8b](https://linux-hardware.org/?probe=b16afcac8b) | Apr 03, 2023 |
| ASRock        | G31M-S                      | Desktop     | [70f35c82f1](https://linux-hardware.org/?probe=70f35c82f1) | Apr 03, 2023 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [aead33a5e6](https://linux-hardware.org/?probe=aead33a5e6) | Apr 01, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [0e18c3546c](https://linux-hardware.org/?probe=0e18c3546c) | Apr 01, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [f243351def](https://linux-hardware.org/?probe=f243351def) | Mar 31, 2023 |
| ASRock        | G31M-S                      | Desktop     | [4ad324790c](https://linux-hardware.org/?probe=4ad324790c) | Mar 28, 2023 |
| ASRock        | G31M-S                      | Desktop     | [225f122e05](https://linux-hardware.org/?probe=225f122e05) | Mar 28, 2023 |
| YANYU         | ITX-S192                    | Desktop     | [0d2fb6a8d7](https://linux-hardware.org/?probe=0d2fb6a8d7) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [fe79f70952](https://linux-hardware.org/?probe=fe79f70952) | Mar 27, 2023 |
| Pegatron      | Acacia                      | Desktop     | [4ce0966b14](https://linux-hardware.org/?probe=4ce0966b14) | Mar 26, 2023 |
| Pegatron      | Acacia                      | Desktop     | [4faa2a52d3](https://linux-hardware.org/?probe=4faa2a52d3) | Mar 26, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [35eaaaac45](https://linux-hardware.org/?probe=35eaaaac45) | Mar 26, 2023 |
| Packard Be... | EasyNote SB65               | Notebook    | [f49cf1aa7a](https://linux-hardware.org/?probe=f49cf1aa7a) | Mar 25, 2023 |
| ASRock        | N68-GS4/USB3 FX             | Desktop     | [b846b11174](https://linux-hardware.org/?probe=b846b11174) | Mar 25, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [872e7f18c5](https://linux-hardware.org/?probe=872e7f18c5) | Mar 24, 2023 |
| ASRock        | H110M-HDV                   | Desktop     | [cfe369e6b8](https://linux-hardware.org/?probe=cfe369e6b8) | Mar 24, 2023 |
| Samsung       | 530XBB                      | Notebook    | [2bb5946ee7](https://linux-hardware.org/?probe=2bb5946ee7) | Mar 23, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [104f6a754e](https://linux-hardware.org/?probe=104f6a754e) | Mar 22, 2023 |
| HP            | 89DC 0100                   | All in one  | [d8afbb81f9](https://linux-hardware.org/?probe=d8afbb81f9) | Mar 21, 2023 |
| Acer          | Aspire one 1-131            | Notebook    | [ea5065ef8f](https://linux-hardware.org/?probe=ea5065ef8f) | Mar 21, 2023 |
| Dell          | Precision M3800             | Notebook    | [1d20598cc5](https://linux-hardware.org/?probe=1d20598cc5) | Mar 17, 2023 |
| ASRock        | H110M-HDV                   | Desktop     | [5228141efd](https://linux-hardware.org/?probe=5228141efd) | Mar 16, 2023 |
| Dell          | Latitude 5290               | Notebook    | [2b4d5d7866](https://linux-hardware.org/?probe=2b4d5d7866) | Mar 15, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [2d5d0e42c5](https://linux-hardware.org/?probe=2d5d0e42c5) | Mar 15, 2023 |
| Dell          | Latitude 7480               | Notebook    | [2c1cca300c](https://linux-hardware.org/?probe=2c1cca300c) | Mar 13, 2023 |
| Gigabyte      | MJPLNBB-00                  | Desktop     | [e8c31757e0](https://linux-hardware.org/?probe=e8c31757e0) | Mar 12, 2023 |
| Positivo      | P5VD2-MX                    | Desktop     | [50b7084313](https://linux-hardware.org/?probe=50b7084313) | Mar 12, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [309d95f00f](https://linux-hardware.org/?probe=309d95f00f) | Mar 11, 2023 |
| BANGHO        | LITE E34                    | Desktop     | [39f7b525e2](https://linux-hardware.org/?probe=39f7b525e2) | Mar 10, 2023 |
| MSI           | S12T 3M/S12 3M              | Notebook    | [b12ff30d25](https://linux-hardware.org/?probe=b12ff30d25) | Mar 09, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [4167bec602](https://linux-hardware.org/?probe=4167bec602) | Mar 09, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [3710f0f407](https://linux-hardware.org/?probe=3710f0f407) | Mar 07, 2023 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [256a8abb58](https://linux-hardware.org/?probe=256a8abb58) | Mar 06, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [3356f97e00](https://linux-hardware.org/?probe=3356f97e00) | Mar 06, 2023 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [dbe64de6bd](https://linux-hardware.org/?probe=dbe64de6bd) | Mar 06, 2023 |
| ASUSTek       | A7N8X-E                     | Desktop     | [d0847fb118](https://linux-hardware.org/?probe=d0847fb118) | Mar 06, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [f4e7268671](https://linux-hardware.org/?probe=f4e7268671) | Mar 05, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [96738d19ab](https://linux-hardware.org/?probe=96738d19ab) | Mar 05, 2023 |
| ASUSTek       | T200TA                      | Notebook    | [4d2a27cffa](https://linux-hardware.org/?probe=4d2a27cffa) | Mar 05, 2023 |
| MSI           | GS65 Stealth 9SD            | Notebook    | [1eef9edf97](https://linux-hardware.org/?probe=1eef9edf97) | Mar 04, 2023 |
| Dell          | Latitude E6230              | Notebook    | [1909328685](https://linux-hardware.org/?probe=1909328685) | Mar 04, 2023 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [b492e1c092](https://linux-hardware.org/?probe=b492e1c092) | Mar 04, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [86b939ac1a](https://linux-hardware.org/?probe=86b939ac1a) | Mar 03, 2023 |
| DEXP          | Aquilon C15                 | Notebook    | [9ae006e12a](https://linux-hardware.org/?probe=9ae006e12a) | Mar 03, 2023 |
| ASRock        | Z87 Extreme4                | Desktop     | [d085a259d5](https://linux-hardware.org/?probe=d085a259d5) | Mar 03, 2023 |
| Intel         | W7650                       | Notebook    | [30bde4c2d8](https://linux-hardware.org/?probe=30bde4c2d8) | Mar 03, 2023 |
| Intel         | X79 V2.72A                  | Desktop     | [ae4efdfbc5](https://linux-hardware.org/?probe=ae4efdfbc5) | Mar 02, 2023 |
| Google        | Celes                       | Notebook    | [1952ca99b7](https://linux-hardware.org/?probe=1952ca99b7) | Mar 01, 2023 |
| Google        | Celes                       | Notebook    | [097300a7d3](https://linux-hardware.org/?probe=097300a7d3) | Mar 01, 2023 |
| Lenovo        | ThinkPad X201 3626AL3       | Notebook    | [6741a47327](https://linux-hardware.org/?probe=6741a47327) | Mar 01, 2023 |
| Acer          | Aspire Z5101                | All in one  | [ec55f791bb](https://linux-hardware.org/?probe=ec55f791bb) | Feb 28, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [264f8cb6db](https://linux-hardware.org/?probe=264f8cb6db) | Feb 27, 2023 |
| Getac         | V200-X                      | Notebook    | [f3a5da3eae](https://linux-hardware.org/?probe=f3a5da3eae) | Feb 27, 2023 |
| Acer          | Aspire Z5101                | All in one  | [3dd821cc61](https://linux-hardware.org/?probe=3dd821cc61) | Feb 27, 2023 |
| HP            | Pavilion 17                 | Notebook    | [dfd1ca1091](https://linux-hardware.org/?probe=dfd1ca1091) | Feb 27, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [26548764cd](https://linux-hardware.org/?probe=26548764cd) | Feb 26, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [be9468c864](https://linux-hardware.org/?probe=be9468c864) | Feb 26, 2023 |
| Lenovo        | ThinkPad X201 3626AL3       | Notebook    | [9c3a1f5cd5](https://linux-hardware.org/?probe=9c3a1f5cd5) | Feb 26, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [0f487c3a2a](https://linux-hardware.org/?probe=0f487c3a2a) | Feb 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [1dfaaf5a59](https://linux-hardware.org/?probe=1dfaaf5a59) | Feb 25, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [4c68f5ea84](https://linux-hardware.org/?probe=4c68f5ea84) | Feb 25, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [21335c1268](https://linux-hardware.org/?probe=21335c1268) | Feb 23, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [4b440b2084](https://linux-hardware.org/?probe=4b440b2084) | Feb 22, 2023 |
| Positivo      | Q232A                       | Notebook    | [71c020b7e4](https://linux-hardware.org/?probe=71c020b7e4) | Feb 22, 2023 |
| Pegatron      | 2A73h                       | Desktop     | [835743de83](https://linux-hardware.org/?probe=835743de83) | Feb 21, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [e61bce94ea](https://linux-hardware.org/?probe=e61bce94ea) | Feb 20, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [11739ccfa1](https://linux-hardware.org/?probe=11739ccfa1) | Feb 20, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [6f9ef751cd](https://linux-hardware.org/?probe=6f9ef751cd) | Feb 20, 2023 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [1c2d1949fd](https://linux-hardware.org/?probe=1c2d1949fd) | Feb 19, 2023 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [edfa765236](https://linux-hardware.org/?probe=edfa765236) | Feb 19, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [d65b4290e6](https://linux-hardware.org/?probe=d65b4290e6) | Feb 19, 2023 |
| Medion        | Akoya E6412T                | Notebook    | [41a31b6bd1](https://linux-hardware.org/?probe=41a31b6bd1) | Feb 18, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [cbf0e3814c](https://linux-hardware.org/?probe=cbf0e3814c) | Feb 18, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [2420c1fb57](https://linux-hardware.org/?probe=2420c1fb57) | Feb 18, 2023 |
| HP            | Notebook                    | Notebook    | [9fbe66f89a](https://linux-hardware.org/?probe=9fbe66f89a) | Feb 18, 2023 |
| Lenovo        | ThinkPad X240 20AMS0RR00    | Notebook    | [d159971f77](https://linux-hardware.org/?probe=d159971f77) | Feb 18, 2023 |
| Getac         | V200-X                      | Notebook    | [754a4bd022](https://linux-hardware.org/?probe=754a4bd022) | Feb 17, 2023 |
| Getac         | V200-X                      | Notebook    | [6794c7246f](https://linux-hardware.org/?probe=6794c7246f) | Feb 17, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [39dfda526c](https://linux-hardware.org/?probe=39dfda526c) | Feb 17, 2023 |
| MSI           | MS-7267                     | Desktop     | [0b89f039c1](https://linux-hardware.org/?probe=0b89f039c1) | Feb 17, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [72b29b5f80](https://linux-hardware.org/?probe=72b29b5f80) | Feb 16, 2023 |
| Lenovo        | IdeaPadFlex 3 11ADA05 82... | Convertible | [1fbc4cea88](https://linux-hardware.org/?probe=1fbc4cea88) | Feb 16, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [fbe0863656](https://linux-hardware.org/?probe=fbe0863656) | Feb 15, 2023 |
| Toshiba       | Satellite L650              | Notebook    | [553bddf256](https://linux-hardware.org/?probe=553bddf256) | Feb 15, 2023 |
| ECS           | G41T-M7                     | Desktop     | [3308b85e2f](https://linux-hardware.org/?probe=3308b85e2f) | Feb 15, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | Notebook    | [8f2bad1d66](https://linux-hardware.org/?probe=8f2bad1d66) | Feb 13, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [360789275e](https://linux-hardware.org/?probe=360789275e) | Feb 13, 2023 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [c7374801ac](https://linux-hardware.org/?probe=c7374801ac) | Feb 13, 2023 |
| MSI           | 970A-G46                    | Desktop     | [6012e644eb](https://linux-hardware.org/?probe=6012e644eb) | Feb 13, 2023 |
| Acer          | Extensa 2540                | Notebook    | [6e7e38afb4](https://linux-hardware.org/?probe=6e7e38afb4) | Feb 12, 2023 |
| HP            | 89D8 SMVB                   | Desktop     | [49d1ea8b3e](https://linux-hardware.org/?probe=49d1ea8b3e) | Feb 11, 2023 |
| Dell          | 0FPP7F A00                  | Desktop     | [0a67b25026](https://linux-hardware.org/?probe=0a67b25026) | Feb 11, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [dcecd700f9](https://linux-hardware.org/?probe=dcecd700f9) | Feb 10, 2023 |
| Insyde        | CherryTrail                 | Notebook    | [db3d49fa06](https://linux-hardware.org/?probe=db3d49fa06) | Feb 08, 2023 |
| Gigabyte      | H61MA-D2V                   | Desktop     | [380eb0d0e1](https://linux-hardware.org/?probe=380eb0d0e1) | Feb 08, 2023 |
| Intel         | NUC5PPYB H76558-109         | Mini pc     | [a3384bd952](https://linux-hardware.org/?probe=a3384bd952) | Feb 06, 2023 |
| Toshiba       | Satellite C55D-A            | Notebook    | [38083cc2a4](https://linux-hardware.org/?probe=38083cc2a4) | Feb 05, 2023 |
| Acer          | TravelMate P253             | Notebook    | [b2cad8970a](https://linux-hardware.org/?probe=b2cad8970a) | Feb 04, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [55e2abbd96](https://linux-hardware.org/?probe=55e2abbd96) | Feb 04, 2023 |
| Acer          | AO756                       | Notebook    | [630b2b9b5b](https://linux-hardware.org/?probe=630b2b9b5b) | Feb 03, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [4f6655087b](https://linux-hardware.org/?probe=4f6655087b) | Feb 03, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [88be1adb45](https://linux-hardware.org/?probe=88be1adb45) | Feb 02, 2023 |
| Intel         | powered classmate PC        | Notebook    | [a3e602934b](https://linux-hardware.org/?probe=a3e602934b) | Jan 29, 2023 |
| Intel         | Unknown                     | Notebook    | [f387a4b732](https://linux-hardware.org/?probe=f387a4b732) | Jan 29, 2023 |
| Intel         | Unknown                     | Notebook    | [79aa357327](https://linux-hardware.org/?probe=79aa357327) | Jan 29, 2023 |
| Lenovo        | ThinkPad X220 4291H82       | Notebook    | [f9781882f8](https://linux-hardware.org/?probe=f9781882f8) | Jan 28, 2023 |
| OEM           | M882CWP                     | Tablet      | [d98f389956](https://linux-hardware.org/?probe=d98f389956) | Jan 28, 2023 |
| OEM           | M882CWP                     | Tablet      | [152e24910a](https://linux-hardware.org/?probe=152e24910a) | Jan 28, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [850fc5b742](https://linux-hardware.org/?probe=850fc5b742) | Jan 25, 2023 |
| MSI           | MS-7032                     | Desktop     | [7b481f4c8c](https://linux-hardware.org/?probe=7b481f4c8c) | Jan 25, 2023 |
| Dell          | Latitude E6410              | Notebook    | [03463d0a58](https://linux-hardware.org/?probe=03463d0a58) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [f0d73c960e](https://linux-hardware.org/?probe=f0d73c960e) | Jan 25, 2023 |
| AXDIA Inte... | WINPAD V10                  | Notebook    | [be66e9073f](https://linux-hardware.org/?probe=be66e9073f) | Jan 25, 2023 |
| AXDIA Inte... | WINPAD V10                  | Notebook    | [3a8aced1b7](https://linux-hardware.org/?probe=3a8aced1b7) | Jan 25, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [1099a3c6c9](https://linux-hardware.org/?probe=1099a3c6c9) | Jan 24, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [4944e0cddd](https://linux-hardware.org/?probe=4944e0cddd) | Jan 24, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [d529b5d578](https://linux-hardware.org/?probe=d529b5d578) | Jan 24, 2023 |
| Alienware     | 15 R3                       | Notebook    | [f70ed3a363](https://linux-hardware.org/?probe=f70ed3a363) | Jan 23, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [4eb3c2afb3](https://linux-hardware.org/?probe=4eb3c2afb3) | Jan 23, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [118cda5e06](https://linux-hardware.org/?probe=118cda5e06) | Jan 23, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [27ea4205e5](https://linux-hardware.org/?probe=27ea4205e5) | Jan 22, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [f1e995c40b](https://linux-hardware.org/?probe=f1e995c40b) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [16708a6471](https://linux-hardware.org/?probe=16708a6471) | Jan 20, 2023 |
| HP            | Compaq 6510b (GM108UC#AB... | Notebook    | [45ae9ca3c9](https://linux-hardware.org/?probe=45ae9ca3c9) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [194f5676bd](https://linux-hardware.org/?probe=194f5676bd) | Jan 20, 2023 |
| ASUSTek       | 1011PX                      | Notebook    | [4c7cc6f614](https://linux-hardware.org/?probe=4c7cc6f614) | Jan 19, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [8c57e1afda](https://linux-hardware.org/?probe=8c57e1afda) | Jan 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [c0055f8de2](https://linux-hardware.org/?probe=c0055f8de2) | Jan 18, 2023 |
| Acer          | Swift SF314-54G             | Notebook    | [c666c8f973](https://linux-hardware.org/?probe=c666c8f973) | Jan 18, 2023 |
| Fujitsu Si... | MS-7504VP-PV                | Desktop     | [11964c6701](https://linux-hardware.org/?probe=11964c6701) | Jan 16, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [f33868aba0](https://linux-hardware.org/?probe=f33868aba0) | Jan 15, 2023 |
| NEC Comput... | ECS-945G                    | Desktop     | [8226ffab22](https://linux-hardware.org/?probe=8226ffab22) | Jan 14, 2023 |
| MSI           | K9A2VM                      | Desktop     | [98ce1d06ad](https://linux-hardware.org/?probe=98ce1d06ad) | Jan 14, 2023 |
| Acer          | Aspire ES1-711              | Notebook    | [87c00cc849](https://linux-hardware.org/?probe=87c00cc849) | Jan 12, 2023 |
| ASRock        | ION3D-HT                    | Desktop     | [48707e3794](https://linux-hardware.org/?probe=48707e3794) | Jan 12, 2023 |
| Fujitsu Si... | AMILO Si 2636               | Notebook    | [4a918c5503](https://linux-hardware.org/?probe=4a918c5503) | Jan 11, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [2549187c34](https://linux-hardware.org/?probe=2549187c34) | Jan 10, 2023 |
| Thomson       | N14C4WH64                   | Notebook    | [e9050d81df](https://linux-hardware.org/?probe=e9050d81df) | Jan 09, 2023 |
| Acer          | Aspire One 721              | Notebook    | [4b9311cfed](https://linux-hardware.org/?probe=4b9311cfed) | Jan 08, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [da62202546](https://linux-hardware.org/?probe=da62202546) | Jan 08, 2023 |
| ASUSTek       | W5Fe                        | Notebook    | [d56398aefd](https://linux-hardware.org/?probe=d56398aefd) | Jan 07, 2023 |
| ASRock        | H110M-HDV                   | Desktop     | [deff7fc898](https://linux-hardware.org/?probe=deff7fc898) | Jan 07, 2023 |
| Google        | Candy                       | Notebook    | [1b955d9847](https://linux-hardware.org/?probe=1b955d9847) | Jan 07, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [e8147a271c](https://linux-hardware.org/?probe=e8147a271c) | Jan 06, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [6ef8fba020](https://linux-hardware.org/?probe=6ef8fba020) | Jan 06, 2023 |
| ASUSTek       | F50SV                       | Notebook    | [ae6f64f5df](https://linux-hardware.org/?probe=ae6f64f5df) | Jan 05, 2023 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [7921dc0197](https://linux-hardware.org/?probe=7921dc0197) | Jan 05, 2023 |
| ASUSTek       | F8SG                        | Notebook    | [d70636ce7e](https://linux-hardware.org/?probe=d70636ce7e) | Jan 05, 2023 |
| Dell          | Dimension 4500S             | Desktop     | [5b907b07e4](https://linux-hardware.org/?probe=5b907b07e4) | Jan 05, 2023 |
| Google        | Celes                       | Notebook    | [4036321fcf](https://linux-hardware.org/?probe=4036321fcf) | Jan 05, 2023 |
| Google        | Celes                       | Notebook    | [70525bfcb2](https://linux-hardware.org/?probe=70525bfcb2) | Jan 05, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [bd9e90dca3](https://linux-hardware.org/?probe=bd9e90dca3) | Jan 04, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [73a67d66af](https://linux-hardware.org/?probe=73a67d66af) | Jan 02, 2023 |
| Positivo      | POS-AG31AP                  | Desktop     | [a0ef7524c6](https://linux-hardware.org/?probe=a0ef7524c6) | Jan 02, 2023 |
| Positivo      | POS-AG31AP                  | Desktop     | [4cc8fbf002](https://linux-hardware.org/?probe=4cc8fbf002) | Jan 02, 2023 |
| Acer          | Aspire SW3-013              | Notebook    | [44016de6db](https://linux-hardware.org/?probe=44016de6db) | Jan 01, 2023 |
| HP            | 21B4 A01                    | Desktop     | [cdc9730e81](https://linux-hardware.org/?probe=cdc9730e81) | Dec 31, 2022 |
| Google        | Candy                       | Notebook    | [86bb9a73fc](https://linux-hardware.org/?probe=86bb9a73fc) | Dec 31, 2022 |
| Acer          | TravelMate B117-M           | Notebook    | [23985812a9](https://linux-hardware.org/?probe=23985812a9) | Dec 30, 2022 |
| Dell          | 05KX61 A00                  | Server      | [9f365307f3](https://linux-hardware.org/?probe=9f365307f3) | Dec 30, 2022 |
| ASUSTek       | K72F                        | Notebook    | [f761bf9bd6](https://linux-hardware.org/?probe=f761bf9bd6) | Dec 30, 2022 |
| Google        | Edgar                       | Notebook    | [738a0d9324](https://linux-hardware.org/?probe=738a0d9324) | Dec 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [41a9d09ec8](https://linux-hardware.org/?probe=41a9d09ec8) | Dec 29, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [a9c1fc9fbd](https://linux-hardware.org/?probe=a9c1fc9fbd) | Dec 28, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [fd1cdfc132](https://linux-hardware.org/?probe=fd1cdfc132) | Dec 28, 2022 |
| Acer          | Aspire SW3-013              | Notebook    | [04286c0e93](https://linux-hardware.org/?probe=04286c0e93) | Dec 27, 2022 |
| Digma         | CITI E401 ET4007EW          | Notebook    | [252a51f201](https://linux-hardware.org/?probe=252a51f201) | Dec 26, 2022 |
| Acer          | Swift SF314-54G             | Notebook    | [34532e7f7d](https://linux-hardware.org/?probe=34532e7f7d) | Dec 26, 2022 |
| HP            | InsydeH2O EFI BIOS          | Notebook    | [96a4f739b8](https://linux-hardware.org/?probe=96a4f739b8) | Dec 26, 2022 |
| HP            | InsydeH2O EFI BIOS          | Notebook    | [19af161114](https://linux-hardware.org/?probe=19af161114) | Dec 26, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [cd547b04a1](https://linux-hardware.org/?probe=cd547b04a1) | Dec 25, 2022 |
| ASRock        | 970DE3/U3S3                 | Desktop     | [1505706e04](https://linux-hardware.org/?probe=1505706e04) | Dec 25, 2022 |
| ASRock        | 970DE3/U3S3                 | Desktop     | [1c996d8122](https://linux-hardware.org/?probe=1c996d8122) | Dec 25, 2022 |
| HP            | Stream Notebook PC 11       | Notebook    | [f33ebabb99](https://linux-hardware.org/?probe=f33ebabb99) | Dec 24, 2022 |
| HP            | Stream 8 Tablet             | Tablet      | [752a0b9007](https://linux-hardware.org/?probe=752a0b9007) | Dec 23, 2022 |
| Positivo      | C14CR21                     | Notebook    | [be49c26bb4](https://linux-hardware.org/?probe=be49c26bb4) | Dec 21, 2022 |
| HP            | Compaq 6715b (RM174UT#AB... | Notebook    | [db3b8615f7](https://linux-hardware.org/?probe=db3b8615f7) | Dec 21, 2022 |
| ZOTAC         | NM10                        | Desktop     | [98b6981431](https://linux-hardware.org/?probe=98b6981431) | Dec 21, 2022 |
| Dell          | Latitude E7470              | Notebook    | [e171eea812](https://linux-hardware.org/?probe=e171eea812) | Dec 21, 2022 |
| Google        | Coral                       | Notebook    | [8e2407d4b2](https://linux-hardware.org/?probe=8e2407d4b2) | Dec 19, 2022 |
| Lenovo        | ThinkPad R61 77324TG        | Notebook    | [90c300a51c](https://linux-hardware.org/?probe=90c300a51c) | Dec 18, 2022 |
| HP            | 2000                        | Notebook    | [bcbeb17a60](https://linux-hardware.org/?probe=bcbeb17a60) | Dec 15, 2022 |
| HP            | Compaq 6830s                | Notebook    | [1883df2312](https://linux-hardware.org/?probe=1883df2312) | Dec 14, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [5c437c961e](https://linux-hardware.org/?probe=5c437c961e) | Dec 13, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [9ddb08e4ae](https://linux-hardware.org/?probe=9ddb08e4ae) | Dec 13, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [becb2e6bbc](https://linux-hardware.org/?probe=becb2e6bbc) | Dec 12, 2022 |
| SGIN          | laptop                      | Notebook    | [8f650d00dd](https://linux-hardware.org/?probe=8f650d00dd) | Dec 11, 2022 |
| ASUSTek       | K50C                        | Notebook    | [6cf2037e0f](https://linux-hardware.org/?probe=6cf2037e0f) | Dec 11, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [492071e526](https://linux-hardware.org/?probe=492071e526) | Dec 09, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [71137ab051](https://linux-hardware.org/?probe=71137ab051) | Dec 08, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [bcf1460e47](https://linux-hardware.org/?probe=bcf1460e47) | Dec 08, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [651f6f4d18](https://linux-hardware.org/?probe=651f6f4d18) | Dec 07, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [bdbc74a754](https://linux-hardware.org/?probe=bdbc74a754) | Dec 07, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [659b20c9b8](https://linux-hardware.org/?probe=659b20c9b8) | Dec 06, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [193053a6ef](https://linux-hardware.org/?probe=193053a6ef) | Dec 05, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [de8272cf2e](https://linux-hardware.org/?probe=de8272cf2e) | Dec 05, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [88e60fc0ba](https://linux-hardware.org/?probe=88e60fc0ba) | Dec 04, 2022 |
| ASUSTek       | PRIME A320M-F               | Desktop     | [abe82b0f58](https://linux-hardware.org/?probe=abe82b0f58) | Dec 04, 2022 |
| ASUSTek       | ET1610PT                    | Desktop     | [d8b1840336](https://linux-hardware.org/?probe=d8b1840336) | Dec 03, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [179ce76921](https://linux-hardware.org/?probe=179ce76921) | Dec 02, 2022 |
| Positivo      | i500pro                     | Notebook    | [4a79aa2383](https://linux-hardware.org/?probe=4a79aa2383) | Nov 30, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [f91b4cdb61](https://linux-hardware.org/?probe=f91b4cdb61) | Nov 29, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Lubuntu/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Lubuntu 22.04    | 518       | 28.52%  |
| Lubuntu 20.04    | 473       | 26.05%  |
| Lubuntu 18.04    | 225       | 12.39%  |
| Lubuntu 24.04    | 127       | 6.99%   |
| Lubuntu 21.10    | 81        | 4.46%   |
| Lubuntu 19.10    | 62        | 3.41%   |
| Lubuntu 23.10    | 54        | 2.97%   |
| Lubuntu 21.04    | 53        | 2.92%   |
| Lubuntu 20.10    | 48        | 2.64%   |
| Lubuntu 22.10    | 46        | 2.53%   |
| Lubuntu 23.04    | 38        | 2.09%   |
| Lubuntu 16.04    | 35        | 1.93%   |
| Lubuntu 24.10    | 18        | 0.99%   |
| Lubuntu 19.04    | 14        | 0.77%   |
| Lubuntu 18.10    | 13        | 0.72%   |
| Lubuntu          | 3         | 0.17%   |
| Lubuntu 16.10    | 2         | 0.11%   |
| Lubuntu 20.04.1  | 1         | 0.06%   |
| Lubuntu 18.04.05 | 1         | 0.06%   |
| Lubuntu 17.10    | 1         | 0.06%   |
| Lubuntu 17.04    | 1         | 0.06%   |
| Lubuntu 13.04    | 1         | 0.06%   |
| Lubuntu 12.04    | 1         | 0.06%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Lubuntu | 1753      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 39        | 1.97%   |
| 5.15.0-43-generic | 36        | 1.82%   |
| 6.8.0-31-generic  | 24        | 1.21%   |
| 5.4.0-52-generic  | 24        | 1.21%   |
| 6.8.0-41-generic  | 23        | 1.16%   |
| 5.15.0-56-generic | 21        | 1.06%   |
| 6.5.0-14-generic  | 19        | 0.96%   |
| 5.13.0-19-generic | 19        | 0.96%   |
| 5.15.0-25-generic | 17        | 0.86%   |
| 5.19.0-32-generic | 16        | 0.81%   |
| 5.15.0-60-generic | 16        | 0.81%   |
| 5.15.0-46-generic | 16        | 0.81%   |
| 5.13.0-40-generic | 16        | 0.81%   |
| 5.13.0-28-generic | 16        | 0.81%   |
| 6.8.0-40-generic  | 15        | 0.76%   |
| 6.2.0-26-generic  | 14        | 0.71%   |
| 5.4.0-48-generic  | 14        | 0.71%   |
| 5.4.0-47-generic  | 14        | 0.71%   |
| 5.3.0-46-generic  | 14        | 0.71%   |
| 5.15.0-41-generic | 14        | 0.71%   |
| 5.11.0-27-generic | 14        | 0.71%   |
| 6.8.0-45-generic  | 13        | 0.66%   |
| 6.5.0-9-generic   | 13        | 0.66%   |
| 6.5.0-18-generic  | 13        | 0.66%   |
| 5.15.0-47-generic | 13        | 0.66%   |
| 5.13.0-30-generic | 13        | 0.66%   |
| 5.11.0-16-generic | 13        | 0.66%   |
| 6.8.0-48-generic  | 12        | 0.61%   |
| 6.2.0-39-generic  | 12        | 0.61%   |
| 5.4.0-54-generic  | 12        | 0.61%   |
| 5.4.0-26-generic  | 12        | 0.61%   |
| 5.19.0-41-generic | 12        | 0.61%   |
| 5.19.0-35-generic | 12        | 0.61%   |
| 5.15.0-58-generic | 12        | 0.61%   |
| 6.8.0-47-generic  | 11        | 0.56%   |
| 6.5.0-41-generic  | 11        | 0.56%   |
| 6.5.0-28-generic  | 11        | 0.56%   |
| 6.5.0-15-generic  | 11        | 0.56%   |
| 6.2.0-34-generic  | 11        | 0.56%   |
| 5.8.0-50-generic  | 11        | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 340       | 18.42%  |
| 5.15.0  | 321       | 17.39%  |
| 4.15.0  | 150       | 8.13%   |
| 6.8.0   | 145       | 7.85%   |
| 6.5.0   | 143       | 7.75%   |
| 5.13.0  | 120       | 6.5%    |
| 5.19.0  | 116       | 6.28%   |
| 5.11.0  | 103       | 5.58%   |
| 5.8.0   | 99        | 5.36%   |
| 6.2.0   | 96        | 5.2%    |
| 5.3.0   | 86        | 4.66%   |
| 5.0.0   | 22        | 1.19%   |
| 6.11.0  | 16        | 0.87%   |
| 4.18.0  | 13        | 0.7%    |
| 4.4.0   | 11        | 0.6%    |
| 6.1.0   | 3         | 0.16%   |
| 6.6.0   | 2         | 0.11%   |
| 5.6.0   | 2         | 0.11%   |
| 5.4.30  | 2         | 0.11%   |
| 5.14.0  | 2         | 0.11%   |
| 4.9.253 | 2         | 0.11%   |
| 4.8.0   | 2         | 0.11%   |
| 4.13.0  | 2         | 0.11%   |
| 4.10.0  | 2         | 0.11%   |
| 6.9.5   | 1         | 0.05%   |
| 6.7.8   | 1         | 0.05%   |
| 6.7.6   | 1         | 0.05%   |
| 6.7.0   | 1         | 0.05%   |
| 6.6.6   | 1         | 0.05%   |
| 6.5.1   | 1         | 0.05%   |
| 6.4.12  | 1         | 0.05%   |
| 6.3.3   | 1         | 0.05%   |
| 6.2.8   | 1         | 0.05%   |
| 6.2.6   | 1         | 0.05%   |
| 6.12.3  | 1         | 0.05%   |
| 6.10.6  | 1         | 0.05%   |
| 6.10.0  | 1         | 0.05%   |
| 6.1.6   | 1         | 0.05%   |
| 6.1.46  | 1         | 0.05%   |
| 6.1.3   | 1         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 342       | 18.53%  |
| 5.15    | 322       | 17.44%  |
| 4.15    | 151       | 8.18%   |
| 6.8     | 145       | 7.85%   |
| 6.5     | 144       | 7.8%    |
| 5.13    | 120       | 6.5%    |
| 5.19    | 118       | 6.39%   |
| 5.11    | 103       | 5.58%   |
| 5.8     | 99        | 5.36%   |
| 6.2     | 98        | 5.31%   |
| 5.3     | 87        | 4.71%   |
| 5.0     | 22        | 1.19%   |
| 6.11    | 16        | 0.87%   |
| 4.18    | 13        | 0.7%    |
| 4.4     | 11        | 0.6%    |
| 6.1     | 8         | 0.43%   |
| 6.0     | 6         | 0.33%   |
| 6.7     | 3         | 0.16%   |
| 6.6     | 3         | 0.16%   |
| 5.6     | 3         | 0.16%   |
| 4.9     | 3         | 0.16%   |
| 4.13    | 3         | 0.16%   |
| 6.10    | 2         | 0.11%   |
| 5.7     | 2         | 0.11%   |
| 5.16    | 2         | 0.11%   |
| 5.14    | 2         | 0.11%   |
| 5.10    | 2         | 0.11%   |
| 4.8     | 2         | 0.11%   |
| 4.10    | 2         | 0.11%   |
| 6.9     | 1         | 0.05%   |
| 6.4     | 1         | 0.05%   |
| 6.3     | 1         | 0.05%   |
| 6.12    | 1         | 0.05%   |
| 5.9     | 1         | 0.05%   |
| 5.5     | 1         | 0.05%   |
| 5.18    | 1         | 0.05%   |
| 5.12    | 1         | 0.05%   |
| 4.20    | 1         | 0.05%   |
| 4.14    | 1         | 0.05%   |
| 3.13    | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1603      | 91.44%  |
| i686    | 136       | 7.76%   |
| aarch64 | 11        | 0.63%   |
| armv7l  | 2         | 0.11%   |
| ppc64   | 1         | 0.06%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| LXQt            | 1419      | 80.58%  |
| LXDE            | 262       | 14.88%  |
| Unknown         | 22        | 1.25%   |
| GNOME           | 21        | 1.19%   |
| Openbox         | 7         | 0.4%    |
| X-Cinnamon      | 5         | 0.28%   |
| Lubuntu         | 4         | 0.23%   |
| KDE5            | 4         | 0.23%   |
| XFCE            | 3         | 0.17%   |
| i3              | 3         | 0.17%   |
| Cinnamon        | 3         | 0.17%   |
| GNOME Flashback | 2         | 0.11%   |
| Budgie          | 2         | 0.11%   |
| ratflow         | 1         | 0.06%   |
| MATE            | 1         | 0.06%   |
| KDE             | 1         | 0.06%   |
| i3-with-shmlog  | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 1692      | 96.03%  |
| Tty         | 54        | 3.06%   |
| Wayland     | 13        | 0.74%   |
| Unknown     | 2         | 0.11%   |
| Unspecified | 1         | 0.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 1031      | 57.95%  |
| Unknown | 439       | 24.68%  |
| LightDM | 165       | 9.27%   |
| TDM     | 68        | 3.82%   |
| GDM     | 38        | 2.14%   |
| GDM3    | 27        | 1.52%   |
| XDM     | 5         | 0.28%   |
| LXDM    | 3         | 0.17%   |
| SLiM    | 2         | 0.11%   |
| NODM    | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 520       | 29.46%  |
| fr_FR   | 169       | 9.58%   |
| pt_BR   | 113       | 6.4%    |
| de_DE   | 111       | 6.29%   |
| it_IT   | 105       | 5.95%   |
| en_GB   | 98        | 5.55%   |
| C       | 98        | 5.55%   |
| ru_RU   | 55        | 3.12%   |
| pl_PL   | 42        | 2.38%   |
| es_ES   | 39        | 2.21%   |
| en_CA   | 38        | 2.15%   |
| Unknown | 31        | 1.76%   |
| en_AU   | 29        | 1.64%   |
| es_AR   | 27        | 1.53%   |
| es_MX   | 24        | 1.36%   |
| tr_TR   | 17        | 0.96%   |
| cs_CZ   | 16        | 0.91%   |
| hu_HU   | 14        | 0.79%   |
| en_IN   | 13        | 0.74%   |
| nl_NL   | 12        | 0.68%   |
| ja_JP   | 11        | 0.62%   |
| fi_FI   | 11        | 0.62%   |
| en_AG   | 11        | 0.62%   |
| es_CR   | 10        | 0.57%   |
| es_CL   | 9         | 0.51%   |
| el_GR   | 8         | 0.45%   |
| es_CO   | 7         | 0.4%    |
| zh_TW   | 6         | 0.34%   |
| nl_BE   | 6         | 0.34%   |
| fr_CA   | 5         | 0.28%   |
| fr_BE   | 5         | 0.28%   |
| es_PE   | 5         | 0.28%   |
| en_ZA   | 5         | 0.28%   |
| en_SG   | 5         | 0.28%   |
| en_PH   | 5         | 0.28%   |
| en_IE   | 5         | 0.28%   |
| sv_SE   | 4         | 0.23%   |
| sk_SK   | 4         | 0.23%   |
| pt_PT   | 4         | 0.23%   |
| fr_CH   | 4         | 0.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 1119      | 63.18%  |
| EFI  | 652       | 36.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1470      | 82.82%  |
| Tmpfs   | 171       | 9.63%   |
| Overlay | 88        | 4.96%   |
| Btrfs   | 20        | 1.13%   |
| Xfs     | 7         | 0.39%   |
| Aufs    | 5         | 0.28%   |
| Unknown | 5         | 0.28%   |
| Ext3    | 3         | 0.17%   |
| Ext2    | 2         | 0.11%   |
| Zfs     | 1         | 0.06%   |
| XXX4    | 1         | 0.06%   |
| Nfs     | 1         | 0.06%   |
| F2fs    | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 726       | 40.92%  |
| Unknown | 574       | 32.36%  |
| MBR     | 474       | 26.72%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1563      | 88.06%  |
| Yes       | 212       | 11.94%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1284      | 72.62%  |
| Yes       | 484       | 27.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 288       | 16.43%  |
| ASUSTek Computer        | 212       | 12.09%  |
| Lenovo                  | 185       | 10.55%  |
| Dell                    | 183       | 10.44%  |
| Acer                    | 125       | 7.13%   |
| MSI                     | 64        | 3.65%   |
| Gigabyte Technology     | 59        | 3.37%   |
| Toshiba                 | 53        | 3.02%   |
| ASRock                  | 47        | 2.68%   |
| Apple                   | 41        | 2.34%   |
| Intel                   | 36        | 2.05%   |
| Samsung Electronics     | 35        | 2%      |
| Unknown                 | 35        | 2%      |
| Google                  | 34        | 1.94%   |
| Sony                    | 26        | 1.48%   |
| Fujitsu                 | 22        | 1.25%   |
| Positivo                | 21        | 1.2%    |
| Fujitsu Siemens         | 16        | 0.91%   |
| Packard Bell            | 15        | 0.86%   |
| AMI                     | 14        | 0.8%    |
| Pegatron                | 13        | 0.74%   |
| Foxconn                 | 11        | 0.63%   |
| Mediacom                | 9         | 0.51%   |
| Supermicro              | 7         | 0.4%    |
| Raspberry Pi Foundation | 7         | 0.4%    |
| Notebook                | 7         | 0.4%    |
| Chuwi                   | 7         | 0.4%    |
| Microsoft               | 6         | 0.34%   |
| Medion                  | 6         | 0.34%   |
| Gateway                 | 6         | 0.34%   |
| eMachines               | 6         | 0.34%   |
| Biostar                 | 6         | 0.34%   |
| AAEON                   | 6         | 0.34%   |
| IBM                     | 5         | 0.29%   |
| HUAWEI                  | 5         | 0.29%   |
| LG Electronics          | 4         | 0.23%   |
| Itautec                 | 4         | 0.23%   |
| AZW                     | 4         | 0.23%   |
| Alienware               | 4         | 0.23%   |
| ZOTAC                   | 3         | 0.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 46        | 2.62%   |
| HP Notebook                           | 16        | 0.91%   |
| HP Pavilion 15                        | 7         | 0.4%    |
| Apple MacBookPro8,1                   | 7         | 0.4%    |
| HP Pavilion dv6                       | 6         | 0.34%   |
| AAEON MF-001                          | 6         | 0.34%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS   | 5         | 0.29%   |
| HP Pavilion g6                        | 5         | 0.29%   |
| Dell OptiPlex 790                     | 5         | 0.29%   |
| Dell OptiPlex 7010                    | 5         | 0.29%   |
| Dell Latitude E6410                   | 5         | 0.29%   |
| Apple iMac7,1                         | 5         | 0.29%   |
| Supermicro X8DTT-IBX                  | 4         | 0.23%   |
| MSI MS-7C37                           | 4         | 0.23%   |
| Mediacom SmartBook 14 FullHD - SB14UC | 4         | 0.23%   |
| HP t620 Quad Core TC                  | 4         | 0.23%   |
| HP Pavilion g7                        | 4         | 0.23%   |
| HP Laptop 15-bw0xx                    | 4         | 0.23%   |
| HP 2000                               | 4         | 0.23%   |
| Google Candy                          | 4         | 0.23%   |
| Dell Latitude D630                    | 4         | 0.23%   |
| Dell Inspiron N5010                   | 4         | 0.23%   |
| ASUS All Series                       | 4         | 0.23%   |
| Acer Aspire 5735                      | 4         | 0.23%   |
| Toshiba Satellite C660                | 3         | 0.17%   |
| Nvidia Tegra                          | 3         | 0.17%   |
| MSI MS-7309                           | 3         | 0.17%   |
| Mediacom WinPad 11,6 FullHD- WPU11    | 3         | 0.17%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK | 3         | 0.17%   |
| Lenovo IdeaPad 320-15AST 80XV         | 3         | 0.17%   |
| Lenovo IdeaPad 100-15IBD 80QQ         | 3         | 0.17%   |
| Lenovo G50-30 80G0                    | 3         | 0.17%   |
| HP ProBook 440 G7                     | 3         | 0.17%   |
| HP Pavilion x2 Detachable             | 3         | 0.17%   |
| HP Compaq Presario CQ60               | 3         | 0.17%   |
| Dell OptiPlex 755                     | 3         | 0.17%   |
| Dell OptiPlex 3010                    | 3         | 0.17%   |
| Dell Latitude E5450                   | 3         | 0.17%   |
| Dell Inspiron 15-3567                 | 3         | 0.17%   |
| Dell Inspiron 13-5378                 | 3         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Acer Aspire             | 89        | 5.08%   |
| Lenovo ThinkPad         | 60        | 3.42%   |
| Lenovo IdeaPad          | 60        | 3.42%   |
| Dell Inspiron           | 55        | 3.14%   |
| HP Pavilion             | 51        | 2.91%   |
| Toshiba Satellite       | 48        | 2.74%   |
| Unknown                 | 46        | 2.62%   |
| HP Compaq               | 45        | 2.57%   |
| Dell Latitude           | 42        | 2.4%    |
| Dell OptiPlex           | 34        | 1.94%   |
| HP ProBook              | 31        | 1.77%   |
| HP EliteBook            | 28        | 1.6%    |
| HP Laptop               | 23        | 1.31%   |
| Lenovo ThinkCentre      | 19        | 1.08%   |
| HP Notebook             | 16        | 0.91%   |
| Dell XPS                | 14        | 0.8%    |
| ASUS VivoBook           | 14        | 0.8%    |
| Dell Vostro             | 11        | 0.63%   |
| Packard Bell EasyNote   | 10        | 0.57%   |
| Fujitsu Siemens AMILO   | 10        | 0.57%   |
| Fujitsu LIFEBOOK        | 9         | 0.51%   |
| ASUS PRIME              | 9         | 0.51%   |
| Dell Precision          | 8         | 0.46%   |
| Acer Extensa            | 8         | 0.46%   |
| RPi Raspberry           | 7         | 0.4%    |
| Apple MacBookPro8       | 7         | 0.4%    |
| Microsoft Surface       | 6         | 0.34%   |
| HP t620                 | 6         | 0.34%   |
| HP Stream               | 6         | 0.34%   |
| HP Presario             | 6         | 0.34%   |
| ASUS ROG                | 6         | 0.34%   |
| Acer Swift              | 6         | 0.34%   |
| AAEON MF-001            | 6         | 0.34%   |
| Lenovo Yoga             | 5         | 0.29%   |
| HP Spectre              | 5         | 0.29%   |
| HP 255                  | 5         | 0.29%   |
| HP 250                  | 5         | 0.29%   |
| Fujitsu Siemens ESPRIMO | 5         | 0.29%   |
| Dell Studio             | 5         | 0.29%   |
| ASUS M5A97              | 5         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 152       | 8.67%   |
| 2012    | 145       | 8.27%   |
| 2010    | 132       | 7.53%   |
| 2008    | 124       | 7.07%   |
| 2013    | 122       | 6.96%   |
| 2007    | 108       | 6.16%   |
| 2009    | 102       | 5.82%   |
| 2019    | 95        | 5.42%   |
| 2017    | 94        | 5.36%   |
| 2014    | 93        | 5.31%   |
| 2016    | 84        | 4.79%   |
| 2015    | 82        | 4.68%   |
| 2021    | 79        | 4.51%   |
| 2020    | 77        | 4.39%   |
| 2018    | 72        | 4.11%   |
| 2006    | 60        | 3.42%   |
| 2022    | 49        | 2.8%    |
| 2023    | 30        | 1.71%   |
| 2005    | 21        | 1.2%    |
| Unknown | 14        | 0.8%    |
| 2004    | 5         | 0.29%   |
| 2024    | 4         | 0.23%   |
| 2003    | 3         | 0.17%   |
| 2002    | 3         | 0.17%   |
| 2001    | 2         | 0.11%   |
| 2000    | 1         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1083      | 61.78%  |
| Desktop        | 552       | 31.49%  |
| Mini pc        | 29        | 1.65%   |
| Convertible    | 23        | 1.31%   |
| All in one     | 23        | 1.31%   |
| Tablet         | 16        | 0.91%   |
| Server         | 14        | 0.8%    |
| System on chip | 12        | 0.68%   |
| Other          | 1         | 0.06%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1653      | 93.92%  |
| Enabled  | 107       | 6.08%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1716      | 97.83%  |
| Yes  | 38        | 2.17%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 536       | 30.1%   |
| 4.01-8.0        | 383       | 21.5%   |
| 1.01-2.0        | 271       | 15.22%  |
| 8.01-16.0       | 189       | 10.61%  |
| 16.01-24.0      | 158       | 8.87%   |
| 2.01-3.0        | 80        | 4.49%   |
| 32.01-64.0      | 64        | 3.59%   |
| 0.51-1.0        | 53        | 2.98%   |
| 24.01-32.0      | 18        | 1.01%   |
| 64.01-256.0     | 18        | 1.01%   |
| 0.01-0.5        | 8         | 0.45%   |
| More than 256.0 | 3         | 0.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 805       | 43%     |
| 0.51-1.0   | 426       | 22.76%  |
| 2.01-3.0   | 319       | 17.04%  |
| 4.01-8.0   | 116       | 6.2%    |
| 3.01-4.0   | 101       | 5.4%    |
| 0.01-0.5   | 77        | 4.11%   |
| 8.01-16.0  | 21        | 1.12%   |
| 16.01-24.0 | 3         | 0.16%   |
| 32.01-64.0 | 2         | 0.11%   |
| Unknown    | 2         | 0.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1219      | 68.75%  |
| 2      | 385       | 21.71%  |
| 3      | 62        | 3.5%    |
| 4      | 35        | 1.97%   |
| 0      | 31        | 1.75%   |
| 5      | 21        | 1.18%   |
| 6      | 7         | 0.39%   |
| 7      | 4         | 0.23%   |
| 8      | 2         | 0.11%   |
| 17     | 1         | 0.06%   |
| 14     | 1         | 0.06%   |
| 13     | 1         | 0.06%   |
| 12     | 1         | 0.06%   |
| 11     | 1         | 0.06%   |
| 10     | 1         | 0.06%   |
| 9      | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 945       | 53.57%  |
| Yes       | 819       | 46.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1504      | 85.55%  |
| No        | 254       | 14.45%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1344      | 76.45%  |
| No        | 414       | 23.55%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 912       | 51.47%  |
| Yes       | 860       | 48.53%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 276       | 15.7%   |
| France       | 176       | 10.01%  |
| Germany      | 147       | 8.36%   |
| Brazil       | 139       | 7.91%   |
| Italy        | 134       | 7.62%   |
| Russia       | 82        | 4.66%   |
| UK           | 70        | 3.98%   |
| Canada       | 53        | 3.01%   |
| Poland       | 48        | 2.73%   |
| Spain        | 42        | 2.39%   |
| Netherlands  | 32        | 1.82%   |
| Argentina    | 32        | 1.82%   |
| Australia    | 29        | 1.65%   |
| Turkey       | 24        | 1.37%   |
| Finland      | 24        | 1.37%   |
| Czechia      | 24        | 1.37%   |
| Indonesia    | 23        | 1.31%   |
| Hungary      | 22        | 1.25%   |
| Mexico       | 21        | 1.19%   |
| Belgium      | 21        | 1.19%   |
| Switzerland  | 19        | 1.08%   |
| India        | 17        | 0.97%   |
| Ukraine      | 12        | 0.68%   |
| Sweden       | 12        | 0.68%   |
| Romania      | 12        | 0.68%   |
| Japan        | 12        | 0.68%   |
| Greece       | 12        | 0.68%   |
| Costa Rica   | 12        | 0.68%   |
| Colombia     | 11        | 0.63%   |
| Chile        | 11        | 0.63%   |
| Malaysia     | 10        | 0.57%   |
| Slovakia     | 9         | 0.51%   |
| Portugal     | 9         | 0.51%   |
| South Africa | 8         | 0.46%   |
| Ireland      | 8         | 0.46%   |
| Bulgaria     | 8         | 0.46%   |
| Taiwan       | 7         | 0.4%    |
| Peru         | 7         | 0.4%    |
| Norway       | 7         | 0.4%    |
| Ecuador      | 7         | 0.4%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Paris             | 25        | 1.36%   |
| Milan             | 18        | 0.98%   |
| Rome              | 17        | 0.92%   |
| Moscow            | 14        | 0.76%   |
| Melbourne         | 13        | 0.71%   |
| Helsinki          | 13        | 0.71%   |
| Sao Paulo         | 11        | 0.6%    |
| Warsaw            | 9         | 0.49%   |
| New York          | 9         | 0.49%   |
| Istanbul          | 9         | 0.49%   |
| St Petersburg     | 8         | 0.43%   |
| Prague            | 8         | 0.43%   |
| Rio de Janeiro    | 7         | 0.38%   |
| Oshawa            | 7         | 0.38%   |
| Lyon              | 7         | 0.38%   |
| Heredia           | 7         | 0.38%   |
| Grecia            | 7         | 0.38%   |
| Budapest          | 7         | 0.38%   |
| Brasília         | 7         | 0.38%   |
| Bengaluru         | 7         | 0.38%   |
| Zurich            | 6         | 0.33%   |
| Munich            | 6         | 0.33%   |
| Mexico City       | 6         | 0.33%   |
| Kyiv              | 6         | 0.33%   |
| Kuala Lumpur      | 6         | 0.33%   |
| Houston           | 6         | 0.33%   |
| Frankfurt am Main | 6         | 0.33%   |
| Curitiba          | 6         | 0.33%   |
| Bogotá           | 6         | 0.33%   |
| Berlin            | 6         | 0.33%   |
| Athens            | 6         | 0.33%   |
| Wellington        | 5         | 0.27%   |
| Toronto           | 5         | 0.27%   |
| Tehran            | 5         | 0.27%   |
| Sydney            | 5         | 0.27%   |
| Stuttgart         | 5         | 0.27%   |
| Santiago          | 5         | 0.27%   |
| Porto Alegre      | 5         | 0.27%   |
| Madrid            | 5         | 0.27%   |
| Kunming           | 5         | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 351       | 477    | 15.85%  |
| Seagate                   | 349       | 469    | 15.76%  |
| Samsung Electronics       | 230       | 335    | 10.39%  |
| Unknown                   | 186       | 251    | 8.4%    |
| Toshiba                   | 141       | 161    | 6.37%   |
| Hitachi                   | 130       | 160    | 5.87%   |
| Kingston                  | 112       | 134    | 5.06%   |
| SanDisk                   | 76        | 87     | 3.43%   |
| Crucial                   | 68        | 87     | 3.07%   |
| HGST                      | 43        | 49     | 1.94%   |
| Intel                     | 33        | 46     | 1.49%   |
| Fujitsu                   | 29        | 31     | 1.31%   |
| SK hynix                  | 25        | 26     | 1.13%   |
| Micron Technology         | 25        | 26     | 1.13%   |
| A-DATA Technology         | 25        | 27     | 1.13%   |
| China                     | 24        | 28     | 1.08%   |
| Unknown                   | 23        | 25     | 1.04%   |
| Maxtor                    | 19        | 21     | 0.86%   |
| Apacer                    | 18        | 18     | 0.81%   |
| Patriot                   | 11        | 11     | 0.5%    |
| Silicon Motion            | 10        | 12     | 0.45%   |
| PNY                       | 10        | 13     | 0.45%   |
| Apple                     | 10        | 17     | 0.45%   |
| Transcend                 | 9         | 11     | 0.41%   |
| KIOXIA                    | 9         | 9      | 0.41%   |
| Intenso                   | 9         | 11     | 0.41%   |
| SPCC                      | 8         | 11     | 0.36%   |
| OCZ                       | 8         | 9      | 0.36%   |
| LITEONIT                  | 8         | 8      | 0.36%   |
| Team                      | 6         | 6      | 0.27%   |
| LITEON                    | 6         | 7      | 0.27%   |
| Lexar                     | 6         | 9      | 0.27%   |
| Hewlett-Packard           | 6         | 15     | 0.27%   |
| GOODRAM                   | 6         | 6      | 0.27%   |
| Phison                    | 5         | 9      | 0.23%   |
| Micron/Crucial Technology | 5         | 7      | 0.23%   |
| LDLC                      | 5         | 7      | 0.23%   |
| KingSpec                  | 5         | 7      | 0.23%   |
| JMicron Technology        | 5         | 5      | 0.23%   |
| Corsair                   | 5         | 5      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 38        | 1.58%   |
| Unknown MMC Card  64GB              | 31        | 1.29%   |
| Kingston SA400S37240G 240GB SSD     | 31        | 1.29%   |
| Unknown                             | 23        | 0.96%   |
| Seagate ST9500325AS 500GB           | 17        | 0.71%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 17        | 0.71%   |
| Toshiba MQ01ABD100 1TB              | 15        | 0.62%   |
| Seagate ST500LT012-1DG142 500GB     | 15        | 0.62%   |
| Seagate ST500DM002-1BD142 500GB     | 15        | 0.62%   |
| Kingston SA400S37480G 480GB SSD     | 14        | 0.58%   |
| Kingston SA400S37120G 120GB SSD     | 14        | 0.58%   |
| Seagate ST1000LM035-1RK172 1TB      | 13        | 0.54%   |
| Unknown MMC Card  16GB              | 12        | 0.5%    |
| Seagate ST500LM012 HN-M500MBB 500GB | 12        | 0.5%    |
| Samsung SSD 850 EVO 250GB           | 12        | 0.5%    |
| Unknown SD/MMC/MS PRO 128GB         | 11        | 0.46%   |
| Toshiba MQ01ABF050 500GB            | 11        | 0.46%   |
| Crucial CT240BX500SSD1 240GB        | 11        | 0.46%   |
| Seagate ST3500418AS 500GB           | 10        | 0.42%   |
| HGST HTS545050A7E680 500GB          | 10        | 0.42%   |
| Unknown NCard  32GB                 | 9         | 0.37%   |
| Unknown DA4064  64GB                | 9         | 0.37%   |
| Seagate ST1000DM010-2EP102 1TB      | 9         | 0.37%   |
| SanDisk DF4032  32GB                | 9         | 0.37%   |
| Kingston SV300S37A120G 120GB SSD    | 9         | 0.37%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 8         | 0.33%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 8         | 0.33%   |
| Toshiba MQ01ABD050 500GB            | 8         | 0.33%   |
| Seagate ST2000DM008-2FR102 2TB      | 8         | 0.33%   |
| Seagate Expansion 1TB               | 8         | 0.33%   |
| HGST HTS545050A7E380 500GB          | 8         | 0.33%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 7         | 0.29%   |
| Unknown MMC Card  128GB             | 7         | 0.29%   |
| Seagate ST9320325AS 320GB           | 7         | 0.29%   |
| Samsung SSD 850 EVO 500GB           | 7         | 0.29%   |
| Crucial CT480BX500SSD1 480GB        | 7         | 0.29%   |
| Crucial CT1000MX500SSD1 1TB         | 7         | 0.29%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 6         | 0.25%   |
| Seagate ST9250315AS 250GB           | 6         | 0.25%   |
| Seagate ST2000DM001-1CH164 2TB      | 6         | 0.25%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 346       | 465    | 31.31%  |
| WDC                 | 309       | 418    | 27.96%  |
| Hitachi             | 130       | 160    | 11.76%  |
| Toshiba             | 121       | 136    | 10.95%  |
| Samsung Electronics | 61        | 90     | 5.52%   |
| HGST                | 43        | 49     | 3.89%   |
| Fujitsu             | 29        | 31     | 2.62%   |
| Maxtor              | 18        | 20     | 1.63%   |
| Unknown             | 11        | 13     | 1%      |
| IBM/Hitachi         | 4         | 5      | 0.36%   |
| Hewlett-Packard     | 4         | 8      | 0.36%   |
| ASMT                | 4         | 5      | 0.36%   |
| TO Exter            | 3         | 3      | 0.27%   |
| JMicron Technology  | 3         | 3      | 0.27%   |
| ExcelStor           | 3         | 4      | 0.27%   |
| Apple               | 3         | 3      | 0.27%   |
| WD MediaMax         | 2         | 3      | 0.18%   |
| USB                 | 2         | 2      | 0.18%   |
| STEC                | 2         | 3      | 0.18%   |
| External            | 2         | 2      | 0.18%   |
| XrayDisk            | 1         | 1      | 0.09%   |
| Synology            | 1         | 1      | 0.09%   |
| RSH-319             | 1         | 1      | 0.09%   |
| LaCie               | 1         | 1      | 0.09%   |
| Apricorn            | 1         | 1      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 109       | 148    | 16.39%  |
| Kingston            | 97        | 117    | 14.59%  |
| Crucial             | 59        | 78     | 8.87%   |
| SanDisk             | 50        | 60     | 7.52%   |
| WDC                 | 32        | 39     | 4.81%   |
| Intel               | 24        | 36     | 3.61%   |
| China               | 22        | 25     | 3.31%   |
| A-DATA Technology   | 22        | 24     | 3.31%   |
| Apacer              | 18        | 18     | 2.71%   |
| Toshiba             | 12        | 14     | 1.8%    |
| PNY                 | 10        | 13     | 1.5%    |
| Patriot             | 10        | 10     | 1.5%    |
| Micron Technology   | 10        | 10     | 1.5%    |
| Transcend           | 9         | 11     | 1.35%   |
| OCZ                 | 8         | 9      | 1.2%    |
| LITEONIT            | 8         | 8      | 1.2%    |
| Intenso             | 8         | 10     | 1.2%    |
| Team                | 6         | 6      | 0.9%    |
| SPCC                | 6         | 7      | 0.9%    |
| LITEON              | 6         | 7      | 0.9%    |
| Lexar               | 6         | 9      | 0.9%    |
| GOODRAM             | 6         | 6      | 0.9%    |
| Apple               | 6         | 12     | 0.9%    |
| SK hynix            | 5         | 6      | 0.75%   |
| KingSpec            | 5         | 7      | 0.75%   |
| Corsair             | 5         | 5      | 0.75%   |
| Plextor             | 4         | 6      | 0.6%    |
| NGFF                | 4         | 4      | 0.6%    |
| XrayDisk            | 3         | 3      | 0.45%   |
| Unknown             | 3         | 3      | 0.45%   |
| Netac               | 3         | 3      | 0.45%   |
| LDLC                | 3         | 3      | 0.45%   |
| Gigabyte Technology | 3         | 3      | 0.45%   |
| Dogfish             | 3         | 3      | 0.45%   |
| Verbatim            | 2         | 2      | 0.3%    |
| Teclast             | 2         | 2      | 0.3%    |
| ORTIAL              | 2         | 2      | 0.3%    |
| Mushkin             | 2         | 2      | 0.3%    |
| Londisk             | 2         | 2      | 0.3%    |
| Leven               | 2         | 4      | 0.3%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 970       | 1428   | 47.6%   |
| SSD     | 628       | 821    | 30.81%  |
| NVMe    | 209       | 280    | 10.26%  |
| MMC     | 207       | 275    | 10.16%  |
| Unknown | 24        | 33     | 1.18%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1415      | 2176   | 74.4%   |
| MMC  | 207       | 275    | 10.88%  |
| NVMe | 205       | 274    | 10.78%  |
| SAS  | 75        | 112    | 3.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1163      | 1552   | 70.79%  |
| 0.51-1.0   | 330       | 465    | 20.09%  |
| 1.01-2.0   | 82        | 115    | 4.99%   |
| 3.01-4.0   | 32        | 67     | 1.95%   |
| 2.01-3.0   | 15        | 22     | 0.91%   |
| 4.01-10.0  | 14        | 19     | 0.85%   |
| 10.01-20.0 | 6         | 8      | 0.37%   |
| 20.01-50.0 | 1         | 1      | 0.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 543       | 30.34%  |
| 251-500        | 406       | 22.68%  |
| 51-100         | 191       | 10.67%  |
| 501-1000       | 173       | 9.66%   |
| 21-50          | 145       | 8.1%    |
| 1-20           | 145       | 8.1%    |
| 1001-2000      | 82        | 4.58%   |
| More than 3000 | 58        | 3.24%   |
| 2001-3000      | 35        | 1.96%   |
| Unknown        | 12        | 0.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 920       | 49.92%  |
| 21-50          | 350       | 18.99%  |
| 101-250        | 186       | 10.09%  |
| 51-100         | 152       | 8.25%   |
| 251-500        | 78        | 4.23%   |
| 501-1000       | 63        | 3.42%   |
| 1001-2000      | 39        | 2.12%   |
| More than 3000 | 30        | 1.63%   |
| 2001-3000      | 13        | 0.71%   |
| Unknown        | 12        | 0.65%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB | 9         | 10     | 3.77%   |
| Seagate ST9500325AS 500GB          | 5         | 5      | 2.09%   |
| Apacer 16GB SATA Flash Drive SSD   | 5         | 5      | 2.09%   |
| Seagate ST500LT012-1DG142 500GB    | 4         | 4      | 1.67%   |
| Hitachi HTS545032B9A300 320GB      | 4         | 4      | 1.67%   |
| Seagate ST9320325AS 320GB          | 3         | 3      | 1.26%   |
| Seagate ST1000DM003-9YN162 1TB     | 3         | 3      | 1.26%   |
| HGST HTS545050A7E680 500GB         | 3         | 3      | 1.26%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 2         | 2      | 0.84%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 2         | 2      | 0.84%   |
| WDC WD40EFRX-68WT0N0 4TB           | 2         | 3      | 0.84%   |
| WDC WD20EFRX-68EUZN0 2TB           | 2         | 2      | 0.84%   |
| WDC WD10SPZX-24Z10T0 1TB           | 2         | 2      | 0.84%   |
| Toshiba MQ01ABD050 500GB           | 2         | 2      | 0.84%   |
| Toshiba DT01ACA050 500GB           | 2         | 2      | 0.84%   |
| Seagate ST9500420AS 500GB          | 2         | 2      | 0.84%   |
| Seagate ST9250315AS 250GB          | 2         | 2      | 0.84%   |
| Seagate ST500LM021-1KJ152 500GB    | 2         | 2      | 0.84%   |
| Seagate ST500DM002-1BD142 500GB    | 2         | 3      | 0.84%   |
| Seagate ST1000LM035-1RK172 1TB     | 2         | 2      | 0.84%   |
| Samsung Electronics HD502IJ 500GB  | 2         | 2      | 0.84%   |
| Hitachi HTS545050A7E380 500GB      | 2         | 2      | 0.84%   |
| Hitachi HTS545016B9A300 160GB      | 2         | 2      | 0.84%   |
| Hitachi HTS542512K9SA00 120GB      | 2         | 2      | 0.84%   |
| HGST HTS545050A7E380 500GB         | 2         | 2      | 0.84%   |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 1         | 1      | 0.42%   |
| WDC WD800BEVS-60RST0 80GB          | 1         | 1      | 0.42%   |
| WDC WD60EFRX-68L0BN1 6TB           | 1         | 2      | 0.42%   |
| WDC WD5000LUCT-62C26Y0 500GB       | 1         | 1      | 0.42%   |
| WDC WD5000LPCX-60VHAT1 500GB       | 1         | 1      | 0.42%   |
| WDC WD5000BPVT-75HXZT1 500GB       | 1         | 1      | 0.42%   |
| WDC WD5000AAKX-003CA0 500GB        | 1         | 1      | 0.42%   |
| WDC WD5000AAKX-001CA0 500GB        | 1         | 1      | 0.42%   |
| WDC WD400EB-00CPF0 40GB            | 1         | 1      | 0.42%   |
| WDC WD400BB-75CAA0 40GB            | 1         | 1      | 0.42%   |
| WDC WD3200BPVT-80ZEST0 320GB       | 1         | 1      | 0.42%   |
| WDC WD3200BPVT-75ZEST0 320GB       | 1         | 1      | 0.42%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 1         | 1      | 0.42%   |
| WDC WD3200BEVT-75A23T0 320GB       | 1         | 1      | 0.42%   |
| WDC WD3200BEKT-60PVMT0 320GB       | 1         | 1      | 0.42%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 66        | 78     | 28.45%  |
| WDC                 | 45        | 52     | 19.4%   |
| Hitachi             | 30        | 32     | 12.93%  |
| Toshiba             | 16        | 16     | 6.9%    |
| HGST                | 9         | 9      | 3.88%   |
| Samsung Electronics | 7         | 15     | 3.02%   |
| Maxtor              | 5         | 5      | 2.16%   |
| Kingston            | 5         | 5      | 2.16%   |
| Intel               | 5         | 6      | 2.16%   |
| Crucial             | 5         | 5      | 2.16%   |
| Apacer              | 5         | 5      | 2.16%   |
| SK hynix            | 4         | 4      | 1.72%   |
| Fujitsu             | 4         | 4      | 1.72%   |
| SanDisk             | 3         | 3      | 1.29%   |
| OCZ                 | 2         | 3      | 0.86%   |
| LITEON              | 2         | 2      | 0.86%   |
| KingSpec            | 2         | 4      | 0.86%   |
| ExcelStor           | 2         | 2      | 0.86%   |
| Apple               | 2         | 2      | 0.86%   |
| A-DATA Technology   | 2         | 2      | 0.86%   |
| Transcend           | 1         | 1      | 0.43%   |
| TCSUNBOW            | 1         | 1      | 0.43%   |
| Silicon Motion      | 1         | 1      | 0.43%   |
| Plextor             | 1         | 1      | 0.43%   |
| ORTIAL              | 1         | 1      | 0.43%   |
| NGFF                | 1         | 1      | 0.43%   |
| Mushkin             | 1         | 1      | 0.43%   |
| Micron Technology   | 1         | 1      | 0.43%   |
| LDLC                | 1         | 1      | 0.43%   |
| Kingmax             | 1         | 1      | 0.43%   |
| China               | 1         | 1      | 0.43%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 66        | 78     | 36.46%  |
| WDC                 | 42        | 49     | 23.2%   |
| Hitachi             | 30        | 32     | 16.57%  |
| Toshiba             | 16        | 16     | 8.84%   |
| HGST                | 9         | 9      | 4.97%   |
| Samsung Electronics | 6         | 14     | 3.31%   |
| Maxtor              | 5         | 5      | 2.76%   |
| Fujitsu             | 4         | 4      | 2.21%   |
| ExcelStor           | 2         | 2      | 1.1%    |
| Apple               | 1         | 1      | 0.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 174       | 210    | 77.33%  |
| SSD  | 48        | 52     | 21.33%  |
| NVMe | 3         | 3      | 1.33%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-75V0TT0 500GB      | 1         | 1      | 7.14%   |
| WDC WD3200AAJS-40RYA0 320GB       | 1         | 1      | 7.14%   |
| WDC WD2500BEVT-75A23T0 250GB      | 1         | 2      | 7.14%   |
| WDC WD1200BEVS-22UST0 120GB       | 1         | 1      | 7.14%   |
| WDC WD10SPZX-22Z10T0 1TB          | 1         | 1      | 7.14%   |
| Toshiba HDWD110 1TB               | 1         | 1      | 7.14%   |
| Seagate ST9320325AS 320GB         | 1         | 1      | 7.14%   |
| Seagate ST3500418AS 500GB         | 1         | 1      | 7.14%   |
| Samsung Electronics SSD 980 1TB   | 1         | 1      | 7.14%   |
| Samsung Electronics SSD 850 250GB | 1         | 1      | 7.14%   |
| Samsung Electronics HM320JI 320GB | 1         | 1      | 7.14%   |
| Samsung Electronics HD080HJ/ 80GB | 1         | 1      | 7.14%   |
| Intel SSDSA1M160G2HP 160GB        | 1         | 1      | 7.14%   |
| HGST HTS725025A7 250GB            | 1         | 1      | 7.14%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 6      | 35.71%  |
| Samsung Electronics | 4         | 4      | 28.57%  |
| Seagate             | 2         | 2      | 14.29%  |
| Toshiba             | 1         | 1      | 7.14%   |
| Intel               | 1         | 1      | 7.14%   |
| HGST                | 1         | 1      | 7.14%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 934       | 1523   | 49.89%  |
| Works    | 702       | 1034   | 37.5%   |
| Malfunc  | 222       | 265    | 11.86%  |
| Failed   | 14        | 15     | 0.75%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1143      | 61.52%  |
| AMD                              | 309       | 16.63%  |
| Nvidia                           | 76        | 4.09%   |
| Samsung Electronics              | 67        | 3.61%   |
| SanDisk                          | 28        | 1.51%   |
| JMicron Technology               | 25        | 1.35%   |
| ASMedia Technology               | 20        | 1.08%   |
| Kingston Technology Company      | 18        | 0.97%   |
| Micron Technology                | 17        | 0.91%   |
| VIA Technologies                 | 16        | 0.86%   |
| SK hynix                         | 14        | 0.75%   |
| Silicon Motion                   | 14        | 0.75%   |
| Silicon Integrated Systems [SiS] | 14        | 0.75%   |
| Marvell Technology Group         | 13        | 0.7%    |
| Micron/Crucial Technology        | 12        | 0.65%   |
| KIOXIA                           | 9         | 0.48%   |
| Toshiba America Info Systems     | 8         | 0.43%   |
| Silicon Image                    | 8         | 0.43%   |
| Phison Electronics               | 7         | 0.38%   |
| LSI Logic / Symbios Logic        | 7         | 0.38%   |
| Broadcom / LSI                   | 6         | 0.32%   |
| Zhaoxin                          | 4         | 0.22%   |
| Union Memory (Shenzhen)          | 3         | 0.16%   |
| ULi Electronics                  | 3         | 0.16%   |
| Solid State Storage Technology   | 3         | 0.16%   |
| ADATA Technology                 | 3         | 0.16%   |
| Yangtze Memory Technologies      | 2         | 0.11%   |
| Shenzhen Longsys Electronics     | 2         | 0.11%   |
| Seagate Technology               | 1         | 0.05%   |
| Realtek Semiconductor            | 1         | 0.05%   |
| Hosin Global Electronics         | 1         | 0.05%   |
| Hewlett-Packard                  | 1         | 0.05%   |
| Broadcom                         | 1         | 0.05%   |
| Apple                            | 1         | 0.05%   |
| Adaptec                          | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 182       | 8.02%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 88        | 3.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 69        | 3.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 63        | 2.78%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 62        | 2.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 58        | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 58        | 2.56%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 56        | 2.47%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 55        | 2.42%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 55        | 2.42%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 51        | 2.25%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 46        | 2.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 44        | 1.94%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 39        | 1.72%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 38        | 1.67%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 37        | 1.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 34        | 1.5%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 34        | 1.5%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 30        | 1.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 29        | 1.28%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 27        | 1.19%   |
| Nvidia MCP61 SATA Controller                                                            | 26        | 1.15%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 26        | 1.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 24        | 1.06%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 24        | 1.06%   |
| Nvidia MCP61 IDE                                                                        | 21        | 0.93%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 21        | 0.93%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 20        | 0.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 20        | 0.88%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 18        | 0.79%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 17        | 0.75%   |
| Intel SATA Controller [RAID mode]                                                       | 17        | 0.75%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 15        | 0.66%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 15        | 0.66%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 14        | 0.62%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 14        | 0.62%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 14        | 0.62%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 14        | 0.62%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 14        | 0.62%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 14        | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1197      | 60.98%  |
| IDE  | 459       | 23.38%  |
| NVMe | 203       | 10.34%  |
| RAID | 96        | 4.89%   |
| SAS  | 4         | 0.2%    |
| SCSI | 4         | 0.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 1342      | 76.55%  |
| AMD          | 393       | 22.42%  |
| ARM          | 12        | 0.68%   |
| CentaurHauls | 4         | 0.23%   |
| PowerMac7,2  | 1         | 0.06%   |
| Unknown      | 1         | 0.06%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 30        | 1.71%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 19        | 1.08%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz           | 18        | 1.03%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 17        | 0.97%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 16        | 0.91%   |
| Intel Atom CPU N270 @ 1.60GHz               | 15        | 0.85%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 14        | 0.8%    |
| Intel Core i5-8265U CPU @ 1.60GHz           | 12        | 0.68%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 12        | 0.68%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 12        | 0.68%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 11        | 0.63%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 11        | 0.63%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 11        | 0.63%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 11        | 0.63%   |
| Intel Atom CPU N450 @ 1.66GHz               | 11        | 0.63%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 11        | 0.63%   |
| ARM Processor                               | 11        | 0.63%   |
| AMD E-450 APU with Radeon HD Graphics       | 11        | 0.63%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 10        | 0.57%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 10        | 0.57%   |
| Intel Atom CPU N455 @ 1.66GHz               | 10        | 0.57%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 9         | 0.51%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 9         | 0.51%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 9         | 0.51%   |
| AMD E-300 APU with Radeon HD Graphics       | 9         | 0.51%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 8         | 0.46%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 8         | 0.46%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 8         | 0.46%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 8         | 0.46%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 8         | 0.46%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 8         | 0.46%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz        | 8         | 0.46%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 7         | 0.4%    |
| Intel Core i5-5200U CPU @ 2.20GHz           | 7         | 0.4%    |
| Intel Core i5-4200U CPU @ 1.60GHz           | 7         | 0.4%    |
| Intel Core i5-3320M CPU @ 2.60GHz           | 7         | 0.4%    |
| Intel Core i5-3230M CPU @ 2.60GHz           | 7         | 0.4%    |
| Intel Core i5 CPU M 460 @ 2.53GHz           | 7         | 0.4%    |
| Intel Core i3-3217U CPU @ 1.80GHz           | 7         | 0.4%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 7         | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 266       | 15.17%  |
| Intel Celeron           | 213       | 12.14%  |
| Intel Core i7           | 147       | 8.38%   |
| Intel Atom              | 142       | 8.1%    |
| Intel Core i3           | 128       | 7.3%    |
| Intel Core 2 Duo        | 122       | 6.96%   |
| Other                   | 63        | 3.59%   |
| Intel Pentium           | 53        | 3.02%   |
| Intel Pentium Dual      | 40        | 2.28%   |
| Intel Pentium Dual-Core | 39        | 2.22%   |
| AMD Ryzen 5             | 37        | 2.11%   |
| Intel Xeon              | 33        | 1.88%   |
| AMD Ryzen 7             | 33        | 1.88%   |
| AMD E                   | 28        | 1.6%    |
| AMD Athlon 64 X2        | 28        | 1.6%    |
| Intel Core 2            | 25        | 1.43%   |
| AMD A6                  | 23        | 1.31%   |
| AMD A4                  | 23        | 1.31%   |
| AMD E1                  | 21        | 1.2%    |
| Intel Pentium 4         | 18        | 1.03%   |
| AMD A10                 | 17        | 0.97%   |
| Intel Genuine           | 16        | 0.91%   |
| AMD FX                  | 15        | 0.86%   |
| Intel Core 2 Quad       | 14        | 0.8%    |
| AMD A8                  | 14        | 0.8%    |
| AMD Athlon II X2        | 13        | 0.74%   |
| AMD E2                  | 10        | 0.57%   |
| AMD Athlon 64           | 9         | 0.51%   |
| AMD Athlon              | 9         | 0.51%   |
| Intel Pentium Silver    | 8         | 0.46%   |
| AMD Ryzen 3             | 8         | 0.46%   |
| Intel Celeron Dual-Core | 7         | 0.4%    |
| AMD GX                  | 7         | 0.4%    |
| Intel Pentium M         | 6         | 0.34%   |
| Intel Pentium D         | 6         | 0.34%   |
| Intel Celeron M         | 6         | 0.34%   |
| AMD Ryzen 9             | 6         | 0.34%   |
| AMD Phenom II X4        | 6         | 0.34%   |
| AMD Mobile Sempron      | 6         | 0.34%   |
| AMD C-50                | 6         | 0.34%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1011      | 57.67%  |
| 4       | 461       | 26.3%   |
| 1       | 139       | 7.93%   |
| 6       | 54        | 3.08%   |
| 8       | 50        | 2.85%   |
| 12      | 9         | 0.51%   |
| 3       | 9         | 0.51%   |
| 10      | 7         | 0.4%    |
| 16      | 4         | 0.23%   |
| Unknown | 4         | 0.23%   |
| 64      | 1         | 0.06%   |
| 40      | 1         | 0.06%   |
| 32      | 1         | 0.06%   |
| 20      | 1         | 0.06%   |
| 14      | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1731      | 98.75%  |
| 2       | 17        | 0.97%   |
| Unknown | 4         | 0.23%   |
| 4       | 1         | 0.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 996       | 56.82%  |
| 2       | 752       | 42.9%   |
| Unknown | 4         | 0.23%   |
| 8       | 1         | 0.06%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1678      | 95.72%  |
| 32-bit         | 65        | 3.71%   |
| Unknown        | 9         | 0.51%   |
| 64-bit         | 1         | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 683       | 38.22%  |
| 0x206a7    | 83        | 4.64%   |
| 0x306a9    | 67        | 3.75%   |
| 0x1067a    | 65        | 3.64%   |
| 0x6fd      | 56        | 3.13%   |
| 0x406c4    | 36        | 2.01%   |
| 0x20655    | 33        | 1.85%   |
| 0x306c3    | 32        | 1.79%   |
| 0x05000119 | 32        | 1.79%   |
| 0x30678    | 31        | 1.73%   |
| 0x40651    | 29        | 1.62%   |
| 0x106ca    | 28        | 1.57%   |
| 0x406c3    | 24        | 1.34%   |
| 0x406e3    | 21        | 1.18%   |
| 0x10676    | 19        | 1.06%   |
| 0x0700010f | 19        | 1.06%   |
| 0x706a8    | 18        | 1.01%   |
| 0x706a1    | 18        | 1.01%   |
| 0x6fb      | 18        | 1.01%   |
| 0x106c2    | 18        | 1.01%   |
| 0x806ec    | 17        | 0.95%   |
| 0x6f6      | 14        | 0.78%   |
| 0x806e9    | 13        | 0.73%   |
| 0x20652    | 13        | 0.73%   |
| 0x06006705 | 13        | 0.73%   |
| 0x806ea    | 12        | 0.67%   |
| 0x506c9    | 12        | 0.67%   |
| 0x06001119 | 12        | 0.67%   |
| 0x010000c8 | 12        | 0.67%   |
| 0x906ea    | 11        | 0.62%   |
| 0x6e8      | 11        | 0.62%   |
| 0x6d8      | 10        | 0.56%   |
| 0x306d4    | 10        | 0.56%   |
| 0x05000029 | 10        | 0.56%   |
| 0x806c1    | 9         | 0.5%    |
| 0x06000852 | 9         | 0.5%    |
| 0x706e5    | 8         | 0.45%   |
| 0x10661    | 8         | 0.45%   |
| 0x0a50000c | 8         | 0.45%   |
| 0x06006704 | 8         | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Silvermont       | 156       | 8.89%   |
| Core             | 140       | 7.98%   |
| Penryn           | 127       | 7.24%   |
| SandyBridge      | 124       | 7.07%   |
| IvyBridge        | 116       | 6.61%   |
| KabyLake         | 106       | 6.04%   |
| Haswell          | 101       | 5.76%   |
| Westmere         | 85        | 4.85%   |
| Bonnell          | 67        | 3.82%   |
| Goldmont plus    | 59        | 3.36%   |
| K8 Hammer        | 58        | 3.31%   |
| Skylake          | 55        | 3.14%   |
| Bobcat           | 55        | 3.14%   |
| K10              | 42        | 2.39%   |
| Excavator        | 42        | 2.39%   |
| Unknown          | 34        | 1.94%   |
| NetBurst         | 31        | 1.77%   |
| Goldmont         | 31        | 1.77%   |
| Piledriver       | 30        | 1.71%   |
| P6               | 28        | 1.6%    |
| Jaguar           | 27        | 1.54%   |
| Zen 3            | 25        | 1.43%   |
| Zen 2            | 25        | 1.43%   |
| Zen+             | 24        | 1.37%   |
| Broadwell        | 22        | 1.25%   |
| TigerLake        | 17        | 0.97%   |
| IceLake          | 17        | 0.97%   |
| Nehalem          | 16        | 0.91%   |
| Puma             | 15        | 0.86%   |
| Zen              | 13        | 0.74%   |
| CometLake        | 13        | 0.74%   |
| Tremont          | 12        | 0.68%   |
| Alderlake Hybrid | 12        | 0.68%   |
| K8 & K10 hybrid  | 8         | 0.46%   |
| Steamroller      | 7         | 0.4%    |
| K10 Llano        | 5         | 0.29%   |
| Gracemont        | 5         | 0.29%   |
| Bulldozer        | 3         | 0.17%   |
| K6               | 1         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1066      | 56.13%  |
| AMD                              | 450       | 23.7%   |
| Nvidia                           | 346       | 18.22%  |
| Matrox Electronics Systems       | 13        | 0.68%   |
| Silicon Integrated Systems [SiS] | 12        | 0.63%   |
| VIA Technologies                 | 6         | 0.32%   |
| Zhaoxin                          | 4         | 0.21%   |
| S3 Graphics                      | 1         | 0.05%   |
| ASPEED Technology                | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 102       | 5.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 90        | 4.43%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 72        | 3.54%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 66        | 3.25%   |
| Intel Core Processor Integrated Graphics Controller                                      | 55        | 2.71%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 54        | 2.66%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 54        | 2.66%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 53        | 2.61%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 49        | 2.41%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 43        | 2.12%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 34        | 1.67%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 32        | 1.57%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 30        | 1.48%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 28        | 1.38%   |
| Intel HD Graphics 500                                                                    | 28        | 1.38%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 21        | 1.03%   |
| Intel HD Graphics 620                                                                    | 20        | 0.98%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 19        | 0.93%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 18        | 0.89%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 18        | 0.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 17        | 0.84%   |
| Intel UHD Graphics 620                                                                   | 17        | 0.84%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 17        | 0.84%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 17        | 0.84%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 16        | 0.79%   |
| Intel HD Graphics 5500                                                                   | 16        | 0.79%   |
| Nvidia GT218 [GeForce 210]                                                               | 15        | 0.74%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 15        | 0.74%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 15        | 0.74%   |
| Intel HD Graphics 530                                                                    | 14        | 0.69%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 14        | 0.69%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 14        | 0.69%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 13        | 0.64%   |
| Intel JasperLake [UHD Graphics]                                                          | 13        | 0.64%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 13        | 0.64%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 13        | 0.64%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 12        | 0.59%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 12        | 0.59%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 12        | 0.59%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 11        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 909       | 51.68%  |
| 1 x AMD            | 357       | 20.3%   |
| 1 x Nvidia         | 244       | 13.87%  |
| Intel + Nvidia     | 86        | 4.89%   |
| Intel + AMD        | 44        | 2.5%    |
| 2 x AMD            | 38        | 2.16%   |
| Other              | 21        | 1.19%   |
| 1 x SiS            | 12        | 0.68%   |
| 1 x Matrox         | 12        | 0.68%   |
| AMD + Nvidia       | 10        | 0.57%   |
| 2 x Intel          | 9         | 0.51%   |
| 1 x VIA            | 6         | 0.34%   |
| 1 x Zhaoxin        | 4         | 0.23%   |
| 2 x Nvidia         | 2         | 0.11%   |
| 1 x S3 Graphics    | 1         | 0.06%   |
| Nvidia + Matrox    | 1         | 0.06%   |
| Intel + 2 x Nvidia | 1         | 0.06%   |
| Intel + 2 x AMD    | 1         | 0.06%   |
| 1 x ASPEED         | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1552      | 88.13%  |
| Proprietary | 125       | 7.1%    |
| Unknown     | 84        | 4.77%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1111      | 62.56%  |
| 0.01-0.5   | 350       | 19.71%  |
| 1.01-2.0   | 124       | 6.98%   |
| 0.51-1.0   | 110       | 6.19%   |
| 3.01-4.0   | 39        | 2.2%    |
| 7.01-8.0   | 15        | 0.84%   |
| 5.01-6.0   | 11        | 0.62%   |
| 2.01-3.0   | 8         | 0.45%   |
| 8.01-16.0  | 8         | 0.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 238       | 13.98%  |
| AU Optronics            | 224       | 13.16%  |
| LG Display              | 160       | 9.4%    |
| BOE                     | 143       | 8.4%    |
| Chimei Innolux          | 126       | 7.4%    |
| Dell                    | 83        | 4.88%   |
| Goldstar                | 55        | 3.23%   |
| Acer                    | 54        | 3.17%   |
| Hewlett-Packard         | 47        | 2.76%   |
| Chi Mei Optoelectronics | 45        | 2.64%   |
| Lenovo                  | 38        | 2.23%   |
| Apple                   | 38        | 2.23%   |
| Philips                 | 37        | 2.17%   |
| LG Philips              | 31        | 1.82%   |
| HannStar                | 26        | 1.53%   |
| AOC                     | 26        | 1.53%   |
| Ancor Communications    | 23        | 1.35%   |
| BenQ                    | 22        | 1.29%   |
| InfoVision              | 18        | 1.06%   |
| Iiyama                  | 16        | 0.94%   |
| CPT                     | 16        | 0.94%   |
| Sharp                   | 15        | 0.88%   |
| Unknown                 | 12        | 0.71%   |
| PANDA                   | 12        | 0.71%   |
| Vizio                   | 10        | 0.59%   |
| Sony                    | 10        | 0.59%   |
| NEC Computers           | 9         | 0.53%   |
| Toshiba                 | 8         | 0.47%   |
| LG Electronics          | 7         | 0.41%   |
| ASUSTek Computer        | 7         | 0.41%   |
| Sceptre Tech            | 6         | 0.35%   |
| Fujitsu Siemens         | 6         | 0.35%   |
| Eizo                    | 6         | 0.35%   |
| ViewSonic               | 5         | 0.29%   |
| RTK                     | 5         | 0.29%   |
| HKC                     | 5         | 0.29%   |
| MSI                     | 4         | 0.24%   |
| InnoLux Display         | 4         | 0.24%   |
| Unknown (ADA)           | 3         | 0.18%   |
| Positivo                | 3         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch     | 11        | 0.64%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 11        | 0.64%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 10        | 0.58%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 9         | 0.52%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 8         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 8         | 0.46%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 8         | 0.46%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch             | 7         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 7         | 0.41%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 7         | 0.41%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 7         | 0.41%   |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch                  | 6         | 0.35%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 6         | 0.35%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 6         | 0.35%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 6         | 0.35%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 6         | 0.35%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                | 5         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 5         | 0.29%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 5         | 0.29%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                     | 5         | 0.29%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 5         | 0.29%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 5         | 0.29%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 5         | 0.29%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 5         | 0.29%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 5         | 0.29%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch            | 5         | 0.29%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 4         | 0.23%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 4         | 0.23%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch              | 4         | 0.23%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 4         | 0.23%   |
| Dell AW2518HF DELA102 1920x1080 544x303mm 24.5-inch                      | 4         | 0.23%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 4         | 0.23%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 4         | 0.23%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 4         | 0.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 4         | 0.23%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 4         | 0.23%   |
| BOE LCD Monitor BOE0771 1366x768 256x144mm 11.6-inch                     | 4         | 0.23%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 4         | 0.23%   |
| BOE LCD Monitor BOE0635 1920x1080 309x173mm 13.9-inch                    | 4         | 0.23%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch            | 4         | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 521       | 31.14%  |
| 1920x1080 (FHD)    | 481       | 28.75%  |
| 1280x800 (WXGA)    | 135       | 8.07%   |
| 1280x1024 (SXGA)   | 82        | 4.9%    |
| 1600x900 (HD+)     | 79        | 4.72%   |
| 1680x1050 (WSXGA+) | 55        | 3.29%   |
| 3840x2160 (4K)     | 52        | 3.11%   |
| 1440x900 (WXGA+)   | 51        | 3.05%   |
| 1024x600           | 37        | 2.21%   |
| 1920x1200 (WUXGA)  | 34        | 2.03%   |
| 2560x1440 (QHD)    | 33        | 1.97%   |
| 1024x768 (XGA)     | 18        | 1.08%   |
| 1360x768           | 16        | 0.96%   |
| Unknown            | 10        | 0.6%    |
| 2288x1287          | 8         | 0.48%   |
| 3440x1440          | 5         | 0.3%    |
| 2160x1440          | 5         | 0.3%    |
| 3840x2400          | 4         | 0.24%   |
| 2560x1600          | 4         | 0.24%   |
| 1280x720 (HD)      | 4         | 0.24%   |
| 3200x1800 (QHD+)   | 3         | 0.18%   |
| 2880x1920          | 3         | 0.18%   |
| 2560x1080          | 3         | 0.18%   |
| 1920x540           | 3         | 0.18%   |
| 1280x768           | 3         | 0.18%   |
| 3600x1200          | 2         | 0.12%   |
| 3200x1080          | 2         | 0.12%   |
| 2880x1800          | 2         | 0.12%   |
| 2048x1536          | 2         | 0.12%   |
| 1600x1200          | 2         | 0.12%   |
| 800x600            | 1         | 0.06%   |
| 5760x2160          | 1         | 0.06%   |
| 3840x1600          | 1         | 0.06%   |
| 3840x1080          | 1         | 0.06%   |
| 3200x1200          | 1         | 0.06%   |
| 3120x2080          | 1         | 0.06%   |
| 3000x2000          | 1         | 0.06%   |
| 2160x1200          | 1         | 0.06%   |
| 2048x1152          | 1         | 0.06%   |
| 1920x1280          | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 477       | 28.11%  |
| 13      | 171       | 10.08%  |
| 14      | 160       | 9.43%   |
| 17      | 104       | 6.13%   |
| 24      | 86        | 5.07%   |
| 11      | 74        | 4.36%   |
| 19      | 71        | 4.18%   |
| 23      | 70        | 4.12%   |
| 27      | 64        | 3.77%   |
| 21      | 63        | 3.71%   |
| Unknown | 53        | 3.12%   |
| 10      | 42        | 2.47%   |
| 18      | 37        | 2.18%   |
| 12      | 37        | 2.18%   |
| 22      | 34        | 2%      |
| 20      | 34        | 2%      |
| 31      | 16        | 0.94%   |
| 84      | 11        | 0.65%   |
| 72      | 10        | 0.59%   |
| 34      | 6         | 0.35%   |
| 32      | 6         | 0.35%   |
| 26      | 6         | 0.35%   |
| 142     | 5         | 0.29%   |
| 40      | 5         | 0.29%   |
| 47      | 4         | 0.24%   |
| 8       | 4         | 0.24%   |
| 52      | 3         | 0.18%   |
| 49      | 3         | 0.18%   |
| 48      | 3         | 0.18%   |
| 42      | 3         | 0.18%   |
| 9       | 3         | 0.18%   |
| 7       | 3         | 0.18%   |
| 65      | 2         | 0.12%   |
| 60      | 2         | 0.12%   |
| 54      | 2         | 0.12%   |
| 43      | 2         | 0.12%   |
| 39      | 2         | 0.12%   |
| 38      | 2         | 0.12%   |
| 29      | 2         | 0.12%   |
| 28      | 2         | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 742       | 44.06%  |
| 201-300        | 240       | 14.25%  |
| 501-600        | 219       | 13%     |
| 401-500        | 193       | 11.46%  |
| 351-400        | 124       | 7.36%   |
| Unknown        | 53        | 3.15%   |
| 601-700        | 25        | 1.48%   |
| 1501-2000      | 22        | 1.31%   |
| 1001-1500      | 21        | 1.25%   |
| 701-800        | 14        | 0.83%   |
| 801-900        | 10        | 0.59%   |
| 101-200        | 9         | 0.53%   |
| 901-1000       | 7         | 0.42%   |
| More than 2000 | 5         | 0.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1152      | 71.96%  |
| 16/10   | 264       | 16.49%  |
| 5/4     | 79        | 4.93%   |
| Unknown | 42        | 2.62%   |
| 4/3     | 31        | 1.94%   |
| 3/2     | 16        | 1%      |
| 21/9    | 7         | 0.44%   |
| 1.00    | 5         | 0.31%   |
| 6/5     | 2         | 0.12%   |
| 32/9    | 2         | 0.12%   |
| 0.56    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 471       | 27.85%  |
| 81-90          | 269       | 15.91%  |
| 201-250        | 208       | 12.3%   |
| 151-200        | 126       | 7.45%   |
| 51-60          | 74        | 4.38%   |
| 301-350        | 68        | 4.02%   |
| 141-150        | 65        | 3.84%   |
| 71-80          | 60        | 3.55%   |
| Unknown        | 53        | 3.13%   |
| 121-130        | 50        | 2.96%   |
| 41-50          | 45        | 2.66%   |
| More than 1000 | 42        | 2.48%   |
| 61-70          | 35        | 2.07%   |
| 251-300        | 34        | 2.01%   |
| 351-500        | 30        | 1.77%   |
| 501-1000       | 25        | 1.48%   |
| 131-140        | 16        | 0.95%   |
| 1-40           | 8         | 0.47%   |
| 91-100         | 7         | 0.41%   |
| 111-120        | 5         | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 589       | 35.4%   |
| 51-100        | 568       | 34.13%  |
| 121-160       | 328       | 19.71%  |
| 161-240       | 66        | 3.97%   |
| Unknown       | 53        | 3.19%   |
| 1-50          | 44        | 2.64%   |
| More than 240 | 16        | 0.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1549      | 87.22%  |
| 2     | 158       | 8.9%    |
| 0     | 59        | 3.32%   |
| 3     | 9         | 0.51%   |
| 4     | 1         | 0.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 940       | 34.72%  |
| Intel                            | 614       | 22.68%  |
| Qualcomm Atheros                 | 375       | 13.85%  |
| Broadcom                         | 196       | 7.24%   |
| Nvidia                           | 65        | 2.4%    |
| Marvell Technology Group         | 63        | 2.33%   |
| Ralink Technology                | 59        | 2.18%   |
| Broadcom Limited                 | 52        | 1.92%   |
| Ralink                           | 45        | 1.66%   |
| TP-Link                          | 33        | 1.22%   |
| Samsung Electronics              | 21        | 0.78%   |
| MediaTek                         | 18        | 0.66%   |
| ASIX Electronics                 | 18        | 0.66%   |
| Xiaomi                           | 15        | 0.55%   |
| VIA Technologies                 | 11        | 0.41%   |
| Attansic Technology              | 11        | 0.41%   |
| Silicon Integrated Systems [SiS] | 10        | 0.37%   |
| NetGear                          | 10        | 0.37%   |
| JMicron Technology               | 9         | 0.33%   |
| Huawei Technologies              | 9         | 0.33%   |
| Belkin Components                | 9         | 0.33%   |
| Qualcomm Atheros Communications  | 8         | 0.3%    |
| D-Link                           | 8         | 0.3%    |
| Mellanox Technologies            | 5         | 0.18%   |
| Dell                             | 5         | 0.18%   |
| ASUSTek Computer                 | 5         | 0.18%   |
| AMD                              | 5         | 0.18%   |
| OPPO Electronics                 | 4         | 0.15%   |
| ICS Advent                       | 4         | 0.15%   |
| Edimax Technology                | 4         | 0.15%   |
| DisplayLink                      | 4         | 0.15%   |
| D-Link System                    | 4         | 0.15%   |
| Qualcomm                         | 3         | 0.11%   |
| Motorola PCS                     | 3         | 0.11%   |
| Micro Star International         | 3         | 0.11%   |
| Hewlett-Packard                  | 3         | 0.11%   |
| Fibocom                          | 3         | 0.11%   |
| 3Com                             | 3         | 0.11%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.07%   |
| ULi Electronics                  | 2         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 538       | 17.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 190       | 6.09%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 72        | 2.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 54        | 1.73%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 45        | 1.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 44        | 1.41%   |
| Intel Wireless 7260                                                     | 43        | 1.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 42        | 1.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 41        | 1.31%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 41        | 1.31%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 39        | 1.25%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 36        | 1.15%   |
| Intel Wireless 7265                                                     | 35        | 1.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 33        | 1.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 30        | 0.96%   |
| Intel Wireless 3165                                                     | 30        | 0.96%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 27        | 0.87%   |
| Ralink MT7601U Wireless Adapter                                         | 25        | 0.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 23        | 0.74%   |
| Nvidia MCP61 Ethernet                                                   | 23        | 0.74%   |
| Intel 82577LM Gigabit Network Connection                                | 23        | 0.74%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 21        | 0.67%   |
| Intel Wireless 8265 / 8275                                              | 20        | 0.64%   |
| Intel Ethernet Connection I217-LM                                       | 20        | 0.64%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 19        | 0.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 18        | 0.58%   |
| Intel Wi-Fi 6 AX200                                                     | 18        | 0.58%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 18        | 0.58%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 17        | 0.54%   |
| Intel Wireless 8260                                                     | 17        | 0.54%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 16        | 0.51%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 16        | 0.51%   |
| Intel Wireless 3160                                                     | 16        | 0.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 15        | 0.48%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 15        | 0.48%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 15        | 0.48%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 14        | 0.45%   |
| Realtek 802.11n WLAN Adapter                                            | 14        | 0.45%   |
| Realtek 802.11ac NIC                                                    | 14        | 0.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 14        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 453       | 31.86%  |
| Qualcomm Atheros                      | 311       | 21.87%  |
| Realtek Semiconductor                 | 280       | 19.69%  |
| Broadcom                              | 128       | 9%      |
| Ralink Technology                     | 59        | 4.15%   |
| Ralink                                | 45        | 3.16%   |
| TP-Link                               | 31        | 2.18%   |
| Broadcom Limited                      | 27        | 1.9%    |
| MediaTek                              | 15        | 1.05%   |
| NetGear                               | 9         | 0.63%   |
| Belkin Components                     | 9         | 0.63%   |
| Qualcomm Atheros Communications       | 8         | 0.56%   |
| D-Link                                | 7         | 0.49%   |
| Marvell Technology Group              | 5         | 0.35%   |
| ASUSTek Computer                      | 5         | 0.35%   |
| Edimax Technology                     | 4         | 0.28%   |
| Micro Star International              | 3         | 0.21%   |
| Fibocom                               | 3         | 0.21%   |
| Dell                                  | 3         | 0.21%   |
| Sierra Wireless                       | 2         | 0.14%   |
| Linksys                               | 2         | 0.14%   |
| D-Link System                         | 2         | 0.14%   |
| ZyXEL Communications                  | 1         | 0.07%   |
| ZTopInc                               | 1         | 0.07%   |
| Texas Instruments                     | 1         | 0.07%   |
| Tenda                                 | 1         | 0.07%   |
| Sitecom Europe                        | 1         | 0.07%   |
| Samsung Electronics                   | 1         | 0.07%   |
| Qualcomm                              | 1         | 0.07%   |
| Microsoft                             | 1         | 0.07%   |
| Logitec                               | 1         | 0.07%   |
| IMC Networks                          | 1         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 72        | 5.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 44        | 3.06%   |
| Intel Wireless 7260                                                     | 43        | 2.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 42        | 2.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 41        | 2.86%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 41        | 2.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 39        | 2.72%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 36        | 2.51%   |
| Intel Wireless 7265                                                     | 35        | 2.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 33        | 2.3%    |
| Intel Wireless 3165                                                     | 30        | 2.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 27        | 1.88%   |
| Ralink MT7601U Wireless Adapter                                         | 25        | 1.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 23        | 1.6%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 21        | 1.46%   |
| Intel Wireless 8265 / 8275                                              | 20        | 1.39%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 19        | 1.32%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 18        | 1.25%   |
| Intel Wi-Fi 6 AX200                                                     | 18        | 1.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 18        | 1.25%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 17        | 1.18%   |
| Intel Wireless 8260                                                     | 17        | 1.18%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 16        | 1.11%   |
| Intel Wireless 3160                                                     | 16        | 1.11%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 15        | 1.04%   |
| Realtek 802.11n WLAN Adapter                                            | 14        | 0.97%   |
| Realtek 802.11ac NIC                                                    | 14        | 0.97%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 14        | 0.97%   |
| Broadcom BCM43142 802.11b/g/n                                           | 13        | 0.91%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 11        | 0.77%   |
| Ralink RT5370 Wireless Adapter                                          | 11        | 0.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 11        | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 11        | 0.77%   |
| Intel Wi-Fi 6 AX201                                                     | 11        | 0.77%   |
| Intel Centrino Ultimate-N 6300                                          | 11        | 0.77%   |
| Intel Centrino Advanced-N 6200                                          | 11        | 0.77%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 11        | 0.77%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 11        | 0.77%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 11        | 0.77%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 11        | 0.77%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 827       | 51.08%  |
| Intel                            | 293       | 18.1%   |
| Qualcomm Atheros                 | 112       | 6.92%   |
| Broadcom                         | 91        | 5.62%   |
| Nvidia                           | 65        | 4.01%   |
| Marvell Technology Group         | 58        | 3.58%   |
| Broadcom Limited                 | 25        | 1.54%   |
| ASIX Electronics                 | 18        | 1.11%   |
| Xiaomi                           | 15        | 0.93%   |
| Samsung Electronics              | 14        | 0.86%   |
| VIA Technologies                 | 11        | 0.68%   |
| Attansic Technology              | 11        | 0.68%   |
| Silicon Integrated Systems [SiS] | 10        | 0.62%   |
| JMicron Technology               | 9         | 0.56%   |
| Huawei Technologies              | 7         | 0.43%   |
| OPPO Electronics                 | 4         | 0.25%   |
| ICS Advent                       | 4         | 0.25%   |
| DisplayLink                      | 4         | 0.25%   |
| Motorola PCS                     | 3         | 0.19%   |
| MediaTek                         | 3         | 0.19%   |
| 3Com                             | 3         | 0.19%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.12%   |
| ULi Electronics                  | 2         | 0.12%   |
| TP-Link                          | 2         | 0.12%   |
| Qualcomm                         | 2         | 0.12%   |
| D-Link System                    | 2         | 0.12%   |
| Aquantia                         | 2         | 0.12%   |
| Accton Technology                | 2         | 0.12%   |
| Yulong                           | 1         | 0.06%   |
| Trident Microsystems             | 1         | 0.06%   |
| T & A Mobile Phones              | 1         | 0.06%   |
| Spreadtrum Communications        | 1         | 0.06%   |
| Research In Motion               | 1         | 0.06%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.06%   |
| NetGear                          | 1         | 0.06%   |
| Microchip Technology             | 1         | 0.06%   |
| Mellanox Technologies            | 1         | 0.06%   |
| LG Electronics                   | 1         | 0.06%   |
| Lab126                           | 1         | 0.06%   |
| Intersil                         | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 538       | 32.84%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 190       | 11.6%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 54        | 3.3%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 45        | 2.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 30        | 1.83%   |
| Nvidia MCP61 Ethernet                                                  | 23        | 1.4%    |
| Intel 82577LM Gigabit Network Connection                               | 23        | 1.4%    |
| Intel Ethernet Connection I217-LM                                      | 20        | 1.22%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 16        | 0.98%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 15        | 0.92%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 15        | 0.92%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 14        | 0.85%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 14        | 0.85%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 14        | 0.85%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 12        | 0.73%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 11        | 0.67%   |
| Intel I211 Gigabit Network Connection                                  | 11        | 0.67%   |
| Intel Ethernet Connection I218-LM                                      | 11        | 0.67%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 11        | 0.67%   |
| Attansic AR8152 v2.0 Fast Ethernet                                     | 11        | 0.67%   |
| ASIX AX88179 Gigabit Ethernet                                          | 11        | 0.67%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 10        | 0.61%   |
| Intel 82579V Gigabit Network Connection                                | 10        | 0.61%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 10        | 0.61%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 9         | 0.55%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 9         | 0.55%   |
| Realtek RTL8125 2.5GbE Controller                                      | 9         | 0.55%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 9         | 0.55%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 9         | 0.55%   |
| Intel Ethernet Controller I225-V                                       | 9         | 0.55%   |
| Intel 82567LM Gigabit Network Connection                               | 9         | 0.55%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 8         | 0.49%   |
| Intel 82574L Gigabit Network Connection                                | 8         | 0.49%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 8         | 0.49%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 7         | 0.43%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 7         | 0.43%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 7         | 0.43%   |
| Nvidia MCP79 Ethernet                                                  | 7         | 0.43%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 7         | 0.43%   |
| Intel Ethernet Connection I219-LM                                      | 7         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1500      | 51.87%  |
| WiFi     | 1345      | 46.51%  |
| Modem    | 42        | 1.45%   |
| Unknown  | 5         | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1041      | 58.95%  |
| Ethernet | 725       | 41.05%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 965       | 55.02%  |
| 1     | 649       | 37%     |
| 0     | 98        | 5.59%   |
| 3     | 35        | 2%      |
| 4     | 6         | 0.34%   |
| 6     | 1         | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1384      | 77.97%  |
| Yes  | 391       | 22.03%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 306       | 35.13%  |
| Realtek Semiconductor           | 102       | 11.71%  |
| Qualcomm Atheros Communications | 77        | 8.84%   |
| Broadcom                        | 59        | 6.77%   |
| Cambridge Silicon Radio         | 51        | 5.86%   |
| Lite-On Technology              | 40        | 4.59%   |
| Apple                           | 40        | 4.59%   |
| Foxconn / Hon Hai               | 32        | 3.67%   |
| IMC Networks                    | 31        | 3.56%   |
| Hewlett-Packard                 | 23        | 2.64%   |
| Dell                            | 23        | 2.64%   |
| Ralink                          | 17        | 1.95%   |
| Toshiba                         | 12        | 1.38%   |
| ASUSTek Computer                | 11        | 1.26%   |
| Alps Electric                   | 10        | 1.15%   |
| MediaTek                        | 6         | 0.69%   |
| Marvell Semiconductor           | 5         | 0.57%   |
| TP-Link                         | 4         | 0.46%   |
| Qcom                            | 3         | 0.34%   |
| Micro Star International        | 3         | 0.34%   |
| Ralink Technology               | 2         | 0.23%   |
| Logitech                        | 2         | 0.23%   |
| Integrated System Solution      | 2         | 0.23%   |
| Askey Computer                  | 2         | 0.23%   |
| USI                             | 1         | 0.11%   |
| Syntek                          | 1         | 0.11%   |
| Smart Modular Technologies      | 1         | 0.11%   |
| Realtek                         | 1         | 0.11%   |
| HTC (High Tech Computer)        | 1         | 0.11%   |
| Fujitsu                         | 1         | 0.11%   |
| Dynex                           | 1         | 0.11%   |
| Chicony Electronics             | 1         | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 165       | 18.86%  |
| Realtek Bluetooth Radio                                                             | 68        | 7.77%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 51        | 5.83%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 42        | 4.8%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 33        | 3.77%   |
| Intel AX201 Bluetooth                                                               | 33        | 3.77%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 17        | 1.94%   |
| Ralink RT3290 Bluetooth                                                             | 17        | 1.94%   |
| Intel AX200 Bluetooth                                                               | 17        | 1.94%   |
| Apple Bluetooth Host Controller                                                     | 17        | 1.94%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 16        | 1.83%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 13        | 1.49%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 13        | 1.49%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 12        | 1.37%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 12        | 1.37%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 12        | 1.37%   |
| Apple Bluetooth HCI                                                                 | 12        | 1.37%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 11        | 1.26%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 11        | 1.26%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 10        | 1.14%   |
| IMC Networks Bluetooth Device                                                       | 10        | 1.14%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 9         | 1.03%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 9         | 1.03%   |
| Realtek RTL8723B Bluetooth                                                          | 8         | 0.91%   |
| Intel AX210 Bluetooth                                                               | 8         | 0.91%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 8         | 0.91%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 7         | 0.8%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 7         | 0.8%    |
| IMC Networks Bluetooth Radio                                                        | 7         | 0.8%    |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 7         | 0.8%    |
| Apple Bluetooth USB Host Controller                                                 | 7         | 0.8%    |
| Lite-On Bluetooth Device                                                            | 6         | 0.69%   |
| Intel AX211 Bluetooth                                                               | 6         | 0.69%   |
| Dell Wireless 365 Bluetooth                                                         | 6         | 0.69%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 6         | 0.69%   |
| Toshiba Integrated Bluetooth HCI                                                    | 5         | 0.57%   |
| Realtek RTL8821A Bluetooth                                                          | 5         | 0.57%   |
| MediaTek Wireless_Device                                                            | 5         | 0.57%   |
| IMC Networks Bluetooth module                                                       | 5         | 0.57%   |
| Broadcom BCM2045 Bluetooth                                                          | 5         | 0.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1194      | 59.23%  |
| AMD                                          | 406       | 20.14%  |
| Nvidia                                       | 257       | 12.75%  |
| C-Media Electronics                          | 26        | 1.29%   |
| VIA Technologies                             | 15        | 0.74%   |
| Silicon Integrated Systems [SiS]             | 13        | 0.64%   |
| Creative Labs                                | 11        | 0.55%   |
| Logitech                                     | 10        | 0.5%    |
| GN Netcom                                    | 8         | 0.4%    |
| Texas Instruments                            | 7         | 0.35%   |
| ASUSTek Computer                             | 6         | 0.3%    |
| Razer USA                                    | 5         | 0.25%   |
| Zoran Co. Personal Media Division (Nogatech) | 4         | 0.2%    |
| Zhaoxin                                      | 4         | 0.2%    |
| XMOS                                         | 4         | 0.2%    |
| Plantronics                                  | 4         | 0.2%    |
| Generalplus Technology                       | 4         | 0.2%    |
| ULi Electronics                              | 3         | 0.15%   |
| Creative Technology                          | 3         | 0.15%   |
| Realtek Semiconductor                        | 2         | 0.1%    |
| Micro Star International                     | 2         | 0.1%    |
| JMTek                                        | 2         | 0.1%    |
| Jieli Technology                             | 2         | 0.1%    |
| Hewlett-Packard                              | 2         | 0.1%    |
| Focusrite-Novation                           | 2         | 0.1%    |
| Sony                                         | 1         | 0.05%   |
| Setek Elektronik                             | 1         | 0.05%   |
| QinHeng Electronics                          | 1         | 0.05%   |
| Nordic Semiconductor ASA                     | 1         | 0.05%   |
| MosArt Semiconductor                         | 1         | 0.05%   |
| Microsoft                                    | 1         | 0.05%   |
| KTMicro                                      | 1         | 0.05%   |
| KORG                                         | 1         | 0.05%   |
| Kingston Technology                          | 1         | 0.05%   |
| Guillemot                                    | 1         | 0.05%   |
| ESI                                          | 1         | 0.05%   |
| Ensoniq                                      | 1         | 0.05%   |
| Elitegroup Computer Systems (ECS)            | 1         | 0.05%   |
| Elgato Systems                               | 1         | 0.05%   |
| EGO SYStems                                  | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 132       | 5.53%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 122       | 5.11%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 106       | 4.44%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 94        | 3.94%   |
| AMD FCH Azalia Controller                                                                         | 86        | 3.6%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 82        | 3.43%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 80        | 3.35%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 77        | 3.22%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 76        | 3.18%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 64        | 2.68%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 59        | 2.47%   |
| AMD Kabini HDMI/DP Audio                                                                          | 54        | 2.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 48        | 2.01%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 47        | 1.97%   |
| Intel 8 Series HD Audio Controller                                                                | 46        | 1.93%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 45        | 1.88%   |
| Nvidia High Definition Audio Controller                                                           | 43        | 1.8%    |
| AMD Wrestler HDMI Audio                                                                           | 43        | 1.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 38        | 1.59%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 38        | 1.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 35        | 1.47%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 34        | 1.42%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 31        | 1.3%    |
| AMD High Definition Audio Controller                                                              | 30        | 1.26%   |
| Nvidia MCP61 High Definition Audio                                                                | 26        | 1.09%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 23        | 0.96%   |
| Intel Broadwell-U Audio Controller                                                                | 21        | 0.88%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 21        | 0.88%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 20        | 0.84%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 20        | 0.84%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 20        | 0.84%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 19        | 0.8%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 19        | 0.8%    |
| Intel Cannon Lake PCH cAVS                                                                        | 19        | 0.8%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 17        | 0.71%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 17        | 0.71%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 17        | 0.71%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 16        | 0.67%   |
| AMD Trinity HDMI Audio Controller                                                                 | 15        | 0.63%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 15        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 258       | 20.25%  |
| Unknown                      | 232       | 18.21%  |
| SK hynix                     | 220       | 17.27%  |
| Micron Technology            | 100       | 7.85%   |
| Kingston                     | 98        | 7.69%   |
| Crucial                      | 48        | 3.77%   |
| Unknown (ABCD)               | 40        | 3.14%   |
| Corsair                      | 36        | 2.83%   |
| A-DATA Technology            | 29        | 2.28%   |
| Nanya Technology             | 28        | 2.2%    |
| G.Skill                      | 24        | 1.88%   |
| Elpida                       | 24        | 1.88%   |
| Unknown                      | 20        | 1.57%   |
| Ramaxel Technology           | 15        | 1.18%   |
| Smart                        | 13        | 1.02%   |
| Transcend                    | 6         | 0.47%   |
| Teikon                       | 6         | 0.47%   |
| Patriot                      | 6         | 0.47%   |
| Team                         | 5         | 0.39%   |
| PNY                          | 5         | 0.39%   |
| Timetec                      | 4         | 0.31%   |
| Unifosa                      | 3         | 0.24%   |
| Qimonda                      | 3         | 0.24%   |
| KINGBANK                     | 3         | 0.24%   |
| High Bridge                  | 3         | 0.24%   |
| GOODRAM                      | 3         | 0.24%   |
| ASint Technology             | 3         | 0.24%   |
| Apacer                       | 3         | 0.24%   |
| Toshiba                      | 2         | 0.16%   |
| Smart Brazil                 | 2         | 0.16%   |
| PUSKILL                      | 2         | 0.16%   |
| fef5                         | 2         | 0.16%   |
| Avant                        | 2         | 0.16%   |
| Xi'an UniIC Semiconductors   | 1         | 0.08%   |
| Wilk                         | 1         | 0.08%   |
| Unknown (AB)                 | 1         | 0.08%   |
| Unknown (0xD306)             | 1         | 0.08%   |
| Unknown (0x4000000000000000) | 1         | 0.08%   |
| Unknown (07FB)               | 1         | 0.08%   |
| TakeMS                       | 1         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 28        | 2.04%   |
| Unknown                                                          | 20        | 1.45%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 1.09%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 14        | 1.02%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 13        | 0.95%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM DDR3 2400MT/s     | 12        | 0.87%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 12        | 0.87%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 12        | 0.87%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 11        | 0.8%    |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 10        | 0.73%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 10        | 0.73%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 10        | 0.73%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 9         | 0.65%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 8         | 0.58%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 8         | 0.58%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.51%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 7         | 0.51%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 6         | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 6         | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 6         | 0.44%   |
| Unknown RAM Module 1024MB SODIMM DRAM                            | 6         | 0.44%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 5         | 0.36%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 5         | 0.36%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s                    | 5         | 0.36%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.36%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 0.36%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.36%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.36%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 5         | 0.36%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 5         | 0.36%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.36%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 4         | 0.29%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 4         | 0.29%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 4         | 0.29%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 4         | 0.29%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 4         | 0.29%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                    | 4         | 0.29%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 4         | 0.29%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.29%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 4         | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 484       | 43.06%  |
| DDR4    | 273       | 24.29%  |
| DDR2    | 129       | 11.48%  |
| LPDDR4  | 71        | 6.32%   |
| SDRAM   | 59        | 5.25%   |
| Unknown | 40        | 3.56%   |
| DDR     | 21        | 1.87%   |
| LPDDR3  | 18        | 1.6%    |
| DRAM    | 13        | 1.16%   |
| LPDDR5  | 11        | 0.98%   |
| DDR5    | 5         | 0.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 713       | 64.64%  |
| DIMM         | 328       | 29.74%  |
| Row Of Chips | 51        | 4.62%   |
| Unknown      | 9         | 0.82%   |
| Chip         | 2         | 0.18%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 4096    | 382       | 30.61%  |
| 8192    | 315       | 25.24%  |
| 2048    | 299       | 23.96%  |
| 1024    | 118       | 9.46%   |
| 16384   | 80        | 6.41%   |
| 512     | 24        | 1.92%   |
| 32768   | 17        | 1.36%   |
| 256     | 6         | 0.48%   |
| 3072    | 2         | 0.16%   |
| 128     | 2         | 0.16%   |
| 65536   | 1         | 0.08%   |
| 12288   | 1         | 0.08%   |
| Unknown | 1         | 0.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 292       | 24.17%  |
| 1333    | 97        | 8.03%   |
| 3200    | 95        | 7.86%   |
| 2400    | 95        | 7.86%   |
| 2667    | 88        | 7.28%   |
| Unknown | 71        | 5.88%   |
| 667     | 66        | 5.46%   |
| 1334    | 57        | 4.72%   |
| 800     | 45        | 3.73%   |
| 2133    | 40        | 3.31%   |
| 1066    | 34        | 2.81%   |
| 1067    | 27        | 2.24%   |
| 533     | 25        | 2.07%   |
| 1867    | 19        | 1.57%   |
| 2048    | 18        | 1.49%   |
| 1866    | 16        | 1.32%   |
| 3266    | 12        | 0.99%   |
| 6400    | 10        | 0.83%   |
| 4267    | 10        | 0.83%   |
| 400     | 10        | 0.83%   |
| 3600    | 8         | 0.66%   |
| 4800    | 5         | 0.41%   |
| 4199    | 5         | 0.41%   |
| 3400    | 5         | 0.41%   |
| 975     | 5         | 0.41%   |
| 333     | 5         | 0.41%   |
| 3066    | 4         | 0.33%   |
| 266     | 4         | 0.33%   |
| 49926   | 3         | 0.25%   |
| 4000    | 3         | 0.25%   |
| 3933    | 3         | 0.25%   |
| 2666    | 3         | 0.25%   |
| 4266    | 2         | 0.17%   |
| 3733    | 2         | 0.17%   |
| 3000    | 2         | 0.17%   |
| 2933    | 2         | 0.17%   |
| 2733    | 2         | 0.17%   |
| 1800    | 2         | 0.17%   |
| 1639    | 2         | 0.17%   |
| 50410   | 1         | 0.08%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 10        | 27.78%  |
| Brother Industries    | 8         | 22.22%  |
| Samsung Electronics   | 6         | 16.67%  |
| Canon                 | 5         | 13.89%  |
| STMicroelectronics    | 2         | 5.56%   |
| Seiko Epson           | 2         | 5.56%   |
| Lexmark International | 2         | 5.56%   |
| Dymo-CoStar           | 1         | 2.78%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung SCX-4200 series                                   | 2         | 5.56%   |
| Brother DCP-7055W                                         | 2         | 5.56%   |
| STMicroelectronics USB Printer Port                       | 1         | 2.78%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 2.78%   |
| Seiko Epson TM-T20X                                       | 1         | 2.78%   |
| Seiko Epson L382 Series                                   | 1         | 2.78%   |
| Samsung Xerox Phaser 3117 Laser Printer                   | 1         | 2.78%   |
| Samsung SCX-3400 Series                                   | 1         | 2.78%   |
| Samsung ML-1640 Series Laser Printer                      | 1         | 2.78%   |
| Samsung M2020 Series                                      | 1         | 2.78%   |
| Lexmark International Z33 Printer                         | 1         | 2.78%   |
| Lexmark International MS617dn                             | 1         | 2.78%   |
| HP PSC 1500 series                                        | 1         | 2.78%   |
| HP OfficeJet 4650 series                                  | 1         | 2.78%   |
| HP LaserJet P2015 series                                  | 1         | 2.78%   |
| HP LaserJet P1102                                         | 1         | 2.78%   |
| HP LaserJet 1200                                          | 1         | 2.78%   |
| HP DeskJet D2460                                          | 1         | 2.78%   |
| HP DeskJet 6980 series                                    | 1         | 2.78%   |
| HP DeskJet 3630 series                                    | 1         | 2.78%   |
| HP Deskjet 3520 series                                    | 1         | 2.78%   |
| HP Deskjet 1050 J410                                      | 1         | 2.78%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                    | 1         | 2.78%   |
| Canon TS5100 series                                       | 1         | 2.78%   |
| Canon PIXMA MP250                                         | 1         | 2.78%   |
| Canon MF3110                                              | 1         | 2.78%   |
| Canon G7000 series                                        | 1         | 2.78%   |
| Canon CanoScan LiDE 300                                   | 1         | 2.78%   |
| Brother PTUSB Printing                                    | 1         | 2.78%   |
| Brother PT-2450DX                                         | 1         | 2.78%   |
| Brother Printer                                           | 1         | 2.78%   |
| Brother MFC-7340                                          | 1         | 2.78%   |
| Brother HL-L2380DW                                        | 1         | 2.78%   |
| Brother HL-2230 series                                    | 1         | 2.78%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 3         | 33.33%  |
| Canon           | 3         | 33.33%  |
| Seiko Epson     | 2         | 22.22%  |
| Mustek Systems  | 1         | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                 | 1         | 11.11%  |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 11.11%  |
| Mustek Systems ScanExpress A3 USB                             | 1         | 11.11%  |
| HP scanjet 8270                                               | 1         | 11.11%  |
| HP ScanJet 2400c                                              | 1         | 11.11%  |
| HP HP4470C                                                    | 1         | 11.11%  |
| Canon CanoScan LiDE 500F                                      | 1         | 11.11%  |
| Canon CanoScan LiDE 220                                       | 1         | 11.11%  |
| Canon CanoScan LiDE 200                                       | 1         | 11.11%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 250       | 25.23%  |
| Realtek Semiconductor                  | 81        | 8.17%   |
| IMC Networks                           | 67        | 6.76%   |
| Microdia                               | 63        | 6.36%   |
| Bison Electronics                      | 48        | 4.84%   |
| Suyin                                  | 46        | 4.64%   |
| Cheng Uei Precision Industry (Foxlink) | 43        | 4.34%   |
| Sunplus Innovation Technology          | 42        | 4.24%   |
| Quanta                                 | 40        | 4.04%   |
| Apple                                  | 39        | 3.94%   |
| Alcor Micro                            | 31        | 3.13%   |
| Silicon Motion                         | 30        | 3.03%   |
| Logitech                               | 22        | 2.22%   |
| Syntek                                 | 20        | 2.02%   |
| Lite-On Technology                     | 18        | 1.82%   |
| Acer                                   | 13        | 1.31%   |
| Lenovo                                 | 12        | 1.21%   |
| Ricoh                                  | 11        | 1.11%   |
| Luxvisions Innotech Limited            | 10        | 1.01%   |
| ALi                                    | 10        | 1.01%   |
| Microsoft                              | 8         | 0.81%   |
| icSpring                               | 8         | 0.81%   |
| GEMBIRD                                | 8         | 0.81%   |
| Z-Star Microelectronics                | 6         | 0.61%   |
| Importek                               | 6         | 0.61%   |
| Samsung Electronics                    | 5         | 0.5%    |
| Generalplus Technology                 | 5         | 0.5%    |
| SunplusIT                              | 4         | 0.4%    |
| OmniVision Technologies                | 4         | 0.4%    |
| Genesys Logic                          | 4         | 0.4%    |
| Y Media                                | 2         | 0.2%    |
| USB Camera CS                          | 2         | 0.2%    |
| Sunplus Technology                     | 2         | 0.2%    |
| Sonix Technology                       | 2         | 0.2%    |
| Shenzhen Kingcome Optoelectronic       | 2         | 0.2%    |
| LG Electronics                         | 2         | 0.2%    |
| KYE Systems (Mouse Systems)            | 2         | 0.2%    |
| ARC International                      | 2         | 0.2%    |
| WCM_USB                                | 1         | 0.1%    |
| WaveRider Communications               | 1         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 25        | 2.51%   |
| Realtek Integrated_Webcam_HD                            | 19        | 1.91%   |
| Alcor Micro USB 2.0 Camera                              | 18        | 1.81%   |
| Chicony HD Webcam                                       | 16        | 1.6%    |
| Chicony HP TrueVision HD                                | 13        | 1.3%    |
| Apple Built-in iSight                                   | 12        | 1.2%    |
| Sunplus HD WebCam                                       | 11        | 1.1%    |
| Chicony USB 2.0 Camera                                  | 11        | 1.1%    |
| Chicony EasyCamera                                      | 11        | 1.1%    |
| IMC Networks USB2.0 HD UVC WebCam                       | 10        | 1%      |
| Chicony TOSHIBA Web Camera - HD                         | 10        | 1%      |
| Chicony HP Webcam                                       | 10        | 1%      |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 10        | 1%      |
| Chicony HP TrueVision HD Camera                         | 9         | 0.9%    |
| Bison Lenovo EasyCamera                                 | 9         | 0.9%    |
| Bison Integrated Camera                                 | 9         | 0.9%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                      | 9         | 0.9%    |
| Apple FaceTime HD Camera                                | 9         | 0.9%    |
| icSpring camera                                         | 8         | 0.8%    |
| Chicony HP HD Webcam                                    | 8         | 0.8%    |
| Chicony 2.0M UVC Webcam / CNF7129                       | 8         | 0.8%    |
| Microdia Integrated_Webcam_HD                           | 7         | 0.7%    |
| Microdia 1.3 MPixel Integrated Webcam                   | 7         | 0.7%    |
| IMC Networks USB2.0 VGA UVC WebCam                      | 7         | 0.7%    |
| IMC Networks USB 2.0 UVC VGA WebCam                     | 7         | 0.7%    |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]       | 7         | 0.7%    |
| Chicony VGA Webcam                                      | 7         | 0.7%    |
| Bison EasyCamera                                        | 7         | 0.7%    |
| Realtek USB Camera                                      | 6         | 0.6%    |
| Realtek Integrated Webcam HD                            | 6         | 0.6%    |
| Quanta HP HD Camera                                     | 6         | 0.6%    |
| Logitech Webcam C270                                    | 6         | 0.6%    |
| Lite-On HP HD Camera                                    | 6         | 0.6%    |
| IMC Networks UVC VGA Webcam                             | 6         | 0.6%    |
| IMC Networks Integrated Webcam                          | 6         | 0.6%    |
| IMC Networks Integrated Camera                          | 6         | 0.6%    |
| ALi WebCam                                              | 6         | 0.6%    |
| Syntek Integrated Camera                                | 5         | 0.5%    |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 5         | 0.5%    |
| Suyin Acer CrystalEye Webcam                            | 5         | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 45        | 38.79%  |
| AuthenTec                  | 18        | 15.52%  |
| Upek                       | 12        | 10.34%  |
| Synaptics                  | 12        | 10.34%  |
| STMicroelectronics         | 10        | 8.62%   |
| Shenzhen Goodix Technology | 9         | 7.76%   |
| LighTuning Technology      | 4         | 3.45%   |
| Samsung Electronics        | 3         | 2.59%   |
| Elan Microelectronics      | 3         | 2.59%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                | 12        | 10.34%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 11        | 9.48%   |
| STMicroelectronics Fingerprint Reader                     | 10        | 8.62%   |
| AuthenTec AES2810                                         | 7         | 6.03%   |
| Shenzhen Goodix  Fingerprint Device                       | 6         | 5.17%   |
| Validity Sensors VFS471 Fingerprint Reader                | 5         | 4.31%   |
| Validity Sensors VFS451 Fingerprint Reader                | 5         | 4.31%   |
| AuthenTec AES2501 Fingerprint Sensor                      | 5         | 4.31%   |
| Validity Sensors VFS5011 Fingerprint Reader               | 4         | 3.45%   |
| Validity Sensors VFS 5011 fingerprint sensor              | 4         | 3.45%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor         | 3         | 2.59%   |
| Validity Sensors VFS491                                   | 3         | 2.59%   |
| Synaptics Fingerprint reader [HP G6]                      | 3         | 2.59%   |
| LighTuning EgisTec Touch Fingerprint Sensor               | 3         | 2.59%   |
| AuthenTec AES1600                                         | 3         | 2.59%   |
| Validity Sensors VFS300 Fingerprint Reader                | 2         | 1.72%   |
| Validity Sensors Fingerprint scanner                      | 2         | 1.72%   |
| Synaptics WBDI                                            | 2         | 1.72%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 2         | 1.72%   |
| Shenzhen Goodix FingerPrint                               | 2         | 1.72%   |
| Samsung Fingerprint Device                                | 2         | 1.72%   |
| Elan ELAN:Fingerprint                                     | 2         | 1.72%   |
| AuthenTec AES1660 Fingerprint Sensor                      | 2         | 1.72%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor         | 1         | 0.86%   |
| Validity Sensors VFS301 Fingerprint Reader                | 1         | 0.86%   |
| Validity Sensors VFS101 Fingerprint Reader                | 1         | 0.86%   |
| Validity Sensors VFS Fingerprint sensor                   | 1         | 0.86%   |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 0.86%   |
| Upek TCS5B Fingerprint sensor                             | 1         | 0.86%   |
| Synaptics UWP WBDI                                        | 1         | 0.86%   |
| Synaptics TouchPad                                        | 1         | 0.86%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 0.86%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 0.86%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 0.86%   |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 0.86%   |
| Samsung Fingerprint Sensor Device - 730B                  | 1         | 0.86%   |
| LighTuning Fingerprint Reader                             | 1         | 0.86%   |
| Elan WBF Fingerprint Sensor                               | 1         | 0.86%   |
| AuthenTec Fingerprint Sensor                              | 1         | 0.86%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 18        | 35.29%  |
| Alcor Micro           | 15        | 29.41%  |
| O2 Micro              | 9         | 17.65%  |
| CHERRY                | 3         | 5.88%   |
| Lenovo                | 2         | 3.92%   |
| Upek                  | 1         | 1.96%   |
| Realtek Semiconductor | 1         | 1.96%   |
| OmniKey               | 1         | 1.96%   |
| Gemalto (was Gemplus) | 1         | 1.96%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 14        | 27.45%  |
| Broadcom BCM5880 Secure Applications Processor                               | 8         | 15.69%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 6         | 11.76%  |
| Broadcom 5880                                                                | 5         | 9.8%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 7.84%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 5.88%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 3.92%   |
| CHERRY SmartCard Reader Keyboard KC 1000 SC                                  | 2         | 3.92%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 1.96%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 1.96%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 1.96%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 1.96%   |
| CHERRY SmartTerminal ST-2xxx                                                 | 1         | 1.96%   |
| Broadcom 58200                                                               | 1         | 1.96%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 1.96%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1311      | 74.28%  |
| 1     | 368       | 20.85%  |
| 2     | 72        | 4.08%   |
| 3     | 10        | 0.57%   |
| 4     | 4         | 0.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 167       | 30.76%  |
| Fingerprint reader       | 115       | 21.18%  |
| Net/wireless             | 65        | 11.97%  |
| Chipcard                 | 46        | 8.47%   |
| Bluetooth                | 29        | 5.34%   |
| Camera                   | 18        | 3.31%   |
| Multimedia controller    | 16        | 2.95%   |
| Communication controller | 16        | 2.95%   |
| Sound                    | 14        | 2.58%   |
| Modem                    | 13        | 2.39%   |
| Net/ethernet             | 11        | 2.03%   |
| Storage                  | 10        | 1.84%   |
| Unassigned class         | 7         | 1.29%   |
| Flash memory             | 5         | 0.92%   |
| Dvb card                 | 5         | 0.92%   |
| Network                  | 3         | 0.55%   |
| Card reader              | 2         | 0.37%   |
| Storage/raid             | 1         | 0.18%   |

