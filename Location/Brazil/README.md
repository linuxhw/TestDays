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

Total: 16446

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [7ff54a3b05](https://linux-hardware.org/?probe=7ff54a3b05) | Dec 01, 2022 |
| Positivo B... | VJFE53F11X-B0511H           | Notebook    | [24b1be97d6](https://linux-hardware.org/?probe=24b1be97d6) | Dec 01, 2022 |
| Positivo B... | VJFE53F11X-B0511H           | Notebook    | [a2e91cba31](https://linux-hardware.org/?probe=a2e91cba31) | Dec 01, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [c8ef49d294](https://linux-hardware.org/?probe=c8ef49d294) | Dec 01, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [3131016a26](https://linux-hardware.org/?probe=3131016a26) | Dec 01, 2022 |
| Dell          | Inspiron 13-5378            | Notebook    | [9d25b2f6e0](https://linux-hardware.org/?probe=9d25b2f6e0) | Dec 01, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [8a4813eec4](https://linux-hardware.org/?probe=8a4813eec4) | Nov 30, 2022 |
| Colorful T... | DJ H310M-E V20              | Desktop     | [ef8cb053dc](https://linux-hardware.org/?probe=ef8cb053dc) | Nov 30, 2022 |
| Colorful T... | DJ H310M-E V20              | Desktop     | [9831bd75b9](https://linux-hardware.org/?probe=9831bd75b9) | Nov 30, 2022 |
| Samsung       | 300E5K/300E5Q               | Notebook    | [f6bb652f5a](https://linux-hardware.org/?probe=f6bb652f5a) | Nov 30, 2022 |
| Samsung       | 550XDA                      | Notebook    | [7614fde301](https://linux-hardware.org/?probe=7614fde301) | Nov 30, 2022 |
| Unknown       | X99H                        | Desktop     | [b9e2236de7](https://linux-hardware.org/?probe=b9e2236de7) | Nov 30, 2022 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [87d3950072](https://linux-hardware.org/?probe=87d3950072) | Nov 30, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [d95adc01a7](https://linux-hardware.org/?probe=d95adc01a7) | Nov 30, 2022 |
| GALAX         | B365M G10b                  | Desktop     | [9eabacd766](https://linux-hardware.org/?probe=9eabacd766) | Nov 30, 2022 |
| GALAX         | B365M G10b                  | Desktop     | [9f7438d5a3](https://linux-hardware.org/?probe=9f7438d5a3) | Nov 30, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [d53007b0b3](https://linux-hardware.org/?probe=d53007b0b3) | Nov 30, 2022 |
| Philco        | 14H                         | Notebook    | [8d29065667](https://linux-hardware.org/?probe=8d29065667) | Nov 30, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [53ee9a8fb9](https://linux-hardware.org/?probe=53ee9a8fb9) | Nov 30, 2022 |
| Dell          | Inspiron 5423               | Notebook    | [db57850733](https://linux-hardware.org/?probe=db57850733) | Nov 29, 2022 |
| Positivo B... | S14SL03                     | Notebook    | [a42ebacec4](https://linux-hardware.org/?probe=a42ebacec4) | Nov 29, 2022 |
| Dell          | Vostro 5470                 | Notebook    | [15c504a6ef](https://linux-hardware.org/?probe=15c504a6ef) | Nov 29, 2022 |
| Lenovo        | Legion 5 15IMH05H 82CF      | Notebook    | [adb0404576](https://linux-hardware.org/?probe=adb0404576) | Nov 29, 2022 |
| Acer          | Nitro AN515-51              | Notebook    | [ba6d4f20e7](https://linux-hardware.org/?probe=ba6d4f20e7) | Nov 29, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [a130766490](https://linux-hardware.org/?probe=a130766490) | Nov 29, 2022 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [d89a05dd31](https://linux-hardware.org/?probe=d89a05dd31) | Nov 29, 2022 |
| Intel         | H61                         | Desktop     | [42f943bc9c](https://linux-hardware.org/?probe=42f943bc9c) | Nov 28, 2022 |
| PCWare        | IPMH61R1                    | Desktop     | [7872d8f10f](https://linux-hardware.org/?probe=7872d8f10f) | Nov 28, 2022 |
| Acer          | TravelMate B113             | Notebook    | [567c2d2e20](https://linux-hardware.org/?probe=567c2d2e20) | Nov 28, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [51d2b67ca3](https://linux-hardware.org/?probe=51d2b67ca3) | Nov 28, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [8263c8ba6f](https://linux-hardware.org/?probe=8263c8ba6f) | Nov 28, 2022 |
| Dell          | G15 5520                    | Notebook    | [251078d1b4](https://linux-hardware.org/?probe=251078d1b4) | Nov 28, 2022 |
| Dell          | Inspiron 5458               | Notebook    | [624e6b243c](https://linux-hardware.org/?probe=624e6b243c) | Nov 28, 2022 |
| Dell          | Inspiron 5458               | Notebook    | [54e985a956](https://linux-hardware.org/?probe=54e985a956) | Nov 28, 2022 |
| Acer          | Aspire A515-57              | Notebook    | [984e01118e](https://linux-hardware.org/?probe=984e01118e) | Nov 28, 2022 |
| HOUTER        | IPMIP-GS                    | Desktop     | [cbc472e6df](https://linux-hardware.org/?probe=cbc472e6df) | Nov 28, 2022 |
| Acer          | Nitro AN517-54              | Notebook    | [a9b90b8910](https://linux-hardware.org/?probe=a9b90b8910) | Nov 27, 2022 |
| Acer          | Nitro AN517-54              | Notebook    | [445583d2bb](https://linux-hardware.org/?probe=445583d2bb) | Nov 27, 2022 |
| Acer          | Aspire V3-571               | Notebook    | [ab9e6cc193](https://linux-hardware.org/?probe=ab9e6cc193) | Nov 27, 2022 |
| CompuLab      | Intense-PC                  | Mini pc     | [25e327c3f1](https://linux-hardware.org/?probe=25e327c3f1) | Nov 27, 2022 |
| Acer          | Aspire V3-571               | Notebook    | [a4d6ce5fa1](https://linux-hardware.org/?probe=a4d6ce5fa1) | Nov 27, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [99e1d10484](https://linux-hardware.org/?probe=99e1d10484) | Nov 27, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [7d3bf460f7](https://linux-hardware.org/?probe=7d3bf460f7) | Nov 27, 2022 |
| AMD           | 58514                       | Desktop     | [7558bc36a0](https://linux-hardware.org/?probe=7558bc36a0) | Nov 27, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [4de72d3d12](https://linux-hardware.org/?probe=4de72d3d12) | Nov 26, 2022 |
| MSI           | P55-CD53                    | Desktop     | [a602949484](https://linux-hardware.org/?probe=a602949484) | Nov 26, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [5b13c289e1](https://linux-hardware.org/?probe=5b13c289e1) | Nov 26, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [c41d8da6ac](https://linux-hardware.org/?probe=c41d8da6ac) | Nov 26, 2022 |
| Megaware      | MW-NM70HD-MI 01/13/2013 ... | Desktop     | [95b48709fd](https://linux-hardware.org/?probe=95b48709fd) | Nov 26, 2022 |
| Huanan        | X99-8M-F V1.1               | Desktop     | [88db74df98](https://linux-hardware.org/?probe=88db74df98) | Nov 26, 2022 |
| Lenovo        | G40-80 80JE                 | Notebook    | [47d9a5f1ca](https://linux-hardware.org/?probe=47d9a5f1ca) | Nov 26, 2022 |
| Lenovo        | G40-80 80JE                 | Notebook    | [5d324af4d0](https://linux-hardware.org/?probe=5d324af4d0) | Nov 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c3e10b2149](https://linux-hardware.org/?probe=c3e10b2149) | Nov 26, 2022 |
| ASUSTek       | B150M-C                     | Desktop     | [bbbdc2b291](https://linux-hardware.org/?probe=bbbdc2b291) | Nov 26, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [e784cdc15d](https://linux-hardware.org/?probe=e784cdc15d) | Nov 26, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [cd5eb0566d](https://linux-hardware.org/?probe=cd5eb0566d) | Nov 26, 2022 |
| Unknown       | PCWARE APMCP68              | Desktop     | [0cb03d53bb](https://linux-hardware.org/?probe=0cb03d53bb) | Nov 26, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [3e969e8aa0](https://linux-hardware.org/?probe=3e969e8aa0) | Nov 26, 2022 |
| Huanan        | X99-8M-F V1.1               | Desktop     | [3ca25803b5](https://linux-hardware.org/?probe=3ca25803b5) | Nov 25, 2022 |
| Intel         | Unknown                     | Desktop     | [bcf46201bc](https://linux-hardware.org/?probe=bcf46201bc) | Nov 25, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [2965050f1a](https://linux-hardware.org/?probe=2965050f1a) | Nov 25, 2022 |
| ASRock        | B460M-HDV                   | Desktop     | [00c07e7aa9](https://linux-hardware.org/?probe=00c07e7aa9) | Nov 25, 2022 |
| Intel         | H61                         | Desktop     | [76825e4753](https://linux-hardware.org/?probe=76825e4753) | Nov 25, 2022 |
| ASUSTek       | Z450LA                      | Notebook    | [ffd2220d21](https://linux-hardware.org/?probe=ffd2220d21) | Nov 25, 2022 |
| HP            | 18E7                        | Desktop     | [048d4bd3ae](https://linux-hardware.org/?probe=048d4bd3ae) | Nov 25, 2022 |
| Positivo      | P5VD2-MX                    | Desktop     | [c9d4c5ea2b](https://linux-hardware.org/?probe=c9d4c5ea2b) | Nov 25, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [618ea5fb0e](https://linux-hardware.org/?probe=618ea5fb0e) | Nov 25, 2022 |
| ASUSTek       | J1800I-C/BR                 | Desktop     | [9cfe40fa0b](https://linux-hardware.org/?probe=9cfe40fa0b) | Nov 25, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [05d0bf9d8d](https://linux-hardware.org/?probe=05d0bf9d8d) | Nov 25, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [c639db74cb](https://linux-hardware.org/?probe=c639db74cb) | Nov 25, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [c43b60c09b](https://linux-hardware.org/?probe=c43b60c09b) | Nov 25, 2022 |
| PCWare        | APM-A320G                   | Desktop     | [a56cdcbd3b](https://linux-hardware.org/?probe=a56cdcbd3b) | Nov 24, 2022 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | Notebook    | [418849100f](https://linux-hardware.org/?probe=418849100f) | Nov 24, 2022 |
| Avell High... | STORM TWO                   | Notebook    | [d8a406b26c](https://linux-hardware.org/?probe=d8a406b26c) | Nov 24, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [2b2778b81a](https://linux-hardware.org/?probe=2b2778b81a) | Nov 24, 2022 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [7d448ab5cc](https://linux-hardware.org/?probe=7d448ab5cc) | Nov 24, 2022 |
| Sony          | VPCEA23FB                   | Notebook    | [187f57793d](https://linux-hardware.org/?probe=187f57793d) | Nov 24, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [96a68d5d80](https://linux-hardware.org/?probe=96a68d5d80) | Nov 24, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [93e1fc870a](https://linux-hardware.org/?probe=93e1fc870a) | Nov 24, 2022 |
| Supermicro    | PDSMi+                      | Desktop     | [3a70b82d42](https://linux-hardware.org/?probe=3a70b82d42) | Nov 24, 2022 |
| Intel         | B75                         | Desktop     | [a8932d4a21](https://linux-hardware.org/?probe=a8932d4a21) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [47116ddd3e](https://linux-hardware.org/?probe=47116ddd3e) | Nov 24, 2022 |
| Toshiba       | IS 1442                     | Notebook    | [8a2d7b5a48](https://linux-hardware.org/?probe=8a2d7b5a48) | Nov 23, 2022 |
| HP            | 0266                        | Desktop     | [13e2e10478](https://linux-hardware.org/?probe=13e2e10478) | Nov 23, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [bc690a128e](https://linux-hardware.org/?probe=bc690a128e) | Nov 23, 2022 |
| Dell          | System Vostro 3460          | Notebook    | [4f9fb6602d](https://linux-hardware.org/?probe=4f9fb6602d) | Nov 23, 2022 |
| Samsung       | 270E5K                      | Notebook    | [871e23c67c](https://linux-hardware.org/?probe=871e23c67c) | Nov 23, 2022 |
| Samsung       | 270E5K                      | Notebook    | [398893bbd1](https://linux-hardware.org/?probe=398893bbd1) | Nov 23, 2022 |
| MSI           | 2A9C                        | Desktop     | [ee8683a595](https://linux-hardware.org/?probe=ee8683a595) | Nov 23, 2022 |
| MSI           | 2A9C                        | Desktop     | [77dd7e3fbc](https://linux-hardware.org/?probe=77dd7e3fbc) | Nov 23, 2022 |
| Positivo      | Mobile                      | Notebook    | [609b7ff8c9](https://linux-hardware.org/?probe=609b7ff8c9) | Nov 22, 2022 |
| Positivo      | Mobile                      | Notebook    | [5e1d512269](https://linux-hardware.org/?probe=5e1d512269) | Nov 22, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | Notebook    | [0fd3b230e0](https://linux-hardware.org/?probe=0fd3b230e0) | Nov 22, 2022 |
| Intel         | B75                         | Desktop     | [24b64d225a](https://linux-hardware.org/?probe=24b64d225a) | Nov 22, 2022 |
| PCWare        | IPMH61R2                    | Desktop     | [93db11744b](https://linux-hardware.org/?probe=93db11744b) | Nov 22, 2022 |
| PCWare        | IPMH110G                    | Desktop     | [7d952c2b0d](https://linux-hardware.org/?probe=7d952c2b0d) | Nov 22, 2022 |
| Dell          | Vostro 3501                 | Notebook    | [ea7c3c0cc4](https://linux-hardware.org/?probe=ea7c3c0cc4) | Nov 22, 2022 |
| Acer          | Aspire E5-574G              | Notebook    | [703b6ee54d](https://linux-hardware.org/?probe=703b6ee54d) | Nov 22, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [0dcdb72cd6](https://linux-hardware.org/?probe=0dcdb72cd6) | Nov 22, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [57b2e84560](https://linux-hardware.org/?probe=57b2e84560) | Nov 22, 2022 |
| Dell          | Latitude 5480               | Notebook    | [5b9f1e717c](https://linux-hardware.org/?probe=5b9f1e717c) | Nov 21, 2022 |
| ASUSTek       | X541NA                      | Notebook    | [8c624c76fa](https://linux-hardware.org/?probe=8c624c76fa) | Nov 21, 2022 |
| Dell          | Inspiron 5548               | Notebook    | [8d8a193e7b](https://linux-hardware.org/?probe=8d8a193e7b) | Nov 21, 2022 |
| Biostar       | A320MH                      | Desktop     | [79eeacd665](https://linux-hardware.org/?probe=79eeacd665) | Nov 21, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [d9678fb5a7](https://linux-hardware.org/?probe=d9678fb5a7) | Nov 21, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [ac4a817e75](https://linux-hardware.org/?probe=ac4a817e75) | Nov 21, 2022 |
| ASRock        | H310CM-HG4                  | Desktop     | [d4f3608765](https://linux-hardware.org/?probe=d4f3608765) | Nov 21, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [b2f3b998a2](https://linux-hardware.org/?probe=b2f3b998a2) | Nov 21, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [308968646b](https://linux-hardware.org/?probe=308968646b) | Nov 21, 2022 |
| Toshiba       | IS 1422                     | Notebook    | [aa59e6576d](https://linux-hardware.org/?probe=aa59e6576d) | Nov 21, 2022 |
| ASUSTek       | X541NA                      | Notebook    | [aa4d9601ee](https://linux-hardware.org/?probe=aa4d9601ee) | Nov 21, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [4599b81a6b](https://linux-hardware.org/?probe=4599b81a6b) | Nov 21, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [5739045caa](https://linux-hardware.org/?probe=5739045caa) | Nov 20, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [18f301f8c5](https://linux-hardware.org/?probe=18f301f8c5) | Nov 20, 2022 |
| Dell          | Vostro 3458                 | Notebook    | [9f05e54f99](https://linux-hardware.org/?probe=9f05e54f99) | Nov 20, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [cd0f904ca4](https://linux-hardware.org/?probe=cd0f904ca4) | Nov 20, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [c4bd142690](https://linux-hardware.org/?probe=c4bd142690) | Nov 20, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [93bb909388](https://linux-hardware.org/?probe=93bb909388) | Nov 20, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [11e00d597d](https://linux-hardware.org/?probe=11e00d597d) | Nov 20, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [c6b85f956a](https://linux-hardware.org/?probe=c6b85f956a) | Nov 20, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [0735dabc9b](https://linux-hardware.org/?probe=0735dabc9b) | Nov 20, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [35fc3411ec](https://linux-hardware.org/?probe=35fc3411ec) | Nov 20, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [1253590f60](https://linux-hardware.org/?probe=1253590f60) | Nov 20, 2022 |
| Samsung       | 767XCL                      | Notebook    | [729f4f303e](https://linux-hardware.org/?probe=729f4f303e) | Nov 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [e777561ba5](https://linux-hardware.org/?probe=e777561ba5) | Nov 19, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [2033b97419](https://linux-hardware.org/?probe=2033b97419) | Nov 19, 2022 |
| HP            | ProBook 6450b               | Notebook    | [10c8ec5d4c](https://linux-hardware.org/?probe=10c8ec5d4c) | Nov 19, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [496647cddb](https://linux-hardware.org/?probe=496647cddb) | Nov 19, 2022 |
| MSI           | H61M-P21                    | Desktop     | [a91ee7dc9d](https://linux-hardware.org/?probe=a91ee7dc9d) | Nov 19, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [5d6f9e57c5](https://linux-hardware.org/?probe=5d6f9e57c5) | Nov 19, 2022 |
| Dell          | Vostro 3501                 | Notebook    | [39ecfb673f](https://linux-hardware.org/?probe=39ecfb673f) | Nov 19, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [1d527a6849](https://linux-hardware.org/?probe=1d527a6849) | Nov 18, 2022 |
| Dell          | Inspiron 7348               | Notebook    | [6a46a84480](https://linux-hardware.org/?probe=6a46a84480) | Nov 18, 2022 |
| ASUSTek       | P8H61-M PLUS V2             | Desktop     | [ff279b1860](https://linux-hardware.org/?probe=ff279b1860) | Nov 18, 2022 |
| Dell          | 0KWVT8 A02                  | Desktop     | [e1b586a15a](https://linux-hardware.org/?probe=e1b586a15a) | Nov 18, 2022 |
| Gigabyte      | G31M-S2L                    | Desktop     | [bc588177c4](https://linux-hardware.org/?probe=bc588177c4) | Nov 18, 2022 |
| HP            | 14                          | Notebook    | [958eb656f2](https://linux-hardware.org/?probe=958eb656f2) | Nov 18, 2022 |
| AMD           | A88                         | Desktop     | [4f23ffbfe2](https://linux-hardware.org/?probe=4f23ffbfe2) | Nov 18, 2022 |
| HP            | 14                          | Notebook    | [8e4d001eb6](https://linux-hardware.org/?probe=8e4d001eb6) | Nov 18, 2022 |
| Huanan        | X99-8M-F V1.1               | Desktop     | [b1d1b0ad4c](https://linux-hardware.org/?probe=b1d1b0ad4c) | Nov 18, 2022 |
| HP            | Presario CQ43               | Notebook    | [0ed80872c0](https://linux-hardware.org/?probe=0ed80872c0) | Nov 18, 2022 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | Notebook    | [f796cfccaa](https://linux-hardware.org/?probe=f796cfccaa) | Nov 17, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [873552cfae](https://linux-hardware.org/?probe=873552cfae) | Nov 17, 2022 |
| Compaq        | 420                         | Notebook    | [07ab1c2b0f](https://linux-hardware.org/?probe=07ab1c2b0f) | Nov 17, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [d71e1be6dc](https://linux-hardware.org/?probe=d71e1be6dc) | Nov 17, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [f2e60e58dc](https://linux-hardware.org/?probe=f2e60e58dc) | Nov 17, 2022 |
| PCWare        | IPX4005G                    | Desktop     | [9989340108](https://linux-hardware.org/?probe=9989340108) | Nov 17, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [7d7f4061fa](https://linux-hardware.org/?probe=7d7f4061fa) | Nov 17, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [d36317c3be](https://linux-hardware.org/?probe=d36317c3be) | Nov 17, 2022 |
| Login Info... | LOG-H61H2-M2                | Desktop     | [aff41de38e](https://linux-hardware.org/?probe=aff41de38e) | Nov 17, 2022 |
| ASUSTek       | P5KPL/1600                  | Desktop     | [24b13d1967](https://linux-hardware.org/?probe=24b13d1967) | Nov 16, 2022 |
| Dell          | G15 5510                    | Notebook    | [5d9d96d71e](https://linux-hardware.org/?probe=5d9d96d71e) | Nov 16, 2022 |
| Huanan        | X99-8M-F V1.1               | Desktop     | [0a623c060a](https://linux-hardware.org/?probe=0a623c060a) | Nov 16, 2022 |
| Intel         | H61                         | Desktop     | [faeac27433](https://linux-hardware.org/?probe=faeac27433) | Nov 16, 2022 |
| Acer          | Aspire V3-571               | Notebook    | [7aa6773734](https://linux-hardware.org/?probe=7aa6773734) | Nov 16, 2022 |
| Acer          | Aspire V3-571               | Notebook    | [d5c4a2f02e](https://linux-hardware.org/?probe=d5c4a2f02e) | Nov 16, 2022 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | Notebook    | [16dc745785](https://linux-hardware.org/?probe=16dc745785) | Nov 16, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [1dc59dc45d](https://linux-hardware.org/?probe=1dc59dc45d) | Nov 16, 2022 |
| Sony          | SVE14A15FBB                 | Notebook    | [1b368520d1](https://linux-hardware.org/?probe=1b368520d1) | Nov 16, 2022 |
| ALDO          | C2016-BSWI-D2               | Desktop     | [0e4c4c6806](https://linux-hardware.org/?probe=0e4c4c6806) | Nov 16, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [41a49817ef](https://linux-hardware.org/?probe=41a49817ef) | Nov 16, 2022 |
| Positivo B... | VJFE44F11X-B2111H           | Notebook    | [070af1bd42](https://linux-hardware.org/?probe=070af1bd42) | Nov 16, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [fe43edb930](https://linux-hardware.org/?probe=fe43edb930) | Nov 16, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [3e04c315ee](https://linux-hardware.org/?probe=3e04c315ee) | Nov 15, 2022 |
| Daten Tecn... | DT02-M4                     | Notebook    | [783a9a5607](https://linux-hardware.org/?probe=783a9a5607) | Nov 15, 2022 |
| Gateway       | NV55C                       | Notebook    | [64d8e467d4](https://linux-hardware.org/?probe=64d8e467d4) | Nov 15, 2022 |
| Dell          | 0RW199                      | Desktop     | [df40ccbcdb](https://linux-hardware.org/?probe=df40ccbcdb) | Nov 15, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [e7f05e6eac](https://linux-hardware.org/?probe=e7f05e6eac) | Nov 15, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [16e5672a66](https://linux-hardware.org/?probe=16e5672a66) | Nov 15, 2022 |
| Acer          | Aspire ES1-572              | Notebook    | [a21cf96dd6](https://linux-hardware.org/?probe=a21cf96dd6) | Nov 15, 2022 |
| Acer          | Aspire ES1-572              | Notebook    | [14e272fe11](https://linux-hardware.org/?probe=14e272fe11) | Nov 15, 2022 |
| Intel         | NUC7JYB M37316-500          | Mini pc     | [fba07c4e71](https://linux-hardware.org/?probe=fba07c4e71) | Nov 14, 2022 |
| Samsung       | RV411                       | Notebook    | [ded212573f](https://linux-hardware.org/?probe=ded212573f) | Nov 14, 2022 |
| Huanan        | X99-F8                      | Desktop     | [0e3b4121ea](https://linux-hardware.org/?probe=0e3b4121ea) | Nov 14, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [c6b6ee8cc8](https://linux-hardware.org/?probe=c6b6ee8cc8) | Nov 14, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [e751f32d49](https://linux-hardware.org/?probe=e751f32d49) | Nov 14, 2022 |
| Dell          | Inspiron 7560               | Notebook    | [45474958e5](https://linux-hardware.org/?probe=45474958e5) | Nov 14, 2022 |
| Lenovo        | G50-80 80R0                 | Notebook    | [35193d2431](https://linux-hardware.org/?probe=35193d2431) | Nov 14, 2022 |
| Dell          | Vostro 5470                 | Notebook    | [5b542891b7](https://linux-hardware.org/?probe=5b542891b7) | Nov 14, 2022 |
| Multilaser    | PC121                       | Notebook    | [5870f0d565](https://linux-hardware.org/?probe=5870f0d565) | Nov 14, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [5b9f10af19](https://linux-hardware.org/?probe=5b9f10af19) | Nov 14, 2022 |
| Gigabyte      | Z370XP SLI-CF               | Desktop     | [3b6d611387](https://linux-hardware.org/?probe=3b6d611387) | Nov 14, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [62348f8b41](https://linux-hardware.org/?probe=62348f8b41) | Nov 13, 2022 |
| Acer          | Nitro AN517-54              | Notebook    | [b5c1404ef7](https://linux-hardware.org/?probe=b5c1404ef7) | Nov 13, 2022 |
| PCWare        | IPMH61R3                    | Desktop     | [7b7925f93d](https://linux-hardware.org/?probe=7b7925f93d) | Nov 13, 2022 |
| ASUSTek       | TUF B360-PLUS GAMING        | Desktop     | [d29245dafc](https://linux-hardware.org/?probe=d29245dafc) | Nov 13, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [7de064ae3a](https://linux-hardware.org/?probe=7de064ae3a) | Nov 13, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [bf79743ff5](https://linux-hardware.org/?probe=bf79743ff5) | Nov 13, 2022 |
| Dell          | G15 5510                    | Notebook    | [641a09f9cc](https://linux-hardware.org/?probe=641a09f9cc) | Nov 13, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [8cb389e68e](https://linux-hardware.org/?probe=8cb389e68e) | Nov 13, 2022 |
| Google        | Celes                       | Notebook    | [4b15e527d5](https://linux-hardware.org/?probe=4b15e527d5) | Nov 12, 2022 |
| Google        | Celes                       | Notebook    | [68323b0e01](https://linux-hardware.org/?probe=68323b0e01) | Nov 12, 2022 |
| Intel         | H55                         | Desktop     | [b3cbb34a98](https://linux-hardware.org/?probe=b3cbb34a98) | Nov 12, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [95f38cc8d9](https://linux-hardware.org/?probe=95f38cc8d9) | Nov 12, 2022 |
| Intel         | H55                         | Desktop     | [c4171c6957](https://linux-hardware.org/?probe=c4171c6957) | Nov 12, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [d9dd29ce39](https://linux-hardware.org/?probe=d9dd29ce39) | Nov 12, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [2dc75b76f4](https://linux-hardware.org/?probe=2dc75b76f4) | Nov 12, 2022 |
| Colorful T... | DJ H310M-E V20              | Desktop     | [6ac470070c](https://linux-hardware.org/?probe=6ac470070c) | Nov 12, 2022 |
| Gigabyte      | Z370XP SLI-CF               | Desktop     | [4e0b0368b8](https://linux-hardware.org/?probe=4e0b0368b8) | Nov 12, 2022 |
| Standard      | MB40II                      | Notebook    | [c95529c90a](https://linux-hardware.org/?probe=c95529c90a) | Nov 12, 2022 |
| Sony          | VGN-CR120E                  | Notebook    | [99def76c59](https://linux-hardware.org/?probe=99def76c59) | Nov 12, 2022 |
| Sony          | VGN-CR120E                  | Notebook    | [d3b618e418](https://linux-hardware.org/?probe=d3b618e418) | Nov 12, 2022 |
| Intel         | H61                         | Desktop     | [7d93f12ac4](https://linux-hardware.org/?probe=7d93f12ac4) | Nov 11, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [3c63d3fb1e](https://linux-hardware.org/?probe=3c63d3fb1e) | Nov 11, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [01a339fb27](https://linux-hardware.org/?probe=01a339fb27) | Nov 11, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [3acc2b87a6](https://linux-hardware.org/?probe=3acc2b87a6) | Nov 11, 2022 |
| Gigabyte      | H110M-S2H DDR3-CF           | Desktop     | [13f37888d5](https://linux-hardware.org/?probe=13f37888d5) | Nov 11, 2022 |
| LG Electro... | 15Z970-E.BH91P1             | Notebook    | [347940efc3](https://linux-hardware.org/?probe=347940efc3) | Nov 11, 2022 |
| Toshiba       | IS 1422+                    | Notebook    | [0c948c9926](https://linux-hardware.org/?probe=0c948c9926) | Nov 11, 2022 |
| Intel         | DG41WV AAE90316-102         | Desktop     | [517598326a](https://linux-hardware.org/?probe=517598326a) | Nov 10, 2022 |
| Positivo B... | VJFE53F11X-XXXXXX           | Notebook    | [7e81c7cf85](https://linux-hardware.org/?probe=7e81c7cf85) | Nov 10, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [fb2b32db6a](https://linux-hardware.org/?probe=fb2b32db6a) | Nov 10, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [8bb3389cc1](https://linux-hardware.org/?probe=8bb3389cc1) | Nov 10, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | Desktop     | [f20eddfba9](https://linux-hardware.org/?probe=f20eddfba9) | Nov 10, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [0e624570e1](https://linux-hardware.org/?probe=0e624570e1) | Nov 10, 2022 |
| Positivo      | POS-EIH61CR POSITIVO        | Desktop     | [81bd40e949](https://linux-hardware.org/?probe=81bd40e949) | Nov 10, 2022 |
| PCWare        | IPMH61R1                    | Desktop     | [6a668c9151](https://linux-hardware.org/?probe=6a668c9151) | Nov 09, 2022 |
| Dell          | 0RW203 A00                  | Desktop     | [67fa42f70a](https://linux-hardware.org/?probe=67fa42f70a) | Nov 09, 2022 |
| Acer          | Aspire 5742                 | Notebook    | [9c688c611e](https://linux-hardware.org/?probe=9c688c611e) | Nov 09, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [73c9a3d81e](https://linux-hardware.org/?probe=73c9a3d81e) | Nov 09, 2022 |
| Foxconn       | H61M-S/H61M                 | Desktop     | [81b2006fd3](https://linux-hardware.org/?probe=81b2006fd3) | Nov 09, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | Desktop     | [3e90cd2d25](https://linux-hardware.org/?probe=3e90cd2d25) | Nov 09, 2022 |
| OKI Brasil    | ST 4280 Padrao              | Desktop     | [f2841b0f4d](https://linux-hardware.org/?probe=f2841b0f4d) | Nov 08, 2022 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [3ffeeccb58](https://linux-hardware.org/?probe=3ffeeccb58) | Nov 08, 2022 |
| OKI Brasil    | ST 4280 Padrao              | Desktop     | [58cb07d7e1](https://linux-hardware.org/?probe=58cb07d7e1) | Nov 08, 2022 |
| HP            | Pavilion dv2700             | Notebook    | [a8e36a1579](https://linux-hardware.org/?probe=a8e36a1579) | Nov 08, 2022 |
| H-BUSTER      | HBNB1403                    | Notebook    | [9d439a53b2](https://linux-hardware.org/?probe=9d439a53b2) | Nov 08, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [533c6216c7](https://linux-hardware.org/?probe=533c6216c7) | Nov 08, 2022 |
| Alienware     | m15 R6                      | Notebook    | [63b53e81ed](https://linux-hardware.org/?probe=63b53e81ed) | Nov 08, 2022 |
| Alienware     | m15 R6                      | Notebook    | [22b8b36df5](https://linux-hardware.org/?probe=22b8b36df5) | Nov 08, 2022 |
| Alienware     | m15 R6                      | Notebook    | [3e808157a3](https://linux-hardware.org/?probe=3e808157a3) | Nov 08, 2022 |
| Samsung       | 500R4K/500R5H/5400RK/501... | Notebook    | [9979d8a6b6](https://linux-hardware.org/?probe=9979d8a6b6) | Nov 08, 2022 |
| Intel         | H61                         | Desktop     | [67af788bd9](https://linux-hardware.org/?probe=67af788bd9) | Nov 08, 2022 |
| Intel         | NUC11TNBi3 M11908-403       | Mini pc     | [c949ec23ce](https://linux-hardware.org/?probe=c949ec23ce) | Nov 07, 2022 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [732e924bbb](https://linux-hardware.org/?probe=732e924bbb) | Nov 07, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [b981adc21a](https://linux-hardware.org/?probe=b981adc21a) | Nov 07, 2022 |
| Intel         | NUC11TNBi3 M11908-403       | Mini pc     | [02610c1e36](https://linux-hardware.org/?probe=02610c1e36) | Nov 07, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [a4bce0a93a](https://linux-hardware.org/?probe=a4bce0a93a) | Nov 07, 2022 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [589354a449](https://linux-hardware.org/?probe=589354a449) | Nov 07, 2022 |
| Dell          | Latitude 3410               | Notebook    | [f6532fe0ee](https://linux-hardware.org/?probe=f6532fe0ee) | Nov 07, 2022 |
| Intel         | NUC7JYB M37316-500          | Mini pc     | [de9cc7561d](https://linux-hardware.org/?probe=de9cc7561d) | Nov 07, 2022 |
| ASRock        | AB350M                      | Desktop     | [fae0de4ece](https://linux-hardware.org/?probe=fae0de4ece) | Nov 07, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [c2f8bf4caf](https://linux-hardware.org/?probe=c2f8bf4caf) | Nov 07, 2022 |
| ASUSTek       | K52Jr                       | Notebook    | [7be3408f46](https://linux-hardware.org/?probe=7be3408f46) | Nov 07, 2022 |
| Lenovo        | G475 20080                  | Notebook    | [f0f78f8e7e](https://linux-hardware.org/?probe=f0f78f8e7e) | Nov 07, 2022 |
| Dell          | 0GDG8Y A02                  | Desktop     | [e61ccb96d0](https://linux-hardware.org/?probe=e61ccb96d0) | Nov 06, 2022 |
| Acer          | Aspire 5742                 | Notebook    | [028e3c3f64](https://linux-hardware.org/?probe=028e3c3f64) | Nov 06, 2022 |
| Samsung       | 550XDA                      | Notebook    | [a57a40964e](https://linux-hardware.org/?probe=a57a40964e) | Nov 06, 2022 |
| PCWare        | IPMH110G                    | Desktop     | [3409bf9968](https://linux-hardware.org/?probe=3409bf9968) | Nov 06, 2022 |
| Gigabyte      | A320M-HD2-CF                | Desktop     | [185fcc2c4f](https://linux-hardware.org/?probe=185fcc2c4f) | Nov 06, 2022 |
| Lenovo        | IdeaPad Z400 Touch VIWZ1    | Notebook    | [5afc3788fc](https://linux-hardware.org/?probe=5afc3788fc) | Nov 06, 2022 |
| Gigabyte      | A320M-HD2-CF                | Desktop     | [7d038a7549](https://linux-hardware.org/?probe=7d038a7549) | Nov 06, 2022 |
| Huanan        | X99-F8D PLUS V1.1           | Desktop     | [a552bf9362](https://linux-hardware.org/?probe=a552bf9362) | Nov 06, 2022 |
| Quanta        | TWS                         | Notebook    | [1ad872afcd](https://linux-hardware.org/?probe=1ad872afcd) | Nov 06, 2022 |
| Positivo      | W940TU                      | Notebook    | [ad13b613fa](https://linux-hardware.org/?probe=ad13b613fa) | Nov 06, 2022 |
| Quanta        | TWS                         | Notebook    | [a800f54191](https://linux-hardware.org/?probe=a800f54191) | Nov 06, 2022 |
| Positivo      | W940TU                      | Notebook    | [ee23486fc7](https://linux-hardware.org/?probe=ee23486fc7) | Nov 06, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [91851e068d](https://linux-hardware.org/?probe=91851e068d) | Nov 06, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [f72391a03b](https://linux-hardware.org/?probe=f72391a03b) | Nov 05, 2022 |
| Dell          | Inspiron 5402               | Notebook    | [109f44c580](https://linux-hardware.org/?probe=109f44c580) | Nov 05, 2022 |
| MSI           | Z170A SLI PLUS              | Desktop     | [f9b39389e6](https://linux-hardware.org/?probe=f9b39389e6) | Nov 05, 2022 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [1466580b6e](https://linux-hardware.org/?probe=1466580b6e) | Nov 05, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [0f6ca0628c](https://linux-hardware.org/?probe=0f6ca0628c) | Nov 05, 2022 |
| Dell          | Vostro 13 5310              | Notebook    | [c25e192969](https://linux-hardware.org/?probe=c25e192969) | Nov 05, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [e4d9794c31](https://linux-hardware.org/?probe=e4d9794c31) | Nov 05, 2022 |
| VS Company    | MCP61M                      | Desktop     | [ef6adc510d](https://linux-hardware.org/?probe=ef6adc510d) | Nov 05, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [e56aa65a39](https://linux-hardware.org/?probe=e56aa65a39) | Nov 05, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [71fac7ca47](https://linux-hardware.org/?probe=71fac7ca47) | Nov 05, 2022 |
| Toshiba       | IS 1422                     | Notebook    | [2ea67b9fac](https://linux-hardware.org/?probe=2ea67b9fac) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [118a1f505b](https://linux-hardware.org/?probe=118a1f505b) | Nov 04, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [31234e156e](https://linux-hardware.org/?probe=31234e156e) | Nov 04, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [787df838b7](https://linux-hardware.org/?probe=787df838b7) | Nov 04, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [03176fa010](https://linux-hardware.org/?probe=03176fa010) | Nov 04, 2022 |
| Dell          | G15 5511                    | Notebook    | [68f1e6d4f0](https://linux-hardware.org/?probe=68f1e6d4f0) | Nov 04, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [8607fcf09d](https://linux-hardware.org/?probe=8607fcf09d) | Nov 04, 2022 |
| Sony          | VPCEA23FB                   | Notebook    | [ff50b0dd2a](https://linux-hardware.org/?probe=ff50b0dd2a) | Nov 04, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [9fec26118c](https://linux-hardware.org/?probe=9fec26118c) | Nov 04, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [60d8b24187](https://linux-hardware.org/?probe=60d8b24187) | Nov 04, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [81c0293410](https://linux-hardware.org/?probe=81c0293410) | Nov 04, 2022 |
| Sony          | VPCEB4L1E                   | Notebook    | [5448ca63bc](https://linux-hardware.org/?probe=5448ca63bc) | Nov 04, 2022 |
| Timi          | RedmiBook Pro 14S           | Notebook    | [9fbf084c28](https://linux-hardware.org/?probe=9fbf084c28) | Nov 04, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [dab31889f1](https://linux-hardware.org/?probe=dab31889f1) | Nov 04, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [0081f15a32](https://linux-hardware.org/?probe=0081f15a32) | Nov 03, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [0f369008f6](https://linux-hardware.org/?probe=0f369008f6) | Nov 03, 2022 |
| Avell High... | B.ON                        | Notebook    | [f0ea745f7d](https://linux-hardware.org/?probe=f0ea745f7d) | Nov 03, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [ec0599883c](https://linux-hardware.org/?probe=ec0599883c) | Nov 03, 2022 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [1d618807a7](https://linux-hardware.org/?probe=1d618807a7) | Nov 03, 2022 |
| Colorful T... | A320M-K PRO YV14            | Desktop     | [cf54f0dbf3](https://linux-hardware.org/?probe=cf54f0dbf3) | Nov 03, 2022 |
| Colorful T... | A320M-K PRO YV14            | Desktop     | [5059f2f52e](https://linux-hardware.org/?probe=5059f2f52e) | Nov 03, 2022 |
| Intel         | powered classmate PC        | Notebook    | [5e9392864a](https://linux-hardware.org/?probe=5e9392864a) | Nov 03, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [d4f292aa03](https://linux-hardware.org/?probe=d4f292aa03) | Nov 03, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [43609f5bd5](https://linux-hardware.org/?probe=43609f5bd5) | Nov 03, 2022 |
| Gigabyte      | H81M-S1                     | Desktop     | [fa134687f2](https://linux-hardware.org/?probe=fa134687f2) | Nov 03, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [5c0b61dfb6](https://linux-hardware.org/?probe=5c0b61dfb6) | Nov 03, 2022 |
| Positivo      | Mobile                      | Notebook    | [f35235fdfa](https://linux-hardware.org/?probe=f35235fdfa) | Nov 03, 2022 |
| Positivo      | Mobile                      | Notebook    | [581c79bdee](https://linux-hardware.org/?probe=581c79bdee) | Nov 03, 2022 |
| Lenovo        | NOK                         | Desktop     | [8c9f8ff505](https://linux-hardware.org/?probe=8c9f8ff505) | Nov 03, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [342c7609c9](https://linux-hardware.org/?probe=342c7609c9) | Nov 02, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [df76e744d7](https://linux-hardware.org/?probe=df76e744d7) | Nov 02, 2022 |
| Daten Tecn... | DT02-M4                     | Notebook    | [cdd5c3cca0](https://linux-hardware.org/?probe=cdd5c3cca0) | Nov 02, 2022 |
| Daten Tecn... | DT02-M4                     | Notebook    | [7d43f3c00b](https://linux-hardware.org/?probe=7d43f3c00b) | Nov 02, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [5b45883fef](https://linux-hardware.org/?probe=5b45883fef) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a156a7484d](https://linux-hardware.org/?probe=a156a7484d) | Nov 02, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [39cb4cb083](https://linux-hardware.org/?probe=39cb4cb083) | Nov 02, 2022 |
| ASRock        | N68-S3 FX                   | Desktop     | [22f68458d4](https://linux-hardware.org/?probe=22f68458d4) | Nov 02, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [7b42bc51be](https://linux-hardware.org/?probe=7b42bc51be) | Nov 02, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [47c34f9269](https://linux-hardware.org/?probe=47c34f9269) | Nov 02, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6 82JF    | Notebook    | [09c2704bb0](https://linux-hardware.org/?probe=09c2704bb0) | Nov 02, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [0f40b36846](https://linux-hardware.org/?probe=0f40b36846) | Nov 02, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [6b48759d1d](https://linux-hardware.org/?probe=6b48759d1d) | Nov 02, 2022 |
| MSI           | H61M-P31                    | Desktop     | [819c124b25](https://linux-hardware.org/?probe=819c124b25) | Nov 01, 2022 |
| VS Company    | G31T-M                      | Desktop     | [75eb6866e0](https://linux-hardware.org/?probe=75eb6866e0) | Nov 01, 2022 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [9704a12e23](https://linux-hardware.org/?probe=9704a12e23) | Nov 01, 2022 |
| HP            | Pavilion 15                 | Notebook    | [8552c17b28](https://linux-hardware.org/?probe=8552c17b28) | Nov 01, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [053e74af53](https://linux-hardware.org/?probe=053e74af53) | Nov 01, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81JM     | Notebook    | [da8fec7ac4](https://linux-hardware.org/?probe=da8fec7ac4) | Nov 01, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [dab530a737](https://linux-hardware.org/?probe=dab530a737) | Nov 01, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [6b2b490208](https://linux-hardware.org/?probe=6b2b490208) | Nov 01, 2022 |
| Samsung       | 800G5M/800G5W               | Notebook    | [c91800e8c1](https://linux-hardware.org/?probe=c91800e8c1) | Oct 31, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [973fc77891](https://linux-hardware.org/?probe=973fc77891) | Oct 31, 2022 |
| Pegatron      | 2AABh                       | Desktop     | [94dd13992c](https://linux-hardware.org/?probe=94dd13992c) | Oct 31, 2022 |
| LG Electro... | A560-T.BG77P1               | Notebook    | [cad4120a42](https://linux-hardware.org/?probe=cad4120a42) | Oct 31, 2022 |
| Avell High... | B.ON                        | Notebook    | [1eb1bf21ed](https://linux-hardware.org/?probe=1eb1bf21ed) | Oct 31, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [fffb5288e0](https://linux-hardware.org/?probe=fffb5288e0) | Oct 31, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [0c1875c94f](https://linux-hardware.org/?probe=0c1875c94f) | Oct 31, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [1b626eed02](https://linux-hardware.org/?probe=1b626eed02) | Oct 31, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [c8970ae94a](https://linux-hardware.org/?probe=c8970ae94a) | Oct 31, 2022 |
| MSI           | Z97 GAMING 3                | Desktop     | [cc2d45c3ff](https://linux-hardware.org/?probe=cc2d45c3ff) | Oct 30, 2022 |
| MSI           | Z97 GAMING 3                | Desktop     | [c0926e68a0](https://linux-hardware.org/?probe=c0926e68a0) | Oct 30, 2022 |
| Pegatron      | IPMIP-GS                    | Desktop     | [4e46d903ae](https://linux-hardware.org/?probe=4e46d903ae) | Oct 30, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [12380f78de](https://linux-hardware.org/?probe=12380f78de) | Oct 30, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [93d25dfb1f](https://linux-hardware.org/?probe=93d25dfb1f) | Oct 30, 2022 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [8384c9e137](https://linux-hardware.org/?probe=8384c9e137) | Oct 30, 2022 |
| MSI           | B250M GAMING PRO            | Desktop     | [98979beea7](https://linux-hardware.org/?probe=98979beea7) | Oct 30, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [d7e9fb65d0](https://linux-hardware.org/?probe=d7e9fb65d0) | Oct 30, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [9991d15803](https://linux-hardware.org/?probe=9991d15803) | Oct 30, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [c49a76df2a](https://linux-hardware.org/?probe=c49a76df2a) | Oct 30, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c11b330691](https://linux-hardware.org/?probe=c11b330691) | Oct 30, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [1b03bb8445](https://linux-hardware.org/?probe=1b03bb8445) | Oct 30, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [97d7d8c2d9](https://linux-hardware.org/?probe=97d7d8c2d9) | Oct 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [eb71b41aa8](https://linux-hardware.org/?probe=eb71b41aa8) | Oct 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [ae6fd2de89](https://linux-hardware.org/?probe=ae6fd2de89) | Oct 29, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [13a12cbd22](https://linux-hardware.org/?probe=13a12cbd22) | Oct 29, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [650f1fd648](https://linux-hardware.org/?probe=650f1fd648) | Oct 29, 2022 |
| Samsung       | 800G5M/800G5W               | Notebook    | [d688233d28](https://linux-hardware.org/?probe=d688233d28) | Oct 29, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [f27aa95917](https://linux-hardware.org/?probe=f27aa95917) | Oct 29, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [182d67f23e](https://linux-hardware.org/?probe=182d67f23e) | Oct 29, 2022 |
| HP            | InsydeH2O EFI BIOS          | Notebook    | [d157bdbc2b](https://linux-hardware.org/?probe=d157bdbc2b) | Oct 29, 2022 |
| ASUSTek       | PRIME H410M-K               | Desktop     | [5a371accfe](https://linux-hardware.org/?probe=5a371accfe) | Oct 29, 2022 |
| Dell          | Precision 5750              | Notebook    | [9b9addd3b7](https://linux-hardware.org/?probe=9b9addd3b7) | Oct 29, 2022 |
| Acer          | Aspire 4745Z                | Notebook    | [baf4fe6e63](https://linux-hardware.org/?probe=baf4fe6e63) | Oct 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [893d006e2f](https://linux-hardware.org/?probe=893d006e2f) | Oct 29, 2022 |
| Samsung       | 670Z5E                      | Notebook    | [159f89858c](https://linux-hardware.org/?probe=159f89858c) | Oct 28, 2022 |
| ASRock        | H510M-HVS                   | Desktop     | [e9ce2f5011](https://linux-hardware.org/?probe=e9ce2f5011) | Oct 28, 2022 |
| Lenovo        | ThinkCentre M58p 6234CZ6    | Desktop     | [5831a0d715](https://linux-hardware.org/?probe=5831a0d715) | Oct 28, 2022 |
| Intel         | B75                         | Desktop     | [59cc97d6c7](https://linux-hardware.org/?probe=59cc97d6c7) | Oct 28, 2022 |
| ASRock        | H510M-HVS                   | Desktop     | [e377db3a9e](https://linux-hardware.org/?probe=e377db3a9e) | Oct 28, 2022 |
| Avell High... | B.ON                        | Notebook    | [194a1eddc3](https://linux-hardware.org/?probe=194a1eddc3) | Oct 28, 2022 |
| Lenovo        | Legion Y540-15IRH 81RJ      | Notebook    | [a90eba59e8](https://linux-hardware.org/?probe=a90eba59e8) | Oct 28, 2022 |
| Samsung       | 275E4E/275E5E               | Notebook    | [d3aebcbac6](https://linux-hardware.org/?probe=d3aebcbac6) | Oct 27, 2022 |
| LG Electro... | 22V280 FAB1                 | All in one  | [9c7127a256](https://linux-hardware.org/?probe=9c7127a256) | Oct 27, 2022 |
| Lenovo        | Unknown                     | Notebook    | [6a3e704d70](https://linux-hardware.org/?probe=6a3e704d70) | Oct 27, 2022 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [fe1166a134](https://linux-hardware.org/?probe=fe1166a134) | Oct 27, 2022 |
| Samsung       | 760XBE                      | Notebook    | [436b83d360](https://linux-hardware.org/?probe=436b83d360) | Oct 27, 2022 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [b35b1298a8](https://linux-hardware.org/?probe=b35b1298a8) | Oct 27, 2022 |
| Lenovo        | 3102 NOK                    | Desktop     | [973ebfcf3e](https://linux-hardware.org/?probe=973ebfcf3e) | Oct 27, 2022 |
| Acer          | Aspire A315-54              | Notebook    | [6de38f7802](https://linux-hardware.org/?probe=6de38f7802) | Oct 27, 2022 |
| ASRock        | H61M-VG4                    | Desktop     | [25b8826346](https://linux-hardware.org/?probe=25b8826346) | Oct 27, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [189ac65e5b](https://linux-hardware.org/?probe=189ac65e5b) | Oct 27, 2022 |
| Samsung       | 760XBE                      | Notebook    | [6787286004](https://linux-hardware.org/?probe=6787286004) | Oct 27, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [3a09f9ee6b](https://linux-hardware.org/?probe=3a09f9ee6b) | Oct 27, 2022 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [6954f669c5](https://linux-hardware.org/?probe=6954f669c5) | Oct 27, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [98cd87adf9](https://linux-hardware.org/?probe=98cd87adf9) | Oct 27, 2022 |
| Intel         | H55                         | Desktop     | [fb3cf518ac](https://linux-hardware.org/?probe=fb3cf518ac) | Oct 27, 2022 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [9285fb0d9d](https://linux-hardware.org/?probe=9285fb0d9d) | Oct 27, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [2474ff9baf](https://linux-hardware.org/?probe=2474ff9baf) | Oct 27, 2022 |
| Dell          | Inspiron 5402               | Notebook    | [a7a8cc4cff](https://linux-hardware.org/?probe=a7a8cc4cff) | Oct 27, 2022 |
| Avell High... | A60 MUV                     | Notebook    | [ccdf105523](https://linux-hardware.org/?probe=ccdf105523) | Oct 26, 2022 |
| Acer          | Veriton M275                | Desktop     | [c4604d6f2a](https://linux-hardware.org/?probe=c4604d6f2a) | Oct 26, 2022 |
| Sony          | VPCEA23FB                   | Notebook    | [1b9688e23f](https://linux-hardware.org/?probe=1b9688e23f) | Oct 26, 2022 |
| ASUSTek       | P7H57D-V EVO                | Desktop     | [785405287b](https://linux-hardware.org/?probe=785405287b) | Oct 26, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [8cb2cd8c19](https://linux-hardware.org/?probe=8cb2cd8c19) | Oct 26, 2022 |
| Dell          | Inspiron 7580               | Notebook    | [a0adbfd7fe](https://linux-hardware.org/?probe=a0adbfd7fe) | Oct 26, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [892c5e2cda](https://linux-hardware.org/?probe=892c5e2cda) | Oct 26, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [ff62c670fd](https://linux-hardware.org/?probe=ff62c670fd) | Oct 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [b98bd6b361](https://linux-hardware.org/?probe=b98bd6b361) | Oct 26, 2022 |
| Dell          | Inspiron 7580               | Notebook    | [519384ee8a](https://linux-hardware.org/?probe=519384ee8a) | Oct 26, 2022 |
| PCWare        | IPMH61R3                    | Desktop     | [9f9410b99d](https://linux-hardware.org/?probe=9f9410b99d) | Oct 25, 2022 |
| Toshiba       | STI 005492G                 | Desktop     | [e7fccc3a84](https://linux-hardware.org/?probe=e7fccc3a84) | Oct 25, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [562c9438d1](https://linux-hardware.org/?probe=562c9438d1) | Oct 25, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [6d4b1d0bb3](https://linux-hardware.org/?probe=6d4b1d0bb3) | Oct 25, 2022 |
| Avell High... | A62 LIV                     | Notebook    | [673f411692](https://linux-hardware.org/?probe=673f411692) | Oct 25, 2022 |
| Gigabyte      | A520M DS3H                  | Desktop     | [88e45a4e65](https://linux-hardware.org/?probe=88e45a4e65) | Oct 25, 2022 |
| Lenovo        | G40-80 80JE                 | Notebook    | [97dfa18602](https://linux-hardware.org/?probe=97dfa18602) | Oct 25, 2022 |
| Toshiba       | K201                        | Notebook    | [63a892bae3](https://linux-hardware.org/?probe=63a892bae3) | Oct 25, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [c0fb49f07a](https://linux-hardware.org/?probe=c0fb49f07a) | Oct 25, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [6b4c7d3c8b](https://linux-hardware.org/?probe=6b4c7d3c8b) | Oct 24, 2022 |
| ASRock        | H61M-VG4                    | Desktop     | [b393d57b17](https://linux-hardware.org/?probe=b393d57b17) | Oct 24, 2022 |
| ASUSTek       | H170M-PLUS/BR               | Desktop     | [31cae2266e](https://linux-hardware.org/?probe=31cae2266e) | Oct 24, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [9a9880cc6a](https://linux-hardware.org/?probe=9a9880cc6a) | Oct 24, 2022 |
| ASRock        | H61M-VG4                    | Desktop     | [1e80f1de23](https://linux-hardware.org/?probe=1e80f1de23) | Oct 24, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [b7315785a1](https://linux-hardware.org/?probe=b7315785a1) | Oct 24, 2022 |
| ASUSTek       | S500CA                      | Notebook    | [bc57450141](https://linux-hardware.org/?probe=bc57450141) | Oct 24, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [4540d714bc](https://linux-hardware.org/?probe=4540d714bc) | Oct 24, 2022 |
| Biostar       | A320MH                      | Desktop     | [b38eca2979](https://linux-hardware.org/?probe=b38eca2979) | Oct 24, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [86e8f9141a](https://linux-hardware.org/?probe=86e8f9141a) | Oct 24, 2022 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [da9c01eb20](https://linux-hardware.org/?probe=da9c01eb20) | Oct 23, 2022 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [9d2d49b8e4](https://linux-hardware.org/?probe=9d2d49b8e4) | Oct 23, 2022 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [dad9e03a82](https://linux-hardware.org/?probe=dad9e03a82) | Oct 23, 2022 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | Notebook    | [edfb470814](https://linux-hardware.org/?probe=edfb470814) | Oct 23, 2022 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [1f3d807ceb](https://linux-hardware.org/?probe=1f3d807ceb) | Oct 23, 2022 |
| Dell          | 0JP3NX A01                  | Desktop     | [86365f2c05](https://linux-hardware.org/?probe=86365f2c05) | Oct 23, 2022 |
| HP            | 1489                        | All in one  | [3b3379c0e2](https://linux-hardware.org/?probe=3b3379c0e2) | Oct 23, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [5388646329](https://linux-hardware.org/?probe=5388646329) | Oct 23, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [cfb362baf3](https://linux-hardware.org/?probe=cfb362baf3) | Oct 23, 2022 |
| Dell          | Inspiron 3576               | Notebook    | [426ddc8fdb](https://linux-hardware.org/?probe=426ddc8fdb) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [e14654d246](https://linux-hardware.org/?probe=e14654d246) | Oct 22, 2022 |
| Dell          | Vostro 3560                 | Notebook    | [b438a2ba8f](https://linux-hardware.org/?probe=b438a2ba8f) | Oct 22, 2022 |
| Gigabyte      | A520M DS3H                  | Desktop     | [3faf4b3ca9](https://linux-hardware.org/?probe=3faf4b3ca9) | Oct 22, 2022 |
| Philco        | DTC-A55                     | Desktop     | [5c7d64ff3f](https://linux-hardware.org/?probe=5c7d64ff3f) | Oct 22, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [d8f21a8ec6](https://linux-hardware.org/?probe=d8f21a8ec6) | Oct 22, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [514642847b](https://linux-hardware.org/?probe=514642847b) | Oct 22, 2022 |
| Avell High... | C62 MOB                     | Notebook    | [3baeb7ee26](https://linux-hardware.org/?probe=3baeb7ee26) | Oct 22, 2022 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [f43a04f63f](https://linux-hardware.org/?probe=f43a04f63f) | Oct 21, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [72f0c231fb](https://linux-hardware.org/?probe=72f0c231fb) | Oct 21, 2022 |
| Positivo      | S14CT01                     | Notebook    | [1a5f77c8f9](https://linux-hardware.org/?probe=1a5f77c8f9) | Oct 21, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [2a9b4f61c6](https://linux-hardware.org/?probe=2a9b4f61c6) | Oct 21, 2022 |
| Microboard    | Cantiga & ICH9M Chipset     | Notebook    | [1fffce3846](https://linux-hardware.org/?probe=1fffce3846) | Oct 21, 2022 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [7bc7482286](https://linux-hardware.org/?probe=7bc7482286) | Oct 21, 2022 |
| Avell High... | B.ON                        | Notebook    | [17ce0979b3](https://linux-hardware.org/?probe=17ce0979b3) | Oct 21, 2022 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [462091e8a8](https://linux-hardware.org/?probe=462091e8a8) | Oct 21, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [ed692d6080](https://linux-hardware.org/?probe=ed692d6080) | Oct 21, 2022 |
| Itautec       | Infoway N8755               | Notebook    | [7eaba382a5](https://linux-hardware.org/?probe=7eaba382a5) | Oct 21, 2022 |
| MSI           | Z97 GAMING 3                | Desktop     | [2b5803628a](https://linux-hardware.org/?probe=2b5803628a) | Oct 20, 2022 |
| MSI           | Z97 GAMING 3                | Desktop     | [94c634f9b8](https://linux-hardware.org/?probe=94c634f9b8) | Oct 20, 2022 |
| Gigabyte      | H87M-D3H                    | Desktop     | [bda1da1137](https://linux-hardware.org/?probe=bda1da1137) | Oct 20, 2022 |
| Dell          | Latitude E5410              | Notebook    | [f3b5d196ef](https://linux-hardware.org/?probe=f3b5d196ef) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [02b0d2ded2](https://linux-hardware.org/?probe=02b0d2ded2) | Oct 20, 2022 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [354afbd4d8](https://linux-hardware.org/?probe=354afbd4d8) | Oct 20, 2022 |
| Positivo      | C4120F                      | Notebook    | [92338290da](https://linux-hardware.org/?probe=92338290da) | Oct 20, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [7799fd6266](https://linux-hardware.org/?probe=7799fd6266) | Oct 20, 2022 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [2991e146ce](https://linux-hardware.org/?probe=2991e146ce) | Oct 19, 2022 |
| Acer          | Aspire E5-574               | Notebook    | [d9797d9fa7](https://linux-hardware.org/?probe=d9797d9fa7) | Oct 19, 2022 |
| Dell          | 0YXT71 A02                  | Desktop     | [137e154b2d](https://linux-hardware.org/?probe=137e154b2d) | Oct 19, 2022 |
| Lenovo        | 3102 NOK                    | Desktop     | [d46ae4e597](https://linux-hardware.org/?probe=d46ae4e597) | Oct 19, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [c395183020](https://linux-hardware.org/?probe=c395183020) | Oct 19, 2022 |
| Lenovo        | 3102 NOK                    | Desktop     | [e57ed46372](https://linux-hardware.org/?probe=e57ed46372) | Oct 19, 2022 |
| Dell          | 0XJ8C4 A00                  | Desktop     | [83da6e6509](https://linux-hardware.org/?probe=83da6e6509) | Oct 19, 2022 |
| Samsung       | 550XDA                      | Notebook    | [fcfceeaf04](https://linux-hardware.org/?probe=fcfceeaf04) | Oct 19, 2022 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [de13cd2a09](https://linux-hardware.org/?probe=de13cd2a09) | Oct 19, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [5e02a12da7](https://linux-hardware.org/?probe=5e02a12da7) | Oct 19, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [93584b3b67](https://linux-hardware.org/?probe=93584b3b67) | Oct 19, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [a8170f7786](https://linux-hardware.org/?probe=a8170f7786) | Oct 19, 2022 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [f2750b0a70](https://linux-hardware.org/?probe=f2750b0a70) | Oct 18, 2022 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [46a99f3d0e](https://linux-hardware.org/?probe=46a99f3d0e) | Oct 18, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [d9b4d01e7f](https://linux-hardware.org/?probe=d9b4d01e7f) | Oct 18, 2022 |
| ASRock        | X670E Steel Legend          | Desktop     | [2b0983acd6](https://linux-hardware.org/?probe=2b0983acd6) | Oct 18, 2022 |
| ASUSTek       | Z450LA                      | Notebook    | [ba00eb6516](https://linux-hardware.org/?probe=ba00eb6516) | Oct 18, 2022 |
| Lenovo        | G480                        | Notebook    | [984691a38d](https://linux-hardware.org/?probe=984691a38d) | Oct 18, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [d458ae27cf](https://linux-hardware.org/?probe=d458ae27cf) | Oct 18, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [6718ea22a9](https://linux-hardware.org/?probe=6718ea22a9) | Oct 18, 2022 |
| Avell High... | B.ON                        | Notebook    | [fc8b4d7534](https://linux-hardware.org/?probe=fc8b4d7534) | Oct 18, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [0e827df91b](https://linux-hardware.org/?probe=0e827df91b) | Oct 18, 2022 |
| Teclast       | F7 Plus                     | Notebook    | [e77cad05c2](https://linux-hardware.org/?probe=e77cad05c2) | Oct 17, 2022 |
| ASUSTek       | Z450LA                      | Notebook    | [6042d84470](https://linux-hardware.org/?probe=6042d84470) | Oct 17, 2022 |
| Itautec       | ST 4273 ST-4273 Padrao 0... | Desktop     | [8c4af1707c](https://linux-hardware.org/?probe=8c4af1707c) | Oct 17, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [bab2e8dad2](https://linux-hardware.org/?probe=bab2e8dad2) | Oct 17, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [732f4ea8fe](https://linux-hardware.org/?probe=732f4ea8fe) | Oct 17, 2022 |
| Unknown       | Beelink GT-King Pro         | Soc         | [9d29015602](https://linux-hardware.org/?probe=9d29015602) | Oct 17, 2022 |
| Dell          | Inspiron 5447               | Notebook    | [735ac089ab](https://linux-hardware.org/?probe=735ac089ab) | Oct 17, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [d86b86e8a8](https://linux-hardware.org/?probe=d86b86e8a8) | Oct 17, 2022 |
| Unknown       | Beelink GT-King Pro         | Soc         | [2e5287f2cb](https://linux-hardware.org/?probe=2e5287f2cb) | Oct 17, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [464ce69071](https://linux-hardware.org/?probe=464ce69071) | Oct 17, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [55f7f983c4](https://linux-hardware.org/?probe=55f7f983c4) | Oct 17, 2022 |
| Multilaser    | PC024                       | Notebook    | [892f53a067](https://linux-hardware.org/?probe=892f53a067) | Oct 17, 2022 |
| Acer          | Aspire 5750                 | Notebook    | [4e90ad293c](https://linux-hardware.org/?probe=4e90ad293c) | Oct 17, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | Notebook    | [81cec7c137](https://linux-hardware.org/?probe=81cec7c137) | Oct 16, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | Notebook    | [2d843ba905](https://linux-hardware.org/?probe=2d843ba905) | Oct 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | Notebook    | [f20a72be72](https://linux-hardware.org/?probe=f20a72be72) | Oct 16, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [def577cdb8](https://linux-hardware.org/?probe=def577cdb8) | Oct 16, 2022 |
| PCWare        | IPMH110G                    | Desktop     | [cde154a026](https://linux-hardware.org/?probe=cde154a026) | Oct 16, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [7293f219d8](https://linux-hardware.org/?probe=7293f219d8) | Oct 16, 2022 |
| Digibras      | NH4CU03                     | Notebook    | [45912a4bae](https://linux-hardware.org/?probe=45912a4bae) | Oct 16, 2022 |
| Intel         | H55                         | Desktop     | [ab27a6c8d9](https://linux-hardware.org/?probe=ab27a6c8d9) | Oct 15, 2022 |
| Alienware     | m15 R6                      | Notebook    | [3cb0cb3e9d](https://linux-hardware.org/?probe=3cb0cb3e9d) | Oct 15, 2022 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [3c5f4ad9a5](https://linux-hardware.org/?probe=3c5f4ad9a5) | Oct 15, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [8e16d67f02](https://linux-hardware.org/?probe=8e16d67f02) | Oct 15, 2022 |
| LG Electro... | S460-G.BG31P1               | Notebook    | [a0b3b8e905](https://linux-hardware.org/?probe=a0b3b8e905) | Oct 15, 2022 |
| Compaq        | 420                         | Notebook    | [cc3fae2a79](https://linux-hardware.org/?probe=cc3fae2a79) | Oct 15, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [5261790ba7](https://linux-hardware.org/?probe=5261790ba7) | Oct 15, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [19d249aa9c](https://linux-hardware.org/?probe=19d249aa9c) | Oct 14, 2022 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [6381ab6a1b](https://linux-hardware.org/?probe=6381ab6a1b) | Oct 14, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [b5cfcb5d6c](https://linux-hardware.org/?probe=b5cfcb5d6c) | Oct 14, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [a65b043bb7](https://linux-hardware.org/?probe=a65b043bb7) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [784360100d](https://linux-hardware.org/?probe=784360100d) | Oct 14, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [8cf96a6d0b](https://linux-hardware.org/?probe=8cf96a6d0b) | Oct 14, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [a68e7df338](https://linux-hardware.org/?probe=a68e7df338) | Oct 14, 2022 |
| Lenovo        | B40-70 80F3                 | Notebook    | [491ba5984a](https://linux-hardware.org/?probe=491ba5984a) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [15ba599a80](https://linux-hardware.org/?probe=15ba599a80) | Oct 14, 2022 |
| Lenovo        | B40-70 80F3                 | Notebook    | [d22d4118a7](https://linux-hardware.org/?probe=d22d4118a7) | Oct 14, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [b966faf224](https://linux-hardware.org/?probe=b966faf224) | Oct 14, 2022 |
| Compaq        | PRESARIOCQ18                | Notebook    | [5172032993](https://linux-hardware.org/?probe=5172032993) | Oct 14, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [f13203e3ce](https://linux-hardware.org/?probe=f13203e3ce) | Oct 14, 2022 |
| Acer          | Aspire A315-34              | Notebook    | [a95d9e55ba](https://linux-hardware.org/?probe=a95d9e55ba) | Oct 14, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [0a89e9b77e](https://linux-hardware.org/?probe=0a89e9b77e) | Oct 13, 2022 |
| Samsung       | 300E5M/300E5L               | Notebook    | [f8eae084ac](https://linux-hardware.org/?probe=f8eae084ac) | Oct 13, 2022 |
| Lenovo        | G50-80 80R0                 | Notebook    | [990bec11d7](https://linux-hardware.org/?probe=990bec11d7) | Oct 13, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [754608b701](https://linux-hardware.org/?probe=754608b701) | Oct 13, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [8e2b577a03](https://linux-hardware.org/?probe=8e2b577a03) | Oct 13, 2022 |
| Toshiba       | STI 005492G                 | Desktop     | [e803b9bcf3](https://linux-hardware.org/?probe=e803b9bcf3) | Oct 13, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [bb386c7d60](https://linux-hardware.org/?probe=bb386c7d60) | Oct 13, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [3c99de982b](https://linux-hardware.org/?probe=3c99de982b) | Oct 13, 2022 |
| Samsung       | 930QDB                      | Convertible | [8cc56657cc](https://linux-hardware.org/?probe=8cc56657cc) | Oct 13, 2022 |
| Itautec       | ST 4254 ST-4254 Padrao 0... | Desktop     | [48ee58de23](https://linux-hardware.org/?probe=48ee58de23) | Oct 13, 2022 |
| Pegatron      | 2AD2A                       | Desktop     | [01827879c5](https://linux-hardware.org/?probe=01827879c5) | Oct 13, 2022 |
| Positivo      | DH8BW01                     | All in one  | [95e8bed16f](https://linux-hardware.org/?probe=95e8bed16f) | Oct 12, 2022 |
| HP            | G42                         | Notebook    | [fd42e3aedb](https://linux-hardware.org/?probe=fd42e3aedb) | Oct 12, 2022 |
| Daten Tecn... | DT02-M4                     | Notebook    | [d800a06da5](https://linux-hardware.org/?probe=d800a06da5) | Oct 12, 2022 |
| Daten Tecn... | DT02-M4                     | Notebook    | [9d4c4f0c96](https://linux-hardware.org/?probe=9d4c4f0c96) | Oct 12, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [212c135857](https://linux-hardware.org/?probe=212c135857) | Oct 12, 2022 |
| ASRock        | N68-VS3 FX                  | Desktop     | [b271788734](https://linux-hardware.org/?probe=b271788734) | Oct 12, 2022 |
| Lenovo        | ThinkPad T480 20L6S1U700    | Notebook    | [df4489e9fb](https://linux-hardware.org/?probe=df4489e9fb) | Oct 12, 2022 |
| Gigabyte      | 945GCM-S2C                  | Desktop     | [d0fe56248f](https://linux-hardware.org/?probe=d0fe56248f) | Oct 12, 2022 |
| Acer          | Aspire ES1-572              | Notebook    | [7741ed43d0](https://linux-hardware.org/?probe=7741ed43d0) | Oct 12, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [585b7e9773](https://linux-hardware.org/?probe=585b7e9773) | Oct 12, 2022 |
| Acer          | Aspire A514-54              | Notebook    | [b566c0179a](https://linux-hardware.org/?probe=b566c0179a) | Oct 12, 2022 |
| Pegatron      | IPM31G                      | Desktop     | [75d4fc0b55](https://linux-hardware.org/?probe=75d4fc0b55) | Oct 12, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [930887578f](https://linux-hardware.org/?probe=930887578f) | Oct 11, 2022 |
| PCWare        | IPMH110G                    | Desktop     | [2bcf719742](https://linux-hardware.org/?probe=2bcf719742) | Oct 11, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [f512c7bf3f](https://linux-hardware.org/?probe=f512c7bf3f) | Oct 11, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [11f3146366](https://linux-hardware.org/?probe=11f3146366) | Oct 11, 2022 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [52997332e0](https://linux-hardware.org/?probe=52997332e0) | Oct 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [3414f3f4c0](https://linux-hardware.org/?probe=3414f3f4c0) | Oct 10, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [8e1e663189](https://linux-hardware.org/?probe=8e1e663189) | Oct 10, 2022 |
| Acer          | Aspire E1-572               | Notebook    | [4097531dec](https://linux-hardware.org/?probe=4097531dec) | Oct 10, 2022 |
| Gigabyte      | 945GM-S2                    | Desktop     | [3087d063e3](https://linux-hardware.org/?probe=3087d063e3) | Oct 10, 2022 |
| Dell          | Latitude 5410               | Notebook    | [c69cc79a8e](https://linux-hardware.org/?probe=c69cc79a8e) | Oct 10, 2022 |
| Intel         | DH67CL AAG10212-206         | Desktop     | [01ebc77ef1](https://linux-hardware.org/?probe=01ebc77ef1) | Oct 10, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [05e8d3583c](https://linux-hardware.org/?probe=05e8d3583c) | Oct 10, 2022 |
| Intel         | DG41TY AAE47335-302         | Desktop     | [c0d07ec775](https://linux-hardware.org/?probe=c0d07ec775) | Oct 10, 2022 |
| Samsung       | 550XBE/350XBE               | Notebook    | [bfce31736f](https://linux-hardware.org/?probe=bfce31736f) | Oct 10, 2022 |
| Acer          | Aspire 5750                 | Notebook    | [f335fc684d](https://linux-hardware.org/?probe=f335fc684d) | Oct 09, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [edb6e4180f](https://linux-hardware.org/?probe=edb6e4180f) | Oct 09, 2022 |
| Dell          | Latitude 5501               | Notebook    | [9051fd0e00](https://linux-hardware.org/?probe=9051fd0e00) | Oct 09, 2022 |
| Dell          | Latitude 5501               | Notebook    | [3396ccdbab](https://linux-hardware.org/?probe=3396ccdbab) | Oct 09, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [65039e3fdd](https://linux-hardware.org/?probe=65039e3fdd) | Oct 09, 2022 |
| PINE64        | Pinebook Pro                | Soc         | [8d79fe1eba](https://linux-hardware.org/?probe=8d79fe1eba) | Oct 09, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [be45a704e2](https://linux-hardware.org/?probe=be45a704e2) | Oct 09, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [8918b1b82e](https://linux-hardware.org/?probe=8918b1b82e) | Oct 09, 2022 |
| Acer          | Predator PH315-53           | Notebook    | [cc8b98a2ff](https://linux-hardware.org/?probe=cc8b98a2ff) | Oct 09, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [ce045937bc](https://linux-hardware.org/?probe=ce045937bc) | Oct 09, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [75502d8d96](https://linux-hardware.org/?probe=75502d8d96) | Oct 09, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [691aa10e89](https://linux-hardware.org/?probe=691aa10e89) | Oct 09, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [939e426600](https://linux-hardware.org/?probe=939e426600) | Oct 08, 2022 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [acd8e18972](https://linux-hardware.org/?probe=acd8e18972) | Oct 08, 2022 |
| Dell          | Vostro 3501                 | Notebook    | [126b7b85f2](https://linux-hardware.org/?probe=126b7b85f2) | Oct 08, 2022 |
| Dell          | Inspiron 5458               | Notebook    | [d6742b3ec0](https://linux-hardware.org/?probe=d6742b3ec0) | Oct 08, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [cdd4dd4637](https://linux-hardware.org/?probe=cdd4dd4637) | Oct 08, 2022 |
| Positivo      | Q232A                       | Notebook    | [658da8785e](https://linux-hardware.org/?probe=658da8785e) | Oct 08, 2022 |
| Standard      | MB40II                      | Notebook    | [97b446abda](https://linux-hardware.org/?probe=97b446abda) | Oct 08, 2022 |
| Unknown       | Unknown                     | Notebook    | [b941499384](https://linux-hardware.org/?probe=b941499384) | Oct 08, 2022 |
| Quanta        | TWS                         | Notebook    | [f7ba149979](https://linux-hardware.org/?probe=f7ba149979) | Oct 08, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [0085d792fd](https://linux-hardware.org/?probe=0085d792fd) | Oct 07, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [dd91590e9f](https://linux-hardware.org/?probe=dd91590e9f) | Oct 07, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [fe1e7b060c](https://linux-hardware.org/?probe=fe1e7b060c) | Oct 07, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [9ccbc0ed3c](https://linux-hardware.org/?probe=9ccbc0ed3c) | Oct 07, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [f8d7d79e14](https://linux-hardware.org/?probe=f8d7d79e14) | Oct 07, 2022 |
| Positivo B... | VJC141F11X-B0111L           | Notebook    | [6f08bf3d68](https://linux-hardware.org/?probe=6f08bf3d68) | Oct 07, 2022 |
| Positivo      | Mobile                      | Notebook    | [f26e597436](https://linux-hardware.org/?probe=f26e597436) | Oct 06, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [986a405690](https://linux-hardware.org/?probe=986a405690) | Oct 06, 2022 |
| Positivo      | W940SU2                     | Notebook    | [d403edabc4](https://linux-hardware.org/?probe=d403edabc4) | Oct 06, 2022 |
| MSI           | X370 SLI PLUS               | Desktop     | [ea7dc6a41a](https://linux-hardware.org/?probe=ea7dc6a41a) | Oct 06, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [ff783e01db](https://linux-hardware.org/?probe=ff783e01db) | Oct 06, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [6ad101df29](https://linux-hardware.org/?probe=6ad101df29) | Oct 06, 2022 |
| Acer          | Aspire E5-475G              | Notebook    | [a545cecc64](https://linux-hardware.org/?probe=a545cecc64) | Oct 05, 2022 |
| Acer          | Aspire E5-475G              | Notebook    | [06fa787cb1](https://linux-hardware.org/?probe=06fa787cb1) | Oct 05, 2022 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [368530a660](https://linux-hardware.org/?probe=368530a660) | Oct 05, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [75f96017fd](https://linux-hardware.org/?probe=75f96017fd) | Oct 05, 2022 |
| Positivo      | N1250                       | Notebook    | [9845103c14](https://linux-hardware.org/?probe=9845103c14) | Oct 05, 2022 |
| Positivo      | C14CR01                     | Notebook    | [7c0d0b2efd](https://linux-hardware.org/?probe=7c0d0b2efd) | Oct 05, 2022 |
| Intel         | B75                         | Desktop     | [a15b4ede9b](https://linux-hardware.org/?probe=a15b4ede9b) | Oct 05, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [d0d3494971](https://linux-hardware.org/?probe=d0d3494971) | Oct 05, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [74130061ff](https://linux-hardware.org/?probe=74130061ff) | Oct 05, 2022 |
| Avell High... | B.ON                        | Notebook    | [2b629889c7](https://linux-hardware.org/?probe=2b629889c7) | Oct 05, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [0ed1bfe4ef](https://linux-hardware.org/?probe=0ed1bfe4ef) | Oct 05, 2022 |
| HP            | 2AA2                        | Desktop     | [e6bc6050b6](https://linux-hardware.org/?probe=e6bc6050b6) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [dea0d04059](https://linux-hardware.org/?probe=dea0d04059) | Oct 05, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [ab3508b938](https://linux-hardware.org/?probe=ab3508b938) | Oct 05, 2022 |
| Gigabyte      | H110M-S2PH-CF               | Desktop     | [580c13ac38](https://linux-hardware.org/?probe=580c13ac38) | Oct 05, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [612b4b36a1](https://linux-hardware.org/?probe=612b4b36a1) | Oct 04, 2022 |
| Unknown       | Unknown                     | Notebook    | [23c45d949c](https://linux-hardware.org/?probe=23c45d949c) | Oct 04, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [10fec0d039](https://linux-hardware.org/?probe=10fec0d039) | Oct 04, 2022 |
| Intel         | X99 V1.0                    | Desktop     | [d96984ac77](https://linux-hardware.org/?probe=d96984ac77) | Oct 04, 2022 |
| Intel         | W7645                       | Notebook    | [4f76b8b5ad](https://linux-hardware.org/?probe=4f76b8b5ad) | Oct 04, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [16f99421ab](https://linux-hardware.org/?probe=16f99421ab) | Oct 04, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [f30bf7e978](https://linux-hardware.org/?probe=f30bf7e978) | Oct 04, 2022 |
| Dell          | Inspiron 5590               | Notebook    | [ed3bf1e99b](https://linux-hardware.org/?probe=ed3bf1e99b) | Oct 04, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [9954860560](https://linux-hardware.org/?probe=9954860560) | Oct 04, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | Notebook    | [a9281e38d4](https://linux-hardware.org/?probe=a9281e38d4) | Oct 04, 2022 |
| Dell          | G3 3500                     | Notebook    | [9a574c1075](https://linux-hardware.org/?probe=9a574c1075) | Oct 04, 2022 |
| Intel         | H55                         | Desktop     | [73719c58ab](https://linux-hardware.org/?probe=73719c58ab) | Oct 03, 2022 |
| Dell          | Latitude E6420              | Notebook    | [652b18aabe](https://linux-hardware.org/?probe=652b18aabe) | Oct 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [c277d88bb6](https://linux-hardware.org/?probe=c277d88bb6) | Oct 03, 2022 |
| Sony          | VPCCA15FX                   | Notebook    | [c6c2a651b9](https://linux-hardware.org/?probe=c6c2a651b9) | Oct 03, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [8125b49bea](https://linux-hardware.org/?probe=8125b49bea) | Oct 03, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [019702e62b](https://linux-hardware.org/?probe=019702e62b) | Oct 03, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [a9f0d894af](https://linux-hardware.org/?probe=a9f0d894af) | Oct 03, 2022 |
| Dell          | Inspiron 5590               | Notebook    | [bdb7d444f0](https://linux-hardware.org/?probe=bdb7d444f0) | Oct 03, 2022 |
| Samsung       | 550XDA                      | Notebook    | [418d32112e](https://linux-hardware.org/?probe=418d32112e) | Oct 03, 2022 |
| Lenovo        | ThinkCentre M58p 6209CM1    | Desktop     | [15fb3b5261](https://linux-hardware.org/?probe=15fb3b5261) | Oct 02, 2022 |
| Dell          | XPS 13 9300                 | Notebook    | [00ecde42a1](https://linux-hardware.org/?probe=00ecde42a1) | Oct 02, 2022 |
| Unknown       | Unknown                     | Notebook    | [fc558ece05](https://linux-hardware.org/?probe=fc558ece05) | Oct 02, 2022 |
| ASUSTek       | A78M-A                      | Desktop     | [91434dfd86](https://linux-hardware.org/?probe=91434dfd86) | Oct 02, 2022 |
| Dell          | XPS L421X                   | Notebook    | [dc90cf9dbf](https://linux-hardware.org/?probe=dc90cf9dbf) | Oct 02, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [9b2e1432f2](https://linux-hardware.org/?probe=9b2e1432f2) | Oct 02, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [6d8ed9f182](https://linux-hardware.org/?probe=6d8ed9f182) | Oct 02, 2022 |
| ASUSTek       | C8HM70-I/HDMI               | Desktop     | [7309d377f6](https://linux-hardware.org/?probe=7309d377f6) | Oct 02, 2022 |
| Samsung       | 275E4E/275E5E               | Notebook    | [ba82d9366c](https://linux-hardware.org/?probe=ba82d9366c) | Oct 02, 2022 |
| ASUSTek       | C8HM70-I/HDMI               | Desktop     | [aedfaab130](https://linux-hardware.org/?probe=aedfaab130) | Oct 02, 2022 |
| Avell High... | B.ON                        | Notebook    | [240b350525](https://linux-hardware.org/?probe=240b350525) | Oct 02, 2022 |
| Positivo      | Mobile                      | Notebook    | [640bc1a962](https://linux-hardware.org/?probe=640bc1a962) | Oct 01, 2022 |
| Positivo      | POS-PIH81DL                 | Desktop     | [c17fe23ea7](https://linux-hardware.org/?probe=c17fe23ea7) | Oct 01, 2022 |
| ASUSTek       | A78M-A                      | Desktop     | [5ad2e5f2a6](https://linux-hardware.org/?probe=5ad2e5f2a6) | Oct 01, 2022 |
| Itautec       | Infoway a7420               | Notebook    | [bb52fe66cf](https://linux-hardware.org/?probe=bb52fe66cf) | Oct 01, 2022 |
| Sony          | VPCCA15FX                   | Notebook    | [96eb3d8cf7](https://linux-hardware.org/?probe=96eb3d8cf7) | Oct 01, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [e666344187](https://linux-hardware.org/?probe=e666344187) | Oct 01, 2022 |
| Dell          | Inspiron 5420               | Notebook    | [71f7e67ca7](https://linux-hardware.org/?probe=71f7e67ca7) | Oct 01, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [27bb1c39eb](https://linux-hardware.org/?probe=27bb1c39eb) | Oct 01, 2022 |
| Biostar       | B350ET2                     | Desktop     | [d7c5b1ad40](https://linux-hardware.org/?probe=d7c5b1ad40) | Oct 01, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [b62ddbdab0](https://linux-hardware.org/?probe=b62ddbdab0) | Oct 01, 2022 |
| Biostar       | A320MH                      | Desktop     | [b07b6c4fc5](https://linux-hardware.org/?probe=b07b6c4fc5) | Oct 01, 2022 |
| Lenovo        | G480 20149                  | Notebook    | [9a047ee214](https://linux-hardware.org/?probe=9a047ee214) | Oct 01, 2022 |
| Lenovo        | G480 20149                  | Notebook    | [4c0a153a12](https://linux-hardware.org/?probe=4c0a153a12) | Oct 01, 2022 |
| Gigabyte      | H110M-H DDR3-CF             | Desktop     | [8169fe8dbd](https://linux-hardware.org/?probe=8169fe8dbd) | Oct 01, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [29c4292c62](https://linux-hardware.org/?probe=29c4292c62) | Oct 01, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [3edc4043a3](https://linux-hardware.org/?probe=3edc4043a3) | Oct 01, 2022 |
| Biostar       | B350ET2                     | Desktop     | [2b7bea0eda](https://linux-hardware.org/?probe=2b7bea0eda) | Sep 30, 2022 |
| Intel         | H61                         | Desktop     | [37af3b0cdb](https://linux-hardware.org/?probe=37af3b0cdb) | Sep 30, 2022 |
| Dell          | 07PR60 A01                  | Desktop     | [812cb18129](https://linux-hardware.org/?probe=812cb18129) | Sep 30, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [1f142c7087](https://linux-hardware.org/?probe=1f142c7087) | Sep 30, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [263313ef38](https://linux-hardware.org/?probe=263313ef38) | Sep 30, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [2c08befa41](https://linux-hardware.org/?probe=2c08befa41) | Sep 30, 2022 |
| Positivo      | Mobile                      | Notebook    | [dcf8b09bec](https://linux-hardware.org/?probe=dcf8b09bec) | Sep 30, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [3c0e0b12ee](https://linux-hardware.org/?probe=3c0e0b12ee) | Sep 30, 2022 |
| Positivo      | Mobile                      | Notebook    | [6d2584bcb8](https://linux-hardware.org/?probe=6d2584bcb8) | Sep 30, 2022 |
| Positivo      | POS-PIQ67CG POSITIVO        | Desktop     | [5cdce489b9](https://linux-hardware.org/?probe=5cdce489b9) | Sep 30, 2022 |
| Positivo      | POS-PIQ67CG POSITIVO        | Desktop     | [3bfbb3744e](https://linux-hardware.org/?probe=3bfbb3744e) | Sep 30, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [149337514c](https://linux-hardware.org/?probe=149337514c) | Sep 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [fa00f3d0ca](https://linux-hardware.org/?probe=fa00f3d0ca) | Sep 30, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [57995ec944](https://linux-hardware.org/?probe=57995ec944) | Sep 30, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | Notebook    | [fdcdf06f55](https://linux-hardware.org/?probe=fdcdf06f55) | Sep 29, 2022 |
| Avell High... | A60 MUV                     | Notebook    | [888e375356](https://linux-hardware.org/?probe=888e375356) | Sep 29, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [64a7e86e22](https://linux-hardware.org/?probe=64a7e86e22) | Sep 29, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [067b155d9b](https://linux-hardware.org/?probe=067b155d9b) | Sep 29, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [058aa145d3](https://linux-hardware.org/?probe=058aa145d3) | Sep 29, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [a674def12d](https://linux-hardware.org/?probe=a674def12d) | Sep 29, 2022 |
| Apple         | Mac-F4208EC8 PVT            | Mini pc     | [62d808a3e5](https://linux-hardware.org/?probe=62d808a3e5) | Sep 28, 2022 |
| Dell          | Inspiron 5447               | Notebook    | [b30346135b](https://linux-hardware.org/?probe=b30346135b) | Sep 28, 2022 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [513d236a1f](https://linux-hardware.org/?probe=513d236a1f) | Sep 28, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [8272a6655b](https://linux-hardware.org/?probe=8272a6655b) | Sep 28, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [be9d7b3e42](https://linux-hardware.org/?probe=be9d7b3e42) | Sep 28, 2022 |
| ASUSTek       | P5K Premium                 | Desktop     | [ec3962c685](https://linux-hardware.org/?probe=ec3962c685) | Sep 28, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [7e4413a053](https://linux-hardware.org/?probe=7e4413a053) | Sep 28, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [bbd715eb5a](https://linux-hardware.org/?probe=bbd715eb5a) | Sep 28, 2022 |
| ASUSTek       | P5GC-MX/CKD/SI              | Desktop     | [72bb90ea71](https://linux-hardware.org/?probe=72bb90ea71) | Sep 28, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [973307d03b](https://linux-hardware.org/?probe=973307d03b) | Sep 28, 2022 |
| Acer          | Aspire E5-573               | Notebook    | [f7e628a5a1](https://linux-hardware.org/?probe=f7e628a5a1) | Sep 28, 2022 |
| Positivo      | S14CT01                     | Notebook    | [66e0c53646](https://linux-hardware.org/?probe=66e0c53646) | Sep 28, 2022 |
| Unknown       | Unknown                     | Notebook    | [3e450900da](https://linux-hardware.org/?probe=3e450900da) | Sep 28, 2022 |
| LG Electro... | C400-G.BC22P1               | Notebook    | [a325f5eb86](https://linux-hardware.org/?probe=a325f5eb86) | Sep 28, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [3eaaf54d1b](https://linux-hardware.org/?probe=3eaaf54d1b) | Sep 28, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [a4b44081c2](https://linux-hardware.org/?probe=a4b44081c2) | Sep 27, 2022 |
| ASUSTek       | B85M-E/BR                   | Desktop     | [5116d1cae9](https://linux-hardware.org/?probe=5116d1cae9) | Sep 27, 2022 |
| Lenovo        | G40-80 80JE                 | Notebook    | [a6347449b3](https://linux-hardware.org/?probe=a6347449b3) | Sep 27, 2022 |
| Dell          | 0YGYJY A01                  | Desktop     | [73e69debd9](https://linux-hardware.org/?probe=73e69debd9) | Sep 27, 2022 |
| Philco        | PNB14.1AC14S128W10          | Notebook    | [ee4bc98535](https://linux-hardware.org/?probe=ee4bc98535) | Sep 27, 2022 |
| Lenovo        | ThinkPad T410 2537AT9       | Notebook    | [553490bb4c](https://linux-hardware.org/?probe=553490bb4c) | Sep 27, 2022 |
| Standard      | AHV                         | Notebook    | [a80b2d344d](https://linux-hardware.org/?probe=a80b2d344d) | Sep 27, 2022 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | Desktop     | [88f0d42935](https://linux-hardware.org/?probe=88f0d42935) | Sep 27, 2022 |
| Intel         | H55                         | Desktop     | [a155052bce](https://linux-hardware.org/?probe=a155052bce) | Sep 26, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [8579eba471](https://linux-hardware.org/?probe=8579eba471) | Sep 26, 2022 |
| Dell          | Latitude 5420               | Notebook    | [bd81c07917](https://linux-hardware.org/?probe=bd81c07917) | Sep 26, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [d9187e470e](https://linux-hardware.org/?probe=d9187e470e) | Sep 26, 2022 |
| Lenovo        | ThinkPad T480 20L6SCWK00    | Notebook    | [60933ed48b](https://linux-hardware.org/?probe=60933ed48b) | Sep 26, 2022 |
| Acer          | Aspire A514-54              | Notebook    | [bab009e0b7](https://linux-hardware.org/?probe=bab009e0b7) | Sep 26, 2022 |
| Positivo      | S14CT01                     | Notebook    | [2191cd2dd1](https://linux-hardware.org/?probe=2191cd2dd1) | Sep 26, 2022 |
| HP            | G42                         | Notebook    | [39a4836398](https://linux-hardware.org/?probe=39a4836398) | Sep 26, 2022 |
| Samsung       | 670Z5E                      | Notebook    | [6bce247e38](https://linux-hardware.org/?probe=6bce247e38) | Sep 26, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [4e228116be](https://linux-hardware.org/?probe=4e228116be) | Sep 25, 2022 |
| Positivo      | S14SL01                     | Notebook    | [a6b3c260f4](https://linux-hardware.org/?probe=a6b3c260f4) | Sep 25, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [8d3b235d4c](https://linux-hardware.org/?probe=8d3b235d4c) | Sep 25, 2022 |
| CCE           | Capella & IbexPeak-M Chi... | Notebook    | [07554a7a2b](https://linux-hardware.org/?probe=07554a7a2b) | Sep 25, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | Notebook    | [d8b270de2b](https://linux-hardware.org/?probe=d8b270de2b) | Sep 25, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [b26f7bf9f5](https://linux-hardware.org/?probe=b26f7bf9f5) | Sep 25, 2022 |
| Positivo      | S14SL01                     | Notebook    | [e09fcd6e38](https://linux-hardware.org/?probe=e09fcd6e38) | Sep 25, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [2e96ddfdd1](https://linux-hardware.org/?probe=2e96ddfdd1) | Sep 25, 2022 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [2d44b203f9](https://linux-hardware.org/?probe=2d44b203f9) | Sep 25, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [107011cb20](https://linux-hardware.org/?probe=107011cb20) | Sep 25, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [939bba43d1](https://linux-hardware.org/?probe=939bba43d1) | Sep 25, 2022 |
| Avell High... | A70 MOB                     | Notebook    | [b867406b76](https://linux-hardware.org/?probe=b867406b76) | Sep 25, 2022 |
| Acer          | AO532h                      | Notebook    | [383ce70d97](https://linux-hardware.org/?probe=383ce70d97) | Sep 25, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [7fb024bb5d](https://linux-hardware.org/?probe=7fb024bb5d) | Sep 25, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [1190ad2886](https://linux-hardware.org/?probe=1190ad2886) | Sep 24, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [118cf21173](https://linux-hardware.org/?probe=118cf21173) | Sep 24, 2022 |
| Dell          | Latitude E5400              | Notebook    | [09be905a45](https://linux-hardware.org/?probe=09be905a45) | Sep 24, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [a2b3fd8ea8](https://linux-hardware.org/?probe=a2b3fd8ea8) | Sep 24, 2022 |
| Dell          | Latitude 3410               | Notebook    | [ba10ea9fc5](https://linux-hardware.org/?probe=ba10ea9fc5) | Sep 24, 2022 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | Notebook    | [5c39bdf4ab](https://linux-hardware.org/?probe=5c39bdf4ab) | Sep 24, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [2322475867](https://linux-hardware.org/?probe=2322475867) | Sep 24, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [2a7c09d404](https://linux-hardware.org/?probe=2a7c09d404) | Sep 24, 2022 |
| Intel         | X99 V1.0                    | Desktop     | [7565f85860](https://linux-hardware.org/?probe=7565f85860) | Sep 24, 2022 |
| Dell          | Latitude 5420               | Notebook    | [170a3248f6](https://linux-hardware.org/?probe=170a3248f6) | Sep 24, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [4658ef6703](https://linux-hardware.org/?probe=4658ef6703) | Sep 24, 2022 |
| Unknown       | WZBTDT1 R110                | Desktop     | [8b6b5af31a](https://linux-hardware.org/?probe=8b6b5af31a) | Sep 24, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [1e9a7dd793](https://linux-hardware.org/?probe=1e9a7dd793) | Sep 24, 2022 |
| ASUSTek       | M2N68                       | Desktop     | [4b23dadbca](https://linux-hardware.org/?probe=4b23dadbca) | Sep 23, 2022 |
| Samsung       | 550XBE/350XBE               | Notebook    | [dec88709ee](https://linux-hardware.org/?probe=dec88709ee) | Sep 23, 2022 |
| Samsung       | 550XBE/350XBE               | Notebook    | [e17fb419bd](https://linux-hardware.org/?probe=e17fb419bd) | Sep 23, 2022 |
| Foxconn       | Q77M                        | Desktop     | [63d0fe0c57](https://linux-hardware.org/?probe=63d0fe0c57) | Sep 23, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [4ed9eae431](https://linux-hardware.org/?probe=4ed9eae431) | Sep 23, 2022 |
| Biostar       | TA75MH2                     | Desktop     | [e76fb13311](https://linux-hardware.org/?probe=e76fb13311) | Sep 23, 2022 |
| ASRock        | G31M-S                      | Desktop     | [76d9b33c76](https://linux-hardware.org/?probe=76d9b33c76) | Sep 23, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [991137f04f](https://linux-hardware.org/?probe=991137f04f) | Sep 23, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [b02d161acb](https://linux-hardware.org/?probe=b02d161acb) | Sep 23, 2022 |
| ASUSTek       | M2N68-AM SE2                | Desktop     | [412f70b76b](https://linux-hardware.org/?probe=412f70b76b) | Sep 23, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [c05619dc16](https://linux-hardware.org/?probe=c05619dc16) | Sep 23, 2022 |
| Gigabyte      | H110M-S2H DDR3-CF           | Desktop     | [fef79bcff4](https://linux-hardware.org/?probe=fef79bcff4) | Sep 22, 2022 |
| Foxconn       | H61M-S/H61M                 | Desktop     | [039b5cff54](https://linux-hardware.org/?probe=039b5cff54) | Sep 22, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [630b3877c4](https://linux-hardware.org/?probe=630b3877c4) | Sep 22, 2022 |
| Gigabyte      | 945GM-S2                    | Desktop     | [9fcea940e6](https://linux-hardware.org/?probe=9fcea940e6) | Sep 22, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [d852d9e0dd](https://linux-hardware.org/?probe=d852d9e0dd) | Sep 22, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [fb451b6d7d](https://linux-hardware.org/?probe=fb451b6d7d) | Sep 22, 2022 |
| Avell High... | B.ON                        | Notebook    | [95c7e35ef3](https://linux-hardware.org/?probe=95c7e35ef3) | Sep 22, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [3c93753c6c](https://linux-hardware.org/?probe=3c93753c6c) | Sep 22, 2022 |
| Sony          | SVE15125CBW                 | Notebook    | [50b65906b1](https://linux-hardware.org/?probe=50b65906b1) | Sep 22, 2022 |
| OEM           | B75 Ver:1.41                | Desktop     | [e22d2bac17](https://linux-hardware.org/?probe=e22d2bac17) | Sep 22, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [183f486a54](https://linux-hardware.org/?probe=183f486a54) | Sep 21, 2022 |
| Intel         | DN2800MT AAG23738-801       | Desktop     | [0019b51cff](https://linux-hardware.org/?probe=0019b51cff) | Sep 21, 2022 |
| Avell High... | B.ON                        | Notebook    | [aaebcf57bb](https://linux-hardware.org/?probe=aaebcf57bb) | Sep 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [74d69dbd69](https://linux-hardware.org/?probe=74d69dbd69) | Sep 21, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [5c6ebb2cfe](https://linux-hardware.org/?probe=5c6ebb2cfe) | Sep 21, 2022 |
| Acer          | Aspire A515-54              | Notebook    | [8116705a81](https://linux-hardware.org/?probe=8116705a81) | Sep 21, 2022 |
| Digiboard     | NM70-TI                     | Desktop     | [84e21c8253](https://linux-hardware.org/?probe=84e21c8253) | Sep 21, 2022 |
| ASUSTek       | X451CA                      | Notebook    | [bdfe92eb66](https://linux-hardware.org/?probe=bdfe92eb66) | Sep 21, 2022 |
| LG Electro... | C400-G.BC22P1               | Notebook    | [b5aad7f903](https://linux-hardware.org/?probe=b5aad7f903) | Sep 20, 2022 |
| ASUSTek       | K46CB                       | Notebook    | [88cbbeaee6](https://linux-hardware.org/?probe=88cbbeaee6) | Sep 20, 2022 |
| Digiboard     | NM70-TI                     | Desktop     | [ace83d527c](https://linux-hardware.org/?probe=ace83d527c) | Sep 20, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [9b0dd73d61](https://linux-hardware.org/?probe=9b0dd73d61) | Sep 20, 2022 |
| Dell          | 0KY237 A01                  | Desktop     | [e1258b712e](https://linux-hardware.org/?probe=e1258b712e) | Sep 20, 2022 |
| Dell          | 0KY237 A01                  | Desktop     | [6f2ce8e794](https://linux-hardware.org/?probe=6f2ce8e794) | Sep 20, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9d0697ec96](https://linux-hardware.org/?probe=9d0697ec96) | Sep 20, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [38234e238c](https://linux-hardware.org/?probe=38234e238c) | Sep 20, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [14351cab57](https://linux-hardware.org/?probe=14351cab57) | Sep 20, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [54d0318e27](https://linux-hardware.org/?probe=54d0318e27) | Sep 20, 2022 |
| Supermicro    | SKAGIT09                    | Desktop     | [b7dcf8a06c](https://linux-hardware.org/?probe=b7dcf8a06c) | Sep 20, 2022 |
| Dell          | 0D883F A06                  | Desktop     | [55f97310c8](https://linux-hardware.org/?probe=55f97310c8) | Sep 20, 2022 |
| LG Electro... | C400-G.BC31P1               | Notebook    | [66c8977810](https://linux-hardware.org/?probe=66c8977810) | Sep 19, 2022 |
| Intel         | X99 V1.0                    | Desktop     | [02bfe94d24](https://linux-hardware.org/?probe=02bfe94d24) | Sep 19, 2022 |
| Samsung       | 300E5K/300E5Q               | Notebook    | [aaedf90f31](https://linux-hardware.org/?probe=aaedf90f31) | Sep 19, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [a681a7cab8](https://linux-hardware.org/?probe=a681a7cab8) | Sep 19, 2022 |
| Lenovo        | G50-80 80R0                 | Notebook    | [f04ed15344](https://linux-hardware.org/?probe=f04ed15344) | Sep 19, 2022 |
| Gigabyte      | A520M DS3H                  | Desktop     | [bf7318e65e](https://linux-hardware.org/?probe=bf7318e65e) | Sep 19, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [136eca7e32](https://linux-hardware.org/?probe=136eca7e32) | Sep 19, 2022 |
| Lenovo        | Legion 5 15ACH6 82QJ        | Notebook    | [e2c5e4775c](https://linux-hardware.org/?probe=e2c5e4775c) | Sep 19, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [37fc6237e2](https://linux-hardware.org/?probe=37fc6237e2) | Sep 19, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [40629d6fbc](https://linux-hardware.org/?probe=40629d6fbc) | Sep 19, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [b98206a5fb](https://linux-hardware.org/?probe=b98206a5fb) | Sep 19, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [41b1b790fd](https://linux-hardware.org/?probe=41b1b790fd) | Sep 19, 2022 |
| Positivo      | C14CR21                     | Notebook    | [e72ef2677b](https://linux-hardware.org/?probe=e72ef2677b) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [8468466b2a](https://linux-hardware.org/?probe=8468466b2a) | Sep 19, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [58d84150d6](https://linux-hardware.org/?probe=58d84150d6) | Sep 18, 2022 |
| Samsung       | 370E4K                      | Notebook    | [1a297b75f9](https://linux-hardware.org/?probe=1a297b75f9) | Sep 18, 2022 |
| MSI           | A68HM-E33                   | Desktop     | [2905913e7e](https://linux-hardware.org/?probe=2905913e7e) | Sep 18, 2022 |
| Dell          | 0KY237 A01                  | Desktop     | [8b2d50f5d1](https://linux-hardware.org/?probe=8b2d50f5d1) | Sep 18, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [cd1441d5a4](https://linux-hardware.org/?probe=cd1441d5a4) | Sep 18, 2022 |
| PCWare        | IPMH110G                    | Desktop     | [6ba309be15](https://linux-hardware.org/?probe=6ba309be15) | Sep 18, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [9e3edc5b61](https://linux-hardware.org/?probe=9e3edc5b61) | Sep 18, 2022 |
| ASUSTek       | M4A785-M                    | Desktop     | [411449bc6d](https://linux-hardware.org/?probe=411449bc6d) | Sep 18, 2022 |
| Intel         | H61                         | Desktop     | [923e50e023](https://linux-hardware.org/?probe=923e50e023) | Sep 18, 2022 |
| Gateway       | NV55C                       | Notebook    | [e00587af22](https://linux-hardware.org/?probe=e00587af22) | Sep 18, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [08bd4157a3](https://linux-hardware.org/?probe=08bd4157a3) | Sep 18, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [7b918ebeb8](https://linux-hardware.org/?probe=7b918ebeb8) | Sep 18, 2022 |
| Samsung       | 670Z5E                      | Notebook    | [50758a53dd](https://linux-hardware.org/?probe=50758a53dd) | Sep 18, 2022 |
| MSI           | J1800I                      | Desktop     | [ff28c29a3e](https://linux-hardware.org/?probe=ff28c29a3e) | Sep 18, 2022 |
| Lenovo        | ThinkPad T430 23501M2       | Notebook    | [b9503c9c28](https://linux-hardware.org/?probe=b9503c9c28) | Sep 18, 2022 |
| MSI           | B360M MORTAR                | Desktop     | [cdcff8c15d](https://linux-hardware.org/?probe=cdcff8c15d) | Sep 18, 2022 |
| HP            | ProBook 6470b               | Notebook    | [3821322b95](https://linux-hardware.org/?probe=3821322b95) | Sep 18, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [edc0c871cb](https://linux-hardware.org/?probe=edc0c871cb) | Sep 17, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [3de0a6e725](https://linux-hardware.org/?probe=3de0a6e725) | Sep 17, 2022 |
| Samsung       | 275E4E/275E5E               | Notebook    | [89706d3dac](https://linux-hardware.org/?probe=89706d3dac) | Sep 17, 2022 |
| Intel         | X79M-S                      | Desktop     | [91e75d3183](https://linux-hardware.org/?probe=91e75d3183) | Sep 17, 2022 |
| Intel         | X79M-S                      | Desktop     | [48c5f5ed77](https://linux-hardware.org/?probe=48c5f5ed77) | Sep 17, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [44a3455d48](https://linux-hardware.org/?probe=44a3455d48) | Sep 17, 2022 |
| Intel         | X99 V1.0                    | Desktop     | [735c794db9](https://linux-hardware.org/?probe=735c794db9) | Sep 17, 2022 |
| Dell          | Vostro 15 3510              | Notebook    | [d70dc7ab47](https://linux-hardware.org/?probe=d70dc7ab47) | Sep 16, 2022 |
| Dell          | Vostro 15 3510              | Notebook    | [0bcb975501](https://linux-hardware.org/?probe=0bcb975501) | Sep 16, 2022 |
| Intel         | H61                         | Desktop     | [d1b17183d7](https://linux-hardware.org/?probe=d1b17183d7) | Sep 16, 2022 |
| Lenovo        | G480 20149                  | Notebook    | [8fed7863dd](https://linux-hardware.org/?probe=8fed7863dd) | Sep 16, 2022 |
| Dell          | Inspiron 5547               | Notebook    | [d66cbae64b](https://linux-hardware.org/?probe=d66cbae64b) | Sep 16, 2022 |
| Acer          | Aspire A515-51              | Notebook    | [59811273b4](https://linux-hardware.org/?probe=59811273b4) | Sep 16, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [52fe410fe3](https://linux-hardware.org/?probe=52fe410fe3) | Sep 16, 2022 |
| Unknown       | Unknown                     | Notebook    | [d391ace7f8](https://linux-hardware.org/?probe=d391ace7f8) | Sep 16, 2022 |
| Dell          | G7 7588                     | Notebook    | [583c4a4c91](https://linux-hardware.org/?probe=583c4a4c91) | Sep 16, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [283a38bb80](https://linux-hardware.org/?probe=283a38bb80) | Sep 16, 2022 |
| HP            | Compaq Presario CQ50        | Notebook    | [41dcd9ffc4](https://linux-hardware.org/?probe=41dcd9ffc4) | Sep 16, 2022 |
| HP            | ProBook 4530s               | Notebook    | [821a6eda47](https://linux-hardware.org/?probe=821a6eda47) | Sep 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [c292f41bc5](https://linux-hardware.org/?probe=c292f41bc5) | Sep 15, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [29241bb609](https://linux-hardware.org/?probe=29241bb609) | Sep 15, 2022 |
| MACHINIST     | X99-RS9 V3.0                | Desktop     | [3f9fc3fc62](https://linux-hardware.org/?probe=3f9fc3fc62) | Sep 15, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [13cd2039a1](https://linux-hardware.org/?probe=13cd2039a1) | Sep 15, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [0a02b8ef94](https://linux-hardware.org/?probe=0a02b8ef94) | Sep 15, 2022 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [6d40add21a](https://linux-hardware.org/?probe=6d40add21a) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [6de8f25119](https://linux-hardware.org/?probe=6de8f25119) | Sep 15, 2022 |
| Positivo      | Mobile                      | Notebook    | [f0f7335929](https://linux-hardware.org/?probe=f0f7335929) | Sep 15, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [24ba1c9bc3](https://linux-hardware.org/?probe=24ba1c9bc3) | Sep 15, 2022 |
| Dell          | Latitude 3420               | Notebook    | [5c00a1875c](https://linux-hardware.org/?probe=5c00a1875c) | Sep 14, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [9c97b9e2c1](https://linux-hardware.org/?probe=9c97b9e2c1) | Sep 14, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [763b0fced4](https://linux-hardware.org/?probe=763b0fced4) | Sep 14, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3557099732](https://linux-hardware.org/?probe=3557099732) | Sep 14, 2022 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [06d4572f5e](https://linux-hardware.org/?probe=06d4572f5e) | Sep 14, 2022 |
| Dell          | 0TW904 A01                  | Desktop     | [141188a631](https://linux-hardware.org/?probe=141188a631) | Sep 14, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [8ec7217b7d](https://linux-hardware.org/?probe=8ec7217b7d) | Sep 14, 2022 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [daab24c8b6](https://linux-hardware.org/?probe=daab24c8b6) | Sep 14, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [47b0975057](https://linux-hardware.org/?probe=47b0975057) | Sep 13, 2022 |
| HP            | 1000                        | Notebook    | [65024f3d7a](https://linux-hardware.org/?probe=65024f3d7a) | Sep 13, 2022 |
| Gigabyte      | Z690 UD AX DDR4             | Desktop     | [70aa78efc6](https://linux-hardware.org/?probe=70aa78efc6) | Sep 13, 2022 |
| Positivo      | POS-PQ45AU                  | Desktop     | [0879f8d9ce](https://linux-hardware.org/?probe=0879f8d9ce) | Sep 13, 2022 |
| Lenovo        | B40-70 80F30005BR           | Notebook    | [b899f1b7da](https://linux-hardware.org/?probe=b899f1b7da) | Sep 13, 2022 |
| Lenovo        | B40-70 80F30005BR           | Notebook    | [99be4451df](https://linux-hardware.org/?probe=99be4451df) | Sep 13, 2022 |
| MACHINIST     | X99-RS9 V3.0                | Desktop     | [64795f6f69](https://linux-hardware.org/?probe=64795f6f69) | Sep 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [16cf967fc8](https://linux-hardware.org/?probe=16cf967fc8) | Sep 13, 2022 |
| Dell          | 04YP6J A00                  | Desktop     | [ef4ae2baac](https://linux-hardware.org/?probe=ef4ae2baac) | Sep 13, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [47ff6a8255](https://linux-hardware.org/?probe=47ff6a8255) | Sep 13, 2022 |
| Positivo      | POS-EINM10CB POSITIVO       | Desktop     | [7c876e560b](https://linux-hardware.org/?probe=7c876e560b) | Sep 13, 2022 |
| Acer          | Aspire 5050                 | Notebook    | [1961d1c468](https://linux-hardware.org/?probe=1961d1c468) | Sep 13, 2022 |
| ASRock        | FM2A55M-HD+ R2.0            | Desktop     | [1faad914c6](https://linux-hardware.org/?probe=1faad914c6) | Sep 13, 2022 |
| Unknown       | X99H                        | Desktop     | [9fb8886110](https://linux-hardware.org/?probe=9fb8886110) | Sep 13, 2022 |
| Compal        | NCL60/61                    | Notebook    | [f1f5499af8](https://linux-hardware.org/?probe=f1f5499af8) | Sep 12, 2022 |
| Dell          | Inspiron 5458               | Notebook    | [bd26475724](https://linux-hardware.org/?probe=bd26475724) | Sep 12, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [ca9a099cf6](https://linux-hardware.org/?probe=ca9a099cf6) | Sep 12, 2022 |
| Samsung       | RV415/RV515                 | Notebook    | [bc83707f72](https://linux-hardware.org/?probe=bc83707f72) | Sep 12, 2022 |
| HP            | EliteBook 2530p             | Notebook    | [4bae06f3d0](https://linux-hardware.org/?probe=4bae06f3d0) | Sep 12, 2022 |
| PCWare        | IPMH61R3                    | Desktop     | [2312ab0f92](https://linux-hardware.org/?probe=2312ab0f92) | Sep 12, 2022 |
| Intel         | H61                         | Desktop     | [d805e24841](https://linux-hardware.org/?probe=d805e24841) | Sep 12, 2022 |
| Dell          | Inspiron 5548               | Notebook    | [341b48f953](https://linux-hardware.org/?probe=341b48f953) | Sep 12, 2022 |
| Avell High... | B.ON                        | Notebook    | [f30bca74ab](https://linux-hardware.org/?probe=f30bca74ab) | Sep 12, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [73684f0e47](https://linux-hardware.org/?probe=73684f0e47) | Sep 12, 2022 |
| Chuwi         | UBook                       | Tablet      | [89a54f0af1](https://linux-hardware.org/?probe=89a54f0af1) | Sep 12, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [09d0fcce0e](https://linux-hardware.org/?probe=09d0fcce0e) | Sep 12, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [94c783f944](https://linux-hardware.org/?probe=94c783f944) | Sep 11, 2022 |
| Intel         | X79G V2.x                   | Desktop     | [3cb7aa6549](https://linux-hardware.org/?probe=3cb7aa6549) | Sep 11, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [afbb849b02](https://linux-hardware.org/?probe=afbb849b02) | Sep 11, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [5e98f641f1](https://linux-hardware.org/?probe=5e98f641f1) | Sep 11, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [aa4d90c7e7](https://linux-hardware.org/?probe=aa4d90c7e7) | Sep 11, 2022 |
| Acer          | Aspire ES1-411              | Notebook    | [064b2bd5f2](https://linux-hardware.org/?probe=064b2bd5f2) | Sep 11, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [7aad54fefa](https://linux-hardware.org/?probe=7aad54fefa) | Sep 11, 2022 |
| Acer          | Aspire A315-42G             | Notebook    | [34964d8e2d](https://linux-hardware.org/?probe=34964d8e2d) | Sep 11, 2022 |
| ASUSTek       | K46CA                       | Notebook    | [9e730cbd6a](https://linux-hardware.org/?probe=9e730cbd6a) | Sep 11, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [fab48b6c15](https://linux-hardware.org/?probe=fab48b6c15) | Sep 10, 2022 |
| Acer          | Aspire ES1-411              | Notebook    | [6bbebcbcb1](https://linux-hardware.org/?probe=6bbebcbcb1) | Sep 10, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [41b9796681](https://linux-hardware.org/?probe=41b9796681) | Sep 10, 2022 |
| ASUSTek       | K53E                        | Notebook    | [d39f35f5d9](https://linux-hardware.org/?probe=d39f35f5d9) | Sep 10, 2022 |
| MSI           | A320M GAMING PRO            | Desktop     | [6ce0fb28ee](https://linux-hardware.org/?probe=6ce0fb28ee) | Sep 10, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [c027a7cf99](https://linux-hardware.org/?probe=c027a7cf99) | Sep 10, 2022 |
| MSI           | A320M GAMING PRO            | Desktop     | [5cce5f5ade](https://linux-hardware.org/?probe=5cce5f5ade) | Sep 10, 2022 |
| PCWare        | IPMH61R1                    | Desktop     | [d79e449b58](https://linux-hardware.org/?probe=d79e449b58) | Sep 10, 2022 |
| Lenovo        | ThinkPad T460 20FMS271BR    | Notebook    | [f2f2786b99](https://linux-hardware.org/?probe=f2f2786b99) | Sep 10, 2022 |
| Dell          | G15 5511                    | Notebook    | [b971c27fae](https://linux-hardware.org/?probe=b971c27fae) | Sep 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [5cfe072b9c](https://linux-hardware.org/?probe=5cfe072b9c) | Sep 10, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [b8a5448c05](https://linux-hardware.org/?probe=b8a5448c05) | Sep 10, 2022 |
| PCWare        | IPMH61R1                    | Desktop     | [1d6ec4fb3b](https://linux-hardware.org/?probe=1d6ec4fb3b) | Sep 10, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [9f5bc258b6](https://linux-hardware.org/?probe=9f5bc258b6) | Sep 10, 2022 |
| LG Electro... | U560-G.BG31P1               | Notebook    | [741c3eddbe](https://linux-hardware.org/?probe=741c3eddbe) | Sep 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | Notebook    | [823dbe2390](https://linux-hardware.org/?probe=823dbe2390) | Sep 10, 2022 |
| Intel         | Unknown                     | Desktop     | [74059aa424](https://linux-hardware.org/?probe=74059aa424) | Sep 10, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [8d1d861b1c](https://linux-hardware.org/?probe=8d1d861b1c) | Sep 09, 2022 |
| Acer          | Aspire E1-572               | Notebook    | [1cfbfd9b91](https://linux-hardware.org/?probe=1cfbfd9b91) | Sep 09, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [e6c0d3de61](https://linux-hardware.org/?probe=e6c0d3de61) | Sep 09, 2022 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [944fa39fb6](https://linux-hardware.org/?probe=944fa39fb6) | Sep 09, 2022 |
| Intel         | X79G V2.x                   | Desktop     | [8efdbea978](https://linux-hardware.org/?probe=8efdbea978) | Sep 09, 2022 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [c716a6bba5](https://linux-hardware.org/?probe=c716a6bba5) | Sep 09, 2022 |
| Avell High... | A70 MOB                     | Notebook    | [1cc84e9a0d](https://linux-hardware.org/?probe=1cc84e9a0d) | Sep 09, 2022 |
| Acer          | Aspire A515-54              | Notebook    | [745c098d8a](https://linux-hardware.org/?probe=745c098d8a) | Sep 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [cc0a825c8e](https://linux-hardware.org/?probe=cc0a825c8e) | Sep 09, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [7d9ebaa4f8](https://linux-hardware.org/?probe=7d9ebaa4f8) | Sep 09, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [92ae6811fa](https://linux-hardware.org/?probe=92ae6811fa) | Sep 09, 2022 |
| Positivo      | H14BT58                     | Notebook    | [669a466b1c](https://linux-hardware.org/?probe=669a466b1c) | Sep 09, 2022 |
| Supermicro    | SKAGIT09                    | Desktop     | [d3f42d0c24](https://linux-hardware.org/?probe=d3f42d0c24) | Sep 08, 2022 |
| Intel         | X99                         | Desktop     | [9ebaa38244](https://linux-hardware.org/?probe=9ebaa38244) | Sep 08, 2022 |
| Lenovo        | IdeaPad S400 20195          | Notebook    | [6bd3292f42](https://linux-hardware.org/?probe=6bd3292f42) | Sep 08, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [d37b0f4483](https://linux-hardware.org/?probe=d37b0f4483) | Sep 08, 2022 |
| Dell          | Inspiron 5457               | Notebook    | [e44e9d3a85](https://linux-hardware.org/?probe=e44e9d3a85) | Sep 08, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [f04353bb0e](https://linux-hardware.org/?probe=f04353bb0e) | Sep 08, 2022 |
| ASUSTek       | K46CB                       | Notebook    | [9449630b6a](https://linux-hardware.org/?probe=9449630b6a) | Sep 08, 2022 |
| Samsung       | 300E5M/300E5L               | Notebook    | [1d73ebcfb8](https://linux-hardware.org/?probe=1d73ebcfb8) | Sep 08, 2022 |
| Acer          | Aspire ES1-411              | Notebook    | [d3df9a2592](https://linux-hardware.org/?probe=d3df9a2592) | Sep 08, 2022 |
| Digibras      | US41II1                     | Notebook    | [890a4894cf](https://linux-hardware.org/?probe=890a4894cf) | Sep 08, 2022 |
| Samsung       | 300E5M/300E5L               | Notebook    | [de1ddd77dd](https://linux-hardware.org/?probe=de1ddd77dd) | Sep 08, 2022 |
| Gigabyte      | H110M-S2H DDR3-CF           | Desktop     | [4942b09228](https://linux-hardware.org/?probe=4942b09228) | Sep 08, 2022 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | Notebook    | [09e8283762](https://linux-hardware.org/?probe=09e8283762) | Sep 08, 2022 |
| Intel         | D33217CK G76541-301         | Desktop     | [1f1e6e67ab](https://linux-hardware.org/?probe=1f1e6e67ab) | Sep 07, 2022 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | Notebook    | [e73c83b5c7](https://linux-hardware.org/?probe=e73c83b5c7) | Sep 07, 2022 |
| Biostar       | G41D3C                      | Desktop     | [2825db69bf](https://linux-hardware.org/?probe=2825db69bf) | Sep 07, 2022 |
| Positivo      | POS-PQ45AU                  | Desktop     | [2770dcd81a](https://linux-hardware.org/?probe=2770dcd81a) | Sep 07, 2022 |
| Unknown       | GSUO H61V10C                | Desktop     | [4eeb38bb0a](https://linux-hardware.org/?probe=4eeb38bb0a) | Sep 07, 2022 |
| Positivo      | Mobile                      | Notebook    | [1378222b07](https://linux-hardware.org/?probe=1378222b07) | Sep 07, 2022 |
| Lenovo        | ThinkPad T400 2767E53       | Notebook    | [104331cf4c](https://linux-hardware.org/?probe=104331cf4c) | Sep 07, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [f547e07cca](https://linux-hardware.org/?probe=f547e07cca) | Sep 07, 2022 |
| Gigabyte      | VM900M                      | Desktop     | [c6eefaabf9](https://linux-hardware.org/?probe=c6eefaabf9) | Sep 07, 2022 |
| Positivo      | Smash                       | Notebook    | [0051f458c6](https://linux-hardware.org/?probe=0051f458c6) | Sep 07, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | Notebook    | [c0e98bf9e5](https://linux-hardware.org/?probe=c0e98bf9e5) | Sep 06, 2022 |
| LG Electro... | A530-T.BE76P1               | Notebook    | [46161b573f](https://linux-hardware.org/?probe=46161b573f) | Sep 06, 2022 |
| Lenovo        | ThinkPad T420 4236PNP       | Notebook    | [7c3dc0af20](https://linux-hardware.org/?probe=7c3dc0af20) | Sep 06, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [b12a6d2146](https://linux-hardware.org/?probe=b12a6d2146) | Sep 06, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [48a1236943](https://linux-hardware.org/?probe=48a1236943) | Sep 06, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO II     | Desktop     | [b1bdd1703e](https://linux-hardware.org/?probe=b1bdd1703e) | Sep 06, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [1020dfb637](https://linux-hardware.org/?probe=1020dfb637) | Sep 06, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [44c27d1083](https://linux-hardware.org/?probe=44c27d1083) | Sep 06, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [ec3283d49b](https://linux-hardware.org/?probe=ec3283d49b) | Sep 06, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [f61f170b4c](https://linux-hardware.org/?probe=f61f170b4c) | Sep 06, 2022 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [6f848cd309](https://linux-hardware.org/?probe=6f848cd309) | Sep 06, 2022 |
| Dell          | Vostro 14-5480              | Notebook    | [fb3ae25db8](https://linux-hardware.org/?probe=fb3ae25db8) | Sep 06, 2022 |
| Intel         | H61                         | Desktop     | [b2d888f266](https://linux-hardware.org/?probe=b2d888f266) | Sep 05, 2022 |
| Positivo B... | VJFE52F11X-B0611H           | Notebook    | [93d596fc4f](https://linux-hardware.org/?probe=93d596fc4f) | Sep 05, 2022 |
| ASUSTek       | P5GZ-MX                     | Desktop     | [883739db23](https://linux-hardware.org/?probe=883739db23) | Sep 05, 2022 |
| Multilaser    | PC112                       | Convertible | [b4a0a8d399](https://linux-hardware.org/?probe=b4a0a8d399) | Sep 05, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [beb1aeb4ad](https://linux-hardware.org/?probe=beb1aeb4ad) | Sep 05, 2022 |
| Alienware     | m15 R7                      | Notebook    | [c9d5bcb40f](https://linux-hardware.org/?probe=c9d5bcb40f) | Sep 05, 2022 |
| Intel         | B75                         | Desktop     | [eca0b46101](https://linux-hardware.org/?probe=eca0b46101) | Sep 05, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [f44a7ef51c](https://linux-hardware.org/?probe=f44a7ef51c) | Sep 05, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [9d9451305b](https://linux-hardware.org/?probe=9d9451305b) | Sep 05, 2022 |
| ASUSTek       | X45C                        | Notebook    | [7267b251b6](https://linux-hardware.org/?probe=7267b251b6) | Sep 05, 2022 |
| Positivo B... | VJFE52F11X-B0611H           | Notebook    | [0e3fd8d374](https://linux-hardware.org/?probe=0e3fd8d374) | Sep 05, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | Desktop     | [1f5b368c96](https://linux-hardware.org/?probe=1f5b368c96) | Sep 05, 2022 |
| PCWare        | IPMH61R3                    | Desktop     | [1cbe0ee116](https://linux-hardware.org/?probe=1cbe0ee116) | Sep 04, 2022 |
| Lenovo        | G40-80 80JE                 | Notebook    | [c876beae17](https://linux-hardware.org/?probe=c876beae17) | Sep 04, 2022 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [078680a25d](https://linux-hardware.org/?probe=078680a25d) | Sep 04, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [61e1164988](https://linux-hardware.org/?probe=61e1164988) | Sep 04, 2022 |
| Lenovo        | G40-80 80JE                 | Notebook    | [e6fa43e12e](https://linux-hardware.org/?probe=e6fa43e12e) | Sep 04, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [920bfdae34](https://linux-hardware.org/?probe=920bfdae34) | Sep 04, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [db5a53a31c](https://linux-hardware.org/?probe=db5a53a31c) | Sep 03, 2022 |
| Timi          | TM1701                      | Notebook    | [740d59830a](https://linux-hardware.org/?probe=740d59830a) | Sep 03, 2022 |
| Samsung       | 300E5M/300E5L               | Notebook    | [3d542c8484](https://linux-hardware.org/?probe=3d542c8484) | Sep 03, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [6aac0a8c6c](https://linux-hardware.org/?probe=6aac0a8c6c) | Sep 03, 2022 |
| Intel         | DX58SO AAE29331-702         | Desktop     | [24c48ddc3e](https://linux-hardware.org/?probe=24c48ddc3e) | Sep 03, 2022 |
| Intel         | H61                         | Desktop     | [af78b53f51](https://linux-hardware.org/?probe=af78b53f51) | Sep 03, 2022 |
| ASUSTek       | P8B75-V                     | Desktop     | [2ae6d7c950](https://linux-hardware.org/?probe=2ae6d7c950) | Sep 03, 2022 |
| Itautec       | Infoway                     | Notebook    | [d207af3252](https://linux-hardware.org/?probe=d207af3252) | Sep 03, 2022 |
| Itautec       | Infoway                     | Notebook    | [737122a0d1](https://linux-hardware.org/?probe=737122a0d1) | Sep 03, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [e742b2e06c](https://linux-hardware.org/?probe=e742b2e06c) | Sep 03, 2022 |
| Daten Tecn... | DT02-M4                     | Notebook    | [b697980a15](https://linux-hardware.org/?probe=b697980a15) | Sep 03, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [9a2200f8f8](https://linux-hardware.org/?probe=9a2200f8f8) | Sep 03, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | Notebook    | [a4290c0678](https://linux-hardware.org/?probe=a4290c0678) | Sep 03, 2022 |
| Dell          | 07PR60 A01                  | Desktop     | [d37a4374eb](https://linux-hardware.org/?probe=d37a4374eb) | Sep 02, 2022 |
| ECS           | H61H2-M2                    | Desktop     | [11dd923e56](https://linux-hardware.org/?probe=11dd923e56) | Sep 02, 2022 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [548332086b](https://linux-hardware.org/?probe=548332086b) | Sep 02, 2022 |
| MSI           | H97 GAMING 3                | Desktop     | [a5fb8d7651](https://linux-hardware.org/?probe=a5fb8d7651) | Sep 02, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [b54a09966b](https://linux-hardware.org/?probe=b54a09966b) | Sep 02, 2022 |
| AMI           | T3 MRD                      | Desktop     | [d0a254e1b7](https://linux-hardware.org/?probe=d0a254e1b7) | Sep 02, 2022 |
| Samsung       | 670Z5E                      | Notebook    | [0e65ce891e](https://linux-hardware.org/?probe=0e65ce891e) | Sep 02, 2022 |
| Samsung       | 670Z5E                      | Notebook    | [595f13e0b9](https://linux-hardware.org/?probe=595f13e0b9) | Sep 02, 2022 |
| Samsung       | 550XBE/350XBE               | Notebook    | [0104e26464](https://linux-hardware.org/?probe=0104e26464) | Sep 02, 2022 |
| Gigabyte      | H110M-S2H DDR3-CF           | Desktop     | [9525064f53](https://linux-hardware.org/?probe=9525064f53) | Sep 02, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [f42a136e4f](https://linux-hardware.org/?probe=f42a136e4f) | Sep 02, 2022 |
| Samsung       | 270E5G/270E5U               | Notebook    | [7ef3570396](https://linux-hardware.org/?probe=7ef3570396) | Sep 02, 2022 |
| Dell          | G15 5510                    | Notebook    | [78f2f5c95a](https://linux-hardware.org/?probe=78f2f5c95a) | Sep 01, 2022 |
| Dell          | G3 3590                     | Notebook    | [cbe6c26276](https://linux-hardware.org/?probe=cbe6c26276) | Sep 01, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [e14cc69370](https://linux-hardware.org/?probe=e14cc69370) | Sep 01, 2022 |
| Lenovo        | 3168 NOK                    | Desktop     | [58c82b01e2](https://linux-hardware.org/?probe=58c82b01e2) | Sep 01, 2022 |
| Positivo      | C14CR01                     | Notebook    | [ff4d1d45b7](https://linux-hardware.org/?probe=ff4d1d45b7) | Sep 01, 2022 |
| Positivo      | C14CR01                     | Notebook    | [d1fc217886](https://linux-hardware.org/?probe=d1fc217886) | Sep 01, 2022 |
| Avell High... | C62 MOB                     | Notebook    | [ab93c1f314](https://linux-hardware.org/?probe=ab93c1f314) | Sep 01, 2022 |
| Daten Tecn... | DT02-M4                     | Notebook    | [6e337cb132](https://linux-hardware.org/?probe=6e337cb132) | Sep 01, 2022 |
| Daten Tecn... | DT02-M4                     | Notebook    | [cdac9cafaf](https://linux-hardware.org/?probe=cdac9cafaf) | Sep 01, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [ad36524b16](https://linux-hardware.org/?probe=ad36524b16) | Sep 01, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [7759e41b1d](https://linux-hardware.org/?probe=7759e41b1d) | Sep 01, 2022 |
| ASRock        | FM2A55M-HD+                 | Desktop     | [2f96c73efb](https://linux-hardware.org/?probe=2f96c73efb) | Sep 01, 2022 |
| ASRock        | N68-GS4 FX R2.0             | Desktop     | [ea730c9b2d](https://linux-hardware.org/?probe=ea730c9b2d) | Sep 01, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [838e09c9cf](https://linux-hardware.org/?probe=838e09c9cf) | Sep 01, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [c1d60c7b0b](https://linux-hardware.org/?probe=c1d60c7b0b) | Aug 31, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [dafd789095](https://linux-hardware.org/?probe=dafd789095) | Aug 31, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [7850c07cdc](https://linux-hardware.org/?probe=7850c07cdc) | Aug 31, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [e9386667fa](https://linux-hardware.org/?probe=e9386667fa) | Aug 31, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [4db54180a8](https://linux-hardware.org/?probe=4db54180a8) | Aug 31, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [c26bf23cdd](https://linux-hardware.org/?probe=c26bf23cdd) | Aug 31, 2022 |
| Samsung       | 670Z5E                      | Notebook    | [c72797ddaa](https://linux-hardware.org/?probe=c72797ddaa) | Aug 31, 2022 |
| Samsung       | 930QDB                      | Convertible | [90bcd97cbb](https://linux-hardware.org/?probe=90bcd97cbb) | Aug 31, 2022 |
| Samsung       | 930QDB                      | Convertible | [fec5bf86f1](https://linux-hardware.org/?probe=fec5bf86f1) | Aug 31, 2022 |
| Lenovo        | ThinkPad T400 2767E53       | Notebook    | [454c7382bd](https://linux-hardware.org/?probe=454c7382bd) | Aug 31, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [988032b933](https://linux-hardware.org/?probe=988032b933) | Aug 31, 2022 |
| Positivo      | W942SW_SW1                  | Notebook    | [bec76a1474](https://linux-hardware.org/?probe=bec76a1474) | Aug 30, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [9fe8c04ec6](https://linux-hardware.org/?probe=9fe8c04ec6) | Aug 30, 2022 |
| Gigabyte      | VM900M                      | Desktop     | [f446d835da](https://linux-hardware.org/?probe=f446d835da) | Aug 30, 2022 |
| Avell High... | B.ON                        | Notebook    | [dbc18dad43](https://linux-hardware.org/?probe=dbc18dad43) | Aug 30, 2022 |
| ASUSTek       | ROG Maximus XII EXTREME     | Desktop     | [a77d5e141e](https://linux-hardware.org/?probe=a77d5e141e) | Aug 30, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [251b320d54](https://linux-hardware.org/?probe=251b320d54) | Aug 30, 2022 |
| Gigabyte      | Z97X-Gaming 7               | Desktop     | [1c993db964](https://linux-hardware.org/?probe=1c993db964) | Aug 30, 2022 |
| Gigabyte      | Z97X-Gaming 7               | Desktop     | [91438fc6b5](https://linux-hardware.org/?probe=91438fc6b5) | Aug 30, 2022 |
| Samsung       | 300E5M/300E5L               | Notebook    | [6f920f9002](https://linux-hardware.org/?probe=6f920f9002) | Aug 29, 2022 |
| Intel         | NUC7JYB M37316-500          | Mini pc     | [0d75ce63f8](https://linux-hardware.org/?probe=0d75ce63f8) | Aug 29, 2022 |
| Positivo B... | VJFE52F11X-B0611H           | Notebook    | [eedd8fa1eb](https://linux-hardware.org/?probe=eedd8fa1eb) | Aug 29, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Brazil/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 1499      | 12.75%  |
| Ubuntu 18.04      | 1024      | 8.71%   |
| OpenMandriva 4.2  | 335       | 2.85%   |
| Pop!_OS 20.04     | 317       | 2.7%    |
| Linux Mint 20     | 313       | 2.66%   |
| Linux Mint 19.3   | 283       | 2.41%   |
| Ubuntu 22.04      | 266       | 2.26%   |
| OpenMandriva 4.3  | 257       | 2.19%   |
| Linux Mint 19.1   | 235       | 2%      |
| Ubuntu 19.04      | 218       | 1.85%   |
| KDE neon 20.04    | 213       | 1.81%   |
| Linux Mint 20.1   | 202       | 1.72%   |
| Linux Mint 20.3   | 193       | 1.64%   |
| Arch              | 189       | 1.61%   |
| Linux Mint 20.2   | 179       | 1.52%   |
| Ubuntu 19.10      | 173       | 1.47%   |
| Manjaro           | 164       | 1.4%    |
| Debian 10         | 155       | 1.32%   |
| Zorin 16          | 148       | 1.26%   |
| Zorin 15          | 148       | 1.26%   |
| Debian 11         | 129       | 1.1%    |
| Pop!_OS 21.04     | 127       | 1.08%   |
| Pop!_OS 20.10     | 127       | 1.08%   |
| Pop!_OS 22.04     | 123       | 1.05%   |
| Fedora 34         | 119       | 1.01%   |
| Xubuntu 20.04     | 114       | 0.97%   |
| Fedora 36         | 114       | 0.97%   |
| Fedora 32         | 111       | 0.94%   |
| Pop!_OS 21.10     | 110       | 0.94%   |
| Fedora 35         | 107       | 0.91%   |
| Fedora 33         | 105       | 0.89%   |
| Linux Mint 19.2   | 103       | 0.88%   |
| Kubuntu 20.04     | 101       | 0.86%   |
| Arch Rolling      | 101       | 0.86%   |
| Ubuntu MATE 20.04 | 99        | 0.84%   |
| Ubuntu 20.10      | 98        | 0.83%   |
| Ubuntu 18.10      | 83        | 0.71%   |
| Endless 3.7.8     | 77        | 0.65%   |
| Ubuntu 21.10      | 76        | 0.65%   |
| Xubuntu 18.04     | 72        | 0.61%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 3462      | 30.75%  |
| Linux Mint    | 1549      | 13.76%  |
| Endless       | 989       | 8.79%   |
| Pop!_OS       | 773       | 6.87%   |
| OpenMandriva  | 653       | 5.8%    |
| Fedora        | 621       | 5.52%   |
| Debian        | 375       | 3.33%   |
| Manjaro       | 336       | 2.98%   |
| Zorin         | 305       | 2.71%   |
| Arch          | 278       | 2.47%   |
| KDE neon      | 254       | 2.26%   |
| Xubuntu       | 213       | 1.89%   |
| Kubuntu       | 193       | 1.71%   |
| Ubuntu MATE   | 132       | 1.17%   |
| ROSA          | 122       | 1.08%   |
| Lubuntu       | 97        | 0.86%   |
| openSUSE      | 93        | 0.83%   |
| Elementary    | 88        | 0.78%   |
| Ubuntu Unity  | 79        | 0.7%    |
| LMDE          | 58        | 0.52%   |
| Kali          | 49        | 0.44%   |
| Deepin        | 45        | 0.4%    |
| LinuxFX       | 40        | 0.36%   |
| Ubuntu Budgie | 39        | 0.35%   |
| ArcoLinux     | 39        | 0.35%   |
| Clear Linux   | 34        | 0.3%    |
| BlackPanther  | 30        | 0.27%   |
| CentOS        | 29        | 0.26%   |
| BigLinux      | 20        | 0.18%   |
| EndeavourOS   | 19        | 0.17%   |
| Gentoo        | 16        | 0.14%   |
| Peppermint    | 14        | 0.12%   |
| Parrot        | 14        | 0.12%   |
| MX            | 13        | 0.12%   |
| UbuntuDDE     | 12        | 0.11%   |
| Solus         | 11        | 0.1%    |
| Linux Lite    | 11        | 0.1%    |
| Garuda Linux  | 11        | 0.1%    |
| Reborn OS     | 10        | 0.09%   |
| Void Linux    | 7         | 0.06%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 708       | 5.59%   |
| 5.10.14-desktop-1omv4002 | 324       | 2.56%   |
| 5.8.0-14-generic         | 298       | 2.35%   |
| 5.16.7-desktop-1omv4003  | 248       | 1.96%   |
| 4.15.0-46-generic        | 156       | 1.23%   |
| 5.3.0-28-generic         | 145       | 1.15%   |
| 5.4.0-48-generic         | 138       | 1.09%   |
| 5.4.0-19-generic         | 138       | 1.09%   |
| 5.4.0-7634-generic       | 123       | 0.97%   |
| 5.4.0-40-generic         | 111       | 0.88%   |
| 5.4.0-58-generic         | 108       | 0.85%   |
| 5.4.0-26-generic         | 105       | 0.83%   |
| 5.4.0-52-generic         | 101       | 0.8%    |
| 4.18.0-15-generic        | 97        | 0.77%   |
| 5.4.0-47-generic         | 96        | 0.76%   |
| 5.11.0-35-generic        | 93        | 0.73%   |
| 5.3.0-40-generic         | 89        | 0.7%    |
| 5.11.0-7620-generic      | 78        | 0.62%   |
| 5.0.0-32-generic         | 78        | 0.62%   |
| 5.3.0-46-generic         | 77        | 0.61%   |
| 5.0.0-37-generic         | 72        | 0.57%   |
| 4.15.0-20-generic        | 72        | 0.57%   |
| 5.4.0-70-generic         | 71        | 0.56%   |
| 5.4.0-72-generic         | 68        | 0.54%   |
| 5.15.0-46-generic        | 64        | 0.51%   |
| 5.4.0-91-generic         | 63        | 0.5%    |
| 5.4.0-80-generic         | 63        | 0.5%    |
| 5.3.0-23-generic         | 63        | 0.5%    |
| 5.4.0-29-generic         | 62        | 0.49%   |
| 4.18.0-16-generic        | 62        | 0.49%   |
| 5.4.0-65-generic         | 61        | 0.48%   |
| 5.4.0-37-generic         | 61        | 0.48%   |
| 5.4.0-39-generic         | 60        | 0.47%   |
| 5.15.0-52-generic        | 60        | 0.47%   |
| 5.0.0-25-generic         | 60        | 0.47%   |
| 5.4.0-74-generic         | 59        | 0.47%   |
| 5.8.0-7630-generic       | 58        | 0.46%   |
| 5.3.0-19-generic         | 58        | 0.46%   |
| 5.13.0-30-generic        | 58        | 0.46%   |
| 5.11.0-37-generic        | 58        | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 2987      | 24.94%  |
| 4.15.0  | 939       | 7.84%   |
| 5.8.0   | 879       | 7.34%   |
| 5.3.0   | 798       | 6.66%   |
| 5.11.0  | 679       | 5.67%   |
| 5.0.0   | 562       | 4.69%   |
| 5.15.0  | 483       | 4.03%   |
| 5.13.0  | 455       | 3.8%    |
| 4.18.0  | 415       | 3.47%   |
| 5.10.14 | 326       | 2.72%   |
| 5.16.7  | 248       | 2.07%   |
| 4.19.0  | 184       | 1.54%   |
| 5.10.0  | 177       | 1.48%   |
| 5.19.0  | 62        | 0.52%   |
| 5.17.5  | 58        | 0.48%   |
| 5.7.9   | 47        | 0.39%   |
| 4.4.0   | 45        | 0.38%   |
| 5.16.11 | 40        | 0.33%   |
| 4.9.0   | 38        | 0.32%   |
| 5.14.0  | 35        | 0.29%   |
| 5.15.5  | 31        | 0.26%   |
| 5.7.0   | 30        | 0.25%   |
| 5.15.15 | 30        | 0.25%   |
| 5.9.16  | 28        | 0.23%   |
| 5.6.19  | 27        | 0.23%   |
| 4.9.60  | 27        | 0.23%   |
| 5.3.18  | 25        | 0.21%   |
| 4.18.16 | 25        | 0.21%   |
| 5.13.19 | 24        | 0.2%    |
| 5.7.10  | 22        | 0.18%   |
| 5.11.12 | 22        | 0.18%   |
| 5.18.12 | 21        | 0.18%   |
| 5.16.15 | 21        | 0.18%   |
| 5.18.10 | 20        | 0.17%   |
| 5.15.8  | 20        | 0.17%   |
| 5.12.4  | 19        | 0.16%   |
| 5.9.11  | 18        | 0.15%   |
| 5.6.15  | 18        | 0.15%   |
| 5.16.0  | 18        | 0.15%   |
| 4.9.20  | 18        | 0.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 3110      | 26.28%  |
| 5.8     | 992       | 8.38%   |
| 4.15    | 939       | 7.93%   |
| 5.3     | 869       | 7.34%   |
| 5.11    | 773       | 6.53%   |
| 5.15    | 719       | 6.08%   |
| 5.10    | 693       | 5.86%   |
| 5.0     | 604       | 5.1%    |
| 5.13    | 547       | 4.62%   |
| 4.18    | 448       | 3.79%   |
| 5.16    | 425       | 3.59%   |
| 4.19    | 220       | 1.86%   |
| 5.7     | 172       | 1.45%   |
| 5.19    | 155       | 1.31%   |
| 5.17    | 149       | 1.26%   |
| 5.18    | 133       | 1.12%   |
| 5.6     | 126       | 1.06%   |
| 5.14    | 123       | 1.04%   |
| 5.12    | 113       | 0.95%   |
| 5.9     | 110       | 0.93%   |
| 4.9     | 103       | 0.87%   |
| 6.0     | 66        | 0.56%   |
| 5.5     | 50        | 0.42%   |
| 4.4     | 50        | 0.42%   |
| 5.1     | 39        | 0.33%   |
| 5.2     | 29        | 0.25%   |
| 3.10    | 14        | 0.12%   |
| 4.13    | 13        | 0.11%   |
| 4.1     | 12        | 0.1%    |
| 4.20    | 10        | 0.08%   |
| 4.10    | 8         | 0.07%   |
| 4.12    | 6         | 0.05%   |
| 4.14    | 5         | 0.04%   |
| 4.8     | 3         | 0.03%   |
| 6.1     | 2         | 0.02%   |
| 4.17    | 2         | 0.02%   |
| 6       | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 10473     | 97.01%  |
| i686    | 296       | 2.74%   |
| aarch64 | 16        | 0.15%   |
| armv7l  | 11        | 0.1%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| GNOME                    | 5141      | 45.6%   |
| Unknown                  | 1784      | 15.82%  |
| KDE5                     | 1287      | 11.41%  |
| X-Cinnamon               | 895       | 7.94%   |
| XFCE                     | 748       | 6.63%   |
| MATE                     | 330       | 2.93%   |
| KDE                      | 310       | 2.75%   |
| Cinnamon                 | 217       | 1.92%   |
| LXQt                     | 91        | 0.81%   |
| Unity                    | 81        | 0.72%   |
| Pantheon                 | 76        | 0.67%   |
| KDE4                     | 66        | 0.59%   |
| Deepin                   | 56        | 0.5%    |
| Budgie                   | 56        | 0.5%    |
| LXDE                     | 48        | 0.43%   |
| i3                       | 28        | 0.25%   |
| GNOME Flashback          | 16        | 0.14%   |
| GNOME Classic            | 12        | 0.11%   |
| awesome                  | 9         | 0.08%   |
| Enlightenment            | 5         | 0.04%   |
| sway                     | 4         | 0.04%   |
| openbox                  | 4         | 0.04%   |
| bspwm                    | 3         | 0.03%   |
| qtile                    | 2         | 0.02%   |
| xmonad                   | 1         | 0.01%   |
| Trinity                  | 1         | 0.01%   |
| jwm                      | 1         | 0.01%   |
| icewm                    | 1         | 0.01%   |
| 03WindowMaker            | 1         | 0.01%   |
| /usr/bin/openbox-session | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 9123      | 82.6%   |
| Wayland | 976       | 8.84%   |
| Unknown | 871       | 7.89%   |
| Tty     | 73        | 0.66%   |
| Web     | 2         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 7202      | 64.59%  |
| SDDM    | 1154      | 10.35%  |
| GDM     | 1139      | 10.22%  |
| TDM     | 538       | 4.83%   |
| GDM3    | 525       | 4.71%   |
| LightDM | 507       | 4.55%   |
| KDM     | 66        | 0.59%   |
| XDM     | 8         | 0.07%   |
| SLiM    | 5         | 0.04%   |
| LXDM    | 3         | 0.03%   |
| MDM     | 2         | 0.02%   |
| SLIMSKI | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| pt_BR       | 7215      | 65.4%   |
| en_US       | 1834      | 16.62%  |
| Unknown     | 1692      | 15.34%  |
| C           | 156       | 1.41%   |
| en_GB       | 45        | 0.41%   |
| pt_PT       | 39        | 0.35%   |
| es_ES       | 14        | 0.13%   |
| en_CA       | 6         | 0.05%   |
| de_DE       | 5         | 0.05%   |
| fr_FR       | 4         | 0.04%   |
| POSIX       | 3         | 0.03%   |
| ja_JP       | 2         | 0.02%   |
| it_IT       | 2         | 0.02%   |
| en_AG       | 2         | 0.02%   |
| ru_RU       | 1         | 0.01%   |
| pt_BRutf8   | 1         | 0.01%   |
| pt_BR.UTF8  | 1         | 0.01%   |
| es_MX       | 1         | 0.01%   |
| es_CL       | 1         | 0.01%   |
| es_AR       | 1         | 0.01%   |
| eo          | 1         | 0.01%   |
| en_US.utf-8 | 1         | 0.01%   |
| en_US.UFT-8 | 1         | 0.01%   |
| en_IN       | 1         | 0.01%   |
| em_US       | 1         | 0.01%   |
| C.UTF8      | 1         | 0.01%   |
| ar_EG       | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 6335      | 57.39%  |
| EFI  | 4704      | 42.61%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 8656      | 78.48%  |
| Overlay | 822       | 7.45%   |
| Unknown | 702       | 6.36%   |
| Btrfs   | 658       | 5.97%   |
| Xfs     | 77        | 0.7%    |
| Zfs     | 40        | 0.36%   |
| Tmpfs   | 23        | 0.21%   |
| Ext3    | 21        | 0.19%   |
| Ext2    | 17        | 0.15%   |
| F2fs    | 11        | 0.1%    |
| Aufs    | 3         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 7585      | 68.67%  |
| GPT     | 2258      | 20.44%  |
| MBR     | 1203      | 10.89%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 9704      | 88.68%  |
| Yes       | 1239      | 11.32%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 8114      | 73.99%  |
| Yes       | 2853      | 26.01%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 1743      | 16.16%  |
| ASUSTek Computer        | 1433      | 13.28%  |
| Acer                    | 1299      | 12.04%  |
| Lenovo                  | 907       | 8.41%   |
| Gigabyte Technology     | 707       | 6.55%   |
| Positivo                | 627       | 5.81%   |
| Hewlett-Packard         | 585       | 5.42%   |
| Samsung Electronics     | 558       | 5.17%   |
| Intel                   | 382       | 3.54%   |
| ASRock                  | 359       | 3.33%   |
| Unknown                 | 208       | 1.93%   |
| MSI                     | 190       | 1.76%   |
| Sony                    | 145       | 1.34%   |
| LG Electronics          | 115       | 1.07%   |
| Apple                   | 106       | 0.98%   |
| Semp Toshiba            | 103       | 0.95%   |
| PCWare                  | 101       | 0.94%   |
| Itautec                 | 100       | 0.93%   |
| Biostar                 | 80        | 0.74%   |
| Avell High Performance  | 66        | 0.61%   |
| Pegatron                | 64        | 0.59%   |
| Digibras                | 63        | 0.58%   |
| ECS                     | 58        | 0.54%   |
| OEM                     | 47        | 0.44%   |
| Philco                  | 45        | 0.42%   |
| Multilaser              | 41        | 0.38%   |
| Compaq                  | 34        | 0.32%   |
| Toshiba                 | 33        | 0.31%   |
| Positivo Bahia - VAIO   | 32        | 0.3%    |
| Megaware                | 29        | 0.27%   |
| Huanan                  | 27        | 0.25%   |
| Foxconn                 | 27        | 0.25%   |
| Notebook                | 24        | 0.22%   |
| Clevo                   | 21        | 0.19%   |
| Login Informatica       | 19        | 0.18%   |
| Gateway                 | 19        | 0.18%   |
| Compal                  | 18        | 0.17%   |
| Raspberry Pi Foundation | 17        | 0.16%   |
| Supermicro              | 15        | 0.14%   |
| Google                  | 15        | 0.14%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 263       | 2.44%   |
| ASUS All Series                             | 133       | 1.23%   |
| Acer Nitro AN515-54                         | 132       | 1.22%   |
| Positivo Mobile                             | 116       | 1.08%   |
| Acer Nitro AN515-44                         | 76        | 0.7%    |
| Acer Aspire A315-53                         | 67        | 0.62%   |
| Samsung 340XAA/350XAA/550XAA                | 65        | 0.6%    |
| Intel H61                                   | 65        | 0.6%    |
| Dell Inspiron 5566                          | 56        | 0.52%   |
| ASUS PRIME B450M-GAMING/BR                  | 56        | 0.52%   |
| Lenovo IdeaPad S145-15API 81V7              | 55        | 0.51%   |
| Dell Inspiron 3583                          | 54        | 0.5%    |
| Lenovo IdeaPad 330-15IKB 81FE               | 52        | 0.48%   |
| Acer Aspire A315-34                         | 52        | 0.48%   |
| Acer Nitro AN517-51                         | 50        | 0.46%   |
| Lenovo IdeaPad S145-15IWL 81S9              | 49        | 0.45%   |
| Dell Inspiron 15-3567                       | 48        | 0.44%   |
| ASRock A320M-HD                             | 47        | 0.44%   |
| ASUS PRIME A320M-K/BR                       | 46        | 0.43%   |
| Acer Nitro AN515-43                         | 45        | 0.42%   |
| Acer Aspire A515-51                         | 44        | 0.41%   |
| Semp Toshiba STI                            | 42        | 0.39%   |
| Intel H55                                   | 42        | 0.39%   |
| ASUS M5A78L-M LX/BR                         | 41        | 0.38%   |
| HP G42                                      | 39        | 0.36%   |
| Samsung 300E5M/300E5L                       | 37        | 0.34%   |
| Positivo S14CT01                            | 37        | 0.34%   |
| Itautec Infoway                             | 37        | 0.34%   |
| Lenovo IdeaPad 320-15IKB 80YH               | 36        | 0.33%   |
| Dell Inspiron 3442                          | 36        | 0.33%   |
| Acer Nitro AN515-52                         | 36        | 0.33%   |
| Dell Inspiron 3421                          | 35        | 0.32%   |
| Gigabyte H61M-S1                            | 34        | 0.32%   |
| Dell Inspiron 7520                          | 33        | 0.31%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 32        | 0.3%    |
| Gigabyte B75M-D3H                           | 32        | 0.3%    |
| Dell Inspiron N4050                         | 32        | 0.3%    |
| Gigabyte A320M-S2H                          | 31        | 0.29%   |
| Dell Inspiron 1545                          | 31        | 0.29%   |
| ASUS P8H61-M LX3 R2.0                       | 31        | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Dell Inspiron      | 1016      | 9.42%   |
| Acer Aspire        | 838       | 7.77%   |
| Lenovo IdeaPad     | 437       | 4.05%   |
| Acer Nitro         | 371       | 3.44%   |
| Unknown            | 263       | 2.44%   |
| Dell Vostro        | 214       | 1.98%   |
| ASUS PRIME         | 207       | 1.92%   |
| Lenovo ThinkPad    | 183       | 1.7%    |
| HP Pavilion        | 181       | 1.68%   |
| Dell Latitude      | 156       | 1.45%   |
| Dell OptiPlex      | 139       | 1.29%   |
| ASUS All           | 133       | 1.23%   |
| Positivo Mobile    | 116       | 1.08%   |
| ASUS M5A78L-M      | 110       | 1.02%   |
| Itautec Infoway    | 97        | 0.9%    |
| HP Compaq          | 89        | 0.82%   |
| ASUS TUF           | 87        | 0.81%   |
| ASUS VivoBook      | 82        | 0.76%   |
| ASUS P8H61-M       | 78        | 0.72%   |
| Intel H61          | 67        | 0.62%   |
| Samsung 340XAA     | 65        | 0.6%    |
| Lenovo ThinkCentre | 52        | 0.48%   |
| Semp Toshiba STI   | 49        | 0.45%   |
| Dell G3            | 49        | 0.45%   |
| ASUS ROG           | 49        | 0.45%   |
| Dell XPS           | 48        | 0.44%   |
| ASRock A320M-HD    | 48        | 0.44%   |
| Samsung RV411      | 45        | 0.42%   |
| HP ProBook         | 45        | 0.42%   |
| Intel H55          | 42        | 0.39%   |
| HP G42             | 39        | 0.36%   |
| Samsung 300E5M     | 37        | 0.34%   |
| Positivo S14CT01   | 37        | 0.34%   |
| Dell System        | 36        | 0.33%   |
| HP EliteBook       | 34        | 0.32%   |
| Gigabyte H61M-S1   | 34        | 0.32%   |
| Gigabyte B75M-D3H  | 32        | 0.3%    |
| Gigabyte B450M     | 31        | 0.29%   |
| Gigabyte A320M-S2H | 31        | 0.29%   |
| Semp Toshiba IS    | 30        | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 1154      | 10.7%   |
| 2012    | 1127      | 10.45%  |
| 2011    | 1041      | 9.65%   |
| 2018    | 1023      | 9.48%   |
| 2017    | 864       | 8.01%   |
| 2013    | 852       | 7.9%    |
| 2010    | 724       | 6.71%   |
| 2016    | 683       | 6.33%   |
| 2014    | 655       | 6.07%   |
| 2020    | 532       | 4.93%   |
| 2009    | 472       | 4.37%   |
| 2008    | 460       | 4.26%   |
| 2015    | 423       | 3.92%   |
| 2021    | 300       | 2.78%   |
| 2007    | 274       | 2.54%   |
| 2006    | 95        | 0.88%   |
| Unknown | 43        | 0.4%    |
| 2022    | 31        | 0.29%   |
| 2005    | 26        | 0.24%   |
| 2004    | 9         | 0.08%   |
| 2003    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 6450      | 59.78%  |
| Desktop        | 4070      | 37.72%  |
| All in one     | 84        | 0.78%   |
| Convertible    | 70        | 0.65%   |
| Mini pc        | 38        | 0.35%   |
| Server         | 32        | 0.3%    |
| System on chip | 25        | 0.23%   |
| Tablet         | 19        | 0.18%   |
| Firewall       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 9734      | 89.66%  |
| Enabled  | 1122      | 10.34%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 10772     | 99.84%  |
| Yes  | 17        | 0.16%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 2953      | 26.92%  |
| 3.01-4.0        | 2944      | 26.84%  |
| 8.01-16.0       | 1917      | 17.48%  |
| 16.01-24.0      | 1612      | 14.7%   |
| 1.01-2.0        | 764       | 6.97%   |
| 32.01-64.0      | 311       | 2.84%   |
| 2.01-3.0        | 245       | 2.23%   |
| 24.01-32.0      | 83        | 0.76%   |
| 64.01-256.0     | 72        | 0.66%   |
| 0.51-1.0        | 58        | 0.53%   |
| More than 256.0 | 6         | 0.05%   |
| 0.01-0.5        | 2         | 0.02%   |
| Unknown         | 2         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 4508      | 37.9%   |
| 2.01-3.0    | 3191      | 26.83%  |
| 3.01-4.0    | 1491      | 12.53%  |
| 4.01-8.0    | 1359      | 11.42%  |
| 0.51-1.0    | 933       | 7.84%   |
| 8.01-16.0   | 261       | 2.19%   |
| 0.01-0.5    | 114       | 0.96%   |
| 16.01-24.0  | 23        | 0.19%   |
| 24.01-32.0  | 5         | 0.04%   |
| Unknown     | 5         | 0.04%   |
| 32.01-64.0  | 3         | 0.03%   |
| 64.01-256.0 | 2         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 6905      | 62.45%  |
| 2       | 3016      | 27.28%  |
| 3       | 647       | 5.85%   |
| 4       | 242       | 2.19%   |
| 0       | 103       | 0.93%   |
| 5       | 74        | 0.67%   |
| 6       | 45        | 0.41%   |
| 7       | 10        | 0.09%   |
| 8       | 6         | 0.05%   |
| 9       | 5         | 0.05%   |
| 18      | 1         | 0.01%   |
| 15      | 1         | 0.01%   |
| 10      | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 6609      | 60.8%   |
| Yes       | 4261      | 39.2%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 9958      | 92.16%  |
| No        | 847       | 7.84%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 7898      | 72.71%  |
| No        | 2964      | 27.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 5481      | 50.34%  |
| Yes       | 5408      | 49.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Brazil  | 10789     | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Sao Paulo            | 1424      | 12.63%  |
| Rio de Janeiro       | 648       | 5.75%   |
| Brasília            | 351       | 3.11%   |
| Belo Horizonte       | 315       | 2.79%   |
| Curitiba             | 306       | 2.71%   |
| Porto Alegre         | 245       | 2.17%   |
| Fortaleza            | 237       | 2.1%    |
| Salvador             | 168       | 1.49%   |
| Campinas             | 159       | 1.41%   |
| Recife               | 149       | 1.32%   |
| Goiânia             | 129       | 1.14%   |
| Santo André         | 120       | 1.06%   |
| Florianópolis       | 120       | 1.06%   |
| Natal                | 97        | 0.86%   |
| Manaus               | 89        | 0.79%   |
| Campo Grande         | 86        | 0.76%   |
| Osasco               | 85        | 0.75%   |
| Guarulhos            | 84        | 0.74%   |
| Niterói             | 83        | 0.74%   |
| Sao José dos Campos | 82        | 0.73%   |
| Sao Luís            | 76        | 0.67%   |
| Maringá             | 75        | 0.67%   |
| Belém               | 73        | 0.65%   |
| Sorocaba             | 71        | 0.63%   |
| Joinville            | 70        | 0.62%   |
| Teresina             | 67        | 0.59%   |
| Londrina             | 62        | 0.55%   |
| Joao Pessoa          | 62        | 0.55%   |
| Ribeirao Preto       | 60        | 0.53%   |
| Uberlândia          | 57        | 0.51%   |
| Juiz de Fora         | 57        | 0.51%   |
| Aracaju              | 57        | 0.51%   |
| Maceió              | 56        | 0.5%    |
| Serra                | 53        | 0.47%   |
| Sao Jose             | 53        | 0.47%   |
| Duque de Caxias      | 50        | 0.44%   |
| Vitória             | 49        | 0.43%   |
| Cuiabá              | 49        | 0.43%   |
| Sao Carlos           | 48        | 0.43%   |
| Canoas               | 47        | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 3106      | 3957   | 20.97%  |
| Seagate                        | 2954      | 4133   | 19.94%  |
| Samsung Electronics            | 1501      | 2057   | 10.13%  |
| Kingston                       | 1496      | 1916   | 10.1%   |
| Toshiba                        | 887       | 1038   | 5.99%   |
| SanDisk                        | 767       | 1028   | 5.18%   |
| Unknown                        | 446       | 609    | 3.01%   |
| A-DATA Technology              | 395       | 494    | 2.67%   |
| Hitachi                        | 363       | 443    | 2.45%   |
| Intel                          | 293       | 353    | 1.98%   |
| China                          | 284       | 335    | 1.92%   |
| Crucial                        | 261       | 336    | 1.76%   |
| Silicon Motion                 | 144       | 182    | 0.97%   |
| ADATA Technology               | 129       | 157    | 0.87%   |
| HGST                           | 127       | 151    | 0.86%   |
| SK hynix                       | 117       | 156    | 0.79%   |
| LITEON                         | 117       | 136    | 0.79%   |
| Maxtor                         | 115       | 134    | 0.78%   |
| KingSpec                       | 86        | 100    | 0.58%   |
| Lexar                          | 82        | 96     | 0.55%   |
| Phison                         | 63        | 84     | 0.43%   |
| Realtek Semiconductor          | 58        | 72     | 0.39%   |
| Corsair                        | 58        | 69     | 0.39%   |
| JMicron Technology             | 56        | 65     | 0.38%   |
| XPG                            | 54        | 67     | 0.36%   |
| Fujitsu                        | 52        | 60     | 0.35%   |
| PNY                            | 39        | 47     | 0.26%   |
| Netac                          | 38        | 48     | 0.26%   |
| Hewlett-Packard                | 38        | 46     | 0.26%   |
| Apple                          | 36        | 52     | 0.24%   |
| Patriot                        | 33        | 45     | 0.22%   |
| Solid State Storage Technology | 31        | 40     | 0.21%   |
| Gigabyte Technology            | 30        | 42     | 0.2%    |
| SSSTC                          | 29        | 30     | 0.2%    |
| Unknown                        | 28        | 28     | 0.19%   |
| Smart                          | 26        | 30     | 0.18%   |
| KingDian                       | 26        | 33     | 0.18%   |
| KIOXIA                         | 25        | 29     | 0.17%   |
| XrayDisk                       | 21        | 27     | 0.14%   |
| Solid State Storage            | 19        | 20     | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD     | 513       | 3.25%   |
| WDC WD10SPZX-21Z10T0 1TB            | 460       | 2.91%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 291       | 1.84%   |
| Kingston SA400S37120G 120GB SSD     | 275       | 1.74%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 267       | 1.69%   |
| Kingston SA400S37480G 480GB SSD     | 242       | 1.53%   |
| Seagate ST500DM002-1BD142 500GB     | 235       | 1.49%   |
| Seagate ST1000DM010-2EP102 1TB      | 186       | 1.18%   |
| Toshiba MQ01ABD100 1TB              | 143       | 0.9%    |
| Kingston SV300S37A120G 120GB SSD    | 132       | 0.84%   |
| Unknown MMC Card  32GB              | 130       | 0.82%   |
| SanDisk SSD PLUS 240GB              | 130       | 0.82%   |
| WDC WD10SPZX-24Z10 1TB              | 125       | 0.79%   |
| Samsung HD322HJ 320GB               | 114       | 0.72%   |
| Seagate Expansion 1TB               | 109       | 0.69%   |
| Seagate ST1000LM035-1RK172 1TB      | 107       | 0.68%   |
| WDC WD10JPVX-22JC3T0 1TB            | 103       | 0.65%   |
| Intel NVMe SSD Drive 512GB          | 103       | 0.65%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 98        | 0.62%   |
| Samsung HM321HI 320GB               | 96        | 0.61%   |
| Samsung HD161HJ 160GB               | 95        | 0.6%    |
| SanDisk SSD PLUS 120GB              | 94        | 0.59%   |
| Samsung HD502HJ 500GB               | 92        | 0.58%   |
| Seagate ST1000DM003-1ER162 1TB      | 91        | 0.58%   |
| Samsung HD502HI 500GB               | 91        | 0.58%   |
| A-DATA IM2S3338-128GD2 128GB SSD    | 88        | 0.56%   |
| Seagate ST1000DM003-1CH162 1TB      | 85        | 0.54%   |
| Seagate ST9500325AS 500GB           | 84        | 0.53%   |
| Crucial CT240BX500SSD1 240GB        | 84        | 0.53%   |
| WDC WD10SPZX-75Z10T2 1TB            | 78        | 0.49%   |
| SanDisk SDSSDA240G 240GB            | 76        | 0.48%   |
| Toshiba MQ01ABF050 500GB            | 75        | 0.47%   |
| WDC WD5000AAKX-003CA0 500GB         | 73        | 0.46%   |
| Intel SSDPEKKW256G7 256GB           | 71        | 0.45%   |
| Toshiba MQ04ABF100 1TB              | 69        | 0.44%   |
| SanDisk NVMe SSD Drive 512GB        | 69        | 0.44%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 68        | 0.43%   |
| ADATA NVMe SSD Drive 256GB          | 68        | 0.43%   |
| Seagate ST3500418AS 500GB           | 67        | 0.42%   |
| WDC WD10EARS-00Y5B1 1TB             | 65        | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2942      | 4104   | 35.23%  |
| WDC                 | 2785      | 3464   | 33.35%  |
| Samsung Electronics | 1044      | 1358   | 12.5%   |
| Toshiba             | 843       | 985    | 10.09%  |
| Hitachi             | 363       | 443    | 4.35%   |
| HGST                | 127       | 151    | 1.52%   |
| Maxtor              | 106       | 124    | 1.27%   |
| Fujitsu             | 51        | 58     | 0.61%   |
| Unknown             | 28        | 31     | 0.34%   |
| Apple               | 16        | 27     | 0.19%   |
| Hewlett-Packard     | 13        | 15     | 0.16%   |
| ExcelStor           | 9         | 10     | 0.11%   |
| SAGE                | 5         | 8      | 0.06%   |
| JMicron Technology  | 5         | 6      | 0.06%   |
| ASMT                | 3         | 3      | 0.04%   |
| USB3.0              | 1         | 1      | 0.01%   |
| MDT                 | 1         | 1      | 0.01%   |
| Maxtor 6            | 1         | 1      | 0.01%   |
| Lenovo              | 1         | 1      | 0.01%   |
| Intenso             | 1         | 1      | 0.01%   |
| Initio              | 1         | 1      | 0.01%   |
| IBM/Hitachi         | 1         | 2      | 0.01%   |
| IBM                 | 1         | 3      | 0.01%   |
| FEASSO              | 1         | 2      | 0.01%   |
| CLOVER              | 1         | 1      | 0.01%   |
| China               | 1         | 1      | 0.01%   |
| Unknown             | 1         | 1      | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 1451      | 1843   | 32.95%  |
| SanDisk             | 586       | 814    | 13.31%  |
| WDC                 | 328       | 402    | 7.45%   |
| Samsung Electronics | 315       | 474    | 7.15%   |
| China               | 283       | 334    | 6.43%   |
| A-DATA Technology   | 251       | 302    | 5.7%    |
| Crucial             | 249       | 320    | 5.66%   |
| LITEON              | 103       | 121    | 2.34%   |
| KingSpec            | 85        | 99     | 1.93%   |
| Lexar               | 81        | 95     | 1.84%   |
| Intel               | 48        | 60     | 1.09%   |
| Corsair             | 46        | 54     | 1.04%   |
| JMicron Technology  | 45        | 53     | 1.02%   |
| PNY                 | 37        | 45     | 0.84%   |
| Netac               | 32        | 41     | 0.73%   |
| Patriot             | 31        | 42     | 0.7%    |
| Smart               | 26        | 30     | 0.59%   |
| KingDian            | 25        | 32     | 0.57%   |
| Gigabyte Technology | 25        | 36     | 0.57%   |
| Unknown             | 22        | 24     | 0.5%    |
| Apple               | 20        | 23     | 0.45%   |
| SK hynix            | 19        | 23     | 0.43%   |
| Hewlett-Packard     | 18        | 22     | 0.41%   |
| Unknown             | 18        | 18     | 0.41%   |
| Toshiba             | 15        | 18     | 0.34%   |
| Seagate             | 14        | 17     | 0.32%   |
| OCZ                 | 14        | 14     | 0.32%   |
| LITEONIT            | 13        | 19     | 0.3%    |
| BHT                 | 12        | 16     | 0.27%   |
| Micron Technology   | 10        | 12     | 0.23%   |
| Maxtor              | 9         | 10     | 0.2%    |
| XrayDisk            | 7         | 8      | 0.16%   |
| Team                | 7         | 15     | 0.16%   |
| RZX                 | 7         | 10     | 0.16%   |
| Plextor             | 7         | 8      | 0.16%   |
| S3+                 | 6         | 6      | 0.14%   |
| HUSKY               | 6         | 6      | 0.14%   |
| BIWIN               | 6         | 6      | 0.14%   |
| Win Memory          | 5         | 6      | 0.11%   |
| walram              | 5         | 5      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 7430      | 10803  | 55.09%  |
| SSD     | 3993      | 5623   | 29.6%   |
| NVMe    | 1606      | 2140   | 11.91%  |
| MMC     | 339       | 487    | 2.51%   |
| Unknown | 120       | 157    | 0.89%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 9593      | 16145  | 80.89%  |
| NVMe | 1603      | 2136   | 13.52%  |
| MMC  | 339       | 487    | 2.86%   |
| SAS  | 324       | 442    | 2.73%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 7259      | 10769  | 63.54%  |
| 0.51-1.0   | 3558      | 4746   | 31.14%  |
| 1.01-2.0   | 420       | 589    | 3.68%   |
| 3.01-4.0   | 70        | 150    | 0.61%   |
| 2.01-3.0   | 66        | 96     | 0.58%   |
| 4.01-10.0  | 47        | 70     | 0.41%   |
| 10.01-20.0 | 4         | 6      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 3175      | 27.91%  |
| 251-500        | 2763      | 24.29%  |
| 501-1000       | 1904      | 16.74%  |
| 1-20           | 830       | 7.3%    |
| 1001-2000      | 795       | 6.99%   |
| 51-100         | 748       | 6.58%   |
| 21-50          | 540       | 4.75%   |
| 2001-3000      | 227       | 2%      |
| Unknown        | 202       | 1.78%   |
| More than 3000 | 192       | 1.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 4538      | 38.59%  |
| 21-50          | 2507      | 21.32%  |
| 101-250        | 1451      | 12.34%  |
| 51-100         | 1421      | 12.08%  |
| 251-500        | 774       | 6.58%   |
| 501-1000       | 527       | 4.48%   |
| 1001-2000      | 229       | 1.95%   |
| Unknown        | 202       | 1.72%   |
| 2001-3000      | 60        | 0.51%   |
| More than 3000 | 51        | 0.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 41        | 44     | 3.68%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 36        | 39     | 3.23%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 26        | 28     | 2.33%   |
| WDC WD5000AAKX-003CA0 500GB         | 24        | 24     | 2.15%   |
| Seagate ST9500325AS 500GB           | 22        | 24     | 1.97%   |
| Samsung Electronics HD322HJ 320GB   | 20        | 23     | 1.79%   |
| Samsung Electronics HD161HJ 160GB   | 17        | 18     | 1.52%   |
| Samsung Electronics HD502HI 500GB   | 16        | 18     | 1.43%   |
| Samsung Electronics HD502HJ 500GB   | 14        | 14     | 1.26%   |
| Toshiba MQ01ABD100 1TB              | 12        | 12     | 1.08%   |
| Seagate ST1000LM035-1RK172 1TB      | 12        | 12     | 1.08%   |
| WDC WD10EARS-00Y5B1 1TB             | 11        | 13     | 0.99%   |
| Toshiba MQ01ABD050 500GB            | 11        | 11     | 0.99%   |
| Kingston SV300S37A120G 120GB SSD    | 11        | 12     | 0.99%   |
| Seagate ST9320325AS 320GB           | 10        | 10     | 0.9%    |
| Seagate ST3500418AS 500GB           | 10        | 14     | 0.9%    |
| WDC WD3200AAJS-00L7A0 320GB         | 9         | 9      | 0.81%   |
| Seagate ST500LT012-9WS142 500GB     | 9         | 11     | 0.81%   |
| Samsung Electronics HD080HJ/ 80GB   | 9         | 11     | 0.81%   |
| Maxtor STM3160215AS 160GB           | 9         | 10     | 0.81%   |
| Seagate ST3320418AS 320GB           | 8         | 12     | 0.72%   |
| Seagate ST1000DM010-2EP102 1TB      | 8         | 11     | 0.72%   |
| Samsung Electronics HM321HI 320GB   | 8         | 8      | 0.72%   |
| Samsung Electronics HD103SJ 1TB     | 8         | 10     | 0.72%   |
| Kingston SA400S37240G 240GB SSD     | 8         | 8      | 0.72%   |
| Kingston SA400S37120G 120GB SSD     | 8         | 12     | 0.72%   |
| Toshiba MQ02ABD100H 1TB             | 7         | 10     | 0.63%   |
| Toshiba MQ01ABF050 500GB            | 7         | 7      | 0.63%   |
| Seagate ST500LT012-1DG142 500GB     | 7         | 8      | 0.63%   |
| Seagate ST1500DL003-9VT16L 1TB      | 7         | 7      | 0.63%   |
| Seagate ST1000DM003-1CH162 1TB      | 7         | 9      | 0.63%   |
| Samsung Electronics HD250HJ 250GB   | 7         | 8      | 0.63%   |
| Kingston SA400S37480G 480GB SSD     | 7         | 8      | 0.63%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 6         | 7      | 0.54%   |
| Toshiba MQ01ABD032 320GB            | 6         | 7      | 0.54%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 6         | 7      | 0.54%   |
| Seagate ST2000DM001-1CH164 2TB      | 6         | 7      | 0.54%   |
| Seagate ST1000DM003-9YN162 1TB      | 6         | 6      | 0.54%   |
| Samsung Electronics HM160HI 160GB   | 6         | 6      | 0.54%   |
| Hitachi HTS547550A9E384 500GB       | 6         | 6      | 0.54%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 355       | 421    | 33.33%  |
| WDC                 | 238       | 270    | 22.35%  |
| Samsung Electronics | 160       | 198    | 15.02%  |
| Toshiba             | 95        | 103    | 8.92%   |
| Hitachi             | 59        | 62     | 5.54%   |
| Kingston            | 43        | 51     | 4.04%   |
| Maxtor              | 18        | 19     | 1.69%   |
| SanDisk             | 17        | 17     | 1.6%    |
| China               | 14        | 15     | 1.31%   |
| A-DATA Technology   | 9         | 9      | 0.85%   |
| HGST                | 7         | 7      | 0.66%   |
| Intel               | 6         | 6      | 0.56%   |
| Fujitsu             | 5         | 6      | 0.47%   |
| XPG                 | 4         | 4      | 0.38%   |
| PNY                 | 4         | 6      | 0.38%   |
| Crucial             | 4         | 4      | 0.38%   |
| OCZ                 | 3         | 3      | 0.28%   |
| Apple               | 3         | 3      | 0.28%   |
| WALRAM              | 2         | 2      | 0.19%   |
| LITEON              | 2         | 2      | 0.19%   |
| Corsair             | 2         | 2      | 0.19%   |
| SK hynix            | 1         | 1      | 0.09%   |
| ShiJi               | 1         | 1      | 0.09%   |
| QIANGHE             | 1         | 1      | 0.09%   |
| Plextor             | 1         | 1      | 0.09%   |
| OCZ-VERTEX3         | 1         | 1      | 0.09%   |
| Netac               | 1         | 1      | 0.09%   |
| Mushkin             | 1         | 1      | 0.09%   |
| Micron Technology   | 1         | 1      | 0.09%   |
| LITEONIT            | 1         | 2      | 0.09%   |
| Initio              | 1         | 1      | 0.09%   |
| Hewlett-Packard     | 1         | 1      | 0.09%   |
| FEASSO              | 1         | 2      | 0.09%   |
| ExcelStor           | 1         | 2      | 0.09%   |
| EGON                | 1         | 1      | 0.09%   |
| Unknown             | 1         | 1      | 0.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 355       | 421    | 38.34%  |
| WDC                 | 226       | 258    | 24.41%  |
| Samsung Electronics | 156       | 194    | 16.85%  |
| Toshiba             | 94        | 102    | 10.15%  |
| Hitachi             | 59        | 62     | 6.37%   |
| Maxtor              | 18        | 19     | 1.94%   |
| HGST                | 7         | 7      | 0.76%   |
| Fujitsu             | 5         | 6      | 0.54%   |
| Apple               | 2         | 2      | 0.22%   |
| Initio              | 1         | 1      | 0.11%   |
| Hewlett-Packard     | 1         | 1      | 0.11%   |
| FEASSO              | 1         | 2      | 0.11%   |
| ExcelStor           | 1         | 2      | 0.11%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 850       | 1077   | 86.03%  |
| SSD  | 123       | 136    | 12.45%  |
| NVMe | 15        | 15     | 1.52%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                  | 2         | 2      | 8.33%   |
| Samsung Electronics HM321HI 320GB                | 2         | 2      | 8.33%   |
| WDC WD1600BEVT-22ZCT0 160GB                      | 1         | 1      | 4.17%   |
| WDC WD10SPZX-75Z10T1 1TB                         | 1         | 1      | 4.17%   |
| WDC WD10SPZX-22Z10T0 1TB                         | 1         | 1      | 4.17%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 4.17%   |
| Toshiba MK5065GSXN 500GB                         | 1         | 1      | 4.17%   |
| Toshiba DT01ACA100 1TB                           | 1         | 1      | 4.17%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 4.17%   |
| Seagate ST3320613AS 320GB                        | 1         | 1      | 4.17%   |
| Seagate ST31000528AS 1TB                         | 1         | 1      | 4.17%   |
| Seagate ST31000340NS 1TB                         | 1         | 1      | 4.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 4.17%   |
| Samsung Electronics MZNTY128HDHP-000H1 128GB SSD | 1         | 1      | 4.17%   |
| Samsung Electronics HM320JI 320GB                | 1         | 1      | 4.17%   |
| Samsung Electronics HM250HI 250GB                | 1         | 1      | 4.17%   |
| Samsung Electronics HD502HJ 500GB                | 1         | 3      | 4.17%   |
| Samsung Electronics HD322GJ 320GB                | 1         | 1      | 4.17%   |
| Samsung Electronics HD103SJ 1TB                  | 1         | 1      | 4.17%   |
| Samsung Electronics HD080HJ/ 80GB                | 1         | 1      | 4.17%   |
| Maxtor STM380215AS 80GB                          | 1         | 1      | 4.17%   |
| Hitachi HDS721050DLE630 500GB                    | 1         | 1      | 4.17%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 11     | 37.5%   |
| Seagate             | 7         | 7      | 29.17%  |
| WDC                 | 3         | 3      | 12.5%   |
| Toshiba             | 3         | 3      | 12.5%   |
| Maxtor              | 1         | 1      | 4.17%   |
| Hitachi             | 1         | 1      | 4.17%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 7778      | 13671  | 67.97%  |
| Works    | 2682      | 4285   | 23.44%  |
| Malfunc  | 960       | 1228   | 8.39%   |
| Failed   | 24        | 26     | 0.21%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 8277      | 68.31%  |
| AMD                              | 1710      | 14.11%  |
| ADATA Technology                 | 301       | 2.48%   |
| Nvidia                           | 244       | 2.01%   |
| SanDisk                          | 225       | 1.86%   |
| Samsung Electronics              | 188       | 1.55%   |
| Silicon Motion                   | 164       | 1.35%   |
| Silicon Integrated Systems [SiS] | 102       | 0.84%   |
| SK hynix                         | 92        | 0.76%   |
| Solid State Storage Technology   | 91        | 0.75%   |
| Realtek Semiconductor            | 91        | 0.75%   |
| Phison Electronics               | 88        | 0.73%   |
| Marvell Technology Group         | 79        | 0.65%   |
| JMicron Technology               | 77        | 0.64%   |
| VIA Technologies                 | 71        | 0.59%   |
| ASMedia Technology               | 61        | 0.5%    |
| Kingston Technology Company      | 56        | 0.46%   |
| Micron/Crucial Technology        | 31        | 0.26%   |
| Lite-On Technology               | 26        | 0.21%   |
| KIOXIA                           | 25        | 0.21%   |
| Toshiba America Info Systems     | 23        | 0.19%   |
| LSI Logic / Symbios Logic        | 20        | 0.17%   |
| Broadcom / LSI                   | 12        | 0.1%    |
| Micron Technology                | 8         | 0.07%   |
| Union Memory (Shenzhen)          | 6         | 0.05%   |
| Silicon Image                    | 6         | 0.05%   |
| MAXIO Technology (Hangzhou)      | 6         | 0.05%   |
| Seagate Technology               | 5         | 0.04%   |
| Shenzhen Longsys Electronics     | 4         | 0.03%   |
| OCZ Technology Group             | 4         | 0.03%   |
| Beijing Starblaze Technology     | 4         | 0.03%   |
| Adaptec                          | 4         | 0.03%   |
| Hewlett-Packard                  | 3         | 0.02%   |
| Netac Technology                 | 2         | 0.02%   |
| Lenovo                           | 2         | 0.02%   |
| Dell                             | 2         | 0.02%   |
| Apple                            | 2         | 0.02%   |
| ULi Electronics                  | 1         | 0.01%   |
| Promise Technology               | 1         | 0.01%   |
| INNOGRIT                         | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 1033      | 6.93%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 922       | 6.19%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 788       | 5.29%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 593       | 3.98%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 556       | 3.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 437       | 2.93%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 433       | 2.91%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 376       | 2.52%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 363       | 2.44%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 350       | 2.35%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 298       | 2%      |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 297       | 1.99%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 295       | 1.98%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 277       | 1.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 232       | 1.56%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 227       | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 227       | 1.52%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 226       | 1.52%   |
| AMD FCH SATA Controller D                                                               | 203       | 1.36%   |
| Intel PROSet/Wireless WiFi Software extension                                           | 200       | 1.34%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 200       | 1.34%   |
| AMD 400 Series Chipset SATA Controller                                                  | 198       | 1.33%   |
| Nvidia MCP61 SATA Controller                                                            | 172       | 1.15%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 156       | 1.05%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 150       | 1.01%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 148       | 0.99%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 147       | 0.99%   |
| Nvidia MCP61 IDE                                                                        | 141       | 0.95%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 138       | 0.93%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 135       | 0.91%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 135       | 0.91%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 131       | 0.88%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 130       | 0.87%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 125       | 0.84%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 120       | 0.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 119       | 0.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 117       | 0.79%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 115       | 0.77%   |
| ADATA Non-Volatile memory controller                                                    | 115       | 0.77%   |
| ADATA IM2P33F8ABR1 NVMe SSD                                                             | 111       | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 8132      | 63.76%  |
| IDE  | 2225      | 17.45%  |
| NVMe | 1615      | 12.66%  |
| RAID | 761       | 5.97%   |
| SCSI | 14        | 0.11%   |
| SAS  | 7         | 0.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 8806      | 81.62%  |
| AMD          | 1951      | 18.08%  |
| ARM          | 26        | 0.24%   |
| CentaurHauls | 5         | 0.05%   |
| Unknown      | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 233       | 2.15%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 158       | 1.46%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 138       | 1.28%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 137       | 1.27%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 128       | 1.18%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 121       | 1.12%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 120       | 1.11%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 113       | 1.04%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 111       | 1.03%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 109       | 1.01%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 105       | 0.97%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 89        | 0.82%   |
| AMD FX-6300 Six-Core Processor                | 88        | 0.81%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 86        | 0.8%    |
| Intel Core i5-2450M CPU @ 2.50GHz             | 86        | 0.8%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 82        | 0.76%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 82        | 0.76%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 81        | 0.75%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 78        | 0.72%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 78        | 0.72%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 75        | 0.69%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 75        | 0.69%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 74        | 0.68%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 74        | 0.68%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 72        | 0.67%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 71        | 0.66%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 71        | 0.66%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 71        | 0.66%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 68        | 0.63%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 67        | 0.62%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 62        | 0.57%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 61        | 0.56%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 60        | 0.55%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 60        | 0.55%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 60        | 0.55%   |
| Intel Celeron CPU 847 @ 1.10GHz               | 60        | 0.55%   |
| Intel Core i5-3330 CPU @ 3.00GHz              | 58        | 0.54%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 58        | 0.54%   |
| Intel Core i5 CPU 650 @ 3.20GHz               | 57        | 0.53%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 56        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 2661      | 24.62%  |
| Intel Core i7           | 1754      | 16.23%  |
| Intel Core i3           | 1508      | 13.95%  |
| Intel Celeron           | 737       | 6.82%   |
| Intel Core 2 Duo        | 483       | 4.47%   |
| AMD Ryzen 5             | 459       | 4.25%   |
| Intel Pentium Dual-Core | 302       | 2.79%   |
| Intel Atom              | 276       | 2.55%   |
| AMD Ryzen 7             | 273       | 2.53%   |
| Intel Pentium           | 256       | 2.37%   |
| AMD FX                  | 242       | 2.24%   |
| Other                   | 212       | 1.96%   |
| Intel Xeon              | 203       | 1.88%   |
| Intel Pentium Dual      | 142       | 1.31%   |
| AMD Ryzen 3             | 97        | 0.9%    |
| Intel Core 2 Quad       | 93        | 0.86%   |
| AMD Phenom II X4        | 71        | 0.66%   |
| AMD Athlon II X2        | 66        | 0.61%   |
| AMD A4                  | 58        | 0.54%   |
| AMD A10                 | 56        | 0.52%   |
| AMD E                   | 53        | 0.49%   |
| Intel Core 2            | 51        | 0.47%   |
| AMD A6                  | 46        | 0.43%   |
| AMD Athlon 64 X2        | 45        | 0.42%   |
| AMD A8                  | 43        | 0.4%    |
| Intel Genuine           | 41        | 0.38%   |
| AMD C-60                | 41        | 0.38%   |
| AMD Athlon              | 38        | 0.35%   |
| AMD Ryzen 9             | 33        | 0.31%   |
| AMD E1                  | 33        | 0.31%   |
| AMD Sempron             | 31        | 0.29%   |
| Intel Pentium 4         | 29        | 0.27%   |
| AMD Phenom II X6        | 26        | 0.24%   |
| AMD C-70                | 24        | 0.22%   |
| Intel Pentium Gold      | 21        | 0.19%   |
| Intel Core i9           | 20        | 0.19%   |
| AMD Athlon II X4        | 18        | 0.17%   |
| AMD Phenom II X2        | 17        | 0.16%   |
| AMD C-50                | 17        | 0.16%   |
| Intel Celeron Dual-Core | 15        | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 5866      | 54.26%  |
| 4       | 3387      | 31.33%  |
| 6       | 684       | 6.33%   |
| 8       | 319       | 2.95%   |
| 1       | 318       | 2.94%   |
| 3       | 129       | 1.19%   |
| 12      | 40        | 0.37%   |
| 16      | 17        | 0.16%   |
| 10      | 16        | 0.15%   |
| Unknown | 15        | 0.14%   |
| 20      | 6         | 0.06%   |
| 14      | 6         | 0.06%   |
| 24      | 3         | 0.03%   |
| 5       | 2         | 0.02%   |
| 32      | 1         | 0.01%   |
| 28      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 10750     | 99.63%  |
| 2       | 37        | 0.34%   |
| Unknown | 2         | 0.02%   |
| 4       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 6935      | 64.22%  |
| 1       | 3848      | 35.63%  |
| Unknown | 15        | 0.14%   |
| 8       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 10203     | 94%     |
| Unknown        | 542       | 4.99%   |
| 32-bit         | 61        | 0.56%   |
| 64-bit         | 48        | 0.44%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2019      | 18.11%  |
| 0x306a9    | 941       | 8.44%   |
| 0x206a7    | 913       | 8.19%   |
| 0x1067a    | 601       | 5.39%   |
| 0x906ea    | 390       | 3.5%    |
| 0x806e9    | 376       | 3.37%   |
| 0x20655    | 351       | 3.15%   |
| 0x306c3    | 347       | 3.11%   |
| 0x40651    | 325       | 2.92%   |
| 0x806ec    | 309       | 2.77%   |
| 0x406e3    | 266       | 2.39%   |
| 0x306d4    | 266       | 2.39%   |
| 0x806ea    | 244       | 2.19%   |
| 0x6fd      | 237       | 2.13%   |
| 0x906e9    | 206       | 1.85%   |
| 0x406c4    | 161       | 1.44%   |
| 0x06000852 | 147       | 1.32%   |
| 0x08108109 | 130       | 1.17%   |
| 0x806c1    | 129       | 1.16%   |
| 0x30678    | 124       | 1.11%   |
| 0x010000c8 | 124       | 1.11%   |
| 0x05000119 | 93        | 0.83%   |
| 0x20652    | 90        | 0.81%   |
| 0x906ed    | 84        | 0.75%   |
| 0x08600103 | 78        | 0.7%    |
| 0x10676    | 76        | 0.68%   |
| 0x0800820d | 76        | 0.68%   |
| 0x08108102 | 74        | 0.66%   |
| 0x706a1    | 71        | 0.64%   |
| 0x506e3    | 70        | 0.63%   |
| 0x08701021 | 69        | 0.62%   |
| 0x6fb      | 65        | 0.58%   |
| 0x706e5    | 64        | 0.57%   |
| 0x106ca    | 59        | 0.53%   |
| 0x806eb    | 53        | 0.48%   |
| 0x406c3    | 52        | 0.47%   |
| 0x08701013 | 52        | 0.47%   |
| 0x10661    | 49        | 0.44%   |
| 0x706a8    | 47        | 0.42%   |
| 0x0810100b | 46        | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 2005      | 18.57%  |
| IvyBridge        | 1144      | 10.59%  |
| SandyBridge      | 1080      | 10%     |
| Haswell          | 842       | 7.8%    |
| Penryn           | 783       | 7.25%   |
| Westmere         | 523       | 4.84%   |
| Core             | 453       | 4.19%   |
| Silvermont       | 417       | 3.86%   |
| Skylake          | 404       | 3.74%   |
| Zen+             | 360       | 3.33%   |
| Broadwell        | 318       | 2.94%   |
| K10              | 281       | 2.6%    |
| Piledriver       | 260       | 2.41%   |
| Zen 2            | 242       | 2.24%   |
| Zen              | 207       | 1.92%   |
| TigerLake        | 161       | 1.49%   |
| Bobcat           | 159       | 1.47%   |
| Goldmont plus    | 133       | 1.23%   |
| CometLake        | 125       | 1.16%   |
| Bonnell          | 118       | 1.09%   |
| K8 Hammer        | 101       | 0.94%   |
| IceLake          | 91        | 0.84%   |
| Unknown          | 77        | 0.71%   |
| Nehalem          | 71        | 0.66%   |
| Excavator        | 71        | 0.66%   |
| Zen 3            | 69        | 0.64%   |
| NetBurst         | 50        | 0.46%   |
| Goldmont         | 46        | 0.43%   |
| K10 Llano        | 43        | 0.4%    |
| Bulldozer        | 39        | 0.36%   |
| Steamroller      | 38        | 0.35%   |
| Jaguar           | 37        | 0.34%   |
| P6               | 26        | 0.24%   |
| K8 & K10 hybrid  | 10        | 0.09%   |
| Puma             | 7         | 0.06%   |
| Alderlake Hybrid | 7         | 0.06%   |
| K6               | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 7310      | 56.51%  |
| Nvidia                           | 3201      | 24.74%  |
| AMD                              | 2234      | 17.27%  |
| Silicon Integrated Systems [SiS] | 99        | 0.77%   |
| VIA Technologies                 | 55        | 0.43%   |
| Matrox Electronics Systems       | 22        | 0.17%   |
| ASPEED Technology                | 7         | 0.05%   |
| Silicon Motion                   | 4         | 0.03%   |
| ATI Technologies                 | 3         | 0.02%   |
| S3 Graphics                      | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 893       | 6.74%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 688       | 5.19%   |
| Intel HD Graphics 620                                                                    | 464       | 3.5%    |
| Intel Core Processor Integrated Graphics Controller                                      | 453       | 3.42%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 380       | 2.87%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 357       | 2.69%   |
| Intel HD Graphics 5500                                                                   | 289       | 2.18%   |
| Intel UHD Graphics 620                                                                   | 276       | 2.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 274       | 2.07%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 270       | 2.04%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 257       | 1.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 253       | 1.91%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 239       | 1.8%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 236       | 1.78%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 225       | 1.7%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 171       | 1.29%   |
| Intel HD Graphics 630                                                                    | 166       | 1.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 164       | 1.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 158       | 1.19%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 151       | 1.14%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 151       | 1.14%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 148       | 1.12%   |
| Nvidia GT218 [GeForce 210]                                                               | 138       | 1.04%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 138       | 1.04%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 137       | 1.03%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 133       | 1%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 127       | 0.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 127       | 0.96%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 98        | 0.74%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 94        | 0.71%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 94        | 0.71%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 93        | 0.7%    |
| Nvidia GP108M [GeForce MX150]                                                            | 93        | 0.7%    |
| AMD Renoir                                                                               | 93        | 0.7%    |
| Nvidia TU117M                                                                            | 89        | 0.67%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 87        | 0.66%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 86        | 0.65%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 82        | 0.62%   |
| Nvidia GM108M [GeForce MX110]                                                            | 81        | 0.61%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 76        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 5361      | 49.38%  |
| 1 x AMD                 | 1597      | 14.71%  |
| 1 x Nvidia              | 1532      | 14.11%  |
| Intel + Nvidia          | 1491      | 13.73%  |
| Intel + AMD             | 390       | 3.59%   |
| AMD + Nvidia            | 150       | 1.38%   |
| 2 x AMD                 | 100       | 0.92%   |
| 1 x SiS                 | 99        | 0.91%   |
| 1 x VIA                 | 54        | 0.5%    |
| Other                   | 29        | 0.27%   |
| 1 x Matrox              | 21        | 0.19%   |
| 2 x Nvidia              | 14        | 0.13%   |
| 1 x ASPEED              | 6         | 0.06%   |
| 2 x Intel               | 4         | 0.04%   |
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

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 8615      | 78.95%  |
| Proprietary | 1863      | 17.07%  |
| Unknown     | 434       | 3.98%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 6591      | 59.64%  |
| 1.01-2.0   | 1618      | 14.64%  |
| 0.01-0.5   | 966       | 8.74%   |
| 0.51-1.0   | 751       | 6.8%    |
| 3.01-4.0   | 715       | 6.47%   |
| 5.01-6.0   | 169       | 1.53%   |
| 7.01-8.0   | 164       | 1.48%   |
| 2.01-3.0   | 54        | 0.49%   |
| 8.01-16.0  | 19        | 0.17%   |
| 4.01-5.0   | 2         | 0.02%   |
| 16.01-24.0 | 2         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 1704      | 14.64%  |
| Goldstar                | 1490      | 12.8%   |
| AU Optronics            | 1435      | 12.33%  |
| BOE                     | 1354      | 11.63%  |
| Chimei Innolux          | 1081      | 9.29%   |
| LG Display              | 1051      | 9.03%   |
| AOC                     | 770       | 6.61%   |
| Dell                    | 486       | 4.17%   |
| Philips                 | 307       | 2.64%   |
| Acer                    | 176       | 1.51%   |
| LG Electronics          | 144       | 1.24%   |
| Chi Mei Optoelectronics | 143       | 1.23%   |
| InfoVision              | 116       | 1%      |
| Hewlett-Packard         | 114       | 0.98%   |
| PANDA                   | 103       | 0.88%   |
| Lenovo                  | 97        | 0.83%   |
| Apple                   | 91        | 0.78%   |
| Sony                    | 79        | 0.68%   |
| BenQ                    | 64        | 0.55%   |
| Unknown                 | 57        | 0.49%   |
| HannStar                | 48        | 0.41%   |
| CPT                     | 46        | 0.4%    |
| RTK                     | 41        | 0.35%   |
| Positivo                | 39        | 0.33%   |
| LG Philips              | 33        | 0.28%   |
| Panasonic               | 30        | 0.26%   |
| InnoLux Display         | 28        | 0.24%   |
| Ancor Communications    | 24        | 0.21%   |
| Sharp                   | 23        | 0.2%    |
| ASUSTek Computer        | 22        | 0.19%   |
| SLD                     | 20        | 0.17%   |
| GDH                     | 19        | 0.16%   |
| Toshiba                 | 18        | 0.15%   |
| NCS                     | 17        | 0.15%   |
| MTD                     | 17        | 0.15%   |
| HB@                     | 15        | 0.13%   |
| AGO                     | 14        | 0.12%   |
| STA                     | 13        | 0.11%   |
| SKY                     | 13        | 0.11%   |
| Envision                | 13        | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch          | 157       | 1.31%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 111       | 0.93%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 105       | 0.88%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 100       | 0.84%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 98        | 0.82%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 96        | 0.8%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 95        | 0.79%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 95        | 0.79%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 91        | 0.76%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch       | 78        | 0.65%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 73        | 0.61%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 72        | 0.6%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 71        | 0.59%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                       | 66        | 0.55%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch        | 64        | 0.53%   |
| BOE LCD Monitor BOE0818 1920x1080 344x194mm 15.5-inch                | 62        | 0.52%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                 | 61        | 0.51%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 58        | 0.48%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                     | 57        | 0.48%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 56        | 0.47%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 55        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 55        | 0.46%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch | 54        | 0.45%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch          | 54        | 0.45%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 54        | 0.45%   |
| BOE LCD Monitor BOE07CE 1366x768 344x193mm 15.5-inch                 | 53        | 0.44%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch        | 53        | 0.44%   |
| InfoVision M140NWR2 R1 IVO057A 1366x768 309x174mm 14.0-inch          | 51        | 0.43%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                | 50        | 0.42%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 50        | 0.42%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 49        | 0.41%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch             | 47        | 0.39%   |
| AOC F19 AOC1900 1366x768 410x230mm 18.5-inch                         | 46        | 0.38%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                 | 44        | 0.37%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch         | 43        | 0.36%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 41        | 0.34%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch          | 40        | 0.33%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch      | 39        | 0.33%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 39        | 0.33%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch        | 38        | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 4620      | 40.73%  |
| 1920x1080 (FHD)    | 3528      | 31.11%  |
| 1600x900 (HD+)     | 475       | 4.19%   |
| 1440x900 (WXGA+)   | 379       | 3.34%   |
| 2560x1080          | 351       | 3.09%   |
| 1360x768           | 316       | 2.79%   |
| 1280x1024 (SXGA)   | 310       | 2.73%   |
| 1280x800 (WXGA)    | 281       | 2.48%   |
| 3840x2160 (4K)     | 248       | 2.19%   |
| 1680x1050 (WSXGA+) | 175       | 1.54%   |
| 1024x768 (XGA)     | 114       | 1.01%   |
| Unknown            | 100       | 0.88%   |
| 2560x1440 (QHD)    | 85        | 0.75%   |
| 1920x1200 (WUXGA)  | 59        | 0.52%   |
| 1280x720 (HD)      | 46        | 0.41%   |
| 1024x600           | 40        | 0.35%   |
| 1920x540           | 31        | 0.27%   |
| 3840x1080          | 28        | 0.25%   |
| 2288x1287          | 20        | 0.18%   |
| 3440x1440          | 12        | 0.11%   |
| 2560x1600          | 10        | 0.09%   |
| 1152x864           | 9         | 0.08%   |
| 5760x1080          | 5         | 0.04%   |
| 4480x1080          | 5         | 0.04%   |
| 3286x1080          | 5         | 0.04%   |
| 1600x1200          | 5         | 0.04%   |
| 1280x960           | 5         | 0.04%   |
| 3360x1080          | 4         | 0.04%   |
| 3200x1080          | 4         | 0.04%   |
| 2736x1824          | 4         | 0.04%   |
| 3840x2400          | 3         | 0.03%   |
| 3520x1080          | 3         | 0.03%   |
| 3200x1800 (QHD+)   | 3         | 0.03%   |
| 2880x1800          | 3         | 0.03%   |
| 2732x768           | 3         | 0.03%   |
| 6400x1080          | 2         | 0.02%   |
| 3600x1080          | 2         | 0.02%   |
| 3360x1050          | 2         | 0.02%   |
| 2800x900           | 2         | 0.02%   |
| 2720x1024          | 2         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 3458      | 29.59%  |
| 14      | 1424      | 12.19%  |
| 13      | 1247      | 10.67%  |
| 18      | 788       | 6.74%   |
| 21      | 728       | 6.23%   |
| 23      | 671       | 5.74%   |
| Unknown | 484       | 4.14%   |
| 17      | 481       | 4.12%   |
| 24      | 323       | 2.76%   |
| 34      | 304       | 2.6%    |
| 20      | 281       | 2.4%    |
| 19      | 273       | 2.34%   |
| 27      | 256       | 2.19%   |
| 31      | 124       | 1.06%   |
| 22      | 110       | 0.94%   |
| 11      | 109       | 0.93%   |
| 12      | 70        | 0.6%    |
| 72      | 59        | 0.5%    |
| 32      | 52        | 0.45%   |
| 40      | 51        | 0.44%   |
| 10      | 46        | 0.39%   |
| 28      | 45        | 0.39%   |
| 84      | 41        | 0.35%   |
| 54      | 41        | 0.35%   |
| 16      | 35        | 0.3%    |
| 26      | 32        | 0.27%   |
| 52      | 31        | 0.27%   |
| 46      | 26        | 0.22%   |
| 47      | 16        | 0.14%   |
| 37      | 10        | 0.09%   |
| 142     | 9         | 0.08%   |
| 48      | 9         | 0.08%   |
| 58      | 6         | 0.05%   |
| 65      | 5         | 0.04%   |
| 39      | 5         | 0.04%   |
| 25      | 5         | 0.04%   |
| 43      | 4         | 0.03%   |
| 41      | 4         | 0.03%   |
| 50      | 3         | 0.03%   |
| 38      | 3         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 6043      | 52.49%  |
| 401-500        | 2063      | 17.92%  |
| 501-600        | 1196      | 10.39%  |
| Unknown        | 484       | 4.2%    |
| 201-300        | 424       | 3.68%   |
| 351-400        | 411       | 3.57%   |
| 701-800        | 356       | 3.09%   |
| 601-700        | 201       | 1.75%   |
| 1001-1500      | 143       | 1.24%   |
| 1501-2000      | 101       | 0.88%   |
| 801-900        | 69        | 0.6%    |
| 901-1000       | 10        | 0.09%   |
| More than 2000 | 9         | 0.08%   |
| 101-200        | 2         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 8411      | 79.79%  |
| 16/10   | 847       | 8.03%   |
| Unknown | 412       | 3.91%   |
| 21/9    | 332       | 3.15%   |
| 5/4     | 309       | 2.93%   |
| 4/3     | 168       | 1.59%   |
| 3/2     | 50        | 0.47%   |
| 1.00    | 9         | 0.09%   |
| 32/9    | 2         | 0.02%   |
| 6/5     | 1         | 0.01%   |
| 0.31    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 3417      | 29.4%   |
| 81-90          | 2515      | 21.64%  |
| 201-250        | 1542      | 13.27%  |
| 141-150        | 955       | 8.22%   |
| 151-200        | 816       | 7.02%   |
| 351-500        | 495       | 4.26%   |
| Unknown        | 484       | 4.16%   |
| 301-350        | 263       | 2.26%   |
| More than 1000 | 209       | 1.8%    |
| 71-80          | 158       | 1.36%   |
| 121-130        | 129       | 1.11%   |
| 501-1000       | 124       | 1.07%   |
| 251-300        | 123       | 1.06%   |
| 51-60          | 109       | 0.94%   |
| 131-140        | 109       | 0.94%   |
| 91-100         | 49        | 0.42%   |
| 41-50          | 46        | 0.4%    |
| 61-70          | 39        | 0.34%   |
| 111-120        | 39        | 0.34%   |
| 1-40           | 2         | 0.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 4774      | 42.27%  |
| 51-100        | 3685      | 32.63%  |
| 121-160       | 1881      | 16.65%  |
| Unknown       | 485       | 4.29%   |
| 1-50          | 308       | 2.73%   |
| 161-240       | 140       | 1.24%   |
| More than 240 | 22        | 0.19%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 8767      | 79.53%  |
| 2     | 1712      | 15.53%  |
| 0     | 451       | 4.09%   |
| 3     | 87        | 0.79%   |
| 4     | 6         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 7681      | 44.69%  |
| Qualcomm Atheros                  | 3450      | 20.07%  |
| Intel                             | 2839      | 16.52%  |
| Broadcom                          | 794       | 4.62%   |
| Ralink Technology                 | 391       | 2.27%   |
| Marvell Technology Group          | 223       | 1.3%    |
| Nvidia                            | 204       | 1.19%   |
| Ralink                            | 198       | 1.15%   |
| JMicron Technology                | 198       | 1.15%   |
| Broadcom Limited                  | 175       | 1.02%   |
| TP-Link                           | 164       | 0.95%   |
| Qualcomm Atheros Communications   | 121       | 0.7%    |
| Samsung Electronics               | 102       | 0.59%   |
| Silicon Integrated Systems [SiS]  | 100       | 0.58%   |
| VIA Technologies                  | 69        | 0.4%    |
| D-Link                            | 67        | 0.39%   |
| Motorola PCS                      | 45        | 0.26%   |
| Xiaomi                            | 42        | 0.24%   |
| Microsoft                         | 40        | 0.23%   |
| D-Link System                     | 36        | 0.21%   |
| ASIX Electronics                  | 30        | 0.17%   |
| MediaTek                          | 28        | 0.16%   |
| ICS Advent                        | 17        | 0.1%    |
| Motorola                          | 13        | 0.08%   |
| DisplayLink                       | 11        | 0.06%   |
| Huawei Technologies               | 7         | 0.04%   |
| Edimax Technology                 | 7         | 0.04%   |
| ASUSTek Computer                  | 7         | 0.04%   |
| Microchip Technology              | 6         | 0.03%   |
| Mercucys                          | 6         | 0.03%   |
| LG Electronics                    | 6         | 0.03%   |
| Dell                              | 6         | 0.03%   |
| Qualcomm                          | 5         | 0.03%   |
| Arduino SA                        | 5         | 0.03%   |
| 3Com                              | 5         | 0.03%   |
| Sundance Technology Inc / IC Plus | 4         | 0.02%   |
| Lenovo                            | 4         | 0.02%   |
| Attansic Technology               | 4         | 0.02%   |
| AMD                               | 4         | 0.02%   |
| Accton Technology                 | 4         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5054      | 26.91%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1700      | 9.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 796       | 4.24%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 703       | 3.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 624       | 3.32%   |
| Intel Wi-Fi 6 AX200                                               | 347       | 1.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 304       | 1.62%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 299       | 1.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 293       | 1.56%   |
| Ralink MT7601U Wireless Adapter                                   | 217       | 1.16%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 203       | 1.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 164       | 0.87%   |
| Intel Wireless 7265                                               | 159       | 0.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 158       | 0.84%   |
| Nvidia MCP61 Ethernet                                             | 152       | 0.81%   |
| Intel Wi-Fi 6 AX201                                               | 147       | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 142       | 0.76%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 140       | 0.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 132       | 0.7%    |
| Realtek RTL8188EE Wireless Network Adapter                        | 112       | 0.6%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 111       | 0.59%   |
| Qualcomm Atheros AR9271 802.11n                                   | 108       | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 107       | 0.57%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 104       | 0.55%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 100       | 0.53%   |
| Intel Wireless 7260                                               | 95        | 0.51%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 94        | 0.5%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 93        | 0.5%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 93        | 0.5%    |
| Realtek 802.11n                                                   | 93        | 0.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 93        | 0.5%    |
| Intel Wireless 3165                                               | 91        | 0.48%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 89        | 0.47%   |
| Intel Ethernet Connection (2) I219-V                              | 86        | 0.46%   |
| Ralink RT5370 Wireless Adapter                                    | 82        | 0.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 81        | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 76        | 0.4%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 75        | 0.4%    |
| Intel I211 Gigabit Network Connection                             | 75        | 0.4%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 74        | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Qualcomm Atheros                      | 3018      | 36.73%  |
| Intel                                 | 2171      | 26.42%  |
| Realtek Semiconductor                 | 1371      | 16.69%  |
| Broadcom                              | 494       | 6.01%   |
| Ralink Technology                     | 391       | 4.76%   |
| Ralink                                | 198       | 2.41%   |
| TP-Link                               | 151       | 1.84%   |
| Qualcomm Atheros Communications       | 121       | 1.47%   |
| Broadcom Limited                      | 99        | 1.2%    |
| D-Link                                | 67        | 0.82%   |
| Microsoft                             | 40        | 0.49%   |
| D-Link System                         | 24        | 0.29%   |
| MediaTek                              | 20        | 0.24%   |
| Marvell Technology Group              | 7         | 0.09%   |
| Edimax Technology                     | 7         | 0.09%   |
| Mercucys                              | 6         | 0.07%   |
| NetGear                               | 3         | 0.04%   |
| Micro Star International              | 3         | 0.04%   |
| Linksys                               | 3         | 0.04%   |
| Encore Electronics                    | 3         | 0.04%   |
| Dell                                  | 3         | 0.04%   |
| Sierra Wireless                       | 2         | 0.02%   |
| Philips (or NXP)                      | 2         | 0.02%   |
| IMC Networks                          | 2         | 0.02%   |
| ASUSTek Computer                      | 2         | 0.02%   |
| Accton Technology                     | 2         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.02%   |
| Texas Instruments                     | 1         | 0.01%   |
| Samsung Electronics                   | 1         | 0.01%   |
| Pegatron                              | 1         | 0.01%   |
| Guillemot                             | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 796       | 9.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 703       | 8.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 624       | 7.55%   |
| Intel Wi-Fi 6 AX200                                                     | 347       | 4.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 304       | 3.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 299       | 3.62%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 293       | 3.55%   |
| Ralink MT7601U Wireless Adapter                                         | 217       | 2.63%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 203       | 2.46%   |
| Intel Wireless 7265                                                     | 159       | 1.92%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 158       | 1.91%   |
| Intel Wi-Fi 6 AX201                                                     | 147       | 1.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 132       | 1.6%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 112       | 1.36%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 111       | 1.34%   |
| Qualcomm Atheros AR9271 802.11n                                         | 108       | 1.31%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 104       | 1.26%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 100       | 1.21%   |
| Intel Wireless 7260                                                     | 95        | 1.15%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 93        | 1.13%   |
| Realtek 802.11n                                                         | 93        | 1.13%   |
| Intel Wireless 3165                                                     | 91        | 1.1%    |
| Ralink RT5370 Wireless Adapter                                          | 82        | 0.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 81        | 0.98%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 75        | 0.91%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 74        | 0.9%    |
| Intel Wireless 3160                                                     | 71        | 0.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 67        | 0.81%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 63        | 0.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 63        | 0.76%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 62        | 0.75%   |
| Intel Centrino Advanced-N 6235                                          | 60        | 0.73%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 58        | 0.7%    |
| Intel Wireless 8265 / 8275                                              | 57        | 0.69%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 55        | 0.67%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 54        | 0.65%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 50        | 0.6%    |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 50        | 0.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 49        | 0.59%   |
| Realtek 802.11ac NIC                                                    | 47        | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 7085      | 68.7%   |
| Intel                             | 989       | 9.59%   |
| Qualcomm Atheros                  | 670       | 6.5%    |
| Broadcom                          | 372       | 3.61%   |
| Marvell Technology Group          | 216       | 2.09%   |
| Nvidia                            | 203       | 1.97%   |
| JMicron Technology                | 198       | 1.92%   |
| Samsung Electronics               | 101       | 0.98%   |
| Silicon Integrated Systems [SiS]  | 100       | 0.97%   |
| Broadcom Limited                  | 82        | 0.8%    |
| VIA Technologies                  | 68        | 0.66%   |
| Xiaomi                            | 42        | 0.41%   |
| Motorola PCS                      | 34        | 0.33%   |
| ASIX Electronics                  | 30        | 0.29%   |
| ICS Advent                        | 17        | 0.16%   |
| TP-Link                           | 13        | 0.13%   |
| D-Link System                     | 12        | 0.12%   |
| DisplayLink                       | 11        | 0.11%   |
| MediaTek                          | 7         | 0.07%   |
| Microchip Technology              | 5         | 0.05%   |
| ASUSTek Computer                  | 5         | 0.05%   |
| 3Com                              | 5         | 0.05%   |
| Sundance Technology Inc / IC Plus | 4         | 0.04%   |
| Qualcomm                          | 4         | 0.04%   |
| LG Electronics                    | 4         | 0.04%   |
| Lenovo                            | 4         | 0.04%   |
| Attansic Technology               | 4         | 0.04%   |
| OPPO Electronics                  | 3         | 0.03%   |
| Hangzhou Silan Microelectronics   | 3         | 0.03%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.02%   |
| T & A Mobile Phones               | 2         | 0.02%   |
| Huawei Technologies               | 2         | 0.02%   |
| Aquantia                          | 2         | 0.02%   |
| Apple                             | 2         | 0.02%   |
| Accton Technology                 | 2         | 0.02%   |
| Standard Microsystems             | 1         | 0.01%   |
| Spreadtrum Communications         | 1         | 0.01%   |
| SK hynix                          | 1         | 0.01%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.01%   |
| NetXen Incorporated               | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5054      | 48.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1700      | 16.29%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 164       | 1.57%   |
| Nvidia MCP61 Ethernet                                             | 152       | 1.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 142       | 1.36%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 140       | 1.34%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 107       | 1.03%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 94        | 0.9%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 93        | 0.89%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 93        | 0.89%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 89        | 0.85%   |
| Intel Ethernet Connection (2) I219-V                              | 86        | 0.82%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 76        | 0.73%   |
| Intel I211 Gigabit Network Connection                             | 75        | 0.72%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 74        | 0.71%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 73        | 0.7%    |
| Intel Ethernet Connection (7) I219-V                              | 71        | 0.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 67        | 0.64%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 66        | 0.63%   |
| Intel 82579V Gigabit Network Connection                           | 66        | 0.63%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 64        | 0.61%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 58        | 0.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 57        | 0.55%   |
| Intel Ethernet Connection I217-LM                                 | 52        | 0.5%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 51        | 0.49%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 46        | 0.44%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 43        | 0.41%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 39        | 0.37%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 39        | 0.37%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 37        | 0.35%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 34        | 0.33%   |
| Motorola PCS motorola one                                         | 34        | 0.33%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 34        | 0.33%   |
| Intel 82578DC Gigabit Network Connection                          | 33        | 0.32%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 32        | 0.31%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 30        | 0.29%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 29        | 0.28%   |
| Intel Ethernet Connection (2) I218-V                              | 29        | 0.28%   |
| Intel Ethernet Connection (4) I219-LM                             | 28        | 0.27%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 26        | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 9949      | 55.5%   |
| WiFi     | 7897      | 44.05%  |
| Modem    | 56        | 0.31%   |
| Unknown  | 25        | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 6505      | 58.12%  |
| Ethernet | 4684      | 41.85%  |
| Unknown  | 4         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 6315      | 58.32%  |
| 1     | 4106      | 37.92%  |
| 0     | 317       | 2.93%   |
| 3     | 68        | 0.63%   |
| 4     | 16        | 0.15%   |
| 10    | 3         | 0.03%   |
| 8     | 1         | 0.01%   |
| 6     | 1         | 0.01%   |
| 5     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 8826      | 79.92%  |
| Yes  | 2218      | 20.08%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1836      | 33.74%  |
| Qualcomm Atheros Communications | 1448      | 26.61%  |
| Lite-On Technology              | 611       | 11.23%  |
| Cambridge Silicon Radio         | 457       | 8.4%    |
| Broadcom                        | 216       | 3.97%   |
| Realtek Semiconductor           | 198       | 3.64%   |
| Foxconn / Hon Hai               | 114       | 2.09%   |
| Apple                           | 110       | 2.02%   |
| IMC Networks                    | 109       | 2%      |
| Dell                            | 71        | 1.3%    |
| Hewlett-Packard                 | 49        | 0.9%    |
| Ralink                          | 47        | 0.86%   |
| Unknown                         | 42        | 0.77%   |
| Qcom                            | 25        | 0.46%   |
| ASUSTek Computer                | 21        | 0.39%   |
| Ralink Technology               | 16        | 0.29%   |
| Alps Electric                   | 13        | 0.24%   |
| Foxconn International           | 12        | 0.22%   |
| Integrated System Solution      | 8         | 0.15%   |
| Askey Computer                  | 8         | 0.15%   |
| MediaTek                        | 7         | 0.13%   |
| Toshiba                         | 4         | 0.07%   |
| Micro Star International        | 4         | 0.07%   |
| Conwise Technology              | 3         | 0.06%   |
| Unknown                         | 3         | 0.06%   |
| SINO WEALTH                     | 2         | 0.04%   |
| Opticis                         | 2         | 0.04%   |
| Marvell Semiconductor           | 2         | 0.04%   |
| Syntek                          | 1         | 0.02%   |
| Realtek                         | 1         | 0.02%   |
| Motorola PCS                    | 1         | 0.02%   |
| D-Link                          | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                                                  | 814       | 14.95%  |
| Intel Bluetooth wireless interface                                                  | 636       | 11.68%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 458       | 8.41%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 457       | 8.4%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 354       | 6.5%    |
| Intel AX200 Bluetooth                                                               | 337       | 6.19%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 228       | 4.19%   |
| Realtek Bluetooth Radio                                                             | 158       | 2.9%    |
| Intel AX201 Bluetooth                                                               | 148       | 2.72%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 145       | 2.66%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 132       | 2.43%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 111       | 2.04%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 86        | 1.58%   |
| Lite-On Bluetooth Device                                                            | 84        | 1.54%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 82        | 1.51%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 65        | 1.19%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 60        | 1.1%    |
| Broadcom BCM2070 Bluetooth Device                                                   | 57        | 1.05%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 54        | 0.99%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 54        | 0.99%   |
| Ralink RT3290 Bluetooth                                                             | 47        | 0.86%   |
| Unknown Bluetooth Device                                                            | 42        | 0.77%   |
| IMC Networks Bluetooth Radio                                                        | 42        | 0.77%   |
| Apple Bluetooth Host Controller                                                     | 40        | 0.73%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 36        | 0.66%   |
| Apple Bluetooth USB Host Controller                                                 | 36        | 0.66%   |
| Dell Wireless 365 Bluetooth                                                         | 31        | 0.57%   |
| IMC Networks Bluetooth Device                                                       | 30        | 0.55%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 30        | 0.55%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 29        | 0.53%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 26        | 0.48%   |
| Lite-On Atheros Bluetooth                                                           | 22        | 0.4%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 22        | 0.4%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 18        | 0.33%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 17        | 0.31%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 16        | 0.29%   |
| Realtek RTL8723A Bluetooth                                                          | 15        | 0.28%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 15        | 0.28%   |
| Intel AX210 Bluetooth                                                               | 15        | 0.28%   |
| Dell DW375 Bluetooth Module                                                         | 15        | 0.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 8378      | 60.8%   |
| AMD                                             | 2166      | 15.72%  |
| Nvidia                                          | 2134      | 15.49%  |
| C-Media Electronics                             | 228       | 1.65%   |
| Generalplus Technology                          | 108       | 0.78%   |
| Silicon Integrated Systems [SiS]                | 101       | 0.73%   |
| Logitech                                        | 78        | 0.57%   |
| VIA Technologies                                | 73        | 0.53%   |
| JMTek                                           | 60        | 0.44%   |
| Kingston Technology                             | 44        | 0.32%   |
| Creative Labs                                   | 37        | 0.27%   |
| Texas Instruments                               | 35        | 0.25%   |
| Corsair                                         | 27        | 0.2%    |
| Microsoft                                       | 21        | 0.15%   |
| Plantronics                                     | 18        | 0.13%   |
| Licensed by Sony Computer Entertainment America | 15        | 0.11%   |
| GN Netcom                                       | 15        | 0.11%   |
| Tenx Technology                                 | 14        | 0.1%    |
| Razer USA                                       | 14        | 0.1%    |
| BEHRINGER International                         | 13        | 0.09%   |
| Sony                                            | 12        | 0.09%   |
| Realtek Semiconductor                           | 10        | 0.07%   |
| M-Audio                                         | 8         | 0.06%   |
| Focusrite-Novation                              | 8         | 0.06%   |
| Dell                                            | 8         | 0.06%   |
| SteelSeries ApS                                 | 7         | 0.05%   |
| Goldvish                                        | 7         | 0.05%   |
| BY EDIFIER                                      | 7         | 0.05%   |
| Philips (or NXP)                                | 6         | 0.04%   |
| JBL                                             | 6         | 0.04%   |
| Fry's Electronics                               | 6         | 0.04%   |
| Creative Technology                             | 6         | 0.04%   |
| Samsung Electronics                             | 5         | 0.04%   |
| Cirrus Logic                                    | 5         | 0.04%   |
| Turtle Beach                                    | 4         | 0.03%   |
| Tdlasunnic                                      | 4         | 0.03%   |
| Samson Technologies                             | 4         | 0.03%   |
| Meizu                                           | 4         | 0.03%   |
| Lenovo                                          | 4         | 0.03%   |
| FIFINE Microphones                              | 4         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1114      | 6.96%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1058      | 6.61%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1058      | 6.61%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 653       | 4.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 555       | 3.47%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 523       | 3.27%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 510       | 3.19%   |
| Intel Cannon Lake PCH cAVS                                                                        | 489       | 3.05%   |
| Intel 8 Series HD Audio Controller                                                                | 380       | 2.37%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 376       | 2.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 375       | 2.34%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 336       | 2.1%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 328       | 2.05%   |
| Intel Broadwell-U Audio Controller                                                                | 307       | 1.92%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 306       | 1.91%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 301       | 1.88%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 287       | 1.79%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 273       | 1.71%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 243       | 1.52%   |
| AMD FCH Azalia Controller                                                                         | 240       | 1.5%    |
| Nvidia High Definition Audio Controller                                                           | 220       | 1.37%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 198       | 1.24%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 188       | 1.17%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 182       | 1.14%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 173       | 1.08%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 169       | 1.06%   |
| Nvidia MCP61 High Definition Audio                                                                | 166       | 1.04%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 166       | 1.04%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 160       | 1%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 160       | 1%      |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 155       | 0.97%   |
| AMD Wrestler HDMI Audio                                                                           | 142       | 0.89%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 136       | 0.85%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 133       | 0.83%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 130       | 0.81%   |
| Intel 200 Series PCH HD Audio                                                                     | 129       | 0.81%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 110       | 0.69%   |
| Generalplus Technology USB Audio Device                                                           | 108       | 0.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 105       | 0.66%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 102       | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 793       | 17.99%  |
| Kingston            | 720       | 16.34%  |
| Smart               | 599       | 13.59%  |
| Samsung Electronics | 410       | 9.3%    |
| SK hynix            | 294       | 6.67%   |
| A-DATA Technology   | 243       | 5.51%   |
| Corsair             | 216       | 4.9%    |
| Teikon              | 160       | 3.63%   |
| Crucial             | 152       | 3.45%   |
| Micron Technology   | 141       | 3.2%    |
| Smart Brazil        | 94        | 2.13%   |
| High Bridge         | 58        | 1.32%   |
| Elpida              | 45        | 1.02%   |
| Team                | 40        | 0.91%   |
| Multilaser          | 40        | 0.91%   |
| Unknown             | 40        | 0.91%   |
| G.Skill             | 35        | 0.79%   |
| Apacer              | 28        | 0.64%   |
| Unknown (ABCD)      | 25        | 0.57%   |
| Patriot             | 24        | 0.54%   |
| Nanya Technology    | 20        | 0.45%   |
| Kllisre             | 14        | 0.32%   |
| Ramaxel Technology  | 12        | 0.27%   |
| Avant               | 12        | 0.27%   |
| Atermiter           | 12        | 0.27%   |
| HT Micron           | 11        | 0.25%   |
| Smart Modular       | 9         | 0.2%    |
| Kreton              | 9         | 0.2%    |
| RZX                 | 8         | 0.18%   |
| HBS                 | 8         | 0.18%   |
| GeIL                | 7         | 0.16%   |
| CSX                 | 7         | 0.16%   |
| PUSKILL             | 6         | 0.14%   |
| Kingmax             | 6         | 0.14%   |
| Carry               | 6         | 0.14%   |
| Unknown (82B5)      | 5         | 0.11%   |
| Positivo            | 5         | 0.11%   |
| GLOWAY              | 5         | 0.11%   |
| Qimonda             | 4         | 0.09%   |
| MemoWise            | 4         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 71        | 1.47%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 50        | 1.03%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1333MT/s            | 44        | 0.91%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s                | 43        | 0.89%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 41        | 0.85%   |
| Unknown                                                          | 40        | 0.83%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 39        | 0.81%   |
| Smart RAM SH564128FH8NZPHSCG 4096MB SODIMM DDR3 1334MT/s         | 36        | 0.74%   |
| Smart RAM SF4641G8CK8IEHLSBG 8192MB SODIMM DDR4 2667MT/s         | 34        | 0.7%    |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s            | 32        | 0.66%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 30        | 0.62%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s            | 30        | 0.62%   |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1600MT/s           | 30        | 0.62%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 29        | 0.6%    |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 29        | 0.6%    |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 29        | 0.6%    |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 29        | 0.6%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 28        | 0.58%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 26        | 0.54%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 26        | 0.54%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 24        | 0.5%    |
| Smart RAM SH564128FJ8NZRNSDG 4GB SODIMM DDR3 1600MT/s            | 24        | 0.5%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 23        | 0.48%   |
| Smart RAM SH564568FH8NZPHSCG 2GB SODIMM DDR3 1333MT/s            | 20        | 0.41%   |
| A-DATA RAM AM1P26KC8T1-BAAS 8GB SODIMM DDR4 2667MT/s             | 20        | 0.41%   |
| A-DATA RAM AE4S240038G17-BHYA 8GB SODIMM DDR4 2400MT/s           | 20        | 0.41%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s            | 19        | 0.39%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 19        | 0.39%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8192MB SODIMM DDR4 2400MT/s        | 18        | 0.37%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 18        | 0.37%   |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s            | 17        | 0.35%   |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s            | 17        | 0.35%   |
| A-DATA RAM DDR4 3000 8GB DIMM DDR4 3600MT/s                      | 17        | 0.35%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s             | 16        | 0.33%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 16        | 0.33%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s              | 16        | 0.33%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 15        | 0.31%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 15        | 0.31%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 15        | 0.31%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 15        | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR3         | 1644      | 43.78%  |
| DDR4         | 1336      | 35.58%  |
| DDR2         | 259       | 6.9%    |
| Unknown      | 184       | 4.9%    |
| SDRAM        | 172       | 4.58%   |
| LPDDR4       | 63        | 1.68%   |
| DDR          | 44        | 1.17%   |
| LPDDR3       | 28        | 0.75%   |
| DRAM         | 19        | 0.51%   |
| DDR5         | 3         | 0.08%   |
| RAM          | 1         | 0.03%   |
| LPDDR5       | 1         | 0.03%   |
| DDR2 FB-DIMM | 1         | 0.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2025      | 54.52%  |
| DIMM         | 1600      | 43.08%  |
| Row Of Chips | 72        | 1.94%   |
| Unknown      | 9         | 0.24%   |
| RIMM         | 3         | 0.08%   |
| FB-DIMM      | 3         | 0.08%   |
| Chip         | 2         | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 1589      | 37.51%  |
| 8192  | 1186      | 28%     |
| 2048  | 884       | 20.87%  |
| 16384 | 344       | 8.12%   |
| 1024  | 148       | 3.49%   |
| 32768 | 64        | 1.51%   |
| 512   | 17        | 0.4%    |
| 256   | 2         | 0.05%   |
| 1536  | 1         | 0.02%   |
| 16    | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 930       | 22.13%  |
| 1333    | 558       | 13.28%  |
| 2667    | 528       | 12.56%  |
| 2400    | 406       | 9.66%   |
| Unknown | 225       | 5.35%   |
| 1334    | 212       | 5.04%   |
| 3200    | 171       | 4.07%   |
| 800     | 145       | 3.45%   |
| 2133    | 134       | 3.19%   |
| 667     | 130       | 3.09%   |
| 1066    | 59        | 1.4%    |
| 3400    | 56        | 1.33%   |
| 3000    | 56        | 1.33%   |
| 1067    | 55        | 1.31%   |
| 3600    | 53        | 1.26%   |
| 1867    | 48        | 1.14%   |
| 4199    | 38        | 0.9%    |
| 533     | 33        | 0.79%   |
| 1866    | 32        | 0.76%   |
| 3466    | 31        | 0.74%   |
| 4267    | 27        | 0.64%   |
| 2933    | 23        | 0.55%   |
| 2800    | 23        | 0.55%   |
| 2048    | 20        | 0.48%   |
| 975     | 20        | 0.48%   |
| 2666    | 19        | 0.45%   |
| 400     | 17        | 0.4%    |
| 3733    | 16        | 0.38%   |
| 3151    | 16        | 0.38%   |
| 333     | 14        | 0.33%   |
| 3800    | 11        | 0.26%   |
| 3266    | 10        | 0.24%   |
| 3334    | 8         | 0.19%   |
| 8400    | 6         | 0.14%   |
| 3333    | 6         | 0.14%   |
| 1200    | 5         | 0.12%   |
| 41632   | 4         | 0.1%    |
| 4800    | 3         | 0.07%   |
| 3066    | 3         | 0.07%   |
| 2733    | 3         | 0.07%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 107       | 45.15%  |
| Seiko Epson           | 62        | 26.16%  |
| Samsung Electronics   | 21        | 8.86%   |
| Canon                 | 19        | 8.02%   |
| Brother Industries    | 16        | 6.75%   |
| QinHeng Electronics   | 2         | 0.84%   |
| Lexmark International | 2         | 0.84%   |
| Apple                 | 2         | 0.84%   |
| Xerox                 | 1         | 0.42%   |
| Ricoh                 | 1         | 0.42%   |
| Prolific Technology   | 1         | 0.42%   |
| Oki Data              | 1         | 0.42%   |
| MIIIW                 | 1         | 0.42%   |
| ARGOX                 | 1         | 0.42%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson L3150 Series                     | 13        | 5.46%   |
| Seiko Epson ET-2600 Series                   | 10        | 4.2%    |
| HP DeskJet 2130 series                       | 9         | 3.78%   |
| HP Ink Tank Wireless 410 series              | 8         | 3.36%   |
| Seiko Epson L355 Series                      | 7         | 2.94%   |
| HP Deskjet 3050 J610 series                  | 7         | 2.94%   |
| HP Deskjet 2540 series                       | 7         | 2.94%   |
| Seiko Epson L365 Series                      | 6         | 2.52%   |
| Canon G3010 series                           | 6         | 2.52%   |
| Samsung SCX-4200 series                      | 5         | 2.1%    |
| HP LaserJet Professional P1102w              | 5         | 2.1%    |
| HP LaserJet 1020                             | 5         | 2.1%    |
| HP DeskJet F4100 Printer series              | 5         | 2.1%    |
| HP DeskJet 2700 series                       | 5         | 2.1%    |
| Samsung M2070 Series                         | 4         | 1.68%   |
| HP LaserJet P1005                            | 4         | 1.68%   |
| HP DeskJet F4200 series                      | 4         | 1.68%   |
| HP DeskJet 3630 series                       | 4         | 1.68%   |
| HP DeskJet 2620 All-in-One Printer           | 4         | 1.68%   |
| HP Deskjet 2050 J510                         | 4         | 1.68%   |
| Seiko Epson L210 Series                      | 3         | 1.26%   |
| Samsung M2020 Series                         | 3         | 1.26%   |
| HP LaserJet 1018                             | 3         | 1.26%   |
| HP Deskjet F4400 series                      | 3         | 1.26%   |
| Brother HL-1200 series                       | 3         | 1.26%   |
| Seiko Epson XP-243 245 247 Series            | 2         | 0.84%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 2         | 0.84%   |
| Seiko Epson L4150 Series                     | 2         | 0.84%   |
| Seiko Epson L375 Series                      | 2         | 0.84%   |
| Seiko Epson L3110 Series                     | 2         | 0.84%   |
| Seiko Epson L222 Series                      | 2         | 0.84%   |
| Seiko Epson ET-3750 Series                   | 2         | 0.84%   |
| Samsung SCX-3200 Series                      | 2         | 0.84%   |
| Samsung ML-216x Series Laser Printer         | 2         | 0.84%   |
| QinHeng CH340S                               | 2         | 0.84%   |
| HP Printing Support                          | 2         | 0.84%   |
| HP DeskJet D1360                             | 2         | 0.84%   |
| HP Deskjet 4620 series                       | 2         | 0.84%   |
| HP DeskJet 2300 series                       | 2         | 0.84%   |
| Canon PIXMA MG3000 series                    | 2         | 0.84%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 8         | 42.11%  |
| Canon           | 8         | 42.11%  |
| Seiko Epson     | 2         | 10.53%  |
| Mustek Systems  | 1         | 5.26%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| HP ScanJet 2400c                                        | 5         | 26.32%  |
| Canon CanoScan LIDE 25                                  | 4         | 21.05%  |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 5.26%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 5.26%   |
| Mustek Systems ScanExpress 1200 UB                      | 1         | 5.26%   |
| HP ScanJet G4050                                        | 1         | 5.26%   |
| HP ScanJet 3800c                                        | 1         | 5.26%   |
| HP Scanjet 200                                          | 1         | 5.26%   |
| Canon CanoScan N670U/N676U/LiDE 20                      | 1         | 5.26%   |
| Canon CanoScan N1240U/LiDE 30                           | 1         | 5.26%   |
| Canon CanoScan LiDE 210                                 | 1         | 5.26%   |
| Canon CanoScan LiDE 110                                 | 1         | 5.26%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1318      | 19.77%  |
| Microdia                               | 747       | 11.21%  |
| Realtek Semiconductor                  | 612       | 9.18%   |
| Quanta                                 | 561       | 8.42%   |
| Silicon Motion                         | 505       | 7.58%   |
| Sunplus Innovation Technology          | 468       | 7.02%   |
| Acer                                   | 430       | 6.45%   |
| IMC Networks                           | 274       | 4.11%   |
| Suyin                                  | 260       | 3.9%    |
| Logitech                               | 240       | 3.6%    |
| Syntek                                 | 188       | 2.82%   |
| Alcor Micro                            | 134       | 2.01%   |
| Apple                                  | 98        | 1.47%   |
| Samsung Electronics                    | 84        | 1.26%   |
| Cheng Uei Precision Industry (Foxlink) | 78        | 1.17%   |
| Z-Star Microelectronics                | 58        | 0.87%   |
| Generalplus Technology                 | 54        | 0.81%   |
| Microsoft                              | 50        | 0.75%   |
| Ricoh                                  | 45        | 0.68%   |
| ALi                                    | 42        | 0.63%   |
| Unknown                                | 31        | 0.47%   |
| Aveo Technology                        | 26        | 0.39%   |
| Lite-On Technology                     | 22        | 0.33%   |
| OmniVision Technologies                | 21        | 0.32%   |
| Importek                               | 21        | 0.32%   |
| GEMBIRD                                | 21        | 0.32%   |
| Pixart Imaging                         | 19        | 0.29%   |
| LG Electronics                         | 18        | 0.27%   |
| Jieli Technology                       | 17        | 0.26%   |
| Lenovo                                 | 16        | 0.24%   |
| Cubeternet                             | 15        | 0.23%   |
| Sonix Technology                       | 12        | 0.18%   |
| USB Camera                             | 11        | 0.17%   |
| Intel                                  | 10        | 0.15%   |
| Genesys Logic                          | 10        | 0.15%   |
| SunplusIT                              | 9         | 0.14%   |
| Sunplus Technology                     | 9         | 0.14%   |
| Camera                                 | 9         | 0.14%   |
| Y Media                                | 7         | 0.11%   |
| MacroSilicon                           | 7         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD              | 263       | 3.94%   |
| Microdia Integrated_Webcam_HD             | 253       | 3.79%   |
| Quanta HD User Facing                     | 236       | 3.53%   |
| Chicony HD User Facing                    | 195       | 2.92%   |
| Chicony HD WebCam                         | 193       | 2.89%   |
| Silicon Motion Web Camera                 | 182       | 2.73%   |
| Sunplus Integrated_Webcam_HD              | 181       | 2.71%   |
| Quanta VGA WebCam                         | 172       | 2.58%   |
| Chicony USB 2.0 Camera                    | 142       | 2.13%   |
| Chicony VGA WebCam                        | 132       | 1.98%   |
| Chicony Integrated Camera                 | 130       | 1.95%   |
| Syntek Integrated Camera                  | 103       | 1.54%   |
| Sunplus HD WebCam                         | 101       | 1.51%   |
| Realtek Integrated Webcam                 | 97        | 1.45%   |
| Microdia Laptop_Integrated_Webcam_HD      | 97        | 1.45%   |
| Quanta HD Webcam                          | 95        | 1.42%   |
| Logitech Webcam C270                      | 91        | 1.36%   |
| Alcor Micro USB 2.0 Camera                | 84        | 1.26%   |
| Samsung Galaxy series, misc. (MTP mode)   | 83        | 1.24%   |
| Acer BisonCam, NB Pro                     | 70        | 1.05%   |
| Acer EasyCamera                           | 64        | 0.96%   |
| Realtek USB Camera                        | 62        | 0.93%   |
| Acer Lenovo EasyCamera                    | 62        | 0.93%   |
| Microdia Dell Laptop Integrated Webcam HD | 53        | 0.79%   |
| Logitech HD Pro Webcam C920               | 52        | 0.78%   |
| Silicon Motion WebCam SC-10HDD12636N      | 48        | 0.72%   |
| IMC Networks Integrated Camera            | 46        | 0.69%   |
| Microdia Integrated Webcam HD             | 44        | 0.66%   |
| Acer VGA WebCam                           | 43        | 0.64%   |
| Suyin Integrated_Webcam_HD                | 42        | 0.63%   |
| Realtek HD WebCam                         | 41        | 0.61%   |
| Chicony EasyCamera                        | 40        | 0.6%    |
| Silicon Motion WebCam SCB-1100N           | 39        | 0.58%   |
| IMC Networks USB2.0 VGA UVC WebCam        | 39        | 0.58%   |
| Silicon Motion WebCam SC-13HDL11939N      | 37        | 0.55%   |
| Generalplus GENERAL WEBCAM                | 37        | 0.55%   |
| Silicon Motion WebCam SC-0311139N         | 36        | 0.54%   |
| Acer HD Webcam                            | 36        | 0.54%   |
| Syntek EasyCamera                         | 35        | 0.52%   |
| Acer USB Camera                           | 35        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 267       | 47.68%  |
| Synaptics                  | 65        | 11.61%  |
| Shenzhen Goodix Technology | 61        | 10.89%  |
| AuthenTec                  | 55        | 9.82%   |
| Upek                       | 52        | 9.29%   |
| LighTuning Technology      | 29        | 5.18%   |
| Samsung Electronics        | 15        | 2.68%   |
| Elan Microelectronics      | 8         | 1.43%   |
| STMicroelectronics         | 3         | 0.54%   |
| Dell                       | 2         | 0.36%   |
| Futronic Technology        | 1         | 0.18%   |
| Focal-systems.Corp         | 1         | 0.18%   |
| DigitalPersona             | 1         | 0.18%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                                | 102       | 18.21%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 44        | 7.86%   |
| Shenzhen Goodix Fingerprint Reader                                         | 41        | 7.32%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 26        | 4.64%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 26        | 4.64%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 24        | 4.29%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 22        | 3.93%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 21        | 3.75%   |
| Validity Sensors Fingerprint scanner                                       | 21        | 3.75%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 18        | 3.21%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 15        | 2.68%   |
| Synaptics  WBDI                                                            | 15        | 2.68%   |
| Shenzhen Goodix  FingerPrint Device                                        | 15        | 2.68%   |
| Samsung Fingerprint Device                                                 | 15        | 2.68%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 14        | 2.5%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 12        | 2.14%   |
| AuthenTec AES2810                                                          | 12        | 2.14%   |
| Validity Sensors VFS491                                                    | 11        | 1.96%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 11        | 1.96%   |
| AuthenTec Fingerprint Sensor                                               | 9         | 1.61%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 8         | 1.43%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 1.43%   |
| Elan ELAN:Fingerprint                                                      | 8         | 1.43%   |
| Upek TCS5B Fingerprint sensor                                              | 7         | 1.25%   |
| Unknown                                                                    | 7         | 1.25%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 1.07%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 1.07%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 1.07%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 0.89%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 0.89%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.54%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 0.54%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 0.36%   |
| Dell MS819 Wired Mouse With Fingerprint Reader                             | 2         | 0.36%   |
| AuthenTec AES1600                                                          | 2         | 0.36%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.18%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.18%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.18%   |
| Upek TouchStrip Fingerprint Sensor                                         | 1         | 0.18%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.18%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 73        | 42.2%   |
| Alcor Micro                       | 27        | 15.61%  |
| Gemalto (was Gemplus)             | 14        | 8.09%   |
| Lenovo                            | 13        | 7.51%   |
| Giesecke & Devrient               | 11        | 6.36%   |
| Upek                              | 8         | 4.62%   |
| Watchdata                         | 6         | 3.47%   |
| Aladdin Knowledge Systems         | 6         | 3.47%   |
| SCM Microsystems                  | 3         | 1.73%   |
| OmniKey                           | 3         | 1.73%   |
| O2 Micro                          | 3         | 1.73%   |
| Chicony Electronics               | 3         | 1.73%   |
| VASCO Data Security International | 1         | 0.58%   |
| Realtek Semiconductor             | 1         | 0.58%   |
| Advanced Card Systems             | 1         | 0.58%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 27        | 15.61%  |
| Broadcom BCM5880 Secure Applications Processor                               | 20        | 11.56%  |
| Broadcom 58200                                                               | 19        | 10.98%  |
| Broadcom 5880                                                                | 18        | 10.4%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 16        | 9.25%   |
| Lenovo Integrated Smart Card Reader                                          | 13        | 7.51%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 13        | 7.51%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 4.62%   |
| Watchdata USB Key                                                            | 6         | 3.47%   |
| Giesecke & Devrient StarSign CUT                                             | 6         | 3.47%   |
| Aladdin Knowledge Systems Token JC                                           | 6         | 3.47%   |
| Giesecke & Devrient StarSign CUT S                                           | 5         | 2.89%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 3         | 1.73%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 2         | 1.16%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 1.16%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 1.16%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.58%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.58%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.58%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.58%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.58%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.58%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.58%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 8761      | 79.91%  |
| 1     | 1930      | 17.6%   |
| 2     | 218       | 1.99%   |
| 3     | 30        | 0.27%   |
| 4     | 16        | 0.15%   |
| 7     | 4         | 0.04%   |
| 8     | 2         | 0.02%   |
| 5     | 2         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 737       | 29.87%  |
| Fingerprint reader       | 556       | 22.54%  |
| Net/wireless             | 315       | 12.77%  |
| Multimedia controller    | 207       | 8.39%   |
| Chipcard                 | 148       | 6%      |
| Communication controller | 97        | 3.93%   |
| Bluetooth                | 82        | 3.32%   |
| Camera                   | 69        | 2.8%    |
| Sound                    | 55        | 2.23%   |
| Unassigned class         | 51        | 2.07%   |
| Storage                  | 37        | 1.5%    |
| Net/ethernet             | 30        | 1.22%   |
| Modem                    | 23        | 0.93%   |
| Flash memory             | 20        | 0.81%   |
| Card reader              | 13        | 0.53%   |
| Network                  | 8         | 0.32%   |
| Storage/ide              | 6         | 0.24%   |
| Firewire controller      | 5         | 0.2%    |
| Storage/raid             | 4         | 0.16%   |
| Video                    | 1         | 0.04%   |
| Storage/nvme             | 1         | 0.04%   |
| Storage/ata              | 1         | 0.04%   |
| Dvb card                 | 1         | 0.04%   |

