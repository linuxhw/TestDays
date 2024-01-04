Linux in Bulgaria - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Bulgaria.

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

Total: 1095

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | Legion Y740-17IRHg 81UJ     | [c106ff91a5](https://linux-hardware.org/?probe=c106ff91a5) | Jan 02, 2024 |
| Sony          | VGN-CS21Z_Q                 | [6c9140100e](https://linux-hardware.org/?probe=6c9140100e) | Dec 30, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [63af20b791](https://linux-hardware.org/?probe=63af20b791) | Dec 29, 2023 |
| Dell          | Precision 5560              | [3555a4c2fa](https://linux-hardware.org/?probe=3555a4c2fa) | Dec 29, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [87e63ff33e](https://linux-hardware.org/?probe=87e63ff33e) | Dec 27, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [2eb4d57b39](https://linux-hardware.org/?probe=2eb4d57b39) | Dec 27, 2023 |
| HP            | ZBook Firefly 14 inch G1... | [97e425d424](https://linux-hardware.org/?probe=97e425d424) | Dec 26, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [ec9fe6e527](https://linux-hardware.org/?probe=ec9fe6e527) | Dec 26, 2023 |
| Lenovo        | G570 20079                  | [148b2b7232](https://linux-hardware.org/?probe=148b2b7232) | Dec 25, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [845e586dba](https://linux-hardware.org/?probe=845e586dba) | Dec 17, 2023 |
| Lenovo        | G50-30 80G0                 | [f210e0dd64](https://linux-hardware.org/?probe=f210e0dd64) | Dec 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [7b209666a3](https://linux-hardware.org/?probe=7b209666a3) | Dec 16, 2023 |
| Lenovo        | G580 20150                  | [c6c8d22a8e](https://linux-hardware.org/?probe=c6c8d22a8e) | Dec 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [f18bd26311](https://linux-hardware.org/?probe=f18bd26311) | Dec 13, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [c71041fa59](https://linux-hardware.org/?probe=c71041fa59) | Dec 12, 2023 |
| HP            | EliteBook 830 G5            | [a4bdf16134](https://linux-hardware.org/?probe=a4bdf16134) | Dec 12, 2023 |
| HP            | ProBook 455 G7              | [1bec383138](https://linux-hardware.org/?probe=1bec383138) | Dec 11, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [11ae906f6f](https://linux-hardware.org/?probe=11ae906f6f) | Dec 11, 2023 |
| Dell          | Vostro 3400                 | [0841e29863](https://linux-hardware.org/?probe=0841e29863) | Dec 10, 2023 |
| HP            | EliteBook 830 G5            | [b2743fd826](https://linux-hardware.org/?probe=b2743fd826) | Dec 09, 2023 |
| Lenovo        | G500 20236                  | [3c17f8cde4](https://linux-hardware.org/?probe=3c17f8cde4) | Dec 08, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [7fdc3ff8fd](https://linux-hardware.org/?probe=7fdc3ff8fd) | Dec 08, 2023 |
| Lenovo        | 3000 G410                   | [439199aff4](https://linux-hardware.org/?probe=439199aff4) | Dec 04, 2023 |
| HP            | 255 G6 Notebook PC          | [ee58e73f03](https://linux-hardware.org/?probe=ee58e73f03) | Dec 04, 2023 |
| MSI           | Modern 14 B4MW              | [487fe9610f](https://linux-hardware.org/?probe=487fe9610f) | Nov 30, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [80e09b727b](https://linux-hardware.org/?probe=80e09b727b) | Nov 30, 2023 |
| HP            | EliteBook 8530p             | [d4dbee494a](https://linux-hardware.org/?probe=d4dbee494a) | Nov 29, 2023 |
| Lenovo        | ThinkPad T490 20N3S5DV0Y    | [c68289cf4c](https://linux-hardware.org/?probe=c68289cf4c) | Nov 26, 2023 |
| HP            | Pavilion dv5                | [de192ce8b7](https://linux-hardware.org/?probe=de192ce8b7) | Nov 26, 2023 |
| HP            | Pavilion dv5                | [51fc2d77fc](https://linux-hardware.org/?probe=51fc2d77fc) | Nov 26, 2023 |
| Lenovo        | G50-30 80G0                 | [e604b5ce78](https://linux-hardware.org/?probe=e604b5ce78) | Nov 25, 2023 |
| Lenovo        | IdeaPad Y500 20193          | [9a8395f2ac](https://linux-hardware.org/?probe=9a8395f2ac) | Nov 24, 2023 |
| Lenovo        | Unknown                     | [2ab4754aa8](https://linux-hardware.org/?probe=2ab4754aa8) | Nov 23, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | [6f740bc140](https://linux-hardware.org/?probe=6f740bc140) | Nov 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [9315424410](https://linux-hardware.org/?probe=9315424410) | Nov 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [5e92402cde](https://linux-hardware.org/?probe=5e92402cde) | Nov 21, 2023 |
| Acer          | Aspire 5750G                | [eb5f5d4b24](https://linux-hardware.org/?probe=eb5f5d4b24) | Nov 19, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [60a416739f](https://linux-hardware.org/?probe=60a416739f) | Nov 17, 2023 |
| Lenovo        | ThinkPad X270 20HMS76D02    | [7da50d5ad3](https://linux-hardware.org/?probe=7da50d5ad3) | Nov 17, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [c7b3d39644](https://linux-hardware.org/?probe=c7b3d39644) | Nov 17, 2023 |
| ASUSTek       | TUF Gaming FA506II_FA506... | [2e60a77926](https://linux-hardware.org/?probe=2e60a77926) | Nov 14, 2023 |
| Lenovo        | IdeaPad Y500 20193          | [de5f1aa77e](https://linux-hardware.org/?probe=de5f1aa77e) | Nov 11, 2023 |
| Apple         | MacBookPro6,2               | [c59084f5fe](https://linux-hardware.org/?probe=c59084f5fe) | Nov 09, 2023 |
| Apple         | MacBookPro6,2               | [0cdc1967cc](https://linux-hardware.org/?probe=0cdc1967cc) | Nov 09, 2023 |
| HP            | ProBook 455 G8 Notebook ... | [4a2561319d](https://linux-hardware.org/?probe=4a2561319d) | Nov 08, 2023 |
| Lenovo        | ThinkPad X230 23252EG       | [143a351fe0](https://linux-hardware.org/?probe=143a351fe0) | Nov 08, 2023 |
| Valve         | Jupiter                     | [03f6022593](https://linux-hardware.org/?probe=03f6022593) | Nov 07, 2023 |
| Lenovo        | ThinkPad T470 20HD0000BM    | [3e379ff6e8](https://linux-hardware.org/?probe=3e379ff6e8) | Nov 04, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [d2a9171090](https://linux-hardware.org/?probe=d2a9171090) | Nov 04, 2023 |
| Lenovo        | IdeaPad Y500 20193          | [f96f6e6127](https://linux-hardware.org/?probe=f96f6e6127) | Nov 03, 2023 |
| Lenovo        | ThinkPad L540 20AUS0YU00    | [16b302d74a](https://linux-hardware.org/?probe=16b302d74a) | Nov 02, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [c06d2e60fc](https://linux-hardware.org/?probe=c06d2e60fc) | Nov 01, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [09b312b58c](https://linux-hardware.org/?probe=09b312b58c) | Oct 30, 2023 |
| Acer          | Aspire 5810T                | [9b65c56faa](https://linux-hardware.org/?probe=9b65c56faa) | Oct 29, 2023 |
| Sony          | SVE1712V1EB                 | [3b8803286b](https://linux-hardware.org/?probe=3b8803286b) | Oct 25, 2023 |
| Sony          | SVE1712V1EB                 | [63963cbe04](https://linux-hardware.org/?probe=63963cbe04) | Oct 25, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [9c136d661d](https://linux-hardware.org/?probe=9c136d661d) | Oct 24, 2023 |
| Lenovo        | ThinkPad T430 2349B74       | [7f7998c326](https://linux-hardware.org/?probe=7f7998c326) | Oct 22, 2023 |
| Dell          | Latitude E5410              | [b1559718de](https://linux-hardware.org/?probe=b1559718de) | Oct 14, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | [5b0b094b32](https://linux-hardware.org/?probe=5b0b094b32) | Oct 14, 2023 |
| ASUSTek       | X542UQ                      | [ca22dfa5cd](https://linux-hardware.org/?probe=ca22dfa5cd) | Oct 14, 2023 |
| ASUSTek       | X542UQ                      | [b795b184d0](https://linux-hardware.org/?probe=b795b184d0) | Oct 14, 2023 |
| ASUSTek       | K73SV                       | [63341aa786](https://linux-hardware.org/?probe=63341aa786) | Oct 13, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [ec7aee0455](https://linux-hardware.org/?probe=ec7aee0455) | Oct 10, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [e06a9dcd7d](https://linux-hardware.org/?probe=e06a9dcd7d) | Oct 09, 2023 |
| Lenovo        | ThinkPad X200 7458Y28       | [ad9893f44c](https://linux-hardware.org/?probe=ad9893f44c) | Oct 09, 2023 |
| HP            | 635                         | [ef474a26d0](https://linux-hardware.org/?probe=ef474a26d0) | Oct 07, 2023 |
| Dell          | Vostro 15 3510              | [233fe08ffd](https://linux-hardware.org/?probe=233fe08ffd) | Oct 07, 2023 |
| ONDA          | V80 PLUS                    | [8651e33f83](https://linux-hardware.org/?probe=8651e33f83) | Oct 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [5584c834bc](https://linux-hardware.org/?probe=5584c834bc) | Oct 04, 2023 |
| HP            | 15                          | [254f7000e9](https://linux-hardware.org/?probe=254f7000e9) | Oct 02, 2023 |
| Lenovo        | ThinkPad W540 20BG001EUK    | [6d78bda800](https://linux-hardware.org/?probe=6d78bda800) | Oct 02, 2023 |
| HP            | 15                          | [a5814d048c](https://linux-hardware.org/?probe=a5814d048c) | Oct 02, 2023 |
| Acer          | Aspire A515-45              | [9e09848439](https://linux-hardware.org/?probe=9e09848439) | Oct 02, 2023 |
| Lenovo        | ThinkPad W540 20BG001EUK    | [55f747d352](https://linux-hardware.org/?probe=55f747d352) | Oct 01, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | [3b76e2cd65](https://linux-hardware.org/?probe=3b76e2cd65) | Sep 26, 2023 |
| Dell          | Precision 5510              | [34ddd03339](https://linux-hardware.org/?probe=34ddd03339) | Sep 25, 2023 |
| Toshiba       | Satellite A300              | [03aa0d1366](https://linux-hardware.org/?probe=03aa0d1366) | Sep 25, 2023 |
| Acer          | Nitro AN515-58              | [589716b973](https://linux-hardware.org/?probe=589716b973) | Sep 23, 2023 |
| Acer          | Extensa 5635ZG              | [925fed495b](https://linux-hardware.org/?probe=925fed495b) | Sep 21, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [08e8a9a1a7](https://linux-hardware.org/?probe=08e8a9a1a7) | Sep 14, 2023 |
| Acer          | Aspire 5735                 | [9d3ceb6624](https://linux-hardware.org/?probe=9d3ceb6624) | Sep 14, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [4ec1be4c03](https://linux-hardware.org/?probe=4ec1be4c03) | Sep 13, 2023 |
| Timi          | A30                         | [7e932a59a6](https://linux-hardware.org/?probe=7e932a59a6) | Sep 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [744362d446](https://linux-hardware.org/?probe=744362d446) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [82d4f51421](https://linux-hardware.org/?probe=82d4f51421) | Sep 12, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [ae29792d70](https://linux-hardware.org/?probe=ae29792d70) | Sep 11, 2023 |
| Dell          | Latitude 5431               | [41e4734fc7](https://linux-hardware.org/?probe=41e4734fc7) | Sep 09, 2023 |
| Dell          | Latitude 5431               | [b2d976a088](https://linux-hardware.org/?probe=b2d976a088) | Sep 08, 2023 |
| MSI           | Bravo 15 C7VF               | [72b288770a](https://linux-hardware.org/?probe=72b288770a) | Sep 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [34fb398b78](https://linux-hardware.org/?probe=34fb398b78) | Sep 06, 2023 |
| ASUSTek       | G551JM                      | [784e1f216e](https://linux-hardware.org/?probe=784e1f216e) | Sep 06, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [a17f1582d4](https://linux-hardware.org/?probe=a17f1582d4) | Sep 05, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | [ca342c2a7e](https://linux-hardware.org/?probe=ca342c2a7e) | Sep 05, 2023 |
| Lenovo        | ThinkPad T430 2349KQ3       | [287ea35176](https://linux-hardware.org/?probe=287ea35176) | Sep 05, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [245964564e](https://linux-hardware.org/?probe=245964564e) | Sep 04, 2023 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | [479e3b96b2](https://linux-hardware.org/?probe=479e3b96b2) | Sep 04, 2023 |
| ASUSTek       | K55VD                       | [3db7c113f4](https://linux-hardware.org/?probe=3db7c113f4) | Sep 01, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [ae4d140b96](https://linux-hardware.org/?probe=ae4d140b96) | Aug 31, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [6dc701c67d](https://linux-hardware.org/?probe=6dc701c67d) | Aug 29, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [f1b8efb723](https://linux-hardware.org/?probe=f1b8efb723) | Aug 29, 2023 |
| Dell          | Precision M4600             | [b7fca4d2f9](https://linux-hardware.org/?probe=b7fca4d2f9) | Aug 27, 2023 |
| Lenovo        | ThinkPad T530 2394D27       | [3dac98b5a5](https://linux-hardware.org/?probe=3dac98b5a5) | Aug 26, 2023 |
| Dell          | Studio 1747                 | [e1fe0ee217](https://linux-hardware.org/?probe=e1fe0ee217) | Aug 25, 2023 |
| MSI           | GL65 9SE                    | [aa162e5634](https://linux-hardware.org/?probe=aa162e5634) | Aug 22, 2023 |
| Acer          | Aspire 5755G                | [e1a9713e26](https://linux-hardware.org/?probe=e1a9713e26) | Aug 21, 2023 |
| Apple         | MacBookPro9,2               | [551dc38c00](https://linux-hardware.org/?probe=551dc38c00) | Aug 19, 2023 |
| Apple         | MacBookPro9,2               | [0bbf9ab6c2](https://linux-hardware.org/?probe=0bbf9ab6c2) | Aug 19, 2023 |
| Lenovo        | ThinkPad X395 20NL000HGE    | [3dacfd8a02](https://linux-hardware.org/?probe=3dacfd8a02) | Aug 16, 2023 |
| Dell          | Latitude E4300              | [7c153c96f5](https://linux-hardware.org/?probe=7c153c96f5) | Aug 15, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [30e2a20d37](https://linux-hardware.org/?probe=30e2a20d37) | Aug 15, 2023 |
| Dell          | Latitude E4300              | [ec4bac7b02](https://linux-hardware.org/?probe=ec4bac7b02) | Aug 14, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | [f8c24a1b02](https://linux-hardware.org/?probe=f8c24a1b02) | Aug 11, 2023 |
| Dell          | Precision M4600             | [f97367efac](https://linux-hardware.org/?probe=f97367efac) | Aug 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [89e3ef8e6c](https://linux-hardware.org/?probe=89e3ef8e6c) | Aug 10, 2023 |
| Dell          | Inspiron 15 3520            | [7723e84488](https://linux-hardware.org/?probe=7723e84488) | Aug 09, 2023 |
| Dell          | Latitude E4300              | [9ae3d19a62](https://linux-hardware.org/?probe=9ae3d19a62) | Aug 09, 2023 |
| Lenovo        | ThinkPad X220 4290W35       | [64db00247d](https://linux-hardware.org/?probe=64db00247d) | Aug 09, 2023 |
| Dell          | Vostro 1700                 | [009c767dae](https://linux-hardware.org/?probe=009c767dae) | Aug 07, 2023 |
| Dell          | Precision 7750              | [cebb7f5165](https://linux-hardware.org/?probe=cebb7f5165) | Aug 06, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [75c36d43c3](https://linux-hardware.org/?probe=75c36d43c3) | Aug 02, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 O... | [491aec1ea1](https://linux-hardware.org/?probe=491aec1ea1) | Aug 02, 2023 |
| HP            | ProBook 4530s               | [884d64edd7](https://linux-hardware.org/?probe=884d64edd7) | Jul 29, 2023 |
| HP            | EliteBook 845 14 inch G9... | [82a4cfcd9f](https://linux-hardware.org/?probe=82a4cfcd9f) | Jul 23, 2023 |
| TUXEDO        | Gemini Gen2                 | [94fe3784a3](https://linux-hardware.org/?probe=94fe3784a3) | Jul 22, 2023 |
| Acer          | Predator PT516-52s          | [957a1037ee](https://linux-hardware.org/?probe=957a1037ee) | Jul 22, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | [ca2f317f1a](https://linux-hardware.org/?probe=ca2f317f1a) | Jul 22, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | [9f14acd318](https://linux-hardware.org/?probe=9f14acd318) | Jul 22, 2023 |
| Acer          | Extensa 215-31              | [968f0d7741](https://linux-hardware.org/?probe=968f0d7741) | Jul 22, 2023 |
| Acer          | Extensa 215-31              | [e937f82e9d](https://linux-hardware.org/?probe=e937f82e9d) | Jul 22, 2023 |
| HP            | 635                         | [bb148a8b2b](https://linux-hardware.org/?probe=bb148a8b2b) | Jul 21, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [5224cc55eb](https://linux-hardware.org/?probe=5224cc55eb) | Jul 20, 2023 |
| HP            | ProBook 6570b               | [0a74371e23](https://linux-hardware.org/?probe=0a74371e23) | Jul 18, 2023 |
| Dell          | Inspiron 3551               | [543382ea16](https://linux-hardware.org/?probe=543382ea16) | Jul 16, 2023 |
| Dell          | Inspiron 3551               | [74050e892f](https://linux-hardware.org/?probe=74050e892f) | Jul 15, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [7ef2028b06](https://linux-hardware.org/?probe=7ef2028b06) | Jul 13, 2023 |
| Acer          | Aspire A515-52G             | [639eb4733c](https://linux-hardware.org/?probe=639eb4733c) | Jul 12, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | [e40458ffe3](https://linux-hardware.org/?probe=e40458ffe3) | Jul 12, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [8267a42a4f](https://linux-hardware.org/?probe=8267a42a4f) | Jul 11, 2023 |
| Dell          | G15 5511                    | [eebe5b09c0](https://linux-hardware.org/?probe=eebe5b09c0) | Jul 08, 2023 |
| HP            | Notebook                    | [19d38aa402](https://linux-hardware.org/?probe=19d38aa402) | Jul 05, 2023 |
| HP            | Notebook                    | [ac7ccc907b](https://linux-hardware.org/?probe=ac7ccc907b) | Jul 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [e6d6494e7a](https://linux-hardware.org/?probe=e6d6494e7a) | Jul 05, 2023 |
| Acer          | Aspire VN7-591G             | [356b066ca9](https://linux-hardware.org/?probe=356b066ca9) | Jun 24, 2023 |
| ASUSTek       | G551JM                      | [04f17cc1d0](https://linux-hardware.org/?probe=04f17cc1d0) | Jun 24, 2023 |
| Dell          | Latitude 3180               | [a9a4a63807](https://linux-hardware.org/?probe=a9a4a63807) | Jun 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [7de42486fb](https://linux-hardware.org/?probe=7de42486fb) | Jun 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [b61cc560f8](https://linux-hardware.org/?probe=b61cc560f8) | Jun 21, 2023 |
| Lenovo        | ThinkPad X230 2325CL7       | [7423b661e5](https://linux-hardware.org/?probe=7423b661e5) | Jun 20, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [d8d9101ef6](https://linux-hardware.org/?probe=d8d9101ef6) | Jun 19, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [3c0316ef92](https://linux-hardware.org/?probe=3c0316ef92) | Jun 18, 2023 |
| Lenovo        | ThinkPad X230 2325CL7       | [baadfc7e98](https://linux-hardware.org/?probe=baadfc7e98) | Jun 18, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [5c365e154b](https://linux-hardware.org/?probe=5c365e154b) | Jun 17, 2023 |
| Lenovo        | Unknown                     | [cd3733c1d5](https://linux-hardware.org/?probe=cd3733c1d5) | Jun 16, 2023 |
| Lenovo        | Unknown                     | [e80d3a47d8](https://linux-hardware.org/?probe=e80d3a47d8) | Jun 16, 2023 |
| Packard Be... | EasyNote TK87               | [eeb1bdc4d1](https://linux-hardware.org/?probe=eeb1bdc4d1) | Jun 15, 2023 |
| Packard Be... | EasyNote TK87               | [3ba89fb405](https://linux-hardware.org/?probe=3ba89fb405) | Jun 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [29085f8fb4](https://linux-hardware.org/?probe=29085f8fb4) | Jun 10, 2023 |
| Dell          | Vostro 3500                 | [3d694e1b9a](https://linux-hardware.org/?probe=3d694e1b9a) | Jun 09, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [6de4ea13fe](https://linux-hardware.org/?probe=6de4ea13fe) | Jun 08, 2023 |
| Dell          | Precision 7710              | [f1b57ded18](https://linux-hardware.org/?probe=f1b57ded18) | Jun 08, 2023 |
| Dell          | Latitude 3350               | [ef85473c50](https://linux-hardware.org/?probe=ef85473c50) | Jun 07, 2023 |
| Cube          | i16-L                       | [5e0bd26a26](https://linux-hardware.org/?probe=5e0bd26a26) | Jun 04, 2023 |
| HP            | Laptop 15-dw3xxx            | [a4854b177f](https://linux-hardware.org/?probe=a4854b177f) | Jun 01, 2023 |
| Lenovo        | ThinkPad T460 20FMS4LL00    | [7519448ca8](https://linux-hardware.org/?probe=7519448ca8) | May 30, 2023 |
| Dell          | Inspiron 7577               | [94e5a63c07](https://linux-hardware.org/?probe=94e5a63c07) | May 29, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [5dd56ed986](https://linux-hardware.org/?probe=5dd56ed986) | May 25, 2023 |
| Lenovo        | Unknown                     | [563922ce1c](https://linux-hardware.org/?probe=563922ce1c) | May 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [87bf7a95c8](https://linux-hardware.org/?probe=87bf7a95c8) | May 21, 2023 |
| Dell          | Inspiron 1501               | [d2fb2ddcce](https://linux-hardware.org/?probe=d2fb2ddcce) | May 20, 2023 |
| Dell          | Inspiron N5110              | [4280ce2bd4](https://linux-hardware.org/?probe=4280ce2bd4) | May 15, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [32fba9e487](https://linux-hardware.org/?probe=32fba9e487) | May 09, 2023 |
| Beelink       | BT3 PRO                     | [fb99607da3](https://linux-hardware.org/?probe=fb99607da3) | May 08, 2023 |
| Lenovo        | ThinkPad Edge E530 62723... | [61e998f782](https://linux-hardware.org/?probe=61e998f782) | May 05, 2023 |
| MSI           | Modern 15 A5M               | [d8b2bfb82c](https://linux-hardware.org/?probe=d8b2bfb82c) | May 03, 2023 |
| HP            | ZBook Firefly 15 inch G8... | [ea5b56dbca](https://linux-hardware.org/?probe=ea5b56dbca) | May 01, 2023 |
| HP            | ZBook Firefly 15 inch G8... | [e67706f385](https://linux-hardware.org/?probe=e67706f385) | May 01, 2023 |
| Acer          | Aspire A515-51G             | [388b693b6d](https://linux-hardware.org/?probe=388b693b6d) | May 01, 2023 |
| Dell          | Vostro 3500                 | [450682b3fc](https://linux-hardware.org/?probe=450682b3fc) | Apr 28, 2023 |
| Dell          | Latitude E4300              | [c61dbb5c53](https://linux-hardware.org/?probe=c61dbb5c53) | Apr 27, 2023 |
| Acer          | Aspire 5742G                | [a1391b4372](https://linux-hardware.org/?probe=a1391b4372) | Apr 27, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C8S... | [765b52074c](https://linux-hardware.org/?probe=765b52074c) | Apr 25, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C8S... | [9cd6c064cc](https://linux-hardware.org/?probe=9cd6c064cc) | Apr 25, 2023 |
| Acer          | Aspire 5742G                | [84679bc442](https://linux-hardware.org/?probe=84679bc442) | Apr 24, 2023 |
| Dell          | Latitude E4300              | [94773cc3da](https://linux-hardware.org/?probe=94773cc3da) | Apr 24, 2023 |
| Dell          | Latitude E4300              | [8bdf03bc75](https://linux-hardware.org/?probe=8bdf03bc75) | Apr 24, 2023 |
| HUAWEI        | KLVL-WXXW                   | [13b6b127e6](https://linux-hardware.org/?probe=13b6b127e6) | Apr 22, 2023 |
| HP            | ProBook 4540s               | [12ee30d786](https://linux-hardware.org/?probe=12ee30d786) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [7afa5cded3](https://linux-hardware.org/?probe=7afa5cded3) | Apr 18, 2023 |
| HP            | Pavilion g6                 | [3b0ab63643](https://linux-hardware.org/?probe=3b0ab63643) | Apr 17, 2023 |
| Valve         | Jupiter                     | [f05e3341d3](https://linux-hardware.org/?probe=f05e3341d3) | Apr 17, 2023 |
| HP            | EliteBook 845 14 inch G9... | [fd256ca124](https://linux-hardware.org/?probe=fd256ca124) | Apr 16, 2023 |
| Acer          | Aspire A515-57              | [16ce6e54e0](https://linux-hardware.org/?probe=16ce6e54e0) | Apr 12, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [87059322b0](https://linux-hardware.org/?probe=87059322b0) | Apr 11, 2023 |
| Gigabyte      | G5 KF                       | [5bd37d599e](https://linux-hardware.org/?probe=5bd37d599e) | Apr 09, 2023 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | [fc68164465](https://linux-hardware.org/?probe=fc68164465) | Apr 08, 2023 |
| Acer          | Aspire E5-575G              | [37194169cd](https://linux-hardware.org/?probe=37194169cd) | Apr 08, 2023 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | [1dcab8aee7](https://linux-hardware.org/?probe=1dcab8aee7) | Apr 08, 2023 |
| Dell          | Vostro 5620                 | [afdf8d46a2](https://linux-hardware.org/?probe=afdf8d46a2) | Apr 05, 2023 |
| HP            | Notebook                    | [935131a649](https://linux-hardware.org/?probe=935131a649) | Apr 04, 2023 |
| HP            | Notebook                    | [f35bee3b90](https://linux-hardware.org/?probe=f35bee3b90) | Apr 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [90b9eaf3fe](https://linux-hardware.org/?probe=90b9eaf3fe) | Apr 02, 2023 |
| Lenovo        | ThinkPad T410 2518P9G       | [4f74fa6cd2](https://linux-hardware.org/?probe=4f74fa6cd2) | Apr 01, 2023 |
| Acer          | Aspire A515-51G             | [efc8399ce9](https://linux-hardware.org/?probe=efc8399ce9) | Apr 01, 2023 |
| Lenovo        | ThinkPad qqqqS2E            | [88caf7c0d1](https://linux-hardware.org/?probe=88caf7c0d1) | Mar 28, 2023 |
| Lenovo        | ThinkPad T580 20LAS1KA0R    | [db00c2ed37](https://linux-hardware.org/?probe=db00c2ed37) | Mar 26, 2023 |
| Toshiba       | Satellite C850-140          | [6682022c49](https://linux-hardware.org/?probe=6682022c49) | Mar 24, 2023 |
| HP            | Pavilion g6                 | [abd4bb0963](https://linux-hardware.org/?probe=abd4bb0963) | Mar 21, 2023 |
| HP            | Pavilion g6                 | [4dcebf6a41](https://linux-hardware.org/?probe=4dcebf6a41) | Mar 21, 2023 |
| HP            | ProBook 6475b               | [1b7a5f385c](https://linux-hardware.org/?probe=1b7a5f385c) | Mar 18, 2023 |
| HP            | ProBook 6475b               | [0fd12da29b](https://linux-hardware.org/?probe=0fd12da29b) | Mar 18, 2023 |
| HP            | ProBook 6475b               | [701aca7f61](https://linux-hardware.org/?probe=701aca7f61) | Mar 18, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [2a6ded1018](https://linux-hardware.org/?probe=2a6ded1018) | Mar 18, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [91ae5652cc](https://linux-hardware.org/?probe=91ae5652cc) | Mar 18, 2023 |
| Toshiba       | Satellite C55-C             | [9d2c56bf69](https://linux-hardware.org/?probe=9d2c56bf69) | Mar 17, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [03123126d0](https://linux-hardware.org/?probe=03123126d0) | Mar 16, 2023 |
| HP            | 255 G6 Notebook PC          | [47df31e0fb](https://linux-hardware.org/?probe=47df31e0fb) | Mar 13, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [c14956dd2d](https://linux-hardware.org/?probe=c14956dd2d) | Mar 12, 2023 |
| Acer          | Aspire 5333                 | [214db069e4](https://linux-hardware.org/?probe=214db069e4) | Mar 11, 2023 |
| Lenovo        | ThinkPad qqqqS2E            | [65c2aab8aa](https://linux-hardware.org/?probe=65c2aab8aa) | Mar 11, 2023 |
| Lenovo        | ThinkPad qqqqS2E            | [e03e243c84](https://linux-hardware.org/?probe=e03e243c84) | Mar 11, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [96f4bd0a52](https://linux-hardware.org/?probe=96f4bd0a52) | Mar 10, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [969ab4279f](https://linux-hardware.org/?probe=969ab4279f) | Mar 10, 2023 |
| Lenovo        | Legion 5 15ARH7 82RE        | [99e2790846](https://linux-hardware.org/?probe=99e2790846) | Mar 10, 2023 |
| HP            | ProBook 6460b               | [4374107e07](https://linux-hardware.org/?probe=4374107e07) | Mar 10, 2023 |
| HP            | ProBook 6460b               | [7a01d6124d](https://linux-hardware.org/?probe=7a01d6124d) | Mar 10, 2023 |
| Dell          | Latitude E4300              | [3c777f1c07](https://linux-hardware.org/?probe=3c777f1c07) | Mar 10, 2023 |
| HP            | ProBook 6475b               | [be06cdc105](https://linux-hardware.org/?probe=be06cdc105) | Mar 09, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [42a0b7428f](https://linux-hardware.org/?probe=42a0b7428f) | Mar 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [daefae334b](https://linux-hardware.org/?probe=daefae334b) | Mar 04, 2023 |
| ASUSTek       | X580VD                      | [f4b107fbf3](https://linux-hardware.org/?probe=f4b107fbf3) | Mar 02, 2023 |
| Lenovo        | ThinkPad T440s 20ARS2T40... | [c068117b39](https://linux-hardware.org/?probe=c068117b39) | Mar 01, 2023 |
| Valve         | Jupiter                     | [df09052bac](https://linux-hardware.org/?probe=df09052bac) | Mar 01, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | [e56350a1c1](https://linux-hardware.org/?probe=e56350a1c1) | Feb 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [54e5bda708](https://linux-hardware.org/?probe=54e5bda708) | Feb 26, 2023 |
| HP            | Notebook                    | [ab0dddc914](https://linux-hardware.org/?probe=ab0dddc914) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [83af08dd1d](https://linux-hardware.org/?probe=83af08dd1d) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c5a45c78fc](https://linux-hardware.org/?probe=c5a45c78fc) | Feb 26, 2023 |
| Acer          | Nitro AN517-55              | [76e7c1c236](https://linux-hardware.org/?probe=76e7c1c236) | Feb 25, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | [4f7bbbdd28](https://linux-hardware.org/?probe=4f7bbbdd28) | Feb 24, 2023 |
| Google        | Astronaut                   | [71e8582f54](https://linux-hardware.org/?probe=71e8582f54) | Feb 22, 2023 |
| Google        | Astronaut                   | [4949e50dad](https://linux-hardware.org/?probe=4949e50dad) | Feb 22, 2023 |
| HP            | Notebook                    | [f6d3ba25ba](https://linux-hardware.org/?probe=f6d3ba25ba) | Feb 22, 2023 |
| Valve         | Jupiter                     | [74b6676de3](https://linux-hardware.org/?probe=74b6676de3) | Feb 19, 2023 |
| HP            | Notebook                    | [9fe647f9a1](https://linux-hardware.org/?probe=9fe647f9a1) | Feb 15, 2023 |
| HP            | Notebook                    | [c4516fb37a](https://linux-hardware.org/?probe=c4516fb37a) | Feb 15, 2023 |
| HP            | ProBook 6460b               | [5436445da0](https://linux-hardware.org/?probe=5436445da0) | Feb 13, 2023 |
| HP            | ProBook 6460b               | [ba14b45543](https://linux-hardware.org/?probe=ba14b45543) | Feb 13, 2023 |
| Valve         | Jupiter                     | [1df562d2d8](https://linux-hardware.org/?probe=1df562d2d8) | Feb 13, 2023 |
| Dell          | Precision M4700             | [6c3746d120](https://linux-hardware.org/?probe=6c3746d120) | Feb 12, 2023 |
| Dell          | Latitude E7470              | [9b58106fd6](https://linux-hardware.org/?probe=9b58106fd6) | Feb 12, 2023 |
| HP            | ProBook 450 G1              | [5afe7ebf87](https://linux-hardware.org/?probe=5afe7ebf87) | Feb 11, 2023 |
| Lenovo        | IdeaPad S12 20021,2959      | [7e8f09a90e](https://linux-hardware.org/?probe=7e8f09a90e) | Feb 07, 2023 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | [e55411b47c](https://linux-hardware.org/?probe=e55411b47c) | Feb 06, 2023 |
| Dell          | Precision M4700             | [c2075893d4](https://linux-hardware.org/?probe=c2075893d4) | Feb 05, 2023 |
| Dell          | Precision 5540              | [de6a1c523e](https://linux-hardware.org/?probe=de6a1c523e) | Jan 28, 2023 |
| HP            | ProBook 455 G1              | [eabdd1585c](https://linux-hardware.org/?probe=eabdd1585c) | Jan 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [303593899d](https://linux-hardware.org/?probe=303593899d) | Jan 26, 2023 |
| HP            | Pavilion g6                 | [c34bc63cb0](https://linux-hardware.org/?probe=c34bc63cb0) | Jan 24, 2023 |
| HP            | Pavilion g6                 | [a9a199e6f7](https://linux-hardware.org/?probe=a9a199e6f7) | Jan 24, 2023 |
| Dell          | Vostro 5620                 | [e70af512c8](https://linux-hardware.org/?probe=e70af512c8) | Jan 20, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [e7548596d1](https://linux-hardware.org/?probe=e7548596d1) | Jan 19, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [3967a4560b](https://linux-hardware.org/?probe=3967a4560b) | Jan 15, 2023 |
| Acer          | Aspire A315-59              | [ca332b4905](https://linux-hardware.org/?probe=ca332b4905) | Jan 13, 2023 |
| Lenovo        | Z50-75 80EC                 | [ac83d70d3f](https://linux-hardware.org/?probe=ac83d70d3f) | Jan 11, 2023 |
| HP            | Pavilion 15                 | [e60b327d4c](https://linux-hardware.org/?probe=e60b327d4c) | Jan 10, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [6aa615094c](https://linux-hardware.org/?probe=6aa615094c) | Jan 10, 2023 |
| Google        | Kled                        | [6380ae012e](https://linux-hardware.org/?probe=6380ae012e) | Jan 07, 2023 |
| Lenovo        | B50-30 20382                | [a03991ee08](https://linux-hardware.org/?probe=a03991ee08) | Jan 07, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [c19db82125](https://linux-hardware.org/?probe=c19db82125) | Jan 05, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [697abed1c0](https://linux-hardware.org/?probe=697abed1c0) | Jan 05, 2023 |
| System76      | Gazelle                     | [b603d1ecc7](https://linux-hardware.org/?probe=b603d1ecc7) | Jan 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [1872e26e1c](https://linux-hardware.org/?probe=1872e26e1c) | Jan 04, 2023 |
| Dell          | Precision M6400             | [8f1b979d06](https://linux-hardware.org/?probe=8f1b979d06) | Jan 03, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [be5212ebcc](https://linux-hardware.org/?probe=be5212ebcc) | Jan 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [3f1ca6740d](https://linux-hardware.org/?probe=3f1ca6740d) | Dec 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [c51bc128e2](https://linux-hardware.org/?probe=c51bc128e2) | Dec 30, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [c844147ffd](https://linux-hardware.org/?probe=c844147ffd) | Dec 28, 2022 |
| Valve         | Jupiter                     | [32b2d1e76f](https://linux-hardware.org/?probe=32b2d1e76f) | Dec 26, 2022 |
| Acer          | Aspire A515-47              | [0ec462e927](https://linux-hardware.org/?probe=0ec462e927) | Dec 21, 2022 |
| Dell          | Latitude E5410              | [969f85bfc3](https://linux-hardware.org/?probe=969f85bfc3) | Dec 21, 2022 |
| Dell          | Inspiron N5110              | [9e4f7a69c9](https://linux-hardware.org/?probe=9e4f7a69c9) | Dec 18, 2022 |
| Valve         | Jupiter                     | [a560caaec5](https://linux-hardware.org/?probe=a560caaec5) | Dec 17, 2022 |
| Acer          | AO756                       | [ebc4d7cfcb](https://linux-hardware.org/?probe=ebc4d7cfcb) | Dec 16, 2022 |
| Lenovo        | ThinkPad X200s 74695XG      | [9bc0315222](https://linux-hardware.org/?probe=9bc0315222) | Dec 14, 2022 |
| Dell          | Vostro 5620                 | [6987aeacd5](https://linux-hardware.org/?probe=6987aeacd5) | Dec 13, 2022 |
| Dell          | XPS 17 9700                 | [46c656a547](https://linux-hardware.org/?probe=46c656a547) | Dec 13, 2022 |
| Dell          | Precision 5510              | [f464385b16](https://linux-hardware.org/?probe=f464385b16) | Dec 13, 2022 |
| Dell          | Precision 5510              | [f4188b30c9](https://linux-hardware.org/?probe=f4188b30c9) | Dec 13, 2022 |
| Toshiba       | Satellite C55-C             | [777b365c04](https://linux-hardware.org/?probe=777b365c04) | Dec 12, 2022 |
| HP            | Compaq Presario CQ71        | [57ab22c9c2](https://linux-hardware.org/?probe=57ab22c9c2) | Dec 11, 2022 |
| HP            | Compaq Presario CQ71        | [b3f0bf2008](https://linux-hardware.org/?probe=b3f0bf2008) | Dec 11, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [ad09795330](https://linux-hardware.org/?probe=ad09795330) | Dec 09, 2022 |
| Acer          | Aspire ES1-731G             | [589cce31c8](https://linux-hardware.org/?probe=589cce31c8) | Dec 09, 2022 |
| Lenovo        | ThinkPad L590 20Q700AWBM    | [ff0997b72a](https://linux-hardware.org/?probe=ff0997b72a) | Dec 09, 2022 |
| HP            | ProBook 450 G0              | [01e7f95a23](https://linux-hardware.org/?probe=01e7f95a23) | Dec 07, 2022 |
| HP            | ProBook 450 G0              | [c3b6c86431](https://linux-hardware.org/?probe=c3b6c86431) | Dec 07, 2022 |
| Dell          | Vostro 5620                 | [50acc3b3b8](https://linux-hardware.org/?probe=50acc3b3b8) | Dec 04, 2022 |
| ASUSTek       | X541NA                      | [9da9a87b5b](https://linux-hardware.org/?probe=9da9a87b5b) | Dec 03, 2022 |
| Acer          | Aspire ES1-731G             | [06918f4cc5](https://linux-hardware.org/?probe=06918f4cc5) | Dec 03, 2022 |
| Dell          | Inspiron N7010              | [3e9458fd24](https://linux-hardware.org/?probe=3e9458fd24) | Dec 02, 2022 |
| Lenovo        | ThinkPad T480S 20L8SBTD0... | [2d4a014ef1](https://linux-hardware.org/?probe=2d4a014ef1) | Dec 01, 2022 |
| Lenovo        | ThinkPad T480S 20L8SBTD0... | [e1cec664eb](https://linux-hardware.org/?probe=e1cec664eb) | Dec 01, 2022 |
| Acer          | AO756                       | [c1ff6fe10c](https://linux-hardware.org/?probe=c1ff6fe10c) | Nov 29, 2022 |
| Acer          | AO756                       | [fa5c9df13a](https://linux-hardware.org/?probe=fa5c9df13a) | Nov 27, 2022 |
| Acer          | AO756                       | [d390d588fe](https://linux-hardware.org/?probe=d390d588fe) | Nov 27, 2022 |
| Acer          | Aspire 5349                 | [82be349d91](https://linux-hardware.org/?probe=82be349d91) | Nov 25, 2022 |
| Dell          | Latitude 5420               | [797ac58b69](https://linux-hardware.org/?probe=797ac58b69) | Nov 23, 2022 |
| HP            | ZBook Studio 15.6 inch G... | [07210e29c5](https://linux-hardware.org/?probe=07210e29c5) | Nov 21, 2022 |
| Dell          | Inspiron N7010              | [210dd0f9f5](https://linux-hardware.org/?probe=210dd0f9f5) | Nov 20, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [6c5f37f683](https://linux-hardware.org/?probe=6c5f37f683) | Nov 19, 2022 |
| Dell          | Vostro 15 5501              | [ea1dbc4f7c](https://linux-hardware.org/?probe=ea1dbc4f7c) | Nov 18, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [d053fe8efe](https://linux-hardware.org/?probe=d053fe8efe) | Nov 16, 2022 |
| Lenovo        | ThinkPad T440s 20ARS2T40... | [f77af97294](https://linux-hardware.org/?probe=f77af97294) | Nov 13, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [b995c794aa](https://linux-hardware.org/?probe=b995c794aa) | Nov 10, 2022 |
| Acer          | Predator PT516-52s          | [b8ebbe76e8](https://linux-hardware.org/?probe=b8ebbe76e8) | Nov 10, 2022 |
| Dell          | Vostro 5402                 | [cca85a282e](https://linux-hardware.org/?probe=cca85a282e) | Nov 09, 2022 |
| Dell          | Latitude E5420              | [c6264f1223](https://linux-hardware.org/?probe=c6264f1223) | Nov 08, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [b1a9ec43d4](https://linux-hardware.org/?probe=b1a9ec43d4) | Nov 07, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [f57f494508](https://linux-hardware.org/?probe=f57f494508) | Nov 06, 2022 |
| HP            | Laptop 15s-eq1xxx           | [b59f9dcf48](https://linux-hardware.org/?probe=b59f9dcf48) | Nov 05, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [832ebcb956](https://linux-hardware.org/?probe=832ebcb956) | Nov 03, 2022 |
| HP            | Laptop 15s-eq1xxx           | [4f5b04e8d9](https://linux-hardware.org/?probe=4f5b04e8d9) | Nov 03, 2022 |
| Dell          | Vostro 1310                 | [0ae18c6c3b](https://linux-hardware.org/?probe=0ae18c6c3b) | Nov 03, 2022 |
| HP            | EliteBook 2730p             | [79830976d8](https://linux-hardware.org/?probe=79830976d8) | Nov 02, 2022 |
| ASUSTek       | G74Sx                       | [4e69212184](https://linux-hardware.org/?probe=4e69212184) | Nov 01, 2022 |
| ASUSTek       | ProArt StudioBook W700GV... | [bf22c22bb4](https://linux-hardware.org/?probe=bf22c22bb4) | Oct 31, 2022 |
| HP            | ProBook 450 G6              | [1b3bb91776](https://linux-hardware.org/?probe=1b3bb91776) | Oct 29, 2022 |
| Acer          | Predator PT516-52s          | [c0cebe4cfe](https://linux-hardware.org/?probe=c0cebe4cfe) | Oct 27, 2022 |
| HP            | ProBook 450 G6              | [ced3daa1b6](https://linux-hardware.org/?probe=ced3daa1b6) | Oct 27, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [a09e3f3669](https://linux-hardware.org/?probe=a09e3f3669) | Oct 26, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [81231e9517](https://linux-hardware.org/?probe=81231e9517) | Oct 26, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | [79144ee806](https://linux-hardware.org/?probe=79144ee806) | Oct 25, 2022 |
| Acer          | Predator PT516-52s          | [ec8dac6fd3](https://linux-hardware.org/?probe=ec8dac6fd3) | Oct 22, 2022 |
| Acer          | Aspire 5830T                | [2423f8bf08](https://linux-hardware.org/?probe=2423f8bf08) | Oct 18, 2022 |
| Toshiba       | Satellite L775-125          | [fbe4f1922c](https://linux-hardware.org/?probe=fbe4f1922c) | Oct 18, 2022 |
| Lenovo        | Y50-70 20378                | [fa5c67a5b1](https://linux-hardware.org/?probe=fa5c67a5b1) | Oct 16, 2022 |
| Lenovo        | Y50-70 20378                | [a17c987ea8](https://linux-hardware.org/?probe=a17c987ea8) | Oct 16, 2022 |
| HP            | Laptop 15-da0xxx            | [d172225c0b](https://linux-hardware.org/?probe=d172225c0b) | Oct 08, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | [866d1ad750](https://linux-hardware.org/?probe=866d1ad750) | Oct 07, 2022 |
| ASUSTek       | R11CX                       | [fb6e1d3652](https://linux-hardware.org/?probe=fb6e1d3652) | Oct 03, 2022 |
| ASUSTek       | R11CX                       | [f0bc5f49a4](https://linux-hardware.org/?probe=f0bc5f49a4) | Oct 03, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [b1df3aa03f](https://linux-hardware.org/?probe=b1df3aa03f) | Sep 20, 2022 |
| HP            | ProBook 450 G1              | [b4b9ca9ae4](https://linux-hardware.org/?probe=b4b9ca9ae4) | Sep 17, 2022 |
| HP            | ProBook 450 G1              | [bb2c7c1b05](https://linux-hardware.org/?probe=bb2c7c1b05) | Sep 17, 2022 |
| HP            | ProBook 450 G1              | [a6082da5f7](https://linux-hardware.org/?probe=a6082da5f7) | Sep 17, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [7099830d0a](https://linux-hardware.org/?probe=7099830d0a) | Sep 16, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [1e9f44a3da](https://linux-hardware.org/?probe=1e9f44a3da) | Sep 14, 2022 |
| Dell          | Latitude 5521               | [cb134441f2](https://linux-hardware.org/?probe=cb134441f2) | Sep 13, 2022 |
| MSI           | Modern 15 A11M              | [bfc50a32ba](https://linux-hardware.org/?probe=bfc50a32ba) | Sep 12, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [e916989486](https://linux-hardware.org/?probe=e916989486) | Sep 11, 2022 |
| MSI           | Modern 15 A11M              | [931f4d2ca7](https://linux-hardware.org/?probe=931f4d2ca7) | Sep 11, 2022 |
| MSI           | Modern 15 A11M              | [4f1849370d](https://linux-hardware.org/?probe=4f1849370d) | Sep 10, 2022 |
| Lenovo        | G710 20252                  | [8afd29a71f](https://linux-hardware.org/?probe=8afd29a71f) | Sep 09, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [7479eb6186](https://linux-hardware.org/?probe=7479eb6186) | Sep 06, 2022 |
| Toshiba       | Satellite C50-B             | [00e103f0a0](https://linux-hardware.org/?probe=00e103f0a0) | Sep 05, 2022 |
| Toshiba       | Satellite C50-B             | [a7708366c2](https://linux-hardware.org/?probe=a7708366c2) | Sep 05, 2022 |
| Lenovo        | ThinkPad P52 20MAS07F04     | [fe662b0bd6](https://linux-hardware.org/?probe=fe662b0bd6) | Sep 03, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [68170e253f](https://linux-hardware.org/?probe=68170e253f) | Sep 01, 2022 |
| HP            | Pavilion Gaming Laptop      | [8382b4123e](https://linux-hardware.org/?probe=8382b4123e) | Aug 31, 2022 |
| Dell          | Latitude E5270              | [d61a2cd74a](https://linux-hardware.org/?probe=d61a2cd74a) | Aug 30, 2022 |
| Dell          | Inspiron N5010              | [3239a22fc0](https://linux-hardware.org/?probe=3239a22fc0) | Aug 28, 2022 |
| Dell          | Inspiron N5010              | [e4cdaf6b35](https://linux-hardware.org/?probe=e4cdaf6b35) | Aug 28, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [d056fbc982](https://linux-hardware.org/?probe=d056fbc982) | Aug 28, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [aa84c700c6](https://linux-hardware.org/?probe=aa84c700c6) | Aug 28, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [7f2e793766](https://linux-hardware.org/?probe=7f2e793766) | Aug 27, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [8aeb1b057b](https://linux-hardware.org/?probe=8aeb1b057b) | Aug 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f4d9682f50](https://linux-hardware.org/?probe=f4d9682f50) | Aug 27, 2022 |
| Acer          | Nitro AN515-45              | [98c26372c2](https://linux-hardware.org/?probe=98c26372c2) | Aug 23, 2022 |
| HP            | ProBook 640 G1              | [a69a02f102](https://linux-hardware.org/?probe=a69a02f102) | Aug 20, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | [bd4737dfcf](https://linux-hardware.org/?probe=bd4737dfcf) | Aug 18, 2022 |
| Lenovo        | Unknown                     | [d6a318092b](https://linux-hardware.org/?probe=d6a318092b) | Aug 16, 2022 |
| Lenovo        | Unknown                     | [a8af2e8de4](https://linux-hardware.org/?probe=a8af2e8de4) | Aug 16, 2022 |
| Toshiba       | PT10F                       | [08b7dc52a2](https://linux-hardware.org/?probe=08b7dc52a2) | Aug 12, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [a7cdb45aa6](https://linux-hardware.org/?probe=a7cdb45aa6) | Aug 12, 2022 |
| Apple         | MacBookPro16,4              | [7571d6d783](https://linux-hardware.org/?probe=7571d6d783) | Aug 09, 2022 |
| Lenovo        | Unknown                     | [4fe504845e](https://linux-hardware.org/?probe=4fe504845e) | Aug 07, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | [1449b21f55](https://linux-hardware.org/?probe=1449b21f55) | Jul 24, 2022 |
| ASUSTek       | K50IJ                       | [60af40882b](https://linux-hardware.org/?probe=60af40882b) | Jul 24, 2022 |
| HP            | EliteBook 850 G5            | [0ffa75c50b](https://linux-hardware.org/?probe=0ffa75c50b) | Jul 20, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | [3dddb3aac3](https://linux-hardware.org/?probe=3dddb3aac3) | Jul 20, 2022 |
| Lenovo        | ThinkPad T430 2349CV8       | [fac90d81d0](https://linux-hardware.org/?probe=fac90d81d0) | Jul 13, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [eb883a57f4](https://linux-hardware.org/?probe=eb883a57f4) | Jul 12, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [25c94a11f7](https://linux-hardware.org/?probe=25c94a11f7) | Jul 08, 2022 |
| Toshiba       | PORTEGE Z930                | [292aa38957](https://linux-hardware.org/?probe=292aa38957) | Jul 05, 2022 |
| Toshiba       | PORTEGE Z930                | [4df74c5b84](https://linux-hardware.org/?probe=4df74c5b84) | Jul 05, 2022 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | [5de569a33e](https://linux-hardware.org/?probe=5de569a33e) | Jun 29, 2022 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | [6542ea7dff](https://linux-hardware.org/?probe=6542ea7dff) | Jun 27, 2022 |
| Dell          | Inspiron 3580               | [dfab1b501e](https://linux-hardware.org/?probe=dfab1b501e) | Jun 26, 2022 |
| Dell          | Latitude E6520              | [3cbcb5e5d5](https://linux-hardware.org/?probe=3cbcb5e5d5) | Jun 26, 2022 |
| Acer          | TravelMate P214-53          | [d93da606dc](https://linux-hardware.org/?probe=d93da606dc) | Jun 26, 2022 |
| Dell          | Latitude E6520              | [e4aeec08da](https://linux-hardware.org/?probe=e4aeec08da) | Jun 25, 2022 |
| HUAWEI        | MACHC-WAX9                  | [00089c4dbe](https://linux-hardware.org/?probe=00089c4dbe) | Jun 25, 2022 |
| Acer          | Aspire 5736Z                | [868525a45e](https://linux-hardware.org/?probe=868525a45e) | Jun 25, 2022 |
| Acer          | Aspire 5736Z                | [ba78e0dde2](https://linux-hardware.org/?probe=ba78e0dde2) | Jun 24, 2022 |
| Dell          | Inspiron 3580               | [22c8672cea](https://linux-hardware.org/?probe=22c8672cea) | Jun 23, 2022 |
| Dell          | Inspiron 7577               | [673bd13d0a](https://linux-hardware.org/?probe=673bd13d0a) | Jun 23, 2022 |
| MSI           | Modern 15 A5M               | [b648b81eca](https://linux-hardware.org/?probe=b648b81eca) | Jun 23, 2022 |
| HP            | ProBook 450 G3              | [fd83a38364](https://linux-hardware.org/?probe=fd83a38364) | Jun 15, 2022 |
| HP            | ProBook 450 G0              | [34d266accd](https://linux-hardware.org/?probe=34d266accd) | Jun 12, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [e2efffbd81](https://linux-hardware.org/?probe=e2efffbd81) | Jun 07, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [c509b12c63](https://linux-hardware.org/?probe=c509b12c63) | Jun 07, 2022 |
| Acer          | Aspire A315-32              | [124288f4e9](https://linux-hardware.org/?probe=124288f4e9) | Jun 05, 2022 |
| HP            | ProBook 450 G0              | [b3399223ef](https://linux-hardware.org/?probe=b3399223ef) | Jun 03, 2022 |
| Dell          | Latitude 5490               | [630b63edff](https://linux-hardware.org/?probe=630b63edff) | Jun 02, 2022 |
| HP            | ProBook 450 G0              | [ac99467383](https://linux-hardware.org/?probe=ac99467383) | Jun 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [164d02e437](https://linux-hardware.org/?probe=164d02e437) | Jun 01, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [e0d6b45da8](https://linux-hardware.org/?probe=e0d6b45da8) | May 31, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [ce6b717155](https://linux-hardware.org/?probe=ce6b717155) | May 30, 2022 |
| HP            | ProBook 450 G0              | [0086280448](https://linux-hardware.org/?probe=0086280448) | May 28, 2022 |
| HP            | Compaq 6730s                | [4dabec8399](https://linux-hardware.org/?probe=4dabec8399) | May 26, 2022 |
| ASUSTek       | ROG Strix G512LU_G512LU     | [24b9b9fc85](https://linux-hardware.org/?probe=24b9b9fc85) | May 25, 2022 |
| ASUSTek       | ROG Strix G512LU_G512LU     | [7d581f520f](https://linux-hardware.org/?probe=7d581f520f) | May 25, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [6be38c26b4](https://linux-hardware.org/?probe=6be38c26b4) | May 25, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [86242183ee](https://linux-hardware.org/?probe=86242183ee) | May 24, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [c941dc302f](https://linux-hardware.org/?probe=c941dc302f) | May 23, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [596b029521](https://linux-hardware.org/?probe=596b029521) | May 21, 2022 |
| HP            | Compaq 6735s                | [bcd9db6031](https://linux-hardware.org/?probe=bcd9db6031) | May 20, 2022 |
| Lenovo        | ThinkPad qqqqS2E            | [7c8ef0ae32](https://linux-hardware.org/?probe=7c8ef0ae32) | May 18, 2022 |
| Dell          | XPS 15 9570                 | [7de7df5240](https://linux-hardware.org/?probe=7de7df5240) | May 15, 2022 |
| Acer          | Aspire E5-571               | [99976087b6](https://linux-hardware.org/?probe=99976087b6) | May 15, 2022 |
| Acer          | Aspire E5-571               | [8eff9fb0c8](https://linux-hardware.org/?probe=8eff9fb0c8) | May 15, 2022 |
| Toshiba       | Satellite L50-A-115         | [186b630cd2](https://linux-hardware.org/?probe=186b630cd2) | May 15, 2022 |
| Lenovo        | ThinkPad qqqqS2E            | [09912cea2f](https://linux-hardware.org/?probe=09912cea2f) | May 14, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e7fcde8001](https://linux-hardware.org/?probe=e7fcde8001) | May 14, 2022 |
| TUXEDO        | Pulse 14 Gen1               | [31d9027f23](https://linux-hardware.org/?probe=31d9027f23) | May 13, 2022 |
| Acer          | Aspire E5-571               | [1dcd852fff](https://linux-hardware.org/?probe=1dcd852fff) | May 12, 2022 |
| ASUSTek       | X540LJ                      | [74341c3077](https://linux-hardware.org/?probe=74341c3077) | May 05, 2022 |
| Lenovo        | ThinkPad T490 20N20009RI    | [5cdef8caad](https://linux-hardware.org/?probe=5cdef8caad) | May 04, 2022 |
| Lenovo        | G500 20236                  | [244ed30771](https://linux-hardware.org/?probe=244ed30771) | May 04, 2022 |
| Toshiba       | Satellite C650              | [58539bbf0a](https://linux-hardware.org/?probe=58539bbf0a) | Apr 29, 2022 |
| Razer         | Blade 15 Studio Edition ... | [563510a4b7](https://linux-hardware.org/?probe=563510a4b7) | Apr 28, 2022 |
| Lenovo        | B590 20206                  | [80befa3088](https://linux-hardware.org/?probe=80befa3088) | Apr 23, 2022 |
| ASUSTek       | K55VD                       | [8c2253380a](https://linux-hardware.org/?probe=8c2253380a) | Apr 23, 2022 |
| Lenovo        | ThinkPad T490 20N20009RI    | [3f5a56d826](https://linux-hardware.org/?probe=3f5a56d826) | Apr 22, 2022 |
| Lenovo        | ThinkPad E14 20RA002UBM     | [a888d6756a](https://linux-hardware.org/?probe=a888d6756a) | Apr 19, 2022 |
| Dell          | Precision M6800             | [46a37b9e8e](https://linux-hardware.org/?probe=46a37b9e8e) | Apr 16, 2022 |
| MSI           | Modern 15 A4M               | [a5837a7f35](https://linux-hardware.org/?probe=a5837a7f35) | Apr 11, 2022 |
| MSI           | Modern 15 A4M               | [085aa2eabf](https://linux-hardware.org/?probe=085aa2eabf) | Apr 10, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [a28b76d4ba](https://linux-hardware.org/?probe=a28b76d4ba) | Apr 04, 2022 |
| Acer          | Aspire A315-35              | [fc67b2d51e](https://linux-hardware.org/?probe=fc67b2d51e) | Apr 03, 2022 |
| Lenovo        | IdeaPad Y500 20193          | [8506a077af](https://linux-hardware.org/?probe=8506a077af) | Apr 02, 2022 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [071753c493](https://linux-hardware.org/?probe=071753c493) | Mar 31, 2022 |
| HP            | ProBook 455 G7              | [60fa1992d1](https://linux-hardware.org/?probe=60fa1992d1) | Mar 30, 2022 |
| Lenovo        | ThinkPad T61 7661WE7        | [30fce12920](https://linux-hardware.org/?probe=30fce12920) | Mar 27, 2022 |
| Toshiba       | Satellite C855-2G8          | [37b97513a6](https://linux-hardware.org/?probe=37b97513a6) | Mar 26, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [19fbf78cc0](https://linux-hardware.org/?probe=19fbf78cc0) | Mar 23, 2022 |
| HP            | Pavilion g6                 | [141b22c372](https://linux-hardware.org/?probe=141b22c372) | Mar 20, 2022 |
| Dell          | Precision M4600             | [deec5e6e2b](https://linux-hardware.org/?probe=deec5e6e2b) | Mar 16, 2022 |
| Dell          | Inspiron 7559               | [82005c3638](https://linux-hardware.org/?probe=82005c3638) | Mar 08, 2022 |
| Lenovo        | IdeaPad Y580                | [26ea7d1cff](https://linux-hardware.org/?probe=26ea7d1cff) | Mar 06, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [441febf3e4](https://linux-hardware.org/?probe=441febf3e4) | Mar 05, 2022 |
| HP            | Pavilion dv5000 (EZ535UA... | [1ce1458a5f](https://linux-hardware.org/?probe=1ce1458a5f) | Mar 05, 2022 |
| HP            | EliteBook 850 G5            | [bf630f003c](https://linux-hardware.org/?probe=bf630f003c) | Mar 04, 2022 |
| Lenovo        | ThinkPad T460 20FN003LUK    | [e604cd4180](https://linux-hardware.org/?probe=e604cd4180) | Mar 03, 2022 |
| HP            | ProBook 450 G2              | [50e3ff9809](https://linux-hardware.org/?probe=50e3ff9809) | Mar 03, 2022 |
| ASUSTek       | N551VW                      | [b7250e82a1](https://linux-hardware.org/?probe=b7250e82a1) | Feb 27, 2022 |
| Dell          | Inspiron 7577               | [660240eb93](https://linux-hardware.org/?probe=660240eb93) | Feb 22, 2022 |
| HP            | OMEN by Laptop 15-dh1xxx    | [fde67099dc](https://linux-hardware.org/?probe=fde67099dc) | Feb 20, 2022 |
| Dell          | Inspiron 1011               | [092837b70d](https://linux-hardware.org/?probe=092837b70d) | Feb 19, 2022 |
| HP            | 255 G2                      | [f4f4bcc310](https://linux-hardware.org/?probe=f4f4bcc310) | Feb 17, 2022 |
| HP            | 255 G2                      | [2eee7b6928](https://linux-hardware.org/?probe=2eee7b6928) | Feb 17, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [c38638517e](https://linux-hardware.org/?probe=c38638517e) | Feb 17, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [64b2c75dae](https://linux-hardware.org/?probe=64b2c75dae) | Feb 16, 2022 |
| HP            | Pavilion 15                 | [191168c7ae](https://linux-hardware.org/?probe=191168c7ae) | Feb 16, 2022 |
| Dell          | Latitude E6330              | [7346afde52](https://linux-hardware.org/?probe=7346afde52) | Feb 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [b12c01311a](https://linux-hardware.org/?probe=b12c01311a) | Feb 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1df0e30fbc](https://linux-hardware.org/?probe=1df0e30fbc) | Feb 13, 2022 |
| HP            | Pavilion dm1                | [577f05089d](https://linux-hardware.org/?probe=577f05089d) | Feb 13, 2022 |
| HP            | 250 G6 Notebook PC          | [a032ab36a8](https://linux-hardware.org/?probe=a032ab36a8) | Feb 12, 2022 |
| Lenovo        | ThinkPad X230 2325AJG       | [eccfa3a972](https://linux-hardware.org/?probe=eccfa3a972) | Feb 12, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [0ec31586a1](https://linux-hardware.org/?probe=0ec31586a1) | Feb 11, 2022 |
| HP            | Pavilion 15                 | [72991a7822](https://linux-hardware.org/?probe=72991a7822) | Feb 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [565e324069](https://linux-hardware.org/?probe=565e324069) | Feb 09, 2022 |
| HP            | EliteBook 8560p             | [f8a96f73d1](https://linux-hardware.org/?probe=f8a96f73d1) | Feb 09, 2022 |
| Toshiba       | Satellite A200              | [e4acc07d44](https://linux-hardware.org/?probe=e4acc07d44) | Feb 06, 2022 |
| Apple         | MacBookPro11,1              | [788939c01d](https://linux-hardware.org/?probe=788939c01d) | Feb 02, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [5d451a6858](https://linux-hardware.org/?probe=5d451a6858) | Jan 31, 2022 |
| Acer          | Aspire E1-531               | [4f7256df40](https://linux-hardware.org/?probe=4f7256df40) | Jan 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [ba372feee9](https://linux-hardware.org/?probe=ba372feee9) | Jan 30, 2022 |
| MSI           | GF63 Thin 10SCXR            | [c4a65986af](https://linux-hardware.org/?probe=c4a65986af) | Jan 29, 2022 |
| Dell          | Inspiron N5010              | [2d5857b9ff](https://linux-hardware.org/?probe=2d5857b9ff) | Jan 27, 2022 |
| Acer          | Aspire E5-575G              | [2c42aa1caf](https://linux-hardware.org/?probe=2c42aa1caf) | Jan 24, 2022 |
| Fujitsu       | LIFEBOOK S760               | [f2de9fb609](https://linux-hardware.org/?probe=f2de9fb609) | Jan 20, 2022 |
| Fujitsu       | LIFEBOOK S760               | [0fdf944115](https://linux-hardware.org/?probe=0fdf944115) | Jan 20, 2022 |
| Lenovo        | ThinkPad T460 20FN003LUK    | [71cab3efa8](https://linux-hardware.org/?probe=71cab3efa8) | Jan 18, 2022 |
| Dell          | Vostro 15 3510              | [83ddee52ce](https://linux-hardware.org/?probe=83ddee52ce) | Jan 14, 2022 |
| Lenovo        | Z50-70 20354                | [5cff653045](https://linux-hardware.org/?probe=5cff653045) | Jan 13, 2022 |
| HP            | Notebook                    | [3467478289](https://linux-hardware.org/?probe=3467478289) | Jan 13, 2022 |
| Dell          | Latitude E4300              | [0d0020f062](https://linux-hardware.org/?probe=0d0020f062) | Jan 12, 2022 |
| Lenovo        | G500 20236                  | [2e7bd2b772](https://linux-hardware.org/?probe=2e7bd2b772) | Jan 12, 2022 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [f891c69576](https://linux-hardware.org/?probe=f891c69576) | Jan 08, 2022 |
| MSI           | Modern 14 B4MW              | [881a1adf4c](https://linux-hardware.org/?probe=881a1adf4c) | Jan 07, 2022 |
| Dell          | Vostro 15 3510              | [8520c449b6](https://linux-hardware.org/?probe=8520c449b6) | Jan 06, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [ca928a7784](https://linux-hardware.org/?probe=ca928a7784) | Jan 06, 2022 |
| Lenovo        | ThinkPad X250 20CLS03Y00    | [64d6a48fd3](https://linux-hardware.org/?probe=64d6a48fd3) | Jan 06, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [6ae5ab676d](https://linux-hardware.org/?probe=6ae5ab676d) | Jan 03, 2022 |
| Packard Be... | EasyNote TK87               | [a551958cb8](https://linux-hardware.org/?probe=a551958cb8) | Jan 01, 2022 |
| Dell          | Inspiron 7520               | [28e0273758](https://linux-hardware.org/?probe=28e0273758) | Dec 31, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [7c11e2a10b](https://linux-hardware.org/?probe=7c11e2a10b) | Dec 30, 2021 |
| Acer          | Aspire 3820                 | [195bb81f89](https://linux-hardware.org/?probe=195bb81f89) | Dec 28, 2021 |
| Acer          | Aspire 3820                 | [149083ba5f](https://linux-hardware.org/?probe=149083ba5f) | Dec 28, 2021 |
| Dell          | Inspiron 5458               | [58bbd792ef](https://linux-hardware.org/?probe=58bbd792ef) | Dec 27, 2021 |
| Dell          | Venue 11 Pro 7130 vPro      | [c3cbdf9c8e](https://linux-hardware.org/?probe=c3cbdf9c8e) | Dec 26, 2021 |
| Dell          | Venue 11 Pro 7130 vPro      | [788a656eea](https://linux-hardware.org/?probe=788a656eea) | Dec 26, 2021 |
| Toshiba       | Satellite L50-B             | [7ee7295f4e](https://linux-hardware.org/?probe=7ee7295f4e) | Dec 26, 2021 |
| HP            | Compaq 6730b (NB021EA#AB... | [25fb717971](https://linux-hardware.org/?probe=25fb717971) | Dec 25, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [df0d434539](https://linux-hardware.org/?probe=df0d434539) | Dec 22, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [9724b1359d](https://linux-hardware.org/?probe=9724b1359d) | Dec 21, 2021 |
| Apple         | MacBookPro11,1              | [ae120235f1](https://linux-hardware.org/?probe=ae120235f1) | Dec 21, 2021 |
| Toshiba       | Equium A60                  | [206f662171](https://linux-hardware.org/?probe=206f662171) | Dec 20, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [183c18d8a8](https://linux-hardware.org/?probe=183c18d8a8) | Dec 19, 2021 |
| Dell          | Inspiron N5010              | [f67c56ba50](https://linux-hardware.org/?probe=f67c56ba50) | Dec 18, 2021 |
| Lenovo        | ThinkPad T420 4236A87       | [74cb9f00a2](https://linux-hardware.org/?probe=74cb9f00a2) | Dec 15, 2021 |
| HP            | ProBook 4540s               | [da7b06db3f](https://linux-hardware.org/?probe=da7b06db3f) | Dec 12, 2021 |
| HP            | 255 G8 Notebook PC          | [2f607ba3fb](https://linux-hardware.org/?probe=2f607ba3fb) | Dec 12, 2021 |
| HP            | 255 G8 Notebook PC          | [5ef3ccbbd8](https://linux-hardware.org/?probe=5ef3ccbbd8) | Dec 12, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [9e861e7f7d](https://linux-hardware.org/?probe=9e861e7f7d) | Dec 11, 2021 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [615e44dbe8](https://linux-hardware.org/?probe=615e44dbe8) | Dec 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6424339164](https://linux-hardware.org/?probe=6424339164) | Dec 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c62460798a](https://linux-hardware.org/?probe=c62460798a) | Dec 09, 2021 |
| Dell          | Vostro 1014                 | [d1be779708](https://linux-hardware.org/?probe=d1be779708) | Dec 08, 2021 |
| Dell          | Latitude 5520               | [4609e387e3](https://linux-hardware.org/?probe=4609e387e3) | Dec 07, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [5dde6ac6a6](https://linux-hardware.org/?probe=5dde6ac6a6) | Dec 05, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [b38dd7fc41](https://linux-hardware.org/?probe=b38dd7fc41) | Dec 04, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [efc98eab3c](https://linux-hardware.org/?probe=efc98eab3c) | Dec 04, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [8c0fabf18d](https://linux-hardware.org/?probe=8c0fabf18d) | Nov 30, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [693e2b3171](https://linux-hardware.org/?probe=693e2b3171) | Nov 30, 2021 |
| MSI           | Modern 14 B4MW              | [c5c0c4aca3](https://linux-hardware.org/?probe=c5c0c4aca3) | Nov 29, 2021 |
| HP            | EliteBook 820 G2            | [5774bcc229](https://linux-hardware.org/?probe=5774bcc229) | Nov 28, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [ee56bc0d39](https://linux-hardware.org/?probe=ee56bc0d39) | Nov 28, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [d140375a6d](https://linux-hardware.org/?probe=d140375a6d) | Nov 27, 2021 |
| Lenovo        | ThinkPad T450s 20BWS3MG0... | [06841abc04](https://linux-hardware.org/?probe=06841abc04) | Nov 27, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [f0dbaf192c](https://linux-hardware.org/?probe=f0dbaf192c) | Nov 25, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [0e34595bcc](https://linux-hardware.org/?probe=0e34595bcc) | Nov 24, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [e2de67ba78](https://linux-hardware.org/?probe=e2de67ba78) | Nov 23, 2021 |
| Lenovo        | ThinkPad L590 20Q700AWBM    | [de3fb571bb](https://linux-hardware.org/?probe=de3fb571bb) | Nov 20, 2021 |
| Dell          | Latitude E6430              | [16f005fd2b](https://linux-hardware.org/?probe=16f005fd2b) | Nov 13, 2021 |
| HP            | ProBook 450 G0              | [ad46c0b68f](https://linux-hardware.org/?probe=ad46c0b68f) | Nov 11, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [2aa779c174](https://linux-hardware.org/?probe=2aa779c174) | Nov 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [28df5fd3c6](https://linux-hardware.org/?probe=28df5fd3c6) | Nov 06, 2021 |
| Acer          | Aspire E5-571G              | [a6509cbba9](https://linux-hardware.org/?probe=a6509cbba9) | Nov 03, 2021 |
| Acer          | Aspire A315-35              | [4ac11dfcbe](https://linux-hardware.org/?probe=4ac11dfcbe) | Nov 03, 2021 |
| Acer          | Aspire E5-571G              | [1c57a8d14c](https://linux-hardware.org/?probe=1c57a8d14c) | Nov 02, 2021 |
| Acer          | Aspire VX5-591G             | [66255ca7b5](https://linux-hardware.org/?probe=66255ca7b5) | Oct 30, 2021 |
| ASUSTek       | N551VW                      | [5d4bce82bd](https://linux-hardware.org/?probe=5d4bce82bd) | Oct 30, 2021 |
| Fujitsu Si... | ESPRIMO Mobile M9410        | [2cec9ef3cc](https://linux-hardware.org/?probe=2cec9ef3cc) | Oct 27, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [a92566ee89](https://linux-hardware.org/?probe=a92566ee89) | Oct 18, 2021 |
| Dell          | Latitude E5430 non-vPro     | [6d4dad5754](https://linux-hardware.org/?probe=6d4dad5754) | Oct 18, 2021 |
| Dell          | Latitude E5430 non-vPro     | [82c79fb7be](https://linux-hardware.org/?probe=82c79fb7be) | Oct 18, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [696a85e281](https://linux-hardware.org/?probe=696a85e281) | Oct 18, 2021 |
| HP            | EliteBook 8460p             | [8430d409b5](https://linux-hardware.org/?probe=8430d409b5) | Oct 11, 2021 |
| HP            | Pavilion dv7                | [dfccb89900](https://linux-hardware.org/?probe=dfccb89900) | Oct 09, 2021 |
| Acer          | Aspire A515-52G             | [bb5c8d6628](https://linux-hardware.org/?probe=bb5c8d6628) | Oct 01, 2021 |
| HP            | Laptop 15-bw0xx             | [642e96374e](https://linux-hardware.org/?probe=642e96374e) | Oct 01, 2021 |
| HP            | EliteBook 8440p             | [6b1e235a76](https://linux-hardware.org/?probe=6b1e235a76) | Sep 28, 2021 |
| Acer          | Extensa 5630                | [3bb0bc9c4d](https://linux-hardware.org/?probe=3bb0bc9c4d) | Sep 25, 2021 |
| HP            | EliteBook 850 G5            | [b6a9870be5](https://linux-hardware.org/?probe=b6a9870be5) | Sep 22, 2021 |
| Lenovo        | IdeaPad Creator 5 16ACH6... | [7251798837](https://linux-hardware.org/?probe=7251798837) | Sep 20, 2021 |
| MSI           | GF63 Thin 10SCSR            | [b4b1c2d06c](https://linux-hardware.org/?probe=b4b1c2d06c) | Sep 19, 2021 |
| HP            | Pavilion 17                 | [e6cd50fc3c](https://linux-hardware.org/?probe=e6cd50fc3c) | Sep 19, 2021 |
| HP            | Pavilion 17                 | [7854f1ed77](https://linux-hardware.org/?probe=7854f1ed77) | Sep 18, 2021 |
| MSI           | Modern 15 A4M               | [1b2e6b06a0](https://linux-hardware.org/?probe=1b2e6b06a0) | Sep 14, 2021 |
| MSI           | Modern 15 A4M               | [dabdf47bdf](https://linux-hardware.org/?probe=dabdf47bdf) | Sep 13, 2021 |
| Lenovo        | IdeaPad S540-13IML 81XA     | [59ce224e2b](https://linux-hardware.org/?probe=59ce224e2b) | Sep 10, 2021 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [dce0b57cdc](https://linux-hardware.org/?probe=dce0b57cdc) | Sep 09, 2021 |
| HP            | EliteBook 850 G2            | [8a29546070](https://linux-hardware.org/?probe=8a29546070) | Sep 09, 2021 |
| HP            | 250 G2                      | [64f9cfdbab](https://linux-hardware.org/?probe=64f9cfdbab) | Sep 09, 2021 |
| HP            | 250 G2                      | [4fb0a2eab3](https://linux-hardware.org/?probe=4fb0a2eab3) | Sep 09, 2021 |
| MSI           | Modern 14 B4MW              | [d54f16f7e3](https://linux-hardware.org/?probe=d54f16f7e3) | Sep 07, 2021 |
| Lenovo        | ThinkPad T540p 20BE0084B... | [45914d6e06](https://linux-hardware.org/?probe=45914d6e06) | Sep 04, 2021 |
| Lenovo        | Yoga 2 11 20428             | [52474e968d](https://linux-hardware.org/?probe=52474e968d) | Sep 01, 2021 |
| Lenovo        | Yoga 2 11 20428             | [c4e6145a5f](https://linux-hardware.org/?probe=c4e6145a5f) | Sep 01, 2021 |
| Toshiba       | Satellite A200              | [9300181bad](https://linux-hardware.org/?probe=9300181bad) | Aug 31, 2021 |
| Toshiba       | Satellite A200              | [ce4010bf4f](https://linux-hardware.org/?probe=ce4010bf4f) | Aug 31, 2021 |
| Toshiba       | Satellite A200              | [afa0ef75a7](https://linux-hardware.org/?probe=afa0ef75a7) | Aug 31, 2021 |
| Toshiba       | Satellite A200              | [2f2e0ec5bf](https://linux-hardware.org/?probe=2f2e0ec5bf) | Aug 31, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [2199b6e642](https://linux-hardware.org/?probe=2199b6e642) | Aug 25, 2021 |
| Lenovo        | IdeaPad Y500 20193          | [5b2d90a434](https://linux-hardware.org/?probe=5b2d90a434) | Aug 21, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [1df5582ca4](https://linux-hardware.org/?probe=1df5582ca4) | Aug 21, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [7b393c5790](https://linux-hardware.org/?probe=7b393c5790) | Aug 21, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [394c99adc8](https://linux-hardware.org/?probe=394c99adc8) | Aug 19, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [8461b48819](https://linux-hardware.org/?probe=8461b48819) | Aug 19, 2021 |
| HP            | EliteBook 850 G5            | [b106b91bcb](https://linux-hardware.org/?probe=b106b91bcb) | Aug 10, 2021 |
| Lenovo        | ThinkPad T420 4236A87       | [2553632d5d](https://linux-hardware.org/?probe=2553632d5d) | Aug 09, 2021 |
| Lenovo        | ThinkPad T420 4236A87       | [c77c7b6360](https://linux-hardware.org/?probe=c77c7b6360) | Aug 09, 2021 |
| MSI           | Modern 14 B4MW              | [76a1354974](https://linux-hardware.org/?probe=76a1354974) | Aug 06, 2021 |
| MSI           | Modern 14 B4MW              | [a06e67aa18](https://linux-hardware.org/?probe=a06e67aa18) | Aug 04, 2021 |
| MSI           | Modern 14 B4MW              | [42266d54c2](https://linux-hardware.org/?probe=42266d54c2) | Aug 02, 2021 |
| Dell          | Inspiron 3521               | [d4bc0c2e33](https://linux-hardware.org/?probe=d4bc0c2e33) | Jul 30, 2021 |
| AMI           | Cherry Trail CR             | [f015614a5c](https://linux-hardware.org/?probe=f015614a5c) | Jul 27, 2021 |
| AMI           | Cherry Trail CR             | [93b4e5b92a](https://linux-hardware.org/?probe=93b4e5b92a) | Jul 26, 2021 |
| HP            | ProBook 6450b               | [95ce6f4407](https://linux-hardware.org/?probe=95ce6f4407) | Jul 26, 2021 |
| HP            | ProBook 6450b               | [79d6b91845](https://linux-hardware.org/?probe=79d6b91845) | Jul 26, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e30dac258e](https://linux-hardware.org/?probe=e30dac258e) | Jul 26, 2021 |
| Acer          | Aspire A717-72G             | [1d1f8cb836](https://linux-hardware.org/?probe=1d1f8cb836) | Jul 25, 2021 |
| Lenovo        | G50-80 80E5                 | [4c5e0baffe](https://linux-hardware.org/?probe=4c5e0baffe) | Jul 25, 2021 |
| HP            | ProBook 6450b               | [557056dd22](https://linux-hardware.org/?probe=557056dd22) | Jul 24, 2021 |
| AMI           | Cherry Trail CR             | [6c5a4659b1](https://linux-hardware.org/?probe=6c5a4659b1) | Jul 23, 2021 |
| HP            | ProBook 650 G1              | [67512f199f](https://linux-hardware.org/?probe=67512f199f) | Jul 23, 2021 |
| AMI           | Cherry Trail CR             | [712382158a](https://linux-hardware.org/?probe=712382158a) | Jul 23, 2021 |
| Lenovo        | V15-ADA 82C7                | [6e77984276](https://linux-hardware.org/?probe=6e77984276) | Jul 20, 2021 |
| Acer          | Aspire V3-571G              | [a26a16fb20](https://linux-hardware.org/?probe=a26a16fb20) | Jul 16, 2021 |
| Dell          | Latitude 12 Rugged Extre... | [c18e377104](https://linux-hardware.org/?probe=c18e377104) | Jul 16, 2021 |
| Dell          | Latitude 12 Rugged Extre... | [baf3a7a407](https://linux-hardware.org/?probe=baf3a7a407) | Jul 16, 2021 |
| HP            | ProBook 6450b               | [f596a27975](https://linux-hardware.org/?probe=f596a27975) | Jul 16, 2021 |
| Acer          | Predator G9-792             | [e0f2c7b0c5](https://linux-hardware.org/?probe=e0f2c7b0c5) | Jul 12, 2021 |
| HP            | ProBook 6450b               | [d9d8115d98](https://linux-hardware.org/?probe=d9d8115d98) | Jul 11, 2021 |
| HP            | ProBook 6450b               | [c3bdfd8206](https://linux-hardware.org/?probe=c3bdfd8206) | Jul 11, 2021 |
| HP            | EliteBook 8540p             | [720242bd55](https://linux-hardware.org/?probe=720242bd55) | Jul 11, 2021 |
| HP            | EliteBook 8540p             | [0005eb3569](https://linux-hardware.org/?probe=0005eb3569) | Jul 11, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [ba7afba1a6](https://linux-hardware.org/?probe=ba7afba1a6) | Jul 08, 2021 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [47bac68af2](https://linux-hardware.org/?probe=47bac68af2) | Jul 06, 2021 |
| Lenovo        | ThinkPad P52 20MAS07F04     | [4d35b037dd](https://linux-hardware.org/?probe=4d35b037dd) | Jul 04, 2021 |
| Lenovo        | ThinkPad X240 20AMS3460B    | [d3b33778bb](https://linux-hardware.org/?probe=d3b33778bb) | Jul 01, 2021 |
| Lenovo        | ThinkPad X240 20AMS3460B    | [3c45c3cf29](https://linux-hardware.org/?probe=3c45c3cf29) | Jul 01, 2021 |
| Dell          | Latitude 5410               | [9b8e7a4fc4](https://linux-hardware.org/?probe=9b8e7a4fc4) | Jun 25, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [614eb34061](https://linux-hardware.org/?probe=614eb34061) | Jun 24, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [9b92db3a47](https://linux-hardware.org/?probe=9b92db3a47) | Jun 24, 2021 |
| Acer          | Aspire VN7-592G             | [2b00566646](https://linux-hardware.org/?probe=2b00566646) | Jun 23, 2021 |
| MSI           | MS-N033                     | [3ba725911d](https://linux-hardware.org/?probe=3ba725911d) | Jun 22, 2021 |
| MSI           | MS-N033                     | [db865cd4b0](https://linux-hardware.org/?probe=db865cd4b0) | Jun 22, 2021 |
| Acer          | Extensa 5630                | [a56495c8ee](https://linux-hardware.org/?probe=a56495c8ee) | Jun 19, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [ddbd903ae7](https://linux-hardware.org/?probe=ddbd903ae7) | Jun 11, 2021 |
| Dell          | Studio 1747                 | [b612af8225](https://linux-hardware.org/?probe=b612af8225) | Jun 06, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [505b82b2de](https://linux-hardware.org/?probe=505b82b2de) | Jun 06, 2021 |
| HP            | Pavilion dv5                | [94cfdbc88f](https://linux-hardware.org/?probe=94cfdbc88f) | Jun 03, 2021 |
| Dell          | Latitude 5500               | [4eb777675a](https://linux-hardware.org/?probe=4eb777675a) | Jun 03, 2021 |
| ASUSTek       | TP300LA                     | [1c4ff3ec3c](https://linux-hardware.org/?probe=1c4ff3ec3c) | Jun 02, 2021 |
| ASUSTek       | TP300LA                     | [aa03d405bc](https://linux-hardware.org/?probe=aa03d405bc) | May 31, 2021 |
| Lenovo        | ThinkPad X220 4291IR6       | [660a6b9e20](https://linux-hardware.org/?probe=660a6b9e20) | May 26, 2021 |
| HP            | ProBook 4540s               | [d0705ef193](https://linux-hardware.org/?probe=d0705ef193) | May 23, 2021 |
| HP            | ProBook 4540s               | [08209a81e4](https://linux-hardware.org/?probe=08209a81e4) | May 23, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | [eccabc11a1](https://linux-hardware.org/?probe=eccabc11a1) | May 21, 2021 |
| Apple         | MacBookAir7,2               | [2fd0c6a88a](https://linux-hardware.org/?probe=2fd0c6a88a) | May 21, 2021 |
| ASUSTek       | GL553VE                     | [c6ddc776ea](https://linux-hardware.org/?probe=c6ddc776ea) | May 18, 2021 |
| Dell          | Studio 1535                 | [90762831e7](https://linux-hardware.org/?probe=90762831e7) | May 17, 2021 |
| Dell          | Studio 1535                 | [9d034e29dc](https://linux-hardware.org/?probe=9d034e29dc) | May 16, 2021 |
| Lenovo        | ThinkPad X220 4291IR6       | [8dac91acc9](https://linux-hardware.org/?probe=8dac91acc9) | May 16, 2021 |
| HP            | EliteBook 8460p             | [133c3509a5](https://linux-hardware.org/?probe=133c3509a5) | May 13, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [75b2ef5126](https://linux-hardware.org/?probe=75b2ef5126) | May 13, 2021 |
| Lenovo        | ThinkPad L450 20DSS00N18    | [85f3722d36](https://linux-hardware.org/?probe=85f3722d36) | May 12, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [734a4fbc56](https://linux-hardware.org/?probe=734a4fbc56) | May 09, 2021 |
| Lenovo        | ThinkPad T61 765912G        | [998d8e53db](https://linux-hardware.org/?probe=998d8e53db) | May 07, 2021 |
| HP            | EliteBook 8460p             | [67bde80034](https://linux-hardware.org/?probe=67bde80034) | May 04, 2021 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [7065f7bb74](https://linux-hardware.org/?probe=7065f7bb74) | May 02, 2021 |
| Acer          | Swift SF114-33              | [59d8b5d3fe](https://linux-hardware.org/?probe=59d8b5d3fe) | May 02, 2021 |
| HP            | Pavilion dv5                | [f75415bbd7](https://linux-hardware.org/?probe=f75415bbd7) | May 01, 2021 |
| HP            | EliteBook 850 G5            | [3b2545921f](https://linux-hardware.org/?probe=3b2545921f) | Apr 29, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [37b746015a](https://linux-hardware.org/?probe=37b746015a) | Apr 28, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [03b6a0117c](https://linux-hardware.org/?probe=03b6a0117c) | Apr 26, 2021 |
| HP            | Notebook                    | [3cc10cc5f1](https://linux-hardware.org/?probe=3cc10cc5f1) | Apr 24, 2021 |
| Lenovo        | ThinkPad X230 232425U       | [69e5ab7b60](https://linux-hardware.org/?probe=69e5ab7b60) | Apr 24, 2021 |
| Dell          | Vostro 3580                 | [8123f6484e](https://linux-hardware.org/?probe=8123f6484e) | Apr 18, 2021 |
| ASUSTek       | K52Je                       | [fb1ce94b02](https://linux-hardware.org/?probe=fb1ce94b02) | Apr 16, 2021 |
| Toshiba       | Satellite U400              | [159d86eda9](https://linux-hardware.org/?probe=159d86eda9) | Apr 16, 2021 |
| HP            | Pavilion dv5                | [901dd6f4bc](https://linux-hardware.org/?probe=901dd6f4bc) | Apr 14, 2021 |
| Dell          | Vostro 3558                 | [025fc515fe](https://linux-hardware.org/?probe=025fc515fe) | Apr 10, 2021 |
| Lenovo        | ThinkPad X250 20CLS1LC13    | [dc8d311227](https://linux-hardware.org/?probe=dc8d311227) | Apr 09, 2021 |
| Dell          | XPS 15 9500                 | [81aeaba043](https://linux-hardware.org/?probe=81aeaba043) | Apr 09, 2021 |
| Acer          | Nitro AN515-43              | [8a34a292e5](https://linux-hardware.org/?probe=8a34a292e5) | Apr 07, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | [bce1022d19](https://linux-hardware.org/?probe=bce1022d19) | Apr 07, 2021 |
| Acer          | Aspire A315-21              | [996a7d6ddd](https://linux-hardware.org/?probe=996a7d6ddd) | Apr 06, 2021 |
| Dell          | Latitude E6330              | [929d29d6a1](https://linux-hardware.org/?probe=929d29d6a1) | Apr 04, 2021 |
| Acer          | Aspire A315-21              | [ba65bedf97](https://linux-hardware.org/?probe=ba65bedf97) | Apr 04, 2021 |
| Dell          | Inspiron MM061              | [b5fd8765a4](https://linux-hardware.org/?probe=b5fd8765a4) | Mar 31, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [0d90d26719](https://linux-hardware.org/?probe=0d90d26719) | Mar 31, 2021 |
| Packard Be... | EasyNote TK87               | [f7a63e6a25](https://linux-hardware.org/?probe=f7a63e6a25) | Mar 30, 2021 |
| Toshiba       | QOSMIO F50                  | [d9d565847f](https://linux-hardware.org/?probe=d9d565847f) | Mar 29, 2021 |
| HP            | Compaq 6530b (GW688AV#AK... | [4644bc75a5](https://linux-hardware.org/?probe=4644bc75a5) | Mar 29, 2021 |
| Apple         | MacBookPro11,1              | [666815417c](https://linux-hardware.org/?probe=666815417c) | Mar 28, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | [129caa2510](https://linux-hardware.org/?probe=129caa2510) | Mar 27, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [151e709efd](https://linux-hardware.org/?probe=151e709efd) | Mar 25, 2021 |
| ASUSTek       | E502SA                      | [11a2b81dd1](https://linux-hardware.org/?probe=11a2b81dd1) | Mar 24, 2021 |
| Apple         | MacBookPro11,1              | [d2027dc1c2](https://linux-hardware.org/?probe=d2027dc1c2) | Mar 24, 2021 |
| Acer          | Nitro AN515-43              | [f6eae97e20](https://linux-hardware.org/?probe=f6eae97e20) | Mar 24, 2021 |
| Acer          | TravelMate 8571             | [a4f34315e7](https://linux-hardware.org/?probe=a4f34315e7) | Mar 23, 2021 |
| Toshiba       | PORTEGE R830                | [f7c456b329](https://linux-hardware.org/?probe=f7c456b329) | Mar 22, 2021 |
| Toshiba       | PORTEGE R830                | [f4b00c40b9](https://linux-hardware.org/?probe=f4b00c40b9) | Mar 22, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [9e4bff4b7d](https://linux-hardware.org/?probe=9e4bff4b7d) | Mar 21, 2021 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | [2cad1297af](https://linux-hardware.org/?probe=2cad1297af) | Mar 19, 2021 |
| Dell          | Inspiron 7577               | [5318792cf8](https://linux-hardware.org/?probe=5318792cf8) | Mar 19, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [1b40fb1844](https://linux-hardware.org/?probe=1b40fb1844) | Mar 17, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [c685612dc3](https://linux-hardware.org/?probe=c685612dc3) | Mar 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [b7a83e1d4a](https://linux-hardware.org/?probe=b7a83e1d4a) | Mar 05, 2021 |
| Lenovo        | Yoga 500-14ISK 80R5         | [871b9656f1](https://linux-hardware.org/?probe=871b9656f1) | Mar 04, 2021 |
| Acer          | Nitro AN515-43              | [67054a2b55](https://linux-hardware.org/?probe=67054a2b55) | Mar 04, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [835e8cad03](https://linux-hardware.org/?probe=835e8cad03) | Feb 25, 2021 |
| Fujitsu       | CELSIUS H720                | [ebed3a7dfe](https://linux-hardware.org/?probe=ebed3a7dfe) | Feb 25, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [a95dd47eb7](https://linux-hardware.org/?probe=a95dd47eb7) | Feb 25, 2021 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [afb4a1cd76](https://linux-hardware.org/?probe=afb4a1cd76) | Feb 24, 2021 |
| Dell          | Inspiron 3584               | [5db4b64bf0](https://linux-hardware.org/?probe=5db4b64bf0) | Feb 23, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [544bcae58c](https://linux-hardware.org/?probe=544bcae58c) | Feb 22, 2021 |
| ASUSTek       | G752VL                      | [3c853cb10a](https://linux-hardware.org/?probe=3c853cb10a) | Feb 21, 2021 |
| Acer          | Nitro AN515-43              | [31612033c1](https://linux-hardware.org/?probe=31612033c1) | Feb 18, 2021 |
| Acer          | Aspire E5-771G              | [6606087332](https://linux-hardware.org/?probe=6606087332) | Feb 17, 2021 |
| Toshiba       | TECRA A11                   | [96fc158d33](https://linux-hardware.org/?probe=96fc158d33) | Feb 16, 2021 |
| Dell          | Latitude E6430              | [f858e68811](https://linux-hardware.org/?probe=f858e68811) | Feb 15, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [0954aa8af0](https://linux-hardware.org/?probe=0954aa8af0) | Feb 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [4dd2d0ba4d](https://linux-hardware.org/?probe=4dd2d0ba4d) | Feb 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [9d43f3047b](https://linux-hardware.org/?probe=9d43f3047b) | Feb 15, 2021 |
| Dell          | Vostro 3580                 | [476cc70c3f](https://linux-hardware.org/?probe=476cc70c3f) | Feb 13, 2021 |
| HP            | EliteBook 850 G5            | [aa7fb32dfe](https://linux-hardware.org/?probe=aa7fb32dfe) | Feb 13, 2021 |
| Dell          | Vostro 3580                 | [b3a0df6f88](https://linux-hardware.org/?probe=b3a0df6f88) | Feb 10, 2021 |
| Lenovo        | IdeaPad S540-14IML 81NF     | [12349b18fb](https://linux-hardware.org/?probe=12349b18fb) | Feb 10, 2021 |
| ASUSTek       | GL553VE                     | [32fe0edcd8](https://linux-hardware.org/?probe=32fe0edcd8) | Feb 07, 2021 |
| MSI           | GF63 Thin 9RCX              | [e196e2ba5d](https://linux-hardware.org/?probe=e196e2ba5d) | Feb 07, 2021 |
| HP            | ProBook 450 G0              | [ea03b28712](https://linux-hardware.org/?probe=ea03b28712) | Feb 06, 2021 |
| HP            | ProBook 450 G0              | [a327d5e0ca](https://linux-hardware.org/?probe=a327d5e0ca) | Feb 06, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0SY0... | [26dbb68145](https://linux-hardware.org/?probe=26dbb68145) | Feb 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [43384d51bb](https://linux-hardware.org/?probe=43384d51bb) | Feb 04, 2021 |
| HP            | ProBook 6460b               | [e531fae869](https://linux-hardware.org/?probe=e531fae869) | Feb 02, 2021 |
| Apple         | MacBook4,1                  | [154f183a32](https://linux-hardware.org/?probe=154f183a32) | Feb 01, 2021 |
| Apple         | MacBook4,1                  | [0d28bdf0d4](https://linux-hardware.org/?probe=0d28bdf0d4) | Jan 30, 2021 |
| Apple         | MacBook4,1                  | [566ca9b700](https://linux-hardware.org/?probe=566ca9b700) | Jan 30, 2021 |
| Toshiba       | Satellite L655              | [c0670e9519](https://linux-hardware.org/?probe=c0670e9519) | Jan 29, 2021 |
| Lenovo        | ThinkPad T430 2349PS3       | [b7eecfebd0](https://linux-hardware.org/?probe=b7eecfebd0) | Jan 29, 2021 |
| Lenovo        | ThinkPad T450s 20BWS3MG0... | [c8df50c9cc](https://linux-hardware.org/?probe=c8df50c9cc) | Jan 28, 2021 |
| Dell          | XPS 13 9360                 | [752f448ced](https://linux-hardware.org/?probe=752f448ced) | Jan 25, 2021 |
| HP            | Laptop 15-da0xxx            | [2fef9954bb](https://linux-hardware.org/?probe=2fef9954bb) | Jan 24, 2021 |
| MSI           | GP60 2PE                    | [2f0ad65f95](https://linux-hardware.org/?probe=2f0ad65f95) | Jan 16, 2021 |
| MSI           | GP60 2PE                    | [676959ecd5](https://linux-hardware.org/?probe=676959ecd5) | Jan 16, 2021 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [782581f6ad](https://linux-hardware.org/?probe=782581f6ad) | Jan 15, 2021 |
| HP            | EliteBook 850 G5            | [839dd41ca6](https://linux-hardware.org/?probe=839dd41ca6) | Jan 13, 2021 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [1c8eedbc0f](https://linux-hardware.org/?probe=1c8eedbc0f) | Jan 11, 2021 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [947ae48eec](https://linux-hardware.org/?probe=947ae48eec) | Jan 10, 2021 |
| HP            | EliteBook 1050 G1           | [34b72d5988](https://linux-hardware.org/?probe=34b72d5988) | Jan 10, 2021 |
| Apple         | MacBookPro11,1              | [e8ac486033](https://linux-hardware.org/?probe=e8ac486033) | Jan 09, 2021 |
| Lenovo        | V130-15IGM 81HL             | [9cd4e14d95](https://linux-hardware.org/?probe=9cd4e14d95) | Jan 09, 2021 |
| Lenovo        | V130-15IGM 81HL             | [d0a18fe6bf](https://linux-hardware.org/?probe=d0a18fe6bf) | Jan 09, 2021 |
| Sony          | VPCEA3L1E                   | [5d9e8a1b24](https://linux-hardware.org/?probe=5d9e8a1b24) | Jan 08, 2021 |
| Sony          | VPCEA3L1E                   | [251d4f6677](https://linux-hardware.org/?probe=251d4f6677) | Jan 07, 2021 |
| Dell          | Latitude E5440              | [b207a3f9fc](https://linux-hardware.org/?probe=b207a3f9fc) | Jan 07, 2021 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [67484b4909](https://linux-hardware.org/?probe=67484b4909) | Jan 06, 2021 |
| Packard Be... | EasyNote TK87               | [c56d5ed89f](https://linux-hardware.org/?probe=c56d5ed89f) | Jan 03, 2021 |
| Dell          | Latitude E6410              | [0a272a215c](https://linux-hardware.org/?probe=0a272a215c) | Jan 02, 2021 |
| Dell          | Latitude E6410              | [38d452be3e](https://linux-hardware.org/?probe=38d452be3e) | Jan 02, 2021 |
| Toshiba       | Satellite C50-A-19T         | [b1855e2094](https://linux-hardware.org/?probe=b1855e2094) | Dec 29, 2020 |
| Toshiba       | Satellite C50-A-19T         | [5d028d0524](https://linux-hardware.org/?probe=5d028d0524) | Dec 29, 2020 |
| Toshiba       | Satellite A300              | [83cb7ff036](https://linux-hardware.org/?probe=83cb7ff036) | Dec 28, 2020 |
| HP            | Laptop 15-da0xxx            | [55bd66c418](https://linux-hardware.org/?probe=55bd66c418) | Dec 27, 2020 |
| Acer          | Aspire 5738                 | [27df1aad94](https://linux-hardware.org/?probe=27df1aad94) | Dec 22, 2020 |
| Acer          | Aspire A315-31              | [d04453166b](https://linux-hardware.org/?probe=d04453166b) | Dec 21, 2020 |
| Lenovo        | ThinkPad T500 20567LG       | [9435132c9f](https://linux-hardware.org/?probe=9435132c9f) | Dec 21, 2020 |
| Apple         | MacBook4,1                  | [17dc1d498a](https://linux-hardware.org/?probe=17dc1d498a) | Dec 18, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e665e888af](https://linux-hardware.org/?probe=e665e888af) | Dec 16, 2020 |
| Dell          | Latitude E5430 non-vPro     | [eb181ebb12](https://linux-hardware.org/?probe=eb181ebb12) | Dec 14, 2020 |
| Apple         | MacBook4,1                  | [8e26299b90](https://linux-hardware.org/?probe=8e26299b90) | Dec 13, 2020 |
| Apple         | MacBook4,1                  | [2f0d63f9a3](https://linux-hardware.org/?probe=2f0d63f9a3) | Dec 12, 2020 |
| Toshiba       | Satellite C50-A-19T         | [0236c0854e](https://linux-hardware.org/?probe=0236c0854e) | Dec 12, 2020 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | [d4d7a977db](https://linux-hardware.org/?probe=d4d7a977db) | Dec 07, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [a388c1bf1e](https://linux-hardware.org/?probe=a388c1bf1e) | Dec 05, 2020 |
| HP            | EliteBook 8560p             | [ef428fdd17](https://linux-hardware.org/?probe=ef428fdd17) | Dec 03, 2020 |
| Dell          | Latitude 5591               | [43f7f0c137](https://linux-hardware.org/?probe=43f7f0c137) | Dec 02, 2020 |
| Dell          | Vostro 3580                 | [a3342731b8](https://linux-hardware.org/?probe=a3342731b8) | Dec 01, 2020 |
| Cube          | i16-L                       | [80ab92ec4d](https://linux-hardware.org/?probe=80ab92ec4d) | Dec 01, 2020 |
| Lenovo        | ThinkPad T495 20NKS01W0H    | [f5481042a6](https://linux-hardware.org/?probe=f5481042a6) | Nov 30, 2020 |
| Lenovo        | ThinkPad T495 20NKS01W0H    | [911676a550](https://linux-hardware.org/?probe=911676a550) | Nov 30, 2020 |
| Lenovo        | ThinkPad X220 4291QT1       | [0b050dca43](https://linux-hardware.org/?probe=0b050dca43) | Nov 29, 2020 |
| Lenovo        | IdeaPad Y510P 20217         | [a5669b915e](https://linux-hardware.org/?probe=a5669b915e) | Nov 25, 2020 |
| Lenovo        | IdeaPad Y510P 20217         | [f0cf2d64a6](https://linux-hardware.org/?probe=f0cf2d64a6) | Nov 23, 2020 |
| Lenovo        | ThinkPad T460s 20FAS2BV0... | [c58bafb526](https://linux-hardware.org/?probe=c58bafb526) | Nov 23, 2020 |
| HP            | EliteBook 850 G7 Noteboo... | [ed63cb31af](https://linux-hardware.org/?probe=ed63cb31af) | Nov 18, 2020 |
| Dell          | Inspiron N5110              | [ca8ffcb464](https://linux-hardware.org/?probe=ca8ffcb464) | Nov 15, 2020 |
| HP            | EliteBook 8560p             | [f934cc994f](https://linux-hardware.org/?probe=f934cc994f) | Nov 14, 2020 |
| Acer          | Aspire E5-572G              | [aa4817a78d](https://linux-hardware.org/?probe=aa4817a78d) | Nov 12, 2020 |
| ASUSTek       | G551JM                      | [5bf5531f2d](https://linux-hardware.org/?probe=5bf5531f2d) | Nov 08, 2020 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [1b21b64248](https://linux-hardware.org/?probe=1b21b64248) | Nov 08, 2020 |
| Dell          | Inspiron 5370               | [a7ffc4fdf0](https://linux-hardware.org/?probe=a7ffc4fdf0) | Nov 07, 2020 |
| Dell          | Latitude E5430 non-vPro     | [9f2d169081](https://linux-hardware.org/?probe=9f2d169081) | Nov 06, 2020 |
| Acer          | Aspire V3-772               | [413786151e](https://linux-hardware.org/?probe=413786151e) | Oct 31, 2020 |
| HP            | ProBook 6470b               | [18f5fab938](https://linux-hardware.org/?probe=18f5fab938) | Oct 31, 2020 |
| Dell          | Vostro 3580                 | [a0e40c6f16](https://linux-hardware.org/?probe=a0e40c6f16) | Oct 29, 2020 |
| ASUSTek       | X541NA                      | [a4497b52bb](https://linux-hardware.org/?probe=a4497b52bb) | Oct 28, 2020 |
| Lenovo        | ThinkPad qqqqS2E            | [4643cfe86d](https://linux-hardware.org/?probe=4643cfe86d) | Oct 27, 2020 |
| Lenovo        | ThinkPad qqqqS2E            | [da5ad20c60](https://linux-hardware.org/?probe=da5ad20c60) | Oct 27, 2020 |
| Dell          | Latitude 5480               | [4191db79b7](https://linux-hardware.org/?probe=4191db79b7) | Oct 25, 2020 |
| Toshiba       | Satellite S70-B             | [a6521e505a](https://linux-hardware.org/?probe=a6521e505a) | Oct 25, 2020 |
| Lenovo        | G50-80 80E5                 | [89f32e3856](https://linux-hardware.org/?probe=89f32e3856) | Oct 23, 2020 |
| ASUSTek       | N551VW                      | [76852e9990](https://linux-hardware.org/?probe=76852e9990) | Oct 22, 2020 |
| Lenovo        | G570 20079                  | [74b57e7887](https://linux-hardware.org/?probe=74b57e7887) | Oct 21, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [a1a02fe851](https://linux-hardware.org/?probe=a1a02fe851) | Oct 18, 2020 |
| Dell          | Latitude E5430 non-vPro     | [dd68c7b3f6](https://linux-hardware.org/?probe=dd68c7b3f6) | Oct 18, 2020 |
| Toshiba       | Satellite P300              | [fdc8cb1b11](https://linux-hardware.org/?probe=fdc8cb1b11) | Oct 16, 2020 |
| Lenovo        | Yoga 2 11 20428             | [f5c8360ae3](https://linux-hardware.org/?probe=f5c8360ae3) | Oct 15, 2020 |
| Lenovo        | G50-80 80E5                 | [3f72e0309a](https://linux-hardware.org/?probe=3f72e0309a) | Oct 15, 2020 |
| Lenovo        | G570 20079                  | [ba66ad5205](https://linux-hardware.org/?probe=ba66ad5205) | Oct 12, 2020 |
| Lenovo        | G570 20079                  | [5e14548b50](https://linux-hardware.org/?probe=5e14548b50) | Oct 12, 2020 |
| HP            | EliteBook 8560p             | [bbae413f9c](https://linux-hardware.org/?probe=bbae413f9c) | Oct 10, 2020 |
| ASUSTek       | K53U                        | [59444922e7](https://linux-hardware.org/?probe=59444922e7) | Oct 10, 2020 |
| ASUSTek       | K53U                        | [5c5b3815f7](https://linux-hardware.org/?probe=5c5b3815f7) | Oct 10, 2020 |
| Lenovo        | IdeaPad Y510P 20217         | [25fb29514f](https://linux-hardware.org/?probe=25fb29514f) | Oct 10, 2020 |
| Lenovo        | ThinkPad W520 4284GN2       | [8677a1b95c](https://linux-hardware.org/?probe=8677a1b95c) | Oct 07, 2020 |
| Lenovo        | ThinkPad W520 4284GN2       | [352bbb87fe](https://linux-hardware.org/?probe=352bbb87fe) | Oct 07, 2020 |
| Acer          | Aspire V3-571G              | [86c3c25832](https://linux-hardware.org/?probe=86c3c25832) | Oct 05, 2020 |
| HP            | 250 G3                      | [ab75ccc4f8](https://linux-hardware.org/?probe=ab75ccc4f8) | Oct 02, 2020 |
| Dell          | Inspiron 3583               | [419cd76be1](https://linux-hardware.org/?probe=419cd76be1) | Oct 01, 2020 |
| Acer          | Aspire 5738                 | [18199ffdaf](https://linux-hardware.org/?probe=18199ffdaf) | Sep 30, 2020 |
| Dell          | G7 7588                     | [0d38edaf0c](https://linux-hardware.org/?probe=0d38edaf0c) | Sep 28, 2020 |
| Toshiba       | Satellite P300              | [33020554c0](https://linux-hardware.org/?probe=33020554c0) | Sep 27, 2020 |
| HP            | EliteBook 8470p             | [e330dd752b](https://linux-hardware.org/?probe=e330dd752b) | Sep 23, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [96d1d6229b](https://linux-hardware.org/?probe=96d1d6229b) | Sep 23, 2020 |
| Acer          | Nitro AN515-44              | [18afb6b15d](https://linux-hardware.org/?probe=18afb6b15d) | Sep 22, 2020 |
| Acer          | Nitro AN515-44              | [c078093e0f](https://linux-hardware.org/?probe=c078093e0f) | Sep 22, 2020 |
| HP            | Compaq tc4400 (RH489ES#A... | [c0305edfae](https://linux-hardware.org/?probe=c0305edfae) | Sep 20, 2020 |
| ASUSTek       | K50C                        | [d4e11f2289](https://linux-hardware.org/?probe=d4e11f2289) | Sep 18, 2020 |
| Acer          | Extensa 5630                | [9040e8e334](https://linux-hardware.org/?probe=9040e8e334) | Sep 12, 2020 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | [a66f1b519a](https://linux-hardware.org/?probe=a66f1b519a) | Sep 10, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [c2a66820da](https://linux-hardware.org/?probe=c2a66820da) | Sep 06, 2020 |
| Lenovo        | ThinkPad X250 20CLS2YH00    | [cee4231640](https://linux-hardware.org/?probe=cee4231640) | Aug 29, 2020 |
| Fujitsu       | LIFEBOOK E752               | [9820c3c8bd](https://linux-hardware.org/?probe=9820c3c8bd) | Aug 28, 2020 |
| Dell          | Precision M4800             | [4765bc9ec2](https://linux-hardware.org/?probe=4765bc9ec2) | Aug 19, 2020 |
| Dell          | Precision M4800             | [eee5b97967](https://linux-hardware.org/?probe=eee5b97967) | Aug 19, 2020 |
| HP            | 250 G3                      | [ff5c3ce273](https://linux-hardware.org/?probe=ff5c3ce273) | Aug 19, 2020 |
| HP            | EliteBook 8560w             | [bf7ae9d5bf](https://linux-hardware.org/?probe=bf7ae9d5bf) | Aug 19, 2020 |
| HP            | 250 G3                      | [01f2866b5c](https://linux-hardware.org/?probe=01f2866b5c) | Aug 18, 2020 |
| Lenovo        | IdeaPad S540-14IML 81NF     | [1619b6bb6c](https://linux-hardware.org/?probe=1619b6bb6c) | Aug 18, 2020 |
| Acer          | Nitro AN515-43              | [65cf550e5a](https://linux-hardware.org/?probe=65cf550e5a) | Aug 16, 2020 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [18c07b157f](https://linux-hardware.org/?probe=18c07b157f) | Jul 29, 2020 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [8051286600](https://linux-hardware.org/?probe=8051286600) | Jul 29, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [06120056c3](https://linux-hardware.org/?probe=06120056c3) | Jul 25, 2020 |
| Lenovo        | IdeaPad S340-15API 81NC     | [e8d593715c](https://linux-hardware.org/?probe=e8d593715c) | Jul 25, 2020 |
| Lenovo        | IdeaPad S540-14IML 81NF     | [42fc06b0e4](https://linux-hardware.org/?probe=42fc06b0e4) | Jul 23, 2020 |
| Packard Be... | DOTS E2                     | [223cceb869](https://linux-hardware.org/?probe=223cceb869) | Jul 19, 2020 |
| Packard Be... | DOTS E2                     | [699033745c](https://linux-hardware.org/?probe=699033745c) | Jul 19, 2020 |
| Acer          | E5-575G                     | [9fb1e1bee4](https://linux-hardware.org/?probe=9fb1e1bee4) | Jul 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [ee5e7f9151](https://linux-hardware.org/?probe=ee5e7f9151) | Jul 18, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [968247c419](https://linux-hardware.org/?probe=968247c419) | Jul 17, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [c1fb882fc5](https://linux-hardware.org/?probe=c1fb882fc5) | Jul 17, 2020 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | [498a1fee5c](https://linux-hardware.org/?probe=498a1fee5c) | Jul 14, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ac0d845ddb](https://linux-hardware.org/?probe=ac0d845ddb) | Jul 13, 2020 |
| ASUSTek       | X510UQR                     | [54f20878cf](https://linux-hardware.org/?probe=54f20878cf) | Jul 12, 2020 |
| Lenovo        | ThinkPad T590 20N5S2BP00    | [16f6fb2756](https://linux-hardware.org/?probe=16f6fb2756) | Jul 02, 2020 |
| Fujitsu Si... | AMILO L Series              | [33762202ef](https://linux-hardware.org/?probe=33762202ef) | Jul 01, 2020 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [5aef8629ba](https://linux-hardware.org/?probe=5aef8629ba) | Jun 30, 2020 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | [9b54e3f16c](https://linux-hardware.org/?probe=9b54e3f16c) | Jun 30, 2020 |
| Dell          | Latitude E6410              | [79c1af2581](https://linux-hardware.org/?probe=79c1af2581) | Jun 29, 2020 |
| Acer          | Swift SF314-57G             | [9bd6123d76](https://linux-hardware.org/?probe=9bd6123d76) | Jun 25, 2020 |
| Toshiba       | Satellite C55-A-1HL         | [c6d6bb3ba1](https://linux-hardware.org/?probe=c6d6bb3ba1) | Jun 18, 2020 |
| Toshiba       | Satellite C55-A-1HL         | [d16857f500](https://linux-hardware.org/?probe=d16857f500) | Jun 17, 2020 |
| Lenovo        | ThinkPad T470s 20HF004UM... | [7a3bd1d810](https://linux-hardware.org/?probe=7a3bd1d810) | Jun 10, 2020 |
| Acer          | Nitro AN515-43              | [65f523b6f2](https://linux-hardware.org/?probe=65f523b6f2) | Jun 06, 2020 |
| Acer          | Nitro AN515-43              | [c8ddcb0ec8](https://linux-hardware.org/?probe=c8ddcb0ec8) | Jun 06, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [d23bc12452](https://linux-hardware.org/?probe=d23bc12452) | Jun 04, 2020 |
| HP            | 250 G3                      | [99be1919b2](https://linux-hardware.org/?probe=99be1919b2) | Jun 01, 2020 |
| Toshiba       | Satellite P300              | [8eb9fa72de](https://linux-hardware.org/?probe=8eb9fa72de) | May 31, 2020 |
| Lenovo        | G505 20240                  | [6860a03dd0](https://linux-hardware.org/?probe=6860a03dd0) | May 31, 2020 |
| HP            | 250 G3                      | [a4e1d1f904](https://linux-hardware.org/?probe=a4e1d1f904) | May 29, 2020 |
| Lenovo        | ThinkPad T495 20NJ0010BM    | [6974ca5761](https://linux-hardware.org/?probe=6974ca5761) | May 29, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [edcc0b8c05](https://linux-hardware.org/?probe=edcc0b8c05) | May 29, 2020 |
| ASUSTek       | X540LJ                      | [67a3981fe5](https://linux-hardware.org/?probe=67a3981fe5) | May 27, 2020 |
| Dell          | Inspiron N5110              | [e2ba0ca3f4](https://linux-hardware.org/?probe=e2ba0ca3f4) | May 22, 2020 |
| ASUSTek       | X705UNR                     | [015957a390](https://linux-hardware.org/?probe=015957a390) | May 22, 2020 |
| HP            | ProBook 6460b               | [babf988605](https://linux-hardware.org/?probe=babf988605) | May 22, 2020 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [29131d3d86](https://linux-hardware.org/?probe=29131d3d86) | May 21, 2020 |
| HP            | EliteBook 840 G1            | [a39e33b1f4](https://linux-hardware.org/?probe=a39e33b1f4) | May 20, 2020 |
| HP            | EliteBook 840 G1            | [4f773edbaa](https://linux-hardware.org/?probe=4f773edbaa) | May 20, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [33722345b4](https://linux-hardware.org/?probe=33722345b4) | May 13, 2020 |
| HP            | 255 G2                      | [ad9ef87735](https://linux-hardware.org/?probe=ad9ef87735) | May 13, 2020 |
| Acer          | Aspire 5742G                | [f27a7b8301](https://linux-hardware.org/?probe=f27a7b8301) | May 13, 2020 |
| HP            | ProBook 450 G0              | [88fc8f3bc8](https://linux-hardware.org/?probe=88fc8f3bc8) | May 13, 2020 |
| Acer          | Aspire 5742G                | [2dec87937c](https://linux-hardware.org/?probe=2dec87937c) | May 12, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [715f4fa65b](https://linux-hardware.org/?probe=715f4fa65b) | May 12, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [96cd96c818](https://linux-hardware.org/?probe=96cd96c818) | May 12, 2020 |
| HP            | ProBook 4710s               | [b2680d0881](https://linux-hardware.org/?probe=b2680d0881) | May 11, 2020 |
| HP            | EliteBook 840 G1            | [f6bc1aa4bf](https://linux-hardware.org/?probe=f6bc1aa4bf) | May 11, 2020 |
| Acer          | Nitro AN515-43              | [6da190e95d](https://linux-hardware.org/?probe=6da190e95d) | May 10, 2020 |
| HP            | 255 G2                      | [ee5dcad518](https://linux-hardware.org/?probe=ee5dcad518) | May 10, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [050c997025](https://linux-hardware.org/?probe=050c997025) | May 08, 2020 |
| Dell          | Latitude 7490               | [94b949eb90](https://linux-hardware.org/?probe=94b949eb90) | May 08, 2020 |
| Acer          | E5-575G                     | [4de3c815fd](https://linux-hardware.org/?probe=4de3c815fd) | May 08, 2020 |
| HP            | EliteBook 820 G2            | [3b379abf6a](https://linux-hardware.org/?probe=3b379abf6a) | May 07, 2020 |
| HP            | EliteBook 840 G1            | [10d3d30341](https://linux-hardware.org/?probe=10d3d30341) | May 07, 2020 |
| HP            | 255 G2                      | [162f37494e](https://linux-hardware.org/?probe=162f37494e) | May 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [ea793cbae5](https://linux-hardware.org/?probe=ea793cbae5) | May 06, 2020 |
| Dell          | Latitude E4300              | [8b26d2727c](https://linux-hardware.org/?probe=8b26d2727c) | May 06, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [cbcdbbc816](https://linux-hardware.org/?probe=cbcdbbc816) | May 04, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [72e18e38ce](https://linux-hardware.org/?probe=72e18e38ce) | May 04, 2020 |
| HP            | Pavilion Notebook           | [35d925dbae](https://linux-hardware.org/?probe=35d925dbae) | May 04, 2020 |
| Dell          | Inspiron 7577               | [02c7c61130](https://linux-hardware.org/?probe=02c7c61130) | May 03, 2020 |
| Dell          | Inspiron 7577               | [d987f6c242](https://linux-hardware.org/?probe=d987f6c242) | May 03, 2020 |
| Toshiba       | Satellite Radius 12 P20W... | [4f272f1c99](https://linux-hardware.org/?probe=4f272f1c99) | May 03, 2020 |
| MSI           | GS65 Stealth Thin 8RE       | [c3b3575e58](https://linux-hardware.org/?probe=c3b3575e58) | May 02, 2020 |
| ASUSTek       | G771JW                      | [77202c9853](https://linux-hardware.org/?probe=77202c9853) | May 02, 2020 |
| HP            | ProBook 450 G0              | [f74dab71c3](https://linux-hardware.org/?probe=f74dab71c3) | May 01, 2020 |
| HP            | ProBook 450 G0              | [7ac5247653](https://linux-hardware.org/?probe=7ac5247653) | May 01, 2020 |
| Acer          | Aspire 3830G                | [1af95987d0](https://linux-hardware.org/?probe=1af95987d0) | Apr 26, 2020 |
| Lenovo        | ThinkPad L590 20Q700AWBM    | [2dde18f51f](https://linux-hardware.org/?probe=2dde18f51f) | Apr 24, 2020 |
| ASUSTek       | N551VW                      | [2d93805421](https://linux-hardware.org/?probe=2d93805421) | Apr 23, 2020 |
| ASUSTek       | N551VW                      | [155a39180a](https://linux-hardware.org/?probe=155a39180a) | Apr 23, 2020 |
| HP            | 250 G7 Notebook PC          | [28fa6e8b6e](https://linux-hardware.org/?probe=28fa6e8b6e) | Apr 22, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [73f401be06](https://linux-hardware.org/?probe=73f401be06) | Apr 22, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [562403e85f](https://linux-hardware.org/?probe=562403e85f) | Apr 21, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [ee479d0e5d](https://linux-hardware.org/?probe=ee479d0e5d) | Apr 20, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [a78b041d0c](https://linux-hardware.org/?probe=a78b041d0c) | Apr 20, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [fbfdc3b5e3](https://linux-hardware.org/?probe=fbfdc3b5e3) | Apr 20, 2020 |
| Sony          | VPCEB4L1E                   | [f1a3807b60](https://linux-hardware.org/?probe=f1a3807b60) | Apr 20, 2020 |
| Compal        | HEL80I                      | [41fd098e10](https://linux-hardware.org/?probe=41fd098e10) | Apr 20, 2020 |
| HP            | 250 G7 Notebook PC          | [6b8e555d43](https://linux-hardware.org/?probe=6b8e555d43) | Apr 18, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [f3b92c302c](https://linux-hardware.org/?probe=f3b92c302c) | Apr 16, 2020 |
| Dell          | Inspiron 3580               | [d1e3e7d629](https://linux-hardware.org/?probe=d1e3e7d629) | Apr 16, 2020 |
| Dell          | Inspiron 3580               | [a9b4abdd56](https://linux-hardware.org/?probe=a9b4abdd56) | Apr 16, 2020 |
| Dell          | Inspiron N5110              | [43f93a43d6](https://linux-hardware.org/?probe=43f93a43d6) | Apr 16, 2020 |
| Dell          | Inspiron N5110              | [20b4b0a6ad](https://linux-hardware.org/?probe=20b4b0a6ad) | Apr 16, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [02d576419f](https://linux-hardware.org/?probe=02d576419f) | Apr 14, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [5fc32fd27b](https://linux-hardware.org/?probe=5fc32fd27b) | Apr 12, 2020 |
| Acer          | Aspire E1-570G              | [e727c9003c](https://linux-hardware.org/?probe=e727c9003c) | Apr 10, 2020 |
| Acer          | Aspire E1-570G              | [fe1196d306](https://linux-hardware.org/?probe=fe1196d306) | Apr 09, 2020 |
| Dell          | Inspiron 3521               | [53b2f1863a](https://linux-hardware.org/?probe=53b2f1863a) | Apr 07, 2020 |
| Acer          | Nitro AN515-43              | [6b0efa548b](https://linux-hardware.org/?probe=6b0efa548b) | Apr 04, 2020 |
| HP            | ProBook 4540s               | [e3c52f3d96](https://linux-hardware.org/?probe=e3c52f3d96) | Apr 01, 2020 |
| Lenovo        | ThinkPad E480 20KN005CBM    | [cbc70bfce5](https://linux-hardware.org/?probe=cbc70bfce5) | Apr 01, 2020 |
| Lenovo        | ThinkPad E480 20KN005CBM    | [d018206f33](https://linux-hardware.org/?probe=d018206f33) | Mar 31, 2020 |
| HP            | EliteBook 8560w             | [5038965b3b](https://linux-hardware.org/?probe=5038965b3b) | Mar 30, 2020 |
| HP            | ProBook 4540s               | [6b9b373a1f](https://linux-hardware.org/?probe=6b9b373a1f) | Mar 30, 2020 |
| Lenovo        | ThinkPad E480 20KN005CBM    | [99865fe49f](https://linux-hardware.org/?probe=99865fe49f) | Mar 29, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [c7eda36111](https://linux-hardware.org/?probe=c7eda36111) | Mar 28, 2020 |
| Acer          | Predator G3-572             | [9434c59ae1](https://linux-hardware.org/?probe=9434c59ae1) | Mar 28, 2020 |
| Acer          | Predator G3-572             | [11828122f2](https://linux-hardware.org/?probe=11828122f2) | Mar 28, 2020 |
| ASUSTek       | TUF Gaming FX505GM_FX505... | [edf4388f6a](https://linux-hardware.org/?probe=edf4388f6a) | Mar 26, 2020 |
| HP            | 620                         | [633afcbbef](https://linux-hardware.org/?probe=633afcbbef) | Mar 25, 2020 |
| HP            | 620                         | [8487590fa2](https://linux-hardware.org/?probe=8487590fa2) | Mar 25, 2020 |
| HP            | 250 G7 Notebook PC          | [c63e1ec4fd](https://linux-hardware.org/?probe=c63e1ec4fd) | Mar 23, 2020 |
| Toshiba       | Satellite L50-C             | [b343a21e42](https://linux-hardware.org/?probe=b343a21e42) | Mar 17, 2020 |
| Lenovo        | ThinkPad T470p 20J6S0A30... | [b02f5ffeeb](https://linux-hardware.org/?probe=b02f5ffeeb) | Mar 17, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [14544480a5](https://linux-hardware.org/?probe=14544480a5) | Mar 16, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [ccc20cb679](https://linux-hardware.org/?probe=ccc20cb679) | Mar 16, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [7b2e2dc41d](https://linux-hardware.org/?probe=7b2e2dc41d) | Mar 15, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [252c5a9ab3](https://linux-hardware.org/?probe=252c5a9ab3) | Mar 15, 2020 |
| ASUSTek       | GL553VE                     | [810b827dfe](https://linux-hardware.org/?probe=810b827dfe) | Mar 15, 2020 |
| Lenovo        | ThinkPad E480 20KN004TBM    | [13768f8615](https://linux-hardware.org/?probe=13768f8615) | Mar 14, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [4c0f104328](https://linux-hardware.org/?probe=4c0f104328) | Mar 11, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [4587e48bf4](https://linux-hardware.org/?probe=4587e48bf4) | Mar 11, 2020 |
| HP            | Unknown                     | [453696ff5e](https://linux-hardware.org/?probe=453696ff5e) | Mar 04, 2020 |
| Dell          | G3 3579                     | [12a87598d6](https://linux-hardware.org/?probe=12a87598d6) | Mar 02, 2020 |
| HP            | Unknown                     | [f8a7212a74](https://linux-hardware.org/?probe=f8a7212a74) | Feb 26, 2020 |
| Acer          | Aspire 5738                 | [d008370d87](https://linux-hardware.org/?probe=d008370d87) | Feb 24, 2020 |
| HP            | Laptop 15-dw0xxx            | [9c5def065e](https://linux-hardware.org/?probe=9c5def065e) | Feb 22, 2020 |
| Dell          | Latitude 5401               | [76f6ff2608](https://linux-hardware.org/?probe=76f6ff2608) | Feb 16, 2020 |
| HP            | Pro Tablet 610 G1           | [4df7386234](https://linux-hardware.org/?probe=4df7386234) | Feb 16, 2020 |
| HP            | Pro Tablet 610 G1           | [d8f25b08f2](https://linux-hardware.org/?probe=d8f25b08f2) | Feb 16, 2020 |
| Lenovo        | ThinkPad T560 20FJS1YD00    | [b379bf7743](https://linux-hardware.org/?probe=b379bf7743) | Feb 15, 2020 |
| Acer          | Aspire 5541                 | [6bf6d1c16b](https://linux-hardware.org/?probe=6bf6d1c16b) | Feb 15, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [60281c26f1](https://linux-hardware.org/?probe=60281c26f1) | Feb 14, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [3977fb1ddb](https://linux-hardware.org/?probe=3977fb1ddb) | Feb 12, 2020 |
| ASUSTek       | X501A                       | [9e5a342bac](https://linux-hardware.org/?probe=9e5a342bac) | Feb 10, 2020 |
| Dell          | Inspiron 3584               | [c080de1bad](https://linux-hardware.org/?probe=c080de1bad) | Feb 03, 2020 |
| Toshiba       | Satellite L40               | [75079b3cba](https://linux-hardware.org/?probe=75079b3cba) | Jan 29, 2020 |
| Dell          | Inspiron 3580               | [b3e528be2c](https://linux-hardware.org/?probe=b3e528be2c) | Jan 29, 2020 |
| Dell          | Inspiron 3580               | [8db2dfbc60](https://linux-hardware.org/?probe=8db2dfbc60) | Jan 29, 2020 |
| Lenovo        | ThinkPad X220 4291B24       | [ce7dd499a5](https://linux-hardware.org/?probe=ce7dd499a5) | Jan 24, 2020 |
| Toshiba       | Satellite L300              | [f5faa63427](https://linux-hardware.org/?probe=f5faa63427) | Jan 12, 2020 |
| ASUSTek       | K55VM                       | [c1595f145d](https://linux-hardware.org/?probe=c1595f145d) | Jan 11, 2020 |
| Dell          | Inspiron 5520               | [601d03392f](https://linux-hardware.org/?probe=601d03392f) | Jan 05, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | [3f4d79ea3b](https://linux-hardware.org/?probe=3f4d79ea3b) | Jan 03, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | [aa34232c5a](https://linux-hardware.org/?probe=aa34232c5a) | Jan 01, 2020 |
| ASUSTek       | X540NV                      | [6bca5f0ae4](https://linux-hardware.org/?probe=6bca5f0ae4) | Jan 01, 2020 |
| Lenovo        | ThinkPad T420 4236A87       | [353a1db8ac](https://linux-hardware.org/?probe=353a1db8ac) | Dec 31, 2019 |
| TUXEDO        | Unknown                     | [8393427822](https://linux-hardware.org/?probe=8393427822) | Dec 27, 2019 |
| HP            | 530 Notebook PC(KP479AA#... | [3e6684e155](https://linux-hardware.org/?probe=3e6684e155) | Dec 27, 2019 |
| ASUSTek       | X541NA                      | [f885d0ee5f](https://linux-hardware.org/?probe=f885d0ee5f) | Dec 23, 2019 |
| Dell          | Inspiron 5482               | [85bb9ecf3b](https://linux-hardware.org/?probe=85bb9ecf3b) | Dec 20, 2019 |
| Lenovo        | B51-30 80LK                 | [32d296fee0](https://linux-hardware.org/?probe=32d296fee0) | Dec 19, 2019 |
| Dell          | Inspiron N5010              | [d5fec65df9](https://linux-hardware.org/?probe=d5fec65df9) | Dec 13, 2019 |
| MSI           | GS65 Stealth Thin 8RE       | [a9a218f5dd](https://linux-hardware.org/?probe=a9a218f5dd) | Dec 06, 2019 |
| Dell          | Studio 1747                 | [e572489472](https://linux-hardware.org/?probe=e572489472) | Dec 05, 2019 |
| Acer          | Aspire E5-572G              | [0c710c33f6](https://linux-hardware.org/?probe=0c710c33f6) | Dec 04, 2019 |
| Fujitsu Si... | AMILO Xi 3650               | [87afd7dd02](https://linux-hardware.org/?probe=87afd7dd02) | Dec 04, 2019 |
| Dell          | Studio 1747                 | [2daf1225e6](https://linux-hardware.org/?probe=2daf1225e6) | Dec 04, 2019 |
| Dell          | Studio 1747                 | [dfba5a95c8](https://linux-hardware.org/?probe=dfba5a95c8) | Dec 04, 2019 |
| Dell          | Studio 1747                 | [24d64d118b](https://linux-hardware.org/?probe=24d64d118b) | Dec 02, 2019 |
| Lenovo        | IdeaPad S540-14API 81NH     | [781e93ad34](https://linux-hardware.org/?probe=781e93ad34) | Nov 26, 2019 |
| Dell          | Latitude E5530 non-vPro     | [9081234810](https://linux-hardware.org/?probe=9081234810) | Nov 22, 2019 |
| Dell          | Latitude E5530 non-vPro     | [f61b57f6fc](https://linux-hardware.org/?probe=f61b57f6fc) | Nov 22, 2019 |
| ASUSTek       | X505BP                      | [a881fdcf1b](https://linux-hardware.org/?probe=a881fdcf1b) | Nov 21, 2019 |
| Gigabyte      | W348M                       | [0db51928b9](https://linux-hardware.org/?probe=0db51928b9) | Oct 29, 2019 |
| Dell          | Latitude E6410              | [2888ece276](https://linux-hardware.org/?probe=2888ece276) | Oct 27, 2019 |
| Dell          | G7 7588                     | [2479b39b58](https://linux-hardware.org/?probe=2479b39b58) | Oct 27, 2019 |
| Dell          | Inspiron 3580               | [29ff86014c](https://linux-hardware.org/?probe=29ff86014c) | Oct 22, 2019 |
| Dell          | Inspiron 3580               | [8e4e877bc9](https://linux-hardware.org/?probe=8e4e877bc9) | Oct 22, 2019 |
| ASUSTek       | N53SN                       | [b41d353d8b](https://linux-hardware.org/?probe=b41d353d8b) | Oct 18, 2019 |
| Lenovo        | G500 20236                  | [cc14742c63](https://linux-hardware.org/?probe=cc14742c63) | Oct 16, 2019 |
| Lenovo        | G500 20236                  | [592a40c6d4](https://linux-hardware.org/?probe=592a40c6d4) | Oct 13, 2019 |
| Dell          | G3 3579                     | [d04a01d41c](https://linux-hardware.org/?probe=d04a01d41c) | Oct 10, 2019 |
| Dell          | Latitude E6320              | [0c6c848244](https://linux-hardware.org/?probe=0c6c848244) | Oct 09, 2019 |
| HP            | ProBook 470 G0              | [d04f4a23f0](https://linux-hardware.org/?probe=d04f4a23f0) | Oct 07, 2019 |
| Dell          | Latitude E6320              | [0bc384b06e](https://linux-hardware.org/?probe=0bc384b06e) | Oct 06, 2019 |
| Dell          | Latitude E6320              | [59d8f18e3d](https://linux-hardware.org/?probe=59d8f18e3d) | Oct 06, 2019 |
| Dell          | Latitude E6320              | [79c9edf47a](https://linux-hardware.org/?probe=79c9edf47a) | Oct 06, 2019 |
| Dell          | G3 3579                     | [349416fbb3](https://linux-hardware.org/?probe=349416fbb3) | Oct 05, 2019 |
| ASUSTek       | X542UQ                      | [0c0cfccb6f](https://linux-hardware.org/?probe=0c0cfccb6f) | Oct 02, 2019 |
| ASUSTek       | X542UQ                      | [bb0a5f1b8e](https://linux-hardware.org/?probe=bb0a5f1b8e) | Sep 28, 2019 |
| Lenovo        | ThinkPad T530 2429AR7       | [e1a5ba64a3](https://linux-hardware.org/?probe=e1a5ba64a3) | Sep 23, 2019 |
| ASUSTek       | N550JK                      | [3a2e4ab12c](https://linux-hardware.org/?probe=3a2e4ab12c) | Sep 18, 2019 |
| Lenovo        | ThinkPad L590 20Q700AWBM    | [5c664d23d8](https://linux-hardware.org/?probe=5c664d23d8) | Sep 17, 2019 |
| HP            | Compaq 6715s (GR762ES#AB... | [320661ca9f](https://linux-hardware.org/?probe=320661ca9f) | Sep 16, 2019 |
| Toshiba       | Satellite L855              | [f5d2dffc84](https://linux-hardware.org/?probe=f5d2dffc84) | Sep 13, 2019 |
| ASUSTek       | X542UQ                      | [fca2fc959c](https://linux-hardware.org/?probe=fca2fc959c) | Sep 13, 2019 |
| Notebook      | P17SM-A                     | [6ccaea7ee4](https://linux-hardware.org/?probe=6ccaea7ee4) | Sep 11, 2019 |
| HP            | Pavilion dv6                | [4ddfed675e](https://linux-hardware.org/?probe=4ddfed675e) | Sep 07, 2019 |
| ASUSTek       | K55VD                       | [072fcfd6de](https://linux-hardware.org/?probe=072fcfd6de) | Aug 29, 2019 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Bulgaria/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 74        | 9.69%   |
| Ubuntu 18.04                 | 49        | 6.41%   |
| Ubuntu 22.04                 | 42        | 5.5%    |
| OpenMandriva 4.3             | 15        | 1.96%   |
| Manjaro                      | 15        | 1.96%   |
| Fedora 38                    | 14        | 1.83%   |
| Debian 11                    | 14        | 1.83%   |
| Pop!_OS 22.04                | 13        | 1.7%    |
| OpenMandriva 4.2             | 13        | 1.7%    |
| Linux Mint 20.3              | 13        | 1.7%    |
| openSUSE Tumbleweed-XXXXXXXX | 12        | 1.57%   |
| KDE neon 20.04               | 12        | 1.57%   |
| Linux Mint 20.1              | 11        | 1.44%   |
| Zorin 16                     | 10        | 1.31%   |
| ROSA R11                     | 10        | 1.31%   |
| Linux Mint 21.1              | 10        | 1.31%   |
| Linux Mint 19.3              | 10        | 1.31%   |
| Kubuntu 20.04                | 10        | 1.31%   |
| Ubuntu 19.04                 | 9         | 1.18%   |
| Linux Mint 20.2              | 9         | 1.18%   |
| Arch Rolling                 | 9         | 1.18%   |
| Arch                         | 9         | 1.18%   |
| Xubuntu 20.04                | 8         | 1.05%   |
| Ubuntu 22.10                 | 8         | 1.05%   |
| ROSA R10                     | 8         | 1.05%   |
| Linux Mint 21.2              | 8         | 1.05%   |
| Linux Mint 20                | 8         | 1.05%   |
| Fedora 33                    | 8         | 1.05%   |
| ArcoLinux Rolling            | 8         | 1.05%   |
| Ubuntu 19.10                 | 7         | 0.92%   |
| Zorin 15                     | 6         | 0.79%   |
| Xubuntu 18.04                | 6         | 0.79%   |
| Ubuntu 23.04                 | 6         | 0.79%   |
| ROSA R9                      | 6         | 0.79%   |
| OpenMandriva 23.08           | 6         | 0.79%   |
| LMDE 4                       | 6         | 0.79%   |
| Fedora 37                    | 6         | 0.79%   |
| Pop!_OS 20.10                | 5         | 0.65%   |
| OpenMandriva 23.03           | 5         | 0.65%   |
| KDE neon 22.04               | 5         | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 196       | 28.74%  |
| Linux Mint    | 68        | 9.97%   |
| Fedora        | 46        | 6.74%   |
| OpenMandriva  | 45        | 6.6%    |
| ROSA          | 30        | 4.4%    |
| Manjaro       | 29        | 4.25%   |
| Pop!_OS       | 25        | 3.67%   |
| Endless       | 24        | 3.52%   |
| Debian        | 23        | 3.37%   |
| KDE neon      | 19        | 2.79%   |
| Zorin         | 17        | 2.49%   |
| Kubuntu       | 17        | 2.49%   |
| Arch          | 17        | 2.49%   |
| Xubuntu       | 16        | 2.35%   |
| Kali          | 16        | 2.35%   |
| openSUSE      | 14        | 2.05%   |
| ArcoLinux     | 10        | 1.47%   |
| Clear Linux   | 9         | 1.32%   |
| Ubuntu Unity  | 6         | 0.88%   |
| LMDE          | 6         | 0.88%   |
| SteamOS       | 4         | 0.59%   |
| EndeavourOS   | 4         | 0.59%   |
| Lubuntu       | 3         | 0.44%   |
| Elementary    | 3         | 0.44%   |
| CentOS        | 3         | 0.44%   |
| Artix         | 3         | 0.44%   |
| Void Linux    | 2         | 0.29%   |
| Parrot        | 2         | 0.29%   |
| MX            | 2         | 0.29%   |
| Mageia        | 2         | 0.29%   |
| Gentoo        | 2         | 0.29%   |
| Deepin        | 2         | 0.29%   |
| Ubuntu Studio | 1         | 0.15%   |
| Ubuntu MATE   | 1         | 0.15%   |
| Ubuntu Budgie | 1         | 0.15%   |
| TUXEDO OS     | 1         | 0.15%   |
| Rocky Linux   | 1         | 0.15%   |
| RHEL          | 1         | 0.15%   |
| Peppermint    | 1         | 0.15%   |
| Oracle Linux  | 1         | 0.15%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003         | 14        | 1.67%   |
| 5.10.14-desktop-1omv4002        | 13        | 1.55%   |
| 5.15.0-56-generic               | 11        | 1.31%   |
| 5.4.0-42-generic                | 10        | 1.19%   |
| 5.4.0-58-generic                | 8         | 0.96%   |
| 5.3.0-28-generic                | 7         | 0.84%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 7         | 0.84%   |
| 5.8.0-14-generic                | 6         | 0.72%   |
| 6.2.0-26-generic                | 5         | 0.6%    |
| 5.4.0-91-generic                | 5         | 0.6%    |
| 5.4.0-48-generic                | 5         | 0.6%    |
| 5.4.0-29-generic                | 5         | 0.6%    |
| 5.4.0-26-generic                | 5         | 0.6%    |
| 4.15.0-20-generic               | 5         | 0.6%    |
| 6.4.11-desktop-1omv2390         | 4         | 0.48%   |
| 6.2.6-desktop-1omv2390          | 4         | 0.48%   |
| 5.9.16-1-MANJARO                | 4         | 0.48%   |
| 5.4.0-90-generic                | 4         | 0.48%   |
| 5.4.0-77-generic                | 4         | 0.48%   |
| 5.4.0-73-generic                | 4         | 0.48%   |
| 5.4.0-65-generic                | 4         | 0.48%   |
| 5.4.0-47-generic                | 4         | 0.48%   |
| 5.4.0-40-generic                | 4         | 0.48%   |
| 5.4.0-19-generic                | 4         | 0.48%   |
| 5.3.0-53-generic                | 4         | 0.48%   |
| 5.15.0-52-generic               | 4         | 0.48%   |
| 5.15.0-47-generic               | 4         | 0.48%   |
| 5.13.0-28-generic               | 4         | 0.48%   |
| 5.13.0-27-generic               | 4         | 0.48%   |
| 5.11.0-41-generic               | 4         | 0.48%   |
| 5.11.0-37-generic               | 4         | 0.48%   |
| 5.0.0-37-generic                | 4         | 0.48%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 4         | 0.48%   |
| 4.19.0-8-amd64                  | 4         | 0.48%   |
| 6.4.8-desktop-2omv2390          | 3         | 0.36%   |
| 6.3.0-kali1-amd64               | 3         | 0.36%   |
| 6.2.6-76060206-generic          | 3         | 0.36%   |
| 6.2.0-34-generic                | 3         | 0.36%   |
| 6.2.0-33-generic                | 3         | 0.36%   |
| 6.2.0-20-generic                | 3         | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 111       | 14.03%  |
| 5.15.0  | 65        | 8.22%   |
| 4.15.0  | 46        | 5.82%   |
| 5.3.0   | 31        | 3.92%   |
| 5.8.0   | 30        | 3.79%   |
| 5.13.0  | 29        | 3.67%   |
| 6.2.0   | 28        | 3.54%   |
| 5.11.0  | 26        | 3.29%   |
| 5.19.0  | 24        | 3.03%   |
| 5.0.0   | 23        | 2.91%   |
| 5.10.0  | 18        | 2.28%   |
| 4.18.0  | 16        | 2.02%   |
| 5.16.7  | 14        | 1.77%   |
| 5.10.14 | 14        | 1.77%   |
| 6.1.0   | 9         | 1.14%   |
| 4.19.0  | 9         | 1.14%   |
| 6.2.6   | 7         | 0.88%   |
| 5.9.16  | 7         | 0.88%   |
| 4.9.20  | 6         | 0.76%   |
| 6.1.1   | 5         | 0.63%   |
| 5.17.5  | 5         | 0.63%   |
| 6.5.0   | 4         | 0.51%   |
| 6.4.11  | 4         | 0.51%   |
| 6.0.12  | 4         | 0.51%   |
| 6.0.0   | 4         | 0.51%   |
| 5.6.8   | 4         | 0.51%   |
| 5.18.0  | 4         | 0.51%   |
| 5.14.0  | 4         | 0.51%   |
| 4.4.0   | 4         | 0.51%   |
| 6.5.5   | 3         | 0.38%   |
| 6.4.8   | 3         | 0.38%   |
| 6.4.6   | 3         | 0.38%   |
| 6.3.0   | 3         | 0.38%   |
| 5.7.19  | 3         | 0.38%   |
| 5.16.0  | 3         | 0.38%   |
| 5.12.14 | 3         | 0.38%   |
| 5.11.12 | 3         | 0.38%   |
| 4.9.60  | 3         | 0.38%   |
| 4.9.155 | 3         | 0.38%   |
| 4.9.124 | 3         | 0.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 118       | 15.3%   |
| 5.15    | 84        | 10.89%  |
| 4.15    | 46        | 5.97%   |
| 6.2     | 45        | 5.84%   |
| 5.10    | 45        | 5.84%   |
| 5.8     | 35        | 4.54%   |
| 5.3     | 35        | 4.54%   |
| 5.13    | 33        | 4.28%   |
| 5.11    | 32        | 4.15%   |
| 5.19    | 28        | 3.63%   |
| 5.0     | 26        | 3.37%   |
| 6.1     | 25        | 3.24%   |
| 5.16    | 25        | 3.24%   |
| 6.5     | 17        | 2.2%    |
| 6.4     | 17        | 2.2%    |
| 4.18    | 17        | 2.2%    |
| 4.9     | 15        | 1.95%   |
| 6.0     | 14        | 1.82%   |
| 4.19    | 14        | 1.82%   |
| 5.9     | 12        | 1.56%   |
| 5.6     | 11        | 1.43%   |
| 5.17    | 11        | 1.43%   |
| 6.6     | 10        | 1.3%    |
| 6.3     | 9         | 1.17%   |
| 5.18    | 8         | 1.04%   |
| 5.14    | 8         | 1.04%   |
| 5.12    | 8         | 1.04%   |
| 5.7     | 6         | 0.78%   |
| 5.5     | 6         | 0.78%   |
| 4.4     | 4         | 0.52%   |
| 5.1     | 2         | 0.26%   |
| 5.2     | 1         | 0.13%   |
| 4.13    | 1         | 0.13%   |
| 4.1     | 1         | 0.13%   |
| 3.13    | 1         | 0.13%   |
| 3.10    | 1         | 0.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 631       | 96.19%  |
| i686   | 25        | 3.81%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 270       | 38.57%  |
| KDE5             | 125       | 17.86%  |
| Unknown          | 74        | 10.57%  |
| XFCE             | 71        | 10.14%  |
| X-Cinnamon       | 53        | 7.57%   |
| KDE4             | 18        | 2.57%   |
| KDE              | 18        | 2.57%   |
| Cinnamon         | 16        | 2.29%   |
| MATE             | 15        | 2.14%   |
| LXQt             | 8         | 1.14%   |
| Unity            | 6         | 0.86%   |
| i3               | 5         | 0.71%   |
| Deepin           | 4         | 0.57%   |
| Pantheon         | 3         | 0.43%   |
| GNOME Flashback  | 3         | 0.43%   |
| LXDE             | 2         | 0.29%   |
| lightdm-xsession | 2         | 0.29%   |
| GNOME Classic    | 2         | 0.29%   |
| xmonad           | 1         | 0.14%   |
| sway             | 1         | 0.14%   |
| icewm            | 1         | 0.14%   |
| Budgie           | 1         | 0.14%   |
| bspwm            | 1         | 0.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 527       | 76.93%  |
| Wayland | 109       | 15.91%  |
| Unknown | 45        | 6.57%   |
| Tty     | 4         | 0.58%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 331       | 48.04%  |
| SDDM    | 105       | 15.24%  |
| LightDM | 79        | 11.47%  |
| GDM3    | 75        | 10.89%  |
| GDM     | 61        | 8.85%   |
| TDM     | 18        | 2.61%   |
| KDM     | 17        | 2.47%   |
| XDM     | 2         | 0.29%   |
| MDM     | 1         | 0.15%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 434       | 64.01%  |
| bg_BG   | 114       | 16.81%  |
| Unknown | 85        | 12.54%  |
| en_GB   | 18        | 2.65%   |
| C       | 11        | 1.62%   |
| ru_RU   | 7         | 1.03%   |
| uk_UA   | 1         | 0.15%   |
| sv_SE   | 1         | 0.15%   |
| POSIX   | 1         | 0.15%   |
| fr_FR   | 1         | 0.15%   |
| es_ES   | 1         | 0.15%   |
| en_DK   | 1         | 0.15%   |
| en_AG   | 1         | 0.15%   |
| de_DE   | 1         | 0.15%   |
| C.UTF8  | 1         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 354       | 52.6%   |
| EFI  | 319       | 47.4%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 500       | 74.29%  |
| Btrfs   | 57        | 8.47%   |
| Overlay | 44        | 6.54%   |
| Unknown | 32        | 4.75%   |
| Tmpfs   | 21        | 3.12%   |
| Xfs     | 11        | 1.63%   |
| Zfs     | 3         | 0.45%   |
| Ext2    | 3         | 0.45%   |
| Ext3    | 2         | 0.3%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 352       | 51.92%  |
| GPT     | 237       | 34.96%  |
| MBR     | 89        | 13.13%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 580       | 87.48%  |
| Yes       | 83        | 12.52%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 472       | 70.87%  |
| Yes       | 194       | 29.13%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 188       | 28.75%  |
| Hewlett-Packard     | 115       | 17.58%  |
| Dell                | 104       | 15.9%   |
| ASUSTek Computer    | 81        | 12.39%  |
| Acer                | 66        | 10.09%  |
| Toshiba             | 32        | 4.89%   |
| MSI                 | 13        | 1.99%   |
| Apple               | 7         | 1.07%   |
| Fujitsu             | 5         | 0.76%   |
| Valve               | 4         | 0.61%   |
| Sony                | 4         | 0.61%   |
| Fujitsu Siemens     | 4         | 0.61%   |
| TUXEDO              | 3         | 0.46%   |
| Samsung Electronics | 3         | 0.46%   |
| HUAWEI              | 3         | 0.46%   |
| Gigabyte Technology | 3         | 0.46%   |
| Packard Bell        | 2         | 0.31%   |
| Medion              | 2         | 0.31%   |
| Google              | 2         | 0.31%   |
| AMI                 | 2         | 0.31%   |
| Timi                | 1         | 0.15%   |
| System76            | 1         | 0.15%   |
| Razer               | 1         | 0.15%   |
| Pegatron            | 1         | 0.15%   |
| ONDA                | 1         | 0.15%   |
| Notebook            | 1         | 0.15%   |
| LG Electronics      | 1         | 0.15%   |
| IBM                 | 1         | 0.15%   |
| Cube                | 1         | 0.15%   |
| Compal              | 1         | 0.15%   |
| Beelink             | 1         | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo G500 20236                          | 5         | 0.76%   |
| Dell Inspiron N5110                        | 5         | 0.76%   |
| Valve Jupiter                              | 4         | 0.61%   |
| HP ProBook 4540s                           | 4         | 0.61%   |
| HP ProBook 450 G8 Notebook PC              | 4         | 0.61%   |
| ASUS X541NA                                | 4         | 0.61%   |
| Unknown                                    | 4         | 0.61%   |
| Lenovo Y520-15IKBN 80WK                    | 3         | 0.46%   |
| HP ProBook 450 G0                          | 3         | 0.46%   |
| HP Pavilion 15                             | 3         | 0.46%   |
| HP Notebook                                | 3         | 0.46%   |
| Dell Precision M4600                       | 3         | 0.46%   |
| Dell Latitude E6410                        | 3         | 0.46%   |
| Dell Latitude E4300                        | 3         | 0.46%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X540MA | 3         | 0.46%   |
| ASUS N551VW                                | 3         | 0.46%   |
| Acer Aspire 5738                           | 3         | 0.46%   |
| Toshiba Satellite L300                     | 2         | 0.31%   |
| Toshiba Satellite C50-A-19T                | 2         | 0.31%   |
| Toshiba Satellite A300                     | 2         | 0.31%   |
| Toshiba Satellite A200                     | 2         | 0.31%   |
| Samsung 300E4Z/300E5Z/300E7Z               | 2         | 0.31%   |
| MSI Modern 15 A5M                          | 2         | 0.31%   |
| Lenovo Yoga S740-14IIL 81RS                | 2         | 0.31%   |
| Lenovo ThinkPad X220 4291IR6               | 2         | 0.31%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS1D900   | 2         | 0.31%   |
| Lenovo ThinkPad T460 20FN003LUK            | 2         | 0.31%   |
| Lenovo ThinkPad T420 4236A87               | 2         | 0.31%   |
| Lenovo ThinkPad T14 Gen 1 20S0000NBM       | 2         | 0.31%   |
| Lenovo ThinkPad L590 20Q700AWBM            | 2         | 0.31%   |
| Lenovo ThinkPad E480 20KN005CBM            | 2         | 0.31%   |
| Lenovo ThinkPad E15 Gen 4 21E6006WBM       | 2         | 0.31%   |
| Lenovo ThinkBook 15 G2 ITL 20VE            | 2         | 0.31%   |
| Lenovo ThinkBook 13s-IML 20RR              | 2         | 0.31%   |
| Lenovo Legion Y740-17IRHg 81UJ             | 2         | 0.31%   |
| Lenovo Legion 5 15ARH05 82B5               | 2         | 0.31%   |
| Lenovo IdeaPad Y510P 20217                 | 2         | 0.31%   |
| Lenovo IdeaPad Y500 20193                  | 2         | 0.31%   |
| Lenovo IdeaPad S540-14API 81NH             | 2         | 0.31%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY       | 2         | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 95        | 14.53%  |
| Acer Aspire           | 47        | 7.19%   |
| Lenovo IdeaPad        | 36        | 5.5%    |
| Dell Latitude         | 36        | 5.5%    |
| HP ProBook            | 33        | 5.05%   |
| Dell Inspiron         | 30        | 4.59%   |
| Toshiba Satellite     | 26        | 3.98%   |
| HP EliteBook          | 22        | 3.36%   |
| HP Pavilion           | 21        | 3.21%   |
| ASUS VivoBook         | 21        | 3.21%   |
| Dell Vostro           | 13        | 1.99%   |
| Lenovo Legion         | 12        | 1.83%   |
| Dell Precision        | 12        | 1.83%   |
| HP Compaq             | 9         | 1.38%   |
| ASUS ROG              | 7         | 1.07%   |
| Lenovo Yoga           | 6         | 0.92%   |
| HP Laptop             | 6         | 0.92%   |
| Acer Nitro            | 6         | 0.92%   |
| MSI Modern            | 5         | 0.76%   |
| Lenovo ThinkBook      | 5         | 0.76%   |
| Lenovo G500           | 5         | 0.76%   |
| ASUS ASUS             | 5         | 0.76%   |
| Valve Jupiter         | 4         | 0.61%   |
| Lenovo V15            | 4         | 0.61%   |
| HP 255                | 4         | 0.61%   |
| HP 250                | 4         | 0.61%   |
| Dell XPS              | 4         | 0.61%   |
| ASUS ZenBook          | 4         | 0.61%   |
| ASUS X541NA           | 4         | 0.61%   |
| Unknown               | 4         | 0.61%   |
| MSI GF63              | 3         | 0.46%   |
| Lenovo Y520-15IKBN    | 3         | 0.46%   |
| HP ZBook              | 3         | 0.46%   |
| HP Notebook           | 3         | 0.46%   |
| Fujitsu Siemens AMILO | 3         | 0.46%   |
| Fujitsu LIFEBOOK      | 3         | 0.46%   |
| Dell Studio           | 3         | 0.46%   |
| ASUS TUF              | 3         | 0.46%   |
| ASUS N551VW           | 3         | 0.46%   |
| Acer TravelMate       | 3         | 0.46%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 62        | 9.48%   |
| 2012 | 57        | 8.72%   |
| 2011 | 55        | 8.41%   |
| 2017 | 50        | 7.65%   |
| 2019 | 49        | 7.49%   |
| 2021 | 44        | 6.73%   |
| 2013 | 44        | 6.73%   |
| 2018 | 43        | 6.57%   |
| 2022 | 38        | 5.81%   |
| 2014 | 38        | 5.81%   |
| 2015 | 37        | 5.66%   |
| 2010 | 34        | 5.2%    |
| 2008 | 34        | 5.2%    |
| 2009 | 22        | 3.36%   |
| 2016 | 19        | 2.91%   |
| 2007 | 12        | 1.83%   |
| 2023 | 8         | 1.22%   |
| 2006 | 6         | 0.92%   |
| 2004 | 2         | 0.31%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 654       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 609       | 92.55%  |
| Enabled  | 49        | 7.45%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 650       | 99.39%  |
| Yes  | 4         | 0.61%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 192       | 28.74%  |
| 3.01-4.0    | 136       | 20.36%  |
| 8.01-16.0   | 135       | 20.21%  |
| 16.01-24.0  | 92        | 13.77%  |
| 32.01-64.0  | 53        | 7.93%   |
| 1.01-2.0    | 20        | 2.99%   |
| 2.01-3.0    | 16        | 2.4%    |
| 24.01-32.0  | 13        | 1.95%   |
| 64.01-256.0 | 8         | 1.2%    |
| 0.51-1.0    | 3         | 0.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 231       | 30.76%  |
| 2.01-3.0   | 212       | 28.23%  |
| 4.01-8.0   | 112       | 14.91%  |
| 3.01-4.0   | 108       | 14.38%  |
| 0.51-1.0   | 45        | 5.99%   |
| 8.01-16.0  | 34        | 4.53%   |
| 16.01-24.0 | 4         | 0.53%   |
| 0.01-0.5   | 3         | 0.4%    |
| 32.01-64.0 | 1         | 0.13%   |
| Unknown    | 1         | 0.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 490       | 73.03%  |
| 2      | 158       | 23.55%  |
| 3      | 15        | 2.24%   |
| 0      | 6         | 0.89%   |
| 5      | 1         | 0.15%   |
| 4      | 1         | 0.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 409       | 62.06%  |
| Yes       | 250       | 37.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 565       | 85.87%  |
| No        | 93        | 14.13%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 648       | 99.08%  |
| No        | 6         | 0.92%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 513       | 77.49%  |
| No        | 149       | 22.51%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Bulgaria | 654       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Sofia               | 362       | 52.01%  |
| Varna               | 57        | 8.19%   |
| Plovdiv             | 45        | 6.47%   |
| Burgas              | 35        | 5.03%   |
| Stara Zagora        | 13        | 1.87%   |
| Pernik              | 10        | 1.44%   |
| Yambol              | 8         | 1.15%   |
| Pleven              | 8         | 1.15%   |
| Veliko Tarnovo      | 7         | 1.01%   |
| Rousse              | 7         | 1.01%   |
| Montana             | 7         | 1.01%   |
| Haskovo             | 6         | 0.86%   |
| Gabrovo             | 6         | 0.86%   |
| Svilengrad          | 5         | 0.72%   |
| Shumen              | 5         | 0.72%   |
| Kazanlak            | 5         | 0.72%   |
| Dobrich             | 5         | 0.72%   |
| Blagoevgrad         | 5         | 0.72%   |
| Pazardzhik          | 4         | 0.57%   |
| Asenovgrad          | 4         | 0.57%   |
| Vidin               | 3         | 0.43%   |
| Razgrad             | 3         | 0.43%   |
| Vratsa              | 2         | 0.29%   |
| Troyan Municipality | 2         | 0.29%   |
| Svoge               | 2         | 0.29%   |
| Smolyan             | 2         | 0.29%   |
| Sliven              | 2         | 0.29%   |
| Sistov              | 2         | 0.29%   |
| Silistra            | 2         | 0.29%   |
| Sevlievo            | 2         | 0.29%   |
| Nesebar             | 2         | 0.29%   |
| Kyustendil          | 2         | 0.29%   |
| Karlovo             | 2         | 0.29%   |
| Kardzhali           | 2         | 0.29%   |
| Gorna Oryahovitsa   | 2         | 0.29%   |
| Zlatia              | 1         | 0.14%   |
| Voluyak             | 1         | 0.14%   |
| Velingrad           | 1         | 0.14%   |
| Trastenik           | 1         | 0.14%   |
| Topuzevo            | 1         | 0.14%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 127       | 193    | 15.6%   |
| Seagate                        | 91        | 117    | 11.18%  |
| WDC                            | 88        | 120    | 10.81%  |
| Toshiba                        | 75        | 100    | 9.21%   |
| SanDisk                        | 45        | 58     | 5.53%   |
| Kingston                       | 40        | 56     | 4.91%   |
| Unknown                        | 39        | 49     | 4.79%   |
| SK hynix                       | 33        | 42     | 4.05%   |
| HGST                           | 33        | 48     | 4.05%   |
| Intel                          | 32        | 46     | 3.93%   |
| Hitachi                        | 31        | 33     | 3.81%   |
| A-DATA Technology              | 23        | 32     | 2.83%   |
| Micron Technology              | 21        | 25     | 2.58%   |
| Crucial                        | 12        | 16     | 1.47%   |
| Transcend                      | 11        | 11     | 1.35%   |
| KIOXIA                         | 11        | 12     | 1.35%   |
| Fujitsu                        | 9         | 12     | 1.11%   |
| SPCC                           | 7         | 10     | 0.86%   |
| KingSpec                       | 7         | 8      | 0.86%   |
| PNY                            | 6         | 6      | 0.74%   |
| Phison Electronics             | 6         | 8      | 0.74%   |
| China                          | 6         | 8      | 0.74%   |
| Team                           | 5         | 5      | 0.61%   |
| LITEON                         | 5         | 7      | 0.61%   |
| Kingston Technology Company    | 5         | 5      | 0.61%   |
| LITEONIT                       | 4         | 4      | 0.49%   |
| Apple                          | 4         | 6      | 0.49%   |
| Silicon Motion                 | 3         | 3      | 0.37%   |
| Union Memory (Shenzhen)        | 2         | 2      | 0.25%   |
| TO Exter                       | 2         | 2      | 0.25%   |
| Teclast                        | 2         | 2      | 0.25%   |
| Realtek                        | 2         | 2      | 0.25%   |
| Patriot                        | 2         | 2      | 0.25%   |
| Lexar                          | 2         | 2      | 0.25%   |
| JMicron Technology             | 2         | 2      | 0.25%   |
| Intenso                        | 2         | 2      | 0.25%   |
| GOODRAM                        | 2         | 2      | 0.25%   |
| Verbatim                       | 1         | 1      | 0.12%   |
| Solid State Storage Technology | 1         | 1      | 0.12%   |
| Realtek Semiconductor          | 1         | 2      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 19        | 2.23%   |
| Toshiba MQ01ABF050 500GB                            | 14        | 1.65%   |
| Toshiba MQ01ABD100 1TB                              | 14        | 1.65%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 14        | 1.65%   |
| HGST HTS721010A9E630 1TB                            | 13        | 1.53%   |
| Samsung NVMe SSD Drive 512GB                        | 11        | 1.29%   |
| Samsung SSD 860 EVO 250GB                           | 9         | 1.06%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 9         | 1.06%   |
| Unknown MMC Card  32GB                              | 8         | 0.94%   |
| Kingston SA400S37240G 240GB SSD                     | 8         | 0.94%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 7         | 0.82%   |
| Unknown MMC Card  64GB                              | 7         | 0.82%   |
| SanDisk NVMe SSD Drive 512GB                        | 7         | 0.82%   |
| Samsung SSD 860 EVO 500GB                           | 7         | 0.82%   |
| HGST HTS541010A9E680 1TB                            | 7         | 0.82%   |
| Samsung SSD 850 EVO 250GB                           | 6         | 0.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 6         | 0.71%   |
| Kingston SA400S37120G 120GB SSD                     | 6         | 0.71%   |
| Toshiba NVMe SSD Drive 256GB                        | 5         | 0.59%   |
| Toshiba MQ04ABF100 1TB                              | 5         | 0.59%   |
| Seagate ST9500325AS 500GB                           | 5         | 0.59%   |
| SanDisk NVMe SSD Drive 256GB                        | 5         | 0.59%   |
| Samsung NVMe SSD Drive 1024GB                       | 5         | 0.59%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 4         | 0.47%   |
| Toshiba MQ01ABD075 752GB                            | 4         | 0.47%   |
| SK hynix NVMe SSD Drive 256GB                       | 4         | 0.47%   |
| Seagate ST9750420AS 752GB                           | 4         | 0.47%   |
| Seagate ST500LT012-1DG142 500GB                     | 4         | 0.47%   |
| Seagate ST1000LM048-2E7172 1TB                      | 4         | 0.47%   |
| Phison PS5013 E13 NVMe Controller 512GB             | 4         | 0.47%   |
| Kingston NVMe SSD Drive 512GB                       | 4         | 0.47%   |
| Intel NVMe SSD Drive 512GB                          | 4         | 0.47%   |
| Hitachi HTS547575A9E384 752GB                       | 4         | 0.47%   |
| HGST HTS545050A7E680 500GB                          | 4         | 0.47%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 3         | 0.35%   |
| WDC WD5000LPVX-75V0TT0 500GB                        | 3         | 0.35%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 3         | 0.35%   |
| Unknown SD/MMC/MS PRO 512GB                         | 3         | 0.35%   |
| Unknown MMC Card  16GB                              | 3         | 0.35%   |
| SPCC Solid State Disk 512GB                         | 3         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 89        | 115    | 29.87%  |
| WDC                 | 71        | 92     | 23.83%  |
| Toshiba             | 57        | 73     | 19.13%  |
| HGST                | 33        | 48     | 11.07%  |
| Hitachi             | 31        | 33     | 10.4%   |
| Fujitsu             | 9         | 12     | 3.02%   |
| Unknown             | 3         | 4      | 1.01%   |
| TO Exter            | 2         | 2      | 0.67%   |
| Samsung Electronics | 2         | 3      | 0.67%   |
| IBM/Hitachi         | 1         | 2      | 0.34%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 55        | 68     | 23.4%   |
| Kingston            | 24        | 28     | 10.21%  |
| SanDisk             | 22        | 27     | 9.36%   |
| A-DATA Technology   | 18        | 27     | 7.66%   |
| WDC                 | 13        | 20     | 5.53%   |
| Crucial             | 10        | 13     | 4.26%   |
| Transcend           | 9         | 9      | 3.83%   |
| Intel               | 8         | 11     | 3.4%    |
| KingSpec            | 7         | 8      | 2.98%   |
| SPCC                | 6         | 9      | 2.55%   |
| PNY                 | 6         | 6      | 2.55%   |
| China               | 6         | 8      | 2.55%   |
| Toshiba             | 5         | 6      | 2.13%   |
| Team                | 5         | 5      | 2.13%   |
| Micron Technology   | 5         | 6      | 2.13%   |
| LITEON              | 5         | 7      | 2.13%   |
| LITEONIT            | 4         | 4      | 1.7%    |
| Apple               | 3         | 5      | 1.28%   |
| Teclast             | 2         | 2      | 0.85%   |
| SK hynix            | 2         | 2      | 0.85%   |
| Patriot             | 2         | 2      | 0.85%   |
| Lexar               | 2         | 2      | 0.85%   |
| JMicron Technology  | 2         | 2      | 0.85%   |
| Intenso             | 2         | 2      | 0.85%   |
| GOODRAM             | 2         | 2      | 0.85%   |
| Verbatim            | 1         | 1      | 0.43%   |
| Unknown             | 1         | 1      | 0.43%   |
| Seagate             | 1         | 1      | 0.43%   |
| Netac               | 1         | 4      | 0.43%   |
| FORESEE             | 1         | 2      | 0.43%   |
| EDGE                | 1         | 1      | 0.43%   |
| ASMT                | 1         | 1      | 0.43%   |
| AMD                 | 1         | 2      | 0.43%   |
| ADATA SU            | 1         | 1      | 0.43%   |
| Unknown             | 1         | 1      | 0.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 288       | 384    | 36.88%  |
| NVMe    | 233       | 356    | 29.83%  |
| SSD     | 223       | 296    | 28.55%  |
| MMC     | 33        | 42     | 4.23%   |
| Unknown | 4         | 3      | 0.51%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 442       | 656    | 60.22%  |
| NVMe | 232       | 354    | 31.61%  |
| MMC  | 33        | 42     | 4.5%    |
| SAS  | 27        | 29     | 3.68%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 322       | 434    | 64.53%  |
| 0.51-1.0   | 167       | 235    | 33.47%  |
| 1.01-2.0   | 9         | 10     | 1.8%    |
| 4.01-10.0  | 1         | 1      | 0.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 180       | 25.97%  |
| 101-250        | 180       | 25.97%  |
| 501-1000       | 120       | 17.32%  |
| 1-20           | 53        | 7.65%   |
| 1001-2000      | 49        | 7.07%   |
| 51-100         | 47        | 6.78%   |
| 21-50          | 36        | 5.19%   |
| Unknown        | 13        | 1.88%   |
| More than 3000 | 11        | 1.59%   |
| 2001-3000      | 4         | 0.58%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 277       | 37.08%  |
| 21-50          | 134       | 17.94%  |
| 101-250        | 109       | 14.59%  |
| 51-100         | 94        | 12.58%  |
| 251-500        | 63        | 8.43%   |
| 501-1000       | 39        | 5.22%   |
| Unknown        | 13        | 1.74%   |
| 1001-2000      | 12        | 1.61%   |
| 2001-3000      | 4         | 0.54%   |
| More than 3000 | 2         | 0.27%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                          | Notebooks | Drives | Percent |
|----------------------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                                      | 3         | 3      | 6.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                             | 3         | 3      | 6.52%   |
| Toshiba MQ01ABF050 500GB                                       | 2         | 2      | 4.35%   |
| Intel SSDSC2CW120A3 120GB                                      | 2         | 2      | 4.35%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                                 | 1         | 1      | 2.17%   |
| WDC WD6000HLHX-01JJPV0 600GB                                   | 1         | 1      | 2.17%   |
| WDC WD5000LPVX-55V0TT0 500GB                                   | 1         | 1      | 2.17%   |
| WDC WD5000BEVT-75A0RT0 500GB                                   | 1         | 1      | 2.17%   |
| WDC WD3200BEVT-80A0RT0 320GB                                   | 1         | 1      | 2.17%   |
| WDC WD1600BEVT-80A23T0 160GB                                   | 1         | 1      | 2.17%   |
| Toshiba MQ01ABD100 1TB                                         | 1         | 1      | 2.17%   |
| Toshiba MQ01ABD050 500GB                                       | 1         | 1      | 2.17%   |
| Toshiba MK2552GSX 250GB                                        | 1         | 3      | 2.17%   |
| Toshiba MK2035GSS 200GB                                        | 1         | 1      | 2.17%   |
| Toshiba MK1637GSX 160GB                                        | 1         | 1      | 2.17%   |
| SPCC M.2 PCIe SSD 256GB                                        | 1         | 1      | 2.17%   |
| Seagate ST9500420AS 500GB                                      | 1         | 2      | 2.17%   |
| Seagate ST94019A 40GB                                          | 1         | 1      | 2.17%   |
| Seagate ST500LT012-9WS142 500GB                                | 1         | 1      | 2.17%   |
| Seagate ST500LT012-1DG142 500GB                                | 1         | 1      | 2.17%   |
| Seagate ST500LM021-1KJ152 500GB                                | 1         | 1      | 2.17%   |
| Seagate ST500LM000-1EJ162 500GB                                | 1         | 1      | 2.17%   |
| Seagate ST1000LM035-1RK172 1TB                                 | 1         | 1      | 2.17%   |
| Seagate ST1000LM014-1EJ164 1TB                                 | 1         | 1      | 2.17%   |
| Samsung Electronics NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 1         | 1      | 2.17%   |
| KingSpec P3-256 256GB SSD                                      | 1         | 1      | 2.17%   |
| KingSpec P3-128 128GB SSD                                      | 1         | 1      | 2.17%   |
| Hitachi HTS723216L9A360 160GB                                  | 1         | 1      | 2.17%   |
| Hitachi HTS547550A9E384 500GB                                  | 1         | 1      | 2.17%   |
| Hitachi HTS545050A7E380 500GB                                  | 1         | 1      | 2.17%   |
| Hitachi HTS543225L9SA00 250GB                                  | 1         | 2      | 2.17%   |
| Hitachi HTS543225L9A300 250GB                                  | 1         | 1      | 2.17%   |
| Hitachi HTS543216L9SA00 160GB                                  | 1         | 1      | 2.17%   |
| Hitachi HTS542525K9SA00 250GB                                  | 1         | 1      | 2.17%   |
| Hitachi HTS541616J9SA00 160GB                                  | 1         | 1      | 2.17%   |
| HGST HTS721010A9E630 1TB                                       | 1         | 1      | 2.17%   |
| Fujitsu MJA2160BH G2 160GB                                     | 1         | 2      | 2.17%   |
| A-DATA Technology SX300 64GB SSD                               | 1         | 1      | 2.17%   |
| A-DATA Technology SU650 480GB SSD                              | 1         | 1      | 2.17%   |
| A-DATA Technology SU650 120GB SSD                              | 1         | 1      | 2.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 15     | 30.43%  |
| Hitachi             | 8         | 9      | 17.39%  |
| Toshiba             | 7         | 9      | 15.22%  |
| WDC                 | 6         | 6      | 13.04%  |
| A-DATA Technology   | 3         | 3      | 6.52%   |
| KingSpec            | 2         | 2      | 4.35%   |
| Intel               | 2         | 2      | 4.35%   |
| SPCC                | 1         | 1      | 2.17%   |
| Samsung Electronics | 1         | 1      | 2.17%   |
| HGST                | 1         | 1      | 2.17%   |
| Fujitsu             | 1         | 2      | 2.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 14        | 15     | 38.89%  |
| Hitachi | 8         | 9      | 22.22%  |
| Toshiba | 7         | 9      | 19.44%  |
| WDC     | 5         | 5      | 13.89%  |
| HGST    | 1         | 1      | 2.78%   |
| Fujitsu | 1         | 2      | 2.78%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 35        | 41     | 77.78%  |
| SSD  | 8         | 8      | 17.78%  |
| NVMe | 2         | 2      | 4.44%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                        | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD1600BEKT-75PVMT0 160GB | 1         | 1      | 50%     |
| HGST HTS545050A7E680 500GB   | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 50%     |
| HGST   | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 401       | 655    | 57.86%  |
| Works    | 246       | 373    | 35.5%   |
| Malfunc  | 44        | 51     | 6.35%   |
| Failed   | 2         | 2      | 0.29%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 479       | 62.13%  |
| Samsung Electronics              | 79        | 10.25%  |
| AMD                              | 58        | 7.52%   |
| SK hynix                         | 31        | 4.02%   |
| SanDisk                          | 30        | 3.89%   |
| Kingston Technology Company      | 20        | 2.59%   |
| Micron Technology                | 16        | 2.08%   |
| KIOXIA                           | 13        | 1.69%   |
| Toshiba America Info Systems     | 12        | 1.56%   |
| Phison Electronics               | 7         | 0.91%   |
| Realtek Semiconductor            | 6         | 0.78%   |
| Silicon Motion                   | 4         | 0.52%   |
| Micron/Crucial Technology        | 3         | 0.39%   |
| Union Memory (Shenzhen)          | 2         | 0.26%   |
| Transcend                        | 2         | 0.26%   |
| VIA Technologies                 | 1         | 0.13%   |
| Solid State Storage Technology   | 1         | 0.13%   |
| Silicon Integrated Systems [SiS] | 1         | 0.13%   |
| O2 Micro                         | 1         | 0.13%   |
| Nvidia                           | 1         | 0.13%   |
| Marvell Technology Group         | 1         | 0.13%   |
| Lenovo                           | 1         | 0.13%   |
| Apple                            | 1         | 0.13%   |
| ADATA Technology                 | 1         | 0.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 64        | 7.67%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 46        | 5.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 41        | 4.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 39        | 4.68%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 35        | 4.2%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 34        | 4.08%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 33        | 3.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 26        | 3.12%   |
| Intel Volume Management Device NVMe RAID Controller                              | 26        | 3.12%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 24        | 2.88%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 20        | 2.4%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 18        | 2.16%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 17        | 2.04%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 17        | 2.04%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 15        | 1.8%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 13        | 1.56%   |
| Intel Tiger Lake-LP SATA Controller                                              | 12        | 1.44%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 12        | 1.44%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 11        | 1.32%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 11        | 1.32%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 9         | 1.08%   |
| Intel SSD 660P Series                                                            | 9         | 1.08%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 9         | 1.08%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 8         | 0.96%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                    | 8         | 0.96%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                 | 8         | 0.96%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 7         | 0.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 7         | 0.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 7         | 0.84%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 7         | 0.84%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 6         | 0.72%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 6         | 0.72%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 6         | 0.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 6         | 0.72%   |
| Intel Alder Lake-P SATA AHCI Controller                                          | 6         | 0.72%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 6         | 0.72%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 6         | 0.72%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 5         | 0.6%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 5         | 0.6%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 5         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 447       | 56.02%  |
| NVMe | 236       | 29.57%  |
| RAID | 60        | 7.52%   |
| IDE  | 55        | 6.89%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 543       | 83.03%  |
| AMD          | 110       | 16.82%  |
| CentaurHauls | 1         | 0.15%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 13        | 1.99%   |
| Intel Core i5-3230M CPU @ 2.60GHz        | 12        | 1.83%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz       | 10        | 1.53%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 10        | 1.53%   |
| Intel Core i7-8750H CPU @ 2.20GHz        | 9         | 1.38%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz       | 9         | 1.38%   |
| Intel Core i7-10510U CPU @ 1.80GHz       | 9         | 1.38%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 8         | 1.22%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 8         | 1.22%   |
| Intel Pentium CPU N4200 @ 1.10GHz        | 7         | 1.07%   |
| Intel Core i5-8265U CPU @ 1.60GHz        | 7         | 1.07%   |
| Intel Core i5-3210M CPU @ 2.50GHz        | 7         | 1.07%   |
| Intel Core i5-2410M CPU @ 2.30GHz        | 7         | 1.07%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 6         | 0.92%   |
| Intel Core i7-3630QM CPU @ 2.40GHz       | 6         | 0.92%   |
| Intel Core i7-2670QM CPU @ 2.20GHz       | 6         | 0.92%   |
| Intel Core i7-10750H CPU @ 2.60GHz       | 6         | 0.92%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 6         | 0.92%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 6         | 0.92%   |
| Intel Core i3 CPU M 370 @ 2.40GHz        | 6         | 0.92%   |
| Intel Celeron N4000 CPU @ 1.10GHz        | 6         | 0.92%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 6         | 0.92%   |
| AMD Ryzen 7 4800H with Radeon Graphics   | 6         | 0.92%   |
| AMD Ryzen 5 5500U with Radeon Graphics   | 6         | 0.92%   |
| AMD Ryzen 3 3250U with Radeon Graphics   | 6         | 0.92%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 5         | 0.76%   |
| Intel Pentium CPU 2020M @ 2.40GHz        | 5         | 0.76%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 5         | 0.76%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz       | 5         | 0.76%   |
| Intel Core i7-3632QM CPU @ 2.20GHz       | 5         | 0.76%   |
| Intel Core i5 CPU M 520 @ 2.40GHz        | 5         | 0.76%   |
| Intel Core i3-5005U CPU @ 2.00GHz        | 5         | 0.76%   |
| Intel Core i3-3110M CPU @ 2.40GHz        | 5         | 0.76%   |
| Intel Core i3-2310M CPU @ 2.10GHz        | 5         | 0.76%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz     | 5         | 0.76%   |
| Intel 12th Gen Core i5-1235U             | 5         | 0.76%   |
| AMD Ryzen 7 6800H with Radeon Graphics   | 5         | 0.76%   |
| AMD Ryzen 7 5700U with Radeon Graphics   | 5         | 0.76%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 4         | 0.61%   |
| Intel Core i7-5600U CPU @ 2.60GHz        | 4         | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 156       | 23.85%  |
| Intel Core i5           | 137       | 20.95%  |
| Other                   | 57        | 8.72%   |
| Intel Core i3           | 51        | 7.8%    |
| Intel Core 2 Duo        | 38        | 5.81%   |
| AMD Ryzen 7             | 37        | 5.66%   |
| Intel Celeron           | 30        | 4.59%   |
| Intel Pentium           | 28        | 4.28%   |
| AMD Ryzen 5             | 24        | 3.67%   |
| Intel Atom              | 11        | 1.68%   |
| AMD Ryzen 3             | 9         | 1.38%   |
| Intel Pentium Dual-Core | 7         | 1.07%   |
| AMD Ryzen 7 PRO         | 7         | 1.07%   |
| Intel Pentium Silver    | 6         | 0.92%   |
| Intel Pentium Dual      | 6         | 0.92%   |
| Intel Core 2            | 5         | 0.76%   |
| AMD Ryzen 5 PRO         | 5         | 0.76%   |
| AMD A6                  | 5         | 0.76%   |
| Intel Genuine           | 3         | 0.46%   |
| AMD E                   | 3         | 0.46%   |
| Intel Pentium M         | 2         | 0.31%   |
| Intel Core i9           | 2         | 0.31%   |
| Intel Celeron Dual-Core | 2         | 0.31%   |
| AMD Turion 64 X2 Mobile | 2         | 0.31%   |
| AMD Ryzen 9             | 2         | 0.31%   |
| AMD E1                  | 2         | 0.31%   |
| Intel Xeon              | 1         | 0.15%   |
| Intel Mobile Pentium 4  | 1         | 0.15%   |
| Intel Core m3           | 1         | 0.15%   |
| Intel Core M            | 1         | 0.15%   |
| Intel Core Duo          | 1         | 0.15%   |
| Intel Core 2 Solo       | 1         | 0.15%   |
| Intel Celeron M         | 1         | 0.15%   |
| CentaurHauls VIA Nano   | 1         | 0.15%   |
| AMD Turion 64 Mobile    | 1         | 0.15%   |
| AMD Sempron             | 1         | 0.15%   |
| AMD Phenom II           | 1         | 0.15%   |
| AMD FX                  | 1         | 0.15%   |
| AMD E2                  | 1         | 0.15%   |
| AMD C-50                | 1         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 316       | 48.24%  |
| 4       | 202       | 30.84%  |
| 6       | 53        | 8.09%   |
| 8       | 48        | 7.33%   |
| 1       | 17        | 2.6%    |
| 10      | 9         | 1.37%   |
| 12      | 4         | 0.61%   |
| 14      | 3         | 0.46%   |
| 24      | 1         | 0.15%   |
| 3       | 1         | 0.15%   |
| Unknown | 1         | 0.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 654       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 483       | 73.74%  |
| 1       | 170       | 25.95%  |
| 4       | 1         | 0.15%   |
| Unknown | 1         | 0.15%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 630       | 95.74%  |
| Unknown        | 17        | 2.58%   |
| 32-bit         | 11        | 1.67%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 195       | 28.18%  |
| 0x306a9    | 48        | 6.94%   |
| 0x206a7    | 44        | 6.36%   |
| 0x1067a    | 24        | 3.47%   |
| 0x806ec    | 23        | 3.32%   |
| 0x306d4    | 23        | 3.32%   |
| 0x306c3    | 20        | 2.89%   |
| 0x406e3    | 17        | 2.46%   |
| 0x20655    | 17        | 2.46%   |
| 0x906ea    | 16        | 2.31%   |
| 0x806c1    | 16        | 2.31%   |
| 0x40651    | 16        | 2.31%   |
| 0x806ea    | 14        | 2.02%   |
| 0x6fd      | 13        | 1.88%   |
| 0x906e9    | 12        | 1.73%   |
| 0x706a1    | 10        | 1.45%   |
| 0x506e3    | 10        | 1.45%   |
| 0x506c9    | 10        | 1.45%   |
| 0x10676    | 10        | 1.45%   |
| 0x806e9    | 8         | 1.16%   |
| 0x0a50000c | 8         | 1.16%   |
| 0x08108109 | 8         | 1.16%   |
| 0x08608103 | 7         | 1.01%   |
| 0x08108102 | 7         | 1.01%   |
| 0xa0652    | 6         | 0.87%   |
| 0x806eb    | 6         | 0.87%   |
| 0x406c3    | 6         | 0.87%   |
| 0x0a50000d | 6         | 0.87%   |
| 0x906a4    | 5         | 0.72%   |
| 0x706e5    | 5         | 0.72%   |
| 0x08600106 | 5         | 0.72%   |
| 0x08600104 | 5         | 0.72%   |
| 0x906a3    | 4         | 0.58%   |
| 0x6f6      | 4         | 0.58%   |
| 0x106c2    | 4         | 0.58%   |
| 0x0a404102 | 4         | 0.58%   |
| 0x906ed    | 3         | 0.43%   |
| 0x806d1    | 3         | 0.43%   |
| 0x106e5    | 3         | 0.43%   |
| 0x08600103 | 3         | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 103       | 15.73%  |
| IvyBridge        | 68        | 10.38%  |
| SandyBridge      | 54        | 8.24%   |
| Haswell          | 47        | 7.18%   |
| Penryn           | 39        | 5.95%   |
| Unknown          | 37        | 5.65%   |
| Skylake          | 31        | 4.73%   |
| TigerLake        | 28        | 4.27%   |
| Broadwell        | 28        | 4.27%   |
| Westmere         | 24        | 3.66%   |
| Core             | 23        | 3.51%   |
| Zen 3            | 21        | 3.21%   |
| Zen 2            | 20        | 3.05%   |
| Zen+             | 17        | 2.6%    |
| Silvermont       | 16        | 2.44%   |
| Alderlake Hybrid | 16        | 2.44%   |
| Goldmont plus    | 13        | 1.98%   |
| Goldmont         | 12        | 1.83%   |
| CometLake        | 10        | 1.53%   |
| Icelake          | 9         | 1.37%   |
| Bonnell          | 6         | 0.92%   |
| P6               | 5         | 0.76%   |
| Excavator        | 5         | 0.76%   |
| Bobcat           | 4         | 0.61%   |
| Nehalem          | 3         | 0.46%   |
| K8 Hammer        | 3         | 0.46%   |
| Piledriver       | 2         | 0.31%   |
| K10              | 2         | 0.31%   |
| Jaguar           | 2         | 0.31%   |
| Zen              | 1         | 0.15%   |
| Tremont          | 1         | 0.15%   |
| Steamroller      | 1         | 0.15%   |
| Puma             | 1         | 0.15%   |
| NetBurst         | 1         | 0.15%   |
| K8 & K10 hybrid  | 1         | 0.15%   |
| K10 Llano        | 1         | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 487       | 55.28%  |
| Nvidia                           | 220       | 24.97%  |
| AMD                              | 172       | 19.52%  |
| VIA Technologies                 | 1         | 0.11%   |
| Silicon Integrated Systems [SiS] | 1         | 0.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 61        | 6.73%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 47        | 5.19%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 28        | 3.09%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 26        | 2.87%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 25        | 2.76%   |
| Intel HD Graphics 5500                                                                   | 25        | 2.76%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 25        | 2.76%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 20        | 2.21%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 19        | 2.1%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 18        | 1.99%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 18        | 1.99%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 17        | 1.88%   |
| Intel Core Processor Integrated Graphics Controller                                      | 16        | 1.77%   |
| Intel UHD Graphics 620                                                                   | 15        | 1.66%   |
| Intel HD Graphics 630                                                                    | 15        | 1.66%   |
| Intel HD Graphics 620                                                                    | 13        | 1.43%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 13        | 1.43%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 12        | 1.32%   |
| AMD Lucienne                                                                             | 11        | 1.21%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 10        | 1.1%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 10        | 1.1%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 10        | 1.1%    |
| Intel HD Graphics 530                                                                    | 10        | 1.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10        | 1.1%    |
| AMD Rembrandt [Radeon 680M]                                                              | 10        | 1.1%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 9         | 0.99%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 9         | 0.99%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 9         | 0.99%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 8         | 0.88%   |
| Nvidia GM108M [GeForce 840M]                                                             | 8         | 0.88%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 0.88%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 8         | 0.88%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 7         | 0.77%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 7         | 0.77%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 7         | 0.77%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 7         | 0.77%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 6         | 0.66%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 6         | 0.66%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 0.66%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 6         | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 281       | 42.58%  |
| Intel + Nvidia | 171       | 25.91%  |
| 1 x AMD        | 108       | 16.36%  |
| Intel + AMD    | 35        | 5.3%    |
| 1 x Nvidia     | 30        | 4.55%   |
| AMD + Nvidia   | 21        | 3.18%   |
| 2 x AMD        | 9         | 1.36%   |
| 2 x Intel      | 2         | 0.3%    |
| Other          | 1         | 0.15%   |
| 1 x VIA        | 1         | 0.15%   |
| 1 x SiS        | 1         | 0.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 541       | 81.11%  |
| Proprietary | 101       | 15.14%  |
| Unknown     | 25        | 3.75%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 410       | 60.21%  |
| 1.01-2.0   | 98        | 14.39%  |
| 0.01-0.5   | 70        | 10.28%  |
| 3.01-4.0   | 42        | 6.17%   |
| 0.51-1.0   | 38        | 5.58%   |
| 5.01-6.0   | 15        | 2.2%    |
| 7.01-8.0   | 4         | 0.59%   |
| 2.01-3.0   | 2         | 0.29%   |
| 8.01-16.0  | 2         | 0.29%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 172       | 23.63%  |
| AU Optronics            | 112       | 15.38%  |
| BOE                     | 85        | 11.68%  |
| Chimei Innolux          | 82        | 11.26%  |
| Samsung Electronics     | 63        | 8.65%   |
| Dell                    | 28        | 3.85%   |
| Lenovo                  | 23        | 3.16%   |
| Chi Mei Optoelectronics | 20        | 2.75%   |
| PANDA                   | 14        | 1.92%   |
| Philips                 | 12        | 1.65%   |
| LG Philips              | 11        | 1.51%   |
| Goldstar                | 11        | 1.51%   |
| Hewlett-Packard         | 10        | 1.37%   |
| Sharp                   | 9         | 1.24%   |
| Apple                   | 7         | 0.96%   |
| BenQ                    | 6         | 0.82%   |
| CSO                     | 5         | 0.69%   |
| AOC                     | 5         | 0.69%   |
| Acer                    | 5         | 0.69%   |
| CPT                     | 4         | 0.55%   |
| Ancor Communications    | 4         | 0.55%   |
| Valve                   | 3         | 0.41%   |
| Toshiba                 | 3         | 0.41%   |
| Sony                    | 3         | 0.41%   |
| Vestel Elektronik       | 2         | 0.27%   |
| InnoLux Display         | 2         | 0.27%   |
| InfoVision              | 2         | 0.27%   |
| Iiyama                  | 2         | 0.27%   |
| HannStar                | 2         | 0.27%   |
| Eizo                    | 2         | 0.27%   |
| BOE Technology Group    | 2         | 0.27%   |
| ASUSTek Computer        | 2         | 0.27%   |
| ViewSonic               | 1         | 0.14%   |
| TMX                     | 1         | 0.14%   |
| Seiko/Epson             | 1         | 0.14%   |
| Panasonic               | 1         | 0.14%   |
| NEC Computers           | 1         | 0.14%   |
| MSI                     | 1         | 0.14%   |
| MPI                     | 1         | 0.14%   |
| LGD                     | 1         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 13        | 1.77%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 9         | 1.23%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 8         | 1.09%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 7         | 0.95%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 6         | 0.82%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 6         | 0.82%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 5         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 5         | 0.68%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 5         | 0.68%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 4         | 0.54%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch             | 4         | 0.54%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 4         | 0.54%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 4         | 0.54%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 4         | 0.54%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 4         | 0.54%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 4         | 0.54%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 4         | 0.54%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 4         | 0.54%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 4         | 0.54%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 3         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 3         | 0.41%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch     | 3         | 0.41%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch            | 3         | 0.41%   |
| LG Display LP156WH2-TLE1 LGDCF01 1366x768 344x194mm 15.5-inch            | 3         | 0.41%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch             | 3         | 0.41%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 3         | 0.41%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 3         | 0.41%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 3         | 0.41%   |
| LG Display LCD Monitor LGD02D3 1366x768 277x156mm 12.5-inch              | 3         | 0.41%   |
| LG Display LCD Monitor LGD021D 1600x900 382x215mm 17.3-inch              | 3         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 3         | 0.41%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 3         | 0.41%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                    | 3         | 0.41%   |
| BOE LCD Monitor BOE08D5 1920x1080 344x194mm 15.5-inch                    | 3         | 0.41%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 3         | 0.41%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 3         | 0.41%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch           | 3         | 0.41%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 0.41%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 3         | 0.41%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                       | 3         | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 308       | 45.49%  |
| 1366x768 (WXGA)    | 184       | 27.18%  |
| 1280x800 (WXGA)    | 34        | 5.02%   |
| 1600x900 (HD+)     | 33        | 4.87%   |
| 3840x2160 (4K)     | 20        | 2.95%   |
| 1920x1200 (WUXGA)  | 18        | 2.66%   |
| 2560x1440 (QHD)    | 14        | 2.07%   |
| 1680x1050 (WSXGA+) | 12        | 1.77%   |
| 2560x1600          | 10        | 1.48%   |
| 1440x900 (WXGA+)   | 6         | 0.89%   |
| 1280x1024 (SXGA)   | 5         | 0.74%   |
| 1024x600           | 5         | 0.74%   |
| 800x1280           | 4         | 0.59%   |
| 2880x1800          | 4         | 0.59%   |
| 2560x1080          | 4         | 0.59%   |
| 3840x2400          | 2         | 0.3%    |
| 800x480            | 1         | 0.15%   |
| 3840x1080          | 1         | 0.15%   |
| 3456x2160          | 1         | 0.15%   |
| 3440x1440          | 1         | 0.15%   |
| 3200x1800 (QHD+)   | 1         | 0.15%   |
| 3000x2000          | 1         | 0.15%   |
| 2256x1504          | 1         | 0.15%   |
| 2160x1440          | 1         | 0.15%   |
| 2048x1152          | 1         | 0.15%   |
| 1600x1200          | 1         | 0.15%   |
| 1280x960           | 1         | 0.15%   |
| 1280x720 (HD)      | 1         | 0.15%   |
| 1024x768 (XGA)     | 1         | 0.15%   |
| Unknown            | 1         | 0.15%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 360       | 49.52%  |
| 14      | 68        | 9.35%   |
| 13      | 66        | 9.08%   |
| 17      | 48        | 6.6%    |
| 24      | 32        | 4.4%    |
| 12      | 26        | 3.58%   |
| 23      | 23        | 3.16%   |
| 27      | 15        | 2.06%   |
| 16      | 15        | 2.06%   |
| 21      | 14        | 1.93%   |
| 11      | 7         | 0.96%   |
| 10      | 6         | 0.83%   |
| 34      | 5         | 0.69%   |
| 22      | 5         | 0.69%   |
| 18      | 5         | 0.69%   |
| 54      | 4         | 0.55%   |
| Unknown | 4         | 0.55%   |
| 84      | 3         | 0.41%   |
| 20      | 3         | 0.41%   |
| 19      | 3         | 0.41%   |
| 7       | 3         | 0.41%   |
| 40      | 2         | 0.28%   |
| 32      | 2         | 0.28%   |
| 28      | 2         | 0.28%   |
| 72      | 1         | 0.14%   |
| 65      | 1         | 0.14%   |
| 33      | 1         | 0.14%   |
| 31      | 1         | 0.14%   |
| 25      | 1         | 0.14%   |
| 3       | 1         | 0.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 469       | 64.87%  |
| 201-300     | 72        | 9.96%   |
| 501-600     | 66        | 9.13%   |
| 351-400     | 59        | 8.16%   |
| 401-500     | 26        | 3.6%    |
| 701-800     | 8         | 1.11%   |
| 1001-1500   | 5         | 0.69%   |
| 601-700     | 4         | 0.55%   |
| 1501-2000   | 4         | 0.55%   |
| 1-100       | 4         | 0.55%   |
| Unknown     | 4         | 0.55%   |
| 801-900     | 2         | 0.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 529       | 82.02%  |
| 16/10   | 90        | 13.95%  |
| 5/4     | 6         | 0.93%   |
| 21/9    | 5         | 0.78%   |
| 3/2     | 4         | 0.62%   |
| Unknown | 4         | 0.62%   |
| 0.67    | 3         | 0.47%   |
| 4/3     | 2         | 0.31%   |
| 6/5     | 1         | 0.16%   |
| 1.00    | 1         | 0.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 357       | 49.38%  |
| 81-90          | 108       | 14.94%  |
| 201-250        | 57        | 7.88%   |
| 121-130        | 42        | 5.81%   |
| 61-70          | 26        | 3.6%    |
| 71-80          | 25        | 3.46%   |
| 301-350        | 15        | 2.07%   |
| 111-120        | 15        | 2.07%   |
| 151-200        | 12        | 1.66%   |
| 351-500        | 11        | 1.52%   |
| 251-300        | 11        | 1.52%   |
| More than 1000 | 8         | 1.11%   |
| 51-60          | 7         | 0.97%   |
| 41-50          | 6         | 0.83%   |
| 141-150        | 6         | 0.83%   |
| 131-140        | 6         | 0.83%   |
| 1-40           | 4         | 0.55%   |
| Unknown        | 4         | 0.55%   |
| 501-1000       | 2         | 0.28%   |
| 91-100         | 1         | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 310       | 43.54%  |
| 101-120       | 199       | 27.95%  |
| 51-100        | 131       | 18.4%   |
| 161-240       | 42        | 5.9%    |
| More than 240 | 20        | 2.81%   |
| 1-50          | 6         | 0.84%   |
| Unknown       | 4         | 0.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 538       | 79.35%  |
| 2     | 101       | 14.9%   |
| 0     | 26        | 3.83%   |
| 3     | 13        | 1.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 359       | 32.85%  |
| Realtek Semiconductor             | 345       | 31.56%  |
| Qualcomm Atheros                  | 142       | 12.99%  |
| Broadcom                          | 65        | 5.95%   |
| MediaTek                          | 30        | 2.74%   |
| Broadcom Limited                  | 23        | 2.1%    |
| Ralink                            | 21        | 1.92%   |
| TP-Link                           | 16        | 1.46%   |
| Ericsson Business Mobile Networks | 15        | 1.37%   |
| Marvell Technology Group          | 12        | 1.1%    |
| Sierra Wireless                   | 11        | 1.01%   |
| Dell                              | 5         | 0.46%   |
| Ralink Technology                 | 4         | 0.37%   |
| Qualcomm Atheros Communications   | 4         | 0.37%   |
| Lenovo                            | 4         | 0.37%   |
| Hewlett-Packard                   | 4         | 0.37%   |
| Huawei Technologies               | 3         | 0.27%   |
| DisplayLink                       | 3         | 0.27%   |
| ASIX Electronics                  | 3         | 0.27%   |
| AMD                               | 3         | 0.27%   |
| Toshiba                           | 2         | 0.18%   |
| Motorola PCS                      | 2         | 0.18%   |
| Google                            | 2         | 0.18%   |
| Davicom Semiconductor             | 2         | 0.18%   |
| D-Link                            | 2         | 0.18%   |
| Xiaomi                            | 1         | 0.09%   |
| Samsung Electronics               | 1         | 0.09%   |
| Quectel Wireless Solutions        | 1         | 0.09%   |
| Qualcomm                          | 1         | 0.09%   |
| Nvidia                            | 1         | 0.09%   |
| NetGear                           | 1         | 0.09%   |
| Micro Star International          | 1         | 0.09%   |
| JMicron Technology                | 1         | 0.09%   |
| ICS Advent                        | 1         | 0.09%   |
| Attansic Technology               | 1         | 0.09%   |
| Apple                             | 1         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 219       | 16.63%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 59        | 4.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 38        | 2.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 32        | 2.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 29        | 2.2%    |
| Intel Wireless 8265 / 8275                                        | 26        | 1.97%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 24        | 1.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 23        | 1.75%   |
| Intel Wi-Fi 6 AX201                                               | 23        | 1.75%   |
| Intel Wireless 7265                                               | 22        | 1.67%   |
| Intel Wireless 7260                                               | 22        | 1.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 21        | 1.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 18        | 1.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 18        | 1.37%   |
| Intel Wi-Fi 6 AX200                                               | 17        | 1.29%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 16        | 1.21%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 14        | 1.06%   |
| Broadcom BCM43142 802.11b/g/n                                     | 14        | 1.06%   |
| Intel Wireless 3160                                               | 13        | 0.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 12        | 0.91%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 12        | 0.91%   |
| Intel Wireless 8260                                               | 12        | 0.91%   |
| Intel WiFi Link 5100                                              | 12        | 0.91%   |
| Intel 82567LM Gigabit Network Connection                          | 12        | 0.91%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 11        | 0.84%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 11        | 0.84%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 11        | 0.84%   |
| Intel Ethernet Connection (3) I218-LM                             | 11        | 0.84%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 11        | 0.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 10        | 0.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 10        | 0.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 10        | 0.76%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 10        | 0.76%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 10        | 0.76%   |
| Intel Centrino Ultimate-N 6300                                    | 10        | 0.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 10        | 0.76%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 9         | 0.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 9         | 0.68%   |
| Intel 82577LM Gigabit Network Connection                          | 9         | 0.68%   |
| Intel Wireless-AC 9260                                            | 8         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 341       | 48.92%  |
| Qualcomm Atheros                  | 118       | 16.93%  |
| Realtek Semiconductor             | 90        | 12.91%  |
| Broadcom                          | 49        | 7.03%   |
| MediaTek                          | 30        | 4.3%    |
| Ralink                            | 21        | 3.01%   |
| TP-Link                           | 12        | 1.72%   |
| Sierra Wireless                   | 11        | 1.58%   |
| Broadcom Limited                  | 7         | 1%      |
| Ralink Technology                 | 4         | 0.57%   |
| Qualcomm Atheros Communications   | 4         | 0.57%   |
| Dell                              | 3         | 0.43%   |
| Ericsson Business Mobile Networks | 2         | 0.29%   |
| Quectel Wireless Solutions        | 1         | 0.14%   |
| Qualcomm                          | 1         | 0.14%   |
| NetGear                           | 1         | 0.14%   |
| Micro Star International          | 1         | 0.14%   |
| Hewlett-Packard                   | 1         | 0.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 32        | 4.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 29        | 4.14%   |
| Intel Wireless 8265 / 8275                                     | 26        | 3.71%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 24        | 3.43%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 23        | 3.29%   |
| Intel Wi-Fi 6 AX201                                            | 23        | 3.29%   |
| Intel Wireless 7265                                            | 22        | 3.14%   |
| Intel Wireless 7260                                            | 22        | 3.14%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 21        | 3%      |
| Intel Cannon Lake PCH CNVi WiFi                                | 18        | 2.57%   |
| Intel Wi-Fi 6 AX200                                            | 17        | 2.43%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 16        | 2.29%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 14        | 2%      |
| Broadcom BCM43142 802.11b/g/n                                  | 14        | 2%      |
| Intel Wireless 3160                                            | 13        | 1.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 12        | 1.71%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 12        | 1.71%   |
| Intel Wireless 8260                                            | 12        | 1.71%   |
| Intel WiFi Link 5100                                           | 12        | 1.71%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 11        | 1.57%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 11        | 1.57%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 11        | 1.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 10        | 1.43%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 10        | 1.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 10        | 1.43%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 10        | 1.43%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 10        | 1.43%   |
| Intel Centrino Ultimate-N 6300                                 | 10        | 1.43%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 10        | 1.43%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 9         | 1.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 9         | 1.29%   |
| Intel Wireless-AC 9260                                         | 8         | 1.14%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 8         | 1.14%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 7         | 1%      |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 7         | 1%      |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 7         | 1%      |
| Sierra Wireless EM7345 4G LTE                                  | 6         | 0.86%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 6         | 0.86%   |
| Intel Centrino Wireless-N 2230                                 | 6         | 0.86%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 5         | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 306       | 52.31%  |
| Intel                    | 155       | 26.5%   |
| Qualcomm Atheros         | 42        | 7.18%   |
| Broadcom                 | 23        | 3.93%   |
| Broadcom Limited         | 16        | 2.74%   |
| Marvell Technology Group | 12        | 2.05%   |
| TP-Link                  | 4         | 0.68%   |
| Lenovo                   | 3         | 0.51%   |
| DisplayLink              | 3         | 0.51%   |
| ASIX Electronics         | 3         | 0.51%   |
| Motorola PCS             | 2         | 0.34%   |
| Huawei Technologies      | 2         | 0.34%   |
| Google                   | 2         | 0.34%   |
| Davicom Semiconductor    | 2         | 0.34%   |
| D-Link                   | 2         | 0.34%   |
| Xiaomi                   | 1         | 0.17%   |
| Samsung Electronics      | 1         | 0.17%   |
| Nvidia                   | 1         | 0.17%   |
| MediaTek                 | 1         | 0.17%   |
| JMicron Technology       | 1         | 0.17%   |
| ICS Advent               | 1         | 0.17%   |
| Attansic Technology      | 1         | 0.17%   |
| Apple                    | 1         | 0.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 219       | 37.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 59        | 10%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 38        | 6.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 18        | 3.05%   |
| Intel 82567LM Gigabit Network Connection                          | 12        | 2.03%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 11        | 1.86%   |
| Intel Ethernet Connection (3) I218-LM                             | 11        | 1.86%   |
| Intel 82577LM Gigabit Network Connection                          | 9         | 1.53%   |
| Intel Ethernet Connection I219-LM                                 | 8         | 1.36%   |
| Intel Ethernet Connection I218-LM                                 | 8         | 1.36%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 1.19%   |
| Intel Ethernet Connection (6) I219-V                              | 6         | 1.02%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 1.02%   |
| Intel 82579V Gigabit Network Connection                           | 6         | 1.02%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 6         | 1.02%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 0.85%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 5         | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 0.85%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 0.85%   |
| Intel Ethernet Connection (16) I219-V                             | 5         | 0.85%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 5         | 0.85%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 4         | 0.68%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.68%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 4         | 0.68%   |
| Intel Ethernet Connection (7) I219-LM                             | 4         | 0.68%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 4         | 0.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 0.51%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.51%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 0.51%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.51%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 3         | 0.51%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 3         | 0.51%   |
| Intel Ethernet Connection (10) I219-V                             | 3         | 0.51%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 3         | 0.51%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express       | 3         | 0.51%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 3         | 0.51%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 0.51%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.34%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.34%   |
| Motorola PCS motorola edge 40                                     | 2         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 648       | 52.26%  |
| Ethernet | 565       | 45.56%  |
| Modem    | 27        | 2.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 543       | 76.8%   |
| Ethernet | 164       | 23.2%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 530       | 80.92%  |
| 1     | 114       | 17.4%   |
| 3     | 6         | 0.92%   |
| 0     | 5         | 0.76%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 637       | 96.08%  |
| Yes  | 26        | 3.92%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 228       | 43.59%  |
| Qualcomm Atheros Communications | 43        | 8.22%   |
| Realtek Semiconductor           | 42        | 8.03%   |
| IMC Networks                    | 34        | 6.5%    |
| Broadcom                        | 34        | 6.5%    |
| Foxconn / Hon Hai               | 27        | 5.16%   |
| Lite-On Technology              | 25        | 4.78%   |
| Toshiba                         | 16        | 3.06%   |
| Dell                            | 15        | 2.87%   |
| Hewlett-Packard                 | 14        | 2.68%   |
| Ralink                          | 11        | 2.1%    |
| Cambridge Silicon Radio         | 8         | 1.53%   |
| Foxconn International           | 6         | 1.15%   |
| Apple                           | 6         | 1.15%   |
| MediaTek                        | 5         | 0.96%   |
| TP-Link                         | 2         | 0.38%   |
| Realtek                         | 2         | 0.38%   |
| Ralink Technology               | 2         | 0.38%   |
| ASUSTek Computer                | 2         | 0.38%   |
| Belkin Components               | 1         | 0.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 92        | 17.59%  |
| Intel Bluetooth Device                              | 56        | 10.71%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 39        | 7.46%   |
| Realtek Bluetooth Radio                             | 33        | 6.31%   |
| Qualcomm Atheros  Bluetooth Device                  | 24        | 4.59%   |
| Intel AX200 Bluetooth                               | 16        | 3.06%   |
| IMC Networks Bluetooth Radio                        | 13        | 2.49%   |
| Ralink RT3290 Bluetooth                             | 11        | 2.1%    |
| IMC Networks Wireless_Device                        | 10        | 1.91%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 9         | 1.72%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 8         | 1.53%   |
| Lite-On Bluetooth Device                            | 8         | 1.53%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 8         | 1.53%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 8         | 1.53%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8         | 1.53%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 7         | 1.34%   |
| Foxconn / Hon Hai Bluetooth Device                  | 7         | 1.34%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 1.34%   |
| Broadcom BCM2045B (BDC-2.1)                         | 7         | 1.34%   |
| Toshiba Integrated Bluetooth HCI                    | 6         | 1.15%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6         | 1.15%   |
| IMC Networks Bluetooth Device                       | 6         | 1.15%   |
| HP Broadcom 2070 Bluetooth Combo                    | 6         | 1.15%   |
| Foxconn International BCM43142A0 Bluetooth module   | 6         | 1.15%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 5         | 0.96%   |
| Dell DW375 Bluetooth Module                         | 5         | 0.96%   |
| MediaTek Wireless_Device                            | 4         | 0.76%   |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 0.76%   |
| IMC Networks 802.11ac WLAN Adapter                  | 4         | 0.76%   |
| Foxconn / Hon Hai Wireless_Device                   | 4         | 0.76%   |
| Foxconn / Hon Hai Bluetooth Adapter                 | 4         | 0.76%   |
| Dell BCM20702A0 Bluetooth Module                    | 4         | 0.76%   |
| Toshiba RT Bluetooth Radio                          | 3         | 0.57%   |
| Toshiba Bluetooth Device                            | 3         | 0.57%   |
| Realtek RTL8723B Bluetooth                          | 3         | 0.57%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 0.57%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 0.57%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 0.57%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 0.57%   |
| Foxconn / Hon Hai BCM20702A0                        | 3         | 0.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 533       | 65.48%  |
| AMD                              | 133       | 16.34%  |
| Nvidia                           | 106       | 13.02%  |
| Lenovo                           | 6         | 0.74%   |
| Razer USA                        | 5         | 0.61%   |
| GN Netcom                        | 4         | 0.49%   |
| C-Media Electronics              | 4         | 0.49%   |
| Realtek Semiconductor            | 3         | 0.37%   |
| Logitech                         | 3         | 0.37%   |
| Plantronics                      | 2         | 0.25%   |
| JMTek                            | 2         | 0.25%   |
| Creative Technology              | 2         | 0.25%   |
| ZOOM                             | 1         | 0.12%   |
| VIA Technologies                 | 1         | 0.12%   |
| Trust                            | 1         | 0.12%   |
| Sony                             | 1         | 0.12%   |
| Silicon Integrated Systems [SiS] | 1         | 0.12%   |
| No brand                         | 1         | 0.12%   |
| Native Instruments               | 1         | 0.12%   |
| GYROCOM C&C                      | 1         | 0.12%   |
| Generalplus Technology           | 1         | 0.12%   |
| ASUSTek Computer                 | 1         | 0.12%   |
| Apple                            | 1         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 82        | 8.37%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 74        | 7.55%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 50        | 5.1%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 48        | 4.9%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 44        | 4.49%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 42        | 4.29%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 28        | 2.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 28        | 2.86%   |
| Intel Broadwell-U Audio Controller                                                                | 28        | 2.86%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 27        | 2.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 26        | 2.65%   |
| Intel Cannon Lake PCH cAVS                                                                        | 26        | 2.65%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 26        | 2.65%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 21        | 2.14%   |
| Intel 8 Series HD Audio Controller                                                                | 21        | 2.14%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 18        | 1.84%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 18        | 1.84%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 18        | 1.84%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 16        | 1.63%   |
| Intel CM238 HD Audio Controller                                                                   | 15        | 1.53%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 15        | 1.53%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 13        | 1.33%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 12        | 1.22%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 12        | 1.22%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 12        | 1.22%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 12        | 1.22%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 12        | 1.22%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 12        | 1.22%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 10        | 1.02%   |
| Intel Comet Lake PCH cAVS                                                                         | 10        | 1.02%   |
| Nvidia Audio device                                                                               | 9         | 0.92%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 9         | 0.92%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 8         | 0.82%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 8         | 0.82%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 8         | 0.82%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 7         | 0.71%   |
| AMD FCH Azalia Controller                                                                         | 7         | 0.71%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 6         | 0.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 0.61%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 110       | 25.17%  |
| SK hynix                                | 100       | 22.88%  |
| Micron Technology                       | 54        | 12.36%  |
| Kingston                                | 50        | 11.44%  |
| Unknown                                 | 24        | 5.49%   |
| Ramaxel Technology                      | 18        | 4.12%   |
| A-DATA Technology                       | 17        | 3.89%   |
| Transcend                               | 10        | 2.29%   |
| Nanya Technology                        | 10        | 2.29%   |
| Corsair                                 | 8         | 1.83%   |
| Elpida                                  | 7         | 1.6%    |
| Apacer                                  | 6         | 1.37%   |
| Team                                    | 5         | 1.14%   |
| Crucial                                 | 5         | 1.14%   |
| Silicon Power Computer & Communications | 2         | 0.46%   |
| ASint Technology                        | 2         | 0.46%   |
| Unknown (ABCD)                          | 1         | 0.23%   |
| Unifosa                                 | 1         | 0.23%   |
| Silicon Power                           | 1         | 0.23%   |
| Qimonda                                 | 1         | 0.23%   |
| Neo Forza                               | 1         | 0.23%   |
| GOODRAM                                 | 1         | 0.23%   |
| fef5                                    | 1         | 0.23%   |
| A Force                                 | 1         | 0.23%   |
| Unknown                                 | 1         | 0.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 10        | 2.15%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 8         | 1.72%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s  | 6         | 1.29%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 5         | 1.08%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 5         | 1.08%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s     | 5         | 1.08%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s     | 5         | 1.08%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s      | 5         | 1.08%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 4         | 0.86%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s  | 4         | 0.86%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 4         | 0.86%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 4         | 0.86%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s  | 4         | 0.86%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s     | 4         | 0.86%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s   | 4         | 0.86%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s      | 4         | 0.86%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 3         | 0.65%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s | 3         | 0.65%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s   | 3         | 0.65%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s    | 3         | 0.65%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s  | 3         | 0.65%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s     | 3         | 0.65%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 3         | 0.65%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s  | 3         | 0.65%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s    | 3         | 0.65%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s     | 3         | 0.65%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s | 3         | 0.65%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s      | 3         | 0.65%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s      | 3         | 0.65%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s      | 3         | 0.65%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s      | 3         | 0.65%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s      | 3         | 0.65%   |
| Kingston RAM 9905744-066.A00G 32GB SODIMM DDR4 3200MT/s   | 3         | 0.65%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s     | 3         | 0.65%   |
| A-DATA RAM Module 8GB SODIMM DDR4 3200MT/s                | 3         | 0.65%   |
| Unknown RAM Module 8GB SODIMM DDR4 3200MT/s               | 2         | 0.43%   |
| Unknown RAM Module 2GB SODIMM DRAM                        | 2         | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                | 2         | 0.43%   |
| Unknown RAM Module 1GB SODIMM DRAM                        | 2         | 0.43%   |
| Unknown RAM Module 1024MB SODIMM DDR                      | 2         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 152       | 43.93%  |
| DDR3    | 138       | 39.88%  |
| DDR2    | 12        | 3.47%   |
| DDR5    | 10        | 2.89%   |
| SDRAM   | 8         | 2.31%   |
| LPDDR4  | 6         | 1.73%   |
| Unknown | 5         | 1.45%   |
| LPDDR5  | 4         | 1.16%   |
| LPDDR3  | 4         | 1.16%   |
| DRAM    | 4         | 1.16%   |
| DDR     | 3         | 0.87%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 322       | 93.88%  |
| Row Of Chips | 12        | 3.5%    |
| DIMM         | 4         | 1.17%   |
| Chip         | 4         | 1.17%   |
| Unknown      | 1         | 0.29%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 8192    | 136       | 35.88%  |
| 4096    | 110       | 29.02%  |
| 16384   | 58        | 15.3%   |
| 2048    | 39        | 10.29%  |
| 32768   | 19        | 5.01%   |
| 1024    | 15        | 3.96%   |
| 512     | 1         | 0.26%   |
| Unknown | 1         | 0.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 91        | 23.95%  |
| 3200    | 78        | 20.53%  |
| 2667    | 65        | 17.11%  |
| 1334    | 31        | 8.16%   |
| 2400    | 20        | 5.26%   |
| 1333    | 18        | 4.74%   |
| Unknown | 12        | 3.16%   |
| 667     | 10        | 2.63%   |
| 2133    | 8         | 2.11%   |
| 4800    | 7         | 1.84%   |
| 1067    | 5         | 1.32%   |
| 1066    | 5         | 1.32%   |
| 6400    | 4         | 1.05%   |
| 4199    | 4         | 1.05%   |
| 3266    | 4         | 1.05%   |
| 5600    | 3         | 0.79%   |
| 2048    | 3         | 0.79%   |
| 1867    | 3         | 0.79%   |
| 800     | 3         | 0.79%   |
| 975     | 2         | 0.53%   |
| 4267    | 1         | 0.26%   |
| 4266    | 1         | 0.26%   |
| 2933    | 1         | 0.26%   |
| 1866    | 1         | 0.26%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 28.57%  |
| Canon               | 2         | 28.57%  |
| STMicroelectronics  | 1         | 14.29%  |
| Seiko Epson         | 1         | 14.29%  |
| Brother Industries  | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 14.29%  |
| Seiko Epson L3150 Series                                  | 1         | 14.29%  |
| Samsung M332x 382x 402x Series                            | 1         | 14.29%  |
| Samsung M267x 287x Series                                 | 1         | 14.29%  |
| Canon PIXMA MP240                                         | 1         | 14.29%  |
| Canon MF3200 series                                       | 1         | 14.29%  |
| Brother DCP-7055 scanner/printer                          | 1         | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| Mustek Systems | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                       | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Mustek Systems SNAPSCAN e22 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 147       | 25.65%  |
| IMC Networks                           | 69        | 12.04%  |
| Bison Electronics                      | 51        | 8.9%    |
| Microdia                               | 50        | 8.73%   |
| Realtek Semiconductor                  | 42        | 7.33%   |
| Quanta                                 | 38        | 6.63%   |
| Sunplus Innovation Technology          | 36        | 6.28%   |
| Lite-On Technology                     | 16        | 2.79%   |
| Suyin                                  | 15        | 2.62%   |
| Cheng Uei Precision Industry (Foxlink) | 15        | 2.62%   |
| Syntek                                 | 14        | 2.44%   |
| Luxvisions Innotech Limited            | 11        | 1.92%   |
| Logitech                               | 10        | 1.75%   |
| Acer                                   | 10        | 1.75%   |
| Alcor Micro                            | 7         | 1.22%   |
| Sonix Technology                       | 5         | 0.87%   |
| Lenovo                                 | 5         | 0.87%   |
| Apple                                  | 5         | 0.87%   |
| Silicon Motion                         | 4         | 0.7%    |
| Ricoh                                  | 3         | 0.52%   |
| Z-Star Microelectronics                | 2         | 0.35%   |
| Samsung Electronics                    | 2         | 0.35%   |
| Primax Electronics                     | 2         | 0.35%   |
| Importek                               | 2         | 0.35%   |
| Alpha Imaging Technology               | 2         | 0.35%   |
| ALi                                    | 2         | 0.35%   |
| Xiongmai                               | 1         | 0.17%   |
| Sunplus Technology                     | 1         | 0.17%   |
| OmniVision Technologies                | 1         | 0.17%   |
| Microsoft                              | 1         | 0.17%   |
| Hewlett-Packard                        | 1         | 0.17%   |
| Creative Technology                    | 1         | 0.17%   |
| Aveo Technology                        | 1         | 0.17%   |
| Arkmicro Technologies                  | 1         | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Chicony Integrated Camera                  | 33        | 5.76%   |
| IMC Networks USB2.0 VGA UVC WebCam         | 22        | 3.84%   |
| IMC Networks Integrated Camera             | 21        | 3.66%   |
| Bison Integrated Camera                    | 19        | 3.32%   |
| Microdia Integrated_Webcam_HD              | 17        | 2.97%   |
| Chicony HD WebCam                          | 16        | 2.79%   |
| Sunplus Integrated_Webcam_HD               | 13        | 2.27%   |
| Realtek Integrated_Webcam_HD               | 11        | 1.92%   |
| Quanta HP HD Camera                        | 9         | 1.57%   |
| Chicony TOSHIBA Web Camera - HD            | 9         | 1.57%   |
| Realtek Lenovo EasyCamera                  | 8         | 1.4%    |
| IMC Networks USB2.0 HD UVC WebCam          | 8         | 1.4%    |
| Bison SunplusIT Integrated Camera          | 8         | 1.4%    |
| Syntek Integrated Camera                   | 7         | 1.22%   |
| Microdia Integrated Webcam                 | 6         | 1.05%   |
| Chicony USB 2.0 Camera                     | 6         | 1.05%   |
| Quanta HD Webcam                           | 5         | 0.87%   |
| Quanta HD User Facing                      | 5         | 0.87%   |
| Lite-On HP HD Webcam                       | 5         | 0.87%   |
| Chicony Lenovo Integrated Camera (0.3MP)   | 5         | 0.87%   |
| Chicony Lenovo EasyCamera                  | 5         | 0.87%   |
| Chicony HD WebCam (Asus N-series)          | 5         | 0.87%   |
| Bison HD Webcam                            | 5         | 0.87%   |
| Acer Lenovo EasyCamera                     | 5         | 0.87%   |
| Suyin Acer/HP Integrated Webcam [CN0314]   | 4         | 0.7%    |
| Sunplus Laptop Integrated Webcam HD        | 4         | 0.7%    |
| Sonix USB2.0 HD UVC WebCam                 | 4         | 0.7%    |
| Quanta HP TrueVision HD Camera             | 4         | 0.7%    |
| Quanta ACER HD User Facing                 | 4         | 0.7%    |
| Lite-On Integrated Camera                  | 4         | 0.7%    |
| IMC Networks UVC VGA Webcam                | 4         | 0.7%    |
| Chicony USB2.0 VGA UVC WebCam              | 4         | 0.7%    |
| Chicony HP HD Webcam                       | 4         | 0.7%    |
| Bison Lenovo EasyCamera                    | 4         | 0.7%    |
| Alcor Micro Acer Integrated Webcam         | 4         | 0.7%    |
| Syntek Lenovo EasyCamera                   | 3         | 0.52%   |
| Sunplus HP HD Webcam [Fixed]               | 3         | 0.52%   |
| Sunplus HD WebCam                          | 3         | 0.52%   |
| Sunplus Dell HD Webcam                     | 3         | 0.52%   |
| Realtek HP Truevision HD integrated webcam | 3         | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 42        | 37.84%  |
| Synaptics                          | 32        | 28.83%  |
| AuthenTec                          | 15        | 13.51%  |
| Shenzhen Goodix Technology         | 7         | 6.31%   |
| Upek                               | 6         | 5.41%   |
| Elan Microelectronics              | 4         | 3.6%    |
| LighTuning Technology              | 3         | 2.7%    |
| STMicroelectronics                 | 1         | 0.9%    |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.9%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 15        | 13.51%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 12        | 10.81%  |
| AuthenTec AES2810                                                          | 8         | 7.21%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 5.41%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 5.41%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 4.5%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 4.5%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 3.6%    |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 3.6%    |
| AuthenTec Fingerprint Sensor                                               | 4         | 3.6%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 2.7%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 2.7%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 2.7%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.8%    |
| Validity Sensors VFS491                                                    | 2         | 1.8%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.8%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.8%    |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.8%    |
| Synaptics WBDI                                                             | 2         | 1.8%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.8%    |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 1.8%    |
| Elan ELAN:Fingerprint                                                      | 2         | 1.8%    |
| Elan ELAN:ARM-M4                                                           | 2         | 1.8%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 1.8%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.9%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.9%    |
| Synaptics UWP WBDI Device                                                  | 1         | 0.9%    |
| Synaptics TouchPad                                                         | 1         | 0.9%    |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.9%    |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.9%    |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.9%    |
| LighTuning Fingerprint Reader                                              | 1         | 0.9%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.9%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.9%    |
| AuthenTec AES1600                                                          | 1         | 0.9%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 28        | 36.36%  |
| Alcor Micro           | 27        | 35.06%  |
| Upek                  | 7         | 9.09%   |
| O2 Micro              | 5         | 6.49%   |
| Lenovo                | 4         | 5.19%   |
| Advanced Card Systems | 3         | 3.9%    |
| SCM Microsystems      | 2         | 2.6%    |
| Clay Logic            | 1         | 1.3%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 27        | 35.06%  |
| Broadcom BCM5880 Secure Applications Processor                               | 12        | 15.58%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 9.09%   |
| Broadcom 58200                                                               | 6         | 7.79%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 6.49%   |
| Broadcom 5880                                                                | 5         | 6.49%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 5.19%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 5.19%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 2.6%    |
| Advanced Card Systems ACR39U                                                 | 2         | 2.6%    |
| Clay Logic Nitrokey Pro                                                      | 1         | 1.3%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 1.3%    |
| Advanced Card Systems ACR122U                                                | 1         | 1.3%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 396       | 57.39%  |
| 1     | 223       | 32.32%  |
| 2     | 66        | 9.57%   |
| 3     | 4         | 0.58%   |
| 7     | 1         | 0.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 111       | 31.9%   |
| Graphics card            | 77        | 22.13%  |
| Chipcard                 | 65        | 18.68%  |
| Net/wireless             | 27        | 7.76%   |
| Multimedia controller    | 17        | 4.89%   |
| Bluetooth                | 17        | 4.89%   |
| Storage                  | 9         | 2.59%   |
| Camera                   | 7         | 2.01%   |
| Communication controller | 4         | 1.15%   |
| Card reader              | 4         | 1.15%   |
| Sound                    | 2         | 0.57%   |
| Net/ethernet             | 2         | 0.57%   |
| Modem                    | 2         | 0.57%   |
| Firewire controller      | 2         | 0.57%   |
| Network                  | 1         | 0.29%   |
| Flash memory             | 1         | 0.29%   |

