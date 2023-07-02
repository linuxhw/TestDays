Linux in Brazil - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Brazil.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Brazil/Desktop/README.md) and [notebooks](/Location/Brazil/Notebook/README.md).

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

Total: 19128

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASRock        | A320M-HD                    | Desktop     | [1df7c65f40](https://linux-hardware.org/?probe=1df7c65f40) | Jul 01, 2023 |
| ZR            | A320M-F 1005                | Desktop     | [c32d8de777](https://linux-hardware.org/?probe=c32d8de777) | Jun 30, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [292b7f6f0f](https://linux-hardware.org/?probe=292b7f6f0f) | Jun 30, 2023 |
| Intel         | X99 V1.x                    | Desktop     | [8e4ce021b1](https://linux-hardware.org/?probe=8e4ce021b1) | Jun 30, 2023 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [69b69e2a09](https://linux-hardware.org/?probe=69b69e2a09) | Jun 30, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [7c3ce62039](https://linux-hardware.org/?probe=7c3ce62039) | Jun 30, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [8386acaa29](https://linux-hardware.org/?probe=8386acaa29) | Jun 30, 2023 |
| AZW           | SEi                         | Desktop     | [37527da518](https://linux-hardware.org/?probe=37527da518) | Jun 30, 2023 |
| Lenovo        | ThinkPad T495 20NK000XBR    | Notebook    | [2b5e40efaa](https://linux-hardware.org/?probe=2b5e40efaa) | Jun 30, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [3e1517b7a7](https://linux-hardware.org/?probe=3e1517b7a7) | Jun 30, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [b95a7c049a](https://linux-hardware.org/?probe=b95a7c049a) | Jun 30, 2023 |
| eMachines     | eME443                      | Notebook    | [0d6808da66](https://linux-hardware.org/?probe=0d6808da66) | Jun 30, 2023 |
| Intel         | B75                         | Desktop     | [73d881c953](https://linux-hardware.org/?probe=73d881c953) | Jun 30, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [7cb124d729](https://linux-hardware.org/?probe=7cb124d729) | Jun 30, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [136060092c](https://linux-hardware.org/?probe=136060092c) | Jun 30, 2023 |
| Positivo      | Mobile                      | Notebook    | [fdaaf6915b](https://linux-hardware.org/?probe=fdaaf6915b) | Jun 30, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [45d5903c62](https://linux-hardware.org/?probe=45d5903c62) | Jun 30, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [3aa4a11068](https://linux-hardware.org/?probe=3aa4a11068) | Jun 30, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [3a8a822af9](https://linux-hardware.org/?probe=3a8a822af9) | Jun 30, 2023 |
| Positivo      | S14CT01                     | Notebook    | [b70845bd08](https://linux-hardware.org/?probe=b70845bd08) | Jun 29, 2023 |
| Intel         | X99 V1.x                    | Desktop     | [1c7ef9ef35](https://linux-hardware.org/?probe=1c7ef9ef35) | Jun 29, 2023 |
| PCWare        | IPMH61R3                    | Desktop     | [e190259144](https://linux-hardware.org/?probe=e190259144) | Jun 29, 2023 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [d0ec676a22](https://linux-hardware.org/?probe=d0ec676a22) | Jun 29, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [cfbc8c8a97](https://linux-hardware.org/?probe=cfbc8c8a97) | Jun 29, 2023 |
| Acer          | TravelMate P449-G2-M        | Notebook    | [b9291d6951](https://linux-hardware.org/?probe=b9291d6951) | Jun 29, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [f0fdd509f7](https://linux-hardware.org/?probe=f0fdd509f7) | Jun 29, 2023 |
| Positivo      | H14CU02                     | Notebook    | [d50e6fbbdc](https://linux-hardware.org/?probe=d50e6fbbdc) | Jun 29, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [bb1cb1ef13](https://linux-hardware.org/?probe=bb1cb1ef13) | Jun 29, 2023 |
| Dell          | Inspiron 1440               | Notebook    | [ed9bcaecd2](https://linux-hardware.org/?probe=ed9bcaecd2) | Jun 29, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [25a1aaf938](https://linux-hardware.org/?probe=25a1aaf938) | Jun 29, 2023 |
| HP            | 0B54h D                     | Desktop     | [c13f21ea22](https://linux-hardware.org/?probe=c13f21ea22) | Jun 29, 2023 |
| Dell          | 0T656F A02                  | Desktop     | [bf4264c797](https://linux-hardware.org/?probe=bf4264c797) | Jun 29, 2023 |
| Sony          | SVE17137CXB                 | Notebook    | [ed6f82dc16](https://linux-hardware.org/?probe=ed6f82dc16) | Jun 29, 2023 |
| MSI           | MS-7438 100                 | Desktop     | [4d0d23065e](https://linux-hardware.org/?probe=4d0d23065e) | Jun 29, 2023 |
| Intel         | DG41RQ AAE54511-205         | Desktop     | [0e896bc137](https://linux-hardware.org/?probe=0e896bc137) | Jun 29, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [a41ff8c573](https://linux-hardware.org/?probe=a41ff8c573) | Jun 29, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [5683980090](https://linux-hardware.org/?probe=5683980090) | Jun 28, 2023 |
| Dell          | 00X7CK A04                  | Server      | [c59e7b7f26](https://linux-hardware.org/?probe=c59e7b7f26) | Jun 28, 2023 |
| ZR            | A320M-F 1005                | Desktop     | [f70bb41b80](https://linux-hardware.org/?probe=f70bb41b80) | Jun 28, 2023 |
| Huanan        | Unknown                     | Desktop     | [397d33202e](https://linux-hardware.org/?probe=397d33202e) | Jun 28, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [2f12ef933e](https://linux-hardware.org/?probe=2f12ef933e) | Jun 28, 2023 |
| ASRock        | B460M-HDV                   | Desktop     | [966b21f9af](https://linux-hardware.org/?probe=966b21f9af) | Jun 28, 2023 |
| ASRock        | H310CM-HG4                  | Desktop     | [8147961b6c](https://linux-hardware.org/?probe=8147961b6c) | Jun 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [f64ccf77fb](https://linux-hardware.org/?probe=f64ccf77fb) | Jun 28, 2023 |
| Fill By OE... | Q7700                       | Desktop     | [93c7c01ecb](https://linux-hardware.org/?probe=93c7c01ecb) | Jun 28, 2023 |
| Toshiba       | PORTEGE R500                | Notebook    | [2c6448083e](https://linux-hardware.org/?probe=2c6448083e) | Jun 28, 2023 |
| Acer          | Aspire A315-23G             | Notebook    | [1c07c9f0b8](https://linux-hardware.org/?probe=1c07c9f0b8) | Jun 28, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [235e541e2d](https://linux-hardware.org/?probe=235e541e2d) | Jun 28, 2023 |
| Acer          | Aspire 4349                 | Notebook    | [9064db77e4](https://linux-hardware.org/?probe=9064db77e4) | Jun 28, 2023 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [bca3e799e0](https://linux-hardware.org/?probe=bca3e799e0) | Jun 27, 2023 |
| HP            | 871A                        | Mini pc     | [79b5fd11c3](https://linux-hardware.org/?probe=79b5fd11c3) | Jun 27, 2023 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [2faeb24e37](https://linux-hardware.org/?probe=2faeb24e37) | Jun 27, 2023 |
| Kennex        | POS-PIG41BA                 | Desktop     | [90addad9e1](https://linux-hardware.org/?probe=90addad9e1) | Jun 27, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [894f8583ea](https://linux-hardware.org/?probe=894f8583ea) | Jun 27, 2023 |
| ASRock        | H310CM-HG4                  | Desktop     | [16c2222f50](https://linux-hardware.org/?probe=16c2222f50) | Jun 27, 2023 |
| Dell          | Vostro 15 3510              | Notebook    | [adb3a3de68](https://linux-hardware.org/?probe=adb3a3de68) | Jun 27, 2023 |
| Clevo         | M540SS Bottom               | Notebook    | [4b613733a0](https://linux-hardware.org/?probe=4b613733a0) | Jun 27, 2023 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [6f9c836bb4](https://linux-hardware.org/?probe=6f9c836bb4) | Jun 27, 2023 |
| Samsung       | 305U1A                      | Notebook    | [cd7de3aecf](https://linux-hardware.org/?probe=cd7de3aecf) | Jun 27, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [ec69000909](https://linux-hardware.org/?probe=ec69000909) | Jun 27, 2023 |
| Fill By OE... | Q7700                       | Desktop     | [32ac9cb839](https://linux-hardware.org/?probe=32ac9cb839) | Jun 27, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [0bfb7dc30a](https://linux-hardware.org/?probe=0bfb7dc30a) | Jun 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [fce3ec0379](https://linux-hardware.org/?probe=fce3ec0379) | Jun 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [5eac5b8b6d](https://linux-hardware.org/?probe=5eac5b8b6d) | Jun 27, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [882bd512a2](https://linux-hardware.org/?probe=882bd512a2) | Jun 27, 2023 |
| Supermicro    | C7Z370-CG-L                 | Server      | [5731d8f8dc](https://linux-hardware.org/?probe=5731d8f8dc) | Jun 27, 2023 |
| Acer          | Aspire VX5-591G             | Notebook    | [b4bd8360ea](https://linux-hardware.org/?probe=b4bd8360ea) | Jun 27, 2023 |
| Acer          | Aspire VX5-591G             | Notebook    | [1ffeb058e9](https://linux-hardware.org/?probe=1ffeb058e9) | Jun 27, 2023 |
| Daten Tecn... | ESTELAR                     | Notebook    | [0052df6a90](https://linux-hardware.org/?probe=0052df6a90) | Jun 27, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [e1e76b3d77](https://linux-hardware.org/?probe=e1e76b3d77) | Jun 27, 2023 |
| Samsung       | 305U1A                      | Notebook    | [ab46376842](https://linux-hardware.org/?probe=ab46376842) | Jun 27, 2023 |
| Supermicro    | C7Z370-CG-L                 | Server      | [c373b5b24d](https://linux-hardware.org/?probe=c373b5b24d) | Jun 26, 2023 |
| Samsung       | 305U1A                      | Notebook    | [b2f2c2b000](https://linux-hardware.org/?probe=b2f2c2b000) | Jun 26, 2023 |
| Intel         | DH55TC AAE70932-206         | Desktop     | [9ff872e2a3](https://linux-hardware.org/?probe=9ff872e2a3) | Jun 26, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [6e179dbfb0](https://linux-hardware.org/?probe=6e179dbfb0) | Jun 26, 2023 |
| Positivo      | POS-PIH81DI                 | Desktop     | [42e304c777](https://linux-hardware.org/?probe=42e304c777) | Jun 26, 2023 |
| Daten Tecn... | ESTELAR                     | Notebook    | [d5f99bced6](https://linux-hardware.org/?probe=d5f99bced6) | Jun 26, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [e89c1b2b89](https://linux-hardware.org/?probe=e89c1b2b89) | Jun 26, 2023 |
| eMachines     | E525                        | Notebook    | [9e477a5fad](https://linux-hardware.org/?probe=9e477a5fad) | Jun 26, 2023 |
| Positivo      | POS-PIH81DI                 | Desktop     | [77d2d3d01b](https://linux-hardware.org/?probe=77d2d3d01b) | Jun 26, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [29cc577c0c](https://linux-hardware.org/?probe=29cc577c0c) | Jun 26, 2023 |
| Lenovo        | 3102 NOK                    | Desktop     | [6277771b08](https://linux-hardware.org/?probe=6277771b08) | Jun 26, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [9af91d0ced](https://linux-hardware.org/?probe=9af91d0ced) | Jun 26, 2023 |
| ASRock        | H110M-HG4                   | Desktop     | [6aba51f328](https://linux-hardware.org/?probe=6aba51f328) | Jun 26, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [ee5172b420](https://linux-hardware.org/?probe=ee5172b420) | Jun 26, 2023 |
| Avell High... | A70 HYB                     | Notebook    | [3ccdaf3c82](https://linux-hardware.org/?probe=3ccdaf3c82) | Jun 26, 2023 |
| Intel         | H61                         | Desktop     | [8013deae02](https://linux-hardware.org/?probe=8013deae02) | Jun 25, 2023 |
| Intel         | H61                         | Desktop     | [8af1bf1ada](https://linux-hardware.org/?probe=8af1bf1ada) | Jun 25, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [9a87719748](https://linux-hardware.org/?probe=9a87719748) | Jun 25, 2023 |
| Intel         | B75                         | Desktop     | [2456289bbd](https://linux-hardware.org/?probe=2456289bbd) | Jun 25, 2023 |
| Biostar       | G31M+                       | Desktop     | [d8347c5f07](https://linux-hardware.org/?probe=d8347c5f07) | Jun 25, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [710bc10bf8](https://linux-hardware.org/?probe=710bc10bf8) | Jun 25, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [a9b805ab66](https://linux-hardware.org/?probe=a9b805ab66) | Jun 25, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [47a0ae93f4](https://linux-hardware.org/?probe=47a0ae93f4) | Jun 25, 2023 |
| Intel         | X99H                        | Desktop     | [60f1f4a8ba](https://linux-hardware.org/?probe=60f1f4a8ba) | Jun 25, 2023 |
| HP            | 3397                        | Desktop     | [8d9ed6d13e](https://linux-hardware.org/?probe=8d9ed6d13e) | Jun 25, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [9dce40179d](https://linux-hardware.org/?probe=9dce40179d) | Jun 25, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [bce89b670d](https://linux-hardware.org/?probe=bce89b670d) | Jun 25, 2023 |
| Sony          | VPCEA23FB                   | Notebook    | [b9a835920f](https://linux-hardware.org/?probe=b9a835920f) | Jun 25, 2023 |
| Sony          | VPCEA23FB                   | Notebook    | [c462c4c75e](https://linux-hardware.org/?probe=c462c4c75e) | Jun 25, 2023 |
| Intel         | H55                         | Desktop     | [993c041483](https://linux-hardware.org/?probe=993c041483) | Jun 25, 2023 |
| Dell          | Latitude E6430              | Notebook    | [be9b6c75da](https://linux-hardware.org/?probe=be9b6c75da) | Jun 25, 2023 |
| Toshiba       | PORTEGE R500                | Notebook    | [e327093da9](https://linux-hardware.org/?probe=e327093da9) | Jun 25, 2023 |
| Intel         | H61                         | Desktop     | [df8b50eae5](https://linux-hardware.org/?probe=df8b50eae5) | Jun 25, 2023 |
| Lenovo        | V15 G2 ITL 82ME             | Notebook    | [3fde30195c](https://linux-hardware.org/?probe=3fde30195c) | Jun 25, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [a87db20468](https://linux-hardware.org/?probe=a87db20468) | Jun 25, 2023 |
| Biostar       | TH55B HD                    | Desktop     | [5fbef8b11a](https://linux-hardware.org/?probe=5fbef8b11a) | Jun 25, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [be14b80f2c](https://linux-hardware.org/?probe=be14b80f2c) | Jun 24, 2023 |
| Lenovo        | ThinkPad T440p 20AWS2820... | Notebook    | [0ea92a193f](https://linux-hardware.org/?probe=0ea92a193f) | Jun 24, 2023 |
| Intel         | H61                         | Desktop     | [0f1d3e1299](https://linux-hardware.org/?probe=0f1d3e1299) | Jun 24, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [c8fc13e942](https://linux-hardware.org/?probe=c8fc13e942) | Jun 24, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [74b9f1b367](https://linux-hardware.org/?probe=74b9f1b367) | Jun 24, 2023 |
| Positivo      | POS-AG31AP                  | Desktop     | [bd3b3228c6](https://linux-hardware.org/?probe=bd3b3228c6) | Jun 24, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [cc2b3ff1ad](https://linux-hardware.org/?probe=cc2b3ff1ad) | Jun 24, 2023 |
| Intel         | D946GZIS AAD66165-301       | Desktop     | [dac65b1c2c](https://linux-hardware.org/?probe=dac65b1c2c) | Jun 24, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [09b5be9c77](https://linux-hardware.org/?probe=09b5be9c77) | Jun 24, 2023 |
| Dell          | G5 5590                     | Notebook    | [6d6974b0eb](https://linux-hardware.org/?probe=6d6974b0eb) | Jun 24, 2023 |
| PERTOSA       | GA-H110TN-M                 | Desktop     | [43b4160c55](https://linux-hardware.org/?probe=43b4160c55) | Jun 24, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | Desktop     | [e3d196b0b5](https://linux-hardware.org/?probe=e3d196b0b5) | Jun 24, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [53dbc2e799](https://linux-hardware.org/?probe=53dbc2e799) | Jun 24, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | Desktop     | [e5b4e8d2d4](https://linux-hardware.org/?probe=e5b4e8d2d4) | Jun 24, 2023 |
| Dell          | Inspiron 7460               | Notebook    | [dcfef21d2b](https://linux-hardware.org/?probe=dcfef21d2b) | Jun 24, 2023 |
| Dell          | Inspiron 7460               | Notebook    | [62d08bd4ca](https://linux-hardware.org/?probe=62d08bd4ca) | Jun 24, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [e0f5116d38](https://linux-hardware.org/?probe=e0f5116d38) | Jun 23, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [60034feb35](https://linux-hardware.org/?probe=60034feb35) | Jun 23, 2023 |
| Dell          | Latitude 3420               | Notebook    | [730bdb05fe](https://linux-hardware.org/?probe=730bdb05fe) | Jun 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [007cf1edce](https://linux-hardware.org/?probe=007cf1edce) | Jun 23, 2023 |
| HP            | 871A                        | Mini pc     | [d0f18a42a4](https://linux-hardware.org/?probe=d0f18a42a4) | Jun 23, 2023 |
| Acer          | Predator PH315-54           | Notebook    | [46d748a0a1](https://linux-hardware.org/?probe=46d748a0a1) | Jun 23, 2023 |
| HP            | 1495                        | Desktop     | [eab7d15f02](https://linux-hardware.org/?probe=eab7d15f02) | Jun 23, 2023 |
| Huanan        | X79 V6.11                   | Desktop     | [e94687bb6b](https://linux-hardware.org/?probe=e94687bb6b) | Jun 23, 2023 |
| Dell          | Inspiron 5406 2n1           | Convertible | [4430ccf679](https://linux-hardware.org/?probe=4430ccf679) | Jun 23, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [efb0264470](https://linux-hardware.org/?probe=efb0264470) | Jun 23, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [e8db86e014](https://linux-hardware.org/?probe=e8db86e014) | Jun 22, 2023 |
| Positivo B... | VJFE43F11X-XXXXXX           | Notebook    | [e03310c8e8](https://linux-hardware.org/?probe=e03310c8e8) | Jun 22, 2023 |
| Positivo      | POS-AG31AP                  | Desktop     | [1dd704fab9](https://linux-hardware.org/?probe=1dd704fab9) | Jun 22, 2023 |
| Samsung       | 750QFG                      | Convertible | [6e0e03a83e](https://linux-hardware.org/?probe=6e0e03a83e) | Jun 22, 2023 |
| ASUSTek       | X45U                        | Notebook    | [63a491a160](https://linux-hardware.org/?probe=63a491a160) | Jun 22, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [170d1f4f0b](https://linux-hardware.org/?probe=170d1f4f0b) | Jun 22, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [761a478742](https://linux-hardware.org/?probe=761a478742) | Jun 22, 2023 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [dda587b759](https://linux-hardware.org/?probe=dda587b759) | Jun 22, 2023 |
| Dell          | Inspiron 11-3168            | Notebook    | [8407c1d3cb](https://linux-hardware.org/?probe=8407c1d3cb) | Jun 22, 2023 |
| Samsung       | 550XDA                      | Notebook    | [f20386ccdd](https://linux-hardware.org/?probe=f20386ccdd) | Jun 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [42cb7025f1](https://linux-hardware.org/?probe=42cb7025f1) | Jun 22, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [0ef8557b4d](https://linux-hardware.org/?probe=0ef8557b4d) | Jun 22, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [d43ff293c1](https://linux-hardware.org/?probe=d43ff293c1) | Jun 22, 2023 |
| Positivo      | Mobile                      | Notebook    | [f9a55866f0](https://linux-hardware.org/?probe=f9a55866f0) | Jun 22, 2023 |
| Positivo      | Mobile                      | Notebook    | [25df2e5abc](https://linux-hardware.org/?probe=25df2e5abc) | Jun 22, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [7d52f04870](https://linux-hardware.org/?probe=7d52f04870) | Jun 22, 2023 |
| ASRock        | B365 Pro4                   | Desktop     | [46dc8e10a8](https://linux-hardware.org/?probe=46dc8e10a8) | Jun 21, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [1cdf3502e8](https://linux-hardware.org/?probe=1cdf3502e8) | Jun 21, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [7bbc89ec0f](https://linux-hardware.org/?probe=7bbc89ec0f) | Jun 21, 2023 |
| Dell          | Inspiron 5557               | Notebook    | [cc0794fa6e](https://linux-hardware.org/?probe=cc0794fa6e) | Jun 21, 2023 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | Desktop     | [446992e1b5](https://linux-hardware.org/?probe=446992e1b5) | Jun 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [817361caf5](https://linux-hardware.org/?probe=817361caf5) | Jun 21, 2023 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | Desktop     | [68ec70d3f8](https://linux-hardware.org/?probe=68ec70d3f8) | Jun 21, 2023 |
| Intel         | H55                         | Desktop     | [545c7e42b3](https://linux-hardware.org/?probe=545c7e42b3) | Jun 21, 2023 |
| Dell          | System Inspiron N4110       | Notebook    | [ebaceedccf](https://linux-hardware.org/?probe=ebaceedccf) | Jun 21, 2023 |
| Dell          | System Inspiron N4110       | Notebook    | [a168f45822](https://linux-hardware.org/?probe=a168f45822) | Jun 21, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [14296e98e7](https://linux-hardware.org/?probe=14296e98e7) | Jun 21, 2023 |
| Dell          | Vostro 5490                 | Notebook    | [10d1aeda8b](https://linux-hardware.org/?probe=10d1aeda8b) | Jun 21, 2023 |
| HP            | 339A                        | Desktop     | [60b0bff872](https://linux-hardware.org/?probe=60b0bff872) | Jun 21, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [e67932c5a0](https://linux-hardware.org/?probe=e67932c5a0) | Jun 21, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [6f0b6969bf](https://linux-hardware.org/?probe=6f0b6969bf) | Jun 20, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [ae2beb307a](https://linux-hardware.org/?probe=ae2beb307a) | Jun 20, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [c2c2365360](https://linux-hardware.org/?probe=c2c2365360) | Jun 20, 2023 |
| Positivo      | POS-ECIG41BSA               | Desktop     | [abaf6ee67e](https://linux-hardware.org/?probe=abaf6ee67e) | Jun 20, 2023 |
| Daten Tecn... | DCM4D-4 v4                  | Notebook    | [8a05558ee0](https://linux-hardware.org/?probe=8a05558ee0) | Jun 20, 2023 |
| Acer          | Nitro AN517-51              | Notebook    | [b4423e6ac2](https://linux-hardware.org/?probe=b4423e6ac2) | Jun 20, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | Notebook    | [c40e92156c](https://linux-hardware.org/?probe=c40e92156c) | Jun 20, 2023 |
| Acer          | TravelMate P449-G2-M        | Notebook    | [98626bde6c](https://linux-hardware.org/?probe=98626bde6c) | Jun 20, 2023 |
| Dell          | Latitude 3410               | Notebook    | [1e0348842a](https://linux-hardware.org/?probe=1e0348842a) | Jun 19, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | Desktop     | [689b10e4be](https://linux-hardware.org/?probe=689b10e4be) | Jun 19, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [fedcf5f651](https://linux-hardware.org/?probe=fedcf5f651) | Jun 19, 2023 |
| Sony          | VPCCA15FX                   | Notebook    | [ed7dba1a4c](https://linux-hardware.org/?probe=ed7dba1a4c) | Jun 19, 2023 |
| Sony          | VPCCA15FX                   | Notebook    | [c5660d0020](https://linux-hardware.org/?probe=c5660d0020) | Jun 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c0dc86bdc1](https://linux-hardware.org/?probe=c0dc86bdc1) | Jun 19, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [2192185525](https://linux-hardware.org/?probe=2192185525) | Jun 18, 2023 |
| Lenovo        | IdeaPad Flex14 SharkBay     | Notebook    | [e904a7b3ce](https://linux-hardware.org/?probe=e904a7b3ce) | Jun 18, 2023 |
| Lenovo        | IdeaPad Flex14 SharkBay     | Notebook    | [cb84a2778b](https://linux-hardware.org/?probe=cb84a2778b) | Jun 18, 2023 |
| PCWare        | IPMH61R3                    | Desktop     | [256988a55a](https://linux-hardware.org/?probe=256988a55a) | Jun 18, 2023 |
| Standard      | Unknown                     | Desktop     | [4956d7fc21](https://linux-hardware.org/?probe=4956d7fc21) | Jun 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [d237a2bfe6](https://linux-hardware.org/?probe=d237a2bfe6) | Jun 18, 2023 |
| Biostar       | A320MH                      | Desktop     | [0c38427f58](https://linux-hardware.org/?probe=0c38427f58) | Jun 18, 2023 |
| ZR            | A320M-F 1005                | Desktop     | [e3c749da2a](https://linux-hardware.org/?probe=e3c749da2a) | Jun 18, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [cf19f7a582](https://linux-hardware.org/?probe=cf19f7a582) | Jun 18, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [4bafdb9349](https://linux-hardware.org/?probe=4bafdb9349) | Jun 18, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [be5a148c53](https://linux-hardware.org/?probe=be5a148c53) | Jun 18, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [c0de332a8b](https://linux-hardware.org/?probe=c0de332a8b) | Jun 18, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [f431c0b66f](https://linux-hardware.org/?probe=f431c0b66f) | Jun 18, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [ca656065e5](https://linux-hardware.org/?probe=ca656065e5) | Jun 17, 2023 |
| PCWare        | IPX1800E1                   | Desktop     | [59b9fa6ff9](https://linux-hardware.org/?probe=59b9fa6ff9) | Jun 17, 2023 |
| Samsung       | 300E5K/300E5Q               | Notebook    | [a281272278](https://linux-hardware.org/?probe=a281272278) | Jun 17, 2023 |
| Avell High... | A70 HYB                     | Notebook    | [10eb079da8](https://linux-hardware.org/?probe=10eb079da8) | Jun 17, 2023 |
| Intel         | NUC13SBBi9 M58736-302       | Mini pc     | [66ef514141](https://linux-hardware.org/?probe=66ef514141) | Jun 17, 2023 |
| Sony          | SVF15213CBW                 | Notebook    | [4fcc62d3ac](https://linux-hardware.org/?probe=4fcc62d3ac) | Jun 17, 2023 |
| ZR            | A320M-F 1005                | Desktop     | [c190f4fcff](https://linux-hardware.org/?probe=c190f4fcff) | Jun 17, 2023 |
| Intel         | H55                         | Desktop     | [d47f462b1a](https://linux-hardware.org/?probe=d47f462b1a) | Jun 17, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | Desktop     | [b4cd8c843f](https://linux-hardware.org/?probe=b4cd8c843f) | Jun 17, 2023 |
| HP            | Pavilion dv7                | Notebook    | [f010c487a1](https://linux-hardware.org/?probe=f010c487a1) | Jun 17, 2023 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | Desktop     | [c99587d0e0](https://linux-hardware.org/?probe=c99587d0e0) | Jun 16, 2023 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [a587493314](https://linux-hardware.org/?probe=a587493314) | Jun 16, 2023 |
| Acer          | Nitro AN517-51              | Notebook    | [d2f2f70083](https://linux-hardware.org/?probe=d2f2f70083) | Jun 16, 2023 |
| IBM           | 69Y4438                     | Server      | [665f34b5bc](https://linux-hardware.org/?probe=665f34b5bc) | Jun 16, 2023 |
| Dell          | 09HY2Y A00                  | Server      | [812a113fa7](https://linux-hardware.org/?probe=812a113fa7) | Jun 16, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [8124f64b22](https://linux-hardware.org/?probe=8124f64b22) | Jun 16, 2023 |
| Dell          | 0XM089 A00                  | Server      | [c52b7c8444](https://linux-hardware.org/?probe=c52b7c8444) | Jun 16, 2023 |
| Intel         | H61                         | Desktop     | [ac7abe7025](https://linux-hardware.org/?probe=ac7abe7025) | Jun 16, 2023 |
| Intel         | H55                         | Desktop     | [76c89618f1](https://linux-hardware.org/?probe=76c89618f1) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [2a3068b835](https://linux-hardware.org/?probe=2a3068b835) | Jun 16, 2023 |
| HP            | 871A                        | Mini pc     | [2935dfbe9b](https://linux-hardware.org/?probe=2935dfbe9b) | Jun 16, 2023 |
| Intel         | B85                         | Desktop     | [1e688ea5e1](https://linux-hardware.org/?probe=1e688ea5e1) | Jun 16, 2023 |
| Positivo      | POS-EINM70CS POS            | Desktop     | [a2d50f27d7](https://linux-hardware.org/?probe=a2d50f27d7) | Jun 16, 2023 |
| Unknown       | Unknown                     | Notebook    | [f1294224ee](https://linux-hardware.org/?probe=f1294224ee) | Jun 15, 2023 |
| eMachines     | eMD728                      | Notebook    | [85dd880b0d](https://linux-hardware.org/?probe=85dd880b0d) | Jun 15, 2023 |
| Pegatron      | IPMIP-GS                    | Desktop     | [fb51893272](https://linux-hardware.org/?probe=fb51893272) | Jun 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [9b8a05d0f9](https://linux-hardware.org/?probe=9b8a05d0f9) | Jun 15, 2023 |
| ASUSTek       | PRIME H310M-E/BR            | Desktop     | [9c446242a8](https://linux-hardware.org/?probe=9c446242a8) | Jun 15, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | Desktop     | [ecc8c7d2d0](https://linux-hardware.org/?probe=ecc8c7d2d0) | Jun 15, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | Desktop     | [4cad282848](https://linux-hardware.org/?probe=4cad282848) | Jun 15, 2023 |
| Positivo      | POS-PIB150DT                | Desktop     | [cddf7d4ac9](https://linux-hardware.org/?probe=cddf7d4ac9) | Jun 15, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [a6f63a08e2](https://linux-hardware.org/?probe=a6f63a08e2) | Jun 15, 2023 |
| Apple         | MacBookAir4,1               | Notebook    | [e8575f0a34](https://linux-hardware.org/?probe=e8575f0a34) | Jun 15, 2023 |
| System76      | Gazelle                     | Notebook    | [79c4236cdd](https://linux-hardware.org/?probe=79c4236cdd) | Jun 15, 2023 |
| Positivo      | Q4128C-S                    | Notebook    | [1fab0b0752](https://linux-hardware.org/?probe=1fab0b0752) | Jun 15, 2023 |
| Dell          | Latitude 5480               | Notebook    | [677cb87f98](https://linux-hardware.org/?probe=677cb87f98) | Jun 14, 2023 |
| Unknown       | G41T-M7                     | Desktop     | [18a63d3a27](https://linux-hardware.org/?probe=18a63d3a27) | Jun 14, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [64da6bc381](https://linux-hardware.org/?probe=64da6bc381) | Jun 14, 2023 |
| Acer          | Aspire A315-54K             | Notebook    | [472d8bc7df](https://linux-hardware.org/?probe=472d8bc7df) | Jun 14, 2023 |
| Kllisre       | X99-B5 V1.1                 | Desktop     | [5e22a31b3e](https://linux-hardware.org/?probe=5e22a31b3e) | Jun 14, 2023 |
| Intel         | H61                         | Desktop     | [5d4fb99018](https://linux-hardware.org/?probe=5d4fb99018) | Jun 14, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [49e4d6ccb3](https://linux-hardware.org/?probe=49e4d6ccb3) | Jun 14, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0c3df957ce](https://linux-hardware.org/?probe=0c3df957ce) | Jun 14, 2023 |
| Samsung       | 670Z5E                      | Notebook    | [20f84530c7](https://linux-hardware.org/?probe=20f84530c7) | Jun 14, 2023 |
| Acer          | Aspire A315-23G             | Notebook    | [18a5adccb6](https://linux-hardware.org/?probe=18a5adccb6) | Jun 14, 2023 |
| Biostar       | B350GT3                     | Desktop     | [13b1026096](https://linux-hardware.org/?probe=13b1026096) | Jun 13, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [d0187875be](https://linux-hardware.org/?probe=d0187875be) | Jun 13, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [d7c90a9c25](https://linux-hardware.org/?probe=d7c90a9c25) | Jun 13, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [5223ed2efd](https://linux-hardware.org/?probe=5223ed2efd) | Jun 13, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [e25224b362](https://linux-hardware.org/?probe=e25224b362) | Jun 13, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [9fe9d9f03f](https://linux-hardware.org/?probe=9fe9d9f03f) | Jun 13, 2023 |
| HP            | 2AED                        | Desktop     | [2550c16272](https://linux-hardware.org/?probe=2550c16272) | Jun 13, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [1439681971](https://linux-hardware.org/?probe=1439681971) | Jun 13, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [3a8d104147](https://linux-hardware.org/?probe=3a8d104147) | Jun 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | Notebook    | [d2e4302f28](https://linux-hardware.org/?probe=d2e4302f28) | Jun 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | Notebook    | [e858489484](https://linux-hardware.org/?probe=e858489484) | Jun 13, 2023 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | Notebook    | [c765305160](https://linux-hardware.org/?probe=c765305160) | Jun 13, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [74b5d0e60a](https://linux-hardware.org/?probe=74b5d0e60a) | Jun 13, 2023 |
| Acer          | TravelMate P449-G2-M        | Notebook    | [97b6ba8bd6](https://linux-hardware.org/?probe=97b6ba8bd6) | Jun 13, 2023 |
| Dell          | Vostro 5470                 | Notebook    | [b5294ee338](https://linux-hardware.org/?probe=b5294ee338) | Jun 13, 2023 |
| ASUSTek       | X451MA                      | Notebook    | [bfa5493aa2](https://linux-hardware.org/?probe=bfa5493aa2) | Jun 12, 2023 |
| Positivo      | C14CR01                     | Notebook    | [11d46971fa](https://linux-hardware.org/?probe=11d46971fa) | Jun 12, 2023 |
| ASUSTek       | M5A78L-M LX3 PLUS           | Desktop     | [2b0095133a](https://linux-hardware.org/?probe=2b0095133a) | Jun 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a1cbc5571a](https://linux-hardware.org/?probe=a1cbc5571a) | Jun 12, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81G3      | Notebook    | [c09c4a0f69](https://linux-hardware.org/?probe=c09c4a0f69) | Jun 12, 2023 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [679fb4f6ab](https://linux-hardware.org/?probe=679fb4f6ab) | Jun 11, 2023 |
| Dell          | G3 3579                     | Notebook    | [c04bf46d3e](https://linux-hardware.org/?probe=c04bf46d3e) | Jun 11, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [9747487f82](https://linux-hardware.org/?probe=9747487f82) | Jun 11, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [5e3b6bfb4c](https://linux-hardware.org/?probe=5e3b6bfb4c) | Jun 11, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [613d703a17](https://linux-hardware.org/?probe=613d703a17) | Jun 10, 2023 |
| Dell          | Latitude 3420               | Notebook    | [07061e9d7d](https://linux-hardware.org/?probe=07061e9d7d) | Jun 10, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c610b3b9fe](https://linux-hardware.org/?probe=c610b3b9fe) | Jun 10, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [88d3849db5](https://linux-hardware.org/?probe=88d3849db5) | Jun 10, 2023 |
| Acer          | Aspire E5-574G              | Notebook    | [8ca78da386](https://linux-hardware.org/?probe=8ca78da386) | Jun 10, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [532d86f9e6](https://linux-hardware.org/?probe=532d86f9e6) | Jun 10, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [ba4527394e](https://linux-hardware.org/?probe=ba4527394e) | Jun 10, 2023 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [d8dac01c79](https://linux-hardware.org/?probe=d8dac01c79) | Jun 10, 2023 |
| Valve         | Jupiter                     | Notebook    | [c1e32f24ee](https://linux-hardware.org/?probe=c1e32f24ee) | Jun 10, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [b3531502a8](https://linux-hardware.org/?probe=b3531502a8) | Jun 10, 2023 |
| Intel         | H81                         | Desktop     | [6a51c76e81](https://linux-hardware.org/?probe=6a51c76e81) | Jun 09, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [0b0c11a052](https://linux-hardware.org/?probe=0b0c11a052) | Jun 09, 2023 |
| Dell          | Vostro 3460                 | Notebook    | [e8ed8e8b1e](https://linux-hardware.org/?probe=e8ed8e8b1e) | Jun 09, 2023 |
| Dell          | Vostro 1310                 | Notebook    | [05fc6f167c](https://linux-hardware.org/?probe=05fc6f167c) | Jun 09, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [c66d30943e](https://linux-hardware.org/?probe=c66d30943e) | Jun 09, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [1bae25f67b](https://linux-hardware.org/?probe=1bae25f67b) | Jun 09, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [bcad738da6](https://linux-hardware.org/?probe=bcad738da6) | Jun 09, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [28d0a897d3](https://linux-hardware.org/?probe=28d0a897d3) | Jun 09, 2023 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [c0fd33b9cc](https://linux-hardware.org/?probe=c0fd33b9cc) | Jun 09, 2023 |
| Dell          | Latitude E7240              | Notebook    | [1d8eb4fce4](https://linux-hardware.org/?probe=1d8eb4fce4) | Jun 09, 2023 |
| Dell          | Latitude E7240              | Notebook    | [da22551dca](https://linux-hardware.org/?probe=da22551dca) | Jun 09, 2023 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [76c3e6625b](https://linux-hardware.org/?probe=76c3e6625b) | Jun 09, 2023 |
| Unknown       | GSUO H61V10C                | Desktop     | [0daf816953](https://linux-hardware.org/?probe=0daf816953) | Jun 09, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [9e88454384](https://linux-hardware.org/?probe=9e88454384) | Jun 09, 2023 |
| Acer          | TravelMate P449-G2-M        | Notebook    | [6b42200bee](https://linux-hardware.org/?probe=6b42200bee) | Jun 09, 2023 |
| Acer          | TravelMate P449-G2-M        | Notebook    | [0fa009ad04](https://linux-hardware.org/?probe=0fa009ad04) | Jun 08, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [a8724dfd68](https://linux-hardware.org/?probe=a8724dfd68) | Jun 08, 2023 |
| Dell          | G15 5520                    | Notebook    | [2410d016d6](https://linux-hardware.org/?probe=2410d016d6) | Jun 08, 2023 |
| Multilaser    | UB820                       | All in one  | [7a1e5beb6e](https://linux-hardware.org/?probe=7a1e5beb6e) | Jun 08, 2023 |
| Dell          | G15 5520                    | Notebook    | [8d48df5869](https://linux-hardware.org/?probe=8d48df5869) | Jun 07, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [e7cdd7e89b](https://linux-hardware.org/?probe=e7cdd7e89b) | Jun 07, 2023 |
| Dell          | Inspiron 15 5510            | Notebook    | [98d7cb7ea7](https://linux-hardware.org/?probe=98d7cb7ea7) | Jun 07, 2023 |
| Toshiba       | Satellite C855-233          | Notebook    | [fb90f9aa02](https://linux-hardware.org/?probe=fb90f9aa02) | Jun 07, 2023 |
| TYAN Compu... | S7020                       | Server      | [6b39aa397f](https://linux-hardware.org/?probe=6b39aa397f) | Jun 07, 2023 |
| Dell          | Inspiron 5548               | Notebook    | [e67581e121](https://linux-hardware.org/?probe=e67581e121) | Jun 07, 2023 |
| Dell          | Vostro 15 3510              | Notebook    | [b661a14644](https://linux-hardware.org/?probe=b661a14644) | Jun 07, 2023 |
| Google        | Chell                       | Notebook    | [cace26f9f9](https://linux-hardware.org/?probe=cace26f9f9) | Jun 07, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [cc023db7a9](https://linux-hardware.org/?probe=cc023db7a9) | Jun 07, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [cbb39d8d29](https://linux-hardware.org/?probe=cbb39d8d29) | Jun 07, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [47fd407976](https://linux-hardware.org/?probe=47fd407976) | Jun 07, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [f7178495c7](https://linux-hardware.org/?probe=f7178495c7) | Jun 07, 2023 |
| DIEBOLD       | B85H3-M5                    | Desktop     | [7e56b1fd68](https://linux-hardware.org/?probe=7e56b1fd68) | Jun 07, 2023 |
| Positivo      | Mobile                      | Notebook    | [12d5c3248c](https://linux-hardware.org/?probe=12d5c3248c) | Jun 06, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [5d75bba35e](https://linux-hardware.org/?probe=5d75bba35e) | Jun 06, 2023 |
| ASRock        | H310M-HG4                   | Desktop     | [47b2817d31](https://linux-hardware.org/?probe=47b2817d31) | Jun 06, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [e066300eac](https://linux-hardware.org/?probe=e066300eac) | Jun 06, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [631e6bba84](https://linux-hardware.org/?probe=631e6bba84) | Jun 06, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [c685007aa8](https://linux-hardware.org/?probe=c685007aa8) | Jun 06, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [2f138401f6](https://linux-hardware.org/?probe=2f138401f6) | Jun 06, 2023 |
| HP            | Laptop 14s-dq1xxx           | Notebook    | [8f99826bf1](https://linux-hardware.org/?probe=8f99826bf1) | Jun 06, 2023 |
| Intel         | DP55WB AAE64798-204         | Desktop     | [fe09edbecc](https://linux-hardware.org/?probe=fe09edbecc) | Jun 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [e8df83921f](https://linux-hardware.org/?probe=e8df83921f) | Jun 06, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [0f91c977f0](https://linux-hardware.org/?probe=0f91c977f0) | Jun 06, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [44cf28ec0e](https://linux-hardware.org/?probe=44cf28ec0e) | Jun 05, 2023 |
| ASUSTek       | M5A88-M                     | Desktop     | [bb29b433c0](https://linux-hardware.org/?probe=bb29b433c0) | Jun 05, 2023 |
| Compaq        | CQ-27                       | Notebook    | [ae3d9bce8c](https://linux-hardware.org/?probe=ae3d9bce8c) | Jun 05, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [e9d79e576b](https://linux-hardware.org/?probe=e9d79e576b) | Jun 05, 2023 |
| ASUSTek       | VX7SX                       | Notebook    | [ddf3010e73](https://linux-hardware.org/?probe=ddf3010e73) | Jun 05, 2023 |
| Intel         | DP965LT AAD41694-301        | Desktop     | [f72bcbf0a2](https://linux-hardware.org/?probe=f72bcbf0a2) | Jun 05, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [da03bf4e08](https://linux-hardware.org/?probe=da03bf4e08) | Jun 05, 2023 |
| Biostar       | B350GT3                     | Desktop     | [b425f8d45a](https://linux-hardware.org/?probe=b425f8d45a) | Jun 05, 2023 |
| Samsung       | 950XEE                      | Notebook    | [cc47fd0df0](https://linux-hardware.org/?probe=cc47fd0df0) | Jun 05, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [ce1569ee48](https://linux-hardware.org/?probe=ce1569ee48) | Jun 05, 2023 |
| Acer          | Aspire A315-42G             | Notebook    | [eb67866c74](https://linux-hardware.org/?probe=eb67866c74) | Jun 05, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [8cbfe4cdf0](https://linux-hardware.org/?probe=8cbfe4cdf0) | Jun 05, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [3a0576b177](https://linux-hardware.org/?probe=3a0576b177) | Jun 05, 2023 |
| ASUSTek       | M5A88-M                     | Desktop     | [e750392f99](https://linux-hardware.org/?probe=e750392f99) | Jun 04, 2023 |
| Dell          | Latitude 3410               | Notebook    | [820e62c9d3](https://linux-hardware.org/?probe=820e62c9d3) | Jun 04, 2023 |
| Dell          | Latitude 3410               | Notebook    | [12515d41c8](https://linux-hardware.org/?probe=12515d41c8) | Jun 04, 2023 |
| Dell          | Inspiron N4030              | Notebook    | [4d82d8bf8b](https://linux-hardware.org/?probe=4d82d8bf8b) | Jun 04, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [b1b0369688](https://linux-hardware.org/?probe=b1b0369688) | Jun 04, 2023 |
| Dell          | 09D7F7 A00                  | Desktop     | [9b80703b01](https://linux-hardware.org/?probe=9b80703b01) | Jun 04, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [f71eae78c5](https://linux-hardware.org/?probe=f71eae78c5) | Jun 04, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [aafda7cf63](https://linux-hardware.org/?probe=aafda7cf63) | Jun 04, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [8690705151](https://linux-hardware.org/?probe=8690705151) | Jun 04, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [8b790b76a6](https://linux-hardware.org/?probe=8b790b76a6) | Jun 03, 2023 |
| Dell          | Inspiron 5437               | Notebook    | [d805b4ec1f](https://linux-hardware.org/?probe=d805b4ec1f) | Jun 03, 2023 |
| Biostar       | B450MX-S                    | Desktop     | [ccc6b5c4b5](https://linux-hardware.org/?probe=ccc6b5c4b5) | Jun 03, 2023 |
| Biostar       | B450MX-S                    | Desktop     | [6a01df1d69](https://linux-hardware.org/?probe=6a01df1d69) | Jun 03, 2023 |
| Compaq        | 420                         | Notebook    | [cf7a8f5641](https://linux-hardware.org/?probe=cf7a8f5641) | Jun 03, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [6ea1bc7e6a](https://linux-hardware.org/?probe=6ea1bc7e6a) | Jun 03, 2023 |
| Positivo      | POS-EINM70CS POS            | Desktop     | [80260b495c](https://linux-hardware.org/?probe=80260b495c) | Jun 03, 2023 |
| Positivo      | POS-PIG41BA                 | Desktop     | [f630c0b9cd](https://linux-hardware.org/?probe=f630c0b9cd) | Jun 03, 2023 |
| Intel         | B75                         | Desktop     | [2387f30645](https://linux-hardware.org/?probe=2387f30645) | Jun 03, 2023 |
| Positivo      | POS-RIB360EE 11144907       | Desktop     | [7837922f5b](https://linux-hardware.org/?probe=7837922f5b) | Jun 02, 2023 |
| Dell          | 0GX832 A01                  | Desktop     | [19b718a96c](https://linux-hardware.org/?probe=19b718a96c) | Jun 02, 2023 |
| Samsung       | 670Z5E                      | Notebook    | [647589cbbd](https://linux-hardware.org/?probe=647589cbbd) | Jun 02, 2023 |
| Dell          | Inspiron N4030              | Notebook    | [3c92b81349](https://linux-hardware.org/?probe=3c92b81349) | Jun 02, 2023 |
| Dell          | Inspiron N4030              | Notebook    | [1aca93ba38](https://linux-hardware.org/?probe=1aca93ba38) | Jun 02, 2023 |
| Unknown       | X99                         | Desktop     | [0ffca5934a](https://linux-hardware.org/?probe=0ffca5934a) | Jun 02, 2023 |
| Samsung       | 730QED                      | Convertible | [f447d7526c](https://linux-hardware.org/?probe=f447d7526c) | Jun 02, 2023 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [da5b2056e4](https://linux-hardware.org/?probe=da5b2056e4) | Jun 02, 2023 |
| Positivo      | POS-RIB360EE 11144907       | Desktop     | [b4ba7702cb](https://linux-hardware.org/?probe=b4ba7702cb) | Jun 02, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [664282cc84](https://linux-hardware.org/?probe=664282cc84) | Jun 02, 2023 |
| Samsung       | 730QED                      | Convertible | [ca8f4d1ff7](https://linux-hardware.org/?probe=ca8f4d1ff7) | Jun 02, 2023 |
| Dell          | G15 5520                    | Notebook    | [5880c98c54](https://linux-hardware.org/?probe=5880c98c54) | Jun 02, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [2dc3c08466](https://linux-hardware.org/?probe=2dc3c08466) | Jun 02, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [55c7d4b615](https://linux-hardware.org/?probe=55c7d4b615) | Jun 02, 2023 |
| HP            | 420                         | Notebook    | [0e369b273b](https://linux-hardware.org/?probe=0e369b273b) | Jun 02, 2023 |
| Positivo B... | VJFE43F11X-XXXXXX           | Notebook    | [ea337d3d2a](https://linux-hardware.org/?probe=ea337d3d2a) | Jun 02, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [5846820609](https://linux-hardware.org/?probe=5846820609) | Jun 02, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [cde4aaef3e](https://linux-hardware.org/?probe=cde4aaef3e) | Jun 01, 2023 |
| Portwell      | RuggedBookJ10               | Tablet      | [828336f149](https://linux-hardware.org/?probe=828336f149) | Jun 01, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | Desktop     | [7ac5ec7c05](https://linux-hardware.org/?probe=7ac5ec7c05) | Jun 01, 2023 |
| Lenovo        | G400s VILG1                 | Notebook    | [fee541ee18](https://linux-hardware.org/?probe=fee541ee18) | Jun 01, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | Notebook    | [33e440f44f](https://linux-hardware.org/?probe=33e440f44f) | Jun 01, 2023 |
| HP            | Pavilion dv6600             | Notebook    | [5e2867ee61](https://linux-hardware.org/?probe=5e2867ee61) | Jun 01, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [17621fb846](https://linux-hardware.org/?probe=17621fb846) | Jun 01, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [a4363d8242](https://linux-hardware.org/?probe=a4363d8242) | Jun 01, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [fd232702db](https://linux-hardware.org/?probe=fd232702db) | Jun 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [46f5148174](https://linux-hardware.org/?probe=46f5148174) | Jun 01, 2023 |
| Samsung       | 300E5K/300E5Q               | Notebook    | [00d2d07850](https://linux-hardware.org/?probe=00d2d07850) | May 31, 2023 |
| Unknown       | Unknown                     | Notebook    | [412c6d4af8](https://linux-hardware.org/?probe=412c6d4af8) | May 31, 2023 |
| HP            | Pavilion dv4                | Notebook    | [75797b5ec9](https://linux-hardware.org/?probe=75797b5ec9) | May 31, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [aad1baf686](https://linux-hardware.org/?probe=aad1baf686) | May 31, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [4fc174a983](https://linux-hardware.org/?probe=4fc174a983) | May 31, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [d950f8b732](https://linux-hardware.org/?probe=d950f8b732) | May 31, 2023 |
| Acer          | TravelMate P449-G2-M        | Notebook    | [41177ef027](https://linux-hardware.org/?probe=41177ef027) | May 31, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [dab4e98680](https://linux-hardware.org/?probe=dab4e98680) | May 31, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [1b457302ec](https://linux-hardware.org/?probe=1b457302ec) | May 31, 2023 |
| AZW           | GTR V02                     | Desktop     | [bd1740c7b2](https://linux-hardware.org/?probe=bd1740c7b2) | May 31, 2023 |
| AZW           | GTR V02                     | Desktop     | [cab90f1838](https://linux-hardware.org/?probe=cab90f1838) | May 31, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [8a18b7bada](https://linux-hardware.org/?probe=8a18b7bada) | May 31, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [611cf59f44](https://linux-hardware.org/?probe=611cf59f44) | May 31, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [1d0c56937c](https://linux-hardware.org/?probe=1d0c56937c) | May 31, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [d3ee3757e0](https://linux-hardware.org/?probe=d3ee3757e0) | May 30, 2023 |
| Notebook      | P15SM-A/SM1-A               | Notebook    | [e71d8e3bc0](https://linux-hardware.org/?probe=e71d8e3bc0) | May 30, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [e51e0ef0da](https://linux-hardware.org/?probe=e51e0ef0da) | May 30, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [ac2f40b972](https://linux-hardware.org/?probe=ac2f40b972) | May 30, 2023 |
| ASRock        | H310CM-HG4                  | Desktop     | [9fa8d9d320](https://linux-hardware.org/?probe=9fa8d9d320) | May 30, 2023 |
| Unknown       | Unknown                     | Notebook    | [9390923473](https://linux-hardware.org/?probe=9390923473) | May 30, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [f45bc9a282](https://linux-hardware.org/?probe=f45bc9a282) | May 30, 2023 |
| Lenovo        | 3098 SDK0E50510 WIN         | Desktop     | [2334995ee9](https://linux-hardware.org/?probe=2334995ee9) | May 30, 2023 |
| Samsung       | RV419/RV420                 | Notebook    | [ddab046bd5](https://linux-hardware.org/?probe=ddab046bd5) | May 30, 2023 |
| Dell          | 0GXM1W A02                  | Desktop     | [9c252c8688](https://linux-hardware.org/?probe=9c252c8688) | May 30, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [dd6ecadb7e](https://linux-hardware.org/?probe=dd6ecadb7e) | May 30, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c0ec67e3b1](https://linux-hardware.org/?probe=c0ec67e3b1) | May 30, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [29d2e377ad](https://linux-hardware.org/?probe=29d2e377ad) | May 29, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [e9f91331b2](https://linux-hardware.org/?probe=e9f91331b2) | May 29, 2023 |
| Itautec       | ST 4265                     | Desktop     | [8814373cb4](https://linux-hardware.org/?probe=8814373cb4) | May 29, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [e29eb3dfcc](https://linux-hardware.org/?probe=e29eb3dfcc) | May 29, 2023 |
| Avell High... | A70 MOB                     | Notebook    | [70e4c12911](https://linux-hardware.org/?probe=70e4c12911) | May 29, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [7adfc9796d](https://linux-hardware.org/?probe=7adfc9796d) | May 29, 2023 |
| Sony          | VPCSA25GB                   | Notebook    | [981a09e39a](https://linux-hardware.org/?probe=981a09e39a) | May 29, 2023 |
| Sony          | VPCSA25GB                   | Notebook    | [e36e944a92](https://linux-hardware.org/?probe=e36e944a92) | May 29, 2023 |
| Itautec       | ST 4265                     | Desktop     | [b89c45a31d](https://linux-hardware.org/?probe=b89c45a31d) | May 29, 2023 |
| Dell          | 0NM64V A01                  | Desktop     | [a109a924f0](https://linux-hardware.org/?probe=a109a924f0) | May 29, 2023 |
| Dell          | Inspiron 5447               | Notebook    | [270e3cd993](https://linux-hardware.org/?probe=270e3cd993) | May 29, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [54afc82ebc](https://linux-hardware.org/?probe=54afc82ebc) | May 29, 2023 |
| HP            | Pavilion g4                 | Notebook    | [12bef484db](https://linux-hardware.org/?probe=12bef484db) | May 29, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [f46b9b1b6a](https://linux-hardware.org/?probe=f46b9b1b6a) | May 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [14e5763b6f](https://linux-hardware.org/?probe=14e5763b6f) | May 29, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [4fc496bcc4](https://linux-hardware.org/?probe=4fc496bcc4) | May 29, 2023 |
| Acer          | Aspire VX5-591G             | Notebook    | [1db96272fe](https://linux-hardware.org/?probe=1db96272fe) | May 29, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [99540846c4](https://linux-hardware.org/?probe=99540846c4) | May 28, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [99c9a792f5](https://linux-hardware.org/?probe=99c9a792f5) | May 28, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [b8436530b0](https://linux-hardware.org/?probe=b8436530b0) | May 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [95793a85de](https://linux-hardware.org/?probe=95793a85de) | May 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [7c9addaf1c](https://linux-hardware.org/?probe=7c9addaf1c) | May 28, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [1b4eb11af8](https://linux-hardware.org/?probe=1b4eb11af8) | May 28, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [40ba623a3e](https://linux-hardware.org/?probe=40ba623a3e) | May 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [77e5b682ff](https://linux-hardware.org/?probe=77e5b682ff) | May 28, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [c78b5e28f1](https://linux-hardware.org/?probe=c78b5e28f1) | May 28, 2023 |
| Unknown       | Unknown                     | Notebook    | [9051961e40](https://linux-hardware.org/?probe=9051961e40) | May 28, 2023 |
| Positivo      | N1250                       | Notebook    | [f014b93eba](https://linux-hardware.org/?probe=f014b93eba) | May 28, 2023 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [c4ee84b38e](https://linux-hardware.org/?probe=c4ee84b38e) | May 28, 2023 |
| Dell          | Inspiron 5421               | Notebook    | [c559e851a2](https://linux-hardware.org/?probe=c559e851a2) | May 28, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [a81daffe89](https://linux-hardware.org/?probe=a81daffe89) | May 28, 2023 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [f90f831805](https://linux-hardware.org/?probe=f90f831805) | May 28, 2023 |
| Intel         | X99                         | Desktop     | [6826d78921](https://linux-hardware.org/?probe=6826d78921) | May 28, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [ef918dfbfa](https://linux-hardware.org/?probe=ef918dfbfa) | May 28, 2023 |
| Dell          | Vostro 5402                 | Notebook    | [41a9c1dcf2](https://linux-hardware.org/?probe=41a9c1dcf2) | May 28, 2023 |
| Intel         | X58M                        | Desktop     | [912addab98](https://linux-hardware.org/?probe=912addab98) | May 27, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [8310aaaa78](https://linux-hardware.org/?probe=8310aaaa78) | May 27, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [ad8e3ea3ea](https://linux-hardware.org/?probe=ad8e3ea3ea) | May 27, 2023 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [bc1c76bb8f](https://linux-hardware.org/?probe=bc1c76bb8f) | May 27, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [86545c89c0](https://linux-hardware.org/?probe=86545c89c0) | May 27, 2023 |
| Intel         | B75                         | Desktop     | [8dba7fa195](https://linux-hardware.org/?probe=8dba7fa195) | May 27, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [e429db5b0b](https://linux-hardware.org/?probe=e429db5b0b) | May 27, 2023 |
| Dell          | Latitude 7490               | Notebook    | [fbad4c1a53](https://linux-hardware.org/?probe=fbad4c1a53) | May 27, 2023 |
| Dell          | Latitude 7490               | Notebook    | [00c44ed00c](https://linux-hardware.org/?probe=00c44ed00c) | May 27, 2023 |
| Positivo      | C14CR21TV                   | Notebook    | [f3907d940d](https://linux-hardware.org/?probe=f3907d940d) | May 27, 2023 |
| HP            | 1000                        | Notebook    | [f3b014fa71](https://linux-hardware.org/?probe=f3b014fa71) | May 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [82cad47c63](https://linux-hardware.org/?probe=82cad47c63) | May 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [09cc59aa19](https://linux-hardware.org/?probe=09cc59aa19) | May 27, 2023 |
| HP            | Pavilion dm4                | Notebook    | [708daa02e2](https://linux-hardware.org/?probe=708daa02e2) | May 26, 2023 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [8b93a6ab33](https://linux-hardware.org/?probe=8b93a6ab33) | May 26, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [1cbedc352f](https://linux-hardware.org/?probe=1cbedc352f) | May 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [2b9c4431c2](https://linux-hardware.org/?probe=2b9c4431c2) | May 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [f5b571be32](https://linux-hardware.org/?probe=f5b571be32) | May 26, 2023 |
| Itautec       | Infoway                     | Notebook    | [03be6afc10](https://linux-hardware.org/?probe=03be6afc10) | May 26, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [0f79b43742](https://linux-hardware.org/?probe=0f79b43742) | May 26, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [4fedff68f1](https://linux-hardware.org/?probe=4fedff68f1) | May 26, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [40af2d79f9](https://linux-hardware.org/?probe=40af2d79f9) | May 26, 2023 |
| Samsung       | 550XDA                      | Notebook    | [6cc9f3cbe4](https://linux-hardware.org/?probe=6cc9f3cbe4) | May 26, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [248bd35ba0](https://linux-hardware.org/?probe=248bd35ba0) | May 26, 2023 |
| ASUSTek       | H110M-C/BR                  | Desktop     | [1c272c65dc](https://linux-hardware.org/?probe=1c272c65dc) | May 26, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [c897394a34](https://linux-hardware.org/?probe=c897394a34) | May 26, 2023 |
| Acer          | Predator PT316-51s          | Notebook    | [0242988287](https://linux-hardware.org/?probe=0242988287) | May 26, 2023 |
| Toshiba       | STI 005492G                 | Desktop     | [4f161f4ed0](https://linux-hardware.org/?probe=4f161f4ed0) | May 26, 2023 |
| LG Electro... | V720                        | All in one  | [5dbe7c937c](https://linux-hardware.org/?probe=5dbe7c937c) | May 26, 2023 |
| HP            | ProBook 645 G1              | Notebook    | [347779f3bf](https://linux-hardware.org/?probe=347779f3bf) | May 26, 2023 |
| A14CR         | Unknown                     | Notebook    | [a504061244](https://linux-hardware.org/?probe=a504061244) | May 25, 2023 |
| Clevo         | P150HMx                     | Notebook    | [d6c90a2c0c](https://linux-hardware.org/?probe=d6c90a2c0c) | May 25, 2023 |
| LG Electro... | 22V280 FAB1                 | All in one  | [0df1994f25](https://linux-hardware.org/?probe=0df1994f25) | May 25, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [a49bd1dd26](https://linux-hardware.org/?probe=a49bd1dd26) | May 25, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0ffdb62c45](https://linux-hardware.org/?probe=0ffdb62c45) | May 25, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [fcecd714d6](https://linux-hardware.org/?probe=fcecd714d6) | May 25, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | Notebook    | [3304e68c39](https://linux-hardware.org/?probe=3304e68c39) | May 25, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [2a3382aa0c](https://linux-hardware.org/?probe=2a3382aa0c) | May 25, 2023 |
| PCWare        | IPMH110G                    | Desktop     | [33b6fce5ff](https://linux-hardware.org/?probe=33b6fce5ff) | May 25, 2023 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [c885a13922](https://linux-hardware.org/?probe=c885a13922) | May 25, 2023 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [897b688aba](https://linux-hardware.org/?probe=897b688aba) | May 25, 2023 |
| Biostar       | A68MHE                      | Desktop     | [d1ef52da36](https://linux-hardware.org/?probe=d1ef52da36) | May 25, 2023 |
| PHILCO ELE... | PNB15.6AP34H1W10            | Notebook    | [dc91cb92af](https://linux-hardware.org/?probe=dc91cb92af) | May 25, 2023 |
| LG Electro... | V720                        | All in one  | [686e013b62](https://linux-hardware.org/?probe=686e013b62) | May 25, 2023 |
| ASUSTek       | PRIME B760M-A D4            | Desktop     | [95321eedeb](https://linux-hardware.org/?probe=95321eedeb) | May 25, 2023 |
| Biostar       | A68MHE                      | Desktop     | [e2244a8ed0](https://linux-hardware.org/?probe=e2244a8ed0) | May 25, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [2c31d88fa2](https://linux-hardware.org/?probe=2c31d88fa2) | May 25, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [efb5aa9bfc](https://linux-hardware.org/?probe=efb5aa9bfc) | May 24, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [1247209c34](https://linux-hardware.org/?probe=1247209c34) | May 24, 2023 |
| Biostar       | N61PB-M2S                   | Desktop     | [e4669affdb](https://linux-hardware.org/?probe=e4669affdb) | May 24, 2023 |
| AZW           | SEi                         | Desktop     | [bc0c7a512f](https://linux-hardware.org/?probe=bc0c7a512f) | May 24, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [bce76b90ef](https://linux-hardware.org/?probe=bce76b90ef) | May 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [86666c3371](https://linux-hardware.org/?probe=86666c3371) | May 24, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [44861be08c](https://linux-hardware.org/?probe=44861be08c) | May 24, 2023 |
| Avell High... | A72 HYB                     | Notebook    | [c6f131b8b1](https://linux-hardware.org/?probe=c6f131b8b1) | May 24, 2023 |
| Avell High... | A72 HYB                     | Notebook    | [d54fb61d87](https://linux-hardware.org/?probe=d54fb61d87) | May 24, 2023 |
| AZW           | SEi                         | Desktop     | [825fbaebcd](https://linux-hardware.org/?probe=825fbaebcd) | May 23, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [255811069a](https://linux-hardware.org/?probe=255811069a) | May 23, 2023 |
| ASUSTek       | B85M-E/BR                   | Desktop     | [ed20b84824](https://linux-hardware.org/?probe=ed20b84824) | May 23, 2023 |
| Intel         | H61                         | Desktop     | [794ecc6c43](https://linux-hardware.org/?probe=794ecc6c43) | May 23, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [7f5d36cc34](https://linux-hardware.org/?probe=7f5d36cc34) | May 23, 2023 |
| Dell          | Vostro 5402                 | Notebook    | [e6834866ba](https://linux-hardware.org/?probe=e6834866ba) | May 23, 2023 |
| Dell          | 0H19HD A06                  | Server      | [25975db1c4](https://linux-hardware.org/?probe=25975db1c4) | May 23, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [9063693561](https://linux-hardware.org/?probe=9063693561) | May 23, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [a92437f5aa](https://linux-hardware.org/?probe=a92437f5aa) | May 23, 2023 |
| Gigabyte      | A320M-S2H-CF SE1            | Desktop     | [61ede8f95d](https://linux-hardware.org/?probe=61ede8f95d) | May 23, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [724db856f3](https://linux-hardware.org/?probe=724db856f3) | May 23, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [db6ba1c42e](https://linux-hardware.org/?probe=db6ba1c42e) | May 23, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [1ff1bde0f0](https://linux-hardware.org/?probe=1ff1bde0f0) | May 23, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [2afda2396c](https://linux-hardware.org/?probe=2afda2396c) | May 22, 2023 |
| Intel         | DP55WB AAE64798-205         | Desktop     | [91bb4c8e5d](https://linux-hardware.org/?probe=91bb4c8e5d) | May 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [84717aefdf](https://linux-hardware.org/?probe=84717aefdf) | May 22, 2023 |
| Acer          | Swift SF514-56T             | Notebook    | [81a0e002b7](https://linux-hardware.org/?probe=81a0e002b7) | May 22, 2023 |
| Dell          | Inspiron 3443               | Notebook    | [35923f74b5](https://linux-hardware.org/?probe=35923f74b5) | May 22, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [2f1b921a18](https://linux-hardware.org/?probe=2f1b921a18) | May 22, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [eeca18ff12](https://linux-hardware.org/?probe=eeca18ff12) | May 22, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [17d027794e](https://linux-hardware.org/?probe=17d027794e) | May 22, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [ebd65238d8](https://linux-hardware.org/?probe=ebd65238d8) | May 22, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [98473b6b1e](https://linux-hardware.org/?probe=98473b6b1e) | May 22, 2023 |
| Philco        | 14H                         | Notebook    | [5dbb0cb3b7](https://linux-hardware.org/?probe=5dbb0cb3b7) | May 21, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [19be933f8a](https://linux-hardware.org/?probe=19be933f8a) | May 21, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [7ff619a028](https://linux-hardware.org/?probe=7ff619a028) | May 21, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [f20160cf5b](https://linux-hardware.org/?probe=f20160cf5b) | May 21, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [1b8a739f9a](https://linux-hardware.org/?probe=1b8a739f9a) | May 21, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | Desktop     | [2a95b22ac3](https://linux-hardware.org/?probe=2a95b22ac3) | May 21, 2023 |
| ASRock        | H310CM-HG4                  | Desktop     | [6f698f47d8](https://linux-hardware.org/?probe=6f698f47d8) | May 21, 2023 |
| Unknown       | GSUO H61V10C                | Desktop     | [8e1037e4c1](https://linux-hardware.org/?probe=8e1037e4c1) | May 20, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [4c5dce3a01](https://linux-hardware.org/?probe=4c5dce3a01) | May 20, 2023 |
| ASRock        | 970A-G                      | Desktop     | [fd39b2185b](https://linux-hardware.org/?probe=fd39b2185b) | May 20, 2023 |
| Gigabyte      | B660M AORUS PRO DDR4        | Desktop     | [6a3afbb593](https://linux-hardware.org/?probe=6a3afbb593) | May 20, 2023 |
| Dell          | 0VTJVC A00                  | Desktop     | [1acd938f30](https://linux-hardware.org/?probe=1acd938f30) | May 20, 2023 |
| ASRock        | 970A-G                      | Desktop     | [fac3e3c961](https://linux-hardware.org/?probe=fac3e3c961) | May 20, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [105fb43fc1](https://linux-hardware.org/?probe=105fb43fc1) | May 20, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [42ab4c7e67](https://linux-hardware.org/?probe=42ab4c7e67) | May 20, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [1a05e80ee5](https://linux-hardware.org/?probe=1a05e80ee5) | May 20, 2023 |
| MSI           | X99S SLI PLUS               | Desktop     | [35b5231ed2](https://linux-hardware.org/?probe=35b5231ed2) | May 20, 2023 |
| Daten Tecn... | DA320MXV DC                 | Desktop     | [0b7e1e51b9](https://linux-hardware.org/?probe=0b7e1e51b9) | May 20, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [4f27fb9c64](https://linux-hardware.org/?probe=4f27fb9c64) | May 20, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [2cde0cc93d](https://linux-hardware.org/?probe=2cde0cc93d) | May 19, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [986792e4f0](https://linux-hardware.org/?probe=986792e4f0) | May 19, 2023 |
| Acer          | Aspire A315-42G             | Notebook    | [1125a4111e](https://linux-hardware.org/?probe=1125a4111e) | May 19, 2023 |
| ASRock        | Z590M Pro4                  | Desktop     | [d039ed90c5](https://linux-hardware.org/?probe=d039ed90c5) | May 19, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [a8bb37c78e](https://linux-hardware.org/?probe=a8bb37c78e) | May 19, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [39725fefa4](https://linux-hardware.org/?probe=39725fefa4) | May 19, 2023 |
| Avell High... | A40 LIV                     | Notebook    | [d1e00e62c4](https://linux-hardware.org/?probe=d1e00e62c4) | May 19, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [9475bc847b](https://linux-hardware.org/?probe=9475bc847b) | May 19, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [14985fd04f](https://linux-hardware.org/?probe=14985fd04f) | May 18, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [6b5bc55aeb](https://linux-hardware.org/?probe=6b5bc55aeb) | May 18, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [e26f4ecf2f](https://linux-hardware.org/?probe=e26f4ecf2f) | May 18, 2023 |
| Lenovo        | ThinkPad T400 2767E53       | Notebook    | [5cd6c87b7e](https://linux-hardware.org/?probe=5cd6c87b7e) | May 18, 2023 |
| Dell          | Vostro 15 3510              | Notebook    | [e5e7213107](https://linux-hardware.org/?probe=e5e7213107) | May 18, 2023 |
| Megaware      | MW-H61M-2H v1.3 - 17/07/... | Desktop     | [72303201a3](https://linux-hardware.org/?probe=72303201a3) | May 18, 2023 |
| Lenovo        | ThinkPad T490s 20NXS01Y0... | Notebook    | [277ed003ce](https://linux-hardware.org/?probe=277ed003ce) | May 18, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [1edee9f902](https://linux-hardware.org/?probe=1edee9f902) | May 18, 2023 |
| Lenovo        | ThinkPad T480s 20L8S8EG0... | Notebook    | [0735cab104](https://linux-hardware.org/?probe=0735cab104) | May 18, 2023 |
| PCWare        | IPX1800E2                   | Desktop     | [f19d94af88](https://linux-hardware.org/?probe=f19d94af88) | May 18, 2023 |
| PCWare        | IPX1800E2                   | Desktop     | [a75df73ade](https://linux-hardware.org/?probe=a75df73ade) | May 18, 2023 |
| Clevo         | P150HMx                     | Notebook    | [17e11751ef](https://linux-hardware.org/?probe=17e11751ef) | May 18, 2023 |
| Clevo         | P150HMx                     | Notebook    | [f749300168](https://linux-hardware.org/?probe=f749300168) | May 18, 2023 |
| Lenovo        | IdeaPad Z470                | Notebook    | [158feeb98d](https://linux-hardware.org/?probe=158feeb98d) | May 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [be46da6480](https://linux-hardware.org/?probe=be46da6480) | May 18, 2023 |
| Lenovo        | ThinkPad Edge E430 3254T... | Notebook    | [681fd36c12](https://linux-hardware.org/?probe=681fd36c12) | May 18, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [255961cb74](https://linux-hardware.org/?probe=255961cb74) | May 18, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [a167afa608](https://linux-hardware.org/?probe=a167afa608) | May 17, 2023 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [0982e8a637](https://linux-hardware.org/?probe=0982e8a637) | May 17, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [9372615767](https://linux-hardware.org/?probe=9372615767) | May 17, 2023 |
| Dell          | Latitude E7240              | Notebook    | [1990186432](https://linux-hardware.org/?probe=1990186432) | May 17, 2023 |
| ASUSTek       | P7H55D-M PRO                | Desktop     | [2c423cf3e9](https://linux-hardware.org/?probe=2c423cf3e9) | May 17, 2023 |
| Dell          | Inspiron 15-7568            | Notebook    | [77675ecccd](https://linux-hardware.org/?probe=77675ecccd) | May 17, 2023 |
| Pegatron      | Yangtze                     | Desktop     | [4e3ce38e7b](https://linux-hardware.org/?probe=4e3ce38e7b) | May 17, 2023 |
| ASUSTek       | P7H55D-M PRO                | Desktop     | [dc1bf86813](https://linux-hardware.org/?probe=dc1bf86813) | May 17, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [dc2f3b9cdc](https://linux-hardware.org/?probe=dc2f3b9cdc) | May 17, 2023 |
| Acer          | Spin SP315-51               | Convertible | [e4b64c42b7](https://linux-hardware.org/?probe=e4b64c42b7) | May 16, 2023 |
| Intel         | DG41WV AAE90316-101         | Desktop     | [9bef3b952d](https://linux-hardware.org/?probe=9bef3b952d) | May 16, 2023 |
| Positivo      | W2150G                      | All in one  | [abe3331aac](https://linux-hardware.org/?probe=abe3331aac) | May 16, 2023 |
| Dell          | Latitude 5420               | Notebook    | [ddd072b69c](https://linux-hardware.org/?probe=ddd072b69c) | May 16, 2023 |
| Acer          | Aspire 5050                 | Notebook    | [44f9abca04](https://linux-hardware.org/?probe=44f9abca04) | May 16, 2023 |
| Dell          | Latitude 7420               | Notebook    | [4e1680877b](https://linux-hardware.org/?probe=4e1680877b) | May 16, 2023 |
| Samsung       | 550XDA                      | Notebook    | [75bc1cdfb3](https://linux-hardware.org/?probe=75bc1cdfb3) | May 16, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [6094f7a191](https://linux-hardware.org/?probe=6094f7a191) | May 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [055aae99b8](https://linux-hardware.org/?probe=055aae99b8) | May 16, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [9dd2c4cbee](https://linux-hardware.org/?probe=9dd2c4cbee) | May 16, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [dfc49eb820](https://linux-hardware.org/?probe=dfc49eb820) | May 16, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [df01be5efd](https://linux-hardware.org/?probe=df01be5efd) | May 16, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [3f5bade9b8](https://linux-hardware.org/?probe=3f5bade9b8) | May 16, 2023 |
| Intel         | H61                         | Desktop     | [c54c89a4b1](https://linux-hardware.org/?probe=c54c89a4b1) | May 16, 2023 |
| PHILCO ELE... | PNB15.6AP34H1W10            | Notebook    | [4c4c7467ec](https://linux-hardware.org/?probe=4c4c7467ec) | May 16, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [377fe6aa67](https://linux-hardware.org/?probe=377fe6aa67) | May 16, 2023 |
| Positivo      | Q4128C-S                    | Notebook    | [05c0522fe3](https://linux-hardware.org/?probe=05c0522fe3) | May 16, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [fe4f47ccc9](https://linux-hardware.org/?probe=fe4f47ccc9) | May 15, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [b25434cdf3](https://linux-hardware.org/?probe=b25434cdf3) | May 15, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [a6ffd0df31](https://linux-hardware.org/?probe=a6ffd0df31) | May 15, 2023 |
| Dell          | G3 3590                     | Notebook    | [75a6a8a107](https://linux-hardware.org/?probe=75a6a8a107) | May 15, 2023 |
| ASUSTek       | Z97M-PLUS/BR                | Desktop     | [dc06cb0aba](https://linux-hardware.org/?probe=dc06cb0aba) | May 15, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [2375fac142](https://linux-hardware.org/?probe=2375fac142) | May 15, 2023 |
| Gigabyte      | Z170X-UD5-CF                | Desktop     | [429dc207a6](https://linux-hardware.org/?probe=429dc207a6) | May 15, 2023 |
| Dell          | G3 3590                     | Notebook    | [b19462038d](https://linux-hardware.org/?probe=b19462038d) | May 15, 2023 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | Notebook    | [f199f11aa5](https://linux-hardware.org/?probe=f199f11aa5) | May 15, 2023 |
| Acer          | AO532h                      | Notebook    | [6cfe2a58cc](https://linux-hardware.org/?probe=6cfe2a58cc) | May 15, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [98f448ed70](https://linux-hardware.org/?probe=98f448ed70) | May 15, 2023 |
| Gigabyte      | Z170X-UD5-CF                | Desktop     | [f887e6f037](https://linux-hardware.org/?probe=f887e6f037) | May 15, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [5dadcb24d0](https://linux-hardware.org/?probe=5dadcb24d0) | May 15, 2023 |
| Dell          | 024JD7 A00                  | Desktop     | [904e4e2a0d](https://linux-hardware.org/?probe=904e4e2a0d) | May 15, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [3e839501e9](https://linux-hardware.org/?probe=3e839501e9) | May 15, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [58f493d242](https://linux-hardware.org/?probe=58f493d242) | May 15, 2023 |
| Valve         | Jupiter                     | Notebook    | [dca8b16469](https://linux-hardware.org/?probe=dca8b16469) | May 15, 2023 |
| ASUSTek       | K45VM                       | Notebook    | [eaef457c8a](https://linux-hardware.org/?probe=eaef457c8a) | May 15, 2023 |
| Dell          | G15 5510                    | Notebook    | [5624d414be](https://linux-hardware.org/?probe=5624d414be) | May 15, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [7feff56d1d](https://linux-hardware.org/?probe=7feff56d1d) | May 15, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [3d3bfc28a6](https://linux-hardware.org/?probe=3d3bfc28a6) | May 14, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [7fe35591e7](https://linux-hardware.org/?probe=7fe35591e7) | May 14, 2023 |
| Lenovo        | ThinkPad T420 4236PJ2       | Notebook    | [22a9e8213e](https://linux-hardware.org/?probe=22a9e8213e) | May 14, 2023 |
| Intel         | W7650                       | Notebook    | [a672f7199c](https://linux-hardware.org/?probe=a672f7199c) | May 14, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [41c5120619](https://linux-hardware.org/?probe=41c5120619) | May 14, 2023 |
| Dell          | Vostro 5471                 | Notebook    | [745ae69749](https://linux-hardware.org/?probe=745ae69749) | May 14, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [821d79dc3f](https://linux-hardware.org/?probe=821d79dc3f) | May 14, 2023 |
| Dell          | System Inspiron N4120       | Notebook    | [c7f1c9e542](https://linux-hardware.org/?probe=c7f1c9e542) | May 14, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [e887133fce](https://linux-hardware.org/?probe=e887133fce) | May 14, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [64237b5d6e](https://linux-hardware.org/?probe=64237b5d6e) | May 14, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [38b6dd7b3f](https://linux-hardware.org/?probe=38b6dd7b3f) | May 14, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [65374a707a](https://linux-hardware.org/?probe=65374a707a) | May 14, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [4e208c9155](https://linux-hardware.org/?probe=4e208c9155) | May 14, 2023 |
| Intel         | X79F1 V2.0                  | Desktop     | [a2446b63b3](https://linux-hardware.org/?probe=a2446b63b3) | May 14, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [f5cbf650c3](https://linux-hardware.org/?probe=f5cbf650c3) | May 14, 2023 |
| Lenovo        | Legion Y540-15IRH 81RJ      | Notebook    | [9eb38c956d](https://linux-hardware.org/?probe=9eb38c956d) | May 14, 2023 |
| Daten Tecn... | DH110MXV                    | Desktop     | [4fd655c0aa](https://linux-hardware.org/?probe=4fd655c0aa) | May 13, 2023 |
| HP            | Compaq Presario CQ40        | Notebook    | [22d379cd2f](https://linux-hardware.org/?probe=22d379cd2f) | May 13, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [2c03c64f49](https://linux-hardware.org/?probe=2c03c64f49) | May 13, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [e5dbe4c6f4](https://linux-hardware.org/?probe=e5dbe4c6f4) | May 13, 2023 |
| Samsung       | 730QED                      | Convertible | [d1dc669b1f](https://linux-hardware.org/?probe=d1dc669b1f) | May 13, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [036fd352bf](https://linux-hardware.org/?probe=036fd352bf) | May 13, 2023 |
| Intel         | B75                         | Desktop     | [da0a89cf17](https://linux-hardware.org/?probe=da0a89cf17) | May 13, 2023 |
| Samsung       | 550XDA                      | Notebook    | [5f562807be](https://linux-hardware.org/?probe=5f562807be) | May 13, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [b15a6ee63f](https://linux-hardware.org/?probe=b15a6ee63f) | May 13, 2023 |
| Toshiba       | STI 007567                  | Desktop     | [579ec5bb2b](https://linux-hardware.org/?probe=579ec5bb2b) | May 13, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [b14b7c3725](https://linux-hardware.org/?probe=b14b7c3725) | May 13, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [9759b380bb](https://linux-hardware.org/?probe=9759b380bb) | May 13, 2023 |
| Dell          | Inspiron 7580               | Notebook    | [01d9730a88](https://linux-hardware.org/?probe=01d9730a88) | May 12, 2023 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [3a0e10e849](https://linux-hardware.org/?probe=3a0e10e849) | May 12, 2023 |
| Toshiba       | STI NA 1401                 | Notebook    | [c9aa3a7539](https://linux-hardware.org/?probe=c9aa3a7539) | May 12, 2023 |
| Huanan        | B75 V10.1 376               | Desktop     | [3293d10187](https://linux-hardware.org/?probe=3293d10187) | May 12, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [ee8fe21e76](https://linux-hardware.org/?probe=ee8fe21e76) | May 12, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [c686c521dd](https://linux-hardware.org/?probe=c686c521dd) | May 12, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [7b966568cc](https://linux-hardware.org/?probe=7b966568cc) | May 12, 2023 |
| Dell          | Inspiron 15-7568            | Notebook    | [bb8fe2215b](https://linux-hardware.org/?probe=bb8fe2215b) | May 12, 2023 |
| Positivo      | J14GL11                     | Notebook    | [bfdf0df9b8](https://linux-hardware.org/?probe=bfdf0df9b8) | May 12, 2023 |
| Multilaser    | PC150                       | Notebook    | [0a59946a8f](https://linux-hardware.org/?probe=0a59946a8f) | May 12, 2023 |
| Biostar       | A320MH                      | Desktop     | [d30baf9379](https://linux-hardware.org/?probe=d30baf9379) | May 12, 2023 |
| MSI           | H61M-P20/W8                 | Desktop     | [b727300be6](https://linux-hardware.org/?probe=b727300be6) | May 11, 2023 |
| Huanan        | B75 V10.1 376               | Desktop     | [3c8b5aefd8](https://linux-hardware.org/?probe=3c8b5aefd8) | May 11, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [db910d4ee1](https://linux-hardware.org/?probe=db910d4ee1) | May 11, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [dbf711a2f5](https://linux-hardware.org/?probe=dbf711a2f5) | May 11, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS II    | Desktop     | [3cccf183d9](https://linux-hardware.org/?probe=3cccf183d9) | May 11, 2023 |
| Apple         | Mac-F2218EC8                | All in one  | [6cab4970b0](https://linux-hardware.org/?probe=6cab4970b0) | May 11, 2023 |
| Positivo      | J14GL11                     | Notebook    | [9594837399](https://linux-hardware.org/?probe=9594837399) | May 11, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [1b0cd4f3e1](https://linux-hardware.org/?probe=1b0cd4f3e1) | May 11, 2023 |
| Itautec       | Infoway w7440               | Notebook    | [41eee30825](https://linux-hardware.org/?probe=41eee30825) | May 11, 2023 |
| Alienware     | m15 R6                      | Notebook    | [bfa28cc7bd](https://linux-hardware.org/?probe=bfa28cc7bd) | May 11, 2023 |
| Dell          | 076VHM A02                  | Desktop     | [7f1984ec16](https://linux-hardware.org/?probe=7f1984ec16) | May 10, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [e9e13fa531](https://linux-hardware.org/?probe=e9e13fa531) | May 10, 2023 |
| Alienware     | m15 R7                      | Notebook    | [d481f5a70d](https://linux-hardware.org/?probe=d481f5a70d) | May 10, 2023 |
| ASRock        | H110M-HG4                   | Desktop     | [7995d3740a](https://linux-hardware.org/?probe=7995d3740a) | May 10, 2023 |
| Dell          | Inspiron 5590               | Notebook    | [117a2b318d](https://linux-hardware.org/?probe=117a2b318d) | May 10, 2023 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [cb4250603d](https://linux-hardware.org/?probe=cb4250603d) | May 10, 2023 |
| ASRock        | H110M-HG4                   | Desktop     | [2864ff8227](https://linux-hardware.org/?probe=2864ff8227) | May 10, 2023 |
| HP            | 0A60h                       | Desktop     | [972820a864](https://linux-hardware.org/?probe=972820a864) | May 10, 2023 |
| ASRock        | N68-S3 FX                   | Desktop     | [0ed94fe810](https://linux-hardware.org/?probe=0ed94fe810) | May 10, 2023 |
| Dell          | Inspiron 5590               | Notebook    | [9c53d54cae](https://linux-hardware.org/?probe=9c53d54cae) | May 10, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [6ddb2fa975](https://linux-hardware.org/?probe=6ddb2fa975) | May 10, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [16bdfe6490](https://linux-hardware.org/?probe=16bdfe6490) | May 10, 2023 |
| Positivo      | Q432BP                      | Convertible | [dbf8652c6c](https://linux-hardware.org/?probe=dbf8652c6c) | May 10, 2023 |
| HP            | ENVY 15                     | Notebook    | [ba0636efe5](https://linux-hardware.org/?probe=ba0636efe5) | May 10, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [e1e22ae448](https://linux-hardware.org/?probe=e1e22ae448) | May 10, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [18afa7a07b](https://linux-hardware.org/?probe=18afa7a07b) | May 10, 2023 |
| Dell          | Inspiron 15 5510            | Notebook    | [174505e46f](https://linux-hardware.org/?probe=174505e46f) | May 10, 2023 |
| Apple         | Mac-F2218EC8                | All in one  | [a4a673b42a](https://linux-hardware.org/?probe=a4a673b42a) | May 09, 2023 |
| Dell          | 0VXN67 A01                  | Desktop     | [0985b52dee](https://linux-hardware.org/?probe=0985b52dee) | May 09, 2023 |
| Dell          | 0VXN67 A01                  | Desktop     | [b7fd2a3e2f](https://linux-hardware.org/?probe=b7fd2a3e2f) | May 09, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [af88b26379](https://linux-hardware.org/?probe=af88b26379) | May 09, 2023 |
| Alienware     | m15 R7                      | Notebook    | [cfd5f51d93](https://linux-hardware.org/?probe=cfd5f51d93) | May 09, 2023 |
| Unknown       | Unknown                     | Phone       | [993a299610](https://linux-hardware.org/?probe=993a299610) | May 09, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [922a0d7b9e](https://linux-hardware.org/?probe=922a0d7b9e) | May 09, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [4df8233d54](https://linux-hardware.org/?probe=4df8233d54) | May 09, 2023 |
| Avell High... | A40 LIV                     | Notebook    | [c4c4a1fe74](https://linux-hardware.org/?probe=c4c4a1fe74) | May 09, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [d9681f2d77](https://linux-hardware.org/?probe=d9681f2d77) | May 09, 2023 |
| Acer          | Aspire A514-54              | Notebook    | [dafa2886a3](https://linux-hardware.org/?probe=dafa2886a3) | May 09, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [e858474ff0](https://linux-hardware.org/?probe=e858474ff0) | May 09, 2023 |
| ASRock        | H310CM-HG4                  | Desktop     | [756ed502db](https://linux-hardware.org/?probe=756ed502db) | May 09, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [205b8a8ca7](https://linux-hardware.org/?probe=205b8a8ca7) | May 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [e0fc6f7617](https://linux-hardware.org/?probe=e0fc6f7617) | May 08, 2023 |
| Samsung       | 550XBE/350XBE               | Notebook    | [479ad5c021](https://linux-hardware.org/?probe=479ad5c021) | May 08, 2023 |
| Avell High... | A65 MOB                     | Notebook    | [d6c6781535](https://linux-hardware.org/?probe=d6c6781535) | May 08, 2023 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [631317f909](https://linux-hardware.org/?probe=631317f909) | May 08, 2023 |
| Avell High... | 1513                        | Notebook    | [6e383641d6](https://linux-hardware.org/?probe=6e383641d6) | May 08, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [83c0f8e7e5](https://linux-hardware.org/?probe=83c0f8e7e5) | May 08, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [97986b63ad](https://linux-hardware.org/?probe=97986b63ad) | May 08, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [0458d9f44b](https://linux-hardware.org/?probe=0458d9f44b) | May 08, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [9e877e8df9](https://linux-hardware.org/?probe=9e877e8df9) | May 08, 2023 |
| Apple         | Mac-F2218EC8                | All in one  | [d7b87b2b8c](https://linux-hardware.org/?probe=d7b87b2b8c) | May 08, 2023 |
| Samsung       | 530XBB                      | Notebook    | [4d039b72a7](https://linux-hardware.org/?probe=4d039b72a7) | May 08, 2023 |
| Dell          | Latitude 7490               | Notebook    | [c871c848b9](https://linux-hardware.org/?probe=c871c848b9) | May 08, 2023 |
| Positivo      | S14CT01                     | Notebook    | [63a129c031](https://linux-hardware.org/?probe=63a129c031) | May 08, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [c437a16a33](https://linux-hardware.org/?probe=c437a16a33) | May 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [68e1c1b5a4](https://linux-hardware.org/?probe=68e1c1b5a4) | May 07, 2023 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [0c3f2af7ad](https://linux-hardware.org/?probe=0c3f2af7ad) | May 07, 2023 |
| Biostar       | A320MH                      | Notebook    | [5b240feaed](https://linux-hardware.org/?probe=5b240feaed) | May 07, 2023 |
| Itautec       | Infoway a7420               | Notebook    | [52788f2c92](https://linux-hardware.org/?probe=52788f2c92) | May 07, 2023 |
| Intel         | H61                         | Desktop     | [c359f42a22](https://linux-hardware.org/?probe=c359f42a22) | May 07, 2023 |
| HP            | Pavilion dm4                | Notebook    | [8f79a54339](https://linux-hardware.org/?probe=8f79a54339) | May 07, 2023 |
| Intel         | D946GZIS AAD66165-301       | Desktop     | [c350f5ed12](https://linux-hardware.org/?probe=c350f5ed12) | May 06, 2023 |
| Dell          | Vostro 14-3468              | Notebook    | [0a096de0e1](https://linux-hardware.org/?probe=0a096de0e1) | May 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [619dc53d25](https://linux-hardware.org/?probe=619dc53d25) | May 06, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [15e77c1f0a](https://linux-hardware.org/?probe=15e77c1f0a) | May 06, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [9a510bb01b](https://linux-hardware.org/?probe=9a510bb01b) | May 06, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | Desktop     | [812ae9a763](https://linux-hardware.org/?probe=812ae9a763) | May 06, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [696525cf17](https://linux-hardware.org/?probe=696525cf17) | May 06, 2023 |
| ASUSTek       | X441BA                      | Notebook    | [326309c1f1](https://linux-hardware.org/?probe=326309c1f1) | May 06, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [05c9e752a5](https://linux-hardware.org/?probe=05c9e752a5) | May 06, 2023 |
| ASUSTek       | X441BA                      | Notebook    | [dee3bc2cdb](https://linux-hardware.org/?probe=dee3bc2cdb) | May 06, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [0a66f5d4e4](https://linux-hardware.org/?probe=0a66f5d4e4) | May 06, 2023 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [384cc356fc](https://linux-hardware.org/?probe=384cc356fc) | May 06, 2023 |
| Avell High... | A70 HYB                     | Notebook    | [0d871806d1](https://linux-hardware.org/?probe=0d871806d1) | May 05, 2023 |
| Avell High... | A70 HYB                     | Notebook    | [9519eef96f](https://linux-hardware.org/?probe=9519eef96f) | May 05, 2023 |
| HP            | 1998                        | Desktop     | [59c2c05cdb](https://linux-hardware.org/?probe=59c2c05cdb) | May 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [f2c390eb7e](https://linux-hardware.org/?probe=f2c390eb7e) | May 05, 2023 |
| ASUSTek       | K45VM                       | Notebook    | [09e73cade8](https://linux-hardware.org/?probe=09e73cade8) | May 05, 2023 |
| Biostar       | G41D3C                      | Desktop     | [15680367e1](https://linux-hardware.org/?probe=15680367e1) | May 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [f7046c6c99](https://linux-hardware.org/?probe=f7046c6c99) | May 05, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [d27392828f](https://linux-hardware.org/?probe=d27392828f) | May 05, 2023 |
| Positivo      | N4350                       | Notebook    | [ec0df546f9](https://linux-hardware.org/?probe=ec0df546f9) | May 05, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [2ae295d2a0](https://linux-hardware.org/?probe=2ae295d2a0) | May 05, 2023 |
| Acer          | Aspire E1-421               | Notebook    | [45bca26278](https://linux-hardware.org/?probe=45bca26278) | May 05, 2023 |
| Dell          | Inspiron 5490               | Notebook    | [a6c9c8b3b5](https://linux-hardware.org/?probe=a6c9c8b3b5) | May 05, 2023 |
| Avell High... | A40 LIV                     | Notebook    | [5745ae021d](https://linux-hardware.org/?probe=5745ae021d) | May 05, 2023 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [cc6641b5d9](https://linux-hardware.org/?probe=cc6641b5d9) | May 04, 2023 |
| Dell          | Inspiron 5402               | Notebook    | [bac25fa124](https://linux-hardware.org/?probe=bac25fa124) | May 04, 2023 |
| Avell High... | C62 LIV                     | Notebook    | [b53a07f1a3](https://linux-hardware.org/?probe=b53a07f1a3) | May 04, 2023 |
| Acer          | Aspire A515-52G             | Notebook    | [4f2fbcc26f](https://linux-hardware.org/?probe=4f2fbcc26f) | May 04, 2023 |
| Unknown       | E450                        | Notebook    | [a3261aab47](https://linux-hardware.org/?probe=a3261aab47) | May 04, 2023 |
| Dell          | Latitude 3470               | Notebook    | [532cd0124e](https://linux-hardware.org/?probe=532cd0124e) | May 04, 2023 |
| Lenovo        | B490 37722XP                | Notebook    | [62808a2dee](https://linux-hardware.org/?probe=62808a2dee) | May 04, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | Notebook    | [42c07a1fe0](https://linux-hardware.org/?probe=42c07a1fe0) | May 03, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | Notebook    | [bbe569dff7](https://linux-hardware.org/?probe=bbe569dff7) | May 03, 2023 |
| ASUSTek       | X751LJ                      | Notebook    | [708ac49447](https://linux-hardware.org/?probe=708ac49447) | May 03, 2023 |
| ASUSTek       | X751LJ                      | Notebook    | [66e45eac2c](https://linux-hardware.org/?probe=66e45eac2c) | May 03, 2023 |
| Lenovo        | ThinkPad T495 20NK000XBR    | Notebook    | [c7ca4b1477](https://linux-hardware.org/?probe=c7ca4b1477) | May 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [93a11302fb](https://linux-hardware.org/?probe=93a11302fb) | May 03, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [c26b48854d](https://linux-hardware.org/?probe=c26b48854d) | May 03, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [89a9759dfb](https://linux-hardware.org/?probe=89a9759dfb) | May 03, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [f4678817a9](https://linux-hardware.org/?probe=f4678817a9) | May 03, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [81a4d2ac8b](https://linux-hardware.org/?probe=81a4d2ac8b) | May 03, 2023 |
| Adreamer      | PN1308P                     | Notebook    | [8ae75bc5a0](https://linux-hardware.org/?probe=8ae75bc5a0) | May 02, 2023 |
| Positivo      | W2150G                      | All in one  | [38c2a94baa](https://linux-hardware.org/?probe=38c2a94baa) | May 02, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [6e70e21e58](https://linux-hardware.org/?probe=6e70e21e58) | May 02, 2023 |
| HP            | 83E2                        | Desktop     | [7facfe6465](https://linux-hardware.org/?probe=7facfe6465) | May 02, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [d817c9a53f](https://linux-hardware.org/?probe=d817c9a53f) | May 02, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | Notebook    | [143b75f514](https://linux-hardware.org/?probe=143b75f514) | May 02, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [a14544f923](https://linux-hardware.org/?probe=a14544f923) | May 02, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [7ae18f770d](https://linux-hardware.org/?probe=7ae18f770d) | May 02, 2023 |
| Samsung       | 550XDA                      | Notebook    | [4bea46787f](https://linux-hardware.org/?probe=4bea46787f) | May 02, 2023 |
| Unknown       | Phitronics N68C-M           | Desktop     | [77747ce79b](https://linux-hardware.org/?probe=77747ce79b) | May 02, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [f149f8c9fb](https://linux-hardware.org/?probe=f149f8c9fb) | May 02, 2023 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [16cac427e3](https://linux-hardware.org/?probe=16cac427e3) | May 02, 2023 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [45f6915427](https://linux-hardware.org/?probe=45f6915427) | May 02, 2023 |
| ASUSTek       | M5A78L-M LX3 PLUS           | Desktop     | [a41adc3f79](https://linux-hardware.org/?probe=a41adc3f79) | May 02, 2023 |
| Intel         | H61                         | Desktop     | [aa4606c36c](https://linux-hardware.org/?probe=aa4606c36c) | May 02, 2023 |
| Intel         | D946GZIS AAD66165-301       | Desktop     | [e61e22863f](https://linux-hardware.org/?probe=e61e22863f) | May 02, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [b7ff999133](https://linux-hardware.org/?probe=b7ff999133) | May 02, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [a5ac1bf5b4](https://linux-hardware.org/?probe=a5ac1bf5b4) | May 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c56afa707e](https://linux-hardware.org/?probe=c56afa707e) | May 01, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [9ff86ca1f1](https://linux-hardware.org/?probe=9ff86ca1f1) | May 01, 2023 |
| Intel         | H55                         | Desktop     | [04dd5e834e](https://linux-hardware.org/?probe=04dd5e834e) | May 01, 2023 |
| Dell          | Inspiron 5458               | Notebook    | [c38d3e6513](https://linux-hardware.org/?probe=c38d3e6513) | May 01, 2023 |
| Daten Tecn... | DH110MXV                    | Desktop     | [96402fa64a](https://linux-hardware.org/?probe=96402fa64a) | May 01, 2023 |
| Dell          | Inspiron 7460               | Notebook    | [696014fc68](https://linux-hardware.org/?probe=696014fc68) | May 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [99a39f6696](https://linux-hardware.org/?probe=99a39f6696) | May 01, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [6997ff96eb](https://linux-hardware.org/?probe=6997ff96eb) | May 01, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [f5f4abd1f3](https://linux-hardware.org/?probe=f5f4abd1f3) | May 01, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [593a6b247f](https://linux-hardware.org/?probe=593a6b247f) | May 01, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [aa8e8397f6](https://linux-hardware.org/?probe=aa8e8397f6) | May 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [66a3f8bc3a](https://linux-hardware.org/?probe=66a3f8bc3a) | May 01, 2023 |
| Unknown       | Unknown                     | Notebook    | [8978b9aa5f](https://linux-hardware.org/?probe=8978b9aa5f) | May 01, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | Notebook    | [a7d6d782b2](https://linux-hardware.org/?probe=a7d6d782b2) | May 01, 2023 |
| PCWare        | IPMH410E                    | Desktop     | [9be4314a33](https://linux-hardware.org/?probe=9be4314a33) | May 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [193fb3ba91](https://linux-hardware.org/?probe=193fb3ba91) | Apr 30, 2023 |
| Unknown       | Unknown                     | Notebook    | [070854df6b](https://linux-hardware.org/?probe=070854df6b) | Apr 30, 2023 |
| DIEBOLD       | NM70-I                      | Desktop     | [c01a40d58c](https://linux-hardware.org/?probe=c01a40d58c) | Apr 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [bd460bdc62](https://linux-hardware.org/?probe=bd460bdc62) | Apr 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [edfcd7daa6](https://linux-hardware.org/?probe=edfcd7daa6) | Apr 30, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [68d85dd28f](https://linux-hardware.org/?probe=68d85dd28f) | Apr 30, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [5166f820a6](https://linux-hardware.org/?probe=5166f820a6) | Apr 30, 2023 |
| ASRock        | 760GM-HD                    | Desktop     | [db79e93331](https://linux-hardware.org/?probe=db79e93331) | Apr 30, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [9109b0a7ed](https://linux-hardware.org/?probe=9109b0a7ed) | Apr 30, 2023 |
| Positivo      | Q464C                       | Notebook    | [8e41593bd3](https://linux-hardware.org/?probe=8e41593bd3) | Apr 30, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [5fd8f6db6e](https://linux-hardware.org/?probe=5fd8f6db6e) | Apr 30, 2023 |
| Samsung       | 730QED                      | Convertible | [f29e3300d2](https://linux-hardware.org/?probe=f29e3300d2) | Apr 30, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | Desktop     | [2e2b57b3ae](https://linux-hardware.org/?probe=2e2b57b3ae) | Apr 30, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [fed083feba](https://linux-hardware.org/?probe=fed083feba) | Apr 30, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [7804689b38](https://linux-hardware.org/?probe=7804689b38) | Apr 30, 2023 |
| Intel         | H61                         | Desktop     | [167616bc61](https://linux-hardware.org/?probe=167616bc61) | Apr 30, 2023 |
| Intel         | H81                         | Desktop     | [c70b10516b](https://linux-hardware.org/?probe=c70b10516b) | Apr 30, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [9b28e69254](https://linux-hardware.org/?probe=9b28e69254) | Apr 30, 2023 |
| Positivo      | S14CT01                     | Notebook    | [b11ef938e1](https://linux-hardware.org/?probe=b11ef938e1) | Apr 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [0a9a85f5f0](https://linux-hardware.org/?probe=0a9a85f5f0) | Apr 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [83b10185e8](https://linux-hardware.org/?probe=83b10185e8) | Apr 29, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [44a08af32f](https://linux-hardware.org/?probe=44a08af32f) | Apr 29, 2023 |
| ASUSTek       | H81M-C/BR                   | Desktop     | [32942be783](https://linux-hardware.org/?probe=32942be783) | Apr 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [af0c1ea83c](https://linux-hardware.org/?probe=af0c1ea83c) | Apr 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [7c8c5a4668](https://linux-hardware.org/?probe=7c8c5a4668) | Apr 29, 2023 |
| HP            | Pavilion dm4                | Notebook    | [3473d4b312](https://linux-hardware.org/?probe=3473d4b312) | Apr 29, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [ba5c65f4e3](https://linux-hardware.org/?probe=ba5c65f4e3) | Apr 29, 2023 |
| ASUSTek       | P8H61-M LE/BR               | Desktop     | [425f1a3e08](https://linux-hardware.org/?probe=425f1a3e08) | Apr 29, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [1e75efbfab](https://linux-hardware.org/?probe=1e75efbfab) | Apr 29, 2023 |
| Positivo      | S14CT01                     | Notebook    | [58988f4876](https://linux-hardware.org/?probe=58988f4876) | Apr 29, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [33e30c562d](https://linux-hardware.org/?probe=33e30c562d) | Apr 29, 2023 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [16b28befee](https://linux-hardware.org/?probe=16b28befee) | Apr 28, 2023 |
| ASUSTek       | Z550SA                      | Notebook    | [7c6c0c9599](https://linux-hardware.org/?probe=7c6c0c9599) | Apr 28, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [1d36dafa86](https://linux-hardware.org/?probe=1d36dafa86) | Apr 28, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [43b57e5088](https://linux-hardware.org/?probe=43b57e5088) | Apr 28, 2023 |
| HP            | 158B                        | Desktop     | [ee0297b0ba](https://linux-hardware.org/?probe=ee0297b0ba) | Apr 28, 2023 |
| Intel         | H61 V124                    | Desktop     | [1fa0b34b3c](https://linux-hardware.org/?probe=1fa0b34b3c) | Apr 28, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [d3442220b0](https://linux-hardware.org/?probe=d3442220b0) | Apr 28, 2023 |
| Intel         | H61                         | Desktop     | [b8f0acdf61](https://linux-hardware.org/?probe=b8f0acdf61) | Apr 28, 2023 |
| Multilaser    | UB820                       | All in one  | [3796d857b1](https://linux-hardware.org/?probe=3796d857b1) | Apr 28, 2023 |
| HP            | Presario CQ43               | Notebook    | [c14c79b3cf](https://linux-hardware.org/?probe=c14c79b3cf) | Apr 28, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [6926565982](https://linux-hardware.org/?probe=6926565982) | Apr 27, 2023 |
| Dell          | Inspiron 5482               | Convertible | [530ed5285a](https://linux-hardware.org/?probe=530ed5285a) | Apr 27, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [f96c9382bd](https://linux-hardware.org/?probe=f96c9382bd) | Apr 27, 2023 |
| Dell          | Latitude D520               | Notebook    | [a643e2e424](https://linux-hardware.org/?probe=a643e2e424) | Apr 27, 2023 |
| ASUSTek       | Z97M-PLUS/BR                | Desktop     | [3255acf414](https://linux-hardware.org/?probe=3255acf414) | Apr 27, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [6a56164bfd](https://linux-hardware.org/?probe=6a56164bfd) | Apr 27, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [475e46f565](https://linux-hardware.org/?probe=475e46f565) | Apr 27, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [9211d42ee3](https://linux-hardware.org/?probe=9211d42ee3) | Apr 27, 2023 |
| Acer          | Aspire A315-54              | Notebook    | [8137aa9008](https://linux-hardware.org/?probe=8137aa9008) | Apr 27, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [9f3b8c952d](https://linux-hardware.org/?probe=9f3b8c952d) | Apr 27, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [2306f31aa2](https://linux-hardware.org/?probe=2306f31aa2) | Apr 27, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [393c7b06d5](https://linux-hardware.org/?probe=393c7b06d5) | Apr 26, 2023 |
| HP            | 3047h                       | Desktop     | [3e6dada8a9](https://linux-hardware.org/?probe=3e6dada8a9) | Apr 26, 2023 |
| Pegatron      | IPM41-D3                    | Desktop     | [faf8704eb3](https://linux-hardware.org/?probe=faf8704eb3) | Apr 26, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [f91ac46cfd](https://linux-hardware.org/?probe=f91ac46cfd) | Apr 26, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [8f417742d1](https://linux-hardware.org/?probe=8f417742d1) | Apr 26, 2023 |
| Dell          | Inspiron 7580               | Notebook    | [d9fe7034bd](https://linux-hardware.org/?probe=d9fe7034bd) | Apr 26, 2023 |
| Biostar       | H610MH                      | Desktop     | [935928c60d](https://linux-hardware.org/?probe=935928c60d) | Apr 26, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [208a0fc365](https://linux-hardware.org/?probe=208a0fc365) | Apr 26, 2023 |
| Intel         | B75                         | Desktop     | [72a3677ac2](https://linux-hardware.org/?probe=72a3677ac2) | Apr 26, 2023 |
| Dell          | G15 5510                    | Notebook    | [9dcb76f7c1](https://linux-hardware.org/?probe=9dcb76f7c1) | Apr 26, 2023 |
| Dell          | G15 5510                    | Notebook    | [4030b4f936](https://linux-hardware.org/?probe=4030b4f936) | Apr 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [84bc235979](https://linux-hardware.org/?probe=84bc235979) | Apr 26, 2023 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [a7e77375d4](https://linux-hardware.org/?probe=a7e77375d4) | Apr 26, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [23571a99b1](https://linux-hardware.org/?probe=23571a99b1) | Apr 26, 2023 |
| Intel         | H81                         | Desktop     | [9a14132581](https://linux-hardware.org/?probe=9a14132581) | Apr 26, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [7cbf188375](https://linux-hardware.org/?probe=7cbf188375) | Apr 26, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [b94d783285](https://linux-hardware.org/?probe=b94d783285) | Apr 26, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [a660a768ce](https://linux-hardware.org/?probe=a660a768ce) | Apr 26, 2023 |
| Dell          | Inspiron N4030              | Notebook    | [a0f1823b8e](https://linux-hardware.org/?probe=a0f1823b8e) | Apr 26, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [9fe0f33003](https://linux-hardware.org/?probe=9fe0f33003) | Apr 26, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [a24f74af8e](https://linux-hardware.org/?probe=a24f74af8e) | Apr 26, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [5c79032176](https://linux-hardware.org/?probe=5c79032176) | Apr 25, 2023 |
| HP            | Pavilion g4                 | Notebook    | [5e2040a91f](https://linux-hardware.org/?probe=5e2040a91f) | Apr 25, 2023 |
| ASRock        | AB350M-HDV                  | Desktop     | [44ac797451](https://linux-hardware.org/?probe=44ac797451) | Apr 25, 2023 |
| Login Info... | LOG-S14BW01-CD              | Notebook    | [5f6e2a61f2](https://linux-hardware.org/?probe=5f6e2a61f2) | Apr 25, 2023 |
| Biostar       | B450MX-S                    | Desktop     | [5ac7debff3](https://linux-hardware.org/?probe=5ac7debff3) | Apr 25, 2023 |
| Dell          | G15 5515                    | Notebook    | [a0dd3f2003](https://linux-hardware.org/?probe=a0dd3f2003) | Apr 25, 2023 |
| Avell High... | A70 HYB BS                  | Notebook    | [c7b5f9ef04](https://linux-hardware.org/?probe=c7b5f9ef04) | Apr 25, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [48e88f7bd1](https://linux-hardware.org/?probe=48e88f7bd1) | Apr 25, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [653c3c4650](https://linux-hardware.org/?probe=653c3c4650) | Apr 25, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [afcce1c52c](https://linux-hardware.org/?probe=afcce1c52c) | Apr 25, 2023 |
| Gigabyte      | H87-D3H-CF                  | Desktop     | [b3a3115f0c](https://linux-hardware.org/?probe=b3a3115f0c) | Apr 25, 2023 |
| OEM           | HN B85 Ver:1.4              | Desktop     | [1da5934b27](https://linux-hardware.org/?probe=1da5934b27) | Apr 25, 2023 |
| Dell          | G3 3500                     | Notebook    | [46996524d0](https://linux-hardware.org/?probe=46996524d0) | Apr 25, 2023 |
| Purism        | Librem 14                   | Notebook    | [8462dbaccb](https://linux-hardware.org/?probe=8462dbaccb) | Apr 25, 2023 |
| HP            | 2B21 A01                    | All in one  | [2eec2836c7](https://linux-hardware.org/?probe=2eec2836c7) | Apr 25, 2023 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [1b26b3f89b](https://linux-hardware.org/?probe=1b26b3f89b) | Apr 24, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [342918aa38](https://linux-hardware.org/?probe=342918aa38) | Apr 24, 2023 |
| Notebook      | N85_N87HCHNHZ               | Notebook    | [ecb3270b4a](https://linux-hardware.org/?probe=ecb3270b4a) | Apr 24, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [13c75fa32e](https://linux-hardware.org/?probe=13c75fa32e) | Apr 24, 2023 |
| AMD           | Inagua CRB                  | Desktop     | [085d0aa051](https://linux-hardware.org/?probe=085d0aa051) | Apr 24, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [9bab79728a](https://linux-hardware.org/?probe=9bab79728a) | Apr 24, 2023 |
| Intel         | D946GZIS AAD66165-301       | Desktop     | [9d5ada0fc4](https://linux-hardware.org/?probe=9d5ada0fc4) | Apr 24, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [2f1eb3e6ee](https://linux-hardware.org/?probe=2f1eb3e6ee) | Apr 24, 2023 |
| Dell          | 0VTJVC A00                  | Desktop     | [da7d66917d](https://linux-hardware.org/?probe=da7d66917d) | Apr 24, 2023 |
| Gateway       | NV55C                       | Notebook    | [3c560a28cf](https://linux-hardware.org/?probe=3c560a28cf) | Apr 24, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [2e7585d261](https://linux-hardware.org/?probe=2e7585d261) | Apr 24, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [de1981f9e6](https://linux-hardware.org/?probe=de1981f9e6) | Apr 24, 2023 |
| Dell          | Inspiron 11-3168            | Notebook    | [5ac6392b05](https://linux-hardware.org/?probe=5ac6392b05) | Apr 24, 2023 |
| Huanan        | X99-8M-F V1.1               | Desktop     | [0621d00b73](https://linux-hardware.org/?probe=0621d00b73) | Apr 24, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [e562ba35c6](https://linux-hardware.org/?probe=e562ba35c6) | Apr 23, 2023 |
| Biostar       | B350ET2                     | Desktop     | [47289e48eb](https://linux-hardware.org/?probe=47289e48eb) | Apr 23, 2023 |
| Dell          | G15 5520                    | Notebook    | [d2cc8527a5](https://linux-hardware.org/?probe=d2cc8527a5) | Apr 23, 2023 |
| ASUSTek       | AM1M-A/BR                   | Desktop     | [0b29ee62f9](https://linux-hardware.org/?probe=0b29ee62f9) | Apr 23, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [0e85243397](https://linux-hardware.org/?probe=0e85243397) | Apr 23, 2023 |
| HP            | G42                         | Notebook    | [1d5b2eefc3](https://linux-hardware.org/?probe=1d5b2eefc3) | Apr 23, 2023 |
| HP            | 18E7                        | Desktop     | [c5bc4d9c7f](https://linux-hardware.org/?probe=c5bc4d9c7f) | Apr 23, 2023 |
| MACHINIST     | E5-MR9A PRO V1.1            | Desktop     | [eebce73217](https://linux-hardware.org/?probe=eebce73217) | Apr 23, 2023 |
| ASUSTek       | H81M-C/BR                   | Desktop     | [46a27a7551](https://linux-hardware.org/?probe=46a27a7551) | Apr 23, 2023 |
| ASUSTek       | X45C                        | Notebook    | [759ed58d76](https://linux-hardware.org/?probe=759ed58d76) | Apr 23, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [793e094165](https://linux-hardware.org/?probe=793e094165) | Apr 23, 2023 |
| Pegatron      | IPMH61P1                    | Desktop     | [b71d5b1a48](https://linux-hardware.org/?probe=b71d5b1a48) | Apr 23, 2023 |
| Unknown       | G41                         | Desktop     | [cbe978cc34](https://linux-hardware.org/?probe=cbe978cc34) | Apr 23, 2023 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | Notebook    | [90b7213592](https://linux-hardware.org/?probe=90b7213592) | Apr 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [9a92345b08](https://linux-hardware.org/?probe=9a92345b08) | Apr 23, 2023 |
| Gigabyte      | VM900M Rev2.0               | Desktop     | [284ada7211](https://linux-hardware.org/?probe=284ada7211) | Apr 23, 2023 |
| PCWare        | IPX1800G2                   | Desktop     | [f63cf0fe51](https://linux-hardware.org/?probe=f63cf0fe51) | Apr 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [0e798db6a8](https://linux-hardware.org/?probe=0e798db6a8) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [1b475eaa99](https://linux-hardware.org/?probe=1b475eaa99) | Apr 23, 2023 |
| Acer          | Spin SP315-51               | Convertible | [42da7880dd](https://linux-hardware.org/?probe=42da7880dd) | Apr 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [dfb9f87dad](https://linux-hardware.org/?probe=dfb9f87dad) | Apr 22, 2023 |
| Dell          | G15 5520                    | Notebook    | [238c8f53aa](https://linux-hardware.org/?probe=238c8f53aa) | Apr 22, 2023 |
| LG Electro... | A530-T.BE76P1               | Notebook    | [8bb0353706](https://linux-hardware.org/?probe=8bb0353706) | Apr 22, 2023 |
| LG Electro... | A530-T.BE76P1               | Notebook    | [b699c8ed48](https://linux-hardware.org/?probe=b699c8ed48) | Apr 22, 2023 |
| LG Electro... | A530-T.BE76P1               | Notebook    | [f5c282ca6c](https://linux-hardware.org/?probe=f5c282ca6c) | Apr 22, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [ea8fb664a3](https://linux-hardware.org/?probe=ea8fb664a3) | Apr 22, 2023 |
| Dell          | G15 5520                    | Notebook    | [07751c950a](https://linux-hardware.org/?probe=07751c950a) | Apr 22, 2023 |
| Acer          | Spin SP314-51               | Convertible | [5fd72bcee7](https://linux-hardware.org/?probe=5fd72bcee7) | Apr 22, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [452177f9a5](https://linux-hardware.org/?probe=452177f9a5) | Apr 21, 2023 |
| ASRock        | H310CM-HG4                  | Desktop     | [6f49f4b883](https://linux-hardware.org/?probe=6f49f4b883) | Apr 21, 2023 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [1de5b776a3](https://linux-hardware.org/?probe=1de5b776a3) | Apr 21, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [a315eaa776](https://linux-hardware.org/?probe=a315eaa776) | Apr 21, 2023 |
| Digibras      | NH4CU53                     | Notebook    | [d6571e3d78](https://linux-hardware.org/?probe=d6571e3d78) | Apr 21, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [cb295448b6](https://linux-hardware.org/?probe=cb295448b6) | Apr 21, 2023 |
| Multilaser    | PC13X                       | Notebook    | [d1144e31a1](https://linux-hardware.org/?probe=d1144e31a1) | Apr 21, 2023 |
| Positivo      | N6440                       | Notebook    | [b0a1fe417d](https://linux-hardware.org/?probe=b0a1fe417d) | Apr 21, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [5f1a1c6abd](https://linux-hardware.org/?probe=5f1a1c6abd) | Apr 20, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [e09f00bead](https://linux-hardware.org/?probe=e09f00bead) | Apr 20, 2023 |
| HP            | Pavilion g4                 | Notebook    | [96a0210940](https://linux-hardware.org/?probe=96a0210940) | Apr 20, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [55685c168f](https://linux-hardware.org/?probe=55685c168f) | Apr 20, 2023 |
| Gigabyte      | G31M-S2C                    | Desktop     | [0c45fc6929](https://linux-hardware.org/?probe=0c45fc6929) | Apr 20, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [f8519c5a20](https://linux-hardware.org/?probe=f8519c5a20) | Apr 20, 2023 |
| Intel         | H61S                        | Desktop     | [e29d71587a](https://linux-hardware.org/?probe=e29d71587a) | Apr 20, 2023 |
| Samsung       | 550P5C/550P7C               | Notebook    | [3648dd39f8](https://linux-hardware.org/?probe=3648dd39f8) | Apr 20, 2023 |
| Dell          | Inspiron 7460               | Notebook    | [bbfe51bf3c](https://linux-hardware.org/?probe=bbfe51bf3c) | Apr 19, 2023 |
| Lenovo        | Yoga 510-14ISK 80UK         | Convertible | [649afe5f77](https://linux-hardware.org/?probe=649afe5f77) | Apr 19, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [701110cf4e](https://linux-hardware.org/?probe=701110cf4e) | Apr 19, 2023 |
| ASUSTek       | PRIME B250M-PLUS/BR         | Desktop     | [c0a82bb35a](https://linux-hardware.org/?probe=c0a82bb35a) | Apr 19, 2023 |
| Intel         | X79M-S                      | Desktop     | [0c51f5a0e0](https://linux-hardware.org/?probe=0c51f5a0e0) | Apr 19, 2023 |
| Samsung       | 730QED                      | Convertible | [5897b751da](https://linux-hardware.org/?probe=5897b751da) | Apr 18, 2023 |
| Samsung       | 730QED                      | Convertible | [84ce1adcfe](https://linux-hardware.org/?probe=84ce1adcfe) | Apr 18, 2023 |
| Acer          | AO722                       | Notebook    | [5fe24a9991](https://linux-hardware.org/?probe=5fe24a9991) | Apr 18, 2023 |
| LG Electro... | White Tip Mountain FAB3     | All in one  | [5f73a9e985](https://linux-hardware.org/?probe=5f73a9e985) | Apr 18, 2023 |
| ASUSTek       | PRIME B250M-PLUS/BR         | Desktop     | [8bb9dc2419](https://linux-hardware.org/?probe=8bb9dc2419) | Apr 18, 2023 |
| Dell          | Vostro 5402                 | Notebook    | [e492c87b46](https://linux-hardware.org/?probe=e492c87b46) | Apr 18, 2023 |
| Dell          | Vostro 5402                 | Notebook    | [b15f47258b](https://linux-hardware.org/?probe=b15f47258b) | Apr 18, 2023 |
| AMD           | Inagua CRB                  | Desktop     | [8d2ce37fca](https://linux-hardware.org/?probe=8d2ce37fca) | Apr 18, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [7fcc7d1b34](https://linux-hardware.org/?probe=7fcc7d1b34) | Apr 18, 2023 |
| Dell          | Vostro 3480                 | Notebook    | [f2f48756e6](https://linux-hardware.org/?probe=f2f48756e6) | Apr 18, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [90c4ba9f6e](https://linux-hardware.org/?probe=90c4ba9f6e) | Apr 17, 2023 |
| HP            | 240 G4 Notebook PC          | Notebook    | [6410232c86](https://linux-hardware.org/?probe=6410232c86) | Apr 17, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [961e1f1908](https://linux-hardware.org/?probe=961e1f1908) | Apr 17, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [bbbc9206b4](https://linux-hardware.org/?probe=bbbc9206b4) | Apr 17, 2023 |
| Avell High... | A70 MOB                     | Notebook    | [869b1ae79b](https://linux-hardware.org/?probe=869b1ae79b) | Apr 17, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [5e9ebca163](https://linux-hardware.org/?probe=5e9ebca163) | Apr 17, 2023 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | Notebook    | [acd0161868](https://linux-hardware.org/?probe=acd0161868) | Apr 17, 2023 |
| Multilaser    | PC13X                       | Notebook    | [3b755838a2](https://linux-hardware.org/?probe=3b755838a2) | Apr 16, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [beac478abb](https://linux-hardware.org/?probe=beac478abb) | Apr 16, 2023 |
| HP            | 240 G2                      | Notebook    | [ca6ae60a2b](https://linux-hardware.org/?probe=ca6ae60a2b) | Apr 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [482a8c29cc](https://linux-hardware.org/?probe=482a8c29cc) | Apr 16, 2023 |
| Valve         | Jupiter                     | Notebook    | [6c83afd9b3](https://linux-hardware.org/?probe=6c83afd9b3) | Apr 16, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [3b20856ccc](https://linux-hardware.org/?probe=3b20856ccc) | Apr 16, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [5ce7874f2e](https://linux-hardware.org/?probe=5ce7874f2e) | Apr 16, 2023 |
| Itautec       | Infoway                     | Notebook    | [c046d6e093](https://linux-hardware.org/?probe=c046d6e093) | Apr 16, 2023 |
| Positivo      | C14CR01                     | Notebook    | [a5fc85315a](https://linux-hardware.org/?probe=a5fc85315a) | Apr 16, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [f7cf140a28](https://linux-hardware.org/?probe=f7cf140a28) | Apr 16, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [73c46e2901](https://linux-hardware.org/?probe=73c46e2901) | Apr 15, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [3decfdc1f6](https://linux-hardware.org/?probe=3decfdc1f6) | Apr 15, 2023 |
| Intel         | B75                         | Desktop     | [18dce6805d](https://linux-hardware.org/?probe=18dce6805d) | Apr 15, 2023 |
| AMD           | A88F2EKS                    | Desktop     | [48cef621bd](https://linux-hardware.org/?probe=48cef621bd) | Apr 15, 2023 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [dd2d3443a9](https://linux-hardware.org/?probe=dd2d3443a9) | Apr 15, 2023 |
| Lenovo        | ThinkCentre M58p 6234CZ6    | Desktop     | [e412c388d8](https://linux-hardware.org/?probe=e412c388d8) | Apr 15, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [dfed605628](https://linux-hardware.org/?probe=dfed605628) | Apr 15, 2023 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [fcfa1ed488](https://linux-hardware.org/?probe=fcfa1ed488) | Apr 14, 2023 |
| Dell          | Inspiron 7460               | Notebook    | [ae861b54cd](https://linux-hardware.org/?probe=ae861b54cd) | Apr 14, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [a34f2e065b](https://linux-hardware.org/?probe=a34f2e065b) | Apr 14, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [ec08193576](https://linux-hardware.org/?probe=ec08193576) | Apr 14, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [e2f136f068](https://linux-hardware.org/?probe=e2f136f068) | Apr 14, 2023 |
| PCWare        | IPMH61R3                    | Desktop     | [776a2824c5](https://linux-hardware.org/?probe=776a2824c5) | Apr 14, 2023 |
| Avell High... | B.ON                        | Notebook    | [0ac252a73b](https://linux-hardware.org/?probe=0ac252a73b) | Apr 14, 2023 |
| OEM           | H110                        | Desktop     | [60e8c50cdd](https://linux-hardware.org/?probe=60e8c50cdd) | Apr 14, 2023 |
| ASUSTek       | Maximus IX APEX             | Desktop     | [f4a7db0c2a](https://linux-hardware.org/?probe=f4a7db0c2a) | Apr 14, 2023 |
| Positivo      | Q4128C-S                    | Notebook    | [8dc2eb7738](https://linux-hardware.org/?probe=8dc2eb7738) | Apr 14, 2023 |
| HP            | 1589                        | Desktop     | [b5309b9a82](https://linux-hardware.org/?probe=b5309b9a82) | Apr 14, 2023 |
| Samsung       | 670Z5E                      | Notebook    | [96bcf536e6](https://linux-hardware.org/?probe=96bcf536e6) | Apr 14, 2023 |
| Samsung       | 670Z5E                      | Notebook    | [dff09c0918](https://linux-hardware.org/?probe=dff09c0918) | Apr 14, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [07a2ba2393](https://linux-hardware.org/?probe=07a2ba2393) | Apr 13, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [4267100894](https://linux-hardware.org/?probe=4267100894) | Apr 13, 2023 |
| Dell          | Inspiron 5515               | Notebook    | [e7306b2521](https://linux-hardware.org/?probe=e7306b2521) | Apr 13, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [c200475e1f](https://linux-hardware.org/?probe=c200475e1f) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [5e9f89e556](https://linux-hardware.org/?probe=5e9f89e556) | Apr 13, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [eedb55e1ba](https://linux-hardware.org/?probe=eedb55e1ba) | Apr 13, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [ae928fe177](https://linux-hardware.org/?probe=ae928fe177) | Apr 13, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [89a7f8f7e7](https://linux-hardware.org/?probe=89a7f8f7e7) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [d72e78c1b0](https://linux-hardware.org/?probe=d72e78c1b0) | Apr 13, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [f57cf8ddf4](https://linux-hardware.org/?probe=f57cf8ddf4) | Apr 13, 2023 |
| Dell          | Inspiron 5482               | Convertible | [2d1dbac3cf](https://linux-hardware.org/?probe=2d1dbac3cf) | Apr 13, 2023 |
| Samsung       | 270E5G/270E5U               | Notebook    | [ea58c893c1](https://linux-hardware.org/?probe=ea58c893c1) | Apr 13, 2023 |
| OEM           | Intel H81                   | Desktop     | [1a73452d73](https://linux-hardware.org/?probe=1a73452d73) | Apr 13, 2023 |
| Positivo      | H14SU08                     | Notebook    | [8e8d14728f](https://linux-hardware.org/?probe=8e8d14728f) | Apr 13, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [c53ec6a9c0](https://linux-hardware.org/?probe=c53ec6a9c0) | Apr 13, 2023 |
| Positivo      | Q4128C-S                    | Notebook    | [a46ba9bff2](https://linux-hardware.org/?probe=a46ba9bff2) | Apr 12, 2023 |
| Positivo      | Q4128C-S                    | Notebook    | [3b5a11f774](https://linux-hardware.org/?probe=3b5a11f774) | Apr 12, 2023 |
| Intel         | powered classmate PC        | Notebook    | [79b262de52](https://linux-hardware.org/?probe=79b262de52) | Apr 12, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [12ca37afd3](https://linux-hardware.org/?probe=12ca37afd3) | Apr 12, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [1b97e4ffc5](https://linux-hardware.org/?probe=1b97e4ffc5) | Apr 12, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [402a94b1c0](https://linux-hardware.org/?probe=402a94b1c0) | Apr 12, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [7b4e6e07cf](https://linux-hardware.org/?probe=7b4e6e07cf) | Apr 12, 2023 |
| Win elemen... | M600                        | Desktop     | [4268d36ca4](https://linux-hardware.org/?probe=4268d36ca4) | Apr 12, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [065d244d4b](https://linux-hardware.org/?probe=065d244d4b) | Apr 12, 2023 |
| Intel         | H61 V124                    | Desktop     | [28b73b97b3](https://linux-hardware.org/?probe=28b73b97b3) | Apr 12, 2023 |
| Dell          | G3 3579                     | Notebook    | [24d10a8497](https://linux-hardware.org/?probe=24d10a8497) | Apr 12, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [4eb8c9f372](https://linux-hardware.org/?probe=4eb8c9f372) | Apr 12, 2023 |
| Daten Tecn... | DH110MXV                    | Desktop     | [6a1c34f539](https://linux-hardware.org/?probe=6a1c34f539) | Apr 12, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Brazil/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 1524      | 11.23%  |
| Ubuntu 18.04       | 1033      | 7.61%   |
| Ubuntu 22.04       | 516       | 3.8%    |
| OpenMandriva 4.2   | 339       | 2.5%    |
| Pop!_OS 20.04      | 318       | 2.34%   |
| Linux Mint 20      | 314       | 2.31%   |
| OpenMandriva 4.3   | 291       | 2.14%   |
| Linux Mint 19.3    | 287       | 2.11%   |
| Linux Mint 19.1    | 235       | 1.73%   |
| Ubuntu 19.04       | 218       | 1.61%   |
| Linux Mint 20.3    | 217       | 1.6%    |
| Pop!_OS 22.04      | 216       | 1.59%   |
| KDE neon 20.04     | 215       | 1.58%   |
| Manjaro            | 214       | 1.58%   |
| Linux Mint 20.1    | 209       | 1.54%   |
| Zorin 16           | 201       | 1.48%   |
| Debian 11          | 190       | 1.4%    |
| Arch               | 189       | 1.39%   |
| Linux Mint 20.2    | 183       | 1.35%   |
| Ubuntu 19.10       | 173       | 1.27%   |
| Arch Rolling       | 162       | 1.19%   |
| Debian 10          | 155       | 1.14%   |
| Zorin 15           | 150       | 1.11%   |
| Linux Mint 21.1    | 134       | 0.99%   |
| Pop!_OS 21.04      | 127       | 0.94%   |
| Pop!_OS 20.10      | 127       | 0.94%   |
| OpenMandriva 23.01 | 126       | 0.93%   |
| Fedora 37          | 123       | 0.91%   |
| Fedora 34          | 120       | 0.88%   |
| Fedora 36          | 119       | 0.88%   |
| Xubuntu 20.04      | 117       | 0.86%   |
| Fedora 32          | 111       | 0.82%   |
| Pop!_OS 21.10      | 110       | 0.81%   |
| Fedora 35          | 110       | 0.81%   |
| Fedora 33          | 105       | 0.77%   |
| Linux Mint 21      | 103       | 0.76%   |
| Linux Mint 19.2    | 103       | 0.76%   |
| Ubuntu MATE 20.04  | 101       | 0.74%   |
| Kubuntu 20.04      | 101       | 0.74%   |
| Ubuntu 20.10       | 99        | 0.73%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 3810      | 29.48%  |
| Linux Mint    | 1750      | 13.54%  |
| Endless       | 1046      | 8.09%   |
| OpenMandriva  | 882       | 6.82%   |
| Pop!_OS       | 864       | 6.69%   |
| Fedora        | 794       | 6.14%   |
| Debian        | 462       | 3.57%   |
| Manjaro       | 397       | 3.07%   |
| Zorin         | 360       | 2.79%   |
| Arch          | 338       | 2.62%   |
| KDE neon      | 276       | 2.14%   |
| Xubuntu       | 229       | 1.77%   |
| Kubuntu       | 219       | 1.69%   |
| Ubuntu MATE   | 139       | 1.08%   |
| ROSA          | 131       | 1.01%   |
| openSUSE      | 126       | 0.97%   |
| Lubuntu       | 107       | 0.83%   |
| Elementary    | 99        | 0.77%   |
| Ubuntu Unity  | 88        | 0.68%   |
| LMDE          | 70        | 0.54%   |
| Kali          | 69        | 0.53%   |
| ArcoLinux     | 58        | 0.45%   |
| Deepin        | 47        | 0.36%   |
| Ubuntu Budgie | 44        | 0.34%   |
| LinuxFX       | 40        | 0.31%   |
| BigLinux      | 37        | 0.29%   |
| Clear Linux   | 36        | 0.28%   |
| CentOS        | 32        | 0.25%   |
| BlackPanther  | 30        | 0.23%   |
| EndeavourOS   | 25        | 0.19%   |
| Gentoo        | 19        | 0.15%   |
| Parrot        | 16        | 0.12%   |
| Garuda Linux  | 16        | 0.12%   |
| Peppermint    | 14        | 0.11%   |
| Nobara        | 14        | 0.11%   |
| MX            | 14        | 0.11%   |
| SteamOS       | 13        | 0.1%    |
| UbuntuDDE     | 12        | 0.09%   |
| Solus         | 12        | 0.09%   |
| Linux Lite    | 12        | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 710       | 4.85%   |
| 5.10.14-desktop-1omv4002 | 328       | 2.24%   |
| 5.8.0-14-generic         | 317       | 2.17%   |
| 5.16.7-desktop-1omv4003  | 275       | 1.88%   |
| 4.15.0-46-generic        | 156       | 1.07%   |
| 5.3.0-28-generic         | 146       | 1%      |
| 5.4.0-48-generic         | 138       | 0.94%   |
| 5.4.0-19-generic         | 138       | 0.94%   |
| 5.4.0-7634-generic       | 123       | 0.84%   |
| 6.1.1-desktop-1omv2290   | 116       | 0.79%   |
| 5.15.0-56-generic        | 112       | 0.77%   |
| 5.11.0-35-generic        | 112       | 0.77%   |
| 5.4.0-40-generic         | 111       | 0.76%   |
| 5.4.0-58-generic         | 110       | 0.75%   |
| 5.4.0-26-generic         | 106       | 0.72%   |
| 5.4.0-52-generic         | 101       | 0.69%   |
| 4.18.0-15-generic        | 97        | 0.66%   |
| 5.4.0-47-generic         | 96        | 0.66%   |
| 6.2.6-desktop-1omv2390   | 93        | 0.64%   |
| 5.3.0-40-generic         | 89        | 0.61%   |
| 5.11.0-7620-generic      | 78        | 0.53%   |
| 5.0.0-32-generic         | 78        | 0.53%   |
| 5.3.0-46-generic         | 77        | 0.53%   |
| 5.0.0-37-generic         | 72        | 0.49%   |
| 4.15.0-20-generic        | 72        | 0.49%   |
| 5.4.0-70-generic         | 71        | 0.49%   |
| 5.4.0-72-generic         | 68        | 0.46%   |
| 5.15.0-46-generic        | 67        | 0.46%   |
| 5.4.0-91-generic         | 66        | 0.45%   |
| 5.15.0-52-generic        | 66        | 0.45%   |
| 5.4.0-80-generic         | 63        | 0.43%   |
| 5.3.0-23-generic         | 63        | 0.43%   |
| 5.4.0-29-generic         | 62        | 0.42%   |
| 4.18.0-16-generic        | 62        | 0.42%   |
| 5.4.0-65-generic         | 61        | 0.42%   |
| 5.4.0-37-generic         | 61        | 0.42%   |
| 5.15.0-58-generic        | 61        | 0.42%   |
| 5.4.0-39-generic         | 60        | 0.41%   |
| 5.15.0-43-generic        | 60        | 0.41%   |
| 5.0.0-25-generic         | 60        | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 3038      | 21.92%  |
| 4.15.0  | 946       | 6.83%   |
| 5.8.0   | 901       | 6.5%    |
| 5.15.0  | 881       | 6.36%   |
| 5.3.0   | 799       | 5.76%   |
| 5.11.0  | 708       | 5.11%   |
| 5.0.0   | 564       | 4.07%   |
| 5.13.0  | 466       | 3.36%   |
| 4.18.0  | 416       | 3%      |
| 5.10.14 | 330       | 2.38%   |
| 5.19.0  | 313       | 2.26%   |
| 5.16.7  | 275       | 1.98%   |
| 5.10.0  | 245       | 1.77%   |
| 4.19.0  | 184       | 1.33%   |
| 6.2.6   | 145       | 1.05%   |
| 6.1.1   | 126       | 0.91%   |
| 5.17.5  | 59        | 0.43%   |
| 6.1.0   | 48        | 0.35%   |
| 4.4.0   | 48        | 0.35%   |
| 6.0.12  | 47        | 0.34%   |
| 5.7.9   | 47        | 0.34%   |
| 6.2.0   | 45        | 0.32%   |
| 4.9.0   | 41        | 0.3%    |
| 5.16.11 | 40        | 0.29%   |
| 5.14.0  | 40        | 0.29%   |
| 5.15.5  | 31        | 0.22%   |
| 5.7.0   | 30        | 0.22%   |
| 5.15.15 | 30        | 0.22%   |
| 5.9.16  | 28        | 0.2%    |
| 5.6.19  | 27        | 0.19%   |
| 4.9.60  | 27        | 0.19%   |
| 5.3.18  | 25        | 0.18%   |
| 5.11.12 | 25        | 0.18%   |
| 4.18.16 | 25        | 0.18%   |
| 6.0.0   | 24        | 0.17%   |
| 5.18.12 | 24        | 0.17%   |
| 5.16.13 | 24        | 0.17%   |
| 5.13.19 | 24        | 0.17%   |
| 6.2.15  | 22        | 0.16%   |
| 5.7.10  | 22        | 0.16%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 3164      | 23.13%  |
| 5.15    | 1162      | 8.49%   |
| 5.8     | 1014      | 7.41%   |
| 4.15    | 946       | 6.91%   |
| 5.3     | 870       | 6.36%   |
| 5.11    | 806       | 5.89%   |
| 5.10    | 769       | 5.62%   |
| 5.0     | 606       | 4.43%   |
| 5.13    | 559       | 4.09%   |
| 5.16    | 461       | 3.37%   |
| 4.18    | 449       | 3.28%   |
| 5.19    | 413       | 3.02%   |
| 6.2     | 338       | 2.47%   |
| 6.1     | 323       | 2.36%   |
| 4.19    | 220       | 1.61%   |
| 6.0     | 196       | 1.43%   |
| 5.7     | 172       | 1.26%   |
| 5.17    | 156       | 1.14%   |
| 5.18    | 139       | 1.02%   |
| 5.14    | 133       | 0.97%   |
| 5.6     | 126       | 0.92%   |
| 5.12    | 113       | 0.83%   |
| 5.9     | 110       | 0.8%    |
| 4.9     | 107       | 0.78%   |
| 6.3     | 74        | 0.54%   |
| 4.4     | 54        | 0.39%   |
| 5.5     | 50        | 0.37%   |
| 5.1     | 39        | 0.29%   |
| 5.2     | 29        | 0.21%   |
| 3.10    | 18        | 0.13%   |
| 4.13    | 13        | 0.1%    |
| 4.1     | 12        | 0.09%   |
| 4.20    | 10        | 0.07%   |
| 4.10    | 9         | 0.07%   |
| 4.12    | 6         | 0.04%   |
| 4.14    | 5         | 0.04%   |
| 4.8     | 3         | 0.02%   |
| 4.17    | 2         | 0.01%   |
| 6.4     | 1         | 0.01%   |
| 6       | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 12015     | 97.29%  |
| i686    | 303       | 2.45%   |
| aarch64 | 19        | 0.15%   |
| armv7l  | 13        | 0.11%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| GNOME                    | 5933      | 45.92%  |
| Unknown                  | 1829      | 14.16%  |
| KDE5                     | 1691      | 13.09%  |
| X-Cinnamon               | 1057      | 8.18%   |
| XFCE                     | 861       | 6.66%   |
| MATE                     | 365       | 2.83%   |
| KDE                      | 312       | 2.41%   |
| Cinnamon                 | 228       | 1.76%   |
| LXQt                     | 109       | 0.84%   |
| Unity                    | 90        | 0.7%    |
| Pantheon                 | 87        | 0.67%   |
| KDE4                     | 66        | 0.51%   |
| Budgie                   | 63        | 0.49%   |
| Deepin                   | 61        | 0.47%   |
| LXDE                     | 53        | 0.41%   |
| i3                       | 34        | 0.26%   |
| GNOME Flashback          | 16        | 0.12%   |
| GNOME Classic            | 14        | 0.11%   |
| awesome                  | 10        | 0.08%   |
| sway                     | 8         | 0.06%   |
| Enlightenment            | 6         | 0.05%   |
| openbox                  | 5         | 0.04%   |
| Hyprland                 | 4         | 0.03%   |
| bspwm                    | 4         | 0.03%   |
| icewm                    | 3         | 0.02%   |
| qtile                    | 2         | 0.02%   |
| xmonad                   | 1         | 0.01%   |
| Trinity                  | 1         | 0.01%   |
| jwm                      | 1         | 0.01%   |
| GNUstep                  | 1         | 0.01%   |
| GNOME:Phosh              | 1         | 0.01%   |
| fluxbox                  | 1         | 0.01%   |
| DDE                      | 1         | 0.01%   |
| 03WindowMaker            | 1         | 0.01%   |
| /usr/bin/openbox-session | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 10228     | 80.71%  |
| Wayland | 1453      | 11.47%  |
| Unknown | 902       | 7.12%   |
| Tty     | 87        | 0.69%   |
| Web     | 2         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 7873      | 61.49%  |
| SDDM    | 1463      | 11.43%  |
| GDM     | 1266      | 9.89%   |
| GDM3    | 891       | 6.96%   |
| LightDM | 682       | 5.33%   |
| TDM     | 538       | 4.2%    |
| KDM     | 66        | 0.52%   |
| XDM     | 10        | 0.08%   |
| SLiM    | 6         | 0.05%   |
| LXDM    | 3         | 0.02%   |
| SLIMSKI | 2         | 0.02%   |
| MDM     | 2         | 0.02%   |
| Ly      | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| pt_BR       | 8319      | 65.81%  |
| en_US       | 2261      | 17.89%  |
| Unknown     | 1702      | 13.47%  |
| C           | 183       | 1.45%   |
| en_GB       | 55        | 0.44%   |
| pt_PT       | 49        | 0.39%   |
| es_ES       | 19        | 0.15%   |
| en_CA       | 11        | 0.09%   |
| fr_FR       | 6         | 0.05%   |
| de_DE       | 5         | 0.04%   |
| POSIX       | 3         | 0.02%   |
| C.UTF8      | 3         | 0.02%   |
| pt_BRutf8   | 2         | 0.02%   |
| ja_JP       | 2         | 0.02%   |
| it_IT       | 2         | 0.02%   |
| en_AG       | 2         | 0.02%   |
| ru_RU       | 1         | 0.01%   |
| pt_BR~      | 1         | 0.01%   |
| pt_BR.UTF8  | 1         | 0.01%   |
| es_MX       | 1         | 0.01%   |
| es_CL       | 1         | 0.01%   |
| es_AR       | 1         | 0.01%   |
| eo          | 1         | 0.01%   |
| en_US.utf-8 | 1         | 0.01%   |
| en_US.UFT-8 | 1         | 0.01%   |
| en_IN       | 1         | 0.01%   |
| en_IE.UTF8  | 1         | 0.01%   |
| en_DK       | 1         | 0.01%   |
| en-US       | 1         | 0.01%   |
| em_US       | 1         | 0.01%   |
| de_CH       | 1         | 0.01%   |
| ar_EG       | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 7124      | 56.32%  |
| EFI  | 5526      | 43.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 9672      | 76.31%  |
| Overlay | 1024      | 8.08%   |
| Btrfs   | 964       | 7.61%   |
| Unknown | 706       | 5.57%   |
| Tmpfs   | 103       | 0.81%   |
| Xfs     | 97        | 0.77%   |
| Zfs     | 47        | 0.37%   |
| Ext3    | 21        | 0.17%   |
| Ext2    | 19        | 0.15%   |
| F2fs    | 16        | 0.13%   |
| Aufs    | 4         | 0.03%   |
| XXXXXXX | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 8212      | 64.74%  |
| GPT     | 3057      | 24.1%   |
| MBR     | 1415      | 11.16%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 11065     | 88.2%   |
| Yes       | 1480      | 11.8%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 9286      | 73.94%  |
| Yes       | 3273      | 26.06%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Dell                   | 2000      | 16.2%   |
| ASUSTek Computer       | 1636      | 13.25%  |
| Acer                   | 1437      | 11.64%  |
| Lenovo                 | 1056      | 8.56%   |
| Gigabyte Technology    | 799       | 6.47%   |
| Positivo               | 701       | 5.68%   |
| Hewlett-Packard        | 660       | 5.35%   |
| Samsung Electronics    | 631       | 5.11%   |
| Intel                  | 466       | 3.78%   |
| ASRock                 | 410       | 3.32%   |
| Unknown                | 231       | 1.87%   |
| MSI                    | 217       | 1.76%   |
| Sony                   | 158       | 1.28%   |
| Apple                  | 131       | 1.06%   |
| LG Electronics         | 128       | 1.04%   |
| Itautec                | 116       | 0.94%   |
| PCWare                 | 114       | 0.92%   |
| Semp Toshiba           | 110       | 0.89%   |
| Biostar                | 98        | 0.79%   |
| Avell High Performance | 87        | 0.7%    |
| Pegatron               | 73        | 0.59%   |
| Digibras               | 71        | 0.58%   |
| ECS                    | 62        | 0.5%    |
| OEM                    | 52        | 0.42%   |
| Multilaser             | 52        | 0.42%   |
| Philco                 | 50        | 0.41%   |
| Compaq                 | 42        | 0.34%   |
| Positivo Bahia - VAIO  | 37        | 0.3%    |
| Toshiba                | 36        | 0.29%   |
| Huanan                 | 35        | 0.28%   |
| Megaware               | 30        | 0.24%   |
| Foxconn                | 28        | 0.23%   |
| Notebook               | 27        | 0.22%   |
| Clevo                  | 25        | 0.2%    |
| Login Informatica      | 22        | 0.18%   |
| Gateway                | 21        | 0.17%   |
| Daten Tecnologia       | 20        | 0.16%   |
| Compal                 | 19        | 0.15%   |
| Google                 | 18        | 0.15%   |
| Supermicro             | 17        | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 293       | 2.37%   |
| ASUS All Series                             | 148       | 1.2%    |
| Acer Nitro AN515-54                         | 138       | 1.12%   |
| Positivo Mobile                             | 122       | 0.99%   |
| Intel H61                                   | 88        | 0.71%   |
| Acer Nitro AN515-44                         | 85        | 0.69%   |
| Samsung 340XAA/350XAA/550XAA                | 68        | 0.55%   |
| Acer Aspire A315-53                         | 68        | 0.55%   |
| Dell Inspiron 5566                          | 66        | 0.53%   |
| Lenovo IdeaPad S145-15API 81V7              | 63        | 0.51%   |
| ASUS PRIME B450M-GAMING/BR                  | 63        | 0.51%   |
| Dell Inspiron 3583                          | 59        | 0.48%   |
| Dell Inspiron 15-3567                       | 57        | 0.46%   |
| Lenovo IdeaPad 330-15IKB 81FE               | 56        | 0.45%   |
| Lenovo IdeaPad S145-15IWL 81S9              | 54        | 0.44%   |
| ASRock A320M-HD                             | 54        | 0.44%   |
| Acer Aspire A315-34                         | 54        | 0.44%   |
| Acer Nitro AN517-51                         | 52        | 0.42%   |
| ASUS PRIME A320M-K/BR                       | 51        | 0.41%   |
| ASUS M5A78L-M LX/BR                         | 51        | 0.41%   |
| Acer Aspire A515-51                         | 51        | 0.41%   |
| Lenovo IdeaPad 320-15IKB 80YH               | 49        | 0.4%    |
| Intel H55                                   | 48        | 0.39%   |
| Semp Toshiba STI                            | 45        | 0.36%   |
| Acer Nitro AN515-43                         | 45        | 0.36%   |
| Samsung 300E5M/300E5L                       | 43        | 0.35%   |
| Dell Inspiron 3442                          | 42        | 0.34%   |
| Samsung 550XDA                              | 41        | 0.33%   |
| Positivo S14CT01                            | 41        | 0.33%   |
| HP G42                                      | 41        | 0.33%   |
| Gigabyte H61M-S1                            | 39        | 0.32%   |
| Itautec Infoway                             | 38        | 0.31%   |
| Dell Inspiron N4050                         | 38        | 0.31%   |
| Dell Inspiron 3421                          | 38        | 0.31%   |
| Gigabyte A320M-S2H                          | 37        | 0.3%    |
| Acer Nitro AN515-52                         | 37        | 0.3%    |
| ASRock B450M Steel Legend                   | 36        | 0.29%   |
| Lenovo IdeaPad 3 15ALC6 82MF                | 35        | 0.28%   |
| ASUS P8H61-M LX3 R2.0                       | 35        | 0.28%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 34        | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Dell Inspiron      | 1133      | 9.18%   |
| Acer Aspire        | 925       | 7.49%   |
| Lenovo IdeaPad     | 522       | 4.23%   |
| Acer Nitro         | 403       | 3.27%   |
| Unknown            | 293       | 2.37%   |
| Dell Vostro        | 253       | 2.05%   |
| ASUS PRIME         | 241       | 1.95%   |
| Lenovo ThinkPad    | 208       | 1.69%   |
| HP Pavilion        | 198       | 1.6%    |
| Dell Latitude      | 183       | 1.48%   |
| Dell OptiPlex      | 163       | 1.32%   |
| ASUS All           | 148       | 1.2%    |
| ASUS VivoBook      | 130       | 1.05%   |
| ASUS M5A78L-M      | 123       | 1%      |
| Positivo Mobile    | 122       | 0.99%   |
| ASUS TUF           | 114       | 0.92%   |
| Itautec Infoway    | 109       | 0.88%   |
| HP Compaq          | 104       | 0.84%   |
| Intel H61          | 92        | 0.75%   |
| ASUS P8H61-M       | 87        | 0.7%    |
| Samsung 340XAA     | 68        | 0.55%   |
| Lenovo ThinkCentre | 67        | 0.54%   |
| Dell G3            | 57        | 0.46%   |
| Dell XPS           | 55        | 0.45%   |
| ASRock A320M-HD    | 55        | 0.45%   |
| ASUS ROG           | 54        | 0.44%   |
| Semp Toshiba STI   | 53        | 0.43%   |
| HP ProBook         | 49        | 0.4%    |
| Intel H55          | 48        | 0.39%   |
| Samsung RV411      | 47        | 0.38%   |
| Samsung 300E5M     | 43        | 0.35%   |
| Samsung 550XDA     | 41        | 0.33%   |
| Positivo S14CT01   | 41        | 0.33%   |
| HP G42             | 41        | 0.33%   |
| Gigabyte H61M-S1   | 39        | 0.32%   |
| Dell System        | 39        | 0.32%   |
| ASRock B450M       | 38        | 0.31%   |
| Gigabyte A320M-S2H | 37        | 0.3%    |
| Acer Predator      | 37        | 0.3%    |
| HP EliteBook       | 35        | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 1297      | 10.51%  |
| 2012    | 1235      | 10.01%  |
| 2011    | 1153      | 9.34%   |
| 2018    | 1150      | 9.32%   |
| 2017    | 993       | 8.05%   |
| 2013    | 937       | 7.59%   |
| 2010    | 783       | 6.34%   |
| 2016    | 753       | 6.1%    |
| 2014    | 733       | 5.94%   |
| 2020    | 682       | 5.53%   |
| 2009    | 527       | 4.27%   |
| 2008    | 505       | 4.09%   |
| 2021    | 503       | 4.08%   |
| 2015    | 468       | 3.79%   |
| 2007    | 292       | 2.37%   |
| 2022    | 133       | 1.08%   |
| 2006    | 100       | 0.81%   |
| Unknown | 54        | 0.44%   |
| 2005    | 26        | 0.21%   |
| 2023    | 9         | 0.07%   |
| 2004    | 9         | 0.07%   |
| 2003    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 7323      | 59.33%  |
| Desktop        | 4680      | 37.92%  |
| All in one     | 105       | 0.85%   |
| Convertible    | 93        | 0.75%   |
| Mini pc        | 48        | 0.39%   |
| Server         | 42        | 0.34%   |
| System on chip | 28        | 0.23%   |
| Tablet         | 21        | 0.17%   |
| Phone          | 2         | 0.02%   |
| Firewall       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 11175     | 89.9%   |
| Enabled  | 1256      | 10.1%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 12321     | 99.82%  |
| Yes  | 22        | 0.18%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 3401      | 27.03%  |
| 3.01-4.0        | 3252      | 25.85%  |
| 8.01-16.0       | 2197      | 17.46%  |
| 16.01-24.0      | 1948      | 15.48%  |
| 1.01-2.0        | 818       | 6.5%    |
| 32.01-64.0      | 407       | 3.24%   |
| 2.01-3.0        | 272       | 2.16%   |
| 24.01-32.0      | 121       | 0.96%   |
| 64.01-256.0     | 92        | 0.73%   |
| 0.51-1.0        | 62        | 0.49%   |
| More than 256.0 | 6         | 0.05%   |
| 0.01-0.5        | 2         | 0.02%   |
| Unknown         | 2         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 5035      | 36.88%  |
| 2.01-3.0    | 3691      | 27.04%  |
| 3.01-4.0    | 1759      | 12.88%  |
| 4.01-8.0    | 1672      | 12.25%  |
| 0.51-1.0    | 998       | 7.31%   |
| 8.01-16.0   | 323       | 2.37%   |
| 0.01-0.5    | 126       | 0.92%   |
| 16.01-24.0  | 30        | 0.22%   |
| 24.01-32.0  | 6         | 0.04%   |
| 32.01-64.0  | 5         | 0.04%   |
| Unknown     | 5         | 0.04%   |
| 64.01-256.0 | 2         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 7870      | 62.05%  |
| 2       | 3459      | 27.27%  |
| 3       | 762       | 6.01%   |
| 4       | 296       | 2.33%   |
| 0       | 122       | 0.96%   |
| 5       | 91        | 0.72%   |
| 6       | 56        | 0.44%   |
| 7       | 11        | 0.09%   |
| 8       | 7         | 0.06%   |
| 9       | 6         | 0.05%   |
| 18      | 1         | 0.01%   |
| 15      | 1         | 0.01%   |
| 10      | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 7778      | 62.51%  |
| Yes       | 4664      | 37.49%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 11301     | 91.4%   |
| No        | 1064      | 8.6%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 9041      | 72.68%  |
| No        | 3399      | 27.32%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6294      | 50.44%  |
| No        | 6183      | 49.56%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Brazil  | 12343     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Sao Paulo             | 1600      | 12.36%  |
| Rio de Janeiro        | 760       | 5.87%   |
| Brasília             | 395       | 3.05%   |
| Belo Horizonte        | 356       | 2.75%   |
| Curitiba              | 348       | 2.69%   |
| Porto Alegre          | 286       | 2.21%   |
| Fortaleza             | 277       | 2.14%   |
| Campinas              | 194       | 1.5%    |
| Salvador              | 188       | 1.45%   |
| Recife                | 164       | 1.27%   |
| Goiânia              | 148       | 1.14%   |
| Florianópolis        | 139       | 1.07%   |
| Santo André          | 138       | 1.07%   |
| Natal                 | 115       | 0.89%   |
| Osasco                | 106       | 0.82%   |
| Manaus                | 104       | 0.8%    |
| Sao José dos Campos  | 98        | 0.76%   |
| Niterói              | 98        | 0.76%   |
| Guarulhos             | 95        | 0.73%   |
| Campo Grande          | 93        | 0.72%   |
| Sao Luís             | 85        | 0.66%   |
| Belém                | 84        | 0.65%   |
| Joao Pessoa           | 83        | 0.64%   |
| Maringá              | 82        | 0.63%   |
| Sorocaba              | 80        | 0.62%   |
| Londrina              | 78        | 0.6%    |
| Joinville             | 77        | 0.59%   |
| Teresina              | 75        | 0.58%   |
| Uberlândia           | 72        | 0.56%   |
| Juiz de Fora          | 67        | 0.52%   |
| Ribeirao Preto        | 66        | 0.51%   |
| Aracaju               | 66        | 0.51%   |
| Maceió               | 65        | 0.5%    |
| Sao Jose              | 57        | 0.44%   |
| Serra                 | 56        | 0.43%   |
| Cuiabá               | 56        | 0.43%   |
| Duque de Caxias       | 55        | 0.42%   |
| Vitória              | 54        | 0.42%   |
| Sao Bernardo do Campo | 54        | 0.42%   |
| Blumenau              | 54        | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 3477      | 4467   | 20.26%  |
| Seagate                        | 3295      | 4652   | 19.2%   |
| Kingston                       | 1757      | 2264   | 10.24%  |
| Samsung Electronics            | 1673      | 2326   | 9.75%   |
| Toshiba                        | 981       | 1149   | 5.72%   |
| SanDisk                        | 875       | 1181   | 5.1%    |
| Unknown                        | 524       | 714    | 3.05%   |
| A-DATA Technology              | 483       | 613    | 2.81%   |
| China                          | 405       | 485    | 2.36%   |
| Hitachi                        | 387       | 476    | 2.25%   |
| Crucial                        | 324       | 418    | 1.89%   |
| Intel                          | 311       | 381    | 1.81%   |
| ADATA Technology               | 194       | 226    | 1.13%   |
| Silicon Motion                 | 180       | 232    | 1.05%   |
| SK hynix                       | 145       | 196    | 0.84%   |
| HGST                           | 140       | 166    | 0.82%   |
| LITEON                         | 128       | 150    | 0.75%   |
| Maxtor                         | 121       | 142    | 0.7%    |
| KingSpec                       | 117       | 133    | 0.68%   |
| Lexar                          | 96        | 112    | 0.56%   |
| Realtek Semiconductor          | 88        | 107    | 0.51%   |
| JMicron Technology             | 72        | 81     | 0.42%   |
| Phison                         | 70        | 92     | 0.41%   |
| Netac                          | 63        | 81     | 0.37%   |
| Corsair                        | 62        | 74     | 0.36%   |
| XPG                            | 60        | 75     | 0.35%   |
| Fujitsu                        | 54        | 62     | 0.31%   |
| SSSTC                          | 53        | 54     | 0.31%   |
| PNY                            | 50        | 62     | 0.29%   |
| Hewlett-Packard                | 48        | 57     | 0.28%   |
| Patriot                        | 47        | 64     | 0.27%   |
| Apple                          | 44        | 64     | 0.26%   |
| XrayDisk                       | 40        | 54     | 0.23%   |
| Solid State Storage            | 38        | 43     | 0.22%   |
| Gigabyte Technology            | 36        | 49     | 0.21%   |
| Unknown                        | 36        | 40     | 0.21%   |
| Solid State Storage Technology | 35        | 48     | 0.2%    |
| KIOXIA                         | 34        | 40     | 0.2%    |
| KingDian                       | 30        | 37     | 0.17%   |
| Micron Technology              | 29        | 32     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD     | 600       | 3.28%   |
| WDC WD10SPZX-21Z10T0 1TB            | 485       | 2.65%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 311       | 1.7%    |
| Kingston SA400S37120G 120GB SSD     | 311       | 1.7%    |
| Kingston SA400S37480G 480GB SSD     | 307       | 1.68%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 298       | 1.63%   |
| Seagate ST500DM002-1BD142 500GB     | 259       | 1.41%   |
| Seagate ST1000DM010-2EP102 1TB      | 223       | 1.22%   |
| Toshiba MQ01ABD100 1TB              | 156       | 0.85%   |
| Kingston SV300S37A120G 120GB SSD    | 147       | 0.8%    |
| Unknown MMC Card  32GB              | 145       | 0.79%   |
| WDC WD10SPZX-24Z10 1TB              | 140       | 0.76%   |
| SanDisk SSD PLUS 240GB              | 140       | 0.76%   |
| Seagate Expansion 1TB               | 127       | 0.69%   |
| Seagate ST1000LM035-1RK172 1TB      | 123       | 0.67%   |
| Samsung HD322HJ 320GB               | 123       | 0.67%   |
| WDC WD10JPVX-22JC3T0 1TB            | 112       | 0.61%   |
| Crucial CT240BX500SSD1 240GB        | 111       | 0.61%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 108       | 0.59%   |
| Samsung HD502HJ 500GB               | 108       | 0.59%   |
| Samsung HM321HI 320GB               | 104       | 0.57%   |
| Samsung HD161HJ 160GB               | 103       | 0.56%   |
| Intel NVMe SSD Drive 512GB          | 103       | 0.56%   |
| SanDisk SSD PLUS 120GB              | 102       | 0.56%   |
| Samsung HD502HI 500GB               | 101       | 0.55%   |
| Seagate ST1000DM003-1ER162 1TB      | 99        | 0.54%   |
| Seagate ST1000DM003-1CH162 1TB      | 95        | 0.52%   |
| Seagate ST9500325AS 500GB           | 94        | 0.51%   |
| A-DATA IM2S3338-128GD2 128GB SSD    | 90        | 0.49%   |
| WDC WD10SPZX-75Z10T2 1TB            | 83        | 0.45%   |
| Toshiba MQ04ABF100 1TB              | 83        | 0.45%   |
| Toshiba MQ01ABF050 500GB            | 80        | 0.44%   |
| SanDisk SDSSDA240G 240GB            | 80        | 0.44%   |
| WDC WD5000AAKX-003CA0 500GB         | 78        | 0.43%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 74        | 0.4%    |
| Seagate ST3500418AS 500GB           | 73        | 0.4%    |
| SanDisk NVMe SSD Drive 512GB        | 73        | 0.4%    |
| Intel SSDPEKKW256G7 256GB           | 71        | 0.39%   |
| WDC WD10JPVX-75JC3T0 1TB            | 69        | 0.38%   |
| WDC WD10EARS-00Y5B1 1TB             | 69        | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3279      | 4617   | 35.44%  |
| WDC                 | 3095      | 3876   | 33.46%  |
| Samsung Electronics | 1145      | 1500   | 12.38%  |
| Toshiba             | 928       | 1085   | 10.03%  |
| Hitachi             | 387       | 476    | 4.18%   |
| HGST                | 140       | 166    | 1.51%   |
| Maxtor              | 112       | 131    | 1.21%   |
| Fujitsu             | 53        | 60     | 0.57%   |
| Unknown             | 34        | 39     | 0.37%   |
| Apple               | 18        | 30     | 0.19%   |
| Hewlett-Packard     | 17        | 20     | 0.18%   |
| ExcelStor           | 11        | 12     | 0.12%   |
| SAGE                | 7         | 12     | 0.08%   |
| JMicron Technology  | 5         | 6      | 0.05%   |
| HPE                 | 5         | 5      | 0.05%   |
| USB3.0              | 3         | 3      | 0.03%   |
| Phison              | 1         | 1      | 0.01%   |
| MDT                 | 1         | 1      | 0.01%   |
| Maxtor 6            | 1         | 1      | 0.01%   |
| Lenovo              | 1         | 1      | 0.01%   |
| Intenso             | 1         | 1      | 0.01%   |
| IBM/Hitachi         | 1         | 2      | 0.01%   |
| IBM                 | 1         | 3      | 0.01%   |
| HGST HTS            | 1         | 1      | 0.01%   |
| FEASSO              | 1         | 2      | 0.01%   |
| CLOVER              | 1         | 1      | 0.01%   |
| China               | 1         | 1      | 0.01%   |
| Unknown             | 1         | 1      | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 1678      | 2149   | 32.6%   |
| SanDisk             | 645       | 893    | 12.53%  |
| China               | 404       | 484    | 7.85%   |
| WDC                 | 381       | 478    | 7.4%    |
| Samsung Electronics | 340       | 530    | 6.6%    |
| Crucial             | 309       | 399    | 6%      |
| A-DATA Technology   | 273       | 333    | 5.3%    |
| LITEON              | 114       | 135    | 2.21%   |
| KingSpec            | 112       | 128    | 2.18%   |
| Lexar               | 93        | 109    | 1.81%   |
| Intel               | 52        | 64     | 1.01%   |
| Corsair             | 50        | 59     | 0.97%   |
| Netac               | 49        | 62     | 0.95%   |
| PNY                 | 48        | 60     | 0.93%   |
| Patriot             | 44        | 60     | 0.85%   |
| KingDian            | 29        | 36     | 0.56%   |
| Gigabyte Technology | 29        | 41     | 0.56%   |
| Smart               | 27        | 31     | 0.52%   |
| Apple               | 24        | 30     | 0.47%   |
| Hewlett-Packard     | 23        | 27     | 0.45%   |
| XrayDisk            | 22        | 26     | 0.43%   |
| Unknown             | 22        | 24     | 0.43%   |
| SK hynix            | 22        | 26     | 0.43%   |
| Toshiba             | 21        | 25     | 0.41%   |
| Unknown             | 20        | 21     | 0.39%   |
| Seagate             | 18        | 22     | 0.35%   |
| OCZ                 | 15        | 16     | 0.29%   |
| BHT                 | 14        | 19     | 0.27%   |
| LITEONIT            | 13        | 20     | 0.25%   |
| Micron Technology   | 11        | 14     | 0.21%   |
| Team                | 10        | 24     | 0.19%   |
| HUSKY               | 10        | 12     | 0.19%   |
| Win Memory          | 9         | 10     | 0.17%   |
| Maxtor              | 9         | 11     | 0.17%   |
| walram              | 8         | 8      | 0.16%   |
| RZX                 | 7         | 14     | 0.14%   |
| Plextor             | 7         | 8      | 0.14%   |
| Pichau              | 7         | 7      | 0.14%   |
| HS-SSD-C100         | 7         | 7      | 0.14%   |
| Colorful            | 7         | 8      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 8211      | 12054  | 52.71%  |
| SSD     | 4650      | 6630   | 29.85%  |
| NVMe    | 2159      | 2928   | 13.86%  |
| MMC     | 403       | 573    | 2.59%   |
| Unknown | 156       | 212    | 1%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 10769     | 18421  | 78.69%  |
| NVMe | 2110      | 2858   | 15.42%  |
| SAS  | 404       | 545    | 2.95%   |
| MMC  | 403       | 573    | 2.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 8175      | 12269  | 63.64%  |
| 0.51-1.0        | 3958      | 5340   | 30.81%  |
| 1.01-2.0        | 495       | 685    | 3.85%   |
| 3.01-4.0        | 84        | 195    | 0.65%   |
| 2.01-3.0        | 70        | 102    | 0.54%   |
| 4.01-10.0       | 57        | 84     | 0.44%   |
| 10.01-20.0      | 5         | 7      | 0.04%   |
| More than 100.0 | 1         | 1      | 0.01%   |
| 0               | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 3646      | 27.87%  |
| 251-500        | 3154      | 24.11%  |
| 501-1000       | 2131      | 16.29%  |
| 1-20           | 1024      | 7.83%   |
| 1001-2000      | 961       | 7.34%   |
| 51-100         | 828       | 6.33%   |
| 21-50          | 600       | 4.59%   |
| 2001-3000      | 264       | 2.02%   |
| Unknown        | 241       | 1.84%   |
| More than 3000 | 235       | 1.8%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 5151      | 38.1%   |
| 21-50          | 2871      | 21.24%  |
| 101-250        | 1692      | 12.52%  |
| 51-100         | 1642      | 12.15%  |
| 251-500        | 899       | 6.65%   |
| 501-1000       | 622       | 4.6%    |
| 1001-2000      | 268       | 1.98%   |
| Unknown        | 241       | 1.78%   |
| 2001-3000      | 68        | 0.5%    |
| More than 3000 | 64        | 0.47%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 46        | 50     | 3.4%    |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 43        | 49     | 3.18%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 30        | 32     | 2.22%   |
| WDC WD5000AAKX-003CA0 500GB         | 25        | 25     | 1.85%   |
| Seagate ST9500325AS 500GB           | 25        | 27     | 1.85%   |
| Samsung Electronics HD322HJ 320GB   | 23        | 32     | 1.7%    |
| Samsung Electronics HD161HJ 160GB   | 21        | 22     | 1.55%   |
| Samsung Electronics HD502HI 500GB   | 19        | 23     | 1.41%   |
| Seagate ST1000LM035-1RK172 1TB      | 15        | 16     | 1.11%   |
| Samsung Electronics HD502HJ 500GB   | 15        | 15     | 1.11%   |
| Toshiba MQ01ABD100 1TB              | 13        | 13     | 0.96%   |
| Toshiba MQ01ABD050 500GB            | 13        | 13     | 0.96%   |
| Kingston SV300S37A120G 120GB SSD    | 13        | 14     | 0.96%   |
| WDC WD10EARS-00Y5B1 1TB             | 12        | 14     | 0.89%   |
| Seagate ST9320325AS 320GB           | 12        | 12     | 0.89%   |
| Seagate ST1000DM010-2EP102 1TB      | 12        | 15     | 0.89%   |
| Seagate ST500LT012-9WS142 500GB     | 11        | 13     | 0.81%   |
| Seagate ST3500418AS 500GB           | 11        | 16     | 0.81%   |
| WDC WD3200AAJS-00L7A0 320GB         | 10        | 10     | 0.74%   |
| Samsung Electronics HM321HI 320GB   | 10        | 10     | 0.74%   |
| Maxtor STM3160215AS 160GB           | 10        | 11     | 0.74%   |
| Seagate ST3320418AS 320GB           | 9         | 13     | 0.67%   |
| Seagate ST31000524AS 1TB            | 9         | 9      | 0.67%   |
| Samsung Electronics HD250HJ 250GB   | 9         | 10     | 0.67%   |
| Samsung Electronics HD080HJ/ 80GB   | 9         | 11     | 0.67%   |
| Kingston SA400S37480G 480GB SSD     | 9         | 10     | 0.67%   |
| Kingston SA400S37240G 240GB SSD     | 9         | 9      | 0.67%   |
| Seagate ST1000DM003-1CH162 1TB      | 8         | 10     | 0.59%   |
| Samsung Electronics HD103SJ 1TB     | 8         | 10     | 0.59%   |
| Samsung Electronics HD103SI 1TB     | 8         | 9      | 0.59%   |
| Kingston SA400S37120G 120GB SSD     | 8         | 12     | 0.59%   |
| China SSD 120GB                     | 8         | 8      | 0.59%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 7         | 8      | 0.52%   |
| Toshiba MQ02ABD100H 1TB             | 7         | 10     | 0.52%   |
| Toshiba MQ01ABF050 500GB            | 7         | 7      | 0.52%   |
| Toshiba MQ01ABD032 320GB            | 7         | 8      | 0.52%   |
| Seagate ST500LT012-1DG142 500GB     | 7         | 8      | 0.52%   |
| Seagate ST3500413AS 500GB           | 7         | 8      | 0.52%   |
| Seagate ST3500312CS 500GB           | 7         | 7      | 0.52%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 7         | 8      | 0.52%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 423       | 506    | 32.77%  |
| WDC                   | 288       | 330    | 22.31%  |
| Samsung Electronics   | 193       | 242    | 14.95%  |
| Toshiba               | 108       | 118    | 8.37%   |
| Hitachi               | 67        | 71     | 5.19%   |
| Kingston              | 50        | 58     | 3.87%   |
| China                 | 26        | 28     | 2.01%   |
| Maxtor                | 21        | 23     | 1.63%   |
| SanDisk               | 20        | 21     | 1.55%   |
| HGST                  | 11        | 11     | 0.85%   |
| A-DATA Technology     | 11        | 12     | 0.85%   |
| XPG                   | 7         | 7      | 0.54%   |
| Intel                 | 6         | 6      | 0.46%   |
| Fujitsu               | 5         | 6      | 0.39%   |
| PNY                   | 4         | 6      | 0.31%   |
| LITEON                | 4         | 4      | 0.31%   |
| Crucial               | 4         | 4      | 0.31%   |
| OCZ                   | 3         | 3      | 0.23%   |
| KingSpec              | 3         | 3      | 0.23%   |
| Apple                 | 3         | 3      | 0.23%   |
| Unknown               | 3         | 3      | 0.23%   |
| XrayDisk              | 2         | 3      | 0.15%   |
| walram                | 2         | 2      | 0.15%   |
| Netac                 | 2         | 2      | 0.15%   |
| Hewlett-Packard       | 2         | 2      | 0.15%   |
| ExcelStor             | 2         | 3      | 0.15%   |
| Corsair               | 2         | 2      | 0.15%   |
| Team                  | 1         | 1      | 0.08%   |
| SSSTC                 | 1         | 1      | 0.08%   |
| SK hynix              | 1         | 1      | 0.08%   |
| Silicon Motion        | 1         | 1      | 0.08%   |
| ShiJi                 | 1         | 3      | 0.08%   |
| Realtek Semiconductor | 1         | 1      | 0.08%   |
| QIANGHE               | 1         | 1      | 0.08%   |
| Plextor               | 1         | 1      | 0.08%   |
| OCZ-VERTEX3           | 1         | 1      | 0.08%   |
| Mushkin               | 1         | 1      | 0.08%   |
| Micron Technology     | 1         | 1      | 0.08%   |
| LITEONIT              | 1         | 2      | 0.08%   |
| Kross Elegance        | 1         | 1      | 0.08%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 423       | 506    | 38.38%  |
| WDC                 | 274       | 314    | 24.86%  |
| Samsung Electronics | 187       | 236    | 16.97%  |
| Toshiba             | 107       | 117    | 9.71%   |
| Hitachi             | 67        | 71     | 6.08%   |
| Maxtor              | 21        | 23     | 1.91%   |
| HGST                | 11        | 11     | 1%      |
| Fujitsu             | 5         | 6      | 0.45%   |
| Hewlett-Packard     | 2         | 2      | 0.18%   |
| ExcelStor           | 2         | 3      | 0.18%   |
| Apple               | 2         | 2      | 0.18%   |
| FEASSO              | 1         | 2      | 0.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1010      | 1293   | 84.24%  |
| SSD  | 162       | 179    | 13.51%  |
| NVMe | 27        | 30     | 2.25%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                  | 4         | 4      | 13.79%  |
| Samsung Electronics HM321HI 320GB                | 2         | 2      | 6.9%    |
| Samsung Electronics HD502HJ 500GB                | 2         | 4      | 6.9%    |
| WDC WD5000AAKS-00C8A0 500GB                      | 1         | 1      | 3.45%   |
| WDC WD3200BPVT-00JJ5T0 320GB                     | 1         | 1      | 3.45%   |
| WDC WD1600BEVT-22ZCT0 160GB                      | 1         | 1      | 3.45%   |
| WDC WD10SPZX-75Z10T1 1TB                         | 1         | 1      | 3.45%   |
| WDC WD10SPZX-22Z10T0 1TB                         | 1         | 1      | 3.45%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 3.45%   |
| Toshiba MK5065GSXN 500GB                         | 1         | 1      | 3.45%   |
| Toshiba DT01ACA100 1TB                           | 1         | 1      | 3.45%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 3.45%   |
| Seagate ST3320613AS 320GB                        | 1         | 1      | 3.45%   |
| Seagate ST31000528AS 1TB                         | 1         | 1      | 3.45%   |
| Seagate ST31000340NS 1TB                         | 1         | 1      | 3.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 3.45%   |
| Samsung Electronics MZNTY128HDHP-000H1 128GB SSD | 1         | 1      | 3.45%   |
| Samsung Electronics HM320JI 320GB                | 1         | 1      | 3.45%   |
| Samsung Electronics HM250HI 250GB                | 1         | 1      | 3.45%   |
| Samsung Electronics HD322GJ 320GB                | 1         | 1      | 3.45%   |
| Samsung Electronics HD103SJ 1TB                  | 1         | 1      | 3.45%   |
| Samsung Electronics HD080HJ/ 80GB                | 1         | 1      | 3.45%   |
| Maxtor STM380215AS 80GB                          | 1         | 1      | 3.45%   |
| Hitachi HDS721050DLE630 500GB                    | 1         | 1      | 3.45%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 12     | 34.48%  |
| Seagate             | 9         | 9      | 31.03%  |
| WDC                 | 5         | 5      | 17.24%  |
| Toshiba             | 3         | 3      | 10.34%  |
| Maxtor              | 1         | 1      | 3.45%   |
| Hitachi             | 1         | 1      | 3.45%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 8713      | 15538  | 66.08%  |
| Works    | 3283      | 5325   | 24.9%   |
| Malfunc  | 1159      | 1502   | 8.79%   |
| Failed   | 29        | 31     | 0.22%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 9374      | 66.41%  |
| AMD                              | 2021      | 14.32%  |
| ADATA Technology                 | 432       | 3.06%   |
| SanDisk                          | 294       | 2.08%   |
| Nvidia                           | 264       | 1.87%   |
| Samsung Electronics              | 236       | 1.67%   |
| Silicon Motion                   | 204       | 1.45%   |
| Solid State Storage Technology   | 137       | 0.97%   |
| Realtek Semiconductor            | 122       | 0.86%   |
| SK hynix                         | 116       | 0.82%   |
| Kingston Technology Company      | 113       | 0.8%    |
| Phison Electronics               | 109       | 0.77%   |
| Silicon Integrated Systems [SiS] | 102       | 0.72%   |
| Marvell Technology Group         | 91        | 0.64%   |
| JMicron Technology               | 83        | 0.59%   |
| VIA Technologies                 | 74        | 0.52%   |
| ASMedia Technology               | 74        | 0.52%   |
| Micron/Crucial Technology        | 40        | 0.28%   |
| KIOXIA                           | 33        | 0.23%   |
| Toshiba America Info Systems     | 26        | 0.18%   |
| Lite-On Technology               | 26        | 0.18%   |
| LSI Logic / Symbios Logic        | 24        | 0.17%   |
| MAXIO Technology (Hangzhou)      | 22        | 0.16%   |
| Micron Technology                | 18        | 0.13%   |
| Broadcom / LSI                   | 13        | 0.09%   |
| Union Memory (Shenzhen)          | 9         | 0.06%   |
| Netac Technology                 | 7         | 0.05%   |
| Silicon Image                    | 6         | 0.04%   |
| Shenzhen Longsys Electronics     | 6         | 0.04%   |
| Beijing Starblaze Technology     | 6         | 0.04%   |
| Seagate Technology               | 5         | 0.04%   |
| OCZ Technology Group             | 4         | 0.03%   |
| Adaptec                          | 4         | 0.03%   |
| INNOGRIT                         | 3         | 0.02%   |
| Hewlett-Packard                  | 3         | 0.02%   |
| Apple                            | 3         | 0.02%   |
| TenaFe                           | 2         | 0.01%   |
| Lenovo                           | 2         | 0.01%   |
| Dell                             | 2         | 0.01%   |
| ULi Electronics                  | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 1231      | 7.15%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1026      | 5.96%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 867       | 5.03%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 650       | 3.77%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 599       | 3.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 492       | 2.86%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 465       | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 427       | 2.48%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 408       | 2.37%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 395       | 2.29%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 338       | 1.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 328       | 1.9%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 315       | 1.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 310       | 1.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 259       | 1.5%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 252       | 1.46%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 252       | 1.46%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 249       | 1.45%   |
| AMD FCH SATA Controller D                                                               | 238       | 1.38%   |
| AMD 400 Series Chipset SATA Controller                                                  | 229       | 1.33%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 219       | 1.27%   |
| Intel PROSet/Wireless WiFi Software extension                                           | 206       | 1.2%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 184       | 1.07%   |
| Nvidia MCP61 SATA Controller                                                            | 183       | 1.06%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 181       | 1.05%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 180       | 1.05%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 161       | 0.93%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 159       | 0.92%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 154       | 0.89%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 153       | 0.89%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 152       | 0.88%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 151       | 0.88%   |
| Nvidia MCP61 IDE                                                                        | 150       | 0.87%   |
| ADATA Non-Volatile memory controller                                                    | 147       | 0.85%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 146       | 0.85%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 145       | 0.84%   |
| ADATA IM2P33F8ABR1 NVMe SSD                                                             | 144       | 0.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 134       | 0.78%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 134       | 0.78%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 132       | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 9336      | 62.98%  |
| IDE  | 2433      | 16.41%  |
| NVMe | 2123      | 14.32%  |
| RAID | 907       | 6.12%   |
| SCSI | 16        | 0.11%   |
| SAS  | 9         | 0.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 10011     | 81.11%  |
| AMD          | 2295      | 18.59%  |
| ARM          | 30        | 0.24%   |
| CentaurHauls | 5         | 0.04%   |
| Qualcomm     | 1         | 0.01%   |
| Unknown      | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 269       | 2.17%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 165       | 1.33%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 149       | 1.2%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 148       | 1.2%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 141       | 1.14%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 134       | 1.08%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 133       | 1.07%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 127       | 1.03%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 125       | 1.01%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 122       | 0.99%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 112       | 0.9%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 100       | 0.81%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 99        | 0.8%    |
| AMD FX-6300 Six-Core Processor                | 98        | 0.79%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 95        | 0.77%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 94        | 0.76%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 92        | 0.74%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 92        | 0.74%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 92        | 0.74%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 90        | 0.73%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 88        | 0.71%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 86        | 0.69%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 85        | 0.69%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 84        | 0.68%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 81        | 0.65%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 80        | 0.65%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 79        | 0.64%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 79        | 0.64%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 76        | 0.61%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 76        | 0.61%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 74        | 0.6%    |
| Intel Core i5-3330 CPU @ 3.00GHz              | 70        | 0.57%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 70        | 0.57%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 70        | 0.57%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 69        | 0.56%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 67        | 0.54%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 67        | 0.54%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 65        | 0.53%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 64        | 0.52%   |
| Intel Core i5 CPU 650 @ 3.20GHz               | 63        | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 2997      | 24.23%  |
| Intel Core i7           | 1937      | 15.66%  |
| Intel Core i3           | 1711      | 13.83%  |
| Intel Celeron           | 837       | 6.77%   |
| AMD Ryzen 5             | 575       | 4.65%   |
| Intel Core 2 Duo        | 530       | 4.28%   |
| Other                   | 390       | 3.15%   |
| AMD Ryzen 7             | 337       | 2.72%   |
| Intel Pentium Dual-Core | 330       | 2.67%   |
| Intel Atom              | 315       | 2.55%   |
| Intel Pentium           | 289       | 2.34%   |
| AMD FX                  | 274       | 2.21%   |
| Intel Xeon              | 249       | 2.01%   |
| Intel Pentium Dual      | 148       | 1.2%    |
| AMD Ryzen 3             | 111       | 0.9%    |
| Intel Core 2 Quad       | 100       | 0.81%   |
| AMD Phenom II X4        | 80        | 0.65%   |
| AMD Athlon II X2        | 74        | 0.6%    |
| AMD A4                  | 65        | 0.53%   |
| AMD E                   | 59        | 0.48%   |
| AMD A10                 | 59        | 0.48%   |
| Intel Core 2            | 56        | 0.45%   |
| AMD A6                  | 54        | 0.44%   |
| AMD Athlon 64 X2        | 50        | 0.4%    |
| AMD A8                  | 49        | 0.4%    |
| AMD Athlon              | 48        | 0.39%   |
| AMD Ryzen 9             | 47        | 0.38%   |
| Intel Genuine           | 42        | 0.34%   |
| AMD C-60                | 42        | 0.34%   |
| AMD E1                  | 35        | 0.28%   |
| AMD Sempron             | 32        | 0.26%   |
| AMD Phenom II X6        | 30        | 0.24%   |
| Intel Pentium 4         | 29        | 0.23%   |
| AMD C-70                | 27        | 0.22%   |
| Intel Pentium Gold      | 24        | 0.19%   |
| Intel Core i9           | 23        | 0.19%   |
| AMD C-50                | 20        | 0.16%   |
| AMD Phenom II X2        | 19        | 0.15%   |
| AMD Athlon II X4        | 18        | 0.15%   |
| Intel Celeron Dual-Core | 17        | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 6518      | 52.69%  |
| 4       | 3920      | 31.69%  |
| 6       | 852       | 6.89%   |
| 8       | 411       | 3.32%   |
| 1       | 345       | 2.79%   |
| 3       | 146       | 1.18%   |
| 12      | 71        | 0.57%   |
| 10      | 36        | 0.29%   |
| 16      | 19        | 0.15%   |
| 14      | 19        | 0.15%   |
| Unknown | 16        | 0.13%   |
| 24      | 6         | 0.05%   |
| 20      | 6         | 0.05%   |
| 5       | 2         | 0.02%   |
| 32      | 1         | 0.01%   |
| 28      | 1         | 0.01%   |
| 22      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 12297     | 99.62%  |
| 2       | 43        | 0.35%   |
| Unknown | 3         | 0.02%   |
| 4       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 8017      | 64.86%  |
| 1       | 4324      | 34.98%  |
| Unknown | 16        | 0.13%   |
| 4       | 2         | 0.02%   |
| 8       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 11756     | 94.72%  |
| Unknown        | 545       | 4.39%   |
| 32-bit         | 62        | 0.5%    |
| 64-bit         | 48        | 0.39%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2720      | 21.22%  |
| 0x306a9    | 1016      | 7.93%   |
| 0x206a7    | 995       | 7.76%   |
| 0x1067a    | 653       | 5.09%   |
| 0x806e9    | 419       | 3.27%   |
| 0x906ea    | 415       | 3.24%   |
| 0x306c3    | 379       | 2.96%   |
| 0x20655    | 371       | 2.89%   |
| 0x40651    | 346       | 2.7%    |
| 0x806ec    | 331       | 2.58%   |
| 0x306d4    | 288       | 2.25%   |
| 0x406e3    | 278       | 2.17%   |
| 0x806ea    | 253       | 1.97%   |
| 0x6fd      | 250       | 1.95%   |
| 0x906e9    | 219       | 1.71%   |
| 0x806c1    | 193       | 1.51%   |
| 0x406c4    | 185       | 1.44%   |
| 0x08108109 | 170       | 1.33%   |
| 0x06000852 | 155       | 1.21%   |
| 0x010000c8 | 134       | 1.05%   |
| 0x30678    | 129       | 1.01%   |
| 0x05000119 | 97        | 0.76%   |
| 0x20652    | 96        | 0.75%   |
| 0x906ed    | 87        | 0.68%   |
| 0x08600103 | 87        | 0.68%   |
| 0x08108102 | 83        | 0.65%   |
| 0x0800820d | 83        | 0.65%   |
| 0x10676    | 82        | 0.64%   |
| 0x706e5    | 81        | 0.63%   |
| 0x706a1    | 77        | 0.6%    |
| 0x506e3    | 77        | 0.6%    |
| 0x08701021 | 76        | 0.59%   |
| 0x6fb      | 65        | 0.51%   |
| 0x106ca    | 63        | 0.49%   |
| 0x706a8    | 60        | 0.47%   |
| 0x406c3    | 60        | 0.47%   |
| 0x806eb    | 58        | 0.45%   |
| 0x306f2    | 57        | 0.44%   |
| 0x08701013 | 55        | 0.43%   |
| 0x0600611a | 54        | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 2240      | 18.13%  |
| IvyBridge        | 1280      | 10.36%  |
| SandyBridge      | 1211      | 9.8%    |
| Haswell          | 945       | 7.65%   |
| Penryn           | 858       | 6.94%   |
| Westmere         | 574       | 4.65%   |
| Core             | 482       | 3.9%    |
| Silvermont       | 474       | 3.84%   |
| Skylake          | 450       | 3.64%   |
| Zen+             | 425       | 3.44%   |
| Broadwell        | 353       | 2.86%   |
| K10              | 306       | 2.48%   |
| Piledriver       | 293       | 2.37%   |
| Zen 2            | 277       | 2.24%   |
| TigerLake        | 255       | 2.06%   |
| Zen              | 237       | 1.92%   |
| Bobcat           | 174       | 1.41%   |
| CometLake        | 171       | 1.38%   |
| Goldmont plus    | 161       | 1.3%    |
| Unknown          | 159       | 1.29%   |
| IceLake          | 135       | 1.09%   |
| Bonnell          | 129       | 1.04%   |
| Zen 3            | 121       | 0.98%   |
| K8 Hammer        | 110       | 0.89%   |
| Excavator        | 85        | 0.69%   |
| Nehalem          | 81        | 0.66%   |
| NetBurst         | 51        | 0.41%   |
| Goldmont         | 49        | 0.4%    |
| Bulldozer        | 47        | 0.38%   |
| K10 Llano        | 46        | 0.37%   |
| Steamroller      | 43        | 0.35%   |
| Alderlake Hybrid | 42        | 0.34%   |
| Jaguar           | 40        | 0.32%   |
| P6               | 26        | 0.21%   |
| K8 & K10 hybrid  | 11        | 0.09%   |
| Puma             | 7         | 0.06%   |
| Tremont          | 6         | 0.05%   |
| K6               | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 8313      | 56.35%  |
| Nvidia                           | 3626      | 24.58%  |
| AMD                              | 2615      | 17.73%  |
| Silicon Integrated Systems [SiS] | 99        | 0.67%   |
| VIA Technologies                 | 56        | 0.38%   |
| Matrox Electronics Systems       | 26        | 0.18%   |
| ASPEED Technology                | 8         | 0.05%   |
| Silicon Motion                   | 4         | 0.03%   |
| ATI Technologies                 | 4         | 0.03%   |
| S3 Graphics                      | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1004      | 6.65%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 756       | 5%      |
| Intel HD Graphics 620                                                                    | 534       | 3.54%   |
| Intel Core Processor Integrated Graphics Controller                                      | 493       | 3.26%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 411       | 2.72%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 382       | 2.53%   |
| Intel HD Graphics 5500                                                                   | 319       | 2.11%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 297       | 1.97%   |
| Intel UHD Graphics 620                                                                   | 296       | 1.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 295       | 1.95%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 294       | 1.95%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 288       | 1.91%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 286       | 1.89%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 264       | 1.75%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 252       | 1.67%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 215       | 1.42%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 197       | 1.3%    |
| Intel HD Graphics 630                                                                    | 182       | 1.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 181       | 1.2%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 179       | 1.19%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 171       | 1.13%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 166       | 1.1%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 162       | 1.07%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 161       | 1.07%   |
| Nvidia GT218 [GeForce 210]                                                               | 150       | 0.99%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 146       | 0.97%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 138       | 0.91%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 138       | 0.91%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 110       | 0.73%   |
| AMD Renoir                                                                               | 110       | 0.73%   |
| Nvidia TU117M                                                                            | 103       | 0.68%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 102       | 0.68%   |
| Nvidia GP108M [GeForce MX150]                                                            | 98        | 0.65%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 98        | 0.65%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 95        | 0.63%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 93        | 0.62%   |
| Nvidia GM108M [GeForce MX110]                                                            | 93        | 0.62%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 90        | 0.6%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 89        | 0.59%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 88        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 6121      | 49.26%  |
| 1 x AMD                 | 1915      | 15.41%  |
| 1 x Nvidia              | 1736      | 13.97%  |
| Intel + Nvidia          | 1682      | 13.54%  |
| Intel + AMD             | 420       | 3.38%   |
| AMD + Nvidia            | 175       | 1.41%   |
| 2 x AMD                 | 112       | 0.9%    |
| 1 x SiS                 | 99        | 0.8%    |
| 1 x VIA                 | 55        | 0.44%   |
| Other                   | 34        | 0.27%   |
| 1 x Matrox              | 25        | 0.2%    |
| 2 x Nvidia              | 18        | 0.14%   |
| 2 x Intel               | 17        | 0.14%   |
| 1 x ASPEED              | 7         | 0.06%   |
| Intel + Silicon Motion  | 2         | 0.02%   |
| 1 x Silicon Motion      | 1         | 0.01%   |
| 1 x S3 Graphics         | 1         | 0.01%   |
| Nvidia + Silicon Motion | 1         | 0.01%   |
| Nvidia + ASPEED         | 1         | 0.01%   |
| Intel + 2 x AMD         | 1         | 0.01%   |
| AMD + 2 x Nvidia        | 1         | 0.01%   |
| AMD + Matrox            | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 9915      | 79.34%  |
| Proprietary | 2102      | 16.82%  |
| Unknown     | 480       | 3.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 7689      | 60.73%  |
| 1.01-2.0   | 1784      | 14.09%  |
| 0.01-0.5   | 1077      | 8.51%   |
| 0.51-1.0   | 821       | 6.48%   |
| 3.01-4.0   | 797       | 6.29%   |
| 7.01-8.0   | 209       | 1.65%   |
| 5.01-6.0   | 192       | 1.52%   |
| 2.01-3.0   | 63        | 0.5%    |
| 8.01-16.0  | 25        | 0.2%    |
| 4.01-5.0   | 2         | 0.02%   |
| 16.01-24.0 | 2         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 1919      | 14.44%  |
| Goldstar                | 1734      | 13.05%  |
| BOE                     | 1599      | 12.04%  |
| AU Optronics            | 1546      | 11.64%  |
| Chimei Innolux          | 1246      | 9.38%   |
| LG Display              | 1160      | 8.73%   |
| AOC                     | 884       | 6.65%   |
| Dell                    | 548       | 4.12%   |
| Philips                 | 358       | 2.69%   |
| Acer                    | 212       | 1.6%    |
| Chi Mei Optoelectronics | 161       | 1.21%   |
| LG Electronics          | 156       | 1.17%   |
| Hewlett-Packard         | 136       | 1.02%   |
| InfoVision              | 125       | 0.94%   |
| PANDA                   | 119       | 0.9%    |
| Apple                   | 114       | 0.86%   |
| Lenovo                  | 110       | 0.83%   |
| Sony                    | 89        | 0.67%   |
| BenQ                    | 68        | 0.51%   |
| Unknown                 | 63        | 0.47%   |
| HannStar                | 49        | 0.37%   |
| CPT                     | 49        | 0.37%   |
| RTK                     | 48        | 0.36%   |
| Positivo                | 46        | 0.35%   |
| LG Philips              | 38        | 0.29%   |
| Panasonic               | 35        | 0.26%   |
| SLD                     | 32        | 0.24%   |
| InnoLux Display         | 32        | 0.24%   |
| ASUSTek Computer        | 31        | 0.23%   |
| Ancor Communications    | 27        | 0.2%    |
| Sharp                   | 26        | 0.2%    |
| GDH                     | 26        | 0.2%    |
| Unknown (XXX)           | 20        | 0.15%   |
| NCS                     | 20        | 0.15%   |
| MTD                     | 20        | 0.15%   |
| Toshiba                 | 19        | 0.14%   |
| VIE                     | 17        | 0.13%   |
| HB@                     | 17        | 0.13%   |
| STA                     | 16        | 0.12%   |
| SKY                     | 16        | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 177       | 1.3%    |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 123       | 0.9%    |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 119       | 0.87%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 115       | 0.84%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 112       | 0.82%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch | 103       | 0.75%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 103       | 0.75%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 101       | 0.74%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 100       | 0.73%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 92        | 0.67%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 82        | 0.6%    |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 76        | 0.56%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 75        | 0.55%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 75        | 0.55%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                       | 73        | 0.53%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 72        | 0.53%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch        | 70        | 0.51%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                 | 67        | 0.49%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 66        | 0.48%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                     | 65        | 0.48%   |
| BOE LCD Monitor BOE0818 1920x1080 344x194mm 15.5-inch                | 63        | 0.46%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch          | 61        | 0.45%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 59        | 0.43%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch        | 58        | 0.42%   |
| BOE LCD Monitor BOE07CE 1366x768 344x193mm 15.5-inch                 | 57        | 0.42%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 56        | 0.41%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch             | 55        | 0.4%    |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                | 55        | 0.4%    |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch | 54        | 0.4%    |
| InfoVision LCD Monitor IVO057A 1366x768 309x174mm 14.0-inch          | 54        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 54        | 0.4%    |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch      | 49        | 0.36%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 48        | 0.35%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch         | 47        | 0.34%   |
| AOC F19 AOC1900 1366x768 410x230mm 18.5-inch                         | 47        | 0.34%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 46        | 0.34%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                 | 46        | 0.34%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch        | 45        | 0.33%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch          | 42        | 0.31%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch               | 42        | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 5168      | 39.96%  |
| 1920x1080 (FHD)    | 4073      | 31.49%  |
| 1600x900 (HD+)     | 541       | 4.18%   |
| 1440x900 (WXGA+)   | 422       | 3.26%   |
| 2560x1080          | 417       | 3.22%   |
| 1360x768           | 359       | 2.78%   |
| 1280x1024 (SXGA)   | 349       | 2.7%    |
| 1280x800 (WXGA)    | 316       | 2.44%   |
| 3840x2160 (4K)     | 309       | 2.39%   |
| 1680x1050 (WSXGA+) | 197       | 1.52%   |
| 2560x1440 (QHD)    | 132       | 1.02%   |
| 1024x768 (XGA)     | 122       | 0.94%   |
| Unknown            | 106       | 0.82%   |
| 1920x1200 (WUXGA)  | 69        | 0.53%   |
| 1280x720 (HD)      | 49        | 0.38%   |
| 1024x600           | 43        | 0.33%   |
| 1920x540           | 38        | 0.29%   |
| 3840x1080          | 29        | 0.22%   |
| 2288x1287          | 23        | 0.18%   |
| 3440x1440          | 18        | 0.14%   |
| 2560x1600          | 17        | 0.13%   |
| 1152x864           | 9         | 0.07%   |
| 1600x1200          | 7         | 0.05%   |
| 800x1280           | 6         | 0.05%   |
| 5760x1080          | 6         | 0.05%   |
| 4480x1080          | 6         | 0.05%   |
| 3840x2400          | 6         | 0.05%   |
| 3360x1080          | 5         | 0.04%   |
| 3286x1080          | 5         | 0.04%   |
| 3200x1080          | 5         | 0.04%   |
| 1280x960           | 5         | 0.04%   |
| 2880x1800          | 4         | 0.03%   |
| 2736x1824          | 4         | 0.03%   |
| 3520x1080          | 3         | 0.02%   |
| 3200x1800 (QHD+)   | 3         | 0.02%   |
| 2732x768           | 3         | 0.02%   |
| 6400x1080          | 2         | 0.02%   |
| 3600x1080          | 2         | 0.02%   |
| 3360x1050          | 2         | 0.02%   |
| 2800x900           | 2         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 3885      | 29.14%  |
| 14      | 1612      | 12.09%  |
| 13      | 1399      | 10.49%  |
| 18      | 892       | 6.69%   |
| 21      | 846       | 6.35%   |
| 23      | 779       | 5.84%   |
| 17      | 538       | 4.04%   |
| Unknown | 523       | 3.92%   |
| 24      | 398       | 2.99%   |
| 34      | 360       | 2.7%    |
| 20      | 334       | 2.51%   |
| 19      | 318       | 2.39%   |
| 27      | 306       | 2.3%    |
| 31      | 146       | 1.1%    |
| 11      | 124       | 0.93%   |
| 22      | 119       | 0.89%   |
| 12      | 79        | 0.59%   |
| 40      | 70        | 0.53%   |
| 72      | 65        | 0.49%   |
| 28      | 63        | 0.47%   |
| 32      | 58        | 0.44%   |
| 54      | 53        | 0.4%    |
| 84      | 50        | 0.38%   |
| 10      | 48        | 0.36%   |
| 16      | 42        | 0.32%   |
| 52      | 37        | 0.28%   |
| 26      | 36        | 0.27%   |
| 46      | 35        | 0.26%   |
| 47      | 16        | 0.12%   |
| 37      | 13        | 0.1%    |
| 142     | 12        | 0.09%   |
| 48      | 11        | 0.08%   |
| 25      | 8         | 0.06%   |
| 58      | 6         | 0.05%   |
| 7       | 6         | 0.05%   |
| 65      | 5         | 0.04%   |
| 43      | 5         | 0.04%   |
| 39      | 5         | 0.04%   |
| 55      | 4         | 0.03%   |
| 41      | 4         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 6784      | 51.64%  |
| 401-500        | 2375      | 18.08%  |
| 501-600        | 1416      | 10.78%  |
| Unknown        | 523       | 3.98%   |
| 201-300        | 490       | 3.73%   |
| 351-400        | 468       | 3.56%   |
| 701-800        | 419       | 3.19%   |
| 601-700        | 247       | 1.88%   |
| 1001-1500      | 175       | 1.33%   |
| 1501-2000      | 116       | 0.88%   |
| 801-900        | 94        | 0.72%   |
| More than 2000 | 12        | 0.09%   |
| 901-1000       | 11        | 0.08%   |
| 1-100          | 6         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 9583      | 79.81%  |
| 16/10   | 965       | 8.04%   |
| Unknown | 442       | 3.68%   |
| 21/9    | 405       | 3.37%   |
| 5/4     | 342       | 2.85%   |
| 4/3     | 182       | 1.52%   |
| 3/2     | 60        | 0.5%    |
| 1.00    | 14        | 0.12%   |
| 0.67    | 6         | 0.05%   |
| 32/9    | 4         | 0.03%   |
| 6/5     | 1         | 0.01%   |
| 2.00    | 1         | 0.01%   |
| 0.56    | 1         | 0.01%   |
| 0.31    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 3845      | 28.99%  |
| 81-90          | 2823      | 21.28%  |
| 201-250        | 1823      | 13.74%  |
| 141-150        | 1078      | 8.13%   |
| 151-200        | 926       | 6.98%   |
| 351-500        | 586       | 4.42%   |
| Unknown        | 523       | 3.94%   |
| 301-350        | 315       | 2.37%   |
| More than 1000 | 250       | 1.88%   |
| 71-80          | 190       | 1.43%   |
| 501-1000       | 157       | 1.18%   |
| 251-300        | 155       | 1.17%   |
| 121-130        | 148       | 1.12%   |
| 131-140        | 127       | 0.96%   |
| 51-60          | 124       | 0.93%   |
| 91-100         | 52        | 0.39%   |
| 41-50          | 48        | 0.36%   |
| 61-70          | 44        | 0.33%   |
| 111-120        | 44        | 0.33%   |
| 1-40           | 6         | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 5396      | 41.88%  |
| 51-100        | 4246      | 32.96%  |
| 121-160       | 2140      | 16.61%  |
| Unknown       | 524       | 4.07%   |
| 1-50          | 362       | 2.81%   |
| 161-240       | 189       | 1.47%   |
| More than 240 | 27        | 0.21%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 10020     | 79.4%   |
| 2     | 1997      | 15.83%  |
| 0     | 495       | 3.92%   |
| 3     | 101       | 0.8%    |
| 4     | 6         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 8814      | 45%     |
| Qualcomm Atheros                  | 3788      | 19.34%  |
| Intel                             | 3353      | 17.12%  |
| Broadcom                          | 894       | 4.56%   |
| Ralink Technology                 | 427       | 2.18%   |
| Marvell Technology Group          | 240       | 1.23%   |
| JMicron Technology                | 228       | 1.16%   |
| Ralink                            | 224       | 1.14%   |
| Nvidia                            | 220       | 1.12%   |
| Broadcom Limited                  | 195       | 1%      |
| TP-Link                           | 193       | 0.99%   |
| Qualcomm Atheros Communications   | 136       | 0.69%   |
| Samsung Electronics               | 118       | 0.6%    |
| Silicon Integrated Systems [SiS]  | 100       | 0.51%   |
| D-Link                            | 75        | 0.38%   |
| VIA Technologies                  | 71        | 0.36%   |
| Xiaomi                            | 55        | 0.28%   |
| MediaTek                          | 54        | 0.28%   |
| Microsoft                         | 49        | 0.25%   |
| Motorola PCS                      | 48        | 0.25%   |
| D-Link System                     | 42        | 0.21%   |
| ASIX Electronics                  | 40        | 0.2%    |
| ICS Advent                        | 18        | 0.09%   |
| Motorola                          | 14        | 0.07%   |
| DisplayLink                       | 14        | 0.07%   |
| Huawei Technologies               | 12        | 0.06%   |
| Edimax Technology                 | 9         | 0.05%   |
| Dell                              | 9         | 0.05%   |
| LG Electronics                    | 8         | 0.04%   |
| Qualcomm                          | 7         | 0.04%   |
| ASUSTek Computer                  | 7         | 0.04%   |
| Microchip Technology              | 6         | 0.03%   |
| Mercucys                          | 6         | 0.03%   |
| Lenovo                            | 5         | 0.03%   |
| Arduino SA                        | 5         | 0.03%   |
| Accton Technology                 | 5         | 0.03%   |
| 3Com                              | 5         | 0.03%   |
| Sundance Technology Inc / IC Plus | 4         | 0.02%   |
| OPPO Electronics                  | 4         | 0.02%   |
| Micro Star International          | 4         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5775      | 26.95%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1883      | 8.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 882       | 4.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 779       | 3.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 671       | 3.13%   |
| Intel Wi-Fi 6 AX200                                               | 386       | 1.8%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 335       | 1.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 326       | 1.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 318       | 1.48%   |
| Ralink MT7601U Wireless Adapter                                   | 240       | 1.12%   |
| Intel Wi-Fi 6 AX201                                               | 236       | 1.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 221       | 1.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 185       | 0.86%   |
| Intel Wireless 7265                                               | 182       | 0.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 172       | 0.8%    |
| Nvidia MCP61 Ethernet                                             | 162       | 0.76%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 162       | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 155       | 0.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 142       | 0.66%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 126       | 0.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 124       | 0.58%   |
| Qualcomm Atheros AR9271 802.11n                                   | 121       | 0.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 115       | 0.54%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 115       | 0.54%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 114       | 0.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 113       | 0.53%   |
| Intel Wireless 7260                                               | 111       | 0.52%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 107       | 0.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 106       | 0.49%   |
| Realtek RTL8125 2.5GbE Controller                                 | 104       | 0.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 103       | 0.48%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 99        | 0.46%   |
| Intel Wireless 3165                                               | 97        | 0.45%   |
| Intel Ethernet Connection (2) I219-V                              | 96        | 0.45%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 93        | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 89        | 0.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 88        | 0.41%   |
| Ralink RT5370 Wireless Adapter                                    | 88        | 0.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 86        | 0.4%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 85        | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Qualcomm Atheros                      | 3316      | 35.21%  |
| Intel                                 | 2584      | 27.44%  |
| Realtek Semiconductor                 | 1640      | 17.42%  |
| Broadcom                              | 552       | 5.86%   |
| Ralink Technology                     | 427       | 4.53%   |
| Ralink                                | 224       | 2.38%   |
| TP-Link                               | 174       | 1.85%   |
| Qualcomm Atheros Communications       | 136       | 1.44%   |
| Broadcom Limited                      | 109       | 1.16%   |
| D-Link                                | 75        | 0.8%    |
| Microsoft                             | 49        | 0.52%   |
| MediaTek                              | 44        | 0.47%   |
| D-Link System                         | 29        | 0.31%   |
| Edimax Technology                     | 9         | 0.1%    |
| Marvell Technology Group              | 8         | 0.08%   |
| Mercucys                              | 6         | 0.06%   |
| Dell                                  | 5         | 0.05%   |
| Micro Star International              | 4         | 0.04%   |
| Encore Electronics                    | 4         | 0.04%   |
| NetGear                               | 3         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.03%   |
| Sierra Wireless                       | 2         | 0.02%   |
| Philips (or NXP)                      | 2         | 0.02%   |
| Linksys                               | 2         | 0.02%   |
| IMC Networks                          | 2         | 0.02%   |
| ASUSTek Computer                      | 2         | 0.02%   |
| Accton Technology                     | 2         | 0.02%   |
| Texas Instruments                     | 1         | 0.01%   |
| Samsung Electronics                   | 1         | 0.01%   |
| Pegatron                              | 1         | 0.01%   |
| Guillemot                             | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 882       | 9.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 779       | 8.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 671       | 7.08%   |
| Intel Wi-Fi 6 AX200                                                     | 386       | 4.07%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 335       | 3.53%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 326       | 3.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 318       | 3.35%   |
| Ralink MT7601U Wireless Adapter                                         | 240       | 2.53%   |
| Intel Wi-Fi 6 AX201                                                     | 236       | 2.49%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 221       | 2.33%   |
| Intel Wireless 7265                                                     | 182       | 1.92%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 172       | 1.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 142       | 1.5%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 126       | 1.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 124       | 1.31%   |
| Qualcomm Atheros AR9271 802.11n                                         | 121       | 1.28%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 115       | 1.21%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 115       | 1.21%   |
| Intel Wireless 7260                                                     | 111       | 1.17%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 107       | 1.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 106       | 1.12%   |
| Intel Wireless 3165                                                     | 97        | 1.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 88        | 0.93%   |
| Ralink RT5370 Wireless Adapter                                          | 88        | 0.93%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 86        | 0.91%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 85        | 0.9%    |
| Intel Wireless 3160                                                     | 83        | 0.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 83        | 0.88%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 80        | 0.84%   |
| Realtek 802.11ac NIC                                                    | 79        | 0.83%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 76        | 0.8%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 71        | 0.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 70        | 0.74%   |
| Intel Centrino Advanced-N 6235                                          | 69        | 0.73%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 68        | 0.72%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 67        | 0.71%   |
| Intel Wireless 8265 / 8275                                              | 66        | 0.7%    |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 60        | 0.63%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 57        | 0.6%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 55        | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 8078      | 69.11%  |
| Intel                             | 1146      | 9.8%    |
| Qualcomm Atheros                  | 726       | 6.21%   |
| Broadcom                          | 424       | 3.63%   |
| Marvell Technology Group          | 232       | 1.98%   |
| JMicron Technology                | 228       | 1.95%   |
| Nvidia                            | 219       | 1.87%   |
| Silicon Integrated Systems [SiS]  | 100       | 0.86%   |
| Broadcom Limited                  | 92        | 0.79%   |
| Samsung Electronics               | 89        | 0.76%   |
| VIA Technologies                  | 70        | 0.6%    |
| Xiaomi                            | 55        | 0.47%   |
| ASIX Electronics                  | 40        | 0.34%   |
| Motorola PCS                      | 37        | 0.32%   |
| TP-Link                           | 19        | 0.16%   |
| ICS Advent                        | 18        | 0.15%   |
| DisplayLink                       | 14        | 0.12%   |
| D-Link System                     | 13        | 0.11%   |
| MediaTek                          | 9         | 0.08%   |
| Huawei Technologies               | 7         | 0.06%   |
| Qualcomm                          | 6         | 0.05%   |
| LG Electronics                    | 6         | 0.05%   |
| Microchip Technology              | 5         | 0.04%   |
| Lenovo                            | 5         | 0.04%   |
| ASUSTek Computer                  | 5         | 0.04%   |
| 3Com                              | 5         | 0.04%   |
| Sundance Technology Inc / IC Plus | 4         | 0.03%   |
| OPPO Electronics                  | 4         | 0.03%   |
| Attansic Technology               | 4         | 0.03%   |
| Hangzhou Silan Microelectronics   | 3         | 0.03%   |
| Dell                              | 3         | 0.03%   |
| Aquantia                          | 3         | 0.03%   |
| Apple                             | 3         | 0.03%   |
| Accton Technology                 | 3         | 0.03%   |
| T & A Mobile Phones               | 2         | 0.02%   |
| Spreadtrum Communications         | 2         | 0.02%   |
| IBM                               | 2         | 0.02%   |
| Standard Microsystems             | 1         | 0.01%   |
| SK hynix                          | 1         | 0.01%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5775      | 48.8%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1883      | 15.91%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 185       | 1.56%   |
| Nvidia MCP61 Ethernet                                             | 162       | 1.37%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 162       | 1.37%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 155       | 1.31%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 114       | 0.96%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 113       | 0.95%   |
| Realtek RTL8125 2.5GbE Controller                                 | 104       | 0.88%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 103       | 0.87%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 99        | 0.84%   |
| Intel Ethernet Connection (2) I219-V                              | 96        | 0.81%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 93        | 0.79%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 89        | 0.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 82        | 0.69%   |
| Intel I211 Gigabit Network Connection                             | 82        | 0.69%   |
| Intel Ethernet Connection (7) I219-V                              | 82        | 0.69%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 80        | 0.68%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 77        | 0.65%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 72        | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 69        | 0.58%   |
| Intel 82579V Gigabit Network Connection                           | 69        | 0.58%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 66        | 0.56%   |
| Intel Ethernet Connection I217-LM                                 | 61        | 0.52%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 53        | 0.45%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 49        | 0.41%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 48        | 0.41%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 48        | 0.41%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 43        | 0.36%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 42        | 0.35%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 41        | 0.35%   |
| Intel 82578DC Gigabit Network Connection                          | 39        | 0.33%   |
| Motorola PCS moto g(30)                                           | 37        | 0.31%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 37        | 0.31%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 36        | 0.3%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 35        | 0.3%    |
| Intel Ethernet Connection (4) I219-LM                             | 34        | 0.29%   |
| ASIX AX88179 Gigabit Ethernet                                     | 33        | 0.28%   |
| Intel Ethernet Connection (2) I218-V                              | 32        | 0.27%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 31        | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 11289     | 55.23%  |
| WiFi     | 9037      | 44.21%  |
| Modem    | 91        | 0.45%   |
| Unknown  | 24        | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 7418      | 57.94%  |
| Ethernet | 5379      | 42.02%  |
| Modem    | 3         | 0.02%   |
| Unknown  | 2         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 7128      | 57.5%   |
| 1     | 4778      | 38.54%  |
| 0     | 379       | 3.06%   |
| 3     | 85        | 0.69%   |
| 4     | 20        | 0.16%   |
| 10    | 3         | 0.02%   |
| 8     | 1         | 0.01%   |
| 6     | 1         | 0.01%   |
| 5     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 9668      | 76.25%  |
| Yes  | 3012      | 23.75%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2222      | 35.06%  |
| Qualcomm Atheros Communications | 1609      | 25.39%  |
| Lite-On Technology              | 674       | 10.63%  |
| Cambridge Silicon Radio         | 534       | 8.43%   |
| Realtek Semiconductor           | 263       | 4.15%   |
| Broadcom                        | 228       | 3.6%    |
| IMC Networks                    | 149       | 2.35%   |
| Apple                           | 135       | 2.13%   |
| Foxconn / Hon Hai               | 127       | 2%      |
| Dell                            | 80        | 1.26%   |
| Hewlett-Packard                 | 57        | 0.9%    |
| Ralink                          | 49        | 0.77%   |
| Smart Modular Technologies      | 46        | 0.73%   |
| Qcom                            | 27        | 0.43%   |
| ASUSTek Computer                | 22        | 0.35%   |
| Ralink Technology               | 17        | 0.27%   |
| MediaTek                        | 16        | 0.25%   |
| Foxconn International           | 13        | 0.21%   |
| Alps Electric                   | 13        | 0.21%   |
| Askey Computer                  | 10        | 0.16%   |
| Integrated System Solution      | 8         | 0.13%   |
| Toshiba                         | 6         | 0.09%   |
| Micro Star International        | 6         | 0.09%   |
| Opticis                         | 5         | 0.08%   |
| ISSC                            | 4         | 0.06%   |
| Conwise Technology              | 3         | 0.05%   |
| Actions                         | 3         | 0.05%   |
| Unknown                         | 3         | 0.05%   |
| SINO WEALTH                     | 2         | 0.03%   |
| Marvell Semiconductor           | 2         | 0.03%   |
| Syntek                          | 1         | 0.02%   |
| Realtek                         | 1         | 0.02%   |
| Motorola PCS                    | 1         | 0.02%   |
| Fujitsu                         | 1         | 0.02%   |
| D-Link                          | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                                                  | 923       | 14.56%  |
| Intel Bluetooth wireless interface                                                  | 715       | 11.28%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 565       | 8.91%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 534       | 8.42%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 380       | 5.99%   |
| Intel AX200 Bluetooth                                                               | 375       | 5.91%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 247       | 3.9%    |
| Intel AX201 Bluetooth                                                               | 240       | 3.79%   |
| Realtek Bluetooth Radio                                                             | 197       | 3.11%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 152       | 2.4%    |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 142       | 2.24%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 126       | 1.99%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 99        | 1.56%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 95        | 1.5%    |
| Lite-On Bluetooth Device                                                            | 91        | 1.44%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 82        | 1.29%   |
| IMC Networks Bluetooth Radio                                                        | 77        | 1.21%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 64        | 1.01%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 59        | 0.93%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 59        | 0.93%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 59        | 0.93%   |
| Ralink RT3290 Bluetooth                                                             | 49        | 0.77%   |
| Apple Bluetooth Host Controller                                                     | 49        | 0.77%   |
| Smart Modular Bluetooth Device                                                      | 46        | 0.73%   |
| Apple Bluetooth USB Host Controller                                                 | 42        | 0.66%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 41        | 0.65%   |
| Dell Wireless 365 Bluetooth                                                         | 35        | 0.55%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 33        | 0.52%   |
| IMC Networks Bluetooth Device                                                       | 32        | 0.5%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 30        | 0.47%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 30        | 0.47%   |
| Intel AX210 Bluetooth                                                               | 26        | 0.41%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 25        | 0.39%   |
| Lite-On Atheros Bluetooth                                                           | 24        | 0.38%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 24        | 0.38%   |
| Intel Bluetooth Device                                                              | 22        | 0.35%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 21        | 0.33%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 20        | 0.32%   |
| Lite-On Wireless_Device                                                             | 18        | 0.28%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 18        | 0.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 9547      | 60.13%  |
| AMD                                             | 2576      | 16.23%  |
| Nvidia                                          | 2455      | 15.46%  |
| C-Media Electronics                             | 264       | 1.66%   |
| Generalplus Technology                          | 130       | 0.82%   |
| Silicon Integrated Systems [SiS]                | 101       | 0.64%   |
| Logitech                                        | 98        | 0.62%   |
| VIA Technologies                                | 77        | 0.49%   |
| JMTek                                           | 69        | 0.43%   |
| Kingston Technology                             | 57        | 0.36%   |
| Texas Instruments                               | 44        | 0.28%   |
| Creative Labs                                   | 39        | 0.25%   |
| Corsair                                         | 30        | 0.19%   |
| Microsoft                                       | 27        | 0.17%   |
| Plantronics                                     | 19        | 0.12%   |
| Razer USA                                       | 17        | 0.11%   |
| GN Netcom                                       | 17        | 0.11%   |
| Licensed by Sony Computer Entertainment America | 16        | 0.1%    |
| BEHRINGER International                         | 16        | 0.1%    |
| Tenx Technology                                 | 15        | 0.09%   |
| Realtek Semiconductor                           | 15        | 0.09%   |
| Sony                                            | 13        | 0.08%   |
| Goldvish                                        | 11        | 0.07%   |
| JBL                                             | 9         | 0.06%   |
| Dell                                            | 9         | 0.06%   |
| Samson Technologies                             | 8         | 0.05%   |
| M-Audio                                         | 8         | 0.05%   |
| Focusrite-Novation                              | 8         | 0.05%   |
| BY EDIFIER                                      | 8         | 0.05%   |
| SteelSeries ApS                                 | 7         | 0.04%   |
| Creative Technology                             | 7         | 0.04%   |
| Samsung Electronics                             | 6         | 0.04%   |
| Philips (or NXP)                                | 6         | 0.04%   |
| Jieli Technology                                | 6         | 0.04%   |
| Fry's Electronics                               | 6         | 0.04%   |
| Tdlasunnic                                      | 5         | 0.03%   |
| KTMicro                                         | 5         | 0.03%   |
| FIFINE Microphones                              | 5         | 0.03%   |
| Elite Silicon                                   | 5         | 0.03%   |
| Cirrus Logic                                    | 5         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1239      | 6.71%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1196      | 6.48%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1180      | 6.39%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 708       | 3.84%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 683       | 3.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 608       | 3.29%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 570       | 3.09%   |
| Intel Cannon Lake PCH cAVS                                                                        | 539       | 2.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 437       | 2.37%   |
| Intel 8 Series HD Audio Controller                                                                | 413       | 2.24%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 409       | 2.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 388       | 2.1%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 382       | 2.07%   |
| Intel Broadwell-U Audio Controller                                                                | 339       | 1.84%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 336       | 1.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 330       | 1.79%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 317       | 1.72%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 300       | 1.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 271       | 1.47%   |
| AMD FCH Azalia Controller                                                                         | 266       | 1.44%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 254       | 1.38%   |
| Nvidia High Definition Audio Controller                                                           | 244       | 1.32%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 223       | 1.21%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 215       | 1.16%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 214       | 1.16%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 211       | 1.14%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 191       | 1.03%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 185       | 1%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 179       | 0.97%   |
| Nvidia MCP61 High Definition Audio                                                                | 177       | 0.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 168       | 0.91%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 161       | 0.87%   |
| AMD Wrestler HDMI Audio                                                                           | 154       | 0.83%   |
| Intel 200 Series PCH HD Audio                                                                     | 153       | 0.83%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 152       | 0.82%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 150       | 0.81%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 141       | 0.76%   |
| Generalplus Technology USB Audio Device                                                           | 130       | 0.7%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 122       | 0.66%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 121       | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 929       | 17.33%  |
| Kingston            | 858       | 16.01%  |
| Smart               | 716       | 13.36%  |
| Samsung Electronics | 509       | 9.5%    |
| SK hynix            | 358       | 6.68%   |
| A-DATA Technology   | 323       | 6.03%   |
| Corsair             | 243       | 4.53%   |
| Teikon              | 186       | 3.47%   |
| Crucial             | 183       | 3.41%   |
| Micron Technology   | 179       | 3.34%   |
| Smart Brazil        | 113       | 2.11%   |
| High Bridge         | 64        | 1.19%   |
| Unknown             | 62        | 1.16%   |
| Team                | 55        | 1.03%   |
| Elpida              | 51        | 0.95%   |
| Multilaser          | 48        | 0.9%    |
| G.Skill             | 40        | 0.75%   |
| Unknown (ABCD)      | 38        | 0.71%   |
| Apacer              | 30        | 0.56%   |
| Patriot             | 28        | 0.52%   |
| Nanya Technology    | 22        | 0.41%   |
| Kllisre             | 20        | 0.37%   |
| Atermiter           | 20        | 0.37%   |
| Avant               | 16        | 0.3%    |
| Ramaxel Technology  | 14        | 0.26%   |
| PUSKILL             | 14        | 0.26%   |
| Kreton              | 12        | 0.22%   |
| Smart Modular       | 11        | 0.21%   |
| HT Micron           | 11        | 0.21%   |
| RZX                 | 10        | 0.19%   |
| HBS                 | 10        | 0.19%   |
| CSX                 | 10        | 0.19%   |
| GeIL                | 9         | 0.17%   |
| Kingmax             | 7         | 0.13%   |
| Unknown (82B5)      | 6         | 0.11%   |
| Unknown (0x0B5E)    | 6         | 0.11%   |
| Positivo            | 6         | 0.11%   |
| Hewlett-Packard     | 6         | 0.11%   |
| Carry               | 6         | 0.11%   |
| Transcend           | 5         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 80        | 1.36%   |
| Unknown                                                          | 62        | 1.05%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 55        | 0.93%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1333MT/s            | 51        | 0.87%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 49        | 0.83%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s                | 49        | 0.83%   |
| Smart RAM SH564128FH8NZPHSCG 4GB SODIMM DDR3 1334MT/s            | 46        | 0.78%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 45        | 0.76%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 40        | 0.68%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s            | 40        | 0.68%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s            | 35        | 0.59%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 34        | 0.58%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 34        | 0.58%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s              | 33        | 0.56%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 32        | 0.54%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s            | 32        | 0.54%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 32        | 0.54%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 32        | 0.54%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 30        | 0.51%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 29        | 0.49%   |
| Smart RAM SH564128FJ8NZRNSDG 4GB SODIMM DDR3 1600MT/s            | 27        | 0.46%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 26        | 0.44%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 24        | 0.41%   |
| Smart RAM SH564128FJ8NZRNSDR 4096MB SODIMM DDR3 1600MT/s         | 24        | 0.41%   |
| A-DATA RAM AM1P26KC8T1-BAAS 8GB SODIMM DDR4 2667MT/s             | 24        | 0.41%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s            | 23        | 0.39%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s           | 22        | 0.37%   |
| Smart RAM SH564568FH8NZPHSCG 2GB SODIMM DDR3 1333MT/s            | 22        | 0.37%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 22        | 0.37%   |
| A-DATA RAM AE4S240038G17-BHYA 8GB SODIMM DDR4 2400MT/s           | 22        | 0.37%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 20        | 0.34%   |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s            | 20        | 0.34%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 20        | 0.34%   |
| Unknown RAM Module 2GB DIMM DDR2                                 | 19        | 0.32%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s              | 19        | 0.32%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s             | 19        | 0.32%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 18        | 0.31%   |
| Smart RAM SH564568FJ8NZRNSDR 2GB SODIMM DDR3 1600MT/s            | 18        | 0.31%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 18        | 0.31%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s                      | 18        | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR3         | 1935      | 42.59%  |
| DDR4         | 1681      | 37%     |
| DDR2         | 306       | 6.74%   |
| Unknown      | 206       | 4.53%   |
| SDRAM        | 193       | 4.25%   |
| LPDDR4       | 90        | 1.98%   |
| DDR          | 46        | 1.01%   |
| LPDDR3       | 34        | 0.75%   |
| DDR5         | 26        | 0.57%   |
| DRAM         | 19        | 0.42%   |
| LPDDR5       | 5         | 0.11%   |
| RAM          | 1         | 0.02%   |
| DDR2 FB-DIMM | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2467      | 54.64%  |
| DIMM         | 1904      | 42.17%  |
| Row Of Chips | 118       | 2.61%   |
| Unknown      | 16        | 0.35%   |
| RIMM         | 4         | 0.09%   |
| FB-DIMM      | 4         | 0.09%   |
| Chip         | 2         | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 1880      | 36.62%  |
| 8192  | 1495      | 29.12%  |
| 2048  | 1016      | 19.79%  |
| 16384 | 461       | 8.98%   |
| 1024  | 163       | 3.17%   |
| 32768 | 97        | 1.89%   |
| 512   | 18        | 0.35%   |
| 256   | 2         | 0.04%   |
| 1536  | 1         | 0.02%   |
| 16    | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1119      | 22.01%  |
| 2667    | 638       | 12.55%  |
| 1333    | 632       | 12.43%  |
| 2400    | 479       | 9.42%   |
| 3200    | 293       | 5.76%   |
| Unknown | 261       | 5.13%   |
| 1334    | 242       | 4.76%   |
| 800     | 169       | 3.32%   |
| 2133    | 160       | 3.15%   |
| 667     | 157       | 3.09%   |
| 1066    | 78        | 1.53%   |
| 3600    | 72        | 1.42%   |
| 3000    | 66        | 1.3%    |
| 3400    | 63        | 1.24%   |
| 1067    | 62        | 1.22%   |
| 1867    | 54        | 1.06%   |
| 4199    | 41        | 0.81%   |
| 4267    | 36        | 0.71%   |
| 3466    | 36        | 0.71%   |
| 533     | 36        | 0.71%   |
| 1866    | 35        | 0.69%   |
| 2800    | 31        | 0.61%   |
| 2933    | 27        | 0.53%   |
| 3733    | 23        | 0.45%   |
| 2666    | 23        | 0.45%   |
| 2048    | 22        | 0.43%   |
| 975     | 22        | 0.43%   |
| 4800    | 21        | 0.41%   |
| 400     | 21        | 0.41%   |
| 3151    | 17        | 0.33%   |
| 333     | 16        | 0.31%   |
| 3800    | 14        | 0.28%   |
| 3266    | 12        | 0.24%   |
| 3334    | 9         | 0.18%   |
| 8400    | 6         | 0.12%   |
| 6400    | 6         | 0.12%   |
| 3333    | 6         | 0.12%   |
| 1200    | 5         | 0.1%    |
| 41632   | 4         | 0.08%   |
| 3933    | 4         | 0.08%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 118       | 43.54%  |
| Seiko Epson           | 78        | 28.78%  |
| Samsung Electronics   | 24        | 8.86%   |
| Canon                 | 20        | 7.38%   |
| Brother Industries    | 18        | 6.64%   |
| Lexmark International | 3         | 1.11%   |
| QinHeng Electronics   | 2         | 0.74%   |
| Apple                 | 2         | 0.74%   |
| Xerox                 | 1         | 0.37%   |
| Ricoh                 | 1         | 0.37%   |
| Prolific Technology   | 1         | 0.37%   |
| Oki Data              | 1         | 0.37%   |
| MIIIW                 | 1         | 0.37%   |
| ARGOX                 | 1         | 0.37%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson ET-2710 Series                   | 14        | 5.11%   |
| Seiko Epson L396 Series                      | 11        | 4.01%   |
| Seiko Epson L355 Series                      | 9         | 3.28%   |
| HP Ink Tank Wireless 410 series              | 9         | 3.28%   |
| HP DeskJet 2130 series                       | 9         | 3.28%   |
| HP DeskJet 2700 series                       | 8         | 2.92%   |
| Seiko Epson L365 Series                      | 7         | 2.55%   |
| HP Deskjet 3050 J610 series                  | 7         | 2.55%   |
| HP Deskjet 2540 series                       | 7         | 2.55%   |
| Canon G3010 series                           | 7         | 2.55%   |
| HP LaserJet 1020                             | 6         | 2.19%   |
| HP DeskJet F4100 Printer series              | 6         | 2.19%   |
| Samsung SCX-4200 series                      | 5         | 1.82%   |
| HP LaserJet Professional P1102w              | 5         | 1.82%   |
| HP Deskjet 2050 J510                         | 5         | 1.82%   |
| Seiko Epson L220 Series                      | 4         | 1.46%   |
| Samsung M2070 Series                         | 4         | 1.46%   |
| Samsung M2020 Series                         | 4         | 1.46%   |
| HP LaserJet P1005                            | 4         | 1.46%   |
| HP DeskJet F4200 series                      | 4         | 1.46%   |
| HP DeskJet 3630 series                       | 4         | 1.46%   |
| HP DeskJet 2620 All-in-One Printer           | 4         | 1.46%   |
| Seiko Epson XP-240 Series                    | 3         | 1.09%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 3         | 1.09%   |
| Seiko Epson L375 Series                      | 3         | 1.09%   |
| Seiko Epson L3110 Series                     | 3         | 1.09%   |
| Seiko Epson L210 Series                      | 3         | 1.09%   |
| Samsung SCX-3200 Series                      | 3         | 1.09%   |
| HP LaserJet 1018                             | 3         | 1.09%   |
| HP Deskjet F4400 series                      | 3         | 1.09%   |
| Brother HL-1200 series                       | 3         | 1.09%   |
| Seiko Epson L6160 Series                     | 2         | 0.73%   |
| Seiko Epson L120 Series                      | 2         | 0.73%   |
| Seiko Epson ET-2700 Series                   | 2         | 0.73%   |
| Samsung SCX-3400 Series                      | 2         | 0.73%   |
| Samsung ML-216x Series Laser Printer         | 2         | 0.73%   |
| QinHeng CH340S                               | 2         | 0.73%   |
| HP PSC-1315/PSC-1317                         | 2         | 0.73%   |
| HP Printing Support                          | 2         | 0.73%   |
| HP DeskJet D1360                             | 2         | 0.73%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 9         | 45%     |
| Hewlett-Packard | 8         | 40%     |
| Seiko Epson     | 2         | 10%     |
| Mustek Systems  | 1         | 5%      |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| HP ScanJet 2400c                                        | 5         | 25%     |
| Canon CanoScan LIDE 25                                  | 4         | 20%     |
| Canon CanoScan LiDE 110                                 | 2         | 10%     |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 5%      |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 5%      |
| Mustek Systems ScanExpress 1200 UB                      | 1         | 5%      |
| HP ScanJet G4050                                        | 1         | 5%      |
| HP ScanJet 3800c                                        | 1         | 5%      |
| HP Scanjet 200                                          | 1         | 5%      |
| Canon CanoScan N670U/N676U/LiDE 20                      | 1         | 5%      |
| Canon CanoScan N1240U/LiDE 30                           | 1         | 5%      |
| Canon CanoScan LiDE 210                                 | 1         | 5%      |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1475      | 19.28%  |
| Microdia                               | 873       | 11.41%  |
| Realtek Semiconductor                  | 699       | 9.14%   |
| Quanta                                 | 622       | 8.13%   |
| Silicon Motion                         | 560       | 7.32%   |
| Sunplus Innovation Technology          | 531       | 6.94%   |
| IMC Networks                           | 320       | 4.18%   |
| Logitech                               | 288       | 3.76%   |
| Suyin                                  | 286       | 3.74%   |
| Bison Electronics                      | 276       | 3.61%   |
| Syntek                                 | 223       | 2.92%   |
| Acer                                   | 209       | 2.73%   |
| Alcor Micro                            | 151       | 1.97%   |
| Apple                                  | 125       | 1.63%   |
| Samsung Electronics                    | 95        | 1.24%   |
| Cheng Uei Precision Industry (Foxlink) | 88        | 1.15%   |
| Generalplus Technology                 | 72        | 0.94%   |
| Z-Star Microelectronics                | 64        | 0.84%   |
| Microsoft                              | 59        | 0.77%   |
| Ricoh                                  | 50        | 0.65%   |
| ALi                                    | 46        | 0.6%    |
| Sonix Technology                       | 42        | 0.55%   |
| Aveo Technology                        | 28        | 0.37%   |
| GEMBIRD                                | 26        | 0.34%   |
| SunplusIT                              | 24        | 0.31%   |
| OmniVision Technologies                | 24        | 0.31%   |
| Lite-On Technology                     | 24        | 0.31%   |
| Importek                               | 24        | 0.31%   |
| Jieli Technology                       | 22        | 0.29%   |
| Unknown                                | 21        | 0.27%   |
| Pixart Imaging                         | 20        | 0.26%   |
| USB Camera                             | 19        | 0.25%   |
| LG Electronics                         | 18        | 0.24%   |
| Cubeternet                             | 17        | 0.22%   |
| Lenovo                                 | 16        | 0.21%   |
| Y Media                                | 14        | 0.18%   |
| Genesys Logic                          | 11        | 0.14%   |
| Shenzhen Kingcome Optoelectronic       | 10        | 0.13%   |
| Intel                                  | 10        | 0.13%   |
| Sunplus Technology                     | 9         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD             | 323       | 4.22%   |
| Realtek Integrated_Webcam_HD              | 308       | 4.02%   |
| Quanta HD User Facing                     | 270       | 3.52%   |
| Chicony HD Webcam                         | 270       | 3.52%   |
| Chicony HD User Facing                    | 219       | 2.86%   |
| Sunplus Integrated_Webcam_HD              | 205       | 2.68%   |
| Silicon Motion Web Camera                 | 204       | 2.66%   |
| Quanta VGA WebCam                         | 195       | 2.54%   |
| Chicony Integrated Camera                 | 156       | 2.04%   |
| Chicony VGA WebCam                        | 140       | 1.83%   |
| Syntek Integrated Camera                  | 127       | 1.66%   |
| Realtek Integrated Webcam                 | 110       | 1.44%   |
| Sunplus HD WebCam                         | 107       | 1.4%    |
| Logitech Webcam C270                      | 104       | 1.36%   |
| Chicony USB 2.0 Camera                    | 96        | 1.25%   |
| Samsung Galaxy A5 (MTP)                   | 94        | 1.23%   |
| Alcor Micro USB 2.0 Camera                | 93        | 1.21%   |
| Quanta HD Webcam                          | 87        | 1.14%   |
| Microdia Laptop_Integrated_Webcam_HD      | 78        | 1.02%   |
| Logitech HD Pro Webcam C920               | 60        | 0.78%   |
| IMC Networks Integrated Camera            | 58        | 0.76%   |
| Microdia Dell Laptop Integrated Webcam HD | 56        | 0.73%   |
| Silicon Motion WebCam SC-10HDD12636N      | 53        | 0.69%   |
| Bison EasyCamera                          | 51        | 0.67%   |
| IMC Networks USB2.0 VGA UVC WebCam        | 50        | 0.65%   |
| Microdia Integrated Webcam HD             | 49        | 0.64%   |
| Generalplus GENERAL WEBCAM                | 49        | 0.64%   |
| Bison BisonCam, NB Pro                    | 49        | 0.64%   |
| Realtek USB Camera                        | 48        | 0.63%   |
| Bison VGA WebCam                          | 46        | 0.6%    |
| Acer BisonCam, NB Pro                     | 46        | 0.6%    |
| Suyin Integrated_Webcam_HD                | 45        | 0.59%   |
| Chicony EasyCamera                        | 44        | 0.57%   |
| Silicon Motion WebCam SCB-1100N           | 42        | 0.55%   |
| Silicon Motion WebCam SC-13HDL11939N      | 41        | 0.54%   |
| Realtek HD WebCam                         | 41        | 0.54%   |
| Syntek EasyCamera                         | 40        | 0.52%   |
| Silicon Motion WebCam SC-0311139N         | 40        | 0.52%   |
| IMC Networks USB2.0 HD UVC WebCam         | 39        | 0.51%   |
| Sonix USB2.0 HD UVC WebCam                | 38        | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 290       | 46.47%  |
| Synaptics                  | 74        | 11.86%  |
| Shenzhen Goodix Technology | 69        | 11.06%  |
| AuthenTec                  | 62        | 9.94%   |
| Upek                       | 58        | 9.29%   |
| LighTuning Technology      | 33        | 5.29%   |
| Samsung Electronics        | 17        | 2.72%   |
| Elan Microelectronics      | 9         | 1.44%   |
| STMicroelectronics         | 4         | 0.64%   |
| Futronic Technology        | 2         | 0.32%   |
| Focal-systems.Corp         | 2         | 0.32%   |
| Dell                       | 2         | 0.32%   |
| Next Biometrics            | 1         | 0.16%   |
| DigitalPersona             | 1         | 0.16%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                                | 111       | 17.79%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 49        | 7.85%   |
| Shenzhen Goodix Fingerprint Reader                                         | 44        | 7.05%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 28        | 4.49%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 27        | 4.33%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 26        | 4.17%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 24        | 3.85%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 23        | 3.69%   |
| Validity Sensors Fingerprint scanner                                       | 22        | 3.53%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 19        | 3.04%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 19        | 3.04%   |
| Shenzhen Goodix  FingerPrint Device                                        | 18        | 2.88%   |
| Samsung Fingerprint Device                                                 | 17        | 2.72%   |
| Synaptics  WBDI                                                            | 16        | 2.56%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 14        | 2.24%   |
| AuthenTec AES2810                                                          | 14        | 2.24%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 14        | 2.24%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 13        | 2.08%   |
| Validity Sensors VFS491                                                    | 11        | 1.76%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 11        | 1.76%   |
| AuthenTec Fingerprint Sensor                                               | 11        | 1.76%   |
| Elan ELAN:Fingerprint                                                      | 9         | 1.44%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 8         | 1.28%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 1.28%   |
| Upek TCS5B Fingerprint sensor                                              | 8         | 1.28%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 1.12%   |
| Shenzhen Goodix FingerPrint                                                | 7         | 1.12%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 0.96%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 0.96%   |
| Synaptics WBDI                                                             | 5         | 0.8%    |
| STMicroelectronics Fingerprint Reader                                      | 4         | 0.64%   |
| AuthenTec AES1600                                                          | 4         | 0.64%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.48%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 0.32%   |
| Futronic FS81 Fingerprint Scanner Module                                   | 2         | 0.32%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 2         | 0.32%   |
| Dell MS819 Wired Mouse With Fingerprint Reader                             | 2         | 0.32%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.16%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.16%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.16%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 84        | 43.08%  |
| Alcor Micro                       | 28        | 14.36%  |
| Gemalto (was Gemplus)             | 16        | 8.21%   |
| Lenovo                            | 13        | 6.67%   |
| Giesecke & Devrient               | 13        | 6.67%   |
| Upek                              | 10        | 5.13%   |
| Watchdata                         | 7         | 3.59%   |
| Aladdin Knowledge Systems         | 6         | 3.08%   |
| SCM Microsystems                  | 4         | 2.05%   |
| OmniKey                           | 3         | 1.54%   |
| O2 Micro                          | 3         | 1.54%   |
| Chicony Electronics               | 3         | 1.54%   |
| Castles Technology                | 2         | 1.03%   |
| VASCO Data Security International | 1         | 0.51%   |
| Realtek Semiconductor             | 1         | 0.51%   |
| Advanced Card Systems             | 1         | 0.51%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 28        | 14.36%  |
| Broadcom 58200                                                               | 23        | 11.79%  |
| Broadcom 5880                                                                | 22        | 11.28%  |
| Broadcom BCM5880 Secure Applications Processor                               | 21        | 10.77%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 18        | 9.23%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 15        | 7.69%   |
| Lenovo Integrated Smart Card Reader                                          | 13        | 6.67%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 10        | 5.13%   |
| Watchdata USB Key                                                            | 7         | 3.59%   |
| Giesecke & Devrient StarSign CUT                                             | 7         | 3.59%   |
| Giesecke & Devrient StarSign CUT S                                           | 6         | 3.08%   |
| Aladdin Knowledge Systems Token JC                                           | 6         | 3.08%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 3         | 1.54%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 2         | 1.03%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 2         | 1.03%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 1.03%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 1.03%   |
| Castles Technology EZCCID Smart Card Reader                                  | 2         | 1.03%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.51%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.51%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.51%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.51%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.51%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.51%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 9967      | 79.36%  |
| 1     | 2263      | 18.02%  |
| 2     | 261       | 2.08%   |
| 3     | 39        | 0.31%   |
| 4     | 20        | 0.16%   |
| 7     | 4         | 0.03%   |
| 5     | 3         | 0.02%   |
| 8     | 2         | 0.02%   |
| 6     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 899       | 30.9%   |
| Fingerprint reader       | 620       | 21.31%  |
| Net/wireless             | 386       | 13.27%  |
| Multimedia controller    | 264       | 9.08%   |
| Chipcard                 | 163       | 5.6%    |
| Communication controller | 111       | 3.82%   |
| Bluetooth                | 89        | 3.06%   |
| Camera                   | 81        | 2.78%   |
| Sound                    | 65        | 2.23%   |
| Unassigned class         | 59        | 2.03%   |
| Storage                  | 43        | 1.48%   |
| Net/ethernet             | 36        | 1.24%   |
| Modem                    | 24        | 0.83%   |
| Flash memory             | 21        | 0.72%   |
| Card reader              | 14        | 0.48%   |
| Network                  | 10        | 0.34%   |
| Storage/ide              | 7         | 0.24%   |
| Firewire controller      | 6         | 0.21%   |
| Storage/raid             | 4         | 0.14%   |
| Storage/nvme             | 3         | 0.1%    |
| Wireless                 | 1         | 0.03%   |
| Video                    | 1         | 0.03%   |
| Storage/ata              | 1         | 0.03%   |
| Dvb card                 | 1         | 0.03%   |

