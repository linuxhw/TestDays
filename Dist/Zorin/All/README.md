Zorin - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for Zorin.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Zorin/Desktop/README.md) and [notebooks](/Dist/Zorin/Notebook/README.md).

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

Total: 7555

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | K50IJ                       | Notebook    | [8262209249](https://linux-hardware.org/?probe=8262209249) | Jun 30, 2023 |
| Dell          | Latitude E6400              | Notebook    | [c8f88ff5b6](https://linux-hardware.org/?probe=c8f88ff5b6) | Jun 30, 2023 |
| HP            | Pro x2 612 G2               | Tablet      | [e47898dc3d](https://linux-hardware.org/?probe=e47898dc3d) | Jun 29, 2023 |
| MSI           | H61M-P31                    | Desktop     | [9012219f61](https://linux-hardware.org/?probe=9012219f61) | Jun 29, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [bb1cb1ef13](https://linux-hardware.org/?probe=bb1cb1ef13) | Jun 29, 2023 |
| Gigabyte      | P31-DS3L                    | Desktop     | [0d32728bdf](https://linux-hardware.org/?probe=0d32728bdf) | Jun 28, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [b4fcb0d0c0](https://linux-hardware.org/?probe=b4fcb0d0c0) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [9d6748ef56](https://linux-hardware.org/?probe=9d6748ef56) | Jun 28, 2023 |
| HP            | ENVY m6                     | Notebook    | [715d68bfc0](https://linux-hardware.org/?probe=715d68bfc0) | Jun 28, 2023 |
| Dell          | Latitude E6400              | Notebook    | [0f9255924f](https://linux-hardware.org/?probe=0f9255924f) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [64433a8783](https://linux-hardware.org/?probe=64433a8783) | Jun 27, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [663ce69f30](https://linux-hardware.org/?probe=663ce69f30) | Jun 27, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [73eab89788](https://linux-hardware.org/?probe=73eab89788) | Jun 27, 2023 |
| Lenovo        | V110-15IKB 80TH             | Notebook    | [e6b9f96475](https://linux-hardware.org/?probe=e6b9f96475) | Jun 27, 2023 |
| HP            | Pavilion dv6700             | Notebook    | [182bf6e4a7](https://linux-hardware.org/?probe=182bf6e4a7) | Jun 27, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20DA50... | Notebook    | [b756e54029](https://linux-hardware.org/?probe=b756e54029) | Jun 27, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [0a35c3c750](https://linux-hardware.org/?probe=0a35c3c750) | Jun 27, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [18ab778722](https://linux-hardware.org/?probe=18ab778722) | Jun 26, 2023 |
| Lenovo        | ThinkCentre M91p 4524WAP    | Desktop     | [85eeeb037b](https://linux-hardware.org/?probe=85eeeb037b) | Jun 26, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [da86501858](https://linux-hardware.org/?probe=da86501858) | Jun 26, 2023 |
| Dell          | Latitude 3189               | Notebook    | [ad7c98c905](https://linux-hardware.org/?probe=ad7c98c905) | Jun 26, 2023 |
| Dell          | Latitude 3189               | Notebook    | [8547503af5](https://linux-hardware.org/?probe=8547503af5) | Jun 25, 2023 |
| Dell          | Latitude 3189               | Notebook    | [3f44430a36](https://linux-hardware.org/?probe=3f44430a36) | Jun 25, 2023 |
| Lenovo        | ThinkPad E560 20EV000UIX    | Notebook    | [ac6bd9497a](https://linux-hardware.org/?probe=ac6bd9497a) | Jun 25, 2023 |
| Toshiba       | Satellite U400              | Notebook    | [58b2ad81eb](https://linux-hardware.org/?probe=58b2ad81eb) | Jun 25, 2023 |
| Acer          | Aspire M3-581G              | Notebook    | [0c348c2570](https://linux-hardware.org/?probe=0c348c2570) | Jun 25, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [2d7e4f3505](https://linux-hardware.org/?probe=2d7e4f3505) | Jun 24, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [8112b061f0](https://linux-hardware.org/?probe=8112b061f0) | Jun 24, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [be14b80f2c](https://linux-hardware.org/?probe=be14b80f2c) | Jun 24, 2023 |
| Positivo      | POS-AG31AP                  | Desktop     | [bd3b3228c6](https://linux-hardware.org/?probe=bd3b3228c6) | Jun 24, 2023 |
| Intel         | D946GZIS AAD66165-301       | Desktop     | [dac65b1c2c](https://linux-hardware.org/?probe=dac65b1c2c) | Jun 24, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [23134d6c71](https://linux-hardware.org/?probe=23134d6c71) | Jun 24, 2023 |
| Dell          | Latitude E6400              | Notebook    | [74be208929](https://linux-hardware.org/?probe=74be208929) | Jun 24, 2023 |
| ASUSTek       | P5B                         | Desktop     | [a62968d622](https://linux-hardware.org/?probe=a62968d622) | Jun 24, 2023 |
| Acer          | AOD270                      | Notebook    | [af596f2c11](https://linux-hardware.org/?probe=af596f2c11) | Jun 24, 2023 |
| Acer          | AOD270                      | Notebook    | [d3204f80d5](https://linux-hardware.org/?probe=d3204f80d5) | Jun 24, 2023 |
| Toshiba       | Satellite U400              | Notebook    | [aa6254ebd2](https://linux-hardware.org/?probe=aa6254ebd2) | Jun 24, 2023 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [011552703c](https://linux-hardware.org/?probe=011552703c) | Jun 24, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0JA... | Tablet      | [1773c81302](https://linux-hardware.org/?probe=1773c81302) | Jun 23, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0JA... | Tablet      | [80b535ff26](https://linux-hardware.org/?probe=80b535ff26) | Jun 23, 2023 |
| HP            | EliteBook 8560p             | Notebook    | [177d2fe509](https://linux-hardware.org/?probe=177d2fe509) | Jun 22, 2023 |
| Positivo      | POS-AG31AP                  | Desktop     | [1dd704fab9](https://linux-hardware.org/?probe=1dd704fab9) | Jun 22, 2023 |
| Google        | Kefka                       | Notebook    | [2580ed90ee](https://linux-hardware.org/?probe=2580ed90ee) | Jun 22, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [ae8c13c6fd](https://linux-hardware.org/?probe=ae8c13c6fd) | Jun 22, 2023 |
| Dell          | 0G9322                      | Desktop     | [a742a26282](https://linux-hardware.org/?probe=a742a26282) | Jun 22, 2023 |
| AZW           | SER                         | Mini pc     | [9ef166eb46](https://linux-hardware.org/?probe=9ef166eb46) | Jun 22, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [1e11366a3e](https://linux-hardware.org/?probe=1e11366a3e) | Jun 21, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [3d558ea9aa](https://linux-hardware.org/?probe=3d558ea9aa) | Jun 21, 2023 |
| Dell          | Vostro 5481                 | Notebook    | [b28f58f09e](https://linux-hardware.org/?probe=b28f58f09e) | Jun 20, 2023 |
| Intel         | D34010WYK H14771-304        | Desktop     | [0d3af8114b](https://linux-hardware.org/?probe=0d3af8114b) | Jun 20, 2023 |
| HP            | ENVY m6                     | Notebook    | [ea4c3aca13](https://linux-hardware.org/?probe=ea4c3aca13) | Jun 20, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [72ef7ff0aa](https://linux-hardware.org/?probe=72ef7ff0aa) | Jun 20, 2023 |
| Dell          | G7 7588                     | Notebook    | [946a645897](https://linux-hardware.org/?probe=946a645897) | Jun 20, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [88d7f8992f](https://linux-hardware.org/?probe=88d7f8992f) | Jun 19, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [93587f51a9](https://linux-hardware.org/?probe=93587f51a9) | Jun 19, 2023 |
| Sony          | VPCCA15FX                   | Notebook    | [ed7dba1a4c](https://linux-hardware.org/?probe=ed7dba1a4c) | Jun 19, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [bc371b62c9](https://linux-hardware.org/?probe=bc371b62c9) | Jun 19, 2023 |
| Sony          | VPCCA15FX                   | Notebook    | [c5660d0020](https://linux-hardware.org/?probe=c5660d0020) | Jun 19, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [8086cf1231](https://linux-hardware.org/?probe=8086cf1231) | Jun 19, 2023 |
| Lenovo        | ThinkPad T440 20B7S0VA05    | Notebook    | [307c8a76ab](https://linux-hardware.org/?probe=307c8a76ab) | Jun 19, 2023 |
| AZW           | GTR V02                     | Desktop     | [f9bee18426](https://linux-hardware.org/?probe=f9bee18426) | Jun 19, 2023 |
| GPU Compan... | GWNC21524                   | Notebook    | [46bd956cbf](https://linux-hardware.org/?probe=46bd956cbf) | Jun 19, 2023 |
| Toshiba       | TECRA M10                   | Notebook    | [37f232dce0](https://linux-hardware.org/?probe=37f232dce0) | Jun 19, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [7546cac791](https://linux-hardware.org/?probe=7546cac791) | Jun 19, 2023 |
| ASUSTek       | P5LD2                       | Desktop     | [7038963b77](https://linux-hardware.org/?probe=7038963b77) | Jun 18, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [e1fc794bc5](https://linux-hardware.org/?probe=e1fc794bc5) | Jun 18, 2023 |
| ASUSTek       | VivoBook S13 X330FA_S330... | Notebook    | [b816a11527](https://linux-hardware.org/?probe=b816a11527) | Jun 18, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [8247e349fc](https://linux-hardware.org/?probe=8247e349fc) | Jun 17, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [bb6859a141](https://linux-hardware.org/?probe=bb6859a141) | Jun 17, 2023 |
| HP            | ProBook 650 G5              | Notebook    | [1d158627b0](https://linux-hardware.org/?probe=1d158627b0) | Jun 17, 2023 |
| Dell          | Latitude 7370               | Notebook    | [5c2378adc5](https://linux-hardware.org/?probe=5c2378adc5) | Jun 17, 2023 |
| Dell          | Latitude 7370               | Notebook    | [44dba24aed](https://linux-hardware.org/?probe=44dba24aed) | Jun 17, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [3614dc460e](https://linux-hardware.org/?probe=3614dc460e) | Jun 17, 2023 |
| Lenovo        | ThinkCentre M91p 4524WAP    | Desktop     | [707e7d9862](https://linux-hardware.org/?probe=707e7d9862) | Jun 17, 2023 |
| HP            | Laptop 14-bw0xx             | Notebook    | [f38253d79c](https://linux-hardware.org/?probe=f38253d79c) | Jun 17, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [7d9f25dc5f](https://linux-hardware.org/?probe=7d9f25dc5f) | Jun 17, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [a2bbc6abd3](https://linux-hardware.org/?probe=a2bbc6abd3) | Jun 17, 2023 |
| Haier         | Y11B                        | Notebook    | [0c2abeea6e](https://linux-hardware.org/?probe=0c2abeea6e) | Jun 17, 2023 |
| HP            | ProBook 650 G5              | Notebook    | [9c53e4cd72](https://linux-hardware.org/?probe=9c53e4cd72) | Jun 17, 2023 |
| HP            | G62                         | Notebook    | [2e1e964887](https://linux-hardware.org/?probe=2e1e964887) | Jun 16, 2023 |
| Acer          | Aspire V5-571P              | Notebook    | [2adeb26f8a](https://linux-hardware.org/?probe=2adeb26f8a) | Jun 15, 2023 |
| eMachines     | eMD728                      | Notebook    | [85dd880b0d](https://linux-hardware.org/?probe=85dd880b0d) | Jun 15, 2023 |
| ASUSTek       | K52N                        | Notebook    | [eb2ec7cb3d](https://linux-hardware.org/?probe=eb2ec7cb3d) | Jun 15, 2023 |
| ASRock        | B85M                        | Desktop     | [19f8b16937](https://linux-hardware.org/?probe=19f8b16937) | Jun 15, 2023 |
| Lenovo        | Win8 STD MM DPK IPG         | All in one  | [c503081708](https://linux-hardware.org/?probe=c503081708) | Jun 15, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [b00d413241](https://linux-hardware.org/?probe=b00d413241) | Jun 14, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [1d487a1ed5](https://linux-hardware.org/?probe=1d487a1ed5) | Jun 14, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [eab79964fb](https://linux-hardware.org/?probe=eab79964fb) | Jun 14, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [e1bb6b17b8](https://linux-hardware.org/?probe=e1bb6b17b8) | Jun 14, 2023 |
| Vorke         | V1 Plus                     | Desktop     | [a63988d437](https://linux-hardware.org/?probe=a63988d437) | Jun 14, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [9fe9d9f03f](https://linux-hardware.org/?probe=9fe9d9f03f) | Jun 13, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [c1992a1680](https://linux-hardware.org/?probe=c1992a1680) | Jun 13, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [b737ce6557](https://linux-hardware.org/?probe=b737ce6557) | Jun 13, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [f46f1000c0](https://linux-hardware.org/?probe=f46f1000c0) | Jun 13, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [535d3d42b7](https://linux-hardware.org/?probe=535d3d42b7) | Jun 13, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [2794a5aa86](https://linux-hardware.org/?probe=2794a5aa86) | Jun 12, 2023 |
| ASUSTek       | P5B                         | Desktop     | [6308a1c633](https://linux-hardware.org/?probe=6308a1c633) | Jun 12, 2023 |
| Toshiba       | Mobile Intel 4 Series/IC... | Desktop     | [45696e1d1b](https://linux-hardware.org/?probe=45696e1d1b) | Jun 12, 2023 |
| HP            | ENVY m6                     | Notebook    | [b3c165b329](https://linux-hardware.org/?probe=b3c165b329) | Jun 12, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [373e36422d](https://linux-hardware.org/?probe=373e36422d) | Jun 12, 2023 |
| MSI           | GL62M 7RDX                  | Notebook    | [d1fb646d9a](https://linux-hardware.org/?probe=d1fb646d9a) | Jun 11, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9cb593e9e1](https://linux-hardware.org/?probe=9cb593e9e1) | Jun 11, 2023 |
| ASUSTek       | U43Jc                       | Notebook    | [1af7e59490](https://linux-hardware.org/?probe=1af7e59490) | Jun 11, 2023 |
| ASUSTek       | U43Jc                       | Notebook    | [15e8e27585](https://linux-hardware.org/?probe=15e8e27585) | Jun 11, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [9ea7188339](https://linux-hardware.org/?probe=9ea7188339) | Jun 11, 2023 |
| HP            | 8350                        | Desktop     | [8a40ff28c8](https://linux-hardware.org/?probe=8a40ff28c8) | Jun 11, 2023 |
| HP            | Pavilion g7                 | Notebook    | [c599527484](https://linux-hardware.org/?probe=c599527484) | Jun 11, 2023 |
| ASUSTek       | P5B                         | Desktop     | [794635cbea](https://linux-hardware.org/?probe=794635cbea) | Jun 10, 2023 |
| Samsung       | N150/N210/N220              | Notebook    | [977d645961](https://linux-hardware.org/?probe=977d645961) | Jun 10, 2023 |
| Notebook      | NJ50_70CU                   | Notebook    | [d39b8694fd](https://linux-hardware.org/?probe=d39b8694fd) | Jun 10, 2023 |
| Packard Be... | EasyNote TE11BZ             | Notebook    | [a8f9a31f17](https://linux-hardware.org/?probe=a8f9a31f17) | Jun 10, 2023 |
| MP            | MS-7848                     | Desktop     | [cd63c98850](https://linux-hardware.org/?probe=cd63c98850) | Jun 10, 2023 |
| Google        | Pirika                      | Notebook    | [67fce0a645](https://linux-hardware.org/?probe=67fce0a645) | Jun 10, 2023 |
| Dell          | Precision 7520              | Notebook    | [c52fb2f851](https://linux-hardware.org/?probe=c52fb2f851) | Jun 10, 2023 |
| Nvidia        | MCP79                       | Desktop     | [8203509a77](https://linux-hardware.org/?probe=8203509a77) | Jun 09, 2023 |
| ASRock        | H81M-HDS                    | Desktop     | [e1ff6f4e2f](https://linux-hardware.org/?probe=e1ff6f4e2f) | Jun 08, 2023 |
| ASUSTek       | P5B                         | Desktop     | [32baec6c0f](https://linux-hardware.org/?probe=32baec6c0f) | Jun 08, 2023 |
| Shenzhen M... | F7BFD                       | Desktop     | [74cf1d0b63](https://linux-hardware.org/?probe=74cf1d0b63) | Jun 08, 2023 |
| Shenzhen M... | F7BFD                       | Desktop     | [88cbeea389](https://linux-hardware.org/?probe=88cbeea389) | Jun 08, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [20d28155d8](https://linux-hardware.org/?probe=20d28155d8) | Jun 08, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [517cbd7f48](https://linux-hardware.org/?probe=517cbd7f48) | Jun 08, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [2ad7aefc45](https://linux-hardware.org/?probe=2ad7aefc45) | Jun 07, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [2ad409f60a](https://linux-hardware.org/?probe=2ad409f60a) | Jun 07, 2023 |
| HP            | 8350                        | Desktop     | [113be26d4c](https://linux-hardware.org/?probe=113be26d4c) | Jun 07, 2023 |
| Dell          | 0G9322                      | Desktop     | [e81a7f788a](https://linux-hardware.org/?probe=e81a7f788a) | Jun 07, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [5254a5fe09](https://linux-hardware.org/?probe=5254a5fe09) | Jun 07, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | Notebook    | [de4c183b01](https://linux-hardware.org/?probe=de4c183b01) | Jun 06, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [e066300eac](https://linux-hardware.org/?probe=e066300eac) | Jun 06, 2023 |
| Nvidia        | MCP79                       | Desktop     | [bf109ed28f](https://linux-hardware.org/?probe=bf109ed28f) | Jun 06, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [79f63dcf8e](https://linux-hardware.org/?probe=79f63dcf8e) | Jun 06, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [d48dc73993](https://linux-hardware.org/?probe=d48dc73993) | Jun 06, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [a98deb1f54](https://linux-hardware.org/?probe=a98deb1f54) | Jun 06, 2023 |
| ASUSTek       | CM1730,CM1830               | Desktop     | [2cc76d0cd9](https://linux-hardware.org/?probe=2cc76d0cd9) | Jun 05, 2023 |
| ASUSTek       | CM1730,CM1830               | Desktop     | [7dc46d923e](https://linux-hardware.org/?probe=7dc46d923e) | Jun 05, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [8308d5da16](https://linux-hardware.org/?probe=8308d5da16) | Jun 05, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [85c6e06d3b](https://linux-hardware.org/?probe=85c6e06d3b) | Jun 05, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [2f8dbb707f](https://linux-hardware.org/?probe=2f8dbb707f) | Jun 05, 2023 |
| Dell          | 00010C A00                  | Desktop     | [fb12198605](https://linux-hardware.org/?probe=fb12198605) | Jun 05, 2023 |
| Dell          | 00010C A00                  | Desktop     | [d94442285c](https://linux-hardware.org/?probe=d94442285c) | Jun 05, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [e3b8e1a109](https://linux-hardware.org/?probe=e3b8e1a109) | Jun 04, 2023 |
| Dell          | Latitude E5250              | Notebook    | [e85c6a09d1](https://linux-hardware.org/?probe=e85c6a09d1) | Jun 04, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [b1b0369688](https://linux-hardware.org/?probe=b1b0369688) | Jun 04, 2023 |
| Lenovo        | ThinkPad T450 20BUS0LW02    | Notebook    | [27f6e7df80](https://linux-hardware.org/?probe=27f6e7df80) | Jun 04, 2023 |
| ASUSTek       | B75M-A                      | Desktop     | [55139a968d](https://linux-hardware.org/?probe=55139a968d) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [413aba0d3f](https://linux-hardware.org/?probe=413aba0d3f) | Jun 04, 2023 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [83967c7908](https://linux-hardware.org/?probe=83967c7908) | Jun 04, 2023 |
| Intel         | NUC8BEB J72693-304          | Mini pc     | [a20f9c3365](https://linux-hardware.org/?probe=a20f9c3365) | Jun 03, 2023 |
| Dell          | 0G9322                      | Desktop     | [a1c5ec8909](https://linux-hardware.org/?probe=a1c5ec8909) | Jun 03, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [55f28b41b4](https://linux-hardware.org/?probe=55f28b41b4) | Jun 03, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [6ea1bc7e6a](https://linux-hardware.org/?probe=6ea1bc7e6a) | Jun 03, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [01387c3030](https://linux-hardware.org/?probe=01387c3030) | Jun 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [20260fb3b3](https://linux-hardware.org/?probe=20260fb3b3) | Jun 03, 2023 |
| HP            | 339A                        | Desktop     | [bb4619f4eb](https://linux-hardware.org/?probe=bb4619f4eb) | Jun 02, 2023 |
| Gateway       | SX2851                      | Desktop     | [262ddffda9](https://linux-hardware.org/?probe=262ddffda9) | Jun 02, 2023 |
| IPASON        | P3                          | Notebook    | [bd9e0660a4](https://linux-hardware.org/?probe=bd9e0660a4) | Jun 02, 2023 |
| ASUSTek       | K70IJ                       | Notebook    | [5b877dfec5](https://linux-hardware.org/?probe=5b877dfec5) | Jun 02, 2023 |
| MSI           | H81M-E34                    | Desktop     | [26362cac22](https://linux-hardware.org/?probe=26362cac22) | Jun 02, 2023 |
| MSI           | H81M-E34                    | Desktop     | [9f04387a7c](https://linux-hardware.org/?probe=9f04387a7c) | Jun 01, 2023 |
| ASRock        | ALiveDual-eSATA2            | Desktop     | [0f490d3b39](https://linux-hardware.org/?probe=0f490d3b39) | Jun 01, 2023 |
| Toshiba       | Satellite L650              | Notebook    | [63eb6978fa](https://linux-hardware.org/?probe=63eb6978fa) | Jun 01, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [abc4bba144](https://linux-hardware.org/?probe=abc4bba144) | Jun 01, 2023 |
| MSI           | 890FXA-GD70                 | Desktop     | [bcc4cd9597](https://linux-hardware.org/?probe=bcc4cd9597) | Jun 01, 2023 |
| HP            | 82B5                        | All in one  | [77ecbfa91c](https://linux-hardware.org/?probe=77ecbfa91c) | Jun 01, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | Notebook    | [a7af6cac2c](https://linux-hardware.org/?probe=a7af6cac2c) | Jun 01, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [923c9a18ff](https://linux-hardware.org/?probe=923c9a18ff) | Jun 01, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [0198d67a15](https://linux-hardware.org/?probe=0198d67a15) | May 31, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [449b742c95](https://linux-hardware.org/?probe=449b742c95) | May 31, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [0ddd2982db](https://linux-hardware.org/?probe=0ddd2982db) | May 31, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [93d1ee7e2d](https://linux-hardware.org/?probe=93d1ee7e2d) | May 31, 2023 |
| Sony          | SVF14214CXW                 | Notebook    | [51568ce56e](https://linux-hardware.org/?probe=51568ce56e) | May 30, 2023 |
| Dell          | Latitude 3480               | Notebook    | [56d1834385](https://linux-hardware.org/?probe=56d1834385) | May 30, 2023 |
| Sony          | SVF14214CXW                 | Notebook    | [6cf7c2d7f2](https://linux-hardware.org/?probe=6cf7c2d7f2) | May 30, 2023 |
| Dell          | Inspiron 5748               | Notebook    | [08b61d608c](https://linux-hardware.org/?probe=08b61d608c) | May 30, 2023 |
| ASUSTek       | U43Jc                       | Notebook    | [db28d8f731](https://linux-hardware.org/?probe=db28d8f731) | May 28, 2023 |
| ASUSTek       | U43Jc                       | Notebook    | [36bd3a5288](https://linux-hardware.org/?probe=36bd3a5288) | May 28, 2023 |
| Lenovo        | ThinkPad E490 20N8A01YGI    | Notebook    | [c46cf56eb1](https://linux-hardware.org/?probe=c46cf56eb1) | May 27, 2023 |
| Acer          | Predator G3-605             | Desktop     | [f33c170be3](https://linux-hardware.org/?probe=f33c170be3) | May 27, 2023 |
| Lenovo        | B50-70 80EU                 | Notebook    | [8c51cdf4ef](https://linux-hardware.org/?probe=8c51cdf4ef) | May 27, 2023 |
| HP            | Pavilion dv6                | Notebook    | [9f96328490](https://linux-hardware.org/?probe=9f96328490) | May 27, 2023 |
| ASUSTek       | M2V-MX SE                   | Desktop     | [be58596103](https://linux-hardware.org/?probe=be58596103) | May 27, 2023 |
| Acer          | Aspire ES1-523              | Notebook    | [681fbd4a1f](https://linux-hardware.org/?probe=681fbd4a1f) | May 27, 2023 |
| ASUSTek       | M2V-MX SE                   | Desktop     | [0eedc4211a](https://linux-hardware.org/?probe=0eedc4211a) | May 27, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [48a2156205](https://linux-hardware.org/?probe=48a2156205) | May 27, 2023 |
| Dell          | 0G9322                      | Desktop     | [4d1450ba3a](https://linux-hardware.org/?probe=4d1450ba3a) | May 27, 2023 |
| Dell          | 0G9322                      | Desktop     | [d742ccb0c4](https://linux-hardware.org/?probe=d742ccb0c4) | May 27, 2023 |
| HP            | 21D0                        | Desktop     | [7f83859a91](https://linux-hardware.org/?probe=7f83859a91) | May 27, 2023 |
| HP            | 81BA                        | All in one  | [d41186191f](https://linux-hardware.org/?probe=d41186191f) | May 27, 2023 |
| MSI           | H97 GUARD-PRO               | Desktop     | [3737e6c832](https://linux-hardware.org/?probe=3737e6c832) | May 27, 2023 |
| Toshiba       | TECRA M10                   | Notebook    | [3ce97963e7](https://linux-hardware.org/?probe=3ce97963e7) | May 26, 2023 |
| Toshiba       | TECRA M10                   | Notebook    | [2c574f9677](https://linux-hardware.org/?probe=2c574f9677) | May 26, 2023 |
| HP            | ProBook 4740s               | Notebook    | [457a56d75c](https://linux-hardware.org/?probe=457a56d75c) | May 26, 2023 |
| Intel         | NUC6CAYB J23203-408         | Mini pc     | [53d45d0d79](https://linux-hardware.org/?probe=53d45d0d79) | May 26, 2023 |
| ASUSTek       | G50VT                       | Notebook    | [6e4a2588b1](https://linux-hardware.org/?probe=6e4a2588b1) | May 26, 2023 |
| Intel         | NUC6CAYB J23203-408         | Mini pc     | [8d7ce86449](https://linux-hardware.org/?probe=8d7ce86449) | May 26, 2023 |
| HP            | 18E5                        | Desktop     | [23e2edb1fe](https://linux-hardware.org/?probe=23e2edb1fe) | May 26, 2023 |
| Dell          | 0K095G A02                  | Desktop     | [f11b8418c9](https://linux-hardware.org/?probe=f11b8418c9) | May 26, 2023 |
| HP            | 21D0                        | Desktop     | [8e52c2613c](https://linux-hardware.org/?probe=8e52c2613c) | May 26, 2023 |
| Google        | Lars                        | Notebook    | [25cc6549c3](https://linux-hardware.org/?probe=25cc6549c3) | May 25, 2023 |
| HP            | ProBook 6440b               | Notebook    | [5ed14b01a3](https://linux-hardware.org/?probe=5ed14b01a3) | May 25, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [61dc4c5620](https://linux-hardware.org/?probe=61dc4c5620) | May 25, 2023 |
| Apple         | MacBookAir4,1               | Notebook    | [d25345cb25](https://linux-hardware.org/?probe=d25345cb25) | May 25, 2023 |
| ECS           | H510H6-M2                   | Desktop     | [eba710b3de](https://linux-hardware.org/?probe=eba710b3de) | May 24, 2023 |
| Vorke         | V1 Plus                     | Desktop     | [81c0b82d6c](https://linux-hardware.org/?probe=81c0b82d6c) | May 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [f6fbdf57b5](https://linux-hardware.org/?probe=f6fbdf57b5) | May 24, 2023 |
| ECS           | H510H6-M2                   | Desktop     | [b36784601b](https://linux-hardware.org/?probe=b36784601b) | May 24, 2023 |
| HP            | Pavilion Notebook 15-bc5... | Notebook    | [933989a15b](https://linux-hardware.org/?probe=933989a15b) | May 24, 2023 |
| HP            | Stream Notebook             | Notebook    | [74d40533fc](https://linux-hardware.org/?probe=74d40533fc) | May 24, 2023 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [504a24887e](https://linux-hardware.org/?probe=504a24887e) | May 24, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [ca3ed99a5c](https://linux-hardware.org/?probe=ca3ed99a5c) | May 24, 2023 |
| Pegatron      | 2AC2A                       | Desktop     | [f9e504a430](https://linux-hardware.org/?probe=f9e504a430) | May 24, 2023 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [8c7d3913b8](https://linux-hardware.org/?probe=8c7d3913b8) | May 24, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [e1baf451db](https://linux-hardware.org/?probe=e1baf451db) | May 23, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [61ef8e4e63](https://linux-hardware.org/?probe=61ef8e4e63) | May 23, 2023 |
| HP            | 21EF                        | Desktop     | [f1d5c9381c](https://linux-hardware.org/?probe=f1d5c9381c) | May 23, 2023 |
| MSI           | H81M-E34                    | Desktop     | [4247f30888](https://linux-hardware.org/?probe=4247f30888) | May 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [977cf42905](https://linux-hardware.org/?probe=977cf42905) | May 23, 2023 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [08746538f6](https://linux-hardware.org/?probe=08746538f6) | May 23, 2023 |
| Dell          | Latitude E5450              | Notebook    | [642802d511](https://linux-hardware.org/?probe=642802d511) | May 23, 2023 |
| Dell          | Inspiron 1501               | Notebook    | [4703a17f03](https://linux-hardware.org/?probe=4703a17f03) | May 23, 2023 |
| HP            | Pavilion g6                 | Notebook    | [4d0edc38d5](https://linux-hardware.org/?probe=4d0edc38d5) | May 23, 2023 |
| HP            | 21EF                        | Desktop     | [3249975d27](https://linux-hardware.org/?probe=3249975d27) | May 22, 2023 |
| Packard Be... | EasyNote MH35               | Notebook    | [ea7710b373](https://linux-hardware.org/?probe=ea7710b373) | May 22, 2023 |
| ASRock        | H77M                        | Desktop     | [7f173e0b75](https://linux-hardware.org/?probe=7f173e0b75) | May 22, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [dfb369a8d2](https://linux-hardware.org/?probe=dfb369a8d2) | May 22, 2023 |
| HP            | EliteBook Folio G1          | Notebook    | [81477cd76f](https://linux-hardware.org/?probe=81477cd76f) | May 22, 2023 |
| HP            | EliteBook Folio G1          | Notebook    | [73d4310fa2](https://linux-hardware.org/?probe=73d4310fa2) | May 22, 2023 |
| HP            | 18E5                        | Desktop     | [d1bc34770d](https://linux-hardware.org/?probe=d1bc34770d) | May 22, 2023 |
| Microsoft     | Surface Book                | Tablet      | [01c76b5ed7](https://linux-hardware.org/?probe=01c76b5ed7) | May 21, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [b6465d2950](https://linux-hardware.org/?probe=b6465d2950) | May 21, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [b9de7bf2f3](https://linux-hardware.org/?probe=b9de7bf2f3) | May 21, 2023 |
| Dell          | 0FGCC7 A01                  | Server      | [3900d6a330](https://linux-hardware.org/?probe=3900d6a330) | May 21, 2023 |
| Dell          | 02N3WF A01                  | Desktop     | [8d0096c040](https://linux-hardware.org/?probe=8d0096c040) | May 21, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [4087cdd6cb](https://linux-hardware.org/?probe=4087cdd6cb) | May 20, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [8db744994d](https://linux-hardware.org/?probe=8db744994d) | May 20, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [6bef224193](https://linux-hardware.org/?probe=6bef224193) | May 20, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [d11ecdffaf](https://linux-hardware.org/?probe=d11ecdffaf) | May 20, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [0bcd2c7244](https://linux-hardware.org/?probe=0bcd2c7244) | May 20, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [c1594f6dab](https://linux-hardware.org/?probe=c1594f6dab) | May 20, 2023 |
| Dell          | Latitude E7450              | Notebook    | [b76cb7567c](https://linux-hardware.org/?probe=b76cb7567c) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [c1f679b4d4](https://linux-hardware.org/?probe=c1f679b4d4) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [0c163f5c69](https://linux-hardware.org/?probe=0c163f5c69) | May 20, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [8a6ad6c590](https://linux-hardware.org/?probe=8a6ad6c590) | May 19, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [514fe06c9e](https://linux-hardware.org/?probe=514fe06c9e) | May 19, 2023 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [aae519e65d](https://linux-hardware.org/?probe=aae519e65d) | May 19, 2023 |
| Tactus        | GeoBook 140                 | Notebook    | [534c32884a](https://linux-hardware.org/?probe=534c32884a) | May 19, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [31568d83f7](https://linux-hardware.org/?probe=31568d83f7) | May 18, 2023 |
| Gigabyte      | H81M-DS2                    | Desktop     | [754dc9d1fc](https://linux-hardware.org/?probe=754dc9d1fc) | May 18, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [0608bc6ac3](https://linux-hardware.org/?probe=0608bc6ac3) | May 18, 2023 |
| Philco        | PHN14C                      | Notebook    | [4efea72b8f](https://linux-hardware.org/?probe=4efea72b8f) | May 18, 2023 |
| Acer          | Aspire A514-55              | Notebook    | [e096b3a75c](https://linux-hardware.org/?probe=e096b3a75c) | May 18, 2023 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [ee37475637](https://linux-hardware.org/?probe=ee37475637) | May 18, 2023 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [68406e2c40](https://linux-hardware.org/?probe=68406e2c40) | May 18, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [cadb0eb363](https://linux-hardware.org/?probe=cadb0eb363) | May 17, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [cd3c24c6a2](https://linux-hardware.org/?probe=cd3c24c6a2) | May 17, 2023 |
| Acer          | Revo 70                     | Desktop     | [6cbc11e75b](https://linux-hardware.org/?probe=6cbc11e75b) | May 17, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [e18deba45b](https://linux-hardware.org/?probe=e18deba45b) | May 17, 2023 |
| HP            | 2B02                        | Desktop     | [a6bf09d51c](https://linux-hardware.org/?probe=a6bf09d51c) | May 17, 2023 |
| Pegatron      | Benicia                     | Desktop     | [e6ee1c66f6](https://linux-hardware.org/?probe=e6ee1c66f6) | May 17, 2023 |
| Framework     | Laptop                      | Notebook    | [b8739c141d](https://linux-hardware.org/?probe=b8739c141d) | May 16, 2023 |
| Fujitsu Si... | AMILO A1645                 | Notebook    | [d825262368](https://linux-hardware.org/?probe=d825262368) | May 16, 2023 |
| Fujitsu Si... | AMILO A1645                 | Notebook    | [18ca79ef29](https://linux-hardware.org/?probe=18ca79ef29) | May 16, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [d3c3cc9f96](https://linux-hardware.org/?probe=d3c3cc9f96) | May 15, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [7b95691784](https://linux-hardware.org/?probe=7b95691784) | May 15, 2023 |
| Intel         | Tiger Hill                  | Desktop     | [fdbe67045c](https://linux-hardware.org/?probe=fdbe67045c) | May 15, 2023 |
| Samsung       | N150/N210/N220              | Notebook    | [3f18889439](https://linux-hardware.org/?probe=3f18889439) | May 15, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [03c67bbed5](https://linux-hardware.org/?probe=03c67bbed5) | May 15, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [496f6048ec](https://linux-hardware.org/?probe=496f6048ec) | May 15, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [dd8c6c3811](https://linux-hardware.org/?probe=dd8c6c3811) | May 15, 2023 |
| HP            | 18E5                        | Desktop     | [7d5ceb9f5d](https://linux-hardware.org/?probe=7d5ceb9f5d) | May 15, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [d27a3510ed](https://linux-hardware.org/?probe=d27a3510ed) | May 14, 2023 |
| HP            | Presario CQ61               | Notebook    | [0967999006](https://linux-hardware.org/?probe=0967999006) | May 14, 2023 |
| Google        | Bluebird                    | Notebook    | [c10880ed1b](https://linux-hardware.org/?probe=c10880ed1b) | May 14, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [24c81ddf59](https://linux-hardware.org/?probe=24c81ddf59) | May 14, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [89fbcb7903](https://linux-hardware.org/?probe=89fbcb7903) | May 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [83e208da09](https://linux-hardware.org/?probe=83e208da09) | May 14, 2023 |
| Lenovo        | IdeaPad Z470                | Notebook    | [2b11351f94](https://linux-hardware.org/?probe=2b11351f94) | May 14, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [38b6dd7b3f](https://linux-hardware.org/?probe=38b6dd7b3f) | May 14, 2023 |
| Dell          | Latitude 3340               | Notebook    | [59d83d9cef](https://linux-hardware.org/?probe=59d83d9cef) | May 14, 2023 |
| SKIKK         | Niflheim 17 II              | Notebook    | [ce9c27f16f](https://linux-hardware.org/?probe=ce9c27f16f) | May 14, 2023 |
| ASUSTek       | K8N-DRE                     | Desktop     | [395dc0cfb3](https://linux-hardware.org/?probe=395dc0cfb3) | May 13, 2023 |
| ASUSTek       | K8N-DRE                     | Desktop     | [f55a0c735f](https://linux-hardware.org/?probe=f55a0c735f) | May 13, 2023 |
| Vorke         | V1 Plus                     | Desktop     | [19f095fc02](https://linux-hardware.org/?probe=19f095fc02) | May 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [e844f3a6fe](https://linux-hardware.org/?probe=e844f3a6fe) | May 13, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [bd9eca79bb](https://linux-hardware.org/?probe=bd9eca79bb) | May 13, 2023 |
| Acer          | Predator G3-605             | Desktop     | [2d1485d58b](https://linux-hardware.org/?probe=2d1485d58b) | May 13, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [e053d0d304](https://linux-hardware.org/?probe=e053d0d304) | May 13, 2023 |
| Chuwi         | GemiBook XPro               | Notebook    | [53b6692944](https://linux-hardware.org/?probe=53b6692944) | May 13, 2023 |
| Chuwi         | GemiBook XPro               | Notebook    | [297921aabf](https://linux-hardware.org/?probe=297921aabf) | May 13, 2023 |
| Acer          | Predator G3-605             | Desktop     | [d3fc5ad399](https://linux-hardware.org/?probe=d3fc5ad399) | May 13, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [080f1c13d8](https://linux-hardware.org/?probe=080f1c13d8) | May 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [e2c57c80fc](https://linux-hardware.org/?probe=e2c57c80fc) | May 13, 2023 |
| Acer          | Aspire E1-570               | Notebook    | [135675c3ad](https://linux-hardware.org/?probe=135675c3ad) | May 13, 2023 |
| Google        | Kled                        | Notebook    | [f4e834ff36](https://linux-hardware.org/?probe=f4e834ff36) | May 12, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [d041d35517](https://linux-hardware.org/?probe=d041d35517) | May 12, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [d3ab5dcb5d](https://linux-hardware.org/?probe=d3ab5dcb5d) | May 12, 2023 |
| Dell          | Precision M2800             | Notebook    | [571407d9a3](https://linux-hardware.org/?probe=571407d9a3) | May 12, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [89b8dfaad7](https://linux-hardware.org/?probe=89b8dfaad7) | May 12, 2023 |
| Chuwi         | GemiBook XPro               | Notebook    | [e13fe43842](https://linux-hardware.org/?probe=e13fe43842) | May 12, 2023 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [c86f346e1d](https://linux-hardware.org/?probe=c86f346e1d) | May 12, 2023 |
| HP            | ProBook 4535s               | Notebook    | [0d2f9561ce](https://linux-hardware.org/?probe=0d2f9561ce) | May 12, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [34bd8e2402](https://linux-hardware.org/?probe=34bd8e2402) | May 12, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [5a1484127d](https://linux-hardware.org/?probe=5a1484127d) | May 12, 2023 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [730cce9495](https://linux-hardware.org/?probe=730cce9495) | May 12, 2023 |
| eMachines     | E620                        | Notebook    | [827a81facc](https://linux-hardware.org/?probe=827a81facc) | May 11, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [381ca3ca78](https://linux-hardware.org/?probe=381ca3ca78) | May 11, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [40b6afc886](https://linux-hardware.org/?probe=40b6afc886) | May 11, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [2c8128a196](https://linux-hardware.org/?probe=2c8128a196) | May 11, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [a7327f2e2e](https://linux-hardware.org/?probe=a7327f2e2e) | May 11, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [256ad0c4d8](https://linux-hardware.org/?probe=256ad0c4d8) | May 11, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [2c96614c16](https://linux-hardware.org/?probe=2c96614c16) | May 11, 2023 |
| Toshiba       | TECRA M10                   | Notebook    | [cf43cf62c7](https://linux-hardware.org/?probe=cf43cf62c7) | May 10, 2023 |
| Toshiba       | TECRA M10                   | Notebook    | [d2be66b23b](https://linux-hardware.org/?probe=d2be66b23b) | May 10, 2023 |
| HP            | Pavilion dv7                | Notebook    | [794d198929](https://linux-hardware.org/?probe=794d198929) | May 10, 2023 |
| 16280-BM-3... | BADWARE-335861024712484 ... | Desktop     | [8f3baa5ed5](https://linux-hardware.org/?probe=8f3baa5ed5) | May 10, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [719d80a236](https://linux-hardware.org/?probe=719d80a236) | May 10, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [b25b524237](https://linux-hardware.org/?probe=b25b524237) | May 10, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [22778449cc](https://linux-hardware.org/?probe=22778449cc) | May 10, 2023 |
| ASUSTek       | A55BM-E                     | Desktop     | [4b1cb4d8cf](https://linux-hardware.org/?probe=4b1cb4d8cf) | May 10, 2023 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [ffd84ff48e](https://linux-hardware.org/?probe=ffd84ff48e) | May 09, 2023 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [ba75f23f44](https://linux-hardware.org/?probe=ba75f23f44) | May 09, 2023 |
| Toshiba       | Satellite M60               | Notebook    | [91437556e8](https://linux-hardware.org/?probe=91437556e8) | May 09, 2023 |
| Toshiba       | Satellite M60               | Notebook    | [39b2bcd3a5](https://linux-hardware.org/?probe=39b2bcd3a5) | May 09, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [abf6d2bf1d](https://linux-hardware.org/?probe=abf6d2bf1d) | May 09, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [0b1518261e](https://linux-hardware.org/?probe=0b1518261e) | May 09, 2023 |
| ASUSTek       | H81I-PLUS                   | Desktop     | [93d7a459be](https://linux-hardware.org/?probe=93d7a459be) | May 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [d45b33c736](https://linux-hardware.org/?probe=d45b33c736) | May 09, 2023 |
| ASUSTek       | GL702VI                     | Notebook    | [3598875ef3](https://linux-hardware.org/?probe=3598875ef3) | May 09, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [372fa59e86](https://linux-hardware.org/?probe=372fa59e86) | May 09, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [9ac068efc7](https://linux-hardware.org/?probe=9ac068efc7) | May 09, 2023 |
| Dell          | Latitude E6520              | Notebook    | [668b26cd28](https://linux-hardware.org/?probe=668b26cd28) | May 09, 2023 |
| HP            | Laptop 15                   | Notebook    | [20a0a03b80](https://linux-hardware.org/?probe=20a0a03b80) | May 08, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | Notebook    | [953d03df07](https://linux-hardware.org/?probe=953d03df07) | May 08, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [d48affb6b2](https://linux-hardware.org/?probe=d48affb6b2) | May 08, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | Notebook    | [ee52ca7ce5](https://linux-hardware.org/?probe=ee52ca7ce5) | May 08, 2023 |
| HP            | 655                         | Notebook    | [be3dec1f65](https://linux-hardware.org/?probe=be3dec1f65) | May 08, 2023 |
| Positivo      | S14CT01                     | Notebook    | [63a129c031](https://linux-hardware.org/?probe=63a129c031) | May 08, 2023 |
| Dell          | Latitude 5520               | Notebook    | [4d8ef45cbc](https://linux-hardware.org/?probe=4d8ef45cbc) | May 07, 2023 |
| TrekStor      | SurfTab twin 11.6           | Convertible | [d6085d9a0b](https://linux-hardware.org/?probe=d6085d9a0b) | May 07, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [96cfd64792](https://linux-hardware.org/?probe=96cfd64792) | May 07, 2023 |
| SKIKK         | Niflheim 17 II              | Notebook    | [0304fddec7](https://linux-hardware.org/?probe=0304fddec7) | May 07, 2023 |
| SKIKK         | Niflheim 17 II              | Notebook    | [2a30823af1](https://linux-hardware.org/?probe=2a30823af1) | May 07, 2023 |
| HP            | 339A                        | Desktop     | [8b646a0fa1](https://linux-hardware.org/?probe=8b646a0fa1) | May 07, 2023 |
| HP            | 339A                        | Desktop     | [e23aaae239](https://linux-hardware.org/?probe=e23aaae239) | May 07, 2023 |
| Intel         | D946GZIS AAD66165-301       | Desktop     | [c350f5ed12](https://linux-hardware.org/?probe=c350f5ed12) | May 06, 2023 |
| Fujitsu Si... | AMILO PRO V3515             | Notebook    | [a6da9a31d7](https://linux-hardware.org/?probe=a6da9a31d7) | May 06, 2023 |
| ASUSTek       | P8Z68 DELUXE/GEN3           | Desktop     | [288e495c16](https://linux-hardware.org/?probe=288e495c16) | May 06, 2023 |
| ASRockRack    | D1521D4I2                   | Desktop     | [136a9303c0](https://linux-hardware.org/?probe=136a9303c0) | May 06, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [7b0b45831c](https://linux-hardware.org/?probe=7b0b45831c) | May 06, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [b7bf9f8683](https://linux-hardware.org/?probe=b7bf9f8683) | May 06, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [46894747b1](https://linux-hardware.org/?probe=46894747b1) | May 05, 2023 |
| HP            | ProBook 6570b               | Notebook    | [480e352bf8](https://linux-hardware.org/?probe=480e352bf8) | May 05, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [2723e21a6e](https://linux-hardware.org/?probe=2723e21a6e) | May 05, 2023 |
| TrekStor      | SurfTab twin 11.6           | Convertible | [2d5ecba977](https://linux-hardware.org/?probe=2d5ecba977) | May 05, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [9a0649d500](https://linux-hardware.org/?probe=9a0649d500) | May 05, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [6069763b68](https://linux-hardware.org/?probe=6069763b68) | May 05, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [d8582f94de](https://linux-hardware.org/?probe=d8582f94de) | May 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [4ac4356e10](https://linux-hardware.org/?probe=4ac4356e10) | May 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [37fd24fab6](https://linux-hardware.org/?probe=37fd24fab6) | May 05, 2023 |
| Lenovo        | ThinkPad Yoga 11e 4th Ge... | Convertible | [b9ef1562db](https://linux-hardware.org/?probe=b9ef1562db) | May 05, 2023 |
| Lenovo        | ThinkPad T520 4242A25       | Notebook    | [6290e7f2fb](https://linux-hardware.org/?probe=6290e7f2fb) | May 05, 2023 |
| Lenovo        | ThinkPad Yoga 11e 4th Ge... | Convertible | [02fa09745c](https://linux-hardware.org/?probe=02fa09745c) | May 05, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [d571b75547](https://linux-hardware.org/?probe=d571b75547) | May 05, 2023 |
| Unknown       | X133                        | Notebook    | [b38ee0b3cc](https://linux-hardware.org/?probe=b38ee0b3cc) | May 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [cf49833602](https://linux-hardware.org/?probe=cf49833602) | May 04, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [408cbd96c0](https://linux-hardware.org/?probe=408cbd96c0) | May 04, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [9684be9c3a](https://linux-hardware.org/?probe=9684be9c3a) | May 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [5b46ed614a](https://linux-hardware.org/?probe=5b46ed614a) | May 04, 2023 |
| ASUSTek       | P5N73-CM                    | Desktop     | [e64a3c2da5](https://linux-hardware.org/?probe=e64a3c2da5) | May 04, 2023 |
| Acer          | Aspire 5732Z                | Notebook    | [f9868f3430](https://linux-hardware.org/?probe=f9868f3430) | May 04, 2023 |
| Unknown       | E450                        | Notebook    | [a3261aab47](https://linux-hardware.org/?probe=a3261aab47) | May 04, 2023 |
| Gigabyte      | Z590 VISION G               | Desktop     | [d37eb8bf49](https://linux-hardware.org/?probe=d37eb8bf49) | May 04, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [15160b0649](https://linux-hardware.org/?probe=15160b0649) | May 04, 2023 |
| ASRock        | H81M-HDS                    | Desktop     | [60e11bdf11](https://linux-hardware.org/?probe=60e11bdf11) | May 04, 2023 |
| KUU           | Andes II                    | Notebook    | [b15876e521](https://linux-hardware.org/?probe=b15876e521) | May 04, 2023 |
| Gigabyte      | MFLP5IP-00                  | Desktop     | [c9c14a6da2](https://linux-hardware.org/?probe=c9c14a6da2) | May 03, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [c338210639](https://linux-hardware.org/?probe=c338210639) | May 03, 2023 |
| Acer          | Aspire E1-570               | Notebook    | [bf515886ac](https://linux-hardware.org/?probe=bf515886ac) | May 03, 2023 |
| Dell          | 09WH54 A00                  | Desktop     | [0afa4006cd](https://linux-hardware.org/?probe=0afa4006cd) | May 03, 2023 |
| Acer          | Aspire V5-531               | Notebook    | [d8c61ad691](https://linux-hardware.org/?probe=d8c61ad691) | May 02, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [d3757c615f](https://linux-hardware.org/?probe=d3757c615f) | May 02, 2023 |
| Intel         | D946GZIS AAD66165-301       | Desktop     | [e61e22863f](https://linux-hardware.org/?probe=e61e22863f) | May 02, 2023 |
| Dell          | Latitude E6540              | Notebook    | [e6f334c91c](https://linux-hardware.org/?probe=e6f334c91c) | May 01, 2023 |
| ASRock        | G41M-GS                     | Desktop     | [0824a9c571](https://linux-hardware.org/?probe=0824a9c571) | May 01, 2023 |
| Intel         | H55                         | Desktop     | [04dd5e834e](https://linux-hardware.org/?probe=04dd5e834e) | May 01, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [f2c5618e4d](https://linux-hardware.org/?probe=f2c5618e4d) | May 01, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [83abb6a8e0](https://linux-hardware.org/?probe=83abb6a8e0) | May 01, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [f395109c45](https://linux-hardware.org/?probe=f395109c45) | May 01, 2023 |
| ASUSTek       | K53U                        | Notebook    | [0745a61353](https://linux-hardware.org/?probe=0745a61353) | May 01, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [cbc75f825e](https://linux-hardware.org/?probe=cbc75f825e) | May 01, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [e316615297](https://linux-hardware.org/?probe=e316615297) | May 01, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [bcd38374a3](https://linux-hardware.org/?probe=bcd38374a3) | May 01, 2023 |
| ASUSTek       | PN41                        | Mini pc     | [99d3eca719](https://linux-hardware.org/?probe=99d3eca719) | May 01, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [1a00a1321e](https://linux-hardware.org/?probe=1a00a1321e) | Apr 30, 2023 |
| MSI           | IONA                        | Desktop     | [966ec83038](https://linux-hardware.org/?probe=966ec83038) | Apr 30, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [6987a21849](https://linux-hardware.org/?probe=6987a21849) | Apr 30, 2023 |
| Foxconn       | G41S/G41S-K                 | Desktop     | [946a95c594](https://linux-hardware.org/?probe=946a95c594) | Apr 30, 2023 |
| Foxconn       | G41S/G41S-K                 | Desktop     | [58cebf39d1](https://linux-hardware.org/?probe=58cebf39d1) | Apr 30, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [f1faff33de](https://linux-hardware.org/?probe=f1faff33de) | Apr 30, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [8b89ffd983](https://linux-hardware.org/?probe=8b89ffd983) | Apr 30, 2023 |
| HP            | Pavilion dv7                | Notebook    | [68b51fde68](https://linux-hardware.org/?probe=68b51fde68) | Apr 30, 2023 |
| Positivo      | S14CT01                     | Notebook    | [b11ef938e1](https://linux-hardware.org/?probe=b11ef938e1) | Apr 29, 2023 |
| Toshiba       | Satellite C650D             | Notebook    | [472dedd62a](https://linux-hardware.org/?probe=472dedd62a) | Apr 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [4b0542737c](https://linux-hardware.org/?probe=4b0542737c) | Apr 29, 2023 |
| Apple         | Mac-F2208EC8                | Mini pc     | [6bad65ad2d](https://linux-hardware.org/?probe=6bad65ad2d) | Apr 29, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [25bc3aa225](https://linux-hardware.org/?probe=25bc3aa225) | Apr 29, 2023 |
| Sony          | VPCF215FX                   | Notebook    | [49c7606269](https://linux-hardware.org/?probe=49c7606269) | Apr 29, 2023 |
| Apple         | MacBook6,1                  | Notebook    | [58b09d7887](https://linux-hardware.org/?probe=58b09d7887) | Apr 29, 2023 |
| Apple         | MacBook6,1                  | Notebook    | [7d91fe30f7](https://linux-hardware.org/?probe=7d91fe30f7) | Apr 29, 2023 |
| Positivo      | S14CT01                     | Notebook    | [58988f4876](https://linux-hardware.org/?probe=58988f4876) | Apr 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [e908fdb73d](https://linux-hardware.org/?probe=e908fdb73d) | Apr 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [a984eefe43](https://linux-hardware.org/?probe=a984eefe43) | Apr 28, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [d9010fa8d0](https://linux-hardware.org/?probe=d9010fa8d0) | Apr 28, 2023 |
| Lenovo        | ThinkPad Edge 25453BG       | Notebook    | [2b5c6e2ded](https://linux-hardware.org/?probe=2b5c6e2ded) | Apr 28, 2023 |
| HP            | Laptop 14-em0xxx            | Notebook    | [8d06549ae0](https://linux-hardware.org/?probe=8d06549ae0) | Apr 28, 2023 |
| Lenovo        | IdeaPad Y470                | Notebook    | [58c809428e](https://linux-hardware.org/?probe=58c809428e) | Apr 28, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [896574c24a](https://linux-hardware.org/?probe=896574c24a) | Apr 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [f1290d4846](https://linux-hardware.org/?probe=f1290d4846) | Apr 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [c4941a5c16](https://linux-hardware.org/?probe=c4941a5c16) | Apr 27, 2023 |
| Pegatron      | IPM41-D3                    | Desktop     | [faf8704eb3](https://linux-hardware.org/?probe=faf8704eb3) | Apr 26, 2023 |
| Dell          | Vostro 1510                 | Notebook    | [71c860d51c](https://linux-hardware.org/?probe=71c860d51c) | Apr 26, 2023 |
| Medion        | E2215T MD60198              | Notebook    | [390ccbba6f](https://linux-hardware.org/?probe=390ccbba6f) | Apr 26, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [86dad710fa](https://linux-hardware.org/?probe=86dad710fa) | Apr 26, 2023 |
| Lenovo        | 3000 N200 0769A97           | Notebook    | [a293f4f1f7](https://linux-hardware.org/?probe=a293f4f1f7) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | Notebook    | [c40de2e155](https://linux-hardware.org/?probe=c40de2e155) | Apr 26, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [f0ea43f3fd](https://linux-hardware.org/?probe=f0ea43f3fd) | Apr 26, 2023 |
| Intel         | D34010WYK H14771-304        | Desktop     | [4fbbe6e603](https://linux-hardware.org/?probe=4fbbe6e603) | Apr 26, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | Desktop     | [07e9099105](https://linux-hardware.org/?probe=07e9099105) | Apr 26, 2023 |
| HP            | 1632                        | Desktop     | [0355cb4e69](https://linux-hardware.org/?probe=0355cb4e69) | Apr 25, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | Notebook    | [7abd61de30](https://linux-hardware.org/?probe=7abd61de30) | Apr 25, 2023 |
| HP            | EliteBook 2730p             | Notebook    | [51c0fadfdb](https://linux-hardware.org/?probe=51c0fadfdb) | Apr 25, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | Notebook    | [927c9a0377](https://linux-hardware.org/?probe=927c9a0377) | Apr 25, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [4231d023e9](https://linux-hardware.org/?probe=4231d023e9) | Apr 25, 2023 |
| eMachines     | MCP61PM-GM                  | Desktop     | [ff00693839](https://linux-hardware.org/?probe=ff00693839) | Apr 25, 2023 |
| Acer          | AOHAPPY                     | Notebook    | [6f32fad8f0](https://linux-hardware.org/?probe=6f32fad8f0) | Apr 24, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [9bab79728a](https://linux-hardware.org/?probe=9bab79728a) | Apr 24, 2023 |
| Toshiba       | Satellite C45-A             | Notebook    | [7720195dfe](https://linux-hardware.org/?probe=7720195dfe) | Apr 24, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [57e3cfa7dc](https://linux-hardware.org/?probe=57e3cfa7dc) | Apr 24, 2023 |
| Intel         | D946GZIS AAD66165-301       | Desktop     | [9d5ada0fc4](https://linux-hardware.org/?probe=9d5ada0fc4) | Apr 24, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [154380c27c](https://linux-hardware.org/?probe=154380c27c) | Apr 24, 2023 |
| Dell          | Inspiron 5565               | Notebook    | [6622474d4b](https://linux-hardware.org/?probe=6622474d4b) | Apr 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [60d1d4aec8](https://linux-hardware.org/?probe=60d1d4aec8) | Apr 24, 2023 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [c087d6cbae](https://linux-hardware.org/?probe=c087d6cbae) | Apr 24, 2023 |
| Gigabyte      | B650M DS3H                  | Desktop     | [3d07651a47](https://linux-hardware.org/?probe=3d07651a47) | Apr 24, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [d9429d7e06](https://linux-hardware.org/?probe=d9429d7e06) | Apr 23, 2023 |
| Lenovo        | ThinkPad T440s 20ARS1BH0... | Notebook    | [b76462c15b](https://linux-hardware.org/?probe=b76462c15b) | Apr 23, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [8db1376917](https://linux-hardware.org/?probe=8db1376917) | Apr 23, 2023 |
| Pegatron      | 2AB5                        | Desktop     | [5f771d8ee5](https://linux-hardware.org/?probe=5f771d8ee5) | Apr 23, 2023 |
| Unknown       | G41                         | Desktop     | [cbe978cc34](https://linux-hardware.org/?probe=cbe978cc34) | Apr 23, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [49a0b005f8](https://linux-hardware.org/?probe=49a0b005f8) | Apr 23, 2023 |
| MSI           | GP62 7RD                    | Notebook    | [277bb2d2e3](https://linux-hardware.org/?probe=277bb2d2e3) | Apr 23, 2023 |
| Acer          | AOD270                      | Notebook    | [d7d653d3d6](https://linux-hardware.org/?probe=d7d653d3d6) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [25ee911879](https://linux-hardware.org/?probe=25ee911879) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [468824c4d9](https://linux-hardware.org/?probe=468824c4d9) | Apr 23, 2023 |
| Gigabyte      | B760M GAMING X AX DDR4      | Desktop     | [a68d32d442](https://linux-hardware.org/?probe=a68d32d442) | Apr 23, 2023 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [401f407dae](https://linux-hardware.org/?probe=401f407dae) | Apr 23, 2023 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [0cd5599131](https://linux-hardware.org/?probe=0cd5599131) | Apr 22, 2023 |
| HP            | Laptop 14-em0xxx            | Notebook    | [55ea4ded18](https://linux-hardware.org/?probe=55ea4ded18) | Apr 22, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [3c3719b07f](https://linux-hardware.org/?probe=3c3719b07f) | Apr 22, 2023 |
| Dell          | 0F373D A00                  | Desktop     | [206de0188d](https://linux-hardware.org/?probe=206de0188d) | Apr 22, 2023 |
| Lenovo        | B590 62743NG                | Notebook    | [ca0be4b423](https://linux-hardware.org/?probe=ca0be4b423) | Apr 22, 2023 |
| Lenovo        | B590 62743NG                | Notebook    | [74e38a8db9](https://linux-hardware.org/?probe=74e38a8db9) | Apr 22, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [e60b9070a6](https://linux-hardware.org/?probe=e60b9070a6) | Apr 22, 2023 |
| ASUSTek       | M5A78L LE                   | Desktop     | [b19724085f](https://linux-hardware.org/?probe=b19724085f) | Apr 21, 2023 |
| Acer          | AOHAPPY                     | Notebook    | [57a7ebf03f](https://linux-hardware.org/?probe=57a7ebf03f) | Apr 21, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [4dc6862db9](https://linux-hardware.org/?probe=4dc6862db9) | Apr 21, 2023 |
| Lenovo        | IdeaPadFlex 6-14IKB 81EM    | Convertible | [0a5da1a9a0](https://linux-hardware.org/?probe=0a5da1a9a0) | Apr 21, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [570077aa64](https://linux-hardware.org/?probe=570077aa64) | Apr 21, 2023 |
| AIERXUAN      | XIAOXUAN Pro                | Notebook    | [e472034313](https://linux-hardware.org/?probe=e472034313) | Apr 21, 2023 |
| AIERXUAN      | XIAOXUAN Pro                | Notebook    | [e500ddd5d9](https://linux-hardware.org/?probe=e500ddd5d9) | Apr 21, 2023 |
| Dell          | Inspiron 3531               | Notebook    | [6222a9aa08](https://linux-hardware.org/?probe=6222a9aa08) | Apr 21, 2023 |
| Gigabyte      | B650M DS3H                  | Desktop     | [de196a2cfa](https://linux-hardware.org/?probe=de196a2cfa) | Apr 21, 2023 |
| Microsoft     | Surface Book                | Tablet      | [13c23678aa](https://linux-hardware.org/?probe=13c23678aa) | Apr 21, 2023 |
| MSI           | GS73VR 7RF                  | Notebook    | [2eb85cc7fe](https://linux-hardware.org/?probe=2eb85cc7fe) | Apr 20, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [d428839f7c](https://linux-hardware.org/?probe=d428839f7c) | Apr 20, 2023 |
| HP            | 2ADE                        | Desktop     | [1a3d108a58](https://linux-hardware.org/?probe=1a3d108a58) | Apr 20, 2023 |
| HP            | 8054                        | Desktop     | [0f2c12c877](https://linux-hardware.org/?probe=0f2c12c877) | Apr 20, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [7d380bf016](https://linux-hardware.org/?probe=7d380bf016) | Apr 20, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [7029b5ee48](https://linux-hardware.org/?probe=7029b5ee48) | Apr 20, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [9093d27c30](https://linux-hardware.org/?probe=9093d27c30) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [069a675d2a](https://linux-hardware.org/?probe=069a675d2a) | Apr 19, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [bb0be3d9e3](https://linux-hardware.org/?probe=bb0be3d9e3) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [e58c3ad9d7](https://linux-hardware.org/?probe=e58c3ad9d7) | Apr 19, 2023 |
| Lenovo        | SHARKBAY 31900058 STD or... | Desktop     | [1331c6ef06](https://linux-hardware.org/?probe=1331c6ef06) | Apr 19, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [65eb0fa6be](https://linux-hardware.org/?probe=65eb0fa6be) | Apr 19, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [c36b1a5778](https://linux-hardware.org/?probe=c36b1a5778) | Apr 19, 2023 |
| Apple         | Mac-F2268DC8                | All in one  | [86e2d42f73](https://linux-hardware.org/?probe=86e2d42f73) | Apr 19, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [1548cc4309](https://linux-hardware.org/?probe=1548cc4309) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [85c7be8d12](https://linux-hardware.org/?probe=85c7be8d12) | Apr 19, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [2a7fe6d74b](https://linux-hardware.org/?probe=2a7fe6d74b) | Apr 18, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [be92b53515](https://linux-hardware.org/?probe=be92b53515) | Apr 18, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [7da02a75b5](https://linux-hardware.org/?probe=7da02a75b5) | Apr 18, 2023 |
| ASL           | BayTrail JHS773             | Desktop     | [3a5977ad04](https://linux-hardware.org/?probe=3a5977ad04) | Apr 18, 2023 |
| Dell          | 0T656F A02                  | Desktop     | [0d291f14a1](https://linux-hardware.org/?probe=0d291f14a1) | Apr 18, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [119560d8db](https://linux-hardware.org/?probe=119560d8db) | Apr 17, 2023 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [79029817b8](https://linux-hardware.org/?probe=79029817b8) | Apr 17, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [a99920ebba](https://linux-hardware.org/?probe=a99920ebba) | Apr 17, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [2f60207985](https://linux-hardware.org/?probe=2f60207985) | Apr 17, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [307e22b0d6](https://linux-hardware.org/?probe=307e22b0d6) | Apr 17, 2023 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [895f57e6d5](https://linux-hardware.org/?probe=895f57e6d5) | Apr 17, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [b2311e7cac](https://linux-hardware.org/?probe=b2311e7cac) | Apr 17, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [b9d869fe6b](https://linux-hardware.org/?probe=b9d869fe6b) | Apr 16, 2023 |
| Dell          | Vostro 3580                 | Notebook    | [b7d9953b54](https://linux-hardware.org/?probe=b7d9953b54) | Apr 16, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [f146ce9da7](https://linux-hardware.org/?probe=f146ce9da7) | Apr 16, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [ea8d83a743](https://linux-hardware.org/?probe=ea8d83a743) | Apr 16, 2023 |
| Lenovo        | ThinkPad P52s 20LCS1DU01    | Notebook    | [3fc78b3451](https://linux-hardware.org/?probe=3fc78b3451) | Apr 16, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [a56688fd70](https://linux-hardware.org/?probe=a56688fd70) | Apr 16, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [798405022f](https://linux-hardware.org/?probe=798405022f) | Apr 16, 2023 |
| AZW           | SEi                         | Notebook    | [a382976bf2](https://linux-hardware.org/?probe=a382976bf2) | Apr 15, 2023 |
| AZW           | SEi                         | Notebook    | [980b83cf5e](https://linux-hardware.org/?probe=980b83cf5e) | Apr 15, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [2b6f0394d7](https://linux-hardware.org/?probe=2b6f0394d7) | Apr 15, 2023 |
| Acer          | Aspire ES1-731G             | Notebook    | [1ef0f89c83](https://linux-hardware.org/?probe=1ef0f89c83) | Apr 15, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [ba3d9dd7e7](https://linux-hardware.org/?probe=ba3d9dd7e7) | Apr 15, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [506ba2605a](https://linux-hardware.org/?probe=506ba2605a) | Apr 15, 2023 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [c7568482a9](https://linux-hardware.org/?probe=c7568482a9) | Apr 15, 2023 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [b66c208e18](https://linux-hardware.org/?probe=b66c208e18) | Apr 15, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [2ca7c3fccc](https://linux-hardware.org/?probe=2ca7c3fccc) | Apr 15, 2023 |
| Intel         | H61                         | Desktop     | [81c7094e68](https://linux-hardware.org/?probe=81c7094e68) | Apr 15, 2023 |
| Lenovo        | ThinkPad T430s 2352CTO      | Notebook    | [a4c5130b84](https://linux-hardware.org/?probe=a4c5130b84) | Apr 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [e122e8dab8](https://linux-hardware.org/?probe=e122e8dab8) | Apr 15, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [d50de3a52c](https://linux-hardware.org/?probe=d50de3a52c) | Apr 14, 2023 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [fcfa1ed488](https://linux-hardware.org/?probe=fcfa1ed488) | Apr 14, 2023 |
| Biostar       | TZ75B                       | Desktop     | [c6720e2db2](https://linux-hardware.org/?probe=c6720e2db2) | Apr 14, 2023 |
| Foxconn       | G31MVP FAB:1.0              | Desktop     | [41eac5ca2f](https://linux-hardware.org/?probe=41eac5ca2f) | Apr 14, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [e9c2f8d5ba](https://linux-hardware.org/?probe=e9c2f8d5ba) | Apr 14, 2023 |
| HP            | 8430 1000                   | All in one  | [b813f95c6f](https://linux-hardware.org/?probe=b813f95c6f) | Apr 14, 2023 |
| HP            | 8430 1000                   | All in one  | [59572d294b](https://linux-hardware.org/?probe=59572d294b) | Apr 14, 2023 |
| Positivo      | Q4128C-S                    | Notebook    | [8dc2eb7738](https://linux-hardware.org/?probe=8dc2eb7738) | Apr 14, 2023 |
| Intel         | H61                         | Desktop     | [8aeeb449f8](https://linux-hardware.org/?probe=8aeeb449f8) | Apr 14, 2023 |
| ASRock        | B550 Steel Legend           | Desktop     | [9da868694f](https://linux-hardware.org/?probe=9da868694f) | Apr 14, 2023 |
| HP            | EliteBook 830 G6            | Notebook    | [75ce029800](https://linux-hardware.org/?probe=75ce029800) | Apr 13, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [4267100894](https://linux-hardware.org/?probe=4267100894) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [5e9f89e556](https://linux-hardware.org/?probe=5e9f89e556) | Apr 13, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [9e6cfba525](https://linux-hardware.org/?probe=9e6cfba525) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [d72e78c1b0](https://linux-hardware.org/?probe=d72e78c1b0) | Apr 13, 2023 |
| Acer          | Aspire E5-771G              | Notebook    | [504d600530](https://linux-hardware.org/?probe=504d600530) | Apr 13, 2023 |
| HP            | Compaq Presario F700        | Notebook    | [2ae0d7557b](https://linux-hardware.org/?probe=2ae0d7557b) | Apr 13, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [ac4059b403](https://linux-hardware.org/?probe=ac4059b403) | Apr 13, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [6f7e9a6bb2](https://linux-hardware.org/?probe=6f7e9a6bb2) | Apr 13, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [27bfaf568a](https://linux-hardware.org/?probe=27bfaf568a) | Apr 12, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [653a25793d](https://linux-hardware.org/?probe=653a25793d) | Apr 12, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [dccecbecf9](https://linux-hardware.org/?probe=dccecbecf9) | Apr 12, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [878333e620](https://linux-hardware.org/?probe=878333e620) | Apr 12, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [b504683b39](https://linux-hardware.org/?probe=b504683b39) | Apr 12, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [8b8d053221](https://linux-hardware.org/?probe=8b8d053221) | Apr 12, 2023 |
| Toshiba       | Satellite C650D             | Notebook    | [fb8b24d111](https://linux-hardware.org/?probe=fb8b24d111) | Apr 12, 2023 |
| Gigabyte      | EX58-EXTREME                | Desktop     | [82a946e356](https://linux-hardware.org/?probe=82a946e356) | Apr 12, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [1627e0654a](https://linux-hardware.org/?probe=1627e0654a) | Apr 11, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [57aa7d103d](https://linux-hardware.org/?probe=57aa7d103d) | Apr 11, 2023 |
| ASUSTek       | P5K                         | Desktop     | [36bc294c5b](https://linux-hardware.org/?probe=36bc294c5b) | Apr 11, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [a2aa745e5c](https://linux-hardware.org/?probe=a2aa745e5c) | Apr 10, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [1bc09aed8a](https://linux-hardware.org/?probe=1bc09aed8a) | Apr 10, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [f847287142](https://linux-hardware.org/?probe=f847287142) | Apr 09, 2023 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [5c0467f4cb](https://linux-hardware.org/?probe=5c0467f4cb) | Apr 09, 2023 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [f410666614](https://linux-hardware.org/?probe=f410666614) | Apr 09, 2023 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [a651483f3c](https://linux-hardware.org/?probe=a651483f3c) | Apr 07, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [c871e7c68b](https://linux-hardware.org/?probe=c871e7c68b) | Apr 07, 2023 |
| Thomson       | WWNEO14C-4BK32F             | Notebook    | [8b461d224b](https://linux-hardware.org/?probe=8b461d224b) | Apr 06, 2023 |
| Quanta        | XV1                         | All in one  | [7cce1c6f6f](https://linux-hardware.org/?probe=7cce1c6f6f) | Apr 06, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [27e5e2df0d](https://linux-hardware.org/?probe=27e5e2df0d) | Apr 06, 2023 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [ecba971f16](https://linux-hardware.org/?probe=ecba971f16) | Apr 06, 2023 |
| HP            | ProBook 4540s               | Notebook    | [02754e47f3](https://linux-hardware.org/?probe=02754e47f3) | Apr 05, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [5363e4031e](https://linux-hardware.org/?probe=5363e4031e) | Apr 05, 2023 |
| ASUSTek       | H87-PRO                     | Desktop     | [085dc66a77](https://linux-hardware.org/?probe=085dc66a77) | Apr 05, 2023 |
| HP            | Notebook                    | Notebook    | [4ac4839ccd](https://linux-hardware.org/?probe=4ac4839ccd) | Apr 05, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [5a864191a9](https://linux-hardware.org/?probe=5a864191a9) | Apr 05, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [bb24498044](https://linux-hardware.org/?probe=bb24498044) | Apr 05, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [68d14e873f](https://linux-hardware.org/?probe=68d14e873f) | Apr 05, 2023 |
| eMachines     | MCP61PM-GM                  | Desktop     | [dc35ec4564](https://linux-hardware.org/?probe=dc35ec4564) | Apr 04, 2023 |
| Google        | Cyan                        | Notebook    | [f02aa2a210](https://linux-hardware.org/?probe=f02aa2a210) | Apr 04, 2023 |
| Gigabyte      | H410M S2 V3                 | Desktop     | [fdff0f112e](https://linux-hardware.org/?probe=fdff0f112e) | Apr 04, 2023 |
| HP            | 82B5                        | All in one  | [59fe255866](https://linux-hardware.org/?probe=59fe255866) | Apr 04, 2023 |
| Medion        | MS-7707                     | Desktop     | [c490d9dc74](https://linux-hardware.org/?probe=c490d9dc74) | Apr 04, 2023 |
| eMachines     | MCP61PM-GM                  | Desktop     | [59f9325843](https://linux-hardware.org/?probe=59f9325843) | Apr 03, 2023 |
| Toshiba       | Satellite C650              | Notebook    | [190547d5cd](https://linux-hardware.org/?probe=190547d5cd) | Apr 03, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [e05fcde338](https://linux-hardware.org/?probe=e05fcde338) | Apr 03, 2023 |
| Acer          | Veriton X4610G              | Desktop     | [49b3c45306](https://linux-hardware.org/?probe=49b3c45306) | Apr 03, 2023 |
| Dell          | Latitude E6430              | Notebook    | [5c205ea646](https://linux-hardware.org/?probe=5c205ea646) | Apr 03, 2023 |
| Fujitsu       | LIFEBOOK T935               | Notebook    | [1cc4178b9a](https://linux-hardware.org/?probe=1cc4178b9a) | Apr 02, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [f78d5a9d04](https://linux-hardware.org/?probe=f78d5a9d04) | Apr 02, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [45086032e1](https://linux-hardware.org/?probe=45086032e1) | Apr 02, 2023 |
| Notebook      | NJ50GU                      | Notebook    | [91e860cd94](https://linux-hardware.org/?probe=91e860cd94) | Apr 02, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [ea4626fdcc](https://linux-hardware.org/?probe=ea4626fdcc) | Apr 02, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [118effffda](https://linux-hardware.org/?probe=118effffda) | Apr 02, 2023 |
| Dell          | 0D883F A04                  | Desktop     | [5bdaaa0d23](https://linux-hardware.org/?probe=5bdaaa0d23) | Apr 02, 2023 |
| Lenovo        | V570 1066EDG                | Notebook    | [8a8a256b79](https://linux-hardware.org/?probe=8a8a256b79) | Apr 02, 2023 |
| Fujitsu       | STYLISTIC Q508              | Tablet      | [50862798b5](https://linux-hardware.org/?probe=50862798b5) | Apr 02, 2023 |
| Fujitsu       | STYLISTIC Q508              | Tablet      | [1340f929dd](https://linux-hardware.org/?probe=1340f929dd) | Apr 02, 2023 |
| HOUTER        | IPMIP-GS                    | Desktop     | [4ef0c7aaaa](https://linux-hardware.org/?probe=4ef0c7aaaa) | Apr 02, 2023 |
| Monster       | HUMA H4 V5.2                | Notebook    | [fdd74dbc8c](https://linux-hardware.org/?probe=fdd74dbc8c) | Apr 02, 2023 |
| Lenovo        | ThinkPad 10 20C3S0Q200      | Tablet      | [e014609915](https://linux-hardware.org/?probe=e014609915) | Apr 01, 2023 |
| Pegatron      | 2ACF                        | Desktop     | [c015b7fd50](https://linux-hardware.org/?probe=c015b7fd50) | Apr 01, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [644ab9aa21](https://linux-hardware.org/?probe=644ab9aa21) | Apr 01, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [61b490cae8](https://linux-hardware.org/?probe=61b490cae8) | Apr 01, 2023 |
| Lenovo        | ThinkPad 10 20C3S0Q200      | Tablet      | [9ee9bc67cf](https://linux-hardware.org/?probe=9ee9bc67cf) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | Desktop     | [1fb4c6ac6a](https://linux-hardware.org/?probe=1fb4c6ac6a) | Apr 01, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [2132a3308c](https://linux-hardware.org/?probe=2132a3308c) | Apr 01, 2023 |
| Acer          | Predator G3-605             | Desktop     | [eb21663788](https://linux-hardware.org/?probe=eb21663788) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | Desktop     | [80bb5bbf28](https://linux-hardware.org/?probe=80bb5bbf28) | Apr 01, 2023 |
| Lenovo        | ThinkPad T410 2518P9G       | Notebook    | [4f74fa6cd2](https://linux-hardware.org/?probe=4f74fa6cd2) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [1fa4ec7b05](https://linux-hardware.org/?probe=1fa4ec7b05) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | Desktop     | [2e79b95cb4](https://linux-hardware.org/?probe=2e79b95cb4) | Apr 01, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [1f0b0c32ca](https://linux-hardware.org/?probe=1f0b0c32ca) | Apr 01, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [22d22e0742](https://linux-hardware.org/?probe=22d22e0742) | Apr 01, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [2994622700](https://linux-hardware.org/?probe=2994622700) | Apr 01, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [af258dcd36](https://linux-hardware.org/?probe=af258dcd36) | Mar 31, 2023 |
| ASUSTek       | X450LD                      | Notebook    | [1ca0cdc1e8](https://linux-hardware.org/?probe=1ca0cdc1e8) | Mar 31, 2023 |
| Dell          | 0K240Y A02                  | Desktop     | [ca6aacf14e](https://linux-hardware.org/?probe=ca6aacf14e) | Mar 31, 2023 |
| Positivo      | S14SL01                     | Notebook    | [e1c79f71b7](https://linux-hardware.org/?probe=e1c79f71b7) | Mar 30, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [2c13e40cd2](https://linux-hardware.org/?probe=2c13e40cd2) | Mar 30, 2023 |
| ASUSTek       | Benicia                     | Desktop     | [7332efabad](https://linux-hardware.org/?probe=7332efabad) | Mar 30, 2023 |
| HP            | kip                         | Notebook    | [fe84eac39e](https://linux-hardware.org/?probe=fe84eac39e) | Mar 30, 2023 |
| Positivo      | Q232A                       | Notebook    | [2282c5ce96](https://linux-hardware.org/?probe=2282c5ce96) | Mar 30, 2023 |
| Apple         | Mac-F2268DC8                | All in one  | [0e8950a217](https://linux-hardware.org/?probe=0e8950a217) | Mar 30, 2023 |
| Positivo      | Q232A                       | Notebook    | [98e6b249af](https://linux-hardware.org/?probe=98e6b249af) | Mar 29, 2023 |
| HOUTER        | ORO-PC                      | Desktop     | [9547c4bdac](https://linux-hardware.org/?probe=9547c4bdac) | Mar 29, 2023 |
| Acer          | FIH57                       | All in one  | [7a6b0e67f0](https://linux-hardware.org/?probe=7a6b0e67f0) | Mar 29, 2023 |
| Dell          | Precision M4500             | Notebook    | [cf7e033a17](https://linux-hardware.org/?probe=cf7e033a17) | Mar 29, 2023 |
| Dell          | Latitude 7430               | Notebook    | [fdef205301](https://linux-hardware.org/?probe=fdef205301) | Mar 29, 2023 |
| Dell          | Latitude 3590               | Notebook    | [9b5971401c](https://linux-hardware.org/?probe=9b5971401c) | Mar 29, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [a927671ce2](https://linux-hardware.org/?probe=a927671ce2) | Mar 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ebf2728d28](https://linux-hardware.org/?probe=ebf2728d28) | Mar 29, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [422e4056ea](https://linux-hardware.org/?probe=422e4056ea) | Mar 28, 2023 |
| MSI           | B560M-A PRO                 | Desktop     | [62bfea11fe](https://linux-hardware.org/?probe=62bfea11fe) | Mar 28, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [c97dbb0917](https://linux-hardware.org/?probe=c97dbb0917) | Mar 28, 2023 |
| Thomson       | WWNEO14C-4BK32F             | Notebook    | [90fa9585c9](https://linux-hardware.org/?probe=90fa9585c9) | Mar 28, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [ccef379a7f](https://linux-hardware.org/?probe=ccef379a7f) | Mar 28, 2023 |
| Dell          | 06X1TJ A01                  | Desktop     | [7e99e3d73e](https://linux-hardware.org/?probe=7e99e3d73e) | Mar 28, 2023 |
| ASRock        | Z68 Pro3-M                  | Desktop     | [60f0809fbf](https://linux-hardware.org/?probe=60f0809fbf) | Mar 28, 2023 |
| Toshiba       | Satellite C55-A-1J8         | Notebook    | [c6ba40cd5c](https://linux-hardware.org/?probe=c6ba40cd5c) | Mar 27, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [dcbcf69a04](https://linux-hardware.org/?probe=dcbcf69a04) | Mar 27, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [dd242e4ae3](https://linux-hardware.org/?probe=dd242e4ae3) | Mar 27, 2023 |
| Dell          | 0J8H4R A00                  | Desktop     | [63d85fd315](https://linux-hardware.org/?probe=63d85fd315) | Mar 27, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [cf226d028d](https://linux-hardware.org/?probe=cf226d028d) | Mar 27, 2023 |
| HP            | 8430 1000                   | All in one  | [c0d9a96bbf](https://linux-hardware.org/?probe=c0d9a96bbf) | Mar 27, 2023 |
| Lenovo        | 11061GG ThinkServer TS13... | Desktop     | [174e514c30](https://linux-hardware.org/?probe=174e514c30) | Mar 26, 2023 |
| Packard Be... | MCP73PV                     | Desktop     | [87d1fd7511](https://linux-hardware.org/?probe=87d1fd7511) | Mar 26, 2023 |
| Dell          | 0GU083 A00                  | Desktop     | [e577b0129c](https://linux-hardware.org/?probe=e577b0129c) | Mar 26, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [05ecadea38](https://linux-hardware.org/?probe=05ecadea38) | Mar 26, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [76fc7291a6](https://linux-hardware.org/?probe=76fc7291a6) | Mar 26, 2023 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [c322e1c537](https://linux-hardware.org/?probe=c322e1c537) | Mar 26, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [7fa1fc4759](https://linux-hardware.org/?probe=7fa1fc4759) | Mar 26, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [cca501adf9](https://linux-hardware.org/?probe=cca501adf9) | Mar 26, 2023 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [b4787579d2](https://linux-hardware.org/?probe=b4787579d2) | Mar 25, 2023 |
| HP            | Compaq 6730s                | Notebook    | [ca30390612](https://linux-hardware.org/?probe=ca30390612) | Mar 25, 2023 |
| AZW           | MINI S                      | Desktop     | [f3381963ae](https://linux-hardware.org/?probe=f3381963ae) | Mar 25, 2023 |
| ASRock        | AB350 Gaming K4             | Desktop     | [ecc09c1362](https://linux-hardware.org/?probe=ecc09c1362) | Mar 25, 2023 |
| WEIPAI        | S15                         | Notebook    | [e6a15d7fa9](https://linux-hardware.org/?probe=e6a15d7fa9) | Mar 25, 2023 |
| HP            | Stream Notebook             | Notebook    | [b1ae4b8667](https://linux-hardware.org/?probe=b1ae4b8667) | Mar 25, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [ab9ed0121f](https://linux-hardware.org/?probe=ab9ed0121f) | Mar 25, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [38b08369e7](https://linux-hardware.org/?probe=38b08369e7) | Mar 25, 2023 |
| Dell          | Latitude E5510              | Notebook    | [8a9a1eec2c](https://linux-hardware.org/?probe=8a9a1eec2c) | Mar 24, 2023 |
| Framework     | Laptop                      | Notebook    | [4e1bd28ce3](https://linux-hardware.org/?probe=4e1bd28ce3) | Mar 24, 2023 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [ce9cdcc598](https://linux-hardware.org/?probe=ce9cdcc598) | Mar 24, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [628d2ea05c](https://linux-hardware.org/?probe=628d2ea05c) | Mar 24, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [e859e77bc7](https://linux-hardware.org/?probe=e859e77bc7) | Mar 24, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [efab305a00](https://linux-hardware.org/?probe=efab305a00) | Mar 24, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [ce7e17cb45](https://linux-hardware.org/?probe=ce7e17cb45) | Mar 24, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [05d4059f59](https://linux-hardware.org/?probe=05d4059f59) | Mar 24, 2023 |
| HP            | 255 G5                      | Notebook    | [99e2d83974](https://linux-hardware.org/?probe=99e2d83974) | Mar 24, 2023 |
| Acer          | FIH57                       | All in one  | [1f63978352](https://linux-hardware.org/?probe=1f63978352) | Mar 23, 2023 |
| Dell          | Inspiron 3721               | Notebook    | [e992b8f3a0](https://linux-hardware.org/?probe=e992b8f3a0) | Mar 23, 2023 |
| HP            | Pavilion 15                 | Notebook    | [32a0c3ec32](https://linux-hardware.org/?probe=32a0c3ec32) | Mar 23, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [78fab808a1](https://linux-hardware.org/?probe=78fab808a1) | Mar 23, 2023 |
| HP            | Pavilion dv6                | Notebook    | [625fff449a](https://linux-hardware.org/?probe=625fff449a) | Mar 23, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [c83000783a](https://linux-hardware.org/?probe=c83000783a) | Mar 23, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [e8ad290196](https://linux-hardware.org/?probe=e8ad290196) | Mar 23, 2023 |
| Intel         | G41                         | Desktop     | [c9fccfc8c1](https://linux-hardware.org/?probe=c9fccfc8c1) | Mar 22, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [d0b0015eb2](https://linux-hardware.org/?probe=d0b0015eb2) | Mar 22, 2023 |
| Orbsmart      | AW-11L                      | Mini pc     | [f66ed5bf1f](https://linux-hardware.org/?probe=f66ed5bf1f) | Mar 21, 2023 |
| Dell          | Latitude E7240              | Notebook    | [a3e408033c](https://linux-hardware.org/?probe=a3e408033c) | Mar 21, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [a6c90e3ad8](https://linux-hardware.org/?probe=a6c90e3ad8) | Mar 21, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [9409e4e133](https://linux-hardware.org/?probe=9409e4e133) | Mar 20, 2023 |
| Acer          | Revo RL80                   | Desktop     | [23ee51b834](https://linux-hardware.org/?probe=23ee51b834) | Mar 20, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [93ae4afbbc](https://linux-hardware.org/?probe=93ae4afbbc) | Mar 20, 2023 |
| Dell          | Inspiron 5405               | Notebook    | [bb59d0b5e9](https://linux-hardware.org/?probe=bb59d0b5e9) | Mar 20, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [e7344d03c0](https://linux-hardware.org/?probe=e7344d03c0) | Mar 20, 2023 |
| Apple         | Mac-F2208EC8                | Mini pc     | [4b47e3ed6c](https://linux-hardware.org/?probe=4b47e3ed6c) | Mar 20, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [cddf0b016f](https://linux-hardware.org/?probe=cddf0b016f) | Mar 20, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [75996f8bcf](https://linux-hardware.org/?probe=75996f8bcf) | Mar 19, 2023 |
| HP            | 158A                        | Desktop     | [61467de4d5](https://linux-hardware.org/?probe=61467de4d5) | Mar 19, 2023 |
| Acer          | TravelMate 2490             | Notebook    | [5a21a61bef](https://linux-hardware.org/?probe=5a21a61bef) | Mar 19, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [2b86166550](https://linux-hardware.org/?probe=2b86166550) | Mar 19, 2023 |
| Dell          | Inspiron 5423               | Notebook    | [70f51cbfcb](https://linux-hardware.org/?probe=70f51cbfcb) | Mar 19, 2023 |
| Google        | Kip                         | Notebook    | [84b79bf446](https://linux-hardware.org/?probe=84b79bf446) | Mar 19, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f0f20a06ef](https://linux-hardware.org/?probe=f0f20a06ef) | Mar 19, 2023 |
| Google        | Kip                         | Notebook    | [4e63ea7ac8](https://linux-hardware.org/?probe=4e63ea7ac8) | Mar 19, 2023 |
| Acer          | Aspire M3-581G              | Notebook    | [1434607f7e](https://linux-hardware.org/?probe=1434607f7e) | Mar 19, 2023 |
| Microtech     | CoreBook                    | Notebook    | [d50c0297a6](https://linux-hardware.org/?probe=d50c0297a6) | Mar 19, 2023 |
| HP            | 2B01                        | Desktop     | [1a096f9b36](https://linux-hardware.org/?probe=1a096f9b36) | Mar 19, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MZ    | Notebook    | [5c59b55c2a](https://linux-hardware.org/?probe=5c59b55c2a) | Mar 19, 2023 |
| Lenovo        | ThinkPad T420 4180RK8       | Notebook    | [752373923e](https://linux-hardware.org/?probe=752373923e) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [ee8b155a83](https://linux-hardware.org/?probe=ee8b155a83) | Mar 18, 2023 |
| Quanta        | XV1                         | All in one  | [2bbbb73d41](https://linux-hardware.org/?probe=2bbbb73d41) | Mar 18, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [314245636a](https://linux-hardware.org/?probe=314245636a) | Mar 18, 2023 |
| Dell          | Inspiron 3721               | Notebook    | [c7b5ea67bb](https://linux-hardware.org/?probe=c7b5ea67bb) | Mar 18, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [211a71ed78](https://linux-hardware.org/?probe=211a71ed78) | Mar 18, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [5f4a932bcd](https://linux-hardware.org/?probe=5f4a932bcd) | Mar 18, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [07dc0a0959](https://linux-hardware.org/?probe=07dc0a0959) | Mar 18, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [f61ec5ce9f](https://linux-hardware.org/?probe=f61ec5ce9f) | Mar 18, 2023 |
| HP            | 83E1                        | Desktop     | [2a1ade4f84](https://linux-hardware.org/?probe=2a1ade4f84) | Mar 17, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [76b31023a4](https://linux-hardware.org/?probe=76b31023a4) | Mar 17, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [901e03fa6e](https://linux-hardware.org/?probe=901e03fa6e) | Mar 17, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [a012da47e9](https://linux-hardware.org/?probe=a012da47e9) | Mar 17, 2023 |
| HP            | Pavilion dm1                | Notebook    | [8707341105](https://linux-hardware.org/?probe=8707341105) | Mar 16, 2023 |
| Alienware     | 15 R3                       | Notebook    | [c1f4b90efb](https://linux-hardware.org/?probe=c1f4b90efb) | Mar 16, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [a029e62352](https://linux-hardware.org/?probe=a029e62352) | Mar 16, 2023 |
| HP            | 158A                        | Desktop     | [4a023a55d8](https://linux-hardware.org/?probe=4a023a55d8) | Mar 16, 2023 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [06dd580c2e](https://linux-hardware.org/?probe=06dd580c2e) | Mar 16, 2023 |
| Google        | Babymega                    | Notebook    | [beead110bb](https://linux-hardware.org/?probe=beead110bb) | Mar 16, 2023 |
| Google        | Babymega                    | Notebook    | [0a45acf149](https://linux-hardware.org/?probe=0a45acf149) | Mar 16, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [d9e1bb3da7](https://linux-hardware.org/?probe=d9e1bb3da7) | Mar 16, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [3388dd991a](https://linux-hardware.org/?probe=3388dd991a) | Mar 15, 2023 |
| AZW           | GTR V01                     | Mini pc     | [98d84656e8](https://linux-hardware.org/?probe=98d84656e8) | Mar 15, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [f5175006b7](https://linux-hardware.org/?probe=f5175006b7) | Mar 15, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [9565625dc4](https://linux-hardware.org/?probe=9565625dc4) | Mar 15, 2023 |
| Lenovo        | ThinkPad T430 23492D1       | Notebook    | [34e2b05336](https://linux-hardware.org/?probe=34e2b05336) | Mar 14, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [f6a3a68640](https://linux-hardware.org/?probe=f6a3a68640) | Mar 14, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [cbb20e87cb](https://linux-hardware.org/?probe=cbb20e87cb) | Mar 14, 2023 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | Desktop     | [eb761f4a30](https://linux-hardware.org/?probe=eb761f4a30) | Mar 14, 2023 |
| ASUSTek       | U36SD                       | Notebook    | [74e2dfbbc6](https://linux-hardware.org/?probe=74e2dfbbc6) | Mar 14, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [cc372ccf7d](https://linux-hardware.org/?probe=cc372ccf7d) | Mar 14, 2023 |
| Dell          | Inspiron 5423               | Notebook    | [4987f344f2](https://linux-hardware.org/?probe=4987f344f2) | Mar 14, 2023 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [0f440670f2](https://linux-hardware.org/?probe=0f440670f2) | Mar 14, 2023 |
| Gigabyte      | H55M-S2H                    | Desktop     | [55d6288663](https://linux-hardware.org/?probe=55d6288663) | Mar 14, 2023 |
| Google        | Celes                       | Notebook    | [4fd0271747](https://linux-hardware.org/?probe=4fd0271747) | Mar 13, 2023 |
| HP            | 83E1                        | Desktop     | [d286798430](https://linux-hardware.org/?probe=d286798430) | Mar 13, 2023 |
| Soncview      | G41D3C                      | Desktop     | [877ff67a70](https://linux-hardware.org/?probe=877ff67a70) | Mar 13, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [77569b52db](https://linux-hardware.org/?probe=77569b52db) | Mar 13, 2023 |
| Quanta        | XV1                         | All in one  | [930e98f517](https://linux-hardware.org/?probe=930e98f517) | Mar 13, 2023 |
| HP            | Pavilion dv6                | Notebook    | [9d5d0051ea](https://linux-hardware.org/?probe=9d5d0051ea) | Mar 13, 2023 |
| Gigabyte      | H97M-D3H                    | Desktop     | [178af6e35b](https://linux-hardware.org/?probe=178af6e35b) | Mar 12, 2023 |
| HP            | Pavilion 15                 | Notebook    | [d5eb709e13](https://linux-hardware.org/?probe=d5eb709e13) | Mar 12, 2023 |
| HP            | 18E7                        | Desktop     | [2042edf904](https://linux-hardware.org/?probe=2042edf904) | Mar 12, 2023 |
| Toshiba       | PORTEGE X30-D               | Notebook    | [9b7e4e10af](https://linux-hardware.org/?probe=9b7e4e10af) | Mar 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [d777dadd73](https://linux-hardware.org/?probe=d777dadd73) | Mar 12, 2023 |
| HP            | Compaq nc6120 (PY505EA#A... | Notebook    | [2b864d8f97](https://linux-hardware.org/?probe=2b864d8f97) | Mar 12, 2023 |
| Novatech      | 15.6 nSpire Laptop          | Notebook    | [f5814aa2e6](https://linux-hardware.org/?probe=f5814aa2e6) | Mar 12, 2023 |
| HP            | 09CCh                       | Desktop     | [e122b11e42](https://linux-hardware.org/?probe=e122b11e42) | Mar 12, 2023 |
| Dell          | 0GM819                      | Desktop     | [1db4004d05](https://linux-hardware.org/?probe=1db4004d05) | Mar 12, 2023 |
| Medion        | MS-7707                     | Desktop     | [a0621e0cd1](https://linux-hardware.org/?probe=a0621e0cd1) | Mar 12, 2023 |
| Lenovo        | ThinkPad X270 20HMS1KL0C    | Notebook    | [f27bb76a32](https://linux-hardware.org/?probe=f27bb76a32) | Mar 12, 2023 |
| Gigabyte      | EX58-EXTREME                | Desktop     | [f45a0d4c01](https://linux-hardware.org/?probe=f45a0d4c01) | Mar 12, 2023 |
| Medion        | MS-7707                     | Desktop     | [4c9432026b](https://linux-hardware.org/?probe=4c9432026b) | Mar 12, 2023 |
| Acer          | TravelMate B113             | Notebook    | [e5f001172d](https://linux-hardware.org/?probe=e5f001172d) | Mar 12, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [91da2169aa](https://linux-hardware.org/?probe=91da2169aa) | Mar 12, 2023 |
| Gigabyte      | X670E AORUS XTREME          | Desktop     | [83cb566647](https://linux-hardware.org/?probe=83cb566647) | Mar 12, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [fd63e92774](https://linux-hardware.org/?probe=fd63e92774) | Mar 12, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [6a0426cb65](https://linux-hardware.org/?probe=6a0426cb65) | Mar 12, 2023 |
| Dell          | Latitude E5470              | Notebook    | [86adaddcae](https://linux-hardware.org/?probe=86adaddcae) | Mar 12, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [bd0c265909](https://linux-hardware.org/?probe=bd0c265909) | Mar 11, 2023 |
| Acer          | TravelMate B113             | Notebook    | [ba6dc5dcb5](https://linux-hardware.org/?probe=ba6dc5dcb5) | Mar 11, 2023 |
| Intel         | H61                         | Desktop     | [5650f6d211](https://linux-hardware.org/?probe=5650f6d211) | Mar 11, 2023 |
| HP            | Pavilion dv6                | Notebook    | [fca49aa86c](https://linux-hardware.org/?probe=fca49aa86c) | Mar 11, 2023 |
| Dell          | Latitude E5470              | Notebook    | [e7e23885b7](https://linux-hardware.org/?probe=e7e23885b7) | Mar 11, 2023 |
| Acer          | WG43M                       | Desktop     | [5858448536](https://linux-hardware.org/?probe=5858448536) | Mar 11, 2023 |
| Acer          | WG43M                       | Desktop     | [3d562885d0](https://linux-hardware.org/?probe=3d562885d0) | Mar 11, 2023 |
| HP            | 09CCh                       | Desktop     | [9421be2c59](https://linux-hardware.org/?probe=9421be2c59) | Mar 11, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [daad1ee8d5](https://linux-hardware.org/?probe=daad1ee8d5) | Mar 11, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [4b9462a4ff](https://linux-hardware.org/?probe=4b9462a4ff) | Mar 11, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [a47baaadde](https://linux-hardware.org/?probe=a47baaadde) | Mar 11, 2023 |
| HP            | Compaq nc6120 (PY505EA#A... | Notebook    | [c8d3cf3a4b](https://linux-hardware.org/?probe=c8d3cf3a4b) | Mar 11, 2023 |
| HP            | 2B3B                        | All in one  | [cb25c51987](https://linux-hardware.org/?probe=cb25c51987) | Mar 11, 2023 |
| ASUSTek       | T100TAM                     | Notebook    | [1d647e564b](https://linux-hardware.org/?probe=1d647e564b) | Mar 10, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [434a8e0e37](https://linux-hardware.org/?probe=434a8e0e37) | Mar 10, 2023 |
| Medion        | Akoya E1318T                | Notebook    | [8b24b109ec](https://linux-hardware.org/?probe=8b24b109ec) | Mar 10, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [6648af3696](https://linux-hardware.org/?probe=6648af3696) | Mar 10, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [807d1626b4](https://linux-hardware.org/?probe=807d1626b4) | Mar 10, 2023 |
| Toshiba       | Satellite L855              | Notebook    | [3b0a7cfbf0](https://linux-hardware.org/?probe=3b0a7cfbf0) | Mar 10, 2023 |
| Toshiba       | Satellite L855              | Notebook    | [08bfa4188e](https://linux-hardware.org/?probe=08bfa4188e) | Mar 10, 2023 |
| HP            | ProBook 4530s               | Notebook    | [e9c9dd943e](https://linux-hardware.org/?probe=e9c9dd943e) | Mar 10, 2023 |
| Dell          | Precision M6700             | Notebook    | [7a02d78344](https://linux-hardware.org/?probe=7a02d78344) | Mar 10, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [565c8963d4](https://linux-hardware.org/?probe=565c8963d4) | Mar 10, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [99d5f17b22](https://linux-hardware.org/?probe=99d5f17b22) | Mar 09, 2023 |
| Acer          | Aspire M3-581G              | Notebook    | [65b41dc560](https://linux-hardware.org/?probe=65b41dc560) | Mar 09, 2023 |
| HP            | Pavilion TS 15              | Notebook    | [5c0b7a773e](https://linux-hardware.org/?probe=5c0b7a773e) | Mar 09, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [bd1ab8d62d](https://linux-hardware.org/?probe=bd1ab8d62d) | Mar 09, 2023 |
| Dell          | Latitude 3180               | Notebook    | [07a18f8eb1](https://linux-hardware.org/?probe=07a18f8eb1) | Mar 09, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [6b906bab7d](https://linux-hardware.org/?probe=6b906bab7d) | Mar 09, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [9acfcb9b4f](https://linux-hardware.org/?probe=9acfcb9b4f) | Mar 09, 2023 |
| HP            | 81C7 MVB 0C                 | Server      | [2ad477ea6c](https://linux-hardware.org/?probe=2ad477ea6c) | Mar 09, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [1599d2a2ef](https://linux-hardware.org/?probe=1599d2a2ef) | Mar 09, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [21f11cf791](https://linux-hardware.org/?probe=21f11cf791) | Mar 09, 2023 |
| Unknown       | HX90                        | Desktop     | [21530c00a4](https://linux-hardware.org/?probe=21530c00a4) | Mar 09, 2023 |
| Multilaser    | PC130                       | Notebook    | [37212994df](https://linux-hardware.org/?probe=37212994df) | Mar 09, 2023 |
| Gigabyte      | Z370 HD3P-CF                | Desktop     | [8115c702cb](https://linux-hardware.org/?probe=8115c702cb) | Mar 09, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [5fd5c7db62](https://linux-hardware.org/?probe=5fd5c7db62) | Mar 09, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [0dc84b30aa](https://linux-hardware.org/?probe=0dc84b30aa) | Mar 09, 2023 |
| Lenovo        | ThinkPad 11e 20DAS0T500     | Notebook    | [e6fd8c46b0](https://linux-hardware.org/?probe=e6fd8c46b0) | Mar 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [d01b6ad50c](https://linux-hardware.org/?probe=d01b6ad50c) | Mar 08, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [cc455dcfac](https://linux-hardware.org/?probe=cc455dcfac) | Mar 08, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [fd255666fc](https://linux-hardware.org/?probe=fd255666fc) | Mar 08, 2023 |
| Dell          | Latitude E4310              | Notebook    | [8dbe3e01fa](https://linux-hardware.org/?probe=8dbe3e01fa) | Mar 08, 2023 |
| Gigabyte      | B450 GAMING X               | Desktop     | [6f7b473b62](https://linux-hardware.org/?probe=6f7b473b62) | Mar 08, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [a598fd0bed](https://linux-hardware.org/?probe=a598fd0bed) | Mar 08, 2023 |
| Lenovo        | YB1-X91F                    | Tablet      | [5582ce4ba9](https://linux-hardware.org/?probe=5582ce4ba9) | Mar 08, 2023 |
| ASRock        | B450M Pro4-F                | Desktop     | [5f93500136](https://linux-hardware.org/?probe=5f93500136) | Mar 08, 2023 |
| ASUSTek       | K54HR                       | Notebook    | [a7c688e9be](https://linux-hardware.org/?probe=a7c688e9be) | Mar 08, 2023 |
| ASRock        | B450M Pro4-F                | Desktop     | [fdba382132](https://linux-hardware.org/?probe=fdba382132) | Mar 08, 2023 |
| Dell          | Latitude 5310 2-in-1        | Convertible | [cccaedd7d3](https://linux-hardware.org/?probe=cccaedd7d3) | Mar 07, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [00ddbf4ad1](https://linux-hardware.org/?probe=00ddbf4ad1) | Mar 07, 2023 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [10c9c37ebc](https://linux-hardware.org/?probe=10c9c37ebc) | Mar 07, 2023 |
| ASUSTek       | P5GC-MX                     | Desktop     | [c7ccf3de7b](https://linux-hardware.org/?probe=c7ccf3de7b) | Mar 07, 2023 |
| Google        | Candy                       | Notebook    | [e74102ff2c](https://linux-hardware.org/?probe=e74102ff2c) | Mar 07, 2023 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [aa987a6626](https://linux-hardware.org/?probe=aa987a6626) | Mar 07, 2023 |
| Lenovo        | ThinkPad X240 20AMA3PVAR    | Notebook    | [367f53195a](https://linux-hardware.org/?probe=367f53195a) | Mar 07, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [0a85b4da67](https://linux-hardware.org/?probe=0a85b4da67) | Mar 07, 2023 |
| Lenovo        | ThinkPad L480 20LS001AMX    | Notebook    | [3f1ebc8271](https://linux-hardware.org/?probe=3f1ebc8271) | Mar 07, 2023 |
| Google        | Lillipup                    | Notebook    | [33350c987b](https://linux-hardware.org/?probe=33350c987b) | Mar 07, 2023 |
| Chuwi         | HeroBox                     | Mini pc     | [6e8a20eb98](https://linux-hardware.org/?probe=6e8a20eb98) | Mar 07, 2023 |
| Packard Be... | EasyNote TM82               | Notebook    | [33de288525](https://linux-hardware.org/?probe=33de288525) | Mar 07, 2023 |
| Gigabyte      | H61M-S2P-B3                 | Desktop     | [83c569f727](https://linux-hardware.org/?probe=83c569f727) | Mar 06, 2023 |
| Gigabyte      | H61M-S2P-B3                 | Desktop     | [ca3531a813](https://linux-hardware.org/?probe=ca3531a813) | Mar 06, 2023 |
| HP            | 81C7 MVB 0C                 | Server      | [e717a99f1f](https://linux-hardware.org/?probe=e717a99f1f) | Mar 06, 2023 |
| YJKC          | vBOOK Plus RVP7             | Notebook    | [acdf0dca1d](https://linux-hardware.org/?probe=acdf0dca1d) | Mar 06, 2023 |
| Google        | Lillipup                    | Notebook    | [214481f959](https://linux-hardware.org/?probe=214481f959) | Mar 06, 2023 |
| Dell          | 0JC474                      | Desktop     | [90db9efd8d](https://linux-hardware.org/?probe=90db9efd8d) | Mar 06, 2023 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [7c9b56f288](https://linux-hardware.org/?probe=7c9b56f288) | Mar 05, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [df192a1871](https://linux-hardware.org/?probe=df192a1871) | Mar 05, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [12c8945329](https://linux-hardware.org/?probe=12c8945329) | Mar 05, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [d1a55c59a3](https://linux-hardware.org/?probe=d1a55c59a3) | Mar 05, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [657175938b](https://linux-hardware.org/?probe=657175938b) | Mar 05, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [47eeabee04](https://linux-hardware.org/?probe=47eeabee04) | Mar 05, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [f3c06b377f](https://linux-hardware.org/?probe=f3c06b377f) | Mar 04, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [05507dab01](https://linux-hardware.org/?probe=05507dab01) | Mar 04, 2023 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [240adbe154](https://linux-hardware.org/?probe=240adbe154) | Mar 04, 2023 |
| Timi          | TM1701                      | Notebook    | [4faac58613](https://linux-hardware.org/?probe=4faac58613) | Mar 04, 2023 |
| Lenovo        | ThinkPad X201 3680Z38       | Notebook    | [414dc8dc29](https://linux-hardware.org/?probe=414dc8dc29) | Mar 04, 2023 |
| Lenovo        | ThinkPad X201 3680Z38       | Notebook    | [3e60e33df2](https://linux-hardware.org/?probe=3e60e33df2) | Mar 04, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [c16eae7537](https://linux-hardware.org/?probe=c16eae7537) | Mar 04, 2023 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [829848b662](https://linux-hardware.org/?probe=829848b662) | Mar 04, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [767045c44e](https://linux-hardware.org/?probe=767045c44e) | Mar 03, 2023 |
| ASRock        | Wolfdale1333-D667           | Desktop     | [7dd4939e64](https://linux-hardware.org/?probe=7dd4939e64) | Mar 03, 2023 |
| Unknown       | Rev.00                      | Desktop     | [89ff2d84f4](https://linux-hardware.org/?probe=89ff2d84f4) | Mar 03, 2023 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [80e66c5eac](https://linux-hardware.org/?probe=80e66c5eac) | Mar 03, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [1237954f03](https://linux-hardware.org/?probe=1237954f03) | Mar 03, 2023 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [52b68672fc](https://linux-hardware.org/?probe=52b68672fc) | Mar 03, 2023 |
| ReachingTe... | DreamQuest Pro 2022         | Mini pc     | [03db87f6d8](https://linux-hardware.org/?probe=03db87f6d8) | Mar 03, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [1e039a31d1](https://linux-hardware.org/?probe=1e039a31d1) | Mar 03, 2023 |
| ASUSTek       | UX331UA                     | Notebook    | [310d69ff6f](https://linux-hardware.org/?probe=310d69ff6f) | Mar 03, 2023 |
| AZW           | GTR V01                     | Mini pc     | [fb4847e7ac](https://linux-hardware.org/?probe=fb4847e7ac) | Mar 03, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [81889ddc9c](https://linux-hardware.org/?probe=81889ddc9c) | Mar 02, 2023 |
| Lenovo        | ThinkPad X230 2333BR3       | Notebook    | [a3b6a280c1](https://linux-hardware.org/?probe=a3b6a280c1) | Mar 02, 2023 |
| HP            | Notebook                    | Notebook    | [453811c44a](https://linux-hardware.org/?probe=453811c44a) | Mar 02, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [188ba8d836](https://linux-hardware.org/?probe=188ba8d836) | Mar 02, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [0ad3a8182e](https://linux-hardware.org/?probe=0ad3a8182e) | Mar 02, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [5729d41d01](https://linux-hardware.org/?probe=5729d41d01) | Mar 02, 2023 |
| Toshiba       | Satellite A100              | Notebook    | [51e1183b15](https://linux-hardware.org/?probe=51e1183b15) | Mar 02, 2023 |
| ASUSTek       | UX331UA                     | Notebook    | [52c7446693](https://linux-hardware.org/?probe=52c7446693) | Mar 02, 2023 |
| Lenovo        | ThinkPad X230 2333BR3       | Notebook    | [7b17e49d0f](https://linux-hardware.org/?probe=7b17e49d0f) | Mar 02, 2023 |
| ASUSTek       | X200MA                      | Notebook    | [95b0a4d944](https://linux-hardware.org/?probe=95b0a4d944) | Mar 02, 2023 |
| HP            | 805D                        | Desktop     | [4638c85566](https://linux-hardware.org/?probe=4638c85566) | Mar 01, 2023 |
| ASUSTek       | ROG Strix G713IH_G713IH     | Notebook    | [e9b7ee04ec](https://linux-hardware.org/?probe=e9b7ee04ec) | Mar 01, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [fa7df5da3b](https://linux-hardware.org/?probe=fa7df5da3b) | Mar 01, 2023 |
| Toshiba       | Satellite S55t-B            | Notebook    | [69734289ba](https://linux-hardware.org/?probe=69734289ba) | Mar 01, 2023 |
| MSI           | Raider GE66 12UHS           | Notebook    | [3fcfdd9fba](https://linux-hardware.org/?probe=3fcfdd9fba) | Mar 01, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [a8b1a02128](https://linux-hardware.org/?probe=a8b1a02128) | Mar 01, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [480ff87a20](https://linux-hardware.org/?probe=480ff87a20) | Feb 28, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [c698fc199a](https://linux-hardware.org/?probe=c698fc199a) | Feb 28, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [b4be9a72dd](https://linux-hardware.org/?probe=b4be9a72dd) | Feb 28, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [66e63a311d](https://linux-hardware.org/?probe=66e63a311d) | Feb 28, 2023 |
| HP            | ENVY 17                     | Notebook    | [61d1252ef3](https://linux-hardware.org/?probe=61d1252ef3) | Feb 28, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [4f835a4f35](https://linux-hardware.org/?probe=4f835a4f35) | Feb 28, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [7478549a38](https://linux-hardware.org/?probe=7478549a38) | Feb 28, 2023 |
| Dell          | Latitude E6440              | Notebook    | [80131cd2a4](https://linux-hardware.org/?probe=80131cd2a4) | Feb 28, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [ca7d449be6](https://linux-hardware.org/?probe=ca7d449be6) | Feb 28, 2023 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | Desktop     | [75e0fb99ed](https://linux-hardware.org/?probe=75e0fb99ed) | Feb 28, 2023 |
| Lenovo        | ThinkPad R400 7439W2F       | Notebook    | [2673ce6bd9](https://linux-hardware.org/?probe=2673ce6bd9) | Feb 27, 2023 |
| Google        | Buddy                       | Desktop     | [ac3d9aaed0](https://linux-hardware.org/?probe=ac3d9aaed0) | Feb 27, 2023 |
| Dell          | Inspiron 3793               | Notebook    | [d7b51f6048](https://linux-hardware.org/?probe=d7b51f6048) | Feb 27, 2023 |
| AZW           | SER                         | Mini pc     | [e086890e6a](https://linux-hardware.org/?probe=e086890e6a) | Feb 27, 2023 |
| HP            | Pavilion dv7                | Notebook    | [d5da5f62b8](https://linux-hardware.org/?probe=d5da5f62b8) | Feb 27, 2023 |
| Acer          | TravelMate B113             | Notebook    | [31691f9681](https://linux-hardware.org/?probe=31691f9681) | Feb 27, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [42acb38635](https://linux-hardware.org/?probe=42acb38635) | Feb 27, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [e8c76a33fe](https://linux-hardware.org/?probe=e8c76a33fe) | Feb 27, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [7f907fadb7](https://linux-hardware.org/?probe=7f907fadb7) | Feb 27, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [766991da5e](https://linux-hardware.org/?probe=766991da5e) | Feb 27, 2023 |
| Dell          | Vostro 1540                 | Notebook    | [8f09ea4351](https://linux-hardware.org/?probe=8f09ea4351) | Feb 27, 2023 |
| HP            | ENVY m7 Notebook            | Notebook    | [14374fbcc8](https://linux-hardware.org/?probe=14374fbcc8) | Feb 27, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [6c62bbbf3b](https://linux-hardware.org/?probe=6c62bbbf3b) | Feb 27, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [2479c3c245](https://linux-hardware.org/?probe=2479c3c245) | Feb 27, 2023 |
| HP            | 1998                        | Desktop     | [90794415e9](https://linux-hardware.org/?probe=90794415e9) | Feb 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [a21ea9613b](https://linux-hardware.org/?probe=a21ea9613b) | Feb 26, 2023 |
| Lenovo        | V570 1066EDG                | Notebook    | [deb326cc4b](https://linux-hardware.org/?probe=deb326cc4b) | Feb 26, 2023 |
| Lenovo        | V570 1066EDG                | Notebook    | [cc220b6122](https://linux-hardware.org/?probe=cc220b6122) | Feb 26, 2023 |
| HP            | 620                         | Notebook    | [e3bf80caf7](https://linux-hardware.org/?probe=e3bf80caf7) | Feb 25, 2023 |
| Quanta        | XV1                         | All in one  | [fa596130ae](https://linux-hardware.org/?probe=fa596130ae) | Feb 25, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [57a009cdd4](https://linux-hardware.org/?probe=57a009cdd4) | Feb 25, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [fc1a3d88ae](https://linux-hardware.org/?probe=fc1a3d88ae) | Feb 25, 2023 |
| MSI           | H81M-P33                    | Desktop     | [1bc1cedec6](https://linux-hardware.org/?probe=1bc1cedec6) | Feb 25, 2023 |
| Dell          | Latitude E6440              | Notebook    | [a4139e4774](https://linux-hardware.org/?probe=a4139e4774) | Feb 25, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [eca93ca661](https://linux-hardware.org/?probe=eca93ca661) | Feb 25, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [7357439273](https://linux-hardware.org/?probe=7357439273) | Feb 25, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [7f88a11698](https://linux-hardware.org/?probe=7f88a11698) | Feb 25, 2023 |
| HP            | 2AF7                        | Desktop     | [a8eba0b0c4](https://linux-hardware.org/?probe=a8eba0b0c4) | Feb 25, 2023 |
| HP            | 2AF7                        | Desktop     | [3bf3afd1d5](https://linux-hardware.org/?probe=3bf3afd1d5) | Feb 25, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [85ea6dded1](https://linux-hardware.org/?probe=85ea6dded1) | Feb 24, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [1fb9cfd7d4](https://linux-hardware.org/?probe=1fb9cfd7d4) | Feb 24, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [bafb67390c](https://linux-hardware.org/?probe=bafb67390c) | Feb 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [602cac9f15](https://linux-hardware.org/?probe=602cac9f15) | Feb 24, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [3b27d3609f](https://linux-hardware.org/?probe=3b27d3609f) | Feb 24, 2023 |
| HP            | ProBook 4545s               | Notebook    | [0f56422e2d](https://linux-hardware.org/?probe=0f56422e2d) | Feb 24, 2023 |
| HP            | 2129                        | Desktop     | [5118eb06d4](https://linux-hardware.org/?probe=5118eb06d4) | Feb 24, 2023 |
| ASUSTek       | T100TAF                     | Notebook    | [4fce660f2d](https://linux-hardware.org/?probe=4fce660f2d) | Feb 23, 2023 |
| Dell          | Latitude 7480               | Notebook    | [fd80b301db](https://linux-hardware.org/?probe=fd80b301db) | Feb 23, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [f283ae7cb2](https://linux-hardware.org/?probe=f283ae7cb2) | Feb 23, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [294c5c45e6](https://linux-hardware.org/?probe=294c5c45e6) | Feb 23, 2023 |
| ASUSTek       | P7H55-M/USB3                | Desktop     | [472721d72c](https://linux-hardware.org/?probe=472721d72c) | Feb 22, 2023 |
| DERE          | V14                         | Notebook    | [bb2d40e676](https://linux-hardware.org/?probe=bb2d40e676) | Feb 22, 2023 |
| HP            | 2129                        | Desktop     | [5a6b1e7169](https://linux-hardware.org/?probe=5a6b1e7169) | Feb 21, 2023 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [e861797e74](https://linux-hardware.org/?probe=e861797e74) | Feb 21, 2023 |
| HP            | ENVY 17                     | Notebook    | [ea0b2e63ef](https://linux-hardware.org/?probe=ea0b2e63ef) | Feb 21, 2023 |
| ASUSTek       | F2A55-M                     | Desktop     | [c9d150f24c](https://linux-hardware.org/?probe=c9d150f24c) | Feb 21, 2023 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [40e2157901](https://linux-hardware.org/?probe=40e2157901) | Feb 21, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [9a9c8192de](https://linux-hardware.org/?probe=9a9c8192de) | Feb 21, 2023 |
| Teclast       | F7                          | Notebook    | [3f5fdc3aa9](https://linux-hardware.org/?probe=3f5fdc3aa9) | Feb 21, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [5d32bc7f7c](https://linux-hardware.org/?probe=5d32bc7f7c) | Feb 21, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [a00e724475](https://linux-hardware.org/?probe=a00e724475) | Feb 21, 2023 |
| HP            | 1850                        | Desktop     | [f184ff6250](https://linux-hardware.org/?probe=f184ff6250) | Feb 21, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | Desktop     | [e062475561](https://linux-hardware.org/?probe=e062475561) | Feb 20, 2023 |
| Dell          | System XPS L502X            | Notebook    | [7352f47bb0](https://linux-hardware.org/?probe=7352f47bb0) | Feb 20, 2023 |
| Apple         | MacBookAir7,1               | Notebook    | [5002433b97](https://linux-hardware.org/?probe=5002433b97) | Feb 20, 2023 |
| HP            | 620                         | Notebook    | [c3dae62545](https://linux-hardware.org/?probe=c3dae62545) | Feb 20, 2023 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [882e2c977d](https://linux-hardware.org/?probe=882e2c977d) | Feb 20, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [115fa87a77](https://linux-hardware.org/?probe=115fa87a77) | Feb 20, 2023 |
| Dell          | Latitude E5440              | Notebook    | [10b94a411c](https://linux-hardware.org/?probe=10b94a411c) | Feb 20, 2023 |
| HP            | Laptop 15s-dr0xxx           | Notebook    | [6733a448f9](https://linux-hardware.org/?probe=6733a448f9) | Feb 20, 2023 |
| eMachines     | MCP61PM-GM                  | Desktop     | [aeafa2dbee](https://linux-hardware.org/?probe=aeafa2dbee) | Feb 19, 2023 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [d20a6e81f8](https://linux-hardware.org/?probe=d20a6e81f8) | Feb 19, 2023 |
| Toshiba       | Satellite L50-B             | Notebook    | [3c53a60245](https://linux-hardware.org/?probe=3c53a60245) | Feb 19, 2023 |
| Toshiba       | Satellite L50D-B            | Notebook    | [689c37d3b7](https://linux-hardware.org/?probe=689c37d3b7) | Feb 19, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | Desktop     | [5d6240bcc6](https://linux-hardware.org/?probe=5d6240bcc6) | Feb 19, 2023 |
| ASUSTek       | Zenbook UX562UG_Q508UG      | Convertible | [2bb870a042](https://linux-hardware.org/?probe=2bb870a042) | Feb 19, 2023 |
| Lenovo        | ThinkPad T460 20FN003LMZ    | Notebook    | [1752223e74](https://linux-hardware.org/?probe=1752223e74) | Feb 19, 2023 |
| HOUTER        | ORO-PC                      | Desktop     | [09aad96389](https://linux-hardware.org/?probe=09aad96389) | Feb 19, 2023 |
| Gigabyte      | H97M-D3H                    | Desktop     | [be0f73193d](https://linux-hardware.org/?probe=be0f73193d) | Feb 19, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [752cdf5b2b](https://linux-hardware.org/?probe=752cdf5b2b) | Feb 19, 2023 |
| Gigabyte      | H97M-D3H                    | Desktop     | [c784a261d4](https://linux-hardware.org/?probe=c784a261d4) | Feb 19, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [d6f4d9d8df](https://linux-hardware.org/?probe=d6f4d9d8df) | Feb 19, 2023 |
| Multilaser    | PC130                       | Notebook    | [3526846c1f](https://linux-hardware.org/?probe=3526846c1f) | Feb 19, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [16350a9c3b](https://linux-hardware.org/?probe=16350a9c3b) | Feb 19, 2023 |
| Lenovo        | ThinkPad T570 20H90002MZ    | Notebook    | [6694311da2](https://linux-hardware.org/?probe=6694311da2) | Feb 19, 2023 |
| HOUTER        | ORO-PC                      | Desktop     | [af7ffdc7a9](https://linux-hardware.org/?probe=af7ffdc7a9) | Feb 18, 2023 |
| Lenovo        | ThinkPad T550 20CK003LMZ    | Notebook    | [e3b00dc0f6](https://linux-hardware.org/?probe=e3b00dc0f6) | Feb 18, 2023 |
| HP            | Unknown                     | Notebook    | [3fea6a053b](https://linux-hardware.org/?probe=3fea6a053b) | Feb 18, 2023 |
| Lenovo        | ThinkPad T560 20FJS24T00    | Notebook    | [91a1aa0a0d](https://linux-hardware.org/?probe=91a1aa0a0d) | Feb 18, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MZ    | Notebook    | [bba1f53762](https://linux-hardware.org/?probe=bba1f53762) | Feb 18, 2023 |
| ASUSTek       | P5KC                        | Desktop     | [b2a9f21210](https://linux-hardware.org/?probe=b2a9f21210) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [6cc82a744e](https://linux-hardware.org/?probe=6cc82a744e) | Feb 18, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [215ae5796f](https://linux-hardware.org/?probe=215ae5796f) | Feb 18, 2023 |
| HP            | ENVY 17                     | Notebook    | [de8af1b249](https://linux-hardware.org/?probe=de8af1b249) | Feb 18, 2023 |
| Dell          | Inspiron 14 Plus 7420       | Notebook    | [59387e9081](https://linux-hardware.org/?probe=59387e9081) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [96c9f07207](https://linux-hardware.org/?probe=96c9f07207) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [2734c1a2ae](https://linux-hardware.org/?probe=2734c1a2ae) | Feb 18, 2023 |
| Medion        | E7220                       | Notebook    | [289b7dc6aa](https://linux-hardware.org/?probe=289b7dc6aa) | Feb 17, 2023 |
| MSI           | H270 PC MATE                | Desktop     | [6581748d54](https://linux-hardware.org/?probe=6581748d54) | Feb 17, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [48bbbc04c4](https://linux-hardware.org/?probe=48bbbc04c4) | Feb 17, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [9b35a3205f](https://linux-hardware.org/?probe=9b35a3205f) | Feb 17, 2023 |
| ASUSTek       | X450LD                      | Notebook    | [b4fb1ddc5a](https://linux-hardware.org/?probe=b4fb1ddc5a) | Feb 17, 2023 |
| Google        | Robo                        | Notebook    | [303c72db93](https://linux-hardware.org/?probe=303c72db93) | Feb 17, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [529e0929d2](https://linux-hardware.org/?probe=529e0929d2) | Feb 17, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [88d9514231](https://linux-hardware.org/?probe=88d9514231) | Feb 17, 2023 |
| Dell          | Inspiron 3793               | Notebook    | [b997f44969](https://linux-hardware.org/?probe=b997f44969) | Feb 16, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [97e017594b](https://linux-hardware.org/?probe=97e017594b) | Feb 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [8043264215](https://linux-hardware.org/?probe=8043264215) | Feb 16, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [51b7c93a69](https://linux-hardware.org/?probe=51b7c93a69) | Feb 16, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [4275665066](https://linux-hardware.org/?probe=4275665066) | Feb 16, 2023 |
| Quanta        | XV1                         | All in one  | [6c4ea36dc2](https://linux-hardware.org/?probe=6c4ea36dc2) | Feb 16, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [c08ad0f295](https://linux-hardware.org/?probe=c08ad0f295) | Feb 16, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [a37ac85ec2](https://linux-hardware.org/?probe=a37ac85ec2) | Feb 16, 2023 |
| HP            | ENVY TS Sleekbook 4         | Notebook    | [1189701feb](https://linux-hardware.org/?probe=1189701feb) | Feb 15, 2023 |
| Acer          | Extensa 5230                | Notebook    | [2716bcf519](https://linux-hardware.org/?probe=2716bcf519) | Feb 15, 2023 |
| Dell          | Latitude 3320               | Notebook    | [fecee449d4](https://linux-hardware.org/?probe=fecee449d4) | Feb 15, 2023 |
| MSI           | Z370M MORTAR                | Desktop     | [5ac9c9a924](https://linux-hardware.org/?probe=5ac9c9a924) | Feb 15, 2023 |
| Lenovo        | ThinkPad L480 20LS001AMX    | Notebook    | [6c1c0027b1](https://linux-hardware.org/?probe=6c1c0027b1) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c2d957f650](https://linux-hardware.org/?probe=c2d957f650) | Feb 15, 2023 |
| Dell          | System XPS L502X            | Notebook    | [2ea016be2a](https://linux-hardware.org/?probe=2ea016be2a) | Feb 14, 2023 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [b9301138cc](https://linux-hardware.org/?probe=b9301138cc) | Feb 14, 2023 |
| Apple         | MacBook2,1                  | Notebook    | [915e87767b](https://linux-hardware.org/?probe=915e87767b) | Feb 14, 2023 |
| Dell          | Latitude 5480               | Notebook    | [03123ee601](https://linux-hardware.org/?probe=03123ee601) | Feb 14, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [995da369f0](https://linux-hardware.org/?probe=995da369f0) | Feb 14, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | Desktop     | [b6b09f6455](https://linux-hardware.org/?probe=b6b09f6455) | Feb 14, 2023 |
| Gigabyte      | 945GZM-S2                   | Desktop     | [e271dc0c66](https://linux-hardware.org/?probe=e271dc0c66) | Feb 14, 2023 |
| IBM           | ThinkPad T40p 2373CG6       | Notebook    | [a7aa67f64e](https://linux-hardware.org/?probe=a7aa67f64e) | Feb 14, 2023 |
| IBM           | ThinkPad T40p 2373CG6       | Notebook    | [eda645cefe](https://linux-hardware.org/?probe=eda645cefe) | Feb 14, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [92fc220243](https://linux-hardware.org/?probe=92fc220243) | Feb 14, 2023 |
| Google        | Teemo                       | Desktop     | [53bf6d19ca](https://linux-hardware.org/?probe=53bf6d19ca) | Feb 14, 2023 |
| Samsung       | 700T1C                      | Notebook    | [66c15f037d](https://linux-hardware.org/?probe=66c15f037d) | Feb 14, 2023 |
| Samsung       | 700T1C                      | Notebook    | [9e154ea3a4](https://linux-hardware.org/?probe=9e154ea3a4) | Feb 14, 2023 |
| MSI           | MS-B9181                    | Desktop     | [a155bc9fc3](https://linux-hardware.org/?probe=a155bc9fc3) | Feb 13, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [1e3c885566](https://linux-hardware.org/?probe=1e3c885566) | Feb 13, 2023 |
| Dell          | 0Y7WYT A00                  | Desktop     | [e289b5bb8d](https://linux-hardware.org/?probe=e289b5bb8d) | Feb 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [5efd07985b](https://linux-hardware.org/?probe=5efd07985b) | Feb 13, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [d1edc30dac](https://linux-hardware.org/?probe=d1edc30dac) | Feb 13, 2023 |
| Lenovo        | IdeaPad U330p 20267         | Notebook    | [de30205f54](https://linux-hardware.org/?probe=de30205f54) | Feb 12, 2023 |
| Lenovo        | IdeaPad U330p 20267         | Notebook    | [19700ab1bd](https://linux-hardware.org/?probe=19700ab1bd) | Feb 12, 2023 |
| Alienware     | 0N43JM A00                  | Desktop     | [ef1d9239ab](https://linux-hardware.org/?probe=ef1d9239ab) | Feb 12, 2023 |
| Lenovo        | ThinkServer TS140           | Desktop     | [59eeaafe59](https://linux-hardware.org/?probe=59eeaafe59) | Feb 12, 2023 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [45f78c29cb](https://linux-hardware.org/?probe=45f78c29cb) | Feb 12, 2023 |
| HP            | Compaq 6730b (NB034ET#UU... | Notebook    | [baa5f72e80](https://linux-hardware.org/?probe=baa5f72e80) | Feb 12, 2023 |
| HP            | Notebook                    | Notebook    | [a17adfd867](https://linux-hardware.org/?probe=a17adfd867) | Feb 12, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [498c449a46](https://linux-hardware.org/?probe=498c449a46) | Feb 12, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Zorin 16 | 3149      | 63.3%   |
| Zorin 15 | 1630      | 32.76%  |
| Zorin 12 | 196       | 3.94%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| Zorin | 4960      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.0-56-generic | 225       | 3.97%   |
| 5.11.0-38-generic | 180       | 3.17%   |
| 5.11.0-27-generic | 155       | 2.73%   |
| 5.15.0-46-generic | 152       | 2.68%   |
| 5.15.0-52-generic | 151       | 2.66%   |
| 5.15.0-58-generic | 150       | 2.65%   |
| 5.15.0-67-generic | 141       | 2.49%   |
| 5.15.0-69-generic | 136       | 2.4%    |
| 5.13.0-30-generic | 126       | 2.22%   |
| 5.11.0-40-generic | 124       | 2.19%   |
| 5.13.0-39-generic | 121       | 2.13%   |
| 5.3.0-40-generic  | 110       | 1.94%   |
| 5.15.0-60-generic | 107       | 1.89%   |
| 5.11.0-41-generic | 107       | 1.89%   |
| 5.11.0-37-generic | 107       | 1.89%   |
| 5.11.0-43-generic | 101       | 1.78%   |
| 5.4.0-42-generic  | 99        | 1.75%   |
| 5.15.0-71-generic | 98        | 1.73%   |
| 5.15.0-48-generic | 95        | 1.68%   |
| 5.11.0-34-generic | 94        | 1.66%   |
| 5.13.0-40-generic | 90        | 1.59%   |
| 5.15.0-53-generic | 81        | 1.43%   |
| 5.0.0-37-generic  | 79        | 1.39%   |
| 5.15.0-41-generic | 76        | 1.34%   |
| 5.13.0-44-generic | 76        | 1.34%   |
| 5.13.0-35-generic | 74        | 1.31%   |
| 5.3.0-46-generic  | 73        | 1.29%   |
| 5.13.0-28-generic | 73        | 1.29%   |
| 5.3.0-51-generic  | 65        | 1.15%   |
| 5.15.0-73-generic | 62        | 1.09%   |
| 5.4.0-47-generic  | 61        | 1.08%   |
| 5.13.0-52-generic | 59        | 1.04%   |
| 5.13.0-27-generic | 59        | 1.04%   |
| 5.15.0-72-generic | 57        | 1.01%   |
| 5.4.0-58-generic  | 54        | 0.95%   |
| 5.3.0-53-generic  | 54        | 0.95%   |
| 5.13.0-41-generic | 54        | 0.95%   |
| 5.3.0-42-generic  | 52        | 0.92%   |
| 5.4.0-48-generic  | 48        | 0.85%   |
| 5.4.0-65-generic  | 46        | 0.81%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 1474      | 28.47%  |
| 5.4.0   | 954       | 18.43%  |
| 5.11.0  | 950       | 18.35%  |
| 5.13.0  | 768       | 14.83%  |
| 5.3.0   | 487       | 9.41%   |
| 4.15.0  | 189       | 3.65%   |
| 5.0.0   | 153       | 2.96%   |
| 4.18.0  | 76        | 1.47%   |
| 5.8.0   | 54        | 1.04%   |
| 5.14.0  | 10        | 0.19%   |
| 4.4.0   | 6         | 0.12%   |
| 5.7.1   | 3         | 0.06%   |
| 6.3.2   | 2         | 0.04%   |
| 5.7.0   | 2         | 0.04%   |
| 5.6.0   | 2         | 0.04%   |
| 5.19.12 | 2         | 0.04%   |
| 5.18.15 | 2         | 0.04%   |
| 5.17.5  | 2         | 0.04%   |
| 5.17.1  | 2         | 0.04%   |
| 5.16.0  | 2         | 0.04%   |
| 5.10.0  | 2         | 0.04%   |
| 4.13.0  | 2         | 0.04%   |
| 6.3.1   | 1         | 0.02%   |
| 6.2.7   | 1         | 0.02%   |
| 6.2.16  | 1         | 0.02%   |
| 6.2.14  | 1         | 0.02%   |
| 6.1.8   | 1         | 0.02%   |
| 6.1.7   | 1         | 0.02%   |
| 6.0.9   | 1         | 0.02%   |
| 6.0.8   | 1         | 0.02%   |
| 6.0.19  | 1         | 0.02%   |
| 6.0.0   | 1         | 0.02%   |
| 5.9.12  | 1         | 0.02%   |
| 5.9.0   | 1         | 0.02%   |
| 5.8.5   | 1         | 0.02%   |
| 5.7.17  | 1         | 0.02%   |
| 5.4.180 | 1         | 0.02%   |
| 5.4.1   | 1         | 0.02%   |
| 5.19.9  | 1         | 0.02%   |
| 5.19.6  | 1         | 0.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 1477      | 28.54%  |
| 5.4     | 956       | 18.47%  |
| 5.11    | 950       | 18.35%  |
| 5.13    | 769       | 14.86%  |
| 5.3     | 487       | 9.41%   |
| 4.15    | 189       | 3.65%   |
| 5.0     | 153       | 2.96%   |
| 4.18    | 76        | 1.47%   |
| 5.8     | 55        | 1.06%   |
| 5.14    | 10        | 0.19%   |
| 5.19    | 8         | 0.15%   |
| 5.7     | 6         | 0.12%   |
| 4.4     | 6         | 0.12%   |
| 5.17    | 5         | 0.1%    |
| 5.16    | 5         | 0.1%    |
| 6.0     | 4         | 0.08%   |
| 5.10    | 4         | 0.08%   |
| 6.3     | 3         | 0.06%   |
| 6.2     | 3         | 0.06%   |
| 5.18    | 3         | 0.06%   |
| 5.9     | 2         | 0.04%   |
| 5.6     | 2         | 0.04%   |
| 4.13    | 2         | 0.04%   |
| 6.1     | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 4572      | 92.12%  |
| i686   | 391       | 7.88%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 3652      | 72.76%  |
| XFCE       | 1042      | 20.76%  |
| Unknown    | 297       | 5.92%   |
| X-Cinnamon | 8         | 0.16%   |
| KDE5       | 4         | 0.08%   |
| KDE        | 4         | 0.08%   |
| Unity      | 3         | 0.06%   |
| Cinnamon   | 3         | 0.06%   |
| Budgie     | 3         | 0.06%   |
| MATE       | 1         | 0.02%   |
| LXDE       | 1         | 0.02%   |
| i3         | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 4740      | 94.84%  |
| Unknown | 182       | 3.64%   |
| Wayland | 74        | 1.48%   |
| Tty     | 2         | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 4057      | 80.42%  |
| GDM3    | 373       | 7.39%   |
| GDM     | 342       | 6.78%   |
| LightDM | 258       | 5.11%   |
| TDM     | 11        | 0.22%   |
| SDDM    | 3         | 0.06%   |
| LXDM    | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1822      | 36.46%  |
| de_DE   | 393       | 7.86%   |
| pt_BR   | 317       | 6.34%   |
| en_GB   | 303       | 6.06%   |
| Unknown | 230       | 4.6%    |
| it_IT   | 171       | 3.42%   |
| fr_FR   | 149       | 2.98%   |
| en_CA   | 143       | 2.86%   |
| es_ES   | 137       | 2.74%   |
| en_IN   | 133       | 2.66%   |
| pl_PL   | 110       | 2.2%    |
| en_AU   | 91        | 1.82%   |
| nl_NL   | 79        | 1.58%   |
| es_MX   | 66        | 1.32%   |
| ru_RU   | 65        | 1.3%    |
| pt_PT   | 56        | 1.12%   |
| es_AR   | 56        | 1.12%   |
| cs_CZ   | 48        | 0.96%   |
| en_ZA   | 47        | 0.94%   |
| hu_HU   | 34        | 0.68%   |
| tr_TR   | 30        | 0.6%    |
| sv_SE   | 30        | 0.6%    |
| C       | 29        | 0.58%   |
| es_CL   | 27        | 0.54%   |
| en_NZ   | 26        | 0.52%   |
| fr_CA   | 24        | 0.48%   |
| es_CO   | 22        | 0.44%   |
| de_AT   | 21        | 0.42%   |
| nl_BE   | 20        | 0.4%    |
| ja_JP   | 20        | 0.4%    |
| de_CH   | 18        | 0.36%   |
| el_GR   | 17        | 0.34%   |
| fr_BE   | 16        | 0.32%   |
| en_PH   | 15        | 0.3%    |
| da_DK   | 14        | 0.28%   |
| nb_NO   | 12        | 0.24%   |
| fi_FI   | 12        | 0.24%   |
| es_PE   | 12        | 0.24%   |
| ro_RO   | 10        | 0.2%    |
| es_VE   | 10        | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2679      | 53.35%  |
| EFI  | 2343      | 46.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 4661      | 93.48%  |
| Overlay  | 102       | 2.05%   |
| Zfs      | 60        | 1.2%    |
| Tmpfs    | 43        | 0.86%   |
| Btrfs    | 38        | 0.76%   |
| Ext2     | 35        | 0.7%    |
| Unknown  | 27        | 0.54%   |
| Xfs      | 9         | 0.18%   |
| Ext3     | 9         | 0.18%   |
| Reiserfs | 1         | 0.02%   |
| Jfs      | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 4412      | 88.03%  |
| GPT     | 443       | 8.84%   |
| MBR     | 157       | 3.13%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4705      | 94.27%  |
| Yes       | 286       | 5.73%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4105      | 82.1%   |
| Yes       | 895       | 17.9%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 863       | 17.4%   |
| ASUSTek Computer    | 696       | 14.03%  |
| Dell                | 651       | 13.13%  |
| Lenovo              | 576       | 11.61%  |
| Gigabyte Technology | 276       | 5.56%   |
| Acer                | 275       | 5.54%   |
| MSI                 | 203       | 4.09%   |
| Toshiba             | 157       | 3.17%   |
| Apple               | 149       | 3%      |
| ASRock              | 137       | 2.76%   |
| Intel               | 78        | 1.57%   |
| Samsung Electronics | 63        | 1.27%   |
| Unknown             | 60        | 1.21%   |
| Sony                | 50        | 1.01%   |
| Fujitsu             | 43        | 0.87%   |
| Pegatron            | 33        | 0.67%   |
| Packard Bell        | 33        | 0.67%   |
| Google              | 33        | 0.67%   |
| Positivo            | 30        | 0.6%    |
| Microsoft           | 25        | 0.5%    |
| Foxconn             | 25        | 0.5%    |
| Biostar             | 24        | 0.48%   |
| Medion              | 22        | 0.44%   |
| Fujitsu Siemens     | 21        | 0.42%   |
| HUAWEI              | 19        | 0.38%   |
| ECS                 | 19        | 0.38%   |
| Alienware           | 17        | 0.34%   |
| Gateway             | 13        | 0.26%   |
| AMI                 | 13        | 0.26%   |
| Notebook            | 12        | 0.24%   |
| eMachines           | 12        | 0.24%   |
| Chuwi               | 10        | 0.2%    |
| AZW                 | 10        | 0.2%    |
| Panasonic           | 9         | 0.18%   |
| Multilaser          | 8         | 0.16%   |
| Semp Toshiba        | 7         | 0.14%   |
| NEC Computers       | 7         | 0.14%   |
| IBM                 | 7         | 0.14%   |
| GPU Company         | 7         | 0.14%   |
| Shuttle             | 6         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 91        | 1.83%   |
| ASUS All Series            | 39        | 0.79%   |
| HP Notebook                | 29        | 0.58%   |
| HP Pavilion Notebook       | 17        | 0.34%   |
| HP Pavilion dv6            | 16        | 0.32%   |
| Dell OptiPlex 7010         | 13        | 0.26%   |
| HP Pavilion dv7            | 12        | 0.24%   |
| HP 15                      | 12        | 0.24%   |
| HP Pavilion 15             | 11        | 0.22%   |
| Dell OptiPlex 780          | 11        | 0.22%   |
| Toshiba Satellite C660     | 10        | 0.2%    |
| Gigabyte A320M-S2H         | 10        | 0.2%    |
| Dell OptiPlex 790          | 10        | 0.2%    |
| Dell Inspiron 1545         | 10        | 0.2%    |
| MSI MS-7817                | 9         | 0.18%   |
| Lenovo MIIX 320-10ICR 80XF | 9         | 0.18%   |
| HP Pavilion g6             | 9         | 0.18%   |
| Dell OptiPlex 380          | 9         | 0.18%   |
| Dell Latitude E6400        | 9         | 0.18%   |
| Dell Latitude D630         | 9         | 0.18%   |
| Apple iMac12,2             | 9         | 0.18%   |
| MSI MS-7C02                | 8         | 0.16%   |
| HP Laptop 15-bw0xx         | 8         | 0.16%   |
| Dell OptiPlex 755          | 8         | 0.16%   |
| Dell Latitude E6540        | 8         | 0.16%   |
| Dell Inspiron 15-3567      | 8         | 0.16%   |
| ASUS M5A97 R2.0            | 8         | 0.16%   |
| ASUS M5A78L-M/USB3         | 8         | 0.16%   |
| Apple MacBookPro8,1        | 8         | 0.16%   |
| HP Pavilion g7             | 7         | 0.14%   |
| HP Pavilion dv6700         | 7         | 0.14%   |
| HP EliteBook 840 G1        | 7         | 0.14%   |
| Gigabyte GA-78LMT-USB3 6.0 | 7         | 0.14%   |
| Gigabyte 970A-DS3P         | 7         | 0.14%   |
| Dell OptiPlex 990          | 7         | 0.14%   |
| Dell Latitude E6410        | 7         | 0.14%   |
| Dell Inspiron 3521         | 7         | 0.14%   |
| Dell Inspiron 1525         | 7         | 0.14%   |
| Apple iMac10,1             | 7         | 0.14%   |
| Toshiba Satellite A100     | 6         | 0.12%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| HP Pavilion           | 194       | 3.91%   |
| Dell Inspiron         | 190       | 3.83%   |
| Lenovo ThinkPad       | 186       | 3.75%   |
| Acer Aspire           | 181       | 3.65%   |
| Dell Latitude         | 165       | 3.33%   |
| Lenovo IdeaPad        | 141       | 2.84%   |
| Toshiba Satellite     | 132       | 2.66%   |
| Dell OptiPlex         | 118       | 2.38%   |
| HP Compaq             | 106       | 2.14%   |
| Unknown               | 91        | 1.83%   |
| HP EliteBook          | 88        | 1.77%   |
| HP ProBook            | 71        | 1.43%   |
| HP Laptop             | 57        | 1.15%   |
| ASUS ROG              | 54        | 1.09%   |
| Lenovo ThinkCentre    | 52        | 1.05%   |
| ASUS PRIME            | 48        | 0.97%   |
| Dell Vostro           | 43        | 0.87%   |
| Dell Precision        | 42        | 0.85%   |
| ASUS VivoBook         | 39        | 0.79%   |
| ASUS All              | 39        | 0.79%   |
| HP ENVY               | 36        | 0.73%   |
| ASUS TUF              | 36        | 0.73%   |
| Dell XPS              | 35        | 0.71%   |
| Lenovo Yoga           | 33        | 0.67%   |
| HP Notebook           | 29        | 0.58%   |
| Packard Bell EasyNote | 27        | 0.54%   |
| Microsoft Surface     | 25        | 0.5%    |
| HP Stream             | 23        | 0.46%   |
| HP EliteDesk          | 19        | 0.38%   |
| Fujitsu ESPRIMO       | 18        | 0.36%   |
| Dell Studio           | 16        | 0.32%   |
| ASUS ZenBook          | 16        | 0.32%   |
| HP Presario           | 15        | 0.3%    |
| Apple iMac12          | 15        | 0.3%    |
| Lenovo MIIX           | 14        | 0.28%   |
| HP ProDesk            | 14        | 0.28%   |
| HP 255                | 14        | 0.28%   |
| HP 15                 | 14        | 0.28%   |
| Gigabyte B450         | 14        | 0.28%   |
| HP OMEN               | 13        | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 437       | 8.81%   |
| 2012    | 408       | 8.23%   |
| 2013    | 389       | 7.84%   |
| 2018    | 357       | 7.2%    |
| 2010    | 351       | 7.08%   |
| 2014    | 313       | 6.31%   |
| 2008    | 306       | 6.17%   |
| 2017    | 291       | 5.87%   |
| 2019    | 288       | 5.81%   |
| 2021    | 279       | 5.63%   |
| 2009    | 269       | 5.42%   |
| 2020    | 266       | 5.36%   |
| 2016    | 243       | 4.9%    |
| 2015    | 237       | 4.78%   |
| 2007    | 228       | 4.6%    |
| 2006    | 103       | 2.08%   |
| 2022    | 83        | 1.67%   |
| 2005    | 66        | 1.33%   |
| 2023    | 17        | 0.34%   |
| 2004    | 11        | 0.22%   |
| Unknown | 9         | 0.18%   |
| 2003    | 8         | 0.16%   |
| 2002    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 2837      | 57.2%   |
| Desktop     | 1769      | 35.67%  |
| Convertible | 105       | 2.12%   |
| All in one  | 103       | 2.08%   |
| Tablet      | 71        | 1.43%   |
| Mini pc     | 64        | 1.29%   |
| Server      | 11        | 0.22%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4492      | 89.98%  |
| Enabled  | 500       | 10.02%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4922      | 99.23%  |
| Yes  | 38        | 0.77%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 1269      | 25.32%  |
| 4.01-8.0        | 1183      | 23.6%   |
| 8.01-16.0       | 766       | 15.28%  |
| 16.01-24.0      | 678       | 13.53%  |
| 1.01-2.0        | 462       | 9.22%   |
| 32.01-64.0      | 291       | 5.81%   |
| 2.01-3.0        | 157       | 3.13%   |
| 0.51-1.0        | 96        | 1.92%   |
| 64.01-256.0     | 62        | 1.24%   |
| 24.01-32.0      | 47        | 0.94%   |
| More than 256.0 | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 2258      | 42.01%  |
| 2.01-3.0   | 1489      | 27.7%   |
| 3.01-4.0   | 613       | 11.4%   |
| 4.01-8.0   | 481       | 8.95%   |
| 0.51-1.0   | 407       | 7.57%   |
| 8.01-16.0  | 71        | 1.32%   |
| 0.01-0.5   | 41        | 0.76%   |
| 16.01-24.0 | 9         | 0.17%   |
| 24.01-32.0 | 4         | 0.07%   |
| 32.01-64.0 | 2         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3350      | 66.1%   |
| 2       | 1176      | 23.2%   |
| 3       | 278       | 5.49%   |
| 4       | 122       | 2.41%   |
| 5       | 60        | 1.18%   |
| 6       | 31        | 0.61%   |
| 0       | 24        | 0.47%   |
| 7       | 13        | 0.26%   |
| 8       | 9         | 0.18%   |
| 51      | 1         | 0.02%   |
| 30      | 1         | 0.02%   |
| 11      | 1         | 0.02%   |
| 10      | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2529      | 50.72%  |
| Yes       | 2457      | 49.28%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4286      | 86.25%  |
| No        | 683       | 13.75%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3944      | 79.16%  |
| No        | 1038      | 20.84%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2639      | 52.7%   |
| No        | 2369      | 47.3%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 1139      | 22.88%  |
| Germany      | 451       | 9.06%   |
| Brazil       | 360       | 7.23%   |
| UK           | 301       | 6.05%   |
| Canada       | 192       | 3.86%   |
| Italy        | 191       | 3.84%   |
| Spain        | 149       | 2.99%   |
| France       | 148       | 2.97%   |
| India        | 142       | 2.85%   |
| Netherlands  | 138       | 2.77%   |
| Poland       | 113       | 2.27%   |
| Australia    | 100       | 2.01%   |
| Mexico       | 91        | 1.83%   |
| Argentina    | 71        | 1.43%   |
| Portugal     | 66        | 1.33%   |
| Russia       | 60        | 1.21%   |
| Czechia      | 57        | 1.15%   |
| South Africa | 55        | 1.1%    |
| Belgium      | 54        | 1.08%   |
| Sweden       | 53        | 1.06%   |
| Romania      | 48        | 0.96%   |
| Switzerland  | 45        | 0.9%    |
| Greece       | 45        | 0.9%    |
| Indonesia    | 42        | 0.84%   |
| Austria      | 41        | 0.82%   |
| Turkey       | 40        | 0.8%    |
| Hungary      | 39        | 0.78%   |
| Colombia     | 35        | 0.7%    |
| Norway       | 34        | 0.68%   |
| New Zealand  | 33        | 0.66%   |
| Chile        | 33        | 0.66%   |
| Denmark      | 31        | 0.62%   |
| Japan        | 30        | 0.6%    |
| Serbia       | 27        | 0.54%   |
| Egypt        | 26        | 0.52%   |
| Bulgaria     | 23        | 0.46%   |
| Philippines  | 21        | 0.42%   |
| Finland      | 21        | 0.42%   |
| Ukraine      | 19        | 0.38%   |
| Slovakia     | 17        | 0.34%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Berlin         | 42        | 0.81%   |
| Sao Paulo      | 40        | 0.77%   |
| Munich         | 32        | 0.62%   |
| Athens         | 32        | 0.62%   |
| Sydney         | 29        | 0.56%   |
| Milan          | 26        | 0.5%    |
| Madrid         | 26        | 0.5%    |
| Vienna         | 25        | 0.48%   |
| Rome           | 25        | 0.48%   |
| Rio de Janeiro | 24        | 0.46%   |
| Montreal       | 20        | 0.39%   |
| Perth          | 19        | 0.37%   |
| New York       | 19        | 0.37%   |
| Johannesburg   | 19        | 0.37%   |
| Toronto        | 18        | 0.35%   |
| Paris          | 18        | 0.35%   |
| Denver         | 18        | 0.35%   |
| Dallas         | 18        | 0.35%   |
| Auckland       | 18        | 0.35%   |
| London         | 17        | 0.33%   |
| Istanbul       | 17        | 0.33%   |
| Bengaluru      | 17        | 0.33%   |
| Belgrade       | 17        | 0.33%   |
| Warsaw         | 16        | 0.31%   |
| Hamburg        | 16        | 0.31%   |
| Cairo          | 16        | 0.31%   |
| Buenos Aires   | 16        | 0.31%   |
| Bucharest      | 16        | 0.31%   |
| Bogotá        | 16        | 0.31%   |
| Prague         | 15        | 0.29%   |
| Moscow         | 14        | 0.27%   |
| Mexico City    | 14        | 0.27%   |
| Jakarta        | 14        | 0.27%   |
| Cape Town      | 14        | 0.27%   |
| Zurich         | 13        | 0.25%   |
| Stockholm      | 13        | 0.25%   |
| Melbourne      | 13        | 0.25%   |
| Copenhagen     | 13        | 0.25%   |
| Calgary        | 13        | 0.25%   |
| Brisbane       | 13        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 1100      | 1518   | 16.37%  |
| WDC                       | 984       | 1309   | 14.64%  |
| Samsung Electronics       | 825       | 1180   | 12.27%  |
| Toshiba                   | 516       | 643    | 7.68%   |
| Unknown                   | 394       | 553    | 5.86%   |
| SanDisk                   | 354       | 426    | 5.27%   |
| Kingston                  | 348       | 459    | 5.18%   |
| Hitachi                   | 307       | 381    | 4.57%   |
| Crucial                   | 217       | 259    | 3.23%   |
| Intel                     | 130       | 167    | 1.93%   |
| HGST                      | 124       | 151    | 1.84%   |
| SK hynix                  | 95        | 114    | 1.41%   |
| A-DATA Technology         | 85        | 99     | 1.26%   |
| China                     | 76        | 87     | 1.13%   |
| Micron Technology         | 72        | 84     | 1.07%   |
| Apple                     | 64        | 70     | 0.95%   |
| Intenso                   | 48        | 53     | 0.71%   |
| Phison                    | 47        | 59     | 0.7%    |
| Maxtor                    | 47        | 65     | 0.7%    |
| PNY                       | 46        | 57     | 0.68%   |
| Fujitsu                   | 43        | 45     | 0.64%   |
| Silicon Motion            | 37        | 46     | 0.55%   |
| Patriot                   | 34        | 47     | 0.51%   |
| SPCC                      | 33        | 39     | 0.49%   |
| KIOXIA                    | 30        | 33     | 0.45%   |
| OCZ                       | 28        | 32     | 0.42%   |
| JMicron Technology        | 27        | 35     | 0.4%    |
| Micron/Crucial Technology | 24        | 28     | 0.36%   |
| GOODRAM                   | 24        | 25     | 0.36%   |
| LITEON                    | 23        | 28     | 0.34%   |
| Transcend                 | 22        | 43     | 0.33%   |
| Netac                     | 22        | 25     | 0.33%   |
| Unknown                   | 22        | 25     | 0.33%   |
| LITEONIT                  | 17        | 20     | 0.25%   |
| Team                      | 16        | 19     | 0.24%   |
| SABRENT                   | 16        | 17     | 0.24%   |
| Lexar                     | 15        | 15     | 0.22%   |
| Hewlett-Packard           | 15        | 19     | 0.22%   |
| Phison Electronics        | 14        | 16     | 0.21%   |
| KingSpec                  | 13        | 15     | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                              | 135       | 1.85%   |
| Unknown MMC Card  64GB                              | 106       | 1.45%   |
| Kingston SA400S37240G 240GB SSD                     | 85        | 1.17%   |
| Seagate ST500DM002-1BD142 500GB                     | 60        | 0.82%   |
| Seagate ST1000LM035-1RK172 1TB                      | 56        | 0.77%   |
| Toshiba MQ01ABF050 500GB                            | 50        | 0.69%   |
| Kingston SA400S37480G 480GB SSD                     | 50        | 0.69%   |
| Crucial CT240BX500SSD1 240GB                        | 48        | 0.66%   |
| Unknown MMC Card  128GB                             | 46        | 0.63%   |
| Kingston SA400S37120G 120GB SSD                     | 46        | 0.63%   |
| Toshiba MQ01ABD100 1TB                              | 45        | 0.62%   |
| Samsung SSD 860 EVO 500GB                           | 45        | 0.62%   |
| Seagate ST500LT012-1DG142 500GB                     | 43        | 0.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 40        | 0.55%   |
| Seagate ST1000DM010-2EP102 1TB                      | 40        | 0.55%   |
| Toshiba MQ04ABF100 1TB                              | 37        | 0.51%   |
| Unknown SD/MMC/MS PRO 250GB                         | 34        | 0.47%   |
| Seagate ST9500325AS 500GB                           | 34        | 0.47%   |
| Samsung SSD 850 EVO 500GB                           | 34        | 0.47%   |
| Samsung NVMe SSD Drive 256GB                        | 34        | 0.47%   |
| Samsung SSD 850 EVO 250GB                           | 33        | 0.45%   |
| Samsung NVMe SSD Drive 512GB                        | 33        | 0.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 33        | 0.45%   |
| Crucial CT500MX500SSD1 500GB                        | 32        | 0.44%   |
| Seagate ST3500418AS 500GB                           | 30        | 0.41%   |
| Samsung NVMe SSD Drive 500GB                        | 30        | 0.41%   |
| Kingston SV300S37A120G 120GB SSD                    | 30        | 0.41%   |
| Toshiba DT01ACA100 1TB                              | 29        | 0.4%    |
| Samsung NVMe SSD Drive 1TB                          | 29        | 0.4%    |
| Unknown MMC Card  16GB                              | 28        | 0.38%   |
| Seagate Expansion 1TB                               | 26        | 0.36%   |
| Samsung SSD 860 EVO 250GB                           | 25        | 0.34%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 24        | 0.33%   |
| Seagate ST1000DM003-1CH162 1TB                      | 24        | 0.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 23        | 0.32%   |
| Seagate ST1000DM003-1ER162 1TB                      | 22        | 0.3%    |
| SanDisk NVMe SSD Drive 256GB                        | 22        | 0.3%    |
| HGST HTS721010A9E630 1TB                            | 22        | 0.3%    |
| HGST HTS541010A9E680 1TB                            | 22        | 0.3%    |
| Unknown                                             | 22        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1087      | 1486   | 34.25%  |
| WDC                 | 881       | 1154   | 27.76%  |
| Toshiba             | 434       | 547    | 13.67%  |
| Hitachi             | 307       | 381    | 9.67%   |
| Samsung Electronics | 158       | 202    | 4.98%   |
| HGST                | 124       | 151    | 3.91%   |
| Maxtor              | 45        | 63     | 1.42%   |
| Fujitsu             | 43        | 45     | 1.35%   |
| Unknown             | 34        | 46     | 1.07%   |
| Apple               | 32        | 34     | 1.01%   |
| USB3.0              | 4         | 5      | 0.13%   |
| IBM/Hitachi         | 4         | 5      | 0.13%   |
| Super Talent        | 3         | 4      | 0.09%   |
| Hewlett-Packard     | 3         | 6      | 0.09%   |
| SSK                 | 2         | 2      | 0.06%   |
| SABRENT             | 2         | 2      | 0.06%   |
| Quantum             | 2         | 2      | 0.06%   |
| JMicron Technology  | 2         | 2      | 0.06%   |
| Intenso             | 2         | 2      | 0.06%   |
| Pioneer             | 1         | 1      | 0.03%   |
| KESU                | 1         | 1      | 0.03%   |
| ExcelStor           | 1         | 1      | 0.03%   |
| ASMT109x            | 1         | 2      | 0.03%   |
| ACASIS              | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 418       | 585    | 19.51%  |
| Kingston            | 300       | 388    | 14.01%  |
| SanDisk             | 216       | 258    | 10.08%  |
| Crucial             | 210       | 250    | 9.8%    |
| WDC                 | 97        | 123    | 4.53%   |
| A-DATA Technology   | 78        | 92     | 3.64%   |
| China               | 74        | 85     | 3.45%   |
| Intel               | 62        | 73     | 2.89%   |
| PNY                 | 46        | 57     | 2.15%   |
| Toshiba             | 45        | 52     | 2.1%    |
| Micron Technology   | 37        | 43     | 1.73%   |
| SK hynix            | 34        | 38     | 1.59%   |
| Intenso             | 34        | 38     | 1.59%   |
| Patriot             | 33        | 46     | 1.54%   |
| SPCC                | 31        | 37     | 1.45%   |
| Apple               | 27        | 29     | 1.26%   |
| OCZ                 | 26        | 30     | 1.21%   |
| LITEON              | 23        | 28     | 1.07%   |
| Transcend           | 22        | 43     | 1.03%   |
| Netac               | 22        | 24     | 1.03%   |
| GOODRAM             | 22        | 23     | 1.03%   |
| LITEONIT            | 17        | 20     | 0.79%   |
| Team                | 16        | 19     | 0.75%   |
| Lexar               | 14        | 14     | 0.65%   |
| KingSpec            | 12        | 14     | 0.56%   |
| Hewlett-Packard     | 11        | 12     | 0.51%   |
| Gigabyte Technology | 11        | 18     | 0.51%   |
| Apacer              | 11        | 13     | 0.51%   |
| Unknown             | 10        | 12     | 0.47%   |
| Leven               | 9         | 10     | 0.42%   |
| Corsair             | 8         | 14     | 0.37%   |
| Plextor             | 7         | 8      | 0.33%   |
| ASMT                | 7         | 7      | 0.33%   |
| Verbatim            | 6         | 6      | 0.28%   |
| OWC                 | 6         | 7      | 0.28%   |
| Mushkin             | 5         | 5      | 0.23%   |
| FORESEE             | 5         | 6      | 0.23%   |
| TCSUNBOW            | 4         | 4      | 0.19%   |
| Seagate             | 4         | 7      | 0.19%   |
| KIOXIA-EXCERIA      | 4         | 8      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2784      | 4145   | 45.39%  |
| SSD     | 1933      | 2689   | 31.51%  |
| NVMe    | 912       | 1233   | 14.87%  |
| MMC     | 369       | 507    | 6.02%   |
| Unknown | 136       | 171    | 2.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 4121      | 6686   | 73.21%  |
| NVMe | 892       | 1195   | 15.85%  |
| MMC  | 369       | 507    | 6.56%   |
| SAS  | 247       | 357    | 4.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3207      | 4486   | 66.4%   |
| 0.51-1.0   | 1201      | 1663   | 24.87%  |
| 1.01-2.0   | 256       | 366    | 5.3%    |
| 4.01-10.0  | 62        | 90     | 1.28%   |
| 3.01-4.0   | 61        | 140    | 1.26%   |
| 2.01-3.0   | 38        | 69     | 0.79%   |
| 10.01-20.0 | 5         | 20     | 0.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1686      | 32.81%  |
| 251-500        | 1247      | 24.27%  |
| 501-1000       | 684       | 13.31%  |
| 51-100         | 515       | 10.02%  |
| 21-50          | 303       | 5.9%    |
| 1001-2000      | 267       | 5.2%    |
| 1-20           | 154       | 3%      |
| More than 3000 | 148       | 2.88%   |
| 2001-3000      | 88        | 1.71%   |
| Unknown        | 46        | 0.9%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2488      | 46.65%  |
| 21-50          | 1227      | 23.01%  |
| 51-100         | 572       | 10.73%  |
| 101-250        | 458       | 8.59%   |
| 251-500        | 247       | 4.63%   |
| 501-1000       | 138       | 2.59%   |
| 1001-2000      | 72        | 1.35%   |
| More than 3000 | 63        | 1.18%   |
| Unknown        | 46        | 0.86%   |
| 2001-3000      | 22        | 0.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                   | 3         | 3      | 2.8%    |
| Seagate ST9500325AS 500GB                | 3         | 3      | 2.8%    |
| HGST HTS541010A9E680 1TB                 | 3         | 3      | 2.8%    |
| Toshiba MQ02ABD100H 1TB                  | 2         | 2      | 1.87%   |
| SK hynix BC711 HFM512GD3JX013N 512GB     | 2         | 2      | 1.87%   |
| Seagate ST9500420AS 500GB                | 2         | 2      | 1.87%   |
| Seagate ST500LT012-9WS142 500GB          | 2         | 2      | 1.87%   |
| Kingston SUV400S37240G 240GB SSD         | 2         | 2      | 1.87%   |
| HGST HTS545050A7E380 500GB               | 2         | 2      | 1.87%   |
| WDC WD6400BEVT-22A0RT0 640GB             | 1         | 1      | 0.93%   |
| WDC WD5000LPVX-75V0TT0 500GB             | 1         | 1      | 0.93%   |
| WDC WD5000LPCX-60VHAT0 500GB             | 1         | 1      | 0.93%   |
| WDC WD5000BEVT-24A0RT0 500GB             | 1         | 1      | 0.93%   |
| WDC WD5000AAKS-00V1A0 500GB              | 1         | 1      | 0.93%   |
| WDC WD3200BPVT-55ZEST0 320GB             | 1         | 1      | 0.93%   |
| WDC WD3200AAKS-22B3A0 320GB              | 1         | 1      | 0.93%   |
| WDC WD3200AAJS-00L7A0 320GB              | 1         | 1      | 0.93%   |
| WDC WD30EFRX-68EUZN0 3TB                 | 1         | 1      | 0.93%   |
| WDC WD1200BEVS-60UST0 120GB              | 1         | 1      | 0.93%   |
| WDC WD10SPZX-75Z10T2 1TB                 | 1         | 1      | 0.93%   |
| WDC WD10JPVX-22JC3T0 1TB                 | 1         | 1      | 0.93%   |
| WDC WD10JPVT-55A1YT0 1TB                 | 1         | 1      | 0.93%   |
| WDC WD10EZEX-21M2NA0 1TB                 | 1         | 2      | 0.93%   |
| WDC WD10EURX-63FH1Y0 1TB                 | 1         | 1      | 0.93%   |
| WDC WD Green 2.5 1000GB SSD              | 1         | 1      | 0.93%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1         | 1      | 0.93%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD     | 1         | 1      | 0.93%   |
| Toshiba MQ01ABF050 500GB                 | 1         | 1      | 0.93%   |
| Toshiba MQ01ABD075 752GB                 | 1         | 1      | 0.93%   |
| Toshiba MK8046GSX 80GB                   | 1         | 1      | 0.93%   |
| Toshiba MK5061GSY 500GB                  | 1         | 1      | 0.93%   |
| Toshiba MK3265GSX 320GB                  | 1         | 1      | 0.93%   |
| Toshiba MK2046GSX 200GB                  | 1         | 1      | 0.93%   |
| Toshiba MG03ACA200 2TB                   | 1         | 1      | 0.93%   |
| Toshiba DT01ACA100 1TB                   | 1         | 1      | 0.93%   |
| Teclast 128GB NS550-2242 SSD             | 1         | 1      | 0.93%   |
| Silicon Motion Inland NVMe SSD 256GB     | 1         | 1      | 0.93%   |
| Seagate ST9320325AS 320GB                | 1         | 1      | 0.93%   |
| Seagate ST9320310AS 320GB                | 1         | 1      | 0.93%   |
| Seagate ST9250315AS 250GB                | 1         | 1      | 0.93%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 37        | 38     | 34.91%  |
| WDC                 | 16        | 17     | 15.09%  |
| Toshiba             | 15        | 15     | 14.15%  |
| HGST                | 8         | 8      | 7.55%   |
| Kingston            | 6         | 6      | 5.66%   |
| Hitachi             | 5         | 5      | 4.72%   |
| Samsung Electronics | 4         | 4      | 3.77%   |
| SK hynix            | 2         | 2      | 1.89%   |
| A-DATA Technology   | 2         | 2      | 1.89%   |
| Teclast             | 1         | 1      | 0.94%   |
| Silicon Motion      | 1         | 1      | 0.94%   |
| OCZ                 | 1         | 1      | 0.94%   |
| Micron Technology   | 1         | 1      | 0.94%   |
| Maxtor              | 1         | 1      | 0.94%   |
| LITEONIT            | 1         | 1      | 0.94%   |
| LITEON              | 1         | 1      | 0.94%   |
| Intel               | 1         | 1      | 0.94%   |
| Hewlett-Packard     | 1         | 1      | 0.94%   |
| Drevo               | 1         | 1      | 0.94%   |
| Unknown             | 1         | 1      | 0.94%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 37        | 38     | 45.68%  |
| WDC                 | 15        | 16     | 18.52%  |
| Toshiba             | 13        | 13     | 16.05%  |
| HGST                | 8         | 8      | 9.88%   |
| Hitachi             | 5         | 5      | 6.17%   |
| Samsung Electronics | 2         | 2      | 2.47%   |
| Maxtor              | 1         | 1      | 1.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 77        | 83     | 75.49%  |
| SSD  | 21        | 21     | 20.59%  |
| NVMe | 4         | 4      | 3.92%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST2000LX001-1RG174 2TB | 1         | 1      | 50%     |
| SanDisk SSD i100 24GB          | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| SanDisk | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 4560      | 7996   | 90.14%  |
| Works    | 396       | 639    | 7.83%   |
| Malfunc  | 101       | 108    | 2%      |
| Failed   | 2         | 2      | 0.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3416      | 60.36%  |
| AMD                              | 909       | 16.06%  |
| Samsung Electronics              | 318       | 5.62%   |
| Nvidia                           | 147       | 2.6%    |
| SanDisk                          | 143       | 2.53%   |
| ASMedia Technology               | 66        | 1.17%   |
| Phison Electronics               | 64        | 1.13%   |
| JMicron Technology               | 63        | 1.11%   |
| Kingston Technology Company      | 62        | 1.1%    |
| SK hynix                         | 57        | 1.01%   |
| Marvell Technology Group         | 48        | 0.85%   |
| Silicon Motion                   | 41        | 0.72%   |
| VIA Technologies                 | 38        | 0.67%   |
| Toshiba America Info Systems     | 38        | 0.67%   |
| Silicon Integrated Systems [SiS] | 36        | 0.64%   |
| Micron Technology                | 36        | 0.64%   |
| KIOXIA                           | 32        | 0.57%   |
| Micron/Crucial Technology        | 31        | 0.55%   |
| ADATA Technology                 | 20        | 0.35%   |
| Silicon Image                    | 14        | 0.25%   |
| Realtek Semiconductor            | 13        | 0.23%   |
| Union Memory (Shenzhen)          | 7         | 0.12%   |
| Seagate Technology               | 7         | 0.12%   |
| Broadcom / LSI                   | 7         | 0.12%   |
| MAXIO Technology (Hangzhou)      | 6         | 0.11%   |
| Lite-On Technology               | 6         | 0.11%   |
| LSI Logic / Symbios Logic        | 5         | 0.09%   |
| Solid State Storage Technology   | 4         | 0.07%   |
| Apple                            | 4         | 0.07%   |
| OCZ Technology Group             | 3         | 0.05%   |
| Yangtze Memory Technologies      | 2         | 0.04%   |
| Integrated Technology Express    | 2         | 0.04%   |
| INNOGRIT                         | 2         | 0.04%   |
| Adaptec                          | 2         | 0.04%   |
| TenaFe                           | 1         | 0.02%   |
| Promise Technology               | 1         | 0.02%   |
| Netac Technology                 | 1         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.02%   |
| Lenovo                           | 1         | 0.02%   |
| HighPoint Technologies           | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 564       | 8.28%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 246       | 3.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 226       | 3.32%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 221       | 3.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 199       | 2.92%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 177       | 2.6%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 174       | 2.56%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 160       | 2.35%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 155       | 2.28%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 136       | 2%      |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 127       | 1.87%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 126       | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 125       | 1.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 122       | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 121       | 1.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 103       | 1.51%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 98        | 1.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 95        | 1.4%    |
| AMD 400 Series Chipset SATA Controller                                                  | 92        | 1.35%   |
| Intel SATA Controller [RAID mode]                                                       | 83        | 1.22%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 81        | 1.19%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 74        | 1.09%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 70        | 1.03%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 70        | 1.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 69        | 1.01%   |
| Samsung NVMe SSD Controller 980                                                         | 65        | 0.95%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 63        | 0.93%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 61        | 0.9%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 60        | 0.88%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 55        | 0.81%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 53        | 0.78%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 47        | 0.69%   |
| Nvidia MCP61 SATA Controller                                                            | 46        | 0.68%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 46        | 0.68%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 45        | 0.66%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 44        | 0.65%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 44        | 0.65%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 42        | 0.62%   |
| AMD 500 Series Chipset SATA Controller                                                  | 42        | 0.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 41        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3520      | 59.36%  |
| IDE  | 1109      | 18.7%   |
| NVMe | 894       | 15.08%  |
| RAID | 392       | 6.61%   |
| SAS  | 9         | 0.15%   |
| SCSI | 6         | 0.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 3873      | 78.08%  |
| AMD          | 1086      | 21.9%   |
| CentaurHauls | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 71        | 1.43%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 41        | 0.83%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 38        | 0.76%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 37        | 0.74%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 36        | 0.72%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 35        | 0.7%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 33        | 0.66%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 33        | 0.66%   |
| AMD Ryzen 5 3600 6-Core Processor             | 31        | 0.62%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 28        | 0.56%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 28        | 0.56%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 27        | 0.54%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 27        | 0.54%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 27        | 0.54%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 26        | 0.52%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 25        | 0.5%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 25        | 0.5%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 23        | 0.46%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 23        | 0.46%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 23        | 0.46%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 22        | 0.44%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 22        | 0.44%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 21        | 0.42%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 21        | 0.42%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 21        | 0.42%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 20        | 0.4%    |
| Intel Core i3-2310M CPU @ 2.10GHz             | 20        | 0.4%    |
| Intel Atom CPU N450 @ 1.66GHz                 | 20        | 0.4%    |
| Intel Pentium 4 CPU 3.00GHz                   | 19        | 0.38%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 19        | 0.38%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 19        | 0.38%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 19        | 0.38%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 19        | 0.38%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 19        | 0.38%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 19        | 0.38%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 18        | 0.36%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 18        | 0.36%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 18        | 0.36%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 18        | 0.36%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 18        | 0.36%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1005      | 20.23%  |
| Intel Core i7           | 618       | 12.44%  |
| Intel Core i3           | 449       | 9.04%   |
| Intel Core 2 Duo        | 342       | 6.89%   |
| Intel Celeron           | 334       | 6.72%   |
| Intel Atom              | 217       | 4.37%   |
| AMD Ryzen 5             | 193       | 3.89%   |
| Other                   | 172       | 3.46%   |
| Intel Pentium           | 149       | 3%      |
| AMD Ryzen 7             | 125       | 2.52%   |
| Intel Xeon              | 96        | 1.93%   |
| Intel Pentium Dual-Core | 94        | 1.89%   |
| AMD FX                  | 75        | 1.51%   |
| Intel Pentium Dual      | 74        | 1.49%   |
| AMD A6                  | 66        | 1.33%   |
| Intel Core 2 Quad       | 63        | 1.27%   |
| AMD A4                  | 57        | 1.15%   |
| AMD Ryzen 3             | 51        | 1.03%   |
| Intel Core 2            | 47        | 0.95%   |
| Intel Genuine           | 46        | 0.93%   |
| AMD Ryzen 9             | 46        | 0.93%   |
| AMD A8                  | 46        | 0.93%   |
| Intel Pentium 4         | 43        | 0.87%   |
| AMD A10                 | 41        | 0.83%   |
| AMD Athlon 64 X2        | 40        | 0.81%   |
| AMD Athlon II X2        | 35        | 0.7%    |
| Intel Pentium M         | 26        | 0.52%   |
| Intel Celeron M         | 25        | 0.5%    |
| AMD E1                  | 25        | 0.5%    |
| AMD E                   | 25        | 0.5%    |
| AMD Phenom II X4        | 23        | 0.46%   |
| AMD Athlon              | 22        | 0.44%   |
| AMD Sempron             | 20        | 0.4%    |
| AMD Turion 64 X2 Mobile | 17        | 0.34%   |
| Intel Core i9           | 16        | 0.32%   |
| Intel Pentium Silver    | 14        | 0.28%   |
| Intel Pentium Gold      | 12        | 0.24%   |
| AMD Athlon II X4        | 12        | 0.24%   |
| AMD Phenom II X6        | 11        | 0.22%   |
| AMD E2                  | 11        | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 2548      | 51.28%  |
| 4      | 1545      | 31.09%  |
| 1      | 286       | 5.76%   |
| 6      | 285       | 5.74%   |
| 8      | 194       | 3.9%    |
| 3      | 35        | 0.7%    |
| 12     | 29        | 0.58%   |
| 10     | 19        | 0.38%   |
| 16     | 18        | 0.36%   |
| 14     | 5         | 0.1%    |
| 20     | 2         | 0.04%   |
| 40     | 1         | 0.02%   |
| 28     | 1         | 0.02%   |
| 24     | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 4940      | 99.6%   |
| 2      | 20        | 0.4%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 2666      | 53.74%  |
| 1      | 2295      | 46.26%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4810      | 96.96%  |
| 32-bit         | 148       | 2.98%   |
| Unknown        | 3         | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 450       | 8.92%   |
| 0x206a7    | 409       | 8.11%   |
| 0x306a9    | 326       | 6.46%   |
| 0x1067a    | 311       | 6.16%   |
| 0x306c3    | 261       | 5.17%   |
| 0x6fd      | 139       | 2.75%   |
| 0x40651    | 139       | 2.75%   |
| 0x20655    | 125       | 2.48%   |
| 0x406e3    | 108       | 2.14%   |
| 0x806e9    | 107       | 2.12%   |
| 0x406c4    | 101       | 2%      |
| 0x306d4    | 98        | 1.94%   |
| 0x30678    | 96        | 1.9%    |
| 0x806c1    | 90        | 1.78%   |
| 0x506e3    | 83        | 1.64%   |
| 0x806ea    | 81        | 1.61%   |
| 0x906ea    | 73        | 1.45%   |
| 0x906e9    | 68        | 1.35%   |
| 0x10676    | 68        | 1.35%   |
| 0x806ec    | 67        | 1.33%   |
| 0x6fb      | 58        | 1.15%   |
| 0x010000c8 | 57        | 1.13%   |
| 0x06000852 | 54        | 1.07%   |
| 0x506c9    | 52        | 1.03%   |
| 0x06001119 | 52        | 1.03%   |
| 0x20652    | 51        | 1.01%   |
| 0x08701021 | 51        | 1.01%   |
| 0x406c3    | 49        | 0.97%   |
| 0x08108109 | 46        | 0.91%   |
| 0x706a8    | 45        | 0.89%   |
| 0x6f6      | 39        | 0.77%   |
| 0x06006705 | 39        | 0.77%   |
| 0x106ca    | 38        | 0.75%   |
| 0x706e5    | 36        | 0.71%   |
| 0x0700010f | 33        | 0.65%   |
| 0x6e8      | 31        | 0.61%   |
| 0x6d8      | 31        | 0.61%   |
| 0x05000119 | 31        | 0.61%   |
| 0x07030105 | 30        | 0.59%   |
| 0x0a50000c | 28        | 0.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 485       | 9.77%   |
| Haswell          | 439       | 8.85%   |
| SandyBridge      | 434       | 8.74%   |
| Penryn           | 401       | 8.08%   |
| IvyBridge        | 350       | 7.05%   |
| Core             | 298       | 6%      |
| Silvermont       | 284       | 5.72%   |
| Skylake          | 203       | 4.09%   |
| Westmere         | 198       | 3.99%   |
| K10              | 125       | 2.52%   |
| Zen 2            | 122       | 2.46%   |
| Zen+             | 114       | 2.3%    |
| Piledriver       | 114       | 2.3%    |
| K8 Hammer        | 105       | 2.12%   |
| Broadwell        | 105       | 2.12%   |
| TigerLake        | 101       | 2.04%   |
| Zen 3            | 94        | 1.89%   |
| P6               | 86        | 1.73%   |
| Excavator        | 78        | 1.57%   |
| Bonnell          | 78        | 1.57%   |
| Goldmont plus    | 74        | 1.49%   |
| Zen              | 70        | 1.41%   |
| CometLake        | 69        | 1.39%   |
| NetBurst         | 61        | 1.23%   |
| Icelake          | 59        | 1.19%   |
| Unknown          | 59        | 1.19%   |
| Goldmont         | 55        | 1.11%   |
| Puma             | 51        | 1.03%   |
| Bobcat           | 48        | 0.97%   |
| Nehalem          | 47        | 0.95%   |
| Jaguar           | 40        | 0.81%   |
| K10 Llano        | 29        | 0.58%   |
| Steamroller      | 19        | 0.38%   |
| Alderlake Hybrid | 19        | 0.38%   |
| Bulldozer        | 18        | 0.36%   |
| K8 & K10 hybrid  | 16        | 0.32%   |
| Tremont          | 12        | 0.24%   |
| K6               | 3         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2943      | 52.61%  |
| Nvidia                           | 1307      | 23.36%  |
| AMD                              | 1285      | 22.97%  |
| Silicon Integrated Systems [SiS] | 29        | 0.52%   |
| VIA Technologies                 | 19        | 0.34%   |
| Matrox Electronics Systems       | 6         | 0.11%   |
| ASPEED Technology                | 3         | 0.05%   |
| Trident Microsystems             | 1         | 0.02%   |
| Silicon Motion                   | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 331       | 5.66%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 219       | 3.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 162       | 2.77%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 142       | 2.43%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 136       | 2.33%   |
| Intel Core Processor Integrated Graphics Controller                                      | 130       | 2.22%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 120       | 2.05%   |
| Intel HD Graphics 620                                                                    | 98        | 1.68%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 95        | 1.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 94        | 1.61%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 80        | 1.37%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 79        | 1.35%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 79        | 1.35%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 77        | 1.32%   |
| Intel UHD Graphics 620                                                                   | 76        | 1.3%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 76        | 1.3%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 74        | 1.27%   |
| Intel HD Graphics 5500                                                                   | 68        | 1.16%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 65        | 1.11%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 64        | 1.09%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 61        | 1.04%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 54        | 0.92%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 53        | 0.91%   |
| Intel HD Graphics 630                                                                    | 52        | 0.89%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 51        | 0.87%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 50        | 0.85%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 49        | 0.84%   |
| Intel HD Graphics 530                                                                    | 49        | 0.84%   |
| Intel HD Graphics 500                                                                    | 46        | 0.79%   |
| AMD Renoir                                                                               | 46        | 0.79%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 42        | 0.72%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 39        | 0.67%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 36        | 0.62%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 34        | 0.58%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 34        | 0.58%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 32        | 0.55%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 32        | 0.55%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 32        | 0.55%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 32        | 0.55%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 30        | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 2380      | 47.78%  |
| 1 x AMD                  | 1033      | 20.74%  |
| 1 x Nvidia               | 868       | 17.43%  |
| Intel + Nvidia           | 373       | 7.49%   |
| Intel + AMD              | 129       | 2.59%   |
| 2 x AMD                  | 75        | 1.51%   |
| AMD + Nvidia             | 45        | 0.9%    |
| 1 x SiS                  | 29        | 0.58%   |
| 1 x VIA                  | 19        | 0.38%   |
| 2 x Nvidia               | 9         | 0.18%   |
| Other                    | 8         | 0.16%   |
| 1 x Matrox               | 5         | 0.1%    |
| 1 x ASPEED               | 2         | 0.04%   |
| 2 x Intel                | 1         | 0.02%   |
| 2 x AMD + 1 x Nvidia     | 1         | 0.02%   |
| 1 x Trident Microsystems | 1         | 0.02%   |
| Nvidia + Silicon Motion  | 1         | 0.02%   |
| Nvidia + ASPEED          | 1         | 0.02%   |
| AMD + Matrox             | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4063      | 81.26%  |
| Proprietary | 703       | 14.06%  |
| Unknown     | 234       | 4.68%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2885      | 57.09%  |
| 0.01-0.5   | 775       | 15.34%  |
| 1.01-2.0   | 500       | 9.9%    |
| 0.51-1.0   | 427       | 8.45%   |
| 3.01-4.0   | 211       | 4.18%   |
| 7.01-8.0   | 127       | 2.51%   |
| 5.01-6.0   | 59        | 1.17%   |
| 8.01-16.0  | 37        | 0.73%   |
| 2.01-3.0   | 27        | 0.53%   |
| 16.01-24.0 | 4         | 0.08%   |
| 4.01-5.0   | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 679       | 13.9%   |
| AU Optronics            | 588       | 12.03%  |
| LG Display              | 434       | 8.88%   |
| Chimei Innolux          | 381       | 7.8%    |
| BOE                     | 361       | 7.39%   |
| Dell                    | 231       | 4.73%   |
| Goldstar                | 214       | 4.38%   |
| Hewlett-Packard         | 179       | 3.66%   |
| Acer                    | 144       | 2.95%   |
| Apple                   | 129       | 2.64%   |
| Chi Mei Optoelectronics | 114       | 2.33%   |
| AOC                     | 105       | 2.15%   |
| Philips                 | 95        | 1.94%   |
| Ancor Communications    | 82        | 1.68%   |
| BenQ                    | 78        | 1.6%    |
| LG Philips              | 73        | 1.49%   |
| Lenovo                  | 73        | 1.49%   |
| Sharp                   | 55        | 1.13%   |
| InfoVision              | 49        | 1%      |
| LG Electronics          | 43        | 0.88%   |
| ViewSonic               | 39        | 0.8%    |
| Unknown                 | 37        | 0.76%   |
| Sony                    | 37        | 0.76%   |
| PANDA                   | 31        | 0.63%   |
| Vizio                   | 28        | 0.57%   |
| Toshiba                 | 28        | 0.57%   |
| HannStar                | 27        | 0.55%   |
| Iiyama                  | 24        | 0.49%   |
| Unknown                 | 23        | 0.47%   |
| CPT                     | 21        | 0.43%   |
| ASUSTek Computer        | 21        | 0.43%   |
| Eizo                    | 19        | 0.39%   |
| Fujitsu Siemens         | 18        | 0.37%   |
| Panasonic               | 16        | 0.33%   |
| Sceptre Tech            | 15        | 0.31%   |
| NEC Computers           | 15        | 0.31%   |
| MSI                     | 13        | 0.27%   |
| Quanta Display          | 11        | 0.23%   |
| Gateway                 | 11        | 0.23%   |
| LGD                     | 10        | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch     | 34        | 0.68%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 24        | 0.48%   |
| Unknown                                                                  | 23        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 21        | 0.42%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 18        | 0.36%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 18        | 0.36%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 18        | 0.36%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 18        | 0.36%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 17        | 0.34%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 16        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 15        | 0.3%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 15        | 0.3%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 14        | 0.28%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 14        | 0.28%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 13        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 13        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 13        | 0.26%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 13        | 0.26%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 13        | 0.26%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 12        | 0.24%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                  | 11        | 0.22%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 11        | 0.22%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 11        | 0.22%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 11        | 0.22%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 11        | 0.22%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 11        | 0.22%   |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch             | 10        | 0.2%    |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 10        | 0.2%    |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 9         | 0.18%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 409x230mm 18.5-inch    | 9         | 0.18%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 9         | 0.18%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 9         | 0.18%   |
| InfoVision LCD Monitor IVO03F4 1920x1200 263x164mm 12.2-inch             | 9         | 0.18%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 9         | 0.18%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 9         | 0.18%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 9         | 0.18%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 9         | 0.18%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 9         | 0.18%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 9         | 0.18%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 9         | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1592      | 33.23%  |
| 1366x768 (WXGA)    | 1308      | 27.3%   |
| 1600x900 (HD+)     | 277       | 5.78%   |
| 1280x800 (WXGA)    | 226       | 4.72%   |
| 3840x2160 (4K)     | 202       | 4.22%   |
| 1440x900 (WXGA+)   | 152       | 3.17%   |
| 1280x1024 (SXGA)   | 152       | 3.17%   |
| 1680x1050 (WSXGA+) | 142       | 2.96%   |
| 2560x1440 (QHD)    | 114       | 2.38%   |
| Unknown            | 78        | 1.63%   |
| 1920x1200 (WUXGA)  | 77        | 1.61%   |
| 1360x768           | 66        | 1.38%   |
| 1024x600           | 47        | 0.98%   |
| 3440x1440          | 35        | 0.73%   |
| 3840x1080          | 32        | 0.67%   |
| 1024x768 (XGA)     | 27        | 0.56%   |
| 2560x1600          | 26        | 0.54%   |
| 2560x1080          | 26        | 0.54%   |
| 1920x540           | 23        | 0.48%   |
| 2736x1824          | 16        | 0.33%   |
| 2160x1440          | 11        | 0.23%   |
| 3200x1800 (QHD+)   | 10        | 0.21%   |
| 2880x1800          | 10        | 0.21%   |
| 2256x1504          | 10        | 0.21%   |
| 1600x1200          | 9         | 0.19%   |
| 1280x768           | 9         | 0.19%   |
| 5760x1080          | 8         | 0.17%   |
| 3840x2400          | 6         | 0.13%   |
| 1280x720 (HD)      | 6         | 0.13%   |
| 3600x1080          | 5         | 0.1%    |
| 5760x2160          | 4         | 0.08%   |
| 4480x1440          | 4         | 0.08%   |
| 3840x1600          | 4         | 0.08%   |
| 1920x1280          | 4         | 0.08%   |
| 1680x945           | 4         | 0.08%   |
| 1400x1050          | 4         | 0.08%   |
| 2880x1920          | 3         | 0.06%   |
| 2048x1152          | 3         | 0.06%   |
| 1152x864           | 3         | 0.06%   |
| 1024x576           | 3         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1329      | 27.41%  |
| 13      | 423       | 8.72%   |
| Unknown | 401       | 8.27%   |
| 14      | 354       | 7.3%    |
| 17      | 315       | 6.5%    |
| 27      | 222       | 4.58%   |
| 21      | 211       | 4.35%   |
| 24      | 210       | 4.33%   |
| 23      | 204       | 4.21%   |
| 19      | 143       | 2.95%   |
| 18      | 125       | 2.58%   |
| 11      | 123       | 2.54%   |
| 20      | 110       | 2.27%   |
| 12      | 95        | 1.96%   |
| 31      | 88        | 1.81%   |
| 22      | 88        | 1.81%   |
| 10      | 60        | 1.24%   |
| 34      | 49        | 1.01%   |
| 40      | 31        | 0.64%   |
| 84      | 26        | 0.54%   |
| 72      | 26        | 0.54%   |
| 54      | 23        | 0.47%   |
| 16      | 21        | 0.43%   |
| 26      | 20        | 0.41%   |
| 32      | 18        | 0.37%   |
| 52      | 10        | 0.21%   |
| 25      | 10        | 0.21%   |
| 65      | 9         | 0.19%   |
| 36      | 9         | 0.19%   |
| 49      | 8         | 0.16%   |
| 42      | 7         | 0.14%   |
| 29      | 6         | 0.12%   |
| 28      | 6         | 0.12%   |
| 74      | 5         | 0.1%    |
| 47      | 5         | 0.1%    |
| 46      | 5         | 0.1%    |
| 39      | 5         | 0.1%    |
| 37      | 5         | 0.1%    |
| 33      | 5         | 0.1%    |
| 48      | 4         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 1935      | 40.39%  |
| 501-600     | 608       | 12.69%  |
| 401-500     | 598       | 12.48%  |
| 201-300     | 474       | 9.89%   |
| Unknown     | 401       | 8.37%   |
| 351-400     | 374       | 7.81%   |
| 601-700     | 119       | 2.48%   |
| 701-800     | 81        | 1.69%   |
| 1001-1500   | 78        | 1.63%   |
| 1501-2000   | 60        | 1.25%   |
| 801-900     | 45        | 0.94%   |
| 901-1000    | 14        | 0.29%   |
| 101-200     | 4         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3238      | 71.54%  |
| 16/10   | 616       | 13.61%  |
| Unknown | 356       | 7.87%   |
| 5/4     | 135       | 2.98%   |
| 21/9    | 56        | 1.24%   |
| 3/2     | 54        | 1.19%   |
| 4/3     | 50        | 1.1%    |
| 32/9    | 13        | 0.29%   |
| 6/5     | 5         | 0.11%   |
| 3.73    | 2         | 0.04%   |
| 0.62    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1322      | 27.45%  |
| 81-90          | 630       | 13.08%  |
| 201-250        | 561       | 11.65%  |
| Unknown        | 401       | 8.33%   |
| 151-200        | 342       | 7.1%    |
| 301-350        | 229       | 4.75%   |
| 121-130        | 186       | 3.86%   |
| 351-500        | 172       | 3.57%   |
| 141-150        | 171       | 3.55%   |
| 71-80          | 149       | 3.09%   |
| 51-60          | 125       | 2.6%    |
| More than 1000 | 122       | 2.53%   |
| 251-300        | 86        | 1.79%   |
| 61-70          | 83        | 1.72%   |
| 501-1000       | 80        | 1.66%   |
| 131-140        | 61        | 1.27%   |
| 41-50          | 58        | 1.2%    |
| 111-120        | 21        | 0.44%   |
| 91-100         | 13        | 0.27%   |
| 1-40           | 4         | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 1546      | 32.87%  |
| 51-100        | 1482      | 31.51%  |
| 121-160       | 908       | 19.3%   |
| Unknown       | 401       | 8.52%   |
| 161-240       | 183       | 3.89%   |
| 1-50          | 125       | 2.66%   |
| More than 240 | 59        | 1.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 4228      | 83.89%  |
| 2     | 526       | 10.44%  |
| 0     | 237       | 4.7%    |
| 3     | 45        | 0.89%   |
| 4     | 3         | 0.06%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2622      | 33.93%  |
| Intel                             | 1970      | 25.49%  |
| Qualcomm Atheros                  | 1017      | 13.16%  |
| Broadcom                          | 629       | 8.14%   |
| Broadcom Limited                  | 196       | 2.54%   |
| Marvell Technology Group          | 140       | 1.81%   |
| Ralink Technology                 | 130       | 1.68%   |
| Nvidia                            | 125       | 1.62%   |
| Ralink                            | 101       | 1.31%   |
| TP-Link                           | 91        | 1.18%   |
| MediaTek                          | 60        | 0.78%   |
| Samsung Electronics               | 49        | 0.63%   |
| ASIX Electronics                  | 34        | 0.44%   |
| Silicon Integrated Systems [SiS]  | 33        | 0.43%   |
| Xiaomi                            | 31        | 0.4%    |
| VIA Technologies                  | 31        | 0.4%    |
| NetGear                           | 31        | 0.4%    |
| D-Link                            | 28        | 0.36%   |
| JMicron Technology                | 26        | 0.34%   |
| Qualcomm Atheros Communications   | 24        | 0.31%   |
| Dell                              | 23        | 0.3%    |
| D-Link System                     | 23        | 0.3%    |
| Huawei Technologies               | 22        | 0.28%   |
| Edimax Technology                 | 18        | 0.23%   |
| DisplayLink                       | 18        | 0.23%   |
| ASUSTek Computer                  | 18        | 0.23%   |
| Microsoft                         | 16        | 0.21%   |
| Sierra Wireless                   | 15        | 0.19%   |
| OPPO Electronics                  | 14        | 0.18%   |
| Hewlett-Packard                   | 14        | 0.18%   |
| Motorola PCS                      | 11        | 0.14%   |
| Qualcomm                          | 10        | 0.13%   |
| Belkin Components                 | 10        | 0.13%   |
| Linksys                           | 9         | 0.12%   |
| Ericsson Business Mobile Networks | 9         | 0.12%   |
| Aquantia                          | 8         | 0.1%    |
| AMD                               | 8         | 0.1%    |
| T & A Mobile Phones               | 6         | 0.08%   |
| Attansic Technology               | 6         | 0.08%   |
| Google                            | 5         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1584      | 17.61%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 478       | 5.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 208       | 2.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 152       | 1.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 144       | 1.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 130       | 1.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 125       | 1.39%   |
| Intel Wireless 7260                                                     | 121       | 1.35%   |
| Intel Wi-Fi 6 AX200                                                     | 121       | 1.35%   |
| Intel Wireless 7265                                                     | 109       | 1.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 96        | 1.07%   |
| Intel Wireless 8265 / 8275                                              | 92        | 1.02%   |
| Intel Ethernet Connection I217-LM                                       | 88        | 0.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 80        | 0.89%   |
| Intel Wireless 3165                                                     | 75        | 0.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 75        | 0.83%   |
| Broadcom BCM43142 802.11b/g/n                                           | 74        | 0.82%   |
| Realtek RTL8125 2.5GbE Controller                                       | 70        | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 68        | 0.76%   |
| Intel Wi-Fi 6 AX201                                                     | 68        | 0.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 66        | 0.73%   |
| Intel I211 Gigabit Network Connection                                   | 66        | 0.73%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 65        | 0.72%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 65        | 0.72%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 64        | 0.71%   |
| Ralink MT7601U Wireless Adapter                                         | 62        | 0.69%   |
| Intel Wireless 8260                                                     | 62        | 0.69%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 59        | 0.66%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 55        | 0.61%   |
| Realtek 802.11ac NIC                                                    | 53        | 0.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 50        | 0.56%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 50        | 0.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 49        | 0.54%   |
| Intel WiFi Link 5100                                                    | 48        | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 47        | 0.52%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 45        | 0.5%    |
| Nvidia MCP61 Ethernet                                                   | 43        | 0.48%   |
| Intel Ethernet Connection (2) I219-V                                    | 41        | 0.46%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 40        | 0.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 40        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1461      | 34.39%  |
| Qualcomm Atheros                      | 810       | 19.07%  |
| Realtek Semiconductor                 | 797       | 18.76%  |
| Broadcom                              | 434       | 10.22%  |
| Ralink Technology                     | 130       | 3.06%   |
| Broadcom Limited                      | 125       | 2.94%   |
| Ralink                                | 101       | 2.38%   |
| TP-Link                               | 79        | 1.86%   |
| MediaTek                              | 49        | 1.15%   |
| NetGear                               | 30        | 0.71%   |
| D-Link                                | 28        | 0.66%   |
| Qualcomm Atheros Communications       | 24        | 0.56%   |
| Marvell Technology Group              | 22        | 0.52%   |
| D-Link System                         | 19        | 0.45%   |
| Edimax Technology                     | 18        | 0.42%   |
| ASUSTek Computer                      | 16        | 0.38%   |
| Sierra Wireless                       | 15        | 0.35%   |
| Microsoft                             | 13        | 0.31%   |
| Dell                                  | 10        | 0.24%   |
| Belkin Components                     | 10        | 0.24%   |
| Linksys                               | 9         | 0.21%   |
| Sitecom Europe                        | 4         | 0.09%   |
| Micro Star International              | 4         | 0.09%   |
| Gemtek                                | 4         | 0.09%   |
| ZyDAS                                 | 3         | 0.07%   |
| TRENDnet                              | 3         | 0.07%   |
| Hewlett-Packard                       | 3         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.07%   |
| ZyXEL Communications                  | 2         | 0.05%   |
| Xiaomi                                | 2         | 0.05%   |
| Senao                                 | 2         | 0.05%   |
| Philips (or NXP)                      | 2         | 0.05%   |
| IMC Networks                          | 2         | 0.05%   |
| Fibocom                               | 2         | 0.05%   |
| AVM                                   | 2         | 0.05%   |
| Realtek                               | 1         | 0.02%   |
| Qualcomm                              | 1         | 0.02%   |
| Qcom                                  | 1         | 0.02%   |
| Panasonic (Matsushita)                | 1         | 0.02%   |
| Ovislink                              | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 152       | 3.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 144       | 3.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 130       | 3.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 125       | 2.92%   |
| Intel Wireless 7260                                                     | 121       | 2.82%   |
| Intel Wi-Fi 6 AX200                                                     | 121       | 2.82%   |
| Intel Wireless 7265                                                     | 109       | 2.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 96        | 2.24%   |
| Intel Wireless 8265 / 8275                                              | 92        | 2.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 80        | 1.87%   |
| Intel Wireless 3165                                                     | 75        | 1.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 75        | 1.75%   |
| Broadcom BCM43142 802.11b/g/n                                           | 74        | 1.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 68        | 1.59%   |
| Intel Wi-Fi 6 AX201                                                     | 68        | 1.59%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 65        | 1.52%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 64        | 1.49%   |
| Ralink MT7601U Wireless Adapter                                         | 62        | 1.45%   |
| Intel Wireless 8260                                                     | 62        | 1.45%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 59        | 1.38%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 55        | 1.28%   |
| Realtek 802.11ac NIC                                                    | 53        | 1.24%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 50        | 1.17%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 50        | 1.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 49        | 1.14%   |
| Intel WiFi Link 5100                                                    | 48        | 1.12%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 45        | 1.05%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 40        | 0.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 40        | 0.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 39        | 0.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 38        | 0.89%   |
| Intel Wireless 3160                                                     | 35        | 0.82%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 35        | 0.82%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 35        | 0.82%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 34        | 0.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 33        | 0.77%   |
| Intel Centrino Ultimate-N 6300                                          | 33        | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 31        | 0.72%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 30        | 0.7%    |
| Realtek RTL8723DE Wireless Network Adapter                              | 29        | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2287      | 50.72%  |
| Intel                                  | 1004      | 22.27%  |
| Qualcomm Atheros                       | 295       | 6.54%   |
| Broadcom                               | 276       | 6.12%   |
| Nvidia                                 | 125       | 2.77%   |
| Marvell Technology Group               | 118       | 2.62%   |
| Broadcom Limited                       | 77        | 1.71%   |
| ASIX Electronics                       | 34        | 0.75%   |
| VIA Technologies                       | 31        | 0.69%   |
| Silicon Integrated Systems [SiS]       | 31        | 0.69%   |
| Xiaomi                                 | 29        | 0.64%   |
| Samsung Electronics                    | 29        | 0.64%   |
| JMicron Technology                     | 26        | 0.58%   |
| Huawei Technologies                    | 18        | 0.4%    |
| DisplayLink                            | 18        | 0.4%    |
| OPPO Electronics                       | 14        | 0.31%   |
| TP-Link                                | 12        | 0.27%   |
| MediaTek                               | 11        | 0.24%   |
| Qualcomm                               | 9         | 0.2%    |
| Motorola PCS                           | 8         | 0.18%   |
| Aquantia                               | 8         | 0.18%   |
| Attansic Technology                    | 6         | 0.13%   |
| Google                                 | 5         | 0.11%   |
| D-Link System                          | 4         | 0.09%   |
| Sundance Technology Inc / IC Plus      | 3         | 0.07%   |
| Hewlett-Packard                        | 3         | 0.07%   |
| Davicom Semiconductor                  | 3         | 0.07%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.04%   |
| Microsoft                              | 2         | 0.04%   |
| HMD Global                             | 2         | 0.04%   |
| ASUSTek Computer                       | 2         | 0.04%   |
| Apple                                  | 2         | 0.04%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.02%   |
| T & A Mobile Phones                    | 1         | 0.02%   |
| Sun Microsystems                       | 1         | 0.02%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.02%   |
| Research In Motion                     | 1         | 0.02%   |
| Novatel Wireless                       | 1         | 0.02%   |
| NetGear                                | 1         | 0.02%   |
| Motorola BCS                           | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1584      | 34.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 478       | 10.47%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 208       | 4.56%   |
| Intel Ethernet Connection I217-LM                                 | 88        | 1.93%   |
| Realtek RTL8125 2.5GbE Controller                                 | 70        | 1.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 66        | 1.45%   |
| Intel I211 Gigabit Network Connection                             | 66        | 1.45%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 65        | 1.42%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 47        | 1.03%   |
| Nvidia MCP61 Ethernet                                             | 43        | 0.94%   |
| Intel Ethernet Connection (2) I219-V                              | 41        | 0.9%    |
| Intel Ethernet Controller I225-V                                  | 37        | 0.81%   |
| Intel Ethernet Connection I218-LM                                 | 35        | 0.77%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 35        | 0.77%   |
| Intel 82567LM Gigabit Network Connection                          | 33        | 0.72%   |
| Intel 82579V Gigabit Network Connection                           | 31        | 0.68%   |
| Intel 82577LM Gigabit Network Connection                          | 31        | 0.68%   |
| Intel Ethernet Connection I217-V                                  | 28        | 0.61%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 27        | 0.59%   |
| Nvidia MCP79 Ethernet                                             | 27        | 0.59%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 27        | 0.59%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 26        | 0.57%   |
| Intel Ethernet Connection I219-LM                                 | 26        | 0.57%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 26        | 0.57%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 25        | 0.55%   |
| Intel Ethernet Connection (2) I219-LM                             | 25        | 0.55%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 25        | 0.55%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 24        | 0.53%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 24        | 0.53%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 24        | 0.53%   |
| ASIX AX88179 Gigabit Ethernet                                     | 24        | 0.53%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 23        | 0.5%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 23        | 0.5%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 22        | 0.48%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 21        | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 21        | 0.46%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 20        | 0.44%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 20        | 0.44%   |
| Intel 82566MM Gigabit Network Connection                          | 20        | 0.44%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 19        | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4277      | 51.15%  |
| WiFi     | 3944      | 47.17%  |
| Modem    | 128       | 1.53%   |
| Unknown  | 13        | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3097      | 60.24%  |
| Ethernet | 2038      | 39.64%  |
| Modem    | 4         | 0.08%   |
| Unknown  | 2         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2837      | 56.99%  |
| 1     | 1909      | 38.35%  |
| 0     | 155       | 3.11%   |
| 3     | 70        | 1.41%   |
| 5     | 4         | 0.08%   |
| 4     | 2         | 0.04%   |
| 7     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3866      | 76.84%  |
| Yes  | 1165      | 23.16%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 994       | 37.2%   |
| Realtek Semiconductor           | 302       | 11.3%   |
| Qualcomm Atheros Communications | 266       | 9.96%   |
| Broadcom                        | 188       | 7.04%   |
| Cambridge Silicon Radio         | 147       | 5.5%    |
| Apple                           | 142       | 5.31%   |
| IMC Networks                    | 110       | 4.12%   |
| Lite-On Technology              | 79        | 2.96%   |
| Foxconn / Hon Hai               | 70        | 2.62%   |
| Dell                            | 68        | 2.54%   |
| Hewlett-Packard                 | 63        | 2.36%   |
| ASUSTek Computer                | 40        | 1.5%    |
| Toshiba                         | 38        | 1.42%   |
| Ralink                          | 25        | 0.94%   |
| Marvell Semiconductor           | 18        | 0.67%   |
| Realtek                         | 14        | 0.52%   |
| MediaTek                        | 14        | 0.52%   |
| Alps Electric                   | 14        | 0.52%   |
| Foxconn International           | 12        | 0.45%   |
| Dynex                           | 10        | 0.37%   |
| TP-Link                         | 7         | 0.26%   |
| Integrated System Solution      | 7         | 0.26%   |
| Belkin Components               | 6         | 0.22%   |
| Askey Computer                  | 6         | 0.22%   |
| Ralink Technology               | 5         | 0.19%   |
| Taiyo Yuden                     | 4         | 0.15%   |
| Micro Star International        | 4         | 0.15%   |
| Chicony Electronics             | 3         | 0.11%   |
| Unknown                         | 3         | 0.11%   |
| Qcom                            | 2         | 0.07%   |
| ISSC                            | 2         | 0.07%   |
| Actions                         | 2         | 0.07%   |
| Sitecom Europe                  | 1         | 0.04%   |
| National Semiconductor          | 1         | 0.04%   |
| Mobile Action Technology        | 1         | 0.04%   |
| Logitech                        | 1         | 0.04%   |
| Fujitsu                         | 1         | 0.04%   |
| Edimax Technology               | 1         | 0.04%   |
| D-Link System                   | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 469       | 17.53%  |
| Realtek Bluetooth Radio                             | 196       | 7.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 147       | 5.5%    |
| Intel AX201 Bluetooth                               | 124       | 4.64%   |
| Qualcomm Atheros  Bluetooth Device                  | 114       | 4.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 113       | 4.22%   |
| Intel AX200 Bluetooth                               | 106       | 3.96%   |
| Realtek  Bluetooth 4.2 Adapter                      | 80        | 2.99%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 49        | 1.83%   |
| Apple Bluetooth Host Controller                     | 49        | 1.83%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 44        | 1.64%   |
| Intel AX210 Bluetooth                               | 42        | 1.57%   |
| IMC Networks Bluetooth Device                       | 41        | 1.53%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 37        | 1.38%   |
| Intel Wireless-AC 3168 Bluetooth                    | 37        | 1.38%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 37        | 1.38%   |
| Apple Bluetooth USB Host Controller                 | 37        | 1.38%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 36        | 1.35%   |
| IMC Networks Bluetooth Radio                        | 33        | 1.23%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 29        | 1.08%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 28        | 1.05%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 28        | 1.05%   |
| Lite-On Atheros AR3012 Bluetooth                    | 26        | 0.97%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 26        | 0.97%   |
| Ralink RT3290 Bluetooth                             | 25        | 0.93%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 21        | 0.79%   |
| HP Broadcom 2070 Bluetooth Combo                    | 21        | 0.79%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 20        | 0.75%   |
| Foxconn / Hon Hai Bluetooth Device                  | 19        | 0.71%   |
| Dell DW375 Bluetooth Module                         | 19        | 0.71%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 19        | 0.71%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 19        | 0.71%   |
| Broadcom BCM2045B (BDC-2.1)                         | 19        | 0.71%   |
| Apple Bluetooth HCI                                 | 19        | 0.71%   |
| Marvell Bluetooth and Wireless LAN Composite        | 17        | 0.64%   |
| Lite-On Bluetooth Device                            | 16        | 0.6%    |
| Realtek Bluetooth Radio                             | 14        | 0.52%   |
| IMC Networks Wireless_Device                        | 13        | 0.49%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 13        | 0.49%   |
| Broadcom BCM2045 Bluetooth                          | 13        | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3604      | 56.59%  |
| AMD                                          | 1288      | 20.22%  |
| Nvidia                                       | 981       | 15.4%   |
| C-Media Electronics                          | 82        | 1.29%   |
| Silicon Integrated Systems [SiS]             | 36        | 0.57%   |
| VIA Technologies                             | 35        | 0.55%   |
| Creative Labs                                | 34        | 0.53%   |
| Logitech                                     | 27        | 0.42%   |
| Texas Instruments                            | 19        | 0.3%    |
| Generalplus Technology                       | 19        | 0.3%    |
| JMTek                                        | 16        | 0.25%   |
| Kingston Technology                          | 14        | 0.22%   |
| GN Netcom                                    | 12        | 0.19%   |
| Creative Technology                          | 12        | 0.19%   |
| ASUSTek Computer                             | 12        | 0.19%   |
| Realtek Semiconductor                        | 11        | 0.17%   |
| Tenx Technology                              | 10        | 0.16%   |
| Razer USA                                    | 10        | 0.16%   |
| Plantronics                                  | 10        | 0.16%   |
| SteelSeries ApS                              | 6         | 0.09%   |
| Lenovo                                       | 5         | 0.08%   |
| Focusrite-Novation                           | 5         | 0.08%   |
| DCMT Technology                              | 5         | 0.08%   |
| Corsair                                      | 5         | 0.08%   |
| Yamaha                                       | 4         | 0.06%   |
| Astro Gaming                                 | 4         | 0.06%   |
| Thesycon Systemsoftware & Consulting         | 3         | 0.05%   |
| Sennheiser Communications                    | 3         | 0.05%   |
| Samsung Electronics                          | 3         | 0.05%   |
| RODE Microphones                             | 3         | 0.05%   |
| Micro Star International                     | 3         | 0.05%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.03%   |
| XMOS                                         | 2         | 0.03%   |
| Turtle Beach                                 | 2         | 0.03%   |
| Sony                                         | 2         | 0.03%   |
| SAVITECH                                     | 2         | 0.03%   |
| OPPO Electronics                             | 2         | 0.03%   |
| Numark                                       | 2         | 0.03%   |
| Micronas                                     | 2         | 0.03%   |
| KTMicro                                      | 2         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 399       | 5.3%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 365       | 4.84%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 315       | 4.18%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 300       | 3.98%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 254       | 3.37%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 248       | 3.29%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 234       | 3.11%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 234       | 3.11%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 212       | 2.81%   |
| AMD FCH Azalia Controller                                                                         | 210       | 2.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 182       | 2.42%   |
| Intel 8 Series HD Audio Controller                                                                | 145       | 1.92%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 141       | 1.87%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 138       | 1.83%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 116       | 1.54%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 112       | 1.49%   |
| AMD Kabini HDMI/DP Audio                                                                          | 109       | 1.45%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 104       | 1.38%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 101       | 1.34%   |
| Intel Broadwell-U Audio Controller                                                                | 100       | 1.33%   |
| Intel Cannon Lake PCH cAVS                                                                        | 99        | 1.31%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 95        | 1.26%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 93        | 1.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 88        | 1.17%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 87        | 1.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 84        | 1.11%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 75        | 1%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 74        | 0.98%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 66        | 0.88%   |
| Nvidia High Definition Audio Controller                                                           | 64        | 0.85%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 62        | 0.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 61        | 0.81%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 60        | 0.8%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 57        | 0.76%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 56        | 0.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 55        | 0.73%   |
| AMD High Definition Audio Controller                                                              | 53        | 0.7%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 49        | 0.65%   |
| Intel 200 Series PCH HD Audio                                                                     | 48        | 0.64%   |
| Nvidia MCP61 High Definition Audio                                                                | 45        | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 230       | 21.93%  |
| SK hynix               | 202       | 19.26%  |
| Unknown                | 140       | 13.35%  |
| Micron Technology      | 96        | 9.15%   |
| Kingston               | 89        | 8.48%   |
| Crucial                | 47        | 4.48%   |
| Corsair                | 29        | 2.76%   |
| G.Skill                | 26        | 2.48%   |
| Unknown (ABCD)         | 22        | 2.1%    |
| Elpida                 | 21        | 2%      |
| Ramaxel Technology     | 19        | 1.81%   |
| Nanya Technology       | 19        | 1.81%   |
| A-DATA Technology      | 16        | 1.53%   |
| Team                   | 11        | 1.05%   |
| Smart                  | 7         | 0.67%   |
| Unknown                | 7         | 0.67%   |
| Qimonda                | 6         | 0.57%   |
| Patriot                | 6         | 0.57%   |
| Transcend              | 3         | 0.29%   |
| Avant                  | 3         | 0.29%   |
| Wilk                   | 2         | 0.19%   |
| Unifosa                | 2         | 0.19%   |
| Timetec                | 2         | 0.19%   |
| Teikon                 | 2         | 0.19%   |
| Smart Brazil           | 2         | 0.19%   |
| SHARETRONIC            | 2         | 0.19%   |
| PNY                    | 2         | 0.19%   |
| High Bridge            | 2         | 0.19%   |
| ff                     | 2         | 0.19%   |
| fef5                   | 2         | 0.19%   |
| CSX                    | 2         | 0.19%   |
| 4ea5                   | 2         | 0.19%   |
| Walton Chaintech       | 1         | 0.1%    |
| Unknown (08B5)         | 1         | 0.1%    |
| Unknown (07F7)         | 1         | 0.1%    |
| Unknown (000080B30080) | 1         | 0.1%    |
| Toshiba                | 1         | 0.1%    |
| SUPER KINGSTEK         | 1         | 0.1%    |
| Strontium              | 1         | 0.1%    |
| Ramos Technology       | 1         | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 20        | 1.78%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 13        | 1.16%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.8%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 9         | 0.8%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 9         | 0.8%    |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s             | 8         | 0.71%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.71%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.62%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 7         | 0.62%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 0.62%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.62%   |
| Unknown                                                          | 7         | 0.62%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.53%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.53%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 6         | 0.53%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.53%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.53%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 6         | 0.53%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 5         | 0.44%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 5         | 0.44%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 5         | 0.44%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 0.44%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 5         | 0.44%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 5         | 0.44%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 5         | 0.44%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 5         | 0.44%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 4         | 0.36%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 4         | 0.36%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 4         | 0.36%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR2 975MT/s            | 4         | 0.36%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.36%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.36%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.36%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 4         | 0.36%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.36%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 4         | 0.36%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.36%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 4         | 0.36%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 4         | 0.36%   |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 4         | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 343       | 37.69%  |
| DDR4    | 311       | 34.18%  |
| DDR2    | 88        | 9.67%   |
| LPDDR4  | 48        | 5.27%   |
| SDRAM   | 40        | 4.4%    |
| Unknown | 31        | 3.41%   |
| LPDDR3  | 28        | 3.08%   |
| DDR     | 10        | 1.1%    |
| DRAM    | 6         | 0.66%   |
| DDR5    | 4         | 0.44%   |
| LPDDR5  | 1         | 0.11%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 566       | 63.24%  |
| DIMM         | 251       | 28.04%  |
| Row Of Chips | 65        | 7.26%   |
| Unknown      | 7         | 0.78%   |
| Chip         | 5         | 0.56%   |
| FB-DIMM      | 1         | 0.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 314       | 30.97%  |
| 8192  | 306       | 30.18%  |
| 2048  | 205       | 20.22%  |
| 16384 | 79        | 7.79%   |
| 1024  | 77        | 7.59%   |
| 32768 | 17        | 1.68%   |
| 512   | 14        | 1.38%   |
| 256   | 2         | 0.2%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 215       | 21.85%  |
| 2667    | 107       | 10.87%  |
| 3200    | 106       | 10.77%  |
| 1333    | 71        | 7.22%   |
| 2400    | 67        | 6.81%   |
| 667     | 47        | 4.78%   |
| Unknown | 41        | 4.17%   |
| 1334    | 40        | 4.07%   |
| 2133    | 37        | 3.76%   |
| 800     | 28        | 2.85%   |
| 1066    | 22        | 2.24%   |
| 1867    | 18        | 1.83%   |
| 3600    | 17        | 1.73%   |
| 4267    | 15        | 1.52%   |
| 3266    | 15        | 1.52%   |
| 2048    | 11        | 1.12%   |
| 975     | 11        | 1.12%   |
| 533     | 11        | 1.12%   |
| 4199    | 9         | 0.91%   |
| 1067    | 8         | 0.81%   |
| 3000    | 7         | 0.71%   |
| 1866    | 7         | 0.71%   |
| 2933    | 6         | 0.61%   |
| 1800    | 6         | 0.61%   |
| 400     | 6         | 0.61%   |
| 4800    | 4         | 0.41%   |
| 3733    | 4         | 0.41%   |
| 333     | 4         | 0.41%   |
| 8400    | 3         | 0.3%    |
| 4266    | 3         | 0.3%    |
| 3866    | 3         | 0.3%    |
| 2800    | 3         | 0.3%    |
| 2666    | 3         | 0.3%    |
| 6400    | 2         | 0.2%    |
| 3800    | 2         | 0.2%    |
| 3666    | 2         | 0.2%    |
| 3466    | 2         | 0.2%    |
| 3400    | 2         | 0.2%    |
| 3333    | 2         | 0.2%    |
| 1639    | 2         | 0.2%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 40        | 29.41%  |
| Canon                 | 29        | 21.32%  |
| Brother Industries    | 23        | 16.91%  |
| Seiko Epson           | 18        | 13.24%  |
| Samsung Electronics   | 15        | 11.03%  |
| Lexmark International | 3         | 2.21%   |
| STMicroelectronics    | 2         | 1.47%   |
| Zebra                 | 1         | 0.74%   |
| Toshiba TEC           | 1         | 0.74%   |
| Ricoh                 | 1         | 0.74%   |
| QinHeng Electronics   | 1         | 0.74%   |
| Pantum                | 1         | 0.74%   |
| Konica Minolta        | 1         | 0.74%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Canon TS3100 series                                       | 4         | 2.94%   |
| Seiko Epson L3110 Series                                  | 3         | 2.21%   |
| HP DeskJet 2700 series                                    | 3         | 2.21%   |
| Canon PIXMA MG2500 Series                                 | 3         | 2.21%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 1.47%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 2         | 1.47%   |
| Samsung SCX-3400 Series                                   | 2         | 1.47%   |
| Samsung ML-216x Series Laser Printer                      | 2         | 1.47%   |
| Samsung CLX-3300 Series                                   | 2         | 1.47%   |
| Samsung C460 Series                                       | 2         | 1.47%   |
| HP LaserJet Professional P1102w                           | 2         | 1.47%   |
| HP LaserJet Professional P 1102w                          | 2         | 1.47%   |
| HP ENVY Photo 6200 series                                 | 2         | 1.47%   |
| HP ENVY 5000 series                                       | 2         | 1.47%   |
| HP ENVY 4520 series                                       | 2         | 1.47%   |
| HP DeskJet 2130 series                                    | 2         | 1.47%   |
| HP DeskJet 1110 series                                    | 2         | 1.47%   |
| Canon PIXMA MX340                                         | 2         | 1.47%   |
| Canon MF4010 series                                       | 2         | 1.47%   |
| Canon LiDE 400                                            | 2         | 1.47%   |
| Brother HL-2140 series                                    | 2         | 1.47%   |
| Brother HL-2130 series                                    | 2         | 1.47%   |
| Zebra ZP 450 Printer                                      | 1         | 0.74%   |
| Toshiba TEC e-STD120 USB                                  | 1         | 0.74%   |
| Seiko Epson XP-7100 Series                                | 1         | 0.74%   |
| Seiko Epson XP-225 Series                                 | 1         | 0.74%   |
| Seiko Epson XP-200 Series                                 | 1         | 0.74%   |
| Seiko Epson WF-2010 Series                                | 1         | 0.74%   |
| Seiko Epson Printer                                       | 1         | 0.74%   |
| Seiko Epson L365 Series                                   | 1         | 0.74%   |
| Seiko Epson L355 Series                                   | 1         | 0.74%   |
| Seiko Epson L220 Series                                   | 1         | 0.74%   |
| Seiko Epson L120 Series                                   | 1         | 0.74%   |
| Seiko Epson ET-2820 Series                                | 1         | 0.74%   |
| Seiko Epson ET-2810 Series                                | 1         | 0.74%   |
| Seiko Epson ET-2710 Series                                | 1         | 0.74%   |
| Seiko Epson AcuLaser C1700                                | 1         | 0.74%   |
| Samsung SCX-483x 5x3x Series                              | 1         | 0.74%   |
| Samsung SCX-4623 Series                                   | 1         | 0.74%   |
| Samsung SCX-4200 series                                   | 1         | 0.74%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 13        | 76.47%  |
| Seiko Epson     | 2         | 11.76%  |
| Hewlett-Packard | 2         | 11.76%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20          | 3         | 17.65%  |
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 2         | 11.76%  |
| Canon CanoScan LIDE 25                      | 2         | 11.76%  |
| Canon CanoScan LiDE 100                     | 2         | 11.76%  |
| HP ScanJet 2400c                            | 1         | 5.88%   |
| HP PSC 1200                                 | 1         | 5.88%   |
| Canon CanoScan LiDE 90                      | 1         | 5.88%   |
| Canon CanoScan LiDE 60                      | 1         | 5.88%   |
| Canon CanoScan LiDE 200                     | 1         | 5.88%   |
| Canon CanoScan LiDE 110                     | 1         | 5.88%   |
| Canon CanoScan D660U                        | 1         | 5.88%   |
| Canon CanoScan 8800F                        | 1         | 5.88%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 624       | 22.53%  |
| Microdia                               | 252       | 9.1%    |
| Realtek Semiconductor                  | 213       | 7.69%   |
| IMC Networks                           | 188       | 6.79%   |
| Sunplus Innovation Technology          | 141       | 5.09%   |
| Apple                                  | 135       | 4.87%   |
| Suyin                                  | 128       | 4.62%   |
| Cheng Uei Precision Industry (Foxlink) | 118       | 4.26%   |
| Bison Electronics                      | 111       | 4.01%   |
| Quanta                                 | 101       | 3.65%   |
| Logitech                               | 92        | 3.32%   |
| Acer                                   | 70        | 2.53%   |
| Syntek                                 | 67        | 2.42%   |
| Silicon Motion                         | 54        | 1.95%   |
| Lite-On Technology                     | 50        | 1.81%   |
| Alcor Micro                            | 47        | 1.7%    |
| Ricoh                                  | 32        | 1.16%   |
| Samsung Electronics                    | 29        | 1.05%   |
| Microsoft                              | 27        | 0.97%   |
| Luxvisions Innotech Limited            | 19        | 0.69%   |
| ALi                                    | 19        | 0.69%   |
| Z-Star Microelectronics                | 18        | 0.65%   |
| Importek                               | 17        | 0.61%   |
| Primax Electronics                     | 15        | 0.54%   |
| GEMBIRD                                | 14        | 0.51%   |
| USB Camera                             | 13        | 0.47%   |
| Generalplus Technology                 | 13        | 0.47%   |
| Sonix Technology                       | 11        | 0.4%    |
| Lenovo                                 | 11        | 0.4%    |
| ARC International                      | 10        | 0.36%   |
| OmniVision Technologies                | 9         | 0.32%   |
| SunplusIT                              | 7         | 0.25%   |
| Genesys Logic                          | 7         | 0.25%   |
| Cubeternet                             | 7         | 0.25%   |
| Sunplus Technology                     | 5         | 0.18%   |
| Shenzhen Kingcome Optoelectronic       | 5         | 0.18%   |
| Jieli Technology                       | 5         | 0.18%   |
| Razer USA                              | 4         | 0.14%   |
| Pixart Imaging                         | 4         | 0.14%   |
| Intel                                  | 4         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 77        | 2.76%   |
| Microdia Integrated_Webcam_HD                    | 46        | 1.65%   |
| IMC Networks USB2.0 HD UVC WebCam                | 44        | 1.58%   |
| Apple FaceTime HD Camera (Built-in)              | 44        | 1.58%   |
| Realtek Integrated_Webcam_HD                     | 43        | 1.54%   |
| Chicony HD WebCam                                | 38        | 1.36%   |
| Microdia Integrated Webcam                       | 36        | 1.29%   |
| Chicony HP Truevision HD                         | 35        | 1.26%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                  | 34        | 1.22%   |
| Syntek Integrated Camera                         | 32        | 1.15%   |
| Apple Built-in iSight                            | 32        | 1.15%   |
| Samsung Galaxy A5 (MTP)                          | 29        | 1.04%   |
| Bison Integrated Camera                          | 29        | 1.04%   |
| Chicony TOSHIBA Web Camera - HD                  | 28        | 1%      |
| IMC Networks Integrated Camera                   | 27        | 0.97%   |
| Chicony USB 2.0 Camera                           | 27        | 0.97%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 26        | 0.93%   |
| Chicony HP TrueVision HD Camera                  | 24        | 0.86%   |
| Acer Lenovo EasyCamera                           | 24        | 0.86%   |
| Sunplus Integrated_Webcam_HD                     | 23        | 0.83%   |
| Realtek Integrated Webcam                        | 22        | 0.79%   |
| Logitech Webcam C270                             | 22        | 0.79%   |
| Chicony EasyCamera                               | 22        | 0.79%   |
| Chicony Lenovo EasyCamera                        | 21        | 0.75%   |
| Sunplus HD WebCam                                | 19        | 0.68%   |
| Chicony VGA WebCam                               | 19        | 0.68%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 19        | 0.68%   |
| Realtek USB Camera                               | 18        | 0.65%   |
| Chicony HP Wide Vision HD Camera                 | 18        | 0.65%   |
| Chicony HP HD Webcam                             | 18        | 0.65%   |
| Alcor Micro USB 2.0 Camera                       | 18        | 0.65%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 17        | 0.61%   |
| Suyin HP Truevision HD                           | 16        | 0.57%   |
| Realtek HP Truevision HD                         | 16        | 0.57%   |
| Quanta HP TrueVision HD Camera                   | 16        | 0.57%   |
| Chicony USB2.0 VGA UVC WebCam                    | 16        | 0.57%   |
| Chicony HP Webcam                                | 16        | 0.57%   |
| ALi Gateway Webcam                               | 16        | 0.57%   |
| Quanta HP Webcam                                 | 15        | 0.54%   |
| Microdia Webcam Vitade AF                        | 15        | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 194       | 43.5%   |
| AuthenTec                  | 61        | 13.68%  |
| Synaptics                  | 51        | 11.43%  |
| Shenzhen Goodix Technology | 49        | 10.99%  |
| Upek                       | 32        | 7.17%   |
| Elan Microelectronics      | 25        | 5.61%   |
| STMicroelectronics         | 18        | 4.04%   |
| LighTuning Technology      | 11        | 2.47%   |
| Samsung Electronics        | 2         | 0.45%   |
| Next Biometrics            | 1         | 0.22%   |
| HOLTEK                     | 1         | 0.22%   |
| Focal-systems.Corp         | 1         | 0.22%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 41        | 9.19%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 31        | 6.95%   |
| Shenzhen Goodix  FingerPrint Device                                        | 28        | 6.28%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 24        | 5.38%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 21        | 4.71%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 20        | 4.48%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 18        | 4.04%   |
| Validity Sensors VFS491                                                    | 18        | 4.04%   |
| Validity Sensors Fingerprint scanner                                       | 18        | 4.04%   |
| STMicroelectronics Fingerprint Reader                                      | 18        | 4.04%   |
| AuthenTec AES2810                                                          | 18        | 4.04%   |
| Shenzhen Goodix Fingerprint Reader                                         | 17        | 3.81%   |
| Elan ELAN:ARM-M4                                                           | 14        | 3.14%   |
| Synaptics  WBDI                                                            | 12        | 2.69%   |
| Elan ELAN:Fingerprint                                                      | 11        | 2.47%   |
| AuthenTec AES1600                                                          | 10        | 2.24%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 9         | 2.02%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 1.79%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 1.79%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 7         | 1.57%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 1.35%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 1.35%   |
| Synaptics UWP WBDI                                                         | 6         | 1.35%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 1.35%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 1.35%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.12%   |
| Synaptics WBDI                                                             | 5         | 1.12%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.9%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 4         | 0.9%    |
| Shenzhen Goodix FingerPrint                                                | 4         | 0.9%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 0.9%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 4         | 0.9%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.67%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 0.67%   |
| LighTuning Fingerprint Sensor                                              | 3         | 0.67%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.67%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.45%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.45%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.45%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 0.45%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 91        | 50%     |
| Alcor Micro                       | 29        | 15.93%  |
| O2 Micro                          | 27        | 14.84%  |
| Lenovo                            | 9         | 4.95%   |
| Upek                              | 7         | 3.85%   |
| Realtek Semiconductor             | 4         | 2.2%    |
| SCM Microsystems                  | 3         | 1.65%   |
| Yubico.com                        | 2         | 1.1%    |
| VASCO Data Security International | 2         | 1.1%    |
| Fujitsu Siemens Computers         | 2         | 1.1%    |
| Advanced Card Systems             | 2         | 1.1%    |
| Reiner SCT Kartensysteme          | 1         | 0.55%   |
| OmniKey                           | 1         | 0.55%   |
| Kobil Systems                     | 1         | 0.55%   |
| Chicony Electronics               | 1         | 0.55%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 44        | 24.04%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 28        | 15.3%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 22        | 12.02%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 22        | 12.02%  |
| Broadcom 5880                                                                | 19        | 10.38%  |
| Lenovo Integrated Smart Card Reader                                          | 9         | 4.92%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 3.83%   |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 2.73%   |
| Broadcom 58200                                                               | 5         | 2.73%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 4         | 2.19%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.09%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1.09%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 2         | 1.09%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 1.09%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.55%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.55%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.55%   |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad                              | 1         | 0.55%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.55%   |
| Kobil Systems KOBIL Class 3 Reader                                           | 1         | 0.55%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.55%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.55%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.55%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.55%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3531      | 70.02%  |
| 1     | 1221      | 24.21%  |
| 2     | 261       | 5.18%   |
| 3     | 24        | 0.48%   |
| 4     | 4         | 0.08%   |
| 8     | 1         | 0.02%   |
| 7     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 439       | 24.79%  |
| Graphics card            | 427       | 24.11%  |
| Net/wireless             | 306       | 17.28%  |
| Chipcard                 | 170       | 9.6%    |
| Multimedia controller    | 148       | 8.36%   |
| Modem                    | 47        | 2.65%   |
| Communication controller | 47        | 2.65%   |
| Storage                  | 45        | 2.54%   |
| Bluetooth                | 35        | 1.98%   |
| Sound                    | 21        | 1.19%   |
| Camera                   | 16        | 0.9%    |
| Unassigned class         | 15        | 0.85%   |
| Flash memory             | 13        | 0.73%   |
| Net/ethernet             | 11        | 0.62%   |
| Storage/raid             | 6         | 0.34%   |
| Network                  | 6         | 0.34%   |
| Card reader              | 6         | 0.34%   |
| Storage/ide              | 4         | 0.23%   |
| Dvb card                 | 4         | 0.23%   |
| Storage/nvme             | 3         | 0.17%   |
| Unclassified device      | 1         | 0.06%   |
| Storage/ata              | 1         | 0.06%   |

