Linux in Mexico - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Mexico.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Mexico/Desktop/README.md) and [notebooks](/Location/Mexico/Notebook/README.md).

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

Total: 4230

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Toshiba       | Satellite L55-C             | Notebook    | [f32d9dc51a](https://linux-hardware.org/?probe=f32d9dc51a) | Feb 02, 2024 |
| Microsoft     | Surface Pro 4               | Tablet      | [07e24523f9](https://linux-hardware.org/?probe=07e24523f9) | Feb 02, 2024 |
| Foxconn       | 2ADA                        | Desktop     | [e92639ba10](https://linux-hardware.org/?probe=e92639ba10) | Feb 02, 2024 |
| HP            | 158A                        | Desktop     | [1ec6b139ac](https://linux-hardware.org/?probe=1ec6b139ac) | Feb 02, 2024 |
| HP            | Pavilion dv4                | Notebook    | [09400a55bb](https://linux-hardware.org/?probe=09400a55bb) | Feb 01, 2024 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | Notebook    | [4f9b6c7262](https://linux-hardware.org/?probe=4f9b6c7262) | Jan 31, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [f8d19ad525](https://linux-hardware.org/?probe=f8d19ad525) | Jan 31, 2024 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [40f306477e](https://linux-hardware.org/?probe=40f306477e) | Jan 31, 2024 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | Notebook    | [0e068176e4](https://linux-hardware.org/?probe=0e068176e4) | Jan 31, 2024 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [25fe740321](https://linux-hardware.org/?probe=25fe740321) | Jan 30, 2024 |
| Dell          | Inspiron 1545               | Notebook    | [3cffc989aa](https://linux-hardware.org/?probe=3cffc989aa) | Jan 29, 2024 |
| Dell          | Inspiron 1545               | Notebook    | [31ce3ae751](https://linux-hardware.org/?probe=31ce3ae751) | Jan 29, 2024 |
| HUAWEI        | NbDE-WXX9                   | Notebook    | [39f2e4dc9e](https://linux-hardware.org/?probe=39f2e4dc9e) | Jan 29, 2024 |
| HUAWEI        | NbDE-WXX9                   | Notebook    | [bf90b37fe4](https://linux-hardware.org/?probe=bf90b37fe4) | Jan 29, 2024 |
| Biostar       | A68MDE                      | Desktop     | [ab1aaeac91](https://linux-hardware.org/?probe=ab1aaeac91) | Jan 29, 2024 |
| HP            | Laptop 15-da0xxx            | Notebook    | [0001a7672a](https://linux-hardware.org/?probe=0001a7672a) | Jan 29, 2024 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [35b6b0dd05](https://linux-hardware.org/?probe=35b6b0dd05) | Jan 28, 2024 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [67781b5f97](https://linux-hardware.org/?probe=67781b5f97) | Jan 28, 2024 |
| Gigabyte      | A520M DS3H V2               | Desktop     | [507d3e9bbf](https://linux-hardware.org/?probe=507d3e9bbf) | Jan 27, 2024 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [fe40514847](https://linux-hardware.org/?probe=fe40514847) | Jan 27, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [32f526010e](https://linux-hardware.org/?probe=32f526010e) | Jan 27, 2024 |
| VPU Compan... | VWNC71429-S                 | Notebook    | [5f72f42958](https://linux-hardware.org/?probe=5f72f42958) | Jan 27, 2024 |
| Lenovo        | ThinkPad T430s 2356GRS      | Notebook    | [c12736937f](https://linux-hardware.org/?probe=c12736937f) | Jan 26, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [5591f82595](https://linux-hardware.org/?probe=5591f82595) | Jan 26, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [8ac63955c7](https://linux-hardware.org/?probe=8ac63955c7) | Jan 26, 2024 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [7af9e0c4ba](https://linux-hardware.org/?probe=7af9e0c4ba) | Jan 26, 2024 |
| Acer          | Aspire ES1-531              | Notebook    | [7faffb7f83](https://linux-hardware.org/?probe=7faffb7f83) | Jan 25, 2024 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [0786b58816](https://linux-hardware.org/?probe=0786b58816) | Jan 24, 2024 |
| Dell          | OptiPlex 780                | Desktop     | [3c444c1e27](https://linux-hardware.org/?probe=3c444c1e27) | Jan 24, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [0bdecdf839](https://linux-hardware.org/?probe=0bdecdf839) | Jan 24, 2024 |
| Lenovo        | Yoga 330-11IGM 81A6         | Convertible | [551769e726](https://linux-hardware.org/?probe=551769e726) | Jan 24, 2024 |
| ECS           | Iris8                       | Desktop     | [91dd8156df](https://linux-hardware.org/?probe=91dd8156df) | Jan 24, 2024 |
| Dell          | 0KN5W4 A03                  | Desktop     | [4665315883](https://linux-hardware.org/?probe=4665315883) | Jan 23, 2024 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [3361cf9ae9](https://linux-hardware.org/?probe=3361cf9ae9) | Jan 23, 2024 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | Notebook    | [7ea2706c0f](https://linux-hardware.org/?probe=7ea2706c0f) | Jan 23, 2024 |
| Gigabyte      | Z270-Gaming 3               | Desktop     | [3977f0ba53](https://linux-hardware.org/?probe=3977f0ba53) | Jan 23, 2024 |
| HP            | 240 G7 Notebook PC          | Notebook    | [5225ed2250](https://linux-hardware.org/?probe=5225ed2250) | Jan 22, 2024 |
| Dell          | Inspiron 5559               | Notebook    | [a0c06abcbd](https://linux-hardware.org/?probe=a0c06abcbd) | Jan 22, 2024 |
| Lenovo        | ThinkPad T480 20L6S3ED18    | Notebook    | [63d8796a60](https://linux-hardware.org/?probe=63d8796a60) | Jan 20, 2024 |
| Gigabyte      | M68MT-S2                    | Desktop     | [ec13e42e3a](https://linux-hardware.org/?probe=ec13e42e3a) | Jan 20, 2024 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [d166663637](https://linux-hardware.org/?probe=d166663637) | Jan 19, 2024 |
| Lenovo        | G40-80 80E4                 | Notebook    | [d03cd5d338](https://linux-hardware.org/?probe=d03cd5d338) | Jan 19, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [3dfc03f457](https://linux-hardware.org/?probe=3dfc03f457) | Jan 19, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [f3ce87bc3c](https://linux-hardware.org/?probe=f3ce87bc3c) | Jan 19, 2024 |
| Acer          | Aspire F5-573               | Notebook    | [9a2df369e8](https://linux-hardware.org/?probe=9a2df369e8) | Jan 19, 2024 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [048c8842d1](https://linux-hardware.org/?probe=048c8842d1) | Jan 19, 2024 |
| Dell          | 0KN5W4 A03                  | Desktop     | [64f7b3272e](https://linux-hardware.org/?probe=64f7b3272e) | Jan 18, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [832ff6a79d](https://linux-hardware.org/?probe=832ff6a79d) | Jan 16, 2024 |
| Lenovo        | G40-80 80E4                 | Notebook    | [b32403a45f](https://linux-hardware.org/?probe=b32403a45f) | Jan 16, 2024 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | Notebook    | [7398e123b9](https://linux-hardware.org/?probe=7398e123b9) | Jan 16, 2024 |
| Gigabyte      | P31-ES3G                    | Desktop     | [27a87a2fc1](https://linux-hardware.org/?probe=27a87a2fc1) | Jan 16, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [de740b2136](https://linux-hardware.org/?probe=de740b2136) | Jan 15, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [109e11ec26](https://linux-hardware.org/?probe=109e11ec26) | Jan 15, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [e7ff1f64dc](https://linux-hardware.org/?probe=e7ff1f64dc) | Jan 15, 2024 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | Notebook    | [0fee6d88f1](https://linux-hardware.org/?probe=0fee6d88f1) | Jan 15, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [2ce7044dec](https://linux-hardware.org/?probe=2ce7044dec) | Jan 15, 2024 |
| MSI           | A520M-A PRO                 | Desktop     | [37f2fc1ee2](https://linux-hardware.org/?probe=37f2fc1ee2) | Jan 14, 2024 |
| Lenovo        | ThinkPad P15v Gen 1 20TR... | Notebook    | [3382b10d32](https://linux-hardware.org/?probe=3382b10d32) | Jan 14, 2024 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [3b6eae725e](https://linux-hardware.org/?probe=3b6eae725e) | Jan 13, 2024 |
| MSI           | A520M-A PRO                 | Desktop     | [04c5daf912](https://linux-hardware.org/?probe=04c5daf912) | Jan 13, 2024 |
| HP            | 8054                        | Desktop     | [cbd77d8fca](https://linux-hardware.org/?probe=cbd77d8fca) | Jan 12, 2024 |
| ASRock        | H61M-DGS                    | Desktop     | [5b064e0d5c](https://linux-hardware.org/?probe=5b064e0d5c) | Jan 12, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [56c544af3a](https://linux-hardware.org/?probe=56c544af3a) | Jan 12, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [a245d0825c](https://linux-hardware.org/?probe=a245d0825c) | Jan 11, 2024 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [5479dc0213](https://linux-hardware.org/?probe=5479dc0213) | Jan 11, 2024 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [48bddf33da](https://linux-hardware.org/?probe=48bddf33da) | Jan 11, 2024 |
| Dell          | Precision 7720              | Notebook    | [7466090144](https://linux-hardware.org/?probe=7466090144) | Jan 11, 2024 |
| Toshiba       | Satellite A215              | Notebook    | [486dfc11fe](https://linux-hardware.org/?probe=486dfc11fe) | Jan 11, 2024 |
| ASUSTek       | N56JR                       | Notebook    | [513c456753](https://linux-hardware.org/?probe=513c456753) | Jan 11, 2024 |
| Dell          | Inspiron N5110              | Notebook    | [1665424e63](https://linux-hardware.org/?probe=1665424e63) | Jan 10, 2024 |
| Toshiba       | Satellite L845              | Notebook    | [e45e9517b3](https://linux-hardware.org/?probe=e45e9517b3) | Jan 10, 2024 |
| Dell          | Inspiron N5110              | Notebook    | [5e233e08dc](https://linux-hardware.org/?probe=5e233e08dc) | Jan 10, 2024 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [4ec27cc26b](https://linux-hardware.org/?probe=4ec27cc26b) | Jan 10, 2024 |
| Microsoft     | Surface Go 3                | Tablet      | [5aaadf7609](https://linux-hardware.org/?probe=5aaadf7609) | Jan 09, 2024 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [8fde8d2ee6](https://linux-hardware.org/?probe=8fde8d2ee6) | Jan 09, 2024 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [ab9812dca2](https://linux-hardware.org/?probe=ab9812dca2) | Jan 08, 2024 |
| ASUSTek       | Unknown                     | Notebook    | [1a45402238](https://linux-hardware.org/?probe=1a45402238) | Jan 08, 2024 |
| Toshiba       | Satellite L655              | Notebook    | [29fa7bdb5e](https://linux-hardware.org/?probe=29fa7bdb5e) | Jan 08, 2024 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [0fbaacab13](https://linux-hardware.org/?probe=0fbaacab13) | Jan 07, 2024 |
| HP            | 2ABA A01                    | Desktop     | [4272f7e431](https://linux-hardware.org/?probe=4272f7e431) | Jan 07, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [e26a035827](https://linux-hardware.org/?probe=e26a035827) | Jan 07, 2024 |
| Toshiba       | Satellite L55D-B            | Notebook    | [e0358ccedc](https://linux-hardware.org/?probe=e0358ccedc) | Jan 06, 2024 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [42bd246eae](https://linux-hardware.org/?probe=42bd246eae) | Jan 05, 2024 |
| Lenovo        | Win8 STD EM DPK IPG         | All in one  | [492077995d](https://linux-hardware.org/?probe=492077995d) | Jan 05, 2024 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [3f8d3f0aec](https://linux-hardware.org/?probe=3f8d3f0aec) | Jan 04, 2024 |
| Toshiba       | Satellite L635              | Notebook    | [c32ce4ff4d](https://linux-hardware.org/?probe=c32ce4ff4d) | Jan 04, 2024 |
| Acer          | Aspire A315-21              | Notebook    | [7d4f4c0cbc](https://linux-hardware.org/?probe=7d4f4c0cbc) | Jan 04, 2024 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [509d8b972c](https://linux-hardware.org/?probe=509d8b972c) | Jan 03, 2024 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [ab04c74157](https://linux-hardware.org/?probe=ab04c74157) | Jan 02, 2024 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [8250c46efe](https://linux-hardware.org/?probe=8250c46efe) | Jan 02, 2024 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [57cd074cfd](https://linux-hardware.org/?probe=57cd074cfd) | Jan 02, 2024 |
| Lenovo        | Win8 STD EM DPK IPG         | All in one  | [26647a45b1](https://linux-hardware.org/?probe=26647a45b1) | Jan 02, 2024 |
| Apple         | MacBookPro7,1               | Notebook    | [9181cf5581](https://linux-hardware.org/?probe=9181cf5581) | Jan 01, 2024 |
| Dell          | Inspiron 7786               | Convertible | [b495c4c522](https://linux-hardware.org/?probe=b495c4c522) | Jan 01, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [6a6513cf92](https://linux-hardware.org/?probe=6a6513cf92) | Jan 01, 2024 |
| HP            | 8054                        | Desktop     | [5389720de6](https://linux-hardware.org/?probe=5389720de6) | Dec 31, 2023 |
| Google        | Blorb                       | Notebook    | [4e0c068a82](https://linux-hardware.org/?probe=4e0c068a82) | Dec 30, 2023 |
| HP            | ENVY m4                     | Notebook    | [6416f24210](https://linux-hardware.org/?probe=6416f24210) | Dec 30, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [394c35d74b](https://linux-hardware.org/?probe=394c35d74b) | Dec 30, 2023 |
| HP            | ENVY m4                     | Notebook    | [f0cd285399](https://linux-hardware.org/?probe=f0cd285399) | Dec 30, 2023 |
| Razer         | Blade                       | Notebook    | [87f8a27b0a](https://linux-hardware.org/?probe=87f8a27b0a) | Dec 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [d5ac5fcf72](https://linux-hardware.org/?probe=d5ac5fcf72) | Dec 29, 2023 |
| Lenovo        | 3000 N500 42333GS           | Notebook    | [523a81b813](https://linux-hardware.org/?probe=523a81b813) | Dec 29, 2023 |
| Lenovo        | SDK0F82990 WIN              | All in one  | [532a81f70f](https://linux-hardware.org/?probe=532a81f70f) | Dec 29, 2023 |
| Acer          | Aspire XC-704               | Desktop     | [37410da8b1](https://linux-hardware.org/?probe=37410da8b1) | Dec 29, 2023 |
| Gateway       | MX3235m                     | Notebook    | [074b414446](https://linux-hardware.org/?probe=074b414446) | Dec 28, 2023 |
| Gateway       | MX3235m                     | Notebook    | [283075fa43](https://linux-hardware.org/?probe=283075fa43) | Dec 28, 2023 |
| ASUSTek       | H81M-A                      | Desktop     | [1676225992](https://linux-hardware.org/?probe=1676225992) | Dec 28, 2023 |
| Dell          | Latitude 3380               | Notebook    | [4f9660f132](https://linux-hardware.org/?probe=4f9660f132) | Dec 28, 2023 |
| Dell          | Latitude 3380               | Notebook    | [bb1422b9bd](https://linux-hardware.org/?probe=bb1422b9bd) | Dec 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [341b25443b](https://linux-hardware.org/?probe=341b25443b) | Dec 28, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [82dda49ee8](https://linux-hardware.org/?probe=82dda49ee8) | Dec 27, 2023 |
| NZXT          | N7 B550                     | Desktop     | [2ce2b46a02](https://linux-hardware.org/?probe=2ce2b46a02) | Dec 27, 2023 |
| Lenovo        | IdeaPad S145-14API 81UV     | Notebook    | [bd8145e3db](https://linux-hardware.org/?probe=bd8145e3db) | Dec 27, 2023 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [df9f1cce5b](https://linux-hardware.org/?probe=df9f1cce5b) | Dec 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [626b056720](https://linux-hardware.org/?probe=626b056720) | Dec 27, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | Desktop     | [370753e882](https://linux-hardware.org/?probe=370753e882) | Dec 27, 2023 |
| Apple         | MacBookPro13,1              | Notebook    | [63344458c9](https://linux-hardware.org/?probe=63344458c9) | Dec 26, 2023 |
| ASUSTek       | X550DP                      | Notebook    | [c7758c21ce](https://linux-hardware.org/?probe=c7758c21ce) | Dec 26, 2023 |
| ASUSTek       | X550DP                      | Notebook    | [a456e712b7](https://linux-hardware.org/?probe=a456e712b7) | Dec 26, 2023 |
| HP            | ENVY Notebook               | Notebook    | [6ffaa62d3d](https://linux-hardware.org/?probe=6ffaa62d3d) | Dec 26, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [53e2517636](https://linux-hardware.org/?probe=53e2517636) | Dec 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [34060a7062](https://linux-hardware.org/?probe=34060a7062) | Dec 26, 2023 |
| HP            | Pavilion dm4                | Notebook    | [f077672580](https://linux-hardware.org/?probe=f077672580) | Dec 25, 2023 |
| Apple         | MacBookPro13,1              | Notebook    | [555e444fe5](https://linux-hardware.org/?probe=555e444fe5) | Dec 25, 2023 |
| ASUSTek       | X411UN                      | Notebook    | [c0cf1b362d](https://linux-hardware.org/?probe=c0cf1b362d) | Dec 25, 2023 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [c37a18c186](https://linux-hardware.org/?probe=c37a18c186) | Dec 25, 2023 |
| Dell          | 0D4VY1 A00                  | All in one  | [794c976b9f](https://linux-hardware.org/?probe=794c976b9f) | Dec 25, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [a2d218ac1b](https://linux-hardware.org/?probe=a2d218ac1b) | Dec 24, 2023 |
| HP            | 2ABA A01                    | Desktop     | [dbee4787fa](https://linux-hardware.org/?probe=dbee4787fa) | Dec 24, 2023 |
| Dell          | 0D4VY1 A00                  | All in one  | [2d510640fd](https://linux-hardware.org/?probe=2d510640fd) | Dec 24, 2023 |
| Lenovo        | ThinkPad T400 6474AV5       | Notebook    | [b98f0a2c09](https://linux-hardware.org/?probe=b98f0a2c09) | Dec 24, 2023 |
| Acer          | Aspire 5250                 | Notebook    | [224ca602f3](https://linux-hardware.org/?probe=224ca602f3) | Dec 24, 2023 |
| Gateway       | NV59C                       | Notebook    | [1537866140](https://linux-hardware.org/?probe=1537866140) | Dec 23, 2023 |
| Unknown       | W1415A                      | Notebook    | [f1fbd72c23](https://linux-hardware.org/?probe=f1fbd72c23) | Dec 23, 2023 |
| Gateway       | NV59C                       | Notebook    | [62d62c0a3b](https://linux-hardware.org/?probe=62d62c0a3b) | Dec 22, 2023 |
| HP            | ENVY Notebook               | Notebook    | [ca2e6f9061](https://linux-hardware.org/?probe=ca2e6f9061) | Dec 22, 2023 |
| Google        | Bobba                       | Notebook    | [c0e8038184](https://linux-hardware.org/?probe=c0e8038184) | Dec 22, 2023 |
| Google        | Bobba                       | Notebook    | [c03b219f2e](https://linux-hardware.org/?probe=c03b219f2e) | Dec 22, 2023 |
| Dell          | Inspiron 3541               | Notebook    | [67f350fefc](https://linux-hardware.org/?probe=67f350fefc) | Dec 21, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [119a1632aa](https://linux-hardware.org/?probe=119a1632aa) | Dec 21, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [64131ee7e0](https://linux-hardware.org/?probe=64131ee7e0) | Dec 21, 2023 |
| Dell          | 0C522T A03                  | Desktop     | [7cd9f2379e](https://linux-hardware.org/?probe=7cd9f2379e) | Dec 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [00b16e835d](https://linux-hardware.org/?probe=00b16e835d) | Dec 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [0b6e9c4c26](https://linux-hardware.org/?probe=0b6e9c4c26) | Dec 20, 2023 |
| Dell          | G7 7700                     | Notebook    | [506de63cb5](https://linux-hardware.org/?probe=506de63cb5) | Dec 20, 2023 |
| HP            | 1905                        | Desktop     | [540abb14df](https://linux-hardware.org/?probe=540abb14df) | Dec 20, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [ca0eab5d48](https://linux-hardware.org/?probe=ca0eab5d48) | Dec 19, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [38ac246006](https://linux-hardware.org/?probe=38ac246006) | Dec 19, 2023 |
| Dell          | 0C522T A03                  | Desktop     | [35b8611349](https://linux-hardware.org/?probe=35b8611349) | Dec 19, 2023 |
| Toshiba       | NB505                       | Notebook    | [7aa351f4c3](https://linux-hardware.org/?probe=7aa351f4c3) | Dec 19, 2023 |
| Toshiba       | NB505                       | Notebook    | [9ed9ded2ea](https://linux-hardware.org/?probe=9ed9ded2ea) | Dec 19, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [19af9254cb](https://linux-hardware.org/?probe=19af9254cb) | Dec 19, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [5881287b44](https://linux-hardware.org/?probe=5881287b44) | Dec 18, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [7383998676](https://linux-hardware.org/?probe=7383998676) | Dec 18, 2023 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [b0526a42f4](https://linux-hardware.org/?probe=b0526a42f4) | Dec 18, 2023 |
| HP            | Compaq CQ45                 | Notebook    | [2d0f39803d](https://linux-hardware.org/?probe=2d0f39803d) | Dec 17, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [39c5fad7d0](https://linux-hardware.org/?probe=39c5fad7d0) | Dec 17, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [d3ff600405](https://linux-hardware.org/?probe=d3ff600405) | Dec 17, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [e85c54f3fd](https://linux-hardware.org/?probe=e85c54f3fd) | Dec 17, 2023 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [e9f2e211bd](https://linux-hardware.org/?probe=e9f2e211bd) | Dec 16, 2023 |
| HP            | G60                         | Notebook    | [9fabfc936c](https://linux-hardware.org/?probe=9fabfc936c) | Dec 16, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [734375c1cc](https://linux-hardware.org/?probe=734375c1cc) | Dec 14, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [3eb792873c](https://linux-hardware.org/?probe=3eb792873c) | Dec 14, 2023 |
| ASUSTek       | Q304UAK                     | Convertible | [7c98d7ffe7](https://linux-hardware.org/?probe=7c98d7ffe7) | Dec 11, 2023 |
| Lenovo        | ThinkCentre M91p 4524CB9    | Desktop     | [1381c72872](https://linux-hardware.org/?probe=1381c72872) | Dec 11, 2023 |
| Dell          | 0C522T A03                  | Desktop     | [11f857231b](https://linux-hardware.org/?probe=11f857231b) | Dec 10, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [67a35f1dd7](https://linux-hardware.org/?probe=67a35f1dd7) | Dec 10, 2023 |
| Gigabyte      | H310M DS2 x.x               | Desktop     | [6150f23143](https://linux-hardware.org/?probe=6150f23143) | Dec 10, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [5a75d4827a](https://linux-hardware.org/?probe=5a75d4827a) | Dec 10, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [d49b26fe0c](https://linux-hardware.org/?probe=d49b26fe0c) | Dec 10, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [f8bd255155](https://linux-hardware.org/?probe=f8bd255155) | Dec 09, 2023 |
| Lenovo        | ThinkCentre M58 7359AW5     | Desktop     | [71d7e25b16](https://linux-hardware.org/?probe=71d7e25b16) | Dec 09, 2023 |
| Dell          | Latitude 3480               | Notebook    | [ee6070cfbe](https://linux-hardware.org/?probe=ee6070cfbe) | Dec 09, 2023 |
| HP            | Compaq 6720s                | Notebook    | [63200c945b](https://linux-hardware.org/?probe=63200c945b) | Dec 08, 2023 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [44e608daff](https://linux-hardware.org/?probe=44e608daff) | Dec 08, 2023 |
| VPU Compan... | VWNC71429-S                 | Notebook    | [c0b0f86403](https://linux-hardware.org/?probe=c0b0f86403) | Dec 07, 2023 |
| Dell          | System Inspiron N4110       | Notebook    | [72874bcc85](https://linux-hardware.org/?probe=72874bcc85) | Dec 07, 2023 |
| MSI           | GF63 Thin 10SC              | Notebook    | [9c8600990d](https://linux-hardware.org/?probe=9c8600990d) | Dec 07, 2023 |
| Valve         | Jupiter                     | Notebook    | [bbb500139e](https://linux-hardware.org/?probe=bbb500139e) | Dec 07, 2023 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [9b36560b08](https://linux-hardware.org/?probe=9b36560b08) | Dec 06, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [747cf33a22](https://linux-hardware.org/?probe=747cf33a22) | Dec 06, 2023 |
| HP            | ENVY Notebook               | Notebook    | [26a4295a68](https://linux-hardware.org/?probe=26a4295a68) | Dec 06, 2023 |
| HP            | 8054                        | Desktop     | [d5e57e23bb](https://linux-hardware.org/?probe=d5e57e23bb) | Dec 06, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [de505ab1fd](https://linux-hardware.org/?probe=de505ab1fd) | Dec 05, 2023 |
| NEC Infron... | MS-9888 10h                 | Desktop     | [8a1a2b9976](https://linux-hardware.org/?probe=8a1a2b9976) | Dec 05, 2023 |
| Toshiba       | Satellite S75-B             | Notebook    | [dbec4c564e](https://linux-hardware.org/?probe=dbec4c564e) | Dec 05, 2023 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [a2e7a10bdf](https://linux-hardware.org/?probe=a2e7a10bdf) | Dec 05, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [b4efc55410](https://linux-hardware.org/?probe=b4efc55410) | Dec 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [2a17ca7efe](https://linux-hardware.org/?probe=2a17ca7efe) | Dec 05, 2023 |
| Acer          | Aspire A515-55              | Notebook    | [0c467a2af3](https://linux-hardware.org/?probe=0c467a2af3) | Dec 04, 2023 |
| HP            | Laptop 17t-cn200            | Notebook    | [26c356c486](https://linux-hardware.org/?probe=26c356c486) | Dec 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [30c19ab13f](https://linux-hardware.org/?probe=30c19ab13f) | Dec 04, 2023 |
| Lenovo        | Bantry CRB SDK0E50515 ST... | Desktop     | [09d4a641d9](https://linux-hardware.org/?probe=09d4a641d9) | Dec 04, 2023 |
| Gigabyte      | GA-880GM-USB3               | Desktop     | [f4078eb310](https://linux-hardware.org/?probe=f4078eb310) | Dec 04, 2023 |
| HP            | 0AECh D                     | Desktop     | [2a30f0332a](https://linux-hardware.org/?probe=2a30f0332a) | Dec 04, 2023 |
| HP            | 0AECh D                     | Desktop     | [689f0d6876](https://linux-hardware.org/?probe=689f0d6876) | Dec 04, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [b6ccfe856f](https://linux-hardware.org/?probe=b6ccfe856f) | Dec 03, 2023 |
| Gateway       | M-6812M                     | Notebook    | [008f6448dc](https://linux-hardware.org/?probe=008f6448dc) | Dec 03, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [4cb46d807d](https://linux-hardware.org/?probe=4cb46d807d) | Dec 03, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [0c74d4b343](https://linux-hardware.org/?probe=0c74d4b343) | Dec 03, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [c7a7d555a6](https://linux-hardware.org/?probe=c7a7d555a6) | Dec 02, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [4f3cfed57b](https://linux-hardware.org/?probe=4f3cfed57b) | Dec 02, 2023 |
| HP            | Compaq 6910p (GY174UP#AB... | Notebook    | [54f08c139f](https://linux-hardware.org/?probe=54f08c139f) | Dec 02, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [73c15b7e61](https://linux-hardware.org/?probe=73c15b7e61) | Dec 02, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6aff076a55](https://linux-hardware.org/?probe=6aff076a55) | Dec 01, 2023 |
| Toshiba       | Satellite A215              | Notebook    | [dcde3a9390](https://linux-hardware.org/?probe=dcde3a9390) | Dec 01, 2023 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [a12db959e6](https://linux-hardware.org/?probe=a12db959e6) | Nov 30, 2023 |
| Dell          | Latitude 3480               | Notebook    | [f83ad2bb01](https://linux-hardware.org/?probe=f83ad2bb01) | Nov 30, 2023 |
| Dell          | Latitude E6420              | Notebook    | [12b36e0bb9](https://linux-hardware.org/?probe=12b36e0bb9) | Nov 30, 2023 |
| PC Special... | Recoil 16                   | Notebook    | [3dd3569b17](https://linux-hardware.org/?probe=3dd3569b17) | Nov 29, 2023 |
| Lenovo        | SHARKBAY SDK0E50515 STD     | Desktop     | [d87ba8d291](https://linux-hardware.org/?probe=d87ba8d291) | Nov 29, 2023 |
| ASUSTek       | X441NA                      | Notebook    | [6965a13f84](https://linux-hardware.org/?probe=6965a13f84) | Nov 29, 2023 |
| HP            | 859B                        | Desktop     | [fd70c499d1](https://linux-hardware.org/?probe=fd70c499d1) | Nov 28, 2023 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [dd98dacf94](https://linux-hardware.org/?probe=dd98dacf94) | Nov 28, 2023 |
| HP            | 245 G4 Notebook PC          | Notebook    | [ef0bb61d83](https://linux-hardware.org/?probe=ef0bb61d83) | Nov 27, 2023 |
| HP            | 245 G4 Notebook PC          | Notebook    | [4a48fe8985](https://linux-hardware.org/?probe=4a48fe8985) | Nov 27, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [54e171f5dc](https://linux-hardware.org/?probe=54e171f5dc) | Nov 27, 2023 |
| HP            | EliteBook 745 G4            | Notebook    | [c3c18efc38](https://linux-hardware.org/?probe=c3c18efc38) | Nov 27, 2023 |
| HP            | G42                         | Notebook    | [b53c2fe1be](https://linux-hardware.org/?probe=b53c2fe1be) | Nov 27, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [13c14b2399](https://linux-hardware.org/?probe=13c14b2399) | Nov 27, 2023 |
| HP            | EliteBook 745 G4            | Notebook    | [33d8baae78](https://linux-hardware.org/?probe=33d8baae78) | Nov 26, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [9e05915f77](https://linux-hardware.org/?probe=9e05915f77) | Nov 26, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [ff1af2d7d2](https://linux-hardware.org/?probe=ff1af2d7d2) | Nov 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [beca2cade6](https://linux-hardware.org/?probe=beca2cade6) | Nov 26, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [c68a8b3cc0](https://linux-hardware.org/?probe=c68a8b3cc0) | Nov 25, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [e17bdfe79f](https://linux-hardware.org/?probe=e17bdfe79f) | Nov 25, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [5cbdf33238](https://linux-hardware.org/?probe=5cbdf33238) | Nov 25, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [ea0a7aa615](https://linux-hardware.org/?probe=ea0a7aa615) | Nov 24, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | Notebook    | [432ec62dd0](https://linux-hardware.org/?probe=432ec62dd0) | Nov 24, 2023 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [85f5270891](https://linux-hardware.org/?probe=85f5270891) | Nov 23, 2023 |
| Lenovo        | IdeaPad Slim 3 15IAN8 82... | Notebook    | [8b107cb438](https://linux-hardware.org/?probe=8b107cb438) | Nov 23, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [4b2a2cc667](https://linux-hardware.org/?probe=4b2a2cc667) | Nov 23, 2023 |
| HUAWEI        | NbDE-WXX9                   | Notebook    | [c5d9332805](https://linux-hardware.org/?probe=c5d9332805) | Nov 23, 2023 |
| Dell          | Inspiron 5485 2n1           | Convertible | [5317e6d4a5](https://linux-hardware.org/?probe=5317e6d4a5) | Nov 22, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [522acd0620](https://linux-hardware.org/?probe=522acd0620) | Nov 22, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [6b88b81e69](https://linux-hardware.org/?probe=6b88b81e69) | Nov 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [f90c57452a](https://linux-hardware.org/?probe=f90c57452a) | Nov 21, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [928f91a2f4](https://linux-hardware.org/?probe=928f91a2f4) | Nov 20, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [508c867ae8](https://linux-hardware.org/?probe=508c867ae8) | Nov 20, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [7273b32790](https://linux-hardware.org/?probe=7273b32790) | Nov 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [dc2ca2e65b](https://linux-hardware.org/?probe=dc2ca2e65b) | Nov 20, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [e5d2cc7fcd](https://linux-hardware.org/?probe=e5d2cc7fcd) | Nov 19, 2023 |
| Gigabyte      | B360HD3                     | Desktop     | [281c4b4ac5](https://linux-hardware.org/?probe=281c4b4ac5) | Nov 18, 2023 |
| Alienware     | m15 R7 AMD                  | Notebook    | [cc1ff7f9a8](https://linux-hardware.org/?probe=cc1ff7f9a8) | Nov 18, 2023 |
| Dell          | Inspiron 15 3515            | Notebook    | [c526bb7fac](https://linux-hardware.org/?probe=c526bb7fac) | Nov 17, 2023 |
| Dell          | Inspiron 15 3515            | Notebook    | [ea21fd1e60](https://linux-hardware.org/?probe=ea21fd1e60) | Nov 17, 2023 |
| Dell          | Latitude 5520               | Notebook    | [234733a1e4](https://linux-hardware.org/?probe=234733a1e4) | Nov 17, 2023 |
| Acer          | Spin SP313-51N              | Convertible | [93616a8cb1](https://linux-hardware.org/?probe=93616a8cb1) | Nov 17, 2023 |
| Dell          | System XPS L502X            | Notebook    | [33f54ee5dc](https://linux-hardware.org/?probe=33f54ee5dc) | Nov 16, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [3e6ad056d6](https://linux-hardware.org/?probe=3e6ad056d6) | Nov 16, 2023 |
| Dell          | Precision 7520              | Notebook    | [f004d80157](https://linux-hardware.org/?probe=f004d80157) | Nov 16, 2023 |
| ASUSTek       | PRIME B650M-A AX            | Desktop     | [496e69e1e4](https://linux-hardware.org/?probe=496e69e1e4) | Nov 16, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [03c6bfd1ee](https://linux-hardware.org/?probe=03c6bfd1ee) | Nov 15, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [41ae79ffa6](https://linux-hardware.org/?probe=41ae79ffa6) | Nov 15, 2023 |
| HP            | 1408h                       | Desktop     | [b39e21e12c](https://linux-hardware.org/?probe=b39e21e12c) | Nov 15, 2023 |
| HP            | 1408h                       | Desktop     | [0eafe0e468](https://linux-hardware.org/?probe=0eafe0e468) | Nov 15, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [870fedf2eb](https://linux-hardware.org/?probe=870fedf2eb) | Nov 15, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [c5f890cb08](https://linux-hardware.org/?probe=c5f890cb08) | Nov 14, 2023 |
| Dell          | Latitude 7390 2-in-1        | Notebook    | [f92b2d58ec](https://linux-hardware.org/?probe=f92b2d58ec) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [c419dad9b3](https://linux-hardware.org/?probe=c419dad9b3) | Nov 14, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [c505d16c82](https://linux-hardware.org/?probe=c505d16c82) | Nov 14, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [e0349fcb14](https://linux-hardware.org/?probe=e0349fcb14) | Nov 14, 2023 |
| Dell          | 0T10XW A01                  | Desktop     | [f7a8d7d27e](https://linux-hardware.org/?probe=f7a8d7d27e) | Nov 14, 2023 |
| Dell          | 0T10XW A01                  | Desktop     | [149bf90d88](https://linux-hardware.org/?probe=149bf90d88) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [1b4972f4e1](https://linux-hardware.org/?probe=1b4972f4e1) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [9e2ced6a3b](https://linux-hardware.org/?probe=9e2ced6a3b) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [7d0e39fe9f](https://linux-hardware.org/?probe=7d0e39fe9f) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [a6e2f5e7f9](https://linux-hardware.org/?probe=a6e2f5e7f9) | Nov 14, 2023 |
| HP            | 871A                        | Mini pc     | [f9bfe70cef](https://linux-hardware.org/?probe=f9bfe70cef) | Nov 14, 2023 |
| HP            | 871A                        | Mini pc     | [af04867373](https://linux-hardware.org/?probe=af04867373) | Nov 14, 2023 |
| ASUSTek       | X555QG                      | Notebook    | [243bc51d12](https://linux-hardware.org/?probe=243bc51d12) | Nov 14, 2023 |
| Unknown       | Unknown                     | Notebook    | [f9ee628d93](https://linux-hardware.org/?probe=f9ee628d93) | Nov 13, 2023 |
| Lenovo        | 3744 WIN SDK0T76466 3424... | All in one  | [765a9d56c1](https://linux-hardware.org/?probe=765a9d56c1) | Nov 12, 2023 |
| HP            | 09F0h                       | Desktop     | [1c1ab6c56f](https://linux-hardware.org/?probe=1c1ab6c56f) | Nov 12, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [87e3c4fa90](https://linux-hardware.org/?probe=87e3c4fa90) | Nov 12, 2023 |
| Intel         | H61 V1.5                    | Desktop     | [798841e126](https://linux-hardware.org/?probe=798841e126) | Nov 12, 2023 |
| Dell          | 018D1Y A00                  | Desktop     | [4a14d46e6b](https://linux-hardware.org/?probe=4a14d46e6b) | Nov 12, 2023 |
| AZW           | GTR V21                     | Desktop     | [8c7e39a466](https://linux-hardware.org/?probe=8c7e39a466) | Nov 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [1f6282ce11](https://linux-hardware.org/?probe=1f6282ce11) | Nov 12, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [e086a0153d](https://linux-hardware.org/?probe=e086a0153d) | Nov 12, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [d49ee32dd4](https://linux-hardware.org/?probe=d49ee32dd4) | Nov 11, 2023 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [0c76c82295](https://linux-hardware.org/?probe=0c76c82295) | Nov 11, 2023 |
| Acer          | Spin SP513-52N              | Convertible | [cb0ff23750](https://linux-hardware.org/?probe=cb0ff23750) | Nov 11, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [164a2ae911](https://linux-hardware.org/?probe=164a2ae911) | Nov 10, 2023 |
| Dell          | 0TKD84 A02                  | Server      | [accebd9648](https://linux-hardware.org/?probe=accebd9648) | Nov 10, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [71b28a2547](https://linux-hardware.org/?probe=71b28a2547) | Nov 10, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [c2d982c2dd](https://linux-hardware.org/?probe=c2d982c2dd) | Nov 10, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [89417204e0](https://linux-hardware.org/?probe=89417204e0) | Nov 09, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | Notebook    | [4af4346c2a](https://linux-hardware.org/?probe=4af4346c2a) | Nov 09, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | Notebook    | [745cc9650d](https://linux-hardware.org/?probe=745cc9650d) | Nov 08, 2023 |
| Dell          | 0YJMC0 A02                  | Desktop     | [7a1de78213](https://linux-hardware.org/?probe=7a1de78213) | Nov 08, 2023 |
| Dell          | 0YJMC0 A02                  | Desktop     | [57fb2a4f18](https://linux-hardware.org/?probe=57fb2a4f18) | Nov 08, 2023 |
| MACHENIKE     | L16P                        | Notebook    | [c8e67672f3](https://linux-hardware.org/?probe=c8e67672f3) | Nov 08, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [ed339d2cbb](https://linux-hardware.org/?probe=ed339d2cbb) | Nov 08, 2023 |
| Dell          | 0VRCY5 A12                  | Server      | [1bf5a3e96c](https://linux-hardware.org/?probe=1bf5a3e96c) | Nov 08, 2023 |
| Dell          | 0VRCY5 A12                  | Server      | [4c2f5a3ff8](https://linux-hardware.org/?probe=4c2f5a3ff8) | Nov 08, 2023 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [5cfd80c832](https://linux-hardware.org/?probe=5cfd80c832) | Nov 08, 2023 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [675571ef30](https://linux-hardware.org/?probe=675571ef30) | Nov 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [b3df6b76e8](https://linux-hardware.org/?probe=b3df6b76e8) | Nov 08, 2023 |
| Acer          | Aspire ES1-531              | Notebook    | [9fd8344477](https://linux-hardware.org/?probe=9fd8344477) | Nov 07, 2023 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [5cfef4c0b7](https://linux-hardware.org/?probe=5cfef4c0b7) | Nov 06, 2023 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [f1d9fe0bb7](https://linux-hardware.org/?probe=f1d9fe0bb7) | Nov 06, 2023 |
| HP            | 8184 X4                     | Desktop     | [fb7f295b44](https://linux-hardware.org/?probe=fb7f295b44) | Nov 05, 2023 |
| Dell          | 0VNP2H A00                  | Desktop     | [98439489ad](https://linux-hardware.org/?probe=98439489ad) | Nov 05, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [279f1b8b4f](https://linux-hardware.org/?probe=279f1b8b4f) | Nov 05, 2023 |
| American M... | A6                          | Notebook    | [4ff43d7d31](https://linux-hardware.org/?probe=4ff43d7d31) | Nov 04, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [6c0dc28b9f](https://linux-hardware.org/?probe=6c0dc28b9f) | Nov 03, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [239e99c725](https://linux-hardware.org/?probe=239e99c725) | Nov 03, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [97ca7a0bfd](https://linux-hardware.org/?probe=97ca7a0bfd) | Nov 02, 2023 |
| Alienware     | 14                          | Notebook    | [3d3be9ce75](https://linux-hardware.org/?probe=3d3be9ce75) | Nov 01, 2023 |
| Toshiba       | Satellite A215              | Notebook    | [de8e05d9e3](https://linux-hardware.org/?probe=de8e05d9e3) | Nov 01, 2023 |
| Toshiba       | Satellite A215              | Notebook    | [4c2cc71fc2](https://linux-hardware.org/?probe=4c2cc71fc2) | Nov 01, 2023 |
| ONE-NETBOO... | ONE XPLAYER 1002-C          | Notebook    | [b89ceef38d](https://linux-hardware.org/?probe=b89ceef38d) | Nov 01, 2023 |
| Dell          | Latitude 5480               | Notebook    | [1bf5aeba87](https://linux-hardware.org/?probe=1bf5aeba87) | Nov 01, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [d7b08bbbab](https://linux-hardware.org/?probe=d7b08bbbab) | Nov 01, 2023 |
| Toshiba       | Satellite L845              | Notebook    | [90e266bd8e](https://linux-hardware.org/?probe=90e266bd8e) | Oct 31, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [17f4f01635](https://linux-hardware.org/?probe=17f4f01635) | Oct 30, 2023 |
| Lenovo        | B40-45 20394                | Notebook    | [ef45bdcea9](https://linux-hardware.org/?probe=ef45bdcea9) | Oct 28, 2023 |
| HP            | 6360t                       | Notebook    | [d0f94e770b](https://linux-hardware.org/?probe=d0f94e770b) | Oct 28, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [607a31a8ef](https://linux-hardware.org/?probe=607a31a8ef) | Oct 27, 2023 |
| Dell          | Inspiron 3451               | Notebook    | [2c1267e536](https://linux-hardware.org/?probe=2c1267e536) | Oct 27, 2023 |
| HP            | Notebook                    | Notebook    | [b6f188a1fe](https://linux-hardware.org/?probe=b6f188a1fe) | Oct 27, 2023 |
| HP            | 2B0A                        | All in one  | [e60260d9b2](https://linux-hardware.org/?probe=e60260d9b2) | Oct 26, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [303c4197c7](https://linux-hardware.org/?probe=303c4197c7) | Oct 26, 2023 |
| Lenovo        | 30FD NOK                    | Mini pc     | [b0175e5f47](https://linux-hardware.org/?probe=b0175e5f47) | Oct 26, 2023 |
| Lenovo        | 30FD NOK                    | Mini pc     | [cf4098d73b](https://linux-hardware.org/?probe=cf4098d73b) | Oct 26, 2023 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [3273bde56c](https://linux-hardware.org/?probe=3273bde56c) | Oct 25, 2023 |
| ASUSTek       | Leonite2                    | Desktop     | [f2ac570d7b](https://linux-hardware.org/?probe=f2ac570d7b) | Oct 25, 2023 |
| Lenovo        | ThinkPad T480 20L6S29D00    | Notebook    | [b270ca3670](https://linux-hardware.org/?probe=b270ca3670) | Oct 24, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [ed7e1a1932](https://linux-hardware.org/?probe=ed7e1a1932) | Oct 24, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [37be8caf53](https://linux-hardware.org/?probe=37be8caf53) | Oct 23, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [5936f87a0e](https://linux-hardware.org/?probe=5936f87a0e) | Oct 23, 2023 |
| HP            | 83EF                        | Desktop     | [9a8026df67](https://linux-hardware.org/?probe=9a8026df67) | Oct 23, 2023 |
| Acer          | Aspire R3-431T              | Notebook    | [eb6c623c2d](https://linux-hardware.org/?probe=eb6c623c2d) | Oct 23, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [2e4786bb32](https://linux-hardware.org/?probe=2e4786bb32) | Oct 23, 2023 |
| AZW           | SER V1                      | Desktop     | [4262bad6c4](https://linux-hardware.org/?probe=4262bad6c4) | Oct 22, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [fde726622c](https://linux-hardware.org/?probe=fde726622c) | Oct 22, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [116946c81c](https://linux-hardware.org/?probe=116946c81c) | Oct 22, 2023 |
| HP            | Notebook                    | Notebook    | [e8c7b38b1b](https://linux-hardware.org/?probe=e8c7b38b1b) | Oct 21, 2023 |
| Gigabyte      | H370 AORUS GAMING 3-CF      | Desktop     | [1303e88b7c](https://linux-hardware.org/?probe=1303e88b7c) | Oct 21, 2023 |
| Biostar       | B450MH                      | Desktop     | [cc72642215](https://linux-hardware.org/?probe=cc72642215) | Oct 20, 2023 |
| Google        | Pirika                      | Notebook    | [98eea3bc0f](https://linux-hardware.org/?probe=98eea3bc0f) | Oct 20, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [d37e5bc4f2](https://linux-hardware.org/?probe=d37e5bc4f2) | Oct 19, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [8e1cb99809](https://linux-hardware.org/?probe=8e1cb99809) | Oct 19, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [4d4e3d82fd](https://linux-hardware.org/?probe=4d4e3d82fd) | Oct 18, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [a80cd678f2](https://linux-hardware.org/?probe=a80cd678f2) | Oct 18, 2023 |
| Dell          | G7 7790                     | Notebook    | [250d61d6a7](https://linux-hardware.org/?probe=250d61d6a7) | Oct 18, 2023 |
| HP            | 2B29                        | Desktop     | [70d4194832](https://linux-hardware.org/?probe=70d4194832) | Oct 18, 2023 |
| HP            | 2B29                        | Desktop     | [b4da4bf11d](https://linux-hardware.org/?probe=b4da4bf11d) | Oct 18, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [036b6067b8](https://linux-hardware.org/?probe=036b6067b8) | Oct 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [04885ecaa3](https://linux-hardware.org/?probe=04885ecaa3) | Oct 18, 2023 |
| ASUSTek       | X200MA                      | Notebook    | [c1ea75561b](https://linux-hardware.org/?probe=c1ea75561b) | Oct 18, 2023 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [501f7abc3b](https://linux-hardware.org/?probe=501f7abc3b) | Oct 18, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [4593a22b63](https://linux-hardware.org/?probe=4593a22b63) | Oct 18, 2023 |
| AZW           | SER V1                      | Desktop     | [fa5f054ba7](https://linux-hardware.org/?probe=fa5f054ba7) | Oct 17, 2023 |
| AZW           | SER V1                      | Desktop     | [e5c570b755](https://linux-hardware.org/?probe=e5c570b755) | Oct 17, 2023 |
| Google        | Treeya                      | Notebook    | [1cf43225f5](https://linux-hardware.org/?probe=1cf43225f5) | Oct 17, 2023 |
| Google        | Treeya                      | Notebook    | [6f05b84b18](https://linux-hardware.org/?probe=6f05b84b18) | Oct 17, 2023 |
| Unknown       | Intel X79                   | Desktop     | [d2553e6cbd](https://linux-hardware.org/?probe=d2553e6cbd) | Oct 17, 2023 |
| HP            | 630                         | Notebook    | [db6efff83b](https://linux-hardware.org/?probe=db6efff83b) | Oct 16, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [fd91b9ece9](https://linux-hardware.org/?probe=fd91b9ece9) | Oct 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [172cfdcd26](https://linux-hardware.org/?probe=172cfdcd26) | Oct 16, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [5079c96f33](https://linux-hardware.org/?probe=5079c96f33) | Oct 15, 2023 |
| HP            | 339A                        | Desktop     | [188e7d023e](https://linux-hardware.org/?probe=188e7d023e) | Oct 14, 2023 |
| Dell          | Inspiron 5575               | Notebook    | [c50573f4ae](https://linux-hardware.org/?probe=c50573f4ae) | Oct 14, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [df4a5a4722](https://linux-hardware.org/?probe=df4a5a4722) | Oct 14, 2023 |
| Dell          | Inspiron 1318               | Notebook    | [2ac81db219](https://linux-hardware.org/?probe=2ac81db219) | Oct 14, 2023 |
| Timi          | RedmiBook 13 R              | Notebook    | [a39c380c4f](https://linux-hardware.org/?probe=a39c380c4f) | Oct 13, 2023 |
| Sony          | VPCEB15EL                   | Notebook    | [f7a3de3793](https://linux-hardware.org/?probe=f7a3de3793) | Oct 13, 2023 |
| HP            | 8714                        | Desktop     | [1379aae868](https://linux-hardware.org/?probe=1379aae868) | Oct 13, 2023 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | Notebook    | [94e6d9d3cb](https://linux-hardware.org/?probe=94e6d9d3cb) | Oct 13, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [01e717042e](https://linux-hardware.org/?probe=01e717042e) | Oct 13, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [de2f74b12a](https://linux-hardware.org/?probe=de2f74b12a) | Oct 13, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [fb51024b14](https://linux-hardware.org/?probe=fb51024b14) | Oct 13, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [27b7cf72ac](https://linux-hardware.org/?probe=27b7cf72ac) | Oct 13, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [71e899c44a](https://linux-hardware.org/?probe=71e899c44a) | Oct 13, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [89197d184c](https://linux-hardware.org/?probe=89197d184c) | Oct 12, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [365f77219e](https://linux-hardware.org/?probe=365f77219e) | Oct 11, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [d582dc334c](https://linux-hardware.org/?probe=d582dc334c) | Oct 11, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [f53b6f5e53](https://linux-hardware.org/?probe=f53b6f5e53) | Oct 11, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [904d65b1c0](https://linux-hardware.org/?probe=904d65b1c0) | Oct 11, 2023 |
| Dell          | Latitude E6440              | Notebook    | [7471faa299](https://linux-hardware.org/?probe=7471faa299) | Oct 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [7d759c245f](https://linux-hardware.org/?probe=7d759c245f) | Oct 10, 2023 |
| ASUSTek       | H81M-A                      | Desktop     | [38a83d68e5](https://linux-hardware.org/?probe=38a83d68e5) | Oct 09, 2023 |
| Toshiba       | Mobile Intel 4 Series/IC... | Desktop     | [d97f4b5e6f](https://linux-hardware.org/?probe=d97f4b5e6f) | Oct 09, 2023 |
| ASUSTek       | H81M-A                      | Desktop     | [fd663ca7fa](https://linux-hardware.org/?probe=fd663ca7fa) | Oct 09, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [e1ff6e4124](https://linux-hardware.org/?probe=e1ff6e4124) | Oct 08, 2023 |
| HP            | Pavilion g4                 | Notebook    | [83fd464aa8](https://linux-hardware.org/?probe=83fd464aa8) | Oct 08, 2023 |
| HP            | Pavilion g4                 | Notebook    | [035c4dbf68](https://linux-hardware.org/?probe=035c4dbf68) | Oct 08, 2023 |
| Toshiba       | Satellite A305D             | Notebook    | [d2fc1d1762](https://linux-hardware.org/?probe=d2fc1d1762) | Oct 07, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [6bc395bbda](https://linux-hardware.org/?probe=6bc395bbda) | Oct 06, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [2d73d7e286](https://linux-hardware.org/?probe=2d73d7e286) | Oct 06, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [97dca67f82](https://linux-hardware.org/?probe=97dca67f82) | Oct 06, 2023 |
| Thomson       | WWN15I5-8BK1T               | Notebook    | [10ca155743](https://linux-hardware.org/?probe=10ca155743) | Oct 06, 2023 |
| Pegatron      | Benicia                     | Desktop     | [b70dfb3fc8](https://linux-hardware.org/?probe=b70dfb3fc8) | Oct 05, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [9d54872fa1](https://linux-hardware.org/?probe=9d54872fa1) | Oct 05, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [ad0cc18353](https://linux-hardware.org/?probe=ad0cc18353) | Oct 05, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [ef041058aa](https://linux-hardware.org/?probe=ef041058aa) | Oct 05, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [75be134738](https://linux-hardware.org/?probe=75be134738) | Oct 05, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [6be4af5bb3](https://linux-hardware.org/?probe=6be4af5bb3) | Oct 05, 2023 |
| Sony          | VPCEG10EL                   | Notebook    | [1c789caaec](https://linux-hardware.org/?probe=1c789caaec) | Oct 04, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [d2e42707c6](https://linux-hardware.org/?probe=d2e42707c6) | Oct 04, 2023 |
| Dell          | Latitude E6410              | Notebook    | [0b58de80dd](https://linux-hardware.org/?probe=0b58de80dd) | Oct 04, 2023 |
| PCChips       | A51G                        | Desktop     | [307e9880cb](https://linux-hardware.org/?probe=307e9880cb) | Oct 03, 2023 |
| PCChips       | A51G                        | Desktop     | [da68aae4b8](https://linux-hardware.org/?probe=da68aae4b8) | Oct 03, 2023 |
| ASUSTek       | Zenbook UX7602ZM_UX7602Z... | Notebook    | [cc7ba8c1ea](https://linux-hardware.org/?probe=cc7ba8c1ea) | Oct 03, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [cacc534be7](https://linux-hardware.org/?probe=cacc534be7) | Oct 02, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [d91dd7bed6](https://linux-hardware.org/?probe=d91dd7bed6) | Oct 02, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [007bb33fbf](https://linux-hardware.org/?probe=007bb33fbf) | Oct 01, 2023 |
| Toshiba       | Satellite L735              | Notebook    | [c969a72669](https://linux-hardware.org/?probe=c969a72669) | Oct 01, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [4fa536be5c](https://linux-hardware.org/?probe=4fa536be5c) | Oct 01, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [efc04e4b27](https://linux-hardware.org/?probe=efc04e4b27) | Oct 01, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [d17d6d2b70](https://linux-hardware.org/?probe=d17d6d2b70) | Oct 01, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [7eebcdc80b](https://linux-hardware.org/?probe=7eebcdc80b) | Oct 01, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [bee067d5dd](https://linux-hardware.org/?probe=bee067d5dd) | Sep 30, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [3d40d7878a](https://linux-hardware.org/?probe=3d40d7878a) | Sep 30, 2023 |
| Sony          | VPCEG10EL                   | Notebook    | [8271942cc2](https://linux-hardware.org/?probe=8271942cc2) | Sep 30, 2023 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [6f19668c91](https://linux-hardware.org/?probe=6f19668c91) | Sep 29, 2023 |
| Pegatron      | Benicia                     | Desktop     | [840b02e356](https://linux-hardware.org/?probe=840b02e356) | Sep 29, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [da030ed703](https://linux-hardware.org/?probe=da030ed703) | Sep 28, 2023 |
| ASUSTek       | Z97-A-USB31                 | Desktop     | [b7e5fb069c](https://linux-hardware.org/?probe=b7e5fb069c) | Sep 28, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [797275028d](https://linux-hardware.org/?probe=797275028d) | Sep 28, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [6b981869d7](https://linux-hardware.org/?probe=6b981869d7) | Sep 27, 2023 |
| Sony          | VPCEG10EL                   | Notebook    | [7bfbe9b21d](https://linux-hardware.org/?probe=7bfbe9b21d) | Sep 27, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [d47b59c89b](https://linux-hardware.org/?probe=d47b59c89b) | Sep 27, 2023 |
| Toshiba       | dynabook T350/46BW          | Notebook    | [26ffaa1c0f](https://linux-hardware.org/?probe=26ffaa1c0f) | Sep 27, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [0ba9157463](https://linux-hardware.org/?probe=0ba9157463) | Sep 27, 2023 |
| HP            | Pavilion 14                 | Notebook    | [a7589d8c93](https://linux-hardware.org/?probe=a7589d8c93) | Sep 26, 2023 |
| HP            | Pavilion 14                 | Notebook    | [1aed6aba04](https://linux-hardware.org/?probe=1aed6aba04) | Sep 26, 2023 |
| Lenovo        | ThinkPad T460 20FMS0RN1S    | Notebook    | [598d621f0d](https://linux-hardware.org/?probe=598d621f0d) | Sep 26, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [897f671915](https://linux-hardware.org/?probe=897f671915) | Sep 25, 2023 |
| Dell          | Latitude E5470              | Notebook    | [64c20e3e21](https://linux-hardware.org/?probe=64c20e3e21) | Sep 25, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [2af47d0dca](https://linux-hardware.org/?probe=2af47d0dca) | Sep 24, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [93b975d65b](https://linux-hardware.org/?probe=93b975d65b) | Sep 24, 2023 |
| Lenovo        | ThinkPad T440 20B6006DUS    | Notebook    | [4428a91f65](https://linux-hardware.org/?probe=4428a91f65) | Sep 23, 2023 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | Notebook    | [05bf70d208](https://linux-hardware.org/?probe=05bf70d208) | Sep 22, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [312172129f](https://linux-hardware.org/?probe=312172129f) | Sep 22, 2023 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [3a965cb7e3](https://linux-hardware.org/?probe=3a965cb7e3) | Sep 22, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [90c9ffe2e0](https://linux-hardware.org/?probe=90c9ffe2e0) | Sep 22, 2023 |
| Dell          | Inspiron 1464               | Notebook    | [026e1e3391](https://linux-hardware.org/?probe=026e1e3391) | Sep 21, 2023 |
| Valve         | Jupiter                     | Notebook    | [2b2966eb3d](https://linux-hardware.org/?probe=2b2966eb3d) | Sep 21, 2023 |
| Dell          | Inspiron 1464               | Notebook    | [bdb084e4a8](https://linux-hardware.org/?probe=bdb084e4a8) | Sep 20, 2023 |
| Lenovo        | ThinkPad L420 78564ES       | Notebook    | [a6f3af802d](https://linux-hardware.org/?probe=a6f3af802d) | Sep 20, 2023 |
| ASRock        | H55M-LE                     | Desktop     | [6b7e52fd8c](https://linux-hardware.org/?probe=6b7e52fd8c) | Sep 20, 2023 |
| ASRock        | H55M-LE                     | Desktop     | [ceefe742e2](https://linux-hardware.org/?probe=ceefe742e2) | Sep 20, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [43edd5f49f](https://linux-hardware.org/?probe=43edd5f49f) | Sep 20, 2023 |
| ASUSTek       | X453MA                      | Notebook    | [8eacbd2f7a](https://linux-hardware.org/?probe=8eacbd2f7a) | Sep 19, 2023 |
| HP            | ProBook 6475b               | Notebook    | [43c4870e11](https://linux-hardware.org/?probe=43c4870e11) | Sep 19, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [9d59b2b43d](https://linux-hardware.org/?probe=9d59b2b43d) | Sep 19, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [f40bb3790e](https://linux-hardware.org/?probe=f40bb3790e) | Sep 18, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [0a5f29963e](https://linux-hardware.org/?probe=0a5f29963e) | Sep 18, 2023 |
| HP            | Dragonfly Pro               | Notebook    | [0c5d439504](https://linux-hardware.org/?probe=0c5d439504) | Sep 18, 2023 |
| Gigabyte      | Z270-Gaming 3               | Desktop     | [9e795a05f1](https://linux-hardware.org/?probe=9e795a05f1) | Sep 18, 2023 |
| ECS           | VX900-I                     | Desktop     | [0a69c91f6b](https://linux-hardware.org/?probe=0a69c91f6b) | Sep 17, 2023 |
| Dell          | Inspiron 1464               | Notebook    | [9830a0345b](https://linux-hardware.org/?probe=9830a0345b) | Sep 17, 2023 |
| Fanless Mi... | Rev JSL62                   | Mini pc     | [adbe2f1ead](https://linux-hardware.org/?probe=adbe2f1ead) | Sep 17, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [a53b964a47](https://linux-hardware.org/?probe=a53b964a47) | Sep 17, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [648af5d937](https://linux-hardware.org/?probe=648af5d937) | Sep 17, 2023 |
| Dell          | Inspiron 5505               | Notebook    | [cf501dc9f9](https://linux-hardware.org/?probe=cf501dc9f9) | Sep 16, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [c3791ba730](https://linux-hardware.org/?probe=c3791ba730) | Sep 16, 2023 |
| Dell          | Latitude 9330               | Convertible | [622af30925](https://linux-hardware.org/?probe=622af30925) | Sep 16, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b4dcc89eae](https://linux-hardware.org/?probe=b4dcc89eae) | Sep 15, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [c424e240c8](https://linux-hardware.org/?probe=c424e240c8) | Sep 15, 2023 |
| Gigabyte      | A55M-DS2                    | Desktop     | [6bc7d0b74c](https://linux-hardware.org/?probe=6bc7d0b74c) | Sep 15, 2023 |
| A-DATA Tec... | XENIAXe15TI5G11GXELX        | Notebook    | [6c2fdbd791](https://linux-hardware.org/?probe=6c2fdbd791) | Sep 14, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [361c6cb056](https://linux-hardware.org/?probe=361c6cb056) | Sep 14, 2023 |
| Toshiba       | Satellite L735              | Notebook    | [fee724f874](https://linux-hardware.org/?probe=fee724f874) | Sep 14, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [28116ad85d](https://linux-hardware.org/?probe=28116ad85d) | Sep 13, 2023 |
| ASUSTek       | Leonite2                    | Desktop     | [6e387e015f](https://linux-hardware.org/?probe=6e387e015f) | Sep 13, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [4ff9edf944](https://linux-hardware.org/?probe=4ff9edf944) | Sep 12, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [26b3fd07ae](https://linux-hardware.org/?probe=26b3fd07ae) | Sep 12, 2023 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [74914c875f](https://linux-hardware.org/?probe=74914c875f) | Sep 12, 2023 |
| Dell          | Precision 7520              | Notebook    | [803e67f286](https://linux-hardware.org/?probe=803e67f286) | Sep 12, 2023 |
| Dell          | 05XGC8 A01                  | Desktop     | [c09c04e44a](https://linux-hardware.org/?probe=c09c04e44a) | Sep 12, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [92762d264f](https://linux-hardware.org/?probe=92762d264f) | Sep 11, 2023 |
| ASUSTek       | X541UA                      | Notebook    | [a8184365b8](https://linux-hardware.org/?probe=a8184365b8) | Sep 10, 2023 |
| Dell          | 0782GW A00                  | Desktop     | [e763eb02b7](https://linux-hardware.org/?probe=e763eb02b7) | Sep 10, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [8c5abbf5a2](https://linux-hardware.org/?probe=8c5abbf5a2) | Sep 10, 2023 |
| Intel         | DX58SO AAE29331-501         | Desktop     | [26d87ed353](https://linux-hardware.org/?probe=26d87ed353) | Sep 09, 2023 |
| ASUSTek       | G750JW                      | Notebook    | [2e81baa143](https://linux-hardware.org/?probe=2e81baa143) | Sep 09, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [178d6df21a](https://linux-hardware.org/?probe=178d6df21a) | Sep 08, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [c5f5d76ac5](https://linux-hardware.org/?probe=c5f5d76ac5) | Sep 08, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [8a48280ff2](https://linux-hardware.org/?probe=8a48280ff2) | Sep 08, 2023 |
| Unknown       | W1415A                      | Notebook    | [67fc8d5ea8](https://linux-hardware.org/?probe=67fc8d5ea8) | Sep 08, 2023 |
| Google        | Pirika                      | Notebook    | [fc27e22f1c](https://linux-hardware.org/?probe=fc27e22f1c) | Sep 08, 2023 |
| Acer          | Predator PH315-51           | Notebook    | [89e33145c3](https://linux-hardware.org/?probe=89e33145c3) | Sep 08, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [7bdd695dc3](https://linux-hardware.org/?probe=7bdd695dc3) | Sep 07, 2023 |
| Dell          | Latitude 5480               | Notebook    | [166d57f310](https://linux-hardware.org/?probe=166d57f310) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b982251e82](https://linux-hardware.org/?probe=b982251e82) | Sep 07, 2023 |
| Dell          | Latitude E5450              | Notebook    | [a705913b6e](https://linux-hardware.org/?probe=a705913b6e) | Sep 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [a5506bdc30](https://linux-hardware.org/?probe=a5506bdc30) | Sep 07, 2023 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [d9509a0fa0](https://linux-hardware.org/?probe=d9509a0fa0) | Sep 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [c4829899c3](https://linux-hardware.org/?probe=c4829899c3) | Sep 06, 2023 |
| Apple         | MacBookPro13,1              | Notebook    | [54f48be7f6](https://linux-hardware.org/?probe=54f48be7f6) | Sep 06, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [ce6860153d](https://linux-hardware.org/?probe=ce6860153d) | Sep 06, 2023 |
| Google        | Pirika                      | Notebook    | [e05149e1de](https://linux-hardware.org/?probe=e05149e1de) | Sep 06, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [9d5880bc6c](https://linux-hardware.org/?probe=9d5880bc6c) | Sep 06, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [6ffc334cf9](https://linux-hardware.org/?probe=6ffc334cf9) | Sep 06, 2023 |
| Apple         | MacBookPro13,1              | Notebook    | [d6b6455af2](https://linux-hardware.org/?probe=d6b6455af2) | Sep 06, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [3c55d4d55b](https://linux-hardware.org/?probe=3c55d4d55b) | Sep 05, 2023 |
| Acer          | Aspire V3-572P              | Notebook    | [1b021435e8](https://linux-hardware.org/?probe=1b021435e8) | Sep 05, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [ab9c556dc7](https://linux-hardware.org/?probe=ab9c556dc7) | Sep 05, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [893bd8a261](https://linux-hardware.org/?probe=893bd8a261) | Sep 04, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [7f9460a97c](https://linux-hardware.org/?probe=7f9460a97c) | Sep 04, 2023 |
| Dell          | 0GWHMW A00                  | Desktop     | [b02b2cb5f0](https://linux-hardware.org/?probe=b02b2cb5f0) | Sep 04, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [b7d2eae326](https://linux-hardware.org/?probe=b7d2eae326) | Sep 04, 2023 |
| Chuwi         | GemiBook XPro               | Notebook    | [acf39c0e3f](https://linux-hardware.org/?probe=acf39c0e3f) | Sep 04, 2023 |
| Lenovo        | ThinkPad T400 64758S4       | Notebook    | [efcb0a82e1](https://linux-hardware.org/?probe=efcb0a82e1) | Sep 04, 2023 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [6ca26976b6](https://linux-hardware.org/?probe=6ca26976b6) | Sep 04, 2023 |
| HP            | 240 G3                      | Notebook    | [24381b91f7](https://linux-hardware.org/?probe=24381b91f7) | Sep 03, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [6b895a5320](https://linux-hardware.org/?probe=6b895a5320) | Sep 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [9e037b28bc](https://linux-hardware.org/?probe=9e037b28bc) | Sep 03, 2023 |
| eMachines     | EL1852G                     | Desktop     | [e9234028f1](https://linux-hardware.org/?probe=e9234028f1) | Sep 03, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [e05acf231c](https://linux-hardware.org/?probe=e05acf231c) | Sep 03, 2023 |
| Biostar       | A10N-9630E                  | Desktop     | [823a9c1693](https://linux-hardware.org/?probe=823a9c1693) | Sep 03, 2023 |
| ASUSTek       | X540NA                      | Notebook    | [69ccd7d6f2](https://linux-hardware.org/?probe=69ccd7d6f2) | Sep 02, 2023 |
| Intel         | S2600CP G50768-512          | Server      | [f05f130786](https://linux-hardware.org/?probe=f05f130786) | Sep 02, 2023 |
| Lenovo        | ThinkPad L570 20J9S07N00    | Notebook    | [88d1350771](https://linux-hardware.org/?probe=88d1350771) | Sep 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [de36e26c21](https://linux-hardware.org/?probe=de36e26c21) | Sep 01, 2023 |
| Lenovo        | ThinkPad L570 20J9S07N00    | Notebook    | [fe660fb390](https://linux-hardware.org/?probe=fe660fb390) | Sep 01, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [5db10955f8](https://linux-hardware.org/?probe=5db10955f8) | Sep 01, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [57ecd81ed7](https://linux-hardware.org/?probe=57ecd81ed7) | Aug 31, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [ffa39e6acd](https://linux-hardware.org/?probe=ffa39e6acd) | Aug 31, 2023 |
| HP            | 2215                        | Desktop     | [3b3b45d0ce](https://linux-hardware.org/?probe=3b3b45d0ce) | Aug 31, 2023 |
| HP            | 1587h                       | Desktop     | [fe659d3db6](https://linux-hardware.org/?probe=fe659d3db6) | Aug 31, 2023 |
| MSI           | Boston                      | Desktop     | [f43cd6df24](https://linux-hardware.org/?probe=f43cd6df24) | Aug 31, 2023 |
| HP            | ProBook 6460b               | Notebook    | [18deeb6be6](https://linux-hardware.org/?probe=18deeb6be6) | Aug 30, 2023 |
| Dell          | Inspiron 1464               | Notebook    | [1020c99eec](https://linux-hardware.org/?probe=1020c99eec) | Aug 30, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [84f61e2225](https://linux-hardware.org/?probe=84f61e2225) | Aug 30, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [3032b93bc8](https://linux-hardware.org/?probe=3032b93bc8) | Aug 30, 2023 |
| Lenovo        | Yoga 720-13IKB 80X6         | Convertible | [e38546c509](https://linux-hardware.org/?probe=e38546c509) | Aug 30, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [9f2585c0aa](https://linux-hardware.org/?probe=9f2585c0aa) | Aug 29, 2023 |
| Dell          | Inspiron 20 Model 3043      | All in one  | [f44b99ca67](https://linux-hardware.org/?probe=f44b99ca67) | Aug 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [863b7d7901](https://linux-hardware.org/?probe=863b7d7901) | Aug 29, 2023 |
| Intel         | S2600CP G50768-512          | Server      | [eba7f74017](https://linux-hardware.org/?probe=eba7f74017) | Aug 29, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [c3065668c8](https://linux-hardware.org/?probe=c3065668c8) | Aug 29, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [3c4c019ee5](https://linux-hardware.org/?probe=3c4c019ee5) | Aug 28, 2023 |
| Google        | Treeya                      | Notebook    | [396f71a402](https://linux-hardware.org/?probe=396f71a402) | Aug 28, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [cc89933ff1](https://linux-hardware.org/?probe=cc89933ff1) | Aug 28, 2023 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [bdd515fe27](https://linux-hardware.org/?probe=bdd515fe27) | Aug 28, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [89044ad89b](https://linux-hardware.org/?probe=89044ad89b) | Aug 28, 2023 |
| Unknown       | V00                         | Mini pc     | [b63adaac28](https://linux-hardware.org/?probe=b63adaac28) | Aug 27, 2023 |
| Dell          | 0HR330                      | Desktop     | [700643ac0e](https://linux-hardware.org/?probe=700643ac0e) | Aug 27, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [f8a316e74c](https://linux-hardware.org/?probe=f8a316e74c) | Aug 27, 2023 |
| Acer          | Aspire V5-471P              | Notebook    | [fcbacf6769](https://linux-hardware.org/?probe=fcbacf6769) | Aug 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [2bbc495ee5](https://linux-hardware.org/?probe=2bbc495ee5) | Aug 25, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [270cd028cf](https://linux-hardware.org/?probe=270cd028cf) | Aug 25, 2023 |
| Dell          | 0M017G A00                  | Desktop     | [f5e52dc9f9](https://linux-hardware.org/?probe=f5e52dc9f9) | Aug 24, 2023 |
| Dell          | G15 5510                    | Notebook    | [f9e857e751](https://linux-hardware.org/?probe=f9e857e751) | Aug 24, 2023 |
| Gateway       | ZX4800                      | All in one  | [8d9b55b788](https://linux-hardware.org/?probe=8d9b55b788) | Aug 24, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [3898bac5d4](https://linux-hardware.org/?probe=3898bac5d4) | Aug 24, 2023 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [62a1cc3d3b](https://linux-hardware.org/?probe=62a1cc3d3b) | Aug 23, 2023 |
| Gateway       | ZX4800                      | All in one  | [ca5095843f](https://linux-hardware.org/?probe=ca5095843f) | Aug 23, 2023 |
| Google        | Pirika                      | Notebook    | [f0937aba65](https://linux-hardware.org/?probe=f0937aba65) | Aug 23, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [69d3db7d28](https://linux-hardware.org/?probe=69d3db7d28) | Aug 23, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [523acf034e](https://linux-hardware.org/?probe=523acf034e) | Aug 23, 2023 |
| Unknown       | Unknown                     | Notebook    | [176f1e45e9](https://linux-hardware.org/?probe=176f1e45e9) | Aug 22, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [3e831762f2](https://linux-hardware.org/?probe=3e831762f2) | Aug 22, 2023 |
| Dell          | Latitude E6430              | Notebook    | [8125ef4bf1](https://linux-hardware.org/?probe=8125ef4bf1) | Aug 22, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [d63bd363bc](https://linux-hardware.org/?probe=d63bd363bc) | Aug 22, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [ca5348bd31](https://linux-hardware.org/?probe=ca5348bd31) | Aug 22, 2023 |
| GMKtec        | NucBox K2                   | Desktop     | [3cc85b0145](https://linux-hardware.org/?probe=3cc85b0145) | Aug 22, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [55e95b21f1](https://linux-hardware.org/?probe=55e95b21f1) | Aug 22, 2023 |
| Lenovo        | ThinkPad T530 23945ZS       | Notebook    | [07f7243392](https://linux-hardware.org/?probe=07f7243392) | Aug 21, 2023 |
| HP            | 18E7                        | Desktop     | [49957c261d](https://linux-hardware.org/?probe=49957c261d) | Aug 21, 2023 |
| Dell          | Latitude E6430              | Notebook    | [839ae55173](https://linux-hardware.org/?probe=839ae55173) | Aug 21, 2023 |
| Dell          | Latitude E7440              | Notebook    | [edae1bc7d3](https://linux-hardware.org/?probe=edae1bc7d3) | Aug 21, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [ca9423253c](https://linux-hardware.org/?probe=ca9423253c) | Aug 21, 2023 |
| Gigabyte      | MZGLKCP-00                  | Desktop     | [c6f294e543](https://linux-hardware.org/?probe=c6f294e543) | Aug 21, 2023 |
| Gigabyte      | MZGLKCP-00                  | Desktop     | [d6e0b89f34](https://linux-hardware.org/?probe=d6e0b89f34) | Aug 21, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [277050ce29](https://linux-hardware.org/?probe=277050ce29) | Aug 20, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [3c24c755d6](https://linux-hardware.org/?probe=3c24c755d6) | Aug 20, 2023 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [455882ed8d](https://linux-hardware.org/?probe=455882ed8d) | Aug 20, 2023 |
| Dell          | Latitude E6430              | Notebook    | [4fc5a7442a](https://linux-hardware.org/?probe=4fc5a7442a) | Aug 20, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [54c2ded452](https://linux-hardware.org/?probe=54c2ded452) | Aug 19, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [68df495196](https://linux-hardware.org/?probe=68df495196) | Aug 19, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [c3d45a0b50](https://linux-hardware.org/?probe=c3d45a0b50) | Aug 18, 2023 |
| Dell          | 0M017G A00                  | Desktop     | [d480387600](https://linux-hardware.org/?probe=d480387600) | Aug 18, 2023 |
| Dell          | 0YJMC0 A02                  | Desktop     | [f4818214d5](https://linux-hardware.org/?probe=f4818214d5) | Aug 18, 2023 |
| Lenovo        | Rev B 82KU                  | Notebook    | [114345f952](https://linux-hardware.org/?probe=114345f952) | Aug 18, 2023 |
| Lenovo        | S10-3                       | Notebook    | [d1c8fb66ec](https://linux-hardware.org/?probe=d1c8fb66ec) | Aug 18, 2023 |
| Lenovo        | G40-30 80FY                 | Notebook    | [6574b3e96d](https://linux-hardware.org/?probe=6574b3e96d) | Aug 16, 2023 |
| ASUSTek       | Leonite2                    | Desktop     | [439a4ee1fb](https://linux-hardware.org/?probe=439a4ee1fb) | Aug 15, 2023 |
| Dell          | Latitude D630               | Notebook    | [878b00d959](https://linux-hardware.org/?probe=878b00d959) | Aug 15, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [de166e8654](https://linux-hardware.org/?probe=de166e8654) | Aug 15, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [b2f8b7afb0](https://linux-hardware.org/?probe=b2f8b7afb0) | Aug 15, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [876d7e9992](https://linux-hardware.org/?probe=876d7e9992) | Aug 15, 2023 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [0bd04d6cc0](https://linux-hardware.org/?probe=0bd04d6cc0) | Aug 15, 2023 |
| AMI           | INTEL                       | Convertible | [21596eaf06](https://linux-hardware.org/?probe=21596eaf06) | Aug 14, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [da00873a9d](https://linux-hardware.org/?probe=da00873a9d) | Aug 14, 2023 |
| Dell          | Inspiron 3505               | Notebook    | [53717914de](https://linux-hardware.org/?probe=53717914de) | Aug 14, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [da23ffa8ca](https://linux-hardware.org/?probe=da23ffa8ca) | Aug 13, 2023 |
| ASRock        | H55M-LE                     | Desktop     | [3751d5807e](https://linux-hardware.org/?probe=3751d5807e) | Aug 12, 2023 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [4fe6eb4d59](https://linux-hardware.org/?probe=4fe6eb4d59) | Aug 12, 2023 |
| HP            | 0A04h                       | Desktop     | [61b0d9bc15](https://linux-hardware.org/?probe=61b0d9bc15) | Aug 12, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [4d26902a65](https://linux-hardware.org/?probe=4d26902a65) | Aug 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [069bfd618c](https://linux-hardware.org/?probe=069bfd618c) | Aug 11, 2023 |
| Lenovo        | IdeaCentre B320             | Desktop     | [175fb6f041](https://linux-hardware.org/?probe=175fb6f041) | Aug 11, 2023 |
| Biostar       | A10N-8800E                  | Desktop     | [5ccf8e7d00](https://linux-hardware.org/?probe=5ccf8e7d00) | Aug 11, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [d6f18c79f6](https://linux-hardware.org/?probe=d6f18c79f6) | Aug 10, 2023 |
| Dell          | 0MGK50 A01                  | Desktop     | [ac0ed4109e](https://linux-hardware.org/?probe=ac0ed4109e) | Aug 10, 2023 |
| Toshiba       | Satellite L745D             | Notebook    | [9576dab2b0](https://linux-hardware.org/?probe=9576dab2b0) | Aug 09, 2023 |
| Lenovo        | 30C1                        | Desktop     | [dda7ed4e8b](https://linux-hardware.org/?probe=dda7ed4e8b) | Aug 09, 2023 |
| Dell          | Precision 3551              | Notebook    | [a9b776ade0](https://linux-hardware.org/?probe=a9b776ade0) | Aug 09, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [6047747c8f](https://linux-hardware.org/?probe=6047747c8f) | Aug 09, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [8a11b56d79](https://linux-hardware.org/?probe=8a11b56d79) | Aug 09, 2023 |
| ASUSTek       | X455LA                      | Notebook    | [8b60fb0411](https://linux-hardware.org/?probe=8b60fb0411) | Aug 08, 2023 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [7a088aea04](https://linux-hardware.org/?probe=7a088aea04) | Aug 08, 2023 |
| MSI           | B350 GAMING PLUS            | Desktop     | [951597859a](https://linux-hardware.org/?probe=951597859a) | Aug 08, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [3fea8d650e](https://linux-hardware.org/?probe=3fea8d650e) | Aug 08, 2023 |
| ASUSTek       | N550LF                      | Notebook    | [57f7da9570](https://linux-hardware.org/?probe=57f7da9570) | Aug 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [72bb72d2aa](https://linux-hardware.org/?probe=72bb72d2aa) | Aug 08, 2023 |
| System76      | Oryx Pro                    | Notebook    | [c5b97761d3](https://linux-hardware.org/?probe=c5b97761d3) | Aug 07, 2023 |
| HUAWEI        | WRTD-WXX9                   | Notebook    | [dc02eefe63](https://linux-hardware.org/?probe=dc02eefe63) | Aug 06, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [f670b492a9](https://linux-hardware.org/?probe=f670b492a9) | Aug 06, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [0c8aef568d](https://linux-hardware.org/?probe=0c8aef568d) | Aug 06, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [597f8ddaf2](https://linux-hardware.org/?probe=597f8ddaf2) | Aug 06, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [8618a7051f](https://linux-hardware.org/?probe=8618a7051f) | Aug 06, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | Notebook    | [8b6db0bfbb](https://linux-hardware.org/?probe=8b6db0bfbb) | Aug 05, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [32f8bbeff7](https://linux-hardware.org/?probe=32f8bbeff7) | Aug 05, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [ab9328165e](https://linux-hardware.org/?probe=ab9328165e) | Aug 05, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [9f813efccc](https://linux-hardware.org/?probe=9f813efccc) | Aug 05, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [349326315f](https://linux-hardware.org/?probe=349326315f) | Aug 05, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d2d45c853b](https://linux-hardware.org/?probe=d2d45c853b) | Aug 05, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [f18b2ff744](https://linux-hardware.org/?probe=f18b2ff744) | Aug 05, 2023 |
| Gigabyte      | GA-MA69VM-S2                | Desktop     | [197a9b0139](https://linux-hardware.org/?probe=197a9b0139) | Aug 03, 2023 |
| INET          | Z12B                        | Mini pc     | [6acbb961c7](https://linux-hardware.org/?probe=6acbb961c7) | Aug 03, 2023 |
| Dell          | Latitude 5490               | Notebook    | [e93c786075](https://linux-hardware.org/?probe=e93c786075) | Aug 03, 2023 |
| Dell          | Latitude E6440              | Notebook    | [c00884f2cd](https://linux-hardware.org/?probe=c00884f2cd) | Aug 03, 2023 |
| Microsoft     | Surface Pro 7+              | Tablet      | [1a39b68c7f](https://linux-hardware.org/?probe=1a39b68c7f) | Aug 03, 2023 |
| Lenovo        | ThinkPad T450 20BU000QLM    | Notebook    | [610fdfd850](https://linux-hardware.org/?probe=610fdfd850) | Aug 03, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [451bfcf27d](https://linux-hardware.org/?probe=451bfcf27d) | Aug 02, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [cfce53f1a3](https://linux-hardware.org/?probe=cfce53f1a3) | Aug 02, 2023 |
| HUAWEI        | WRTD-WXX9                   | Notebook    | [18396303b8](https://linux-hardware.org/?probe=18396303b8) | Aug 02, 2023 |
| Anbernic      | Win600                      | Notebook    | [6d076e4bc9](https://linux-hardware.org/?probe=6d076e4bc9) | Aug 02, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [6f220fcf23](https://linux-hardware.org/?probe=6f220fcf23) | Aug 01, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [d6c2eae395](https://linux-hardware.org/?probe=d6c2eae395) | Aug 01, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [39774f9f5d](https://linux-hardware.org/?probe=39774f9f5d) | Aug 01, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [1dfc12fc6c](https://linux-hardware.org/?probe=1dfc12fc6c) | Jul 31, 2023 |
| Dell          | 0D8M0M A00                  | Desktop     | [3ac6740883](https://linux-hardware.org/?probe=3ac6740883) | Jul 31, 2023 |
| VPU Compan... | VWNC71429-S                 | Notebook    | [2a21ab7b53](https://linux-hardware.org/?probe=2a21ab7b53) | Jul 31, 2023 |
| Dell          | 0RF705                      | Desktop     | [9370437c75](https://linux-hardware.org/?probe=9370437c75) | Jul 30, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [9d93bef2df](https://linux-hardware.org/?probe=9d93bef2df) | Jul 30, 2023 |
| ASUSTek       | X540NA                      | Notebook    | [68b0d7d1fb](https://linux-hardware.org/?probe=68b0d7d1fb) | Jul 30, 2023 |
| Dell          | 0RF705                      | Desktop     | [fe3118bd3c](https://linux-hardware.org/?probe=fe3118bd3c) | Jul 30, 2023 |
| Biostar       | A320MH                      | Desktop     | [8fbc21fb3e](https://linux-hardware.org/?probe=8fbc21fb3e) | Jul 29, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [c098429c68](https://linux-hardware.org/?probe=c098429c68) | Jul 29, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [fb2ba2d3eb](https://linux-hardware.org/?probe=fb2ba2d3eb) | Jul 29, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [8d3733b439](https://linux-hardware.org/?probe=8d3733b439) | Jul 29, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [28bd5d7d66](https://linux-hardware.org/?probe=28bd5d7d66) | Jul 29, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [dd2b310ecf](https://linux-hardware.org/?probe=dd2b310ecf) | Jul 29, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [b8e059a47d](https://linux-hardware.org/?probe=b8e059a47d) | Jul 29, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [27af99ec54](https://linux-hardware.org/?probe=27af99ec54) | Jul 28, 2023 |
| HP            | 0A04h                       | Desktop     | [aaf7bb9453](https://linux-hardware.org/?probe=aaf7bb9453) | Jul 28, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [4d413cb864](https://linux-hardware.org/?probe=4d413cb864) | Jul 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [e46fa3639e](https://linux-hardware.org/?probe=e46fa3639e) | Jul 27, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [1e0ad64e6f](https://linux-hardware.org/?probe=1e0ad64e6f) | Jul 27, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [01110b1f21](https://linux-hardware.org/?probe=01110b1f21) | Jul 27, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [865315bd06](https://linux-hardware.org/?probe=865315bd06) | Jul 27, 2023 |
| Dell          | Latitude 5530               | Notebook    | [165d2cd3b1](https://linux-hardware.org/?probe=165d2cd3b1) | Jul 27, 2023 |
| ASUSTek       | B250 MINING EXPERT          | Desktop     | [0236b3ce26](https://linux-hardware.org/?probe=0236b3ce26) | Jul 26, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [c950e4d2f9](https://linux-hardware.org/?probe=c950e4d2f9) | Jul 25, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [fb125d5fcb](https://linux-hardware.org/?probe=fb125d5fcb) | Jul 25, 2023 |
| Acer          | Aspire A114-33              | Notebook    | [a8c1a06e1a](https://linux-hardware.org/?probe=a8c1a06e1a) | Jul 25, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [156d74ec26](https://linux-hardware.org/?probe=156d74ec26) | Jul 24, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [d3ba6058c7](https://linux-hardware.org/?probe=d3ba6058c7) | Jul 24, 2023 |
| Biostar       | A68MDE                      | Desktop     | [8ab5498633](https://linux-hardware.org/?probe=8ab5498633) | Jul 24, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | Notebook    | [92c6b0de0c](https://linux-hardware.org/?probe=92c6b0de0c) | Jul 23, 2023 |
| Dell          | Latitude E6400              | Notebook    | [77a598aa4d](https://linux-hardware.org/?probe=77a598aa4d) | Jul 23, 2023 |
| Dell          | 0F373D A00                  | Desktop     | [fd337bb7ab](https://linux-hardware.org/?probe=fd337bb7ab) | Jul 23, 2023 |
| Dell          | 0F373D A00                  | Desktop     | [026854a02c](https://linux-hardware.org/?probe=026854a02c) | Jul 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [28340d4ad4](https://linux-hardware.org/?probe=28340d4ad4) | Jul 23, 2023 |
| HP            | 18E7                        | Desktop     | [1638b42b8b](https://linux-hardware.org/?probe=1638b42b8b) | Jul 23, 2023 |
| HP            | 18E7                        | Desktop     | [909788f739](https://linux-hardware.org/?probe=909788f739) | Jul 23, 2023 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [a6e2f105ed](https://linux-hardware.org/?probe=a6e2f105ed) | Jul 23, 2023 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | Desktop     | [c4890b8f34](https://linux-hardware.org/?probe=c4890b8f34) | Jul 23, 2023 |
| HP            | Pavilion dv2500             | Notebook    | [6e86c0a75b](https://linux-hardware.org/?probe=6e86c0a75b) | Jul 23, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [af255054c3](https://linux-hardware.org/?probe=af255054c3) | Jul 22, 2023 |
| MSI           | Boston                      | Desktop     | [d71010f2a7](https://linux-hardware.org/?probe=d71010f2a7) | Jul 22, 2023 |
| Dell          | Latitude E7450              | Notebook    | [d7a8f0a599](https://linux-hardware.org/?probe=d7a8f0a599) | Jul 22, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [d10701a88b](https://linux-hardware.org/?probe=d10701a88b) | Jul 22, 2023 |
| HP            | Pavilion dv6700             | Notebook    | [aed45c2e40](https://linux-hardware.org/?probe=aed45c2e40) | Jul 21, 2023 |
| HP            | 3048h                       | Desktop     | [1be902df43](https://linux-hardware.org/?probe=1be902df43) | Jul 21, 2023 |
| Acer          | Aspire SW3-013              | Notebook    | [b503fa1044](https://linux-hardware.org/?probe=b503fa1044) | Jul 21, 2023 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [937715a75f](https://linux-hardware.org/?probe=937715a75f) | Jul 20, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [39ea43d323](https://linux-hardware.org/?probe=39ea43d323) | Jul 20, 2023 |
| HP            | 2B26 A01                    | All in one  | [41de8f48f0](https://linux-hardware.org/?probe=41de8f48f0) | Jul 20, 2023 |
| Dell          | Latitude 5420               | Notebook    | [ea97d72c47](https://linux-hardware.org/?probe=ea97d72c47) | Jul 20, 2023 |
| HP            | ENVY Notebook               | Notebook    | [0055da01e2](https://linux-hardware.org/?probe=0055da01e2) | Jul 19, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [d79851836e](https://linux-hardware.org/?probe=d79851836e) | Jul 19, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [c4ab55ea69](https://linux-hardware.org/?probe=c4ab55ea69) | Jul 18, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [666c1c0162](https://linux-hardware.org/?probe=666c1c0162) | Jul 18, 2023 |
| HP            | G42                         | Notebook    | [d42b44461e](https://linux-hardware.org/?probe=d42b44461e) | Jul 18, 2023 |
| HP            | 805A                        | Desktop     | [d4e6fca09f](https://linux-hardware.org/?probe=d4e6fca09f) | Jul 17, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [a83e3b42b3](https://linux-hardware.org/?probe=a83e3b42b3) | Jul 17, 2023 |
| MSI           | GE72MVR 7RG                 | Notebook    | [c1834b63c2](https://linux-hardware.org/?probe=c1834b63c2) | Jul 16, 2023 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [2687ecdde1](https://linux-hardware.org/?probe=2687ecdde1) | Jul 14, 2023 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [ed49c9c5e0](https://linux-hardware.org/?probe=ed49c9c5e0) | Jul 14, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [a63fbcabfb](https://linux-hardware.org/?probe=a63fbcabfb) | Jul 14, 2023 |
| MSI           | MPG Z590 GAMING CARBON W... | Desktop     | [7e1752f29c](https://linux-hardware.org/?probe=7e1752f29c) | Jul 14, 2023 |
| GPU Compan... | GWTC51427                   | Notebook    | [138ef93d27](https://linux-hardware.org/?probe=138ef93d27) | Jul 13, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [1976f92f56](https://linux-hardware.org/?probe=1976f92f56) | Jul 12, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a167d41a74](https://linux-hardware.org/?probe=a167d41a74) | Jul 12, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [dd19bc7fee](https://linux-hardware.org/?probe=dd19bc7fee) | Jul 12, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [3866c4a7ff](https://linux-hardware.org/?probe=3866c4a7ff) | Jul 12, 2023 |
| Lenovo        | ThinkPad L390 Yoga 20NUS... | Convertible | [a1334a7b0f](https://linux-hardware.org/?probe=a1334a7b0f) | Jul 11, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [052461ef4d](https://linux-hardware.org/?probe=052461ef4d) | Jul 11, 2023 |
| HP            | Pavilion g4                 | Notebook    | [6e76f09416](https://linux-hardware.org/?probe=6e76f09416) | Jul 11, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [ea833bb195](https://linux-hardware.org/?probe=ea833bb195) | Jul 11, 2023 |
| ASUSTek       | Zenbook UX562UG_Q508UG      | Convertible | [058522b2ca](https://linux-hardware.org/?probe=058522b2ca) | Jul 11, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [a0fd2eeb7b](https://linux-hardware.org/?probe=a0fd2eeb7b) | Jul 11, 2023 |
| ASRock        | B460M Pro4                  | Desktop     | [c972293107](https://linux-hardware.org/?probe=c972293107) | Jul 10, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [b1b3d1eedc](https://linux-hardware.org/?probe=b1b3d1eedc) | Jul 10, 2023 |
| Acer          | Aspire ES1-511              | Notebook    | [1e7434d3b0](https://linux-hardware.org/?probe=1e7434d3b0) | Jul 10, 2023 |
| ASRock        | N68-VS3 FX                  | Desktop     | [9934022e9b](https://linux-hardware.org/?probe=9934022e9b) | Jul 09, 2023 |
| Dell          | Precision M6700             | Notebook    | [ec5b230e37](https://linux-hardware.org/?probe=ec5b230e37) | Jul 09, 2023 |
| ECS           | A790GXM-AD3                 | Desktop     | [d88aa3d8d1](https://linux-hardware.org/?probe=d88aa3d8d1) | Jul 09, 2023 |
| Sony          | VPCF236FM                   | Notebook    | [21a805fe1d](https://linux-hardware.org/?probe=21a805fe1d) | Jul 08, 2023 |
| Dell          | Inspiron 5565               | Notebook    | [d1df053096](https://linux-hardware.org/?probe=d1df053096) | Jul 08, 2023 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [883185ea85](https://linux-hardware.org/?probe=883185ea85) | Jul 07, 2023 |
| Toshiba       | Satellite L745              | Notebook    | [cda3474ee7](https://linux-hardware.org/?probe=cda3474ee7) | Jul 07, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [905af6686d](https://linux-hardware.org/?probe=905af6686d) | Jul 06, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [8d64c46d1d](https://linux-hardware.org/?probe=8d64c46d1d) | Jul 06, 2023 |
| HP            | 895C                        | Desktop     | [8a7f102530](https://linux-hardware.org/?probe=8a7f102530) | Jul 05, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [e59862f167](https://linux-hardware.org/?probe=e59862f167) | Jul 05, 2023 |
| Lenovo        | C205                        | All in one  | [04e0a62210](https://linux-hardware.org/?probe=04e0a62210) | Jul 05, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [9d57d6a85f](https://linux-hardware.org/?probe=9d57d6a85f) | Jul 05, 2023 |
| Acer          | Aspire V5-472               | Notebook    | [663adbe947](https://linux-hardware.org/?probe=663adbe947) | Jul 05, 2023 |
| Dell          | 0MWYPT A02                  | Desktop     | [bbfc788fae](https://linux-hardware.org/?probe=bbfc788fae) | Jul 05, 2023 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [5e07b39a67](https://linux-hardware.org/?probe=5e07b39a67) | Jul 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [8553179448](https://linux-hardware.org/?probe=8553179448) | Jul 04, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [6ce7d33591](https://linux-hardware.org/?probe=6ce7d33591) | Jul 03, 2023 |
| Lenovo        | Aptio CRB SDK0J40679 WIN... | Mini pc     | [40f510325d](https://linux-hardware.org/?probe=40f510325d) | Jul 02, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [011aa45cc1](https://linux-hardware.org/?probe=011aa45cc1) | Jul 01, 2023 |
| HP            | 550                         | Notebook    | [7681694808](https://linux-hardware.org/?probe=7681694808) | Jul 01, 2023 |
| PCChips       | P17G ECS                    | Desktop     | [c1181f8ae7](https://linux-hardware.org/?probe=c1181f8ae7) | Jul 01, 2023 |
| Dell          | 0YXT71 A00                  | Desktop     | [031599c8b1](https://linux-hardware.org/?probe=031599c8b1) | Jul 01, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [4d4d992cb0](https://linux-hardware.org/?probe=4d4d992cb0) | Jul 01, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [3c3ddffa8b](https://linux-hardware.org/?probe=3c3ddffa8b) | Jul 01, 2023 |
| Lenovo        | ThinkPad L430 246634S       | Notebook    | [5368d4410f](https://linux-hardware.org/?probe=5368d4410f) | Jun 30, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [7c07dbad40](https://linux-hardware.org/?probe=7c07dbad40) | Jun 29, 2023 |
| Alienware     | 17 R4                       | Notebook    | [e7f3110f1f](https://linux-hardware.org/?probe=e7f3110f1f) | Jun 29, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [2f50312c02](https://linux-hardware.org/?probe=2f50312c02) | Jun 29, 2023 |
| Dell          | 0H1TR9 A00                  | All in one  | [b4be8eaa80](https://linux-hardware.org/?probe=b4be8eaa80) | Jun 27, 2023 |
| HP            | Pavilion dv6700             | Notebook    | [182bf6e4a7](https://linux-hardware.org/?probe=182bf6e4a7) | Jun 27, 2023 |
| HP            | Pavilion dv6700             | Notebook    | [c5e6819ca8](https://linux-hardware.org/?probe=c5e6819ca8) | Jun 26, 2023 |
| HP            | 339A                        | Desktop     | [ff38f43250](https://linux-hardware.org/?probe=ff38f43250) | Jun 25, 2023 |
| Lenovo        | ThinkPad T480 20L6S01G00    | Notebook    | [a66d6dba45](https://linux-hardware.org/?probe=a66d6dba45) | Jun 25, 2023 |
| Acer          | AOD270                      | Notebook    | [af596f2c11](https://linux-hardware.org/?probe=af596f2c11) | Jun 24, 2023 |
| Acer          | AOD270                      | Notebook    | [d3204f80d5](https://linux-hardware.org/?probe=d3204f80d5) | Jun 24, 2023 |
| MSI           | GE66 Raider 10SFS           | Notebook    | [683b7b2dc2](https://linux-hardware.org/?probe=683b7b2dc2) | Jun 24, 2023 |
| MSI           | GE66 Raider 10SFS           | Notebook    | [558a5b8a7f](https://linux-hardware.org/?probe=558a5b8a7f) | Jun 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 16IAH7 ... | Notebook    | [ef5eb06f90](https://linux-hardware.org/?probe=ef5eb06f90) | Jun 24, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [44b5bb5453](https://linux-hardware.org/?probe=44b5bb5453) | Jun 23, 2023 |
| Dell          | Latitude E5470              | Notebook    | [e10153b4c9](https://linux-hardware.org/?probe=e10153b4c9) | Jun 23, 2023 |
| Dell          | 0G9322                      | Desktop     | [a742a26282](https://linux-hardware.org/?probe=a742a26282) | Jun 22, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [2e654ead73](https://linux-hardware.org/?probe=2e654ead73) | Jun 21, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [2ebfd9c347](https://linux-hardware.org/?probe=2ebfd9c347) | Jun 21, 2023 |
| Gateway       | ZX4800                      | All in one  | [fbb23975d9](https://linux-hardware.org/?probe=fbb23975d9) | Jun 21, 2023 |
| Gateway       | ZX4800                      | All in one  | [eea8b39580](https://linux-hardware.org/?probe=eea8b39580) | Jun 21, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [696e42eaba](https://linux-hardware.org/?probe=696e42eaba) | Jun 20, 2023 |
| ASUSTek       | TP501UA                     | Notebook    | [e883c61561](https://linux-hardware.org/?probe=e883c61561) | Jun 19, 2023 |
| Gigabyte      | GA-E350N                    | Desktop     | [dc5ab95b15](https://linux-hardware.org/?probe=dc5ab95b15) | Jun 19, 2023 |
| Dell          | Latitude 5531               | Notebook    | [bf22616526](https://linux-hardware.org/?probe=bf22616526) | Jun 18, 2023 |
| HP            | 2B3B                        | All in one  | [5e96206d26](https://linux-hardware.org/?probe=5e96206d26) | Jun 17, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [a2bbc6abd3](https://linux-hardware.org/?probe=a2bbc6abd3) | Jun 17, 2023 |
| MSI           | B360M PRO-VH                | Desktop     | [e628906fc2](https://linux-hardware.org/?probe=e628906fc2) | Jun 16, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [dc892cf2b0](https://linux-hardware.org/?probe=dc892cf2b0) | Jun 16, 2023 |
| Dell          | Latitude E6320              | Notebook    | [f1552f3016](https://linux-hardware.org/?probe=f1552f3016) | Jun 16, 2023 |
| Chuwi         | LarkBook X                  | Notebook    | [1869c3f4dc](https://linux-hardware.org/?probe=1869c3f4dc) | Jun 16, 2023 |
| Chuwi         | LarkBook X                  | Notebook    | [2aed95c237](https://linux-hardware.org/?probe=2aed95c237) | Jun 16, 2023 |
| Dell          | Inspiron 5548               | Notebook    | [547ffd8db7](https://linux-hardware.org/?probe=547ffd8db7) | Jun 16, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [67ed3346c2](https://linux-hardware.org/?probe=67ed3346c2) | Jun 15, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [07f1089ee7](https://linux-hardware.org/?probe=07f1089ee7) | Jun 15, 2023 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [ae9d05ff3a](https://linux-hardware.org/?probe=ae9d05ff3a) | Jun 15, 2023 |
| Acer          | Aspire V5-472               | Notebook    | [58dc632831](https://linux-hardware.org/?probe=58dc632831) | Jun 15, 2023 |
| Lenovo        | ThinkPad T495 20NKS0TG00    | Notebook    | [628c8fb554](https://linux-hardware.org/?probe=628c8fb554) | Jun 15, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [ca0a511cd7](https://linux-hardware.org/?probe=ca0a511cd7) | Jun 14, 2023 |
| HP            | G61                         | Notebook    | [52e962e82d](https://linux-hardware.org/?probe=52e962e82d) | Jun 14, 2023 |
| Dell          | Latitude 5590               | Notebook    | [56f8f9bbaf](https://linux-hardware.org/?probe=56f8f9bbaf) | Jun 14, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [f444f44a49](https://linux-hardware.org/?probe=f444f44a49) | Jun 13, 2023 |
| Gateway       | NE572                       | Notebook    | [771f8d0d63](https://linux-hardware.org/?probe=771f8d0d63) | Jun 13, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [2794a5aa86](https://linux-hardware.org/?probe=2794a5aa86) | Jun 12, 2023 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | Notebook    | [98a4801b23](https://linux-hardware.org/?probe=98a4801b23) | Jun 12, 2023 |
| Toshiba       | Mobile Intel 4 Series/IC... | Desktop     | [45696e1d1b](https://linux-hardware.org/?probe=45696e1d1b) | Jun 12, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [4cf431ecc8](https://linux-hardware.org/?probe=4cf431ecc8) | Jun 12, 2023 |
| ASUSTek       | PRIME B650M-A AX            | Desktop     | [f39a1874f7](https://linux-hardware.org/?probe=f39a1874f7) | Jun 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [2c5f9d83bd](https://linux-hardware.org/?probe=2c5f9d83bd) | Jun 12, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [b31d9c8e55](https://linux-hardware.org/?probe=b31d9c8e55) | Jun 12, 2023 |
| Dell          | Latitude 5590               | Notebook    | [f6347f5d6b](https://linux-hardware.org/?probe=f6347f5d6b) | Jun 11, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [f3a04ea109](https://linux-hardware.org/?probe=f3a04ea109) | Jun 11, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [d9ad875572](https://linux-hardware.org/?probe=d9ad875572) | Jun 11, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [7e6a1fa5ff](https://linux-hardware.org/?probe=7e6a1fa5ff) | Jun 11, 2023 |
| Lenovo        | Legion Slim 7 16IRH8 82Y... | Notebook    | [e9e79a1c3b](https://linux-hardware.org/?probe=e9e79a1c3b) | Jun 11, 2023 |
| HP            | Stream Laptop 11-ah0XX      | Notebook    | [a3e566ad38](https://linux-hardware.org/?probe=a3e566ad38) | Jun 11, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [e3311e26b6](https://linux-hardware.org/?probe=e3311e26b6) | Jun 11, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [03f0e4060e](https://linux-hardware.org/?probe=03f0e4060e) | Jun 10, 2023 |
| Google        | Pirika                      | Notebook    | [67fce0a645](https://linux-hardware.org/?probe=67fce0a645) | Jun 10, 2023 |
| Dell          | Vostro 3560                 | Notebook    | [86f646e00f](https://linux-hardware.org/?probe=86f646e00f) | Jun 10, 2023 |
| Dell          | Vostro 3560                 | Notebook    | [1bb9178df2](https://linux-hardware.org/?probe=1bb9178df2) | Jun 10, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [881d5dc409](https://linux-hardware.org/?probe=881d5dc409) | Jun 09, 2023 |
| Dell          | Inspiron 7348               | Notebook    | [a2bd4ab5b9](https://linux-hardware.org/?probe=a2bd4ab5b9) | Jun 09, 2023 |
| Dell          | 0YXT71 A00                  | Desktop     | [477afe615b](https://linux-hardware.org/?probe=477afe615b) | Jun 09, 2023 |
| Dell          | 0YXT71 A00                  | Desktop     | [463dfa5d83](https://linux-hardware.org/?probe=463dfa5d83) | Jun 09, 2023 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [176b4ca0bb](https://linux-hardware.org/?probe=176b4ca0bb) | Jun 09, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | Notebook    | [a579703f97](https://linux-hardware.org/?probe=a579703f97) | Jun 09, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [c35e22de2b](https://linux-hardware.org/?probe=c35e22de2b) | Jun 09, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [68be9da7f1](https://linux-hardware.org/?probe=68be9da7f1) | Jun 09, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [e28668e147](https://linux-hardware.org/?probe=e28668e147) | Jun 08, 2023 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [5861bc7cef](https://linux-hardware.org/?probe=5861bc7cef) | Jun 08, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [f1100ce875](https://linux-hardware.org/?probe=f1100ce875) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [59ff5486a9](https://linux-hardware.org/?probe=59ff5486a9) | Jun 08, 2023 |
| ASUSTek       | X455LA                      | Notebook    | [583596672d](https://linux-hardware.org/?probe=583596672d) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [3acaedf40f](https://linux-hardware.org/?probe=3acaedf40f) | Jun 08, 2023 |
| Dell          | 0G9322                      | Desktop     | [e81a7f788a](https://linux-hardware.org/?probe=e81a7f788a) | Jun 07, 2023 |
| Gigabyte      | B550 VISION D               | Desktop     | [94cf7f5675](https://linux-hardware.org/?probe=94cf7f5675) | Jun 07, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [99b42755e8](https://linux-hardware.org/?probe=99b42755e8) | Jun 07, 2023 |
| Dell          | Latitude E6400              | Notebook    | [ced90af89e](https://linux-hardware.org/?probe=ced90af89e) | Jun 06, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [a9ea51ea77](https://linux-hardware.org/?probe=a9ea51ea77) | Jun 06, 2023 |
| Lenovo        | ThinkPad W520 427637U       | Notebook    | [1bec07891b](https://linux-hardware.org/?probe=1bec07891b) | Jun 05, 2023 |
| HP            | Pavilion g4                 | Notebook    | [af0c33de44](https://linux-hardware.org/?probe=af0c33de44) | Jun 05, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [bfce53d6f5](https://linux-hardware.org/?probe=bfce53d6f5) | Jun 05, 2023 |
| HP            | 240 G3                      | Notebook    | [475e3e63ef](https://linux-hardware.org/?probe=475e3e63ef) | Jun 05, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [d275c3c00b](https://linux-hardware.org/?probe=d275c3c00b) | Jun 05, 2023 |
| ASUSTek       | H81M-A                      | Desktop     | [9636642e65](https://linux-hardware.org/?probe=9636642e65) | Jun 04, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [9ee7eff678](https://linux-hardware.org/?probe=9ee7eff678) | Jun 04, 2023 |
| MSI           | Boston                      | Desktop     | [95b4d5183d](https://linux-hardware.org/?probe=95b4d5183d) | Jun 04, 2023 |
| Lanix         | AL V9                       | Notebook    | [3bd23fdde7](https://linux-hardware.org/?probe=3bd23fdde7) | Jun 04, 2023 |
| Dell          | 0G9322                      | Desktop     | [a1c5ec8909](https://linux-hardware.org/?probe=a1c5ec8909) | Jun 03, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [e14ab40d68](https://linux-hardware.org/?probe=e14ab40d68) | Jun 03, 2023 |
| ASUSTek       | PRIME B650M-A AX            | Desktop     | [983a81f19e](https://linux-hardware.org/?probe=983a81f19e) | Jun 03, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [8933e1b0ad](https://linux-hardware.org/?probe=8933e1b0ad) | Jun 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [b546b2e7f1](https://linux-hardware.org/?probe=b546b2e7f1) | Jun 02, 2023 |
| Dell          | Latitude E5470              | Notebook    | [daa15a6cb0](https://linux-hardware.org/?probe=daa15a6cb0) | Jun 02, 2023 |
| Dell          | Latitude E5470              | Notebook    | [92d3a8b502](https://linux-hardware.org/?probe=92d3a8b502) | Jun 02, 2023 |
| Dell          | Inspiron N4030              | Notebook    | [1a01fbae46](https://linux-hardware.org/?probe=1a01fbae46) | Jun 02, 2023 |
| Lenovo        | ThinkPad T430 2350BG7       | Notebook    | [29d6e72544](https://linux-hardware.org/?probe=29d6e72544) | Jun 02, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [bc606409ff](https://linux-hardware.org/?probe=bc606409ff) | Jun 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [30a2370d6e](https://linux-hardware.org/?probe=30a2370d6e) | Jun 01, 2023 |
| Acer          | AO756                       | Notebook    | [e135dbe37e](https://linux-hardware.org/?probe=e135dbe37e) | Jun 01, 2023 |
| Lenovo        | ThinkPad L440 20ASA20VLM    | Notebook    | [1d59682589](https://linux-hardware.org/?probe=1d59682589) | Jun 01, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [560680687c](https://linux-hardware.org/?probe=560680687c) | May 31, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [65b03710b2](https://linux-hardware.org/?probe=65b03710b2) | May 31, 2023 |
| Lenovo        | ThinkPad T430 2350BG7       | Notebook    | [a09171afde](https://linux-hardware.org/?probe=a09171afde) | May 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [32ba69494b](https://linux-hardware.org/?probe=32ba69494b) | May 31, 2023 |
| Gigabyte      | GA-E6010N                   | Desktop     | [563074319d](https://linux-hardware.org/?probe=563074319d) | May 31, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [54b872a39b](https://linux-hardware.org/?probe=54b872a39b) | May 31, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [6dbaa9e2ff](https://linux-hardware.org/?probe=6dbaa9e2ff) | May 30, 2023 |
| TPV-INVENT... | 2AC6 A01                    | Desktop     | [1ac394c97c](https://linux-hardware.org/?probe=1ac394c97c) | May 30, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [d2ce08a746](https://linux-hardware.org/?probe=d2ce08a746) | May 30, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | Notebook    | [ed1996aaeb](https://linux-hardware.org/?probe=ed1996aaeb) | May 30, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | Notebook    | [3b8f9077db](https://linux-hardware.org/?probe=3b8f9077db) | May 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [bb05a8a89b](https://linux-hardware.org/?probe=bb05a8a89b) | May 30, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [f23e90acce](https://linux-hardware.org/?probe=f23e90acce) | May 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7816244e1a](https://linux-hardware.org/?probe=7816244e1a) | May 30, 2023 |
| Biostar       | H310MHP                     | Desktop     | [7bfe35481d](https://linux-hardware.org/?probe=7bfe35481d) | May 29, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [6dca0624e2](https://linux-hardware.org/?probe=6dca0624e2) | May 29, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [fc839b0b6f](https://linux-hardware.org/?probe=fc839b0b6f) | May 29, 2023 |
| Biostar       | H310MHP                     | Desktop     | [7138f287c8](https://linux-hardware.org/?probe=7138f287c8) | May 29, 2023 |
| HP            | Compaq 6910p (GY174UP#AB... | Notebook    | [43ee52e798](https://linux-hardware.org/?probe=43ee52e798) | May 28, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [412b42ae92](https://linux-hardware.org/?probe=412b42ae92) | May 28, 2023 |
| HP            | Mini 110-3700               | Notebook    | [0f9528a8d2](https://linux-hardware.org/?probe=0f9528a8d2) | May 28, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [cc1c8b2941](https://linux-hardware.org/?probe=cc1c8b2941) | May 28, 2023 |
| ASUSTek       | H81M-A                      | Desktop     | [70714d71f5](https://linux-hardware.org/?probe=70714d71f5) | May 28, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [3f6fc3ec0c](https://linux-hardware.org/?probe=3f6fc3ec0c) | May 27, 2023 |
| PCChips       | P17G ECS                    | Desktop     | [0518fce589](https://linux-hardware.org/?probe=0518fce589) | May 27, 2023 |
| Dell          | 0G9322                      | Desktop     | [4d1450ba3a](https://linux-hardware.org/?probe=4d1450ba3a) | May 27, 2023 |
| Biostar       | A10N-8800E                  | Desktop     | [6b8c135c5d](https://linux-hardware.org/?probe=6b8c135c5d) | May 27, 2023 |
| HP            | 1497                        | Desktop     | [94f79f2f74](https://linux-hardware.org/?probe=94f79f2f74) | May 27, 2023 |
| Dell          | 0G9322                      | Desktop     | [d742ccb0c4](https://linux-hardware.org/?probe=d742ccb0c4) | May 27, 2023 |
| HP            | 1497                        | Desktop     | [d2cca6c2a1](https://linux-hardware.org/?probe=d2cca6c2a1) | May 27, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [3715c09ad3](https://linux-hardware.org/?probe=3715c09ad3) | May 27, 2023 |
| HP            | 895C                        | Desktop     | [f0986c3613](https://linux-hardware.org/?probe=f0986c3613) | May 26, 2023 |
| HP            | 2B3B                        | All in one  | [7819836b92](https://linux-hardware.org/?probe=7819836b92) | May 26, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [df5ea78282](https://linux-hardware.org/?probe=df5ea78282) | May 25, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [45ac56e70c](https://linux-hardware.org/?probe=45ac56e70c) | May 25, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [922428b203](https://linux-hardware.org/?probe=922428b203) | May 25, 2023 |
| Dell          | Latitude E5470              | Notebook    | [6054d2ee2b](https://linux-hardware.org/?probe=6054d2ee2b) | May 25, 2023 |
| Apple         | MacBookPro6,1               | Notebook    | [c8eb2c32b3](https://linux-hardware.org/?probe=c8eb2c32b3) | May 25, 2023 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [edfd6dd6d9](https://linux-hardware.org/?probe=edfd6dd6d9) | May 24, 2023 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [43cf78743a](https://linux-hardware.org/?probe=43cf78743a) | May 24, 2023 |
| Apple         | MacBookPro6,1               | Notebook    | [a8da820b95](https://linux-hardware.org/?probe=a8da820b95) | May 24, 2023 |
| Dell          | Inspiron 5548               | Notebook    | [5665ccbc0a](https://linux-hardware.org/?probe=5665ccbc0a) | May 23, 2023 |
| Toshiba       | Satellite C645D             | Notebook    | [97abd98fdd](https://linux-hardware.org/?probe=97abd98fdd) | May 23, 2023 |
| MSI           | GF65 Thin 9SE               | Notebook    | [c485674a13](https://linux-hardware.org/?probe=c485674a13) | May 23, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [e9c0ee4659](https://linux-hardware.org/?probe=e9c0ee4659) | May 23, 2023 |
| HP            | Pavilion dm4                | Notebook    | [81f264e4ef](https://linux-hardware.org/?probe=81f264e4ef) | May 22, 2023 |
| HP            | Pavilion dm4                | Notebook    | [1f1a9e3f62](https://linux-hardware.org/?probe=1f1a9e3f62) | May 22, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ab21a2a608](https://linux-hardware.org/?probe=ab21a2a608) | May 22, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [a4b0d5fd13](https://linux-hardware.org/?probe=a4b0d5fd13) | May 22, 2023 |
| HP            | Pavilion dm4                | Notebook    | [e25186a486](https://linux-hardware.org/?probe=e25186a486) | May 22, 2023 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [e3ea42dd02](https://linux-hardware.org/?probe=e3ea42dd02) | May 22, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [2ae04bd0d4](https://linux-hardware.org/?probe=2ae04bd0d4) | May 21, 2023 |
| HP            | 2B3B                        | All in one  | [2ed92e9c21](https://linux-hardware.org/?probe=2ed92e9c21) | May 21, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [b2c9a1cd71](https://linux-hardware.org/?probe=b2c9a1cd71) | May 21, 2023 |
| Lenovo        | ThinkPad W530 24382LU       | Notebook    | [908f53f58b](https://linux-hardware.org/?probe=908f53f58b) | May 20, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [c25d920f3d](https://linux-hardware.org/?probe=c25d920f3d) | May 20, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [03c6d7a815](https://linux-hardware.org/?probe=03c6d7a815) | May 19, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [f76ac6d7b5](https://linux-hardware.org/?probe=f76ac6d7b5) | May 19, 2023 |
| Lenovo        | C205                        | All in one  | [16ecd2d81d](https://linux-hardware.org/?probe=16ecd2d81d) | May 19, 2023 |
| Lenovo        | C205                        | All in one  | [dfb0b6c8f3](https://linux-hardware.org/?probe=dfb0b6c8f3) | May 19, 2023 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [916931d01a](https://linux-hardware.org/?probe=916931d01a) | May 19, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C2C... | Notebook    | [a0f983e519](https://linux-hardware.org/?probe=a0f983e519) | May 18, 2023 |
| ASUSTek       | G73Sw                       | Notebook    | [ec9817e3d1](https://linux-hardware.org/?probe=ec9817e3d1) | May 16, 2023 |
| Dell          | Inspiron 20 Model 3043      | All in one  | [2401d72219](https://linux-hardware.org/?probe=2401d72219) | May 16, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [496f6048ec](https://linux-hardware.org/?probe=496f6048ec) | May 15, 2023 |
| Samsung       | R530/R730                   | Notebook    | [d7674fa203](https://linux-hardware.org/?probe=d7674fa203) | May 15, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [2df8fbd5a5](https://linux-hardware.org/?probe=2df8fbd5a5) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [204400bcf7](https://linux-hardware.org/?probe=204400bcf7) | May 13, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [275f194797](https://linux-hardware.org/?probe=275f194797) | May 13, 2023 |
| HP            | 2B3B                        | All in one  | [4785289345](https://linux-hardware.org/?probe=4785289345) | May 13, 2023 |
| ASRock        | H55M-LE                     | Desktop     | [e31e211aa2](https://linux-hardware.org/?probe=e31e211aa2) | May 13, 2023 |
| ASRock        | H55M-LE                     | Desktop     | [8f2f79fb45](https://linux-hardware.org/?probe=8f2f79fb45) | May 13, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [f8c0bd3176](https://linux-hardware.org/?probe=f8c0bd3176) | May 12, 2023 |
| HP            | 2B3B                        | All in one  | [a4c65ac28f](https://linux-hardware.org/?probe=a4c65ac28f) | May 12, 2023 |
| HP            | 2B3B                        | All in one  | [ca83ed5e3f](https://linux-hardware.org/?probe=ca83ed5e3f) | May 12, 2023 |
| HP            | 0A58h                       | Desktop     | [b48452bdd9](https://linux-hardware.org/?probe=b48452bdd9) | May 12, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [ecb43775d1](https://linux-hardware.org/?probe=ecb43775d1) | May 11, 2023 |
| Biostar       | B450MH                      | Desktop     | [e5dac06f4e](https://linux-hardware.org/?probe=e5dac06f4e) | May 11, 2023 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [e644ef3b24](https://linux-hardware.org/?probe=e644ef3b24) | May 11, 2023 |
| Biostar       | B450MH                      | Desktop     | [12659ad2e2](https://linux-hardware.org/?probe=12659ad2e2) | May 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [f02c2abaab](https://linux-hardware.org/?probe=f02c2abaab) | May 11, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [9ff409cce8](https://linux-hardware.org/?probe=9ff409cce8) | May 11, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | Notebook    | [79d149ff5c](https://linux-hardware.org/?probe=79d149ff5c) | May 11, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [e360693145](https://linux-hardware.org/?probe=e360693145) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [b791be35c2](https://linux-hardware.org/?probe=b791be35c2) | May 10, 2023 |
| eMachines     | E625                        | Notebook    | [1271e33078](https://linux-hardware.org/?probe=1271e33078) | May 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [7058baf75d](https://linux-hardware.org/?probe=7058baf75d) | May 10, 2023 |
| eMachines     | E625                        | Notebook    | [3160c872b8](https://linux-hardware.org/?probe=3160c872b8) | May 10, 2023 |
| Lenovo        | ThinkPad T480 20L6S91L00    | Notebook    | [82c3d7dd74](https://linux-hardware.org/?probe=82c3d7dd74) | May 09, 2023 |
| Lanix Amer... | A V19                       | Notebook    | [31e64dbd5d](https://linux-hardware.org/?probe=31e64dbd5d) | May 08, 2023 |
| HP            | 15                          | Notebook    | [fd2af6a225](https://linux-hardware.org/?probe=fd2af6a225) | May 08, 2023 |
| HP            | Laptop 15-da2xxx            | Notebook    | [8f08aa189f](https://linux-hardware.org/?probe=8f08aa189f) | May 08, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [75fe05267b](https://linux-hardware.org/?probe=75fe05267b) | May 08, 2023 |
| AZW           | SER V01                     | Mini pc     | [6097531bfc](https://linux-hardware.org/?probe=6097531bfc) | May 08, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [a8d45ac430](https://linux-hardware.org/?probe=a8d45ac430) | May 07, 2023 |
| Gigabyte      | Z390 I AORUS PRO WIFI-CF    | Desktop     | [dbeb828b17](https://linux-hardware.org/?probe=dbeb828b17) | May 07, 2023 |
| ASUSTek       | Q405UA                      | Convertible | [f8f69fc110](https://linux-hardware.org/?probe=f8f69fc110) | May 06, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [c3ef7b4de9](https://linux-hardware.org/?probe=c3ef7b4de9) | May 06, 2023 |
| HP            | Pavilion g4                 | Notebook    | [55a4a7978e](https://linux-hardware.org/?probe=55a4a7978e) | May 04, 2023 |
| Lenovo        | IdeaPad Yoga 11S 20246      | Notebook    | [fde0845fa4](https://linux-hardware.org/?probe=fde0845fa4) | May 04, 2023 |
| Gigabyte      | H410M H                     | Desktop     | [3e13b2bc4a](https://linux-hardware.org/?probe=3e13b2bc4a) | May 04, 2023 |
| Lenovo        | IdeaPad Yoga 11S 20246      | Notebook    | [1a15177f0a](https://linux-hardware.org/?probe=1a15177f0a) | May 04, 2023 |
| Lenovo        | Yoga 300-11IBY 80M0         | Notebook    | [a4a894bb7a](https://linux-hardware.org/?probe=a4a894bb7a) | May 03, 2023 |
| Dell          | Inspiron 20 Model 3043      | All in one  | [8a25091e19](https://linux-hardware.org/?probe=8a25091e19) | May 03, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [3a9a2590e3](https://linux-hardware.org/?probe=3a9a2590e3) | May 01, 2023 |
| Dell          | 0D6H9T A00                  | Desktop     | [0e46a82cca](https://linux-hardware.org/?probe=0e46a82cca) | May 01, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c2b7a8dbe1](https://linux-hardware.org/?probe=c2b7a8dbe1) | May 01, 2023 |
| Lenovo        | ThinkPad T480 20L6S91L00    | Notebook    | [fe2f2e420f](https://linux-hardware.org/?probe=fe2f2e420f) | May 01, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [0784fc9b1c](https://linux-hardware.org/?probe=0784fc9b1c) | Apr 30, 2023 |
| Dell          | Latitude 5580               | Notebook    | [556abc1561](https://linux-hardware.org/?probe=556abc1561) | Apr 30, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [9c07454907](https://linux-hardware.org/?probe=9c07454907) | Apr 30, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [3056c07eb6](https://linux-hardware.org/?probe=3056c07eb6) | Apr 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [4490476bd2](https://linux-hardware.org/?probe=4490476bd2) | Apr 29, 2023 |
| Gigabyte      | H410M H                     | Desktop     | [3ea3271f4a](https://linux-hardware.org/?probe=3ea3271f4a) | Apr 29, 2023 |
| Biostar       | A10N-9630E                  | Desktop     | [e9df412284](https://linux-hardware.org/?probe=e9df412284) | Apr 28, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [210ceedb6d](https://linux-hardware.org/?probe=210ceedb6d) | Apr 28, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [7aa3832621](https://linux-hardware.org/?probe=7aa3832621) | Apr 28, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [155ce08a00](https://linux-hardware.org/?probe=155ce08a00) | Apr 27, 2023 |
| ASUSTek       | AM1M-A                      | Desktop     | [ab3c4ea199](https://linux-hardware.org/?probe=ab3c4ea199) | Apr 26, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [1fb0741f20](https://linux-hardware.org/?probe=1fb0741f20) | Apr 26, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [f43777b85b](https://linux-hardware.org/?probe=f43777b85b) | Apr 26, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | Desktop     | [07e9099105](https://linux-hardware.org/?probe=07e9099105) | Apr 26, 2023 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [c9ef115a29](https://linux-hardware.org/?probe=c9ef115a29) | Apr 26, 2023 |
| Dell          | 0WR7PY A01                  | Desktop     | [6eeb692185](https://linux-hardware.org/?probe=6eeb692185) | Apr 25, 2023 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [1602540ab8](https://linux-hardware.org/?probe=1602540ab8) | Apr 25, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [93b15a590f](https://linux-hardware.org/?probe=93b15a590f) | Apr 25, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [e05975b1cc](https://linux-hardware.org/?probe=e05975b1cc) | Apr 25, 2023 |
| Dell          | 03FV9K A00                  | Server      | [4d9f06ca7b](https://linux-hardware.org/?probe=4d9f06ca7b) | Apr 24, 2023 |
| DERE          | X16                         | Notebook    | [8c51699ade](https://linux-hardware.org/?probe=8c51699ade) | Apr 23, 2023 |
| HP            | 805D                        | Desktop     | [091e90cae0](https://linux-hardware.org/?probe=091e90cae0) | Apr 23, 2023 |
| Acer          | AOD270                      | Notebook    | [d7d653d3d6](https://linux-hardware.org/?probe=d7d653d3d6) | Apr 23, 2023 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [9f5177c657](https://linux-hardware.org/?probe=9f5177c657) | Apr 23, 2023 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [e263516539](https://linux-hardware.org/?probe=e263516539) | Apr 23, 2023 |
| Toshiba       | Satellite C845              | Notebook    | [8174d09074](https://linux-hardware.org/?probe=8174d09074) | Apr 21, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [880ee85934](https://linux-hardware.org/?probe=880ee85934) | Apr 21, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [7215ce49dd](https://linux-hardware.org/?probe=7215ce49dd) | Apr 21, 2023 |
| Dell          | G15 5510                    | Notebook    | [724945ee92](https://linux-hardware.org/?probe=724945ee92) | Apr 20, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d8025962bf](https://linux-hardware.org/?probe=d8025962bf) | Apr 20, 2023 |
| ASUSTek       | T100TAF                     | Notebook    | [9e59d428d2](https://linux-hardware.org/?probe=9e59d428d2) | Apr 19, 2023 |
| Dell          | 0HR330                      | Desktop     | [1619f09258](https://linux-hardware.org/?probe=1619f09258) | Apr 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [2cb8ecb34d](https://linux-hardware.org/?probe=2cb8ecb34d) | Apr 19, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [33b92210c7](https://linux-hardware.org/?probe=33b92210c7) | Apr 19, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [fe26aeffdd](https://linux-hardware.org/?probe=fe26aeffdd) | Apr 19, 2023 |
| HP            | Unknown                     | Notebook    | [5a295b02bc](https://linux-hardware.org/?probe=5a295b02bc) | Apr 19, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [39057bb60a](https://linux-hardware.org/?probe=39057bb60a) | Apr 18, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [ebfd8fec1b](https://linux-hardware.org/?probe=ebfd8fec1b) | Apr 18, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [28f6e6e6c6](https://linux-hardware.org/?probe=28f6e6e6c6) | Apr 18, 2023 |
| Intel         | DZ68DB AAG27985-105         | Desktop     | [aa030a4054](https://linux-hardware.org/?probe=aa030a4054) | Apr 18, 2023 |
| Gigabyte      | H370 AORUS GAMING 3-CF      | Desktop     | [8b585cf135](https://linux-hardware.org/?probe=8b585cf135) | Apr 18, 2023 |
| HP            | ProBook 645 G1              | Notebook    | [e7d992accf](https://linux-hardware.org/?probe=e7d992accf) | Apr 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [ad381ae6d8](https://linux-hardware.org/?probe=ad381ae6d8) | Apr 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [94f62c41e5](https://linux-hardware.org/?probe=94f62c41e5) | Apr 17, 2023 |
| Gigabyte      | GA-IMB410TN                 | Desktop     | [44293ba6b9](https://linux-hardware.org/?probe=44293ba6b9) | Apr 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [4644eb92ef](https://linux-hardware.org/?probe=4644eb92ef) | Apr 17, 2023 |
| Gigabyte      | GA-IMB410TN                 | Desktop     | [983906ed11](https://linux-hardware.org/?probe=983906ed11) | Apr 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [52e4ec34e1](https://linux-hardware.org/?probe=52e4ec34e1) | Apr 16, 2023 |
| HP            | 1850                        | Desktop     | [9ba17e1d9c](https://linux-hardware.org/?probe=9ba17e1d9c) | Apr 16, 2023 |
| Biostar       | A10N-8800E                  | Desktop     | [31557d5e8c](https://linux-hardware.org/?probe=31557d5e8c) | Apr 15, 2023 |
| HP            | 1850                        | Desktop     | [d30cea781b](https://linux-hardware.org/?probe=d30cea781b) | Apr 15, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Mexico/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 280       | 9.4%    |
| Ubuntu 22.04       | 196       | 6.58%   |
| Ubuntu 18.04       | 174       | 5.84%   |
| OpenMandriva 4.2   | 93        | 3.12%   |
| OpenMandriva 4.3   | 87        | 2.92%   |
| Debian 11          | 83        | 2.79%   |
| Zorin 16           | 75        | 2.52%   |
| Fedora 38          | 73        | 2.45%   |
| Manjaro            | 55        | 1.85%   |
| KDE neon 20.04     | 51        | 1.71%   |
| Pop!_OS 22.04      | 46        | 1.54%   |
| Linux Mint 20.3    | 46        | 1.54%   |
| Fedora 36          | 43        | 1.44%   |
| ArcoLinux Rolling  | 40        | 1.34%   |
| Arch Rolling       | 39        | 1.31%   |
| Linux Mint 21.2    | 35        | 1.18%   |
| Debian 12          | 35        | 1.18%   |
| OpenMandriva 23.03 | 34        | 1.14%   |
| Arch               | 34        | 1.14%   |
| Pop!_OS 20.04      | 33        | 1.11%   |
| KDE neon 22.04     | 32        | 1.07%   |
| Zorin 15           | 30        | 1.01%   |
| Linux Mint 21.1    | 28        | 0.94%   |
| OpenMandriva 23.08 | 27        | 0.91%   |
| Linux Mint 20      | 27        | 0.91%   |
| Ubuntu 19.10       | 26        | 0.87%   |
| Linux Mint 19.3    | 26        | 0.87%   |
| Fedora 35          | 26        | 0.87%   |
| Ubuntu 21.10       | 25        | 0.84%   |
| OpenMandriva 23.01 | 25        | 0.84%   |
| Fedora 37          | 25        | 0.84%   |
| Ubuntu 19.04       | 23        | 0.77%   |
| Debian 10          | 23        | 0.77%   |
| Ubuntu 22.10       | 22        | 0.74%   |
| Ubuntu 20.10       | 22        | 0.74%   |
| Pop!_OS 21.04      | 22        | 0.74%   |
| Linux Mint 21      | 22        | 0.74%   |
| Fedora 39          | 22        | 0.74%   |
| Ubuntu 23.04       | 20        | 0.67%   |
| Linux Mint 20.1    | 20        | 0.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 809       | 28.47%  |
| OpenMandriva  | 281       | 9.89%   |
| Fedora        | 240       | 8.44%   |
| Linux Mint    | 227       | 7.99%   |
| Debian        | 154       | 5.42%   |
| Zorin         | 118       | 4.15%   |
| Pop!_OS       | 116       | 4.08%   |
| Manjaro       | 104       | 3.66%   |
| KDE neon      | 84        | 2.96%   |
| Arch          | 73        | 2.57%   |
| Kubuntu       | 57        | 2.01%   |
| Endless       | 48        | 1.69%   |
| Xubuntu       | 47        | 1.65%   |
| ROSA          | 47        | 1.65%   |
| Elementary    | 44        | 1.55%   |
| ArcoLinux     | 40        | 1.41%   |
| Kali          | 34        | 1.2%    |
| openSUSE      | 31        | 1.09%   |
| Nobara        | 20        | 0.7%    |
| EndeavourOS   | 19        | 0.67%   |
| Lubuntu       | 17        | 0.6%    |
| Clear Linux   | 15        | 0.53%   |
| Ubuntu MATE   | 14        | 0.49%   |
| LMDE          | 14        | 0.49%   |
| Gentoo        | 14        | 0.49%   |
| Ubuntu Budgie | 12        | 0.42%   |
| Parrot        | 12        | 0.42%   |
| Ubuntu Unity  | 11        | 0.39%   |
| SteamOS       | 11        | 0.39%   |
| MX            | 10        | 0.35%   |
| CentOS        | 10        | 0.35%   |
| Xero          | 9         | 0.32%   |
| Garuda Linux  | 9         | 0.32%   |
| Archcraft     | 6         | 0.21%   |
| Peppermint    | 5         | 0.18%   |
| Linux Lite    | 5         | 0.18%   |
| RHEL          | 4         | 0.14%   |
| Reborn OS     | 4         | 0.14%   |
| BlackPanther  | 4         | 0.14%   |
| BigLinux      | 4         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 93        | 2.86%   |
| 5.16.7-desktop-1omv4003  | 80        | 2.46%   |
| 5.4.0-42-generic         | 44        | 1.35%   |
| 6.2.6-desktop-1omv2390   | 29        | 0.89%   |
| 5.4.0-58-generic         | 27        | 0.83%   |
| 5.15.0-56-generic        | 27        | 0.83%   |
| 6.4.11-desktop-1omv2390  | 23        | 0.71%   |
| 6.1.1-desktop-1omv2290   | 23        | 0.71%   |
| 5.15.0-58-generic        | 22        | 0.68%   |
| 5.8.0-14-generic         | 21        | 0.65%   |
| 5.4.0-91-generic         | 20        | 0.62%   |
| 5.3.0-40-generic         | 20        | 0.62%   |
| 5.11.0-27-generic        | 19        | 0.58%   |
| 5.4.0-52-generic         | 18        | 0.55%   |
| 5.4.0-48-generic         | 18        | 0.55%   |
| 5.15.0-52-generic        | 18        | 0.55%   |
| 5.4.0-40-generic         | 17        | 0.52%   |
| 5.19.0-35-generic        | 17        | 0.52%   |
| 5.15.0-48-generic        | 17        | 0.52%   |
| 5.15.0-47-generic        | 17        | 0.52%   |
| 6.1.0-13-amd64           | 16        | 0.49%   |
| 5.3.0-46-generic         | 16        | 0.49%   |
| 5.11.0-37-generic        | 16        | 0.49%   |
| 6.5.0-14-generic         | 15        | 0.46%   |
| 6.2.6-76060206-generic   | 15        | 0.46%   |
| 5.4.0-65-generic         | 15        | 0.46%   |
| 5.13.0-40-generic        | 15        | 0.46%   |
| 6.2.0-26-generic         | 14        | 0.43%   |
| 5.4.0-54-generic         | 14        | 0.43%   |
| 5.4.0-37-generic         | 14        | 0.43%   |
| 5.3.0-42-generic         | 14        | 0.43%   |
| 5.3.0-28-generic         | 14        | 0.43%   |
| 5.19.0-43-generic        | 14        | 0.43%   |
| 5.19.0-38-generic        | 14        | 0.43%   |
| 5.13.0-39-generic        | 14        | 0.43%   |
| 6.2.0-37-generic         | 13        | 0.4%    |
| 5.15.0-91-generic        | 13        | 0.4%    |
| 5.15.0-78-generic        | 13        | 0.4%    |
| 5.11.0-7620-generic      | 13        | 0.4%    |
| 6.2.0-39-generic         | 12        | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 399       | 13%     |
| 5.15.0  | 277       | 9.03%   |
| 5.11.0  | 134       | 4.37%   |
| 5.13.0  | 127       | 4.14%   |
| 5.8.0   | 121       | 3.94%   |
| 4.15.0  | 113       | 3.68%   |
| 5.3.0   | 111       | 3.62%   |
| 5.19.0  | 101       | 3.29%   |
| 6.2.0   | 94        | 3.06%   |
| 5.10.14 | 93        | 3.03%   |
| 5.10.0  | 88        | 2.87%   |
| 5.16.7  | 81        | 2.64%   |
| 4.18.0  | 74        | 2.41%   |
| 5.0.0   | 72        | 2.35%   |
| 6.1.0   | 55        | 1.79%   |
| 6.2.6   | 44        | 1.43%   |
| 6.5.0   | 41        | 1.34%   |
| 4.19.0  | 35        | 1.14%   |
| 6.4.11  | 31        | 1.01%   |
| 6.1.1   | 30        | 0.98%   |
| 6.6.2   | 14        | 0.46%   |
| 6.5.5   | 11        | 0.36%   |
| 6.4.6   | 11        | 0.36%   |
| 6.2.15  | 11        | 0.36%   |
| 6.0.12  | 11        | 0.36%   |
| 5.16.13 | 11        | 0.36%   |
| 5.14.0  | 11        | 0.36%   |
| 6.5.6   | 10        | 0.33%   |
| 6.0.0   | 10        | 0.33%   |
| 5.17.5  | 10        | 0.33%   |
| 6.4.12  | 9         | 0.29%   |
| 6.3.5   | 9         | 0.29%   |
| 6.2.14  | 9         | 0.29%   |
| 4.9.20  | 9         | 0.29%   |
| 6.2.9   | 8         | 0.26%   |
| 6.6.1   | 7         | 0.23%   |
| 6.4.8   | 7         | 0.23%   |
| 6.4.4   | 7         | 0.23%   |
| 6.4.10  | 7         | 0.23%   |
| 6.0.11  | 7         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 429       | 14.17%  |
| 5.15    | 348       | 11.5%   |
| 5.10    | 224       | 7.4%    |
| 6.2     | 186       | 6.14%   |
| 5.11    | 152       | 5.02%   |
| 5.13    | 145       | 4.79%   |
| 5.19    | 137       | 4.53%   |
| 5.8     | 136       | 4.49%   |
| 5.3     | 128       | 4.23%   |
| 5.16    | 124       | 4.1%    |
| 6.1     | 122       | 4.03%   |
| 4.15    | 113       | 3.73%   |
| 6.5     | 95        | 3.14%   |
| 6.4     | 95        | 3.14%   |
| 4.18    | 76        | 2.51%   |
| 5.0     | 73        | 2.41%   |
| 6.0     | 54        | 1.78%   |
| 6.6     | 49        | 1.62%   |
| 6.3     | 42        | 1.39%   |
| 4.19    | 41        | 1.35%   |
| 5.18    | 37        | 1.22%   |
| 5.17    | 35        | 1.16%   |
| 5.14    | 33        | 1.09%   |
| 5.9     | 25        | 0.83%   |
| 4.9     | 25        | 0.83%   |
| 5.7     | 22        | 0.73%   |
| 5.12    | 21        | 0.69%   |
| 5.6     | 19        | 0.63%   |
| 5.5     | 9         | 0.3%    |
| 4.4     | 6         | 0.2%    |
| 6.7     | 5         | 0.17%   |
| 5.2     | 4         | 0.13%   |
| 4.12    | 4         | 0.13%   |
| 4.13    | 3         | 0.1%    |
| 4.1     | 3         | 0.1%    |
| 4.10    | 2         | 0.07%   |
| 3.10    | 2         | 0.07%   |
| 5.1     | 1         | 0.03%   |
| 4.20    | 1         | 0.03%   |
| 3.2     | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2642      | 96.99%  |
| i686    | 77        | 2.83%   |
| aarch64 | 4         | 0.15%   |
| armv7l  | 1         | 0.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 1261      | 44.29%  |
| KDE5              | 587       | 20.62%  |
| Unknown           | 231       | 8.11%   |
| XFCE              | 202       | 7.1%    |
| X-Cinnamon        | 179       | 6.29%   |
| MATE              | 85        | 2.99%   |
| KDE               | 74        | 2.6%    |
| Pantheon          | 42        | 1.48%   |
| Cinnamon          | 37        | 1.3%    |
| LXQt              | 25        | 0.88%   |
| KDE4              | 22        | 0.77%   |
| LXDE              | 18        | 0.63%   |
| Budgie            | 16        | 0.56%   |
| Unity             | 11        | 0.39%   |
| Deepin            | 9         | 0.32%   |
| i3                | 8         | 0.28%   |
| openbox           | 5         | 0.18%   |
| Hyprland          | 5         | 0.18%   |
| GNOME Classic     | 5         | 0.18%   |
| qtile             | 4         | 0.14%   |
| lightdm-xsession  | 4         | 0.14%   |
| Trinity           | 3         | 0.11%   |
| GNOME Flashback   | 3         | 0.11%   |
| Enlightenment     | 3         | 0.11%   |
| awesome           | 2         | 0.07%   |
| Yaru:ubuntu:GNOME | 1         | 0.04%   |
| xmonad            | 1         | 0.04%   |
| wayland           | 1         | 0.04%   |
| i3-with-shmlog    | 1         | 0.04%   |
| chadwm            | 1         | 0.04%   |
| bspwm             | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2058      | 72.9%   |
| Wayland | 603       | 21.36%  |
| Unknown | 143       | 5.07%   |
| Tty     | 19        | 0.67%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1360      | 48.02%  |
| SDDM    | 490       | 17.3%   |
| GDM3    | 339       | 11.97%  |
| LightDM | 284       | 10.03%  |
| GDM     | 267       | 9.43%   |
| TDM     | 53        | 1.87%   |
| KDM     | 23        | 0.81%   |
| SLiM    | 5         | 0.18%   |
| XDM     | 4         | 0.14%   |
| LXDM    | 3         | 0.11%   |
| NODM    | 1         | 0.04%   |
| MDM     | 1         | 0.04%   |
| LY-DM   | 1         | 0.04%   |
| Ly      | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| es_MX      | 1375      | 49.19%  |
| en_US      | 901       | 32.24%  |
| Unknown    | 224       | 8.01%   |
| es_ES      | 181       | 6.48%   |
| C          | 49        | 1.75%   |
| en_GB      | 21        | 0.75%   |
| es_US      | 8         | 0.29%   |
| en_CA      | 5         | 0.18%   |
| fr_FR      | 3         | 0.11%   |
| POSIX      | 2         | 0.07%   |
| it_IT      | 2         | 0.07%   |
| es_MX.UTF8 | 2         | 0.07%   |
| es_CO      | 2         | 0.07%   |
| es_AR      | 2         | 0.07%   |
| en_MX      | 2         | 0.07%   |
| en_DK      | 2         | 0.07%   |
| C.UTF8     | 2         | 0.07%   |
| uk_UA      | 1         | 0.04%   |
| ru_RU      | 1         | 0.04%   |
| pt_BR      | 1         | 0.04%   |
| nhn_MX     | 1         | 0.04%   |
| es_PE      | 1         | 0.04%   |
| es_GT      | 1         | 0.04%   |
| es_CR      | 1         | 0.04%   |
| es_419     | 1         | 0.04%   |
| en_US.UTF8 | 1         | 0.04%   |
| en_IE      | 1         | 0.04%   |
| de_DE      | 1         | 0.04%   |
| Default    | 1         | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 1466      | 52.62%  |
| EFI  | 1320      | 47.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Computers | Percent |
|---------------------|-----------|---------|
| Ext4                | 2015      | 71.94%  |
| Btrfs               | 287       | 10.25%  |
| Overlay             | 265       | 9.46%   |
| Tmpfs               | 97        | 3.46%   |
| Unknown             | 69        | 2.46%   |
| Xfs                 | 37        | 1.32%   |
| Zfs                 | 12        | 0.43%   |
| Ext2                | 8         | 0.29%   |
| Reiserfs            | 3         | 0.11%   |
| XXXXXXX             | 2         | 0.07%   |
| F2fs                | 2         | 0.07%   |
| Ext3                | 2         | 0.07%   |
| Fuse.fuse-overlayfs | 1         | 0.04%   |
| Aufs                | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1474      | 52.79%  |
| GPT     | 1007      | 36.07%  |
| MBR     | 311       | 11.14%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2418      | 87.26%  |
| Yes       | 353       | 12.74%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1893      | 68.09%  |
| Yes       | 887       | 31.91%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 521       | 19.13%  |
| Lenovo                  | 395       | 14.51%  |
| Dell                    | 385       | 14.14%  |
| ASUSTek Computer        | 312       | 11.46%  |
| Gigabyte Technology     | 187       | 6.87%   |
| Acer                    | 141       | 5.18%   |
| Apple                   | 90        | 3.31%   |
| Toshiba                 | 84        | 3.08%   |
| HUAWEI                  | 75        | 2.75%   |
| MSI                     | 59        | 2.17%   |
| Sony                    | 42        | 1.54%   |
| ASRock                  | 40        | 1.47%   |
| Intel                   | 36        | 1.32%   |
| ECS                     | 33        | 1.21%   |
| Biostar                 | 29        | 1.07%   |
| Gateway                 | 24        | 0.88%   |
| Samsung Electronics     | 21        | 0.77%   |
| Pegatron                | 18        | 0.66%   |
| Google                  | 18        | 0.66%   |
| Alienware               | 17        | 0.62%   |
| Lanix                   | 16        | 0.59%   |
| Unknown                 | 16        | 0.59%   |
| Microsoft               | 11        | 0.4%    |
| Chuwi                   | 11        | 0.4%    |
| Valve                   | 9         | 0.33%   |
| PCChips                 | 9         | 0.33%   |
| Foxconn                 | 8         | 0.29%   |
| AMI                     | 8         | 0.29%   |
| GPU Company             | 7         | 0.26%   |
| eMachines               | 7         | 0.26%   |
| GHIA                    | 5         | 0.18%   |
| A-DATA Technology       | 5         | 0.18%   |
| Timi                    | 4         | 0.15%   |
| System76                | 4         | 0.15%   |
| Raspberry Pi Foundation | 4         | 0.15%   |
| HONOR                   | 4         | 0.15%   |
| EVOO                    | 4         | 0.15%   |
| AZW                     | 4         | 0.15%   |
| TPV-INVENTA             | 3         | 0.11%   |
| Supermicro              | 3         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 31        | 1.14%   |
| HP Notebook                           | 29        | 1.07%   |
| ASUS PRIME A320M-K                    | 23        | 0.84%   |
| HUAWEI HVY-WXX9                       | 18        | 0.66%   |
| HP Pavilion Laptop 15-cw0xxx          | 17        | 0.62%   |
| HP Pavilion g4                        | 16        | 0.59%   |
| HP Pavilion Notebook                  | 15        | 0.55%   |
| ASUS All Series                       | 12        | 0.44%   |
| Apple MacBookPro9,2                   | 12        | 0.44%   |
| Apple MacBookPro8,1                   | 11        | 0.4%    |
| HP Pavilion Laptop 15-cw1xxx          | 10        | 0.37%   |
| HP Laptop 15-da0xxx                   | 10        | 0.37%   |
| Dell Latitude E6430                   | 10        | 0.37%   |
| Valve Jupiter                         | 9         | 0.33%   |
| HP EliteBook 8460p                    | 9         | 0.33%   |
| Gigabyte B450M DS3H                   | 9         | 0.33%   |
| Lenovo IdeaPad 330-14AST 81D5         | 8         | 0.29%   |
| HP Pavilion dv4                       | 8         | 0.29%   |
| HP Laptop 15-bw0xx                    | 8         | 0.29%   |
| Dell OptiPlex 7010                    | 8         | 0.29%   |
| Dell Inspiron 5559                    | 8         | 0.29%   |
| HUAWEI NBLK-WAX9X                     | 7         | 0.26%   |
| HUAWEI NBLB-WAX9N                     | 7         | 0.26%   |
| HP Laptop 15-db0xxx                   | 7         | 0.26%   |
| ECS A320AM4-M3D                       | 7         | 0.26%   |
| Dell OptiPlex 9020                    | 7         | 0.26%   |
| Dell OptiPlex 745                     | 7         | 0.26%   |
| ASUS PRIME B450M-A II                 | 7         | 0.26%   |
| Apple MacBookPro12,1                  | 7         | 0.26%   |
| Lenovo IdeaPad 3 14ALC6 82KT          | 6         | 0.22%   |
| Lenovo G40-45 80E1                    | 6         | 0.22%   |
| HP Pavilion x360 Convertible 14-ba0xx | 6         | 0.22%   |
| HP Pavilion dv5                       | 6         | 0.22%   |
| HP Pavilion 14                        | 6         | 0.22%   |
| HP Laptop 14-cm0xxx                   | 6         | 0.22%   |
| HP G42                                | 6         | 0.22%   |
| HP Compaq 6200 Pro SFF PC             | 6         | 0.22%   |
| GPU Company GWNR71517                 | 6         | 0.22%   |
| Gigabyte GA-880GM-USB3                | 6         | 0.22%   |
| Gigabyte A320M-S2H                    | 6         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| HP Pavilion        | 132       | 4.85%   |
| Lenovo ThinkPad    | 126       | 4.63%   |
| Lenovo IdeaPad     | 122       | 4.48%   |
| Dell Inspiron      | 121       | 4.44%   |
| Dell Latitude      | 103       | 3.78%   |
| Acer Aspire        | 100       | 3.67%   |
| Toshiba Satellite  | 75        | 2.75%   |
| ASUS PRIME         | 75        | 2.75%   |
| HP Laptop          | 72        | 2.64%   |
| Dell OptiPlex      | 70        | 2.57%   |
| HP Compaq          | 49        | 1.8%    |
| Unknown            | 31        | 1.14%   |
| Lenovo ThinkCentre | 30        | 1.1%    |
| HP EliteBook       | 30        | 1.1%    |
| HP Notebook        | 29        | 1.07%   |
| ASUS VivoBook      | 28        | 1.03%   |
| ASUS ROG           | 28        | 1.03%   |
| HP ProBook         | 27        | 0.99%   |
| Dell Precision     | 20        | 0.73%   |
| HUAWEI HVY-WXX9    | 18        | 0.66%   |
| HP ENVY            | 18        | 0.66%   |
| Lenovo Yoga        | 16        | 0.59%   |
| ASUS TUF           | 16        | 0.59%   |
| Dell XPS           | 14        | 0.51%   |
| Lenovo Legion      | 13        | 0.48%   |
| HP ProDesk         | 13        | 0.48%   |
| HP 240             | 13        | 0.48%   |
| Dell Vostro        | 13        | 0.48%   |
| Apple MacBookPro9  | 13        | 0.48%   |
| Gigabyte B450M     | 12        | 0.44%   |
| ASUS All           | 12        | 0.44%   |
| Apple MacBookPro8  | 12        | 0.44%   |
| Microsoft Surface  | 11        | 0.4%    |
| Dell Studio        | 11        | 0.4%    |
| Gigabyte A320M-S2H | 10        | 0.37%   |
| Valve Jupiter      | 9         | 0.33%   |
| HP OMEN            | 9         | 0.33%   |
| HP EliteDesk       | 9         | 0.33%   |
| Gigabyte X570      | 9         | 0.33%   |
| ASUS M5A78L-M      | 9         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 257       | 9.44%   |
| 2011    | 233       | 8.56%   |
| 2020    | 220       | 8.08%   |
| 2012    | 220       | 8.08%   |
| 2019    | 204       | 7.49%   |
| 2017    | 203       | 7.46%   |
| 2014    | 176       | 6.46%   |
| 2013    | 172       | 6.32%   |
| 2015    | 166       | 6.1%    |
| 2021    | 159       | 5.84%   |
| 2010    | 142       | 5.21%   |
| 2016    | 133       | 4.88%   |
| 2008    | 114       | 4.19%   |
| 2009    | 101       | 3.71%   |
| 2022    | 78        | 2.86%   |
| 2007    | 67        | 2.46%   |
| 2023    | 30        | 1.1%    |
| 2006    | 27        | 0.99%   |
| 2005    | 12        | 0.44%   |
| Unknown | 6         | 0.22%   |
| 2004    | 2         | 0.07%   |
| 2003    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1682      | 61.77%  |
| Desktop        | 848       | 31.14%  |
| All in one     | 59        | 2.17%   |
| Convertible    | 55        | 2.02%   |
| Tablet         | 28        | 1.03%   |
| Mini pc        | 28        | 1.03%   |
| Server         | 19        | 0.7%    |
| System on chip | 4         | 0.15%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2504      | 91.12%  |
| Enabled  | 244       | 8.88%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2703      | 99.27%  |
| Yes  | 20        | 0.73%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 754       | 27.26%  |
| 3.01-4.0        | 597       | 21.58%  |
| 8.01-16.0       | 539       | 19.49%  |
| 16.01-24.0      | 381       | 13.77%  |
| 32.01-64.0      | 155       | 5.6%    |
| 1.01-2.0        | 154       | 5.57%   |
| 2.01-3.0        | 56        | 2.02%   |
| 24.01-32.0      | 54        | 1.95%   |
| 64.01-256.0     | 47        | 1.7%    |
| 0.51-1.0        | 24        | 0.87%   |
| More than 256.0 | 3         | 0.11%   |
| 0.01-0.5        | 1         | 0.04%   |
| Unknown         | 1         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 1067      | 35.45%  |
| 2.01-3.0    | 818       | 27.18%  |
| 3.01-4.0    | 395       | 13.12%  |
| 4.01-8.0    | 386       | 12.82%  |
| 0.51-1.0    | 190       | 6.31%   |
| 8.01-16.0   | 109       | 3.62%   |
| 0.01-0.5    | 24        | 0.8%    |
| 16.01-24.0  | 12        | 0.4%    |
| 24.01-32.0  | 4         | 0.13%   |
| 32.01-64.0  | 2         | 0.07%   |
| Unknown     | 2         | 0.07%   |
| 64.01-256.0 | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1843      | 65.63%  |
| 2       | 678       | 24.15%  |
| 3       | 148       | 5.27%   |
| 4       | 64        | 2.28%   |
| 0       | 33        | 1.18%   |
| 5       | 19        | 0.68%   |
| 6       | 14        | 0.5%    |
| 7       | 5         | 0.18%   |
| 37      | 1         | 0.04%   |
| 18      | 1         | 0.04%   |
| 8       | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1737      | 63.35%  |
| Yes       | 1005      | 36.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2321      | 85.14%  |
| No        | 405       | 14.86%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2249      | 82.2%   |
| No        | 487       | 17.8%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1641      | 59.5%   |
| No        | 1117      | 40.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Mexico  | 2723      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Mexico City           | 558       | 19.29%  |
| Guadalajara           | 147       | 5.08%   |
| Monterrey             | 100       | 3.46%   |
| Tijuana               | 90        | 3.11%   |
| Zapopan               | 86        | 2.97%   |
| Puebla City           | 81        | 2.8%    |
| Mérida               | 57        | 1.97%   |
| Queretaro             | 55        | 1.9%    |
| Toluca                | 40        | 1.38%   |
| Morelia               | 39        | 1.35%   |
| Ciudad Juárez        | 38        | 1.31%   |
| Tlalnepantla          | 37        | 1.28%   |
| Hermosillo            | 37        | 1.28%   |
| Cancún               | 36        | 1.24%   |
| Naucalpan             | 32        | 1.11%   |
| Mexicali              | 32        | 1.11%   |
| León                 | 32        | 1.11%   |
| Ecatepec              | 32        | 1.11%   |
| Cuernavaca            | 29        | 1%      |
| Ciudad Lopez Mateos   | 29        | 1%      |
| Apodaca               | 29        | 1%      |
| Ciudad Nezahualcoyotl | 28        | 0.97%   |
| Xalapa                | 27        | 0.93%   |
| Oaxaca City           | 27        | 0.93%   |
| Chihuahua City        | 27        | 0.93%   |
| Veracruz              | 26        | 0.9%    |
| Culiacán             | 26        | 0.9%    |
| San Luis Potosí City | 25        | 0.86%   |
| Mexico                | 24        | 0.83%   |
| Saltillo              | 22        | 0.76%   |
| Guadalupe             | 22        | 0.76%   |
| Iztapalapa            | 21        | 0.73%   |
| Gustavo Adolfo Madero | 21        | 0.73%   |
| Villahermosa          | 20        | 0.69%   |
| Aguascalientes        | 19        | 0.66%   |
| Querétaro City       | 18        | 0.62%   |
| Pachuca               | 18        | 0.62%   |
| Ensenada              | 17        | 0.59%   |
| Colima                | 17        | 0.59%   |
| Celaya                | 17        | 0.59%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 655       | 957    | 17.66%  |
| WDC                         | 561       | 768    | 15.13%  |
| Kingston                    | 366       | 474    | 9.87%   |
| Toshiba                     | 314       | 381    | 8.47%   |
| A-DATA Technology           | 270       | 335    | 7.28%   |
| Samsung Electronics         | 238       | 308    | 6.42%   |
| Hitachi                     | 177       | 225    | 4.77%   |
| Unknown                     | 163       | 222    | 4.4%    |
| SanDisk                     | 118       | 147    | 3.18%   |
| HGST                        | 89        | 103    | 2.4%    |
| SK hynix                    | 65        | 84     | 1.75%   |
| Intel                       | 64        | 104    | 1.73%   |
| Crucial                     | 49        | 66     | 1.32%   |
| Apple                       | 40        | 56     | 1.08%   |
| XPG                         | 35        | 47     | 0.94%   |
| Micron Technology           | 33        | 45     | 0.89%   |
| Fujitsu                     | 25        | 30     | 0.67%   |
| PNY                         | 24        | 31     | 0.65%   |
| Realtek Semiconductor       | 22        | 28     | 0.59%   |
| China                       | 21        | 22     | 0.57%   |
| Silicon Motion              | 20        | 22     | 0.54%   |
| KIOXIA                      | 20        | 23     | 0.54%   |
| Kingston Technology Company | 18        | 19     | 0.49%   |
| ADATA Technology            | 18        | 20     | 0.49%   |
| Unknown                     | 18        | 18     | 0.49%   |
| Phison                      | 16        | 17     | 0.43%   |
| LITEON                      | 15        | 20     | 0.4%    |
| Phison Electronics          | 13        | 16     | 0.35%   |
| Hewlett-Packard             | 13        | 14     | 0.35%   |
| Micron/Crucial Technology   | 11        | 15     | 0.3%    |
| Netac                       | 10        | 12     | 0.27%   |
| Maxtor                      | 10        | 12     | 0.27%   |
| Acer                        | 10        | 12     | 0.27%   |
| JMicron Technology          | 9         | 10     | 0.24%   |
| YMTC                        | 8         | 9      | 0.22%   |
| Patriot                     | 8         | 12     | 0.22%   |
| Gigabyte Technology         | 8         | 9      | 0.22%   |
| UMIS                        | 6         | 7      | 0.16%   |
| MAXIO Technology (Hangzhou) | 6         | 6      | 0.16%   |
| AS201                       | 6         | 6      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                   | 101       | 2.53%   |
| Kingston SA400S37480G 480GB SSD                   | 77        | 1.93%   |
| Seagate ST1000LM035-1RK172 1TB                    | 74        | 1.86%   |
| Toshiba MQ01ABD100 1TB                            | 51        | 1.28%   |
| A-DATA SU650 120GB SSD                            | 50        | 1.25%   |
| Toshiba MQ04ABF100 1TB                            | 44        | 1.1%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 41        | 1.03%   |
| A-DATA SU630 240GB SSD                            | 41        | 1.03%   |
| Seagate ST500DM002-1BD142 500GB                   | 39        | 0.98%   |
| Unknown MMC Card  32GB                            | 34        | 0.85%   |
| Seagate ST500LT012-1DG142 500GB                   | 32        | 0.8%    |
| Toshiba MQ01ABF050 500GB                          | 31        | 0.78%   |
| Kingston SA400S37120G 120GB SSD                   | 30        | 0.75%   |
| Seagate ST1000DM010-2EP102 1TB                    | 27        | 0.68%   |
| A-DATA SU630 480GB SSD                            | 27        | 0.68%   |
| Kingston SA400S37960G 960GB SSD                   | 26        | 0.65%   |
| A-DATA SU650 240GB SSD                            | 22        | 0.55%   |
| Unknown MMC Card  64GB                            | 20        | 0.5%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 19        | 0.48%   |
| Unknown                                           | 18        | 0.45%   |
| Unknown SD/MMC/MS PRO 256GB                       | 17        | 0.43%   |
| Unknown MMC Card  16GB                            | 17        | 0.43%   |
| Seagate ST9500325AS 500GB                         | 17        | 0.43%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 17        | 0.43%   |
| HGST HTS541010A9E680 1TB                          | 16        | 0.4%    |
| Toshiba DT01ACA050 500GB                          | 15        | 0.38%   |
| Seagate ST3500418AS 500GB                         | 15        | 0.38%   |
| Kingston SV300S37A120G 120GB SSD                  | 15        | 0.38%   |
| XPG GAMMIX S11 Pro 256GB                          | 14        | 0.35%   |
| Toshiba DT01ACA100 1TB                            | 14        | 0.35%   |
| Seagate ST500LM021-1KJ152 500GB                   | 14        | 0.35%   |
| Seagate ST2000LM007-1R8174 2TB                    | 14        | 0.35%   |
| HGST HTS725050A7E630 500GB                        | 14        | 0.35%   |
| Seagate ST1000DM003-1CH162 1TB                    | 13        | 0.33%   |
| Samsung NVMe SSD Drive 512GB                      | 13        | 0.33%   |
| Kingston Company SNV2S1000G 1TB                   | 13        | 0.33%   |
| A-DATA SU800 512GB SSD                            | 13        | 0.33%   |
| WDC WD5000LPCX-60VHAT0 500GB                      | 12        | 0.3%    |
| Seagate ST500LT012-9WS142 500GB                   | 12        | 0.3%    |
| Sandisk WD Blue SN550 NVMe SSD 512GB              | 12        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 651       | 951    | 36.23%  |
| WDC                 | 480       | 643    | 26.71%  |
| Toshiba             | 282       | 344    | 15.69%  |
| Hitachi             | 177       | 225    | 9.85%   |
| HGST                | 89        | 103    | 4.95%   |
| Samsung Electronics | 35        | 40     | 1.95%   |
| Fujitsu             | 25        | 30     | 1.39%   |
| Unknown             | 17        | 18     | 0.95%   |
| Apple               | 13        | 18     | 0.72%   |
| Maxtor              | 10        | 12     | 0.56%   |
| JMicron Technology  | 5         | 6      | 0.28%   |
| Hewlett-Packard     | 3         | 3      | 0.17%   |
| LaCie               | 2         | 3      | 0.11%   |
| StoreJet            | 1         | 1      | 0.06%   |
| SAGE                | 1         | 1      | 0.06%   |
| QUANTUM             | 1         | 2      | 0.06%   |
| MaxDigital          | 1         | 4      | 0.06%   |
| IBM/Hitachi         | 1         | 1      | 0.06%   |
| HPE                 | 1         | 1      | 0.06%   |
| External            | 1         | 1      | 0.06%   |
| DELLBOSS            | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 328       | 416    | 30.8%   |
| A-DATA Technology   | 251       | 314    | 23.57%  |
| Samsung Electronics | 72        | 86     | 6.76%   |
| WDC                 | 68        | 91     | 6.38%   |
| Crucial             | 43        | 52     | 4.04%   |
| SanDisk             | 41        | 47     | 3.85%   |
| PNY                 | 23        | 30     | 2.16%   |
| China               | 21        | 22     | 1.97%   |
| Apple               | 21        | 23     | 1.97%   |
| SK hynix            | 17        | 26     | 1.6%    |
| Intel               | 15        | 20     | 1.41%   |
| Micron Technology   | 13        | 16     | 1.22%   |
| LITEON              | 13        | 18     | 1.22%   |
| Netac               | 10        | 12     | 0.94%   |
| Hewlett-Packard     | 9         | 10     | 0.85%   |
| Acer                | 9         | 10     | 0.85%   |
| Patriot             | 7         | 11     | 0.66%   |
| Gigabyte Technology | 7         | 8      | 0.66%   |
| AS201               | 6         | 6      | 0.56%   |
| Wibtek              | 5         | 5      | 0.47%   |
| Unknown             | 5         | 5      | 0.47%   |
| Toshiba             | 4         | 4      | 0.38%   |
| Team                | 4         | 4      | 0.38%   |
| SPCC                | 4         | 4      | 0.38%   |
| LITEONIT            | 4         | 4      | 0.38%   |
| Lexar               | 4         | 4      | 0.38%   |
| Blackpcs            | 4         | 4      | 0.38%   |
| Yeyian              | 3         | 6      | 0.28%   |
| USB3.0              | 3         | 3      | 0.28%   |
| Unknown             | 3         | 3      | 0.28%   |
| Transcend           | 3         | 3      | 0.28%   |
| Pioneer             | 3         | 4      | 0.28%   |
| OCZ                 | 3         | 5      | 0.28%   |
| BHT                 | 3         | 3      | 0.28%   |
| tecmiyo             | 2         | 4      | 0.19%   |
| SABRENT             | 2         | 2      | 0.19%   |
| Quaroni             | 2         | 2      | 0.19%   |
| KingSpec            | 2         | 7      | 0.19%   |
| Dogfish             | 2         | 5      | 0.19%   |
| ZTC                 | 1         | 1      | 0.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1594      | 2408   | 47.24%  |
| SSD     | 961       | 1328   | 28.48%  |
| NVMe    | 632       | 890    | 18.73%  |
| MMC     | 147       | 198    | 4.36%   |
| Unknown | 40        | 60     | 1.19%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2191      | 3635   | 70.77%  |
| NVMe | 630       | 886    | 20.35%  |
| MMC  | 147       | 198    | 4.75%   |
| SAS  | 128       | 165    | 4.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1590      | 2309   | 60.73%  |
| 0.51-1.0   | 791       | 1048   | 30.21%  |
| 1.01-2.0   | 157       | 216    | 6%      |
| 3.01-4.0   | 36        | 68     | 1.38%   |
| 2.01-3.0   | 25        | 34     | 0.95%   |
| 4.01-10.0  | 17        | 41     | 0.65%   |
| 10.01-20.0 | 2         | 20     | 0.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 740       | 25.61%  |
| 251-500        | 663       | 22.95%  |
| 501-1000       | 462       | 15.99%  |
| 1-20           | 243       | 8.41%   |
| 51-100         | 228       | 7.89%   |
| 1001-2000      | 225       | 7.79%   |
| 21-50          | 132       | 4.57%   |
| More than 3000 | 89        | 3.08%   |
| 2001-3000      | 59        | 2.04%   |
| Unknown        | 48        | 1.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1224      | 40.94%  |
| 21-50          | 578       | 19.33%  |
| 101-250        | 354       | 11.84%  |
| 51-100         | 327       | 10.94%  |
| 251-500        | 199       | 6.66%   |
| 501-1000       | 139       | 4.65%   |
| 1001-2000      | 78        | 2.61%   |
| Unknown        | 48        | 1.61%   |
| More than 3000 | 27        | 0.9%    |
| 2001-3000      | 15        | 0.5%    |
| 0              | 1         | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB              | 8         | 9      | 2.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 7         | 8      | 2.29%   |
| Seagate ST500LT012-1DG142 500GB     | 6         | 7      | 1.96%   |
| Toshiba MQ04ABF100 1TB              | 5         | 5      | 1.63%   |
| HGST HTS541010A9E680 1TB            | 5         | 5      | 1.63%   |
| Toshiba MQ01ABF050 500GB            | 4         | 4      | 1.31%   |
| Seagate ST9500420AS 500GB           | 4         | 4      | 1.31%   |
| Seagate ST500LM021-1KJ152 500GB     | 4         | 4      | 1.31%   |
| Seagate ST3160815AS 160GB           | 4         | 4      | 1.31%   |
| Seagate ST1000LM035-1RK172 1TB      | 4         | 4      | 1.31%   |
| Hitachi HTS545050B9A300 500GB       | 4         | 4      | 1.31%   |
| HGST HTS541075A9E680 752GB          | 4         | 4      | 1.31%   |
| Seagate ST9500325AS 500GB           | 3         | 3      | 0.98%   |
| Seagate ST3500418AS 500GB           | 3         | 4      | 0.98%   |
| Seagate ST31000524AS 1TB            | 3         | 5      | 0.98%   |
| Seagate ST2000DL003-9VT166 2TB      | 3         | 3      | 0.98%   |
| LITEON CV8-8E128-HP 128GB SSD       | 3         | 3      | 0.98%   |
| HGST HTS545050A7E380 500GB          | 3         | 5      | 0.98%   |
| HGST HTS541010A7E630 1TB            | 3         | 3      | 0.98%   |
| China SSD 256GB                     | 3         | 3      | 0.98%   |
| A-DATA Technology SU650 240GB SSD   | 3         | 3      | 0.98%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 2      | 0.65%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 2         | 2      | 0.65%   |
| WDC WD3200AAJS-00YZCA0 320GB        | 2         | 3      | 0.65%   |
| WDC WD2500BEVS-60UST0 250GB         | 2         | 2      | 0.65%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 2         | 2      | 0.65%   |
| WDC WD10JPVX-60JC3T0 1TB            | 2         | 2      | 0.65%   |
| Toshiba DT01ACA100 1TB              | 2         | 2      | 0.65%   |
| Seagate ST9320325AS 320GB           | 2         | 4      | 0.65%   |
| Seagate ST500LT012-9WS142 500GB     | 2         | 2      | 0.65%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2         | 3      | 0.65%   |
| Seagate ST500DM002-1BD142 500GB     | 2         | 2      | 0.65%   |
| Seagate ST2000DM001-1CH164 2TB      | 2         | 2      | 0.65%   |
| Seagate ST1500DL003-9VT16L 1TB      | 2         | 2      | 0.65%   |
| Seagate ST1000DM010-2EP102 1TB      | 2         | 2      | 0.65%   |
| Seagate ST1000DM003-9YN162 1TB      | 2         | 2      | 0.65%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 2         | 2      | 0.65%   |
| Maxtor 6Y080M0 82GB                 | 2         | 2      | 0.65%   |
| Kingston SUV400S37480G 480GB SSD    | 2         | 2      | 0.65%   |
| Kingston SA400S37240G 240GB SSD     | 2         | 2      | 0.65%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 93        | 128    | 31.31%  |
| WDC                       | 58        | 71     | 19.53%  |
| Toshiba                   | 39        | 51     | 13.13%  |
| Hitachi                   | 37        | 40     | 12.46%  |
| HGST                      | 18        | 20     | 6.06%   |
| Kingston                  | 13        | 13     | 4.38%   |
| Samsung Electronics       | 8         | 8      | 2.69%   |
| A-DATA Technology         | 7         | 7      | 2.36%   |
| Fujitsu                   | 5         | 5      | 1.68%   |
| SanDisk                   | 4         | 4      | 1.35%   |
| LITEON                    | 4         | 4      | 1.35%   |
| Maxtor                    | 3         | 3      | 1.01%   |
| China                     | 3         | 3      | 1.01%   |
| Crucial                   | 2         | 2      | 0.67%   |
| Micron/Crucial Technology | 1         | 2      | 0.34%   |
| Micron Technology         | 1         | 1      | 0.34%   |
| Intel                     | 1         | 1      | 0.34%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 93        | 128    | 35.91%  |
| WDC                 | 57        | 70     | 22.01%  |
| Toshiba             | 39        | 51     | 15.06%  |
| Hitachi             | 37        | 40     | 14.29%  |
| HGST                | 18        | 20     | 6.95%   |
| Samsung Electronics | 7         | 7      | 2.7%    |
| Fujitsu             | 5         | 5      | 1.93%   |
| Maxtor              | 3         | 3      | 1.16%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 245       | 324    | 86.57%  |
| SSD  | 32        | 32     | 11.31%  |
| NVMe | 6         | 7      | 2.12%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST3500410AS 500GB         | 2         | 3      | 25%     |
| Seagate ST31500341AS 1TB          | 2         | 3      | 25%     |
| WDC WD1600BEVT-75A23T0 160GB      | 1         | 1      | 12.5%   |
| Toshiba MK1234GSX 120GB           | 1         | 1      | 12.5%   |
| Samsung Electronics HD161GJ 160GB | 1         | 1      | 12.5%   |
| Hitachi HTS545016B9A300 160GB     | 1         | 1      | 12.5%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 6      | 33.33%  |
| WDC                 | 1         | 1      | 16.67%  |
| Toshiba             | 1         | 1      | 16.67%  |
| Samsung Electronics | 1         | 1      | 16.67%  |
| Hitachi             | 1         | 1      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1709      | 2970   | 58.53%  |
| Works    | 928       | 1541   | 31.78%  |
| Malfunc  | 277       | 363    | 9.49%   |
| Failed   | 6         | 10     | 0.21%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1683      | 53.51%  |
| AMD                                     | 692       | 22%     |
| Samsung Electronics                     | 141       | 4.48%   |
| SanDisk                                 | 98        | 3.12%   |
| Nvidia                                  | 66        | 2.1%    |
| Kingston Technology Company             | 60        | 1.91%   |
| ADATA Technology                        | 55        | 1.75%   |
| SK hynix                                | 47        | 1.49%   |
| Realtek Semiconductor                   | 36        | 1.14%   |
| Phison Electronics                      | 32        | 1.02%   |
| Toshiba America Info Systems            | 29        | 0.92%   |
| Marvell Technology Group                | 24        | 0.76%   |
| KIOXIA                                  | 21        | 0.67%   |
| Silicon Motion                          | 20        | 0.64%   |
| Micron Technology                       | 20        | 0.64%   |
| Micron/Crucial Technology               | 18        | 0.57%   |
| Union Memory (Shenzhen)                 | 15        | 0.48%   |
| ASMedia Technology                      | 11        | 0.35%   |
| JMicron Technology                      | 10        | 0.32%   |
| Yangtze Memory Technologies             | 9         | 0.29%   |
| LSI Logic / Symbios Logic               | 9         | 0.29%   |
| MAXIO Technology (Hangzhou)             | 8         | 0.25%   |
| VIA Technologies                        | 6         | 0.19%   |
| Apple                                   | 6         | 0.19%   |
| Broadcom / LSI                          | 4         | 0.13%   |
| Silicon Image                           | 3         | 0.1%    |
| Lite-On Technology                      | 3         | 0.1%    |
| Hewlett-Packard                         | 3         | 0.1%    |
| Solid State Storage Technology          | 2         | 0.06%   |
| Seagate Technology                      | 2         | 0.06%   |
| Lenovo                                  | 2         | 0.06%   |
| INNOGRIT                                | 2         | 0.06%   |
| Solidigm                                | 1         | 0.03%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.03%   |
| Shenzhen Unionmemory Information System | 1         | 0.03%   |
| O2 Micro                                | 1         | 0.03%   |
| Broadcom                                | 1         | 0.03%   |
| Biwin Storage Technology                | 1         | 0.03%   |
| Adaptec                                 | 1         | 0.03%   |
| Unknown                                 | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 481       | 13.06%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 129       | 3.5%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 126       | 3.42%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 121       | 3.28%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 97        | 2.63%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 75        | 2.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 72        | 1.95%   |
| Intel SATA Controller [RAID Mode]                                                       | 65        | 1.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 62        | 1.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 60        | 1.63%   |
| AMD 400 Series Chipset SATA Controller                                                  | 60        | 1.63%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 55        | 1.49%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 54        | 1.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 51        | 1.38%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 50        | 1.36%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 49        | 1.33%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 49        | 1.33%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 48        | 1.3%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 44        | 1.19%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 44        | 1.19%   |
| AMD FCH SATA Controller D                                                               | 44        | 1.19%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 43        | 1.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 41        | 1.11%   |
| AMD 500 Series Chipset SATA Controller                                                  | 41        | 1.11%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 39        | 1.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 38        | 1.03%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 37        | 1%      |
| Intel Volume Management Device NVMe RAID Controller                                     | 37        | 1%      |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 37        | 1%      |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 35        | 0.95%   |
| Nvidia MCP61 SATA Controller                                                            | 29        | 0.79%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 28        | 0.76%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 27        | 0.73%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 26        | 0.71%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 26        | 0.71%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 25        | 0.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 25        | 0.68%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 25        | 0.68%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 25        | 0.68%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 24        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1988      | 60.5%   |
| NVMe | 631       | 19.2%   |
| IDE  | 396       | 12.05%  |
| RAID | 254       | 7.73%   |
| SAS  | 15        | 0.46%   |
| SCSI | 2         | 0.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 1882      | 69.09%  |
| AMD          | 835       | 30.65%  |
| ARM          | 4         | 0.15%   |
| Unknown      | 2         | 0.07%   |
| CentaurHauls | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 26        | 0.95%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 25        | 0.92%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 24        | 0.88%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 24        | 0.88%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 23        | 0.84%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 22        | 0.81%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 21        | 0.77%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 20        | 0.73%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 20        | 0.73%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 19        | 0.7%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 19        | 0.7%    |
| Intel Celeron CPU N3350 @ 1.10GHz             | 19        | 0.7%    |
| Intel Celeron CPU N3060 @ 1.60GHz             | 19        | 0.7%    |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 19        | 0.7%    |
| AMD Ryzen 5 5600G with Radeon Graphics        | 19        | 0.7%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 18        | 0.66%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 17        | 0.62%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 17        | 0.62%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 17        | 0.62%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 16        | 0.59%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 16        | 0.59%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 15        | 0.55%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 15        | 0.55%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 14        | 0.51%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 14        | 0.51%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 14        | 0.51%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 14        | 0.51%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 14        | 0.51%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 14        | 0.51%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 13        | 0.48%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 13        | 0.48%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 13        | 0.48%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 13        | 0.48%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 12        | 0.44%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 12        | 0.44%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 12        | 0.44%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 12        | 0.44%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 12        | 0.44%   |
| AMD Ryzen 5 3600 6-Core Processor             | 12        | 0.44%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 12        | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 486       | 17.82%  |
| Intel Core i7           | 402       | 14.74%  |
| Intel Celeron           | 234       | 8.58%   |
| Intel Core i3           | 222       | 8.14%   |
| AMD Ryzen 5             | 176       | 6.45%   |
| Other                   | 149       | 5.46%   |
| Intel Core 2 Duo        | 111       | 4.07%   |
| AMD Ryzen 7             | 100       | 3.67%   |
| Intel Atom              | 62        | 2.27%   |
| AMD Ryzen 3             | 56        | 2.05%   |
| Intel Xeon              | 55        | 2.02%   |
| AMD A6                  | 54        | 1.98%   |
| Intel Pentium           | 53        | 1.94%   |
| AMD A8                  | 49        | 1.8%    |
| AMD A4                  | 38        | 1.39%   |
| AMD FX                  | 35        | 1.28%   |
| AMD A10                 | 32        | 1.17%   |
| AMD Ryzen 9             | 31        | 1.14%   |
| AMD E                   | 31        | 1.14%   |
| AMD Athlon              | 31        | 1.14%   |
| Intel Pentium Dual-Core | 29        | 1.06%   |
| Intel Pentium Dual      | 29        | 1.06%   |
| Intel Core 2 Quad       | 17        | 0.62%   |
| AMD E1                  | 17        | 0.62%   |
| AMD Athlon II X2        | 17        | 0.62%   |
| Intel Core 2            | 15        | 0.55%   |
| AMD Athlon 64 X2        | 13        | 0.48%   |
| Intel Pentium 4         | 12        | 0.44%   |
| AMD Sempron             | 11        | 0.4%    |
| Intel Genuine           | 10        | 0.37%   |
| AMD Turion 64 X2 Mobile | 10        | 0.37%   |
| AMD Athlon II           | 10        | 0.37%   |
| AMD Ryzen 5 PRO         | 9         | 0.33%   |
| AMD Phenom II X4        | 9         | 0.33%   |
| Intel Pentium Silver    | 7         | 0.26%   |
| Intel Core i9           | 6         | 0.22%   |
| AMD Ryzen 3 PRO         | 6         | 0.22%   |
| AMD Phenom II X6        | 6         | 0.22%   |
| AMD E2                  | 6         | 0.22%   |
| Intel Celeron M         | 5         | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1331      | 48.77%  |
| 4       | 839       | 30.74%  |
| 6       | 234       | 8.57%   |
| 1       | 131       | 4.8%    |
| 8       | 115       | 4.21%   |
| 12      | 22        | 0.81%   |
| 16      | 13        | 0.48%   |
| 10      | 13        | 0.48%   |
| 3       | 11        | 0.4%    |
| 14      | 9         | 0.33%   |
| 24      | 4         | 0.15%   |
| 28      | 3         | 0.11%   |
| Unknown | 2         | 0.07%   |
| 56      | 1         | 0.04%   |
| 32      | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2704      | 99.27%  |
| 2       | 19        | 0.7%    |
| Unknown | 1         | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1650      | 60.48%  |
| 1       | 1075      | 39.41%  |
| Unknown | 2         | 0.07%   |
| 4       | 1         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2660      | 97.47%  |
| Unknown        | 35        | 1.28%   |
| 32-bit         | 22        | 0.81%   |
| 64-bit         | 12        | 0.44%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 817       | 28.74%  |
| 0x206a7    | 152       | 5.35%   |
| 0x306a9    | 118       | 4.15%   |
| 0x1067a    | 80        | 2.81%   |
| 0x306c3    | 68        | 2.39%   |
| 0x08108109 | 56        | 1.97%   |
| 0x40651    | 55        | 1.93%   |
| 0x30678    | 53        | 1.86%   |
| 0x806ec    | 50        | 1.76%   |
| 0x806e9    | 48        | 1.69%   |
| 0x806ea    | 43        | 1.51%   |
| 0x906ea    | 42        | 1.48%   |
| 0x306d4    | 42        | 1.48%   |
| 0x6fd      | 40        | 1.41%   |
| 0x406e3    | 38        | 1.34%   |
| 0x506e3    | 37        | 1.3%    |
| 0x06006705 | 37        | 1.3%    |
| 0x806c1    | 36        | 1.27%   |
| 0x406c4    | 35        | 1.23%   |
| 0x20655    | 34        | 1.2%    |
| 0x010000c8 | 33        | 1.16%   |
| 0x906e9    | 32        | 1.13%   |
| 0x06001119 | 32        | 1.13%   |
| 0x10676    | 30        | 1.06%   |
| 0x08600106 | 28        | 0.98%   |
| 0x0810100b | 28        | 0.98%   |
| 0x406c3    | 26        | 0.91%   |
| 0x07030105 | 24        | 0.84%   |
| 0x106ca    | 23        | 0.81%   |
| 0x0600611a | 23        | 0.81%   |
| 0x0a50000d | 22        | 0.77%   |
| 0x08608103 | 22        | 0.77%   |
| 0x08108102 | 22        | 0.77%   |
| 0x08101016 | 21        | 0.74%   |
| 0x0800820d | 20        | 0.7%    |
| 0x05000119 | 20        | 0.7%    |
| 0x706a1    | 19        | 0.67%   |
| 0x20652    | 19        | 0.67%   |
| 0x6fb      | 18        | 0.63%   |
| 0x706e5    | 17        | 0.6%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 332       | 12.17%  |
| SandyBridge      | 219       | 8.03%   |
| Haswell          | 182       | 6.67%   |
| IvyBridge        | 168       | 6.16%   |
| Silvermont       | 136       | 4.99%   |
| Penryn           | 134       | 4.91%   |
| Zen+             | 124       | 4.55%   |
| Skylake          | 119       | 4.36%   |
| Excavator        | 101       | 3.7%    |
| Core             | 93        | 3.41%   |
| Unknown          | 91        | 3.34%   |
| Zen 2            | 81        | 2.97%   |
| Zen              | 77        | 2.82%   |
| Westmere         | 72        | 2.64%   |
| Zen 3            | 70        | 2.57%   |
| Broadwell        | 69        | 2.53%   |
| K10              | 65        | 2.38%   |
| Piledriver       | 61        | 2.24%   |
| TigerLake        | 58        | 2.13%   |
| CometLake        | 53        | 1.94%   |
| Goldmont plus    | 52        | 1.91%   |
| Bobcat           | 44        | 1.61%   |
| K8 Hammer        | 43        | 1.58%   |
| Puma             | 41        | 1.5%    |
| Bonnell          | 39        | 1.43%   |
| IceLake          | 30        | 1.1%    |
| Goldmont         | 26        | 0.95%   |
| Alderlake Hybrid | 24        | 0.88%   |
| Steamroller      | 17        | 0.62%   |
| NetBurst         | 17        | 0.62%   |
| Nehalem          | 17        | 0.62%   |
| Jaguar           | 17        | 0.62%   |
| K10 Llano        | 13        | 0.48%   |
| P6               | 11        | 0.4%    |
| Bulldozer        | 11        | 0.4%    |
| Tremont          | 9         | 0.33%   |
| K8 & K10 hybrid  | 9         | 0.33%   |
| Gracemont        | 2         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1599      | 52.02%  |
| AMD                              | 877       | 28.53%  |
| Nvidia                           | 574       | 18.67%  |
| Matrox Electronics Systems       | 14        | 0.46%   |
| VIA Technologies                 | 4         | 0.13%   |
| ASPEED Technology                | 3         | 0.1%    |
| ATI Technologies                 | 2         | 0.07%   |
| Silicon Integrated Systems [SiS] | 1         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 179       | 5.61%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 100       | 3.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 99        | 3.1%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 71        | 2.22%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 70        | 2.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 66        | 2.07%   |
| Intel HD Graphics 620                                                                    | 58        | 1.82%   |
| Intel Core Processor Integrated Graphics Controller                                      | 58        | 1.82%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 57        | 1.79%   |
| Intel HD Graphics 5500                                                                   | 55        | 1.72%   |
| Intel UHD Graphics 620                                                                   | 52        | 1.63%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 52        | 1.63%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 52        | 1.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 49        | 1.54%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 49        | 1.54%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 48        | 1.5%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 47        | 1.47%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 47        | 1.47%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 46        | 1.44%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 46        | 1.44%   |
| Intel HD Graphics 530                                                                    | 39        | 1.22%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 38        | 1.19%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 36        | 1.13%   |
| Intel HD Graphics 630                                                                    | 36        | 1.13%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 35        | 1.1%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 35        | 1.1%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 35        | 1.1%    |
| AMD Lucienne                                                                             | 34        | 1.07%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 34        | 1.07%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 31        | 0.97%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 30        | 0.94%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 30        | 0.94%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 29        | 0.91%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 24        | 0.75%   |
| Intel HD Graphics 500                                                                    | 23        | 0.72%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 23        | 0.72%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 22        | 0.69%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 20        | 0.63%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 20        | 0.63%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 20        | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 1288      | 46.99%  |
| 1 x AMD         | 731       | 26.67%  |
| 1 x Nvidia      | 301       | 10.98%  |
| Intel + Nvidia  | 219       | 7.99%   |
| Intel + AMD     | 54        | 1.97%   |
| 2 x AMD         | 52        | 1.9%    |
| AMD + Nvidia    | 43        | 1.57%   |
| 2 x Intel       | 13        | 0.47%   |
| 1 x Matrox      | 12        | 0.44%   |
| Other           | 10        | 0.36%   |
| 2 x Nvidia      | 7         | 0.26%   |
| 1 x VIA         | 3         | 0.11%   |
| 1 x ASPEED      | 3         | 0.11%   |
| Nvidia + Matrox | 2         | 0.07%   |
| 3 x AMD         | 1         | 0.04%   |
| 1 x SiS         | 1         | 0.04%   |
| Nvidia + VIA    | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2403      | 87.35%  |
| Proprietary | 280       | 10.18%  |
| Unknown     | 68        | 2.47%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1657      | 59.24%  |
| 0.01-0.5   | 398       | 14.23%  |
| 1.01-2.0   | 268       | 9.58%   |
| 0.51-1.0   | 221       | 7.9%    |
| 3.01-4.0   | 104       | 3.72%   |
| 7.01-8.0   | 67        | 2.4%    |
| 5.01-6.0   | 50        | 1.79%   |
| 2.01-3.0   | 18        | 0.64%   |
| 8.01-16.0  | 10        | 0.36%   |
| 16.01-24.0 | 4         | 0.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 338       | 11.41%  |
| AU Optronics            | 338       | 11.41%  |
| Samsung Electronics     | 318       | 10.73%  |
| Chimei Innolux          | 285       | 9.62%   |
| LG Display              | 263       | 8.88%   |
| Hewlett-Packard         | 215       | 7.26%   |
| Dell                    | 173       | 5.84%   |
| Goldstar                | 110       | 3.71%   |
| Apple                   | 88        | 2.97%   |
| BenQ                    | 80        | 2.7%    |
| Acer                    | 74        | 2.5%    |
| AOC                     | 62        | 2.09%   |
| Lenovo                  | 56        | 1.89%   |
| Chi Mei Optoelectronics | 45        | 1.52%   |
| Unknown                 | 40        | 1.35%   |
| Sony                    | 25        | 0.84%   |
| Sharp                   | 25        | 0.84%   |
| LG Philips              | 25        | 0.84%   |
| Ancor Communications    | 23        | 0.78%   |
| ASUSTek Computer        | 22        | 0.74%   |
| PANDA                   | 21        | 0.71%   |
| Gateway                 | 21        | 0.71%   |
| ViewSonic               | 20        | 0.67%   |
| InfoVision              | 15        | 0.51%   |
| HannStar                | 12        | 0.4%    |
| ___                     | 10        | 0.34%   |
| VOR                     | 9         | 0.3%    |
| Valve                   | 8         | 0.27%   |
| Insignia                | 8         | 0.27%   |
| HUAWEI                  | 8         | 0.27%   |
| FOX                     | 8         | 0.27%   |
| Unknown                 | 8         | 0.27%   |
| Sceptre Tech            | 7         | 0.24%   |
| LG Electronics          | 7         | 0.24%   |
| Hitachi                 | 7         | 0.24%   |
| CSO                     | 7         | 0.24%   |
| Vizio                   | 6         | 0.2%    |
| Unknown (AAA)           | 6         | 0.2%    |
| Toshiba                 | 6         | 0.2%    |
| SAC                     | 6         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 22        | 0.73%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 18        | 0.6%    |
| BOE LCD Monitor BOE076F 1366x768 344x194mm 15.5-inch                 | 17        | 0.56%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 16        | 0.53%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                | 16        | 0.53%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 15        | 0.5%    |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 15        | 0.5%    |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 15        | 0.5%    |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 14        | 0.46%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                | 14        | 0.46%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 14        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 13        | 0.43%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 13        | 0.43%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 12        | 0.4%    |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 12        | 0.4%    |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 12        | 0.4%    |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 11        | 0.36%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch           | 11        | 0.36%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch        | 11        | 0.36%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 10        | 0.33%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 10        | 0.33%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                    | 10        | 0.33%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 10        | 0.33%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 9         | 0.3%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 9         | 0.3%    |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch      | 9         | 0.3%    |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch        | 9         | 0.3%    |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch               | 9         | 0.3%    |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 8         | 0.26%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch | 8         | 0.26%   |
| Goldstar ULTRAWIDE GSM7770 2560x1080 798x334mm 34.1-inch             | 8         | 0.26%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch      | 8         | 0.26%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch      | 8         | 0.26%   |
| Chimei Innolux LCD Monitor CMN1476 1366x768 309x174mm 14.0-inch      | 8         | 0.26%   |
| Unknown                                                              | 8         | 0.26%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 7         | 0.23%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 7         | 0.23%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch         | 7         | 0.23%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch             | 7         | 0.23%   |
| Insignia NS19D220NA16A BBY0019 1680x1050 640x384mm 29.4-inch         | 7         | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 984       | 34.73%  |
| 1920x1080 (FHD)    | 929       | 32.79%  |
| 1600x900 (HD+)     | 125       | 4.41%   |
| 1280x800 (WXGA)    | 111       | 3.92%   |
| 1440x900 (WXGA+)   | 100       | 3.53%   |
| 3840x2160 (4K)     | 88        | 3.11%   |
| 1280x1024 (SXGA)   | 83        | 2.93%   |
| 1680x1050 (WSXGA+) | 40        | 1.41%   |
| 2560x1440 (QHD)    | 39        | 1.38%   |
| 2560x1080          | 32        | 1.13%   |
| 1360x768           | 31        | 1.09%   |
| 1024x768 (XGA)     | 27        | 0.95%   |
| 1024x600           | 27        | 0.95%   |
| 3440x1440          | 23        | 0.81%   |
| 2560x1600          | 23        | 0.81%   |
| 1920x1200 (WUXGA)  | 23        | 0.81%   |
| Unknown            | 22        | 0.78%   |
| 2160x1440          | 19        | 0.67%   |
| 3840x1080          | 10        | 0.35%   |
| 2288x1287          | 10        | 0.35%   |
| 800x1280           | 9         | 0.32%   |
| 2880x1800          | 9         | 0.32%   |
| 1600x1200          | 8         | 0.28%   |
| 2736x1824          | 6         | 0.21%   |
| 3200x1800 (QHD+)   | 5         | 0.18%   |
| 3000x2000          | 5         | 0.18%   |
| 1280x960           | 5         | 0.18%   |
| 3840x2400          | 4         | 0.14%   |
| 2520x1680          | 3         | 0.11%   |
| 3600x1080          | 2         | 0.07%   |
| 3360x1080          | 2         | 0.07%   |
| 2256x1504          | 2         | 0.07%   |
| 2240x1400          | 2         | 0.07%   |
| 1920x540           | 2         | 0.07%   |
| 1400x1050          | 2         | 0.07%   |
| 1280x768           | 2         | 0.07%   |
| 1152x864           | 2         | 0.07%   |
| 7280x2160          | 1         | 0.04%   |
| 6720x1440          | 1         | 0.04%   |
| 6000x1440          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 756       | 25.66%  |
| 13      | 404       | 13.71%  |
| 14      | 313       | 10.62%  |
| 21      | 155       | 5.26%   |
| 23      | 141       | 4.79%   |
| 19      | 115       | 3.9%    |
| 18      | 115       | 3.9%    |
| 17      | 113       | 3.84%   |
| 24      | 107       | 3.63%   |
| 27      | 106       | 3.6%    |
| Unknown | 89        | 3.02%   |
| 20      | 79        | 2.68%   |
| 11      | 67        | 2.27%   |
| 31      | 49        | 1.66%   |
| 34      | 45        | 1.53%   |
| 12      | 43        | 1.46%   |
| 16      | 35        | 1.19%   |
| 22      | 31        | 1.05%   |
| 10      | 28        | 0.95%   |
| 72      | 23        | 0.78%   |
| 84      | 21        | 0.71%   |
| 40      | 14        | 0.48%   |
| 54      | 11        | 0.37%   |
| 32      | 10        | 0.34%   |
| 26      | 9         | 0.31%   |
| 29      | 8         | 0.27%   |
| 7       | 8         | 0.27%   |
| 142     | 7         | 0.24%   |
| 46      | 5         | 0.17%   |
| 25      | 5         | 0.17%   |
| 52      | 4         | 0.14%   |
| 39      | 4         | 0.14%   |
| 8       | 4         | 0.14%   |
| 49      | 2         | 0.07%   |
| 48      | 2         | 0.07%   |
| 42      | 2         | 0.07%   |
| 37      | 2         | 0.07%   |
| 86      | 1         | 0.03%   |
| 74      | 1         | 0.03%   |
| 64      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1365      | 46.94%  |
| 401-500        | 446       | 15.34%  |
| 501-600        | 348       | 11.97%  |
| 201-300        | 284       | 9.77%   |
| 351-400        | 135       | 4.64%   |
| Unknown        | 89        | 3.06%   |
| 601-700        | 64        | 2.2%    |
| 701-800        | 57        | 1.96%   |
| 1501-2000      | 45        | 1.55%   |
| 1001-1500      | 30        | 1.03%   |
| 801-900        | 21        | 0.72%   |
| 1-100          | 9         | 0.31%   |
| More than 2000 | 7         | 0.24%   |
| 101-200        | 4         | 0.14%   |
| 901-1000       | 4         | 0.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2047      | 76.47%  |
| 16/10   | 316       | 11.8%   |
| 5/4     | 82        | 3.06%   |
| Unknown | 70        | 2.61%   |
| 21/9    | 48        | 1.79%   |
| 4/3     | 46        | 1.72%   |
| 3/2     | 40        | 1.49%   |
| 1.00    | 8         | 0.3%    |
| 0.67    | 8         | 0.3%    |
| 6/5     | 4         | 0.15%   |
| 32/9    | 3         | 0.11%   |
| 0.62    | 2         | 0.07%   |
| 0.56    | 2         | 0.07%   |
| 2.65    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 773       | 26.49%  |
| 81-90          | 630       | 21.59%  |
| 201-250        | 355       | 12.17%  |
| 151-200        | 244       | 8.36%   |
| 141-150        | 151       | 5.17%   |
| 301-350        | 113       | 3.87%   |
| 351-500        | 104       | 3.56%   |
| 71-80          | 91        | 3.12%   |
| Unknown        | 89        | 3.05%   |
| More than 1000 | 75        | 2.57%   |
| 51-60          | 68        | 2.33%   |
| 121-130        | 47        | 1.61%   |
| 61-70          | 34        | 1.17%   |
| 251-300        | 34        | 1.17%   |
| 501-1000       | 32        | 1.1%    |
| 41-50          | 27        | 0.93%   |
| 111-120        | 19        | 0.65%   |
| 131-140        | 15        | 0.51%   |
| 1-40           | 13        | 0.45%   |
| 91-100         | 4         | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 1052      | 37.02%  |
| 51-100        | 859       | 30.23%  |
| 121-160       | 593       | 20.87%  |
| 161-240       | 119       | 4.19%   |
| 1-50          | 91        | 3.2%    |
| Unknown       | 89        | 3.13%   |
| More than 240 | 39        | 1.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2248      | 80.54%  |
| 2     | 413       | 14.8%   |
| 0     | 86        | 3.08%   |
| 3     | 40        | 1.43%   |
| 4     | 4         | 0.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 1607      | 39.16%  |
| Intel                                 | 1009      | 24.59%  |
| Qualcomm Atheros                      | 515       | 12.55%  |
| Broadcom                              | 311       | 7.58%   |
| Ralink Technology                     | 80        | 1.95%   |
| Ralink                                | 74        | 1.8%    |
| Broadcom Limited                      | 67        | 1.63%   |
| TP-Link                               | 59        | 1.44%   |
| Nvidia                                | 55        | 1.34%   |
| Marvell Technology Group              | 51        | 1.24%   |
| MediaTek                              | 40        | 0.97%   |
| Qualcomm Atheros Communications       | 35        | 0.85%   |
| ASIX Electronics                      | 21        | 0.51%   |
| Huawei Technologies                   | 20        | 0.49%   |
| Mercucys                              | 13        | 0.32%   |
| Motorola PCS                          | 12        | 0.29%   |
| DisplayLink                           | 12        | 0.29%   |
| Samsung Electronics                   | 11        | 0.27%   |
| Xiaomi                                | 10        | 0.24%   |
| Linksys                               | 7         | 0.17%   |
| Qualcomm                              | 6         | 0.15%   |
| ICS Advent                            | 6         | 0.15%   |
| D-Link                                | 6         | 0.15%   |
| VIA Technologies                      | 5         | 0.12%   |
| OPPO Electronics                      | 5         | 0.12%   |
| Spreadtrum Communications             | 4         | 0.1%    |
| Lenovo                                | 4         | 0.1%    |
| Google                                | 4         | 0.1%    |
| Dell                                  | 4         | 0.1%    |
| D-Link System                         | 4         | 0.1%    |
| NetGear                               | 3         | 0.07%   |
| Microchip Technology                  | 3         | 0.07%   |
| IBM                                   | 3         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.07%   |
| ZTE WCDMA Technologies MSM            | 2         | 0.05%   |
| Wacom                                 | 2         | 0.05%   |
| Microsoft                             | 2         | 0.05%   |
| LG Electronics                        | 2         | 0.05%   |
| JMicron Technology                    | 2         | 0.05%   |
| Tenda                                 | 1         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 936       | 19.02%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 340       | 6.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 118       | 2.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 108       | 2.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 85        | 1.73%   |
| Intel Wi-Fi 6 AX200                                                    | 80        | 1.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 69        | 1.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 68        | 1.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 67        | 1.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 67        | 1.36%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 57        | 1.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 56        | 1.14%   |
| Intel Wireless 8265 / 8275                                             | 53        | 1.08%   |
| Broadcom BCM43142 802.11b/g/n                                          | 51        | 1.04%   |
| Intel Wi-Fi 6 AX201                                                    | 48        | 0.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 47        | 0.95%   |
| Intel Wireless 7265                                                    | 46        | 0.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 42        | 0.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 41        | 0.83%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 40        | 0.81%   |
| Intel Ethernet Connection I217-LM                                      | 39        | 0.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 38        | 0.77%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 36        | 0.73%   |
| Intel Wireless 7260                                                    | 36        | 0.73%   |
| Intel Wireless 8260                                                    | 34        | 0.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 34        | 0.69%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 33        | 0.67%   |
| Intel I211 Gigabit Network Connection                                  | 33        | 0.67%   |
| Realtek RTL8125 2.5GbE Controller                                      | 31        | 0.63%   |
| Intel Wireless 3165                                                    | 31        | 0.63%   |
| Qualcomm Atheros AR9271 802.11n                                        | 30        | 0.61%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 30        | 0.61%   |
| Ralink MT7601U Wireless Adapter                                        | 29        | 0.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 29        | 0.59%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 27        | 0.55%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 26        | 0.53%   |
| Realtek 802.11ac NIC                                                   | 25        | 0.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 24        | 0.49%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 23        | 0.47%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 23        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 739       | 31.02%  |
| Realtek Semiconductor                 | 602       | 25.27%  |
| Qualcomm Atheros                      | 430       | 18.05%  |
| Broadcom                              | 231       | 9.7%    |
| Ralink Technology                     | 80        | 3.36%   |
| Ralink                                | 74        | 3.11%   |
| TP-Link                               | 57        | 2.39%   |
| Broadcom Limited                      | 45        | 1.89%   |
| Qualcomm Atheros Communications       | 35        | 1.47%   |
| MediaTek                              | 35        | 1.47%   |
| Mercucys                              | 13        | 0.55%   |
| Marvell Technology Group              | 7         | 0.29%   |
| D-Link                                | 6         | 0.25%   |
| Linksys                               | 5         | 0.21%   |
| Qualcomm                              | 3         | 0.13%   |
| NetGear                               | 3         | 0.13%   |
| Dell                                  | 3         | 0.13%   |
| D-Link System                         | 3         | 0.13%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.13%   |
| Wacom                                 | 2         | 0.08%   |
| Tenda                                 | 1         | 0.04%   |
| Qualcomm Technologies                 | 1         | 0.04%   |
| Microsoft                             | 1         | 0.04%   |
| Micro Star International              | 1         | 0.04%   |
| Gemtek                                | 1         | 0.04%   |
| Belkin Components                     | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 118       | 4.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 85        | 3.52%   |
| Intel Wi-Fi 6 AX200                                            | 80        | 3.31%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 69        | 2.86%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 68        | 2.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 67        | 2.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 67        | 2.78%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 57        | 2.36%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 56        | 2.32%   |
| Intel Wireless 8265 / 8275                                     | 53        | 2.2%    |
| Broadcom BCM43142 802.11b/g/n                                  | 51        | 2.11%   |
| Intel Wi-Fi 6 AX201                                            | 48        | 1.99%   |
| Intel Wireless 7265                                            | 46        | 1.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 42        | 1.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 41        | 1.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 40        | 1.66%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 38        | 1.57%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 36        | 1.49%   |
| Intel Wireless 7260                                            | 36        | 1.49%   |
| Intel Wireless 8260                                            | 34        | 1.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 34        | 1.41%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 33        | 1.37%   |
| Intel Wireless 3165                                            | 31        | 1.28%   |
| Qualcomm Atheros AR9271 802.11n                                | 30        | 1.24%   |
| Ralink MT7601U Wireless Adapter                                | 29        | 1.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 29        | 1.2%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 27        | 1.12%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 26        | 1.08%   |
| Realtek 802.11ac NIC                                           | 25        | 1.04%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 23        | 0.95%   |
| Intel Wireless 3160                                            | 23        | 0.95%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 22        | 0.91%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 22        | 0.91%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 21        | 0.87%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 20        | 0.83%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 20        | 0.83%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 19        | 0.79%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 19        | 0.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 18        | 0.75%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 18        | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1369      | 55.97%  |
| Intel                                  | 528       | 21.59%  |
| Qualcomm Atheros                       | 150       | 6.13%   |
| Broadcom                               | 132       | 5.4%    |
| Nvidia                                 | 55        | 2.25%   |
| Marvell Technology Group               | 44        | 1.8%    |
| Broadcom Limited                       | 22        | 0.9%    |
| ASIX Electronics                       | 21        | 0.86%   |
| Huawei Technologies                    | 19        | 0.78%   |
| DisplayLink                            | 12        | 0.49%   |
| Samsung Electronics                    | 11        | 0.45%   |
| Xiaomi                                 | 10        | 0.41%   |
| Motorola PCS                           | 8         | 0.33%   |
| ICS Advent                             | 6         | 0.25%   |
| VIA Technologies                       | 5         | 0.2%    |
| OPPO Electronics                       | 5         | 0.2%    |
| MediaTek                               | 5         | 0.2%    |
| Spreadtrum Communications              | 4         | 0.16%   |
| Google                                 | 4         | 0.16%   |
| Qualcomm                               | 3         | 0.12%   |
| Lenovo                                 | 3         | 0.12%   |
| IBM                                    | 3         | 0.12%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.08%   |
| TP-Link                                | 2         | 0.08%   |
| Microchip Technology                   | 2         | 0.08%   |
| Linksys                                | 2         | 0.08%   |
| LG Electronics                         | 2         | 0.08%   |
| JMicron Technology                     | 2         | 0.08%   |
| T & A Mobile Phones                    | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.04%   |
| Microsoft                              | 1         | 0.04%   |
| Lab126                                 | 1         | 0.04%   |
| Insyde Software                        | 1         | 0.04%   |
| HTC (High Tech Computer)               | 1         | 0.04%   |
| Hisense                                | 1         | 0.04%   |
| Foxconn / Hon Hai                      | 1         | 0.04%   |
| Emulex                                 | 1         | 0.04%   |
| Davicom Semiconductor                  | 1         | 0.04%   |
| D-Link System                          | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 936       | 37.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 340       | 13.68%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 108       | 4.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 47        | 1.89%   |
| Intel Ethernet Connection I217-LM                                      | 39        | 1.57%   |
| Intel I211 Gigabit Network Connection                                  | 33        | 1.33%   |
| Realtek RTL8125 2.5GbE Controller                                      | 31        | 1.25%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 30        | 1.21%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 24        | 0.97%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 23        | 0.93%   |
| Nvidia MCP61 Ethernet                                                  | 23        | 0.93%   |
| Intel Ethernet Connection I218-LM                                      | 19        | 0.76%   |
| Intel Ethernet Connection (4) I219-LM                                  | 18        | 0.72%   |
| Intel Ethernet Connection (2) I219-LM                                  | 18        | 0.72%   |
| Intel 82579V Gigabit Network Connection                                | 18        | 0.72%   |
| ASIX AX88179 Gigabit Ethernet                                          | 18        | 0.72%   |
| Intel Ethernet Controller I225-V                                       | 17        | 0.68%   |
| Intel Ethernet Connection (2) I219-V                                   | 17        | 0.68%   |
| Huawei STG-LX1                                                         | 17        | 0.68%   |
| Intel Ethernet Connection (7) I219-V                                   | 15        | 0.6%    |
| Intel Ethernet Connection (3) I218-LM                                  | 15        | 0.6%    |
| Intel 82567LM Gigabit Network Connection                               | 15        | 0.6%    |
| Intel 82577LM Gigabit Network Connection                               | 14        | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 13        | 0.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 13        | 0.52%   |
| Nvidia MCP79 Ethernet                                                  | 13        | 0.52%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 13        | 0.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 12        | 0.48%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 12        | 0.48%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 12        | 0.48%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 12        | 0.48%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 12        | 0.48%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 11        | 0.44%   |
| Intel Ethernet Connection I217-V                                       | 11        | 0.44%   |
| Intel 82574L Gigabit Network Connection                                | 11        | 0.44%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 11        | 0.44%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 10        | 0.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 9         | 0.36%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 9         | 0.36%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 9         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2319      | 50.53%  |
| WiFi     | 2247      | 48.96%  |
| Modem    | 13        | 0.28%   |
| Unknown  | 10        | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1761      | 61.21%  |
| Ethernet | 1114      | 38.72%  |
| Unknown  | 2         | 0.07%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1587      | 58.11%  |
| 1     | 1060      | 38.81%  |
| 0     | 48        | 1.76%   |
| 3     | 23        | 0.84%   |
| 4     | 6         | 0.22%   |
| 8     | 3         | 0.11%   |
| 6     | 3         | 0.11%   |
| 5     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1869      | 66.63%  |
| Yes  | 936       | 33.37%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 564       | 33.98%  |
| Realtek Semiconductor           | 285       | 17.17%  |
| Qualcomm Atheros Communications | 145       | 8.73%   |
| Cambridge Silicon Radio         | 122       | 7.35%   |
| Broadcom                        | 99        | 5.96%   |
| Apple                           | 80        | 4.82%   |
| IMC Networks                    | 66        | 3.98%   |
| Lite-On Technology              | 63        | 3.8%    |
| Foxconn / Hon Hai               | 46        | 2.77%   |
| Dell                            | 33        | 1.99%   |
| Realtek                         | 32        | 1.93%   |
| Hewlett-Packard                 | 24        | 1.45%   |
| Toshiba                         | 22        | 1.33%   |
| Ralink                          | 20        | 1.2%    |
| ASUSTek Computer                | 14        | 0.84%   |
| MediaTek                        | 9         | 0.54%   |
| Ralink Technology               | 7         | 0.42%   |
| Marvell Semiconductor           | 7         | 0.42%   |
| TP-Link                         | 6         | 0.36%   |
| Foxconn International           | 4         | 0.24%   |
| Alps Electric                   | 4         | 0.24%   |
| USI                             | 1         | 0.06%   |
| Roper                           | 1         | 0.06%   |
| Micro Star International        | 1         | 0.06%   |
| Integrated System Solution      | 1         | 0.06%   |
| Fujitsu                         | 1         | 0.06%   |
| Dynex                           | 1         | 0.06%   |
| Chicony Electronics             | 1         | 0.06%   |
| Unknown                         | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 214       | 12.88%  |
| Realtek Bluetooth Radio                                                             | 144       | 8.66%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 122       | 7.34%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 115       | 6.92%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 99        | 5.96%   |
| Intel AX201 Bluetooth                                                               | 93        | 5.6%    |
| Intel AX200 Bluetooth                                                               | 78        | 4.69%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 72        | 4.33%   |
| Apple Bluetooth Host Controller                                                     | 37        | 2.23%   |
| Intel Bluetooth Device                                                              | 35        | 2.11%   |
| IMC Networks Bluetooth Radio                                                        | 33        | 1.99%   |
| Realtek Bluetooth Radio                                                             | 32        | 1.93%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 29        | 1.74%   |
| Apple Bluetooth USB Host Controller                                                 | 24        | 1.44%   |
| Lite-On Bluetooth Device                                                            | 22        | 1.32%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 21        | 1.26%   |
| Ralink RT3290 Bluetooth                                                             | 20        | 1.2%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 19        | 1.14%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 18        | 1.08%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 18        | 1.08%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 18        | 1.08%   |
| Realtek RTL8723B Bluetooth                                                          | 16        | 0.96%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 16        | 0.96%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 15        | 0.9%    |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 14        | 0.84%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 13        | 0.78%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 12        | 0.72%   |
| IMC Networks Wireless_Device                                                        | 11        | 0.66%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 11        | 0.66%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 11        | 0.66%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 11        | 0.66%   |
| Intel AX210 Bluetooth                                                               | 10        | 0.6%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 10        | 0.6%    |
| MediaTek Wireless_Device                                                            | 9         | 0.54%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 9         | 0.54%   |
| IMC Networks Bluetooth Device                                                       | 9         | 0.54%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 9         | 0.54%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 8         | 0.48%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 8         | 0.48%   |
| Apple Bluetooth HCI                                                                 | 8         | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1810      | 53.66%  |
| AMD                                          | 883       | 26.18%  |
| Nvidia                                       | 444       | 13.16%  |
| C-Media Electronics                          | 31        | 0.92%   |
| Logitech                                     | 22        | 0.65%   |
| Generalplus Technology                       | 19        | 0.56%   |
| Texas Instruments                            | 17        | 0.5%    |
| Realtek Semiconductor                        | 9         | 0.27%   |
| Creative Labs                                | 9         | 0.27%   |
| Kingston Technology                          | 8         | 0.24%   |
| JMTek                                        | 8         | 0.24%   |
| GN Netcom                                    | 8         | 0.24%   |
| ASUSTek Computer                             | 8         | 0.24%   |
| VIA Technologies                             | 7         | 0.21%   |
| Corsair                                      | 7         | 0.21%   |
| Razer USA                                    | 6         | 0.18%   |
| Plantronics                                  | 6         | 0.18%   |
| Tenx Technology                              | 5         | 0.15%   |
| Lenovo                                       | 5         | 0.15%   |
| Syntek                                       | 4         | 0.12%   |
| Focusrite-Novation                           | 4         | 0.12%   |
| Creative Technology                          | 4         | 0.12%   |
| BR23                                         | 3         | 0.09%   |
| Apple                                        | 3         | 0.09%   |
| Thesycon Systemsoftware & Consulting         | 2         | 0.06%   |
| Synaptics                                    | 2         | 0.06%   |
| SAVITECH                                     | 2         | 0.06%   |
| Samson Technologies                          | 2         | 0.06%   |
| Microsoft                                    | 2         | 0.06%   |
| M-Audio                                      | 2         | 0.06%   |
| KTMicro                                      | 2         | 0.06%   |
| ATI Technologies                             | 2         | 0.06%   |
| Anlya.cn                                     | 2         | 0.06%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.03%   |
| Yamaha                                       | 1         | 0.03%   |
| USB-MIC                                      | 1         | 0.03%   |
| Sony                                         | 1         | 0.03%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.03%   |
| Shure                                        | 1         | 0.03%   |
| Sennheiser Communications                    | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 277       | 6.54%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 195       | 4.61%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 177       | 4.18%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 174       | 4.11%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 153       | 3.61%   |
| AMD FCH Azalia Controller                                                                         | 151       | 3.57%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 118       | 2.79%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 116       | 2.74%   |
| AMD Kabini HDMI/DP Audio                                                                          | 101       | 2.39%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 98        | 2.31%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 98        | 2.31%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 96        | 2.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 81        | 1.91%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 77        | 1.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 74        | 1.75%   |
| Intel Cannon Lake PCH cAVS                                                                        | 73        | 1.72%   |
| Intel 8 Series HD Audio Controller                                                                | 72        | 1.7%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 71        | 1.68%   |
| Intel Broadwell-U Audio Controller                                                                | 65        | 1.54%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 64        | 1.51%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 63        | 1.49%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 58        | 1.37%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 58        | 1.37%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 58        | 1.37%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 55        | 1.3%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 55        | 1.3%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 52        | 1.23%   |
| AMD High Definition Audio Controller                                                              | 52        | 1.23%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 41        | 0.97%   |
| AMD Trinity HDMI Audio Controller                                                                 | 41        | 0.97%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 41        | 0.97%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 39        | 0.92%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 38        | 0.9%    |
| Intel Comet Lake PCH cAVS                                                                         | 37        | 0.87%   |
| Intel 200 Series PCH HD Audio                                                                     | 30        | 0.71%   |
| Nvidia MCP61 High Definition Audio                                                                | 29        | 0.68%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 29        | 0.68%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 28        | 0.66%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 28        | 0.66%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 27        | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 380       | 22.74%  |
| SK hynix                                         | 290       | 17.35%  |
| Kingston                                         | 266       | 15.92%  |
| Micron Technology                                | 183       | 10.95%  |
| A-DATA Technology                                | 136       | 8.14%   |
| Unknown                                          | 128       | 7.66%   |
| Corsair                                          | 46        | 2.75%   |
| Ramaxel Technology                               | 44        | 2.63%   |
| Crucial                                          | 36        | 2.15%   |
| Elpida                                           | 29        | 1.74%   |
| Nanya Technology                                 | 24        | 1.44%   |
| Unknown (ABCD)                                   | 15        | 0.9%    |
| Team                                             | 15        | 0.9%    |
| Patriot                                          | 9         | 0.54%   |
| Qimonda                                          | 7         | 0.42%   |
| PNY                                              | 7         | 0.42%   |
| Unknown                                          | 7         | 0.42%   |
| G.Skill                                          | 6         | 0.36%   |
| ChangXin Memory                                  | 6         | 0.36%   |
| Timetec                                          | 5         | 0.3%    |
| Transcend                                        | 4         | 0.24%   |
| Hewlett-Packard                                  | 2         | 0.12%   |
| CSX                                              | 2         | 0.12%   |
| Avant                                            | 2         | 0.12%   |
| Unknown (8A6B)                                   | 1         | 0.06%   |
| Unknown (0x8AF1)                                 | 1         | 0.06%   |
| Unknown (0x4D342037305435363633515A332D43453620) | 1         | 0.06%   |
| Unknown (0x29E)                                  | 1         | 0.06%   |
| Unknown (0x0E9D)                                 | 1         | 0.06%   |
| Unifosa                                          | 1         | 0.06%   |
| Silicon Power                                    | 1         | 0.06%   |
| SHARETRONIC                                      | 1         | 0.06%   |
| SGS/Thomson                                      | 1         | 0.06%   |
| S                                                | 1         | 0.06%   |
| Patriot Memory                                   | 1         | 0.06%   |
| MKF_SMBIOS_TYPE17_MANUFACTURER                   | 1         | 0.06%   |
| Goldkey                                          | 1         | 0.06%   |
| Gigabyte Technology                              | 1         | 0.06%   |
| ff                                               | 1         | 0.06%   |
| ASint Technology                                 | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 27        | 1.49%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                         | 20        | 1.1%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 19        | 1.05%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s          | 18        | 0.99%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 15        | 0.83%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 14        | 0.77%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 14        | 0.77%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 13        | 0.72%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 12        | 0.66%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 12        | 0.66%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 12        | 0.66%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 11        | 0.61%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 11        | 0.61%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 11        | 0.61%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s            | 11        | 0.61%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 10        | 0.55%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s                 | 10        | 0.55%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 9         | 0.5%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 9         | 0.5%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 9         | 0.5%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 8         | 0.44%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 8         | 0.44%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 8         | 0.44%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 8         | 0.44%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 8         | 0.44%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 8         | 0.44%   |
| Kingston RAM 99U5428-018.A00LF 8192MB SODIMM DDR3 1600MT/s          | 8         | 0.44%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 7         | 0.39%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 7         | 0.39%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s         | 7         | 0.39%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 7         | 0.39%   |
| Unknown                                                             | 7         | 0.39%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                           | 6         | 0.33%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                | 6         | 0.33%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s              | 6         | 0.33%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 6         | 0.33%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 6         | 0.33%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 6         | 0.33%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s               | 6         | 0.33%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 6         | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 587       | 42.38%  |
| DDR3    | 516       | 37.26%  |
| DDR2    | 92        | 6.64%   |
| LPDDR4  | 47        | 3.39%   |
| SDRAM   | 44        | 3.18%   |
| Unknown | 30        | 2.17%   |
| LPDDR3  | 29        | 2.09%   |
| DDR5    | 16        | 1.16%   |
| DDR     | 13        | 0.94%   |
| LPDDR5  | 9         | 0.65%   |
| RAM     | 1         | 0.07%   |
| DRAM    | 1         | 0.07%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 822       | 60%     |
| DIMM         | 418       | 30.51%  |
| Row Of Chips | 119       | 8.69%   |
| Chip         | 5         | 0.36%   |
| Unknown      | 3         | 0.22%   |
| RIMM         | 2         | 0.15%   |
| FB-DIMM      | 1         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 553       | 35.11%  |
| 4096  | 475       | 30.16%  |
| 2048  | 243       | 15.43%  |
| 16384 | 154       | 9.78%   |
| 1024  | 72        | 4.57%   |
| 32768 | 63        | 4%      |
| 512   | 9         | 0.57%   |
| 256   | 2         | 0.13%   |
| 65536 | 1         | 0.06%   |
| 32767 | 1         | 0.06%   |
| 12288 | 1         | 0.06%   |
| 128   | 1         | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 348       | 22.64%  |
| 2667    | 219       | 14.25%  |
| 3200    | 184       | 11.97%  |
| 1333    | 112       | 7.29%   |
| 2400    | 96        | 6.25%   |
| 2133    | 72        | 4.68%   |
| 667     | 51        | 3.32%   |
| 3600    | 48        | 3.12%   |
| 1334    | 48        | 3.12%   |
| 800     | 38        | 2.47%   |
| Unknown | 32        | 2.08%   |
| 3266    | 27        | 1.76%   |
| 1067    | 22        | 1.43%   |
| 3733    | 20        | 1.3%    |
| 4267    | 19        | 1.24%   |
| 1867    | 19        | 1.24%   |
| 1866    | 14        | 0.91%   |
| 2048    | 13        | 0.85%   |
| 533     | 13        | 0.85%   |
| 1066    | 12        | 0.78%   |
| 4800    | 10        | 0.65%   |
| 6400    | 8         | 0.52%   |
| 975     | 8         | 0.52%   |
| 3466    | 7         | 0.46%   |
| 3400    | 7         | 0.46%   |
| 3000    | 7         | 0.46%   |
| 4199    | 6         | 0.39%   |
| 2666    | 6         | 0.39%   |
| 8400    | 5         | 0.33%   |
| 49926   | 4         | 0.26%   |
| 5600    | 4         | 0.26%   |
| 3933    | 4         | 0.26%   |
| 3800    | 4         | 0.26%   |
| 3066    | 4         | 0.26%   |
| 2800    | 4         | 0.26%   |
| 1800    | 4         | 0.26%   |
| 1331    | 4         | 0.26%   |
| 2933    | 3         | 0.2%    |
| 2200    | 3         | 0.2%    |
| 1639    | 3         | 0.2%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Seiko Epson            | 16        | 24.62%  |
| Hewlett-Packard        | 16        | 24.62%  |
| Brother Industries     | 14        | 21.54%  |
| Samsung Electronics    | 7         | 10.77%  |
| Canon                  | 7         | 10.77%  |
| Kyocera                | 2         | 3.08%   |
| TSC Auto ID Technology | 1         | 1.54%   |
| QinHeng Electronics    | 1         | 1.54%   |
| BIXOLON                | 1         | 1.54%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Seiko Epson L120 Series                 | 6         | 9.09%   |
| HP DeskJet 1110 series                  | 3         | 4.55%   |
| Samsung M2020 Series                    | 2         | 3.03%   |
| HP LaserJet Professional P 1102w        | 2         | 3.03%   |
| HP DeskJet 2300 series                  | 2         | 3.03%   |
| Canon G3000 series                      | 2         | 3.03%   |
| Brother MFC-J470DW                      | 2         | 3.03%   |
| Brother MFC-J460DW                      | 2         | 3.03%   |
| Brother HL-1110 series                  | 2         | 3.03%   |
| TSC Auto ID Printer                     | 1         | 1.52%   |
| Seiko Epson XP-235 Series               | 1         | 1.52%   |
| Seiko Epson Printer                     | 1         | 1.52%   |
| Seiko Epson L805 Series                 | 1         | 1.52%   |
| Seiko Epson L6160 Series                | 1         | 1.52%   |
| Seiko Epson L555 Series                 | 1         | 1.52%   |
| Seiko Epson L382 Series                 | 1         | 1.52%   |
| Seiko Epson L300 Series                 | 1         | 1.52%   |
| Seiko Epson L210 Series                 | 1         | 1.52%   |
| Seiko Epson L200 Series                 | 1         | 1.52%   |
| Seiko Epson L1300 Series                | 1         | 1.52%   |
| Seiko Epson ET-2700 Series              | 1         | 1.52%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 1.52%   |
| Samsung SCX-4600 Series                 | 1         | 1.52%   |
| Samsung ML-1660 Series                  | 1         | 1.52%   |
| Samsung ML-1640 Series Laser Printer    | 1         | 1.52%   |
| Samsung M283x Series                    | 1         | 1.52%   |
| QinHeng CH340S                          | 1         | 1.52%   |
| Kyocera FS-1116MFP                      | 1         | 1.52%   |
| Kyocera FS-1030D printer                | 1         | 1.52%   |
| HP OfficeJet Pro 7740 series            | 1         | 1.52%   |
| HP LaserJet P3010 Series                | 1         | 1.52%   |
| HP LaserJet 1018                        | 1         | 1.52%   |
| HP DeskJet F4200 series                 | 1         | 1.52%   |
| HP DeskJet F300 series                  | 1         | 1.52%   |
| HP DeskJet 4720 series                  | 1         | 1.52%   |
| HP DeskJet 3700 series                  | 1         | 1.52%   |
| HP DeskJet 2600 series                  | 1         | 1.52%   |
| HP Deskjet 2540 series                  | 1         | 1.52%   |
| Canon PIXMA MG3500 Series               | 1         | 1.52%   |
| Canon PIXMA iP3000x Printer             | 1         | 1.52%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 5         | 83.33%  |
| Seiko Epson     | 1         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| HP ScanJet 5590                                    | 2         | 33.33%  |
| HP ScanJet 4500C/5550C                             | 2         | 33.33%  |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO] | 1         | 16.67%  |
| HP ScanJet 3300c                                   | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 385       | 21.03%  |
| IMC Networks                           | 170       | 9.28%   |
| Microdia                               | 166       | 9.07%   |
| Realtek Semiconductor                  | 123       | 6.72%   |
| Cheng Uei Precision Industry (Foxlink) | 93        | 5.08%   |
| Sunplus Innovation Technology          | 89        | 4.86%   |
| Quanta                                 | 80        | 4.37%   |
| Bison Electronics                      | 79        | 4.31%   |
| Suyin                                  | 72        | 3.93%   |
| Apple                                  | 67        | 3.66%   |
| Logitech                               | 65        | 3.55%   |
| Syntek                                 | 59        | 3.22%   |
| Lite-On Technology                     | 46        | 2.51%   |
| Acer                                   | 31        | 1.69%   |
| Generalplus Technology                 | 28        | 1.53%   |
| Silicon Motion                         | 23        | 1.26%   |
| Ricoh                                  | 23        | 1.26%   |
| Importek                               | 20        | 1.09%   |
| Alcor Micro                            | 18        | 0.98%   |
| Luxvisions Innotech Limited            | 16        | 0.87%   |
| Microsoft                              | 15        | 0.82%   |
| Z-Star Microelectronics                | 11        | 0.6%    |
| Samsung Electronics                    | 11        | 0.6%    |
| Jieli Technology                       | 11        | 0.6%    |
| Primax Electronics                     | 9         | 0.49%   |
| Y Media                                | 8         | 0.44%   |
| Sonix Technology                       | 8         | 0.44%   |
| GEMBIRD                                | 8         | 0.44%   |
| ALi                                    | 8         | 0.44%   |
| OmniVision Technologies                | 7         | 0.38%   |
| HRY                                    | 6         | 0.33%   |
| Genesys Logic                          | 6         | 0.33%   |
| KYE Systems (Mouse Systems)            | 5         | 0.27%   |
| USB Camera                             | 4         | 0.22%   |
| MacroSilicon                           | 4         | 0.22%   |
| LG Electronics                         | 4         | 0.22%   |
| Lenovo                                 | 4         | 0.22%   |
| Xiongmai                               | 3         | 0.16%   |
| SunplusIT                              | 3         | 0.16%   |
| Sunplus Technology                     | 3         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 55        | 2.98%   |
| Microdia Integrated_Webcam_HD                                  | 52        | 2.82%   |
| Chicony HD WebCam                                              | 42        | 2.28%   |
| IMC Networks Integrated Camera                                 | 37        | 2.01%   |
| Realtek Integrated_Webcam_HD                                   | 36        | 1.95%   |
| Bison Integrated Camera                                        | 30        | 1.63%   |
| Sunplus Integrated_Webcam_HD                                   | 28        | 1.52%   |
| IMC Networks HD Camera                                         | 25        | 1.36%   |
| Generalplus GENERAL WEBCAM                                     | 25        | 1.36%   |
| Logitech HD Pro Webcam C920                                    | 24        | 1.3%    |
| IMC Networks USB2.0 VGA UVC WebCam                             | 24        | 1.3%    |
| Syntek Integrated Camera                                       | 23        | 1.25%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 23        | 1.25%   |
| Chicony HP Webcam                                              | 23        | 1.25%   |
| Apple FaceTime HD Camera                                       | 23        | 1.25%   |
| Chicony HP TrueVision HD Camera                                | 22        | 1.19%   |
| Quanta HP Webcam                                               | 18        | 0.98%   |
| Lite-On HP Wide Vision HD Camera                               | 18        | 0.98%   |
| Chicony HP Truevision HD                                       | 18        | 0.98%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera               | 18        | 0.98%   |
| Microdia Integrated Webcam                                     | 17        | 0.92%   |
| Syntek Lenovo EasyCamera                                       | 16        | 0.87%   |
| IMC Networks EasyCamera                                        | 16        | 0.87%   |
| Apple Built-in iSight                                          | 15        | 0.81%   |
| IMC Networks ov9734_azurewave_camera                           | 14        | 0.76%   |
| Chicony USB 2.0 Camera                                         | 14        | 0.76%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 14        | 0.76%   |
| Sunplus HD WebCam                                              | 13        | 0.71%   |
| Logitech Webcam C270                                           | 13        | 0.71%   |
| Apple FaceTime HD Camera (Built-in)                            | 13        | 0.71%   |
| Realtek USB Camera                                             | 12        | 0.65%   |
| Quanta HP TrueVision HD Camera                                 | 12        | 0.65%   |
| Microdia Lenovo EasyCamera                                     | 12        | 0.65%   |
| Chicony HP Wide Vision HD Camera                               | 12        | 0.65%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 12        | 0.65%   |
| Acer Integrated Camera                                         | 12        | 0.65%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 11        | 0.6%    |
| Jieli USB PHY 2.0                                              | 11        | 0.6%    |
| Chicony HP HD Camera                                           | 11        | 0.6%    |
| Chicony HD User Facing                                         | 11        | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 96        | 31.68%  |
| Shenzhen Goodix Technology         | 76        | 25.08%  |
| Synaptics                          | 51        | 16.83%  |
| AuthenTec                          | 25        | 8.25%   |
| Upek                               | 18        | 5.94%   |
| Elan Microelectronics              | 14        | 4.62%   |
| Focal-systems.Corp                 | 8         | 2.64%   |
| STMicroelectronics                 | 5         | 1.65%   |
| LighTuning Technology              | 4         | 1.32%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.66%   |
| Suprema                            | 1         | 0.33%   |
| Samsung Electronics                | 1         | 0.33%   |
| GDMicroelectronics                 | 1         | 0.33%   |
| DigitalPersona                     | 1         | 0.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 65        | 21.45%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 21        | 6.93%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 18        | 5.94%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 16        | 5.28%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 13        | 4.29%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 13        | 4.29%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 13        | 4.29%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 12        | 3.96%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 10        | 3.3%    |
| Shenzhen Goodix Fingerprint Reader                                         | 10        | 3.3%    |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 8         | 2.64%   |
| Elan ELAN:Fingerprint                                                      | 7         | 2.31%   |
| Elan ELAN:ARM-M4                                                           | 7         | 2.31%   |
| Validity Sensors VFS491                                                    | 6         | 1.98%   |
| AuthenTec AES2810                                                          | 6         | 1.98%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.65%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 1.65%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 1.65%   |
| STMicroelectronics Fingerprint Reader                                      | 5         | 1.65%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 1.32%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 1.32%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 1.32%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 0.99%   |
| Synaptics WBDI                                                             | 3         | 0.99%   |
| Synaptics Fingerprint reader [HP G6]                                       | 3         | 0.99%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 0.99%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.99%   |
| AuthenTec AES1600                                                          | 3         | 0.99%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.66%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.66%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.66%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.66%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.66%   |
| Synaptics UWP WBDI                                                         | 2         | 0.66%   |
| Synaptics  WBDI                                                            | 2         | 0.66%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 0.66%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.66%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.33%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.33%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 52        | 64.2%   |
| Alcor Micro           | 13        | 16.05%  |
| Upek                  | 8         | 9.88%   |
| Lenovo                | 6         | 7.41%   |
| O2 Micro              | 1         | 1.23%   |
| Gemalto (was Gemplus) | 1         | 1.23%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 20        | 24.69%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 14        | 17.28%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 13        | 16.05%  |
| Broadcom 5880                                                                | 10        | 12.35%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 9.88%   |
| Broadcom 58200                                                               | 7         | 8.64%   |
| Lenovo Integrated Smart Card Reader                                          | 6         | 7.41%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 1.23%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.23%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 1.23%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1926      | 69.23%  |
| 1     | 711       | 25.56%  |
| 2     | 123       | 4.42%   |
| 3     | 14        | 0.5%    |
| 5     | 3         | 0.11%   |
| 6     | 2         | 0.07%   |
| 8     | 1         | 0.04%   |
| 7     | 1         | 0.04%   |
| 4     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 300       | 29.67%  |
| Graphics card            | 198       | 19.58%  |
| Net/wireless             | 167       | 16.52%  |
| Chipcard                 | 77        | 7.62%   |
| Multimedia controller    | 75        | 7.42%   |
| Communication controller | 46        | 4.55%   |
| Bluetooth                | 33        | 3.26%   |
| Camera                   | 32        | 3.17%   |
| Unassigned class         | 15        | 1.48%   |
| Net/ethernet             | 13        | 1.29%   |
| Storage                  | 12        | 1.19%   |
| Sound                    | 12        | 1.19%   |
| Card reader              | 7         | 0.69%   |
| Network                  | 6         | 0.59%   |
| Modem                    | 6         | 0.59%   |
| Storage/raid             | 3         | 0.3%    |
| Storage/ide              | 2         | 0.2%    |
| Firewire controller      | 2         | 0.2%    |
| Video                    | 1         | 0.1%    |
| Tv card                  | 1         | 0.1%    |
| Storage/nvme             | 1         | 0.1%    |
| Storage/ata              | 1         | 0.1%    |
| Dvb card                 | 1         | 0.1%    |

