Kubuntu 22.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Kubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Kubuntu_22.04/Desktop/README.md) and [notebooks](/Dist/Kubuntu_22.04/Notebook/README.md).

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

Total: 1753

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME X370-PRO              | Desktop     | [58d150eef2](https://linux-hardware.org/?probe=58d150eef2) | Feb 02, 2024 |
| Unknown       | Unknown                     | Notebook    | [8c03bd946c](https://linux-hardware.org/?probe=8c03bd946c) | Feb 02, 2024 |
| Notebook      | V15x_V17xRNx                | Notebook    | [901e71289e](https://linux-hardware.org/?probe=901e71289e) | Feb 02, 2024 |
| ASUSTek       | P5Q                         | Desktop     | [63522c9a09](https://linux-hardware.org/?probe=63522c9a09) | Feb 02, 2024 |
| GX55          | Unknown                     | Tablet      | [99db62ac14](https://linux-hardware.org/?probe=99db62ac14) | Feb 02, 2024 |
| Dell          | Inspiron 5547               | Notebook    | [507fad3c00](https://linux-hardware.org/?probe=507fad3c00) | Feb 02, 2024 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [c2514048e9](https://linux-hardware.org/?probe=c2514048e9) | Feb 02, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [8e3680cd5d](https://linux-hardware.org/?probe=8e3680cd5d) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [f1b0b8716f](https://linux-hardware.org/?probe=f1b0b8716f) | Feb 01, 2024 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [9d2088ace3](https://linux-hardware.org/?probe=9d2088ace3) | Feb 01, 2024 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [8f630da527](https://linux-hardware.org/?probe=8f630da527) | Jan 31, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [02d7b129fc](https://linux-hardware.org/?probe=02d7b129fc) | Jan 31, 2024 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [a477ec4fe1](https://linux-hardware.org/?probe=a477ec4fe1) | Jan 31, 2024 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [aabd02c85c](https://linux-hardware.org/?probe=aabd02c85c) | Jan 30, 2024 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [c823432a5a](https://linux-hardware.org/?probe=c823432a5a) | Jan 30, 2024 |
| ASUSTek       | G75VX                       | Notebook    | [5c270f1082](https://linux-hardware.org/?probe=5c270f1082) | Jan 30, 2024 |
| Toshiba       | Satellite P300              | Notebook    | [14da91750f](https://linux-hardware.org/?probe=14da91750f) | Jan 29, 2024 |
| Acer          | Veriton X6630G              | Desktop     | [66d62ae7ed](https://linux-hardware.org/?probe=66d62ae7ed) | Jan 29, 2024 |
| Acer          | Veriton X6630G              | Desktop     | [9684aca764](https://linux-hardware.org/?probe=9684aca764) | Jan 29, 2024 |
| Acer          | TravelMate P215-41-G2       | Notebook    | [0500733b2d](https://linux-hardware.org/?probe=0500733b2d) | Jan 28, 2024 |
| HP            | EliteBook 8470w             | Notebook    | [a92904a970](https://linux-hardware.org/?probe=a92904a970) | Jan 28, 2024 |
| Acer          | Aspire A715-42G             | Notebook    | [6e3e887615](https://linux-hardware.org/?probe=6e3e887615) | Jan 27, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AHA... | Notebook    | [f2ed690a39](https://linux-hardware.org/?probe=f2ed690a39) | Jan 27, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AHA... | Notebook    | [4644130b45](https://linux-hardware.org/?probe=4644130b45) | Jan 27, 2024 |
| ASRock        | B450M Pro4                  | Desktop     | [23faf0c03e](https://linux-hardware.org/?probe=23faf0c03e) | Jan 25, 2024 |
| Lenovo        | ThinkPad Twist 334729G      | Notebook    | [0a17051b66](https://linux-hardware.org/?probe=0a17051b66) | Jan 25, 2024 |
| Medion        | S14409                      | Notebook    | [8e8339905a](https://linux-hardware.org/?probe=8e8339905a) | Jan 25, 2024 |
| AZW           | Gemini T45                  | Desktop     | [5a3dba74d6](https://linux-hardware.org/?probe=5a3dba74d6) | Jan 24, 2024 |
| AZW           | Gemini T45                  | Desktop     | [a0e1db7908](https://linux-hardware.org/?probe=a0e1db7908) | Jan 24, 2024 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [7c94952653](https://linux-hardware.org/?probe=7c94952653) | Jan 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | Notebook    | [f9da9c2d2e](https://linux-hardware.org/?probe=f9da9c2d2e) | Jan 23, 2024 |
| HP            | ProBook 4540s               | Notebook    | [84367073dd](https://linux-hardware.org/?probe=84367073dd) | Jan 22, 2024 |
| HP            | ProBook 4540s               | Notebook    | [f72cd2d1a0](https://linux-hardware.org/?probe=f72cd2d1a0) | Jan 22, 2024 |
| Lenovo        | 1037 SDK0Q40104 WIN 3305... | Server      | [e8d7aba4fe](https://linux-hardware.org/?probe=e8d7aba4fe) | Jan 22, 2024 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [31a4f6e57f](https://linux-hardware.org/?probe=31a4f6e57f) | Jan 22, 2024 |
| ASUSTek       | UX410UAK                    | Notebook    | [1155ca8c5c](https://linux-hardware.org/?probe=1155ca8c5c) | Jan 22, 2024 |
| Gigabyte      | Z97-HD3                     | Desktop     | [e568089bad](https://linux-hardware.org/?probe=e568089bad) | Jan 21, 2024 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [aaf1d1d0de](https://linux-hardware.org/?probe=aaf1d1d0de) | Jan 21, 2024 |
| HP            | Notebook                    | Notebook    | [71136f647b](https://linux-hardware.org/?probe=71136f647b) | Jan 20, 2024 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [494d0af2e5](https://linux-hardware.org/?probe=494d0af2e5) | Jan 19, 2024 |
| Dell          | Latitude 7330               | Notebook    | [d8b532bbee](https://linux-hardware.org/?probe=d8b532bbee) | Jan 19, 2024 |
| HP            | OMEN Laptop 15-ek1xxx       | Notebook    | [5c18e1a4bc](https://linux-hardware.org/?probe=5c18e1a4bc) | Jan 18, 2024 |
| Great Wall    | MBX-Z60AR110 TBD            | Desktop     | [fdfa81d344](https://linux-hardware.org/?probe=fdfa81d344) | Jan 18, 2024 |
| Dell          | Latitude 5530               | Notebook    | [df5d5becd7](https://linux-hardware.org/?probe=df5d5becd7) | Jan 17, 2024 |
| Medion        | H110H4-EM                   | Desktop     | [ea736cf314](https://linux-hardware.org/?probe=ea736cf314) | Jan 17, 2024 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [0d81012aa0](https://linux-hardware.org/?probe=0d81012aa0) | Jan 16, 2024 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [c69281db28](https://linux-hardware.org/?probe=c69281db28) | Jan 15, 2024 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [ca627d3c3e](https://linux-hardware.org/?probe=ca627d3c3e) | Jan 15, 2024 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [cdfc29ad66](https://linux-hardware.org/?probe=cdfc29ad66) | Jan 15, 2024 |
| MSI           | Summit E16Flip A12UCT       | Notebook    | [efb852e7fb](https://linux-hardware.org/?probe=efb852e7fb) | Jan 15, 2024 |
| Google        | Fleex                       | Notebook    | [46f5b6af86](https://linux-hardware.org/?probe=46f5b6af86) | Jan 14, 2024 |
| VALE          | Notebook Slim S132          | Notebook    | [32021c35d3](https://linux-hardware.org/?probe=32021c35d3) | Jan 14, 2024 |
| VALE          | Notebook Slim S132          | Notebook    | [0d2db2e184](https://linux-hardware.org/?probe=0d2db2e184) | Jan 14, 2024 |
| HP            | x2 210 G2                   | Tablet      | [e1baf3e443](https://linux-hardware.org/?probe=e1baf3e443) | Jan 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [bda32c8468](https://linux-hardware.org/?probe=bda32c8468) | Jan 14, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [398927cd45](https://linux-hardware.org/?probe=398927cd45) | Jan 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [25341b5586](https://linux-hardware.org/?probe=25341b5586) | Jan 13, 2024 |
| Lenovo        | ThinkPad T495 20NJ000XIX    | Notebook    | [700470a7f6](https://linux-hardware.org/?probe=700470a7f6) | Jan 12, 2024 |
| MSI           | H410M PRO                   | Desktop     | [76a24b5fa3](https://linux-hardware.org/?probe=76a24b5fa3) | Jan 12, 2024 |
| Lenovo        | ThinkPad E450 20DC003WUS    | Notebook    | [817c17d60e](https://linux-hardware.org/?probe=817c17d60e) | Jan 12, 2024 |
| HP            | ProBook 6450b               | Notebook    | [ddae4148a2](https://linux-hardware.org/?probe=ddae4148a2) | Jan 12, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bddc683db5](https://linux-hardware.org/?probe=bddc683db5) | Jan 12, 2024 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [a188d14c50](https://linux-hardware.org/?probe=a188d14c50) | Jan 11, 2024 |
| Dell          | Inspiron 3793               | Notebook    | [60ded5e8e7](https://linux-hardware.org/?probe=60ded5e8e7) | Jan 11, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f1814dff2e](https://linux-hardware.org/?probe=f1814dff2e) | Jan 11, 2024 |
| HP            | 8767 A                      | Desktop     | [88f6719b01](https://linux-hardware.org/?probe=88f6719b01) | Jan 10, 2024 |
| ASUSTek       | H81T R2.0                   | Desktop     | [23cc8eb053](https://linux-hardware.org/?probe=23cc8eb053) | Jan 10, 2024 |
| Sony          | VGN-CS190N                  | Notebook    | [2ac26516a6](https://linux-hardware.org/?probe=2ac26516a6) | Jan 09, 2024 |
| ASUSTek       | Zephyrus S GX502GW_GX502... | Notebook    | [8101d22b4a](https://linux-hardware.org/?probe=8101d22b4a) | Jan 09, 2024 |
| Dell          | 0HD5W2 A01                  | Desktop     | [7194fe43ed](https://linux-hardware.org/?probe=7194fe43ed) | Jan 09, 2024 |
| Dell          | 0F96C8 A00                  | All in one  | [f7d20028f6](https://linux-hardware.org/?probe=f7d20028f6) | Jan 08, 2024 |
| Gigabyte      | H67A-UD3H-B3                | Desktop     | [f43717fa8e](https://linux-hardware.org/?probe=f43717fa8e) | Jan 08, 2024 |
| Dell          | Latitude E7450              | Notebook    | [a60667c993](https://linux-hardware.org/?probe=a60667c993) | Jan 08, 2024 |
| Apple         | MacBookAir9,1               | Notebook    | [6af0a29be6](https://linux-hardware.org/?probe=6af0a29be6) | Jan 07, 2024 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [ee9fb5898f](https://linux-hardware.org/?probe=ee9fb5898f) | Jan 07, 2024 |
| HP            | 3397                        | Desktop     | [0ba7322ded](https://linux-hardware.org/?probe=0ba7322ded) | Jan 05, 2024 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [5feecec8b2](https://linux-hardware.org/?probe=5feecec8b2) | Jan 05, 2024 |
| Biostar       | B365MHC                     | Desktop     | [0936a451ce](https://linux-hardware.org/?probe=0936a451ce) | Jan 04, 2024 |
| HP            | ENVY m6                     | Notebook    | [d63a06fb89](https://linux-hardware.org/?probe=d63a06fb89) | Jan 04, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [cf1f935e69](https://linux-hardware.org/?probe=cf1f935e69) | Jan 03, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [cf07066830](https://linux-hardware.org/?probe=cf07066830) | Jan 03, 2024 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [4c7efd21fe](https://linux-hardware.org/?probe=4c7efd21fe) | Jan 02, 2024 |
| Rockchip      | RK3588 OPi 5 Plus           | Soc         | [a948fd2006](https://linux-hardware.org/?probe=a948fd2006) | Jan 02, 2024 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [fb59929b28](https://linux-hardware.org/?probe=fb59929b28) | Jan 02, 2024 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [435dc251c1](https://linux-hardware.org/?probe=435dc251c1) | Jan 02, 2024 |
| Rockchip      | RK3588 OPi 5 Plus           | Soc         | [e8e24c9091](https://linux-hardware.org/?probe=e8e24c9091) | Jan 01, 2024 |
| MSI           | 2AE0                        | Desktop     | [00b5d15112](https://linux-hardware.org/?probe=00b5d15112) | Jan 01, 2024 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [8a1771af4b](https://linux-hardware.org/?probe=8a1771af4b) | Jan 01, 2024 |
| Rockchip      | RK3588 OPi 5 Plus           | Soc         | [c6a3df522b](https://linux-hardware.org/?probe=c6a3df522b) | Dec 31, 2023 |
| Toshiba       | STI 013442                  | Desktop     | [c8488906f2](https://linux-hardware.org/?probe=c8488906f2) | Dec 31, 2023 |
| Notebook      | NL5xNU                      | Notebook    | [915031852a](https://linux-hardware.org/?probe=915031852a) | Dec 31, 2023 |
| Toshiba       | STI 013442                  | Desktop     | [ed56d2dcb5](https://linux-hardware.org/?probe=ed56d2dcb5) | Dec 31, 2023 |
| Apple         | MacBookAir9,1               | Notebook    | [71c755966f](https://linux-hardware.org/?probe=71c755966f) | Dec 31, 2023 |
| Apple         | MacBookAir9,1               | Notebook    | [b13ec8c4fe](https://linux-hardware.org/?probe=b13ec8c4fe) | Dec 31, 2023 |
| ASUSTek       | PRIME B360M-A               | Notebook    | [42b25d8ac5](https://linux-hardware.org/?probe=42b25d8ac5) | Dec 30, 2023 |
| HP            | ENVY m4                     | Notebook    | [6416f24210](https://linux-hardware.org/?probe=6416f24210) | Dec 30, 2023 |
| HP            | ENVY m4                     | Notebook    | [f0cd285399](https://linux-hardware.org/?probe=f0cd285399) | Dec 30, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [3700165122](https://linux-hardware.org/?probe=3700165122) | Dec 28, 2023 |
| Rockchip      | RK3588 OPi 5 Plus           | Soc         | [4f74bf57df](https://linux-hardware.org/?probe=4f74bf57df) | Dec 28, 2023 |
| Rockchip      | RK3588 OPi 5 Plus           | Soc         | [59ae3d3d52](https://linux-hardware.org/?probe=59ae3d3d52) | Dec 28, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [c68ea76b65](https://linux-hardware.org/?probe=c68ea76b65) | Dec 28, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [48d04b219b](https://linux-hardware.org/?probe=48d04b219b) | Dec 28, 2023 |
| Foxconn       | 2AB7                        | Desktop     | [2d0962bbfa](https://linux-hardware.org/?probe=2d0962bbfa) | Dec 27, 2023 |
| Foxconn       | 2AB7                        | Desktop     | [b1b00dd0b5](https://linux-hardware.org/?probe=b1b00dd0b5) | Dec 27, 2023 |
| Notebook      | NL5xNU                      | Notebook    | [ad5a093909](https://linux-hardware.org/?probe=ad5a093909) | Dec 26, 2023 |
| Lenovo        | ThinkPad T520 4243ED3       | Notebook    | [6fd4832f12](https://linux-hardware.org/?probe=6fd4832f12) | Dec 26, 2023 |
| Apple         | MacBookAir9,1               | Notebook    | [22b65c12f2](https://linux-hardware.org/?probe=22b65c12f2) | Dec 26, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [0714d5920a](https://linux-hardware.org/?probe=0714d5920a) | Dec 26, 2023 |
| PC Special... | 14 Fusion Pro               | Notebook    | [76bf311c34](https://linux-hardware.org/?probe=76bf311c34) | Dec 25, 2023 |
| Dell          | 0F6X5P A00                  | Desktop     | [8b6cbdd646](https://linux-hardware.org/?probe=8b6cbdd646) | Dec 24, 2023 |
| HP            | 340S G7 Notebook PC         | Notebook    | [097603b65a](https://linux-hardware.org/?probe=097603b65a) | Dec 23, 2023 |
| Lenovo        | ThinkPad T500 20564RG       | Notebook    | [e17f4b51d6](https://linux-hardware.org/?probe=e17f4b51d6) | Dec 22, 2023 |
| Lenovo        | M30-70 80H8                 | Notebook    | [8ec7db7a8a](https://linux-hardware.org/?probe=8ec7db7a8a) | Dec 22, 2023 |
| Eluktronic... | MECH-17                     | Notebook    | [0a69b2e084](https://linux-hardware.org/?probe=0a69b2e084) | Dec 22, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [db6db43604](https://linux-hardware.org/?probe=db6db43604) | Dec 22, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [cdcc0b8368](https://linux-hardware.org/?probe=cdcc0b8368) | Dec 22, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [1b860f6465](https://linux-hardware.org/?probe=1b860f6465) | Dec 21, 2023 |
| Dell          | 0F6X5P A00                  | Desktop     | [fb2877e727](https://linux-hardware.org/?probe=fb2877e727) | Dec 21, 2023 |
| Apple         | Mac-F2218FC8                | All in one  | [81855c7ee8](https://linux-hardware.org/?probe=81855c7ee8) | Dec 21, 2023 |
| Google        | Cave                        | Notebook    | [ec9d49335f](https://linux-hardware.org/?probe=ec9d49335f) | Dec 20, 2023 |
| HP            | Pavilion 17                 | Notebook    | [449c36ff1c](https://linux-hardware.org/?probe=449c36ff1c) | Dec 19, 2023 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [031f8b45bd](https://linux-hardware.org/?probe=031f8b45bd) | Dec 19, 2023 |
| MSI           | H97M-P35                    | Desktop     | [759943cd15](https://linux-hardware.org/?probe=759943cd15) | Dec 19, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [42706222be](https://linux-hardware.org/?probe=42706222be) | Dec 19, 2023 |
| HP            | 81B3                        | Desktop     | [86d9fc12a5](https://linux-hardware.org/?probe=86d9fc12a5) | Dec 19, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [d56dcc35b9](https://linux-hardware.org/?probe=d56dcc35b9) | Dec 18, 2023 |
| Gateway       | NV54 Series                 | Notebook    | [1bd87c77d2](https://linux-hardware.org/?probe=1bd87c77d2) | Dec 18, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [6115b25184](https://linux-hardware.org/?probe=6115b25184) | Dec 18, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [8507460974](https://linux-hardware.org/?probe=8507460974) | Dec 18, 2023 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [fe9179b1fb](https://linux-hardware.org/?probe=fe9179b1fb) | Dec 16, 2023 |
| Gigabyte      | 970-GAMING                  | Desktop     | [f1f6a55f9c](https://linux-hardware.org/?probe=f1f6a55f9c) | Dec 16, 2023 |
| Gigabyte      | 970-GAMING                  | Desktop     | [8b6e7627f9](https://linux-hardware.org/?probe=8b6e7627f9) | Dec 16, 2023 |
| HP            | G62                         | Notebook    | [fd110d99fd](https://linux-hardware.org/?probe=fd110d99fd) | Dec 15, 2023 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | Notebook    | [d438fe20ff](https://linux-hardware.org/?probe=d438fe20ff) | Dec 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | Notebook    | [42b02a9d8e](https://linux-hardware.org/?probe=42b02a9d8e) | Dec 14, 2023 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [57cc6cbccf](https://linux-hardware.org/?probe=57cc6cbccf) | Dec 14, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [27c22f0c94](https://linux-hardware.org/?probe=27c22f0c94) | Dec 14, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [22dfb202b4](https://linux-hardware.org/?probe=22dfb202b4) | Dec 12, 2023 |
| Lenovo        | IdeaPad D330-10IGL 82H0     | Tablet      | [a73b0c39f2](https://linux-hardware.org/?probe=a73b0c39f2) | Dec 12, 2023 |
| Lenovo        | IdeaPad D330-10IGL 82H0     | Tablet      | [b569f37962](https://linux-hardware.org/?probe=b569f37962) | Dec 11, 2023 |
| HP            | Laptop                      | Notebook    | [8bdb6d048e](https://linux-hardware.org/?probe=8bdb6d048e) | Dec 11, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [281cfa9ff7](https://linux-hardware.org/?probe=281cfa9ff7) | Dec 11, 2023 |
| HP            | Laptop                      | Notebook    | [b5d2cf7074](https://linux-hardware.org/?probe=b5d2cf7074) | Dec 10, 2023 |
| Acer          | Nitro AN517-41              | Notebook    | [6e5abc0ea5](https://linux-hardware.org/?probe=6e5abc0ea5) | Dec 10, 2023 |
| Gigabyte      | P55-UD3                     | Desktop     | [4c20f6a826](https://linux-hardware.org/?probe=4c20f6a826) | Dec 10, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [3a6b7f5ae4](https://linux-hardware.org/?probe=3a6b7f5ae4) | Dec 09, 2023 |
| Notebook      | N24_25JU                    | Notebook    | [170b205714](https://linux-hardware.org/?probe=170b205714) | Dec 09, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [6f35ce12bd](https://linux-hardware.org/?probe=6f35ce12bd) | Dec 07, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [2edc689735](https://linux-hardware.org/?probe=2edc689735) | Dec 06, 2023 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [1f68b6b7c7](https://linux-hardware.org/?probe=1f68b6b7c7) | Dec 06, 2023 |
| eMachines     | eME732G                     | Notebook    | [d94dd62bf1](https://linux-hardware.org/?probe=d94dd62bf1) | Dec 05, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e90c011500](https://linux-hardware.org/?probe=e90c011500) | Dec 05, 2023 |
| Acer          | Aspire A314-22              | Notebook    | [daa41db960](https://linux-hardware.org/?probe=daa41db960) | Dec 05, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [57a63775b2](https://linux-hardware.org/?probe=57a63775b2) | Dec 05, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [e6e58d5148](https://linux-hardware.org/?probe=e6e58d5148) | Dec 05, 2023 |
| Samsung       | 730QED                      | Convertible | [e7b8057036](https://linux-hardware.org/?probe=e7b8057036) | Dec 04, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [8fd5e3b166](https://linux-hardware.org/?probe=8fd5e3b166) | Dec 04, 2023 |
| eMachines     | eME732G                     | Notebook    | [931569e396](https://linux-hardware.org/?probe=931569e396) | Dec 03, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [abb3c226ed](https://linux-hardware.org/?probe=abb3c226ed) | Dec 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [ff37eb859a](https://linux-hardware.org/?probe=ff37eb859a) | Dec 02, 2023 |
| ASUSTek       | M4A88TD-M EVO               | Desktop     | [7f6b5fd810](https://linux-hardware.org/?probe=7f6b5fd810) | Dec 01, 2023 |
| Lenovo        | K14 G2 IRU 21G1             | Notebook    | [b52ce46b0d](https://linux-hardware.org/?probe=b52ce46b0d) | Dec 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [88bd7270db](https://linux-hardware.org/?probe=88bd7270db) | Dec 01, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [be4ecb6dfa](https://linux-hardware.org/?probe=be4ecb6dfa) | Nov 29, 2023 |
| ASUSTek       | P7P55D-E PRO                | Desktop     | [6fe23dd80e](https://linux-hardware.org/?probe=6fe23dd80e) | Nov 28, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [1f830eb37e](https://linux-hardware.org/?probe=1f830eb37e) | Nov 27, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [e38428746a](https://linux-hardware.org/?probe=e38428746a) | Nov 27, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [12e26441e1](https://linux-hardware.org/?probe=12e26441e1) | Nov 27, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [4b4737d484](https://linux-hardware.org/?probe=4b4737d484) | Nov 27, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [8474959120](https://linux-hardware.org/?probe=8474959120) | Nov 26, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [c166853e23](https://linux-hardware.org/?probe=c166853e23) | Nov 26, 2023 |
| ASUSTek       | ROG STRIX B460-I GAMING     | Desktop     | [7a0adaf9f3](https://linux-hardware.org/?probe=7a0adaf9f3) | Nov 25, 2023 |
| ASUSTek       | ROG STRIX B460-I GAMING     | Desktop     | [b96e460a4f](https://linux-hardware.org/?probe=b96e460a4f) | Nov 25, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [7c92224aed](https://linux-hardware.org/?probe=7c92224aed) | Nov 25, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [57a3d9064a](https://linux-hardware.org/?probe=57a3d9064a) | Nov 25, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [a4c63ff9b4](https://linux-hardware.org/?probe=a4c63ff9b4) | Nov 25, 2023 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | Notebook    | [2b5e71ca1e](https://linux-hardware.org/?probe=2b5e71ca1e) | Nov 24, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [48112cbfe0](https://linux-hardware.org/?probe=48112cbfe0) | Nov 24, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [1ad50e2862](https://linux-hardware.org/?probe=1ad50e2862) | Nov 23, 2023 |
| Lenovo        | 1037 SDK0Q40104 WIN 3305... | Server      | [7b466d7f56](https://linux-hardware.org/?probe=7b466d7f56) | Nov 22, 2023 |
| BESSTAR Te... | TH50                        | Desktop     | [39c4acf035](https://linux-hardware.org/?probe=39c4acf035) | Nov 22, 2023 |
| Acer          | Aspire E1-570               | Notebook    | [8c6fd80245](https://linux-hardware.org/?probe=8c6fd80245) | Nov 22, 2023 |
| Lenovo        | ThinkCentre M91p 4518A31    | Desktop     | [9031421465](https://linux-hardware.org/?probe=9031421465) | Nov 22, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [195e3a2ce6](https://linux-hardware.org/?probe=195e3a2ce6) | Nov 22, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [cd86a8c45b](https://linux-hardware.org/?probe=cd86a8c45b) | Nov 22, 2023 |
| HP            | 2AA7 H                      | Desktop     | [c98041f477](https://linux-hardware.org/?probe=c98041f477) | Nov 21, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [6066ce2199](https://linux-hardware.org/?probe=6066ce2199) | Nov 20, 2023 |
| PC Special... | Lafite Pro II 15            | Notebook    | [b7b85ab8ce](https://linux-hardware.org/?probe=b7b85ab8ce) | Nov 20, 2023 |
| Dell          | 0YJPT1 A00                  | Desktop     | [7728c1ff4c](https://linux-hardware.org/?probe=7728c1ff4c) | Nov 20, 2023 |
| HP            | ProBook 430 G6              | Notebook    | [6175f06df9](https://linux-hardware.org/?probe=6175f06df9) | Nov 20, 2023 |
| Dell          | 02M8NY A00                  | Desktop     | [dd2bdfb403](https://linux-hardware.org/?probe=dd2bdfb403) | Nov 20, 2023 |
| HP            | Pavilion 17                 | Notebook    | [00c2d45d1d](https://linux-hardware.org/?probe=00c2d45d1d) | Nov 19, 2023 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [883da32584](https://linux-hardware.org/?probe=883da32584) | Nov 18, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [2902bc3e9f](https://linux-hardware.org/?probe=2902bc3e9f) | Nov 15, 2023 |
| Dell          | Latitude 5521               | Notebook    | [2cd2e72764](https://linux-hardware.org/?probe=2cd2e72764) | Nov 15, 2023 |
| Dell          | Latitude E7450              | Notebook    | [500f23ef78](https://linux-hardware.org/?probe=500f23ef78) | Nov 14, 2023 |
| HP            | ProBook 6570b               | Notebook    | [edf0d74b51](https://linux-hardware.org/?probe=edf0d74b51) | Nov 14, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [b158de590e](https://linux-hardware.org/?probe=b158de590e) | Nov 14, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [25455f055b](https://linux-hardware.org/?probe=25455f055b) | Nov 14, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [0874caf8a9](https://linux-hardware.org/?probe=0874caf8a9) | Nov 13, 2023 |
| ASRock        | B760M Steel Legend WiFi     | Desktop     | [8fd2ed0ba7](https://linux-hardware.org/?probe=8fd2ed0ba7) | Nov 13, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [2166a882d2](https://linux-hardware.org/?probe=2166a882d2) | Nov 13, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [872e6f2ca5](https://linux-hardware.org/?probe=872e6f2ca5) | Nov 12, 2023 |
| HP            | Pavilion g6                 | Notebook    | [1215d8475b](https://linux-hardware.org/?probe=1215d8475b) | Nov 11, 2023 |
| Lenovo        | ThinkPad T480s 20L7001MH... | Notebook    | [f5c3846dce](https://linux-hardware.org/?probe=f5c3846dce) | Nov 10, 2023 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [85e2b37a15](https://linux-hardware.org/?probe=85e2b37a15) | Nov 10, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [ecb49b0454](https://linux-hardware.org/?probe=ecb49b0454) | Nov 09, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [5b67ed0642](https://linux-hardware.org/?probe=5b67ed0642) | Nov 09, 2023 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [34c0a2ec4c](https://linux-hardware.org/?probe=34c0a2ec4c) | Nov 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [8ef23bbac8](https://linux-hardware.org/?probe=8ef23bbac8) | Nov 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [003be2f197](https://linux-hardware.org/?probe=003be2f197) | Nov 07, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [9b3ffcb3d5](https://linux-hardware.org/?probe=9b3ffcb3d5) | Nov 07, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [01884ea8de](https://linux-hardware.org/?probe=01884ea8de) | Nov 07, 2023 |
| Dell          | Precision 3561              | Notebook    | [8fd1f7d515](https://linux-hardware.org/?probe=8fd1f7d515) | Nov 06, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [b5e4afb8e9](https://linux-hardware.org/?probe=b5e4afb8e9) | Nov 06, 2023 |
| Lenovo        | ThinkPad T480 20L6S5VP3U    | Notebook    | [ea70f0e597](https://linux-hardware.org/?probe=ea70f0e597) | Nov 05, 2023 |
| Dell          | 08WKV3 A00                  | Desktop     | [e16dbbaf8b](https://linux-hardware.org/?probe=e16dbbaf8b) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [4f690a4297](https://linux-hardware.org/?probe=4f690a4297) | Nov 05, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [f154c5979f](https://linux-hardware.org/?probe=f154c5979f) | Nov 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [85733c0ec0](https://linux-hardware.org/?probe=85733c0ec0) | Nov 05, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [8a4147b40a](https://linux-hardware.org/?probe=8a4147b40a) | Nov 05, 2023 |
| Tactus        | GeoFlex 140                 | Convertible | [a386eceffe](https://linux-hardware.org/?probe=a386eceffe) | Nov 05, 2023 |
| Tactus        | GeoFlex 140                 | Convertible | [1e6407d9d5](https://linux-hardware.org/?probe=1e6407d9d5) | Nov 04, 2023 |
| Gigabyte      | H81M-DS2                    | Desktop     | [5ac9818b1f](https://linux-hardware.org/?probe=5ac9818b1f) | Nov 03, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [c9e7b12e63](https://linux-hardware.org/?probe=c9e7b12e63) | Nov 03, 2023 |
| Dell          | Latitude E7470              | Notebook    | [343fdc858a](https://linux-hardware.org/?probe=343fdc858a) | Nov 03, 2023 |
| Gigabyte      | P35-DS3L                    | Desktop     | [c2df6f267b](https://linux-hardware.org/?probe=c2df6f267b) | Nov 03, 2023 |
| Acer          | Aspire A515-43              | Notebook    | [6aa1f3a294](https://linux-hardware.org/?probe=6aa1f3a294) | Nov 02, 2023 |
| Acer          | Aspire A515-43              | Notebook    | [3e65346dfd](https://linux-hardware.org/?probe=3e65346dfd) | Nov 02, 2023 |
| ASRock        | H61M-VS                     | Desktop     | [677490b7c2](https://linux-hardware.org/?probe=677490b7c2) | Nov 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [0f4435d620](https://linux-hardware.org/?probe=0f4435d620) | Nov 02, 2023 |
| Lenovo        | ThinkBook 14p Gen 3 21EJ    | Notebook    | [cde7923bf2](https://linux-hardware.org/?probe=cde7923bf2) | Nov 01, 2023 |
| MSI           | B450-A PRO                  | Desktop     | [f0b1ef4bc8](https://linux-hardware.org/?probe=f0b1ef4bc8) | Nov 01, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [50a30d4ebd](https://linux-hardware.org/?probe=50a30d4ebd) | Nov 01, 2023 |
| Acer          | Aspire A517-52G             | Notebook    | [f65225d50a](https://linux-hardware.org/?probe=f65225d50a) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [5acc8f68a0](https://linux-hardware.org/?probe=5acc8f68a0) | Nov 01, 2023 |
| Acer          | Aspire A517-52G             | Notebook    | [69f7a5ebed](https://linux-hardware.org/?probe=69f7a5ebed) | Nov 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [8a2a3561ab](https://linux-hardware.org/?probe=8a2a3561ab) | Nov 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [7271f0fc8c](https://linux-hardware.org/?probe=7271f0fc8c) | Nov 01, 2023 |
| HP            | 2AF7                        | Desktop     | [0a2c239b75](https://linux-hardware.org/?probe=0a2c239b75) | Nov 01, 2023 |
| Dell          | Latitude 7290               | Notebook    | [b7170343fb](https://linux-hardware.org/?probe=b7170343fb) | Oct 31, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [98d01105c7](https://linux-hardware.org/?probe=98d01105c7) | Oct 31, 2023 |
| ASRock        | H110 Pro BTC+               | Desktop     | [c889a29b7f](https://linux-hardware.org/?probe=c889a29b7f) | Oct 31, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [77d9982cf2](https://linux-hardware.org/?probe=77d9982cf2) | Oct 31, 2023 |
| Acer          | Aspire AV15-51              | Notebook    | [84064baf19](https://linux-hardware.org/?probe=84064baf19) | Oct 31, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [babfdba8f2](https://linux-hardware.org/?probe=babfdba8f2) | Oct 30, 2023 |
| Dell          | Latitude 5530               | Notebook    | [1731342e23](https://linux-hardware.org/?probe=1731342e23) | Oct 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [986edacf9a](https://linux-hardware.org/?probe=986edacf9a) | Oct 30, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [9b3c09e73a](https://linux-hardware.org/?probe=9b3c09e73a) | Oct 27, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [40769bf0a3](https://linux-hardware.org/?probe=40769bf0a3) | Oct 27, 2023 |
| MSI           | B250M PRO-VDH               | Desktop     | [c3d5a72f41](https://linux-hardware.org/?probe=c3d5a72f41) | Oct 27, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [3831a70240](https://linux-hardware.org/?probe=3831a70240) | Oct 27, 2023 |
| EXTRA Comp... | MS-1758                     | Notebook    | [eced546e79](https://linux-hardware.org/?probe=eced546e79) | Oct 26, 2023 |
| HP            | Pavilion 17                 | Notebook    | [9eb519ce8c](https://linux-hardware.org/?probe=9eb519ce8c) | Oct 26, 2023 |
| HP            | Pavilion 17                 | Notebook    | [9b004ab742](https://linux-hardware.org/?probe=9b004ab742) | Oct 26, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [f956ab0313](https://linux-hardware.org/?probe=f956ab0313) | Oct 26, 2023 |
| SYWZ          | S210H Series                | Desktop     | [9239922f80](https://linux-hardware.org/?probe=9239922f80) | Oct 26, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [e25ec0e229](https://linux-hardware.org/?probe=e25ec0e229) | Oct 25, 2023 |
| HP            | Pavilion g7                 | Notebook    | [3bd963fd9e](https://linux-hardware.org/?probe=3bd963fd9e) | Oct 24, 2023 |
| ASUSTek       | K56CM                       | Notebook    | [a5437fcab8](https://linux-hardware.org/?probe=a5437fcab8) | Oct 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c74b24edc0](https://linux-hardware.org/?probe=c74b24edc0) | Oct 23, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [4f269eeaa7](https://linux-hardware.org/?probe=4f269eeaa7) | Oct 23, 2023 |
| ASRockRack    | ROMED8-2T                   | Desktop     | [d71e04d478](https://linux-hardware.org/?probe=d71e04d478) | Oct 23, 2023 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | Notebook    | [55c5bbce9f](https://linux-hardware.org/?probe=55c5bbce9f) | Oct 23, 2023 |
| Gigabyte      | Z77X-UP7                    | Desktop     | [806cdb2bef](https://linux-hardware.org/?probe=806cdb2bef) | Oct 23, 2023 |
| AZW           | SEi                         | Notebook    | [94602bd41b](https://linux-hardware.org/?probe=94602bd41b) | Oct 22, 2023 |
| Gigabyte      | GA-890FXA-UD5               | Desktop     | [bd8cdfe190](https://linux-hardware.org/?probe=bd8cdfe190) | Oct 22, 2023 |
| HP            | ProBook 4340s               | Notebook    | [8746af78f7](https://linux-hardware.org/?probe=8746af78f7) | Oct 22, 2023 |
| ECS           | CHICAGO2                    | Desktop     | [e33ec52f5a](https://linux-hardware.org/?probe=e33ec52f5a) | Oct 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [130d199934](https://linux-hardware.org/?probe=130d199934) | Oct 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [f23d0ff7da](https://linux-hardware.org/?probe=f23d0ff7da) | Oct 20, 2023 |
| Dell          | Latitude E7470              | Notebook    | [4870f90403](https://linux-hardware.org/?probe=4870f90403) | Oct 20, 2023 |
| MACHENIKE     | MACHCREATOR-16              | Notebook    | [91f29a5a63](https://linux-hardware.org/?probe=91f29a5a63) | Oct 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [09b04f5fd5](https://linux-hardware.org/?probe=09b04f5fd5) | Oct 20, 2023 |
| Lenovo        | ThinkBook 14p Gen 3 21EJ    | Notebook    | [4bfe18fe76](https://linux-hardware.org/?probe=4bfe18fe76) | Oct 20, 2023 |
| Lenovo        | ThinkBook 14p Gen 3 21EJ    | Notebook    | [e83ad29e5e](https://linux-hardware.org/?probe=e83ad29e5e) | Oct 20, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [a0cdc0c3e1](https://linux-hardware.org/?probe=a0cdc0c3e1) | Oct 19, 2023 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | Desktop     | [c2215ccabb](https://linux-hardware.org/?probe=c2215ccabb) | Oct 19, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [aad7482915](https://linux-hardware.org/?probe=aad7482915) | Oct 19, 2023 |
| HP            | G60                         | Notebook    | [3c3f75c072](https://linux-hardware.org/?probe=3c3f75c072) | Oct 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [495a705c9e](https://linux-hardware.org/?probe=495a705c9e) | Oct 18, 2023 |
| Dell          | Precision 7520              | Notebook    | [bd78f68578](https://linux-hardware.org/?probe=bd78f68578) | Oct 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [6fe57753a4](https://linux-hardware.org/?probe=6fe57753a4) | Oct 17, 2023 |
| Lenovo        | 01KN179                     | Server      | [9f36a4143d](https://linux-hardware.org/?probe=9f36a4143d) | Oct 16, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [02bc0ccf6d](https://linux-hardware.org/?probe=02bc0ccf6d) | Oct 16, 2023 |
| AMI           | Intel                       | Convertible | [38a3df30fe](https://linux-hardware.org/?probe=38a3df30fe) | Oct 15, 2023 |
| Dell          | Latitude E7470              | Notebook    | [59258fc186](https://linux-hardware.org/?probe=59258fc186) | Oct 15, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [88c47cfb66](https://linux-hardware.org/?probe=88c47cfb66) | Oct 15, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [92049beb26](https://linux-hardware.org/?probe=92049beb26) | Oct 15, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [3eff97b04d](https://linux-hardware.org/?probe=3eff97b04d) | Oct 15, 2023 |
| HP            | 829A                        | Mini pc     | [f9af7b48fe](https://linux-hardware.org/?probe=f9af7b48fe) | Oct 14, 2023 |
| MSI           | B560M PRO                   | Desktop     | [1dba250310](https://linux-hardware.org/?probe=1dba250310) | Oct 14, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [a03109d57a](https://linux-hardware.org/?probe=a03109d57a) | Oct 14, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [007ce9ca02](https://linux-hardware.org/?probe=007ce9ca02) | Oct 14, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [09a90189ec](https://linux-hardware.org/?probe=09a90189ec) | Oct 14, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [f18ac93db8](https://linux-hardware.org/?probe=f18ac93db8) | Oct 13, 2023 |
| MSI           | B85-G43                     | Desktop     | [8684995c92](https://linux-hardware.org/?probe=8684995c92) | Oct 13, 2023 |
| Dell          | Latitude 7490               | Notebook    | [b5e38fe27e](https://linux-hardware.org/?probe=b5e38fe27e) | Oct 13, 2023 |
| Acer          | Aspire 5250                 | Notebook    | [bef1086dfe](https://linux-hardware.org/?probe=bef1086dfe) | Oct 12, 2023 |
| HP            | EliteBook 8770w             | Notebook    | [bf26581f5d](https://linux-hardware.org/?probe=bf26581f5d) | Oct 12, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [f48331f12b](https://linux-hardware.org/?probe=f48331f12b) | Oct 12, 2023 |
| Dell          | Vostro 5490                 | Notebook    | [616aecbfbd](https://linux-hardware.org/?probe=616aecbfbd) | Oct 11, 2023 |
| Alienware     | m16 R1                      | Notebook    | [6ea5ba513f](https://linux-hardware.org/?probe=6ea5ba513f) | Oct 11, 2023 |
| Alienware     | m16 R1                      | Notebook    | [f9c4374e7c](https://linux-hardware.org/?probe=f9c4374e7c) | Oct 11, 2023 |
| Dell          | Latitude 5511               | Notebook    | [164cc57420](https://linux-hardware.org/?probe=164cc57420) | Oct 10, 2023 |
| Dell          | Latitude 5511               | Notebook    | [9827df8ea8](https://linux-hardware.org/?probe=9827df8ea8) | Oct 10, 2023 |
| Dell          | Latitude 5530               | Notebook    | [95ec4384f9](https://linux-hardware.org/?probe=95ec4384f9) | Oct 10, 2023 |
| Dell          | Latitude 5530               | Notebook    | [4d218edfa4](https://linux-hardware.org/?probe=4d218edfa4) | Oct 10, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [3ba4207fd0](https://linux-hardware.org/?probe=3ba4207fd0) | Oct 09, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [f6dac1e5f6](https://linux-hardware.org/?probe=f6dac1e5f6) | Oct 09, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [1996d5a1ff](https://linux-hardware.org/?probe=1996d5a1ff) | Oct 08, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [84ff0a9a08](https://linux-hardware.org/?probe=84ff0a9a08) | Oct 07, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [1505f63948](https://linux-hardware.org/?probe=1505f63948) | Oct 07, 2023 |
| Medion        | E15302                      | Notebook    | [d26c76cedf](https://linux-hardware.org/?probe=d26c76cedf) | Oct 07, 2023 |
| TUXEDO        | Book XP15 / XP17 Gen12      | Notebook    | [5ff0e17804](https://linux-hardware.org/?probe=5ff0e17804) | Oct 07, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [5ac03d658c](https://linux-hardware.org/?probe=5ac03d658c) | Oct 07, 2023 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [7e01bc1824](https://linux-hardware.org/?probe=7e01bc1824) | Oct 06, 2023 |
| ASUSTek       | Z87-PRO                     | Desktop     | [31248aa2bf](https://linux-hardware.org/?probe=31248aa2bf) | Oct 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [5b84610e15](https://linux-hardware.org/?probe=5b84610e15) | Oct 06, 2023 |
| Lenovo        | Yoga Creator 7 15IMH05 8... | Notebook    | [e796c2f9ba](https://linux-hardware.org/?probe=e796c2f9ba) | Oct 05, 2023 |
| Dell          | Latitude 7490               | Notebook    | [ff1fcbaff6](https://linux-hardware.org/?probe=ff1fcbaff6) | Oct 04, 2023 |
| Dell          | Latitude 7490               | Notebook    | [7eca4901d4](https://linux-hardware.org/?probe=7eca4901d4) | Oct 04, 2023 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [57b1771805](https://linux-hardware.org/?probe=57b1771805) | Oct 04, 2023 |
| Lenovo        | IdeaPad S540-13IML 81XA     | Notebook    | [2fdd309c6a](https://linux-hardware.org/?probe=2fdd309c6a) | Oct 04, 2023 |
| ASUSTek       | E2KM1I-DELUXE               | Desktop     | [bb9493309a](https://linux-hardware.org/?probe=bb9493309a) | Oct 04, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3f7231bda4](https://linux-hardware.org/?probe=3f7231bda4) | Oct 03, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [f349819e0a](https://linux-hardware.org/?probe=f349819e0a) | Oct 02, 2023 |
| Google        | Blorb                       | Notebook    | [04e37bafe3](https://linux-hardware.org/?probe=04e37bafe3) | Oct 02, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [122f1d4ca8](https://linux-hardware.org/?probe=122f1d4ca8) | Oct 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [f8ee109cbd](https://linux-hardware.org/?probe=f8ee109cbd) | Oct 01, 2023 |
| Schenker      | VIA 15 Pro (M22)            | Notebook    | [1919690674](https://linux-hardware.org/?probe=1919690674) | Oct 01, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [ffd2e0d99d](https://linux-hardware.org/?probe=ffd2e0d99d) | Oct 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [1448f32279](https://linux-hardware.org/?probe=1448f32279) | Oct 01, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [48ff113276](https://linux-hardware.org/?probe=48ff113276) | Sep 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [3421ba07f9](https://linux-hardware.org/?probe=3421ba07f9) | Sep 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [480316a0da](https://linux-hardware.org/?probe=480316a0da) | Sep 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [cd9628c344](https://linux-hardware.org/?probe=cd9628c344) | Sep 29, 2023 |
| Alienware     | x15 R1                      | Notebook    | [a34b343fce](https://linux-hardware.org/?probe=a34b343fce) | Sep 29, 2023 |
| ASUSTek       | EB1501P                     | Desktop     | [df48fa7e96](https://linux-hardware.org/?probe=df48fa7e96) | Sep 29, 2023 |
| ASUSTek       | K72Jr                       | Notebook    | [9167494336](https://linux-hardware.org/?probe=9167494336) | Sep 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [a329c5630e](https://linux-hardware.org/?probe=a329c5630e) | Sep 28, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [e54490e96a](https://linux-hardware.org/?probe=e54490e96a) | Sep 27, 2023 |
| HP            | EliteBook 8770w             | Notebook    | [3286090099](https://linux-hardware.org/?probe=3286090099) | Sep 27, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [2f574aa287](https://linux-hardware.org/?probe=2f574aa287) | Sep 27, 2023 |
| Acer          | FX58M                       | Desktop     | [e24f36e0bd](https://linux-hardware.org/?probe=e24f36e0bd) | Sep 26, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [37840dad1c](https://linux-hardware.org/?probe=37840dad1c) | Sep 26, 2023 |
| Lenovo        | B480 20140                  | Notebook    | [960fe0be2b](https://linux-hardware.org/?probe=960fe0be2b) | Sep 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [56cd5e0bfd](https://linux-hardware.org/?probe=56cd5e0bfd) | Sep 25, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [2691aa5f87](https://linux-hardware.org/?probe=2691aa5f87) | Sep 24, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [a834cee874](https://linux-hardware.org/?probe=a834cee874) | Sep 24, 2023 |
| ASRock        | ALiveXFire-eSATA2           | Desktop     | [7e69c8e2e1](https://linux-hardware.org/?probe=7e69c8e2e1) | Sep 23, 2023 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | Notebook    | [05bf70d208](https://linux-hardware.org/?probe=05bf70d208) | Sep 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ad1f9f63c0](https://linux-hardware.org/?probe=ad1f9f63c0) | Sep 22, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [583c577b02](https://linux-hardware.org/?probe=583c577b02) | Sep 22, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | Desktop     | [16fe0e3ba6](https://linux-hardware.org/?probe=16fe0e3ba6) | Sep 22, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | Desktop     | [aab34fa582](https://linux-hardware.org/?probe=aab34fa582) | Sep 22, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [28c84c64c1](https://linux-hardware.org/?probe=28c84c64c1) | Sep 21, 2023 |
| HP            | 18E7                        | Desktop     | [ba0cb8996d](https://linux-hardware.org/?probe=ba0cb8996d) | Sep 21, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [389282109e](https://linux-hardware.org/?probe=389282109e) | Sep 21, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [c7142a0d96](https://linux-hardware.org/?probe=c7142a0d96) | Sep 20, 2023 |
| Toshiba       | Satellite Pro C70-B         | Notebook    | [a24c6808ba](https://linux-hardware.org/?probe=a24c6808ba) | Sep 20, 2023 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [e753271d63](https://linux-hardware.org/?probe=e753271d63) | Sep 19, 2023 |
| Dell          | Precision 7520              | Notebook    | [99e70bdd81](https://linux-hardware.org/?probe=99e70bdd81) | Sep 19, 2023 |
| ASRock        | Z68 Pro3                    | Desktop     | [4ffee8598b](https://linux-hardware.org/?probe=4ffee8598b) | Sep 19, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [c8a7f18e5d](https://linux-hardware.org/?probe=c8a7f18e5d) | Sep 19, 2023 |
| Dell          | Precision 7520              | Notebook    | [89f1a6a0a5](https://linux-hardware.org/?probe=89f1a6a0a5) | Sep 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [cbfe8b032d](https://linux-hardware.org/?probe=cbfe8b032d) | Sep 18, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [144dcee0ae](https://linux-hardware.org/?probe=144dcee0ae) | Sep 18, 2023 |
| Dell          | Inspiron 5520               | Notebook    | [91404ec81d](https://linux-hardware.org/?probe=91404ec81d) | Sep 17, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [5a9f4e8791](https://linux-hardware.org/?probe=5a9f4e8791) | Sep 17, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [e6db76aa66](https://linux-hardware.org/?probe=e6db76aa66) | Sep 17, 2023 |
| HP            | Compaq 6820s                | Notebook    | [99a625283d](https://linux-hardware.org/?probe=99a625283d) | Sep 16, 2023 |
| HP            | Compaq 6820s                | Notebook    | [2ae8b9ac9d](https://linux-hardware.org/?probe=2ae8b9ac9d) | Sep 16, 2023 |
| ASUSTek       | Z97-PRO                     | Desktop     | [37d6d12772](https://linux-hardware.org/?probe=37d6d12772) | Sep 15, 2023 |
| Lenovo        | 1037 SDK0Q40104 WIN 3305... | Server      | [fabf2bef4c](https://linux-hardware.org/?probe=fabf2bef4c) | Sep 15, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [a32457e14d](https://linux-hardware.org/?probe=a32457e14d) | Sep 15, 2023 |
| HP            | 0A9Ch                       | Desktop     | [4894ac01b8](https://linux-hardware.org/?probe=4894ac01b8) | Sep 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [15256fdeb2](https://linux-hardware.org/?probe=15256fdeb2) | Sep 14, 2023 |
| Notebook      | P65_P67SA                   | Notebook    | [4d11ae0ff7](https://linux-hardware.org/?probe=4d11ae0ff7) | Sep 13, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [8f3c4bff98](https://linux-hardware.org/?probe=8f3c4bff98) | Sep 13, 2023 |
| HP            | 1998                        | Desktop     | [c3451afea8](https://linux-hardware.org/?probe=c3451afea8) | Sep 11, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [53139247c9](https://linux-hardware.org/?probe=53139247c9) | Sep 10, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [938cec3228](https://linux-hardware.org/?probe=938cec3228) | Sep 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [4e30077177](https://linux-hardware.org/?probe=4e30077177) | Sep 08, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [7ce5ebe4bc](https://linux-hardware.org/?probe=7ce5ebe4bc) | Sep 07, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [eb92b04384](https://linux-hardware.org/?probe=eb92b04384) | Sep 06, 2023 |
| ASUSTek       | X580VD                      | Notebook    | [989134a7c5](https://linux-hardware.org/?probe=989134a7c5) | Sep 06, 2023 |
| Alienware     | 0H869M A00                  | Desktop     | [64132daa63](https://linux-hardware.org/?probe=64132daa63) | Sep 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [cf9c65c6f4](https://linux-hardware.org/?probe=cf9c65c6f4) | Sep 06, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [d2ae9b900d](https://linux-hardware.org/?probe=d2ae9b900d) | Sep 06, 2023 |
| Dell          | Latitude 7490               | Notebook    | [2a945e76de](https://linux-hardware.org/?probe=2a945e76de) | Sep 05, 2023 |
| Dell          | Inspiron 3480               | Notebook    | [3d639d27ba](https://linux-hardware.org/?probe=3d639d27ba) | Sep 05, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [1cd7fc15b1](https://linux-hardware.org/?probe=1cd7fc15b1) | Sep 05, 2023 |
| ASUSTek       | S400CA                      | Notebook    | [453335f199](https://linux-hardware.org/?probe=453335f199) | Sep 04, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [7944dc4ca2](https://linux-hardware.org/?probe=7944dc4ca2) | Sep 04, 2023 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [2dff249b45](https://linux-hardware.org/?probe=2dff249b45) | Sep 04, 2023 |
| Dell          | Latitude E6500              | Notebook    | [6199709334](https://linux-hardware.org/?probe=6199709334) | Sep 04, 2023 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [515a81a0d1](https://linux-hardware.org/?probe=515a81a0d1) | Sep 03, 2023 |
| Dell          | Latitude E6500              | Notebook    | [308d8d0f19](https://linux-hardware.org/?probe=308d8d0f19) | Sep 03, 2023 |
| Fujitsu Si... | LIFEBOOK E8410              | Notebook    | [31618d06c6](https://linux-hardware.org/?probe=31618d06c6) | Sep 02, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [85cc9860f3](https://linux-hardware.org/?probe=85cc9860f3) | Sep 02, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | Notebook    | [2fc5b41456](https://linux-hardware.org/?probe=2fc5b41456) | Sep 02, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [1aeb1ffd17](https://linux-hardware.org/?probe=1aeb1ffd17) | Sep 02, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [9028ba6c0f](https://linux-hardware.org/?probe=9028ba6c0f) | Sep 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [7dabe0d117](https://linux-hardware.org/?probe=7dabe0d117) | Sep 01, 2023 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [b132ff749e](https://linux-hardware.org/?probe=b132ff749e) | Sep 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [d80ee341d8](https://linux-hardware.org/?probe=d80ee341d8) | Sep 01, 2023 |
| Dell          | XPS 9315                    | Notebook    | [5676f0c210](https://linux-hardware.org/?probe=5676f0c210) | Aug 31, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | Notebook    | [3384884acc](https://linux-hardware.org/?probe=3384884acc) | Aug 31, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [17e971c3fb](https://linux-hardware.org/?probe=17e971c3fb) | Aug 31, 2023 |
| Sony          | VPCEC390X                   | Notebook    | [ddad567e2a](https://linux-hardware.org/?probe=ddad567e2a) | Aug 31, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [d9a8673516](https://linux-hardware.org/?probe=d9a8673516) | Aug 31, 2023 |
| AZW           | MINI S                      | Desktop     | [fb828c24eb](https://linux-hardware.org/?probe=fb828c24eb) | Aug 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2906fc34f6](https://linux-hardware.org/?probe=2906fc34f6) | Aug 30, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [ca4ddb2663](https://linux-hardware.org/?probe=ca4ddb2663) | Aug 29, 2023 |
| HP            | 212B                        | Desktop     | [80b2496334](https://linux-hardware.org/?probe=80b2496334) | Aug 29, 2023 |
| Fujitsu       | LIFEBOOK U9312              | Notebook    | [891b276812](https://linux-hardware.org/?probe=891b276812) | Aug 28, 2023 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [ae73127da5](https://linux-hardware.org/?probe=ae73127da5) | Aug 28, 2023 |
| Dell          | Vostro 3501                 | Notebook    | [0211379a67](https://linux-hardware.org/?probe=0211379a67) | Aug 27, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | Notebook    | [69a4a078cd](https://linux-hardware.org/?probe=69a4a078cd) | Aug 27, 2023 |
| HP            | 18E7                        | Desktop     | [0b94065a0f](https://linux-hardware.org/?probe=0b94065a0f) | Aug 27, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [cf2cba5c59](https://linux-hardware.org/?probe=cf2cba5c59) | Aug 26, 2023 |
| mPTech        | ARC 11.6 128GB HD           | Notebook    | [4167149587](https://linux-hardware.org/?probe=4167149587) | Aug 26, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [efa1e38911](https://linux-hardware.org/?probe=efa1e38911) | Aug 26, 2023 |
| MSI           | 990FXA GAMING               | Desktop     | [813d9c9c10](https://linux-hardware.org/?probe=813d9c9c10) | Aug 26, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [5004de7897](https://linux-hardware.org/?probe=5004de7897) | Aug 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [d0de544ecd](https://linux-hardware.org/?probe=d0de544ecd) | Aug 25, 2023 |
| Lenovo        | IdeaPad Z580                | Notebook    | [b84eb0a6fa](https://linux-hardware.org/?probe=b84eb0a6fa) | Aug 24, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [0161911081](https://linux-hardware.org/?probe=0161911081) | Aug 24, 2023 |
| MSI           | GL65 9SE                    | Notebook    | [aa162e5634](https://linux-hardware.org/?probe=aa162e5634) | Aug 22, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [aee37b4a93](https://linux-hardware.org/?probe=aee37b4a93) | Aug 21, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [8c6f4a2e1c](https://linux-hardware.org/?probe=8c6f4a2e1c) | Aug 21, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [4d631eed0e](https://linux-hardware.org/?probe=4d631eed0e) | Aug 21, 2023 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [bb5a7dc0d8](https://linux-hardware.org/?probe=bb5a7dc0d8) | Aug 21, 2023 |
| HP            | ElitePad 1000 G2            | Notebook    | [bb21bd2dbc](https://linux-hardware.org/?probe=bb21bd2dbc) | Aug 21, 2023 |
| Fujitsu       | D3602-A1 S26361-D3602-A1    | Desktop     | [8144c6d466](https://linux-hardware.org/?probe=8144c6d466) | Aug 21, 2023 |
| Dell          | Latitude E6520              | Notebook    | [923d01a34f](https://linux-hardware.org/?probe=923d01a34f) | Aug 21, 2023 |
| Schenker      | XMG PRO (E23)               | Notebook    | [9b1639077c](https://linux-hardware.org/?probe=9b1639077c) | Aug 20, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [df48f3ca66](https://linux-hardware.org/?probe=df48f3ca66) | Aug 19, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [ed75b0702f](https://linux-hardware.org/?probe=ed75b0702f) | Aug 19, 2023 |
| MSI           | B250M MORTAR                | Desktop     | [fc97ccab18](https://linux-hardware.org/?probe=fc97ccab18) | Aug 17, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS WI... | Desktop     | [1962f7a581](https://linux-hardware.org/?probe=1962f7a581) | Aug 17, 2023 |
| Intel         | D53427RKE G87971-402        | Desktop     | [433dcaffa6](https://linux-hardware.org/?probe=433dcaffa6) | Aug 17, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [ace741b68a](https://linux-hardware.org/?probe=ace741b68a) | Aug 17, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [e9f564475b](https://linux-hardware.org/?probe=e9f564475b) | Aug 16, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [41b9b0bfc9](https://linux-hardware.org/?probe=41b9b0bfc9) | Aug 14, 2023 |
| ASUSTek       | N53SV                       | Notebook    | [8643d609f2](https://linux-hardware.org/?probe=8643d609f2) | Aug 14, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [29aa72820d](https://linux-hardware.org/?probe=29aa72820d) | Aug 14, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [83dd0f7fe7](https://linux-hardware.org/?probe=83dd0f7fe7) | Aug 14, 2023 |
| LG Electro... | 17Z90N-V.AA72A8             | Notebook    | [28e815418c](https://linux-hardware.org/?probe=28e815418c) | Aug 13, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [7ad086cf8b](https://linux-hardware.org/?probe=7ad086cf8b) | Aug 13, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [e2fe66aca4](https://linux-hardware.org/?probe=e2fe66aca4) | Aug 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [307eb30c27](https://linux-hardware.org/?probe=307eb30c27) | Aug 13, 2023 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [760a5d6077](https://linux-hardware.org/?probe=760a5d6077) | Aug 13, 2023 |
| Dell          | 0GNVHC A00                  | Desktop     | [27e3be4942](https://linux-hardware.org/?probe=27e3be4942) | Aug 12, 2023 |
| ASUSTek       | CM1630                      | Desktop     | [dfd52e2852](https://linux-hardware.org/?probe=dfd52e2852) | Aug 12, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [b4b9fa2d17](https://linux-hardware.org/?probe=b4b9fa2d17) | Aug 12, 2023 |
| ASUSTek       | CM1630                      | Desktop     | [d8f56bcdaf](https://linux-hardware.org/?probe=d8f56bcdaf) | Aug 12, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [181db8cf87](https://linux-hardware.org/?probe=181db8cf87) | Aug 11, 2023 |
| Medion        | P651x series                | Notebook    | [46505da47d](https://linux-hardware.org/?probe=46505da47d) | Aug 11, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [ba03034ac5](https://linux-hardware.org/?probe=ba03034ac5) | Aug 10, 2023 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [be6c815f39](https://linux-hardware.org/?probe=be6c815f39) | Aug 10, 2023 |
| ASUSTek       | Q87M-E                      | Desktop     | [0dee84c129](https://linux-hardware.org/?probe=0dee84c129) | Aug 10, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | Notebook    | [d97ae334a3](https://linux-hardware.org/?probe=d97ae334a3) | Aug 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f28e4b71d6](https://linux-hardware.org/?probe=f28e4b71d6) | Aug 09, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [58d7c4be4c](https://linux-hardware.org/?probe=58d7c4be4c) | Aug 08, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [068b8c5a6f](https://linux-hardware.org/?probe=068b8c5a6f) | Aug 07, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [ebe7ed3f69](https://linux-hardware.org/?probe=ebe7ed3f69) | Aug 07, 2023 |
| Timi          | RedmiBook 14-APCS           | Notebook    | [a0a289f4ee](https://linux-hardware.org/?probe=a0a289f4ee) | Aug 06, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [ec1bd43523](https://linux-hardware.org/?probe=ec1bd43523) | Aug 05, 2023 |
| Dell          | Inspiron 3520               | Notebook    | [00b2c0458a](https://linux-hardware.org/?probe=00b2c0458a) | Aug 05, 2023 |
| HP            | 2AF7                        | Desktop     | [655c896815](https://linux-hardware.org/?probe=655c896815) | Aug 04, 2023 |
| Lenovo        | ThinkPad T480 20L50000MC    | Notebook    | [341698801e](https://linux-hardware.org/?probe=341698801e) | Aug 04, 2023 |
| Dell          | Inspiron 3520               | Notebook    | [6bef2ead01](https://linux-hardware.org/?probe=6bef2ead01) | Aug 04, 2023 |
| Dell          | Latitude 5530               | Notebook    | [dd85033508](https://linux-hardware.org/?probe=dd85033508) | Aug 03, 2023 |
| System76      | Galago Pro                  | Notebook    | [2677fc9a99](https://linux-hardware.org/?probe=2677fc9a99) | Aug 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [3bb1942723](https://linux-hardware.org/?probe=3bb1942723) | Aug 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [7748df9ae9](https://linux-hardware.org/?probe=7748df9ae9) | Aug 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [48c7912f46](https://linux-hardware.org/?probe=48c7912f46) | Aug 01, 2023 |
| MSI           | PRO Z690-A                  | Desktop     | [19f4cb0c69](https://linux-hardware.org/?probe=19f4cb0c69) | Jul 31, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [be7baf7741](https://linux-hardware.org/?probe=be7baf7741) | Jul 31, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [3b0862f434](https://linux-hardware.org/?probe=3b0862f434) | Jul 31, 2023 |
| Dell          | Precision 3571              | Notebook    | [83a85ddae5](https://linux-hardware.org/?probe=83a85ddae5) | Jul 31, 2023 |
| Dell          | Inspiron 16 7610            | Notebook    | [e7befe5a64](https://linux-hardware.org/?probe=e7befe5a64) | Jul 29, 2023 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [0ed7dfdf32](https://linux-hardware.org/?probe=0ed7dfdf32) | Jul 29, 2023 |
| MSI           | X99S SLI PLUS               | Desktop     | [edf7fd3a91](https://linux-hardware.org/?probe=edf7fd3a91) | Jul 28, 2023 |
| Gigabyte      | EP45T-UD3LR                 | Desktop     | [c2928283bd](https://linux-hardware.org/?probe=c2928283bd) | Jul 28, 2023 |
| MSI           | PRO Z690-A                  | Desktop     | [f1a5d69727](https://linux-hardware.org/?probe=f1a5d69727) | Jul 28, 2023 |
| Supermicro    | C7H61                       | Desktop     | [57c9a4eeff](https://linux-hardware.org/?probe=57c9a4eeff) | Jul 27, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [810ff8bbd6](https://linux-hardware.org/?probe=810ff8bbd6) | Jul 26, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [3548050f99](https://linux-hardware.org/?probe=3548050f99) | Jul 26, 2023 |
| Lenovo        | ThinkPad E580 20KS003LLM    | Notebook    | [9bc92a8ef2](https://linux-hardware.org/?probe=9bc92a8ef2) | Jul 26, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [7b7287762f](https://linux-hardware.org/?probe=7b7287762f) | Jul 26, 2023 |
| HP            | G60                         | Notebook    | [4d64158286](https://linux-hardware.org/?probe=4d64158286) | Jul 26, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [914560761d](https://linux-hardware.org/?probe=914560761d) | Jul 25, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [4a1a31cb65](https://linux-hardware.org/?probe=4a1a31cb65) | Jul 25, 2023 |
| Gigabyte      | P67A-UD3-B3                 | Desktop     | [26e7657871](https://linux-hardware.org/?probe=26e7657871) | Jul 23, 2023 |
| MSI           | Z87 MPOWER                  | Desktop     | [dcbda0f556](https://linux-hardware.org/?probe=dcbda0f556) | Jul 23, 2023 |
| HP            | Presario CQ62               | Notebook    | [b736890f88](https://linux-hardware.org/?probe=b736890f88) | Jul 23, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [25fd4c6993](https://linux-hardware.org/?probe=25fd4c6993) | Jul 22, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [e07c3205da](https://linux-hardware.org/?probe=e07c3205da) | Jul 22, 2023 |
| Medion        | H110H4-EM2                  | Desktop     | [443b61cb44](https://linux-hardware.org/?probe=443b61cb44) | Jul 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [e948334857](https://linux-hardware.org/?probe=e948334857) | Jul 22, 2023 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [1a39665e1c](https://linux-hardware.org/?probe=1a39665e1c) | Jul 22, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [38a01d299e](https://linux-hardware.org/?probe=38a01d299e) | Jul 21, 2023 |
| Intel         | DQ57TM AAE70931-402         | Desktop     | [01621f8578](https://linux-hardware.org/?probe=01621f8578) | Jul 21, 2023 |
| Dell          | Latitude 5289               | Convertible | [eeb009e8f5](https://linux-hardware.org/?probe=eeb009e8f5) | Jul 21, 2023 |
| Lenovo        | 3151 SDK0J40697 WIN 3305... | Mini pc     | [3e6dc436dd](https://linux-hardware.org/?probe=3e6dc436dd) | Jul 21, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [620c7f4aec](https://linux-hardware.org/?probe=620c7f4aec) | Jul 21, 2023 |
| Acer          | ConceptD CN715-71           | Notebook    | [ae4de8c5b2](https://linux-hardware.org/?probe=ae4de8c5b2) | Jul 21, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [df9e2bd667](https://linux-hardware.org/?probe=df9e2bd667) | Jul 20, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [4f438fcc8b](https://linux-hardware.org/?probe=4f438fcc8b) | Jul 20, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [26695664a7](https://linux-hardware.org/?probe=26695664a7) | Jul 18, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [d4a4fec7c0](https://linux-hardware.org/?probe=d4a4fec7c0) | Jul 17, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [164e93a53b](https://linux-hardware.org/?probe=164e93a53b) | Jul 16, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [ded2ed05d8](https://linux-hardware.org/?probe=ded2ed05d8) | Jul 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [3caf271d7c](https://linux-hardware.org/?probe=3caf271d7c) | Jul 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [689d391a1d](https://linux-hardware.org/?probe=689d391a1d) | Jul 15, 2023 |
| ASRock        | B85M Pro4                   | Desktop     | [8e53be597f](https://linux-hardware.org/?probe=8e53be597f) | Jul 13, 2023 |
| ASRock        | B85M Pro4                   | Desktop     | [dcb1a242c5](https://linux-hardware.org/?probe=dcb1a242c5) | Jul 13, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [b5374c8055](https://linux-hardware.org/?probe=b5374c8055) | Jul 12, 2023 |
| ASUSTek       | Q87M-E                      | Desktop     | [0d59e226ae](https://linux-hardware.org/?probe=0d59e226ae) | Jul 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [975668f4f1](https://linux-hardware.org/?probe=975668f4f1) | Jul 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [7bc8c956fd](https://linux-hardware.org/?probe=7bc8c956fd) | Jul 10, 2023 |
| Dell          | Latitude E5420              | Notebook    | [6dba8e523b](https://linux-hardware.org/?probe=6dba8e523b) | Jul 09, 2023 |
| Lenovo        | B560 43308UG                | Notebook    | [20ea6219d4](https://linux-hardware.org/?probe=20ea6219d4) | Jul 09, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [41ede144c1](https://linux-hardware.org/?probe=41ede144c1) | Jul 09, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [17c907528f](https://linux-hardware.org/?probe=17c907528f) | Jul 09, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [978a7ef06f](https://linux-hardware.org/?probe=978a7ef06f) | Jul 08, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [7c39787112](https://linux-hardware.org/?probe=7c39787112) | Jul 08, 2023 |
| AWOW          | AR40S                       | Stick pc    | [35b286ba6b](https://linux-hardware.org/?probe=35b286ba6b) | Jul 08, 2023 |
| AWOW          | AR40S                       | Stick pc    | [44eaa3f5c1](https://linux-hardware.org/?probe=44eaa3f5c1) | Jul 08, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [46132f9b9c](https://linux-hardware.org/?probe=46132f9b9c) | Jul 07, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B2502CBA... | Notebook    | [397adc6b70](https://linux-hardware.org/?probe=397adc6b70) | Jul 06, 2023 |
| Dell          | Latitude E6530              | Notebook    | [16581ade55](https://linux-hardware.org/?probe=16581ade55) | Jul 06, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [b1f7c9aea2](https://linux-hardware.org/?probe=b1f7c9aea2) | Jul 06, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [6b250aabab](https://linux-hardware.org/?probe=6b250aabab) | Jul 05, 2023 |
| Lenovo        | ThinkCentre A70 7844H9G     | Desktop     | [46bfb7c0ff](https://linux-hardware.org/?probe=46bfb7c0ff) | Jul 05, 2023 |
| Gigabyte      | Z87-D3HP-CF                 | Desktop     | [7502eb638e](https://linux-hardware.org/?probe=7502eb638e) | Jul 04, 2023 |
| Dell          | Latitude 7530               | Notebook    | [0d03a052d8](https://linux-hardware.org/?probe=0d03a052d8) | Jul 03, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [947d2ff164](https://linux-hardware.org/?probe=947d2ff164) | Jul 03, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [b5a7ef8997](https://linux-hardware.org/?probe=b5a7ef8997) | Jul 02, 2023 |
| Dell          | G3 3779                     | Notebook    | [bcae1c7195](https://linux-hardware.org/?probe=bcae1c7195) | Jul 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [1c976fee39](https://linux-hardware.org/?probe=1c976fee39) | Jul 01, 2023 |
| Fujitsu       | LIFEBOOK U757               | Notebook    | [f7bac40ab1](https://linux-hardware.org/?probe=f7bac40ab1) | Jul 01, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [9beb3b7196](https://linux-hardware.org/?probe=9beb3b7196) | Jul 01, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [cb6f37ea2b](https://linux-hardware.org/?probe=cb6f37ea2b) | Jul 01, 2023 |
| Dell          | Latitude E5450              | Notebook    | [e0826ab83a](https://linux-hardware.org/?probe=e0826ab83a) | Jun 30, 2023 |
| Schenker      | XMG PRO (E23)               | Notebook    | [c70da63bd9](https://linux-hardware.org/?probe=c70da63bd9) | Jun 30, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [b52c0ac96a](https://linux-hardware.org/?probe=b52c0ac96a) | Jun 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [bbd13c14eb](https://linux-hardware.org/?probe=bbd13c14eb) | Jun 29, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [802b3686d4](https://linux-hardware.org/?probe=802b3686d4) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [abf9b9909f](https://linux-hardware.org/?probe=abf9b9909f) | Jun 27, 2023 |
| MSI           | H81M-P33                    | Desktop     | [1726bb80ec](https://linux-hardware.org/?probe=1726bb80ec) | Jun 27, 2023 |
| Positivo      | POS-PIH81DI                 | Desktop     | [42e304c777](https://linux-hardware.org/?probe=42e304c777) | Jun 26, 2023 |
| Positivo      | POS-PIH81DI                 | Desktop     | [77d2d3d01b](https://linux-hardware.org/?probe=77d2d3d01b) | Jun 26, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [589dd91af9](https://linux-hardware.org/?probe=589dd91af9) | Jun 25, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [aa50925a16](https://linux-hardware.org/?probe=aa50925a16) | Jun 23, 2023 |
| Dell          | G3 3590                     | Notebook    | [14ab83043b](https://linux-hardware.org/?probe=14ab83043b) | Jun 21, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [014c851c43](https://linux-hardware.org/?probe=014c851c43) | Jun 21, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [3dffeb35fa](https://linux-hardware.org/?probe=3dffeb35fa) | Jun 20, 2023 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [233b6c3412](https://linux-hardware.org/?probe=233b6c3412) | Jun 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | Notebook    | [7d00ddf4fc](https://linux-hardware.org/?probe=7d00ddf4fc) | Jun 20, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [5daecd88f5](https://linux-hardware.org/?probe=5daecd88f5) | Jun 19, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [260297ab72](https://linux-hardware.org/?probe=260297ab72) | Jun 19, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [83d17fd3bd](https://linux-hardware.org/?probe=83d17fd3bd) | Jun 17, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [739c466bf0](https://linux-hardware.org/?probe=739c466bf0) | Jun 17, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [587c48c954](https://linux-hardware.org/?probe=587c48c954) | Jun 17, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [75eeeb7917](https://linux-hardware.org/?probe=75eeeb7917) | Jun 16, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [b8d24f1cc8](https://linux-hardware.org/?probe=b8d24f1cc8) | Jun 15, 2023 |
| HP            | Notebook                    | Notebook    | [e0a00a71de](https://linux-hardware.org/?probe=e0a00a71de) | Jun 15, 2023 |
| HP            | Notebook                    | Notebook    | [76433ab03f](https://linux-hardware.org/?probe=76433ab03f) | Jun 15, 2023 |
| HP            | 86F0 11000                  | All in one  | [45026f50ef](https://linux-hardware.org/?probe=45026f50ef) | Jun 15, 2023 |
| HP            | 86F0 11000                  | All in one  | [f074cca59a](https://linux-hardware.org/?probe=f074cca59a) | Jun 15, 2023 |
| Dell          | Latitude 3310               | Notebook    | [40aa328d98](https://linux-hardware.org/?probe=40aa328d98) | Jun 15, 2023 |
| Proline       | V1165C4                     | Notebook    | [89f6135da3](https://linux-hardware.org/?probe=89f6135da3) | Jun 14, 2023 |
| Lenovo        | ThinkPad T440p 20AN009CU... | Notebook    | [54fd87b596](https://linux-hardware.org/?probe=54fd87b596) | Jun 14, 2023 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [a0cdda9a4d](https://linux-hardware.org/?probe=a0cdda9a4d) | Jun 14, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [f616cb77b5](https://linux-hardware.org/?probe=f616cb77b5) | Jun 13, 2023 |
| Gigabyte      | C246-WU4-CF                 | Desktop     | [8babb9b5f1](https://linux-hardware.org/?probe=8babb9b5f1) | Jun 13, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [7f974cd282](https://linux-hardware.org/?probe=7f974cd282) | Jun 12, 2023 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [679fb4f6ab](https://linux-hardware.org/?probe=679fb4f6ab) | Jun 11, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [36f0bbcb6d](https://linux-hardware.org/?probe=36f0bbcb6d) | Jun 11, 2023 |
| Lenovo        | 312A SDK0R32862 WIN 3258... | Desktop     | [1e8ab337a5](https://linux-hardware.org/?probe=1e8ab337a5) | Jun 11, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [b599a55609](https://linux-hardware.org/?probe=b599a55609) | Jun 10, 2023 |
| Lenovo        | ThinkPad T570 20H9000UUS    | Notebook    | [606989ab70](https://linux-hardware.org/?probe=606989ab70) | Jun 10, 2023 |
| Supermicro    | C7H61                       | Desktop     | [7eef5b7873](https://linux-hardware.org/?probe=7eef5b7873) | Jun 08, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [610c9c318f](https://linux-hardware.org/?probe=610c9c318f) | Jun 08, 2023 |
| PC Special... | Initia Ii 15                | Notebook    | [36a16c2890](https://linux-hardware.org/?probe=36a16c2890) | Jun 08, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [62418abec4](https://linux-hardware.org/?probe=62418abec4) | Jun 08, 2023 |
| Acer          | Nitro AN515-56              | Notebook    | [f02195de51](https://linux-hardware.org/?probe=f02195de51) | Jun 07, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [646e1db08d](https://linux-hardware.org/?probe=646e1db08d) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [f4e4a4b982](https://linux-hardware.org/?probe=f4e4a4b982) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [7948f267c2](https://linux-hardware.org/?probe=7948f267c2) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [1139c69312](https://linux-hardware.org/?probe=1139c69312) | Jun 06, 2023 |
| MSI           | 2AE0                        | Desktop     | [15b3c478d3](https://linux-hardware.org/?probe=15b3c478d3) | Jun 06, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [5e9fd3f392](https://linux-hardware.org/?probe=5e9fd3f392) | Jun 05, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [693fdb51d3](https://linux-hardware.org/?probe=693fdb51d3) | Jun 05, 2023 |
| Biostar       | B350GT3                     | Desktop     | [b425f8d45a](https://linux-hardware.org/?probe=b425f8d45a) | Jun 05, 2023 |
| Lenovo        | Yoga Creator 7 15IMH05 8... | Notebook    | [3bcc239452](https://linux-hardware.org/?probe=3bcc239452) | Jun 04, 2023 |
| Dell          | Latitude E6500              | Notebook    | [4053ff5676](https://linux-hardware.org/?probe=4053ff5676) | Jun 03, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [767241151a](https://linux-hardware.org/?probe=767241151a) | Jun 03, 2023 |
| Lenovo        | ThinkPad T460 20FN004BMN    | Notebook    | [dafbbaeb0f](https://linux-hardware.org/?probe=dafbbaeb0f) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [6ae18b11ab](https://linux-hardware.org/?probe=6ae18b11ab) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [963b30ca7f](https://linux-hardware.org/?probe=963b30ca7f) | Jun 02, 2023 |
| Biostar       | A10N-8800E                  | Desktop     | [906dbab25c](https://linux-hardware.org/?probe=906dbab25c) | Jun 01, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [7baed02e0e](https://linux-hardware.org/?probe=7baed02e0e) | Jun 01, 2023 |
| ASRock        | H170M Pro4                  | Desktop     | [d936c663d3](https://linux-hardware.org/?probe=d936c663d3) | Jun 01, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [8720e6163e](https://linux-hardware.org/?probe=8720e6163e) | Jun 01, 2023 |
| MSI           | GF63 Thin 11SC              | Notebook    | [8f8afcc010](https://linux-hardware.org/?probe=8f8afcc010) | Jun 01, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [0586d2c0e2](https://linux-hardware.org/?probe=0586d2c0e2) | Jun 01, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ebd7782079](https://linux-hardware.org/?probe=ebd7782079) | May 31, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [e936e44332](https://linux-hardware.org/?probe=e936e44332) | May 31, 2023 |
| ASUSTek       | Z97-DELUXE                  | Desktop     | [2723d218b7](https://linux-hardware.org/?probe=2723d218b7) | May 31, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [c677ff5b2d](https://linux-hardware.org/?probe=c677ff5b2d) | May 31, 2023 |
| AZW           | GTR V02                     | Desktop     | [bd1740c7b2](https://linux-hardware.org/?probe=bd1740c7b2) | May 31, 2023 |
| AZW           | GTR V02                     | Desktop     | [cab90f1838](https://linux-hardware.org/?probe=cab90f1838) | May 31, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [2667cb67a3](https://linux-hardware.org/?probe=2667cb67a3) | May 30, 2023 |
| Dell          | G15 5525                    | Notebook    | [f7e5d0ae57](https://linux-hardware.org/?probe=f7e5d0ae57) | May 30, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [0568aa067a](https://linux-hardware.org/?probe=0568aa067a) | May 30, 2023 |
| ASRock        | AB350M Pro4                 | Desktop     | [4f23de2827](https://linux-hardware.org/?probe=4f23de2827) | May 30, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [bca463af6d](https://linux-hardware.org/?probe=bca463af6d) | May 28, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [e429db5b0b](https://linux-hardware.org/?probe=e429db5b0b) | May 27, 2023 |
| Dell          | Precision 5530              | Notebook    | [cb116bdfd2](https://linux-hardware.org/?probe=cb116bdfd2) | May 26, 2023 |
| ASUSTek       | P7P55-M                     | Desktop     | [a8fd95ce79](https://linux-hardware.org/?probe=a8fd95ce79) | May 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [1c62418caf](https://linux-hardware.org/?probe=1c62418caf) | May 25, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [3e1fb6f93b](https://linux-hardware.org/?probe=3e1fb6f93b) | May 25, 2023 |
| Acer          | Aspire M3920                | Desktop     | [5e61c22a26](https://linux-hardware.org/?probe=5e61c22a26) | May 24, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [2ef3c0b337](https://linux-hardware.org/?probe=2ef3c0b337) | May 24, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [174a3139c4](https://linux-hardware.org/?probe=174a3139c4) | May 24, 2023 |
| Dell          | Inspiron 14 5401            | Notebook    | [16d8b1c945](https://linux-hardware.org/?probe=16d8b1c945) | May 24, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [9568d26302](https://linux-hardware.org/?probe=9568d26302) | May 24, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [3eb016e8c7](https://linux-hardware.org/?probe=3eb016e8c7) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3d4cdd163c](https://linux-hardware.org/?probe=3d4cdd163c) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c3251b8c63](https://linux-hardware.org/?probe=c3251b8c63) | May 23, 2023 |
| ASUSTek       | Z170-PRO                    | Desktop     | [27819563b9](https://linux-hardware.org/?probe=27819563b9) | May 23, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [7f3dae82d3](https://linux-hardware.org/?probe=7f3dae82d3) | May 23, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [185b65bf34](https://linux-hardware.org/?probe=185b65bf34) | May 22, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [8d8c13c10c](https://linux-hardware.org/?probe=8d8c13c10c) | May 22, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [434372d228](https://linux-hardware.org/?probe=434372d228) | May 21, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [1c178d1658](https://linux-hardware.org/?probe=1c178d1658) | May 21, 2023 |
| Fujitsu       | LIFEBOOK U748               | Notebook    | [a8d8e219a2](https://linux-hardware.org/?probe=a8d8e219a2) | May 21, 2023 |
| MSI           | X370 GAMING PLUS            | Desktop     | [610c8c1a42](https://linux-hardware.org/?probe=610c8c1a42) | May 19, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [1e7af790ed](https://linux-hardware.org/?probe=1e7af790ed) | May 19, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [e0300907f0](https://linux-hardware.org/?probe=e0300907f0) | May 18, 2023 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [7da21ce089](https://linux-hardware.org/?probe=7da21ce089) | May 18, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [28b96d7d6a](https://linux-hardware.org/?probe=28b96d7d6a) | May 17, 2023 |
| Samsung       | 730QFG                      | Convertible | [134377c283](https://linux-hardware.org/?probe=134377c283) | May 17, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [7c05862259](https://linux-hardware.org/?probe=7c05862259) | May 16, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [8cb1f28963](https://linux-hardware.org/?probe=8cb1f28963) | May 16, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [c8250719d9](https://linux-hardware.org/?probe=c8250719d9) | May 16, 2023 |
| ASUSTek       | F1A75-V PRO                 | Desktop     | [9ee8a0ca50](https://linux-hardware.org/?probe=9ee8a0ca50) | May 14, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [e81d6a8a69](https://linux-hardware.org/?probe=e81d6a8a69) | May 14, 2023 |
| Dell          | Latitude E6500              | Notebook    | [b223b17c87](https://linux-hardware.org/?probe=b223b17c87) | May 14, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [0701f94970](https://linux-hardware.org/?probe=0701f94970) | May 13, 2023 |
| Dell          | G3 3590                     | Notebook    | [696d2d38df](https://linux-hardware.org/?probe=696d2d38df) | May 13, 2023 |
| Samsung       | R425/R525                   | Notebook    | [a7719ea5d3](https://linux-hardware.org/?probe=a7719ea5d3) | May 13, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [9ca71ebd01](https://linux-hardware.org/?probe=9ca71ebd01) | May 12, 2023 |
| Dell          | Latitude 7490               | Notebook    | [a187ae7b7e](https://linux-hardware.org/?probe=a187ae7b7e) | May 12, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [9448d89bb6](https://linux-hardware.org/?probe=9448d89bb6) | May 12, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [e360693145](https://linux-hardware.org/?probe=e360693145) | May 11, 2023 |
| Dell          | Latitude 5420               | Notebook    | [a3c2a7c9bf](https://linux-hardware.org/?probe=a3c2a7c9bf) | May 11, 2023 |
| HP            | ProBook x360 440 G1         | Convertible | [63e082c879](https://linux-hardware.org/?probe=63e082c879) | May 10, 2023 |
| HP            | ProBook x360 440 G1         | Convertible | [c85cc0e79c](https://linux-hardware.org/?probe=c85cc0e79c) | May 10, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [d567c1f954](https://linux-hardware.org/?probe=d567c1f954) | May 10, 2023 |
| IBM           | 00AM544                     | Server      | [4c011ef794](https://linux-hardware.org/?probe=4c011ef794) | May 09, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [c941da38cd](https://linux-hardware.org/?probe=c941da38cd) | May 08, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [cbafd29abc](https://linux-hardware.org/?probe=cbafd29abc) | May 08, 2023 |
| Dell          | Latitude 3570               | Notebook    | [8209fc06f4](https://linux-hardware.org/?probe=8209fc06f4) | May 08, 2023 |
| TerraQue      | W65_W67RB                   | Notebook    | [842f203ec5](https://linux-hardware.org/?probe=842f203ec5) | May 07, 2023 |
| Acer          | Aspire M3920                | Desktop     | [aed14c1e20](https://linux-hardware.org/?probe=aed14c1e20) | May 07, 2023 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [a062cb2ab6](https://linux-hardware.org/?probe=a062cb2ab6) | May 07, 2023 |
| Lenovo        | ThinkPad T460s 20F9CTO1W... | Notebook    | [4229be0afa](https://linux-hardware.org/?probe=4229be0afa) | May 07, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [7bbdc5e568](https://linux-hardware.org/?probe=7bbdc5e568) | May 07, 2023 |
| Samsung       | Galaxy TabPro S             | Tablet      | [167229560a](https://linux-hardware.org/?probe=167229560a) | May 05, 2023 |
| Razer         | Blade Pro 17 (2019)         | Notebook    | [4b2265c354](https://linux-hardware.org/?probe=4b2265c354) | May 05, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [00a1158a86](https://linux-hardware.org/?probe=00a1158a86) | May 04, 2023 |
| ASUSTek       | X750JB                      | Notebook    | [02a5481254](https://linux-hardware.org/?probe=02a5481254) | May 03, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [ae1618c708](https://linux-hardware.org/?probe=ae1618c708) | May 03, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [63015eecb0](https://linux-hardware.org/?probe=63015eecb0) | May 03, 2023 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [36574d4502](https://linux-hardware.org/?probe=36574d4502) | May 03, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [2da8ff7129](https://linux-hardware.org/?probe=2da8ff7129) | May 03, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [263099c212](https://linux-hardware.org/?probe=263099c212) | May 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [ee8e81add2](https://linux-hardware.org/?probe=ee8e81add2) | May 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [e8ce8c11c0](https://linux-hardware.org/?probe=e8ce8c11c0) | May 01, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [45a7e28db1](https://linux-hardware.org/?probe=45a7e28db1) | Apr 30, 2023 |
| Intel         | H81                         | Desktop     | [c70b10516b](https://linux-hardware.org/?probe=c70b10516b) | Apr 30, 2023 |
| Acer          | Aspire M5-481T              | Notebook    | [d215d36b64](https://linux-hardware.org/?probe=d215d36b64) | Apr 30, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [a31fa8f985](https://linux-hardware.org/?probe=a31fa8f985) | Apr 28, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [dd76e10243](https://linux-hardware.org/?probe=dd76e10243) | Apr 28, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [7feb43607e](https://linux-hardware.org/?probe=7feb43607e) | Apr 27, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [44c5943019](https://linux-hardware.org/?probe=44c5943019) | Apr 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [812906148b](https://linux-hardware.org/?probe=812906148b) | Apr 27, 2023 |
| Dell          | Inspiron 3793               | Notebook    | [f9d337a0a1](https://linux-hardware.org/?probe=f9d337a0a1) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430s 23539MU      | Notebook    | [83a1144be6](https://linux-hardware.org/?probe=83a1144be6) | Apr 26, 2023 |
| Alienware     | Aurora R15 AMD              | Desktop     | [f2e22848d1](https://linux-hardware.org/?probe=f2e22848d1) | Apr 25, 2023 |
| MSI           | FM2-A75MA-E35               | Desktop     | [011f691ce1](https://linux-hardware.org/?probe=011f691ce1) | Apr 25, 2023 |
| Acer          | Spin SP313-51N              | Convertible | [76646ac40d](https://linux-hardware.org/?probe=76646ac40d) | Apr 24, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [6d49fc2276](https://linux-hardware.org/?probe=6d49fc2276) | Apr 24, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [3d8d7c49f8](https://linux-hardware.org/?probe=3d8d7c49f8) | Apr 24, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [e9a3b8f1d1](https://linux-hardware.org/?probe=e9a3b8f1d1) | Apr 24, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [2a8a92135b](https://linux-hardware.org/?probe=2a8a92135b) | Apr 24, 2023 |
| Carbon Sys... | Iridium 14                  | Notebook    | [10cd21aba6](https://linux-hardware.org/?probe=10cd21aba6) | Apr 23, 2023 |
| Dell          | 00V16R A00                  | All in one  | [cb94924faa](https://linux-hardware.org/?probe=cb94924faa) | Apr 23, 2023 |
| Dell          | Precision 7550              | Notebook    | [31830a82c6](https://linux-hardware.org/?probe=31830a82c6) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c4a5aad8a1](https://linux-hardware.org/?probe=c4a5aad8a1) | Apr 22, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [0dcc2eaa50](https://linux-hardware.org/?probe=0dcc2eaa50) | Apr 22, 2023 |
| HP            | 82F2 A01                    | Desktop     | [fbcf679bae](https://linux-hardware.org/?probe=fbcf679bae) | Apr 21, 2023 |
| Supermicro    | C7H61                       | Desktop     | [f5e17f37d4](https://linux-hardware.org/?probe=f5e17f37d4) | Apr 21, 2023 |
| Carbon Sys... | Iridium 14                  | Notebook    | [af5e3d750a](https://linux-hardware.org/?probe=af5e3d750a) | Apr 20, 2023 |
| ASUSTek       | Z170-PRO                    | Desktop     | [970c4dfa6f](https://linux-hardware.org/?probe=970c4dfa6f) | Apr 20, 2023 |
| Supermicro    | C7H61                       | Desktop     | [d975325f4b](https://linux-hardware.org/?probe=d975325f4b) | Apr 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [cd58803d5c](https://linux-hardware.org/?probe=cd58803d5c) | Apr 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [7adb4b2000](https://linux-hardware.org/?probe=7adb4b2000) | Apr 19, 2023 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [cccb2ff44c](https://linux-hardware.org/?probe=cccb2ff44c) | Apr 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [cc18450a32](https://linux-hardware.org/?probe=cc18450a32) | Apr 17, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [7ed9078ed9](https://linux-hardware.org/?probe=7ed9078ed9) | Apr 17, 2023 |
| MSI           | Modern 14 B11MOU            | Notebook    | [d76555e7e6](https://linux-hardware.org/?probe=d76555e7e6) | Apr 16, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [7aef52516b](https://linux-hardware.org/?probe=7aef52516b) | Apr 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [073b59d558](https://linux-hardware.org/?probe=073b59d558) | Apr 16, 2023 |
| AXIOO         | SlimBook 11                 | Notebook    | [b0c639ab77](https://linux-hardware.org/?probe=b0c639ab77) | Apr 15, 2023 |
| HP            | ProBook 650 G3              | Notebook    | [00526690c9](https://linux-hardware.org/?probe=00526690c9) | Apr 15, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [d21971f30f](https://linux-hardware.org/?probe=d21971f30f) | Apr 13, 2023 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [624fa75f43](https://linux-hardware.org/?probe=624fa75f43) | Apr 12, 2023 |
| ASUSTek       | Z97-A                       | Desktop     | [139f5f3aca](https://linux-hardware.org/?probe=139f5f3aca) | Apr 12, 2023 |
| Dell          | Latitude E5450              | Notebook    | [f98cdf4da0](https://linux-hardware.org/?probe=f98cdf4da0) | Apr 11, 2023 |
| Dell          | Latitude E5450              | Notebook    | [7bf04cdb7d](https://linux-hardware.org/?probe=7bf04cdb7d) | Apr 11, 2023 |
| HP            | 829C                        | All in one  | [91f5a10ba1](https://linux-hardware.org/?probe=91f5a10ba1) | Apr 11, 2023 |
| Dell          | 0RW199                      | Desktop     | [8c41f4ff91](https://linux-hardware.org/?probe=8c41f4ff91) | Apr 11, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [5875837a8d](https://linux-hardware.org/?probe=5875837a8d) | Apr 10, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [6b6b2a8633](https://linux-hardware.org/?probe=6b6b2a8633) | Apr 09, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [00489240d2](https://linux-hardware.org/?probe=00489240d2) | Apr 09, 2023 |
| Dell          | 0F373D A00                  | Desktop     | [e42bdc9769](https://linux-hardware.org/?probe=e42bdc9769) | Apr 09, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | Desktop     | [8187fc54a3](https://linux-hardware.org/?probe=8187fc54a3) | Apr 07, 2023 |
| Unknown       | Unknown                     | Notebook    | [0bf91f3219](https://linux-hardware.org/?probe=0bf91f3219) | Apr 06, 2023 |
| Lenovo        | ThinkPad T420 4177RVU       | Notebook    | [994fccf5d0](https://linux-hardware.org/?probe=994fccf5d0) | Apr 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [ec673ad1c1](https://linux-hardware.org/?probe=ec673ad1c1) | Apr 06, 2023 |
| Gigabyte      | M61SME-S2                   | Desktop     | [25d436d2cb](https://linux-hardware.org/?probe=25d436d2cb) | Apr 06, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [edd397551c](https://linux-hardware.org/?probe=edd397551c) | Apr 05, 2023 |
| HP            | 0A9Ch                       | Desktop     | [178046626f](https://linux-hardware.org/?probe=178046626f) | Apr 05, 2023 |
| Gigabyte      | 970-GAMING                  | Desktop     | [6ec3c125d5](https://linux-hardware.org/?probe=6ec3c125d5) | Apr 05, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [32f708c916](https://linux-hardware.org/?probe=32f708c916) | Apr 05, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [0779903086](https://linux-hardware.org/?probe=0779903086) | Apr 05, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [7cce222ce2](https://linux-hardware.org/?probe=7cce222ce2) | Apr 04, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [7eeea6ba29](https://linux-hardware.org/?probe=7eeea6ba29) | Apr 04, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [6e750dfaa5](https://linux-hardware.org/?probe=6e750dfaa5) | Apr 04, 2023 |
| Notebook      | PD5x_7xSNC_SND_SNE          | Notebook    | [1c9d684eba](https://linux-hardware.org/?probe=1c9d684eba) | Apr 04, 2023 |
| Alienware     | 0VDT73 A00                  | Desktop     | [ed92305da6](https://linux-hardware.org/?probe=ed92305da6) | Apr 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CFS... | Notebook    | [0cff652e48](https://linux-hardware.org/?probe=0cff652e48) | Apr 03, 2023 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [72dc18dacb](https://linux-hardware.org/?probe=72dc18dacb) | Apr 03, 2023 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [8ba82ca424](https://linux-hardware.org/?probe=8ba82ca424) | Apr 03, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [f8e61fd850](https://linux-hardware.org/?probe=f8e61fd850) | Apr 03, 2023 |
| ASUSTek       | ASUS ExpertBook P2451FA_... | Notebook    | [05261a9b98](https://linux-hardware.org/?probe=05261a9b98) | Apr 03, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [35c3ae13c5](https://linux-hardware.org/?probe=35c3ae13c5) | Apr 02, 2023 |
| Thomson       | SPNEOX13-4RD64              | Notebook    | [bf3eb39804](https://linux-hardware.org/?probe=bf3eb39804) | Apr 02, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [e800b0ff2e](https://linux-hardware.org/?probe=e800b0ff2e) | Apr 02, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [a0dddcbb95](https://linux-hardware.org/?probe=a0dddcbb95) | Apr 02, 2023 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [12647b9601](https://linux-hardware.org/?probe=12647b9601) | Apr 02, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [46e8dbcdc8](https://linux-hardware.org/?probe=46e8dbcdc8) | Apr 02, 2023 |
| Notebook      | PD5x_7xSNC_SND_SNE          | Notebook    | [4809c76aba](https://linux-hardware.org/?probe=4809c76aba) | Apr 02, 2023 |
| Lenovo        | ThinkPad X280 20KF001UUS    | Notebook    | [49e740bc77](https://linux-hardware.org/?probe=49e740bc77) | Apr 02, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [0fbed59931](https://linux-hardware.org/?probe=0fbed59931) | Apr 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [bc77efa103](https://linux-hardware.org/?probe=bc77efa103) | Apr 01, 2023 |
| MSI           | MAG A520M VECTOR WIFI       | Desktop     | [3c08cf9aba](https://linux-hardware.org/?probe=3c08cf9aba) | Apr 01, 2023 |
| ASUSTek       | EB1036                      | Desktop     | [955d389e06](https://linux-hardware.org/?probe=955d389e06) | Mar 30, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [278ed0e013](https://linux-hardware.org/?probe=278ed0e013) | Mar 30, 2023 |
| Dell          | 0200DY A01                  | Desktop     | [722b28547b](https://linux-hardware.org/?probe=722b28547b) | Mar 28, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [548224967e](https://linux-hardware.org/?probe=548224967e) | Mar 28, 2023 |
| MSI           | B85-G43                     | Desktop     | [3dac8c76c2](https://linux-hardware.org/?probe=3dac8c76c2) | Mar 28, 2023 |
| Lenovo        | SHARKBAY SDK0J40709 WIN ... | Desktop     | [22e3e1831c](https://linux-hardware.org/?probe=22e3e1831c) | Mar 28, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [84092aca44](https://linux-hardware.org/?probe=84092aca44) | Mar 27, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [6553d2c85a](https://linux-hardware.org/?probe=6553d2c85a) | Mar 26, 2023 |
| Lenovo        | ThinkPad SL 2743NSC         | Notebook    | [48d6301eaa](https://linux-hardware.org/?probe=48d6301eaa) | Mar 26, 2023 |
| HUAWEI        | KLVDZ-WXX9                  | Notebook    | [369363c3a9](https://linux-hardware.org/?probe=369363c3a9) | Mar 26, 2023 |
| Intel         | NUC5i3RYB H41000-502        | Mini pc     | [fac3426827](https://linux-hardware.org/?probe=fac3426827) | Mar 26, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [2246abad85](https://linux-hardware.org/?probe=2246abad85) | Mar 25, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [4262f0e159](https://linux-hardware.org/?probe=4262f0e159) | Mar 25, 2023 |
| Carbon Sys... | Iridium 14                  | Notebook    | [e7f9195a1d](https://linux-hardware.org/?probe=e7f9195a1d) | Mar 25, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [9a8b9b917f](https://linux-hardware.org/?probe=9a8b9b917f) | Mar 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c114580013](https://linux-hardware.org/?probe=c114580013) | Mar 24, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [c7ec617422](https://linux-hardware.org/?probe=c7ec617422) | Mar 24, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [c50deee021](https://linux-hardware.org/?probe=c50deee021) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M560... | Notebook    | [16b93bfe5d](https://linux-hardware.org/?probe=16b93bfe5d) | Mar 24, 2023 |
| Dell          | Latitude 5420               | Notebook    | [42d5b573c4](https://linux-hardware.org/?probe=42d5b573c4) | Mar 24, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [9b048b064d](https://linux-hardware.org/?probe=9b048b064d) | Mar 24, 2023 |
| Notebook      | NV4xPZ                      | Notebook    | [74d70a3568](https://linux-hardware.org/?probe=74d70a3568) | Mar 23, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [84f93bfcf1](https://linux-hardware.org/?probe=84f93bfcf1) | Mar 23, 2023 |
| HP            | ZBook 15 G6                 | Notebook    | [61dcde6523](https://linux-hardware.org/?probe=61dcde6523) | Mar 22, 2023 |
| MSI           | GE70 2PE                    | Notebook    | [5e68fcc30d](https://linux-hardware.org/?probe=5e68fcc30d) | Mar 22, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [ae63ffa582](https://linux-hardware.org/?probe=ae63ffa582) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [d9c0447b0d](https://linux-hardware.org/?probe=d9c0447b0d) | Mar 21, 2023 |
| HP            | ProBook 640 G4              | Notebook    | [2787c4bf42](https://linux-hardware.org/?probe=2787c4bf42) | Mar 20, 2023 |
| HP            | 21F5                        | Desktop     | [865a85e5bc](https://linux-hardware.org/?probe=865a85e5bc) | Mar 20, 2023 |
| Intel         | DH67BL AAG10189-208         | Desktop     | [420f476f82](https://linux-hardware.org/?probe=420f476f82) | Mar 19, 2023 |
| ASUSTek       | T300CHI                     | Notebook    | [371961ad53](https://linux-hardware.org/?probe=371961ad53) | Mar 19, 2023 |
| Acer          | Nitro AN517-41              | Notebook    | [5e5fd3788e](https://linux-hardware.org/?probe=5e5fd3788e) | Mar 19, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [efaf7d4a30](https://linux-hardware.org/?probe=efaf7d4a30) | Mar 18, 2023 |
| Carbon Sys... | Iridium 14                  | Notebook    | [c70e1d7e98](https://linux-hardware.org/?probe=c70e1d7e98) | Mar 18, 2023 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [ef3e267972](https://linux-hardware.org/?probe=ef3e267972) | Mar 18, 2023 |
| Clevo         | W340EU                      | Notebook    | [b90ad98b0a](https://linux-hardware.org/?probe=b90ad98b0a) | Mar 18, 2023 |
| HP            | 8266                        | Desktop     | [8bac7f79e8](https://linux-hardware.org/?probe=8bac7f79e8) | Mar 17, 2023 |
| Clevo         | W340EU                      | Notebook    | [240779648a](https://linux-hardware.org/?probe=240779648a) | Mar 17, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [9ca1015389](https://linux-hardware.org/?probe=9ca1015389) | Mar 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [1ed7ccd033](https://linux-hardware.org/?probe=1ed7ccd033) | Mar 16, 2023 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [d1edfbc4b3](https://linux-hardware.org/?probe=d1edfbc4b3) | Mar 16, 2023 |
| Acer          | Aspire M3920                | Desktop     | [bb2e9ec8a1](https://linux-hardware.org/?probe=bb2e9ec8a1) | Mar 16, 2023 |
| Dell          | Inspiron 13 5310            | Notebook    | [697914b165](https://linux-hardware.org/?probe=697914b165) | Mar 16, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | Notebook    | [69f39892c4](https://linux-hardware.org/?probe=69f39892c4) | Mar 15, 2023 |
| Dell          | Inspiron 5575               | Notebook    | [0ace5375f4](https://linux-hardware.org/?probe=0ace5375f4) | Mar 15, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | Notebook    | [8fff8ca97d](https://linux-hardware.org/?probe=8fff8ca97d) | Mar 15, 2023 |
| Supermicro    | X9DRD-C/iT+                 | Desktop     | [57c78aa4db](https://linux-hardware.org/?probe=57c78aa4db) | Mar 15, 2023 |
| HP            | ZBook 15                    | Notebook    | [ebc4b1e01e](https://linux-hardware.org/?probe=ebc4b1e01e) | Mar 14, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [f424a1dc42](https://linux-hardware.org/?probe=f424a1dc42) | Mar 14, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [b5ef4ae548](https://linux-hardware.org/?probe=b5ef4ae548) | Mar 14, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [783ff991d4](https://linux-hardware.org/?probe=783ff991d4) | Mar 14, 2023 |
| MSI           | B85-G43                     | Desktop     | [7e9ce07cb8](https://linux-hardware.org/?probe=7e9ce07cb8) | Mar 13, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [e79cdeaf10](https://linux-hardware.org/?probe=e79cdeaf10) | Mar 13, 2023 |
| MSI           | B85-G43                     | Desktop     | [9a9a70ade3](https://linux-hardware.org/?probe=9a9a70ade3) | Mar 13, 2023 |
| Acer          | Aspire A715-74G             | Notebook    | [57000f8a86](https://linux-hardware.org/?probe=57000f8a86) | Mar 13, 2023 |
| Dell          | Latitude E6420              | Notebook    | [6fe2914b41](https://linux-hardware.org/?probe=6fe2914b41) | Mar 12, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [60bc8c1ef5](https://linux-hardware.org/?probe=60bc8c1ef5) | Mar 12, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [4ee87a1213](https://linux-hardware.org/?probe=4ee87a1213) | Mar 12, 2023 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [77b7a9348b](https://linux-hardware.org/?probe=77b7a9348b) | Mar 12, 2023 |
| MSI           | MAG B660M BAZOOKA DDR4      | Desktop     | [cb1be19cd3](https://linux-hardware.org/?probe=cb1be19cd3) | Mar 11, 2023 |
| MSI           | B85-G43                     | Desktop     | [47ac638c2e](https://linux-hardware.org/?probe=47ac638c2e) | Mar 11, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [d039d459d7](https://linux-hardware.org/?probe=d039d459d7) | Mar 10, 2023 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [9f02108ada](https://linux-hardware.org/?probe=9f02108ada) | Mar 09, 2023 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [5a0eb5bfed](https://linux-hardware.org/?probe=5a0eb5bfed) | Mar 09, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [f658e58c98](https://linux-hardware.org/?probe=f658e58c98) | Mar 09, 2023 |
| Dell          | Inspiron 15-3565            | Notebook    | [a71845e346](https://linux-hardware.org/?probe=a71845e346) | Mar 09, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [fdc9f52c81](https://linux-hardware.org/?probe=fdc9f52c81) | Mar 08, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [7bd6e95116](https://linux-hardware.org/?probe=7bd6e95116) | Mar 08, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [d3cd7ae3e8](https://linux-hardware.org/?probe=d3cd7ae3e8) | Mar 07, 2023 |
| Lenovo        | IdeaPad C340-14IWL 81RL     | Convertible | [9625716631](https://linux-hardware.org/?probe=9625716631) | Mar 07, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [b48c76be97](https://linux-hardware.org/?probe=b48c76be97) | Mar 07, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [22569ee1f4](https://linux-hardware.org/?probe=22569ee1f4) | Mar 07, 2023 |
| HP            | ENVY TS 17                  | Notebook    | [c915d51f5e](https://linux-hardware.org/?probe=c915d51f5e) | Mar 07, 2023 |
| ASUSTek       | K52JT                       | Notebook    | [802fe86b5c](https://linux-hardware.org/?probe=802fe86b5c) | Mar 06, 2023 |
| Alienware     | x14                         | Notebook    | [a1665c85ab](https://linux-hardware.org/?probe=a1665c85ab) | Mar 06, 2023 |
| Alienware     | x14                         | Notebook    | [8f12fe3ee5](https://linux-hardware.org/?probe=8f12fe3ee5) | Mar 06, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [6db57d4d9f](https://linux-hardware.org/?probe=6db57d4d9f) | Mar 05, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [28dbdcfbb7](https://linux-hardware.org/?probe=28dbdcfbb7) | Mar 05, 2023 |
| Dell          | Latitude E6420              | Notebook    | [569d016799](https://linux-hardware.org/?probe=569d016799) | Mar 05, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [8805f0bce5](https://linux-hardware.org/?probe=8805f0bce5) | Mar 05, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [7d43df02db](https://linux-hardware.org/?probe=7d43df02db) | Mar 04, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [63e9a399f8](https://linux-hardware.org/?probe=63e9a399f8) | Mar 04, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [c654c1809d](https://linux-hardware.org/?probe=c654c1809d) | Mar 04, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [9a3c215b30](https://linux-hardware.org/?probe=9a3c215b30) | Mar 03, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [fdee05953f](https://linux-hardware.org/?probe=fdee05953f) | Mar 03, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [a5939aa47c](https://linux-hardware.org/?probe=a5939aa47c) | Mar 03, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [cc8c299b5d](https://linux-hardware.org/?probe=cc8c299b5d) | Mar 01, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [ecfa5f6c27](https://linux-hardware.org/?probe=ecfa5f6c27) | Mar 01, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [8fd450db03](https://linux-hardware.org/?probe=8fd450db03) | Feb 28, 2023 |
| Dell          | Latitude 5530               | Notebook    | [f892221e4c](https://linux-hardware.org/?probe=f892221e4c) | Feb 27, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | Notebook    | [aa26becbb1](https://linux-hardware.org/?probe=aa26becbb1) | Feb 27, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [a2af33e0e3](https://linux-hardware.org/?probe=a2af33e0e3) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [a5f5bdc903](https://linux-hardware.org/?probe=a5f5bdc903) | Feb 26, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [575e6a8c55](https://linux-hardware.org/?probe=575e6a8c55) | Feb 26, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [8bfe7e434d](https://linux-hardware.org/?probe=8bfe7e434d) | Feb 26, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [c6ca9e8499](https://linux-hardware.org/?probe=c6ca9e8499) | Feb 26, 2023 |
| HP            | G62                         | Notebook    | [871207750c](https://linux-hardware.org/?probe=871207750c) | Feb 25, 2023 |
| ASRock        | H97 Pro4                    | Desktop     | [f703af2e6b](https://linux-hardware.org/?probe=f703af2e6b) | Feb 25, 2023 |
| Alienware     | m15 R7 AMD                  | Notebook    | [0a44dcc29e](https://linux-hardware.org/?probe=0a44dcc29e) | Feb 24, 2023 |
| Dell          | Latitude 5530               | Notebook    | [8ad26dd8a0](https://linux-hardware.org/?probe=8ad26dd8a0) | Feb 24, 2023 |
| Alienware     | m15 R7 AMD                  | Notebook    | [3ba05d49d8](https://linux-hardware.org/?probe=3ba05d49d8) | Feb 24, 2023 |
| ASRock        | M3A770DE                    | Desktop     | [b025c7a092](https://linux-hardware.org/?probe=b025c7a092) | Feb 24, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [463265c999](https://linux-hardware.org/?probe=463265c999) | Feb 24, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [4aec81f692](https://linux-hardware.org/?probe=4aec81f692) | Feb 24, 2023 |
| Dell          | System Inspiron N7110       | Notebook    | [4a3b8e0755](https://linux-hardware.org/?probe=4a3b8e0755) | Feb 22, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [acb8644ede](https://linux-hardware.org/?probe=acb8644ede) | Feb 21, 2023 |
| MSI           | B85-G43                     | Desktop     | [62273631b2](https://linux-hardware.org/?probe=62273631b2) | Feb 21, 2023 |
| Lenovo        | ThinkPad T440p 20AWS3E20... | Notebook    | [012b54b31c](https://linux-hardware.org/?probe=012b54b31c) | Feb 21, 2023 |
| ASRock        | 960GC-GS FX                 | Desktop     | [39718b8983](https://linux-hardware.org/?probe=39718b8983) | Feb 20, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [6033e6cb63](https://linux-hardware.org/?probe=6033e6cb63) | Feb 20, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [63de5bef96](https://linux-hardware.org/?probe=63de5bef96) | Feb 20, 2023 |
| Gigabyte      | X99-Ultra Gaming-CF         | Desktop     | [031c13ea35](https://linux-hardware.org/?probe=031c13ea35) | Feb 19, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [6824ee9944](https://linux-hardware.org/?probe=6824ee9944) | Feb 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [82db23bd7f](https://linux-hardware.org/?probe=82db23bd7f) | Feb 19, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [93f3ae1f77](https://linux-hardware.org/?probe=93f3ae1f77) | Feb 19, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [25c9923614](https://linux-hardware.org/?probe=25c9923614) | Feb 18, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [b3c5c043ea](https://linux-hardware.org/?probe=b3c5c043ea) | Feb 18, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [1c1470c8a2](https://linux-hardware.org/?probe=1c1470c8a2) | Feb 18, 2023 |
| Dell          | Inspiron 14 7420 2-in-1     | Convertible | [7daf230ef2](https://linux-hardware.org/?probe=7daf230ef2) | Feb 18, 2023 |
| Dell          | System Inspiron N7110       | Notebook    | [542553dd55](https://linux-hardware.org/?probe=542553dd55) | Feb 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [4baabf8013](https://linux-hardware.org/?probe=4baabf8013) | Feb 18, 2023 |
| Dell          | Precision 7540              | Notebook    | [2a511e3e78](https://linux-hardware.org/?probe=2a511e3e78) | Feb 17, 2023 |
| MSI           | MAG B560 TOMAHAWK WIFI      | Desktop     | [6538791548](https://linux-hardware.org/?probe=6538791548) | Feb 17, 2023 |
| MSI           | MAG B560 TOMAHAWK WIFI      | Desktop     | [2da59271fe](https://linux-hardware.org/?probe=2da59271fe) | Feb 17, 2023 |
| Dell          | 0DF42J A00                  | Desktop     | [e192547cd3](https://linux-hardware.org/?probe=e192547cd3) | Feb 17, 2023 |
| Alienware     | 17 R2                       | Notebook    | [a70da6118b](https://linux-hardware.org/?probe=a70da6118b) | Feb 16, 2023 |
| Dell          | System Inspiron N7110       | Notebook    | [a59b4a2c12](https://linux-hardware.org/?probe=a59b4a2c12) | Feb 16, 2023 |
| ASUSTek       | X75VD                       | Notebook    | [81c64d5916](https://linux-hardware.org/?probe=81c64d5916) | Feb 16, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [6f0ca25023](https://linux-hardware.org/?probe=6f0ca25023) | Feb 16, 2023 |
| Lenovo        | ThinkPad L13 20R30006PB     | Notebook    | [aad1f06bb9](https://linux-hardware.org/?probe=aad1f06bb9) | Feb 16, 2023 |
| Dell          | G15 5515                    | Notebook    | [17ff15f50e](https://linux-hardware.org/?probe=17ff15f50e) | Feb 16, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [832920f31b](https://linux-hardware.org/?probe=832920f31b) | Feb 14, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [e6f972234b](https://linux-hardware.org/?probe=e6f972234b) | Feb 14, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [695abe8c65](https://linux-hardware.org/?probe=695abe8c65) | Feb 14, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [08a9c049a1](https://linux-hardware.org/?probe=08a9c049a1) | Feb 13, 2023 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [d517411fc5](https://linux-hardware.org/?probe=d517411fc5) | Feb 13, 2023 |
| HP            | ProBook 6470b               | Notebook    | [e747086309](https://linux-hardware.org/?probe=e747086309) | Feb 13, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [23eec2d2bc](https://linux-hardware.org/?probe=23eec2d2bc) | Feb 13, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [067646f7f8](https://linux-hardware.org/?probe=067646f7f8) | Feb 12, 2023 |
| MSI           | GE62VR 6RF                  | Notebook    | [89c148a5f9](https://linux-hardware.org/?probe=89c148a5f9) | Feb 12, 2023 |
| Lenovo        | ThinkPad T450 20BV0001US    | Notebook    | [d149fd1ed6](https://linux-hardware.org/?probe=d149fd1ed6) | Feb 12, 2023 |
| HP            | 3397                        | Desktop     | [cc5cdaf09b](https://linux-hardware.org/?probe=cc5cdaf09b) | Feb 12, 2023 |
| Google        | Blooguard                   | Notebook    | [b4cdae3965](https://linux-hardware.org/?probe=b4cdae3965) | Feb 11, 2023 |
| Gigabyte      | GB-BKi5(H)A-7200            | Notebook    | [57ff1b0fe3](https://linux-hardware.org/?probe=57ff1b0fe3) | Feb 11, 2023 |
| Lenovo        | ZHAOYANG K4e-ITL 82Q1       | Notebook    | [4ab5181634](https://linux-hardware.org/?probe=4ab5181634) | Feb 11, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [3af9191e4f](https://linux-hardware.org/?probe=3af9191e4f) | Feb 11, 2023 |
| ASUSTek       | ET2400IN-1G                 | All in one  | [c65e5f04d0](https://linux-hardware.org/?probe=c65e5f04d0) | Feb 11, 2023 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [b2c120d8d7](https://linux-hardware.org/?probe=b2c120d8d7) | Feb 11, 2023 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [a19717f948](https://linux-hardware.org/?probe=a19717f948) | Feb 10, 2023 |
| HP            | 86F0 11000                  | All in one  | [2fab63e976](https://linux-hardware.org/?probe=2fab63e976) | Feb 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [e3ea6ad8da](https://linux-hardware.org/?probe=e3ea6ad8da) | Feb 10, 2023 |
| MSI           | GS73 Stealth 8RF            | Notebook    | [ccbec1376d](https://linux-hardware.org/?probe=ccbec1376d) | Feb 09, 2023 |
| MSI           | GS73 Stealth 8RF            | Notebook    | [0d5a38a089](https://linux-hardware.org/?probe=0d5a38a089) | Feb 09, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [b4fa86401f](https://linux-hardware.org/?probe=b4fa86401f) | Feb 09, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [ee5a11ee81](https://linux-hardware.org/?probe=ee5a11ee81) | Feb 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [5df3b5ad7e](https://linux-hardware.org/?probe=5df3b5ad7e) | Feb 08, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [556b064487](https://linux-hardware.org/?probe=556b064487) | Feb 07, 2023 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [be25e0c930](https://linux-hardware.org/?probe=be25e0c930) | Feb 07, 2023 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [d139473252](https://linux-hardware.org/?probe=d139473252) | Feb 07, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [7dcb345b45](https://linux-hardware.org/?probe=7dcb345b45) | Feb 06, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [8c3dd4055e](https://linux-hardware.org/?probe=8c3dd4055e) | Feb 06, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [c454139724](https://linux-hardware.org/?probe=c454139724) | Feb 06, 2023 |
| Lenovo        | ThinkPad T470 20HES3X300    | Notebook    | [6a77ec4c4f](https://linux-hardware.org/?probe=6a77ec4c4f) | Feb 06, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [5f59acbf0d](https://linux-hardware.org/?probe=5f59acbf0d) | Feb 05, 2023 |
| ONN           | 100002435                   | Tablet      | [35d8a4ce58](https://linux-hardware.org/?probe=35d8a4ce58) | Feb 05, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [c614e44344](https://linux-hardware.org/?probe=c614e44344) | Feb 05, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [ad59fdb4e4](https://linux-hardware.org/?probe=ad59fdb4e4) | Feb 05, 2023 |
| HP            | G60                         | Notebook    | [518195af9f](https://linux-hardware.org/?probe=518195af9f) | Feb 04, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [27d852788e](https://linux-hardware.org/?probe=27d852788e) | Feb 03, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [2ed6b9969d](https://linux-hardware.org/?probe=2ed6b9969d) | Feb 03, 2023 |
| ASUSTek       | X550JK                      | Notebook    | [c42e4eb249](https://linux-hardware.org/?probe=c42e4eb249) | Feb 03, 2023 |
| Lenovo        | ThinkPad T460 20FMS66R00    | Notebook    | [293690383a](https://linux-hardware.org/?probe=293690383a) | Feb 02, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [caf63a9d0f](https://linux-hardware.org/?probe=caf63a9d0f) | Feb 02, 2023 |
| Lenovo        | ThinkPad W530 2463A49       | Notebook    | [374c21a672](https://linux-hardware.org/?probe=374c21a672) | Feb 02, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [d186290a3f](https://linux-hardware.org/?probe=d186290a3f) | Feb 01, 2023 |
| Dell          | Precision 7540              | Notebook    | [1d0d197808](https://linux-hardware.org/?probe=1d0d197808) | Feb 01, 2023 |
| Google        | Lillipup                    | Notebook    | [45f9b8c3cf](https://linux-hardware.org/?probe=45f9b8c3cf) | Jan 31, 2023 |
| Acer          | Aspire AV14-51              | Notebook    | [fa801eea4b](https://linux-hardware.org/?probe=fa801eea4b) | Jan 31, 2023 |
| HP            | 829A                        | Mini pc     | [a6925c200b](https://linux-hardware.org/?probe=a6925c200b) | Jan 31, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [96671141f9](https://linux-hardware.org/?probe=96671141f9) | Jan 30, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [b3c357b53b](https://linux-hardware.org/?probe=b3c357b53b) | Jan 30, 2023 |
| Lenovo        | ThinkPad T580 20LA0025MX    | Notebook    | [c5e4274143](https://linux-hardware.org/?probe=c5e4274143) | Jan 29, 2023 |
| Lenovo        | IdeaPad 720S-14IKB 81BD     | Notebook    | [50eb066d41](https://linux-hardware.org/?probe=50eb066d41) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [175211d52c](https://linux-hardware.org/?probe=175211d52c) | Jan 29, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [0abc762f30](https://linux-hardware.org/?probe=0abc762f30) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [a011ba3b9e](https://linux-hardware.org/?probe=a011ba3b9e) | Jan 28, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [1a9e67408e](https://linux-hardware.org/?probe=1a9e67408e) | Jan 28, 2023 |
| Dell          | Precision 7730              | Notebook    | [058f16ac84](https://linux-hardware.org/?probe=058f16ac84) | Jan 28, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [fa464af5fb](https://linux-hardware.org/?probe=fa464af5fb) | Jan 27, 2023 |
| HP            | 3397                        | Desktop     | [764f737fcf](https://linux-hardware.org/?probe=764f737fcf) | Jan 27, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [32a666b611](https://linux-hardware.org/?probe=32a666b611) | Jan 27, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [7273b8320c](https://linux-hardware.org/?probe=7273b8320c) | Jan 26, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [2de4e60fef](https://linux-hardware.org/?probe=2de4e60fef) | Jan 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [7403ca2f73](https://linux-hardware.org/?probe=7403ca2f73) | Jan 25, 2023 |
| Lenovo        | ThinkPad L380 20M6S2YE00    | Notebook    | [e6c626133e](https://linux-hardware.org/?probe=e6c626133e) | Jan 25, 2023 |
| TrekStor      | Surfbook A13B               | Notebook    | [4306d9ba1c](https://linux-hardware.org/?probe=4306d9ba1c) | Jan 25, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [b7dea81a92](https://linux-hardware.org/?probe=b7dea81a92) | Jan 25, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [6462d71b74](https://linux-hardware.org/?probe=6462d71b74) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [18d42efe40](https://linux-hardware.org/?probe=18d42efe40) | Jan 24, 2023 |
| HP            | ProBook 6470b               | Notebook    | [3319221b9c](https://linux-hardware.org/?probe=3319221b9c) | Jan 23, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [3951ddfe72](https://linux-hardware.org/?probe=3951ddfe72) | Jan 23, 2023 |
| MSI           | MS-AEC21                    | All in one  | [e541cd3043](https://linux-hardware.org/?probe=e541cd3043) | Jan 23, 2023 |
| HP            | ProBook 6570b               | Notebook    | [3bc0488b6d](https://linux-hardware.org/?probe=3bc0488b6d) | Jan 22, 2023 |
| Dell          | Latitude E6430s             | Notebook    | [8f9185a327](https://linux-hardware.org/?probe=8f9185a327) | Jan 22, 2023 |
| Carbon Sys... | Iridium 14                  | Notebook    | [7fcc79f37c](https://linux-hardware.org/?probe=7fcc79f37c) | Jan 22, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [d2b797f3de](https://linux-hardware.org/?probe=d2b797f3de) | Jan 21, 2023 |
| Acer          | TravelMate B118-M           | Notebook    | [029850a46e](https://linux-hardware.org/?probe=029850a46e) | Jan 21, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [bfaffed5d2](https://linux-hardware.org/?probe=bfaffed5d2) | Jan 21, 2023 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [a6f80e64b2](https://linux-hardware.org/?probe=a6f80e64b2) | Jan 21, 2023 |
| MSI           | Prestige 15 A12SC           | Notebook    | [b368e80a36](https://linux-hardware.org/?probe=b368e80a36) | Jan 21, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [29d770594e](https://linux-hardware.org/?probe=29d770594e) | Jan 21, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [0072a47bce](https://linux-hardware.org/?probe=0072a47bce) | Jan 20, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [732a1b992a](https://linux-hardware.org/?probe=732a1b992a) | Jan 20, 2023 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [49f0bb23ea](https://linux-hardware.org/?probe=49f0bb23ea) | Jan 20, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [28b4d041ad](https://linux-hardware.org/?probe=28b4d041ad) | Jan 20, 2023 |
| Dell          | Latitude 5320               | Notebook    | [aaf625ee63](https://linux-hardware.org/?probe=aaf625ee63) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [2b7ce5b726](https://linux-hardware.org/?probe=2b7ce5b726) | Jan 20, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [d9e9f47ad4](https://linux-hardware.org/?probe=d9e9f47ad4) | Jan 19, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [a9d66d6af6](https://linux-hardware.org/?probe=a9d66d6af6) | Jan 18, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [0bc976587f](https://linux-hardware.org/?probe=0bc976587f) | Jan 18, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [3dfd98d007](https://linux-hardware.org/?probe=3dfd98d007) | Jan 17, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [0426ee9130](https://linux-hardware.org/?probe=0426ee9130) | Jan 17, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [dcbf101b59](https://linux-hardware.org/?probe=dcbf101b59) | Jan 17, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [3964c82d71](https://linux-hardware.org/?probe=3964c82d71) | Jan 17, 2023 |
| HP            | Laptop 17-by3xxx            | Notebook    | [542c3d1ef4](https://linux-hardware.org/?probe=542c3d1ef4) | Jan 16, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [3f24b17bd8](https://linux-hardware.org/?probe=3f24b17bd8) | Jan 16, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [3715650f46](https://linux-hardware.org/?probe=3715650f46) | Jan 16, 2023 |
| Dynabook      | Satellite Pro C50-J         | Notebook    | [ba8e771128](https://linux-hardware.org/?probe=ba8e771128) | Jan 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [86039b3063](https://linux-hardware.org/?probe=86039b3063) | Jan 15, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [aa35c556bc](https://linux-hardware.org/?probe=aa35c556bc) | Jan 13, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [709045636c](https://linux-hardware.org/?probe=709045636c) | Jan 13, 2023 |
| ASUSTek       | G10AJ                       | Desktop     | [e300c19806](https://linux-hardware.org/?probe=e300c19806) | Jan 13, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [1b1fee733e](https://linux-hardware.org/?probe=1b1fee733e) | Jan 12, 2023 |
| Dell          | Latitude 3420               | Notebook    | [53b3f46e20](https://linux-hardware.org/?probe=53b3f46e20) | Jan 12, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | Notebook    | [1987221c12](https://linux-hardware.org/?probe=1987221c12) | Jan 12, 2023 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [6286dbdb0b](https://linux-hardware.org/?probe=6286dbdb0b) | Jan 11, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [c5e0e8163f](https://linux-hardware.org/?probe=c5e0e8163f) | Jan 10, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Kubuntu_22.04/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.0-56-generic | 68        | 4.84%   |
| 5.15.0-52-generic | 66        | 4.7%    |
| 5.15.0-48-generic | 41        | 2.92%   |
| 5.15.0-58-generic | 40        | 2.85%   |
| 5.15.0-43-generic | 39        | 2.78%   |
| 5.15.0-47-generic | 36        | 2.56%   |
| 5.15.0-91-generic | 35        | 2.49%   |
| 6.2.0-26-generic  | 34        | 2.42%   |
| 5.15.0-53-generic | 33        | 2.35%   |
| 5.15.0-46-generic | 33        | 2.35%   |
| 5.15.0-60-generic | 32        | 2.28%   |
| 5.15.0-41-generic | 29        | 2.06%   |
| 5.19.0-35-generic | 28        | 1.99%   |
| 5.15.0-25-generic | 28        | 1.99%   |
| 5.15.0-40-generic | 26        | 1.85%   |
| 5.15.0-67-generic | 25        | 1.78%   |
| 6.2.0-34-generic  | 24        | 1.71%   |
| 5.19.0-46-generic | 24        | 1.71%   |
| 5.15.0-27-generic | 24        | 1.71%   |
| 5.19.0-38-generic | 23        | 1.64%   |
| 5.15.0-50-generic | 23        | 1.64%   |
| 6.2.0-39-generic  | 22        | 1.57%   |
| 5.19.0-41-generic | 19        | 1.35%   |
| 5.19.0-32-generic | 19        | 1.35%   |
| 5.15.0-75-generic | 19        | 1.35%   |
| 6.2.0-37-generic  | 18        | 1.28%   |
| 6.2.0-36-generic  | 18        | 1.28%   |
| 5.15.0-33-generic | 18        | 1.28%   |
| 6.2.0-33-generic  | 16        | 1.14%   |
| 6.5.0-15-generic  | 15        | 1.07%   |
| 5.15.0-78-generic | 15        | 1.07%   |
| 5.15.0-71-generic | 15        | 1.07%   |
| 5.15.0-69-generic | 15        | 1.07%   |
| 6.2.0-32-generic  | 14        | 1%      |
| 5.19.0-42-generic | 14        | 1%      |
| 5.15.0-57-generic | 14        | 1%      |
| 6.5.0-14-generic  | 13        | 0.93%   |
| 5.15.0-73-generic | 13        | 0.93%   |
| 5.19.0-43-generic | 12        | 0.85%   |
| 5.15.0-88-generic | 12        | 0.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 837       | 64.09%  |
| 5.19.0  | 170       | 13.02%  |
| 6.2.0   | 164       | 12.56%  |
| 6.5.0   | 35        | 2.68%   |
| 5.17.0  | 16        | 1.23%   |
| 6.0.0   | 6         | 0.46%   |
| 5.13.0  | 6         | 0.46%   |
| 6.1.0   | 5         | 0.38%   |
| 6.4.10  | 2         | 0.15%   |
| 6.3.8   | 2         | 0.15%   |
| 6.3.6   | 2         | 0.15%   |
| 6.2.2   | 2         | 0.15%   |
| 6.2.16  | 2         | 0.15%   |
| 6.1.5   | 2         | 0.15%   |
| 6.0.7   | 2         | 0.15%   |
| 6.0.1   | 2         | 0.15%   |
| 5.19.5  | 2         | 0.15%   |
| 5.18.4  | 2         | 0.15%   |
| 5.18.10 | 2         | 0.15%   |
| 6.7.1   | 1         | 0.08%   |
| 6.6.2   | 1         | 0.08%   |
| 6.5.7   | 1         | 0.08%   |
| 6.5.5   | 1         | 0.08%   |
| 6.5.3   | 1         | 0.08%   |
| 6.5.10  | 1         | 0.08%   |
| 6.4.8   | 1         | 0.08%   |
| 6.4.0   | 1         | 0.08%   |
| 6.3.9   | 1         | 0.08%   |
| 6.3.4   | 1         | 0.08%   |
| 6.3.1   | 1         | 0.08%   |
| 6.3.0   | 1         | 0.08%   |
| 6.2.8   | 1         | 0.08%   |
| 6.1.9   | 1         | 0.08%   |
| 6.1.69  | 1         | 0.08%   |
| 6.1.58  | 1         | 0.08%   |
| 6.1.55  | 1         | 0.08%   |
| 6.1.12  | 1         | 0.08%   |
| 6.1.1   | 1         | 0.08%   |
| 6.0.9   | 1         | 0.08%   |
| 6.0.8   | 1         | 0.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 839       | 64.34%  |
| 5.19    | 175       | 13.42%  |
| 6.2     | 169       | 12.96%  |
| 6.5     | 39        | 2.99%   |
| 5.17    | 21        | 1.61%   |
| 6.1     | 13        | 1%      |
| 6.0     | 12        | 0.92%   |
| 6.3     | 8         | 0.61%   |
| 5.18    | 8         | 0.61%   |
| 5.13    | 6         | 0.46%   |
| 6.4     | 4         | 0.31%   |
| 5.16    | 3         | 0.23%   |
| 5.10    | 2         | 0.15%   |
| 6.7     | 1         | 0.08%   |
| 6.6     | 1         | 0.08%   |
| 5.4     | 1         | 0.08%   |
| 5.14    | 1         | 0.08%   |
| 5.11    | 1         | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1259      | 99.76%  |
| aarch64 | 2         | 0.16%   |
| riscv64 | 1         | 0.08%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 1238      | 97.87%  |
| KDE        | 10        | 0.79%   |
| GNOME      | 9         | 0.71%   |
| XFCE       | 1         | 0.08%   |
| X-Cinnamon | 1         | 0.08%   |
| Unity      | 1         | 0.08%   |
| MATE       | 1         | 0.08%   |
| i3         | 1         | 0.08%   |
| GNUstep    | 1         | 0.08%   |
| Cinnamon   | 1         | 0.08%   |
| Budgie     | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1204      | 94.88%  |
| Wayland | 41        | 3.23%   |
| Tty     | 23        | 1.81%   |
| Web     | 1         | 0.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 925       | 72.78%  |
| Unknown | 250       | 19.67%  |
| GDM3    | 62        | 4.88%   |
| LightDM | 31        | 2.44%   |
| SLiM    | 1         | 0.08%   |
| LXDM    | 1         | 0.08%   |
| GDM     | 1         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 605       | 47.79%  |
| de_DE   | 111       | 8.77%   |
| it_IT   | 64        | 5.06%   |
| fr_FR   | 62        | 4.9%    |
| ru_RU   | 59        | 4.66%   |
| en_GB   | 57        | 4.5%    |
| es_ES   | 31        | 2.45%   |
| en_AU   | 30        | 2.37%   |
| pt_BR   | 28        | 2.21%   |
| pl_PL   | 22        | 1.74%   |
| en_IN   | 21        | 1.66%   |
| en_CA   | 18        | 1.42%   |
| C       | 11        | 0.87%   |
| es_AR   | 10        | 0.79%   |
| cs_CZ   | 9         | 0.71%   |
| hu_HU   | 8         | 0.63%   |
| nl_NL   | 7         | 0.55%   |
| en_ZA   | 7         | 0.55%   |
| en_PH   | 7         | 0.55%   |
| zh_CN   | 6         | 0.47%   |
| en_NZ   | 6         | 0.47%   |
| tr_TR   | 5         | 0.39%   |
| es_MX   | 5         | 0.39%   |
| es_CO   | 5         | 0.39%   |
| en_SG   | 5         | 0.39%   |
| nl_BE   | 4         | 0.32%   |
| fi_FI   | 4         | 0.32%   |
| el_GR   | 4         | 0.32%   |
| de_CH   | 4         | 0.32%   |
| Default | 4         | 0.32%   |
| fr_CH   | 3         | 0.24%   |
| fr_BE   | 3         | 0.24%   |
| en_AG   | 3         | 0.24%   |
| de_AT   | 3         | 0.24%   |
| sl_SI   | 2         | 0.16%   |
| pt_PT   | 2         | 0.16%   |
| es_VE   | 2         | 0.16%   |
| es_CL   | 2         | 0.16%   |
| en_IL   | 2         | 0.16%   |
| en_DE   | 2         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 678       | 53.22%  |
| BIOS | 596       | 46.78%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1061      | 83.02%  |
| Tmpfs   | 117       | 9.15%   |
| Btrfs   | 45        | 3.52%   |
| Overlay | 41        | 3.21%   |
| Xfs     | 10        | 0.78%   |
| Zfs     | 2         | 0.16%   |
| Ext3    | 1         | 0.08%   |
| Ext2    | 1         | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 864       | 67.87%  |
| Unknown | 321       | 25.22%  |
| MBR     | 88        | 6.91%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1135      | 89.44%  |
| Yes       | 134       | 10.56%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 800       | 63.09%  |
| Yes       | 468       | 36.91%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 216       | 17.12%  |
| ASUSTek Computer    | 211       | 16.72%  |
| Hewlett-Packard     | 170       | 13.47%  |
| Dell                | 147       | 11.65%  |
| Gigabyte Technology | 88        | 6.97%   |
| MSI                 | 85        | 6.74%   |
| Acer                | 61        | 4.83%   |
| ASRock              | 40        | 3.17%   |
| Apple               | 27        | 2.14%   |
| HUAWEI              | 18        | 1.43%   |
| Samsung Electronics | 13        | 1.03%   |
| Google              | 9         | 0.71%   |
| Fujitsu             | 9         | 0.71%   |
| Toshiba             | 8         | 0.63%   |
| Notebook            | 8         | 0.63%   |
| Intel               | 8         | 0.63%   |
| AZW                 | 8         | 0.63%   |
| Alienware           | 8         | 0.63%   |
| Unknown             | 8         | 0.63%   |
| TUXEDO              | 6         | 0.48%   |
| Supermicro          | 6         | 0.48%   |
| Sony                | 5         | 0.4%    |
| Medion              | 5         | 0.4%    |
| Biostar             | 5         | 0.4%    |
| Timi                | 4         | 0.32%   |
| Microsoft           | 4         | 0.32%   |
| System76            | 3         | 0.24%   |
| Schenker            | 3         | 0.24%   |
| PC Specialist       | 3         | 0.24%   |
| Framework           | 3         | 0.24%   |
| VALE                | 2         | 0.16%   |
| Shuttle             | 2         | 0.16%   |
| Razer               | 2         | 0.16%   |
| Positivo            | 2         | 0.16%   |
| Panasonic           | 2         | 0.16%   |
| LG Electronics      | 2         | 0.16%   |
| HONOR               | 2         | 0.16%   |
| Haier               | 2         | 0.16%   |
| GPU Company         | 2         | 0.16%   |
| Foxconn             | 2         | 0.16%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| ASUS All Series                        | 19        | 1.51%   |
| Unknown                                | 13        | 1.03%   |
| ASUS ROG STRIX B550-F GAMING           | 6         | 0.48%   |
| MSI MS-7B79                            | 5         | 0.4%    |
| HUAWEI HVY-WXX9                        | 5         | 0.4%    |
| Lenovo IdeaPad 5 15ARE05 81YQ          | 4         | 0.32%   |
| HP Pavilion g6                         | 4         | 0.32%   |
| HP 255 G8 Notebook PC                  | 4         | 0.32%   |
| MSI MS-7B86                            | 3         | 0.24%   |
| MSI MS-7B51                            | 3         | 0.24%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7       | 3         | 0.24%   |
| Lenovo IdeaPad 3 15ALC6 82KU           | 3         | 0.24%   |
| HP ProBook 6570b                       | 3         | 0.24%   |
| HP ProBook 6470b                       | 3         | 0.24%   |
| HP ProBook 440 G8 Notebook PC          | 3         | 0.24%   |
| HP OMEN Laptop 15-en0xxx               | 3         | 0.24%   |
| HP Notebook                            | 3         | 0.24%   |
| HP Laptop 15-ef2xxx                    | 3         | 0.24%   |
| HP EliteBook 845 G7 Notebook PC        | 3         | 0.24%   |
| HP Compaq Elite 8300 SFF               | 3         | 0.24%   |
| Gigabyte B450M DS3H                    | 3         | 0.24%   |
| Framework Laptop (12th Gen Intel Core) | 3         | 0.24%   |
| Dell XPS 15 9560                       | 3         | 0.24%   |
| Dell OptiPlex 7010                     | 3         | 0.24%   |
| Dell Latitude 7490                     | 3         | 0.24%   |
| Dell Latitude 5420                     | 3         | 0.24%   |
| Dell Latitude 3420                     | 3         | 0.24%   |
| AZW SER                                | 3         | 0.24%   |
| ASUS ROG STRIX X570-E GAMING           | 3         | 0.24%   |
| ASUS PRIME X370-PRO                    | 3         | 0.24%   |
| ASRock B450M Pro4                      | 3         | 0.24%   |
| Acer Aspire A515-45                    | 3         | 0.24%   |
| VALE Notebook Slim S132                | 2         | 0.16%   |
| Timi TM1701                            | 2         | 0.16%   |
| Supermicro SKAGIT09                    | 2         | 0.16%   |
| MSI MS-7D43                            | 2         | 0.16%   |
| MSI MS-7C95                            | 2         | 0.16%   |
| MSI MS-7C56                            | 2         | 0.16%   |
| MSI MS-7B84                            | 2         | 0.16%   |
| MSI MS-7B61                            | 2         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 87        | 6.89%   |
| Lenovo IdeaPad     | 48        | 3.8%    |
| Dell Latitude      | 45        | 3.57%   |
| Acer Aspire        | 36        | 2.85%   |
| ASUS ROG           | 35        | 2.77%   |
| Dell Inspiron      | 29        | 2.3%    |
| HP Pavilion        | 27        | 2.14%   |
| ASUS PRIME         | 27        | 2.14%   |
| HP ProBook         | 25        | 1.98%   |
| HP EliteBook       | 21        | 1.66%   |
| ASUS VivoBook      | 21        | 1.66%   |
| Dell XPS           | 19        | 1.51%   |
| Dell Precision     | 19        | 1.51%   |
| ASUS All           | 19        | 1.51%   |
| HP Laptop          | 18        | 1.43%   |
| ASUS TUF           | 18        | 1.43%   |
| Lenovo ThinkCentre | 17        | 1.35%   |
| Dell OptiPlex      | 16        | 1.27%   |
| Unknown            | 13        | 1.03%   |
| Lenovo Yoga        | 12        | 0.95%   |
| Lenovo Legion      | 12        | 0.95%   |
| Lenovo ThinkBook   | 10        | 0.79%   |
| HP ENVY            | 10        | 0.79%   |
| Acer Nitro         | 10        | 0.79%   |
| Gigabyte X570      | 9         | 0.71%   |
| Dell Vostro        | 9         | 0.71%   |
| Toshiba Satellite  | 7         | 0.55%   |
| HP ZBook           | 7         | 0.55%   |
| HP OMEN            | 6         | 0.48%   |
| ASUS ASUS          | 6         | 0.48%   |
| MSI MS-7B79        | 5         | 0.4%    |
| HUAWEI HVY-WXX9    | 5         | 0.4%    |
| HP ProDesk         | 5         | 0.4%    |
| HP EliteDesk       | 5         | 0.4%    |
| HP Compaq          | 5         | 0.4%    |
| HP 255             | 5         | 0.4%    |
| Fujitsu ESPRIMO    | 5         | 0.4%    |
| Microsoft Surface  | 4         | 0.32%   |
| Lenovo IdeaCentre  | 4         | 0.32%   |
| HP Spectre         | 4         | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 197       | 15.61%  |
| 2020    | 173       | 13.71%  |
| 2019    | 112       | 8.87%   |
| 2022    | 107       | 8.48%   |
| 2018    | 100       | 7.92%   |
| 2012    | 92        | 7.29%   |
| 2014    | 75        | 5.94%   |
| 2017    | 68        | 5.39%   |
| 2013    | 64        | 5.07%   |
| 2016    | 57        | 4.52%   |
| 2011    | 52        | 4.12%   |
| 2015    | 51        | 4.04%   |
| 2010    | 33        | 2.61%   |
| 2023    | 29        | 2.3%    |
| 2009    | 18        | 1.43%   |
| 2008    | 18        | 1.43%   |
| 2007    | 13        | 1.03%   |
| Unknown | 3         | 0.24%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 710       | 56.26%  |
| Desktop        | 456       | 36.13%  |
| Convertible    | 40        | 3.17%   |
| Mini pc        | 20        | 1.58%   |
| All in one     | 15        | 1.19%   |
| Tablet         | 11        | 0.87%   |
| Server         | 7         | 0.55%   |
| System on chip | 2         | 0.16%   |
| Stick pc       | 1         | 0.08%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1143      | 90.07%  |
| Enabled  | 126       | 9.93%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1251      | 99.13%  |
| Yes  | 11        | 0.87%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 341       | 26.81%  |
| 4.01-8.0        | 267       | 20.99%  |
| 8.01-16.0       | 223       | 17.53%  |
| 32.01-64.0      | 212       | 16.67%  |
| 3.01-4.0        | 108       | 8.49%   |
| 64.01-256.0     | 65        | 5.11%   |
| 24.01-32.0      | 39        | 3.07%   |
| 1.01-2.0        | 7         | 0.55%   |
| 2.01-3.0        | 5         | 0.39%   |
| More than 256.0 | 4         | 0.31%   |
| 0.51-1.0        | 1         | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 344       | 25.65%  |
| 2.01-3.0   | 336       | 25.06%  |
| 3.01-4.0   | 269       | 20.06%  |
| 1.01-2.0   | 259       | 19.31%  |
| 8.01-16.0  | 93        | 6.94%   |
| 16.01-24.0 | 20        | 1.49%   |
| 0.51-1.0   | 9         | 0.67%   |
| 24.01-32.0 | 5         | 0.37%   |
| 32.01-64.0 | 4         | 0.3%    |
| 0.01-0.5   | 2         | 0.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 669       | 52.31%  |
| 2      | 357       | 27.91%  |
| 3      | 120       | 9.38%   |
| 4      | 62        | 4.85%   |
| 5      | 31        | 2.42%   |
| 6      | 16        | 1.25%   |
| 7      | 12        | 0.94%   |
| 9      | 3         | 0.23%   |
| 8      | 3         | 0.23%   |
| 0      | 3         | 0.23%   |
| 11     | 2         | 0.16%   |
| 12     | 1         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 922       | 72.89%  |
| Yes       | 343       | 27.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1034      | 81.8%   |
| No        | 230       | 18.2%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1032      | 81.65%  |
| No        | 232       | 18.35%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 896       | 70.5%   |
| No        | 375       | 29.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 274       | 21.66%  |
| Germany      | 144       | 11.38%  |
| Italy        | 88        | 6.96%   |
| France       | 78        | 6.17%   |
| Russia       | 69        | 5.45%   |
| UK           | 55        | 4.35%   |
| Brazil       | 43        | 3.4%    |
| Poland       | 38        | 3%      |
| Spain        | 36        | 2.85%   |
| Australia    | 29        | 2.29%   |
| Netherlands  | 25        | 1.98%   |
| Canada       | 25        | 1.98%   |
| India        | 23        | 1.82%   |
| Switzerland  | 19        | 1.5%    |
| Argentina    | 17        | 1.34%   |
| Hungary      | 16        | 1.26%   |
| Czechia      | 16        | 1.26%   |
| Belgium      | 13        | 1.03%   |
| Finland      | 12        | 0.95%   |
| Indonesia    | 11        | 0.87%   |
| Turkey       | 10        | 0.79%   |
| Mexico       | 10        | 0.79%   |
| Slovenia     | 9         | 0.71%   |
| Bulgaria     | 9         | 0.71%   |
| Austria      | 9         | 0.71%   |
| Sweden       | 8         | 0.63%   |
| Portugal     | 8         | 0.63%   |
| Philippines  | 8         | 0.63%   |
| Thailand     | 7         | 0.55%   |
| South Africa | 7         | 0.55%   |
| Serbia       | 7         | 0.55%   |
| Romania      | 7         | 0.55%   |
| New Zealand  | 7         | 0.55%   |
| Greece       | 7         | 0.55%   |
| China        | 7         | 0.55%   |
| Norway       | 6         | 0.47%   |
| Denmark      | 6         | 0.47%   |
| Singapore    | 5         | 0.4%    |
| Colombia     | 5         | 0.4%    |
| Chile        | 5         | 0.4%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 20        | 1.53%   |
| Milan             | 18        | 1.37%   |
| Berlin            | 17        | 1.3%    |
| Paris             | 11        | 0.84%   |
| Hamburg           | 10        | 0.76%   |
| Warsaw            | 9         | 0.69%   |
| Prague            | 8         | 0.61%   |
| Madrid            | 8         | 0.61%   |
| Budapest          | 8         | 0.61%   |
| Sydney            | 7         | 0.53%   |
| St Petersburg     | 7         | 0.53%   |
| Sao Paulo         | 7         | 0.53%   |
| Munich            | 7         | 0.53%   |
| Montreal          | 7         | 0.53%   |
| Dallas            | 7         | 0.53%   |
| Castro Valley     | 7         | 0.53%   |
| Vladivostok       | 6         | 0.46%   |
| Frankfurt am Main | 6         | 0.46%   |
| Cologne           | 6         | 0.46%   |
| Bengaluru         | 6         | 0.46%   |
| Amsterdam         | 6         | 0.46%   |
| Wroclaw           | 5         | 0.38%   |
| Vienna            | 5         | 0.38%   |
| Singapore         | 5         | 0.38%   |
| Rio de Janeiro    | 5         | 0.38%   |
| New York          | 5         | 0.38%   |
| London            | 5         | 0.38%   |
| Krakow            | 5         | 0.38%   |
| Houston           | 5         | 0.38%   |
| Belgrade          | 5         | 0.38%   |
| Auckland          | 5         | 0.38%   |
| Zurich            | 4         | 0.31%   |
| Washington        | 4         | 0.31%   |
| Vilnius           | 4         | 0.31%   |
| Varna             | 4         | 0.31%   |
| Turin             | 4         | 0.31%   |
| Seattle           | 4         | 0.31%   |
| Rome              | 4         | 0.31%   |
| Melbourne         | 4         | 0.31%   |
| Johannesburg      | 4         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 343       | 543    | 17.18%  |
| WDC                         | 252       | 368    | 12.63%  |
| Seagate                     | 224       | 371    | 11.22%  |
| Kingston                    | 131       | 155    | 6.56%   |
| SanDisk                     | 125       | 170    | 6.26%   |
| Toshiba                     | 108       | 151    | 5.41%   |
| Crucial                     | 82        | 93     | 4.11%   |
| SK hynix                    | 65        | 76     | 3.26%   |
| Unknown                     | 62        | 82     | 3.11%   |
| Intel                       | 57        | 68     | 2.86%   |
| Hitachi                     | 47        | 56     | 2.35%   |
| Micron Technology           | 42        | 45     | 2.1%    |
| A-DATA Technology           | 30        | 36     | 1.5%    |
| KIOXIA                      | 29        | 32     | 1.45%   |
| HGST                        | 29        | 35     | 1.45%   |
| China                       | 22        | 27     | 1.1%    |
| Apple                       | 17        | 20     | 0.85%   |
| Phison                      | 16        | 16     | 0.8%    |
| Phison Electronics          | 15        | 15     | 0.75%   |
| Patriot                     | 15        | 18     | 0.75%   |
| SPCC                        | 14        | 16     | 0.7%    |
| PNY                         | 14        | 27     | 0.7%    |
| Silicon Motion              | 12        | 15     | 0.6%    |
| Unknown                     | 11        | 11     | 0.55%   |
| Micron/Crucial Technology   | 10        | 13     | 0.5%    |
| Kingston Technology Company | 9         | 13     | 0.45%   |
| Corsair                     | 9         | 11     | 0.45%   |
| Maxtor                      | 8         | 10     | 0.4%    |
| JMicron Technology          | 8         | 8      | 0.4%    |
| SSSTC                       | 7         | 7      | 0.35%   |
| SABRENT                     | 7         | 9      | 0.35%   |
| Lexar                       | 7         | 7      | 0.35%   |
| Transcend                   | 6         | 7      | 0.3%    |
| Team                        | 6         | 6      | 0.3%    |
| OCZ                         | 6         | 6      | 0.3%    |
| LITEON                      | 6         | 6      | 0.3%    |
| Realtek Semiconductor       | 5         | 5      | 0.25%   |
| Intenso                     | 5         | 8      | 0.25%   |
| GOODRAM                     | 5         | 6      | 0.25%   |
| Verbatim                    | 4         | 4      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 27        | 1.2%    |
| Kingston SA400S37480G 480GB SSD                    | 21        | 0.93%   |
| Kingston SA400S37240G 240GB SSD                    | 21        | 0.93%   |
| Samsung SSD 860 EVO 500GB                          | 18        | 0.8%    |
| Samsung SSD 850 EVO 500GB                          | 15        | 0.67%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 14        | 0.62%   |
| Samsung SSD 850 EVO 250GB                          | 12        | 0.53%   |
| Toshiba MQ01ABD100 1TB                             | 11        | 0.49%   |
| Toshiba DT01ACA100 1TB                             | 11        | 0.49%   |
| Seagate ST2000DM008-2FR102 2TB                     | 11        | 0.49%   |
| Samsung SSD 980 PRO 1TB                            | 11        | 0.49%   |
| Samsung SSD 860 EVO 1TB                            | 11        | 0.49%   |
| Unknown                                            | 11        | 0.49%   |
| Unknown MMC Card  64GB                             | 10        | 0.45%   |
| Seagate ST4000DM004-2CV104 4TB                     | 10        | 0.45%   |
| Samsung SSD 980 1TB                                | 10        | 0.45%   |
| Samsung SSD 970 EVO Plus 500GB                     | 10        | 0.45%   |
| Samsung SSD 970 EVO Plus 1TB                       | 10        | 0.45%   |
| Samsung SSD 870 EVO 1TB                            | 10        | 0.45%   |
| Crucial CT500MX500SSD1 500GB                       | 10        | 0.45%   |
| Crucial CT1000MX500SSD1 1TB                        | 10        | 0.45%   |
| Unknown MMC Card  32GB                             | 9         | 0.4%    |
| Seagate ST1000LM035-1RK172 1TB                     | 9         | 0.4%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 9         | 0.4%    |
| SanDisk NVMe SSD Drive 1TB                         | 9         | 0.4%    |
| Samsung SSD 870 QVO 1TB                            | 9         | 0.4%    |
| Crucial CT240BX500SSD1 240GB                       | 9         | 0.4%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 8         | 0.36%   |
| Seagate Expansion 1TB                              | 8         | 0.36%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB               | 8         | 0.36%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 7         | 0.31%   |
| Unknown MMC Card  128GB                            | 7         | 0.31%   |
| Toshiba MQ04ABF100 1TB                             | 7         | 0.31%   |
| Seagate ST2000LM007-1R8174 2TB                     | 7         | 0.31%   |
| Seagate ST2000DM001-1ER164 2TB                     | 7         | 0.31%   |
| Samsung SSD 970 EVO Plus 250GB                     | 7         | 0.31%   |
| Samsung SSD 870 EVO 500GB                          | 7         | 0.31%   |
| Samsung SSD 860 QVO 1TB                            | 7         | 0.31%   |
| SABRENT Disk 500GB                                 | 7         | 0.31%   |
| Phison PS5013 E13 NVMe Controller 256GB            | 7         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 212       | 350    | 36.12%  |
| WDC                 | 175       | 249    | 29.81%  |
| Toshiba             | 73        | 105    | 12.44%  |
| Hitachi             | 47        | 56     | 8.01%   |
| HGST                | 29        | 35     | 4.94%   |
| Samsung Electronics | 24        | 38     | 4.09%   |
| Maxtor              | 7         | 9      | 1.19%   |
| JMicron Technology  | 5         | 5      | 0.85%   |
| Apple               | 5         | 5      | 0.85%   |
| Unknown             | 3         | 3      | 0.51%   |
| SAGE                | 1         | 1      | 0.17%   |
| KESU                | 1         | 1      | 0.17%   |
| IET                 | 1         | 1      | 0.17%   |
| HPE                 | 1         | 6      | 0.17%   |
| HGST HTS            | 1         | 1      | 0.17%   |
| Fujitsu             | 1         | 1      | 0.17%   |
| External            | 1         | 1      | 0.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 168       | 251    | 25.11%  |
| Kingston            | 88        | 101    | 13.15%  |
| Crucial             | 63        | 71     | 9.42%   |
| SanDisk             | 61        | 78     | 9.12%   |
| WDC                 | 40        | 64     | 5.98%   |
| A-DATA Technology   | 24        | 29     | 3.59%   |
| China               | 21        | 26     | 3.14%   |
| Patriot             | 15        | 18     | 2.24%   |
| Intel               | 14        | 19     | 2.09%   |
| PNY                 | 12        | 25     | 1.79%   |
| SPCC                | 11        | 11     | 1.64%   |
| Micron Technology   | 11        | 11     | 1.64%   |
| Toshiba             | 7         | 10     | 1.05%   |
| SABRENT             | 7         | 9      | 1.05%   |
| SK hynix            | 6         | 6      | 0.9%    |
| OCZ                 | 6         | 6      | 0.9%    |
| LITEON              | 6         | 6      | 0.9%    |
| Lexar               | 6         | 6      | 0.9%    |
| Apple               | 6         | 6      | 0.9%    |
| Transcend           | 5         | 5      | 0.75%   |
| Team                | 5         | 5      | 0.75%   |
| GOODRAM             | 5         | 6      | 0.75%   |
| Verbatim            | 4         | 4      | 0.6%    |
| Intenso             | 4         | 5      | 0.6%    |
| Plextor             | 3         | 3      | 0.45%   |
| Mushkin             | 3         | 4      | 0.45%   |
| LITEONIT            | 3         | 3      | 0.45%   |
| Hewlett-Packard     | 3         | 3      | 0.45%   |
| Emtec               | 3         | 3      | 0.45%   |
| Corsair             | 3         | 3      | 0.45%   |
| Unknown             | 3         | 3      | 0.45%   |
| USB3.0              | 2         | 2      | 0.3%    |
| Smart               | 2         | 2      | 0.3%    |
| Seagate             | 2         | 3      | 0.3%    |
| Netac               | 2         | 2      | 0.3%    |
| KODAK               | 2         | 2      | 0.3%    |
| KIOXIA-EXCERIA      | 2         | 4      | 0.3%    |
| KingSpec            | 2         | 2      | 0.3%    |
| Apacer              | 2         | 2      | 0.3%    |
| ADATA SU            | 2         | 2      | 0.3%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 635       | 861    | 35.67%  |
| SSD     | 565       | 860    | 31.74%  |
| HDD     | 481       | 867    | 27.02%  |
| MMC     | 59        | 70     | 3.31%   |
| Unknown | 40        | 56     | 2.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 786       | 1644   | 50.16%  |
| NVMe | 632       | 854    | 40.33%  |
| SAS  | 90        | 146    | 5.74%   |
| MMC  | 59        | 70     | 3.77%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 546       | 866    | 48.71%  |
| 0.51-1.0   | 332       | 470    | 29.62%  |
| 1.01-2.0   | 121       | 179    | 10.79%  |
| 3.01-4.0   | 60        | 120    | 5.35%   |
| 4.01-10.0  | 32        | 53     | 2.85%   |
| 2.01-3.0   | 23        | 27     | 2.05%   |
| 10.01-20.0 | 7         | 12     | 0.62%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 301       | 23.35%  |
| 101-250        | 264       | 20.48%  |
| 501-1000       | 246       | 19.08%  |
| 1001-2000      | 177       | 13.73%  |
| More than 3000 | 118       | 9.15%   |
| 2001-3000      | 77        | 5.97%   |
| 1-20           | 46        | 3.57%   |
| 51-100         | 44        | 3.41%   |
| 21-50          | 13        | 1.01%   |
| Unknown        | 3         | 0.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 255       | 19.44%  |
| 101-250        | 247       | 18.83%  |
| 21-50          | 173       | 13.19%  |
| 51-100         | 168       | 12.8%   |
| 251-500        | 164       | 12.5%   |
| 501-1000       | 140       | 10.67%  |
| 1001-2000      | 84        | 6.4%    |
| More than 3000 | 55        | 4.19%   |
| 2001-3000      | 23        | 1.75%   |
| Unknown        | 3         | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 3         | 3      | 2.33%   |
| Samsung Electronics SSD 870 EVO 500GB | 3         | 3      | 2.33%   |
| Samsung Electronics SSD 870 EVO 1TB   | 3         | 3      | 2.33%   |
| HGST HTS545050A7E680 500GB            | 3         | 3      | 2.33%   |
| Toshiba MQ04ABF100 1TB                | 2         | 2      | 1.55%   |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 2         | 2      | 1.55%   |
| SK hynix BC711 HFM256GD3JX013N 256GB  | 2         | 2      | 1.55%   |
| Seagate ST3500418AS 500GB             | 2         | 2      | 1.55%   |
| Seagate ST2000LM007-1R8174 2TB        | 2         | 2      | 1.55%   |
| SanDisk SSD PLUS 240GB                | 2         | 2      | 1.55%   |
| Samsung Electronics HM321HI 320GB     | 2         | 2      | 1.55%   |
| Samsung Electronics HD103SI 1TB       | 2         | 2      | 1.55%   |
| Maxtor STM3250310AS 250GB             | 2         | 2      | 1.55%   |
| Kingston SUV400S37240G 240GB SSD      | 2         | 2      | 1.55%   |
| Kingston SA400S37480G 480GB SSD       | 2         | 2      | 1.55%   |
| Hitachi HTS547550A9E384 500GB         | 2         | 2      | 1.55%   |
| Hitachi HDS721010CLA630 1TB           | 2         | 2      | 1.55%   |
| HGST HTS721010A9E630 1TB              | 2         | 2      | 1.55%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 1         | 1      | 0.78%   |
| WDC WD7502ABYS-02A6B0 752GB           | 1         | 1      | 0.78%   |
| WDC WD5000AZRX-00A3KB0 500GB          | 1         | 1      | 0.78%   |
| WDC WD5000AVVS-63M8B0 500GB           | 1         | 1      | 0.78%   |
| WDC WD5000AAKS-00V1A0 500GB           | 1         | 1      | 0.78%   |
| WDC WD40EURX-63BMCY0 4TB              | 1         | 1      | 0.78%   |
| WDC WD40EFAX-68JH4N1 4TB              | 1         | 4      | 0.78%   |
| WDC WD3200JD-22KLB0 320GB             | 1         | 1      | 0.78%   |
| WDC WD30EZRX-00MMMB0 3TB              | 1         | 1      | 0.78%   |
| WDC WD30EFRX-68EUZN0 3TB              | 1         | 1      | 0.78%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1         | 2      | 0.78%   |
| WDC WD20EADS-14R6B0 2TB               | 1         | 1      | 0.78%   |
| WDC WD10EZRX-00L4HB0 1TB              | 1         | 1      | 0.78%   |
| WDC WD10EZEX-22MFCA0 1TB              | 1         | 1      | 0.78%   |
| WDC WD10EZEX-08M2NA0 1TB              | 1         | 1      | 0.78%   |
| WDC WD10EURX-73C57Y0 1TB              | 1         | 1      | 0.78%   |
| WDC WD10EARS-00MVWB0 1TB              | 1         | 1      | 0.78%   |
| WDC WD10EADS-00L5B1 1TB               | 1         | 1      | 0.78%   |
| WDC WD10EACS-65D6B0 1TB               | 1         | 1      | 0.78%   |
| WDC WD1001FALS-40U9B0 1TB             | 1         | 1      | 0.78%   |
| VISIPRO SSD 256GB                     | 1         | 2      | 0.78%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD  | 1         | 1      | 0.78%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 27     | 18.4%   |
| WDC                 | 18        | 24     | 14.4%   |
| Samsung Electronics | 16        | 26     | 12.8%   |
| Hitachi             | 11        | 11     | 8.8%    |
| Toshiba             | 8         | 8      | 6.4%    |
| Crucial             | 7         | 7      | 5.6%    |
| HGST                | 6         | 6      | 4.8%    |
| SK hynix            | 5         | 5      | 4%      |
| SanDisk             | 5         | 5      | 4%      |
| Kingston            | 4         | 4      | 3.2%    |
| Maxtor              | 3         | 3      | 2.4%    |
| A-DATA Technology   | 3         | 3      | 2.4%    |
| Micron Technology   | 2         | 2      | 1.6%    |
| Intel               | 2         | 5      | 1.6%    |
| VISIPRO             | 1         | 2      | 0.8%    |
| tecmiyo             | 1         | 3      | 0.8%    |
| T-FORCE             | 1         | 1      | 0.8%    |
| SSSTC               | 1         | 1      | 0.8%    |
| R580                | 1         | 1      | 0.8%    |
| Phison Electronics  | 1         | 1      | 0.8%    |
| OCZ                 | 1         | 1      | 0.8%    |
| LITEONIT            | 1         | 1      | 0.8%    |
| LITEON              | 1         | 1      | 0.8%    |
| Intenso             | 1         | 1      | 0.8%    |
| Corsair             | 1         | 1      | 0.8%    |
| BAITITON            | 1         | 1      | 0.8%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 27     | 31.94%  |
| WDC                 | 17        | 23     | 23.61%  |
| Hitachi             | 11        | 11     | 15.28%  |
| Toshiba             | 7         | 7      | 9.72%   |
| HGST                | 6         | 6      | 8.33%   |
| Samsung Electronics | 5         | 15     | 6.94%   |
| Maxtor              | 3         | 3      | 4.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 68        | 92     | 57.14%  |
| SSD  | 42        | 50     | 35.29%  |
| NVMe | 9         | 9      | 7.56%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HD502IJ 500GB | 1         | 1      | 50%     |
| Hitachi HTS547550A9E384 500GB     | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 50%     |
| Hitachi             | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 695       | 1270   | 48.67%  |
| Detected | 617       | 1291   | 43.21%  |
| Malfunc  | 115       | 151    | 8.05%   |
| Failed   | 1         | 2      | 0.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 754       | 42.82%  |
| AMD                                     | 276       | 15.67%  |
| Samsung Electronics                     | 189       | 10.73%  |
| SanDisk                                 | 114       | 6.47%   |
| SK hynix                                | 59        | 3.35%   |
| Kingston Technology Company             | 55        | 3.12%   |
| Phison Electronics                      | 40        | 2.27%   |
| Toshiba America Info Systems            | 31        | 1.76%   |
| Micron Technology                       | 31        | 1.76%   |
| Micron/Crucial Technology               | 29        | 1.65%   |
| ASMedia Technology                      | 29        | 1.65%   |
| KIOXIA                                  | 27        | 1.53%   |
| JMicron Technology                      | 17        | 0.97%   |
| Silicon Motion                          | 15        | 0.85%   |
| Marvell Technology Group                | 12        | 0.68%   |
| Realtek Semiconductor                   | 11        | 0.62%   |
| ADATA Technology                        | 9         | 0.51%   |
| Solid State Storage Technology          | 8         | 0.45%   |
| LSI Logic / Symbios Logic               | 7         | 0.4%    |
| Union Memory (Shenzhen)                 | 6         | 0.34%   |
| Apple                                   | 6         | 0.34%   |
| Seagate Technology                      | 5         | 0.28%   |
| Nvidia                                  | 5         | 0.28%   |
| Broadcom / LSI                          | 4         | 0.23%   |
| Shenzhen Longsys Electronics            | 3         | 0.17%   |
| MAXIO Technology (Hangzhou)             | 3         | 0.17%   |
| Zhaoxin                                 | 2         | 0.11%   |
| Silicon Image                           | 2         | 0.11%   |
| Netac Technology                        | 2         | 0.11%   |
| Yangtze Memory Technologies             | 1         | 0.06%   |
| VIA Technologies                        | 1         | 0.06%   |
| Solidigm                                | 1         | 0.06%   |
| OCZ Technology Group                    | 1         | 0.06%   |
| O2 Micro                                | 1         | 0.06%   |
| Lenovo                                  | 1         | 0.06%   |
| Jiangsu Xinsheng Intelligent Technology | 1         | 0.06%   |
| INNOGRIT                                | 1         | 0.06%   |
| Hewlett-Packard                         | 1         | 0.06%   |
| Unknown                                 | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 193       | 9.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 82        | 4.13%   |
| Intel Volume Management Device NVMe RAID Controller                            | 68        | 3.42%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 60        | 3.02%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 60        | 3.02%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 54        | 2.72%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 52        | 2.62%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 43        | 2.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 40        | 2.01%   |
| AMD 400 Series Chipset SATA Controller                                         | 38        | 1.91%   |
| AMD 500 Series Chipset SATA Controller                                         | 31        | 1.56%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 27        | 1.36%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 27        | 1.36%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 26        | 1.31%   |
| Intel Tiger Lake-LP SATA Controller                                            | 25        | 1.26%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 25        | 1.26%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 25        | 1.26%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 24        | 1.21%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 24        | 1.21%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 23        | 1.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 22        | 1.11%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 21        | 1.06%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 20        | 1.01%   |
| Intel SATA Controller [RAID mode]                                              | 20        | 1.01%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 19        | 0.96%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 19        | 0.96%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 18        | 0.91%   |
| Intel SSD 660P Series                                                          | 18        | 0.91%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 18        | 0.91%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 17        | 0.86%   |
| Intel Comet Lake SATA AHCI Controller                                          | 17        | 0.86%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 17        | 0.86%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 15        | 0.76%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 15        | 0.76%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 14        | 0.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 14        | 0.7%    |
| Phison E12 NVMe Controller                                                     | 13        | 0.65%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 13        | 0.65%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 13        | 0.65%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 12        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 891       | 50.97%  |
| NVMe | 628       | 35.93%  |
| RAID | 142       | 8.12%   |
| IDE  | 79        | 4.52%   |
| SAS  | 6         | 0.34%   |
| SCSI | 2         | 0.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor        | Computers | Percent |
|---------------|-----------|---------|
| Intel         | 895       | 70.92%  |
| AMD           | 362       | 28.68%  |
| CentaurHauls  | 2         | 0.16%   |
| ARM           | 2         | 0.16%   |
| sifive,u74-mc | 1         | 0.08%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 28        | 2.22%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 21        | 1.66%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 20        | 1.58%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 20        | 1.58%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 17        | 1.35%   |
| Intel 12th Gen Core i7-12700H           | 14        | 1.11%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 14        | 1.11%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 13        | 1.03%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 13        | 1.03%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 12        | 0.95%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 12        | 0.95%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 11        | 0.87%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 10        | 0.79%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 10        | 0.79%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 10        | 0.79%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 9         | 0.71%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 9         | 0.71%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 9         | 0.71%   |
| Intel 12th Gen Core i7-1255U            | 9         | 0.71%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 8         | 0.63%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 8         | 0.63%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 8         | 0.63%   |
| Intel 12th Gen Core i7-1260P            | 8         | 0.63%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 7         | 0.55%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 7         | 0.55%   |
| Intel Core i5-9600K CPU @ 3.70GHz       | 7         | 0.55%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 7         | 0.55%   |
| Intel Core i5-10400F CPU @ 2.90GHz      | 7         | 0.55%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 7         | 0.55%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 7         | 0.55%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 7         | 0.55%   |
| AMD Ryzen 5 4600H with Radeon Graphics  | 7         | 0.55%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 6         | 0.48%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 6         | 0.48%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 6         | 0.48%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 6         | 0.48%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 6         | 0.48%   |
| Intel Celeron N4000 CPU @ 1.10GHz       | 6         | 0.48%   |
| Intel 12th Gen Core i5-1240P            | 6         | 0.48%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 6         | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 257       | 20.36%  |
| Intel Core i5           | 239       | 18.94%  |
| Other                   | 192       | 15.21%  |
| AMD Ryzen 7             | 104       | 8.24%   |
| AMD Ryzen 5             | 93        | 7.37%   |
| Intel Core i3           | 59        | 4.68%   |
| Intel Celeron           | 44        | 3.49%   |
| AMD Ryzen 9             | 39        | 3.09%   |
| Intel Xeon              | 25        | 1.98%   |
| Intel Pentium           | 21        | 1.66%   |
| AMD Ryzen 3             | 21        | 1.66%   |
| Intel Core 2 Duo        | 20        | 1.58%   |
| AMD FX                  | 15        | 1.19%   |
| Intel Core i9           | 14        | 1.11%   |
| AMD Ryzen 7 PRO         | 14        | 1.11%   |
| AMD A6                  | 11        | 0.87%   |
| AMD A8                  | 9         | 0.71%   |
| Intel Pentium Silver    | 7         | 0.55%   |
| Intel Atom              | 6         | 0.48%   |
| AMD Ryzen 5 PRO         | 6         | 0.48%   |
| AMD Phenom II X4        | 6         | 0.48%   |
| AMD A10                 | 6         | 0.48%   |
| Intel Core 2 Quad       | 5         | 0.4%    |
| AMD Athlon              | 5         | 0.4%    |
| Intel Pentium Gold      | 3         | 0.24%   |
| Intel Pentium Dual-Core | 3         | 0.24%   |
| Intel Core m3           | 3         | 0.24%   |
| AMD Ryzen Threadripper  | 3         | 0.24%   |
| AMD E                   | 3         | 0.24%   |
| AMD Athlon 64 X2        | 3         | 0.24%   |
| Intel Xeon Gold         | 2         | 0.16%   |
| AMD PRO A10             | 2         | 0.16%   |
| AMD Phenom II X6        | 2         | 0.16%   |
| AMD Phenom II X2        | 2         | 0.16%   |
| AMD Opteron             | 2         | 0.16%   |
| AMD Athlon II X2        | 2         | 0.16%   |
| AMD Athlon II           | 2         | 0.16%   |
| AMD A4                  | 2         | 0.16%   |
| Intel Core M            | 1         | 0.08%   |
| Intel Core 2            | 1         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 452       | 35.82%  |
| 2       | 333       | 26.39%  |
| 6       | 175       | 13.87%  |
| 8       | 166       | 13.15%  |
| 12      | 39        | 3.09%   |
| 14      | 27        | 2.14%   |
| 10      | 27        | 2.14%   |
| 16      | 22        | 1.74%   |
| 24      | 7         | 0.55%   |
| 1       | 7         | 0.55%   |
| 3       | 2         | 0.16%   |
| Unknown | 2         | 0.16%   |
| 44      | 1         | 0.08%   |
| 36      | 1         | 0.08%   |
| 5       | 1         | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1250      | 99.05%  |
| 2       | 10        | 0.79%   |
| Unknown | 2         | 0.16%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 986       | 77.82%  |
| 1       | 279       | 22.02%  |
| Unknown | 2         | 0.16%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1259      | 99.76%  |
| Unknown        | 2         | 0.16%   |
| 64-bit         | 1         | 0.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 599       | 46.58%  |
| 0x306a9    | 40        | 3.11%   |
| 0x0a50000c | 38        | 2.95%   |
| 0x806c1    | 37        | 2.88%   |
| 0x306c3    | 34        | 2.64%   |
| 0x906a3    | 33        | 2.57%   |
| 0x806ea    | 28        | 2.18%   |
| 0x906ea    | 25        | 1.94%   |
| 0x206a7    | 19        | 1.48%   |
| 0x08608103 | 19        | 1.48%   |
| 0x806ec    | 18        | 1.4%    |
| 0x08701021 | 17        | 1.32%   |
| 0x08600106 | 17        | 1.32%   |
| 0x906e9    | 15        | 1.17%   |
| 0x506e3    | 15        | 1.17%   |
| 0x806e9    | 13        | 1.01%   |
| 0x906ed    | 11        | 0.86%   |
| 0x406e3    | 11        | 0.86%   |
| 0x906a4    | 10        | 0.78%   |
| 0x0a50000d | 10        | 0.78%   |
| 0x08108109 | 10        | 0.78%   |
| 0x1067a    | 9         | 0.7%    |
| 0x0800820d | 9         | 0.7%    |
| 0xa0653    | 8         | 0.62%   |
| 0xa0652    | 8         | 0.62%   |
| 0x806c2    | 8         | 0.62%   |
| 0x706a8    | 8         | 0.62%   |
| 0x08608102 | 8         | 0.62%   |
| 0x706a1    | 7         | 0.54%   |
| 0x40651    | 7         | 0.54%   |
| 0x010000c8 | 7         | 0.54%   |
| 0xa0655    | 6         | 0.47%   |
| 0x90672    | 6         | 0.47%   |
| 0x806d1    | 6         | 0.47%   |
| 0x706e5    | 6         | 0.47%   |
| 0x0a201016 | 6         | 0.47%   |
| 0x406f1    | 5         | 0.39%   |
| 0x40661    | 5         | 0.39%   |
| 0x306d4    | 5         | 0.39%   |
| 0x0a601203 | 5         | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 195       | 15.4%   |
| Haswell          | 110       | 8.69%   |
| IvyBridge        | 103       | 8.14%   |
| Unknown          | 98        | 7.74%   |
| Zen 3            | 97        | 7.66%   |
| TigerLake        | 76        | 6%      |
| Alderlake Hybrid | 65        | 5.13%   |
| Zen 2            | 62        | 4.9%    |
| Skylake          | 56        | 4.42%   |
| Zen+             | 47        | 3.71%   |
| SandyBridge      | 47        | 3.71%   |
| CometLake        | 40        | 3.16%   |
| Goldmont plus    | 32        | 2.53%   |
| IceLake          | 31        | 2.45%   |
| Zen              | 25        | 1.97%   |
| Broadwell        | 23        | 1.82%   |
| Penryn           | 22        | 1.74%   |
| Piledriver       | 21        | 1.66%   |
| Westmere         | 18        | 1.42%   |
| K10              | 17        | 1.34%   |
| Excavator        | 14        | 1.11%   |
| Nehalem          | 12        | 0.95%   |
| Silvermont       | 11        | 0.87%   |
| Core             | 11        | 0.87%   |
| Goldmont         | 7         | 0.55%   |
| Puma             | 5         | 0.39%   |
| Bobcat           | 5         | 0.39%   |
| Steamroller      | 4         | 0.32%   |
| K10 Llano        | 4         | 0.32%   |
| K8 Hammer        | 3         | 0.24%   |
| Bulldozer        | 2         | 0.16%   |
| Bonnell          | 2         | 0.16%   |
| K8 & K10 hybrid  | 1         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 693       | 45.23%  |
| Nvidia                     | 453       | 29.57%  |
| AMD                        | 375       | 24.48%  |
| Matrox Electronics Systems | 6         | 0.39%   |
| ASPEED Technology          | 3         | 0.2%    |
| Zhaoxin                    | 2         | 0.13%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 68        | 4.36%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 58        | 3.72%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 48        | 3.08%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 35        | 2.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 35        | 2.25%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 35        | 2.25%   |
| AMD Lucienne                                                                | 35        | 2.25%   |
| Intel UHD Graphics 620                                                      | 33        | 2.12%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 32        | 2.05%   |
| Intel HD Graphics 620                                                       | 30        | 1.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 29        | 1.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 27        | 1.73%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 25        | 1.6%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 23        | 1.48%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 22        | 1.41%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 20        | 1.28%   |
| Intel HD Graphics 530                                                       | 19        | 1.22%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 19        | 1.22%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 19        | 1.22%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 18        | 1.15%   |
| Intel HD Graphics 630                                                       | 18        | 1.15%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 16        | 1.03%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 16        | 1.03%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 15        | 0.96%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                 | 15        | 0.96%   |
| Nvidia GK208B [GeForce GT 710]                                              | 13        | 0.83%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 12        | 0.77%   |
| Intel HD Graphics 5500                                                      | 12        | 0.77%   |
| AMD Rembrandt [Radeon 680M]                                                 | 12        | 0.77%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 11        | 0.71%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 10        | 0.64%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 10        | 0.64%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 10        | 0.64%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 10        | 0.64%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 9         | 0.58%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 9         | 0.58%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 9         | 0.58%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                  | 9         | 0.58%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 9         | 0.58%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                      | 9         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 461       | 36.47%  |
| 1 x AMD                  | 280       | 22.15%  |
| 1 x Nvidia               | 242       | 19.15%  |
| Intel + Nvidia           | 166       | 13.13%  |
| AMD + Nvidia             | 38        | 3.01%   |
| Intel + AMD              | 35        | 2.77%   |
| 2 x AMD                  | 18        | 1.42%   |
| Other                    | 7         | 0.55%   |
| 2 x Nvidia               | 4         | 0.32%   |
| 1 x Matrox               | 3         | 0.24%   |
| 1 x Zhaoxin              | 2         | 0.16%   |
| Nvidia + ASPEED          | 2         | 0.16%   |
| AMD + Matrox             | 2         | 0.16%   |
| 3 x Nvidia               | 1         | 0.08%   |
| Nvidia + Matrox          | 1         | 0.08%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.08%   |
| 1 x ASPEED               | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 910       | 71.71%  |
| Proprietary | 322       | 25.37%  |
| Unknown     | 37        | 2.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 815       | 63.77%  |
| 0.01-0.5   | 112       | 8.76%   |
| 1.01-2.0   | 103       | 8.06%   |
| 3.01-4.0   | 71        | 5.56%   |
| 0.51-1.0   | 57        | 4.46%   |
| 7.01-8.0   | 56        | 4.38%   |
| 5.01-6.0   | 36        | 2.82%   |
| 8.01-16.0  | 20        | 1.56%   |
| 16.01-24.0 | 4         | 0.31%   |
| 2.01-3.0   | 3         | 0.23%   |
| 4.01-5.0   | 1         | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 186       | 12.48%  |
| BOE                     | 151       | 10.13%  |
| AU Optronics            | 151       | 10.13%  |
| Chimei Innolux          | 140       | 9.4%    |
| LG Display              | 120       | 8.05%   |
| Dell                    | 99        | 6.64%   |
| Goldstar                | 89        | 5.97%   |
| Hewlett-Packard         | 63        | 4.23%   |
| Philips                 | 44        | 2.95%   |
| Acer                    | 44        | 2.95%   |
| BenQ                    | 31        | 2.08%   |
| AOC                     | 28        | 1.88%   |
| Iiyama                  | 26        | 1.74%   |
| Sharp                   | 25        | 1.68%   |
| ASUSTek Computer        | 25        | 1.68%   |
| Ancor Communications    | 25        | 1.68%   |
| Apple                   | 22        | 1.48%   |
| InfoVision              | 17        | 1.14%   |
| Lenovo                  | 15        | 1.01%   |
| CSO                     | 13        | 0.87%   |
| Sony                    | 12        | 0.81%   |
| Chi Mei Optoelectronics | 11        | 0.74%   |
| ViewSonic               | 9         | 0.6%    |
| PANDA                   | 8         | 0.54%   |
| Eizo                    | 7         | 0.47%   |
| NEC Computers           | 6         | 0.4%    |
| Gigabyte Technology     | 6         | 0.4%    |
| Vizio                   | 4         | 0.27%   |
| Sceptre Tech            | 4         | 0.27%   |
| RTK                     | 4         | 0.27%   |
| Panasonic               | 4         | 0.27%   |
| MSI                     | 4         | 0.27%   |
| HKC                     | 4         | 0.27%   |
| Fujitsu Siemens         | 4         | 0.27%   |
| Medion                  | 3         | 0.2%    |
| LG Electronics          | 3         | 0.2%    |
| Insignia                | 3         | 0.2%    |
| Idek Iiyama             | 3         | 0.2%    |
| CHD                     | 3         | 0.2%    |
| Xiaomi                  | 2         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 10        | 0.65%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 10        | 0.65%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 9         | 0.58%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 9         | 0.58%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 8         | 0.52%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 8         | 0.52%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                     | 7         | 0.45%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 6         | 0.39%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                 | 6         | 0.39%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                     | 6         | 0.39%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 6         | 0.39%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch     | 5         | 0.32%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 5         | 0.32%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch              | 5         | 0.32%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                  | 5         | 0.32%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch          | 5         | 0.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 5         | 0.32%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                     | 5         | 0.32%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 5         | 0.32%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 4         | 0.26%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch              | 4         | 0.26%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                       | 4         | 0.26%   |
| Dell P2314H DEL4099 1920x1080 509x286mm 23.0-inch                         | 4         | 0.26%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                     | 4         | 0.26%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                     | 4         | 0.26%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch            | 4         | 0.26%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 4         | 0.26%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 4         | 0.26%   |
| AOC 27G2G8 AOC2702 1920x1080 598x336mm 27.0-inch                          | 4         | 0.26%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 3         | 0.19%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch         | 3         | 0.19%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 3         | 0.19%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 3         | 0.19%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                    | 3         | 0.19%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                        | 3         | 0.19%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch              | 3         | 0.19%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch               | 3         | 0.19%   |
| LG Display LCD Monitor LGD0354 1366x768 293x165mm 13.2-inch               | 3         | 0.19%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 3         | 0.19%   |
| InfoVision LCD Monitor IVO0536 1920x1080 294x165mm 13.3-inch              | 3         | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 702       | 50.54%  |
| 1366x768 (WXGA)    | 173       | 12.46%  |
| 3840x2160 (4K)     | 103       | 7.42%   |
| 2560x1440 (QHD)    | 78        | 5.62%   |
| 1920x1200 (WUXGA)  | 61        | 4.39%   |
| 1600x900 (HD+)     | 42        | 3.02%   |
| 1680x1050 (WSXGA+) | 37        | 2.66%   |
| 2560x1600          | 29        | 2.09%   |
| 3440x1440          | 24        | 1.73%   |
| 1280x1024 (SXGA)   | 23        | 1.66%   |
| 2880x1800          | 17        | 1.22%   |
| 2560x1080          | 13        | 0.94%   |
| 1440x900 (WXGA+)   | 13        | 0.94%   |
| 1360x768           | 8         | 0.58%   |
| 1280x800 (WXGA)    | 7         | 0.5%    |
| 3840x1080          | 6         | 0.43%   |
| 2240x1400          | 6         | 0.43%   |
| Unknown            | 5         | 0.36%   |
| 2160x1440          | 4         | 0.29%   |
| 2256x1504          | 3         | 0.22%   |
| 1920x540           | 3         | 0.22%   |
| 1280x720 (HD)      | 3         | 0.22%   |
| 1024x768 (XGA)     | 3         | 0.22%   |
| 3840x2400          | 2         | 0.14%   |
| 3840x1600          | 2         | 0.14%   |
| 3072x1920          | 2         | 0.14%   |
| 2736x1824          | 2         | 0.14%   |
| 2520x1680          | 2         | 0.14%   |
| 1600x1200          | 2         | 0.14%   |
| 6160x1440          | 1         | 0.07%   |
| 5760x2160          | 1         | 0.07%   |
| 5760x1080          | 1         | 0.07%   |
| 480x1920           | 1         | 0.07%   |
| 4800x1080          | 1         | 0.07%   |
| 3840x1200          | 1         | 0.07%   |
| 3600x1200          | 1         | 0.07%   |
| 3200x1800 (QHD+)   | 1         | 0.07%   |
| 3000x2000          | 1         | 0.07%   |
| 2496x1664          | 1         | 0.07%   |
| 2288x1287          | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 340       | 22.83%  |
| 24      | 143       | 9.6%    |
| 14      | 131       | 8.8%    |
| 27      | 127       | 8.53%   |
| 13      | 118       | 7.92%   |
| 23      | 114       | 7.66%   |
| 21      | 85        | 5.71%   |
| 17      | 79        | 5.31%   |
| 31      | 44        | 2.96%   |
| 16      | 38        | 2.55%   |
| 34      | 35        | 2.35%   |
| Unknown | 26        | 1.75%   |
| 22      | 23        | 1.54%   |
| 19      | 23        | 1.54%   |
| 20      | 17        | 1.14%   |
| 18      | 15        | 1.01%   |
| 12      | 15        | 1.01%   |
| 72      | 13        | 0.87%   |
| 11      | 11        | 0.74%   |
| 32      | 10        | 0.67%   |
| 54      | 9         | 0.6%    |
| 40      | 8         | 0.54%   |
| 46      | 7         | 0.47%   |
| 25      | 7         | 0.47%   |
| 84      | 6         | 0.4%    |
| 65      | 4         | 0.27%   |
| 48      | 4         | 0.27%   |
| 28      | 4         | 0.27%   |
| 10      | 4         | 0.27%   |
| 49      | 3         | 0.2%    |
| 36      | 3         | 0.2%    |
| 69      | 2         | 0.13%   |
| 60      | 2         | 0.13%   |
| 52      | 2         | 0.13%   |
| 42      | 2         | 0.13%   |
| 37      | 2         | 0.13%   |
| 26      | 2         | 0.13%   |
| 142     | 1         | 0.07%   |
| 78      | 1         | 0.07%   |
| 64      | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 546       | 37.66%  |
| 501-600        | 342       | 23.59%  |
| 401-500        | 147       | 10.14%  |
| 351-400        | 103       | 7.1%    |
| 201-300        | 98        | 6.76%   |
| 601-700        | 67        | 4.62%   |
| 701-800        | 48        | 3.31%   |
| 1001-1500      | 35        | 2.41%   |
| Unknown        | 26        | 1.79%   |
| 1501-2000      | 22        | 1.52%   |
| 801-900        | 12        | 0.83%   |
| 901-1000       | 3         | 0.21%   |
| More than 2000 | 1         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1000      | 77.7%   |
| 16/10   | 177       | 13.75%  |
| 21/9    | 39        | 3.03%   |
| 5/4     | 19        | 1.48%   |
| Unknown | 19        | 1.48%   |
| 3/2     | 17        | 1.32%   |
| 4/3     | 6         | 0.47%   |
| 32/9    | 5         | 0.39%   |
| 6/5     | 2         | 0.16%   |
| 1.96    | 1         | 0.08%   |
| 1.00    | 1         | 0.08%   |
| 0.25    | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 348       | 23.84%  |
| 201-250        | 278       | 19.04%  |
| 81-90          | 198       | 13.56%  |
| 301-350        | 129       | 8.84%   |
| 351-500        | 92        | 6.3%    |
| 121-130        | 68        | 4.66%   |
| 151-200        | 59        | 4.04%   |
| 71-80          | 52        | 3.56%   |
| 251-300        | 48        | 3.29%   |
| More than 1000 | 45        | 3.08%   |
| 501-1000       | 30        | 2.05%   |
| 111-120        | 29        | 1.99%   |
| Unknown        | 26        | 1.78%   |
| 141-150        | 21        | 1.44%   |
| 61-70          | 13        | 0.89%   |
| 51-60          | 11        | 0.75%   |
| 131-140        | 6         | 0.41%   |
| 41-50          | 4         | 0.27%   |
| 91-100         | 3         | 0.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 443       | 31.46%  |
| 51-100        | 434       | 30.82%  |
| 101-120       | 285       | 20.24%  |
| 161-240       | 136       | 9.66%   |
| 1-50          | 51        | 3.62%   |
| More than 240 | 33        | 2.34%   |
| Unknown       | 26        | 1.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 935       | 72.93%  |
| 2     | 264       | 20.59%  |
| 3     | 37        | 2.89%   |
| 0     | 35        | 2.73%   |
| 4     | 11        | 0.86%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 698       | 36.09%  |
| Intel                             | 691       | 35.73%  |
| Qualcomm Atheros                  | 157       | 8.12%   |
| Broadcom                          | 85        | 4.4%    |
| MediaTek                          | 70        | 3.62%   |
| TP-Link                           | 23        | 1.19%   |
| Ralink Technology                 | 21        | 1.09%   |
| ASIX Electronics                  | 16        | 0.83%   |
| Samsung Electronics               | 13        | 0.67%   |
| Ralink                            | 12        | 0.62%   |
| Broadcom Limited                  | 11        | 0.57%   |
| Aquantia                          | 10        | 0.52%   |
| Marvell Technology Group          | 8         | 0.41%   |
| Lenovo                            | 8         | 0.41%   |
| Huawei Technologies               | 8         | 0.41%   |
| Sierra Wireless                   | 7         | 0.36%   |
| NetGear                           | 6         | 0.31%   |
| DisplayLink                       | 6         | 0.31%   |
| Xiaomi                            | 5         | 0.26%   |
| Qualcomm Atheros Communications   | 5         | 0.26%   |
| Nvidia                            | 5         | 0.26%   |
| Edimax Technology                 | 5         | 0.26%   |
| Qualcomm                          | 4         | 0.21%   |
| Dell                              | 4         | 0.21%   |
| Belkin Components                 | 4         | 0.21%   |
| Apple                             | 4         | 0.21%   |
| Hewlett-Packard                   | 3         | 0.16%   |
| Ericsson Business Mobile Networks | 3         | 0.16%   |
| D-Link                            | 3         | 0.16%   |
| ASUSTek Computer                  | 3         | 0.16%   |
| Wilocity                          | 2         | 0.1%    |
| VIA Technologies                  | 2         | 0.1%    |
| Solarflare Communications         | 2         | 0.1%    |
| JMicron Technology                | 2         | 0.1%    |
| IBM                               | 2         | 0.1%    |
| Google                            | 2         | 0.1%    |
| D-Link System                     | 2         | 0.1%    |
| ZyXEL Communications              | 1         | 0.05%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.05%   |
| U-Blox                            | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 443       | 19.44%  |
| Intel Wi-Fi 6 AX200                                                    | 78        | 3.42%   |
| Intel Wi-Fi 6 AX201                                                    | 55        | 2.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 53        | 2.33%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 51        | 2.24%   |
| Realtek RTL8125 2.5GbE Controller                                      | 48        | 2.11%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 48        | 2.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 46        | 2.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 43        | 1.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 40        | 1.76%   |
| Intel Wireless 8265 / 8275                                             | 37        | 1.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 35        | 1.54%   |
| Intel I211 Gigabit Network Connection                                  | 34        | 1.49%   |
| Intel Ethernet Controller I225-V                                       | 31        | 1.36%   |
| Intel Wireless 7265                                                    | 26        | 1.14%   |
| Intel Wireless 7260                                                    | 26        | 1.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 24        | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 24        | 1.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 24        | 1.05%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 23        | 1.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 23        | 1.01%   |
| Intel Ethernet Connection I217-LM                                      | 22        | 0.97%   |
| Intel Wireless 8260                                                    | 21        | 0.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 21        | 0.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 19        | 0.83%   |
| Intel Ethernet Connection (7) I219-V                                   | 18        | 0.79%   |
| Intel Ethernet Connection (2) I219-V                                   | 18        | 0.79%   |
| Intel Ethernet Connection (4) I219-LM                                  | 17        | 0.75%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 17        | 0.75%   |
| Intel Wireless 3165                                                    | 15        | 0.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 14        | 0.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 14        | 0.61%   |
| Intel 82579V Gigabit Network Connection                                | 14        | 0.61%   |
| ASIX AX88179 Gigabit Ethernet                                          | 14        | 0.61%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 13        | 0.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 13        | 0.57%   |
| Realtek 802.11ac NIC                                                   | 13        | 0.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 13        | 0.57%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 12        | 0.53%   |
| Intel Ethernet Connection (2) I218-V                                   | 12        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 524       | 48.12%  |
| Realtek Semiconductor             | 200       | 18.37%  |
| Qualcomm Atheros                  | 118       | 10.84%  |
| MediaTek                          | 69        | 6.34%   |
| Broadcom                          | 62        | 5.69%   |
| Ralink Technology                 | 21        | 1.93%   |
| TP-Link                           | 19        | 1.74%   |
| Ralink                            | 12        | 1.1%    |
| Broadcom Limited                  | 8         | 0.73%   |
| Sierra Wireless                   | 7         | 0.64%   |
| NetGear                           | 6         | 0.55%   |
| Qualcomm Atheros Communications   | 5         | 0.46%   |
| Edimax Technology                 | 5         | 0.46%   |
| Qualcomm                          | 4         | 0.37%   |
| Dell                              | 4         | 0.37%   |
| Belkin Components                 | 4         | 0.37%   |
| D-Link                            | 3         | 0.28%   |
| ASUSTek Computer                  | 3         | 0.28%   |
| Wilocity                          | 2         | 0.18%   |
| Marvell Technology Group          | 2         | 0.18%   |
| Ericsson Business Mobile Networks | 2         | 0.18%   |
| D-Link System                     | 2         | 0.18%   |
| ZyXEL Communications              | 1         | 0.09%   |
| Quectel Wireless Solutions        | 1         | 0.09%   |
| Microsoft                         | 1         | 0.09%   |
| Mercucys                          | 1         | 0.09%   |
| Linksys                           | 1         | 0.09%   |
| LG Electronics                    | 1         | 0.09%   |
| Fibocom                           | 1         | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 78        | 7.06%   |
| Intel Wi-Fi 6 AX201                                            | 55        | 4.98%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 51        | 4.62%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 48        | 4.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 40        | 3.62%   |
| Intel Wireless 8265 / 8275                                     | 37        | 3.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 35        | 3.17%   |
| Intel Wireless 7265                                            | 26        | 2.35%   |
| Intel Wireless 7260                                            | 26        | 2.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 24        | 2.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 24        | 2.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 24        | 2.17%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 23        | 2.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 23        | 2.08%   |
| Intel Wireless 8260                                            | 21        | 1.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 21        | 1.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 19        | 1.72%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 17        | 1.54%   |
| Intel Wireless 3165                                            | 15        | 1.36%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 14        | 1.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 14        | 1.27%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 13        | 1.18%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 13        | 1.18%   |
| Realtek 802.11ac NIC                                           | 13        | 1.18%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 13        | 1.18%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 12        | 1.09%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 12        | 1.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 12        | 1.09%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 9         | 0.81%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 9         | 0.81%   |
| Intel Wireless 3160                                            | 9         | 0.81%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 9         | 0.81%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 9         | 0.81%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 9         | 0.81%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 8         | 0.72%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 8         | 0.72%   |
| Realtek 802.11n WLAN Adapter                                   | 8         | 0.72%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 8         | 0.72%   |
| Intel Centrino Advanced-N 6235                                 | 8         | 0.72%   |
| Ralink RT5370 Wireless Adapter                                 | 7         | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 597       | 53.02%  |
| Intel                      | 346       | 30.73%  |
| Qualcomm Atheros           | 43        | 3.82%   |
| Broadcom                   | 35        | 3.11%   |
| ASIX Electronics           | 16        | 1.42%   |
| Samsung Electronics        | 13        | 1.15%   |
| Aquantia                   | 10        | 0.89%   |
| Lenovo                     | 8         | 0.71%   |
| Huawei Technologies        | 8         | 0.71%   |
| Marvell Technology Group   | 6         | 0.53%   |
| DisplayLink                | 6         | 0.53%   |
| Xiaomi                     | 5         | 0.44%   |
| Nvidia                     | 5         | 0.44%   |
| TP-Link                    | 4         | 0.36%   |
| Apple                      | 4         | 0.36%   |
| Broadcom Limited           | 3         | 0.27%   |
| VIA Technologies           | 2         | 0.18%   |
| Solarflare Communications  | 2         | 0.18%   |
| JMicron Technology         | 2         | 0.18%   |
| IBM                        | 2         | 0.18%   |
| Google                     | 2         | 0.18%   |
| ZTE WCDMA Technologies MSM | 1         | 0.09%   |
| Spreadtrum Communications  | 1         | 0.09%   |
| Mellanox Technologies      | 1         | 0.09%   |
| MediaTek                   | 1         | 0.09%   |
| ICS Advent                 | 1         | 0.09%   |
| Hewlett-Packard            | 1         | 0.09%   |
| American Megatrends        | 1         | 0.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 443       | 38.22%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 53        | 4.57%   |
| Realtek RTL8125 2.5GbE Controller                                              | 48        | 4.14%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 46        | 3.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 43        | 3.71%   |
| Intel I211 Gigabit Network Connection                                          | 34        | 2.93%   |
| Intel Ethernet Controller I225-V                                               | 31        | 2.67%   |
| Intel Ethernet Connection I217-LM                                              | 22        | 1.9%    |
| Intel Ethernet Connection (7) I219-V                                           | 18        | 1.55%   |
| Intel Ethernet Connection (2) I219-V                                           | 18        | 1.55%   |
| Intel Ethernet Connection (4) I219-LM                                          | 17        | 1.47%   |
| Intel 82579V Gigabit Network Connection                                        | 14        | 1.21%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 14        | 1.21%   |
| Intel Ethernet Connection (2) I218-V                                           | 12        | 1.04%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 10        | 0.86%   |
| Realtek Killer E2600 GbE Controller                                            | 10        | 0.86%   |
| Intel I210 Gigabit Network Connection                                          | 10        | 0.86%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 9         | 0.78%   |
| Intel Ethernet Connection I219-LM                                              | 9         | 0.78%   |
| Intel Ethernet Connection (7) I219-LM                                          | 8         | 0.69%   |
| Intel Ethernet Connection (10) I219-V                                          | 8         | 0.69%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 7         | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 7         | 0.6%    |
| Intel Ethernet Connection (16) I219-LM                                         | 7         | 0.6%    |
| Intel Ethernet Connection (13) I219-V                                          | 7         | 0.6%    |
| Intel 82574L Gigabit Network Connection                                        | 7         | 0.6%    |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 7         | 0.6%    |
| Intel Ethernet Connection I217-V                                               | 6         | 0.52%   |
| Intel Ethernet Connection (14) I219-V                                          | 6         | 0.52%   |
| Huawei STG-LX1                                                                 | 6         | 0.52%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 5         | 0.43%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 5         | 0.43%   |
| Intel Ethernet Connection (5) I219-LM                                          | 5         | 0.43%   |
| Intel Ethernet Connection (4) I219-V                                           | 5         | 0.43%   |
| Intel Ethernet Connection (3) I218-LM                                          | 5         | 0.43%   |
| Intel Ethernet Connection (2) I219-LM                                          | 5         | 0.43%   |
| Intel Ethernet Connection (11) I219-V                                          | 5         | 0.43%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 5         | 0.43%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 5         | 0.43%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                              | 5         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1032      | 49.69%  |
| WiFi     | 1031      | 49.64%  |
| Modem    | 9         | 0.43%   |
| Unknown  | 5         | 0.24%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 807       | 60.81%  |
| Ethernet | 520       | 39.19%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 654       | 51.82%  |
| 1     | 537       | 42.55%  |
| 3     | 41        | 3.25%   |
| 0     | 21        | 1.66%   |
| 4     | 7         | 0.55%   |
| 6     | 2         | 0.16%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 891       | 70.05%  |
| Yes  | 381       | 29.95%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 462       | 50.6%   |
| Realtek Semiconductor           | 102       | 11.17%  |
| Cambridge Silicon Radio         | 56        | 6.13%   |
| Qualcomm Atheros Communications | 52        | 5.7%    |
| IMC Networks                    | 45        | 4.93%   |
| Broadcom                        | 38        | 4.16%   |
| Foxconn / Hon Hai               | 31        | 3.4%    |
| Lite-On Technology              | 27        | 2.96%   |
| ASUSTek Computer                | 22        | 2.41%   |
| Apple                           | 20        | 2.19%   |
| MediaTek                        | 12        | 1.31%   |
| TP-Link                         | 7         | 0.77%   |
| Realtek                         | 7         | 0.77%   |
| Dell                            | 6         | 0.66%   |
| Toshiba                         | 5         | 0.55%   |
| Ralink                          | 4         | 0.44%   |
| Edimax Technology               | 4         | 0.44%   |
| Marvell Semiconductor           | 2         | 0.22%   |
| Hewlett-Packard                 | 2         | 0.22%   |
| Alps Electric                   | 2         | 0.22%   |
| USI                             | 1         | 0.11%   |
| SINO WEALTH                     | 1         | 0.11%   |
| Foxconn International           | 1         | 0.11%   |
| Dynex                           | 1         | 0.11%   |
| D-Link                          | 1         | 0.11%   |
| Conwise Technology              | 1         | 0.11%   |
| Chicony Electronics             | 1         | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 124       | 13.55%  |
| Intel AX201 Bluetooth                               | 102       | 11.15%  |
| Realtek Bluetooth Radio                             | 83        | 9.07%   |
| Intel AX200 Bluetooth                               | 75        | 8.2%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 56        | 6.12%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 56        | 6.12%   |
| Intel Bluetooth Device                              | 53        | 5.79%   |
| Qualcomm Atheros  Bluetooth Device                  | 26        | 2.84%   |
| Intel AX210 Bluetooth                               | 22        | 2.4%    |
| IMC Networks Wireless_Device                        | 20        | 2.19%   |
| Lite-On Wireless_Device                             | 16        | 1.75%   |
| Foxconn / Hon Hai Wireless_Device                   | 16        | 1.75%   |
| Realtek  Bluetooth 4.2 Adapter                      | 15        | 1.64%   |
| IMC Networks Bluetooth Radio                        | 15        | 1.64%   |
| Apple Bluetooth Host Controller                     | 14        | 1.53%   |
| MediaTek Wireless_Device                            | 12        | 1.31%   |
| Intel Wireless-AC 3168 Bluetooth                    | 12        | 1.31%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 11        | 1.2%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 10        | 1.09%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 10        | 1.09%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 9         | 0.98%   |
| Broadcom HP Portable SoftSailing                    | 9         | 0.98%   |
| ASUS ASUS USB-BT500                                 | 9         | 0.98%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 8         | 0.87%   |
| TP-Link UB500 Adapter                               | 7         | 0.77%   |
| Realtek Bluetooth Radio                             | 7         | 0.77%   |
| Foxconn / Hon Hai Bluetooth Device                  | 7         | 0.77%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 0.66%   |
| IMC Networks Bluetooth Device                       | 5         | 0.55%   |
| Ralink RT3290 Bluetooth                             | 4         | 0.44%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 0.44%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth         | 4         | 0.44%   |
| Dell DW375 Bluetooth Module                         | 4         | 0.44%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 3         | 0.33%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 0.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 3         | 0.33%   |
| Apple Bluetooth USB Host Controller                 | 3         | 0.33%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 0.22%   |
| Realtek RTL8723B Bluetooth                          | 2         | 0.22%   |
| Marvell Bluetooth and Wireless LAN Composite        | 2         | 0.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 873       | 46.49%  |
| AMD                       | 423       | 22.52%  |
| Nvidia                    | 352       | 18.74%  |
| C-Media Electronics       | 34        | 1.81%   |
| GN Netcom                 | 17        | 0.91%   |
| JMTek                     | 12        | 0.64%   |
| Logitech                  | 10        | 0.53%   |
| Lenovo                    | 9         | 0.48%   |
| Generalplus Technology    | 8         | 0.43%   |
| Texas Instruments         | 7         | 0.37%   |
| Realtek Semiconductor     | 7         | 0.37%   |
| Hewlett-Packard           | 7         | 0.37%   |
| Razer USA                 | 6         | 0.32%   |
| Focusrite-Novation        | 6         | 0.32%   |
| Creative Labs             | 6         | 0.32%   |
| Micro Star International  | 5         | 0.27%   |
| Corsair                   | 5         | 0.27%   |
| ASUSTek Computer          | 5         | 0.27%   |
| Apple                     | 5         | 0.27%   |
| VIA Technologies          | 4         | 0.21%   |
| Kingston Technology       | 4         | 0.21%   |
| Blue Microphones          | 4         | 0.21%   |
| Tenx Technology           | 3         | 0.16%   |
| KORG                      | 3         | 0.16%   |
| ZOOM                      | 2         | 0.11%   |
| Zhaoxin                   | 2         | 0.11%   |
| TerraTec Electronic       | 2         | 0.11%   |
| SteelSeries ApS           | 2         | 0.11%   |
| Sony                      | 2         | 0.11%   |
| Sennheiser Communications | 2         | 0.11%   |
| Samson Technologies       | 2         | 0.11%   |
| Plantronics               | 2         | 0.11%   |
| Nordic Semiconductor ASA  | 2         | 0.11%   |
| M-Audio                   | 2         | 0.11%   |
| Creative Technology       | 2         | 0.11%   |
| Arturia                   | 2         | 0.11%   |
| AKAI Professional M.I.    | 2         | 0.11%   |
| Yamaha                    | 1         | 0.05%   |
| XMOS                      | 1         | 0.05%   |
| Veho                      | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 185       | 8.28%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 120       | 5.37%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 92        | 4.12%   |
| Intel Sunrise Point-LP HD Audio                                            | 91        | 4.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 76        | 3.4%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 69        | 3.09%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 59        | 2.64%   |
| Intel Cannon Lake PCH cAVS                                                 | 57        | 2.55%   |
| AMD Starship/Matisse HD Audio Controller                                   | 56        | 2.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 51        | 2.28%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 46        | 2.06%   |
| Nvidia GP107GL High Definition Audio Controller                            | 35        | 1.57%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 34        | 1.52%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 33        | 1.48%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 33        | 1.48%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 31        | 1.39%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 29        | 1.3%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 27        | 1.21%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 26        | 1.16%   |
| Intel 200 Series PCH HD Audio                                              | 26        | 1.16%   |
| Intel Comet Lake PCH cAVS                                                  | 25        | 1.12%   |
| Nvidia GA106 High Definition Audio Controller                              | 24        | 1.07%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 23        | 1.03%   |
| AMD FCH Azalia Controller                                                  | 23        | 1.03%   |
| Nvidia TU116 High Definition Audio Controller                              | 22        | 0.99%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 22        | 0.99%   |
| Nvidia TU106 High Definition Audio Controller                              | 21        | 0.94%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 21        | 0.94%   |
| Nvidia GA104 High Definition Audio Controller                              | 20        | 0.9%    |
| Intel Comet Lake PCH-LP cAVS                                               | 20        | 0.9%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 19        | 0.85%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 18        | 0.81%   |
| Nvidia GP104 High Definition Audio Controller                              | 17        | 0.76%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 17        | 0.76%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 17        | 0.76%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 16        | 0.72%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 16        | 0.72%   |
| Intel Haswell-ULT HD Audio Controller                                      | 16        | 0.72%   |
| Intel Broadwell-U Audio Controller                                         | 16        | 0.72%   |
| Nvidia GK107 HDMI Audio Controller                                         | 15        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 236       | 23.84%  |
| SK hynix                   | 145       | 14.65%  |
| Kingston                   | 120       | 12.12%  |
| Micron Technology          | 106       | 10.71%  |
| Crucial                    | 76        | 7.68%   |
| Corsair                    | 60        | 6.06%   |
| Unknown                    | 47        | 4.75%   |
| G.Skill                    | 41        | 4.14%   |
| A-DATA Technology          | 19        | 1.92%   |
| Unknown (ABCD)             | 18        | 1.82%   |
| Unknown                    | 12        | 1.21%   |
| Ramaxel Technology         | 11        | 1.11%   |
| Elpida                     | 11        | 1.11%   |
| Team                       | 9         | 0.91%   |
| Nanya Technology           | 9         | 0.91%   |
| Transcend                  | 6         | 0.61%   |
| Smart                      | 6         | 0.61%   |
| Patriot                    | 6         | 0.61%   |
| Silicon Power              | 4         | 0.4%    |
| AMD                        | 4         | 0.4%    |
| Wilk                       | 3         | 0.3%    |
| PNY                        | 3         | 0.3%    |
| Lexar                      | 3         | 0.3%    |
| ff                         | 3         | 0.3%    |
| 4ea5                       | 3         | 0.3%    |
| Teikon                     | 2         | 0.2%    |
| GOODRAM                    | 2         | 0.2%    |
| Atermiter                  | 2         | 0.2%    |
| Xi'an UniIC Semiconductors | 1         | 0.1%    |
| V-Color                    | 1         | 0.1%    |
| Unknown (8A02)             | 1         | 0.1%    |
| Unknown (08C8)             | 1         | 0.1%    |
| Unifosa                    | 1         | 0.1%    |
| Super Talent               | 1         | 0.1%    |
| Shenzhen Zhongteng         | 1         | 0.1%    |
| Shenzhen WODPOSIT          | 1         | 0.1%    |
| SHARETRONIC                | 1         | 0.1%    |
| Qumo                       | 1         | 0.1%    |
| Qimonda                    | 1         | 0.1%    |
| Neo Forza                  | 1         | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 15        | 1.44%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 13        | 1.25%   |
| Unknown                                                             | 12        | 1.15%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 10        | 0.96%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s          | 10        | 0.96%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 9         | 0.86%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 9         | 0.86%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 9         | 0.86%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 8         | 0.77%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 7         | 0.67%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s              | 7         | 0.67%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s               | 7         | 0.67%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                | 6         | 0.58%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 6         | 0.58%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 6         | 0.58%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 6         | 0.58%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 6         | 0.58%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 6         | 0.58%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 5         | 0.48%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 5         | 0.48%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 5         | 0.48%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 5         | 0.48%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s               | 5         | 0.48%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s                | 5         | 0.48%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 5         | 0.48%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s                | 5         | 0.48%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 4         | 0.38%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                         | 4         | 0.38%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                         | 4         | 0.38%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 4         | 0.38%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 4         | 0.38%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s              | 4         | 0.38%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s              | 4         | 0.38%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s               | 4         | 0.38%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s             | 4         | 0.38%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s              | 4         | 0.38%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s               | 4         | 0.38%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 3         | 0.29%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                | 3         | 0.29%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s      | 3         | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 491       | 58.8%   |
| DDR3    | 192       | 22.99%  |
| LPDDR4  | 53        | 6.35%   |
| DDR5    | 33        | 3.95%   |
| LPDDR5  | 17        | 2.04%   |
| Unknown | 15        | 1.8%    |
| DDR2    | 13        | 1.56%   |
| SDRAM   | 10        | 1.2%    |
| LPDDR3  | 9         | 1.08%   |
| DDR     | 2         | 0.24%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 481       | 56.99%  |
| DIMM         | 265       | 31.4%   |
| Row Of Chips | 87        | 10.31%  |
| Chip         | 5         | 0.59%   |
| Unknown      | 5         | 0.59%   |
| RIMM         | 1         | 0.12%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 398       | 43.64%  |
| 16384 | 198       | 21.71%  |
| 4096  | 192       | 21.05%  |
| 2048  | 60        | 6.58%   |
| 32768 | 56        | 6.14%   |
| 1024  | 8         | 0.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 237       | 26.33%  |
| 1600    | 131       | 14.56%  |
| 2667    | 119       | 13.22%  |
| 2400    | 76        | 8.44%   |
| 1333    | 48        | 5.33%   |
| 2133    | 32        | 3.56%   |
| 3600    | 31        | 3.44%   |
| 4800    | 24        | 2.67%   |
| 4267    | 21        | 2.33%   |
| 6400    | 16        | 1.78%   |
| 1867    | 16        | 1.78%   |
| 1334    | 12        | 1.33%   |
| 2666    | 10        | 1.11%   |
| 3800    | 7         | 0.78%   |
| 3266    | 7         | 0.78%   |
| 3000    | 7         | 0.78%   |
| 1066    | 7         | 0.78%   |
| 2933    | 6         | 0.67%   |
| 1866    | 6         | 0.67%   |
| 667     | 6         | 0.67%   |
| 4266    | 5         | 0.56%   |
| 3666    | 5         | 0.56%   |
| Unknown | 5         | 0.56%   |
| 3066    | 4         | 0.44%   |
| 2800    | 4         | 0.44%   |
| 800     | 4         | 0.44%   |
| 5600    | 3         | 0.33%   |
| 3866    | 3         | 0.33%   |
| 3733    | 3         | 0.33%   |
| 3533    | 3         | 0.33%   |
| 3333    | 3         | 0.33%   |
| 1648    | 3         | 0.33%   |
| 400     | 3         | 0.33%   |
| 8400    | 2         | 0.22%   |
| 6000    | 2         | 0.22%   |
| 5808    | 2         | 0.22%   |
| 4199    | 2         | 0.22%   |
| 4000    | 2         | 0.22%   |
| 3400    | 2         | 0.22%   |
| 2048    | 2         | 0.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 10        | 31.25%  |
| Seiko Epson         | 6         | 18.75%  |
| Canon               | 4         | 12.5%   |
| Brother Industries  | 4         | 12.5%   |
| Samsung Electronics | 2         | 6.25%   |
| Zebra               | 1         | 3.13%   |
| Xerox               | 1         | 3.13%   |
| Prolific Technology | 1         | 3.13%   |
| Kyocera             | 1         | 3.13%   |
| Dymo-CoStar         | 1         | 3.13%   |
| Datamax-O'Neil      | 1         | 3.13%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Seiko Epson L360 Series               | 2         | 6.25%   |
| Seiko Epson L3110 Series              | 2         | 6.25%   |
| Samsung M2070 Series                  | 2         | 6.25%   |
| Brother MFC-J460DW                    | 2         | 6.25%   |
| Zebra Thrmal 2844                     | 1         | 3.13%   |
| Xerox Phaser 3140 and 3155            | 1         | 3.13%   |
| Seiko Epson XP-3100 Series            | 1         | 3.13%   |
| Seiko Epson ET-2700 Series            | 1         | 3.13%   |
| Prolific PL2305 Parallel Port         | 1         | 3.13%   |
| Kyocera Mita FS-820                   | 1         | 3.13%   |
| HP OfficeJet 5500 series              | 1         | 3.13%   |
| HP LaserJet Professional P 1102w      | 1         | 3.13%   |
| HP LaserJet P2015 series              | 1         | 3.13%   |
| HP LaserJet 1022                      | 1         | 3.13%   |
| HP LaserJet 1012                      | 1         | 3.13%   |
| HP ENVY 4500 series                   | 1         | 3.13%   |
| HP DeskJet D2300                      | 1         | 3.13%   |
| HP DeskJet 3700 series                | 1         | 3.13%   |
| HP DeskJet 3630 series                | 1         | 3.13%   |
| HP ColorLaserJet M253-M254            | 1         | 3.13%   |
| Dymo-CoStar LabelWriter 450           | 1         | 3.13%   |
| Datamax-O'Neil Datamax E-4304         | 1         | 3.13%   |
| Canon PIXMA MX470 Series              | 1         | 3.13%   |
| Canon PIXMA MG5500 Series             | 1         | 3.13%   |
| Canon LaserShot LBP-1120 Printer      | 1         | 3.13%   |
| Canon iP2600 series                   | 1         | 3.13%   |
| Brother PT-P700 P-touch Label Printer | 1         | 3.13%   |
| Brother HL-2230 series                | 1         | 3.13%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Canon          | 5         | 71.43%  |
| Seiko Epson    | 1         | 14.29%  |
| Mustek Systems | 1         | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40      | 2         | 28.57%  |
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 14.29%  |
| Mustek Systems ScanExpress A3 USB 1200 PRO  | 1         | 14.29%  |
| Canon CanoScan N670U/N676U/LiDE 20          | 1         | 14.29%  |
| Canon CanoScan LiDE 220                     | 1         | 14.29%  |
| Canon CanoScan LiDE 210                     | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 162       | 18.97%  |
| IMC Networks                           | 84        | 9.84%   |
| Microdia                               | 83        | 9.72%   |
| Logitech                               | 73        | 8.55%   |
| Quanta                                 | 57        | 6.67%   |
| Realtek Semiconductor                  | 54        | 6.32%   |
| Bison Electronics                      | 48        | 5.62%   |
| Sunplus Innovation Technology          | 43        | 5.04%   |
| Cheng Uei Precision Industry (Foxlink) | 30        | 3.51%   |
| Acer                                   | 28        | 3.28%   |
| Luxvisions Innotech Limited            | 21        | 2.46%   |
| Syntek                                 | 18        | 2.11%   |
| Apple                                  | 15        | 1.76%   |
| Lite-On Technology                     | 12        | 1.41%   |
| Suyin                                  | 9         | 1.05%   |
| Silicon Motion                         | 8         | 0.94%   |
| Samsung Electronics                    | 8         | 0.94%   |
| Microsoft                              | 8         | 0.94%   |
| Generalplus Technology                 | 7         | 0.82%   |
| Y Media                                | 5         | 0.59%   |
| USB Camera                             | 5         | 0.59%   |
| Sonix Technology                       | 5         | 0.59%   |
| Alcor Micro                            | 5         | 0.59%   |
| SunplusIT                              | 4         | 0.47%   |
| KYE Systems (Mouse Systems)            | 4         | 0.47%   |
| Z-Star Microelectronics                | 3         | 0.35%   |
| ShineTech                              | 3         | 0.35%   |
| GEMBIRD                                | 3         | 0.35%   |
| Cubeternet                             | 3         | 0.35%   |
| ARC International                      | 3         | 0.35%   |
| YGTek                                  | 2         | 0.23%   |
| Unknown                                | 2         | 0.23%   |
| Trust                                  | 2         | 0.23%   |
| Ricoh                                  | 2         | 0.23%   |
| Primax Electronics                     | 2         | 0.23%   |
| MacroSilicon                           | 2         | 0.23%   |
| LG Electronics                         | 2         | 0.23%   |
| Lenovo                                 | 2         | 0.23%   |
| Jieli Technology                       | 2         | 0.23%   |
| Importek                               | 2         | 0.23%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 45        | 5.24%   |
| Microdia Integrated_Webcam_HD                                   | 37        | 4.31%   |
| IMC Networks Integrated Camera                                  | 31        | 3.61%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 21        | 2.44%   |
| Bison Integrated Camera                                         | 21        | 2.44%   |
| Realtek Integrated_Webcam_HD                                    | 20        | 2.33%   |
| Logitech HD Pro Webcam C920                                     | 15        | 1.75%   |
| Chicony HD Webcam                                               | 15        | 1.75%   |
| Chicony HD User Facing                                          | 15        | 1.75%   |
| Sunplus Integrated_Webcam_HD                                    | 14        | 1.63%   |
| Logitech Webcam C270                                            | 14        | 1.63%   |
| Syntek Integrated Camera                                        | 12        | 1.4%    |
| Quanta HP TrueVision HD Camera                                  | 11        | 1.28%   |
| Microdia Integrated_Webcam_FHD                                  | 11        | 1.28%   |
| Chicony HP HD Camera                                            | 11        | 1.28%   |
| Quanta HD User Facing                                           | 10        | 1.16%   |
| Realtek USB Camera                                              | 9         | 1.05%   |
| Microdia Webcam Vitade AF                                       | 9         | 1.05%   |
| Bison BisonCam,NB Pro                                           | 9         | 1.05%   |
| Acer Integrated Camera                                          | 9         | 1.05%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 8         | 0.93%   |
| Chicony Integrated Camera (1280x720@30)                         | 8         | 0.93%   |
| Apple FaceTime HD Camera (Built-in)                             | 8         | 0.93%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 7         | 0.81%   |
| Logitech C922 Pro Stream Webcam                                 | 7         | 0.81%   |
| IMC Networks HD Camera                                          | 7         | 0.81%   |
| Quanta HP Wide Vision HD Camera                                 | 6         | 0.7%    |
| Quanta HP HD Camera                                             | 6         | 0.7%    |
| Chicony USB2.0 Camera                                           | 6         | 0.7%    |
| Chicony HP Wide Vision HD Camera                                | 6         | 0.7%    |
| Chicony HP TrueVision HD                                        | 6         | 0.7%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 6         | 0.7%    |
| Acer HD Webcam                                                  | 6         | 0.7%    |
| Y Media USB Camera                                              | 5         | 0.58%   |
| USB Camera USB Camera                                           | 5         | 0.58%   |
| Quanta ACER HD User Facing                                      | 5         | 0.58%   |
| Luxvisions Innotech Limited Integrated Camera                   | 5         | 0.58%   |
| Logitech C920 PRO HD Webcam                                     | 5         | 0.58%   |
| Generalplus GENERAL WEBCAM                                      | 5         | 0.58%   |
| Chicony HP TrueVision HD Camera                                 | 5         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 51        | 30.72%  |
| Validity Sensors                   | 42        | 25.3%   |
| Shenzhen Goodix Technology         | 40        | 24.1%   |
| Elan Microelectronics              | 14        | 8.43%   |
| AuthenTec                          | 6         | 3.61%   |
| Upek                               | 5         | 3.01%   |
| LighTuning Technology              | 4         | 2.41%   |
| STMicroelectronics                 | 1         | 0.6%    |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.6%    |
| Focal-systems.Corp                 | 1         | 0.6%    |
| Dell                               | 1         | 0.6%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 31        | 18.67%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 14        | 8.43%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 9         | 5.42%   |
| Elan ELAN:ARM-M4                                                           | 9         | 5.42%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 7         | 4.22%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 4.22%   |
| Shenzhen Goodix Fingerprint Reader                                         | 7         | 4.22%   |
| Validity Sensors VFS491                                                    | 6         | 3.61%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 3.01%   |
| Synaptics WBDI                                                             | 5         | 3.01%   |
| Synaptics UWP WBDI                                                         | 5         | 3.01%   |
| Elan ELAN:Fingerprint                                                      | 5         | 3.01%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 2.41%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 2.41%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 1.81%   |
| Synaptics UWP WBDI Device                                                  | 3         | 1.81%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 1.81%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 1.81%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 1.2%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.2%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 1.2%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 1.2%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.2%    |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 1.2%    |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 2         | 1.2%    |
| Synaptics  WBDI                                                            | 2         | 1.2%    |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 1.2%    |
| Shenzhen Goodix FingerPrint                                                | 2         | 1.2%    |
| AuthenTec AES2810                                                          | 2         | 1.2%    |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.6%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.6%    |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.6%    |
| Synaptics TouchPad                                                         | 1         | 0.6%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.6%    |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.6%    |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.6%    |
| LighTuning Fingerprint Sensor                                              | 1         | 0.6%    |
| LighTuning Fingerprint Reader                                              | 1         | 0.6%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.6%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.6%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 30        | 42.25%  |
| Alcor Micro           | 27        | 38.03%  |
| Upek                  | 4         | 5.63%   |
| OmniKey               | 2         | 2.82%   |
| Bit4id                | 2         | 2.82%   |
| SCM Microsystems      | 1         | 1.41%   |
| O2 Micro              | 1         | 1.41%   |
| Lenovo                | 1         | 1.41%   |
| Gemalto (was Gemplus) | 1         | 1.41%   |
| Clay Logic            | 1         | 1.41%   |
| Advanced Card Systems | 1         | 1.41%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 27        | 38.03%  |
| Broadcom 58200                                                               | 12        | 16.9%   |
| Broadcom 5880                                                                | 9         | 12.68%  |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 7.04%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 5.63%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 5.63%   |
| Bit4id miniLector EVO                                                        | 2         | 2.82%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 1.41%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 1.41%   |
| OmniKey CardMan 1021                                                         | 1         | 1.41%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 1.41%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 1.41%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 1.41%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 1.41%   |
| Advanced Card Systems ACR39U                                                 | 1         | 1.41%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 873       | 67.73%  |
| 1     | 329       | 25.52%  |
| 2     | 74        | 5.74%   |
| 3     | 9         | 0.7%    |
| 4     | 2         | 0.16%   |
| 9     | 1         | 0.08%   |
| 7     | 1         | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 163       | 33.06%  |
| Graphics card            | 74        | 15.01%  |
| Chipcard                 | 63        | 12.78%  |
| Net/wireless             | 58        | 11.76%  |
| Camera                   | 30        | 6.09%   |
| Multimedia controller    | 27        | 5.48%   |
| Unassigned class         | 18        | 3.65%   |
| Bluetooth                | 16        | 3.25%   |
| Sound                    | 11        | 2.23%   |
| Communication controller | 11        | 2.23%   |
| Storage                  | 5         | 1.01%   |
| Storage/ide              | 4         | 0.81%   |
| Network                  | 4         | 0.81%   |
| Net/ethernet             | 3         | 0.61%   |
| Card reader              | 3         | 0.61%   |
| Modem                    | 2         | 0.41%   |
| Dvb card                 | 1         | 0.2%    |

